# Agrio (agrio)

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

Agrio is a precision plant protection solution that helps growers and crop advisors forecast, identify, and treat plant diseases, pests, and nutrient deficiencies. With Agrio APIs, developers can access AI-powered plant disease diagnosis from images, crop advisory data, weather pattern analysis, pest and disease predictions, and satellite vegetation monitoring to build accurate crop advisory tools.

**URL:** [https://agrio.app](https://agrio.app)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Agriculture, Plant Disease, Pest Detection, AI, Crop Advisory

## Timestamps

- **Created:** 2024-07-11
- **Modified:** 2026-04-19

## APIs

### Agrio Agriculture API
The Agrio Agriculture API provides AI-powered plant disease and pest diagnosis from images, plus crop advisory data, credit balance management, and access to a catalog of supported crop types. Returns ranked disease and pest identifications with confidence scores, common names, and scientific names.

**Human URL:** [https://agrio.app/Agriculture-API/](https://agrio.app/Agriculture-API/)

#### Tags:

 - Plant Disease, Pest Detection, AI, Image Recognition, Crop Advisory

#### Properties

- [Documentation](https://agrio.app/Agriculture-API/)
- [OpenAPI](openapi/agrio-openapi-original.yml)
- [Diagnosis Schema](json-schema/agrio-diagnosis-schema.json)
- [Diagnosis Result Schema](json-schema/agrio-diagnosis-result-schema.json)
- [Crop Schema](json-schema/agrio-crop-schema.json)
- [Credit Balance Schema](json-schema/agrio-credit-balance-schema.json)
- [Diagnosis Structure](json-structure/agrio-diagnosis-structure.json)
- [Crop Structure](json-structure/agrio-crop-structure.json)
- [JSON-LD Context](json-ld/agrio-context.jsonld)

## Common Properties

- [Website](https://agrio.app)
- [API Portal](https://pro.agrio.app/image-diagnosis-api)
- [Support](mailto:info@saillog.co)

## Features

| Name | Description |
|------|-------------|
| AI Image Diagnosis | Computer vision algorithms identify plant diseases, pests, and nutrient deficiencies from uploaded photos with confidence scores. |
| AgrioShield Pest Prediction | Predictive algorithms forecast disease pressure before or between scouting events to enable proactive intervention. |
| Satellite Imagery Alerts | Remote sensing AI detects vegetation issues from satellite data, enabling early detection before visible symptoms appear. |
| Ranked Diagnoses | Returns multiple ranked diagnoses with confidence scores, common names, and scientific names for disambiguation. |
| Credit-Based Usage | API usage is metered using a credit system; one credit is consumed per diagnosis request. |
| Supported Crop Catalog | Discoverable catalog of supported crop types for building targeted diagnosis workflows. |

## Use Cases

| Name | Description |
|------|-------------|
| Crop Advisory Tool Integration | Embed AI plant disease diagnosis into existing crop advisory and farm management applications. |
| In-Field Disease Identification | Enable agronomists and farmers to photograph plant symptoms and receive immediate AI-powered diagnosis. |
| Early Warning Systems | Use AgrioShield alerts to notify growers when disease or pest conditions become favorable before visible symptoms appear. |
| Precision Agriculture Platforms | Integrate Agrio diagnosis into precision agriculture platforms for targeted treatment recommendations. |
| Research and Development | Access Agrio plant disease data for agricultural research and development of new advisory models. |

## Integrations

| Name | Description |
|------|-------------|
| Weather Data Systems | Agrio APIs integrate weather pattern data to enhance pest and disease prediction models. |
| Satellite Imagery Providers | Remote sensing data from satellite providers is used for vegetation monitoring and anomaly detection. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Agrio Agriculture API](openapi/agrio-openapi-original.yml)

### JSON Schema

- [Credit Balance Schema](json-schema/agrio-credit-balance-schema.json)
- [Diagnose Request Schema](json-schema/agrio-diagnose-request-schema.json)
- [Diagnosis Result Schema](json-schema/agrio-diagnosis-result-schema.json)
- [Diagnosis Schema](json-schema/agrio-diagnosis-schema.json)
- [Crop Schema](json-schema/agrio-crop-schema.json)
- [Supported Crops Response Schema](json-schema/agrio-supported-crops-response-schema.json)
- [Error Response Schema](json-schema/agrio-error-response-schema.json)

### JSON Structure

- [Credit Balance Structure](json-structure/agrio-credit-balance-structure.json)
- [Diagnosis Result Structure](json-structure/agrio-diagnosis-result-structure.json)
- [Diagnosis Structure](json-structure/agrio-diagnosis-structure.json)
- [Crop Structure](json-structure/agrio-crop-structure.json)

### JSON-LD

- [Agrio Context](json-ld/agrio-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Agrio API](capabilities/shared/agrio-api.yaml) — 3 operations for plant disease diagnosis and crop advisory

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Crop Protection](capabilities/crop-protection.yaml) | Agrio Agriculture API | 3 | Agronomist, Crop Advisor, Precision Agriculture Developer |

## Vocabulary

- [Agrio Vocabulary](vocabulary/agrio-vocabulary.yaml) — Unified taxonomy mapping 3 resources, 3 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Agrio Spectral Rules](rules/agrio-spectral-rules.yml) — 21 rules across 9 categories enforcing Agrio API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
