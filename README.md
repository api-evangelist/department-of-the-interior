# Department of the Interior (department-of-the-interior)

The U.S. Department of the Interior manages federal lands, water, wildlife, energy and mineral resources, and trust responsibilities to American Indian, Alaska Native, and insular communities. Interior bureaus - National Park Service, U.S. Geological Survey, Bureau of Land Management, U.S. Fish and Wildlife Service, Bureau of Reclamation, Bureau of Indian Affairs, and the Office of Natural Resources Revenue - publish a number of public APIs and open-data portals.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/department-of-the-interior/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/department-of-the-interior/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Federal Government
- Public Lands
- Natural Resources
- Geospatial

## Timestamps

- **Created:** 2024-12-25
- **Modified:** 2026-05-19

## APIs

### National Park Service Data API

Search and retrieve parks, alerts, campgrounds, visitor centers, events, and articles for U.S. National Park Service units.

- **Human URL:** [https://www.nps.gov/subjects/developer/api-documentation.htm](https://www.nps.gov/subjects/developer/api-documentation.htm)
- **Base URL:** `https://developer.nps.gov/api/v1`

#### Tags

- NPS
- Parks

#### Properties

- [Documentation](https://www.nps.gov/subjects/developer/api-documentation.htm)
- [OpenAPI](openapi/nps-data-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nps-data-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nps-data-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/nps-park-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Example](examples/park-example.json)
- [Authentication](https://www.nps.gov/subjects/developer/get-started.htm)

### USGS Earthquake Hazards Program API

FDSN-compatible earthquake catalog API returning GeoJSON FeatureCollections for queries by time, magnitude, location, and depth.

- **Human URL:** [https://earthquake.usgs.gov/fdsnws/event/1/](https://earthquake.usgs.gov/fdsnws/event/1/)
- **Base URL:** `https://earthquake.usgs.gov/fdsnws/event/1`

#### Tags

- USGS
- Earthquakes
- Geospatial

#### Properties

- [Documentation](https://earthquake.usgs.gov/fdsnws/event/1/)
- [OpenAPI](openapi/usgs-earthquake-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/usgs-earthquake-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usgs-earthquake-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/earthquake-feature-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Example](examples/earthquake-example.json)

### USGS Water Services API

Real-time and historical surface-water, groundwater, and water-quality data via the National Water Information System.

- **Human URL:** [https://waterservices.usgs.gov/](https://waterservices.usgs.gov/)
- **Base URL:** `https://waterservices.usgs.gov/nwis`

#### Tags

- USGS
- Water
- Hydrology

#### Properties

- [Documentation](https://waterservices.usgs.gov/)
- [OpenAPI](openapi/usgs-water-services-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/usgs-water-services-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usgs-water-services-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### DOI Open Data Catalog

Department-wide open-data catalog at data.doi.gov, including datasets from all Interior bureaus.

- **Human URL:** [https://data.doi.gov/](https://data.doi.gov/)

#### Tags

- Open Data

#### Properties

- [Documentation](https://data.doi.gov/)
- [Postman Collection](collections/nps-data-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nps-data-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/usgs-earthquake-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usgs-earthquake-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/usgs-water-services-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usgs-water-services-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### BLM Public Lands Data

Bureau of Land Management public-land data, including the Land Records System, mining claims, and recreation areas.

- **Human URL:** [https://www.blm.gov/about/data](https://www.blm.gov/about/data)

#### Tags

- BLM
- Public Lands

#### Properties

- [Documentation](https://www.blm.gov/about/data)
- [Postman Collection](collections/nps-data-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nps-data-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/usgs-earthquake-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usgs-earthquake-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/usgs-water-services-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usgs-water-services-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### USFWS Environmental Conservation Online System (ECOS) API

U.S. Fish and Wildlife Service data on listed species under the Endangered Species Act and the National Wildlife Refuge System.

- **Human URL:** [https://ecos.fws.gov/ecp/](https://ecos.fws.gov/ecp/)

#### Tags

- USFWS
- Wildlife
- Endangered Species

#### Properties

- [Documentation](https://ecos.fws.gov/ecp/)
- [Postman Collection](collections/nps-data-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nps-data-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/usgs-earthquake-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usgs-earthquake-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/usgs-water-services-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usgs-water-services-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bureau of Reclamation Water Data

Reclamation reservoir, dam, and water-operations data for the western United States.

- **Human URL:** [https://www.usbr.gov/projects/index.php](https://www.usbr.gov/projects/index.php)

#### Tags

- Reclamation
- Water
- Dams

#### Properties

- [Documentation](https://www.usbr.gov/projects/index.php)
- [Postman Collection](collections/nps-data-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nps-data-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/usgs-earthquake-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usgs-earthquake-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/usgs-water-services-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usgs-water-services-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ONRR Natural Resources Revenue Data

Office of Natural Resources Revenue datasets on royalty, rent, and bonus revenue from federal energy and mineral production.

- **Human URL:** [https://revenuedata.doi.gov/](https://revenuedata.doi.gov/)

#### Tags

- ONRR
- Revenue

#### Properties

- [Documentation](https://revenuedata.doi.gov/)
- [Postman Collection](collections/nps-data-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nps-data-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/usgs-earthquake-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usgs-earthquake-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/usgs-water-services-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usgs-water-services-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/doi-open-data)
- [LinkedIn](https://www.linkedin.com/company/department-of-the-interior)
- [Portal](https://www.doi.gov/)
- [Documentation](https://www.doi.gov/developer)
- [Datasets](https://data.doi.gov/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
