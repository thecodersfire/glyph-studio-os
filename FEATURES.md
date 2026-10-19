# Built-in features for glyph-studio-os

Purpose: graphic design

1. **prepare a creative project** — run glyph-studio-os-workspace. It creates ~/Documents/glyph-studio-os-workspace/ with Briefs, Working Files, Exports folders.
2. **plan a production session** — run glyph-studio-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/glyph-studio-os-session-plans/.
3. **check project and export readiness** — run glyph-studio-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/glyph-studio-os-workspace features/glyph-studio-os-plan features/glyph-studio-os-check "$HOME/.local/bin/"
