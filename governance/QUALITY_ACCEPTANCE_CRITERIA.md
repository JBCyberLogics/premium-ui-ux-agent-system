# Quality Acceptance Criteria

## Acceptance rule
A task passes only when the requested outcome is delivered, relevant checks are completed, no critical failure remains, and limitations are reported. A high numerical score cannot override a critical failure.

## Critical failure gates
Any of the following blocks acceptance:
- primary navigation or essential user journey is broken;
- a requested core feature no longer works;
- serious security, privacy, or data-integrity regression is introduced;
- critical content or controls are inaccessible to keyboard or assistive technology;
- major viewport causes unusable layout or hides essential actions;
- primary form cannot be completed or errors cannot be recovered from;
- fabricated real-world data is presented as genuine;
- severe rendering or runtime error affects core use;
- unapproved scope or major creative-direction change is made.

Severity should be judged in context. A minor decorative issue is not a critical failure.

## Required checks for substantial UI work
- build/type/lint/test checks where available;
- route and navigation checks;
- primary interaction checks;
- representative desktop and mobile inspection;
- loading, empty, error, and success states relevant to the feature;
- keyboard and focus review;
- reduced-motion review when animation is used;
- visual audit and weighted score.

## Evidence
For each check report: passed, failed, not applicable, or unverified. Include the method used. Do not infer success from source code alone.

## Acceptance levels
- **Accepted:** critical gates pass; relevant checks pass; score and limitations documented.
- **Accepted with known limitations:** no critical failure, but disclosed non-critical gaps remain.
- **Not accepted:** any critical failure remains or essential verification is missing without a valid limitation explanation.

## Small tasks
Scale checks to risk. A small styling correction does not require a full application audit, but must still be checked in context.
