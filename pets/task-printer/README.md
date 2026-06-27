# Task Printer

Task Printer is a Codex digital pet based on a frantic high-throughput printer mascot: tiny direction goes in, many finished outputs come out, and the machine keeps visibly working.

Package contents:

- `pet.json` - Codex pet manifest.
- `spritesheet.webp` - Final 1536x1872 RGBA atlas using 192x208 cells.
- `qa/contact-sheet.png` - Visual row-by-row review sheet.
- `qa/validation.json` - Atlas validation output.
- `qa/review.json` - Extracted-frame inspection output.

Generation notes:

- `running-left` was derived by mirroring `running-right`.
- The `failed` row needed two targeted repairs to avoid slot slicing artifacts.
- `idle`, `running-right`, `waving`, `jumping`, `failed`, `waiting`, `running`, and `review` were generated as grounded row strips.
- Validation passed with no errors or warnings.
