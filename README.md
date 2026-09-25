# This Cursed Throne

A political TTRPG of dynasty and decline. Each player leads a noble House
across DECADES, not single sessions — a campaign can span generations,
with characters dying/aging out and heirs stepping up. The throne itself
is cursed; you cannot win by seizing power while the realm collapses —
the crown only counts if the looming Calamity has been survived.

**Rules reference site:** https://murkguy.github.io/this-cursed-throne/
— lives on the `gh-pages` branch, rebuilt manually (not auto-synced
with `master`) whenever the reference content needs updating.

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
  - `character-traits.md` — the 52-entry character trait table (1
    card, direct suit+rank lookup, same 4 categories as house traits)
    used by Birth Deal — **LOCKED**
  - `character-traits-bank.md` — historical: the personality traits
    originally pulled out of the house table, now folded into
    `character-traits.md` above
  - `calamity-shared-endgame.md` — mechanics shared by every Calamity
    module (Competitive-vs-Calamity trials, decade×trial scaling,
    alliance, the standard decisive/narrow/loss shape, the survivor
    score tally that answers "how does a campaign conclude, who wins")
  - `calamity-magic-born.md` — 1st of 4 Calamity modules, **DRAFTED**
  - `calamity-invasion.md` — 2nd of 4, **DRAFTED** — its Doom Clock
    trigger (Ace/2/3 of Spades in the events deck) is now resolved
  - `calamity-blight.md` — 3rd of 4, drafted but **PINNED, not
    locked** — the shared 3-trial shape felt too reskinned across
    modules; wants genuinely distinct mechanics on a future pass
  - `events-deck.md` — the 52-entry table drawn every Kingdom Scene —
    **LOCKED**. Varied effect types (dice bonuses, free task attempts,
    cursed/blessed luck, alliance bonds, PERSONAL death-check/trait-
    gain cards hitting a fixed Leader/heir role, a CONTEST card per
    suit), plus randomized pool amounts instead of flat numbers
  - (the 4th Calamity module — economic collapse — not yet drafted)
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
survivor score tally. **Magic-born and External Invasion are locked**
(`tables/calamity-magic-born.md`, `tables/calamity-invasion.md`); a
**Blight** draft exists but is pinned pending more distinct mechanics.
**The character trait table is now locked** (`tables/character-traits.md`),
and **the events deck is now locked** (`tables/events-deck.md`) — the
last remaining playtest blocker is gone. **The game is fully
playtestable now**, using Magic-born or External Invasion as the
Calamity module. Remaining content: the Economic Collapse Calamity
module, and a Blight rewrite with more distinct final-round mechanics.
