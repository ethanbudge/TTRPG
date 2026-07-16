# Design Notes & Research

How this draft got here: the research consulted, the games it borrows from, and the math under the dice. Written so future revisions can see *why* each choice was made before unmaking it.

## The Brief, Compressed

The system was designed against these requirements: faction-first play where individuals *and* the organization succeed · classes as organizational roles, genre-agnostic · one combat system across genres *and scales* (knife fight → trade war → fleet battle) · goal-oriented turns, fast pacing · small numbers forever, no HP inflation · four stats (Physical/Mental/Emotional/+1), mirrored at faction scale · eight resources (4 stats × internal/external), examples-not-hardcoded · contested 3d6-vs-3d6 dice with ±d6 steps, clamped 1–5, targeting ~55/75/90/99% success bands · traits instead of ancestries · perk economy forcing self-vs-faction choices · nodes-and-distribution faction map · 3–7 players, robust to duplicate/missing classes.

## Influences — What Was Borrowed, What Was Refused

**[Blades in the Dark](https://bladesinthedark.com/crew)** ([faction game](https://bladesinthedark.com/faction-game), [SRD](https://github.com/amazingrando/blades-in-the-dark-srd-content/blob/main/Blades-in-the-Dark-SRD.md), [Alexandrian cheat sheet](https://thealexandrian.net/wordpress/40484/roleplaying-games/blades-in-the-dark-system-cheat-sheet)) — *Borrowed:* the crew as a shared advancing character; clocks; stakes-forward rolling; faction relationship ladder (its −3..+3 status became our 7-step ladder); "the score → downtime" loop shape. *Refused:* Tier as vertical faction advancement (violates small-numbers — replaced by web-of-rivals difficulty), stress-as-player-currency (one currency was wanted, and it's perks).

**[Stars Without Number](https://takeonrules.com/2018/12/27/lets-read-stars-without-number-factions/)** — *Borrowed:* the between-session faction turn with income → upkeep → one-action shape and its ~30-minute budget; assets with their own small tracks; goals-as-clocks for rivals. *Refused:* faction HP as one big pool (nodes + Cohesion carry it instead), and FacCred mono-currency (the brief demanded 8 typed pools — the types make distribution a game).

**[REIGN](https://atomicovermind.com/reign/)** ([review](https://www.rpg.net/reviews/archive/13/13162.phtml)) — *Borrowed:* the proof that company qualities can mirror character stats, and that *PC actions should feed company rolls* — that bridge became Channel/Commit. *Refused:* separate company-scale quality names (Might/Sovereignty/etc.); The Party uses the *same four words* at both scales, which is the thematic thesis.

**[Burning Wheel](https://keepontheheathlands.com/2017/11/27/burning-wheel-the-intimidating-game-that-is-not-actually-intimidating/)** — *Borrowed:* Intent & Task (our goal/approach/stakes procedure is it, nearly verbatim) and Let It Ride (one roll settles the goal). This is the backbone of "goal-oriented" play the brief asked for.

**[Fate](https://thecatholicgeeks.com/2019/05/24/fate-rpg-alternate-rules-health/)** ([damage-mechanics survey](https://uxdesign.cc/tabletop-rpg-design-6-types-of-damage-mechanics-20f27bc3dd26), [non-HP systems](https://jfacegames.substack.com/p/health-systems-in-tabletop-rpgs-beyond)) — *Borrowed:* stress that clears + consequences that linger and write fiction onto the sheet (→ strain + conditions/scars); zone-based distance ([via Sly Flourish's zone conversion](https://slyflourish.com/fate_style_zones_in_5e.html)) → the four bands. *Refused:* aspect-invocation economy (too many touchpoints per roll for the pacing target).

**[Daggerheart](https://rpgbot.net/daggerheart-a-review/)** ([EN World review](https://www.enworld.org/threads/daggerheart-review-the-duality-of-robust-combat-mechanics-and-freeform-narrative.713471/)) — *Borrowed:* fear of HP bloat done right (thresholds, small pools), initiative-less spotlight flow, and the warning label: reviewers found GM-metacurrency pacing (Fear hoarding) could produce repetitive play — The Party deliberately has **no GM metacurrency**; GM pressure comes from stakes, ties, and rival clocks.

**[Band of Blades](https://gnomestew.com/band-of-blades-review/)** ([Indie Game Reading Club](https://indiegamereadingclub.com/indie-game-reading-club/band-of-blades-a-supposedly-fun-thing-ill-never-do-again/)) — *Borrowed:* organizational role-sheets held by players (→ faction-turn step ownership and class synergies); Scale/Threat for enemies (→ scale tiers). *Refused, emphatically:* its subsystem sprawl — the most consistent criticism in reviews was moving parts crowding out talk. The Party's discipline: **one resolution engine, one track shape, one condition rule, reused everywhere.**

**On slow combat** ([Campaign Mastery](https://www.campaignmastery.com/blog/combat-system-design/), [The Alexandrian](https://thealexandrian.net/wordpress/40484/roleplaying-games/blades-in-the-dark-system-cheat-sheet), [community threads](https://ttrpg.network/post/22594594)) — the compounding-seconds analysis (every extra per-turn step × players × rounds) drove the hardest rule in the book: one contest per goal, no separate to-hit/damage/save chain, margin does the work.

**On advancement** ([Scroll and Tome on vertical vs. horizontal progression](https://www.scrollandtome.com/ttrpg-progression-systems/)) — horizontal advancement (breadth-not-power) is the established answer to power creep; The Party commits fully: stat caps, fixed tracks, features-as-options.

**On unified mass combat** ([EN World discussion](https://www.enworld.org/threads/two-combat-systems-one-game.693082/)) — precedent (Traveller's same-mechanics-different-timescale ship combat) validated the clockspeed approach: don't write a second system, change what a beat *means*.

## Dice Math

Contested d6 sums, all pool matchups (P = player dice, G = opposition dice). "Success" = win + tie (ties favor the acting side at a cost):

| P\G | 1 | 2 | 3 | 4 | 5 |
| --- | --- | --- | --- | --- | --- |
| **1** | 58% | 16% | 3% | 0.3% | ~0% |
| **2** | 91% | 56% | 22% | 6% | 1% |
| **3** | 99% | 85% | **55%** | 26% | 9% |
| **4** | 99.9% | 96% | **81%** | 54% | 28% |
| **5** | ~100% | 99.4% | **94%** | 78% | 54% |

Strong wins (margin ≥ 5) run 14.5% at 3v3, 41% at 4v3, 69% at 5v3 — stacking edges doesn't just win more, it wins *bigger*, which is the buildup-and-payoff lever.

Why these choices:

- **3d6 base kept from the brief.** The bands the brief targeted (55/75/90/99) fall out *naturally* from 3v3 / 4v3 / 5v3 / 5v2 with ties-to-actor — no fudge factors. The brief's instinct was mathematically sound.
- **Ties to the acting side, with a cost.** Raw 3v3 wins only 45% — below the target band and, worse, ~9% of rolls would be dead "nothing happens" results. Assigning ties to the actor hits 55% *and* converts every tie into forward story motion (the fail-forward result every modern design reaches for), *and* stays symmetric: NPCs initiating against PCs get the same courtesy, so defense feels dangerous.
- **Sums, not dice-pool successes.** Counting successes (Shadowrun-style) is slower at the table than comparing two sums, and sums produce a natural **margin** for free — which powers strong wins, strain amounts, and clock ticks with zero extra rolls.
- **The 1–5 clamp with overflow.** Guarantees "theoretically winnable by either party" at every matchup (5v1 loses once per ~47,000) while letting overwhelming preparation still matter past the cap (overflow strips opposition dice). Probability steps between adjacent pools run 20–27 points mid-range — each edge is *felt*, which keeps the edge-hunting game meaningful without decimal bookkeeping.

## The Load-Bearing Unifications

Design moves that make the generalizability brief work, listed so nobody accidentally un-unifies them:

1. **Four stats = four faction stats = eight resource pools.** One vocabulary from character sheet to war map.
2. **Everything breakable has the same track.** PCs, mooks, assets, nodes, Cohesion: 1–6 boxes, same marking rules.
3. **One condition rule at every scale.** *Blinded* on a duelist and *Infiltrated* on a faction are the same mechanic.
4. **Scale is a camera, not a system.** Clockspeed + bands + scale tiers are declarations, not rule modules.
5. **The faction layer is additive.** Faction conflict = personal conflict + four moves (Channel/Commit/Deploy/Marshal). Removing the faction from a scene removes rules; it never swaps them.
