# Job System

## Core Philosophy

Jobs are the strongest identity layer in the build system.

Changing job should change how the character plays, not only which damage numbers appear.

The long-term vision is approximately **100 jobs**, but this is a design aspiration rather than a launch requirement.

A real implementation should prove the architecture with only a few jobs first.

## Starting State

The player begins **Jobless / Unemployed**.

This acts as an organic tutorial state.

Current candidate:

- reach roughly Job Lv 10 while Jobless before normal job changes become available

The exact threshold is not final.

## Job Hierarchy

Possible structure:

Jobless -> 1st-tier Jobs -> 2nd-tier Jobs -> 3rd-tier Jobs

Alongside this:

- hidden jobs
- hidden branches
- cross-condition jobs
- history-dependent jobs
- status-dependent jobs
- stat-dependent jobs

A hidden job does not need to sit neatly inside the visible tree.

## No Global Character Level

Current design:

**There is no standard global Character Level.**

Progression is primarily job-specific.

Example:

- Knight Job Lv 30
- Mage Job Lv 18
- Assassin Job Lv 7

Changing jobs normally in the same active timeline remembers each job's existing level.

Time-leaping is different: physical progression rewinds to the historical state of that time.

See [TIME_LEAP_SYSTEM.md](TIME_LEAP_SYSTEM.md).

## Job Level and Stat Points

Current direction:

- gaining one Job Lv grants one stat point
- stat allocation belongs to the job's current progression state
- stat allocations can participate in hidden unlock conditions

Example hidden-job condition:

- Mage Job Lv >= 30
- STR >= 15
- INT >= 15
- sword mastery condition satisfied
- special event experienced

Possible result:

**Hidden Job discovered: Magic Swordsman**

Exact stat names and formulas remain open.

## Previous Jobs Do Not Automatically Donate Their Kits

Avoid traditional multi-class accumulation where every old ability remains available after changing jobs.

If the player changes from Knight to Mage:

- the player is now playing Mage
- Knight's full combat kit is not automatically retained

This protects job identity.

Previous-job history can still be used as an unlock condition.

Example:

- Knight Mastery achieved
- Mage Mastery achieved
- specific magical duel completed
- result: Hidden Job — Arcane Knight

Arcane Knight has its own kit.

It is not simply "Knight + Mage with everything equipped."

## Job Mastery

A possible maximum Job Lv is around 50, but this is not final.

Possible milestones:

- Lv 10 -> core mechanic expansion
- Lv 20 -> skill branch
- Lv 30 -> common advanced-job requirement
- Lv 40 -> advanced trait
- Lv 50 -> job mastery

Mastering a job may create a permanent knowledge/history flag even if time is later rewound.

The exact persistence rule must remain consistent with the knowledge-only time-leap model.

## Hidden Jobs

Hidden jobs are a major discovery system.

The UI should not necessarily reveal the total number of jobs.

Avoid fixed completion displays such as:

Jobs Found: 27 / 103

Prefer gradual discovery:

Hidden Job: Blood Moon Knight

- Knight Job Lv 30 — satisfied
- Vampire transformation experienced — satisfied
- ???
- ???

As the player learns more, unknown requirements may become more specific.

## Conditions Behind Conditions

A job condition may depend on another hidden system.

Example:

1. obtain a curse
2. curse reveals a hidden door
3. hidden door leads to a forgotten shrine
4. shrine reveals a new status
5. status enables interaction with a historical echo
6. historical echo unlocks a hidden job

This layered structure is intentional.

## Job Identity Components

A job may define or modify:

- primary action
- secondary action
- dodge
- guard / defensive mechanic
- R2 signature action
- ultimate
- resource system
- active skill pool
- passive traits
- aerial behavior
- charge mechanics
- stat affinity
- HUD
- NPC interaction
- exploration perception
- status interaction

The architecture should reuse modules while allowing distinctive combinations.

## Example Job Families

These are examples only, not canon.

### Warrior Family
- Warrior
- Knight
- Berserker
- Duelist
- Blood Berserker
- Destroyer

### Mage Family
- Mage
- Sage
- Archmage
- healer / sanctuary specialist
- status specialist
- buff / support specialist

### Dark / Death Family
- Necromancer
- soul manipulator
- blood caster
- curse specialist

### Production / Combat Family
- Blacksmith
- Magic Smith
- Master Smith

A production job is allowed to be fully combat-capable.

## Prototype Rule

Do not begin by implementing 100 jobs.

A good first proof may contain only:

- Jobless
- Warrior
- Mage
- Assassin
- one hidden job

The question is:

> **Does changing jobs genuinely change the game feel?**

If the answer is no, adding 95 more jobs will not solve the problem.
