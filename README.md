# 🌿 MEGHA Bio-Wellness – Brand & Marketing Assets Repo
Elegant • Authentic • Evidence-Based  
*(Last updated 2025-07-26 | Maintainer: **Brand Ops Lead**)*

---

## 1. Purpose
This repository is the **single source of truth** for all creative assets, copy blocks, and code snippets powering Megha Bio-Wellness marketing.  
Designers, developers, and assistants use it to:

* Keep every file on-brand (colours, fonts, voice, legal footer).
* Track version history and approve changes via Pull Requests.
* Sync assets with downstream tools (Figma, Sora, CMS, Print house).

---

## 2. Directory Map

| Path | What lives here | Notes |
|------|-----------------|-------|
| `01_Logos/` | Primary + alt marks (`.svg`, `.png`) | **Do not** edit originals – add new variants in sub-folder |
| `02_Palette-Fonts/` | HEX swatches (`.ase`), font OTFs, mini CSS file | Fonts licensed Apache 2.0 |
| `03_Product_Images/` | Tiered powder shots, extract renders | Named `YYYYMMDD_v1_<Asset>_<Tier>.png` |
| `04_Process_Illustrations/` | Flowcharts, AI overlay SVGs | Editable `.fig` + export `.png` |
| `05_Video_B-roll/` | Approved MP4 clips (≤30 s) | 4 K originals in `/raw/` |
| `06_Copy_Library/` | `copy_blocks.md`, disclaimers, alt-text JSON | Markdown for easy diff |
| `07_Templates/` | InDesign grids, PPT masters, email headers | Use these for all new docs |
| `08_Archive_YYYY-MM/` | Retired or superseded assets | Automated monthly move via CI |

> **Tip:** Clone with `--depth=1` if you only need latest.

---

## 3. Quick-Start (New Contributor)

```bash
# 1 — Fork + clone
git clone https://github.com/Megha-BioWellness/brand-assets.git
cd brand-assets

# 2 — Create feature branch
git checkout -b feat/add-pro-tier-bottle-img

# 3 — Add or edit files in correct folder
git add 03_Product_Images/20250727_v1_Bottle_Pro.png
git commit -m "feat: add Professional tier bottle hero shot"

# 4 — Push & open Pull Request
git push origin feat/add-pro-tier-bottle-img
