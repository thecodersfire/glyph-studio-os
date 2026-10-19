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

## Fifteen more purpose-specific preinstalled applications

These applications add tools suited to this setup focus. They are installed from Flathub by the setup scripts.

1. **Pixelorama** (com.orama_interactive.Pixelorama) — draw pixel-art sprites and frame-based animations.
2. **Synfig Studio** (org.synfig.SynfigStudio) — create vector-based 2D animations.
3. **OpenToonz** (io.github.OpenToonz) — produce hand-drawn and cutout 2D animation.
4. **RawTherapee** (com.rawtherapee.RawTherapee) — develop RAW photo files with tone and color controls.
5. **digiKam** (org.kde.digikam) — catalog, tag, and batch-process large photo collections.
6. **Shotwell** (org.gnome.Shotwell) — import, sort, and make quick edits to photo libraries.
7. **MuseScore Studio** (org.musescore.MuseScore) — write, play back, and print sheet music.
8. **LMMS** (io.lmms.LMMS) — compose electronic music and loops.
9. **Hydrogen** (org.hydrogenmusic.Hydrogen) — program drum patterns and percussion tracks.
10. **Guitarix** (org.guitarix.Guitarix) — shape guitar tone with amp and effects processing.
11. **JabRef** (org.jabref.jabref) — organize BibTeX references and research citations.
12. **Thunderbird** (org.mozilla.Thunderbird) — manage email and communication accounts.
13. **Disk Usage Analyzer** (org.gnome.baobab) — find large files and manage storage.
14. **GNOME Logs** (org.gnome.Logs) — inspect logs during troubleshooting.
15. **Flatseal** (com.github.tchx84.Flatseal) — review Flatpak app permissions.

Emulator frontends do not include game ROMs or copyrighted game files; supply only files you are legally allowed to use.

## Fifteen further purpose-specific preinstalled applications

This second batch adds another set of apps selected for this setup’s purpose. They are installed from Flathub by the setup scripts.

1. **KolourPaint** (org.kde.kolourpaint) — make quick raster sketches, labels, and simple image edits.
2. **Gwenview** (org.kde.gwenview) — review image sets and make quick crop, resize, and annotation edits.
3. **Kamoso** (org.kde.kamoso) — capture webcam photos and short video clips.
4. **Rnote** (com.github.flxzt.rnote) — sketch diagrams, write by hand, and annotate pictures or documents.
5. **Okular** (org.kde.okular) — read, bookmark, and annotate technical drawings, reading lists, and reference PDFs.
6. **Dolphin** (org.kde.dolphin) — organize project assets and inspect folders.
7. **Ark** (org.kde.ark) — open and create common project archive files.
8. **Filelight** (org.kde.filelight) — find large folders and reclaim disk space.
9. **Warehouse** (io.github.flattool.Warehouse) — review installed Flatpaks, manage versions, and clean app data.
10. **Kate** (org.kde.kate) — edit configuration, code, notes, and structured project files.
11. **Meld** (org.gnome.meld) — compare and merge source files, folders, and Git changes.
12. **Konsole** (org.kde.konsole) — run shell commands and inspect development or system tasks.
13. **KCalc** (org.kde.kcalc) — run scientific and unit calculations for coursework or technical work.
14. **Elisa** (org.kde.elisa) — organize and play local music libraries.
15. **Kwave** (org.kde.kwave) — record and edit audio waveforms with basic filters and analysis.

Game frontends do not include proprietary game data; add only games or files you are allowed to use.

## Blender included in every setup

Blender (org.blender.Blender) is included in every setup for 3D modeling, animation, rendering, and video editing. Installers fetch it from Flathub; Blender’s own license and terms apply.

## Fifteen additional purpose-specific applications

The setup adds these Flathub applications for graphic design. Applications are fetched from Flathub by the setup script; each app keeps its own licensing and terms.

1. **Shotcut** (org.shotcut.Shotcut) — Edit multitrack video with filters, transitions, and titles.
2. **HandBrake** (fr.handbrake.ghb) — Transcode video files to common formats and presets.
3. **OpenShot** (org.openshot.OpenShot) — Assemble video clips on a multitrack timeline.
4. **Glaxnimate** (org.kde.glaxnimate) — Create vector animations, motion graphics, and animated SVG assets.
5. **Subtitle Composer** (org.kde.subtitlecomposer) — Create and synchronize captions for video projects.
6. **KPhotoAlbum** (org.kde.kphotoalbum) — Tag and organize large photo collections.
7. **Kid3** (org.kde.kid3) — Edit audio tags and album metadata in batches.
8. **Loupe** (org.gnome.Loupe) — View images and make simple crop, rotate, or flip edits.
9. **Kasts** (org.kde.kasts) — Subscribe to podcasts and manage playback queues.
10. **Jellyfin Desktop** (org.jellyfin.JellyfinDesktop) — Browse and play personal media from a configured Jellyfin server.
11. **EasyEffects** (com.github.wwmm.easyeffects) — Adjust audio input and output with equalizers and effects.
12. **QGIS** (org.qgis.qgis) — Create and analyze geographic information system projects.
13. **GNOME Maps** (org.gnome.Maps) — Look up places and routes using online map data.
14. **Marble** (org.kde.marble) — Explore maps and a virtual globe for route and place context.
15. **KGeography** (org.kde.kgeography) — Practice place and map recognition.
