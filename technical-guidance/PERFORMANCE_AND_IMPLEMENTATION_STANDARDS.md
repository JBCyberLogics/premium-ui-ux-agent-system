# Performance and Implementation Standards

## Architecture
- Follow existing project structure and conventions.
- Separate concerns and create reusable components where reuse is real.
- Avoid needless abstraction and over-generalized components.
- Keep state ownership clear and predictable.
- Preserve API contracts and existing integrations.
- Use semantic, maintainable code.

## Rendering and assets
- Optimize images, fonts, video, and icons.
- Use responsive image delivery and lazy loading where appropriate.
- Avoid layout shifts by reserving media dimensions.
- Load heavy or optional experiences on demand.
- Avoid shipping large libraries for small effects.
- Respect server/client boundaries in frameworks that distinguish them.

## Runtime
- Avoid unnecessary re-renders and expensive computations.
- Clean up event listeners, observers, subscriptions, and animation timelines.
- Avoid blocking main-thread work.
- Handle network failure, slow responses, and partial data.
- Keep error handling and loading feedback useful.

## Security and data integrity
- Never expose secrets in client code.
- Do not bypass authorization or validation for convenience.
- Do not fabricate production data or imply mock content is live.
- Preserve privacy and existing security boundaries.

## Verification
Run relevant build, lint, type, test, and runtime checks available in the project. Report unavailable checks. A successful build does not establish accessibility, usability, or visual quality.
