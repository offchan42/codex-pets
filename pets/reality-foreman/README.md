# Reality Foreman

Reality Foreman is a Codex digital pet based on a frantic construction foreman mascot: it treats reality as bendable tiles and drives disciplined execution until desire becomes output.

Package contents:

- `pet.json` - Codex pet manifest.
- `spritesheet.webp` - Final 1536x1872 RGBA atlas using 192x208 cells.
- `qa/contact-sheet.png` - Visual row-by-row review sheet.
- `qa/validation.json` - Atlas validation output.
- `qa/review.json` - Extracted-frame inspection output.

Generation notes:

- `running-left` was generated separately because the asymmetric tool rig and tile pose did not mirror cleanly.
- `idle`, `running-right`, `running-left`, `waving`, `jumping`, `failed`, `waiting`, `running`, and `review` were generated as grounded row strips.
- Validation passed with no errors or warnings.
