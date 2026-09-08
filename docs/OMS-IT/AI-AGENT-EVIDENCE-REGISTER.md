# OMS IT — AI Agent Evidence Register

This public register provides an evidence-first index of AI-agent work associated with OMS IT. It intentionally publishes safe metadata and evidence direction only; private source code, secrets, credentials, private logs, internal infrastructure and confidential project data remain private.

## Evidence vocabulary

- **Declared** — documented as a planned or intended capability.
- **Implemented** — implementation exists in the engineering workspace.
- **Integrated** — connected to the relevant system or workflow.
- **Tested** — supported by recorded testing evidence.
- **Deployed** — deployed to a non-local environment.
- **Production** — serving a production surface.
- **Verified** — independently or reproducibly checked against the stated evidence.

## Public evidence rule

Agent claims should identify the agent/project, role, implementation status, tools or providers where publishable, authorization boundary, testing status, deployment status, public evidence and last verification date. Do not publish credentials, secrets, private prompts, private customer data, internal endpoints or sensitive operational details.

## Current public register

The public record should contain only agents for which the corresponding status and evidence can be supported. An architectural target or declared capability must not be presented as a deployed or production agent without deployment evidence.

### omsai-foundry

- **Status:** Declared / architectural target unless a newer public deployment record establishes a stronger status.
- **Role:** AI-agent and AI-system engineering foundation.
- **Evidence direction:** OMS IT engineering documentation and intentionally published project evidence.
- **Verification rule:** Do not infer a deployed-agent count from repository names or architecture documents alone.

## Audit procedure

1. Identify the exact agent and project.
2. Verify implementation evidence.
3. Verify integration and authorization boundaries.
4. Verify tests and relevant security controls.
5. Verify deployment and public endpoint, if applicable.
6. Record only the strongest status supported by evidence.
7. Re-check after material releases or architecture changes.

## Publication boundary

This file is a public evidence index, not a copy of the private OMS IT agent workspace. Private implementation details remain in the private engineering source of truth.
