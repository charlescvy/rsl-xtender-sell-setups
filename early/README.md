# RSL-Xtender Sell-Setup "Conservative Early"

`early-v1.json` — August 2026 — 🧪 **field-testing in progress** (the author is running it on an early account; feedback welcome via issues)

[🇫🇷 Version française](README.fr.md) · 📄 [PDF version](early-v1_EN.pdf)

## Who is it for?

**Early** accounts: you farm dungeons between stages **~10 and 15** (the pivot is **Dragon 13** — the first stage where 6★ gear drops). Clan Boss Easy/Normal/Hard. If you can **auto Dragon 16+**, switch to the [Mid profile](../mid/).

## Why a dedicated early profile?

An early player **wears** what a mid player would sell: 4★ rares, "weak" sets (Life, Offense, Defense), average-stat pieces. Using a midgame file early means selling the gear your champions need. This profile is therefore **very conservative**: it only sells what has objectively no use, even for a beginner.

## The rules

| Rule | Detail |
|---|---|
| Common / Uncommon | always sold |
| Rank ≤ 3★ | sold (≤ 2★ for premium/event sets) |
| 4★ rare/epic with NO good substat at all | sold — a single stat among SPD, C.RATE, C.DMG, ACC, RES, HP%, ATK%, DEF% saves the piece |
| 5★ rare with no good substat | sold |
| Chest/gauntlets/boots with a flat main stat | rare ≤ 5★ sold; epic sold only if it also has no good substat |
| **5★+ epics and legendaries** | **never auto-sold** |
| First 6★ drops (Dragon 13+) | never auto-sold (except common/uncommon) |

## Special protections

- **Speed and Lifesteal: no quality rules at all** — early on, the set bonus is worth more than the stats (your campaign farmer's Lifesteal set stays as-is until mid-game). Only common/uncommon and ≤ 3★ are sold.
- **ACC saves everything**: any piece with Accuracy (main or substat) passes the filters — it's THE stat you can't find early and your Clan Boss debuffers live on it.
- **C.DMG% amulets: never sold** (the only accessory slot that can roll it).
- Already-upgraded pieces (level > 4) are protected — compatible with the "level to +4, check the substat, decide" method.
- Accessories: epics/legendaries never sold, 3★ rares kept (at Spider < 13 that's what you get), only ≤ 2★ and 4★ rares with no good stat are sold.

## When to switch to the Mid profile

When you can **auto Dragon 16+** (and Brutal CB takes 2-4 keys): your drops become mostly 5-6★ and this profile then keeps too much. → [Mid profile](../mid/)

## Import

**Sell** tab → import icon (top right) → select the JSON. ⚠️ This replaces your current configuration — export it first. Shared as-is, use at your own risk — your account may differ.

## Sources

- HellHades / RSL Helper — *Beginner* sample sell-file (SellfileCreator, RSL Helper V6): [rsl-helper.de](https://rsl-helper.de/?lang=en)
- HellHades — Defining Your Stage of Progress: [hellhades.com/defining-your-stage-of-raid-shadow-legends-and-progress-priorities](https://hellhades.com/defining-your-stage-of-raid-shadow-legends-and-progress-priorities/)
- HellHades — The Best Gear for New Players: [hellhades.com/the-best-gear-for-new-players-in-raid-shadow-legends](https://hellhades.com/the-best-gear-for-new-players-in-raid-shadow-legends/)
- InTeleria — Beginner Guide 2026: [inteleria.com/raid-shadow-legends-beginner-guide-2026-fast-start-zero-regrets](https://www.inteleria.com/raid-shadow-legends-beginner-guide-2026-fast-start-zero-regrets/)
- InTeleria — Dungeon Drop Rates (ranks per stage): [inteleria.com/raid-dungeon-drop-rates](https://www.inteleria.com/raid-dungeon-drop-rates/)
- Ayumilove — Artifact & Accessory Guide: [ayumilove.net/raid-shadow-legends-artifact-and-accessory-guide](https://ayumilove.net/raid-shadow-legends-artifact-and-accessory-guide/)

---

*Profile compiled by CHICHON — early-v1, August 2026. Feedback and issue reports: [github.com/charlescvy/rsl-xtender-sell-setups/issues](https://github.com/charlescvy/rsl-xtender-sell-setups/issues)*
