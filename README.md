# AoE2 DE Build Order Companion

A glanceable Age of Empires II: Definitive Edition build-order companion for a
second screen (tablet/phone) while playing. Runs entirely in the browser - no
build step, no server code.

## Use it

**Hosted:** open `<your-username>.github.io/aoe2-build-orders/` (GitHub Pages URL).

**Self-hosted on LAN** (note: the first load pulls React/Tailwind from CDNs, so
internet is required):

1. Download this repository (Code -> Download ZIP) and extract it.
2. Run `python -m http.server 8000` inside the extracted folder.
3. Open `http://<your-pc>:8000/` on the tablet.

## Features

- 4 build orders (Scouts 20, Archers 20, M@A 20, Fast Castle 26+2) with step-by-step
  context row, board with villager assignment replay, and per-minute gather rates.
- Production calculator: villagers needed for constant unit production, with
  per-age gather rates (all eco techs of the age assumed researched), per-civ eco
  bonuses, per-civ unit cost/train variants, and team bonuses derived from your
  civ + allies.
- Civ picker with crests; Me/allies limited to base-game civs, enemies can be any
  civ (AI may pick DLC civs).

## Data provenance

- Gather rates, civ bonuses and unit stats extracted from Survivalist's
  aoe2-de-tools (villagers-required), verified against game patch 185872.
- Civilization crest icons from the open-source aoe2techtree project
  (Siege Engineers). Game icons from the Age of Empires Wiki.

## Legal

Age of Empires II © Microsoft Corporation. This tool uses game assets under
Microsoft's Game Content Usage Rules. It is not affiliated with or endorsed by
Microsoft. Non-commercial fan project.
