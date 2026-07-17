# Evidence Access and Assessment Readiness

## Assessment scope

| Field | Value |
|---|---|
| Repository | `symbiotic7solutions/omnyl-eu-governance-evidence` |
| Repository URL | <https://github.com/symbiotic7solutions/omnyl-eu-governance-evidence> |
| Reference branch | `main` |
| Reference commit | `746539defe8bae64ad201f70785e0c6595a035f8` |
| Assessment status | **Not assessable: required evidence package not supplied to the assessment workflow** |

This document records an evidence-intake blocker. It is not a compliance opinion, certification, legal determination, or conclusion about control design or operating effectiveness. The repository URL and reference revision identify the intended evidence source; they do not establish that the assessment workflow received and tested the repository contents.

## Framework criteria in scope

| Framework | Criteria | Determination |
|---|---|---|
| SOC 2 Trust Services Criteria | CC2, CC3, CC4, CC5 | Not assessable |
| ISO/IEC 42001 | Clauses 4.3, 6.1, 7.5, 9.1 | Not assessable |
| EU AI Act | Applicability, role, risk classification, and obligation determination | Cannot be completed |

No conclusion is issued for the remaining SOC 2 common criteria, CC1 through CC9, because the system boundary and control inventory needed to determine relevance and test coverage have not been established.

## Condition

The repository URL has been identified, but the assessment workflow has not received an inspectable evidence package containing the repository files, exact assessed revision, policies, implementation artifacts, and test evidence.

## Criteria

Compliance conclusions must be supported by evidence that is authentic, traceable to the assessed system and period, and reproducible from the identified source revision. Assertions, links without retained artifacts, or inaccessible evidence cannot support a compliant rating.

Testing cannot begin until the assessment workflow has, at minimum:

- an approved system boundary;
- an AI system and control inventory;
- the applicable policy set;
- an evidence repository snapshot tied to an exact commit; and
- records showing control design and operation during the assessment period.

## Impact

The available assessment record cannot support a defensible conclusion regarding:

- SOC 2 CC1 through CC9 applicability, design, or operating effectiveness;
- ISO/IEC 42001 AI management system implementation;
- EU AI Act role, applicability, risk classification, or obligations;
- the completeness of the control inventory or policy set; or
- repository-level implementation, testing, monitoring, or recurring-control claims.

Any such conclusion would be unverifiable until the evidence package is ingested, preserved, and tested.

## Required remediation

Upload a ZIP export of the repository to the assessment workflow. Include Git history metadata or identify the exact commit SHA being assessed. Record the source branch, export date, assessment period, evidence owner, and integrity hash for the uploaded package.

The minimum evidence package should contain:

- README and architecture documentation;
- AI system inventory and intended-use descriptions;
- risk assessments and EU AI Act classification records;
- governance policies, roles, approvals, and management review records;
- data governance and model lifecycle documentation;
- human oversight, logging, transparency, and incident procedures;
- vendor and model-provider due diligence;
- security, access, change-management, and monitoring controls;
- test suites, evaluation results, CI workflows, and deployment configuration; and
- evidence logs demonstrating that recurring controls operated during the assessment period.

## Reassessment gate

Assessment testing may begin only after the evidence package passes these intake checks:

- the archive opens and its integrity hash is recorded;
- the repository identity, branch, and commit match the assessment scope;
- the assessment period and system boundary are approved;
- evidence items have owners, dates, and source references;
- the control inventory maps evidence to the criteria in scope; and
- missing or inaccessible items are recorded as evidence exceptions.

After intake, assess each criterion separately. Do not convert evidence availability into a compliant rating; design and operating effectiveness still require testing.
