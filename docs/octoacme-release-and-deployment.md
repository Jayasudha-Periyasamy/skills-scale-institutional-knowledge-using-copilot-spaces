# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans (verified by DevOps Engineer)
- Release notes drafted
- Rollback / mitigation plan documented (DevOps Engineer)
- Smoke tests prepared
- Support Lead notified of upcoming release

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable) — DevOps Engineer responsibility
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred) — DevOps Engineer executes
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders, Support Lead, and support team

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call (Support Lead coordinates)
  - Rollback to last known-good release if necessary (DevOps Engineer executes)
  - Triage root cause and capture action items
  - Support Lead communicates with affected users and stakeholders

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
