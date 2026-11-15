---
layout: page
title: Hazard Deck Balance Lab — Baseline and Controlled Variant
---

# Hazard Deck Balance Lab — Baseline and Controlled Variant

**Purpose:** decide whether the Academy's 30-card Hazard deck is doing its job, without changing the Hero deck or quietly making the first campaign easier or harder.

This is a research and practice page. It does **not** replace the active Hazard list. Keep the Challenge Deck C-derived baseline for the first three recorded games. The proposed v1.1 list is an experiment only.

## 1. Keep the Hero deck fixed

The control setup remains:

| Zone | Cards |
|---|---:|
| Hero play deck | **36** |
| — Resources | 30 |
| — Character/Wizard cards shuffled into it | 6 |
| Starting company and two Cram items | Separate setup cards |
| Hazard deck | **30** |
| Location deck | 15 site cards, not shuffled |

The Hero list stays unchanged while the Hazard list is evaluated. Do not change the Wizard, Resource list, starting company, route and Hazard list in the same test. Otherwise you will not know which change caused the difference.

The Hero play deck is the teaching build, not a claim of tournament optimisation. Use the [Hero deck list]({{ '/decks/hero-deck/' | relative_url }}) as the physical-card checklist.

## 2. The fixed Hazard baseline

| Quantity | Card |
|---:|---|
| 3 | Cave Worm |
| 3 | Despair of the Heart |
| 3 | Full of Froth and Rage |
| 3 | Giant Spiders |
| 3 | Lesser Spiders |
| 2 | Neeker-breekers |
| 2 | River |
| 2 | Seized by Terror |
| 2 | Twilight |
| 2 | Wake of War |
| 2 | Wargs |
| 3 | Watcher in the Water |
| **30** | **Total** |

That is **16 creatures (53%)** and **14 non-creature Hazards (47%)**. The independent *My Solo Rules* guide suggests roughly half creatures and half general Hazards as a useful starting point, not a rule. The baseline is close to that guide and preserves the historical teaching list.

### What is live on the three opening routes?

The opening Book campaign uses:

1. Rivendell → Moria: Rhudaur → Hollin → Redhorn Gate.
2. Moria → Goblin-gate: Redhorn Gate → Hollin → Rhudaur → High Pass.
3. Goblin-gate → Blue Mountain Dwarf-hold: High Pass → Rhudaur → Arthedain → Númeriador.

All three paths contain Wilderness, but **Watcher in the Water is not a generic double-Wilderness creature**. Its printed key requires two Wilderness regions plus a Coastal Sea, or it may be played at Moria. It is therefore legal on the first leg through the explicit Moria permission, but not on the later two legs.

On these three opening routes:

- **Seized by Terror ×2** is inactive because none of the paths contains a Shadow-land or Dark-domain. A Shadow-hold site symbol is not a Shadow-land region symbol.
- **Twilight ×2** has no target because the active Hero main deck has no Environment and the sideboard is closed.
- **Watcher in the Water ×3** is legal only on the Moria leg; it is route-inactive on the Goblin-gate and Blue Mountain legs.

These cards are not universally dead. The corrected Hero Location deck also includes **The Wind Throne**, whose site path from Lórien contains a Shadow-land and whose named region is Grey Mountain Narrows. That route makes Seized by Terror and Cave Worm legal, but not Watcher in the Water or Giant Spiders. The full audit is in the [Location Deck Legality & Wind Throne Lab]({{ '/scenarios/location-deck-legality-lab/' | relative_url }}).

Other conditional cards still have meaningful opportunities:

- **Despair of the Heart:** can target an eligible Dwarf; only one corruption card may be played on a given character per turn, so the three copies must be spread across different characters.
- **Full of Froth and Rage:** improves Spider and Animal attacks, but is discarded if one of those attacks is defeated.
- **Wake of War:** improves Wolf, Spider and Animal attacks. It also adds a strike to those attacks, subject to the exact wording of the attack.
- **River:** can disrupt the destination Site Phase. Óin is a Ranger in the starting company, so he can tap to cancel River; that still costs the company an action and may remove him as a support character.
- **Creatures:** check the actual site path and printed key every time. Do not assume that a card is legal merely because the destination sounds dangerous.

## 3. Route pressure: draw size is not the same as usable pressure

The five-Dwarf company has a base Hazard Limit of five in these examples. The solo Hazard draw is **2 + twice the normal Hazard draw**. The first three rows are the connected opening expedition; the final row is the optional Starter Movement route to The Wind Throne.

| Journey | Movement | Hero draw | Solo Hazard draw | Route-inactive cards | Expected total creatures | Expected route-legal creatures | Chance of at least one route-inactive card |
|---|---|---:|---:|---:|---:|---:|---:|
| Rivendell → Moria | Region (3 regions) | Up to 2 | **8** | 4 | 4.27 | **4.27** | **73.3%** |
| Moria → Goblin-gate | Region (4 regions) | Up to 1 | **6** | 7 | 3.20 | **2.60** | **83.0%** |
| Goblin-gate → Blue Mountain Dwarf-hold | Region (4 regions) | Up to 1 | **4** | 7 | 2.13 | **1.73** | **67.7%** |
| Lórien → The Wind Throne | Starter | Up to 2 | **6** | 8 | 3.20 | **2.00** | **87.4%** |

For the first three routes, the inactive-card counts are:

- **Moria:** Seized by Terror ×2 and Twilight ×2 = 4.
- **Goblin-gate / Blue Mountain:** Watcher in the Water ×3, Seized by Terror ×2 and Twilight ×2 = 7.

For The Wind Throne route, the eight inactive cards are Giant Spiders ×3, Watcher in the Water ×3 and Twilight ×2. Seized by Terror is now legal because the printed site path includes a Shadow-land.

The expected total-creature count uses all 16 creatures in the deck. The expected **route-legal** count uses only creatures that can actually be keyed on that route: 16 on the Moria leg, 13 on the later two legs, and 10 on the Wind Throne route. The five-Dwarf Hazard Limit remains five; it does not change with the number drawn.

### What the probabilities mean

The figures assume a fresh, shuffled 30-card deck and draws without replacement:

- Expected total creatures = draw size × 16/30.
- Expected route-legal creatures = draw size × number of route-legal creature cards / 30.
- Chance of at least one route-inactive card = 1 - C(30-k, n) / C(30, n), where (k) is the route-inactive card count and (n) is the solo draw size.
- Chance of seeing at least one Despair of the Heart is 62.1% on the eight-card Moria draw, 50.1% on a six-card draw, and 36.0% on the four-card Blue Mountain draw.
- The chance of seeing at least one Full of Froth and Rage or Wake of War is 81.5%, 70.2% and 53.8% for draws of eight, six and four respectively.

These are **composition probabilities, not chances of a successful attack or of winning**. They do not account for the company, exact card timing, earlier cards removed from the Hazard deck, or the choice of which legal Hazards to play. A support event being drawn does not mean it should automatically be played.

## 4. Proposed route-specific variants — only after baseline games

Keep the 30-card baseline unchanged for the first three recorded games. If those games show a real weakness, test **one** of these route-specific two-card variants:

| Variant | Remove | Add | Intended route |
|---|---|---|---|
| **Moria / Goblin-gate** | 1 Twilight; 1 Watcher in the Water | 1 Arouse Minions; 1 Brigands | Arouse Minions can raise the automatic attack at a Shadow-hold. Brigands is keyed to Border-land/Wilderness and pressures the company's Items. |
| **Wind Throne** | 1 Twilight; 1 Watcher in the Water | 1 Arouse Denizens; 1 Brigands | Arouse Denizens can raise the automatic attack at a Ruins & Lairs. Brigands is keyed to the site's Border-land/Wilderness path. |

Both variants keep **16 creatures / 14 non-creature Hazards (53/47)** and add no Dragon creatures. Both retain the two Seized by Terror copies. Do not remove Seized by Terror: The Wind Throne route makes it a live card.

### Moria / Goblin-gate variant

- Moria: 27/30 route/target opportunities; 3 route-inactive cards; expected route-legal creatures 4.27; chance of at least one inactive card 62.1%.
- Goblin-gate: 25/30 opportunities; 5 inactive; expected route-legal creatures 2.80; chance 70.2%.
- Blue Mountain: 24/30 opportunities; 6 inactive; expected route-legal creatures 1.87; chance 61.2%.

The variant improves the three-leg campaign-wide count from 26/30 to 27/30. It preserves the creature/event ratio; it does not raise the raw expected number of creatures drawn.

### Wind Throne variant

- Wind Throne: 24/30 route/target opportunities; 6 inactive; expected route-legal creatures 2.20; chance of at least one inactive card 77.3%.

Arouse Denizens is the correct site-attack modifier for The Wind Throne because it is a Ruins & Lairs. Arouse Minions is not legal there. The card increases one automatic attack's prowess by +3; it does not add strikes. Brigands adds a route-keyed creature that can threaten the company's Items.

Both variants are proposals only. Check your physical collection before buying anything. Keep the Hero deck, starting company, route and decision standards fixed while testing; do not change the Wizard choice at the same time.

## 5. A worked Moria pressure check

For a five-Dwarf company moving Rivendell → Moria:

- Hero draw: up to 2.
- Solo Hazard draw: 8.
- Base Hazard Limit: 5.
- Moria automatic attack if the company enters: Orcs, four strikes at 7 prowess.

Arouse Minions, if tested, can raise that automatic attack to four strikes at 10 prowess. It is still one Hazard play and does not force the Hero company to enter.

The Hazard player must distinguish three layers:

1. **Route-keyed attacks:** creatures legal because of the actual Redhorn Gate / Wilderness site path.
2. **Movement/Hazard events:** effects such as Despair, River and attack support, each with its own target and timing.
3. **Site automatic attack:** part of entering Moria; it is not itself a Hazard card and does not consume a Hazard slot. Arouse Minions is a separate Hazard play that modifies it.

Use the [Hazard Player guide]({{ '/reference/hazard-player/' | relative_url }}) and the [Site Entry & Automatic Attack Lab]({{ '/scenarios/site-entry-lab/' | relative_url }}) to keep those layers separate.

## 6. The controlled test

### Baseline — three games

Keep the 36-card Hero deck and 30-card Hazard baseline fixed. Use the same five starting Dwarves and the same Book of Mazarbul mission. Record each Movement/Hazard Phase.

| Measure | Game 1 | Game 2 | Game 3 |
|---|---:|---:|---:|
| Hazard cards drawn | | | |
| Cards with a legal play available | | | |
| Normal Hazard plays made | | | |
| Unused cards discarded under the Academy solo supplement | | | |
| Creature attacks faced | | | |
| Wounds / taps caused by Hazards | | | |
| Corruption checks caused by Hazards | | | |
| River played / Ranger response | | | |
| Site entered? | | | |
| Objective progress | | | |
| Reason for abort or recovery | | | |

Do not count an unplayed but legal card as an automatic failure of the deck. The Hazard Limit, timing, company state and the relative impact of each option matter.

### Variant — only if the baseline shows a real weakness

If the first three records show repeated route-inactive draws or an obvious lack of pressure, and you physically own the relevant candidate cards, run three further games with only one of the route-specific two-card variants. Do not combine the Moria/Goblin-gate and Wind Throne variants.

Keep the Hero deck, starting company, mission, location cards and decision standards unchanged. Compare:

- campaign-inactive draws;
- legal plays available;
- Hazard Limit usage;
- actual wounds, taps and corruption checks;
- item losses or Site Phase denial;
- whether the Hero objective was delayed, abandoned or completed.

Do not change the Wizard choice or Hero Resources at the same time. If the variant produces more legal choices but no meaningful change to the expedition, it may be more flexible without being more difficult. That is a useful result, not a failure.

## 7. Practice before changing the cards

Complete the [Hazard Deck Balance Lab — model answer]({{ '/scenarios/hazard-deck-balance-lab/answer-key/' | relative_url }}) only after attempting these questions:

1. Why is Watcher in the Water legal at Moria but not on the Goblin-gate or Blue Mountain legs?
2. Why are Seized by Terror and Twilight inactive on the three opening routes, but Seized by Terror legal on the Wind Throne route?
3. Why is Arouse Minions legal at Moria and Goblin-gate but not Blue Mountain or The Wind Throne?
4. Why is Arouse Denizens the matching candidate for The Wind Throne?
5. Does Brigands' item-discard effect happen if no character is wounded?
6. Why do the expected route-legal creature counts differ from the raw expected creature counts?
7. What evidence would justify changing the baseline?

## Sources and authority

- [Council of Elrond current consolidated rules](https://www.councilofelrond.org/rules/) — movement, site paths, Hazard Limits, event timing, corruption and actions.
- [Council of Elrond official card database](https://www.councilofelrond.org/cards/) — current card text and errata for Arouse Minions, Brigands, Seized by Terror, Twilight, Despair of the Heart, Full of Froth and Rage, and Wake of War.
- [The Wizards rules and solitaire procedure](https://meccg.com/rules/by-expansion/the-wizards/) — printed solo setup and the separate Hazard-draw procedure.
- [My Solo Rules](https://meccg.wordpress.com/my-solo-rules/) — independent solo-deck construction guidance; its suggested 30–40 card ranges and approximate creature/event balance are recommendations, not official deck-building limits.

**Decision for now:** keep the active 30-card Hazard baseline unchanged. Complete three baseline games before considering v1.1. The Hero deck remains fixed at 36 cards, and the non-Haven route plan remains available without buying anything.
