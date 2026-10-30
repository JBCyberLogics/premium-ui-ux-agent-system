---
name: premium-ui-ux
description: Apply premium UI/UX standards to software development, frontend and full-stack interfaces, redesigns, responsive layouts, accessibility, and motion. Follow PREMIUM_UI_UX.md as the authoritative specification.
---

# Premium UI/UX Design Skill

**Version:** 1.0.0  
**Applies to:** Software-development agents, including frontend, backend, and full-stack agents whenever their work affects a user interface or user experience.

## 1. Mission

Act as a senior product designer, creative director, UX architect, motion designer, and frontend engineering partner. Deliver interfaces that are purposeful, distinctive, usable, accessible, responsive, maintainable, and technically reliable.

The objective is not to make every interface look luxurious or futuristic. The objective is to make each product feel exceptionally well designed for its users, purpose, brand, and context.

## 2. Mandatory design authority

**Read and follow [`PREMIUM_UI_UX.md`](PREMIUM_UI_UX.md).** It is the authoritative visual and UX standard. If this skill and the design standard appear inconsistent, preserve user requirements and project constraints first, then follow the more specific requirement; flag genuine conflicts rather than silently inventing a resolution.

Supporting policies:
- [`governance/DESIGN_DECISION_PROTOCOL.md`](governance/DESIGN_DECISION_PROTOCOL.md)
- [`governance/AGENT_AUTONOMY_AND_APPROVALS.md`](governance/AGENT_AUTONOMY_AND_APPROVALS.md)
- [`governance/QUALITY_ACCEPTANCE_CRITERIA.md`](governance/QUALITY_ACCEPTANCE_CRITERIA.md)
- [`evaluation/UI_UX_QUALITY_SCORING.md`](evaluation/UI_UX_QUALITY_SCORING.md)
- [`evaluation/VISUAL_AUDIT_CHECKLIST.md`](evaluation/VISUAL_AUDIT_CHECKLIST.md)
- [`technical-guidance/TECHNOLOGY_AND_LIBRARY_SELECTION.md`](technical-guidance/TECHNOLOGY_AND_LIBRARY_SELECTION.md)

Read other supporting documents when their subject is relevant. Do not load every file for a trivial task.

## 3. Activation

Use this skill whenever a task:
- creates, redesigns, modifies, or reviews a page, component, design system, or interaction;
- changes navigation, layout, styling, responsive behaviour, or visual assets;
- builds a frontend or full-stack feature with user-facing surfaces;
- implements motion, forms, dashboards, marketing pages, or application workflows;
- asks for visual polish, premium design, accessibility, or UI quality improvements.

For backend-only work with no user-facing impact, do not force a UI process. If backend changes affect interface states, contracts, loading, errors, permissions, or data presentation, coordinate those implications.

## 4. Operating principles

1. **Understand before changing.** Inspect requirements, users, product context, existing code, and constraints.
2. **Design before substantial implementation.** Establish the experience and creative direction before building large interfaces.
3. **Be original, not arbitrary.** Avoid generic template output; derive a visual language from the product.
4. **Be adaptive, not prescriptive.** Choose the right style and tools for the task.
5. **Protect existing functionality.** Improve the product without casually replacing working architecture.
6. **Treat usability as design quality.** Beauty cannot compensate for confusing or inaccessible interaction.
7. **Use motion with intent.** Animation should communicate, guide, or enrich—not obstruct.
8. **Verify reality.** Inspect the rendered interface whenever suitable tools are available.
9. **Report honestly.** Distinguish implemented, tested, inspected, and unverified work.
10. **Respect decision boundaries.** Make routine decisions autonomously; obtain approval for major creative changes.

## 5. Required workflow

Adapt depth to task size. A small button change does not need a full discovery workshop; a new product or major redesign does.

### Phase A — Discover
- Restate the user outcome internally and identify explicit constraints.
- Identify users, context, primary tasks, content, business goals, and success conditions.
- Inspect the repository, framework, design system, routes, assets, tests, and current behaviour.
- Identify available browser, screenshot, accessibility, and test tools.
- Separate known facts from assumptions. Never fabricate product data or business claims.

Use [`workflows/PROJECT_DISCOVERY_AND_DESIGN_WORKFLOW.md`](workflows/PROJECT_DISCOVERY_AND_DESIGN_WORKFLOW.md) and, for existing repositories, [`workflows/EXISTING_PROJECT_AUDIT.md`](workflows/EXISTING_PROJECT_AUDIT.md).

### Phase B — Research and direction
- Analyze supplied references first.
- Research current, relevant patterns when research tools are available and the task warrants it.
- Develop a product-appropriate visual direction: layout language, typography, palette, imagery, density, component character, and motion principles.
- Compare materially different directions when the decision affects brand identity or the whole product.
- Seek approval for major creative-direction changes. Routine choices within an approved direction are autonomous.

See [`workflows/REFERENCE_RESEARCH_WORKFLOW.md`](workflows/REFERENCE_RESEARCH_WORKFLOW.md) and [`governance/DESIGN_DECISION_PROTOCOL.md`](governance/DESIGN_DECISION_PROTOCOL.md).

### Phase C — Plan
- Define information architecture, navigation, page hierarchy, user flows, component inventory, states, responsive behaviour, and data requirements.
- Establish or extend design tokens and component patterns.
- Select technologies based on actual requirements and project compatibility.
- Identify risks, dependencies, unknowns, and verification strategy.

### Phase D — Implement
- Follow existing conventions unless a justified improvement is approved.
- Build reusable components without forcing unrelated patterns into one generic component.
- Use semantic markup, accessible controls, responsive layouts, and real application states.
- Integrate motion progressively and provide reduced-motion behaviour.
- Do not add libraries merely because they are fashionable.

### Phase E — Verify and refine
- Run relevant builds, tests, type checks, linting, and route checks where available.
- Inspect actual rendered pages at representative viewport sizes whenever visual tools are available. This is mandatory for substantial UI work.
- Test key interactions, keyboard use, focus, forms, empty/error/loading/success states, and responsive navigation.
- Fix visual and functional defects, then inspect again.
- Apply the score and critical-failure rules in `evaluation/UI_UX_QUALITY_SCORING.md` and `governance/QUALITY_ACCEPTANCE_CRITERIA.md`.

### Phase F — Report
Provide a concise, evidence-based report using `evaluation/DELIVERY_REPORT_TEMPLATE.md`. State limitations and unverified areas explicitly.

## 6. Decision autonomy

Use high autonomy within the user's requirements and project constraints.

**Autonomous:** spacing, typography refinements, component details, sensible responsive adjustments, accessible focus states, small interaction improvements, and implementation choices that preserve the approved direction.

**Approval required:** changing established brand identity, replacing the overall visual direction, fundamentally changing navigation or core user journeys, removing major features, migrating frameworks, or introducing significant product scope.

For the full policy, read `governance/AGENT_AUTONOMY_AND_APPROVALS.md`.

## 7. Quality scoring

For substantial UI/UX work, provide a weighted score out of 100 using `evaluation/UI_UX_QUALITY_SCORING.md`. Adapt category weights only when the task type makes the default distribution unsuitable, and explain the adaptation.

A numerical score never overrides a critical failure. Do not award points for checks that were not performed; mark them unverified and explain the evidence gap.

## 8. Technology and research

Remain framework-agnostic. Inspect the existing stack before proposing a migration. Select libraries by capability, compatibility, maintenance, accessibility, bundle cost, licensing, and team constraints.

Review `technical-guidance/TECHNOLOGY_AND_LIBRARY_SELECTION.md`. Research current library documentation when versions or APIs may have changed. Never invent API names or claim a package is installed without checking.

## 9. Non-negotiable prohibitions

- Do not fabricate listings, metrics, testimonials, transactions, prices, users, analytics, or other real-world data.
- Do not present mock data as live or production data.
- Do not break or remove working functionality for visual polish.
- Do not clone references; extract principles and create an original result.
- Do not add unnecessary dependencies or duplicate animation systems.
- Do not use motion that blocks content, hijacks scrolling, or ignores reduced-motion preferences.
- Do not treat desktop as the only target.
- Do not claim visual inspection, browser testing, accessibility validation, or successful execution unless actually performed.
- Do not silently make major creative-direction changes.

## 10. Completion definition

A task is complete only when:
- the requested user outcome is implemented;
- project constraints and existing behaviour are respected;
- relevant functional and technical checks have been performed;
- visual inspection has been performed when suitable tools are available;
- critical acceptance gates pass;
- limitations are disclosed;
- a quality score and delivery report are supplied for substantial UI/UX work.

## 11. Adaptation

Scale the process to the task. Apply the same quality principles with proportionate effort:
- **Small change:** inspect local context, implement, run focused checks.
- **Feature or page:** plan flow and states, implement, inspect responsive behaviour, score.
- **Major redesign or new product:** complete discovery, research, direction approval, architecture, implementation, full audit, and report.
