# Decisions Log — "This Cursed Throne"

Everything resolved since the original design-notes conversation
(`design-notes-original.txt`), in the order it was decided. Treat entries
here as locked unless the designer explicitly reopens them.

## Title
The game is titled **"This Cursed Throne"** (working title "Throne Game"
retired). The throne itself is literally cursed — this is the core
thematic conceit, and it retroactively frames mechanics already built:
the King's permanent +10 Legend, the King's harsher events-table draws
while crowned, and the Doom Clock all read as symptoms of the throne's
curse rather than abstract balance devices.

## The 8 original open questions

1. **Unclaimed pool default recipient:** newly generated resources always
   just sit in the unclaimed pool — no automatic/narrative assignment. A
   house must spend a task (a STATIC CHECK) to claim them, same as any
   other unclaimed resource. Keeps the task economy central.

2. **What the Calamity is:** a per-campaign SELECTABLE MODULE, not one
   fixed lore fact. Candidate module types: magic-born (tied to Legend),
   external invasion, systemic collapse of the zero-sum economy, slow
   environmental/supernatural blight. Each module has its own escalation
   mechanics; the table picks one before a campaign starts. Module
   content itself still needs drafting.

3. **Legend's extra risk:** superseded by the King/Legend unification
   below — Legend's risk now lives entirely in the events-deck draw
   mechanic rather than a separate bolt-on rule.

4. **Win-by-exactly-1 competitive check margin:** replaced the flat rule
   with a 3-tier band width, validated via exact dice-pool math (d6 pool,
   success on 5-6, p=1/3 per die):
   - Larger pool <5 dice → any win is decisive (no denial band)
   - 5–13 dice → denial band width 1 (decisive needs margin 2+, same as
     the original rule)
   - 14+ dice (near the ~20 stat cap) → denial band width 2 (decisive
     needs margin 3+)

   Reason: under the old flat rule, narrow/denial wins were 83% of all
   wins at 2v2 pools and only 29% at 20v20 — too punishing for young/weak
   houses. The 3-tier version holds narrow-win rate in a 36–63% band from
   pool size 5 up, and guarantees every win is decisive below pool size 5.

5. **Moniker trigger:** two-step. (a) ELIGIBILITY is mechanical — a
   leader crosses a Legend/events-table threshold to become eligible for
   a moniker pool. (b) CONFERRAL is a King's power, not automatic — the
   King decides whether/which eligible moniker actually gets bestowed,
   and can snub an eligible rival or delay. Mechanically free like Mercy;
   the cost lives at the table. Likely a new addition to the King's
   per-turn powers list — exact slotting TBD.

6. **Full trait table content:** still needs drafting (unblocked now that
   the shape-affecting questions below are resolved).

7. **Final task type list:** War, Trade, Diplomacy, Espionage,
   Stewardship, Magic (six total). Faith dropped as its own category
   (folds into Diplomacy/Stewardship flavor). Magic added as its own
   gated task type — same d6 pool mechanic, rolled against Legend, only
   attemptable by characters with the Magic trait.

8. **Character vs. house traits:** fully separate tables, no overlap.
   Confirms "a Cruel house can still produce a Pious relative."

## Birth Deal — card-based character generation

Replaces dice for character/birth generation. Uses a standard 52-card
deck, **always reshuffled after every birth** (fresh full deck each time,
no cross-birth or cross-house scarcity tracking).

1. Flip ONE card for trait count via rank lookup:
   - Ace–3 → 2 traits
   - 4–6 → 3 traits
   - 7–9 → 4 traits
   - 10–Jack → 5 traits
   - Queen → 6 traits
   - King → 7 traits
2. Flip that many additional cards, one at a time; each card's rank is a
   direct row-lookup on the 13-entry mixed (boon/burden) trait table — no
   separate roll-then-cross-reference step.
3. Magic conversion trigger (replaces the old "roll X-or-higher"
   threshold): an **Ace of Spades** is always eligible for conversion
   (~2% per card, any house) regardless of traits. If the house has the
   Magic house trait, **any face card** (J/Q/K, any suit, ~23% per card)
   is also eligible. Conversion remains a player CHOICE, not automatic.

This mechanic was arrived at after simulating and rejecting a "flip until
a stop condition" version (e.g. stop on a repeated rank) — any simple
stop-rule mathematically piles up 25–42% of births at the hard cap of 7
traits, which inverts the intent that Greater (6-7 trait) births should
be rare, not the norm.

Future production intent: the designer may eventually print dedicated
custom trait cards (trait text directly on the card face) instead of
using a standard deck + lookup table. If pursued, the underlying rank/
suit structure (13 ranks = 13 trait-table rows, Ace of Spades / face-card
Magic triggers) needs to carry over identically so the tuned count curve
and Magic rarity stay intact.

## Cards vs. dice — a game-wide principle

**Dice** = things a house/player actively DOES: the six task types (War,
Trade, Diplomacy, Espionage, Stewardship, Magic) — the whole competitive/
static check economy, unchanged from the original design.

**Cards** = things that HAPPEN TO a house or the realm: Birth (Birth
Deal, above), and the events table — which now also covers Kingdom Scene
reveals, unclaimed-pool-feeding random events, AND Calamity checks (one
unified deck/system instead of Calamity staying separate on dice).

## The unified events deck

- **Suit = event category (flavor only):**
  - ♥ Hearts — Dynastic/Personal
  - ♦ Diamonds — Wealth/Trade
  - ♣ Clubs — Military/Political
  - ♠ Spades — Calamity/Doom-flavored
- **Rank = outcome quality**, low→high runs bad→good.
- Deck is **always reshuffled** after every draw (fresh 52-card deck each
  time), consistent with Birth Deal.

## King + Legend, unified into one rule

Originally drafted as two separate rules (a King-specific "draw 2 take
worse" and a separate Legend-specific Doom Clock trigger) — deliberately
simplified into one after designer feedback that the two-rule version was
"too crunchy":

- Becoming King grants an immediate **+10 Legend** (the crown's burden
  IS a Legend increase — no separate King-only mechanic). This does
  **NOT revert** after losing the crown; it's permanent. Thematically
  load-bearing under "This Cursed Throne" — the crown's mark never fully
  washes off.
- For every 10 Legend a house has, it draws **one extra card** at the
  events table; when multiple cards are drawn, **keep the lowest**
  (worst). A King (always Legend 10+ once crowned) always draws at least
  2 and keeps the worst; a non-King house with Legend 25 draws 3 and
  keeps the worst of those.
- **Doom Clock trigger:** if the kept (lowest) card is an Ace, 2, or 3,
  the Doom Clock advances by 1. Reuses the same low-rank threshold
  already established in Birth Deal's trait-count table rather than
  inventing a new concept.

## Setup Order (see `rulebook/setup-order.md`)

Full step-by-step campaign setup, written with no assumed knowledge:
- Minimum 4 players, proposed soft cap ~6-7 (unconfirmed)
- Calamity module chosen by the table before anything else (content TBD)
- Starting resources: 12 points per house, split across Land/Manpower/
  Wealth by player choice, minimum 1 in each stat
- Starting Honor/Infamy: 0 for every house
- Starting Legend: 0 for every house
- House traits: 2 chosen + 2 rolled (trait table content TBD)
- House Leader generated via full Birth Deal, same as any birth
- Each house also starts with a spouse and at least 1 child for the
  Leader (spouse generation method and multi-child rules still proposed
  defaults, not fully confirmed)
- Throne starts vacant; first King emerges through play

## Turn Order (see `rulebook/turn-order.md`)

Full decade loop, five phases, written with no assumed knowledge. Key
points not obvious from the original design notes:
- Tasks assigned in Phase 5 of one decade resolve at the top of Phase 1
  of the NEXT decade — a full decade of in-fiction lag between assigning
  a task and its outcome.
- **Scenes are freeform by default**, only calling for a dice-pool check
  (STATIC/COMPETITIVE, matching task type) when something concrete is
  actually being risked. Reuses the task-resolution system rather than a
  separate scene mechanic.
- Each house declares exactly 1 scene per decade, flat regardless of
  player count.
- The King's per-turn powers (must grant, may redistribute, may confer a
  moniker, may move 1 house's position in house order) all happen during
  Phase 4 (Kingdom Scene), after the GM's events-deck reveal and after
  any Revolt resolution.
- A declared Revolt resolves at the Kingdom Scene later in the SAME
  decade it was declared, not the following decade's.
- The House Leader can be personally assigned to a Task like any other
  relative — no restriction keeping them home.

House order changes only when a King spends a per-turn power to move one
house's position (see below) — it never rotates on a fixed schedule.

## Setup/turn order follow-up pass (resolved 2026-08-11)

- No upper player-count cap; minimum 4 stands alone.
- Starting spouse generated via full Birth Deal, same as the Leader.
- Starting children: exactly 1 by default; a house with the **Fecund**
  house trait starts with 1-2 *extra* children instead, determined by a
  single card flip (rank Ace-6 → 1 extra, rank 7-King → 2 extra), each
  generated via Birth Deal individually.
- **House order** (e.g. seating order) is established at setup and sets
  priority when two houses' declared scenes conflict during play.
- Traits CAN change after generation: whenever a character is directly
  involved in a Destiny-triggering event, they may swap one existing
  trait for a newly flipped one (single card flip, same 13-entry trait
  table as Birth Deal). Reuses the existing Destiny trigger list rather
  than a new "how major is major" judgment call.
- Resolution phase internal order flipped: births/deaths are now rolled
  BEFORE task outcomes are checked (not after) — this makes it possible
  for a relative to die before their own pending task resolves. A task
  whose assigned relative died this Resolution **auto-fails**, no roll.
- Conflicting scene declarations are adjudicated by house order (see
  above) — earlier house in the order gets their scene as declared.
- One Task per relative per decade (no double-booking across two Tasks).
  A relative involved in this decade's Scene CAN also take a Task the
  same decade, but at most 2 relatives per house may be double-booked
  (Scene + Task) in a single decade.

## Geography — house order as the map (see `rulebook/geography.md`)

House order isn't just a scene-conflict tiebreaker — it's a **ring**,
with the King's seat as the capital. Every house has exactly 2
neighbors (immediate left/right in the ring); those are its only
borders. The **War task can only target a ring-adjacent house** — every
other task type (Trade, Diplomacy, Espionage, Stewardship, Magic) stays
unrestricted by geography, since only armies are geography-bound. The
King's house keeps its normal ring position — being the capital is
flavor, not a mechanical hub, and grants no extra war targets or
protection.

This gives real teeth to the King's per-turn power to move 1 house's
position (resolved earlier): moving a house now changes who can go to
war with whom, not just scene priority. The King quite literally draws
the borders.

Still open: how house order is initially arranged into a ring at setup
(does seating order = ring order automatically?), and what happens to
adjacency when a house falls/collapses entirely.

## Birth & Death — the Fate Check (see `rulebook/birth-death.md`)

Resolves the biggest remaining structural gap. Only the House Leader,
spouse, and direct descendants are mechanically tracked (no procedurally
generated extended family). Introduces **age** (decades since birth;
Leader/spouse start at age 3, ~30-39 years old).

- **Death check:** one card flip per tracked relative per decade. Death
  band widens with age (0-2 → Ace, 3-5 → Ace-2, 6-8 → Ace-4, 9+ → Ace-7).
  Sickly shifts a character up one age tier; Long-Lived shifts down one
  tier (floor at the youngest band). Validated by simulation: baseline
  median death age ~50 years (mean ~51); Sickly drags the mean to ~33;
  Long-Lived extends it to ~68.
- **Birth check:** one card flip per viable couple per decade (not
  age-weighted, unlike death — deliberately not stacking two new curves
  in one pass). Birth on Queen-King (~15.4%). Fecund widens this to
  9-King (~30.8%); Barren removes the birth range entirely (heirs only
  via marrying in).
- Both checks run during Resolution step 1, before task outcomes are
  checked in step 2 (unchanged from the prior setup/turn-order pass).

"Who dies" is resolved by construction: since every relative is checked
individually against their own card, whoever's flip lands in their death
band is who dies — no separate house-level pick needed.

## Still open / not yet drafted

- Calamity module content (the actual magic-born / invasion / systemic-
  collapse / blight entries)
- Full trait table content (house traits, character traits — confirmed
  separate tables, entries not yet written)
- Events table content (the actual Hearts/Diamonds/Clubs/Spades entries
  per rank)
- Whether the spouse can start at a different age than the Leader by
  player choice, or must always match
