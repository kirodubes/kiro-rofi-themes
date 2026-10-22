# Changelog

## 2026.10.22

### What Changed
- **New theme `Kiro-Grid`**: a centered app grid, 5 big icons with their names per row on a dark glass card, with
  a search bar on top. First used by the Kiro wayfire edition (its waybar apps icon). Works on X11 and Wayland
  (rofi 2.0).

### Technical Details
- Based on adi1090x/rofi launcher type-3 style-1 (GPL-3.0, credited in the file header). Made self-contained:
  upstream imports colours and fonts from `~/.config/rofi/`, which Kiro doesn't ship, so the One Dark palette and
  the font (JetBrainsMono Nerd Font) are inlined. The card background is 85% opaque instead of 10%, so it stays
  readable when the compositor doesn't blur behind it.
- `rofi -dump-theme` parses it cleanly.

### Files Modified
- `usr/share/rofi/themes/Kiro-Grid.rasi` (new)

## 2026.05.21

### What Changed
- Initial markdown scaffold added per the ecosystem MD-scaffold rule ([HQ/CLAUDE.md](/home/erik/Insync/Kiro/Kiro-HQ/CLAUDE.md#required-markdown-scaffold-every-repo)).
- Stubs created for `CHANGELOG.md`, `CLAUDE.md`, `IDEAS.md`, `TODO.md` (whichever were missing).
- README rewritten with real install/usage content (replaced earlier one-line stub) where applicable.

### Files Modified
- CHANGELOG.md (created)
- CLAUDE.md (created where missing)
- IDEAS.md (created where missing)
- TODO.md (created where missing)
- README.md (rewritten where it was a stub)
