# Time-Leap Dark Fantasy ARPG — Open Game Design

> **A freely reusable game-design concept for a dark-fantasy action RPG where the player can leap through time, rewrite history, discover hidden jobs, and build a character through an intentionally huge web of systems.**

**Status:** Game-design concept / living design document.  
**Implementation:** Not included yet. No finished game is promised.  
**License:** The design documents in this repository are released under **CC0 1.0 Universal**. You may use, remix, modify, translate, fork, or implement any part of them without asking permission or giving attribution.

---

## 日本語概要

これは、個人の趣味として考え始めた**斜め見下ろし3D・ダークファンタジーARPG**の公開ゲームデザインです。

中心となる発想は次の通りです。

- プレイヤーは世界の**時間を跳躍**できる。
- 過去を変えると、その地点以降の歴史が変化する。
- 時間を戻したときに持ち越せるのは基本的に**知識・発見・解放情報**であり、装備・所持品・Job Lv・ステータスなどは当時の状態へ戻る。
- キャラクターレベルは持たず、**Job Lv**を成長の中心にする。
- 1次職 → 2次職 → 3次職に加えて、多数の**隠し職業**を用意する構想。
- スキル、ステータス配分、状態異常、世界の歴史、称号などが隠し条件に影響する。
- 雑魚戦は爽快に、強敵・ボスは読み合い重視。
- ボスは固定コンボだけでなく、プレイヤーの行動傾向を観測して攻撃候補の重みを変える。
- 一本道の「メインストーリー」は置かず、王国・宗教・魔族・エルフなど複数の出来事が世界側で進行する。
- 同じ地域でも職業・種族・状態・歴史によって新しい秘密が見つかる。
- 通常世界はソロ前提。将来的なオンライン要素は「深淵」など独立領域での1〜4人Co-opを候補とする。

このリポジトリの目的は「作者が必ず完成させること」ではありません。

**この考え方が誰かに刺さったなら、好きに料理してください。**

一部分だけ自分の作品へ持っていくのも、全体を再解釈するのも、別ジャンルへ変えるのも自由です。

---

## The Core Fantasy

The world does **not** wait for the player.

Kingdoms struggle, factions conspire, people live and die, hidden events unfold, and history moves forward whether the player intervenes or not.

The player, however, possesses one extraordinary ability:

**they can move through previously experienced time and change what happened.**

They can witness a kingdom collapse, return to the past, prevent the collapse, then jump forward again and see what kind of future grew from the new history.

The player remembers what they learned across those histories even when their physical state rewinds.

Knowledge becomes progression.

---

## Core Design Pillars

### 1. Freedom without a forced heroic main quest
There may be wars, conspiracies, religious conflicts, disasters, and world-changing events, but the player is not obligated to become the world's chosen hero.

Help a kingdom. Ignore it. Betray it. Destroy it. Save it later.

### 2. Discovery as progression
Jobs, skills, maps, bosses, interactions, and world states can be hidden behind unusual combinations of conditions.

The game should constantly create the feeling:

> "Wait... that was possible?"

### 3. Time-leaping as a playable system, not a simple undo button
Changing history should create new consequences, new events, and **Causality Distortion** rather than merely restoring a previous save.

### 4. Huge build diversity through combinable systems
Race × Job × Weapon × Skills × Stats × Status Effects × Equipment × History × Titles.

The goal is not to manually author every build, but to create systems that produce unexpected combinations.

### 5. Fast, satisfying combat
Combat feel takes inspiration from fast top-down action games such as **Hades II** and similar action roguelites, while job/weapon identity takes inspiration from games where different combat styles substantially change controls.

The goal is **inspiration, not imitation**.

### 6. Trash mobs are satisfying; strong enemies are mind games
Normal enemies let powerful builds feel powerful.

Elite enemies and bosses require observation, movement, defensive timing, and adaptation.

### 7. Old areas should stay relevant
A forest visited at hour 2 may reveal entirely different content at hour 40 because the player now has a different job, status, history, title, or perception ability.

---

## Long-Term Vision

The intentionally ambitious version of the concept may eventually contain:

- ~100 jobs as a long-term design target
- 1st / 2nd / 3rd-tier job progression
- hidden jobs and hidden job trees
- skill mastery, evolution, and fusion
- hidden stats
- dense open regions rather than a giant empty seamless world
- autonomous faction/world-history progression
- title-based NPC and boss reactions
- adaptive boss behavior
- time-leaping and causality distortion
- a build-testing facility
- an optional 1–4 player Abyss/Deep Realm mode

**These are a vision, not a scope promise.**

A real implementation should begin with a very small vertical slice and prove that the core systems are fun before scaling up.

---


---

## Join the Discussion

You do **not** need to be a game developer to participate.

If you simply think "I would play this", "this sounds annoying", or "what if it worked like this instead?", that is useful feedback.

👉 **[Open GitHub Discussions](https://github.com/mero807/time-leap-arpg-game-design/discussions)**

Use Discussions for casual reactions, questions, polls, and new ideas.

### React to Individual Mechanics

If you want to react to one specific mechanic, each major concept also has its own lightweight thread. A 👍 is enough.

- [**Time Leap — knowledge survives, power rewinds**](https://github.com/mero807/time-leap-arpg-game-design/issues/1)
- [**Hidden Jobs — discover classes through strange cross-system conditions**](https://github.com/mero807/time-leap-arpg-game-design/issues/2)
- [**Causality Distortion — rewriting history creates new anomalies instead of a simple penalty**](https://github.com/mero807/time-leap-arpg-game-design/issues/3)
- [**Adaptive Bosses — bosses notice habits and change attack selection**](https://github.com/mero807/time-leap-arpg-game-design/issues/4)
- [**Living World — factions and events keep moving without a mandatory main quest**](https://github.com/mero807/time-leap-arpg-game-design/issues/5)
- [**Buildcraft — jobs, skills, stats, statuses, history and titles combine into unexpected builds**](https://github.com/mero807/time-leap-arpg-game-design/issues/6)

See [COMMUNITY.md](COMMUNITY.md) for the full community guide, [COMMUNITY_IDEAS.md](COMMUNITY_IDEAS.md) for ideas that came from Reddit/GitHub feedback, and [SHAREABLE_POSTS.md](SHAREABLE_POSTS.md) for short versions that can be reposted elsewhere.


## Repository Map

- [GAME_CONCEPT.md](GAME_CONCEPT.md) — overall game concept and player fantasy
- [DESIGN_PRINCIPLES.md](DESIGN_PRINCIPLES.md) — rules that guide future design decisions
- [COMBAT_SYSTEM.md](COMBAT_SYSTEM.md) — combat controls, feel, aerial combat, skills and ultimates
- [JOB_SYSTEM.md](JOB_SYSTEM.md) — job progression and hidden-job philosophy
- [SKILL_SYSTEM.md](SKILL_SYSTEM.md) — active skills, mastery, evolution and fusion
- [TIME_LEAP_SYSTEM.md](TIME_LEAP_SYSTEM.md) — time travel, timeline rewriting and causality distortion
- [WORLD_SYSTEM.md](WORLD_SYSTEM.md) — regions, world threads and autonomous events
- [CHARACTER_GROWTH.md](CHARACTER_GROWTH.md) — Job Lv, stats and hidden stats
- [FACTION_REPUTATION.md](FACTION_REPUTATION.md) — Trust/Fear reputation and titles
- [BOSS_AI.md](BOSS_AI.md) — adaptive boss behavior
- [ABYSS_COOP.md](ABYSS_COOP.md) — optional endgame/co-op concept
- [CRAFTING_SYSTEM.md](CRAFTING_SYSTEM.md) — crafting and combat-capable production jobs
- [OPEN_QUESTIONS.md](OPEN_QUESTIONS.md) — unresolved design questions
- [IDEA_LOG.md](IDEA_LOG.md) — experimental ideas that are not canon
- [COMMUNITY_IDEAS.md](COMMUNITY_IDEAS.md) — promising ideas and variations suggested through public feedback
- [CONTRIBUTING.md](CONTRIBUTING.md) — how to use or extend this repository

---

## Reference Direction

The project draws broad inspiration from the **feel or design philosophy** of games such as:

- Hades II — fast isometric action and combat readability
- Cinderia — build variety and stylized character presentation
- Ruby Knight — dark-fantasy mood / top-down presentation
- Monster Hunter — weapon-style identity and readable enemy combat
- Skyrim — freedom to ignore the "intended" path and simply exist in the world

No affiliation is implied, and this repository does **not** attempt to reproduce proprietary characters, assets, story, code, animations, UI, or other protected expression.

---

## Use This However You Want

Fork it.

Take one mechanic.

Turn it into a 2D game.

Turn it into a 3D game.

Make a tiny game about only the time system.

Use the hidden-job idea in something unrelated.

Ignore everything except the boss AI concept.

**You do not need permission.**

See [LICENSE](LICENSE) for the CC0 dedication.
