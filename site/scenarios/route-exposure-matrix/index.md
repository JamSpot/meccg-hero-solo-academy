---
layout: page
title: Route Exposure Matrix
permalink: /scenarios/route-exposure-matrix/
---

# Route Exposure Matrix — what can the Hazard side actually play?

Use this with the locked 30-card Challenge Deck C-derived Hazard list. It answers a practical question: **before choosing the strongest Hazard, which cards are actually legal against this company's declared route and destination?**

This is a legality audit, not a prediction of the random draw. A card shown as a candidate must still be in the drawn hand, meet its target and timing requirements, and be resolved according to its current text and errata.

## 1. The three connected teaching journeys

The same five-Dwarf company is used for the route comparison.

| Journey | Region Movement site path | Regions | Region types | Site-card numbers (Hazard / Hero) | Hero draw | Solo Hazard draw | Base Hazard Limit | Automatic attack if entered |
|---|---|---:|---|---:|---:|---:|---:|---|
| Rivendell → Moria | Rhudaur → Hollin → Redhorn Gate | 3 | {w}{w}{w} | 3/2 | Up to 2 | **8** | **5** | Orcs — 4 strikes at 7 |
| Moria → Goblin-gate | Redhorn Gate → Hollin → Rhudaur → High Pass | 4 | {w}{w}{w}{w} | 2/1 | Up to 1 | **6** | **5** | Orcs — 3 strikes at 6 |
| Goblin-gate → Blue Mountain Dwarf-hold | High Pass → Rhudaur → Arthedain → Númeriador | 4 | {w}{w}{w}{w} | 1/1 | Up to 1 | **4** | **5** | None |

The notation is **normal Hazard-player draw / Hero-player draw** from the Hero site card. The Academy's selected solitaire procedure uses **Solo Hazard draw = 2 + (2 × normal Hazard draw)**.

The five-Dwarf company has a base Hazard Limit of five. Drawing eight cards at Moria does not allow eight ordinary Hazard plays. The Hero draw is separate: this company qualifies because it contains characters of mind 3 or greater, and must draw at least one, up to the lighter number shown on the site card. Reconcile the Hero hand to five after the Movement/Hazard Phase.

The site automatic attack is faced only if the company enters during its Site Phase. It is not a Hazard card and does not consume a Hazard Limit slot. A Hazard that modifies an automatic attack is a separate Hazard play and normally does consume a slot.

## 2. Baseline Hazard legality matrix

All three declared paths contain only Wilderness regions. The route-specific names change, but the region-type key is present on every leg.

| Baseline card | What makes it a candidate? | Rivendell → Moria | Moria → Goblin-gate | Goblin-gate → Blue Mountain |
|---|---|---|---|---|
| **Cave Worm** | Named-region key. The relevant names are Redhorn Gate, High Pass and Númeriador. It is a Drake, not a Dragon. | Yes — Redhorn Gate | Yes — Redhorn Gate / High Pass | Yes — High Pass / Númeriador |
| **Giant Spiders** | Double-Wilderness key. Its additional site-type keys are restricted to specified Mirkwood regions and do not create a general Moria site key. | Yes | Yes | Yes |
| **Lesser Spiders** | Wilderness or Shadow-land region key; it also has a separate Ruins & Lairs site key. | Yes — via {w} | Yes — via {w} | Yes — via {w} |
| **Neeker-breekers** | Wilderness is one of its region keys. It does not affect Wizards; each affected character faces one strike at prowess equal to that character's mind, and a character who would be wounded is tapped instead. | Yes — via {w} | Yes — via {w} | Yes — via {w} |
| **Wargs** | Border-land, Wilderness or Shadow-land region key. | Yes — via {w} | Yes — via {w} | Yes — via {w} |
| **Watcher in the Water** | Double-Wilderness key; it also has explicit permission to be played at Moria. | Yes — both routes satisfy a key | Yes — via double {w} | Yes — via double {w} |
| **Despair of the Heart** | Target restriction, not a route key: target a non-Hobbit, non-Wizard, non-Ringwraith character. The target receives 2 corruption points and makes a corruption check each time a character in his company becomes wounded. During Organization, the target may tap and roll; a result greater than 4 removes the card. The Dwarves are legal targets; Gandalf is not. | Conditional on target | Conditional on target | Conditional on target |
| **Full of Froth and Rage** | A Spider or Animal attack must be present. It gives those attacks +2 prowess and is discarded if a Spider or Animal attack is defeated. | Conditional on attack | Conditional on attack | Conditional on attack |
| **Wake of War** | A Wolf, Spider or Animal attack must be present. It gives that attack +1 strike and +1 prowess. The extra Wolf bonus requires Doors of Night, which is absent from this baseline. | Conditional on attack | Conditional on attack | Conditional on attack |
| **River** | Playable on the destination site while a company is moving there. The company must do nothing in its Site Phase unless a Ranger taps to cancel the effect. Óin is a Ranger. | Yes | Yes | Yes |
| **Seized by Terror** | Requires a non-Wizard, non-Ringwraith character moving in a Shadow-land or Dark-domain. If the roll plus the target's mind is below 12, the character splits off and returns to the company's site of origin. None of these three paths contains either region type. | No | No | No |
| **Twilight** | Requires an Environment card in play or declared earlier in the same chain. The active Hero deck has no Environment, the Hazard list has none, and the sideboard is closed for the baseline. Twilight does not count against the Hazard Limit, but still needs a legal target. | No target in baseline | No target in baseline | No target in baseline |

**Fixed one-strike-per-character attacks:** Neeker-breekers and Watcher in the Water each specify one strike per character. A general strike-count modifier does not add extra strikes to such an attack, although applicable prowess modifiers still apply.

**Do not confuse the site type with the route's region types.** Moria and Goblin-gate are Shadow-holds [{S}], not Ruins & Lairs [{R}] sites. Lesser Spiders and Neeker-breekers are candidates on these journeys because the declared routes contain Wilderness [{w}], not because Moria or Goblin-gate satisfies their {R} site key. Watcher in the Water has its own explicit Moria wording.

## 3. What the route audit tells us

The locked creature package is route-active on all three teaching legs:

- Cave Worm has a named-region key on each route.
- Giant Spiders and Watcher in the Water have double-Wilderness access.
- Lesser Spiders, Neeker-breekers and Wargs have a Wilderness region key.
- Despair of the Heart can target the Dwarves on any of the three legs.
- Full of Froth and Rage and Wake of War have eligible Spider/Animal/Wolf attacks available in the baseline creature package.
- River can target each new destination site.

On this specific campaign, **26 of the 30 physical Hazard cards have a route or target available on every leg**. The four that do not are the two copies of **Seized by Terror** (no Shadow-land/Dark-domain route) and the two copies of **Twilight** (no Environment target). Full of Froth and Rage and Wake of War are counted as conditional because eligible Spider/Animal/Wolf attacks are in the baseline creature package. These are campaign-specific dead draws, not universally dead cards; a different route or an Environment can change their status. That is not a reason to redraw or to pretend they are playable.

The biggest pressure difference between these routes is therefore not a wholesale change in the creature keying. It is the **8 / 6 / 4 solo Hazard draw**, the destination's automatic attack, the Hero objective, and the company's condition on arrival.

### Later test cards — not part of the 30-card baseline

| Candidate | Moria | Goblin-gate | Blue Mountain | Why it is only a test |
|---|---|---|---|---|
| **Arouse Minions** | Yes — Shadow-hold | Yes — Shadow-hold | No — Free-hold | Raises one automatic attack at the target site by +3 prowess for the turn. It may be played during the Movement/Hazard Phase even if the company later declines to enter; the modifier matters only if the attack is actually faced. It counts against the Hazard Limit. |
| **Brigands** | Yes — Wilderness key | Yes — Wilderness key | Yes — Wilderness key | Two strikes at 8 prowess; if any strike wounds a character, the company discards one item of the defender's choice. |

Neither card belongs in the locked list. Check your physical collection before considering a purchase, and test any replacement only after the baseline games have been recorded.

## 4. Practice hand — eight drawn, five slots

This is a **constructed exercise hand**, not a claim about a random draw:

- Cave Worm
- Giant Spiders
- Lesser Spiders
- Full of Froth and Rage
- Wake of War
- River
- Seized by Terror
- Twilight

Use it against each of the three routes above.

1. Mark each card as **legal now**, **legal only when its target/condition exists**, or **illegal in this game state**.
2. Identify the two cards that cannot be used on these routes in the baseline.
3. Choose up to five Hazard plays. Explain why each one is more damaging than the legal alternative you leave out.
4. If you play a Spider attack with both support events, resolve the chain correctly. Full of Froth and Rage is discarded if a Spider or Animal attack is defeated, so its bonus may not remain for a later attack.
5. Decide whether River is worth using against this company. Óin can tap at the start of the Site Phase to cancel River; that may cost the Hero player a useful Ranger action.
6. Record whether the company enters the site and whether it faces the site's automatic attack.

There is no universal five-card answer independent of the company's condition. The Hazard side must choose the most disadvantageous **legal** combination for the actual state, not simply select the five cards with the highest printed numbers.

Open the [model answer and route-by-route reasoning →]({{ '/scenarios/route-exposure-matrix/answer-key/' | relative_url }}) after completing your own table.

## 5. Fair-play sequence

Use this order every time:

1. Fix the destination and legal movement before drawing.
2. Reveal the site and declare the actual Region Movement site path.
3. Draw the correct number of Hazard cards randomly.
4. For each card, check route key, site key, target, timing and current game state.
5. Separate legal cards from conditional cards and illegal cards.
6. Choose the most disadvantageous legal combination within the Hazard Limit.
7. Record every card left unused and the exact reason it could not be played or was a weaker choice.

Never change the route after seeing the Hazard hand, search the deck for a better creature, or make a card legal because the company looks too strong.

## Official references

- [Council of Elrond Official Game Rules](https://councilofelrond.org/rules/) — movement, site paths, Hazard Limit, attacks and timing.
- [Council of Elrond Official Card Database](https://www.councilofelrond.org/cards/) — current card wording and errata for the Hero sites and Hazard cards.
- [The Wizards rules and clarifications](https://meccg.com/rules/by-expansion/the-wizards/) — Region Movement and solo-play source material.
- [My Solo Rules](https://meccg.wordpress.com/my-solo-rules/) — independent supplementary solo handling used by this Academy; distinguish it from printed rules.

---

<div class="next-lesson">

**NEXT: Put the route, hand and company state together**

[Open the Expedition Decision Lab →]({{ '/scenarios/expedition-decision-lab/' | relative_url }})

</div>
