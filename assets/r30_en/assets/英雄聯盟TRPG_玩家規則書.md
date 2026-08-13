# League of Legends TRPG Rulebook v0.2

> **Design Team**: Tabletop RPG Rules Studio
> **Lead Designer**: Cheng Guiyao
> **Core Design**: Bi Dou'an (dice system) | Ke Jiaoling (character system) | Zhan Zhige (combat system) | Jing Shiwen (worldbuilding)
> **Based on**: LoL S14 data conversion + v0.1 draft expansion
> **Recommended Group Size**: 2-4 hours / session, standard party of 5 + 1 GM

---

## 📑 Table of Contents

- Chapter One: Core Rules
  - 1.1 Dice System
  - 1.2 Two-Layer Attribute Architecture
  - 1.3 Skill System (Non-Combat)
  - 1.4 Check Rules
  - 1.5 Core Damage Formula
  - 1.6 Attack Speed (AS) Rules
  - 1.7 Rest & Recovery
- Chapter Two: Character Creation
  - 2.1 Creation Process
  - 2.2 Talent System
  - 2.3 Ability Points & Skill Growth
  - 2.3.5 Multiclass Rules (Optional)
  - 2.4 Energy/Mana System
  - 2.5 Levels & Experience
  - 2.6 Per-Level Attribute Growth
  - 2.7 Equipment System
  - 2.7.5 Encumbrance & Resource Management (Optional)
  - 2.8 Recommended Starting Builds
- Chapter Three: Combat & Conflict
  - 3.1 Turn Structure
  - 3.2 Action Economy
  - 3.3 Damage Types
  - 3.4 Skill Hit Types
  - 3.5 Cooldown & CDR
  - 3.6 Archetype Skill Templates
  - 3.7 Crowd Control (CC)
  - 3.7.5 Poison & Disease
  - 3.8 Terrain & Vision
  - 3.8.5 Stealth & Detection
  - 3.9 Defensive Structures
  - 3.10 Minions & Monsters
  - 3.11 Epic Monsters
  - 3.12 Death & Revival
  - 3.13 Boss Phase Framework
  - 3.13.5 Summon & Pet Rules
  - 3.14 Summoner Spells
- Chapter Four: World & Narrative
  - 4.1 Runeterra World Overview
  - 4.2 Regional Origin System
  - 4.3 Regional Battlefield Rules
  - 4.4 Champion Bond System
  - 4.5 Regional Enhancement System
  - 4.6 Party Framework
  - 4.7 GM Toolkit (Reference Entry)
- Appendices
  - A. Glossary
  - B. Damage Formula Quick Reference
  - C. Check Formula Quick Reference
  - D. Cooldown Quick Reference
  - E. Tenacity & Control
  - E2. Status Effect Index
  - F. AS Frequency Quick Reference
  - G. Level Milestones
  - H. Character Sheet Template
  - I. Quick Creation Flow Card
- Expanded Content
  - Complete Skill Catalog: 技能圖鑑.md
  - Complete Equipment Catalog: 裝備圖鑑.md
  - DLC Augment Device: 增幅裝置DLC.md
  - DLC Arcane (Player Handbook): 奧術DLC_玩家手冊.md

---

# Chapter One: Core Rules

## 1.1 Dice System

### Core Die: d20

This system uses a single d20 as the core resolution die. All uncertain situations — skill shots, ability checks, initiative order — roll a d20.

**Design Principle**: The linear distribution of a d20 (5% per face) preserves the MOBA's signature "comeback kill from a hopeless position" feel. A nat20 does not need to be re-rolled, nor does it require an extra crit die.

### When to Roll

| Situation | Rule |
|------|------|
| Basic attack damage | **Auto-hit**, calculate damage directly (like a MOBA) |
| Targeted / Lock-On skill | **Auto-hit** |
| Non-Targeted skill | Roll d20 + hit bonus vs Evasion DC |
| Narrative skill check | Roll d20 + ability modifier + Proficiency Bonus vs DC |
| Initiative check | Roll d20 + AS modifier + AGI modifier |
| Crit determination | Roll d20 ≤ Critical Strike Chance × 20 |
| Contest check | Both sides roll d20, higher wins |

### Advantage / Disadvantage

A D&D 5e mechanic reflavored for League of Legends:

- **Advantage**: Roll 2d20, take the higher. Sources: bush ambush, true vision, high-ground execution, Cloud Drake Soul blessing
- **Disadvantage**: Roll 2d20, take the lower. Sources: blind debuff, smoke bomb, being flanked, fatigued state
- **Advantage/Disadvantage cancel**: One advantage offsets one disadvantage (not a net count); only the highest resulting state applies

| Target DC | Normal success rate | Advantage success rate | Equivalent bonus |
|:------:|:--------:|:--------:|:------:|
| 10 | 55% | 79.8% | +4.95 |
| 15 | 30% | 51.0% | +4.20 |
| 20 | 5% | 9.75% | +0.95 |

> Advantage is roughly equivalent to +5 at medium difficulty (DC 10-16), with diminishing returns at low difficulty. This makes "skills that would already hit easier to land," but cannot make "the impossible possible."

---

## 1.2 Two-Layer Attribute Architecture

### Layer A: Combat Attributes (12 stats, inherited from the LoL stat panel)

| Category | Attribute | Abbr | Scope |
|------|------|:--:|--------|
| **Offense** | Attack Damage (AD) | AD | Base auto-attack damage |
| | Ability Power (AP) | AP | Base skill damage |
| | Attack Speed (AS) | AS | Initiative order, auto-attack frequency |
| | Critical Strike Chance (Crit) | Crit | d20 crit threshold |
| | Armor Penetration (ArPen) | ArPen | Reduces target's Armor value |
| | Magic Penetration (MgPen) | MgPen | Reduces target's Magic Resistance value |
| **Defense** | Health Points (HP) | HP | Survival check |
| | Armor (Armor) | Armor | Physical damage reduction |
| | Magic Resistance (MR) | MR | Magic damage reduction |
| | Tenacity (Ten) | Ten | Crowd Control duration reduction |
| **Utility** | Move Speed (MS) | MS | Evasion DC, movement squares |
| | Cooldown Reduction (CDR) | CDR | Skill frequency, cap 40% |

### Layer B: Character Abilities (6 stats, TRPG narrative side)

| Ability | Abbr | Design Intent | Typical Champions |
|------|:--:|----------|----------|
| **Strength** | STR | Physical burst, encumbrance, breaking doors | Darius / Garen |
| **Agility** | AGI | Evasion, stealth, first strike | Ezreal / Vayne |
| **Constitution** | CON | Endurance, poison resistance | Dr. Mundo / Zac |
| **Intelligence** | INT | Arcane knowledge, mechanism decoding | Heimerdinger / Ryze |
| **Perception** | PER | Scouting, tracking, awareness | Ashe / Kindred |
| **Charisma** | CHA | Persuasion, leadership, performance | Seraphine / Ezreal |

**Ability score range**: -2 to +5

### Layer B → Layer A Mapping

| Character Ability | Affected Combat Attribute | Conversion Formula |
|----------|--------------|----------|
| STR | AD, Armor | AD bonus = STR×2; Armor bonus = STR×1 |
| AGI | AS, MS, Crit | AS modifier = AGI; MS modifier = AGI; base Crit = 5% + AGI×1% |
| CON | HP | HP bonus = CON×10 (extra +CON per level) |
| INT | AP, CDR, MgPen | AP bonus = INT×2; CDR modifier = INT |
| PER | Crit Chance | Crit modifier = PER×1% (stacks with AGI) |
| CHA | Tenacity | Tenacity modifier = CHA |

---

## 1.3 Skill System (Non-Combat)

| Skill | Linked Ability | Typical Scene | Example DC |
|------|:--:|----------|:--:|
| Athletics | STR | Climbing walls, breaking down doors | Climb smooth wall DC18 |
| Stealth | AGI | Hidden movement, pickpocketing | Sneak past guards DC15 |
| Perception | PER | Spotting ambushes, discerning illusions | Detect bush ambush DC20 |
| Lore | INT | Identifying runes, alchemy recipes | Recognize ancient runes DC18 |
| Persuasion | CHA | Persuading NPCs, haggling | Convince guard to let you pass DC15 |

**Proficiency Bonus (PB)**: Characters pick 2 skill proficiencies; PB grows with level:

| Level | 1-4 | 5-8 | 9-12 | 13-16 | 17-18 |
|------|:--:|:--:|:--:|:--:|:--:|
| PB | +2 | +3 | +4 | +5 | +6 |

---

## 1.4 Check Rules

### Standard Skill Check

```
d20 + ability modifier + Proficiency Bonus (if any) vs DC
```

**When auto-success applies**:
- DC ≤ character's passive score (10 + modifier)
- Everyday trivial tasks
- Outcome is certain and there is no time pressure

### Difficulty Ladder

| Difficulty | DC | Description | Example |
|------|:--:|------|------|
| Trivial | 5 | Nearly impossible to fail | Climb a low wall barehanded |
| Simple | 10 | 50/50 for the untrained | Recognize common herbs |
| Medium | 15 | Requires professional training | Pick a simple rune lock |
| Hard | 20 | Expert-level challenge | Stealth through a dense patrol camp |
| Very Hard | 25 | Master-level feat | Hit a target 300 yards away in a storm |
| Legendary | 30 | Beyond mortal limits | Decipher lost millennium-old god-script |

### Non-Targeted Skill Check (Core Innovation)

This is the key feature that distinguishes this system from traditional d20 TRPGs — it brings LoL skill-shot aiming to the tabletop.

**Formula**: `d20 + skill hit modifier vs target's Evasion DC`

| Skill Type | Hit Modifier Source | Example |
|----------|------------|------|
| Physical shot | AGI modifier + PB | Ezreal's Q (Mystic Shot) |
| Magic projectile | INT modifier + PB | Lux's Q (Light Binding) |
| Hybrid / special | (AGI+INT)/2 + PB | Akali's E |

**Target Evasion DC** = `10 + MS modifier + evasion bonus`

**Skill-shot hit-rate analysis**:

| Attacker \ Defender MS | +1(DC11) | +2(DC12) | +3(DC13) | +4(DC14) | +5(DC15) |
|:----------------|:------:|:------:|:------:|:------:|:------:|
| +2 (Lv.1 unskilled) | 60% | 55% | 50% | 45% | 40% |
| +5 (Lv.4 skilled) | 75% | 70% | 65% | 60% | 55% |
| +8 (Lv.12 master) | 90% | 85% | 80% | 75% | 70% |
| +11 (Lv.18 min-maxed) | 100% | 95% | 90% | 85% | 80% |

### Degree of Success System

| Exceeds DC by | Success Tier | Effect |
|:------:|:------:|------|
| 0-4 | Ordinary Success | Base effect |
| 5-9 | Excellent Success | +1 damage die or extra effect |
| 10-14 | Extraordinary Success | +2 damage dice or strong effect |
| 15+ | Legendary Success | Maximized effect |
| nat20 | Perfect Success | Auto-Legendary + narrative flourish |

### Contest Checks

- **PvP**: Both sides roll `d20 + relevant modifier`, higher wins. Tie keeps the status quo.
- **Group check**: More than half succeed → group success; all succeed → excellent success; half fail → lowest roller triggers a crisis
- **Assist**: The helper rolls d20; if ≥ DC-5 the helped character gains Advantage. At most 2 helpers per target.

---

## 1.5 Core Damage Formula

### Damage Formula

```
Physical damage = AD × 100 / (100 + target Armor − ArPen) × crit modifier
Magic damage    = AP × 100 / (100 + target MR − MgPen) × effect modifier
True damage     = raw damage value (ignores resistances)
```

### Critical Determination

Roll a d20; if the result ≤ (Critical Strike Chance × 20), it is a crit. Example: 25% crit → d20 rolls 1-5 crit. Default crit deals 175% damage. A nat20 always crits; a nat1 never crits.

### Armor Reduction Quick Reference

| Armor | Damage Multiplier | Effective Reduction | Effective HP | Typical Source |
|:----:|:------:|:------:|:-----:|------|
| 0 | 1.000 | 0% | ×1.00 | No gear |
| 20 | 0.833 | 16.7% | ×1.20 | Cloth armor |
| 30 | 0.769 | 23.1% | ×1.30 | Lv.1 base Armor |
| 50 | 0.667 | 33.3% | ×1.50 | Guardian Angel |
| 100 | 0.500 | 50.0% | ×2.00 | Tank baseline |
| 150 | 0.400 | 60.0% | ×2.50 | Full tank build |
| 200 | 0.333 | 66.7% | ×3.00 | Rammus W |
| 300 | 0.250 | 75.0% | ×4.00 | Theoretical Limit |

### Basic Attack TTK Verification (Revised)

| Scenario | Lv.1 | Lv.18 naked | Lv.18 full tank |
|------|:--:|:--:|:--:|
| ADC vs squishy | ~10 hits | ~15 hits | — |
| ADC vs tank (no ArPen) | ~14 hits | ~22 hits | ~45 hits |
| ADC vs tank (with ArPen) | — | ~19 hits | ~40 hits |

> Key insight: Kill count grows from 10→14 hits at Lv.1 to 15→22 hits at Lv.18 — matching LoL's "more lethal early, tankier late" pacing. Combined with skill damage (1.5-3× a basic attack), actual TTK shortens by 40-60%.

---

## 1.6 Attack Speed (AS) Rules

| AS Range | Basic Attack Frequency | Note |
|:--|:--:|------|
| 0.50-0.99 | 1 per turn | 🔧 Floor protection: permanent minimum 1/turn |
| 1.00-1.49 | 1 per turn | Standard line |
| 1.50-1.99 | 3 per 2 turns | Odd/even turn system (odd turn 1, even turn 2) |
| 2.00+ | 2 per turn | High-speed line |

> **Core principle**: AS never reduces the base attack right — 1/turn is every hero's guaranteed minimum. AS's value lies in "crossing from 1 toward 2."

### Per-Archetype AS Growth Curve

| Level | ADC (Marksman) | Warrior | Mage | Tank (Support/Assassin) |
|:--:|:---------:|:---:|:---:|:-------------:|
| 1 | 0.75→**1** | 0.68→**1** | 0.63→**1** | 0.65→**1** |
| 11 | 1.45→**1** | 1.15→**1** | 0.88→**1** | 0.95→**1** |
| 14 | 1.70→**1.5** | 1.30→**1** | 0.97→**1** | 1.05→**1** |
| 18 | 2.10→**2** | 1.55→**1.5** | 1.05→**1** | 1.15→**1** |

> ADC breaks the 1.5 band at Lv.14 and the 2.0 band at Lv.18 (full build reaches 2.10). Mages/Tanks stay at 1/turn for life — relying on skill output.

---

## 1.7 Rest & Recovery

### Short Rest

Spend **10 minutes** (roughly 2-3 turns of narrative time) on a short rest. During it a character may:
- Use a Health Potion or other consumables
- Perform simple bandaging (DC10 Constitution check, success restores HP×10%)
- Recover all consumed Summoner Spell uses (excluding daily-limited spells)
- A Mage may meditate to recover 20% Mana

**Limitation**: No movement or strenuous activity during a short rest. Usually 1 short rest is allowed between encounters.

### Long Rest

Spend **8 hours** (typically a full night's sleep or camp downtime) on a long rest. Upon completion:
- HP restored to maximum
- MP/Mana/Energy restored to maximum
- All skill cooldowns reset
- All daily-limited abilities (e.g., Augment Device, talent limits) reset
- Remove 1 stack of "Shimmer Dependency" (if any)
- Remove all non-permanent negative states (poison, disease, fatigue)

**Limitation**: A long rest must occur in a safe environment (town, camp, hidden shelter). When taken in a dangerous area (dungeon, enemy territory), the GM should roll d20 to decide if interrupted (DC varies by environment, typically 15).

### Encounter-Day Budget

A standard "encounter day" (between two long rests) should contain:

| Difficulty | Encounter Count | Short Rest Count | Applicable Scene |
|:--:|:--:|:--:|------|
| Light | 2-3 | 1-2 | Narrative chapters, town exploration |
| Standard | 4-6 | 2-3 | Dungeon exploration, main campaign segments |
| High Pressure | 7-8 | 1-2 | Just before a Boss fight, survival scenario |

> An encounter is not necessarily combat — social maneuvering, complex traps, and environmental challenges also count as one encounter.

### Rest After Death

When a character dies and is revived (via revival timer or a teammate's skill), HP/MP restore to 50% and a long rest is needed to return to full. For 3 turns after revival, damage dealt is -20% (Weakened state).

---

# Chapter Two: Character Creation

## 2.1 Creation Process (5 Steps)

### Step One: Choose an Archetype (5 choose 1)

| Archetype | HP | AD | AP | AR | MR | AS | Move | Role |
|------|:--:|:--:|:--:|:--:|:--:|:--:|:--:|------|
| **Assassin** | 650 | 58 | 0 | 40 | 32 | 0.75 | 4 sq | High burst, low survival, mobile |
| **Warrior** | 600 | 65 | 0 | 35 | 32 | 0.70 | 4 sq | Melee carry, mid tankiness |
| **Mage** | 550 | 52 | 50 | 22 | 30 | 0.65 | 4 sq | Spell burst, ranged, squishy |
| **Marksman** | 560 | 62 | 0 | 28 | 30 | 0.80 | 4 sq | Ranged sustained output |
| **Support** | 580 | 50 | 40 | 32 | 32 | 0.65 | 4 sq | Heal/shield/control |

### Step Two: Choose Talents

```
Primary tree (1 core + 2 secondary, same tree)
Secondary tree (1 secondary, any tree)
Attribute Shards (3, may repeat)
Total: 1 core + 3 secondary + 3 shards = 7 items
```

### Step Three: Choose Starting Skill

Pick 1 of Q/W/E to learn at Lv.1.

### Step Four: Choose 2 Summoner Spells

### Step Five: Spend 500 gold on starting equipment

---

## 2.2 Talent System

### Precision — Enhance Attacks

**Core (choose 1 of 4)**:
| Talent | Effect |
|------|------|
| Deadly Precision | Crit Chance +10%, crit damage 200% |
| Lethal Tempo | On hit +3% AS/stack (max 18%), at max stacks +1 square attack range |
| Fleet Footwork | Move 3 squares to charge; at max stacks basic attack heals 20+AD×0.15 HP + +1 Move Speed |
| Conqueror | On hit stack (AD+3 or AP+5); at 6 stacks 8% damage converts to healing |

**Secondary**: Press the Attack (3 consecutive hits trigger Vulnerable), Coup de Grace (HP<40% +8% dmg), Cut Down (HP>self +10% dmg), Last Stand (lower HP = higher dmg), Legend: Alacrity/Bloodline

### Domination — Burst & Harvest

**Core (choose 1 of 4)**:
| Talent | Effect |
|------|------|
| Electrocute | 3 hits within 2 turns trigger AD×0.4+AP×0.25 (cooldown 5) |
| Predator | Active +3 Move Speed ×2 turns, next attack +AD×0.5+AP×0.3 (cooldown 8) |
| Dark Harvest | Targets below 50% HP take +20% damage; kill resets |
| Hail of Blades | First 3 basic attacks in combat +100% AS |

**Secondary**: Taste of Blood, Ghost Poro, Eyeball Collection, Ultimate Hunter, Sudden Impact, Relentless Hunter

### Sorcery — Skill Enhancement

**Core (choose 1 of 4)**:
| Talent | Effect |
|------|------|
| Arcane Mastery | Skill damage +15%, cooldown -1 turn |
| Summon Aery | Attacks +10+AP×0.1, shields +10+AP×0.1 (cooldown 1) |
| Phase Rush | +1 Move Speed, basic attack after skill costs no movement |
| Manaflow Band | On skill hit +3 Mana (max 30), at max stacks +2 Mana regen |

**Secondary**: Scorch, Waterwalking, Absolute Focus, Gathering Storm, Transcendence, Celerity

### Resolve — Durability & Control

**Core (choose 1 of 3)**:
| Talent | Effect |
|------|------|
| Unbreakable Shield | Max HP+15%, control duration -30% |
| Aftershock | After applying control, Armor+MR +25+10% (cooldown 5) |
| Guardian | Ally within 3 squares takes damage → 80+AP×0.2 shield (cooldown 5) |

**Secondary**: Revitalize, Conditioning, Overgrowth, Bone Plating, Shield Bash, Font of Life

### Inspiration — Rule Bending

**Core (choose 1 of 3)**:
| Talent | Effect |
|------|------|
| Glacial Augment | After control, 1-square slow field (cooldown 6) |
| Unsealed Spellbook | Swap Summoner Spell mid-combat (cooldown 5) |
| Kleptomancy | Every 3 turns, random core talent ×2 turns |

**Secondary**: Poise, Future's Market, Time Warp Tonic, Cosmic Insight, Magic Boots, Biscuit Delivery, Approach Velocity, Minion Dematerializer

### Attribute Shards (choose 3)

| Shard | Effect | Shard | Effect |
|------|------|------|------|
| Attack Damage | AD+6 | Magic Resistance | MR+5 |
| Ability Power | AP+6 | CDR | CDR+3% |
| Attack Speed | AS+5% | Move Speed | +0.5 sq |
| Health Points | HP+50 | Growth AD | +0.5 AD/level |
| Armor | AR+5 | Growth AP | +0.5 AP/level |
| | | Growth HP | +15 HP/level |

---

## 2.3 Ability Points & Skill Growth

### Level-by-Level Allocation

```
Lv.1  → Learn 1 of Q/W/E (Lv.1)
Lv.2  → Learn 1 of the remaining 2 (Lv.1)
Lv.3  → Auto-fill the last one (Lv.1) — Q/W/E complete
Lv.4  → +1 ability point    Lv.5 → +1    Lv.6 → +1 [R auto Lv.1]
Lv.7  → +1           Lv.8 → +1    Lv.9 → +1    Lv.10 → +1
Lv.11 → +1 [R auto Lv.2]            Lv.12 → +1   Lv.13 → +1
Lv.14 → +1           Lv.15 → +1   Lv.16 → +1 [R auto Lv.3]
Lv.17 → +1           Lv.18 → +1
```

**Point verification**: Q/W/E each need 4 points to max = 12 points; Lv.4-18 yields 15 ability points (including R's auto-upgrades at Lv.6/11/16), an exact match.

---

## 2.3.5 Multiclass Rules (Optional)

Upon reaching **Lv.6**, a character may choose to multiclass into a second archetype.

### Multiclass Benefits
- Gain the second archetype's **passive ability**
- Gain the second archetype's **Q/W/E skills** (each starting at Lv.1)
- Ability points may be allocated to either archetype's skills from this point
- Attribute growth becomes the average of both archetypes (HP/AD/AP/AR/MR/AS each averaged then rounded)

### Multiclass Limits
- The second archetype's R skill unlocks at **Lv.11** (not Lv.6)
- The two archetypes' skill cooldowns are tracked independently
- Total ability points are unchanged (the 12 points after Lv.6 must be split across 8 skills)
- **No multiclassing into the same archetype**, and no triple-classing

### Recommended Multiclass Combinations
| Primary | Secondary | Style |
|------|------|------|
| Warrior + Assassin | High-burst semi-tank |
| Mage + Support | Healing Mage |
| Marksman + Assassin | High-mobility ADC |
| Support + Mage | Control Support |

---

---

## 2.4 Energy/Mana System

| Archetype | Lv.1 Mana | Growth | Regen/turn | Note |
|------|:------:|:--:|:------:|------|
| Assassin | 300 | +25 | 5% | Fast-paced energy type |
| Warrior | 100 | — | +15/on basic atk +10/on hit taken -10/out of combat | Rage mechanic |
| Mage | 400 | +30 | 6% | High mana pool |
| Marksman | 300 | +20 | 4% | Moderate consumption |
| Support | 350 | +25 | 5% | Moderate mana pool |

**Mana cost baseline**: Q=30(+5/level), W=40(+5/level), E=50(+5/level), R=100 (unchanged)

---

## 2.5 Levels & Experience

### EXP Table

| Level Up | EXP Needed | Cumulative | Milestone |
|:--:|:----:|:----:|--------|
| 1→2 | 280 | 280 | |
| 2→3 | 340 | 620 | Q/W/E complete |
| 3→4 | 400 | 1,020 | First ability point |
| 4→5 | 480 | 1,500 | |
| 5→6 | 560 | 2,060 | R unlocks Lv.1 |
| 6→7 | 640 | 2,700 | |
| 7→8 | 720 | 3,420 | |
| 8→9 | 800 | 4,220 | |
| 9→10 | 880 | 5,100 | |
| 10→11 | 960 | 6,060 | R→Lv.2 |
| 11→12 | 1,040 | 7,100 | |
| 12→13 | 1,120 | 8,220 | |
| 13→14 | 1,200 | 9,420 | |
| 14→15 | 1,280 | 10,700 | |
| 15→16 | 1,360 | 12,060 | R→Lv.3 |
| 16→17 | 1,440 | 13,500 | |
| 17→18 | 1,520 | 15,020 | Max level |

> **v0.2.1 fix**: The late EXP curve was adjusted to steady growth (+80 EXP/level) to avoid stagnation at Lv.13-16. Cumulative EXP adjusted from 12,420 to 15,020.

### EXP Sources

| Source | EXP |
|------|:--:|
| Melee minion | 60 |
| Ranged minion | 30 |
| Siege minion (cannon) | 90 |
| Large monster | 100 |
| Epic monster | 200 |
| Champion kill | 300(+level difference×20) |
| Assist | 150(+level difference×10) |
| Turret (shared) | 250 |
| Quest completion (GM award) | 100-500 |

---

## 2.6 Per-Level Attribute Growth

| Archetype | HP | AD | AP | AR | MR | AS |
|------|:--:|:--:|:--:|:--:|:--:|:--:|
| Assassin | +110 | +3.0 | +0 | +5.0 | +2.0 | +1.5% |
| Warrior | +100 | +4.0 | +0 | +4.5 | +1.5 | +2.5% |
| Mage | +90 | +2.5 | +5.0 | +3.5 | +1.3 | +1.5% |
| Marksman | +90 | +3.5 | +0 | +3.5 | +1.3 | +3.5% |
| Support | +95 | +2.5 | +4.0 | +4.0 | +1.5 | +2.0% |

### Lv.18 Naked Attributes

| Archetype | HP | AD | AP | AR | MR | AS |
|------|:--:|:--:|:--:|:--:|:--:|:--:|
| Assassin | 2,520 | 109 | 0 | 125 | 66 | 1.01 |
| Warrior | 2,300 | 133 | 0 | 112 | 58 | 1.13 |
| Mage | 2,080 | 95 | 135 | 82 | 52 | 0.91 |
| Marksman | 2,090 | 122 | 0 | 88 | 52 | 1.40 |
| Support | 2,195 | 93 | 108 | 100 | 58 | 0.99 |

---

## 2.7 Equipment System

> For the complete equipment catalog, see the standalone file **`裝備圖鑑.md`** (127 items with build paths, mythic items, and recommended build routes).

### Equipment Slots
- 6 equipment slots (unique per name) + 1 boot slot (independent) + 1 trinket slot (independent)
- Recall channel 2 turns → full state, sell returns 70%

### Gold Source Quick Reference

| Source | Gold | Source | Gold |
|------|:--:|------|:--:|
| Passive income | By level (see table below) | Assist | 150 |
| Melee minion (last hit) | 21 | First Blood | +100 |
| Ranged minion (last hit) | 14 | Shutdown (3-kill streak) | 450 |
| Siege minion (last hit) | 60 | Shutdown (5-kill streak) | 600 |
| Champion kill | 300 | Turret (shared) | 250 |
| Quest reward (GM-granted) | 100-500 | Epic monster | 100 |

#### Passive Income (grows by level)

| Level Range | Passive Gold/turn | Note |
|:--:|:--:|------|
| Lv.1-5 | 20 | Early laning |
| Lv.6-10 | 30 | Mid-game roaming |
| Lv.11-15 | 45 | Late-game teamfights |
| Lv.16-18 | 60 | End-game full-build sprint |

> **v0.2.1 fix**: Passive income now grows by level, ensuring late-game item progression matches game pacing. The 60 gold/turn at Lv.16+ lets a full build be reached in ~30-35 turns (including kill rewards).

### Starting Equipment (optional reference)
| Name | Price | Attributes | Effect |
|------|:--:|------|------|
| Doran's Blade | 450 | AD+8, HP+80 | +3 damage vs minions |
| Doran's Ring | 450 | AP+12, HP+60 | +6 Mana on kill |
| Doran's Shield | 450 | HP+80, +6/turn regen | Blocks 8 single-target damage |

---

## 2.7.5 Encumbrance & Resource Management (Optional Rule)

> The GM may enable the following rules to add survival challenge. By default, tracking is not enforced.

### Encumbrance Limits

| STR | Light (no penalty) | Medium (Move -1) | Heavy (Move -2, Evasion Disadvantage) |
|:--:|:--:|:--:|:--:|
| -2 | 30 | 60 | 90 |
| -1 | 45 | 90 | 135 |
| 0 | 60 | 120 | 180 |
| +1 | 75 | 150 | 225 |
| +2 | 90 | 180 | 270 |
| +3 | 105 | 210 | 315 |
| +4 | 120 | 240 | 360 |
| +5 | 135 | 270 | 405 |

**Item weight reference**: Weapons 5-15, armor 15-30, potions 1, gold 0.01/coin (1,000 gold = 10 units).

### Ammunition (ranged weapons)

Ranged basic attacks are assumed to have ample ammunition by default. If the GM enables ammunition tracking:
- Each combat consumes 1 unit of ammunition (regardless of number of attacks)
- Ammunition price: 20 gold / 10 units
- When ammunition runs out, basic attack damage is halved

### Lighting

| Light Source | Range | Duration | Price |
|------|:--:|:--:|:--:|
| Torch | 3 sq | 10 turns | 5 gold |
| Lantern | 5 sq | 30 turns | 50 gold |
| Hextech Flashlight | 6 sq | Permanent (needs Hextech crystal) | 300 gold |

---

## 2.8 Recommended Starting Builds

> For detailed build routes, see **`裝備圖鑑.md`** Chapter 12 (5 archetypes × 5-stage route table).

| Archetype | Primary Talent Tree | Summoner | Starting Equipment Reference |
|------|---------|--------|------|
| Assassin | Domination (Electrocute) | Flash + Ignite | Doran's Blade + potion |
| Warrior | Precision (Conqueror) | Flash + Ghost | Doran's Shield + potion |
| Mage | Sorcery (Arcane Mastery) | Flash + Barrier | Doran's Ring + 2 potions |
| Marksman | Precision (Lethal Tempo) | Flash + Heal | Doran's Blade + potion |
| Support | Resolve (Guardian) | Flash + Exhaust | Spellthief's Edge + 2 potions |

---

# Chapter Three: Combat & Conflict

## 3.1 Turn Structure

### Full Turn Flow

```
1. Start Phase
   ├─ Trigger "turn start" effects (DoT, status tick, dot/doh)
   ├─ Resolve environment effects (terrain damage, auras)
   └─ Refresh reactions, per-turn limits

2. Action Phase (act in initiative order)
   ├─ Highest initiative → perform all actions → end
   ├─ Next highest initiative → ...
   └─ Lowest initiative → end

3. End Phase
   ├─ Trigger "turn end" effects (recovery, status expiry)
   ├─ Resolve delayed effects
   └─ Turn counter +1
```

### Initiative

`Initiative = d20 + AS modifier + AGI modifier`

- On tie, higher AS goes first
- Delay action: may declare a lower position; once dropped below someone it permanently fixes the new position
- Ready action: spend a standard action, set a trigger condition, execute on reaction

---

## 3.2 Action Economy

Each turn, every hero has:

| Action Type | Count | Use |
|----------|:--:|------|
| Standard action | 1 | Basic attack / cast skill / use equipment active |
| Move action | 1 | Move MS squares / enter bush / interact |
| Bonus action | 1 | Specific skills / swap equipment / drink potion |
| Free action | Unlimited | Speak / mark / change stance |
| Reaction | 1/turn | Opportunity attack / trigger-type skill reaction |

**Action trading**: A standard action may be downgraded to a move action. Two move actions do not combine.

### Opportunity Attack

Leaving any enemy's melee range (within 1 square) triggers an opportunity attack: a free basic attack. Flash/blink-type skills are immune to opportunity attacks.

---

## 3.3 Damage Types

| Type | Formula | Unaffected |
|------|------|----------|
| Physical | AD×100/(100+Armor–ArPen) | Shield absorbed first, Armor reduces |
| Magic | AP×100/(100+MR–MgPen) | Shield absorbed first, MR reduces |
| True | Raw value | Ignores all resistances and shields |
| Critical | Physical×(175%+equipment bonus) | nat20 always crits, nat1 never crits |

---

## 3.4 Skill Hit Types

Every skill must be tagged with one of the following three hit types:

| Tag | Meaning | Check Formula |
|------|------|----------|
| **【Auto-Hit】** | Single-target lock / self-buff / aura | No roll needed |
| **【Directed Projectile】** | Requires aiming direction | d20 + attribute modifier + PB vs Evasion DC (10+MS modifier) |
| **【Area Check】** | AOE skill | Same as above, center square DC-2 |

**Attribute modifier assignment**:
- AGI modifier (physical shot): Assassin Q/W/R, Warrior Q/E, Marksman Q/E/R
- INT modifier (magic projectile): Mage Q/W/R, Support E
- Auto-hit (no attribute needed, or self-buff, aura, locked target): Assassin E, Warrior W/R, Mage E, Marksman W, Support Q/W/R

---

## 3.5 Cooldown & CDR

### Base Cooldown Conversion

| Original LoL CD | Corresponding Turns |
|:--------:|:------:|
| 3-5 sec | 1 turn |
| 6-10 sec | 2 turns |
| 11-15 sec | 3 turns |
| 16-30 sec | 4 turns |
| 60-90 sec (ultimate) | 6-8 turns |
| 120+ sec | 10-12 turns |

### CDR Effect

`Every 10% CDR reduces cooldown by 1 turn (minimum 1 turn), cap 40%`

**Example**: A 4-turn cooldown skill at 40% CDR becomes min(4-4, 1) = 1 turn.

---

## 3.6 Archetype Skill Templates

> The complete skill catalog (25 template sets × 5 archetypes = 125 Q/W/E/R skills + 16 Summoner Spells) is in the standalone file **`技能圖鑑.md`**.

### Quick Reference: First Template Set per Archetype (Template A)

| Archetype | Q | W | E | R |
|------|---|---|---|---|
| Assassin | Shadow Stab (AD×1.5) | Smoke Bomb (reduce hit) | Blink (dash + bonus dmg) | Death Lotus (AOE harvest) |
| Warrior | Cyclone Slash (cone AOE) | Battle Cry (shield + reflect) | Charge Assault (control) | Endless Fury (empower) |
| Mage | Arcane Missile (ranged poke) | Frost Nova (AOE slow) | Mana Barrier (shield) | Meteor Fall (AOE burst) |
| Marksman | Piercing Shot (pierce) | Tailwind Step (burst move) | Beast Trap (immobilize) | Ultimate Hunt (ranged execute) |
| Support | Healing Wave (heal) | Holy Light Shield (shield) | Binding Light (immobilize) | Sacred Domain (aura) |

> There are also 4 variant template sets (B/C/D/E) + 5 passives + combo suggestions; see the skill catalog for details.

---

## 3.7 Crowd Control (CC)

| Type | Effect | Tenacity-reduced? | Example Skill |
|------|------|:--:|----------|
| Stun | Lose all actions 1-2 turns | ✓ | Leona Q |
| Slow | MS-1~2 sq, lasts 1-3 turns | ✓ | Ashe W |
| Root | Cannot move but can attack/cast | ✓ | Ezreal E |
| Silence | Cannot cast but can attack/move | ✓ | Soraka E |
| Knockup | Lose all actions 1 turn (uncleanseable) | ✗ | Malphite R |
| Suppress | Both sides lose all actions | ✗ | Malzahar R |
| Blind | Basic attacks auto-miss | ✓ | Teemo Q |
| Fear | Forced movement away from source | ✓ | Fiddlesticks Q |
| Charm | Forced movement toward source | ✓ | Ahri E |
| Sleep | Cannot act until damaged awake | ✓ | Zoe E |
| Immobilize | Cannot move/basic attack, can cast | ✓ | Senna W |
| Disarm | Cannot basic attack, can move/cast | ✓ | Quinn Q |
| Ground | Cannot use dash skills | ✓ | Cassiopeia W |
| Knockback | Forced displacement | ✗ | Lee Sin R |
| Suppress (special) | Both sides lose all actions | ✗ | — |
| Invulnerable | Immune to damage and CC | ✗ | Taric R |

**Tenacity formula**: `Actual duration = original duration × (1 − Tenacity%)`, rounded up (minimum 1 turn)

---

## 3.7.5 Poison & Disease

### Poison

Poison is a damage-over-time status. Each time a character takes poison-attribute damage, they gain poison stacks.

| Poison Stacks | Damage/turn | Duration | Save DC |
|:--:|:--:|:--:|:--:|
| Light (1-3 stacks) | HP×1% | 2 turns | DC12 Constitution |
| Moderate (4-6 stacks) | HP×2% | 3 turns | DC15 Constitution |
| Heavy (7-9 stacks) | HP×3% | 4 turns | DC18 Constitution |
| Lethal (10+ stacks) | HP×5% | 5 turns | DC20 Constitution |

**Removing poison**: Each short rest allows a Constitution save against the poison DC; success reduces 1 stack. After a long rest all poison stacks clear. Healing-type skills can remove 1-3 stacks (by skill level).

### Disease

Disease is a long-term negative state that does not fade on its own.

| Disease | Effect | Incubation | Cure DC | Cure Method |
|------|------|:--:|:--:|------|
| Zaun Grey Lung | Max HP -5% after each long rest (cumulative) | 3 days | DC15 | Magic cure + 3× long rest |
| Shimmer Dependency | See Arcane DLC Shimmer system | — | Special | Withdrawal quest |
| Rune Fever | Max Mana -20%, casting DC+2 | 1 day | DC18 | Holy water + DC15 Constitution save |
| Shadow Corruption | HP -5 at start of each turn, takes ×1.5 light damage | Immediate | DC20 | Holy purification ritual |
| Blight | STR & AGI -2 (permanent until cured) | 7 days | DC22 | Legendary-grade healing |

> Diseases mainly serve as narrative tools; the GM may customize incubation, effects, and cure requirements.

---

---

## 3.8 Terrain & Vision

### Seven Terrain Types

| Terrain | Move Cost | Special Effect |
|------|:--:|------|
| Flat ground | 1 sq | Normal |
| Bush | 1 sq | Hidden on entry (visible within same bush), initiative advantage |
| River | 2 sq | Entering costs extra movement |
| Wall | Impassable | Can serve as cover, needs Flash/dash to cross |
| Thicket | 2 sq | Like bush + difficult terrain |
| Shallow water | 2 sq | Move speed halved |
| Tower Ruin | 1 sq | Unrebuildable destroyed tower spot |

### Vision

| Vision Tier | Distance | Condition |
|:------:|:--:|------|
| Normal | 6 sq | Unobstructed |
| Inside bush | Own square | One-way vision (cannot see in/out of bush, can see within same bush) |
| True vision | 6 sq | Reveals stealthed units |
| Restricted | 3 sq | Smoke/blind effect |
| Night | 2 sq | Night combat / Shadow Isles environment |

### Ward System

| Type | Vision | Duration | Cooldown |
|------|:--:|:--:|:--:|
| Stealth Ward | 5 sq | 12 turns | 8 |
| Control Ward | 3 sq true vision | Permanent (can be destroyed) | 5 |
| Farsight Ward | 1 sq (placed at range) | Permanent (destroyed in 1 hit) | 10 |

---

## 3.8.5 Stealth & Detection

### Hide

In combat, a character may use a **bonus action** to attempt to Hide. Make a Stealth check (d20 + AGI modifier + Proficiency Bonus); the result becomes the stealth DC. An enemy must beat this DC with a Perception check to spot you.

**Hiding conditions**:
- Must be in heavy cover (full cover, dense fog, smoke, bush)
- Cannot begin hiding within an enemy's direct line of sight
- Enemies whose passive awareness ≥ stealth DC auto-detect (no check needed)

**Passive awareness**: 10 + PER modifier + Proficiency Bonus (if any). The GM may secretly use this value to judge whether monsters notice the players.

### Group Stealth

When the whole party stealths, use the **lowest-value rule**: each member rolls their own Stealth check; the lowest result becomes the party's stealth DC. Discovery by any single enemy exposes the party.

**Condition relief**: If a party member provides cover (e.g., creates a distraction, uses smoke), the lowest roller's DC gains +5.

### Alert Level (GM Tool)

| Level | State | Enemy Behavior |
|:--:|------|------|
| 0 | Unaware | Normal patrol |
| 1 | Suspicious | Move toward anomaly, Perception DC+2 |
| 2 | Alert | Search area, Perception DC+5, +1 wave of reinforcements |
| 3 | Combat | Whole area enters combat state |

Each time players trigger an alert (spotted, trap triggered, loud noise), alert level +1. Each short rest lowers it by 1 level.

### Stealth in Combat

- **Stealthed**: Cannot be directly targeted (single-target directed skills cannot select); AOE can still hit
- **Attacking breaks stealth**: Stealth ends immediately after attacking or casting a damage skill
- **Detecting stealth**: True-vision wards, control wards, and specific skills can reveal stealthed units

---

## 3.9 Defensive Structures

### Turrets

| Tower Type | HP | AD | AR | MR | Attack Range | Special |
|------|:--:|:--:|:--:|:--:|:--:|------|
| Outer Tower | 500 | 80 | 50 | 50 | 8 sq | Plating 5 layers ×100HP |
| Inner Tower | 600 | 100 | 80 | 70 | 8 sq | — |
| Inhibitor Tower | 700 | 120 | 100 | 90 | 8 sq | — |
| Nexus Tower | 400×2 | 90 | 70 | 70 | 8 sq | Two towers protect each other |

**Tower attack priority**: Enemy champion > siege minion > melee minion > ranged minion

**Tower damage stacking**: Consecutive attacks on the same target deal +40% damage (2nd hit = 1.4×, 3rd = 1.8×… cap 4 stacks)

**Plating mechanic**: Each layer 100HP, destroyed grants 160 gold. After 14 turns plating vanishes, tower defense -20%.

**No-minion reinforcement**: Tower Armor+MR +100.

### Inhibitor / Nexus

- Inhibitor HP 400, AR 50, MR 50
- After destruction: that lane's enemy minions upgrade to super minions (+50% HP, +30% AD), respawn after 5 turns

---

## 3.10 Minions & Monsters

### Minion Waves

One wave every 3 turns (2 melee + 2 ranged). Every 3rd wave adds a siege minion.

| Minion | HP | AD | AR | Gold | EXP |
|------|:--:|:--:|:--:|:--:|:--:|
| Melee minion | 300-800 | 8-30 | 10-50 | 21 | 60 |
| Ranged minion | 200-550 | 12-40 | 5-30 | 14 | 30 |
| Siege minion | 500-1500 | 25-70 | 40-90 | 60 | 90 |
| Super minion | 800-2500 | 35-100 | 80-120 | 60 | 90 |

### Jungle Camps

| Monster | HP | AD | Special Buff | Gold | EXP |
|------|:--:|:--:|------|:--:|:--:|
| Crimson Brambleback (Red Buff) | 600-2000 | 30-90 | Basic attacks deal true damage + slow + out-of-combat heal | 100 | 100 |
| Blue Sentinel (Blue Buff) | 600-2000 | 25-80 | Mana regen + 20% CDR + 10% AP | 100 | 100 |
| Gromp | 500-1800 | 35-100 | None | 80 | 80 |
| Greater Murk Wolf | 300×3 | 15-50 | None (scout area) | 60 | 60 |
| Raptor | 200×6 | 10-35 | None | 10×6 | 10×6 |
| Stone Beetle | 400/200×4 | 20/10 | None (split mechanic) | 100 | 100 |
| Rift Scuttler | 300 | 0 | Speed shrine (5-sq move-speed buff zone) | 50 | 50 |

---

## 3.11 Epic Monsters

### Elemental Drakes

4 Elemental Drake types × 2 phases (transitions at 50% HP).

| Drake | HP | AD | AR/MR | Elemental Skill | Dragon Soul Buff |
|------|:--:|:--:|:--:|------|------|
| Infernal Drake | 800 | 70 | 50/50 | Fire Breath (cone AP damage) | AD/AP +8% |
| Ocean Drake | 800 | 55 | 50/50 | Water Wave (line knockback) | Recover 5% missing HP per turn |
| Cloud Drake | 800 | 45 | 50/50 | Storm Vortex (AOE slow) | +2 Move Speed out of combat |
| Mountain Drake | 900 | 60 | 80/80 | Rockfall (single-target high damage) | AR/MR +10% |

### Baron Nashor (Epic Boss)

| Attribute | HP | AD | AR/MR |
|------|:--:|:--:|:--:|
| Baron | 2000 | 120 | 100/100 |

**3-phase mechanic** (P1→P2: 70% HP, P2→P3: 35% HP, 1 invulnerable transition turn):

- **P1**: Basic attack + Acid Pool (designated area DoT) + Tentacle Sweep (cone knockback)
- **P2**: Adds Void Gaze (line, hit unit stunned 1 turn)
- **P3**: Adds Void Collapse (full-screen AOE, center hit DC-5), damage +30%

**Baron's Eye weak point**: On specific turns a weak point appears 1 square behind; attacks on that square deal double damage.

**Baron buff**: After kill, whole party AD/AP+30, minion empower aura (permanent).

---

## 3.12 Death & Revival

### Near-Death Rules

After HP drops to 0, enter near-death state: at start of each turn roll d20 (DC10); 3 successes → stabilized (HP back to 1), 3 failures → dead.

### Revival Timer

| Level | Revival Turns | Note |
|:--:|:--:|------|
| 1-5 | 2 turns | Early fast pace |
| 6-10 | 3 turns | Mid-game |
| 11-15 | 4 turns | Late-game |
| 16-18 | 5 turns | Max level |

After revival HP/MP full; recall revival is faster (1 turn).

---

## 3.13 Boss Phase Framework (Configurable)

### General Rules

| Parameter | Default | Adjustable Range |
|------|:--:|:--:|
| Phase trigger threshold | HP 70%/35% | Any percentage |
| Phase count | 3 | 2-4 |
| Transition mode | Invulnerable transition | Invulnerable / Scripted / Seamless |

### Three Transition Modes

| Mode | Effect | Applicable Scene |
|------|------|----------|
| **Invulnerable transition** | Boss invulnerable 1 turn | Dragons, Baron (standard epic Boss) |
| **Scripted transition** | Boss not invulnerable, only performs a scripted action | Intro module (lower difficulty) |
| **Seamless transition** | Instant switch, no transition turn | Berserk-type Boss |

---

## 3.13.5 Summon & Pet Rules

Several skills can create summons (clone, turret, trap, sand soldier, undead, etc.). The following are unified management rules.

### Summon Action Rules

- **Control**: The summon is controlled by its creator during the creator's turn
- **Action cost**: Commanding a summon uses the creator's **bonus action** (at most 1 summon action per turn)
- **Summon action**: Each commanded summon may take 1 move (per its move speed) and 1 attack/special action
- **Duration**: Per skill description; expires and vanishes automatically

### Summon Attribute Formulas

| Summon Type | HP | AD | Move Speed | Example Skill |
|------|:--:|:--:|:--:|------|
| Clone | Creator HP×20-40% | Creator AD×30-50% | Same as creator | Assassin W — Shadow Clone |
| Turret/Trap | Fixed value (by skill level) | Creator AD×30-50% | 0 (fixed) | Marksman E — Beast Trap |
| Summoned creature | Fixed value (by skill level) | Fixed value | 3-4 sq | Support R — Summon |
| Undead | Fixed HP (by skill level) | Fixed AD | 2-3 sq | Shadow Isles skills |

### Summon Limits

- Max simultaneous count of the same type per skill description (usually 1-4)
- Summons cannot hold equipment, use skills, or trigger talents
- Summons take AOE damage normally (no reduction)
- When the creator dies, all summons vanish immediately

---

---

## 3.14 Summoner Spells (choose 2)

> The complete Summoner Spell catalog (16 spells) is in the standalone file **`技能圖鑑.md`** Chapter 8.

### Core 9 Spells Quick Reference

| Spell | Cooldown | Effect |
|------|:--:|------|
| **Flash** | 10 | Blink 3 squares |
| **Ignite** | 8 | 80+LV×20 true damage 3 turns + Grievous Wounds |
| **Heal** | 10 | Restore 100+LV×20 + Move Speed +1 |
| **Barrier** | 8 | 100+LV×30 shield 2 turns |
| **Ghost** | 8 | Move Speed +3×3 turns, ignores collision |
| **Cleanse** | 8 | Cleanse CC + 65% Tenacity 1 turn |
| **Teleport** | 15 | Channel 2 turns → teleport to friendly unit |
| **Smite** | 5 | 300+LV×30 true damage to monsters + heal HP×10% |
| **Exhaust** | 8 | Enemy damage -40% + Move Speed -2×2 turns |

> Expanded spells (Clarity, Clairvoyance, Iron Elixir, Time Rift, Mighty Blow, Energy Burst, Revive) are detailed in the skill catalog.

---

# Chapter Four: World & Narrative

## 4.1 Runeterra World Overview

### Three Narrative Axes

| Axis | Core Tension | Typical Conflict |
|------|----------|----------|
| **Power & Price** | What must be paid to gain power? | Order of anti-magic stone vs freedom of magic |
| **Order & Chaos** | Eternal tug-of-war of civilization and wilderness | Demacia vs Noxus, Piltover vs Zaun |
| **Belonging & Exile** | Who has the right to define "us"? | Ionia's anti-invasion, Freljord tribal identity |

### Key Regions (8)

| Region | Core Conflict | Suitable Adventures |
|------|----------|----------|
| **Demacia** | Anti-magic decree vs oppressed mages | Political intrigue, underground rescue |
| **Noxus** | Will of the strong vs imperial machine | Military operations, power struggles |
| **Ionia** | Traditional balance vs war trauma | Spiritual trials, resistance movement |
| **Freljord** | Three tribes' struggle & ancient Iceborn | Survival, tribal alliance |
| **Shurima** | Empire revival vs desert law | Ruin exploration, ancient secrets |
| **Bilgewater** | Lawless pirate port | Smuggling, treasure hunting |
| **Piltover & Zaun** | Upper city prosperity vs lower city chem pollution | Tech crime, class conflict |
| **Shadow Isles** | Return of the dead & the edge of humanity | Horror survival, soul redemption |

---

## 4.2 Regional Origin System

### Design Philosophy

Every hero comes from a corner of Runeterra. Your origin is more than backstory — it grants unique regional traits, an initial bond NPC, and advantages in specific terrain. This lets the worldbuilding be felt through **mechanics**, not just GM narration.

### Creation Step — Regional Origin (after choosing archetype)

```
Step 1: Choose archetype (5 choose 1)
Step 1.5: Choose origin region (8 choose 1) ← added
Step 2: Choose talents
...
```

### Eight Region Origin Traits

| Region | Regional Trait (passive) | Regional Weakness (counterbalance) | Initial Bond NPC |
|------|------|------|------|
| **Demacia** | When taking magic damage, treat AR/MR as +10 (Lightshield Lineage) | Marked as priority target by enemy mages (Hatred +1) | Garen / Lux |
| **Noxus** | After killing an enemy, +15% AD next turn (Third Charge) | Disadvantage on social interaction checks (feared reputation) | Darius / Swain |
| **Ionia** | Outside combat, 10-min meditation recovers 1 consumed Q/W/E cooldown (Spiritual Balance) | After first participating in a massacre scene, Disadvantage until next meditation | Irelia / Karma |
| **Freljord** | Frost damage halved; first lethal hit each combat leaves 1 HP (Winter's Form) | Fire damage +25% | Ashe / Sejuani |
| **Shurima** | No move penalty in desert terrain; advantage on ancient ruin Lore checks (Ascension Legacy) | -1 Move Speed in water/wetlands | Azir / Nasus |
| **Bilgewater** | Killing grants extra +50 gold; advantage on social (haggling/intimidation) checks (Pirate's Nature) | Disadvantage on legal-occasion social checks | Miss Fortune / Gangplank |
| **Piltover** | Equipment craft cost -15%; advantage on Lore checks (Academy Training) | Disadvantage on stealth in pure natural environments (unused to the wild) | Caitlyn / Jayce |
| **Shadow Isles** | After death may act 1 more turn before falling (Will of the Dead) | Takes ×1.5 holy/light damage | Thresh / Kalista |

> Every origin has positive and negative effects — Demacians resist magic but draw mage hatred, Noxians hit hard but nobody trusts them. This ensures the choice is never pure gain.

---

## 4.3 Regional Battlefield Rules

> The Regional Battlefield Rules (8-region field effects + d8 random draw table) have moved to **`gm_toolkit_v0.2.md`** Chapter One.

---

## 4.4 Champion Bond System

### Design Philosophy

Each region has 2-3 well-known champions. Players accumulate **Bond Value** (0-10) through narrative interaction, unlocking increasingly strong narrative and combat rewards.

### Eight-Region Champion Roster

| Region | Mentor Champion | Ally Champion | Nemesis Champion |
|------|------|------|------|
| Demacia | Garen (Warrior) | Lux (Mage) | Sylas (Mage) |
| Noxus | Swain (Mage) | Darius (Warrior) | Katarina (Assassin) |
| Ionia | Karma (Support) | Irelia (Warrior) | Zed (Assassin) |
| Freljord | Ashe (Marksman) | Braum (Support) | Lissandra (Mage) |
| Shurima | Nasus (Warrior) | Azir (Mage) | Renekton (Warrior) |
| Bilgewater | Gangplank (Warrior) | Miss Fortune (Marksman) | Pyke (Assassin) |
| Piltover | Jayce (Warrior) | Caitlyn (Marksman) | Viktor (Mage) |
| Shadow Isles | Thresh (Support) | Kalista (Marksman) | Hecarim (Warrior) |

### Bond Tiers & Rewards

| Bond Value | Tier | Unlocked Effect | How to Gain |
|:--:|------|------|------|
| 1-3 | **Acquainted** | May request small help: 1 intel tip / temporary equipment loan (value ≤ 500 gold) | Complete regional quest |
| 4-6 | **Ally** | 1 champion assist call per chapter: AD×2.0 single-target damage (mentor), AP×2.0 (mage type) | Protect that champion in a Boss fight |
| 7-8 | **Comrade** | Gain that champion's signature passive (e.g., Garen's "Tenacity" = below 50% HP heals double per turn) | Complete champion's personal story arc |
| 9 | **Legacy Candidate** | Gain a variant version of one of that champion's Q/W/E skills | Make a major sacrifice |
| 10 | **Legacy Bearer** | Gain a variant version of that champion's R skill; champion formally retires/hands over | Complete an epic personal story |

> **GM note**: The presence of a nemesis champion per region ensures bonding is never pure positive gain — allying with one means offending another.

---

## 4.5 Regional Enhancement System (8-region balanced equivalent)

### Design Philosophy

Each region has a unique **enhancement path**, giving region-born characters extra growth opportunities. All systems are numerically equivalent — differences lie only in **how they are obtained** and **flavor**.

```
Balance baseline: spend ~1,500 gold-equivalent resources / 1 chapter milestone
→ gain a permanent boost roughly equal to 1 starter item (~700 gold value)
```

---

### 4.5.1 Piltover & Zaun — Hextech Forging

| Forge Tier | Cost | Effect | Requirements |
|:--:|:--:|------|------|
| Basic | 500 gold | +3 main attribute to 1 designated item | Visit blacksmith NPC |
| Intermediate | 1,200 gold + 1 Hextech crystal | +6 attribute to 1 item + random Common-rarity Augment effect (roll d20 from common pool) | Visit blacksmith + complete 1 commission |
| Advanced | 2,500 gold + 3 Hextech crystals | +10 attribute to 1 item + random Rare-rarity Augment effect | Blacksmith favor ≥ 7 |

**Hextech crystal sources**: Boss drops 1-2, hidden chests, shop purchase (800 gold each).

---

### 4.5.2 Noxus — Blood Trial

Noxians trade **proof of battle** for power, not gold.

| Trial Tier | Requirement | Effect | Frequency Limit |
|:--:|------|------|:--:|
| Basic | Solo-defeat 1 equal-level enemy (GM-controlled) | Permanent AD +3 or AP +4 | 1/Chapter |
| Intermediate | First to kill 3 enemy champions in combat (cumulative) | Permanently gain "Third Charge" enhancement: +20% AD for 2 turns after kill (was 1 turn +15%) | 2/Campaign |
| Advanced | Kill a full-HP enemy champion while at disadvantage (HP<25%) | Permanent HP +150 + gain "Might of Noxus": once per combat, at 0 HP keep 1 HP and double AD next turn | 1/Campaign |

---

### 4.5.3 Ionia — Path of Spiritual Cultivation

Ionians trade **time and meditation** for inner strength.

| Cultivation Tier | Requirement | Effect |
|:--:|------|------|
| Basic | Spend 2 long rests in spiritual cultivation | Permanent MP +50 |
| Intermediate | Spend 4 long rests + visit 1 sacred site | Learn "Flash of Insight": once per chapter, instantly recover all cooldown of 1 consumed skill |
| Advanced | Spend 6 long rests + complete a spiritual trial (GM-designed) | Gain "Clear Mind": once per combat, foresee enemy's next-turn action (GM must tell truthfully) |

---

### 4.5.4 Freljord — Ancestral Blessing

Freljordians gain power through **resonance with ancestral spirits**.

| Blessing Tier | Requirement | Effect |
|:--:|------|------|
| Basic | Complete 1 rite at a tribal ground (spend 300 gold tribute) | Frost resistance from 50% to 75% |
| Intermediate | Defeat 1 Icefield Behemoth (GM-designed Boss fight) | Gain "Touch of the Iceborn": basic attacks add slow -1 (slowed targets -2), ignore frost terrain |
| Advanced | Find ancestral shrine + pass trial | Gain "Winter's Descent": once per combat, full-field frost storm, enemies Move Speed -2, ranged hit Disadvantage (lasts 2 turns) |

---

### 4.5.5 Shurima — Ascension Legacy

Shurimans unearth forgotten power in **ancient ruins**.

| Excavation Tier | Requirement | Effect |
|:--:|------|------|
| Basic | Successfully explore 1 ruin (DC18 Lore check) | Permanent AR +3, MR +3 |
| Intermediate | Decode 1 ancient stele (DC20 Lore + specific material) | Gain "Touch of the Sun": 10% chance basic attacks deal AP×0.3 magic damage |
| Advanced | Complete Ascension Trial ruin (multi-room dungeon) | Gain "Body of the Ascended": HP +200, size +25%, attack range +1 square |

---

### 4.5.6 Bilgewater — Bounty Hunting

Bilgewater folk grow strong through **bounties and plunder**.

| Hunt Tier | Requirement | Effect |
|:--:|------|------|
| Basic | Complete 1 bounty writ (GM-issued side objective) | Extra 300 gold (bounty) + 1 random consumable |
| Intermediate | Complete 3 bounty writs | Learn "Pirate's Intuition": advantage on Perception checks; 10% chance to evade single-target skill in combat (no roll) |
| Advanced | Kill 1 bounty Boss (high-difficulty single target) | Gain "Captain's Order": once per chapter, summon 1 pirate squad (3 melee + 2 ranged) to assist in combat |

---

### 4.5.7 Demacia — Lightshield Military Rank

Demacians gain resources and authority through **military merit promotion**.

| Rank | Requirement | Effect |
|:--:|------|------|
| Basic (Soldier) | Complete 1 military commission | Gain standard Demacian breastplate (AR+15, unsellable) |
| Intermediate (Officer) | Complete 3 commissions + lead 1 successful team quest | Learn "Rallying Cry": once per combat, whole party gains Advantage on next-turn hits |
| Advanced (General) | Make a key contribution in a large campaign | Gain "Wrath of the Lightshield": +20% damage to enemy mages; may conscript 1 Demacian squad (4 melee) |

---

### 4.5.8 Shadow Isles — Soul Pact

Shadow Isles folk make **pacts with the dead** — trading life for power.

| Pact Tier | Requirement | Effect | Price |
|:--:|------|------|------|
| Basic | Survive 3 days on the Shadow Isles (or equivalent narrative time) | Gain "Sight of the Dead": see stealthed units within 5 squares (no roll) | Max HP -10% (permanent) |
| Intermediate | Reach agreement with 1 named undead (narrative) | Learn "Soul Drain": killing an enemy restores 15% max HP | After each use, +25% light damage taken next turn |
| Advanced | Sacrifice 1 Legendary item (value ≥ 3,000 gold) | Gain 2× that item's attribute bonus (added directly to character, no slot) | Item permanently destroyed; character gains undead features in appearance |

---

### Regional Enhancement Numerical Balance Summary

| Region | System | Cost Type | Basic Effect (~350 gold equiv) | Advanced Effect (~2,500 gold equiv) |
|------|------|:--:|------|------|
| Piltover/Zaun | Hextech Forging | Gold + material | +3 attribute | +10 attribute + 1 Rare Augment |
| Noxus | Blood Trial | Combat achievement | AD+3/AP+4 | Near-death reversal = HP+150 + death immunity |
| Ionia | Spiritual Cultivation | Time (long rest) | MP+50 | Foresee enemy action |
| Freljord | Ancestral Blessing | Quest + tribute | 75% frost resist | Full-field frost storm |
| Shurima | Ascension Legacy | Exploration + Lore | AR/MR+3 | HP+200 + range+1 sq |
| Bilgewater | Bounty Hunting | Bounty quest | 300 gold + consumable | Summon pirate squad |
| Demacia | Lightshield Rank | Military commission | AR+15 breastplate | +20% vs mages + soldiers |
| Shadow Isles | Soul Pact | Life + equipment | Reveal stealth (-10% HP) | Item ×2 attributes (item destroyed) |

> **Design principle**: All regions' advanced enhancements take roughly 2-3 chapters of investment, ensuring a "hardship first, reward later" growth curve. Different cost types (gold/time/record/life) give each region a different play rhythm.

---

## 4.6 Party Framework (TRPG-specific)

| Framework | Player Relationship | Narrative Type | Typical Adventure |
|------|----------|----------|----------|
| **Pact of Fate** | Bound by a shared prophecy/mission | Epic hero | Stop the Rune Wars |
| **Mercenary Contract** | Bounty hunter / mercenary company | Grey morality | Escort a smuggler caravan |
| **Sanctuary** | Disaster survivors | Survival / rebuilding | Flee a fallen city |

### Four-Act Campaign Arc

| Act | Level | Theme | Narrative Function |
|:--:|:--:|------|----------|
| Act One | Lv.1-5 | Survival | Build bonds, discover the threat |
| Act Two | Lv.6-10 | Choice | Faction dilemma, moral quandary |
| Act Three | Lv.11-16 | Hero | Lead strength, turn the tide |
| Act Four | Lv.17-20 | Fate | Final showdown, world impact |

---

## 4.7 GM Toolkit

> GM running guide (four-beat rule, encounter design, MOBA narrative conversion), narrative rules (Fate Die, Background Tags, group decisions), enemy AI rules, difficulty adjustment quick reference, regional battlefield effects — see **`英雄聯盟TRPG_GM規則書.md`**.

### Quick Entry

| Need | Reference File | Chapter |
|------|------|------|
| How to run a 4-hour session | `gm_toolkit_v0.2.md` | Chapter Two |
| Encounter design / Boss fight principles | `gm_toolkit_v0.2.md` | Chapter Two |
| Narrative rules / Fate Die / Background Tags | `gm_toolkit_v0.2.md` | Chapter Three |
| Enemy AI behavior table / NPC templates | `gm_toolkit_v0.2.md` | Chapter Four |
| Difficulty adjustment / DC quick reference | `gm_toolkit_v0.2.md` | Chapter Five |
| Regional battlefield effects (8 regions) | `gm_toolkit_v0.2.md` | Chapter One |
| Intro module "White Wall Rift" | `adventures_campaign_v0.2.md` | Scenario #0 |
| Full campaign script (Lv.1-20) | `adventures_campaign_v0.2.md` | Main 4 parts + Side 4 parts |

---

# Appendices

## A. Glossary

| Abbr | English |
|:--:|------|
| AD | Attack Damage |
| AP | Ability Power |
| AS | Attack Speed |
| CDR | Cooldown Reduction |
| Crit | Critical Strike Chance |
| ArPen | Armor Penetration |
| MgPen | Magic Penetration |
| MS | Move Speed |
| MR | Magic Resistance |
| HP | Health Points |
| AR | Armor |
| Ten | Tenacity |
| DC | Difficulty Class |
| PB | Proficiency Bonus |
| TTK | Time To Kill |
| CC | Crowd Control |
| Dos | Degree of Success |

## B. Damage Formula Quick Reference

```
Physical damage = AD × 100/(100 + Armor − ArPen) × crit modifier
Magic damage    = AP × 100/(100 + MR − MgPen) × effect modifier
True damage     = raw value (ignores resistances)
Crit damage     = base × 175% (Infinity Edge: 210%)
```

## C. Check Formula Quick Reference

```
Skill check     = d20 + ability modifier + PB vs DC
Non-target skill = d20 + hit modifier vs 10 + MS modifier
Initiative      = d20 + AS modifier + AGI modifier
Crit            = d20 ≤ Critical Strike Chance × 20
Evasion DC      = 10 + MS modifier + evasion bonus
```

## D. Cooldown Quick Reference

```
10% CDR = -1 turn cooldown (minimum 1 turn)
CDR cap 40%
```

## E. Tenacity & Control

```
Actual duration = original duration × (1 − Tenacity%)
Not reduced by Tenacity: Knockup, Suppress, Sleep, Invulnerable
```

## E2. Status Effect Index

| Status | Effect | Auto-End Condition | Stackable? |
|------|------|------|:--:|
| Stun | Lose all actions | Duration ends | ✗ |
| Slow | MS -1~2 sq | Duration ends | ✗ |
| Root | Cannot move, can attack/cast | Duration ends | ✗ |
| Silence | Cannot cast, can attack/move | Duration ends | ✗ |
| Knockup | Lose all actions (uncleanseable) | 1 turn | ✗ |
| Suppress | Both sides lose all actions | Duration ends | ✗ |
| Blind | Basic attacks auto-miss | Duration ends | ✗ |
| Fear | Forced move away from source | Duration ends | ✗ |
| Immobilize | Cannot move/basic attack, can cast | Duration ends | ✗ |
| Disarm | Cannot basic attack, can move/cast | Duration ends | ✗ |
| Invulnerable | Immune to damage and CC | Duration ends | ✗ |
| Poison | HP% damage per turn | See §3.7.5 | ✓ (stacks) |
| Burn | Fixed damage per turn | Duration ends | ✓ (stacks) |
| Bleed | AD-proportion damage per turn | Duration ends | ✓ (stacks) |
| Grievous Wounds | Healing -40% | 3 turns | ✗ |
| Stealth | Cannot be selected as single target | Broken by attack/cast | ✗ |

## F. AS Frequency Quick Reference

```
0.50-0.99 → 1/turn (floor)
1.00-1.49 → 1/turn
1.50-1.99 → 3/2 turns
2.00+ → 2/turn
```

## G. Level Milestones

```
Lv.1  → Q/W/E choose 1
Lv.2  → Q/W/E choose 2
Lv.3  → Q/W/E complete
Lv.6  → R unlocks Lv.1
Lv.11 → R→Lv.2
Lv.16 → R→Lv.3
Lv.18 → Max level
```

## H. Character Sheet Template

```
◇══════════════════════════════════════════════◇
│ Name:___________  Archetype:___________  Lv:___  │
│ EXP:___/___      Gold:________               │
├──────────────────────────────────────────────┤
│ HP:____/____     MP:____/____                │
│ AD:___  AP:___   AS:___  Crit:___%           │
│ AR:___  MR:___   MS:___sq CDR:___%           │
│ ArPen:___   MgPen:___   Ten:___%             │
├──────────────────────────────────────────────┤
│ Talents                                           │
│ Core:______________________                      │
│ Sec1:________  Sec2:________  Sec3:________      │
│ Shards:________   ________   ________        │
├──────────────────────────────────────────────┤
│ Skills                                            │
│ Passive:_____________________________            │
│ Q(__/5):___________________________              │
│ W(__/5):___________________________              │
│ E(__/5):___________________________              │
│ R(__/3):___________________________              │
├──────────────────────────────────────────────┤
│ Summoner Spells                                  │
│ 1.______________  2.______________            │
├──────────────────────────────────────────────┤
│ Equipment                                        │
│ 1.________  2.________  3.________               │
│ 4.________  5.________  6.________               │
│ Boots:________  Trinket:________                │
├──────────────────────────────────────────────┤
│ Background Tags                                   │
│ Origin:________________                           │
│ Loyalty:________________                          │
│ Secret:________________                           │
◇══════════════════════════════════════════════◇
```

---

## I. Quick Creation Flow Card

```
□ Step 1: Choose archetype (Assassin/Warrior/Mage/Marksman/Support)
□ Step 2: Choose talents (primary 1 core+2 secondary, secondary 1 secondary, 3 shards)
□ Step 3: Choose starting skill (Q/W/E choose 1 at Lv.1)
□ Step 4: Choose 2 Summoner Spells
□ Step 5: Spend 500 gold on starting gear + potions
```

---

> **v0.2 Design Note**
> This ruleset is based on LoL S14 data conversion; basic attacks auto-hit to preserve MOBA feel, and non-targeted skill checks bring casting foresight to the tabletop. The talent tree uses LoL's primary/secondary/shard three-layer architecture; the equipment catalog covers AD/AP/tank/support four categories with 30+ items.
> Numerical balance has passed multi-scenario cross-validation (basic-attack TTK trend, ArPen effect, AS growth curve).
> The campaign mode supports level inheritance across chapters, equipment crafting upgrades, and fits long multi-chapter campaigns.
> **This is a beta ruleset**; we look forward to iterative improvement after real playtest feedback.