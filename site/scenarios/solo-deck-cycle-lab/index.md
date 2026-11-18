---
layout: page
title: Solo Deck Cycle Lab
permalink: /scenarios/solo-deck-cycle-lab/
---

# Solo Deck Cycle Lab — hand resets, saved cards and recycling

This lab teaches how the Academy's two shuffled play piles behave across a complete expedition. It does **not** change either teaching deck. Use the fixed 36-card Hero play deck, separate 30-card Hazard deck and corrected 15-card Hero Location deck.

## 1. Keep the card zones separate

| Zone | What belongs there | What happens to it |
|---|---|---|
| Hero play deck | 30 Resources, five non-Wizard characters and one Gandalf | Supplies the Hero hand and normal Hero movement draws |
| Hero hand | Cards drawn from the Hero play deck | Reset after each company's Movement/Hazard Phase and again at End of Turn |
| Hero discard pile | Hero cards discarded or played and later discarded | Kept separate from the Hazard discard |
| Hazard draw deck | The 30-card Hazard teaching list | Supplies the solo Hazard draw for each company's Movement/Hazard Phase |
| Hazard discard pile | Unplayed drawn Hazards under the Academy supplement, plus Hazards discarded after use | Shuffled to form a new Hazard deck when the draw deck is exhausted |
| Saved-for-Doors-of-Night area | A Hazard that cannot yet be played because it requires Doors of Night | Kept aside until a Doors of Night is drawn |
| Hazard cards in play | Long-events and permanent-events whose effects continue | Stay in play until their text or normal timing discards them |
| Hero marshalling-point pile | Stored Resources and, in the full scoring game, defeated creatures | Not part of either draw deck |

Never combine the Hero discard pile and Hazard discard pile. Hazard cards drawn for a company do not enter the Hero hand.

## 2. The two five-card Hero-hand resets

The printed solitaire rules replace the normal eight-card hand target with **five** whenever a hand would normally be drawn up or discarded down to eight.

1. Start with five Hero cards.
2. After each company's Movement/Hazard Phase, reset the Hero hand to five (apply any active hand-size modifier).
3. Resolve the Site Phase and the rest of the turn normally.
4. At the End-of-Turn Phase, reset the Hero hand to five again.

The hand is not capped at five every second of the turn. If the Hero player draws two cards during movement while already holding five, the hand can temporarily contain seven. Keep those cards while the Movement/Hazard Phase is being resolved; reset when that phase ends, before the Site Phase. After the Site Phase, the End-of-Turn Phase is the second reset.

The active Gandalf baseline has a target of five. The Book's hand-size ability is an action, not a passive bonus: its bearer must be a Sage and you must tap the Book during the Organization Phase. The +1 lasts only until the next Untap Phase. If the Book is not tapped, keep the base target of five. Gandalf's +1 corruption-check modifier does not itself increase hand size.

## 3. Keep the three movement numbers separate

For each company, determine the ordinary site-card draw number first. A non-Haven destination normally supplies the number; a Haven destination uses the site of origin's number. Then apply the solo Hazard formula.

**Moria example — five starting Dwarves**

| Measure | Result |
|---|---:|
| Moria's normal Hazard-player draw number | 3 |
| Hero draw from the lighter site-card box | Up to 2 |
| Solo Hazard draw | 2 + (2 × 3) = **8** |
| Base Hazard Limit | **5** |

Eight Hazard cards are available to evaluate. The five-card Hazard Limit is the maximum number of ordinary limit-counting Hazard plays against this company in this phase. The draw does not increase the limit.

## 4. Route planning: two non-Haven legs, two separate Hazard phases

Use the Academy's connected route after the Book expedition:

**Moria → Goblin-gate → Blue Mountain Dwarf-hold**

| Leg | Normal Hazard draw number | Hero draw | Solo Hazard draw | Five-Dwarf base Hazard Limit |
|---|---:|---:|---:|---:|
| Moria → Goblin-gate | 2 | Up to 1 | **6** | **5** |
| Goblin-gate → Blue Mountain Dwarf-hold | 1 | Up to 1 | **4** | **5** |
| **Across both legs** | — | Up to 2 | **10 cards across two phases** | **5 in each phase, not 10 at once** |

Each leg has its own site path, Hazard draw, legality check and Hazard Limit. The second phase does not inherit unused slots from the first. If the company remains five characters, its base limit is five again; if its size changes before the next phase, calculate the new limit at the start of that phase.

This is why Region Movement does not mean one enormous Hazard draw for the whole journey. The route and site path determine which creatures can be keyed; the destination's normal draw number determines the solo draw volume. See the [Free Movement guide]({{ '/reference/free-movement/' | relative_url }}) and [Expedition Planner]({{ '/routes/expedition-planner/' | relative_url }}) for the physical region sequence and route decisions.

## 5. What happens to the Hazard cards after the phase?

The printed *The Wizards* solitaire paragraph says to draw 2 plus twice the normal Hazard draw and play as many drawn Hazards as possible within the company's Hazard Limit, choosing the most disadvantageous legal plays. It also includes the special Doors of Night instruction below.

The printed paragraph does **not** explicitly state what happens to ordinary drawn-but-unplayed Hazards. The Academy adopts the supplementary handling in [My Solo Rules](https://meccg.wordpress.com/my-solo-rules/): discard those unplayed cards at the end of that company's Movement/Hazard Phase. If the Hazard draw deck is exhausted and more cards must be drawn, shuffle the Hazard discard pile to make a new draw deck.

Do not discard a card that the official solitaire rule tells you to save for Doors of Night. Do not shuffle a long-event or permanent-event that is still in play into the Hazard deck.

## 6. The Doors of Night exception

The official *The Wizards* solitaire paragraph says that **Hazard cards requiring Doors of Night are saved and played when a Doors of Night is drawn**. This is a specific exception to treating every unplayed card as an ordinary end-of-phase discard.

For the active Academy baseline:

- The 30-card Hazard deck contains no Doors of Night.
- None of its cards requires Doors of Night before it can be played.
- Wake of War is still playable without Doors of Night. Its normal Wolf, Spider and Animal bonus applies; Doors of Night only improves its Wolf bonus further.

If a later Hazard variant includes cards that actually require Doors of Night, keep those cards in a clearly marked saved area. When Doors of Night is drawn, bring them into consideration and apply their own text and the current Hazard Limit. A saved card is not a free extra play.

## 7. Mission mode and scoring mode recycle creatures differently

- **Book of Mazarbûl tutorial:** this is not a kill-MP challenge. The Academy follows its selected solo supplement: defeated non-unique creatures go to the Hazard discard and can return when the deck is recycled. Follow normal uniqueness rules; a unique creature cannot simply be brought back.
- **Full solo scoring game:** use normal scoring handling. Defeated Hazard creatures go to the Hero marshalling-point pile and leave the Hazard cycle. The Hazard deck therefore becomes progressively less creature-heavy as creatures are defeated.

Do not carry the tutorial's creature-recycling exception into the full scoring game. The [Full Solo Scoring Trial]({{ '/scenarios/full-solo-scoring-trial/' | relative_url }}) explains the change.

## 8. Practice — answer before opening the key

1. **Eight drawn, five slots.** At Moria you draw eight Hazards for a five-Dwarf company. Five cards have legal, useful plays and three do not. Where do the three unplayed cards go?
2. **A card needs Doors of Night.** A future Hazard variant contains a card whose text requires Doors of Night. What do you do if it is drawn before Doors of Night?
3. **Wake of War.** Doors of Night is not in play. Is Wake of War unusable, or does it still have its normal effect?
4. **The deck runs out mid-draw.** You need eight cards but only three remain in the Hazard draw deck. What happens next?
5. **Two route legs.** Calculate the solo Hazard draws and limits for Moria → Goblin-gate → Blue Mountain Dwarf-hold. Explain why the two limits do not combine.
6. **Two hand resets.** You finish the Movement/Hazard Phase with seven Hero cards, then play a Resource during the Site Phase. When do you reset to five?
7. **A defeated Cave Worm.** Explain where a defeated non-unique creature goes in the Book tutorial and where it goes in the full scoring game.

Write your answers down, then open the [model answer]({{ '/scenarios/solo-deck-cycle-lab/answer-key/' | relative_url }}).

## Rules references

- [The Wizards — Solitaire Rules](https://meccg.com/rules/by-expansion/the-wizards/) — five-card hand, separate Hazard deck, 2 + twice draw, most-disadvantageous legal play and the Doors of Night saved-card rule.
- [Council of Elrond Official Game Rules](https://www.councilofelrond.org/rules/) — company Movement/Hazard Phases, normal movement draws, Hazard Limit and card timing.
- [My Solo Rules](https://meccg.wordpress.com/my-solo-rules/) — supplementary discard of unplayed drawn Hazards and Hazard-deck recycling adopted by this Academy.

---

<div class="next-lesson">

**NEXT: Test the actual Hazard choices**

Complete the [Hazard Legality Workshop]({{ '/scenarios/hazard-legality-workshop/' | relative_url }}) after this deck-handling lesson.

</div>
