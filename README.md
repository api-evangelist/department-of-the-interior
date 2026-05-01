# Department of the Interior

The U.S. Department of the Interior manages federal lands, water, wildlife, energy and mineral resources, and trust responsibilities to American Indian, Alaska Native, and insular communities. Interior bureaus - National Park Service (NPS), U.S. Geological Survey (USGS), Bureau of Land Management (BLM), U.S. Fish and Wildlife Service (USFWS), Bureau of Reclamation (BOR), Bureau of Indian Affairs (BIA), and the Office of Natural Resources Revenue (ONRR) - publish a number of public APIs and open-data portals.

**APIs.yml:** [apis.yml](https://raw.githubusercontent.com/api-evangelist/department-of-the-interior/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Federal Government
- Public Lands
- Natural Resources
- Geospatial

## Repository Layout

- [`apis.yml`](apis.yml) — APIs.json/yml index
- [`openapi/`](openapi/) — OpenAPI 3.1 specs (NPS Data, USGS Earthquake, USGS Water Services)
- [`json-schema/`](json-schema/) — JSON Schemas for parks and earthquake features
- [`json-ld/`](json-ld/) — JSON-LD context aligning Interior terms to schema.org and WGS84
- [`vocabulary/`](vocabulary/) — Controlled vocabulary across NPS, USGS, BLM, USFWS, BOR, ONRR
- [`capabilities/`](capabilities/) — Capability catalog
- [`rules/`](rules/) — Access, attribution, and rate-limit rules
- [`examples/`](examples/) — Representative response payloads

## APIs in this Index

### National Park Service
- **NPS Data API** — parks, alerts, campgrounds, visitor centers, events, articles

### U.S. Geological Survey
- **USGS Earthquake Hazards Program API** — FDSN earthquake catalog (GeoJSON)
- **USGS Water Services API** — real-time and historical water data (NWIS)

### Other Bureaus
- **DOI Open Data Catalog** — department-wide datasets
- **BLM Public Lands Data**
- **USFWS Environmental Conservation Online System (ECOS)**
- **Bureau of Reclamation Water Data**
- **ONRR Natural Resources Revenue Data**

## Authentication

- **NPS Data API** — API key (api.nps.gov)
- **USGS APIs** — public, no key required
- **Other bureau data portals** — primarily downloadable datasets

## Data License

Interior data is U.S. government work in the public domain. Attribute the originating bureau when republishing. NPS image properties may carry separate credit/copyright fields that must be surfaced.

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
