# Null Lantern

Null Lantern is a quiet contemplative Codex digital pet based on the concept sheet's shrine-like lantern totem: a dark charcoal hood, ring handle, bone face inset, closed eyes, muted gold markings, and a small warm flame window.

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
- `idle`, `running-right`, `waving`, `jumping`, `failed`, `waiting`, `running`, and `review` were generated as grounded row strips.
- Validation passed with no errors or warnings.
