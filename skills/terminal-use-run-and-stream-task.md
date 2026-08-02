---
name: Run a task against an agent and stream results
description: Create a persistent filesystem, start a task against a deployed Terminal Use agent, send it input, and stream the agent's messages back over SSE.
api: openapi/terminal-use-openapi-original.json
operations: [filesystems_create, tasks_create, tasks_send_event, tasks_stream, messages_v2_list, states_retrieve]
---

# Run a task against a Terminal Use agent and stream results

Use this to invoke a deployed agent from your app and read its output.

## Auth
Send `Authorization: Bearer tu_...` on every request (or set `TERMINALUSE_API_KEY`). Base URL: `https://api.terminaluse.com`.

## Steps
1. (Optional) Create a persistent filesystem for the task with **`filesystems_create`** (pass the `project_id`). Reuse an existing filesystem id to share state across tasks.
2. Create the task with **`tasks_create`**, targeting the agent (by `namespace/agent`) and optionally attaching the `filesystem_id` and an initial message.
3. Send additional input to the running task with **`tasks_send_event`**.
4. Stream the agent's messages/events with **`tasks_stream`** (SSE, `GET /tasks/{id}/stream`). For React chat UIs, the `@terminaluse/vercel-ai-sdk-provider` consumes this stream.
5. When not streaming, poll output with **`messages_v2_list`** and read continuity state with **`states_retrieve`**.

## Conventions
- Idempotency: file uploads accept an `Idempotency-Key` header (see `conventions/terminal-use-conventions.yml`).
- Errors: validation failures return HTTP 422 with a `detail[]` envelope; the SDK auto-retries 408/429/5xx (see `errors/terminal-use-problem-types.yml`).
- Pagination: list endpoints accept `limit` (plus offset/cursor on some).
