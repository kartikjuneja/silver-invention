# Messy Money brand kit

Locked overlapping ribbon **M** plus lowercase **messy money**.

Every file uses that same picture. The logo files have no plate. Icons, banners, and boards are that logo placed on a ground.

Not a two-stroke redraw.

Wordmark is **messy money** only. On a light ground it is ink `#121926`. On ink banners it is white.

In-app Flutter ships this kit from assets/brand/ (mark.png, lockup.png, app_icon_1024.png) and platform icons from app-icon-1024.png. The signed-out landing uses assets/public/app-icon.png.

## Files

| File | Role |
|---|---|
| `mark.png` / `mark.svg` | Logo only. Transparent |
| `lockup.png` / `lockup.svg` | Mark + **messy money**. Transparent |
| `lockup-wide.png` / `lockup-wide.svg` | Same lockup, larger |
| `lockup-stacked.png` / `lockup-stacked.svg` | Mark above the wordmark. Transparent |
| `app-icon.png` | Same mark on a white squircle. Corners outside the tile are transparent |
| `app-icon-1024.png` … `app-icon-32.png` | That icon at 1024 / 512 / 256 / 128 / 32 |
| `app-icon.svg` | Same pixels as `app-icon.png` |
| `app-icon-studio.png` | The squircle on grey |
| `connector-icon.png` | Same icon at 256×256 |
| `banner-frost.png` | 1600×900 frost, horizontal lockup |
| `banner-ink.png` | 1600×900 ink, horizontal lockup, white type |
| `banner-og.png` | 1280×720 frost |
| `banner-social-ink.png` | 1280×720 ink, white type |
| `banner-stacked-frost.png` | Stacked lockup on frost |
| `banner-stacked-ink.png` | Stacked lockup on ink, white type |
| `identity-sheet.png` | Icon, mark, lockup, and the size row |
| `brand-board.png` | Those pieces plus the banners |

## Which file to use

| Surface | File |
|---|---|
| Mark on frost, glass, or any ground | **`mark.png`** |
| Header on a light ground | **`lockup.png`** or `lockup-wide.png` |
| Centered lockup on a light ground | `lockup-stacked.png` |
| Android / iOS / web launcher | `app-icon-1024.png` |
| Favicon | `app-icon-32.png` (or `app-icon-128.png`) |
| ChatGPT Apps / MCP connector icon | **`connector-icon.png`** |
| Site / OG / docs banner | `banner-frost.png` or `banner-og.png` |
| Dark / social cover | `banner-ink.png` or `banner-social-ink.png` |
| Overview | `identity-sheet.png` or `brand-board.png` |

Do **not** live-upload the connector from this directory. File-on-disk only.

## Colors

Iris `#6B5AED` → cyan `#33D1FF` → earned `#22C55E`. Wordmark ink `#121926`. Frost `#EEF2FF` → `#F5F0FF` → `#E8F6FF`. Banner ink `#121926`. Squircle fill white.

Wordmark: Manrope ExtraBold, lowercase, no tracking tricks.

## Do not use

- A white rectangle behind `mark.png` or the lockups
- A second drawing of the M
- White **M** on a gradient tile
- Black stamp / 1-color homework icons as the product mark

## Historical / unused

`icon-lg.png`, `icon-md.png`, and `icon-sm.png` were odd crops of the old sheet. The size row is `app-icon-128.png`, `app-icon-32.png`, and the other `app-icon-*` files.

Previous files in this folder were the **Mowgli squircle** (white Manrope **M** on a gradient rounded square) for SPEC-M8-41. Git history keeps those. Gemini blobs remain unused:

`docs/design/Mowgli generated files/Gemini images/`
