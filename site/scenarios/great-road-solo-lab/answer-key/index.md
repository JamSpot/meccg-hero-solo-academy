---
layout: page
title: Great-road in Solo — Model Answer
permalink: /scenarios/great-road-solo-lab/answer-key/
---

# Great-road in Solo — model answer

Use this after completing the [Great-road Solo Draw Lab]({{ '/scenarios/great-road-solo-lab/' | relative_url }}).

## The draw calculation

Moria's normal Hazard draw number is **3**.

Great-road allows the Hazard side to draw up to twice the normal number:

**3 × 2 = 6.**

The printed solitaire rule then applies:

**2 + (2 × 6) = 14 Hazard cards.**

The Academy uses **14 as the maximum draw** for this combination. It is not 16: Great-road modifies the normal site-card draw before the solo formula is applied. This follows the CRF ruling that Great-road modifies the normal draw number; the printed solitaire procedure then doubles that modified number and adds two.

The five-Dwarf company still has a base Hazard Limit of **5**. Great-road changes the number of cards available to the Hazard side, not the number of limit-counting plays. The Hero player still draws up to **2** from Moria's Hero draw number.

## Movement and return

The route Rhudaur → Hollin → Redhorn Gate is a legal three-region teaching route if the physical Region cards confirm each adjacency. Great-road does not replace or waive movement rules.

Great-road is played at the **end of the Organization Phase** while the company is at Rivendell, a Haven. The company then completes its normal Movement/Hazard Phase and may enter Moria during the Site Phase.

At the end of the turn, the company may return to Rivendell. The card explicitly makes this movement occur **without** another Movement/Hazard Phase:

- no second Hazard draw;
- no second Hero movement draw;
- no second Site Phase.

If Book of Mazarbul was successfully played, it stays with its bearer. Moria is tapped and, as a tapped non-Haven site being left, is discarded. If Moria was not tapped, its site card returns to the Location deck.

If the company chooses not to enter Moria, it does not face the site's four Orc strikes at 7 prowess and cannot attempt to play the Book. The return to Rivendell is still available at the end of the turn.

## Why the probability changes so sharply

The fixed Hazard deck has 16 creature cards among 30 cards. On the Rivendell–Moria route, all 16 are legal candidates either through the declared Wilderness/Redhorn Gate path or because Watcher in the Water may be played at Moria.

For a fresh shuffled deck, the probability of drawing at least five creatures is:

| Draw size | Calculation result |
|---:|---:|
| 8 cards | 42.6% |
| 14 cards | 98.6% |

The probability is calculated without replacement:

`P(X ≥ 5) = sum from k = 5 to min(16, n) of [C(16, k) × C(14, n − k)] / C(30, n).`

It means the 14-card Great-road draw almost always provides at least five creature cards from which the Hazard side can choose. It does not mean that five creatures must be played: the solo player should still choose the most disadvantageous **legal** combination, which may include support events. It also does not increase the five-card Hazard Limit.

Twilight is outside the Hazard Limit, but in the baseline Hero deck it normally has no Environment Resource target to cancel. It is not a free sixth attack.

## Recommended decision

For the first baseline game, use normal Region Movement and the standard **8-card** solo Hazard draw. That keeps the first expedition focused on learning movement, Hazard selection, site entry and the Book attempt.

Keep Great-road in the deck. Use it later when the return to a Haven is valuable enough to justify the much larger Hazard selection. It is a powerful tactical option, but it is not a free safe shortcut.

## Rules confidence and sources

**Directly supported by published rules/rulings:**

- Great-road is playable at the end of the Organization Phase on a company at a Haven, allows up to twice the normal draw, and returns the company to its starting Haven at End of Turn without a second Movement/Hazard Phase. See the [official card database](https://www.councilofelrond.org/cards/).
- The erratum changes “opponent draws twice” to “opponent draws up to twice”; the return is movement without a Movement/Hazard Phase. See [CRF 17 — Great-road](https://meccg.es/reglas/collected-rulings-and-errata-crf/crf-17/card-errata-and-rulings/).
- The Great-road ruling says it modifies the normal site-card draw number. See the [MeCCG Ruling Digests PDF](https://meccg.es/meta/rules/MeCCG%20Ruling%20Digests%20v1.0.pdf), Ruling Digest #108.
- The printed solitaire procedure uses 2 + twice the normal Hazard draw number. See [The Wizards — Solitaire Rules](https://meccg.com/rules/by-expansion/the-wizards/).

**Academy interpretation:** apply Great-road's normal-draw modifier before the solitaire multiplier, producing 14 at Moria. I found no published ruling that explicitly addresses this exact Great-road/solitaire combination. If a direct ruling is found, update this lab and the Hero Resource guide together.
