# Contests — The Dice Engine

Every roll in The Party is a **contest**: a fistful of six-siders against a fistful of six-siders. The player rolls; the GM rolls; higher sum wins. That's the whole engine — everything else in this chapter is about *how many dice* each side picks up and *what winning means*.

## The Contest Procedure

1. **Declare a goal.** The acting side says what they want to be true when the dust settles. One sentence. *"I want the guard captain convinced we're the relief shift." "I want our freighters through the blockade this month."*
2. **Set the stakes.** The GM says what's at risk — what happens if the acting side loses. Stakes are stated *before* dice hit the table. No stakes, no roll: if nothing interesting happens on a failure, the goal just succeeds.
3. **Pick the stat.** The goal and the approach imply one of the four [stats](core/stats.md). Your stat is your base dice pool.
4. **Count edges and setbacks.** Circumstances, class features, gifts, aid, and committed resources adjust the pool (see below).
5. **Roll and compare.** Both sides roll their pools and sum. Higher total wins. Pools are always **1 to 5 dice** — nothing can push a pool outside that range.

## Outcomes

| Result | What happens |
| --- | --- |
| **Acting side wins** | The goal comes true. |
| **Wins by 5+ (a strong win)** | The goal comes true *and* the winner picks one boon: inflict an extra strain, gain a better position, tick an extra clock segment, create a useful condition, or recover 1 strain. |
| **Tie** | **Costly success** — the acting side's goal comes true, but the GM attaches a real cost: strain, a condition, lost position, lost resources, or a complication that changes the scene. |
| **Acting side loses** | The stakes land. The GM narrates the miss and the consequence. |
| **Loses by 5+** | The stakes land hard — the GM may double the consequence or introduce a new threat. |

Ties going to the acting side (at a price) keeps the story moving forward and makes even-odds rolls feel slightly heroic. Note that "acting side" means whoever initiated the contest — when an NPC assassin lunges at *you*, the tie favors *them*.

## Edges and Setbacks

An **edge** adds one die to your pool. A **setback** removes one. Count them all, take the net, apply it, and clamp the pool between 1 and 5.

**Overflow:** if your pool is already at 5 and you have edges left over, each remaining edge *removes one die from the opposing pool* (to a minimum of 1). Setbacks overflow the same way in reverse. This is how overwhelming preparation turns into near-certainty.

Edges come from, at most one each of:

- **Craft** — a class feature, calling feature, or gift that applies.
- **Aid** — one ally helps, says how, and shares the stakes if things go wrong.
- **Position** — the fiction favors you: high ground, home turf, surprise, blackmail in hand, a rehearsed plan.
- **Resources** — committed stock from the faction's [pools](faction/resources.md), 1 edge per stock, **maximum 2 stock per contest**, and the stock type must plausibly power the approach.

Setbacks come from [conditions](core/strain-and-conditions.md#conditions), hostile terrain, acting out of your depth, or scale mismatch (see [Faction Conflict](combat/faction.md#scale)).

In practice a roll is: *stat, plus maybe two or three edges, minus maybe one setback*. If the table is debating more than four modifiers, the GM should simplify to the two that matter most and roll.

## The Opposition Pool

The GM's pool is either an **opposing character's stat** (contested action) or a **difficulty** (the world resists):

| Opposition | Pool | Feels like |
| --- | --- | --- |
| Trivial | 1 | Only a disaster fails |
| Weak | 2 | Routine for a professional |
| Standard | 3 | A real challenge — the default |
| Hard | 4 | Skilled, entrenched, or dangerous |
| Formidable | 5 | Elite, fortified, or nearly impossible |

The GM's pool takes edges and setbacks too — an alerted guard, a fortified vault, a storm at sea.

## The Probabilities

The engine was tuned against target success bands. Numbers below include costly successes (ties):

| Matchup | Full win | Win incl. costly | Reads as |
| --- | --- | --- | --- |
| 2 vs 3 | 15% | 22% | Outmatched |
| 3 vs 3 | 45% | 55% | A fair fight — most regular checks |
| 4 vs 3 | 74% | 81% | Capable — skill or resources applied |
| 5 vs 3 | 91% | 94% | Loaded — serious resources applied |
| 5 vs 2 | 99% | 99.4% | Trivial |
| 5 vs 1 | 99.99% | ~100% | A formality — but not *quite* certain |

Every band remains winnable by both sides. Even five dice against one loses about once in 47,000 — and when it happens, everyone at the table will remember it. Full tables and the math behind them live in [Design Notes](appendix/design-notes.md#dice-math).

## One Roll Settles It

A contest resolves the *goal*, not a single twitch of effort. If you win the contest to sneak past the checkpoint, you're past — the GM doesn't call for three more sneak rolls on the same fiction. Re-rolling the same goal requires the situation to genuinely change. (Borrowed with gratitude from Burning Wheel's *Let It Ride*.)

## Group Contests

When several characters pursue **one shared goal**, don't roll a pile of dice separately:

- **Lead and aid.** One character leads and rolls; each meaningful helper is a single Aid edge (remember: max one Aid edge — pick the best helper; the rest contribute through the fiction or by taking separate goals).
- **Everyone's exposed.** If the group loses, the stakes hit the whole group. The leader decides who absorbs any strain unless the fiction dictates.
- **Faction contests** work identically, with the faction's stat as the base pool and any character [channeling](combat/faction.md#channeling) as the roller.

## Clocks

For anything too big for one contest — a siege, an election, a research program, a trade war — draw a **clock**: a circle divided into 4, 6, or 8 segments.

- A relevant contest **win ticks 1 segment** (2 on a strong win).
- A **costly success** ticks 1 but the GM ticks an opposing clock or inflicts a cost.
- A **loss** may tick a rival's clock instead.

Two clocks racing each other (*Our Cartel Corners the Market* vs. *The Consortium Locks Us Out*) is the skeleton of every long-form conflict in The Party. When a conflict spans months, each contest simply represents a bigger swing of effort — see [Conflict Overview](combat/overview.md#timescale).

## Spending a Perk on a Roll

Once per contest, you may spend 1 [perk](characters/advancement.md) to either:

- **Reroll** one of your dice after seeing the result, or
- **Prepare** — declare, before rolling, a bit of groundwork your character plausibly did earlier ("I bribed the doorman *last week*"). Gain a Position edge and let the fiction catch up.
