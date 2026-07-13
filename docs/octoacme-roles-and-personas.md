# Roles and Personas

This document lists roles and personas defined for OctoAcme projects and how they interact.

## Additional Personas and Role Responsibilities

### Delivery Lead (Program-level)
- Responsibilities: Owns delivery across multiple related projects; coordinates roadmaps, prioritization between teams, and risk trade-offs. Ensures cross-project dependencies are visible and mitigated.
- Interactions: Works with Product Owner(s) for prioritization, Engineering Manager(s) for capacity planning, and Release Manager for scheduling deployments.

### Release Manager
- Responsibilities: Owns release planning, deployment runbooks, cutover plans, and post-release verification. Maintains release calendar and communicates release risks.
- Interactions: Coordinates with Engineering teams, QA, Security, and Site Reliability to schedule releases and rollbacks.

### Quality Advocate (QA Persona)
- Responsibilities: Defines acceptance criteria, test strategies, and ensures automated test coverage requirements are met. Champions quality earlier in the lifecycle.
- Interactions: Partners with Developers for testability, Product for acceptance criteria, and Release Manager to sign off releases.

### Integration / Partner Liaison
- Responsibilities: Manages third-party vendor relationships, integration contracts, API change coordination, and data-sharing agreements.
- Interactions: Works with Architects for integration design, Product for scope, and Legal/Procurement for contracts.

### Stakeholder Communications Lead
- Responsibilities: Owns stakeholder updates, executive summaries, and manages the stakeholder feedback loop. Ensures messaging consistency.
- Interactions: Pulls status from Delivery Lead and Product Owners and coordinates communications with Marketing/Comms as needed.

### Security & Compliance Representative
- Responsibilities: Reviews feature designs for security/compliance impacts, signs off on risk assessments, and ensures necessary controls are documented.
- Interactions: Works with Architects, Engineering, and Release Manager to ensure compliance checks are included in the release checklist.

## How this improves outcomes
- Clearer ownership reduces delays: explicit role responsibilities remove ambiguity about who makes decisions or performs key tasks.
- Faster onboarding: new team members can quickly understand where responsibilities lie.
- Better risk and release management: introducing Release Manager and Quality Advocate roles improves gating and reduces incident rates.
- Smoother third-party coordination: Integration Liaisons reduce missed compatibility issues and contract surprises.

## Suggested placement
Add a new section in docs/octoacme-roles-and-personas.md titled "Additional Personas and Role Responsibilities" and include the above entries. Where applicable, add cross-references to existing roles and update any diagrams that show role interactions.

## Next steps (suggested)
- Review proposed personas with Delivery Leads and Product Owners
- Iterate language to match existing role naming conventions
- Update process diagrams and notify teams of changes
