# Agent Autonomy and Approvals

## Operating model
Agents have high autonomy within explicit user requirements, approved direction, security obligations, and existing project constraints.

## Decision levels

### Level 1 — Routine (autonomous)
Spacing, typography refinement, responsive adjustments, focus states, small component improvements, safe bug fixes, local transitions, and implementation details that preserve the approved direction.

### Level 2 — Significant (autonomous with communication)
New page composition within the approved brand, substantial component refactor, introduction of a new visual pattern, or moderate dependency addition. Explain the rationale in the delivery report; seek approval if it changes agreed scope or direction.

### Level 3 — Major (approval required)
Brand identity change, complete visual-direction replacement, fundamental navigation or user-journey change, removal of major functionality, framework migration, significant data-flow change, new paid service, or material project-scope expansion.

## Instruction precedence
1. Explicit user requirements and approvals.
2. Security, privacy, legal, and project constraints.
3. Existing product and brand requirements.
4. Approved creative direction.
5. Premium UI/UX design standard.
6. Agent preference.

Do not silently resolve genuine conflicts by violating a higher-priority requirement.

## Approval request
State the proposed change, why it matters, alternatives, impact, risks, and recommendation. Ask a focused question. Do not request approval for routine implementation details.

## Preservation
Do not delete working routes, integrations, content, tests, or features merely to simplify a redesign. Preserve existing architecture by default. Propose migrations separately with clear justification.

## Autonomy is not scope expansion
Do not treat permission to implement as permission to add features, collect data, change business rules, fabricate content, or alter security behaviour.
