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

---

## QA Lead / Quality Assurance Manager

### Role Summary
QA Leads own quality standards, test strategy, and acceptance criteria validation. They ensure features meet quality gates and provide confidence for production releases. They work closely with Developers and Product Managers to define testability requirements and validate deliverables.

### Responsibilities
- Define quality standards and acceptance criteria for features
- Own test strategy (unit, integration, end-to-end, performance, security)
- Build and maintain automated test suites
- Conduct manual QA for complex or high-risk features
- Identify and triage bugs, work with developers on fixes
- Validate releases before production deployment
- Mentor team on testing best practices
- Collaborate with Technical Leads on test architecture and coverage goals

### Goals
- Catch defects early in the development cycle
- Reduce post-release incidents and customer issues
- Build team confidence in quality standards
- Establish quality as a shared responsibility across the team

### Typical Communication
- Acceptance criteria discussions in backlog refinement with Product Managers and Project Managers
- Test plan reviews with engineering leads and Technical Leads
- Bug triage and priority discussions with Developers
- Release readiness sign-offs with Project Managers and DevOps teams

### Interaction with Existing Roles
- **Developers**: Partner on testable design, test execution, and debugging. QA provides feedback on code quality and test coverage.
- **Product Managers**: Validate acceptance criteria, communicate quality risk impact on delivery timelines.
- **Project Managers**: Escalate quality blockers and release readiness status.

---

## Technical Lead / Architect

### Role Summary
Technical Leads provide technical direction, guide system design, and mentor engineers. They help teams make sound architectural decisions and maintain code quality standards. They work across all technical roles to ensure consistency and excellence.

### Responsibilities
- Review system designs for scalability, security, and maintainability
- Conduct architecture and code reviews
- Advise on technical trade-offs and technology choices
- Mentor junior engineers and lead PR discussions
- Identify technical risks and propose mitigations
- Define coding standards and best practices
- Collaborate with other technical leads on cross-team dependencies
- Support QA Leads with test architecture and coverage strategy

### Goals
- Ensure systems are well-designed and maintainable
- Reduce technical debt and unplanned rework
- Build team technical capability
- Facilitate knowledge sharing and continuous improvement

### Typical Communication
- Design review meetings with Developers and Architects
- Code review comments and architectural guidance in PRs
- Technical spike discussions with Project Managers to scope effort
- Cross-team technical dependency planning with other Technical Leads

### Interaction with Existing Roles
- **Developers**: Guide technical decisions, review code, mentor growth.
- **Product Managers**: Advise on technical feasibility, timeline impact of architectural changes.
- **Project Managers**: Communicate technical risks and complexity to timeline and resource planning.

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters facilitate agile ceremonies, remove blockers, and coach teams on agile practices. They work with Project Managers to optimize team velocity and ensure consistent execution of the process.

### Responsibilities
- Facilitate daily standups, sprint planning, and retrospectives
- Identify and escalate team blockers and dependencies
- Coach team members on agile principles and practices
- Maintain sprint boards and iteration tracking
- Help the team optimize their velocity and process
- Shield the team from external distractions and scope creep
- Work with Project Managers on schedule and resource planning

### Goals
- Maximize team productivity and flow
- Build a culture of continuous improvement
- Ensure team members follow agile best practices
- Reduce cycle time and lead time for features

### Typical Communication
- Daily standups and iteration ceremonies
- One-on-ones with team members for coaching
- Retrospective facilitation and action item tracking
- Weekly coordination with Project Managers on planning and blockers

### Interaction with Existing Roles
- **Project Managers**: Partner on timeline planning, escalation of blockers, resource availability.
- **Developers**: Remove impediments, coach on agile practices, facilitate technical collaboration.
- **Product Managers**: Support backlog refinement sessions, help prioritization discussions.

---

## UX/Design Lead

### Role Summary
UX/Design Leads own user experience, design systems, and usability standards. They collaborate with Product Managers to translate customer needs into intuitive designs and work with Developers to ensure design quality in implementation.

### Responsibilities
- Conduct user research and validate design decisions
- Create wireframes, prototypes, and design specs
- Establish and maintain design systems and component libraries
- Review implementation against design specifications
- Advocate for user needs in prioritization discussions
- Mentor team members on UX best practices
- Collaborate with Product Managers on feature feasibility and user impact

### Goals
- Maximize customer usability and satisfaction
- Ensure consistency across product features
- Reduce user support burden through intuitive design
- Build brand trust through quality user experience

### Typical Communication
- Design review sessions with Product Managers and Developers
- User research findings and insights presentations
- Design system documentation and component guidance
- Feedback on feature implementation and quality

### Interaction with Existing Roles
- **Product Managers**: Define success metrics for user experience, align design with business goals.
- **Developers**: Collaborate on implementation feasibility, provide design specifications, review code against design.
- **Project Managers**: Communicate design complexity and timing to overall project schedules.

---

## DevOps / Release Engineer

### Role Summary
DevOps and Release Engineers manage deployment pipelines, infrastructure, and release automation. They work with all technical roles to ensure reliable, repeatable deployments and maintain system reliability and observability.

### Responsibilities
- Design and maintain CI/CD pipelines and deployment automation
- Manage infrastructure, environments, and cloud resources
- Implement security controls and compliance requirements
- Monitor system performance and health
- Manage releases, rollbacks, and incident response
- Establish deployment best practices and standards
- Collaborate with developers on environment and tooling needs
- Support production troubleshooting and optimization

### Goals
- Enable reliable, fast deployments with minimal downtime
- Maintain secure, scalable, and observable systems
- Reduce manual effort and human error in operations
- Support rapid iteration while ensuring stability

### Typical Communication
- Release coordination meetings with Project Managers and Developers
- Infrastructure and deployment planning discussions
- Incident response and post-mortems
- Documentation of deployment procedures and runbooks
- Performance and reliability reviews with technical leadership

### Interaction with Existing Roles
- **Project Managers**: Coordinate release windows, communicate deployment readiness.
- **Developers**: Support environment setup, CI/CD tooling, troubleshooting production issues.
- **Technical Leads**: Collaborate on architecture that supports reliable deployment and observability.

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, funding decisions, and strategic alignment for projects. They represent business, customer, and organizational interests and ensure projects deliver value aligned with company strategy.

### Responsibilities
- Define business objectives and success metrics
- Approve project scope, budget, and timeline
- Provide strategic guidance and business context
- Champion project internally and with customers
- Make prioritization and trade-off decisions
- Monitor business impact and ROI
- Participate in go/no-go decisions and phase approvals

### Goals
- Ensure projects deliver measurable business value
- Align technical work with business strategy
- Maintain stakeholder confidence and transparency
- Maximize ROI and minimize business risk

### Typical Communication
- Project charter and approval meetings
- Monthly or milestone-based status updates
- Business metrics and impact reviews
- Executive summaries and decision briefings
- Budget and resource allocation discussions

### Interaction with Existing Roles
- **Product Managers**: Partner on business objectives, success metrics, and prioritization.
- **Project Managers**: Receive status updates, approve scope changes, make funding decisions.
- **Developers**: Provide business context and requirements clarity through Product Managers.

---

## Business Analyst

### Role Summary
Business Analysts gather requirements, clarify scope, and translate business needs into actionable product requirements. They work between stakeholders and the technical team to ensure mutual understanding and alignment.

### Responsibilities
- Gather and document business requirements from stakeholders
- Conduct user research and needs analysis
- Clarify scope and validate understanding with stakeholders
- Create requirements documentation and acceptance criteria
- Identify gaps and dependencies in requirements
- Facilitate discussions between business and technical teams
- Support change management and scope decisions
- Validate that delivered solutions meet business needs

### Goals
- Ensure clear, shared understanding of requirements across all teams
- Reduce rework and scope creep
- Improve delivery velocity through better planning
- Bridge the gap between business intent and technical implementation

### Typical Communication
- Requirements gathering sessions with stakeholders
- Backlog refinement meetings with Product Managers and Developers
- Scope clarification documents and specification reviews
- Change request analysis and impact assessment
- Acceptance validation and lessons learned documentation

### Interaction with Existing Roles
- **Product Managers**: Support backlog prioritization, requirements documentation, and customer validation.
- **Project Managers**: Provide scope clarity and change impact analysis for timeline planning.
- **Developers**: Collaborate on acceptance criteria clarity and technical feasibility.
- **Stakeholders**: Translate business needs into technical language and gather feedback on delivery.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Consider typical persona interactions and communication patterns when planning projects and resolving conflicts.
- Build balanced teams by ensuring all necessary personas are represented or clearly delegated to existing team members.
