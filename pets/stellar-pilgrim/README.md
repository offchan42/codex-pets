# Stellar Pilgrim

Stellar Pilgrim is a hooded rationalist Codex digital pet based on the top-right male pilgrim concept: a charcoal robe with gold trim, a brass lantern with a blue-white star flame, blue-and-gold probability beads, a small satchel, and a careful curious expression.

Package contents:

- `pet.json` - Codex pet manifest.
- `spritesheet.webp` - Final 1536x1872 RGBA atlas using 192x208 cells.
- `qa/contact-sheet.png` - Visual row-by-row review sheet.
- `qa/validation.json` - Atlas validation output.
- `qa/review.json` - Extracted-frame inspection output.
- `source-images/` - Selected generated row strips and provenance manifests.

Generation notes:

- `running-left` was generated separately instead of mirrored because the lantern, beads, and satchel are handed identity props.
- `idle`, `running-right`, `running-left`, `waving`, `jumping`, `failed`, `waiting`, `running`, and `review` were generated as grounded row strips from the canonical base reference.
- Validation passed with no errors or warnings.
