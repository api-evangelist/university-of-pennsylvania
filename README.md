# University of Pennsylvania (university-of-pennsylvania)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

The University of Pennsylvania (Penn) is a private Ivy League research university in Philadelphia, ranked #11 in the QS World University Rankings 2025. This repository catalogs Penn's public developer and API footprint as an [APIs.json](https://apisjson.org) provider profile for the API Evangelist network.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-pennsylvania/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-pennsylvania-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Open Data, Courses, Library, United States, Ivy League

## APIs

- **Penn OpenData API** — institutional ESB exposing Registrar, Dining, Directory, Transit, News, Events, Maps, Calendar, and Laundry data (token required; docs gated). Docs: https://pennlabs.org/resources/
- **Penn SDK (Python)** — Penn Labs open-source Python wrapper for OpenData. Docs: https://penn-sdk.readthedocs.io/en/latest/ | https://github.com/pennlabs/penn-sdk-python
- **Penn OpenData Node SDK** — JavaScript/Node SDK for OpenData. Docs: https://penn-sdk.js.org/
- **Penn Courses (PCX) API** — open-source course planning/registration platform; backend uses OpenData. Docs: https://github.com/pennlabs/penn-courses/blob/master/backend/README.md
- **Penn Course Review API** — JSON REST API for course reviews and registrar data. Docs: https://penncoursereview.com/api/documentation/
- **Penn Libraries Open Metadata** — bibliographic catalog metadata via OAI-PMH and Z39.50. Docs: https://www.library.upenn.edu/about/policies/open-metadata

## Plans

See [plans/university-of-pennsylvania-plans-pricing.yml](plans/university-of-pennsylvania-plans-pricing.yml).

## Rate Limits

See [rate-limits/university-of-pennsylvania-rate-limits.yml](rate-limits/university-of-pennsylvania-rate-limits.yml).

## FinOps

See [finops/university-of-pennsylvania-finops.yml](finops/university-of-pennsylvania-finops.yml).

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.upenn.edu/
- GitHub (official): https://github.com/upenn
- Source Code (Penn Labs): https://github.com/pennlabs
- Developer Portal: https://pennlabs.org/resources/
- LinkedIn: https://www.linkedin.com/school/university-of-pennsylvania/

## Notes

- The official **Penn OpenData API** is real but gated — its documentation host (`esb.isc-seo.upenn.edu`) does not resolve from outside the Penn network, and most services require a validated API token. It is cataloged honestly without inventing public endpoints.
- The richest publicly verifiable API surface is maintained by **Penn Labs**, a student-run software organization (not an official university IT property), via open-source SDKs and JSON REST APIs.
- All cataloged docs URLs were probed live on 2026-06-03; the legacy `data.pennlabs.org` demo returned 404 and is noted as such in `review.yml`.

## Maintainers

- Kin Lane — kin@apievangelist.com
