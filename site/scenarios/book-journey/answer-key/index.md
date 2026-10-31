---
layout: page
title: Book of Mazarbul — Second Expedition Answer Key
permalink: /scenarios/book-journey/answer-key/
---

# Book of Mazarbul — Model Answer

Use this after completing the [Second Expedition workbook]({{ '/scenarios/book-journey/' | relative_url }}). The answer is a method, not a command to choose the same route in every game.

## 1. Check the mission and timing

The first mission was to acquire Book of Mazarbul at Moria. Once acquired, the new mission is to store it at a Dwarf-hold for its five-point stored value.

The Organization Phase has already passed when the Book is acquired during Moria's Site Phase. You cannot store it or declare the next movement retroactively. On the next turn:

1. Untap tapped characters; heal wounded characters at a Haven only if the company is at one.
2. During the Organization Phase, declare the next destination and movement.
3. The company then takes its Movement/Hazard Phase.

When the company eventually reaches Blue Mountain Dwarf-hold, the Book is not stored during that arrival turn's Site Phase. Storage is an Organization Phase action, separate from Site Phase entry; the company does not need to enter Blue Mountain solely to store the Book on the following turn. At the start of the following turn, while the company is at Blue Mountain, the bearer may attempt to store the Book and make the required corruption check. If successful, it goes into the marshalling-point pile for **5 MP**, not 1 + 5. **Bearer choice matters:** Dori, Kíli and Óin each receive -1 to all of their corruption checks, so one of them may be a safer bearer than Thorin or Glóin if the rest of the company's risk profile supports it. Include every corruption point on the bearer, not just the Book's two points. Despair of the Heart can add another two corruption points and trigger checks when anyone in the company is wounded.

## 2. Route legality

### Moria → Goblin-gate

**Redhorn Gate → Hollin → Rhudaur → High Pass**

The route contains four regions, including both endpoints. The region adjacency references confirm:

- Redhorn Gate is adjacent to Hollin.
- Hollin is adjacent to Rhudaur.
- Rhudaur is adjacent to High Pass.

There are no repeated regions. This is a legal normal Region Movement route.

### Goblin-gate → Blue Mountain Dwarf-hold

**High Pass → Rhudaur → Arthedain → Númeriador**

The route contains four regions, including both endpoints. The region adjacency references confirm:

- High Pass is adjacent to Rhudaur.
- Rhudaur is adjacent to Arthedain.
- Arthedain is adjacent to Númeriador.

There are no repeated regions. This is also legal normal Region Movement.

### Why the direct route from Moria is not one movement

**Redhorn Gate → Hollin → Rhudaur → Arthedain → Númeriador** contains five regions. Normal Region Movement allows at most four consecutive regions, including origin and destination. Do not omit an endpoint to make the count appear legal.

## 3. Draws and Hazard Limits

For a five-character company with no relevant modifiers:

| Movement | Normal Hazard draw used | Academy solo draw | Base Hazard Limit |
|---|---:|---:|---:|
| Moria → Goblin-gate | Goblin-gate: 2 | **6** | **5** |
| Goblin-gate → Blue Mountain | Blue Mountain: 1 | **4** | **5** |
| Moria → Rivendell | Moria, because destination is a Haven: 3 | **8** | **5** |
| Rivendell → Blue Mountain | Blue Mountain: 1 | **4** | **5** |

The solo formula is **2 + twice the normal Hazard draw number**. The normal rule determines which site's draw number is used first: a move to a non-Haven uses the new site; a move to a Haven normally uses the site of origin.

A draw of six does not permit six ordinary Hazard plays against a company with a base Hazard Limit of five. The Hazard Limit is fixed for that Movement/Hazard Phase. If the company loses a character during Leg 1, recalculate its base limit for Leg 2.

## 4. Hazard legality on the Goblin-gate leg

The declared path is four Wilderness regions and includes the named regions Redhorn Gate, Hollin, Rhudaur and High Pass.

| Card | Decision | Reason |
|---|---|---|
| **Cave Worm** | Candidate | Its named-region key includes **Redhorn Gate** and **High Pass**, both in the declared path. |
| **Giant Spiders** | Candidate | Four Wilderness regions satisfy double Wilderness. |
| **Lesser Spiders** | Candidate | Wilderness is one of its region-type keys. Goblin-gate is a Shadow-hold, not a Ruins & Lairs site. |
| **Wargs** | Candidate | Wilderness is one of its keys. |
| **Neeker-breekers** | Candidate | Wilderness is one of its keys. Apply the one-strike-per-character text exactly. |
| **Watcher in the Water** | Candidate | Double Wilderness is satisfied. Do not use the special Moria permission: the destination is Goblin-gate. |
| **Seized by Terror** | Illegal | The path contains no Shadow-land or Dark-domain region. A Shadow-hold site symbol is not a Shadow-land region symbol. |
| **Full of Froth and Rage** | Conditional candidate | It needs a Spider or Animal attack whose prowess it can modify. Check timing and whether it is already duplicated. |
| **Wake of War** | Conditional candidate | It can affect Wolf, Spider and Animal attacks. Check timing, duration and whether it is already in play. |
| **Despair of the Heart** | Candidate | Any starting Dwarf is a non-Wizard, non-Hobbit target. It adds 2 corruption points and makes the target check whenever a character in his company becomes wounded. This can make a later wound trigger a dangerous check on the Book bearer. |
| **River** | Candidate if played on the destination site | If the company does not tap a Ranger by the beginning of the Site Phase, it must do nothing during that Site Phase. The Hero may tap Óin, the starting Ranger, to avoid this. River does not prohibit the next turn's Organization Phase storage. |
| **Twilight** | Only if it has a legal Environment target | It is not a generic extra attack. It does not count against the Hazard Limit, but needs an Environment card to cancel. |

“Candidate” means check the printed text and current state; it does not mean the card is automatically playable in every hand.

## 5. Hazard legality on the Blue Mountain leg

The path is **High Pass → Rhudaur → Arthedain → Númeriador**. All four regions are Wilderness.

- Cave Worm can use its named-region key to **High Pass** or **Númeriador**.
- Giant Spiders can use double Wilderness.
- Lesser Spiders, Wargs and Neeker-breekers can use their Wilderness keys.
- Watcher in the Water can use double Wilderness; its Moria-specific site permission is irrelevant here.
- Seized by Terror remains illegal because the path has no Shadow-land or Dark-domain region.
- River's current erratum lets the Hero tap a Ranger by the beginning of the Site Phase; the starting company has Óin. If Óin is available, the Hazard play costs the Hero a tap rather than automatically denying the site phase. If the company was already going to skip the site phase, River may add little practical pressure. It does not cancel a later Organization Phase storage attempt.

Blue Mountain Dwarf-hold is a Free-hold by site type, but the site is named as a Dwarf-hold and is the location specified by the Book's storage condition. The Hero site has no automatic attack. The lack of an automatic attack does not cancel the four-card Hazard draw.

## 6. Goblin-gate: enter or use as a waypoint?

Goblin-gate has an automatic attack of **three Orc strikes at 6 prowess**. It is faced if the company enters the site.

A strong Hero-side decision depends on the company's actual state:

- If the company is badly wounded, tapped or has spent its avoidance cards, skipping entry may preserve the company and keep the Book mission alive.
- If the company is healthy and Gollum is a worthwhile objective, entering may be justified—but the automatic attack must be resolved first.
- If you do not enter, you cannot take site actions or play cards there during that Site Phase. The company remains at Goblin-gate and can move on the next turn.

Do not count the automatic attack as one of the Hazard player's six drawn cards or five ordinary Hazard slots. It is a separate site encounter.

## 7. What does the Hazard player do with six cards and five slots?

Suppose the constructed practice hand for Moria → Goblin-gate is:

- Cave Worm
- Giant Spiders
- Wargs
- Watcher in the Water
- Full of Froth and Rage
- Wake of War

All six are potential legal candidates on the declared path, subject to their exact card text, target, timing and current state. With a base Hazard Limit of five, you cannot play all six if all count against the limit.

A strong line to evaluate is:

1. Full of Froth and Rage.
2. Wake of War.
3. Giant Spiders.
4. Wargs.
5. Watcher in the Water.

This is a **model combination to test**, not a universal script. Cave Worm remains a legal alternative: compare its single high-prowess strike against the extra strike volume and modified prowess of the other creatures. Choose the most disadvantageous legal combination for the actual company.

Order matters. Full of Froth and Rage is discarded if a Spider or Animal attack is defeated. After each attack, check whether it remains in play before resolving the next one. Wake of War has a separate duration and effect. Do not assume the first sequence you think of is always the strongest.

## 8. Why the Haven route can still be better

The Haven alternative is:

1. Moria → Rivendell via Redhorn Gate → Hollin → Rhudaur.
2. Rivendell → Blue Mountain via Rhudaur → Arthedain → Númeriador.

The first movement to a Haven uses Moria's normal Hazard draw number of 3, producing an eight-card solo draw. The second leg produces four cards.

At Rivendell, during the Untap Phase, each tapped character may untap or each wounded character may be healed to the tapped position. A character healed this way does not also untap during that same phase. This recovery can still be worth the additional first-leg Hazard draw, especially if a key character is wounded.

Do not use Starter Movement directly from Moria to Rivendell: Moria's nearest Haven is Lórien. The example uses Region Movement.

## 9. Final decision checklist

- [ ] The Book is actually in play and its bearer is identified.
- [ ] The company condition is recorded before choosing a route.
- [ ] Both Region Movement routes contain four or fewer regions.
- [ ] Every adjacency has been checked against the Region cards.
- [ ] The Hazard draw is calculated from the correct site.
- [ ] The Hazard Limit is recalculated for the actual company size.
- [ ] Goblin-gate's automatic attack is kept separate from the Hazard draw.
- [ ] I have chosen whether to enter Goblin-gate before resolving its Site Phase.
- [ ] I know that Book storage occurs in the next Organization Phase at Blue Mountain.
- [ ] I will make the bearer’s corruption check and score 5 MP only if storage succeeds.

## Sources

- [Council of Elrond Official Game Rules](https://www.councilofelrond.org/rules/) — movement, site paths, Hazard Limits, Untap Phase, Organization Phase and site entry.
- [Collected Rules File 22](https://meccg.com/rules/collected-rulings-and-errata-crf/crf-22/) — current card errata, including River's Ranger-tap option.
- [The Wizards rules — official Solitaire Rules](https://meccg.com/rules/by-expansion/the-wizards/) — separate Hazard deck, five-card hand, solo draw formula and most-disadvantageous legal plays.
- [Challenge Deck C Player's Guide](https://assets.cardgamegeek.com/public/library/meccg/Challenge_Decks_PG.pdf) — historical deck list and suggested resource sites.
- [MECCG Full Spoiler List](https://meccg.es/meta/cards/MeCCG%20Full%20Spoiler%20List.pdf) — site details and Region adjacency.
- [Council of Elrond Official Card Database](https://www.councilofelrond.org/cards/) — current card wording and errata.

Return to the [workbook]({{ '/scenarios/book-journey/' | relative_url }}) and record the route you chose. Then update the [Expedition Planner]({{ '/routes/expedition-planner/' | relative_url }}) for the next campaign objective.
