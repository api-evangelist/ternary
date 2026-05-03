# Ternary

Ternary is a multi-cloud FinOps platform providing cost visibility, anomaly detection, commitment management, forecasting, and Kubernetes cost allocation for cloud environments. Originally purpose-built for Google Cloud, Ternary now supports AWS, Azure, OCI, and other cloud providers through its Universal Spend Ledger. The REST API provides programmatic access to all platform capabilities.

**Type:** company  
**Website:** [https://ternary.app/](https://ternary.app/)  
**Documentation:** [https://docs.ternary.app/](https://docs.ternary.app/)

## Tags

Cloud Cost Management, Cost Optimization, FinOps, Google Cloud, Kubernetes, Multi-Cloud

## APIs

### Ternary API
Ternary provides a REST API exposing all platform capabilities programmatically. Customers can automate FinOps workflows, integrate cost data into CI/CD pipelines, trigger alerts based on spend thresholds, manage commitments, and generate reports. Authentication uses API keys generated from the platform.

- **Documentation:** [https://docs.ternary.app/](https://docs.ternary.app/)
- **API Reference:** [https://docs.ternary.app/reference](https://docs.ternary.app/reference)
- **OpenAPI:** [openapi/ternary-openapi.yml](openapi/ternary-openapi.yml)

## OpenAPI Specifications

| Spec | Description |
|---|---|
| [ternary-openapi.yml](openapi/ternary-openapi.yml) | Ternary REST API - cost allocation, anomalies, commitments, budgets, reports, Kubernetes |

## Spectral Rules

| Ruleset | Description |
|---|---|
| [ternary-rules.yml](rules/ternary-rules.yml) | Spectral rules enforcing Ternary API conventions |

## Naftiko Capabilities

### Shared Definitions

| File | Description |
|---|---|
| [capabilities/shared/ternary.yaml](capabilities/shared/ternary.yaml) | Ternary API consumed definition |

### Workflow Capabilities

| File | Description |
|---|---|
| [capabilities/cloud-cost-management.yaml](capabilities/cloud-cost-management.yaml) | Full FinOps workflow (anomalies, budgets, commitments, allocations, reports, Kubernetes) |

## JSON Schemas

| Schema | Description |
|---|---|
| [ternary-anomaly-schema.json](json-schema/ternary-anomaly-schema.json) | Cloud cost anomaly schema |
| [ternary-budget-schema.json](json-schema/ternary-budget-schema.json) | Cloud cost budget schema |

## JSON Structures

| Structure | Description |
|---|---|
| [ternary-anomaly-structure.json](json-structure/ternary-anomaly-structure.json) | Anomaly field documentation |

## JSON-LD

| Context | Description |
|---|---|
| [ternary-context.jsonld](json-ld/ternary-context.jsonld) | JSON-LD context for FinOps and cloud cost concepts |

## Examples

| Example | Description |
|---|---|
| [ternary-list-anomalies-example.json](examples/ternary-list-anomalies-example.json) | List cost anomalies request/response |
| [ternary-create-budget-example.json](examples/ternary-create-budget-example.json) | Create budget request/response |

## Vocabulary

| Vocabulary | Description |
|---|---|
| [ternary-vocabulary.yml](vocabulary/ternary-vocabulary.yml) | FinOps and cloud cost management vocabulary |

## Links

- **GCP Integration:** [https://ternary.app/integrations/google-cloud-gcp/](https://ternary.app/integrations/google-cloud-gcp/)
- **Kubernetes:** [https://ternary.app/integrations/kubernetes/](https://ternary.app/integrations/kubernetes/)
- **Blog:** [https://ternary.app/blog/](https://ternary.app/blog/)

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
