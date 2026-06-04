# Emory University (emory)

Emory University is a private research university in Atlanta, Georgia, United States, ranked #196 in the QS World University Rankings 2025. This repository catalogs Emory's public developer and API footprint as an [APIs.json](https://apisjson.org) profile. Emory has no central self-service developer portal; the confirmed programmatic surfaces are concentrated in the libraries and research-computing units plus standard LMS and identity services.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/emory/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=emory-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Research, Libraries, United States, Atlanta

## APIs

- **Emory Digital Slide Archive REST API** — Girder/HistomicsTK digital-pathology platform with a live Swagger REST API. Docs: https://computablebrain.emory.edu/api/v1
- **Emory Canvas LMS REST API** — Instructure Canvas REST API at the Emory Canvas host; gated by account and developer keys. Docs: https://canvas.emory.edu/doc/api/
- **Emory Identity (Shibboleth / SAML)** — Federated SAML single sign-on IdP. Docs: https://login.emory.edu/
- **Emory Libraries Digital Repository Software** — ~120 public open-source repos (Samvera/Hyrax, dlp-curate, TheKeep, dlp-lux). GitHub: https://github.com/emory-libraries

## Plans / Rate Limits / FinOps

- Plans: [plans/emory-plans-pricing.yml](plans/emory-plans-pricing.yml)
- Rate Limits: [rate-limits/emory-rate-limits.yml](rate-limits/emory-rate-limits.yml)
- FinOps: [finops/emory-finops.yml](finops/emory-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.emory.edu/
- Developer Portal (IT Service Catalog): https://it.emory.edu/catalog/index.html
- GitHub: https://github.com/emory-libraries
- Source Code: https://github.com/emory-libraries/dlp-curate
- Authentication: https://login.emory.edu/
- LinkedIn: https://www.linkedin.com/school/emory-university/

## Notes

All URLs in this profile were probed live on 2026-06-03. The Digital Slide Archive API returned HTTP 200 (including its `/system/version` endpoint), confirming a working public REST API. Canvas and Shibboleth are documented but gated to credential holders. The `EmoryUniversity` GitHub org exists but has 0 public repositories, so the active `emory-libraries` org (~120 repos) was cataloged instead. OPUS and Course Atlas are gated browser applications with no documented public API. OpenEmory (`open.library.emory.edu`) returns 403 to automated requests but is publicly browsable. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
