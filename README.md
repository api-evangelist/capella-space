# Capella Space (capella-space)

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
