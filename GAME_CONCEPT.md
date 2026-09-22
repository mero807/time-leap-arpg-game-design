# Game Concept

## One-Sentence Pitch

A dark-fantasy, angled top-down 3D action RPG where the world advances independently, the player discovers an enormous web of jobs and hidden systems, and a unique time-leaping ability allows previously experienced history to be rewritten.

## 日本語要約

プレイヤーに一本のメインストーリーを押し付けず、世界側に複数の歴史・事件・勢力争いを存在させる。  
プレイヤーは好きな出来事だけに関わり、必要なら過去へ戻って別の選択をし、到達済みの未来まで再び時間を進められる。

「何をするか」だけでなく、「何者になるか」「何を発見したか」「どんな歴史を経験したか」がゲームプレイを変える。

---

## Intended Genre

- Action RPG
- Dark fantasy
- Angled top-down / isometric-like 3D presentation
- Exploration and discovery driven
- Persistent-character structure
- Buildcraft-heavy
- Primarily single-player
- Optional co-op isolated from the main mutable world

This is **not** intended to be a run-based timed roguelite where the player must rush through a fixed loop before a timer expires.

The player should be allowed to stop, explore, experiment, revisit, and live in the world.

---

## Player Fantasy

The player begins as an ordinary, jobless person in a world that does not revolve around them.

Over time they may become:

- a knight
- a necromancer
- an assassin
- a blacksmith who fights with self-made weapons
- a feared criminal
- a hero trusted by a kingdom
- a monster-like figure feared by everyone
- a hidden time-related job that only exists because multiple contradictory histories were experienced

The central fantasy is:

> **"I discovered something the world did not explicitly tell me was possible."**

---

## No Mandatory Main Story

The world contains stories.

It does not need a single mandatory "main story."

Instead, the game can contain multiple **World Threads**:

- royal politics
- religious conflicts
- demon politics
- elven conflicts
- guild struggles
- ancient disasters
- regional crises
- time anomalies

Each thread can progress independently.

The player may enter, ignore, interrupt, destroy, support, or later rewrite these histories.

A royal succession crisis might resolve without the player's involvement.

The consequences then become part of the current world.

---

## The World Does Not Wait

Some events remain dormant until discovered.

Some start progressing once the player becomes involved.

A limited number of major world events may progress regardless of player involvement.

This avoids turning the entire game into constant deadline anxiety while preserving the feeling that the world is alive.

Suggested event categories:

1. **Dormant Events** — frozen until interaction.
2. **Triggered Progression Events** — time begins after discovery or activation.
3. **Major World Events** — may advance independently.

Failure is not automatically a reload condition.

A child not rescued in time may die.

That can create:

- a ghost interaction for necromancers
- a curse investigation
- a different family storyline
- a future time-rewrite opportunity
- a hidden-job condition

Failure should generate content whenever possible.

---

## Time as a Core Player Tool

The player can travel backward within the period of history they have already experienced.

Changing an earlier event changes the active future.

The player can then move forward again toward their furthest previously reached point in time.

The game does not need to keep an unlimited number of complete parallel universes.

Instead, it can maintain:

- one active world history
- event/state history
- permanent player knowledge of histories already experienced

This distinction is explored in [TIME_LEAP_SYSTEM.md](TIME_LEAP_SYSTEM.md).

---

## Build Identity

The main build axes are currently:

- Race
- Job
- Weapon
- Active Skills
- Ultimate
- Stats
- Status Effects
- Equipment
- Summons
- Titles
- Historical experience

Not every axis must have equal weight.

The job should remain the strongest identity anchor.

Previous jobs do not automatically donate all their abilities to the current job.

---

## Long-Term Job Vision

A long-term target of approximately 100 jobs is intentionally ambitious.

The structure may include:

- Unemployed / Jobless start
- 1st-tier jobs
- 2nd-tier jobs
- 3rd-tier jobs
- hidden jobs
- hidden branches
- jobs unlocked through bizarre cross-system conditions

The number 100 is a **vision target**, not an initial implementation requirement.

A real project should prove the system with only a few jobs first.

---

## Combat Identity

The basic combat philosophy is:

> **Trash mobs: power fantasy and flow.  
> Strong enemies: observation and mind games.**

A build should be allowed to annihilate ordinary enemies when it is well constructed.

Bosses should still demand player interaction.

A strong build should help, but not completely replace movement, reading, defense, timing, or adaptation.

---

## World Structure

The preferred world is not a giant seamless map.

It is a set of **dense open regions**.

A long-term target might be around seven major regions, each containing:

- settlements
- dungeons
- hidden routes
- bosses
- profession/job interactions
- faction content
- historical variants
- secrets that require later abilities or knowledge

The design goal is:

> **Freedom through what you can do in a place, not merely through how far you can walk.**

---

## Replayability Philosophy

Replayability should not depend only on:

- bigger numbers
- infinite loot rarity
- repeating the same dungeon
- endless seasonal content

Instead, it should come from:

- hidden jobs
- alternate histories
- unusual stat distributions
- skill fusion
- status-dependent interactions
- title reactions
- job-specific perception
- adaptive bosses
- secrets in old areas
- contradictory history requirements

The player should be able to spend hundreds of hours and still have the possibility of discovering something new.

---

## Online Philosophy

The core game should remain fully functional when the online population is zero.

A full MMORPG is outside the current concept.

If multiplayer exists, the strongest current direction is:

- main mutable world = solo
- Abyss / Deep Realm = isolated 1–4 player co-op

This avoids the need to synchronize every player's completely different world history.

---

## Production Reality

The full vision is extremely large.

The correct implementation strategy is not to build 100 jobs first.

A sensible vertical slice would contain roughly:

- one small region
- 3–4 jobs
- a handful of enemies
- one adaptive boss
- one hidden job
- one meaningful time-rewrite event
- basic stat progression
- four active skill slots + ultimate

If that slice is not fun, scaling the content will not fix it.

If it is fun, the design can grow.
