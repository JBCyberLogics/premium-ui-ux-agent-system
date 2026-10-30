# Visual Audit Checklist

Use this checklist whenever suitable visual inspection tools are available. For substantial UI work, inspection is mandatory.

## Preparation
- [ ] Run the application using the project's documented method.
- [ ] Confirm the intended route and state.
- [ ] Use realistic content lengths without fabricating production claims.
- [ ] Capture representative desktop, tablet, and mobile views where relevant.
- [ ] Check light/dark themes if supported.

## Composition
- [ ] Clear hierarchy and focal point.
- [ ] Consistent alignment and spacing rhythm.
- [ ] Appropriate content width and line length.
- [ ] No accidental overlap, clipping, or horizontal overflow.
- [ ] Section transitions and page rhythm feel intentional.

## Typography and color
- [ ] Type scale and weights are coherent.
- [ ] Text remains readable at all tested sizes.
- [ ] Contrast is sufficient.
- [ ] Accent colors are used consistently.
- [ ] Focus and semantic states are distinguishable.

## Components and content
- [ ] Buttons, cards, forms, tables, navigation, and overlays fit their purpose.
- [ ] Image crops and focal points are correct.
- [ ] Long labels, empty content, and validation messages are handled.
- [ ] No broken assets, placeholder leakage, or invented data.

## Interaction
- [ ] Primary actions work.
- [ ] Hover, focus, active, disabled, loading, and selected states are coherent.
- [ ] Menus and overlays open and close predictably.
- [ ] Keyboard operation is possible.
- [ ] Feedback is understandable.

## Responsive
- [ ] Navigation works at narrow widths.
- [ ] Content order and hierarchy adapt intentionally.
- [ ] Controls remain usable.
- [ ] Images and text reflow appropriately.
- [ ] No content is hidden or clipped.

## Motion
- [ ] Motion has a purpose.
- [ ] No scroll hijacking or blocking entrance sequence.
- [ ] No layout instability.
- [ ] Reduced-motion behaviour is respected.
- [ ] Performance remains acceptable.

## Record
For each defect, record severity, location, reproduction steps, expected result, actual result, and correction. Reinspect after fixes.

If visual tools are unavailable, state that rendered visual inspection was not performed. Do not claim this checklist passed.
