# Responsive and Accessibility Standards

## Responsive design
- Design for content and tasks, not named device sizes alone.
- Establish breakpoints based on where the layout stops working.
- Reconsider navigation, content order, density, imagery, and control placement at narrow widths.
- Avoid fixed widths that cause overflow.
- Use fluid containers and typography within sensible bounds.
- Ensure touch targets are practical and sufficiently separated.
- Test zoom and text enlargement where applicable.
- Tables, charts, and complex data need a usable narrow-screen strategy.

## Accessibility baseline
- Use semantic HTML and native controls where appropriate.
- Provide labels and accessible names.
- Ensure keyboard operation and visible focus.
- Maintain logical reading and focus order.
- Use sufficient contrast for text and meaningful UI boundaries.
- Do not communicate meaning by color alone.
- Provide text alternatives for informative images.
- Associate validation errors with their fields.
- Announce important dynamic status changes appropriately.
- Manage focus correctly in dialogs, drawers, and route transitions.
- Respect reduced-motion preferences.
- Ensure controls have understandable names and states.

## Review
Use automated checks as support, not as a substitute for manual review. Test keyboard-only flows and representative screen sizes. Verify focus visibility, labels, contrast, semantics, and dynamic feedback.

## Standard
Target WCAG 2.2 AA where feasible and applicable. If the project has a stricter legal or organizational requirement, follow that requirement. Document known exceptions and remediation plans.
