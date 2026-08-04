# Capella Space (capella-space)

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

Capella Space operates a constellation of synthetic aperture radar (SAR) satellites and provides on-demand, high-resolution Earth-observation imagery through a self-service Console and public API. Customers can task the constellation with 15-minute scheduling cycles, search a STAC-based catalog of archive collects, place orders, and download imagery products for defense, intelligence, maritime, energy, insurance, and analytics use cases.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/capella-space/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/capella-space/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Synthetic Aperture Radar
- SAR
- Earth Observation
- Satellite Imagery
- Geospatial
- STAC
- Remote Sensing
- Tasking
- Catalog

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Capella Space Tasking API

The Capella Tasking API lets customers submit imagery tasking requests against the Capella SAR constellation, configure collect parameters (geometry, resolution, polarization, look direction, off-nadir angle), monitor tasking and collect statuses, and manage repeat tasking. Supports 15-minute scheduling cycles and flexible collection tiers.

- **Human URL:** [https://docs.capellaspace.com/api/tasking/](https://docs.capellaspace.com/api/tasking/)
- **Base URL:** `https://api.capellaspace.com`

#### Tags

- Tasking
- SAR
- Collects
- Scheduling

#### Properties

- [Documentation](https://docs.capellaspace.com/api/tasking/)
- [Authentication](https://docs.capellaspace.com/)
- [Sign Up](https://console.capellaspace.com/)
- [Postman Collection](collections/capella-space.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/capella-space.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Capella Space Catalog API

The Capella Catalog API is a STAC-compliant search interface over the archive of SAR collects. Clients query the catalog by geometry, time, product type, resolution, and polarization to discover scenes available for ordering and download.

- **Human URL:** [https://docs.capellaspace.com/api/catalog/](https://docs.capellaspace.com/api/catalog/)
- **Base URL:** `https://api.capellaspace.com`

#### Tags

- Catalog
- STAC
- Search
- Discovery

#### Properties

- [Documentation](https://docs.capellaspace.com/api/catalog/)
- [Authentication](https://docs.capellaspace.com/)
- [Postman Collection](collections/capella-space.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/capella-space.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Capella Space Orders API

The Capella Orders API submits and tracks orders for SAR products, manages order lifecycle, and returns signed download URLs for completed imagery via endpoints such as GET /orders/{orderId}/download.

- **Human URL:** [https://docs.capellaspace.com/accessing-data/ordering-and-downloading/](https://docs.capellaspace.com/accessing-data/ordering-and-downloading/)
- **Base URL:** `https://api.capellaspace.com`

#### Tags

- Orders
- Download
- Fulfillment

#### Properties

- [Documentation](https://docs.capellaspace.com/accessing-data/ordering-and-downloading/)
- [Authentication](https://docs.capellaspace.com/)
- [Postman Collection](collections/capella-space.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/capella-space.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.capellaspace.com)
- [Documentation](https://docs.capellaspace.com/)
- [API Reference](https://support.capellaspace.com/api-reference-and-documentation)
- [Getting Started](https://docs.capellaspace.com/)
- [Console](https://console.capellaspace.com/)
- [Sign Up](https://console.capellaspace.com/)
- [Login](https://console.capellaspace.com/)
- [Support](https://support.capellaspace.com/)
- [Knowledge Base](https://support.capellaspace.com/)
- [Blog](https://www.capellaspace.com/insights)
- [Newsroom](https://www.capellaspace.com/news)
- [GitHub Organization](https://github.com/capellaspace)
- [SDK](https://github.com/capellaspace/console-client)
- [SDK](https://capella-console-client.readthedocs.io/en/main/pages/api_reference.html)
- [Sample Code](https://github.com/capellaspace/jupyter-notebooks)
- [Sample Code](https://github.com/capellaspace/postman_collections)
- [Sample Code](https://github.com/capellaspace/capella-reader)
- [LinkedIn](https://www.linkedin.com/company/capella-space)
- [Twitter](https://twitter.com/capellaspace)
- [YouTube](https://www.youtube.com/c/CapellaSpace)
- [Features](undefined)
- [Use Cases](undefined)
- [Authentication](undefined)
- [Compliance](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
