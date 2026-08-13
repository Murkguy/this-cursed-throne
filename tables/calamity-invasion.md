# Calamity Module: External Invasion

**STATUS: DRAFTED**, with one content dependency flagged below (the
Doom Clock trigger). Second of the 4 Calamity modules, built on the
shared endgame shape — see `tables/calamity-shared-endgame.md` for the
mechanics common to every module (Competitive-vs-Calamity, decade×
trial scaling, alliance, the standard decisive/narrow/loss shape, the
survivor score tally). This file only covers what's unique to
Invasion: its theme, Doom Clock trigger, prep action, and its 3
trials.

## Theme
A foreign power is coming — not raiding, not testing a border, but
coming to take the realm entire. It has no stake in who sits the
throne or which House holds which valley; every house is the same
target to it. The only question is whether the realm notices in time
to matter, or spends its last years of warning still counting old
grudges against its own neighbors.

## The Doom Clock
Starts at **0**, maxes at **10**.

**Advance trigger — 🚧 CONTENT-DEPENDENT:** certain **Spades-suit**
event cards (the events deck's existing Calamity/Doom category — see
`turn-order.md` Phase 4) carry an "the invasion draws closer" effect
that advances the Doom Clock by 1 when drawn at Kingdom Scene. Which
specific ranks/cards carry this effect isn't decided yet — that's part
of the still-undrafted 52-entry events table content, not a gap in
this module's design. Unlike Magic-Born (whose trigger is a
structural mechanic tied to Legend), Invasion's escalation is meant to
come from the realm's unfolding story as told by the events deck
itself.

## Preparing for the End: Muster the Border Watch
A new **War** action, **STATIC, Manpower + Land**, attemptable **once
per decade**, any decade from the moment the module is chosen.
Fortifying against an invasion that hasn't arrived yet is a real,
ongoing investment, not a last-minute scramble.

- **Success:** bank **1 Bulwark**. A house may hold at most **3
  Bulwarks** at once — one per trial.
- **Failure:** the muster strains the treasury and the levies without
  producing anything lasting — **lose 1 Manpower and 1 Wealth.**
  Unlike Magic-Born's failure cost, fortifying against invaders
  doesn't itself feed the invasion — it just costs you when it goes
  wrong.

**Spending Bulwarks, during the Siege:** after a trial's roll resolves,
spend any number of banked Bulwarks to upgrade that trial's outcome
one tier per Bulwark spent (Loss→Narrow win, Narrow win→Decisive win).
Same rule as Wards — they soften the blow, they don't guarantee
anything, and a house that never invested in its defenses has none to
spend when the enemy is at the gate.

## The Final Round: The Siege
When the Doom Clock strikes its final mark, the invasion is no longer
a rumor from the border — it is at every house's gate at once. Uses
the standard Final Round mechanics (see `calamity-shared-endgame.md`):
3 sequential Competitive trials against a scaling Calamity pool,
alliance allowed, every death check one age-tier worse, Ruin/Extinction
knocks a house out of contention immediately.

### Trial 1: The Vanguard — Manpower + Wealth
The first wave isn't the invasion itself — it's the probe, testing
which houses are ready and which are still arguing over old borders.
Soldiers and the coin to arm them are what stands between a house and
finding out the hard way.

- **Decisive win:** the vanguard breaks against this house's
  defenses, but repelling it isn't free — lose **1 Wealth**.
- **Narrow win:** lose **1 Manpower and 1 Wealth**, and the player's
  choice of ONE relative takes a death check.
- **Loss:** standard Loss (see `calamity-shared-endgame.md`) — lose 5
  from every stat, every relative takes a death check. The vanguard
  was never the real threat; a house that can't stop it has no chance
  against what's coming behind it.

### Trial 2: The Siege Lines — Land + Wealth
What doesn't break through simply surrounds. Fields go unharvested,
roads go uncrossed, and a house's own walls become the only border
that matters — for as long as the stores inside them hold out.

- **Decisive win:** the lines hold, but not the whole territory — lose
  **1 Land**.
- **Narrow win:** lose **1 Land and 1 Wealth**, and ONE chosen
  relative takes a death check.
- **Loss:** standard Loss — starvation and encirclement don't
  distinguish between what a house has and what it's proud of; both go.

### Trial 3: The Breach — Manpower + Cunning
The walls give somewhere. They always do, eventually. What happens
next isn't decided by how many soldiers a house has left — it's
decided by whether anyone still standing can out-think an enemy that's
already inside.

- **Decisive win:** the breach is sealed, at a cost — lose **1
  Manpower**.
- **Narrow win:** lose **1 Manpower and 1 Cunning**, and ONE chosen
  relative takes a death check.
- **Loss:** standard Loss — a house that loses the fight for its own
  gates loses everything behind them too.

Losing Trial 1 and Trial 2 together already guarantees full Ruin
(standard Loss zeroes Manpower, Wealth, and Land between them)
regardless of Trial 3's result. **There is no version of losing the
whole Siege — or even losing badly partway through it — that leaves a
house quietly surviving.**

---

## Open items this module surfaced (not yet resolved)
- Which specific events-deck cards carry the Doom Clock advance
  effect — depends on the still-undrafted 52-entry events table.
