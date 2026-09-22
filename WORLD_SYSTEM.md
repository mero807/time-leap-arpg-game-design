# World System

## Core World Philosophy

The world should feel alive even when the player is not actively solving its problems.

The game should avoid a single mandatory heroic storyline.

Instead, multiple world threads can coexist:

- kingdom politics
- demon conflicts
- elven affairs
- religions
- guilds
- regional disasters
- ancient threats
- time anomalies

The player may participate in any of them, ignore them, or later rewrite their consequences through time-leaping.

---

## Dense Open Regions

The preferred structure is not one enormous seamless open world.

It is a set of dense **Open Regions**.

A long-term target of roughly seven major regions is currently envisioned, though the exact count is not final.

Each region may contain:

- settlements
- dungeons
- hidden routes
- caves and underground spaces
- faction content
- job unlocks
- world-event variants
- historical variants
- bosses
- NPC services
- secret interactions

The guiding idea is:

> **Freedom through what the player can do in a place, not only through how far they can travel.**

---

## Revisiting Old Areas

A region should not become obsolete after first completion.

The same forest may reveal different content depending on:

- current job
- race
- title
- status effect
- faction reputation
- time of day
- current history
- previously discovered knowledge

Examples:

- Mage detects an invisible magical barrier.
- Necromancer speaks to a dead traveler.
- Vampire traces blood.
- Beast-type race smells a hidden route.
- Cursed character sees a sealed shrine.
- A title causes a hidden NPC to reveal themselves.

Revisiting is part of discovery, not filler.

---

## World Threads

A World Thread is an evolving chain of events tied to a faction, place, person, ideology, or disaster.

Examples:

### Royal Thread
- succession issue
- assassination
- civil war
- occupation
- restoration

### Religious Thread
- schism
- heresy investigation
- holy war
- secret cult
- divine anomaly

### Elven Thread
- forest conflict
- World Tree crisis
- border war
- internal faction split

Threads can intersect.

A kingdom's civil war may weaken the border and trigger a demon invasion.

A religious purge may kill an NPC needed for a hidden job.

---

## Event Timing Categories

To avoid constant pressure, not every event progresses the same way.

### Dormant Events
Do not advance until the player discovers or activates them.

### Triggered Progression Events
Begin advancing only after the player becomes involved.

### Major World Events
Can advance independently of the player's attention.

This provides both freedom and a sense of a living world.

---

## Emergent Incidents, Rumors, and Mission Escalation

Not every problem in the world should become a visible quest.

Small incidents should first exist as **world state**, not as UI tasks.

Examples:

- a child fails to return from a forest
- a merchant notices stock disappearing
- travelers report strange lights at night
- two villagers begin fighting over missing money
- hunters stop returning from one route
- a rumor spreads about a witch, monster, cult, or hidden ruin

The player may hear about these through conversation, observation, letters, gossip, witnesses, faction reports, or environmental evidence.

The game should **not automatically respond with a quest banner, objective checklist, map marker, or completion counter**.

The guiding rule is:

> **The event exists because it happened in the world, not because the game wants the player to complete content.**

The player may investigate, ignore it, misunderstand it, arrive too late, or discover that the rumor was false.

Rumors themselves may be:

- accurate
- incomplete
- exaggerated
- outdated
- biased by the speaker
- deliberately false

This makes information gathering part of exploration.

A lightweight Rumor / Observation log may record what the player has actually heard or discovered, but it should avoid converting that information into explicit instructions such as "Go here" or "Kill 0/10."

---

## From Small Incident to Extra Mission

A small incident may grow into a major event.

Conceptual escalation:

1. **Ambient Incident** — something happens in the simulation.
2. **Local Rumor** — people notice and begin talking about it.
3. **Regional Problem** — multiple incidents reveal a larger pattern.
4. **Formal Mission** — a guild, kingdom, faction, or organization recognizes the problem and issues an explicit task.
5. **Extra Mission / Major Event** — the player uncovers a threat whose scale is far beyond the original incident.
6. **World Event** — the situation becomes large enough to affect regions, factions, history, or the wider population.

Example:

- a mother says her son has not returned from the forest
- the player finds abandoned equipment marked with an unknown symbol
- other disappearances are discovered
- rumors point toward a hidden group
- investigation reveals a large ritual or invasion plan
- only then does an **Extra Mission** or major world event become formally recognized

The important point is that the escalation should come from **world state and discovered causality**, not merely from a prewritten quest chain revealing its next step.

Ignoring the first incident does not need to freeze the world.

Depending on its event timing category:

- another NPC may intervene
- another adventurer may solve it
- the missing person may return alone
- the victim may die
- the responsible group may grow stronger
- the incident may disappear without becoming important
- it may later explode into a regional or world-scale crisis

The same type of small incident should therefore be capable of producing different histories.

Formal quest UI is best reserved for situations where the fiction itself justifies a formal mission, such as:

- guild contracts
- military orders
- faction assignments
- explicit requests accepted by the player
- major emergencies
- Extra Missions
- World Events

Because ordinary problems are not constantly labeled as quests, the appearance of an **Extra Mission** or **World Event** notification should feel exceptional and significant.

---

## AI-Driven NPC Society — Long-Term Vision

A long-term direction is for NPCs to behave less like scripted quest terminals and more like inhabitants with persistent internal state.

An important NPC may conceptually maintain:

- temperament and personality
- values and prejudices
- current emotions
- needs and short-term goals
- long-term ambitions
- occupation and schedule
- family and social relationships
- faction loyalty
- personal history
- memories of the player
- memories of other NPCs
- knowledge boundaries: what this NPC knows, suspects, or does not know
- reactions to major historical events

Dialogue should be derived from these states whenever practical rather than being limited to a fixed list of lines.

The desired result is that the same situation may produce different reactions from different characters.

A stranger may react awkwardly when suddenly greeted.

A friend may answer casually.

A hostile NPC may refuse conversation.

A person whose family was harmed by a faction may interpret the player differently from someone who benefited from that faction.

NPCs should also be able to create consequences for one another without waiting for the player.

Examples:

- rumors spread
- friendships form or collapse
- theft creates conflict
- marriages or rivalries alter relationships
- people flee a dangerous area
- merchants relocate
- factions recruit or punish people
- witnesses carry information between settlements

This is a **long-term simulation goal**, not an initial vertical-slice requirement.

A practical implementation should not require every NPC to run expensive full reasoning continuously.

Possible layered simulation:

- lightweight schedule/state simulation for ordinary background life
- event-driven updates when meaningful changes occur
- deeper social reasoning when important NPCs interact
- high-detail reasoning/dialogue when the player directly engages
- summarized simulation for distant populations and regions

This can be treated as a form of **Cognitive Level of Detail**: the world preserves continuity for many inhabitants while expensive reasoning is concentrated where meaningful decisions are occurring.

---

## Natural Player Interaction — Future Interface Direction

The world simulation should be designed so that it does not depend exclusively on menu-based interaction.

Even if the initial game uses conventional controls, world actions should ideally be representable as semantic events such as:

- PlayerGreetedNPC
- PlayerThreatenedNPC
- PlayerTouchedNPCShoulder
- PlayerReturnedLostProperty
- PlayerOverheardRumor
- PlayerInterruptedFight

This leaves room for future input methods such as natural voice conversation, hand tracking, VR, or other embodied controls without redesigning the entire social simulation.

The long-term ideal is:

> **The player expresses intent naturally; the world interprets the action and responds according to its current state.**

## World-State Tags

The world should be data-driven whenever practical.

Examples:

- Kingdom.Destroyed = true
- WorldTree.Burned = true
- ElfFaction.Hostile = true
- ReligionA.LeaderAlive = false
- Region3.Cursed = true

NPCs, bosses, map access, jobs, and dialogue can query these tags.

The goal is to avoid hard-coding every possible combination manually.

---

## Perception as Build Content

Builds should affect exploration.

A job or status may change what the player can perceive.

Examples:

- magic sense
- spirit sight
- blood tracking
- curse detection
- beast scent
- historical echo perception

This turns build choice into more than combat optimization.

---

## Day / Night

A day/night system is desirable but not fully specified.

Possible uses:

- NPC schedules
- hidden merchants
- monster changes
- moon-dependent jobs
- blood-moon events
- different faction patrols
- secret bosses

Exact time scale remains unresolved.

---

## World History Without a Hard Ending

The ambition is for world history to continue beyond a finite authored campaign.

This does not mean infinitely authored bespoke story.

Instead, long-term history can combine:

- handcrafted major events
- rule-based faction transitions
- smaller systemic events

This allows the world to keep changing without requiring an infinite number of manually written quests.

---

## Major Region Ideas

These are placeholders, not final canon:

- Royal Capital Region
- Ancient Forest / Elven Region
- Forge / Industrial Region
- Land of the Dead
- Demon Territory
- Forgotten Time-Distorted Region
- Abyssal Boundary Region

Regions should be defined by culture, conflict, and gameplay as much as by elemental theme.

---

## NPC Permanence and Death

NPCs may die.

NPC death should matter.

Possible consequences:

- services disappear
- successors appear
- inheritance changes
- faction reactions
- ghosts become interactable
- hidden jobs become possible
- future historical paths change

Time-leaping may allow the player to revisit a period before the death.

The active timeline then changes according to the new history.
