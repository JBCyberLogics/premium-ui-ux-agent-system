# Versioning Policy

## Version format
Use semantic versioning: `MAJOR.MINOR.PATCH`.

- **MAJOR:** incompatible restructuring or changed core requirements.
- **MINOR:** new guidance, workflows, or capabilities that remain compatible.
- **PATCH:** clarifications, corrections, and non-breaking improvements.

## Compatibility
Keep relative links valid. Update the README and changelog when files move or responsibilities change. If an agent integration requires a specific skill format, document that adapter separately rather than weakening the framework-agnostic core.

## Release checklist
- [ ] Update version references.
- [ ] Update `CHANGELOG.md`.
- [ ] Validate internal Markdown links.
- [ ] Confirm score weights total 100.
- [ ] Check terminology and cross-document consistency.
- [ ] Review installation instructions.
- [ ] Check for outdated library recommendations.
- [ ] Verify no placeholders or contradictory rules remain.
