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

## Trait table framework overhaul: ACE-HIGH tiers (2026-08-11)

Triggered by feedback that Great Warriors (rank 3, weak tier) didn't
match its iconic name, and Tyrannical (K) felt too nerfed relative to
holding the crown. New system, replacing the earlier ascending-rank
magnitude curve entirely:

- **Rank order flips to ACE-HIGH** — 2 is the worst card, Ace is the
  best. Reverses the low-to-high convention used elsewhere in the game
  (Birth Deal, the events deck) — deliberately, for this table only.
- **Ranks 2-4**: net **-1 die** total (benefit minus cost). Rank 2 also
  carries a bespoke restriction beyond dice, not just a numeric one.
- **Ranks 5-7**: net **0** — a pure sidegrade, reflavors capability
  without a net power change.
- **Ranks 8-10**: net **+1 die** total.
- **J, Q, K, A**: abandon dice math entirely — each is a unique,
  strictly positive mechanic (no more flat bonuses at this tier).

**This reopens Hearts and Diamonds**, both previously locked under the
old system — they need the same refactor. Clubs was rebuilt fully under
the new framework first (see above entry) as the template: Great
Warriors moved rank 3→8 and de-nerfed (+2 War/-1 Diplomacy); Tyrannical
softened (-2→-1 per other task while holding the crown); Ambitious
redesigned into a bespoke Ace-tier mechanic (declare War on the King's
house without ring-adjacency, once per campaign) instead of flat dice.

Rank 2 went through two versions. First: **Client House**, a
patron-permission-gate on declaring War — designer didn't like it.
**Final: Ill-Trained Levies** — instead of a flat dice penalty, this
house's Manpower-based rolls (War, Border Raid) only count 6s as
successes, not the normal 5-6, roughly halving their effective success
rate. A genuine success-threshold-level restriction rather than just
fewer dice, matching the "rank 2 also alters playstyle" rule more
literally than a permission-gate did.

Warmonger and Kingmaker were then flagged as too narrow/situational to
feel like real face-card rewards — Warmonger's death-check tweak might
never come up, and Kingmaker just amplified an already-universal option
(any house can already join a Revolt bloc). Reworked: **Warmonger**
now doubles capture stakes on a decisive War/Border Raid win.
**Kingmaker** now grants +3 dice to whichever Revolt side this house
backs, independent of its own stat contribution — the point is their
endorsement matters, not their army. **Tyrannical**'s benefit was also
still flat dice (+2 War), which belongs in the 8-10 tier, not K — fixed
to doubling the King's per-turn powers while holding the crown.

**Ambitious** (A) was then caught as not actually useful — War doesn't
grant the crown, only Revolt does, and anyone can already declare a
Revolt, so "declare War on the King's house without ring-adjacency"
didn't give a real edge toward the throne. Redesigned: whenever this
house declares a Revolt bid, it immediately gains Destiny for that
resolution if it doesn't already hold it — a genuine edge on the actual
path to power, distinct from Kingmaker's "back someone else's bid"
angle (Ambitious is about seizing it yourself).

Refined once more: Ambitious now grants a 1 ADDITIONAL Destiny even if
this house already holds one — an explicit, deliberate exception to
the "only one Destiny per house" rule, per designer instruction to let
it break the rule outright rather than gate on "if not already held."

Clubs confirmed. **Hearts refactored to the same framework** — all 13
entries reordered into the new tiers. The four Dynastic bespoke traits
(Sickly, Barren, Fecund, Long-Lived) already had non-dice effects, so
most sorted into place by their actual net feel without needing a
redesign: Fecund and Long-Lived read strongly positive (high tier),
Sickly reads net-negative (low tier), Barren's compensating benefit
(dice + unlocking Adopt an Heir) pushed it into positive territory
despite its severe cost. New: **Squabbling Heirs** (rank 2) breaks the
"succession is fully deterministic" promise specifically for this
house — the GM may rule a different eligible heir claims the seat when
the Succession Custom would normally dictate otherwise. **Grand
Lineage** (Ace) reworked from flat +3 Diplomacy into "Arrange Marriage
and Forge Alliance always succeed." **Inbred Line retired** — its
concept is subsumed by Squabbling Heirs' rank-2 slot.

Diamonds and Spades still need the same treatment.

## Major design principle surfaced: no GM discretion (2026-08-11)

While reviewing Hearts rank 2 (Squabbling Heirs, which read "the GM may
rule a different eligible heir claims the seat"), the designer flagged
that **the game is trying to eliminate the persistent GM role
entirely** — the King acts as a temporary GM instead. This is a
significant, previously-unstated design principle that affects
anything referencing GM discretion/adjudication going forward.

**Immediate scope**: no mechanic in the house trait table (or any
future content) should resolve via "the GM decides X." Resolution
must be dice, cards, or a fixed rule. Fixed on the spot: **Feuding
Cadets** replaces Squabbling Heirs — same succession-uncertainty
tension (this house's Leader dying doesn't guarantee the Succession
Custom is followed), but resolved by a card flip (Ace = a cadet branch
usurps the seat) instead of GM adjudication.

**Not yet addressed**: `setup-order.md` step 1 still says "choose a
GM," and `turn-order.md`/`tasks.md` reference GM adjudication in
several places (Static check target numbers, Kingdom Scene narration,
Broker Peace's "GM may call for a roll from the resisting party," etc).
This is a genuinely large, separate design question — whether the King
literally replaces the GM's remaining functions, or whether some
lighter-weight facilitation role still exists — flagged for a dedicated
pass, not fixed retroactively in this trait-table session.

## Barren retired, replaced with Madness (2026-08-11)

"No natural births, ever" was judged too damaging even with the Adopt
an Heir compensation (unlocked a whole new action just to offset one
trait's cost — a lot of mechanical weight for one card). Retired
Barren, replaced with **Madness** (rank 10): once per decade, draw 2
cards and keep the best for any ONE action this house attempts —
madness grants flashes of brilliant, reckless genius. Cost: death band
+1 tier, unchanged in spirit from Sickly's cost but now representing
the family's mind and body being burdened by their own instability.

This orphaned three things, all fixed: **Adopt an Heir** removed from
`rulebook/tasks.md` entirely (it existed only to compensate Barren).
The **Fecund/Barren mutual-exclusivity rule** removed from
`tables/house-traits.md` (Sickly/Long-Lived remains the one exclusive
pair). **`birth-death.md`**'s description of Barren's birth-blocking
effect removed, with a note that no trait currently blocks natural
births outright — Extinction can still occur through ordinary bad luck.

## Long-Lived and Grand Lineage further polished (2026-08-11)

**Long-Lived**'s cost changed from -1 Magic to -1 Espionage — no
functional reason given, just a different flavor fit ("so long a life
leaves no secrets"). **Grand Lineage** (Ace) was called "pretty weak" —
"Arrange Marriage/Forge Alliance always succeed" barely mattered
against an already-forgiving Static target number. Strengthened to a
sweeping, always-on effect: this house automatically has the
+2-dice-acting-together bond with EVERY other house at the table, no
action needed at all. Cost bumped from -1 to -2 Espionage to match the
much stronger benefit.

## Rank 2 finally lands: Leprosy; Cursed and Ace revisited again (2026-08-11)

Two more rounds after the above:

- **Cursed** (K) — designer noted its benefit (+1 Legend on Leader's
  death) is light enough that it doesn't need a cost at all. Removed
  the cost entirely, a deliberate exception to "every trait needs a
  cost" (same category of exception as Magic/Piety being exceptions to
  the active/passive stat rule).
- **Grand Lineage** (Ace) — the alliance-bond concept itself was
  rejected ("I think we just change the concept"), not just its
  numbers. Designer suggested "giant's blood." New: **Giant's Blood** —
  every birth in this house rolls trait count ONE TIER HIGHER on the
  Birth Deal table (Ace-3 acts as 4-6, 4-6 acts as 7-9, ... capped at
  Q acting as K) — vigor and size run deep in their ancestry. Cost: -1
  Espionage (too towering to move unseen).
- **Rank 2** — Feuding Cadets (the GM-free fix from the previous
  round) STILL wasn't right; two attempts total before this. Third
  and final: **Leprosy** — once per campaign, generate 1 additional
  relative via Birth Deal (age 0) for free, no action needed
  (countryfolk leave children at the gate, an offering to ward off the
  disease). Cost: Diplomacy rolls only count 6s as successes, not the
  normal 5-6 (reuses the success-threshold-restriction pattern
  established by Clubs' Ill-Trained Levies) — masked and diseased, no
  court treats them as equals.

## Two more tweaks: Leprosy timing, Giant's Blood redefined (2026-08-11)

**Leprosy**'s free-relative benefit changed from once-per-campaign to
**once every 100 years (10 decades)** — recurring but rare, rather than
a single grant for the whole campaign.

**Giant's Blood** (Ace) had its benefit redefined entirely (cost kept
as-is): instead of shifting Birth Deal trait-count rolls up a tier, it
now grants a **death ward** — every character connected to this house
(Leader, spouse, children, descendants) survives the FIRST death that
would claim them, no matter the cause (Fate Check, War Death Check,
Assassination, anything). Spent individually per character; once used,
that character is mortal as normal thereafter.

**Hearts confirmed** — all 13 entries settled after many rounds.

## Diamonds refactored to Ace-high (2026-08-11)

Third suit converted. Counting existing entries surfaced a mismatch:
4 candidates for the 3 weak-tier slots (Stingy, Hospitable, Pious,
Cunning Traders) and only 3 existing unique-mechanic traits (Ostentatious,
Landed Gentry, Golden) for the 4 J/Q/K/A slots. Retired **Hospitable**
and added a new unique mechanic, **Iron Bank** (Ace) — once per decade,
lend 1 Wealth to another house; after 3 decades they owe 2 back
(interest), or this house may seize 1 Land or Manpower if unpaid. First
lending/debt mechanic in the game. **Stingy** (2) gained a bespoke
restriction: can never use Renegotiate to give Wealth away, only
receive it. Enterprising's cost softened -2→-1 Stewardship to fit the
8-10 net-+1 tier (everything else in Diamonds already fit the curve
without changes).

## Diamonds polish pass (2026-08-11)

- **Stingy** renamed **Close-Fisted**, and simplified to match the
  now-established rank-2 pattern (Ill-Trained Levies in Clubs,
  Leprosy in Hearts): one dice bonus, and the cost is ENTIRELY a
  success-threshold restriction, no additional flat dice line stacked
  on top. Diplomacy rolls only count 6s as successes, not 5-6.
- **Landed Gentry** (Q) — "take whatever's there" instead of a fixed 2:
  once every 100 years (10 decades, matching Leprosy's timing pattern),
  claim ALL Land currently in the unclaimed pool, whatever that amount
  is. This also resolves the earlier open question about what happens
  if the pool has less than 2 Land — moot now, since it just takes
  whatever exists.
- **Iron Bank** (A) replaced entirely — judged too on-the-nose a Game
  of Thrones reference, and lending/debt mechanics don't fit this
  game. New: **Endless Ledgers** — once per decade, convert any amount
  of one active stat (Land, Manpower, Wealth) into an equal amount of
  any other, no other house's cooperation needed. Self-contained,
  unlike the rejected lending version.

**Diamonds confirmed.**

## Spades drafted fresh under Ace-high (2026-08-11) — ALL FOUR SUITS DONE

Fourth and final suit, done directly under the established framework
from the start rather than needing a second pass. No house-vs-personal
migration needed — Calamity/Doom traits (magical traditions, espionage
reputations) read institutional naturally, same pattern as Clubs and
Diamonds. Counting surfaced the same "3 bespoke traits for 4 unique-
tier slots" mismatch as Diamonds: only Magical, Doom-Touched, and
Harbinger were truly bespoke. **Shadow-Bound**'s conditional dice bonus
(+2/-2 Espionage depending on whether the target was the King's house)
was upgraded into a genuine unique mechanic, **Crown's Shadow** (Ace):
Espionage actions against the King's house ignore margin restrictions
entirely — even a narrow win or tie counts as decisive. **Paranoid**
(2) reuses the now-standard success-threshold-restriction pattern
(Diplomacy only counts 6s) established across all three other suits'
rank-2 cards (Ill-Trained Levies, Leprosy, Close-Fisted).

All 52 entries across all four suits are now built under the same
Ace-high framework. Awaiting designer confirm on Spades before the
house trait table is considered fully locked.

## Spades polish pass (2026-08-11)

- **Paranoid** (2) — its Diplomacy-only-6s restriction repeated the
  same task Hearts (Leprosy) and Diamonds (Close-Fisted) already used
  for their rank-2 cards. Moved to **Trade** instead (matches
  Paranoid's own original flavor, "trusts no merchant") — the
  success-threshold-restriction pattern is now spread across Manpower
  (Clubs), Diplomacy (Hearts, Diamonds), and Trade (Spades), not
  repeated a third time on the same task.
- **Magical** (Q) — its cost ("draws 2 keeps worst on Spade-suited
  events targeting it") was awkward and narrower than the framework's
  weak-cost expectation for this tier. Simplified to a plain -1
  Diplomacy.
- **Harbinger** (K) — flagged as too similar to Doom-Touched (J), both
  originally just "Doom Clock triggers → +1 Legend." Reworked around a
  different role: foresight and restraint instead of profit — always
  knows the Doom Clock's exact value, and once per decade may force a
  redraw of any card that would advance it. Doom-Touched keeps the
  original passive Legend-gain angle; the two traits no longer overlap.
- **Ace** — Crown's Shadow ("ignore margin restrictions on Espionage
  vs. the King's house") was judged not to make sense. Replaced with
  **Fate's Hand**: once per campaign, shift the Doom Clock itself by up
  to 3 in either direction — ties directly into the suit's core theme
  rather than being an Espionage-margin edge case.

## Rank-2 restriction diversified once more (2026-08-11)

Even after moving Spades' Paranoid off Diplomacy, Hearts (Leprosy) and
Diamonds (Close-Fisted) still both used Diplomacy. Moved **Close-Fisted**
to **Stewardship** instead ("too miserly to invest in their own land's
upkeep and development") — the success-threshold restriction is now
spread across four distinct tasks with no repeats: ~~Manpower~~ War
(Clubs), Diplomacy (Hearts), Stewardship (Diamonds), Trade (Spades).

Immediately caught a mislabel: "Manpower" is a STAT, not a task
category — describing Clubs' entry that way was wrong. **Ill-Trained
Levies**' actual wording said "Manpower-based rolls," which under a
literal reading would ALSO restrict Assassinate (Cunning+Manpower) and
Develop Territory (Land+Manpower), not just War/Border Raid — never
the intent. Rescoped explicitly to the **War** task category, matching
how the other three entries are scoped to a category (Diplomacy,
Stewardship, Trade), not a stat.

Still awaiting final designer confirm on Spades (and the table as a
whole) before considering all 52 entries locked.

## Design principle: nothing rewards advancing the Doom Clock (2026-08-11)

Caught on Doom-Touched, Harbinger, and Fate's Hand, all of which either
rewarded or enabled a house for wanting the Doom Clock to advance.
"No one wins by getting the doom clock up" — the Clock threatens every
house's win condition equally (you can't win if the realm collapses),
so nothing in the game should ever give a rational reason to want it
higher. Locked as a general rule for all future content, not just this
pass: **Doom-Touched** (J) now sees the top card of any events-deck
draw before it happens (pure foresight, no reward tied to the Clock
itself). **Harbinger** (K) can now outright prevent a Doom Clock
advance once per decade (was a vaguer "force a redraw," which didn't
guarantee the outcome). **Fate's Hand** (A) dropped its "advance the
Clock" option entirely — can only push it back, buying the whole realm
time, never hastening the end. This principle should carry forward into
the still-undrafted events table and Calamity module content, where
Doom Clock interactions will come up again.

## Doom Clock is public information (2026-08-11)

Established: the Doom Clock's current value is tracked openly at the
table — a visible counter or token, not a GM secret. It threatens
every house's win condition equally, so there's no reason to hide it,
and it's consistent with the game's broader move away from GM-gatekept
information (see the earlier no-GM-discretion principle). Documented
in `rulebook/turn-order.md`, Phase 4, where the Doom Clock is first
introduced.

This made **Harbinger**'s "always knows the exact current Doom Clock
value" clause redundant — everyone already knows it by default, so the
clause wasn't actually granting anything. Removed; Harbinger now just
grants the once-per-decade prevent-an-advance power.

## Harbinger and Fate's Hand needed a personal edge (2026-08-11)

Once both traits became purely protective (per the Doom-Clock
incentive-alignment fix above), they'd turned into pure collective
goods — preventing/delaying the Clock helps every house at the table
equally, with no advantage for the house that actually holds the
trait and spends the power. Fixed: **Harbinger** now grants the owning
house +1 Legend whenever it prevents an advance. **Fate's Hand** now
grants +1 Piety and +1 Legend whenever it pushes the Clock back. Both
keep the shared realm-wide benefit, but now also reward the specific
house that acted.

## Spades J/Q/K/A: Doom Clock cluster rejected, replaced with rule-breaking magic (2026-08-11)

The designer rejected the whole Doom Clock theme for the top tier
outright: "I don't want doom clock mechanisms here." New direction:
**magic that lets a house cheat the game's normal rules**, with
"functional changes," not small numeric tweaks. Three new bespoke
Magic actions, each unlocked by its own house trait on top of the base
Magic trait requirement:

- **Time-Binder** (J) — unlocks a Magic action letting one relative
  perform TWO Tasks in the same decade, once per decade. Breaks the
  one-task-per-relative limit on purpose.
- **Unweaver** (K) — unlocks a Competitive Magic action (Legend +
  Cunning vs. the target's same) that destroys 1 point of any active
  stat of the caster's choice from the target — no War, Trade War, or
  Espionage needed, bypassing the normal capture economy entirely.
  Full margin table: decisive win destroys the stat (sent to the
  unclaimed pool), narrow win fizzles with no effect, loss backfires
  onto the caster's own chosen stat.
- **Soul Trade** (A) — unlocks a no-roll Magic action (a purely
  voluntary, internal sacrifice) converting any amount of one active
  stat directly into an equal amount of Legend — cheats the established
  rule that Legend only grows through dramatic deeds.

**Magical** (Q) was untouched — it was never part of the rejected Doom
Clock cluster, so it didn't need replacing. Full definitions for all
three new actions added to `rulebook/tasks.md`.

## Spades J/K/A: Magic-gating dropped in favor of direct luck abilities (2026-08-11)

Same day, one more pivot: the "unlocks a new Magic action" versions of
Time-Binder/Unweaver/Soul Trade were flagged as flawed — gating them
behind the Magic house trait meant a house without a Magic-capable
character couldn't use them at all, regardless of which J/K/A card
they rolled. **Magical (Q) stayed untouched** throughout — the fix
targets only J/K/A. New versions, all direct house-level abilities
with no Magic-task dependency:

- **Ill-Starred** (J) — once every 10 years, force an opponent to
  redraw 1 card (any single card draw in the game, reflipped).
- **Fortune's Grace** (K) — once every 20 years, redraw one of this
  house's OWN card draws.
- **Charmed Life** (A) — whenever this house spends Destiny, roll 1
  die; on a 5 or 6, the house keeps Destiny instead of losing it
  (still gains the spent effect that time, but the flag isn't used up).

Removed the now-orphaned Time-Binder's Rite/Unweaving/Soul Trade's Rite
definitions from `rulebook/tasks.md`.

## HOUSE TRAIT TABLE FULLY LOCKED (2026-08-11)

Spades confirmed — all 52 entries across all four suits (Hearts,
Diamonds, Clubs, Spades) are now locked under the Ace-high framework.
This closes out the entire house trait table content-drafting effort
that began earlier this session. See `tables/house-traits.md` for the
final table.

## Birth Deal trait count: dice pool replaces the card-table lookup (2026-08-12)

Replaced the old "flip 1 card, look up trait count on a 6-tier table"
step (`setup-order.md` step 4.1) with a dice pool: roll **10d6**,
count successes on **5-6**, that's the trait count. Reasons:

- Matches the success threshold used everywhere else in the game
  (dice = things that happen to a house, but the resolution math
  should still feel like the rest of the system).
- Finally wires in the original design notes' Legend bonus, which
  never actually made it into the current rulebook text: **automatic
  hits equal to Legend ÷ 5, rounded down**, added on top of the dice
  result. A Legend-12 house adds 2 guaranteed traits to whatever it
  rolls.

Validated the distribution before locking it in (10d6, success on 5-6,
plus auto hits):

| Legend | Auto hits | Mean traits | % below old min (2) | % above old max (7) |
|---|---|---|---|---|
| 0  | 0 | 3.33 | 10.4% | 0.3% |
| 5  | 1 | 4.33 | 1.8%  | 2.0% |
| 10 | 2 | 5.33 | 0%    | 7.6% |
| 15 | 3 | 6.34 | —     | 21.3% |
| 20 | 4 | 7.34 | —     | 44.1% |

Decided **no floor, no cap** — a Legend-0 house can rarely roll 0-1
traits (real variance at the low end), and a high-Legend house
routinely exceeds the old max of 7 (Legend paying off as a visible,
uncapped dynastic engine is the point, not a bug to clamp away).

Confirmed Giant's Blood (Spades Ace, see `tables/house-traits.md`)
doesn't reference the old card-table tier system — it was already
redefined to the death-ward mechanic in an earlier pass, so no
follow-up edit needed there.

## Still open / not yet drafted

- Calamity module content (the actual magic-born / invasion / systemic-
  collapse / blight entries)
- Character trait table (separate from house traits, confirmed distinct,
  not yet drafted)
- Events table content (the actual Hearts/Diamonds/Clubs/Spades entries
  per rank)
- Whether the spouse can start at a different age than the Leader by
  player choice, or must always match

## Rules-consistency gap analysis (2026-08-12)

Full read-through of every rulebook/ and tables/ file, cross-checking
terminology, mechanics, and references against each other. Fixed 3
concrete cross-reference bugs (all committed): house-archetypes.md's
Magical Order cited "Spades 10" for the Magical trait, which is
actually Spades Q (Spades 10 is Omen-Marked, an unrelated Magic-dice
trait); setup-order.md and tasks.md both called it "the Magic house
trait" when its real name is "Magical"; tasks.md's Magic-gating
paragraph still described "Sickly's Ace-2-of-Spades conversion," a
mechanic dropped when Sickly was simplified to flat +2 Piety. Also
clarified in the same pass: Magic-task access is gated per-CHARACTER
(a relative who underwent Magic conversion at Birth Deal), not
automatically house-wide just from having the Magical trait.

Larger structural gaps found, not fixed (need designer input, logged
here for tracking):
- **No dedicated rulebook page for King & Revolt, or for Destiny.**
  Both are referenced constantly and are load-bearing for several
  locked house traits (Kingmaker, Warmonger, Ambitious, Cursed,
  Charmed Life) and for turn-order.md's Kingdom Scene phase, but the
  actual mechanics (Revolt's bid/alliance-bloc/resolution procedure,
  the failure cost, Destiny's earn triggers and spend effect, moniker
  eligibility thresholds) only exist in `design-notes-original.txt`
  and scattered decisions-log summaries — never carried into a clean
  `rulebook/` file the way setup/turn-order/tasks/birth-death were. A
  new player following only the current rulebook/ can't actually
  resolve a Revolt or spend Destiny.
- **Static check target number is still unconfirmed** (`tasks.md`'s
  own open-items list flags "proposing 2 successes, not yet
  confirmed") — this underlies every STATIC action in the game
  (Broker Deal, Arrange Marriage, Forge Alliance, Court Favor, Invoke
  Faith, Ordain a Novice, Fortify, Scry, Bless, Steadfast's bonus,
  etc.), making it the single most load-bearing unresolved number in
  the ruleset.
- **Zealous** (Clubs 6, house-traits.md) reads "+2 dice on the first
  task a relative attempts each decade / -2 dice on every other task
  that same relative attempts that decade" — but turn-order.md's "one
  Task per relative per decade" rule plus the one-decade gap between a
  Task being assigned (Phase 5) and resolved (next decade's Phase 1)
  means it's unclear the downside can trigger in normal play at all
  (only a same-decade Scene-check + Task-resolution overlap would do
  it). As written it may function as a near-pure-upside trait, which
  breaks the "no trait is pure upside" design principle applied
  everywhere else in the table.
- **Magical Order archetype grants a 5th trait for free.**
  house-traits.md states flatly "every house has 4 traits" with no
  exception; house-archetypes.md's Magical Order grants the Magical
  trait's effect "without spending one of the 4 trait picks" — meaning
  a Magical Order house actually carries 5 traits (Magical + 2 chosen
  + 2 rolled), contradicting the "4 traits, always" framing elsewhere.
  Might be intentional (archetype identity should feel bigger than a
  normal trait pick), but the "always 4" line needs an explicit
  exception noted if so.

## Gap #1 closed: King & Revolt and Destiny now have a rulebook page (2026-08-12)

New file `rulebook/king-and-revolt.md`. This was porting already-
RESOLVED content from `design-notes-original.txt` into a clean page,
plus nailing down a handful of pieces the original notes had left
genuinely open or that needed reconciling with systems built since.
Designer decisions this pass:

- **Revolt bloc pool = Manpower + Wealth** (same combo as War) — a
  Revolt is civil war, fought with armies funded by treasuries.
- **Failure cost = 1/4 of Land, Manpower, AND Wealth**, rounded down,
  calculated separately per stat (not a lump sum) — same three stats
  Ruin already checks.
- **Every relative committed to a losing bloc's contribution** takes a
  death check, not just the challenging Leader — each house's Leader
  is automatically committed; a player may nominate additional
  relatives too (no extra dice, just shared risk).
- **Revolt is binary win/lose**, not 3-tier margin-graded — a crown
  can't be half-won. Whichever bloc has the most successes wins;
  ties redraw among only the tied blocs.
- **The King's own house auto-joins the loyalist bloc** with its own
  Manpower + Wealth — never a passive bystander waiting on allies.
- **A dethroned King's house pays the same failure cost as a failed
  challenger** — losing a Revolt is dangerous regardless of which side
  started the fight. The permanent +10 Legend curse-mark is a
  separate, additional consequence, not a substitute for this cost.
- **The Decade 1 forced-draw King also earns the crowning Destiny** —
  one rule for however the crown was obtained, not a special case.
- **Mercy is available to whichever bloc wins**, not King-only as the
  original notes framed it — a victorious challenger sparing the old
  King's loyalists is the same story beat, generalized to one rule.

Destiny itself is now fully specified on the same page (single-use
flag, one per house, 6s-explode-when-spent effect, full earn-trigger
list) — previously only existed in the frozen original notes and
scattered decisions-log mentions, despite being load-bearing for
Ambitious, Cursed, and Charmed Life.

Added cross-references from `turn-order.md`, `tasks.md`, and
`setup-order.md` at their existing Revolt/Destiny mentions, and listed
the new file in `README.md`. Left open on the new page: moniker
eligibility's exact mechanical threshold (conferral was already
resolved as a King's power; eligibility's precise trigger wasn't), and
Calamity compensation's exact Destiny trigger (pending the undrafted
Calamity module content).

## Gap #2 closed: Static check target number resolved (2026-08-12)

`tasks.md` had flagged this as its own open item — "proposing 2
successes as default, not yet confirmed" — the most load-bearing
unresolved number in the ruleset, since every STATIC action in the
game depends on it. Validated by simulation before proposing: a flat
target of 2 is literally impossible at pool 1 and only 11% at pool 2,
the same "punishes small houses" failure mode the Competitive margin
bands already had to fix once. A pool-size-scaled hard cutoff (mirror
the Competitive fix) was tested and rejected too — it produces a
perverse notch where a BIGGER pool can have WORSE odds right at a tier
boundary (needing 1 success at pool 2 succeeds 55.6% of the time;
needing 2 at pool 3 only succeeds 25.9%).

Designer wanted odds that stay roughly constant (~33%) regardless of
house size — no integer target hits exactly 33% at every pool size,
but **target successes = round(pool ÷ 3) + 1** stays in a tight
~21-46% band at every size tested (1-20), with simple mental math at
the table. Locked in.

Added a new "Check types — STATIC vs. COMPETITIVE" section to
`tasks.md` (previously the game had no single place defining either
check type's actual resolution mechanic — both were used constantly
but never formally specified in one spot). This also finally writes
down the Competitive margin-band rule itself (pool <5 → any win
decisive; 5-13 → decisive needs margin 2+; 14+ → decisive needs margin
3+), which had been RESOLVED back when Competitive margins were first
validated by simulation but, like King/Revolt/Destiny, never actually
made it from decisions-log.md into a rulebook file until now. Removed
the now-resolved open item from `tasks.md`'s open-items list.

## Gap #3 closed: Zealous rescoped house-wide (2026-08-12)

Traced exactly when Zealous's downside (Clubs 6) could fire under the
current rules: a Task is *assigned* in Phase 5 but doesn't *resolve*
until Phase 1 of the NEXT decade, so a single relative's assigned Task
and any Scene-check they make almost never land in the same decade —
the only window is the Scene+Task double-booking rule (capped at 2
relatives/house). For the ordinary case (one Task, no Scene overlap),
the old per-relative wording was a clean +2 with no cost that decade,
breaking the "no trait is pure upside" principle applied to every
other entry in the table.

Rescoped to house-wide: **+2 dice on the first Task any relative of
this house attempts each decade, -2 dice on every OTHER task any
relative of the house attempts that same decade** — reliably triggers
whenever a house runs more than one Task assignment in a decade (the
common case for any house with more than one active relative), and
reads better thematically too (the whole house's fervor channels into
one endeavor at the expense of everything else). Added a note that the
"first" task is a player declaration at assignment time, not an
arbitrary order.

## Gap #4 closed: Magical Order's 5th trait documented as an exception (2026-08-12)

house-traits.md stated flatly "every house has 4 traits," but Magical
Order's archetype bonus (`house-archetypes.md`) grants the Magical
trait's effects on top of the normal 2 chosen + 2 rolled, not in place
of one — a Magical Order house actually carries 5. This was already a
deliberate design choice (archetype identity should feel bigger than
an ordinary trait pick), so no mechanical change — added an explicit
"Exception: a Magical Order house has 5" clause to house-traits.md's
opening framing instead of leaving the "always 4" line to silently
contradict it.

**Gap analysis complete — all 4 items closed.** Fixes: 3 stale
Magical-trait cross-references, `rulebook/king-and-revolt.md` (new),
Static check target number + Check Types section in `tasks.md`,
Zealous rescoped house-wide, Magical Order's 5-trait exception
documented.

## No-GM-discretion terminology finally applied game-wide (2026-08-12)

Last remaining piece of the "the game eliminates the persistent GM
role" principle (surfaced back during the house-trait-table pass,
never retroactively applied to setup-order.md/turn-order.md). Every
"the GM does X" phrase in the rulebook was checked — Static-check
target numbers and event outcomes are now both fixed rules (the
round(pool÷3)+1 formula and table lookups), so there was never
anything left needing a judgment call. Resolved:

- **setup-order.md step 1** rewritten from "gather players and choose
  a GM" to just "gather players" — no dedicated role chosen at setup.
- **Kingdom Scene's events-deck reveal** (`turn-order.md` Phase 4) is
  now performed by **the King's player** when a King is seated (the
  King already acts as a temporary, powerless-beyond-the-fixed-rules
  host of that moment) — or, if the throne is vacant, **any player**,
  since the outcome is a fixed table lookup regardless of who flips
  the card.
- **Decade 1's forced-king draw** (both `setup-order.md` step 6 and
  `turn-order.md` Phase 4) changed from "the GM flips" to "any player
  flips" — purely mechanical, no King exists yet to assign it to.
- Softened the remaining descriptive "no GM bottleneck" / "not a GM
  secret" phrasings to describe the actual mechanism (no
  single-adjudicator bottleneck; the Doom Clock is never hidden)
  rather than presupposing a GM role exists to contrast against.

Updated the note in `king-and-revolt.md` that had flagged this as a
known leftover — no longer applicable.
