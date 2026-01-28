# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support, customers)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status
- Coordinate with Support Lead for customer-facing communications
- Involve Business Analyst for stakeholder requirement updates

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication (coordinated by Support Lead)
- Triage summary
- Actions being taken (with DevOps Engineer input)
- Expected timeline
- Post-incident blameless retrospective scheduled (facilitated by Scrum Master or PM)

## Escalation Paths
- Team-level -> Scrum Master -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call
- For infrastructure/deployment issues: DevOps Engineer -> Engineering Lead
- For production incidents affecting users: Support Lead -> PM -> Product Lead
- For design/UX concerns: UX Designer -> Product Manager -> Product Lead
