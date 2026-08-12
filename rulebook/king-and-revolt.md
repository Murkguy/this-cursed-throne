# King & Revolt, and Destiny

This is the canonical page for two systems that were designed early
(see `docs/design-notes-original.txt`) and referenced constantly ever
since — by `turn-order.md`'s Kingdom Scene, and by several LOCKED house
traits (Kingmaker, Warmonger, Ambitious, Cursed, Charmed Life) — but
never had their own write-up. Nothing here contradicts what's already
resolved elsewhere; this consolidates it and fills in the pieces that
were left open.

## Becoming King
There are exactly two ways a house ends up on the throne:

1. **Winning a Revolt** (see below) — the normal path, any decade after
   the first.
2. **Decade 1's forced draw** — if no house bids during Decade 1, any
   player flips one card per house at Decade 1's Kingdom Scene; the
   highest card is forced onto the throne. Already fully specified in
   `setup-order.md` step 6 and `turn-order.md` Phase 4 — not repeated
   here.

**Regardless of which path**, becoming King grants, immediately and
permanently:
- **+10 Legend** — does not revert when the crown is later lost (see
  `tasks.md`/`turn-order.md`'s Legend/events-table mechanic — this is
  the curse's mark, not a King-only bonus that switches off).
- **1 Destiny** (see below) — even the Decade 1 forced case counts.
  Being handed the crown by an unlucky draw isn't a personal
  achievement, but the CROWNING itself is still the kind of
  irreversible moment of change Destiny exists to reward — the house
  that wears it is changed either way.

There is no election. "A King is elected from among the houses" (an
earlier framing in the original notes) is superseded entirely by the
reactive bid/Revolt system below, plus the Decade 1 fallback.

## Declaring a Revolt
Any house may declare a bid to contest the crown during **Scene
Declaration** (Phase 2) — the same notecard/simultaneous mechanism as
a regular scene, and it uses up that house's one Scene Declaration
slot for the decade. **No ring-adjacency requirement** — unlike War,
a Revolt can target the crown from anywhere in the house order.

Multiple houses may each declare their own bid the same decade — this
is how a Revolt ends up with more than one challenger bloc (see
below). A Revolt always resolves at **that same decade's Kingdom
Scene** (Phase 4), not a later one — already established in
`turn-order.md`.

## Alliances
Alliances are drawn **live**, at the Kingdom Scene where the Revolt
resolves — nothing is pre-committed at declaration time.

- **The King's own house automatically anchors the loyalist bloc**,
  contributing its own Manpower + Wealth alongside whoever else backs
  them. The King is never a passive bystander waiting on allies.
- **Each house that declared a bid anchors its own challenger bloc.**
  If two houses declare independently and don't fold into a shared
  bloc, they remain separate blocs, each rolling for themselves.
- **Any house that didn't declare a bid may join any bloc** — loyalist
  or a specific challenger's — at this point, contributing its own
  Manpower + Wealth to that bloc's pool. A house may also simply
  abstain, contributing nothing and facing no risk.
- The King's past behavior (grants given, redistributions taken)
  directly determines how many loyalists actually show up — this is
  intentional; generosity and coercion as King are banking (or
  spending) future support for exactly this moment.

**Each house in a bloc is represented by its Leader**, who is
automatically treated as personally committed to the fight. A player
may also nominate additional relatives from their house to fight
alongside the Leader — this adds no extra dice (the bloc's pool is
fixed to Manpower + Wealth regardless of headcount) but does mean
those relatives share the Leader's risk if the bloc loses (see Failure
Cost). Purely a narrative/stakes choice, not a mechanical one.

## The Roll
**COMPETITIVE, binary win/lose** — no decisive/narrow distinction,
since a crown can't be half-won. Each bloc's combined dice pool is the
**sum of every member house's Manpower + Wealth**, plus any flat trait
bonuses that apply (e.g. Kingmaker's +3 to whichever side it joins).
All blocs roll simultaneously; **whichever bloc rolls the most
successes wins the crown**. If the top two (or more) blocs tie, redraw
among only the tied blocs — same tie-break convention as Decade 1's
forced draw.

## Outcome: the crown
The winning bloc takes the throne.

- **Single-house bloc:** that house's Leader becomes King immediately.
- **Coalition bloc:** succession is deliberately **not mechanically
  resolved** — the winning houses must agree among themselves who
  actually takes the crown. If they can't agree, or the deal falls
  apart, that can itself spiral into a following Revolt. This is left
  to table negotiation on purpose — a coalition fracturing after
  victory is meant to be a story beat, not a rule.

## Outcome: failure cost
**Every losing bloc pays the same cost — including a dethroned King's
house**, not just failed challengers. Losing a Revolt is what's
dangerous, not which side you started on:

- **A quarter of Land, Manpower, and Wealth**, rounded down,
  calculated separately per stat, is sent to the unclaimed pool. (E.g.
  a house at 8/4/4 loses 2/1/1.) This can push a stat to 0, and can
  contribute toward a Ruin collapse if all three hit 0 at once — see
  `birth-death.md`.
- **Every relative who was committed to that bloc's contribution**
  (each house's Leader, plus any relatives a player chose to nominate
  alongside them — see Alliances above) takes **one death check**, same
  age/trait-adjusted band as the ambient Fate Check — mirrors the War
  Death Check pattern in `birth-death.md`.

## Mercy
**The winning bloc's new (or reigning) Leader may spare any specific
losing house from the failure cost** — both the stat loss and the
death checks — free, no cost to the winner. This is available to
whichever side wins, not just a King defending the crown; a victorious
challenger sparing the old King's loyalists is the same story beat.
With 3+ blocs in play, mercy is granted per-house — the winner can
spare some, all, or none of the losing houses individually. Like the
game's other free political choices, the cost lives entirely at the
table: a ruler who spares the deserving or the undeserving is a
visible choice other players remember.

---

# Destiny

**A single-use FLAG, not a resource pool.** A house either holds
Destiny or it doesn't — only ONE per house at a time (Ambitious, Clubs
A, is the sole documented exception, granting a second even if one is
already held).

**Effect when spent:** every 6 rolled in that check's dice pool
explodes — reroll it and keep adding, chaining on any new 6s too —
spent at the moment the player chooses, on any dice-pool check their
house is making. Bigger pools mean more explosive potential.

**Charmed Life** (Spades A) modifies spending specifically: roll 1
die when Destiny is spent — on a 5-6, the house keeps the flag instead
of losing it, even though the explode effect still fires that time.

**Earned by** (always a moment of change, never a passive state):
- **The House Leader dies** — this always counts as a Destiny-earning
  moment for the new heir, whether or not the dying Leader already
  held one (if they did, the heir simply keeps it — still capped at
  one; if they didn't, the succession itself is what grants it).
- **A house overtakes the current #1** in some tracked ranking — the
  moment of dethroning specifically, not for sitting at #1 afterward.
- **A house becomes the new lowest-ranked** — the moment of falling to
  the bottom, not for sitting there.
- **Calamity compensation** — exact trigger depends on the
  not-yet-drafted Calamity module content.
- **Resolving a vendetta** against another house (a duel, a marriage
  that settles a feud, etc.) — already referenced from Broker Peace in
  `tasks.md`.
- **Winning the crown** — by Revolt or the Decade 1 forced draw, see
  above.

If a house already holds Destiny when a new trigger fires, nothing
changes (still just one) — except Ambitious's explicit exception.

**Related, but a separate effect:** whenever a character is directly
involved in any of the events above, that character may also swap one
existing trait for a newly flipped one (a single card flip, same
13-entry lookup as Birth Deal) — this trait-swap is automatic and
happens regardless of whether the event actually granted a new
Destiny flag. Already defined in `turn-order.md`, Phase 1 step 3 —
not a second Destiny-only mechanic, just reusing the same trigger
list.

---

## Open items this page surfaced (not yet resolved)
- Moniker eligibility's exact mechanical threshold — decisions-log.md
  gestures at "a Legend/events-table threshold," but the precise
  number was never locked. Conferral itself (a King's per-turn power)
  is already defined in `turn-order.md`.
- Calamity compensation's exact Destiny trigger, pending the
  undrafted Calamity module content.
