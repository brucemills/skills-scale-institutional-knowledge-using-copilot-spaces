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

## Engineering Manager / Tech Lead

### Role Summary
Engineering Managers and Tech Leads own technical direction, architecture alignment, and implementation quality. They bridge product intent and engineering execution, ensuring teams deliver with appropriate standards and sustainable practices.

### Responsibilities
- Own technical direction, architecture decisions, and implementation quality standards
- Validate feasibility during planning and guide scope trade-offs with product and project leads
- Ensure engineering standards are applied (code quality, test strategy, observability)
- Facilitate technical design reviews and unblock engineers on complex problems
- Identify and escalate technical risks to Project Managers

### Goals
- Maintain a healthy, scalable codebase aligned with business goals
- Reduce technical debt accumulation while enabling delivery velocity
- Develop team capability and technical confidence

### Typical Communication
- Architecture and design review sessions
- Sprint planning and backlog grooming (technical input)
- Engineering retrospectives and post-incident reviews

### Interaction Points with Other Roles
- **Product Managers:** balance outcome goals with technical constraints; negotiate scope trade-offs
- **Project Managers:** coordinate sequencing, dependency management, and risk escalation
- **Developers:** conduct design reviews, provide unblock support, and set quality standards
- **DevOps / Platform Engineers:** align on deployment safety, observability, and CI/CD standards
- **Security / Compliance Representatives:** ensure secure-by-design implementation practices

---

## UX/UI Designer

### Role Summary
UX/UI Designers define user flows, interaction patterns, and design specifications that ensure products are usable, accessible, and aligned with customer needs. They represent the user perspective throughout the delivery lifecycle.

### Responsibilities
- Define user flows, interaction patterns, and design specifications
- Ensure usability and accessibility considerations are incorporated early in planning
- Provide design acceptance criteria and support validation during demos and reviews
- Facilitate user research and usability testing to inform design decisions
- Maintain design system consistency across product surfaces

### Goals
- Deliver experiences that are intuitive, accessible, and meet user needs
- Reduce rework by resolving UX ambiguity before development begins
- Improve adoption and customer satisfaction through high-quality interfaces

### Typical Communication
- Design reviews and prototype walkthroughs
- Acceptance criteria annotations on backlog items
- Async feedback on PRs or design tools (e.g., Figma comments)

### Interaction Points with Other Roles
- **Product Managers:** translate user problems and research into actionable solution concepts
- **Developers:** align on implementation feasibility and preserve design intent
- **QA/Testing:** coordinate on UX acceptance criteria, edge cases, and accessibility validation
- **Customer Support / Success Representatives:** incorporate user feedback and reported usability issues into design iterations

---

## DevOps / Platform Engineer

### Role Summary
DevOps and Platform Engineers maintain the reliability, scalability, and efficiency of the delivery infrastructure. They own CI/CD pipelines, deployment standards, and operational readiness so that teams can ship confidently and recover quickly.

### Responsibilities
- Maintain CI/CD pipeline reliability, deployment standards, and environment readiness
- Define release guardrails, rollback mechanisms, and operational runbooks
- Improve delivery automation, monitoring, and incident response readiness
- Manage infrastructure provisioning, scaling, and cost efficiency
- Support teams in adopting deployment-safe development practices

### Goals
- Enable fast, reliable, and low-risk deployments
- Minimize toil and manual intervention in delivery processes
- Ensure observability and rapid incident recovery

### Typical Communication
- Release readiness reviews and deployment windows
- Incident postmortems and on-call handoffs
- Infrastructure change notifications and runbook updates

### Interaction Points with Other Roles
- **Project Managers:** support release planning, risk mitigation, and rollback planning
- **Developers:** ensure deployment-safe changes, observability instrumentation, and CI standards
- **Engineering Managers / Tech Leads:** align on infrastructure direction and engineering standards
- **Security / Compliance Representatives:** enforce security controls in pipelines and environments
- **Stakeholders:** coordinate during release windows and communicate post-deploy status

---

## Customer Support / Success Representative

### Role Summary
Customer Support and Success Representatives bring the voice of the customer into the delivery process. They surface pain points, adoption barriers, and feedback trends that help teams prioritize and validate work with real-world impact.

### Responsibilities
- Bring customer pain points, incident trends, and adoption feedback into planning conversations
- Validate release communication quality and support team readiness before launches
- Identify known issues, workarounds, and documentation gaps affecting customers
- Serve as the customer escalation point during and after releases
- Contribute to support content (FAQs, release notes, help articles)

### Goals
- Reduce customer friction and support ticket volume through better product quality
- Ensure customers are informed and supported through changes and releases
- Close the feedback loop between customer experience and product/engineering decisions

### Typical Communication
- Planning and release readiness reviews (customer impact perspective)
- Feedback summaries and incident trend reports
- Release notes review and go-live communication sign-off

### Interaction Points with Other Roles
- **Product Managers:** contribute to feedback loops, adoption measurement, and impact assessment
- **Project Managers:** align on stakeholder communication and rollout readiness checklists
- **Developers / QA:** surface frequent user-facing defects and priority areas for quality improvement
- **UX/UI Designers:** share usability observations and support escalations to inform design decisions

---

## Security / Compliance Representative

### Role Summary
Security and Compliance Representatives ensure that product and delivery decisions meet security, privacy, and regulatory requirements. They integrate security thinking into the lifecycle rather than treating it as a gate at the end.

### Responsibilities
- Provide threat modeling and risk input during planning and design phases
- Define security acceptance checks and compliance constraints for features
- Review architectural and implementation decisions for security implications
- Support incident handling expectations and policy alignment
- Maintain awareness of regulatory changes that may affect scope or timelines

### Goals
- Reduce security risk through early identification and mitigation
- Ensure compliance with relevant regulatory and policy requirements
- Build a culture of security awareness across engineering and product teams

### Typical Communication
- Security review sessions during planning and design
- Risk register contributions and compliance checklists
- Incident and vulnerability response coordination

### Interaction Points with Other Roles
- **Engineering Managers / DevOps:** align on secure implementation, deployment controls, and pipeline security
- **Project Managers:** advise on risk escalation paths and compliance-impacting scope changes
- **Product Managers:** surface requirements that may affect scope, timeline, or compliance obligations
- **Developers:** provide secure coding guidance and review security-critical implementations

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- For a structured view of how roles engage across the project lifecycle, see [OctoAcme Role-Responsibility Matrix](./octoacme-role-responsibility-matrix.md).

