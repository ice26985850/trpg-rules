# Honkai: Star Rail TRPG Rulebook

> **Version**: v1.0  
> **Design**: TRPG Rules Studio  
> **Based on**: *Honkai: Star Rail* IP (HoYoverse)  
> **Recommended Level**: Moderate complexity; suitable for players with TRPG experience

---

## Table of Contents

- [Chapter One: Core Rules](#第一章核心規則)
  - [1.1 d20 Check System](#11-d20-檢定系統)
  - [1.2 Attribute System](#12-屬性體系)
  - [1.3 Skill System](#13-技能體系)
  - [1.4 Difficulty Class (DC): Difficulty Ladder](#14-難度等級dc-難度階梯)
  - [1.5 Energy and Ultimate System](#15-能量與終結技系統)
  - [1.6 Weakness Break System](#16-弱點擊破系統)
  - [1.7 Elemental Interaction System](#17-元素互動系統)
- [Chapter Two: Character Creation](#第二章角色創建)
  - [2.1 Character Creation Process](#21-創角流程)
  - [2.2 Origin](#22-出身)
  - [2.3 Identity](#23-身份)
  - [2.4 Path Class](#24-命途職業)
  - [2.5 Progression System](#25-成長系統)
- [Chapter Three: Combat and Conflict](#第三章戰鬥與衝突)
  - [3.1 Tactical Grid](#31-戰術棋盤)
  - [3.2 Action Economy](#32-動作經濟)
  - [3.3 Initiative and Turns](#33-先攻與回合)
  - [3.4 Attack and Damage](#34-攻擊與傷害)
  - [3.5 Weakness Break (Combat)](#35-弱點擊破戰鬥篇)
  - [3.6 Elemental Interaction Effects](#36-元素互動效果)
  - [3.7 Status Effects Compendium](#37-狀態效果大全)
  - [3.8 Optional Combat Rules](#38-戰鬥可選規則)
- [Chapter Four: World and Narrative](#第四章世界與敘事)
  - [4.1 Cosmology](#41-宇宙觀)
  - [4.2 Known Planets](#42-已知星球)
  - [4.3 Factions and Powers](#43-陣營勢力)
- [Appendix](#附錄)
  - [A. Glossary](#a-術語表)
  - [B. Quick Reference](#b-速查表)
  - [C. Character Sheet Template](#c-角色卡模板)

> **🛠 GM Tools**: monster building, encounter design, original planet creation, GM running guide, module templates, optional rules (Social Combat / Simulated Universe) → see **the *GM Guide*** (`崩壞星穹鐵道TRPG_GM規則書.md`)
>
> **💎 Equipment Codex**: Light Cone catalog (20+19+14 items), Relic catalog (18+14 sets), slot affixes, enhancement rules, GM distribution guidelines → see **the *Equipment Codex*** (`../assets/物品圖鑑.md`)
>
> **👹 Monster Manual**: pre-built monster data (26 enemies / 5 chapters), Challenge Rating (CR), weaknesses, Toughness, Experience Points (XP) → see **the *Monster Manual*** (`../assets/怪物圖鑑.md`)
>
> **✨ Spell Compendium**: 7 Paths' skill/Ultimate system, Talent nodes → see **the *Spell Compendium*** (`../assets/魔法圖鑑.md`)

---

# Chapter One: Core Rules

## 1.1 d20 Check System

### Core Formula

> **Check Result = d20 + ability modifier + Proficiency Bonus (if any) + other bonuses**

- **Success**: Check Result ≥ Difficulty Class (DC)
- **Failure**: Check Result < Difficulty Class (DC)
- **Critical success (natural 20 / crit)**: d20 rolls a 20 (natural 20), automatic success, and Margin of Success (MoS) is at least Tier 1
- **Critical failure (natural 1 / fumble)**: d20 rolls a 1 (natural 1), automatic failure, and produces a negative side effect

### Tiers of Success (Margin of Success)

Simulating the *Star Rail* "multi-hit attack" mechanic:

| Success Tier | Margin over Difficulty Class (DC) | Effect Multiplier | Example: Attack Check |
|-----------|-------------|---------|--------------|
| Tier 0 | 0–4 (just meets threshold) | ×1.0 | Base damage, 1 segment |
| Tier 1 | 5–9 (clear success) | ×1.25 | +1 segment of damage (2 segments total) |
| Tier 2 | 10–14 (excellent success) | ×1.5 | +2 segments of damage (3 segments total) |
| Tier 3 | 15–19 (brilliant success) | ×1.75 | +3 segments of damage (4 segments total) |
| Tier 4 | 20+ (legendary success) | ×2.0 | +4 segments of damage (5 segments total) |

**Margin of Success effects in skill checks**: Tier 0 achieves the basic goal; Tier 1 grants a secondary benefit; Tier 2 doubles the effect; Tier 3+ the GM may grant additional rewards at their discretion.

### Advantage / Disadvantage Mechanic

- **Advantage**: roll 2d20, take the higher
- **Disadvantage**: roll 2d20, take the lower
- **Cannot stack**; sources cancel out
- Equivalent mathematical effect: advantage ≈ +3.3 modifier, disadvantage ≈ −3.3 modifier

**Common sources of advantage**: tactically favorable position, target in a restricted state, ally assistance, attacking with the target's weakness element, specific Path abilities.  
**Common sources of disadvantage**: blocked line of sight, negative status, out of range, attacking with a non-weakness element/attribute.

---

## 1.2 Attribute System

### Six Core Attributes

| Attribute | Abbrev. | Core Influence |
|------|------|---------|
| **Strength (STR)** | STR | physical attack power, melee accuracy, carry weight, forced breakthrough |
| **Agility (AGI)** | AGI | Speed/Initiative, evasion/dodging, ranged accuracy, Finesse |
| **Constitution (CON)** | CON | Hit Points (HP) maximum, Defense (damage reduction), Toughness resistance, endurance |
| **Intellect (INT)** | INT | Energy Point (EP) recovery rate, Technology operation, knowledge/memory, strategy |
| **Perception (PER)** | PER | scouting/search, reading intentions, first-strike perception, tracking |
| **Charisma (CHA)** | CHA | social Persuasion, Resonance inspiration, Path connection, ally buffs |

### Attribute Score to Modifier Conversion

> **Modifier = floor((Attribute Score − 10) ÷ 2)**

| Attribute Score | 8-9 | 10-11 | 12-13 | 14-15 | 16-17 | 18-19 | 20-21 | 22-23 | 24-25 |
|--------|-----|-------|-------|-------|-------|-------|-------|-------|-------|
| Modifier | −1 | +0 | +1 | +2 | +3 | +4 | +5 | +6 | +7 |

Initial range 8-20 (modifier −1 to +5); at max level can reach 24+ (modifier +7+).

### Derived Attributes

| Derived Attribute | Formula |
|---------|------|
| Hit Points (HP) Maximum | base Hit Points (HP) + Constitution (CON) modifier × level + Path bonus |
| Initiative | Agility (AGI) modifier + Perception (PER) modifier + other bonuses |
| Evasion | 10 + Agility (AGI) modifier + equipment bonus |
| Defense (damage reduction) | Constitution (CON) modifier (minimum 0) |
| Energy Point (EP) Maximum | 100 (base; some Paths 120-200) |
| Energy Point (EP) Recovery | Intellect (INT) modifier × 5 (passive per round) |
| Carry Capacity (Carry) | Strength (STR) × 5 kg |

**Encumbrance Levels**:

| Encumbrance State | Condition | Penalty |
|---------|------|------|
| Light | ≤ Strength (STR) × 5 kg | None |
| Medium | ≤ Strength (STR) × 10 kg | Speed −2 squares, disadvantage on Agility (Acrobatics/Stealth) |
| Heavy | > Strength (STR) × 10 kg | Speed halved (minimum 2 squares), disadvantage on all Strength/Agility/Constitution checks, cannot use bonus action Dash |
| Overweight | > Strength (STR) × 15 kg | cannot move, disadvantage on all actions |

> **Simplified Rule** (optional): Do not track the weight of each item. The GM only requires a check when a character attempts to carry a clearly excessive amount of items.

---

## 1.3 Skill System (20 Skills)

### Strength Group (Strength (STR), 1 skill)
- **Athletics**: climbing, jumping, swimming, lifting, forced breakthrough

### Agility Group (Agility (AGI), 3 skills)
- **Acrobatics**: balance, roll-dodge, fall damage reduction
- **Stealth**: sneaking, hiding, tailing
- **Finesse**: lockpicking, trap disarming, pickpocketing

### Constitution Group (Constitution (CON), 1 skill)
- **Endurance**: resist extreme environments, poison/disease, breath-holding

### Intellect Group (Intellect (INT), 4 skills)
- **Technology**: operate terminals, hacking, mechanical repair
- **Lore**: Aeon knowledge, Path studies, ancient civilizations
- **Investigation**: search for clues, reasoning/deduction, code-breaking
- **Engineering**: build devices, modify weapons, demolition

### Perception Group (Perception (PER), 6 skills)
- **Perception (skill)**: spot hidden things, detect ambushes, recognize disguises
- **Insight**: judge lies, sense emotions, predict intentions
- **Survival**: foraging, navigation/tracking, taming creatures
- **Anticipation**: combat first-strike perception, identify enemy weaknesses
- **Animal Handling**: soothe, tame, ride alien creatures and mounts
- **Medicine**: first aid, stabilize wounds, diagnose abnormal states, battlefield medicine

### Charisma Group (Charisma (CHA), 5 skills)
- **Persuasion**: peaceful negotiation, bargaining, building friendly relations
- **Deception**: lying, disguise, distraction
- **Intimidation**: physical threats, psychological pressure, interrogation
- **Performance**: public speech, artistic performance, disguise roleplay
- **Resonance**: Path Resonance, sense Aeon will, inspire allies

### Proficiency Bonus Progression

| Character Level | 1-4 | 5-8 | 9-12 | 13-16 | 17-20 |
|---------|-----|-----|------|-------|-------|
| Proficiency Bonus (PB) | +2 | +3 | +4 | +5 | +6 |

---

## 1.4 Difficulty Class (DC): Difficulty Ladder

| Difficulty Class (DC) | Difficulty Label | Unskilled (+0) Success Rate | Skilled (+5) Success Rate | Master (+11) Success Rate |
|----|---------|-------------------|-----------------|------------------|
| 5 | Trivial | 80% | 100% | 100% |
| 10 | Simple | 55% | 80% | 100% |
| 12 | Slightly Hard | 45% | 70% | 95% |
| 15 | Moderate | 30% | 55% | 85% |
| 18 | Hard | 15% | 40% | 70% |
| 20 | Severe | 5% | 30% | 60% |
| 23 | Very Hard | 0% | 15% | 45% |
| 25 | Nearly Impossible | 0% | 5% | 35% |
| 28 | Legendary | 0% | 0% | 20% |
| 30 | Mythic | 0% | 0% | 10% |

> **Design Baseline**: Difficulty Class (DC) 15 is the standard moderate challenge; a skilled character (+5) has a 55% success rate.

---

## 1.5 Energy and Ultimate System

### Energy Maximum (Energy Point (EP), by Path)

| Path | Energy Maximum |
|------|---------|
| Standard (Hunt/Harmony/Nihility/Preservation) | 100 |
| Destruction | 120 |
| Erudition | 140 |
| Abundance | 120 |

### Energy Gain

| Action | Energy Gained |
|------|---------|
| Basic attack hits | +20 |
| Skill use | +30 |
| Being attacked | +5 (max +15 per round) |
| Killing an enemy | +10 |
| Weakness Break | +10 |
| Ally's Ultimate | +5 |
| Round start (passive) | + Intellect (INT) modifier × 5 |
| Ultimate release | resets to zero |

### Ultimate Release Rules

**Release Timing** (may be inserted after any action is declared, before the die roll):
- On your own turn: as a free action (does not consume an action)
- On an ally's turn: after the ally declares an action, before the die roll
- On an enemy's turn: after the GM declares the enemy's action, before the die roll

**Rules**:
- Each character may release an Ultimate only once per round
- When multiple characters declare simultaneously, resolution order is determined by Agility (AGI) modifier (higher first)
- Ultimates only consume Energy Point (EP), not Path resources

### Two-Layer Resource Structure

This ruleset uses a **two-layer resource system**:

| Layer | Name | Use | Acquisition | Design Owner |
|------|------|------|---------|---------|
| First Layer | **Energy Point (EP)** | Ultimate-exclusive | unified mechanic (attack/being hit/kill…) | Core Rules |
| Second Layer | **Path Resource** | Path-exclusive skills | each Path's exclusive mechanic | Character System |

The two resource layers are **tracked and consumed independently**, without interfering with each other.

### Ultimate Enhancement (Path Resource Synergy)

When releasing an Ultimate, you may **choose to consume Path resources** to enhance its effect:

| Path | Cost | Enhancement Effect |
|------|------|---------|
| Destruction | 5 Ardor stacks | Damage +3d8 |
| Hunt | 3 Focus | auto-critical against Prey |
| Erudition | 5 Inspiration | area radius +10m |
| Harmony | 8 Resonance stacks | whole party 2d6 temporary Hit Points (HP) |
| Nihility | target with 4 Marks | additionally apply 3 Marks |
| Preservation | 10 Fortitude | whole-party Shield (Fortitude ×3) |
| Abundance | 5 Life Seeds | group healing 3d8 |

> **Typical Energy Cycle**: A standard character (Intellect (INT) +2, Energy Point (EP) 100) can release an Ultimate about once every 3 rounds.

---

## 1.5a Rest, Recovery, and Death

### Short Rest

**Duration**: 1 hour of light activity (bandaging wounds, organizing equipment, drinking and eating).

**Effects**:
- Spend Hit Dice to recover Hit Points (HP): roll any number of Hit Dice (HD) + Constitution (CON) modifier per die
- Energy Point (EP) does not auto-recover (requires Energy items)
- May use healing potions (out-of-combat recovery +50%)
- Some Path resources partially recover (GM refers to each Path)

**Limit**: At most 2 short rests per day.

### Long Rest

**Duration**: 8 hours (at least 6 hours of sleep, the rest may be light watch or reading).

**Effects**:
- Hit Points (HP) recover to maximum
- Energy Point (EP) resets to zero (must accumulate from scratch)
- Recover half of spent Hit Dice (minimum 1)
- Path resources recover to initial value
- Reset daily-use limits (e.g. abilities "once per long rest")
- Remove 1 level of exhaustion

**Limit**: Only 1 long rest per 24 hours. A long rest must be taken in a safe environment (wilderness camping requires a Difficulty Class (DC) 12 Survival check to ensure safety).

### Hit Die (HD)

Hit Dice are used to recover Hit Points (HP) during short rests, and are also consumed by some Path abilities.

| Path | Hit Die (HD) Type | Gained per Level | Level 1 Base Hit Points (HP) |
|------|--------|---------|---------|
| Erudition | d6 | 1 per level | 6 + Constitution (CON) mod |
| Hunt/Harmony/Nihility/Abundance | d8 | 1 per level | 8 + Constitution (CON) mod |
| Destruction | d10 | 1 per level | 10 + Constitution (CON) mod |
| Preservation | d12 | 1 per level | 12 + Constitution (CON) mod |

### Hit Points (HP) Growth and Recovery Overview

| Scenario | Recovery Amount |
|------|--------|
| Short Rest (spend Hit Die (HD)) | per Hit Die (HD): die roll + Constitution (CON) modifier |
| Long Rest | Hit Points (HP) recover to maximum |
| Out-of-combat healing potion | recovery +50% (see Economy system, Chapter 6) |
| First Aid Kit | stabilize wounds or recover 1d4+2 Hit Points (HP) (5 uses) |
| Abundance Path healing | depends on Path ability |

### Dying and Death

When a character's Hit Points (HP) drop to 0:
1. The character enters the **Dying state** (Prone, unable to act, makes a death saving throw each round)
2. If Hit Points (HP) drop below negative of the maximum HP, the character **dies instantly**

**Death Saving Throw (Death Save)**:
- At the start of each round, roll d20 (no modifier unless a special ability applies)
- **10+**: 1 success; **9−**: 1 failure
- **Natural 20**: recover to 1 Hit Points (HP) and regain consciousness
- **Natural 1**: counts as 2 failures
- Accumulate **3 successes**: stabilized (no more death saves, but remains at 0 Hit Points (HP) and unconscious)
- Accumulate **3 failures**: character dies
- Taking any damage: automatic 1 failure (critical hit counts as 2)
- Healed to ≥1 Hit Points (HP): dying ends, normal action resumes

**After stabilization**: The character remains at 0 Hit Points (HP) and unconscious. After 1d4 hours, recovers to 1 Hit Points (HP) and regains consciousness. An ally may use a Difficulty Class (DC) 10 Medicine check to stabilize a dying character (no need to wait for death saves).

---

## 1.6 Weakness Break System

### Toughness Formula

> **Toughness = Base Toughness (by Challenge Rating (CR)) × type multiplier**

#### Base Toughness (by Challenge Rating (CR))

| Challenge Rating (CR) Range | Base Toughness | Enemy Type |
|---------|---------|---------|
| 0–1/2 | 20 | mobs, small monsters |
| 1–2 | 30 | standard soldiers, basic robots |
| 3–4 | 45 | enhanced soldiers, medium machinery |
| 5–7 | 60 | Elite enemies, heavy mechs |
| 8–10 | 80 | Elite commanders, ancient weapons |
| 11–13 | 100 | sub-Boss level |
| 14–16 | 130 | Boss level |
| 17–19 | 160 | high-tier Boss |
| 20+ | 200 | stellar organisms, Aeon emissaries |

#### Type Multiplier

| Type | Multiplier |
|------|------|
| Common (Normal) | ×1.0 |
| Elite | ×1.3 |
| Boss | ×1.6 |
| Summon | ×0.5 |

### Toughness Reduction

| Attack Type | Weakness Element Toughness Reduction | Non-Weakness Element Toughness Reduction | Physical Toughness Reduction |
|---------|------------|-------------|------------|
| Basic Attack | **−20** | −10 | **−15** |
| Skill | **−30** | −15 | **−20** |
| Ultimate | **−50** | −25 | **−35** |
| Bonus/Tier bonus (per level) | +10 | +5 | +8 |

> **Physical Attribute Special Rule**: Against non-weakness targets, Toughness reduction is not halved, fixed at 75% of the weakness value—reflecting Physical's "reliable, all-around" role.

### Break Effect (triggered when Toughness reaches 0)

- **Damage Boost**: all damage sources **+25%** (multiplicative)
- **Action Delay**: Initiative **−10**
- **Skip Turn**: if delayed past the current round, skip the current round
- **Broken Duration**: lasts until the enemy's next actual action begins
- **Break Special Effect**: triggers the corresponding element's Weakness Break special effect

### Toughness Recovery

- After the Broken state ends, Toughness recovers to full
- During Broken, if Toughness is reduced to ≤ 0 again, refresh the Broken duration
- After Elite/Boss's second Broken recovery, base Toughness ×1.2 (max ×1.6)
- Summons are destroyed immediately after being Broken

---

## 1.7 Elemental Interaction System

### Elemental Interaction Matrix (Difficulty Class (DC) reduction for checks)

| Using Element ↓ → Target | Physical | Fire | Ice | Lightning | Wind | Quantum | Imaginary |
|-------------------|------|----|----|----|----|------|------|
| **Physical** | — | — | — | — | — | −3 | — |
| **Fire** | — | — | −5 | — | — | — | — |
| **Ice** | — | −5 | — | — | −3 | — | — |
| **Lightning** | — | — | — | — | — | — | −3 |
| **Wind** | — | −3 | — | −3 | — | — | — |
| **Quantum** | −3 | — | — | — | — | — | −5 |
| **Imaginary** | — | — | — | — | — | −5 | — |

Values in the table are Difficulty Class (DC) reductions (favorable to the checker). "—" indicates no special interaction.

---

# Chapter Two: Character Creation

## 2.1 Character Creation Process

Character creation proceeds in the following six steps:

1. **Choose Origin** (8 choose 1) → gain attribute bonus + racial ability
2. **Determine Attributes** (27-point buy) → base 8-15 + Origin bonus
3. **Choose Path** (7 choose 1) → gain level 1 ability + Hit Die + proficiency
4. **Choose Identity** (8 choose 1) → gain starting resources + equipment + connections
5. **Choose Elemental Affinity** (primary element + secondary element) → choose from the 7 elements
6. **Starting Equipment** (Identity equipment pack + 3★ Light Cone + 200+1d4×50 Credit Points)

### Elemental Affinity Rules

The **primary element** and **secondary element** you choose at character creation determine your attack attribute and tactical style. This is the most core combat differentiation system of the Star Rail TRPG.

#### Basic Rules

| Rule | Description |
|------|------|
| **Attack Element** | Your basic attacks, skills, and Ultimates deal **primary element** damage by default |
| **Switch Secondary Element** | Once per combat, you may use a **bonus action** to switch attacks to the **secondary element** (lasts until end of combat or another switch) |
| **Physical Attribute Versatility** | If primary/secondary element is Physical, Toughness reduction against any target is **never discounted** (still 75% against non-weakness; see Combat chapter) |
| **Exploiting Elemental Weakness** | When attacking with the enemy's weakness element, the attack check gains **advantage** and Toughness reduction doubles |
| **Elemental Attach Effect** | On hitting an enemy, automatically applies the corresponding element's **normal attach effect** (see Element table in section 3.5) |
| **Elemental Resonance** | If an ally's attack element differs from yours but can trigger a Resonance combo, you may declare a "Coordinated Attack" (both spend a reaction) → triggers the Resonance effect and resolves using the higher attack bonus |

#### Elemental Affinity by Path

| Path | Available Primary Elements | Available Secondary Elements |
|------|----------|----------|
| Destruction | Physical, Fire | choose from the 6 elements other than primary |
| Hunt | Wind, Lightning | same as above |
| Erudition | Ice, Quantum | same as above |
| Harmony | Wind, Imaginary | same as above |
| Nihility | Lightning, Quantum | same as above |
| Preservation | Physical, Ice | same as above |
| Abundance | Wind, Imaginary | same as above |

> **Design Intent**: Each Path has 2 selectable primary elements + 6 freely combinable secondary elements, producing 12 element combinations. The secondary element switch limit (once per combat) ensures meaningful choice, but allies' Elemental Resonance combos (Fire+Lightning=Overload, Ice+Lightning=Superconduct, Wind+Fire=Swirl, Physical+Ice=Shatter) encourage tactical cooperation.

#### Element Selection Strategy

| Strategy | Approach | Advantage | Risk |
|------|------|------|------|
| **Counter Type** | Primary element aligned to expected enemy weakness | attack advantage + doubled Toughness reduction | weak against resistant enemies |
| **Versatile Type** | primary Physical, secondary a countering element | Physical never at disadvantage + targeted secondary element | Toughness reduction efficiency lower than dual-weakness |
| **Resonance Type** | choose Resonance combos with allies | high Coordinated Attack burst | depends on team coordination |
| **Control Type** | primary Ice/Imaginary | high control (Slow/Imprison) | damage-type enemies may require burst |

#### Example: March 7th's Element Use

> March 7th chooses **primary element = Ice**, **secondary element = Wind**.  
> Against an Ice-weak Fragmentum Phantom: uses primary element (Ice) → attack advantage, Toughness reduction −20 (weakness), applies Freeze + Slow.  
> Against a Fire-construct with Ice resistance: spends a bonus action to switch to secondary element (Wind); subsequent attacks become Wind-attribute.  
> Ally Dan Heng (Wind) on the field: March 7th uses Ice + Dan Heng uses Wind → no Resonance combo (Ice+Wind not in the Resonance table), cannot coordinate.

### Attribute Point-Buy Cost Table (27 points)

| Attribute Score | Cost | Attribute Score | Cost |
|--------|------|--------|------|
| 8 | 0 | 12 | 4 |
| 9 | 1 | 13 | 5 |
| 10 | 2 | 14 | 7 |
| 11 | 3 | 15 | 9 |

---

## 2.2 Origin (Innate Attributes)

Origin represents a character's **innate traits**—bloodline, species, cultural roots. It provides attribute bonuses and racial special abilities.

| Origin | Attribute Bonus | Core Ability |
|------|---------|---------|
| **Belobogian** | +2 CON, +1 STR | Iron Will (advantage vs Fear/Charm), Builder's Bloodline (advantage with artisan tools), Eternal Winter Walker (Ice damage reduction) |
| **Xianzhou Native** | +2 AGI, +1 PER | Sword Heart Clarity (critical 19-20 with swords), Millennia Cultivation (4h meditation = long rest), Cloud Knight Tactics (mark enemy) |
| **Stellaron Resonator** | +2 CHA, +1 CON | Stellaron Resonance (sense Stellarons, release 1d6 random element), Chaos Adaptation (immune to Stellaron environments), Hunter Instinct (advantage on tracking) |
| **Corporate Citizen** | +2 INT, +1 CHA | Commercial Privilege (+500 Credit Points / +2 Persuasion), Data Analysis (bonus analysis +1d4 to hit), Standardized Training (advantage with tech tools) |
| **Trailblazer Descendant** | +1/+1/+1 (any three) | Star Track Walker (extra swappable skill proficiency), Citizen of the World (advantage on first encounter Charisma), Trailblaze Mark (leave message mark) |
| **Mechanical Lifeform** | +2 INT, +1 CON | Construct Resistance (immune to disease/poison, no need to eat/drink/breathe), Precision Calculation (after failure, +1d4 remedy), Modular Design (Armor Class (AC) 13+AGI / swappable modules) |
| **Void Child** | +2 PER, +1 CHA | Imaginary Sense (sense life within 30m), Fate Weaving (reaction ±2 to others' checks), Void Walk (survive vacuum / 15m teleport) |
| **Legion Defector** | +2 STR, +1 AGI | Destruction Embers (1 min Destruction mode +2 damage +3× critical), Combat Modification (60m darkvision / unarmed 1d4), Defector's Intuition (Initiative +2 / can still react when ambushed) |

---

## 2.3 Identity (Acquired Role)

Identity represents a character's **social role**—profession, organizational background, network resources. It provides starting resources, equipment packs, and connection networks.

| Identity | Starting Equipment Pack | Starting Resources | Connections |
|------|----------|---------|------|
| **The Nameless** | Star Track Communicator, Trailblazer Backpack, Basic Survival Kit | 300 Credit Points + Astral Express Pass | Nameless network, contact points on each planet |
| **Stellaron Hunter** | Stellaron Detector, Shadow Cape, Intel Chip | 500 Credit Points + bounty contract ×1 | underground intelligence network, client network |
| **IPC Employee** | Corporate Terminal, Commercial License, Data Analyzer | 1,000 Credit Points + company credit line | IPC commercial network, interstellar branches |
| **Free Adventurer** | Multi-tool Kit, Mercenary License, First Aid Kit | 200 Credit Points + wanted poster ×2 | Adventurer's Guild, employer contacts |
| **Genius Society Researcher** | Research Terminal, Sample Collector, Appraisal Tools | 400 Credit Points + research fund | Society library, academic network |
| **Xianzhou Cloud Knight** | Cloud Knight Light Armor, Standard Longsword, Commune Talisman | 300 Credit Points + military rank proof | Cloud Knight intelligence network, Xianzhou Six Offices |
| **Sea-Ranger** | Revolver Cannon, Ranger Coat, Bounty Terminal | 400 Credit Points + wanted notice ×3 | Sea-Ranger network, Bounty Hunter Guild |
| **Masked Fool** | Disguise Kit, Trick Props, Fool's Mark | 250 Credit Points + tavern "favor" ×1 | regular at the World's End Tavern, underground Pleasure cult network |

### Identity Equipment Item Table

| Item | Source Identity | Type | Description |
|------|---------|------|------|
| **Star Track Communicator** | The Nameless | Communication Tool | A communication device exclusive to the Astral Express, capable of transmitting text and voice messages across star systems. Includes Star Track positioning, sensing the direction of the nearest Star Track. Communication range is affected by Star Track density; remote star regions may experience delay or interruption |
| **Trailblazer Backpack** | The Nameless | Storage | A multi-purpose backpack strengthened by Star Track energy; interior space is 1.5× larger than its exterior. Comes with a basic environmental isolation layer protecting contents from extreme temperature and humidity. Carry Capacity +10kg |
| **Basic Survival Kit** | The Nameless | Tool Set | Contains flint, water-purifying capsules ×10, universal rope 30m, emergency rations ×5, simple tent. Meets basic survival needs in the wild. Consumes 1 ration and 1 purifying capsule daily |
| **Astral Express Pass** | The Nameless | Document | A token granting access to the Astral Express. Any holder may summon the train at any Star Track node; travel costs are covered by the Nameless organization. Non-transferable; lost passes require 1 week to reissue |
| **Stellaron Detector** | Stellaron Hunter | Detection Device | Can sense Stellaron energy fluctuations within 500m. As you approach a Stellaron, it emits a pulse of increasing frequency—the closer, the more rapid. Sensitivity to dormant Stellarons is halved |
| **Shadow Cape** | Stellaron Hunter | Clothing | A lightweight optical-camo cape. When activated, provides 10 minutes of visual concealment (advantage on Stealth checks), cooldown 1 hour. Ineffective against thermal sensing and Stellaron energy scans |
| **Intel Chip** | Stellaron Hunter | Data Storage | An encrypted storage device containing read-only access to the Stellaron Hunters' shared database—known Stellaron locations, bounty rates, client reviews. Insert into any standard terminal to read; data updates daily |
| **Corporate Terminal** | IPC Employee | Communication/Commercial | A multi-function handheld terminal standard-issued by the IPC. Can make interstellar transfers, view internal corporate announcements, access the commercial database (commercial-related Knowledge check +2). Includes credit-line query function |
| **Commercial License** | IPC Employee | Document | A general trade permit issued by the Interastral Peace Corporation. Within IPC-controlled star regions, permits legal cross-planet trade with basic tax reductions. Cannot be forged; includes biometric identification |
| **Data Analyzer** | IPC Employee | Analysis Tool | A portable market-analysis device. Scanning goods yields the current interstellar market estimate (±15% error). Bonus analysis: once per short rest, grants +1d4 to the next commercial-related check |
| **Multi-tool Kit** | Free Adventurer | Tool Set | Universal repair/disassembly tools, including wrench set, welding gun, screwdriver set, circuit tester. Usable for simple mechanical repair or field modification. Without parts, only emergency measures possible |
| **Mercenary License** | Free Adventurer | Document | A general mercenary qualification certificate issued by the Adventurer's Guild. Can accept bounty missions at guild branches on major planets; reputation affects mission tier available. Initially issued at "Bronze" tier |
| **First Aid Kit** | Free Adventurer | Medical | Contains tourniquet, disinfectant spray, burn gel, painkiller syringes ×3, bandage roll. After use, can stabilize a character's wounds (stop bleeding/poisoning and other ongoing damage), or recover 1d4+2 Hit Points (HP). 5 total uses |
| **Research Terminal** | Genius Society Researcher | Communication/Research | An academic terminal issued by the Genius Society. Can access the Society paper library (Lore check +2), submit research reports, and collaborate remotely with other researchers. Includes basic sample analysis |
| **Sample Collector** | Genius Society Researcher | Collection Tool | A portable device that safely collects and seals biological/mineral/energy samples. Self-contained vacuum seal and temperature control; sealed samples stay stable for 30 days. Seals 3 samples per use; reusable after replacing the cartridge |
| **Appraisal Tools** | Genius Society Researcher | Analysis Tool | A multi-function material analysis kit, including handheld spectrometer, micro-microscope, chemical reagent set. Can preliminarily identify unknown substances' composition and age on-site. Full analysis takes 10 minutes; simple test takes 1 action |
| **Cloud Knight Light Armor** | Xianzhou Cloud Knight | Armor | Standard light armor of the Xianzhou Cloud Knights. Armor Class (AC) 13 + Agility modifier (max +3), provides Ice damage reduction 1. Chest bears the Cloud Knight insignia, serving as a pass within Xianzhou territory |
| **Standard Longsword** | Xianzhou Cloud Knight | Weapon | Standard-issue Cloud Knight sword, forged from Xianzhou alloy. 1d8 slashing damage, Finesse property (may use Strength or Agility modifier for attack checks). +1 to hit against Ice-weakness targets |
| **Commune Talisman** | Xianzhou Cloud Knight | Communication Tool | A communication talisman empowered by Xianzhou arts, can instantly transmit brief messages (within 20 characters) within the same planet. After the talisman is burned, the message is sent; the recipient's talisman synchronously self-ignites and displays the text. 5 total; replenishable at Xianzhou |
| **Revolver Cannon** | Sea-Ranger | Weapon | A large-caliber handheld cannon combining a revolver's portability with a small cannon's destructive power. 1d10 piercing damage, 6-round magazine, reload is 1 move action. Medium range; disadvantage at close range. Includes 24 spare bullets |
| **Ranger Coat** | Sea-Ranger | Clothing | A specially treated long coat, windproof, dustproof, and durable. Multiple hidden inner pockets (safe stowage of small items); outer layer bears the Sea-Ranger emblem—serves as identification in the bounty hunter community. No Armor Class (AC) bonus, but provides movement relief in harsh weather like sandstorms/acid rain |
| **Bounty Terminal** | Sea-Ranger | Communication/Mission | A portable terminal exclusive to the Sea-Ranger network. Can instantly view interstellar wanted notices, update prey status, and exchange intel with other rangers. After completing a bounty, claim rewards via the terminal; Credit Points transfer directly to the bound account |
| **Disguise Kit** | Masked Fool | Tool Set | Contains moldable masks ×3, color-changing dye, voice-changing throat-mic, fake beard/wig sets ×2 each. Disguising takes 5 minutes; upon completion grants advantage on Deception (disguise) checks. Masks are single-use; cannot be restored once removed |
| **Trick Props** | Masked Fool | Tool Set | Masked Fool entry-level "Performance" tools: smoke bombs ×3, flash cards, extendable bouquet, fake-blood capsules ×5, remote noise-maker. Though they look like toys, in the hands of an experienced Fool they may produce unexpected tactical effects (at GM discretion) |
| **Fool's Mark** | Masked Fool | Token | An unremarkable metal badge whose pattern subtly changes each time it is flipped. Other Masked Fools instantly recognize the bearer as "one of us." Presenting the mark at the World's End Tavern grants a free first drink—the number of drinks is proportional to the bartender's mood |

> **Design Note**: Identity equipment items are starting gear unique to that Identity. Common items (rope, torches, ordinary weapons, etc.) may be purchased separately by characters using Credit Points; the GM may reference the D&D 5e equipment table or set their own prices. If an Identity-exclusive item is lost during an adventure, it usually must be replaced or remade at a stronghold of the corresponding faction.

---

## 2.4 Path Classes

### Path Overview

| Path | Hit Die (HD) | Primary Attribute | Energy Point (EP) Cap | Core Resource | Role | Elemental Affinity |
|------|-----|--------|--------|------|------|---------|
| **Destruction** | d10 | STR/CON | 120 | Ardor stacks | Frontline damage / semi-tank | Physical, Fire |
| **Hunt** | d8 | Agility (AGI) | 100 | Focus | Ranged single-target burst | Wind, Lightning |
| **Erudition** | d6 | Intellect (INT) | 140 | Inspiration | Area spellcaster | Ice, Quantum |
| **Harmony** | d8 | Charisma (CHA) | 100 | Resonance stacks | Team-buff support | Wind, Imaginary |
| **Nihility** | d8 | Intellect (INT) | 100 | Nihility Mark | DoT / debuff control | Lightning, Quantum |
| **Preservation** | d12 | STR/CON | 100 | Fortitude | Tank / shield | Physical, Ice |
| **Abundance** | d8 | Perception (PER) | 120 | Life Seed | Healing / cleanse | Wind, Imaginary |

### Destruction

**Core Mechanic: Ardor stacks** — The lower your Hit Points (HP), the more stacks you gain; each stack adds +1–3 damage (scales with level).

| Level | Ability |
|------|------|
| 1 | Ardor Surge, Destruction Strike (spend Ardor +1d8/stack) |
| 2 | Fighting Style (Great Weapon / Two-Weapon / Defense / Reckless), Unyielding Will |
| 3 | Talent first node (Bloodthirsty Frenzy / Pain Resonance / Iron Physique — choose one) |
| 5 | Extra Attack, Ardor Empower (15%/stack, 6-stack cap, +2/stack) |
| 7 | Talent second node (Flesh Sacrifice / Destruction Ripple / Unyielding Bastion — choose one) |
| 9 | Destruction Aura (enemies within 10m take −1 Armor Class (AC)) |
| 10 | Ardor Empower II (10%/stack, 10-stack cap) |
| 11 | Talent third node (Life Furnace / Destruction Storm / Death Denial — choose one) |
| 13 | Phoenix Heart (at 0 Hit Points (HP), restore half HP) |
| 14 | Extra Attack (2) |
| 15 | Talent fourth node (Collapse Herald / Eternal Wrath / Terminator — choose one) |
| 17 | Ardor Maximum (15 stacks, +3/stack) |
| 18 | Destruction Avatar (at 8+ stacks, crit range −2, extra 1d6 Fire damage) |
| 19 | Talent fifth node |
| 20 | Final Advent (1 minute of full Ardor + control immunity + extra attack action) |

#### Destruction Talent Node Details

**Lv 3 — First Node (choose one of three)**
| Talent | Effect |
|------|------|
| **Bloodthirsty Frenzy** | When Ardor stacks ≥3, melee attack damage +2 |
| **Pain Resonance** | When you take damage, the attacker takes 25% of that damage (psychic damage, no save) |
| **Iron Physique** | When Hit Points (HP) below 50%, Armor Class (AC) +2, damage reduction +1 |

**Lv 7 — Second Node (choose one of three)**
| Talent | Effect |
|------|------|
| **Flesh Sacrifice** | Spend 10 Hit Points (HP) (unreducible) → next attack +2d6 damage, crit range 18–20 |
| **Destruction Ripple** | When you kill an enemy, all enemies within 5 squares must make a Constitution (CON) saving throw at Difficulty Class (DC) 13 or take 50% of the overflow damage |
| **Unyielding Bastion** | Once per short rest: when you would take lethal damage, instead drop to 1 Hit Points (HP) |

**Lv 11 — Third Node (choose one of three)**
| Talent | Effect |
|------|------|
| **Life Furnace** | Add Constitution (CON) modifier to damage calculations (melee attacks only) |
| **Destruction Storm** | Your Ultimate deals half damage to all enemies within 10m |
| **Death Denial** | When Hit Points (HP) reach 0, immediately trigger a free Destruction Strike (no action cost), then enter Dying |

**Lv 15 — Fourth Node (choose one of three)**
| Talent | Effect |
|------|------|
| **Collapse Herald** | On Weakness Break, deal an extra 2d10 typeless damage to the target |
| **Eternal Wrath** | Ardor stacks no longer decay from leaving combat |
| **Terminator** | Attacks against targets with Hit Points (HP) <25% have automatic advantage, crit range +2 |

**Lv 19 — Fifth Node (choose one of three)**
| Talent | Effect |
|------|------|
| **Nanook's Gaze** | Once per long rest: for 1 minute, your attacks ignore the target's resistances and immunities |
| **Universal Collapse** | When your Ultimate hits, reduce the target's Toughness by −80 (replacing the original Break efficiency) |
| **Undying Wargod** | While Dying, death saving throw Difficulty Class (DC) drops to 8; a natural 18+ restores 25% Hit Points (HP) |

### Hunt

**Core Mechanic: Focus** — Lock onto prey, spend Focus to unleash Precision / Vital / Soul-Chase / Hamstring.

| Level | Ability |
|------|------|
| 1 | Prey Lock, Focused Shot (advantage on attacks vs. prey 1/round) |
| 2 | Hunt Step (Speed +3m + bonus Disengage/Dash), Sniper's Intuition |
| 5 | Extra Attack, Focus capacity expanded to 6 |
| 9 | Windwalker (bonus teleport 15m, Agility (AGI) modifier times per short rest) |
| 10 | Killing Blow (Vital Snipe +4d6, regain 1 Focus on crit) |
| 13 | Dual Lock (2 prey simultaneously) |
| 14 | Extra Attack (2) |
| 17 | Heartseeker (ignores full cover, Vital +6d6) |
| 18 | Eye of Death (prey with Hit Points (HP) <50% take maximum damage) |
| 20 | Arrow of the Aeon (auto-hit guaranteed crit 10d10, ignores resistance and immunity / long rest) |

#### Hunt Talent Node Details

**Lv 3 — First Node (choose one of three)**
| Talent | Effect |
|------|------|
| **Precision Shot** | Aim action (expend movement) → next ranged attack +3 to hit |
| **Ranger's Footwork** | Do not suffer ranged disadvantage from enemies within 5 squares |
| **Wind's Favor** | Movement Speed +2 squares, Initiative +3 |

**Lv 7 — Second Node (choose one of three)**
| Talent | Effect |
|------|------|
| **Piercing Arrow** | Attacks ignore half cover and soft cover |
| **Arrow Rain** | Once per short rest: make one ranged attack against a 10m burst area (normal attack roll) |
| **Formless Hunter** | When attacking a target that has not detected you, damage dice take maximum value |

**Lv 11 — Third Node (choose one of three)**
| Talent | Effect |
|------|------|
| **Aeon's Gaze** | Marking prey no longer costs a bonus action (becomes a free action) |
| **Death Mark** | Crit range vs. prey 17–20 |
| **Quantum Arrow** | Ranged attacks may choose to deal Quantum damage (twice per short rest) |

**Lv 15 — Fourth Node (choose one of three)**
| Talent | Effect |
|------|------|
| **Final Arrow** | Your Ultimate is guaranteed to crit against prey |
| **God of the Hunt** | Focus cap +3, automatically gain 1 point each round |
| **Infinite Quiver** | Common arrows no longer consumed (special arrows such as explosive arrows still consumed normally) |

### Erudition

**Core Mechanic: Inspiration** — Used to amplify / spread / pierce / quick-cast spells.

| Level | Ability |
|------|------|
| 1 | Inspiration Casting, Knowledge Burst (2d6 / 3m range / Agility (AGI) save) |
| 5 | Element Specialization I (choose Ice or Quantum, +1/die + Difficulty Class (DC) +1) |
| 6 | Knowledge Burst Empower (3d6 / 5m range) |
| 10 | Element Specialization II (second specialization or double the original) |
| 13 | Quantum Entanglement (targets hit by area spells become linked → disadvantage on next save) |
| 14 | Group Amplify (1 Inspiration amplifies all targets +1d6) |
| 17 | Cataclysm (5 Inspiration / 20m radius / 10d8 / long rest) |
| 18 | Nous's Gaze (1 minute / Inspiration cost halved / range doubled / long rest) |
| 20 | Cosmic Truth (immune to 1 element / ignores resistance / half damage vs. immune) |

#### Erudition Talent Node Details

**Lv 3 — First Node (choose one of three)**
| Talent | Effect |
|------|------|
| **Light of Nous** | Lore / Investigation / Technology checks +2 |
| **Energy Efficiency** | Energy Point (EP) recovery +5/round |
| **Area Specialization** | Area spells may choose to exclude 1 friendly target |

**Lv 7 — Second Node (choose one of three)**
| Talent | Effect |
|------|------|
| **Overload Calculation** | Once per long rest: combat technique damage dice take maximum value |
| **Multiple Projection** | Single-target spell may spend 1 Inspiration to also affect 1 adjacent additional target |
| **Knowledge Is Power** | Add Intellect (INT) modifier to all damage calculations (not limited to spells) |

**Lv 11 — Third Node (choose one of three)**
| Talent | Effect |
|------|------|
| **Foresight Calculation** | Once per battle: declare a number (1–20); if any d20 that round rolls that number, you may substitute it as your result |
| **Energy Torrent** | Inspiration cap +5 |
| **Element Master** | May choose two element attacks (chosen from Ice / Fire / Lightning / Quantum; changeable after Lv 5) |

**Lv 15 — Fourth Node (choose one of three)**
| Talent | Effect |
|------|------|
| **Eye of Truth** | Automatically see through illusions / Invisible; puzzles at Difficulty Class (DC) 20 or below require no roll |
| **Final Calculation** | Your Ultimate may instead target a single 50m target (original area damage converted to 2× single-target) |
| **Nous's Resonance** | Once per long rest: the GM must answer a yes/no question about the current adventure |

### Harmony

**Core Mechanic: Resonance stacks** — Link allies to build stacks, used for buffs / shields / coordination.

| Level | Ability |
|------|------|
| 1 | Resonance Weave, Inspiring Voice (1d6 to any d20 / Proficiency Bonus (PB) times / short rest) |
| 2 | Touch of Harmony (spend Resonance stacks to heal), Teamwork |
| 5 | Resonance Amplify I (stacks doubled / max links +1) |
| 6 | Inspiring Voice Empower (1d8 / Proficiency Bonus (PB) ×2 times) |
| 9 | Mind Link (telepathy + sense sharing) |
| 10 | Resonance Amplify II (cap doubled / Harmony Amplify 1d6) |
| 13 | Resonance Burst (10 stacks / 6d6 sonic / allies regain half HP) |
| 14 | Eternal Harmony (retain Resonance stacks after battle) |
| 17 | Grand Chorus (15 stacks / all linked allies gain 1 minute of attack advantage + Armor Class (AC) +2 + 5 Hit Points (HP) per round) |
| 20 | Universal Harmony (100m infinite links 1 minute + infinite Resonance stacks / long rest) |

#### Harmony Talent Node Details

**Lv 3 — First Node (choose one of three)**
| Talent | Effect |
|------|------|
| **Harmony Resonance** | Number of linked allies +1 |
| **Inspiration Master** | When granting an ally advantage, also grant 1d4 temporary Hit Points (HP) |
| **Rhythm Sense** | Initiative checks may use Charisma (CHA) in place of Agility (AGI) |

**Lv 7 — Second Node (choose one of three)**
| Talent | Effect |
|------|------|
| **Duet** | Inspiring Voice may affect 2 allies simultaneously |
| **Defensive Chord** | Linked allies gain Armor Class (AC) +1 |
| **Accelerando** | Once per battle: a linked ally gains an extra bonus action next round |

**Lv 11 — Third Node (choose one of three)**
| Talent | Effect |
|------|------|
| **Collective Will** | When any linked ally succeeds on a save → other linked allies may use that result as their own save (once per short rest) |
| **Resonance Spread** | When gaining Resonance stacks, 50% chance to gain 1 extra stack |
| **Mental Chorus** | At long rest, choose one skill; for the day, all linked allies gain proficiency in that skill |

**Lv 15 — Fourth Node (choose one of three)**
| Talent | Effect |
|------|------|
| **Symphony Movement** | Your Ultimate may simultaneously trigger all linked allies' Ultimate effects (teammates' Energy Point (EP) consumed normally) |
| **Eternal Melody** | Resonance stacks no longer decay from leaving combat |
| **Xipe's Blessing** | Once per long rest: for 1 minute, the whole party adds your Charisma (CHA) modifier to all saving throws |

### Nihility

**Core Mechanic: Nihility Mark** — Build stacks to reduce Armor Class (AC) / saving throws, can detonate / spread / withering aura.

| Level | Ability |
|------|------|
| 1 | Erosion, Touch of Nihility (1d8 + INT / applies 1 Mark) |
| 2 | Withering Aura (marked targets within 10m take stack damage each round), Shadow Step |
| 5 | Erosion Empower I (6-stack cap / AC & save penalty cap −4) |
| 9 | Spreading Despair (when a marked target dies → transfer all stacks) |
| 10 | Erosion Empower II (detonate 3d6/stack / spread transfers all) |
| 13 | Entropy Increase (3+ stacks each round Constitution (CON) save → exhaustion) |
| 14 | Eternal Erosion (Marks persist) |
| 17 | Nihility Domain (20m radius / auto 1 stack each round / long rest) |
| 18 | IX's Gaze (5 stacks + Fear / long rest) |
| 20 | Heat Death (100m / Mark stacks ×10 Hit Points (HP) / no save, no reduction / long rest) |

#### Nihility Talent Node Details

**Lv 3 — First Node (choose one of three)**
| Talent | Effect |
|------|------|
| **Abyss Gaze** | Marked target's saves −1 (stacks with original penalty) |
| **Shadow Spread** | When applying a Mark, another enemy within 3 squares also gains 1 stack |
| **Nihility Resilience** | Advantage on psychic damage and Charm / Fear saves |

**Lv 7 — Second Node (choose one of three)**
| Talent | Effect |
|------|------|
| **Pain Echo** | When a marked target takes damage, it additionally takes 1d4 psychic damage |
| **Withering Acceleration** | Withering Aura damage +1d4 |
| **Nihility Step** | Once per battle: teleport 10 squares as a bonus action |

**Lv 11 — Third Node (choose one of three)**
| Talent | Effect |
|------|------|
| **Entropy Acceleration** | Entropy Increase triggers at 2+ stacks (originally 3) |
| **Despair Chain** | When detonating a Mark, chain damage range expands from adjacent to 5 squares |
| **Touch of IX** | Once per long rest: all Marks on a single target trigger immediately (as if detonated), costs no action |

**Lv 15 — Fourth Node (choose one of three)**
| Talent | Effect |
|------|------|
| **Nihility Domain** | Enemies within 10m automatically gain 1 Mark stack each round (lasts 1 minute / long rest) |
| **Existence Erasure** | When killing a marked target, restore 10 Energy Point (EP) |
| **Nihility Avatar** | Immune to Charm / Fear / Confusion; once per long rest, immune to one instant-death effect |

### Preservation

**Core Mechanic: Fortitude** — Generate shields to absorb damage (Fortitude ×2–3), blocking attacks.

| Level | Ability |
|------|------|
| 1 | Builder's Wall, Guardian Strike (generate shield on hit) |
| 2 | Taunt Roar (15m Perception save / attacking anyone but you is at disadvantage), Bedrock Body |
| 5 | Extra Attack, Shield Empower (Fortitude ×3, max shield +1) |
| 6 | Reflect Shield (reflect damage equal to Constitution modifier when hit) |
| 9 | Guardian Aura (allies within 5m take 2 less damage / active shield +2m range) |
| 10 | Unbreakable (shield blocks any damage / Iron Bastion reduces damage by CON + Proficiency) |
| 13 | Reflection Barrier (reflect damage ×2 / triggers when own shield is hit) |
| 14 | Extra Attack (2) |
| 17 | Fortress Mode (Speed halved + damage halved + all resistances + 30m Taunt / long rest) |
| 18 | Qlipoth's Forge (immune to crits / 50% shield at no cost) |
| 20 | Unfallen City (at 0 Hit Points (HP) → 1 Hit Points (HP) + full shield / once per long rest per target) |

#### Preservation Talent Node Details

**Lv 3 — First Node (choose one of three)**
| Talent | Effect |
|------|------|
| **Reinforced Shield** | Shield value +25% (Fortitude ×2.5–3.75) |
| **Bedrock Reflection** | When hit in melee, reflect damage equal to Constitution (CON) modifier |
| **Guardian Aura** | Allies within 3 squares gain Armor Class (AC) +1 |

**Lv 7 — Second Node (choose one of three)**
| Talent | Effect |
|------|------|
| **Taunt Roar Empower** | Taunt range expands to 25m, Difficulty Class (DC) +2 |
| **Shield Burst** | May actively detonate your own shield → enemies within 10m must make a Constitution (CON) saving throw at Difficulty Class (DC) 13 or take damage equal to 50% of shield value |
| **Unyielding** | When Hit Points (HP) <25%, gain a temporary shield equal to Fortitude (once per long rest) |

**Lv 11 — Third Node (choose one of three)**
| Talent | Effect |
|------|------|
| **Bastion** | Self Armor Class (AC) +1 (stacks with armor / shield), Movement Speed −1 square |
| **Shared Guard** | May transfer 50% of your shield to any ally within 5 squares (bonus action) |
| **Reflection Barrier Empower** | Reflect damage becomes Constitution modifier ×3 |

**Lv 15 — Fourth Node (choose one of three)**
| Talent | Effect |
|------|------|
| **Qlipoth's Wall** | Once per long rest: for 3 rounds, all allies within 15m radius gain Armor Class (AC) +3, damage reduction = Constitution (CON) mod |
| **Eternal Guardian** | Fortitude cap +5 |
| **Unbreakable Shield** | When shield is broken, overflow damage halved |

### Abundance

**Core Mechanic: Life Seed** — After sowing, use Bloom for healing / cleanse / protect / vitality.

| Level | Ability |
|------|------|
| 1 | Life Seed, Touch of Abundance (1 seed / 1d8 + PER / single-target heal) |
| 2 | Natural Regeneration (extra 1d6 at short rest), Hand of Purification (remove disease / Poisoned) |
| 5 | Life Seed Empower I (+2 seeds / 1d10 / 2 seeds on same target) |
| 6 | Abundance Aura (15m / 1 Hit Points (HP) per round / with seed 1d4 + PER) |
| 9 | Group Bloom (affects all seeded targets simultaneously) |
| 10 | Life Seed Empower II (+2 seeds / 1d12 / seeds last until long rest) |
| 13 | Flower of Revival (10 seeds / revive a dead ally within 1 minute / long rest) |
| 14 | Endless Abundance (when seeds depleted, regain 1 per round) |
| 17 | Tree of Life (15m radius / 2d6 per round + death save advantage / long rest) |
| 18 | Yaoshi's Blessing (all healing maximized) |
| 20 | Eternal Song (30m / 1 minute / immune to death + 10 Hit Points (HP) per round + suppresses negative effects / long rest) |

#### Abundance Talent Node Details

**Lv 3 — First Node (choose one of three)**
| Talent | Effect |
|------|------|
| **Touch of Life** | Healing amount + Perception (PER) modifier |
| **Purification Expert** | Hand of Purification may remove 2 conditions simultaneously |
| **Natural Resilience** | Constitution (CON) modifier added to healing calculations |

**Lv 7 — Second Node (choose one of three)**
| Talent | Effect |
|------|------|
| **Seed Spread** | Sowing may affect 2 allies simultaneously (seeds consumed normally) |
| **Regeneration Empower** | When Bloom heals, the target also gains 1d4/round regeneration (3 rounds) |
| **Life Link** | May take 50% of damage dealt to a linked ally (transferred to self) |

**Lv 11 — Third Node (choose one of three)**
| Talent | Effect |
|------|------|
| **Vigorous Growth** | Life Seed cap +3 |
| **Purification Aura** | Allies within the Abundance Aura automatically remove 1 poison / disease each round |
| **Emergency Bloom** | When an ally's Hit Points (HP) drop to 0, may use a reaction to trigger the seed on them (immediate heal) |

**Lv 15 — Fourth Node (choose one of three)**
| Talent | Effect |
|------|------|
| **Touch of Yaoshi** | Healing crit (natural 20 doubles healing amount) |
| **Life Cycle** | Once per long rest: the whole party recovers 50% Hit Points (HP) and revives one ally who died within 1 minute |
| **Eternal Bloom** | 50% of overflow healing from seeds converts to temporary Hit Points (HP) (cap = level ×5) |

### Attack Attribute Allocation

Different Paths use different attributes for attack checks:

| Path | Attack Attribute | Design Logic |
|------|---------|---------|
| Destruction | Strength (STR) | Melee brawling, frontal crushing |
| Preservation | Strength (STR) | Shield-blocking, physical counter |
| Hunt | Agility (AGI) | Precision shooting, high-speed assassination |
| Erudition | Intellect (INT) | Energy projection, tech weapons |
| Harmony | Perception (PER) | Battlefield rhythm, state sensing |
| Abundance | Perception (PER) | Life sensing, precise healing |
| Nihility | Charisma (CHA) | Willpower / Path resonance |

---

---

> **🛠 Equipment Codex**: Light Cones (10 at 3★ / 15 at 4★ / 8 at 5★), Relics (14 four-piece sets + 10 accessory sets), slot main affixes, random sub affix tables, enhancement rules, and GM distribution guidance are collected in the **Equipment Codex** (`../assets/物品圖鑑.md`).
>
> ✨ The 7 Paths' combat techniques / Ultimates and Talent nodes are detailed in the **Magic Codex** (`../assets/魔法圖鑑.md`).

---

## 2.5 Progression System

### Experience Points Table

| Level | Experience Points (XP) Required | Cumulative Experience Points (XP) | Proficiency Bonus |
|------|--------|--------|---------|
| 1 | — | 0 | +2 |
| 2 | 300 | 300 | +2 |
| 3 | 600 | 900 | +2 |
| 4 | 1,200 | 2,100 | +2 |
| 5 | 2,400 | 4,500 | +3 |
| 6 | 4,800 | 9,300 | +3 |
| 7 | 7,200 | 16,500 | +3 |
| 8 | 9,600 | 26,100 | +3 |
| 9 | 14,400 | 40,500 | +4 |
| 10 | 19,200 | 59,700 | +4 |
| 11 | 24,000 | 83,700 | +4 |
| 12 | 28,800 | 112,500 | +4 |
| 13 | 36,000 | 148,500 | +5 |
| 14 | 43,200 | 191,700 | +5 |
| 15 | 57,600 | 249,300 | +5 |
| 16 | 72,000 | 321,300 | +5 |
| 17 | 86,400 | 407,700 | +6 |
| 18 | 108,000 | 515,700 | +6 |
| 19 | 144,000 | 659,700 | +6 |
| 20 | 180,000 | 839,700 | +6 |

### Experience Points (XP) Gain and Allocation

- **Combat Experience Points (XP)**: After defeating enemies, the total enemy Experience Points (XP) is **evenly distributed** among all participating characters
- **Story Experience Points (XP)**: Completing quests, reaching milestones, or resolving major conflicts usually grants Experience Points (XP) directly (not distributed)
- **Exploration / Social Experience Points (XP)**: The GM may grant 50–500 Experience Points (XP) based on character participation
- **Single-Session Experience Points (XP) Reference**: Lv 1–4 about 300–600, Lv 5–10 about 800–2,000, Lv 11–16 about 2,000–5,000, Lv 17–20 about 5,000–12,000

> **Milestone Leveling (Optional)**: The GM may choose not to use Experience Points (XP) calculations, instead leveling up the whole party at major story nodes. In this mode, ignore the Experience Points (XP) table; the GM decides leveling timing based on story pacing.

### Ability Score Improvement (ASI) Nodes
At levels 4/8/12/16/19, you may allocate **+2 ability points** (cap 20, cannot stack on the same attribute).

### Hit Points (HP) Growth (fixed value)
- d6 (Erudition): 4/level + Constitution (CON) mod
- d8 (Hunt / Harmony / Nihility / Abundance): 5/level + Constitution (CON) mod
- d10 (Destruction): 6/level + Constitution (CON) mod
- d12 (Preservation): 7/level + Constitution (CON) mod

### Traces System

Traces are a passive enhancement network that characters unlock as they level up. They fill the "downtime" between levels, ensuring every level-up brings tangible growth — much like the Trace nodes in Honkai: Star Rail, where each level unlocks a small bonus.

#### Trace Node Types

| Type | Icon | Description |
|------|:--:|------|
| **Attribute Boost** | ◆ | Gain +1 ability point (freely allocated, cannot exceed the Ability Score Improvement (ASI) cap of 20) |
| **Ability Advance** | ★ | One existing ability gains an enhancement (damage die +1 step, expanded range, or lower cost) |
| **Resource Expansion** | ● | Energy Point (EP) cap +5 or Path resource cap +1 |
| **Defense Boost** | ▲ | Hit Points (HP) +3 or Armor Class (AC) +1 (Armor Class (AC) may accumulate up to 2 times, max Armor Class (AC) 22) |

#### Level Trace Table

| Level | Trace Node | Description |
|:----:|:------:|------|
| 1 | ◆ Attribute Boost | Starting +1 attribute (already counted in the post-point-buy initial value, not gained extra) |
| 2 | ▲ Defense Boost | Hit Points (HP) +3 |
| 3 | ★ Ability Advance I | Base attack damage die +1 step (1d6→1d8, 1d8→1d10, 1d10→2d6, and so on) |
| 4 | ◆ Attribute Boost | Ability Score Improvement (ASI) node (+2 attribute); Trace bonus does not apply at this level |
| 5 | ★ Ability Advance II | Combat technique gains an enhancement (choose one: damage +1d6, or Difficulty Class (DC) +1, or range +1 square) |
| 6 | ● Resource Expansion I | Energy Point (EP) cap +5 |
| 7 | ▲ Defense Boost | Armor Class (AC) +1 (stacks with armor, cap Armor Class (AC) 22) |
| 8 | ◆ Attribute Boost | Ability Score Improvement (ASI) node (+2 attribute); Trace bonus does not apply at this level |
| 9 | ★ Ability Advance III | Ultimate enhancement (Energy Point (EP) cost −10, or damage +2d6, or add a secondary effect) |
| 10 | ● Resource Expansion II | Path resource cap +1 |
| 11 | ▲ Defense Boost | Hit Points (HP) +5 |
| 12 | ◆ Attribute Boost | Ability Score Improvement (ASI) node (+2 attribute); Trace bonus does not apply at this level |
| 13 | ★ Ability Advance IV | Choose one Talent node to gain an extra effect (negotiated by GM and player, e.g. +1d4 damage / range +1 square / uses +1) |
| 14 | ● Resource Expansion III | Energy Point (EP) cap +10 |
| 15 | ▲ Defense Boost | Armor Class (AC) +1 |
| 16 | ◆ Attribute Boost | Ability Score Improvement (ASI) node (+2 attribute); Trace bonus does not apply at this level |
| 17 | ★ Ability Advance V | Combat technique gains a second enhancement (may choose a different option than Lv5, or stack the same option) |
| 18 | ● Resource Expansion IV | Path resource cap +2 |
| 19 | ◆ Attribute Boost | Ability Score Improvement (ASI) node (+2 attribute); Trace bonus does not apply at this level |
| 20 | ★ Ultimate Trace | Choose one: all attributes +1, or Energy Point (EP) cap +20, or unlock a cross-Path base ability |

> **Ability Score Improvement (ASI) Node Note**: At Lv 4/8/12/16/19 you already gain the Ability Score Improvement (ASI) +2 attribute; Traces provide no extra enhancement at these levels — to avoid double attribute growth.

#### Trace Overview (cumulative for a max-level character)

| Type | Cumulative Gain |
|------|---------|
| ◆ Attribute Boost | 5 times (non-ASI levels from Lv1–19, including Lv1's starting +1) = 5 free attribute points |
| ★ Ability Advance | 6 times (base attack / combat technique ×2 / Ultimate / Talent / Ultimate Trace) |
| ● Resource Expansion | 4 times (Energy Point (EP) +15 + Path resource +3) |
| ▲ Defense Boost | 4 times (Hit Points (HP) +8 + Armor Class (AC) +2) |

#### Relationship Between Traces and Talents

- **Talent nodes** (Lv 3/7/11/15/19) are major **choose-one-of-three** decisions — they change playstyle
- **Trace nodes** are **fixed** passive growth — they ensure base numbers keep pace with the level curve
- The two complement each other: Talents provide horizontal differentiation, Traces provide vertical numerical growth

#### Example: Himeko's Trace Growth

> Himeko (Erudition Lv 8):
> - Lv1 (◆): Starting +1 Intellect (INT) (point buy 15 +1 = 16, modifier +3)
> - Lv2 (▲): Hit Points (HP) +3 → from 28 to 31
> - Lv3 (★): Base attack damage die 1d6→1d8
> - Lv4 (Ability Score Improvement (ASI)): +2 Intellect (INT) → 18 (modifier +4)
> - Lv5 (★): Combat technique enhancement — chose "damage +1d6", expanded firepower
> - Lv6 (●): Energy Point (EP) cap 140→145
> - Lv7 (▲): Armor Class (AC) +1 → from 14 to 15
> - Lv8 (Ability Score Improvement (ASI)): +2 Intellect (INT) → 20 (modifier +5)
>
> Cumulative growth at level 8: Intellect (INT) 15→20, Hit Points (HP) +3, base attack +1 step, combat technique +1d6, Energy Point (EP) +5, Armor Class (AC) +1 — every level leaves its mark.

### Multiclass Rules

Characters may choose to dabble in a second Path when leveling up. Multiclassing means the character embarks on a second Path, gaining some of its abilities, but cannot reach the ultimate depth of a single Path.

#### Multiclass Requirements
- Primary Path's corresponding attribute ≥ 13, desired multiclass Path's corresponding attribute ≥ 13
- After multiclassing, you may not take a third Path

#### Multiclass Gains (each level invested)
| Gained | Rule |
|---------|------|
| Hit Points (HP) | Gained per the multiclass Path's Hit Die (HD) (not maximum; must roll) |
| Proficiency | Gain the multiclass Path's weapon / armor proficiency, but not skill proficiency or save proficiency |
| Path Abilities | Gain that Path's abilities at the **corresponding level** (e.g. multiclass 1 level = that Path's 1st-level abilities) |
| Resource Pool | **Path resource pools are fully independent** — primary Path resources and multiclass Path resources are tracked separately, each gained by their own mechanics |
| Energy Point (EP) | Shares the same Energy Point (EP) pool. The Energy Point (EP) cap takes the **higher** of the two Paths |
| Extra Attack | Does not stack — even if both Paths gain "Extra Attack" at their corresponding levels, total attack count takes the **highest value** (not cumulative) |
| Ability Score Improvement (ASI) | Triggered by character total level (4/8/12/16/19), not by single Path level |

#### Multiclass Balance Limits
- The sum of multiclass levels may not exceed the primary Path level
- Path resources may not be converted between each other (e.g. Ardor stacks cannot be converted to Focus)
- When releasing an Ultimate, only Energy Point (EP) is consumed; Path resource enhancement effects may only trigger using one Path's resource

#### Multiclass Combination Examples
> **Himeko (Erudition 5 / Destruction 3)**  
> Primary Erudition grants area spells; multiclass Destruction grants the Ardor mechanic.  
> Energy Point (EP) maximum = 140 (uses the higher Erudition value).  
> Inspiration (Erudition) and Ardor stacks (Destruction) are tracked separately.  
> You may choose to spend 5 Inspiration to expand the Ultimate's area, or spend 5 Ardor stacks to increase Ultimate damage — but not both at once.

---

# Chapter 3: Combat and Conflict

## 3.1 Tactical Grid

### Grid System Basics
- Grid-based board (Grid System), 1 square = 1.5 meters
- Base movement speed: 6 squares
- Diagonal movement: first square 1, second square 2 (repeating)
- Crossing allies: pass freely but treated as difficult terrain
- Crossing enemies: requires a DC 15 + enemy's Agility modifier Agility (Acrobatics) check; failure halts movement and triggers an opportunity attack

### Distance Categories

| Name | Distance (squares) | Typical Use |
|------|-----------|---------|
| Adjacent | 0–1 squares | Melee attack, reach range |
| Close | 2–5 squares | Thrown weapons, short-range skills |
| Medium | 6–15 squares | Standard ranged weapons |
| Long | 16–30 squares | Longbow, sniper-type skills |
| Extreme | 31+ squares | Special scenarios |

### Area Attack Shapes
- **Burst**: circular spread centered on the target square, radius N
- **Cone**: fan-shaped spread extending forward from the origin, length N
- **Line**: straight extension forward from the origin, length N × width W

### Line of Sight (LoS)
A line connecting any corner of the character's square to any corner of the target square is not blocked by obstacles. Full cover blocks it, half cover does not, and smoke/darkness provides concealment.

### Cover Rules

| Cover Type | Armor Class (AC) Bonus | Reflex Save Bonus | Condition |
|----------|---------|-------------|------|
| Soft cover | +2 | +0 | Friendly creature in the line of attack |
| Half cover | +2 | +2 | Object covers at least 1/4 of the body |
| Three-quarters cover | +5 | +5 | Object covers at least 3/4 of the body |
| Total cover | Cannot be targeted | Immune to area damage | Fully hidden behind an obstacle |

### Terrain
- Difficult terrain: each 1 square of movement costs 2 squares of movement
- Hazardous terrain: entering or staying triggers damage/effect
- Elevation change: each 1 square of height difference requires an additional 1 square of movement to climb

---

## 3.2 Action Economy

### Turn Structure
> Turn Start Phase → Main Action Phase → Turn End Phase  
> 　　│　　　　　　　　│　　　　　　　　│  
> 　　▼　　　　　　　　▼　　　　　　　　▼  
> Ongoing effects trigger　　Use actions　　　　Ongoing effects expire  
> DoT resolution　　　　Cast Ultimate　　　Death saving throw  
> Turn-start abilities　　　Move　　　　　　Turn-end abilities

### Action Types

**A. Main Action (once per turn)**
- Attack action, use skill, Dash (movement ×2), Defend (Armor Class (AC) +2), Interact, Help (grant advantage), Hide, Ready action

**B. Move Action (once per turn)**
- Move (up to Speed squares), Stand up, Swap position (with adjacent willing creature), Climb/Swim, Manipulate simple object, Aim (ignore half cover)

**C. Minor Action (up to 1 per turn, optional)**
- Drink potion, switch equipment, command pet/summon, certain Path abilities, mark target (ally attack +1)

**D. Ultimate (does not use a turn action)**
- Trigger: Energy Point (EP) full
- Interrupt timing: may be inserted after any character declares an action, before the dice roll
- Each character may use at most 1 per round
- Multiple Ultimate conflict: higher initiative order takes priority

**E. Reaction (1 per round)**
- Opportunity attack: enemy leaves melee range without disengaging
- Ready action trigger, certain defensive reactions

**F. Free Action**
- Speak, drop item, end ongoing spell, Knowledge check

---

## 3.3 Initiative and Turns

### Initiative Check
> **Initiative** = d20 + Agility modifier + Perception modifier + other bonuses
- Natural 20: +5 bonus; natural 1: −5 (minimum 0)
- Tie: higher Agility modifier goes first; if still tied, roll d20

### Turn Order
- Arranged by Initiative from high to low, fixed for the entire combat
- Delay action is valid only for the current round; original order resumes next round
- Action delay caused by the Broken state is a permanent change

### Ultimate Interrupt Window
> Player A acts → after A's turn start → after A's action → before A's turn end → before Player B acts → ...
Each arrow is a window where an Ultimate may be inserted.

---

## 3.4 Attack and Damage

### Attack Roll
> **Attack roll** = d20 + attack ability modifier + Proficiency Bonus (PB) + other bonuses
The attack ability is determined by Path (see Section 2.4 Attack Ability Assignment).

### Margin of Success System (Combat)
> **Margin of Success (MoS)** = floor((total roll − target Armor Class (AC)) / 5)

| MoS | Name | Effect |
|--------|------|------|
| 0 | Ordinary Success | Base effect |
| 1 | Excellent Success | +1d6 extra damage / status duration +1 round |
| 2 | Outstanding Success | +2d6 extra damage / push 1 square / status Difficulty Class (DC) +2 |
| 3+ | Legendary Success | +3d6 extra damage / push 2 squares / immediately apply a minor status |

### Damage Formula
> **Final damage** = floor(total of base damage dice × (1 + damage bonus%)) + ability modifier + flat bonus − target's damage reduction

### Weapon Combat Styles

#### Dual Wielding
- Both weapons must have the **Light** trait (unless a relevant feat applies)
- When attacking with a **Main Action**, you may use a **Bonus Action** to attack once more with the off-hand weapon
- Off-hand attack does **not add ability modifier** to damage (unless the modifier is negative)
- Off-hand attack uses the same attack bonus as the main hand
- If the main-hand attack is multi-hit (e.g., extra attack), the off-hand still only gets 1 attack

#### Two-Handed
- When the weapon has the "Heavy" trait, it must be wielded with two hands
- Damage is taken directly from the weapon die, with no extra bonus
- Wielding a non-heavy weapon (e.g., longsword) with two hands: weapon die +1 step (1d8 → 1d10)

#### Ranged Weapon Special Rules
- When an enemy is within 5 squares, ranged attacks have **disadvantage**
- When beyond the base range (first value) but within the maximum range (second value), the attack has **disadvantage**
- Beyond maximum range, attack is impossible
- Ammunition tracking is an **optional rule** (not tracked by default; the Game Master (GM) declares when enabled)

#### Shields
- Wielding a shield occupies one hand (cannot dual wield)
- Treated as defensive equipment (Armor Class (AC) bonus see the Economy System armor table)
- Can be used as an improvised weapon (1d4 bludgeoning, no Proficiency Bonus (PB))

### Critical Hit
- Natural 20: automatic hit + damage dice doubled
- Expanded critical range (e.g., 18–20): counts as a critical only on a hit, not an automatic hit
- Some monsters are immune to critical hits

### Multi-Hit Attack
- Skill is tagged "Multi-hit N"
- Each Margin of Success (MoS) tier beyond the threshold adds 1 extra independent attack roll
- Maximum extra hits = the skill's N value
- From the 2nd hit onward, each hit's damage dice −1 die (minimum 1 die)

---

## 3.5 Weakness Break (Combat)

For detailed Toughness formulas, Toughness reduction values, and Break effects, see [1.6 Weakness Break System](#16-弱點擊破系統).

### Toughness Management in Combat

**Broken State Flow:**
> Attack hits (weakness element) ➔ Toughness reduction −20 / −30 / −50 (+ Tier bonus)  
> 　　　　 ↓  
> 　　Toughness ≤ 0?  
> 　　↓ Yes　　　　　　↓ No  
> Trigger Broken　　　Continue combat  
> 　　↓  
> Enemy enters "Broken" state:  
> 　• Takes +25% damage  
> 　• Initiative −10  
> 　• Element Break effect triggers  
> 　• If already acted → skip next turn  
> 　　 ↓  
> At enemy's next action start → Broken ends, Toughness restores to full

---

## 3.6 Elemental Interaction Effects

### Elemental Append Effects

| Element | Common Append Effect | Weakness Break Effect |
|------|-------------|-------------|
| **Physical** | Bleed DoT (2d4/round) DC 12 CON save | Major Bleed: 4d4/round, 2 rounds |
| **Fire** | Burn DoT (1d6/round) DC 12 CON save | Scorch: Burst radius 1, all enemies Burn |
| **Ice** | Freeze Slow (Speed −2 squares) DC 13 CON save | Frostbind: skip turn + critical range +1 |
| **Lightning** | Shock (1d8, chains to 1 adjacent enemy) DC 12 CON save | Thunderstorm: chains to 3 enemies, 2d8 |
| **Wind** | Laceration (5% of target's max Hit Points (HP)) DC 13 CON save | Sunder: 10% max Hit Points (HP) + Vulnerable |
| **Quantum** | Entanglement (action delay + 1d4 damage) DC 13 PER save | Quantum Collapse: delay 2d4 squares + Quantum mark |
| **Imaginary** | Imprison (Slow −3 squares + delay 1 square) DC 13 PER save | Imaginary Cage: fully Rooted for 1 round |

### Elemental Resonance

| Combo | Effect |
|------|------|
| Fire + Lightning | Overload (2d10 Fire, Burst radius 1) |
| Ice + Lightning | Superconduct (Armor Class (AC) −2) |
| Wind + Fire | Swirl (Burn spreads, Burst radius 2) |
| Physical + Ice | Shatter (Bleed doubled) |
| Quantum + Imaginary | Collapse (Armor Class (AC) −3, all saves −2) |
| Wind + Lightning | Storm (1d8 Lightning, all adjacent) |

---

## 3.7 Complete Status Effect List

### Damage-type DoT (all support stacking)
- **Burn**: 1d6 Fire damage per round, ends on DC 12 CON save
- **Bleed**: 2d4 Physical damage per round, ends on DC 12 CON save
- **Shock**: 1d8 Lightning damage per round, chains to 1 adjacent enemy
- **Laceration**: 5% of target's max Hit Points (HP) per round, ends on DC 13 CON save

### Control-type
- **Freeze**: Speed −2 squares, cannot take reactions
- **Entanglement**: action delay 1d4 squares, 1d4 damage per round
- **Imprison**: Speed −3 squares + delay 1 square
- **Stun**: completely unable to act, lasts 1 round
- **Rooted**: cannot move but may take other actions

### Mental-type
- **Charm**: cannot attack the caster, caster gains social advantage
- **Fear**: must use all movement to flee the source, attack disadvantage
- **Confusion**: before each attack/cast, roll d20; 11+ acts normally, 10− random target

### Buff-type
- **Shield**: absorbs damage (Fortitude × 2–3)
- **Haste**: Speed +3 squares
- **Empower**: Attack +1d4
- **Regeneration**: heal 1d4+PER per round

### Debuff-type
- **Slow**: Speed halved
- **Vulnerable**: +50% damage taken
- **Poisoned**: 1d6 Poison damage per round, attack disadvantage
- **Blinded**: attack disadvantage, cannot use abilities requiring sight
- **Silenced**: cannot use abilities requiring speech/chanting

---

## 3.8 Optional Combat Rules

1. **Flanking**: two allies on opposite sides of an enemy → melee attack advantage
2. **Surround/Encirce**: 3+ allies fully surround → enemy saves −2, Armor Class (AC) −1
3. **Elevation Advantage**: 2 squares higher +1, 5 squares higher +2 and ranged range +50%
4. **Charge**: move in a straight line 2+ squares → melee attack +2, Armor Class (AC) −2 until next turn
5. **Suppressing Fire**: designate Burst radius 1; enemy entering/leaving triggers a reaction ranged attack
6. **Push and Knockback**: into obstacle +1d6, fall 1d6 per square
7. **Cover Destruction**: wood 20 / stone 50 / metal 80 Hit Points (HP)
8. **Morale System**: mooks/Elite with Hit Points (HP) <50% require DC 12 PER save or flee
9. **Knockdown and Stand Up**: Prone melee −4, standing up costs 3 squares of movement

---

> **🛠 Game Master (GM)-Only Content**: Monster-building tools (Challenge Rating (CR) value reference table, Elite/Boss templates, sample monster data cards) and encounter-building guidance (Experience Points (XP) budget table, five core building principles, quick procedure) are collected in **the GM Guide** (`崩壞星穹鐵道TRPG_GM規則書.md`) Chapters 1 and 2. GMs should consult that document for monster design and encounter balance.

---

# Chapter 4: World and Narrative

## 4.1 Cosmology

### Aeons and Paths

In the cosmos exist supreme beings known as "Aeons." They are not personified deities, but rather the embodiment of a certain philosophical ideal — when a certain thought or belief reaches a cosmic extreme, the corresponding Aeon is born.

Each "Path" represents the road an Aeon walks, and is also the source of their power. Mortals may choose to "set foot upon a Path," following the ideals of an Aeon to gain extraordinary power.

| Aeon | Path | Core Ideal |
|------|------|---------|
| Qlipoth | Preservation | Build walls to protect, ward off the end |
| Lan | Hunt | Endless hunt, annihilate Abundance |
| Nanook | Destruction | End all things, purify the cosmos |
| Yaoshi | Abundance | Endless life, eternal propagation |
| IX | Nihility | Nihilism, all returns to void |
| Xipe | Harmony | Harmony of all, collective consciousness |
| Nous | Erudition | Calculate all things, foresee everything |

### Stellarons and the Fragmentum

The **Stellaron** is an anomalous entity in the cosmos, radiating reality-warping power. A Stellaron creates a **Fragmentum** — a distorted region of space-time where physical laws no longer apply and monsters breed. The Stellaron is both the source of disaster and the temptation of power; some individuals (such as Stellaron Resonants) gain special abilities after bonding with a Stellaron.

### The Astral Express

The Astral Express is a legendary train that travels between the stars, sailing along the Star Track of the "Trailblaze" Path. The passengers aboard are called **the Nameless**, whose mission is to explore unknown planets, connect civilizations, and repair Fragmentum corrupted by Stellarons.

---

## 4.2 Known Planets

### Belobog

**Theme**: frozen city, doomsday survival, class struggle  
**Stellaron Influence**: eternal winter, the entire planet is frozen  
**Key Factions**: the Great Guardian (city-builders), the Underworld resistance  
**Adventure Potential**: political intrigue, icefield exploration, Fragmentum cleanup

### Xianzhou Luofu

**Theme**: interstellar fleet, Long-Life species civilization, Yaoshi's Secret Teachings  
**Stellaron Influence**: Abundance corruption, some residents mutate into Long-Life Calamity species  
**Key Factions**: the Cloud Knights, Yaoshi's Secret Teachings, the Six Offices  
**Adventure Potential**: internal strife, the mystery of longevity, fleet battles

### Penacony

**Theme**: dream hotel, Family influence, Recollection Zone exploration  
**Stellaron Influence**: dreams merge with reality, memories become manifest  
**Key Factions**: the Family, the Garden of Recollection, dream merchants  
**Adventure Potential**: dream puzzles, memory regression, Family politics

### Herta's Space Station

**Theme**: Genius Society, Simulated Universe, research hub  
**Stellaron Influence**: minor, mainly under Genius Society control  
**Key Factions**: the Genius Society, the Intelligentsia Guild, IPC branch  
**Adventure Potential**: tech missions, Simulated Universe challenges, academic competition

---

## 4.3 Factions and Powers

| Faction | Core Ideal | Relationship with Players |
|------|---------|-----------|
| **Interastral Peace Corporation (IPC)** | Commerce above all, interstellar trade monopoly | Employer/rival/partner |
| **Stellaron Hunters** | Hunt Stellarons for bounty | Optional identity/potential ally |
| **Antimatter Legion** | Follow Nanook to destroy all | Primary hostile faction |
| **Genius Society** | Gathering of the cosmos' top intellects | Quest giver/tech support |
| **Garden of Recollection** | Guardians and traders of memory | Information provider/mysterious ally |
| **Intelligentsia Guild** | Academic research, knowledge sharing | Employer/research partner |
| **Masked Fools** | Chaotic entertainment, break the rules | Unpredictable third party |
| **Roving Rangers** | Follow the "Hunt" Path, interstellar vigilantes who fight violence with violence | Potential ally / friend or foe |

### Key Faction Strongholds

**World's End Tavern (Masked Fools)**
- **Location**: exists in the seams of the cosmos, impossible to locate with a conventional star chart — only those who are "invited" can find the entrance. Sometimes it appears out of nowhere in the most inconspicuous alley of a planet; sometimes it floats in the void, and pushing open any door might lead into it
- **Appearance**: always an old-style tavern in dusk tones, with a neon sign flickering on and off, and a record player spinning tunes no one has heard. The space is far larger than it appears; a corner may lead to an entirely different era or planet
- **Owner/Regulars**: the bartender's identity is always vague — possibly a high-ranking member of the Masked Fools, a punished Aeon follower, and some even say the tavern itself is a joke of Aha (Aeon of Elation). Patrons are a mixed bag — desperate mercenaries, geniuses seeking inspiration, lost Stellaron Hunters, even deserters from the Antimatter Legion
- **Rules**: violence is forbidden inside the tavern (violators are "shown out" — possibly thrown into a random Fragmentum). Information can be traded, but the currency is not necessarily Credit Points (CP): a secret, a memory, a future promise can all serve as bar tab
- **Adventure Uses**:
  - **Information Exchange**: any lead unobtainable through normal channels can be obtained here at a price
  - **Quest Board**: the Masked Fools often leave "commissions" at the tavern — usually seemingly absurd tasks that hide deeper meaning
  - **Chapter Transition**: the GM can let players rest at the tavern, as a breather between two adventures
  - **NPC Debut**: an excellent stage to introduce mysterious characters — the stranger drinking at the next table today may become a key ally or sworn enemy tomorrow

**Two-Phase Paradise / Two-Dimensional City (Masked Fools)**
- **Location**: a bizarre amusement park floating in a dimensional rift; the entrance may appear anywhere "utterly boring" — the backstage of an abandoned theater, an electronic billboard looping ads, the inner pages of a dog-eared magazine. The moment you step in, the whole world is "flattened" into a two-dimensional plane; visitors become flat color blocks but can still move freely
- **Appearance**: the visual style is like an animated pop-art poster, colors saturated to a glaring degree. Roller coaster tracks grow wildly across a paper-thin horizon; the carousel mounts are cartoonish forms of each visitor's most shameful memory; snack stalls sell "pixel popcorn" and "emotion cotton candy" — eating them really does temporarily change your mood
- **Rules**: the essence of Two-Phase Paradise is a "game of rules." Visitors must obey the absurd rules announced that day (e.g., "speak only by singing," "turn in place every three steps"); violators suffer "deepening two-dimensionalization" — first they lose color, then outline, and finally are pressed into a postcard and mailed to a random address on a random planet (restored after 24 hours). The core rule is **no boredom** — if the GM judges a player's behavior "too rational and dull," the park automatically triggers random events to "increase entertainment"
- **Adventure Uses**:
  - **Trial Ground**: the Masked Fools' initiation rites or promotion exams often take place here — complete a seemingly absurd challenge (such as "make the Ferris wheel spin backward" or "win a fight against your own shadow") to prove you have "the qualification"
  - **Start of Strange Commissions**: a Fool "lost Elation" inside the park and needs players to go in and bring it out — the previous "rescue team" has already become new carousel mounts
  - **Information in Bizarre Forms**: crucial intel may be "flattened" in the park into a stall's prize, a roller coaster's graffiti, or the sweetness of cotton candy — players must interpret it amid the madness
  - **Pure Breather**: occasionally let players play a few mini-games in the park, think of nothing, and enjoy the chaos — Aha picks up the tab anyway

---

> **🛠 Game Master (GM)-Only Content**: the original-planet creation toolkit (five-step guide, planet attribute card template, Rustcrown and Azure Abyss-Song examples), GM running guide (three-phase pacing model, fail-forward principle, reward pacing table), adventure module template (including the Rustcrown Steam Heart demo), and optional rules (Social Combat, interstellar travel event table, Simulated Universe) are collected in **the GM Guide** (`崩壞星穹鐵道TRPG_GM規則書.md`) Chapters 3 through 6. GMs should consult that document.

---

## 4.4 Loot and Treasure

### Distribution Principles
- **60–70% Credit Points (CP)** + **20–30% sellable loot** + **10% special items** (Light Cone/Relic/Stellar Jade)
- Each encounter should yield an immediate reward; each chapter completion should yield a major reward
- GMs should prioritize Relics and special Light Cones as loot rather than shop goods

### Suggested Reward per Adventure (Credit Points per person)

| Player Level | Short Adventure (1 session) | Mid Adventure (2–3 sessions) | Long Adventure/Chapter |
|:-------:|:------------:|:-----------:|:--------:|
| 1–2 | 100–300 | 300–600 | 500–1,200 |
| 3–4 | 150–400 | 400–1,000 | 1,000–2,500 |
| 5–6 | 300–700 | 800–1,800 | 2,000–4,500 |
| 7–8 | 500–1,200 | 1,300–3,000 | 3,500–7,500 |
| 9–10 | 800–2,000 | 2,200–5,000 | 5,500–12,000 |
| 11+ | 1,300–5,000+ | 3,500–13,000+ | 9,000–30,000+ |

> See the Economy System (`經濟系統.md`) Chapter 11 wealth curve.

### Loot Types
- **Currency**: Credit Points (CP), Stellar Jade (extremely rare)
- **Equipment**: weapons, armor, Light Cone, Relic (single piece or set)
- **Consumables**: healing potions, buff items, ammunition
- **Materials**: Path materials, Light Cone enhancement materials
- **Information/Connections**: non-material rewards, GMs may use as plot key

## 4.5 Interstellar Travel Rules

### Travel Phases
Interstellar travel is divided into three phases; the GM may insert events in each phase:

| Phase | Content | Typical Event |
|------|------|---------|
| **Departure** | Obtain tickets/fuel, complete formalities, gather navigation intel | DC 12 Social/Investigation |
| **In Transit** | Shipboard life, encounter events, character development | Voyage event table (roll d20) |
| **Arrival** | Entry inspection, local intel gathering, find stronghold | DC 12–18 Social/Stealth |

### Voyage Event Table (d20)

| d20 | Event |
|:---:|------|
| 1–2 | **Interstellar Pirate Interception**: encounter space raiders with Challenge Rating (CR) = party level |
| 3–4 | **Mechanical Failure**: DC 15 Technology/Engineering check, else delay 1d4 days |
| 5–6 | **Star Track Anomaly**: voyage time ×1.5, whole party DC 12 CON save or 1 level of Fatigue |
| 7–8 | **Smuggling Inspection**: IPC or local enforcers board to inspect (DC 15 Deception/Persuasion) |
| 9–12 | **Calm Voyage**: no event; characters may take 1 short rest activity (training/crafting/research) |
| 13–14 | **Aeon Ruins Detected**: sense an unmarked ancient signal in the nearby star sector (GM may plant a side-quest hook) |
| 15–16 | **Fellow Traveler**: meet an interesting NPC (potential ally/commissioner/intel source) |
| 17–18 | **Star Track Acceleration Current**: voyage time halved, whole party gains inspiration (advantage on next check) |
| 19–20 | **Trailblazer Ruins**: discover drifting objects from Akivili's era — 1d4 Stellar Jade shards or ancient relics |

### Character Actions During Travel (choose 1 per voyage)
- **Training**: gain temporary skill proficiency (valid during voyage)
- **Research**: Lore/Investigation check; success yields destination intel
- **Crafting**: spend materials to make an item (DC 15 Engineering)
- **Social**: build a relationship with a traveling NPC (Charisma check)
- **Rest**: remove 1 level of Fatigue or a disadvantage condition

---


# Appendix

## A. Glossary

| Abbrev | English | Chinese |
|------|------|------|
| DC | Difficulty Class | 難度等級 |
| MoS | Margin of Success | 成功度（超出DC的幅度） |
| Adv/Dis | Advantage/Disadvantage | 優勢/劣勢（雙骰取高/低） |
| PB | Proficiency Bonus | 熟練加值 |
| TN | Toughness Number | 韌性值 |
| CR | Challenge Rating | 挑戰等級 |
| EP | Energy Points | 能量點 |
| AC | Armor Class | 防禦等級（命中難度） |
| ASI | Ability Score Improvement | 屬性值提升節點 |

## B. Quick Reference

### Common Difficulty Class (DC) Quick Reference

| Situation | Difficulty Class (DC) |
|------|-----|
| Kick open a wooden door | 12 |
| Pick a lock (ordinary) | 15 |
| Persuade a neutral NPC | 15 |
| Sneak past patrol | 15 |
| Hack a terminal | 15–20 |
| Spot a hidden trap | 18 |
| Climb a smooth icy wall | 20 |

### Elemental Weakness Quick Reference

| Enemy Faction | Common Weakness | Common Resistance |
|---------|---------|---------|
| Antimatter Legion | Wind, Physical | Quantum |
| Swarm | Fire, Ice | Physical |
| Mechanical | Lightning | Physical |
| Voidspawn | Wind, Imaginary | Quantum |
| Fragmentum Creature | Quantum, Imaginary | Physical |

## C. Character Sheet Template

> ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
>    Honkai: Star Rail TRPG Character Sheet
> ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
> Character Name: ______________  Player Name: ______________
> Origin: ________________  Identity: ________________
> Path: ________________  Level: ____  Experience Points (XP): ________
> Elemental Affinity (Primary): ________  (Secondary): ________
> 
> 【Attributes】
> Strength (STR) ____(+__)  Agility (AGI) ____(+__)  Constitution (CON) ____(+__)
> Intellect (INT) ____(+__)  Perception (PER) ____(+__)  Charisma (CHA) ____(+__)
> 
> 【Combat】
> Hit Points (HP): ____ / Current Hit Points (HP): ____  Initiative: +____
> Armor Class (AC) (Defense): ____  Speed: ____ squares
> Energy Point (EP) Max: ____ / Current Energy Point (EP): ____  Energy Point (EP) Recovery: +____/round
> Path Resource: ________  Current Value: ____
> 
> 【Attacks】
> Weapon/Skill      Attack Bonus     Damage            Range     Element     Notes
> ___________   +____     ___________    ____    ____    ______
> ___________   +____     ___________    ____    ____    ______
> 
> 【Saving Throws】
> STR____  AGI____  CON____  INT____  PER____  CHA____
> 
> 【Skills】 (★ = Proficient)
> Strength (STR)  □ Athletics(+__)
> Agility (AGI)  □ Acrobatics(+__) □ Stealth(+__) □ Finesse(+__)
> Constitution (CON)  □ Endurance(+__)
> Intellect (INT)  □ Technology(+__) □ Lore(+__) □ Investigation(+__) □ Engineering(+__)
> Perception (PER)  □ Perception(skill)(+__) □ Insight(+__) □ Survival(+__) □ Anticipation(+__)
>      □ Animal Handling(+__) □ Medicine(+__)
> Charisma (CHA)  □ Persuasion(+__) □ Deception(+__) □ Intimidation(+__) □ Performance(+__) □ Resonance(+__)
> 
> 【Path Abilities】
> Lv___：________________________________
> Lv___：________________________________
> Lv___：________________________________
> 
> 【Equipment】
> Light Cone: ____________________ (__ star)
> Weapon: ____________________  Armor: ____________________
> Relic Set: ____________________ (2-pc/4-pc)
> Accessory Set: ____________________ (2-pc)
> Inventory: ________________________________
> Credit Points: ________  Stellar Jade: ________
> ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

---

> **Design Team**  
> Bi Shi'an (Core Mechanics) · Ke Jiaoling (Character System) · Zhan Zhige (Combat System) · Jing Shiwen (Worldbuilding & GM Guide)  
> Lead: Cheng Guiyao | TRPG Rules Studio  
> Based on the Honkai: Star Rail IP (© HoYoverse)
