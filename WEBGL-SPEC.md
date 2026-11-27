# WEBGL-SPEC.md - Phase 2 WebGL Steering Specification

- **Recommended Lane:** Lane B (Data / Particle Intelligence). Communicates deterministic validator node flows and directional settlement arcs toward the hero CTA. Lane D is rejected to protect conversion and mobile frame budgets.
- **Palette:** Canvas `oklch(0.13 0.010 250)`, core nodes `oklch(0.95 0.006 250)`, orbital ring and arcs `oklch(0.76 0.145 168)`. Zero violet/lavender.
- **Stack & Context Cap:** Single Three.js `WebGLRenderer` (max 1 live WebGL context on landing), paused offscreen via `IntersectionObserver` and on hidden tab.
- **Non-WebGL Fallback First:** Crisp inline SVG orbital lattice inside `position: relative; overflow: hidden` (`aria-hidden="true"`) with `oklab` atmospheric vignette in `index.html`, readable in <3 seconds without JS.
- **Four Gates:** Message (<3s clarity, AA/AAA contrast), Performance (`Math.min(devicePixelRatio, 1.5)`, 60% fewer particles <768px), Accessibility (`prefers-reduced-motion` static frame + pause toggle), Reliability (`failIfMajorPerformanceCaveat: true`, `webglcontextlost` fallback, geometry/material disposal).
