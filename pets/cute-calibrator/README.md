# Cute Calibrator

Cute Calibrator is a rationalist measurement companion based on the Calibrator character from the provided concept sheet.

The canonical base keeps the original Calibrator pose and expression, horizontally mirrored left-to-right rather than turned into a side-facing pose. The design uses the sheet's cream, charcoal, teal, brass, and moon-gray palette with twin gauge ears, a forehead needle, and calibration marks on the tunic.

Generation notes:

- Base identity: original sheet Calibrator, mirrored left-to-right.
- Theme: calibrating beliefs against reality through measurement and evidence.
- `running-left` was generated directly instead of mirrored from `running-right` so the orange/teal gauge sides stayed consistent with the canonical identity.
- Row image generation used subagents for `idle`, `running-right`, `running-left`, `waving`, `jumping`, `failed`, `waiting`, `running`, and `review`.

Validation:

- Final atlas: `1536x1872` RGBA WebP.
- `qa/review.json`: no errors or warnings.
- `qa/validation.json`: no errors or warnings.
