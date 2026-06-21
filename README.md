# CentML (centml)

CentML is an AI inference optimization platform that serves popular open models through OpenAI-compatible serverless endpoints and lets teams stand up dedicated, autoscaling model-serving deployments and compute clusters. The serverless inference API runs at https://api.centml.com/openai/v1 with Bearer API keys, while a separate platform (control-plane) API manages deployments and clusters.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/centml/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/centml/refs/heads/main/apis.yml)

## Tags

- AI
- LLM
- Inference
- Serverless
- GPU

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### CentML Serverless Inference (Chat Completions) API

OpenAI-compatible chat completions and text completions across open models (Llama, Qwen, DeepSeek, GPT OSS and others) running on CentML-optimized serverless GPU endpoints, with streaming, tool use, and structured outputs.

- **Human URL:** [https://docs.centml.ai/apps/serverless](https://docs.centml.ai/apps/serverless)
- **Base URL:** `https://api.centml.com/openai/v1`

#### Tags

- Chat
- Completions
- LLM

#### Properties

- [Documentation](https://docs.centml.ai/apps/serverless)
- [API Reference](https://docs.centml.ai/clients/sdk)
- [OpenAPI](openapi/centml-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [AsyncAPI](asyncapi/centml-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/centml.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/centml.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CentML Models API

Lists the models available on CentML's OpenAI-compatible serverless endpoints, returning model IDs that can be passed to the chat completions and completions endpoints.

- **Human URL:** [https://docs.centml.ai/apps/serverless](https://docs.centml.ai/apps/serverless)
- **Base URL:** `https://api.centml.com/openai/v1`

#### Tags

- Models
- Catalog

#### Properties

- [Documentation](https://docs.centml.ai/apps/serverless)
- [API Reference](https://centml.ai/models/)
- [OpenAPI](openapi/centml-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/centml.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/centml.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CentML Deployments / Endpoints API

Platform (control-plane) API for creating and managing dedicated inference, compute, and job deployments — including create, retrieve, update, status, and logs — that expose models as autoscaling HTTPS endpoints.

- **Human URL:** [https://docs.centml.ai/apps/inference](https://docs.centml.ai/apps/inference)
- **Base URL:** `https://api.centml.com`

#### Tags

- Deployments
- Endpoints
- Platform

#### Properties

- [Documentation](https://docs.centml.ai/apps/inference)
- [API Reference](https://docs.centml.ai/clients/sdk)
- [OpenAPI](openapi/centml-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/centml.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/centml.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CentML Clusters API

Platform (control-plane) API for listing regional clusters and GPU capacity available to place deployments on, used when selecting hardware and region for dedicated endpoints.

- **Human URL:** [https://docs.centml.ai/apps/inference](https://docs.centml.ai/apps/inference)
- **Base URL:** `https://api.centml.com`

#### Tags

- Clusters
- Capacity
- GPU

#### Properties

- [Documentation](https://docs.centml.ai/apps/inference)
- [API Reference](https://docs.centml.ai/clients/sdk)
- [OpenAPI](openapi/centml-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/centml.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/centml.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/CentML)
- [LinkedIn](https://www.linkedin.com/company/centml)
- [Website](https://centml.ai/)
- [Documentation](https://docs.centml.ai)
- [Plans](plans/centml-plans-pricing.yml)
- [Rate Limits](rate-limits/centml-rate-limits.yml)
- [Fin Ops](finops/centml-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
