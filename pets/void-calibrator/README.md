# Void Calibrator

Void Calibrator is a serious contemplative Codex digital pet based on the concept sheet's dark seated calibrator totem: a charcoal rounded form, closed eyes, a deep teal central eye-dial, muted gold calibration ticks, and a chest calibration ring.

Package contents:

- `pet.json` - Codex pet manifest.
- `spritesheet.webp` - Final 1536x1872 RGBA atlas using 192x208 cells.
- `qa/contact-sheet.png` - Visual row-by-row review sheet.
- `qa/validation.json` - Atlas validation output.
- `qa/review.json` - Extracted-frame inspection output.
- `qa/videos/` - Per-row animation preview videos.
- `source-images/` - Selected original generated images and provenance manifests.

Generation notes:

- `running-left` was derived by mirroring `running-right` because the design is symmetric and has no text, logos, handed props, or side-specific accessories.
- `idle`, `running-right`, `waving`, `jumping`, `failed`, `waiting`, `running`, and `review` were generated as grounded row strips from the canonical base reference.
- Validation passed with no errors or warnings.
