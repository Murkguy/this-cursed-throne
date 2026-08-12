# Calamity Module: Magic-Born

**STATUS: DRAFTED.** First of the 4 Calamity modules — also establishes
the shared endgame SHAPE (final gauntlet → survivor score tally) that
the other 3 modules are intended to reuse, each with their own bespoke
trials. See `setup-order.md` step 2 for module selection and
`gameflow.md` for how this fits the overall game flow.

## Theme
Magic itself is the threat. Every act of Legend — every dramatic deed,
every spell cast, every curse laid — leaves a mark on the world. The
more legendary the realm's houses become, the closer that mark pulls
reality toward rupture.

## The Doom Clock
Starts at **0**, maxes at **10**.

**Advance trigger — this module's own, not shared with other
modules:** the existing King/Legend curse draw (`turn-order.md` Phase
4 — for every 10 Legend a house has, it draws an extra card at
Kingdom Scene and keeps the lowest) is Magic-Born's mechanism. If the
kept card is an **Ace, 2, or 3**, the Doom Clock advances by 1. Raw
magical renown is what destabilizes the realm under this module — the
more houses lean into Legend, the faster the Clock fills. (Other
modules, once drafted, will define their own distinct advance
triggers — this one doesn't generalize.)

## The Final Round: The Sundering
Ten decades of mounting Legend have worn the world thin. When the
Doom Clock strikes its final mark, the wound tears open all at once —
this is the **last decade of the campaign**, and it does not resolve
gently. Before Task Assignment that decade, every house still standing
faces **3 sequential trials** — not one roll, a gauntlet. Each trial
is a STATIC check (target = round(pool÷3)+1, same formula as any other
Static check) rolled individually by every house still in the
campaign. Stats update immediately after each trial's consequences
apply, so a house wounded by an early trial enters the next one
already bleeding — the damage compounds on purpose, and it is meant to
be felt.

**Every death check rolled during the Sundering is treated as one
age-tier worse than normal** (stacking with Sickly/Long-Lived) — the
Calamity does not spare the young or favor the strong.

A house that hits **Ruin or Extinction** (see `birth-death.md`) at any
point during this round collapses immediately and is **out of
contention** for the final score, same as any other collapse — no
special exception for the Sundering. Failing all 3 trials is written
below to guarantee this outcome on stats alone, on top of whatever the
death checks have already done to the family line — a house that
fails the whole gauntlet does not limp away from it.

### Trial 1: The Wild Surge — Legend + Cunning
The sky opens first. Color bleeds out of the world in slow pulses, and
for one unbearable moment every oath ever sworn, every curse ever
laid, every legend ever earned comes due at once — a tide of raw,
undirected magic sweeping over everything a house has ever done to be
remembered. **Fail:** this house loses **2 Legend and 1 Cunning** —
the surge doesn't just wound reputation, it unravels the cleverness a
house relies on to navigate what comes next — and **EVERY relative
tracked by this house** (Leader, spouse, every descendant and their
own spouses/children still in the family tree) takes an immediate
death check. Not one chosen sacrifice — the whole bloodline stands in
the surge together. **Succeed:** the house holds its shape against the
tide.

### Trial 2: The Restless Dead — Manpower + Wealth
What the surge does not claim outright, it wakes. Barrows crack open.
Old battlefields give up what they buried. Every soldier a house ever
spent, every soul lost to the long slow bleed of War, rises now and
walks toward the living. **Fail:** this house's standing army breaks
entirely — **lose ALL Manpower and ALL Wealth** (the coin spent
buying loyalty and steel is worthless against the dead; there is
nothing left to hire, nothing left to arm) — and **EVERY relative**
takes another death check, on top of whatever Trial 1 already cost
this family. **Succeed:** the line holds.

### Trial 3: The Land Unmade — Land + Wealth
Last, and worst: the ground itself stops agreeing to exist. Fields,
walls, ancestral halls — the very earth a house's claim was built on
buckles, folds, and in places simply isn't there anymore when the
light comes back. **Fail:** **lose ALL remaining Land and ALL
remaining Wealth** — there is no "half" left to lose by this point, a
house that reaches this trial already wounded loses whatever ground
it still stood on — and **EVERY relative** takes a third death check.
**Succeed:** something of the house still stands when the ground
stops moving.

Failing Trial 2 and Trial 3 together already zeroes Manpower, Wealth,
AND Land at once — full Ruin, guaranteed, regardless of Trial 1's
result. Failing all three additionally means the family line has taken
three consecutive age-worsened death checks — Extinction is a very
live possibility on top of Ruin, not a separate bad-luck outcome.
**There is no version of failing the whole gauntlet that leaves a
house quietly surviving.**

## Determining the winner
After all 3 trials resolve, any house that collapsed during the round
is out of contention. Among the houses still standing, **sum all 7
stats** (Land + Manpower + Wealth + Piety + Legend + Cunning, plus
Honor/Infamy counted as its **absolute magnitude** — a deeply feared,
infamous house is just as formidable in the tally as a beloved one;
only near-total neutrality contributes little) — **highest total wins
the campaign.** This is deliberately the same shape the other 3
Calamity modules are meant to reuse (final gauntlet of bespoke trials,
then a survivor score tally) — it's also the answer to the
previously-unresolved "how does a campaign conclude, who wins"
question that applied to the whole game, not just this
module.

---

## Open items this module surfaced (not yet resolved)
- Whether a house that only just rebuilt after an earlier collapse
  (per `geography.md`'s rebuild-with-full-budget rule) is at an
  unfair disadvantage entering the Sundering with fresh, low stats —
  flagging, not fixing.
