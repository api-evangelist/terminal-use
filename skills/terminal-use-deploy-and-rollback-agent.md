---
name: Deploy an agent and roll back a bad version
description: Deploy a new agent version to a branch/environment, inspect the branch's active version, and roll back to an earlier version if needed.
api: openapi/terminal-use-openapi-original.json
operations: [deploy, agents_retrieve, agents_list_versions, branches_retrieve, branches_rollback]
---

# Deploy a Terminal Use agent and roll back

Manage the build/deploy loop over the HTTP API (the `tu deploy` / `tu rollback` CLI wraps these).

## Auth
`Authorization: Bearer tu_...`. Base URL `https://api.terminaluse.com`.

## Steps
1. Deploy a new build with **`deploy`** — this creates a new immutable Version and activates it on the resolved branch/environment.
2. Confirm the agent and its current version with **`agents_retrieve`**, and enumerate builds with **`agents_list_versions`**.
3. Inspect the branch's active version with **`branches_retrieve`**.
4. If the new version is bad, restore service with **`branches_rollback`** to point the branch back at an earlier Version.

## Notes
- Each `deploy` is immutable; rollback is a pointer change on the branch, not a rebuild (see `lifecycle/terminal-use-lifecycle.yml`).
- Tasks are created against a specific version, so in-flight tasks are unaffected by a branch pointer change.
- Errors: 422 validation envelope; 409 on conflicts. See `errors/terminal-use-problem-types.yml`.
