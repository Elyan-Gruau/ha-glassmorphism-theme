# Glassmorphism

An elegant frosted-glass theme for Home Assistant.

![HACS: custom repository](https://img.shields.io/badge/HACS-custom-41BDF5?style=flat-square&logo=homeassistantcommunitystore&logoColor=white)
![License: MIT](https://img.shields.io/badge/license-MIT-black?style=flat-square)

## Install

### HACS

1. HACS → ⋮ → **Custom repositories** → add this repo URL, category `Theme`.
2. Install **Glassmorphism** and reload themes.
3. **Profile → Theme** → `glassmorphism`.

### Manual

1. Copy `themes/glassmorphism.yaml` into `/config/themes/`.
2. In `configuration.yaml`:
   ```yaml
   frontend:
     themes: !include_dir_merge_named themes
   ```
3. Reload themes and select `glassmorphism`.

## Requirements

- [card-mod](https://github.com/thomasloven/lovelace-card-mod) — optional, for the frosted header, media seek bar and logbook header.

## License

[MIT](LICENSE)
