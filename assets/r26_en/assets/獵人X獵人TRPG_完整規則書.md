# Hunter × Hunter TRPG Rulebook

> **Version:** v1.0
> **Codename:** hunter-trpg
> **Design Studio:** Tabletop Rules Studio
> **Core Theme:** Based on Yoshihiro Togashi's *Hunter × Hunter*, a worldview in which players create their own Nen abilities × a Restriction & Pledge balance system

---

## Table of Contents

- [Chapter 1: Core Rules](#chapter-1-core-rules)
- [Chapter 2: Character Creation](#chapter-2-character-creation)
- [Chapter 3: Combat & Conflict](#chapter-3-combat--conflict)
- [Chapter 4: World & Narrative](#chapter-4-world--narrative)
- [Appendix](#appendix)

---

# Chapter 1: Core Rules

This chapter defines the game's dice system, attribute framework, skill checks, and difficulty ladder — the foundation for all judgment of in-game actions.

---

## 1-1 Dice System

This game uses the **d20 core system**: the success or failure of all actions is decided by a single 20-sided die.

**Basic Formula:**
```
d20 + Attribute Modifier + Proficiency Bonus ≥ DC (Difficulty Class) → Success
```

**Design Philosophy:** The uniform distribution of the d20 means every +1 maps precisely to +5% success rate, giving the Game Master (GM) extremely high predictability when setting the Difficulty Class (DC), and it naturally fits the contest framework against Armor Class (AC).

---

## 1-2 The Six Core Attributes

All characters are defined by six core attributes, with values ranging from 1–20 (the normal human range is 8–18).

| Attribute | Abbreviation | Meaning | Primary Influence |
|------|------|------|----------|
| Constitution | Constitution (CON) | Physical strength, stamina, vitality | Hit Points (HP), carrying capacity, Enhancement aptitude |
| Dexterity | Dexterity (DEX) | Speed, reaction, agility | Armor Class (AC), Initiative, Transmutation aptitude |
| Perception | Perception (PER) | Observation, intuition, sensory acuity | Perception, Tracking, Emission aptitude |
| Intelligence | Intelligence (INT) | Analysis, memory, strategy | Tactics, Nen Knowledge, Conjuration aptitude |
| Willpower | Willpower (WIL) | Mental strength, resolve, stress resistance | Spirit Points (SP), Nen Defense, Manipulation aptitude |
| Charisma | Charisma (CHA) | Leadership, persuasion, presence | Persuasion, Intimidation, Specialization aptitude |

### Attribute Value → Modifier Mapping

```
Modifier = ⌊(Attribute Value − 10) / 2⌋ (round down)
```

| Attribute Value | Modifier | Description |
|:---:|:---:|------|
| 1 | −5 | Barely able to care for oneself |
| 2-3 | −4 | Extremely frail |
| 4-5 | −3 | Clearly deficient |
| 6-7 | −2 | Below average |
| 8-9 | −1 | Slightly weak |
| 10-11 | +0 | Ordinary human level |
| 12-13 | +1 | Slightly above average |
| 14-15 | +2 | Clearly excellent (common among Hunter Exam passers) |
| 16-17 | +3 | Gifted (Professional Hunter level) |
| 18-19 | +4 | Top-tier (Star Hunter) |
| 20 | +5 | Human limit (Chairman level) |

---

## 1-3 Derived Attributes

| Attribute | Formula | Purpose |
|------|------|------|
| **Hit Points (HP)** | Constitution × 5 + 10 | Absorb physical damage |
| **Spirit Points (SP)** | Willpower × 5 + 10 | Fuel for Nen abilities |
| **Armor Class (AC)** | 10 + Dexterity Modifier + Nen Defense Bonus | Threshold to be hit by physical attacks |
| **Initiative** | Dexterity Modifier + Perception Modifier | Determines combat action order |
| **Nen Defense (ND)** | Willpower Modifier + Four Major Technique Proficiency Bonus | Direct damage reduction against Nen attacks |

### Four Major Technique Proficiency and Nen Defense Bonus

| Four Major Technique Level | Nen Defense Bonus | Nen Type Check Bonus |
|:---:|:---:|:---:|
| Lv.0 (Unawakened) | +0 | +0 |
| Lv.1 (Novice) | +1 | +1 |
| Lv.2 (Skilled) | +2 | +2 |
| Lv.3 (Adept) | +3 | +3 |
| Lv.4 (Ultimate) | +4 | +4 |

---

## 1-4 Skill System

### Complete Skill List

#### Constitution (CON)
| Skill | Purpose |
|------|------|
| **Endurance** | Resist fatigue, poison, extreme environments |
| **Survival** | Wilderness survival, foraging, tracking prey |
| **Athletics** | Climbing, swimming, jumping, running |

#### Dexterity (DEX)
| Skill | Purpose |
|------|------|
| **Stealth** | Concealed movement, hiding, tailing |
| **Acrobatics** | Balance, tumbling, dodging traps |
| **Sleight of Hand** | Pickpocketing, lockpicking, fine manipulation |
| **Marksmanship** | Firearms, bows, thrown weapons |

#### Perception (PER)
| Skill | Purpose |
|------|------|
| **Perception** | Spot hidden objects, faint sounds |
| **Tracking** | Follow footprints, read scene clues |
| **Insight** | Read people, judge lies |
| **Nen Sense** | Sense Nen aura, judge SP and Nen type |

#### Intelligence (INT)
| Skill | Purpose |
|------|------|
| **Nen Knowledge** | Nen ability theory, knowledge of each type, restriction analysis |
| **Investigation** | Scene analysis, intelligence gathering, logical deduction |
| **Medicine** | First aid, dissection, medical application of Nen |
| **Tactics** | Combat planning, enemy analysis, team coordination |

#### Willpower (WIL)
| Skill | Purpose |
|------|------|
| **Nen Control** | SP allocation (Ryu), emission and absorption of aura |
| **Concentration** | Resist interference, maintain Nen techniques, prolonged vigilance |
| **Courage** | Resist fear, intimidation, mental attacks |
| **Oath** | Establish and maintain restrictions & pledges |

#### Charisma (CHA)
| Skill | Purpose |
|------|------|
| **Persuasion** | Convince, bargain, build cooperation |
| **Deception** | Lie, disguise, mislead |
| **Intimidation** | Show power to deter, force confessions |
| **Leadership** | Inspire allies, command operations |

### Proficiency Levels

| Level | Bonus | Description |
|------|:---:|------|
| Unskilled | +0 | Anyone can attempt, relying only on talent |
| Proficient | +2 | Has received formal training |
| Expert | +4 | A professional in the field |
| Master | +6 | World-class level |

### Acquiring Proficiency Points

- **At character creation:** Gain **6–8 Proficiency Points**
- **Each growth stage advancement:** +4 Proficiency Points
- **Experience Points (XP) purchase** (optional): Proficient → Expert costs 8 Experience Points (XP), Expert → Master costs 12 Experience Points (XP)

### Skill Check Formula

```
Skill Check = d20 + Corresponding Attribute Modifier + Proficiency Bonus
```

**Example:** Gon (Perception 15, +2) uses "Tracking" (Proficient, +2) to trail a target. Rolls d20(13) + 2 + 2 = 17. The Game Master (GM) rules that tracks in the rainy mud are obvious, Difficulty Class (DC) 12 → **Success**.

---

## 1-5 Difficulty Ladder (DC)

| Difficulty Class (DC) | Difficulty | Hunter World Example |
|:---:|------|------|
| 5 | Very Easy | Find a bestselling book in a library |
| 8 | Very Simple | Recognize the Heavens Arena logo |
| 10 | Simple | Climb a 2m wall |
| 12 | Slightly Moderate | Notice a tail in a crowd |
| **15** | **Moderate (baseline)** | Use "Zetsu" to hide aura; identify a Nen user's type |
| 18 | Hard | Use "Ryu" to precisely allocate SP during combat |
| 20 | Very Hard | Use a Nen ability cross-type at 60% efficiency |
| 22 | Expert | Maintain "En" at a 50m radius while fighting |
| 25 | Extremely Hard | Analyze an opponent's restrictions & pledges mid-combat |
| 28 | Master | Pass a Nen beast sentry with "Zetsu" unprepared |
| 30 | Legendary | Chairman-level — a punch with flesh surpassing the speed of sound |

> **Difficulty Class (DC) 15 baseline calibration:** Attribute 14 (+2) + Proficiency (+2) = 50% success rate. This ensures the stacking of talent + training yields a perceptible sense of growth, without making any check an automatic success.

---

## 1-6 Check Rules

### Standard Check

```
d20 + Attribute Modifier + Proficiency Bonus + Other Bonuses ≥ DC → Success
```

**Natural 20 (critical success):** Automatic success; the Game Master (GM) grants an extra benefit.
**Natural 1 (critical failure):** Automatic failure, possibly with a minor side effect.
Triggered only when it matters — climbing a 1m wall won't get you "killed" even on a 1.

### Contest Check

```
Active side: d20 + Attribute Modifier + Proficiency Bonus
Passive side: d20 + Attribute Modifier + Proficiency Bonus
Active side ≥ Passive side → Active side wins
```

On a tie, the higher Attribute Modifier wins; if still tied, the status quo is maintained.

### Group Check

- The helper must have **Proficient** rank or higher in the skill
- The helper rolls a Difficulty Class (DC) 10 check; on success the main actor gains +2 (not stackable)
- When multiple people attempt simultaneously: if at least half succeed, the group succeeds

### Advantage / Disadvantage

- **Advantage:** Roll 2d20, take the higher
- **Disadvantage:** Roll 2d20, take the lower
- Advantage and disadvantage are mutually exclusive; when either applies, ignore other situational bonuses

| Base Success Rate | With Advantage | With Disadvantage | Equivalent Bonus |
|:---:|:---:|:---:|:---:|
| 30% | 51.0% | 9.0% | ≈ +4.2 |
| 50% | 75.0% | 25.0% | ≈ +5.0 |
| 65% | 87.8% | 42.3% | ≈ +4.6 |

---

## 1-7 Saving Throws

When a special effect does not target Armor Class (AC), the target makes a saving throw:

```
Saving Throw = d20 + Corresponding Attribute Modifier + Proficiency Bonus (if proficient in that save)
```

| Save | Attribute | Common Uses |
|------|------|----------|
| Fortitude Save | Constitution | Resist poison, disease, physical restraint |
| Reflex Save | Dexterity | Dodge area attacks, traps |
| Will Save | Willpower | Resist mental control, fear, Nen pressure |

---

# Chapter 2: Character Creation

---

## 2-1 Seven Steps of Character Creation

| Step | Content | Reference Section |
|:---:|------|:---:|
| 1 | Background setup (origin, motivation, personality) | 2-2 |
| 2 | Attribute allocation (27 points free distribution) | 2-3 |
| 3 | Water Divination (determine main Nen type) | 2-4 |
| 4 | Design Nen ability (Binding Pledge points (BP) system) | 2-5 |
| 5 | Initial Four Major Techniques setup | 2-6 |
| 6 | Choose Hunter Domain | 2-7 |
| 7 | Equipment & Resources | 2-8 |

---

## 2-2 Background Setup

### Origin (d10)

| d10 | Origin |
|:---:|------|
| 1 | Ordinary family — no special background; set out on the Hunter path due to some trigger |
| 2 | Hunter family — parents or elders are Hunters |
| 3 | Slums / streets — learned various skills to survive |
| 4 | Wealthy household — rich in resources but burdened by family expectations |
| 5 | Remote region — from an underdeveloped but simple and honest homeland |
| 6 | Criminal organization — grew up in the Mafia |
| 7 | Research institution — from a lab or academy |
| 8 | Wanderer — no fixed residence, roams the world |
| 9 | Secret society — member of a hidden organization |
| 10 | Otherworld — from the vicinity of the Dark Continent or a special environment |

### Motivation (d12)

| d12 | Reason for Becoming a Hunter |
|:---:|------|
| 1 | Searching for someone (missing family / mentor / enemy) |
| 2 | Pursuit of power |
| 3 | Protect what matters |
| 4 | Curiosity — want to witness the world's unknown firsthand |
| 5 | Money and fame |
| 6 | Atonement — seek redemption for past mistakes |
| 7 | Inheritance — carry on someone's last will |
| 8 | Freedom — the Hunter License is the ultimate pass |
| 9 | Revenge |
| 10 | Prove oneself — to someone or to the world |
| 11 | No specific purpose — go with the flow |
| 12 | Fate — feel guided by some force |

---

## 2-3 Attribute Allocation

### 27-Point Free Allocation Method

- All attributes start at a base value of **8**
- The player has **27 attribute points**
- A single attribute can be raised to a maximum of **15** (cap during allocation phase)

| Attribute Value | Cumulative Cost | Per-Level Cost | Modifier |
|:---:|:---:|:---:|:---:|
| 8 | 0 | — | −1 |
| 9 | 1 | 1 | −1 |
| 10 | 2 | 1 | +0 |
| 11 | 3 | 1 | +0 |
| 12 | 4 | 1 | +1 |
| 13 | 5 | 1 | +1 |
| 14 | 7 | 2 | +2 |
| 15 | 9 | 2 | +2 |

### Recommended Allocation Plans

| Plan | Attribute Distribution | Suited For |
|------|---------|------|
| Balanced | 13, 13, 13, 12, 12, 12 | Beginners, uncertain direction |
| Twin Peaks | 15, 15, 12, 10, 8, 8 | Specialize in two fields |
| Primary Polarization | 15, 14, 13, 10, 10, 8 | Clear primary-attribute build |
| Three-Dimensional Balance | 14, 14, 13, 12, 10, 8 | Flexible generalist |
| Social Specialist | 15, 12, 12, 10, 10, 14 | Charisma-type character |

### Post-Allocation Bonuses

1. **Nen type bonus** (after Water Divination): main type's corresponding attribute +2
2. **Hunter Domain bonus** (after choosing domain): domain's corresponding attribute +1

The final single-attribute cap is **17** (15 + 2), and the starting modifier can reach +3 at most.

---

## 2-4 Water Divination: Nen Type Determination

### The Six Types

```
                 Enhancement
                      |
        Transmutation — + — Emission
                      |
         Conjuration — + — Manipulation
                      |
                 Specialization
```

### Type Characteristics

| Type | Corresponding Attribute Bonus | Typical Abilities | Adjacent Type Efficiency | Diagonal Type Efficiency |
|------|:---:|------|:---:|:---:|
| **Enhancement** | Constitution +2 | Strengthen self or objects | 80% | 60% |
| **Transmutation** | Dexterity +2 | Change the nature of Nen (shape/property) | 80% | 60% |
| **Emission** | Perception +2 | Emit Nen outside the body and sustain it | 80% | 60% |
| **Conjuration** | Intelligence +2 | Materialize Nen into matter | 80% | 60% |
| **Manipulation** | Willpower +2 | Control matter or living things | 80% | 60% |
| **Specialization** | Charisma +2 | Special abilities outside the other five types | 80% | 80% |

> **Cross-Type Use Rule:** When using a non-main-type Nen ability, Spirit Points (SP) cost × efficiency reciprocal (e.g., Enhancement using Conjuration: 1/0.6 = 1.67× cost)

### Water Divination Determination (d100)

| d100 | Effect | Corresponding Type |
|:---:|------|------|
| 1-20 | Water volume increases — water overflows | Enhancement |
| 21-38 | Taste of the water changes | Transmutation |
| 39-56 | Color of the water changes | Emission |
| 57-74 | Impurities / crystals appear in the water | Conjuration |
| 75-92 | The leaf moves on its own | Manipulation |
| 93-100 | A special phenomenon other than the above | Specialization |

> **Free-Choice Mode:** The Game Master (GM) may allow players to directly choose their main type (suited for groups with a clear character concept).

---

## 2-5 Nen Ability Design System (Restrictions & Pledges)

This is the core feature of the system. Players do not merely pick skills, but **design their own Nen abilities from scratch**.

### Design Process

```
1. Confirm main type → determine ability category
2. Define base effect (determine base SP cost)
3. Stack restrictions & pledges (gain BP)
4. Spend BP to enhance the ability (increase damage / range / duration / effect)
5. Calculate final SP cost
6. GM review
```

### Restriction Types and Binding Pledge points (BP) Gains

#### A. Conditional Restrictions (Usage Conditions)

| Condition | Binding Pledge points (BP) | Example |
|------|:---:|------|
| Requires specific posture / chant (1 round preparation) | +1 | Must press both palms together |
| Requires specific posture / chant (2+ rounds preparation) | +2 | Full spell chant |
| Requires a medium (common item) | +1 | Must hold cards / dice |
| Requires a medium (rare item) | +2 | Requires blood of a specific bloodline |
| Must be used at a specific time | +1 ~ +3 | On a full-moon night (+2) |
| Must be used at a specific place | +1 ~ +3 | Within own En range (+1) |
| Must meet a specific situation | +1 ~ +3 | After an ally falls (+2) |

#### B. Usage-Limit Restrictions

| Limit | Binding Pledge points (BP) | Example |
|------|:---:|------|
| 3 times per day | +1 | — |
| 1 time per day | +2 | — |
| Usable only once per same target | +2 | — |
| Self takes damage after use (minor) | +1 | Hit Points (HP) −2 after use |
| Self takes damage after use (severe) | +3 | Hit Points (HP) halved after use |
| Falls into negative status after use | +1 ~ +2 | Cannot use Nen for 1 round (+2) |
| Consumes special resource | +1 ~ +3 | Consume own blood (+1), consume lifespan (+3) |

#### C. Pledge (Risk Type)

| Pledge Content | Binding Pledge points (BP) |
|------|:---:|
| "If I break X, I will lose my Nen ability" | +3 |
| "If I fail, I suffer severe consequences" | +3 |
| "Ability has strict target limitations" (e.g., only against a specific group) | +2 |
| "Ability effect is tied to own state" | +1 ~ +2 |

#### D. Ability Cost

| Cost | Binding Pledge points (BP) |
|------|:---:|
| Cooldown of 1 day after use | +1 |
| Cooldown of 1 week after use | +2 |
| Cooldown of 1 month after use | +3 |
| Permanently lose the ability after use | +4 |

### Binding Pledge points (BP) Cost Table (Ability Enhancement)

| Enhancement Effect | Binding Pledge points (BP) Cost |
|------|:---:|
| Damage die +1d6 | 1 |
| Range: single target → 3m circle | 1 |
| Range: 3m → 10m circle | 2 |
| Duration: instant → 1 minute | 1 |
| Duration: 1 minute → 10 minutes | 2 |
| Effect check difficulty −2 | 1 |
| Ignore half of target's Nen Defense | 2 |
| Add secondary effect (Restrained / Slow / Poisoned, etc.) | 2 |
| Add powerful effect (instakill / absolute control / spatial teleport) | 4 |
| Affect +1 additional target simultaneously | 1 |
| Ability becomes unremovable / unresistable | 3 |
| Hide activation traces | 1 |

### Binding Pledge points (BP) Cap (by Growth Stage)

| Growth Stage | Binding Pledge points (BP) Cap | Description |
|---------|:---:|------|
| Rookie (creation) | 4 Binding Pledge points (BP) | Can design an ability with multiple light restrictions |
| Apprentice Hunter | 5 Binding Pledge points (BP) | Can make one moderate restriction |
| Licensed Hunter | 8 Binding Pledge points (BP) | Can make a major restriction |
| Professional Hunter | 12 Binding Pledge points (BP) | Can maintain multiple restrictions at once |
| Star Hunter | 15 Binding Pledge points (BP) | Comparable to Morel / Knov level |
| Legendary | 18+ Binding Pledge points (BP) | Chairman / Ging level |

---

## 2-6 Initial Four Major Techniques Setup

All starting characters automatically learn the following Four Major Techniques at Lv.1:

| Technique | Initial Level | Spirit Points (SP) Cost | Effect |
|------|:---:|------|------|
| **Ten** | Lv.1 | 1/round | Aura wraps the whole body; Nen Defense +2 |
| **Zetsu** | Lv.1 | 0 (but Nen techniques unusable) | Close aura nodes, hide aura; detection difficulty +5 |
| **Ren** | Lv.1 | 3/round | Emit large amounts of Nen; attack +3, Nen Defense +3 |
| **Hatsu** | Lv.1 | Per ability | Release one's unique Nen ability (custom) |

---

## 2-7 Hunter Domains

Choose one domain to gain its corresponding starting advantage:

| Domain | Attribute Bonus | Skill Bonus | Starting Money | Special Item |
|------|:---:|------|:---:|------|
| **Bounty Hunter** | Perception +1 | Tracking +2 | 8,000J | Bounty Hunter Manual (criminal intel network) |
| **Beast Hunter** | Intelligence +1 | Nen Knowledge +2 | 10,000J | Rare Creature Codex |
| **Gourmet Hunter** | Constitution +1 | Survival +2 | 12,000J | Special ingredient samples ×3 |
| **Ruins Hunter** | Intelligence +1 | Investigation +2 | 15,000J | Ancient ruins map |
| **Contract Hunter** | Charisma +1 | Persuasion +2 | 20,000J | High-tier commission channel contact |
| **Music Hunter** | Perception +1 | Perception +2 | 8,000J | Special instrument (usable as Nen medium) |
| **Blacklist Hunter** | Perception +1 | Stealth +2 | 6,000J | Target dossier (detailed intel on 3 targets) |
| **Lost Hunter** | Choose +1 | Choose +2 | 10,000J | Mysterious item (GM secret setup) |

### Domain Narrative Advancement Rules

Each domain gains advantage on checks in specific situations:
- **Bounty Hunter:** Advantage on Investigation checks when gathering target intel
- **Beast Hunter:** Advantage on Nen Knowledge checks when interacting with beasts or analyzing ecology
- **Gourmet Hunter:** Advantage on Survival checks when appraising ingredients or cooking
- **Ruins Hunter:** Advantage on Investigation checks when deciphering ancient text or disarming traps
- **Contract Hunter:** Advantage on Persuasion checks when first building trust with a client
- **Music Hunter:** Advantage on hearing-based Perception checks
- **Blacklist Hunter:** Advantage on Tracking checks when trailing a registered target
- **Lost Hunter:** Intuition checks (GM discretion) when facing the unknown

---

## 2-8 Equipment & Economy

### Jenny Currency System

| Amount | Purchasing Power Reference |
|------|------|
| 1 J | A bottle of mineral water |
| 100 J | An ordinary meal |
| 1,000 J | One night at a cheap inn |
| 10,000 J | An ordinary weapon |
| 1 million J | A used car |
| 100 million J | A mansion |
| 1 billion J | The Greed Island game |

### Melee Weapons

| Weapon | Damage | Attribute | Price | Rarity |
|------|:---:|------|:---:|:---:|
| Unarmed | 1d4 | Dexterity or Constitution | — | Common |
| Dagger | 1d6 | Dexterity | 500J | Common |
| Short Sword | 1d6 | Dexterity | 1,000J | Common |
| Longsword | 1d8 | Dexterity or Constitution | 3,000J | Common |
| Club | 1d6 | Constitution | 300J | Common |
| Battle Axe | 1d10 | Constitution | 5,000J | Uncommon |
| Whip | 1d4 | Dexterity | 1,500J | Common |
| Katana | 1d8 | Dexterity | 8,000J | Uncommon |
| Greatsword | 2d6 | Constitution | 10,000J | Rare |
| Nen-Edge Dagger | 1d6+1d4 Nen | Dexterity | 50,000J | Rare |

### Ranged Weapons

| Weapon | Damage | Range | Price |
|------|:---:|------|:---:|
| Throwing Knife | 1d4 | 3-15m | 300J |
| Short Bow | 1d6 | 16-50m | 2,000J |
| Long Bow | 1d8 | 16-50m | 5,000J |
| Pistol | 2d6 | 16-50m | 20,000J |
| Rifle | 2d8 | 51-200m | 50,000J |

### Armor

| Armor | Armor Class (AC) Bonus | Price | Special |
|------|:---:|:---:|------|
| Leather Armor | +1 | 2,000J | — |
| Anti-Blade Vest | +2 | 8,000J | −1 vs slashing damage |
| Reinforced Fiber Suit | +2 | 15,000J | Light, no Stealth disadvantage |
| Military Armor | +3 | 30,000J | Stealth disadvantage |
| Nen Protection Charm | Nen Defense +1 | 40,000J | Occupies accessory slot |

### Consumables

| Item | Effect | Price |
|------|------|:---:|
| First Aid Kit | Restore Hit Points (HP) 1d8+2 | 500J |
| Medical Kit | Restore Hit Points (HP) 2d8+4 | 1,500J |
| Spirit Points (SP) Recovery Potion (Small) | Restore Spirit Points (SP) 1d6 | 1,000J |
| Spirit Points (SP) Recovery Potion (Medium) | Restore Spirit Points (SP) 2d6 | 3,000J |
| Spirit Points (SP) Recovery Potion (Large) | Restore Spirit Points (SP) 3d6 | 8,000J |
| Antidote | Remove Poisoned status | 800J |
| Stimulant | Ignore Fatigue for 1 hour; 2 levels of Fatigue after it ends | 2,000J |
| Smoke Grenade | Create a 5m-radius smoke (heavy obscurement) | 500J |
| Flash Grenade | Targets within 10m must make Reflex Difficulty Class (DC) 15 or be blinded for 1 round | 1,000J |

---

## 2-9 Growth System

This game uses an **Experience Points (XP) point-buy system** (not level-based), which better fits the cultivation philosophy of the Hunter world.

### Growth Stages (GM Reference Benchmarks)

| Stage | Experience Points (XP) Range | Binding Pledge points (BP) Cap | Proficiency Points | Effective Level (EL) |
|------|:---:|:---:|:---:|:---:|
| **Rookie** | 0-15 Experience Points (XP) | 4 | 6-8 | 1-2 |
| **Apprentice Hunter** | 16-40 Experience Points (XP) | 5 | 10-12 | 3-5 |
| **Licensed Hunter** | 41-80 Experience Points (XP) | 8 | 14-16 | 6-9 |
| **Professional Hunter** | 81-150 Experience Points (XP) | 12 | 18-20 | 10-13 |
| **Star Hunter** | 151-250 Experience Points (XP) | 15 | 22-24 | 14-17 |
| **Legendary** | 251+ Experience Points (XP) | 18+ | 26-28 | 18+ |

### Gaining Experience

| Source | Experience Value |
|------|:---:|
| Combat victory (simple) | 1 Experience Point (XP) |
| Combat victory (hard) | 3-5 Experience Points (XP) |
| Solve a problem using a Nen ability | 1-3 Experience Points (XP) |
| Discover a new restriction & pledge usage | 2 Experience Points (XP) |
| Complete a Hunter commission | 2-5 Experience Points (XP) |
| Character story milestone | 3-10 Experience Points (XP) (GM decides) |
| Attendance reward | 1 Experience Point (XP) / session |

### Experience Points (XP) Cost Table

| Growth Item | Experience Points (XP) Cost |
|------|:---:|
| Attribute +1 | New attribute value × 3 Experience Points (XP) |
| Hit Points (HP) Max +5 | 8 Experience Points (XP) |
| Spirit Points (SP) Max +5 | 8 Experience Points (XP) |
| Learn new Advanced Application Technique Lv.1 | 5 Experience Points (XP) |
| Advanced Application Technique Lv.1→2 | New level × 3 Experience Points (XP) |
| Advanced Application Technique Lv.2→3 | New level × 3 Experience Points (XP) |
| Advanced Application Technique Lv.3→4 | New level × 3 Experience Points (XP) |
| Design a new Nen ability | 10 Experience Points (XP) + story trigger |
| Modify an existing Nen ability's restrictions | 5 Experience Points (XP) + Game Master (GM) review |
| Skill Proficient → Expert | 8 Experience Points (XP) |
| Skill Expert → Master | 12 Experience Points (XP) |

### Four Major Techniques Experience Points (XP) Cost

| Technique | Lv.1→2 | Lv.2→3 | Lv.3→4 |
|------|:---:|:---:|:---:|
| Ten | 6 Experience Points (XP) | 9 Experience Points (XP) | 12 Experience Points (XP) |
| Zetsu | 6 Experience Points (XP) | 9 Experience Points (XP) | 12 Experience Points (XP) |
| Ren | 8 Experience Points (XP) | 12 Experience Points (XP) | 16 Experience Points (XP) |
| Hatsu | 8 Experience Points (XP) | 12 Experience Points (XP) | 16 Experience Points (XP) |

---

# Chapter 3: Combat & Conflict

---

## 3-1 Combat Framework

### Round Structure (10 phases per round)

| Phase | Content |
|:---:|------|
| 1 | Initiative determination |
| 2 | Round start (ongoing effects trigger) |
| 3 | **Declare action** (lower Initiative declares first, simulating "reading ahead") |
| 4 | **SP allocation** (attack / defense / special three zones) |
| 5 | Execute action (higher Initiative acts first) |
| 6 | Defense reaction (dodge / contest / attack of opportunity) |
| 7 | Hit determination |
| 8 | Damage calculation |
| 9 | Status effect resolution |
| 10 | Round end |

### Initiative Rules

- **Initiative** = Dexterity Modifier + Perception Modifier
- Highest Initiative acts first
- On tie, higher Dexterity Modifier priority; if still tied, roll d20
- **Delay:** May voluntarily lower Initiative priority
- **Ready:** Declare "if X happens then do Y"; when X happens, execute Y as a reaction
- **Surprise round:** The undetected side gains a full round of first action

### Action Economy

| Action Type | Per Round | Spirit Points (SP) Cost | Description |
|------|:---:|------|------|
| **Standard action** | 1 time | — | Attack, Nen ability, use item |
| **Move action** | 1 time | 0 | Move = Dexterity value (meters) |
| **Minor action** | 1 time | Per action | Switch weapon, drink potion, brief dialogue |
| **Reaction** | 1 time | Per action | Attack of opportunity, dodge, readied action |
| **Free action** | Unlimited | 0 | Speak, release, expression |

### Reverse Declaration Order

- **Lower Initiative declares action first**; higher Initiative can strike later
- Cannot change after declaration (unless using "Ryu" for instant adjustment)
- This is a unique feature of Hunter combat — simulating "reading ahead" in battle

---

## 3-2 Hit & Damage

### Hit Formula

| Attack Type | Formula | Contest |
|------|------|:---:|
| Physical melee (precision) | d20 + Proficiency + Dexterity Modifier | Armor Class (AC) |
| Physical melee (strength) | d20 + Proficiency + Constitution Modifier | Armor Class (AC) |
| Physical ranged | d20 + Proficiency + Dexterity Modifier | Armor Class (AC) |
| Nen attack (direct) | d20 + Proficiency + Willpower Modifier | Armor Class (AC) |
| Nen attack (control) | d20 + Proficiency + Intelligence Modifier | Armor Class (AC) |

### Armor Class (AC)

```
AC = 10 + Dexterity Modifier + Nen Defense Bonus + Cover Bonus + Equipment Bonus
```

- Attacker's d20 + bonus ≥ target's Armor Class (AC) → hit
- Natural 20: always hits, critical hit (weapon damage die ×2)
- Natural 1: always misses

### Physical Damage

```
Physical Damage = Weapon base damage die + Attribute Modifier + Other bonuses − Target physical damage reduction
```

### Nen Attack Damage

```
Nen Attack Damage = Ability base damage die + Willpower Modifier + SP allocation bonus + BP enhancement − Target Nen Defense
```

- **Nen Defense vs physical attack:** Only provides an Armor Class (AC) bonus (no direct damage reduction)
- **Nen Defense vs Nen attack:** Directly subtracted from damage (e.g., Nen Defense 3 → −3 Nen damage)

### Damage Multipliers

| Situation | Multiplier |
|------|:---:|
| Critical hit (natural 20) | ×2 (weapon damage die portion) |
| Weak point attack | ×1.5 |
| Ko Lv.1-2 | ×3 |
| Ko Lv.3-4 | ×4 |
| Resistance | ×0.5 |
| Immunity | ×0 |

---

## 3-3 Movement & Distance

### Movement

```
Base Movement = Dexterity value (m)
```

| Dexterity | Movement | Example |
|:---:|:---:|------|
| 8 | 8m | Clumsy or injured |
| 10 | 10m | Ordinary person |
| 14 | 14m | Hunter level |
| 18+ | 18m+ | Top-tier physique |

### Distance Classification

| Distance | Range | Melee | Throw / Short-range Nen | Ranged / Emission |
|------|:---:|:---:|:---:|:---:|
| Melee | 0-2m | ✅ | Disadvantage | ❌ |
| Mid-range | 3-15m | ❌ | ✅ | ✅ |
| Long-range | 16-50m | ❌ | Disadvantage | ✅ |
| Extreme | 51-200m | ❌ | ❌ | Disadvantage |
| Beyond Sight | 200m+ | ❌ | ❌ | Special ability only |

### Special Movement

| Movement Type | Movement | Description |
|------|:---:|------|
| Climbing | ×0.5 | Requires Climb check |
| Swimming | ×0.5 | Requires Swim check |
| Stealth move | ×0.5 | Requires Stealth check |
| Nen acceleration | +5m | Spirit Points (SP) 1/round |
| Retreat action | Normal | Consumes a move action, safely leaves one enemy's melee range |

---

## 3-4 Four Major Techniques Combat Data

### Ten

| Level | Spirit Points (SP) | Nen Defense | Special |
|:---:|:---:|:---:|------|
| Lv.1 | 1/round | +2 | Detectable by Gyo / En |
| Lv.2 | 1/round | +3 | — |
| Lv.3 | 1/round | +4 | Can maintain Ten + Gyo simultaneously |
| Lv.4 | 1/round | +5 | Can combine with En |

### Zetsu

| Level | Spirit Points (SP) | Stealth Bonus | Special |
|:---:|:---:|:---:|------|
| Lv.1 | 0 | +5 | All Nen techniques unusable, defense drops to zero |
| Lv.2 | 0 | +7 | Spirit Points (SP) natural recovery +1/round |
| Lv.3 | 0 | +9 | Can freely switch Zetsu / non-Zetsu as an action |
| Lv.4 | 0 | +11 | Switching costs no action |

### Ren

| Level | Spirit Points (SP) | Attack Bonus | Defense Bonus | Special |
|:---:|:---:|:---:|:---:|------|
| Lv.1 | 3/round | +3 | +3 | Detectable at long range |
| Lv.2 | 3/round | +4 | +4 | — |
| Lv.3 | 2/round | +5 | +5 | Spirit Points (SP) cost −1 |
| Lv.4 | 2/round | +5 | +5 | Spirit Points (SP) cost −1, can combine with Hatsu |

### Hatsu

| Level | Effect |
|:---:|------|
| Lv.1 | Can design 1 Nen ability |
| Lv.2 | Nen ability Spirit Points (SP) cost −1 (minimum 1) |
| Lv.3 | Nen ability effect amount +50% or can design a 2nd Nen ability |
| Lv.4 | Can combine with other techniques |

---

## 3-5 Advanced Application Techniques

### Complete Data Table

| Technique | Spirit Points (SP) | Effect | Prerequisite | Action |
|------|:---:|------|------|:---:|
| **Gyo** | 1 | See Nen distribution and hidden Nen | Ten Lv.2 | Minor |
| **En** | 2+ | Expand Nen perception field (radius = Four Major Technique × 5m); stealth and Zetsu invalid within range | Ten Lv.3 + Ren Lv.2 | Standard |
| **In** | 2 | Hide one's own Nen, against Gyo detection | Zetsu Lv.2 | Minor |
| **Ko** | 5 (one-time) | Concentrate all Nen at one point; attack ×3-4 but other parts' defense drops to zero | Ren Lv.3 | Standard |
| **Ken** | 5/round | Maintain 50-60% Ren state over the whole body; balanced offense and defense | Ren Lv.2 + Ten Lv.2 | Standard |
| **Ryu** | 1/adjustment | Dynamically allocate SP across attack / defense / special three zones | Ken Lv.2 | Reaction |

### Advanced Application Technique Proficiency

| Level | Name | Effect |
|:---:|------|------|
| Lv.0 | Not Learned | Unusable |
| Lv.1 | Novice | Base effect |
| Lv.2 | Skilled | Cost −1 (minimum 1) |
| Lv.3 | Adept | Effect amount +50% |
| Lv.4 | Ultimate | Can combine with other techniques |

---

## 3-6 Spirit Point Allocation System (Ryu)

### Three-Zone Allocation Formula

Each round, declare the allocation ratio of SP across three zones (total 100%):

| Zone | Formula | Cap |
|------|------|:---:|
| Attack Zone (A%) | Attack Bonus = Ren Bonus × A% | 70% (Ren Lv.3+ can be 80%) |
| Defense Zone (D%) | Defense Bonus = Ren Bonus × D% | 70% (same as above) |
| Special Zone (S%) | Effect Multiplier = 1 + (Ren Bonus × S% ÷ 10) | 70% (same as above) |

**Minimum:** Any single zone at least 10%.

**Example — Ren Lv.3 (bonus +3), allocate A50% / D30% / S20%:**
- Attack Bonus = 3 × 0.5 = +1.5 (rounded down = +1)
- Defense Bonus = 3 × 0.3 = +0.9 (rounded down = +0)
- Special Multiplier = 1 + (3 × 0.2 ÷ 10) = 1.06

### Ryu Instant Adjustment

| Ryu Lv. | Adjustment Timing |
|:---:|------|
| Lv.1 | Allocate only at round start |
| Lv.2 | One micro-adjustment after a standard action (max 20% adjustment) |
| Lv.3 | Adjust at any time (maintain cap 20%) |
| Lv.4 | Adjust at any time without limit |

### Tactical Deception

A player may "declare" one allocation ratio (so the opponent hears it), but use a different allocation when actually acting on their own turn — provided they have sufficient Ryu proficiency. This recreates the core mechanic of Hunter combat: "mutually deceiving the SP configuration."

---

## 3-7 Status Effects

### Physical States

| Status | Effect | Removal Method |
|------|------|------|
| **Restrained** | Movement = 0, attack disadvantage | Constitution Difficulty Class (DC) 15 to break free |
| **Poisoned Lv.1** | 1d4 poison damage per round | Fortitude Difficulty Class (DC) 12 / Antidote |
| **Poisoned Lv.2** | 1d6 poison damage per round, disadvantage on all checks | Fortitude Difficulty Class (DC) 15 / Antidote |
| **Poisoned Lv.3** | 2d6 poison damage per round, disadvantage on all checks | Fortitude Difficulty Class (DC) 18 / Strong Antidote |
| **Paralyzed** | Cannot use standard action | Fortitude Difficulty Class (DC) 14 / re-roll at end of each round |
| **Bleeding** | 1d4 damage per round until bandaged | Medicine Difficulty Class (DC) 12 |
| **Fatigue Lv.1** | Movement −2 | Short rest |
| **Fatigue Lv.2** | Movement −4, disadvantage on all checks | Long rest |
| **Unconscious** | Lose consciousness, Hit Points (HP) below 0 | Restore Hit Points (HP) or death saving throw |

### Mental States

| Status | Effect | Removal Method |
|------|------|------|
| **Frightened Lv.1** | Attack disadvantage | Will Difficulty Class (DC) 12 |
| **Frightened Lv.2** | Cannot voluntarily approach the fear source, disadvantage on all checks | Will Difficulty Class (DC) 15 |
| **Frightened Lv.3** | Must use all movement to flee the fear source | Will Difficulty Class (DC) 18 |
| **Confused** | Attack random target (including allies) | Will Difficulty Class (DC) 14 |
| **Charmed** | Cannot attack the charm source, disadvantage on checks against it | Will Difficulty Class (DC) 15 |

### Nen Ability States

| Status | Effect |
|------|------|
| **Nen Seal** | Cannot use any Nen ability; Ten / Zetsu / Ren / Hatsu all unusable |
| **Nen Interference** | Nen ability SP cost ×2, effect halved |
| **Nen Mark** | Caster can track location, no distance limit |
| **Nen Drain** | Spirit Points (SP) −1d6 per round; caster recovers equal Spirit Points (SP) |
| **Forced Zetsu** | Equivalent to "Zetsu" state, and cannot be self-removed |

---

## 3-8 Spirit Points (SP) Cost Formula

### Base SP Tiers

| Tier | Base Spirit Points (SP) | Example Ability |
|:---:|:---:|------|
| Tiny | 1 | Gyo, instant Nen Sense perception |
| Small | 2 | In, Nen bullet (single-target minor damage) |
| Medium | 4 | En (radius 10m), Nen blade, Nen protection |
| Large | 6 | En (radius 30m), Emission beam |
| Huge | 10 | Ko concentrated attack, area Nen ability |
| Legendary | 15+ | Chairman-class Hundred-Type Guanyin, spatial teleport |

### Enhancement Multiplier Effect on SP

| Enhancement Type | SP Increase | Description |
|------|:---:|------|
| Damage +1 tier | +30% | 1d6→2d6, etc. |
| Range +1 tier | +30-50% | Single → 3m → 10m → larger |
| Duration +1 tier | +20-40% | Instant → 1min → 10min → 1hr |

### Restriction Discounts

| Restriction Category | SP Discount | Description |
|------|:---:|------|
| Type A (conditional) | −1 SP / Binding Pledge point (BP) | Each BP reduces 1 SP |
| Type B (limit) | −1.5 SP / Binding Pledge point (BP) | Each BP reduces 1.5 SP |
| Type C (pledge) | −2 SP / Binding Pledge point (BP) | Each BP reduces 2 SP |
| Type D (cost) | −1 SP / Binding Pledge point (BP) | Each BP reduces 1 SP |
| Minimum SP | 1 | No ability's final SP below 1 |

### SP Recovery

| State | Recovery Rate |
|------|:---:|
| During combat | 0 (unless using consumables) |
| Short rest (10 min) | Willpower Modifier + Four Major Technique level / hour |
| Long rest (8 hr sleep) | Full recovery |
| Zetsu state | Extra +1 Spirit Points (SP) / round |

---

## 3-9 Monster / Non-Player Character (NPC) Templates

### Challenge Rating (CR) and Experience Points (XP)

| Challenge Rating (CR) | Corresponding Growth Stage | Experience Points (XP) Reward |
|:---:|------|:---:|
| 1/4 | Rookie mook | 25 Experience Points (XP) |
| 1/2 | Rookie Boss | 50 Experience Points (XP) |
| 1 | Apprentice Hunter level | 100 Experience Points (XP) |
| 2-3 | Apprentice → Licensed level | 150-300 Experience Points (XP) |
| 4-5 | Licensed Hunter level | 400-500 Experience Points (XP) |
| 6-8 | Professional Hunter level | 600-900 Experience Points (XP) |
| 9-12 | Star Hunter level | 1200-1800 Experience Points (XP) |
| 13-15+ | Legendary | 2000+ Experience Points (XP) |

### Three-Tier Templates

| Tier | Challenge Rating (CR) Range | Hit Points (HP) Range | Main Attack | Spirit Points (SP) Range |
|------|:---:|:---:|------|:---:|
| Mook | 1/4 ~ 1 | 15-40 | 1d6 ~ 2d6 | 10-25 |
| Mid-tier | 2 ~ 5 | 40-90 | 2d6 ~ 3d6+ | 25-60 |
| Boss | 6 ~ 14+ | 90-250+ | 3d6+ ~ 6d6+ | 60-150+ |

### Boss Three-Phase Mechanic

| Phase | Trigger Condition | Behavior Change |
|------|------|------|
| **Probing** | Default | Use base abilities, test Player Character (PC) tactics |
| **Serious** | Hit Points (HP) 70% or round 3 | Begin using Nen abilities, upgrade attack patterns |
| **Limit** | Hit Points (HP) 30% or pledge triggered | Go all out, restriction effect doubled, may have self-destruct tendency |

---

## 3-10 Death & Grievous Wounds

### Death Saving Throw

When Hit Points (HP) drop to 0:
- At the start of each round, make a death saving throw: d20, ≥10 gains 1 success, <10 gains 1 failure
- **3 successes cumulative:** Stabilized (HP at 0 but no longer dying)
- **3 failures cumulative:** Dead
- **Natural 20:** Recover 1 Hit Points (HP), awaken
- **Natural 1:** Counts as 2 failures

### Grievous Wound Table (optional rule)

When taking a single hit exceeding half of max Hit Points (HP), roll d6:

| d6 | Grievous Wound | Effect |
|:---:|------|------|
| 1 | Severed Limb | That limb unusable, requires Nen ability or advanced medicine to recover |
| 2 | Internal Injury | Fortitude disadvantage, only recovers half Hit Points (HP) per long rest |
| 3 | Concussion | Intelligence and Perception check disadvantage for 24 hours |
| 4 | Aura Node Damage | Spirit Points (SP) max temporarily −10, recovers on long rest |
| 5 | Deep Scar | Charisma check may gain disadvantage or advantage (by situation) |
| 6 | Near-Death Experience | No permanent injury, but next Fear check automatically fails |

---

# Chapter 4: World & Narrative

---

## 4-1 Worldview Overview

### Three-Layer World Model

| Layer | Name | Content | Ordinary Person's Awareness |
|------|------|------|:---:|
| Surface | Everyday World | Modern civilized society, technology, nations, law | ✓ Fully aware |
| Middle | Hunter World | Hunter Association, Nen users, magical beasts, secret realms | ✗ Partially heard of |
| Deep | Dark Continent | Hyper-ancient civilization ruins, Five Calamities, unknown ecology | ✗ Completely unknown |

### Nen and Technology Coexist

- Nen does not replace technology — a phone is still more convenient than telepathy
- Technology does not deny Nen — X-rays cannot see hidden Nen
- The two intersect in specific fields: Nen-made tools, Nen-enhanced weapons, Nen ability research equipment

### Key Nodes in World History

| Era | Event |
|------|------|
| ~300 years ago | V5 established, signed the Dark Continent Silence Treaty |
| ~280 years ago | Hunter Association founded |
| ~50 years ago | Netero becomes the 12th Chairman |
| ~20 years ago | Kakin Kingdom withdraws from V5, reorganizes as V6 |
| Several years ago | Chimera Ant incident; Netero killed in battle |
| Now | New Chairman inaugurated, Dark Continent voyage plan launched |

---

## 4-2 Factions & Powers

### Six Major Powers

| Power | Nature | Core Stance |
|------|------|------|
| **Hunter Association** | World's largest Nen user organization | Maintain order, manage Hunters |
| **Phantom Troupe** | S-rank criminal syndicate | Anarchism, plunder what they desire |
| **Zoldyck Family** | Strongest assassin family | Absolute professionalism, highest bidder wins |
| **V5/V6** | International political system | Preserve status quo, conceal Nen and the Dark Continent |
| **Kakin Kingdom** | Emerging power | Expand influence, push Dark Continent exploration |
| **Mafia** | Underground economic network | Profit above all, gray-market dealings |

### Association Internal Factions

| Faction | Representative | Core Claim |
|------|------|------|
| Stabilist | Mizaistom (Ox) | Preserve existing order |
| Expansionist | Pariston (former · Rat) | Evolve through chaos |
| Reformist | Cheadle (Dog) | Reform Association institutions |
| Militant | Botobai (Tiger) | Strength above all |
| Neutralist | Gel (Ram) | Maintain balance |
| Dark Division | — | Handle affairs the Association "cannot appear involved in" |

---

## 4-3 Hunter License & Star Ratings

### License Permissions (formalized)

| Permission | Effect |
|------|------|
| Public facilities | 90% free transport and lodging |
| Restricted areas | Enter sealed zones without extra permit |
| Information access | Association intel database (limited by star rating) |
| Crime immunity | Minor-crime exemption (not abusable, can be revoked) |
| Commission brokerage | Accept paid missions via the Hunter website |
| Weapon carry | Legal weapon carry in most countries |
| Diplomatic immunity | Simplified customs for cross-border action |
| Emergency help | Can send emergency signal to the Association |
| Hunter-exclusive shops | Use Hunter-exclusive equipment and services |

### Star Rating Advancement

| Star Rating | Condition | New Permissions |
|:---:|------|------|
| ★ | Outstanding achievement in a field | Can recommend Hunter Exam candidates |
| ★★ | Multi-field achievement + disciple earns one star | Can join Association decision meetings |
| ★★★ | Legendary-level achievement | Earns "Great Hunter" title, influences Association policy |

---

## 4-4 Game Master (GM) Running Guide

### Character Creation Facilitation Points (30-60 min)

1. **Guide the backstory** — let players voice their character's motivation and bonds
2. **Assist allocation** — recommend allocation plans to beginners
3. **Water Divination ritual feel** — describe the change after the roll
4. **Nen ability design guidance** — ask "what do you want to do," not "what numbers do you want"
5. **Restriction rewards** — encourage players to limit themselves: "the more interesting your restriction, the stronger your ability"

### Togashi-style Narrative Style

- **Information asymmetry**: The Player Character (PC)'s perceived world ≠ the real world
- **Three layers of truth**: surface statement → internal intel → ultimate truth
- **Defeat ≠ end**: what is lost this round may become the turning point next round
- **Strategic space**: give Player Characters (PCs) sufficient information to make meaningful tactical choices
- **Moral gray**: no pure evil; every villain has an understandable reason

### Five-Dimension Nen Ability Review Standards

| Dimension | Evaluation Question |
|------|------|
| Type Rationality | Is the ability within that type's scope? |
| Restriction balance | Is the Binding Pledge points (BP) income/expense balanced? Is the cost truly limiting? |
| Combat fairness | Will it make other Player Characters (PCs) feel useless? |
| Narrative potential | Can this ability create interesting plot? |
| Weakness exists | Is there a clear weakness or limitation left? |

---

## 4-5 Module Framework

### Module 1: Hunter Exam (intro, 4-6 hours)

**Suited for:** Beginner guidance, tutorial group after character creation

| Scene | Content | Check Focus |
|:---:|------|------|
| 1 | Physical test — cross dangerous terrain | Athletics, Survival, Endurance |
| 2 | Intelligence stage — puzzles and intel gathering | Investigation, Tactics |
| 3 | Teamwork — a test passable only through cooperation | Social skills |
| 4 | Live elimination — battle other examinees | Combat system tutorial |
| 5 | Final interview — the Chairman's persuasion / test | Free player expression |

**Loot:** Hunter License, basic equipment set, 1,000J

---

### Module 2: Heavens Arena (combat, repeatable)

**Suited for:** Repeatable combat module

Five-tier system:
- **Floors 10-50:** Novice fighters (CR 1/4 ~ 1/2)
- **Floors 50-100:** Amateur fighters (CR 1 ~ 2)
- **Floors 100-150:** Professional fighters (CR 3 ~ 5)
- **Floors 150-200:** Nen user zone (CR 6 ~ 8)
- **Floors 200+:** Top-tier experts (CR 9+)

**Rival system:** The Game Master (GM) designs 3-5 rivals who clash with Player Characters (PCs) at different floors, forming a long-term story line.

---

### Module 3: Yorknew Auction (infiltration / multi-thread, 6-8 hours)

**Suited for:** Intermediate group, tests social and infiltration abilities

Multi-thread mission design — five powers act simultaneously:
1. **Auction organizers** — escort mission
2. **Phantom Troupe** — raid plan
3. **Mafia** — intel trading
4. **Zoldyck** — hired third party
5. **Player Characters (PCs)** — their own objective

**Core experience:** Information war, faction choice, the climax of intersecting threads.

---

### Module 4: Dangerous Beast Subjugation (high difficulty, 8-12 hours)

**Suited for:** Advanced group, Chimera Ant arc style

| Phase | Content | Duration |
|:---:|------|:---:|
| Preparation | Intel gathering, equipment purchase, team plan | 2hr |
| March | Cross the target's territory | 2hr |
| Subjugation loop | Encounter → Combat → Retreat → Re-prepare | 4-6hr |
| Final battle | Boss three-phase combat | 2hr |

**Creature design template:** See the Challenge Rating (CR) framework and Boss phase mechanic in Combat System section 3-9.

---

## 4-6 Original Expansions

### Dark Continent Regions

| Region | Ecological Threat | Unique Treasure |
|------|------|------|
| **Crystallized Wasteland** | Crystallization syndrome (spreads on contact with biological tissue), memory crystal storm | Memory crystal (reveals past Nen records) |
| **Tear Sea** | Emotion materialization (sorrow → weight, anger → high heat), ancient ruin guardians | Emotion crystal, hyper-ancient tech relic |
| **Inverted Forest** | Gravity-flip zone, zenith predators, upside-down plants | Anti-gravity ore, floating wood |

### Original Hunter Domains

| Domain | Attribute | Skill Bonus | Core Gameplay |
|------|:---:|------|------|
| **Network Hunter** | Intelligence +1 | Investigation +2 | Digital intel war, dark-web infiltration, AI Nen-tool control |
| **Psychology Hunter** | Willpower +1 | Insight +2 | Psychological profiling, Nen-pressure therapy, memory probe |
| **Boundary Hunter** | Constitution +1 | Survival +2 | Dark Continent frontier exploration, unknown ecology recording |

### Nen Beast System Framework

| Nen Beast Type | Base Attributes | Maintain Spirit Points (SP) | Special |
|------|:---:|:---:|------|
| Scout | Hit Points (HP) 10, Armor Class (AC) 12 | 1/round | Shared senses |
| Combat | Hit Points (HP) 30, Armor Class (AC) 14 | 3/round | Independent attack (1d6 + controller's Willpower Modifier) |
| Support | Hit Points (HP) 20, Armor Class (AC) 12 | 2/round | Provides specific skill advantage |
| Composite | Multiple units | 5/round | Combines attack, defense, and scout functions |

---

# Appendix

---

## Appendix A: Quick Reference Tables

### Combat Round Quick Reference

| Step | Action |
|:---:|------|
| 1 | Initiative (d20 + Dexterity Modifier + Perception Modifier) |
| 2 | Declare action (lower Initiative declares first) |
| 3 | SP allocation (attack / defense / special three zones, total 100%) |
| 4 | Execute action |
| 5 | Hit determination (d20 + bonus vs Armor Class (AC)) |
| 6 | Damage calculation |
| 7 | Status resolution |

### Armor Class (AC) Composition

```
10 + Dexterity Modifier + Nen Defense + Cover + Equipment
```

### Difficulty Class (DC) Quick Reference

| Difficulty Class (DC) | Difficulty |
|:---:|------|
| 5-8 | Simple |
| 10-12 | Daily challenge |
| 15 | Standard challenge (50% success baseline) |
| 18-20 | Hard |
| 22-25 | Expert |
| 28-30 | Legendary |

### Spirit Points (SP) Recovery Quick Reference

| State | Recovery |
|------|:---:|
| During combat | 0 (unless consumables) |
| Short rest (10 min) | Willpower Modifier + Four Major Technique Lv |
| Long rest (8 hr) | Full recovery |

---

## Appendix B: Glossary

| Term | Category | Abbreviation |
|------|----------|--------------|
| Constitution | Core Attribute | CON |
| Dexterity | Core Attribute | DEX |
| Perception | Core Attribute | PER |
| Intelligence | Core Attribute | INT |
| Willpower | Core Attribute | WIL |
| Charisma | Core Attribute | CHA |
| Hit Points | Derived Stat | HP |
| Spirit Points | Derived Stat | SP |
| Armor Class | Derived Stat | AC |
| Nen Defense | Derived Stat | ND |
| Difficulty Class | Check | DC |
| Binding Pledge points | Resource | BP |
| Advantage / Disadvantage | Modifier | ADV / DIS |
| Challenge Rating | Monster | CR |
| Effective Level | Progression | EL |
| Ten / Zetsu / Ren / Hatsu | Four Major Techniques | — |
| Gyo / En / In / Ko / Ken / Ryu | Advanced Application Techniques | — |

---

## Appendix C: Character Sheet Template

```
╔══════════════════════════════════════════════╗
║        Hunter × Hunter TRPG Rulebook         ║
║              CHARACTER SHEET                  ║
╠══════════════════════════════════════════════╣
║ Name: _____________   Nen Type: _________     ║
║ Domain: ___________   Growth Stage: _______   ║
║ Total XP: ________   BP Cap: ___________      ║
╠══════════════════════════════════════════════╣
║           CORE ATTRIBUTES                     ║
║  Constitution (CON): ___ (Mod: ___)           ║
║  Dexterity (DEX):    ___ (Mod: ___)           ║
║  Perception (PER):   ___ (Mod: ___)           ║
║  Intelligence (INT): ___ (Mod: ___)           ║
║  Willpower (WIL):    ___ (Mod: ___)           ║
║  Charisma (CHA):     ___ (Mod: ___)           ║
╠══════════════════════════════════════════════╣
║           DERIVED ATTRIBUTES                  ║
║  HP: ____ / ____        SP: ____ / ____       ║
║  AC: ______             Initiative: ______    ║
║  Nen Defense: ______                           ║
╠══════════════════════════════════════════════╣
║           FOUR MAJOR TECHNIQUES               ║
║  Ten: Lv.__   Zetsu: Lv.__   Ren: Lv.__       ║
║  Hatsu: Lv.__                                ║
║  Advanced Application Techniques:             ║
║  Gyo: Lv.__   En: Lv.__   In: Lv.__           ║
║  Ko: Lv.__   Ken: Lv.__   Ryu: Lv.__          ║
╠══════════════════════════════════════════════╣
║           SKILL PROFICIENCY                   ║
║  □ Endurance   □ Survival    □ Athletics      ║
║  □ Stealth     □ Acrobatics  □ Sleight of Hand □ Marksmanship ║
║  □ Perception  □ Tracking    □ Insight    □ Nen Sense ║
║  □ Nen Knowledge □ Investigation □ Medicine □ Tactics ║
║  □ Nen Control □ Concentration □ Courage  □ Oath ║
║  □ Persuasion  □ Deception   □ Intimidation □ Leadership ║
╠══════════════════════════════════════════════╣
║           NEN ABILITY                         ║
║  ┌────────────────────────────────────────┐  ║
║  │ Ability Name:                          │  ║
║  │ Nen Type:         SP Cost:            │  ║
║  │ Base Effect:                            │  ║
║  │ Restrictions & Pledges (BP gained):     │  ║
║  │ BP Enhancements (BP spent):             │  ║
║  │ BP Balance: ____ / ____                 │  ║
║  └────────────────────────────────────────┘  ║
╠══════════════════════════════════════════════╣
║           EQUIPMENT & ITEMS                   ║
║  Weapon: _________   Damage: ______           ║
║  Armor:  _________   AC Bonus: ___            ║
║  Money:  ____________ J                        ║
║  Items: ______________________________________ ║
╠══════════════════════════════════════════════╣
║           BACKGROUND                          ║
║  Origin: ________   Motivation: ________      ║
║  Surface Trait: ____   Deep Trait: ____       ║
║  Core Bond: __________________________________ ║
╚══════════════════════════════════════════════╝
```

---

## Appendix D: Design Team

This rulebook was collaboratively completed by four designers from the "Tabletop Rules Studio":

| Designer | Role | Responsible Area |
|------|------|------|
| Bi Dou'an | Core Mechanics Designer | Chapter 1: Core Rules |
| Ke Jiaoling | Character System Designer | Chapter 2: Character Creation |
| Zhan Zhige | Combat System Designer | Chapter 3: Combat & Conflict |
| Jing Shiwen | Worldview & Narrative Designer | Chapter 4: World & Narrative |

**Lead:** Cheng Guiyao — requirements analysis, team coordination, cross-review, rulebook compilation.

---

> *"The deeper you restrict yourself, the closer you come to the essence of Nen."*
> *— Hunter world proverb*

> **Version History**
> - v1.0 (2026-06-21): First complete edition of the rulebook. Based on requirements spec v0.1; four designers worked in parallel, then compiled after cross-review and unified revision.
