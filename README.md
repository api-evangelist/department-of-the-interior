# Department of the Interior (department-of-the-interior)

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
