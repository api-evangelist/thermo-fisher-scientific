# Thermo Fisher Scientific (thermo-fisher-scientific)

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

Thermo Fisher Scientific is the world leader in serving science, providing analytical instruments, life sciences solutions, specialty diagnostics, laboratory products, and biopharma services. Developer APIs enable laboratory automation, instrument control, LIMS integration, and data management across life science workflows.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/thermo-fisher-scientific/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/thermo-fisher-scientific/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Life Sciences
- Laboratory
- Scientific Instruments
- LIMS
- Diagnostics
- Biosciences
- Fortune 500

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-05-19

## APIs

### Thermo Fisher SampleManager LIMS REST API

The Thermo Scientific SampleManager LIMS REST API enables secure connection between software applications and the SampleManager LIMS system for simplified data exchange. Provides access to sample data, workflows, entities, results, and laboratory operations. Runs on port 56105 and supports token authentication.

- **Human URL:** [https://www.thermofisher.com/us/en/home/digital-solutions/lab-informatics/lab-information-management-systems-lims/solutions/samplemanager.html](https://www.thermofisher.com/us/en/home/digital-solutions/lab-informatics/lab-information-management-systems-lims/solutions/samplemanager.html)
- **Base URL:** `https://{your-server}:{port}/smpwcfrestvgsm`

#### Tags

- LIMS
- Laboratory
- Life Sciences
- Sample Management
- REST API

#### Properties

- [Documentation](https://www.thermofisher.com/us/en/home/digital-solutions/lab-informatics/lab-information-management-systems-lims/solutions/samplemanager.html)
- [OpenAPI](openapi/thermo-fisher-samplemanager-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/thermo-fisher-samplemanager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/thermo-fisher-samplemanager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Thermo Fisher NanoDrop Ultra Web API

The Thermo Scientific NanoDrop Ultra Web API provides RESTful access to instrument control and data export for the NanoDrop Ultra microvolume UV-Vis spectrophotometer. Enables laboratory informatics integration, automated measurement workflows, and data retrieval from the instrument.

- **Human URL:** [https://documents.thermofisher.com/TFS-Assets/CAD/manuals/nanodrop-ultra-api-reference-manual-m024.pdf](https://documents.thermofisher.com/TFS-Assets/CAD/manuals/nanodrop-ultra-api-reference-manual-m024.pdf)
- **Base URL:** `https://{nanodrop-instrument-ip}`

#### Tags

- Spectrophotometry
- Laboratory Instruments
- Life Sciences
- REST API
- UV-Vis

#### Properties

- [Documentation](https://documents.thermofisher.com/TFS-Assets/CAD/manuals/nanodrop-ultra-api-reference-manual-m024.pdf)
- [OpenAPI](openapi/thermo-fisher-nanodrop-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/thermo-fisher-nanodrop.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/thermo-fisher-nanodrop.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Thermo Fisher Connect Platform OData API

The Thermo Fisher Connect Platform OData API provides standards-based interoperability for laboratory data management, enabling integration between instruments, LIMS, ELN, and enterprise systems through the OData REST protocol.

- **Human URL:** [https://www.thermofisher.com/us/en/home/digital-science/thermo-fisher-connect.html](https://www.thermofisher.com/us/en/home/digital-science/thermo-fisher-connect.html)
- **Base URL:** `https://api.thermofisher.com`

#### Tags

- Platform
- OData
- Laboratory
- Life Sciences
- Integration

#### Properties

- [Documentation](https://www.thermofisher.com/blog/connectedlab/platform-for-science-developer-portal-beta/)
- [Postman Collection](collections/thermo-fisher-nanodrop.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/thermo-fisher-nanodrop.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/thermo-fisher-samplemanager.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/thermo-fisher-samplemanager.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/thermo-fisher-scientific)
- [Website](https://www.thermofisher.com)
- [Documentation](https://www.thermofisher.com/us/en/home/digital-science/thermo-fisher-connect.html)
- [Blog](https://www.thermofisher.com/blog/connectedlab/)
- [Documentation](https://www.thermofisher.com/blog/connectedlab/platform-for-science-developer-portal-beta/)
- [GitHub Repository](https://github.com/thermofisherlsms/iapi)
- [GitHub Organization](https://github.com/thermofisherlsms)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
