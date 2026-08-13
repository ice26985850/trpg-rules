# Nation Building TRPG — GM Guide

> **Version:** v1.0  
> **Purpose:** A complete guide for the Game Master (GM) running *Nation Building TRPG*  
> **How to read:** This guide includes the entirety of the Player's Handbook plus GM-exclusive rules; the GM only needs to read this document to run the game.  
> **Player count:** Default 1 player + 1 GM (solo mode). Optional multiplayer mode (multiple players each govern a nation).

---

## Table of Contents

**Part One: Rules Foundations (identical to the Player's Handbook)**
1. [Game Overview](#第一章遊戲概述)
2. [Core Rules — Dice and Checks](#第二章核心規則骰子與檢定)
3. [Nation Creation](#第三章國家創建)
4. [National Attributes and Derived Values](#第四章國家屬性與衍生值)
5. [Race System](#第五章種族系統)
6. [Era Progression](#第六章時代演進)
7. [Construction System](#第七章建設系統)
8. [Nation Ideals and Policies](#第八章建國理念與政策)
9. [Turn-Based Game Flow](#第九章回合制遊戲流程)
10. [Diplomacy and Conflict](#第十章外交與衝突)
11. [Hero Units](#第十一章英雄單位)
12. [Crisis Management](#第十二章危機處理)
12.1 [Equipment, Items, and Magic Applications](#第十二章之一裝備道具與魔法應用玩家內容)

**Part Two: GM-Exclusive Rules**
13. [GM Tool: Complete Difficulty Class (DC) Setting Guide](#第十三章gm-工具難度等級設定完整指南)
14. [Complete War System](#第十四章完整戰爭系統)
15. [Crisis Deck and Trigger Mechanics](#第十五章危機牌組與觸發機制)
16. [Neighbor AI System](#第十六章鄰國人工智慧系統)
17. [Setting — The Continent of Elden](#第十七章世界觀設定埃爾登大陸)
18. [Starting Region Setup](#第十八章初始區域設定)
19. [Preset Neighbor Nations and Factions](#第十九章預設鄰國與勢力)
20. [GM Turn Operation Manual](#第二十章gm-回合操作手冊)
21. [Solo Game Hosting Guide](#第二十一章單人遊戲主持指南)
22. [Scenario Running Guide](#第二十二章劇本運行指引)
23. [Optional Rules and Variants](#第二十三章可選規則與變體)
24. [Status Effects Complete Rules](#第二十四章狀態效果完整規則)
25. [Random Wilderness Encounter Tables](#第二十五章隨機野外遭遇表)
26. [Complete Hero Skills and Spell List](#第二十六章英雄技能與法術完整清單)
27. [Monster Combat and War Integration](#第二十七章怪物戰鬥與戰爭整合)
28. [Appendix](#附錄二)

---

# Part One: Rules Foundations

---

## Chapter One: Game Overview

### 1.1 What Kind of Game Is This?

*Nation Building TRPG* is a tabletop role-playing game centered on "nation management." Players take on the role of a ruler who builds a nation from scratch — starting from a small camp of 50 people, progressing through the Tribal Age, City-State Age, Kingdom Age, and Empire Age, and potentially reaching the Legendary Age.

### 1.2 The Core Game Loop

```
Nation Creation → Turn Start (Spring) → Player Declares Actions →
Check/Dice Roll → Action Resolution → Crisis Trigger → Turn End →
Next Turn (Summer) → ... (four turns per year) → Era Progression
```

### 1.3 Core Terminology

| Term | Full Name | Description |
|------|-----------|-------------|
| Population (POP) | Population | Total number of the nation's citizens; determines labor and troop pool |
| Resources (RES) | Resources | Combined output capacity of food, minerals, timber, and other natural resources |
| Economy (ECO) | Economy | Trade networks, monetary system, tax efficiency |
| Military (MIL) | Military | Army size, equipment quality, strategic capability |
| Technology (TEC) | Technology | Technical level, research speed, magic systems |
| Morale (MOR) | Morale | Citizen loyalty, cultural cohesion, happiness index |
| National Power (NP) | National Power | A nation's overall influence, used for diplomatic Opposed Checks |
| Difficulty Class (DC) | Difficulty Class | The target number a check must reach |
| Modifier (MOD) | Modifier | The attribute's bonus/penalty applied to a check |
| Game Master (GM) | Game Master | The person who runs the game and plays the world |
| Advantage (ADV) | Advantage | Roll 2d20, take the higher |
| Disadvantage (DIS) | Disadvantage | Roll 2d20, take the lower |

---

## Chapter Two: Core Rules — Dice and Checks

### 2.1 Dice System: d20 + Modifier

**Check Formula:**

```
Check Result = 1d20 + Attribute Modifier (MOD) + Other Bonuses/Penalties

Success Condition: Check Result ≥ Difficulty Class (DC)
```

### 2.2 Attribute Modifier (MOD)

| Attribute Range | Modifier (MOD) |
|-----------|-------------|
| 1 – 4 | -2 |
| 5 – 9 | -1 |
| 10 – 14 | 0 |
| 15 – 19 | +1 |
| 20 – 24 | +2 |
| 25 – 29 | +3 |
| 30 – 34 | +4 |
| 35 – 39 | +5 |
| 40 – 44 | +6 |
| 45 – 49 | +7 |
| 50 – 54 | +8 |
| 55 – 59 | +9 |
| 60 – 64 | +10 |
| 65 – 69 | +11 |
| 70 – 74 | +12 |
| 75 – 79 | +13 |
| 80 – 84 | +14 |
| 85 – 89 | +15 |
| 90 – 94 | +16 |
| 95 – 99 | +17 |
| 100+ | +1 per +5 |

**Formula:** MOD = ⌊(Attribute Value − 10) ÷ 5⌋ (round down)

### 2.3 Difficulty Class (DC)

| Difficulty | DC | Description | Example |
|------|-----|------|------|
| Trivial | 5 | Almost impossible to fail | Build a simple wooden palisade |
| Easy | 10 | Easily achieved by the experienced | Clear a small farmland |
| Normal | 15 | Requires some competence | Establish trade with a neutral neighbor |
| Hard | 20 | Requires expertise or luck | Persuade a hostile neighbor to cease fire |
| Very Hard | 25 | Risky even for experts | Establish an oasis city in the desert |
| Legendary | 30 | Beyond mortal reach | Persuade two nations to set aside a generational feud and fight together |

### 2.4 Advantage (ADV) and Disadvantage (DIS)

- **Advantage (ADV):** Roll 2d20, take the higher result
- **Disadvantage (DIS):** Roll 2d20, take the lower result
- Advantage and Disadvantage cancel each other out

### 2.5 Critical Success and Critical Failure

- **Critical Success (Crit):** natural 20 → automatic success + extra benefit
- **Critical Failure (Fumble):** natural 1 → automatic failure + negative consequence

### 2.6 Check Types

**Standard Check:** Declare action → decide attribute and difficulty → roll → compare result.

**Opposed Check:** Both sides roll simultaneously and compare results. Used for diplomatic negotiations, wars, etc.

**Group Check (multiplayer mode):** The overall succeeds if at least half of the players succeed.

**Aid Check:** The helper first makes a 1d20 + relevant attribute check (DC 10); on success the main actor gets +2 (Critical Success +4), on failure no bonus (Critical Failure the main actor gets −2). In solo play, an advisor NPC played by the GM may also aid.

### 2.7 Seasonal Modifiers

| Season | Effect |
|------|------|
| Spring | Diplomacy checks +1 |
| Summer | Construction checks gain Advantage (ADV) |
| Autumn | Trade checks +2 |
| Winter | Construction checks gain Disadvantage (DIS); food consumption ×1.3 |

---

## Chapter Three: Nation Creation

### Step One: Choose Origin

| Origin | Attribute Effects |
|------|----------|
| **Fugitives** | Morale (MOR) +10, Military (MIL) −5 |
| **Pioneers** | Resources (RES) +10, Economy (ECO) −5 |
| **Rebels** | Military (MIL) +10, Morale (MOR) −5 |
| **Expedition** | Technology (TEC) +10, Population (POP) −5 |
| **Exiled Nobility** | Economy (ECO) +10, Resources (RES) −5 |
| **Faithful Followers** | Morale (MOR) +10, Technology (TEC) −5 |

### Step Two: Choose Racial Composition

Starting population 50. Choose either a **single race** (that race's aptitude bonus ×2, starting Racial Satisfaction +10) or a **dual-race mix** (each race's aptitude at base value, unlocks cultural fusion benefits, starting Racial Satisfaction 50). See [Chapter Five](#第五章種族系統).

> Upon completing nation creation, the nation immediately receives **starting Gold 150** and **starting Food 200** (see Chapter Four resource stockpile).

### Step Three: Choose Geographic Location

| Terrain | Advantage | Disadvantage |
|------|------|------|
| Forest | Resources (RES) +10 | Military (MIL) −5 |
| Plains | Population (POP) +10 | Military (MIL) −5 |
| Mountains | Military (MIL) +10 | Resources (RES) −5 |
| Coast | Economy (ECO) +10 | Population (POP) −5 |
| Riverside | Resources (RES) +5, Population (POP) +5 | Military (MIL) −10 |
| Plateau | Technology (TEC) +10 | Economy (ECO) −5 |

### Step Four: Allocate Initial Attribute Points

Each of the six dimensions starts at 10, with 30 points freely allocated, plus origin, terrain, and racial bonuses.

### Step Five: Choose Nation Ideal

| Ideal | Core Effect |
|------|----------|
| Military Power | Military (MIL) +10, military spending −20% |
| Trade Hub | Economy (ECO) +10, trade income +30% |
| Magic Nation | Technology (TEC) +10, Research Points (RP) +50% |
| Free City-State | Morale (MOR) +10, population growth +20% |

### Step Six: Meet Your First Neighbor

The GM sets the initial neighbor nation based on the starting region (see [Chapter Eighteen](#第十八章初始區域設定) and [Chapter Nineteen](#第十九章預設鄰國與勢力)).

---

## Chapter Four: National Attributes and Derived Values

### 4.1 The National Six Dimensions

| Attribute | Abbrev. | Core Function |
|------|------|----------|
| Population (POP) | Population | Labor, conscription cap, market size |
| Resources (RES) | Resources | Food output, building material supply |
| Economy (ECO) | Economy | Taxation, trade, monetary stability |
| Military (MIL) | Military | Army quality, defensive capability |
| Technology (TEC) | Technology | Research speed, magic level |
| Morale (MOR) | Morale | Loyalty, culture, happiness |

### 4.2 Derived Attributes

| Derived Attribute | Formula |
|----------|------|
| National Power (NP) | Population (POP) × 0.5 + Resources (RES) + Economy (ECO) + Military (MIL) |
| Tax (TAX) | Economy (ECO) × Population (POP) × 0.01 |
| Food Consumption (FOD) | Population (POP) × 0.8 (Winter × 1.3) |
| Research Points (RP) | Technology (TEC) × 0.5 |
| Population Cap (CAP) | 10 + Resources (RES) × 5 |
| Military Cap (MCP) | Population (POP) × 0.1 + Military (MIL) × 0.5 |

**Resource Stockpile:**

| Resource | Initial | Change Rule |
|------|--------|----------|
| Gold (GOLD) | 150 | Per turn + Tax (TAX) − maintenance − troop wages − other expenses |
| Food (FOOD) | 200 | Per turn + food output (Autumn ×2) − food consumption (FOD); if < 0, set to 0 and Morale −5 |
| Wood (MAT_WOOD) | 30 | Produced by lumber mill; market 1 gold = 1 wood |
| Stone (MAT_STONE) | 20 | Produced by quarry; market 1 gold = 1 stone |
| Iron Ore (MAT_IRON) | 10 | Produced by mine; market 1 gold = 1 iron ore |

---

## Chapter Five: Race System

### 5.1 Race List

| Race | Aptitude Bonus | Special Requirement | Cultural Trait |
|------|----------|----------|----------|
| **Human (HUM)** | Economy (ECO) +5, Morale (MOR) +5 | None | Highly adaptable, neutral diplomacy |
| **Dwarf (DWA)** | Resources (RES) +10 | Requires mountain terrain | Construction cost −20% |
| **Elf (ELF)** | Technology (TEC) +10 | Requires forest cover > 30% | Magic affinity |
| **Orc (ORC)** | Military (MIL) +10 | Each turn requires combat/hunting | Morale rarely drops |
| **Halfling (HAL)** | Economy (ECO) +5, Morale (MOR) +5 | Avoid prolonged wars | Food output +20% |
| **Dragonborn (DRA)** | Military (MIL) +5, Technology (TEC) +5 | Requires "Dragon Nest Temple" | Diplomatic deterrence |
| **Gnome (GNO)** | Technology (TEC) +10 | Requires "Invention Workshop" | Invention chance +10% |
| **Goliath (GOL)** | Military (MIL) +5, Resources (RES) +5 | Population growth −50% | Construction efficiency +30% |

### 5.2 Racial Satisfaction

| Satisfaction | Effect |
|--------|------|
| 80 – 100 | Output +20% |
| 50 – 79 | Normal |
| 30 – 49 | Output −10% |
| 10 – 29 | Output −30%, risk of protests |
| 0 – 9 | Possible rebellion |

---

## Chapter Six: Era Progression

| Era | Trigger Condition | Unlocks |
|------|----------|------|
| **Tribal Age** | Initial | Basic farmland, wooden palisade, hunter's hut |
| **City-State Age** | Population (POP) > 250 | Stone walls, market, barracks |
| **Kingdom Age** | National Power (NP) > 150 + city walls | Castle, university, navy |
| **Empire Age** | National Power (NP) > 350 + ally | Wonders, expeditionary army |
| **Legendary Age** | Technology (TEC) > 150 + event | Sky City, teleport gate |

Each era upgrade: all attributes × 1.2, unlocks new buildings/units, Crisis Difficulty Class (DC) +2.

> **On Growth and Caps:** This game has no traditional level/XP system; growth comes from construction, Era Progression, and legendary deeds. After the Legendary Age there is no hard level cap; the endgame is decided by the scenario or the players.

---

## Chapter Seven: Construction System

Construction cap per turn = Population (POP) × 0.05 (at least 1 item).

**Building Material Stockpile:** The wood / stone / iron ore costs in a building's price are independent stockpiles (see Chapter Four). When a corresponding production building exists, output is automatic each turn; otherwise market 1 gold = 1 building material (in the Tribal Age without a market, you must first build a production building or trade).

**Ongoing Gold Drain (gold sink):** Deducted at end-of-turn settlement — building maintenance = sum of all built "gold costs" × 2% (rounded); troop wages = sum of all unit "costs" × 2% (militia exempt from wages). This avoids early false poverty and late-game gold overflow.

**Construction Time (City-State and above):** Tribal buildings are marked (1–2 turns); City-State 2 turns, Kingdom 2–3 turns, Empire 3–4 turns, Legendary 4–5 turns (GM may fine-tune by scale).

### Tribal Age Buildings

| Building | Cost | Effect |
|------|------|------|
| Farmland | 50 gold | Food output +10, Resources (RES) +2 |
| Hunter's Hut | 40 gold, 20 wood | Food output +5, Military (MIL) +1 |
| Wooden Palisade | 60 gold, 30 wood | Defense +5 |
| Well | 30 gold | Population Cap +10 |
| Warehouse | 80 gold | Storage Cap +50 |
| Simple Shrine | 50 gold | Morale (MOR) +2 |
| Workshop | 100 gold | Technology (TEC) +2 |
| Trading Post | 60 gold | Economy (ECO) +2 |
| Lumber Mill | 50 gold | Wood (MAT_WOOD) +5/turn |
| Quarry | 80 gold | Stone (MAT_STONE) +6/turn |
| Mine | 120 gold | Iron Ore (MAT_IRON) +2/turn |

### City-State Age New Buildings

| Building | Prereq | Cost | Effect |
|------|------|------|------|
| Market | Trading Post | 200 gold | Economy (ECO) +5 |
| Stone Wall | Wooden Palisade | 300 gold, 60 stone | Defense +15 |
| Barracks | — | 250 gold | Military (MIL) +5, unlocks infantry |
| Port | Coast | 350 gold | Economy (ECO) +5 |
| Library | Workshop | 200 gold | Technology (TEC) +5 |
| Merchant Guild | Market | 300 gold | Trade +20% |
| Smithy | — | 200 gold | Military equipment +1 |
| Temple | Simple Shrine | 250 gold | Morale (MOR) +5 |

### Kingdom Age New Buildings

| Building | Prereq | Cost | Effect |
|------|------|------|------|
| Castle | Stone Wall + Barracks | 1,000 gold | Defense +30 |
| University | Library | 800 gold | Technology (TEC) +10 |
| Mint | Merchant Guild | 600 gold | Economy (ECO) +10 |
| Naval Dockyard | Port | 700 gold | Military (MIL) +5, unlocks warships |
| Embassy | — | 500 gold | Diplomacy +50% |
| Arena | — | 400 gold | Morale (MOR) +8 |

### Empire Age New Buildings

| Building | Prereq | Cost | Effect |
|------|------|------|------|
| Grand Arena | Arena | 2,000 gold | Morale (MOR) +15 |
| Royal Academy | University | 3,000 gold | Technology (TEC) +20 |
| Expeditionary Barracks | Barracks + Castle | 1,500 gold | Military (MIL) +15 |
| Central Bank | Mint | 2,500 gold | Economy (ECO) +20 |
| Grand Library | Library × 2 | 2,000 gold | All-tech acceleration 30% |
| Colony Port | Port | 1,800 gold | Unlocks colonies |
| Mage Tower | University | 3,500 gold | Technology (TEC) +25 |
| Wonder Monument | — | 5,000 gold | National Power (NP) +20 |

### Legendary Age Buildings

| Building | Prereq | Cost | Effect |
|------|------|------|------|
| Sky City (Wonder) | Mage Tower + Technology (TEC) > 150 | 20,000 gold | National Power (NP) +50, cannot be besieged |
| Planar Teleport Gate | Mage Tower × 2 | 15,000 gold | Unlocks planar diplomacy and trade |
| God-Cannon Tower | Mage Tower | 10,000 gold | Defense +100, can attack god-level threats |
| Fountain of Eternity (Wonder) | Technology (TEC) > 200 | 25,000 gold | Population (POP) never affected by famine |

---

## Chapter Eight: Nation Ideals and Policies

### 8.1 Four Nation Ideals

**Military Power:** Military spending −20% → total mobilization → war Advantage (ADV)

**Trade Hub:** Trade income +30% → free port → financial hegemony

**Magic Nation:** Research Points (RP) +50% → magic building cost −30% → wellspring of mana

**Free City-State:** Population growth +20% → immigrant paradise → beacon of enlightenment

### 8.2 Complete Policy Tree

Whenever National Power (NP) reaches the following thresholds, a new policy unlocks:

| National Power (NP) Threshold | Military Power | Trade Hub | Magic Nation | Free City-State |
|--------------|----------|----------|----------|----------|
| 60 | Conscription: Population (POP) × 0.05 becomes militia | Market Monopoly: single commodity price +50% | Arcane Enlightenment: unlocks basic magic | Citizens' Assembly: Morale (MOR) +5 |
| 180 | War Machine: whole army Advantage (ADV) | Financial Alliance: loan interest −50% | Elemental Pact: unlocks elemental summoning | Immigrant Paradise: attracts neighbor immigration |
| 380 | Scorched Earth: can destroy enemy resources when retreating | Trade Empire: vassals auto-sign unequal treaties | Mana Wellspring: magic building output ×2 | Beacon of Enlightenment: global diplomatic leaning turns friendly |
| 600 | Total War: can mobilize entire population for war | Gold Standard: currency never devalues | Apotheosis: ruler can gain divinity | World Council: can convene global peace conference |

---

## Chapter Nine: Turn-Based Game Flow

One turn = one season (three months); four turns = one year.

### Five Turn Phases

1. **Season Announcement (GM)**
2. **Player Action Declaration** (3 major actions)
3. **Action Check and Resolution**
4. **Crisis Trigger and Resolution**
5. **Turn-End Settlement**

### Turn-End Settlement Checklist

```
☐ Gold (GOLD) += Tax (TAX) − building maintenance − troop wages − other expenses
☐ Food (FOOD) += food output (Autumn ×2) − food consumption (FOD); if FOOD < 0 → set to 0 and Morale (MOR) −5
☐ Research Points (RP) += Technology (TEC) × 0.5 (every 50 RP accumulated can be spent to unlock a "Tech Breakthrough": Technology (TEC) +2 or a specialty bonus)
☐ Calculate natural population change (formula below)
☐ Check era upgrade conditions
☐ Record all data changes
☐ Check special event triggers
```

**Natural Population Growth:** Base growth rate 3%; Morale (MOR) ≥ 60 and Food (FOOD) > 0 → +1% (total 4%); Morale (MOR) < 40 → −1% (decline); Food (FOOD) = 0 → additional decline FLOOR(gap ÷ 2). The "Free City-State" ideal's "population growth +20%" is × 1.2 (multiplied onto the growth rate, not +20 percentage points). Population change = Population (POP) × growth rate × racial modifier (Goliath ×0.5, Halfling ×1.2), capped at Population Cap (CAP).

---

## Chapter Ten: Diplomacy and Conflict

### 10.1 Neighbor Relations Levels

| Level | Range | Effect |
|------|------|------|
| Hostile (HOS) | -100 ~ -51 | Can declare war, embargo |
| Cold (CLD) | -50 ~ -11 | Border blockade |
| Neutral (NTR) | -10 ~ +10 | Basic trade |
| Friendly (FRD) | +11 ~ +50 | Trade preferences |
| Allied (ALL) | +51 ~ +100 | Military alliance |

### 10.2 Diplomatic Actions

| Action | Cost | Effect |
|------|------|------|
| Dispatch Ambassador | 1 turn + 50 gold | Establish diplomacy |
| Trade Negotiation | 1 turn | Sign agreement |
| Alliance Proposal | Relations > 30 | Military alliance |
| Marriage Alliance | Special event | Relations +30 |
| Declare War | — | Relations drop to Hostile |
| Sue for Peace | Gold + resources | End war |

---

## Chapter Eleven: Hero Units

### Hero Types

| Type | Primary Attributes | Core Function |
|------|----------|----------|
| **General (GEN)** | Might (ATK) + Tactics (TAC) | Command armies |
| **Spy (SPY)** | Stealth (STL) + Wits (INT) | Infiltrate/sabotage |
| **Scholar (SCH)** | Wits (INT) + Knowledge (KNW) | Accelerate research |
| **Envoy (ENV)** | Charisma (CHA) + Eloquence (ELO) | Diplomatic specialist |
| **Master Artisan (ART)** | Craft (CRF) + Creativity (CRE) | Special buildings |

### Hero Attributes (0–20)

Might (ATK), Wits (INT), Charisma (CHA), Stealth (STL), Knowledge (KNW), Tactics (TAC), Craft (CRF), Eloquence (ELO), Creativity (CRE).

### Hero Loyalty (1–10)

| Loyalty | Effect |
|------|------|
| 1-3 | May defect |
| 4-6 | Normal |
| 7-9 | Missions gain Advantage (ADV) |
| 10 | May reroll once on failure |

### Hero Personal Combat

Heroes may leave the army to perform solo missions or fight personally (hero vs hero, hero vs monster).

**Hit Points (HP):** Hero Hit Points = 20 + Might (ATK) × 4 + Constitution (CON) × 2 (Constitution is set by the GM from background, 0–10, default 5).

**Combat Action Economy:** Hero combat is turn-based; each hero may perform **1 major action + 1 move action** per turn (Movement (MOV) = 3 + FLOOR(Might (ATK) ÷ 5)). At combat start, roll 1d20 + Stealth (STL) or Might (ATK) to determine initiative.

**Hero Defense (DEF):** Hero base Defense (DEF) = 10, plus armor bonus (see item catalog). E.g., a hero wearing Leather Armor (+2) has Defense (DEF) = 12.

**Damage Calculation:**

```
Hit Check: 1d20 + corresponding hero attribute (melee uses Might (ATK), ranged uses Stealth (STL), spell uses Knowledge (KNW)) ≥ enemy Defense (DEF)
Melee damage per hit = Hero Might (ATK) + weapon attack bonus + FLOOR(Might (ATK) ÷ 3)
Ranged damage per hit = Hero Stealth (STL) + weapon attack bonus + FLOOR(Stealth (STL) ÷ 3)
(Weapon base damage is based on the hero's corresponding attribute; weapon "Attack +N" stacks on top)
```

**Monster vs Hero:** Monster hit = 1d20 + monster Attack (ATK) ≥ hero Defense (DEF); on hit, actual damage = monster Attack (ATK) − armor bonus (minimum 1). Armor thus provides both an evasion chance and damage reduction.

**Rest and Recovery:** Resting at a safe location recovers **max Hit Points (HP) × 10%** per turn (rounded, minimum 1); Mana (MP) recovers 5 that turn (town/temple 10).

**Death and Down:** When Hit Points (HP) reach 0 the hero is **down** (incapacitated, dying). If not aided and not recovered within 3 turns, the hero **dies** (permanently lost). May use Healing Potion, rest, or spell to recover Hit Points.

### Hero Skills and Spells

Each hero has 2–3 specialty skills by type (see table below), and may learn general skills through missions and training. Casting spells costs **Mana (MP)** (see Chapter Twenty-Six).

| Hero Type | Specialty Skills (examples) | Key Attributes |
|----------|----------------|----------|
| General (GEN) | Tactical Command (whole army +2 attack), Charge Order, Hold the Line | Might (ATK), Tactics (TAC) |
| Spy (SPY) | Stealth Infiltration, Intelligence Theft, Poison (target −3 attribute/turn, 2–3 turns) | Stealth (STL), Wits (INT) |
| Scholar (SCH) | Arcane Missile (damage 2d6+Knowledge), Appraisal, Quick Research | Knowledge (KNW), Wits (INT) |
| Envoy (ENV) | Persuasion (Opposed +3), Treaty-Making, Diplomatic Intelligence | Charisma (CHA), Eloquence (ELO) |
| Master Artisan (ART) | Enchant (equipment +1), Rapid Build (construction −1 turn), Invent | Craft (CRF), Creativity (CRE) |

**General Skills** (learnable by any hero): Scouting, First Aid (recover 1d6+2 Hit Points), Riding, Intimidation, Climbing.

### Hero Equipment

Heroes may wear weapons and armor; effects stack directly onto the hero's attack and defense:

- **Weapon** (e.g., Iron Sword, Attack +2): adds to the hero's weapon base damage.
- **Armor** (e.g., Leather Armor, Defense +2): adds to the hero's Defense (DEF).
- **Special Equipment** (e.g., Arquebus, Attack +8 ranged): takes effect per item catalog values.

> For rules on how equipment affects "national attributes" and "military units," see Chapter Thirteen of the Player's book; the GM may refer directly to item catalog values.

### Hero Growth

Heroes grow continuously through missions and training: every 3 hero missions completed (or 3 hero victories accumulated) grants 1 attribute point (single-attribute cap 20); may also spend 50 gold/turn on specialized training for +1 to a designated attribute. See Chapter Eleven, Section Nine of the Player's book.

---

## Chapter Twelve: Crisis Management

### Five Crisis Types

| Type | Example | Impact |
|------|------|------|
| Natural Disaster (NAT) | Flood, drought, plague | Resources (RES), Population (POP) |
| Economic Crisis (ENC) | Inflation, deficit | Economy (ECO), Morale (MOR) |
| Diplomatic Crisis (DIP) | Border conflict, sanctions | Military (MIL), Morale (MOR) |
| Internal Crisis (INT) | Rebellion, secession | Morale (MOR), Population (POP) |
| Supernatural Crisis (SUP) | Monster invasion, magic disaster | All |

### Resolution Results

| Result | Condition | Effect |
|------|------|------|
| Critical Success | natural 20 | Perfect resolution + reward |
| Success | ≥ DC | No-loss resolution |
| Partial Success | Within DC − 3 | −2 attribute |
| Failure | < DC − 3 | −5 ~ −15 attribute |
| Critical Failure | natural 1 | Crisis worsens |

---

# Part Two: GM-Exclusive Rules

---

## Chapter Twelve-One: Equipment, Items, and Magic Applications (Player Content)

> This chapter is identical to Chapter Thirteen of the Player's Handbook, for the GM's reference; the GM-exclusive status effects, random encounters, and spell lists are in Chapters Twenty-Four through Twenty-Seven.

### Who Equipment Affects

| Target | How It Applies | Example |
|------|----------|------|
| Hero | Weapon to hero weapon damage, armor to Defense (DEF) | Iron Sword +2, Leather Armor +2 |
| Military Unit | Via buildings like Smithy, +1 attack/defense for a unit type | Cavalry Lance: cavalry +3 |
| Nation | Strategic equipment affects attributes or war | God-Cannon: siege +50 |

### Mana (MP) System

- Mana Cap (MP_MAX) = 10 + Knowledge (KNW) × 2
- Recover 5 per turn; resting in town/temple recovers 10
- Common spells 2–5 points; powerful 6–10 points; Lesser Mana Potion recovers 10

### Magic Types and Casting

| Magic Type | Casting Attribute | Typical Effect |
|----------|----------|----------|
| Arcane Magic | Knowledge (KNW) | Arcane Missile, Arcane Shield |
| Divine Magic | Charisma (CHA) | Heal, Turn Undead |
| Nature Magic | Knowledge (KNW) | Entangle, Speak with Beasts |
| Rune Magic | Craft (CRF) | Enchant, Warding Rune |
| Alchemy | Craft (CRF) | Explosive, Healing Draught |

Casting: `1d20 + corresponding hero attribute (base value) ≥ Spell Difficulty Class (DC)`; on failure waste Mana (MP) and produce no effect.

---

## Chapter Thirteen: GM Tool — Complete Difficulty Class (DC) Setting Guide

### 13.1 General Task Difficulty Principles (Not for Crises)

> ⚠️ **Crisis checks do NOT use this section.** All crisis Difficulty Classes (DC) are uniformly based on the Crisis Deck (Chapter Fifteen) card DC, then stacked with 15.3 National Power adjustment and 13.2 situational fine-tuning (full rules in 13.5 Unified Crisis DC Framework). This section is only for reference on general tasks (construction, diplomacy, research, and other non-crisis actions).

General task DC may be fine-tuned as the nation grows, but **the increase must be smaller than the growth of the nation's Modifier (MOD)** (MOD is currently +1 per 5 points), to avoid "the stronger you get, the harder it becomes" canceling out specialty advantages. It is recommended to primarily use the six-tier DC from Player's book 2.3, applying slight upward pressure per the table below when necessary:

| National Power (NP) Range | DC Adjustment | Description |
|--------------|--------|------|
| 1 – 50 (Tribal~City-State) | ±0 | Baseline unchanged |
| 51 – 120 (Kingdom) | +1 | International politics slightly more complex |
| 121 – 200 (Empire) | +2 | Internal and external troubles coexist |
| 200+ (Legendary) | +3 | God-level challenges |

### 13.2 Difficulty Fine-Tuning Factors

Adjust the base difficulty (DC) based on the following factors:

| Factor | Adjustment |
|------|------|
| Player has ample resources (Gold > 500) | DC +2 (things money can solve shouldn't be too easy) |
| Player is disadvantaged (some attribute < 20) | DC −2 (give the struggling small nation a lifeline) |
| Hero assistance present | DC −3 (heroes are professionals) |
| Player has already handled the same crisis | DC +2 (repeated challenges get harder, avoid resource farming) |
| This is an action related to the player's nation ideal | DC −2 (the ideal is the nation's specialty) |
| This action violates the nation ideal | DC +3 (the price of violating the ideal) |

### 13.3 Attribute Pairing Guide by Action Type

| Action Type | Primary Attribute | Secondary Attribute (optional) |
|----------|----------|-----------------|
| Build infrastructure | Resources (RES) | Economy (ECO) |
| Build military facilities | Military (MIL) | Resources (RES) |
| Build cultural facilities | Morale (MOR) | Economy (ECO) |
| Build tech facilities | Technology (TEC) | Economy (ECO) |
| Diplomatic negotiation | Economy (ECO) | Morale (MOR) |
| Military action | Military (MIL) | Technology (TEC) |
| Tech research | Technology (TEC) | — |
| Quell public discontent | Morale (MOR) | Economy (ECO) |
| Develop resources | Resources (RES) | Technology (TEC) |
| Trade agreement | Economy (ECO) | Morale (MOR) |
| Census/management | Population (POP) | Economy (ECO) |
| Hero mission | Corresponding hero attribute | — |

### 13.4 Hidden Difficulty

The GM should never directly tell the player the Difficulty Class (DC) number. Use descriptive language instead:

| Don't say | Say instead |
|--------|--------|
| "The difficulty is 15" | "This task requires a certain diplomatic finesse" |
| "The difficulty is 25, too hard" | "Your advisory council unanimously agrees this is nearly impossible — but not entirely without hope" |
| "The difficulty dropped 2 because you have a hero" | "Your general stands before the map and points out several key breakthroughs" |

### 13.5 Unified Crisis DC Framework (the only standard)

To avoid multiple DC rule sets conflicting, all crisis checks uniformly use the following single formula, and **13.1's era-baseline DC is no longer applied**:

```
Final Crisis DC = Crisis Deck card DC (Chapter Fifteen)
                + 15.3 National Power (NP) severity adjustment (−5 ~ +5)
                + 13.2 situational fine-tuning factors (e.g.: hero assist −3, ideal-related −2, violates ideal +3, etc.)
```

- The deck card DC is already the designer's baseline calibrated to crisis intensity; do not additionally stack 13.1's era DC.
- 15.3's National Power adjustment range is only −5 ~ +5, deliberately kept low so that a high-development nation's MOD advantage (+1 per 5 points) is not fully canceled by crisis DC.
- General tasks (non-crisis) are the only ones that apply 13.1's slight DC fine-tuning.

---

## Chapter Fourteen: Complete War System

### 14.1 War Trigger

War may be triggered by:
- Player actively declares war (relations drop to Hostile)
- Neighbor declares war (Hostile relations + neighbor aggression check)
- Diplomatic crisis escalation
- Border conflict spiraling out of control

### 14.2 Military Units

#### Tribal Age

| Unit | Cost (gold) | Attack | Defense | Movement | Special |
|------|------------|--------|--------|--------|------|
| Militia (MLT) | 20 | 2 | 1 | 1 | Lowest cost, morale easily breaks |
| Hunter (HNT) | 30 | 3 | 1 | 2 | Forest terrain Advantage (ADV) |
| Clubman (CLB) | 25 | 2 | 2 | 1 | Cheap defensive unit |

#### City-State Age

| Unit | Cost | Attack | Defense | Movement | Special |
|------|------|--------|--------|--------|------|
| Infantry (INF) | 50 | 5 | 4 | 1 | Basic regular army |
| Archer (ARC) | 60 | 6 (ranged) | 2 | 1 | Range 2, siege −50% |
| Scout (SCT) | 40 | 2 | 1 | 3 | Vision +3, can recon |
| Light Cavalry (LCV) | 80 | 6 | 2 | 3 | Charge: first hit +3 |
| Spearman (SPR) | 55 | 4 | 6 | 1 | Counters cavalry |

#### Kingdom Age

| Unit | Cost | Attack | Defense | Movement | Special |
|------|------|--------|--------|--------|------|
| Heavy Infantry (HVY) | 120 | 8 | 10 | 1 | Position defense +5 |
| Knight (KNT) | 200 | 12 | 8 | 3 | Charge damage ×2 |
| Battering Ram (RAM) | 300 | 15 (siege) | 4 | 1 | Only effective vs buildings |
| Crossbowman (CRB) | 100 | 9 (ranged) | 3 | 1 | Range 3 |
| Warship (WSH) | 250 | 8 | 6 | 3 (water) | Naval unit |

#### Empire Age

| Unit | Cost | Attack | Defense | Movement | Special |
|------|------|--------|--------|--------|------|
| Royal Guard (RGD) | 400 | 14 | 14 | 2 | Whole army morale +2 |
| Cannon (CAN) | 500 | 20 (siege) | 3 | 1 | Range 4, area attack |
| Dragon Knight (DRK) | 800 | 18 | 10 | 4 | Flying unit, ignores terrain |
| Colonial Troops (COL) | 150 | 6 | 5 | 2 | Recruitable in colonies |

#### Legendary Age

| Unit | Cost | Attack | Defense | Movement | Special |
|------|------|--------|--------|--------|------|
| Golem Legion (GLM) | 1,000 | 20 | 25 | 1 | Immune to morale effects |
| Sky Fleet (SKF) | 2,000 | 25 | 15 | 5 (flying) | Can attack any terrain target |
| Archmage (ARM) | 1,500 | 30 (magic) | 5 | 2 | Area magic attack |

### 14.3 War Turn Structure

After entering war, each turn is divided into the following phases:

1. **Intelligence Phase:** Both sides gain intel on enemy forces (requires scout/spy)
2. **Deployment Phase:** Move forces, deploy formations
3. **Engagement Phase:** Both sides roll for Opposed Check

```
Battle Result = 1d20 + Military (MIL) Modifier (MOD) + Commander Tactics (TAC) + Terrain Adjustment

Damage Calculation:
If attacker wins:
    Damage Value = Attack − Defense + (dice difference ÷ 2)
    Enemy Units Lost = Damage Value ÷ enemy unit Defense (at least 1)
```

4. **Battle Resolution:** Calculate casualties, judge retreat/pursuit
5. **Morale Check:** When over half lost, make a morale check

---

### 14.4 Morale System

| Morale Value | Effect |
|--------|------|
| 100 | Whole army Advantage (ADV) |
| 75 – 99 | Normal combat |
| 50 – 74 | Each turn check whether to rout (DC 15) |
| 25 – 49 | Disadvantage (DIS), check each turn (DC 12) |
| 0 – 24 | Auto-rout — whole army retreats |

Morale is affected by:
- Commander slain: −30
- Consecutive victories: +10/battle
- Consecutive defeats: −15/battle
- Rear attacked: −20
- Hero general present: +15

### 14.5 War End Conditions

| Condition | Result |
|------|------|
| One side's army annihilated | Other side occupies territory |
| One side sues for peace | Negotiated terms (gold/territory/resource reparations) |
| Stalemate > 8 turns | Auto-enter peace talks (both sides' National Power −10) |
| Third-party intervention | Mediation — GM judges result |

### 14.6 Impact of War on National Attributes

At the end of each war turn:

```
Population (POP) decrease = Units Lost × 2
Resources (RES) decrease = War Turns × 1
Economy (ECO) decrease = War Turns × 0.5
Military (MIL) decrease = Units Lost × 0.5 (temporary)
Morale (MOR) decrease = War Turns × 1 (loser × 2)
```

---

## Chapter Fifteen: Crisis Deck and Trigger Mechanics

### 15.1 Crisis Draw

At the end of each turn, roll 1d20 to determine whether a crisis triggers:

| Roll Result | Crisis Count |
|----------|----------|
| 1 – 5 | No crisis |
| 6 – 15 | 1 crisis |
| 16 – 19 | 2 crises |
| 20 | 2 crises + special event (may be good or bad) |

### 15.2 Crisis Deck (50 cards total)

#### Natural Disaster (NAT) — 10 cards

| ID | Crisis Name | Difficulty (DC) | Impact | Resolution Method |
|------|----------|-----------|------|----------|
| NAT-01 | Flood | 15 | Resources (RES) −8, Population (POP) −5 | Resources (RES) evacuate / Technology (TEC) water works |
| NAT-02 | Severe Drought | 18 | Resources (RES) −15, food output zeroed | Resources (RES) reserve grain / Economy (ECO) import food |
| NAT-03 | Locust Swarm | 14 | Resources (RES) −10 | Military (MIL) drive off / Technology (TEC) pesticide |
| NAT-04 | Plague Spread | 20 | Population (POP) −15, Morale (MOR) −10 | Technology (TEC) develop cure / Military (MIL) quarantine |
| NAT-05 | Earthquake | 22 | Resources (RES) −10, all building durability −20% | Resources (RES) rebuild / Economy (ECO) emergency funding |
| NAT-06 | Blizzard | 16 | Resources (RES) −5, food consumption ×2 (this turn) | Resources (RES) material dispatch |
| NAT-07 | Forest Fire | 17 | Resources (RES) −12, forest coverage declines | Military (MIL) mobilize firefighting / Technology (TEC) weather magic |
| NAT-08 | Beast Tide | 16 | Population (POP) −5, Resources (RES) −5 | Military (MIL) defense |
| NAT-09 | Meteor Fall | 25 | All attributes −5, produces special mineral resource | Technology (TEC) research / Military (MIL) blockade region |
| NAT-10 | Tsunami (coastal only) | 20 | Population (POP) −20, Resources (RES) −15 | Technology (TEC) early warning / Resources (RES) rebuild |

#### Economic Crisis (ENC) — 10 cards

| ID | Crisis Name | Difficulty (DC) | Impact | Resolution Method |
|------|----------|-----------|------|----------|
| ENC-01 | Inflation | 14 | Economy (ECO) −8 | Economy (ECO) regulate |
| ENC-02 | Trade Partner Bankruptcy | 16 | Economy (ECO) −10 | Economy (ECO) find new market |
| ENC-03 | Fiscal Deficit | 15 | Gold zeroed (if negative then Morale −5) | Economy (ECO) raise taxes / Morale (MOR) raise donations |
| ENC-04 | Food Price Surge | 13 | Morale (MOR) −5, gold expenditure ×2 | Economy (ECO) price control |
| ENC-05 | Currency Counterfeiting Crisis | 18 | Economy (ECO) −12 | Technology (TEC) anti-counterfeit tech / Military (MIL) crackdown |
| ENC-06 | Major Vein Depletion | 17 | Resources (RES) −10 | Technology (TEC) prospecting / Economy (ECO) import |
| ENC-07 | Trade Route Cut | 16 | Economy (ECO) −8 | Military (MIL) escort / diplomacy rebuild route |
| ENC-08 | Speculative Bubble Burst | 19 | Economy (ECO) −15, Morale (MOR) −8 | Economy (ECO) bailout |
| ENC-09 | Neighbor Dumping | 15 | Economy (ECO) −5, domestic industry damaged | Economy (ECO) tariff / Technology (TEC) industry upgrade |
| ENC-10 | Bank Run | 20 | Economy (ECO) −20 | Economy (ECO) deposit insurance / Morale (MOR) reassurance |

#### Diplomatic Crisis (DIP) — 10 cards

| ID | Crisis Name | Difficulty (DC) | Impact | Resolution Method |
|------|----------|-----------|------|----------|
| DIP-01 | Border Conflict | 17 | Relations with neighbor −20 | Military (MIL) counterattack / diplomatic negotiation |
| DIP-02 | Envoy Detained | 16 | Relations −30 | Diplomatic negotiation / Military (MIL) rescue |
| DIP-03 | Neighbor Coup | 15 | Relations reset, trade cleared | Diplomatic recognition of new regime / Military (MIL) intervention |
| DIP-04 | Trade Sanctions | 18 | Economy (ECO) −10 | Diplomatic thaw / Economy (ECO) find alternative market |
| DIP-05 | Ally Internal Unrest | 14 | Ally cannot fulfill alliance obligations | Military (MIL) send aid / diplomatic mediation |
| DIP-06 | Spy Captured | 20 | Relations −40, hero may be executed | Diplomatic negotiation / Military (MIL) rescue operation |
| DIP-07 | Marriage Alliance Broken | 15 | Relations −25 | Diplomatic repair |
| DIP-08 | Neighbor Declares War | 22 | Enters war state | Respond to war |
| DIP-09 | International Isolation | 16 | All relations −10, trade −50% | Diplomatic PR |
| DIP-10 | Refugee Crisis | 14 | Population (POP) +10 (short-term pressure), Morale (MOR) −5 | Resources (RES) resettlement / Military (MIL) border control |

#### Internal Crisis (INT) — 10 cards

| ID | Crisis Name | Difficulty (DC) | Impact | Resolution Method |
|------|----------|-----------|------|----------|
| INT-01 | Noble Rebellion | 20 | Morale (MOR) −15, Military (MIL) −10 | Military (MIL) suppress / negotiate compromise |
| INT-02 | Religious Schism | 17 | Morale (MOR) −10, population growth stalled | Morale (MOR) inclusive policy / Military (MIL) crackdown |
| INT-03 | Strike Wave | 14 | Construction efficiency −50% | Economy (ECO) raise wages / Military (MIL) forced return to work |
| INT-04 | Succession Dispute | 18 | Morale (MOR) −10, possible civil war | Morale (MOR) establish succession law |
| INT-05 | Corruption Scandal | 15 | Morale (MOR) −5, Economy (ECO) −5 | Military (MIL) anti-corruption action |
| INT-06 | Immigration Wave | 13 | Population (POP) −10 | Economy (ECO) improve living conditions / Military (MIL) seal border |
| INT-07 | Famine Riot | 16 | Morale (MOR) −15, Resources (RES) −5 | Resources (RES) distribute reserve grain / Military (MIL) suppress |
| INT-08 | Witch Panic | 17 | Technology (TEC) −5, Morale (MOR) −8 | Technology (TEC) rational education / Morale (MOR) reassurance |
| INT-09 | Slave Revolt (if applicable) | 19 | Population (POP) −10, Resources (RES) −10 | Military (MIL) suppress / Economy (ECO) abolition compensation |
| INT-10 | Spy Infiltration (foreign instigation) | 20 | Military (MIL) −10, Technology (TEC) secrets leaked | Military (MIL) counter-espionage / Technology (TEC) encryption |

#### Supernatural Crisis (SUP) — 10 cards

| ID | Crisis Name | Difficulty (DC) | Impact | Resolution Method |
|------|----------|-----------|------|----------|
| SUP-01 | Undead Invasion | 22 | All attributes −5 | Military (MIL) + Technology (TEC) |
| SUP-02 | Magic Storm | 20 | Technology (TEC) −10, magic disabled | Technology (TEC) stabilize magic field |
| SUP-03 | Alien Rift | 25 | All attributes continuously decline | Technology (TEC) close rift + Military (MIL) defend against extraplanar beings |
| SUP-04 | Divine Trial | 28 | All attributes −10 | Morale (MOR) sacrifice / Technology (TEC) theology research |
| SUP-05 | Curse Spread | 18 | Population (POP) −5/turn | Technology (TEC) break curse |
| SUP-06 | Dragon King Awakens | 26 | All attributes huge threat | Military (MIL) slay dragon / Morale (MOR) sacrifice to sue for peace |
| SUP-07 | Time Anomaly | 24 | Turn effects randomly doubled/zeroed | Technology (TEC) chrono magic |
| SUP-08 | Demon Contract Expiry | 23 | Economy (ECO) +20 (short-term), but… | Technology (TEC) renegotiate / Military (MIL) break pact and fight |
| SUP-09 | Earth Spirit's Wrath | 22 | Resources (RES) −20 | Morale (MOR) sacrificial appeasement / Technology (TEC) spirit communication |
| SUP-10 | Apocalypse Prophecy | 20 | Morale (MOR) −20 (panic) | Morale (MOR) reassurance / Technology (TEC) research truth |

### 15.3 Crisis Severity Dynamic Adjustment

| National Power (NP) | Crisis DC Adjustment | Description |
|-----------|------------|------|
| 1 – 20 | DC −5 | Newbie protection |
| 21 – 50 | DC −2 | Growth period |
| 51 – 120 | DC +0 | Normal |
| 121 – 200 | DC +3 | "With great power comes great responsibility" |
| 200+ | DC +5 | God-level trial |

> This table is the **only** National Power adjustment source for the Unified Crisis DC Framework (13.5); for general tasks see 13.1.

---

## Chapter Sixteen: Neighbor AI System

### 16.1 Neighbor Behavior Patterns

When managing neighbors, the GM uses the following simplified process:

Each turn, for each neighbor, execute:

```
1. Roll 1d6 to decide action tendency (ACTION)
2. Execute action based on relations value and action tendency
3. Update the neighbor's own attributes
```

| Action Tendency (1d6) | Behavior |
|----------------|------|
| 1 | Aggressive: launch attack/declare war/expand |
| 2 | Diplomatic: propose agreement/alliance/marriage |
| 3 | Defensive: build defenses/strengthen border |
| 4 | Economic: develop trade/invest in construction |
| 5 | Introverted: handle internal affairs |
| 6 | Opportunistic: choose the most advantageous action based on current situation |

### 16.2 Automatic Relations Change

Each turn, automatically adjust neighbor relations based on the following factors:

| Factor | Change |
|------|------|
| Shared border | −1 (borders bring friction) |
| Active trade | +1 (per trade route) |
| Military alliance | +2 |
| National Power gap > 30 | −1 (weak side fears, strong side is arrogant) |
| Same race share > 50% | +1 |
| Long-term no conflict (> 10 turns) | +1 |
| Spy activity discovered | −15 |

### 16.3 Neighbor Autonomous Development

Each neighbor also follows the same Era Progression rules, but the pace is controlled by the GM according to narrative needs. Suggestions:

- Initial neighbors develop in sync with the player
- Distant great powers may be one era ahead of the player
- The Legendary Age is limited to the player and very few factions

---

## Chapter Seventeen: Setting — The Continent of Elden

### 17.1 World Overview

**Elden** is a vast new continent. Five hundred years ago, the civilization of the old continent was destroyed in "The Sundering" — a magical disaster of unknown cause that tore apart the order of the old world. Survivors arrived at Elden aboard battered fleets, and discovered that this land already held ancient ruins, unknown magic, and many intelligent races that were mere legend in the old world.

### 17.2 Creation Myth

The natives of Elden (Elves, Dwarves, Dragonborn, etc.) share a common myth:

> In the beginning of the world, five creator gods each created a race: the Earth God "Gran" shaped the Dwarves, the Life God "Sylva" awakened the Elves, the War God "Karn" granted life to the Orcs, the Wisdom God "Minerva" enlightened the Dragonborn, and the Fate God "Fatum" created Humans.
>
> But Fatum felt Humans were too fragile, so he borrowed power from the other four gods — the Dwarves' resilience, the Elves' agility, the Orcs' courage, the Dragonborn's majesty — and blended them into Humanity's infinite possibility. This is also why Humans can coexist peacefully with any race.

### 17.3 Magic System

Magic in Elden is a **natural force** — like wind and water. Magic originates from the "Ley Lines" — energy lines running through the earth.

| Magic Type | Source | User |
|----------|------|--------|
| Arcane Magic | Direct extraction from Ley Lines | Mages, wizards (requires talent + training) |
| Divine Magic | Granted by gods | Priests, paladins (requires faith) |
| Nature Magic | Life energy | Druids, rangers (requires resonance with nature) |
| Rune Magic | Ancient runes | Dwarf runesmiths (requires inheritance) |
| Alchemy | Material combination | Anyone (requires equipment + knowledge) |

### Mana (MP) System

Casting spells and some hero skills cost **Mana (MP)**:

- **Mana Cap (MP_MAX)** = 10 + Knowledge (KNW) × 2 (Scholar-type heroes usually highest).
- **Recover per turn**: rest one turn to recover 5; rest in town/temple recovers 10.
- **Cost**: common spells 2–5 points; powerful spells 6–10 points.
- **Replenish**: "Lesser Mana Potion" recovers 10 Mana (see item catalog).

### Casting Rules

```
Casting Check: 1d20 + corresponding hero attribute (base value) ≥ Spell Difficulty Class (DC)
Casting Attribute: Arcane / Nature = Knowledge (KNW); Divine = Charisma (CHA); Rune / Alchemy = Craft (CRF)
Failure: waste Mana (MP) and no effect; Critical Failure (natural 1): Mana (MP) backlash, self takes 1d6 damage
```

> For the complete spell list and hero skill details, see [Chapter Twenty-Six: Complete Hero Skills and Spell List](#第二十六章英雄技能與法術完整清單).

### 17.4 Historical Timeline

| Year | Event |
|------|------|
| 0 AE (After Exodus) | Human refugee fleets arrive at Elden's east coast |
| 50 AE | First cross-race settlement "Sunrise Port" established |
| 150 AE | Discovery of first ancient ruin — "Tower of the Void" |
| 200 AE | First cross-race great war — "War of Division" |
| 350 AE | "Peace Accord" signed, factions delimit borders |
| 480 AE | Last confirmed Dragon King sighting |
| 500 AE | **Game begins** — a new round of power reshuffling is brewing |

---

## Chapter Eighteen: Starting Region Setup

### Optional Starting Regions (6)

#### Region A: Emerald River Valley

| Item | Content |
|------|------|
| Terrain | Riverside plains |
| Resource Advantage | Fertile soil (agriculture +20%), fresh water, convenient river transport |
| Resource Disadvantage | Lacks stone and minerals |
| Initial Threat | River pirates, spring floods |
| Initial Neighbor | "Stone Cliff Tribe" (mostly Dwarf, neutral attitude) |

#### Region B: Black Forest Edge

| Item | Content |
|------|------|
| Terrain | Forest edge |
| Resource Advantage | Abundant wood, game, herbs, magic materials |
| Resource Disadvantage | Limited farmland, limited visibility |
| Initial Threat | Beasts in the forest, guardians of Elven ancient ruins |
| Initial Neighbor | "Silverleaf Elven Kingdom" (Elf, cold attitude) |

#### Region C: Ironridge Foothills

| Item | Content |
|------|------|
| Terrain | Mountains |
| Resource Advantage | Rich veins (iron, copper, gems), natural defense |
| Resource Disadvantage | Scarce farmland, poor transport |
| Initial Threat | Goblin tribes in the mountains, avalanches |
| Initial Neighbor | "Deepforge Dwarven Kingdom" (Dwarf, friendly attitude — as long as you don't touch their mines) |

#### Region D: Azure Coast

| Item | Content |
|------|------|
| Terrain | Coast |
| Resource Advantage | Seafood, salt, natural harbors, trade potential |
| Resource Disadvantage | Typhoons, pirates, insufficient fresh water |
| Initial Threat | Pirate fleets, marine creatures |
| Initial Neighbor | "Coral Isle Sea Elves" (Half-Elf, neutral attitude, keen on trade) |

#### Region E: Golden Plains

| Item | Content |
|------|------|
| Terrain | Open plains |
| Resource Advantage | Best agro-pastoral land, open visibility |
| Resource Disadvantage | Lacks natural barriers, must import wood and stone |
| Initial Threat | Nomadic Orc tribes, grassland wildfires |
| Initial Neighbor | "Gale Clan" (Orc, hostile attitude — they believe the plains are theirs) |

#### Region F: Mistmarsh Highlands

| Item | Content |
|------|------|
| Terrain | Highland marsh |
| Resource Advantage | Rare herbs, magic springs, unique resources |
| Resource Disadvantage | Difficult construction, disease risk |
| Initial Threat | Marsh monsters, poison fog season |
| Initial Neighbor | "Misthidden Dragonborn Lair" (Dragonborn, cold and mysterious attitude) |

---

## Chapter Nineteen: Preset Neighbor Nations and Factions

### 19.1 Major Factions (12)

| ID | Name | Race | Era | National Power | Attitude Baseline | Trait |
|------|------|------|------|------|----------|------|
| N01 | Iron Crown Kingdom | Human | Kingdom | 85 | Cold (−20) | Old-continent noble descendants, self-claimed legitimate |
| N02 | Deepforge Dwarven Kingdom | Dwarf | Kingdom | 72 | Friendly (+25) | Largest weapons exporter |
| N03 | Silverleaf Elven Kingdom | Elf | City-State | 48 | Cold (−10) | Guards ancient forests, xenophobic |
| N04 | Rageflame Orc Khanate | Orc | City-State | 55 | Hostile (−60) | Worships force, constantly expanding |
| N05 | Sunrise Port Free City | Human + Halfling | City-State | 42 | Friendly (+30) | Largest trade port |
| N06 | Dragonridge Dragonborn Alliance | Dragonborn | Kingdom | 68 | Neutral (+0) | Ancient and mysterious, does not easily intervene |
| N07 | Southern Gnome Republic | Gnome | City-State | 40 | Friendly (+20) | Most technologically advanced nation |
| N08 | Icepeak Goliath Tribe | Goliath | Tribe | 28 | Neutral (+5) | Isolated tribe in the mountains |
| N09 | Blood Moon Pirate Federation | Mixed | City-State | 35 | Hostile (−40) | Plunders coasts, refuses diplomacy |
| N10 | Dawn Doctrine State | Human | City-State | 45 | Friendly (+15) | Religious state, eager to proselytize |
| N11 | Void Cult | Mixed | City-State | 38 | Hostile (−70) | Worships ancient beings, rejected by all nations |
| N12 | Emerald Merchant Alliance | Halfling | City-State | 50 | Friendly (+35) | Controls most of the continent's trade routes |

### 19.2 Faction Relations Web

```
Iron Crown Kingdom ←→ Silverleaf Elf ←→ Dragonridge Alliance  (old-power axis, mutual respect but not necessarily allied)
    ↓ Hostile
Rageflame Orc ←→ Icepeak Goliath                  (grassland and plains generational feud)
    ↑ Neutral
Emerald Merchant ←→ Sunrise Port ←→ Southern Gnome    (trade axis, economically interdependent)
    ↓ Hostile
Blood Moon Pirate ←→ Sunrise Port                  (sea-power struggle)
    ↓ Hostile (ideological)
Dawn Doctrine ←→ Void Cult                          (religious holy war)
```

---

## Chapter Twenty: GM Turn Operation Manual

### 20.1 Per-Turn GM Checklist

```
【Phase 1: Season Announcement】
☐ Announce current season
☐ Announce seasonal effect
☐ Describe climate, environment, domestic mood
☐ Hint at upcoming seasonal events

【Phase 2: Receive Player Actions】
☐ Listen to player declare 3 major actions
☐ Set applicable attribute and Difficulty Class (DC) for each action (don't tell player)
☐ Confirm whether Advantage (ADV)/Disadvantage (DIS) applies

【Phase 3: Action Check and Resolution】
☐ Player rolls dice
☐ Announce result (use narrative language, don't report numbers)
☐ Record attribute changes
☐ Update nation character sheet data

【Phase 4: Crisis Trigger and Resolution】
☐ Roll 1d20 to decide crisis trigger
☐ Draw corresponding number from Crisis Deck
☐ Describe crisis situation
☐ Player chooses resolution method and rolls
☐ Settle crisis effect

【Phase 5: Turn-End Settlement】
☐ Calculate Tax (TAX)
☐ Deduct food consumption (FOD)
☐ Grant Research Points (RP)
☐ Deduct building maintenance
☐ Calculate population change
☐ Check era upgrade conditions
☐ Update all neighbor relations
☐ Advance neighbor actions
☐ Record turn count and year
☐ Check scenario progress (trigger plot events)
```

### 20.2 Pacing Control Suggestions

| Era | Suggested Time | Notes |
|------|----------|----------|
| Tribal Age | 10–15 min/turn | Brisk pace, let players feel growth |
| City-State Age | 15–25 min/turn | Introduce diplomatic complexity |
| Kingdom Age | 25–35 min/turn | War, intrigue, multi-threading |
| Empire Age | 30–45 min/turn | Complex governance, slow and weighty |
| Legendary Age | Flexible | No longer bound to normal pace |

### 20.3 Single Game Suggestions

| Game Type | Turns | Era Range | Actual Time |
|----------|--------|----------|----------|
| Beginner Intro | 10–15 turns | Tribal Age | 2–3 hours |
| Short Scenario | 30–50 turns | Tribal→City-State | 4–6 hours (can split) |
| Full Scenario | 80–120 turns | Tribal→Kingdom | Multiple sessions (campaign mode) |
| Epic Campaign | 200+ turns | All five eras | Long-term campaign |

---

## Chapter Twenty-One: Solo Game Hosting Guide

### 21.1 Specifics of Solo Play

The default module supports solo (1 GM + 1 player). The following are notes specific to solo mode:

1. **The GM must also play the opponent:** The neighbors you control must have strategic thinking — not random actions, but goals and personality.
2. **No teammates to share the burden:** Every player decision bears consequences alone. Ensure failure is not a dead end — always provide a "Plan B."
3. **Side NPC characters matter:** The player's advisors, generals, and family fill the gaps.

### 21.2 Side NPC Design

Design 3–5 core side NPCs for the player:

| Role | Function | Example Personality |
|------|------|----------|
| **Chancellor/Chief Advisor** | Provide advice, manage daily affairs | Cautious conservative / radical reformer |
| **General** | Military advice, command the front | Loyal veteran / ambitious |
| **Finance Minister** | Economic data analysis | Stingy actuary / generous investor |
| **Heir** | Personal emotional arc, future security | Green but smart / rebellious |
| **Close Friend/Mentor** | Emotional support, ethical guidance | — |

Each side NPC has:
- name, age, personality traits
- loyalty to the nation and personal goals
- relationship with the player character

### 21.3 Solo Player "Safety Nets"

| Safety Net Mechanism | Description |
|------------|------|
| **Mandate Reroll** | Once per era may reroll (not limited to own actions) |
| **Inheritance Mechanism** | On ruler death, heir takes over (retains 70% of nation data) |
| **Exile Government** | When nation is destroyed, may lead remnants into exile to rebuild elsewhere (retains 50%) |
| **Turning Point of Fate** | After a major failure, the GM offers a "glimmer in the darkness" choice |

### 21.4 Multiplayer Variant (Optional)

If more than 1 player, the following modes may be used:

**A. Each Their Own:** Each player governs an independent nation (suited for 2–4 players). They may ally or oppose each other.

**B. Coalition Cabinet:** All players jointly govern one nation, each responsible for a domain:
- King (final decision-maker)
- General (military)
- Finance Minister (economy)
- Archmage/Chief Scholar (technology)
- Foreign Minister

**C. Faction Conflict:** Players split into two factions, each governing a nation.

---

## Chapter Twenty-Two: Scenario Running Guide

### 22.1 Five Scenarios Overview

| Scenario | Era Range | Turns | Difficulty | Core Theme |
|------|----------|--------|------|----------|
| S1: Wilderness Birth | Tribal → City-State | ~40 turns | ★☆☆ | Survival, foundation, first choices |
| S2: Three-Way Standoff | City-State → Kingdom | ~60 turns | ★★☆ | Competition, diplomacy, war |
| S3: Empire's Legacy | Kingdom | ~50 turns | ★★★ | Exploration, moral choices, ancient legacy |
| S4: The Darkest Age | Kingdom → Empire | ~70 turns | ★★★★ | Survival crisis, sacrifice, civilization's ember |
| S5: War of Succession | Empire → Legendary | ~60 turns | ★★★★★ | Internal rupture, legendary finale |

### 22.2 Scenario Trigger Conditions

The GM should introduce plot events when the scenario's corresponding era and turn count are reached. It need not strictly follow turn counts — flexibly adjust to player progress.

### 22.3 Scenario Structure Example (S1: Wilderness Birth)

| Chapter | Turn | Content | Key Event |
|------|------|------|----------|
| 1. Landing | 1–5 | Explore starting region, establish first camp | Choose settlement, first construction |
| 2. First Winter | 5–8 | Survive the trial of the first harsh winter | Food crisis, first crisis handling |
| 3. Expansion Period | 9–20 | Population growth, explore surroundings | Discover resource points, meet neighbors |
| 4. Neighbor's Shadow | 21–30 | Diplomatic maneuvering with neighbors | First diplomatic choice |
| 5. Becoming a City-State | 31–40 | Population exceeds 250, enter new era | Era upgrade, new map unlocked |

### 22.4 Free Mode

Beyond applying preset scenarios, the GM may also run "Free Mode" — no preset plot, letting player choices and the crisis system naturally drive the story. Suited for players who enjoy a sandbox experience.

---

## Chapter Twenty-Three: Optional Rules and Variants

### 23.1 Simplified Mode (Quick Game)

Suited for beginners or time-limited sessions:

- No hero system
- No Racial Satisfaction tracking
- Crisis triggers every 2 turns
- Era thresholds halved
- Construction consumes no turn (only gold)

### 23.2 Hardcore Mode

Suited for veteran players who enjoy challenge:

- Crisis difficulty +3
- Food consumption ×1.5
- No safety net (cancel Mandate Reroll)
- Winter lasts 2 turns

### 23.3 Peace Mode

Suited for players who dislike war:

- Cannot actively declare war
- Neighbor aggression reduced
- Diplomacy becomes the main conflict resolution
- Increase possibility of trade and cultural victory

### 23.4 Mythic Mode

Suited for players who enjoy fantasy elements:

- Increase supernatural crisis trigger rate
- Add god-interaction system
- Heroes may gain divinity
- Legendary Age threshold lowered

### 23.5 Legendary Deeds System (Optional)

When the player completes a major achievement, grant a "Legendary Deed":

| Deed | Trigger Condition | Reward |
|------|----------|------|
| "First Foundation Stone" | Build first building | Permanent +1 to any attribute |
| "Winter Survivor" | Successfully survive first winter | Winter resistance +20% |
| "Diplomacy Master" | Establish friendly relations with 5 nations | Diplomatic actions permanently gain Advantage (ADV) |
| "Conqueror" | Occupy a nation | Military (MIL) permanent +5 |
| "Peacemaker" | End a war exceeding 10 turns | Morale (MOR) permanent +10 |
| "Legendary Age" | Enter Legendary Age | Unlock god interaction |

---

## Chapter Twenty-Four: Status Effects Complete Rules

The following status effects apply to heroes and monsters (nation-level crises are handled separately by the Crisis Deck). A single target may stack different statuses, but the same status does not stack in layers — only its duration refreshes.

| Status | Source | Effect | Duration | Removal |
|------|------|------|------|------|
| Stun (STUN) | Blunt force, shock spell | Skip this turn's action | 1 turn | Auto-removed at turn end |
| Poison (PSN) | Poison blade, poison fog, spider | −3 Hit Points (HP) per turn | 2–3 turns | Antidote, rest |
| Burn (BURN) | Torch, flame spell | −2 Hit Points (HP) per turn, not reduced until extinguished | 1–3 turns | Roll/water, extinguish |
| Prone (PRONE) | Knockback, trip | All attacks against it have Advantage (ADV) until it stands | Until stands | 1 move action to stand |
| Petrify (PETR) | Petrifying gaze, rune trap | Cannot act, treated as Defense +10 | 3 turns | Stone-to-flesh spell |
| Confuse (CONF) | Confusion spell, mental attack | Actions random (decided by roll) | 2 turns | Rest, clarity spell |
| Bind (BIND) | Vines, webs, chains | Cannot move, major action requires escape check | Until escaped | Escape check DC 12 |
| Fear (FEAR) | Dragon aura, terrifying sight | Flee fear source, cannot attack voluntarily | 2 turns | Will check DC 12 |
| Bleed (BLEED) | Pierce, tear wound | −2 Hit Points (HP) per turn | Until treated | First aid, bandage |
| Rally (RALLY) | General's order, war song | Attack +2, morale +1 | 3 turns | — |

> All persistent damage (Poison / Burn / Bleed) stops calculating when the target's Hit Points (HP) reach 0. Status effects do not affect the National Six Dimensions; they act only on individuals in combat.

## Chapter Twenty-Five: Random Wilderness Encounter Tables

When exploring the wilderness, patrolling borders, or sending heroes on field missions, the GM may roll 1d20 on these tables. Encounter Level (CL) corresponds to experience and resource rewards granted (see Monster Manual Challenge Rating).

### Forest / Mountains

| 1d20 | Encounter | Note |
|------|------|------|
| 1-5 | Nothing (resource point: herbs/ore) | May gather +5 building materials |
| 6-9 | Wolf Pack (CL 1) | 2–3, cooperative surround |
| 10-12 | Goblin Patrol (CL 2) | May lead to camp |
| 13-15 | Giant Bear (CL 3) | Single strong foe |
| 16-17 | Ogre (CL 4) | Drops rare materials |
| 18-19 | Treant/Stone Elemental (CL 5) | Nature guardian |
| 20 | Dragonborn (CL 6) | Rare, may negotiate |

### Plains / Coast

| 1d20 | Encounter | Note |
|------|------|------|
| 1-6 | Nothing (wandering caravan) | May trade |
| 7-10 | Bandits (CL 2) | Rob or recruit |
| 11-13 | Exiled Refugees (CL 1) | Accept +population |
| 14-16 | Pirates/Cavalry (CL 3) | Sea/plains raid |
| 17-18 | Griffin/Giant Crocodile (CL 4) | Beast |
| 19-20 | Expeditionary Outpost (CL 5) | Neighbor force |

### Ruins / Supernatural

| 1d20 | Encounter | Note |
|------|------|------|
| 1-5 | Trap (mechanism DC 14) | Injury on failure |
| 6-9 | Skeleton Guard (CL 2) | Undead guardian |
| 10-13 | Wraith (CL 3) | Mental attack |
| 14-16 | Rune Golem (CL 4) | Must solve runes |
| 17-19 | Ancient Gatekeeper (CL 6) | Legacy guardian |
| 20 | Void Walker (CL 8) | Legendary threat |

## Chapter Twenty-Six: Complete Hero Skills and Spell List

### General Skills

| Skill | Check | Effect |
|------|------|------|
| Scouting | Intelligence/Wisdom | Discover hidden threats or resources (DC 10–15) |
| First Aid | Intelligence | Restore target 1d6+2 Hit Points (HP) |
| Riding | Dexterity | Ride a mount, Movement +2 |
| Intimidation | Charisma (CHA) | Inflict Fear (FEAR) on those weaker than self |
| Climbing | Strength/Dexterity | Climb walls/terrain (DC 12) |

### Spell List (consumes Mana MP)

> ▶ **The complete spell list is compiled separately in `assets/魔法圖鑑.md` (with `魔法圖鑑.yaml`)**, categorized by magic type (Arcane / Divine / Nature / Rune / Alchemy / Chrono), including casting attribute, Difficulty Class (DC), Mana (MP), Cooldown (CD), and effects; the GM and players should consult that catalog directly.

**General Casting Rules**: `1d20 + corresponding hero attribute (base value) ≥ Spell Difficulty Class (DC)`, on failure waste Mana (MP) with no effect. Critical Success (natural 20) spell effect ×1.5 and costs no extra Mana (MP); Critical Failure (natural 1) Mana (MP) backlash 1d6 self-damage. Spells marked with CD must wait that many turns after casting before being cast again; high-tier spells (Meteor Strike, Time Stop) are limited by CD to prevent a single hero from endlessly clearing the field.

## Chapter Twenty-Seven: Monster Combat and War Integration

### Monster Value Generation

Monsters in the *Monster Manual* are divided into two types; the GM should choose based on context to avoid conflict between "catalog values" and "formula values":

1. **Named Bosses (catalog hand-tuned values):** The Hit Points (HP) / Attack (ATK) / Defense (DEF) / loot listed for each catalog entry (Goblin, Young Red Dragon, Fallen God, etc.) are baseline values **hand-tuned** by the designer for feel, suited to key scenario battles, boss fights, and named encounters. Apply catalog values directly.
2. **Generic Wild Monsters (formula-generated):** Used for random encounters, mob groups, and quick generation. Apply the following formula by Challenge Rating (CR):

```
Monster Hit Points (HP) = 10 + CR × 5
Monster Attack (ATK) = CR × 2 + 2
Monster Defense (DEF) = 8 + CR × 1.5 (rounded)
Monster Reward (exp/resources) = CR × 10 gold equivalent
```

> Note: High Challenge Rating (CR ≥ 10) monsters are **army- or multi-squad-scale encounters**; it is not recommended for a single hero to face them alone (see "Hero-Scale Encounter Table" below).

### Hero vs Monster (Personal Combat Rules)

- **Hero Hit**: 1d20 + corresponding hero attribute ≥ monster Defense (DEF)
- **Monster Hit**: 1d20 + monster Attack (ATK) ≥ hero Defense (DEF)
- **Hero Defense (DEF)** = 10 (base) + armor bonus (Leather Armor +2, Chainmail +4, Plate Armor +6, Dragon Scale Armor +10, etc.)
- **Monster Damage**: On hit deals monster Attack (ATK) damage, then subtract the hero's **armor bonus** (minimum 1). I.e., actual damage = monster ATK − armor bonus (minimum 1)

With this model, armor provides both an "evasion chance" (raising hero Defense (DEF) so the monster may fail its roll) and "damage reduction" (lowering actual damage after a hit), no longer being merely cosmetic.

### War Scale vs Hero Scale

- **National War** (Chapter Fourteen): Uses military units (Attack/Defense/Movement), affects the National Six Dimensions.
- **Hero Combat** (this chapter and Chapter Eleven): Uses individual Hit Points (HP)/Defense (DEF), affects a single hero's life or death.
- **Cross-over**: A general in war can provide "Tactical Command" +2 attack to their troops (see Chapter Fourteen military units); a hero infiltrating behind enemy lines can single-handedly assassinate an enemy commander, directly reducing enemy morale (morale −10).
- **Monster vs Army Conversion**: When a monster attacks a military unit, damage = monster ATK − unit Defense (DEF) (minimum 1), and unit losses are settled per Chapter Fourteen war rules.

### Hero-Scale Encounter Table

| Hero Scale | Suggested CR Cap | Description |
|----------|-------------|------|
| Single hero | CR 6 | Beyond suggested value, rely on terrain, items, or retreat |
| Hero squad (2–3) | CR 12 | Can cooperate against boss-level monsters |
| Hero + army | CR 10+ | Apply "Monster vs Army Conversion" for combined combat |

---

## Appendix Two

### A. Quick Reference — GM Common Formulas

```
Standard Check:    1d20 + MOD ≥ DC
Opposed Check:     Both sides 1d20 + MOD, higher wins
War Damage:        Attack − Defense + (dice diff ÷ 2)
Crisis Trigger:    Roll 1d20 (1-5 none / 6-15 one / 16-19 two / 20 special)
National Power (NP):    Population (POP) × 0.5 + Resources (RES) + Economy (ECO) + Military (MIL)
Tax (TAX):         Economy (ECO) × Population (POP) × 0.01
Food Consumption (FOD):  Population (POP) × 0.8 (Winter × 1.3)
Research Points (RP):    Technology (TEC) × 0.5
Gold (GOLD):       Starting 150 + per turn (Tax (TAX) − maintenance)
Food (FOOD):       Starting 200 + Σ food output (Autumn ×2) − food consumption (FOD)
Natural Population Growth:  Population (POP) × growth rate (3%~4%) × racial modifier, cap Population Cap (CAP)
Hero Hit Points (HP):  20 + Might (ATK) × 4 + Constitution (CON) × 2
```

### B. Quick Reference — Era Thresholds

| Era | Condition | Unlock DC Baseline |
|------|------|------------|
| Tribal → City-State | Population (POP) > 250 | DC 10–12 |
| City-State → Kingdom | National Power (NP) > 150 + city walls | DC 13–16 |
| Kingdom → Empire | National Power (NP) > 350 + ally | DC 17–20 |
| Empire → Legendary | Technology (TEC) > 150 + event | DC 21–30 |

### C. Scenario File Index

| File | Content |
|------|------|
| `scenarios/S1_荒野新生.md` | Scenario One full content (human-readable) |
| `scenarios/S1_荒野新生.yaml` | Scenario One structured data (for AI GM) |
| `scenarios/S2_三方鼎立.md` | Scenario Two full content |
| `scenarios/S2_三方鼎立.yaml` | Scenario Two structured data |
| ... | ... |

### D. Excel Character Sheet Index

| File | Content |
|------|------|
| `sheets/空白玩家角色卡.xlsx` | Blank nation character sheet (with formulas) |
| `sheets/空白NPC角色卡.xlsx` | Blank NPC character sheet |
| `sheets/空白敵人角色卡.xlsx` | Blank enemy character sheet |
| `sheets/範例玩家角色卡.xlsx` | Multi-page sample character sheet |
| `sheets/NPC角色卡合集.xlsx` | All NPCs collection |
| `sheets/敵人角色卡合集.xlsx` | All enemies collection |

---

> **Ready?** You now have everything needed to run *Nation Building TRPG*.
>
> 1. Read this guide
> 2. Choose a starting region (Chapter Eighteen)
> 3. Choose a scenario (Chapter Twenty-Two, or Free Mode)
> 4. Help your players create their nations
> 5. Start the first turn
>
> **Remember:** Rules are a guide, not law. When a rule conflicts with a good story — choose the good story.
