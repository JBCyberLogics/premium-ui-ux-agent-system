# Premium UI/UX Design Standard

**Version:** 1.0.0  
**Status:** Authoritative design specification  
**Audience:** All agents and teams producing or modifying user-facing software.

## 1. Purpose and definition

This standard defines what high-quality digital experiences must achieve. “Premium” means intentional, coherent, polished, distinctive, useful, accessible, and dependable. It does **not** mean automatically dark, expensive-looking, minimalist, glassmorphic, animated, or visually loud.

The right design is the one that best serves the product, audience, brand, content, and context.

## 2. Design principles

### 2.1 Purpose before decoration
Every element must support comprehension, navigation, action, feedback, identity, or atmosphere. Remove decoration that weakens clarity.

### 2.2 Clear hierarchy
Users should understand where they are, what matters, what they can do, and what happens next. Use scale, spacing, contrast, position, and grouping deliberately.

### 2.3 Distinctive composition
Avoid default template composition when the product warrants a stronger concept. Use editorial, asymmetric, bento, split-screen, immersive, modular, or conventional layouts according to content and usability—not trend alone.

### 2.4 Consistency with meaningful variation
Shared components should behave and appear consistently. Components with different purposes may have different compositions and visual treatments.

### 2.5 Content integrity
Never fabricate real products, prices, statistics, testimonials, inventory, user activity, or business claims. Use clearly labelled illustrative examples only when explicitly appropriate. Prefer honest empty states when data is unavailable.

### 2.6 Functional integrity
Visual changes must preserve working behaviour unless the user explicitly requests a change. A beautiful broken interface is not acceptable.

## 3. Creative direction

Before substantial design work, establish:
- product purpose and audience;
- brand personality and industry context;
- desired emotional tone;
- information density and primary user tasks;
- content and imagery requirements;
- technical and accessibility constraints;
- references and competitive patterns.

Translate these into a concise direction covering:
1. visual concept;
2. layout and composition language;
3. typography character and scale;
4. palette and contrast strategy;
5. imagery and art direction;
6. component character;
7. motion principles;
8. responsive adaptation.

Possible directions include luxury editorial, enterprise clarity, expressive creative, warm human, technical/futuristic, utilitarian, or playful. These are examples, not a closed catalogue. Obtain approval before changing an established brand or agreed direction.

## 4. Layout and composition

- Establish a deliberate grid and alignment system.
- Use whitespace to separate meaning, not as arbitrary emptiness.
- Control content width and line length for readability.
- Establish rhythm across sections and page lengths.
- Use asymmetry only when it improves hierarchy or character.
- Avoid repetitive card grids when a more suitable presentation exists.
- Keep primary actions discoverable and visually clear.
- Ensure composition remains coherent at narrower widths.
- Avoid horizontal overflow and accidental overlap.

## 5. Typography

- Choose typefaces appropriate to brand, language, readability, and available licensing.
- Use a deliberate scale for display, heading, body, labels, metadata, and captions.
- Control line length, line height, letter spacing, and weight.
- Avoid excessive font families and arbitrary font weights.
- Preserve readable text contrast and minimum practical sizes.
- Use fluid typography only within controlled bounds.
- Do not use oversized display type at the expense of content comprehension.

## 6. Color and surface systems

- Define primary, secondary, accent, neutral, and semantic colors.
- Define semantic roles such as background, surface, elevated surface, text, muted text, border, focus, success, warning, and danger.
- Check contrast for text, controls, icons, and meaningful boundaries.
- Use accents selectively; avoid competing highlights.
- Gradients, blur, transparency, shadows, glow, and glass effects must support hierarchy or brand expression.
- Do not assume dark mode is inherently premium.
- If themes are supported, design and test each theme as a complete experience.

## 7. Imagery and visual assets

- Use relevant, high-quality, properly licensed or user-provided assets.
- Art-direct crop, focal point, aspect ratio, overlay, and placement.
- Optimize images and provide appropriate alternative text.
- Avoid irrelevant stock imagery, broken assets, watermarks, and inconsistent image treatment.
- Do not invent brand marks or imply partnerships.
- Use placeholders only when clearly identified and appropriate.
- Use decorative imagery without alternative text when it conveys no information; meaningful imagery needs useful text alternatives.

## 8. Navigation

Navigation must make location, hierarchy, and next actions understandable.

- Navbars should fit product complexity and screen size.
- Sidebars should support scanning, grouping, active state, and collapse behaviour where useful.
- Mobile navigation must be deliberately designed, not merely squeezed.
- Menus, dropdowns, breadcrumbs, tabs, and pagination need clear states and keyboard support.
- Sticky or floating navigation must not obscure content.
- Glass or translucent navigation requires sufficient contrast and backdrop resilience.

## 9. Component standards

### Buttons and actions
Use clear action labels, distinct primary/secondary/tertiary hierarchy, visible focus, disabled and loading states, adequate hit areas, and clear feedback. Avoid ambiguous icon-only actions unless their meaning is accessible.

### Cards
Choose structure based on content: product, feature, metric, testimonial, pricing, article, or action. Avoid making every card identical. Provide clear hierarchy and purposeful interaction; hover effects must not be the only way to reveal essential content.

### Forms and authentication
Use explicit labels, appropriate input types, helpful instructions, inline validation, error recovery, password visibility where suitable, and clear submission feedback. Preserve entered values when safe and useful. Do not claim authentication works without a real integration.

### Tables and data
Prioritize scanability, alignment, meaningful formatting, sorting/filtering feedback, empty states, and responsive alternatives. Preserve access to important information on small screens.

### Modals, drawers, and popovers
Use only when they improve focus or contextual access. Provide dismissal, focus management, keyboard behaviour, and sensible mobile treatment. Avoid stacking overlays.

### Dashboards
Prioritize tasks and information hierarchy. Distinguish KPIs, trends, tables, alerts, and activity. Label units and time ranges. Charts must communicate honestly and must not imply fabricated live data.

## 10. Page and experience patterns

### Landing and marketing pages
Build a narrative rather than stacking generic sections. Establish the proposition, proof, product or service detail, benefits, and next action. Hero sections may be cinematic, editorial, split-screen, image-led, or minimal depending on the brand. Final CTAs should feel like a purposeful conclusion, not a repeated banner.

### Product and marketplace experiences
Support discovery, comparison, detail, trust, availability, and clear next steps. Never invent stock, prices, reviews, or seller credentials.

### Application and dashboard experiences
Optimize for repeated tasks, clarity, speed, status visibility, and information density. Make navigation and state transitions predictable.

### Authentication and onboarding
Minimize friction, explain requirements, provide recovery, and communicate privacy and security accurately. Decorative backgrounds must not reduce form readability.

## 11. Interaction and feedback

Every interactive control needs:
- an understandable affordance;
- hover where applicable;
- visible keyboard focus;
- pressed/selected/expanded states as applicable;
- disabled and loading states where relevant;
- success, error, or confirmation feedback;
- predictable keyboard and pointer behaviour.

Do not use hover as the sole interaction mechanism. Do not make controls appear interactive if they do nothing.

## 12. Motion and animation

Motion must communicate state, hierarchy, continuity, feedback, or storytelling. Define a coherent motion language with durations, easing, distance, and sequencing.

Use simple CSS transitions for simple state changes. Use a dedicated motion library only when its capabilities justify the dependency. Scroll-triggered and 3D experiences require particular attention to performance, accessibility, and device capability.

Respect `prefers-reduced-motion`. Avoid scroll hijacking, excessive parallax, long blocking entrances, layout shifts, and animations that delay access to content. See [`technical-guidance/ANIMATION_AND_MOTION_GUIDELINES.md`](technical-guidance/ANIMATION_AND_MOTION_GUIDELINES.md).

## 13. Responsive design

Treat mobile, tablet, and desktop as related but intentionally composed experiences. Reconsider hierarchy, navigation, controls, imagery, spacing, and content order at each breakpoint. Do not merely scale down desktop. See [`technical-guidance/RESPONSIVE_AND_ACCESSIBILITY_STANDARDS.md`](technical-guidance/RESPONSIVE_AND_ACCESSIBILITY_STANDARDS.md).

## 14. Accessibility

Use semantic structure, keyboard access, visible focus, appropriate labels, contrast, accessible names, status announcements, logical focus order, and reduced-motion alternatives. Do not rely on color alone. Accessibility is part of product quality, not optional polish.

## 15. Design systems

Define reusable tokens for:
- color and semantic roles;
- typography;
- spacing;
- layout and breakpoints;
- borders and radii;
- elevation and shadows;
- motion;
- component variants;
- theme behaviour.

Use a single source of truth where the framework supports it. Avoid duplicated or contradictory values. Document intentional exceptions.

## 16. States and edge cases

Design and test:
- initial and populated states;
- loading and skeleton states;
- empty states;
- errors and recovery;
- success and confirmation;
- disabled and permission-restricted states;
- long content and overflow;
- missing or unavailable data;
- slow network and partial failure;
- narrow viewport and zoom.

Never conceal unavailable functionality behind a misleading visual.

## 17. Technical quality

Visual quality must coexist with maintainability, semantic code, predictable state, security, performance, and compatibility. Follow existing project conventions unless a change is justified and authorized. See [`technical-guidance/PERFORMANCE_AND_IMPLEMENTATION_STANDARDS.md`](technical-guidance/PERFORMANCE_AND_IMPLEMENTATION_STANDARDS.md).

## 18. Verification and acceptance

For substantial UI work:
- run relevant technical checks;
- inspect actual rendered pages whenever visual inspection tools are available;
- evaluate representative viewport sizes;
- test key interactions and states;
- perform an accessibility review proportionate to the task;
- fix defects and reinspect;
- provide a weighted score and evidence-based report.

A critical failure blocks acceptance regardless of numerical score. See [`governance/QUALITY_ACCEPTANCE_CRITERIA.md`](governance/QUALITY_ACCEPTANCE_CRITERIA.md) and [`evaluation/UI_UX_QUALITY_SCORING.md`](evaluation/UI_UX_QUALITY_SCORING.md).

## 19. Quality score

The default weighting is:
- Visual design and composition: 20
- UX and usability: 20
- Design system and consistency: 15
- Responsive design: 10
- Motion and interactions: 10
- Accessibility: 10
- Technical quality and performance: 10
- Originality and creative direction: 5

Total: 100. Weights may be adapted for task type if the rationale is documented. Unverified criteria must not be represented as verified.

## 20. Final standard

The finished experience should feel intentionally designed rather than assembled from defaults. It should be visually coherent, easy to use, responsive, accessible, performant, honest about its capabilities, and consistent with the product's identity. Every major decision should have a reason; every claimed verification should have evidence.
