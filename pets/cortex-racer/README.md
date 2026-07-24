# Cortex Racer

A racecar-brain pet optimized for velocity and competitive cognition.

Package contents:

- `pet.json` - Codex pet manifest.
- `spritesheet.webp` - Final v2 1536x2288 RGBA atlas using 192x208 cells.
- `qa/contact-sheet.png` - Visual review sheet for all 11 rows.
- `qa/look-directions.png` - Neutral frame plus all 16 labeled look directions.
- `qa/validation.json` - Atlas validation output.
- `qa/review.json` - Extracted-frame inspection output.
- `qa/direction-semantics.json` - Labeled semantic verdicts for every look direction.
- `qa/direction-blind-validation.json` - Three-reviewer blind direction consensus validation.
- `qa/look-continuity.json` - Adjacent look-direction continuity measurements.
- `qa/chroma-despill.json` - Deterministic edge-local chroma cleanup report.
- `qa/final-visual-qa.json` - Independent final visual review result.
- `qa/run-summary.json` - Finalization summary with source run paths.

Generation notes:

- `running-left` was derived by mirroring `running-right` after visual approval.
- `idle`, `running-right`, `waving`, `jumping`, `failed`, `waiting`, `running`, and `review` were generated as grounded row strips.
- Rows 0-8 are preserved from the validated v1 pet.
- Rows 9-10 add 16 clockwise look directions with hard cardinal semantics, blind review, labeled-loop review, and continuity QA.
- `spriteVersionNumber: 2` enables the extended atlas contract.
- Strict v2 validation and deterministic chroma cleanup passed with no errors or warnings.
