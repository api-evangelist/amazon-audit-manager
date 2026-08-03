# Amazon Audit Manager

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
