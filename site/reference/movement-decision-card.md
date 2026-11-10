---
layout: page
title: Movement Decision Card
permalink: /reference/movement-decision-card/
---

# Movement Decision Card

Keep this page open beside the table. It is the short version of the [Free / Player-Directed Movement Guide]({{ '/reference/free-movement/' | relative_url }}). Use it after you understand the basic turn sequence.

## 1. Choose the destination during Organization

1. Decide what the company is trying to achieve: acquire an item, recruit a faction or ally, store an item later, or recover.
2. Choose the destination site card and place it face-down with the company.
3. Decide which movement method will make that destination legal: Starter Movement or Region Movement.
4. Do not assume the shortest route is the safest route. The route also determines which Hazard creatures can be keyed against the company.

Movement is declared in the Organization Phase. Its legality is checked when the new site is revealed in the Movement/Hazard Phase. If the declared movement is illegal, the company stays at its origin and still conducts a Movement/Hazard Phase.

## 2. Is Starter Movement legal?

Starter Movement is legal if at least one of these tests is true:

- The current site is a Haven and the new site's card lists that Haven as its nearest Haven.
- The new site is a Haven and the current site's card lists that Haven as its nearest Haven.
- Both sites are Havens and each site's card lists a site path to the other.

If none applies, use another legal movement method. Do not invent a Haven connection because two sites look close on the map.

**Why Starter Movement can be safer:** its site path identifies the region types and names the origin and destination regions, but not the names of intervening regions. Region Movement identifies the names and types of every region in the path. That gives the Hazard side more named-region keys when you use Region Movement.

## 3. Check Region Movement

For normal Region Movement:

- Use no more than **four consecutive regions**, counting the origin and destination regions.
- Do not repeat a region.
- Every consecutive pair must be adjacent according to the Region cards / official map.
- The path must be legal when movement is declared in the Organization Phase.
- When the new site is revealed, declare the actual region sequence. It can differ from the site's printed site path, but it must still be legal.

The origin and destination both count. A journey through five regions is not a legal single normal Region Movement, even if the middle three regions look like a direct corridor.

## 4. Calculate the three numbers separately

| Number | How to calculate it | What it controls |
|---|---|---|
| Hero draw | The lighter number on the relevant site card, if the moving company contains an avatar or a character with mind 3 or greater. Draw at least one if eligible, unless an effect reduces it below one. | Cards drawn by the Hero player from the Hero play deck. |
| Normal Hazard draw | The darker number on the relevant site card. The Hazard player normally draws at least one if the company moves, unless an effect reduces it below one. | The multiplayer baseline used by the solo formula. |
| Base Hazard Limit | Current company size or 2, whichever is greater. It is fixed for that company's Movement/Hazard Phase. | Maximum number of ordinary Hazard plays that can be made, before relevant modifiers. |

**Which site's numbers?**

- Moving to a non-Haven: use the new site's numbers.
- Moving to a Haven: use the site of origin's numbers.
- Not moving: the standard movement rules do not draw movement cards. The printed solo extension does not clearly specify a universal extra draw for a stationary company; the Academy treats that edge case as scenario-specific rather than inventing a number.

**Solo Hazard draw:** use **2 + (2 × the normal Hazard draw)**. This is a draw count, not the Hazard Limit. For the Academy's first-play procedure, draw from the separate Hazard deck, then play the most disadvantageous legal cards within the company's Hazard Limit. The Academy uses the independent *My Solo Rules* procedure for unplayed draws: discard them at the end of the phase and reshuffle the Hazard discard when the Hazard deck is exhausted. That discard handling is a supplementary solo procedure, not a claim that the printed solo paragraph says the same thing.

The site automatic attack is a separate Site Phase encounter if the company enters. It is not one of the drawn Hazard cards and does not use a Hazard Limit slot. A Hazard event that modifies an automatic attack is still a Hazard play and normally counts against the limit.

## 5. Worked route comparison: Moria to Blue Mountain Dwarf-hold

A direct Moria → Blue Mountain Dwarf-hold Region Movement would use five regions and is illegal as one normal movement. Two practical two-leg routes are available:

| Route | Leg 1 | Leg 2 | Total solo Hazard draws | Strategic trade-off |
|---|---|---|---:|---|
| Non-Haven route | Moria → Goblin-gate: 4 regions; normal Hazard draw 2; solo draw 6 | Goblin-gate → Blue Mountain: 4 regions; normal Hazard draw 1; solo draw 4 | **10** | Avoids a Haven detour, but gives no Haven recovery between legs. Goblin-gate's automatic attack is faced only if the company enters. |
| Haven recovery route | Moria → Rivendell: destination is a Haven, so use Moria's numbers; normal Hazard draw 3; solo draw 8 | Rivendell → Blue Mountain: 3 regions; normal Hazard draw 1; solo draw 4 | **12** | Costs two more solo Hazard draws, but offers a Haven recovery and organization opportunity. |

The lower-draw route is not automatically the better route. Compare the company's wounds, tapped characters, remaining avoidance cards, the value of entering Goblin-gate, and whether a Haven recovery is worth the extra exposure.

## 6. Before the Hazard side plays

For each company, ask in this order:

1. What is the exact declared site path?
2. Which region names and region types does it expose?
3. What is the destination site's type and name?
4. Which creatures match an exposed region type, named region, site type or named site?
5. Which event cards have a legal target and timing window?
6. What is the current Hazard Limit, after any modifiers?
7. Which legal sequence is most disadvantageous to this company?

Do not confuse a site type with a region type. Moria and Goblin-gate are both Shadow-hold sites; neither is a Shadow-land region. A Shadow-hold site does not create a Shadow-land region in the site path. A named-site permission such as Watcher in the Water's permission to be played at Moria does not automatically apply at Goblin-gate.

## 7. Quick self-check

- **Rivendell → Moria:** the Region Movement path is Rhudaur → Hollin → Redhorn Gate. It has three regions. The normal Hazard draw is 3, so the solo Hazard draw is 8. The five-Dwarf company has a base Hazard Limit of 5.
- **Moria → Rivendell:** Rivendell is a Haven, so use Moria's site numbers, not Rivendell's. The solo Hazard draw is 8.
- **Moria → Goblin-gate:** Redhorn Gate → Hollin → Rhudaur → High Pass is four regions. The normal Hazard draw is 2, so the solo draw is 6.
- **Goblin-gate → Blue Mountain Dwarf-hold:** High Pass → Rhudaur → Arthedain → Númeriador is four regions. The normal Hazard draw is 1, so the solo draw is 4.
- **Moria → Blue Mountain Dwarf-hold in one leg:** five regions; illegal as one normal Region Movement.

## Sources and status

The movement tests, site-path procedure, draw timing and Hazard Limit are based on the [Council of Elrond Official Game Rules](https://councilofelrond.org/rules/), especially sections 2.II.7 and 2.IV.i–vii. The solo draw multiplier is from the printed solitaire rules reproduced in the Academy's [Solo Rules Reference]({{ '/reference/solo-ruleset/' | relative_url }}). The unplayed-Hazard discard procedure is explicitly identified as the Academy's chosen supplementary procedure from [My Solo Rules](https://meccg.wordpress.com/my-solo-rules/).

**Next:** return to the [Free Movement Guide]({{ '/reference/free-movement/' | relative_url }}) for detailed site-path examples, then use the [Expedition Planner]({{ '/routes/expedition-planner/' | relative_url }}) to compare routes before committing a company.
