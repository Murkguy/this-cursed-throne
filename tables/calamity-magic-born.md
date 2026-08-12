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

## Preparing for the End: the Ritual of the Unbroken Ward
Every Calamity module gives houses exactly ONE dedicated way to
prepare for its ending, at the cost of a Task Assignment slot that
could otherwise go toward growing the house today — Magic-Born's is
the **Ritual of the Unbroken Ward**.

A new Magic action, **STATIC, Legend + Cunning**, gated the same as
any other Magic action (see `tasks.md` — needs a relative who
underwent Magic conversion at Birth Deal). Attemptable **once per
decade**, any decade from the moment the module is chosen — not just
in the final stretch. A house that starts preparing early has more
chances to succeed than one that panics at Doom Clock 8.

- **Success:** bank **1 Ward**. A house may hold at most **3 Wards**
  at once — one per trial, no point banking more than the gauntlet
  can use.
- **Failure:** the meddling stirs the very thing it's trying to
  survive — **the Doom Clock advances by 1 immediately.** Reaching for
  a ward against the end of the world risks hastening it.

**Spending Wards, during the Sundering:** after a trial's roll
resolves (so the house knows exactly how bad it is before deciding),
spend any number of banked Wards to upgrade that trial's outcome one
tier per Ward spent (Loss→Narrow win, Narrow win→Decisive win — a
Loss can be pushed all the way to Decisive by spending 2 Wards on it).
Wards don't guarantee anything and can't prevent a bad roll, only
soften what it costs — and a house that never invested in Magic
across the campaign has none to spend when it matters most.

## The Final Round: The Sundering
Ten decades of mounting Legend have worn the world thin. When the
Doom Clock strikes its final mark, the wound tears open all at once —
this is the **last decade of the campaign**, and it does not resolve
gently. Before Task Assignment that decade, every house still standing
faces **3 sequential trials** — not one roll, a gauntlet. Stats update
immediately after each trial's consequences apply, so a house wounded
by an early trial enters the next one already bleeding — the damage
compounds on purpose, and it is meant to be felt.

**Each trial is COMPETITIVE, rolled against the Calamity itself**, not
a Static check against a fixed target — the Calamity's pool for Trial
N is **(the current decade number) × N**, so a Sundering triggered in
decade 10 pits Trial 1 against a pool of 10, Trial 2 against 20, Trial
3 against 30. This scales with however long the campaign actually ran
(more decades means more accumulated power on every side, so the
threat never goes stale) and gets meaningfully harder trial to trial.
Margin is graded using the normal Competitive band-width rule (see
`tasks.md`, Check Types) against whichever pool — house's or
Calamity's — is larger.

**Houses may ally on any trial.** Any number of houses facing the same
trial may pool their relevant stats into ONE combined roll against the
Calamity's pool for that trial — better odds for everyone involved.
But alliance only pools the DICE. **The outcome (decisive/narrow/loss)
applies identically to every allied house, but each house still
suffers its own consequences individually, using its own stats** — if
the trial calls for losing all Manpower, each allied house loses all
of its own Manpower, not a shared amount. Banding together to face the
end of the world is intended and encouraged; it does not make anyone
safe from it.

**Even a decisive win still costs something.** Nothing about the
Sundering is free.

**Every death check rolled during the Sundering is treated as one
age-tier worse than normal** (stacking with Sickly/Long-Lived) — the
Calamity does not spare the young or favor the strong.

A house that hits **Ruin or Extinction** (see `birth-death.md`) at any
point during this round collapses immediately and is **out of
contention** for the final score, same as any other collapse — no
special exception for the Sundering. Losing all 3 trials is written
below to guarantee this outcome on stats alone, on top of whatever the
death checks have already done to the family line — a house that
loses the whole gauntlet does not limp away from it.

### Trial 1: The Wild Surge — Legend + Cunning
The sky opens first. Color bleeds out of the world in slow pulses, and
for one unbearable moment every oath ever sworn, every curse ever
laid, every legend ever earned comes due at once — a tide of raw,
undirected magic sweeping over everything a house has ever done to be
remembered.

- **Decisive win:** the house holds its shape against the tide, but
  not without cost — lose **1 Cunning**.
- **Narrow win:** lose **1 Legend and 1 Cunning**, and the player's
  choice of ONE relative takes a death check — the house comes through
  scarred.
- **Loss:** the surge doesn't stop at reputation — it unravels
  everything this house is. **Lose 5 points from EVERY one of its 7
  stats** (Land, Manpower, Wealth, Honor/Infamy, Piety, Legend,
  Cunning — each floored at 0), and **EVERY relative tracked by this
  house** (Leader, spouse, every descendant and their own
  spouses/children still in the family tree) takes a death check. Not
  one chosen sacrifice — the whole bloodline stands in the surge
  together, and what it takes from a house, it takes from all of it.

### Trial 2: The Restless Dead — Manpower + Wealth
What the surge does not claim outright, it wakes. Barrows crack open.
Old battlefields give up what they buried. Every soldier a house ever
spent, every soul lost to the long slow bleed of War, rises now and
walks toward the living.

- **Decisive win:** the line holds, but the cost is real — lose **1
  Manpower**.
- **Narrow win:** lose **1 Manpower and 1 Wealth**, and ONE chosen
  relative assigned to the defense takes a death check.
- **Loss:** this house's standing army breaks entirely, and the dead
  do not stop at the gate. **Lose 5 points from EVERY one of its 7
  stats** (floored at 0) — coin, land, faith, renown, none of it
  matters to something that's already dead — and **EVERY relative**
  takes another death check, on top of whatever Trial 1 already cost
  this family.

### Trial 3: The Land Unmade — Land + Wealth
Last, and worst: the ground itself stops agreeing to exist. Fields,
walls, ancestral halls — the very earth a house's claim was built on
buckles, folds, and in places simply isn't there anymore when the
light comes back.

- **Decisive win:** something of the house still stands when the
  ground stops moving — lose **1 Land**.
- **Narrow win:** lose **1 Land and 1 Wealth**, and ONE chosen
  relative takes a death check.
- **Loss:** there is no ground left to stand on, and nothing that
  stood on it is spared. **Lose 5 points from EVERY one of its 7
  stats** (floored at 0) — a house that loses this trial already
  wounded loses whatever it had left standing — and **EVERY
  relative** takes a third death check.

**These -5-to-everything losses stack.** A house that loses two
trials takes -10 to every stat across the round; losing all three is
-15 to every stat, floored at 0 each time — for the overwhelming
majority of houses, even one lost trial is enough to threaten Ruin on
its own, and losing any two guarantees it regardless of how the third
goes. Losing all three additionally means the family line has taken
three consecutive age-worsened death checks — Extinction is a very
live possibility on top of Ruin, not a separate bad-luck outcome.
**There is no version of losing the whole gauntlet — or even losing
badly partway through it — that leaves a house quietly surviving.**

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
