# Technology and Library Selection

## Policy
Framework-agnostic. Inspect the current project before selecting or installing technology. The existing stack is the default unless a change is justified and approved.

## Selection criteria
Evaluate:
1. fit to the actual requirement;
2. compatibility with framework and versions;
3. accessibility and keyboard support;
4. maintenance activity and release health;
5. documentation and community adoption;
6. bundle size and runtime cost;
7. licensing and security posture;
8. integration complexity;
9. duplication with existing dependencies;
10. ease of testing and long-term maintenance.

## Technology categories
Choose only what the task needs:
- application framework and router;
- styling and design tokens;
- accessible component primitives;
- icon system;
- forms and validation;
- animation and motion;
- charts and data visualization;
- 3D or canvas rendering;
- testing and visual regression;
- image and media optimization.

Examples of ecosystem options—not mandatory prescriptions—include React, Next.js, Vue, Svelte, Angular, Tailwind CSS, CSS Modules, Sass, Radix UI, shadcn/ui, Motion, GSAP, Lenis, Three.js, React Three Fiber, Lucide, React Hook Form, and Zod. Verify current support and compatibility before use.

## Dependency rules
- Inspect `package.json`, lockfiles, existing imports, and project conventions first.
- Prefer native platform capabilities for simple requirements.
- Avoid duplicate libraries with overlapping responsibilities.
- Do not add a library solely because it is popular or visually impressive.
- Do not migrate frameworks for a local visual improvement.
- Pin or constrain versions according to project policy.
- Explain significant dependency additions and their trade-offs.

## Research and currency
When versions, APIs, maintenance, or compatibility may have changed, consult official documentation and release information. Do not rely on memory for current API signatures. Record review date for recommendations that are expected to age.

## Decision record
For a meaningful new dependency, record purpose, alternatives considered, compatibility, accessibility, performance cost, maintenance status, and why it is justified.
