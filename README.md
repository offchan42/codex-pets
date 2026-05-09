# Codex Pets

Personal Codex pet packages and their QA artifacts.

This repository is the source-of-truth archive for custom pets. Installed runtime copies live under:

```text
C:\Users\ASUS\.codex\pets\
```

To install or refresh a pet, copy its package folder from this repository into the Codex pets directory. For example:

```powershell
Copy-Item -Recurse -Force .\pets\caliper C:\Users\ASUS\.codex\pets\caliper
```

Each pet package should include:

- `pet.json` - Codex pet manifest.
- `spritesheet.webp` - Final transparent-capable sprite atlas.
- `README.md` - Pet-specific notes.
- `qa/contact-sheet.png` - Visual row review.
- `qa/validation.json` - Atlas validation output.
- `qa/review.json` - Extracted-frame inspection output.

Generated intermediate runs should stay out of this repo unless they are needed for a specific audit.
