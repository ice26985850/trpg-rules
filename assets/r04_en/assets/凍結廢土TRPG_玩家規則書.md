# Frozen Wasteland TRPG — Player Rulebook v1.1

> **Codename:** `frozen-wasteland-trpg`
> **Design Premise:** In the apocalypse, time congeals within localized regions. You can step into a frozen world and plunder its supplies—but you never know whether the next second will bring a thaw. Some of the frozen are still alive.
> **Design Philosophy:** "The apocalypse is not a ruin of space, but a fragment of time."
> **Emotional Tone:** Taut, neurotic tension—not fear of monsters, but fear of "the second time starts flowing again."

---


# Chapter One: Core Rules

## 1.1 The Dice System

### Base Resolution Die: d20 + Attribute Modifier

All risky action checks use **one 20-sided die (d20)**, plus the modifier of the relevant attribute, against the target Difficulty (DC).

### Why d20

The linear distribution of the d20 (each face 5% chance) creates a "every roll is a gamble" tension that fits perfectly with the "taut, neurotic" emotional tone of Frozen Wasteland. There is no comfort of a bell curve—you can never calculate the result precisely.

### Roll Type Overview

| Roll Type | Dice Used | Trigger | Roller |
|---|---|---|---|
| **Attribute Check** | d20 + Attribute Modifier | Character attempts a risky action | Player |
| **Disadvantage Check** | 2d20 take lower + Attribute Modifier | Panic, unfavorable environment, overload | Player |
| **Advantage Check** | 2d20 take higher + Attribute Modifier | Thorough preparation, assisting action, Time Shield | Player |
| **Thaw Die** | d20 vs Thaw Threshold | Each turn inside the Freeze Zone | GM (secret) |
| **Guts Check** | d20 + Guts Modifier | At the Thaw Moment, witnessing a horrific scene | Player |
| **Contest Check** | Both sides d20 + modifier, higher wins | Chase, grapple, stealth vs. perception | Both sides |

---

## 1.2 The Five Attributes

| Attribute | Abbrev. | Meaning | Role in Freeze Zone | Starting Range | Max |
|---|---|---|---|---|---|
| **Speed** | Speed (SPD) | Movement, reaction speed | Flee at the Thaw Moment—every square is life or death | 2–8 | 10 |
| **Perception** | Perception (PER) | Observation, prediction, intuition | Read the Freeze Zone's "micro-expressions"—Time Rifts, slight object movement | 2–8 | 10 |
| **Guts** | Guts (GUT) | Composure, willpower, risk tolerance | Hands that don't shake in the Freeze Zone—Rattled means everything collapses | 2–8 | 10 |
| **Tech** | Tech (TEC) | Device operation, mechanical understanding, evaluation | Operate detectors, disarm hazards, assess freeze stability | 2–8 | 10 |
| **Negotiation** | Negotiation (NEG) | Persuasion, negotiation, social influence | Sell loot, deal with survivors | 2–8 | 10 |

### Attribute Allocation

**Plan A: Free Allocation (recommended)**—25 points freely assigned among the five attributes, each at minimum 2, maximum 8.

**Plan B: Quick Arrays**—

| Array Name | Attribute Values | Suited For |
|---|---|---|
| Well-rounded | 6, 5, 5, 5, 4 | No glaring weakness |
| Specialist | 8, 5, 5, 4, 3 | One extreme strength, clear weakness |
| Iron Gut | 5, 4, 8, 5, 3 | Exceptional Guts |
| Negotiator | 5, 5, 4, 3, 8 | Thrives in the base |
| Techie | 4, 5, 5, 8, 3 | Gadgets never fail |

**Plan C: Roll (not advised for beginners)**—Roll 5d10, take the first five results. Allow one reroll of a result below 3.

### Attribute Modifier Table

**Modifier = Attribute Value − 5**

| Attribute Value | Modifier | Description |
|---|---|---|
| 1 | −4 | Nearly crippled |
| 2 | −3 | Clearly disadvantaged |
| 3 | −2 | Below average |
| 4 | −1 | Slightly weak |
| **5** | **+0** | **Average human** |
| 6 | +1 | Slightly better |
| 7 | +2 | Clearly excellent |
| 8 | +3 | Professional grade |
| 9 | +4 | Legendary (requires progression to unlock) |
| 10 | +5 | Human limit |

---

## 1.3 Derived Attributes

| Derived Attribute | Calculation | Use |
|---|---|---|
| **Movement (MV)** | Speed value + 3 squares/turn | Movement distance per turn inside the Freeze Zone |
| **Premonition Sense (FS)** | Perception modifier | Bonus to checks for detecting Thaw Omens |
| **Panic Threshold (PT)** | Guts value × 2 + 5 | Panic when stress exceeds this value |
| **Time Resistance (TR)** | Tech modifier | Resist side effects of temporal anomalies |
| **Health (HP)** | Guts value × 2 + 10 | Capacity to withstand damage |

---

## 1.4 Attribute Checks

### Basic Procedure

```
GM declares: Action + Attribute + Difficulty (DC)
        ↓
Player rolls d20 + Attribute Modifier
        ↓
Compare result vs Difficulty (DC) → Success / Failure
```

### Difficulty Ladder

| Difficulty (DC) | Difficulty Level | Success Rate (mod +0) | Typical Scenario |
|---|---|---|---|
| 5 | Trivial | 80% | Hear footsteps in a quiet environment |
| 8 | Simple | 65% | Recognize common Freeze Zone omens |
| 10 | Ordinary | 55% | Quickly clamber over obstacles |
| **12** | **Moderate** | **45%** | **Notice subtle Time Rifts** |
| 15 | Hard | 30% | Disarm explosives at the Thaw Moment |
| 18 | Very Hard | 15% | Stabilize a Frozen One on the verge of collapse |
| 20 | Nearly Impossible | 5% | Close a Time Rift bare-handed |

### Binary Pass/Fail + Extreme Outcomes

| Roll Result | Term | Effect |
|---|---|---|
| Natural 20 | **Critical Success** | Unconditional success + extra positive effect |
| ≥ Difficulty (DC) (not natural 20 (nat 20)) | **Success** | Action achieves intended effect |
| < Difficulty (DC) (not natural 1 (nat 1)) | **Failure** | Action not achieved, possible side effects |
| Natural 1 | **Catastrophe** | Unconditional failure + extra negative effect |

### Disadvantage Rolls

When a character is in a state such as Panic or an unfavorable environment, roll **2d20 take the lower**, then add the Attribute Modifier.

| Normal Success Rate | Success Rate with Disadvantage | Equivalent Penalty |
|---|---|---|
| 65% (need 8+) | 42.3% | −4.5 |
| 55% (need 10+) | 30.3% | −5.0 |
| 45% (need 12+) | 20.3% | −5.0 |
| 30% (need 15+) | 9.0% | −4.2 |

> Disadvantage hits moderate difficulty (Difficulty (DC) 10–15) the hardest—precisely the most common check range in the Freeze Zone.

### Advantage Rolls

In situations such as thorough preparation, ally assistance, or Time Shield, roll **2d20 take the higher**. When Advantage and Disadvantage are both present, they cancel out and you roll 1d20 normally.

---

## 1.5 The Thaw Die Mechanic (Core System)

### Basic Mechanic

At the end of each turn inside the Freeze Zone, the GM secretly rolls 1d20 (the Thaw Die) and compares it to that zone's **Thaw Threshold**:

| Roll Result | Event | Effect |
|---|---|---|
| **Roll < Threshold** | Time Holds | Nothing happens, turn proceeds normally |
| **Roll = Threshold** | Omen Appears | Player makes a Perception check (see below) |
| **Roll > Threshold** | Local Thaw | Triggers Thaw Moment rules (see Chapter 3) |

### Thaw Threshold Decline

The Thaw Threshold gradually lowers with each turn the players remain in the Freeze Zone—the longer you stay, the more dangerous it becomes.

**Baseline model—Pulse Type** (most common):

| Turn Range | Thaw Threshold | P(Nothing) | P(Omen) | P(Thaw) | Cumulative P(at least one Thaw) |
|---|---|---|---|---|---|
| 1–3 | 17 | 80% | 5% | 15% | 38.6% |
| 4–6 | 16 | 75% | 5% | 20% | 70.5% |
| 7–9 | 15 | 70% | 5% | 25% | 89.7% |
| 10–12 | 14 | 65% | 5% | 30% | 97.3% |
| 13–15 | 13 | 60% | 5% | 35% | 99.6% |
| 16+ | 12 | 55% | 5% | 40% | ≈100% |

### Threshold Parameters of the Five Rhythm Patterns

| Pattern | Starting Threshold | Decline Rate | Minimum Threshold | Trait |
|---|---|---|---|---|
| **Slumber Type** | 19 | −1 every 4 turns | 14 | Omen Difficulty (DC) −3, suited for beginners |
| **Pulse Type** | 17 | −1 every 3 turns | 10 | Regular decline, trackable |
| **Spasm Type** | 15 | 1d4−1 per turn | 5 | Completely unpredictable |
| **Chain Type** | 18 | −1 every 2 turns; −2 when an adjacent zone thaws | 6 | One thaw accelerates all |
| **Breath Type** | 16 | −1/turn ×3, then +3 reset, cycling | 10 | Has a breathing window |

### Omen Perception Check

When the Thaw Die equals the threshold, the player may make a Perception check against that zone's **Omen Difficulty (DC)**:

| Omen Clarity | Difficulty (DC) | Typical Description |
|---|---|---|
| Very Obvious | 8 | Sound of ice crystals cracking, obvious spatial distortion |
| Obvious | 10 | Objects begin to move slightly, temperature shifts abruptly |
| Moderate | 12 | Subtle temporal ripples, abnormal light refraction |
| Subtle | 15 | Nearly imperceptible energy fluctuations |
| Barely Perceptible | 18 | Only the truly sharp can sense it |

**Check Success Benefits**:
- Success (≥ Difficulty (DC)): Learn "a thaw will occur this turn," may take one preparatory action before the thaw
- Critical Success (nat 20): As above + exactly know the thaw range and which object will awaken
- Failure: Not detected → caught off guard at the thaw (Guts check Difficulty (DC) +2)

### Omen Detection Rate by Perception Level

| Perception Mod | Difficulty (DC) 8 (Obvious) | Difficulty (DC) 10 | Difficulty (DC) 12 (Moderate) | Difficulty (DC) 15 | Difficulty (DC) 18 (Subtle) |
|---|---|---|---|---|---|
| −3 (Perception (PER) 2) | 50% | 40% | 30% | 15% | 5% |
| +0 (Perception (PER) 5) | 65% | 55% | 45% | 30% | 15% |
| +2 (Perception (PER) 7) | 75% | 65% | 55% | 40% | 25% |
| +3 (Perception (PER) 8) | 80% | 70% | 60% | 45% | 30% |

> Even the sharpest character (Perception (PER) 8) has only a 30% detection rate against "barely perceptible" omens. **No one can fully control the Freeze Zone.**

---

## 1.6 Guts Checks and the Panic System

### Guts Check at the Thaw Moment

When a thaw occurs, all players within the thaw range must immediately make a Guts check:

| Situation | Difficulty (DC) | Failure Effect |
|---|---|---|
| With Omen Warning (detected successfully) | 10 | Rattled this turn (Movement −2 + Disadvantage on actions) |
| No Warning (undetected or no omen) | 14 | Rattled + Panic Value +1 |
| Thaw is a known major threat | Difficulty (DC) +2~4 | By threat intensity |
| Thaw is an ally/innocent | Difficulty (DC) −2 | GM discretion |

### Guts Modifier vs Key Difficulty (DC) Success Rates

| Guts Mod | Difficulty (DC) 10 (prepared) | Difficulty (DC) 14 (caught off guard) | Difficulty (DC) 16 (extreme) |
|---|---|---|---|
| −3 (Guts (GUT) 2) | 40% | 20% | 10% |
| +0 (Guts (GUT) 5) | 55% | 35% | 25% |
| +2 (Guts (GUT) 7) | 65% | 45% | 35% |
| +3 (Guts (GUT) 8) | 70% | 50% | 40% |

> Even a character with the highest Guts has only a 50% chance of staying composed against an unexpected thaw. **No one is immune to fear.**

### Panic Value

Panic Value tracks a character's psychological stress inside the Freeze Zone, starting at 0.

**Panic Increase**:

| Event | Panic Value Change |
|---|---|
| Thaw occurs (Guts check failed) | +2 |
| Thaw occurs (Guts check succeeded) | +1 |
| Every 3 turns spent in the Freeze Zone | +1 (environmental pressure) |
| Witness an ally injured/downed | +3 |
| Sustain damage yourself | +2 |
| Check Catastrophe (nat 1) | +1 |

**Panic Release**:

| Event | Panic Value Change |
|---|---|
| Retreat to a safe zone and rest 1 hour | −3 |
| Use a Sedative | −2 (one-time) |
| Successfully stabilize a Critical Frozen One | −2 |
| Complete looting objective and withdraw | Reset to 0 |

### Panic Threshold

**Panic Threshold = Guts value × 2 + 5**

| Guts Value | Panic Threshold | Endurance |
|---|---|---|
| 2 | 9 | Extremely fragile—a single thaw may cause panic |
| 5 | 15 | Average—can withstand 3–4 turns of pressure |
| 8 | 21 | Iron guts—almost never panics on a mission |

### Panic Trigger

When the Panic Value **>** Panic Threshold (exceeding, not equaling), the character enters the **Panic state**:

- All attribute checks at **Disadvantage** (2d20 take lower)
- Movement −2
- Cannot perform assist actions
- Premonition Sense (FS) check Difficulty (DC) +4

The Panic state persists until the Panic Value drops below the threshold.

---

## 1.7 Movement

**Movement (MV) = Speed value + 3 squares/round** (each square ≈ 1.5 meters)

| Speed | Movement | Description |
|---|---|---|
| 2 | 5 squares | Dragging one's feet |
| 5 | 8 squares | A normal person running |
| 7 | 10 squares | A well-trained plunderer |
| 8 | 11 squares | Gale—swiftly breaks away at the Thaw Moment |

- Each round: Move + one action is the standard configuration
- If you only move and take no other action, movement distance ×1.5
- When carrying the Frozen, Movement −3
- In the Panic state, Movement −2


## 1.8 Environmental Hazard System

The world of Frozen Wasteland itself kills. The following four environmental hazards share a unified grading system.

### 1.8.1 Cold Hazard

| Level | Environmental Example | Effect | Check (every 5 rounds) |
|---|---|---|---|
| **Mild Cold** | Winter outdoors in safe zones, edges of Freeze Zones | No immediate effect, but prolonged exposure accumulates Cold Fatigue (see §1.9) | Guts (GUT) Difficulty (DC) 8 |
| **Moderate Cold** | Interior of Freeze Zones, cold storage, night wasteland | Movement −1 per round; accumulates Cold Fatigue | Guts (GUT) Difficulty (DC) 12 |
| **Severe Cold** | Deep Freeze Zones, blizzards, polar wasteland | Movement −2 per round + Disadvantage on Speed checks; rapidly accumulates Cold Fatigue | Guts (GUT) Difficulty (DC) 16 |
| **Lethal Cold** | Periphery of the Time Storm Eye, liquid nitrogen leak zones | 1d4 Frostbite damage per round; immediately accumulates Cold Fatigue | Guts (GUT) Difficulty (DC) 20 |

**Warming Gear** can lower the effective hazard level by 1–2 tiers (e.g.: Protective Suit provides −1 tier, hot pack −1 tier, Time Isolation Suit −2 tiers).

### 1.8.2 Darkness/Visibility

| Level | Situation | Effect |
|---|---|---|
| **Dim Glow** | Moonlight, distant firelight, edge of flashlight beam | Disadvantage on Perception (PER) checks (vision-related) |
| **Faint Light** | Single flashlight, candlelight | Disadvantage on Perception (PER) checks + Movement −1 (can't see footing) |
| **Total Darkness** | No light source | Automatic failure on Perception (PER) checks (vision-related); Movement −3; unable to read/identify fine detail |

**Light Sources**: A hand-crank flashlight provides 10 squares of Dim Glow / 5 squares of Faint Light. A flare provides 30 squares of Faint Light / 15 squares of normal illumination (lasts 5 rounds). A detector screen provides only its own 1 square of Dim Glow.

### 1.8.3 Noise Hazard

The silence of the Freeze Zone is a double-edged sword—you can hear threats approaching, and threats can hear you too.

| Action | Noise Level | Audible Distance | Effect |
|---|---|---|---|
| **Silent Action** (successful stealth) | 0 | Imperceptible | — |
| **Whispered Conversation / Slow Movement** | 1 | 5 squares | Nearby threats perceive with Perception Difficulty (DC) 15 |
| **Normal Conversation / Normal Movement** | 2 | 10 squares | Threats perceive with Perception Difficulty (DC) 10 |
| **Loud Shout / Running / Metal Clash** | 3 | 20 squares | Threats automatically perceive direction |
| **Gunshot / Explosion / Structural Collapse** | 4 | 50 squares | Area-wide alert + **Thaw Die trigger bonus +2** |

> **Firearm Warning**: Using firearms in a Freeze Zone, the noise not only attracts threats, but also accelerates the expansion of Time Rifts through vibration.

### 1.8.4 Starvation and Thirst

| Status | Trigger Condition | Effect |
|---|---|---|
| **Normal** | Eat 1 Ration + drink water daily | None |
| **Hunger** (no food for 24 hours) | Last ate over 24 hours ago | Disadvantage on all physical checks |
| **Starving & Thirsty** (no food for 48 hours or no water for 24 hours) | — | Disadvantage on all checks + Movement −2 |
| **Exhaustion** (no food for 72 hours) | — | Disadvantage on all checks + Movement −3 + Health (HP) −1 per hour |
| **Dehydration** (no water for 48 hours) | — | Disadvantage on all checks + Health (HP) −1d4 per 2 hours |

**Rations**: 1 emergency Ration (1 unit weight) sustains for 1 day. A Water Purification Tablet purifies 1 liter of water (1 day's supply).

---

## 1.9 Cold Fatigue

Cold Fatigue is the cumulative effect of prolonged exposure to low-temperature environments, and is a different system from Frostbite (see §3.3).

### 1.9.1 Fatigue Levels

| Level | Trigger | Effect | Recovery Condition |
|---|---|---|---|
| **Level 1: Shivering** | 5 rounds in Moderate Cold / prolonged time in Mild Cold | Disadvantage on Speed checks (trembling affects fine motor control) | Rest 1 hour back in safe zone / stay near heat source 10 minutes |
| **Level 2: Sluggish** | Reached Level 1 + 5 more rounds of exposure / 3 rounds in Severe Cold | Speed −2 + Disadvantage on Perception (PER) checks (dulled senses) + Movement −1 per round | Rest 4 hours in safe zone / use hot pack to immediately drop to Level 1 |
| **Level 3: Hypothermia** | Reached Level 2 + 5 more rounds of exposure / 1 round in Lethal Cold | Speed −4 + Disadvantage on all checks + Health (HP) −1 per round (body heat loss) | Rest 8 hours in safe zone + Medicine Difficulty (DC) 12 / emergency warming measures |

### 1.9.2 Fatigue Checks

Whenever a Cold check triggers (usually every 5 rounds), the character makes a **Guts (GUT) + Guts Modifier vs Environment Difficulty (DC)** check (see §1.8.1 Cold Hazard level table):

- **Success**: Resist the cold, fatigue level does not increase
- **Failure**: Fatigue level +1
- **Catastrophe (nat 1)**: Fatigue level +2

### 1.9.3 Special Rules

- **Warming Gear** can grant Advantage on Guts (GUT) checks (e.g. hot packs)
- **Time Crystals** can serve as emergency heat sources: spend 1 crystal to immediately lower fatigue by 1 level (crystals release heat when discharging time energy)
- **Panic characters**: while in the Panic state, Cold Fatigue accumulates twice as fast (check every 3 rounds instead)

---

## 1.10 Freeze Levels

Some Freeze Zones contain "Progressive Freeze"—time does not fully stand still, but flows at an extremely slow speed, causing entrants to be gradually frozen.

### 1.10.1 Freeze Level Table

| Level | Effect | Appearance |
|---|---|---|
| **Level 0: Normal** | No effect | — |
| **Level 1: Stasis** | Movement −2; all actions cost 1 extra Minor Action (movements slowed) | Skin slightly pale, movements slightly stuttering |
| **Level 2: Half-Frozen** | Movement −4; each round may perform only 1 Major Action OR move (not both); Speed Modifier −3 | Limbs stiff, body temperature drops sharply, breath visible as ice mist |
| **Level 3: Full Freeze** | Character is frozen in time—cannot act, cannot perceive the outside world, cannot be damaged normally (equivalent to the Frozen) | Body completely still, covered in thin frost |

### 1.10.2 Freeze Accumulation and Resistance

- **Accumulation Trigger**: While in a Progressive Freeze environment, every 3 rounds make a **Tech (TEC) + Tech Modifier vs Difficulty (DC)** check (set by zone, usually 12–16)
- **Success**: Resist freeze, level does not increase
- **Failure**: Freeze level +1
- **Catastrophe (nat 1)**: Freeze level +2

### 1.10.3 Thawing

| Method | Requirement | Effect |
|---|---|---|
| **Leave the Freeze Zone** | Exit the zone that triggers freezing | Level 1 clears immediately; Levels 2–3 drop by 1 per round (in safe zone) |
| **Time Crystal Treatment** | Spend 2 crystals, Tech (TEC) Difficulty (DC) 14 | Immediately lower by 2 levels |
| **Defrost Agent** | Spend 1 Defrost Agent (see §2.2 Equipment) | Immediately lower by 1 level, and become immune to that zone's freeze accumulation for the next 3 rounds |
| **Share Body Heat with Teammate** | Teammate spends a Major Action, Guts (GUT) Difficulty (DC) 10 | Target gains Advantage on their next Freeze Resistance check |

> **Characters at Full Freeze (Level 3)** cannot thaw themselves—a teammate must carry them out of the Freeze Zone and use a Defrost Agent or Time Crystal to thaw them from the outside.

---

## 1.11 Stealth Rules

In the Freeze Zone, sometimes the best strategy is neither running nor fighting—but remaining undetected.

### 1.11.1 Stealth Check

When stealthing, the character rolls **Speed (SPD) + Speed Modifier vs the threat's Perception (PER) Modifier + 10** (passive perception), or the Difficulty (DC) set by the GM:

| Situation | Difficulty (DC) |
|---|---|
| Open space, no cover, normal light | 18 |
| Partial cover (shelves, vehicles), dim glow | 14 |
| Ample cover (corners, ruins), faint light | 10 |
| Full concealment, total darkness | Automatic success (unless the threat has special senses) |

### 1.11.2 Stealth Modifiers

| Situation | Modifier |
|---|---|
| Wearing heavy armor (Armor Value ≥3) | Disadvantage |
| Light load (burden ≤5 units) | Advantage |
| Panic state | Automatic failure (trembling and rapid breathing cannot be hidden) |
| Carrying ≥6 Time Crystals | Disadvantage (the crystals' time-noise leaks the location) |
| Silent Step feat | Advantage |
| Teammate assists as distraction | Advantage (assistant must spend a Minor Action) |

### 1.11.3 Consequences of Being Detected

| Threat Type | Reaction |
|---|---|
| **Mutated Creature** | Immediately attacks or goes alert (Perception (PER) contest determines surprise round) |
| **Hostile Plunderer** | May ambush, evade, or negotiate (depending on NPC disposition) |
| **Environmental Threat** | Being detected does not trigger environmental threats—but failed stealth is often accompanied by noise (see §1.8.3), which may trigger a Thaw |
| **The Frozen** | The Frozen cannot perceive stealth characters—but nearby awakened threats might |

### 1.11.4 Team Stealth

- When the whole team stealths, use the check result of the character with the **lowest Speed (SPD) Modifier** as the team result
- The team may split into groups—after splitting, each group checks independently
- "Chain Type Coordinator" experience can use a warning action to grant stealth Advantage to teammates

---

## 1.12 Looting and Searching

### 1.12.1 Search Check

Searching an area (e.g. a room, a row of shelves, a vehicle) costs **1 Major Action** (small area) or **1 round** (large area). Make a **Perception (PER) + Perception Modifier vs Difficulty (DC)** check (set by GM per area):

| Area State | Difficulty (DC) | Expected Haul |
|---|---|---|
| Already looted | 18 | Misc items worth 1d4 Scrap Coins |
| Partially disordered | 12 | Basic supplies (rations, water, bandages) |
| Mostly intact | 10 | Good supplies (medical kits, tools, few crystal shards) |
| Never searched | 8 | Abundant supplies (roll on the area's supply table) |

**Degree of Success Effects**:
- Bare success (≥ Difficulty (DC)): gain base haul
- Great success (≥ Difficulty (DC)+3): gain one extra item
- Critical Success (nat 20): discover hidden or high-value item

### 1.12.2 Universal Loot Table (d20)

> ▶ The Universal Loot Table (d20) is found in **assets/物品圖鑑.md**.

### 1.12.3 Quick Looting (Time-Saving Rule)

If the GM does not want to roll per area, a simplified rule may be used:

- **Shallow Looting** (edge areas): automatically gain 2d4 rations + 2d6×10 Scrap Coins + 25% chance to gain 1 crystal shard
- **Mid Looting**: 3d6 rations + 3d6×10 Scrap Coins + 1 medical kit + 50% chance to gain 1d3 crystals
- **Deep Looting**: 4d8 rations + 4d8×10 Scrap Coins + 2 medical kits + 2d4 crystals + 15% chance to gain a rare item

---

## 1.13 Design Note: Attributes-as-Skills

Frozen Wasteland uses a simplified **"Attributes-as-Skills"** design—there is no separate skill list. All actions map directly to the Five Attributes, and the GM judges the most relevant attribute and sets the Difficulty (DC).

**Design Rationale**:
- The pace of the Freeze Zone demands fast adjudication—looking up skills in a table would slow the tension of the Thaw Moment
- The Five Attributes already cover the core action dimensions of Frozen Wasteland: movement/reaction (Speed), observation/anticipation (Perception), will/calm (Guts), operation/understanding (Tech), social/negotiation (Negotiation)
- Character differentiation is expressed through Motivation abilities, Zone Experience, Trauma, and Feats, rather than fine-grained skill point allocation

**GM Adjudication Principles**:
- If an action clearly falls under a single attribute → use that attribute directly
- If it spans multiple attributes → choose the most core attribute, or allow the player to use the higher attribute but at Difficulty (DC) +2
- If the player proposes a creative alternative → encourage it! Change the attribute mapping, Difficulty (DC) stays the same or drops slightly



# Chapter 2: Character Creation

## 2.1 Six Steps of Character Creation

### Step 1: Motivation — Why did you enter the Freeze Zone?

| Motivation | Extra Resources | Motivation Ability | Narrative Tag |
|---|---|---|---|
| **Survivor** | Large backpack (burden +5), extra rations ×2 | **Collective Responsibility**: Advantage on Guts checks when protecting teammates | `breadwinner` `in-debt` |
| **Seeker** | Clue notes + faded photo, flares ×2 | **Never Give Up**: spend 1 Resolve Point to gain Advantage on Perception checks related to finding the target | `obsessive` `haunted-by-the-past` |
| **Crystal Hunter** | Modified detector (70% accuracy), black-market contact | **Keen Nose**: automatic success when appraising Time Crystal value | `greedy` `well-connected` |
| **Explorer** | Research notes, analysis toolkit | **Scholar's Eye**: when entering a new Freeze Zone, the GM reveals one unique feature | `curious` `naive` |
| **Atoner** | Relic (custom), starts with 1 extra Resolve Point | **No More Running**: when in a Trauma-like situation, spend 1 Resolve Point to turn Disadvantage into normal | `guilty` `self-destructive` |

### Step 2: Attribute Allocation

25 points freely allocated to the Five Attributes, each 2–8. Calculate derived attributes:
- Movement = Speed + 3
- Premonition Sense = Perception Modifier
- Panic Threshold = Guts × 2 + 5
- Time Resistance = Tech Modifier
- Health = Guts × 2 + 10
- Starting Resolve Points = Guts Modifier (minimum 1)

### Step 3: Zone Experience — Which rhythm are you familiar with?

| Experience Type | Experience Advantage | Experience Intuition (passive) |
|---|---|---|
| **Slumber Type Veteran** | In Slumber Type zones, gains Advantage on Perception checks for Omens | Panic pressure accumulates only once every two rounds |
| **Pulse Type Dancer** | Can predict the exact round count of the next Thaw (Tech Difficulty (DC) 10) | Movement +1 in regular-thaw environments |
| **Spasm Type Gambler** | Guts check at the Thaw Moment at Difficulty (DC) −2 | Panic pressure increases by only half each Thaw |
| **Chain Type Coordinator** | Spend an action to warn teammates the next zone is about to Thaw | Teammates within line of sight gain +1 on Guts checks |
| **Breath Type Stalker** | Sense whether the current phase is "inhale" or "exhale" (no roll needed) | Movement speed is not halved during the Breath Type progressive phase |

### Step 4: Trauma — What did you lose in the Freeze Zone?

Trauma has a **two-sided effect**: disadvantageous situations weigh you down, while advantageous situations give you superhuman Resolve.

| Trauma | Trauma Effect (Disadvantage) | Resolve Effect (Advantage) |
|---|---|---|
| **Lost Comrade** | Disadvantage on Guts checks when a teammate is in danger | Recover 1 Resolve Point when successfully protecting a teammate |
| **Lost Limb/Sense** | Disadvantage on checks requiring that body part | The missing part is abnormally sensitive to time—automatically senses nearby crystals/thaw nodes (10 squares) |
| **Stranger You Couldn't Save** | Disadvantage on Negotiation checks when a Frozen One pleads for help | Gain extra Resolve Points when you choose to save someone over taking supplies |
| **Time Poisoning** | Disadvantage on Speed checks for actions needing precise timing | Spend 1 Resolve Point to reroll a Perception check |
| **Betrayal** | Disadvantage when negotiating with strangers | Automatic success when detecting deception or ambush |

**Overcoming Trauma**: When facing a trauma-related situation and making a different choice, the GM may rule that the trauma is overcome—the Disadvantage is removed, the Advantage is doubled, and it transforms into a "Mark."

### Step 5: The One You're Still Searching For

Define a person you believe remains frozen somewhere. This is not a mission—it is a faint beacon that always glows in the background.

| Trigger Condition | Reward |
|---|---|
| Discover a clue related to the target | Gain 1 Insight Point (max 3) |
| Spend 1 Insight Point | Reroll any single attribute check |
| Spend 1 Insight Point | Ask the GM a yes/no question (the GM must answer honestly) |
| Spend 2 Insight Points | Gain an extra action during the Thaw Moment |
| Ultimately find this person | Permanent Insight Point cap +1 |

### Step 6: Starting Equipment

**Common Starting Equipment**:
- Basic Protective Suit ×1 (Armor +1, Time Resistance +1)
- Time Crystal Detector (basic) ×1 (range 30 squares, accuracy 60%)
- Multi-tool Knife ×1
- Backpack (weight capacity 15 units)
- Emergency Rations (3 days' worth)
- Hand-crank Flashlight
- Chalk ×5

**Motivation Bonus Equipment**: Determined by the Motivation chosen in Step 1.

---

## 2.2 Equipment System

> ▶ For the complete equipment, weapon, and tool tables, see **assets/物品圖鑑.md**.

## 2.3 Time Crystal Economy

### Acquisition

| Location Type | Risk | Typical Yield |
|---|---|---|
| Thaw Edge | Moderate | 1–2 Crystals |
| Time Rift Point | High | 2–4 Crystals |
| Time Storm Eye | Extreme | 4–8 Crystals |
| On the Frozen | Variable | 0–3 Crystals |

### Usage

| Use | Cost | Effect |
|---|---|---|
| Personal Time Shield | 1 Crystal | Immune to Thaw effects for 1d4 rounds |
| Extend an object's thaw time | 1–3 Crystals | Each Crystal delays by 1 round |
| Buy time for the Frozen | 2 Crystals | Extends the survival time of a Critically Frozen person from minutes to several hours |
| Stabilize a Time Rift | 3 Crystals | No Thaw occurs within a 5-square radius for 5 rounds |

### Carry Risk

| Amount Carried | Effect |
|---|---|
| 1–2 | Almost no effect |
| 3–5 | GM's Thaw Die +1 |
| 6–10 | Thaw Die +2; each round, Tech Difficulty (DC) 10 or suffer Time Disorientation |
| 11+ | Thaw Die +3, Perception Disadvantage, detectable from 20 squares away |

### Dual Currency System
- **Scrap Coin**: everyday currency; 10 Scrap Coins ≈ one day of basic living expenses
- **Time Crystal**: hard currency; 1 Crystal ≈ 500–1000 Scrap Coins

---

## 2.4 Progression System (Level-less)

### Milestone Triggers

The GM grants progression at the following moments (recommended once every 1–2 sessions; at major story nodes such as key campaign turning points, an extra "Story Milestone" may be granted—allowing two rewards at once, such as +1 Attribute and a new Feat):

| Milestone Type | Trigger Condition | Reward |
|---|---|---|
| Survival | Complete a full looting run and return safely | One Attribute +1 (max 10) |
| Ethics | Make a major ethical choice | Gain experience with a second Thaw Rhythm |
| Trauma | Face a trauma situation and make a different choice | Trauma is overcome |
| Relationship | A major discovery related to "The One You're Still Searching For" | Insight Point cap +1 |
| Tech | Learn a new device or make a major discovery | Gain a new Feat |

### Feat List (Excerpt)

| Feat | Prerequisite | Effect |
|---|---|---|
| Quick-Strip Hands | Tech (TEC) ≥ 7 | Halve the action cost to defuse dangerous objects |
| Silent Step | Speed (SPD) ≥ 7 | −1 to the Thaw Die trigger bonus while moving |
| Time Reader | Perception (PER) ≥ 7 | Upon entering a new Freeze Zone, Perception Difficulty (DC) 12 reveals the rhythm type |
| Iron Guts | Guts (GUT) ≥ 7 | Panic Threshold +3 |
| Time Adaptation | Survived a deep Freeze Zone 2+ times | Crystal carry risk reduced by one tier |

---

## 2.5 Character Sheet Template

```
╔══════════════════════════════════════════════════╗
║        Frozen Wasteland — Time Plunderer Sheet   ║
╠══════════════════════════════════════════════════╣
║Name: ____________   Alias: ____________          ║
║Motivation: ____________   Base: ____________     ║
╠══════════════════════════════════════════════════╣
║Attribute    Value   Mod    Derived Attr    Value ║
║Speed (SPD)      __     __    Movement (MV)     __║
║Perception (PER) __     __    Premonition (FS)  __║
║Guts (GUT)       __     __    Health (HP)       __║
║Tech (TEC)       __     __    Panic Thr. (PT)   __║
╠══════════════════════════════════════════════════╣
║Negotiation (NEG) __    __    Time Resist (TR)  __║
║Zone Experience: __________                       ║
║Trauma: __________   State: □Unmet / □Overcome    ║
║The One You're Still Searching For: __________    ║
║Insight: __/3   Resolve: __/__   Panic: __        ║
╠══════════════════════════════════════════════════╣
║Equipment:                                        ║
║Armor: __________   Armor Val: +___               ║
║Weapon: __________   Dmg: ___   Range: ___        ║
║Detector Model: ______   Range: __   Acc: __%     ║
║Load: __/15    Time Crystals: __                  ║
╚══════════════════════════════════════════════════╝
```

---


# Chapter Three: Combat and Conflict System

## 3.1 Freeze Zone Round Structure

Each full round consists of two layers: the **Frozen Phase** (player actions) and the **Thaw Moment** (crisis reaction):

```
┌──────────────────────────────────────────────────────────┐
│                  A Complete Round                          │
│                                                            │
│  [Frozen Phase]                 [Thaw Moment]             │
│  1. GM secretly rolls Thaw Die →  2. GM describes threat  │
│  2. Players declare actions          3. Guts check        │
│  3. Resolve actions                4. Player reaction     │
│  4. Reveal Thaw Die result          5. Time re-freezes    │
│     ├ No event → next round                               │
│     ├ Omen → Perception check                              │
│     └ Thaw → enter right column                            │
└──────────────────────────────────────────────────────────┘
```

### Declaration Order (Core Design)

**Players declare actions first → the GM reveals the Thaw Die result afterward.** Players always make decisions without knowing whether this round will Thaw.

### Action Types

| Action Type | Per Round | Description |
|---|---|---|
| **Move** | 1 | Movement = Speed + 3 squares |
| **Major Action** | 1 | Complex operation requiring focus |
| **Minor Action** | 1 | Quick operation |
| **Free Action** | Unlimited | Speaking, dropping items |
| **Reaction** | 1 per round | Triggered during another's turn |

### Common Operation Action Costs

| Operation | Cost |
|---|---|
| Loot small item | Minor Action |
| Loot medium item | Major Action |
| Loot valuable/large item | Major + Minor |
| Scan with detector | Minor Action |
| Use first-aid kit (self) | Minor Action |
| Use first-aid kit (other) | Major Action |
| Use Time Crystal | Minor Action |
| Assist ally action | Minor Action (grants Advantage) |
| Guard a direction | Minor Action (+2 Perception in that direction) |

---

## 3.2 Thaw Moment Reaction Rules

### Full Procedure

```
Thaw Trigger
    ↓
【Step A】GM describes the waking threat
    ↓
【Step B】All make a Guts check vs Difficulty (DC)
    ├ Success → act normally
    ├ Failure → Rattled: −2 Movement this round + action Disadvantage
    └ Critical Failure (natural 1 (nat 1)) → Panic episode: full Disadvantage + −2 Movement + Omen Difficulty (DC) +4
    ↓
【Step C】Player declares reaction action (choose one of five)
    ├ A. Run
    ├ B. Take Cover
    ├ C. Counterattack
    ├ D. Keep Looting
    └ E. Rescue the Frozen
    ↓
【Step D】Resolve reaction action + GM judges consequences
    ↓
【Step E】Time re-freezes → damage retained → stress updated
```

### Guts Check Difficulty (DC) System

| Thaw Situation | Guts Difficulty (DC) |
|---|---|
| Minor threat + Omen warning | 10 |
| Moderate threat + Omen warning | 12 |
| Sudden, no warning | 14 |
| Major threat + no warning | 16 |
| Catastrophic (multiple threats at once) | 18 |

**Threat Distance Modifier**:

| Threat Distance | Difficulty (DC) Modifier |
|---|---|
| Far (over 10 squares) | −2 |
| Mid (5–10 squares) | ±0 |
| Near (2–5 squares) | +2 |
| Point-blank (within 1 square) | +4 |

---

### Reaction Option A: Run

- +2 squares Movement this round (adrenaline), but must move in a straight line
- Path obstacle: Speed check Difficulty (DC) 12; failure means you fall (Prone)
- After movement, may dive for cover
- If the threat pursues: opposed Speed check

### Reaction Option B: Take Cover

Move to a cover position; the cover's Defense value is added directly to your Defense (AC):

| Cover Quality | Physical Defense | Example |
|---|---|---|
| Poor | +1 | Overturned table |
| Ordinary | +2 | Edge of a concrete wall |
| Good | +3 | Reinforced concrete pillar |
| Excellent | +5 | Bunker-grade cover |

### Reaction Option C: Counterattack

Initiative determination: opposed Speed (compare d20 + Speed modifier; higher wins).

| Attack Method | Check | Damage |
|---|---|---|
| Melee (improvised weapon) | d20 + Speed modifier vs Defense (AC) | 1d4 + Speed modifier |
| Melee (dedicated weapon) | d20 + Speed modifier vs Defense (AC) | Per weapon |
| Firearm | d20 + Tech modifier vs Defense (AC) | Per firearm |
| Thrown | d20 + Speed modifier vs Difficulty (DC) 10–15 | 1d4 + Speed modifier |
| Time Crystal device | d20 + Tech modifier vs Difficulty (DC) 14 | Re-freeze target for 1d4 rounds |

### Reaction Option D: Keep Looting

- Must first pass a Guts check at Difficulty (DC) 14
- Success → +50% loot yield, but fully exposed this round (threat attacks auto-hit)
- If damaged: additional +1d4

### Reaction Option E: Rescue the Frozen

See §3.5 for detailed rules.

---

## 3.3 Damage System

### Health

**Health (HP) = Guts value × 2 + 10**

| Guts | 2 | 4 | 5 | 7 | 8 |
|---|---|---|---|---|---|
| Health (HP) | 14 | 18 | 20 | 24 | 26 |

> **Design Note: Health (HP) and Combat Risk**—In Frozen Wasteland, Health does not grow with "level." Health (HP) depends solely on the Guts (GUT) attribute; even veterans who have plundered dozens of times differ little from novices. This is a deliberate design choice: in Frozen Wasteland, combat is always high-risk. A character's growth is reflected in their understanding of the Freeze Zone (Zone Experience), abilities learned (Feats), and accumulated resources (Crystals and gear)—not in physical enhancement. Every time you choose to fight rather than flee or sneak, you are gambling with your life.

### Four Types of Damage

| Type | Source | Mitigation |
|---|---|---|
| **Physical** | Explosions, falls, weapons, collapses | Armor Value reduces directly (for area damage such as explosions/collapses, Armor Value is calculated ×2, minimum 1); ordinary attacks reduced to a minimum of 1 |
| **Time Damage** | Thaw spillover, Crystal backlash | **Ignores Armor**; only the Tech (TEC) modifier can reduce it |
| **Frostbite** | Prolonged exposure, cold environments | Mitigated by Warming Gear. 3 points accumulated permanently −1 Speed (SPD) |
| **Mental Damage** | Trauma triggers, witnessing atrocities | Does not reduce Health (HP); increases Stress value |

> **Armor Design Note**: Basic armor (such as a Protective Suit +1) is suitable for blocking small physical damage, but offers limited protection against explosions. Reflective armor (+3) provides an effective reduction of 6 points against explosions—enough to withstand a small blast but not to fully protect against a large collapse. In Frozen Wasteland, the best defense is always "not being within the blast radius."

### Damage Source Reference

| Damage Source | Type | Base Damage |
|---|---|---|
| Grenade explosion (within 3 squares) | Physical | 4d6 |
| Ceiling collapse (small) | Physical | 2d6 |
| Mutant creature claw strike | Physical | 1d6+2 |
| Time Thaw spillover (minor) | Time | 1d4 |
| Time Thaw spillover (severe) | Time | 2d6 |
| Prolonged frostbite (per round, −10°C) | Frostbite | 1d4 |

### Dying and Death

| Health (HP) State | Effect |
|---|---|
| Health (HP) > 50% | Normal |
| Health (HP) ≤ 50% | Light Wound: Disadvantage on all physical actions |
| Health (HP) ≤ 25% | Heavy Wound: Disadvantage on all actions + Movement (MV) −2 |
| Health (HP) = 0 | Dying: Prone, only 1 Minor Action per round. Each round make a Guts (GUT) check vs Difficulty (DC) 12 to remain conscious |
| Health (HP) < 0 | Unconscious. Each round make a Guts (GUT) check vs Difficulty (DC) 15; three failures means death |

### Healing

| Healing Method | Recovery | Condition |
|---|---|---|
| First Aid Kit (self-use) | 1d6+2 Health (HP) | Minor Action |
| First Aid Kit (assisted by another) | 1d6+4 Health (HP) | Major Action, must be adjacent |
| Time Crystal healing | 2d6 Health (HP) | Spend 2 Time Crystals (carries a 1d4 Time Damage risk) |
| Emergency Self-Heal | Restore to Health (HP) = 1 | Only when Health (HP) < 0, one-time use |
| Safe Zone rest (8 hours) | 1d6 + Guts (GUT) modifier Health (HP) | Must be in a non-Freeze Zone |

---

## 3.4 Hazardous Item Rules

### Explosives

| Item | Rule |
|---|---|
| Detection Difficulty (DC) (spot) | Perception (PER) Difficulty (DC) 12 |
| Detection Difficulty (DC) (assess) | Perception (PER) Difficulty (DC) 15 |
| Detonation delay after Thaw | 1 reaction round |

| Response | Check |
|---|---|
| Kick away | Speed (SPD) Difficulty (DC) 12, push it d6 squares away |
| Throw | Speed (SPD) Difficulty (DC) 10, throw to a designated location |
| Dive for cover | No check; cover Defense (AC) ×2 against the explosion |
| Freeze | Tech (TEC) Difficulty (DC) 14, spend 1 Time Crystal to re-freeze for 1d4 rounds |
| Disarm | Tech (TEC) Difficulty (DC) 16 (must be done before Thaw) |

### Frozen Guns

| Item | Rule |
|---|---|
| Detection Difficulty (DC) (spot) | Perception (PER) Difficulty (DC) 13 |
| Detection Difficulty (DC) (trajectory) | Perception (PER) Difficulty (DC) 16—accurately judge the bullet's flight path |
| Behavior after Thaw | Bullet continues flying in its original direction |

### Collapsing Structures

| Collapse Scale | Squares Affected | Damage | Dodge Difficulty (DC) |
|---|---|---|---|
| Small | 1×2 | 1d6 | 10 |
| Medium | 3×3 | 2d6 | 13 |
| Large | 5×5 | 4d6 | 16 |

### Frozen Attacking Creatures

The most dangerous hazardous item: the attack has already been launched to its final stage, and after Thaw it **automatically hits**.

| Response | Check |
|---|---|
| Move out of the attack trajectory | Speed (SPD) Difficulty (DC) 10 |
| Preemptive counter | Speed (SPD) contest |
| Exploit (redirect attack at another threat) | Tech (TEC) Difficulty (DC) 14 |
| Capture | Tech (TEC) Difficulty (DC) 16 |

---

## 3.5 Rescue Actions for the Frozen

### Carrying a Fully Frozen Person

- **Time required**: 2 rounds
- **Personnel required**: Minimum 2 people (a single person takes Double Disadvantage)
- **Check**: Combined Speed (SPD) check (each of the two rolls d20 + Speed modifier; take the lower vs Difficulty (DC) 10)
- **Carrying penalty**: Each of the 2 carriers loses −3 squares of Movement (MV)
- **Thaw interruption**: Guts (GUT) Difficulty (DC) 12; on failure you are forced to drop them and become Rattled

### Stabilizing a Critically Frozen Person

- **Time required**: 3 rounds

| Round | Action | Check | Difficulty (DC) |
|---|---|---|---|
| 1 | Assess degree of freezing and remaining time | Tech (TEC) | 10 |
| 2 | Stop bleeding, immobilize, assist with Crystal | Tech (TEC) | 12 |
| 3 | Final stabilization, prepare for carrying | Tech (TEC) | 12 |

- **Countdown after Thaw**: Dies 1d6 + 2 rounds later (no healing)
- Each Time Crystal spent extends this by 2 rounds

### Ending Loop Freeze

| Stage | Action | Check |
|---|---|---|
| Observe | Watch a full loop (3–5 rounds) | Perception (PER) Difficulty (DC) 14 |
| Intervene | Insert at the loop's critical moment | Guts (GUT) Difficulty (DC) 14 + Tech (TEC) Difficulty (DC) 14 |
| Break the loop | Change one variable within the loop | Tech (TEC) Difficulty (DC) 16 |

- Requires spending 2 Time Crystals
- The intervener automatically takes 1d4 Time Damage

---

## 3.6 Status Effects

| Status | Trigger | Effect | Duration |
|---|---|---|---|
| **Rattled** | Failed Guts (GUT) check | Movement −2 + Disadvantage | Current Thaw Moment |
| **Panic** | Natural 1 (nat 1) or Stress over threshold | All Disadvantage + Movement −2 + Omen Difficulty (DC) +4 | Until retreat or calmed |
| **Partial Freeze** | Time Damage ≥ 5 | Body part loses function (random d6) | Permanent (special treatment can cure) |
| **Time Disorientation** | Time Damage ≥ 4 | Perception (PER) Disadvantage + cannot judge distance | 1d4 rounds |
| **Frostbite (Light)** | Frostbite accumulated 1–2 | Speed (SPD) −1 | Until treated |
| **Frostbite (Moderate)** | Frostbite accumulated 3–4 | Speed (SPD) −2 + Speed check Disadvantage | Until treated |
| **Frostbite (Severe)** | Frostbite accumulated ≥ 5 | Speed (SPD) −3 + equivalent to Partial Freeze | Permanent risk |
| **Prone** | Knocked down | Movement reduced to zero + melee attackers have Advantage against you | Stand up using half your Movement |

---

## 3.7 Tactical Impact of the Five Thaw Rhythms

| Mode | Trait | Best Strategy | Main Trap |
|---|---|---|---|
| **Slumber Type** | Very low frequency, clear Omen | Plunder at full strength, leave a retreat buffer | Complacency |
| **Pulse Type** | Regular 6-round cycle | Count the rhythm, manage resources to the rhythm | Rhythm dependence |
| **Spasm Type** | Completely random, almost no Omen | In fast, out fast (3–4 rounds), travel light | Over-optimism |
| **Chain Type** | One Thaw triggers nearby ones | Isolate / spread out / act first | Entire party caught in the same chain |
| **Breath Type** | Gradual cycle, with transition phase | Three-stage tiered goals | Misjudging the stage position |

---

## 3.8 Retreat Rules

### Retreat Trigger Timing
- Any Frozen Phase round, during the declaration phase
- After a successful Perception (PER) check to identify an Omen
- Choosing "Run" as a Reaction and moving toward the boundary
- May call a retreat when Health (HP) ≤ 25%
- Automatically attempts to retreat when Panic triggers

### Freeze Boundary Crossing Check

**d20 + Tech (TEC) modifier vs Difficulty (DC) 12** (standard)

| Difficulty (DC) Modifier | Modifier |
|---|---|
| Slumber Type zone | −2 |
| Spasm Type zone | +2 |
| Carrying a Frozen person | +2 |
| Using Time Crystal assistance | −3 (spend 1 Time Crystal) |
| Teammate providing support outside the boundary | −2 |
| Wounded (Health (HP) ≤ 50%) | +2 |

**Critical Failure (nat 1)**: Trapped at the boundary for 1 round, taking 1d4 Time Damage.

---

## 3.9 Monster/NPC Stat Template

> ▶ For the monster/NPC stat template and examples, see **assets/怪物圖鑑.md**.

## 3.10 Downtime Activities

Between plundering missions, the time characters spend in a safe zone (Downtime) is not only for recovery, but also an opportunity to advance the story and strengthen characters. Downtime usually lasts 1–7 days.

### 3.10.1 Downtime Actions

Each character may choose **2 Downtime Actions** (for a roughly 1-week downtime) or **1 action** (for a short 1–3 day downtime):

| Action | Cost | Effect | Check (if needed) |
|---|---|---|---|
| **Rest & Recover** | None | Restore full Health (HP) + clear all Cold Fatigue + reset Panic Value to zero | None |
| **Trade & Barter** | Per transaction | Buy gear, sell loot, exchange intel (Silver Tongue feat applies) | Negotiation (NEG) can haggle |
| **Gather Intel** | 10–50 Scrap Coins (buy drinks / bribe) | Gain info on 1 new Freeze Zone (parameters, threats, rumors), or advance a main-story clue | Negotiation (NEG) Difficulty (DC) 12–16 |
| **Training** | None | Choose one attribute; the first check using that attribute in the next session gains Advantage | Guts (GUT) Difficulty (DC) 12 (self-discipline) |
| **Gear Repair/Upgrade** | Material cost (per gear) | Repair damaged gear; can upgrade a detector to the next tier (requires parts) | Tech (TEC) Difficulty (DC) 12–16 |
| **Social Interaction** | None | Build a relationship with a specific NPC, resolve a personal story line, advance "The One You're Still Searching For" clue | Narrative-driven, occasional Negotiation (NEG) check |
| **Time Crystal Research** | Spend 1 Time Crystal | Experiment on a Crystal—may discover a new use, decode time memories stored within, or accidentally trigger a micro-Thaw | Tech (TEC) Difficulty (DC) 14 |
| **Crafting** | Material cost + time | Craft simple items (bandages, flare, basic tools); with suitable materials, may attempt advanced items | Tech (TEC) Difficulty (DC) 10–18 |
| **Help the Community** | None | Provide help in a settlement (free clinic, repairs, teaching)—raise reputation, may gain extra resources or intel | Depends on the action |

### 3.10.2 Downtime Events (Optional)

The GM may roll d6 to trigger a downtime event:

| d6 | Event |
|---|---|
| 1 | **Trouble Comes Knocking**: Creditors, enemies, or the Church's people come looking for the characters—requires Negotiation, evasion, or combat |
| 2 | **Unexpected Windfall**: Chance upon a rare item in the market (GM chooses an item fitting the current story) |
| 3 | **Word Gets Out**: The characters' last mission draws the attention of a faction—which may be good or bad |
| 4 | **Reunion with an Old Acquaintance**: Meet an NPC known from the past—bringing news, a commission, or trouble |
| 5 | **Resource Shortage**: A settlement runs short of some resource (medicine/fuel/food)—prices rise, or a new plundering mission motive appears |
| 6 | **A Quiet Day**: No special event. The characters get a chance to reflect, keep a journal, or have a deep conversation with teammates (RP reward: gain 1 Insight Point) |



## 3.10 Downtime Activities

Between plundering missions, the time characters spend in a safe zone (Downtime) is not only for recovery, but also an opportunity to advance the story and strengthen characters. Downtime usually lasts 1–7 days.

### 3.10.1 Downtime Actions

Each character may choose **2 Downtime Actions** (for a roughly 1-week downtime) or **1 action** (for a short 1–3 day downtime):

| Action | Cost | Effect | Check (if needed) |
|---|---|---|---|
| **Rest & Recover** | None | Restore full Health (HP) + clear all Cold Fatigue + reset Panic Value to zero | None |
| **Trade & Barter** | Per transaction | Buy gear, sell loot, exchange intel (Silver Tongue feat applies) | Negotiation (NEG) can haggle |
| **Gather Intel** | 10–50 Scrap Coins (buy drinks / bribe) | Gain info on 1 new Freeze Zone (parameters, threats, rumors), or advance a main-story clue | Negotiation (NEG) Difficulty (DC) 12–16 |
| **Training** | None | Choose one attribute; the first check using that attribute in the next session gains Advantage | Guts (GUT) Difficulty (DC) 12 (self-discipline) |
| **Gear Repair/Upgrade** | Material cost (per gear) | Repair damaged gear; can upgrade a detector to the next tier (requires parts) | Tech (TEC) Difficulty (DC) 12–16 |
| **Social Interaction** | None | Build a relationship with a specific NPC, resolve a personal story line, advance "The One You're Still Searching For" clue | Narrative-driven, occasional Negotiation (NEG) check |
| **Time Crystal Research** | Spend 1 Time Crystal | Experiment on a Crystal—may discover a new use, decode time memories stored within, or accidentally trigger a micro-Thaw | Tech (TEC) Difficulty (DC) 14 |
| **Crafting** | Material cost + time | Craft simple items (bandages, flare, basic tools); with suitable materials, may attempt advanced items | Tech (TEC) Difficulty (DC) 10–18 |
| **Help the Community** | None | Provide help in a settlement (free clinic, repairs, teaching)—raise reputation, may gain extra resources or intel | Depends on the action |

### 3.10.2 Downtime Events (Optional)

The GM may roll d6 to trigger a downtime event:

| d6 | Event |
|---|---|
| 1 | **Trouble Comes Knocking**: Creditors, enemies, or the Church's people come looking for the characters—requires Negotiation, evasion, or combat |
| 2 | **Unexpected Windfall**: Chance upon a rare item in the market (GM chooses an item fitting the current story) |
| 3 | **Word Gets Out**: The characters' last mission draws the attention of a faction—which may be good or bad |
| 4 | **Reunion with an Old Acquaintance**: Meet an NPC known from the past—bringing news, a commission, or trouble |
| 5 | **Resource Shortage**: A settlement runs short of some resource (medicine/fuel/food)—prices rise, or a new plundering mission motive appears |
| 6 | **A Quiet Day**: No special event. The characters get a chance to reflect, keep a journal, or have a deep conversation with teammates (RP reward: gain 1 Insight Point) |



---

# Appendix A: Player Quick Reference

| What I Want to Do | Roll | Opposed By |
|---|---|---|
| Do something risky | d20 + Attribute Modifier | Difficulty (DC) (declared by GM) |
| Do anything while in Panic | 2d20 take lower + Attribute Modifier | Difficulty (DC) |
| After using a Time Shield | 2d20 take higher + Attribute Modifier | Difficulty (DC) |
| Notice a Thaw Omen | d20 + Perception (PER) modifier | Omen Difficulty (DC) |
| Stay calm during a Thaw | d20 + Guts (GUT) modifier | Difficulty (DC) 10 (with warning) / 14 (without) |
| Judge the Freeze Zone type | d20 + Tech (TEC) modifier | Difficulty (DC) 8–18 |
| Soothe a panicking teammate | d20 + Negotiation (NEG) modifier | Difficulty (DC) 12 |

---
