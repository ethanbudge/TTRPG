# Resources — The Eight Pools

Faction resources come in **eight pools**: one **internal** and one **external** pool for each of the four stats. The rules below are hard-coded; the *names and fictions* of the pools are not — every campaign names its own eight during faction creation. That single step is what lets one resource system run a monastery, a heist crew, and a battle fleet.

## The Grid

| Stat | Internal — *keeps you alive* | External — *projects power* |
| --- | --- | --- |
| **Physical** | **Provisions** — food, fuel, medicine, ammunition, life support | **Force** — troops, muscle, warships, enforcers, war machines |
| **Mental** | **Expertise** — training, competent staff, maintenance knowledge | **Intelligence** — secrets, maps, blackmail, R&D breakthroughs |
| **Emotional** | **Morale** — comfort, celebration, camaraderie, rest | **Influence** — reputation, propaganda reach, favors, diplomatic capital |
| **Conviction** | **Unity** — shared ritual, discipline, doctrine, identity | **Zeal** — fervor, recruitment energy, willingness to sacrifice |

The names above are the *canonical examples* used throughout these rules. Your campaign should rename them — the [genre frames](gm/genre-frames.md) show eight-pool spreads for five different settings.

**Internal pools are consumed by your own nodes** at every faction turn's Upkeep step. They are the cost of existing. Starve a node of Provisions and it starves; starve it of Unity and it stops believing it's part of you.

**External pools are spent at the world.** They fuel [Resource edges](core/contests.md#edges-and-setbacks) in contests, power faction actions, and purchase [assets](faction/nodes.md#assets). They are the cost of *acting*.

## Stock

Resources are counted in **stock** — small integers, like everything in The Party.

- Stock lives **at nodes**, not in an abstract treasury. Each node holds at most **5 stock total** (upgrades can raise this). Where things are *matters*: Force stockpiled at the Chapel can't defend the Docks tonight.
- Stock moves along **routes** during the faction turn's Logistics step — free on safe routes, contested on threatened ones. Cut routes are how sieges work.
- Stock is spent by saying where it comes from. Committing Force to a contest means *those* enforcers, from *that* node.

## Gaining Stock

| Source | How |
| --- | --- |
| **Node yields** | Each node produces 1–2 stock per faction turn (its Yields line) — farms yield Provisions, temples yield Unity, listening posts yield Intelligence. |
| **Ventures** | Loot, prizes, converts, and secrets won in play become stock at the GM's ruling — a robbed vault might be +2 Influence... or +2 of whatever the campaign calls money. |
| **Trade actions** | Swap stock types at 2:1 with the market, or 1:1 with an Allied faction. |
| **Class synergies** | Duplicated offices each add +1 stock of their type at Yield ([see classes](characters/classes.md)). |
| **Rival misfortune** | Raid their routes, flip their nodes, catch their couriers. |

## Spending Stock

| Use | Cost |
| --- | --- |
| **Resource edge** in a contest | 1 stock = 1 edge, max 2 per contest; type must plausibly power the approach; stock must be present (on site, or at a node connected by an unbroken route). |
| **Faction actions** | Some actions burn stock — a Campaign runs on Influence or Zeal, a Strike on Force. Typically 1, listed with the [action](faction/faction-turn.md#4-actions). |
| **Assets** | 2 stock of the matching external type + a faction action, or 3 perks. |
| **Emergency upkeep** | Cover a missing internal need with 2 stock of the same stat's *external* pool (the troops eat the war-chest; morale is patched with propaganda). Ugly, and everyone knows it. |

## Shortfall — Starving the Body

When a node's Needs go unpaid at Upkeep:

1. **First miss:** the node takes a lasting condition matching the starved pool — *Starving* (Provisions), *Falling Apart* (Expertise), *Restless* (Morale), *Doubting* (Unity). Conditions impose setbacks on everything the node does, including its yields — hunger compounds.
2. **Second consecutive miss:** mark 2 strain on the node's track and the condition worsens (the GM sharpens the fiction — desertions begin, the presses break, the congregation thins).
3. **Third consecutive miss:** the node **flips** — it defects to a rival, dissolves, or goes dark, GM's choice, always foreshadowed. Mark 1 Cohesion.

## Surplus — Feeding It Well

A node whose needs are all paid *and* which holds 2+ unspent stock at the end of Upkeep becomes **Flourishing** until next turn: +1 edge on its yields or its defense (its people are fed, proud, and loyal). Distribution isn't just triage — generosity is a strategy.

## Design Note — Why Eight, Why Named-by-You

Four stats × internal/external gives the faction economy the same shape as the character sheet: the same four words describe what a *person* is and what an *organization* is, which is the thematic core of The Party. Leaving the pool names to the table (with strong defaults) is what the brief called generalizability — the rules govern *flows* (yield, upkeep, movement, spend), and flows are genre-proof even when grain tithes become reactor fuel. See [Design Notes](appendix/design-notes.md) for the research trail.
