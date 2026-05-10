# Codex Pets

Personal Codex pet packages and their QA artifacts.

This repository is the source-of-truth archive for custom pets. Installed runtime copies live under the Codex home directory:

```text
<Codex home>/pets/
```

By default, Codex home is usually `%USERPROFILE%\.codex` on Windows and `$HOME/.codex` on macOS/Linux. If your environment sets `CODEX_HOME`, use that value instead.

To install or refresh a pet, copy its package folder from this repository into the Codex pets directory.

Windows PowerShell:

```powershell
$codexHome = if ($env:CODEX_HOME) { $env:CODEX_HOME } else { Join-Path $env:USERPROFILE ".codex" }
Copy-Item -Recurse -Force .\pets\caliper (Join-Path $codexHome "pets\caliper")
```

macOS/Linux shell:

```sh
codex_home="${CODEX_HOME:-$HOME/.codex}"
mkdir -p "$codex_home/pets"
cp -R ./pets/caliper "$codex_home/pets/caliper"
```

Each pet package should include:

- `pet.json` - Codex pet manifest.
- `spritesheet.webp` - Final transparent-capable sprite atlas.
- `README.md` - Pet-specific notes.
- `qa/contact-sheet.png` - Visual row review.
- `qa/validation.json` - Atlas validation output.
- `qa/review.json` - Extracted-frame inspection output.

Generated intermediate runs should stay out of this repo unless they are needed for a specific audit.
