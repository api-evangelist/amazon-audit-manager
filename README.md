# Amazon Audit Manager

AWS Audit Manager helps you continuously audit your AWS usage to simplify how you assess risk and compliance with regulations and industry standards.

## Overview

The Amazon Audit Manager API enables programmatic control over assessments, compliance frameworks, controls, evidence collection, and assessment reports. It enables building automated compliance monitoring solutions backed by AWS service data.

## API Documentation

- **Human URL:** https://docs.aws.amazon.com/audit-manager/latest/APIReference/Welcome.html
- **Base URL:** https://auditmanager.us-east-1.amazonaws.com

## Features

- Continuous compliance monitoring with automated evidence collection
- Pre-built frameworks for SOC 2, PCI DSS, HIPAA, GDPR, and more
- Custom framework and control creation for internal policies
- Automated evidence collection from AWS Config, Security Hub, and CloudTrail
- Evidence folder organization by control and control set
- Assessment delegation to process owners and resource owners
- Assessment report generation in PDF format
- Multi-account support through AWS Organizations
- Evidence finder for cross-assessment evidence search
- Integration with AWS Security Hub for security findings

## Use Cases

- Automate SOC 2 compliance evidence collection
- Prepare for PCI DSS and HIPAA audits with continuous monitoring
- Build custom compliance frameworks for internal policies
- Delegate control reviews to business process owners
- Generate audit-ready reports for external auditors
- Monitor compliance posture across multiple AWS accounts

## Artifacts

### OpenAPI Specification
`openapi/amazon-audit-manager-openapi.yml`

Complete OpenAPI 3.1.0 specification covering all Audit Manager API paths.

### Spectral Rules
`rules/amazon-audit-manager-spectral-rules.yml`

### Naftiko Capabilities
- `capabilities/shared/audit-manager-api.yaml` — Shared per-API capability definition
- `capabilities/compliance-auditing.yaml` — Workflow capability for compliance auditing

### Vocabulary
`vocabulary/amazon-audit-manager-vocabulary.yaml`

### JSON Schemas
`json-schema/` — 62 JSON Schema files for all objects.

### JSON Structures
`json-structure/` — 62 JSON Structure files.

### JSON-LD Context
`json-ld/amazon-audit-manager-context.jsonld`

### Examples
`examples/` — 62 example JSON files.

## Integrations

- AWS Config
- AWS Security Hub
- AWS CloudTrail
- AWS IAM
- Amazon S3
- Amazon SNS
- AWS Organizations
- AWS KMS
- Amazon CloudWatch
- AWS Systems Manager

## Tags

Amazon Audit Manager, Compliance, Audit, Risk Management, AWS

## Maintainers

- Kin Lane (kin@apievangelist.com)
