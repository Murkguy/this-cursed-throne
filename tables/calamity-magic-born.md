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
The decade the Doom Clock reaches 10 is the **last decade of the
campaign**. Before Task Assignment that decade, every house still
standing faces **3 sequential trials** — not one roll, a gauntlet.
Each trial is a STATIC check (target = round(pool÷3)+1, same formula
as any other Static check) rolled individually by every house still
in the campaign. Stats update immediately after each trial's
consequences apply, so a house wounded by an early trial enters the
next one with a smaller pool — the damage compounds on purpose.

A house that hits **Ruin or Extinction** (see `birth-death.md`) at any
point during this round collapses immediately and is **out of
contention** for the final score, same as any other collapse — no
special exception for the Sundering.

### Trial 1: The Wild Surge — Legend + Cunning
Raw magic floods the realm in an uncontrolled tide. **Fail:** this
house loses **2 Legend**, and the player's choice of one relative
takes an immediate death check (age/trait-adjusted band, same as the
Fate Check). **Succeed:** no effect — the house weathers the surge.

### Trial 2: The Restless Dead — Manpower + Wealth
Spirits and magic-warped horrors assail every house's lands,
demanding a defense. **Fail:** this house loses **1 Manpower and 1
Land** (sent to the unclaimed pool), and the player's choice of one
relative assigned to the defense takes a death check. **Succeed:** no
effect.

### Trial 3: The Land Unmade — Land + Wealth
The ground itself buckles as reality tears further. **Fail:** this
house loses **HALF of its remaining Land and Wealth**, each rounded
down. **Succeed:** no effect.

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
