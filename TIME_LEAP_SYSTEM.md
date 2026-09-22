# Time-Leap System

## Core Concept

The protagonist possesses an unusual ability to move through previously experienced time.

This is closer to **time-leaping** than to saving multiple parallel universes.

The player can:

1. experience history
2. return to an earlier point
3. act differently
4. allow or force history to progress again
5. observe a changed future

The system should turn timeline manipulation into gameplay.

## Knowledge Persists, Physical State Does Not

Current decision: **knowledge-only persistence**.

When the player returns to the past, the world and the character's physical/progression state return to what existed at that time.

Examples that rewind:

- Job Lv
- stat allocation
- equipped items
- inventory
- money/resources
- skill mastery
- physical quest state
- NPC life/death
- faction state
- local world state

Examples that may persist as meta-knowledge:

- jobs whose existence has been discovered
- known unlock conditions
- historical outcomes already witnessed
- learned clues
- discovered map secrets as knowledge
- records of contradictory histories experienced

Important distinction:

> Knowing that a hidden job exists does not mean the player physically meets its requirements in the past.

They may need to satisfy those requirements again.

## One Active History, Not Infinite Saved Universes

The system does not need to store a complete copy of every possible worldline.

Conceptually:

0h -> A -> B -> C -> D -> 11h

The player returns to 3h and changes B into X.

0h -> A -> X -> new events -> new 11h state

The old future does not need to remain as a fully playable parallel universe.

Instead retain:

- current active world state
- event/history records required for simulation
- permanent knowledge of important histories the player has experienced

## Temporal Horizon

The player should not freely jump into arbitrary unseen future time.

Current concept:

**The furthest point the player has genuinely reached defines the Temporal Horizon.**

If the player has lived until hour 11:

- they may return anywhere valid between the beginning and hour 11
- if they rewrite hour 3, they may advance again toward hour 11
- history from hour 3 onward is produced under the new conditions

Whether advancing is instantaneous, simulated in steps, or requires anchor points is implementation-dependent.

## Historical Simulation

Do not simulate every NPC movement every second for thousands of hours.

Use layered world simulation.

### Layer 1 — Authored Major Events
Examples:

- king assassinated
- World Tree burns
- city falls
- demon invasion
- religion splits

### Layer 2 — Systemic Faction Events
Examples:

- alliance
- war
- occupation
- leadership change
- trade collapse
- migration

### Layer 3 — Small Generated / Rule-Based Events
Examples:

- merchant relocation
- monster population increase
- local bandit activity
- resource shortage

Long time jumps can resolve these events in event/state space rather than literally running the full simulation frame by frame.

## Time Rewrite Example

Original history:

- Hour 2: Prince disappears
- Hour 4: succession crisis
- Hour 6: civil war
- Hour 9: demon faction invades weakened kingdom
- Hour 11: capital destroyed

Player returns to Hour 1 and prevents the prince's disappearance.

Possible new history:

- Hour 2: Prince survives
- Hour 4: no succession crisis
- Hour 7: kingdom sends army elsewhere
- Hour 9: elves become hostile because of that campaign
- Hour 11: capital survives, forest border burns

The system does not need to pre-author every possible exact timeline.

It needs enough state rules and authored major outcomes to produce meaningful differences.

## Causality Distortion

Repeated or extreme interference with history creates **Causality Distortion**.

This is not intended to be only a punishment meter.

It is new content.

Possible effects:

- enemies that should not exist
- NPCs from incompatible periods
- unstable areas
- overlapping environments
- hidden bosses
- time anomalies
- altered dialogue
- unique loot
- secret jobs

Possible hidden time-related jobs:

- Timewalker
- Causality Mage
- Observer
- Chrono Knight

Names are placeholders.

## Distortion as a Cost

Time travel itself should remain broadly available.

The player should not become permanently unable to reach content because they "used up" timeline edits.

Therefore, rewriting history should preferably create **interesting consequences**, not a limited number of total rewrites.

Possible scale:

- minor local change -> small distortion
- major NPC survival rewrite -> medium distortion
- prevent national collapse -> large distortion
- rewrite world-scale catastrophe -> extreme distortion

Exact values remain undecided.

## Death

Death is integrated with the time system rather than conventional resurrection.

Concept:

- player dies
- time fractures
- player selects or is returned to an earlier valid temporal anchor
- world state rewinds accordingly
- experience/progress earned after the anchor may be lost

Items do not need a separate corpse-drop system because the world itself is rewound.

Possible anchors:

- boss entrance
- region entrance
- settlement
- manually established temporal point

Exact rules remain open.

## Item Paradoxes

The knowledge-only model naturally prevents many duplication paradoxes.

Example:

1. kill NPC
2. take NPC's sword
3. return to time before NPC death

Result:

- NPC is alive
- sword is back in its historical state
- player no longer physically owns the future sword

The player's memory of obtaining it may remain.

## Hidden Job Interaction

Time history itself may become an unlock condition.

Example:

- Experienced: World Tree Destroyed
- Experienced: World Tree Saved
- other hidden conditions
- result: Secret Job condition updated

This allows mutually exclusive historical outcomes to both matter without requiring simultaneous world states.

## The Protagonist's Narrative Role

A fixed main quest is not required, but the protagonist's ability may be an important piece of fixed lore.

The player can be an unusually special existence because they can perceive and manipulate time.

Why the protagonist has this ability remains intentionally unresolved.

See [OPEN_QUESTIONS.md](OPEN_QUESTIONS.md).
