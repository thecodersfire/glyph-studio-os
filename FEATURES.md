# Built-in features for glyph-studio-os

Purpose: graphic design

1. **prepare a creative project** — run glyph-studio-os-workspace. It creates ~/Documents/glyph-studio-os-workspace/ with Briefs, Working Files, Exports folders.
2. **plan a production session** — run glyph-studio-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/glyph-studio-os-session-plans/.
3. **check project and export readiness** — run glyph-studio-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/glyph-studio-os-workspace features/glyph-studio-os-plan features/glyph-studio-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for graphic design:

1. **GIMP** — org.gimp.GIMP
2. **Kdenlive** — org.kde.kdenlive
3. **Blender** — org.blender.Blender

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for graphic design:

1. **OBS Studio** — record or stream sessions (com.obsproject.Studio)
2. **Audacity** — edit audio recordings (org.audacityteam.Audacity)
3. **Ardour** — record and mix multitrack audio (org.ardour.Ardour)
4. **darktable** — develop RAW photos (org.darktable.Darktable)
5. **Scribus** — lay out print-ready publications (org.scribus.Scribus)
6. **VLC** — review media files (org.videolan.VLC)
7. **Mixxx** — prepare and mix DJ sets (org.mixxx.Mixxx)
8. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
9. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
10. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.
