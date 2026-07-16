# Nodes & Routes

A **node** is a place where the faction *is*: a chapel, a safehouse, a dry dock, a caravanserai, a forum server, a sympathetic precinct, a moon base. The faction's presence in the world is exactly the sum of its nodes — growing the map **is** gaining prominence. Recommended count: **3–6 nodes**. More than that, and the faction turn slows; consolidate or abstract.

## Anatomy of a Node

```
NODE: The Grinning Lantern — dockside tavern & listening post
TRACK   □ □ □ □ □         STOCK CAP: 5
NEEDS   1 Provisions, 1 Morale          (paid every faction turn)
YIELDS  1 Intelligence, 1 Influence     (earned every faction turn)
STOCK   2 Intelligence, 1 Force
UPGRADES  Hidden Cellar (warehouse: +2 cap)
CONDITIONS  —
ROUTES  → The Undercroft (tunnels, safe) · → Harbor Row (streets, Watched)
```

- **Track** — 5 boxes, marked when the node is attacked, sabotaged, or starved. A node taken out is occupied, burned, or scattered — it can sometimes be retaken, but its people remember who failed them.
- **Needs** — 1–2 internal stock per faction turn. What does this place consume to stay yours? Shortfall rules are in [Resources](faction/resources.md#shortfall--starving-the-body).
- **Yields** — 1–2 stock per faction turn. What does it produce? Any pool, internal or external.
- **Stock cap** — 5, before upgrades. Full warehouses are targets; empty ones are liabilities.
- **Upgrades** — up to 3 per node. Examples: **Fortified** (+1 protection tag), **Warehouse** (+2 stock cap), **Workshop** (+1 to one yield), **Cell Structure** (raids against it get a setback), **Beloved** (its people resist rival Influence with an edge), **Hidden** (rivals must find it before they can touch it).
- **Conditions** — same rules as [everywhere else](core/strain-and-conditions.md#conditions-at-faction-scale).

## The Stronghold

One node is the **Stronghold** — the seat, the mother church, the home port. It follows all normal rules, plus: losing it marks **2 Cohesion** and the faction must crown a new Stronghold by the end of the next faction turn or take a second condition (*Headless*). Strongholds are worth fortifying first.

## Routes

Routes connect nodes: roads, sea lanes, courier relays, encrypted channels, hyperspace corridors. Stock only moves along routes, during Logistics.

- **Safe** routes move stock freely.
- **Threatened** routes (contested territory, patrols, tariffs, pirates) require a contest per shipment — typically faction Physical or Mental vs. the threat.
- **Cut** routes move nothing until cleared by a faction action or venture. Cutting a rival's routes is often better strategy than burning their nodes: a rich node that can't be fed is a gift that keeps giving.

Rivals can **Raid** (steal moving stock), **Blockade** (cut a route), or **Watch** (their Intelligence yields +1 while they observe your logistics) — and so can you.

## Growing the Map

New nodes come from **Expand** [faction actions](faction/faction-turn.md#4-actions) (start a 4-segment clock; each successful Expand or supporting venture ticks it; on completion, the node opens with a basic profile you design with the GM) — or from a player spending 5 perks to *personally* found one, in which case it's theirs to define and the fiction should show their fingerprints on it forever.

Nodes gain upgrades via **Fortify/Develop** actions or 3 perks.

## Assets

An **asset** is faction property that *acts*: a strike team, a smear machine, a spy ring, a missionary circuit, a gunboat, a lawyer on retainer. Assets are the faction's limbs in [faction conflicts](combat/faction.md) and can work autonomously between sessions.

```
ASSET: The Red Choir — fanatic street preachers
TYPE Conviction   RATING 3   TRACK □ □ □   LOCATION The Undercroft
TAG  Sweeping (their sermons hit crowds, not people)
```

- **Type** — the stat it embodies; also the external pool that buys it (2 matching stock + a faction action, or 3 perks).
- **Rating (2–4)** — its dice pool when it acts alone or is [channeled](combat/faction.md#channeling). Assets are deliberately capped below 5: organizations are strong, people are exceptional.
- **Track** — 3 boxes. Assets are more expendable than people, and the game says so out loud.
- **Location** — an asset is *at a node*, and moves like stock. The gunboat defends the harbor it's anchored in.

During a faction turn, an idle asset can attempt one simple job on its own (rating vs. difficulty, no PC involved): the spy ring watches a rival, the strike team guards a route. Autonomous assets that fail contests take the consequences alone — which is how PCs find out something has gone wrong.
