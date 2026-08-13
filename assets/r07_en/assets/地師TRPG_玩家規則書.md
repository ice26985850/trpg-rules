# Earth Master TRPG — Player Rulebook

> **Version:** v1.0
> **Design Studio:** TTRPG Rules Studio
> **Genre & Theme:** Eastern Folk Customs × Tomb-Raiding Exploration × Low-Martial True Qi × Folk Spells
>
> You are not a Touch-Gold Captain; you are an Earth Master—reading Feng Shui, discerning Yin-Yang, Open Coffin & Locate the Acupoint, and negotiating terms with the things in the tomb.
> Some tombs should not be opened. Yet you opened them anyway.

---

# Chapter One: Core Rules

## 1-1 Core Check System

Earth Master TRPG uses a check system of **2d10 + Attribute Value + Skill Level** against **Difficulty Class (DC)**.

### Check Formula

```
Check Result = 2d10 + Attribute Value + Skill Level + Equipment Modifier
Success Condition: Check Result ≥ Difficulty Class (DC)
```

### Why 2d10?

The results of two ten-sided dice form a bell curve—the probability of extreme values (2 or 20) is only 1%, while the middle value (11) appears as high as 10%. This means:

- **Skill Overwhelms Luck**: A skilled Earth Master will not have a 5% chance of making a low-level mistake
- **Every Point of Modifier Matters**: In the middle section of the bell curve, each +1 modifier raises the success rate by roughly 5-10%
- **Critical Success and Critical Failure Are Rare and Precious**: double 10 Critical Success (1%), double 1 Critical Failure (1%)

### Critical Success and Critical Failure

| Roll Result | Name | Effect |
|:---:|------|------|
| **Double 10 (20)** | **Critical Success** | Automatic success, and gain an additional positive effect (GM's discretion) |
| **Double 1 (2)** | **Critical Failure** | Automatic failure, and an accidental negative effect occurs (GM's discretion) |

### Advantage and Disadvantage

In certain situations, checks gain **Advantage** or **Disadvantage**:

| Status | Mechanic | Equivalent Modifier |
|------|------|:---:|
| **Advantage** | Roll 3d10, take the higher two | approx. +3.8 |
| **Disadvantage** | Roll 3d10, take the lower two | approx. −3.8 |
| **Double Disadvantage** | Roll 4d10, take the lower two | approx. −5.5 |

> **Fear Disadvantage**: When your Fear Value exceeds your Fear Threshold, all actions gain Disadvantage. This is the state Earth Masters most often face in tombs.

### 2d10 Success Rate Reference Table

| Total Modifier | DC 6 | DC 10 | DC 14 | DC 18 | DC 22 | DC 26 | DC 30 |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| +0 | 90% | 64% | 28% | 6% | 1% | 0% | 0% |
| +2 | 98% | 85% | 45% | 15% | 3% | 0% | 0% |
| +4 | 100% | 97% | 64% | 28% | 6% | 1% | 0% |
| +6 | 100% | 99% | 85% | 45% | 15% | 3% | 0% |
| +8 | 100% | 100% | 94% | 64% | 28% | 6% | 1% |
| +10 | 100% | 100% | 98% | 85% | 45% | 15% | 3% |

---

## 1-2 Five Attributes

| Attribute | Abbreviation | Meaning | Role in Tomb-Raiding |
|------|:---:|------|------|
| **Agility (身)** | 身 | Nimbleness, movement, physique—the body's execution | Evade traps, climb tomb passages, close-quarters combat |
| **True Qi (氣)** | 氣 | Internal cultivation, breath circulation—reserve and use of inner energy | Execute martial techniques, resist Corpse Poison, circulate Qi to protect the body |
| **Geomancy (輿)** | 輿 | Feng Shui knowledge, tomb layout, trap principles | Divide-Gold Fix-Point, see through traps, judge tomb chamber structure |
| **Spirit Sense (靈)** | 靈 | Perceive the supernatural, talisman efficacy, spirit communication | Open the Yin-Yang Eye, draw talismans, negotiate with the "things" in the tomb |
| **Courage (膽)** | 膽 | Willpower, psychological endurance | Resist fear, suppress corpse-aura pressure, stay calm while suffocating |

### Attribute Value Meaning

| Attribute Value | Narrative Description |
|:---:|------|
| 1 | Extremely weak—this ability barely exists |
| 2–3 | Weak—below average person |
| 4–5 | Average—ordinary person level |
| 6–7 | Excellent—through training or exceptional talent |
| 8–9 | Outstanding—Grandmaster level |
| 10 | Legendary—human limit (only reachable through leveling up) |

---

## 1-3 Derived Attributes

| Derived Attribute | Abbreviation | Formula | Use |
|------|:---:|------|------|
| **Health Points (HP)** | HP | Agility × 3 + 10 | Upper limit of physical damage endurance |
| **Qi Pool (QP)** | QP | True Qi × 2 + 5 | Energy reserve for martial techniques and spells |
| **Fear Value** | Fear Value | 0 (start), dynamically accumulates | Current degree of fear |
| **Fear Threshold (FT)** | FT | Courage × 2 + 5 | Upper limit of fear tolerance |
| **Yin-Yang Perception (YY)** | YY | 10 + Spirit Sense | Passive perception of supernatural existences |
| **Putrefaction Resistance (PR)** | PR | True Qi + floor(Courage ÷ 2) | Bonus to checks against Putrefaction Infection |
| **Defense (DEF)** | DEF | Agility + Equipment Defense Modifier + Iron Body Modifier | Hit threshold when attacked |
| **Initiative (INIT)** | INIT | Agility + floor(Courage ÷ 2) | Determines action order at the start of an encounter (fixed value) |

### Health Points (HP) Status

| HP Status | Effect |
|------|------|
| HP ≥ 50% | Normal state |
| HP < 50% | Light Wound—no extra penalty, but GM should describe physical condition |
| HP < 25% | Heavy Wound—Disadvantage on all actions |
| HP ≤ 0 | Unconscious and fallen. Lose 1 HP per round (bleeding). Requires ally's treatment |
| HP ≤ −Agility | Death |

---

## 1-4 Difficulty Class (DC) Ladder

| DC | Difficulty | Description | Example |
|:---:|------|------|------|
| **6** | Trivial | Almost never fails | Walking on flat ground, identifying common items |
| **10** | Simple | An average person has better than half chance of success | Climbing a wall with footholds, spotting an obvious trap |
| **14** | Moderate | Requires some training | Judging a tomb chamber's dynasty, drawing an Evil-Dispelling Talisman |
| **18** | Hard | Requires professional level | Divide-Gold Fix-Point to find a hidden ancient tomb, drawing a Corpse-Suppressing Talisman |
| **22** | Very Hard | Grandmaster-level challenge | Seeing through a false tomb, drawing the Five-Thunder Talisman |
| **26** | Legendary | Only the world's top can accomplish | Conversing with a Flesh-That-Does-Not-Decay to gain trust |
| **30** | Nearly Impossible | Legendary feats | Sealing a Corpse-Nurturing Ground alone |

---

## 1-5 Skill System

Earth Masters have **25 Skills**, divided among the Five Attributes, each skill level 0–6 (creation cap Lv3; Lv6 unlocks at level ≥ 12).

### Agility Skills (身)

| Skill | Abbreviation | Typical Use |
|------|:---:|------|
| **Climb** | Climb | Climb tomb-passage shafts, vault over dragon-breaking stones, rope descent |
| **Dodge** | Dodge | Dodge trap crossbows, avoid falling rocks, evade Jiangshi pounces |
| **Stealth** | Stealth | Move silently in the tomb, avoid detection by the tomb's things |
| **Weapon Combat** | Weapon | Close-quarters combat, slay Jiangshi with a peachwood sword, pierce spirits with a Coin Sword |
| **Throw** | Throw | Throw glutinous-rice bags, fling ropes, toss a fire starter to ignite gas |

### True Qi Skills (氣)

| Skill | Abbreviation | Typical Use |
|------|:---:|------|
| **Qi Guard** | Guard | Spend Qi to negate damage, maintain protective Qi aura |
| **Breath Regulation** | Breath | Hold breath, resist poison gas, act underwater |
| **Qi Sense Detection** | Sense | Sense living auras, corpse-aura, Sha |
| **Qi Emission** | Emit | Qi-added damage for palm/finger techniques |
| **Meridian Opening** | Meridian | Accelerate Qi recovery, lower martial-art cost |

### Geomancy Skills (輿)

| Skill | Abbreviation | Typical Use |
|------|:---:|------|
| **Divide-Gold Fix-Point** | Point | Use a compass to locate tombs |
| **Trap Detection** | Trap | Discover and disarm tomb traps |
| **Tomb Reading** | Tomb | Judge tomb-chamber layout, dynasty, tomb-owner identity |
| **Earth-Vein Sense** | Vein | Sense dragon-vein courses, Sha gathering points |
| **Antiquity Appraisal** | Appraise | Appraise burial goods' era, value, and whether cursed |

### Spirit Sense Skills (靈)

| Skill | Abbreviation | Typical Use |
|------|:---:|------|
| **Talisman Drawing** | Talisman | Draw talismans (consume materials and Qi) |
| **Yin-Yang Eye** | Eye | See spirits, perceive Yin-energy density |
| **Summon Spirit** | Summon | Call a specific departed soul to appear |
| **Exorcise** | Exorcise | Banish spirits, purify Sha |
| **Spirit Communion** | Commune | Negotiate and parley with spirits / goblins |

### Courage Skills (膽)

| Skill | Abbreviation | Typical Use |
|------|:---:|------|
| **Will Hold** | Will | Resist mental attacks, hallucinations, possession |
| **Fear Resistance** | Fear | Calm when facing supernatural fear |
| **Pressure Resistance** | Pressure | Resist Jiangshi corpse-aura pressure, tomb-owner's obsession oppression |
| **Calm Judgment** | Calm | Make correct decisions under extreme pressure |
| **Death Struggle** | Struggle | Can still act when HP is below 25% |

### Skill Level

| Skill Level | Narrative Meaning | Cumulative Skill Points | Unlock Condition |
|:---:|------|:---:|------|
| 0 | Untrained—relying purely on attribute talent | 0 | — |
| 1 | Beginner—just starting training | 1 | — |
| 2 | Apprentice—solid basics | 3 | — |
| 3 | Proficient—professional level | 6 | **Creation Cap** |
| 4 | Expert—among the best in the sect | 10 | **Level ≥ 2** |
| 5 | Grandmaster—top of the age | 15 | **Level ≥ 6** |
| 6 | Legendary—named in history | 21 | **Level ≥ 12** |

---

# Chapter Two: Character Creation

## 2-1 Character Creation Flow Overview (10 Steps)

```
Background Origin → Attribute Allocation → Skill Allocation → Main Heritage → Spell Heritage → Affiliated Sect → Signature Technique → First Talisman → Worst Coffin → Team Role
```

---

## 2-2 Step One: Background Origin (roll d8 or choose)

| d8 | Origin | Brief |
|:---:|------|------|
| 1 | **Daoist Temple Adoptee** | Abandoned at a Daoist temple and raised by a master. Learned martial arts not to raid tombs—but to survive |
| 2 | **Escort Bureau Child** | Family ran an escort bureau; trained in boxing since childhood. After the bureau collapsed, found tomb-raiding pays faster than escorting |
| 3 | **Family Craft** | Three generations of Touch-Gold; could read a compass at five. What else would you do? |
| 4 | **Maoshan Apprentice** | As a child you "could see" and were sent up the mountain. The master said you had talent—and that you'd eventually touch what shouldn't be touched |
| 5 | **Self-Taught** | Bought an incomplete Feng Shui secret manual at a used-book stall and dove in |
| 6 | **Learned in the Army** | Served and learned fists and nerve. After discharge an old Earth Master pulled you in—said your "fate is hard" |
| 7 | **Forced Into the Trade** | Never wanted to learn. Family debt forced you to use these skills to repay |
| 8 | **Fled Into Daoism** | Escaped war into a deserted mountain temple; an old Daoist passed on all he knew before dying |

---

## 2-3 Step Two: Attribute Allocation

**25 points** freely allocated to the Five Attributes.
- Single-attribute minimum: **1**
- Single-attribute maximum: **9** (cannot reach 10 at creation)

### Newcomer Attribute Templates

| Template | Agility | True Qi | Geomancy | Spirit Sense | Courage | Suitable Heritage |
|------|:---:|:---:|:---:|:---:|:---:|------|
| **Guardian Grandmaster** | 4 | 9 | 4 | 3 | 5 | Orthodox Daoist Transmission |
| **Melee Bruiser** | 9 | 3 | 3 | 3 | 7 | Folk Martial Master |
| **Wandering Dragon in the Tomb** | 7 | 3 | 7 | 4 | 4 | Touch-Gold Clan |
| **Talisman Specialist** | 3 | 4 | 3 | 9 | 6 | Maoshan Disciple |
| **Balanced Earth Master** | 5 | 5 | 5 | 5 | 5 | Any |
| **Bold and Careful** | 5 | 4 | 6 | 3 | 7 | Touch-Gold + Maoshan |

---

## 2-4 Step Three: Skill Allocation

**20 points** allocated to 25 skills, single-skill cap **Lv3**.

Suggest prioritizing strengthening the heritage's core skills:
- Orthodox Daoist Transmission → Qi Guard, Breath Regulation
- Folk Martial Master → Weapon Combat, Dodge
- Touch-Gold Clan → Climb, Trap Detection
- Maoshan Disciple → Talisman Drawing, Yin-Yang Eye

---

## 2-5 Step Four: Choose Main Heritage

### Heritage Overview

| Heritage | Core Attribute | Specialty | Qi Style | HP Tendency |
|------|:---:|------|------|:---:|
| **Orthodox Daoist Transmission** | True Qi (氣) | Protective arts, healing, deep Qi | Deep and enduring | Medium (+4/level) |
| **Folk Martial Master** | Agility (身) | Footwork, palm techniques, Iron Body, melee | Burst, fierce | High (+5/level) |
| **Touch-Gold Clan** | Agility + Geomancy | Lightfoot, dodge, trap-breaking | Light and agile | Low (+3/level) |
| **Maoshan Disciple** | Spirit Sense (靈) | Talismans, spirit sense, spirit negotiation | Weak but pure | Low (+3/level) |

> Heritage is not a class—it is where you learned your martial arts and spells. Each Earth Master has a different origin and master, which determines how you survive in the tomb.

### Orthodox Daoist Transmission

**Attribute Requirement:** True Qi (氣) ≥ 6
**Starting Talent—Deep Qi:** Qi Pool cap +3 extra
**Heritage Trait—Enduring Qi-Vein:** +1 to Qi recovery when meditating/regulating breath

**Starting Martial Arts (choose 2):**

| Martial Art | Type | Qi | Corresponding Skill | Effect |
|------|------|:---:|------|------|
| **Taiji Force** | Protective Art | 2 | Qi Guard | Physical damage taken this round halved |
| **Innate Gang Qi** | Protective Art | 1/round | Qi Guard | After activation, 1 Qi per round, damage reduction 2 |
| **Daoist Breathing** | Healing | 3 | Breath Regulation | Restore 2d4 HP (self only) |
| **Qi Pierces the Rainbow** | Support | 2 | Meridian Opening | Next Qi-related check gains Advantage |

**Advanced Martial Arts (unlock by level):**

| Level | Martial Art | Type | Qi | Corresponding Skill | Effect |
|:---:|------|------|:---:|------|------|
| 3 | **Two-Forms Generation** | Protective Art | 4 | Qi Guard | Transfer one instance of damage entirely to the Qi Pool (1 damage = 1 Qi); shortfall deducted from HP |
| 5 | **Hunyuan Stance** | Passive | — | — | Qi Pool permanently +10 |
| 7 | **Return-to-Source Healing** | Healing | 5 | Breath Regulation | Restore 3d6 HP, usable in combat |
| 9 | **Bagua Roaming Body** | Footwork | 3 | Dodge | All attacks against you have Disadvantage this round |
| 12 | **Daoist Heart Method** | Passive | — | — | Meditation recovery +2 more (after stacking, recover 5 per round) |
| 15 | **Wuji Return-to-Source** | Healing | All | Breath Regulation | Spend all Qi, restore HP equal to consumption ×1.5 |

### Folk Martial Master

**Attribute Requirement:** Agility (身) ≥ 6
**Starting Talent—Forged in Battle:** HP cap +5 extra
**Heritage Trait—Fierce Body-Forging:** +5 HP growth per level

**Starting Martial Arts (choose 2):**

| Martial Art | Type | Qi | Corresponding Skill | Effect |
|------|------|:---:|------|------|
| **Iron Sand Palm** | Palm Technique | 1/hit | Weapon Combat | 1d6 + martial-art level Qi damage. Can shatter wood and stone |
| **Eight-Step Toad Chase** | Footwork | 1 | Dodge | Movement speed doubled for one round. Kick off vertical walls for three steps |
| **Iron Bridge Firm Stance** | Iron Body | Passive | — | Damage reduction 1 (DEF Iron Body modifier +1) |
| **Beng Fist** | Palm Technique | 2 | Weapon Combat | 1d4 + martial-art level Qi damage, ignores target's damage reduction |

**Advanced Martial Arts (unlock by level):**

| Level | Martial Art | Type | Qi | Corresponding Skill | Effect |
|:---:|------|------|:---:|------|------|
| 3 | **Golden Bell Cover** | Protective Art | 2/round | Qi Guard | Reduction raised to 3 (DEF Iron Body modifier +3) |
| 5 | **Seven-Probe Snake Form** | Footwork | 3 | Dodge | Enemy cannot target you this round |
| 7 | **Iron Shirt** | Iron Body | Passive | — | Reduction permanently +2 (DEF Iron Body modifier +2, stacks with Iron Bridge Firm Stance up to +3) |
| 9 | **Heart-Driving Palm** | Palm Technique | 4 | Weapon Combat | 2d8 + martial-art level Qi damage; target must make a Constitution check (DC 16) or suffer internal-organ shock |
| 12 | **Iron Body Mastery** | Passive | — | — | Unarmed attacks count as arcane implements (can harm Flesh-That-Does-Not-Decay) |
| 15 | **Vajra Indestructibility** | Protective Art | 5 | Qi Guard | Immune to all physical damage for one round. Once per battle |

### Touch-Gold Clan

**Attribute Requirement:** Agility (身) ≥ 5 and Geomancy (輿) ≥ 5
**Starting Talent—Tomb Intuition:** Trap-perception checks +2. Agility checks in tomb-chamber environments gain Advantage
**Heritage Trait—Wandering Dragon in the Tomb:** +1 to all Agility checks in enclosed spaces

**Starting Martial Arts (choose 2):**

| Martial Art | Type | Qi | Corresponding Skill | Effect |
|------|------|:---:|------|------|
| **Gecko Skill** | Lightfoot | 1 | Climb | Move freely on vertical walls/ceilings for a number of rounds equal to Geomancy value |
| **Bone-Contracting Skill** | Special | 2 | — | Pass through narrow gaps the size of a skull |
| **Listen-to-Wind, Discern-Devices** | Passive | — | — | No Disadvantage in darkness. Sense faint sounds within 30 feet |
| **Civet Cat Turn** | Footwork | 1 | Dodge | When hit, spend a reaction to dodge—re-roll the opponent's hit check |

**Advanced Martial Arts (unlock by level):**

| Level | Martial Art | Type | Qi | Corresponding Skill | Effect |
|:---:|------|------|:---:|------|------|
| 3 | **Swallow Three Touches Water** | Lightfoot | 2 | Climb | Skim three steps across water + evade one attack |
| 5 | **Cloud-Probing Hand** | Passive | 1 | Trap Detection | Advantage on disarming traps; can operate one-handed |
| 7 | **Shadowless Step** | Footwork | 3 | Dodge | Enemy cannot target you this round |
| 9 | **Dragon-Seeking Point-Acupoint** | Support | 2 | Divide-Gold Fix-Point | Sense tomb-chamber structure within 60 feet (hidden doors, trap trigger points) |
| 12 | **Night Crow Flight** | Lightfoot | 3 | Stealth | Move silently for one round, ignoring terrain obstacles |
| 15 | **Even Thieves Have Code** | Special | 4 | — | All traps ineffective against you for one round. Traps can be redirected |

### Maoshan Disciple

**Attribute Requirement:** Spirit Sense (靈) ≥ 6
**Starting Talent—Talisman Heritage:** Start with 3 extra pre-drawn talismans. Talisman Drawing checks +1
**Heritage Trait—Yin-Yang Eye:** When Spirit Sense ≥ 6, automatically sense supernatural existences within 50 feet. Can spend 1 Qi to see through ghost-wall illusions

**Starting Talismans (choose 2):**

| Talisman | Qi | Material | Corresponding Skill | Effect |
|------|:---:|------|:---:|------|
| **Evil-Dispelling Talisman** | 1 | Cinnabar + yellow paper | Talisman Drawing | 1d8 burn damage to spirits/Jiangshi; target has Disadvantage on attacks and halved movement next round |
| **Protective Talisman** | 2 | Cinnabar + yellow paper | Talisman Drawing | Block one supernatural attack (damage reduced to zero; talisman burns up) |
| **Path-Guiding Talisman** | 1 | Cinnabar + yellow paper | Talisman Drawing | After burning, drifts toward the heaviest Yin-energy, lasting 10 minutes |
| **Calming Talisman** | 1 | Cinnabar + yellow paper | Talisman Drawing | Paste on forehead—Fear Value immediately drops to zero. One-time use |

**Advanced Talismans (unlock by level):**

| Level | Talisman/Spell | Qi | Material | Corresponding Skill | Effect |
|:---:|------|:---:|------|:---:|------|
| 3 | **Corpse-Suppressing Talisman** | 3 | Cinnabar + yellow paper + Qi infusion | Talisman Drawing (DC 18) | Pin a Jiangshi for several hours; external force can tear it off or water can nullify it |
| 5 | **Defilement-Breaking Talisman** | 3 | Cinnabar + yellow paper + glutinous-rice powder | Talisman Drawing (DC 14) | Disperse Yin-energy within 20 feet; low-tier spirits forcibly driven back |
| 7 | **Five-Thunder Talisman** | 4 | Cinnabar + yellow paper + Qi | Talisman Drawing (DC 22) | 3d8 arcane-implement damage to Jiangshi; can split the Jiangshi's surface |
| 9 | **Spirit-Summoning Art** | 5 | Spirit-Summoning Banner + deceased's belongings | Summon Spirit (DC 18) | Force a departed soul to appear and answer three truth questions. ⚠ Using it generates karma |
| 12 | **Celestial Master Talisman Method** | 5 | Cinnabar + yellow paper + Qi | Talisman Drawing (DC 22) | Effects of drawn talismans ×2 (stacks with the Celestial Master Talisman item) |
| 15 | **Invite the Gods / Spirit Possession** | 8 | Incense×3 + talisman + self | Will Hold (DC 15) | Patriarch possesses you for 10 minutes; cast any known talisman without materials. After ending, make a Courage DC 15 check; on failure, cannot invite gods again for 24hr and all checks have Disadvantage. ⚠ Using it generates karma |

> **Maoshan Minor Inheritance Restriction:** If Maoshan is a minor heritage, talisman advancement is delayed by 2 levels (levels in the table above +2), and "Invite the Gods / Spirit Possession" cannot be obtained. Qi cost is an extra +1.

---

## 2-6 Step Five: Choose Spell Heritage

Maoshan Disciple (minor) or None. If Step Four already chose Maoshan as main, skip.

### Multi-Heritage Combination Rules

| Combination | Gains |
|------|------|
| **Maoshan (Main)** | All Maoshan starting + 4 talismans (1 extra) |
| **Orthodox Daoist (Main) + Maoshan (Minor)** | All Daoist + 1 Maoshan starting talisman + Talisman Drawing +1. Minor talisman advancement delayed 2 levels, cannot obtain Invite the Gods, Qi cost +1 |
| **Martial Master (Main) + Maoshan (Minor)** | All Martial Master + 1 Maoshan starting talisman + Talisman Drawing +1. Same restrictions as above |
| **Touch-Gold (Main) + Maoshan (Minor)** | All Touch-Gold + 1 Maoshan starting talisman + Talisman Drawing +1. Same restrictions as above |
| **Any (Main) + None** | Only the main heritage's full abilities, more specialized |

---

## 2-7 Step Six: Affiliated Sect

Heritage answers "where you learned your martial arts," while sect answers "which organization you belong to."

| Sect | Core Philosophy | Sect Resources |
|------|------|------|
| **Dragon-Shaker Sect** | Locate dragons and point acupoints; all the world's tombs lie in your chest | Dragon-Shaker secret compass usage rights, ancient-tomb maps, free lodging at strongholds |
| **Xuan Kong Sect** | True Qi as root, Yin-Yang as use | Meditation recovery ×1.5 in training rooms; can take Xuan Kong heart method (LV5+) |
| **Talisman Sect** | Talisman magic reaches heaven; one sheet suppresses Yin-Yang | Talisman materials half price; LV7+ can learn the exclusive talisman "Golden Light Spell" |
| **Mountain-Mover Sect** | Move mountains and lift ridges; real combat is king | Secret passages and safe houses in major cities, mountain-moving shovel (earth-probing +2), Mountain-Mover secret records |

> Sects provide "organizational resources" rather than "combat numbers." Choosing the Dragon-Shaker Sect means you have better maps and compasses; choosing the Mountain-Mover Sect means you have secret passages and professional tools.

### Sect-Exclusive Abilities

**Talisman Sect—Golden Light Spell (LV7+):** Spend 3 Qi to radiate golden light for 1 minute. During this, low-tier spirits (White Jiangshi and below) cannot approach within 10 feet; your DEF +2 vs supernatural attacks; can illuminate 30 feet in darkness. Usable Spirit Sense value times per day.

**Xuan Kong Sect—Xuan Kong Heart Method (LV5+):** Passive ability. Qi Pool cap +5; extra +1 Qi recovery when meditating/regulating breath (stacks with Orthodox Daoist Transmission's Enduring Qi-Vein); can sense dragon-vein / earth-energy anomalies within 100 feet (no check needed, GM informs secretly).

---

## 2-8 Steps Seven–Ten: Character Portrayal

### Step Seven: Signature Technique

Choose one known martial art / talisman and gain one of the following enhancements:
- **Mastery**: That martial-art check gains Advantage
- **Economy**: Qi cost −1 (minimum 1)
- **Amplify**: Damage +1d / duration +1 round / range expanded
- **Original**: Co-create a unique effect with the GM

### Step Eight: First Talisman

What was the first talisman you successfully drew? Who taught you? Is it still around? If it was used up—what happened that time?
(GM optional: if "still kept," when used it automatically takes the maximum value, one-time)

### Step Nine: The Worst Coffin You've Opened

What tomb? Whose coffin? What was inside? How did you escape? What changed in you since then?

### Step Ten: Role in the Team

| Role | Duty | Suggested Heritage + Sect |
|------|------|------|
| **Eye-Master (Feng Shui Master)** | Divide-Gold Fix-Point, judge tomb layout | Touch-Gold + Dragon-Shaker |
| **Vanguard (Path-Opener)** | First down the tomb passage, triggers traps and survives | Martial Master + Mountain-Mover |
| **Coffin-Suppressor (Muscle)** | Handle the things in the coffin | Martial Master + Mountain-Mover, Orthodox Daoist + Xuan Kong |
| **Talisman-Caster (Spell Role)** | Paste talismans, chant spells, sprinkle glutinous rice | Maoshan + Talisman |
| **Negotiator (Medium)** | Negotiate terms with the things in the tomb | Maoshan + Talisman (Spirit Sense ≥ 7) |
| **Rear-Guard (Cover Retreat)** | Ensure everyone gets out alive | Orthodox Daoist + Xuan Kong, Martial Master + Mountain-Mover |

---

# Chapter Three: Growth and Leveling Up

## 3-1 Level Stages

| Stage | Level | Description |
|------|:---:|------|
| **Greenhorn** | 1–4 | Can handle White Jiangshi; Black Jiangshi needs full-team cooperation |
| **Holding Your Own** | 5–9 | Can independently handle Black Jiangshi, deal with traps |
| **Renowned in the Region** | 10–14 | Fight Jumping Corpses, crack imperial mausoleums |
| **A Grandmaster of the Age** | 15 | Face the Flesh-That-Does-Not-Decay, seal Corpse-Nurturing Grounds |

## 3-2 Experience Points (XP) Table

| Level | XP to Level | Cumulative XP | Approx. Adventures |
|:---:|:---:|:---:|:---:|
| 1 | — | 0 | Character creation |
| 2 | 250 | 250 | 1 small tomb |
| 3 | 500 | 750 | 2 times |
| 4 | 750 | 1,500 | 3–4 times |
| 5 | 1,250 | 2,750 | 5–6 times |
| 6 | 1,750 | 4,500 | 8–9 times |
| 7 | 2,500 | 7,000 | 12 times |
| 8 | 3,250 | 10,250 | 16 times |
| 9 | 4,000 | 14,250 | 20 times |
| 10 | 5,000 | 19,250 | 25 times |
| 11 | 6,000 | 25,250 | 30 times |
| 12 | 7,000 | 32,250 | 36 times |
| 13 | 8,000 | 40,250 | 43 times |
| 14 | 9,500 | 49,750 | 50 times |
| 15 | 11,000 | 60,750 | 58 times |

XP Acquisition Reference: Minor Tomb 200–400 / Medium Tomb 500–800 / Major Tomb 900–1,500 / Imperial Mausoleum 1,500–3,000

## 3-3 Growth per Level

| Level | HP/QP Growth | Attribute Points | Skill Points | Martial Art / Talisman | Feat | Heritage Ability | Skill Cap |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| 1 | Starting | — | Char. Creation 20 | Starting 2 Techniques | — | Starting Talent | Lv3 |
| 2 | +Heritage Value | — | +2 | — | — | — | **Lv4** |
| 3 | +Heritage Value | +1 | +2 | Learn 1 New Technique | — | — | Lv4 |
| 4 | +Heritage Value | — | +2 | — | — | — | Lv4 |
| 5 | +Heritage Value | +1 | +2 | — | — | ⭐ Advancement | Lv4 |
| 6 | +Heritage Value | — | +2 | Learn 1 New Technique | — | — | **Lv5** |
| 7 | +Heritage Value | +1 | +2 | — | — | — | Lv5 |
| 8 | +Heritage Value | — | +2 | — | Feat ×1 | — | Lv5 |
| 9 | +Heritage Value | — | +2 | Learn 1 New Technique | — | — | Lv5 |
| 10 | +Heritage Value | — | +2 | — | — | ⭐⭐ Mastery | Lv5 |
| 11 | +Heritage Value | +1 | +2 | — | — | — | Lv5 |
| 12 | +Heritage Value | — | +2 | Learn 1 New Technique | — | — | **Lv6** |
| 13 | +Heritage Value | — | +2 | — | Feat ×1 | — | Lv6 |
| 14 | +Heritage Value | +1 | +2 | — | — | — | Lv6 |
| 15 | +Heritage Value | — | +2 | — | — | ⭐⭐⭐ Ultimate | Lv6 |

### Martial Art Level (Martial Art Level)

Martial Art Level determines the attack bonus and overall power when you perform martial arts. It increases automatically with character level:

| Character Level | Martial Art Level | Description |
|:---:|:---:|------|
| 1–2 | +1 | Apprentice — Just mastered the basic moves |
| 3–4 | +2 | Initiate — Moves begin to integrate into real combat |
| 5–6 | +3 | Proficient — Can perform combo techniques fluidly |
| 7–9 | +4 | Mastery — Moves flow freely at will |
| 10–12 | +5 | Grandmaster — Every movement is martial art |
| 13–15 | +6 | Legendary — Top of the current age |

**Martial Art Attack Formula:** `2d10 + Agility (身) + Martial Art Level vs Target DEF`

> Martial Art Level is a unified bonus — you do not need to track a level for each individual technique. It represents your overall martial art cultivation. When you level up, Martial Art Level increases automatically. Talisman checks do not use Martial Art Level — they use the formula "2d10 + Spirit Sense (靈) + Talisman-Drawing Skill".
>
> **Design Note:** High-level martial arts (such as Cuixin Palm / Heart-Crushing Palm) provide higher single-turn burst damage, but have lower True Qi efficiency (damage per Qi is lower than Tiesha Palm / Iron Sand Palm). Choosing when to use high-cost martial arts is the core strategy of Qi management — burst at critical moments rather than squandering it every turn.

### HP/QP Growth by Heritage

| Heritage | HP per Level | QP per Level |
|------|:---:|:---:|
| Orthodox Daoist Transmission | +4 | +4 |
| Folk Martial Master | +5 | +2 |
| Touch-Gold Clan | +3 | +3 |
| Maoshan Disciple (Primary) | +3 | +3 |

### LV1–LV15 Cumulative

- Attribute Points: 6 points (LV3/5/7/11/14)
- Skill Points: 28 points (level × +2) + Char. Creation 20 = 48 points total
- Martial Art / Talisman: Starting 2 techniques + 4 learned on level-up = 6 techniques total
- Feats: 2 (LV8/13)
- Heritage Abilities: 3 tiers (LV5/10/15)

## 3-4 Feat System (Choose 1 each at LV8, LV13)

| Feat | Effect |
|------|------|
| **Strong Body** | HP Maximum +10 |
| **Long Qi Vessels** | QP Maximum +8 |
| **Iron Courage** | Fear Threshold (FT) +5 |
| **Talisman Mastery** | Talisman-Drawing check permanent +2 (requires Talisman ability) |
| **Dual Talismans** | Maintain two protective talismans simultaneously |
| **Mechanism Expert** | Advantage on disable / detect trap checks |
| **Putrefaction Immunity** | Putrefaction Resistance (PR) +4 |
| **Lightfoot Specialization** | Lightfoot-type martial arts Qi cost −1 |
| **Iron Body Specialization** | Defense (DEF) Iron Body modifier +1 additional |
| **Quick Talisman Hand** | Drawing talismans in combat becomes a bonus action (once per battle) |
| **Will of Iron** | Advantage on checks against fear / charm / possession |
| **Survival in the Tomb** | When HP hits 0, immediately recover 1d6 (once per adventure) |

---

# Chapter Four: Combat Basics (Player Perspective)

## 4-1 Action Economy

Each turn you may perform the following combination of actions:

| Action Type | Uses per Turn | Content |
|------|:---:|------|
| **Main Action** | 1 | Attack, use item, perform martial art, draw talisman (in combat), open coffin |
| **Move Action** | 1 | Move up to 30 ft (may forgo main action to gain a second move) |
| **Reaction Action** | 1 (not on own turn) | Dodge (Cat-Spin), Body-Guarding Skill (Circulate Qi to Guard Body), Block |
| **Free Action** | Unlimited | Speak, drop items, switch held equipment |

### Movement and Distance

This game defaults to using **Theater of the Mind** — the GM and players understand battlefield positions through narration, without using a grid map. Distances are marked in "ft" for reference (1 ft ≈ 30 cm):

- **Melee Range:** Within 5 ft. Melee attacks may be made within this range.
- **Normal Movement:** 30 ft per turn (about 9 m). In a tomb passage you can roughly move from the back of the group to the front.
- **Double Move:** Forgo the main action for a second move — 60 ft total.
- **Difficult Terrain:** Rubble, flooded areas, narrow tomb passages — movement speed halved.

### Dodge Action

If you lack Iron Body or the Body-Guarding Skill, you may use a **Main Action** to perform a Dodge: your DEF +4 this turn (effective against both melee and ranged attacks), until the start of your next turn. This action costs no Qi, but consumes your main action (i.e., you cannot attack this turn).

### Teamwork Check

When multiple characters cooperate to complete the same task:

- The **Helper** makes the relevant check (DC 10).
- On success, the **Primary Performer** gains **Advantage** (roll 3d10, take the higher two).
- At most 2 people may assist the same check (i.e., at most 3 people cooperate on one task).
- Some tasks require multiple people (e.g., the Sha-Suppressing Grand Array in S5 requires 3 Earth Masters) and cannot be completed solo.

### Opportunity Attack

When an enemy is within your melee range (5 ft) and leaves your range without using the "Retreat" action, you may spend a **Reaction Action** to make one melee attack (general attack formula: 2d10 + Agility (身) + Brawling). This attack uses a normal hit check; on hit it deals the weapon's base damage (no Qi bonus).

## 4-2 Attack Check

```
Attack Check = 2d10 + Agility (身) + Relevant Skill vs Target Defense (DEF)
```

- **Hit:** Attack Check ≥ Target DEF
- **Miss:** Attack is dodged or blocked
- **Critical Success (double 10):** Automatic hit, damage takes maximum value
- **Critical Failure (double 1):** Automatic miss, an accident may occur

### Martial Art Attack vs General Attack

| Attack Method | Formula |
|------|------|
| **Martial Art Attack** (palm techniques, sword techniques, etc.) | 2d10 + Agility (身) + Martial Art Level |
| **General Attack** (emergency when no martial art) | 2d10 + Agility (身) + Brawling Skill Level |

## 4-3 Damage Calculation

| Damage Type | Description | Source Example |
|------|------|------|
| **Physical Damage** | Ordinary weapons and unarmed attacks | Fists, blades, traps |
| **True Qi Damage** | Qi-enhanced attacks | Iron Sand Palm, Beng Fist, Cuixin Palm |
| **Talisman Damage** | Burn damage produced by talismans | Evil-Dispelling Talisman, Five-Thunder Talisman |
| **Spirit Tool Damage** | Special implements' suppression of the supernatural | Peachwood Sword, Coin Sword, Century Peachwood Sword |
| **Mental Damage** | Attacks that directly affect the mind | Vengeful Spirit's mental shock |
| **Environmental Damage** | Damage caused by the tomb environment | Poison gas, mercury, collapse |

### Supernatural Damage Matrix

| Attack Method | vs White Jiangshi | vs Black Jiangshi | vs Hopping Corpse | vs Unrotting Bone | vs Vengeful Spirit |
|------|:---:|:---:|:---:|:---:|:---:|
| Ordinary Weapon | 1d6 (halved) | 1d4 (halved) | 0 (ineffective) | 0 (ineffective) | 0 (no physical form) |
| Unarmed Attack | 1d4 | 1d2 | 0 | 0 | 0 |
| Palm Technique (Qi) | 1d6 + Martial Art Level | 1d6 + Martial Art Level | 1d4 + Martial Art Level | 1 + Martial Art Level | Martial Art Level damage |
| Peachwood Sword | 1d4 | 1d4 | 1d2 | 0 | 1d6 |
| Coin Sword | 1d8+1d4 burn | 1d8 | 1d6 | 1d4 | 1d4 |
| Century Peachwood Sword | 1d8 | 1d8 | 1d6 | 1d4 | 2d6 |
| Five-Thunder Talisman | 3d8 | 3d8 | 3d8 | 2d8 | 2d8 |

## 4-4 Use of True Qi in Combat

| Qi Use | Cost | Effect |
|------|:---:|------|
| Circulate Qi to Guard Body | 1/turn | Spend Qi to negate damage (1 Qi = negate 2 damage) |
| Hold Breath | 1/turn | Temporarily need no breath in poison gas / underwater / corpse qi |
| Suppress Corpse Poison | 2/turn | Halt the spread of corpse poison (must keep spending until treated) |
| Qi Sense Detection | 2/use | Sense nearby "aura" — living, dead, Sha |
| Qi Healing | Variable | 1 Qi = 1 HP, recover at most 3 HP per turn |

## 4-5 Use of Talismans in Combat

### Talisman-Drawing Modes

| Mode | Condition | Check | Time |
|------|------|:---:|------|
| **Pre-Drawn Talisman** | Safe environment | Automatic success | 1 minute per talisman |
| **Combat Activate Talisman** | Use a pre-drawn talisman | No check needed | Main Action |
| **Emergency Draw Talisman** | Draw on the spot in combat | Difficulty Class (DC) +4 | Main Action |

### Talisman Combat Data

| Talisman | Draw DC | Qi | Effect |
|------|:---:|:---:|------|
| Evil-Dispelling Talisman | 14 | 1 | 1d8 burn to spirit / jiangshi; target has Disadvantage on attacks and halved movement next turn |
| Corpse-Suppressing Talisman | 18 | 3 | Pins a jiangshi for several hours; external force can tear it off or water immersion nullifies it |
| Protective Talisman | 18 | 2 | Blocks one supernatural attack (Black Dog Blood enhanced version DC 20, blocks two) |
| Guide Talisman | 10 | 1 | After lighting, drifts toward the heaviest yin energy, lasts 10 minutes |
| Message Talisman | 10 | 1 | Remote communication (requires a pair of talismans; burn one → text appears on the other) |
| Defile-Breaking Talisman | 14 | 3 | Disperses yin energy within 20 ft; low-tier spirits are force-dispelled |
| Five-Thunder Talisman | 22 | 4 | 3d8 damage to jiangshi; can split open the jiangshi's outer body |

## 4-6 Fear System

### Fear Value Accumulation

| Trigger Event | Fear Value Increase |
|------|:---:|
| Witness a White Jiangshi | +2 |
| Witness a Black Jiangshi | +3 |
| Witness a Hopping Corpse | +4 |
| Witness an Unrotting Bone | +5 |
| Witness a Vengeful Spirit appearing | +3 |
| Eroded by corpse qi | +1/turn |
| Companion severely wounded and falls | +2 |
| Tomb chamber collapse | +3 |
| Ghost Wall (Ghost-Baffling Wall) | +2 |
| Corpse in coffin opens eyes | +3 |

### Fear States

| Fear Value State | Effect |
|------|------|
| Fear Value ≤ Fear Threshold (FT) | **Calm** — normal actions |
| Fear Value > FT | **Fear** — Disadvantage on all actions |
| Fear Value > FT × 1.5 | **Panic** — must use a move action to flee the fear source each turn |
| Fear Value > FT × 2 | **Breakdown** — cannot act; make a Courage (膽) DC 18 check each turn to recover |

### Fear Subsidence

| Method | Effect |
|------|------|
| Leave the fear source | −1 per turn |
| Companion's comfort (DC 14) | −3 immediately |
| Use a Calming Talisman | reset to zero immediately |
| Soul-Calming Bell | −3 within 30 ft |
| Mind-Stabilizing Incense | halved |
| Safe rest for 10 minutes | reset to zero |

## 4-7 Opening Coffin Mechanism

### Preparations Before Opening the Coffin

| Preparatory Action | Check | Effect |
|------|:---:|------|
| **Bind Ink-Line** | Mechanism Detection DC 10 | Boundary prevents jiangshi from jumping out; Advantage on Initiative check |
| **Affix Corpse-Suppressing Talisman** | Talisman-Drawing DC 18 | If a jiangshi is inside, the talisman auto-pins it for 1 turn |
| **Light Eternal Lamp** | — | Disperses yin energy; +1 to supernatural checks |
| **Sprinkle Glutinous Rice** | — | Jiangshi stepping out of coffin takes 1d4 burn |

### Opening Coffin Random Table (d6)

| d6 | Result |
|:---:|------|
| 1 | **Corpse intact — no mutation:** The tomb owner is merely asleep. Perhaps it truly awaits something. |
| 2 | **Normal remains:** Burial goods may be taken. No supernatural threat. |
| 3 | **Mutation — low tier:** A White Jiangshi sits up. Initiative check. |
| 4 | **Mutation — mid tier:** A Black Jiangshi not only sits up — it has memories from life and may be willing to talk. |
| 5 | **Mutation — high tier:** The coffin is empty. A Hopping Corpse is behind you. Ambush check. |
| 6 | **No corpse:** Inside the coffin is a letter, a spirit tool, or a spirit tablet bearing your name (GM's decision). |

---

# Chapter Five: Equipment and Items

## 5-1 Currency System

| Currency | Conversion | Purchasing Power |
|------|------|------|
| 1 Silver Dollar (Dayang) | = 10 Jiao = 100 Fen | A worker's monthly wage is about 5–8 silver dollars |
| 1 Jiao | = 10 Fen | A filling meal |

## 5-2 Rarity

| Rarity | Mark | Acquisition Method |
|------|:---:|------|
| Common | ◇ White | Shop purchase |
| Refined | ◆ Green | Specific shops, larger towns |
| Rare | ◈ Blue | Antique dealers, peer trade, found in tombs |
| Very Rare | ✦ Purple | Deep tombs, heirloom items |
| Legendary | ★ Gold | Unique, GM's discretion |

## 5-3 Armor

| Armor | Rarity | Price | Weight | Defense Modifier | Notes |
|------|:---:|:---:|:---:|:---:|------|
| No Armor | — | — | — | +0 | Purely relies on Agility (身) to dodge |
| Thick Cloth Garment | ◇ | 1 silver dollar | 1 | +1 | Basic protection |
| Leather Armor | ◇ | 8 silver dollars | 2 | +2 | Stealth −1 |
| Heart-Protection Mirror | ◆ | 15 silver dollars | 3 | +2 | Additional −1 to physical damage |

**Defense (DEF) = Agility (身) + Equipment Defense Modifier (highest) + Iron Body Modifier**

## 5-4 Standard Equipment

| Equipment | Rarity | Price | Weight | Effect |
|------|:---:|:---:|:---:|------|
| Feng Shui Compass (Entry) | ◇ | 3 silver dollars | 1 | Geomancy (輿) check +1 |
| Feng Shui Compass (Refined) | ◆ | 20 silver dollars | 1 | Geomancy (輿) check +2 |
| Peachwood Sword | ◇ | 3 silver dollars | 2 | 1d6 vs spirits; physical 0 |
| Coin Sword | ◆ | 10 silver dollars | 3 | 1d8 vs jiangshi (White Jiangshi +1d4 burn); 1d4 vs spirits |
| Ink-Line Reel | ◇ | 1 silver dollar | 1 | Ink-Line Boundary 10 ft; low-tier spirits / White Jiangshi cannot cross; lasts 1 hr |
| Glutinous Rice (1 bag, 5 jin) | ◇ | 5 jiao | 3 | Sprinkled on ground, jiangshi stepping on it takes 1d4 burn. Drawing out corpse poison costs 1 jin per use, lowers DC by 2 |
| Black Dog Blood (1 bottle) | ◇ | 2 silver dollars | 2 | Splashed on jiangshi → attack Disadvantage + Evil-Dispelling Talisman +2 |
| Cinnabar (1 box) | ◇ | 3 silver dollars | 0.5 | Draws 20 talismans |
| Yellow Paper (1 stack, 20 sheets) | ◇ | 1 silver dollar | 0.5 | Talisman medium |
| Incense (1 bundle, 10 sticks) | ◇ | 5 jiao | 0.5 | 30 minutes per stick. Ritual without incense → Disadvantage |
| Paper Money (1 stack, 50 sheets) | ◇ | 2 jiao | 0.5 | Toll money, soothes low-tier spirits |
| Fire Starter | ◇ | 1 silver dollar | 0.5 | Lights 20 ft, burns for 2 hr |
| Rope (50 ft) | ◇ | 2 silver dollars | 5 | Climb DC −2 |
| Luoyang Shovel | ◇ | 4 silver dollars | 4 | Earth-probing Geomancy (輿) +1 |
| First Aid Kit | ◇ | 3 silver dollars | 1 | Restore 1d6 HP (once per adventure) |

## 5-5 Rare Equipment

| Equipment | Rarity | Price | Weight (kg) | Effect |
|------|:---:|:---:|------|
| Century Peachwood Sword | ◈ | 50 silver dollars | 2d6 vs spirits; 1d8 vs jiangshi. Emits faint glow 5 ft |
| Consecrated Bagua Mirror | ◈ | 40 silver dollars | Yin-Yang Perception (YY) +2. Spend 2 Qi to see through Ghost Wall |
| Soul-Calming Bell | ◈ | 60 silver dollars | Low-tier spirits within 30 ft are stilled for 1 turn. 3 times per day |
| Celestial Master Talisman | ✦ | 80 silver dollars | One-time use, effect ×2 |
| Ink-Line Reel (Gold Thread) | ◈ | 35 silver dollars | Boundary effective against Black Jiangshi and below. Lasts 3 hr |
| Dragon-Seeking Ruler | ◈ | 30 silver dollars | Geomancy (輿) may reroll once (take higher), 3 times per adventure |
| Corpse-Avoiding Incense | ◈ | 25 silver dollars | White Jiangshi will not actively approach within 20 ft. Burns for 1 hr |

---

## 5-6 Consumables

### Talisman Materials

| Material | Sale Price | Consumption Rate |
|------|:---:|------|
| Cinnabar (1 box) | 3 silver dollars | Draws 20 talismans |
| Yellow Paper (1 stack) | 1 silver dollar | 1 sheet per talisman |
| Black Dog Blood (1 bottle) | 2 silver dollars | 1 use |
| Glutinous Rice Flour (1 bag) | 5 jiao | 1 Defile-Breaking Talisman |

Pre-drawn talisman carry limit = Spirit Sense (靈) value × 2 sheets

### Elixirs

| Elixir | Price | Effect |
|------|:---:|------|
| Peiyuan Pill | 5 silver dollars | Restore +5 Qi |
| Xuming Pill | 15 silver dollars | Restore 2d6 HP |
| Jiedu Pill | 8 silver dollars | Removes common poison and mild corpse poison (DC −4) |
| Mind-Stabilizing Incense | 12 silver dollars | Halve Fear Value, effective for all within 30 ft |
| Guixi Pill | 30 silver dollars | No breathing needed for 10 minutes |
| Chunyang Pill | 25 silver dollars | Immune to yin-energy attacks for 1 hr |

At most 2 pills per battle. Repeated use of the same type has diminishing effects.

## 5-7 Encumbrance System

```
Encumbrance Limit = Agility (身) × 5 + 10 (kg)
```

| Encumbrance Level | Condition | Effect |
|------|:---:|------|
| Light | ≤ 50% | Agility (身) check +1 |
| Normal | 51%–100% | No effect |
| Overweight | 101%–150% | Movement halved. Agility (身) / Dodge Disadvantage. Cannot use Lightfoot |
| Extreme Overweight | 151%–200% | Movement 5 ft/turn. Agility (身) auto-fails |
| Impossible | > 200% | Cannot move |

---

# Chapter Six: True Qi and Spells

## 6-1 True Qi Recovery

| Method | Recovery Amount |
|------|:---:|
| Seated Meditation (1 turn) | +2 |
| Deep Trance (10 undisturbed minutes) | Fully restored |
| Take Peiyuan Pill | +5 |
| Meditate at a Dragon Vein Node (Feng Shui treasure spot) | Recovery rate ×2 |

## 6-2 Spell Costs

| Cost Type | Effect |
|------|------|
| **Qi Consumption** | 1–4 Qi per talisman |
| **Material Consumption** | Talisman paper, cinnabar, incense, paper money, etc. — prepare enough before entering the tomb |
| **Yang Energy Loss** | When more than half of the Qi Pool is spent on spells during one encounter, after it ends triggers: temporary HP maximum −5, temporary QP maximum −5, until a long rest is taken |
| **Karma** | Using Soul-Summoning Art (forcing the dead to answer) or keeping a small ghost grants 1 Karma point. Each Karma point doubles the "supernatural encounter probability" secretly rolled by the GM in the next adventure. Karma can be removed by: fulfilling a dead soul's last wish (−1 Karma), a Talisman Sect purification ritual DC 18 (−1 Karma), or returning a cursed burial good to its original tomb (−2 Karma) |

---

## 6-3 Rest and Recovery

### Short Rest (10 minutes)

Briefly rest for 10 minutes in a safe environment. You may:

- Spend **Hit Dice** to recover HP: you have one d6 Hit Die per character level. Spend any number of Hit Dice, each recovering `1d6 + floor(Character Level/2)` HP.
- Perform seated meditation: recover 2 Qi per turn (Orthodox Daoist Transmission +3, Xuan Kong sect mental method holders +1 more).
- Use a First Aid Kit (recover 1d6 HP, once per adventure).
- Halve Fear Value.

Hit Dice are fully restored after a long rest.

### Long Rest (8 hours, usually overnight)

Rest fully for 8 hours in a safe environment. Effects:

- HP restored to maximum.
- Qi Pool restored to maximum.
- All spent Hit Dice restored.
- Fear Value reset to zero.
- Remove one level of "Fatigue" status.
- Yang Energy Loss effect removed.

> **Adventure Day Suggestion:** The GM should design encounters so players have a chance for a short rest after every 2–3 combat encounters, and a long rest after each adventure ends. If players cannot find a safe rest point in the tomb (such as a side chamber, an island in a mercury river, etc.), the GM should provide an alternative in the narrative (such as a Talisman Sect rest boundary).

### Sleep Deprivation

If a player cannot take a long rest for over 24 hours, they gain one level of "Fatigue" (all checks −1). Each additional 24 hours without rest, Fatigue level +1. Fatigue is fully removed after one complete long rest.

---

# Appendix

## Appendix A: Core Formula Quick Reference

| Formula | Content |
|------|------|
| General Check | 2d10 + Attribute Value + Skill Level + Equipment Modifier vs DC |
| Contest Check | 2d10 + Attribute Value + Skill Level vs Target 2d10 + Attribute Value + Skill Level |
| Martial Art Attack | 2d10 + Agility (身) + Martial Art Level vs Target DEF |
| General Attack | 2d10 + Agility (身) + Brawling Skill vs Target DEF |
| Health Points (HP) | Agility (身) × 3 + 10 (+ Martial Master talent +5) + per-level growth |
| Qi Pool (QP) | True Qi (氣) × 2 + 5 (+ Daoist talent +3) + per-level growth |
| Defense (DEF) | Agility (身) + Equipment Defense Modifier (highest) + Iron Body Modifier |
| Initiative (INIT) | Agility (身) + floor(Courage (膽) ÷ 2) (fixed value) |

## Appendix B: DC Ladder Quick Reference

| DC | Difficulty | Typical Use |
|:---:|------|------|
| 6 | Trivial | Daily actions |
| 10 | Simple | Imperial Mausoleum acupoint location, basic talismans |
| 14 | Moderate | General's Tomb acupoint location, Evil-Dispelling Talisman |
| 18 | Hard | Hidden ancient tomb acupoint location, Corpse-Suppressing Talisman |
| 22 | Very Hard | Decoy tomb identification, Five-Thunder Talisman, Unrotting Bone conversation |
| 26 | Legendary | Sealing a corpse-raising ground |
| 30 | Nearly Impossible | Single-handedly suppressing a Dragon Vein Sha Acupoint |

## Appendix C: Character Creation Quick Checklist

```
□ Step 1: Background Origin (d8 or choose)
□ Step 2: Attribute Allocation (25 points, single attribute 1–9)
□ Step 3: Skill Allocation (20 points, single skill cap Lv3)
□ Step 4: Primary Heritage (Daoist / Martial / Touch-Gold / Maoshan)
□ Step 5: Spell Heritage (Maoshan minor study or none)
□ Step 6: Affiliated Sect (Dragon-Shaker / Xuan Kong / Talisman / Mountain-Mover)
□ Step 7: Signature Technique (Mastery / Economy / Amplify / Original)
□ Step 8: First Talisman (roleplay)
□ Step 9: The Worst Coffin (roleplay)
□ Step 10: Team Role (Eye / Vanguard / Coffin-Guard / Talisman-Drawer / Negotiator / Rear-Guard)
□ Calculate Derived Attributes (HP/QP/FT/YY/PR/DEF/INIT)
□ Purchase Equipment (starting funds 50 silver dollars — see note below)

> **Starting Funds:** Each newly created Earth Master begins with **50 silver dollars**. This money is used to buy equipment and supplies before entering the tomb. It is recommended to first secure a fire starter (light source), at least one weapon, and basic supplies, then spend the rest on other equipment. The GM may adjust based on the character's Background Origin (±20 silver dollars).
```

---

> **Earth Master TRPG Player Rulebook v1.0**
>
> "The compass is still spinning. So is your heartbeat. Take a deep breath — the coffin lid is about to open."
>
> Tabletop Rules Studio © 2025
