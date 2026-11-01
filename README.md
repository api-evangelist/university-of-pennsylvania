# University of Pennsylvania

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

The University of Pennsylvania (Penn) is a private Ivy League research university in Philadelphia. Penn operates no central developer portal and publishes no institution-wide API program, and the surface that the 2026-06-03 profile treated as its headline API — the Penn OpenData API on the ISC enterprise service bus — is retired: the host esb.isc-seo.upenn.edu no longer resolves and its documentation page returns a soft-404. What Penn genuinely operates is library and identity infrastructure: the PennKey Shibboleth identity provider, whose signed SAML 2.0 metadata resolves live in the InCommon federation; ScholarlyCommons at Penn, a DSpace 7.6 repository on Penn's own domain serving a conformant OAI-PMH 2.0 endpoint over real Penn records; the Franklin catalog and the Colenda digital repository, both Blacklight applications with JSON twins on every page under Penn Libraries' published open-metadata policy; and OPenn, a bulk open-data site of manuscript images and TEI descriptions. The far larger and better known surface — Penn Course Alert, Penn Course Plan, Penn Course Review, Penn Degree Plan and Penn Clubs, with a live 45-path OpenAPI at penncourseplan.com/api/openapi/ — is NOT operated by the university. It is built and run by Penn Labs, a non-profit student-run software organization, on domains registered to Penn Labs. Penn's Office of Student Affairs adopted Penn Clubs as its official student-group registry, which is institutional endorsement of the product, not institutional operation of the API. Those surfaces are recorded here as tenant relationships so the relationship is preserved without crediting Penn for engineering it did not do.

**Areas:** Education · Higher Education · University · Research University · Ivy League · United States · Philadelphia · Open Data · Library · Course Catalog · Research Repository · Identity Federation

## University of Pennsylvania on APIs.io

Everything profiled for University of Pennsylvania is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/university-of-pennsylvania/](https://apis.io/providers/university-of-pennsylvania/)** — or go straight to one of the APIs or properties below.

### APIs (10)

- [Penn Courses API (Penn Course Alert / Plan / Review / Degree Plan)](https://apis.io/apis/university-of-pennsylvania/penn-courses/) — One API, four student-facing products: Penn Course Alert (PCA), Penn Course Plan (PCP), Penn Course Review (PCR) and Penn Degree Plan (PDP), plus a shared…
- [Penn Clubs API](https://apis.io/apis/university-of-pennsylvania/penn-clubs/) — JSON API behind Penn Clubs, the student-organization directory that Penn's Office of Student Affairs adopted as its official student-group registration…
- [Penn SDK (Python)](https://apis.io/apis/university-of-pennsylvania/penn-sdk-python/) — Open-source Python client maintained by Penn Labs wrapping Penn data services. Published documentation at penn-sdk.readthedocs.io returned HTTP 200. An SDK…
- [Penn SDK (JavaScript / Node)](https://apis.io/apis/university-of-pennsylvania/penn-sdk-js/) — Open-source JavaScript/Node client from Penn Labs. Documentation is hosted on js.org, a community subdomain service, at penn-sdk.js.org (HTTP 200) — a…
- [PennKey Identity Provider — SAML 2.0 / Shibboleth Metadata](https://apis.io/apis/university-of-pennsylvania/pennkey-identity-provider/) — Penn's Shibboleth identity provider publishes a signed SAML 2.0 EntityDescriptor at a well-known location (HTTP 200, application/xml, entityID…
- [ScholarlyCommons at Penn — DSpace REST API](https://apis.io/apis/university-of-pennsylvania/scholarlycommons-rest/) — DSpace 7.6 HAL+JSON REST API on Penn's own host. The API root returned HTTP 200 advertising dspaceName "ScholarlyCommons at Penn" and the full DSpace link…
- [Colenda Digital Repository — Search JSON](https://apis.io/apis/university-of-pennsylvania/colenda/) — Penn Libraries' digital repository at colenda.library.upenn.edu exposes a Blacklight/Solr JSON search response (/catalog.json returned HTTP 200, ~59 KB,…
- [OPenn — Open Manuscript Data](https://apis.io/apis/university-of-pennsylvania/openn/) — Penn Libraries' bulk open-data site publishing high-resolution manuscript images and TEI/XML descriptions in the public domain, laid out as a…
- [University of Pennsylvania Catalog API](https://apis.io/apis/university-of-pennsylvania/university-of-pennsylvania-catalog-api/) — Bibliographic search and record retrieval.
- [University of Pennsylvania Request API](https://apis.io/apis/university-of-pennsylvania/university-of-pennsylvania-request-api/) — The Request API from University of Pennsylvania — 1 operation(s) for request.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [University Of Pennsylvania Agentic Access](https://apis.io/agentic-access/university-of-pennsylvania/university-of-pennsylvania-agentic-access/)

#### JSON Schema (3)

The data models the API reads and writes.

- [CourseDetail](https://apis.io/schemas/university-of-pennsylvania/university-of-pennsylvania-course/)
- [Schedule](https://apis.io/schemas/university-of-pennsylvania/university-of-pennsylvania-schedule/)
- [SectionDetail](https://apis.io/schemas/university-of-pennsylvania/university-of-pennsylvania-section/)

#### JSON Structure (2)

Data models expressed in JSON Structure.

- [University Of Pennsylvania Course Structure](https://apis.io/json-structure/university-of-pennsylvania/university-of-pennsylvania-course-structure/)
- [University Of Pennsylvania Section Structure](https://apis.io/json-structure/university-of-pennsylvania/university-of-pennsylvania-section-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [University Of Pennsylvania Context](https://apis.io/jsonld/university-of-pennsylvania/university-of-pennsylvania-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [University of Pennsylvania Penn Courses Vocabulary](https://apis.io/vocabularies/university-of-pennsylvania/university-of-pennsylvania-vocabulary/)

#### Examples (2)

Example requests and responses.

- [University Of Pennsylvania Course Detail Example](https://apis.io/examples/university-of-pennsylvania/university-of-pennsylvania-course-detail-example/)
- [University Of Pennsylvania Section Detail Example](https://apis.io/examples/university-of-pennsylvania/university-of-pennsylvania-section-detail-example/)

#### Collections (25)

Postman and Open Collection request collections.

- [Penn Courses API Documentation [Accounts] User [Accounts] User [Accounts] User API](https://apis.io/collections/university-of-pennsylvania/open-university-of-pennsylvania-accounts-user-api/)
- [Penn Courses API Documentation [Accounts] User [Accounts] User [PCA] Registration API](https://apis.io/collections/university-of-pennsylvania/open-university-of-pennsylvania-pca-registration-api/)
- [Penn Courses API Documentation [Accounts] User [Accounts] User [PCA] Registration History API](https://apis.io/collections/university-of-pennsylvania/open-university-of-pennsylvania-pca-registration-history-api/)
- [Penn Courses API Documentation [Accounts] User [Accounts] User [PCP] Break API](https://apis.io/collections/university-of-pennsylvania/open-university-of-pennsylvania-pcp-break-api/)
- [Penn Courses API Documentation [Accounts] User [Accounts] User [PCP] Calendar API](https://apis.io/collections/university-of-pennsylvania/open-university-of-pennsylvania-pcp-calendar-api/)
- [Penn Courses API Documentation [Accounts] User [Accounts] User [PCP] Course Recommendations API](https://apis.io/collections/university-of-pennsylvania/open-university-of-pennsylvania-pcp-course-recommendations-api/)
- [Penn Courses API Documentation [Accounts] User [Accounts] User [PCP] Primary Schedule API](https://apis.io/collections/university-of-pennsylvania/open-university-of-pennsylvania-pcp-primary-schedule-api/)
- [Penn Courses API Documentation [Accounts] User [Accounts] User [PCP] Schedule API](https://apis.io/collections/university-of-pennsylvania/open-university-of-pennsylvania-pcp-schedule-api/)
- [Penn Courses API Documentation [Accounts] User [Accounts] User [PCR] Autocomplete Dump API](https://apis.io/collections/university-of-pennsylvania/open-university-of-pennsylvania-pcr-autocomplete-dump-api/)
- [Penn Courses API Documentation [Accounts] User [Accounts] User [PCR] Plots API](https://apis.io/collections/university-of-pennsylvania/open-university-of-pennsylvania-pcr-plots-api/)
- [Penn Courses API Documentation [Accounts] User [Accounts] User [PCx] Attributes API](https://apis.io/collections/university-of-pennsylvania/open-university-of-pennsylvania-pcx-attributes-api/)
- [Penn Courses API Documentation [Accounts] User [Accounts] User [PCx] Course API](https://apis.io/collections/university-of-pennsylvania/open-university-of-pennsylvania-pcx-course-api/)
- [Penn Courses API Documentation [Accounts] User [Accounts] User [PCx] Friendship API](https://apis.io/collections/university-of-pennsylvania/open-university-of-pennsylvania-pcx-friendship-api/)
- [Penn Courses API Documentation [Accounts] User [Accounts] User [PCx] Healths API](https://apis.io/collections/university-of-pennsylvania/open-university-of-pennsylvania-pcx-healths-api/)
- [Penn Courses API Documentation [Accounts] User [Accounts] User [PCx] NGSS Restrictions API](https://apis.io/collections/university-of-pennsylvania/open-university-of-pennsylvania-pcx-ngss-restrictions-api/)
- [Penn Courses API Documentation [Accounts] User [Accounts] User [PCx] Pre-NGSS Requirements API](https://apis.io/collections/university-of-pennsylvania/open-university-of-pennsylvania-pcx-pre-ngss-requirements-api/)
- [Penn Courses API Documentation [Accounts] User [Accounts] User [PCx] Section API](https://apis.io/collections/university-of-pennsylvania/open-university-of-pennsylvania-pcx-section-api/)
- [Penn Courses API Documentation [Accounts] User [Accounts] User [PCx] Status Updates API](https://apis.io/collections/university-of-pennsylvania/open-university-of-pennsylvania-pcx-status-updates-api/)
- [Penn Courses API Documentation [Accounts] User [Accounts] User [PDP] Degree API](https://apis.io/collections/university-of-pennsylvania/open-university-of-pennsylvania-pdp-degree-api/)
- [Penn Courses API Documentation [Accounts] User [Accounts] User [PDP] Degree Plan Detail API](https://apis.io/collections/university-of-pennsylvania/open-university-of-pennsylvania-pdp-degree-plan-detail-api/)
- [Penn Courses API Documentation [Accounts] User [Accounts] User [PDP] Degree Plan Lists API](https://apis.io/collections/university-of-pennsylvania/open-university-of-pennsylvania-pdp-degree-plan-lists-api/)
- [Penn Courses API Documentation [Accounts] User [Accounts] User [PDP] Docked Course API](https://apis.io/collections/university-of-pennsylvania/open-university-of-pennsylvania-pdp-docked-course-api/)
- [Penn Courses API Documentation [Accounts] User [Accounts] User [PDP] Fulfillment API](https://apis.io/collections/university-of-pennsylvania/open-university-of-pennsylvania-pdp-fulfillment-api/)
- [Penn Courses API Documentation [Accounts] User [Accounts] User [PDP] Onboard From Transcript API](https://apis.io/collections/university-of-pennsylvania/open-university-of-pennsylvania-pdp-onboard-from-transcript-api/)
- [Penn Courses API Documentation [Accounts] User [Accounts] User [PDP] Satisfied Rule Lists API](https://apis.io/collections/university-of-pennsylvania/open-university-of-pennsylvania-pdp-satisfied-rule-lists-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [University of Pennsylvania — jsonschema rules](https://apis.io/rules/university-of-pennsylvania/university-of-pennsylvania-jsonschema-spectral-rules/)
- [University of Pennsylvania API Rules](https://apis.io/rules/university-of-pennsylvania/university-of-pennsylvania-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [University Of Pennsylvania Authentication](https://apis.io/security/university-of-pennsylvania/university-of-pennsylvania-authentication/)
- [University Of Pennsylvania Domain Security](https://apis.io/security/university-of-pennsylvania/university-of-pennsylvania-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [University Of Pennsylvania Plans Pricing](https://apis.io/plans/university-of-pennsylvania/university-of-pennsylvania-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [University Of Pennsylvania Rate Limits](https://apis.io/rate-limits/university-of-pennsylvania/university-of-pennsylvania-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [University Of Pennsylvania Finops](https://apis.io/finops/university-of-pennsylvania/university-of-pennsylvania-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.upenn.edu/)
- [Documentation](https://pennlabs.org/resources/)
- [Blog](https://penntoday.upenn.edu/rss.xml)
- [Privacy policy](https://www.upenn.edu/about/privacy-policy)
- [GitHub](https://github.com/upenn)

## API Evangelist rating

**Kin Score 31.0** — thin · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 50.3 |
| Contract governance | 13.6 |
| Operational transparency | 7.9 |
| Developer ergonomics | 19.0 |
| Access clarity | 26.3 |

**Agent readiness 20.0** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | paginated |
| Operation Distinctiveness | distinct |

**Regulatory alignment 18.6** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/university-of-pennsylvania/](https://apis.io/providers/university-of-pennsylvania/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for University of Pennsylvania: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/university-of-pennsylvania/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
