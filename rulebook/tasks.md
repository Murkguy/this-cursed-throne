# Tasks — Stats, Check Types, and Actions

Every task's dice pool = its stat below + the acting relative's trait
bonus (if a trait fits) + scene modifiers (see `turn-order.md`, Phase 5).
Five house stats, six tasks — Wealth is shared by Trade and Espionage,
matching the original notes' description of Wealth as covering
"bribes, dowries, feasts, **hiring**."

| Task | Stat | Check Type | Opposed By | Example actions |
|---|---|---|---|---|
| **War** | Manpower | COMPETITIVE, always — target must be ring-adjacent (see `geography.md`) | Manpower | Campaigns, sieges, border raids. |
| **Trade** | Wealth | STATIC, always | — | Brokering deals, establishing trade routes, claiming unclaimed Wealth. |
| **Diplomacy** | \|Honor/Infamy\| (absolute value — see below) | STATIC, always | — | Marriage proposals, forging alliances, courting favor, claiming unclaimed Honor. |
| **Espionage** | Wealth | COMPETITIVE, always — always has a target | Stewardship | Spying, sabotage, assassination attempts, blackmail. |
| **Stewardship** | Land | STATIC, always (never initiates a Competitive check) | (see above — defends against Espionage) | Developing land, growing population, claiming unclaimed Land. |
| **Magic** | Legend | STATIC, always — gated behind the Magic trait | — | Scrying, cursing a rival's harvest, communing with something not fully of this world (see `decisions-log.md` for the Magic-trait rules). |

Only War and Espionage are Competitive — both are inherently adversarial
(they always target a specific house). The other four are Static: about
growing what you have or acting on the world/circumstance rather than
directly contesting a rival, per the original resolution-mechanic rules.

## Diplomacy uses |Honor/Infamy|, not Honor/Infamy directly
A house with -8 Infamy rolls the same Diplomacy pool size as a house
with +8 Honor — an infamous house is just as diplomatically potent as a
beloved one, just through fear and reputation rather than trust. A
house sitting near 0 (unknown, unremarkable) has the weakest Diplomacy
pool of all. This makes staying reputationally invisible an active
liability, not a safe default.

## Static check target number
STATIC checks need a fixed number of successes to pass — proposing **2
successes** as the default target, adjustable by the GM for unusually
easy or hard circumstances. Not yet confirmed; flagging rather than
quietly assuming, since nothing in the resolved rules ever set this
number.

## Stewardship's dual role
Stewardship never initiates a Competitive check, but it IS the stat a
house defends with when targeted by an Espionage task — an attacker's
Wealth-based Espionage pool rolls against the defender's Land-based
Stewardship pool. Confirms and preserves the "Espionage vs. Stewardship
defense" example from the original design notes.

## What a successful Static task grants
Trade, Diplomacy, and Stewardship successes let a house claim the
matching resource from the unclaimed pool (Wealth, Honor, and Land
respectively) — consistent with the already-resolved rule that
unclaimed-pool resources are only ever claimed via a task, never
auto-assigned. Magic does not touch the standard resource economy at
all — its reward is always a unique narrative effect, never a stat
claim, per the already-resolved "Magic unlocks unique task options
rather than granting bonus dice" rule.

---

## Task-type and check-type trait bonuses stack freely
Now that every task has exactly ONE fixed check type (never
situational), the stacking question from the house trait table is
resolved: they're just two independent modifiers added to the same
pool. A Steadfast house (+1 Static/-1 Competitive) attempting Trade
(always Static) gets Steadfast's +1; the same house attempting War
(always Competitive) gets Steadfast's -1. A Great Warriors house
(+2/-2 War/Diplomacy) attempting War gets its own +2 on top of whatever
check-type modifier applies. No conflict, no special stacking rule
needed — they were never actually competing for the same modifier slot.

## Open items this pass surfaced (not yet resolved)
- Static check target number (proposing 2 successes as default, not yet
  confirmed)
