# Wheelboss

A caffeinated hamster operator powering a tiny deadline command station.

Package contents:

- `pet.json` - Codex pet manifest.
- `spritesheet.webp` - Final v2 1536x2288 RGBA atlas using 192x208 cells.
- `qa/contact-sheet.png` - Visual row-by-row review sheet for all 11 rows.
- `qa/look-directions.png` - Neutral plus all 16 labeled gaze directions.
- `qa/direction-semantics.json` - Per-direction labeled semantic review.
- `qa/direction-blind-validation.json` - Consensus blind-axis validation.
- `qa/look-continuity.json` - Adjacent-direction continuity measurements.
- `qa/chroma-despill.json` - Final edge-local chroma cleanup report.
- `qa/validation.json` - Required-v2 atlas validation output.
- `qa/review.json` - Extracted-frame inspection output.
- `qa/run-summary.json` - Finalization summary with source run paths.

Generation notes:

- `running-left` was derived by mirroring `running-right` after visual approval.
- `idle`, `running-right`, `waving`, `jumping`, `failed`, `waiting`, `running`, and `review` were generated as grounded row strips.
- The nine original animation rows were preserved exactly from the approved v1 atlas.
- Rows 9-10 add 16 clockwise look directions from `000` up through `337.5` up-left.
- Required-v2 validation and deterministic chroma cleanup passed with no errors or warnings.
