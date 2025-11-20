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
- Support Lead coordinates customer-facing communications
- Data Analyst provides metrics and impact data for stakeholder reports
- Technical Writer ensures release notes and documentation are clear and timely
- UX Designer shares design rationale and user research insights as needed

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call (DevOps Engineer involved in incident response)
- For customer-impacting issues, Support Lead coordinates with PM and Product Manager
- For infrastructure/reliability issues, DevOps Engineer escalates to Infrastructure Lead
- For usability concerns, UX Designer collaborates with Product Manager on solutions
