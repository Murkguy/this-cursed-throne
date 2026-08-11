# Claude Code Handoff — "Throne Game" (working title, now "This Cursed Throne")

## What this is
Pick up an in-progress original TTRPG design and set it up properly as a
project: a GitHub repo, organized docs, and continued iterative design work
inside Claude Code. This is a companion project to "Rifts & Revolvers" —
same designer, same collaborative approach, different game.

The attached file `design-notes-original.txt` is the full running design
doc from a long design conversation with Claude (chat), preserved as-is.
It's the source of truth for the decisions made in that conversation. See
`decisions-log.md` for everything resolved since (the game's actual title
is now "This Cursed Throne").

## The pitch
A Game of Thrones-style political RPG. Each player leads a noble House and
plays across DECADES, not single scenes — a campaign can span generations,
with characters dying/aging out and heirs stepping up. It's explicitly a
hybrid: RPG-first (roleplayed scenes, character voice, narrative stakes),
with board-game-style systemic backbone underneath (zero-sum resource
economy, dice-pool task resolution, structured turn phases) to keep it
tight, fast, and playtestable rather than sprawling into freeform. The
throne itself is literally cursed — that's now the core thematic conceit,
and several mechanics (the King's permanent Legend mark, harsher draws
while crowned) are the curse made mechanical.

**Win condition:** highest stats once the realm's looming Calamity has been
survived/avoided. You cannot win by seizing the throne while the realm
collapses — the crown only counts if the realm endures.

## How the designer works (important — read before generating content)
- Talks through design decisions collaboratively before committing —
  doesn't want unilateral rewrites of settled mechanics.
- Makes decisive, definitive calls once a topic has been discussed; once
  something is marked RESOLVED, treat it as locked unless the designer
  explicitly reopens it.
- Comfortable with, and values, quantitative/math validation to stress-test
  intuitions (dice-pool math, card-draw probability simulations) — this has
  caught real balance bugs (e.g. the original win-by-exactly-1 competitive
  check rule, and a naive card-flip mechanic that over-produced max-trait
  births).
- Actively pushes back on crunch — prefers fewer, unified rules over
  several narrow special-case rules (e.g. collapsed a separate King-draw
  rule and a separate Legend-draw rule into one shared mechanic when the
  two-rule version felt "too crunchy").
- Wants naming, tone, and mechanics to carry real thematic weight — avoid
  generic reskins.
- Prefers simple, fast-resolving mechanics (flat d6 pools, card flips) over
  granular/fiddly systems, because sessions need to cover 3-8 decades
  (30-80 years) in a couple hours.

## Current state
All 8 of the original open questions from the source chat are RESOLVED —
see `decisions-log.md` for the full list plus everything decided after
that (Birth Deal, the unified events deck, the King/Legend curse mechanic,
the game's actual title).

## What to do next
- Continue the same pattern: propose options with tradeoffs, let the
  designer make the call, mark decisions RESOLVED, keep `decisions-log.md`
  current.
- Don't draft full trait-table / events-table / Calamity-module content
  unprompted — the shape of those systems is now locked, but the actual
  entries haven't been written yet and should be talked through the same
  way everything else was.
