# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies (Developers, DevOps Engineers, PM)
- Weekly delivery sync — show progress, updates, and flagged risks (full cross-functional team)
- Demo/Review at the end of each sprint or milestone (includes UX Designers, Product, Support Lead)
- Design reviews (as needed) — validate UX flows and mockups (UX Designer, Product Manager, Developers)
- Documentation reviews (ongoing) — ensure features are properly documented (Technical Writer, Developers)
- Metrics reviews (weekly/biweekly) — track success metrics and KPIs (Data Analyst, Product Manager)
- Support sync (weekly) — review user feedback and escalations (Support Lead, Product Manager, PM)

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review (DevOps Engineer maintains CI/CD pipelines)
  - Tag Technical Writer for documentation review when docs are affected
  - Tag UX Designer when UI/UX changes are included
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown (PM, Data Analyst)
- Monitor success metrics identified in the Project One-pager (Data Analyst, Product Manager)
- Use dashboards for key signals (errors, latency, usage) (DevOps Engineer, Data Analyst)
- Review user satisfaction and support ticket trends (Support Lead, Data Analyst)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
