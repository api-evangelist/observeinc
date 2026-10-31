# Observe

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

Observe (Observe, Inc., now "Observe by Snowflake" following its acquisition by Snowflake; www.observeinc.com redirects to snowflake.com/en/product/observe) is an observability platform for logs, metrics, traces and APM built on a data lake and the OPAL query language. Its developer surface lives on docs.observeinc.com: a tenant-scoped REST API (https://{customerid}.observeinc.com/v1, bearer "<customerid> <token>") covering monitors, datasets, ingest and API tokens, reference tables, service accounts and query export, with date-based Observe-Api-Version response versioning; a read-only Apache Iceberg REST Catalog endpoint; a tenant MCP server; a CLI; and a Terraform provider. Snowflake's own APIs are not credited here.

**Areas:** Company · Observability · Monitoring · Logs · Metrics · Traces · APM · Snowflake

## Observe on APIs.io

Everything profiled for Observe is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/observeinc/](https://apis.io/providers/observeinc/)** — or go straight to one of the APIs or properties below.

### APIs (22)

- [Observe Apache Iceberg REST Catalog API](https://apis.io/apis/observeinc/iceberg-rest-catalog/) — Read-only subset of the Apache Iceberg REST Catalog protocol served under /v1/iceberg/catalog on each Observe tenant, authenticated with the same Observe…
- [Observe Alert API](https://apis.io/apis/observeinc/observeinc-alert-api/) — Query monitor alerts. Learn more about [alerts](https://docs.observeinc.com/docs/work-with-alerts).
- [Observe APM API](https://apis.io/apis/observeinc/observeinc-apm-api/) — The APM API from Observe — 3 operation(s) for apm.
- [Observe Dashboards API](https://apis.io/apis/observeinc/observeinc-dashboards-api/) — The Dashboards API from Observe — 2 operation(s) for dashboards.
- [Observe Dataset API](https://apis.io/apis/observeinc/observeinc-dataset-api/) — Manage datasets. Learn more about [datasets](https://docs.observeinc.com/en/latest/content/reference/ObserveKeyConcepts.html#datasets)..
- [Observe Dataset Legacy API](https://apis.io/apis/observeinc/observeinc-dataset-legacy-api/) — Legacy dataset endpoints. Will be deprecated in the future.
- [Observe Dataset Query Filter API](https://apis.io/apis/observeinc/observeinc-dataset-query-filter-api/) — Manage dataset query filters. Learn more about [dataset query filters](https://docs.observeinc.com/docs/dataset-query-filters).
- [Observe Documentation API](https://apis.io/apis/observeinc/observeinc-documentation-api/) — Semantic search across Observe's built-in documentation.
- [Observe Drop Filters API](https://apis.io/apis/observeinc/observeinc-drop-filters-api/) — Manage drop filters used to reduce ingest volume by dropping a configurable fraction of observations matching an OPAL predicate. Learn more about [drop…
- [Observe Export API](https://apis.io/apis/observeinc/observeinc-export-api/) — Export query results from Observe.
- [Observe Ingest Routes API](https://apis.io/apis/observeinc/observeinc-ingest-routes-api/) — The Ingest Routes API from Observe — 2 operation(s) for ingest routes.
- [Observe Ingest Tokens API](https://apis.io/apis/observeinc/observeinc-ingest-tokens-api/) — The Ingest Tokens API from Observe — 2 operation(s) for ingest tokens.
- [Observe Login API](https://apis.io/apis/observeinc/observeinc-login-api/) — Manage api tokens. Learn more about [api tokens](https://docs.observeinc.com/en/latest/content/reference/ObserveAPIAuth.html).
- [Observe Metrics API](https://apis.io/apis/observeinc/observeinc-metrics-api/) — The Metrics API from Observe — 1 operation(s) for metrics.
- [Observe Monitor API](https://apis.io/apis/observeinc/observeinc-monitor-api/) — Manage monitors. Learn more about [monitors](https://docs.observeinc.com/en/latest/content/monitors/MonitorsIntro.html).
- [Observe Monitor Mute API](https://apis.io/apis/observeinc/observeinc-monitormute-api/) — Manage monitor mute rules. Mute rules suppress alert notifications for one or more monitors during a defined time window. Learn more about [monitor mute…
- [Observe Object Tags API](https://apis.io/apis/observeinc/observeinc-objecttags-api/) — Search for object tags on objects such as dashboards, datasets, worksheets, etc.
- [Observe Reference Tables API](https://apis.io/apis/observeinc/observeinc-referencetables-api/) — Manage reference tables. Learn more about [reference tables](https://docs.observeinc.com/en/latest/content/reference/ReferenceTables.html).
- [Observe Skills API](https://apis.io/apis/observeinc/observeinc-skills-api/) — Manage custom AI agent skills for the AI-SRE agent.
- [Observe Tags API](https://apis.io/apis/observeinc/observeinc-tags-api/) — The Tags API from Observe — 1 operation(s) for tags.
- [Observe Service Accounts API](https://apis.io/apis/observeinc/observeinc-service-accounts-api/) — Manage service accounts and api tokens. Learn more about service accounts.
- [Observe Tag Values API](https://apis.io/apis/observeinc/observeinc-tag-values-api/) — The Tag Values API from Observe — 1 operation(s) for tag values.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [Observe by Snowflake MCP Server](https://apis.io/servers/observeinc/observe-by-snowflake-mcp-server/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Observeinc Agentic Access](https://apis.io/agentic-access/observeinc/observeinc-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [AlertResource](https://apis.io/schemas/observeinc/observeinc-alert-resource/)
- [DatasetQueryFilter](https://apis.io/schemas/observeinc/observeinc-dataset-query-filter-resource/)
- [DatasetResource](https://apis.io/schemas/observeinc/observeinc-dataset-resource/)
- [IngestFiltersObject](https://apis.io/schemas/observeinc/observeinc-ingest-filters-resource/)
- [IngestRoutesObject](https://apis.io/schemas/observeinc/observeinc-ingest-routes-resource/)
- [MonitorResource](https://apis.io/schemas/observeinc/observeinc-monitor-resource/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Observeinc Context](https://apis.io/jsonld/observeinc/observeinc-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Observe API Rules](https://apis.io/rules/observeinc/observeinc-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Observeinc Authentication](https://apis.io/security/observeinc/observeinc-authentication/)
- [Observeinc Domain Security](https://apis.io/security/observeinc/observeinc-domain-security/)

#### Rate limits (1)

Published request limits.

- [Observeinc Rate Limits](https://apis.io/rate-limits/observeinc/observeinc-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.observeinc.com)
- [Documentation](https://docs.observeinc.com/)
- [Getting started](https://docs.observeinc.com/docs/google-cloud-platform-quickstart-1)
- [API reference](https://docs.observeinc.com/reference/how-you-can-interact-with-the-observe-api)
- [Pricing](https://www.snowflake.com/en/pricing-options/)
- [Sign up](https://signup.snowflake.com/)
- [Support](https://www.snowflake.com/en/support/)
- [Blog](https://www.snowflake.com/en/blog/product-and-technology/?tags=blog%2Fproduct-and-technology%2Fobservability)
- [Trust centre](https://trust.snowflake.com/)
- [Terms of service](https://www.observeinc.com/legal/terms-of-service)
- [Privacy policy](https://www.snowflake.com/en/legal/privacy/privacy-policy/)
- [GitHub](https://github.com/observeinc)
- [Status](https://status.snowflake.com/)

## API Evangelist rating

**Kin Score 63.0** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 76.7 |
| Contract quality | 68.1 |
| Contract governance | 22.0 |
| Operational transparency | 86.8 |
| Developer ergonomics | 61.9 |
| Access clarity | 52.6 |

**Agent readiness 44.8** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | distinct |

**Regulatory alignment 29.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/observeinc/](https://apis.io/providers/observeinc/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Observe: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/observeinc/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
