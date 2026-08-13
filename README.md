# This Cursed Throne

A Game of Thrones-style political TTRPG. Each player leads a noble House
across DECADES, not single sessions — a campaign can span generations,
with characters dying/aging out and heirs stepping up. The throne itself
is cursed; you cannot win by seizing power while the realm collapses —
the crown only counts if the looming Calamity has been survived.

Companion project to *Rifts & Revolvers* (same designer, same
collaborative design approach).

## Structure

- `docs/` — design notes and decision history
  - `design-notes-original.txt` — the frozen original design-conversation
    transcript
  - `claude-code-handoff.md` — how this project got set up, and how the
    designer likes to collaborate
  - `decisions-log.md` — everything resolved since the original notes,
    in order (start here for current state)
- `tables/` — trait tables, the events deck, Calamity modules
  - `house-traits.md` — the 52-entry house trait table (1 card, direct
    suit+rank lookup) — **LOCKED**, all four suits confirmed
  - `character-traits-bank.md` — personality traits pulled out of the
    house table, held for the future character trait table
  - `calamity-shared-endgame.md` — mechanics shared by every Calamity
    module (Competitive-vs-Calamity trials, decade×trial scaling,
    alliance, the standard decisive/narrow/loss shape, the survivor
    score tally that answers "how does a campaign conclude, who wins")
  - `calamity-magic-born.md` — 1st of 4 Calamity modules, **DRAFTED**
  - `calamity-invasion.md` — 2nd of 4, **DRAFTED** (one content
    dependency flagged: its Doom Clock trigger needs specific
    events-deck cards that don't exist yet)
  - (character trait table proper, events deck, and 2 more Calamity
    modules — economic collapse, blight — not yet drafted)
- `rulebook/` — the eventual polished rulebook
  - `setup-order.md` — full campaign setup, step by step
  - `turn-order.md` — the five-phase decade loop
  - `birth-death.md` — the Fate Check (age, natural births/deaths)
  - `geography.md` — house order as the map of the realm, border wars
  - `tasks.md` — the six tasks: stats, check types, example actions
  - `house-archetypes.md` — House Archetype (7 options) and Succession
    Custom (4 options), setup-time choices distinct from house traits
  - `king-and-revolt.md` — how a house takes and loses the throne
    (Revolt: bids, alliances, the roll, failure cost, Mercy), and
    Destiny (the single-use flag, how it's earned and spent)
  - `gameflow.md` — consolidated linear walkthrough of the whole game,
    setup through a played-out example campaign; doesn't redefine any
    rule, cites the other rulebook files for detail

## Status

All shape-affecting open questions are resolved (see `decisions-log.md`).
Core systems are specified: the decade loop, dice-pool task resolution,
Birth Deal (card-based character generation), the unified events deck,
the King/Legend curse mechanic, and the Fate Check (birth/death). The
**house trait table is fully drafted and locked** (52 entries, all four
suits). The endgame gap `gameflow.md`'s worked example surfaced (no
mechanic existed for what happens when the Doom Clock maxes out, or
what "surviving the Calamity" means) is now resolved: each Calamity
module ends in a final-round gauntlet of bespoke trials, then a
survivor score tally. **Magic-born and External Invasion are drafted**
(`tables/calamity-magic-born.md`, `tables/calamity-invasion.md`).
Remaining content: character trait table, events table, and 2 more
Calamity modules (economic collapse, blight).
