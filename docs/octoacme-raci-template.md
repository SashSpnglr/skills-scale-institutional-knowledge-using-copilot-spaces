# OctoAcme RACI Matrix Template

## Purpose
The RACI matrix clarifies roles and responsibilities for key project activities and decisions. Use this template to eliminate ambiguity, prevent overlaps, and ensure accountability across cross-functional teams.

## When to Use
- During project initiation to align stakeholders on decision-making authority
- When introducing new roles or team members
- To resolve confusion about who owns specific activities
- For complex, cross-functional projects with multiple stakeholders

## RACI Definitions

- **R — Responsible**: Does the work to complete the task. Multiple people can be Responsible.
- **A — Accountable**: Ultimately answerable for completion and has veto power. Only ONE person should be Accountable per activity.
- **C — Consulted**: Provides input and expertise. Two-way communication.
- **I — Informed**: Kept up-to-date on progress. One-way communication.

## Best Practices

1. **One Accountable per activity**: Avoid "A" for multiple people to prevent decision deadlock
2. **Minimize "C"**: Too many consultations slow down decisions
3. **Be specific**: Break down activities to an appropriate level of detail
4. **Review regularly**: Update the matrix as roles or project scope changes
5. **Get agreement**: All stakeholders should review and approve the RACI matrix

## Template

| Activity / Decision | Project Sponsor | Project Manager | Product Manager | Solution Architect | Developer | QA Lead | Business Analyst | Change Manager | Stakeholders |
|---------------------|-----------------|-----------------|-----------------|--------------------|-----------|---------|--------------------|----------------|--------------|
| Approve project initiation | A | R | C | C | I | I | C | I | C |
| Define project scope | C | A | R | C | I | I | R | I | C |
| Create project plan | I | A/R | C | C | I | C | I | I | I |
| Approve budget | A | R | I | I | I | I | I | I | C |
| Define technical architecture | I | I | C | A/R | C | C | I | I | I |
| Implement features | I | I | C | C | A/R | C | I | I | I |
| Define test strategy | I | C | C | C | C | A/R | I | I | I |
| Execute testing | I | I | I | I | C | A/R | I | I | I |
| Define acceptance criteria | I | C | A | C | C | R | R | I | C |
| Approve release | C | A | C | C | I | R | I | I | I |
| Manage project risks | C | A/R | C | C | I | C | I | I | I |
| Stakeholder communication | I | A/R | C | I | I | I | C | C | I |
| Facilitate retrospectives | I | A/R | C | I | C | C | C | I | I |
| Develop change plan | C | C | I | I | I | I | C | A/R | C |
| Conduct training | I | I | I | I | I | I | C | A/R | I |
| Business requirements gathering | I | C | A | I | I | I | R | C | C |
| Technical design review | I | I | C | A | R | C | I | I | I |

## Instructions for Use

1. **Copy this template** to your project documentation (e.g., project charter, README, or dedicated RACI doc)
2. **Customize rows** to reflect your project's specific activities and decision points
3. **Add/remove columns** based on roles involved in your project
4. **Fill in the matrix** using R, A, C, I designations
5. **Review with team** during project kickoff or planning
6. **Update as needed** when roles, scope, or team structure changes

## Example: Feature Development

| Activity / Decision | Project Manager | Product Manager | Solution Architect | Developer | QA Lead | Business Analyst |
|---------------------|-----------------|-----------------|--------------------|-----------|---------|--------------------|
| Define feature requirements | C | A | C | C | C | R |
| Prioritize backlog | C | A/R | I | I | I | C |
| Design technical solution | I | C | A/R | C | C | I |
| Write code | I | I | C | A/R | I | I |
| Code review | I | I | C | R | C | I |
| Create test cases | I | C | C | C | A/R | C |
| Execute tests | I | I | I | C | A/R | I |
| Approve feature for release | C | A | C | I | R | C |
| Document feature | I | C | I | R | I | C |

## Troubleshooting Common Issues

| Issue | Solution |
|-------|----------|
| Too many people Accountable for one activity | Designate a single owner; others become Responsible or Consulted |
| Unclear who makes final decision | Identify the Accountable person; ensure only one "A" per row |
| Activities taking too long | Reduce the number of "C" (Consulted) roles; convert some to "I" (Informed) |
| Team members confused about expectations | Add more specific activity rows; conduct a RACI review meeting |
| Matrix becomes outdated | Schedule quarterly RACI reviews as part of retrospective |

## Related Documentation
- [OctoAcme Roles and Personas](./octoacme-roles-and-personas.md)
- [OctoAcme Project Management Overview](./octoacme-project-management-overview.md)
- [OctoAcme Project Initiation](./octoacme-project-initiation.md)
