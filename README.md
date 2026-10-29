# Emory University

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

Emory University is a private research university in Atlanta, Georgia, and a member of the Association of American Universities. Its programmable footprint is small, federated across units, and — as of the 2026-09-01 re-profile — partly retired. Emory operates no central developer portal and no public course, campus or open-data API. The surfaces it genuinely runs itself are: a Shibboleth/SAML identity provider at login.emory.edu, registered in InCommon and reachable through eduGAIN, which is the strongest machine-readable thing the institution publishes; two Emory Libraries applications built on the division's own open-source Rails code (a Blacklight JSON:API search endpoint at digital.library.emory.edu and a Samvera Hyrax repository at open.library.emory.edu that exposes a ResourceSync capability list); and a large public GitHub organization, emory-libraries, holding the Hyrax/Samvera software those systems run on. The Girder-based Digital Slide Archive REST API at computablebrain.emory.edu was Emory-operated and is the source of the 22 OpenAPI contracts held here, but the host now serves a stock nginx page and refuses TLS; those contracts are kept as a retired, correctly attributed Emory surface. Everything else that looks like an Emory API is a tenancy: Canvas on Instructure, library discovery on Ex Libris Primo, and the Course Atlas catalog on CourseLeaf.

**Areas:** University · Higher Education · Education · Private Research University · Association of American Universities · United States · Georgia · Atlanta · Research · Library · Research Repository · Library Catalog

## Emory University on APIs.io

Everything profiled for Emory University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/emory/](https://apis.io/providers/emory/)** — or go straight to one of the APIs or properties below.

### APIs (31)

- [Emory Canvas LMS REST API](https://apis.io/apis/emory/canvas-lms/) — Emory's instance of the Instructure Canvas learning management system exposes the standard Canvas LMS REST API. Access requires an Emory Canvas account and…
- [Emory Identity (Shibboleth / SAML)](https://apis.io/apis/emory/shibboleth/) — Emory operates a federated Shibboleth identity provider for SAML-based single sign-on across institutional and partner services (InCommon federation). The…
- [Emory Libraries Digital Repository Software](https://apis.io/apis/emory/libraries-github/) — Emory Libraries (Library Technology and Digital Strategies) maintains a large public open-source GitHub organization with ~120 repositories, including the…
- [Emory University Annotation API](https://apis.io/apis/emory/emory-annotation-api/) — annotation resource
- [Emory University API Key API](https://apis.io/apis/emory/emory-api-key-api/) — api_key resource
- [Emory University Assetstore API](https://apis.io/apis/emory/emory-assetstore-api/) — assetstore resource
- [Emory University Collection API](https://apis.io/apis/emory/emory-collection-api/) — collection resource
- [Emory University Dicomweb Assetstore API](https://apis.io/apis/emory/emory-dicomweb-assetstore-api/) — dicomweb_assetstore resource
- [Emory University File API](https://apis.io/apis/emory/emory-file-api/) — file resource
- [Emory University Files API](https://apis.io/apis/emory/emory-files-api/) — files resource
- [Emory University Folder API](https://apis.io/apis/emory/emory-folder-api/) — folder resource
- [Emory University Group API](https://apis.io/apis/emory/emory-group-api/) — group resource
- [Emory University Histomicsui API](https://apis.io/apis/emory/emory-histomicsui-api/) — histomicsui resource
- [Emory University Homepage API](https://apis.io/apis/emory/emory-homepage-api/) — homepage resource
- [Emory University Item API](https://apis.io/apis/emory/emory-item-api/) — item resource
- [Emory University Job API](https://apis.io/apis/emory/emory-job-api/) — job resource
- [Emory University Large Image API](https://apis.io/apis/emory/emory-large-image-api/) — large_image resource
- [Emory University Notification API](https://apis.io/apis/emory/emory-notification-api/) — notification resource
- [Emory University Resource API](https://apis.io/apis/emory/emory-resource-api/) — resource resource
- [Emory University Slicer Cli Web API](https://apis.io/apis/emory/emory-slicer-cli-web-api/) — slicer_cli_web resource
- [Emory University System API](https://apis.io/apis/emory/emory-system-api/) — system resource
- [Emory University Tcga API](https://apis.io/apis/emory/emory-tcga-api/) — tcga resource
- [Emory University Token API](https://apis.io/apis/emory/emory-token-api/) — token resource
- [Emory University User API](https://apis.io/apis/emory/emory-user-api/) — user resource
- [Emory University Worker API](https://apis.io/apis/emory/emory-worker-api/) — worker resource
- [Emory Digital Library Program Search API (Blacklight JSON:API)](https://apis.io/apis/emory/dlp-lux-search/) — The Emory Libraries Digital Library Program discovery layer (dlp-lux) exposes its Blacklight search index as a JSON:API document at /catalog.json. Query,…
- [OpenEmory Repository (Samvera Hyrax / ResourceSync)](https://apis.io/apis/emory/openemory-resourcesync/) — OpenEmory is Emory's open-access institutional repository, running Samvera Hyrax 5.2.0 on Emory infrastructure. It publishes a ResourceSync source…
- [Emory in the InCommon Identity Federation](https://apis.io/apis/emory/incommon-federation/) — Emory's Shibboleth identity provider is registered in the InCommon federation and is therefore resolvable through the InCommon Metadata Query service and,…
- [Emory University in the Research Organization Registry (ROR)](https://apis.io/apis/emory/ror-registration/) — Emory University is registered in ROR, the open registry of research organization identifiers, under ROR ID 03czfpz43. The registry is shared because every…
- [Emory Libraries Discovery (Ex Libris Primo VE)](https://apis.io/apis/emory/primo-discovery/) — Library discovery and catalog search for Emory Libraries runs on Ex Libris Primo VE. The Emory entry point search.library.emory.edu redirects to the…
- [Emory Course Atlas (CourseLeaf)](https://apis.io/apis/emory/course-atlas/) — Course Atlas is Emory's published course catalog and class schedule. It is a CourseLeaf (Leepfrog Technologies) tenancy on an Emory hostname. The catalog…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Emory Agentic Access](https://apis.io/agentic-access/emory/emory-agentic-access/)

#### JSON Schema (4)

The data models the API reads and writes.

- [Girder Annotation](https://apis.io/schemas/emory/emory-annotation/)
- [Girder Collection](https://apis.io/schemas/emory/emory-collection/)
- [Girder Folder](https://apis.io/schemas/emory/emory-folder/)
- [Girder Item](https://apis.io/schemas/emory/emory-item/)

#### JSON Structure (4)

Data models expressed in JSON Structure.

- [Emory Annotation Structure](https://apis.io/json-structure/emory/emory-annotation-structure/)
- [Emory Collection Structure](https://apis.io/json-structure/emory/emory-collection-structure/)
- [Emory Folder Structure](https://apis.io/json-structure/emory/emory-folder-structure/)
- [Emory Item Structure](https://apis.io/json-structure/emory/emory-item-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Emory Context](https://apis.io/jsonld/emory/emory-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Emory Digital Slide Archive Vocabulary](https://apis.io/vocabularies/emory/emory-vocabulary/)

#### Examples (4)

Example requests and responses.

- [Emory Get Item Example](https://apis.io/examples/emory/emory-get-item-example/)
- [Emory List Annotations Example](https://apis.io/examples/emory/emory-list-annotations-example/)
- [Emory List Collections Example](https://apis.io/examples/emory/emory-list-collections-example/)
- [Emory List Folders Example](https://apis.io/examples/emory/emory-list-folders-example/)

#### Collections (22)

Postman and Open Collection request collections.

- [Girder REST API (Emory Digital Slide Archive) annotation API](https://apis.io/collections/emory/open-emory-annotation-api/)
- [Girder REST API (Emory Digital Slide Archive) annotation api_key API](https://apis.io/collections/emory/open-emory-api-key-api/)
- [Girder REST API (Emory Digital Slide Archive) annotation assetstore API](https://apis.io/collections/emory/open-emory-assetstore-api/)
- [Girder REST API (Emory Digital Slide Archive) annotation collection API](https://apis.io/collections/emory/open-emory-collection-api/)
- [Girder REST API (Emory Digital Slide Archive) annotation dicomweb_assetstore API](https://apis.io/collections/emory/open-emory-dicomweb-assetstore-api/)
- [Girder REST API (Emory Digital Slide Archive) annotation file API](https://apis.io/collections/emory/open-emory-file-api/)
- [Girder REST API (Emory Digital Slide Archive) annotation files API](https://apis.io/collections/emory/open-emory-files-api/)
- [Girder REST API (Emory Digital Slide Archive) annotation folder API](https://apis.io/collections/emory/open-emory-folder-api/)
- [Girder REST API (Emory Digital Slide Archive) annotation group API](https://apis.io/collections/emory/open-emory-group-api/)
- [Girder REST API (Emory Digital Slide Archive) annotation histomicsui API](https://apis.io/collections/emory/open-emory-histomicsui-api/)
- [Girder REST API (Emory Digital Slide Archive) annotation homepage API](https://apis.io/collections/emory/open-emory-homepage-api/)
- [Girder REST API (Emory Digital Slide Archive) annotation item API](https://apis.io/collections/emory/open-emory-item-api/)
- [Girder REST API (Emory Digital Slide Archive) annotation job API](https://apis.io/collections/emory/open-emory-job-api/)
- [Girder REST API (Emory Digital Slide Archive) annotation large_image API](https://apis.io/collections/emory/open-emory-large-image-api/)
- [Girder REST API (Emory Digital Slide Archive) annotation notification API](https://apis.io/collections/emory/open-emory-notification-api/)
- [Girder REST API (Emory Digital Slide Archive) annotation resource API](https://apis.io/collections/emory/open-emory-resource-api/)
- [Girder REST API (Emory Digital Slide Archive) annotation slicer_cli_web API](https://apis.io/collections/emory/open-emory-slicer-cli-web-api/)
- [Girder REST API (Emory Digital Slide Archive) annotation system API](https://apis.io/collections/emory/open-emory-system-api/)
- [Girder REST API (Emory Digital Slide Archive) annotation tcga API](https://apis.io/collections/emory/open-emory-tcga-api/)
- [Girder REST API (Emory Digital Slide Archive) annotation token API](https://apis.io/collections/emory/open-emory-token-api/)
- [Girder REST API (Emory Digital Slide Archive) annotation user API](https://apis.io/collections/emory/open-emory-user-api/)
- [Girder REST API (Emory Digital Slide Archive) annotation worker API](https://apis.io/collections/emory/open-emory-worker-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Emory University — jsonschema rules](https://apis.io/rules/emory/emory-jsonschema-spectral-rules/)
- [Emory University API Rules](https://apis.io/rules/emory/emory-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Emory Authentication](https://apis.io/security/emory/emory-authentication/)
- [Emory Domain Security](https://apis.io/security/emory/emory-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Emory Plans Pricing](https://apis.io/plans/emory/emory-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Emory Rate Limits](https://apis.io/rate-limits/emory/emory-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Emory Finops](https://apis.io/finops/emory/emory-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.emory.edu/)
- [Support](https://it.emory.edu/support/index.html)
- [Blog](https://emory-libraries.github.io/)

## API Evangelist rating

**Kin Score 34.8** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 53.8 |
| Contract governance | 9.8 |
| Operational transparency | 26.3 |
| Developer ergonomics | 38.1 |
| Access clarity | 5.3 |

**Agent readiness 22.1** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | partial |
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

**Regulatory alignment 16.7** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/emory/](https://apis.io/providers/emory/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Emory University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/emory/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
