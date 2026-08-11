# House Trait Table

Every house has 4 traits: 2 chosen freely by the player, 2 rolled (see
`setup-order.md` step 3b). Both chosen and rolled traits come from this
same 52-entry list — "chosen" means picking which card's trait you want,
not inventing a new one.

**Rolling:** flip 1 card. Its exact identity (e.g. "7 of Hearts") is a
direct lookup below — no math, no summing, just find that card. Suit is
the same four categories as the events deck (♥ Dynastic/Personal, ♦
Wealth/Trade, ♣ Military/Political, ♠ Calamity/Doom); rank runs roughly
mundane-to-dramatic from Ace to King within each suit.

**Duplicates:** if a roll produces a trait the house already has (chosen
or previously rolled), reroll.

**Mutually exclusive pairs:** a house cannot have both **Fecund** and
**Barren**, or both **Sickly** and **Long-Lived** — direct
contradictions. If a roll produces one and the house already has its
opposite, reroll.

Every trait cuts both ways — a real benefit paired with a real cost.
None are pure upside, but they don't need to be precisely balanced
against each other — some traits are simply stronger or weaker than
others, same as any trait table.

## ♥ Hearts — Dynastic

House-level traits only — institutional, bloodline, or generational
characteristics a whole dynasty shares, not one person's mood. (An
earlier draft of this suit mixed in individual personality traits like
Timid and Prideful; those were pulled out to seed the future character
trait table — see `character-traits-bank.md`.)

| Rank | Trait | Benefit | Cost |
|---|---|---|---|
| A | **Inbred Line** | +1 die on Trade tasks — a tightly controlled internal economy. | -2 dice on Diplomacy tasks — insular, awkward with outsiders. |
| 2 | **Sickly** | +2 Piety — suffering breeds deep devotion. | Death band shifts +1 tier (see `birth-death.md`). |
| 3 | **Fostering Tradition** | +1 die on Diplomacy tasks — wards and hostages exchanged as political bonds. | -2 dice on Stewardship tasks — always distracted managing outside children. |
| 4 | **Barren** | +2 dice on all Stewardship tasks. Unlocks **Adopt an Heir** (see `rulebook/tasks.md`, Diplomacy) as this house's real path to new heirs. | No natural births, ever (see `birth-death.md`). |
| 5 | **Kinslayers** | +2 dice on War tasks — a family hardened by its own internal bloodshed. | -2 dice on Diplomacy tasks — no one fully trusts a house that turns on its own. |
| 6 | **Hostage Culture** | +2 dice on Espionage tasks — generations of practice handling prisoners as leverage. | -2 dice on Trade tasks — the practice poisons trade relationships. |
| 7 | **Steadfast** | +1 die on all STATIC checks. | -1 die on all COMPETITIVE checks — reliable in routine matters, unremarkable in direct contests. |
| 8 | **Long Memory** | +2 dice on Diplomacy tasks — this house never forgets an old alliance. | -1 die on War tasks — slow to fully commit while still weighing old grudges. |
| 9 | **Ancestral Seat** | +2 dice on Stewardship tasks — generations of investment in this land. | -1 die on Magic tasks — too grounded in tradition, resistant to strange new practices. |
| 10 | **Fecund** | Birth band widens to 9-King (see `birth-death.md`). | -1 Wealth each time a birth occurs. |
| J | **Grand Lineage** | +3 dice on Diplomacy tasks — a storied bloodline commands real respect at court. | -1 die on Espionage tasks — too famous to move unseen. |
| Q | **Long-Lived** | Death band shifts -1 tier (see `birth-death.md`). | -1 die on Magic tasks. |
| K | **Cursed** | Whenever this house's Leader dies, gain +1 Legend automatically (on top of normal Destiny inheritance). | -1 die on Diplomacy tasks — others fear the cursed. |

## ♦ Diamonds — Wealth/Trade

| Rank | Trait | Benefit | Cost |
|---|---|---|---|
| A | **Stingy** | +1 die on Trade tasks. | -2 dice on Diplomacy tasks. |
| 2 | **Hospitable** | +1 die on Diplomacy tasks. | -2 dice on Trade tasks. |
| 3 | **Pious** | +1 die on Stewardship tasks — temple and faith organize a community well. | -2 dice on Trade tasks — forbidden from the most profitable but impious dealings. |
| 4 | **Cunning Traders** | +1 die on Trade tasks. | -2 dice on War tasks. |
| 5 | **Stewards Born** | +2 dice on Stewardship tasks. | -2 dice on War tasks. |
| 6 | **Isolationist** | +2 dice on Stewardship tasks. | -2 dice on Diplomacy tasks. |
| 7 | **Extravagant** | +2 dice on Diplomacy tasks — lavish feasts win favor. | -2 dice on Trade tasks — spends too freely. |
| 8 | **Enterprising** | +2 dice on Trade tasks. | -2 dice on Stewardship tasks — always chasing the next venture. |
| 9 | **Charitable** | +2 dice on Diplomacy tasks — generosity wins hearts and favor. | -1 die on Trade tasks — too generous to profit. |
| 10 | **Frugal** | +2 dice on Trade tasks. | -1 die on War tasks — unwilling to fund costly campaigns. |
| J | **Ostentatious** | This house's STATIC Diplomacy actions always succeed — no roll needed, wealth speaks loud enough that failure isn't an option. | -2 dice on Espionage tasks — too visible to ever move unseen. |
| Q | **Landed Gentry** | Once per campaign, this house may immediately claim 2 Land from the unclaimed pool for free — no roll, no Task Assignment slot spent, an ancestral claim honored on sight. | -2 dice on Trade tasks — comfortable old money, not hungry for more. |
| K | **Golden** | At setup, this house's resource budget (`setup-order.md` step 3c) is 14 points instead of 12. | -1 die on War tasks — wealth breeds complacency. |

## ♣ Clubs — Military/Political

House-level traits only, same rule as Hearts — a whole house's political
standing or military doctrine, not one person's mood. Cowardly was
pulled (personal, not institutional) and banked in
`character-traits-bank.md`; Ill-Trained Levies replaces it.

**Rank order is ACE-HIGH** — 2 is the worst card, Ace is the best,
reversing the low-to-high convention used elsewhere (Birth Deal, the
events deck). Within a suit: ranks 2-4 net **-1 die** total (benefit
minus cost), with rank 2 also carrying a bespoke restriction beyond
dice; ranks 5-7 net **0** (a pure sidegrade); ranks 8-10 net **+1 die**;
J/Q/K/A abandon dice math entirely for unique, positive mechanics.

| Rank | Trait | Benefit | Cost |
|---|---|---|---|
| 2 | **Ill-Trained Levies** | +1 die on Trade tasks — cheap, expendable manpower frees up resources elsewhere. | This house's Manpower-based rolls (War, Border Raid) only count 6s as successes, not 5-6 — a poorly-drilled, wasteful fighting force. |
| 3 | **Cruel** | +1 die on Espionage tasks. | -2 dice on Stewardship tasks — smallfolk resent and resist cruel rule. |
| 4 | **Silver-Tongued** | +1 die on Diplomacy tasks — generations of skilled orators and negotiators. | -2 dice on War tasks. |
| 5 | **Boastful** | +2 dice on War tasks — a warfare culture built on grand declarations and bravado. | -2 dice on Espionage tasks — too loud a reputation for subtlety. |
| 6 | **Zealous** | +2 dice on the first task a relative attempts each decade. | -2 dice on every other task that same relative attempts that decade. |
| 7 | **Disciplined** | +1 die on War and Stewardship tasks. | -1 die on Diplomacy and Espionage tasks. |
| 8 | **Great Warriors** | +2 dice on War tasks. | -1 die on Diplomacy tasks. |
| 9 | **Expansionist** | +2 dice on War tasks. | -1 die on Stewardship tasks — always looking outward. |
| 10 | **Duplicitous** | +2 dice on Espionage tasks. | -1 die on Diplomacy tasks — allies never quite trust their word. |
| J | **Warmonger** | Whenever this house's War or Border Raid results in a decisive win, capture DOUBLE the normal stakes. | Whenever this house would gain Honor from an event, gain 1 less. |
| Q | **Kingmaker** | Whichever side (King's loyalists or a challenger's bloc) this house joins during a Revolt resolution gets +3 dice on the roll — regardless of this house's own stat contribution. Their endorsement carries the weight, not their army. | -1 die on Magic tasks — all politics, no patience for mysticism. |
| K | **Tyrannical** | While this house holds the crown, it may exercise EACH King's per-turn power (grant, redistribute, confer a moniker, move house order) twice per decade instead of once. | While this house holds the crown, -1 die on every OTHER task type — absolute power, absolute overreach. |
| A | **Ambitious** | Whenever this house declares a bid to contest the crown (Revolt), they immediately gain 1 ADDITIONAL Destiny — even if they already hold one. Deliberate exception to the "only one Destiny per house" rule: their hunger for power bends fate at the crucial moment, rules be damned. | -1 die on Stewardship tasks — too fixed on the throne to tend their own lands. |

## ♠ Spades — Calamity/Doom

| Rank | Trait | Benefit | Cost |
|---|---|---|---|
| A | **Superstitious** | +2 dice on Magic tasks. | -2 dice on Trade tasks — refuses deals struck under the wrong omens. |
| 2 | **Scholarly** | +2 dice on Magic tasks. | -2 dice on War tasks. |
| 3 | **Sly** | +2 dice on Espionage tasks. | -2 dice on Diplomacy tasks. |
| 4 | **Paranoid** | +2 dice on Espionage tasks — always watching. | -2 dice on Trade tasks — trusts no merchant. |
| 5 | **Reclusive** | +2 dice on Magic tasks. | -2 dice on Diplomacy tasks. |
| 6 | **Watchful** | +1 die on Espionage tasks. | -1 die on Trade tasks. |
| 7 | **Secretive** | +2 dice on Espionage tasks. | -2 dice on Trade tasks — too guarded to grease a deal. |
| 8 | **Ruthless** | +2 dice on Espionage tasks. | Whenever this house would gain Honor from an event, gain 1 less. |
| 9 | **Omen-Marked** | +2 dice on Magic tasks. | -2 dice on Espionage tasks — their omens give them away. |
| 10 | **Magical** | The Magic-conversion trigger includes any face card (J/Q/K), not just the Ace of Spades (see `birth-death.md`). | This house always draws 2 cards and keeps the worst specifically on Spade-suited events-deck draws targeting it. |
| 11 | **Doom-Touched** | Whenever this house's kept events-deck card triggers the Doom Clock, also gain +1 Legend. | -2 dice on Diplomacy tasks — people are wary of them. |
| 12 | **Shadow-Bound** | +2 dice on Espionage tasks targeting the King's house specifically. | -2 dice on Espionage tasks against any other house. |
| K | **Harbinger** | Once per decade, may voluntarily advance the Doom Clock by 1 to gain +1 Legend. | -2 dice on Stewardship tasks — obsessed with the coming end, neglects the mundane. |

---

Task stats, categories, and named actions are now fully defined in
`rulebook/tasks.md`. Task-type and check-type bonuses stack freely
since every individual ACTION (not category — Trade now has both a
Static action and a Competitive one) has exactly one fixed check type.

## House-level vs. personal traits
A house trait must describe something the whole dynasty shares across
generations — a military tradition, a bloodline curse, a mercantile
reputation — not one person's mood. Traits that read as individual
personality get pulled and banked in `character-traits-bank.md` for the
future character trait table, with house-appropriate replacements
drafted in their place at the same rank (same magnitude tier). Applied
to Hearts so far; still needs applying to Diamonds, Clubs, and Spades.

## Rank-tier magnitude curve
Within each suit, low ranks (A-4) have a weak benefit (+1) paired with
a standard cost (-2), mid ranks (5-8) stay standard on both (+2/-2),
and high ranks (9-K) get a strong benefit (+2 to +3) paired with a weak
cost (-1) — "the lower the card, the worse it is," reusing the same
low=bad/high=good convention as everything else in the game. **Cost
never exceeds -2** — starting stats can be as low as 1 (the point-buy
floor) or a modest 4-6 typically, so anything harsher is crippling
rather than a flavorful tradeoff; the curve works entirely through the
benefit side instead. Traits don't need to be precisely balanced
against each other, only internally honest (a real cost, a real
benefit, weighted to their rank). Applied to Hearts; still needs
applying to Diamonds, Clubs, and Spades.

## Open items this pass surfaced (not yet resolved)
- Character (relative) trait table — separate from this one, not yet
  drafted (`character-traits-bank.md` has 7 candidates banked so far)
- Landed Gentry (Diamonds Q): what happens if the unclaimed pool has
  less than 2 Land available when claimed — take whatever's there, or
  can it go unclaimed and wait?
