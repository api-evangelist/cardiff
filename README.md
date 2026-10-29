# Cardiff University

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

Cardiff University is a public research university in Cardiff, Wales, and a member of the Russell Group. Unusually for a UK institution it operates its own API gateway rather than only buying one: api.data.cardiff.ac.uk runs WSO2 API Manager under the University's own registrable domain and serves five institution-authored REST contracts - Courses, Modules, Lookups, Publications and an Echo connectivity test - published through a developer portal at data.cardiff.ac.uk/devportal. Access is OAuth2 client-credentials and is not open self-serve: external developers must email integration@cardiff.ac.uk with a use case before an application can be created. As of a probe on 2026-08-30 both data.cardiff.ac.uk and api.data.cardiff.ac.uk 302-redirect every path to the University's service-unavailable page at outage.cf.ac.uk, so nothing on the gateway is callable from outside at this moment; the contracts in this repository were harvested while it was up. Beyond the gateway, Cardiff's genuinely institution-operated machine-readable surfaces are its Shibboleth identity federation membership (a registered UK Access Management Federation IdP), the OAI-PMH interface of its own EPrints repository ORCA, its DataCite repository client and DOI prefix 10.17035, and the ARCCA research-computing GitHub organisation. Its research data repository, research portal and library discovery layer are vendor platforms running under Cardiff subdomains - Figshare, Clarivate Converis and Ex Libris respectively - and are recorded here as tenant relationships, not as Cardiff's engineering.

**Areas:** Education · Higher Education · University · Public Research University · United Kingdom · Wales · Russell Group · Open Data · Course Catalog · Research Repository · Identity Federation · Research Computing

## Cardiff University on APIs.io

Everything profiled for Cardiff University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/cardiff/](https://apis.io/providers/cardiff/)** — or go straight to one of the APIs or properties below.

### APIs (21)

- [Cardiff University Courses API](https://apis.io/apis/cardiff/cardiff-courses-api/) — Course records, descriptions and structure for taught programmes. 4 operation(s), from Cardiff's own CoursesApi contract on the api.data.cardiff.ac.uk…
- [Cardiff University Clearing Adjustments API](https://apis.io/apis/cardiff/cardiff-clearing-adjustments-api/) — Clearing and adjustment availability against the course catalogue. 1 operation(s), from Cardiff's own CoursesApi contract on the api.data.cardiff.ac.uk…
- [Cardiff University Groups API](https://apis.io/apis/cardiff/cardiff-groups-api/) — Course grouping records exposed by the Courses contract. 1 operation(s), from Cardiff's own CoursesApi contract on the api.data.cardiff.ac.uk gateway (base…
- [Cardiff University Modules API](https://apis.io/apis/cardiff/cardiff-modules-api/) — Module records and module catalogues for taught modules. 5 operation(s), from Cardiff's own ModulesApi contract on the api.data.cardiff.ac.uk gateway (base…
- [Cardiff University Assessments API](https://apis.io/apis/cardiff/cardiff-assessments-api/) — Assessments attached to a module, filterable by academic year. 1 operation(s), from Cardiff's own ModulesApi contract on the api.data.cardiff.ac.uk gateway…
- [Cardiff University Occurrences API](https://apis.io/apis/cardiff/cardiff-occurrences-api/) — Module occurrences, including the VLE (learn) occurrence records. 4 operation(s), from Cardiff's own ModulesApi contract on the api.data.cardiff.ac.uk…
- [Cardiff University Rollover API](https://apis.io/apis/cardiff/cardiff-rollover-api/) — Year-on-year module rollover mapping. 2 operation(s), from Cardiff's own ModulesApi contract on the api.data.cardiff.ac.uk gateway (base path /modules/v1).
- [Cardiff University Schools API](https://apis.io/apis/cardiff/cardiff-schools-api/) — Reference list of academic schools used across the University. 1 operation(s), from Cardiff's own LookupsApi contract on the api.data.cardiff.ac.uk gateway…
- [Cardiff University Subjects API](https://apis.io/apis/cardiff/cardiff-subjects-api/) — Reference list of subject codes. 1 operation(s), from Cardiff's own LookupsApi contract on the api.data.cardiff.ac.uk gateway (base path /lookups/v1).
- [Cardiff University Levels API](https://apis.io/apis/cardiff/cardiff-levels-api/) — Reference list of study levels. 1 operation(s), from Cardiff's own LookupsApi contract on the api.data.cardiff.ac.uk gateway (base path /lookups/v1).
- [Cardiff University Semesters API](https://apis.io/apis/cardiff/cardiff-semesters-api/) — Reference list of semester codes. 1 operation(s), from Cardiff's own LookupsApi contract on the api.data.cardiff.ac.uk gateway (base path /lookups/v1).
- [Cardiff University Qualifications API](https://apis.io/apis/cardiff/cardiff-qualifications-api/) — Reference list of qualification codes. 1 operation(s), from Cardiff's own LookupsApi contract on the api.data.cardiff.ac.uk gateway (base path /lookups/v1).
- [Cardiff University Years API](https://apis.io/apis/cardiff/cardiff-years-api/) — Reference list of academic years. 1 operation(s), from Cardiff's own LookupsApi contract on the api.data.cardiff.ac.uk gateway (base path /lookups/v1).
- [Cardiff University Publications API](https://apis.io/apis/cardiff/cardiff-publications-api/) — Research publication records, keyed on the ORCA EPrints identifier. 2 operation(s), from Cardiff's own PublicationsApi contract on the…
- [Cardiff University Echo Default API](https://apis.io/apis/cardiff/cardiff-default-api/) — Gateway connectivity-test catch-all path. 1 operation(s), from Cardiff's own EchoTest contract on the api.data.cardiff.ac.uk gateway (base path /echo/v1).
- [Cardiff University Echo Test API](https://apis.io/apis/cardiff/cardiff-test-api/) — Gateway connectivity-test endpoint. 1 operation(s), from Cardiff's own EchoTest contract on the api.data.cardiff.ac.uk gateway (base path /echo/v1).
- [ORCA OAI-PMH Interface](https://apis.io/apis/cardiff/cardiff-orca-oai-pmh/) — Online Research @ Cardiff (ORCA) is Cardiff University's own EPrints institutional repository, listed as an IT service the University runs. Its OAI-PMH…
- [Cardiff University IT Status API](https://apis.io/apis/cardiff/cardiff-status-api/) — Cardiff University publishes IT service status on an Atlassian Statuspage at status.cardiff.ac.uk, which carries the standard Statuspage v2 JSON API.…
- [Cardiff University Research Data Repository (Figshare tenancy)](https://apis.io/apis/cardiff/cardiff-research-data-repository/) — Cardiff's research data repository at research-data.cardiff.ac.uk is a Figshare for Institutions instance - the host CNAMEs to proxy-eu-01.figshare.com, and…
- [Cardiff University Research Portal (Converis tenancy)](https://apis.io/apis/cardiff/cardiff-research-portal/) — research.cardiff.ac.uk is Cardiff's research information system, running on Clarivate Converis - the host CNAMEs to cu.converis.clarivate.com and the…
- [Cardiff LibrarySearch (Ex Libris Primo tenancy)](https://apis.io/apis/cardiff/cardiff-librarysearch/) — librarysearch.cardiff.ac.uk is Cardiff's discovery layer, an Ex Libris Primo view (vid=44WHELF_CAR:CAR) sitting on the WHELF shared Alma library management…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Cardiff Agentic Access](https://apis.io/agentic-access/cardiff/cardiff-agentic-access/)

#### JSON Schema (4)

The data models the API reads and writes.

- [Course](https://apis.io/schemas/cardiff/cardiff-course/)
- [Meta](https://apis.io/schemas/cardiff/cardiff-meta/)
- [Module](https://apis.io/schemas/cardiff/cardiff-module/)
- [Publication](https://apis.io/schemas/cardiff/cardiff-publication/)

#### JSON Structure (3)

Data models expressed in JSON Structure.

- [Cardiff Course Structure](https://apis.io/json-structure/cardiff/cardiff-course-structure/)
- [Cardiff Module Structure](https://apis.io/json-structure/cardiff/cardiff-module-structure/)
- [Cardiff Publication Structure](https://apis.io/json-structure/cardiff/cardiff-publication-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Cardiff Context](https://apis.io/jsonld/cardiff/cardiff-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Cardiff University API Vocabulary](https://apis.io/vocabularies/cardiff/cardiff-vocabulary/)

#### Examples (4)

Example requests and responses.

- [Cardiff Courses List Example](https://apis.io/examples/cardiff/cardiff-courses-list-example/)
- [Cardiff Lookups Schools Example](https://apis.io/examples/cardiff/cardiff-lookups-schools-example/)
- [Cardiff Modules List Example](https://apis.io/examples/cardiff/cardiff-modules-list-example/)
- [Cardiff Publications List Example](https://apis.io/examples/cardiff/cardiff-publications-list-example/)

#### Collections (16)

Postman and Open Collection request collections.

- [CoursesApi Assessments API](https://apis.io/collections/cardiff/open-cardiff-assessments-api/)
- [CoursesApi Assessments Clearing Adjustments API](https://apis.io/collections/cardiff/open-cardiff-clearing-adjustments-api/)
- [CoursesApi Assessments Courses API](https://apis.io/collections/cardiff/open-cardiff-courses-api/)
- [CoursesApi Assessments * API](https://apis.io/collections/cardiff/open-cardiff-default-api/)
- [CoursesApi Assessments Groups API](https://apis.io/collections/cardiff/open-cardiff-groups-api/)
- [CoursesApi Assessments Levels API](https://apis.io/collections/cardiff/open-cardiff-levels-api/)
- [CoursesApi Assessments Modules API](https://apis.io/collections/cardiff/open-cardiff-modules-api/)
- [CoursesApi Assessments Occurrences API](https://apis.io/collections/cardiff/open-cardiff-occurrences-api/)
- [CoursesApi Assessments Publications API](https://apis.io/collections/cardiff/open-cardiff-publications-api/)
- [CoursesApi Assessments Qualifications API](https://apis.io/collections/cardiff/open-cardiff-qualifications-api/)
- [CoursesApi Assessments Rollover API](https://apis.io/collections/cardiff/open-cardiff-rollover-api/)
- [CoursesApi Assessments Schools API](https://apis.io/collections/cardiff/open-cardiff-schools-api/)
- [CoursesApi Assessments Semesters API](https://apis.io/collections/cardiff/open-cardiff-semesters-api/)
- [CoursesApi Assessments Subjects API](https://apis.io/collections/cardiff/open-cardiff-subjects-api/)
- [CoursesApi Assessments Test API](https://apis.io/collections/cardiff/open-cardiff-test-api/)
- [CoursesApi Assessments Years API](https://apis.io/collections/cardiff/open-cardiff-years-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Cardiff University — jsonschema rules](https://apis.io/rules/cardiff/cardiff-jsonschema-spectral-rules/)
- [Cardiff University API Rules](https://apis.io/rules/cardiff/cardiff-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Cardiff Authentication](https://apis.io/security/cardiff/cardiff-authentication/)
- [Cardiff Domain Security](https://apis.io/security/cardiff/cardiff-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Cardiff Scopes](https://apis.io/scopes/cardiff/cardiff-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Cardiff Plans Pricing](https://apis.io/plans/cardiff/cardiff-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Cardiff Rate Limits](https://apis.io/rate-limits/cardiff/cardiff-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Cardiff Finops](https://apis.io/finops/cardiff/cardiff-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.cardiff.ac.uk/)
- [Blog](https://www.cardiff.ac.uk/news/)
- [Terms of service](http://www.cardiff.ac.uk/terms/)
- [GitHub](https://github.com/ARCCA)

## API Evangelist rating

**Kin Score 31.9** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 47.7 |
| Contract governance | 9.8 |
| Operational transparency | 7.9 |
| Developer ergonomics | 33.3 |
| Access clarity | 18.4 |

**Agent readiness 20.7** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 26.5** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/cardiff/](https://apis.io/providers/cardiff/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Cardiff University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/cardiff/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
