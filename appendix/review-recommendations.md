# Review & Recommendations

An outside look at The Party — what an independent reader found, what research says players actually want, and what this system should change, add, or watch. This page is deliberately harsher than the rest of the book. That's its job.

## How This Review Was Made

Two inputs, kept separate so they could disagree:

1. **A cold read.** An independent reviewer with *no knowledge of this project* — no design notes, no open-questions list, no access to the designers' intent — read the entire book in a stranger's order, then reported comprehension friction, rules contradictions, gaps, and recommendations. The reviewer was explicitly barred from the appendix's self-assessment pages so its findings would be independent.
2. **Research.** A survey of what's known about player enjoyment, why campaigns die, and where designs like this one historically fail — sources linked throughout.

This is a **repeatable protocol**: after each major revision, run a fresh cold read by a reader (human or otherwise) who hasn't seen the design conversation, and re-check its findings against this page. A game about organizations should practice institutional memory.

> **Status marks used below:** ✅ *applied in this revision* · 🔲 *awaiting a design decision* · 🧪 *needs playtest data to decide*

## What the Research Says Players Want

Condensed from the sources, with implications for this system:

- **Character uniqueness and immersion consistently top player-motivation surveys** ([player-type research overview](https://dl.acm.org/doi/fullHtml/10.1145/3582437.3582457), [Run a Game's synthesis](https://www.runagame.net/2015/06/player-types-and-motivations.html)). Players also split along tactical-mechanical versus social-narrative motivations — and shift between them by context. *Implication:* The Party serves social-narrative players richly; its tactical offering is edge-hunting and resource positioning, which is real but thin for build-optimizers. The classes must make two same-office characters feel distinct (see recommendations).
- **Campaigns die of scheduling and GM burnout more than of bad rules** ([The DM Lair on campaign failure](https://thedmlair.com/blogs/news/top-7-reasons-d-d-campaigns-fail-and-how-to-save-yours), [Magpie Games on GM burnout](https://magpiegames.com/blogs/news/gm-tips-fending-off-burnout), [Domain of Many Things](https://www.domainofmanythings.com/blog/gm-burnout)). *Implication:* every rule that adds GM workload — and The Party's GM rolls in *every* contest and runs 2–4 rival factions — must pay for itself. The system needs absent-player rules and GM-side automation more than it needs more player options.
- **Homebrew systems historically fail on modifier accumulation and terminology sprawl** ([Mythcreants on common design mistakes](https://mythcreants.com/blog/six-more-common-design-mistakes-in-roleplaying-games/)) — and Blades in the Dark, this game's closest ancestor, drew exactly that criticism: fresh jargon for every concept makes a simple game read as complicated ([an analysis of Blades criticism](https://aggregatecognizance.com/p/dead-letters/)). *Implication:* The Party has ~30 terms of art (venture, beat, clockspeed, stock, node, channel, commit…). The glossary helps; discipline going forward helps more. Every new subsystem should reuse an existing noun before minting one.
- **Goal-based play causes decision paralysis in a documented minority of players** ([RPG PUB thread on choice paralysis in narrative-first games](https://www.rpgpub.com/threads/how-to-reconcile-paralysis-of-choice-with-narrative-first-rules-light-games.10789/), [Gnome Stew on analysis paralysis](https://gnomestew.com/planning-and-analysis-paralysis/)). "You can attempt anything" freezes some people. PbtA-style move lists work as *inspiration menus* rather than restriction. *Implication:* see the goal-prompts recommendation below.
- **Onboarding research favors quick-starts, progressive disclosure, and teach-by-play** ([rulebook design guide](https://boardgamesguide.com/ultimate-guide-role-playing-game-rulebooks-2026/), [Tabletop Bellhop on learnability](https://tabletopbellhop.com/gaming-advice/boardgame-design-tips/)). *Implication:* the examples chapter and glossary carry most of this; the missing piece is a runnable starter scenario.
- **Opposed-roll systems trade GM attention for drama** ([RPGnet on opposed roll mechanics](https://forum.rpg.net/index.php?threads/opposed-roll-mechanic.720728/)). Fate-style static difficulty frees the GM's hands; contested rolls put the GM in every moment. The Party chose drama on purpose — but big tables feel the cost. *Implication:* an optional static-opposition dial (below).

## What the Cold Reader Found

The full independent report is preserved in the project's history; its material findings, triaged:

### Contradictions between rules and examples — ✅ all fixed this revision

The reviewer's sharpest finding: four worked examples taught rules the rulebook forbids. The flagship tavern fight resolved a tie without billing the acting side; the fleet battle used a phantom "strain = −1 die" rule and let massed force count as leverage; the heist example ignored the overflow rule the dice chapter is proudest of; a character appeared with an impossible stat. All corrected, along with the root causes: the tie rule now states explicitly that **the goal lands with full teeth and the cost always bills the acting side**; the edge sources are now a **five-source budget table with hard caps** (Craft 1 · Aid 1 · Position 1 · Resources 2 · Banked 1); banked set-up edges are **capped at one per ally**; leverage has a **test** (a named vulnerability established in fiction *before* the harmful goal — mass never qualifies); and hard conditions explicitly also hinder.

### Underspecified faction machinery — ✅ quantified this revision

Shortfall conditions now cost nodes 1 yield; Flourishing now grants +1 yield (or a defense edge); granted stock lands where the fiction says, defaulting to the Stronghold; Recruit gains 1 stock (2 on a strong win); stock committed to actions is spent win or lose; node defense has a written procedure; the Cohesion track no longer double-charges a lost node; "does defending consume my turn?" is answered in a callout (**no**); "scene" is defined in the glossary.

### Real gaps — 🔲 the designer's queue

These survive the errata pass and need decisions, not edits. They form the backbone of the recommendations below.

## Recommendations

Organized by the system's own stated goals. The verdicts are the reviewer's and the research's, merged; the decisions are yours.

### Goal: fast, dynamic, generalizable combat

1. 🔲 **Add goal prompts to every class page** — six *"try declaring…"* one-liners per office, tuned per calling. This is the research-backed cure for goal-paralysis at no cost to freedom: menus as inspiration, never as walls. Cheap, high-impact, genre-neutral.
2. 🧪 **Strong wins are common for specialists, not rare** — margin-5+ triggers on ~41% of 4v3 wins and ~70% of 5v3 wins. Boon-picking on nearly half of a specialist's rolls is either delightful texture or decision drag; only a table can say. If it drags, raise the strong-win threshold to 6+ (drops those rates to roughly 30% and 58%) before touching anything else.
3. 🔲 **Offer a static-opposition dial for big tables.** Optional rule: routine opposition doesn't roll — it stands on 3.5 × its pool, rounded (difficulty 3 = 11). Contested rolls stay for rivals, nemeses, and anything with a name. This halves table rolls at seven players and gives the GM's hands back, at the confessed cost of the "both sides can always win" purity — which is why it should be a dial, not the default.
4. 🧪 **Watch the Hand's unlimited Interpose.** The death-spiral risk (the Hand absorbs everything and exits early) is real on paper. If playtests confirm, the nerf is once per beat.

### Goal: meaningful, distinct character generation

5. 🔲 **Make duplicate offices structurally distinct.** Two Hands work mechanically, but the research is blunt that character uniqueness is a top motivation. Cheapest fix: a soft rule at creation — *duplicated offices should take different callings* — plus one "rivalry or lineage?" bond question binding the pair. Zero new mechanics.
6. 🔲 **Guard class identity against multiclass dilution.** Cross-class features at +1 perk is generous enough that veteran characters may converge (the Blades critique of vestigial playbooks). Consider capping cross-class features at two per character, or gating the third behind a fiction cost (formally serving the other office for an arc).
7. 🔲 **Write the replacement-character rule.** Death and retirement are designed outcomes, but a mid-campaign replacement's budget is unstated. Suggested default: new characters enter with advances equal to the table's median, minus one — powerful from session one is the game's promise, and it should survive your funeral.

### Goal: character–faction interplay

8. 🔲 **Write the Crisis/PvP procedure.** Cohesion's entire payoff — the schism played out — is the one scene the contest engine doesn't adjudicate: who is "acting side" between PCs, who sets stakes, whether flaws and perks fire. A half page settles it (suggested: the GM frames stakes for both sides; initiator is acting side; harm rules unchanged; flaw perks flow normally — betrayal should pay).
9. 🔲 **Credit faction investment publicly.** The perk economy's known social risk is freeloading — everyone waits for someone else to fund the faction. Cheapest countermeasure from domain-play experience ([RPGnet domain-play thread](https://forum.rpg.net/threads/domain-level-play-experiences-and-advice.838392/), [EN World on bases and communities](https://www.enworld.org/threads/the-ttrpg-revival-of-pc-bases-strongholds-and-communities.684587/)): stamp the funder's name on everything perk-bought (*Brakk's Own*, *Halla's Priory*) and let the GM route fiction through named investments. Consider also: a character's *first* faction advance each arc costs 1 less.
10. 🧪 **Rival tempo should scale with table size.** Seven players generate eight faction actions a turn against each rival's one — big tables out-tempo the opposition mechanically. Consider giving rivals one action per *agenda rung completed by the players' faction*, or simply two actions when facing tables of six-plus. Playtest which feels fair rather than punitive.
11. 🔲 **Bridge personal loot.** "What's my cut?" has no answer: gear is permission, stock is the faction's, perks are effort. Suggested: personal wealth is fiction until a player wants it to matter, at which point it converts to Position edges or (at the GM's price) stock — never to perks. One paragraph in the faction resources chapter closes the heist genre's most predictable question.

### Goal: accessible to everyone, kind to the GM

12. 🔲 **Ship "Your First Venture."** The single highest-impact addition available: the Undercroft campaign already exists across the examples — assemble it into a runnable starter (the four session-zero characters as pregens, a three-scene opening job, one faction turn on rails, the Consortium as antagonist). Onboarding research is unanimous that teach-by-play beats exposition, and this book currently teaches brilliantly but hands the new GM nothing to *run*.
13. 🔲 **Consolidate a conditions reference.** The status-effect system is scattered across five chapters as examples. One appendix table — name, tier, typical exit, which scale it bites at — plus space on the sheets. (The quick reference has the rule; the table needs the vocabulary.)
14. 🔲 **Add an opposition gallery.** Four template rows are not a bestiary. A dozen statted antagonists across the five genre frames — each a pool, a track, one tag, one gift-equivalent, and a sentence of tactics — would cover most tables' first arc, and teach opposition design by example.
15. 🔲 **Absent-player rules.** Scheduling kills more campaigns than any mechanic; a faction game has a uniquely good answer available — absent officers are *on assignment*: their synergy still applies, their downtime auto-resolves as Work or Recover, and their node doesn't starve because a player had a work trip. Three sentences, large payoff.
16. 🔲 **Expand safety guidance beyond a name-drop.** The book aims at first-time players and then says "lines and veils" without explaining them. Two paragraphs and a link-out, or cut the reference.

## What the System May Be Missing Entirely

Flagged by the cold read and the research as absent layers, in rough priority order:

| Missing piece | Why it matters | Effort |
| --- | --- | --- |
| Starter scenario with pregens | The accessibility promise is unbacked without it | Medium — mostly assembly |
| Powers/magic module | High-magic tables currently improvise from the Mind's chassis | Large — already tracked in [Open Questions](appendix/open-questions.md) |
| Opposition gallery | GM invents every enemy from four rows | Medium |
| Exploration/travel guidance | The third classic pillar; clocks and bands can carry it, but nobody says how | Small — one GM-guide section |
| Conditions reference table | The de facto status system has no index | Small |
| Campaign-end / era-transition procedures | The agenda ladder promises an "end of era" it never details | Small |
| VTT / play-aid assets | Sheets exist; shared-table digital play has nothing | Large, later |

## The Shortlist

If only five things happen before the next playtest, the merged review says they should be: **goal prompts on the class pages · "Your First Venture" · the Crisis/PvP half-page · absent-player rules · the conditions table.** Three of the five are under a page of writing; none touches the core engine — which both reviewers, independently, judged to be the strongest thing in the book.

<div class="flourish">❖ ❖ ❖</div>

*Sources consulted for this review, beyond those linked inline: [player experience evaluation in TTRPGs (ACM)](https://dl.acm.org/doi/fullHtml/10.1145/3582437.3582457), [The RPG Gazette on campaign burnout](https://therpggazette.wordpress.com/2025/05/07/the-gms-empty-tank-recognizing-and-combating-campaign-burnout/), [Apothecary Press on failed campaigns](https://apothecary.press/2024/01/01/when-campaigns-fail/), [Chris Longhurst on decision-making systems](https://medium.com/@potatocubed/systems-systems-everywhere-b8783d58a9e4), and the design-lineage sources in [Design Notes](appendix/design-notes.md).*
