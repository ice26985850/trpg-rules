# Otherworld Invasion TRPG — GM Rulebook

> **Version:** v2.0 (Class System Update)
> **Design Focus:** Modern Urban × Otherworld Invasion × Physical Law Conflict × Personal Growth × Dual-EXP Class System
> **Audience:** GM (Game Master). This book contains everything in the Player Rulebook plus GM-exclusive mechanics.

---

# Chapter One: Core Rules

## 1.1 Dice System

This game uses **d100 Percentile Dice** as the core resolution tool.

| Mode | Formula | Usage Scenario |
|------|---------|----------------|
| Roll-Low-to-Succeed | d100 ≤ target % | Attack hit check |
| Roll-High-to-Succeed | d100 + modifier ≥ Difficulty Class (DC) | Skill check, attribute check |

---

## 1.2 Attribute System

| Attribute | Abbr | Primary Influence |
|-----------|------|-------------------|
| Strength (STR) | Physical Attack, carry weight |
| Dexterity (DEX) | Initiative order, Dodge Rate, Critical Rate |
| Constitution (CON) | HP max, physical damage reduction, dying check |
| Intelligence (INT) | Magic Attack, trap decryption |
| Wisdom (WIS) | Hit Rate, detecting hidden threats |
| Spirit (SPI) | Mana pool max, mental resistance |

### Attribute Stepwise Cost

| Attribute Range | Cost/pt | Attribute Range | Cost/pt |
|-----------------|---------|-----------------|---------|
| 1 - 10 | 1 pt | — | — |
| 11 - 20 | 1 pt | 61 - 80 | 4 pts |
| 21 - 40 | 2 pts | 81 - 100 | 5 pts |
| 41 - 60 | 3 pts | 101+ | 6 pts |

> Attribute base value is 10. At creation, the player has 30 attribute points to allocate freely.

---

## 1.3 Derived Attributes

| Derived Attribute | Abbr | Formula |
|-------------------|------|---------|
| Hit Points (HP) | Constitution (CON) × 10 + Level × 5 |
| Mana Points (MP) | Spirit (SPI) × 5 + Level × 3 |
| Physical Attack (PATK) | Strength (STR) × 2 + weapon bonus |
| Magic Attack (MATK) | Intelligence (INT) × 2 + weapon bonus |
| Physical Defense (PDEF) | Constitution (CON) × 1.5 + armor bonus |
| Magic Defense (MDEF) | Spirit (SPI) × 1.5 + armor bonus |
| Hit Rate (HIT%) | 50% + Wisdom (WIS) × 3% (cap 95%) |
| Dodge Rate (DGE%) | 10% + Dexterity (DEX) × 2% (cap 60%) |
| Critical Rate (CRT%) | 5% + Dexterity (DEX) × 1% |

---

## 1.4 Attack Resolution Flow

1. Declare the attack target and method
2. Calculate **Effective Hit Rate (EHit%)** = Hit Rate (HIT%) − target's Dodge Rate (DGE%) [min 5%, max 95%]
3. Roll d100
4. Judgment: **1-5 = Critical Success** (guaranteed hit + crit + extra positive effect); **96-100 = Critical Failure** (guaranteed miss + negative consequence); **6-95**: d100 ≤ Effective Hit Rate (EHit%) → hit (if ≤ Critical Rate (CRT%) → crit), otherwise → miss
5. Normal attack damage = max(Attack − target's Defense, 1); crit ×1.5 (Critical Success ×2.0)
6. Skill damage = max((Attack + Skill Base Power) × (1 + Class Level ÷ 20) − target's corresponding Defense, 1). Physical skills use Physical Attack (PATK); magic skills use Magic Attack (MATK).

---

## 1.5 Skill Checks

```
Check Result = d100 + (corresponding Attribute + passive bonus) ≥ Difficulty Class (DC)
```

> **Passive bonus** includes: background traits, class traits, equipment effects, Awakening Skill bonuses, and other permanent or always-on numeric bonuses. A Combat Class grants a +1 skill-check bonus to its corresponding attribute every 10 levels (Lv.10=+1, Lv.20=+2, and so on).

### Full Difficulty Class (DC) Difficulty Table

| Difficulty Class (DC) | Difficulty | Description | Example |
|-----------------------|-----------|-------------|---------|
| 20 | Very Easy | Almost cannot fail | Climbing stairs |
| 40 | Simple | Basic training suffices | Picking a common door lock |
| 60 | Normal | Requires some focus | Finding clues in ruins |
| 70 | Moderate | Somewhat challenging | Decrypting encoded comms |
| 80 | Hard | Ordinary people may fail | Climbing in a storm |
| 100 | Very Hard | Requires professional level | Disarming a high-tier magic trap |
| 120 | Epic | Top experts may still fail | Reverse-decrypting otherworld runes |
| 140 | Legendary | Nearly impossible | Persuading a hostile clan's chief god |
| 160+ | Mythic | Beyond mortals | Directly intervening in law erosion |

### GM Dynamic Difficulty Class (DC) Adjustment

| Situation | Adjustment |
|-----------|------------|
| Ample preparation time | Difficulty Class (DC) −10 |
| Suitable tools / resources | Difficulty Class (DC) −10 ~ −20 |
| Time pressure | Difficulty Class (DC) +10 |
| Harsh environment (darkness, noise, etc.) | Difficulty Class (DC) +10 ~ +20 |
| Inside a Rift | +0 ~ +40 by Rift tier (see §4.1) |

---

## 1.6 Critical Success / Critical Failure

| d100 | Result | GM Suggestion |
|------|--------|---------------|
| 1 - 5 | Critical Success | Give extra information, extra damage, chain effects |
| 96 - 100 | Critical Failure | Weapon jams, friendly fire, attracts patrol monsters |

---

## 1.7 Advantage and Disadvantage

Roll 2d100, take the favorable (low on attack / high on check) or unfavorable result. Multiple instances do not stack; Advantage and Disadvantage cancel each other.

---

## 1.8 Team Cooperative Check

The primary actor makes the check; a helper who passes Difficulty Class (DC)−20 provides +15 (max +30).

---

# Chapter Two: Character Creation (same as Player Rulebook §2)

The full character creation flow (background, awakening scene, attribute allocation, skill selection, awakening skill draw, starting gear) is in Player Rulebook §2. The GM should be familiar with the following to assist players in creation.

### Beginner Quick Templates (GM backup)

| Template | Strength (STR)/Dexterity (DEX)/Constitution (CON)/Intelligence (INT)/Wisdom (WIS)/Spirit (SPI) | HP | Class (suggested) | Starting Skills |
|----------|----------------------------------------|----|------|------|
| Balanced | 15/15/15/15/15/15 | 155 | Vanguard | Heavy Strike (Base 40, MP8) + Iron Wall (MP15, Physical Defense (PDEF)+8) + Trait: Iron Wall Break |
| Melee Tank | 21/12/20/10/12/10 | 205 | Guardian | Guardian Oath (MP12) + Holy Bastion (MP18) + Trait: Unshakeable Shield |
| Agile Assassin | 10/22/16/10/12/10 | 165 | Assaulter | Lethal Thrust (Base 30, MP10) + Flash Step (MP10) + Trait: Lethal Rhythm |
| Magic DPS | 10/12/12/22/10/17 | 125 | Warlock | Mana Bolt (Base 30, MP6) + Mana Shield (MP15) + Trait: Mana Resonance |

---

# Chapter Three: Skill System

Same as Player Rulebook §3. GM focus: **skill point cost** (Lv.N→N+1 costs N+1 points; maxing one skill costs 54 points), and **Awakening Skill evolution conditions** are triggered at the GM's discretion.

---

# Chapter Four: Combat Rules (Full Version)

## 4.1 Combat Framework

- Turn-Based (6 sec/turn)
- Action economy: 1 Standard + 1 Move + 1 Swift + 1 Reaction / turn
- Initiative = Dexterity (DEX) + d20

## 4.2 Zone-Based Map

| Distance Tier | Zone Gap | Move Cost |
|---------------|----------|-----------|
| Same Zone | 0 | 0 |
| Near | 1 zone | 1 Move action |
| Mid | 2 - 3 zones | 2 Move actions (Dash) |
| Far | 4 - 5 zones | — |
| Extreme | 6+ zones | — |

## 4.3 Damage Types and Resistance

### Eight Damage Types

| Type | Category | Typical Source |
|------|----------|----------------|
| Slashing | Physical | Blades, A02 Whirlwind Slash |
| Piercing | Physical | Bow/arrow, A03/A04/A05 |
| Bludgeoning | Physical | Clubs, A01 Heavy Strike |
| Fire | Elemental | A06 burst splash, A08 |
| Frost | Elemental | A08 (frost) |
| Lightning | Elemental | A08 (lightning) |
| Shadow | Magic | A07 Mana Bolt, A09 infusion |
| Holy | Magic | A07 (Osaikus variant) |

### Five Resistance Tiers

| Tier | Damage Multiplier | Description |
|------|-------------------|-------------|
| Weakness | ×1.5 | That damage type deals +50% |
| Normal | ×1.0 | No special resistance or weakness |
| Resistance | ×0.5 | That damage type halved |
| Immunity | ×0 | Completely unaffected by this damage |
| Absorb | Converts to Hit Points (HP) restore | Damage becomes healing |

## 4.4 Full Status Effect List

### Negative Status

| Status | Effect | Duration | Removal Condition |
|--------|--------|----------|-------------------|
| Stun | Skip next turn | 1 turn | Auto-expires |
| Bleed | Each turn lose Physical Attack (PATK) × 0.2 × stacks Hit Points (HP) | 2 turns | First Aid Difficulty Class (DC) 40 |
| Burn | Each turn lose 5 × stacks Mana Points (MP) | 2 turns | Use water or Difficulty Class (DC) 40 |
| Freeze | Cannot move, Physical Defense (PDEF) +30% | 2 turns | Removed by fire damage |
| Paralysis | 25% chance action fails | 1 turn | Auto-expires |
| Poison | Each turn lose 3 × stacks Hit Points (HP) | 3 turns | Antidote Difficulty Class (DC) 40 |
| Confusion | Attack random target | 2 turns | Difficulty Class (DC) 60 Spirit check |
| Curse | All checks at Disadvantage | 3 turns | Removed by Holy damage |

### Positive Status

| Status | Effect | Duration |
|--------|--------|----------|
| Buff | Attack +30% | 3 turns |
| Shield | Temp Hit Points (HP) = Spirit (SPI) × 3 | Until broken |
| Invisible | Cannot be targeted by single-target | 2 turns |
| Haste | Extra 1 Standard action + move +1 zone | 3 turns |

### Potion Use Limit

In each battle, each character may use at most **3 potions** (healing and mana combined). This limit resets after a Short Rest. The GM may relax it to 5 potions in especially difficult Boss fights.

## 4.5 Environmental Interaction

| Action | Effect | Check |
|--------|--------|-------|
| Find cover | Dodge Rate (DGE%)+10% | Wisdom (WIS) Difficulty Class (DC) 40 |
| Occupy high ground | Hit Rate (HIT%)+10% | Dexterity (DEX) Difficulty Class (DC) 40 |
| Topple object | Create obstacle or damage | Strength (STR) Difficulty Class (DC) 40-60 |
| Destroy environment | Change the battlefield | Strength (STR) Difficulty Class (DC) 60 |

### Urban Ruins Environmental Elements (d20)

| d20 | Environmental Element | Usability |
|-----|----------------------|----------|
| 1-3 | Overturned vehicle | Cover (DGE% +15%) |
| 4-6 | Burst water pipe | Create slippery floor (Difficulty Class (DC) +5) |
| 7-8 | Exposed wires | Can deal lightning damage |
| 9-10 | Gas leak | Fire damage +50% |
| 11-12 | Collapsed wall | Block movement or create passage |
| 13-14 | Scattered glass | Moving requires Difficulty Class (DC) 40 stealth or makes noise |
| 15-16 | Abandoned weapon crate | May find supplies |
| 17-18 | Otherworld Crystal | Collect to craft equipment |
| 19-20 | Rift Resonance Point | Mana Points (MP) restore +20%, but attracts monsters |

---

## 4.6 Monster / NPC Data Templates

### Standard Data Card Format

```
[Monster Name] Level Lv.X | Challenge Rating (CR) Y | Category
Hit Points (HP): X | Mana Points (MP): X | Physical Attack (PATK): X | Magic Attack (MATK): X | Physical Defense (PDEF): X | Magic Defense (MDEF): X
Hit Rate (HIT%): X | Dodge Rate (DGE%): X | Critical Rate (CRT%): X
Damage Type: X | Resistance: X | Weakness: X
Special Abilities:
- Ability Name: effect description
AI Behavior Template: X
Drop: X Experience Points (EXP), X G, equipment
```

### Value Benchmarks by Level Range

| Tier | Challenge Rating (CR) Range | Hit Points (HP) Range | Physical Attack (PATK) Range | Physical Defense (PDEF) Range | Hit Rate (HIT%) Range | Dodge Rate (DGE%) Range |
|------|----------------------------|-----------------------|------------------------------|-------------------------------|-----------------------|-------------------------|
| E-Rank | 1-10 | 50 - 230 | 12 - 30 | 5 - 20 | 55 - 70 | 10 - 25 |
| D-Rank | 11-25 | 300 - 820 | 35 - 72 | 25 - 55 | 65 - 80 | 20 - 38 |
| C-Rank | 26-45 | 1,100 - 2,600 | 80 - 165 | 60 - 120 | 75 - 88 | 30 - 48 |
| B-Rank | 46-70 | 3,200 - 7,000 | 180 - 380 | 130 - 250 | 80 - 92 | 38 - 55 |
| A-Rank | 71-100 | 9,000 - 24,000 | 420 - 800 | 260 - 450 | 85 - 95 | 45 - 60 |
| S-Rank | 101+ | 32,000 - 100,000+ | 900 - 3,500+ | 480 - 1,200+ | 90 - 95 | 50 - 60 |

### Challenge Rating (CR)

**Challenge Rating (CR) = the monster level a solo player of that level can defeat at moderate difficulty.**

Examples:
- **Challenge Rating (CR) 5 monster** = a Lv.5 solo player can defeat at moderate difficulty
- **Challenge Rating (CR) 10 monster** = a Lv.10 solo player can defeat at moderate difficulty
- Two Challenge Rating (CR) 5 monsters ≈ one Challenge Rating (CR) 7 monster (equivalent CR = CR_base × 1.4)

### Encounter Difficulty Rating (EDR)

```
Encounter Difficulty Rating (EDR) = sum of monster CR ÷ (number of players × average level)
```

| Encounter Difficulty Rating (EDR) | Difficulty | Description |
|-----------------------------------|-----------|-------------|
| < 0.3 | Trivial | Players easily crush, no resource cost |
| 0.3 - 0.7 | Standard | Requires serious response, resource cost |
| 0.7 - 1.0 | Hard | A character may enter Dying State |
| 1.0 - 1.3 | Lethal | Someone may die |
| > 1.3 | Desperate | Not recommended unless the plot demands it |

> **Solo Mode**: Encounter Difficulty Rating (EDR) thresholds raised by 0.2 (Trivial < 0.5, Standard 0.5-1.2, Hard 1.2-1.5, Lethal 1.5-1.8, Desperate > 1.8)

### Monster AI Behavior Templates

| Template | Behavior Logic |
|----------|----------------|
| Beast Instinct | Attack nearest target, flee at Hit Points (HP) < 30% |
| Predator | Prioritize low-HP targets, use cover and ambush |
| Warrior | Frontal attack, no flee, enter rage at Hit Points (HP) < 50% (+20% damage) |
| Commander | Direct other monsters to focus fire, support from range |
| Guardian | Hold a fixed position (e.g. Rift core), unaffected by HP |

---

## 4.7 Boss Mechanics

### Common Boss Traits

| Trait | Description |
|-------|-------------|
| Tenacity | Immune to instant-death and most control (Stun reduced to 1-turn Paralysis) |
| Phase Transition | Triggers a phase change at 75% / 50% / 25% Hit Points (HP) |
| Legendary Action | Boss may act between player turns (1-2×/round) |
| Legendary Resistance | 1-3×/encounter, may choose to resist one negative status |
| Area Telegraph | Large AoE attacks announce the target zone one turn ahead |

### Sample Boss 1: Rift Aggregator (D-Rank Challenge Rating (CR) 15)

```
Rift Aggregator Lv.15 | Challenge Rating (CR) 15 | Aberrant Fusion
Hit Points (HP): 800 | Mana Points (MP): 200
Physical Attack (PATK): 80 | Magic Attack (MATK): 50 | Physical Defense (PDEF): 60 | Magic Defense (MDEF): 40
Hit Rate (HIT%): 75 | Dodge Rate (DGE%): 15 | Critical Rate (CRT%): —
Damage Type: Bludgeoning | Weakness: Fire (×1.5) | Immune: Crit
Special Abilities:
- Tentacle Sweep: hit all targets around (×1.2 Physical Attack (PATK)), Difficulty Class (DC) 60 Dexterity (DEX) dodge halved
- Devour Regen: swallow a small monster to restore 100 Hit Points (HP) (usable every 3 turns)
- Phase 2 (Hit Points (HP) < 50%): summon 1d3 Void Rats (Lv.3) each turn
AI: Guardian (hold the Rift entrance), prioritize nearest target
Drop: 800 Experience Points (EXP), 150 Gold (G), D-Rank weapon crate (60%) / B-Rank material (40%)
```

### Sample Boss 2: Shadow Wolf Chieftain · Nighthowl (C-Rank Challenge Rating (CR) 35)

```
Shadow Wolf Chieftain · Nighthowl Lv.35 | Challenge Rating (CR) 35 | Beast-type Leader
Hit Points (HP): 2,200 | Mana Points (MP): 400
Physical Attack (PATK): 150 | Magic Attack (MATK): 30 | Physical Defense (PDEF): 100 | Magic Defense (MDEF): 60
Hit Rate (HIT%): 85 | Dodge Rate (DGE%): 40 | Critical Rate (CRT%): 18%
Damage Type: Slashing | Weakness: Holy (×1.5) | Resistance: Shadow (×0.5)
Special Abilities:
- Shadow Stealth: vanish 1 turn, next attack ignores Dodge Rate (DGE%) and is guaranteed crit
- Pack Tactics: summon 2 Shadow Wolves (Lv.20), 300 Hit Points (HP) each
- Phase 1 (Hit Points (HP) > 70%): guerrilla, prioritize back row
- Phase 2 (Hit Points (HP) 30-70%): frontal combat, damage +20%
- Phase 3 (Hit Points (HP) < 30%): rage, 2 attacks per turn, Dodge Rate (DGE%) −20%
AI: Predator, no flee at Hit Points (HP) < 30%
Drop: 2,500 Experience Points (EXP), 500 Gold (G), C-Rank weapon (Purple · Unique)
```

### Sample Boss 3: Magma Guardian · Kargnus (B-Rank Challenge Rating (CR) 55)

```
Magma Guardian · Kargnus Lv.55 | Challenge Rating (CR) 55 | Elemental Guardian
Hit Points (HP): 6,500 | Mana Points (MP): 800
Physical Attack (PATK): 350 | Magic Attack (MATK): 280 | Physical Defense (PDEF): 250 | Magic Defense (MDEF): 180
Hit Rate (HIT%): 90 | Dodge Rate (DGE%): 20 | Critical Rate (CRT%): 10%
Damage Type: Fire + Bludgeoning | Immune: Fire | Weakness: Frost (×1.5)
Special Abilities:
- Magma Eruption: deal Magic Attack (MATK) × 1.8 fire damage in a 2-zone area (telegraphed 1 turn)
- Core Link: Kargnus shares Hit Points (HP) with the Rift core. Destroying the core (Hit Points (HP) 1,500, Defense (DEF) 15) weakens Kargnus (−30% all attributes)
- Magma Domain: at end of each turn, all characters within 3 zones take 15 fire damage
- Phase 2 (Hit Points (HP) < 50%): Magma Domain damage doubles to 30
AI: Guardian, hold the core position, telegraph-type AoE prioritizes clustered players
Drop: 6,000 Experience Points (EXP), 2,000 Gold (G), B-Rank equipment (Orange · Legendary)
```

---

## 4.8 Party Combat Adjustments

| Adjustment | Formula | Scenario |
|------------|---------|----------|
| Increase monster count | original count × players × 0.8 | General encounter |
| Raise Challenge Rating (CR) | monster CR ≈ 0.8 - 1.2× average player level | Boss fight |
| Strengthen Boss | Hit Points (HP) × players × 0.5, extra Legendary Action +1 | Important Boss |

---

# Chapter Five: Rift System

## 5.1 Five Waves of Creeping Law Erosion

This is the game's core time-pressure mechanic:

| Invasion Wave | Days | Max Rifts Opened | Max Monsters Passable |
|---------------|------|-----------------|-----------------------|
| First Wave | 0 - 30 days | E-Rank, D-Rank | Low-Rank Monsters, D-Rank Boss |
| Second Wave | 31 - 90 days | open to C-Rank | Mid-Rank Monsters |
| Third Wave | 91 - 180 days | open to B-Rank | High-Rank Monsters, B-Rank Boss |
| Fourth Wave | 181 - 365 days | open to A-Rank | Clan Elite |
| Fifth Wave | 366 days+ | open to S-Rank | Chief-God Projection |

## 5.2 Six Rift Tiers

| Rift Tier | Color | Erosion Zone Radius | Suggested Level | Closing Condition |
|-----------|-------|---------------------|-----------------|-------------------|
| E-Rank | White · Common | 100m - 500m | Lv.1 - 10 | Kill all monsters |
| D-Rank | Green · Uncommon | 500m - 2km | Lv.11 - 25 | Kill Boss |
| C-Rank | Blue · Rare | 2km - 5km | Lv.26 - 45 | Kill all Bosses |
| B-Rank | Purple · Unique | 5km - 15km | Lv.46 - 70 | Kill Boss + destroy core |
| A-Rank | Orange · Legendary | 15km - 50km | Lv.71 - 100 | Destroy core + kill Guardian |
| S-Rank | Red · Mythic | 50km+ | Lv.101+ | Repel Chief-God Projection |

## 5.3 Rift Interior Structure

Each Rift interior is a small labyrinth (3-10 zones):

| Interior Element | Description |
|------------------|-------------|
| Monster Density | 3-5× the exterior |
| Rift Core | B-Rank and above have a core (Hit Points (HP) by tier: E none / D none / C none / B 1,500 / A 5,000 / S 20,000) |
| Otherworld Resources | Unique minerals, plants, materials |
| Time Pressure | An unhandled Rift auto-upgrades one tier every 14 days (E→D→C→B→A→S) |

## 5.4 Erosion Zone Rules

| Erosion Degree | Distance from Rift | Effect |
|----------------|--------------------|-------|
| Light | Edge | Electronics unstable, ranged weapon Hit Rate −5% |
| Moderate | Mid | Firearms fail, electronics fully dead |
| Heavy | Near core | Magic recovery +20%, physical Difficulty Class (DC) +20, magic Difficulty Class (DC) −10 |
| Total | Core area | Otherworld law fully overrides, mana cost −10%, per-hour Difficulty Class (DC) 80 Constitution (CON) check |

---

# Chapter Six: Quest System

## 6.1 Three Quest Tiers

| Tier | Issuer | Experience Points (EXP) | Gold (G) | Equipment |
|------|--------|-------------------------|----------|-----------|
| Personal Quest (Daily) | The System | 50 - 200 | Small | White · Common / Green · Uncommon random crate |
| Personal Quest (Story) | The System | 200 - 1,000 | Medium | Blue · Rare item |
| Regional Quest | The System + Guild | 500 - 3,000 | High | Blue · Rare ~ Purple · Unique equipment crate |
| World Quest | The System | 3,000 - 10,000+ | Huge | Orange · Legendary ~ Red · Mythic item |

## 6.2 Guild Commissions

| Commission Difficulty | Color | Suggested Level | Reward |
|-----------------------|-------|-----------------|--------|
| E-Rank | White · Common | Lv.1 - 10 | Small gold |
| D-Rank | Green · Uncommon | Lv.11 - 25 | Gold + Green · Uncommon material |
| C-Rank | Blue · Rare | Lv.26 - 45 | High gold + Blue · Rare equipment |
| B-Rank | Purple · Unique | Lv.46 - 70 | High gold + Purple · Unique material |
| A-Rank | Orange · Legendary | Lv.71 - 100 | Orange · Legendary equipment + territory rights |
| S-Rank | Red · Mythic | Lv.101+ | Red · Mythic item |

---

# Chapter Seven: Guild System

## 7.1 Organization Structure

The human-side management organization is **GAGA (Global Awakened Guild Alliance)**.

| Level | Description |
|-------|-------------|
| GAGA HQ | Global decisions, based in Geneva |
| Branch | One per continent (Tokyo, New York, London, Shanghai, São Paulo) |
| Major Guild | Large guilds in each city |
| Affiliate Guild | Small or newly formed guilds |

## 7.2 Reputation System (10 tiers)

| Tier | Title | Reputation Needed | Unlock |
|------|-------|-------------------|--------|
| 1 | Initiate | 0 | E-Rank commission |
| 2 | Apprentice | 100 | D-Rank commission, 5% shop discount |
| 3 | Full Member | 300 | Guild dormitory |
| 4 | Senior Member | 600 | C-Rank commission, 10% shop discount |
| 5 | Elite | 1,000 | Guild training facility |
| 6 | Expert | 1,800 | B-Rank commission, 15% shop discount |
| 7 | Master | 3,000 | Personal research lab |
| 8 | Grandmaster | 5,000 | A-Rank commission, 20% shop discount |
| 9 | Legend | 8,000 | Territory management rights |
| 10 | Chairman Candidate | 12,000 | Vote in guild leadership council |

### Reputation Gains
- Complete commissions: +10 ~ +200 (by difficulty)
- Close Rifts: +50 ~ +500 (by tier)
- Donate otherworld materials: converted by material value
- Rescue other Awakeners: +20 ~ +50

---

# Chapter Eight: Worldview

## 8.1 D-Day: The Invasion Begins

**March 15, 2027**, a purple halo appeared above Shinjuku, Tokyo. Within 12 hours Shinjuku fell as the first Erosion Zone. The six Beastman Clans of the otherworld joined forces to open the Main Rift at the World Heart, then spawned hundreds of Secondary Portals worldwide.

Humanity soon discovered: bullets fail in Erosion Zones, missiles fizzle near monsters, electronics short-circuit close to Rifts. It wasn't a lack of firepower — the physical laws were simply unequal.

## 8.2 Awakeners

A tiny fraction of humans gained "The System" when the Rifts opened — a augmentation tool designed for modern humanity by the God of Play, Collector, on commission from the God of Light, Osaikus. The System lets Awakeners level up by slaying monsters, gaining attribute panels, skill points, and a quest system.

## 8.3 Otherworld Geography

| Region | Faction | Stance |
|--------|---------|--------|
| Southeast — Beastman Forest | Six Beastman Clans | Hostile (invasion planners) |
| Northeast — Human Territory | Otherworld humans, White Serpent Tribe, Dwarves | Humans friendly; others neutral |
| Northwest — Nature Realm | Elves, Dark Elves, Treants, Centaurs | Neutral |
| Center — Inner & Outer Seas | Merfolk, Fishmen | Neutral |
| Northeast Wastes | Ancient Battlefield Desert | — |
| Southern Isles | Dragons (Dragon Isle) | Neutral |

## 8.4 Deity System

### Primordial Beings

**World Tree Spirit — Yggdra** Divine Rank 20 | Absolute Neutral
- The will of the World Tree itself. Born alongside the World Heart at the dawn of creation.
- **Forbidden Law: any deity stepping onto the continental land in true form or projection → Yggdra awakens, forcibly expelling all participating gods.**
- "Tolerates" the Beastman invasion of Earth — otherworld matters are not Her concern.
- Relationship with Collector: a crotchety elder and a mischievous grandson. Collector is the only god permitted to come and go freely in the World Tree.

**Ancient Dragon Ancestor — Ignaros, Flame of Nirvana** Divine Rank 20 | Chaotic Neutral | **Asleep**
- The first dragon. Mother of Angerwide. Fell asleep deep in the Dragon Isle volcano after the ancient war.
- If ever awakened → indiscriminately burns everything nearby. Only exception: son Angerwide + those Angerwide wishes to protect (generally other dragons on the isle).
- No one should attempt to wake her.

### Human Side (Friendly)

**God of Light — Osaikus** Divine Rank 19 | Lawful Neutral
- Domains: Sun, Justice, Protection, Cartography, Seafaring, Trade
- The otherworld's only human chief god. Commissioned Collector to build the System.

### Special

**God of Play — Collector** Divine Rank 19 | Chaotic Neutral
- Domains: Time, Space, Games, Illusion, Adventure
- Creator of the System. Yggdra's only favored "grandson."

### Beastman Side (Hostile) — Six Clan Chief Gods

| Clan | Chief God | Divine Rank | Alignment | Core |
|------|-----------|-------------|-----------|------|
| Werewolf | Wolf God · Kotal | 16 | Chaotic Neutral | Forest, Moon, Beast |
| Bearman | Mountain King · Gulam | 17 | Lawful Neutral | Earth, Forging, Contract |
| Catman | Shadow Mother · Sylvia | 15 | Chaotic Neutral | Shadow, Agility, Illusion |
| Black Serpent | Venom Lord · Malkis | 16 | Lawful Evil | Toxin, Forbidden Knowledge, Mind Control |
| Eagleman | Sky King · Zephyros | 15 | Lawful Neutral | Storm, Prophecy, Judgment |
| Foxman | Mirage Princess · Iluna | 17 | Chaotic Neutral | Enchantment, Fate, Thousand-Face Disguise |

### Neutral-Side Deities

| Deity | Divine Rank | Alignment | Core |
|-------|-------------|-----------|------|
| Dragon God · Angerwide | 18 | Lawful Neutral | Element, Storm, Stars, Dragon; son of Ignaros |
| Death God · Fregra | 18 | Neutral Evil | Shadow, Darkness, Death |
| Life Goddess · Lilith | 17 | Neutral Good | Life, Abundance, Love |
| Wisdom God · Herabergen | 17 | Absolute Neutral | Knowledge, Magic, Craft |
| Ice Goddess · Aish | 16 | Lawful Neutral | Glacier, Cold, Exploration |

### Cosmic Phenomenon

**Void Abyss — Abyss** Non-deity | Uncommunicable
- The true cost of Rift pacts. Power borrowed from the void ultimately connects back to the void.
- The root of Creeping Law Erosion — Rift throughput is limited by the Abyss, not Beastman strategy.

---

## 8.5 Neutral Race Diplomacy

| Race | Initial Favorability | Unique Reward |
|------|---------------------|---------------|
| Dwarves | 40 (Neutral) | Rune-customized equipment |
| Elves | 35 (Neutral) | Magic training (Intelligence (INT) +1) |
| Dark Elves | 20 (Cold) | Underground network intel |
| Treants | 30 (Neutral) | Rare wood material |
| Centaurs | 35 (Neutral) | Follower companion |
| Dragons | 10 (Hostile) | Dragon Scale material (Red · Mythic) |
| White Serpent Tribe | 45 (Neutral) | Antidote secret medicine |
| Merfolk | 40 (Neutral) | Underwater exploration gear |
| Otherworld Humans | 70 (Friendly) | Intel + supplies |

### Five Favorability Tiers

| Range | Relation | Interaction |
|-------|----------|-------------|
| 0-19 | Hostile | Refuse contact, may attack |
| 20-39 | Cold | Basic trade, no help offered |
| 40-59 | Neutral | Normal trade, accept commissions |
| 60-79 | Friendly | Discounted trade, provide intel |
| 80-100 | Allied | Military support, shared resources |

---

# Chapter Nine: GM Running Guide

## 9.1 Pacing: the E-C-N-R Cycle

| Phase | Description | Suggested Time Share |
|-------|-------------|----------------------|
| Explore | Players freely explore the environment, gather intel | 25% |
| Combat | Encounter enemies, fight | 35% |
| Narrative | NPC interaction, plot progression | 25% |
| Rest | Recover resources, level up, shop | 15% |

## 9.2 Encounter Design Flow

1. **Set difficulty**: use the Encounter Difficulty Rating (EDR) formula (§4.6)
2. **Design the battlefield**: add 1-3 environmental elements (§4.5 Environmental Interaction)
3. **Configure monsters**: pick suitable Challenge Rating (CR) monsters from the benchmark table
4. **Set AI**: choose a behavior template for each monster type (§4.6)
5. **Calculate rewards**: Experience Points (EXP), Gold, equipment drops

## 9.3 Reward Benchmarks

| Player Level | Gold per Encounter | Experience Points (EXP) per Rift Closed | Equipment Quality |
|--------------|--------------------|------------------------------------------|------------------|
| Lv.1-10 | 30-80 Gold (G) | 100-200 | Mostly White · Common, occasionally Green · Uncommon |
| Lv.11-25 | 80-250 Gold (G) | 200-500 | Mostly Green · Uncommon, occasionally Blue · Rare |
| Lv.26-45 | 250-800 Gold (G) | 500-1,500 | Mostly Blue · Rare, occasionally Purple · Unique |
| Lv.46-70 | 800-2,000 Gold (G) | 1,500-4,000 | Mostly Purple · Unique, occasionally Orange · Legendary |
| Lv.71-100 | 2,000-8,000 Gold (G) | 4,000-10,000 | Mostly Orange · Legendary, Red · Mythic in world events |
| Lv.101+ | 8,000-50,000 Gold (G) | 10,000-30,000 | Orange · Legendary + Red · Mythic |

## 9.4 Creeping Law Erosion Operation

### Track Invasion Progress
- Record the in-game date (counted from D-Day)
- Every 14 days, check whether unclosed Rifts have upgraded
- When each wave arrives, open Rifts of the corresponding tier

### Rift Map Management
- Maintain 3-8 active Rifts per city/region
- Rift tiers should have a gradient (not all high tier)
- After players close a Rift, no new Rift appears at that location within 14 days
- Leave 1-2 "distant Rifts" to give players future goals

## 9.5 Solo Mode GM Guide

| Adjustment | Rule |
|------------|------|
| Enemy count | Halved (−50%) |
| Enemy Hit Points (HP) | −20% |
| Boss Hit Points (HP) | −25% |
| Boss damage | −15% |
| Boss action count | −1 (minimum 1) |
| Experience Points (EXP) | ×1.3 |
| Non-combat Difficulty Class (DC) | −10 |
| Post-battle recovery | 30% Hit Points (HP)/Mana Points (MP) |
| Potion drops | +50% |

### NPC Companion System (optional in Solo Mode)

A solo player may recruit up to 2 NPC companions.

#### Acquiring Companions
Companions may be gained by:
- Story joining (guild assignment, rescued civilian Awakener, etc.)
- Reputation unlock (Guild Reputation Lv.3 recruits 1, Lv.6 recruits a 2nd)
- Diplomacy result (neutral race favorability ≥ 60 recruits a companion of that race)
- GM discretion (any plot-reasonable moment)

#### Companion Attributes
Companions use a simplified data card:
- **Level** = player level × 0.8 (cap Lv.60)
- **Hit Points (HP) / Mana Points (MP)** = use the same-tier values from the monster benchmark table §4.6 by level × 0.35
- **Attributes** = use the corresponding attribute allocation from the GM book §2 beginner templates, multiplying attribute values × (companion level ÷ template suggested level)
- **Skills** = determined by the companion's "role", pick 1-2 suitable skills (including traits) from the player skill compendium
- **No Awakening Skills or Deity Classes**

#### Companion Leveling
- Companions auto-level with the player's character level (no extra Experience Points (EXP) needed)
- On each level-up, Hit Points (HP)/Mana Points (MP)/attributes recalculated per the above formula
- Every 10 levels unlocks one skill (Lv.10/20/30/40/50, one each, chosen from the corresponding class skill table)

#### Companions in Combat
- **Action order**: act after the player, same initiative as the player
- **AI control**: GM uses simplified AI (attack nearest target / protect player / use healing skill)
- Player may spend 1 Swift action to "issue a command" — designate the companion's action target this turn
- Companions cannot use "Master Skills" or "Ultimate Traits"
- At Hit Points (HP) 0, enter Dying State (same as player rules), can be stabilized by player First Aid

#### Companion Death and Replacement
- After a companion dies, a funeral may be held (no resource cost) or revival (requires Lilith deity-granted skill or a Legendary revival item)
- Player may dismiss the current companion (no penalty) and recruit a new one
- New companion level = player level × 0.8 (recalculated by current level)
- A dismissed companion may be re-recruited later, retaining original level

#### Companion Quick Data Card Template
```
[Companion Name] Lv.X | Role (class reference)
Hit Points (HP): X | Mana Points (MP): X | Physical Attack (PATK): X | Magic Attack (MATK): X | Physical Defense (PDEF): X | Magic Defense (MDEF): X
Hit Rate (HIT%): X | Dodge Rate (DGE%): X | Critical Rate (CRT%): X
Skills:
- Skill Name: effect summary
AI Tendency: [Offensive / Defensive / Support]
```

## 9.6 Class System GM Management

### Dual EXP Tracking

Players have two EXP pools to track simultaneously. Suggested after each battle:
1. Announce Character EXP (shared by whole party)
2. Ask the player which "active class" was used this battle
3. That class gains Class EXP (sum of monster EXP × 0.8)
4. If that class's skill was used, extra +30%

### Life Class EXP (non-combat crafting)

Life classes (Blacksmith/Alchemist/Cook, etc.) gain Class EXP per successful craft:

| Class | EXP per Successful Craft | Note |
|-------|:------------------------:|------|
| Blacksmith | 50 + (target Difficulty Class (DC) − check result) × 2 (cap 200) | More precise forging = more EXP |
| Alchemist | 40 + crafted item rarity tier × 20 | White=20, Green=40, Blue=60, Purple=80, Orange=100, Red=120 |
| Cook | 30 + ingredient rarity × 15 | E=15, D=30, C=45, B=60, A=75, S=90 |
| Explorer | 30 (successfully explore one Rift interior) | Per exploration |
| Analyst | 20 (successfully analyze one enemy or item) | Per analysis |
| Merchant | equal to per-trade net profit ÷ 10 | Minimum 5 EXP |
| Negotiator | equal to reputation gained from successful negotiation | — |
| Tracker | equal to tracking distance ÷ 100m | Minimum 10 EXP |

### Class EXP Quick Reference

| Class Level | Cumulative EXP | Main Unlock |
|-------------|---------------|-------------|
| Lv.1 | 0 | 2 skills + trait |
| Lv.3 | 700 | New skill |
| Lv.6 | 3,400 | New skill |
| Lv.10 | 14,200 | Trait evolution |
| Lv.15 | 55,600 | Branch choice |
| Lv.20 | 91,600 | New skill |
| Lv.30 | 176,600 | Trait evolution |
| Lv.40 | 286,600 | Master skill |
| Lv.50 | 496,600 | Ultimate trait |

### Class Change and Adding Classes

- Players may begin training a new class at any time (requires plot plausibility — find a mentor, join training, etc.)
- New class starts at Lv.1
- Sum of all Class Levels ≤ Character Level
- Suggested: after each Long Rest (8-hour sleep), the player may declare a change of "active class"

### Deity Class Trigger Timing

| Deity | Suggested Trigger Scenario | Condition |
|-------|----------------------------|-----------|
| Osaikus | S7 or later | Otherworld human favorability ≥ 80 |
| Collector | S19 | Plot-forced (hard to get free) |
| Kotal | — | After defeating the Wolf God projection, may choose a pact |
| Gulam | S7 | After finding a pact loophole, may speak directly with Gulam |
| Sylvia | S6 | Pass the Catman Hunting Grounds trial |
| Malkis | S10 | Accept the Black Serpent's terms |
| Zephyros | S10 | After refusing Malkis, may turn to Eagleman |
| Iluna | S18 | Pass the City of a Thousand Faces |
| Angerwide | S14 | Pass the Dragon God's trial |
| Fregra | S11 | Gazed upon by the Death God while Dying |
| Lilith | After S16 | Rescue large numbers of civilians |
| Herabergen | S14 side line | Find the Wisdom God's library in the World Tree |
| Aish | S9 | Delve deep into the Ancient Battlefield Desert |

---

# Chapter Ten (original): Scenario Framework (Five Seasons, 20 Scenarios)

## Season One "Awakening Chapter" Lv.1-20

| ID | Scenario | Level | Core Conflict | Expected Length |
|----|----------|-------|---------------|-----------------|
| S1 | Day of Awakening | Lv.1-5 | Character awakening + first Rift encounter | 1-2 sessions |
| S2 | Guild Summons | Lv.3-8 | Join the guild + first official commission | 1-2 sessions |
| S3 | Depths of the Erosion Zone | Lv.7-14 | Delve into a D-Rank Rift interior | 2-3 sessions |
| S4 | Shadow of the Six Pillars | Lv.12-20 | First encounter with Beastman clan vanguard | 2-4 sessions |

## Season Two "Resistance Chapter" Lv.21-40

| ID | Scenario | Level | Core Conflict |
|----|----------|-------|---------------|
| S5 | Expedition Prep | Lv.21-27 | Gather rare materials needed to cross the Rift |
| S6 | Through the Rift | Lv.25-32 | First entry into the otherworld, meet neutral races |
| S7 | Allies and Enemies | Lv.28-36 | Build ties with otherworld humans + clan internal conflicts |
| S8 | B-Rank Threat | Lv.33-40 | First B-Rank Rift appears |

## Season Three "Expedition Chapter" Lv.41-60

| ID | Scenario | Level | Core Conflict |
|----|----------|-------|---------------|
| S9 | Abyssal Expedition | Lv.41-48 | Deep into the Beastman Forest border |
| S10 | Clan Intrigue | Lv.46-53 | Uncover the internal conflicts between clans |
| S11 | Shadow of the God | Lv.50-57 | First sense the presence of clan chief gods |
| S12 | The Kingdom's Plea | Lv.55-60 | Otherworld human kingdom requests help against Beastmen |

## Season Four "Final Battle Chapter" Lv.61-80

| ID | Scenario | Level | Core Conflict |
|----|----------|-------|---------------|
| S13 | Total War | Lv.61-68 | Earth's full defense war |
| S14 | Dragon Isle Expedition | Lv.66-73 | Seek the Dragons' aid |
| S15 | Eve of the Godwar | Lv.71-77 | Prepare to confront clan chief gods head-on |
| S16 | Descent of the Six Pillars | Lv.75-80 | The six clan chief-god projections begin to descend |

## Season Five "Godfall Chapter" Lv.81-100+

| ID | Scenario | Level | Core Conflict |
|----|----------|-------|---------------|
| S17 | Gate of the Gods | Lv.81-88 | Open the path to the divine realm |
| S18 | The Betraying Fox-God | Lv.87-94 | Iluna (Foxman chief god)'s double game |
| S19 | Collector's Final Game | Lv.93-100 | Collector appears, presents the final trial |
| S20 | Fate of Two Worlds | Lv.100+ | Final battle, decides the future of two worlds |

### Five Possible Endings

| Ending | Condition | Result |
|--------|-----------|--------|
| Separation | Fully close the Main Rift | Two worlds permanently isolated, otherworld humans stay in the modern world |
| Conquest | Defeat all clan chief gods | Humanity reverse-colonizes the otherworld |
| Coexistence | Reach a multi-party peace accord | Build a cross-world alliance, jointly manage Rifts |
| Sacrifice | Player sacrifices self to close the Rift | Player becomes the new guardian of the World Heart |
| Corruption | Accept Malkis's terms | Player becomes the new lord of the Black Serpent Clan |

---

## 10.1 Key NPC Data Cards

The following are key NPCs from Season One to Season Two (S1-S8), for the GM to use directly in the corresponding scenarios.

### S1 Day of Awakening

```
[Survivor · Tanaka (ordinary citizen)] Lv.0 | Civilian
Hit Points (HP): 20 | Mana Points (MP): 0 | Physical Attack (PATK): 2 | Magic Attack (MATK): 0 | Physical Defense (PDEF): 0 | Magic Defense (MDEF): 0
Hit Rate (HIT%): 30 | Dodge Rate (DGE%): 10 | Critical Rate (CRT%): —
Special Abilities: none
AI: Follow players, avoid combat
Use: Must be escorted by players across the Erosion Zone edge. Survival grants extra Experience Points (EXP) +30.
```

### S2 Guild Summons

```
[Intelligence Officer · Yamada (guild liaison)] Lv.8 | Guild NPC
Hit Points (HP): 90 | Mana Points (MP): 40 | Physical Attack (PATK): 25 | Magic Attack (MATK): 35 | Physical Defense (PDEF): 15 | Magic Defense (MDEF): 18
Hit Rate (HIT%): 68 | Dodge Rate (DGE%): 22 | Critical Rate (CRT%): 8%
Role: Analyst type (non-combat personnel)
Skills: Intelligence Gathering (Difficulty Class (DC) 50 Wisdom (WIS) check to gain target intel), Emergency Evacuation Teleport (1×/day, teleport back to guild)
Use: S2 introduces guild operations; S4 and later provides intel support. Favorability affects intel accuracy.
```

### S3 Depths of the Erosion Zone

```
[Drifter Awakener · Gary (D-Rank lone wolf)] Lv.12 | Human Awakener
Hit Points (HP): 145 | Mana Points (MP): 50 | Physical Attack (PATK): 55 | Magic Attack (MATK): 20 | Physical Defense (PDEF): 35 | Magic Defense (MDEF): 20
Hit Rate (HIT%): 72 | Dodge Rate (DGE%): 30 | Critical Rate (CRT%): 12%
Weapon: Demon Hunter Dagger (Green · Uncommon, Physical Attack (PATK)+5, Hit Rate (HIT%)+5% vs monsters)
Skills: Lethal Thrust (Base 30, MP10, Critical Rate (CRT%)+15%), Smoke Bomb (can help players disengage)
AI: Predator type. Initially hostile (mistakes players for invaders); negotiation Difficulty Class (DC) 60 can turn him friendly.
Use: Can be recruited as the first companion (if the player persuades him to join).
```

### S4 Shadow of the Six Pillars

```
[Werewolf Scout Captain · Gruk] Lv.18 | Challenge Rating (CR) 16 | Beastman-type
Hit Points (HP): 500 | Mana Points (MP): 80 | Physical Attack (PATK): 95 | Magic Attack (MATK): 10 | Physical Defense (PDEF): 55 | Magic Defense (MDEF): 25
Hit Rate (HIT%): 78 | Dodge Rate (DGE%): 28 | Critical Rate (CRT%): 15%
Damage Type: Slashing (claws) + Piercing (fangs)
Resistance: Shadow ×0.5 | Weakness: Holy ×1.5
Special Abilities:
- Pack Command: summon 1d3 Shadow Wolves (Lv.12, Hit Points (HP) 150)
- Tearing Bite: on hit, add Bleed (2 turns, Physical Attack (PATK)×0.2×stacks)
- Can talk: if the player chooses negotiation (Difficulty Class (DC) 70), Gruk reveals the Beastmen are collecting "World Heart Shards"
AI: Commander type. At Hit Points (HP) < 30%, retreats to report to the clan.
Drop: 350 Experience Points (EXP), 80 Gold (G), Wolf Clan Necklace (Green · Uncommon accessory, Dodge Rate (DGE%)+5%)
```

### S5 Expedition Prep

```
[Dwarf Forge Master · Balder (neutral race NPC)] Lv.30 | Dwarf
Hit Points (HP): 400 | Mana Points (MP): 100 | Physical Attack (PATK): 80 | Magic Attack (MATK): 40 | Physical Defense (PDEF): 90 | Magic Defense (MDEF): 60
Hit Rate (HIT%): 75 | Dodge Rate (DGE%): 15 | Critical Rate (CRT%): 10%
Role: Blacksmith type (non-combat personnel, can provide forging services)
Skills: Material Appraisal, Rune Forging, Masterwork
Use: In S5 can help forge the mana-adaptation gear needed to cross the Rift. Favorability affects forging discount and quality.
```

### S6-S7 First Contact with the Otherworld

```
[Archmage · Eileen Starwhisper (Demigod, humanity's strongest mage)] Lv.85 | Warlock · Elementalist branch | Human-side Demigod
Hit Points (HP): 1,500 | Mana Points (MP): 1,200 | Physical Attack (PATK): 120 | Magic Attack (MATK): 380 | Physical Defense (PDEF): 150 | Magic Defense (MDEF): 280
Hit Rate (HIT%): 92 | Dodge Rate (DGE%): 40 | Critical Rate (CRT%): 18%
Damage Type: Fire/Frost/Lightning (selectable) | Resistance: Magic ×0.5 | Weakness: Physical ×1.2
Role: Non-combat NPC — Eileen doesn't fight, responds to provocation with academic arrogance.
Skills (plot reference only, she won't directly join combat):
- Element Storm (Base 60, three-element composite, 2-zone AoE)
- Mana Resonance (after 3 spells → next 2 free Mana Points (MP))
- Element Avatar (immune to self-chosen element)
AI: Does not join combat. If the player shows knowledge or raises academic questions → opens dialogue and intel.
Use: S6 first contact representative of the otherworld human intellectual circle. S7 can provide intel support at the Capital Magic Academy.
At favorability ≥ 70: opens Herabergen library sub-collection access (gains skill "Academic Training" INT check +5).
See `catalogs/半神圖鑑.md`.
```

### S8 First B-Rank Rift

```
[Guild Mole · ?? (intel leaker)] Lv.28 | Human Awakener
Hit Points (HP): 380 | Mana Points (MP): 150 | Physical Attack (PATK): 75 | Magic Attack (MATK): 110 | Physical Defense (PDEF): 40 | Magic Defense (MDEF): 50
Hit Rate (HIT%): 78 | Dodge Rate (DGE%): 25 | Critical Rate (CRT%): 12%
Class: Shadowrunner · Infiltrator branch Lv.18
Skills: Stealth, Assassinate, Smoke Bomb, Shadow Bind, Lethal Poison
True identity: decided by the GM — could be an Awakener threatened by the Black Serpent Clan, or a willing inside agent serving the Beastmen.
AI: Uses Shadowrunner tactics in combat. After exposed, flees (Difficulty Class (DC) 70 Dexterity (DEX) check to pursue).
Use: The "guild mole clue" introduced in S5 is exposed in S8.
```

> **Season Three to Five (S9-S20) NPCs**: Because they involve multiple branch choices and deity routes, the GM is advised to select suitable values from the above templates to customize based on the players' chosen ending direction. Data for key NPCs (chief-god projections, Collector) are in `catalogs/神祇完整圖鑑.md` and `catalogs/半神圖鑑.md`.

---

# Chapter Eleven: Otherworld Exploration

## 11.1 Reverse Crossing

- Condition: requires ≥ C-Rank Rift + mana-adaptation gear (MAG)
- Check: Difficulty Class (DC) 60 mana-sync check
- Side effect: after crossing, Difficulty Class (DC) 40 stun check; failure means Disadvantage in the first battle

## 11.2 Otherworld Laws

| Rule | Effect |
|------|--------|
| Mana Density | 3× → magic effect +20%, Mana Points (MP) cost +10% |
| Tech Failure | All modern tech (phones, firearms) unusable |
| Recovery Acceleration | Natural recovery speed ×2 |
| Mana Heat | Every 8 hours Difficulty Class (DC) 60 Constitution (CON) check, failure gains 1 stack of Mana Heat (stacks until unconscious) |

## 11.3 Neutral Race Contact Protocol

1. Detect (Difficulty Class (DC) set by distance)
2. Approach (observe cultural taboos, else favorability −5 ~ −20)
3. Dialogue (language barrier requires Difficulty Class (DC) 40 Intelligence (INT) decryption)
4. Intent Declaration (Difficulty Class (DC) 60 negotiation)
5. Response (determined by favorability)

---

# Appendix

## A. Quick Reference Card

### GM Combat Round
1. Announce initiative order
2. Player turn: ask for actions
3. Monster turn: execute per AI template
4. Resolve environmental effects (if any)
5. Status duration −1
6. End of round

### Difficulty Reference
- Simple encounter: Encounter Difficulty Rating (EDR) 0.3-0.7, 2-3 same-tier monsters
- Boss encounter: Encounter Difficulty Rating (EDR) 0.7-1.0, 1 Boss + 0-2 minions
- High-difficulty encounter: Encounter Difficulty Rating (EDR) 1.0-1.3, increased count or Challenge Rating (CR)

## B. Term Reference

| Term | Abbr | Term | Abbr |
|------|------|------|------|
| Strength (STR) |  | Hit Points (HP) |  |
| Dexterity (DEX) |  | Mana Points (MP) |  |
| Constitution (CON) |  | Physical Attack (PATK) |  |
| Intelligence (INT) |  | Magic Attack (MATK) |  |
| Wisdom (WIS) |  | Physical Defense (PDEF) |  |
| Spirit (SPI) |  | Magic Defense (MDEF) |  |
| Hit Rate (HIT%) | Difficulty Class (DC) |  |  |
| Dodge Rate (DGE%) | Challenge Rating (CR) |  |  |
| Critical Rate (CRT%) | Encounter Difficulty Rating (EDR) |  |  |
| Effective Hit Rate | Effective Hit Rate (EHit%) | Experience Points (EXP) |  |
| Gold | Gold (G) | Silver | S |
| Copper | C | Global Awakened Guild Alliance | GAGA |
