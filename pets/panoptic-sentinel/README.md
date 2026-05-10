# Panoptic Sentinel

Panoptic Sentinel is a calm minimalist avian scout pet: a compact owl/falcon-style companion with matte ceramic and carbon-fiber forms, focused amber eyes, and a precise low-distraction posture.

## Build Notes

- Canonical base and row strips were generated with the hatch-pet workflow.
- `running-left` was derived by mirroring `running-right`; the design has no readable text, logo, held prop, or side-specific semantic marking that would become wrong when flipped.
- Row generation used subagents for `idle`, `running-right`, `waving`, `jumping`, `failed`, `waiting`, `running`, and `review`.

## QA

- Atlas validation: `qa/validation.json`
- Frame inspection: `qa/review.json`
- Visual contact sheet: `qa/contact-sheet.png`

Both validation files reported no errors or warnings for this build.
