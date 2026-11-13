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

### What is live on the three teaching routes?

The opening campaign uses:

1. Rivendell → Moria: Rhudaur → Hollin → Redhorn Gate.
2. Moria → Goblin-gate: Redhorn Gate → Hollin → Rhudaur → High Pass.
3. Goblin-gate → Blue Mountain Dwarf-hold: High Pass → Rhudaur → Arthedain → Númeriador.

All three declared Region Movement paths contain Wilderness regions. The four cards with no route/target in this closed-sideboard campaign are:

- **Seized by Terror ×2:** requires a moving non-Wizard, non-Ringwraith character in a Shadow-land or Dark-domain region. A Shadow-hold site symbol is not a Shadow-land region symbol.
- **Twilight ×2:** requires an Environment card in play or declared earlier in the same chain. The active Hero main deck has no Environment and the sideboard is closed; the Hazard list has no other Environment.

These are campaign-inactive cards, not universally dead cards. A different route or an Environment can make them useful. In this solo setup, a Twilight drawn from the separate Hazard deck is used as a Hazard, not played as a Resource.

Other conditional cards still have meaningful opportunities:

- **Despair of the Heart:** can target an eligible Dwarf; only one corruption card may be played on a given character per turn, so the three copies must be spread across different characters.
- **Full of Froth and Rage:** improves Spider and Animal attacks, but is discarded if one of those attacks is defeated.
- **Wake of War:** improves Wolf, Spider and Animal attacks. It also adds a strike to those attacks, subject to the exact wording of the attack.
- **River:** can disrupt the destination Site Phase. Óin is a Ranger in the starting company, so he can tap to cancel River; that still costs the company an action and may remove him as a support character.
- **Creatures:** check the actual site path and printed key every time. Do not assume that a card is legal merely because the destination sounds dangerous.

## 3. Route pressure: three different draw sizes

The site-card numbers are shown as **normal Hazard draw / Hero draw**. The solo Hazard side draws \(2 + 2 \times\) the normal Hazard draw. The five-Dwarf company has a base Hazard Limit of five in these examples.

| Journey | Regions | Hero draw | Solo Hazard draw | Expected creatures in a fresh draw — baseline | Chance of at least one campaign-inactive card — baseline |
|---|---:|---:|---:|---:|---:|
| Rivendell → Moria | 3 | Up to 2 | **8** | 4.27 | 73.3% |
| Moria → Goblin-gate | 4 | Up to 1 | **6** | 3.20 | 61.2% |
| Goblin-gate → Blue Mountain Dwarf-hold | 4 | Up to 1 | **4** | 2.13 | 45.4% |

These are not three different Hazard Limits. The company limit remains five; the number drawn changes with the destination's normal Hazard draw number. The route is still legal Region Movement: count both endpoint regions, use no more than four consecutive regions, do not repeat a region, and check every adjacency.

### What the probabilities mean

The figures above use a fresh, shuffled 30-card baseline and a draw without replacement:

- Expected creatures = draw size × 16/30.
- “At least one campaign-inactive card” means at least one of the two Seized by Terror or two Twilight cards appears in the draw.
- The chance of seeing at least one Despair of the Heart is 62.1% on the eight-card Moria draw, 50.1% on the six-card Goblin-gate draw, and 36.0% on the four-card Blue Mountain draw.
- The chance of seeing at least one Full of Froth and Rage or Wake of War is 81.5%, 70.2% and 53.8% respectively. On the eight-card Moria draw, the chance of drawing at least five creatures is 42.6% in the baseline and 51.5% in the proposed variant.

For example, the Moria expectation is 8 × 16/30 = 4.27 creatures. The chance of at least one of the four campaign-inactive cards is 1 − [C(26,8) / C(30,8)] ≈ 73.3%.

These are **composition probabilities, not chances of a successful attack or of winning**. They do not account for the company, exact card timing, earlier cards removed from the Hazard deck, or the choice of which legal Hazards to play. A support event being drawn does not mean it should automatically be played.

## 4. Proposed v1.1 — two swaps, not an extra deck

Only after the baseline games, test this exact two-card change:

| Remove | Add | Why test it? |
|---|---|---|
| 1 Twilight | 1 Arouse Minions | Adds a route-relevant way to increase one automatic attack at a Shadow-hold or Dark-hold by +3 prowess. |
| 1 Seized by Terror | 1 Brigands | Adds a two-strike, 8-prowess Men creature keyed to Border-land or Wilderness; if any strike wounds a character, the company discards one item chosen by the defender. |

The variant remains 30 cards:

- **17 creatures (57%)**
- **13 non-creature Hazards (43%)**
- One Twilight remains for a later Environment campaign.
- One Seized by Terror remains for a later Shadow-land/Dark-domain route.
- No Dragon creatures are added.

### The route-specific trade-off

| Destination | Arouse Minions? | Brigands? | Cards with no route/target in this campaign — variant |
|---|---|---|---:|
| Moria | Yes — 4 Orc strikes rise from 7 to 10 prowess | Yes — Wilderness key | 2/30 |
| Goblin-gate | Yes — 3 Orc strikes rise from 6 to 9 prowess | Yes — Wilderness key | 2/30 |
| Blue Mountain Dwarf-hold | No — this is a Free-hold, not a Shadow-hold/Dark-hold | Yes — Wilderness key | 3/30 |

For a fresh draw, the variant's expected creature counts are 4.53, 3.40 and 2.27 for the 8-, 6- and 4-card draws. Its chance of drawing at least one campaign-inactive card is 46.9%, 36.6% and 36.0% respectively.

The variant therefore makes more cards potentially relevant on the first two legs, but it does **not** guarantee stronger play:

- Arouse Minions consumes a normal Hazard Limit slot. It does not add strikes; it raises the prowess of one automatic attack at the site.
- The Hero company can decline to enter the site, in which case it does not face that site's automatic attack.
- Brigands' item-discard effect only matters if a strike wounds a character and the company has an item to discard.
- At Blue Mountain, Arouse Minions is not legal on the Free-hold destination.
- A support card still consumes a Hazard slot that could have been used for a creature or disruption card.

Do not buy either candidate just for this test. Check your physical collection first. No proxy or printed replacement is part of the Academy.

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

If the first three records show repeated campaign-inactive draws or an obvious lack of pressure, and you physically own both candidate cards, run three further games with only the two Hazard swaps.

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

1. Why are Seized by Terror and Twilight unavailable on the three opening routes?
2. Why is Arouse Minions legal at Moria and Goblin-gate but not Blue Mountain Dwarf-hold?
3. Does Brigands' item-discard effect happen if no character is wounded?
4. Does Arouse Minions add three strikes to Moria's automatic attack?
5. Why can a 30-card deck with 16 creatures still fail to produce five useful creature plays in a given phase?
6. What evidence would justify changing the baseline?
7. In the v1.1 variant, the company moves from Goblin-gate to Blue Mountain Dwarf-hold. Why is Arouse Minions not legal on this leg even though the company started at a Shadow-hold? Why is Brigands still legal, and how many Hazard cards are drawn?

## Sources and authority

- [Council of Elrond current consolidated rules](https://www.councilofelrond.org/rules/) — movement, site paths, Hazard Limits, event timing, corruption and actions.
- [Council of Elrond official card database](https://www.councilofelrond.org/cards/) — current card text and errata for Arouse Minions, Brigands, Seized by Terror, Twilight, Despair of the Heart, Full of Froth and Rage, and Wake of War.
- [The Wizards rules and solitaire procedure](https://meccg.com/rules/by-expansion/the-wizards/) — printed solo setup and the separate Hazard-draw procedure.
- [My Solo Rules](https://meccg.wordpress.com/my-solo-rules/) — independent solo-deck construction guidance; its suggested 30–40 card ranges and approximate creature/event balance are recommendations, not official deck-building limits.

**Decision for now:** keep the active 30-card Hazard baseline unchanged. Complete three baseline games before considering v1.1. The Hero deck remains fixed at 36 cards, and the non-Haven route plan remains available without buying anything.
