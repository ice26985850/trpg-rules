# SAO_TRPG GM Rulebook

> SAO TRPG (Sword Art Online adaptation) — This document is compiled from the chapters of the rulebook; its content is consistent with the original chapters.

## Chapter 6: GM Guide

> *"GM, you are the Kayaba Akihiko of this world. You create the rules, you design the challenges, you control life and death. But you must also remember — your goal is not to kill the players, but to let them experience a true adventure."*

---

## 6.1 Core Principles of the GM

### 6.1.1 Death Tension vs. Fairness

The core tension of SAO TRPG comes from **Permanent Death**. But the GM must learn to balance:

| What You Should Do | What You Should Not Do |
|--------------------|------------------------|
| Let players feel that danger is real | Design unavoidable death traps |
| Provide ample information-gathering opportunities before a Boss fight | Hide the Boss's lethal skills until they are used |
| Offer a window to use escape means (Teleport Crystal) | Launch an instant-kill attack right after a player has just used a Sword Skill and is in Recovery Lag |
| Make death a meaningful story turning point | Kill characters with unexpected random encounters |
| Provide a beginner protection period for new players (Lv.1-5) | Show the game's cruelty during the tutorial phase |

### 6.1.2 Shaping the SAO Atmosphere

The unique atmosphere of SAO comes from the following elements:

1. **This is indeed a game** — with UI prompts, skill effects, drop screens, and level displays
2. **But it is not a game** — you can feel pain, fatigue, fear, hunger, and death
3. **The interweaving of the everyday and the extraordinary** — clearing the Frontline and fishing by the lakeside are equally important
4. **The player community** — there are thousands of real "Players" in the towns, each with their own story
5. **The passage of time** — being trapped for two years is not a single dungeon expedition, but another kind of life

It is recommended that the GM intersperse "daily life scenes" between chapters:
- Character dialogue while resting at an inn
- Treasure-hunting at the player market
- Trying newly discovered cuisine
- Receiving distress letters from other players

---

## 6.2 Encounter Design

### 6.2.1 Standard Monster Template

Use the following template to quickly create monsters:

```
═══════════════════════════════
  Monster: [Name]
═══════════════════════════════

Level: [___]  Type: [Normal/Elite/Rare/Boss]
Area: [Floor/Area]

HP: [___]  SP: [___]
ATK: [___]  DEF: [___]
HIT: [___]  EVA: [___]
SPD: [___]

Attack Patterns:
  1. [Name]: HIT[±___], Damage Multiplier×[.__], [Effect]
  2. [Name]: HIT[±___], Damage Multiplier×[.__], [Effect]

Special Abilities:
  - [_____________]
  - [_____________]

Drops:
  Col: [___] Col
  Materials: [_____________] ([Chance]%)
  Equipment: [_____________] ([Chance]%)

Description: [_____________]
═══════════════════════════════
```

### 6.2.2 Monster Stat Reference Table

| Monster Level | HP | ATK | DEF | HIT | EVA | EXP (Normal) | EXP (Elite) |
|---------------|----|-----|-----|-----|-----|--------------|-------------|
| Lv.5 | 80 | 12 | 8 | 30 | 20 | 75 | 200 |
| Lv.10 | 160 | 18 | 14 | 35 | 25 | 150 | 400 |
| Lv.20 | 300 | 28 | 22 | 40 | 30 | 300 | 800 |
| Lv.30 | 500 | 40 | 32 | 45 | 35 | 450 | 1,200 |
| Lv.40 | 750 | 55 | 42 | 50 | 38 | 600 | 1,600 |
| Lv.50 | 1000 | 70 | 55 | 55 | 40 | 750 | 2,000 |
| Lv.60 | 1400 | 90 | 68 | 60 | 45 | 900 | 2,400 |
| Lv.70 | 2000 | 110 | 80 | 65 | 48 | 1,050 | 2,800 |
| Lv.80 | 3000 | 135 | 95 | 70 | 50 | 1,200 | 3,200 |
| Lv.90 | 5000 | 165 | 110 | 75 | 55 | 1,350 | 3,600 |
| Lv.100 | 10000 | 200 | 130 | 80 | 60 | 1,500 | 4,000 |

### 6.2.3 Elite Monsters (×1.5~2×)

Multiply the above values by ×1.5~2, and add 1–2 special skills.

### 6.2.4 Boss Stat Design

| | Minor Boss | Mid Boss | Major Boss | Floor Boss |
|-----------|-----------|----------|------------|------------|
| HP Multiplier | ×5 | ×10 | ×20 | ×30-50 |
| ATK/DEF | ×1.3 | ×1.5 | ×1.8 | ×2.0 |
| Phases | 1 | 2 | 2-3 | 3 |
| Special Skills | 1 | 2 | 3-4 | 4-6 |
| Recommended Party | 4 players | 4-6 players | 8-12 players | 12-24+ players |

### 6.2.5 Encounter Difficulty and Reward Balance

A standard party (4 players) should earn the following in one game chapter:

| Chapter Type | Battles | Total EXP (per player) | Total Col (per player) | Equipment Drops |
|--------------|---------|------------------------|------------------------|-----------------|
| Short Chapter (1 session) | 2-3 | 150-400 | 200-600 | 0-1 piece |
| Mid Chapter (2-3 sessions) | 4-6 | 600-1,500 | 800-2,500 | 1-2 pieces |
| Boss Chapter | 1-2 | 1,500-4,000 | 1,500-5,000 | 1 Rare piece per player |

---

## 6.3 Boss Design In-Depth

### 6.3.1 Floor Boss Design Principles

1. **Thematic Consistency** — The Boss's appearance and skills should match the Floor's theme
2. **Sense of Phases** — At least 2 phases, so the battle has ups and downs
3. **Clearerability** — There must be a weakness or pattern for players to exploit
4. **Sense of Epic** — Descriptions should be grand, and HP depletion should have visual changes
5. **Survival Pressure** — but not unbeatable

### 6.3.2 Floor Boss Design Example

```
═══════════════════════════════
  Boss: Vulcan the Iron Guardian
═══════════════════════════════

Floor 15 Floor Boss | Lv.18 | Type: Mechanical Giant
Recommended Clear: Lv.15-18, 8-12 players

[Base Attributes]
HP: 2400 / 2400     SP: 200 / 200
ATK: 35    DEF: 40
HIT: 45    EVA: 20
SPD: 30

[Phase 1: 100%-61%]
Description: Vulcan moves slowly, the giant gears on both arms rotating slowly

Skills:
  1. Crush Strike: ATK×1.5, single target, HIT-5
  2. Gear Blade: ATK×1.3, 3 frontal targets, HIT+0
  3. Earthshaker Wave: ATK×1.0, all targets, AGI check or Prone

[Phase 2: 60%-31%]
Description: Vulcan's armor opens up, revealing its internal high-temperature core

Skills:
  1. Overload Strike: ATK×2.0, single target, HIT+5
  2. Flame Spray: ATK×1.5, frontal cone, applies Burning
  3. Super Earthshaker Wave: ATK×1.3, all targets, always Prone
  4. Self-Repair: restores 200 HP (usable 2 times)

[Phase 3: 30%-0%]
Description: Vulcan enters berserk mode, its whole body glowing red-hot, movement speed sharply increases

Skills:
  1. Berserk Combo: ATK×2.5, 4-hit combo, random targets
  2. Meltdown Beam: ATK×3.0, line piercing, HIT+15
  3. Self-Destruction Countdown: explodes after 3 turns, ATK×10 to all

[Weaknesses]
- Ice-attribute weapon damage ×1.5
- Back attack HIT+15 (core exposed)
- After leg destruction SPD-20 (requires accumulating 100 damage to the legs)

[Drops]
LA Reward: Vulcan's Heart (Rare reinforcement stone, can enhance a weapon to +7)
Fixed Drop: Steel Gear × 5 (Rare forging material)
Random Drop: Guardian Shield (DEF+18, block success rate +15%), 50% chance
```

---

## 6.4 Adventure Structure Design

### 6.4.1 Typical Adventure Framework

```
═══════════════════════════════
  Adventure: [Title]
═══════════════════════════════

[Prologue] Receive a quest / hear a rumor in town

[Chapter 1: Information Gathering]
- Ask NPCs for information
- Collect maps, learn monster weaknesses
- Prepare supplies

[Chapter 2: Field Exploration]
- Journey to the maze entrance
- 1-3 field encounters

[Chapter 3: Maze Clearing]
- Explore the maze to find the Boss room
- Traps / mechanisms
- 3-5 maze encounters
- May find a safe room (rest point)

[Chapter 4: Boss Battle]
- Boss battle
- Victory → Chapter 5
- Retreat → requires re-clearing the maze

[Chapter 5: Return and Settlement]
- Return to town
- Sell spoils
- Roleplay scenes
- Unlock new Floor teleport gate
- Distribute EXP and Col

[Interlude]
- Daily life scenes
- Guild activities
- Personal story
```

### 6.4.2 Pacing Control

| Sessions | Content Plan |
|----------|--------------|
| 1st | Information gathering + departure + 1-2 field battles |
| 2nd | Maze exploration + 2-3 battles + discover Boss room |
| 3rd | Boss strategy meeting + Boss battle + settlement |

---

## 6.5 Special Scenario Handling

### 6.5.1 Orange Players (Criminal Players)

In SAO, attacking other players turns one's marker orange (Orange Player).

**TRPG Handling**:
- Orange Players cannot enter the Safe Zone of towns
- NPC shops refuse transactions
- Other players may attack Orange Players without turning orange
- The Orange state lasts 72 hours (in-game time), after which it can be cleared through a quest

**Green Players**:
- Players who defeat Orange Players sometimes turn green-marked
- Social standing increases, some shops offer discounts

### 6.5.2 Red Players (PK Guilds)

For example, "Laughing Coffin" — the most infamous PK guild in SAO.

**TRPG Handling**:
- Red Players are hostile NPCs
- Encountering Red Players is far more difficult than fighting same-level monsters (because they have intelligence)
- Red Players may use dirty tactics (ambush, traps, hostages)
- Defeating a Red organization is an important story milestone in the campaign

### 6.5.3 Mental Breakdown / Withdrawal from Clearing

The stress of being trapped in a death game is immense. Some players suffer mental breakdowns and refuse to leave town.

**TRPG Handling**:
- Player characters will not be forced to break down (unless the player chooses to RP it)
- NPCs' mental state is an important story element
- You may design side quests to soothe NPC players and rebuild their confidence

---

## 6.6 Item and Drop Design

### 6.6.1 Consumable Item Table

| Item | Effect | Price | Rarity |
|------|--------|-------|--------|
| Small HP Potion | Restores 50 HP | 100 Col | Common |
| Medium HP Potion | Restores 150 HP | 300 Col | Common |
| Large HP Potion | Restores 300 HP | 800 Col | Uncommon |
| SP Recovery Potion | Restores 20 SP | 250 Col | Uncommon |
| Antidote Potion | Cures Poisoned | 150 Col | Common |
| Panacea Potion | Cures all abnormal status | 1,000 Col | Rare |
| Teleport Crystal | Teleports to nearest Safe Town | 500 Col | Uncommon |
| Corridor Crystal | Opens a temporary two-way teleport gate | 5,000 Col | Rare |
| Bomb | Area damage 30-50 | 200 Col | Common |
| Smoke Bomb | Lowers enemy HIT-20 for 1 turn | 150 Col | Common |

### 6.6.2 Drop Table Design

| Monster Type | Col Drop | Material Drop Rate | Equipment Drop Rate |
|--------------|----------|--------------------|---------------------|
| Normal | Level × 8 | 30% | 5% |
| Elite | Level × 20 | 60% | 20% |
| Rare | Level × 40 | 80% | 50% |
| Boss | Level × 120 (split among party) | 100% (multiple) | 100% + LA Reward |

### 6.6.3 Rarity System

| Rarity | Mark | Drop Rate Multiplier | Price Multiplier | Number of Effects |
|--------|------|----------------------|------------------|-------------------|
| Common | ★ | ×1.0 | ×1.0 | 0 |
| Fine | ★★ | ×0.3 | ×3.0 | 1 |
| Rare | ★★★ | ×0.1 | ×10.0 | 2 |
| Legendary | ★★★★ | ×0.02 | ×50.0 | 3 |
| Mythic | ★★★★★ | Boss-only | Priceless | 4 |

---

## 6.7 Campaign Management

### 6.7.1 Campaign Trajectory Record

The GM should record the following to enable long-term tracking:

| Record Item | Description |
|-------------|-------------|
| Current Game Date | SAO internal time |
| Clearing Progress | Highest Floor currently unlocked |
| List of Deceased Characters | Recorded at the Black Iron Palace |
| Important NPC Status | Life/death, relationship changes |
| Economic Status | Party's total assets |
| Unfinished Quests | Side quest tracking |
| Guild Dynamics | Power shifts among guilds |

### 6.7.2 Long-Term Progress Recommendations

| Actual Play Time | In-Game Time | Recommended Progress |
|------------------|--------------|----------------------|
| 1 month (4 sessions) | ~2 months | Lv.1→10, clear up to Floor 5 |
| 3 months (12 sessions) | ~6 months | Lv.10→25, clear up to Floor 25 |
| 6 months (24 sessions) | ~1 year | Lv.25→50, clear up to Floor 50 |
| 1 year (48 sessions) | ~2 years | Lv.50→75, clear up to Floor 75 |

---

## 6.8 Variant Rules

### 6.8.1 Parallel World Mode

If players do not want Permanent Death, the following variant may be used:
- Upon character death, lose all EXP and items gained during that adventure
- Resurrect in town, gaining the "Death Mark" debuff (all checks -10, until next level-up)
- This mode suits a more casual play style (but is not recommended — fear of death is the core of SAO)

### 6.8.2 ALfheim Online Mode

Switch the setting to the Fairy Dance arc:
- Remove Permanent Death (ALO has no death game)
- Add flight system and magic system
- Race system (9 major fairy races)
- Suits groups wanting a lighter fantasy style

### 6.8.3 Gun Gale Online Mode

Switch the setting to the Phantom Bullet arc:
- Remove Permanent Death
- Sci-fi gun weapons replace Sword Skills
- Add the BoB (Bullet of Bullets) tournament system
- Suits groups wanting a modern combat style

---

## 6.9 SAO GM Toolkit

### 6.9.1 Improvised Naming Table

Use when you need to quickly name an NPC or town:

| Prefix | Infix | Suffix |
|--------|-------|--------|
| Steel | Iron | Town |
| Moon | Light | Castle |
| Wind | Shadow | Tower |
| Flame | Ice | Valley |
| Star | Dream | Port |
| Dragon | Sword | City |
| Silver | Wing | Island |
| Dark | Flame | Cavern |

Combination: Steel + Iron + Town = Steel Town (for Japanese style, use kanji reading: Koutetsu-machi)

### 6.9.2 Boss Name Generator

Format: `[Adjective] + [Creature/Object] + [Title]`

| Adjective (20) | Creature/Object (20) | Title (20) |
|----------------|----------------------|------------|
| Searing, Frost, Shadow, Radiant | Giant Dragon, Demon Wolf, Stone Statue, Knight | Lord, Guardian, Emperor, Reaper |
| Chaotic, Void, Iron, Blood-colored | Giant Python, Stone Golem, Undead, Mage | Tyrant, Dominator, Avenger, Inquisitor |
| Cyclonic, Abyssal, Thunder, Phantom | Scorpion King, Eagle King, Giant Spider, Serpent Queen | Soul-Eater, Destroyer, Watcher, Mocker |
| Emerald, Amethyst, Golden, Silver | Treant, Fire Sprite, Water Nymph, Sword Saint | Forger, Devourer, Eternal, Lonely One |
| Filthy, Holy, Ancient, Newborn | Machine Soldier, Magic Puppet, Ghost, Priest | Watcher, Commander, Executor, Terminator |

Examples: `Iron Demon Wolf Guardian`, `Chaotic Mage Destroyer`

---

## 6.10 Monster Type System

Group all monsters into the following types, each with fixed characteristics. When designing monsters, the GM directly applies the type template:

| Type | Characteristics | Weakness | Representative Monsters |
|------|-----------------|----------|-------------------------|
| **Beast** | SPD+5, ATK+5 | No special weakness | Berserk Boar, Giant Wolf |
| **Undead** | Poison/Bleeding immune | Holy×2.0 | Skeleton Warrior |
| **Insect** | EVA+5, Poison attacks common | Fire×1.5 | Giant Spider |
| **Armored** | DEF+10, SPD-5 | Lightning×1.5 | Kobold Guard, Ruins Guardian |
| **Dragon** | All attributes +10 | Varies by subspecies | Storm Dragon |
| **Demi-human** | Intelligent behavior, can use weapons | No special weakness | Kobold, Goblin-type |
| **Plant** | Poison/Paralysis attacks common | Fire×1.5 | Treant |
| **Magical** | Ranged attacks, floating | Physical×1.2 | Demon Eye, Fairy |
| **Mechanical** | DEF+15, Poison immune | Lightning×1.5 | Mechanical Giant |

Usage: After selecting a type for the monster, directly add the type's characteristics onto the base stats.

---

## 6.11 Unique Skills

Besides Dual Blades, SAO has other Unique Skills. There are only 10 Unique Skills in all of SAO, and only one person may hold each.

### 6.11.1 Known Unique Skills

| Skill Name | Holder | Effect | Unlock Condition |
|------------|--------|--------|------------------|
| **Dual Blades** | Kirito | Dual-wield one-handed weapons | Fastest reaction speed |
| **Holy Sword** | Heathcliff / Kayaba Akihiko | Combined offense and defense, HP regeneration | GM permission |
| **Infinite Spear** | — (original setting) | Ultimate spear evolution | Specific condition |
| **Darkness Blade** | — (original setting) | Strongest Dark-attribute | Specific condition |

### 6.11.2 GM Usage Guide

- **Dual Blades**: The only Unique Skill unlockable by players
- **Holy Sword**: As the signature ability of the final Boss (Heathcliff)
- **Other Unique Skills**: May appear as NPC abilities in the late campaign, or be created by the GM
- Each Unique Skill can only be held by **one player or NPC** — this is an inviolable system rule

---

## End-of-Volume Appendix: GM Quick Reference Table

```
═══════════════════════════════
  GM Quick Check Table
═══════════════════════════════

Combat Order: SPD sort (high → low)
Hit: D100 ≤ HIT - enemy EVA
Damage: (ATK × multiplier - DEF) × critical × attribute
Critical Success: 01-05 (always succeeds + special effect)
Critical Failure: 96-00 (always fails + mishap)

═══════════════════════════════
  Quick Monster Generation
═══════════════════════════════
HP = Level × 15 (Normal) / ×30 (Elite) / ×100+ (Boss)
ATK = Level × 1.2 + 5
DEF = Level × 0.9 + 5
HIT = 25 + Level × 0.5
EVA = 15 + Level × 0.3

═══════════════════════════════
  Quick Reward Calculation
═══════════════════════════════
EXP = Monster Level × 15 (Normal) / ×40 (Elite) / ×120 (Boss, party total)
Col = Monster Level × 8 (Normal) / ×20 (Elite) / ×120 (Boss, party total)
```

---
