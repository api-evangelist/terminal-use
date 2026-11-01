# Terminal Use

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Terminal Use is a deployment and orchestration platform for background AI agents — "Vercel for background agents." It gives agents that need long-lived task state, persistent files at /workspace, and production deployment primitives (versions, rollback, logs, environment secrets) a single runtime model and one deploy flow. Teams write agent code in Python with the AgentServer runtime, ship it with the tu CLI, then call deployed agents from their own app with the Python or TypeScript SDKs (including a Vercel AI SDK provider for streaming chat UIs). The platform is model- and framework- agnostic — run the Claude Agent SDK, Codex SDK, or your own framework inside sandboxed compute with forkable, shareable filesystems. The HTTP API exposes namespaces, projects, agents, branches, versions, tasks, events, messages, state, filesystems, schedules, secrets, API keys, and webhook keys. Terminal Use is a Y Combinator (W26) company founded by Vivek Raja, Filip Balucha, and Stavros Filosidis.

**Areas:** Company · Agents · AI Agents · Background Agents · Agent Infrastructure · Deployment · Orchestration · Sandboxed Compute · Filesystem · Developer Tools · SDK · CLI

## Terminal Use on APIs.io

Everything profiled for Terminal Use is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/terminal-use/](https://apis.io/providers/terminal-use/)** — or go straight to one of the APIs or properties below.

### APIs (28)

- [Terminal Use Agent APIKeys API](https://apis.io/apis/terminal-use/terminal-use-agent-apikeys-api/) — The Agent APIKeys API from Terminal Use — 4 operation(s) for agent apikeys.
- [Terminal Use Agent Task Tracker API](https://apis.io/apis/terminal-use/terminal-use-agent-task-tracker-api/) — The Agent Task Tracker API from Terminal Use — 2 operation(s) for agent task tracker.
- [Terminal Use Agents API](https://apis.io/apis/terminal-use/terminal-use-agents-api/) — The Agents API from Terminal Use — 7 operation(s) for agents.
- [Terminal Use API Keys API](https://apis.io/apis/terminal-use/terminal-use-api-keys-api/) — The API Keys API from Terminal Use — 3 operation(s) for api keys.
- [Terminal Use Authentication API](https://apis.io/apis/terminal-use/terminal-use-authentication-api/) — The Authentication API from Terminal Use — 1 operation(s) for authentication.
- [Terminal Use Branch Events API](https://apis.io/apis/terminal-use/terminal-use-branch-events-api/) — The Branch Events API from Terminal Use — 1 operation(s) for branch events.
- [Terminal Use Branches API](https://apis.io/apis/terminal-use/terminal-use-branches-api/) — The Branches API from Terminal Use — 10 operation(s) for branches.
- [Terminal Use Builds API](https://apis.io/apis/terminal-use/terminal-use-builds-api/) — The Builds API from Terminal Use — 3 operation(s) for builds.
- [Terminal Use CLI Authentication API](https://apis.io/apis/terminal-use/terminal-use-cli-authentication-api/) — The CLI Authentication API from Terminal Use — 2 operation(s) for cli authentication.
- [Terminal Use Environments API](https://apis.io/apis/terminal-use/terminal-use-environments-api/) — The Environments API from Terminal Use — 4 operation(s) for environments.
- [Terminal Use Events API](https://apis.io/apis/terminal-use/terminal-use-events-api/) — The Events API from Terminal Use — 2 operation(s) for events.
- [Terminal Use Filesystems API](https://apis.io/apis/terminal-use/terminal-use-filesystems-api/) — The Filesystems API from Terminal Use — 9 operation(s) for filesystems.
- [Terminal Use Groups API](https://apis.io/apis/terminal-use/terminal-use-groups-api/) — The Groups API from Terminal Use — 8 operation(s) for groups.
- [Terminal Use Logs API](https://apis.io/apis/terminal-use/terminal-use-logs-api/) — The Logs API from Terminal Use — 3 operation(s) for logs.
- [Terminal Use Messages v2 API](https://apis.io/apis/terminal-use/terminal-use-messages-v2-api/) — The Messages v2 API from Terminal Use — 2 operation(s) for messages v2.
- [Terminal Use Namespaces API](https://apis.io/apis/terminal-use/terminal-use-namespaces-api/) — The Namespaces API from Terminal Use — 5 operation(s) for namespaces.
- [Terminal Use Organizations API](https://apis.io/apis/terminal-use/terminal-use-organizations-api/) — The Organizations API from Terminal Use — 7 operation(s) for organizations.
- [Terminal Use Projects API](https://apis.io/apis/terminal-use/terminal-use-projects-api/) — The Projects API from Terminal Use — 4 operation(s) for projects.
- [Terminal Use Raw Events API](https://apis.io/apis/terminal-use/terminal-use-raw-events-api/) — The Raw Events API from Terminal Use — 1 operation(s) for raw events.
- [Terminal Use Registry API](https://apis.io/apis/terminal-use/terminal-use-registry-api/) — The Registry API from Terminal Use — 1 operation(s) for registry.
- [Terminal Use Schedules API](https://apis.io/apis/terminal-use/terminal-use-schedules-api/) — The Schedules API from Terminal Use — 5 operation(s) for schedules.
- [Terminal Use Search API](https://apis.io/apis/terminal-use/terminal-use-search-api/) — The Search API from Terminal Use — 1 operation(s) for search.
- [Terminal Use Secrets API](https://apis.io/apis/terminal-use/terminal-use-secrets-api/) — The Secrets API from Terminal Use — 4 operation(s) for secrets.
- [Terminal Use States API](https://apis.io/apis/terminal-use/terminal-use-states-api/) — The States API from Terminal Use — 2 operation(s) for states.
- [Terminal Use Tasks API](https://apis.io/apis/terminal-use/terminal-use-tasks-api/) — The Tasks API from Terminal Use — 14 operation(s) for tasks.
- [Terminal Use Version Events API](https://apis.io/apis/terminal-use/terminal-use-version-events-api/) — The Version Events API from Terminal Use — 1 operation(s) for version events.
- [Terminal Use Versions API](https://apis.io/apis/terminal-use/terminal-use-versions-api/) — The Versions API from Terminal Use — 6 operation(s) for versions.
- [Terminal Use O Auth API](https://apis.io/apis/terminal-use/terminal-use-oauth-api/) — The OAuth API from Terminal Use — 2 operation(s) for oauth.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Terminal Use Webhooks](https://apis.io/asyncapis/terminal-use/terminal-use-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [terminal-use](https://apis.io/servers/terminal-use/terminal-use/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Terminal Use Agentic Access](https://apis.io/agentic-access/terminal-use/terminal-use-agentic-access/)

#### Collections (28)

Postman and Open Collection request collections.

- [Sb0 Agent APIKeys API](https://apis.io/collections/terminal-use/open-terminal-use-agent-apikeys-api/)
- [Sb0 Agent APIKeys Agent Task Tracker API](https://apis.io/collections/terminal-use/open-terminal-use-agent-task-tracker-api/)
- [Sb0 Agent APIKeys Agents API](https://apis.io/collections/terminal-use/open-terminal-use-agents-api/)
- [Sb0 Agent APIKeys API Keys API](https://apis.io/collections/terminal-use/open-terminal-use-api-keys-api/)
- [Sb0 Agent APIKeys Authentication API](https://apis.io/collections/terminal-use/open-terminal-use-authentication-api/)
- [Sb0 Agent APIKeys Branch Events API](https://apis.io/collections/terminal-use/open-terminal-use-branch-events-api/)
- [Sb0 Agent APIKeys Branches API](https://apis.io/collections/terminal-use/open-terminal-use-branches-api/)
- [Sb0 Agent APIKeys Builds API](https://apis.io/collections/terminal-use/open-terminal-use-builds-api/)
- [Sb0 Agent APIKeys CLI Authentication API](https://apis.io/collections/terminal-use/open-terminal-use-cli-authentication-api/)
- [Sb0 Agent APIKeys Environments API](https://apis.io/collections/terminal-use/open-terminal-use-environments-api/)
- [Sb0 Agent APIKeys Events API](https://apis.io/collections/terminal-use/open-terminal-use-events-api/)
- [Sb0 Agent APIKeys Filesystems API](https://apis.io/collections/terminal-use/open-terminal-use-filesystems-api/)
- [Sb0 Agent APIKeys Groups API](https://apis.io/collections/terminal-use/open-terminal-use-groups-api/)
- [Sb0 Agent APIKeys Logs API](https://apis.io/collections/terminal-use/open-terminal-use-logs-api/)
- [Sb0 Agent APIKeys Messages v2 API](https://apis.io/collections/terminal-use/open-terminal-use-messages-v2-api/)
- [Sb0 Agent APIKeys Namespaces API](https://apis.io/collections/terminal-use/open-terminal-use-namespaces-api/)
- [Sb0 Agent APIKeys OAuth API](https://apis.io/collections/terminal-use/open-terminal-use-oauth-api/)
- [Sb0 Agent APIKeys Organizations API](https://apis.io/collections/terminal-use/open-terminal-use-organizations-api/)
- [Sb0 Agent APIKeys Projects API](https://apis.io/collections/terminal-use/open-terminal-use-projects-api/)
- [Sb0 Agent APIKeys Raw Events API](https://apis.io/collections/terminal-use/open-terminal-use-raw-events-api/)
- [Sb0 Agent APIKeys Registry API](https://apis.io/collections/terminal-use/open-terminal-use-registry-api/)
- [Sb0 Agent APIKeys Schedules API](https://apis.io/collections/terminal-use/open-terminal-use-schedules-api/)
- [Sb0 Agent APIKeys Search API](https://apis.io/collections/terminal-use/open-terminal-use-search-api/)
- [Sb0 Agent APIKeys Secrets API](https://apis.io/collections/terminal-use/open-terminal-use-secrets-api/)
- [Sb0 Agent APIKeys States API](https://apis.io/collections/terminal-use/open-terminal-use-states-api/)
- …and 3 more published on APIs.io

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Terminal Use Openapi Overlay](https://apis.io/overlays/terminal-use/terminal-use-openapi-overlay/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Terminal Use Authentication](https://apis.io/security/terminal-use/terminal-use-authentication/)
- [Terminal Use Domain Security](https://apis.io/security/terminal-use/terminal-use-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.terminaluse.com)
- [Documentation](https://docs.terminaluse.com)
- [Getting started](https://docs.terminaluse.com/introduction/quickstart)
- [API reference](https://docs.terminaluse.com/api-reference/authentication)
- [Sign up](https://app.terminaluse.com)
- [GitHub](https://github.com/terminal-use)

## API Evangelist rating

**Kin Score 41.5** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 51.4 |
| Contract governance | 4.5 |
| Operational transparency | 10.5 |
| Developer ergonomics | 66.1 |
| Access clarity | 0.0 |

**Agent readiness 40.6** — agent-native

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | verified |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | — |
| Event Surface Described | yes |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | distinct |

**Regulatory alignment 16.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/terminal-use/](https://apis.io/providers/terminal-use/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Terminal Use: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/terminal-use/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
