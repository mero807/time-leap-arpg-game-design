# Design Principles

These principles are intended to guide future decisions when individual mechanics conflict.

## 1. Discovery Is a Reward

Not every mechanic should be exposed immediately.

The game should allow the player to discover:

- jobs
- job branches
- skill evolutions
- fusion skills
- hidden stats
- title interactions
- map access
- boss phases
- alternate NPC behavior
- historical conditions

Unknown requirements can appear as `???` and become clearer as the player learns more.

The goal is not obscurity for its own sake.

The goal is to create meaningful "I figured it out" moments.

---

## 2. Knowledge Can Be More Valuable Than Power

Time-leaping rewinds physical progression.

Knowledge does not fully rewind.

Learning that an event exists, that a job can be unlocked, or that a boss reacts to a title may be permanent meta-progression.

The player becomes stronger partly because **they understand the world better**.

---

## 3. The Player Is Special, but the World Is Not Centered on Them

The player possesses a unique relationship with time/history.

That does not mean every political conflict, disaster, religion, or faction exists only to serve the player.

The world should feel like it had history before the player arrived and would continue without them.

---

## 4. No Forced Hero Role

The game should not force morality through a universal "good / evil" meter.

The player may:

- save a city
- ignore it
- destroy it
- join its enemies
- regret the result
- return to the past and create another outcome

Different factions and characters respond according to their own values.

---

## 5. Failure Should Create Content

When possible, failure should alter the world rather than merely produce a "retry" screen.

Examples:

- failed rescue -> death -> spirit interaction
- lost war -> occupation storyline
- NPC death -> inheritance conflict
- boss escapes -> later encounter
- world disaster -> new biome state

Not every failure needs bespoke content, but the philosophy should favor consequences over dead ends.

---

## 6. Old Places Must Gain New Meaning

A map should not become useless after its first clear.

Revisiting should matter because of:

- different jobs
- different races
- different titles
- different statuses
- changed history
- day/night state
- newly discovered knowledge
- new perception abilities

A small dense world that keeps revealing new layers is preferable to a huge empty world.

---

## 7. Job Identity Must Be Felt in the Hands

Changing jobs should not feel like only replacing damage numbers.

A job may change:

- normal attack rhythm
- heavy/secondary action
- dodge behavior
- defensive option
- resource system
- signature action
- ultimate
- aerial combat
- HUD information
- interaction with statuses

Controls should share a common grammar so the game remains learnable.

---

## 8. Strong Builds Are Allowed

Unexpectedly powerful combinations are part of the fantasy.

Balance should not mean "everything produces identical DPS."

Different builds may dominate:

- single-target damage
- area clearing
- defense
- status control
- summons
- mobility
- co-op support
- exploration

The line to watch is not "this is strong."

The line is:

> "This is so universally superior that meaningful choice disappears."

---

## 9. Bosses Should Be Unpredictable but Readable

A boss may change which attack it chooses based on the player.

It should not read inputs unfairly.

The next attack does not need to be predictable.

Once an attack begins, the player should have enough information to react through animation, sound, positioning, or timing.

**Unpredictable does not mean unavoidable.**

---

## 10. Time Travel Must Create Gameplay

Time travel should not be a glorified save/load menu.

It should interact with:

- events
- jobs
- hidden conditions
- NPC survival
- factions
- items
- world states
- causality distortion

Rewriting a major historical event should matter.

---

## 11. Systems Should Combine

Whenever practical, systems should be described in reusable tags/conditions instead of hard-coded one-off combinations.

Conceptual examples:

```
Race = Elf
Job = Necromancer
Status = Cursed
Title = Kingslayer
History = SawWorldTreeBurn
FactionTrust.Kingdom < -50
```

NPCs, bosses, maps, and job unlocks can react to these tags.

This is the technical foundation for emergent combinations.

---

## 12. Build the Smallest Proof First

The full design may be enormous.

Implementation should begin with only enough content to prove the core:

- fast combat
- meaningful job differences
- hidden discovery
- one time rewrite
- one adaptive boss
- one dense area

Do not build 100 jobs before proving four jobs are fun.
---

## 13. World Events Before Quests

Not every interesting event should become a quest.

Small problems, rumors, disappearances, arguments, crimes, discoveries, and strange phenomena should be allowed to exist simply because something happened in the world.

The player should often decide for themselves whether something is worth investigating.

Avoid automatically turning every hint into:

- a quest banner
- an objective checklist
- a map marker
- a completion counter
- an implied obligation to finish content

Formal quest presentation is most appropriate when the fiction itself creates a formal assignment or when an incident has escalated into a major event.

A small incident may organically become an Extra Mission or World Event if the underlying situation grows large enough.

The desired feeling is:

> **"I discovered that this mattered," not "the game told me what content to do next."**

---

## 14. NPCs Should Be Inhabitants, Not Quest Terminals

NPCs should exist for reasons beyond giving the player content.

Whenever practical, characters should have persistent state such as relationships, beliefs, memories, schedules, goals, knowledge, and reactions to history.

Their behavior should be driven by the world they inhabit and what they have experienced, not only by whether the player currently needs a quest.

The player should be capable of forming stories with NPCs through repeated interaction even when no formal quest is involved.

Long-term AI-driven dialogue or social simulation should preserve this principle rather than becoming a procedural replacement for static quest text.

