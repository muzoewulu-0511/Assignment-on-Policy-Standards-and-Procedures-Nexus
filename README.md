# Nexus Financial Services | Information Security Policy Framework

![Project](https://img.shields.io/badge/Project-GRC%20Case%20Study-blue)
![Focus](https://img.shields.io/badge/Focus-Policy%20Governance-005A9C)
![Deliverable](https://img.shields.io/badge/Deliverable-Framework%20%26%20Draft%20Policy-008080)
![Status](https://img.shields.io/badge/Policy%20Status-Draft%20for%20Board%20Approval-orange)

A team-developed information security policy framework connecting management direction, document governance, operational requirements, and accountability.

The project addresses inconsistent security practices at Nexus Financial Services through a five-layer documentation hierarchy, a governance matrix for four core policies, and a draft Information Security Policy.

> This repository presents a documentation-based case study. It does not demonstrate actual Board approval, deployed security controls, regulatory compliance, or ISO 27001 certification.

## Project Overview

Nexus Financial Services is described as a growing financial services organization headquartered in Lagos, Nigeria, with:

- 150 employees
- $800 million in assets
- Cloud-based applications
- Remote staff
- Payment systems

The organization already has security documents, but lacks a consistent framework for maintaining, approving, communicating, and enforcing them.

This project treats the central challenge as a governance problem—not simply a shortage of policies.

## Problem Statement

The case study identifies three connected weaknesses:

1. Policies are outdated and lack clear owners or review schedules.
2. Departments and technical teams follow different security practices.
3. Data classification, access management, and staff training are inconsistent.

These gaps make it difficult to establish a single source of authority, maintain current requirements, assign accountability, and demonstrate consistent implementation.

## Project Objectives

- Define a coherent information security documentation structure.
- Map business problems to the appropriate documentation layers.
- Establish governance for four core policies.
- Define a controlled policy lifecycle.
- Draft an overarching Information Security Policy.
- Connect policy requirements to implementation and audit evidence.

## Key Deliverables

| Deliverable | Included Content |
|---|---|
| Documentation framework | Five layers with purposes, approval roles, and proposed supporting documents |
| Problem-to-document mapping | Links governance weaknesses to the documents needed to address them |
| Core-policy model | Defines how Information Security, Acceptable Use, Access Control, and Data Classification policies connect |
| Policy lifecycle | Covers identification, development, review, approval, publication, training, monitoring, revision, and retirement |
| Governance matrix | Defines ownership, review, approval, training, enforcement, and exception requirements |
| Draft Information Security Policy | Provides overarching security direction, responsibilities, and mandatory requirements |
| Document controls | Includes a document ID, version history, status, classification, and approval arrangements |

The Information Security Policy is drafted in the report. The other three core policies are described and governed, but are not supplied as complete standalone policies.

## Documentation Framework

The framework organizes security documentation into five complementary layers:

| Layer | Question Answered | Examples Proposed in the Report |
|---|---|---|
| Policy | What must the organization achieve? | Information Security, Acceptable Use, Access Control, Data Classification |
| Standard | What mandatory requirements must be met? | Authentication, encryption, logging, cloud security, privileged access |
| Procedure | How is the requirement performed? | Joiner–Mover–Leaver, access reviews, incident response, exception management |
| Guideline | What practices are recommended? | Secure remote working, phishing recognition, safe use of messaging and generative AI tools |
| Baseline | What minimum configuration must exist? | Endpoint, mobile device, cloud tenant, server, network, and payment-system configurations |

These are documentation categories and proposed artifacts, not evidence that every listed document or configuration has been implemented.

## How the Core Policies Connect

For an employee handling customer financial information:

- The Data Classification Policy determines the information’s sensitivity.
- The Access Control Policy determines who may access it.
- The Acceptable Use Policy establishes permitted use.
- The Information Security Policy provides overarching direction and accountability.

Supporting standards, procedures, guidelines, and baselines translate this direction into practical requirements.

```text
Information Security Direction
              |
              v
Core Policies and Assigned Accountability
              |
              v
Standards | Procedures | Guidelines | Baselines
              |
              v
Implementation and Staff Communication
              |
              v
Monitoring, Evidence, Review, and Improvement
```

## Policy Governance

The governance matrix addresses eight requirements for each core policy:

1. Owner
2. Reviewer
3. Approver
4. Review frequency
5. Version control
6. Training requirements
7. Enforcement mechanism
8. Exception process

### Proposed Ownership and Approval

| Policy | Owner | Approval Authority |
|---|---|---|
| Information Security | Chief Information Security Officer | Board of Directors, via the Board Risk Committee |
| Acceptable Use | CISO, with HR as co-sponsor | CEO / Executive Committee |
| Access Control | CISO, with implementation by the Head of IT | Executive Committee, endorsed by the Board Risk Committee |
| Data Classification | Data Protection Officer | Executive Committee, endorsed by the Board Risk Committee |

These are proposed case-study responsibilities, not verified appointments.

## Policy Lifecycle

The framework defines the following lifecycle:

```text
Identify → Develop → Review → Approve → Publish
                                          |
                                          v
Retire ← Review and Update ← Monitor ← Implement
                                          ^
                                          |
                                Train and Communicate
```

Lifecycle requirements include:

- A central policy register
- Defined approval authority
- Version history and controlled publication
- Training and acknowledgment records
- Annual and event-triggered reviews
- Documented enforcement
- Time-limited exceptions to supporting requirements
- Withdrawal and archiving of superseded versions

## Draft Information Security Policy

### Document Details

| Field | Value in the Report |
|---|---|
| Document ID | NFS-ISP-001 |
| Initial draft version | 0.1 |
| Draft date | October 17, 2026 |
| Owner | CISO |
| Classification | Internal |
| Status | Draft for Board approval |
| Effective date | Pending Board approval |

### Coverage

The draft policy addresses:

- Purpose, scope, and objectives
- Roles and responsibilities
- Information security risk management
- Information classification and protection
- Identity and access control
- Incident management
- Third-party security
- Awareness and training
- Compliance monitoring
- Enforcement
- Exceptions
- Policy review and maintenance

### Selected Proposed Requirements

Examples of requirements written into the draft include:

- Four information classifications: Public, Internal, Confidential, and Restricted
- MFA for remote access, cloud applications, payment systems, and privileged accounts
- Quarterly access reviews and monthly privileged-access reviews
- Annual security awareness training
- A training-completion target of at least 95%
- Quarterly security reporting to the Board Risk Committee
- Documented, risk-assessed exceptions to supporting standards or baselines
- A maximum exception duration of six months

These are proposed organizational requirements. The project does not demonstrate that they have been approved, implemented, or measured.

## Reference and Regulatory Context

The report discusses:

- Nigeria Data Protection Act 2023
- CBN cybersecurity requirements applicable to the organization’s license category
- PCI DSS where payment card data is handled
- ISO/IEC 27001:2022 as a management-system reference
- NIST SP 800-63B as an authentication reference

These references inform the draft. Their inclusion does not establish regulatory applicability or compliance.

Before operational use, validate the organization’s license category, current regulatory requirements, applicable standard versions, and notification obligations.

## Tools, Formats, and Technologies

| Item | Role |
|---|---|
| DOCX | Source framework and policy report |
| Markdown | Repository documentation |
| Governance matrix | Accountability and policy administration |
| Documentation hierarchy | Organization of security requirements |
| Policy lifecycle model | Document development and maintenance |
| ISO/IEC 27001:2022 | Information security management reference |

The report also discusses IAM, MFA, PAM, SIEM, DLP, endpoint protection, and cloud configuration baselines as proposed mechanisms or examples.

No specific security product, cloud deployment, programming language, application runtime, or automation pipeline is confirmed as implemented.

## Repository Structure

Suggested layout using the supplied document:

```text
.
├── README.md
└── INFORMATION-SECURITY-POLICY-FRAMEWORK.docx
```

## Getting Started

### Prerequisites

- A DOCX-compatible document viewer
- Git, only if cloning the repository

This is a documentation project. No application installation, dependencies, cloud credentials, or build steps are required.

### Review the Framework

Download `INFORMATION-SECURITY-POLICY-FRAMEWORK.docx` and open it in a compatible viewer.

Alternatively, replace the placeholders and clone the repository:

```bash
git clone [https://github.com/](https://github.com/)<github-username>/<repository-name>.git
cd <repository-name>
```

Open the DOCX report to review the complete framework and draft policy.

## Usage

### For Recruiters and Hiring Managers

Review the project to assess:

- Information security policy development
- Governance and accountability design
- Document hierarchy and lifecycle management
- Stakeholder responsibility mapping
- Risk-based exception management
- Compliance-aware business writing
- Collaborative GRC documentation

### For Learners and Reviewers

1. Start with the business problem.
2. Review how each weakness maps to documentation layers.
3. Examine the relationships between the four core policies.
4. Review ownership and approval requirements in the governance matrix.
5. Read the draft Information Security Policy.
6. Identify the supporting documents and evidence needed for implementation.

For organizational reuse, adapt roles, deadlines, controls, and approval arrangements to the actual operating environment.

## Project Status and Limitations

- The Information Security Policy remains a draft for Board approval.
- Supporting policies, standards, procedures, and baselines are largely proposed rather than supplied as complete documents.
- No approval records, training results, deployed configurations, or monitoring evidence are included.
- The report describes a case-study environment, not a verified organizational assessment.
- Some governance details require reconciliation before adoption, including the distinction between policy exceptions and exceptions to supporting documents.
- Regulatory interpretations and referenced guidance require validation before operational use.

## Future Enhancements

Potential additions—not currently included—are:

- Standalone Acceptable Use Policy
- Standalone Access Control Policy
- Standalone Data Classification Policy
- Policy register template
- Exception request form and register
- Policy approval and review checklist
- Staff acknowledgment and training tracker
- Supporting standards and procedures
- Governance KPI/KRI dashboard
- PDF version of the report
- Exported lifecycle and framework diagrams

## Contributing

To propose an improvement:

1. Open an issue explaining the proposed change and rationale.
2. Identify affected policies, roles, or supporting documents.
3. Submit focused changes through a pull request.
4. Explain any changes to regulatory references or mandatory requirements.

Please:

- Preserve team attribution.
- Keep draft requirements separate from implemented practices.
- Use synthetic information in examples.
- Do not upload confidential organizational records, credentials, or personal information.
- Respect third-party copyright and licensing restrictions.

## Project Team

The source document credits:

- Angela Amuzu
- Christy Aghe
- Joel Kamanda
- Maureen Uzoewulu
- Olatunji Afolayan
- Oreoluwa Lawal

Individual contribution details: <Add verified responsibilities if available.>

### Portfolio Contact

Maureen Uzoewulu

- GitHub: <GitHub profile URL>
- LinkedIn: <LinkedIn profile URL>
- Contact: <optional professional email>

## References

The source report cites:

- 10Alytics access-control policy and policy-governance course materials
- Central Bank of Nigeria cybersecurity guidance
- Nigeria Data Protection Act 2023
- Nigeria Data Protection Commission guidance
- ISO/IEC 27001:2022
- PCI Security Standards Council documentation
- NIST SP 800-63B

See the report for full reference details.

## License and Publication Permissions

<Specify reuse permissions and add a corresponding LICENSE file if appropriate.>

Confirm team consent and publication permission before sharing the report publicly. The source document is marked “Internal”; clarify whether this is a case-study classification or an actual distribution restriction.

Any repository license should distinguish original team content from third-party materials.
