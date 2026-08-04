# Cardiff University (cardiff)

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
