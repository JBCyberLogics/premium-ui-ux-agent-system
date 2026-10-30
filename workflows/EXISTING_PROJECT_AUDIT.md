# Existing Project Audit

## Objective
Improve an existing application without damaging working behaviour or replacing architecture unnecessarily.

## Audit checklist
- [ ] Identify framework, runtime, package manager, and versions.
- [ ] Inspect repository structure and project instructions.
- [ ] Identify routes, layouts, navigation, and entry points.
- [ ] Locate design tokens, global styles, component libraries, and themes.
- [ ] Identify shared components and duplicated patterns.
- [ ] Inspect assets, fonts, and image strategy.
- [ ] Identify API contracts, data sources, authentication, and permissions relevant to the UI.
- [ ] Review tests, build scripts, linting, and type checks.
- [ ] Run the existing application if possible.
- [ ] Record current defects and known limitations.

## Preservation rules
- Do not remove routes or features merely to simplify styling.
- Do not replace a framework or component library for convenience.
- Do not alter API contracts without coordination and approval.
- Do not delete tests because they fail; investigate first.
- Preserve user data and existing integrations.
- Make changes incrementally and verify regressions.

## Report
Summarize current architecture, reusable assets, constraints, risks, recommended improvements, and any major changes requiring approval.
