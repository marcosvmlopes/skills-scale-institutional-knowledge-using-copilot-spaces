# OctoAcme — Project docs

This repository contains work for the "Scale institutional knowledge using Copilot Spaces" initiative.

Overview
--------
This docs folder holds high-level documentation intended to support onboarding, collaboration, and knowledge capture for OctoAcme projects.

Project management processes (brief)
-----------------------------------
OctoAcme follows a lightweight, outcome-focused process designed to scale institutional knowledge and make work traceable and reviewable.

- Planning and cadence
  - Work is planned in short iterations (1–2 week sprints) with a prioritized backlog.
  - Milestones are used for larger deliverables and to align cross-team work.

- Issue-driven development
  - All work starts as an issue describing the problem, acceptance criteria, and any relevant context.
  - Issues are tagged with labels (priority, type, area) to make triage and filtering straightforward.

- Pull requests and reviews
  - Changes are made on feature branches and proposed via pull requests.
  - Each PR must include a clear description, link to related issues, and tests or QA steps.
  - At least one reviewer is required; code owners are requested where applicable.

- Knowledge capture and documentation
  - Decision records (ADRs) are created for important architectural choices.
  - Project notes, retrospectives, and onboarding materials are stored in docs/ and Copilot Spaces.
  - Short how-to guides and runbooks are preferred over long-form manuals to keep information actionable.

- Quality and automation
  - CI runs automated tests and linters on each PR; merges are gated on passing checks.
  - Important releases are tagged and release notes are maintained in the changelog.

- Communication and retrospectives
  - Weekly syncs and end-of-sprint retrospectives identify improvements to process and tooling.
  - Action items from retros are tracked as issues and prioritized in the backlog.

How this repo maps to the process
---------------------------------
- Issues: use GitHub issues to describe and triage work.
- Branches: create feature branches; use short-lived branches tied to issues.
- Docs: this docs/ folder holds project-level docs, onboarding, and process guidance.
- Reviews: request reviewers on PRs; link PRs to issues to maintain traceability.

If you want this README expanded (more templates, ADR examples, a contributor guide, or CI links), tell me what to add and I'll include it in the PR.
