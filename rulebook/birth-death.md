# Birth & Death — The Fate Check

Runs during Resolution, Phase 1, step 1 of every decade (before task
outcomes are checked — see `turn-order.md`). This is the *ambient*
background life-cycle mechanic: natural births and natural deaths. War,
Calamity, Revolt failure, and Espionage can still kill characters through
their own already-resolved mechanics — this check exists so that time
passing, by itself, has real weight.

Only the House Leader, their spouse, and direct descendants (and those
descendants' own spouses/children, if a player chooses to develop that
branch) are mechanically tracked. Siblings' children, cousins, and other
collateral relatives are not procedurally generated or checked — they
only exist if a player narrates one into the story for a specific
reason. This keeps the check scoped to a manageable family tree
regardless of how many generations a campaign runs.

## Age
Every tracked character has an **age**, measured in decades since birth
(age 0 = born this decade, age 1 = one decade old, and so on — 10 years
per age point). No separate calendar to track; age is just "how many
Resolution phases have passed since this character was born (or, for
starting characters, since setup)."

**Starting age at setup:** the House Leader begins at **age 3** (30-39
years old). The spouse is assumed to start at the same age unless a
player wants to narratively justify otherwise.

## Death Check — per relative, per decade
Every tracked living relative gets **one card flip** per decade. Death
occurs if the flipped rank falls within that character's current death
band, which widens with age:

| Age (decades since birth) | Death band | Approx. odds |
|---|---|---|
| 0-2 (0-29 yrs) | Ace | ~7.7% |
| 3-5 (30-59 yrs) | Ace-2 | ~15.4% |
| 6-8 (60-89 yrs) | Ace-4 | ~30.8% |
| 9+ (90+ yrs) | Ace-7 | ~53.8% |

**Trait modifiers** shift a character's effective tier before checking
the band:
- **Sickly** — treated as one tier older (shift +1)
- **Long-Lived** — treated as one tier younger (shift -1, floor at tier
  0 — never better odds than the 0-2 band)

Validated by simulation: base curve gives a median death age of ~50
years (mean ~51). Sickly drags the mean down to ~33 years; Long-Lived
extends it to ~68. A meaningful, felt difference in both directions —
consistent with "no pure upside" trait design.

**Who dies, if the check triggers:** open question, not yet decided (see
below).

## Birth Check — per viable couple, per decade
Every viable couple in the tracked family (a pairing capable of having a
child — narratively determined, not restricted by gender) gets **one
card flip** per decade, independent of the death check. Birth occurs on
rank **Queen-King** (~15.4%).

Birth is NOT age-weighted (unlike death) — kept flat to avoid stacking
two new curves in the same pass. Revisit later if it feels wrong at the
table.

**Trait modifiers:**
- **Fecund** widens the birth range to **9-King** (~30.8%) — on top of
  the extra-starting-children bonus already resolved in `setup-order.md`
- **Barren** removes the birth range entirely — this house cannot
  produce natural births; heirs only arrive by marrying in

If a birth occurs, the new child is generated immediately via **Birth
Deal** (see `decisions-log.md`), starting at age 0.

---

## Open items this pass surfaced (not yet resolved)
- Who dies when a relative's death check triggers — player's choice, or
  some other method? (Deferred from the original discussion pending
  further thought.)
- Whether the spouse can start at a different age than the Leader by
  player choice, or must always match
