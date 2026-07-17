# Contests — The Dice Engine

Every roll in The Party is a **contest**: a handful of six-siders against a handful of six-siders. The player rolls, the GM rolls, higher sum wins. The rest of this chapter covers how many dice each side picks up and what winning means.

## The Contest Procedure

1. **Declare a goal.** The acting side says what they want to be true when the dust settles, in one sentence. *"I want the guard captain convinced we're the relief shift." "I want our freighters through the blockade this month."*
2. **Set the stakes.** The GM says what happens if the acting side loses, before dice hit the table. No stakes, no roll — if nothing interesting happens on a failure, the goal just succeeds.
3. **Pick the stat.** The goal and the approach imply one of the four [stats](core/stats.md). Your rating is your base pool.
4. **Count edges and snags.** Circumstances, features, gifts, aid, and committed resources adjust the pool (below).
5. **Roll and compare sums.** Higher total wins. Pools always stay between **1 and 5 dice**.

<div class="callout example" data-title="A whole contest in forty seconds">
<p><span class="speaker">Priya (playing Vess, the faction's Mouth):</span> "Goal — I want the harbormaster to seal the manifest without reading page three."</p>
<p><span class="speaker">GM:</span> "Doable. Stakes: if you lose, he reads it, and he's the type to sell what he finds. He's a wary professional — I'm rolling 3 dice. What's your approach?"</p>
<p><span class="speaker">Priya:</span> "Pure charm and paperwork momentum. Emotional, 4 dice."</p>
<p><span class="speaker">GM:</span> "Roll me." <em>Priya rolls 4d6: 14. The GM rolls 3d6: 11.</em> "He stamps it, bored, mid-anecdote about his nephew. Page three passes under his thumb unread."</p>
</div>

## Outcomes

| Result | What happens |
| --- | --- |
| **Win** | The goal comes true. |
| **Triumph** — win by 8+ | The goal comes true *and* you pick a boon: an extra strain, a better position, an extra countdown segment struck, a useful condition created, 1 strain recovered, or an edge primed for an ally. |
| **Tie** | **Costly success** — the acting side's goal comes true, but the GM attaches a real cost. |
| **Loss** | The stakes land. |
| **Disaster** — lose by 8+ | The stakes land hard: the GM may double the consequence or introduce a new threat. |

"Acting side" means whoever initiated the contest. When an NPC assassin lunges at you, a tie favors them. Two rulings about ties come up at every table:

- **The goal lands with full teeth.** If the goal was to harm you, a tie still harms you.
- **The cost bills the acting side.** The defender is never charged extra for a tie. When the assassin's blade finds you on a tie, the assassin is the one left overextended, exposed, or seen.

## Edges and Snags

An **edge** adds one die to your pool. A **snag** removes one. Count them, take the net, and clamp the pool between 1 and 5.

**Overflow:** if your pool is already at 5 and you have edges left, each remaining edge removes a die from the opposing pool instead (to a minimum of 1). Snags overflow the same way in reverse.

Edges come from six sources, one each:

| Source | Cap | What it is |
| --- | --- | --- |
| **Craft** | 1 | A Seat feature, calling feature, or gift that applies |
| **Aid** | 1 | One ally helps, says how, and shares the stakes if it goes wrong |
| **Position** | 1 | The situation favors you: high ground, home turf, surprise, blackmail in hand |
| **Personal Resource** | 1 | An extraordinary tool or possession of your own — the master-forged hammer, the experimental lens |
| **Faction Resource** | 1 | One committed [stock](faction/resources.md), if it's [Ready](faction/nodes.md#accessibility) and the type fits the approach |
| **Primed** | 1 | An edge an ally set up for you ([Build-Up & Payoff](combat/overview.md#build-up--payoff)) |

Expected tools grant nothing: a locksmith with picks is just a locksmith working. Personal Resource edges are for gear beyond the trade's norm — and *missing* an expected tool doesn't snag you, it raises the difficulty or blocks the goal.

Snags come from [conditions](core/strain-and-conditions.md#conditions), hostile terrain, acting out of your depth, or scale mismatch ([Faction Conflict](combat/faction.md#scale)).

In practice a roll is your stat, one or two edges, maybe a snag. If the table is debating more than four modifiers, the GM picks the two that matter most and calls for the roll.

<div class="callout example" data-title="Counting the dice">
<p>Marcus's character is slipping into a counting house at night. Physical 3 is the base. He shadowed the night porter for an evening (a feature granting a Craft edge, +1), and the faction spent 1 Intelligence stock on the floor plans (Faction Resource, +1). Five dice. But he's still carrying <em>Old Wound</em> from the rooftop fall last session (snag, −1): <strong>4 dice</strong> against the GM's 3 for a locked and shuttered building.</p>
</div>

## The Opposition Pool

The GM's pool is either an opposing character's stat, or a **difficulty** when the world itself resists:

| Opposition | Pool | Feels like |
| --- | --- | --- |
| Trivial | 1 | Only a disaster fails |
| Weak | 2 | Routine for a professional |
| Standard | 3 | A real challenge — the default |
| Hard | 4 | Skilled, entrenched, or dangerous |
| Formidable | 5 | Elite, fortified, or nearly impossible |

The GM's pool takes edges and snags too — an alerted guard, a fortified vault, a storm at sea.

## The Probabilities

| Matchup | Win | Win incl. ties | Triumph | Disaster |
| --- | --- | --- | --- | --- |
| 1 vs 3 | 1% | 3% | — | 44% |
| 2 vs 3 | 15% | 22% | <1% | 15% |
| 3 vs 3 | 45% | 55% | 4% | 4% |
| 4 vs 3 | 74% | 81% | 19% | <1% |
| 5 vs 3 | 91% | 94% | 46% | <1% |
| 5 vs 2 | 99% | 99.4% | 74% | — |
| 5 vs 1 | 99.99% | ~100% | 94% | — |

Both sides can always win. Five dice against one still loses about once in 47,000 rolls, and the table will talk about it for years when it happens.

## One Roll Settles It

A contest resolves the goal, not one twitch of effort. Win the contest to sneak past the checkpoint and you're past — the GM doesn't call for three more rolls on the same situation. Rolling the same goal again requires the situation to genuinely change.

## Group Contests

When several characters pursue one shared goal:

- **One leads and rolls.** The best-placed helper grants the single Aid edge; everyone else contributes through the story or takes a separate goal.
- **Everyone's exposed.** If the group loses, the stakes hit the whole group. The leader decides who absorbs any strain unless the situation dictates.
- **Faction contests** work the same way, with a faction stat as the base pool and one character [channeling](combat/faction.md#channel) as the roller.

## Countdowns

Anything too big for one contest — a siege, an election, a research program, a trade war — gets a **countdown**: a track of 4, 6, or 8 segments. When it reaches zero, the thing it names comes true.

- A relevant contest **win strikes 1 segment** (2 on a Triumph).
- A **costly success** strikes 1, and the GM strikes one from an opposing countdown or attaches a cost.
- A **loss** may strike a rival countdown instead.

Countdowns run toward good news and bad alike: *The Vault Opens (4)* is your project; *Reinforcements Arrive (4)* is the GM's. Two countdowns racing — yours against theirs — is the skeleton of every long struggle in The Party.
