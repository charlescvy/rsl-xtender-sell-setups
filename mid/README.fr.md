# Sell-setup RSL-Xtender « Midgame équilibré »

`midgame-v3.json` — juillet 2026

[🇬🇧 English version](README.md)

## Pour qui ?

Les comptes **midgame** : vous farmez les donjons autour des stages **16 à 22** (Dragon, Spider, Golem, Fire Knight).

## Pourquoi ce fichier ?

Parce que ton temps de jeu, c'est pour jouer, pas pour ranger ! Ce fichier applique les recommandations des guides de référence (HellHades, InTeleria, Ayumilove), **adaptées au niveau midgame**. Philosophie **équilibrée** : on vend ce qui n'a pas d'avenir, on garde tout potentiel réel.

## Le socle : vendu partout

| Règle | Détail |
|---|---|
| Commun / Peu commun | vendus, toujours |
| Rang ≤ 4★ | vendus (aux stages 16+ vous droppez du 5-6★) — seuil ≤ 3★ pour les sets premium |
| Rares sans SPD en substat | vendus (sauf bottes SPD, et pièces déjà montées) |
| Plastron / gants / bottes à stat principale plate (HP/ATK/DEF) | vendus |

## Les 4 tiers de sets (69 sets couverts)

| Tier | Sets | Règle épique/légendaire |
|---|---|---|
| **T1 — Premium / événementiels** | Feral, Merciless, Pinpoint, Stoneskin, Protection, Zeal, Lethal, Supersonic, Slayer, Stonecleaver, Rebirth, Chronophage, Mercurial, Swift Parry, Deflection, Bolster, Defiant, Impulse, Righteous, Killstroke, Instinct, Untouchable, Frostbite, Bloodthirst, Guardian | vendu seulement si AUCUNE substat utile (SPD, CR, CDMG, ACC, HP%, DEF%, ATK%, +RES pour les tanks) |
| **T2 — Clés farmables** | Speed, Lifesteal, Relentless, Perception, Regeneration, Immortal, Shield, Immunity, Accuracy, Savage, Crit Rate, Crit Damage, Cruel, Reflex, Stalwart, Resilience, Fortitude, sets Divine | gardé avec ≥ 1 substat du rôle du set (crit pour les sets dégâts, SPD/ACC pour les supports, HP%/DEF%/RES pour les tanks) |
| **T3 — Situationnels** | Daze, Cursed, Frost, Frenzy, Stun, Toxic, Provoke, Retaliation, Avenging, Curing, Destroy, Fury, Fatal, Affinitybreaker | comme T2, plus : épique ≤ 5★ sans SPD = vendu |
| **T4 — Faibles** | Life, Offense, Defense, Resistance, Divine Offense | épique sans SPD = vendu (même 6★) ; légendaire gardé avec 1 substat de rôle |

## Règles par slot (épique/légendaire)

- **Bottes** : SPD principale = toujours gardées. % = gardées seulement avec SPD en substat.
- **Gants** : C.RATE / C.DMG principale = gardés selon le rôle du set. Plats = vendus.
- **Plastron** : HP%/ATK%/DEF%/ACC gardés selon rôle ; RES sans SPD = vendu ; plats = vendus.
- **Casque / Arme / Bouclier** : jugés uniquement sur les substats (listes de rôle).

## Accessoires (calibrage Spider ~20)

- ≤ 4★ vendus (le Spider 20 droppe ~73 % de 5★ et ~27 % de 6★) — sauf légendaires, épargnés.
- Rares sans SPD vendus ; épiques sans aucune substat utile vendus ; légendaires 5★+ toujours gardés.
- Amulette plate sans SPD ni C.DMG : vendue. Bannière plate sans SPD ni ACC : vendue.
- Refresh / Cleansing / Reaction et accessoires des sets premium : quasi tout gardé.

## Sécurités intégrées

- **Mythiques jamais auto-vendus** (ils ont deux stats principales).
- Pièces déjà améliorées (niveau > 4) protégées des règles de qualité.
- Légendaires d'accessoires jamais auto-vendus.

## Fiabilité

La sémantique de chaque champ du format (rangs, raretés, stat principale, groupes de substats « S:<N ») a été vérifiée contre le comportement réel de RSL-Xtender, et le fichier a été validé sur des sessions de farm réelles surveillées au log, y compris le cas piège des légendaires à bonnes stats, qui restent bien dans l'inventaire.

## Quand quitter ce profil

Aux donjons 24-25 (majorité de 6★), durcissez les rares et épiques 5★ ; en Hard mode / CB Ultra-Nightmare, passez sur un profil lategame.

## Import

Onglet **Sell** → icône d'import (en haut à droite) → sélectionner le JSON. ⚠️ Remplace votre configuration actuelle : exportez-la d'abord. Fichier partagé tel quel, à utiliser à vos risques — votre compte peut différer.

## Sources

- HellHades — Artifact Tier List : [hellhades.com/raid/artifact-tier-list](https://hellhades.com/raid/artifact-tier-list/)
- HellHades / RSL Helper — sell-files d'exemple midgame/lategame (SellfileCreator, RSL Helper V6) : [rsl-helper.de](https://rsl-helper.de/?lang=en)
- InTeleria — Gear Tier List : [inteleria.com/raid-shadow-legends-artifact-sets-and-gear-tier-list](https://www.inteleria.com/raid-shadow-legends-artifact-sets-and-gear-tier-list/)
- InTeleria — What to Keep and What to Dump : [inteleria.com/raid-shadow-legends-gear-guide-what-to-keep-and-what-to-dump](https://www.inteleria.com/raid-shadow-legends-gear-guide-what-to-keep-and-what-to-dump/)
- InTeleria — Dungeon Drop Rates (rangs par stage) : [inteleria.com/raid-dungeon-drop-rates](https://www.inteleria.com/raid-dungeon-drop-rates/)
- Ayumilove — Artifact & Accessory Guide : [ayumilove.net/raid-shadow-legends-artifact-and-accessory-guide](https://ayumilove.net/raid-shadow-legends-artifact-and-accessory-guide/)
- Ayumilove — Loot Table & Drop Rates : [ayumilove.net/raid-shadow-legends-loot-table-and-drop-rates](https://ayumilove.net/raid-shadow-legends-loot-table-and-drop-rates/)

---

*Profil compilé et testé par CHICHON — midgame-v3, juillet 2026. Retours et signalements : [github.com/charlescvy/rsl-xtender-sell-setups/issues](https://github.com/charlescvy/rsl-xtender-sell-setups/issues)*
