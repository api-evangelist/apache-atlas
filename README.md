# Apache Atlas (apache-atlas)

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

Apache Atlas is a scalable and extensible set of core foundational data governance services developed by the Apache Software Foundation. It enables enterprises to effectively meet their compliance requirements within Hadoop and allows integration with the whole enterprise data ecosystem. Atlas provides metadata management, data classification, lineage tracking, business glossary, and a REST API for programmatic governance operations. It supports discovery, auditing, and policy management for enterprise data assets.

**URL:** [https://atlas.apache.org/](https://atlas.apache.org/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - Apache, Big Data, Compliance, Data Governance, Data Lineage, Hadoop, Metadata, Open Source

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache Atlas REST API
The Atlas REST API provides endpoints for managing types, entities, lineage, discovery, and glossary resources, enabling programmatic metadata management and data governance operations.

**Human URL:** [https://atlas.apache.org/api/v2/index.html](https://atlas.apache.org/api/v2/index.html)

#### Tags

 - Governance, Metadata, REST

#### Properties

- [Documentation](https://atlas.apache.org/api/v2/index.html)
- [OpenAPI](openapi/apache-atlas-rest-openapi.yaml)
- [GettingStarted](https://atlas.apache.org/quick_start_v2.html)

## Common Properties

- [GitHubOrganization](https://github.com/apache)
- [GitHubRepository](https://github.com/apache/atlas)
- [Documentation](https://atlas.apache.org/)
- [GettingStarted](https://atlas.apache.org/quick_start_v2.html)
- [Support](https://atlas.apache.org/mailing_list.html)
- [TermsOfService](https://www.apache.org/licenses/)
- [ChangeLog](https://github.com/apache/atlas/releases)

## Features

| Name | Description |
|------|-------------|
| Metadata Management | Centrally manage metadata for enterprise data assets including Hive tables, HDFS files, Kafka topics, HBase tables, and Spark jobs. |
| Data Classification | Apply classification tags to data assets for sensitivity classification (PII, PHI, confidential) and policy enforcement. |
| Data Lineage Tracking | Automatically capture and visualize data lineage across data pipeline stages for impact analysis and compliance. |
| Business Glossary | Manage a centralized business glossary of terms and categories to standardize data definitions across the organization. |
| REST API | Comprehensive REST API for programmatic metadata management, discovery, lineage retrieval, and type definition management. |
| Search and Discovery | Find data assets using basic, full-text, DSL, and attribute-based search across all registered metadata. |
| Policy-Based Data Access | Integrate with Apache Ranger for attribute-based access control policies driven by Atlas classification tags. |
| Auditing | Comprehensive audit trail of all metadata changes and entity operations for compliance and governance. |
| Hook-Based Metadata Collection | Hooks for Hive, HBase, Sqoop, Storm, and other Hadoop ecosystem tools for automatic metadata harvesting. |
| Type System | Extensible type system for defining custom entity types, classification types, and relationship types. |

## Use Cases

| Name | Description |
|------|-------------|
| Data Governance and Compliance | Track data assets, apply classifications, and enforce policies for GDPR, HIPAA, and CCPA compliance. |
| Data Lineage Analysis | Trace data from source to consumption to understand pipeline impact and debug data quality issues. |
| Metadata-Driven Data Discovery | Enable data consumers to find relevant datasets using classification-based and attribute-based search. |
| Data Catalog Integration | Serve as the metadata backbone for enterprise data catalogs and data mesh architectures. |
| Sensitive Data Identification | Classify PII and sensitive data assets and integrate with Ranger for attribute-based access control. |
| Business Glossary Management | Maintain standard business definitions and link them to technical metadata for consistent data interpretation. |

## Integrations

| Name | Description |
|------|-------------|
| Apache Hive | Native Hive hook for automatic metadata harvesting of Hive databases, tables, and query lineage. |
| Apache Ranger | Integration with Ranger for policy-based data access control driven by Atlas classification tags. |
| Apache Kafka | Kafka hook for tracking Kafka topics and message schema metadata. |
| Apache HBase | HBase hook for capturing table and namespace metadata. |
| Apache Spark | Spark integration for capturing dataset and job-level lineage from Spark applications. |
| Apache Sqoop | Sqoop hook for importing relational database metadata and lineage into Atlas. |
| Cloudera Data Platform | Native integration with Cloudera Data Platform (CDP) as the metadata management backbone. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache Atlas REST API](openapi/apache-atlas-rest-openapi.yaml)

### JSON Schema

11 schema files covering Atlas entities, types, search results, lineage info, glossary, relationships, and error responses.

### JSON-LD

- [Apache Atlas Context](json-ld/apache-atlas-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Apache Atlas REST API](capabilities/shared/atlas-rest.yaml) — 8 operations for entity management, search, lineage, and glossary

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Apache Atlas Data Governance](capabilities/atlas-data-governance.yaml) | Atlas REST | 6 | Data Governance Team, Data Engineer |

## Vocabulary

- [Apache Atlas Vocabulary](vocabulary/apache-atlas-vocabulary.yaml) — Unified taxonomy mapping 8 resources, 5 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Apache Atlas Spectral Rules](rules/apache-atlas-spectral-rules.yml) — 12 rules across 6 categories enforcing Apache Atlas API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
