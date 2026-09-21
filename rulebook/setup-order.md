# Setup Order

Follow these steps in order to start a new campaign of *This Cursed
Throne*. Every step below is either a RESOLVED rule or an explicitly
flagged placeholder awaiting content — nothing here should require the
table to guess.

## 1. Gather players
Each player will create and lead one noble House for the campaign.
**No persistent GM** — every check resolves by fixed rule (dice pool,
card flip, or table lookup), never by adjudication, so there's no
judgment call for a dedicated role to make. Kingdom Scene's events-deck
reveal is handled by whichever house currently holds the crown (see
`turn-order.md`, Phase 4) — the King acting as a temporary, powerless-
beyond-the-fixed-rules host of that moment, not a GM. Any purely
mechanical bookkeeping that comes up before a King exists (e.g. Decade
1's forced-king draw, step 6 below) can be done by any player — it
doesn't matter who physically flips the card, since the fixed rule
decides the outcome either way.

**Minimum 4 players.** No upper cap — table size is the players' own
call, not a role's to judge. Scene count already scales with player
count (1 scene per house per decade, so more houses just means more
scenes running in parallel).

Establish a **house order** now — the players sort out among themselves
who sits where in the ring, no mechanical process (no roll, no fixed
rule) beyond table negotiation. This sets priority if two houses'
declared scenes ever conflict during play (see `turn-order.md`, Phase
2), AND it's the map of the realm: house order forms a ring with the
King's seat as the capital, and only ring-adjacent houses can go to War
with each other (see `geography.md`). This order doesn't rotate on a
schedule; it only changes when a King later spends their per-turn power
to move one house's position (see `turn-order.md`, Phase 4).

## 2. Choose a Calamity module
Before anything else about the world is decided, the table picks ONE
Calamity module together — this is the shared threat the campaign is
building toward, and each module defines its own Doom Clock starting
length/max, its own advance trigger, and its own final-round trials
(see `gameflow.md` for how this fits the rest of play).

- **Magic-born** (tied to Legend) — **DRAFTED**, see
  `tables/calamity-magic-born.md`.
- **External invasion** — **DRAFTED**, see `tables/calamity-invasion.md`
  (one content dependency flagged: its Doom Clock trigger needs
  specific events-deck cards that don't exist yet).
- Systemic collapse of the zero-sum economy, slow environmental/
  supernatural blight — *(Open: not yet drafted.)*

## 3. Create your House

### 3a. Choose House Archetype and Succession Custom
Before anything else about the house — pick a **House Archetype**
(Noble House, Merchant House, Mercenary Company, Priestly Cloister,
Magical Order, Knightly Order, or Scholarly Order) and a **Succession
Custom** (Primogeniture, Patriarchal, Matriarchal, or Ultimogeniture).
Both are one-time choices for the whole campaign — see
`house-archetypes.md` for what each one does. Done first because some
archetypes affect the next two steps (Magical Order auto-grants the
Magical trait, so a player needs to know that before spending a free
trait pick on it in step 3b; Golden similarly matters before step 3c).

### 3b. Generate house traits
Every house has **4 traits total**: 2 chosen freely by the player, 2
rolled on the house trait table (`tables/house-traits.md` — flip 1
card, look up its exact suit and rank directly, no math). Every trait —
chosen or rolled — must be given a narrative justification when picked;
that justification IS the house's lineage/history (no separate lineage
system). Done before resource allocation, because one trait (**Golden**)
changes the resource budget used in the next step.

### 3c. Allocate starting resources
Each house divides **12 points** (or **14**, if the house took Golden)
among Land, Manpower, and Wealth as the player chooses, with a
**minimum of 1 point in each stat**. (E.g. a war-first house might go
8/2/2; a balanced house might go 4/4/4.) This is a per-house budget, not
drawn from one shared pool — every house gets the same budget to
allocate independently.

### 3d. Set starting Honor/Infamy
Every house starts at **0** Honor/Infamy. Nothing to divide up — the
pool only grows from here via random events during play.

### 3e. Set starting Legend
Every house starts at **0** Legend. Legend is built entirely through
play (dramatic acts, Magic use, surviving calamities) — never allocated
at setup.

### 3f. Set starting Piety
Every house starts at **0** Piety (see `tasks.md`, Active vs. Passive
stats). Built entirely through play (Invoke Faith, Blessings received)
— never allocated at setup, same as Honor/Infamy and Legend. Piety is a
PASSIVE stat — never rolled in a Task action, only checked by events.

### 3g. Set starting Cunning
Every house starts at **3** Cunning (see `tasks.md`) — a small flat
value, not part of the 12-point budget in 3c and not a hard 0 like
Honor/Legend/Piety, so Espionage and Border Raid aren't nearly
impossible before any Cunning has been earned through play.

## 4. Create your House Leader
The player's starting character (House Leader) is generated using the
same **Birth Deal** procedure used for any birth during play — no
special-case rule for the starting leader. The Leader starts at **age 3**
(30-39 years old) — see `birth-death.md` for how age works. The spouse
(step 5) is assumed to start at the same age unless a player wants to
narratively justify otherwise.

1. Roll **10d6** for trait count — count successes on **5-6** (the same
   threshold used everywhere else). Add **automatic hits equal to the
   house's Legend ÷ 5, rounded down** — a house with Legend 12 adds 2
   automatic hits on top of whatever the dice roll. No floor, no cap:
   a Legend-0 house can (rarely) roll as few as 0 traits, and a
   high-Legend house can roll well past what the old card-table's max
   of 7 ever allowed — Legend paying off as a visible dynastic engine
   is the point.
2. Flip that many cards; each rank is a row-lookup on the 13-entry
   mixed character trait table (`tables/character-traits.md` —
   **LOCKED**).
3. An Ace of Spades is always eligible for Magic conversion; if the
   house has the **Magical** house trait, any face card is also
   eligible. Conversion is a player choice.

## 5. Create your Leader's starting family
Every house begins with a **spouse** and **at least 1 child** for the
Leader, in addition to the Leader itself.

- **Spouse:** generated via the same Birth Deal procedure as the Leader
  — no special-case rule, even though they married in rather than being
  born into the house.
- **Child(ren):** every house starts with exactly 1 child, generated via
  Birth Deal, UNLESS the house took the **Fecund** house trait, in which
  case it starts with 1-2 *extra* children instead. Determine the extra
  count with a single card flip: rank Ace-6 → 1 extra child, rank 7-King
  → 2 extra children. Each extra child is then individually generated
  via Birth Deal, same as any other.

## 6. Confirm the throne is vacant
No house starts as King. Nobody knows who the king will be yet.

**But the throne cannot stay empty past Decade 1.** If one or more
houses declare a bid during Decade 1's Scene Declaration (Phase 2), it
resolves normally at Decade 1's Kingdom Scene via the standard
alliance/bloc mechanism — same as any later Revolt, see
`king-and-revolt.md`. But if NO house
volunteers a bid, any player flips one card per house at the start of
Decade 1's Kingdom Scene; **the house with the highest card is forced
to assume the throne** (redraw among tied houses only). The curse doesn't
wait for volunteers — by the end of the first decade, someone wears the
crown. See `turn-order.md`, Phase 4.

## 7. Begin play
Proceed to the first decade's Resolution phase. See `turn-order.md`.

---

## Open items this step surfaced (not yet resolved)
- Doom Clock starting length (likely per-Calamity-module, not universal)
