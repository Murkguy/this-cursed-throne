# The Full Gameflow — Setup Through a Played Campaign

This is a **consolidated, linear walkthrough** of the whole game —
setup once, then the decade loop, followed with one example table
across several decades. It does not redefine any rule; where a step
needs the exact mechanic, it cites the canonical file
(`setup-order.md`, `turn-order.md`, `king-and-revolt.md`, `tasks.md`,
`birth-death.md`, `geography.md`, `house-archetypes.md`,
`tables/house-traits.md`). If this doc and a canonical file ever
disagree, the canonical file wins — fix this doc, not the other way.

Two symbols used throughout:
- 🚧 **CONTENT NEEDED** — the mechanic is fully specified, but the
  actual table/deck content it draws from hasn't been drafted yet.
  The example below improvises a plausible stand-in so the trace can
  continue.
- ⚠️ **MECHANIC NOT YET DESIGNED** — not just missing content; the
  rule itself doesn't exist yet anywhere, including the frozen
  original design notes.

## The example table
Four players, four Houses, all created via the identical setup
procedure:
- **House Ashvale** — our point-of-view house, followed closely below.
- **House Corrow**, **House Talvane**, **House Brenmoor** — the other
  three, referenced by name when they interact with Ashvale.

---

# Setup (once, before Decade 1)

### 1. Gather players
No GM is chosen (see `setup-order.md` step 1) — everything below
resolves by fixed rule. 4 players confirmed (the minimum).

**House order** is negotiated at the table into a ring: Ashvale →
Corrow → Talvane → Brenmoor → (back to Ashvale). Ashvale and Brenmoor
are ring-neighbors, as are Ashvale and Corrow.

### 2. Choose a Calamity module
🚧 **CONTENT NEEDED** — no module write-ups exist yet. For this trace,
assume the table picked **"systemic collapse of the zero-sum
economy"** as a placeholder so setup can continue. Doom Clock starting
length is itself an open item (`setup-order.md`'s own open-items
list) — assume a placeholder starting length of 0, max not yet defined
(see the endgame gap flagged at the bottom of this doc).

### 3a. House Ashvale picks Archetype + Succession Custom
**Noble House** (baseline, no bonus/cost) and **Primogeniture**.

### 3b. House Ashvale's traits (2 chosen + 2 rolled)
- Chosen: **Great Warriors** (Clubs 8 — +2 War / -1 Diplomacy),
  **Frugal** (Diamonds 10 — +2 Trade / -1 War).
- Rolled: flip 2 cards → **9 of Hearts** (Ancestral Seat — +2
  Stewardship / -1 Magic), **Queen of Spades** (Magical — Magic
  conversion trigger includes any face card / -1 Diplomacy).

No Golden, so budget stays at 12.

### 3c. Allocate resources
Land 5 / Manpower 4 / Wealth 3 (12 points, minimum 1 each satisfied).

### 3d-3g. Set starting stats
Honor 0, Legend 0, Piety 0, Cunning 3.

### 4. Create the House Leader — Birth Deal
1. Roll 10d6, count 5-6s. Legend is 0, so 0 automatic hits. Example
   roll: 4 successes → **4 traits**.
2. Flip 4 cards, look up each on the 13-entry character trait table.
   🚧 **CONTENT NEEDED** — that table isn't drafted. Standing in with
   4 of the real banked candidates from `character-traits-bank.md`
   for this example: **Restless, Prideful, Doting, Hot-Blooded.**
3. None of the 4 flips were an Ace of Spades or (Magical is present,
   so) a face card, so no Magic conversion this time.

Result: **Lord Aldric Ashvale**, age 3, House Leader.

### 5. Starting family
- **Spouse:** Lady Wren Ashvale, generated the same way, age 3 (the
  player didn't invoke the "different starting age" option this time,
  though it was available — see `birth-death.md`).
- **Child:** no Fecund trait, so exactly 1 child — **Elenor Ashvale**,
  age 0.

### 6-7. Throne vacant, begin play
Nobody starts as King. The other three houses complete the identical
procedure (not detailed here).

---

# The Decade Loop, played out

## Decade 1

**Phase 1 — Resolution.** No prior decade exists, so no Task outcomes
to check. The Fate Check still runs (see `birth-death.md`): every
tracked relative in all 4 houses gets a death-check flip, every viable
couple gets a birth-check flip. In this example, nobody dies and no
new births land yet (Aldric & Wren's marriage is too fresh — a birth
would need a Queen-King flip).

**Phase 2 — Scene Declaration.** House Ashvale writes a notecard:
approach House Corrow about an alliance.

**Phase 3 — Scene Resolution.** Freeform, then calls for a check when
the alliance is actually proposed: **Forge Alliance** (Diplomacy,
STATIC, Manpower + Cunning). Ashvale's pool = 4 + 3 = 7. Target =
round(7÷3)+1 = round(2.33)+1 = **3 successes needed**. Roll 7 dice:
6, 6, 5, 4, 2, 3, 1 → three 5-6s → **succeeds**. Ashvale and Corrow now
get +2 dice on any task they take together going forward.

**Phase 4 — Kingdom Scene.** Nobody bid for the throne this decade, so
Decade 1's forced draw happens (`setup-order.md` step 6): any player
flips 1 card per house — Ashvale 7, Corrow Q, Talvane K, Brenmoor 3.
**Talvane's highest card (K) forces them onto the throne.** Talvane's
Leader gets +10 Legend (permanent) and 1 Destiny immediately (see
`king-and-revolt.md`).

Events-deck reveal: now performed by Talvane's player (the new King).
Talvane's Legend just hit 10, so they draw 1 extra card and keep the
lowest (this triggers even on the same Kingdom Scene they were
crowned in — the crown's mark applies immediately). Draws: 9 of
Diamonds and Ace of Hearts → keeps the **Ace of Hearts** (lowest).
🚧 **CONTENT NEEDED** — no events table exists, so the actual
flavor/effect of "Ace of Hearts, Dynastic category" is a placeholder.
Mechanically: the Ace triggers the **Doom Clock to advance by 1**
(kept card was an Ace/2/3).

King's per-turn powers: Talvane must grant 1 resource from the
unclaimed pool (grants 1 Wealth to Brenmoor), may redistribute
(declines this decade), may confer a moniker (nobody's done anything
moniker-worthy yet, declines), may move a house's ring position
(declines).

**Phase 5 — Task Assignment.** Ashvale assigns Lord Aldric to
**Develop Territory** (Stewardship, Land + Manpower). This resolves
next decade, not now.

## Decade 2

**Phase 1 — Resolution.** Fate Check first (nobody dies or is born
this time). THEN Aldric's Develop Territory from last decade resolves:
pool = Land 5 + Manpower 4 = 9. Target = round(9÷3)+1 = 3+1 =
**4 successes needed**. Roll 9 dice: 6,5,3,6,2,4,5,1,6 → five 5-6s →
**succeeds**. Ashvale claims 1 Wealth from the unclaimed pool (Wealth
3→4).

**Phases 2-3.** Ashvale declines a scene this decade (not mandatory).

**Phase 4 — Kingdom Scene.** King Talvane draws again (Legend still
10, 1 extra card kept-lowest): draws 8 of Clubs and 6 of Wealth...
🚧 **CONTENT NEEDED** — kept card (say 6 of Diamonds) isn't an Ace/2/3,
so no Doom Clock advance this time. King grants 1 Land to Talvane's
own house (allowed — the mandatory grant isn't restricted from
benefiting the King's own house).

**Phase 5.** Ashvale assigns Lord Aldric to **War** against
ring-adjacent House Corrow (a border dispute) — Manpower + Wealth
combo, resolves immediately per War's own rule (not next decade — see
`tasks.md`, War is the one action that resolves the moment it's
declared, then continues automatically). Ashvale's pool = Manpower 4 +
Wealth 4 = 8. Corrow's pool (example stats: Manpower 3, Wealth 3) = 6.
Both max out under 14, so the Competitive band width is 1 (5-13 range,
see `tasks.md` Check Types). Rolls: Ashvale gets 4 successes, Corrow
gets 1 — margin = 3, **decisive win**. Ashvale captures 1 Land AND 1
Manpower from Corrow. Lord Aldric takes a **War Death Check** (age
0→ wait, Aldric is age 2 by now — 0-2 band, Ace, ~7.7%) — flip: he
survives. The War is now a **standing state** and continues
automatically every decade until either house Brokers Peace.

## Decade 3

**Phase 1.** Fate Check: Aldric and Wren's couple-flip lands
Queen-King this time — **a birth occurs**. New child generated via
Birth Deal (age 0). War with Corrow auto-resolves again (same combo,
new roll) — Ashvale wins again, more Land/Manpower changes hands.

**Phase 2-3.** House Corrow declares **Broker Peace** with Ashvale (no
roll, pure roleplay) — the standing War ends. Corrow gains +1 Honor
for ending it. This also happens to be a "resolving a vendetta" moment
— Corrow's Leader gains **Destiny** (see `king-and-revolt.md`).

**Phase 4.** King Talvane, moved by Corrow's diplomacy, **confers a
moniker**: "Corrow the Peacemaker" — pure fluff, freely improvised,
no roll (see `turn-order.md` Phase 4's simplified moniker rule).

**Phase 5.** Ashvale assigns Lady Wren to **Invoke Faith** (Diplomacy,
Static, Wealth + Land) to start building Piety.

## Decade 4

**Phase 1.** Fate Check: Lord Aldric is now age 6 (60-69 years old,
band Ace-4, ~30.8%) — his flip lands in-band. **Lord Aldric dies.**
Per Primogeniture, his eldest living child (Elenor, now an adult)
inherits as the new House Leader. This is a Destiny-triggering event —
Ashvale's house didn't already hold one, so **the new Leader (Elenor)
gains Destiny**. Because Elenor was directly involved, she may also
swap one existing trait for a freshly flipped one (same character
trait table — still 🚧 content-needed, using another banked candidate
as a stand-in).

## Decade 5

**Phase 2.** Elenor, now Leader, declares a **Revolt** against King
Talvane during Scene Declaration.

**Phase 4 — Revolt resolves.** Alliances drawn live: Ashvale anchors
the challenger bloc alone; Corrow (remembering Ashvale's past
generosity, or just backing the peacemaker's ally) joins Ashvale's
bloc. Talvane's own house auto-joins the loyalist bloc; Brenmoor backs
Talvane too. Challenger pool = Ashvale (Manpower+Wealth) + Corrow
(Manpower+Wealth). Loyalist pool = Talvane + Brenmoor, same combo.
Binary win/lose (see `king-and-revolt.md`) — challenger bloc rolls
more successes. **Elenor Ashvale becomes the new Queen.** +10 Legend
(permanent), +1 Destiny (but Ashvale's house already holds one from
Decade 4 — no change, capped at one, no Ambitious-style exception
here).

Talvane's dethroned house pays the failure cost: 1/4 of Land,
Manpower, and Wealth (each rounded down) to the unclaimed pool, and
every relative committed to their bloc's contribution takes a death
check. Elenor, now Queen, chooses to extend **Mercy** to House
Brenmoor (who only joined the loyalist bloc out of habit, not real
loyalty) — Brenmoor's failure cost is waived. Talvane's own house
still pays it in full.

---

# Content gaps confirmed by this trace

This walkthrough hit every major system in the game at least once
(setup, Static and Competitive checks, the Fate Check, War as a
standing state, Broker Peace, Destiny's trigger list and trait-swap,
Succession, Kingdom Scene, the Legend/Doom-Clock draw, moniker
conferral, and a full Revolt). **No new mechanical gap was found
beyond the three already-known content types** — every 🚧 marker above
traces back to one of:

1. **The 13-entry character trait table** (Birth Deal step 2) — 8
   candidates already banked in `character-traits-bank.md`.
2. **The 52-entry events deck content** (Kingdom Scene reveals) — the
   mechanical shell (suit/rank/Legend-draw/Doom-Clock-trigger) is
   fully specified, only the actual table entries are missing.
3. **Calamity module write-ups** (setup step 2) — including, per
   `setup-order.md`'s own open item, each module's Doom Clock starting
   length.

**One larger gap this trace did surface, not just missing content:**

⚠️ **There is no mechanic anywhere for what happens when the Doom
Clock reaches its maximum, or what "surviving the Calamity" actually
resolves as.** The Doom Clock advancing is fully specified
(`turn-order.md` Phase 4), and the README states the game's entire win
condition depends on it ("the crown only counts if the looming
Calamity has been survived") — but nothing defines the Doom Clock's
max value, what triggers when it's reached, whether survival is a
roll/check/collective action, or how a campaign actually concludes.
This isn't a table-content gap like the other three (more rows to
write) — it's a missing mechanic, likely Calamity-module-specific
(each module probably needs its own "the Calamity strikes" procedure),
and is probably the single biggest remaining design hole in the game.
