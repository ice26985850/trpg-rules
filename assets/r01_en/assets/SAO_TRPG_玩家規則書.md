# SAO TRPG Player Rulebook

> SAO TRPG (Sword Art Online adaptation) — this document is compiled from the individual chapters of the rulebook; its contents are consistent with the original chapters.

## Chapter 1: Basic Systems

> *"This may be a game, but it's not something to be taken lightly."* — Kayaba Akihiko

---

## 1.1 Game Overview

This rule system is a tabletop role-playing game (TRPG) based on the Aincrad arc of *Sword Art Online* (SAO). Players take on the roles of players trapped in a death game, starting from Floor 1 and progressively clearing the 100 floors of the steel floating castle, with only one goal — **to survive and clear the game**.

### Core Features

- **Irreversible Death** — When HP reaches zero, the character is permanently gone. This is the core source of tension in the system.
- **Sword Skill System** — System-assisted finishing moves that consume Sword Energy (SP) and incur Recovery Lag.
- **Switch Tactics** — Alternating entry and coordinated attacks between teammates.
- **100-Floor Clearing** — Each floor has a unique theme, Maze areas, and a Floor Boss.
- **Life Skills** — A complete sub-class system including forging, cooking, fishing, and more.

---

## 1.2 Core Dice Mechanics

This game uses the **Hundred-Sided Die (D100)** as its core resolution tool.

### 1.2.1 Skill Checks

When the outcome of a character's action is uncertain and carries a risk of failure, make a skill check:

> **Roll D100 ≤ relevant attribute → Success**  
> **Roll D100 > relevant attribute → Failure**

**Difficulty Adjustment (Check Modifier):**

| Difficulty | Modifier | Description |
|-----------|----------|-------------|
| Very Easy | +40 | Almost impossible to fail |
| Easy | +20 | Achievable with basic training |
| Normal | +0 | Requires a certain level of ability |
| Hard | -20 | Requires considerable expertise |
| Very Hard | -40 | Requires top-tier proficiency |

> Example: Kirito attempts to sneak in the dark (Hard). His AGI is 65, difficulty modifier -20, check value = 65 - 20 = 45. He needs to roll ≤45 to succeed.

### 1.2.2 Contested Checks

When two characters/creatures oppose each other, both roll D100 within the range below their own attribute; **the one with the higher degree of success wins**. Degree of success = attribute - rolled value.

> Example: Kirito (AGI 65) and Klein (AGI 50) test blades. Kirito rolls 23 (degree of success 42), Klein rolls 18 (degree of success 32), Kirito wins.

### 1.2.3 Special Rolls

**Critical Success**: Rolling 01-05 → guaranteed success and an additional effect.  
**Fumble**: Rolling 96-00 → guaranteed failure and possibly an accident.

---

## 1.3 Attribute System

Each character has six base attributes, with starting values based on point allocation at character creation (see Chapter 2).

### 1.3.1 Base Attributes

| Attribute | Abbr. | Description | Affects |
|-----------|-------|-------------|---------|
| **Strength** | STR | Physical attack power, carrying capacity | Melee damage, carry limit, some Sword Skill damage |
| **Agility** | AGI | Speed, reaction, evasion | Action order, evasion rate, movement speed |
| **Vitality** | VIT | Hit Points, stamina, resistance | HP cap, abnormal status resistance, fatigue recovery |
| **Dexterity** | DEX | Precision, craftsmanship | Hit rate, critical rate, forging/crafting success rate |
| **Intelligence** | INT | Learning, knowledge, analysis | Skill learning speed, some life skills |
| **Luck** | LUK | Fortune, chance factors | Drop rate, rare events, critical check bonus |

### 1.3.2 Derived Attributes

Derived attributes are calculated from base attributes:

| Derived Attribute | Formula | Description |
|-------------------|---------|-------------|
| **HP (Hit Points)** | VIT × 8 + Level × 2 | Reaching zero means death |
| **SP (Sword Energy)** | STR × 2 + AGI | Resource consumed when using Sword Skills |
| **ATK (Attack)** | STR + Weapon ATK | Base physical damage value (includes weapon) |
| **MATK (Magic Attack)** | INT + Special Weapon MATK | Used for ALO/UW expansions |
| **DEF (Defense)** | VIT + Armor DEF | Reduces physical damage |
| **HIT (Hit)** | DEX × 2 + AGI | Attack hit check |
| **EVA (Evasion)** | AGI × 2 - Armor Evasion Penalty | Evasion check |
| **SPD (Speed)** | AGI + Equipment Speed Bonus | Determines action order |
| **CRT (Critical Rate)** | DEX ÷ 3 + LUK ÷ 5 | Probability of a critical occurring (%) |
| **Carry Limit** | STR × 3 (kg) | Exceeding it lowers AGI -5, SPD -10 |

---

## 1.4 Level and EXP

### 1.4.1 Level Mechanics

- Starting Level: **Lv.1**
- Level Cap: **Lv.100** (corresponds to 100-floor clearing progress)
- On level-up gain: **Attribute Points × 3** + **Skill Points × 2**

### 1.4.2 Gaining EXP

| Source | EXP |
|--------|-----|
| Normal monster | Monster Level × 15 |
| Elite monster | Monster Level × 40 |
| Maze-area monster | Monster Level × 20 |
| Floor Boss | Boss Level × 120 (party total; each member gets an equal party share) |
| Quest completion | 100-800 (by quest difficulty, see Chapter 5) |
| Discovering a new floor | Level × 10 (first arrival at that floor) |
| Excellent roleplay | GM reward, suggested 50-200 |

> **Practical Suggestion**: If strictly tracking EXP is too cumbersome, the GM may adopt a **milestone system** — clearing 1 floor levels everyone up 1 level, mid floors (25+) grant 2 levels, high floors (50+) grant 3 levels.

### 1.4.3 Level-Up Requirement Table

| Level | EXP Required | Cumulative EXP | Est. Sessions |
|-------|-------------|----------------|---------------|
| Lv.1→2 | 120 | 120 | 1 |
| Lv.2→3 | 260 | 380 | 1-2 |
| Lv.3→4 | 420 | 800 | 1-2 |
| Lv.4→5 | 600 | 1,400 | 1-2 |
| Lv.5→6 | 820 | 2,220 | 1-2 |
| Lv.6→7 | 1,060 | 3,280 | 1-2 |
| Lv.7→8 | 1,320 | 4,600 | 1-2 |
| Lv.8→9 | 1,600 | 6,200 | 1-2 |
| Lv.9→10 | 1,900 | 8,100 | 1-2 |
| Lv.10→15 | 2,200-3,600 per level | — | 2-3 per level |
| Lv.15→20 | 3,800-5,600 per level | — | 2-3 per level |
| Lv.20→30 | 6,000-11,000 per level | — | 2-4 per level |
| Lv.30→50 | 11,500-22,000 per level | — | 3-5 per level |
| Lv.50→75 | 23,000-42,000 per level | — | 4-6 per level |
| Lv.75→100 | 43,000-75,000 per level | — | 5-8 per level |

> Baseline formula: `EXP Required ≈ 120 × 1.25^(Level-1)` (rounded down to the nearest multiple of 10). This formula ensures that levels 1-100 can be completed in roughly 44-72 sessions total, corresponding to the campaign's estimated total length.

---

## 1.5 HP and Death Rules

### 1.5.1 HP (Hit Points)

> **This is not an ordinary game. The moment your HP hits zero, your brain will be incinerated by the NerveGear's microwaves.**

- HP drops to 0 → **the character dies permanently, cannot be revived. The character sheet is destroyed.**
- When HP falls below 25%, the character shows RP cues such as blurred vision and sluggish movement.
- On level-up, HP updates automatically with VIT changes: new HP cap = new VIT × 8 + new Level × 2; current HP is retained proportionally.
- Resting after leaving combat: recover VIT × 2 HP per 1 hour.
- Overnight at an inn (8 hours): HP/SP fully recovered.
- Wilderness camping (8 hours): HP recovers VIT × 8, SP recovers STR × 4.
- SP fully recovers 10 minutes after leaving combat.

### 1.5.2 Death Protection Mechanics (Extremely Rare)

In the SAO original work, death can be reversed by the following means:

| Item/Mechanic | Rarity | Description |
|---------------|--------|-------------|
| Holy Revival Crystal | ★★★★★ | Only a scant few exist in the world. A player who dies within 10 seconds of use can be revived. |
| Guild Protection | ★★★★ | A few large guilds possess special items that protect their near-death members. |

> **GM Note**: The Holy Revival Crystal may appear at most 1-2 times across the entire campaign, for key story moments. Overuse would destroy the core tension of SAO.

### 1.5.3 Near-Death State

When HP drops to 1-5:
- All checks receive a -30 modifier.
- Movement speed is halved.
- Cannot use Sword Skills that require 30 SP or more.
- Teammates may use the "First Aid" skill to stabilize wounds.

---

## 1.6 Damage Calculation

### 1.6.1 Attack Formula

**Hit Check**: `D100 ≤ Attacker's HIT - Defender's EVA`

**Damage Calculation (Unified Formula)**:
```
Step 1: Damage = (Attacker's ATK × Damage Multiplier - Defender's DEF)
Step 2: Final Damage = Step 1 result × Critical Modifier
                (skip Step 2 if no critical)
                (minimum 1, cannot be negative)
```

> **Note**: ATK already includes weapon values (ATK = STR + Weapon ATK); just use the ATK on the character sheet directly, no need to add the weapon again. The critical multiplier is applied after subtracting DEF — break the defense first, then crit.

### 1.6.2 Damage Multipliers

| Attack Type | Multiplier |
|-------------|------------|
| Normal Attack | ×1.0 |
| Light Sword Skill | ×1.3 ~ ×1.5 |
| Medium Sword Skill | ×1.8 ~ ×2.5 |
| Heavy Sword Skill | ×3.0 ~ ×5.0 |
| Critical | ×2.0 (stacks) |

### 1.6.3 Elemental Damage

SAO contains some elemental weapons (Fire, Ice, Lightning, etc.) that are effective against specific monsters:

| Element | vs. Weak monsters | vs. Resistant monsters |
|---------|-------------------|------------------------|
| Fire | Damage ×1.5 | Damage ×0.5 |
| Ice | Damage ×1.5 | Damage ×0.5 |
| Lightning | Damage ×1.5 | Damage ×0.5 |
| Dark | Damage ×1.5 | Damage ×0.5 |
| Holy | ×2.0 vs. Undead | — |

---

## 1.7 Abnormal Status

| Status | Effect | Duration | Removal |
|--------|--------|----------|---------|
| Poisoned | Lose VIT ÷ 2 HP each turn | 1D6 turns | Antidote Potion / auto-cleared at end of combat |
| Paralyzed | Cannot move or attack, EVA = 0 | 1D4 turns | Paralysis Antidote / teammate spends a major action to assist |
| Stunned | Cannot act, DEF halved | 1D3 turns | Teammate spends a major action to wake |
| Asleep | Cannot act, wakes when attacked | 1D6 turns or until attacked | Attacked / teammate spends a major action to wake |
| Cursed | All checks -20 | Until removed | Curse Antidote / Holy purification |
| Weapon Broken | Weapon ATK halved | Until repaired | Forging skill repair / weapon shop repair |
| Bleeding | Lose STR ÷ 2 HP each turn | 1D4 turns | Bandage / First Aid skill |
| Burning | Lose 5 HP each turn, DEF -5 | 1D4 turns | Drop and roll (spend move action) / Water-element magic |

**Abnormal Status Stacking Rules**:
- Same-name status does not stack (refreshes duration).
- Different-name statuses can coexist (e.g. Poisoned + Burning, total HP loss per turn VIT÷2 + 5 HP).
- When Paralyzed + Stunned simultaneously, Paralyzed takes priority (cannot act + EVA = 0).

**Buff Stacking Rules**:
- Same-source buffs do not stack (e.g. drinking two Strength potions only one takes effect).
- Different-source buffs can stack (cuisine + potion + guild buff + magic buff can all be active).
- For same-name attribute bonuses, take the highest value (STR+5 cuisine and STR+10 potion → take +10).

---

## 1.8 Time and Turns

### 1.8.1 Exploration Mode

- Movement speed: walking approx. 5 km/h (map-grid movement).
- Perception check: once per area moved, may make a D100 ≤ AGI+INT.
- Rest: every 6 hours requires 1 hour of rest, otherwise a fatigue penalty is incurred (all checks -10).

### 1.8.2 Combat Mode

- **1 turn = approx. 6 seconds**
- Each turn, all characters act in order from highest SPD to lowest.
- Each turn allows: 1 major action + 1 move action + 1 instant action.
- After using a Sword Skill there is a "Recovery Lag" (number of turns unable to act).

### 1.8.3 Floor Clearing Pace

| Phase | Time | Content |
|-------|------|---------|
| Town Exploration | 1-2 days (game time) | Gather intel, resupply, take quests |
| Field Exploration | 2-5 days | Map drawing, leveling, treasure hunting |
| Maze Clearing | 3-7 days | Explore the Maze, find the Boss room |
| Boss Clearing | 1 day | Strategy meeting + Boss battle |
| Rest & Resupply | 1-3 days | Return to frontline town to resupply |

---

## 1.9 Anti-Crystal Zones & Boss Room Lockdown

> *"The crystals... no response!?" This is the most despairing moment in SAO.*

### 1.9.1 Anti-Crystal Zones

In the following areas, **all crystal items (Teleport Crystal, Corridor Crystal, Record Crystal) become completely non-functional**:

| Area Type | Coverage | Notes |
|-----------|----------|-------|
| **Boss Room** | Entire Floor Boss room | Activates after the Boss door closes |
| **Trap Area** | Specific Maze blocks | Determined by Maze design |
| **Special Quest Area** | Specified per quest | GM may set freely |
| **Deep High-Floor Maze** | Deep areas of Maze floors 50+ | Gradually increases |

> **Player Countermeasure**: The only choice is — **defeat the Boss or die inside**. This is why every Boss battle is so tense for the Clearers.

### 1.9.2 Boss Room Door Lock System

```
Entering the Boss room procedure:
1. Party gathers before the Boss door for a final confirmation
2. Open the Boss room gate (entry allowed)
3. After everyone enters → the gate auto-closes
4. A "LOCKED" marker appears on the door → Anti-Crystal activation begins
5. The door re-opens only after the Boss dies
6. Those outside cannot enter, those inside cannot escape
```

**TRPG Resolution**:
- Before entering the Boss room: the GM should clearly tell players "once you enter, there is no way back."
- During the Boss battle: escape is only possible by running on foot to the door (but the door is locked) = impossible.
- **Only exception**: if a guild possesses a "Corridor Crystal" and has pre-set an exit outside the Boss room (requires very high tactical preparation).

### 1.9.3 Retreat Rules (Non-Boss Battles)

In normal combat, players may choose to retreat:
- **Full Retreat**: the entire party declares retreat using a major action.
- **Retreat Check**: whole party D100 ≤ AGI×2 (difficulty depends on monster SPD).
- **Covering Sacrifice**: one character stays behind to cover while the others auto-succeed at retreat (that character must survive alone for 1D3 turns before attempting to retreat).
- **Teleport Crystal Retreat**: see Chapter 3, 3.7.1.

---

## 1.10 Weapon Durability and Breakage

### 1.10.1 Durability System

| Equipment Rarity | Durability | Repair Cost |
|------------------|-----------|-------------|
| Common ★ | 100 | Missing durability ×2 Col |
| Fine ★★ | 150 | Missing durability ×5 Col |
| Rare ★★★ | 250 | Missing durability ×10 Col |
| Legendary ★★★★ | 400 | Missing durability ×20 Col |
| Mythic ★★★★★ | 600 | Missing durability ×50 Col |

After each battle, weapon durability -1; when taking a critical hit, weapon durability additionally -2.

### 1.10.2 Weapon Breakage and Repair

- Durability reaches zero → weapon is damaged, ATK = 10% of original.
- On Fumble (96-00): weapon durability -10 (in very rare cases directly causes in-combat weapon breakage).
- **Repairing a damaged weapon**: requires Forging skill Lv.7 or a paid weapon shop (30% of original weapon price); after repair ATK fully recovers.
- When durability is lowered but not zero: may use a whetstone (restores 20 durability, 100 Col / use) or the Forging skill to repair.
- Armor durability rules are the same as for weapons.

---

## 1.11 Safe Zones and Sleep PK

### 1.11.1 Within the Circle (Safe Zone)

Inside towns (Within the Circle), no form of HP damage can be dealt:
- Attacks are nullified.
- Duels cannot be initiated Within the Circle.
- But — **players can be moved or carried Within the Circle**.

### 1.11.2 Sleep PK

This is an evil exploit in SAO:
1. The victim is sleeping at an inn.
2. The attacker carries the victim from Within the Circle **to Outside the Circle**.
3. Attacks Outside the Circle.

**TRPG Handling**:
- When resting at an inn, set up a watch (GM may prompt).
- Attacked while asleep: initiative automatically goes to the attacker.
- It is recommended that the GM use Sleep PK as a story tool rather than a random encounter.

### 1.11.3 Inn Safety Levels

| Inn Level | Price | Safety |
|-----------|-------|--------|
| Budget Inn | 20 Col/night | Extremely low risk of being carried out |
| Standard Inn | 50 Col/night | Safe (NPC manager patrols) |
| Premium Inn | 150 Col/night | Absolutely safe (private room + electronic lock) |

---

## End-of-Volume Appendix: Quick Check Flow

```
1. Player declares action intent
2. GM decides whether a check is needed
3. Determine the relevant attribute and difficulty modifier
4. Calculate check value = attribute value + difficulty modifier
5. Roll D100
   ├─ ≤ check value → success (01-05 is a critical success)
   └─ > check value → failure (96-00 is a fumble)
6. GM describes the result
```

---

## Chapter 2: Character Creation

> *"I'm Kirito. My class... is more or less a one-handed swordsman."*

---

## 2.1 Creation Process Overview

Creating an SAO adventurer requires the following steps:

```
1. Decide the character concept (background, motivation, role)
2. Allocate attribute points
3. Choose initial weapon type
4. Choose initial skills
5. Decide starting equipment
6. Fill in the character background
7. Calculate derived attributes
```

---

## 2.2 Attribute Point Allocation

### 2.2.1 Standard Allocation Method (Recommended for Beginners)

At character creation, gain **60 attribute points** to distribute among the six base attributes.

**Limits**:
- Minimum per attribute: 10 (represents the baseline of an ordinary player).
- Maximum per attribute: 25 (the cap at character creation).
- Setting a single attribute to 25 costs 5 points (rather than 3) — 14→15 is normal, but beyond that it counts as "talent".

### 2.2.2 Attribute Level Meaning

| Attribute Value | Description | Reference |
|-----------------|-------------|-----------|
| 1-10 | Novice player | Just started VR games |
| 11-20 | Ordinary player | Some game experience |
| 21-35 | Veteran player | Frontline Clearer level |
| 36-50 | Top player | Core guild member |
| 51-70 | Legendary | Kirito/Asuna level |
| 71+ | Beyond the system | Kayaba Akihiko level |

### 2.2.3 Sample Attribute Builds

**Frontline Swordsman Type (Kirito style)**
- STR: 22 | AGI: 22 | VIT: 17 | DEX: 18 | INT: 12 | LUK: 9
- Total: 100 points (but practical 60-point allocation) → actual creation version:
- STR: 14 | AGI: 16 | VIT: 11 | DEX: 10 | INT: 5 | LUK: 4 → 60 points

**Light Rapier Type (Asuna style)**
- STR: 11 | AGI: 18 | VIT: 10 | DEX: 14 | INT: 8 | LUK: 4 → 65 points
- Within max attribute cap: STR: 11 | AGI: 18 | VIT: 10 | DEX: 12 | INT: 6 | LUK: 4 → 61 points

**Heavy Tank Type (Agil style)**
- STR: 15 | AGI: 8 | VIT: 18 | DEX: 8 | INT: 6 | LUK: 5 → 60 points

---

## 2.3 Leveling and Attribute Growth

### 2.3.1 Resources Gained on Level-Up

Each time you level up, gain:
- **Attribute Points × 3**: distributable to any base attribute.
- **Skill Points × 2**: distributable to any skill.

### 2.3.2 Attribute Caps

| Level Range | Single Attribute Cap |
|-------------|----------------------|
| Lv.1-20 | 35 |
| Lv.21-50 | 55 |
| Lv.51-75 | 70 |
| Lv.76-100 | 100 |

At character creation (Lv.1) the attribute cap is 25. Each level gained unlocks each attribute's cap individually.

### 2.3.3 Derived Attribute Updates on Level-Up

| Derived Attribute | Update Rule |
|-------------------|-------------|
| HP | New cap = new VIT × 8 + new Level × 2; current HP retained proportionally |
| SP | New cap = new STR × 2 + new AGI; current SP retained proportionally |
| ATK/DEF/HIT/EVA/SPD/CRT | Recalculate using new attribute values |
| Carry | new STR × 3 |
| Skill Slot | See 2.7 Skill Slot System |

> **Procedure**: First allocate attribute points → calculate new base attributes → update all derived attributes.

### 2.3.4 Allocation Example (Lv.1→Lv.10 Growth)

```
Lv.1 creation (60 points): STR 12, AGI 14, VIT 10, DEX 12, INT 6, LUK 6
Lv.1→10 gain: Attribute Points 27 (=3×9 levels) + Skill Points 18 (=2×9 levels)

Level-up allocation:
  STR +5 → 17   AGI +5 → 19   VIT +4 → 14
  DEX +6 → 18   INT +3 → 9    LUK +4 → 10

Lv.10 final: STR 17, AGI 19, VIT 14, DEX 18, INT 9, LUK 10
            HP = 14×8 + 10×2 = 132
            SP = 17×2 + 19 = 53
```

---

## 2.4 Weapon Type Selection

Each player chooses one **main weapon type** at character creation. The weapon type determines the learnable Sword Skill tree.

### 2.3.1 Weapon Type Overview

| Weapon Type | Role | Traits | Representative Character |
|-------------|------|--------|--------------------------|
| **One-Handed Sword** | Balanced | Balanced offense/defense, well-rounded Sword Skills | Kirito (main weapon) |
| **Rapier** | Speed | High Hit, high Critical, low damage | Asuna |
| **Two-Handed Sword** | Power | High damage, wide range, slow attack speed | — |
| **Axe** | Destruction | Highest damage, armor-break effect, extremely slow | Agil |
| **Short Sword** | Assassin | High Critical, stealth bonus, short range | Kuradeel |
| **Katana** | Technical | High Critical, special stances, hard to unlock | Klein (?) |
| **Spear** | Mid-range | First-strike advantage, area attacks | — |
| **Mace / Flail** | Control | Stun effect, armor break | — |
| **Dual Blades** | Legendary | Unique to all of SAO, dual weapons, GM permission | Kirito (hidden) |

### 2.3.2 Weapon Base Stats

| Weapon | ATK | HIT Bonus | Speed | Special Effect |
|--------|-----|-----------|-------|----------------|
| One-Handed Sword | +5 | +0 | Normal | — |
| Rapier | +3 | +5 | Fast | Critical Rate +5% |
| Two-Handed Sword | +10 | -5 | Slow | Area attack |
| Axe | +12 | -10 | Slowest | Armor Break: ignore 5 DEF |
| Short Sword | +2 | +8 | Fastest | Back-attack damage ×2 |
| Katana | +6 | +3 | Fast | Critical damage ×3 (not ×2) |
| Spear | +7 | +0 | Normal | First-strike attack +10 initiative |
| Mace | +8 | -3 | Slow | On hit, target must make VIT check or be Stunned 1 turn |

### 2.3.3 About Dual Blades

Dual Blades is the **only Unique Skill in SAO**. In the TRPG:

- Only **1 player** may unlock Dual Blades across the entire campaign.
- Unlock condition (GM decides): the fastest reaction, or a specific story trigger.
- Dual Blades allows equipping two one-handed weapons, attacking twice per turn (damage ×0.7 each).
- Has a dedicated Sword Skill tree (e.g. Starburst Stream).

---

## 2.5 Skill System

### 2.4.1 Skill Points

- Gain **10 skill points** at character creation.
- Gain **2 skill points** per level.
- Skill level cap = Character Level ÷ 5 + 5 (minimum 5).

### 2.4.2 Initial Skill Allocation

Players must invest at least **5 points** into the "Weapon Skill" category; the rest may be allocated freely.

### 2.4.3 Skill Categories

See Chapter 4, "Skills and Life Systems," for details. Only the categories are listed here:

| Category | Description |
|----------|-------------|
| Weapon Skill | Proficiency with each weapon and unlocked Sword Skills |
| Combat Skill | Generic combat abilities such as Block, Evasion, Switch |
| Life Skill | Forging, cooking, fishing, etc. |
| Social Skill | Negotiation, information gathering, guild management |

---

## 2.6 Starting Equipment

At character creation the character receives the following starting equipment:

| Equipment | Description |
|-----------|-------------|
| Beginner's Sword (for the chosen weapon type) | ATK+2, no special effect |
| Cloth Garb | DEF+1, no evasion penalty |
| Small Health Potion × 3 | Restores 50 HP |
| Teleport Crystal × 1 | Teleport back to the nearest town (unusable in combat) |
| Col | 1000 (starting funds) |
| Beginner's Guidebook | Basic system explanation |

---

## 2.7 Character Background

### 2.6.1 Background Elements

Each character must define the following background elements:

1. **Real-World Identity**: What did they do before SAO? (Student, office worker, game addict…)
2. **Reason for being trapped**: Why did they buy SAO? Were they a Beta Tester?
3. **Mindset**: How did their mindset shift after being trapped? (Panic → acceptance → clearing, enjoying it from the start…)
4. **Goal**: What drives them to stay alive in the death game? (Return to reality, protect someone, get stronger…)
5. **Relationships**: Relationships with other players/guilds.

### 2.6.2 Background's Impact on the Game

The GM may grant situational modifiers based on character background. For example:
- Beta Tester → Aincrad knowledge checks +10.
- Martial arts experience → relevant checks vs. humans +10.
- Programmer → system-understanding checks +10.
- Former athlete → stamina-related checks +10.

---

---

## 2.8 Skill Slot System

> In SAO, skills you learn aren't all usable. Each player can only **equip a limited number of skills**.

### 2.8.1 Number of Skill Slots

| Character Level | Skill Slots | Description |
|-----------------|------------|-------------|
| Lv.1 | 2 | Newbies can only equip two skills |
| Lv.10 | 3 | |
| Lv.20 | 4 | |
| Lv.30 | 5 | |
| Lv.50 | 6 | |
| Lv.70 | 7 | |
| Lv.90 | 8 | |
| Lv.100 | 10 | |

### 2.8.2 Skill Slot Occupancy

| Skill Type | Slots Used | Notes |
|------------|------------|-------|
| Weapon Skill (each) | 1 | Can equip only one weapon skill in a slot = use that weapon's Sword Skills in combat |
| Passive Skill (each) | 1 | e.g. Battle Healing, Sprint |
| Life Skill (each) | 0 | Life skills don't occupy combat skill slots, but have a separate "Life Skill Slot" = 2 |
| Generic Combat Skill (each) | 1 | Block, Evasion, First Aid, etc. |

### 2.8.3 Switching Skills

Skills equipped may be freely swapped in towns or safe zones. During exploration, they may be swapped at each rest (1 hour or more).

---

## 2.9 Passive Skill System

SAO has a large number of passive skills that don't consume actions; this is the core of character customization.

### 2.8.1 Complete Passive Skill List

| Skill Name | Effect (per level) | Max Level | Requirement |
|------------|--------------------|-----------|-------------|
| **Battle Healing** | Recover Lv.×3 HP at end of each turn | 10 | VIT 20+ |
| **Sprint** | Movement speed + AGI÷10 meters/level | 5 | AGI 15+ |
| **Light Metal Equip** | EVA penalty -2/level when wearing light armor | 5 | — |
| **Heavy Metal Equip** | Can equip heavy armor (each level unlocks higher DEF requirement) | 5 | STR 18+ |
| **Extended Weight** | Carry limit +10 kg/level | 5 | STR 15+ |
| **Meditation** | SP recovery speed during rest ×1.5/level | 5 | INT 15+ |
| **Emergency Recovery** | DEF+5/level when HP below 25% | 5 | VIT 15+ |
| **Hypersense** | Detection of hidden enemies +5/level | 5 | Level 30+ |
| **Weapon Guard** | Weapon block success rate +5%/level | 5 | DEX 15+ |
| **Potion Efficiency** | Potion recovery amount +10%/level | 5 | — |
| **Drop Rate Up** | Monster material drop rate +5%/level | 5 | LUK 15+ |

### 2.8.2 Detailed Explanation of Key Passive Skills

**Battle Healing**:
One of the most important passive skills in SAO. With a high-level Battle Healing in the late game, you can continuously recover during combat.

| Level | Recovery per turn | Description |
|-------|-------------------|-------------|
| 1-3 | 3-9 HP | Basic recovery |
| 4-6 | 12-18 HP | Noticeable staying power |
| 7-9 | 21-27 HP | Greatly improved staying power |
| 10 | 30 HP/turn | Equivalent to a permanent minor heal |

**Sprint**: Directly affects movement distance and chase/escape capability.  
**Meditation**: Recovers SP between battles; crucial for characters that frequently use Sword Skills.

---

## 2.10 Beta Tester

> *"That guy is a beater!"* — the discriminatory term for Beta Testers in SAO.

### 2.9.1 Beta Tester Advantages

| Advantage | Game Effect |
|-----------|-------------|
| Map Knowledge | Geography checks for floors 1-10 +15 |
| Monster Knowledge | Monster weaknesses for floors 1-10 auto-known (no check needed) |
| Quest Pre-empt | Some quests completed 50% faster |
| Combat Experience | Initiative checks for floors 1-5 +5 |

### 2.9.2 Beta Tester Disadvantages

| Disadvantage | Game Effect |
|--------------|-------------|
| Social Discrimination | NPC attitude checks toward Beta Testers -10 |
| Information Blackout | Non-Beta players unwilling to share intel |
| "Beater" Label | Some guilds refuse Beta Testers |
| System Change Trap | The GM may design traps that "didn't exist in the beta," against which Beta Testers get no bonus |

### 2.9.3 Usage Suggestions

- A party may have 1 Beta Tester (recommended).
- Very strong early on; advantage weakens mid-game.
- The social disadvantage is important RP material.

---

## 2.11 Marriage System

> *"Asuna... let's get married."*

### 2.10.1 Marriage Conditions and Process

```
1. Both parties must have reached Floor 22 or above (system unlocks marriage feature)
2. Purchase a wedding ring (5,000 Col, available at specific NPC shops)
3. Hold the ceremony at a church in any town (other players may be invited to witness)
4. After system confirmation, the spouse's name appears in each other's status bar
5. Shared features unlocked
```

### 2.10.2 Marriage System Effects

| Feature | Description |
|---------|-------------|
| **Shared Storage** | Spouse can access the other's storage |
| **Location Check** | Can see the spouse's position on the map |
| **HP Monitor** | Can see the spouse's real-time HP status |
| **Instant Message** | Can send instant messages to the spouse (no distance limit) |

### 2.10.3 In the TRPG

- Marriage is an important RP milestone; it is recommended that the GM use it as a story reward.
- Shared storage practically makes party item management more convenient.
- If a spouse dies, seeing their HP hit zero in the monitor — this is the most heartbreaking scene in SAO.

---

## 2.12 Character Inheritance Mechanic

In a long campaign, a player's character may die. To let the player keep participating:

### 2.11.1 Introducing a New Character

When a character dies, the player creates a new one:
- New character level = dead character's level - 10 (minimum 1).
- Retain 50% of the dead character's Col (as "inheritance").
- The new character's background may be set as "a non-clearer who was finally motivated to step out of town."

### 2.11.2 Inheritance

A dead character's important equipment may name an heir (must be noted on the character sheet in advance):
- Named heir → obtains unconditionally.
- No named heir → distributed by party/guild decision.
- Special equipment (e.g. Midnight Coat) → GM decides whether it can be inherited.

---

## 2.13 Character Sheet Template

```
══════════════════════════════════
  SAO TRPG Character Sheet
══════════════════════════════════

Character Name: [_______________]  Lv.[___]
Gender: [___]  Age: [___]
Title: [_______________]

Real-World Identity: [_______________]

══════════════════════════════════
  Base Attributes
──────────────────────────────────
STR [___]  AGI [___]  VIT [___]
DEX [___]  INT [___]  LUK [___]

══════════════════════════════════
  Derived Attributes
──────────────────────────────────
HP  [____/____]  SP  [____/____]
ATK [____]  MATK [____]  DEF [____]
HIT [____]  EVA  [____]  SPD [____]
CRT [____%]  Carry [____/____]

══════════════════════════════════
  Equipment
──────────────────────────────────
Main Weapon: [_______________] ATK+[__]
Sub Weapon:  [_______________] ATK+[__]
Head:        [_______________] DEF+[__]
Body:        [_______________] DEF+[__]
Accessory 1: [_______________]
Accessory 2: [_______________]

══════════════════════════════════
  Skills
──────────────────────────────────
Weapon Skill  Lv.[__] [____________]
Combat Skill  Lv.[__] [____________]
Life Skill    Lv.[__] [____________]

══════════════════════════════════
  Inventory
──────────────────────────────────
Col: [__________] Col

[_____________________________]
[_____________________________]
[_____________________________]

══════════════════════════════════
  Notes
──────────────────────────────────



══════════════════════════════════
```

---

## End-of-Volume Appendix: 5-Minute Quick Character Creation Flow

```
1. Think of a character concept (1 minute)
2. Allocate 60 points across the six attributes (2 minutes)
3. Choose weapon type (30 seconds)
4. Brief background (1 minute)
5. Calculate derived attributes (30 seconds)
→ Done!
```

---
## Chapter 3: Combat System

> *"Switch!" — the standard tactical command of the SAO frontline Clearers*

---

## 3.1 Combat Flow Overview

### 3.1.1 Turn Order

1. **Initiative Check**: All participants are arranged in action order from highest to lowest SPD.
2. **Action Phase**: Each character acts in sequence.
3. **End Phase**: Resolve ongoing effects and status-abnormality reductions.

### 3.1.2 Actions Allowed Per Turn

| Action Type | Quantity | Description |
|-------------|----------|-------------|
| Major Action | 1 | Attack, use a Sword Skill, use an item, first aid, etc. |
| Move Action | 1 | Move (up to AGI ÷ 2 meters), reposition, stand up |
| Instant Action | 1 | Switch with an ally, declare a guard, certain skills |

### 3.1.3 Preemptive Attack (Ambush)

If one side launches an attack while the other is unaware:
- The ambushing side gains **one free round of actions** (Surprise Round)
- During that round, all attacks by the ambushing side gain HIT +20
- The ambushed side cannot act during the surprise round

---

## 3.2 Attack Types

### 3.2.1 Normal Attack

The most basic attack action. No SP cost, no Recovery Lag.

- Roll D100 ≤ HIT - target EVA → Hit
- On hit: Damage = ATK × 1.0 - target DEF

### 3.2.2 Sword Skill Attacks (Sword Skills)

> **Sword Skills are the core of the SAO combat system. When activated, the system takes over the character's body and executes a preset attack motion.**

#### Sword Skill Usage Rules

1. **Declare the Sword Skill name** and spend the corresponding SP
2. **Roll the hit check**: D100 ≤ HIT - target EVA + Sword Skill hit bonus
3. **Calculate damage**: Base damage × Sword Skill damage multiplier - target DEF
4. **Enter Recovery Lag**: After activating a Sword Skill, the character cannot act for a specified duration

#### Recovery Lag System (Post-Motion Delay)

The stronger the Sword Skill, the longer the Recovery Lag:

| Sword Skill Tier | SP Cost | Recovery Lag Turns | Description |
|------------------|---------|--------------------|-------------|
| Novice Sword Skill | 5-10 SP | 0 turns | No Recovery Lag; can be used consecutively or followed by other actions |
| Intermediate Sword Skill | 11-20 SP | 1 turn | Cannot act on the next turn after use |
| Advanced Sword Skill | 21-35 SP | 2 turns | Cannot act on the next two turns after use |
| Secret/Ultimate Tier | 36+ SP | 3 turns | Cannot act on the next three turns after use; SP drops to zero for 1 turn after use |

> **Tactical Note**: Advanced-tier and above Sword Skills are usually finishing moves. If you are hit by a monster during Recovery Lag, the consequences are extremely severe. This is why "Switching" is needed in SAO — allies cover you during your Recovery Lag.

### 3.2.3 Switch (Switch)

> *SAO's most iconic team tactic. When one player uses a Sword Skill and enters Recovery Lag, another player switches in to take over the attack, forming a cycle.*

#### Switch Rules

1. **Switch Declaration**: At any time after an ally uses a Sword Skill (or at any moment), declare a Switch as an Instant Action
2. **Position Swap**: The switcher and the target ally exchange positions
3. **Hate Transfer**: The monster's attack target shifts to the player who switched in
4. **Combo Bonus**: When consecutive Switches succeed, the first attack after each Switch gains a cumulative bonus:

| Consecutive Switch Count | HIT Bonus | Damage Bonus | Description |
|--------------------------|-----------|--------------|-------------|
| 1st | +5 | ×1.0 | Basic Switch |
| 2nd | +10 | ×1.1 | Rhythm established |
| 3rd | +15 | ×1.2 | Smooth coordination |
| 4th | +20 | ×1.3 | Perfect coordination |
| 5th+ | +25 | ×1.5 | Legendary teamwork |

> **Note**: If any attack after a Switch misses, the combo breaks and the bonus resets.

#### Switch Tactical Example

```
Turn 1: Kirito uses intermediate Sword Skill "Vertical Arc Slash" (SP-15) → deals 45 damage → Recovery Lag 1 turn
       → Asuna declares Switch, enters the fray!
Turn 2: Asuna uses novice Sword Skill "Linear Attack" (SP-5) → HIT+5 (combo) → deals 32 damage → no Recovery Lag
       → Klein declares Switch, enters the fray!
Turn 3: Klein uses intermediate Sword Skill "Whirlwind Slash" (SP-12) → HIT+10 (combo) → deals 38 damage → Recovery Lag 1 turn
       → Kirito (recovered) declares Switch, enters the fray!
```

---

## 3.3 Defensive Actions

### 3.3.1 Block

Declared as an Instant Action. When blocking:
- Forfeit the major action for that turn
- Gain DEF × 2 defensive bonus against one designated attack
- Block check: D100 ≤ STR + weapon skill level (shields get an extra bonus)
- On successful block: damage taken is reduced by DEF × 2, and no abnormal status is triggered

### 3.3.2 Emergency Dodge

Declared as an Instant Action. When emergency dodging:
- Forfeit the major action for that turn
- EVA gains +30 bonus against one attack
- Dodge check: D100 ≤ AGI + dodge skill level
- Move 1-3 meters

### 3.3.3 Parry

A high-difficulty defensive action using the sword to block a sword:
- Must be declared and costs 5 SP
- Roll D100 ≤ DEX + weapon skill level
- Success: completely negate one melee attack
- Failure: take 1.5× damage
- **Critical Success (01-05)**: after the parry, may immediately counterattack (free normal attack)

---

## 3.4 Boss Battle Special Rules

The Floor Boss battles of SAO are the climax of the entire game. Below are rules exclusive to Boss battles.

### 3.4.1 Boss Attributes

Bosses possess the following special attributes:

| Attribute | Description |
|-----------|-------------|
| Boss HP | Approximately 20-50× that of normal monsters on the same Floor |
| Multi-Phase | Boss switches behavior patterns when its HP drops to specific ratios |
| Area Attack | Most Bosses possess AOE skills |
| Immunity | Bosses are immune to strong control effects such as Stun and Sleep |

### 3.4.2 Boss Phase Transition

A Boss enters a new phase at the following HP ratios:

| Phase | HP | Behavior Change |
|-------|----|------------------|
| Phase 1 | 100%-61% | Basic attack pattern |
| Phase 2 | 60%-31% | Unlocks new skills, attack frequency increases |
| Phase 3 | 30%-0% | Enraged state: ATK×1.5, SPD+10, uses strongest skills |

### 3.4.3 Boss Strategy Meeting

Before a Boss battle, players may hold a strategy meeting, lasting about 1-2 in-game hours. Successful intelligence gathering and strategic planning provide bonuses.

The following checks grant Boss battle bonuses:

| Action | Check | Success Reward |
|--------|-------|----------------|
| Investigate Boss intel | INT | Learn 1-3 of the Boss's skills |
| Analyze weaknesses | INT + Monster Knowledge | Whole party +5% CRT rate against the Boss |
| Formulate tactics | INT + Tactics skill | First Switch of the whole party: HIT+10 |
| Morale speech | Roleplay | Whole party: ATK+3 on the first round |

### 3.4.4 Last Attack Bonus

> *SAO's hidden mechanic: the player who lands the last hit on a Boss gains a rare drop.*

- The player who lands the last hit on a Boss gains the "LA Bonus" — one drop item with +1 extra rarity
- This mechanic encourages players to compete for the last hit within a safe range (and adds subtle competition within the team)

---

## 3.5 Hate System

SAO has no explicit hate value display, but monsters prioritize attacking the target that poses the greatest threat to them or that recently dealt damage.

### 3.5.1 Hate Value Calculation

| Action | Hate Value |
|--------|------------|
| Normal attack hit | +10 |
| Novice Sword Skill hit | +15 |
| Intermediate Sword Skill hit | +25 |
| Advanced Sword Skill hit | +40 |
| Secret/Ultimate Sword Skill hit | +60 |
| Critical hit | Extra +20 |
| Heal an ally | +5 (to all monsters present) |
| Switch in | Immediately becomes the primary target |

### 3.5.2 Monster Attack Target

Monsters attack the character with the highest current hate value. If hate values are tied, they attack the nearest one.

---

## 3.6 Team Combat Rules

### 3.6.1 Party Size

| Size | Members | Typical Use |
|------|---------|-------------|
| Small party | 2-3 | Field leveling, simple quests |
| Mid party | 4-6 | Maze exploration, elite monster subjugation |
| Clearing force | 7-24 | Boss subjugation battle (multiple small parties combined) |
| United clearing army | 25-48 | High-level Boss subjugation |

### 3.6.2 Party Roles

Typical clearing-party composition:

| Role | Members | Suggested Weapons | Task |
|------|---------|-------------------|------|
| Tank/Frontline | 1-2 | One-handed sword + shield, two-handed sword | Draw hate, absorb damage, Switch core |
| Damage/Attacker | 2-3 | Rapier, katana, axe | Deal damage, activate high-damage Sword Skills |
| Support/Control | 1 | Spear, hammer | Control monsters, handle trash mobs |
| Scout | 0-1 | Short sword | Stealth reconnaissance, trap disarming |

### 3.6.3 Friendly Fire

> SAO has no friendly fire. This is a game system design, and it also means you can safely use area Sword Skills next to your allies.

---

## 3.7 Special Combat Situations

### 3.7.1 Transfer Crystal Combat

A transfer crystal may be used to escape during combat, but:
- Using the crystal is a major action
- After use, there is a 10-second (1-turn) activation delay
- Being attacked during the delay interrupts the teleport
- Therefore, ally cover is required

### 3.7.2 Trap Combat

Traps in mazes may trigger special battles:
- Pitfall trap: fall damage + separation from the party
- Poison mist trap: area Poison
- Alarm trap: attracts all nearby monsters
- Teleport trap: teleports the party deep into the maze (an area where escape via crystal is impossible)

### 3.7.3 Dual Boss / Multi-Target Boss

Some Bosses consist of multiple individuals. In such cases:
- Hate values are calculated separately
- Tanks must be assigned to handle each individually
- Switch tactics become more complex

---

## 3.8 Quick Battle Example

```
Scene: Kirito (Lv.40) and Asuna (Lv.38) encounter a "Skeleton Guardian" (Lv.35 elite monster) in a maze area

[Initiative Check]
Kirito SPD 75 > Asuna SPD 82 > Skeleton Guardian SPD 40

[Turn 1]
▶ Asuna: Moves closer → uses novice Sword Skill "Linear Attack"
  Hit check: D100(34) ≤ HIT(72) - EVA(30) = 42 → Hit!
  Damage: (ATK 48 + Rapier +7) × 1.4 - DEF 25 = 52 damage
  Boss HP: 320 → 268

▶ Kirito: Uses intermediate Sword Skill "Vertical Arc Slash"
  Hit check: D100(22) ≤ HIT(68) - EVA(30) = 38 → Hit!
  Damage: ATK(67) × 2.2 - DEF 25 = 122 damage
  Boss HP: 268 → 146
  Kirito enters Recovery Lag (1 turn)

▶ Skeleton Guardian: Attacks Kirito (highest hate) (hate: Kirito 25 > Asuna 15)
  Hit check: D100(71) ≤ HIT(55) - Kirito EVA(50) = 5 → Fail (Miss)
  Swinging greatsword strikes empty air!

[Turn 2]
▶ Asuna: Declares "Switch!" → swaps position with Kirito
  Hate transfer: Boss target becomes Asuna
  Combo bonus: 1st Switch, HIT+5

▶ Asuna: Uses intermediate Sword Skill "Flickering Thrust"
  Hit check: D100(18) ≤ HIT(72+5 combo) - EVA(30) = 47 → Hit!
  Damage: ATK(55) × 2.0 - DEF 25 = 85 damage
  Boss HP: 146 → 61
  Asuna enters Recovery Lag (1 turn)

▶ Kirito (recovered from Recovery Lag): Declares "Switch!"
  Combo bonus: 2nd Switch, HIT+10

▶ Kirito: Uses advanced Sword Skill "Sonic Impact"
  Hit check: D100(15) ≤ HIT(68+10) - EVA(30) = 48 → Hit!
  Critical check: CRT 18% → D100(03) → Critical!
  Damage: (ATK 67 × 3.0 - DEF 25) × 2.0 (critical) = 352 damage
  Boss HP: 61 → 0

[Victory!]
EXP: Lv.35 elite × 40 = 1400 EXP (split between two, 700 each)
Drop: Skeleton Bracer (DEF+12, rare armor)
LA Bonus: Kirito obtains "Guardian's Soul Crystal" (rare material)
```

---

## 3.8 Duel System

> *"I challenge you to a duel. Mode — Total Loss Duel."*

Duels are an important mechanism in SAO for resolving disputes between players, and also a key plot driver (Kirito's duel against Heathcliff directly led to the fateful turning point of the KoB).

### 3.8.1 Duel Modes

| Mode | Victory Condition | Defeat Consequence | Use |
|------|-------------------|--------------------|-----|
| **First Strike** | Land a hit on the opponent first | No real loss | Training, entertainment, sparring |
| **Half HP** | Reduce opponent's HP below 50% | HP drops to 50% | Resolve disputes, guild selection |
| **Total HP** | Reduce opponent's HP to 0 | **Character death** | Life-or-death struggle (rarely used) |

### 3.8.2 Duel Flow

```
1. Initiator points at target, opens menu → select "Duel Request"
2. Select duel mode (Total Loss mode requires both sides to confirm a warning window)
3. Countdown 10→0
4. Duel begins (both sides' HP displayed at top of view)
5. Upon reaching victory condition → system announces the winner
```

### 3.8.3 Duel Rules (TRPG)

- **First Strike**: The first to succeed on a hit check wins, up to 3 turns.
- **Half HP**: Normal combat, until one side's HP drops below 50%.
- **Total HP**: Identical to normal combat; HP reaching zero means the character suffers Permanent Death.

**GM Note**:
- Spectators cannot interfere with the duel (system protection)
- Recovery items cannot be used during the duel (system prohibition)
- Total Loss Duels should be key plot moments; do not let an NPC initiate one lightly

---

## 3.9 Martial Arts

> Skills in SAO for fighting without equipping a weapon. Few players use them, but they do exist.

### 3.9.1 Martial Arts Sword Skills

| Level | Sword Skill Name | SP | Recovery Lag | Multiplier | Effect |
|-------|------------------|-----|--------------|------------|--------|
| 1 | Straight Punch | 3 | 0 | ×1.0 | Basic punch |
| 2 | Combo Punch | 5 | 0 | ×1.2 | Two-hit combo |
| 3 | Uppercut | 8 | 1 | ×1.5 | Inflicts Stun |
| 4 | Roundhouse Kick | 10 | 1 | ×1.6 | Can knock back |
| 5 | Palm Strike | 12 | 1 | ×1.8 | Ignores 5 DEF |
| 6 | Flash Blow | 18 | 2 | ×2.5 | +20% CRT rate |
| 7 | Meteor Fist | 25 | 2 | ×3.0 | Five-hit combo |
| 8 | Mountain Breaker | 35 | 3 | ×4.0 | Ultimate single-target |

**Martial Arts Passives**:
- Lv.5: "Iron Wall" — When unarmed, DEF = VIT×2
- Lv.8: "Master" — Martial Arts attacks ignore 10 DEF

> **Source Connection**: In the Layer 1 strategy meeting, Kirito used a Martial Arts skill to kick a provocative player; he also employed Martial Arts during his duel with Heathcliff.

---

## 3.10 Combat Detail Supplements

### 3.10.1 Order When SPD Is Tied

When multiple characters have the same SPD, sort by the following priority:
1. Higher AGI goes first
2. If AGI is tied → higher DEX goes first
3. If still tied → player characters take priority over monsters; among players, decide by coin flip

### 3.10.2 Combat Distance and Range

| Distance | Range | Melee Weapon | Ranged Weapon | Movement Required |
|----------|-------|--------------|---------------|-------------------|
| Close | 0-3m | Normal hit | HIT-10 | No movement needed |
| Near | 3-8m | HIT-5 | Normal | 1 move action |
| Mid | 8-20m | Cannot attack | Normal | 1-2 move actions |
| Far | 20-50m | Cannot attack | HIT-5 | 2-3 move actions |
| Extreme | 50m+ | — | HIT-10 | — |

The starting distance between both sides is decided by the GM based on the scene (field: Mid / maze: Near / ambush encounter: Close).

### 3.10.3 Weather and Environment Effects

| Environment | Effect |
|-------------|--------|
| Darkness (no light source) | All HIT-20, detection check -15 |
| Dense fog | Ranged attacks HIT-15, sight range limited to 10m |
| Heavy rain | Movement speed halved, Fire damage ×0.5 |
| Extreme heat | Every 5 turns, VIT check or suffer fatigue (all checks -5) |
| Cold | SP cost +5, AGI-5 |
| Strong wind | Thrown/flying HIT-10 |
| Underwater | Non-aquatic weapons have ATK halved, movement halved |

### 3.10.4 Multi-Monster Hate Handling

When multiple monsters attack the same player simultaneously:
- Monsters still each choose their target by hate value
- If two monsters have equal hate and target the same player → decided by the GM (usually attacks the nearest)
- For each additional monster attacking simultaneously, the player's EVA -5 (surround penalty, max -20)

### 3.10.5 Failed Escape Consequences

When the retreat check (D100 ≤ AGI×2) fails:
- That character cannot move that turn
- The monster gains one free attack opportunity against that character (HIT+5)
- May attempt retreat again next turn
- **Sacrificial Cover**: One character stays behind to cover the retreat; other allies automatically retreat successfully, but the covering character must survive alone for 1D3 turns before attempting to retreat

---

## End-of-Chapter Appendix: Combat Quick Reference Card

```
═══════════════════════════════
  Combat Turn Flow
═══════════════════════════════

1. Initiative Check: SPD order
2. Act in sequence, each person:
   □ Major Action ×1
   □ Move Action ×1
   □ Instant Action ×1
3. Resolve ongoing effects

═══════════════════════════════
  Hit Formula
═══════════════════════════════
D100 ≤ Your HIT - Enemy EVA

═══════════════════════════════
  Damage Formula
═══════════════════════════════
(ATK × Damage Multiplier - Enemy DEF)
 × Skill Modifier × Critical Modifier

═══════════════════════════════
  Sword Skill Recovery Lag Table
═══════════════════════════════
Novice (5-10 SP) → No Recovery Lag
Intermediate (11-20 SP) → Recovery Lag 1 turn
Advanced (21-35 SP) → Recovery Lag 2 turns
Secret/Ultimate (36+ SP) → Recovery Lag 3 turns

═══════════════════════════════
  Switch Combo Bonus
═══════════════════════════════
1st: +5 HIT
2nd: +10 HIT, ×1.1 damage
3rd: +15 HIT, ×1.2 damage
4th: +20 HIT, ×1.3 damage
5th+: +25 HIT, ×1.5 damage
```
## Chapter 4: Skills & Life Systems

> *"There is no magic in SAO. In its place are system-external skills known as 'Sword Skills,' along with countless life skills."*

---

## 4.1 Skill System Overview

Skills in SAO are divided into **three major categories**:

| Category | Description | Skill Point Cost |
|----------|-------------|------------------|
| Weapon Skills | Increases proficiency with a specific weapon, unlocks Sword Skills | Primary investment |
| General Combat Skills | Weapon-agnostic combat capabilities | Secondary investment |
| Life Skills | Non-combat production, gathering, and social abilities | Free investment |

---

## 4.2 Weapon Skill Trees

Each weapon has its own independent skill tree. Skill level determines the Sword Skill tier and damage bonus available.

### 4.2.1 Proficiency & Bonuses

| Skill Level | Skill Points Required | ATK Bonus | Unlocks |
|-------------|----------------------|-----------|---------|
| 1 | 1 | +0 | Can use beginner Sword Skills |
| 2 | 2 | +1 | — |
| 3 | 3 | +1 | Can use intermediate Sword Skills |
| 4 | 4 | +2 | — |
| 5 | 5 | +2 | Unlocks specialization passive |
| 6 | 6 | +3 | Can use advanced Sword Skills |
| 7 | 7 | +3 | — |
| 8 | 8 | +4 | — |
| 9 | 9 | +4 | Can use secret-art Sword Skills |
| 10 | 10 | +5 | Unlocks ultimate passive |

**Maximum Skill Level** = Character Level ÷ 5 + 5 (minimum 5)

### 4.2.2 One-Handed Sword Skill Tree

> Representative character: Kirito

| Level | Sword Skill Unlocked | SP | Recovery Lag | Damage Multiplier | Special Effect |
|-------|----------------------|----|-----------|------------------|----------------|
| 1 | **Slant** | 5 | 0 | ×1.3 | Basic slash |
| 2 | **Horizontal** | 8 | 0 | ×1.4 | Can hit 2 adjacent targets |
| 3 | **Vertical** | 12 | 1 | ×1.8 | Single target, -5 to defense break |
| 4 | **Sonic Leap** | 15 | 1 | ×2.0 | Dash forward then slash, HIT+5 |
| 5 | **Vertical Arc** | 18 | 1 | ×2.2 | Two-stage slash, each hit judged independently |
| 6 | **Vorpal Strike** | 25 | 2 | ×3.0 | Heavy single-target strike, Critical rate +10% |
| 7 | **Horizontal Square** | 28 | 2 | ×2.5 | Area attack (4 directions), can hit all surrounding targets |
| 8 | **Nova Ascension** | 32 | 2 | ×3.5 | 10-hit combo, HIT+15 |
| 9 | **Deadly Sins** | 40 | 3 | ×4.5 | 7-hit combo, each hit can target a different enemy |
| 10 | **The Eclipse** | 50 | 3 | ×5.0 | Ultimate secret-art with 27-hit combo |

**One-Handed Sword Passive Skills**:
- Lv.5: "Swordsman's Intuition" — Restores 5 SP on a successful block
- Lv.10: "Endless Sword Dance" — Normal attacks have a 20% chance to not consume an action

### 4.2.3 Rapier Skill Tree

> Representative character: Asuna

| Level | Sword Skill Unlocked | SP | Recovery Lag | Damage Multiplier | Special Effect |
|-------|----------------------|----|-----------|------------------|----------------|
| 1 | **Linear** | 5 | 0 | ×1.3 | High-speed thrust |
| 2 | **Parallel Sting** | 8 | 0 | ×1.4 | Two-hit thrust |
| 3 | **Triangular** | 12 | 1 | ×1.8 | Three-hit thrust, each hit judged independently |
| 4 | **Shooting Star** | 14 | 1 | ×2.0 | Thrusting lunge, HIT+10 |
| 5 | **Flashing Penetrator** | 18 | 1 | ×2.3 | High-speed five-hit thrust |
| 6 | **Crucifixion** | 22 | 2 | ×2.8 | Cross-trajectory six-hit thrust |
| 7 | **Star Splash** | 28 | 2 | ×3.2 | 8-hit thrust, HIT+15 |
| 8 | **Radiance Torrent** | 33 | 2 | ×3.8 | 12-hit thrust, Critical rate +15% |
| 9 | **Mother's Rosario** | 42 | 3 | ×5.0 | Legendary secret-art with 11-hit thrust |

**Rapier Passive Skills**:
- Lv.5: "Gale" — When hitting the same target consecutively, each subsequent attack gains HIT+3 (max +15)
- Lv.9: "Flash" — SPD permanently +10 (the reason Asuna earned the "Flash" title)

### 4.2.4 Two-Handed Sword Skill Tree

| Level | Sword Skill Unlocked | SP | Recovery Lag | Damage Multiplier | Special Effect |
|-------|----------------------|----|-----------|------------------|----------------|
| 1 | **Heavy Slash** | 6 | 0 | ×1.4 | Charged slash |
| 2 | **Wide Sweep** | 10 | 1 | ×1.5 | Front cone 120° area attack |
| 3 | **Ground Breaker** | 14 | 1 | ×1.8 | Area attack, adds knockdown (AGI check) |
| 4 | **Cyclone** | 18 | 1 | ×2.0 | Spinning attack, 360° around |
| 5 | **Sky Rending** | 22 | 2 | ×2.5 | Vertical chop, ignores 10 DEF |
| 6 | **Avalanche** | 30 | 2 | ×3.0 | Front-line three-hit area attack |
| 7 | **Titan's Hammer** | 35 | 2 | ×3.5 | Jumping heavy strike, area damage |
| 8 | **Earth Divide** | 40 | 3 | ×4.0 | Massive area, stun check |
| 9 | **Calamity Disaster** | 50 | 3 | ×5.0 | Ultimate area secret-art |

**Two-Handed Sword Passive Skills**:
- Lv.5: "Weight Adaptation" — Two-handed sword speed penalty halved
- Lv.9: "Unbreakable" — When HP is below 25%, DEF+15

### 4.2.5 Axe Skill Tree

| Level | Sword Skill Unlocked | SP | Recovery Lag | Damage Multiplier | Special Effect |
|-------|----------------------|----|-----------|------------------|----------------|
| 1 | **Chop** | 6 | 0 | ×1.5 | Basic axe strike |
| 2 | **Armor Break** | 10 | 1 | ×1.6 | Target DEF-10 (lasts 2 turns) |
| 3 | **Whirlwind Axe** | 15 | 1 | ×1.8 | Surrounding area |
| 4 | **Power Strike** | 20 | 1 | ×2.5 | Charged single strike |
| 5 | **Tomahawk Throw** | 18 | 1 | ×1.8 | Mid-range throwing attack |
| 6 | **Earth Axe** | 25 | 2 | ×2.8 | Area shock |
| 7 | **Berserker** | 30 | 2 | ×3.5 | Three consecutive axe strikes, but own DEF-10 |
| 8 | **Destroyer** | 38 | 2 | ×4.0 | Ignores 20 DEF |
| 9 | **Ragnarok** | 48 | 3 | ×5.5 | Highest single-hit multiplier of all weapons |

**Axe Passive Skills**:
- Lv.5: "Armor Break Mastery" — Normal attacks also ignore 3 DEF
- Lv.9: "Battle High" — Each enemy killed grants ATK+5 (max +20, lasts until end of combat)

### 4.2.6 Dagger Skill Tree

| Level | Sword Skill Unlocked | SP | Recovery Lag | Damage Multiplier | Special Effect |
|-------|----------------------|----|-----------|------------------|----------------|
| 1 | **Rapid Stab** | 4 | 0 | ×1.2 | Fastest attack |
| 2 | **Backstab** | 8 | 0 | ×2.0 | Must be behind target, guaranteed critical |
| 3 | **Venom Edge** | 10 | 1 | ×1.5 | Adds Poisoned (1D4 turns) |
| 4 | **Shadow Step** | 12 | 0 | ×1.3 | Teleport behind target then attack |
| 5 | **Fatal Jab** | 15 | 1 | ×2.5 | Ignores DEF |
| 6 | **Assassin Combo** | 20 | 1 | ×2.8 | 6-hit thrust, HIT+10 |
| 7 | **Paralyze Dagger** | 22 | 1 | ×2.0 | Adds Paralyzed (1D3 turns) |
| 8 | **Death Dance** | 30 | 2 | ×4.0 | Consecutive assassination on surrounding targets ×3 |

**Dagger Passive Skills**:
- Lv.5: "Shadow Walker" — Movement speed not reduced while stealth
- Lv.8: "Grim Reaper" — ×1.5 damage against targets with HP below 25%

### 4.2.7 Katana Skill Tree

> The Katana is a weapon type unlocked relatively late in SAO, learned through specific quests or conditions.

| Level | Sword Skill Unlocked | SP | Recovery Lag | Damage Multiplier | Special Effect |
|-------|----------------------|----|-----------|------------------|----------------|
| 1 | **Iai Strike** | 6 | 0 | ×1.5 | Must start from sheathed state |
| 2 | **Iai Flash** | 8 | 0 | ×1.6 | HIT+10 |
| 3 | **Renzan** | 12 | 1 | ×1.9 | Three-hit slash |
| 4 | **Sakura Storm** | 16 | 1 | ×2.1 | Surrounding three-hit slash |
| 5 | **Tsukikage** | 20 | 1 | ×2.3 | Circle behind to slash |
| 6 | **Mumyo Slash** | 24 | 2 | ×3.0 | Charged slash, ignores 10 DEF |
| 7 | **Hien Tachi** | 28 | 2 | ×3.5 | Adds Fire damage |
| 8 | **Senbonzakura** | 35 | 2 | ×3.8 | 10-hit slash, CRT rate +20% |
| 9 | **Shura** | 45 | 3 | ×5.5 | Ultimate iai technique, HP becomes 1 after use |

**Katana Passive Skills**:
- Lv.5: "Iai Mastery" — First strike from sheathed state is guaranteed critical
- Lv.9: "Asura Path" — Lower HP grants higher damage (for every 10% HP lost, damage +5%)

### 4.2.8 Spear Skill Tree

| Level | Sword Skill Unlocked | SP | Recovery Lag | Damage Multiplier | Special Effect |
|-------|----------------------|----|-----------|------------------|----------------|
| 1 | **Thrust** | 5 | 0 | ×1.3 | Basic spear strike |
| 2 | **Sweep** | 8 | 0 | ×1.4 | Front cone |
| 3 | **Triple Thrust** | 12 | 1 | ×1.7 | Three-hit thrust |
| 4 | **Spiral Thrust** | 15 | 1 | ×2.0 | Spinning penetration, ignores 5 DEF |
| 5 | **Gale Lance** | 18 | 1 | ×2.2 | High-speed charge + area |
| 6 | **Dragon Fang** | 24 | 2 | ×3.0 | Jumping top-down thrust |
| 7 | **Army Breaker** | 30 | 2 | ×2.5 | Straight-line penetration forward (max 3 targets) |
| 8 | **Gungnir** | 38 | 2 | ×4.0 | Ultimate single-target thrust |

**Spear Passive Skills**:
- Lv.5: "First Strike Victory" — First attack each combat HIT+15
- Lv.8: "Piercing" — ×1.3 damage against targets with defensive buffs

### 4.2.9 Hammer / Mace Skill Tree

| Level | Sword Skill Unlocked | SP | Recovery Lag | Damage Multiplier | Special Effect |
|-------|----------------------|----|-----------|------------------|----------------|
| 1 | **Smash** | 6 | 0 | ×1.5 | Basic hammer strike |
| 2 | **Concussion** | 10 | 1 | ×1.6 | Stun check (vs VIT) |
| 3 | **Bone Crusher** | 15 | 1 | ×1.8 | Target DEF-10 |
| 4 | **Earthquake** | 20 | 1 | ×2.0 | Surrounding area + knockdown |
| 5 | **Meteor Hammer** | 22 | 1 | ×2.3 | Jumping heavy strike |
| 6 | **Mjolnir** | 28 | 2 | ×3.0 | Adds Paralyzed check |
| 7 | **World Crush** | 35 | 2 | ×3.5 | Massive area |
| 8 | **Divine Punishment** | 42 | 3 | ×4.5 | Stun + armor break + knockdown combo |

**Hammer Passive Skills**:
- Lv.5: "Stun Enhancement" — Stun chance +15%
- Lv.8: "Crusher" — ×3 damage to buildings and objects

---

## 4.3 General Combat Skills

These skills are not bound to a specific weapon and can be learned by any character.

| Skill | Effect (per level) | Max Level |
|-------|--------------------|-----------|
| **Block** | DEF +2/level when blocking | 10 |
| **Evasion** | EVA +2/level | 10 |
| **Tactics** | Switch combo bonus +1 HIT/level | 5 |
| **First Aid** | Use in combat to restore HP = Level×5 | 10 |
| **Detection** | HIT+3/level to find hidden targets | 10 |
| **Hate Control** | Can actively reduce hate value 5/level | 5 |
| **Weapon Swap** | Speed of swapping equipment in combat (each level reduces instant→0 time) | 5 |

---

## 4.4 Life Skills

A large number of non-combat skills enrich the world of SAO, and are also an important element of roleplay. Life skills use a separate "Life Skill Slot" (2 slots) and do not occupy combat Skill Slots.

### Common Effects by Life Skill Level

| Skill Level | Proficiency | Base Success Rate | Craftable Tier | Special Effect |
|-------------|-------------|-------------------|----------------|----------------|
| 1-2 | Beginner | 40% | Beginner Items | — |
| 3-4 | Apprentice | 55% | Intermediate Items | High-quality chance +10% |
| 5-6 | Journeyman | 70% | Advanced Items | High-quality chance +15%, crafting time -20% |
| 7-8 | Expert | 80% | Rare Items | High-quality chance +20%, can accept NPC orders |
| 9-10 | Master | 90% | Legendary Tier | High-quality chance +30%, can teach others (+10%) |

---

## 4.5 Blacksmithing

> *"Lisbeth's Weapon Shop — what kind of sword do you want? I can forge a custom one for you."*

### 4.5.1 Facility Requirements

- Forge (rent at blacksmith shops in major towns: 50 Col/use, or build your own at Guild Level 3+)
- Anvil, hammer (rental included in forge fee)
- Materials: corresponding ore + monster materials (per recipe requirements)

### 4.5.2 Weapon Forging Recipes

| Weapon Tier | Forging Lv Required | Core Material | Auxiliary Material | Base ATK | Success Rate |
|-------------|---------------------|---------------|--------------------|----------|--------------|
| Beginner Weapon | Lv.1 | Iron Ore×3 | Coal×1 | +2 | 80% |
| Iron-tier Weapon | Lv.2 | Iron Ore×8 + Sand Iron×2 | Coal×3 | +5 | 65% |
| Steel-tier Weapon | Lv.4 | Steel Ore×6 + Beast Hide×1 | Coal×5 | +8 | 55% |
| Knight-tier Weapon | Lv.5 | Steel Ore×10 + Black Iron Ore×2 | Coal×8 | +12 | 45% |
| Mithril-tier Weapon | Lv.7 | Mithril Ore×8 + Small Mana Crystal×2 | Small Reinforcement Stone×2 | +18 | 35% |
| Elemental Weapon | Lv.7 | Mithril base + Element Stone×3 | Medium Mana Crystal×1 | +18+element | 30% |
| Legendary Weapon | Lv.9 | Orichalcum×3 + Dragon Blood Stone×1 | Large Reinforcement Stone×2 | +30 | 20% |

### 4.5.3 Weapon Enhancement System

| Enhancement Level | Material Required | ATK Increase | Forging Lv Required | Failure Risk |
|-------------------|-------------------|--------------|---------------------|--------------|
| +1 | Iron Ore×3 | +1 | Lv.1 | None |
| +2 | Iron Ore×5 + Coal×3 | +2 | Lv.2 | None |
| +3 | Steel Ore×3 + Small Reinforcement Stone×1 | +3 | Lv.3 | 5% fail (materials lost) |
| +4 | Steel Ore×5 + Small Reinforcement Stone×2 | +4 | Lv.4 | 10% fail |
| +5 | Mithril Ore×3 + Medium Reinforcement Stone×2 | +5 | Lv.6 | 15% fail |
| +6 | Mithril Ore×5 + Medium Reinforcement Stone×3 | +6 | Lv.7 | 25% fail, 5% weapon destroyed |
| +7 (max) | Orichalcum×1 (or Vulcan's Heart×1) + Large Reinforcement Stone×1 | +7 | Lv.9 | 40% fail, 15% weapon destroyed |

> **Kirito's Elucidator +45** corresponds to a +6 ~ +7 enhancement level in the TRPG.

### 4.5.4 Weapon Repair

| Damage Level | Requirement | Cost | Forging Lv Required |
|--------------|-------------|------|---------------------|
| Minor wear (durability >50%) | Iron Ore×2 | — | Lv.1 |
| Moderate wear (durability 25-50%) | Steel Ore×3 | — | Lv.3 |
| Severe wear (durability <25%) | Mithril Ore×2 + Small Reinforcement Stone×1 | — | Lv.5 |
| Weapon broken (durability zero) | Original base material | 1,000 Col | Lv.7 |

### 4.5.5 Forging Check

```
Roll D100 ≤ (DEX + Forging Skill×5)
─ At a town blacksmith shop: +10 to check (professional equipment)
─ Using herbs/seasonings (cooking bonus does not apply): extra +5
─ Great Success (01-05): Quality +1 tier / enhancement always succeeds
─ Great Failure (96-00): Materials lost / weapon destroyed on enhancement
```

---

## 4.6 Armor Crafting

### 4.6.1 Facility Requirements

- Smithing workbench (same as blacksmith shop, or guild facility)
- Materials: ore + leather/cloth

### 4.6.2 Body Armor Recipes

| Armor Name | Lv Required | Core Material | Auxiliary Material | Base DEF | Evasion Penalty |
|------------|-------------|---------------|--------------------|----------|-----------------|
| Leather Armor | Lv.1 | Beast Hide×5 | Linen×3 | +5 | -2 |
| Chainmail | Lv.3 | Iron Ore×8 + Beast Hide×3 | Coal×3 | +9 | -5 |
| Steel Breastplate | Lv.5 | Steel Ore×10 + Tough Beast Hide×2 | Coal×5 | +15 | -8 |
| Knight Armor | Lv.6 | Steel Ore×15 + Black Iron Ore×5 | Small Reinforcement Stone×2 | +22 | -10 |
| Dragon Scale Armor | Lv.8 | Mithril Ore×10 + Dragon Scale×3 | Medium Reinforcement Stone×2 | +30 | -12 |
| Paladin Armor | Lv.10 | Orichalcum×5 + Holy Spirit Herb×1 | Large Reinforcement Stone×2 | +40 | -12 |

### 4.6.3 Shield Crafting

| Shield | Lv Required | Core Material | DEF | Special Effect |
|--------|-------------|---------------|-----|----------------|
| Small Round Shield | Lv.1 | Iron Ore×3 + Beast Hide×1 | +4 | Block +10% |
| Knight Shield | Lv.4 | Steel Ore×5 + Black Iron Ore×1 | +8 | DEF×3 when blocking |
| Tower Shield | Lv.7 | Steel Ore×10 + Mithril Ore×3 | +15 | Can block AOE |

### 4.6.4 Armor Enhancement

| Enhancement Level | Material Required | DEF Increase | Lv Required | Failure Risk |
|-------------------|-------------------|--------------|-------------|--------------|
| +1 | Iron Ore×3 | +1 | Lv.1 | None |
| +2 | Iron Ore×5 | +2 | Lv.2 | None |
| +3 | Steel Ore×3 + Small Reinforcement Stone×1 | +3 | Lv.3 | 5% |
| +4 | Steel Ore×5 + Small Reinforcement Stone×2 | +4 | Lv.4 | 10% |
| +5 | Mithril Ore×3 + Medium Reinforcement Stone×2 | +5 | Lv.6 | 15% |

---

## 4.7 Alchemy

> *"A good potion can save your life. A bad one... well, you may not get the chance to complain."*

### 4.7.1 Facility Requirements

- Alchemy table (rent at potion shops: 30 Col/use, or home facility)
- Medicinal herbs + empty bottles (purchased at shop: 10 Col/each)

### 4.7.2 Potion Recipes

| Potion Name | Lv Required | Core Material | Auxiliary Material | Effect | Yield |
|-------------|-------------|---------------|--------------------|--------|-------|
| Small Life Potion | Lv.1 | Herb×3 | Empty Bottle×1 | Restore 50 HP | 1 |
| Medium Life Potion | Lv.3 | Herb×5 + Moonleaf×2 | Empty Bottle×1 | Restore 150 HP | 1 |
| Large Life Potion | Lv.5 | Moonleaf×4 + Ginseng×1 | Empty Bottle×1 + Honey×1 | Restore 300 HP | 1 |
| Premium Life Potion | Lv.7 | Ginseng×2 + Phoenix Feather×1 | Empty Bottle×1 + Lingzhi×1 | Restore 500 HP | 1 |
| Small SP Potion | Lv.2 | Blue Herb×3 | Empty Bottle×1 | Restore 20 SP | 1 |
| Medium SP Potion | Lv.4 | Blue Herb×5 + Fairy Tear×1 | Empty Bottle×1 | Restore 40 SP | 1 |
| Antidote Potion | Lv.1 | Antidote Herb×3 | Empty Bottle×1 | Cure Poisoned | 1 |
| Panacea Potion | Lv.6 | Lingzhi×2 + Ginseng×1 | Empty Bottle×1 + Honey×2 | Cure all abnormal status | 1 |
| Strength Potion | Lv.4 | Dragon Tongue Herb×3 + Moonleaf×2 | Empty Bottle×1 | Temporary STR+10 (1 combat) | 1 |
| Agility Potion | Lv.4 | Windbell Flower×3 + Moonleaf×2 | Empty Bottle×1 | Temporary AGI+10 (1 combat) | 1 |

### 4.7.3 Poisons & Special Items

| Item | Lv Required | Core Material | Effect |
|------|-------------|---------------|--------|
| Paralysis Poison (Blade Coat) | Lv.3 | Snake Venom Gland×2 + Evil Mushroom×1 | Attacks add Paralyzed (1D3 turns), 3 uses |
| Lethal Poison (Blade Coat) | Lv.5 | Snake Venom Gland×3 + Evil Mushroom×2 | Attacks add Poisoned (1D6 turns, -10 HP/turn), 3 uses |
| Smoke Bomb | Lv.2 | Coal×2 + Evil Mushroom Powder×1 | All enemies HIT -20 (1 turn) |
| Bomb | Lv.3 | Coal×3 + Flame Stone Powder×1 | Area damage 30-50 |
| Large Bomb | Lv.6 | Coal×5 + Flame Stone×2 | Area damage 80-120 |

### 4.7.4 Alchemy Check

```
Roll D100 ≤ (INT + Potion Alchemy Skill×4)
─ Great Success (01-05): Yield×2 / effect +50%
─ Great Failure (96-00): Explosion! Self takes 1D20 damage, all materials destroyed
```

---

## 4.8 Cooking

> *"Asuna's cooking is truly delicious."* — Kirito

Cooking is the most representative life skill in SAO, and a core element of roleplay.

### 4.8.1 Facility Requirements

- Kitchen (rent at inn: 20 Col/use, or free home kitchen, or guild kitchen)
- Ingredients (gathering/hunting/fishing/shop purchase)
- Seasonings (purchased at shop or self-made)

### 4.8.2 Cuisine Effect Tiers

| Dish Quality | Duration | Effect | Success Rate Baseline |
|--------------|----------|--------|-----------------------|
| Failed Dish | — | VIT+1 (1h), but taste is despair-inducing | <20% check value |
| Normal | 1 hour | Single attribute +3 | 20-40% |
| Delicious | 2 hours | Single attribute +5 | 40-60% |
| Superb | 4 hours | Two attributes +5 | 60-80% |
| Legendary | 8 hours | Two attributes +8 + special effect | 80%+ |

### 4.8.3 Complete Recipes

| Dish Name | Lv Required | Main Ingredient | Auxiliary Ingredient | Effect | Note |
|-----------|-------------|-----------------|----------------------|--------|------|
| **Black Bread** | Lv.1 | Wheat×3 | Salt×1 | VIT+2 (1h) | Basic ration |
| **Grilled Fish** | Lv.2 | Any Fish×1 | Salt×1 | DEX+4 (2h) | Quality varies by fish species |
| **Sandwich** | Lv.2 | Wheat×3 + Vegetables×2 | Salt×1 | STR+3, AGI+3 (2h) | Clearer carry food |
| **Stewed Meat** | Lv.3 | Meat×3 + Vegetables×2 | Salt×1 + Herb×1 | VIT+5 (2h) | Most common warm dish |
| **Cream Stew** | Lv.3 | Vegetables×4 + Butter×1 | Salt×1 + Wheat×2 | VIT+5 (2h) | Asuna's specialty |
| **Steak** | Lv.4 | Beef×2 | Salt×1 + Herb×2 | STR+5, VIT+3 (2h) | Requires heat control |
| **Rabbit Meat Hotpot** | Lv.5 | Rabbit Meat×3 + Vegetables×3 | Salt×1 + Herb×3 | AGI+5, LUK+5 (4h) | Kirito and Asuna's courtship dish |
| **Fish Steak** | Lv.4 | Salmon×2 | Salt×1 + Butter×1 | DEX+5, AGI+3 (2h) | High-grade fish dish |
| **Dragon Meat Stew** | Lv.8 | Dragon Meat×2 + Vegetables×4 | Herb×3 + Phantom Spice×1 | STR+8, VIT+8 (8h) | Top-tier dish |
| **Rainbow Trout Dish** | Lv.6 | Rainbow Trout×1 + Vegetables×2 | Butter×1 + Herb×2 | DEX+6, AGI+4 (4h) | Beautiful appearance |
| **Golden Carp Feast** | Lv.8 | Golden Carp×1 + Rice×3 | Herb×3 + Phantom Spice×1 | All attributes +5 (8h) | Legendary |
| **Abyssal Banquet** | Lv.10 | Abyss Fish×1 + Dragon Meat×2 | Phantom Spice×2 | All attributes +8 (8h), SP recovery +50 | Mythic dish |

### 4.8.4 Cooking Check

```
Roll D100 ≤ (DEX + INT + Cooking Skill×4)
─ At home kitchen: +15 to check
─ Inn kitchen: +5 to check
─ Outdoor cooking (campfire): -10 to check
─ Using herbs: extra +5/each (max +15)
─ Using Phantom Spice: extra +20
─ Great Success (01-05): Quality +2 tiers (automatically Superb or above)
─ Great Failure (96-00): Indescribable dark cuisine; eater must pass VIT check or become Poisoned
```

### 4.8.5 Seasoning Crafting

High-grade cooking requires crafting your own seasonings:

| Seasoning | Lv Required | Material | Use |
|-----------|-------------|---------|-----|
| Soy Sauce | Lv.3 | Soybean×5 + Salt×1 + Wheat×1 | Japanese cuisine base |
| Mayonnaise | Lv.2 | Egg×2 + Oil (shop) | Sandwich bonus |
| Ketchup | Lv.2 | Vegetables×5 + Salt×1 | Italian cuisine |

---

## 4.9 Accessory Crafting

### 4.9.1 Facility Requirements

- Precision workbench (rent at accessory shop: 80 Col/use)
- Materials: ore + mana crystal + special materials

### 4.9.2 Accessory Recipes

| Accessory | Lv Required | Core Material | Auxiliary Material | Effect |
|-----------|-------------|---------------|--------------------|--------|
| Strength Ring | Lv.2 | Copper Ore×3 + Iron Ore×2 | — | STR+5 |
| Gale Ring | Lv.2 | Copper Ore×3 + Windbell Flower×1 | — | AGI+5 |
| Life Charm | Lv.3 | Iron Ore×5 + Small Mana Crystal×1 | Beast Hide×1 | HP+100 |
| Sword Energy Crystal | Lv.3 | Silver Ore×3 + Small Mana Crystal×1 | — | SP+30 |
| Critical Ring | Lv.5 | Silver Ore×5 + Medium Mana Crystal×1 | Wolf Fang×2 | CRT rate +10% |
| Regen Ring | Lv.7 | Gold Ore×5 + Medium Mana Crystal×2 | Phoenix Feather×1 | Restore 10 HP per turn |
| Lucky Rabbit Foot | Lv.5 | Rabbit Meat×3 + Gold Ore×2 | Medium Mana Crystal×1 | LUK+15, drop rate ×1.5 |
| Teleport Charm | Lv.8 | Gold Ore×5 + Transfer Stone×3 | Large Mana Crystal×1 | One free teleport per day |
| Dragon Scale Necklace | Lv.7 | Dragon Scale×3 + Gold Ore×3 | Dragon Fang×1 | DEF+10, Fire resistance |
| Fairy Plume | Lv.6 | Fairy Powder×3 + Silver Ore×5 | Butterfly Wing×1 | EVA+10, SPD+5 |

### 4.9.3 Accessory Crafting Check

```
Roll D100 ≤ (DEX + INT + Accessory Crafting Skill×4)
─ Great Success (01-05): Gain random additional special effect
─ Great Failure (96-00): All materials destroyed
```

---

## 4.10 Tailoring

### 4.10.1 Facility Requirements

- Tailoring table (rent at tailor shop: 30 Col/use)
- Materials: cloth + leather + special thread

### 4.10.2 Tailoring Recipes

| Armor | Lv Required | Core Material | Auxiliary Material | DEF | Special Effect |
|-------|-------------|---------------|--------------------|-----|----------------|
| Cloth Garb | Lv.1 | Linen×5 | — | +1 | EVA penalty 0 |
| Cotton Robe | Lv.2 | Cotton Cloth×8 | Linen×3 | +3 | EVA penalty 0 |
| Leather Armor | Lv.3 | Beast Hide×5 + Linen×3 | — | +5 | EVA penalty -2 |
| Silk Robe | Lv.5 | Silk×8 + Cotton Cloth×3 | Wool×2 | +5 | EVA+5, SPD+3 |
| Mage Robe | Lv.7 | Mage Cloth×6 + Silk×4 | Medium Mana Crystal×2 | +8 | Magic damage -10 |
| Phantom Cloak | Lv.9 | Phantom Silk×5 + Mage Cloth×3 | Large Mana Crystal×1 | +5 | EVA+15, Stealth+20 |
| Wool Coat | Lv.3 | Wool×8 | Silk×2 | +4 | Cold resistance (no penalty in snowy areas) |

### 4.10.3 Tailoring Check

```
Roll D100 ≤ (DEX + INT + Tailoring Skill×4)
─ Great Success (01-05): Quality +1 tier, exquisite appearance
─ Great Failure (96-00): Poor fit, must redo
```

---

## 4.11 Gathering-Type Life Skills

### 4.11.1 Mining

**Check**: `D100 ≤ (STR + Mining Skill×3 + LUK÷2)`

| Area Type | Lv Required | Common Yield | Rare Yield (10%) | Great Success Yield |
|-----------|-------------|--------------|-----------------|---------------------|
| Shallow Mine (Floor 1-5) | Lv.1 | Iron Ore, Coal, Copper Ore | Sand Iron | Steel Ore |
| Mid Mine (Floor 6-15) | Lv.3 | Steel Ore, Coal, Fluorite | Silver Ore | Black Iron Ore |
| Deep Mine (Floor 25-40) | Lv.6 | Mithril Ore, Gold Ore | Small Mana Crystal | Medium Mana Crystal |
| Special: Snow Mountain Vein | Lv.5 | Iron Ore, Steel Ore | Ice Crystal Stone | Ice Crystal Stone×3 |
| Special: Volcano Vein | Lv.5 | Steel Ore, Coal | Flame Stone | Flame Stone×3 |
| Legendary Vein (Floor 50+) | Lv.9 | Mithril Ore, Gold Ore | Orichalcum (2%) | Starlight Stone |

**Each mining session**: Consumes 2 hours of game time. Success yields 1D3 of that area's common material.

### 4.11.2 Gathering

**Check**: `D100 ≤ (INT + Gathering Skill×3 + LUK)`

| Area Type | Lv Required | Common Yield | Rare Yield (10%) |
|-----------|-------------|--------------|-----------------|
| Grassland (Floor 1-10) | Lv.1 | Herb, Vegetables, Wild Berries, Wheat | Blue Herb |
| Forest (Floor 5-20) | Lv.3 | Antidote Herb, Moonleaf, Honey, Evil Mushroom | Herb |
| Wetland/Swamp (Floor 8-20) | Lv.4 | Evil Mushroom, Dragon Tongue Herb | Blue Herb, Windbell Flower |
| Highlands (Floor 15-30) | Lv.3 | Windbell Flower, Cotton Cloth | Silk |
| Snow Mountain (Floor 18-50) | Lv.7 | Moonleaf, Ice Crystal Flower | Ginseng |
| Deep Mountains (Floor 30-50) | Lv.7 | Ginseng, Lingzhi | Lingzhi×2 |
| Sacred Ground (Floor 70+) | Lv.9 | Ginseng, Lingzhi | Holy Spirit Herb (2%) |

**Each gathering session**: Consumes 1 hour of game time. Success yields 1D3 of that area's common material.

### 4.11.3 Fishing

**Check**: `D100 ≤ (DEX + Fishing Skill×3 + LUK÷2)`
**Requirement**: Fishing rod (shop purchase: 200 Col) + bait (10 Col/use, or substitute with vegetables)

| Water | Lv Required | Common Catch | Rare Catch (10%) | Great Success (01-05) |
|-------|-------------|--------------|-----------------|-----------------------|
| Floor 1-10 River | Lv.1 | Small Crucian | Trout | Treasure chest (random item) |
| Floor 10-22 Clear Stream | Lv.2 | Trout, Salmon | Rainbow Trout | Rare fish×2 |
| Floor 22 Lake | Lv.3 | Lake Bass, Salmon | Lake Master (Boss-tier, requires combat) | Ancient gold coin (2000 Col) |
| Floor 15-30 Swamp | Lv.4 | Giant Catfish | Rainbow Trout | Rare material |
| Floor 40+ Secret Water | Lv.7 | Rainbow Trout | Golden Carp (5%) | Legendary catch |
| Floor 70+ Dark Lake | Lv.9 | Rainbow Trout, Golden Carp | Abyss Fish (3%) | Mythic item |

**Each fishing session**: Consumes 1-2 hours of game time. Success catches 1 fish.

### 4.11.4 Hunting

**Check**: `D100 ≤ (AGI + DEX + Hunting Skill×2)`
**Condition**: After defeating a beast-type monster, perform a Hunting check on the corpse

| Source Monster | Lv Required | Common Harvest (success) | Rare Harvest (great success) |
|----------------|-------------|--------------------------|------------------------------|
| Beast-type | Lv.1 | Beast Hide×1D3, corresponding Meat×1D2 | Tough Beast Hide×1 |
| Ox-type | Lv.2 | Beef×1D3, Beast Hide×1 | Ox Horn×1 |
| Wolf-type | Lv.1 | Wolf Meat×1D2, Beast Hide×1 | Wolf Fang×1 |
| Snake-type | Lv.2 | Beast Hide×1 | Snake Venom Gland×1 |
| Dragon-type | Lv.6 | Dragon Scale×1D2 | Dragon Fang×1, Dragon Blood Stone (5%) |
| Fairy-type | Lv.4 | Fairy Powder×1D2 | Fairy Tear×1 |
| Deer-type | Lv.3 | Deer Meat×1D3, Beast Hide×1D2 | Tough Beast Hide×1 |
| Sheep-type | Lv.2 | Wool×1D3 | Wool×5 |

---

## 4.12 Knowledge-Type Life Skills

### 4.12.1 Appraisal

**Check**: `D100 ≤ (INT + Appraisal Skill×4)`

| Appraisal Target | Lv Required | Time Cost | Success Effect |
|------------------|-------------|-----------|----------------|
| Normal equipment (★~★★) | Lv.1 | 10 min | Displays complete equipment attributes |
| Rare equipment (★★★) | Lv.3 | 30 min | Displays equipment attributes and hidden effects |
| Legendary equipment (★★★★) | Lv.6 | 1 hour | Displays equipment attributes and history (includes plot clues) |
| Mythic equipment (★★★★★) | Lv.9 | 4 hours | Full appraisal |
| Unknown potion | Lv.1 | 5 min | Identify potion effect |
| Monster drop | Lv.2 | 10 min | Identify use and value |

**Appraisal fee (NPC appraisal)**: If you don't want to appraise yourself, you can pay at an item shop.
- Normal equipment: 50 Col / Rare: 200 Col / Legendary: 1,000 Col / Mythic: 5,000 Col

### 4.12.2 Monster Knowledge

**Check**: `D100 ≤ (INT + Monster Knowledge Skill×3)`

| Check Target | Success Effect |
|--------------|----------------|
| Identify monster name and level | Basic info |
| Learn monster weakness element | Whole party ×1.2 damage of that element vs monster |
| Learn monster attack pattern | Whole party EVA+5 vs that monster |
| Learn monster drops | Know drop table and probabilities |
| Discover monster hidden ability | Avoid being ambushed by special skills |

**Passive Effect**: Each level of Monster Knowledge automatically performs one check when encountering a new monster.

### 4.12.3 Cartography

**Check**: `D100 ≤ (INT + DEX + Cartography Skill×3)`

| Level | Function |
|-------|----------|
| Lv.1 | Draw a basic map of explored areas (routes + monster positions) |
| Lv.3 | Mark trap locations, hidden passages |
| Lv.5 | Mark gathering points, ore vein locations |
| Lv.7 | After mapping a whole floor, can sell it at the info shop (price = floor number×100 Col) |
| Lv.9 | Can make a "strategy map"; allies using it gain Detection +10 |

Drawing a map requires actually exploring that area. Drawing time = area size ÷ 2 hours.

### 4.12.4 Trap Disarming

**Detection Check**: `D100 ≤ (INT + Trap Disarming Skill×3)` (passive, auto-checked on entering new area)
**Disarm Check**: `D100 ≤ (DEX + Trap Disarming Skill×4)` (active, costs 1 action)

| Trap Type | Disarm Difficulty | Failure Consequence |
|-----------|-------------------|---------------------|
| Pitfall Trap | Normal (+0) | Fall damage 2D20 |
| Poison Mist Trap | Normal (+0) | Area Poisoned |
| Alarm Trap | Hard (-10) | Attracts 2D4 nearby monsters |
| Teleport Trap | Hard (-15) | Teleported to depths of maze |
| Instant-Death Trap | Extreme (-25) | HP drops to 1 |

---

## 4.13 Social-Type Life Skills

### 4.13.1 Negotiation

**Check**: `D100 ≤ (INT + LUK + Negotiation Skill×4)`

| Negotiation Goal | Difficulty | Success Effect |
|------------------|------------|----------------|
| Shop discount | Normal (+0) | 10% off (each extra level of Negotiation -1%, minimum 30% off) |
| Persuade NPC to provide info | Normal~Hard | NPC reveals hidden info |
| Quest reward negotiation | Hard (-10) | Reward +20% |
| Defuse conflict (prevent combat) | Hard~Extreme | Avoid combat with hostile NPC |
| Recruit guild member | Depends on NPC attitude | Successful recruitment |

Passive Effect: When purchasing items at shops, each level of Negotiation automatically grants a 1% discount (max level 10 = 10% discount).

### 4.13.2 Information Gathering

**Check**: `D100 ≤ (INT + Information Gathering Skill×3 + LUK÷2)`

| Collection Target | Lv Required | Time Cost | Success Effect |
|-------------------|-------------|-----------|----------------|
| General rumors | Lv.1 | 2 hours | Gain 1D3 pieces of city info |
| Quest info | Lv.2 | 4 hours | Discover 1 hidden quest |
| Boss weakness info | Lv.4 | 8 hours | Gain detailed info on 1-2 of Boss's skills |
| Rare monster location | Lv.5 | 6 hours | Learn rare monster respawn location |
| Hidden area info | Lv.7 | 12 hours | Discover hidden maze or secret shop |

**Passive Effect**: In towns, every 24 hours of game time automatically grants 1 free rumor.

### 4.13.3 Guild Management

This skill affects guild operational efficiency, not personal combat power.

| Level | Effect |
|-------|--------|
| Lv.1 | Guild EXP gain +5% |
| Lv.3 | Guild storage capacity +10 slots/level |
| Lv.5 | Extra guild shop discount +5% |
| Lv.7 | Guild buff effect +50% (e.g. attribute +2→+3) |
| Lv.9 | Can build guild-exclusive facilities (forge/kitchen/alchemy table) |

### 4.13.4 Taming

**Check**: `D100 ≤ (LUK + Taming Skill×5)`
**Prerequisite**: Requires corresponding taming item (taming rope: shop 500 Col)

| Tameable Monster | Lv Required | After Success | Familiar Ability |
|------------------|-------------|---------------|------------------|
| Small Feydrake | Lv.5 | Gain flying familiar (similar to Pina) | Healing breath: restores 30 HP to master / once per combat |
| Young Wolf | Lv.3 | Gain wolf familiar | Track scent: Detection +10 |
| Eaglet | Lv.4 | Gain eagle familiar | Aerial scout: auto-draws area map |
| Small Elemental | Lv.7 | Gain elemental familiar | Corresponding element attack: ATK×0.5 |

**Taming Restrictions**:
- Each Player can only have 1 familiar
- A familiar cannot be revived after dying in battle
- On taming failure, the monster immediately attacks

---

## 4.14 Title System

Players in SAO earn unofficial titles (Dual Name / *futatsuna*) based on their actions:

| Title | Acquisition Condition | Effect |
|-------|----------------------|--------|
| **Flash** | Rapier skill Lv.9, highest SPD in party | Social check +10 |
| **Black Swordsman** | One-Handed Sword Lv.10, equipped with black coat | Intimidation check +15 |
| **Beater** | Beta Tester + high-profile behavior | Some NPCs -15 attitude, some +15 |
| **Berserker** | Kill 10+ monsters in a single combat | Combat morale +5 ATK (encounter only) |
| **Front Liner** | Participated in 3+ Floor Boss subjugations | Shop discount 5% |
| **Master Blacksmith** | Forging skill 7+ | Forging order price ×1.5 |
| **Master Chef** | Cooking skill 8+ | Cuisine sale price ×2 |
| **Pioneer** | First to activate a new floor's teleport gate | EXP+100 (one-time) |

---

## 4.15 Downtime Daily Activities

SAO is not only about clearing. A character's "daily life" between chapters is equally important.

Each "game day" a character can perform **2 daily activities** (excluding combat):

| Activity | Effect | Check |
|----------|--------|-------|
| Part-time work (restaurant/shop) | Gain 50-200 Col | None |
| Forging practice | Forging EXP +1, may produce items | DEX |
| Cooking practice | Cooking EXP +1, may produce dishes | DEX |
| Information gathering | Gain 1D3 pieces of info | INT |
| Fishing | Gain fish/ingredients | LUK |
| Socializing (with NPC) | Raise specific NPC affinity | INT+LUK |
| Training | Gain small EXP (Level×5) | STR or AGI |
| Shopping | Buy supplies and equipment | — |
| Explore town | Discover hidden shop or quest | INT+LUK |
| Rest | HP/SP fully restored | — |

---

## Appendix: Skill Quick Planning Table

```
═══════════════════════════════
  Character Creation Skill Point Allocation Suggestions
═══════════════════════════════

Lv.1 Creation (10 points):
  Frontline type: Weapon 5 + Block 3 + Evasion 2
  Speed type: Weapon 5 + Evasion 3 + Detection 2
  Support type: Weapon 4 + First Aid 4 + Detection 2
  Life type: Weapon 3 + Cooking 3 + Forging 2 + Gathering 2

═══════════════════════════════
  Life Skill Combination Suggestions
═══════════════════════════════
  Blacksmith route: Forging + Mining + Appraisal
  Alchemist route: Potion Alchemy + Gathering + Monster Knowledge
  Chef route: Cooking + Fishing/Hunting + Negotiation
  Tailor route: Tailoring + Hunting/Gathering + Negotiation
  Accessory maker route: Accessory Crafting + Mining + Appraisal
═══════════════════════════════
```
## Chapter 5: World Setting

> *"Aincrad. A steel floating castle made of 100 Floors. This is our world, and also our prison."*

---

## 5.1 Aincrad Overview

Aincrad is a massive floating castle made of 100 Floors. Each Floor is an independent world, with its own unique climate, terrain, and ecosystem.

### 5.1.1 Basic Structure

```
── Floor 100: Ruby Palace (where Kayaba Akihiko resides)
...
── Floors 76-99: Upper-tier region (rarely reached by the Clearers)
── Floor 75 (current clearing progress as of anime Season 1)
...
── Floor 50: Main relay town "Algade"
...
── Floor 22: Lakeshore and forest (where Kirito and Asuna's cabin is located)
...
── Floor 1: Town of Beginnings
```

### 5.1.2 Floor Scale

| Floor Range | Diameter (approx.) | Area (approx.) | Features |
|-------------|--------------------|----------------|----------|
| Floor 1 | 10km | ~80km² | Largest Floor, mostly grassland and forest |
| Floors 1-25 | 10→5km | Decreasing | Basic difficulty zone |
| Floors 26-50 | 5→3km | Decreasing | Intermediate difficulty zone |
| Floors 51-75 | 3→2km | Decreasing | Advanced difficulty zone |
| Floors 76-100 | 2→1km | Decreasing | Most dangerous region |

---

## 5.2 Iconic Floors

### 5.2.1 Floor 1 — Town of Beginnings

- **Town**: Town of Beginnings (largest population, ~3000 permanent residents)
- **Environment**: Temperate grassland, gentle hills, low-level forest
- **Floor Boss**: Illfang the Kobold Lord
- **SAO History**: The Floor 1 Boss raid was the baptism of the first death game
- **Feature**: Black Iron Palace — a massive prison/monument located at the center of Town of Beginnings

### 5.2.2 Floor 2 — Floor of the Bull

- **Town**: Urbus
- **Environment**: Grassland and rocky mountain terrain, many bovine-type monsters
- **Floor Boss**: Asteris the Golden Bull King
- **Feature**: Weapon enhancement related quest line

### 5.2.3 Floor 22 — Floor of the Forest

- **Town**: Coral
- **Environment**: Vast coniferous forest and lakes; one of the few regions with year-round snow
- **Feature**: Kirito and Asuna bought a cabin here and spent a brief honeymoon
- **Representative Monsters**: Large fish-type monsters in the lakes

### 5.2.4 Floor 50 — Relay Point

- **Town**: Algade
- **Environment**: Confluence of diverse terrain
- **Significance**: As the relay point at Floor 50, it is an important supply base for the Frontline Clearers
- **Feature**: The largest player market and information trading hub

### 5.2.5 Floor 55 — Knights of the Blood Oath Headquarters

- **Town**: Grandzam
- **Significance**: Location of the Knights of the Blood Oath (KoB) guild headquarters
- **Architecture**: An all-white knight order castle

### 5.2.6 Floor 74 — Maze Classic

- **Environment**: Maze complexity rises sharply
- **Floor Boss**: Gleam Eyes
- **SAO History**: Kirito first demonstrated Dual Blades before everyone, defeating the Boss alone

### 5.2.7 Floor 75 — Floor of Death

- **Floor Boss**: Skull Reaper
- **SAO History**: A battle in which the Clearers suffered heavy casualties. Kirito uncovered Kayaba Akihiko's identity
- **Feature**: The Boss possesses power far beyond its Floor, and is one of the deadliest Bosses in SAO

### 5.2.8 Floor 100 — Ruby Palace

- **Location**: The top of Aincrad
- **Environment**: Magnificent palace, blood-red sky
- **Theoretical Floor Boss**: Kayaba Akihiko (Heathcliff) himself
- **Game History**: The decisive battle occurred early at Floor 75; Floor 100 was never reached during the clearing

---

## 5.3 Floor Design Template

The GM may refer to the following template when designing a new Floor:

```
═══════════════════════════════
  Floor [X] Design Sheet
═══════════════════════════════

Floor: [___]    Name: [_____________]
Diameter: [___] km    Recommended Level: Lv.[__] ~ [__]

[Environment Theme]
Terrain: [Plains/Forest/Desert/Swamp/Snowy Mountain/Volcano/...]
Climate: [Mild/Hot/Cold/Rainy/...]
Color Tone: [_____________]

[Main Town]
Name: [_____________]
Scale: [Village/Small Town/City]
Population: [____] NPC + [____] Players
Main Facilities: [Item Shop/Weapon Shop/Inn/Info Broker/...]

[Wilderness Areas]
Area A: [Name] — [Monster Level] — [Feature]
Area B: [Name] — [Monster Level] — [Feature]
Area C: [Name] — [Monster Level] — [Feature]

[Maze Area]
Entrance: [Location Description]
Depth: [B1~B(X)]
Special Traps: [_____________]
Maze Monster Level: Lv.[__] ~ [__]

[Floor Boss]
Name: [_____________]
Level: Lv.[__]
HP: [____]  SP: [____]
ATK: [____]  DEF: [____]
Special Skills:
  1. [_____________]
  2. [_____________]
  3. [_____________]

[Unique Resources]
Gathering: [Ore/Herbs/Ingredients/...]
Quests: [_____________]
Rare Drops: [_____________]
```

---

## 5.4 Guild System

Guilds are the core form of player organization in SAO.

### 5.4.1 Guild Types

| Type | Scale | Representative Guilds | Features |
|------|-------|----------------------|----------|
| Clearing Guild | 20-50 members | Knights of the Blood Oath (KoB), Divine Dragon Alliance (DDA) | Clearing-focused, strict discipline |
| Mid-size Guild | 10-30 members | Fuurinkazan, Moonlit Black Cats | Balances clearing and mutual aid |
| Small Guild | 3-10 members | Silver Flag | A tight-knit small group |
| Production Guild | Unlimited | — | Focused on crafting, cooking, and other production activities |
| Commercial Guild | Unlimited | — | Runs shops and market trading |

### 5.4.2 Guild Creation (TRPG Rules)

Players can create a guild in-game. Requirements:

- **5,000 Col** registration fee
- **At least 3** initial members
- **Guild Name** and **Guild Emblem**
- Registered at the Guild Administration Office in the Black Iron Palace on Floor 1

### 5.4.3 Guild Levels and Benefits

| Guild Level | Total EXP Required | Member Cap | Benefits |
|-------------|--------------------|------------|----------|
| 1 | — | 10 | Guild Storage (20 slots) |
| 2 | 5,000 | 20 | Guild Storage expansion, EXP +5% |
| 3 | 15,000 | 30 | Guild Buff: specific attribute +2 |
| 4 | 30,000 | 40 | Guild Shop 10% discount |
| 5 | 50,000 | 50+ | Guild-exclusive quests, guild cabin |

### 5.4.4 Major NPC Guilds (GM Reference)

| Guild | Leader | Role | Attitude Toward Players |
|-------|--------|------|-------------------------|
| Knights of the Blood Oath (KoB) | Heathcliff | Strongest clearing guild | Elitist; requires passing a test |
| Divine Dragon Alliance (DDA) | — | Large clearing guild | Competitive relationship |
| Fuurinkazan | Klein | Friendly mid-size guild | Friendly, eager to cooperate |
| Moonlit Black Cats | Keita | Small guild | — (wiped out in SAO) |
| the Army (ALF) | Shinka | Large-scale organization | Responsible for maintaining order but inefficient, internally corrupt |

---

## 5.5 Town Facilities

Each Floor's main town usually contains the following facilities:

| Facility | Function |
|----------|----------|
| **Item Shop** | Buy consumables such as potions, crystals, and throwing items |
| **Weapon Shop** | Buy and repair weapons |
| **Armor Shop** | Buy and repair armor |
| **Inn** | Rest to recover HP and gain Buffs |
| **Teleport Gate** | Instant travel between unlocked Floors (requires a Teleport Crystal or passing through the gate) |
| **Info Broker** | Buy maps, quest intel, and monster weaknesses |
| **Player Market** | Trading venue between players (largest at Algade on Floor 50) |
| **Forge Facilities** | Requires the Forging skill to use |
| **Cooking Facilities** | Requires the Cooking skill to use |
| **Storage** | Store items (paid service) |

---

## 5.6 Teleport System

### 5.6.1 Teleport Gate

- Each Floor's main town has a Teleport Gate
- Can only teleport to **unlocked** Floor Teleport Gates
- Usage fee: Target Floor × 10 Col
- The Teleport Gate on Floor 1 was the first to be unlocked

### 5.6.2 Teleport Crystal

- A single-use item that teleports you to the nearest town's Teleport Gate upon use
- **Usable during combat**, but with a 10-second delay
- Price: 500 Col (expensive early on)
- A standard escape item for the Frontline Clearers

### 5.6.3 Corridor Crystal

- Extremely rare item
- Opens a temporary Teleport Gate connecting to any previously visited Teleport Gate
- Can be used deep in a Maze to let follow-up parties arrive quickly
- Price: 5,000+ Col or quest reward

---

## 5.7 Currency and Economy

### 5.7.1 Currency Unit

The currency unit of SAO is **Col**. Reference prices:

| Item | Price |
|------|-------|
| Small Life Potion (restores 50 HP) | 100 Col |
| Medium Life Potion (restores 150 HP) | 300 Col |
| Large Life Potion (restores 300 HP) | 800 Col |
| Teleport Crystal | 500 Col |
| Common Weapon (around Lv.10) | 500-1,500 Col |
| Rare Weapon (around Lv.30) | 5,000-20,000 Col |
| One Night at Inn | 50 Col |
| Simple Cooking | 10-50 Col |
| Intel (general) | 50-200 Col |
| Intel (Boss weakness) | 2,000+ Col |
| Player House (Floor 22 cabin) | ~10,000 Col (original work price) |

### 5.7.2 Income Sources of the Frontline Clearers

- Monsters drop Col
- Sell unwanted dropped equipment
- Quest completion rewards
- Boss LA rewards (selling rare drops for huge income)

---

## 5.8 Death Markers and the Monument

### 5.8.1 Black Iron Palace

A black building located at the center of Town of Beginnings on Floor 1. It is the site of the **Monument of Life**.

- The stele is engraved with the names of all players
- When a player dies, their name is struck through, and the time and cause of death are recorded
- It is a place where SAO players gather and mourn

### 5.8.2 Death Records in TRPG

The GM should record every character death in the setting of the Black Iron Palace; this becomes part of the campaign history.

---

## 5.9 Timeline (TRPG Time Framework Referencing the Original Work)

| Time | Event | Suitable TRPG Phase |
|------|-------|---------------------|
| November 6, 2022 | SAO officially launches; the death game begins | Campaign start |
| First Month | Period of chaos; ~2000 deaths | Lv.1-5, learning to survive |
| Months 2-6 | Floor 1 Boss raid → Clearers take shape | Lv.5-15 |
| Months 6-12 | Frontline clearing steadily advances to ~Floor 25 | Lv.15-30 |
| 2023 (Year 2) | Cleared to ~Floor 50 | Lv.30-50 |
| Early 2024 | Cleared to ~Floor 70 | Lv.50-70 |
| October 2024 | Floor 74 Boss (Dual Blades revealed) | Lv.70+ |
| November 2024 | Floor 75 Boss → Kayaba revealed → final battle | Lv.75-96 |
| November 7, 2024 | SAO cleared; players log out | Campaign end |

---

## 5.10 Player Housing

Players can purchase houses on specific Floors; this is an important source of SAO's "sense of life."

### 5.10.1 Housing Purchase Conditions

- Unlocked from Floor 22 and above
- Prices range from 10,000 Col (cabin) to 100,000+ Col (luxury mansion)
- Monthly maintenance fee required (1% of house price)
- Married spouses automatically share the residence

### 5.10.2 Housing Effects

| Function | Effect |
|----------|--------|
| Full Rest | HP/SP recovery speed ×2 when resting at home |
| Private Storage | 200 slots of storage space (additional to guild storage) |
| Cooking Bonus | +10% cooking success rate in the home kitchen |
| Sense of Security | Cannot be PK'd inside the home (system protection) |

---

## 5.11 Quest System

### 5.11.1 Quest Types

| Type | Source | Reward | Example |
|------|--------|--------|---------|
| **Subjugation Quest** | Town bulletin board / NPC | Col + EXP | Defeat specific monster ×10 |
| **Collection Quest** | NPC | Col + Materials | Collect herbs ×5 |
| **Escort Quest** | NPC | Col + Rare Item | Protect an NPC through a dangerous area |
| **Exploration Quest** | Info Broker | Map data + EXP | Chart the map of an unknown region |
| **Event Quest** | System (GM) | Limited equipment/items | Christmas Boss subjugation (event-limited) |
| **Guild Quest** | Guild Administration | Guild EXP + Guild Funds | Subjugate a designated Floor Boss |

### 5.11.2 Quest Difficulty and Rewards

| Difficulty | Recommended Level | Reward Col | Reward EXP |
|------------|-------------------|------------|------------|
| E | Lv.1-5 | 100-300 | 50-100 |
| D | Lv.5-15 | 300-800 | 100-300 |
| C | Lv.15-30 | 800-2,000 | 300-800 |
| B | Lv.30-50 | 2,000-5,000 | 800-1,500 |
| A | Lv.50-70 | 5,000-15,000 | 1,500-3,000 |
| S | Lv.70+ | 15,000+ | 3,000+ |

---

## 5.12 Event Monsters and Special Events

SAO features special events unrelated to Floor clearing but tied to time/festivals.

### 5.12.1 Christmas-Limited Boss (Original Work Example)

> **Nicholas the Renegade**  
> Appearance Time: December 24 (in-game time), a specific area on Floor 49  
> Legendary Drop: **Holy Revival Crystal** (can revive one deceased player)  
> SAO History: Kirito subjugated this Boss alone, but could not save the members of the Moonlit Black Cats

### 5.12.2 Event Design Template

```
Event Name: [_____________]
Trigger Time: [In-game Date/Season]
Location: [Floor/Region]
Special Drop: [_____________]
Story Background: [_____________]
```

---

## 5.13 Floor Unlock Ceremony

> When the Floor Boss is defeated, the spiral staircase to the next Floor appears.

### 5.13.1 Floor Clearing Process

1. Boss defeated → A Teleport Gate appears at the center of the Boss room
2. Enter the Teleport Gate → Arrive at the **main town** of the next Floor
3. Find the **Teleport Gate Plaza** at the center of the main town
4. **Activate the Teleport Gate**: The first player to touch the gate activates it automatically
5. Once activated, that Floor connects to the teleport network of all Floors below
6. System-wide announcement: "Floor X Cleared"

### 5.13.2 First-Arrival Rewards

| Achievement | Reward |
|-------------|--------|
| First to activate a Floor Teleport Gate | EXP+100, title "Pioneer" |
| First to discover a main town | EXP+50 |
| Participate in Floor Boss subjugation | Extra EXP +10% (all members) |

---

## 5.14 Info Brokers and Player Ecology

> *"Information is power. Especially so in a death game."* — Argo

### 5.14.1 Information Broker

Info Brokers are an important part of the SAO player ecosystem, represented by Argo "The Rat".

| Intel Type | Price Range | Acquisition Difficulty |
|------------|-------------|------------------------|
| Floor map data | 200-500 Col | Normal |
| Monster weakness intel | 300-800 Col | Normal |
| Boss strategy intel | 2,000-10,000 Col | Difficult |
| Hidden quest info | 5,000-20,000 Col | Extremely Difficult |
| Other player intel (location, level, etc.) | 1,000-5,000 Col | Special |

### 5.14.2 Player Strategy Guide

The *Strategy Guide Handbook* created by Argo is an important resource for beginners:

- Freely distributed to all players
- Includes basic survival tips, monster info, and danger-zone warnings
- Updated after each Floor is cleared
- In TRPG, this is the GM's channel for providing world information to players

---

## 5.15 Travel Between Floors

### 5.15.1 Teleport Gate Travel

The Teleport Gates of unlocked Floors' main towns allow instant teleportation. Usage fee: Target Floor × 10 Col.

### 5.15.2 Walking Travel

| Travel Method | Time Required Per Floor |
|---------------|-------------------------|
| Within same Floor, main town → Maze entrance | 2-8 hours (depending on Floor size) |
| Maze entrance → Boss room | 4-12 hours (including encounters and rest) |
| Walking through cleared Floors | Not needed (use Teleport Gate) |
| Walking from Floor 1 to Floor 50 | ~3-5 days of game time (not recommended) |

---

## 5.16 Player-to-Player Trading

In SAO, players can freely trade in Safe Zones:

| Trade Method | Description |
|--------------|-------------|
| Face-to-Face Trade | Both parties meet in town and exchange items/Col via the system menu |
| Player Market | Sell items at the market in Algade (Floor 50) or major towns (can set up a stall) |
| NPC Broker | Indirect trading through an NPC trader in town (5% fee) |
| Guild Storage | Free access among guild members (guild master must set permissions) |
| Mail | Send items via town mailboxes (delivered in 1-3 days, fee 100 Col) |

**Trade Restrictions**:

- Equipment of Rarity ★★★★ or higher can only be traded if both parties are Clearers
- Some story items cannot be traded (GM's decision)
- Orange Players cannot use NPC Broker or Mail services

---

## 5.17 Map System

Aincrad is a structured floating castle; each Floor is an independent world. The GM should use the Map System to track players' exploration progress and unlocked areas.

### 5.17.1 Map Structure of Each Floor

Each Floor contains three core regions:

```
┌─────────────────────────────────────┐
│  Main Town (Town) — Safe Zone        │
│    └ Shops, inn, facilities          │
├─────────────────────────────────────┤
│  Elevator Tower (Tower) — vertical   │
│    └ Connects upper and lower Floors │
├─────────────────────────────────────┤
│  Wilderness Area (Wilderness)        │
│    └ Grassland/forest/desert/monsters│
├─────────────────────────────────────┤
│  Maze Area (Dungeon) — Boss room at  │
│    └ Traps, elite monsters, Boss     │
└─────────────────────────────────────┘
```

### 5.17.2 Map Tracking

The GM needs to continuously track the following information:

| Tracking Item | Description | Update Timing |
|---------------|-------------|---------------|
| Cleared Floors | Which Floors have been cleared | When the Floor Boss is killed |
| Explored Areas | Which maze passages have been traversed | Each time the maze is explored |
| Teleport Gate Status | Whether each Floor's gate is activated | Upon first activation |
| Boss Alive Status | Whether the Boss has been defeated | When the Boss battle ends |
| NPC Location | Which Floor important NPCs are currently on | As the story progresses |

### 5.17.3 Complete Aincrad Map

For complete 100-Floor map data, refer to **資源/地圖資料.md**. This file contains:

- Map info for all iconic Floors (towns, environment themes, Floor Bosses, resources)
- Connections between Floors (elevator tower passages, maze passages)
- MAP_UPDATE syntax examples
- Map status tracking table template

### 5.17.4 Map Node Categories

| Node Type | Color | Description |
|-----------|-------|-------------|
| Town of Beginnings | `#10b981` | The city where the story begins |
| Frontline Town | `#3b82f6` | Unlocked frontline residential city |
| Maze Area | `#f59e0b` | Maze region containing the Boss room |
| Boss Room | `#ef4444` | Location of the Floor Boss |
| Special Area | `#a855f7` | Key story locations (Ruby Palace, etc.) |
| Unexplored | `#6b7280` | Floors the players have not yet reached |

### 5.17.5 GM Map Usage Process

1. At game start, create the map tracking table (see table above)
2. When players first arrive at a Floor, mark it "Explored"
3. After clearing the Boss, mark the Floor "Cleared" and open the next Floor
4. Before each Boss battle, show the explored progress of that Floor's maze area
5. Use special markers for important story nodes (e.g., the Moonlit Black Cats tragedy, Dual Blades unlock)

### 5.17.6 Map Nodes vs. Scenario Sections

| Map Node | Floor | Corresponding Scenario Section | Event/Purpose |
|----------|-------|-------------------------------|---------------|
| town-beginnings | Floor 1 | `lone_swordsman` Vol. 1 Act1-Act6 | Story start, forced teleport, Illfang Boss battle |
| coral-lake | Floor 22 | `lone_swordsman` Vol. 2 "Asuna's Appearance" | House purchase/marriage unlock, Asuna's cabin |
| dualblade-unlock | Floor 45 | `lone_swordsman` Vol. 3 "Awakening of Dual Blades" | Dual Blades system restriction lifted |
| algade-midpoint | Floor 50 | `lone_swordsman` Vol. 3 "Midway Boss" | Relay point, largest market |
| gleam-eyes | Floor 74 | `lone_swordsman` Vol. 4 "Gleam Eyes" | Dual Blades public debut |
| skull-reaper | Floor 75 | `lone_swordsman` Vol. 4 "Truth Revealed" | Kayaba's identity revealed |
| red-palace | Floor 100 | `lone_swordsman` Vol. 5 "Final Battle" | Ruby Palace decisive battle |

> For detailed MAP_UPDATE examples, see the `map_progression` block in `scenarios/lone_swordsman_campaign.yaml`.

3. After clearing the Boss, mark the Floor "Cleared" and open the next Floor
4. Before each Boss battle, show the explored progress of that Floor's maze area
5. Use special markers for important story nodes (e.g., the Moonlit Black Cats tragedy, Dual Blades unlock)

---

## End-of-Volume Appendix: Floor Inspiration Keywords

```
═══════════════════════════════
  100-Floor Inspiration Keywords
═══════════════════════════════

Floors 1-10:   Grassland, cattle, misty forest, dungeon, ruins,
              poison swamp, wilderness, canyon, mine, old castle
Floors 11-20:  Ice and snow, volcano, underground lake, tall tower, graveyard,
              dense forest, desert, stalactite cave, temple, sky garden
Floors 21-30:  Lake and marsh, coniferous forest, bell tower, arena, seabed,
              waterfall, rainbow valley, garden, giant tree, windmill hill
Floors 31-40:  Insect nest, lava, factory, library, cemetery,
              mirror maze, clock tower, submerged city, sea of clouds, prison
Floors 41-50:  Maze city, sky corridor, wrecked ship, treasure cave, observatory,
              colosseum, rose garden, dreamscape, gear city, relay point
Floors 51-75:  Difficulty curve rises sharply; maze complexity greatly increases
Floors 76-100: Legendary realm; each Floor is equivalent to a complete campaign
```
## Chapter 7: Supplementary Rules

> *"I just wanted to recreate this world… as completely as possible."*

---

## Supplementary Notes

This chapter supplements the systems not yet covered in the first six chapters, aligned to the Aincrad arc of the original *Sword Art Online*. The following is organized by degree of impact on the play experience.

---

# Part One: P0-Level Omissions (Affecting Core Experience)

## 7.1 Anti-Crystal Zone & Boss Room Lockdown

> *"The crystal… isn't responding!?"* — one of the most despair-inducing moments in SAO.

### 7.1.1 Anti-Crystal Zone

This is the most critical mechanic creating the tension of death in SAO. Within the following areas, **all crystal items (Teleport Crystal, Corridor Crystal, Record Crystal) are completely disabled**:

| Zone Type | Coverage | Notes |
|-----------|----------|-------|
| **Boss Room** | Entire Floor Boss room | Takes effect after the Boss room door closes |
| **Trap Zone** | Specific maze blocks | Determined by maze design |
| **Special Quest Zone** | Designated per individual quest | GM may set freely |
| **Deep High-Floor Maze** | Deep areas of mazes on Floor 50 and above | Gradually increases |

> **Player Countermeasure**: The only choice is — **defeat the Boss or die inside**. This is why every Boss battle is so tense for the Clearers.

### 7.1.2 Boss Room Door Lock System

```
Process for entering the Boss room:

1. Party gathers before the Boss door and makes a final confirmation
2. Open the Boss room gate (entry becomes possible)
3. After everyone enters → the gate closes automatically
4. The "LOCKED" mark appears on the door → crystal disablement activates
5. The door only reopens once the Boss dies
6. Those outside cannot enter; those inside cannot escape
```

**TRPG Ruling**:
- Before entering the Boss room: The GM should clearly inform the players that "once you enter, there is no turning back"
- During the Boss battle: Escape is only possible by running to the door on foot (but the door is locked) = impossible
- **Only exception**: If the guild possesses a "Corridor Crystal" and has pre-set an exit outside the Boss room (requires extremely high tactical preparation)

### 7.1.3 Retreat Rules (Outside Boss Battles)

In normal combat, players may choose to retreat:
- **Full Retreat**: All members use their main action to declare a retreat
- **Retreat Check**: All members D100 ≤ AGI×2 (difficulty depends on monster SPD)
- **Covering Sacrifice**: One character stays behind to cover, the other party members automatically succeed in retreating (that character must survive alone for 1D3 turns before attempting to retreat)
- **Teleport Crystal Retreat**: See Chapter 3, section 3.7.1

---

## 7.2 Duel System

> *"I challenge you to a duel. Mode — Total Loss Duel."*

The duel is a key mechanic for resolving disputes between players in SAO, and also a crucial driver of the plot (Kirito vs. Heathcliff's duel directly led to the turning point in the fate of the KoB).

### 7.2.1 Duel Modes

| Mode | Victory Condition | Defeat Consequence | Use |
|------|-------------------|--------------------|-----|
| **First Strike** | Land a hit on the opponent first | No real loss | Training, entertainment, sparring |
| **Half HP** | Reduce opponent's HP below 50% | HP drops to 50%, no permanent damage | Resolving disputes, guild selection |
| **Total HP** | Reduce opponent's HP to 0 | **Character death** | Fight to the death (rarely used) |

### 7.2.2 Duel Procedure

```
1. Initiator points at target, opens menu → select "Duel Request"
2. Select duel mode (Total Loss mode requires both parties to confirm a warning window)
3. Countdown 10→0
4. Duel begins (both parties' HP displayed at top of view)
5. Upon meeting victory condition → system announces the winner
```

### 7.2.3 Duel Rules (TRPG)

- **First Strike**: The first to succeed on a hit check wins. Combat lasts at most 3 turns.
- **Half HP**: Normal combat, until one side's HP drops below 50%.
- **Total HP**: **Identical to normal combat; HP reaching zero means the character's Permanent Death**. This is the most dramatic scene in SAO.

**GM Note**:
- Onlookers cannot interfere with the duel (system protection)
- Recovery items cannot be used during the duel (system-prohibited — this is the rule of duels)
- Total Loss duels should be key moments in the plot; do not casually have NPCs initiate Total Loss duels against players
- The Kirito vs. Heathcliff duel is the best example — the outcome affects the entire direction of the story

---

## 7.3 Skill Slot System

> In SAO, skills cannot all be used just because you learned them. Each player can only **equip a limited number of skills**.

This is a system often overlooked in the original work yet extremely important — it explains why players cannot master all weapons and life skills simultaneously.

### 7.3.1 Number of Skill Slots

| Character Level | Skill Slots | Description |
|-----------------|-------------|-------------|
| Lv.1 | 2 | Beginners can only equip two skills |
| Lv.10 | 3 | |
| Lv.20 | 4 | |
| Lv.30 | 5 | |
| Lv.50 | 6 | |
| Lv.70 | 7 | |
| Lv.90 | 8 | |
| Lv.100 | 10 | |

### 7.3.2 Skill Slot Occupancy

| Skill Type | Slots Used | Notes |
|------------|------------|-------|
| Weapon Skill (each) | 1 | Only one weapon skill can be equipped in a slot = using that weapon's Sword Skills in combat |
| Passive Skill (each) | 1 | e.g., Battle Healing, Sprint, etc. |
| Life Skill (each) | 0 | Life skills do not occupy combat skill slots, but have a separate "Life Skill Slot" = 2 slots |
| General Combat Skill (each) | 1 | Guard, Evasion, First Aid, etc. |

### 7.3.3 Switching Skills

Skills can be freely changed within towns or Safe Zones. During exploration, they can be changed each time the party rests (1 hour or more).

**Strategic Layer**:
- Players must choose which weapon skill to equip — meaning they cannot use both a one-handed sword and a katana in combat simultaneously
- The choice of passive skills reflects the character's build path
- One advantage of high-level players is more skill slots

---

## 7.4 Passive Skill System

SAO has a large number of passive skills that do not consume an action, and they are the core of character customization.

### 7.4.1 Complete List of Passive Skills

| Skill Name | Effect (per level) | Max Level | Requirement |
|------------|--------------------|-----------|-------------|
| **Battle Healing** | Recover Lv.×3 HP at end of each turn | 10 | VIT 20+ |
| **Sprint** | Movement speed + AGI÷10 meters/level | 5 | AGI 15+ |
| **Light Metal Equip** | EVA penalty -2/level when wearing light armor | 5 | — |
| **Heavy Metal Equip** | Can equip heavy armor (each level unlocks higher DEF requirement) | 5 | STR 18+ |
| **Extended Weight** | Weight capacity +10 kg/level | 5 | STR 15+ |
| **Meditation** | SP recovery speed during rest ×1.5/level | 5 | INT 15+ |
| **Emergency Recovery** | DEF+5/level when HP below 25% | 5 | VIT 15+ |
| **Hypersense** | Detection of hidden enemies +5/level | 5 | Level 30+ |
| **Weapon Guard** | Weapon block success rate +5%/level | 5 | DEX 15+ |
| **Potion Efficiency** | Potion recovery amount +10%/level | 5 | — |
| **Drop Rate Up** | Monster material drop rate +5%/level | 5 | LUK 15+ |

### 7.4.2 Detailed Explanation of Key Passive Skills

#### Battle Healing
One of the most important passive skills in SAO. Kirito possessed a high level of Battle Healing in the later stages, allowing continuous recovery during battle.

| Level | Recovery per Turn | Description |
|-------|-------------------|-------------|
| 1-3 | 3-9 HP | Beginner recovery, better than nothing |
| 4-6 | 12-18 HP | Equivalent to 1/3 of a small potion per turn |
| 7-9 | 21-27 HP | Noticeable improvement in sustainability |
| 10 | 30 HP/turn | Equivalent to a permanently active micro-heal |

#### Sprint
Directly affects movement distance and pursuit/escape capability.

#### Meditation
The ability to recover SP between battles, crucial for characters who frequently use Sword Skills. Combined with rest, SP can be recovered quickly.

---

## 7.5 Marriage System

> *"Asuna… let's get married."*

The marriage system in SAO is one of the most touching elements of the original work. It is not just an RP element — it has actual system effects.

### 7.5.1 Marriage Conditions & Procedure

```
1. Both parties must have reached Floor 22 or above (system unlocks marriage function)
2. Purchase a wedding ring (5,000 Col, available at specific NPC shops)
3. Hold the ceremony at a church in any town (other players may be invited to witness)
4. After system confirmation, the spouse's name appears in both status windows
5. Shared functions unlocked
```

### 7.5.2 Marriage System Effects

| Function | Description |
|----------|-------------|
| **Shared Storage** | Spouse can access the other's storage (originally only the owner could open it) |
| **Location Check** | Can see the spouse's location on the map (a very practical function) |
| **HP Monitor** | Can see the spouse's real-time HP status |
| **Instant Message** | Can send instant messages to the spouse (no distance limit) |

### 7.5.3 Marriage in TRPG

- Marriage is an important RP milestone; it is recommended that the GM treat it as a story reward
- Shared storage practically means easier item management for the party
- If the spouse dies, the moment HP reaches zero in the HP monitor… this is the most heartbreaking scene in SAO

---

# Part Two: P1-Level Omissions (Important Supplements)

## 7.6 Martial Arts

> Skills in SAO for fighting without equipping a weapon. Few players use them, but they exist.

### 7.6.1 Martial Arts Sword Skills

| Level | Sword Skill | SP | Recovery Lag | Multiplier | Effect |
|-------|-------------|-----|--------------|------------|--------|
| 1 | Straight Punch | 3 | 0 | ×1.0 | Basic punch |
| 2 | Combo Punch | 5 | 0 | ×1.2 | Two-hit combo |
| 3 | Uppercut | 8 | 1 | ×1.5 | Inflicts Stun |
| 4 | Roundhouse Kick | 10 | 1 | ×1.6 | Can knock back |
| 5 | Palm Strike | 12 | 1 | ×1.8 | Ignores 5 DEF |
| 6 | Flash Blow | 18 | 2 | ×2.5 | CRT rate +20% |
| 7 | Meteor Fist | 25 | 2 | ×3.0 | Five-hit combo |
| 8 | Mountain Breaker | 35 | 3 | ×4.0 | Ultimate single-target |

**Martial Arts Passives**:
- Lv.5: "Iron Wall" — DEF = VIT×2 when unarmed
- Lv.8: "Master" — Martial arts attacks ignore 10 DEF

> **Original Work Connection**: Kirito used martial arts to kick a taunting player at the Floor 1 strategy meeting; he also used martial arts in the duel against Heathcliff.

---

## 7.7 Other Unique Skills

Besides Dual Blades, there are other Unique Skills in SAO. There are only 10 Unique Skills in all of SAO.

### 7.7.1 Known Unique Skills

| Skill Name | Holder | Effect | Unlock Condition |
|------------|--------|--------|------------------|
| **Dual Blades** | Kirito | Dual-wield one-handed weapons | Fastest reaction speed |
| **Holy Sword** | Heathcliff / Kayaba Akihiko | Integrated offense and defense, HP regeneration | GM authority (actually a system administrator skill) |
| **Infinite Spear** | — (original setting) | Ultimate evolution of the spear | Specific condition |
| **Darkness Blade** | — (original setting) | Strongest Dark-element | Specific condition |

### 7.7.2 Unique Skills in TRPG

It is recommended that the GM, in the campaign:
- **Dual Blades**: The only Unique Skill that players can unlock
- **Holy Sword**: As the exclusive ability of the final Boss (Heathcliff)
- **Other Unique Skills**: May appear as NPC abilities in the later part of the campaign, or be created by the GM

> Each Unique Skill can only be held by **one Player or NPC**. This is an inviolable system rule.

---

## 7.8 Beta Tester Mechanics

> *"That guy is a Beater!"* — the discriminatory term for Beta Testers in SAO.

### 7.8.1 Advantages of Beta Testers

| Advantage | Game Effect |
|-----------|-------------|
| Map Knowledge | Geography checks for Floors 1-10 +15 |
| Monster Knowledge | Monster weaknesses on Floors 1-10 auto-known (no check needed) |
| Quest Prerequisite | Completion speed of some quests +50% |
| Combat Experience | Initiative checks for battles on Floors 1-5 +5 |

### 7.8.2 Disadvantages of Beta Testers

| Disadvantage | Game Effect |
|--------------|-------------|
| Social Discrimination | Attitude checks of NPC players toward Beta Testers -10 |
| Information Blackout | Non-Beta players unwilling to share intel with Beta Testers |
| "Beater" Label | Some guilds refuse to accept Beta Testers |
| System Change Trap | The GM can design traps "not present during the beta," which give Beta Testers no bonus |

### 7.8.3 Use in TRPG

- The party may have 1 Beta Tester (recommended)
- Beta Testers are very strong early on, but their advantage weakens from the mid-game onward
- The social-level disadvantage is important material for RP
- The GM can use "system changes" to create unexpected challenges for Beta Testers

---

## 7.9 Familiar / Taming System

> *"Pina… Pina protected me…"* — Silica

A familiar system exists in SAO. Though very few players possess one, it does exist.

### 7.9.1 Acquiring a Familiar

- Obtained through **Taming Skill** + a specific quest
- Not all monsters can be tamed (only specific "tameable" types of younglings)
- A familiar cannot be revived after death (unlike players, a familiar has no NerveGear)

### 7.9.2 Familiar Combat Rules

| Familiar Level | HP | Actions Available |
|----------------|-----|-------------------|
| Youngling | 50 | Distract (target enemy single HIT-5), Scout (find hidden targets) |
| Growing | 100 | Distract, Scout, Small Attack (ATK×0.5) |
| Mature | 200 | Distract, Scout, Medium Attack (ATK×0.8), Special Ability |
| Complete | 350 | Distract, Scout, Attack (ATK×1.0), Special Ability×2 |

### 7.9.3 Representative Familiars

| Familiar | Owner | Type | Special Ability |
|----------|-------|------|-----------------|
| Pina | Silica | Small Feathered Dragon | Healing Breath (recovers 30 HP to owner, once per battle) |
| — | — | Wolf | Track scent |
| — | — | Hawk | High-altitude scouting, draws area map |

---

## 7.10 Player Housing

Players can purchase houses on specific Floors. This is an important source of the "sense of living" in the SAO world.

### 7.10.1 Housing Conditions

- Purchasing unlocked on Floor 22 and above
- Prices range from 10,000 Col (small cabin) to 100,000+ Col (luxury mansion)
- Monthly maintenance fee required (1% of house price)
- Married spouses automatically share the house

### 7.10.2 Housing Effects

| Function | Effect |
|----------|--------|
| Full Rest | HP/SP recovery speed ×2 when resting at home |
| Private Storage | 200 slots of storage space (additional to guild storage) |
| Cooking Bonus | Cooking success rate +10% in home kitchen |
| Sense of Security | Cannot be PKed inside the home (system protection) |

---

# Part Three: P2-Level Omissions (Icing on the Cake)

## 7.11 Monster Type System

All monsters are grouped into the following types, each with fixed traits:

| Type | Traits | Weakness | Representative |
|------|--------|----------|----------------|
| **Beast** | SPD+5, ATK+5 | No special weakness | Berserk Boar, Giant Wolf |
| **Undead** | Poison/Bleed immune | Holy×2.0 | Skeleton Warrior |
| **Insect** | EVA+5, Poison attacks common | Fire×1.5 | — |
| **Armored** | DEF+10, SPD-5 | Lightning×1.5 | Kobold Guard, Ruin Guardian |
| **Dragon** | All stats +10 | Varies by subspecies | — |
| **Demi-human** | Intelligent behavior, can use weapons | No special weakness | Kobold, Goblin-type |
| **Plant** | Poison/Paralysis attacks common | Fire×1.5 | — |
| **Magical** | Ranged attack, floating | Physical×1.2 | Demon Eye, Fairy |
| **Mechanical** | DEF+15, Poison immune | Lightning×1.5 | Mechanical Giant |

By directly applying type templates when designing monsters, the GM can greatly simplify the design process.

---

## 7.12 Weapon Durability & Destruction

### 7.12.1 Durability System

| Equipment Rarity | Durability | Repair Cost |
|------------------|-----------|-------------|
| Common ★ | 100 | Missing durability ×2 Col |
| Fine ★★ | 150 | Missing durability ×5 Col |
| Rare ★★★ | 250 | Missing durability ×10 Col |
| Legendary ★★★★ | 400 | Missing durability ×20 Col |
| Mythic ★★★★★ | 600 | Missing durability ×50 Col |

After each battle, weapon durability -1; when taking a Critical hit, weapon durability additionally -2.

### 7.12.2 Weapon Destruction

- Durability reaches zero → weapon breaks, ATK = 10% of original
- On a Critical Failure (96-00): weapon durability -10 (in very rare cases, directly causes weapon destruction in combat)

---

## 7.13 Quest System

### 7.13.1 Quest Types

| Type | Source | Reward | Example |
|------|--------|--------|---------|
| **Subjugation Quest** | Town bulletin board / NPC | Col + EXP | Defeat specific monster ×10 |
| **Collection Quest** | NPC | Col + Materials | Collect herbs ×5 |
| **Escort Quest** | NPC | Col + Rare item | Protect NPC through dangerous area |
| **Exploration Quest** | Info Broker | Map data + EXP | Map an unknown area |
| **Event Quest** | System (GM) | Limited equipment / item | Christmas Boss subjugation (event-limited) |
| **Guild Quest** | Guild administration | Guild EXP + Guild funds | Subjugate a designated Floor Boss |

### 7.13.2 Quest Levels

| Difficulty | Suggested Level | Reward Col | Reward EXP |
|------------|-----------------|------------|------------|
| E | Lv.1-5 | 100-300 | 50-100 |
| D | Lv.5-15 | 300-800 | 100-300 |
| C | Lv.15-30 | 800-2,000 | 300-800 |
| B | Lv.30-50 | 2,000-5,000 | 800-1,500 |
| A | Lv.50-70 | 5,000-15,000 | 1,500-3,000 |
| S | Lv.70+ | 15,000+ | 3,000+ |

---

## 7.14 Event Monsters & Special Events

SAO features special events unrelated to Floor clearing but tied to time/holidays.

### 7.14.1 Christmas-Limited Boss (Original Work Case)

> **Nicholas the Renegade**
> - Appearance time: December 24 (in-game time)
> - Appearance location: Specific area on Floor 49
> - Legendary drop: **Revival Holy Crystal** (can revive one already-dead player)
> - SAO history: Kirito solo-subjugated this Boss, but could not save the members of the Moonlit Black Cats

### 7.14.2 Event Design Template

```
Event Name: [_______________]
Trigger Time: [In-game date / season]
Appearance Location: [Floor / area]
Special Drop: [_______________]
Story Background: [_______________]
```

---

## 7.15 Floor Unlock Ceremony

> Only when the Floor Boss is defeated does the spiral staircase to the next floor appear.

### 7.15.1 Floor Clearing Procedure

1. Boss defeated → Teleport Gate appears at the center of the Boss room
2. Enter the Teleport Gate → Arrive at the **main town** of the next floor
3. Find the **Teleport Gate Plaza** at the center of the main town
4. **Activate the Teleport Gate**: The first player to touch it activates it automatically
5. Once the Teleport Gate is activated, that floor and all floors below connect to the teleport network
6. System-wide announcement: "Floor X Cleared"

### 7.15.2 First-Arrival Rewards

| Achievement | Reward |
|-------------|--------|
| First to activate the Floor Teleport Gate | EXP+100, title "Pioneer" |
| First to discover the main town | EXP+50 |
| Participated in Floor Boss subjugation | EXP +10% extra (all members) |

---

## 7.16 Sleep PK & Safety Mechanics

### 7.16.1 Within the Circle (Safe Zone / Safe Area)

Inside towns (within the Circle), no form of HP damage can be dealt:
- Attacks are nullified
- Duels cannot be initiated within the Circle
- But — **players can be moved or carried within the Circle**

### 7.16.2 Sleep PK

This is a malicious exploit in SAO:
1. The victim sleeps at an inn (won't wake even if HP reaches zero)
2. The attacker carries the victim from within the Circle **to outside the Circle**
3. Attacks outside the Circle
4. The victim wakes already having been attacked

**TRPG Handling**:
- Set a watch when resting at an inn (GM may prompt)
- Attacked while sleeping: initiative automatically goes to the attacker
- It is recommended that the GM use Sleep PK as a plot device, not as a random encounter (too malicious)

### 7.16.3 Inn Safety Levels

| Inn Level | Price | Safety |
|-----------|-------|--------|
| Budget Inn | 20 Col/night | Extremely low risk of being carried away |
| Standard Inn | 50 Col/night | Safe (NPC manager patrols) |
| Premium Inn | 150 Col/night | Absolutely safe (private room + electronic lock) |

---

## 7.17 Information Brokers & Player Ecology

> *"Information is power. Especially in a death game."* — Argo

### 7.17.1 Information Broker

Information brokers are an important part of the SAO player ecology, represented by Argo ("The Rat").

| Intel Type | Price Range | Acquisition Difficulty |
|------------|-------------|------------------------|
| Floor map data | 200-500 Col | Normal |
| Monster weakness intel | 300-800 Col | Normal |
| Boss strategy intel | 2,000-10,000 Col | Hard |
| Hidden quest info | 5,000-20,000 Col | Very Hard |
| Other players' intel (location, level, etc.) | 1,000-5,000 Col | Special |

### 7.17.2 Player Strategy Guide

The *Strategy Guide Manual* made by Argo is an important resource for beginners:
- Distributed free to all players
- Includes basic survival tips, monster info, and danger-zone warnings
- Updated after each floor is cleared
- In TRPG, this can be a channel for the GM to provide world information to players

---

## 7.18 Special Social Title System

In SAO, players gain unofficial titles (Dual Name / *futatsuna*) based on their behavior:

| Title | Acquisition Condition | Effect |
|-------|----------------------|--------|
| **Flash** | Rapier User skill Lv.9, highest SPD in party | Social check +10 |
| **Black Swordsman** | One-handed Sword Lv.10, equipped with black coat | Intimidation check +15 |
| **Beater** | Beta Tester + acts high-profile | Some NPCs -15 attitude, some +15 |
| **Berserker** | Kill 10+ monsters in a single battle | Combat morale +5 ATK (encounter battles only) |
| **Front Liner** | Participated in 3+ Floor Boss subjugations | Shop discount 5% |
| **Master Blacksmith** | Forging skill 7+ | Forging order price ×1.5 |
| **Culinary God** | Cooking skill 8+ | Cooked dish selling price ×2 |

---

## 7.19 Inter-Chapter Downtime Activities

SAO is not only about clearing. The "daily life" of characters between chapters is equally important.

### Daily Activity Points

Each "game day" a character may perform **2 activities** (excluding combat):

| Activity | Effect | Check |
|----------|--------|-------|
| Part-time job (restaurant/shop) | Gain 50-200 Col | None |
| Forging practice | Forging EXP +1, may produce items | DEX |
| Cooking practice | Cooking EXP +1, may produce dishes | DEX |
| Gather intel | Gain 1D3 pieces of intel | INT |
| Fishing | Gain fish / ingredients | LUK |
| Socialize (with NPC) | Raise a specific NPC's affinity | INT+LUK |
| Training | Gain small EXP (Level×5) | STR or AGI |
| Shopping | Buy supplies and equipment | — |
| Explore town | Discover hidden shops or quests | INT+LUK |
| Rest | HP/SP fully recovered | — |

---

## 7.20 Character Retirement & Inheritance

In long campaigns, player characters may die (core to SAO). To let players continue participating, the following mechanic is provided:

### 7.20.1 New Character Introduction

When a character dies, the player creates a new one:
- New character level = dead character's level - 10 (minimum 1)
- Retain 50% of the dead character's Col (as "inheritance")
- The new character's background can be set as "a non-clearer who has always lived in towns, inspired by the sacrifices on the Frontline"

### 7.20.2 Inheritance

Important equipment of the dead character can designate an heir (must be noted on the character sheet in advance):
- Designated heir → obtained unconditionally
- No designation → distributed by the party / guild
- Special equipment (e.g., the Midnight Coat) → GM decides whether it can be inherited

---

## End of Volume: Post-Supplement Rules Coverage Assessment

| Original Element | Coverage Status |
|------------------|-----------------|
| Basic combat system | ✅ Complete |
| Sword Skills + Recovery Lag | ✅ Complete |
| Switch combo | ✅ Complete |
| 100-floor worldview | ✅ Complete |
| 8 weapon skill trees | ✅ Complete |
| Dual Blades unique skill | ✅ Complete |
| Boss battle phase system | ✅ Complete |
| Life skills | ✅ Complete |
| Guild system | ✅ Complete |
| **Anti-Crystal / Boss Lockdown** | ✅ Supplemented this time |
| **Duel System** | ✅ Supplemented this time |
| **Skill Slot System** | ✅ Supplemented this time |
| **Passive Skill System** | ✅ Supplemented this time |
| **Marriage System** | ✅ Supplemented this time |
| **Martial Arts** | ✅ Supplemented this time |
| **Beta Tester Mechanics** | ✅ Supplemented this time |
| **Familiar / Taming** | ✅ Supplemented this time |
| **Player Housing** | ✅ Supplemented this time |
| **Monster Type System** | ✅ Supplemented this time |
| **Weapon Durability / Destruction** | ✅ Supplemented this time |
| **Quest Grading System** | ✅ Supplemented this time |
| **Event Monsters** | ✅ Supplemented this time |
| **Floor Unlock Ceremony** | ✅ Supplemented this time |
| **Sleep PK / Safe Zone** | ✅ Supplemented this time |
| **Information Broker System** | ✅ Supplemented this time |
| **Title System** | ✅ Supplemented this time |
| **Downtime Activities** | ✅ Supplemented this time |
| **Character Inheritance Mechanic** | ✅ Supplemented this time |

> **Coverage: Core elements of the original Aincrad arc are now covered at ≥ 95%.**

---
