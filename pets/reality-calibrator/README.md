# Reality Calibrator

Reality Calibrator is a feminine rationalist Codex digital pet based on the bottom-left female calibrator concept: long dark hair, ornate white-and-teal robes, a forehead eye-dial, close teal calibration arcs, and a black star-filled reality shard held at the chest.

Package contents:

- `pet.json` - Codex pet manifest.
- `spritesheet.webp` - Final 1536x1872 RGBA atlas using 192x208 cells.
- `qa/contact-sheet.png` - Visual row-by-row review sheet.
- `qa/validation.json` - Atlas validation output.
- `qa/review.json` - Extracted-frame inspection output.
- `source-images/` - Selected generated row strips and provenance manifests.

Generation notes:

- `running-left` was derived by mirroring `running-right` because the design has a centered crystal, centered forehead eye-dial, no text or logos, no side-specific accessories, and no handed prop semantics.
- `idle`, `running-right`, `waving`, `jumping`, `failed`, `waiting`, `running`, and `review` were generated as grounded row strips from the canonical base reference.
- `failed` was repaired once for chroma-key-adjacent sprite pixels.
- `jumping` was repaired once after visual QA found identity drift from the approved base.
- Validation passed with no errors or warnings.
