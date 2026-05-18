# OctoAcme — Release Readiness Review Checklist

## Purpose
Use this checklist before a production release to confirm that the change is ready across engineering, quality, security, operations, and support. It complements [OctoAcme — Release & Deployment Guide](./octoacme-release-and-deployment.md).

## Required sign-off roles
- [Project Manager](./octoacme-roles-and-personas.md#project-managers) — coordinates the review, captures decisions, and confirms timing
- [QA / Test Engineer](./octoacme-roles-and-personas.md#qa--test-engineer) — confirms feature acceptance and test coverage
- [Security / AppSec Reviewer](./octoacme-roles-and-personas.md#security--appsec-reviewer) — confirms required security checks are complete
- [SRE / Operations / Platform Engineer](./octoacme-roles-and-personas.md#sre--operations--platform-engineer) — confirms operational readiness, observability, and rollback
- [Customer Support / Support Lead](./octoacme-roles-and-personas.md#customer-support--support-lead) — confirms support readiness and communication needs

## Release scope and quality
- [ ] Scope for the release is explicitly listed
- [ ] All acceptance criteria are met
- [ ] Required automated tests and smoke tests passed
- [ ] Known issues are documented with mitigations
- [ ] Release notes draft is ready

## Security sign-off
- [ ] Security-sensitive changes were reviewed
- [ ] Required scans and checks completed successfully
- [ ] Open vulnerabilities are accepted, remediated, or blocked from release
- [ ] Incident or escalation contacts are confirmed for release day

## Operational readiness sign-off
- [ ] Deployment plan and window are confirmed
- [ ] Rollback / mitigation plan is documented
- [ ] Monitoring, alerting, and dashboards are ready
- [ ] Runbooks or operator notes are current
- [ ] Post-deploy verification steps are assigned

## Support and communication sign-off
- [ ] Support team has troubleshooting guidance or FAQs
- [ ] Stakeholder and customer communication needs are confirmed
- [ ] Known limitations and escalation paths are documented
- [ ] On-call or support coverage is confirmed for the release window

## Review outcome

| Role | Sign-off status | Notes |
|---|---|---|
| Project Manager |  |  |
| QA / Test Engineer |  |  |
| Security / AppSec Reviewer |  |  |
| SRE / Operations / Platform Engineer |  |  |
| Customer Support / Support Lead |  |  |

## Go / no-go decision
- Decision:
- Release owner:
- Date / time:
- Follow-up actions:

