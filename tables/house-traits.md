# House Trait Table

Every house has 4 traits: 2 chosen freely by the player, 2 rolled (see
`setup-order.md` step 3d). Both chosen and rolled traits come from this
same 25-entry list — "chosen" means picking which entry you want, not
inventing a new one.

**Rolling:** flip 2 cards and sum their ranks (Ace=1 ... King=13). The
sum (2-26) is a direct row-lookup below — 25 possible sums, 25 entries,
no wasted rows. This naturally bell-curves: sum 14 is the single most
likely result, the extremes (2 and 26) are the rarest — so the most
dramatic traits sit at the tails and the most ordinary ones sit in the
middle.

**Duplicates:** if a roll produces a trait the house already has
(chosen or previously rolled), reroll.

**Mutually exclusive pairs:** a house cannot have both **Fecund** and
**Barren**, or both **Sickly** and **Long-Lived** — they're direct
contradictions. If a roll produces one and the house already has its
opposite, reroll.

Every trait below cuts both ways — a real mechanical benefit paired with
a real cost. None are pure upside.

| Sum | Trait | Benefit | Cost |
|---|---|---|---|
| 2 | **Cursed** | Whenever this house's Leader dies, gain +1 Legend automatically (on top of normal Destiny inheritance) — the curse deepens with each death. | This house always draws 2 cards and keeps the worst on any events-deck draw targeting it, even without Legend 10+ — as if permanently carrying a King's burden. |
| 3 | **Sickly** | The Magic-conversion trigger widens from Ace of Spades only to any Ace **or 2** of Spades for this house's characters — illness draws them nearer the other side. | Death band shifts +1 tier (see `birth-death.md`). |
| 4 | **Barren** | +2 dice on all Stewardship tasks — a house unburdened by squabbling heirs runs a tighter administration. | No natural births, ever (see `birth-death.md`) — heirs only by marrying in. |
| 5 | **Cowardly** | +2 dice on Espionage tasks — skilled at avoiding confrontation and detection alike. | -2 dice on War tasks. |
| 6 | **Cruel** | +2 dice on Espionage tasks (intimidation and intrigue). | -2 dice on Stewardship tasks — smallfolk resent and resist cruel rule. |
| 7 | **Great Warriors** | +2 dice on War tasks. | -2 dice on Diplomacy tasks — a house known for the sword struggles at the negotiating table. |
| 8 | **Zealous** | +2 dice on the first task a relative attempts each decade — fervor sharpens whatever they're currently focused on. | -2 dice on every other task that same relative attempts that decade — single-minded, neglects all else. |
| 9 | **Proud** | +2 dice on Diplomacy tasks. | -2 dice on Espionage tasks — too proud to stoop to deception. |
| 10 | **Cunning Traders** | +2 dice on Trade tasks. | -2 dice on War tasks. |
| 11 | **Stewards Born** | +2 dice on Stewardship tasks. | -2 dice on War tasks. |
| 12 | **Pious** | +2 dice on Stewardship tasks — temple and faith organize a community well. | -2 dice on Trade tasks — forbidden from the most profitable but impious dealings. |
| 13 | **Frugal** | +2 dice on Trade tasks. | -2 dice on Diplomacy tasks — too stingy for the generous gestures diplomacy often needs. |
| 14 | **Steadfast** | +1 die on all STATIC checks. | -1 die on all COMPETITIVE checks — reliable in routine administration, unremarkable in direct contests. |
| 15 | **Boastful** | +2 dice on War tasks — bravado rallies troops. | -2 dice on Espionage tasks — loud mouths make poor spies. |
| 16 | **Scholarly** | +2 dice on Magic tasks. | -2 dice on War tasks. |
| 17 | **Expansionist** | +2 dice on War tasks. | -2 dice on Stewardship tasks — always looking outward, neglects the home front. |
| 18 | **Charitable** | +2 dice on Diplomacy tasks. | -2 dice on Trade tasks — generous to a fault, gives away what could've been profit. |
| 19 | **Ambitious** | +2 dice on War tasks that target the current King's house specifically. | -2 dice on War tasks against any other house — no interest in "small" fights, hungry only for the crown. |
| 20 | **Isolationist** | +2 dice on Stewardship tasks. | -2 dice on Diplomacy tasks — inward-focused, distrustful of outsiders. |
| 21 | **Silver-Tongued** | +2 dice on Diplomacy tasks. | -2 dice on War tasks — words, not swords. |
| 22 | **Superstitious** | +2 dice on Magic tasks. | -2 dice on Trade tasks — refuses deals struck under the wrong omens. |
| 23 | **Duplicitous** | +2 dice on Espionage tasks. | -2 dice on Diplomacy tasks — too clever by half, allies never quite trust their word. |
| 24 | **Fecund** | Birth band widens to 9-King (see `birth-death.md`). | -1 Wealth each time a birth occurs — many children strain the treasury. |
| 25 | **Long-Lived** | Death band shifts -1 tier (see `birth-death.md`). | -2 dice on Magic tasks — a house that endures long ages grows resistant to fleeting magic, or magic avoids those who cheat death naturally. |
| 26 | **Magical** | The Magic-conversion trigger includes any face card (J/Q/K), not just the Ace of Spades (see `birth-death.md`). | This house always draws 2 cards and keeps the worst specifically on Spade-suited events-deck draws targeting it — magic draws Calamity's attention. |

---

## Open items this pass surfaced (not yet resolved)
- Whether Static/Competitive check bonuses (e.g. Steadfast) and task-type
  bonuses (e.g. Great Warriors) can stack on the same roll if a task is
  both War and a STATIC check, or whether that's even possible under the
  existing check-type rules
- Character (relative) trait table — separate from this one (confirmed
  earlier), not yet drafted
