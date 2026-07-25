# RSL-Xtender Sell-Setup "Balanced Midgame"

`midgame-v3.json` — July 2026

[🇫🇷 Version française](README.fr.md)

## Who is it for?

**Midgame** accounts: you farm dungeons around stages **16 to 22** (Dragon, Spider, Golem, Fire Knight).

## Why this file?

Because your play time is for playing, not for sorting gear! This file applies the recommendations of the reference guides (HellHades, InTeleria, Ayumilove), **tuned for midgame**. **Balanced** philosophy: sell what has no future, keep everything with real potential.

## The baseline: sold everywhere

| Rule | Detail |
|---|---|
| Common / Uncommon | always sold |
| Rank ≤ 4★ | sold (at stages 16+ you drop 5-6★) — threshold ≤ 3★ for premium sets |
| Rares without a SPD substat | sold (except SPD boots, and already-upgraded pieces) |
| Chest / gauntlets / boots with a flat main stat (HP/ATK/DEF) | sold |

## The 4 set tiers (all 69 sets covered)

| Tier | Sets | Epic/Legendary rule |
|---|---|---|
| **T1 — Premium / event** | Feral, Merciless, Pinpoint, Stoneskin, Protection, Zeal, Lethal, Supersonic, Slayer, Stonecleaver, Rebirth, Chronophage, Mercurial, Swift Parry, Deflection, Bolster, Defiant, Impulse, Righteous, Killstroke, Instinct, Untouchable, Frostbite, Bloodthirst, Guardian | sold only with NO useful substat at all (SPD, CR, CDMG, ACC, HP%, DEF%, ATK%, +RES for tank sets) |
| **T2 — Farmable core** | Speed, Lifesteal, Relentless, Perception, Regeneration, Immortal, Shield, Immunity, Accuracy, Savage, Crit Rate, Crit Damage, Cruel, Reflex, Stalwart, Resilience, Fortitude, Divine sets | kept with ≥ 1 substat matching the set's role (crit for damage sets, SPD/ACC for supports, HP%/DEF%/RES for tanks) |
| **T3 — Situational** | Daze, Cursed, Frost, Frenzy, Stun, Toxic, Provoke, Retaliation, Avenging, Curing, Destroy, Fury, Fatal, Affinitybreaker | same as T2, plus: epic ≤ 5★ without SPD = sold |
| **T4 — Weak** | Life, Offense, Defense, Resistance, Divine Offense | epic without SPD = sold (even 6★); legendary kept with 1 role substat |

## Per-slot rules (epic/legendary)

- **Boots**: SPD main = always kept. % main = kept only with a SPD substat.
- **Gauntlets**: C.RATE / C.DMG main = kept per set role. Flat mains = sold.
- **Chestplate**: HP%/ATK%/DEF%/ACC kept per role; RES without SPD = sold; flat = sold.
- **Helmet / Weapon / Shield**: judged on substats only (role lists).

## Accessories (tuned for Spider ~20)

- ≤ 4★ sold (Spider 20 drops ~73% 5★ and ~27% 6★) — except legendaries, always spared.
- Rares without SPD sold; epics with no useful substat sold; 5★+ legendaries always kept.
- Flat amulet without SPD or C.DMG: sold. Flat banner without SPD or ACC: sold.
- Refresh / Cleansing / Reaction and premium-set accessories: almost everything kept.

## Built-in safeties

- **Mythicals are never auto-sold** (they have two main stats).
- Already-upgraded pieces (level > 4) are protected from the quality rules.
- Legendary accessories are never auto-sold.

## Reliability

The semantics of every field of the format (ranks, rarities, main stat, "S:<N" substat groups) were verified against the actual behaviour of RSL-Xtender, and the file was validated on real, log-monitored farming sessions — including the tricky case of good-substat legendaries, which correctly stay in your inventory.

## When to move on

At dungeons 24-25 (mostly 6★ drops), tighten 5★ rares and epics; in Hard mode / Ultra-Nightmare Clan Boss, switch to a lategame profile.

## Import

**Sell** tab → import icon (top right) → select the JSON. ⚠️ This replaces your current configuration — export it first. Shared as-is, use at your own risk — your account may differ.

## Sources

- HellHades — Artifact Tier List: [hellhades.com/raid/artifact-tier-list](https://hellhades.com/raid/artifact-tier-list/)
- HellHades / RSL Helper — midgame/lategame sample sell-files (SellfileCreator, RSL Helper V6): [rsl-helper.de](https://rsl-helper.de/?lang=en)
- InTeleria — Gear Tier List: [inteleria.com/raid-shadow-legends-artifact-sets-and-gear-tier-list](https://www.inteleria.com/raid-shadow-legends-artifact-sets-and-gear-tier-list/)
- InTeleria — What to Keep and What to Dump: [inteleria.com/raid-shadow-legends-gear-guide-what-to-keep-and-what-to-dump](https://www.inteleria.com/raid-shadow-legends-gear-guide-what-to-keep-and-what-to-dump/)
- InTeleria — Dungeon Drop Rates (ranks per stage): [inteleria.com/raid-dungeon-drop-rates](https://www.inteleria.com/raid-dungeon-drop-rates/)
- Ayumilove — Artifact & Accessory Guide: [ayumilove.net/raid-shadow-legends-artifact-and-accessory-guide](https://ayumilove.net/raid-shadow-legends-artifact-and-accessory-guide/)
- Ayumilove — Loot Table & Drop Rates: [ayumilove.net/raid-shadow-legends-loot-table-and-drop-rates](https://ayumilove.net/raid-shadow-legends-loot-table-and-drop-rates/)

---

*Profile compiled and tested by CHICHON — midgame-v3, July 2026. Feedback and issue reports: [github.com/charlescvy/rsl-xtender-sell-setups/issues](https://github.com/charlescvy/rsl-xtender-sell-setups/issues)*
