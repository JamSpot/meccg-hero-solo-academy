---
layout: page
title: Ranger Capacity & River Denial Lab
permalink: /scenarios/ranger-capacity-lab/
---

# 6K. Ranger Capacity & River Denial Lab

This lab answers a practical question that the earlier River exercises only partly answered:

**How much safer is a company with two Rangers than a company with one, and does adding more characters help if they do not add another Ranger?**

The exercise uses the locked 30-card Hazard deck (River ×2 and Seized by Terror ×2), the existing Dwarf company, and routes already taught in the Academy. It does not change either active deck.

## The two route tests

| Route | Movement | Normal Hazard draw | Solo Hazard draw | Seized by Terror |
|---|---|---:|---:|---|
| Lórien → The Wind Throne | Starter Movement | 2 | **6** | Legal: printed path includes a Shadow-land |
| Eagles’ Eyrie → Iron Hill | Region Movement | 3 | **8** | Legal: Grey Mountain Narrows is a Shadow-land |
| Lórien → Iron Hill | Starter Movement | 3 | **8** | Illegal: printed path has no Shadow-land or Dark-domain |

The Wind Throne is in the locked 15-site Hero Location deck. Eagles’ Eyrie is not; the Eyrie route is a supplementary map exercise, not a Game 1 route. The direct Lórien → Iron Hill Starter Movement route is the useful contrast: it draws eight Hazards, but Seized by Terror is not keyed to its printed site path.

The normal Hazard draw comes from the destination site on a non-Haven move. The Academy's solo procedure then uses **2 + twice the normal Hazard draw**. Do not confuse this draw with the company's Hazard Limit.

## Four company profiles

Count the Rangers who are actually in the moving company. Gandalf is a Scout, not a Ranger. Gildor Inglorion is a Ranger.

| Profile | Characters | Rangers | Base Hazard Limit |
|---|---:|---:|---:|
| Five starting Dwarves | 5 | 1 — Óin | 5 |
| Five Dwarves + Gandalf | 6 | 1 — Óin | 6 |
| Five Dwarves + Gildor | 6 | 2 — Óin and Gildor | 6 |
| Five Dwarves + Gandalf + Gildor | 7 | 2 — Óin and Gildor | 7 |

The five-Dwarf company has only Óin as a Ranger. Gandalf increases company size and therefore the Hazard Limit, but does **not** add a Ranger. Gildor is the only character in the active six-card support package who adds a second Ranger. Balin, Boromir II, Celeborn and Fíli do not add Ranger skill.

The **five Dwarves + Gildor** row measures that moving company with Gandalf in a separate company (or otherwise not part of this moving company). A separate Gandalf company has its own Movement/Hazard Phase and Hazard Limit. If Gandalf joins the Dwarves and Gildor, use the seven-character row.

A company away from a Haven cannot exceed seven characters. The seven-character profile is therefore the largest version of this Dwarf company that can move together away from a Haven.

## What River actually asks you to do

River is playable on a site. If a company has moved to that site this turn, it must tap one Ranger for each River played on that site by the beginning of its Site Phase. The Ranger may tap at the beginning of the Site Phase without entering the site.

- One River requires one Ranger.
- Two Rivers require two Rangers.
- If the company cannot meet the requirement, it must do nothing during its Site Phase.
- If enough Rangers tap, the Site Phase may proceed, but those Rangers are now tapped. Another untapped character may still attempt a faction or play another eligible Resource.

Use the current [Collected Rulings File, CRF 22 — River](https://meccg.com/rules/collected-rulings-and-errata-crf/crf-22/card-errata-and-rulings/). The official [Council of Elrond rules](https://www.councilofelrond.org/rules/) set the Hazard Limit at the company's size or two, whichever is greater, and keep it fixed throughout that company's Movement/Hazard Phase, even if a character later splits away.

## First decision table: River without Seized by Terror

Assume the Rangers are untapped when the Site Phase begins.

| Rangers available | One River | Two Rivers |
|---:|---|---|
| 0 | Site Phase denied | Site Phase denied |
| 1 | Tap the Ranger; Site Phase may proceed | Site Phase denied |
| 2 | Tap one Ranger; Site Phase may proceed | Tap both; Site Phase may proceed |
| 3 or more | Tap one Ranger; Site Phase may proceed | Tap two; Site Phase may proceed |

**More characters do not automatically mean more protection.** The requirement counts Rangers, not total company size.

## Second decision table: add Seized by Terror

On a route containing a Shadow-land or Dark-domain, Seized by Terror can target an eligible non-Wizard, non-Ringwraith character moving with the company. The target's player rolls 2D6 and adds the character's mind. A result below 12 splits that character into a different company and returns that company to the original company's site of origin.

| Moving company and Hazard hand | Strongest River-denial line |
|---|---|
| One Ranger; one River; one Seized | Target the only Ranger. If the split succeeds, no Ranger remains to satisfy River. |
| One Ranger; one River; two Seized | Target the same Ranger with the first copy; if it fails, try the second copy on that still-moving Ranger. Either success denies the Site Phase. |
| One Ranger; two Rivers | River already denies the Site Phase. Use Seized on a different valuable eligible character, such as Dori, rather than spending it on the only Ranger. |
| Two Rangers; one River; one Seized | One split is not enough: the other Ranger can still tap. Target another valuable character. |
| Two Rangers; one River; two Seized | To deny the Site Phase, target both Rangers, one with each copy. Both split rolls must succeed. |
| Two Rangers; two Rivers; one Seized | Split either Ranger. One remaining Ranger cannot satisfy two River costs. Óin is the better target than Gildor because his mind is lower. |
| Two Rangers; two Rivers; two Seized | Target Óin first; if he remains with the company after the first roll, target Óin again with the second copy. One successful split is enough to deny the Site Phase. |

### Why the second Seized copy changes the decision

Seized by Terror is a short-event and its current card text has no “cannot be duplicated” restriction. The Hazard player may take actions as many times as desired until the Hazard Limit is reached. Each copy must be played as a separate action/chain and counts as one Hazard play.

- **Two Rivers, two Rangers:** only one Ranger needs to split. If the first Seized attempt against Óin fails, he is still moving and can be targeted by the second copy. The chance of at least one success is (1-(10/36)^2=92.28\%\), not the 88.43% obtained by assigning one attempt to each Ranger.
- **One River, two Rangers:** both Rangers must split. The two copies must target different Rangers; a second attempt on the same Ranger cannot remove the other Ranger who could still satisfy River.

If the first attempt succeeds in the two-River case, the denial is already secured; the second copy may be used on another eligible character if doing so is worthwhile and remains legal.

## ## Fresh-draw probability: how often is a denial line available?

The active Hazard deck has 30 cards, including River ×2 and Seized by Terror ×2. The following calculations use a **fresh, shuffled deck** and the six-card Wind Throne solo draw or eight-card Iron Hill solo draw.

The table is the chance that the Hazard player can create a Site Phase denial using only River and Seized by Terror, including the required Seized split roll. It is not a win probability.

| Moving company | 6-card draw (Wind Throne) | 8-card draw (Iron Hill) |
|---|---:|---:|
| One Ranger (Óin) | **11.53%** | **19.87%** |
| Two untapped Rangers (Óin + Gildor) | **1.05%** | **2.81%** |

Why the two-Ranger figure is much lower:

- With two Rivers, both Rangers can normally tap and proceed. The Hazard player needs Seized by Terror to split at least one Ranger.
- With one River, the Hazard player needs both Seized by Terror copies and must split both Rangers.
- With one Ranger, two Rivers deny the Site Phase automatically; alternatively, one River plus a successful Seized split is enough.

The probability that a fresh draw contains at least one River **and** at least one Seized by Terror is 11.88% for six cards and 20.49% for eight cards. That is not the same as the denial probability: the target's split roll and the number of Rangers still matter.

### Assumptions behind the probability table

- All cards are drawn from a fresh, shuffled 30-card Hazard deck.
- No cards have been seen, discarded, recycled or sideboarded earlier in the expedition.
- The Hazard player did not access the sideboard during this turn’s Untap Phase, so the full base Hazard Limit applies.
- The company has moved to the site this turn.
- The listed Rangers are untapped before River and Seized by Terror resolve.
- No other card effect taps, removes or protects a Ranger.
- The Hazard player prioritises the River/Seized denial line and has enough Hazard Limit to play it.

The relevant lines require at most four Hazard plays, so they fit the normal five-card base Hazard Limit of the starting company. The larger company profiles do not need their extra Hazard Limit to assemble this particular combination. In a continuous multi-leg expedition, the second draw is not a fresh-deck probability; use the actual draw/discard state instead.

## What this means for the Hero deck

The current Hero deck already contains the right optional redundancy: Gildor.

- Óin is the starting Ranger.
- Gildor is the second Ranger if recruited into the moving company.
- Gandalf adds no Ranger skill.
- Balin, Boromir II, Celeborn and Fíli add no Ranger skill.

Do not recruit Gildor solely to make River irrelevant. He is useful because he reduces the Hazard player's ability to deny a Site Phase with a single River and one Seized by Terror. Two Rivers still require two Rangers, and two Seized by Terror copies can threaten both Rangers if only one River is present.

Gildor also uses four points of general influence if controlled by general influence. Recheck the company's influence and seven-character limit before recruiting him. The [Hero Deck Construction guide]({{ '/decks/hero-deck/' | relative_url }}) contains the full character comparison.

## Route-planning lesson

Before moving, record these separately:

1. **Movement type:** Starter or Region Movement?
2. **Site path:** does it contain a Shadow-land or Dark-domain?
3. **Solo draw:** six, eight, or another number based on the site's normal Hazard draw?
4. **Hazard Limit:** how many ordinary Hazard plays can the company face?
5. **Ranger count:** how many Rangers will still be untapped at the beginning of the Site Phase?
6. **Objective:** if River prevents the Site Phase, what Resource or faction attempt is lost?

A direct Starter Movement route can be strategically safer even if it draws the same number of Hazards, because it may keep Seized by Terror illegal. Conversely, a Region Movement route can expose a Shadow-land and make the split effect available. Use the [Free Movement guide]({{ '/reference/free-movement/' | relative_url }}) and [Expedition Planner]({{ '/routes/expedition-planner/' | relative_url }}) before declaring the move.

## Practice — answer before opening the model answer

1. Five starting Dwarves move to The Wind Throne. The Hazard player draws six cards and plays one River. Can the company enter if Óin is untapped?
2. The same company faces two Rivers. How many Rangers are required, and can it take Site Phase actions?
3. The company adds Gandalf but not Gildor. What changes about the Hazard Limit? What changes about River?
4. The company adds Gildor instead. How many Rangers are now available?
5. Óin and Gildor are both untapped. One River and Seized by Terror are played. Can the Hazard player deny the Site Phase by splitting Óin?
6. Óin and Gildor are both untapped. Two Rivers and Seized by Terror are played. Which Ranger is the stronger target?
7. The company has seven characters, but only Óin and Gildor are Rangers. Does the seventh character help satisfy a third River?
8. One Ranger is already tapped when the Site Phase begins. How many additional untapped Rangers are available for two Rivers?
9. Why is Seized by Terror illegal on the direct Lórien → Iron Hill Starter Movement path but legal on the final Eagles’ Eyrie → Iron Hill Region Movement leg?
10. Explain why “the Hazard player drew both River and Seized” is not the same as “the Site Phase is denied.”

**Do not change the active decks after this exercise.** Record actual River/Seized appearances and whether Gildor materially changed a Site Phase before proposing a deck adjustment.

## Rules and card references

- [Council of Elrond Official Game Rules](https://www.councilofelrond.org/rules/) — Hazard Limit, company size, movement and Site Phase.
- [CRF 22 — Card Errata and Rulings](https://meccg.com/rules/collected-rulings-and-errata-crf/crf-22/card-errata-and-rulings/) — current River erratum and one-Ranger-per-River ruling.
- [Council of Elrond Official Card Database](https://www.councilofelrond.org/cards/) — current card wording and errata.
- [Iron Hill — River & Seized by Terror Lab]({{ '/scenarios/iron-hill-river-lab/' | relative_url }}) — the original route-specific exercise.
- [Shadow-land Route & Seized by Terror Lab]({{ '/scenarios/shadowland-route-lab/' | relative_url }}) — the Wind Throne route and target-selection lesson.


## After the split: where did the Ranger go?

A successful Seized by Terror does not send the target to a nearest Haven. The character returns to the **site of origin** for the movement being resolved. The original company continues its current Movement/Hazard Phase with the Hazard Limit set at its beginning; the split character gets no separate Hazard draw or new Hazard Limit and cannot take Site Phase actions that turn.

For the River calculation, count only the Rangers still with the company at the destination. Óin being split away removes him from the River response at The Wind Throne; Dori being split away does not. Gildor adds a second Ranger, but two Rivers still require both Rangers.

The [Seized by Terror — Aftermath & Regrouping Lab]({{ '/scenarios/seized-terror-aftermath-lab/' | relative_url }}) adds the carried-card, follower-control, regrouping and Promptings of Wisdom rules.
