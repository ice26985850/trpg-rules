# Backrooms Walker TRPG — Player Rulebook

> **Version:** v1.1
> **Design Studio:** Tabletop Rules Studio
> **Language:** Traditional Chinese

---

# Chapter One: Welcome to the Backrooms

## 1.1 What Is Backrooms Walker TRPG?

**Backrooms Walker TRPG** is a tabletop role-playing game set in the world of "The Backrooms." You play an ordinary person who has accidentally "phased through" (noclip) from the real world into the Backrooms — perhaps an office worker pulling a late-night shift, a delivery driver lost in an underground parking garage, or a student who walked through the wrong door at home.

This is not a story about heroes. This is a story about survival.

## 1.2 The Core Experience of This Game

| Core Gameplay | Description |
|---------|------|
| **Level Exploration** | The Backrooms is composed of infinitely many "Levels." Each Level has its own spatial structure, physical rules, and threats |
| **Resource Management** | Almond Water, food, batteries — everything must be carefully budgeted |
| **Entity Avoidance** | The Backrooms contains "Entities" — they are not monsters you can defeat. Most of the time, you should run |
| **Exit Finding** | Every Level has exits leading to other Levels. Your goal is: to find a way to stay alive |

> **Design Philosophy:** "The Backrooms does not care about you. It bears no malice — it simply bears no goodwill. You are not a hero here; you are an ordinary person trying not to die in an infinite maze."

## 1.3 What Do You Need to Play?

| Item | Purpose |
|------|------|
| This rulebook | To understand the game rules |
| Character Sheet (Blank Player Character Sheet.xlsx) | To record your character information |
| One twenty-sided die (D20) | To make Checks |
| Pencil and eraser | To record and revise |
| One Game Master (GM) | Played by a friend, responsible for describing the world, portraying NPCs, and adjudicating actions |

## 1.4 Quick Start for Your First Game

If you're eager to play, here is a five-minute quick start:

1. **Open the Character Sheet Excel file** and fill it out following the Six-Step Creation Process in Chapter Three
2. **Read Chapter Two** to learn how to roll dice and make Checks
3. **Your GM will guide you** into the first scenario "S1: Awakening"
4. When you encounter an unfamiliar term, flip to the appendix to consult the glossary

---

# Chapter Two: Core Rules

## 2.1 Basic Dice System

Backrooms Walker TRPG uses the **D20 system**. When you attempt anything with an uncertain outcome, roll a twenty-sided die (D20), add the relevant modifiers, and pit it against a target Difficulty Class (DC).

### Basic Formula

```
D20 + Attribute Value (AV) + Proficiency Bonus (PB) + Circumstance Modifier vs Difficulty Class (DC)
```

- **If the result ≥ DC**: You succeed!
- **If the result < DC**: You fail. Things may get worse.

### Critical Success and Critical Failure (Dual-Track System)

| Situation | Effect |
|------|------|
| Natural die roll of **20** | **Critical Success!** You do better than expected. The GM will describe an additional positive effect. |
| Natural die roll of **1** | **Critical Failure...** Things go wrong in the worst possible way. |
| Result is **10 or more above** the DC | **Critical Success!** Even without a natural 20. |
| Result is **10 or more below** the DC | **Critical Failure...** Even without a natural 1. |

The two can stack: a natural 20 that is also 10+ above the DC = **Legendary Success**. A natural 1 that is also 10+ below the DC = **Catastrophic Failure**.

### Advantage and Disadvantage

When you are in a particularly favorable or unfavorable situation, the GM may grant you "Advantage" or "Disadvantage":

- **Advantage**: Roll 2 D20s, take the higher result
- **Disadvantage**: Roll 2 D20s, take the lower result

Advantage and Disadvantage do not stack — if you have both Advantage and Disadvantage simultaneously, they cancel each other out, and you roll a single D20 normally.

> **Tip:** Advantage is roughly equivalent to a +3.3 bonus. Disadvantage is roughly equivalent to -3.3. They do not change the range you can roll (1-20), but they significantly change your success rate.

## 2.2 The Five Attributes

Your character has five core attributes, representing the various facets of your survival in the Backrooms:

| Attribute | Abbrev. | Meaning | Role in the Backrooms |
|------|------|------|---------------|
| **Physique** | PHY | Physical health, endurance, resistance to physical harm | Walking for long periods without exhaustion, resisting Entity attacks, maintaining mobility in dangerous environments |
| **Agility** | AGI | Speed, reaction, dexterity | Fleeing pursuers, crossing dangerous areas before collapse, moving silently |
| **Perception** | PER | Observational skill, sensitivity to environmental detail, intuition | Noticing exit locations, identifying anomalous objects, hearing distant footsteps |
| **Sanity** | SAN | Mental resilience and psychological endurance | Resisting the Backrooms' erosion of the mind — endless corridors, loneliness, illogical spaces |
| **Knowledge** | KNO | Understanding of Backrooms rules, memory | Recalling Level information, solving environmental puzzles, exchanging intelligence with other Wanderers |

**Attribute Value range**: 1 to 10. The average for an ordinary human is about 5.

**Attribute Bonus**: In Backrooms Walker, the attribute bonus **is directly equal to your attribute value**. For example: a character with Physique 6 gains a +6 bonus on Physique Checks.

## 2.3 Derived Attributes

From the Five Attributes, the following derived values can be calculated:

| Derived Attribute | Formula | Description |
|---------|---------|------|
| **Hit Points (HP)** | Physique × 2 + 5 | How much damage your body can withstand. At zero, you are at the brink of death |
| **Defense (DEF)** | 10 + Agility value | The target number an Entity must exceed when attacking you |
| **Sanity Points (SP)** | Sanity × 3 + 10 | Your total mental resilience. At zero, you lose control |
| **Almond Water Reserve** | Starting 5 units | The most critical resource in the Backrooms — healing, restoring Sanity, repelling Entities |
| **Calorie Reserve** | Starting 10 units | Consume 1 unit per day. At zero → Physique -1 per day |
| **Carry Capacity** | Physique × 2 (kg) | The total weight of items you can carry |
| **Movement Speed** | 6 + Agility value (meters/turn) | The distance you can move per turn in combat |
| **Initiative Bonus** | Agility value + Perception value | Determines action order in combat |

### The Meaning of Hit Points (HP)

HP is not a resource you can casually spend. In the Backrooms, your HP is very limited — a healthy ordinary person (Physique 5) has only 15 HP. A single Entity attack can deal 4-8 points of damage.

**This is why combat is the last option.**

### The Meaning of Sanity Points (SP)

SP represents your mental integrity. It does not decrease from physical damage the way HP does — it is eroded by fear, loneliness, and witnessing things that should not exist.

As SP decreases, your perception of the world begins to distort. When SP reaches zero, you lose control of yourself.

## 2.4 Difficulty Class (DC) Ladder

| DC | Difficulty Label | Typical Scenario |
|----|---------|---------|
| 5 | Trivial | Opening an unlocked door |
| 8 | Simple | Climbing over a low wall |
| 10 | Routine | Searching for items on a cluttered desk |
| 12 | Moderate | Picking a simple lock |
| 15 | Hard | Searching for useful supplies in a messy environment |
| 18 | Very Hard | Moving silently in the dark |
| 20 | Extreme | Forcibly clipping out of a Level |
| 25 | Nearly Impossible | Determining direction in total darkness |

### Circumstance Modifier

The environment affects the difficulty of your Checks. The GM may adjust the DC based on the following factors:

| Factor | Adjustment |
|------|------|
| Well-lit | DC -2 |
| Dim/Faint light | DC +2 |
| Total darkness | Automatic failure (unless you have a special ability) |
| Proper tools available | DC -2 to -5 |
| Ample time | DC -3 |
| Rushed/Under pressure | DC +2 |
| Character already injured | DC +2 |

## 2.5 Skill System

Skills represent specific abilities you have gained through background and experience. Backrooms Walker TRPG has a total of **18 Skills**, categorized by the Five Attributes:

### Physique (PHY) Skills

| Skill | Description |
|------|------|
| **Athletics** | Climbing, jumping, swimming, long-distance movement |
| **Endurance** | Resisting fatigue, enduring hunger and thirst, surviving extreme temperatures |
| **Might** | Lifting heavy objects, breaking obstacles, pushing through blocked doors |

### Agility (AGI) Skills

| Skill | Description |
|------|------|
| **Stealth** | Moving silently, hiding, avoiding detection by Entities |
| **Acrobatics** | Maintaining balance, rolling, passing through narrow passages |
| **Sleight of Hand** | Picking locks, disarming traps, fine manipulation |
| **Evasion** | Dodging attacks, escaping dangerous areas |

### Perception (PER) Skills

| Skill | Description |
|------|------|
| **Search** | Finding supplies, clues, hidden items in the environment |
| **Track** | Following traces, identifying footprints, judging Entity activity zones |
| **Insight** | Judging others' intentions, detecting deception, recognizing disguises |
| **Danger Sense** | Instinctively sensing impending danger |

### Sanity (SAN) Skills

| Skill | Description |
|------|------|
| **Willpower** | Resisting fear, staying calm, fighting mental control |
| **Composure** | Maintaining Sanity under high-pressure environments, soothing others |
| **Meditation** | Restoring Sanity through mental focus, resisting environmental erosion |

### Knowledge (KNO) Skills

| Skill | Description |
|------|------|
| **Backrooms Lore** | Recalling Level information, Entity traits, known exits |
| **First Aid** | Treating wounds, stabilizing injuries, identifying medicines |
| **Crafting** | Repairing items, making tools, modifying equipment |
| **Spatial Memory** | Remembering routes, not getting lost, drawing maps |

### Skill Proficiency

Each skill has three Proficiency Tiers:

| Tier | Bonus | Description |
|------|------|------|
| **Untrained** | +0 | You have no special training in this skill and can only rely on your attribute |
| **Trained** | +3 | You have received relevant training or have rich experience |
| **Expert** | +5 | You are an expert in this field |

**Skill Check Formula**: `D20 + Attribute Value + Proficiency Bonus vs DC`

> **Example**: Your character has "Perception 6" and "Search (Trained)." You are searching for supplies in an abandoned office. The GM sets the DC at 15. You roll a D20 and get 11.
> 
> 11 + 6 (Perception value) + 3 (Trained bonus) = 20 ≥ 15 → **Success!**
> 
> You find a sealed bottle of Almond Water and a few batteries deep in a drawer.

---

# Chapter Three: Character Creation

## 3.1 Character Creation Overview

Character creation in Backrooms Walker TRPG is a six-step narrative process. You are not "building a class character" — you are defining a **real person**, and then throwing him/her into the Backrooms.

| Step | Content | Output |
|------|------|------|
| 1. Who are you | Name, age, life before phasing through | Character backstory |
| 2. Attribute Allocation | Distribute 25 points among the Five Attributes | Attribute values |
| 3. What's in your pocket | Items on your person when you phased through | Starting equipment |
| 4. How long have you been here | Determine starting Knowledge value and starting Level | Starting condition |
| 5. What have you seen | First Entity encounter | Initial Sanity adjustment |
| 6. Do you want to go back | Character's core motivation | Story hook |

## 3.2 Step One: Who Are You

Answer the following questions to build your character:

- **Name**: What is your character called?
- **Age**: How old?
- **Life before phasing through**: What work do you do? What is your daily routine like?
- **The moment of phasing through**: Where were you, and what were you doing when you fell into the Backrooms?

> **Example**: Li Ming, 32 years old, night-shift security guard. While patrolling an old office building at 3 a.m., he walked down an unusually long corridor — when the door at the end of the corridor opened, it was not the parking garage, but the yellow cubicles of Level 0.

## 3.3 Step Two: Attribute Allocation

You have **25 points** to distribute among the Five Attributes. The range for each attribute is **1 to 8** (the per-attribute cap during initial creation is 8).
### Attribute Allocation Tips

| Character Type | Recommended Primary Attributes |
|---------|-------------|
| Body-reliant Survivor | High Physique, moderate-high Agility |
| Cautious Explorer | High Perception, moderate-high Knowledge |
| Mentally Resilient Lone Wanderer | High Sanity, moderate Knowledge |
| All-Rounder | Evenly distribute across all attributes (about 5/5/5/5/5) |

> **Allocation Example** (Night Shift Security Guard, Li Ming):
>
> Physique 6, Agility 5, Perception 7, Sanity 4, Knowledge 3
>
> Total: 6+5+7+4+3 = 25 ✓

### Derived Attribute Calculation

After filling in your attributes, immediately calculate your derived attributes:

| Derived Attribute | Calculation | Li Ming's Values |
|---------|------|-----------|
| Hit Points (HP) | Physique × 2 + 5 | 6×2+5 = **17** |
| Defense (DEF) | 10 + Agility Value | 10+5 = **15** |
| Sanity Points (SP) | Sanity × 3 + 10 | 4×3+10 = **22** |
| Carry Capacity | Physique × 2 kg | 6×2 = **12 kg** |
| Movement Speed | 6 + Agility Value m | 6+5 = **11 m/round** |
| Initiative Bonus | Agility Value + Perception Value | 5+7 = **+12** |

## 3.4 Step Three: Background Selection

Choose a "pre-noclip Background". Your Background determines your proficient Skills and suggested starting gear. Below are eight optional Backgrounds:

> **⚠ Character Creation Proficiency Allocation (Must Read)**: Each Background grants you three categories of proficiency. You must complete all of them:
> - **Trained Skills (choose 3)**: Pick from the suggested Skills in the Background list.
> - **Free Training (choose 2)**: Any Skills that do not overlap with the above, raised to Trained (+3).
> - **Expert Skill (choose 1)**: Raise **any single** Skill directly to Expert (+5). This is a choice you **must** make during Character Creation — it represents your strongest area. Record it in the "Skill Proficiency" field on your Character Sheet.

### Background One: Night Shift Security Guard

> *"I've worked the night shift in this building for three years. I thought I knew every corner. Until tonight."*

| Item | Content |
|------|------|
| **Attribute Tendency** | Perception + Physique |
| **Trained Skills (choose 3)** | Search, Insight, Danger Sense, Endurance |
| **Expert Suggestion** | Search or Insight |
| **Free Training (choose 2)** | Any Skills that do not overlap with the above |
| **Suggested Starting Gear** | Flashlight (with batteries), keyring (with universal key), thermos (filled with coffee) |
| **Background Ability** | **Night Vision Adaptation**: In dimly lit environments, Perception Checks do not suffer Disadvantage from insufficient light |

### Background Two: Delivery Rider

> *"I ride through half the city every day. I know every shortcut. But today, the navigation led me down a road that isn't on any map."*

| Item | Content |
|------|------|
| **Attribute Tendency** | Agility + Perception |
| **Trained Skills (choose 3)** | Spatial Memory, Acrobatics, Athletics, Endurance |
| **Expert Suggestion** | Spatial Memory or Acrobatics |
| **Free Training (choose 2)** | Any Skills that do not overlap with the above |
| **Suggested Starting Gear** | Smartphone (no signal but usable as flashlight), backpack (large capacity), insulated bag (with food inside) |
| **Background Ability** | **Shortcut Thinking**: Navigation-related Spatial Memory Checks gain Advantage |

### Background Three: Graduate Student

> *"The topic of my thesis is 'Theoretical Models of Non-Euclidean Space.' My professor said it had no practical use. He was wrong."*

| Item | Content |
|------|------|
| **Attribute Tendency** | Knowledge + Sanity |
| **Trained Skills (choose 3)** | Backrooms Lore, Crafting, Meditation, Insight |
| **Expert Suggestion** | Backrooms Lore or Crafting |
| **Free Training (choose 2)** | Any Skills that do not overlap with the above |
| **Suggested Starting Gear** | Notebook and pen, calculator, library card (useless, but it comforts you) |
| **Background Ability** | **Theory Application**: When encountering anomalous phenomena related to physical rules, you may make a Knowledge Check (DC 15) to understand their pattern; on success, your next related Check gains Advantage |

### Background Four: Emergency Nurse

> *"I've seen many terrible things. Car crashes, severe injuries, death. But nothing prepared me to face this place."*

| Item | Content |
|------|------|
| **Attribute Tendency** | Sanity + Knowledge |
| **Trained Skills (choose 3)** | First Aid, Composure, Willpower, Insight |
| **Expert Suggestion** | First Aid or Composure |
| **Free Training (choose 2)** | Any Skills that do not overlap with the above |
| **Suggested Starting Gear** | First aid kit, medical gloves, nurse uniform (many pockets) |
| **Background Ability** | **Emergency Treatment**: First Aid Checks gain Advantage. When treating others, restore an additional 1D4 HP |

### Background Five: Warehouse Worker

> *"I move things around the warehouse every day. Concrete floors, shelves, forklifts. But the warehouse I work in isn't this big — big enough to have no end."*

| Item | Content |
|------|------|
| **Attribute Tendency** | Physique + Agility |
| **Trained Skills (choose 3)** | Might, Endurance, Athletics, Crafting |
| **Expert Suggestion** | Might or Crafting |
| **Free Training (choose 2)** | Any Skills that do not overlap with the above |
| **Suggested Starting Gear** | Work gloves (protective), multi-tool knife, iron hammer (usable as weapon) |
| **Background Ability** | **Carry Adaptation**: Carry Capacity increased by 50% (becomes Physique × 3 kg) |

### Background Six: Photographer

> *"I see the world through a lens. When you frame the world in a rectangle, you start noticing the details others overlook."*

| Item | Content |
|------|------|
| **Attribute Tendency** | Perception + Knowledge |
| **Trained Skills (choose 3)** | Search, Track, Insight, Spatial Memory |
| **Expert Suggestion** | Search or Track |
| **Free Training (choose 2)** | Any Skills that do not overlap with the above |
| **Suggested Starting Gear** | Camera (with batteries), spare memory card, lens cleaning cloth |
| **Background Ability** | **Eye for Detail**: On Search Checks, if you spend extra time (GM's discretion), you may gain Advantage |

### Background Seven: Wanderer (Someone Who Has Already Stayed in The Backrooms)

> *"I no longer remember what the outside world looks like. How long have I been here...? Months? Or years?"*

| Item | Content |
|------|------|
| **Attribute Tendency** | Choose any two |
| **Trained Skills (choose 4)** | Backrooms Lore, Stealth, Endurance, Willpower, Spatial Memory (choose 4) |
| **Expert Suggestion** | Backrooms Lore or Stealth |
| **Free Training (choose 1)** | Any Skills that do not overlap with the above |
| **Suggested Starting Gear** | Worn-out backpack, worn machete, a journal filled with notes |
| **Background Ability** | **Veteran's Intuition**: Once per session, you may ask the GM a question about the current Level; the GM must answer honestly (though the answer may be vague) |

### Background Eight: Office Worker

> *"My life was just one cubicle to another. From home to the office, from the meeting room to the pantry. Now it's from one yellow cubicle to another yellow cubicle."*

| Item | Content |
|------|------|
| **Attribute Tendency** | Sanity + Knowledge |
| **Trained Skills (choose 3)** | Composure, Meditation, Insight, Sleight of Hand |
| **Expert Suggestion** | Composure or Sleight of Hand |
| **Free Training (choose 2)** | Any Skills that do not overlap with the above |
| **Suggested Starting Gear** | Briefcase (can hold items), insulated tumbler, company ID badge (useless, but looking at it gives you a strange sense of reassurance) |
| **Background Ability** | **Administrative Resilience**: When performing repetitive, tedious tasks (such as searching large volumes of documents for a long time), you do not suffer Disadvantage from monotony; your carried briefcase provides +1 kg to Carry Capacity |

## 3.5 Step Four: How Long Have You Been Here

This choice affects your initial Knowledge Value and starting state:

| Time | Initial Knowledge Value | Starting Sanity Adjustment | Starting Level | Description |
|------|-----------|-------------|---------|------|
| **First Day** | 0 | No adjustment | Level 0 | You just noclipped in. You know nothing. You have nothing. Only you and the endless yellow corridors. |
| **One Week** | +2 | Sanity -2 | Level 1 or Level 0 | You've learned the basics. You know what Almond Water is. You may have already met people from M.E.G. |
| **One Month** | +4 | Sanity -4 | Level 1, Level 2 or Level 11 | You're already an experienced Wanderer. You know the exits of several Levels. You have some resources — and scars. |

> **Knowledge Value (KNO Value)**: The Knowledge Value is an **independently tracked number** (do not confuse it with the "Knowledge" attribute), representing your intuitive understanding of The Backrooms. At Character Creation it is determined by "time spent in The Backrooms": First Day +0 / One Week +2 / One Month +4. When making a **Backrooms Lore** Check, add the Knowledge Value directly to the Knowledge attribute (e.g., Knowledge 3 + Knowledge Value 2 = 5 for the Check). The Knowledge Value can grow during play — when you reach Milestone 5 "The Knower", or when you discover a key secret of a certain Level / Entity, the GM may let it +1. Please record this number in the "Knowledge Value" field on your Character Sheet and update it each time it grows.

## 3.6 Step Five: What Have You Seen

You have encountered at least one Entity. Choose or roll to decide (1D6):

| Roll | Entity | Encounter Description | Initial Effect |
|------|------|---------|---------|
| 1-2 | **Hounds** | You heard them in the dark — the sound of claws scraping the ground. You ran. You didn't look back. | You have a basic understanding of the Hounds' behavior patterns. You gain a +1 bonus to hiding Checks against Hounds. Sanity -1 (the memory haunts you). |
| 3-4 | **Smilers** | The moment the lights went out, you saw it — that oversized smile in the dark. You aimed your light at it, and it vanished. But not immediately. | You will never forget that smile in the dark. You gain a +1 bonus to Willpower Checks against Smilers. You have a mild fear of darkness (in darkness, Sanity Check DC +1). |
| 5 | **Partygoers** | You were invited to a "party". You almost accepted. Until you noticed that person's smile never faded — not even for a second. | You stay wary of overly friendly strangers. You gain a +2 bonus to Insight Checks against Partygoers. |
| 6 | **Skin-Stealers** | You traveled with a person for three days. On the third night, you noticed his finger count was wrong. | You don't easily trust anyone. You gain a +1 bonus to Perception Checks against disguised Entities. Sanity -2 (loss of trust). |

## 3.7 Step Six: Do You Want to Go Back

This is the most important question. Your answer will define your character's core motivation throughout the entire game.

| Choice | Description |
|------|------|
| **"I must go back."** | Someone is waiting for you out there — family, a lover, or an unfulfilled promise. Every action you take is to find the way home. |
| **"I'm not sure."** | You've seen in The Backrooms something the real world never gave you — a strange freedom, a chance to start over. You struggle with it. |
| **"No. This is where I belong."** | You have nothing in the real world worth returning to. The Backrooms is hell — but at least it's an honest hell. |
| **"I want to go back — but not alone."** | You must go back, but you can't leave the others behind. You'll find a way to let everyone go back together. |

### Inspiration Point Mechanic (Optional)

Your "reason for going back" is also a game mechanic. Once per session, when your character makes an important decision or takes a risk because of this reason, you may gain one "Inspiration Point".

**Using an Inspiration Point**: Reroll any one D20 Check. You must accept the new result.

---

# Chapter Four: Resources and Equipment

## 4.1 Core Resources Overview

In The Backrooms, resources are life. Below are the core resources you need to manage during your journey:

| Resource | Initial Amount | Use | Consumption Method |
|------|--------|------|---------|
| **Almond Water** | 5 units | Healing, Sanity recovery, Entity expulsion, trade currency | 1 unit per use |
| **Calorie** | 10 units | Sustaining life | 1 unit per day (after depletion, Physique -1 per day) |
| **Battery** | Depends on equipment | Powers flashlights, communication devices | Consumed per usage scenario |
| **Sanity Points (SP)** | Sanity × 3 + 10 | Maintaining mental stability | Fluctuates with events |

## 4.2 Almond Water — The Liquid Gold of The Backrooms

Almond Water is the most critical resource in The Backrooms. It is a transparent liquid with a faint almond scent, naturally generated in certain Levels.

### The Four Uses of Almond Water

| Use | Effect | Consumption |
|------|------|------|
| **Drink — Healing** | Restore 1D6 HP | 1 unit |
| **Drink — Restore Sanity** | Restore 1D4 SP | 1 unit |
| **Throw — Expel Entity** | Expel Smilers for 1D3+1 rounds, expel Hounds for 1D3 rounds | 1 unit |
| **Trade** | Used as a universal currency at outposts and within the BNTG network | Depends on trade |

> **Important**: Almond Water cannot exist outside The Backrooms. If you try to bring it back to the real world, it will evaporate into tasteless vapor within seconds.

## 4.3 Item System

### Item Categories

| Category | Description | Example |
|------|------|------|
| **Light Source** | Lets you see. Essential in dark Levels. | Flashlight, glow stick, lighter, candle |
| **Weapon/Tool** | Items that can be used as weapons. Remember — you shouldn't fight. | Iron pipe, machete, screwdriver, iron hammer |
| **Food & Water** | Maintain Calories and hydration. | Canned food, energy bar, bottled water |
| **Medical Supplies** | More effective physical treatment than Almond Water. | Bandages, first-aid medicine, disinfecting alcohol |
| **Clothing & Protection** | Protect the body, provide warmth. | Coat, gloves, protective vest |
| **Communication & Recording** | Record information, contact others. | Walkie-talkie, notebook, voice recorder |
| **Special Items** | Useful items that don't fit other categories. | Tape, rope, universal key |

### Item Stat Explanation

Each item has the following attributes:

| Attribute | Description |
|------|------|
| **Weight** | Occupies your Carry Capacity (kg). Exceeding carry weight makes you unable to move. |
| **Durability/Uses** | How many times an item can be used before breaking. |
| **Effect** | The item's game effect. |
| **Rarity** | Common/Uncommon/Rare — affects the difficulty of finding it while scavenging. |

### Selected Item List

#### Light Sources

| Item | Weight | Durability | Effect | Rarity |
|------|------|------|------|------|
| Flashlight | 0.5 kg | 6 hours battery | Illuminates near to mid range. Essential in dark Levels. | Common |
| Glow Stick (pack of 3) | 0.1 kg | 6 hours (each) | Illuminates near range. Dimmer than flashlight but does not attract Entity attention. | Common |
| Lighter | 0.05 kg | 100 uses | Illuminates near range. Can ignite flammable objects. Faint light but the battery never runs out. | Common |
| Headlamp | 0.2 kg | 8 hours battery | Illuminates near to mid range. Frees both hands. | Uncommon |
| Camping Lantern | 1 kg | 12 hours battery | Illuminates mid range. Can cover a small room. Battery cannot be replaced — spent means discarded. | Uncommon |
| Oil Lamp | 1.5 kg | Requires fuel | Illuminates mid to far range. Warm, steady light. Some Entities loathe firelight. | Rare |

#### Weapons & Tools

| Item | Weight | Damage | Effect | Rarity |
|------|------|------|------|------|
| Iron Pipe | 2 kg | 1D6 Bludgeoning | Can be used as a lever. | Common |
| Screwdriver | 0.1 kg | 1D3 Piercing | Can pick locks, disassemble equipment. | Common |
| Iron Hammer | 1.5 kg | 1D6 Bludgeoning | Can break obstacles. | Common |
| Machete | 1 kg | 1D8 Slashing | Can cut ropes, vines. | Uncommon |
| Fire Axe | 3 kg | 1D10 Slashing | Can break doors and obstacles. Unwieldy. | Uncommon |
| Homemade Spear | 2 kg | 1D6 Piercing | Mid range. Can attack from a safe distance. | Scarce (requires Crafting Skill) |
#### Food & Water

| Item | Weight | Effect | Rarity |
|------|------|------|------|
| Canned Food | 0.5 kg | Restores 2 Calories | Common |
| Energy Bar | 0.1 kg | Restores 1 Calorie | Common |
| Bottled Water (500ml) | 0.5 kg | Maintains hydration for 1 day | Common |
| Military Ration | 0.8 kg | Restores 3 Calories, no need to eat for 24 hours | Uncommon |
| Thermos (filled with coffee) | 0.5 kg | Restores 1 Calorie, resists one Fatigue effect within 6 hours | Scarce |

#### Medical Supplies

| Item | Weight | Effect | Rarity |
|------|------|------|------|
| Bandage (5 uses) | 0.2 kg | Restores 2D6 HP, removes Bleeding status | Common |
| First Aid Medicine (3 uses) | 0.1 kg | Restores 3D6 HP, removes Poisoned and Bleeding | Uncommon |
| Disinfectant Alcohol (5 uses) | 0.3 kg | Prevents wound infection (used in Hardcore Mode) | Common |
| Sedative (2 uses) | 0.05 kg | Restores 1D6 SP, temporarily resists Panic | Uncommon |
| First Aid Kit (complete) | 1 kg | Contains one of each medical supply listed above | Rare |

#### Special Items

| Item | Weight | Effect | Rarity |
|------|------|------|------|
| Tape (one roll) | 0.3 kg | Universal repair tool. Can temporarily repair any item. | Common |
| Rope (10 m) | 1 kg | Climbing, binding, setting traps. | Common |
| Universal Key | 0.1 kg | Auto-succeeds on simple locks (DC 12 or below). 3 uses. | Uncommon |
| Backrooms Map (fragment) | 0.05 kg | Shows a partial area of a specific Level. May be outdated. | Scarce |
| Walkie-Talkie (a pair) | 0.5 kg (each) | Communication within Medium range. Requires batteries. | Uncommon |
| Voice Recorder | 0.1 kg | Records voice logs. Each recording restores 1 SP (once per day). | Scarce |

### Carry Capacity Management

Your Carry Capacity = Physique × 2 kg. Consequences of exceeding Carry Capacity:

| Exceed Ratio | Effect |
|---------|------|
| Below 100% | Normal movement |
| 101-150% | Movement Speed halved, all Physique and Agility checks are made with Disadvantage |
| Above 151% | Unable to move |

> **Hint**: The Warehouse Worker background has a Carry Capacity of Physique × 3 kg.

## 4.4 Starting Resource Allocation

Each new character starts with the following resources:

| Resource | Initial Amount |
|------|--------|
| Almond Water | 5 units |
| Calories | 10 units |
| Pocket Items | 3 items (chosen from background suggestions, total weight not exceeding Carry Capacity) |

---

## 4.5 Crafting System

Supplies in the Backrooms are never enough. Fortunately, you don't need to find ready-made gear—you can **make your own** from the scrap you pick up. This system makes the "Crafting" skill truly useful (the "Homemade Spear" in the item list is produced through it).

### Crafting Check

`D20 + Knowledge Value + Crafting Proficiency Bonus vs Crafting Difficulty (DC)`

| Item | DC | Time | Description |
|------|-----|------|------|
| Simple Repair (fix lockpicking tools, patch a backpack) | 10 | 10 minutes | Restores item uses or function |
| Simple Modification (add a grip, secure with rope) | 12 | 30 minutes | Slightly improves item effect |
| **Homemade Weapon/Tool** (e.g., Homemade Spear) | 14 | 1 hour | Craft usable equipment from scrap metal/wood |
| Complex Equipment (rebuild simple comms, repair machinery) | 18 | Several hours | Requires corresponding parts and blueprints |

### Materials

Crafting requires corresponding scrap, gathered from Level scavenging (metal parts, electronic components, fabric, wood, etc.). The GM determines available materials based on Level abundance—Level 1 and Level 4's machinery rooms and office equipment are the primary sources.

### Crafting Critical Success/Critical Failure

- **Critical Success (5+ above DC)**: Finished product quality improved—extra +1 Durability, or homemade weapon damage die +1.
- **Critical Failure**: Materials damaged (or partially lost), must scavenge materials again before retrying.

### Example: Homemade Spear

| Item | Value |
|------|------|
| Material | Long shaft (wood/metal) + pointed tip (scrap metal) |
| Check | Crafting DC 14, takes 1 hour |
| Product | 2 kg, 1D6 piercing damage, Medium range—can attack Entities from a safe distance |
| Rarity | Scarce (requires Crafting skill) |

> **Reminder**: Crafting is a survival tool, not combat enhancement. Even if you craft a spear, Backrooms Entities still resist physical damage—the spear's value lies in "keeping distance," not in "dealing massive damage."

---

# Chapter Five: Survival Guide

## 5.1 Sanity System

Sanity Points (SP) represent your mental integrity. They are one of the most core survival resources in Backrooms Walker TRPG—in some ways more important than HP.

### The Five Stages of SP

| SP Percentage | Stage | Effect |
|-----------|------|------|
| 100-76% | **Stable** | No negative effects. Your perception of the world is accurate. |
| 75-51% | **Uneasy** | Perception and Knowledge checks are made with Disadvantage. The GM may add an unreliable detail to the environment description. |
| 50-26% | **Fear** | All non-Physique checks are made with Disadvantage. The environment described by the GM begins to distort—you may see patterns on the wall moving (but they vanish after you blink). |
| 25-1% | **Edge of Collapse** | All checks are made with Disadvantage. Each time you face a stressful event, make a Willpower check (DC 15) or fall into a Panic state. |
| 0 | **Uncontrolled** | Your mind collapses. Roll D10 to determine your behavior: blind flight / frozen unable to act / hallucinatory attack (attacking the air) / hysterical laughter / catatonia (unable to speak or move). This state lasts 1D6 minutes or until someone helps you. |

### SP Loss

| Triggering Event | SP Loss |
|----------|---------|
| Alone in a Level for over 6 hours | -1 |
| Witnessing an Entity's terrifying form | -1 to -3 |
| Staying in "illogical" spaces (looping corridors, reversed directions, etc.) | -2 |
| Prolonged hunger or dehydration (per day) | -1 |
| Alone in darkness for over 30 minutes | -1 |
| Close encounter with a Partygoer's transformation ritual | -3 |

### SP Recovery

| Method | Recovery | Limit |
|------|--------|------|
| Drinking Almond Water | +1D4 SP | 1 unit per use |
| Interacting with other Wanderers | +1 to +3 SP | Once per encounter |
| Resting in a safe area | +1 SP/hour | Must be in a confirmed safe area (such as an outpost) |
| Completing an important goal | +1D3 SP | GM's discretion |
| Meditation check (Knowledge DC 12) | +1 SP | Requires spending 1 hour in a quiet environment |
| Writing a journal or recording | +1 SP | Once per day |

### Willpower Resistance

When facing a situation that may cause SP loss, you may attempt a Willpower check to resist:

- **Willpower Check**: `D20 + Sanity Value + Willpower Proficiency Bonus vs DC`
- DC = Potential SP Loss × 5 + 5
- Success: SP loss halved (rounded down)
- Critical Success (10+ above DC): Completely resist SP loss

> **Example**: You witness an Entity's terrifying form (potential loss -3 SP). You make a Willpower check: DC = 3×5+5 = 20. You roll 15 + Sanity 4 + Trained Willpower 3 = 22. Success! You only lose 1 SP.

## 5.2 Damage and Treatment

### Damage Types

| Type | Description | Example |
|------|------|------|
| **Physical—Blunt** | Blunt impact, strikes | Struck by a Hound, hit by falling debris |
| **Physical—Edged** | Cutting, piercing | Torn by claw strikes, cut by metal shards |
| **Physical—Piercing** | Penetrating damage | Pierced by spikes |
| **Environmental** | Damage from the environment | Falls, steam burns, drowning, crushing |
| **Mental** | Direct damage to Sanity | Witnessing the unspeakable |

### Injury States

| State | Trigger Condition | Effect |
|------|---------|------|
| **Minor Injury** | HP below 60% | All checks -1 |
| **Serious Injury** | HP below 30% | All checks -2, Movement Speed halved |
| **Dying** | HP drops to 0 | All checks are made with Disadvantage. Each turn requires a Physique check (DC 15); failure means death. After three successes, you stabilize (HP returns to 1, but you remain in a Serious Injury state). |

### Treatment Methods

| Method | Recovery | Limit |
|------|--------|------|
| Drinking Almond Water | 1D6 HP + 1D4 SP | 1 unit per use |
| Using Bandage | 2D6 HP, removes Bleeding | 1 use per use |
| Using First Aid Medicine | 3D6 HP, removes Bleeding and Poisoned | 1 use per use |
| Full Rest (8 hours) | Restores 50% of all HP | Must be in a safe area |
| Short Rest (1 hour) | Restores 1D6 HP | Must be in a relatively safe area |

## 5.3 Rest and Recovery

### Short Rest (1 hour)
- Restores 1D6 HP
- May make one Meditation check to recover SP
- May eat (consumes Calories)
- Cannot be done in dangerous areas

### Full Rest (8 hours)
- Restores 50% of all HP
- Restores 1D4 SP (stacks with Meditation effect)
- Consumes 1 Calorie
- Can only be done in safe areas (outposts, confirmed sealed rooms, etc.)

## 5.4 Calories and Survival

| Calorie Status | Effect |
|-----------|------|
| Calories > 0 | Normal state |
| Calories = 0 | **Starvation**: Physique -1 per day (permanent, until eating). All Physique checks are made with Disadvantage. |
| Calories = 0 for 3 consecutive days | **Severe Starvation**: Physique -2 per day. Movement Speed halved. SP -1 per day. |

**Replenishing Calories**: Eating food restores the corresponding Calorie value. The daily "natural consumption" is settled at each Full Rest.

---

# Chapter Six: Combat Basics (Player Perspective)

> **Important Reminder**: This chapter teaches you how to fight. But that doesn't mean you should fight. Most Entities in the Backrooms are not something you can defeat—they are part of the environment. Combat is the last option. Fleeing is almost always the wiser choice.

## 6.1 When Combat Occurs

Combat occurs in the following situations:
- You are discovered by an Entity and cannot escape
- You choose to attack proactively (not recommended)
- You are forced to protect yourself or others

The GM will declare "Enter Combat," then proceed according to the following flow.

## 6.2 Combat Flow Overview

```
1. Initiative Determination → 2. Round Cycle → 3. Combat End
```

### Initiative Determination

Each participant makes an Initiative check: `D20 + Agility Value + Perception Value`. Results are arranged in action order from highest to lowest. The GM's Entities also participate in this check.

On a tie, the one with higher Agility goes first. If still tied, the player goes first.

If you launch an attack while the Entity is unaware (ambush), you automatically take the first position in the initiative order.

### Round Structure

Each round is divided into three phases:

| Phase | Description |
|------|------|
| **1. Declare Intent** | Each participant (in initiative order) declares what they want to do this round. The GM declares the Entity's intent first. |
| **2. Execute Action** | In initiative order, each participant executes their action. |
| **3. Environment Phase** | The GM describes environmental changes—flickering lights, ceiling debris falling, sounds from afar, etc. |

> **The Benefit of Declaring Intent**: This lets you react to what is about to happen. If your teammate declares they will flee, you may want to adjust your plan. This mechanic also adds tension—you know what the Entity will do, but you are powerless to stop it.

## 6.3 Action Points (AP)

Each round you have **2 Action Points (AP)**. You can use AP to perform the following actions:

| Action | AP Cost | Description |
|------|---------|------|
| **Move** | 1 AP | Move one distance zone (Close→Medium, Medium→Far, etc.). You can move multiple zones, each consuming 1 AP. |
| **Attack** | 2 AP | Make one attack with a weapon. |
| **Use Item** | 1 AP | Drink Almond Water, use Bandage, swap items in hand, etc. |
| **Environmental Interaction** | 1 AP | Open/close doors, push objects, pull levers, etc. |
| **Hide** | 1 AP | Try to find cover and hide. Make a Stealth check. |
| **Observe** | 1 AP | Observe the environment carefully. Make a Perception check to gain more information. |
| **Defensive Stance** | 1 AP | Focus on defense. Attacks against you this round are made with Disadvantage. |
| **Assist** | 1 AP | Help an ally's next check, granting them Advantage. |
| **Wait** | Free | Delay your action to a later point in the round. Cannot be delayed to the next round. |
| **Sprint** | 2 AP | Move two distance zones. |
### Reactions

Each round you have **1 Reaction**. A Reaction can be used when it is not your turn:

| Reaction | Trigger | Effect |
|------|---------|------|
| **Dodge** | When you are attacked | +2 to your Defense (DEF). Must be declared before being attacked. |
| **Opportunity Action** | When an Entity (or enemy) moves away from you | Make a free melee attack. |
| **Change Intent** | When the environment undergoes a major change | Change the action you declared during the Declare Intent step (but total AP cost must not change). |

## 6.4 Distance System

Backrooms Walker TRPG uses a **zone system** rather than precise grids:

| Distance | Description | Typical Scenarios |
|------|------|---------|
| **Close** | Within reach (0-2 m) | Melee attacks, handing over items, whispering |
| **Medium** | Within the same room (2-10 m) | Effective flashlight illumination, pistol range, normal conversation |
| **Far** | Same corridor or large space (10-30 m) | Maximum throwing distance, shouting |
| **Out of Sight** | Not visible but possibly in the same zone | Behind a corner, beyond a wall, another room |

Moving one distance zone costs 1 AP.

## 6.5 Attacks

If you really must attack, here is the procedure:

### Attack Check

`D20 + Agility Value (melee) or Perception Value (ranged) + Weapon Proficiency vs target's Defense (DEF)`

- **Hit**: Your attack hits. Roll weapon damage dice.
- **Miss**: Your attack misses.
- **Critical Success** (natural 20 or exceeds DEF by 10+): Deal maximum damage, or apply an extra effect (GM's discretion).

### Damage

Use the damage dice corresponding to the weapon in the item list. Most improvised weapons deal 1D6 damage.

> **Important Reminder**: Backrooms Entities usually have some resistance to physical damage or extremely high HP. A Hound may withstand 20+ damage before going down—far more than you can deal. Fighting them is usually a waste of time and resources.

## 6.6 Non-Combat Actions

### Stealth

When you do not wish to be discovered by an Entity:

- **Stealth Check**: `D20 + Agility Value + Stealth Proficiency Bonus vs Entity's Perception Value`
- Lighting effects: In total darkness you gain Advantage, but if the Entity has special perception of darkness the reverse applies.
- Group Stealth: Each member makes their own check. If even one person fails, the whole group may be discovered.

### Fleeing

Fleeing is the most critical survival skill in Backrooms Walker:

**Chase Mechanic**: When you flee, the GM sets the starting "chase distance" (usually 3-8). You need to make consecutive Agility contest checks to gain distance.

| Chase Distance | Status |
|---------|------|
| 0 | Caught—enter melee |
| 1-3 | Dangerous—Entity can attack next turn |
| 4-6 | Contained—some distance gained |
| 7-9 | Safe—Entity at edge of sight |
| 10 | **Successfully escaped!** |

Each successful distance gain (your Agility check > Entity's Agility check): distance +2. Failure: distance -2.

### Almond Water Throw

Against specific Entities, throwing Almond Water can create a precious window to flee:

| Target Entity | Effect | Duration |
|---------|------|------|
| **Smilers** | Banished, retreats to Far | 1D3+1 rounds |
| **Hounds** | Banished, retreats to Medium | 1D3 rounds |
| **Other Entities** | Confused/stops action | 1 round |

Throwing Almond Water costs 1 AP, requires no attack check (auto-hit), but you must be within Medium range.

---

# Appendix A: Quick Reference

## Basic Check Formulas

| Check Type | Formula |
|---------|------|
| Attribute Check | D20 + Attribute Value vs DC |
| Skill Check | D20 + Attribute Value + Proficiency Bonus vs DC |
| Attack Check | D20 + Agility Value (melee) / Perception Value (ranged) vs DEF |
| Initiative Check | D20 + Agility Value + Perception Value |
| Will Resistance | D20 + Sanity Value + Willpower Proficiency Bonus vs DC |

## Difficulty Class Quick Reference

| DC | Difficulty | Success rate at Attribute 5 | Success rate at Attribute 5 + Expert |
|----|------|-------------|-----------------|
| 5 | Trivial | 100% | 100% |
| 8 | Easy | 90% | 100% |
| 10 | Average | 80% | 95% |
| 12 | Medium | 70% | 90% |
| 15 | Hard | 55% | 80% |
| 18 | Very Hard | 40% | 65% |
| 20 | Extreme | 30% | 55% |
| 25 | Nearly Impossible | 5% | 30% |

## Core Resources Quick Reference

| Resource | Formula | Initial Value |
|------|---------|--------|
| Hit Points (HP) | Physique × 2 + 5 | — |
| Defense (DEF) | 10 + Agility Value | — |
| Sanity Points (SP) | Sanity × 3 + 10 | — |
| Almond Water | — | 5 units |
| Calories | — | 10 units |
| Carry Capacity | Physique × 2 kg | — |
| Movement Speed | 6 + Agility Value m/round | — |
| Initiative Bonus | Agility Value + Perception Value | — |

## Healing Quick Reference

| Method | HP Recovery | SP Recovery | Notes |
|------|---------|---------|------|
| Almond Water | 1D6 | 1D4 | 1 unit each |
| Bandage | 2D6 | — | Removes bleeding |
| First Aid Kit | 3D6 | — | Removes bleeding + poisoning |
| Short Rest | 1D6 | — | 1 hour |
| Full Rest | 50% max HP | 1D4 | 8 hours, requires safe zone |
| Social Contact | — | 1~3 | Once per encounter |
| Recording/Journal | — | 1 | Once per day |

## Common Circumstance Modifiers

| Circumstance | Modifier |
|------|------|
| Well-lit | DC -2 |
| Dim/Faint light | DC +2 |
| With proper tools | DC -2 to -5 |
| Ample time | DC -3 |
| Rushed/Under pressure | DC +2 |
| Character already injured | DC +2 |

---

## Growth Summary: Eight Milestones

Backrooms Walker does not use a level system. Characters grow through **Milestones**—important moments in life. For full rules see Volume II of the GM Rulebook; the table below is a quick reference for players:

| # | Milestone | Trigger Condition | Growth Reward |
|---|--------|---------|---------|
| 1 | First Awakener | Create character | Initial allocation + Background ability |
| 2 | Survivor | Survive first crisis | 1 skill: Untrained → Trained |
| 3 | Explorer | First entry into a new Level | +1 any Attribute |
| 4 | Adaptor | Survive over a month | 1 skill → Expert |
| 5 | Knower | Master a Level/Entity secret | +1 Attribute + 1 skill tier-up + **Knowledge Value +1** |
| 6 | Guardian | Save or protect others | 1 skill → Expert + permanent ally at outpost |
| 7 | Awakened | Understand the nature of the Backrooms | +1 Attribute (can exceed cap of 10) + unique ability |
| 8 | Legend | Find the exit/Final choice | Ending reward (depends on your choice) |

> The power curve is deliberately flat: three attribute points and two Expert tiers across the entire campaign—you will be noticeably more capable, but will not become a superhero.

---

## Trade Price Reference

Almond Water is the common currency of the Backrooms. The table below shows common exchange rates at BNTG/M.E.G. outposts (actual prices are determined by the GM and Level supply and demand):

| Item | Buy Price (Almond Water) | Sell Price (Almond Water) |
|------|----------------|----------------|
| Almond Water (1 unit) | 1 | 1.5 |
| Canned Food | 0.5 | 1 |
| Bandage (5 uses) | 1 | 2 |
| Flashlight | 1 | 2 |
| Machete | 2 | 4 |
| Rare Level Intel | 3-5 | — |
| Complete Level Map | 5-10 | — |

> For detailed item values and rarity, see the Item Compendium.

---

# Appendix B: Glossary

| Traditional Chinese Term | Abbreviation | Description |
|-------------|------|------|
| The Backrooms | — | The game's main world—a parallel dimensional space made of infinite Levels |
| Noclip (phase through) | — | The act of phasing through reality into the Backrooms (from the gaming term Noclipping) |
| Level | — | Independent dimensional pockets within the Backrooms, each with unique structure and rules |
| Almond Water | — | The most important resource in the Backrooms—healing, Sanity recovery, banishing Entities, trade |
| Entity | — | Non-human existence in the Backrooms—environmental threats rather than killable monsters |
| Hounds | — | Quadruped predators that hunt in packs in dark Levels |
| Smilers | — | Entities that only appear in darkness—wearing an overly large smile on their faces |
| Skin-Stealers | — | Entities that disguise as humans and blend into crowds—hard to identify |
| Partygoers | — | A threat unique to Level 4—using excessive friendliness as a trap |
| The Lost | — | Former humans with zero Sanity—wandering eternally through the Levels |
| Wanderer | — | A general term for all humans surviving in the Backrooms |
| Major Explorer Group | M.E.G. | The largest human organization—providing intel, trade, and medical aid |
| Backrooms Nonprofit Trade Group | BNTG | Cross-Level trade organization—everything has a price |
| Outpost | — | Fixed safe zones established by outposts |
| Hit Points | HP | A character's physical health value |
| Sanity Points | SP | A character's mental health value |
| Defense | DEF | The target value Entities must exceed when attacking a character |
| Difficulty Class | DC | The target value a check must reach |
| Action Points | AP | Action resource available each round in combat |
| Game Master | GM | The game host responsible for describing the world, playing NPCs, and adjudicating actions |

---

> **The Player Rulebook ends here.**
> 
> Take this rulebook and your Character Sheet, and step into the Backrooms. Remember the first rule: do not panic. The second rule: start walking. Keep walking. If you stop for too long—you begin to feel this place is normal. That is the most dangerous part.
> 
> Good luck, Wanderer. You may need it.
