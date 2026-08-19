# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Stakeholders/Sponsors

### Role Summary
Stakeholders or project sponsors represent business interests and provide governance oversight. They define project scope, approve budgets, and make or approve high-level decisions that guide project direction and constraints.

### Responsibilities
- Define business objectives and success criteria for the project
- Approve project scope, budget, timeline, and resource allocation
- Escalate and resolve high-level risks and organizational blockers
- Provide strategic feedback on deliverables and project direction
- Make or approve go/no-go decisions at key project gates

### Goals
- Ensure business value delivery within organizational constraints
- Minimize risk, scope creep, and budget overruns
- Maintain alignment between project delivery and organizational strategy

### Typical Communication
- Executive steering committee meetings
- Go/no-go decision gates and milestone approvals
- Budget reviews and resource requests
- High-level project status updates

### Interactions with Other Roles
- **Project Managers**: Receive project plans, budgets, and risk escalations; provide approval and strategic direction
- **Product Managers**: Align on business objectives and prioritization; approve product roadmap and scope
- **Developers**: Stakeholders define success criteria; developers deliver to those criteria

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
- **Technical Leads**: Receive architecture guidance and technical standards; participate in design reviews
- **QA Leads**: Collaborate on test strategy; provide code for quality assurance and testing
- **Product Managers**: Clarify acceptance criteria and feature requirements
- **Project Managers**: Report progress, risks, and blockers

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
- **Stakeholders**: Define business objectives together; obtain approval for roadmap and scope
- **Business Analysts**: Gather detailed requirements and validate user stories
- **Developers**: Collaborate on acceptance criteria and feasibility
- **Project Managers**: Coordinate delivery timelines and dependencies

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
- **Stakeholders**: Escalate risks and blockers; report on budget and timeline status
- **Product Managers**: Coordinate delivery schedules and dependencies
- **Developers**: Track progress, manage commitments, remove blockers
- **Release Managers**: Coordinate release planning and deployment schedules
- **QA Leads**: Plan testing cycles and quality gates into project timeline

---

## Quality Assurance Leads

### Role Summary
QA Leads own quality strategy, test planning, and automation infrastructure. They ensure deliverables meet acceptance criteria and quality standards.

### Responsibilities
- Define quality standards and acceptance criteria
- Plan testing strategies and test coverage for features and releases
- Build and maintain test automation infrastructure
- Identify quality risks, defects, and gaps in coverage
- Validate completeness and correctness of deliverables before release

### Goals
- Detect defects early in the development cycle
- Maintain high product quality and reliability
- Reduce manual testing effort through automation

### Typical Communication
- QA planning sessions and design reviews
- Test reports and quality metrics
- Defect logs and quality dashboards
- Release readiness assessments

### Interactions with Other Roles
- **Developers**: Collaborate on test strategy; review code for testability; work through defect reports
- **Product Managers**: Clarify acceptance criteria and quality requirements
- **Project Managers**: Plan testing cycles and quality gates into project timeline
- **Technical Leads**: Review test automation architecture and quality standards
- **Release Managers**: Validate release readiness; coordinate quality sign-off for deployments

---

## Technical Leads/Architects

### Role Summary
Technical Leads guide technical direction, design system architecture, and ensure technical excellence across the team.

### Responsibilities
- Define technical vision, architecture, and design principles
- Conduct design and architecture reviews
- Identify technical risks and propose solutions
- Mentor developers and enforce coding standards
- Evaluate and recommend tools, technologies, and frameworks

### Goals
- Deliver scalable, maintainable technical solutions
- Reduce technical debt and system complexity
- Build team technical capabilities and knowledge sharing

### Typical Communication
- Technical design reviews and RFC discussions
- Architecture documentation and decision records
- Code review and mentoring interactions
- Technical spike investigations

### Interactions with Other Roles
- **Developers**: Provide architecture guidance; conduct design reviews; mentor on best practices
- **Project Managers**: Identify and escalate technical risks and dependencies
- **QA Leads**: Review test automation architecture and quality standards
- **Stakeholders**: Present technical trade-offs and implications for scope/timeline

---

## Release/Operations Managers

### Role Summary
Release Managers coordinate deployment activities, manage release schedules, and ensure production stability and incident response.

### Responsibilities
- Plan and coordinate release activities and deployment schedules
- Manage deployment dependencies and sequencing across teams
- Monitor production health, performance, and stability
- Lead incident response, escalation, and resolution
- Coordinate rollback procedures and contingency planning

### Goals
- Deploy reliably with minimal production impact
- Reduce deployment risk and cycle time
- Maintain high system availability and performance

### Typical Communication
- Release planning and coordination meetings
- Deployment runbooks and status updates
- Incident reports and post-mortems
- Production monitoring dashboards

### Interactions with Other Roles
- **Project Managers**: Coordinate release planning into project timeline
- **Developers**: Provide deployment requirements and incident response support
- **QA Leads**: Obtain quality sign-off before release; coordinate testing in staging environments
- **Technical Leads**: Review deployment architecture and technical readiness
- **Stakeholders**: Report on release status and production stability

---

## Business Analysts

### Role Summary
Business Analysts bridge business requirements and technical implementation. They gather detailed requirements, validate user stories, and ensure solutions meet business needs.

### Responsibilities
- Gather and document detailed business requirements
- Create and refine user stories and acceptance criteria
- Validate solutions with stakeholders and end users
- Identify process improvements and gaps in current state
- Communicate between business and technical teams to reduce misalignment

### Goals
- Ensure built solutions solve real business problems
- Reduce rework and scope misalignment
- Improve stakeholder satisfaction and solution adoption

### Typical Communication
- Requirements gathering sessions and workshops
- User story refinement and acceptance criteria definition
- Stakeholder validation and feedback sessions
- Process documentation and flow diagrams

### Interactions with Other Roles
- **Product Managers**: Gather customer insights and business priorities; refine roadmap
- **Stakeholders**: Understand business context and success criteria; validate solutions
- **Developers**: Clarify requirements and acceptance criteria; discuss feasibility
- **Project Managers**: Identify scope changes and dependencies early
- **QA Leads**: Define test scenarios and acceptance criteria alignment

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Interaction patterns between roles illustrate dependencies and communication flows in project delivery.
