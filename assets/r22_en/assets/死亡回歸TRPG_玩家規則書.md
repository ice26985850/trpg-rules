# Death Return TRPG — Player Rulebook

> *"Every time you die you return to the Save Point. You remember everything—who betrayed you, which door hides a trap. But every time you restart, your gear, money, and relationships all reset to zero."*

---

## Table of Contents

- [Chapter One: Core Rules](#chapter-one-core-rules)
  - [1.1 Dice System](#11-dice-system)
  - [1.2 The Five Attributes](#12-the-five-attributes)
  - [1.3 Skill System](#13-skill-system)
  - [1.4 Check Rules](#14-check-rules)
  - [1.5 Difficulty Tiers](#15-difficulty-tiers)
- [Chapter Two: Character Creation](#chapter-two-character-creation)
  - [2.1 Six Steps of Character Creation](#21-six-steps-of-character-creation)
  - [2.2 Background System](#22-background-system)
  - [2.3 Derived Attribute Calculation](#23-derived-attribute-calculation)
  - [2.4 Character Growth](#24-character-growth)
- [Chapter Three: Death Return Core Mechanics](#chapter-three-death-return-core-mechanics)
  - [3.1 Save Points](#31-save-points)
  - [3.2 Memory Fragment System](#32-memory-fragment-system)
  - [3.3 Rift Mark System](#33-rift-mark-system)
  - [3.4 Intel Layer and Execution Layer](#34-intel-layer-and-execution-layer)
- [Chapter Four: Combat Basics](#chapter-four-combat-basics)
  - [4.1 Time Unit System](#41-time-unit-system)
  - [4.2 Action Types](#42-action-types)
  - [4.3 Attack & Defense](#43-attack--defense)
  - [4.4 Wounds & Damage](#44-wounds--damage)
  - [4.5 Memory-Bonus Combat](#45-memory-bonus-combat)
- [Chapter Five: World Intro](#chapter-five-world-intro)
  - [5.1 Resonance Continent](#51-resonance-continent)
  - [5.2 Ashfall City](#52-ashfall-city)
- [Appendix](#appendix)
  - [Quick Reference Card](#quick-reference-card)
  - [Glossary](#glossary)
  - [Character Creation Worksheet](#character-creation-worksheet)

---

# Chapter One: Core Rules

## 1.1 Dice System

Death Return TRPG uses the **twenty-sided die (d20)** as its core die. The base formula for all checks is:

> **Check Value = d20 + Attribute Modifier (MOD) + Skill Level**
>
> **Success Condition: Check Value ≥ Difficulty Class (DC)**
>
> **Attribute Modifier (MOD)** = floor(Attribute Value ÷ 2), reference: Attr4→+2, Attr5→+2, Attr6→+3, Attr7→+3, Attr8→+4, Attr9→+4, Attr10→+5, Attr12→+6, Attr15→+7.

### Advantage and Disadvantage

| State | Abbrev. | Rule | Effect Note |
|------|------|------|---------|
| **Advantage (ADV)** | ADV | Roll 2d20, take higher | When situation favors you (e.g., you know the terrain via intel gathering) |
| **Normal** | — | Roll 1d20 | Standard situation |
| **Disadvantage (DIS)** | DIS | Roll 2d20, take lower | When situation disfavors you (e.g., accumulated Rift Mark affects judgment) |

**Stacking Rule:** Advantage and Disadvantage cancel out. No matter how many sources of each, if at least one of each exists, they fully cancel into a normal roll.

### Special Results

| Roll Result | Term | Effect |
|----------|------|------|
| Natural 20 | **Critical Success (Crit)** | Auto success + extra favorable effect |
| Natural 1 | **Critical Failure (Disaster)** | Auto failure + may trigger unfavorable consequence |
| Check Value ≥ DC+5 | **Exceptional Success** | Better result than expected |
| Check Value ≤ DC−5 | **Severe Failure** | Worse consequence than mere failure |

> **Degree-of-Success Effect Cap**: The extra effects of Critical Success / Critical Failure are bound by the "Degree-of-Success Effect Cap table" (see 4.3.1); the GM may not freely adjudicate beyond it.

---

## 1.2 The Five Attributes

Your character has five core attributes, each representing a basic capability. Attribute values range from **4 to 9**; each starts at base 4 (free), with **18 points** to buy (increasing cost, see 2.1 Step Two).

### Attribute Overview

| Attribute | Abbrev. | Meaning | Typical Use |
|------|------|------|----------|
| **Insight (INS)** | INS | Observe details, notice anomalies, read people | Scout scenes, spot lies, detect hidden clues |
| **Memory (MEM)** | MEM | Ability to retain prior-loop info | Carry Memory Fragments, recall past details |
| **Execution (EXE)** | EXE | Actual operational ability | Combat, stealth, lockpicking, athletics |
| **Social (SOC)** | SOC | Persuasion, charm, build relationships | Persuade NPC, rebuild relationships, gain trust |
| **Will (WIL)** | WIL | Bear the psychological burden of death | Resist fear, bear Rift Mark, mental resistance |

### Attribute Pointing Suggestions

| Style | Suggested Distribution | Suited Player |
|------|----------|-----------|
| **Intel Priority** | INS8, MEM8, EXE4, SOC5, WIL5 | Likes gathering info, planning routes |
| **Action Type** | INS5, MEM5, EXE8, SOC7, WIL5 | Likes taking initiative, trying various methods |
| **Social Engineering** | INS6, MEM5, EXE4, SOC9, WIL6 | Likes interacting with NPCs, using relationships as weapon |
| **Resilient Survivor** | INS5, MEM6, EXE5, SOC4, WIL9 | Endurance player, unafraid of death |
| **Balanced** | All 6 | Unsure of style, try each method first |

---

## 1.3 Skill System

Skills represent professionally trained domains. Skill Level ranges 0 (untrained) to 5 (Legendary), starting with **8 skill points** to distribute, creation cap 3 per skill.

### Intel Layer Skills

| Skill | Abbrev. | Attribute | Use |
|------|------|----------|------|
| **Reconnaissance (REC)** | REC | Insight (INS) | Actively observe environment, search clues, find hidden things |
| **Conversation Mining (DIA)** | DIA | Social (SOC) | Extract intel from dialogue, steer topics |
| **Anomaly Sense (ANO)** | ANO | Insight (INS) | Passively notice something off, intuitive warning |
| **Cause-of-Death Analysis (DEA)** | DEA | Will (WIL) | Analyze cause of death, infer danger source |

### Execution Layer Skills

| Skill | Abbrev. | Attribute | Use |
|------|------|----------|------|
| **Combat (COM)** | COM | Execution (EXE) | Melee, ranged, dodge, block |
| **Stealth (STE)** | STE | Execution (EXE) | Conceal movement, hide, tail |
| **Mechanics (MEC)** | MEC | Execution (EXE) | Lockpick, operate machinery, set traps |
| **Persuasion (PER)** | PER | Social (SOC) | Persuade NPC, build relationships, gain trust |

### General Skills

| Skill | Abbrev. | Attribute | Use |
|------|------|----------|------|
| **Memory Recall (RECALL)** | RECALL | Memory (MEM) | Precisely recall prior-loop details, resist memory blur |
| **Mental Resistance (RES)** | RES | Will (WIL) | Resist fear, mental manipulation, psychological trauma |

### Crafting Skill

| Skill | Abbrev. | Attribute | Use |
|------|------|----------|------|
| **Alchemy (ALC)** | ALC | Execution (EXE) | Craft potions, fire bombs, simple antidotes, scroll materials (see *Item Codex* and GM 14-9) |

### Skill Level Description

| Level | Description |
|------|------|
| 0 | Untrained—may still attempt, but relies on attribute alone |
| 1 | Beginner—received basic training |
| 2 | Proficient—can perform steadily |
| 3 | Expert—stands out in the field |
| 4 | Master—top tier (gained through in-game growth) |
| 5 | Legendary—human limit (gained through in-game growth) |

---

## 1.4 Check Rules

### Standard Check

When you attempt an action with risk of failure, the Game Master (GM) declares a check:

```
Check Value = d20 + Attribute Modifier (MOD) + Skill Level
Success ⇔ Check Value ≥ Difficulty Class (DC)
```

**Example:** You want to sneak into an abandoned building; GM sets DC 16. Your Execution (EXE) = 6 (Attribute Modifier +3), Stealth (STE) skill level = 2. Roll d20 = 11, Check Value = 11 + 3 + 2 = 16 ≥ 16 → **Success**.

### Contested Check

When you directly oppose a Non-Player Character (NPC), both sides roll, higher value wins:

```
Player Value = d20 + Player Attribute Modifier (MOD) + Player Skill
NPC Value = d20 + NPC Attribute Modifier (MOD) + NPC Skill
Player Success ⇔ Player Value > NPC Value
```

### NPC Assistance

When receiving NPC assistance:
- If NPC relevant Skill ≥ 2: you gain **Advantage (ADV)**
- If NPC Skill ≥ 4: you additionally gain **+2 bonus**

---

## 1.5 Difficulty Tiers

| Difficulty | Abbrev. | DC | Note |
|------|------|-----|------|
| **Trivial** | TRI | 8 | Daily action, almost shouldn't fail |
| **Easy** | EAS | 12 | Needs basic ability, proficient pass steadily |
| **Medium** | MED | 16 | **Core game difficulty**, ~50–60% success rate without prep |
| **Hard** | HRD | 20 | Needs prep or intel support |
| **Extreme** | EXT | 24 | Even experts need intel support |
| **Nearly Impossible** | NIM | 28 | Needs perfect prep and very high attributes |

GM may adjust DC by ±2 per situation. Favorable factors (detailed map, proper tools) lower DC; unfavorable factors (insufficient info, tight time) raise DC.

### 1.5.1 Dynamic Shift

The base DC table does not change with character growth; increased challenge comes from enemy attributes and environment, not rising DC. But to prevent S4–S5 core checks from becoming too easy due to character growth, an "overall shift" is used:

- **S1–S3**: Apply the table directly, no shift.
- **S4**: Core checks (those directly tied to main-story progression and survival, marked by GM) DC **+2**; non-core checks no shift.
- **S5**: Core checks DC **+4**; or adopt "expand DC ceiling" plan—open DC **32 (Legendary) / 36 (Miraculous)** tiers for S5-exclusive top-tier threats, GM-only.

Calculation order: base DC → mark if core check → add shift by tier → then add environment/contest modifiers. Shift does not stack onto a contested opponent's adjustment value.

---

# Chapter Two: Character Creation

## 2.1 Six Steps of Character Creation

### Step One: Your First Death

Choose your cause of death and the source of your Return ability.

#### Cause of Death Options

| Cause of Death | Attribute Bonus | Gained Ability | Ability Note |
|------|----------|----------|----------|
| **Killed (Murder)** | Execution +1 | **Danger Scent** | Once per loop, when about to enter a scene that previously caused your death, GM gives a vague premonition |
| **Killed (Combat)** | Execution +1 | **Combat Memory** | Against an enemy that previously killed you, first attack gains Advantage |
| **Accident (Mishap)** | Insight +1 | **Anomaly Sense** | On entering a scene, automatically notice the most obvious "something off" |
| **Accident (Disaster)** | Insight +1 | **Omen Sense** | In scenes with an impending fixed event, GM may give early vague warning |
| **Suicide (Despair)** | Will +2 | **Last-Stand Will** | When Rift Mark exceeds 20, Will checks after each death gain Advantage |
| **Suicide (Sacrifice)** | Will +2 | **Light of Conviction** | When trying to save or protect others, any check gains +1 bonus |

#### Return Source

| Source | Initial Bonus | Narrative Impact |
|------|----------|----------|
| **Curse** | Memory Fragment Capacity +2 | Your Return comes from some existence—what does It want? |
| **Experiment** | Can carry two Skill Fragments (second use adds +1 Rift Mark) | Your body was modified |
| **Innate Gift** | Initial Rift Mark −1 (min 0) | You were born this way, no cost—but no explanation either |
| **Unknown** | Start with one free Fate Fragment | You don't know why; the most common yet most terrifying case |

---

### Step Two: Attribute Distribution

Each attribute base is **4 (free)**, single-attribute cap **9**. You have **18 points** to buy, with increasing cost:

| Increase | 4→5 | 5→6 | 6→7 | 7→8 | 8→9 |
|------|-----|-----|-----|-----|-----|
| Cost | 1 pt | 1 pt | 2 pts | 2 pts | 3 pts |

Cause-of-death and background bonuses add an extra **+1** to the final value (not counted in buy). Memory (MEM) and Will (WIL) share the 4–9 range.

| Attribute | Abbrev. | Base (free) | Buy Points | CoD Bonus | Background Bonus | Final |
|------|------|------------|----------|----------|----------|--------|
| Insight | INS | 4 | ___ | +___ | +___ | **___** |
| Memory | MEM | 4 | ___ | +___ | +___ | **___** |
| Execution | EXE | 4 | ___ | +___ | +___ | **___** |
| Social | SOC | 4 | ___ | +___ | +___ | **___** |
| Will | WIL | 4 | ___ | +___ | +___ | **___** |
| **Total Buy** | | | **18** | | | |

---

### Step Three: Your Save Point

Choose the type of your first Save Point:

| Type | Note | Example |
|------|------|------|
| **Location Type** | A concrete physical location | Your apartment bedroom, safe house, church pew |
| **Moment Type** | A recurring point in time | 7:00 AM alarm every day, every Monday dawn |
| **Event Type** | Bound to a specific event | After completing a commission, after talking with key NPC |

---

### Step Four: The One You Don't Want to Redo

Choose your Psychological Trauma:

| Type | Description | Game Effect |
|------|------|----------|
| **Witnessed a Companion's Death** | Watched someone you care about die | When companion NPC faces danger, all actions that loop gain Advantage, but each death adds +1 Rift Mark |
| **Caused a Tragedy** | Wrong choice led to irreversible consequence | When facing similar moral choice, GM may demand Will check |
| **Betrayed by a Trusted One** | The one you trusted most killed you | Rebuilding "trust" relationship needs one extra successful check, but after built gains +2 bonus |
| **Unbearable Pain** | Some death too painful | When suffering same death type, extra +2 Rift Mark |
| **Limit of Loneliness** | Experienced absolute loneliness | At loop start may choose one NPC to auto-gain "Acquainted" relationship |

---

### Step Five: A Name You'll Always Remember

Choose your Core Relationship:

| Type | Description | Game Effect |
|------|------|----------|
| **Bond** | You love this person | Each loop start auto-gain this person's Character Fragment (doesn't count toward cap) |
| **Debt** | Unfinished business between you | Each successful interaction reduces Rift Mark by 1 (once per loop) |
| **Mystery** | This person holds a secret you want to unravel | Each time you gain new intel from this NPC, +1 temporary fragment cap |
| **Mirror** | This person reminds you of your past self | When making similar choices may reroll one Will check |

---

### Step Six: Your Rift Mark

Roll **1d6** to determine initial Rift Mark value. Innate Gift source −1 (min 0).

| Rift Mark | State |
|--------|------|
| 1 | Just started Returning, death still fresh to you |
| 2–3 | Experienced a few loops, beginning to adapt but feel the weight |
| 4–5 | Rift Mark begins to show, speech sometimes seems odd to NPCs |
| 6 | Standing at the edge, but thereby become extremely sharp |

---

## 2.2 Background System

Death Return TRPG does not use traditional classes. Your "background" represents your identity before your first death.

### Eight Backgrounds

| Background | Attribute Bonus | Core Ability | Suited Player |
|------|----------|----------|----------|
| **Scholar** | Memory +1 | Erudite Memory (Advantage on Memory checks recalling book knowledge), Research Acuity (+2 Insight in research places) | Research/analysis type |
| **Soldier** | Execution +1 | Tactical Training (forfeit one turn → next turn Attack Advantage), Body Memory (+1 to physically performed actions) | Combat/action type |
| **Thief** | Execution +1 | Shadow Step (Stealth Advantage on traveled routes), Dexterous Hands (+2 fine operations like lockpicking) | Stealth/solve type |
| **Doctor** | Insight +1 | Medical Knowledge (+2 healing, can judge cause of death), Cause Analysis (auto gain extra info when witnessing death) | Support/investigation type |
| **Wanderer** | Will +1 | Survival Instinct (+1 Insight/Execution in wild), Adaptability (choose one environmental adaptation per loop) | Exploration/survival type |
| **Merchant** | Social +1 | Negotiation Expert (+2 trade negotiation), Connection Memory (Advantage on Memory recalling who can help) | Negotiation/resource type |
| **Performer** | Social +1 | Performance Charm (Social Advantage when drawing attention), Mind Reading (once per loop read NPC's strongest emotion) | Roleplay/interaction type |
| **Detective** | Insight +1 | Reasoning (three info → GM reveals logical link), Detail Observation (+2 Insight searching scenes) | Puzzle/intel type |

---

## 2.3 Derived Attribute Calculation

Calculate your core numbers from the five attributes:

| Derived Attribute | Formula | Use |
|----------|------|------|
| **Hit Points (HP)** | Execution (EXE) + Will (WIL) + 5 | Total damage capacity; wound level derived from remaining proportion (see 4.4) |
| **Mind Points (MP)** | Will (WIL) + Memory (MEM) + 3 | Consumption of social/mental checks, and fear/madness resistance |
| **Stamina Points (SP)** | Execution (EXE) + Will (WIL) + 3 | Stamina resource: attack, sprint, reaction etc. cost Stamina (see 4.2); zero = Exhaustion |
| **Memory Fragment Capacity** | Memory (MEM) × 2 + 5 + source bonus | Total fragment capacity carried per loop |
| **Rift Threshold** | **fixed 10** (= Unbalanced start, narrative cue only; stages by absolute Rift Mark value, not shifted by Will) | At Rift Mark 10 enters Unbalanced (pure narrative cue, no mechanical penalty) |
| **Damage Tolerance (TOL)** | Armor Value (AV) + floor((Execution (EXE) + Will (WIL)) ÷ 4), soft cap 9 | Damage reduction: final damage = max(0, raw damage − Damage Tolerance) |
| **Relationship-Rebuild Base** | Social (SOC) ÷ 2 (floor) | Base efficiency of NPC relationship rebuilding |

---

## 2.4 Character Growth

Death Return TRPG **does not use a traditional level system**. Growth comes from milestones:

| Growth Event | Gain | Frequency |
|----------|------|------|
| **Complete a scenario** | +2 attribute points + 1 skill point + Memory Fragment Capacity +1; counts as **1 Milestone** | Once per scenario |
| **Unlock new Save Point** | +1 attribute point + Rift Mark −1d3; counts as **1 Milestone** | Once per Save Point |
| **Discover key intel** | Every cumulative **3 times** = +1 attribute point; counts as **1 Milestone** (cumulative, not dependent on single-loop GM subjectivity) | Record at most once per loop |
| **Complete character personal goal** | +1 attribute point; counts as **1 Milestone** | Once per goal |
| **Every 3 Milestones** | +1 skill point | Cumulative |
| **First recovery below 10 after Rift Mark 20+** | Will +1 | Once only |
| **Complete 10+ loops** | Memory Fragment Capacity +2 | Once |

> **Milestone design goal**: Make the sources of "skill points" and "attribute points" explicit and predictable. Completing scenarios and unlocking Save Points are deterministic attribute/skill sources; key intel and personal goals become "cumulative Milestones," redeemed uniformly by "1 skill point per 3 Milestones," avoiding variance from different GMs' amounts.

**Attribute growth cap:** Insight/Memory/Execution/Social cap 12, Will cap 15. **Skill Level cap: 5** (creation cap 3, rest via skill points; skill points from scenario completion and milestones).

---

# Chapter Three: Death Return Core Mechanics

## 3.1 Save Points

A Save Point is the destination you return to after death. You may have multiple Save Points, but only the latest is active.

### Save Point Types

| Type | Establish Condition | Note |
|------|----------|------|
| **Location Save (Loc-Save)** | Rest ≥ 1 hour at safe place | Bound to specific location |
| **Time Save (Time-Save)** | Before key event, GM declares save possible | Bound to specific time point |
| **Event Save (Evt-Save)** | Auto-saved after completing major story event | Bound after event completion |

### Save Point Rules

1. **Single Active**: Only one active Save Point at a time; new save overwrites old
2. **Death Return**: After death return to latest Save Point, keep memory but lose all physical resources
3. **Memory Fragment Choice**: After Return, choose fragments to carry from last loop's memory (within Capacity)
4. **Rift Mark Retained**: Rift Mark value does not reset on Return
5. **Equipment Binding (Save Binding)**: After spending 1 hour on a "binding ritual" at a Save Point, you may mark up to **2** pieces of equipment as "Save Bound." After Death Return, these bound items **are not lost with physical resources** (money still resets to starting value). Re-binding required each time the active Save Point changes. This mechanic solves the problem where "economic death reset" makes equipment lists lose long-term meaning.

---

## 3.2 Memory Fragment System

Memory Fragments (MF) are info you can "carry" to the next loop after death. Choose which fragments to carry at each loop start.

### Five Fragment Types

| Fragment Type | Abbrev. | Cost | Effect | Duration |
|----------|------|------|------|----------|
| **Event Fragment** | EF | 1 | Precisely remember an event's time, place, and participants | Single use |
| **Character Fragment** | CF | 1 | Advantage on all social checks vs that NPC (carry cap **3** per loop, prevents social builds from dominating) | Whole loop |
| **Location Fragment** | LF | 2 | Advantage on stealth and recon checks vs that location | Whole loop |
| **Skill Fragment** | SF | 2 | Retain one "temporarily learned this loop" skill to next loop (1 per loop) | Whole loop |
| **Fate Fragment** | FF | 5 | Force survival once (1 per loop) | Consumed on trigger |

> **Skill Permanently Retained Principle**: Skills learned at creation and gained through growth are **permanently retained, not reset by death**. Skill Fragments (SF) only retain "temporarily learned this loop" skills—e.g., learned from an NPC mentor, from a training scene or scroll, and would be lost on death. If no temporary skill this loop, SF can be kept for a needed loop.

### Fragment Acquisition

| Method | Gain |
|------|------|
| Witness key event | Event Fragment ×1 |
| Deeply understand NPC (successfully reveal important info) | Character Fragment ×1 |
| Fully explore a region (≥80%) | Location Fragment ×1 |
| Some skill raised to level 3+ this loop | Skill Fragment ×1 |
| Experience death (know cause) | Fate Fragment ×1 |

### Fragment Carry Strategy Example (Memory 5, Capacity 15)

| Style | Config | Total Cost |
|------|------|--------|
| **Info Gatherer** | EF×3(3)+CF×3(3)+LF×1(2)+SF×1(2) | 10 |
| **Strategy Type** | EF×1(1)+CF×1(1)+LF×3(6)+SF×1(2) | 10 |
| **Relationship Type** | EF×2(2)+CF×3(3)+LF×1(2)+SF×1(2) | 9 |
| **Insurance Type** | EF×1(1)+CF×2(2)+LF×1(2)+SF×1(2)+FF×1(5) | 12 |

---

## 3.3 Rift Mark System

The Rift Mark (RM) is the **only resource that accumulates across loops and never resets**, representing psychological trauma from repeated death.

### Rift Mark Increase

| Manner of Death | Rift Mark Increase | Note |
|----------|----------|------|
| **Quick Death** | +1 | Over in an instant |
| **Voluntary Death** | +2 | You chose death—but each leaves a mark in your heart |
| **Painful Death** | +3 | Burning, suffocation, slow bleed—you had time to feel every moment |
| **Betrayal Death** | +5 | Killed by someone you trusted |
| **Despair Death** | +7 | Watched a companion die—then it's your turn |
| **Time Exhausted** | +1 | Loop time limit reached, natural Return |

### Rift Mark Stages

| Rift Mark | State | Effect |
|--------|------|------|
| **0–9** | **Calm** | No effect. Mind works normally |
| **10–19** | **Unbalanced** | All Social (SOC) checks get **Disadvantage**. You begin to keep distance from people subconsciously |
| **20–29** | **Shattered** | Insight (INS) checks **Advantage** (sensitive to anomalies), Will (WIL) checks **Disadvantage** (fragile psyche) |
| **30–39** | **Critical** | After each death must pass DC 15 Will (WIL) check, failure forces skip next Save Point |
| **40+** | **Uncontrolled** | GM may intervene in character narrative. Character may act unpredictably |

### Rift Mark Relief

| Method | Relief | Condition |
|------|--------|------|
| Unlock new Save Point | −1d3 | Auto trigger |
| Complete scenario main goal | −2 | Once per scenario |
| Form emotional bond with NPC (Bond relationship) | −2 | Need to complete dedicated story line |
| Help core NPC achieve important goal | −3 | Once per scenario |
| Reveal core worldview truth | −4 | GM judgment |
| Prevent fixed event | −5 | Extremely rare |

> Rift Mark can only be relieved, never zeroed—the memory of death is always part of you.

---

## 3.4 Intel Layer and Execution Layer

The core gameplay loop of Death Return TRPG is: **Intel Gathering → Route Planning → Execute Action → Death or Success**.

**Core Rule: Successful Intel Layer can grant Advantage to related Execution Layer checks.**

### Intel Layer Actions

| Action | Check | Execution Layer Bonus After Success |
|------|------|-------------------|
| **Reconnaissance (REC)** | Insight+Reconnaissance vs DC | Stealth and Combat checks in that area gain Advantage |
| **Conversation Mining (DIA)** | Social+Conversation Mining vs DC | Persuasion checks vs same NPC gain Advantage |
| **Anomaly Sense (ANO)** | Insight+Anomaly Sense vs DC | Combat or Stealth checks vs that threat gain Advantage |
| **Cause-of-Death Analysis (DEA)** | Will+Cause-of-Death Analysis vs DC | All checks vs same threat next loop gain Advantage |

> **Mind Point Cost (Intel Layer)**: Each Intel Layer check (Reconnaissance/Conversation Mining/Anomaly Sense/Cause-of-Death Analysis) costs **1 Mind Point (MP)**. If Mind Points < 3, substitute with Will (WIL) check instead, no extra MP cost. This makes intel gathering not zero-cost, constraining "infinite recon."

### Execution Layer Actions

| Action | Check | Intel Gain Condition |
|------|------|-------------|
| **Combat (COM)** | Execution+Combat vs DC | Already learned enemy via Reconnaissance or Cause-of-Death Analysis |
| **Stealth (STE)** | Execution+Stealth vs DC | Already carrying Location Fragment or successfully reconned area |
| **Mechanics (MEC)** | Execution+Mechanics vs DC | Already successfully reconned the device |
| **Persuasion (PER)** | Social+Persuasion vs DC | Already carrying Character Fragment or successful Conversation Mining |

---

# Chapter Four: Combat Basics

## 4.1 Time Unit System

This game uses **Time Unit (TU)** to measure combat actions. Each combat round (round), you have **6 Time Units (6 TU)**.

### Round Flow

```
Highest Initiative → declare action → spend TU → resolve effect →
Next highest Initiative → declare action → spend TU → resolve effect →
Loop until all characters' TU exhausted or forfeited →
Round ends → recover all TU → new round begins
```

You may choose to **Hold (Wait)**: with TU remaining, pause and insert your action after any other character's action ends. TU held to round end unused is wasted.

### Initiative Judgment

```
Initiative Value = Insight (INS) + 1d10
```

- If you have **intel advantage** vs current enemy (encountered in prior loops): Initiative **+2**
- If you prepared an **ambush**: Initiative check gains **Advantage**
- If you are **surprised**: Initiative check gains **Disadvantage**

---

## 4.2 Action Types

### Action Cost Table

| Action Type | Time Unit (TU) | Stamina Cost | Note |
|----------|---------------|----------|------|
| **Major Action** | 3 TU | 2 SP | Attack, use combat skill, first aid, complex interaction |
| **Minor Action** | 1 TU | 0 SP | Draw weapon, reload, quick item use, observe |
| **Move** | 1 TU/zone | 0 SP | Move between combat zones (each zone ~5 meters) |
| **Sprint** | 2 TU | 1 SP | Move 3 zones (needs Execution check DC 10) |
| **Rest** | 3 TU | +Execution SP | Recover Stamina, cannot combine with Major Action |
| **Reaction** | 0 TU | 1 SP | Once per round: Dodge, Block, Opportunity Attack |

### Reaction Actions

| Reaction | Trigger | Effect |
|------|----------|------|
| **Dodge** | When attacked | d20+Execution vs attack check, success fully avoids |
| **Block** | When melee attacked | d20+Execution vs attack check, success halves damage |
| **Opportunity Attack** | Enemy leaves melee range | Free melee attack once |

---

## 4.2.1 Stamina Round Recovery

In long fights Stamina is a key resource. To avoid forced Exhaustion in drawn-out fights making Stamina meaningless, **Stamina Points auto-recover 2 points at each round start** (not exceeding Stamina cap). The "Rest" action (4.2) can still additionally recover Stamina; the two stack.

---

## 4.3 Attack & Defense

### Attack Check

```
Attack Value = d20 + Execution (EXE) + Combat Skill (COM) + Memory Bonus
Defense Value = 10 + floor(Execution (EXE) ÷ 2) + Armor Value (AV) + Cover Modifier
```

- Attack Value ≥ Defense Value: **Hit**
- Attack Value ≥ Defense Value + 5: **Precise Hit (Crit)**—final damage extra +1 level

> **Weapon Base Damage**: from *Item Codex* weapon table's "Damage" column (includes weapon's innate bonus, e.g., Short Sword 1d6+1).
> **Cover Modifier**: while in cover, Defense Value +2.

### Damage Resolution

After hit, calculate and deduct Hit Points (HP):

```
Raw Damage = Weapon Base Damage (from *Item Codex*, includes innate bonus) + floor(Execution (EXE) ÷ 2) + weakness bonus
Final Damage = max(0, Raw Damage − target Damage Tolerance (TOL))
Target Hit Points (HP) −= Final Damage
```

- If Final Damage is 0: attack fully defended, only blunt pain (no wound change)
- After deducting HP, map remaining proportion to **Wound Level** (see 4.4)
- Both sides use the **same** HP and wound rules, only values differ

### 4.3.1 Degree-of-Success Effect Cap Table

Extra effects of Natural 20 (Critical Success) and Natural 1 (Critical Failure) are bound by the table below; GM may not freely adjudicate beyond it:

| Result | Allowed Extra Effect (choose one) | Forbidden |
|------|----------------------|----------|
| **Critical Success (Natural 20)** | ① Damage/healing +1 level (or extra +1d6); ② 1 minor benefit (e.g., enemy loses 1 TU, gain 1 intel fragment) | No multiple strong effects at once; no instant kill; no skipping story gates |
| **Critical Failure (Natural 1)** | ① Action fails; ② 1 minor cost (e.g., +1 Rift Mark, lose 1 TU, trigger 1 status) | No direct death; no permanent loss of key item; no unconditional party wipe |

**Low-Difficulty Exemption**: When check DC ≤ 12 (Trivial/Easy), Natural 1 is only a normal failure, no Critical Failure cost; Natural 20 may still give 1 minor benefit per the table above.

---

## 4.4 Wounds & Damage

All characters (player and enemy) have numeric **Hit Points (HP)**. On taking damage first deduct HP, then map remaining proportion to **Wound Level** as narrative description. This keeps combat resolution always with clear numbers, while preserving the "ordinary people get hurt" feel.

### 4.4.1 Wound Levels (from Hit Points)

| Remaining HP % | Wound Level | Name | Game Effect |
|---------------|---------|------|----------|
| 100% | 0 | **No Wound** | Normal action |
| 76–99% | 1 | **Light Wound** | Record wounded location; no check Disadvantage |
| 51–75% | 2 | **Moderate Wound** | **Disadvantage** on actions for that wounded location; Sharp damage adds Bleeding |
| 26–50% | 3 | **Severe Wound** | All Execution checks **Disadvantage**; halved movement; each round start Will (WIL) DC 12, failure **sustains and accumulates fatigue (next round DC +2, max +4)**, success clears fatigue; First Aid or Healing Potion can drop back to Moderate |
| 1–25% | 4 | **Fatal Wound** | Cannot take Major Actions; each round start Will (WIL) DC 15, failure enters **Unconscious-savable** (need First Aid or Healing Potion to pull back, else next round failure again = death; two consecutive failures = death) |
| 0% | 5 | **Death/Down** | Player triggers Return; enemy removed from combat |

> HP reaching zero is death, no extra accumulation rule needed. The per-round Will checks at Severe and Fatal represent the struggle to "hold on": success sustains status, failure accumulates fatigue at Severe or enters Unconscious-savable at Fatal (needs First Aid/potion to pull back, death only after two consecutive failures), weakening the original "half-HP instant death" spiral.

### 4.4.2 Damage Types and Status Effects

| Damage Type | Trait | Status Triggered |
|----------|------|----------------|
| **Blunt** | Can stun, knock back | Precise Hit → target Execution DC 12, failure Stun 1 TU |
| **Sharp** | Causes bleeding | Moderate Wound+ adds Bleeding (−1 HP per round) |
| **Piercing** | Pierces armor | When calculating TOL, Armor Value halved |
| **Fire** | Continues burning | Moderate Wound+ adds Burning (−1 final damage per round) |
| **Ice/Electric** | Temporary slowdown | After hit target move cost +1 TU (lasts 2 TU) |
| **Poison** | Progressive worsening | Adds Poisoned (wound level upgrades one step every 10 min until cured) |
| **Fear (Mental)** | Forces action | Adds Fear (Will DC 13, failure can only move and take minor actions) |
| **Madness (Mental)** | Mind collapse | Triggered when Mind Points hit zero, see Mind Points note |

### 4.4.3 Status Effect Summary

| Status | Abbrev. | Effect | Removal |
|------|------|------|----------|
| **Stun** | STN | Cannot act | Pass Will DC 10 at end of each round |
| **Bleeding** | BLDe | −1 HP per round (Severe+ −2) | First Aid (Execution+First Aid DC 13) stops it |
| **Poisoned** | PSN | Wound level upgrades one step every 10 min | Antidote, or Will DC 12 / hour |
| **Burning** | BRN | −1 final damage per round (not reduced by TOL, Severe+ −2) | Extinguish (water/roll/fire suppression) |
| **Fear** | FER | Can only move and take minor actions | Threat gone, or pass Will DC 12 |
| **Bound** | BND | Cannot move | Break free (Execution DC 12) or external removal |
| **Blinded** | BLD | Disadvantage on attack checks | Pass Will DC 12 at end of each round to restore sight (or eye wash/treatment) |

### 4.4.4 Medical and Rest

Recovery paths after injury:

| Method | Condition | Effect |
|------|------|------|
| **Short Rest** | 1 hour safe time | Restore all Stamina; restore 50% Mind Points; no HP restored |
| **Long Rest** | 8 hours safe sleep | Restore all Stamina and Mind Points; HP restored to max (requires no untreated Bleeding/Poison) |
| **First Aid** | Consume medical kit; Execution+First Aid (Medicine) skill vs DC 13 | Stabilize Bleeding, restore 1d4+Will HP, stop wound worsening; usable on self or contacted others |
| **Medical Treatment** | Consume medical kit; Execution+First Aid DC 15 | Severe Wound needs hours, Fatal Wound needs days; only after treatment can Long Rest restore |
| **Healing Potion** | Consume 1 bottle | Restore = max(1d6+3, floor(Max HP × 25%)), and after healing HP not exceeding **75%** of max (high formula ensures low-tier sufficient, high-tier not a drop in the bucket) |
| **Antidote** | Consume 1 bottle | Immediately remove Poisoned |

> Medical kits and Healing Potions are consumable items, counts on character card; detailed list in *Item Codex*.

### 4.4.5 Stamina Depletion

| Stamina State | Effect |
|----------|------|
| Stamina > 0 | Normal action |
| Stamina = 0 | **Exhaustion**: all Execution checks Disadvantage; move cost doubled; cannot use combat skills |
| Stamina < 0 | Each 1 point overdraft = 1 level Light Wound (and Stamina set to 0) |

---

## 4.5 Memory-Bonus Combat

This is the core combat feature of Death Return TRPG—your memory directly affects combat power.

### First Encounter—Disadvantage Rule

When you fight a specific enemy for the **first time in the current Return loop**:
- All Attack checks: **Disadvantage**
- All Dodge checks: **Disadvantage**
- Exception: if Memory (MEM) ≥ 9, first encounter bears no Disadvantage (you remember this enemy from prior loops, fitting the "learn by dying" theme)

### Memory Bonus Table

| Memory (MEM) | Bonus Effect |
|------------|----------|
| 3–4 | Attack check +1 |
| 5–6 | Attack check +2, know 1 weakness |
| 7–8 | Attack check +3, know 2 weaknesses, Initiative +2 |
| 9–10 | Attack check +3, know all weaknesses, Initiative +3, first-encounter Disadvantage becomes Normal (cancels first-encounter Disadvantage) |
| 11+ | Attack Advantage + all weaknesses auto-active + Initiative +3 |

> Memory Bonus is smoothed: removed the original "1–2 cancels Disadvantage" dead tier (creation rule sets MEM minimum 3, never reachable); "all weaknesses auto-active" deferred to MEM 11+ to avoid MEM 9 single-point qualitative shift simultaneously bypassing "first-encounter Disadvantage" and auto-weakness, collapsing the loop experience.

### Weakness Strikes

| Weakness Type | Discover Condition | Strike Effect |
|----------|----------|----------|
| **Old Wound** | Memory 5+/Insight DC 14 | On hit final damage +1 (equiv wound level +1) |
| **Rhythm Blind Spot** | Observe minor action (Insight DC 12) | After hit target loses 2 TU next round |
| **Fear Trigger** | Memory 7+/story intel | Target Will DC 14, failure can only defend |
| **Equipment Weakness** | Memory 5+/Insight DC 13 | After hit target Armor Value halved |
| **Psychological Trauma** | Story unlock | After hit target all checks Disadvantage 2 rounds |

---

# Chapter Five: World Intro

## 5.1 Resonance Continent

The world you are in is called **Resonance Continent**. A land forgotten by time—past events refract repeatedly like echoes.

Legend says at the birth of time, a great serpent named **Ouroboros (the Time Serpent)** coiled above the void, devouring its own tail, creating the cycle of time. But a Time-Watcher named **Kadros** pierced the serpent's scales. Where the serpent's blood dripped, mortal souls were marked—this is the origin of the "Return Curse."

Souls touched by Serpent's Blood do not dissipate after death, but are pulled back to a moment in the past, again and again. These people are called **Returners**—you are one of them.

The current age is called the **Age of Embers**—three hundred years after the Radiant Gold Empire collapsed. Ashfall City is built on the empire's ruins, orderly on the surface, but time anomalies grow frequent underground. Returner appearances rise sharply; scholars call it "Serpent's Blood Boiling."

## 5.2 Ashfall City

Ashfall City is the core stage of your story. The city divides into five main districts:

| District | Feature | Key Locations |
|------|------|----------|
| **Bell Tower District** | Upper-class residential, Ashfall Council seat | Council Hall, Mayor's Mansion, Bell Tower Square |
| **Hearth District** | Commercial center, artisan guilds and market | "The Cup of Cycles" tavern, various shops |
| **Ash Alley** | Slums and underground society, Shadow Guild HQ | Black market, secret tunnel network |
| **Holy Relic District** | Death Church territory | Holy Relic Cathedral, Eternal Well |
| **Old City Ruins** | Radiant Gold imperial palace ruins | Shattered Throne Hall, Royal Archive |

At the city center is a deep well with an never-extinguished pale blue light pillar—the **Eternal Well (Well of Eternity)**. Most Returners' default Save Point is here.

### Three Great Factions

| Faction | Position | Attitude to Returners |
|------|------|---------------|
| **Death Church** | Religious organization, worships death and rebirth | Views as "god-chosen" to guide (actually control) |
| **Tower of Time** | Academic institution, studies time magic | Views as "research subject" (some want repair, some want elimination) |
| **Shadow Guild** | Underground intel network | Views as "infinite-retry tool" (hire and exploit) |

There is also the hidden **Returner Mutual Aid Society**—an underground mutual-aid organization of Returners, surviving in the cracks between the Three Great Factions.

---

## 5.3 On Magic and Player Abilities

Resonance Continent has four types of magic—elemental, life, shadow, and the most dangerous time magic (held by Tower of Time and Death Church high ranks). But **ordinary Returners (player characters) cannot cast magic**: you are ordinary people with Death Return, not spellcasters.

Magic affects players in these ways:

- **From NPC**: nuns, scholars, guild mages use magic, forming threat and support in combat or social.
- **From items**: magic scrolls, alchemy potions and other consumables let players indirectly gain one-time magic effects (see *Item Codex*).
- **From environment**: residual magic of time anomaly zones and ancient ruins affects rules (see GM Rulebook Chapter Fourteen).

> If some background or special ability allows casting, GM will clearly mark its limits and costs at character creation.

### 5.3.1 Mental Damage and Madness

Some enemies (e.g., Time Devourer Prototype, Inquisitor) and some environmental magic cause **Mental Damage**. Mental Damage deducts **Mind Points (MP)** rather than HP:

- When Mind Points hit zero triggers **Madness (MAD)**: from that loop all social and mental checks get **Disadvantage**; at each loop end pass Will (WIL) DC 13 to recover 1d4 Mind Points, two consecutive rounds passing = exit Madness.
- During Madness if hit by Mental Damage again and Mind Points insufficient to deduct, overflow instead deducts HP.
- Short Rest/Long Rest can normally recover Mind Points (see 4.4.4).

### 5.3.2 Magic Scrolls

Players cannot cast, but can gain one-time magic effects via **Magic Scrolls** (values see *Item Codex* special type). Common scrolls: Flame Scroll (2d6 Fire Damage, 30G), Healing Scroll (restore 1d6+3 HP, 40G), Warding Scroll (absorb 1 hit, 35G), Purification Scroll (remove all negative statuses, 25G). Scrolls are consumable, burned after use.

---

# Appendix

## Quick Reference Card

### Check Flow

```
1. GM declares check type and DC
2. Confirm your Attribute + Skill = Modifier
3. Confirm if Advantage/Disadvantage
4. Roll: Normal(1d20), Advantage(2d20 take higher), Disadvantage(2d20 take lower)
5. Result = d20 + Modifier, compare with DC
```

### Memory Fragment Quick Pick

| Want to do? | Carry what? |
|-----------|----------|
| Quickly rebuild relationship with an NPC | Character Fragment ×1 (cost 1) |
| Safely explore an area | Location Fragment ×1 (cost 2) |
| Retain combat/lockpick ability | Skill Fragment ×1 (cost 2) |
| Ensure one survival | Fate Fragment ×1 (cost 5) |
| Optimize route planning | Event Fragment ×N (cost 1 each) |

### Rift Mark Stage Quick

| Feeling | Rift Mark | Strategy |
|------|--------|------|
| "I'm fine" | 0–9 | Normal play |
| "NPC seems to dislike me" | 10–19 | Avoid social, use stealth instead |
| "I'm too sensitive, but mentally tired" | 20–29 | Use Insight Advantage, avoid Will checks |
| "Every pressure makes me break" | 30–39 | Finish goal ASAP, consider relieving Rift Mark |

### Combat Action Cost Quick

| Action | TU | Stamina |
|------|--------|------|
| Major Action (attack/combat skill) | 3 | 2 |
| Minor Action | 1 | 0 |
| Move (1 zone) | 1 | 0 |
| Sprint (3 zones) | 2 | 1 |
| Rest | 3 | +Execution SP |
| Reaction | 0 | 1 |

### Wound Quick

| Wound Level | Remaining HP | Main Effect |
|---------|-----------|----------|
| 0 No Wound | 100% | Normal action |
| 1 Light Wound | 76–99% | Record wounded location |
| 2 Moderate Wound | 51–75% | Disadvantage on that location's actions + Bleeding (Sharp) |
| 3 Severe Wound | 26–50% | All Execution Disadvantage + halved movement + each round Will DC 12 |
| 4 Fatal Wound | 1–25% | Cannot take Major Actions + each round death check |
| 5 Death | 0% | Triggers Return |

---

## Glossary

| Term | Abbrev. | Notes |
|----------|------|------|
| Insight | INS | Observe details, notice anomalies, read people |
| Memory | MEM | Ability to retain prior-loop info |
| Execution | EXE | Actual operational ability |
| Social | SOC | Persuasion, charm, build relationships |
| Will | WIL | Bear psychological burden of death |
| Difficulty Class | DC | Check target value |
| Advantage | ADV | 2d20 take higher |
| Disadvantage | DIS | 2d20 take lower |
| Critical Success | Crit | Natural 20 |
| Critical Failure | Disaster | Natural 1 |
| Memory Fragment | MF | Info carried across loops |
| Event Fragment | EF | Remember event (cost 1) |
| Character Fragment | CF | Remember NPC (cost 1) |
| Location Fragment | LF | Remember location (cost 2) |
| Skill Fragment | SF | Retain skill (cost 2) |
| Fate Fragment | FF | Force survival (cost 5) |
| Rift Mark | RM | Death-accumulated psychological trauma |
| Rift Threshold | RT | Fixed 10 (Unbalanced start, pure narrative cue; stages by absolute Rift Mark value, not shifted by Will) |
| Save Point | — | Death Return destination |
| Intel Layer | IL | Information gathering phase |
| Execution Layer | EL | Action execution phase |
| Hit Points | HP | Total damage capacity (Execution+Will+5) |
| Mind Points | MP | Social/mental check consumption and fear resistance (Will+Memory+3) |
| Stamina Points | SP | Stamina resource (Execution+Will+3), zero = Exhaustion |
| Damage Tolerance | TOL | Damage reduction (TOL = AV + floor((EXE+WIL)÷4), soft cap 9; final damage = raw − TOL) |
| Time Unit | TU | Combat action measure |
| Stun | STN | Cannot act, Will DC 10 each round to remove |
| Bleeding | BLDe | −1 HP per round, first aid stops |
| Poisoned | PSN | Wound level upgrades every 10 min, antidote or Will DC 12 removes |
| Burning | BRN | −1 final damage per round (not reduced by TOL), extinguish stops |
| Fear | FER | Will DC 13 failure = only move and minor actions |
| Bound | BND | Cannot move, need to break free |
| Blinded | BLD | Disadvantage on attack checks, Will DC 12 pass or sight restored removes |
| Mental Damage | MD | Damage deducting Mind Points (MP); zero triggers Madness |
| Madness | MAD | Triggered at zero Mind Points, Disadvantage on social/mental checks, recover via Will DC 13 each round |
| Returner | — | Individual with Death Return ability |
| Relationship Value | RV | NPC-player closeness |
| Suspicion Value | SV | NPC suspicion of player's abnormal behavior |

---

## Character Creation Worksheet

### Quick Creation Checklist

- [ ] Choose cause of death type (gain attribute bonus and special ability)
- [ ] Choose Return Source (gain source bonus)
- [ ] Choose background (gain attribute bonus and two background abilities)
- [ ] Distribute 18 buy points (attributes 4–9; Memory and Will same range, no minimum-3 limit)
- [ ] Calculate derived attributes
- [ ] Define Save Point (type + specific description)
- [ ] Write "the one you don't want to redo" (trauma type + story)
- [ ] Write "the one you'll always remember" (name + relationship type + story)
- [ ] Roll 1d6 for initial Rift Mark value
- [ ] Record special abilities (1 cause-of-death ability + 2 background abilities)
- [ ] Distribute 8 skill points (creation cap 3)
- [ ] Record starting equipment

---

> *"Are you ready? Open your eyes—it's a new day. You remember everything. They remember nothing."*

**Death Return TRPG Player Rulebook v1.0**
