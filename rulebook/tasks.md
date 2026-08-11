# Tasks — Categories, Stats, and Actions

The six tasks (War, Trade, Diplomacy, Espionage, Stewardship, Magic) are
**categories**, not single moves — each contains a small menu of named
actions. A player assigning a relative in Phase 5 picks a specific
action from the relevant category, not just "the task." Every action's
dice pool = its category's stat + the acting relative's trait bonus (if
a trait fits) + scene modifiers.

## War — Manpower
Always targets a ring-adjacent house (see `geography.md`).

- **Border Raid** — the standard War action. COMPETITIVE vs. the
  target's Manpower, resolved with the existing margin rules (decisive
  win captures, narrow win sends to the unclaimed pool, loss gets
  nothing). One additional death check for the relative who fought it
  either way (see `birth-death.md`).
- **Full Invasion** — commits fully. +2 dice on the pool. Stakes
  double (decisive win captures 2x, decisive loss costs the attacker
  2x). The War Death Check for this action shifts +1 tier harsher —
  heavier forces committed means heavier casualties, win or lose.

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
  two houses: both gain +2 dice on Diplomacy actions with each other
  going forward.
- **Forge Alliance** — STATIC. Same lasting +2-dice-with-each-other
  bond as Arrange Marriage, without a marriage — a political or
  military pact instead.
- **Court Favor** — STATIC. Claim unclaimed Honor from the pool.
- **Broker Peace** — STATIC (or GM may call for a roll from the other
  party if they're resisting). Resolves an active vendetta peacefully
  — can trigger Destiny, per the existing "resolving a vendetta"
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
house defends with when targeted by Espionage (see above).

- **Develop Territory** — claim unclaimed Land from the pool.
- **Fortify** — no resource claim. Instead, this house gains +2 dice on
  the next Espionage defense it has to roll (banked until used) — a
  proactive investment in security rather than growth.

## Magic — Legend
Always STATIC. Gated behind the Magic house trait (or a narrower
trigger, like Sickly's Ace-2-of-Spades conversion — see
`tables/house-traits.md`). Never touches the standard resource economy
— the payoff is always a unique effect, not a stat claim.

- **Scry** — gain hidden information about a target house: their next
  decade's Task Assignments, or a trait they haven't revealed yet.
- **Curse** — targets a rival house. Success inflicts a lasting
  penalty: -2 dice on one task type of the caster's choice, for that
  house's next decade.
- **Commune** — gain insight into the Doom Clock: learn its exact
  current value (if normally kept hidden by the GM), or grant this
  house's next events-deck draw a reroll if the GM allows it.

---

## Open items this pass surfaced (not yet resolved)
- Static check target number (proposing 2 successes as default, not yet
  confirmed)
- Whether other categories (Diplomacy, Espionage, Stewardship, Magic)
  should also get a "small vs. large commitment" scale option the way
  War now has Border Raid vs. Full Invasion, or whether that's
  War-specific
- Exact wording/limits on "Turn a Relative" and "Curse" — both grant
  fairly open-ended GM-adjudicated effects ("their next task
  automatically fails," "-2 dice on one task type") that may need
  tighter bounds once playtested
