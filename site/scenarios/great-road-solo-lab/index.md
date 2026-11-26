---
layout: page
title: Great-road in Solo — Hazard Draw Lab
permalink: /scenarios/great-road-solo-lab/
---

# Great-road in Solo — Hazard Draw Lab

This optional card-specific exercise resolves a practical question in the fixed Hero Resource list: how should **Great-road** interact with the printed solitaire Hazard-draw formula?

Keep the teaching decks unchanged. Great-road remains in the 30-card Resource list and the 36-card Hero play deck. This lab explains when to use it, why it is risky, and what the return to a Haven actually does.

## The rules chain

1. **Great-road's card text:** it is playable at the end of the Organization Phase on a company at a Haven. The Hazard player may draw up to twice the normal number of cards for that company during its Movement/Hazard Phase. At the end of the turn, the company may replace its site card with the Haven where it began; this is movement with no Movement/Hazard Phase.
2. **Erratum:** the current wording is **“up to twice”**, not an automatic “twice”.
3. **Great-road draw ruling:** the Collected Rulings File says Great-road modifies the normal draw number shown on the site card.
4. **Printed solitaire procedure:** the Hazard side draws **2 + twice the normal Hazard draw number** for the relevant site.

**Academy working interpretation:** apply Great-road to the normal site-card Hazard draw first, then apply the solitaire formula. I found no published ruling that explicitly combines Great-road with the printed solitaire formula, so this is a transparent Academy interpretation, not a claim that CoE has issued a direct solo-specific ruling.

## Worked expedition: Rivendell to Moria

**Company:** Thorin II, Dori, Kíli, Glóin and Óin.

**Starting site:** Rivendell (Haven).

**Destination:** Moria.

**Legal teaching route:** Rhudaur → Hollin → Redhorn Gate. It contains three regions, including the origin and destination regions. Check the adjacency of each pair on the physical Region cards before declaring it.

Moria's Hero site card shows a normal Hazard draw of **3** and a Hero draw of **2**.

| Step | Calculation | Result |
|---|---|---:|
| Normal Hazard draw at Moria | Printed site-card number | 3 |
| Great-road maximum | 3 × 2 | 6 |
| Solitaire Hazard draw | 2 + (2 × 6) | **14** |
| Five-Dwarf base Hazard Limit | Company size or 2, whichever is greater | **5** |
| Hero draw | Moria's Hero draw number | Up to **2** |

Great-road modifies the Hazard side's draw only. It does not change the Hero player's draw, the route's legality, the site automatic attack or the company's Hazard Limit.

### Why the result is 14, not 16

Do not first calculate the ordinary solo draw of 8 and then double that result. The Great-road ruling treats it as a modifier to the **normal site-card draw**: Moria's 3 becomes up to 6. The printed solitaire formula is then applied to 6:

**2 + (2 × 6) = 14.**

Because Great-road says “up to twice”, the Hazard side could draw fewer than 14. For the Academy's solo procedure, which directs you to choose the most disadvantageous legal Hazard sequence, use the maximum draw unless a specific situation gives a reason not to.

## What happens after the Movement/Hazard Phase?

Great-road's return is an End-of-Turn movement effect. If you choose to use it:

- The company returns to **Rivendell**, the Haven where it began this turn.
- The return is movement **without** another Movement/Hazard Phase. There is no second Hazard draw, no second Hero movement draw and no second Site Phase.
- If you entered Moria and successfully played Book of Mazarbul, the Book stays with its bearer. It is not stored merely because the company returned to Rivendell.
- Successfully playing the Book taps Moria. A tapped non-Haven site is discarded when the company leaves; if Moria was not tapped, its site card returns to the Location deck.
- If you did not enter Moria, you do not face its automatic attack and cannot attempt the Book. Great-road can still return the company to Rivendell at the end of the turn.

The site automatic attack at Moria is **Orcs — four strikes with 7 prowess**. It is faced only if the company chooses to enter and explore Moria during the Site Phase. It is separate from the Hazard draw and does not consume a Hazard Limit slot.

## Exercise — decide whether to play Great-road

Answer these before opening the model answer:

1. Why is Great-road legal at Rivendell, and when must you play it?
2. What is the maximum solo Hazard draw to Moria with Great-road?
3. What is the five-Dwarf Hazard Limit?
4. How many cards may the Hero player draw from Moria?
5. Does Great-road let you ignore the three-region route or the region-adjacency rules?
6. If the company does not enter Moria, does it face the Orc automatic attack? Can it play Book of Mazarbul?
7. If the company plays the Book successfully, what happens to the Book and to Moria when the company returns to Rivendell?
8. Does Great-road's return cause another Movement/Hazard Phase?
9. Compare the Great-road option with a normal eight-card solo draw to Moria. What does the extra draw change, and what does it not change?

## How much more dangerous is the extra draw?

The fixed Hazard deck contains **16 creature cards in 30 cards**. All 16 are legal candidates on the Rivendell–Moria route or at Moria itself. For a fresh, shuffled deck, the chance of drawing at least five creatures is:

| Hazard cards drawn | Chance of at least five creature cards |
|---:|---:|
| 8 (normal solo draw) | 42.6% |
| 14 (Great-road maximum) | 98.6% |

This is a hypergeometric calculation without replacement. It does **not** predict which five Hazards the solo side will choose or whether the company will survive. It shows that a 14-card draw almost always gives the Hazard side the option of filling all five ordinary Hazard slots with creature cards before considering event combinations.

The Hazard Limit remains five. Drawing fourteen does not permit fourteen ordinary Hazard plays. Twilight, if drawn, remains outside the Hazard Limit but still needs a legal Environment target.

## Baseline deck instruction

- Keep Great-road in the fixed 30-card Hero Resource list.
- Do **not** remove it from the deck to make Game 1 easier.
- For baseline Game 1, do not play it; the first expedition is designed to teach the ordinary eight-card Moria solo draw.
- If Great-road appears in your hand and you are not planning a later sortie-and-return, discard it at a normal hand reset. It is a situational Resource, not a mandatory play.

## Related lessons

- [Hero Deck Construction]({{ '/decks/hero-deck/' | relative_url }})
- [Hero Resource Timing Workshop]({{ '/scenarios/hero-resource-practice/' | relative_url }})
- [Hazard Deck Construction]({{ '/decks/hazard-deck/' | relative_url }})
- [Which Solo Rules Are We Using?]({{ '/reference/solo-ruleset/' | relative_url }})
- [Free / Player-Directed Movement Guide]({{ '/reference/free-movement/' | relative_url }})
