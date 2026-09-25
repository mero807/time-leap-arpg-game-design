# Community Feedback Summary

This document summarizes what the public discussion has taught us so far.

It is not a canon design document by itself.  
For concrete ideas that may become part of the game, see [COMMUNITY_IDEAS.md](COMMUNITY_IDEAS.md).  
For games and stories suggested as references, see [REFERENCES.md](REFERENCES.md).

---

## Why collect community feedback?

The goal is not only to spread the concept.

A major benefit of posting individual mechanics publicly is that other people often:

- compare the idea to games we had not considered
- point out design risks
- turn abstract ideas into concrete gameplay examples
- suggest strange edge cases
- reveal what is easy or hard to understand
- propose systems that fit the project better than the original explanation did

The most useful discussions are often the ones where somebody says:

> "What if it worked like this?"

and the idea becomes more specific.

---

# 1. Time Leap — knowledge survives, physical progression rewinds

The first public discussion produced the most feedback so far.

## Main comparisons people made

Readers compared the idea to:

- roguelikes / roguelites
- save scumming
- Re:Zero
- Outer Wilds
- In Stars and Time
- Twelve Minutes
- Majora's Mask
- Mother of Learning

These comparisons were useful because they clarified what the project needs to communicate.

## What became clearer

The core fantasy is not:

> "Reload until the outcome is perfect."

It is:

> **Learn from one history, return to the past, change it, then discover what the new future became.**

The player should gain power through **knowledge**, not only through permanent stats.

That knowledge can include:

- hidden-job conditions
- enemy weaknesses
- attack patterns
- NPC routines
- ecosystem behavior
- historical outcomes
- hidden locations
- unusual item interactions
- connections between events that were not obvious the first time

## Temporal Awareness

A community suggestion led to the idea that a small number of special entities may remember rewritten timelines.

Ordinary enemies reset normally.

Rare beings such as:

- time-related bosses
- causality anomalies
- entities partly outside normal history

may recognize that the player has fought them before.

Possible effects:

- changed dialogue
- altered attack selection
- counters to tactics used in erased histories
- instability caused by repeated rewinds
- knowledge of events that no longer happened

This became [COMMUNITY_IDEAS.md — 001 Temporal Awareness](COMMUNITY_IDEAS.md).

## Knowledge-Based World Interaction

One particularly useful discussion expanded "knowledge as progression" beyond quests.

Examples suggested by the community:

- carrying meat may attract a creature
- throwing the meat may redirect it instead of starting combat
- a creature may attack only because the player entered its territory
- a parent animal may be aggressive because the player is between it and its young
- defeating or subduing a pack leader may change how the rest behave
- populations may learn to avoid humans

The important lesson:

> **The player should learn how the world works, not just memorize quest answers.**

## Retrospective discovery

Another strong idea was that something meaningless on the first visit can become important later.

Examples:

- a strange tree species is repeatedly found above a rare buried material
- much later, the player realizes those same trees were near the starting area
- an "easy tutorial enemy group" turns out to have been a caravan traveling to a hidden treasure cache
- after rewinding, the player can follow them instead of killing them

The desired feeling is:

> **"Wait... that was there the whole time."**

This became part of [COMMUNITY_IDEAS.md — 002 Knowledge-Based World Interaction & Creature Ecology](COMMUNITY_IDEAS.md).

## Impossible fights and rewritten outcomes

Another suggestion explored fights that appear scripted to be lost.

In one history:

- allies sacrifice themselves
- the player loses an important battle
- the future develops from that failure

After gaining knowledge and returning:

- the player may prepare differently
- an "impossible" fight may become winnable
- the resulting future changes

A useful design clarification came from this:

> There should not necessarily be one perfect "true ending" where everybody survives and every problem is solved.

Saving someone may create a different problem elsewhere.

---

# 2. Causality Distortion — useful posting lesson

The second public post explained the Causality Distortion mechanic in detail.

The post described:

- enemies from erased timelines
- overlapping versions of history
- NPCs remembering impossible events
- hidden bosses created by timeline changes
- distorted-history jobs and abilities
- time-aware bosses
- history changes without one objectively perfect ending

## Community response

The post received views and some votes, but no comments during the initial discussion period.

This was useful feedback about **how to present ideas publicly**.

## Posting lesson

The post explained too much and left too little space for the reader to contribute.

A polished design explanation can make people think:

> "That sounds well thought out."

but not necessarily:

> "I have something to add."

The final question also asked for a fairly abstract judgment:

> Would unpredictable consequences make players afraid to rewrite history?

That requires more effort than a simple creative prompt.

## Better participation pattern

For future posts, prefer questions such as:

> **If rewriting history could create one strange enemy, location, NPC, or event, what would you add?**

General lesson:

> **A good design post and a good discussion prompt are not always the same thing.**

The current posting strategy should intentionally leave room for people to participate.

---

# 3. Hidden Jobs — community participation as design

The third public post asked people directly:

> **If you could add one hidden class to an RPG, what would the class be — and what weird condition would unlock it?**

This was intentionally designed to be easier to answer.

## Recoverable hidden jobs

A commenter liked the concept but disliked the idea of permanently missing a class because of a one-time condition.

That led to a strong design principle:

> **Hidden jobs can be difficult to discover without being permanently missable.**

The Time Leap system provides a natural solution:

1. The player misses an event.
2. Much later, they learn that it mattered.
3. They rewind.
4. They recreate the conditions intentionally.
5. The hidden job becomes obtainable.

The challenge should be discovering and recreating the conditions, not permanently losing content because the player lacked information.

This became [COMMUNITY_IDEAS.md — 003 Recoverable Hidden Jobs](COMMUNITY_IDEAS.md).

## Strange player behavior as a hidden system

Another commenter suggested that the game could quietly observe actions that normally seem pointless.

Examples included:

- repeatedly hitting the same NPC
- sitting in a corner for a long time
- attacking fake targets
- printing absurd numbers of copies
- repeatedly dying in an easy area
- taking unusually long to solve a puzzle
- speedrunner-like behavior
- moving animals into enclosures for no obvious reason
- following a ridiculous suggestion mentioned casually by an NPC

The interesting part is not only the reward.

The **world could acknowledge what the player did**.

Examples:

- NPC reactions
- hidden titles
- altered dialogue
- unusual perks
- hidden jobs
- jokes that persist through the playthrough

This suggests a broader principle:

> **The game should notice player habits that players assume do not matter.**

## Dialogue-skipping behavior

The same discussion suggested jokingly "punishing" players who constantly skip dialogue.

A less frustrating interpretation could be:

- NPCs notice that the player never listens
- NPCs start summarizing information
- the player gains an "Impatient" title
- certain unusual events only occur for chronic skippers
- playstyle itself becomes a hidden condition

This expands hidden conditions beyond combat and quest decisions into **meta-behavior inside the game**.

## Hidden does not mean unknowable

A different commenter raised an important concern:

Small secret rewards can be extremely obscure.

A whole class is much more significant.

If a major class is hidden behind completely arbitrary behavior with no realistic clue, the player may feel that the game expects them to use a wiki.

This leads to another important principle:

> **Hidden ≠ unknowable.**

Large hidden rewards should have discoverable breadcrumbs, such as:

- NPC reactions
- rumors
- environmental clues
- title changes
- partial unlock information
- unusual UI hints
- repeated thematic signals

The goal should be:

> **Connect the clues.**

not:

> **Try every possible random action until something happens.**

## Thematic unlock conditions

A community member gave the example of the Paradox Mage from *Tales of Maj'Eyal 4*.

The interesting part was not merely that the unlock condition was unusual.

The unlock itself matched the theme of the class:

- encounter a future version of yourself
- "lose" in a specific way
- trigger a paradox
- unlock a time-related class

This suggests a strong hidden-job rule:

> **The best strange unlock conditions should feel inevitable in hindsight.**

The player should be able to think:

> **"Of course that is how this class would be born."**

Weirdness alone is not enough.

The condition should express the identity, story, mechanics, or philosophy of the class.

## Other references

Vampire Survivors was also mentioned as a reference for unlocks that encourage experimentation with game systems.

See [REFERENCES.md](REFERENCES.md) for the growing reference list.

---

# Design Principles Emerging From Community Feedback

Several recurring principles are becoming clearer.

## 1. Knowledge is a real progression system

The character may rewind.

The player's understanding should not.

## 2. Time travel must do more than reload

Changing history should create genuinely different states, not simply let the player retry until they get the best result.

## 3. The world should reward observation

The game should support moments where old scenery, NPC behavior, creatures, and events gain new meaning after the player learns more.

## 4. Strange behavior can matter

Player habits that look irrelevant may become part of hidden systems.

## 5. Hidden content should be discoverable

Mystery is good.

Pure randomness is not.

## 6. Important hidden content should generally be recoverable

Time Leap can turn missed opportunities into later discoveries instead of permanent lockouts.

## 7. Hidden unlock conditions should match what they unlock

The condition should help tell the story of the class or mechanic.

## 8. There should not always be one perfect timeline

Different histories should create different tradeoffs, consequences, and possibilities.

---

# Community Posting Lessons

The public posts are also teaching us how to ask better questions.

## What gets responses

Posts are easier to join when readers can answer with:

- one class idea
- one enemy idea
- one strange condition
- one example from another game
- one concern

## What gets fewer responses

Posts may receive fewer comments when they:

- explain nearly every possibility already
- ask only for abstract evaluation
- feel like a finished specification
- leave no obvious space for somebody else's idea

## Current posting approach

Future posts should aim for:

**Design explanation + deliberate creative gap + easy question**

For example:

> "Here is the system. Here are 3 examples. What would you add?"

rather than:

> "Here are 12 examples and my complete solution. Is this good?"

---

# Current Community Workflow

When useful feedback appears:

1. **New mechanic / variation**  
   → preserve it in [COMMUNITY_IDEAS.md](COMMUNITY_IDEAS.md)

2. **Reference game / story / comparison**  
   → add it to [REFERENCES.md](REFERENCES.md)

3. **Strong enough to discuss independently**  
   → create a dedicated GitHub Issue

4. **Fits the main design after discussion**  
   → promote it into the relevant core design document

5. **Interesting but unresolved**  
   → keep it as Exploring or an Open Question

Community ideas are not automatically canon.

The purpose is to preserve good ideas without forcing every suggestion into the design.
