# Release Checklist

Purpose: Ensure releases are coordinated, safe, and verifiable. This checklist should be completed and signed off by the Release Manager, Quality Advocate, and Security & Compliance Representative (as applicable) before a production deployment.

Pre-release
- [ ] Confirm release scope and included changes (link to PRs and changelog)
- [ ] Confirm feature flags and toggles are defined and tested
- [ ] Run all automated test suites (unit, integration, E2E) — all must pass or have documented exceptions
- [ ] Verify migration scripts and data changes with DB owner
- [ ] Security review completed for high-risk items
- [ ] Confirm rollback plan and validate rollback steps
- [ ] Notify stakeholders and update release calendar
- [ ] Confirm monitoring and alerting for new changes
- [ ] Confirm runbook and on-call contacts are up-to-date

Deployment
- [ ] Execute deployment plan per runbook
- [ ] Monitor health checks and metrics during rollout
- [ ] Run smoke tests and verify basic user flows
- [ ] Confirm no critical alerts are firing

Post-release
- [ ] Verify post-release acceptance criteria
- [ ] Close release notes and update documentation
- [ ] Retrospective note and actions logged for follow-up
- [ ] If rollback occurred, follow post-mortem procedures and update runbook

Sign-offs:
- Release Manager: ____________________  Date: _______
- Quality Advocate: ____________________ Date: _______
- Security & Compliance Rep: ___________ Date: _______
