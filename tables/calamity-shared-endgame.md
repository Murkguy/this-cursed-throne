# Calamity Modules — Shared Endgame Mechanics

Every Calamity module ends the campaign the same way once its own
Doom Clock reaches its max — this file is that shared shape, factored
out so each module file only needs to define what's actually unique to
it (theme, Doom Clock trigger, prep action, and its 3 trials). If a
module's file and this one ever disagree on the shared mechanics, this
file wins — fix the module file, not this one, unless a module
explicitly and deliberately overrides something (and says so).

## The Final Round
Triggered the decade a module's Doom Clock reaches its max — this is
the **last decade of the campaign**. Before Task Assignment that
decade, every house still standing faces **3 sequential trials**
specific to the chosen module — not one roll, a gauntlet.

- **Each trial is COMPETITIVE, rolled against the Calamity itself.**
  The Calamity's pool for Trial N is **(the current decade number) ×
  N** — a Sundering-equivalent triggered in decade 10 pits Trial 1
  against a pool of 10, Trial 2 against 20, Trial 3 against 30. This
  scales with however long the campaign actually ran, so the threat
  never goes stale regardless of how strong houses have grown.
- Margin is graded using the normal Competitive band-width rule (see
  `tasks.md`, Check Types) against whichever pool — house's or
  Calamity's — is larger.
- Stats update immediately after each trial's consequences apply, so a
  house wounded by an early trial enters the next one already
  bleeding — the damage compounds on purpose.
- **Houses may ally on any trial.** Any number of houses facing the
  same trial may pool their relevant stats into ONE combined roll
  against the Calamity's pool. The outcome (decisive/narrow/loss)
  applies identically to every allied house, but each house still
  suffers its own consequences individually, using its own stats.
  Banding together for better odds is always intended and encouraged;
  it never reduces individual stakes.
- **Every death check rolled during the Final Round is one age-tier
  worse than normal** (stacking with Sickly/Long-Lived) — the Calamity
  does not spare the young or favor the strong.
- A house that hits **Ruin or Extinction** (see `birth-death.md`) at
  any point during the round collapses immediately and is **out of
  contention**, same as any other collapse.

## Standard trial outcome shape
Unless a module's own trial explicitly says otherwise, every trial
uses this same three-tier shape:

- **Decisive win:** lose 1 point from ONE of the trial's two pool
  stats (the module picks which, to fit its flavor).
- **Narrow win:** lose 1 point from EACH of the trial's two pool
  stats, and the player's choice of ONE relative takes a death check.
- **Loss:** lose **5 points from EVERY one of the house's 7 stats**
  (Land, Manpower, Wealth, Honor/Infamy, Piety, Legend, Cunning — each
  floored at 0), and **EVERY relative tracked by the house** (Leader,
  spouse, every descendant and their own spouses/children still in the
  family tree) takes a death check.

**Nothing about the Final Round is free — even a decisive win costs
something.** The -5-to-everything Loss stacks across multiple lost
trials (-10 for two, -15 for three, floored at 0 each time it's
applied): for most houses, even ONE lost trial threatens Ruin on its
own, and losing any two guarantees it regardless of the third. Losing
all three additionally means the family line has taken three
consecutive age-worsened death checks — Extinction is a very live
possibility on top of Ruin, not a separate bad-luck outcome. There is
no version of losing a Final Round — or even losing badly partway
through one — that leaves a house quietly surviving.

## The prep-action pattern
Every Calamity module grants exactly **one** dedicated action for
preparing against its own ending, costing a Task Assignment slot today
in exchange for a real edge when the Final Round arrives — see
`tasks.md`'s Magic section for the cross-reference pattern. Each
module defines its own version, themed to its own flavor (Magic-Born's
is the Ritual of the Unbroken Ward — `tables/calamity-magic-born.md`).

## Determining the winner
After all 3 trials resolve, any house that collapsed during the round
is out of contention. Among the houses still standing, **sum all 7
stats** (Land + Manpower + Wealth + Piety + Legend + Cunning, plus
Honor/Infamy counted as its **absolute magnitude** — a deeply feared,
infamous house is just as formidable in the tally as a beloved one) —
**highest total wins the campaign.** This is the answer to "how does a
campaign conclude, who wins" for the whole game, not just one module.
