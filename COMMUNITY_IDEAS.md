# Community Ideas

This file collects interesting ideas, variations, concerns, and suggestions that come from Reddit, GitHub Discussions, Issues, or other public feedback.

These are **not automatically canon**.

The goal is to preserve good outside ideas, let people see how the design evolves, and give each promising suggestion a place where others can react or build on it.

## Status

- **New** — worth preserving, but not evaluated yet
- **Exploring** — actively worth discussing or testing
- **Adopted** — accepted into the main design direction
- **Partially adopted** — part of the idea was accepted
- **Not adopted** — interesting, but does not currently fit
- **Open question** — unresolved and intentionally left for discussion

---

## 001 — Temporal Awareness

**Status:** Exploring  
**Source:** Reddit feedback on the Time Leap concept  
**Discussion:** https://github.com/mero807/time-leap-arpg-game-design/issues/9

### Original suggestion

What if enemies or bosses could somehow notice that the player has rewound time and become stronger or better prepared after repeated rewinds?

### Current interpretation

Ordinary enemies should **not** remember timeline rewrites.

However, a small number of special entities may retain partial awareness across rewritten histories:

- time-related bosses
- beings created or changed by Causality Distortion
- anomalous entities that exist partly outside normal causality
- exceptionally important characters with a lore reason to perceive timeline changes

Possible reactions include:

- different dialogue after a rewind
- recognizing tactics used in a previous history
- altered attack selection
- preparing counters to repeated player habits
- becoming more unstable after repeated timeline changes
- revealing knowledge that should be impossible in the current history

### Why it is interesting

This connects three existing systems:

**Time Leap × Causality Distortion × Adaptive Boss AI**

It could make certain encounters feel genuinely unsettling: the player expects the world to forget, then discovers that something remembered.

### Design caution

Temporal awareness should remain rare.

If every enemy remembers every rewind, the player's signature ability may begin to feel like a punishment system instead of a source of discovery.

### Open questions

- Should these entities remember every rewritten timeline, or only fragments?
- Can the player discover why they remember?
- Should awareness ever persist across the entire game?
- Can a boss exploit information from a future that technically no longer exists?
- Should repeated rewrites unlock entirely new boss phases or encounters?

---

## 002 — Knowledge-Based World Interaction & Creature Ecology

**Status:** Exploring  
**Source:** Reddit feedback on knowledge as progression

### Original suggestion

Knowledge progression could go beyond remembering quest answers or unlock conditions.

The player might learn how enemies, animals, monsters, and ecosystems actually behave — and use that understanding in later timelines.

Examples from the community feedback included:

- learning enemy weaknesses and attack patterns
- noticing visual or posture cues that reveal an upcoming attack
- discovering that carrying certain food attracts a creature
- throwing that food to redirect the creature instead of fighting it
- finding unexpected interactions between ordinary items and specific monsters
- understanding territorial behavior
- realizing that a parent creature is aggressive only because the player is between it and its young
- learning pack hierarchy and using it to influence the rest of the group
- populations gradually learning to avoid humans in a region

### Current interpretation

The player's persistent knowledge should not only answer:

**"What unlocks this hidden job?"**

It should also answer:

**"How does this world actually work?"**

After seeing one possible future, the player may return to the past knowing:

- how a creature hunts
- what scares or attracts it
- what environmental conditions change its behavior
- which attack animation reveals its next move
- how an ecosystem or population reacts to human interference
- how to resolve an encounter without combat
- which seemingly useless item has an unexpected use against a particular enemy

This turns knowledge itself into a form of player power even when character stats, equipment, and progression rewind.

### Retrospective Realization

A particularly strong variation from the Reddit discussion is that **ordinary-looking things can gain new meaning after the player learns more about the world**.

Examples:

- A strange species of tree is often seen growing over a certain alien metal. Much later, the player realizes the same trees were clustered near the starting area — implying that valuable material may have been buried there from the beginning.
- A group of supposedly easy enemies encountered early in the game appears to be a simple combat tutorial. In a later timeline, the player realizes they were actually a caravan traveling to retrieve a hidden treasure cache. After rewinding, the player can choose not to attack and instead follow them.
- Background scenery, enemy placement, animal behavior, item descriptions, or NPC routines can all become clues whose importance is only understood much later.

The goal is to create moments where the player thinks:

> **"Wait... that was there the whole time."**

This makes revisiting the past rewarding even when the player is not choosing a different dialogue option or repeating a quest. The same world can become richer because the player's interpretation of it has changed.

### Why it is interesting

This creates a strong connection between:

**Time Leap × Knowledge Progression × Exploration × Creature AI**

A future timeline can teach the player something about the world that becomes useful in an earlier timeline.

The important distinction is that the character does not permanently gain a numerical bonus — **the player becomes more capable because they understand more.**

It also gives time travel meaningful uses outside quests and major historical decisions.

For example:

1. The player encounters an apparently unavoidable monster in one timeline.
2. Much later, they discover that the species follows territorial or feeding rules.
3. They rewind.
4. This time they manipulate the environment, redirect the creature, or avoid the fight entirely.
5. The altered encounter may produce a different downstream history.

### Design caution

The behavior needs to be understandable enough that players can genuinely learn it.

If creature behavior is too random or every interaction requires obscure trial-and-error, "knowledge as progression" may feel like guessing rather than mastery.

Likewise, not every creature needs a complex simulation. A smaller set of readable behavioral rules could create the illusion of a much richer ecosystem.

### Open questions

- Which creature behaviors should be systemic, and which should be authored?
- How clearly should the game communicate behavioral clues?
- Can creature populations change behavior across history?
- Can knowledge from a future ecosystem still be reliable after the player changes the past?
- Should some hidden jobs or skills require understanding a creature instead of defeating it?
- Can non-combat solutions create unique historical branches?
- How much of this knowledge should be recorded in-game versus remembered by the player?

---

## 003 — Recoverable Hidden Jobs

**Status:** Exploring  
**Source:** Reddit feedback on hidden-job unlock conditions

### Original concern

A player liked the hidden-class concept but worried about missing jobs because of **one-time unlock conditions**.

That concern is especially important for a game built around obscure, cross-system requirements.

### Current interpretation

Hidden jobs can be difficult to discover without being permanently missable.

The preferred design direction is:

> **The challenge should be discovering and recreating the conditions — not permanently losing access because the player made one uninformed choice many hours earlier.**

The Time Leap system gives this idea a natural solution.

For example:

1. The player passes an event without knowing it is relevant.
2. Much later, they discover clues that reveal a hidden job and its unusual requirements.
3. They return to an earlier point in history.
4. They intentionally recreate the necessary conditions.
5. The hidden job becomes obtainable in the rewritten timeline.

This allows one-time historical events to matter without turning them into permanent lockouts.

### Why it is interesting

This connects:

**Hidden Jobs × Knowledge Progression × Time Leap**

A missed opportunity becomes a reason to understand the past better rather than a reason to reload an old save or consult a wiki before every decision.

It also supports the fantasy that **knowledge gained in one history makes previously invisible possibilities accessible in another.**

### Design caution

Recoverable does not need to mean easy.

Some hidden jobs may require:

- reaching the correct historical window
- recreating several unusual conditions at once
- changing an earlier event first
- preserving or preventing a specific NPC, faction, curse, title, or world state
- combining knowledge gathered across multiple timelines

However, the game should avoid permanently locking a player out of a job solely because they did not already know that an obscure one-time event mattered.

### Open questions

- Should every hidden job be recoverable through time travel?
- Are there any cases where permanent loss would genuinely improve the design?
- How much information should the player receive after discovering that a job exists?
- Should clues point to the historical period where the unlock became possible?
- Can changing history make one hidden job available while making another temporarily unreachable?
- Should some jobs require information gathered from multiple incompatible futures?

---

## How new ideas get added

Interesting community feedback can be preserved here even when it is not accepted into the main design.

For promising ideas, a dedicated GitHub Issue can be opened so people can:

- leave a 👍 reaction
- suggest variations
- point out problems
- connect the idea to other systems

If an idea is later adopted, the relevant main design document can be updated separately.

The repository remains open design: outside ideas are welcome, but there is no expectation that every suggestion becomes part of the concept.
