# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

### Interactions with Other Roles
- **With Product Managers**: Clarify acceptance criteria and feature requirements
- **With Project Managers**: Report progress, identify blockers, and support estimation
- **With QA/Test Leads**: Collaborate on test coverage and Definition of Done
- **With Technical Leads**: Seek guidance on architectural decisions and technical design
- **With Design/UX Leads**: Implement designs and provide technical feasibility feedback

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

### Interactions with Other Roles
- **With Project Managers**: Align on priorities, timelines, and resource needs
- **With Developers**: Define requirements and validate solutions
- **With Design/UX Leads**: Collaborate on user experience and feature prioritization
- **With QA/Test Leads**: Define acceptance criteria and success metrics
- **With Stakeholders/Sponsors**: Communicate roadmap and strategic alignment

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

### Interactions with Other Roles
- **With Product Managers**: Align on priorities and release planning
- **With Developers**: Track progress, identify blockers, and manage dependencies
- **With All Delivery Team Members**: Facilitate ceremonies and coordinate communication
- **With Stakeholders/Sponsors**: Provide regular updates and escalate risks
- **With Scrum Masters**: Collaborate on process execution and team enablement

---

## Design/UX Lead

### Role Summary
Design/UX Leads own the user experience strategy, design systems, and cross-functional collaboration. They ensure that features are intuitive, accessible, and aligned with user needs and brand standards.

### Responsibilities
- Define user experience strategy and design direction
- Create and maintain design systems and component libraries
- Conduct user research and usability testing
- Design interfaces and user flows that meet accessibility standards
- Collaborate with product and engineering on design feasibility
- Mentor team members on design best practices
- Provide design reviews and feedback during development

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Maintain consistency across features and platforms
- Reduce friction in user workflows
- Build a strong design culture within the team

### Typical Communication
- Design kickoff meetings with product and engineering
- Weekly design reviews and feedback sessions
- Usability testing reports and findings
- Design system documentation and updates

### Interactions with Other Roles
- **With Product Managers**: Collaborate on feature prioritization and user needs
- **With Developers**: Provide design specs and support implementation feasibility discussions
- **With QA/Test Leads**: Define usability acceptance criteria and design edge cases
- **With Stakeholders**: Communicate design rationale and user research findings
- **With Project Managers**: Align on design timelines and dependencies

---

## QA/Test Lead

### Role Summary
QA/Test Leads own the quality strategy and acceptance validation for projects. They collaborate with product and engineering to define testability requirements, design test plans, and ensure features meet acceptance criteria before release.

### Responsibilities
- Define quality standards and testing strategy for projects
- Collaborate with product on acceptance criteria and user scenarios
- Design test plans (unit, integration, end-to-end, performance, security)
- Validate that completed work meets Definition of Done
- Identify and escalate quality risks and blockers
- Mentor team on testability and quality practices
- Lead test execution and document known issues pre-release
- Establish and monitor quality metrics

### Goals
- Deliver high-quality features that meet user expectations
- Reduce defects reaching production
- Enable fast, confident releases through comprehensive testing
- Build a culture of quality ownership across the team

### Typical Communication
- Sprint planning and backlog refinement (define testability)
- Daily standups (flag quality risks and test blockers)
- PR reviews (validate test coverage and acceptance criteria)
- Release readiness reviews and quality sign-offs

### Interactions with Other Roles
- **With Product Managers**: Define acceptance criteria and user scenarios for testing
- **With Developers**: Collaborate on test coverage, testability, and bug resolution
- **With Technical Leads**: Discuss testing strategies and technical test implementation
- **With Release/DevOps Engineers**: Coordinate smoke testing and production validation
- **With Project Managers**: Escalate quality blockers and release readiness concerns
- **With Design/UX Leads**: Define usability test cases and accessibility requirements

---

## Technical Lead/Architect

### Role Summary
Technical Leads oversee technical decisions, conduct design reviews, manage system architecture, and mentor developers. They ensure solutions are scalable, maintainable, and aligned with technical strategy.

### Responsibilities
- Make architectural decisions and define technical strategy
- Conduct design and code reviews to ensure quality standards
- Manage technical debt and propose refactoring initiatives
- Mentor and coach developers on best practices
- Identify and mitigate technical risks
- Ensure systems are scalable, reliable, and secure
- Collaborate with product on technical feasibility of features
- Lead technical spike investigations and proof-of-concepts

### Goals
- Deliver scalable, maintainable, and secure systems
- Reduce technical debt and system complexity
- Enable team growth through mentorship and knowledge sharing
- Balance speed of delivery with long-term code quality

### Typical Communication
- Technical design reviews and architecture discussions
- Code review comments and guidance
- Technical risk assessments and mitigation plans
- Mentoring sessions with developers

### Interactions with Other Roles
- **With Developers**: Provide architectural guidance and code review feedback
- **With Product Managers**: Discuss technical feasibility and trade-offs
- **With Project Managers**: Identify technical risks and estimate effort
- **With QA/Test Leads**: Define testability requirements and quality standards
- **With Release/DevOps Engineers**: Collaborate on deployment strategies and system reliability
- **With Stakeholders**: Communicate technical decisions and system health

---

## Release/DevOps Engineer

### Role Summary
Release/DevOps Engineers manage deployment pipelines, infrastructure, and production monitoring. They enable fast, reliable, and safe releases while ensuring system uptime and incident response.

### Responsibilities
- Design and maintain deployment pipelines and infrastructure
- Automate build, test, and deployment processes
- Manage configuration, secrets, and access control
- Monitor production systems and set up alerting
- Lead production deployments and coordinate rollbacks
- Respond to and triage production incidents
- Document runbooks and incident playbooks
- Optimize infrastructure for performance and cost

### Goals
- Enable fast, reliable releases with minimal risk
- Maintain high system availability and performance
- Reduce manual toil through automation
- Support team learning through incident post-mortems

### Typical Communication
- Deployment planning and release coordination
- Infrastructure and deployment automation updates
- Incident reports and post-mortems
- Monitoring dashboards and alerts
- Runbooks and deployment documentation

### Interactions with Other Roles
- **With Developers**: Support deployment of changes and troubleshoot production issues
- **With QA/Test Leads**: Coordinate smoke testing in staging and production
- **With Technical Leads**: Collaborate on system architecture and reliability
- **With Project Managers**: Coordinate release windows and communicate deployment status
- **With All Teams**: Support incident response and provide infrastructure support

---

## Scrum Master/Agile Coach

### Role Summary
Scrum Masters facilitate agile ceremonies, remove impediments, and coach teams on process improvements. They enable team self-organization and foster a culture of continuous improvement and psychological safety.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Remove impediments and blockers that slow team progress
- Coach team on agile practices and continuous improvement
- Track team velocity and burndown metrics
- Identify process bottlenecks and propose improvements
- Foster psychological safety and encourage open communication
- Support team self-organization and decision-making
- Escalate process-related risks to Project Manager

### Goals
- Enable team self-organization and autonomy
- Maximize team velocity and delivery predictability
- Build a culture of continuous learning and improvement
- Maintain psychological safety and high team morale

### Typical Communication
- Facilitation of all agile ceremonies
- One-on-one coaching with team members
- Process improvement recommendations
- Team health and retrospective insights

### Interactions with Other Roles
- **With Project Managers**: Provide team health insights and process recommendations
- **With All Team Members**: Facilitate collaboration and remove blockers
- **With Developers**: Coach on technical practices and sprint discipline
- **With Product Managers**: Ensure backlog is groomed and ready for planning
- **With Stakeholders**: Support communication about team progress and dependencies

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, strategic alignment, and resource advocacy for projects. They ensure projects deliver business value and maintain executive visibility and support.

### Responsibilities
- Define business objectives and success criteria
- Provide strategic context and business priorities
- Approve project scope, timeline, and resource allocation
- Make key decisions and resolve escalations
- Advocate for resources and remove organizational blockers
- Monitor project progress and business impact
- Communicate project status to broader organization
- Support risk management and contingency planning

### Goals
- Ensure projects deliver maximum business value
- Maintain strategic alignment across initiatives
- Enable fast decision-making and resource allocation
- Reduce organizational friction and dependencies

### Typical Communication
- Monthly stakeholder reviews and status updates
- Decision-making meetings and approvals
- Executive briefings and business case discussions
- Risk escalation and contingency planning

### Interactions with Other Roles
- **With Project Managers**: Receive regular updates and escalations; provide decisions
- **With Product Managers**: Align on roadmap and business priorities
- **With All Team Leads**: Provide strategic context and remove organizational blockers
- **With Scrum Masters**: Support team enablement through resource advocacy
- **With Finance/HR**: Coordinate budget and resource allocation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference these role definitions when clarifying ownership, responsibilities, and cross-functional collaboration.
