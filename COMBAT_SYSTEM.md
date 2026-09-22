# Combat System

## Core Combat Rule

> **Trash mobs should feel satisfying to destroy. Strong enemies should become mind games.**

The combat system should support both power fantasy and mechanical mastery.

A well-built character is allowed to erase ordinary enemies quickly.

Elite enemies and bosses should still ask the player to observe, move, defend, and adapt.

---

## Presentation Direction

Preferred camera:

- angled top-down 3D
- readable silhouettes
- clear attack telegraphs
- enough verticality for jumping and aerial attacks
- stylized presentation rather than photorealism

Combat feel is inspired broadly by fast top-down action games such as Hades II.

The goal is to study and reproduce principles of responsiveness such as:

- low input latency
- clean animation timing
- readable hit reactions
- satisfying hit-stop
- impact sound
- knockback
- responsive dodge
- animation cancel rules
- clear VFX hierarchy

The project should not copy proprietary animations, art, UI, or assets.

---

## Controller Grammar

Current candidate layout for a PlayStation-style controller:

| Input | Role |
|---|---|
| Left Stick | Move |
| Right Stick | Camera / aim |
| Square | Primary action / normal attack |
| Triangle | Secondary action / heavy attack |
| Circle | Dodge / evasive action |
| Cross | Jump |
| L2 + Square | Active Skill 1 |
| L2 + Triangle | Active Skill 2 |
| L2 + Circle | Active Skill 3 |
| L2 + Cross | Active Skill 4 |
| R2 | Job / weapon signature action |
| R1 | Ultimate |
| R3 | Lock-on |
| L3 | Sprint or context movement |
| D-Pad | items / shortcuts / utility |

Exact buttons are not final.

The important principle is:

> **Shared input grammar, different job behavior.**

The same button should be understandable across jobs even when the action itself changes.

---

## Primary and Secondary Actions

Avoid treating every job as:

- Square = identical weak attack
- Triangle = identical heavy attack

Instead:

- Square = primary combat action
- Triangle = secondary combat action

Examples:

### Warrior
- Square: fast weapon combo
- Triangle: heavy strike

### Mage
- Square: fast magic projectile
- Triangle: charged spell / alternate casting

### Assassin
- Square: dagger chain
- Triangle: mark / execution setup

This preserves shared controls without making every job feel the same.

---

## Signature Action — R2

R2 is the strongest candidate for the job's defining mechanic.

Examples:

- Knight -> guard / just guard
- Berserker -> armor-through-hit / rage action
- Assassin -> short vanish / shadow step
- Mage -> magic barrier or spell stance
- Archer -> aiming stance
- Necromancer -> summon command
- aerial specialist -> air dash / aerial stance

The player should be able to understand the job's fantasy quickly by using its signature action.

---

## Dodge and Defense

Every job needs a reliable response to danger, but that response does not need to be identical.

Examples:

- generic warrior -> roll
- berserker -> aggressive forward burst
- assassin -> afterimage dash
- mage -> short blink
- beast-type job -> leap
- heavy knight -> short evasive step with guard frames

Some shield jobs may emphasize blocking.

Other jobs may have little or no conventional guard and rely on mobility.

---

## Jump and Aerial Combat

Jumping is a shared system candidate.

All jobs should be able to perform at least a basic aerial action.

Some jobs can strongly specialize in aerial combat.

Possible inputs:

- Jump -> Square
- Jump -> Triangle
- Jump -> R2
- aerial skill use

Example job fantasy:

### Dragoon-like Job
- launcher
- aerial pursuit
- mid-air combo
- air dash
- diving finisher

### Heavy Ground Job
- weak air mobility
- very powerful falling strike
- bonuses while grounded

Verticality can therefore become part of build identity.

---

## Charge Attacks

Charge attacks are not required for every job.

Possible shared input grammar:

- hold Triangle
- hold R2
- hold specific skill input

Examples:

- greatsword -> charged strike
- bow -> charged shot
- mage -> spell channel
- berserker -> charge while consuming Rage
- assassin -> no charge mechanic at all

---

## Active Skills

The current decision is:

**4 active skill slots.**

Suggested controller access:

- L2 + Square
- L2 + Triangle
- L2 + Circle
- L2 + Cross

Skills should generally have some form of limitation.

Possible limitations:

- cooldown
- resource cost
- charges
- conditional availability
- self-inflicted status
- positional requirement

Not every job needs to use the same limitation system.

---

## Ultimate

The ultimate has a dedicated slot separate from the four active skills.

The ultimate should strongly communicate job identity.

Examples:

- Berserker -> Blood Frenzy
- Assassin -> Zero Shadow
- Sage -> Sanctuary
- Necromancer -> Army of the Dead

The exact activation button and charge rules remain open.

---

## Job-Dependent Resources

Avoid forcing every job into one universal stamina/mana system.

Examples:

- Mana
- Rage
- Blood
- Soul
- Focus
- Heat
- Faith
- summon capacity

A different resource model is one of the strongest ways to make jobs feel mechanically distinct.

---

## Combat Feel Test Room

Before building large maps, create a dedicated combat test room.

Minimum contents:

- flat arena
- player
- training dummy
- one weak enemy
- one aggressive enemy
- debug sliders

Useful live-tunable parameters:

- hit-stop duration
- attack startup
- recovery frames
- dodge distance
- invulnerability duration
- movement speed
- knockback
- camera shake
- hit reaction strength
- animation cancel windows
- input buffer duration

The purpose is to reach:

> "Moving and attacking feels good even before there is a real game around it."

---

## Enemy Tempo

### Normal Enemies
Purpose:

- flow
- build expression
- crowd clearing
- satisfying chain reactions
- status and AoE experimentation

### Elite Enemies
Purpose:

- introduce counters
- punish one-dimensional play
- test positioning and defensive timing

### Bosses
Purpose:

- learn the player
- branch attacks dynamically
- use feints
- react to titles, jobs, race, status and history
- create readable but non-scripted pressure

Boss behavior is expanded in [BOSS_AI.md](BOSS_AI.md).
