---
name: Provision a namespace, project, and API key
description: Stand up a new Terminal Use tenancy — check and create a namespace, create a project for filesystem access control, and mint a scoped API key.
api: openapi/terminal-use-openapi-original.json
operations: [namespaces_check_slug_availability, namespaces_create, projects_create, api_keys_create, api_keys_update_scopes]
---

# Provision a Terminal Use namespace, project, and API key

Onboarding flow for a new team or customer tenancy.

## Auth
`Authorization: Bearer tu_...`. Base URL `https://api.terminaluse.com`.

## Steps
1. Check the desired namespace slug with **`namespaces_check_slug_availability`**.
2. Create the isolation boundary with **`namespaces_create`** (compute + storage isolation).
3. Create a **`projects_create`** project inside the namespace — projects are the permission boundary for filesystems, useful for per-customer or per-workflow access control.
4. Mint credentials with **`api_keys_create`**, then narrow permissions with **`api_keys_update_scopes`**.

## Notes
- Keep the three key types distinct: API keys call the API, webhook keys verify inbound webhooks, environment secrets configure deployed agents (see `authentication/terminal-use-authentication.yml`).
- Namespace provisioning is asynchronous; retry with `namespaces_retry_provisioning` if provisioning stalls.
