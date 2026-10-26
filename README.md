# WattTime (watttime)

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

WattTime is a nonprofit organization that provides real-time, forecast, and historical data for electric grids around the world, enabling carbon-aware computing and clean energy procurement decisions. The WattTime API delivers marginal emissions data (CO2 MOER), health damage signals, average emissions rates, and renewable energy forecasts for 342 grid regions across 210 countries and territories. Developers and organizations use the API to schedule workloads during low-carbon windows, measure actual emissions reductions from clean energy procurement, and meet sustainability reporting requirements.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/watttime/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/watttime/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Emissions
- Climate
- Carbon
- Energy
- Electricity Grid
- Sustainability
- Clean Energy

## Timestamps

- **Created:** 2025-05-02
- **Modified:** 2026-05-19

## APIs

### WattTime API

The WattTime Data API v3 provides access to real-time, forecast, and historical marginal emissions data for electric grids worldwide. Key signals include CO2 MOER (Marginal Operating Emissions Rate), health damage estimates, and CO2 AOER (Average Operating Emissions Rate). The API covers 342 grid regions in 210 countries and territories, with real-time data updated every five minutes via the forecast endpoint.

- **Human URL:** [https://docs.watttime.org/](https://docs.watttime.org/)
- **Base URL:** `https://api.watttime.org/v3`

#### Tags

- Emissions
- Carbon
- Electricity Grid
- Marginal Emissions
- Forecasting
- Climate

#### Properties

- [Documentation](https://docs.watttime.org/)
- [Documentation](https://legacy-docs.watttime.org/)
- [OpenAPI](openapi/watttime-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/watttime.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/watttime.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/watttime-data-point-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/watttime-data-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/watttime-forecast-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/watttime-region-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/watttime-data-point-structure.json)
- [JSON Structure](json-structure/watttime-data-response-structure.json)

### WattTime Python Client

Official Python SDK for the WattTime API providing simplified access to real-time, forecast, and historical emissions data.

- **Human URL:** [https://github.com/WattTime/watttime-python-client](https://github.com/WattTime/watttime-python-client)

#### Tags

- Python
- SDK
- Client Library

#### Properties

- [SDK](https://pypi.org/project/watttime/)
- [Code Examples](https://github.com/WattTime/watttime-python-client)
- [Postman Collection](collections/watttime.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/watttime.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/watttime)
- [Portal](https://watttime.org/)
- [Documentation](https://docs.watttime.org/)
- [Release Notes](https://watttime.org/data-science/release-notes/)
- [Status Page](http://status.watttime.org/)
- [GitHub Organization](https://github.com/WattTime)
- [Support](mailto:support@watttime.org)
- [Spectral Rules](rules/watttime-spectral-rules.yml)
- [Vocabulary](vocabulary/watttime-vocabulary.yml)
- [JSON-LD](json-ld/watttime-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
