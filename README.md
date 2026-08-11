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
    suit+rank lookup), under active revision suit by suit
  - `character-traits-bank.md` — personality traits pulled out of the
    house table, held for the future character trait table
  - (character traits proper, events deck, Calamity modules not yet
    drafted)
- `rulebook/` — the eventual polished rulebook
  - `setup-order.md` — full campaign setup, step by step
  - `turn-order.md` — the five-phase decade loop
  - `birth-death.md` — the Fate Check (age, natural births/deaths)
  - `geography.md` — house order as the map of the realm, border wars
  - `tasks.md` — the six tasks: stats, check types, example actions
  - `house-archetypes.md` — House Archetype (7 options) and Succession
    Custom (4 options), setup-time choices distinct from house traits

## Status

All shape-affecting open questions are resolved (see `decisions-log.md`).
Core systems are specified: the decade loop, dice-pool task resolution,
Birth Deal (card-based character generation), the unified events deck,
the King/Legend curse mechanic, and the Fate Check (birth/death). Table
*content* (actual trait entries, Calamity modules, events) has not been
drafted yet.
