# Amazon Well-Architected Tool (amazon-well-architected-tool)
The AWS Well-Architected Tool helps you review your workloads and compare them to the latest AWS architectural best practices. It provides a consistent process for evaluating architectures and implementing designs that scale over time across five pillars: operational excellence, security, reliability, performance efficiency, and cost optimization. The tool offers lens catalogs, custom lenses, profiles, review templates, and API-driven extensibility for integration into governance workflows.

**URL:** [https://raw.githubusercontent.com/api-evangelist/amazon-well-architected-tool/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/amazon-well-architected-tool/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Architecture, AWS, Best Practices, Cloud Governance, Well-Architected, Workloads

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### AWS Well-Architected Tool API
The AWS Well-Architected Tool API provides programmatic access to create and manage workloads, lenses, milestones, profiles, review templates, and review reports. It enables integration of the Well-Architected review process into DevOps workflows and automation pipelines for continuous architecture assessment. The API supports 56 operations covering workload management, lens operations, lens reviews, answers, milestones, profiles, review templates, notifications, checks, and administration.

**Human URL:** [https://aws.amazon.com/well-architected-tool/](https://aws.amazon.com/well-architected-tool/)

#### Tags:

 - Architecture, AWS, Best Practices, Cloud Governance, Workloads, Lenses

#### Properties

- [Documentation](https://docs.aws.amazon.com/wellarchitected/latest/userguide/)
- [APIReference](https://docs.aws.amazon.com/wellarchitected/latest/APIReference/)
- [GettingStarted](https://docs.aws.amazon.com/wellarchitected/latest/userguide/getting-started.html)
- [Pricing](https://aws.amazon.com/well-architected-tool/pricing/)
- [FAQ](https://aws.amazon.com/well-architected-tool/faqs/)
- [OpenAPI](openapi/amazon-well-architected-tool-openapi-original.yaml)
- [JSONSchema](json-schema/well-architected-tool-workload-schema.json)
- [JSONLD](json-ld/amazon-well-architected-tool-context.jsonld)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [Website](https://aws.amazon.com/well-architected-tool/)
- [Documentation](https://docs.aws.amazon.com/wellarchitected/latest/userguide/)
- [Console](https://console.aws.amazon.com/wellarchitected/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [SignUp](https://signin.aws.amazon.com/signup?request_type=register)
- [Login](https://aws.amazon.com/console/)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [GitHubOrganization](https://github.com/aws)
- [GitHubRepository](https://github.com/aws-samples/custom-lens-wa-hub)
- [Compliance](https://aws.amazon.com/compliance/)

## Features

| Name | Description |
|------|-------------|
| Lens Catalog | Expert-authored review lenses from AWS covering diverse technology and industry-specific pillars, continuously refreshed with latest best practices. |
| Custom Lenses | Create organization-specific lenses that combine internal best practices with AWS guidance, shareable with up to 300 IAM users or across AWS Organizations. |
| Profiles | Pre-define business goals to auto-generate prioritized review questions tailored to your workload context. |
| Review Templates | Standardize answers across multiple workloads to ensure consistent architectural reviews at scale. |
| Enhanced Collaboration | Share workloads and custom lenses with IAM users or integrate with AWS Organizations for organization-wide access and visibility. |
| Service Integration | Native integration with AWS Trusted Advisor and AWS Service Catalog AppRegistry to reduce manual review effort. |
| API-Driven Extensibility | Robust APIs allow extending Well-Architected functionality into existing architecture governance processes, applications, and workflows. |
| Milestone Tracking | Save milestones, implement improvements, and measure progress over time with point-in-time snapshots of workload review state. |
| Compliance and Regulatory Support | Available in GovCloud (US) with FedRAMP compliance for organizations with stringent regulatory requirements. |
| Consolidated Reporting | Generate consolidated reports across workloads for governance and executive visibility into architectural risk posture. |

## Use Cases

| Name | Description |
|------|-------------|
| Architecture Reviews and Governance | Evaluate cloud workload architecture quality against AWS best practices across the five Well-Architected pillars. |
| Multi-Workload Standardization | Use review templates to standardize architectural answers and enforce consistent governance across multiple workloads and teams. |
| Industry-Specific Best Practice Implementation | Apply industry-specific and technology-specific lenses from the lens catalog to assess specialized workloads. |
| Regulatory Compliance Assessment | Evaluate workloads for FedRAMP, GovCloud, and other regulatory compliance requirements through targeted lenses. |
| DevOps Pipeline Integration | Integrate Well-Architected reviews into CI/CD workflows and automation pipelines for continuous architecture assessment. |
| Cross-Team Architectural Alignment | Share workloads with reviewers and stakeholders to facilitate collaborative architectural decision-making across teams. |
| Sustainability Goal Realization | Use the sustainability pillar to minimize environmental impact and meet organizational sustainability commitments. |

## Integrations

| Name | Description |
|------|-------------|
| AWS Trusted Advisor | Integration with AWS Trusted Advisor provides automated checks that complement manual Well-Architected review processes. |
| AWS Service Catalog AppRegistry | AppRegistry integration enables linking Well-Architected workloads to application metadata for richer governance context. |
| AWS Organizations | Organization-level sharing of workloads and custom lenses for enterprise-wide architectural governance programs. |
| AWS IAM | Fine-grained access control via AWS IAM for workload sharing and reviewer management within the tool. |
| AWS CloudFormation | Workloads can be associated with CloudFormation stacks for automated resource discovery and architecture documentation. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amazon Well-Architected Tool OpenAPI](openapi/amazon-well-architected-tool-openapi-original.yaml)

### JSON Schema

314 JSON Schema files extracted from the OpenAPI specification covering all API resource types.

### JSON Structure

314 JSON Structure files converted from JSON Schema definitions.

### JSON-LD

- [Amazon Well-Architected Tool Context](json-ld/amazon-well-architected-tool-context.jsonld)

### Examples

117 example JSON files generated from JSON Schema definitions.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [AWS Well-Architected Tool API](capabilities/shared/well-architected-tool.yaml) — 9 operations for workload management, lens reviews, milestones, profiles, and reporting

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Architecture Governance](capabilities/architecture-governance.yaml) | AWS Well-Architected Tool | 9 | Cloud Architect, Governance Team |

## Vocabulary

- [Amazon Well-Architected Tool Vocabulary](vocabulary/amazon-well-architected-tool-vocabulary.yaml) — Unified taxonomy mapping 10 resources, 10 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amazon Well-Architected Tool Spectral Rules](rules/amazon-well-architected-tool-spectral-rules.yml) — 22 rules across 9 categories enforcing Amazon Well-Architected Tool API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
