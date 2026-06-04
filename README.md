# University of Tübingen (university-of-tubingen)

The University of Tübingen (Eberhard Karls Universität Tübingen), founded in 1477 in Tübingen, Germany, is one of the oldest German universities and ranks #222 in the QS World University Rankings 2025. This repository catalogs the institution's public developer/API footprint as an [APIs.json](https://apisjson.org) profile.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-tubingen/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-tubingen-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research Data, Germany, Open Data

## APIs

- **FDAT Repository REST API** — JSON REST API (InvenioRDM) for the FDAT institutional research data repository. Docs: https://fdat.uni-tuebingen.de — Base: https://fdat.uni-tuebingen.de/api/records
- **FDAT Repository OAI-PMH** — OAI-PMH 2.0 metadata harvesting endpoint for FDAT (DataCite/Dublin Core). Docs: https://fdat.uni-tuebingen.de/oai2d?verb=Identify — Base: https://fdat.uni-tuebingen.de/oai2d

## Plans / Rate Limits / FinOps

- Plans & Pricing: [plans/university-of-tubingen-plans-pricing.yml](plans/university-of-tubingen-plans-pricing.yml)
- Rate Limits: [rate-limits/university-of-tubingen-rate-limits.yml](rate-limits/university-of-tubingen-rate-limits.yml)
- FinOps: [finops/university-of-tubingen-finops.yml](finops/university-of-tubingen-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://uni-tuebingen.de/en/
- GitHub (University Library): https://github.com/ubtue
- LinkedIn: https://www.linkedin.com/company/university-of-tuebingen
- Source Code (Software Engineering): https://github.com/se-tuebingen
- Review: [review.yml](review.yml)

## Notes

All entries were verified live where possible. No central developer portal or published API documentation hub exists for the university. Only the FDAT research data repository (InvenioRDM) exposes a publicly documented, live REST and OAI-PMH API (both HTTP 200 as of 2026-06-03). Central systems (ALMA student information system, ILIAS, Moodle, FIT, TIMMS) are gated with no public API docs and were not cataloged to avoid fabricating endpoints. Multiple verified GitHub organizations publish source code but not consumer web APIs.

## Maintainers

- Kin Lane — kin@apievangelist.com
