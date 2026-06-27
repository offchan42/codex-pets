# Runtime Foreman

Runtime Foreman is a Codex digital pet based on a frantic runtime operator mascot: many controls, levers, and processes move in parallel while the user supplies direction, taste, and judgment.

Package contents:

- `pet.json` - Codex pet manifest.
- `spritesheet.webp` - Final 1536x1872 RGBA atlas using 192x208 cells.
- `qa/contact-sheet.png` - Visual row-by-row review sheet.
- `qa/validation.json` - Atlas validation output.
- `qa/review.json` - Extracted-frame inspection output.

Generation notes:

- `running-left` was derived by mirroring the repaired `running-right` row.
- The `running-right` row needed one targeted repair before final atlas assembly.
- `idle`, `running-right`, `waving`, `jumping`, `failed`, `waiting`, `running`, and `review` were generated as grounded row strips.
- Validation passed with no errors or warnings.
