---
layout: page
title: Iron Hill Expedition — Starter vs Region Movement
---

# Iron Hill Expedition — Starter vs Region Movement

This is the worked alternative expedition promised by the Resource Route Planner. It teaches a crucial distinction: **Starter Movement can use a site path longer than four regions; the four-region maximum belongs to Region Movement.** It also shows how choosing a different legal site path can make different Hazard cards playable.

## Objective: Iron Hill Dwarves

The active Hero Resource list contains **Iron Hill Dwarves**, a unique Dwarf faction worth **4 marshalling points**. It is playable at Iron Hill Dwarf-hold if the influence check is greater than 8. The faction gives a +2 standard modification to a Dwarf influencer.

Iron Hill Dwarf-hold is a Hero **Free-hold**, not a Shadow-hold. Its site card has:

- Region: Iron Hills
- Nearest Haven: Lórien
- Site-card numbers: **3 Hazard / 3 Hero**
- Automatic attack: **none**
- Site type: Free-hold

The card's name includes “Dwarf-hold”, but its actual site type is Free-hold. That distinction matters for Hazard keying: **Arouse Minions is not playable there.**

## Route A — direct Starter Movement from Lórien

**Legal one-movement route**

Lórien is a Haven, and the Iron Hill Dwarf-hold site card lists Lórien as its nearest Haven. That satisfies the Starter Movement condition.

The printed site path is:

**Wilderness → Border-land → Border-land → Wilderness → Wilderness**

That is five region-type symbols. It is still legal Starter Movement: the four-consecutive-region maximum applies to Region Movement, not Starter Movement.

The Starter Movement site path contains the region types and the names of the origin and destination regions, but not the names of the intermediate regions. In this case the path does not expose a Shadow-land or Dark-domain region type.

| Measure | Direct Starter Movement |
|---|---:|
| Movements | 1 |
| Hero draw | Up to **3** |
| Normal Hazard draw | **3** |
| Solo Hazard draw | **8** |
| Five-Dwarf Hazard Limit | **5** |
| Site automatic attack | None |
| Seized by Terror | **Not legal** |

Why Seized by Terror is not legal: the site path contains Wilderness and Border-land, but no Shadow-land or Dark-domain. A Shadow-hold site symbol would not substitute for a Shadow-land region symbol; here the destination is not even a Shadow-hold.

Other relevant Hazard opportunities:

- **Cave Worm:** legal, because Iron Hills is the named destination region on the site path.
- **Brigands:** legal in the proposed variant, because the path contains Border-land and Wilderness.
- **Arouse Minions:** not legal; the destination is a Free-hold, not a Shadow-hold or Dark-hold.
- **Twilight:** no useful Environment target in the fixed first-play build.

The route has a high solo draw of eight Hazards, but it avoids the Shadow-land key and reaches the objective in one movement.

## Route B — stage at Eagles’ Eyrie, then use Region Movement

This alternative demonstrates how to move between non-Haven sites without returning to a Haven every turn.

### Leg 1: Lórien → Eagles’ Eyrie

Eagles’ Eyrie is a Hero Free-hold in Anduin Vales. Its site card lists Lórien as its nearest Haven and has site-card numbers **1 Hazard / 1 Hero**, with no automatic attack.

Starter Movement from Lórien is legal.

| Measure | Lórien → Eagles’ Eyrie |
|---|---:|
| Hero draw | Up to **1** |
| Normal Hazard draw | **1** |
| Solo Hazard draw | **4** |
| Five-Dwarf Hazard Limit | **5** |
| Site automatic attack | None |

### Leg 2: Eagles’ Eyrie → Iron Hill Dwarf-hold

Use Region Movement through this exact sequence:

**Anduin Vales → Grey Mountain Narrows → Northern Rhovanion → Iron Hills**

This is four consecutive regions, including both endpoints. Each adjacency is printed on the relevant Region cards, and no region repeats.

The site path now exposes these region types and names:

| Region | Type |
|---|---|
| Anduin Vales | Border-land |
| Grey Mountain Narrows | Shadow-land |
| Northern Rhovanion | Wilderness |
| Iron Hills | Wilderness |

| Measure | Eagles’ Eyrie → Iron Hill |
|---|---:|
| Hero draw | Up to **3** |
| Normal Hazard draw | **3** |
| Solo Hazard draw | **8** |
| Five-Dwarf Hazard Limit | **5** |
| Site automatic attack | None |

The crucial difference is **Grey Mountain Narrows**. It is a Shadow-land, so **Seized by Terror is now legal** against an eligible character in the moving company.

The second leg also exposes the named regions to creatures keyed by name. Cave Worm can be keyed to Iron Hills. The path still contains Wilderness and Border-land, so the proposed Brigands card is legal too.

The price is an extra movement/hazard phase: the staged journey draws **4 + 8 = 12 solo Hazard cards** across two legs, compared with eight on the direct Starter Movement. The company does receive a Site Phase at Eagles’ Eyrie. A generally playable minor item or another legal action may still be worthwhile, but no card in the current Resource list specifically names or rewards Eagles’ Eyrie. Weigh that possible Site Phase against four extra solo Hazard draws; do not take the stop just because the four-region route looks tidy.

## What the route teaches about the Hazard deck

| Hazard | Direct Starter path | Region path via Eagles’ Eyrie |
|---|---|---|
| Cave Worm | Legal — Iron Hills named | Legal — Iron Hills named |
| Giant Spiders | Legal — double Wilderness | Legal — double Wilderness |
| Brigands (proposed) | Legal — Border-land/Wilderness | Legal — Border-land/Wilderness |
| Seized by Terror | **Illegal** — no Shadow-land/Dark-domain | **Legal** — Grey Mountain Narrows is Shadow-land |
| Arouse Minions (proposed) | **Illegal** — Free-hold destination | **Illegal** — Free-hold destination |
| Twilight | No useful Environment target | No useful Environment target |

The direct Starter path gives the baseline Hazard deck 26 cards with a route or target opportunity; the route through Grey Mountain Narrows raises that to 28 because the two Seized by Terror copies gain a legal key. In the proposed v1.1 variant, the direct path rises to 27/30 because Brigands replaces a card with no key, while the Grey Mountain Narrows route remains 28/30: Seized by Terror is already live there and Arouse Minions is not legal at the Free-hold. This is not a claim that all route-active cards can be played in one phase: timing, targets, duplication restrictions and the Hazard Limit still apply.

This is also why the proposed two-card Hazard variant is route-dependent. See the [Hazard Deck Balance Lab]({{ '/scenarios/hazard-deck-balance-lab/' | relative_url }}) for the full draw-probability analysis and controlled test protocol. Arouse Minions improves the Moria and Goblin-gate legs, but has no target at Iron Hill. On the route through Grey Mountain Narrows, Seized by Terror is useful, so replacing one copy with Brigands does not increase the number of route-active cards. Keep the baseline until the first three games are recorded.

The Hazard deck contains three Cave Worms. Cave Worm is a **Drake, not a Dragon**; the current baseline has no Dragon creatures. This route makes its Iron Hills key relevant without requiring a Dragon-heavy Hazard build.

## Preparing the Iron Hill faction attempt

The faction is worth four MPs, but you must enter the site and have an untapped character and untapped site to play it.

Two starting Dwarves are natural influencers:

- **Thorin II:** +2 direct influence against Dwarves and Dwarf factions.
- **Glóin:** +1 direct influence against Dwarves and Dwarf factions.

The faction itself gives Dwarves +2 as a standard modification. The influence check must be greater than 8.

There is an important Organization Phase choice. In the current starting-company arrangement, Thorin's direct influence is used to control Dori and Kíli, and Glóin's is used to control Óin. That means their direct influence is already committed; do not automatically count the full amount as available for the faction check.

You may move followers to general influence during the Organization Phase if your maximum general influence is not exceeded. The five starting Dwarves have total mind **20** (8 + 1 + 3 + 5 + 3), exactly matching the Wizard player's starting general influence of 20. If you move all three followers to general influence, Thorin and Glóin have their direct influence available for the faction attempt, but all 20 general influence is then committed. You give up spare general influence for another non-follower character, while freeing direct influence to control new followers; choose the arrangement that best supports the next recruitment step.

The [model answer]({{ '/routes/iron-hill-expedition/answer-key/' | relative_url }}) works through the check modifiers and the route choice. Check the actual untapped characters and available influence before attempting it.

### Optional Iron Hill specialists — not in the active baseline

The official card database identifies **Dáin II** and **Gimli** as stronger, site-specific candidates: both have Iron Hill Dwarf-hold as their home site and +2 direct influence against the Iron Hill Dwarves faction. Dáin has mind 7 and base direct influence 3; Gimli has mind 6 and base direct influence 2. Under the current follower assignments, seven general influence is unused, so either character could fit at the home site if included in the Hero play deck and drawn. Dáin would use all seven available general influence.

With their direct influence available, Dáin would have 3 + 2 against the faction, plus the faction's Dwarf standard +2: total modifier +7, which clears the greater-than-8 check on any natural 2D6 result. Gimli would have 2 + 2 + 2 = +6, succeeding on a natural 3 or higher (35/36). Dáin is the stronger dedicated Iron Hill influencer; Gimli is the slightly lower-mind alternative. Adding one would take the current 36-card play deck to 37; adding both would make 38. Both remain within the standard character-card limit and above the solo 30-card minimum, but they change the deck's draw density. This is a strong **future Iron Hill-focused deck experiment**, not a change to the 36-card teaching baseline. Neither character is in the current list; check your physical collection before considering either, and do not buy cards just for this test. If you want to play Dáin or Gimli under the seven spare general influence, keep the current follower assignments; moving all three followers to general influence would use all 20 GI and leave no room for either specialist.

## Practice questions

1. Why is Lórien → Iron Hill Dwarf-hold legal by Starter Movement even though the printed path has five region types?
2. Why is a single Region Movement from Lórien to Iron Hill illegal?
3. Why is Seized by Terror illegal on the direct Starter path but legal on the route through Grey Mountain Narrows?
4. Why is Arouse Minions not playable at Iron Hill, despite the route passing through a Shadow-land on the second option?
5. Calculate both solo Hazard draws on Route B and compare them with Route A.
6. What Organization Phase change frees Thorin's and Glóin's direct influence for the faction attempt?
7. If the only objective is Iron Hill Dwarves and there is no reason to visit Eagles’ Eyrie, which route is the more efficient Hero choice?

See the [model answer]({{ '/routes/iron-hill-expedition/answer-key/' | relative_url }}) after attempting the questions.

## Sources

- [Council of Elrond current rules](https://www.councilofelrond.org/rules/) — Starter Movement, Region Movement, site paths, movement draws, Hazard Limits, general/direct influence and faction influence checks.
- [Council of Elrond official card database](https://www.councilofelrond.org/cards/) — Iron Hill Dwarf-hold, Eagles’ Eyrie, Iron Hill Dwarves, Thorin II, Glóin, Cave Worm, Seized by Terror, Brigands and Arouse Minions.
- [Hero deck and Resource list]({{ '/decks/hero-deck/' | relative_url }})
- [Free Movement guide]({{ '/reference/free-movement/' | relative_url }})
- [Hazard deck audit]({{ '/decks/hazard-deck/' | relative_url }})

**Teaching point:** the longest printed Starter site path is not automatically illegal or more dangerous. Compare the actual movement method, region types, named regions, card keys and draw numbers before choosing a route.
