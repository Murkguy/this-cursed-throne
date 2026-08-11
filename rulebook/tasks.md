# Tasks — Categories, Stats, and Actions

The six tasks (War, Trade, Diplomacy, Espionage, Stewardship, Magic) are
**categories**, not single moves — each contains a small menu of named
actions. A player assigning a relative in Phase 5 picks a specific
action from the relevant category, not just "the task."

## Active vs. Passive stats
The house stat block splits into two groups:

- **ACTIVE stats — rolled in Task actions**: Land, Manpower, Wealth,
  **Cunning** (new).
- **PASSIVE stats — never rolled**: Honor/Infamy, Piety, Legend. These
  are checked by EVENTS (Kingdom Scene, house events) for who's
  highest/lowest and rewarded or punished accordingly, rather than
  being something a player actively spends dice on. This generalizes a
  pattern that was already true of Legend (the Doom Clock trigger,
  moniker eligibility, the King's +10, Birth Deal's trait bonus are all
  "passive stat affects how systems treat you") and Honor (Destiny's
  "overtakes #1" / "becomes new lowest" triggers) — just applied
  consistently to all three now, and locked as a rule: these three
  NEVER determine a dice pool.

Action OUTCOMES can still change a passive stat (Bless still grants +1
Piety, Sow Rumors still damages Honor/Infamy) — only the pool itself is
restricted to the four active stats.

## Cunning — new active stat
Your house's reputation for guile and trickery. Starts at **3** for
every house at setup (see `setup-order.md`) — a small flat value,
deliberately not part of the 12-point Land/Manpower/Wealth budget and
deliberately not a hard 0 like Legend/Honor/Piety, so Espionage and
Border Raid aren't nearly impossible in the early game. Grows through
play: a decisive win on any Espionage or Border Raid action grants +1
Cunning — the same dynastic-engine feedback loop Legend already has
(successful schemes breed a reputation for cleverness, which enables
more successful schemes).

## Dice pools use the LOWER of two stats when an action lists a combo
Prevents combo actions from just being strictly better than single-stat
ones (summing two ~20-cap stats would roll pools nearly double a
single-stat action). A combo action is bottlenecked by whichever of its
two stats is currently weaker — a wealthy house with a thin army still
can't wage effective War.

## War — Manpower-based
Always targets a ring-adjacent house (see `geography.md`).

- **Border Raid** — a one-off strike. COMPETITIVE, this house's
  **Manpower + Cunning** (lower of the two) vs. the target's
  Stewardship (raiding hits infrastructure, not armies — see
  Stewardship below). Stakes: 1 Wealth — decisive win captures it,
  narrow win destroys it (sent to the unclaimed pool), loss gets
  nothing. No death check — a raid isn't a real battle.
- **War** — a standing state, not a one-off action. Declaring it
  (Phase 5) resolves an immediate battle: COMPETITIVE, this house's
  **Manpower + Wealth** (lower of the two — an army needs pay, not
  just bodies) vs. the target's same combo. Stakes: 1 Land AND 1
  Manpower — decisive win captures both, narrow win sends both to the
  unclaimed pool, loss gets nothing. The declaring relative takes a War
  Death Check (see `birth-death.md`).

  **Once declared, the war continues automatically every decade** —
  the same battle re-resolves at the top of every Resolution phase for
  both houses, no Task Assignment needed to keep it going, including a
  War Death Check each time. If the declaring relative dies, the war
  still continues (stats vs. stats), but no further death checks occur
  for that house until a new relative is assigned to lead the war
  effort. Ends only when either house resolves **Broker Peace**.

## Trade — Wealth-based
- **Broker Deal** — STATIC. **Wealth + Cunning** (lower). Claim
  unclaimed Wealth from the pool — a shrewd trader needs both capital
  and guile.
- **Trade War** — COMPETITIVE. **Wealth + Manpower** (lower — economic
  warfare needs some muscle to enforce it) vs. the target's same combo.
  Same margin rules as Border Raid. NOT restricted by geography — coin
  and economic pressure reach further than armies.

## Diplomacy — mixed
Diplomacy is the most roleplay-forward category — most of the actual
work happens in the scene itself (see `turn-order.md`, Phase 3's
freeform-by-default rule); the roll only matters for these specific,
concrete outcomes.

- **Arrange Marriage** — STATIC. **Wealth + Land** (lower — a dowry and
  territory to offer). Success forges a lasting bond between two
  houses: both gain +2 dice on ANY task the two houses take together
  going forward.
- **Forge Alliance** — STATIC. **Manpower + Cunning** (lower — a
  mutual-defense pact needs real military weight and cleverly drawn
  terms). Same lasting +2-dice-acting-together bond as Arrange
  Marriage, without a marriage.
- **Court Favor** — STATIC. **Cunning** alone — plain charm. Claim
  unclaimed Honor from the pool. (The action's pool is Cunning; its
  reward still touches the passive Honor stat — see above.)
- **Invoke Faith** — STATIC. **Wealth + Land** (lower — funding
  temples and religious infrastructure). Claim unclaimed Piety from the
  pool.
- **Declare Heresy** — COMPETITIVE. **Cunning** vs. the target's
  Cunning (building a credible accusation vs. defending against one).
  Decisive win: the target is branded heretic, -2 dice on all Diplomacy
  actions until they clear their name. Loss: it backfires — the
  accusing house takes that same -2 Diplomacy penalty instead, having
  overreached.
- **Broker Peace** — NO ROLL. Pure roleplay resolution — ends an active
  vendetta or a standing War peacefully. Grants +1 Honor. Can also
  trigger Destiny, per the existing "resolving a vendetta" trigger.

## Espionage — Cunning-based
Always COMPETITIVE, opposed by the target's Stewardship.

- **Assassinate** — **Cunning + Manpower** (lower). Targets a specific
  enemy relative. Decisive win: the relative dies. Narrow win: the
  attempt fails and is never traced back. Loss: the attacking relative
  is caught — they take a death check of their own (same as the War
  Death Check).
- **Turn a Relative** — **Cunning + Wealth** (lower — a clever approach
  backed by a bribe). Targets a specific enemy relative. Decisive win:
  that relative becomes a secret asset — their house's next Task
  Assignment is revealed to you before it resolves, or (player's
  choice) their next task automatically fails. Narrow win: a seed of
  doubt is planted, no mechanical effect yet. Loss: your attempt is
  discovered — your house gains +1 Infamy.
- **Steal Secrets** — **Cunning** alone, the purest expression of
  spycraft. Targets a house. Decisive win: claim 1 Wealth directly from
  them AND see their next decade's Task Assignments in advance. Narrow
  win: a small amount of Wealth goes to the unclaimed pool instead.
  Loss: nothing.
- **Sow Rumors** — **Cunning + Wealth** (lower — funded agents spread a
  story convincingly). Targets a house. Decisive win: their
  Honor/Infamy shifts 2 points toward Infamy. Narrow win: shifts 1
  point. Loss: backfires — the attacker's own house gains 1 point
  toward Infamy instead.

## Stewardship — Land-based
Always STATIC. Never initiates a Competitive check, but is the stat a
house defends with when targeted by Espionage or a War Border Raid.

- **Develop Territory** — **Land + Manpower** (lower — land needs
  laborers). Claim unclaimed Land, Wealth, OR Manpower (player's
  choice of which) — Stewardship is the generalist "administer the
  realm" option, Trade the specialist one.
- **Fortify** — **Land + Wealth** (lower — fortifications need
  funding). No resource claim. Instead, this house gains +2 dice on
  the next Espionage or Border Raid defense it has to roll (banked
  until used).

## Magic — Cunning-based
Always STATIC unless noted. Gated behind the Magic house trait (or a
narrower trigger, like Sickly's Ace-2-of-Spades conversion — see
`tables/house-traits.md`). Never touches the standard resource economy
— the payoff is always a unique effect or a passive-stat change, never
an active-stat claim.

- **Scry** — **Cunning** alone. Peek at the next card of any deck
  (Birth Deal, the events deck) before it's drawn, for this house or
  any other.
- **Curse** — COMPETITIVE. **Cunning** vs. the target's Cunning (only
  the clever see through dark workings, or resist them). Success: the
  target draws 2 cards and keeps the WORST on their next relevant draw
  (same "disadvantage" mechanic already used for the King's harsh draw
  and the Cursed house trait).
- **Bless** — **Cunning** alone, no opposed roll — can only target
  another house, never yourself. The target draws 2 cards and keeps
  the BEST on their next relevant draw (the mirror of Curse), and
  gains +1 Piety.

---

## Open items this pass surfaced (not yet resolved)
- Static check target number (proposing 2 successes as default, not yet
  confirmed)
- The exact events-deck CONTENT that checks passive stats (which cards
  reward/punish the most/least Pious, Honorable, or Legendary house) is
  future table-content work, not yet drafted — this pass only locks the
  PRINCIPLE that such cards exist and that passive stats are never
  rolled directly
