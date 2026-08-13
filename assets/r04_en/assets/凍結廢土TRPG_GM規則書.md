# Frozen Wasteland TRPG — GM Rulebook v1.1

> **Code:** frozen-wasteland-trpg | **Document Type:** GM Rulebook

---

# Chapter 1: Core Rules

## 1.1 Dice System

### Base Resolution Die: d20 + Attribute Modifier

All risky action checks use **1 twenty-sided die (d20)**, plus the character's Attribute Modifier for the relevant attribute, against the target Difficulty (DC).

### Why d20

The linear distribution of a d20 (each face a 5% chance) creates the tension of "every roll is a gamble," which fits perfectly with Frozen Wasteland's "taut, neurotic" emotional tone. There is no bell-curve sense of safety — you can never calculate the outcome precisely.

### Roll Types Overview

| Roll Type | Dice Used | Trigger | Roller |
|---|---|---|---|
| **Attribute Check** | d20 + Attribute Modifier | Character attempts a risky action | Player |
| **Disadvantage Check** | 2d20 take lower + Attribute Modifier | Panic, adverse environment, overload stress | Player |
| **Advantage Check** | 2d20 take higher + Attribute Modifier | Full preparation, assisting action, Time Shield | Player |
| **Thaw Die** | d20 vs Thaw Threshold | Every round inside a Freeze Zone | GM (secret) |
| **Guts Check** | d20 + Guts Modifier | Thaw Moment, witnessing a horrific scene | Player |
| **Contest Check** | Both sides d20 + Modifier, higher wins | Chase, grapple, Hide vs Spot | Both sides |

---

## 1.2 Five Attributes

| Attribute | Abbrev. | Meaning | Character in a Freeze Zone | Starting Range | Max |
|---|---|---|---|---|---|
| **Speed** | Speed (SPD) | Movement, reaction speed | Escape at the Thaw Moment — every square is life or death | 2–8 | 10 |
| **Perception** | Perception (PER) | Observation, prediction, intuition | Read the Freeze Zone's "micro-expressions" — Time Rifts, subtle object movement | 2–8 | 10 |
| **Guts** | Guts (GUT) | Composure, willpower, risk tolerance | Steady hands in the Freeze Zone — Rattled, and everything collapses | 2–8 | 10 |
| **Tech** | Tech (TEC) | Device operation, mechanical understanding, assessment | Operate detectors, disarm hazards, assess freeze stability | 2–8 | 10 |
| **Negotiation** | Negotiation (NEG) | Persuasion, negotiation, social influence | Sell loot, deal with survivors | 2–8 | 10 |

### Attribute Allocation

**Option A: Free Allocation (Recommended)** — Distribute 25 points freely among the five attributes, each at minimum 2, maximum 8.

**Option B: Quick Arrays** —

| Array Name | Attribute Values | Suited For |
|---|---|---|
| Well-Rounded | 6, 5, 5, 5, 4 | No obvious weak point |
| Specialist | 8, 5, 5, 4, 3 | One extreme strength, obvious weakness |
| Tough Nut | 5, 4, 8, 5, 3 | Exceptional Guts |
| Negotiator | 5, 5, 4, 3, 8 | At home in the base |
| Techie | 4, 5, 5, 8, 3 | Devices never fail |

**Option C: Rolling (Not recommended for beginners)** — Roll 5d10, take the five highest results. One re-roll allowed for a result below 3.

### Attribute Modifier Table

**Modifier = Attribute Value − 5**

| Attribute Value | Modifier | Description |
|---|---|---|
| 1 | −4 | Near-defective |
| 2 | −3 | Clear disadvantage |
| 3 | −2 | Below average |
| 4 | −1 | Slightly weak |
| **5** | **+0** | **Average human** |
| 6 | +1 | Slightly better |
| 7 | +2 | Clearly excellent |
| 8 | +3 | Professional grade |
| 9 | +4 | Legendary (unlocked via progression) |
| 10 | +5 | Human limit |

---

## 1.3 Derived Attributes

| Derived Attribute | Calculation | Use |
|---|---|---|
| **Movement (MV)** | Speed Value + 3 squares/round | Distance moved per round inside a Freeze Zone |
| **Premonition Sense (FS)** | Perception Modifier | Bonus to checks for sensing Thaw Omens |
| **Panic Threshold (PT)** | Guts Value × 2 + 5 | Panic when stress exceeds this |
| **Time Resistance (TR)** | Tech Modifier | Resist side effects of temporal anomalies |
| **Health (HP)** | Guts Value × 2 + 10 | Capacity to absorb damage |

---

## 1.4 Attribute Checks

### Basic Flow

```
GM declares: Action + Attribute + Difficulty (DC)
        ↓
Player rolls d20 + Attribute Modifier
        ↓
Compare result vs Difficulty (DC) → Success / Failure
```

### Difficulty Ladder

| Difficulty (DC) | Difficulty Tier | Success Rate (Mod +0) | Typical Scenario |
|---|---|---|---|
| 5 | Trivial | 80% | Hearing footsteps in a quiet environment |
| 8 | Easy | 65% | Recognizing a common Freeze Zone omen |
| 10 | Ordinary | 55% | Quickly climbing over an obstacle |
| **12** | **Moderate** | **45%** | **Noticing a subtle Time Rift** |
| 15 | Hard | 30% | Disarming an explosive at the Thaw Moment |
| 18 | Very Hard | 15% | Stabilizing a collapsing Frozen One |
| 20 | Nearly Impossible | 5% | Closing a Time Rift bare-handed |

### Binary Success/Failure + Extreme Results

| Roll Result | Term | Effect |
|---|---|---|
| Natural 20 | **Critical Success** | Unconditional success + extra positive effect |
| ≥ Difficulty (DC) (not natural 20 (nat 20)) | **Success** | Action achieves intended effect |
| < Difficulty (DC) (not natural 1 (nat 1)) | **Failure** | Action not achieved, possible side effect |
| Natural 1 | **Catastrophe** | Unconditional failure + extra negative effect |

### Disadvantage Rolls

When a character is in a state such as Panic or an adverse environment, roll **2d20 and take the lower**, then add the Attribute Modifier.

| Normal Success Rate | Success Rate with Disadvantage | Equivalent Penalty |
|---|---|---|
| 65% (needs 8+) | 42.3% | −4.5 |
| 55% (needs 10+) | 30.3% | −5.0 |
| 45% (needs 12+) | 20.3% | −5.0 |
| 30% (needs 15+) | 9.0% | −4.2 |

> Disadvantage hits moderate Difficulty (DC 10–15) hardest — exactly the most common check range in Freeze Zones.

### Advantage Rolls

In situations such as full preparation, ally assistance, or a Time Shield, roll **2d20 and take the higher**. When both Advantage and Disadvantage are present, they cancel out and you roll 1d20 normally.

---

## 1.5 Thaw Die Mechanic (Core System)

### Basic Mechanism

At the end of every round inside a Freeze Zone, the GM secretly rolls 1d20 (the Thaw Die) and compares it against the zone's **Thaw Threshold**:

| Roll Result | Event | Effect |
|---|---|---|
| **Die < Threshold** | Time holds | Nothing happens; the round proceeds normally |
| **Die = Threshold** | Omen appears | Player makes a Perception check (see below) |
| **Die > Threshold** | Local Thaw | Triggers Thaw Moment rules (see Chapter 3) |

### Declining Thaw Threshold

The Thaw Threshold gradually lowers with the number of rounds players remain in the Freeze Zone — the longer you stay, the more dangerous it gets.

**Baseline model — Pulse Type** (most common):

| Round Range | Thaw Threshold | P(nothing) | P(omen) | P(thaw) | Cumulative P(at least one thaw) |
|---|---|---|---|---|---|
| 1–3 | 17 | 80% | 5% | 15% | 38.6% |
| 4–6 | 16 | 75% | 5% | 20% | 70.5% |
| 7–9 | 15 | 70% | 5% | 25% | 89.7% |
| 10–12 | 14 | 65% | 5% | 30% | 97.3% |
| 13–15 | 13 | 60% | 5% | 35% | 99.6% |
| 16+ | 12 | 55% | 5% | 40% | ≈100% |

### Threshold Parameters for the Five Rhythm Types

| Type | Starting Threshold | Decline Rate | Minimum Threshold | Trait |
|---|---|---|---|---|
| **Slumber Type** | 19 | −1 every 4 rounds | 14 | Omen Difficulty (DC) −3, suited for beginners |
| **Pulse Type** | 17 | −1 every 3 rounds | 10 | Regular decline, trackable |
| **Spasm Type** | 15 | 1d4−1 per round | 5 | Completely unpredictable |
| **Chain Type** | 18 | −1 every 2 rounds; −2 when an adjacent zone thaws | 6 | One thaw accelerates all |
| **Breath Type** | 16 | −1/round ×3, then +3 reset, cycling | 10 | Has a breathing window |

### Omen Perception Check

When the Thaw Die equals the threshold, the player may make a Perception check against the zone's **Omen Difficulty (DC)**:

| Omen Clarity | Difficulty (DC) | Typical Description |
|---|---|---|
| Very obvious | 8 | Sound of ice shattering, visible spatial distortion |
| Obvious | 10 | Objects begin to drift, temperature shifts abruptly |
| Moderate | 12 | Faint temporal ripples, abnormal light refraction |
| Subtle | 15 | Nearly imperceptible energy fluctuation |
| Nearly imperceptible | 18 | Only the truly sharp can sense it |

**Check Success Benefit**:
- Success (≥ Difficulty (DC)): Learn "a Thaw will occur this round," may take one preparatory action before the Thaw
- Critical Success (nat 20): Above + exact knowledge of the Thaw's range and which object will awaken
- Failure: Unaware → caught off guard at the Thaw (Guts check Difficulty (DC) +2)

### Omen Detection Rate by Perception Level

| Perception Mod | Difficulty (DC) 8 (Obvious) | Difficulty (DC) 10 | Difficulty (DC) 12 (Moderate) | Difficulty (DC) 15 | Difficulty (DC) 18 (Subtle) |
|---|---|---|---|---|---|
| −3 (Perception (PER) 2) | 50% | 40% | 30% | 15% | 5% |
| +0 (Perception (PER) 5) | 65% | 55% | 45% | 30% | 15% |
| +2 (Perception (PER) 7) | 75% | 65% | 55% | 40% | 25% |
| +3 (Perception (PER) 8) | 80% | 70% | 60% | 45% | 30% |

> Even the sharpest character (Perception (PER) 8) has only a 30% detection rate against a "nearly imperceptible" omen. **No one fully controls the Freeze Zone.**

---

## 1.6 Guts Check and Panic System

### Guts Check at the Thaw Moment

When a Thaw occurs, all players within the Thaw's range must immediately make a Guts check:

| Situation | Difficulty (DC) | Failure Effect |
|---|---|---|
| With omen warning (detected successfully) | 10 | Rattled this round (Movement −2 + Disadvantage on actions) |
| No warning (undetected or no omen) | 14 | Rattled + Panic Value +1 |
| A known major threat thaws | Difficulty (DC) +2~4 | By threat intensity |
| A teammate/innocent thaws | Difficulty (DC) −2 | GM discretion |

### Guts Modifier vs Key Difficulty (DC) Success Rate

| Guts Mod | Difficulty (DC) 10 (prepared) | Difficulty (DC) 14 (caught off guard) | Difficulty (DC) 16 (extreme) |
|---|---|---|---|
| −3 (Guts (GUT) 2) | 40% | 20% | 10% |
| +0 (Guts (GUT) 5) | 55% | 35% | 25% |
| +2 (Guts (GUT) 7) | 65% | 45% | 35% |
| +3 (Guts (GUT) 8) | 70% | 50% | 40% |

> Even the highest-Guts character has only a fifty-fifty chance of staying calm against a caught-off-guard Thaw. **No one is immune to fear.**

### Panic Value

The Panic Value tracks a character's psychological stress inside a Freeze Zone, starting at 0.

**Panic Increases**:

| Event | Panic Value Change |
|---|---|
| Thaw occurs (Guts check failed) | +2 |
| Thaw occurs (Guts check succeeded) | +1 |
| Every 3 rounds spent in a Freeze Zone | +1 (environmental stress) |
| Witnessing a teammate injured/down | +3 |
| Taking damage yourself | +2 |
| Catastrophe on a check (nat 1) | +1 |

**Panic Release**:

| Event | Panic Value Change |
|---|---|
| Retreat to a safe zone and rest 1 hour | −3 |
| Use a Sedative | −2 (one-time) |
| Successfully stabilize a Critical Frozen One | −2 |
| Complete looting objective and extract | Reset to zero |

### Panic Threshold

**Panic Threshold = Guts Value × 2 + 5**

| Guts Value | Panic Threshold | Endurance |
|---|---|---|
| 2 | 9 | Extremely fragile — a single Thaw may cause Panic |
| 5 | 15 | Average — can endure 3–4 rounds of stress |
| 8 | 21 | Iron nerves — almost never panics on a mission |

### Panic Trigger

When the Panic Value **>** Panic Threshold (exceeds, not equals), the character enters the **Panic state**:

- All attribute checks at **Disadvantage** (2d20 take lower)
- Movement −2
- Cannot perform assisting actions
- Omen Perception check Difficulty (DC) +4

The Panic state persists until the Panic Value drops below the threshold.

---

## 1.7 Movement

**Movement = Speed Value + 3 squares/round** (each square ≈ 1.5 meters)

| Speed Value | Movement | Description |
|---|---|---|
| 2 | 5 squares | Shuffling along |
| 5 | 8 squares | Normal human run |
| 7 | 10 squares | Trained looter |
| 8 | 11 squares | Gale — swiftly leaves at the Thaw Moment |

- Each round: move + one action is standard
- If you only move and take no other action, movement distance ×1.5
- Carrying a Frozen One: Movement −3
- Panic state: Movement −2


## 1.8 Environmental Hazard System

The world of Frozen Wasteland kills on its own. The four environmental hazards below share a unified grading system.

### 1.8.1 Cold Hazard

| Tier | Environment Example | Effect | Check (every 5 rounds) |
|---|---|---|---|
| **Mild Cold** | Safe-zone winter outdoors, Freeze Zone edge | No immediate effect, but long exposure accumulates Cold Fatigue (see §1.9) | Guts (GUT) Difficulty (DC) 8 |
| **Moderate Cold** | Inside a Freeze Zone, cold storage, night wasteland | Movement −1 per round; accumulates Cold Fatigue | Guts (GUT) Difficulty (DC) 12 |
| **Severe Cold** | Deep Freeze Zone, blizzard, polar wasteland | Movement −2 per round + Speed check Disadvantage; rapidly accumulates Cold Fatigue | Guts (GUT) Difficulty (DC) 16 |
| **Lethal Cold** | Around the Time Storm Eye, liquid-nitrogen leak area | 1d4 Frostbite damage per round; immediately accumulates Cold Fatigue | Guts (GUT) Difficulty (DC) 20 |

**Warming Gear** can lower the effective hazard tier by 1–2 (e.g.: Protective Suit gives −1 tier, heat pack −1 tier, Time Isolation Suit −2 tier).

### 1.8.2 Darkness / Visibility

| Tier | Situation | Effect |
|---|---|---|
| **Dim** | Moonlight, distant firelight, edge of flashlight | Perception check Disadvantage (sight-related) |
| **Gloomy** | Single flashlight, candlelight | Perception check Disadvantage + Movement −1 (can't see footing) |
| **Total Darkness** | No light source | Perception check auto-fails (sight-related); Movement −3; cannot read/identify details |

**Light sources**: A crank flashlight provides 10 squares of dim light / 5 squares of gloomy light. A flare provides 30 squares of gloomy light / 15 squares of normal light (lasts 5 rounds). A detector screen provides only 1 square of dim light around itself.

### 1.8.3 Noise Hazard

The silence of a Freeze Zone is a double-edged blade — you can hear threats approach, and threats can hear you.

| Action | Noise Level | Audible Distance | Effect |
|---|---|---|---|
| **Silent action** (successful stealth) | 0 | Imperceptible | — |
| **Whisper / slow movement** | 1 | 5 squares | Nearby threat perceives at Perception Difficulty (DC) 15 |
| **Normal conversation / normal movement** | 2 | 10 squares | Threat perceives at Perception Difficulty (DC) 10 |
| **Loud shout / running / metal clash** | 3 | 20 squares | Threat automatically locates direction |
| **Gunshot / explosion / structural collapse** | 4 | 50 squares | Whole zone alerted + **Thaw Die trigger bonus +2** |

> **Firearms warning**: Using firearms inside a Freeze Zone — the noise not only draws threats, it also accelerates the expansion of Time Rifts through vibration.

### 1.8.4 Starvation and Thirst

| State | Trigger Condition | Effect |
|---|---|---|
| **Normal** | Eat 1 Ration + drink water daily | None |
| **Starving** (no food for 24 hours) | Last meal over 24 hours ago | Disadvantage on all physical checks |
| **Starvation and Thirst** (48 hours without food or 24 hours without water) | — | Disadvantage on all checks + Movement −2 |
| **Exhaustion** (72 hours without food) | — | Disadvantage on all checks + Movement −3 + Health (HP) −1 per hour |
| **Dehydration** (48 hours without water) | — | Disadvantage on all checks + Health (HP) −1d4 per 2 hours |

**Rations**: 1 emergency ration (1 unit of weight) sustains for 1 day. A Water Purification Tablet purifies 1 liter of water (1 day's supply).

---

## 1.9 Cold Fatigue

Cold Fatigue is the cumulative effect of prolonged exposure to low-temperature environments, and is a separate system from Frostbite (see §3.3).

### 1.9.1 Fatigue Levels

| Level | Trigger | Effect | Recovery Condition |
|---|---|---|---|
| **Level 1: Shivering** | 5 rounds in moderate cold / prolonged exposure in light cold | Disadvantage on Speed checks (trembling affects fine motor control) | Rest 1 hour in safe zone / stay near heat source for 10 minutes |
| **Level 2: Sluggish** | Reached Level 1 + 5 more rounds of exposure / 3 rounds in severe cold | Speed −2 + Disadvantage on Perception checks (dulled senses) + Movement −1 per round | Rest 4 hours in safe zone / use a warm compress to immediately drop to Level 1 |
| **Level 3: Hypothermia** | Reached Level 2 + 5 more rounds of exposure / 1 round in lethal cold | Speed −4 + Disadvantage on all checks + Health (HP) −1 per round (body heat loss) | Rest 8 hours in safe zone + Medicine Difficulty (DC) 12 / emergency warming measures |

### 1.9.2 Fatigue Check

Each time a cold check triggers (usually every 5 rounds), the character makes **Guts (GUT) + Guts modifier vs environment Difficulty (DC)** (see §1.8.1 Cold Hazard Level table):

- **Success**: Resist the cold; fatigue level does not increase
- **Failure**: Fatigue level +1
- **Catastrophe (nat 1)**: Fatigue level +2

### 1.9.3 Special Rules

- **Warming Gear** provides Advantage on Guts (GUT) checks (e.g., warm compress)
- **Time Crystal** can serve as an emergency heat source: spend 1 crystal to immediately reduce fatigue by 1 level (crystals release heat when discharging their time energy)
- **Panicked characters** accumulate Cold Fatigue twice as fast while in Panic (checked every 3 rounds)

---

## 1.10 Freeze Level

Some Freeze Zones contain "Progressive Freeze" — time is not fully frozen but flows extremely slowly, gradually freezing those who enter.

### 1.10.1 Freeze Level Table

| Level | Effect | Appearance |
|---|---|---|
| **Level 0: Normal** | No effect | — |
| **Level 1: Stasis** | Movement −2; all actions cost an extra Minor Action (movements slow) | Skin slightly pale, movements slightly stuttering |
| **Level 2: Half-Frozen** | Movement −4; each round may perform only 1 Major Action or movement (not both); Speed modifier −3 | Limbs stiff, body temperature drops sharply, visible ice mist in breath |
| **Level 3: Full Freeze** | Character is frozen in time — cannot act, cannot perceive the outside world, cannot be normally harmed (equivalent to the Frozen) | Body completely still, covered in thin frost |

### 1.10.2 Freeze Accumulation and Resistance

- **Accumulation Trigger**: While in a Progressive Freeze environment, every 3 rounds make **Tech (TEC) + Tech modifier vs Difficulty (DC) (per zone setting, usually 12–16)**
- **Success**: Resist freezing; level does not increase
- **Failure**: Freeze level +1
- **Catastrophe (nat 1)**: Freeze level +2

### 1.10.3 Thaw Release

| Method | Requirement | Effect |
|---|---|---|
| **Leave the Freeze Zone** | Exit the zone that triggered freezing | Level 1 releases immediately; Levels 2–3 decrease −1 per round (in safe zone) |
| **Time Crystal Treatment** | Spend 2 crystals, Tech (TEC) Difficulty (DC) 14 | Immediately reduce by 2 levels |
| **Defrost Agent** | Spend 1 Defrost Agent (see §2.2 Equipment) | Immediately reduce by 1 level, immune to that zone's freeze accumulation for the next 3 rounds |
| **Teammate Body Heat Transfer** | Teammate spends a Major Action, Guts (GUT) Difficulty (DC) 10 | Target gains Advantage on their next Freeze Resistance check |

> A **character at Full Freeze (Level 3)** cannot release themselves — a teammate must carry them out of the Freeze Zone and use a Defrost Agent or Time Crystal to release them from the outside.

---

## 1.11 Stealth Rules

In a Freeze Zone, sometimes the best strategy is not to run or fight — but to remain undetected.

### 1.11.1 Stealth Check

When performing stealth, the character rolls **Speed (SPD) + Speed modifier vs the threat's Perception (PER) modifier + 10** (passive awareness), or a Difficulty (DC) set by the GM:

| Situation | Difficulty (DC) |
|---|---|
| Open space, no cover, normal light | 18 |
| Partial cover (shelves, vehicles), dim light | 14 |
| Adequate cover (corners, ruins), gloomy | 10 |
| Full concealment, total darkness | Automatic success (unless the threat has special senses) |

### 1.11.2 Stealth Modifiers

| Situation | Modifier |
|---|---|
| Wearing heavy armor (Armor Value ≥3) | Disadvantage |
| Light load (carrying ≤5 units) | Advantage |
| Panic state | Automatic failure (trembling and rapid breathing cannot be hidden) |
| Carrying ≥6 Time Crystals | Disadvantage (crystals' time-noise leaks position) |
| Stealthy Feat | Advantage |
| Teammate assistance as distraction | Advantage (assistant must spend a Minor Action) |

### 1.11.3 Consequences of Being Discovered

| Threat Type | Reaction |
|---|---|
| **Mutated creature** | Immediately attacks or goes alert (Perception (PER) contest determines surprise round) |
| **Hostile raider** | May ambush, evade, or negotiate (per NPC disposition) |
| **Environmental threat** | Discovery does not trigger environmental threats — but failed stealth is often accompanied by noise (see §1.8.3), which may trigger a Thaw |
| **The Frozen** | The Frozen cannot perceive the stealth character — but nearby awakened threats might |

### 1.11.4 Team Stealth

- When the whole team stealths, use **the check result of the character with the lowest Speed (SPD) modifier** as the team result
- The team may split up — each split group checks independently
- "Chain Type Coordinator" Zone Experience can use a warning action to grant stealth Advantage to teammates

---

## 1.12 Looting and Searching

### 1.12.1 Search Check

Searching an area (such as a room, a row of shelves, a vehicle) costs **1 Major Action** (small area) or **1 round** (large area). Make **Perception (PER) + Perception modifier vs Difficulty (DC)** (set by GM per area):

| Area State | Difficulty (DC) | Expected Haul |
|---|---|---|
| Already looted | 18 | Misc items worth 1d4 Scrap Coins |
| Partially disturbed | 12 | Basic supplies (rations, water, bandages) |
| Largely intact | 10 | Good supplies (medkit, tools, few Crystal Shards) |
| Never searched | 8 | Abundant supplies (roll on area supply table) |

**Degree of success matters**:
- Bare success (≥ Difficulty (DC)): obtain base haul
- Major success (≥ Difficulty (DC)+3): obtain one extra item
- Critical Success (nat 20): discover hidden item or high-value item

### 1.12.2 General Loot Table (d20)

> ▶ General Loot Table (d20) see **assets/物品圖鑑.md**.

### 1.12.3 Quick Looting (Time-Saving Rule)

If the GM does not want to roll per area, a simplified rule may be used:

- **Shallow looting** (edge areas): automatically gain 2d4 rations + 2d6×10 Scrap Coins + 25% chance of 1 Crystal Shard
- **Mid looting**: 3d6 rations + 3d6×10 Scrap Coins + 1 medkit + 50% chance of 1d3 crystals
- **Deep looting**: 4d8 rations + 4d8×10 Scrap Coins + 2 medkits + 2d4 crystals + 15% chance of a rare item

---

## 1.13 Design Note: Attributes-as-Skills

Frozen Wasteland uses a simplified **"Attributes-as-Skills"** design — there is no separate skill list. All actions map directly to the five attributes, and the GM judges the most relevant attribute and sets the Difficulty (DC).

**Design Rationale**:
- The pace of the Freeze Zone demands fast rulings — looking up skills in a table would slow the tension of the Thaw Moment
- The five attributes already cover the core action dimensions of the Frozen Wasteland: movement/reaction (Speed), observation/prediction (Perception), will/calm (Guts), operation/understanding (Tech), social/negotiation (Negotiation)
- Character differentiation comes from Motivation abilities, Zone Experience, Trauma, and Feats, rather than fine-grained skill point allocation

**GM Adjudication Principles**:
- If an action clearly falls under a single attribute → use that attribute directly
- If it spans multiple attributes → choose the most core attribute, or allow the player to use the higher attribute but with Difficulty (DC) +2
- If the player proposes a creative alternative → encourage it! Change the attribute mapping, Difficulty (DC) unchanged or slightly lower





# Chapter 2: Character Creation

## 2.1 Six Steps of Character Creation

### Step 1: Motivation — Why did you enter the Freeze Zone?

| Motivation | Extra Resources | Motivation Ability | Narrative Tags |
|---|---|---|---|
| **Survivor** | Large backpack (load +5), extra rations ×2 | **Collective Responsibility**: when protecting teammates, Advantage on Guts checks | `breadwinner` `in debt` |
| **Seeker** | Clue notes + faded photo, flare ×2 | **Never Give Up**: when making Perception checks related to the search target, spend 1 Resolve Point to gain Advantage | `obsessive` `haunted by the past` |
| **Crystal Prospector** | Modified detector (accuracy 70%), black-market contact | **Keen Nose**: automatically succeeds at appraising Time Crystal value | `greedy` `well-connected` |
| **Explorer** | Research notes, analysis toolkit | **Scholar's Eye**: when entering a new Freeze Zone, the GM informs of one unique feature | `curious` `naive` |
| **Atoner** | Relic (custom), starts with 1 extra Resolve Point | **No More Running**: in situations similar to Trauma, spend 1 Resolve Point to turn Disadvantage into normal | `guilty` `self-destructive` |

### Step 2: Attribute Allocation

25 points freely allocated to the five attributes, 2–8 each. Compute derived attributes:
- Movement = Speed + 3
- Premonition Sense = Perception modifier
- Panic Threshold = Guts × 2 + 5
- Time Resistance = Tech modifier
- Health = Guts × 2 + 10
- Starting Resolve Points = Guts modifier (minimum 1)

### Step 3: Zone Experience — Which rhythm are you familiar with?

| Experience Type | Experience Advantage | Experience Intuition (passive) |
|---|---|---|
| **Slumber Type Veteran** | In Slumber Type zones, Perception checks for Omens gain Advantage | Panic pressure accumulates only once every two rounds |
| **Pulse Type Dancer** | Can predict the exact number of rounds until the next Thaw (Tech Difficulty (DC) 10) | In regular Thaw environments, Movement +1 |
| **Spasm Type Gambler** | Guts check at Thaw Moment Difficulty (DC) −2 | Panic pressure increases by only half per Thaw |
| **Chain Type Coordinator** | Spend one action to warn teammates of the next zone's imminent Thaw | Teammates within line of sight gain +1 on Guts checks |
| **Breath Type Stalker** | Sense whether the current phase is "inhale" or "exhale" (no roll needed) | In Breath Type progressive phases, movement speed is not halved |

### Step 4: Trauma — What did you lose in the Freeze Zone?

Trauma has a **two-sided effect**: disadvantageous situations drag you down, advantageous situations give you superhuman resolve.

| Trauma | Trauma Effect (Disadvantage) | Resolve Effect (Advantage) |
|---|---|---|
| **Lost Teammate** | When a teammate is in danger, Disadvantage on Guts checks | When successfully protecting a teammate, recover 1 Resolve Point |
| **Lost Limb/Sense** | Disadvantage on checks requiring that part | The missing part is highly sensitive to time anomalies — automatically sense nearby crystals/Thaw nodes (10 squares) |
| **Stranger You Couldn't Save** | When facing a Frozen One's plea for help, Disadvantage on Negotiation checks | When actively choosing to save someone over taking supplies, gain extra Resolve Points |
| **Time Poisoning** | In actions requiring precise timing, Disadvantage on Speed checks | Spend 1 Resolve Point to reroll a Perception check |
| **Betrayal** | Disadvantage when negotiating with strangers | Automatically succeed at detecting deception or ambush |

**Overcoming Trauma**: When facing a Trauma-related situation and making a different choice, the GM may rule the Trauma overcome — disadvantage removed, advantage doubled, transformed into a "Mark".

### Step 5: The One You're Still Searching For

Define a person you believe is still frozen somewhere. This is not a quest — it is a faint beacon that always glows in the background.

| Trigger Condition | Reward |
|---|---|
| Discover a clue related to the target | Gain 1 Insight Point (max 3) |
| Spend 1 Insight Point | Reroll any one attribute check |
| Spend 1 Insight Point | Ask the GM a yes/no question (GM must answer honestly) |
| Spend 2 Insight Points | Gain an extra action at the Thaw Moment |
| Finally find this person | Insight Point max permanently +1 |

### Step 6: Starting Equipment

**Common Starting Equipment**:
- Basic Protective Suit ×1 (Armor +1, Time Resistance +1)
- Time Crystal Detector (basic) ×1 (range 30 squares, accuracy 60%)
- Multi-tool knife ×1
- Backpack (load limit 15 units)
- Emergency rations (3 days' worth)
- Hand-crank flashlight
- Chalk ×5

**Motivation Extra Equipment**: determined by the Motivation from Step 1.

---

## 2.2 Equipment System

> ▶ Full equipment, weapon, and tool tables see **assets/物品圖鑑.md**.

## 2.3 Time Crystal Economy

### Acquisition

| Location Type | Risk | Typical Haul |
|---|---|---|
| Thaw edge | Medium | 1–2 crystals |
| Time Rift point | High | 2–4 crystals |
| Time Storm Eye | Extreme | 4–8 crystals |
| On a Frozen One | Variable | 0–3 crystals |

### Usage

| Use | Cost | Effect |
|---|---|---|
| Personal Time Shield | 1 crystal | Immune to Thaw effects for 1d4 rounds |
| Extend object Thaw time | 1–3 crystals | Each crystal delays by 1 round |
| Buy time for a Frozen One | 2 crystals | Critical Frozen One's survival time extended from minutes to hours |
| Stabilize a Time Rift | 3 crystals | No Thaw occurs within radius 5 squares for 5 rounds |

### Carrying Risk

| Carrying Count | Effect |
|---|---|
| 1–2 | Almost no effect |
| 3–5 | GM Thaw Die +1 |
| 6–10 | Thaw Die +2, Tech Difficulty (DC) 10 each round or suffer Time Disorientation |
| 11+ | Thaw Die +3, Perception Disadvantage, detectable from 20 squares away |

### Dual-Currency System
- **Scrap Coin**: everyday currency, 10 Scrap Coins ≈ one day's basic living cost
- **Time Crystal**: hard currency, 1 crystal ≈ 500–1000 Scrap Coins

---

## 2.4 Progression System (Level-less)

### Milestone Triggers

The GM grants progression at the following moments (recommended once per 1–2 sessions; at important story nodes such as key campaign turning points, an extra "Story Milestone" may be granted — allowing two rewards at once, e.g., attribute +1 and a new Feat):

| Milestone Type | Trigger Condition | Reward |
|---|---|---|
| Survival | Complete one full looting run and return safely | One attribute +1 (max 10) |
| Ethics | Make a major ethical choice | Gain a second Thaw Rhythm experience |
| Trauma | Face a Trauma situation and make a different choice | Trauma overcome |
| Relationship | Major discovery related to "The One You're Still Searching For" | Insight Point max +1 |
| Tech | Learn a new device or make a major discovery | Gain a new Feat |

### Feat List (excerpt)

| Feat | Prerequisite | Effect |
|---|---|---|
| Quick-Break | Tech (TEC) ≥ 7 | Time to disarm dangerous items halved |
| Stealthy | Speed (SPD) ≥ 7 | Thaw Die trigger bonus −1 when moving |
| Time-Reader | Perception (PER) ≥ 7 | On entering a new Freeze Zone, Perception Difficulty (DC) 12 reveals the rhythm type |
| Iron Guts | Guts (GUT) ≥ 7 | Panic Threshold +3 |
| Time Adaptation | Survived deep Freeze Zones 2+ times | Carrying risk lowered by one tier |

---

## 2.5 Character Sheet Template

```
╔══════════════════════════════════════════════════╗
║     Frozen Wasteland — Cold Walker Character Sheet      ║
╠══════════════════════════════════════════════════╣
║ Name: ____________   Alias: ____________          ║
║ Motivation: ____________   Base: ____________      ║
╠══════════════════════════════════════════════════╣
║ Attribute      Value  Mod   Derived Attr     Value ║
║ Speed (SPD)      __    __    Movement (MV)       __   ║
║ Perception (PER) __    __    Premonition (FS)   __     ║
║ Guts (GUT)       __    __    Health (HP)         __    ║
║ Tech (TEC)       __    __    Panic Thresh (PT)  __     ║
║ Negotiation (NEG) __   __    Time Resist (TR)   __     ║
╠══════════════════════════════════════════════════╣
║ Zone Experience: __________                        ║
║ Trauma: __________   Status: □Unovercome / □Overcome ║
║ The One You're Still Searching For: __________    ║
║ Insight: __/3    Resolve: __/__    Panic: __      ║
╠══════════════════════════════════════════════════╣
║ Equipment:                                        ║
║ Armor: __________   Armor Value: +___             ║
║ Weapon: __________  Damage: ___  Range: ___       ║
║ Detector Model: ____  Range: __  Accuracy: __%    ║
║ Load: __/15    Time Crystals: __                  ║
╚══════════════════════════════════════════════════╝
```

---


# Chapter 3: Combat and Conflict System

## 3.1 Freeze Zone Round Structure

Each full round consists of two layers: the **Frozen Phase** (player actions) and the **Thaw Moment** (crisis reaction):

```
┌──────────────────────────────────────────┐
│              A Complete Round              │
│                                           │
│  [Frozen Phase]            [Thaw Moment]  │
│  1. GM secretly rolls Thaw Die → 2. GM describes awakening threat │
│  2. Players declare actions    3. Guts check │
│  3. Resolve actions            4. Player reaction actions │
│  4. Reveal Thaw Die result     5. Time re-freezes │
│     ├ Nothing → next round │
│     ├ Omen → Perception check │
│     └ Thaw → enter right column │
└──────────────────────────────────────────┘
```

### Declaration Order (Core Design)

**Players declare actions first → GM reveals Thaw Die result after.** Players always make their decisions without knowing whether the round will thaw.

### Action Types

| Action Type | Quantity per Round | Description |
|---|---|---|
| **Movement** | 1 time | Movement = Speed + 3 squares |
| **Major Action** | 1 time | A complex operation requiring focus |
| **Minor Action** | 1 time | A quick operation |
| **Free Action** | Unlimited | Speaking, dropping items |
| **Reaction** | 1 per round | Triggered during another's turn |

### Common Operation Action Costs

| Operation | Cost |
|---|---|
| Loot a small item | Minor Action |
| Loot a medium item | Major Action |
| Loot a valuable/large item | Major + Minor |
| Use a scanner to scan | Minor Action |
| Use a first-aid kit (self) | Minor Action |
| Use a first-aid kit (others) | Major Action |
| Use a Time Crystal | Minor Action |
| Assist a teammate's action | Minor Action (grants Advantage) |
| Watch a specific direction | Minor Action (Perception +2 in that direction) |

---

## 3.2 Thaw Moment Reaction Rules

### Full Procedure

```
Thaw Triggered
    ↓
[Step A] GM describes the awakening threat
    ↓
[Step B] All make Guts check vs Difficulty (DC)
    ├ Success → act normally
    ├ Failure → Rattled: −2 Movement this round + Disadvantage on actions
    └ Catastrophe (natural 1 (nat 1)) → Panic Attack: full Disadvantage + −2 Movement + Omen Difficulty (DC) +4
    ↓
[Step C] Players declare reaction action (choose one of five)
    ├ A. Run
    ├ B. Take Cover
    ├ C. Counterattack
    ├ D. Keep Looting
    └ E. Rescue the Frozen
    ↓
[Step D] Resolve reaction action + GM judges consequences
    ↓
[Step E] Time re-freezes → damage persists → pressure updates
```

### Guts Check Difficulty (DC) System

| Thaw Situation | Guts Difficulty (DC) |
|---|---|
| Minor threat + Omen warning | 10 |
| Moderate threat + Omen warning | 12 |
| Sudden with no warning | 14 |
| Major threat + no warning | 16 |
| Catastrophic (multiple threats at once) | 18 |

**Threat Distance Modifier**:

| Threat Distance | Difficulty (DC) Modifier |
|---|---|
| Far (over 10 squares) | −2 |
| Mid (5–10 squares) | ±0 |
| Near (2–5 squares) | +2 |
| Very close (within 1 square) | +4 |

---

### Reaction Option A: Run

- +2 squares Movement this round (adrenaline), but must move in a straight line
- Path obstacle: Speed check Difficulty (DC) 12; failure means falling Prone
- May dive for cover after movement ends
- If the threat gives chase: contested Speed check

### Reaction Option B: Take Cover

Move to a cover position; the cover's Defense directly adds to Defense (AC):

| Cover Quality | Physical Defense | Example |
|---|---|---|
| Poor | +1 | Overturned table |
| Ordinary | +2 | Edge of a concrete wall |
| Good | +3 | Reinforced concrete pillar |
| Excellent | +5 | Bunker-grade cover |

### Reaction Option C: Counterattack

Initiative determination: contested Speed (compare d20 + Speed modifier, higher wins).

| Attack Method | Check Method | Damage |
|---|---|---|
| Melee (improvised weapon) | d20 + Speed modifier vs Defense (AC) | 1d4 + Speed modifier |
| Melee (dedicated weapon) | d20 + Speed modifier vs Defense (AC) | per weapon |
| Firearm | d20 + Tech modifier vs Defense (AC) | per firearm |
| Thrown | d20 + Speed modifier vs Difficulty (DC) 10–15 | 1d4 + Speed modifier |
| Time Crystal device | d20 + Tech modifier vs Difficulty (DC) 14 | Re-freeze target 1d4 rounds |

### Reaction Option D: Keep Looting

- Must first pass a Guts check Difficulty (DC) 14
- Success → +50% loot yield, but fully exposed that round (threat attacks automatically hit)
- If taking damage: additional +1d4

### Reaction Option E: Rescue the Frozen

See §3.5 for detailed rules.

---

## 3.3 Damage System

### Health

**Health (HP) = Guts value × 2 + 10**

| Guts | 2 | 4 | 5 | 7 | 8 |
|---|---|---|---|---|---|
| Health (HP) | 14 | 18 | 20 | 24 | 26 |

> **Design Note: Health (HP) and Combat Risk**—In Frozen Wasteland, Health does not grow with "level." Health (HP) depends solely on the Guts attribute, so a veteran who has looted dozens of times differs little from a novice. This is a deliberate design choice: in the Frozen Wasteland, combat is always high-risk. A character's growth shows in their understanding of the Freeze Zone (Experience), abilities learned (Feats), and accumulated resources (Crystals and gear)—not in physical augmentation. Every time you choose to fight instead of fleeing or sneaking, you gamble with your life.

### Four Damage Types

| Type | Source | Mitigation |
|---|---|---|
| **Physical** | Explosions, falls, weapons, collapse | Armor Value reduces directly (for area damage such as explosions/collapses, Armor Value is calculated at ×2, minimum 1); ordinary attacks reduce to minimum 1 |
| **Time Damage** | Thaw splash, Crystal backlash | **Ignores armor**, only Tech modifier mitigates |
| **Frostbite** | Prolonged exposure, cold environment | Mitigated by Warming Gear. Each 3 points accumulated permanently −1 Speed |
| **Mental Damage** | Trauma triggers, witnessing horrors | Does not reduce Health (HP); increases Pressure value |

> **Armor Design Note**: Basic armor (such as Protective Suit +1) is suitable for blocking small physical damage, but has limited effect against explosions. Reflective armor (+3) gives an effective 6-point reduction against explosions—enough to withstand a small blast but not fully protect against a large collapse. In the Frozen Wasteland, the best defense is always "not being in the blast radius."

### Damage Source Reference

| Damage Source | Type | Base Damage |
|---|---|---|
| Grenade explosion (near, 3 squares) | Physical | 4d6 |
| Ceiling collapse (small) | Physical | 2d6 |
| Mutant creature claw | Physical | 1d6+2 |
| Time thaw splash (minor) | Time | 1d4 |
| Time thaw splash (severe) | Time | 2d6 |
| Prolonged frostbite (per round, −10°C) | Frostbite | 1d4 |

### Dying and Death

| Health (HP) State | Effect |
|---|---|
| Health (HP) > 50% | Normal |
| Health (HP) ≤ 50% | Light wound: Disadvantage on all physical actions |
| Health (HP) ≤ 25% | Heavy wound: Disadvantage on all actions + −2 Movement |
| Health (HP) = 0 | Dying: Prone, only 1 Minor Action per round. Each round make Guts Difficulty (DC) 12 consciousness check |
| Health (HP) < 0 | Unconscious. Each round Guts Difficulty (DC) 15; three failures means death |

### Healing

| Healing Method | Recovery | Condition |
|---|---|---|
| First-aid kit (self) | 1d6+2 Health (HP) | Minor Action |
| First-aid kit (others) | 1d6+4 Health (HP) | Major Action, must be adjacent |
| Time Crystal healing | 2d6 Health (HP) | Consume 2 Crystals (with 1d4 Time Damage risk) |
| Emergency self-heal | Recover to Health (HP)=1 | Only if Health (HP)<0, one-time use |
| Safe-zone rest (8 hours) | 1d6 + Guts modifier Health (HP) | Requires a non-Freezone |

---

## 3.4 Hazardous Item Rules

### Explosives

| Item | Rule |
|---|---|
| Detection Difficulty (DC) (discover) | Perception Difficulty (DC) 12 |
| Detection Difficulty (DC) (assess) | Perception Difficulty (DC) 15 |
| Detonation delay after thaw | 1 reaction round |

| Response | Check |
|---|---|
| Kick away | Speed Difficulty (DC) 12, push d6 squares away |
| Throw | Speed Difficulty (DC) 10, throw to designated location |
| Dive for cover | No check, cover Defense ×2 against explosion |
| Freeze | Tech Difficulty (DC) 14, consume 1 Crystal to re-freeze 1d4 rounds |
| Disarm | Tech Difficulty (DC) 16 (must be done before thaw) |

### Frozen Firearm

| Item | Rule |
|---|---|
| Detection Difficulty (DC) (discover) | Perception Difficulty (DC) 13 |
| Detection Difficulty (DC) (trajectory) | Perception Difficulty (DC) 16—accurately judge bullet flight path |
| Behavior after thaw | Bullet continues flying in original direction |

### Collapsing Structure

| Collapse Scale | Affected Squares | Damage | Dodge Difficulty (DC) |
|---|---|---|---|
| Small | 1×2 | 1d6 | 10 |
| Medium | 3×3 | 2d6 | 13 |
| Large | 5×5 | 4d6 | 16 |

### Frozen Attacking Creature

The most dangerous hazardous item: the attack has already reached its final stage, and after thaw it **automatically hits**.

| Response | Check |
|---|---|
| Move out of attack path | Speed Difficulty (DC) 10 |
| Preemptive counter | Contested Speed |
| Exploit (redirect attack at another threat) | Tech Difficulty (DC) 14 |
| Capture | Tech Difficulty (DC) 16 |

---

## 3.5 Rescue-the-Frozen Actions

### Carrying a Fully Frozen Person

- **Time required**: 2 rounds
- **Personnel required**: minimum 2 people (solo means double Disadvantage)
- **Check**: Combined Speed check (both roll d20 + Speed modifier, take the lower vs Difficulty (DC) 10)
- **Carry penalty**: each of the 2 carriers −3 squares Movement
- **Thaw interruption**: Guts Difficulty (DC) 12; failure means forced to drop and become Rattled

### Stabilizing a Critically Frozen Person

- **Time required**: 3 rounds

| Round | Operation | Check | Difficulty (DC) |
|---|---|---|---|
| 1 | Assess freeze degree and remaining time | Tech | 10 |
| 2 | Stop bleeding, immobilize, Crystal assist | Tech | 12 |
| 3 | Final stabilization, prepare to carry | Tech | 12 |

- **Countdown after thaw**: dies after 1d6 + 2 rounds (no treatment)
- Each Crystal consumed extends by 2 rounds

### Ending Loop Freeze

| Stage | Operation | Check |
|---|---|---|
| Observe | Watch the full loop (3–5 rounds) | Perception Difficulty (DC) 14 |
| Intervene | Insert at the loop's key moment | Guts Difficulty (DC) 14 + Tech Difficulty (DC) 14 |
| Break loop | Change one variable in the loop | Tech Difficulty (DC) 16 |

- Requires consuming 2 Time Crystals
- The intervener automatically takes 1d4 Time Damage

---

## 3.6 Status Effects

| Status | Trigger | Effect | Duration |
|---|---|---|---|
| **Rattled** | Failed Guts check | −2 Movement + Disadvantage | Current Thaw Moment |
| **Panic** | Natural 1 (nat 1) or Pressure over threshold | Full Disadvantage + −2 Movement + Omen Difficulty (DC) +4 | Until retreat or sedation |
| **Partial Freeze** | Time Damage ≥5 | Body part loses function (random d6) | Permanent (special treatment can cure) |
| **Time Disorientation** | Time Damage ≥4 | Perception Disadvantage + cannot judge distance | 1d4 rounds |
| **Frostbite (light)** | Frostbite accumulated 1–2 | Speed −1 | Until treated |
| **Frostbite (moderate)** | Frostbite accumulated 3–4 | Speed −2 + Disadvantage on Speed checks | Until treated |
| **Frostbite (severe)** | Frostbite accumulated ≥5 | Speed −3 + equivalent to Partial Freeze | Permanent risk |
| **Prone** | Knocked down | Movement zeroed + melee attackers have Advantage | Spend half Movement to stand |

---

## 3.7 Tactical Impact of the Five Thaw Rhythms

| Mode | Trait | Best Strategy | Main Trap |
|---|---|---|---|
| **Slumber Type** | Very low frequency, clear Omen | Loot with full effort, leave retreat buffer | Complacency |
| **Pulse Type** | Regular 6-round cycle | Count the rhythm, manage resource rhythm | Rhythm dependence |
| **Spasm Type** | Completely random, almost no Omen | Fast in fast out (3–4 rounds), light load | Over-optimism |
| **Chain Type** | One thaw triggers nearby | Isolate/disperse/preempt | Whole team caught in same chain |
| **Breath Type** | Gradual cycle, has transition phase | Three-stage goal gradation | Misjudging phase position |

---

## 3.8 Retreat Rules

### Retreat Trigger Timing
- Any Frozen Phase round declaration stage
- After a successful Perception check identifying an Omen
- Choosing "Run" as a reaction action and moving toward the boundary
- May call retreat when Health (HP) ≤ 25%
- Automatically attempts retreat when Panic triggers

### Freeze Boundary Crossing Check

**d20 + Tech modifier vs Difficulty (DC) 12** (standard)

| Difficulty (DC) Modifier Factor | Modifier |
|---|---|
| Slumber Type zone | −2 |
| Spasm Type zone | +2 |
| Carrying the Frozen | +2 |
| Using Time Crystal assist | −3 (consume 1 Crystal) |
| Teammate covering outside boundary | −2 |
| Injured (Health (HP) ≤ 50%) | +2 |

**Catastrophe (nat 1)**: Trapped in the boundary for 1 round, takes 1d4 Time Damage.

---

## 3.9 Monster/NPC Data Templates

> ▶ Monster/NPC data templates and examples are in **assets/怪物圖鑑.md**.

## 3.10 Downtime Activities

Between looting missions, the time characters spend in a safe zone (Downtime) is not only recovery, but also an opportunity to advance the story and strengthen characters. Downtime is typically 1–7 days.

### 3.10.1 Downtime Actions

Each character may choose **2 Downtime Actions** (for a roughly 1-week downtime) or **1 action** (for a roughly 1–3 day short rest):

| Action | Cost | Effect | Check (if needed) |
|---|---|---|---|
## 3.10 Downtime Activities

Between looting missions, the time characters spend in a safe zone (Downtime) is not only for recovery, but also an opportunity to advance the story and strengthen characters. Downtime usually lasts 1–7 days.

### 3.10.1 Downtime Actions

Each character may choose **2 Downtime Actions** (roughly a 1-week downtime) or **1 action** (roughly a 1–3 day short rest):

| Action | Cost | Effect | Check (if needed) |
|---|---|---|---|
| **Rest & Recovery** | None | Restore all Health (HP) + clear all Cold Fatigue + reset Panic Value to zero | None |
| **Trade & Barter** | Per transaction | Purchase gear, sell loot, exchange intel (Silver Tongue feat applies) | Negotiation (NEG) may haggle |
| **Gather Intel** | 10–50 Scrap Coins (buy drinks / bribe) | Gain info on 1 new Freeze Zone (parameters, threats, rumors), or advance main-plot clues | Negotiation (NEG) Difficulty (DC) 12–16 |
| **Training** | None | Choose one attribute; the first check using that attribute in the next session gains Advantage | Guts (GUT) Difficulty (DC) 12 (self-discipline) |
| **Gear Repair / Upgrade** | Material cost (per gear) | Repair damaged gear; can upgrade a detector to the next tier (requires parts) | Tech (TEC) Difficulty (DC) 12–16 |
| **Social Interaction** | None | Build relationships with specific NPCs, resolve personal storylines, advance "The One You're Still Searching For" clues | Narrative-led, occasional Negotiation (NEG) checks |
| **Time Crystal Research** | Consume 1 crystal | Experiment on a crystal—may discover new uses, decode stored time memories, or accidentally trigger a micro-thaw | Tech (TEC) Difficulty (DC) 14 |
| **Crafting** | Material cost + time | Make simple items (bandages, signal flares, simple tools); with suitable materials, may attempt advanced items | Tech (TEC) Difficulty (DC) 10–18 |
| **Help the Community** | None | Provide help in a settlement (free clinics, repairs, teaching)—raise reputation, may gain extra resources or intel | Varies by action |

### 3.10.2 Downtime Events (Optional)

The GM may roll d6 to trigger a downtime event:

| d6 | Event |
|---|---|
| 1 | **Trouble Comes Knocking**: Creditors, rivals, or church folk come looking for the characters—requires negotiation, evasion, or combat |
| 2 | **Unexpected Find**: Stumble upon a rare item in the market (GM picks an item fitting the current story) |
| 3 | **Word Gets Out**: The characters' last mission drew the attention of a faction—could be good or bad |
| 4 | **Old Acquaintance**: Meet an NPC known from the past—bringing news, a commission, or trouble |
| 5 | **Resource Shortage**: A settlement runs short of some resource (medicine / fuel / food)—prices rise, or provides new looting-mission motivation |
| 6 | **A Quiet Day**: No special event. Characters get a chance to reflect, write a journal, or have deep conversations with teammates (RP reward: gain 1 Insight Point) |



---

# Chapter 4: World & Narrative

## 4.1 Era Background

### Current Year: 17 Years After the Freeze (PF17)

Roughly 62% of land is covered by Freeze Zones; humanity fell from about 7.8 billion to an estimated fewer than 300 million. Old-world technology still exists—it is simply locked inside the Freeze Zones. There is no global government; the largest political unit is the refuge city. The Time Plunderer is the most respected and most feared profession of this age.

### The Genesis Catastrophe: Three Hypotheses (GM may choose or never reveal)

**Hypothesis A: The Themis Anomaly (Scientific Disaster)**
An out-of-control multinational quantum physics experiment created a self-sustaining "time standing wave." Spreading at the speed of light, it covered 40% of Earth's surface within 47 hours.

**Hypothesis B: The Whisper from Beyond (Supernatural)**
A being that does not belong to linear time invaded humanity's dimension. The Freeze Zone is its "shadow"; the Time Crystal is the residue of its "breath."

**Hypothesis C: Time Is Alive (Philosophical / Fable)**
Time itself is a living organism. Humanity's exponential acceleration over two centuries traumatized the temporal ecosystem; the Freeze is an immune response.

### How Freeze Zones Operate (Regardless of the Truth)

1. Time flow inside a Freeze Zone is zero—everything is locked at the Thaw Moment
2. A Freeze Zone has a boundary—a "time gradient band" where entrants feel a viscous sensation
3. Thaw is local and temporary—its range and duration are uncertain
4. Freeze Zones slowly expand
5. Creatures inside a Freeze Zone do not age—but whether consciousness still functions is known to no one

---

## 4.2 Geographical Imagery

Safe zones are islands; Freeze Zones are the ocean.

### Sights Inside a Freeze Zone

- **Visual**: Light "solidifies," shadows never move, hues lean blue. The Frozen are the most common sight—frozen in every posture
- **Sound**: Near-total silence—a "pressurized" quiet. Plunderers can only hear their own heartbeat and footsteps
- **Touch**: Air is completely still, no airflow. The time gradient band has a "viscous" feel
- **Texture of Time**: Subjective time distorts—some feel only minutes passed, only to find hours have gone by once outside

---

## 4.3 The Five Settlements

| Settlement | Location | Population | Feature |
|---|---|---|---|
| **Lakeside City** | Southwest shore of Lake Michigan | 85,000 | Capital of the Great Lakes Refuge Alliance; has a Plunderer school |
| **Steel Bridge Town** | Steel Bridge of the Ural Mountains | 12,000 | Eurasian trade hub; Plunderers hold the highest status |
| **Salt Village** | Beneath the Utah salt mines | 3,000 | Closed religious community; unwelcoming to Plunderers |
| **Floating Port** | Floating city in a Nordic fjord | 20,000 | Maritime settlement; North Sea trade node |
| **Three Towers** | Cape Peninsula, South Africa | 50,000 | Humanity's largest knowledge-preservation center |

---

## 4.4 The Five Factions

| Faction | Ideology | Scale | Attitude toward Plunderers |
|---|---|---|---|
| **Plunderers' Guild Union** | Plunderers should have autonomy and political representation | ~8,000–10,000 active Plunderers | — (own people) |
| **Frozen Research Society** | The Freeze can be scientifically understood, predicted, and reversed | ~500–800 researchers | Cooperative partners (fund missions for data) |
| **Relic Administration** | Pre-Freeze civilization heritage must be systematically preserved | ~1,000–1,500 members | Cooperative partners (designate rescue targets) |
| **Church of the Silent Hand** | The Freeze is a sacred event; stillness of time is a blessing | ~30,000–50,000 believers | Hostile (Plunderers are "desecrators") |
| **The Collector** | Collects and trades everything scarce, beautiful, and dangerous | ~200–300 core + thousands of mercenaries | Best client / worst boss |

---

## 4.5 The Five Thaw Rhythm Modes (GM Tool)

### Slumber Type—"This zone sleeps deeply"

- Thaws are extremely rare (once every few days to weeks); Omens are very obvious (30–60 minutes ahead)
- Good for: Beginner tutorials, supply-gathering missions
- Trap: Complacency—when a major thaw comes, its range is enormous

### Pulse Type—"It has a heartbeat, regular and steady"

- Thaw cycle is precise (e.g., thaw 5 minutes every 60 minutes); Omen is predictable (light flickers exactly 30 seconds ahead)
- Good for: Missions requiring tactical planning, puzzle scenes
- Trap: Routine breeds dependence; dependence breeds vulnerability

### Spasm Type—"You never know what the next second brings"

- Completely random; almost no Omen (1–4 seconds)
- Good for: High-risk high-reward, testing reflexes, horror themes
- GM technique: Use a real-world timer to roll every 5–10 minutes, letting players know you're rolling but not the result

### Chain Type—"One zone's thaw awakens the neighbor's"

- Thaw spreads: after each thaw, neighboring zones have a 50–80% chance to thaw
- Good for: Multi-zone missions requiring team coordination
- The team must divide duties: isolate / disperse / preempt

### Breath Type—"It's breathing. Slowly. Deeply."

- Time flow smoothly transitions between 0%–100%, with "inhale" and "exhale" phases
- Good for: Narrative-heavy missions, infiltration scenes, interacting with the Frozen
- At 50% flow there is an obvious "underwater" sensation; below 25% nearly impossible to move

---

## 4.6 Ethical Framework for the Frozen

### Four Types

**Fully Frozen**: After thawing, completely normal, with no memory of having been frozen.
- Ethical issue: Save them or not? Bring them back to the safe zone? What do you tell them?

**Critically Frozen**: After thawing, only seconds to minutes of consciousness, then death.
- Ethical issue: What can you do in those seconds? Hold their hand? Record their last words?

**Partially Frozen**: Part of the body is frozen forever—alive but incomplete.
- Ethical issue: Revive them but maimed—does that count as saving?

**Loop Frozen**: Each thaw returns them to the last moment before freezing, repeating forever.
- Ethical issue: End the loop or watch? Do you have the right to interrupt someone's eternity?

### GM Narrative Guidance

- No standard answer—the purpose of these questions is to make players think
- Make the Frozen the center of the scene, not the background
- Use concrete details: wounds, labored breathing, the expression on their face
- Give players genuine agency—they cannot save everyone, but they can choose how to respond

---

## 4.7 Sample Freeze Zones

### Sample A: The Still Supermarket (Beginner, Slumber Type)

A three-story supermarket Freeze Zone. Good for a first session, 2–4 hours.

- **Thaw Mode**: Slumber Type (starting threshold 19, −1 every 4 turns)
- **In-Zone Threats**: Collapsed ceiling fragments (minor collapse, 2d6), one frozen mutant dog (frozen-food section)
- **Supply Distribution**: Canned food on the first floor, medicine counter on the second, home goods on the third
- **The Frozen**: A cashier (fully frozen), an elderly person who collapsed by the medicine counter (critically frozen)

### Sample B: The Freezing Hospital (Intermediate, Pulse + Chain Type)

A five-story general hospital. 4–6 hours.

- **Thaw Mode**: Each department has a different pulse cycle; corridors are Chain Type
- **In-Zone Threats**: Emergency equipment on a cart (oxygen tanks with explosion risk), a frozen operating room
- **Ethical Core**: Patients in the ICU (multiple types of the Frozen)
- **Mystery**: The "Gazer" in the basement—a being seemingly unaffected by the Freeze

### Sample C: Countdown at the Military Checkpoint (High Difficulty, Spasm Type)

A freezing military facility containing unexploded ordnance and frozen crossfire scenes. 5–8 hours.

- **Thaw Mode**: Spasm Type (starting threshold 15, decreasing 1d4−1 per turn)
- **Special Rule**: Bullet-cloud navigation—multiple frozen volleys interweave into a 3D ballistic web
- **Core Risk**: The nuclear launch sequence frozen at the final 30-second countdown
- **High-Value Target**: 8+ Time Crystals in the command center

---

## 4.8 GM Operations Manual

### Game Preparation Checklist

**One Week Before**: Choose a Freeze Zone, set parameters, design key encounters, prepare Frozen encounters
**On the Day**: Print character sheets, prepare the Thaw Die tracking sheet, review the five rhythm modes
**During Play**: Record Thaw Threshold changes, track per-turn events, manage rhythm (tension ↔ breather)
**After Play**: Settle supplies and experience, record key choices (for use in later story)

### Thaw Die Tracking Sheet

```
Turn ｜ Thaw Threshold ｜ Roll Result ｜ Event ｜ Notes
  1  ｜   17    ｜   __    ｜ ___  ｜ 
  2  ｜   17    ｜   __    ｜ ___  ｜ 
  3  ｜   17    ｜   __    ｜ ___  ｜ 
  4  ｜   16    ｜   __    ｜ ___  ｜ 
 ... ｜  ...    ｜   ...   ｜ ...  ｜
```

### Omen Description Lexicon

| Sense | Minor Omen | Obvious Omen |
|---|---|---|
| **Visual** | Slight light distortion | Ripples appear on object surfaces |
| **Auditory** | Slight ear-pressure change | Low hum / ice-crack sound |
| **Tactile** | Tingling fingertips | Time gradient band fluctuates |
| **Psychological** | Vague unease | Distorted time perception |

### Handling Common Issues

- **Players refuse to enter the Freeze Zone**: Make plundering an attractive choice—hungry NPCs, scarce medicine
- **Death by thaw**: Provide escape chances but don't overprotect—Frozen Wasteland is dangerous
- **Saving everyone**: Resource limits—backpack space, time, and manpower are all limited
- **Rhythm fatigue**: Intersperse safe-zone social scenes, NPC interaction, world-building reveals
- **PvP conflict**: Establish a Plunderer code of honor so betrayal carries narrative weight

---

## 4.9 Module Framework

### One-shot Structure

1. **Opening (15 min)**: Base introduction, mission briefing, characters meet one another
2. **Entry (10 min)**: Travel to the Freeze Zone boundary, first taste of the atmosphere
3. **Exploration & Looting (60–90 min)**: Main gameplay content, 2–4 thaw events
4. **Ethical Dilemma (20 min)**: Frozen encounter, major decision
5. **Retreat & Settlement (15 min)**: Exit the Freeze Zone, settle supplies, narrative wrap-up

### Continuous Campaign Framework

- **Sessions 1–3**: Slumber Type and Pulse Type, build team rapport
- **Sessions 4–6**: Introduce Chain Type and Breath Type, deepen faction relationships
- **Sessions 7–9**: Spasm Type high-risk missions, advance "The One You're Still Searching For" storyline
- **Sessions 10+**: Reveal Genesis Hypothesis clues, face the ethical endgame

---

# Glossary

| Chinese | Abbreviation | Definition |
|---|---|---|
| Difficulty Level | Difficulty (DC) | The target number a check must reach |
| Thaw Threshold | UT | Base value the GM secretly compares the Thaw Die against |
| Attribute Modifier | AM | Attribute value − 5, added to the d20 check |
| Disadvantage | — | Roll 2d20, take the lower |
| Advantage | — | Roll 2d20, take the higher |
| Critical Success | — | Natural roll of 20 |
| Catastrophe | — | Natural roll of 1 |
| Panic Value | PAN | A value tracking a character's psychological pressure |
| Panic Threshold | Panic Threshold (PT) | Guts × 2 + 5; exceeding it causes Panic |
| Omen | Omen | The warning phenomenon when the Thaw Die equals the threshold |
| Movement | Movement (MV) | Speed + 3 squares / turn |
| Time Resistance | Time Resistance (TR) | Tech modifier; resists temporal anomalies |
| Resolve Point | RP | Starting = Guts modifier (minimum 1); usable for special abilities |
| Insight Point | IP | Gained from finding clues; usable for rerolls or questions |

---

# Appendix A: Player Quick Reference

| What I want to do | Roll what | Against |
|---|---|---|
| Do something risky | d20 + Attribute Modifier | Difficulty (DC) (declared by GM) |
| Do anything while in Panic | 2d20 take lower + Attribute Modifier | Difficulty (DC) |
| After using Time Shield | 2d20 take higher + Attribute Modifier | Difficulty (DC) |
| Notice thaw Omens | d20 + Perception modifier | Omen Difficulty (DC) |
| Stay calm during a thaw | d20 + Guts modifier | Difficulty (DC) 10 (with warning) / 14 (without) |
| Judge Freeze Zone type | d20 + Tech modifier | Difficulty (DC) 8–18 |
| Soothe a panicking teammate | d20 + Negotiation modifier | Difficulty (DC) 12 |

---
