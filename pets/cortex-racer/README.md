# Cortex Racer

A racecar-brain pet optimized for velocity and competitive cognition.

Package contents:

- `pet.json` - Codex pet manifest.
- `spritesheet.webp` - Final 1536x1872 RGBA atlas using 192x208 cells.
- `qa/contact-sheet.png` - Visual row-by-row review sheet.
- `qa/validation.json` - Atlas validation output.
- `qa/review.json` - Extracted-frame inspection output.
- `qa/run-summary.json` - Finalization summary with source run paths.

Generation notes:

- `running-left` was derived by mirroring `running-right` after visual approval.
- `idle`, `running-right`, `waving`, `jumping`, `failed`, `waiting`, `running`, and `review` were generated as grounded row strips.
- Validation passed with no errors or warnings.
