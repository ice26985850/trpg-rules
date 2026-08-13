# Backrooms Walker TRPG — GM Rulebook

> **Version:** v1.1
> **Design Studio:** Tabletop Rules Studio
> **Language:** Traditional Chinese
> **Audience:** Game Master (GM)

---

# How to Use This Rulebook

## A Word to the GM

This GM rulebook contains everything you need to run "Backrooms Walker TRPG." It is designed to be **self-contained** — you do not need to read the Player Rulebook separately (though it is recommended that players read it).

**You are the most important participant in this game.** You create the world, play the NPCs, adjudicate actions, and guide the players through a story of trying not to die in an infinite maze. This rulebook is your toolbox.

## GM Rulebook Structure

| Volume | Content |
|--------|---------|
| **Volume I: Core Rules** | Complete dice system, attribute framework, and check mechanics (including probability analysis) |
| **Volume II: Character System** | Character creation process, background templates, and growth system |
| **Volume III: Combat & Entities** | Complete combat rules, full stats for five core Entities, and status effects |
| **Volume IV: Worldview** | The nature of The Backrooms, complete data for fifteen or more Levels, and the Four Factions |
| **Volume V: GM Toolkit** | Atmosphere building, pacing control, horror narration, solo support, and improvisation guide |
| **Volume VI: Scenario Framework** | Design outlines and running guidance for eight complete scenarios |
| **Volume VII: Optional Rules** | Hardcore survival mode, narrative-driven mode, and multiplayer adjustments |
| **Appendix** | Encounter tables, glossary, and quick reference |

> **Reference Compendium**: For complete stats and distributions of Entities, items, and Levels, see the bundled *Entity Compendium*, *Item Compendium*, and *Level Compendium*.

---

# Volume I: Core Rules

## Chapter One: Basic Dice System

### 1.1 Core Formula

Backrooms Walker TRPG uses a basic dice system of **D20 + Attribute Value + Proficiency Bonus vs Difficulty Class (DC)**.

```
Check Result = D20 + Attribute Value (AV) + Proficiency Bonus (PB) + Circumstance Modifier
Success Condition: Check Result ≥ Difficulty Class (DC)
```

### 1.2 Design Philosophy

| Design Choice | Rationale |
|---------------|-----------|
| Attribute bonus = the Attribute Value itself (1-10) | Intuitive and transparent. An ordinary person with Attribute 5 has a 55% success rate against DC 15 — sitting right in the optimal "challenging but doable" gameplay zone |
| Proficiency Bonus +3/+5 | Training brings reliability, not invincibility. Expertise raises the DC 15 success rate from 55% to 80% |
| Dual-track Critical Success | Natural die and Margin of Success (MoS) judged independently, ensuring experts do not fail absurdly while the weak can still break through in desperate straits |
| DC 5-25 full spectrum | Covers all difficulties from everyday to legendary; DC 25 is extremely rare for Attribute 5 and below (relying only on the 5% of a natural 20) |

### 1.3 Critical Success and Critical Failure (Dual-Track)

| Situation | Trigger Condition | Effect |
|-----------|-------------------|--------|
| **Critical Success** | Natural die 20, or Check Result ≥ DC + 10 | The action outcome is better than expected. The GM describes an extra positive effect. |
| **Critical Failure** | Natural die 1, or Check Result ≤ DC - 10 | The action goes wrong in the worst possible way. The GM describes a memorable negative consequence. |
| **Legendary Success** | Natural die 20 and Check Result ≥ DC + 10 | A near-miraculous result. May change the entire direction of the scene. |
| **Catastrophic Failure** | Natural die 1 and Check Result ≤ DC - 10 | Catastrophic consequence. May produce long-term negative effects. |

**GM Tip**: Critical Success and Critical Failure are narrative tools. Do not just say "you succeeded" or "you failed" — describe why the result is especially good or especially bad. Let the story of the dice become part of the story.

### 1.4 Advantage and Disadvantage

Advantage and Disadvantage are the most flexible difficulty-adjustment tools in the GM's hands:

- **Advantage**: The player rolls 2D20 and takes the higher. Roughly equivalent to a +3.3 bonus (but does not change the range).
- **Disadvantage**: The player rolls 2D20 and takes the lower. Roughly equivalent to a -3.3 bonus.

**When to grant Advantage**:
- The character is well prepared and has suitable tools
- Another character provides effective assistance
- The environment is especially favorable
- The character exploits a known weakness of an Entity

**When to grant Disadvantage**:
- The character is under stress, panic, or injured
- The environment is especially unfavorable (darkness, noise, stench)
- The character attempts action beyond a reasonable scope
- An Entity uses a special ability to interfere

**Important Rule**: Advantage and Disadvantage cancel each other out (they do not stack). If a character has both Advantage and Disadvantage, roll a normal single D20.

### 1.5 Contest Check

When two characters (or a character and an Entity) directly oppose each other:

- Both sides roll D20 + relevant bonus
- The higher result wins
- On a tie, the defender (or passive side) has the advantage

**Contest Check Probability**: A +3 bonus difference is roughly equivalent to a 14% win-rate advantage (significant but not overwhelming).

### 1.6 Team Checks

| Check Type | Rule |
|------------|------|
| **Collaboration** | The helper makes a relevant DC 10 check. On success → the main checker gains Advantage. |
| **Team Stealth** | Each member makes their own Stealth check. More than half succeed → team succeeds. Fewer than half → entire team is detected. |
| **Team Search** | Each member makes their own Search check. Take the highest result. |
| **Team Navigation** | The pathfinder makes the check (may gain assistance Advantage from teammates). |

---

## Chapter Two: The Five Attributes System

### 2.1 Attribute Details

| Attribute | Abbrev | Range | Meaning | Used For |
|-----------|--------|-------|---------|----------|
| Physique | PHY | 1-10 | Physical health, endurance, physical tolerance | HP calculation, Carry Capacity, Endurance checks, Might checks |
| Agility | AGI | 1-10 | Speed, reaction, dexterity | Defense (DEF) calculation, Initiative, Stealth, Evasion, fleeing |
| Perception | PER | 1-10 | Observance, acuity, intuition | Search, Track, detecting threats, Initiative |
| Sanity | SAN | 1-10 | Mental resilience, psychological tolerance | SP calculation, Willpower checks, resisting fear |
| Knowledge | KNO | 1-10 | Understanding of The Backrooms, memory | Backrooms Lore, First Aid, Crafting, Spatial Memory |

**Attribute bonus = the Attribute Value itself**. This is the core design choice of Backrooms Walker TRPG — simple, transparent, intuitive.

**Initial Allocation**: 25 points, with a single-attribute cap of 8 (at initial creation).

### 2.2 Complete Derived Attribute Formulas

| Derived Attribute | Formula | Range | Notes |
|-------------------|---------|-------|-------|
| Hit Points (HP) | Physique × 2 + 5 | 7-25 | **Note: This is very low HP. This is intentional. Combat is the last option.** |
| Defense (DEF) | 10 + Agility Value | 11-20 | Entity attacks must be ≥ this value to hit |
| Sanity Points (SP) | Sanity × 3 + 10 | 13-40 | Mental health. Reaching zero = loss of control |
| Almond Water Reserve | — | Initial 5 | The Backrooms' liquid gold |
| Calorie Reserve | — | Initial 10 | 1 consumed per day |
| Carry Capacity | Physique × 2 kg | 2-20 kg | Warehouse Worker background changes to ×3 |
| Movement Speed | 6 + Agility Value m/turn | 7-16 m | Base movement in combat |
| Initiative Bonus | Agility Value + Perception Value | +2 ~ +20 | Determines action order |

---

## Chapter Three: Skill System (Complete 18 Skills)

### 3.1 Skill List and Attribute Mapping

#### Physique (PHY) Skills

| # | Skill | Description | Typical DC Example |
|---|-------|-------------|--------------------|
| 1 | **Athletics** | Climbing, jumping, swimming, long-distance movement | Climbing a slippery pipe DC 13 |
| 2 | **Endurance** | Resisting fatigue, enduring hunger/thirst, extreme temperatures | Sustained activity in 35°C pipes DC 12 |
| 3 | **Might** | Lifting, breaking obstacles, pushing jammed doors | Pushing open a rusted iron door DC 14 |

#### Agility (AGI) Skills

| # | Skill | Description | Typical DC Example |
|---|-------|-------------|--------------------|
| 4 | **Stealth** | Silent movement, hiding | Slipping past Hounds in the dark DC 14 |
| 5 | **Acrobatics** | Balance, tumbling, narrow passages | Running on slippery tiles DC 12 |
| 6 | **Sleight of Hand** | Lockpicking, disarming traps, fine manipulation | Opening a simple lock with a paperclip DC 12 |
| 7 | **Evasion** | Dodging attacks, escaping danger zones | Evading falling debris DC 13 |

#### Perception (PER) Skills

| # | Skill | Description | Typical DC Example |
|---|-------|-------------|--------------------|
| 8 | **Search** | Finding supplies, clues, hidden items | Finding Almond Water in a messy drawer DC 15 |
| 9 | **Track** | Following traces, identifying footprints | Following a blood trail through cubicles DC 12 |
| 10 | **Insight** | Judging intent, detecting deception | Noticing a Partygoer's abnormal smile DC 14 |
| 11 | **Danger Sense** | Instinctively sensing impending danger | Sensing an imminent Hound ambush DC 15 |

#### Sanity (SAN) Skills

| # | Skill | Description | Typical DC Example |
|---|-------|-------------|--------------------|
| 12 | **Willpower** | Resisting fear, staying calm | Resisting SP loss from witnessing an Entity DC 15 |
| 13 | **Composure** | Maintaining sanity under high pressure | Keeping a sense of direction in a spatial anomaly DC 14 |
| 14 | **Meditation** | Recovery through mental focus | Meditating to recover SP in a safe zone DC 12 |

#### Knowledge (KNO) Skills

| # | Skill | Description | Typical DC Example |
|---|-------|-------------|--------------------|
| 15 | **Backrooms Lore** | Recalling Level info, Entity traits | Recalling the Hound nest location on Level 2 DC 15 |
| 16 | **First Aid** | Treating wounds, stabilizing injuries | Emergency treatment for a gravely wounded teammate DC 13 |
| 17 | **Crafting** | Repairing, making tools, modifying | Crafting a simple spear from scrap metal DC 14 |
| 18 | **Spatial Memory** | Remembering routes, not getting lost, drawing maps | Finding the way back to the exit in Level 0 DC 14 |

### 3.2 Three Proficiency Tiers

| Tier | Bonus | How Acquired |
|------|-------|--------------|
| Untrained | +0 | Default. All skills start here. |
| Trained | +3 | Initially gained 3-4 from background + 2 free choices. |
| Expert | +5 | Initially may choose 1 Expert. Later gained through Milestones. |

### 3.3 Advancing Skill Proficiency

During play, players may gain new proficiencies through the following means:
- **Milestone Growth**: Reaching each Milestone grants an Expert or Trained proficiency
- **GM Reward**: After repeated use and success with a specific skill, the GM may reward a proficiency increase

---

## Chapter Four: Difficulty Class (DC) Complete Ladder

### 4.1 DC Scale

| DC | Label | Common Scenario | Attribute 5 Success Rate | Attribute 5+Expert |
|----|-------|-----------------|--------------------------|--------------------|
| 5 | Trivial | Opening an unlocked door, walking in lit areas | 100% | 100% |
| 8 | Easy | Climbing a low wall, remembering a simple route | 90% | 100% |
| 10 | Routine | Searching a messy desk, picking a simple lock | 80% | 95% |
| 12 | Moderate | Identifying common Entities, climbing pipes | 70% | 90% |
| 15 | Hard | Searching for useful supplies, stealth in darkness | 55% | 80% |
| 18 | Very Hard | Forcing a level shift, stealth past an Entity nest | 40% | 65% |
| 20 | Extreme | Finding direction in the dark, persuading a hostile NPC | 30% | 55% |
| 22 | Epic | Going unnoticed among a group of Entities, solving a complex puzzle | 20% | 40% |
| 25 | Near Impossible | Locating the exit in total darkness, memorizing an entire Level map | 5% | 30% |

### 4.2 Situational DC Fluctuation

These are tools for the GM to adjust DC. Do not tell players the adjustment value directly — weave it into the environment description.

| Factor | DC Adjustment | Narrative Integration |
|--------|---------------|------------------------|
| Ample light | -2 | "The fluorescent lights are bright; you can see every corner clearly" |
| Dim/faint light | +2 | "The light is insufficient — you can only see blurry outlines" |
| Total darkness | Automatic failure* | "Pitch black. You can see nothing. You need a light source." |
| With suitable tools | -2 to -5 | "Your lockpicking tools fit this lock perfectly" |
| Ample time | -3 | "You have plenty of time — take it slow, check each drawer carefully" |
| Pressing time | +2 | "You hear footsteps getting closer. You must hurry." |
| Character already injured | +2 | "Your wound throbs, distracting your focus" |
| Character in panic | +3 | "Your hands are trembling. Focusing becomes extremely difficult" |
| Entity nearby | +2 | "You know it's nearby. The back of your neck tingles." |

*Exception in total darkness: Characters with special abilities, darkvision, or using other senses may still attempt (but the DC is extremely high).

### 4.3 Complete Probability Curve

Below are the success rates at four key reference points across each DC, for the GM's reference when assessing difficulty:

| DC | Attribute 3 (Weak) | Attribute 5 (Average) | Attribute 8 (Excellent) | Attribute 5+Expert (+5) |
|----|--------------------|-----------------------|-------------------------|-------------------------|
| 5 | 95% | 100% | 100% | 100% |
| 8 | 80% | 90% | 100% | 100% |
| 10 | 70% | 80% | 95% | 95% |
| 12 | 60% | 70% | 85% | 90% |
| 15 | 45% | 55% | 70% | 80% |
| 18 | 30% | 40% | 55% | 65% |
| 20 | 20% | 30% | 45% | 55% |
| 22 | 10% | 20% | 35% | 40% |
| 25 | 5% | 5% | 10% | 30% |

**GM Reference**: DC 15 is the baseline for "Hard" tasks. An Attribute 5 character has a 55% success rate — feeling like a fair challenge. An Attribute 5+Expert character has 80% — feeling like work they are good at.

---
## Chapter 5: Special Check Rules

### 5.1 Level Movement Check

| Movement Method | Check Type | DC | Success | Failure |
|-----------------|------------|-----|---------|---------|
| Discover a Known Exit | No Check Required | — | Pass Directly | — |
| Search for a New Exit | Perception Check | 15-20 | Locate the Exit | Continue Searching (costs time and resources) |
| Forced Exit | Sanity Check | 18 | Successfully exit to another Level | Stuck in the wall (1D4 damage), or fall into a worse Level |
| Follow Others | No Check Required | — | Pass Directly | — |

### 5.2 Scavenging Check

`D20 + Perception value + Search Proficiency Bonus vs Area Richness DC`

| Area Richness | DC | Description |
|---------------|-----|-------------|
| Rich (Level 1 Warehouse) | 8 | Basic supplies are easy to find |
| Moderate (Level 0) | 12 | Requires some time and attention |
| Scarce (Level 2 Dark Zone) | 15 | Supplies exist but are hard to discover |
| Depleted (already scavenged area) | 18 | Almost completely stripped |
| High-Value Target (specific rare item) | 20 | Find a specific rare item |

**Critical Success (5+ above DC)**: Find additional or rarer items.

### 5.3 Complete Stealth Rules

#### Basic Stealth
`D20 + Agility value + Stealth Proficiency Bonus vs Entity's Perception value`

#### Effect of Light on Stealth
| Light Condition | Effect on Stealth User | Effect on Entity |
|-----------------|------------------------|------------------|
| Fully Lit | Disadvantage (unless effective cover) | Normal |
| Dim Light | Normal | Disadvantage |
| Total Darkness | Advantage (if Entity relies on sight) | Requires special perception to detect |
| Flickering Lights | Random each turn (1D6: 1-3 lit, 4-6 dark) | Same as above |

#### Group Stealth
- Each member makes their own Stealth Check
- More than half succeed → Group succeeds overall
- Half or fewer succeed → Entity becomes aware of the group's presence
- A character with Expert Stealth can attempt to guide the group (make a DC 15 Stealth Check; on success all members gain +2)

### 5.4 Fleeing and Chase Rules

When a player decides to flee, initiate the chase mechanic (rather than a normal Agility contest):

**Step One: Set Chase Distance**
The GM sets the starting chase distance based on the situation (usually 4-8):
- Entity appears suddenly (close-range ambush): distance 4-5
- Character perceives Entity before it approaches: distance 6-8

> **⚠ Straight-Line Ambush Protection**: If the encounter occurs in an "unobstructed pure straight corridor" (such as Level ! or Level 2 corridors), the starting distance must not be below 4-5; and the GM should ensure each chase includes at least 1 corner, to avoid the near-certain-death situation of "caught after losing two turns in a row." A corner reduces the Hounds' Agility value to 4/3 (see terrain effects), restoring the designed experience of "using corners to escape."

**Step Two: Chase Rounds**
Each round both sides make an Agility Contest Check:
- Character wins: distance +2
- Entity wins: distance -2
- Tie: distance unchanged

**Step Three: Distance Effects**

| Distance | Status |
|----------|--------|
| 0 | Caught — enters melee |
| 1-3 | Dangerous distance — Entity can attack (Disadvantage) |
| 4-6 | Controllable distance — Entity cannot attack but can pursue |
| 7-9 | Safe distance — Entity at edge of sight |
| 10 | **Successfully Escape!** |

**Terrain Effects**:
- Corners/narrow spaces: Favorable to Hounds (they turn clumsily, so narrow spaces are instead unfavorable)
- Open straight: Favorable to Hounds (speed advantage)
- Slippery ground: Disadvantage for both sides
- Dark environment: Favorable to Smilers (if character has no light source)

**Cumulative Fatigue**: After every 3 chase rounds, the character's Agility Check gains a cumulative -1 penalty.

### 5.5 Environment Interaction Check

| Interaction | Check | DC | Success | Failure |
|-------------|-------|-----|---------|---------|
| Push heavy shelving | Might | 14 | Shelving moves, creating a passage or obstacle | Shelving collapses — huge noise attracts attention |
| Climb slippery pipes | Athletics | 13 | Reach upper pipe level | Slip — 1D3 damage |
| Pry open locked door | Sleight of Hand | 12-18 | Door is opened | Lock damaged — door cannot be opened |
| Repair broken equipment | Crafting | 14 | Equipment temporarily restored | Equipment completely destroyed |
| Read predecessor's notes | Backrooms Lore | 10-15 | Understand useful information | Misunderstand information (GM gives vague or misleading information) |

---

# Volume Two: Character System (GM Perspective)

## Chapter 1: Character Creation GM Guidance

(This section overlaps with Chapter 3 of the player rulebook, but provides additional guidance from the GM's perspective.)

### 1.1 Assisting Players in Character Creation

When players create characters, the GM's role is that of a guide and gatekeeper:

- **Encourage narrativity**: Help players imagine their character as a "real person," not a string of numbers
- **Ensure reasonable attributes**: 25-point allocation, single attribute 1-8 (initial). There is no "useless low attribute" — every attribute has an important use in The Backrooms
- **Review starting items**: Ensure total weight does not exceed Carry Capacity
- **Record story hooks**: The answer players provide in Step Six "Do you want to go back?" is your most important story resource — write it down!

### 1.2 Background Ability Balance

The eight Background abilities are designed to provide interesting gameplay choices rather than pure numerical advantage. The GM should plant corresponding opportunities to shine in the scenario based on the player's Background:

| Background | Ability | Opportunity the GM Should Provide |
|-----------|---------|-----------------------------------|
| Night Shift Security Guard | Night Vision Adaptation | Arrange key observation points in dim-light environments |
| Delivery Worker | Shortcut Thinking | Provide navigation advantage in complex corridors |
| Graduate Student | Theory Application | Arrange a physical anomaly that requires understanding |
| ER Nurse | Emergency Response | Arrange an NPC in need of treatment |
| Warehouse Worker | Load Adaptation | Provide large amounts of supplies — but they must be carried |
| Photographer | Eye for Detail | Arrange secrets that require careful observation to discover |
| Wanderer | Veteran's Intuition | Prepare a secret that "only a veteran would know" |
| Office Worker | Administrative Resilience | Arrange scenes requiring patient perusal of large volumes of documents |

---

## Chapter 2: Growth System — Eight Milestones

### 2.1 Milestone Overview

Backrooms Walker does not use a traditional leveling system. Character growth is expressed through "Milestones" — important moments in life.

| # | Milestone Name | Trigger Condition (Narrative) | Trigger Condition (Mechanical Reference) |
|---|----------------|-------------------------------|------------------------------------------|
| 1 | **First Awakener** | Create character | Initial state |
| 2 | **Survivor** | Successfully survive the first crisis | Complete the main objective of the first scenario |
| 3 | **Explorer** | Enter a new Level for the first time | Fully explore a new Level (GM adjudicates) |
| 4 | **Adapter** | Survive in The Backrooms for over a month | Cumulatively complete 3+ sessions |
| 5 | **The Knower** | Master the deep secret of a certain Level or Entity | Discover an important world secret |
| 6 | **Guardian** | Save or protect another life | Choose to help others at a critical moment |
| 7 | **The Enlightened** | Understand a part of The Backrooms' essence | Come into contact with the core mystery of The Backrooms |
| 8 | **Legend** | Find an exit or make the final choice | Complete the endgame scenario |

### 2.2 Growth Rewards for Each Milestone

| Milestone | Attribute Points | Skill Growth | Special Reward |
|-----------|------------------|--------------|----------------|
| 1 First Awakener | — | Initial allocation | Background ability |
| 2 Survivor | — | 1 skill raised from Untrained to Trained | — |
| 3 Explorer | +1 any attribute | — | — |
| 4 Adapter | — | 1 skill raised to Expert | — |
| 5 The Knower | +1 any attribute | 1 skill raised to Trained | A new Background ability or variant |
| 6 Guardian | — | 1 skill raised to Expert | Gain a permanent ally relationship with a stronghold |
| 7 The Enlightened | +1 any attribute (can exceed 10 cap) | — | A unique ability (designed through GM-player negotiation) |
| 8 Legend | — | — | Ending reward — depends on the character's final choice |

### 2.3 Power Curve Analysis

| Milestone | Attribute Total Range | Expert Skills Count | Power Description |
|-----------|----------------------|---------------------|-------------------|
| 1 First Awakener | 25 | 1 | Ordinary mortal, first day in The Backrooms |
| 3 Explorer | 26 | 1-2 | Experienced Wanderer, beginning to grasp survival tricks |
| 5 The Knower | 27 | 2-3 | Veteran Wanderer, with deep understanding of The Backrooms |
| 7 The Enlightened | 28+ (can exceed 10) | 3-4 | Near-legendary being, may have mastered The Backrooms' secrets |

**Note**: The power curve is gentle. Characters do not become superheroes — but they become noticeably more capable of survival. Three attribute points and two Expert tiers across the entire campaign are significant but not exaggerated improvements.

---

# Volume Three: Combat and Entities (GM Complete Edition)

## Chapter 1: Complete Combat Rules

### 1.1 When Combat is Triggered

The GM controls when combat is triggered. In Backrooms Walker, most encounters should not begin with combat — they should begin with **awareness**.

**Encounter Flow**:
```
Environment description → Player perception (may detect threat) → Player decision (bypass/stealth/flee/interact) → Enter combat on failure
```

Combat rounds are triggered only in the following situations:
- Players are discovered by an Entity and cannot/unwilling to flee
- Players actively choose to attack
- Entity's active attack is unavoidable (such as Hounds ambush)

### 1.2 Initiative Rules

- Each participant makes an Initiative Check: `D20 + Agility value + Perception value`
- Results arranged from high to low
- Tie: higher Agility value acts first; if still tied, players act first
- **Ambusher automatically placed in first position** (regardless of Initiative Check result)

### 1.3 Action Economy (2 AP/turn)

Each participant has **2 Action Points (AP)** and **1 Reaction** per turn.

#### Complete Action List

| Action | AP | Type | Description |
|--------|-----|------|-------------|
| Move (1 zone) | 1 | Move | Move to an adjacent distance zone |
| Attack | 2 | Action | Make one attack |
| Use Item | 1 | Action | Drink potion, use bandage, swap equipment |
| Environment Interaction | 1 | Action | Open door, push object, pull lever |
| Hide | 1 | Action | Find cover and stealth |
| Observe | 1 | Action | Carefully observe to gain information (Perception Check) |
| Defensive Stance | 1 | Action | Attacks against you this turn gain Disadvantage |
| Assist | 1 | Action | Next ally Check gains Advantage |
| Sprint | 2 | Move | Move 2 distance zones |
| Wait | 0 | Special | Delay action to a later point in this turn |

#### Reactions (1 per turn)

| Reaction | Trigger | Effect |
|----------|---------|--------|
| Evade | Being attacked | Defense +2 |
| Attack of Opportunity | Enemy flees from nearby | One free melee attack |
| Change Intent | Major environmental change | Change a declared action |

### 1.4 Distance System

| Distance | Range | Vision | Attack | Sound |
|----------|-------|--------|--------|-------|
| Close | 0-2 m | Clear | Melee reachable | Whisper audible |
| Medium | 2-10 m | Clear | Thrown/short-range | Normal conversation |
| Far | 10-30 m | Blurry | Ranged weapons | Loud shout |
| Out of Sight | 30+ m | Invisible | No | None |

**Movement Cost**: 1 AP to move 1 zone.

### 1.5 Attack and Damage

#### Attack Check
`D20 + Agility value (melee) or Perception value (ranged) + weapon-related bonus vs DEF`

**Hit**: Roll weapon damage die.

#### Weapon Damage Players May Use

| Weapon | Damage | Notes |
|--------|--------|-------|
| Bare Hands | 1D3 | Not recommended against Entities |
| Iron Pipe/Iron Hammer | 1D6 Bludgeoning | Common improvised weapon |
| Machete | 1D8 Slashing | Requires finding or trading to obtain |
| Fire Axe | 1D10 Slashing | Heavy (3 kg), Uncommon |
| Homemade Spear | 1D6 Piercing | Medium range, requires crafting |

**Damage Effect on Entities**: Most Entities have significant resistance to physical damage. The GM should track Entity HP behind the scenes, but should not give exact numbers in damage narration — instead describe the Entity's reaction ("It flinched a bit, but didn't seem to take serious damage").

### 1.6 Combat End Conditions

Combat ends in the following situations:
- One side successfully flees (chase distance reaches 10)
- One side is defeated/unconscious
- Environmental change makes combat impossible to continue (lights restored, floor collapses, etc.)
- Both sides reach some form of agreement
## Chapter 2: Damage and Healing System

### 2.1 Hit Points (HP) Formula

**HP = Physique × 2 + 5 (range 7-25)**

This is a very low HP. Design intent: make every instance of Damage tense, and make Combat a genuine danger.

### 2.2 Damage Types

| Type | Example | Effect on Different Targets |
|------|---------|-----------------------------|
| **Physical — Bludgeoning** | Struck by a Hound, falling object | Normal against all targets |
| **Physical — Slashing** | Claw strike, knife wound | Halved against some Entities |
| **Physical — Piercing** | Spikes, debris | Normal against all targets |
| **Environmental** | Steam burn, drowning, crushing | Normal against all targets |
| **Mental** | Sanity damage | Only effective against humans |

### 2.3 Damage Value Reference (GM Behind the Screen)

| Damage Source | Base Damage | Note |
|---------------|-------------|------|
| Hound claw strike | 1D6+2 (Physical Slashing) | Higher damage when in packs |
| Hound charge | 1D8 (Physical Bludgeoning) | May knock the target down |
| Smiler touch | 1D4 (Physical) + SP -1D4 | Main threat is SP loss |
| Partygoer group attack | 1D4 × number of participants | Weak alone, extremely dangerous in groups |
| Skin-Stealer attack | 2D6 (Physical Piercing) | Only attacks when exposed |
| Environmental — Fall (3m) | 1D6 | +1D6 for every additional 3m |
| Environmental — Steam burn | 1D4 | Light contact |
| Environmental — Drowning | 1D4/round | Under suffocation rules |
| Environmental — Crushing | 2D8 | Serious accidents such as collapse |

### 2.4 Injury Status Thresholds

| Status | HP Threshold | Effect |
|--------|--------------|--------|
| Healthy | 100-61% | Normal |
| Lightly Wounded | 60-31% | All Checks -1 |
| Severely Wounded | 30-1% | All Checks -2, Movement Speed halved |
| Near Death | 0 | Disadvantage on all Checks, Physique DC 15 each round or die (stabilize after 3 successful saves) |

### 2.5 Healing Values

| Healing Method | HP Recovery | SP Recovery | Note |
|---------------|-------------|-------------|------|
| Almond Water (drink) | 1D6 | 1D4 | 1 unit per use |
| Bandage | 2D6 | — | Removes bleeding |
| First Aid supplies | 3D6 | — | Removes bleeding + poisoning |
| Short rest (1 hour) | 1D6 | — | Relatively safe area |
| Full rest (8 hours) | 50% max HP | 1D4 | Requires safe area |
| Social contact | — | +1~3 | Limited to once per encounter |
| Meditation | — | +1 | DC 12, 1 hour |

---

## Chapter 3: The Five Core Entities — Complete Game Data

> **GM Note**: Entities are not "monsters." They are part of the environment. Do not treat the data below as "Combat stats" — treat them as "encounter rules."

---

### Entity One: Smiler

> *"You thought you were safe in the dark, because no one could see you. But Smilers don't need to see you — they only need the dark."*

#### Basic Stats

| Attribute | Value | Description |
|-----------|-------|-------------|
| Threat Level (TL) | ★★★ | Extremely dangerous in the dark, no threat when there is a light source |
| Hit Points (HP) | 15 | Can be damaged when materialized, but physical attacks have limited effect |
| Defense (DEF) | 14 | Ethereal in the dark (Disadvantage on physical attacks) |
| Attack Bonus | +5 (only in the dark) | Darkness touch |
| Damage | 1D4 Physical + SP -1D4 | Main threat is mental damage |
| Perception | 18 (in dark) / 8 (in light) | Extremely keen senses in the dark |
| Agility | 4 | Moves slowly but is not blocked by walls (in the dark) |

#### Core Mechanic — Lighting System

| Light Level | Smiler State | Player Safety |
|-------------|--------------|---------------|
| **Full Light** (flashlight direct beam / fluorescent lights fully on) | Banished — cannot exist in this area | Completely safe |
| **Dim Light** (flickering fluorescent / glow stick) | Present but ethereal — cannot attack, only perceived | Relatively safe |
| **Flickering** (unstable light, random each round) | 50% chance to materialize each round | Dangerous — unpredictable |
| **Darkness** (no light source at all) | Fully materialized — can attack and pursue | Extremely dangerous |

#### Encounter Flow

1. **Darkness Falls**: The GM describes the light source going out or the character entering a dark area
2. **The Feeling of Being Watched**: The character feels watched (Perception DC 15 to notice the Smiler's presence)
3. **The Smile Appears**: An oversized grin emerges from the dark (SP -1D3, halved on Willpower DC 15)
4. **Attack**: If the character does not flee or restore a light source, the Smiler begins to attack
5. **Resolution**: Restore light → Smiler is banished; sustained darkness → Smiler pursues until the character flees or loses consciousness

#### Banishment Conditions
- Any light source restored to "Full Light": The Smiler immediately vanishes
- Almond Water thrown: The Smiler is banished for 1D3+1 rounds (light becomes Dim Light level)
- Fire (oil lamp / torch): The Smiler keeps its distance

#### GM Narrative Suggestion
Smilers are an excellent tool for psychological horror. Don't say directly "you see a Smiler." Instead: "The moment the fluorescent light goes out, you notice a vague silhouette in the dark. Then you see it — a mouth. An oversized, unnatural smile, emitting a faint white glow in the complete darkness. It has no eyes. Only that mouth. It is watching you."

---

### Entity Two: Hound

> *"You won't see the Hounds first. You'll hear them first — the sound of claws scraping concrete floors, coming from the other end of the corridor. That is your only warning."*

#### Basic Stats

| Attribute | Value | Description |
|-----------|-------|-------------|
| Threat Level (TL) | ★★★★ | Extremely dangerous in packs |
| Hit Points (HP) | 20 (single) | Physical damage is effective but requires multiple attacks |
| Defense (DEF) | 13 | Medium-sized predator defense |
| Attack Bonus | +6 (close range) | Claw strike and charge |
| Damage | 1D6+2 claw strike or 1D8 charge | Charge may knock down (Physique DC 13) |
| Perception | 14 (hearing) / 10 (sight) | Relies mainly on hearing and heat sensing |
| Agility | 8 (straight line) / 4 (cornering) | **Extremely fast but clumsy at cornering** |
| Pack Size | 1-5 | Solo patrol or pack hunting |

#### Core Mechanic — Pursuit and Cornering Penalty

| Chase Situation | Hound Agility | Description |
|-----------------|---------------|-------------|
| Straight-line chase | 8 | Hounds have Advantage — they are extremely fast |
| Passing one corner | 4 | Hounds slow down significantly when cornering |
| Passing more than two corners | 3 | Continuous cornering makes Hounds almost unable to follow |
| Narrow space (< 1m wide) | 4 | Narrow passages limit their body size |

#### Encounter Flow

1. **Hearing the Sound**: Claw scraping sounds come from afar (Perception DC 12 to determine number and direction)
2. **Spotted**: The Hound perceives the character's sound or heat source
3. **Pursuit Begins**: Initiate the chase mechanic — starting distance depends on when they are noticed
4. **Using Corners**: Each corner gives the Hound Disadvantage on chase Checks
5. **Resolution**: The character escapes (distance 10) / the Hound loses track (can't hear / smell) / the character is caught up to

#### Banishment Conditions
- Almond Water thrown: The Hound backs off to medium distance, lasting 1D3 rounds
- Loud noise (explosion, metal impact): The Hound is startled, backs off to far distance
- Fire: The Hound stays beyond medium distance, won't approach proactively
- **Cannot kill the whole pack**: Even if you kill one or two, the rest will keep pursuing — and may attract more

#### GM Narrative Suggestion
Hounds are "environmental pressure" rather than a "Combat encounter." Use them to create time pressure — the characters know the Hounds are patrolling, so they must act quickly, stay quiet, and complete their objective before the Hounds discover them.

---

### Entity Three: Partygoer

> *"'Hey! Are you a Wanderer too? We have a safe community on F5, and there's a party tonight! Come join us!' That person was smiling too brightly. You find yourself unable to find a reason to refuse — that smile... makes you want to believe."*

#### Basic Stats

| Attribute | Value | Description |
|-----------|-------|-------------|
| Threat Level (TL) | ★★★★★ | Mechanically the most dangerous — not by combat power, but by deception |
| Hit Points (HP) | 10 (single) | Weak alone, but never appears alone |
| Defense (DEF) | 12 | Human-form defense |
| Attack Bonus | +3 (single) / +6 (group suppression) | Group attack |
| Damage | 1D4 × number of group participants | Group suppression damage increases with number |
| Perception | 16 (social insight) | They can precisely judge your emotional state |
| Agility | 5 | Normal human speed |
| Social Bonus | +8 (when disguised as human) | Extremely strong disguise ability |

#### Core Mechanic — Social Trap Three Stages

**Stage One: Approach**
- The Partygoer appears as a friendly Wanderer
- Behavior is almost perfect — they'll chat about everyday topics, share The Backrooms survival tips, express a longing to go home
- **Subtle Flaws**: The smile never disappears (not even for a second), the eyes never blink, certain words are repeated collectively
- Perception DC 14 to notice the anomaly; Insight DC 16 to confirm the anomaly

**Stage Two: Invitation**
- The Partygoer repeatedly invites the character to the "party"
- After refusal, they show disappointment — then invite again with greater enthusiasm
- Tone remains friendly, but the content becomes increasingly pressuring
- **Weakness**: Sincere expression of negative emotion (sadness, fear) causes the Partygoer to become confused and pause action for about 1 minute

**Stage Three: Closing**
- Once the character accepts or gets close enough to the Partygoer's territory (above F5 on Level 4)
- More Partygoers appear, forming an encirclement
- The character is led to the "party venue" for the conversion ritual
- Escape becomes extremely difficult at this point

#### Partygoer Weaknesses

| Weakness | Effect | Duration |
|----------|--------|----------|
| **Sincere sadness/fear** | The Partygoer is confused, pauses all action | About 1 minute |
| **Lightless + windowless room** | The Partygoer cannot enter | Permanent (limited to that room) |
| **Mirror** | The Partygoer in the mirror has no face — seeing their own reflection causes panic | 1D3 rounds of confusion |
| **Refuse more than three times** | The Partygoer's disguise begins to crack (smile becomes unstable) | Permanent (further social Checks DC -5) |

#### Conversion Ritual

If the character is brought to the "party venue" and forced to participate in the conversion ritual:
- **Sanity Check DC 18**, failure → the character begins to convert into a Partygoer
- The conversion process lasts 1D6 hours
- During conversion, the character remains conscious but gradually loses self-control
- After full conversion, the character becomes an NPC Partygoer (equivalent to character death)

#### GM Narrative Suggestion
Partygoers are the most unsettling Entities in The Backrooms, because they represent "betrayal of trust." Let the players truly believe in them for a while — let them say seemingly sincere words, share seemingly valuable intel. When the truth is revealed, the impact will be stronger. Partygoers are also a good opportunity to show the tragedy of The Backrooms — they were once human.

---

### Entity Four: Skin-Stealer

> *"You traveled with him for three days. He helped you find water, shared food. He was the first good person you met in this hell. Then one night, you noticed his fingers — the thumb was in the wrong place. Your blood froze instantly."*

#### Basic Stats

| Attribute | Value | Description |
|-----------|-------|-------------|
| Threat Level (TL) | ★★★★ | Hidden threat — almost impossible to detect before exposure |
| Hit Points (HP) | 18 | Can be damaged after being exposed |
| Defense (DEF) | 14 | Before exposure, any attack automatically misses (because the character wouldn't want to attack a "human") |
| Attack Bonus | +5 (only when exposed) | Piercing attack |
| Damage | 2D6 Piercing | Extremely dangerous when exposed |
| Perception | 14 | Normal perception |
| Disguise Bonus | +8 (against Insight Checks) | Extremely strong disguise ability |

#### Core Mechanic — Detection Difficulty Ladder

The Skin-Stealer's disguise is not perfect — they have flaws. But these flaws change with the duration of the disguise:

| Disguise Stage | Flaw Type | Detection DC | Description |
|----------------|-----------|--------------|-------------|
| **Just disguised** (< 1 hour) | **Physiological anomaly** | 15 | Number of fingers, joint direction, slight skin texture anomalies |
| **Short time** (1-24 hours) | **Behavioral anomaly** | 17 | Doesn't understand certain human behaviors, delayed reactions |
| **Long time** (1-7 days) | **Linguistic anomaly** | 18 | Language patterns show repetition, unable to understand humor and metaphor |
| **Long term** (> 7 days) | **Subtle anomaly** | 20 | Nearly perfect — only the keenest observer can detect |

#### Encounter Flow

1. **Disguise Stage**: The Skin-Stealer appears as a human Wanderer. They will genuinely help the character, provide valuable information and resources.
2. **Lurking Stage**: The Skin-Stealer learns the character's behavior patterns, memorizes the character's habits and relationships.
3. **Replacement Preparation**: The Skin-Stealer begins to distance the character from others, or tries to isolate the character.
4. **Exposure**: The character successfully detects the anomaly, or the Skin-Stealer's disguise shows an unexpected flaw.
5. **Confrontation**: An exposed Skin-Stealer will attack or flee — they don't want to fight unnecessarily.

#### Behavior After Exposure

| Situation | Skin-Stealer's Response |
|-----------|-------------------------|
| Discovered by the character alone | Attack — tries to eliminate the witness |
| Discovered by multiple people | Flee — seeks the next disguise target |
| Discovered in a stronghold | Flee — the stronghold's armed forces are the real threat |
| Identified but some don't believe it | Deny — uses others' doubt to protect itself |
#### GM Narration Tips
Skin-Stealers are the perfect tool for a long-term story arc. Make one an NPC companion—staying with the players across several sessions and building genuine trust. When the reveal comes, the impact is real. Use the "hindsight" technique: after the reveal, look back at the Skin-Stealer's past behavior to let players realize those "odd moments" were clues all along.

---

### Entity Five: Dullers

> *"You did not see it. You will never see it. But you know it is there. You can feel it—the air behind you grows heavy. Your nape tingles. Something stands behind you, less than an arm's length away, and every instinct in you screams: do not turn around."*

#### Basic Stats

| Attribute | Value | Description |
|-----------|-------|-------------|
| Threat Level (TL) | ★★ (Normal) / ★★★★★ (if you look back) | Does not attack unprovoked, but its gaze effect is devastating |
| Hit Points (HP) | — | Cannot be attacked. They do not exist on the physical plane—or at least cannot be reached by weapons. |
| Defense (DEF) | — | Cannot be attacked |
| Attack Bonus | — | Does not attack |
| Gaze Effect | SP permanently -5 | Irrecoverable—Willpower DC 20 halves it |
| Perception Value | — | Method of perception unknown |
| Agility Value | — | Does not move—they are there when you are not paying attention |

#### Core Mechanic—The Gaze Rule

The Dullers' only mechanic is the "Gaze":

- **Trigger**: The character turns to look back (or sees a Duller via a reflective surface such as a mirror)
- **Effect**: Permanently lose 5 maximum SP (Willpower DC 20 halves it to a permanent -2)
- **Irrecoverable**: These SP never come back. It is not "damage"—it is an "existential reduction"
- **Effect Stacks**: Each gaze upon a Duller stacks the effect

> **🛡 Campaign-Wide Cumulative Cap (to prevent irreversible snowballing)**: Regardless of how many times a character encounters Dullers / Leviathan, the cumulative "permanent maximum SP reduction" must not exceed 8 points (or SAN value ×2, whichever is lower). Any excess is no longer deducted—treated as that character's mind having reached its limit of endurance. This cap protects characters in long campaigns from collapsing due to stacked values.
> **Rare Recovery Path**: The extremely rare "Awakener" story arc can let a character recover up to 3 permanent SP at once (requires the GM to design a dedicated event).

#### Encounter Flow

1. **Sensation**: The character feels someone standing behind them. No check required—the GM describes the feeling directly.
2. **Choice**: The character must decide whether to look back.
3. **Resist**: If the character does not look back—nothing happens. The Duller will eventually vanish (1D6 hours).
4. **Gaze**: If the character looks back—the gaze effect triggers. The GM describes an unforgettable image (but do not describe the Duller's face—because no one has ever seen a Duller's face).

#### How to "Deal With" Dullers

- **Do not look back**: The simplest method. Never look back.
- **Mirror**: Using a mirror lets you see behind without directly gazing—but the image in the mirror still triggers the gaze effect (only the DC drops to 15)
- **Move**: Stand up slowly and walk forward. Never walk backward.
- **Almond Water**: Ineffective. Dullers are unaffected by Almond Water.
- **Conversation**: Ineffective. Dullers do not respond to any form of communication.

#### GM Narration Tips
Dullers are the ultimate embodiment of "things that should not exist" in The Backrooms. When using them, focus on "feeling" rather than "sight." Dullers appear at moments when players might let their guard down—when they have just completed a goal, found a safe corner, or are enjoying a rare respite. Dullers remind players: in The Backrooms, you are never truly safe.

---

## Chapter Four: Complete List of Status Effects

### 4.1 Physical Status

| Status | Trigger Condition | Effect | Removal Method |
|--------|-------------------|--------|----------------|
| **Light Wounds** | HP < 60% | All checks -1 | HP restored above 60% |
| **Heavy Wounds** | HP < 30% | All checks -2, Movement Speed halved | HP restored above 30% |
| **Dying** | HP = 0 | Disadvantage on all checks, Physique DC 15 each round | 3 successful stabilizations (HP returns to 1) |
| **Bleeding** | Edged-weapon damage | Lose 1 HP each round | Bandage or First Aid supplies |
| **Poisoned** | Contact with toxin | 1D4 damage per hour | First Aid supplies or natural recovery (1D3 days) |
| **Exhaustion** | Extreme fatigue | Disadvantage on Physique-related checks | Full rest |
| **Starvation** | Calorie Reserve depleted | Physique -1 per day | Eat |
| **Prone** | Knocked down | Requires 1 AP to stand; melee attacks against you have Advantage | Spend 1 AP to stand |

### 4.2 Mental Status

| Status | Trigger Condition | Effect | Removal Method |
|--------|-------------------|--------|----------------|
| **Unease** | SP < 75% | Disadvantage on Perception and Knowledge checks | SP restored above 75% |
| **Fear** | SP < 50% | Disadvantage on all non-Physique checks + mild hallucinations | SP restored above 50% |
| **Panic** | SP < 25% or failed Willpower | Character loses control of actions—GM decides behavior | 1D6 minutes or assistance from others |
| **Breakdown** | SP = 0 | D10 random behavior (blind fleeing / frozen / hallucinatory attack / hysteria / catatonia) | 1D6 minutes or a major event |
| **Stunned** | Witnessing the unspeakable | Cannot act next turn | Automatically removed at end of turn |

### 4.3 Environmental Status

| Status | Trigger Condition | Effect | Removal Method |
|--------|-------------------|--------|----------------|
| **Darkness** | No light source | Vision-related checks automatically fail (unless a special ability applies) | Restore light source |
| **Concealment** | Hiding behind cover | Attacks against you gain Disadvantage | Leave cover |
| **Detected** | Failed Stealth | Entities know your location | Re-stealth (must break line of sight first) |
| **Concentration** | Using the Concentrate action | Gain Advantage on the next specific check | After using that check or if interrupted |
| **Defending** | Using the Defensive Stance | Attacks against you gain Disadvantage | At the start of your next turn |

---

## Chapter Five: Environmental Hazard Rules

### 5.1 Level-Specific Environmental Hazards

| Level | Environmental Hazard | Mechanic | Damage / Effect |
|-------|----------------------|----------|-----------------|
| **Level 0** | Dark zones | SP loss doubled in darkness; Smilers appearance rate tripled | SP -1/30 min |
| **Level 1** | Shelf collapse | Random event. Physique DC 13 or take 2D6 damage | 2D6 blunt |
| **Level 2** | High-temperature steam | Pipe rupture. Agility DC 12 to dodge | 1D4 burn |
| **Level 2** | Darkness weighting | Additional SP -1/30 min in darkness | SP loss |
| **Level 2** | Heat fatigue | Physique DC 12 every 2 hours | Gain Exhaustion status |
| **Level 4** | Partygoer territory | Encounter rate spikes above F5 | Social traps |
| **Level 11** | Skin-Stealer density | 15% of each social encounter in the city is a Skin-Stealer | Disguise threat |
| **Level 37** | The lure of water | After 30 minutes in water, Willpower DC 10+ | Unwilling to leave the water's surface |
| **Level 37** | Drowning risk | GM secretly tracks time while underwater | 1D4/round |

### 5.2 Illogical Space Effects

| Spatial Anomaly | Trigger | Effect | Response |
|-----------------|---------|--------|----------|
| **Looping Corridor** | Random trigger | Character walks back to where they started. SP -2 | Mark a trail, walk with eyes closed, or wait for the cycle to end |
| **Direction Reversal** | Random trigger | Up/down/left/right swap. Disorientation | Willpower DC 13 to maintain sense of direction |
| **Spatial Compression** | Random trigger | Distances distort. Medium range becomes long range | Spatial Memory DC 14 to adapt |
| **Time Anomaly** | Rare | Experienced time differs from actual time | Willpower DC 15 to stay calm |

### 5.3 Cumulative Stress System (Optional)

During extended exploration, characters accumulate stress:

| Stress Source | Stress Points | Effect (cumulative to) |
|---------------|---------------|------------------------|
| Starvation (per day) | +1 | 3 points → Disadvantage on Physique checks |
| Sleep deprivation (per day) | +2 | 5 points → All checks -1 |
| Dark environment (per hour) | +1 | 8 points → Additional SP -1 per day |
| Loneliness (alone every 6 hours) | +1 | 10 points → Gain a psychological trauma |

Stress is removed by a full rest in a safe zone (each full rest removes 1D6 stress).

---

# Volume Four: Worldbuilding (Full GM Version)

## Chapter One: What Is The Backrooms?

The Backrooms is an infinite-dimensional space existing parallel to the real world. It is not another planet, not hell, nor a dream—it is a "liminal realm" that truly exists but cannot be reached by conventional means.

### The Five Core Laws of The Backrooms

#### Law One: The Non-Euclidean Nature of Space
The space of The Backrooms does not follow Euclidean geometry. A straight corridor may bring you back to where you started. Maps are nearly useless in The Backrooms—or rather, a map is only useful in that instant.

#### Law Two: The Hierarchical Structure of Levels
The Backrooms is organized into multiple "Levels," each an independent dimensional pocket. Levels are connected through unstable exits.

#### Law Three: Noclip—The Only Entrance and Exit
The only way to enter The Backrooms is "Noclipping"—phasing through the "mesh" of reality. Noclip is unpredictable, uncontrollable, and almost always one-way.

#### Law Four: The Almond Water Law
Almond Water is the most important resource in The Backrooms, and exists only within it. This suggests some essential connection between Almond Water and The Backrooms itself.

#### Law Five: The Erosion of Sanity
The Backrooms exerts a continuous corrosive effect on the human mind. A character whose Sanity hits zero does not die—they become "The Lost."

### The Mystery of The Backrooms' Nature (GM-Exclusive)

The nature of The Backrooms is an open mystery. Five possible truths are offered below; the GM may choose one or create their own version:

| Hypothesis | Core Concept | Impact on the Story |
|------------|--------------|---------------------|
| **Manifestation of the Collective Unconscious** | The Backrooms is the physical embodiment of humanity's fear of "forgotten spaces" | Characters may influence The Backrooms by changing collective consciousness |
| **A Scar of Reality** | The Backrooms is the universe's "debug zone"—collecting physical errors | Noclip events can be predicted in reality |
| **Heritage of an Ancient Civilization** | The Backrooms was built by a primordial super-civilization | Truths are hidden in ruins and ancient devices |
| **A Realm Between Life and Death** | The Backrooms is the physical expression of near-death experiences | Every character is in a near-death state in reality |
| **Nothing at All** | The Backrooms has no deeper meaning—it simply exists | Characters must create their own meaning |

---

## Chapter Two: Complete Data on Fifteen Levels

> **The following is the full GM data for each Level. Players should learn this information only through exploration and experience.**

### Level 0 — "The Lobby"

**Basic Information**:
- Type: Yellow office cubicles
- Spatial Stability: Mildly unstable (space shifts slightly)
- Primary Threats: Isolation (SP erosion), occasional Hounds
- Unique Resources: Basic Almond Water supply points

**Spatial Structure**: Endlessly extending office cubicles, yellow wallpaper, buzzing fluorescent lights, damp beige carpet.

**Physical Rules**:
- Areas you leave may have changed layout when you return
- The probability of two people naturally meeting in Level 0 is near zero
- Areas where fluorescent lights are completely out are extremely dangerous
- Sound travel distance is not fixed

**Entity Distribution**: Hounds (dark zones, possibly encountered once per 8-12 zones), Dullers (triggered by prolonged stay), Skin-Stealers (extremely rare).

**Resource Locations**: Almond Water (damp corners, 1 bottle found per 5-8 zones), office supplies (abundant but limited use).

**Special Rule—"The Initial Gift"**: Every new character is certain to find a bottle of Almond Water within five cubicles of their starting position.

**Exits and Entrances**:
- Entry: About 70% of noclip events arrive at Level 0
- To Level 1: Unmarked fire door
- To Level 2: Downward staircase in dark zones
- To Level 4: Still-functioning elevator (extremely rare)

**GM-Usable Elements**:
- "First Night" phenomenon: The character has a warm memory dream (restores 1D4 SP)—only once
- Wall messages left by predecessors (can serve as worldbuilding or traps)
- Fluorescent lights flicker in sync—"Level 0 is breathing"

---

### Level 1 — "The Warehouse"

**Basic Information**:
- Type: Abandoned warehouse / industrial space
- Spatial Stability: Moderate (most zones fixed)
- Primary Threats: Smilers (dark corners), faction competition
- Unique Resources: Abundant tools and materials

**Spatial Structure**: Concrete columns, metal shelving, loading docks, office mezzanine, mechanical rooms.

**Physical Rules**:
- More stable than Level 0
- Some supplies reset weekly (rare phenomenon)
- Noise conduction amplified—distant sounds unusually clear

**Entity Distribution**: Smilers (common in dark areas), Hounds (deep in shelving, more aggressive than in Level 0), human NPCs (M.E.G. patrol zones).

**Resource Locations**: Tools and parts (abundant in mechanical rooms), Almond Water (moderate in loading-dock crates), canned food (rare in containers but in large quantities).

**Key Location—M.E.G. Outpost "Cornerstone"**: Garrisoned by 15-25 people, the main contact point for newcomers. Provides intel, trade, and medical care.

**Exits and Entrances**:
- To Level 0: Yellow-toned door
- To Level 2: Downward maintenance staircase deep in the mechanical room
- To Level 4: Powered elevator in the office mezzanine
- To Level 11: Perimeter loading door (extremely rare)

**GM-Usable Elements**:
- Random shelf-collapse event (noise cover or threat warning)
- "The Gramophone": Plays 1940s music—approaching restores 1D3 SP

---

### Level 2 — "The Pipes"

**Basic Information**:
- Type: Dim pipe maze
- Spatial Stability: Moderate (three-dimensional maze)
- Primary Threats: Hound dens, maze-like passages, high temperature
- Unique Resources: Advanced Almond Water variants

**Spatial Structure**: A three-dimensional maze of concrete and metal pipes. Narrow corridors (1-2m wide), low ceilings (2-2.5m), high temperature (30-35°C).

**Physical Rules**:
- 90% of zones are in darkness or near-darkness
- Darkness Weighting Rule: Additional SP -1/30 min in darkness
- Sound absorption—travel distance only 50%
- Heat fatigue risk

**Entity Distribution**: Hounds (high—this is their main habitat, in packs of 2-5), Smilers (high), Pipe Worms (rare, non-aggressive but cause burns on contact), The Lost (rare).

**Resource Locations**:
- Almond Water (standard): Stagnant water by pipe valves (rare)
- Almond Water (variant): Pipe seepage (moderate, requires identification)
- Scrap metal: Abundant (crafting material)
- Batteries: Beside emergency lights (rare but extremely precious)

**Variant Almond Water System (Level 2 Exclusive)**:
| D100 | Variant | Effect |
|------|---------|--------|
| 1-40 | Ordinary Almond Water | Standard effect |
| 41-65 | Concentrated Almond Water | Double effect + 1 hour of darkvision |
| 66-85 | Contaminated Almond Water | SP loss doubled for 1D4 hours, then restores 1D6 SP |
| 86-95 | Pipe Venom | Physique DC 15 or else 1D4 Physique damage |
| 96-100 | "The Void" | SP -2, but gain a truth clue |

**Exits and Entrances**:
- To Level 1: Upward maintenance staircase
- To Level 4: A door with faint light leaking through
- To Level 11: Narrow passage → city sewer
- To the Deep Levels: Continue downward (GM may introduce original levels)

**GM-Usable Elements**:
- "The Heart of the Den": A giant Hound den at the deepest point (no one who enters comes out alive)
- Red valve network—turning them changes pipe flow; the correct combination may trigger a special event

---
### Level 4 —— "Office"

**Basic Information**:
- Type: Abandoned modern office building
- Spatial Stability: High
- Primary Threat: Partygoers
- Unique Resources: Office equipment can be dismantled

**Spatial Structure**: A modern office building, floors B2 to F8. White walls, gray carpet, meeting rooms, a pantry/break room, and a server room.

**Physical Rules**:
- Time Locked: It is always 7:42 PM, "after work."
- Electrical Anomalies: Electronic devices power on by themselves when no one is watching.
- "Quitting Bell": Rings once every 6 hours; for the following 10 minutes, Entity activity patterns change.

**Entity Distribution**: Partygoers (high frequency above F5), Smilers (moderate in unlit corridors), office Entity "The Clerk" (rare, a faceless humanoid that types repetitively), Hounds (uncommon in the B1-B2 parking garage).

**Resource Locations**: Office equipment parts (abundant), Almond Water (moderate in the pantry), document records (abundant in the archive room), batteries (concentrated but uncommon in the server room).

**Entrances & Exits**:
- To Level 0: F1 revolving door
- To Level 11: F8 fire escape
- To Level 37: B2 flooded area

**GM-Usable Elements**:
- "The Last Employee": A special Clerk Entity in a corner office on F3 — occasionally types out meaningful text
- Origin of the Partygoers: Digital records in the F5 server room
- Mirror Room (F7): Partygoers do not enter; if you stay longer than 10 minutes, your reflection in the mirror begins to smile

---

### Level 11 —— "Boundless City"

**Basic Information**:
- Type: Infinite modern city
- Spatial Stability: High
- Primary Threat: Getting lost, Skin-Stealers
- Unique Resources: Outpost trading

**Spatial Structure**: An infinitely extending city with mixed architectural styles. 70% of buildings are empty inside, 25% have basic structure, 5% are complete.

**Physical Rules**:
- One of the most stable known Levels
- The sky is fake (perpetually overcast, clouds are motionless)
- A "reset" once every 30 days: building interiors re-randomize (occupied buildings are unaffected)

**Entity Distribution**: Skin-Stealers (high — this is their main hunting ground), Smilers (moderate in underground parking), Hounds (uncommon at the city edge), human NPCs (high — the most densely populated Level by Wanderers).

**Resource Locations**: Nearly all resources can be obtained through trade. Natural generation is scarce.

**Important Locations**: BNTG trade center, M.E.G. city outpost, multiple Independent Wanderer communities.

**Entrances & Exits**:
- To many Levels — Level 11 is the transportation hub of The Backrooms
- To Level 37: Diving in a public swimming pool
- To the Deep Layers: A downward staircase at the subway station entrance

**GM-Usable Elements**:
- An exception to the "31st Day Reset" — buildings that should not exist appear
- The dark side of BNTG's monopoly
- The city is the main venue for social encounters and trade

---

### Level 37 —— "Warm Water Pool"

**Basic Information**:
- Type: Warm water pool facility
- Spatial Stability: High (fixed space) but mentally unstable (the allure of the water)
- Primary Threat: Unknown underwater Entities, hypoxia, the hypnotic effect of the water
- Unique Resources: Abundant water (extremely scarce on other Levels)

**Spatial Structure**: Tile corridors connect dozens of pools. Water temperature is a constant 32°C. The bottoms of some pools are far deeper than they appear, with underwater passageways.

**Physical Rules**:
- The allure of the water: Staying in the water for more than 30 minutes requires a Willpower Check, or the character will not want to leave
- Hypoxia suppression: Characters underwater do not feel a strong sense of suffocation — the GM must secretly track underwater time
- Abnormal underwater sound conduction — sounds from other pools can be heard (are they real?)

**Entity Distribution**: Underwater Entity "The Swimmer" (moderate in the deep areas of large pools, grabs ankles to try to keep people there), The Lost (uncommon by the children's pool), "The Lifeguard" (extremely rare, sits unmoving on a high chair — if you drown, drags you into the depths).

**Resource Locations**: Water (extremely abundant in all pools but requires containers), Almond Water (surface film, one patch every 3-5 pools), relics left by The Lost (uncommon by the poolside).

**Entrances & Exits**:
- To Level 4: A dry, tiled-free corridor
- To Level 11: Climb out from the other side of a specific pool
- To the Deep Layers: A downward underwater tunnel at the very deepest point

**GM-Usable Elements**:
- "The Thing at the Bottom of the Pool": A huge, motionless black shadow at the bottom of the deepest waters
- The legend of the "Third Exit": An underwater passage in a cold-water pool leads to reality
- The "Water Mirror" phenomenon: The reflection on the water's surface shows a parallel version of yourself
- The Hermit — a "Deep Recorder" who has lived here for three years

---

### Level 3 —— "Power Station" (Scenario Extension)

**Basic Information**:
- Type: Abandoned power facility — exposed wiring, malfunctioning equipment, huge machine rooms
- Spatial Stability: Moderate
- Primary Threat: "The Electrician" Entity (patrols and attacks with electric shocks)
- Unique Resources: Spare batteries, tool parts

**Spatial Structure**: Huge machine rooms, three generator sets, a control room, and an inspection hatch leading downward.

**Physical Rules**:
- Electric shock risk: In areas with exposed wiring, pass an Agility DC 12 or take 1D6 electric shock damage (SP -1).
- Some areas have flickering lights (flickering lights affect Stealth and Search).

**Entity Distribution**: The Electrician (1-2 patrolling), occasional Hounds (following in from Level 2).

**Resource Locations**: Batteries (abundant in the machine room), tool parts (control room), Almond Water (sealed cabinet).

**Core Mechanic — Restart the Three Generator Sets**: The 3 generator sets must be restarted in sequence (Crafting DC 14 ×3 or an equivalent skill). Once all are restarted, the inspection hatch opens.

**Entrances & Exits**: In: Level 2 maintenance door; Out: Inspection hatch → Level 4.

**GM-Usable Elements**: The Electrician can be temporarily disabled by cutting the main power (1D6 turns); a previous occupant's notes record the correct restart sequence.

---

### Level 5 —— "Horror Hotel" (Scenario Extension)

**Basic Information**:
- Type: Infinite Victorian-style hotel — red carpets, crystal chandeliers
- Spatial Stability: Low (room layouts change)
- Primary Threat: "The Servant" (faceless waiter), portrait Entities
- Unique Danger: Empty chairs in the banquet hall (sitting down = permanent imprisonment)

**Spatial Structure**: Endless red-carpet corridors, hundreds of guest rooms, a central banquet hall, a hidden back door behind the curtain.

**Physical Rules**:
- Each room door is engraved with the name of a Lost one.
- The eyes in the portraits move (perceived with Perception DC 14; upon noticing, SP -1D3).
- The empty chairs in the banquet hall: whoever sits is permanently imprisoned on this Level (character ends).

**Entity Distribution**: The Servant (faceless waiter, guides characters toward the banquet hall), portrait Entities (mental attacks).

**Resource Locations**: Occasionally supplies inside guest rooms; banquet hall food (looks normal, eating it costs SP -1).

**Entrances & Exits**: In: Level 4 golden elevator; Out: Back door behind the banquet hall curtain → Level 6; or sit on a chair (character ends).

**GM-Usable Elements**: The waiter accurately speaks the character's name; behind every door may be an ordinary room or an endless maze.

---

### Level 6 —— "Blackout" (Scenario Extension)

**Basic Information**:
- Type: Absolutely dark, damp corridors — light sources are devoured
- Spatial Stability: Low
- Primary Threat: "Shadows" Entity (touch → shadow permanently disappears)
- Special Rule: Upon entry, all light sources fail

**Spatial Structure**: Endless damp corridors, occasional rooms, structurally fragile floors.

**Physical Rules**:
- Upon entry, light sources fail (flashlights / glow sticks all go out).
- SP -1 every 15 minutes.
- Can only navigate by hearing (Perception DC 15 to determine direction).

**Entity Distribution**: Shadows (in groups, moving at the edges; touching causes the character to lose their shadow — Agility-related Checks -1, resist with Willpower DC 15).

**Resource Locations**: Extremely scarce. Occasionally an emergency light that still has power is found (brief illumination).

**Entrances & Exits**: Floor structure collapses and caves in → Level 7.

**GM-Usable Elements**: Sound-navigation actions (wall-tapping echoes); the rustling of moving Shadows sounds from behind.

---

### Level 7 —— "Thalassophobia" (Scenario Extension)

**Basic Information**:
- Type: A research base flooded by seawater
- Spatial Stability: High (fixed space) but dangerous underwater
- Primary Threat: "Leviathan" — a gigantic underwater creature
- Resources: Diving equipment (30 minutes of oxygen)

**Spatial Structure**: Flooded corridors, laboratories, a drainage pipe system.

**Physical Rules**:
- Underwater hypoxia rules (GM secretly tracks underwater time, 1D4/turn).
- The hypnotic effect of the water (Willpower DC 10, or the character will not want to leave the water surface).

**Entity Distribution**: Leviathan (a gigantic underwater creature, must not be looked at directly — direct eye contact permanently reduces SP by 3, halved to -1 with Willpower DC 20; extremely difficult to kill). Both are subject to the "campaign-wide permanent SP reduction cap" (see the Dullers section).

**Resource Locations**: Diving equipment, research supplies, sealed Almond Water (laboratories).

**Entrances & Exits**: Drainage pipes (surface to the water) → Level 8.

**GM-Usable Elements**: The gigantic shadow of the Leviathan swimming in the depths; the reflection on the water's surface shows a distorted version of yourself.

---

### Level 8 —— "Cave System" (Scenario Extension)

**Basic Information**:
- Type: Fluorescent fungus caves — glowing spores form a "starry sky"
- Spatial Stability: Moderate (three-dimensional caves)
- Primary Threat: "Cave Dwellers" (afraid of light, in groups)
- Resources: Edible glowing mushrooms

**Spatial Structure**: Giant caves, fluorescent fungus forests, tunnel networks.

**Physical Rules**:
- Glowing spores provide faint illumination (not an Entity light source, Smilers may still appear in the darkest spots).
- Some areas have toxic spores (Knowledge DC 14 to distinguish edible / toxic).

**Entity Distribution**: Cave Dwellers (afraid of light, act in groups; recoil from light; melee 1D4 physical).

**Resource Locations**: Glowing mushrooms (eating restores Calories / a small amount of SP), minerals.

**Entrances & Exits**: Tunnels → Level 9.

**GM-Usable Elements**: Cave Dweller nest (in the depths); the low hum of mineral resonance.

---

### Level 9 —— "Suburb" (Scenario Extension)

**Basic Information**:
- Type: Endless suburb in perpetual rainy night — identical houses
- Spatial Stability: Low (houses repeat hypnotically)
- Primary Threat: "The Thing Behind the Window" (lures you into houses)
- Rule: Do not enter any house

**Spatial Structure**: Endless streets, identical houses, streetlight sequences.

**Physical Rules**:
- Navigate by following the streetlight flicker sequence (Perception DC 15).
- Entering any house = trapped by The Thing Behind the Window (SP continuously -1, must pass Willpower DC 18 to leave).

**Entity Distribution**: The Thing Behind the Window (peers behind every window, lures characters into houses).

**Resource Locations**: Occasionally supplies inside houses, but obtaining them is extremely dangerous.

**Entrances & Exits**: Follow the streetlight sequence to its end → Level 10.

**GM-Usable Elements**: The streetlight sequence puzzle; the hypnotic feeling brought by identical houses.

---

### Level 10 —— "Wheat Field" (Scenario Extension)

**Basic Information**:
- Type: Boundless golden wheat field — a false idyll
- Spatial Stability: Low (paths change)
- Primary Threat: Moving scarecrows
- Navigation: Paths change (Spatial Memory DC 16)

**Spatial Structure**: Endless wheat field, slowly moving scarecrows, a farmhouse on the horizon.

**Physical Rules**:
- Paths rearrange every hour (loss of sense of direction).
- Scarecrows slowly move closer (large gatherings form a maze).

**Entity Distribution**: Scarecrows (not hostile but SP -1 when they approach; they do not attack, but block the way forward).

**Resource Locations**: Occasionally wild fruit at the edge of the wheat field.

**Entrances & Exits**: Find the asphalt road → Level 11.

**GM-Usable Elements**: The gaze of the scarecrows; the farmhouse on the horizon (entering = a trap).

---
### Level ! — "Run If You Don't Want to Die!" (Scenario Expansion)

**Basic Information**:
- Type: Ten-kilometer hospital-style corridor — red alert + piercing sirens
- Spatial Stability: Fixed (straight long hallway)
- Primary Threat: A mixed pursuit by all common Entities
- Core Rule: The only level with a forced death risk

**Spatial Structure**: Endless hospital corridors, occasional supply rooms, and the EXIT door at the end.

**Physical Rules**:
- Every 1 kilometer advanced requires a Physique check (Physique / Agility DC escalates: 10→20). **Failure**: chase distance -1 (the group behind closes in), or 1D4 environmental damage (tripping / cut by broken glass), at the GM's discretion.
- At the 9th kilometer, a Willpower DC 18 (to avoid panic). **Failure**: fall into panic for 1 round (unable to advance, chase distance -2).
- Swarms of Entities chase from behind (chase distance system).

**Entity Distribution**: Mixed (Hounds / Smilers / Partygoers, etc.) chasing in packs.

**Resource Locations**: Supply rooms along the way (Almond Water, bandages).

**Entrances/Exits**: EXIT door → white space (the ending Level). Each character may enter only once; being caught = character death.

**GM Usable Elements**: Time pressure; distance counter (kilometer markers); red-alert visual and auditory descriptions.

---

## Chapter Three: The Four Factions

### M.E.G. — Major Explorer Group

| Item | Content |
|------|---------|
| Core Motivation | Protect newcomers, explore and record, find exits, maintain civilization |
| Organizational Structure | Three-person committee → Explorers / Recorders / Suppliers / Guardians |
| Attitude Toward Players | Welcoming but not charitable — contributions are required to keep receiving support |

**Relationship Tiers**:
| Tier | Requirement | Benefit |
|------|-------------|---------|
| 0 Stranger | First contact | Free newcomer starter pack |
| 1 Friend | 1 mission | Purchase basic supplies, use rest points |
| 2 Ally | 3 missions + 50 contribution points | Intelligence map, high-reward missions |
| 3 Member | Sworn in + 5 missions | Internal intelligence, equipment support |
| 4 Senior Member | 200 contribution points + deep-level exploration | Squad resources, participation in decisions (about 8–10 standard missions) |
| 5 Committee Candidate | Special achievement | Core secrets |

### BNTG — Backrooms Nonprofit Trade Group

| Item | Content |
|------|---------|
| Core Motivation | Profit, supply-chain control, becoming an indispensable force |
| Organizational Structure | Seven-person Trade Council → Caravan Leader → Trader → Scavenger → Guard |
| Attitude Toward Players | Friendly to all with trading value — asks no questions about morality |

**Credit System**: BNTG offers credit loans. High interest rates, severe consequences for default.

**Relationship Tiers**:
| Tier | Requirement | Benefit |
|------|-------------|---------|
| 0 Passerby | No trade record | Basic trading rights |
| 1 Customer | 100 credit points | Commission to find specific items |
| 2 Regular | 500 credit points | 5% discount, intelligence trading |
| 3 Partner | 2000 credit points or 3 contracted missions | 10% discount, credit loans |
| 4 VIP | 3000 credit points | 15% discount, rare items (about 30–40 trade commissions) |
| 5 Potential Council Candidate | Special achievement | Influence trade policy |

### Independent Wanderers — The Silent Majority

No organizational structure. Each independent Wanderer has their own story. The GM may use 1D6 to determine attitude (1-2 hostile, 3-4 neutral, 5-6 friendly).

**Notable Independent Wanderers (NPC Templates)**:
- **Old Zhao** (Level 1): Former construction worker — teaches tool crafting
- **"The Cartographer" Mira** (Level 11): Former librarian — trades map fragments
- **"The Mute"** (Level 2): Communicates by tapping pipes — can lead passage through the pipe network
- **"The Doctor" Wu** (roams various Levels): Former nurse — provides medical services

### The Lost — Humans Whose Sanity Has Hit Zero

Not a Faction, but a state. The Lost are former humans whose Sanity has hit zero — existing between human and Entity.

**How the GM Uses Them**:
- Atmosphere element — reminds players of the fragility of Sanity
- Source of information — fragmented useful intel may hide within their mutterings
- Potential for recovery (extremely rare — an "Awoken One" brings back deep secrets)

---

### Faction Reputation Earning Rate

Faction relationship tiers (see each faction's relationship table) must be accumulated through "contribution points" (M.E.G.) or "credit points" (BNTG). The following are reference earning rates the GM may use:

| Action | M.E.G. Contribution Points | BNTG Credit Points |
|--------|----------------------------|--------------------|
| Complete a patrol / escort mission | +15 ~ +30 | — |
| Provide valuable Level intelligence | +5 ~ +10 | Commission reward +50 ~ +200 |
| Rescue / heal outpost members | +15 | — |
| Deliver trade-commission items | — | +30 ~ +100 |
| Assist in exploring a new Level and report back | +20 | — |
| Sell rare resources (Almond Water variants, etc.) | — | Market price ×1.5 |

**Rate Suggestion**: Generally, players need about 3-5 standard missions to rise from "Stranger" to "Ally / Regular." The GM may speed up or slow down according to campaign Pacing, but avoid letting reputation become a number farm — it should serve the story, not replace exploration.

### Resource Economy Baseline (GM Reference)

**Typical Session Resource Settlement Table** (baseline: 3–4 hours, single-Level exploration):

| Session Type | Almond Water Found | Almond Water Consumed | Net Balance |
|--------------|--------------------|-----------------------|-------------|
| Exploration type (Level 0 / 2) | 3–6 units | 2–4 (healing + banishment + minor trading) | +1–2 |
| Combat-intensive type | 1–3 units | 3–5 (mainly healing) | -1–3 (resupply needed) |
| Trading type (BNTG outpost) | Depends on commission | 0–1 | Credit points accumulate |

Note: Almond Water mainly comes from "scavenging" rather than "buying." Generally a session's net balance is low, and players should not expect steady accumulation — this fits the "survive, not get rich" design. If a session's net balance exceeds +5, the GM should appropriately raise the subsequent Level's scavenging DC or scarcity.

**Faction Currency and Supply Exchange**: M.E.G. contribution points and BNTG credit points **cannot be directly exchanged for Almond Water**, but can offset supplies through outpost benefits — for example, Ally tier may use rest points for free, VIP tier may buy supplies directly from BNTG caravans with credit points (priced equivalently to Almond Water). In short: faction currency is "permissions and discounts," Almond Water is "circulating currency," and the two are complementary rather than substitutive.

---

# Volume Five: GM Toolbox

## Chapter One: Atmosphere Building

### 1.1 Creating a Sense of Loneliness

- **Use of Silence**: Deliberately leave long stretches of silence while players explore
- **Oppressive Space**: Describe the length of corridors, the lowness of ceilings, the texture of walls
- **Blurred Time**: Never tell players "X hours have passed" — instead describe physical sensations
- **Glimmers in Loneliness**: Periodically insert small warmth (predecessors' messages, a bottle of Almond Water), then let loneliness descend again

### 1.2 The Five-Senses Rule of Environmental Narration

| Sense | How to Use | Example |
|-------|-----------|---------|
| Sight | Describe the quality of light rather than the objects themselves | "The yellow-green glow of the fluorescent lights makes everything look sick" |
| Hearing | Use ambient sound to hint at threat or safety | "The hum of the fluorescent lights is your background music — when it stops, your blood stops too" |
| Touch | Let players feel the physicality of the environment | "The carpet is damp enough to seep through your socks" |
| Smell | Hint at the environment's history and anomalies | "A musty smell mixed with an unidentifiable sweetness — your nape tingles" |
| Taste | Use sparingly, at key moments | "Almond Water slides down your throat, leaving a faint sweetness that does not belong to Earth" |

### 1.3 Staged Revelation

Do not give a full description the moment players enter a new area:
1. **First Glance**: Light, dominant color, the basic shape of the space
2. **Second Glance**: Details — marks on the walls, condition of the floor, anomalous sounds
3. **Third Glance**: Potential threats or opportunities — things in the shadows, items in the corners

---

## Chapter Two: Pacing Control

### 2.1 The Golden Cycle

```
Explore (40%) → Discovery (15%) → Crisis (25%) → Respite (20%)
    ↑                                            ↓
    ←────────────── Loop ───────────────────────┘
```

### 2.2 Pacing Warnings

| Player Behavior | Problem | Adjustment |
|-----------------|---------|------------|
| Frequent distraction / joking | Tension too low | Trigger a discovery or minor crisis |
| Decision paralysis | Tension too high | Provide a respite opportunity or lower difficulty |
| Ignoring environmental descriptions | Exploration too long | Accelerate toward the discovery / crisis phase |
| Avoiding all risk | Crisis penalty too heavy | Show manageable danger |

---

## Chapter Three: Horror Narration Guide

### 3.1 Three Sources of Horror

1. **The Unknown**: Not knowing whether something is around the corner — and if so, what it is
2. **The Endless**: Corridors that never end — infinity itself is terrifying
3. **The Illogical**: Rooms that should not exist — their existence challenges the sense of reality

### 3.2 The Five Levels of Horror Narration

| Level | Technique | Example |
|-------|-----------|---------|
| 1. Unease | Describe slight anomalies | "The hum of the fluorescent lights is a pitch higher than before — you're not quite sure" |
| 2. Fear | Hint at a clear threat | "You smell it — a damp, animal odor. There are Hounds nearby." |
| 3. Dread | Let players imagine it themselves | "A dragging sound comes from the other side of the partition. Then it stops." |
| 4. Shock | Reveal a dreadful truth | "Those eyes are on the ceiling. That thing is on the ceiling." |
| 5. Existential Dread | Challenge the understanding of reality | "On the back of the photo it says: 'You never left. This is the real one.'" |

### 3.3 Sanity as a Narrative Tool

| SP Range | Narrative Impact |
|----------|------------------|
| 100-76% | Descriptions are accurate and reliable |
| 75-51% | Add one unreliable detail to descriptions |
| 50-26% | Clear hallucination elements — the GM describes what the "character sees" (without telling the player whether it is real) |
| 25-1% | The line between reality and hallucination blurs — the GM may mix true and false information |
| 0 | Character becomes The Lost — appears as an NPC in future stories |

---

## Chapter Four: Solo Mode Support

### 4.1 "Soliloquy Companion" Mechanic

| Soliloquy Type | Trigger | Effect |
|----------------|---------|--------|
| Talking to oneself | Player freely, or GM prompts after long silence | Player organizes thoughts; GM may grant a "flash of inspiration" |
| Recording journal | Discover recording equipment | Restore 1 SP (once per 24 hours) |
| Letter / notes | Find paper and pen | Restore 1D2 SP |
| Conversing with an encountered person | Meet an NPC | Restore 1D3 SP, may provide plot clues |
| Talking to objects | Character develops this on their own | Early sign of declining Sanity but also a coping mechanism |

### 4.2 Solo Mode Difficulty Adjustments

| Adjustment Item | Suggestion |
|-----------------|-----------|
| Resource generation rate | Increase by 25-50% |
| Entity encounter frequency | Unchanged |
| SP recovery opportunities | Increase (Soliloquy mechanic) |
| Combat difficulty | Reduce Entity count, maintain single-target threat |
| NPC importance | Greatly increased — make NPCs richer and more storied |

---

## Chapter Five: The Fun of Failure

Death is not the only failure. In Backrooms Walker TRPG:

| Failure Type | Narrative Consequence | Game Consequence |
|--------------|----------------------|------------------|
| Lost | Lose orientation on the current Level | Consume more resources, SP drops |
| Resource Depletion | Hunger / thirst / darkness | Physical state declines, decision-making impaired |
| Partial SP Collapse | Brief mental breakdown | Temporarily lose character control, gain permanent psychological trauma |
| Captured by Entity | Dragged away / trapped | New escape storyline |
| Lose important item | Emotional loss | Personalized failure |
| Lose NPC ally | Sacrifice / disappearance / betrayal | Emotional shock + loss of service |
| Death | Character vanishes forever | Story ends (kept as the most extreme consequence) |

---

## Chapter Six: Improvisation Guide

### 6.1 Core Principles

**"Yes, and…"** — Never say "no, you can't do that." Instead: "Yes, you can try — and because you are in The Backrooms, the result may not be what you imagined."

### 6.2 Emergency Encounter Generator

When players walk into an unprepared area:

1. **Roll 1D6 to determine area type**: 1-dead end, 2-empty room, 3-resource point, 4-danger zone, 5-exit clue, 6-unexpected discovery
2. **Roll 1D6 to determine current state**: 1-3 safe, 4-5 signs of threat, 6 direct encounter
3. **Adjust by Level**: dark Levels raise threat, civilized Levels raise social encounters

---
# Volume VI: Scenario Framework (v1.1 Extended Edition — 8 Scenarios, 15+ Levels)

> The following is a GM quick-reference framework for the 8 scenarios. For full scenario narratives, see the .md files in the `scenarios/` directory.
> For structured data, see the corresponding .yaml files.

## Scenario Overview

| # | Scenario | Level | Milestone | Duration | Core Experience |
|---|---------|-------|-----------|----------|-----------------|
| S1 | Awakening | Level 0 | 1 | 4-6h | Lost, First Discovery, First Threat |
| S2 | Traverse | Level 1→2→3 | 2-3 | 6-9h | Outpost preparation, Pipe Hell, Power Station Maze |
| S3 | The Hotel | Level 4→5 | 3-4 | 7-10h | Partygoer trap, Horror Hotel, Banquet Hall choice |
| S4 | Blackout | Level 6→7 | 4-5 | 6-9h | Absolute Darkness, Deep Sea Dread, Leviathan |
| S5 | Trek | Level 8→9→10 | 5-6 | 8-12h | Glowing Caves, Eternal-Night Suburb, Golden Wheat Field |
| S6 | Respite | Level 11 | 6-7 | 7-10h | Urban Civilization, Trade & Socializing, Skin-Stealer Investigation |
| S7 | Sprint | Level ! | 7-8 | 4-6h | Ten-kilometer life-or-death sprint — the only mandatory death risk |
| S8 | The Way Home | Ending Level | 8 | 2-3h | Ultimate choice: return to the Frontrooms or stay in The Backrooms |

## S1: Awakening — GM Notes
- **Level 0**: The initial gift mechanic ensures survival. The spreading darkness is the first threat. Old Zhao's message establishes the sense of world.
- Key checks: Keep Calm DC 10, Observe DC 8, Stealth DC 12, Willpower DC 14.
- Ending: M.E.G. rookie care package → leads to Level 1.

## S2: Traverse — GM Notes
- **Level 1**: M.E.G. outpost — trade, recruit NPC companions.
- **Level 2**: 35°C+ darkness + Hound nest. Predecessors' shelter (Wang Jing's diary). The mystery of the red valve room.
- **Level 3**: Power Station — restart 3 generator units to open the maintenance door. "The Electrician" Entity (2D6 electric shock).
- Ending: Maintenance door → Level 4.

## S3: The Hotel — GM Notes
- **Level 4**: Partygoer trap + escape. Mirror Room (F7) and the lightless room are safe zones.
- **Level 5**: Horror Hotel — the Waiter speaks the character's name. Every door is engraved with the name of a Lost. The empty chairs in the banquet hall = permanent imprisonment.
- Ending: Back door → Level 6. Or sit in a chair (character permanently ends).

## S4: Blackout — GM Notes
- **Level 6**: Light sources are devoured — SP -1 every 15 minutes. Sound navigation. Shadows Entity (shadow permanently disappears).
- **Level 7**: Submerged research base. Diving equipment (30 minutes of oxygen). Leviathan — must not be looked at directly (SP permanently -3).
- Ending: Drainage pipe → Level 8.

## S5: Trek — GM Notes
- **Level 8**: Glowing caves + fungal forest. Cave Dwellers (fear light). Edible/toxic mushrooms.
- **Level 9**: Endless suburb in the eternal-night rain. Do not enter any house. Navigate by following the streetlight sequence.
- **Level 10**: Golden wheat field. Moving scarecrows. The path changes.
- Ending: Asphalt road → Level 11.

## S6: Respite — GM Notes
- **Level 11**: BNTG trade, M.E.G. outpost. Old Zhao appears in person. Social and trade scenes dominate.
- Skin-Stealer investigation: disappearance cases → infiltrate community → find the impostor.
- Gather intel on Level !: elevator in the abandoned hospital basement.
- Ending: Enter the Level ! entrance.

## S7: Sprint — GM Notes
- **Level !**: 10-kilometer hospital corridor. Red alert + piercing sirens. Swarms of Entities in pursuit.
- A Physique check once per kilometer (Physique/Agility DC escalating). Willpower DC 18 at the 9th kilometer.
- **The only level with mandatory death risk** — caught = character death. Each character may enter only once.
- Ending: EXIT door → white space.

## S8: The Way Home — GM Notes
- White space — no time, no threats. Review the key moments of the entire Campaign.
- Two doors: left = the Frontrooms (go home), right = The Backrooms (stay and become a guide).
- No DC, no checks. Pure character choice.
- Both endings have full narrative descriptions. Make the players' choices meaningful.

---

# Volume VII: Optional Rules & Variants

## Chapter 1: Multiplayer Mode Adjustments

| Adjustment | Description |
|-----------|-------------|
| Team Resource Pool | Shareable food, water, Almond Water |
| Role Division | Encourage Scout/Negotiator/Technician/Guardian divisions |
| Social Aspect of SP | Team interaction can restore extra SP |
| Group Decision | Use voting or persuasion mechanics when there is disagreement |
| Resource Generation Rate | 2-3 players: 90%; 4-5 players: 80%; 6+: 70% |

## Chapter 2: Hardcore Survival Mode

| Additional Mechanic | Description |
|---------------------|-------------|
| Detailed Hunger Tracking | Measured in hours |
| Wound Infection | Open wounds require a Physique check |
| Fatigue Level | Sleep quality and fatigue accumulation |
| Permanent Damage | Severe injury may lead to permanent effects |
| Almond Water Tolerance | Diminishing returns on consecutive use |

## Chapter 3: Narrative-Focused Mode

- Simplified checks (success / success-but / failure three-outcome system)
- Fate points (1-2 per session, can reroll or add environmental elements)
- Narrative combat (replace precise HP with advantage/disadvantage tracks)
- Character-driven plot (define core drives)
- Collaborative world-building (players participate in describing the environment)

## Chapter 4: Trust & Betrayal (Multiplayer Mode)

| Trust Level | Effect |
|-------------|--------|
| Complete Trust | Automatic assistance, shared resources |
| Trust | Can request assistance, share partial resources |
| Neutral | Each acts independently, transactional interaction |
| Suspicion | Assistance requires a social check, each guards own resources |
| Hostility | May take adversarial actions |

**Betrayal Safety Rules**: Must have character motivation, must advance the plot, must have consequences, destructive betrayal is forbidden, use safety tools (e.g., X-Card).

---

# Appendix A: Random Encounter Tables

## Level 0 (1D10)

| D10 | Encounter |
|-----|-----------|
| 1 | Area of total darkness — claw-scratching sounds in the distance |
| 2 | Fresh marks on the wall — left by predecessors within the last few hours |
| 3 | An unopened bottle of Almond Water on the low wall of a cubicle |
| 4 | A running computer — a line of text on the screen |
| 5 | Fluorescent lights begin going out row by row — toward your direction |
| 6 | A temporary barricade built from overturned office desks |
| 7 | Bloodstains on the carpet — drag marks leading into the depths |
| 8 | Complete silence — the fluorescent hum stops for 1D6 minutes |
| 9 | Three bottles of Almond Water neatly placed + a note: "You are not alone." |
| 10 | A door that shouldn't exist — leading to... |

## Level 2 (1D10)

| D10 | Encounter |
|-----|-----------|
| 1 | Ruptured pipe spews high-temperature steam (Agility DC 12 to evade) |
| 2 | Edge of a Hound nest — can see the entrance, hear pups |
| 3 | Leaking liquid from a ruptured pipe — possibly Almond Water |
| 4 | A Lost sitting by the pipe, muttering numbers |
| 5 | Large scratches on the wall — not left by a human |
| 6 | A bright red valve vibrating |
| 7 | Pipe-tapping sounds — from multiple directions, answering each other |
| 8 | A small shelter inside a half-open maintenance door — supplies left by predecessors |
| 9 | Total darkness — light sources fail here |
| 10 | Upward stairs — leading to (1D4: 1=Level 1 / 2=Level 4 / 3=Level 11 / 4=Unknown) |

## Level 11 (1D10)

| D10 | Encounter |
|-----|-----------|
| 1 | A BNTG trader passes by pushing a cart |
| 2 | A person stands at the street corner — smiling for too long |
| 3 | An intact bookstore — books on the shelves |
| 4 | An M.E.G. recruitment poster |
| 5 | The street suddenly ends — a blank area ahead |
| 6 | A Wanderer runs up asking for help — real or a trap? |
| 7 | An abandoned market stall — some items still left behind |
| 8 | A hand-drawn Level 11 district map — several locations marked |
| 9 | A group of Wanderers sit around a park bench — they look at you |
| 10 | You hear your name — from the alley. You recognize that voice. |

## Level 1 (1D10)

| D10 | Encounter |
|-----|-----------|
| 1 | A loud crash of collapsing shelves — noise cover, but draws attention |
| 2 | M.E.G. patrol — provides intel and trade |
| 3 | A Smiler's smile flickering in a dark corner |
| 4 | A box of unopened canned food (scavenge DC 12) |
| 5 | Abandoned repair tools (Crafting materials) |
| 6 | A gramophone — plays 1940s music, nearby restores 1D3 SP |
| 7 | A Hound's low growl from deep in the shelves |
| 8 | A panicked independent Wanderer — requests escort |
| 9 | A machinery room — can scavenge batteries and parts |
| 10 | An elevator descending into the depths — what's behind the door? |

## Level 4 (1D10)

| D10 | Encounter |
|-----|-----------|
| 1 | An unlit corridor — a Smiler smiling in the dark |
| 2 | "The Last Employee" — a faceless Clerk typing in the F3 corner |
| 3 | An Almond Water supply point in the pantry |
| 4 | A Partygoer's invitation — "Party in F5!" |
| 5 | Mirror Room (F7) — a safe zone the Partygoers dare not enter |
| 6 | Archive room — records Level intel left by predecessors |
| 7 | Server room — digital records of the Partygoers' origin |
| 8 | A genuine Wanderer ally — shares supplies |
| 9 | Appliances start on their own — anomalies when no one is watching |
| 10 | A golden elevator — leads to Level 5 |

## Level 37 (1D10)

| D10 | Encounter |
|-----|-----------|
| 1 | A warm-water pool — the temptation of water begins (Willpower DC 10) |
| 2 | An Almond Water film — floating on the surface (one per 3-5 pools) |
| 3 | "The Swimmer" grabs your ankle — trying to keep you down |
| 4 | Remains of the Lost — old supplies by the pool |
| 5 | "The Lifeguard" — unmoving on a high chair, drags you into the depths when you drown |
| 6 | Water-mirror phenomenon — the reflection shows a parallel version of yourself |
| 7 | A Lost by the children's pool — muttering fragmentary intel |
| 8 | A dry, un-tiled corridor — leads to Level 4 |
| 9 | A dark shadow in the deepest water — "the thing at the bottom of the pool" |
| 10 | The legend of a third exit — an underwater passage in a cold-water pool |

---

# Appendix B: Complete Glossary

| Traditional Chinese | Abbrev. | English | Description |
|---------------------|---------|---------|-------------|
| 後室 | — | The Backrooms | The game's primary world — a parallel dimension made of infinite Levels |
| 卡穿 | — | Noclipping | Phasing through reality to enter The Backrooms |
| 樓層 | — | Level | An independent dimensional pocket |
| 杏仁水 | — | Almond Water | Core resource — healing / restoring Sanity / banishing / trading |
| 實體 | — | Entity | Non-human entities in The Backrooms |
| 獵犬 | — | Hound | Pack predators in dark Levels |
| 笑魘 | — | Smiler | Entity appearing in darkness — an over-wide smile |
| 竊皮者 | — | Skin-Stealer | Entity disguised as a human |
| 派對客 | — | Partygoer | Entity that traps with friendliness |
| 鈍人 | — | Duller | Entity you must not look back at |
| 失落者 | — | The Lost | Former humans whose Sanity has hit zero |
| 流浪者 | — | Wanderer | The collective term for all humans in The Backrooms |
| 主要探索者集團 | M.E.G. | Major Explorer Group | The largest human organization |
| 後室貿易網絡 | BNTG | Backrooms Trade Network Group | A cross-Level trading organization |
| 前哨站 | — | Outpost | Fixed stronghold of a faction |
| 生命值 | HP | Health Points | A character's physical health value |
| 理智值 | SP | Sanity Points | A character's mental health value |
| 防禦值 | DEF | Defense | The target value to exceed when attacked |
| 難度等級 | DC | Difficulty Class | The target value for a check |
| 行動點數 | AP | Action Points | Action resource in combat rounds |
| 熟練加值 | PB | Proficiency Bonus | Bonus from skill training |
| 遊戲主持人 | GM | Game Master | The person running the game — that's you |

---

# Appendix C: Quick Reference (GM Only)

## DC Quick Reference

| DC | Label | AV 5 Success Rate | AV 5 + Expert |
|----|-------|-------------------|---------------|
| 5 | Trivial | 100% | 100% |
| 10 | Routine | 80% | 95% |
| 12 | Moderate | 70% | 90% |
| 15 | Hard | 55% | 80% |
| 18 | Very Hard | 40% | 65% |
| 20 | Extreme | 30% | 55% |
| 25 | Nearly Impossible | 5% | 30% |

## Core Formulas

| Calculation | Formula |
|-------------|---------|
| HP | Physique × 2 + 5 |
| DEF | 10 + Agility value |
| SP | Sanity × 3 + 10 |
| Carry Capacity | Physique × 2 kg |
| Attribute Check | D20 + Attribute Value vs DC |
| Skill Check | D20 + Attribute Value + Proficiency Bonus vs DC |
| Willpower Resistance | D20 + Sanity Value + Willpower Proficiency vs DC (DC = SP Loss × 5 + 5) |
## Healing Quick Reference

| Method | HP | SP | Note |
|------|-----|-----|------|
| Almond Water | 1D6 | 1D4 | 1 unit per use |
| Bandage | 2D6 | — | removes Bleeding |
| First Aid Kit | 3D6 | — | removes Bleeding + Poison |

## Chase Distance

| Distance | Status |
|------|------|
| 0 | Caught |
| 1-3 | Danger (Entities attack at Disadvantage) |
| 4-6 | Controllable |
| 7-9 | Safe |
| 10 | **Escaped!** |

---

> **This concludes the Game Master Rulebook.**
> 
> You now have all the tools you need to run Backrooms Walker TRPG. Remember — your most important role is not that of a rules enforcer, but a storyteller. The Backrooms is a story about loneliness, survival, and finding meaning in an endless maze. Make the players' choices matter, let failure have consequences but not be the end, and let every moment of respite feel like a gift.
> 
> Good luck, Game Master. The Backrooms awaits you — and your players.
