# University of Pennsylvania (university-of-pennsylvania)

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
