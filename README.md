# Cardiff University (cardiff)

Cardiff University is a public research university in Cardiff, Wales, United Kingdom, ranked #186 in the QS World University Rankings 2025. It operates a public developer portal at [data.cardiff.ac.uk](https://data.cardiff.ac.uk/devportal/) (powered by WSO2 API Manager) exposing a small set of OAuth2-secured RESTful institutional APIs for courses, modules, lookups, and research publications, served from the gateway at `api.data.cardiff.ac.uk`.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/cardiff/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=cardiff-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, United Kingdom, Wales, Open Data, Courses, Research

## APIs

- **Courses** — Lists of courses and course details, filterable by school, language, level and year. [Docs](https://data.cardiff.ac.uk/devportal/apis/1353914a-a34a-4fb5-85ac-ef06dda0bf2b) · `https://api.data.cardiff.ac.uk/courses/v1`
- **Modules** — Academic module information. [Docs](https://data.cardiff.ac.uk/devportal/apis/e1345fea-99ae-4b42-8a0a-06b321ce5137) · `https://api.data.cardiff.ac.uk/modules/v1`
- **Lookups** — Reference/lookup code lists used across the institutional APIs. [Docs](https://data.cardiff.ac.uk/devportal/apis/80738ed1-f656-45ef-ac30-df693142f8ed) · `https://api.data.cardiff.ac.uk/lookups/v1`
- **Publications** — Lists of research publications and publication details. [Docs](https://data.cardiff.ac.uk/devportal/apis/32d23956-5638-423f-8be2-01f583c407a3) · `https://api.data.cardiff.ac.uk/publications/v1`
- **EchoTest** — Connectivity/credential test utility. [Docs](https://data.cardiff.ac.uk/devportal/apis/157609f4-814a-4cac-aaac-384f700b64ea) · `https://api.data.cardiff.ac.uk/echo/v1`

All APIs are OAuth2-secured. Integration requires creating an application and generating consumer keys and access tokens; external developers request access by emailing integration@cardiff.ac.uk.

## Plans, Rate Limits & FinOps

- [Plans & Pricing](plans/cardiff-plans-pricing.yml)
- [Rate Limits](rate-limits/cardiff-rate-limits.yml)
- [FinOps](finops/cardiff-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.cardiff.ac.uk/
- Developer Portal: https://data.cardiff.ac.uk/devportal/
- Authentication: https://data.cardiff.ac.uk/devportal/
- LinkedIn: https://www.linkedin.com/school/cardiff-university/

## Notes

- The five APIs were confirmed live via the portal's anonymous catalog endpoint (`/api/am/devportal/v2/apis`), which returned `count=5`. No endpoints were fabricated.
- A direct call to a gateway endpoint returned HTTP 401, confirming the APIs are gated by OAuth2 rather than openly accessible.
- The marketing landing page (data.cardiff.ac.uk root), the official website, and the ORCA EPrints repository bot-block automated requests (HTTP 403) but are reachable in a browser. ORCA OAI-PMH could not be verified via automated probe and is therefore not cataloged.
- No official Cardiff University GitHub organization was confirmed; the university uses a self-hosted GitLab at git.cardiff.ac.uk.

## Maintainers

- Kin Lane — kin@apievangelist.com
