# DSRV Management Enterprise

DSRV Management is the enterprise home for DSRV’s engineering, quality, and AI-assisted software delivery work.

This enterprise supports the repositories, workflows, and operational systems behind DSRV platform development, including stability intelligence, pharmaceutical quality workflows, Local HQ operations, and agent-assisted PR review.

## Mission

DSRV builds software systems that help turn complex operational, quality, and compliance workflows into clear, auditable, human-reviewable processes.

Our engineering model combines:

- Human-owned product direction
- AI-assisted development
- Evidence-backed QA
- Pull request review discipline
- Clear approval gates before production changes

## Core platforms

### DSRV Stability / ECI

The DSRV Stability and ECI platform supports pharmaceutical stability-program workflows, including:

- Stability study visibility
- Study health and triage
- OOS / OOT surfacing
- Shelf-life analysis
- Import review and signoff
- Quality evidence tracking
- Human-in-the-loop review flows

### Local HQ

Local HQ is the operational command center for DSRV work. It supports:

- Workflow tickets
- QA receipts
- Agent dispatch
- Delivery tracking
- Review handoffs
- Operational audit trails

### DSRV Platform

The broader DSRV platform includes internal and external product surfaces for dashboards, customer workflows, intelligence tools, and operational systems.

## Engineering workflow

DSRV uses a structured AI-assisted engineering workflow.

Typical work passes through:

1. Scoped issue or work-order definition
2. Branch or PR implementation
3. Local verification gates
4. Code review
5. QA evidence capture
6. Human approval
7. Controlled merge and deployment

AI agents may assist with development, review, QA, and documentation, but production-impacting decisions remain human-owned.

## Repository governance

Repositories under this enterprise should follow these principles:

- Keep production code, experiments, and agent scratch work clearly separated
- Preserve clean git history and reviewable pull requests
- Avoid committing secrets, credentials, generated junk, or local environment files
- Require evidence for major fixes, launches, and production-readiness claims
- Use protected branches and review gates where appropriate
- Document ownership and operational context for critical systems

## Security principles

DSRV treats access control, authentication, and billing as sensitive enterprise-level functions.

Security expectations:

- Use least-privilege access
- Avoid sharing credentials in issues, PRs, tickets, comments, or agent logs
- Require owner review for permission changes
- Treat SSO, billing, and enterprise-owner changes as high-impact administrative actions
- Maintain recovery access before changing authentication configuration
- Keep auditability for production and quality-system work

## AI-assisted development

DSRV uses AI-assisted engineering to increase throughput across PR creation, code review, QA, and operational documentation.

Primary goals for enterprise-level AI workflows:

- Higher coding and PR-review capacity
- Centralized usage visibility
- Better billing controls
- Secure repository access
- Reliable review and QA workflows
- Clear separation between agent assistance and human approval

## Quality and compliance mindset

Because DSRV systems may support pharmaceutical quality and stability workflows, engineering work should emphasize:

- Traceability
- Data integrity
- Human review
- Clear evidence
- Reproducible verification
- Controlled changes
- Audit-friendly documentation

## Operating principles

- No production-impacting change without review and verification
- No secrets in code, tickets, comments, or agent-visible logs
- PRs should include clear scope, testing evidence, and risk notes
- QA findings should be captured with exact repro steps
- Authentication, billing, and enterprise permissions require deliberate owner action
- Agent-generated work must remain inspectable and human-approved

## Enterprise administration

Enterprise administration should remain limited to trusted owners.

Recommended setup priorities:

1. Maintain at least two trusted enterprise owners
2. Confirm billing and AI usage model before scaling automation
3. Configure SSO only after recovery access is confirmed
4. Apply repo and branch protections to production systems
5. Monitor usage, Actions minutes, Copilot/AI requests, and billing trends

## Contact

Enterprise owner: Thedson Desravines  
Organization: DSRV-Management  
Enterprise: dsrv-management-enterprise
