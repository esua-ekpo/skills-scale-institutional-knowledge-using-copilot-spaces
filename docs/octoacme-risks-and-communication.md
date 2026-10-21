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

## Role-Based Ownership for Risk and Communication
Different types of risk should have a clear owner and escalation path.

- Project Manager: owns overall project risk tracking, status communication, and dependency management
- Technical Lead: owns technical debt, integration risk, and implementation-related blockers
- QA / Test Lead: owns quality, regression, and validation risk
- Security / Compliance Partner: owns controls, policy, privacy, and compliance concerns
- Customer Success / Stakeholder Liaison: owns user-impact and stakeholder communication risks

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

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
- For security incidents, follow the security incident runbook and notify Security on-call
- When customer or stakeholder impact is significant, involve the Customer Success / Stakeholder Liaison and Product lead in the communication path

