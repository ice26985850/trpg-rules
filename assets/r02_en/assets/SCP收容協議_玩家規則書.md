# SCP: CONTAINMENT PROTOCOL
## SCP Foundation TRPG Rulebook — Player's Manual v1.0

---

> *"Secure. Contain. Protect."*
> — Foundation Motto

**Dice System**: d100 Roll-Under (percentile)
**Tabletop Rules Studio** · June 2026

---

## Table of Contents

- [Chapter 1: Core Rules](#chapter-1-core-rules)
- [Chapter 2: Character Creation](#chapter-2-character-creation)
- [Chapter 3: Combat Rules](#chapter-3-combat-rules)
- [Appendix](#appendix)

---

# Chapter 1: Core Rules

## 1.1 Dice System

### Core Formula

This game uses the **d100 Roll-Under** system. All checks follow a unified formula:

```
d100 ≤ Target Number (TN) → Success
Success Rate = TN%
```

**Target Number Composition**:
```
TN = Base Attribute + Skill + Difficulty Modifier ± Circumstance Adjustment
```

The TN range is fixed at 1–99. A roll of 01 = automatic success (Critical), a roll of 00 = automatic failure (Catastrophic Failure).

### Degree of Success System

| Roll Range | Degree of Success | Effect |
|---------|--------|------|
| 01 | Legendary Success | Automatic success + extra gain (double damage / critical intel / flawless completion) |
| 02 – TN×0.2 | Exceptional Success | High-quality completion, with additional effect or information |
| TN×0.2+1 – TN×0.5 | Solid Success | Standard success, fully achieves the goal |
| TN×0.5+1 – TN | Ordinary Success | Barely completes, may carry a small cost |
| TN+1 – 99 | Failure | Goal not achieved |
| 00 | Catastrophic Failure | Automatic failure + severe negative consequence |

**Example** (TN = 60):
- Roll 01 → Legendary / 02–12 → Exceptional / 13–30 → Solid / 31–60 → Ordinary / 61–99 → Failure / 00 → Catastrophic

### Advantage/Disadvantage

| Status | Rule | Equivalent Effect |
|------|------|---------|
| Advantage (ADV) | Roll 2 sets of d10 to form d100, take the most favorable result | +16% effective success rate |
| Disadvantage (DIS) | Roll 2 sets of d10 to form d100, take the least favorable result | -16% effective success rate |
| Double Advantage | Roll 3 sets, take the best | +23% |
| Double Disadvantage | Roll 3 sets, take the worst | -23% |
| Advantage + Disadvantage | Cancel out, normal single die | — |

---

## 1.2 Attribute System

### Seven Attributes

#### Physical Dimension

| Attribute | Abbr. | Design Intent |
|------|------|---------|
| **Strength** | STR | Muscular output, melee damage, carrying load, breaking doors / lockpicking |
| **Agility** | AGI | Full-body coordination, evasion, initiative, stealth, piloting, fine manipulation |
| **Endurance** | END | Physical resilience, HP base, toxin resistance, sustained action |

#### Mental Dimension

| Attribute | Abbr. | Design Intent |
|------|------|---------|
| **Intellect** | INT | Logical reasoning, knowledge retrieval, technical operation, research analysis |
| **Perception** | PER | Environmental observation, threat detection, reading people, searching, seeing through disguises |
| **Willpower** | WIL | Mental resilience, SAN base, resisting cognitohazards, overcoming fear |

#### Social Dimension

| Attribute | Abbr. | Design Intent |
|------|------|---------|
| **Presence** | PRE | Persuasiveness, intimidation, leadership, deception, reassurance, performance |

### Value System

- **Range**: 10–65 (human baseline; can break through to 80 later)
- **Total Point Buy**: 190 points (freely distributed across 7 attributes, minimum 10 and maximum 65 per attribute)
- **Standard Array** (quick creation): STR 50 / AGI 44 / END 38 / INT 32 / PER 26 / WIL 20 / PRE 14
- **Alternate Array**: 55, 50, 45, 40, 35, 30, 25 (distributed across 7 attributes)
- **Random Dossier**: 7×(3d10×2+10), range 16–70, mean ~43

### Attribute Tier Semantics

| Attribute Value | Tier | Narrative Meaning |
|--------|------|---------|
| 10–15 | Fragile | Obvious weakness |
| 16–25 | Below Average | Untrained weak point |
| 26–35 | Average | Ordinary adult level |
| 36–45 | Above Average | Trained or talented |
| 46–55 | Excellent | Foundation professional standard |
| 56–65 | Exceptional | Top of the field — MTF elite, lead researcher |
| 66–80 | Legendary | Human limit — O5 directly-assigned agents |

### Derived Attributes

| Derived Attribute | Formula | Description |
|---------|------|------|
| **Health Points (HP)** | END + Class HP Bonus + Level Growth | See Chapter 2 class table. HP = 0 enters Near-Death |
| **Sanity (SAN)** | 50 + WIL (max 99) | Long-term mental stability. SAN ≤ 0 = Permanent Insanity |
| **Stress (SP)** | Starts at 0, max 100 | Short-term psychological stress accumulation. SP ≥ SAN triggers Breakdown |
| **Initiative (INIT)** | AGI + PER (optional class tweak) | Determines combat action order |
| **Movement (MOV)** | (STR + AGI) / 2 meters / move action | Base movement distance per move action |
| **Carrying Load** | STR × 2 kg | Comfortable load limit |

---

## 1.3 Skill System

### Skill List (24 Skills)

#### Combat

| Skill | Attribute | Typical Use |
|------|------|---------|
| Firearms | AGI | Pistols, rifles, submachine guns, shotguns |
| Heavy Weapons | AGI | Machine guns, grenade launchers, rocket launchers |
| Melee | STR | Unarmed combat, blades, blunt weapons, stun batons |
| Throwing | AGI | Grenades, throwing knives, thrown containment devices |
| Dodge | AGI | Evading attacks, finding cover, breaking grapples |

#### Technical

| Skill | Attribute | Typical Use |
|------|------|---------|
| Computers | INT | Hacking systems, bypassing firewalls, data recovery |
| Engineering | INT | Repairing equipment, breaching obstacles, building makeshift devices |
| Demolitions | INT | Setting / disarming explosives |
| Medicine | INT | First aid, surgery, identifying drugs / toxins |
| Cryptography | INT | Deciphering codes, analyzing anomalous symbols, identifying memetic encoding |
| Piloting | AGI | Driving vehicles, helicopters, anomalous craft |

#### Knowledge

| Skill | Attribute | Typical Use |
|------|------|---------|
| Anomalistics | INT | SCP identification, Hume Field theory, containment protocols |
| Foundation Lore | INT | Foundation history, notable events |
| Occult | INT | Ritual knowledge, GOI belief systems |
| Science | INT | Physics, chemistry, biology — "normal" science |
| Linguistics | INT | Translating unknown languages, memetic language patterns |

#### Social

| Skill | Attribute | Typical Use |
|------|------|---------|
| Persuasion | PRE | Diplomatic negotiation, civilian reassurance |
| Deception | PRE | Disguising identity, misleading enemies |
| Interrogation | PRE | Extracting information from captives / witnesses |
| Leadership | PRE | Battlefield command, boosting morale |

#### Survival

| Skill | Attribute | Typical Use |
|------|------|---------|
| Stealth | AGI | Concealed movement, disguise, tailing |
| Observation | PER | Spotting ambushes, identifying anomalous traces |
| Survival | END | Wilderness survival, tracking, resisting extreme environments |
| Resist | WIL | Resisting fear / memes / cognitohazards |

### Skill Proficiency (6 Tiers)

| Tier | Skill Value | Name | Narrative Meaning |
|------|--------|------|---------|
| 0 | 1–20 | Novice | Basic training or amateur attempt |
| 1 | 21–35 | Apprentice | Formally trained, can complete basic tasks independently |
| 2 | 36–50 | Proficient | Reliable professional level, Foundation agent standard |
| 3 | 51–65 | Expert | Skill authority within the team |
| 4 | 66–80 | Master | Widely recognized top of the field |
| 5 | 81–99 | Legendary | Human limit, usually an NPC |

### Attribute–Skill Mapping Quick Reference

```
STR — Melee
AGI — Firearms, Heavy Weapons, Throwing, Dodge, Piloting, Stealth
END — Survival
INT — Computers, Engineering, Demolitions, Medicine, Cryptography, Anomalistics, Foundation Lore, Occult, Science, Linguistics
PER — Observation
WIL — Resist
PRE — Persuasion, Deception, Interrogation, Leadership
```

---

## 1.4 Check Rules

### Standard Check Procedure

1. GM determines the target attribute + skill (or bare attribute)
2. GM sets the Difficulty Modifier (default ±0)
3. Player calculates TN = Attribute Value + Skill Value + Difficulty Modifier ± Circumstance Adjustment
4. Player rolls d100
5. Compare the die result with TN to determine the Degree of Success
6. GM describes the outcome based on the Degree of Success

### Difficulty Modifier Table

| Difficulty | TN Modifier | Description | Example |
|------|---------|------|------|
| Trivial | +60 | Almost impossible to fail | Routine work using a professional skill |
| Easy | +30 | Clearly easy | Finding something in a well-lit room |
| Slightly Easy | +10 | Slight advantage | Prying open an old wooden door with a crowbar |
| **Standard** | ±0 | Requires professional training | Hacking a standard security network |
| Challenging | -20 | Significant pressure | Performing emergency first aid under fire |
| Hard | -40 | High pressure / high complexity | Decrypting anomalous code under a cognitohazard's influence |
| Very Hard | -60 | Near human limit | Stabilizing a Keter breach solo within 30 seconds |
| Legendary | -80 | Almost impossible | Talking an activated anomaly into stopping |

### Success Probability Reference

Assume a professional agent (Attribute 40 + Skill 35 = base TN 75):

| Difficulty | TN Modifier | Final TN | Success Rate |
|------|---------|---------|--------|
| Easy | +30 | 99 | 99% |
| Slightly Easy | +10 | 85 | 85% |
| **Standard** | ±0 | **75** | **75%** |
| Challenging | -20 | 55 | 55% |
| Hard | -40 | 35 | 35% |
| Very Hard | -60 | 15 | 15% |

### Opposed Check

When two characters' actions directly conflict: each rolls d100 ≤ their own TN, then compare the Degree of Success.

- Both succeed → higher Degree of Success wins
- One succeeds, one fails → the successful side wins
- Both fail → tie / no progress

### Assist & Team

**Assist**: The helper successfully rolls d100 ≤ their own TN → the primary actor gains +10 TN (stackable up to 2 people, i.e. +20).

**Team Skill Challenge**: At least half of the members succeed → team success.

**Extended Contest (Skill Challenge)**: Accumulate N successes (usually 3–5) while allowing M failures (usually 2–3).

---

## 1.5 Sanity & Stress Dual-Track System

> *"SAN is how long you can hold on. SP is how scared you are right now."*

### SAN (Sanity)

```
SAN Maximum = 50 + WIL
Starting SAN = Maximum (starts at full)
Range: 60 (WIL=10) – 99 (capped)
```

The SAN Check takes the form `d100 ≤ Current SAN`.

#### SAN Damage Sources

| Source | SAN Damage | Example |
|------|---------|------|
| Mild cognitohazard | 1d4 | Seeing a low-risk anomalous image |
| Moderate cognitohazard | 2d6 | First encounter with a Euclid-class SCP |
| Severe cognitohazard | 3d8 | Witnessing a Keter-class breach containment |
| Extreme cognitohazard | 4d10 | Directly exposed to a memetic entity |
| Witnessing a teammate's death (within 10m) | 1d6 | — |
| Witnessing a teammate's anomalous transformation | 2d6 | — |
| Forced to sacrifice others | 1d4 | Cumulative effect |
| Long-term stress | 1d4 per week | Sustained containment-breach environment |

#### SAN Thresholds & States

| SAN Remaining | State | Effect |
|----------|------|------|
| 100%–76% | Stable | Functions normally |
| 75%–51% | Unsettled | Stress checks at DIS; subtle hallucinations / paranoia |
| 50%–26% | Shaken | SP +1 per round; cannot gain ADV on WIL checks |
| 25%–1% | On the Brink | All checks at DIS; may develop hostility toward teammates |
| ≤ 0 | Permanently Insane | Character becomes an NPC |

#### SAN Recovery

| Method | Recovery | Condition |
|------|--------|------|
| Safe rest (on-site) | 1d4/day | Threat-free environment |
| Psychological counseling | 1d6/session | At most 1 per week |
| Amnestics (Class B) | 2d6 | Erases traumatic memories. Roll d100 ≤ INT: success loses no experience, failure reduces a random skill by -1d10 |
| Completing a major containment mission | 1d8 | At GM's discretion |
| Memetic Resistance Drug | 1d4 | Limited to 1 per week; overdose has side effects (consecutive use → d100 ≤ END or permanent INT -1d3) |

#### Amnestic Classification Rules

| Class | SAN Recovery | Side Effect | Check | Use Case |
|------|---------|--------|------|---------|
| **Class A** (Short-Term) | No recovery (SP only cleared) | Loses details of the current mission's memory; relevant skill -5 at the start of next mission | Automatic | Post-standard-mission processing |
| **Class B** (Long-Term) | 2d6 SAN | d100 ≤ INT success = no loss, failure reduces a random skill by -1d10; loses the entire mission's memory | Requires CL 3+ authorization | After traumatic events |
| **Class C** (Personality Reconstruction) | 3d6 SAN | All skills -2d10; permanently loses 1d3 skills (reduced to 0); personality may change | Requires Ethics Committee approval | Memetic infection / last resort |

### SP (Stress)

```
SP starts at 0, max = 100

SP Auto-Gain triggers:
· +1 per round in combat
· Suppressive fire +1d4
· Witnessing a cognitohazard +1d6
· Teammate panic +1d4
· Suffering a critical wound +2
· Being alone in total darkness +1d4/round
· Learning of a memetic / infohazard +1d6
```

#### Breakdown Check

When **SP ≥ SAN**, a Breakdown Check is triggered:
`d100 ≤ SAN - SP`

- Success → SP halved, gains "Tense" state for 1 round
- Failure → roll d100 on the Breakdown Table to determine manifestation

#### Breakdown Table (d100)

| d100 | Manifestation | Duration |
|------|------|------|
| 01–15 | **Catatonia**: unable to act / speak | 1d4 rounds |
| 16–30 | **Flight**: flee from the threat at full speed | 1d6 rounds |
| 31–45 | **Combat Frenzy**: randomly attacks the nearest target (50% friendly) | 1d4 rounds |
| 46–60 | **Scream & Exposure**: reveals position | 1 round |
| 61–70 | **Hallucination**: GM provides false information | 1d6 rounds |
| 71–80 | **Aphasia**: unable to speak / understand language | 1d4 hours |
| 81–90 | **Amnesia**: forgets the last 1d6 hours | 1d4 hours |
| 91–95 | **Personality Fragment Replacement**: overwritten by a random personality | 1d6 days |
| 96–99 | **Violent Psychosis**: indiscriminate violence | 1d6 hours |
| 00 | **Psychogenic Death**: cardiac arrest | Permanent |

#### SP Relief

| Method | SP Reduction | Condition |
|------|---------|------|
| Taking no action for a turn | -1d4 | No direct threat |
| Teammate "Reassurance" (PRE + Leadership check) | -2d4 | Consumes a standard action |
| Leaving the direct threat area | -1d6/round | Until SP = SAN/2 |
| Post-mission rest (safe environment, 8 hours) | Reduced to 0 | Full reset |

---

## 1.6 Security Clearance Level

The Foundation controls information access through clearance levels. The level is a narrative attribute and does not automatically increase with experience points.

| CL | Name | Information Access | Typical Personnel |
|----|------|----------|---------|
| 0 | Unrestricted | Public information | Support staff / D-Class / temporary workers |
| 1 | Confidential | Routine Site operations | Junior researchers / guards |
| 2 | Secret | Routine SCPs | Field agents / MTF / senior researchers |
| 3 | Top Secret | High-risk SCPs / MTF details | Site Director / MTF commander |
| 4 | Eyes Only | Strategy / Thaumiel | Regional Director / O5 Liaison |
| 5 | Samael | Everything | O5 Council |

### Overclearance Operation

| Overextend | TN Modifier | Success Consequence | Failure Consequence |
|------|---------|----------|----------|
| +1 level | -20 | Obtain information, system logs it | Flagged "Pending Review" |
| +2 levels | -40 | Triggers internal security protocol | Security team dispatched |
| +3 levels | -60 | O5 takes notice of the anomaly | MTF dispatched + formal hearing |
| +4 levels | DIS + -80 | Extremely low probability | Arrest + possible amnestics |

### Clearance & SAN Interaction

- **Promotion Cost**: Each level gained requires a SAN Check; failure = SAN-1 — you read what you shouldn't have
- **Lv.4 Cost**: SAN maximum permanently -10
- **Lv.5 Cost**: SAN maximum permanently -30
- **Emergency Overclearance (Protocol 42-Solomon)**: Temporary +2 CL/scene; cost SAN-1d3 + post-operation O5 hearing

---
# Chapter 2: Character Creation

## 2.1 Character Creation (9 Steps)

1. **Concept**: What is your role's position within the Foundation? Why did they join?
2. **Choose Role**: Select from the Seven Roles (see §2.2)
3. **Allocate Attributes**: 190 point-buy, range 10–65 (see §1.2)
4. **Choose Humanoid Classification** (see §2.3)
5. **Allocate Skill Points**: Gain skill points per class template (see §2.4)
6. **Calculate Derived Attributes**: HP, SAN, INIT, MOV
7. **Choose Subclass** (takes effect at Lv.3)
8. **Initial Equipment Issue**: Acquire equipment by Security Clearance Level
9. **Fill in Background & Department Relations**: GM Review

---

## 2.2 The Seven Roles

| # | Role | Focus | HP Bonus | HP/Level | Core Attribute | Starting Clearance |
|---|------|-------|----------|----------|----------------|--------------------|
| 1 | **MTF Operative** | Combat/Containment/Assault | +20 | +3 | STR | Lv.2 |
| 2 | **Field Agent** | Investigation/Infiltration/Intelligence | +15 | +3 | AGI | Lv.2 |
| 3 | **Security Agent** | Defense/Protection/Vigilance | +15 | +3 | PER | Lv.2 |
| 4 | **Technical Specialist** | Engineering/Hacking/Equipment | +10 | +2 | INT | Lv.3 |
| 5 | **Medical Specialist** | Treatment/Psychology/Toxicology | +10 | +2 | INT | Lv.3 |
| 6 | **Researcher** | Knowledge/Analysis/Containment Procedures | +5 | +1 | INT | Lv.3 |
| 7 | **D-Class Personnel** | Expendable/Survival/Desperate | +0 | +1 | Any | Lv.0 |

**Unified HP Formula**:
```
HP = END + Class HP Bonus + Level Growth × (Level - 1)
```

**HP Range Quick Reference** (END=38 example):

| Role | Lv.1 | Lv.5 | Lv.10 |
|------|------|------|-------|
| MTF Operative | 58 | 70 | 85 |
| Field Agent | 53 | 65 | 80 |
| Security Agent | 53 | 65 | 80 |
| Technical Specialist | 48 | 56 | 66 |
| Medical Specialist | 48 | 56 | 66 |
| Researcher | 43 | 47 | 52 |
| D-Class Personnel | 38 | 42 | 47 |

### Role Details

#### MTF Operative (Mobile Task Force Operative)

**Core Resource**: Tactical Points (TP), pool size = 3 + ⌊Level/2⌋, resets each mission.

| Level | Ability |
|-------|---------|
| 1 | **Combat Training**: Choose any 2 of Firearms, Melee, Dodge +10 Proficiency |
| 1 | **Tactical Points**: Gain TP resource pool |
| 2 | **Quick Reload**: Reload reduced to a quick action |
| 3 | **Subclass**: Assault / Fire Support / Melee Expert / Tactical Command |
| 5 | **Double Strike**: Spend 2 TP, two standard attacks in the same round (second at DIS) |
| 7 | **Battlefield Adaptation**: All attacks gain ADV when HP < 50% |
| 9 | **Tactical Master**: TP pool doubled |

#### Field Agent (Field Agent)

**Core Resource**: Adaptability Points (AP), pool size = 3 + ⌊Level/2⌋, resets each mission.

| Level | Ability |
|-------|---------|
| 1 | **Investigation Training**: Choose any 2 of Stealth, Observation, Deception, Persuasion +10 Proficiency |
| 1 | **Adaptability Points**: Gain AP resource pool |
| 2 | **Skilled Disguise**: Identity disguise checks at ADV in non-combat scenes |
| 3 | **Subclass**: Infiltrator / Negotiator / Scout / Disguise Specialist |
| 5 | **Quick Thinking**: Spend 1 AP, immediately reroll after a failure |
| 7 | **Sixth Sense**: Always ADV on Observation checks for ambushes/traps |
| 9 | **Thorough Preparation**: AP pool doubled |

#### Security Agent (Security Agent)

**Core Resource**: Vigilance Points (VP), pool size = 3 + ⌊Level/2⌋, resets each mission.

| Level | Ability |
|-------|---------|
| 1 | **Guard Training**: Choose any 2 of Observation, Melee, Firearms, Dodge +10 |
| 1 | **Vigilance Points**: Gain VP resource pool |
| 2 | **Opportunity Specialist**: 2 reactions per round (one of which must be an opportunity attack) |
| 3 | **Subclass**: Site Security / VIP Protection / Tactical Response / Interrogation Specialist |
| 5 | **Guardian**: Spend 1 VP to take damage for an ally within 5m |
| 7 | **Immovable**: Behind cover and unmoved → enemies gain Double Disadvantage |
| 9 | **Vigilance Network**: VP pool doubled |

#### Researcher (Researcher)

**Core Resource**: Insight Points (IP), pool size = 3 + ⌊Level/2⌋, resets each mission.

| Level | Ability |
|-------|---------|
| 1 | **Academic Training**: Choose any 3 of Anomalistics, Science, Cryptography, Foundation Lore, Linguistics +10 |
| 1 | **Insight Points**: Gain IP resource pool |
| 2 | **Quick Analysis**: Evaluation checks for anomalies reduced one tier |
| 3 | **Subclass**: Anomalist / Memeticist / Reality Theorist / Engineer |
| 5 | **Weakness Discovery**: Spend 2 IP to reveal anomaly weakness (all relevant team checks +20 TN) |
| 7 | **Scholar's Intuition**: Knowledge checks with TN ≤ INT → automatic success |
| 9 | **Erudite**: IP pool doubled |

#### Technical Specialist (Technical Specialist)

**Core Resource**: Technical Points (TTP), pool size = 3 + ⌊Level/2⌋, resets each mission. Note the distinction from the MTF Tactical Points (TP).

| Level | Ability |
|-------|---------|
| 1 | **Technical Training**: Choose any 2 of Computers, Engineering, Demolitions, Cryptography +10 |
| 1 | **Technical Points**: Gain TTP resource pool |
| 2 | **Quick Repair**: Repair checks reduced one tier |
| 3 | **Subclass**: Hacker / Demolitionist / Mechanic / Anomaly Technician |
| 5 | **Overload**: Spend 2 TTP, double equipment effect for 1d4 rounds |
| 7 | **Eureka**: After a failed Technical check, spend 1 TTP to reroll |
| 9 | **Technical Prodigy**: TTP pool doubled |

#### Medical Specialist (Medical Specialist)

**Core Resource**: Medical Supplies (MS), pool size = 3 + ⌊Level/2⌋, resets each mission.

| Level | Ability |
|-------|---------|
| 1 | **Medical Training**: Choose any 2 of Medicine, Science, Resist +10 |
| 1 | **Medical Supplies**: Gain MS resource pool |
| 2 | **Battlefield Triage**: First aid action reduced to a quick action |
| 3 | **Subclass**: Surgeon / Psychiatrist / Toxicologist / Anomaly Biologist |
| 5 | **Emergency Surgery**: Spend 2 MS, reverse permanent effects of Critical Wounds |
| 7 | **Group Treatment**: Spend 1 MS, all allies within 10m recover 1d6 HP |
| 9 | **Medical Director**: MS pool doubled |

#### D-Class Personnel (D-Class Personnel)

**Core Resource**: Luck Points (LP), pool size = 3 (cannot grow), resets each mission.

| Level | Ability |
|-------|---------|
| 1 | **Desperate Instinct**: After HP < 50%, Movement +3m |
| 1 | **Luck Points**: Gain LP resource pool |
| 2 | **Scrap Crafting**: Can craft temporary tools from scrap (d100 ≤ INT+Survival) |
| 3 | **Unobtrusive**: In non-combat scenes, enemies prioritize attacking "threatening" targets |
| 5 | **Last Resort**: Triggers the full three-stage check (see §2.8) |
| 7 | **Freak Luck**: Spend 1 LP to reroll a failure as ADV |
| 9 | **Legendary D-Class**: Unlocks the "Nine Lives" mark (see §2.8) |

---

## 2.3 Humanoid Classification

| Classification | Definition | PC Available |
|---------------|------------|--------------|
| **Baseline Human** | Standard Homo Sapiens | ✅ Default |
| **Augmented Human** | Foundation-approved genetic/mechanical augmentation | ✅ Requires Clearance Lv.4+ |
| **Thaumiel-Class Humanoid Anomaly** | Mild anomaly that contributes to containment | ✅ Special Clearance |
| **Euclid-Class Humanoid Anomaly** | Moderate danger but communicative | ❌ NPC |
| **Keter-Class Humanoid Anomaly** | Highly dangerous and non-communicative | ❌ Hostile NPC |

Aside from Baseline Humans, the other classifications include attribute adjustments and special abilities:

| Classification | Attribute Adjustment | Special Ability | Clearance Requirement |
|---------------|----------------------|----------------|-----------------------|
| **Augmented Human** | Any one physical attribute +10, any one mental attribute -5 | Choose one biochemical augmentation (Night Vision / Subdermal Armor DR1 / Accelerated Healing +1d6 HP per long rest) | CL.4+ Approval |
| **Thaumiel-Class Humanoid Anomaly** | WIL -15 (the cost of long-term confinement), choose one attribute +10 | One mild anomalous ability (negotiated by GM and player, e.g.: sense emotions within 20m / read memory fragments from last 24h by touching an object / passively sense Hume Field) | O5 Special Clearance + Ethics Committee unanimous vote |
| **Mekhanite Augment** | STR +5 / END +5 / PRE -5 | Mechanical prosthetic (Melee damage +2, can embed one small tool) | CL.3+ Approval |
| **Neo-Sarkic Adapt** | END +5 / AGI +5 / PRE -10 | Biological adaptation (each long rest may redistribute 5 attribute points: move from one attribute to another, not exceeding the 65 cap) | CL.4+ Approval |

GM Note: Non-Baseline Human PCs face prejudice within the Foundation. NPCs' initial attitude toward Thaumiel-Class PCs is -2 (fear/distrust).

---

## 2.4 Starting Skill Points

| Class Template | Skill Points | Notes |
|---------------|--------------|-------|
| MTF Operative | 200 + INT | Combat + Tactics focused |
| Field Agent | 180 + INT | Balanced |
| Security Agent | 160 + INT | Observation + Melee focused |
| Researcher | 240 + INT | Technical + Knowledge focused |
| Technical Specialist | 200 + INT | Technical focused |
| Medical Specialist | 200 + INT | Medicine + Knowledge focused |
| D-Class Personnel | 120 + INT | Survival-type; some skills may be unexpectedly high |

Skill points are invested into the 24 skills, following the 6-tier proficiency rule. Checks without a corresponding skill use half the attribute value as TN.

**Skill Level Cap** (1:1 investment, each 1 skill point = +1 skill value):

| Character Level | Single Skill Cap | Notes |
|-----------------|-----------------|-------|
| Lv.1–2 | 50 (Proficient) | Starting characters cannot reach Expert |
| Lv.3–4 | 65 (Expert) | Can specialize after subclass unlock |
| Lv.5–6 | 75 | — |
| Lv.7–8 | 85 | — |
| Lv.9–10 | 99 (Legendary) | Peak characters can reach the human limit |

**Skill Points Gained Per Level**: At Lv.2 and Lv.6, gain = Starting Skill Points × 0.3 (rounded down). Example: MTF starts with 232 points → gains 69 at Lv.2, gains 69 at Lv.6.

---

## 2.5 Growth & Leveling

### Experience Points Table

| Level | Cumulative XP | XP to Level Up | Per-Level Benefit |
|-------|---------------|----------------|-------------------|
| 1 | 0 | — | Starting role ability + skill points |
| 2 | 500 | 500 | +skill points |
| 3 | 1,500 | 1,000 | Subclass choice |
| 4 | 3,000 | 1,500 | Attribute increase (+5 or +3+3) |
| 5 | 5,000 | 2,000 | Role tier ability |
| 6 | 7,500 | 2,500 | +skill points |
| 7 | 10,500 | 3,000 | Role tier ability |
| 8 | 14,000 | 3,500 | Attribute increase (+5 or +3+3) |
| 9 | 18,000 | 4,000 | Role tier ability (resource pool doubled) |
| 10 | 23,000 | 5,000 | Peak ability |

**Leveling Pace** (reference: ~1,000–2,000 XP per mission):
- Lv.1→5: ~4–6 game sessions (fast-paced growth)
- Lv.5→8: ~6–8 game sessions (mid-game consolidation)
- Lv.8→10: ~5–7 game sessions (endgame sprint)
- Full 1→10 campaign: ~15–21 game sessions

### XP Sources

- **Mission Completion**: See the mission reward table (includes base XP value)
- **Extra SCP Containment**: +300–600 XP per additional SCP contained
- **Character Development**: Major personal choice/sacrifice +300–800 XP
- **Site Contribution**: Organizational management achievement +200–500 XP
- **Excellent Mission Report**: +200 XP (limited to the character who writes the report)

### Multiclass Rules

A character may, upon leveling up, choose to gain a Level 1 ability of another role instead of the current level's improvement. Requirements:

1. **Attribute Requirement**: Meet the target role's core attribute ≥ 40
2. **Narrative Justification**: Have a plausible story reason (e.g.: a Researcher accepts combat training after multiple field missions)
3. **Independent Resource Pools**: Each role's resource pools are tracked separately and cannot be mixed
4. **HP Growth**: Use the highest per-level HP growth value among all roles
5. **Restriction**: At most 1 additional multiclass role (i.e. maximum 2 roles). Subclasses cannot be combined — a subclass can only be gained from one role

**Security Clearance Level takes the highest value among multiclasses.**

### Security Clearance Level Promotion (Independent of Experience)

Security Clearance Level does not automatically increase with character level. Requires:
1. Character level requirement met (Lv.4→can raise to CL.3 / Lv.8→can raise to CL.4 / Lv.10→can raise to CL.5)
2. Site Security ≥ 40
3. O5 Attention ≤ 6
4. No severe departmental hostility
5. Complete the "Clearance Upgrade Evaluation Mission" (customized by GM)

---

## 2.6 Equipment & Economy

### Currency System

The Foundation uses a triple economy system:

| Currency | Acquisition Method | Usage |
|------|---------|------|
| **Credit Points (CR)** | Mission rewards, Site budget | Purchase standard equipment |
| **Security Assets (SA)** | Relations with Security Department | Exchange for restricted-tier equipment |
| **Political Capital (PC)** | Relations with O5/Ethics Committee | Access to anomalous item usage |

#### Mission Reward Table

| Mission Difficulty | Base CR Reward | SA Gained | PC Gained | Base XP |
|---------|-----------|---------|---------|---------|
| Routine (no SCP breach) | 400–600 | 1 | 0 | 500 |
| Challenging (Safe-class breach) | 700–1,000 | 2 | 0 | 800 |
| Hard (Euclid-class breach) | 1,200–1,800 | 3–4 | 1 | 1,200 |
| Extreme (Keter-class/Site crisis) | 2,000–3,000 | 5–7 | 2–3 | 1,800 |
| Apocalyptic (XK-class scenario) | 5,000+ | 10+ | 5+ | 3,000 |

**Bonuses & Adjustments**:
- No casualties: CR +20%
- All SCPs successfully contained: additional SA +1
- Exposing internal corruption/security vulnerabilities: PC +1
- Civilian casualties/exposure: CR -50%, O5 Attention +2
- D-Class personnel consumed beyond quota: CR -10%/person

**SA and Department Relation Conversion**: Sum of all department relation values ÷ 2 (rounded down) = additional SA income per mission. Example: Security Department +4 + Field Operations +2 = total 6 → additional +3 SA/mission.

**PC and Relation Conversion**: Ethics Committee relation value ≥ +5 → gain +1 PC per 2 missions. Each 1 level decrease in O5 Attention (from initial value) → gain +1 PC.

### Weapon Quick Reference

| Weapon | Damage | Attribute | Ammo | Special |
|------|------|------|------|------|
| Pistol (9mm) | 1d8 Piercing | Firearms | 15 | Concealed |
| Submachine Gun | 1d8 Piercing | Firearms | 30 | Automatic Fire |
| Assault Rifle | 1d10 Piercing | Firearms | 30 | Automatic Fire |
| Shotgun | 2d6 Piercing | Firearms | 8 | Close-range ADV |
| Sniper Rifle | 2d10 Piercing | Firearms | 5 | Can designate body part after aiming |
| Combat Knife | 1d6 Slashing | Melee | — | Concealed |
| Stun Baton | 1d4 Bludgeoning | Melee | 5 uses | Paralysis (1d4 rounds) |
| Fragmentation Grenade | 3d6 Piercing | Throwing | 1 | 10m AoE |

### Armor Quick Reference

| Armor | DR (Piercing) | DR (Slashing) | DR (Bludgeoning) | Special |
|------|-----------|-----------|-----------|------|
| Light Load-bearing Gear | 1 | 1 | 0 | No penalty |
| Tactical Vest | 2 | 2 | 1 | Standard issue |
| Ceramic Plate | 3 | 2 | 2 | Can be inserted into tactical vest |
| Full Body Armor | 4 | 3 | 2 | AGI -5 |
| Bomb Disposal Armor | 5 | 5 | 5 | AGI -10, MOV -3m |
| Hazmat Suit | 0 | 5 (Chemical) | 0 | Sealed, Thermal weakness |

### Anomalous Item Usage Rules

Anomalous items are graded by risk:

| Tier | Approval | Check | Risk |
|------|------|------|------|
| **Green** (Stable) | CL.3+ | Automatic | Almost none |
| **Yellow** (Controllable) | CL.4+ | d100 ≤ relevant skill | Low probability side effects |
| **Red** (High Risk) | CL.5+ | d100 ≤ SAN-20 | Moderate probability backlash |
| **Black** (Uncontrolled) | O5 unanimous vote | d100 ≤ 01 | Every use is a gamble |

### Vehicle Quick Reference

| Vehicle | MOV (Combat) | MOV (Cruise) | Crew | Armor (DR) | Special |
|------|----------|----------|------|---------|------|
| Foundation Jeep | 20m/round | 120km/h | 1+4 | Piercing DR 3 | Communications array |
| APC Armored Personnel Carrier | 12m/round | 80km/h | 2+8 | All DR 8 | Sealed, Night vision |
| Helicopter UH-60 | 50m/round | 280km/h | 2+12 | Piercing DR 2 | Aerial, Winch |
| Motorcycle | 25m/round | 160km/h | 1+1 | None | Narrow alley access |

**Piloting Check** (d100 ≤ AGI + Piloting skill):
- Standard road conditions: Standard (±0)
- Complex terrain/chase: Challenging (-20)
- Driving under fire: Hard (-40)
- Collision: deals 2d10 ~ 6d10 Bludgeoning damage (depending on speed); crew must make d100 ≤ END or become stunned

### Initial Issue Table

| Identity | Below Lv.2 | Lv.3–4 | Lv.5+ |
|------|----------|--------|-------|
| MTF Operative | Assault Rifle + Tactical Vest + First Aid Kit ×1 + Comms Device | + Fragmentation Grenade ×2 + Night Vision Goggles | + Ceramic Plate + Adrenaline Syringe ×1 |
| Field Agent | Pistol + Light Load-bearing Gear + Forged Credentials + Lockpicking Tools | + Submachine Gun + Comms Device | + Suppressor + Smoke Grenade ×2 |
| Security Agent | Pistol + Tactical Vest + Comms Device + Handcuffs | + Shotgun + Flashlight | + Riot Shield |
| Technical Specialist | Unarmed + Tool Kit + SCiPNet Tablet | + Pistol + Anomaly Detector | + Portable Terminal + Demolition Tools |
| Medical Specialist | Unarmed + Medical Kit (5 uses) + Adrenaline Syringe ×2 | + Pistol + Hazmat Suit | + Surgical Kit + Antidote ×3 |
| Researcher | Unarmed + SCiPNet Tablet + Research Notes | + Pistol + Anomaly Detector | + SCRAMBLE Goggles + Portable Hume Meter |
| D-Class Personnel | Orange Jumpsuit + ID Tag (with tracker) | — | — |

### Economy Operation Rules

**Per-Mission Settlement** (performed by the GM upon mission completion):

1. Disburse CR, SA, PC, XP according to the Mission Reward Table
2. SA is automatically deposited into the character file (Foundation standard: "Security Assets Tracking Form" Form-SEC-447)
3. PC cannot be traded or transferred; personal use only
4. CR can be used to purchase standard equipment (see price table), black market trade (2× price), or donated as Site budget (every 500 CR = Site resources +5)

**SA Usage Rules**:
- SA represents your "trust quota" within the Foundation's security apparatus
- Exchanging restricted-tier equipment deducts from the SA pool (non-refundable)
- SA accumulated ≥ 10 → automatically gain "Priority Resupply" status (may request one piece of ≤ SA3 equipment for free before each mission)
- SA drops below zero → triggers Security Department review (O5 Attention +1, next mission equipment issue downgraded one tier)

**PC Usage Rules**:
- PC represents your influence within the Foundation's power structure
- Spend 2 PC → request an Ethics Committee hearing (can overturn one departmental decision)
- Spend 3 PC → request O5-level information decryption (temporary CL+2 access, single use)
- Spend 5 PC → apply for anomalous item trial permit (Green/Yellow tier, single mission)
- PC never automatically decreases—it is only consumed through use or revoked by O5 due to scandal

**Site Budget Application** (Organization Management mode):
After each mission, one `d100 ≤ PRE + Bureaucracy` check may be made to apply for additional budget:
- Success → +300 CR or +1 SA (choose one)
- Exceptional Success → doubled
- Failure → none, and O5 Attention +0 (bureaucratic applications are not penalized)
|------|-----------|-------------|-------------|
| Pistol | 200 | 1 | — |
| Submachine Gun | 500 | 3 | — |
| Assault Rifle | 800 | 5 | — |
| Shotgun | 400 | 2 | — |
| Sniper Rifle | 1,200 | 8 | — |
| Combat Knife | 50 | — | — |
| Stun Baton | 150 | 1 | — |
| Fragmentation Grenade | 300/each | 2/each | — |
| Smoke Grenade | 150/each | 1/each | — |

### Armor Prices

| Armor | Credit Points (CR) | Security Assets (SA) |
|------|-----------|-------------|
| Light Load-bearing Gear | 300 | 1 |
| Tactical Vest | 600 | 3 |
| Ceramic Plate | 800 | 5 |
| Full Body Armor | 1,500 | 10 |
| Bomb Disposal Armor | 2,500 | 15 |
| Hazmat Suit | 1,000 | 8 |

---

## 2.7 Clearance Level Combat Effects

| CL | Squad Command Range | Equipment Authority | Special |
|----|------------|---------|------|
| 0 | None | Unarmed | Can only receive orders |
| 1 | None | Basic Uniform | — |
| 2 | Self only | Standard Issue | Can lead 2 NPCs |
| 3 | Squad (+5m) | Tactical Equipment | Can issue retreat order |
| 4 | Site-level | Restricted Equipment | 1 additional Squad Command |
| 5 | Site Protocol | Full Equipment | Not subject to O5 Attention restrictions |

---

## 2.8 D-Class Personnel "Last Resort" Mechanic

> *"The average life expectancy of D-Class personnel is 30 days. But some—very few—just won't die."*

### Trigger & Check

| Trigger Event | Check |
|---------|------|
| HP drops to 0 (Near-Death) | d100 ≤ WIL + LP×5 |
| Directly attacked by an anomaly | d100 ≤ AGI |
| In a certain-death scenario (GM ruling) | d100 ≤ (STR+AGI+END+WIL)/4 |

### Success Effects

| Degree of Success | Effect |
|--------|------|
| **Legendary** (roll=01) | Escape death + gain Advantage |
| **Exceptional** | Fully evade + discover escape route |
| **Solid** | Avoid death, reduced to Critical Wound (25% HP) |
| **Ordinary** | Avoid death, Critical Wound + lose next turn + item destroyed |
| **Failure** | Enter normal Near-Death process (but D-Class Near-Death save ADV) |

### "Nine Lives" Tracking

- Hidden counter starts at 1d3 (unknown to player)
- Each successful Last Resort → -1
- Reaching zero → unlocks "Legendary D-Class" marker (O5 Attention +2, month-end settlement auto-success ×1)
- After reaching zero, counter resets to 1d3 (GM rolls secretly) and tracking continues—the Legendary state can trigger multiple times
- Upon the third trigger of the Legendary marker → the D-Class PC gains "O5 Special Attention" status: may be recruited as a special agent, or treated as a potential anomaly requiring study (GM decides based on narrative direction)

### Month-End Settlement

```
d100 ≤ WIL + (months survived ×2) + (successful contribution missions ×3)

Legendary/Exceptional → exemption takes effect immediately, transferred to Class C personnel
Solid → next month +10 TN cumulative
Ordinary → no change
Catastrophic (00) → transferred to higher-risk post, next month TN -20
```

---


# Chapter 3: Combat & Conflict

## 3.1 Action Economy

### Turn Structure

Each round ≈ 6 seconds of game time.

```
1. Initiative Phase → Roll initiative (AGI+PER), sort in descending order
2. Action Phase → Each character acts in initiative order
3. End Phase → Tick ongoing effects, morale spread, environment resolution
```

### Action Quota

| Action Type | Per Round | Description |
|---------|---------|------|
| Standard Action | 1 | Attack, use ability, first aid, containment equipment |
| Move Action | 1 | Move MOV meters, stand up, reload, switch weapons |
| Quick Action | 1 | Aim, mark target, squad comms, injector |
| Reaction | 1 | Attack of opportunity, covering fire, emergency dodge |

Actions can be downgraded (Standard → Move → Quick), but not upgraded. Reactions cannot be downgraded.

### Special Combat Actions

| Action | Cost | Effect |
|------|------|------|
| **Aim** | Quick | Next ranged attack this round gains ADV |
| **Full Defense** | Standard | Until start of next round, enemies have DIS against you |
| **Suppressive Fire** | Standard | Cone area suppression (see §3.3) |
| **Sprint** | Standard+Move | MOV×3, cannot attack this round |
| **First Aid** | Standard | Stabilize near-death/temporary bleeding stop (see §3.5) |
| **Containment Operation** | Standard | Activate Scranton Anchor, etc. |
| **Assess Anomaly** | Standard | d100 ≤ INT+Anomalistics, gain weakness info |
| **Retreat** | Standard | Movement this round does not trigger opportunity attacks |

---

## 3.2 Attack & Evasion (d100 Opposed System)

### Attack Sequence

```
Attacker rolls d100 ≤ attack skill value (AGI + weapon skill value)
Defender rolls d100 ≤ AGI + Dodge skill value (total evasion value)

Result resolution:
┌────────────┬─────────────────────┬─────────────────────┐
│            │ Defender Succeeds   │ Defender Fails      │
│            │ (≤AGI+Dodge)        │ (>AGI+Dodge)        │
├────────────┼─────────────────────┼─────────────────────┤
│ Attacker   │ Compare degree of   │ Attack Hits ✓       │
│ Succeeds   │ success; higher     │                     │
│ (≤attack   │ wins                │                     │
│  skill)    │                     │                     │
├────────────┼─────────────────────┼─────────────────────┤
│ Attacker   │ Attack Misses ✗     │ Stray round /       │
│ Fails      │                     │ environment damage  │
│ (>attack   │                     │                     │
│  skill)    │                     │                     │
└────────────┴─────────────────────┴─────────────────────┘
```

### Degree of Success Damage Bonus

When an attack succeeds, the degree of success directly affects damage:

| Attack Degree of Success | Damage Adjustment |
|-----------|---------|
| Legendary Success (roll 01) | Damage ×2 (take max) |
| Exceptional Success (≤ TN/5) | Damage +1 die (e.g. 1d10 → 2d10) |
| Solid Success (≤ TN/2) | Damage +2 |
| Ordinary Success (≤ TN) | Standard damage |
| Failure | No damage |

**Design Intent**: High skill not only improves hit rate but also increases damage output. An Expert deals higher effective damage with the same weapon (hitting vitals, timing strikes). This shortens TTK in equal-tier matchups—Expert versus Expert no longer becomes a 25-round war of attrition.

### Critical Hit

If the attack roll ≤ 1/10 of the attack skill value, and the defender fails to evade → triggers a body-part special effect; damage is calculated as Legendary Success (×2).

### Melee Attack

Use **STR + Melee skill value** as the attack skill value. If using an agile melee weapon (e.g., dagger, rapier), AGI may replace STR (requires GM approval). Defender rolls d100 ≤ AGI + Dodge skill value.

---

## 3.3 Damage System

### HP Thresholds & Status

| HP Remaining | Status | Effect |
|---------|------|------|
| 100%–76% | Intact | No penalty |
| 75%–51% | Light Wound | Narrative description only |
| 50%–26% | Moderate Wound | All action checks TN -10 |
| 25%–1% | Heavy Wound | TN -20; each round may take only one of Standard or Move |
| 0 | Near-Death | See §3.4 |

### Body Part Damage (Three-Zone System)

| Body Part | Trigger Condition | Damage Multiplier | Special Effect |
|------|---------|---------|---------|
| Head | Roll ≤ 5 or deliberate aim | ×1.5 | d100 ≤ END or Stunned 1 round |
| Torso | Default | ×1.0 | None |
| Limbs | Roll ≥ 96 or deliberate aim | ×0.75 | Legs: MOV halved; Arms: attack DIS |

**Deliberate Aim**: Spend a Standard Action to target a specific body part; attack TN -20.

### Damage Types & Resistance

| Type | Example | Resistance Source |
|------|------|---------|
| Piercing | Bullets, claws | Ballistic armor |
| Slashing | Blades, bone edges | Slashing protection |
| Bludgeoning | Clubs, shockwaves | Padded armor |
| Thermal | Fire, extreme cold | Insulated suit |
| Chemical | Corrosion, nerve agents | Hazmat suit |
| Radiation | Nuclear waste, radioactive SCP | Lead lining |
| **Anomalous** | Reality bending, conceptual erosion | Scranton Anchor (rarely) |

Armor provides **Damage Reduction (DR)**: Light 1–2 / Medium 3–4 / Heavy 5–6. Anomalous damage usually ignores normal DR.

**Minimum Damage Rule**: After DR reduction, minimum damage is 1 (unless target is immune). Even if armor fully absorbs the numerical value of an attack, each hit deals at least 1 point of graze/impact damage.

---

## 3.4 Critical Wounds, Near-Death & Death

### Critical Wound Table

Triggered when a single instance of damage exceeds the **END attribute value** (i.e., single-instance injury > END). If a character has END=38, then taking ≥39 damage from a single hit triggers a critical wound check (d100):

| d100 | Effect |
|------|------|
| 01–25 | **Concussion**: Lose all actions next round |
| 26–50 | **Fracture**: Affected limb unusable |
| 51–75 | **Internal Bleeding**: -1d4 HP per round |
| 76–90 | **Organ Damage**: Permanent -5 to attribute (requires advanced medical recovery) |
| 91–00 | **Near-Death**: Immediately enter near-death state |

### Near-Death Rules

Each round, roll a near-death save: `d100 ≤ END` (bare roll, no modifiers)

- 3 cumulative successes → Stabilized, HP returns to 1, unconscious 1d4 hours
- 3 cumulative failures → Death
- Roll 01–05 → Immediately recover 1 HP and regain consciousness
- Roll 96–00 → Counts as 2 failures

### Treatment

| Method | Action | Effect | Limit |
|------|------|------|------|
| First Aid Stabilize | Standard | Stabilize near-death + stop internal bleeding | Requires first aid kit, d100 ≤ Medicine |
| Battlefield Bandage | Standard | Restore 1d6 + (Medicine/10) HP | Once per character per combat |
| Administer First-Aid Stimpak | Quick | Restore 2d6 HP, ignore heavy wound penalty for 1 round | Repeat within 24h → d100 ≤ END or vomit |
| Medical Station Treatment | 1 hour | Restore Level×d8 HP | Requires medical facility |
| Surgery | 4–8 hours | Remove permanent heavy wound effects, full recovery | Requires Foundation medical wing |

---

## 3.5 Tactical Rules

### Cover System

| Cover Level | Effect | Example |
|---------|------|------|
| Partial Cover | Attacker TN -10 | Overturned table, bushes |
| Half Cover | Attacker TN -20 | Low wall, car door |
| Full Cover | Cannot be directly aimed at | Behind concrete wall |
| Reinforced Cover | Full + impenetrable | Ballistic shield, security door |

Cover must be actively declared (Quick Action to crouch/hug wall). Area attack effects are halved.

### Suppressive Fire

Standard Action + ammunition expenditure, against a 15m cone area:

- Enemies in the area roll `d100 ≤ WIL - suppression modifier (TN = shooter's Firearms skill value)`
- Failure → **Suppressed**: Must seek cover, movement toward suppression source halved, attack DIS
- Success → No effect
- Quick Action to maintain suppression until next round
- Crossfire: Enemy TN -15 (harder to resist)

### Squad Command

Those holding command authority use a Standard Action to issue orders:

| Command | Effect | Duration |
|------|------|------|
| Focus Fire | Attack on marked target gains ADV | 1 round |
| Disperse | Next area attack's damage halved | Until next round |
| Alternating Cover | Move does not trigger opportunity + retain cover | 1 round |
| Suppression Advance | Move + suppressive fire auto-cover | 1 round |
| Retreat | MOV×2, retreat does not consume Standard Action | 1 round |

### Morale & Panic

**Morale Value Calculation**:
```
Squad morale value = 40 + commander's WIL/2 (rounded down)
NPC morale value = preset value (Civilian 30 / Security 45 / MTF 55 / Elite 65)
```

**Morale Check** (d100 ≤ morale value - situational modifier):

- Success: Normal
- Failure (margin 1–20): **Nervous** — 25% chance action becomes Full Defense
- Failure (margin 21+): **Panic**

**Panic Spread**: At the end of a panicked ally's turn, friendly units within 10m must make a morale check. The commander may use a Standard Action to issue **Calm Order** (d100 ≤ PRE+Leadership) to suppress the spread.

---

## 3.6 Status Effects

There are 18 status effects total; core status quick reference:

| Status | Primary Effect | Removal Condition |
|------|---------|---------|
| **Panic** | Must move away from threat, cannot focus | Threat gone / d100 ≤ WIL |
| **Nervous** | 25% chance action becomes Full Defense | Auto-recovers |
| **Confusion** | d6 random behavior | Each round d100 ≤ WIL |
| **Suppressed** | Must seek cover, attack DIS | Full cover / suppression ends |
| **Bleeding** | -1d4 HP per round | First aid d100 ≤ Medicine |
| **Poisoned** | All checks DIS + poison damage per round | Antidote / d100 ≤ END |
| **Blinded** | Visual actions auto-fail | Blind source removed |
| **Deafened** | No hearing, Initiative -10 | Deaf source removed |
| **Paralyzed** | Completely unable to act | Each round d100 ≤ END |
| **Stunned** | Lose all actions next round | Auto-recovers (1 round) |
| **Burning** | 1d6 fire damage per round | Extinguish action d100 ≤ AGI |
| **Frozen** | MOV halved + freezing damage | Heat source / leave cold |
| **Restrained** | MOV reduced to 0, attack DIS | Break free d100 ≤ STR |
| **Unconscious** | Cannot act / perceive | HP recovers to 1+ or awakened |
| **Meme Infection** | Behavior altered, contagious | Corresponding-tier amnestic |
| **Reality Destabilized** | Attributes fluctuate randomly | Scranton Anchor / leave area |


# Appendix

## Appendix A: Glossary

| Abbrev | Full Name | Meaning |
|------|------|------|
| TN | Target Number | d100 target value |
| ADV | Advantage | Advantage (d100 take lower) |
| DIS | Disadvantage | Disadvantage (d100 take higher) |
| DR | Damage Reduction | Armor damage reduction |
| SAN | Sanity | Sanity value |
| SP | Stress Points | Stress value |
| CH | Cognitohazard | Cognitohazard |
| STR | Strength | Strength |
| AGI | Agility | Agility |
| END | Endurance | Endurance |
| INT | Intellect | Intellect |
| PER | Perception | Perception |
| WIL | Willpower | Willpower |
| PRE | Presence | Presence |
| HP | Hit Points | Health Points |
| CL | Clearance Level | Security Clearance Level |
| MTF | Mobile Task Force | Mobile Task Force |
| GOC | Global Occult Coalition | Global Occult Coalition |
| O5 | Overseer Council | Overseer Council |

## Appendix B: Quick Reference

### TN Calculation Quick Reference

```
Standard Check: d100 ≤ (Attribute + Skill + Difficulty Modifier)
Attack Check: d100 ≤ (AGI + Weapon Skill - Cover Modifier)
SAN Check: d100 ≤ (SAN - CH Modifier)
Overclearance Operation: d100 ≤ (Attribute + Skill - Overclearance Modifier)
Near-Death Save: d100 ≤ END (bare roll)
```

### Difficulty Modifier Quick Reference

| +60 Trivial | +30 Easy | +10 Slightly Easy | ±0 Standard |
| -20 Challenging | -40 Hard | -60 Very Hard | -80 Legendary |

### Cognitohazard Quick Reference

| Mild: d100 ≤ SAN, 1d4 SAN | Moderate: d100 ≤ SAN-10, 2d6 |
| Severe: d100 ≤ SAN-20, 3d8 | Extreme: d100 ≤ SAN-30, 4d10 |

### Combat Quick Reference

| Action Quota: 1 Standard + 1 Move + 1 Quick + 1 Reaction |
| Cover: Partial TN-10 / Half TN-20 / Full cannot be aimed |
| Armor DR: Light 1-2 / Medium 3-4 / Heavy 5-6 |
| Part Aim: Head TN-20 / Limbs TN-10 |

## Appendix C: Character Sheet Template

```
┌──────────────────────────────────────────────────────┐
│  SCP Foundation Agent Dossier                         │
├──────────────────────────────────────────────────────┤
│ Name:____________  Callsign:____________             │
│ Identity:_______  Subclass:________  Level:____       │
│ Clearance Level:____  XP:________                    │
├──────────────────────────────────────────────────────┤
│  Attributes                                         │
│  STR ____  AGI ____  END ____  INT ____             │
│  PER ____  WIL ____  PRE ____                       │
├──────────────────────────────────────────────────────┤
│  Derived                                           │
│  HP ____/____  SAN ____/____  SP ____              │
│  INIT ____  MOV ____m  Load ____kg                 │
├──────────────────────────────────────────────────────┤
│  Skills                                            │
│  □Firearms____ □Heavy Weapons____ □Melee____ □Throwing____ □Dodge____ │
│  □Computers____ □Engineering____ □Demolitions____ □Medicine____ □Cryptography____ │
│  □Anomalistics____ □Foundation Lore____ □Occult____ □Science____ □Linguistics____ │
│  □Persuasion____ □Deception____ □Interrogation____ □Leadership____ │
│  □Stealth____ □Observation____ □Survival____ □Resist____ │
├──────────────────────────────────────────────────────┤
│  Resource Pools           Status Effects            │
│  □□□□□                    □Panic □Nervous □Bleeding □Poisoned │
│                           □Blinded □Stunned □Burning □Restrained │
├──────────────────────────────────────────────────────┤
│  Identity Abilities / Feats                         │
│  · ________________________________________         │
│  · ________________________________________         │
├──────────────────────────────────────────────────────┤
│  Equipment                Weapons                   │
│  ________________            _____ Damage____ Ammo___ │
│  ________________            _____ Damage____ Ammo___ │
│  ________________            Armor____ DR____        │
├──────────────────────────────────────────────────────┤
│  Background / Department Relations                  │
│  ________________________________________           │
│  Humanity ____ / 10    Morality ____ / 10            │
└──────────────────────────────────────────────────────┘
```

---

*SCP: CONTAINMENT PROTOCOL Rulebook v1.0*
*Tabletop Rules Studio · June 2026*
*Phase 1–4 Fully Complete*

*For the complete GM reference manual, detailed preset SCP dossiers, and module expansion packs, see the separate volumes*
