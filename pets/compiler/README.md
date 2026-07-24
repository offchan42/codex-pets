# Compiler

A wiry compiler creature converting chaos into builds while sprinting.

Package contents:

- `pet.json` - Codex pet manifest.
- `spritesheet.webp` - Final sprite-version-2 1536x2288 RGBA atlas using 192x208 cells.
- `qa/contact-sheet.png` - Visual review of the nine preserved standard animation rows.
- `qa/contact-sheet-extended.png` - Visual review of all eleven atlas rows.
- `qa/look-directions.png` - Focused 16-direction look-cycle review sheet.
- `qa/direction-blind-pairs.png` - Label-free cardinal-direction evidence used by independent reviewers.
- `qa/validation.json` - Final structural, alpha, and chroma validation output.
- `qa/direction-semantics.json` - Per-direction semantic review for the complete look cycle.
- `qa/direction-blind-validation.json` - Aggregated blind cardinal-review result.
- `qa/look-continuity.json` - Adjacent-angle continuity measurements, including loop closure.
- `qa/final-visual-qa.json` - Independent final visual-review verdict.
- `qa/review.json` - Preserved standard-row extracted-frame inspection output.
- `qa/run-summary.json` - Finalization summary with source run paths.

Generation notes:

- The original nine standard animation rows retain their version-1 source content and timing; version-2 chroma despill removes legacy magenta-key residue from those rows.
- Version 2 adds two look rows encoding 16 clockwise directions: 000, 022.5, 045, 067.5, 090, 112.5, 135, 157.5, 180, 202.5, 225, 247.5, 270, 292.5, 315, and 337.5 degrees.
- Three fresh blind reviews unanimously passed both hard cardinal pairs: left/right and down/up.
- `running-left` was derived by mirroring `running-right` after visual approval.
- `idle`, `running-right`, `waving`, `jumping`, `failed`, `waiting`, `running`, and `review` were generated as grounded row strips.
- Final version-2 validation passed with no errors or warnings after chroma despill.
