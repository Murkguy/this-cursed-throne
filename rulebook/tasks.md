# Tasks — Categories, Stats, and Actions

The six tasks (War, Trade, Diplomacy, Espionage, Stewardship, Magic) are
**categories**, not single moves — each contains a small menu of named
actions. A player assigning a relative in Phase 5 picks a specific
action from the relevant category, not just "the task."

## Active vs. Passive stats
The house stat block splits into two groups:

- **ACTIVE stats — rolled in Task actions**: Land, Manpower, Wealth,
  Cunning.
- **PASSIVE stats — never rolled**: Honor/Infamy, Piety, Legend. These
  are checked by EVENTS (Kingdom Scene, house events) for who's
  highest/lowest and rewarded or punished accordingly, rather than
  being something a player actively spends dice on.

**Task categories are not stats.** War, Trade, Diplomacy, Espionage,
Stewardship, and Magic are groupings of actions, not rollable values —
"opposed by Stewardship" is meaningless, since Stewardship itself rolls
Land. Any opposition always names the actual stat.

**Two explicit exceptions** to "passive stats are never rolled," both
called out where they happen: **Declare Heresy** uses Piety (see
Diplomacy), and **all of Magic** uses Legend — Magic is thematically
unique enough to justify breaking the rule on purpose.

## Cunning — active stat
Your house's reputation for guile and trickery. Starts at **3** for
every house at setup (see `setup-order.md`) — a small flat value,
deliberately not part of the 12-point Land/Manpower/Wealth budget and
deliberately not a hard 0, so Espionage and Border Raid aren't nearly
impossible in the early game. Grows through play: a decisive win on any
Espionage or Border Raid action grants +1 Cunning.

## Dice pools COMBINE both stats when an action lists a combo
A combo action's pool is the two listed stats added together — a
genuinely bigger pool than a single-stat action, at the cost of some
tension with the original "~20 dice stays rollable" pacing rationale on
a house's biggest actions. Accepted as intentional.

## War — Manpower-based
Always targets a ring-adjacent house (see `geography.md`).

- **Border Raid** — a one-off strike. COMPETITIVE, this house's
  **Manpower + Cunning** vs. the target's **Land** (raiding hits
  infrastructure, defended by the same stat Stewardship rolls — not
  "Stewardship" itself, which isn't a stat). Stakes: 1 Wealth —
  decisive win captures it, narrow win destroys it (sent to the
  unclaimed pool), loss gets nothing. No death check.
- **War** — a standing state, not a one-off action. Declaring it
  (Phase 5) resolves an immediate battle: COMPETITIVE, this house's
  **Manpower + Wealth** vs. the target's same combo. Stakes: 1 Land AND
  1 Manpower — decisive win captures both, narrow win sends both to
  the unclaimed pool, loss gets nothing. The declaring relative takes a
  War Death Check (see `birth-death.md`).

  **Once declared, the war continues automatically every decade** until
  either house resolves **Broker Peace** — see the full mechanic
  unchanged from before.

## Trade — Wealth-based
- **Broker Deal** — STATIC. **Wealth + Cunning**. Claim unclaimed
  Wealth from the pool.
- **Trade War** — COMPETITIVE. **Wealth + Cunning** (not Manpower — a
  trade war is fought with capital and guile, not soldiers) vs. the
  target's same combo. Decisive win: capture 1 Wealth directly from the
  target. Narrow win: that Wealth is destroyed instead — sent to the
  unclaimed pool, not captured. Loss: nothing. NOT restricted by
  geography.
- **Renegotiate** — NO ROLL. A cooperative deal between two willing
  houses, not a contest — same principle as Broker Peace. Restricted to
  **ring-adjacent houses only** (trade routes run along shared borders,
  the same logic that makes War ring-locked, but for cooperation
  instead of conflict). Two neighboring houses may mutually agree to
  exchange any amount of Land, Manpower, or Wealth for any other, at
  whatever rate they negotiate — Wealth for Manpower, Land for Wealth,
  whatever the table agrees to. Doesn't touch the unclaimed pool or
  change the total in play, just redistributes between two consenting
  houses.

## Diplomacy — mixed
Diplomacy is the most roleplay-forward category — most of the actual
work happens in the scene itself (see `turn-order.md`, Phase 3's
freeform-by-default rule); the roll only matters for these specific,
concrete outcomes.

- **Arrange Marriage** — STATIC. **Wealth + Land**. Only rolled for a
  **foreign marriage** — marrying a relative into (or in from) another
  PLAYER house. A marriage to an NPC/the wider world needs no roll.
  STATIC checks are pure pass/fail, no margin grading — so the "chance
  at a dowry" is a separate card flip, not a margin outcome. Success:
  the incoming spouse is generated via Birth Deal, joins the house,
  both houses gain +2 dice on ANY task they take together going
  forward, THEN flip 1 card for the dowry — Queen or King transfers 1
  Wealth between the two houses, any other rank means no dowry.
  Failure: the marriage doesn't happen.
- **Forge Alliance** — STATIC. **Manpower + Cunning**. Same lasting
  +2-dice-acting-together bond as Arrange Marriage, without a marriage.
- **Court Favor** — STATIC. **Cunning** alone. Claim unclaimed Honor
  from the pool.
- **Invoke Faith** — STATIC. **Wealth + Land**. Claim unclaimed Piety
  from the pool.
- **Declare Heresy** — COMPETITIVE. **Piety + 2** (flat bonus) vs. the
  target's same. Explicit exception to "passive stats aren't rolled" —
  a religious accusation should scale with how devout your house
  actually is, and the flat +2 keeps it usable even at low Piety.
  Decisive win: the target is branded heretic, -2 dice on all Diplomacy
  actions until they clear their name. Narrow win: suspicion, not a
  lasting scandal — same -2 Diplomacy penalty, but only until the
  target's NEXT Diplomacy attempt, not indefinitely. Loss: it backfires
  — the accusing house takes the full indefinite -2 Diplomacy penalty
  instead, having overreached.
- **Broker Peace** — NO ROLL. Pure roleplay resolution — ends an active
  vendetta or a standing War peacefully. Grants +1 Honor. Can also
  trigger Destiny, per the existing "resolving a vendetta" trigger.

## Espionage — Cunning-based
Always COMPETITIVE, opposed by the target's **Land** (the same stat
Stewardship rolls).

- **Assassinate** — **Cunning + Manpower**. Targets a specific enemy
  relative. Outcome depends on the margin (attacker's successes minus
  defender's):
  - **Win by any margin**: the relative dies, cleanly — the assassin is
    not discovered.
  - **Tie**: the relative dies, but the assassin is discovered and
    captured by the target house.
  - **Lose by 1**: the attempt fails, cleanly — the assassin escapes
    undetected.
  - **Lose by 2 or more**: the attempt fails AND the assassin is
    discovered and captured.

  Being "captured" doesn't kill the assassin automatically — they
  become a prisoner of the target house, a real narrative complication
  (ransom, execution, a hostage to trade) rather than an immediate
  death check. *(This margin table is my best reading of the intended
  breakpoints — flag if the win/tie/loss boundaries should sit
  differently.)*
- **Steal Secrets** — **Cunning** alone, the purest expression of
  spycraft. Targets a house. Decisive win: choose ONE of the target's
  PASSIVE stats (Piety, Honor/Infamy, or Legend) and reduce it by 2 —
  blackmail material, made public. Narrow win: reduce the chosen stat
  by 1 instead. Loss: nothing. (This replaces the old Wealth-theft
  version — Steal Secrets is now specifically about digging up
  something reputationally damaging, not robbery.)
- **Sow Rumors** — **Cunning + Wealth**. Targets a house. Keeps its
  original, narrower niche next to Steal Secrets' flexibility: always
  Honor/Infamy specifically, never Piety or Legend. Decisive win: their
  Honor/Infamy shifts 2 points toward Infamy. Narrow win: shifts 1
  point. Loss: backfires — the attacker's own house gains 1 point
  toward Infamy instead.

~~Turn a Relative~~ — removed, too hard to track reliably at the table.

## Stewardship — Land-based
Always STATIC. Never initiates a Competitive check, but Land is the
stat a house rolls defensively when targeted by Espionage or a War
Border Raid (see above).

- **Develop Territory** — **Land + Manpower**. Claim unclaimed Land,
  Wealth, OR Manpower (player's choice of which).
- **Fortify** — **Land + Wealth**. No resource claim. Instead, this
  house gains +2 dice on the next Espionage or Border Raid defense it
  has to roll (banked until used).

## Magic — Legend-based (unique exception)
Every Magic action uses **Legend + Cunning** — the second explicit
exception to "passive stats aren't rolled." Magic is thematically
singular enough to justify it: mystical renown (Legend) channeled
through cleverness (Cunning). Always STATIC unless noted. Gated behind
the Magic house trait (or a narrower trigger, like Sickly's
Ace-2-of-Spades conversion — see `tables/house-traits.md`). Never
touches the standard resource economy — the payoff is always a unique
effect or a passive-stat change, never an active-stat claim.

- **Scry** — **Legend + Cunning**. Peek at the next card of any deck
  (Birth Deal, the events deck) before it's drawn, for this house or
  any other.
- **Curse** — COMPETITIVE. **Legend + Cunning** vs. the target's same
  combo (resisting magic doesn't require having the Magic trait
  yourself). Decisive win: the target draws 2 cards and keeps the WORST
  on their next TWO relevant draws. Narrow win: same effect, but only
  their next ONE relevant draw. Loss: it backfires — the CASTER draws 2
  and keeps the worst on their own next relevant draw instead.
- **Bless** — **Legend + Cunning**, no opposed roll — can only target
  another house, never yourself. The target draws 2 cards and keeps
  the BEST on their next relevant draw, and gains +1 Piety.

(An earlier draft added three trait-gated Magic actions here —
Time-Binder's Rite, Unweaving, Soul Trade's Rite — tied to Spades
J/K/A. Retired: gating them behind the Magic trait meant a house
without a Magic-capable character couldn't use them at all. Those three
traits are now direct house-level luck abilities instead — see
`tables/house-traits.md`, Ill-Starred, Fortune's Grace, and Charmed
Life — with no Magic-task definitions needed here.)

---

## Open items this pass surfaced (not yet resolved)
- Static check target number (proposing 2 successes as default, not yet
  confirmed)
- Assassinate's exact win/tie/loss breakpoints — written as my best
  reading of the description, not yet explicitly confirmed
- The exact events-deck CONTENT that checks passive stats is future
  table-content work, not yet drafted
- Renegotiate has no cap on how much can change hands per use — flagging
  in case repeated use lets two cooperating players consolidate
  resources onto one house faster than intended. Not capped for now
  since each use still costs a Task Assignment slot on both sides,
  which already rate-limits it somewhat.
