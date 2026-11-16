---
layout: page
title: Hero Opening Hand & Access Lab
permalink: /scenarios/hero-opening-hand-lab/
---

# Hero Opening Hand & Access Lab

This lab answers a practical question before the first expedition: **what is the 36-card Hero deck likely to give you, and what should you do when the card you want is not in your opening hand?**

It uses the fixed Academy list: 30 Resources, five non-Wizard characters and one Gandalf. It does not change the deck or add a mulligan.

## 1. The five-card opening hand

The printed solitaire procedure sets the base hand target to five. The Academy uses no mulligan. Shuffle the full 36-card Hero play deck and draw five. Card effects can modify the target during play.

The starting company is already in play: Thorin II, Dori, Kíli, Glóin and Óin. Those five Dwarves are not drawn from the 36-card deck. The six character/Wizard cards in the play deck are additional cards that may be played later when legal.

## 2. Opening-hand access

The 30 Resources contain 12 site-playable cards (eight Items, two Factions and two Allies) and 18 supporting Resource events. The other six cards are characters/Wizard.

| Group | Copies in 36 | Expected in first 5 | Chance of at least one in first 5 |
|---|---:|---:|---:|
| One specific card (Book of Mazarbûl or Gandalf) | 1 | 0.14 | **13.9%** |
| A two-copy card (A Friend or Three) | 2 | 0.28 | **26.2%** |
| A three-copy card (Concealment) | 3 | 0.42 | **37.0%** |
| Any of the six character/Wizard cards | 6 | 0.83 | **62.2%** |
| Any of the 12 site-playable Resources | 12 | 1.67 | **88.7%** |
| Any Sage-capable card (Gandalf, Balin, Celeborn) | 3 | 0.42 | **37.0%** |

These are exact draw-without-replacement probabilities for a five-card sample from 36, rounded to one decimal place. The chance of seeing at least one of k copies in n cards is 1 − C(36 − k, n) / C(36, n).

The key lesson: **a one-copy card is not guaranteed**. The opening hand has only a 13.9% chance of containing the Book and the same chance of containing Gandalf. That is normal for a singleton, not evidence by itself that the deck needs another copy.

## 3. What the first Moria movement adds

The Hero version of Moria is **3/2** (opponent draws / you draw). The five starting Dwarves qualify for the Hero draw because they include characters with mind 3 or greater. If you take the full two-card Hero draw, you have seen seven distinct cards:

| Group | First 5 seen | After 2 more Hero cards (7 seen) |
|---|---:|---:|
| One specific one-copy card | 13.9% | **19.4%** |
| At least one of a two-copy card | 26.2% | **35.6%** |
| At least one of a three-copy card | 37.0% | **48.8%** |
| Any of the six character/Wizard cards | 62.2% | **75.6%** |
| Any of the 12 site-playable Resources | 88.7% | **95.9%** |
| Any Sage-capable card | 37.0% | **48.8%** |

“Seen” means the card appeared in the opening hand or the two-card draw. The Hero hand is reset to its current target of five after the company's Movement/Hazard Phase. You choose which cards to retain; the table does not mean all seven remain in hand.

The solo Hazard side separately draws **2 + (2 × 3) = 8** cards from its own Hazard deck. The five-Dwarf base Hazard Limit is **5**. These are separate calculations; the eight Hazards never enter the Hero hand.

If Gandalf joins the Dwarves before they move, the company has six characters and its base Hazard Limit becomes **6**. If he is elsewhere or travels separately, do not add him to the Dwarves' company size; resolve each company's phase and limit separately.

## 4. The Book and the Sage are separate pieces of access

Book of Mazarbûl is a unique Special Item, playable only at Moria. It is worth 1 MP in play, can be stored at a Dwarf-hold for 5 MPs, and gives its bearer 2 corruption points. If its bearer is a Sage, the Book may be tapped during the Organization Phase to increase the Hero hand size by one until the next untap phase.

The Sage must actually be in play and **bear the Book**. Holding Gandalf, Balin or Celeborn in hand does not activate the ability. The five starting Dwarves have no Sage skill.

If a Dwarf acquires the Book before a Sage joins, its normal play and storage value still apply; the hand-size ability is simply unavailable. Transferring it later to a Sage at the same site requires a corruption check for the initial bearer. It is not an automatic or free transfer.

## 5. The first Organization Phase matters

Only one character action is available in the Organization Phase. You cannot play Gandalf and Balin in the same phase.

If Gandalf is in the opening hand, he may be revealed at Rivendell. If he joins the five Dwarves before movement, the company becomes six characters and its base Hazard Limit becomes six. That gives the Hazard side one additional ordinary play if enough legal cards are available. In return, Gandalf supplies Sage, Scout and Diplomat skills, +1 to his own corruption checks, and a possible Sage bearer for the Book.

This is a choice, not an automatic instruction. The Wizard avatar is valuable and should not be exposed without considering the route and the company's ability to protect him. The five-Dwarf company remains valid if Gandalf is not yet in play.

## 6. Three constructed practice hands

These are practice hands, not scripted draws.

### Hand A — the Book is present
- Book of Mazarbûl
- Gandalf
- Concealment
- Fellowship
- A Friend or Three

Decide whether to play Gandalf at Rivendell, what that does to company size and Hazard Limit, which card is the mission objective, and why Concealment should be retained until an attack exists. Does Gandalf's presence activate the Book before he bears it?

### Hand B — a Sage backup, but no Wizard
- Book of Mazarbûl
- Balin
- Concealment
- Risky Blow
- Marvels Told

Can Balin be played at Rivendell? What happens to the Hazard Limit if he joins? Can Marvels Told be used before Balin is in play? Can Balin use the Book's Sage ability if he later bears it? What is required to transfer the Book from a Dwarf?

### Hand C — competing objectives, no Book
- Gollum
- Iron Hill Dwarves
- Fíli
- Not at Home
- Fellowship

The Book mission is not immediately achievable from this hand. Gollum points to Goblin-gate; Iron Hill Dwarves points to Iron Hill Dwarf-hold. Why is Not at Home not a universal answer to Moria's Orc automatic attack? What site, route, influence and company information is needed before choosing either objective?

Use the [Resource Route Planner]({{ '/scenarios/resource-route-planner/' | relative_url }}) for objective sites and the [Free Movement guide]({{ '/reference/free-movement/' | relative_url }}) for legal routes.

## 7. The practical hand-selection rule

Sort the five cards into:
1. **Current objective** — can complete the mission being pursued.
2. **Protection** — has a legal response to a threat that may actually occur.
3. **Future objective** — needs a later site or company skill.
4. **Uncertain** — its text, timing, target or site condition still needs checking.

Before moving, check the Resource's playable site, the 15-card Hero Location deck, movement legality, both normal draw numbers, the solo Hazard draw, company Hazard Limit, automatic attack and whether the company can afford to enter.

A site-playable card is a reason to consider a destination, not an order to travel there. If the Book is absent, do not pretend it is in hand. Choose another objective, use a legal draw effect, or make a deliberate search expedition—and record which plan you chose.

A stationary company makes no normal Hero movement draw. Under the Academy's literal application of the printed solo formula, it still produces two Hazard draws; the interpretation and its scenario-specific exception are documented in the [solo rules reference]({{ '/reference/solo-ruleset/' | relative_url }}). Staying put is not a way to cycle through the Hero deck for free.

## 8. What this says about the fixed deck

The 36-card deck has a high chance of presenting at least one site-playable Resource early, but a low chance of presenting any named singleton. Keep the list fixed for the first three recorded games. Record a card as “not seen” separately from “seen but unusable”; change a card only after repeated evidence.

The same discipline applies to the Hazard deck: keep its 30-card baseline unchanged while recording legal plays, route-inactive draws, wounds, taps, corruption checks and objective delays.

## References

- [The Wizards — Solitaire Rules](https://meccg.com/rules/by-expansion/the-wizards/) — five-card solitaire hand and separate Hazard draw.
- [Council of Elrond — Official Game Rules](https://www.councilofelrond.org/rules/) — starting hands, no mulligan, character actions, movement draws, Hazard Limits, item transfer and storage.
- [Council of Elrond — Official Card Database](https://www.councilofelrond.org/cards/) — current card text and errata.
- [Hero Deck Construction]({{ '/decks/hero-deck/' | relative_url }}) — exact list and Resource audit.
- [Resource Route Planner]({{ '/scenarios/resource-route-planner/' | relative_url }}) — objective sites and priorities.
- [Movement Draw Lab]({{ '/scenarios/movement-draw-lab/' | relative_url }}) — Hero draw, solo Hazard draw and Hazard Limit.

---

<div class="next-lesson">

**NEXT: Use the hand you actually drew**

[Open the Hero deck list →]({{ '/decks/hero-deck/' | relative_url }}) · [Plan a Resource objective →]({{ '/scenarios/resource-route-planner/' | relative_url }})

</div>
