# OctoAcme Project Management Documentation

## Overview

OctoAcme follows a structured project management approach focused on customer value, iterative delivery, clear ownership, and data-informed decisions. This documentation provides guidance for all team members on how to initiate, plan, execute, and close projects successfully.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Documentation Structure

### Getting Started

- [**Project Management Overview**](./octoacme-project-management-overview.md) - Start here for roles, artifacts, and lifecycle overview
- [**Roles & Personas**](./octoacme-roles-and-personas.md) - Understand team member responsibilities

### Project Lifecycle

1. [**Project Initiation**](./octoacme-project-initiation.md) - Validate ideas, align stakeholders, create lightweight plans
2. [**Project Planning**](./octoacme-project-planning.md) - Break work into shippable increments, identify dependencies
3. [**Execution & Tracking**](./octoacme-execution-and-tracking.md) - Manage day-to-day delivery and progress tracking
4. [**Release & Deployment**](./octoacme-release-and-deployment.md) - Standardize release processes and reduce risk
5. [**Retrospective & Continuous Improvement**](./octoacme-retrospective-and-continuous-improvement.md) - Capture learnings and drive improvements

### Cross-cutting Topics

- [**Risk Management & Communication**](./octoacme-risks-and-communication.md) - Identify, manage, and communicate risks and dependencies

## OctoAcme Project Management Process Summary

### Lifecycle and Core Structure

OctoAcme follows a structured five-phase project lifecycle designed to deliver customer value through iterative, measurable increments. Projects begin with **Initiation**, where a lightweight one-pager confirms business need, identifies stakeholders, and establishes success metrics before moving to a go/no-go decision gate. This flows into **Planning**, where work is broken into shippable increments with clear acceptance criteria, prioritized backlogs, and dependencies mapped across teams. The **Execution** phase emphasizes daily standups, small pull requests (≤400 lines), continuous integration with automated testing, and a structured project board with columns from Backlog through Done. Following successful delivery, projects move to **Release**, where staged deployments, smoke tests, and rollback plans minimize production risk. Finally, **Retrospectives** capture learnings and convert them into actionable improvements tracked through the project backlog.

### Roles, Communication, and Accountability

OctoAcme defines clear role clarity with a **Project Manager** coordinating schedules and risks, a **Product Manager** prioritizing the backlog and measuring outcomes, and **Developers** who implement features while collaborating on design and testing. The organization emphasizes psychological safety and data-informed decisions, with a communication cadence of daily 15-minute standups, weekly PM-PdM syncs, twice-weekly delivery team standups, and monthly stakeholder updates. Risk and dependency escalation follows a three-level path from team-level triage to PM escalation to sponsor intervention, ensuring visibility and timely intervention when blockers emerge.

### Quality, Risk Management, and Continuous Improvement

Quality is embedded throughout execution via unit and integration tests, end-to-end smoke tests before release, CI-based security scanning, and manual QA for feature acceptance. A formal **Risk Register** tracks risks by ID, impact, likelihood, owner, and mitigation status, reviewed weekly during syncs. Pre-release checklists ensure all acceptance criteria are met, tests pass, and release notes and rollback plans are documented. The organization maintains a strong continuous improvement culture through structured retrospectives (45–75 minutes) that capture what went well, identify improvements, and assign owners with clear due dates—creating a feedback loop that drives incremental refinement of both processes and products.

## Quick Reference

- **New project?** Start with [Project Initiation](./octoacme-project-initiation.md)
- **Need to plan work?** See [Project Planning](./octoacme-project-planning.md)
- **Managing risks?** Review [Risk Management & Communication](./octoacme-risks-and-communication.md)
- **Ready to release?** Follow [Release & Deployment](./octoacme-release-and-deployment.md)
- **Wrapping up a project?** Check [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

## How to Use These Docs

- Keep the Project Charter updated in your project repo
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context
- Use issue templates in `.github/ISSUE_TEMPLATE/` to request updates to process documentation
- Reference relevant sections during project kickoffs and planning sessions
