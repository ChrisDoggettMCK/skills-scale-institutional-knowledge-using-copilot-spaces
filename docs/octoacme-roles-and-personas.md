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

## QA/Testing

### Role Summary
QA/Testing engineers validate that features meet acceptance criteria and quality standards before release. They design and execute test plans, identify defects, and partner with developers to maintain a high quality bar throughout the lifecycle.

### Responsibilities
- Define test plans and acceptance test cases from requirements and acceptance criteria
- Execute manual and automated tests at the feature, integration, and regression levels
- File and triage defects; track resolution to closure
- Coordinate smoke and end-to-end tests for release readiness
- Maintain and improve test automation coverage over time

### Goals
- Prevent regressions and catch defects early in the cycle
- Ensure releases are production-ready and meet the Definition of Done
- Reduce manual testing effort through automation

### Typical Communication
- Test plans and bug reports shared with Developers and the Project Manager
- Release readiness sign-offs communicated to the Release Manager and PM
- Participation in sprint demos and retrospectives

### Interactions with Other Roles
- **Developers**: Collaborate on reproducing defects and verifying fixes; review acceptance criteria together during sprint planning.
- **Product Manager**: Receive acceptance criteria and clarify edge cases before writing test plans.
- **Project Manager**: Report test status and release readiness; flag risks that could block the timeline.
- **Release Manager**: Provide final sign-off on smoke tests prior to production deployment.
- **Scrum Master**: Surface testing blockers during standups for timely resolution.

---

## Stakeholders

### Role Summary
Stakeholders are individuals or groups with a vested interest in the project's outcomes — including business owners, customers, and executives. They provide strategic direction, approve key decisions, and receive regular progress updates.

### Responsibilities
- Provide business context, goals, and constraints during initiation
- Review and approve project charters, roadmaps, and major scope changes
- Offer timely feedback on deliverables and milestone reviews
- Act as escalation points for business-critical decisions

### Goals
- Ensure the project delivers measurable business or customer value
- Maintain visibility and confidence in project progress
- Enable quick decision-making to avoid delays

### Typical Communication
- Monthly status updates (or milestone-based) from the Project Manager
- Roadmap reviews with the Product Manager
- Release announcements from the Release Manager

### Interactions with Other Roles
- **Product Manager**: Align on priorities, success metrics, and scope trade-offs.
- **Project Manager**: Receive risk updates and approve scope or timeline changes.
- **Release Manager**: Notified of upcoming deployments and post-release status.
- **Data Analyst**: Consume dashboards and reports summarizing project impact and usage.

---

## Scrum Master (Delivery Lead)

### Role Summary
The Scrum Master (or Delivery Lead) facilitates Agile ceremonies, removes team blockers, and coaches the team on process adoption. They protect team focus and drive continuous improvement in how the team works.

### Responsibilities
- Facilitate sprint planning, daily standups, sprint reviews, and retrospectives
- Identify and remove impediments that block team progress
- Coach the team on Agile principles and practices
- Shield the team from external disruptions during an active sprint
- Track and report team health, velocity, and process metrics

### Goals
- Maintain a sustainable team cadence and remove friction from delivery
- Improve team self-organization and cross-functional collaboration
- Foster a culture of continuous improvement

### Typical Communication
- Daily standups and sprint ceremonies with the full delivery team
- Regular check-ins with the Project Manager on blockers and dependencies
- Retrospective action items shared with the team and PM

### Interactions with Other Roles
- **Project Manager**: Coordinate on schedule risks, cross-team dependencies, and escalation paths; the Scrum Master focuses on team process while the PM focuses on overall delivery health.
- **Product Manager**: Ensure backlog is groomed and prioritized before sprint planning; clarify acceptance criteria with the team.
- **Developers**: Remove technical and organizational blockers; support estimation and sprint commitment.
- **QA/Testing**: Ensure test tasks are included in sprint planning and that QA is not left as a bottleneck at the end of the sprint.
- **Stakeholders**: Keep stakeholders from interrupting sprint work; channel requests through the Product Manager backlog.

---

## UX Designer

### Role Summary
The UX Designer creates user flows, wireframes, and prototypes that translate product requirements into intuitive experiences. They gather and synthesize user feedback to validate design decisions before and during development.

### Responsibilities
- Conduct user research to understand needs, pain points, and behaviors
- Create wireframes, prototypes, and high-fidelity designs for new features
- Collaborate with Developers to ensure accurate implementation of designs
- Gather and incorporate user feedback through usability testing
- Maintain a shared design system or component library

### Goals
- Deliver user experiences that are intuitive, accessible, and aligned with business goals
- Reduce costly rework by validating designs with users before implementation begins
- Serve as the voice of the user in product and planning discussions

### Typical Communication
- Design reviews and prototype walkthroughs with Developers and the Product Manager
- Usability research findings shared with Product Manager and Stakeholders
- Design specifications and annotated assets handed off to Developers

### Interactions with Other Roles
- **Product Manager**: Collaborate on feature requirements and user stories; translate business goals into user-centered design solutions.
- **Developers**: Hand off design specs and assets; participate in implementation reviews to identify deviations early.
- **QA/Testing**: Share interaction specifications so test cases capture intended UX behavior.
- **Data Analyst**: Consume usage metrics and funnel data to identify UX improvement opportunities.
- **Stakeholders**: Present research findings and prototype walkthroughs to gather early feedback.

---

## Data Analyst

### Role Summary
The Data Analyst owns metrics definition, builds dashboards, and generates insights from product and project data. They help the team make data-informed decisions across the full project lifecycle.

### Responsibilities
- Define and document success metrics and KPIs in alignment with project goals
- Build and maintain dashboards for tracking usage, performance, and quality
- Analyze data to surface insights and trends that inform prioritization
- Support retrospectives with quantitative evidence of what improved or regressed
- Partner with the Product Manager on experiment design and outcome measurement

### Goals
- Enable data-informed decision-making across the team and stakeholder group
- Surface actionable insights from usage and operational data quickly
- Ensure success metrics are defined before work begins, not after

### Typical Communication
- Dashboard and report summaries shared with Product Manager, PM, and Stakeholders
- Metric definitions reviewed during planning with the Product Manager
- Retrospective data presented at the end of each sprint or release

### Interactions with Other Roles
- **Product Manager**: Co-define success metrics for new features; validate that outcomes match expected impact.
- **Project Manager**: Provide project-level health metrics (e.g., velocity, defect rates) that inform schedule and scope decisions.
- **Developers**: Coordinate on instrumentation and logging requirements to capture needed signals.
- **UX Designer**: Share funnel and engagement metrics to guide design iteration.
- **Stakeholders**: Deliver executive-level dashboards summarizing project value and business outcomes.

---

## Release Manager

### Role Summary
The Release Manager coordinates complex or multi-team releases, manages cutover plans, and communicates deployment status. They reduce release risk and ensure all parties are informed and prepared.

### Responsibilities
- Maintain the release calendar and coordinate release windows across teams
- Confirm release readiness (CI passing, QA sign-off, release notes drafted, rollback plan in place)
- Manage the deployment checklist and cutover plan for each release
- Communicate release status and post-deploy verification results to stakeholders
- Lead incident response coordination if a deployment causes a production issue

### Goals
- Execute predictable, low-risk releases with clear rollback options
- Ensure all dependencies are resolved and stakeholders are informed before go-live
- Continuously improve the release process to reduce manual effort and risk

### Typical Communication
- Pre-release readiness meetings with QA, Developers, and the Project Manager
- Release announcements and post-deploy summaries to Stakeholders
- Deployment runbooks and cutover plans shared with the delivery team

### Interactions with Other Roles
- **Developers**: Review deployment steps, confirm build artifacts, and coordinate hotfix timing if issues arise.
- **QA/Testing**: Receive final sign-off and smoke test results before initiating production deployment.
- **Project Manager**: Align on deployment windows, timeline impacts, and risk mitigations.
- **Product Manager**: Confirm which features are in scope for the release and ensure release notes are accurate.
- **Stakeholders**: Provide advance notice of planned deployments and communicate post-release outcomes.

---

## Tech Lead (Engineering Lead)

### Role Summary
The Tech Lead provides technical direction, upholds code quality and architecture standards, and bridges the gap between engineering execution and product planning. They are a senior contributor who guides Developers on design decisions and cross-cutting concerns.

### Responsibilities
- Define and communicate technical standards, patterns, and best practices
- Lead architecture and design reviews for significant features or changes
- Support Developers through code reviews and technical mentoring
- Identify and manage technical debt and engineering risk
- Collaborate with the Product Manager and PM on technical feasibility and effort estimates

### Goals
- Maintain a high-quality, maintainable, and scalable codebase
- Reduce technical risk through proactive design and review
- Enable Developers to deliver with confidence and consistency

### Typical Communication
- Technical design docs and architecture decision records (ADRs) shared with the team
- Code review feedback on PRs
- Participation in planning sessions to assess technical scope

### Interactions with Other Roles
- **Developers**: Provide technical guidance, conduct code reviews, and mentor on standards and patterns.
- **Product Manager**: Assess technical feasibility of proposed features; flag constraints or trade-offs early.
- **Project Manager**: Surface engineering risks and dependencies that affect the schedule.
- **Security/AppSec Reviewer**: Partner on secure design and remediation of vulnerabilities.
- **Scrum Master**: Collaborate to address technical blockers surfaced during standups.

---

## Security / AppSec Reviewer

### Role Summary
The Security/AppSec Reviewer ensures that features and changes meet security and compliance standards before they reach production. They conduct threat modelling, review code for vulnerabilities, and validate that security controls are in place.

### Responsibilities
- Conduct threat modelling for new features and significant architectural changes
- Review code and infrastructure changes for security vulnerabilities
- Validate that security scanning is configured in CI and that findings are addressed
- Define and communicate security acceptance criteria for releases
- Track and triage security findings from automated tools and manual review

### Goals
- Prevent security vulnerabilities from reaching production
- Embed security practices early in the development cycle ("shift left")
- Maintain compliance with applicable security and privacy standards

### Typical Communication
- Security review findings shared with the Tech Lead and Developers
- Release security sign-off communicated to the Release Manager
- Periodic security posture updates shared with Stakeholders and the Project Manager

### Interactions with Other Roles
- **Tech Lead**: Collaborate on secure architecture and remediation of design-level vulnerabilities.
- **Developers**: Provide guidance on secure coding practices; review and approve remediated code.
- **Release Manager**: Issue security sign-off as part of the release readiness gate.
- **QA/Testing**: Coordinate on security-related test scenarios and penetration testing.
- **Project Manager**: Surface security risks that may affect the release timeline or scope.

---

## Lifecycle Interaction Matrix

This table maps each project lifecycle stage to the primary activities and level of involvement expected from each role.
**Key:** R = Responsible (does the work), A = Accountable (owns the outcome), C = Consulted (provides input), I = Informed (kept up to date)

| Role | Initiation | Planning | Execution & Tracking | Release & Deployment | Retrospective |
|---|---|---|---|---|---|
| Product Manager | A: Define goals & success metrics | A: Roadmap, backlog prioritization | C: Backlog refinement, scope decisions | I: Release sign-off, notes review | A: Review outcomes vs. metrics |
| Project Manager | A/R: Charter, stakeholder alignment | A/R: Schedule, milestones, risk register | A: Track progress, escalate risks | A: Coordinate deployment window | A/R: Facilitate retrospective |
| Scrum Master | C: Process setup | R: Facilitate planning ceremony | R: Standups, blockers, ceremonies | C: Deployment readiness coordination | R: Facilitate retrospective |
| Tech Lead | C: Architecture feasibility | R: Technical design, estimation | R: Code review, standards, tech debt | R: Deployment oversight | C: Engineering improvement actions |
| Developers | I: Review charter | C: Estimation, spike work | R: Build, test, review | R: Deploy, verify, on-call handoff | C: Discuss improvement actions |
| UX Designer | C: User research input | R: User flows, prototypes | R: Design reviews, implementation checks | I: Confirm UI in production | C: UX feedback analysis |
| QA/Testing | I: Review requirements | C: Test planning, acceptance criteria | R: Testing, defect tracking | R: Smoke tests, release sign-off | C: Quality metrics review |
| Data Analyst | C: KPI/metric definition | C: Metric instrumentation planning | C: Dashboard monitoring | I: Usage baseline capture | R: Retrospective data & insights |
| Release Manager | I: Aware of planned scope | C: Release calendar, dependency mapping | C: Readiness tracking | A/R: Coordinate and execute release | C: Release process improvement |
| Security Reviewer | I: Threat model awareness | C: Security requirements | C: Security review of changes | R: Security sign-off for release | I: Security finding trends |
| Stakeholders | A: Approve initiation & goals | I: Review and approve plan | I: Status updates, milestone demos | I: Release announcement | A: Review business outcomes |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The Lifecycle Interaction Matrix above can be used to determine which roles to involve at each stage of a project scenario.

