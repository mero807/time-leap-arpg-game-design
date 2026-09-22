# Adaptive Boss AI

## Goal

Bosses should not feel like fixed scripts where the player memorizes:

> Attack A always leads to B, then C.

The goal is to create enemies that appear to **learn the player's tendencies** while remaining fair and testable.

This does not require real-time machine learning.

A deterministic or weighted rule system is preferred for production.

---

## Motion Graph

A boss can possess a large library of authored attacks.

Each move has metadata such as:

- valid distance
- valid angle
- target position
- cooldown
- previous-move compatibility
- aggression level
- health phase
- player status
- punish category
- feint capability

The AI chooses among valid moves using weighted scoring.

---

## Player Tendencies to Observe

Possible observations:

- left dodge frequency
- right dodge frequency
- backward dodge frequency
- parry frequency
- average combat distance
- healing timing
- repeated skill use
- tendency to attack after a boss whiff
- aerial combat frequency
- guard reliance

The boss does not need to observe everything.

Different bosses can specialize in reading different habits.

---

## Example Adaptation

Observed pattern:

1. boss attacks
2. player dodges right
3. player uses heavy attack

If this repeats several times, the boss increases the weight of:

- right-side follow-up
- delayed sweep
- fake recovery
- repositioning punish

The player may then realize:

> "It noticed what I was doing."

---

## Branching Combos

Instead of:

A -> B -> C

Use:

- A -> B -> C
- A -> D
- A -> B -> E
- A -> feint -> F
- A -> disengage

The branch depends on current combat state and observed player tendencies.

This makes sequence memorization less dominant.

---

## Feints

Some strong enemies can intentionally interrupt or delay an expected attack.

A feint should still be readable.

The purpose is to punish premature reactions, not to create unavoidable damage.

---

## Fairness Rule

> **Unpredictable is allowed. Unreadable is not.**

The player should not always know what move comes next.

But once the move begins, animation, audio, positioning, or timing should provide enough information to respond.

Avoid unfair input-reading.

The boss should not instantly counter a button press because it secretly knows the input before the animation begins.

---

## Learning Limits

Bosses can have different observation capacity.

Example:

- normal elite -> tracks 1 tendency
- major boss -> tracks 3 tendencies
- hidden boss -> tracks 5
- time-related boss -> tracks many and adapts quickly

This makes intelligence itself part of enemy identity.

---

## Personality

Boss AI can also have personality traits.

Examples:

- aggressive
- cautious
- deceptive
- territorial
- enraged
- patient

Personality changes attack weighting.

A causality-distorted version of a boss might possess a different personality and therefore feel meaningfully different without requiring an entirely new moveset.

---

## Context Reactions

Bosses may also react to:

- player race
- job
- title
- status
- faction reputation
- historical actions

Example:

Race = Elf -> unique dialogue

Race = Elf + Job = Necromancer -> unique dialogue + holy counter move

Title = Kingslayer -> boss becomes cautious or enraged

History = KilledElfKing -> hidden phase

These interactions should be data-driven where possible.

---

## No Generated Animations During Battle

The boss should select from authored and tested animations.

Do not rely on generating brand-new combat motions at runtime.

Dynamic selection is desirable.

Unvalidated runtime animation invention is not.

---

## Testing Requirement

Adaptive AI requires good debugging tools.

Useful tools:

- show current move weights
- show observed player tendencies
- force specific branches
- freeze adaptation
- reset learned tendencies
- log why a move was chosen

Without this visibility, balancing the boss becomes unnecessarily difficult.
