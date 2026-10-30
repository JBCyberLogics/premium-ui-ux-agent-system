# Animation and Motion Guidelines

## Purpose
Treat motion as part of the interaction and visual system—not decoration applied after the interface is built.

## Motion principles
- Purpose: communicate state, cause and effect, hierarchy, continuity, feedback, or storytelling.
- Restraint: not every element needs animation.
- Consistency: establish shared durations, easing, distance, and sequencing.
- Responsiveness: adapt or remove costly effects on constrained devices.
- Accessibility: respect `prefers-reduced-motion`.
- Performance: avoid expensive layout and paint work where possible.

## Motion categories
1. Micro-interactions: button feedback, toggles, validation, icon state.
2. Component transitions: menus, tabs, drawers, dialogs, cards.
3. Navigation transitions: route or page changes.
4. Scroll storytelling: reveals, parallax, pinned sequences.
5. Media transitions: image reveals, video transitions, text treatments.
6. Advanced interaction: 3D, canvas, data visualization.

## Tool selection
- CSS transitions/animations: simple hover, focus, opacity, transform, and state changes.
- Motion for React or equivalent: component and layout transitions in supported UI frameworks.
- GSAP/ScrollTrigger or equivalent: complex timelines, scroll-linked sequences, coordinated scenes.
- Smooth-scroll libraries: only when they materially improve the experience and can be integrated accessibly.
- Three.js/WebGL: only for meaningful 3D or real-time visual experiences.

Do not combine multiple libraries that solve the same problem without a clear reason. See `TECHNOLOGY_AND_LIBRARY_SELECTION.md`.

## Practical guidance
- Keep common micro-interactions quick and unobtrusive.
- Use easing that matches intent; avoid mechanical linear movement for natural UI transitions.
- Avoid long intro sequences that delay access to content.
- Avoid scroll hijacking and forced scroll positions.
- Avoid animating large areas continuously.
- Avoid animating layout properties when transforms/opacity can achieve the result.
- Ensure content remains understandable if animation is disabled.
- Clean up observers, timelines, listeners, and animation instances on unmount or route changes.
- Prevent hydration mismatch and layout shifts in server-rendered applications.

## Reduced motion
When reduced motion is requested:
- remove non-essential parallax, large transforms, and continuous movement;
- replace spatial transitions with simple opacity or immediate state changes where appropriate;
- preserve all functionality and feedback;
- do not hide content until an animation completes.

## Verification
Test motion on representative devices and viewport sizes. Check frame stability, scroll behaviour, reduced-motion settings, and interaction interruption. Report what was actually tested.
