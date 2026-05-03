# Thermo Fisher Scientific

Thermo Fisher Scientific is the world leader in serving science, providing analytical instruments, life sciences solutions, specialty diagnostics, laboratory products, and biopharma services. Developer APIs enable laboratory automation, instrument control, LIMS integration, and data management across life science workflows.

**URL:** [https://raw.githubusercontent.com/api-evangelist/thermo-fisher-scientific/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/thermo-fisher-scientific/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
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
- **Modified:** 2026-05-03

## APIs

### Thermo Fisher SampleManager LIMS REST API

REST API for Thermo Scientific SampleManager LIMS enabling secure access to sample data, test results, entity browsing, and workflow automation.

**Human URL:** [https://www.thermofisher.com/us/en/home/digital-solutions/lab-informatics/lab-information-management-systems-lims/solutions/samplemanager.html](https://www.thermofisher.com/us/en/home/digital-solutions/lab-informatics/lab-information-management-systems-lims/solutions/samplemanager.html)

**Base URL:** https://{server}:56105/smpwcfrestvgsm

#### Tags

- LIMS
- Laboratory
- Life Sciences
- Sample Management
- REST API

#### Operations

| Method | Path | Summary |
|--------|------|---------|
| POST | /mobile/login | Login |
| POST | /mobile/logout | Logout |
| GET | /mobile/browses/{entity} | Browse Entity |
| GET | /mobile/browses/{entity}/{id} | Get Entity By ID |
| GET | /mobile/samples | Get Samples |
| GET | /mobile/samples/{sampleId} | Get Sample By ID |
| GET | /mobile/samples/{sampleId}/results | Get Sample Results |
| POST | /mobile/results | Submit Results |
| POST | /mobile/workflows/{workflowName}/trigger | Trigger Workflow |

#### Properties

- [Documentation](https://www.thermofisher.com/us/en/home/digital-solutions/lab-informatics/lab-information-management-systems-lims/solutions/samplemanager.html)
- [OpenAPI](openapi/thermo-fisher-samplemanager-openapi.yml)

### Thermo Fisher NanoDrop Ultra Web API

Local REST API for the NanoDrop Ultra microvolume UV-Vis spectrophotometer for instrument control, measurement execution, and LIMS data export.

**Human URL:** [https://documents.thermofisher.com/TFS-Assets/CAD/manuals/nanodrop-ultra-api-reference-manual-m024.pdf](https://documents.thermofisher.com/TFS-Assets/CAD/manuals/nanodrop-ultra-api-reference-manual-m024.pdf)

**Base URL:** http://{instrument-ip}:8080

#### Tags

- Spectrophotometry
- Laboratory Instruments
- Life Sciences
- REST API
- UV-Vis

#### Operations

| Method | Path | Summary |
|--------|------|---------|
| GET | /api/status | Get Instrument Status |
| POST | /api/measure | Perform Measurement |
| GET | /api/measurements | Get Measurements |
| GET | /api/measurements/{measurementId} | Get Measurement By ID |
| GET | /api/methods | Get Methods |
| POST | /api/export | Export Measurements |

#### Properties

- [Documentation](https://documents.thermofisher.com/TFS-Assets/CAD/manuals/nanodrop-ultra-api-reference-manual-m024.pdf)
- [OpenAPI](openapi/thermo-fisher-nanodrop-openapi.yml)

## Artifacts

### OpenAPI Specs

- [SampleManager LIMS REST API](openapi/thermo-fisher-samplemanager-openapi.yml)
- [NanoDrop Ultra Web API](openapi/thermo-fisher-nanodrop-openapi.yml)

### JSON Schemas

- [Sample](json-schema/thermo-fisher-sample-schema.json)
- [NanoDrop Measurement](json-schema/thermo-fisher-measurement-schema.json)

### JSON Structure

- [LIMS Structure](json-structure/thermo-fisher-lims-structure.json)

### JSON-LD

- [Thermo Fisher Context](json-ld/thermo-fisher-context.jsonld)

### Examples

- [Get Samples](examples/thermo-fisher-get-samples-example.json)
- [NanoDrop Measurement](examples/thermo-fisher-nanodrop-measurement-example.json)

### Spectral Rules

- [Thermo Fisher Rules](rules/thermo-fisher-rules.yml)

### Capabilities

- [Lab Data Management](capabilities/lab-data-management.yaml)

**Shared Definitions:**

- [SampleManager LIMS](capabilities/shared/samplemanager-lims.yaml)
- [NanoDrop Ultra](capabilities/shared/nanodrop-ultra.yaml)

### Vocabulary

- [Thermo Fisher Vocabulary](vocabulary/thermo-fisher-vocabulary.yml)

## Common Properties

- [Website](https://www.thermofisher.com)
- [Thermo Fisher Connect Platform](https://www.thermofisher.com/us/en/home/digital-science/thermo-fisher-connect.html)
- [Connected Lab Blog](https://www.thermofisher.com/blog/connectedlab/)
- [Developer Portal (Beta)](https://www.thermofisher.com/blog/connectedlab/platform-for-science-developer-portal-beta/)
- [Instrument API GitHub](https://github.com/thermofisherlsms/iapi)
- [GitHub Organization](https://github.com/thermofisherlsms)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
