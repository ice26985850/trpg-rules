# Hunter × Hunter TRPG Player Handbook

> **Version:** v1.0
> **Code name:** hunter-trpg
> **Audience:** Players (PC)
> **Core Theme:** Based on the world of Yoshihiro Togashi's *HUNTER×HUNTER*, featuring player-created Nen abilities × a Restrictions & Pledges balance system.

> 📘 **Game Masters (GM): please refer to the *Hunter × Hunter TRPG Game Master (GM) Handbook***, which contains the worldview setting, factions and powers, module framework, and Monster / NPC templates.

---

## Table of Contents

- [Chapter 1: Core Rules](#chapter-1-core-rules)
- [Chapter 2: Character Creation](#chapter-2-character-creation)
- [Chapter 3: Combat & Conflict](#chapter-3-combat--conflict)
- [Appendix](#appendix)

---

# Chapter 1: Core Rules

This chapter defines the game's dice system, attribute framework, skill checks, and difficulty ladder — the foundation for resolving all in-game actions.

---

## 1-1 Dice System

This game uses the **d20 core system**: the success or failure of all actions is determined by a single 20-sided die.

**Basic Formula:**
```
d20 + Attribute Modifier + Proficiency Bonus ≥ DC (Difficulty Class) → Success
```

---

## 1-2 Six Core Attributes

All characters are defined by six core attributes, with values ranging from 1 to 20 (the normal human range is 8 to 18).

| Attribute | Abbrev. | Meaning | Primary Influence |
|------|------|------|----------|
| Constitution | Constitution (CON) | Physical strength, stamina, vitality | Hit Points (HP), carrying capacity, Enhancement aptitude |
| Dexterity | Dexterity (DEX) | Speed, reflexes, agility | Armor Class (AC), Initiative, Transmutation aptitude |
| Perception | Perception (PER) | Observation, intuition, sensory acuity | Perception, Tracking, Emission aptitude |
| Intelligence | Intelligence (INT) | Analysis, memory, strategy | Tactics, Nen Knowledge, Conjuration aptitude |
| Willpower | Willpower (WIL) | Mental strength, resolve, composure | Spirit Points (SP), Nen Defense, Manipulation aptitude |
| Charisma | Charisma (CHA) | Leadership, persuasion, presence | Persuasion, Intimidation, Specialization aptitude |

### Attribute Value → Modifier Mapping

```
Modifier = ⌊(Attribute Value − 10) / 2⌋ (round down)
```

| Attribute Value | Modifier | Description |
|:---:|:---:|------|
| 1 | −5 | Barely able to care for oneself |
| 2-3 | −4 | Extremely frail |
| 4-5 | −3 | Noticeable deficiency |
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

| Attribute | Formula | Use |
|------|------|------|
| **Hit Points (HP)** | Constitution × 5 + 10 | Absorbs physical damage |
| **Spirit Points (SP)** | Willpower × 5 + 10 | Fuel for Nen abilities |
| **Armor Class (AC)** | 10 + Dexterity Modifier + Nen Defense bonus | Threshold to be hit by physical attacks |
| **Initiative** | Dexterity Modifier + Perception Modifier | Determines combat action order |
| **Nen Defense (ND)** | Willpower Modifier + Four Major Techniques proficiency bonus | Direct damage reduction against Nen attacks |

### Four Major Techniques Proficiency and Nen Defense Bonus

| Four Major Techniques Level | Nen Defense Bonus | Nen Type Check Bonus |
|:---:|:---:|:---:|
| Lv.0 (Unawakened) | +0 | +0 |
| Lv.1 (Novice) | +1 | +1 |
| Lv.2 (Skilled) | +2 | +2 |
| Lv.3 (Adept) | +3 | +3 |
| Lv.4 (Ultimate) | +4 | +4 |

---

## 1-4 Skill System

### Full Skill List

#### Constitution (CON)
| Skill | Use |
|------|------|
| **Endurance** | Resist fatigue, poison, extreme environments |
| **Survival** | Wilderness survival, foraging, tracking prey |
| **Athletics** | Climbing, swimming, jumping, running |
| **Melee (Strength)** | Heavy strikes, grappling, brute-force attacks — used for attack checks of strength-based melee |

#### Dexterity (DEX)
| Skill | Use |
|------|------|
| **Stealth** | Concealed movement, hiding, tailing |
| **Acrobatics** | Balance, tumbling, dodging traps |
| **Sleight of Hand** | Pickpocketing, lockpicking, fine manipulation |
| **Marksmanship** | Firearms, bows, thrown weapons |
| **Melee (Precision)** | Swordsmanship, assassination, quick thrusts — used for attack checks of precision melee |

#### Perception (PER)
| Skill | Use |
|------|------|
| **Perception** | Spot hidden objects, faint sounds |
| **Tracking** | Follow footprints, read scene clues |
| **Insight** | Read body language, judge lies |
| **Nen Sense** | Sense the aura of Nen, judge SP and type |

#### Intelligence (INT)
| Skill | Use |
|------|------|
| **Nen Knowledge** | Nen ability theory, knowledge of each type, restriction analysis |
| **Investigation** | Scene analysis, intelligence gathering, logical deduction |
| **Medicine** | First aid, dissection, medical applications of Nen |
| **Tactics** | Combat planning, enemy analysis, team coordination |
| **Nen Attack (Manipulation)** | Precise Nen attacks of Manipulation / Conjuration — used for attack checks of manipulation-type Nen attacks |

#### Willpower (WIL)
| Skill | Use |
|------|------|
| **Nen Control** | SP allocation (Ryu), emission and retraction of aura |
| **Concentration** | Resist interference, maintain Nen techniques, prolonged vigilance |
| **Courage** | Resist fear, intimidation, mental attacks |
| **Nen Attack (Direct)** | Direct Nen attacks of Emission / Enhancement — used for attack checks of direct-type Nen attacks |
| **Oath** | Establish and maintain restrictions and pledges |

#### Charisma (CHA)
| Skill | Use |
|------|------|
| **Persuasion** | Convince, bargain, build cooperation |
| **Deception** | Lie, disguise, mislead |
| **Intimidation** | Display intimidating power, extract confessions |
| **Leadership** | Inspire allies, command operations |

### Proficiency Levels

| Level | Bonus | Description |
|------|:---:|------|
| Unskilled | +0 | Anyone can attempt, relies on talent alone |
| Proficient | +2 | Formally trained |
| Expert | +4 | A professional in the field |
| Master | +6 | World-class level |

### Acquiring Proficiency Points

- **At character creation:** gain **6-8 Proficiency points**
- **Each growth-stage advancement:** +4 Proficiency points
- **Experience Points (XP) purchase (optional):** Proficient → Expert 8 XP, Expert → Master 12 XP

### Skill Check Formula

```
Skill Check = d20 + corresponding Attribute Modifier + Proficiency Bonus
```

**Example:** Gon (Perception 15, +2) uses "Tracking" (Proficient, +2) to trail a target. Rolls d20(13) + 2 + 2 = 17. The GM judges the rainy, muddy traces to be obvious, Difficulty Class (DC) 12 → **Success**.

---

## 1-5 Difficulty Ladder (DC)

| Difficulty Class (DC) | Difficulty | Hunter World Example |
|:---:|------|------|
| 5 | Trivial | Finding a bestseller in a library |
| 8 | Very Easy | Recognizing the Heavens Arena logo |
| 10 | Easy | Climbing a 2m wall |
| 12 | Slightly Easy | Noticing a tail in a crowd |
| **15** | **Medium (baseline)** | Hiding aura using "Zetsu"; identifying a Nen user's type |
| 18 | Hard | Allocating SP precisely using "Ryu" in combat |
| 20 | Very Hard | Using a Nen ability cross-type at 60% efficiency |
| 22 | Expert | Maintaining "En" at a 50m radius while fighting |
| 25 | Extremely Hard | Analyzing an opponent's restrictions and pledge in combat |
| 28 | Master | Passing Nen beast sentries with "Zetsu" unprepared |
| 30 | Legendary | Chairman-level — a fist moving faster than sound |

> **Difficulty Class (DC) 15 baseline calibration:** Attribute 14 (+2) + Proficiency (+2) = 50% success rate.

---

## 1-6 Check Rules

### Standard Check

```
d20 + Attribute Modifier + Proficiency Bonus + other bonuses ≥ DC → Success
```

**Natural 20 (critical success):** automatic success; the GM grants an extra benefit.
**Natural 1 (critical failure):** automatic failure, possibly with a minor side effect.

### Contest Check

```
Active side: d20 + Attribute Modifier + Proficiency Bonus
Passive side: d20 + Attribute Modifier + Proficiency Bonus
Active side ≥ Passive side → Active side wins
```

On a tie, the side with the higher Attribute Modifier wins; if still tied, the status quo is maintained.

### Group Check

- The helper must have the relevant skill at **Proficient** level or above
- The helper rolls a Difficulty Class (DC) 10 check; on success the main actor gains +2 (not stackable)
- When multiple people attempt simultaneously: if at least half succeed, the group succeeds

### Advantage / Disadvantage

- **Advantage:** roll 2d20, take the higher
- **Disadvantage:** roll 2d20, take the lower
- Advantage and Disadvantage are mutually exclusive; when one applies, ignore other situational bonuses

| Base Success Rate | With Advantage | With Disadvantage | Equivalent Bonus |
|:---:|:---:|:---:|:---:|
| 30% | 51.0% | 9.0% | ≈ +4.2 |
| 50% | 75.0% | 25.0% | ≈ +5.0 |
| 65% | 87.8% | 42.3% | ≈ +4.6 |

---

## 1-7 Saving Throws

When a special effect does not target Armor Class (AC), the target makes a saving throw:

```
Saving Throw = d20 + corresponding Attribute Modifier + Proficiency Bonus (if proficient in that save)
```

| Save | Attribute | Common Use |
|------|------|----------|
| Fortitude Save | Constitution | Resist poison, disease, physical restraint |
| Reflex Save | Dexterity | Dodge area attacks, traps |
| Will Save | Willpower | Resist mental control, fear, Nen pressure |

---

## 1-8 Environmental Damage & Special Rules

### Falling Damage

| Fall Height | Damage | Save |
|:---:|:---:|:---:|
| Under 3m | 1d6 bludgeoning | — |
| 3-6m | 2d6 bludgeoning | Acrobatics DC 12 halves |
| 6-15m | 4d6 bludgeoning | Acrobatics DC 15 halves |
| 15-30m | 6d6 bludgeoning | Acrobatics DC 18 halves |
| 30m+ | 10d6 bludgeoning | Cannot be reduced |

- **Intentional jump:** Acrobatics DC 15 success treats it as one tier lower
- **Nen cushion:** while using Ten/Ken, Nen Defense can offset falling damage (each point of Nen Defense −1 damage)

### Drowning & Suffocation

| State | Effect |
|------|------|
| Holding breath | Constitution × 2 rounds (about 12-40 seconds), may act normally |
| Oxygen deprivation | After breath holds out, Fortitude DC 12 each round; failure deals 1d4 damage and imposes disadvantage on all checks |
| Unconscious | When Hit Points (HP) reach 0, begin drowning death save (same as death saving throw rules) |

### Extreme Environments

| Environment | Effect | Save |
|------|------|:---:|
| Extreme Cold | Every 10 minutes requires Fortitude DC 12; failure grants Fatigue Lv.1 | Fortitude +1/attempt |
| Extreme Heat | Every 10 minutes requires Fortitude DC 12; failure increases SP consumption by +1 | Fortitude +1/attempt |
| High-Pressure Nen Field | SP −1d4 every 10 minutes | Willpower DC 15 to resist |

### Carrying Capacity

| Load Level | Weight | Effect |
|:---:|------|------|
| Light | ≤ Constitution × 5 kg | Normal |
| Medium | ≤ Constitution × 10 kg | Movement −2, disadvantage on Stealth/Acrobatics |
| Heavy | ≤ Constitution × 15 kg | Movement halved, disadvantage on all physical checks |
| Overweight | > Constitution × 15 kg | Cannot move |

> **Example:** Constitution 12 → Light ≤ 60kg, Medium ≤ 120kg, Heavy ≤ 180kg.

---

## 2-1 Seven Steps of Character Creation

| Step | Content | Reference |
|:---:|------|:---:|
| 1 | Background setup (origin, motivation, personality) | 2-2 |
| 2 | Attribute allocation (27-point point-buy) | 2-3 |
| 3 | Water Divination (determine main Nen type) | 2-4 |
| 4 | Design Nen ability (Binding Pledge points (BP) system) | 2-5 |
| 5 | Initial Four Major Techniques | 2-6 |
| 6 | Choose Hunter Domain | 2-7 |
| 7 | Equipment & resources | 2-8 |

---

## 2-2 Background Setup

### Origin (d10)

| d10 | Origin |
|:---:|------|
| 1 | Ordinary family — no special background; set out on the Hunter path by chance |
| 2 | Hunter family — parents or elders are Hunters |
| 3 | Slums / streets — learned various skills to survive |
| 4 | Wealthy scion — rich in resources but burdened by family expectations |
| 5 | Remote region — from an underdeveloped but simple homeland |
| 6 | Criminal organization — raised in the Mafia |
| 7 | Research institute — from a lab or academy |
| 8 | Wanderer — no fixed home, roaming the world |
| 9 | Secret society — member of a hidden organization |
| 10 | Otherworld — from the fringes of the Dark Continent or a special environment |

### Motivation (d12)

| d12 | Reason for becoming a Hunter |
|:---:|------|
| 1 | Search for someone (missing relative / mentor / enemy) |
| 2 | Pursuit of power |
| 3 | Protect what matters |
| 4 | Curiosity — want to witness the world's unknowns firsthand |
| 5 | Money and fame |
| 6 | Atonement — seek redemption for past mistakes |
| 7 | Legacy — inherit someone's will |
| 8 | Freedom — the Hunter License is the ultimate pass |
| 9 | Revenge |
| 10 | Prove oneself — to someone or to the world |
| 11 | No specific purpose — go with the flow |
| 12 | Destiny — feel guided by some force |

---

## 2-3 Attribute Allocation

### 27-Point Point-Buy Method

- All attributes start at a base value of **8**
- The player has **27 attribute points**
- A single attribute can be raised at most to **15** (cap during allocation)

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

| Plan | Attribute Spread | Suited For |
|------|---------|------|
| Balanced | 13, 13, 13, 12, 12, 12 | Beginners, unsure of direction |
| Twin-Peak | 15, 15, 12, 10, 8, 8 | Specialize in two fields |
| Polarized Main | 15, 14, 13, 10, 10, 8 | Clear main-attribute build |
| Tri-Dimensional | 14, 14, 13, 12, 10, 8 | Flexible all-rounder |
| Social Specialist | 15, 12, 12, 10, 10, 14 | Charisma-type character |

### Post-Allocation Bonuses

1. **Nen type bonus** (after Water Divination): +2 to the main type's corresponding attribute
2. **Hunter Domain bonus** (after choosing domain): +1 to the domain's corresponding attribute

The final single-attribute cap is **17** (15 + 2); the starting modifier can reach at most +3.

---

## 2-4 Water Divination: Nen Type Determination

### Six Types

```
                    Enhancement
                        |
        Transmutation -- + -- Emission
                        |
        Conjuration -- + -- Manipulation
                        |
                    Specialization
```

### Type Characteristics

| Type | Corresponding Attribute Bonus | Typical Ability | Adjacent Efficiency | Diagonal Efficiency |
|------|:---:|------|:---:|:---:|
| **Enhancement** | Constitution +2 | Strengthen self or objects | 80% | 60% |
| **Transmutation** | Dexterity +2 | Alter the nature of Nen (form/property) | 80% | 60% |
| **Emission** | Perception +2 | Emit Nen from the body and sustain it | 80% | 60% |
| **Conjuration** | Intelligence +2 | Materialize Nen into matter | 80% | 60% |
| **Manipulation** | Willpower +2 | Control matter or living things | 80% | 60% |
| **Specialization** | Charisma +2 | Special abilities outside the other five types | 80% | 80% |

> **Cross-type usage rule:** When using a non-main-type Nen ability, SP consumption × inverse of efficiency (e.g., Enhancement using Conjuration: 1/0.6 = 1.67×).

### Water Divination Determination (d100)

| d100 | Effect | Corresponding Type |
|:---:|------|------|
| 1-20 | Water volume increases — overflows | Enhancement |
| 21-38 | Taste of the water changes | Transmutation |
| 39-56 | Color of the water changes | Emission |
| 57-74 | Impurities / crystals appear in the water | Conjuration |
| 75-92 | The leaf moves on its own | Manipulation |
| 93-100 | A special phenomenon unlike any above | Specialization |

> **Free-choice mode:** The GM may allow players to directly choose their main type (suited for groups with a clear character concept).

---

## 2-5 Nen Ability Design System (Restrictions & Pledges)

This is the core feature of the system. Players do not merely pick skills — they **design their own Nen abilities from scratch**.

### Design Process

```
1. Confirm main type → determine ability category
2. Define base effect (determines base SP cost)
3. Stack restrictions and pledges (gain BP)
4. Spend BP to enhance the ability (add damage / range / duration / effect)
5. Calculate final SP cost
6. GM review
```

### Restriction Types and Binding Pledge points (BP) Yield

#### A. Conditional Restrictions

| Condition | Binding Pledge points (BP) | Example |
|------|:---:|------|
| Requires specific posture / chant (1 round prep) | +1 | Must press both palms together |
| Requires specific posture / chant (2+ rounds prep) | +2 | Full incantation of a spell |
| Requires a medium (common item) | +1 | Must hold cards / dice |
| Requires a medium (rare item) | +2 | Needs blood of a specific bloodline |
| Must be used at a specific time | +1 ~ +3 | Full moon night (+2) |
| Must be used at a specific place | +1 ~ +3 | Within one's own En range (+1) |
| Must meet a specific situation | +1 ~ +3 | After a teammate falls (+2) |

#### B. Usage-Limit Restrictions

| Limit | Binding Pledge points (BP) | Example |
|------|:---:|------|
| 3 times per day | +1 | — |
| Once per day | +2 | — |
| Only once per same target | +2 | — |
| Self takes damage after use (minor) | +1 | After use Hit Points (HP) −2 |
| Self takes damage after use (severe) | +3 | After use Hit Points (HP) halved |
| Falls into negative status after use | +1 ~ +2 | Cannot use Nen for 1 round (+2) |
| Consumes special resource | +1 ~ +3 | Consume own blood (+1), consume lifespan (+3) |

#### C. Pledge (Risk Type)

| Pledge Content | Binding Pledge points (BP) |
|------|:---:|
| "If I break X, I will lose my Nen ability" | +3 |
| "If I fail, I suffer severe consequences" | +3 |
| "Ability has strict target limitations" (e.g., only a specific group) | +2 |
| "Ability effect tied to own state" | +1 ~ +2 |

#### D. Ability Cost

| Cost | Binding Pledge points (BP) |
|------|:---:|
| Cooldown 1 day after use | +1 |
| Cooldown 1 week after use | +2 |
| Cooldown 1 month after use | +3 |
| Permanently lose the ability after use | +4 |

### Binding Pledge points (BP) Cost Table (Ability Enhancement)

| Enhancement Effect | Binding Pledge points (BP) Cost |
|------|:---:|
| Damage die +1d6 | 1 |
| Range: single target → 3m circle | 1 |
| Range: 3m → 10m circle | 2 |
| Duration: instant → 1 minute | 1 |
| Duration: 1 minute → 10 minutes | 2 |
| Effect check Difficulty −2 | 1 |
| Ignore half of target's Nen Defense | 2 |
| Add minor effect (Restrained / Slow / Poisoned, etc.) | 1 |
| Add powerful effect (instant death / absolute control / teleport) | 4 |
| Affect +1 additional target | 1 |
| Ability becomes unremovable / unresistable | 3 |
| Hide activation signs | 1 |

### Binding Pledge points (BP) Cap (by Growth Stage)

| Growth Stage | Binding Pledge points (BP) Cap | Description |
|---------|:---:|------|
| Rookie (creation) | 4 BP | Can design an ability with multiple light restrictions |
| Apprentice Hunter | 5 BP | Can set one moderate restriction |
| Licensed Hunter | 8 BP | Can set a major restriction |
| Professional Hunter | 12 BP | Can maintain multiple restrictions at once |
| Star Hunter | 15 BP | Comparable to Morel / Knov level |
| Legendary | 18+ BP | Chairman / Ging level |

---

## 2-6 Initial Four Major Techniques

All starting characters automatically learn the following Four Major Techniques at Lv.1:

| Technique | Initial Level | Spirit Points (SP) Cost | Effect |
|------|:---:|------|------|
| **Ten** | Lv.1 | 1/round | Aura wraps the body; Nen Defense +2 |
| **Zetsu** | Lv.1 | 0 (but Nen techniques unusable) | Close the aura nodes, hide aura, detection Difficulty +5 |
| **Ren** | Lv.1 | 3/round | Emit large amounts of Nen; attack +3, Nen Defense +3 |
| **Hatsu** | Lv.1 | per ability | Release one's unique Nen ability (custom) |

---

## 2-7 Hunter Domains

Choose one domain and gain its corresponding starting advantage:

| Domain | Attribute Bonus | Skill Bonus | Starting Money | Special Item |
|------|:---:|------|:---:|------|
| **Bounty Hunter** | Perception +1 | Tracking +2 | 8,000J | Bounty Hunter manual (criminal intel network) |
| **Beast Hunter** | Intelligence +1 | Nen Knowledge +2 | 10,000J | Rare creature codex |
| **Gourmet Hunter** | Constitution +1 | Survival +2 | 12,000J | Sample of special ingredients ×3 |
| **Ruins Hunter** | Intelligence +1 | Investigation +2 | 15,000J | Ancient ruins map |
| **Contract Hunter** | Charisma +1 | Persuasion +2 | 20,000J | Contact for high-tier commission channel |
| **Music Hunter** | Perception +1 | Perception +2 | 8,000J | Special instrument (can serve as Nen medium) |
| **Blacklist Hunter** | Perception +1 | Stealth +2 | 6,000J | Target dossier (detailed intel on 3 targets) |
| **Lost Hunter** | self-choice +1 | self-choice +2 | 10,000J | Mysterious item (GM secret setting) |

### Domain Story-Advancement Rules

Each domain gains advantage on checks in specific situations:
- **Bounty Hunter:** advantage on Investigation when gathering target intel
- **Beast Hunter:** advantage on Nen Knowledge when interacting with beasts or analyzing ecology
- **Gourmet Hunter:** advantage on Survival when appraising ingredients or cooking
- **Ruins Hunter:** advantage on Investigation when deciphering ancient script or disarming traps
- **Contract Hunter:** advantage on Persuasion when first building trust with a client
- **Music Hunter:** advantage on Perception checks oriented toward hearing
- **Blacklist Hunter:** advantage on Tracking when trailing a registered target
- **Lost Hunter:** intuition check when facing the unknown (GM discretion)

---

## 2-8 Equipment & Economy

> ▶ For data on Legendary and special items, see the *Item Codex*; for full stats of enemy characters (NPCs and bosses) see the *Monster Codex*.

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
| Reinforced Leather | +1 | 4,000J | No Stealth disadvantage |
| Chainmail | +2 | 5,000J | Stealth disadvantage |
| Anti-Blade Vest | +2 | 8,000J | −1 vs slashing damage |
| Reinforced Fiber Suit | +2 | 15,000J | Light, no Stealth disadvantage |
| Military Armor | +3 | 30,000J | Stealth disadvantage |
| Nen Ward | Nen Defense +1 | 40,000J | Occupies accessory slot |

### Consumables

| Item | Effect | Price |
|------|------|:---:|
| First Aid Kit | Restore Hit Points (HP) 1d8+2 | 500J |
| Medical Kit | Restore Hit Points (HP) 2d8+4 | 1,500J |
| SP Restore (S) | Restore Spirit Points (SP) 1d6 | 1,000J |
| SP Restore (M) | Restore Spirit Points (SP) 2d6 | 3,000J |
| SP Restore (L) | Restore Spirit Points (SP) 3d6 | 8,000J |
| Antidote | Cure Poisoned status | 800J |
| Stimulant | Ignore Fatigue for 1 hour; Fatigue Lv.2 after it ends | 2,000J |
| Smoke Grenade | Create a 5m-radius smoke (heavy obscurement) | 500J |
| Flashbang | Targets within 10m need Reflex DC 15 or blinded 1 round | 1,000J |

---

## 2-9 Growth System

This game uses an **Experience Points (XP) point-buy system** (not a level system), which better fits the cultivation philosophy of the Hunter world.

### Growth Stages

| Stage | Experience Points (XP) Range | Binding Pledge points (BP) Cap | Proficiency Points | Effective Level (EL) |
|------|:---:|:---:|:---:|:---:|
| **Rookie** | 0-15 XP | 4 | 6-8 | 1-2 |
| **Apprentice Hunter** | 16-40 XP | 5 | 10-12 | 3-5 |
| **Licensed Hunter** | 41-80 XP | 8 | 14-16 | 6-9 |
| **Professional Hunter** | 81-150 XP | 12 | 18-20 | 10-13 |
| **Star Hunter** | 151-250 XP | 15 | 22-24 | 14-17 |
| **Legendary** | 251+ XP | 18+ | 26-28 | 18+ |

### Stage Advancement Conditions

When the PC's accumulated Experience Points (XP) reach the next stage threshold, the GM checks the following conditions (advancement requires meeting at least one):

| Stage | Experience Points (XP) Threshold | Suggested Advancement Trigger |
|------|:---:|------|
| Rookie → Apprentice | 15 XP | Complete first Hunter commission OR complete an independent task after obtaining Hunter License |
| Apprentice → Licensed | 40 XP | Solo complete a commission with Challenge Rating (CR) ≥ PC average EL+2 OR learn an Advanced Application Technique Lv.2+ |
| Licensed → Professional | 80 XP | Complete an Association-recognized high-difficulty commission OR reach Lv.3 in any of the Four Major Techniques |
| Professional → Star | 150 XP | Obtain one-star Hunter qualification OR solo defeat an enemy with Challenge Rating (CR) ≥ 12 |
| Star → Legendary | 250 XP | Complete an action that changes the world order (GM discretion) OR make a major discovery in the Dark Continent |

### Gaining Experience

| Source | XP |
|------|:---:|
| Combat victory (easy) | 1 XP |
| Combat victory (hard) | 3-5 XP |
| Solve a problem using Nen ability | 1-3 XP |
| Discover new restriction/pledge usage | 2 XP |
| Complete Hunter commission | 2-5 XP |
| Character story milestone | 3-10 XP (GM decides, examples below) |
| Attendance bonus | 1 XP / session |

### Experience Points (XP) Milestone Examples (GM Reference)

| Experience Points (XP) | Milestone Type | Example |
|:---:|------|------|
| 3 XP | Character Growth | Overcome a personal weakness, confess a secret to a teammate |
| 5 XP | Plot Advancement | Uncover a major mystery, build trust with an important NPC |
| 7 XP | Major Decision | Make a meaningful sacrifice in a moral dilemma, abandon major interest to uphold principles |
| 10 XP | Story Turning Point | Complete a character's life goal, change the fate of a region |

### Experience Points (XP) Spending Table

| Growth Item | Experience Points (XP) Cost |
|------|:---:|
| Attribute +1 | New attribute value × 3 XP |
| Hit Points (HP) max +5 | 8 XP |
| Spirit Points (SP) max +5 | 8 XP |
| Learn new Advanced Application Technique Lv.1 | 5 XP |
| Advanced Application Technique Lv.1→2 | New level × 3 XP |
| Advanced Application Technique Lv.2→3 | New level × 3 XP |
| Advanced Application Technique Lv.3→4 | New level × 3 XP |
| Design new Nen ability | 10 XP + story trigger |
| Modify existing Nen ability's restrictions | 5 XP + GM review |
| Skill Proficient → Expert | 8 XP |
| Skill Expert → Master | 12 XP |

### Four Major Techniques XP Cost

| Technique | Lv.1→2 | Lv.2→3 | Lv.3→4 |
|------|:---:|:---:|:---:|
| Ten | 6 XP | 9 XP | 12 XP |
| Zetsu | 6 XP | 9 XP | 12 XP |
| Ren | 8 XP | 12 XP | 16 XP |
| Hatsu | 8 XP | 12 XP | 16 XP |

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
| 6 | Defensive reaction (dodge / contest / opportunity attack) |
| 7 | Hit determination |
| 8 | Damage calculation |
| 9 | Status effect resolution |
| 10 | Round end |

### Initiative Rules

- **Initiative** = Dexterity Modifier + Perception Modifier
- Highest Initiative acts first
- On tie, higher Dexterity Modifier priority; if still tied, roll d20
- **Delay:** voluntarily lower one's Initiative order
- **Ready:** declare "if X happens then do Y"; when X happens, execute Y as a reaction
- **Surprise round:** a side that is undetected gains a full round of first action

### Action Economy

| Action Type | Per Round | Spirit Points (SP) Cost | Description |
|------|:---:|------|------|
| **Standard Action** | 1 | — | Attack, Nen ability, use item |
| **Move Action** | 1 | 0 | Movement = Dexterity value (meters) |
| **Minor Action** | 1 | per action | Switch weapon, drink potion, brief talk |
| **Reaction** | 1 | per action | Opportunity attack, dodge, readied action |
| **Free Action** | unlimited | 0 | Speak, release, expression |

### Reverse Declaration Order

- **Lower Initiative declares action first**; higher Initiative can act later for advantage
- Declaration cannot be changed after (unless using Ryu's real-time adjustment)
- This is a unique feature of Hunter combat — simulating "reading ahead" in battle

---

## 3-2 Hit & Damage

### Hit Formula

**Attack Check = d20 + corresponding Attribute Modifier + corresponding combat Skill Proficiency Bonus**

| Attack Type | Corresponding Skill | Attribute Modifier | Defense |
|------|------|------|:---:|
| Physical melee (precision) | Melee (Precision) | Dexterity Modifier | Armor Class (AC) |
| Physical melee (strength) | Melee (Strength) | Constitution Modifier | Armor Class (AC) |
| Physical ranged | Marksmanship | Dexterity Modifier | Armor Class (AC) |
| Nen attack (direct) | Nen Attack (Direct) | Willpower Modifier | Armor Class (AC) |
| Nen attack (manipulation) | Nen Attack (Manipulation) | Intelligence Modifier | Armor Class (AC) |

> **Proficiency Bonus comes from skill proficiency level:** Unskilled +0 / Proficient +2 / Expert +4 / Master +6. If no Proficiency points were allocated to combat skills at creation, that attack uses +0.

### Armor Class (AC)

```
AC = 10 + Dexterity Modifier + Nen Defense Bonus + Cover Bonus + Equipment Bonus
```

- Attacker d20 + bonus ≥ target Armor Class (AC) → hit
- Natural 20: always hits, critical hit (weapon damage die ×2)
- Natural 1: always misses

### Physical Damage

```
Physical Damage = weapon base damage die + Attribute Modifier + other bonuses − target physical damage reduction
```

### Nen Attack Damage

```
Nen Attack Damage = ability base damage die + Willpower Modifier + SP allocation bonus + BP enhancement − target Nen Defense
```

- **Nen Defense vs physical attack:** only provides Armor Class (AC) bonus (no direct damage reduction)
- **Nen Defense vs Nen attack:** directly subtracted from damage (e.g., Nen Defense 3 → −3 Nen damage)

### Damage Multipliers

| Situation | Multiplier |
|------|:---:|
| Critical hit (natural 20) | ×2 (weapon damage die portion) |
| Weakness attack | ×1.5 |
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
| 18+ | 18m+ | Top-tier skill |

### Distance Classification

| Distance | Range | Melee | Throw / Short Nen | Ranged / Emission |
|------|:---:|:---:|:---:|:---:|
| Melee | 0-2m | ✅ | Disadvantage | ❌ |
| Mid | 3-15m | ❌ | ✅ | ✅ |
| Ranged | 16-50m | ❌ | Disadvantage | ✅ |
| Far | 51-200m | ❌ | ❌ | Disadvantage |
| Beyond Sight | 200m+ | ❌ | ❌ | Special ability only |

### Special Movement

| Movement Type | Movement | Description |
|------|:---:|------|
| Climbing | ×0.5 | Requires climb check |
| Swimming | ×0.5 | Requires swim check |
| Stealth move | ×0.5 | Requires Stealth check |
| Nen acceleration | +5m | SP 1/round |
| Retreat action | normal | Costs a Move Action, safely leave one enemy's melee range |

---

## 3-4 Four Major Techniques Combat Data

### Ten

| Level | Spirit Points (SP) | Nen Defense | Special |
|:---:|:---:|:---:|------|
| Lv.1 | 1/round | +2 | Detectable by Gyo/En |
| Lv.2 | 1/round | +3 | — |
| Lv.3 | 1/round | +4 | Can maintain Ten+Gyo simultaneously |
| Lv.4 | 1/round | +5 | Can combine with En |

### Zetsu

| Level | Spirit Points (SP) | Stealth Bonus | Special |
|:---:|:---:|:---:|------|
| Lv.1 | 0 | +5 | All Nen techniques unusable, defense drops to zero |
| Lv.2 | 0 | +7 | Non-combat SP natural recovery doubled |
| Lv.3 | 0 | +9 | Can freely switch Zetsu/non-Zetsu (but that round's attack/defense still calculated by pre-switch state) |
| Lv.4 | 0 | +11 | Switching costs no action |

### Ren

| Level | Spirit Points (SP) | Attack Bonus | Defense Bonus | Special |
|:---:|:---:|:---:|:---:|------|
| Lv.1 | 3/round | +3 | +3 | Detectable at long range |
| Lv.2 | 3/round | +4 | +4 | — |
| Lv.3 | 2/round | +5 | +5 | SP cost −1 |
| Lv.4 | 2/round | +5 | +5 | SP cost −1, can combine with Hatsu |

### Hatsu

| Level | Effect |
|:---:|------|
| Lv.1 | Can design 1 Nen ability |
| Lv.2 | Nen ability SP cost −1 (minimum 1) |
| Lv.3 | Choose one of: (1) all Nen abilities' **damage die +1 tier** (e.g., 1d6→1d8) (2) can design a 2nd Nen ability |
| Lv.4 | Can be used simultaneously with other Four Major Techniques or Advanced Application Techniques (combination techniques) |

> **Multi-ability rule after choosing (2) at Lv.3:** The two Nen abilities **share** the same Binding Pledge points (BP) cap. For example, a character with BP cap 8 can design one ability costing 5 BP and another costing 3 BP (total not exceeding 8). Each ability calculates its restriction income and enhancement spending independently.

---

## 3-5 Advanced Application Techniques

### Full Data Table

| Technique | Spirit Points (SP) | Effect | Prerequisite | Action |
|------|:---:|------|------|:---:|
| **Gyo** | 1 | See the distribution of Nen and hidden Nen | Ten Lv.2 | Minor |
| **En** | 2+ | Expand Nen perception field (radius = Four Major Techniques × 5m); invisibility and Zetsu invalid within range | Ten Lv.3 + Ren Lv.2 | Standard |
| **In** | 2 | Hide one's own Nen, resist Gyo detection | Zetsu Lv.2 | Minor |
| **Ko** | 5 (one-time) | Concentrate all Nen at one point; attack ×3-4 but other parts' defense drops to zero | Ren Lv.3 | Standard |
| **Ken** | 5/round | Maintain 50-60% Ren state over whole body; offense and defense combined | Ren Lv.2 + Ten Lv.2 | Standard |
| **Ryu** | 1/adjustment | Dynamically allocate SP across attack/defense/special three zones | Ken Lv.2 | Reaction |

### Advanced Application Technique Proficiency

| Level | Name | Effect |
|:---:|------|------|
| Lv.0 | Unskilled | Cannot use |
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
| Attack zone (A%) | Attack bonus = ⌊Ren bonus × (A% + 40%)⌋ | 70% (Ren Lv.3+ can be 80%) |
| Defense zone (D%) | Defense bonus = ⌊Ren bonus × (D% + 40%)⌋ | 70% (same as above) |
| Special zone (S%) | Effect multiplier = 1 + ((Ren bonus × (S% + 40%)) ÷ 10) | 70% (same as above) |

**Minimum:** any single zone at least 10%.

**Example — Ren Lv.3 (bonus +5), allocate A50% / D30% / S20%:**
- Attack bonus = ⌊5 × (0.5 + 0.4)⌋ = ⌊4.5⌋ = **+4** (if unallocated, +2)
- Defense bonus = ⌊5 × (0.3 + 0.4)⌋ = ⌊3.5⌋ = **+3** (if unallocated, +2)
- Special multiplier = 1 + ((5 × (0.2 + 0.4)) ÷ 10) = 1 + 0.3 = **1.30**

> **Design intent:** the +40% baseline ensures that even allocating the minimum 10%, you still get 50% of the Ren bonus effect (rather than near zero). The allocation difference varies from +2 to +7 — enough to make each round's allocation decision meaningful.

### Ryu Real-Time Adjustment

| Ryu Lv. | Adjustment Timing |
|:---:|------|
| Lv.1 | Allocate only at round start |
| Lv.2 | One micro-adjustment after a Standard Action (cap 20%) |
| Lv.3 | Adjust at any time (cap 20%) |
| Lv.4 | Adjust at any time without limit |

### Tactical Deception

A player may "declare" one allocation ratio (so the opponent hears it) but use a different allocation when actually acting on their turn — provided they have sufficient Ryu proficiency. This reproduces the core mechanic of Hunter combat where "parties deceive each other about SP configuration."

---

## 3-7 Status Effects

### Physical States

| Status | Effect | Removal |
|------|------|------|
| **Restrained** | Movement = 0, attack disadvantage | Constitution DC 15 to break free |
| **Poisoned Lv.1** | 1d4 poison damage per round | Fortitude DC 12 / Antidote |
| **Poisoned Lv.2** | 1d6 poison damage per round, disadvantage on all checks | Fortitude DC 15 / Antidote |
| **Poisoned Lv.3** | 2d6 poison damage per round, disadvantage on all checks | Fortitude DC 18 / Strong Antidote |
| **Paralyzed** | Cannot use Standard Action | Fortitude DC 14 / re-roll each round end |
| **Bleeding** | 1d4 damage per round until stanched | Medicine DC 12 |
| **Fatigue Lv.1** | Movement −2 | Short rest |
| **Fatigue Lv.2** | Movement −4, disadvantage on all checks | Long rest |
| **Unconscious** | Lose consciousness, Hit Points (HP) below 0 | Restore Hit Points (HP) or death saving throw |

### Mental States

| Status | Effect | Removal |
|------|------|------|
| **Frightened Lv.1** | Attack disadvantage | Willpower DC 12 |
| **Frightened Lv.2** | Cannot voluntarily approach fear source, disadvantage on all checks | Willpower DC 15 |
| **Frightened Lv.3** | Must use all movement to flee the fear source | Willpower DC 18 |
| **Confused** | Attack random target (including allies) | Willpower DC 14 |
| **Charmed** | Cannot attack charm source, disadvantage on checks against it | Willpower DC 15 |

### Nen Ability States

| Status | Effect |
|------|------|
| **Nen Seal** | Cannot use any Nen ability; Ten/Zetsu/Ren/Hatsu all unusable |
| **Nen Interference** | Nen ability SP cost ×2, effect halved |
| **Nen Mark** | Caster can track location, no distance limit |
| **Nen Drain** | SP −1d6 per round; caster recovers equal SP |
| **Forced Zetsu** | Equivalent to "Zetsu" state, and cannot be removed voluntarily |

---

## 3-8 Spirit Points (SP) Cost Formula

### Base SP Tiers

| Tier | Base Spirit Points (SP) | Example Ability |
|:---:|:---:|------|
| Tiny | 1 | Gyo, momentary Nen Sense |
| Small | 2 | In, Nen bullet (single-target minor damage) |
| Medium | 4 | En (radius 10m), Nen blade, Nen ward |
| Large | 6 | En (radius 30m), Emission beam |
| Huge | 10 | Ko concentrated attack, area Nen ability |
| Legendary | 15+ | Chairman-level Hundred-Type Guanyin, teleport |

### Enhancement Multiplier Effect on SP

| Enhancement Type | SP Increase | Description |
|------|:---:|------|
| Damage +1 tier | +30% | 1d6→2d6, etc. |
| Range +1 tier | +30-50% | single→3m→10m→larger |
| Duration +1 tier | +20-40% | instant→1min→10min→1hour |

### Restriction Discount

| Restriction Category | SP Discount | Description |
|------|:---:|------|
| A (conditional) | −1 SP / BP | Each BP reduces 1 SP |
| B (limit) | −1.5 SP / BP | Each BP reduces 1.5 SP |
| C (pledge) | −2 SP / BP | Each BP reduces 2 SP |
| D (cost) | −1 SP / BP | Each BP reduces 1 SP |
| Minimum SP | 1 | Any ability's final SP not below 1 |

### SP Recovery

| State | Recovery Rate |
|------|:---:|
| In combat | 0 (unless using consumables) |
| Short rest (10-min rest) | Restore Willpower Modifier + total Four Major Techniques levels in SP |
| Long rest (8-hour sleep) | Full recovery |
| Zetsu state (non-combat) | Extra +1 SP / 10 min |

> **Short rest example:** Willpower 14 (+2), Ten Lv.2 + Zetsu Lv.1 + Ren Lv.2 + Hatsu Lv.1 → total Four Major Techniques 6 levels. Short rest restores 2 + 6 = 8 SP. Given typical combat costs about 5-15 SP, one or two short rests replenish most of it.

---

## 3-9 Death & Grievous Wounds

### Death Saving Throw

When Hit Points (HP) drop to 0:
- At the start of each round, roll death save: d20, ≥10 gains 1 success, <10 gains 1 failure
- **3 successes cumulative:** stabilized (HP at 0 but no longer dying)
- **3 failures cumulative:** death
- **Natural 20:** recover 1 Hit Points (HP), awaken
- **Natural 1:** counts as 2 failures

### Grievous Wound Table (optional rule)

When taking a single hit exceeding half of max Hit Points (HP), roll d6:

| d6 | Grievous Wound | Effect |
|:---:|------|------|
| 1 | Severed limb | That limb unusable; requires Nen ability or advanced medicine to restore |
| 2 | Internal injury | Fortitude disadvantage, each long rest restores only half Hit Points (HP) |
| 3 | Concussion | Intelligence and Perception check disadvantage for 24 hours |
| 4 | Aura node damage | SP max temporarily −10, restored on long rest |
| 5 | Deep scar | Charisma check may gain disadvantage or advantage (by situation) |
| 6 | Near-death experience | No permanent damage, but next Fear check automatically fails |

---

# Appendix

---

## Appendix A: Quick Reference Tables

### Combat Round Quick Reference

| Step | Action |
|:---:|------|
| 1 | Initiative (d20 + Dexterity Modifier + Perception Modifier) |
| 2 | Declare action (lower Initiative declares first) |
| 3 | SP allocation (attack/defense/special three zones, total 100%) |
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
| 5-8 | Easy |
| 10-12 | Daily challenge |
| 15 | Standard challenge (50% success baseline) |
| 18-20 | Hard |
| 22-25 | Expert |
| 28-30 | Legendary |

### Spirit Points (SP) Recovery Quick Reference

| State | Recovery |
|------|:---:|
| In combat | 0 (unless consumables) |
| Short rest (10 min) | Willpower Modifier + total Four Major Techniques Lv |
| Long rest (8 hours) | Full recovery |

---

## Appendix B: Glossary

| Term | English | In-Text Form |
|------|------|:---:|
| Constitution | Constitution | Constitution (CON) |
| Dexterity | Dexterity | Dexterity (DEX) |
| Perception | Perception | Perception (PER) |
| Intelligence | Intelligence | Intelligence (INT) |
| Willpower | Willpower | Willpower (WIL) |
| Charisma | Charisma | Charisma (CHA) |
| Hit Points | Hit Points | Hit Points (HP) |
| Spirit Points | Spirit Points | Spirit Points (SP) |
| Armor Class | Armor Class | Armor Class (AC) |
| Nen Defense | Nen Defense | Nen Defense (ND) |
| Difficulty Class | Difficulty Class | Difficulty Class (DC) |
| Binding Pledge | Binding Pledge | Binding Pledge points (BP) |
| Advantage / Disadvantage | Advantage / Disadvantage | Advantage (ADV) / Disadvantage (DIS) |
| Challenge Rating | Challenge Rating | Challenge Rating (CR) |
| Effective Level | Effective Level | Effective Level (EL) |
| Ten / Zetsu / Ren / Hatsu | Ten / Zetsu / Ren / Hatsu | — |
| Gyo / En / In / Ko / Ken / Ryu | Gyo / En / In / Ko / Ken / Ryu | — |

---

## Appendix C: Character Sheet Template

```
╔══════════════════════════════════════════════╗
║           Hunter × Hunter TRPG               ║
║              CHARACTER SHEET                  ║
╠══════════════════════════════════════════════╣
║ Name:_____________   Type:_____________       ║
║ Domain:_____________  Growth Stage:_______    ║
║ Total XP:________   BP Cap:___________       ║
╠══════════════════════════════════════════════╣
║              CORE ATTRIBUTES                  ║
║  CON:___ (mod:___)                            ║
║  DEX:___ (mod:___)                            ║
║  PER:___ (mod:___)                            ║
║  INT:___ (mod:___)                            ║
║  WIL:___ (mod:___)                            ║
║  CHA:___ (mod:___)                            ║
╠══════════════════════════════════════════════╣
║              DERIVED STATS                    ║
║  HP:______ / ______     SP:______ / ______    ║
║  AC:______             Init:______            ║
║  Nen Defense:______                             ║
╠══════════════════════════════════════════════╣
║          FOUR MAJOR TECHNIQUES                ║
║  Ten:Lv.__  Zetsu:Lv.__  Ren:Lv.__           ║
║  Hatsu:Lv.__                                    ║
║  Advanced Application Techniques:               ║
║  Gyo:Lv.__  En:Lv.__  In:Lv.__                ║
║  Ko:Lv.__   Ken:Lv.__  Ryu:Lv.__              ║
╠══════════════════════════════════════════════╣
║           SKILL PROFICIENCY                   ║
║  Endurance  Survival  Athletics  Melee(Str)   ║
║  Stealth  Acrobatics  Sleight  Marksmanship   ║
║  Perception  Tracking  Insight  Nen Sense     ║
║  Nen Knowledge  Investigation  Medicine  Tactics║
║  Nen Attack(Manip)  Nen Control               ║
║  Concentration  Courage  Oath  Nen Attack(Dir)║
║  Persuasion  Deception  Intimidation  Leadership║
╠══════════════════════════════════════════════╣
║              NEN ABILITY                      ║
║  Ability Name:                                ║
║  Type:          SP Cost:                      ║
║  Base Effect:                                  ║
║  Binding Pledge (BP income):                   ║
║  BP Enhancement (BP spent):                    ║
║  BP Balance:____ / ____                        ║
╠══════════════════════════════════════════════╣
║           EQUIPMENT & ITEMS                   ║
║  Weapon:_____________  Damage:______          ║
║  Armor:_____________  AC Bonus:___            ║
║  Money:____________ J                          ║
║  Items:____________________________________   ║
╠══════════════════════════════════════════════╣
║              BACKGROUND                       ║
║  Origin:________  Motivation:________         ║
║  Appearance:____  Deep Trait:____             ║
║  Core Bond:__________________________________ ║
╚══════════════════════════════════════════════╝
```

---

> *"The deeper you restrict yourself, the closer you draw to the essence of Nen."*
> *— Hunter World Proverb*

> 📘 **Game Masters (GM): please refer to the *Hunter × Hunter TRPG Game Master (GM) Handbook* v1.0**, which contains the complete worldview setting, factions and powers, NPC / Monster templates, encounter design guides, and four module frameworks.

> **Version History**
> - v1.0 (2026-06-21): Initial release. Split out from the complete rulebook.
