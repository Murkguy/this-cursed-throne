# Tasks — Categories, Stats, and Actions

The six tasks (War, Trade, Diplomacy, Espionage, Stewardship, Magic) are
**categories**, not single moves — each contains a small menu of named
actions. A player assigning a relative in Phase 5 picks a specific
action from the relevant category, not just "the task." Every action's
dice pool = its category's stat + the acting relative's trait bonus (if
a trait fits) + scene modifiers.

## War — Manpower
Always targets a ring-adjacent house (see `geography.md`).

- **Border Raid** — a one-off strike. COMPETITIVE, this house's
  Manpower vs. the target's **Stewardship** (raiding hits
  infrastructure, not armies). Stakes: 1 Wealth — decisive win captures
  it, narrow win destroys it (sent to the unclaimed pool), loss gets
  nothing. No death check — a raid isn't a real battle.
- **War** — a standing state, not a one-off action. Declaring it (Phase
  5, Task Assignment) resolves an immediate battle: COMPETITIVE, this
  house's Manpower vs. the target's Manpower. Stakes: 1 Land AND 1
  Manpower — decisive win captures both, narrow win sends both to the
  unclaimed pool, loss gets nothing. The declaring relative takes a War
  Death Check (see `birth-death.md`).

  **Once declared, the war continues automatically every decade** —
  the same battle (Manpower vs. Manpower, same stakes, same War Death
  Check for the relative who declared it) re-resolves at the top of
  every Resolution phase for BOTH houses, with no Task Assignment
  needed to keep it going. If the declaring relative dies, the war
  still continues (stats vs. stats), but no further death checks occur
  for that house until a new relative is assigned to lead the war
  effort (a fresh Task Assignment, optional). The war only ends when
  either house resolves **Broker Peace** (see Diplomacy, below).

## Trade — Wealth
- **Broker Deal** — STATIC. Claim unclaimed Wealth from the pool.
- **Trade War** — COMPETITIVE vs. the target's Wealth, same margin
  rules as Border Raid. NOT restricted by geography — coin and
  economic pressure reach further than armies, so a Trade War can
  target any house, not just a ring-adjacent one.

## Diplomacy — |Honor/Infamy|
Diplomacy is the most roleplay-forward category — most of the actual
work happens in the scene itself (see `turn-order.md`, Phase 3's
freeform-by-default rule); the roll only matters for these specific,
concrete outcomes.

- **Arrange Marriage** — STATIC. Success forges a lasting bond between
  two houses: both gain +2 dice on ANY task the two houses take
  together going forward (not Diplomacy-only).
- **Forge Alliance** — STATIC. Same lasting +2-dice-acting-together
  bond as Arrange Marriage, without a marriage — a political or
  military pact instead.
- **Court Favor** — STATIC. Claim unclaimed Honor from the pool.
- **Invoke Faith** — STATIC. Claim unclaimed Piety from the pool (see
  Piety, below).
- **Broker Peace** — NO ROLL. Pure roleplay resolution — ends an active
  vendetta or a standing War (see above) peacefully. Grants +1 Honor.
  Can also trigger Destiny, per the existing "resolving a vendetta"
  trigger.

## Espionage — Wealth
Always COMPETITIVE, opposed by the target's Stewardship. Every action
below uses the same margin structure (decisive/narrow/loss) but with
outcomes specific to what's actually being risked — not a generic
resource capture.

- **Assassinate** — targets a specific enemy relative. Decisive win:
  the relative dies. Narrow win: the attempt fails and is never traced
  back. Loss: the attacking relative is caught — they take a death
  check of their own (same as the War Death Check), being caught in a
  failed assassination is dangerous.
- **Turn a Relative** — targets a specific enemy relative. Decisive
  win: that relative becomes a secret asset — their house's next Task
  Assignment is revealed to you before it resolves, or (player's
  choice) their next task automatically fails. Narrow win: a seed of
  doubt is planted, no mechanical effect yet, but the GM notes it for
  future scenes. Loss: your attempt is discovered — your house gains
  +1 Infamy.
- **Steal Secrets** — targets a house. Decisive win: claim 1 Wealth
  directly from them (not from the unclaimed pool) AND see their next
  decade's Task Assignments in advance. Narrow win: a small amount of
  Wealth goes to the unclaimed pool instead. Loss: nothing.
- **Sow Rumors** — targets a house. Decisive win: their Honor/Infamy
  shifts 2 points toward Infamy. Narrow win: shifts 1 point. Loss: it
  backfires — the attacker's own house gains 1 point toward Infamy
  instead.

## Stewardship — Land
Always STATIC. Never initiates a Competitive check, but is the stat a
house defends with when targeted by Espionage or a War Border Raid (see
above).

- **Develop Territory** — claim unclaimed Land, Wealth, OR Manpower
  from the pool (player's choice of which) — still rolled against the
  Stewardship (Land) pool regardless of which resource is claimed. This
  overlaps with Trade's Broker Deal on purpose: Stewardship is the
  generalist "administer the realm" option, Trade is the specialist
  option (and the only path to a Trade War).
- **Fortify** — no resource claim. Instead, this house gains +2 dice on
  the next Espionage or Border Raid defense it has to roll (banked
  until used) — a proactive investment in security rather than growth.

## Magic — Legend
Always STATIC. Gated behind the Magic house trait (or a narrower
trigger, like Sickly's Ace-2-of-Spades conversion — see
`tables/house-traits.md`). Never touches the standard resource economy
— the payoff is always a unique effect, not a stat claim.

- **Scry** — peek at the next card of any deck (Birth Deal, the events
  deck) before it's drawn, for this house or any other.
- **Curse** — COMPETITIVE, this house's Legend vs. the target's
  **Piety** (see below). Success: the target draws 2 cards and keeps
  the WORST on their next relevant draw (same "disadvantage" mechanic
  already used for the King's harsh draw and the Cursed house trait).
- **Bless** — can only target another house, never yourself. No
  opposed roll. The target draws 2 cards and keeps the BEST on their
  next relevant draw (the mirror of Curse), and gains +1 Piety.

## Piety — the sixth house stat
Every house also tracks **Piety**, alongside Land, Manpower, Wealth,
Honor/Infamy, and Legend. Same model as Honor/Infamy: zero-sum among
current holders at any moment, but random events feed a growing
unclaimed pool over time (see the original unclaimed-pool rules). Same
soft cap (~20) as every other stat. Starts at **0** for every house at
setup (see `setup-order.md`) — built through play via Invoke Faith
(Diplomacy, above), never allocated at setup.

Piety is the defense stat against Curse — a devout house resists
curses better than a godless one, regardless of how honored or
infamous it is. This is deliberately a SEPARATE axis from Honor/Infamy:
a beloved-but-godless house and a devout-but-reviled house are now
mechanically distinct from each other.

---

## Open items this pass surfaced (not yet resolved)
- Static check target number (proposing 2 successes as default, not yet
  confirmed)
- Whether other categories (Trade, Diplomacy, Espionage, Magic) should
  also get a War-style "standing state" option, or whether that's
  specific to War
- Exact wording/limits on "Turn a Relative" and "Curse" — both grant
  fairly open-ended GM-adjudicated effects that may need tighter bounds
  once playtested
- Whether the Pious house trait (Diamonds 3, `tables/house-traits.md`)
  should be updated now that Piety is a real tracked stat, rather than
  just a flavor-matched name with no mechanical tie to it
