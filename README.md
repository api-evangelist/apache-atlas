# Apache Atlas (apache-atlas)
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
