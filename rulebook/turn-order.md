# Turn Order — The Decade Loop

Each decade runs through five phases in order. **Tasks assigned in Phase
5 of one decade resolve at the top of Phase 1 of the NEXT decade** — there
is a full decade of in-fiction time between assigning a task and learning
its outcome. This is inferred from the phase ordering (Task Assignment is
last, Resolution is "check outcomes of last decade's tasks") rather than
stated as an explicit rule anywhere — flagging it because it's easy to
misread as "assign and resolve immediately."

## Phase 1: Resolution
Opens the decade by settling everything set in motion last decade.

1. **Run the Fate Check** for births and deaths. See
   `birth-death.md` for the full mechanic (per-relative death checks
   weighted by age and Dynastic traits, per-couple birth checks).
2. **Check task outcomes.** Every task assigned during last decade's
   Phase 5 resolves now, using the dice-pool mechanic (STATIC or
   COMPETITIVE check, as appropriate to the task) — EXCEPT a task whose
   assigned relative died in step 1 above, which **auto-fails**, no roll
   made. Death is checked first specifically so this is possible; a dead
   relative's pending task is already known to be dead-on-arrival by the
   time you get here. A relative whose task was **War** gets one
   additional death check right now (see `birth-death.md`) once that
   War's outcome is known.
3. **Apply trait changes.** Whenever a character is directly involved in
   a Destiny-triggering event (death of the house's leader, the house
   overtaking #1 in some ranking, the house becoming the new lowest-
   ranked, calamity compensation, resolving a vendetta, or winning the
   crown — see `king-and-revolt.md` for the full Destiny trigger list),
   that character may swap one existing trait for a newly flipped one —
   a single card flip, same 13-entry trait table lookup as Birth Deal.
   Reuses the Destiny trigger list rather than a separate "how major is
   major" judgment call.

## Phase 2: Scene Declaration
Every house writes **exactly 1 scene intent** for the decade on a
notecard — who they want a scene with, and what they're attempting
(including poisonings, backroom deals, betrayals, alliances). All cards
flip simultaneously. Nothing stays hidden once flipped. One scene per
house, flat, regardless of player count — "scales with player count" is
satisfied automatically, since more houses means more scenes running in
parallel, not more scenes per house.

If two houses' declared scenes conflict (e.g. both target the same third
house at the same moment, or contradict each other), **house order sets
priority** — whichever house is earlier in the order gets their scene as
declared; the conflicting house's scene is bumped or must be re-narrated
around it. House order is set at setup (see `setup-order.md`) and only
changes when a King spends the house-order-move power described in
Phase 4 below.

## Phase 3: Scene Resolution
Since nothing is hidden after declaration, every declared scene can run
in parallel around the table — no single-adjudicator bottleneck, since
there's no persistent GM to run every scene through.

**Scenes are freeform by default.** A Scene is played out narratively;
it only calls for a dice-pool check (STATIC or COMPETITIVE, using the
matching task type) at the moment something concrete is actually being
risked or contested — a poisoning attempt triggers an Espionage check, a
betrothal negotiation triggers a Diplomacy check, but a scene that's pure
conversation/politics needs no roll at all. This reuses the exact same
task-type dice system rather than a separate "scene mechanic."

## Phase 4: Kingdom Scene
**The King's player** reveals the decade's big public moment by drawing
from the **events deck** — or, if the throne is currently vacant, any
player does (it doesn't matter who physically draws, the fixed table
lookup decides the outcome either way). Suit = category (♥
Dynastic/Personal, ♦ Wealth/Trade, ♣ Military/Political, ♠
Calamity/Doom), rank = outcome quality (low→high = bad→good). If any
house has Legend 10+ (including any King, who gets +10 automatically),
that house draws extra cards per every 10 Legend and keeps the lowest.
If the kept card is an Ace/2/3, the Doom Clock advances by 1. Deck is
reshuffled after every draw. **The Doom Clock's current value is
public** — tracked openly at the table (a visible counter or token),
never hidden. It threatens every house's win condition equally, so
there's no reason to hide it — consistent with there being no
persistent GM to gatekeep it in the first place.

This is also where a declared Revolt (from this same decade's Phase 2)
resolves, if one was declared — NOT next decade's Kingdom Scene, this
one, later in the same loop. Alliances are drawn live at this point if a
Revolt is resolving. See `king-and-revolt.md` for the full Revolt
procedure (bids, alliances, the roll, failure cost, Mercy).

**Decade 1 is a special case: the throne cannot leave this Kingdom Scene
still vacant.** If a house declared a bid in Decade 1's Phase 2, it
resolves here normally. If nobody did, any player flips one card per
house right now, highest card is forced to assume the throne (redraw
ties). See `setup-order.md`, step 6. No other decade has this forcing
rule — after Decade 1, the throne can stay vacant indefinitely if no
one bids for it.

**The King's per-turn powers happen here too**, as the second half of
this phase: after the events-deck reveal above (and after Revolt
resolution, if any), the King must grant 1 resource from the unclaimed
pool, may then redistribute one resource between houses, may confer an
eligible moniker, and **may move 1 house's position in the house order**
(see Phase 2's scene-conflict priority rule). All four are exercised
during Kingdom Scene, not as a separate phase.

House order is therefore not fixed for the campaign — it only ever
changes when the King chooses to spend this power, one house at a time,
one move per turn. No King means no change to the order that decade.

## Phase 5: Task Assignment
Players delegate relatives to a specific action within one of the six
task categories (War, Trade, Diplomacy, Espionage, Stewardship, Magic —
see `tasks.md` for each category's stat and its menu of named actions),
based on the relative's traits and the house's stats. **The House
Leader can be assigned to a task the same as any other relative** — no
restriction keeping them home. These tasks resolve next decade, in
Phase 1.

**War can only target a ring-adjacent house** — see `geography.md`.
Every other task type is unrestricted by geography.

**One Task per relative per decade** — no relative can be double-booked
across two Tasks in the same decade.

A relative involved in this decade's Scene CAN also be assigned a Task
the same decade, but **at most 2 relatives per house** may be
double-booked this way (Scene + Task) in a single decade. This matters
because a Scene can involve more than one of a house's relatives at
once — the cap limits how much a house can pack into one decade, not
whether double-booking is allowed at all.

---

## Open items this phase surfaced (not yet resolved)
- Whether house order (scene-conflict priority) is fixed for the
  campaign or rotates decade to decade
