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

## QA/Testing Lead

### Role Summary
QA/Testing Leads own the quality assurance strategy, test planning, and acceptance validation. They work with product and engineering to ensure features meet acceptance criteria and quality standards before release.

### Responsibilities
- Develop test plans and acceptance criteria validation strategies
- Coordinate manual QA and acceptance testing
- Work with developers on test coverage and automation strategies
- Conduct smoke tests and regression testing before releases
- Track and triage defects
- Participate in release readiness reviews

### Interaction with Other Roles
- **Developers**: Collaborate on test automation, quality gates, and bug verification
- **Product Managers**: Validate acceptance criteria and success metrics before implementation
- **Project Managers**: Provide test status and risk assessment for release planning
- **Release Manager**: Coordinate pre-release testing and sign-off

### Goals
- Ensure features meet quality standards before release
- Reduce production defects and customer-impacting bugs
- Provide early quality signals to inform release decisions

### Typical Communication
- Test plans and QA status in sprint planning
- Defect tracking and triage in daily standups
- Release readiness reports and smoke test results

---

## Technical Lead/Architect

### Role Summary
Technical Leads own the technical design, architecture decisions, and technical risk mitigation. They ensure solutions are scalable, maintainable, and aligned with technical strategy.

### Responsibilities
- Design technical solutions and architecture
- Review technical approach and identify technical risks
- Mentor developers and guide implementation approach
- Participate in design reviews and architectural decisions
- Ensure code quality and maintainability standards
- Identify technical dependencies and integration points

### Interaction with Other Roles
- **Developers**: Provide technical guidance, conduct design reviews, and mentor on best practices
- **Project Managers**: Identify technical risks, dependencies, and effort estimates for planning
- **Product Managers**: Advise on technical feasibility and trade-offs during prioritization
- **Security Lead**: Collaborate on secure design patterns and architectural security controls

### Goals
- Deliver scalable, maintainable technical solutions
- Reduce technical debt and rework
- Ensure alignment with technical strategy and standards

### Typical Communication
- Technical design documents and architecture reviews
- Risk identification in planning and weekly syncs
- Code review feedback and mentoring sessions

---

## Sponsor/Executive Stakeholder

### Role Summary
Sponsors and Executive Stakeholders provide strategic direction, funding approval, and business alignment for projects. They ensure initiatives ladder up to organizational goals and remove business-level impediments.

### Responsibilities
- Approve project charter and business case
- Provide strategic direction and business context
- Allocate budget and resources for projects
- Make prioritization decisions across competing initiatives
- Escalate and resolve business-impacting blockers
- Communicate project status to senior leadership

### Interaction with Other Roles
- **Project Managers**: Receive status reports, provide approvals, and escalation support
- **Product Managers**: Align on strategy, priorities, and business metrics
- **Developers/Technical Leads**: Provide context on business constraints and strategic direction

### Goals
- Ensure projects deliver measurable business value
- Align team efforts with organizational strategy
- Maximize return on investment and resource utilization

### Typical Communication
- Monthly stakeholder updates and business reviews
- Quarterly strategy and priority alignment sessions
- Escalation paths for business-impacting decisions

---

## Scrum Master/Delivery Lead

### Role Summary
Scrum Masters and Delivery Leads facilitate team processes, remove blockers, and enable the team to deliver incrementally. They coach the team on Agile practices and foster continuous improvement.

### Responsibilities
- Facilitate daily standups, sprint planning, and retrospectives
- Identify and help resolve team blockers and impediments
- Coach team on Agile/Scrum practices and ceremonies
- Track sprint metrics (velocity, burndown) and health indicators
- Protect team focus and manage scope creep
- Support process improvements from retrospectives

### Interaction with Other Roles
- **Project Managers**: Coordinate on schedule, dependencies, and escalations
- **Developers**: Remove blockers and facilitate team collaboration
- **Product Managers**: Help manage backlog priorities and acceptance criteria clarity
- **All team members**: Create psychological safety and foster continuous improvement

### Goals
- Maximize team productivity and predictability
- Foster a culture of continuous improvement and learning
- Enable the team to deliver consistently high-quality increments

### Typical Communication
- Daily standup facilitation and blocker resolution
- Sprint retrospectives and action item tracking
- Metrics dashboards and sprint health reports

---

## Security Lead/CISO Liaison

### Role Summary
Security Leads ensure that projects meet security and compliance requirements. They advise on secure design patterns, conduct security reviews, and coordinate incident response when security issues are discovered.

### Responsibilities
- Review security requirements and compliance obligations
- Conduct threat modeling and architectural security reviews
- Advise on secure design patterns and secure coding practices
- Coordinate security testing and vulnerability scanning
- Manage security incident response and escalation
- Track and manage security risks and remediation

### Interaction with Other Roles
- **Technical Lead/Architect**: Collaborate on secure design and security controls
- **Developers**: Provide security guidance, code review feedback, and secure coding training
- **Project Managers**: Escalate security risks and coordinate remediation timelines
- **QA/Testing Lead**: Coordinate security testing and vulnerability validation

### Goals
- Prevent security breaches and compliance violations
- Integrate security into the development lifecycle
- Maintain customer trust and organizational reputation

### Typical Communication
- Security design reviews and threat modeling sessions
- Vulnerability reports and remediation tracking
- Security incident response and post-incident reviews

---

## Product Operations/Release Manager

### Role Summary
Product Operations and Release Managers oversee the coordination of release planning, deployment workflows, and go-live activities. They ensure smooth transitions from development to production and support post-release stability.

### Responsibilities
- Plan and coordinate release schedules and deployment windows
- Manage release notes and stakeholder communications
- Coordinate staging environment testing and sign-offs
- Oversee deployment execution and rollback procedures
- Monitor post-release stability and coordinate incident response
- Track release metrics and communicate status to stakeholders

### Interaction with Other Roles
- **Project Managers**: Align on release timelines and milestone delivery
- **QA/Testing Lead**: Coordinate pre-release testing and smoke test execution
- **Technical Lead/Architect**: Validate technical readiness and deployment approach
- **Developers**: Coordinate code freeze, deployment, and hotfix procedures
- **Product Managers**: Communicate release contents and business impact

### Goals
- Execute reliable, predictable releases with minimal disruption
- Reduce deployment risks and time-to-recovery for incidents
- Maintain high quality and stability in production environments

### Typical Communication
- Release planning and coordination meetings
- Deployment checklists and status updates
- Post-release reviews and incident reports

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
