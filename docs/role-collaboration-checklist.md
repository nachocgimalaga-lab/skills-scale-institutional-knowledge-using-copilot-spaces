# OctoAcme Role Collaboration Checklist

## Purpose
This checklist ensures that all necessary roles are engaged at appropriate project stages and that key handoffs and communication points are not missed.

---

## Project Initiation Phase

### Stakeholders & Decision Makers
- [ ] Product Manager defined problem statement and success metrics
- [ ] Project Manager identified timeline and milestones
- [ ] Project Manager confirmed resource availability
- [ ] Key stakeholders reviewed and approved business case

### Role Engagement
- [ ] Product Manager aligned with key stakeholders
- [ ] Project Manager confirmed team composition (Developers, QA Lead, UX/UI Designer, etc.)
- [ ] Security Analyst reviewed scope for security considerations
- [ ] Support/Customer Success team provided market/customer context

---

## Project Planning Phase

### Requirements & Design
- [ ] Product Manager finalized acceptance criteria
- [ ] UX/UI Designer created wireframes/mockups for review
- [ ] Developers assessed technical feasibility
- [ ] Security Analyst identified security requirements
- [ ] QA Lead drafted test plan and acceptance criteria
- [ ] Technical Writer identified documentation needs

### Planning Artifacts
- [ ] Project backlog created and prioritized (Product Manager)
- [ ] Release plan and milestones defined (Project Manager)
- [ ] Risk register initiated (Project Manager with input from all roles)
- [ ] Design specs documented (UX/UI Designer)
- [ ] Technical architecture reviewed (Developers, Security Analyst)
- [ ] CI/CD requirements identified (Automation Engineer)

---

## Execution Phase

### Daily/Weekly Coordination
- [ ] Daily standups held with Developers, QA Lead, Project Manager
- [ ] Weekly delivery sync includes Developers, QA Lead, Project Manager, Product Manager
- [ ] Sprint planning includes clear story ownership and acceptance criteria
- [ ] Blockers and risks tracked and escalated by Project Manager

### Development & Quality
- [ ] Developers implement features with tests
- [ ] Code reviews include Developers and Security Analyst
- [ ] QA Lead coordinates test execution and defect triage
- [ ] Automation Engineer ensures CI/CD pipeline health
- [ ] Technical Writer updates documentation in parallel with development
- [ ] UX/UI Designer reviews implementation against design specs

### Risk & Dependency Management
- [ ] Risk register updated weekly (Project Manager)
- [ ] Dependencies identified and communicated (Project Manager)
- [ ] Security issues escalated immediately (Security Analyst)
- [ ] Customer issues escalated (Support/Customer Success)

---

## Pre-Release Phase

### Release Readiness
- [ ] QA Lead confirms all acceptance criteria met and defects resolved
- [ ] Automation Engineer verifies deployment automation is ready
- [ ] Security Analyst conducts final security review
- [ ] Technical Writer completes documentation and release notes
- [ ] Release Manager develops deployment plan and communications

### Stakeholder Alignment
- [ ] Product Manager confirms feature completeness
- [ ] Project Manager verifies no open blockers or risks
- [ ] Support/Customer Success prepares customer communications
- [ ] Key stakeholders briefed on release contents and timing

---

## Release & Deployment Phase

### Deployment Coordination
- [ ] Release Manager coordinates deployment window
- [ ] Developers on standby for support during deployment
- [ ] QA Lead runs smoke tests post-deployment
- [ ] Automation Engineer monitors CI/CD and rollback readiness
- [ ] Support/Customer Success monitors for customer-reported issues

### Communication
- [ ] Release notes published (Technical Writer, Release Manager)
- [ ] Customer communication sent (Release Manager, Support/Customer Success)
- [ ] Stakeholder updates provided (Project Manager, Release Manager)
- [ ] Support team briefed on changes and known issues

---

## Post-Release Phase

### Verification & Learning
- [ ] Release Manager conducts post-release review
- [ ] Success metrics reviewed against targets (Product Manager)
- [ ] Project Manager facilitates retrospective with all roles
- [ ] Key learnings documented and action items assigned

### Continuous Improvement
- [ ] Action items tracked with clear owners (Project Manager)
- [ ] Process improvements identified and implemented
- [ ] Customer feedback collected and shared (Support/Customer Success)
- [ ] Release retrospective published for future reference

---

## Critical Handoff Points

### Handoff 1: Design to Development
**From:** UX/UI Designer  
**To:** Developers  
**Checkpoint:**
- [ ] Design specs are clear and approved
- [ ] Developers have questions answered
- [ ] Acceptance criteria align with design
- [ ] Developers confirm feasibility

### Handoff 2: Development to QA
**From:** Developers  
**To:** QA Lead  
**Checkpoint:**
- [ ] Code is merged and deployed to test environment
- [ ] Unit tests pass
- [ ] Test plan is ready
- [ ] QA Lead has access to feature and documentation

### Handoff 3: QA to Release
**From:** QA Lead  
**To:** Release Manager  
**Checkpoint:**
- [ ] All acceptance criteria verified as met
- [ ] Known defects logged and prioritized
- [ ] Test coverage documented
- [ ] Release readiness sign-off provided

### Handoff 4: Release to Support
**From:** Release Manager  
**To:** Support/Customer Success  
**Checkpoint:**
- [ ] Release notes complete and accurate
- [ ] Known issues and workarounds documented
- [ ] Support team trained on new features
- [ ] Escalation procedures clear

---

## Communication Template

### Weekly Status Update (Project Manager to All)
```
**Project:** [Project Name]
**Week of:** [Date]

**Progress This Week:**
- [Key accomplishments]

**Next Steps:**
- [Planned work for next week]

**Risks & Blockers:**
- [Any risks or blockers requiring escalation]

**Metrics:**
- Sprint velocity: [X story points]
- Defect count: [X open, Y closed]
- Test coverage: [X%]

**Decisions Needed:**
- [Any decisions required from stakeholders or other roles]
```

---

## When to Escalate

### Escalation Triggers
- **Critical security vulnerability** → Escalate immediately to Project Manager and Release Manager
- **Release delay > 1 week** → Project Manager escalates to sponsor
- **Customer-impacting production issue** → Support/Customer Success escalates to Project Manager and Release Manager
- **Quality risk (low test coverage, high defect rate)** → QA Lead escalates to Project Manager
- **Deployment failure** → Release Manager and Automation Engineer investigate; Project Manager communicates

### Escalation Path
1. **Level 1:** Team-level triage in daily standup
2. **Level 2:** PM escalates to Product Lead and dependent teams
3. **Level 3:** Sponsor-level escalation for business-impacting issues

---

## Continuous Improvement Metrics

Track these metrics to ensure effective collaboration:

- **Time to resolution** (for defects and issues)
- **Deployment frequency** (how often releases occur)
- **Deployment success rate** (% of releases without rollback)
- **Mean time to recovery** (MTTR for production incidents)
- **Test coverage** (% of code covered by tests)
- **Customer satisfaction** (NPS, support ticket volume)
- **Documentation completeness** (% of features documented)
