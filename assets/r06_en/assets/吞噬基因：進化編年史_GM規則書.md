# Devour Gene: Chronicle of Evolution — GM Rulebook

> **Version:** v1.0
> **Intended Audience:** Game Master (GM)
> **Core Concept:** This document contains the full content of the Player Rulebook, plus GM-exclusive behind-the-scenes mechanics, monster data, encounter design guidance, worldview setting, and scenario guidance. The GM only needs to read this one document to run the game.

---

## Table of Contents

**Part One: Basic Rules (same as the Player Rulebook)**
1. [System Overview](#i-system-overview)
2. [Core Dice System](#ii-core-dice-system)
3. [Five Attributes](#iii-five-attributes)
4. [Base Forms](#iv-base-forms)
5. [Character Creation](#v-character-creation)
6. [Evolution Tree System](#vi-evolution-tree-system)
7. [Evolution Points and Costs](#vii-evolution-points-and-costs)
8. [Humanity Value System](#viii-humanity-value-system)
9. [Combat Rules](#ix-combat-rules)
10. [Absorption System](#x-absorption-system)
11. [Equipment and Items](#xi-equipment-and-items)

**Part Two: GM-Exclusive Content**
12. [Worldview Setting](#xii-worldview-setting)
13. [Complete GM Check and DC Guide](#xiii-complete-gm-check-and-dc-guide)
14. [Monster Design and Behavior AI](#xiv-monster-design-and-behavior-ai)
15. [Encounter Design and Difficulty Balance](#xv-encounter-design-and-difficulty-balance)
16. [Scenario Run Guidance](#xvi-scenario-run-guidance)
17. [Complete Special Systems Rules](#xvii-complete-special-systems-rules)
18. [Complete Evolution Node Catalog](#xviii-complete-evolution-node-catalog)
19. [Optional Rules and Variants](#xix-optional-rules-and-variants)
20. [Quick Reference Tables](#xx-quick-reference-tables)

---

# Part One: Basic Rules

## I. System Overview

### 1-1 What is Devour Gene: Chronicle of Evolution?

"Devour Gene: Chronicle of Evolution" is a tabletop role-playing game (TRPG) whose core mechanic is "evolution through absorption." In this world, living beings possess the ability to absorb defeated enemies and acquire their traits. Players do not grow stronger by leveling up—instead they grow stronger through continuous evolution, but each evolution may cause them to drift away from their original form.

### 1-2 Core Features

| Feature | Description |
|---|---|
| **No Class System** | Abilities come from Evolution choices, not class labels |
| **No Level System** | Strength depends on the quantity and quality of accumulated Evolution Nodes |
| **No Fixed Skill Tree** | Every Evolution Tree is unique |
| **Growth by Absorption** | After defeating enemies, you can absorb traits to unlock new Evolution directions |
| **Identity** | Evolution has a cost—Humanity Value gradually drains away |

### 1-3 Player Count

This system is designed by default to support a **1 Player + 1 GM** solo mode, and is also fully compatible with 2–5 player multiplayer mode.

### 1-4 What Does the GM Need to Prepare?

| Item | Description |
|---|---|
| This Rulebook | The document you are currently reading |
| Scenario files | .md or .yaml files in the scenarios/ directory |
| Monster/NPC data | Character sheet collections in sheets/ |
| A standard set of TRPG dice | d4, d6, d8, d10, d12, d20 |
| Notepad | To record players' Evolution Trees, Humanity Value changes, and plot clues |

---

## II. Core Dice System

### 2-1 Basic Check

**Roll Formula:** d20 + Attribute Value ≥ Difficulty Level (DC) → Success

The Attribute Value is used directly as a bonus (no need to calculate a derived modifier).

### 2-2 Difficulty Level Table

| Difficulty | DC Range | Description | Example |
|---|---|---|---|
| **Trivial** | 5-9 | Almost impossible to fail | Running on flat ground, lifting a light object, remembering a familiar route |
| **Normal** | 10-14 | An ordinary person has a 50% chance of success | Climbing a rope, persuading a neutral NPC, tracking obvious footprints |
| **Hard** | 15-19 | Requires some expertise or talent | Disarming a trap, tracking in a heavy storm, negotiating a major deal |
| **Very Hard** | 20-24 | Even experts find it tricky | Climbing a cliff face, breaking a magic seal, persuading a sworn enemy |
| **Epic** | 25-29 | A realm beyond ordinary humans | Catching a flying arrow with one hand, walking on lava, persuading a king to abdicate |
| **Legendary** | 30+ | A near-mythical achievement | Tearing down a city wall bare-handed, conversing with deities, altering the laws of nature |

### 2-3 Critical Success and Critical Failure

| Roll Result | Name | Effect |
|---|---|---|
| **Natural 20** | Critical Success | Automatic success, plus an extra benefit |
| **Natural 1** | Critical Failure | Automatic failure, possibly accompanied by negative consequences |

### 2-4 Advantage and Disadvantage

| State | Rule |
|---|---|
| Advantage | Roll 2d20, take the higher |
| Disadvantage | Roll 2d20, take the lower |

When Advantage and Disadvantage are both present, they cancel out (reverting to 1d20).

### 2-5 Contest Check

Both sides each roll d20 + their corresponding Attribute Value; the side with the higher result wins. On a tie, the status quo is maintained.

### 2-6 Team Check

Designate one primary performer to make the check; each assisting teammate whose relevant Attribute is ≥ 4 grants +2 (maximum +6).

---

## III. Five Attributes

| Attribute Name | Abbr. | Meaning | Primary Effects |
|---|---|---|---|
| **Strength** | LIL | Physical attack power and carrying capacity | Melee damage, Encumbrance limit, breaking obstacles |
| **Agility** | MJ | Speed and flexibility | Initiative, evasion, movement distance, precise manipulation |
| **Constitution** | TZ | Vitality and resistance | HP maximum, poison resistance, fatigue recovery |
| **Perception** | GZ | Observation and reaction ability | Detecting traps, tracking, preemptive strike, identifying weaknesses |
| **Will** | YZ | Mental power and evolution control | Controlling evolution direction, resisting mental attacks, maintaining self-awareness |

### Derived Values

| Derived Value | Calculation Formula |
|---|---|
| HP | Constitution (TZ) × 5 |
| Max Energy | Constitution (TZ) + Will (YZ) |
| Max Evolution Capacity | 10 + Constitution (TZ) + Will (YZ) |
| Initiative | Agility (MJ) + 1d20 |
| Movement Speed | Agility 1-3→4 squares, 4-6→5 squares, 7-9→6 squares, 10-12→7 squares, 13-15→8 squares, 16+→9 squares |
| Defense Value (Player) | 10 + Agility (MJ) |
| Defense Value (Monster) | Set according to the Scenario tier (see Section IX Defense-by-Tier table: Minion 14-22 / Elite 18-24 / Boss 22-27 / Final Boss 28-32) |

---

## IV. Base Forms

| Base Form | Strength | Agility | Constitution | Perception | Will | Talent |
|---|---|---|---|---|---|---|
| Human | 3 | 3 | 3 | 4 | 5 | Adaptability: Evolution cost -1 |
| Beast | 5 | 4 | 4 | 3 | 2 | Wild Instinct: Advantage on Perception (GZ) checks in combat |
| Insect | 1 | 5 | 2 | 5 | 3 | Multiple Organs: Can activate two Organ Nodes simultaneously |
| Plant | 2 | 1 | 6 | 3 | 4 | Photosynthesis: Recover 1d4 HP each turn while stationary |
| Inorganic | 4 | 1 | 7 | 2 | 3 | Painless: Immune to poison and pain effects |
| Hatchling Dragon | 6 | 3 | 5 | 4 | 4 | High Origin: Node effects +20%, cost ×1.5 |

---

## V. Character Creation

### Step 1: Choose an Origin Form
### Step 2: Decide on a Background (10 options, each with a starting bonus)
### Step 3: Attribute Allocation (8 free points, no single attribute starts above 10)
### Step 4: Choose a Root Node (3 options per form)
### Step 5: Set your Evolution Vision
### Step 6: Your Forbidden Evolution (refusing Forbidden Evolution grants 1 extra Evolution Point per Scenario)

(See Player Rulebook Section V for details)

---

## VI. Evolution Tree System

### Five Node Types

| Node Type | Description | Humanity Value Reduction |
|---|---|---|
| Attribute Node | Permanently increases Attribute Value | 0 |
| Passive Node | A passive ability that is permanently in effect | -1 |
| Active Node | A skill usable in combat | -1 |
| Organ Node | Unlocks a new body part or organ | -4 |
| Form Node | Changes the base form—the most significant evolution | -8 |

### Evolution Conflict

| Conflict Rule | Description |
|---|---|
| Type Conflict | Within a series, only one branch may be chosen |
| Form Conflict | A Form Node resets the conflicting old nodes (Evolution Points are not refunded) |
| Capacity Limit | Total node count ≤ 10 + Constitution (TZ) + Will (YZ) |

(See Section XVIII for the complete node list)

---

## VII. Evolution Points and Costs

| Node Type | Evolution Point Cost | Biomass Requirement |
|---|---|---|
| Attribute Node | 2-5 | None |
| Passive Node | 2-4 | None |
| Active Node | 2-5 | Few exceptions |
| Organ Node | 3-5 | 2-6 |
| Form Node | 5 | 5-15 |

Biomass is collected from defeated enemies (Small 1 / Medium 2-3 / Large 4-5 / Giant 6-10 / BOSS 10+), with a 3-day shelf life.

---

## VIII. Humanity Value System

Starts at 100. Evolution reduces Humanity Value: Attribute Node 0, Passive -1, Active -1, Organ -4, Form -8.

| Humanity Value | Stage | Effect |
|---|---|---|
| >70% | Humanoid | Normal social interaction |
| 40-70% | Mixed | Disadvantage on social checks |
| 10-40% | Aberrant | NPCs fear/hostile, cannot enter human settlements |
| <10% | Monster | Not bound by social rules |

(See Player Rulebook Section VIII for details)

---

## IX. Combat Rules

### Action Points (3 per turn)

| Action | Cost |
|---|---|
| Normal Attack | 1 |
| Evolution Skill | 1-3 |
| Move | 1 |
| Defend (halve damage) | 1 |
| Observe / Identify Weakness | 1 |
| Absorb Attempt | 2 |
| Forced Evolution | 3 |
| Use Item | 1 |

### Energy System

- Max Energy = Constitution (TZ) + Will (YZ)
- Recover 2 Energy per turn
- Low-tier skills 1-2 Energy, mid-tier 3, high-tier 5, ultimate all

### Attack and Damage

- Melee Attack: d20 + Strength (LIL) vs Defense Value
- Ranged Attack: d20 + Agility (MJ) vs Defense Value
- Player Defense Value = 10 + Agility (MJ)
- Monster Defense Value = Set according to the Scenario tier (see "Defense and Attack by Tier" table below), keeping hit rates reasonable across all stages
- Melee Damage: 1d6 + Strength (LIL)
- Ranged Damage: 1d4 + Agility (MJ)

#### Defense and Attack by Tier Table (for Monsters, v1.1 balance revision)

Monsters do not use the players' fixed Defense formula. Their Defense and Attack bonus are set according to the "recommended tier" of the Scenario they belong to, ensuring players hit roughly 60-75% and monsters hit same-tier players roughly 45-55% across all stages. If used in a higher-tier scene, each tier above adds +2 Defense and +2 Attack bonus.

| Tier (Scenario) | Minion Defense / Attack Bonus | Elite Defense / Attack Bonus | Boss Defense / Attack Bonus | Final Boss Defense / Attack Bonus |
|---|---|---|---|---|
| S1 (0-5 nodes) | 14-15 / +4~+5 | 16-17 / +5~+6 | 19-20 / +6~+7 | — |
| S2 (3-8 nodes) | 15-16 / +5~+6 | 18-19 / +6~+7 | 20-21 / +7~+8 | — |
| S3 (6-12 nodes) | 17-18 / +6~+7 | 21-22 / +8~+9 | 23-24 / +9~+10 | — |
| S4 (10-15 nodes) | 19-20 / +8~+9 | 23-24 / +10~+11 | 25-26 / +11~+12 | 28-30 / +14~+16 |
| S5 (13-20 nodes) | 21-22 / +9~+10 | 23-24 / +11~+12 | 25-27 / +12~+14 | 30-32 / +16~+18 |

> A monster's Attack bonus is the "+X" after its attack die (e.g. "Bite 1d4+X"). The GM may fine-tune by ±2 based on actual player values (see 15-4 Dynamic Adjustment).

### Status Effects

| Status | Effect |
|---|---|
| Poisoned | 1d4 poison damage per turn, lasts 3 turns |
| Burning | 1d6 fire damage per turn, lasts 2 turns |
| Paralyzed | Lose all actions for 1 turn |
| Frozen | Movement Speed halved, 2 turns |
| Stunned | Disadvantage on all checks, 1 turn |
| Bleeding | 1d4 damage per turn, lasts until bandaged |
| Petrified | Cannot act but damage resistance +5, 1 turn |
| Feared | Cannot approach the source, Disadvantage on attacks |
| Blinded | Disadvantage on attack and Perception checks |
| Silenced | Cannot use skills that require sound |
| Hidden | Enemies must make a Perception (GZ) check contested against the target's Agility (MJ) to detect them; while undetected, attacks against the hidden target have Disadvantage and the hidden target's attacks against them have Advantage. Taking an active attack, being hit, using a sound-requiring skill, or being exposed to unobstructed sight ends Hidden |

### Spatial Combat and Area Rules

The GM uses a grid map to position monsters. Rules are exactly the same as Player Rulebook 9-7:

- **Distance**: Melee 1 square / Medium 2-3 squares / Long 4-6 squares / Extreme 7-10 squares
- **Area Templates**: Cone N squares (facing a sector), Circle / Radius N squares (centered on a point), Line (a 1-square-wide strip), Burst (radius 1 square, instant expansion)
- **Opportunity Attack**: When an enemy voluntarily leaves your melee range, you may make one free melee attack (once per turn); you are not subject to opportunity attacks while in "Defend"
- **Difficult Terrain**: Each 1 square of movement costs 2 squares of movement
- **Passing Through Squares**: May pass through allied squares (cannot stop there); passing through enemy squares requires Agility (MJ) DC 14, failure means stopping in place and taking 1d4 damage; Giant size cannot be passed through

---

## X. Absorption System

| Target State | Absorption DC (Will) |
|---|---|
| Already Dead | 15 |
| Near Death (HP < 10%) | 10 |
| Paralyzed / Incapacitated | 8 |
| Voluntary | Automatic success |

On successful absorption, you gain a "Trait Sample"—choose 1 of 3 Evolution directions to unlock; the others are permanently closed.

---

## XI. Equipment and Items

| Humanity Stage | Usable Equipment |
|---|---|
| Humanoid (>70%) | All human equipment |
| Mixed (40-70%) | Weapons, partial armor (requires modification), accessories |
| Aberrant (10-40%) | Simple weapons, partial accessories |
| Monster (<10%) | Body is the weapon |

(See Player Rulebook Section XI for the complete equipment table and consumables table)

---

# Part Two: GM-Exclusive Content

---

## XII. Worldview Setting

### 12-1 Creation Myth — "The First Devourer"

In an era long before human civilization was born, the world was ruled by a being known as the "**Void Abyss Worm**." This creature had but one instinct: to devour. It devoured rock, it devoured seawater, it devoured the sky—and from each devouring it gained a new form.

The Void Abyss Worm eventually devoured itself; each fragment of it became a new life. These lives inherited its core ability—absorption and evolution. This is why every living being in this world possesses the potential to evolve.

But most creatures evolve extremely slowly, requiring thousands of years. Until humans appeared—humans possess the purest "Void Abyss fragments," making their evolution far faster than any other species. In other words, the ability to evolve is not a gift, but the legacy of an ancient monster.

### 12-2 Current State of the World — "Fission Era"

The current world is in a turbulent period known as the "Fission Era." Key features:

| Element | Current State |
|---|---|
| **Level of Civilization** | Transition from medieval to Renaissance. A few highly advanced ancient ruin technologies exist (evolution laboratories, gene forges), but modern society cannot replicate them |
| **Population Ratio** | About 5% of the population are "Awakened Evolvers" (those who can actively control evolution). The remaining 95% are ordinary people, who also have evolutionary potential but have never Awakened |
| **Attitude of Ordinary People** | More fear than worship. Evolvers are seen as destabilizing factors. Remote villages drive out Evolvers; large cities have "Evolver enclaves" |
| **Main Conflicts** | ① Evolvers vs Ordinary People (existential anxiety) ② Rapid-Evolution faction vs Evolution-Control faction (a struggle over direction) ③ Human forces vs Mutant Beast Tides (external threat) |

### 12-3 Three Factions

#### Faction One: Ultimate Evolution Cult

| Item | Content |
|---|---|
| **Ideology** | "Evolution is the only truth. The ultimate form is god." The Cult believes the fragments of the Void Abyss Worm are the key to divinity, and the end of evolution is to become a new creator god |
| **Base** | Abyssal Sanctum—a city built inside the fossil of a giant Void Abyss Worm |
| **Style of Operation** | Radical. Encourages unlimited evolution, conducts extensive human experimentation. Does not care about Humanity Value—they believe "humanity" is the shackle of evolution |
| **Attitude Toward Players** | Attempts to recruit. If the player refuses, they are seen as "weaklings wasting their talent" and may become enemies |
| **Key Figure** | "The Thousand-Faced Bishop"—said to have evolved over 100 times; no one knows what his original form was |

#### Faction Two: Humanity Guardians

| Item | Content |
|---|---|
| **Ideology** | "Evolution is a tool, not a goal. We are human—we cannot become monsters." The Guardians believe evolution should be strictly controlled; any Evolver with Humanity Value below 40% should be quarantined or "purified" |
| **Base** | White Tower City—a large city built and managed entirely by humans (non-Evolvers) |
| **Style of Operation** | Conservative, exclusionary. Wary of Evolvers, but uses evolution technology to defend against external threats. Possesses a specialized "Purification Force" for combating evolved creatures |
| **Attitude Toward Players** | If Humanity Value remains high (>60%), they can become allies. If Humanity Value is too low, they are seen as a threat |

| **Key Figure** | "Purifier Marshal" Elena—a rare "Anti-Evolver" (a special individual possessing the ability to suppress other Evolvers) |

#### Faction Three: Symbiosis Accord (The Symbiosis Accord)

| Item | Content |
|---|---|
| **Philosophy** | "Evolution and humanity are not opposed. The true answer is—learn to coexist with your evolution." The Symbiosis Accord takes a third path: acknowledging the necessity of evolution, but advocating to control it through training, ritual, and technology |
| **Base** | Balance Academy—an institution that is half-academic, half-temple, teaching "Evolution Meditation" and "Humanity Maintenance" techniques |
| **Operating Style** | Neutral, academic. Studies the nature of evolution. They discovered the secret of the "Void Abyss Fragment" and are searching for a way to control the fragment |
| **Attitude Toward Players** | Welcomes all Evolvers willing to learn. Provides free Humanity Value (HV) restoration service (per week +2) |
| **Key Figure** | "The Inheritor" Alden—a legendary old Evolver who has lived 300 years, with Humanity Value (HV) always maintained above 80% |

### 12-4 Geographic Map

| Region | Description | Danger Level | Special Rules |
|---|---|---|---|
| **Abyssal Rift** | The place where the Void Abyss Worm fell; the earth split open into an abyss 300 kilometers long. At the bottom of the rift lies the shrine of the Ultimate Evolution Cult. The radiation in the rift accelerates evolution (for each day spent here, automatically gain 1 Evolution Point (EP)—but Humanity Value (HV) -1d4) | ★★★★★ | Accelerated evolution, Humanity Value (HV) loss |
| **White Tower Plains** | A vast plain surrounding White Tower City. The heartland of human civilization. Farmlands, villages, trade routes. Evolvers here must register and wear identity marks | ★★ | Frequent Humanity Value (HV) checks, public display of evolution abilities forbidden |
| **Corrupted Wilderness** | Land polluted by ancient experiments. Wild flora and fauna mutate here at an astonishing rate. An excellent place for Evolvers to hunt and absorb—but also the lair of Mutant Beasts | ★★★★ | +1 enemy count per encounter battle |
| **Gene Forge Ruins** | Ruins of an experimental facility from an ancient civilization. Inside are well-preserved evolution devices—including gene-modification vats and Biomass synthesizers. Multiple factions contest control of this place | ★★★ | Resources may be paid here to reroll a closed evolution direction (limited to 1 per Scenario) |
| **Balance Academy Island** | An island in a lake, the headquarters of the Symbiosis Accord. The only neutral zone. The academy holds the largest evolution-knowledge library on the continent | ★ | Accelerated Humanity Value (HV) recovery (per week +3), can learn evolution control techniques |
| **Border Void** | The edge of the known world. Here the laws of physics begin to collapse. It is said that the remains of ancient Evolvers lie in the void—each remains a potential source of an Ultimate Form Node | ★★★★★ | Each turn, Will (YZ) check DC 15; failure results in Humanity Value (HV) -1d4 |

### 12-5 Key Historical Events

| Time | Event | Impact |
|---|---|---|
| **Approx. 10,000 years ago** | The Void Abyss Worm devoured itself and collapsed | All life gained evolution potential |
| **Approx. 3,000 years ago** | The first "Awakened Evolvers" appeared among humans | Human civilization began to utilize evolution technology, establishing an ancient gene civilization |
| **Approx. 1,000 years ago** | The Gene War—the ancient civilization was destroyed due to loss of control over evolution | High-tech facilities such as the Gene Forge were abandoned; civilization regressed to medieval levels |
| **500 years ago** | The Ultimate Evolution Cult was founded | Radical evolutionists became organized |
| **300 years ago** | White Tower City was established, the Humanity Guardians rose | A force to counter the Cult emerged |
| **150 years ago** | The Symbiosis Accord was founded | A moderate path was introduced |
| **50 years ago** | The Abyssal Rift expanded—the rift grows by 1 meter each year | Panic spread; more believed the end was near |
| **Now** | The Fission Era—the number of Evolvers surged, the three factions stand in confrontation | The players' story begins here |

### 12-6 Faction Reputation System

The Three Factions, beyond their worldview setting, also provide a quantifiable reputation mechanic. Players can accumulate reputation through actions, unlocking the exclusive rewards of each faction.

**Reputation Value Range:** -10 to +10 (negative values represent hostility, positive values represent being trusted).

**Joining Requirements:**

| Faction | Method of Joining |
|---|---|
| Ultimate Evolution Cult | Actively accept the Cult's recruitment quests; Humanity Value (HV) unrestricted (the Cult welcomes any degree of evolution) |
| Humanity Guardians | Apply to White Tower City when Humanity Value (HV) ≥ 50%, pass the loyalty trial |
| Symbiosis Accord | Visit Balance Academy Island, complete the "Evolution Meditation" initiation ritual (any Humanity Value (HV) acceptable) |

**Reputation Gain/Loss:**

| Action | Reputation Change |
|---|---|
| Complete that faction's quests | +1 to +3 (depending on difficulty) |
| Assist that faction's opposing forces | -2 to -4 |
| Maintain high Humanity Value (HV) in that faction's territory (Cult opposite: maintain low Humanity Value (HV)) | +1 / Scenario |
| Publicly violate that faction's core philosophy | -3 to -5 |

**Reputation Reward Tiers:**

| Reputation | Ultimate Evolution Cult | Humanity Guardians | Symbiosis Accord |
|---|---|---|---|
| +3 | Free Form Node discount (cost -1) | Rare equipment supply | Free Humanity Value (HV) restoration (per week +3) |
| +5 | Advanced evolution skill instruction | Purification Unit support (summon 1 Minion in combat) | Evolution control technique (Forced Evolution side effect -1) |
| +8 | Cult Relic (Legendary accessory) | White Tower City citizenship (free entry to all human strongholds) | Heart of Balance (special Passive Node) |

> Reputation does not recover automatically; switching factions reduces the old faction's reputation by -3.

---

## Thirteen. GM Checks and Complete DC Guide

### 13-1 DC Setting Framework

When a player attempts an action, the GM needs to set a DC. The following is a decision framework:

```
This action is...
├─ Trivial (DC 5-9): No training needed; anyone has over 80% success rate
├─ Ordinary (DC 10-14): An ordinary person has a 50% chance
├─ Difficult (DC 15-19): Requires relevant experience or talent
├─ Very Difficult (DC 20-24): Expert-level challenge
├─ Epic (DC 25-29): Beyond human limits
└─ Legendary (DC 30+): Nearly impossible
```

### 13-2 DC Situation Table by Attribute

#### Strength (LIL) Check DC

| DC | Situation |
|---|---|
| 8 | Push open a heavy door |
| 12 | Lift an adult |
| 15 | Break wooden obstacles, pry open an iron fence bare-handed |
| 18 | Drag a horse cart, shatter a stone wall |
| 22 | Wrestle a giant creature to the ground, lift a boulder |
| 25 | Tear apart a steel gate bare-handed |
| 30 | Shake the foundation of a building |

#### Agility (MJ) Check DC

| DC | Situation |
|---|---|
| 8 | Leap a 2-meter-wide ditch |
| 12 | Climb rough cliff walls |
| 15 | Run along narrow eaves, dodge incoming arrows |
| 18 | Walk a rope in a storm, land precisely from a height |
| 22 | Weave through collapsed buildings, dodge consecutive traps |
| 25 | Dodge between blades |
| 30 | Dodge lightning |

#### Constitution (TZ) Check DC

| DC | Situation |
|---|---|
| 8 | Run 1 km without rest |
| 12 | Endure extreme heat/cold for 1 hour |
| 15 | Resist potent poison, hold breath for minutes before drowning |
| 18 | Operate in a high-radiation zone for 10 minutes |
| 22 | Operate near lava, resist fatal disease |
| 25 | Briefly survive in a vacuum |
| 30 | Cross a magma river with one's body |

#### Perception (GZ) Check DC

| DC | Situation |
|---|---|
| 8 | Notice an obvious trap |
| 12 | Hear distant conversation, track obvious footprints |
| 15 | Find a hidden secret door, identify a disguised enemy |
| 18 | Hear a specific sound in a storm, track footprints from a day ago |
| 22 | Perceive nearly perfect invisibility, identify illusion |
| 25 | Lock onto a single target's weakness in a chaotic battlefield |
| 30 | See the essence of a soul |

#### Will (YZ) Check DC

| DC | Situation |
|---|---|
| 8 | Resist mild fear |
| 12 | Stay calm when threatened |
| 15 | Resist mental control, absorb a dead enemy |
| 18 | Avoid breaking under torture, resist powerful mental attacks |
| 22 | Maintain self-awareness against the side effects of form mutation |
| 25 | Refuse a god's command |
| 30 | Reclaim the self when consciousness is fully eroded |

### 13-3 Hidden DC Principle

The GM does not need to tell the player the DC every time. The following principles are for reference:

- **Perception-type Checks**: Always hide the DC. Players do not know how hard the trap is to find—only what they found (or didn't find)
- **Social-type Checks**: Usually hide the DC. Players do not know the NPC's true attitude
- **Physical-type Checks** (Strength/Agility): May reveal the DC. Players can usually judge the difficulty of the action
- **Absorption Checks**: Reveal the DC. Players know absorbing a dead enemy is harder than absorbing a near-dead one

### 13-4 Gradual Success

Not all checks are a binary "success/failure." The GM may adopt graduated results:

| Dice Result vs DC | Effect |
|---|---|
| 10+ below DC | Catastrophic failure—not only fails, but causes negative consequences |
| 5-9 below DC | Ordinary failure—failed to achieve the goal, but no extra loss |
| 1-4 below DC | Near success—failed to fully achieve, but made partial progress. GM may offer a remedy opportunity |
| Equal to or above DC | Success |
| 5+ above DC | Excellent success—effect exceeds expectations |
| 10+ above DC | Perfect success—achieves the maximum possible result + extra benefit |

---

## Fourteen. Monster Design and Behavior AI

### 14-1 Monster Templates

#### Minion Template (Grunts)

Minions are the "consumables" of combat—numerous, individually weak, defeatable in 1-2 turns.

| Attribute | Value Range |
|---|---|
| HP | 8-15 |
| Defense Value (DV) | Set per scene tier (see Section Nine Tier Defense and Attack Table): Minions 14-22 (S1 14-15 → S5 21-22), default design uses S1 baseline 15 |
| Attribute Value | Main attribute 4-5, others 1-3 |
| Attack | 1 type (melee 1d6 + 2 or ranged 1d4 + 2) |
| Absorbable | Basic Biomass: 1 |

**Minion Examples:**

| Name | HP | Defense | Attributes | Attack | Trait Sample Directions |
|---|---|---|---|---|---|
| Mutant Rat | 8 | 15 | MJ 5, GZ 3 | Bite 1d4+2, inflicts disease (Constitution DC 10) | ①Disease Resistance ②Night Vision ③Burrow Stealth |
| Spore Zombie | 12 | 14 | TZ 5, LIL 3, MJ 3 | Slam 1d6+4 | ①Poison Resistance ②Plant Affinity ③Enhanced Photosynthesis |
| Abyss Larva | 10 | 14 | LIL 2, MJ 4 | Acid Spray 1d4+2 mid-range | ①Acidic Saliva ②Heat Resistance ③Hardened Skin |
| Scrap Golem | 15 | 15 | LIL 4, TZ 6 | Charge 1d6+5 | ①Metallicize ②Strength Enhancement ③Magnetic Sense |

#### Elite Template (Elites)

Elite enemies are the core of combat—requiring 3-5 turns to defeat. They possess full attributes and limited skills.

| Attribute | Value Range |
|---|---|
| HP | 25-50 |
| Defense Value (DV) | Set per scene tier (see Section Nine Tier Defense and Attack Table): Elites 16-24 (S1 16-17 → S5 23-24), default design uses S1 baseline 17 |
| Attribute Value | Main attribute 6-8, others 3-5 |
| Attack | 2-3 types (including 1 low/mid-tier skill) |
| Absorbable | Biomass: 2-3; Trait Sample: 3 directions |

**Elite Examples:**

| Name | HP | Defense | Attributes | Skill | Trait Sample Directions |
|---|---|---|---|---|---|
| Abyss Stalker | 35 | 19 | LIL 6, MJ 7, GZ 5 | Claw Strike (1d8+3), Tail Sting (1d6+3+poison), Camouflage Stealth | ①Camouflage Skin ②Poison Gland ③Climbing Claw |
| Flame Stone Golem | 45 | 16 | LIL 7, TZ 8, MJ 4 | Heavy Strike (1d10+4), Flame Breath (mid-tier, cone 3 grids 2d6), Earth Rift (straight line forward) | ①Heat Resistance ②Elemental Gland (fire) ③Shock Impact |
| Mind Parasite | 28 | 17 | YZ 8, MJ 5, GZ 6 | Psychic Shock (2d6, Will DC 14 halved), Parasitic Control (can control one target for 1 turn) | ①Psionic Shield ②Mental Attack ③Will Enhancement |
| Mutant Thorn Tree | 50 | 16 | TZ 9, GZ 4, LIL 5, MJ 3 | Vine Bind (mid-range, Agility DC 14), Thorn Counter (1d4 when melee-attacked), Regeneration 2HP/turn | ①Plant Affinity ②Regeneration ③Vine Tentacle |

#### Boss Template (Bosses)

BOSS is the climax of combat—requiring 5-8 turns to defeat. Possesses full attributes, multiple skills, and phase changes.

| Attribute | Value Range |
|---|---|
| HP | 60-120 |
| Defense Value (DV) | Set per scene tier (see Section Nine Tier Defense and Attack Table): Boss 19-27 (S1 19-20 → S5 25-27), default design uses S1 baseline 20 |
| Attribute Value | Main attribute 8-12, others 4-7 |
| Attack | 4-5 skills (including 1-2 high-tier) |
| Phase Change | When HP drops to 50%, enters the second phase—gains new skills or changes behavior pattern |
| Absorbable | Biomass: 10+; Trait Sample: 5 directions (choose 2) |

**Boss Examples:**

| Name | HP | Defense | Description |
|---|---|---|---|
| Ancient Devourer | 100 | 20 | A mutant giant python that has lived a thousand years, having evolved multiple organs. Phase One: primarily physical attacks. Phase Two (HP<50%): activates mental abilities, performing Will attacks on all targets simultaneously |
| Rebellious Evolver | 80 | 20 | A former Symbiosis Accord scholar who chose unlimited evolution. Has now evolved beyond 20 nodes. Phase One: uses own evolution skills. Phase Two: Forced Evolution—temporarily activates a new Form Node |
| Void Abyss Fragment Avatar | 120 | 22 | An activated fragment of the Void Abyss Worm. Phase One: randomly uses the evolution skills of any creature present (ability copy). Phase Two: opens the "Void Domain"—all on field make a Will check DC 16 each turn; failure results in Humanity Value (HV) -1 |

### 14-2 Monster Behavior AI

The following is decision guidance for the GM controlling monsters, to keep monster behavior realistic and interesting:

#### Minion Behavior Logic

```
Minion turn begins:
├─ Near-dead ally nearby? → 50% chance to flee (Will DC 12)
├─ Isolated (no ally within 3 grids)? → Prioritize moving toward allies
├─ Can attack the weakest target? → Attack that target (Minions tend to attack those that look easy to defeat)
├─ Surrounded by multiple enemies? → Attempt to flee
└─ Otherwise → Attack the nearest target
```

#### Elite Behavior Logic

```
Elite turn begins:
├─ HP < 30% and no allies? → Consider fleeing (Will DC 14)
├─ Has usable skill and sufficient Energy (EN)? → Prioritize using skill
├─ Can attack a ranged/healing character? → Prioritize attacking the back row
├─ Has a near-dead ally? → 50% chance to protect ally (move in front of ally)
├─ Player using Defense? → Switch target (Elites can tell who is defending)
└─ Otherwise → Use the most effective attack
```

#### Boss Behavior Logic

```
Boss turn begins:
├─ HP drops to 50% threshold? → Trigger second phase
│   ├─ Activate new passive ability
│   ├─ Gain 1-2 new skills
│   └─ Recover 2d10 HP (symbolizing the strengthening of the "Second Form")
├─ Energy (EN) ≥ 5? → Use high-tier skill (BOSS does not conserve Energy (EN))
├─ Can attack multiple targets? → Prioritize area skill
├─ Player with lowest current HP in range? → Prioritize attack (BOSS targets the weak)
├─ Took heavy damage from same player last turn? → Turn to attack that player (revenge behavior)
└─ Detect player using a specific pattern (e.g., always defends then attacks)? → Change strategy to counter
```

### 14-3 Creating Custom Monsters

#### Quick Creation Formula

1. **Decide Tier**: Minion / Elite / Boss
2. **Set Theme**: What is this enemy's evolution theme? (poison, fire, ice, mental, physical…)
3. **Allocate Attributes**: Use values within the template range
4. **Derived Values**: HP = TZ×5 (Minions may be lower), Defense = per scene tier, see Section Nine Tier Defense and Attack Table (Minion 14-22 / Elite 16-24 / Boss 19-27 / Ultimate Boss 28-32), Energy (EN) = TZ+YZ
5. **Design Skills**: 1 (Minion) / 2-3 (Elite) / 4-5 (Boss) attack methods, at least 1 of which is an evolution skill
6. **Design Trait Sample**: If the player absorbs this enemy, what evolution directions can they gain? (3 options)

#### Balance Checklist

| Check Item | Minion | Elite | Boss |
|---|---|---|---|
| Average damage of a single attack | ≤ 10% of player HP | ≤ 20% of player HP | ≤ 30% of player HP |
| Total output per turn | ≤ 20% of player HP | ≤ 35% of player HP | ≤ 50% of player HP |
| Total HP | Defeatable within 2 turns | Defeatable within 4 turns | Defeatable within 7 turns |
| Number of special abilities | 0-1 | 2-3 | 4-6 |

---

## Fifteen. Encounter Design and Difficulty Balance

### 15-1 Encounter Composition Formula

Using 1 player as the baseline, adjust as follows for each additional player:

| Encounter Difficulty | 1 Player (Solo) | 2-3 Players | 4-5 Players |
|---|---|---|---|
| **Simple** | 2 Minions | 4 Minions | 6 Minions |
| **Ordinary** | 3 Minions or 1 Elite | 5 Minions or 1 Elite + 2 Minions | 7 Minions or 2 Elites |
| **Difficult** | 1 Elite + 1 Minion | 2 Elites | 1 Elite + 5 Minions or 3 Elites |
| **Lethal** | 1 Boss | 1 Boss + 2 Minions | 1 Boss + 1 Elite + 3 Minions |

### 15-2 Encounter Pacing

The recommended encounter configuration for a standard Scenario (about 3-4 hours):

```
Prologue Exploration (no combat or 1 Simple encounter)
  ↓
First Battle (Ordinary difficulty, 2-3 Minions)—player warm-up
  ↓
Exploration/Puzzle-solving/Social (about 30-45 minutes)—pacing change
  ↓
Second Battle (Difficult difficulty, Elite + Minion)—trial
  ↓
Plot Twist / Important Discovery
  ↓
Third Battle (Lethal difficulty, Boss battle)—climax
  ↓
Ending and Rewards
```

### 15-3 Solo Mode Balancing

The three most important adjustments in Solo Mode:

1. **Reduce Enemy Count**: All encounter enemy counts ×0.6 (round down, minimum 1)
2. **Provide Recovery Resources**: Before each battle, ensure the player has at least 1 healing potion
3. **NPC Companion System**: The GM may provide an NPC companion that does not participate in evolution to assist in combat. The companion uses simplified stats—HP 20, Defense 12, melee attack 1d6+2. The companion has only 2 Action Points (AP) per turn and cannot use evolution skills

### 15-4 Dynamic Difficulty Adjustment

Adjusting difficulty in real time during the game requires no announcement. The following techniques:

| Situation | Adjustment Method |
|---|---|
| Player too strong (kills Elite in 2 turns) | Next wave of enemies +2 HP, or reinforce with 1-2 Minions in the second turn |
| Player too weak (near death every turn) | Enemy damage -1d4, "coincidentally" there are environmental objects to use as cover |
| Single BOSS battle too easy | Trigger second phase at 50% HP, or summon 2 Minions |
| Single BOSS battle too hard | Have the BOSS "underestimate the opponent," choosing flashy attacks instead of lethal ones (e.g., using weaker skills instead of strongest skills) |

### 15-5 Reward Distribution Guide

| Encounter Type | Evolution Points (EP) | Biomass | Remnant Coins (coins) | Other |
|---|---|---|---|---|
| Simple Encounter | 1 | 1-2 | 5-10 | Minor consumables |
| Ordinary Encounter | 2 | 2-4 | 10-30 | Standard consumables |

| Hard Encounter | 3 | 4-7 | 30-60 | Rare Consumables |
| Lethal Encounter (BOSS) | 5 | 8-15 | 50-100 (incl. Absorption Crystal +50%) | Very Rare Consumables + Trait Samples (choose 2 of 5) |
| Complete Scenario | 3-5 | - | 20-50 | Special Story Reward (e.g., free Evolution Node) |

> **Remnant Coins Economy (v1.1 Balance Correction):** Monsters no longer have "no drops." Defeating enemies guarantees a fixed drop of Remnant Coins (Minion 5-10 / Elite 15-30 / Boss 50-100; see Player Rulebook 7-1). You can also sell surplus Biomass (3 coins/unit) and Equipment (50% of sale price) for coins. A standard Scenario can accumulate about 80-200 coins, enough to resupply 1-2 Rare pieces of equipment or a batch of consumables in town. Absorbed enemy corpses cannot be sold, but refined "Evolution Crystals" can be exchanged for an extra 50% Remnant Coins.

### 15-6 Random Encounter Table

When players explore mid-session or the GM needs to improvise filler, roll d20 to determine the encounter (choose the corresponding table by environment). In Solo Mode, multiply the number of enemies by ×0.6 (minimum 1).

> **Tier Scaling (v1.1 Balance Correction):** The table below is designed with S1 (0-5 nodes) as the baseline. If used in higher-tier scenarios (S2-S5), replace the monsters in the table with "same environment, higher tier" versions (e.g., S1's Mutant Rat → S3's Bio-mech-tier Minion). Their Defense Value and attack bonuses will automatically increase per Section Nine's "Tier Defense and Attack Table," ensuring hit rates remain reasonable at each stage. Principle: Minion/S1, Elite/S2-3, Boss/S4-5; the Ultimate Boss is limited to the S4-5 climax battle.

**Wilderness / Corrupted Wilderness (d20):**

| d20 | Encounter |
|---|---|
| 1-4 | 2 Minions (Mutant Rat / Spore Zombie) |
| 5-8 | 3 Minions |
| 9-11 | 1 Elite (Abyssal Stalker) |
| 12-13 | 1 Elite + 2 Minions |
| 14-15 | Environmental Hazard (Trap / Poison Swamp, requires Constitution DC 14) |
| 16-17 | Friendly NPC (can provide information or trade) |
| 18-19 | 1 Boss Prototype (Ancient Devourer Larva, HP 60) |
| 20 | Special: Discover a Biomass Vein (gain 5 Biomass) |

**Ruins / Laboratory (d20):**

| d20 | Encounter |
|---|---|
| 1-5 | 2 Minions (Scrap Golem) |
| 6-9 | 3 Minions + Auto-Defense Turret (ranged 1d8) |
| 10-12 | 1 Elite (Defense Array) |
| 13-14 | 1 Elite + 2 Minions |
| 15-16 | Puzzle / Archive (gain Evolution Knowledge, +1 Evolution Point) |
| 17-18 | Trapped Test Subject (can be released as an ally or absorbed) |
| 19-20 | 1 Boss (Prototype Ω) |

**City / White Tower Plains (d20):**

| d20 | Encounter |
|---|---|
| 1-6 | Peaceful Event (market, social) |
| 7-10 | Guardian Patrol (hostile if Humanity Value < 40%) |
| 11-13 | Cult Recruiter (tries to persuade you) |
| 14-16 | Thief / Rival Evolver (1v1 duel) |
| 17-18 | Caravan (trade opportunity) |
| 19-20 | Sudden Mutant Beast Attack (1 Elite) |

**Void / Frontier (d20):**

| d20 | Encounter |
|---|---|
| 1-5 | Will DC 15 Environment Check (failure: Humanity -1d4) |
| 6-9 | 2 Void Fluids |
| 10-12 | 1 Elite Void Creature |
| 13-15 | Ancient Evolver Remains (can be absorbed as a hint toward Ultimate Form) |
| 16-18 | 1 Boss (Abyssal Gatekeeper) |
| 19-20 | Void Abyss Shard Phenomenon (Will DC 20, success: all attributes +1) |

---

## Sixteen, Scenario Running Guide

### 16-1 Overview of the Five Scenarios

#### S1: Nest Awakening (Recommended Nodes 0-5)

| Item | Content |
|---|---|
| **Opening** | The player awakens in an underground nest, surrounded by the corpses of dead kin. Memory is a complete blank. The only instinct: climb upward. |
| **Scene Structure** | ①Awakening (wake up, feel the Evolution impulse, choose a Root Node) → ②The First Meal (encounter a Mutant Rat, the choice of first Absorbing or killing) → ③A Voice in the Dark (meet another surviving Evolver—NPC companion or rival) → ④The Exit (defeat the gatekeeping Elite, escape the nest) → ⑤The Surface (first sight of the outside world, join or encounter a faction) |
| **Core Conflict** | Survival Instinct vs. Identity Question (Who am I?) |
| **Key NPCs** | Another surviving Evolver (can become a companion or rival), a faction representative on the surface |
| **Possible Endings** | ①Escape alone and set out on a journey to find your memory; ②Alliance with another Evolver; ③Absorb the gatekeeper after defeating it—paying a Humanity Value cost for power |

#### S2: Lab Escape (Recommended Nodes 3-8)

| Item | Content |
|---|---|
| **Opening** | The player discovers they are a test subject. The laboratory is a massive underground genetic research facility, managed by the remnants of a pre-civilization AI. The AI's goal: collect data on all Evolution paths. |
| **Scene Structure** | ①The Cage (discover the cage and experiment logs, learn your origin) → ②The Recycling Zone (other test subjects—some want to cooperate and escape, some have already lost control and become monsters) → ③The Core Laboratory (face the AI, choose whether to destroy it or exploit its knowledge) → ④The Breakthrough (fight the Elite guards, escape the laboratory) |
| **Core Conflict** | Freedom vs. Knowledge (the AI can provide complete information on Evolution paths—but the cost is staying in the laboratory forever) |
| **Key NPCs** | The AI "Guardian" (neither friend nor foe, purely rational), Mutant Test Subjects (may become allies or enemies) |
| **Possible Endings** | ①Destroy the AI and escape (gain a large number of Evolution Points but lose the knowledge); ②Leave after trading with the AI (gain Evolution Codex information but help the AI conduct one final experiment); ③Absorb the AI's core—gain the "Mechanical Fusion" special Evolution direction |

#### S3: Evolution War (Recommended Nodes 6-12)

| Item | Content |
|---|---|
| **Opening** | The Ultimate Evolution Cult and the Humanity Guardians face off before the Gene Forge Ruins. Both sides want to control this ancient facility that can accelerate Evolution. The player must choose a faction—or become a spoiler. |
| **Scene Structure** | ①Faction Contact (representatives of both sides approach the player, each offering tempting terms) → ②Preliminary Mission (the chosen faction's trial mission) → ③The Forge Contest (three-way melee—the player's faction, the opposing faction, and the Forge's auto-defense system) → ④The Forge Core (control the Forge—gain a powerful Evolution opportunity) |
| **Core Conflict** | Choice and Consequence—each faction's path is reasonable but comes with a price |
| **Key NPCs** | Cult Emissary (offers power but demands lowering Humanity Value), Guardian Commander (offers equipment and resources but restricts Evolution), Accord Observer (offers a third path but does not join combat) |
| **Possible Endings** | ①Help the Cult control the Forge (gain 5 Evolution Points + a free Form Node but Humanity Value -10); ②Help the Guardians control the Forge (gain Rare equipment + Humanity Value +5); ③Shut down the Forge so neither side gets it (gain Accord favor + the special passive node "Heart of Balance") |

#### S4: Apex of the Food Chain (Recommended Nodes 10-15)

| Item | Content |
|---|---|
| **Opening** | The player steps into the "Arena"—a continent sealed off by ancient power. There is only one rule: only the strongest Evolver can leave alive. All Evolvers trapped in the Arena hunt and absorb one another. |
| **Scene Structure** | ①Entry (enter the Arena, discover the rule—cannot leave until becoming the "Apex") → ②Hunter and Prey (encounter other Evolvers—you may become the hunter, or the prey) → ③Alliance and Betrayal (temporary alliances are common in the Arena—but betrayal is even more common) → ④Semifinals (defeat the Arena's regional overlord) → ⑤Finals (only you and one other strongest Evolver remain—the final showdown) |
| **Core Conflict** | Competition vs. Empathy (not all Evolvers in the Arena are villains—some are trapped here just like you) |
| **Key NPC** | The "Champion"—the winner of the previous Arena, who has evolved over 20 nodes. He voluntarily stays in the Arena awaiting a worthy opponent. |
| **Possible Endings** | ①Leave after defeating the Champion (gain the most Evolution Points); ②Join forces with the Champion to break the Arena's seal (requires a combined Will check DC 22; success liberates all Evolvers in the Arena); ③Absorb the Champion—gain an Ultimate Form node but Humanity Value drops below 10% |

#### S5: The Final Evolution (Recommended Nodes 13-20)

| Item | Content |
|---|---|
| **Opening** | The expansion of the Abyssal Rift is unstoppable. In a month, the Rift will devour White Tower City and the entire plains. There is only one way to stop the Rift—descend to its deepest point, face the residual consciousness of the Void Abyss Worm, and make the "Final Choice." |
| **Scene Structure** | ①Descent into the Rift (encounter the Rift's deepest mutant creatures—the most dangerous Evolvers along the way) → ②Hall of Shards (the Void Abyss Worm's consciousness fragments exist here as echoes. Dialogue with the fragments reveals all truths) → ③The Final Choice (three options: absorb the fragment's full power to become a new Void Abyss Worm? Destroy the fragment to end the Evolution curse? Or fuse the fragment with yourself but control it with your humanity?) |
| **Core Conflict** | Ultimate Evolution vs. Self-Sacrifice |
| **Key NPC** | The Void Abyss Echo (not an enemy—it is the memory echo of the ancient Worm, possibly appearing in the form of a deceased loved one or mentor) |
| **Possible Endings** | ①Absorb the fragment—become a new "Devourer" (power at its peak, infinite Evolution Capacity, but Humanity Value drops to zero, the character becomes an NPC/villain); ②Destroy the fragment—the Evolution ability of all creatures in the world vanishes (including yours), but the Rift stops expanding; ③Fuse and Control—successfully merge the fragment's power into yourself while retaining humanity (requires a Will YZ check DC 30; success grants the "Ultimate Form"—you can freely switch between all unlocked Forms and Humanity Value no longer decreases) |

Detailed scenario content can be found in the `scenarios/` directory.

### 16-2 Evolution Pacing Control

The GM needs to control the players' Evolution speed. Too fast → the game loses its challenge; too slow → players cannot enjoy the fun of Evolution.

**Suggested Pacing:**

| Game Phase | Evolution after each Encounter | Total Growth per Scenario |
|---|---|---|
| Prologue (first 3 encounters) | 1-2 Evolution Points per encounter | accumulate 3-5 points, unlock 2-3 new nodes |
| Mid-game | Hard Encounter 2-3 points, BOSS 3-5 points | unlock 4-6 nodes |
| Final Chapter | BOSS battle 5+ points, story reward 5+ | unlock 5-8 nodes |

**Strategies to Prevent Over-Powering:**
- Do not let players unlock more than 8 new nodes in the same Scenario
- Organ Nodes and Form Nodes should have a "cooldown period"—after unlocking a Form Node, at least 2 encounters must pass before the next one can be unlocked
- Cell Capacity is a built-in soft cap—when players' number of Evolution Nodes approaches the capacity, they will naturally slow down

**Strategies to Prevent Under-Powering:**
- If players fail to successfully Absorb for 3 consecutive encounters, make the next encounter's enemies provide easier absorption conditions (voluntary or already paralyzed)
- Environmental Adaptation rewards can be offered as a "safety net" when combat is difficult

### 16-3 NPC Roleplaying Essentials

A Humanity Value-centric NPC reaction system:

| NPC Type | Reaction to High Humanity Value (>40%) | Reaction to Low Humanity Value (<40%) |
|---|---|---|
| Ordinary Villager | Curious, cautious, tradeable | Fearful, flees, may summon guards |
| Merchant | Trades normally | Refuses trade or price ×3 |
| Guardian Soldier | Lets you pass after registration | Attacks or expels immediately |
| Cult Member | Tries to recruit ("You're not strong enough yet") | Shows respect ("You are already on the right path") |
| Accord Scholar | Friendly, offers help | Offers Humanity Value restoration service (for a fee) |
| Mutant Beast | Normal hostility | May view you as kin (50% chance not to attack first) |

### 16-4 Improvisation Tools

When players take unexpected actions:

1. **Determine Intent**: "What are you trying to achieve?"
2. **Judge Feasibility**: Is it possible? (Yes → set a DC; No → explain the reason + offer alternatives)
3. **Set Consequences**: What happens on success? What happens on failure?
4. **Roll Dice**: Let the player roll
5. **Narrate the Result**: Describe what happens—remember, you are not announcing numbers, you are telling a story

---

## Seventeen, Complete Rules for Special Systems

### 17-1 Environmental Adaptation System

Players can gain Environmental Adaptation rewards after spending a long time active in a specific environment.

| Environment Type | Hazard Effect | Adaptation Condition | Adaptation Reward (optional Evolution direction) |
|---|---|---|---|
| **Desert / High Temperature** | Constitution (TZ) DC 12 per hour, failure deals 1d4 heat damage | Survive 3 turns (approx. 3 hours) | ①Heat Resistance ②Water Storage (Passive: drinking need halved) ③Thermal Vision |
| **Extreme Cold / Tundra** | Constitution (TZ) DC 12 per hour, failure reduces Movement Speed by 2 tiles | Survive 3 turns | ①Cold Resistance ②Hibernation (Passive: can enter dormant state to reduce consumption) ③Frost Skin (Passive: frost damage -1) |
| **Deep Sea / High Pressure** | Constitution (TZ) DC 14 per turn, failure deals 1d6 pressure damage | Survive 3 turns | ①Aquatic Adaptation ②Deep-Dive Organ (Organ: deep-sea vision + pressure resistance) ③Bioluminescence (Passive) |
| **Volcano / Extreme Heat** | 1d6 fire damage per turn (no save) | Survive 3 turns | ①Fire Immunity ②Lava Form (Form Node hint) ③Fire Breath |
| **Toxic Swamp** | Constitution (TZ) DC 14 per turn, failure causes poisoning | Survive 3 turns without poisoning (or resist successfully 3 times) | ①Poison Immunity ②Acid Gland (Organ) ③Swamp Camouflage (Passive) |
| **High-Radiation Zone** | Humanity Value -1 per turn (unresistable) | Survive 5 turns | ①Radiation Absorption (Passive: can convert radiation into Energy, +1 Energy per turn) ②Gene Stabilization (Passive: Humanity Value reduction -1) ③Radiation Breath (Advanced Active) |
| **Void / Frontier** | Will (YZ) DC 15 per turn, failure deals Humanity Value -1d4 | Survive 5 turns and succeed on Will checks more than 3 times | ①Void Adaptation (Form Node hint) ②Dimensional Perception (Passive: can sense nearby spatial anomalies) ③Void Blade |

### 17-2 Evolution Conflict and Reversal

**Voluntarily Discarding a Node:**
Players may choose to permanently discard an already-unlocked Evolution Node. Effects:
- The node's effect disappears
- Evolution Points are not refunded
- Biomass is not refunded
- Humanity Value restored +3
- Releases 1 Evolution Capacity

**Form Switching:**
Some players may unlock multiple Form Nodes. Rule: only one Form Node can be active at a time (except Insect—two Organ Nodes can be active simultaneously, but only one Form still). Switching Forms requires a 1-turn "transformation" process—during which you cannot act.

### 17-3 Multiplayer Cooperative Evolution

In multiplayer games, unique interactions can arise between Evolvers:

| Interaction | Rule |
|---|---|
| **Shared Absorption** | Two players can Absorb a large enemy (such as a BOSS) simultaneously, each gaining a Trait Sample (options may differ per person) |
| **Evolution Resonance** | Players who share an Absorption experience, when within 3 tiles of each other in combat, each recover +1 Energy/turn |
| **Human Bond** | If a player's Humanity Value drops below 20%, a teammate can spend 1 Action Point to perform a "Humanity Call" (Will YZ check DC 15); on success the player temporarily recovers 1d4 Humanity Value (lasts only until combat ends) |

### 17-4 Evolution Rampage

When players accumulate too many nodes or perform overly drastic Evolution at once, an Evolution Rampage may occur:

**Trigger Condition:** Gaining more than 8 Evolution Points in a single instance and spending them all on Evolution, or unlocking another Form Node while Humanity Value is below 20%.

**Rampage Effect (roll 1d6):**

| d6 | Rampage Manifestation |
|---|---|
| 1 | Flesh Rampage—randomly triggers an already-unlocked Active Node (GM chooses the worst possible timing) |
| 2 | Random Form Switch—if you have multiple Form Nodes, randomly activates one (may be unsuitable for the current environment) |
| 3 | Energy Overload—lose all remaining Energy and take damage equal to the amount lost |
| 4 | Consciousness Fragmentation—cannot control the character's actions for 1d4 turns (GM describes your Evolution instinct taking over your body) |
| 5 | Reverse Evolution—randomly lose an Evolution Node (GM chooses secretly, no point refund) |
| 6 | Benign Rampage—fortunately, this rampage has no negative effect (but that doesn't mean next time will be as lucky) |

---

## Eighteen, Complete Evolution Node Codex

This section collects the complete data of all Evolution Nodes as a GM reference. (The full node list is the same as Section Six of the Player Rulebook and is not repeated here.)

GMs may use `catalogs/Evolution Node Codex.md` as a quick reference tool.

### 18-1 GM Custom Node Guide

When creating new Evolution Nodes, follow these balancing principles:

| Node Type | Effect Strength Reference | Evolution Point Cost |
|---|---|---|
| Attribute Node | Total attributes increase by 1-3 points | Per +1 attribute ≈ 1.5 Evolution Points |
| Passive Node | Numerical effect roughly equal to +1 to +3 attribute equivalent | Equivalent attribute value ×1.5 |
| Low-tier Active | Equivalent damage roughly 1d8+attribute, or equivalent control of 1 turn | 2 |
| Mid-tier Active | Equivalent damage roughly 2d8+attribute, or area effect | 3-4 |
| High-tier Active | Equivalent damage roughly 3d10+attribute, or strong control | 5 |
| Ultimate Active | Battle-deciding effect | 5 + special condition |
| Organ Node | Provides 2-3 independent effects | 3-5 + Biomass |
| Form Node | Attribute change 4-7 points + multiple new abilities + major side effects | 5 + large amount of Biomass |

> The complete data and unlock conditions for Ultimate Active Nodes (Form Transformation, Domain Expansion, Ultimate Evolution, Self-Destruct Rebirth, Gene Collapse, Devour All) can be found in the "Ultimate Active Nodes" section of `catalogs/Evolution Node Codex.md`. Players need to accumulate considerable Evolution depth (usually 15+ nodes) to unlock them.

---

## Nineteen, Optional Rules and Variants

### 19-1 Fast Evolution Mode

Suitable for short games (1-2 scenarios). Changes:
- All Evolution costs -1 (minimum 1)
- Evolution Point reward per encounter +1
- Evolution Capacity cap +3 (because game length is insufficient to raise Constitution and Will)
- Humanity Value reduction halved (because there isn't enough time in the game to handle Humanity Value recovery)

### 19-2 Permadeath Mode

Suitable for high-risk hardcore experiences. Changes:
- No Constitution check at Near Death—permanent death when HP drops to -(Constitution ×5)
- However—if you successfully Absorb a nearby enemy while at Near Death, you can "steal" its life essence to recover 1d10 HP
- This emergency Absorption can be used 1 time per Scenario

### 19-3 Cooperative Evolution Mode

Suitable for multiplayer team games. Changes:
- Players can donate Evolution Points to teammates (maximum 2 points donated per person per Scenario)
- Both donor and recipient gain "Evolution Bond"—afterward, when within 5 tiles of each other, each recovers +1 Energy
- Cost: the donor permanently loses 1 Humanity Value (because your Evolution energy has left your body)

### 19-4 Random Evolution Mode

Suitable for chaotic and fun experiences. Changes:
- After Absorbing an enemy, no choice is offered—instead, randomly gain one Evolution direction of that enemy
- Players gain the "Reject Evolution" ability—if the randomly obtained direction is a Forbidden Evolution, they can spend 1 Evolution Point to re-roll
- In this mode, the Human's "Adaptability" talent changes to: can re-roll a random result 1 time

### 19-5 No Humanity Value Mode

Suitable for player groups who only want pure Evolution combat. Changes:
- The Humanity Value system is completely removed—Evolution no longer carries any social or identity cost
- All Humanity Value-related talents and equipment adjustments: the Human talent changes to "Evolution Capacity +2"; the Hatchling Dragon's cost penalty is removed
- This mode suits single-combat-oriented games and is not suitable for long campaigns

---

## Twenty, Quick Reference Tables

### 20-1 Core Check Formulas

| Check Type | Formula |
|---|---|
| Attribute Check | d20 + attribute value vs DC |
| Melee Attack | d20 + Strength (LIL) vs Defense Value |
| Ranged Attack | d20 + Agility (MJ) vs Defense Value |
| Absorption Check | d20 + Will (YZ) vs Absorption DC |
| Initiative | d20 + Agility (MJ) |
| Contest Check | Both sides d20 + corresponding attribute, higher wins |
| Humanity Value Check | d20 + Will (YZ) vs DC |

### 20-2 Derived Value Formulas

| Derived Value | Formula |
|---|---|
| Health (HP) | Constitution × 5 |
| Energy Cap | Constitution + Will |
| Evolution Capacity Cap | Constitution + Will |
| Movement Speed | Agility 1-3→4 / 4-6→5 / 7-9→6 / 10-12→7 / 13-15→8 / 16+→9 |
| Defense Value | 10 + Agility + template bonus (Minion +0 / Elite +2 / Boss +4) |
| Basic Melee Damage | 1d6 + Strength |
| Basic Ranged Damage | 1d4 + Agility |

### 20-3 Action Point Quick Reference

| Action | Cost | Description |
|---|---|---|
| Normal Attack | 1 AP | Basic melee/ranged attack |
| Evolution Skill | 1-3 AP | Depends on skill level |
| Move | 1 AP | Up to Movement Speed in tiles |
| Defend | 1 AP | Halve damage this round |
| Observe | 1 AP | Perception check → Advantage on next attack |
| Absorption Attempt | 2 AP | Absorb Near Death/paralyzed enemy |
| Forced Evolution | 3 AP | Temporarily activate an unlocked node |
| Use Item | 1 AP | Consumable |

### 20-4 Energy Consumption Quick Reference

| Skill Level | Energy Cost | Cooldown |
|---|---|---|
| Low-tier | 1-2 | None/1 turn |
| Mid-tier | 3 | 1-2 turns |
| High-tier | 5 | 3 turns |
| Ultimate | All (minimum 5) | 1 time per combat |

### 20-5 Absorption DC Quick Reference

| Target State | DC |
|---|---|
| Already Dead | 15 |
| Near Death (HP < 10%) | 10 |
| Paralyzed / Numb | 8 |
| Voluntary | Automatic Success |

### 20-6 Humanity Value Stage Quick Reference

| Humanity Value | Stage | Social Effect |
|---|---|---|
| >70% | Humanoid | Normal |
| 40-70% | Mixed | Disadvantage on social checks |
| 10-40% | Aberrant | NPC fear/hostility |
| <10% | Monster | Not bound by social rules |

---

> **"You are not running a game. You are witnessing a history of Evolution."**
>
> — First Article of the GM Code

---

*Devour Gene: Chronicle of Evolution GM Rulebook v1.0*
*This document contains the complete content of the Player Rulebook + GM-exclusive content. The GM only needs to read this one document to run the game.*
