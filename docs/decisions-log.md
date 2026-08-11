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

## Decade 1 must produce a King (see `setup-order.md` step 6 and
`turn-order.md` Phase 4)

The throne starts vacant (already resolved), but **it cannot stay vacant
past Decade 1** — this is a deliberate exception to the otherwise fully
reactive King/Revolt system. If a house declares a bid during Decade 1's
Scene Declaration, it resolves normally at that decade's Kingdom Scene.
If nobody volunteers, the GM flips one card per house at Decade 1's
Kingdom Scene; the house with the highest card is forced onto the
throne (redraw among ties). "The curse doesn't wait for volunteers." No
other decade has this forcing rule — after Decade 1, the throne can sit
vacant indefinitely if no one bids.

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

The initial ring arrangement is pure table negotiation — players sort
out who sits where at setup, no roll or fixed rule involved.

**When a house falls, the ring closes the gap** — its two former
neighbors become newly adjacent to each other. **The player is not
eliminated** — they build a brand new house using the identical setup
procedure (full 12-point budget, no restart penalty), inserted into the
ring adjacent to a house of their choosing. Every player stays engaged
for the whole campaign.

**"House falls/collapses entirely" is now defined** — two independent
triggers: EXTINCTION (the House Leader dies with no living heir to
inherit) or RUIN (Land, Manpower, AND Wealth all hit 0 simultaneously —
deliberately not Land alone, to keep a low-Land/low-Manpower,
high-Wealth merchant-house archetype viable rather than perpetually on
the verge of collapse).

This surfaced that War — despite being the game's namesake conflict
task — had no way to actually kill anyone, only move resources. New
**War Death Check**: a relative assigned to a War task gets one
additional death check (same age/trait-adjusted band as the ambient
Fate Check, just a second flip) when that task's outcome is determined.
Win or lose, war is dangerous — no separate win/loss threshold, kept
simple per designer feedback.

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

## Tasks defined (see `rulebook/tasks.md`)

The six tasks never had more than a one-line gloss each. First pass
gave each a stat and one fixed check type; REVISED same day after
designer feedback that this was too abstract ("what do people gain
here?" — Espionage in particular had no defined payoff) and that a
single roll per task couldn't capture real differences in scale (a war
can be a border raid or a full invasion).

**Current model: each of the six tasks is a CATEGORY containing a menu
of named actions**, not one generic roll. Stat-per-category is
unchanged (War/Manpower, Trade/Wealth, Diplomacy/\|Honor-Infamy\|,
Espionage/Wealth, Stewardship/Land, Magic/Legend, Wealth shared by
Trade and Espionage), but check type is now per-ACTION, not per-
category — e.g. Trade has both a Static action (Broker Deal) and a
Competitive one (Trade War, "trade wars exist," deliberately NOT
restricted by geography the way War is).

Key actions per category: War gets Border Raid (standard) vs. Full
Invasion (+2 dice, double stakes, harsher War Death Check — the
scale distinction the designer specifically asked for). Diplomacy
leans roleplay-first (Arrange Marriage, Forge Alliance both grant a
lasting +2-dice bond between the two houses; Court Favor claims
unclaimed Honor; Broker Peace resolves vendettas). Espionage finally
has real payoffs: Assassinate (kill a targeted relative on a decisive
win), Turn a Relative (make them a secret asset), Steal Secrets (direct
Wealth theft + intel), Sow Rumors (Honor/Infamy manipulation). Magic
gets Scry, Curse, Commune, matching the original notes' own examples.
Stewardship keeps Develop Territory (claim unclaimed Land) and adds
Fortify (banks +2 dice for a future Espionage defense).

This resolved the house-trait-table's stacking question at the ACTION
level: since every individual action (not category) has exactly one
fixed check type, task-type and check-type trait bonuses are still just
two independent modifiers on the same pool — no conflict.

**REVISED again same day** after a detailed pass through every action:

- **War** split into a one-off action and a standing state. **Border
  Raid**: Manpower vs. the target's Stewardship (not Manpower vs.
  Manpower), 1 Wealth stakes, no death check. **War**: Manpower vs.
  Manpower, 1 Land + 1 Manpower stakes, AND — once declared — the same
  battle **auto-resolves every decade** without needing re-assignment,
  including a War Death Check each time, until either side resolves
  **Broker Peace**. This is a real structural change: War is now a
  standing state between two houses, not a single roll.
- **Trade** unchanged (Broker Deal / Trade War).
- **Diplomacy**: Arrange Marriage/Forge Alliance's bond now applies to
  ANY task the two houses take together, not just Diplomacy. Broker
  Peace dropped its roll entirely (pure roleplay, grants +1 Honor) and
  now also ends a standing War. New action **Invoke Faith** claims
  unclaimed Piety (see below).
- **Espionage** keeps all 4 actions with distinct effects: Assassinate,
  Turn a Relative, Steal Secrets (Wealth theft + intel), and Sow Rumors
  (Honor/Infamy damage, contested vs. Stewardship — this was briefly
  misnamed "Steal Secrets" mid-conversation and corrected).
- **Stewardship**'s Develop Territory now claims Land, Wealth, OR
  Manpower (player's choice) — Stewardship becomes the generalist
  pool-claiming option, Trade the specialist one (and the only path to
  a Trade War). Deliberate overlap.
- **Magic** dropped Commune, kept **Scry** (peek the next card of any
  deck before it's drawn), redefined **Curse** (Legend vs. the target's
  Piety — success inflicts "draw 2 keep worst" on the target's next
  relevant draw, reusing the same disadvantage mechanic as the King's
  harsh draw), and added **Bless** (target-only, never self; grants
  "draw 2 keep best" plus +1 Piety).

## Piety — a new 6th house stat

Added after the designer flagged "I feel like we're missing religion."
Full house-level stat, same zero-sum-with-growing-unclaimed-pool model
as Honor/Infamy, same ~20 soft cap, starts at 0 (never allocated at
setup). Claimed via Diplomacy's Invoke Faith. (Its role as Curse's
defense stat was superseded almost immediately — see Active vs. Passive
stats, below.)

## Active vs. Passive stats — a 7th stat (Cunning) and a rule split

REVISED again same day, twice more. First: after trying to patch the
"Piety has 0 actions" problem with invented actions (Crusade,
Excommunicate) that the designer didn't like, the fix was combo dice
pools instead — "War should be both manpower and wealth... maybe all
actions invoke combos of stats." Then, mid-revision, the designer
reframed the whole stat block: **Legend, Piety, and Honor/Infamy are
never rolled in Task actions at all.** Instead, they're PASSIVE —
checked by events (Kingdom Scene, house events) for who's highest/
lowest and rewarded or punished accordingly. This generalizes a pattern
Legend already had (Doom Clock trigger, moniker eligibility, the King's
+10, Birth Deal's trait bonus were all already "passive stat affects
external systems") and Honor already had (Destiny's ranking triggers) —
just locked as a universal rule covering all three, and explicitly
including Piety now too. Action OUTCOMES can still change a passive
stat (Bless still grants +1 Piety) — only the dice POOL is restricted.

That left only 3 stats (Land, Manpower, Wealth) available to roll,
which wasn't enough — Espionage in particular had been rolling on
Wealth the whole time, a mismatch for "spycraft." Added **Cunning** as
a 4th ACTIVE stat: your house's reputation for guile and trickery, NOT
zero-sum (grows through play like Legend — decisive wins on Espionage
or Border Raid grant +1). Starts at a flat **3** (not 0 like Legend/
Honor/Piety, not part of the 12-point budget) specifically so Espionage
and Border Raid aren't nearly impossible before any Cunning is earned.

**Combo dice pools COMBINE (add together) both stats**, REVISED from an
initial "lower of the two" rule the same day — the designer wanted
committing two resources to genuinely roll a bigger pool, not just be
bottlenecked by the weaker one. Accepted tradeoff: this reopens real
tension with the original "~20 dice stays rollable" pacing rationale
behind the stat caps (a house strong in both halves of a combo can roll
well past 20 on its biggest actions), kept intentional — big wars
should feel big at the table. Every action in `rulebook/tasks.md` was
remapped onto only the 4 active stats: War → Manpower+Cunning (raid) /
Manpower+Wealth (war), Trade → Wealth+Cunning / Wealth+Manpower,
Diplomacy → various Land/Wealth/Manpower/Cunning combos (Court Favor
and the new **Declare
Heresy** action use Cunning alone), Espionage → all Cunning-based now,
Stewardship → Land-based combos, Magic → all Cunning-based (Curse and
Bless dropped their Piety/Legend pools entirely, now Cunning vs.
Cunning or Cunning alone).

## Action-by-action correction pass (2026-08-11, same day)

Caught a real error: several actions were "opposed by the target's
Stewardship," but Stewardship is a task CATEGORY, not a stat — it rolls
Land. Fixed everywhere; any opposition now names the actual stat
(Land). Locked as an explicit rule: task categories are never
themselves rollable/opposable values.

Other fixes from a full designer pass:
- **Trade War** now rolls Wealth+Cunning (not Wealth+Manpower) vs. the
  same — fought with capital and guile, not soldiers.
- **Arrange Marriage** now only rolled for FOREIGN marriages (into/from
  another player house — NPC marriages need no roll). Success generates
  the incoming spouse via Birth Deal and grants a chance at a 1-Wealth
  dowry on a decisive win.
- **Declare Heresy** now explicitly uses Piety + a flat +2 — the second
  deliberate exception (after nothing previously) to "passive stats
  aren't rolled," justified because a religious accusation should scale
  with actual devotion.
- **Assassinate** gained a discovery/capture mechanic: win by any
  margin = clean kill; tie = kill succeeds but the assassin is
  captured; lose by 1 = clean failure; lose by 2+ = failure AND
  captured. Capture doesn't auto-kill the assassin — they become a
  prisoner, a narrative complication rather than a resolved death.
- **Turn a Relative** removed entirely — too hard to track reliably.
- **Steal Secrets** redefined: no longer Wealth theft — now lets the
  attacker choose ONE of the target's passive stats (Piety, Honor/
  Infamy, or Legend) to damage, representing flexible blackmail.
  **Sow Rumors** keeps its narrower original niche (Honor/Infamy only)
  next to Steal Secrets' new flexibility.
- **Magic** reworked a second time: now uses Legend + Cunning for every
  action (not Cunning alone) — the third deliberate exception to
  "passive stats aren't rolled," justified because Magic is
  thematically unique enough to warrant it. Reverses the previous
  all-Cunning version from the prior revision.

Still open: the STATIC check target number (proposing 2 successes as
default, not yet confirmed); Assassinate's exact win/tie/loss
breakpoints (written as best-reading, not explicitly confirmed);
whether the Pious house trait should be updated now that Piety exists
as a real passive stat; the actual events-deck CONTENT that checks
passive stats is future table-content work, not yet drafted.

## Margin-completeness pass (2026-08-11, same day)

Audited every COMPETITIVE action for a fully spelled-out decisive/
narrow/loss (or equivalent) outcome — none should say just "success" or
defer to "same as X action" without restating it inline. Found and
fixed three gaps: **Trade War** was deferring to "same as Border Raid,"
now spelled out inline. **Declare Heresy** was missing its narrow-win
case entirely — added (suspicion, -2 Diplomacy but only until the
target's next Diplomacy attempt, vs. the indefinite penalty on a
decisive win). **Curse** only said "Success," no margin differentiation
at all — now decisive win afflicts the next TWO relevant draws, narrow
win just the next ONE, and loss backfires onto the caster.

Also caught a real bug while auditing: **Arrange Marriage** is STATIC
(pure pass/fail, no margin grading — an established rule from the
original design), but had been written with decisive/narrow-win
language for the dowry. Fixed: the dowry "chance" is now a separate
card flip after a successful marriage roll (Queen or King grants it),
not a margin outcome — keeps the Static check itself properly binary.

## House Trait Table (see `tables/house-traits.md`)

Drafted 2026-08-11, REVISED same day after playtester feedback that the
first version's roll mechanic (flip 2 cards, sum ranks 2-26, 25 entries)
was hard to grasp — summing added arithmetic on top of a lookup.

**Current mechanic: 52 entries, flip 1 card, direct lookup** by its
exact suit+rank, no math at all. Reuses the events deck's suit-as-
category language (♥ Dynastic/Personal, ♦ Wealth/Trade, ♣ Military/
Political, ♠ Calamity/Doom) so it's not a new thing to learn — same four
categories, same meanings. Rank runs roughly mundane-to-dramatic from
Ace to King within each suit. Both the 2 chosen and 2 rolled house
traits (see the 8 original open questions, #8) come from this same
52-entry list. Duplicates reroll; Fecund/Barren and Sickly/Long-Lived
are mutually exclusive pairs.

Every entry has a real benefit and a real cost — mostly a +2/-2 dice
pair across two of the six task types, with bespoke mechanics for the
traits that already had defined effects elsewhere (Sickly, Barren,
Fecund, Long-Lived from `birth-death.md`; Magical, referenced by Birth
Deal's Magic-conversion rule) plus a few new capstone traits at King
rank per suit (Cursed, Golden, Tyrannical, Harbinger).

**Golden** (Diamonds K) changes the starting resource budget from 12 to
14 points — this reordered `setup-order.md` step 3 so house traits are
now generated BEFORE resource allocation (previously the other way
around), since a house needs to know if it has Golden before spending
its budget.

Still open: whether task-type bonuses and check-type bonuses (Static vs.
Competitive) can stack when a task is both at once — not yet checked
against how the dice-pool rules are actually written.

## House trait table — suit-by-suit revision pass (in progress, 2026-08-11)

Started reviewing the house trait table suit by suit (Hearts first).
Two rules emerged and are now locked for the rest of the pass:

1. **House-level vs. personal traits.** A house trait must describe
   something the whole dynasty shares across generations — a military
   tradition, a bloodline curse, a mercantile reputation — not one
   person's mood ("we won't have a house full of timid people"). Traits
   that read as individual personality get pulled and moved to
   `tables/character-traits-bank.md`, a holding pen for the future
   character trait table, with a house-appropriate replacement drafted
   at the same rank.
2. **Rank-tier magnitude curve.** Within each suit, low ranks (A-4) skew
   weak benefit / strong cost, mid ranks (5-8) stay roughly balanced,
   high ranks (9-K) skew strong benefit / weak cost — reusing the same
   low=bad/high=good convention as everything else card-based in the
   game. Traits don't need to be precisely balanced against each other,
   only internally honest for their own rank.

**Hearts, revised**: Timid, Humble, Hot-Blooded, Doting, Prideful,
Vengeful, and Restless were pulled (personal, not dynastic) and banked.
Replaced with 7 new house-level traits at the same ranks/magnitudes:
Inbred Line (A), Fostering Tradition (3), Kinslayers (5), Hostage
Culture (6), Long Memory (8), Ancestral Seat (9), Grand Lineage (J).
Sickly, Barren, Fecund, and Long-Lived were repositioned within the
suit (not renumbered in content, just moved to ranks matching their
already-existing benefit/cost weight — Sickly and Barren's severe costs
fit low ranks, Fecund and Long-Lived's strong benefits fit high ranks).
Cursed (K) had its cost lightened (dropped the "always draws 2 keep
worst on any draw" penalty down to a single -1 Diplomacy die) so the
rarest card in the suit reads as net-positive, matching the curve.

Diamonds, Clubs, and Spades still need the same two-rule treatment
applied. Paused mid-review of Diamonds (drafted, awaiting confirm) for
House Archetype/Succession Custom — see below.

## House Archetype & Succession Custom (see `rulebook/house-archetypes.md`)

Surfaced by the designer noting the trait table only covered a generic
landed noble house — "think of all the powers in these books, they're
noble houses, merchant houses, bands of men, priestly cloisters, etc."
These are explicitly NOT house trait table entries — a separate
setup-time choice, made once per campaign, alongside (not instead of)
the 4 house traits.

**House Archetype** (7 options, all require some official/legitimate
standing in the realm — a criminal syndicate and an unsanctioned raider
fleet were both considered and cut for lacking that): Noble House
(baseline, no bonus/cost), Merchant House (+1 Trade/-1 War), Mercenary
Company (+1 War/-1 Stewardship), Priestly Cloister (+1 Invoke
Faith+Declare Heresy/-1 Trade, plus a new **Ordain a Novice** action —
generates a relative via Birth Deal starting at age 2, an adult
convert, as an additional growth path alongside normal births), Magical
Order (auto-grants the Magical house trait's effect without spending a
trait pick, -1 War), Knightly Order (+1 War/-1 Trade), Scholarly Order
(+1 Stewardship/-1 Diplomacy).

**Succession Custom** (4 options) closes a real, previously-unresolved
gap — how the game picks a new Leader when the old one dies. All four
are fully deterministic (on purpose — 3 other candidates considered,
Elective/Strongest-Claims-It/Gavelkind, were cut for not working well
for planning): Primogeniture (eldest child, any gender), Patriarchal
(eldest son, daughters only if no sons), Matriarchal (eldest daughter,
sons only if no daughters), Ultimogeniture (youngest child — new
addition beyond the original 3-option draft). If no qualifying child is
alive, the house hits the existing EXTINCTION collapse condition — a
surviving spouse never inherits under any custom.

Reordered `setup-order.md` step 3: Archetype/Succession Custom is now
chosen FIRST (3a), before house traits (3b, was 3a) — Magical Order
auto-granting the Magical trait means a player needs to know their
Archetype before spending a free trait pick that might now be
redundant. Resource allocation moved to 3c, Honor/Legend/Piety/Cunning
to 3d-3g.

Still open: whether a spousal-regency exception is wanted for
succession (currently: no, by design, not an oversight).

## Face-card traits get more interesting mechanics; new Trade action: Renegotiate

Designer wants J/Q/K entries to feel like a different KIND of reward,
not just bigger dice numbers — the same spirit as **Golden** (which
changes the starting resource budget, not a dice pool). Brainstormed a
menu of mechanic types (breaking an established rule once, bending
Succession Custom, reaching into the King's business, touching the
Doom Clock, bigger card manipulation, extra economy actions) for future
face-card design.

That led to a genuinely new task: **Renegotiate** (Trade category,
`rulebook/tasks.md`) — NO ROLL, same cooperative-deal principle as
Broker Peace. Restricted to ring-adjacent houses only (trade routes run
along shared borders, same logic as why War is ring-locked, but for
cooperation instead of conflict). Two neighboring houses may mutually
exchange any amount of Land, Manpower, or Wealth for any other, at
whatever rate they agree to. Doesn't touch the unclaimed pool, just
redistributes between two consenting houses. Not capped per use — each
use still costs a Task Assignment slot on both sides, which already
rate-limits it, but flagged as worth watching for resource
consolidation between cooperating players.

Still open: the actual face-card mechanic upgrades themselves (only the
brainstormed menu exists so far, not concrete J/Q/K designs beyond
Golden, which was already locked).

## Hearts fixes: Sickly, Barren, Long-Lived (2026-08-11) — HEARTS LOCKED

Restarted the Hearts review after the Archetype/Renegotiate detour and
caught three problems. **Hearts suit is now fully locked** — all 13
entries confirmed. Diamonds is next.

- **Sickly** (2) — its only benefit (a narrow Magic-conversion trigger
  widening) felt thin next to a real cost (death band +1 tier). First
  tried adding +1 Piety alongside the widening, then dropped the
  widening entirely as still lackluster — final: **+2 Piety** alone
  ("suffering breeds deep devotion"), a single tangible payoff instead
  of one strong effect plus one weak one.
- **Barren** (4) — "no natural births, ever" with no concrete
  alternative path was effectively a death sentence: eventually the
  house has no heir and hits Extinction with no way to prevent it. Gave
  it a real lifeline: unlocks a new action, **Adopt an Heir** (Diplomacy
  category, `rulebook/tasks.md` — STATIC, Wealth + Land, generates a
  relative via Birth Deal at age 2), reusing the same structure as the
  Priestly Cloister archetype's Ordain a Novice. A Barren house isn't
  doomed anymore, it just grows differently — spending Task Assignment
  slots on adoption instead of relying on the passive Fate Check.
- **Long-Lived** (Q) — its cost (-2 Magic) was heavier than the Q-tier
  curve calls for (strong benefit / weak cost, -1 max), making it read
  as nerfed relative to its rank. Dropped to -1 Magic.

## Diamonds: magnitude curve applied, then 9/J/Q reworked (2026-08-11) — DIAMONDS LOCKED

The magnitude-curve redesign for Diamonds had only ever been proposed
in chat, never written to the file — fixed. Also fixed Golden's cost
from -2 to -1 to match its K-tier weak-cost expectation (same issue as
Hearts' Long-Lived).

Then reworked three entries per designer feedback that they still felt
flat:
- **Charitable** (9) simplified from a bespoke Honor-redirect mechanic
  to a plain +2 Diplomacy / -1 Trade die bonus.
- **Ostentatious** (J) now makes this house's STATIC Diplomacy actions
  always succeed (no roll needed) instead of a flat +3 dice bonus.
- **Landed Gentry** (Q) went through two versions. First: Land could
  never be reduced below 1 by any means — rejected as game-breaking
  (permanent Ruin immunity, and it conflicted with how War/Trade War
  captures are supposed to resolve when a decisive win would take a
  house's last Land point). Second version — a single-use-per-campaign
  reactive save (keep 1 Land when it would hit 0) — was then judged too
  weak, since it might never trigger at all over a whole campaign if
  the house never gets close to 0 Land. **Final version**: a proactive,
  guaranteed benefit instead — once per campaign, immediately claim 2
  Land from the unclaimed pool for free, no roll needed. Open edge
  case: what happens if the pool has less than 2 Land available at the
  time.

## Clubs suit reworked (2026-08-11)

Applied the now-established two rules directly (house-vs-personal audit
+ magnitude curve) rather than presenting the stale version first —
only **Cowardly** needed migrating to the character trait bank (personal,
not institutional); Clubs' political/military reputation traits read as
institutional far more naturally than Hearts' emotional ones did.
Replaced with **Client House** (a subordinate house reliant on a
patron's protection). Also gave the J/Q face cards unique mechanics,
consistent with the Diamonds precedent: **Warmonger** (J) now means the
War Death Check only applies on a loss, never a win; **Kingmaker** (Q)
means this house's contribution to a Revolt alliance bloc counts double.

## Still open / not yet drafted

- Calamity module content (the actual magic-born / invasion / systemic-
  collapse / blight entries)
- Character trait table (separate from house traits, confirmed distinct,
  not yet drafted)
- Events table content (the actual Hearts/Diamonds/Clubs/Spades entries
  per rank)
- Whether the spouse can start at a different age than the Leader by
  player choice, or must always match
