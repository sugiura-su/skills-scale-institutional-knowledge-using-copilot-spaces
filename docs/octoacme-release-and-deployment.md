# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans (DevOps Engineer validates pipeline)
- Release notes drafted (Technical Writer reviews for clarity)
- Documentation updated and published (Technical Writer)
- Rollback / mitigation plan documented (DevOps Engineer)
- Smoke tests prepared (QA with DevOps Engineer)
- Support team briefed on changes (Support Lead coordinates)
- Monitoring and alerts configured (DevOps Engineer, Data Analyst)
- Success metrics baseline captured (Data Analyst)

## Deployment Checklist
- [ ] Deployment window scheduled (if needed) — PM coordinates
- [ ] Backup or snapshot (if applicable) — DevOps Engineer
- [ ] Deploy to staging and run smoke tests — DevOps Engineer, QA
- [ ] Deploy to production (automated pipeline preferred) — DevOps Engineer
- [ ] Run post-deploy verifications — DevOps Engineer, QA
- [ ] Verify monitoring and alerts are working — DevOps Engineer, Data Analyst
- [ ] Announce release to stakeholders and support — PM, Support Lead
- [ ] Update documentation to reflect release — Technical Writer
- [ ] Monitor success metrics and user feedback — Data Analyst, Support Lead

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call (DevOps Engineer leads technical response)
  - Rollback to last known-good release if necessary (DevOps Engineer executes)
  - Communicate status to customers if impacted (Support Lead coordinates)
  - Triage root cause and capture action items (cross-functional team)
  - Track impact metrics and recovery (Data Analyst)

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
