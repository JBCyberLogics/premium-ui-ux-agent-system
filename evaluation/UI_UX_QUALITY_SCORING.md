# UI/UX Quality Scoring

## Purpose
Score substantial interface work consistently using a weighted 100-point model. Scores must be evidence-based.

## Default rubric

| Category | Weight | Evaluation focus |
|---|---:|---|
| Visual design and composition | 20 | Hierarchy, layout, spacing, typography, color, imagery, polish |
| UX and usability | 20 | Task clarity, navigation, interaction predictability, feedback, content comprehension |
| Design system and consistency | 15 | Tokens, component consistency, variants, coherent visual language |
| Responsive design | 10 | Deliberate behaviour across relevant screen sizes and zoom |
| Motion and interactions | 10 | Purpose, timing, consistency, control, reduced motion, interaction states |
| Accessibility | 10 | Semantics, keyboard, focus, labels, contrast, announcements |
| Technical quality and performance | 10 | Maintainability, runtime stability, asset loading, bundle/animation cost |
| Originality and creative direction | 5 | Product fit, distinctiveness, thoughtful reference use |
| **Total** | **100** | |

## Scoring method
For each category, assign a percentage of its available points based on evidence:
- 0–24%: absent or seriously deficient;
- 25–49%: weak, inconsistent, or materially incomplete;
- 50–69%: adequate but with visible weaknesses;
- 70–84%: strong and mostly complete;
- 85–94%: excellent, with minor refinements possible;
- 95–100%: exceptional and thoroughly verified.

Awarded points = category weight × assessed percentage. Round category scores to one decimal if needed. Sum to a maximum of 100.

## Interpretation
- 95–100: Exceptional
- 90–94.9: Excellent
- 80–89.9: Strong
- 70–79.9: Needs refinement
- Below 70: Does not meet the standard

## Critical gate
A critical failure blocks acceptance regardless of score. Refer to `governance/QUALITY_ACCEPTANCE_CRITERIA.md`.

## Task-specific weighting
The default weights are a baseline, not a straitjacket. For a data-heavy dashboard, increase UX, accessibility, and data presentation emphasis. For a cinematic marketing page, visual composition and creative direction may carry more weight. Keep the total at 100 and explain every adjustment.

## Evidence and honesty
- Do not award points for checks that were not performed.
- Mark unavailable checks as unverified and explain why.
- Distinguish implementation evidence from rendered visual evidence.
- A successful build is not proof of good visual design.
- Include the score by category, total, critical-gate status, and key evidence in the delivery report.
