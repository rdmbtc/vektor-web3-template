# DESIGN.md - Phase 3 Locked Visual System

- **OKLCH Neutral Ramp (H=250):** Canvas `oklch(0.13 0.010 250)`, Surface `oklch(0.17 0.012 250)`, Elevated `oklch(0.21 0.014 250)`, Border `oklch(0.29 0.015 250)`, Primary Text `oklch(0.95 0.006 250)` (>15:1), Muted Text `oklch(0.72 0.012 250)` (>6.5:1).
- **Primary Accent Ramp (Signal Emerald, H=168, zero violet):** Solid `oklch(0.76 0.145 168)` with dark ink `oklch(0.14 0.015 168)` (>10:1).
- **Typography (`typeset`):** `Space Grotesk` (display), `Inter` (body/UI, 16px floor, 45-68ch measure), `JetBrains Mono` (`tabular-nums` for all metrics), `text-wrap: balance` on headings and `pretty` on body.
- **Geometry (`design-taste-frontend`):** Sharp infra radii (`4px / 6px / 8px`), 1240px max container with equal edges, 1 button pair (44px min height), 1 card family. Token gate: PASS.
