# Dungeon Lord: Core Resolution Mechanics Draft (Revised v2.0)

> **Design Version**: Draft v2.0 (cross-review revision)
> **Dice System**: d6 Dice Pool (5–6 = Success, a 6 may explode for +1 die)
> **Attribute Range**: 1–5 (attribute value = number of base dice)
> **Complexity**: Medium strategy
> **Revisions**: Unified attribute naming / initial point adjustment / territory expansion mechanic / monster allocation mechanic / monster economy ability table / captive system simplification / dual-track skill tree confirmation / dungeon attribute mapping

---

## Table of Contents

1. [Dice System](#i-dice-system)
2. [Attribute System](#ii-attribute-system)
3. [Skill System](#iii-skill-system)
4. [Check Rules](#iv-check-rules)
5. [Dungeon Lord Attributes & Dungeon Derived Attribute Mapping](#v-dungeon-lord-attributes--dungeon-derived-attribute-mapping)
6. [Territory Expansion Dice Pool Mechanic](#vi-territory-expansion-dice-pool-mechanic)
7. [Monster Allocation Dice Pool Mechanic](#vii-monster-allocation-dice-pool-mechanic)
8. [Random Monster Economy Ability Generation Table](#viii-random-monster-economy-ability-generation-table)
9. [Captive System Core Checks](#ix-captive-system-core-checks)
10. [Dual-Track Skill Tree & Archetype Abilities](#x-dual-track-skill-tree--archetype-abilities)
11. [Mathematical Validation](#xi-mathematical-validation)
12. [Glossary](#xii-glossary)

---

## I. Dice System

### 1.1 Base Rules

This ruleset uses the **d6 Dice Pool** system:

| Die Face | Result |
|------|------|
| 6 | **Success** + **Explosion (Critical)**: counts as 1 success and grants +1 extra die (may chain) |
| 5 | **Success**: counts as 1 success |
| 1–4 | No effect |

**Design Intent**: The 5–6 success rule (1/3 hit rate) yields a moderate success expectation. A 6-explosion introduces "surprise moments," giving every roll dramatic potential. Each die's expected successes = 0.4, making pool growth predictable yet still variable.

### 1.2 Dice Pool Composition

```
Dice Pool = Attribute Dice + Skill Dice + Modifier Dice
```

| Source | Description | Cap |
|------|------|------|
| **Attribute Dice** | Attribute value = number of base dice (1–5) | 5d6 |
| **Skill Dice** | Skill level grants extra dice (0–5) | +5d6 |
| **Environmental Bonus** | Temporary extra dice from gear/terrain/aid | +3d6 |
| **Environmental Penalty** | Removes dice (lowest to highest) | −3d6 |
| **Advantage** | Fixed pre-roll dice (rare; usually from archetype ability or magic) | +2d6 |
| **Disadvantage** | Pre-roll dice removal (removes highest N dice among Attribute + Skill) | −2d6 |

**Pool Cap**: A single check's dice pool does not exceed 10d6.

### 1.3 Margin of Success Tiers

| Net Successes | Result Tier | Description |
|----------|---------|------|
| 0 | **Failure** | Action fails to meet goal; possible minor negative consequence |
| 1 | **Partial Success** | Goal achieved but with a cost, delay, or reduced effect |
| 2 | **Full Success** | Goal achieved cleanly |
| 3 | **Critical Success** | Exceeds expectations; grants an extra benefit |
| 4+ | **Legendary Success** | Effect doubled or unlocks hidden benefit |

**Design Intent**: 0 successes ≠ disaster (unless DC is extreme). 1 success still advances the game, avoiding the frustration of "nothing happened." 3+ successes create highlight moments.

### 1.4 Difficulty Levels

| Difficulty | Successes Required | Typical Scenario |
|------|-----------|---------|
| Easy | 1 | Command loyal servants, basic construction, simple ritual |
| Standard | 2 | Build a room, interrogate a T2 captive, craft a trap, recruit a monster |
| Hard | 3 | Interrogate a high-will captive, magic trap, deep excavation, elite ritual |
| Extreme | 4 | Convert a legendary captive, ultimate ritual, intimidate a legendary adventurer |
| Epic | 5+ | World-shaping magic, duels between Abyss Lords |

### 1.5 Key Probability Quick Reference

| Pool | P(≥1 success) | P(≥2 successes) | P(≥3 successes) | Expected Successes |
|------|-----------|-----------|-----------|-----------|
| 1d6 | 33.3% | 5.6% | — | 0.40 |
| 2d6 | 55.6% | 18.5% | 3.1% | 0.80 |
| 3d6 | 70.4% | 33.3% | 11.1% | 1.20 |
| 4d6 | 80.2% | 48.1% | 21.0% | 1.60 |
| 5d6 | 86.8% | 60.5% | 32.2% | 2.00 |
| 6d6 | 91.2% | 70.8% | 43.7% | 2.40 |
| 7d6 | 94.1% | 78.9% | 54.4% | 2.80 |
| 8d6 | 96.1% | 85.1% | 64.1% | 3.20 |

> **Sweet Spot**: 3d6–5d6 is the main range for most player checks. At 3d6, Standard difficulty (needs 2 successes) has ~33% success rate — slightly challenging; at 4d6 it rises to ~48%; at 5d6 it reaches ~60%, the best feel.

---

## II. Attribute System

### 2.1 The Five Core Attributes

> **Cross-review unified naming** — fully aligned with the Character System and world setting.

| Short | Full Name | Chinese | Core Domain | Typical Check Scenarios |
|------|------|------|----------|------------|
| **Cunning (CUN)** | Cunning | Cunning | Trap design, ambush, deception, intelligence | Set traps, forge intel, hide passages, counter-recon, infiltrate |
| **Dominion (DOM)** | Dominion | Dominion | Interrogation, intimidation, commanding servants, negotiation | Command servants, interrogate captives, maintain discipline, dark-coin trade talks |
| **Arcana (ARC)** | Arcana | Arcana | Magic knowledge, rituals, curses, enchantment | Cast spells, magic research, dispel, soul-binding, build mana nodes |
| **Industry (IND)** | Industry | Industry | Construction, gathering, forging, engineering | Expand rooms, gather resources, forge gear, engineer structures, excavate |
| **Warfare (WAR)** | Warfare | Warfare | Monster command, tactical deployment, defense, deterrence (incl. fear/reputation) | Command monster combat, deploy defenses, spread terror, deter enemies, chase/flee |

### 2.2 Attribute Value Correspondence

| Attribute Value | Title | Base Pool | World Standing |
|--------|------|---------|---------|
| 1 | Novice | 1d6 | A newly inherited Lord, or a declining old Lord |
| 2 | Qualified | 2d6 | An inexperienced but established Abyss Lord |
| 3 | Proficient | 3d6 | A seasoned Lord who has repelled many adventurer waves |
| 4 | Expert | 4d6 | A threat flagged by the Adventurers' Guild |
| 5 | Legendary | 5d6 | An Abyssal legend even the Order of Light fears |

### 2.3 Attribute Point Allocation

| Item | Rule |
|------|------|
| **Initial Points** | **12 points** (revised: down from 15, because archetypes grant attribute bonuses; low start creates greater differentiation) |
| **Attribute Floor** | 1 (cannot go below 1) |
| **Initial Attribute Cap** | 4 (cannot reach 5 at creation; archetype bonus may break this) |
| **Archetype Bonus** | Added after choosing an archetype (e.g., Mad Sorcerer gets Arcana (ARC)+2, reaching 5 at start) |
| **Growth** | +1 attribute point per dungeon level gained |
| **Endgame Cap** | 5 (Legendary) |

**Allocation Examples** (12 points, attributes start at 1):
- **Balanced**: Cunning (CUN) 3 / Dominion (DOM) 3 / Arcana (ARC) 3 / Industry (IND) 3 / Warfare (WAR) 3 (each +2, 10 points spent, 2 points free)
- **Specialized**: Cunning (CUN) 2 / Dominion (DOM) 2 / Arcana (ARC) 4 / Industry (IND) 3 / Warfare (WAR) 4 (favors Warfare and Arcana)
- **Niched**: Cunning (CUN) 4 / Dominion (DOM) 2 / Arcana (ARC) 2 / Industry (IND) 4 / Warfare (WAR) 2 (favors Cunning and Industry)

> **Design Intent**: 12 points means average attribute ~2.4, i.e. "qualified-plus." Archetype bonuses drive players to push their highest attribute to 4–5, forming clear strengths and weaknesses. Math validation shows the 3–5 dice sweet spot is unaffected — only the initial spread is wider, increasing reliance on archetype bonuses.

### 2.4 Old Attribute Name Mapping (Migration Reference)

| Old Name | New Name | Note |
|------|------|------|
| DRE (Dread / fear) | WAR (Warfare) | Fear/reputation/deterrence unified under Warfare; WAR covers broader tactical command |

---

## III. Skill System

### 3.1 The 20 Skill Trees (Universal Growth System)

> **Cross-review confirmed**: These 20 skill trees are retained as the universal growth system for all Dungeon Lords. The Character System's archetype-exclusive abilities stack on top; the two do not conflict — skills represent "acquired craft," archetype abilities represent "innate talent."

Each attribute maps to 4 skills. Skill level 0–5; leveling costs skill points (gained when dungeon level rises, +1 skill point).

#### Cunning (CUN) Skills

| # | Skill | Description | Typical Use |
|---|------|------|---------|
| 1 | **Trap Craft** | Design, build, hide traps | Trap workshop crafting check, raise trap trigger difficulty |
| 2 | **Deception** | Forge intel, disguise dungeon entrance, mislead adventurers | Spread false intel, hide true dungeon Depth, fake rooms |
| 3 | **Intelligence** | Scout adventurer movements, infiltrate guild, decode intel | Recon outpost check, read captive confessions, predict invasion |
| 4 | **Stealth** | Hide passages, ambush deployment, assassination | Monster ambush check, secret passage building, assassination orders |

#### Dominion (DOM) Skills

| # | Skill | Description | Typical Use |
|---|------|------|---------|
| 5 | **Interrogation** | Question captives, extract intel, psychological pressure | Captive Willpower (WIL) opposed, learn Adventurers' Guild movements |
| 6 | **Intimidation** | Frighten enemies, awe adventurers, maintain order | Lower adventurer morale, suppress captive riots, deter invaders |
| 7 | **Command** | Command servants, coordinate defense, battlefield dispatch | Command monsters in combat, mobilize servant defense |
| 8 | **Negotiation** | Trade with dark merchants, ransom with Adventurers' Guild | Trade check, captive ransom talks, Abyssal Council diplomacy |

#### Arcana (ARC) Skills

| # | Skill | Description | Typical Use |
|---|------|------|---------|
| 9 | **Ritual Magic** | Sacrifice, curses, empowerment rituals | Altar ritual check, sacrifice captives, empower servants |
| 10 | **Curse & Enchant** | Cast curses, enchant items, soul-binding | Magic trap crafting, gear enchant, curse adventurers |
| 11 | **Arcane Knowledge** | Decode ancient magic texts, appraise magic items | Research chamber check, appraise adventurer magic items |
| 12 | **Alchemy** | Brew potions, refine Mana Crystals, mutation experiments | Mad Sorcerer mutation check, optimize Mana Crystal output |

#### Industry (IND) Skills

| # | Skill | Description | Typical Use |
|---|------|------|---------|
| 13 | **Construction** | Room building & upgrade, structural design | Build/upgrade room check, optimize dungeon layout |
| 14 | **Gathering** | Mine extraction, resource gathering, prospecting | Mine output check, resource prospecting, vein discovery |
| 15 | **Forging** | Gear manufacturing, weapons/armor, machine parts | Forge gear, build mechanical sentry parts |
| 16 | **Engineering** | Large engineering, excavation, mechanical devices | **Territory expansion excavation check**, drilling platforms, giant devices |

#### Warfare (WAR) Skills

| # | Skill | Description | Typical Use |
|---|------|------|---------|
| 17 | **Monster Command** | Command monster combat, coordinated attacks, tactical synergy | **Monster combat dice pool check**, coordinated attack command |
| 18 | **Tactical Deployment** | Defense layout, force allocation, terrain use | **Defense deployment check**, pre-fortification bonus |
| 19 | **Fortification** | Defensive structures, walls, barricades, reinforcement | Raise room Defense value, build defensive facilities |
| 20 | **Deterrence** | Spread terror, psychological war, reputation use | Lower invasion Tier, deterrence negotiation, Infamy (INF) use |

### 3.2 Skill Level & Bonus

| Skill Level | Title | Bonus Dice |
|----------|------|------|
| 0 | Untrained | +0d6 |
| 1 | Apprentice | +1d6 |
| 2 | Journeyman | +2d6 |
| 3 | Expert | +3d6 |
| 4 | Master | +4d6 |
| 5 | Legendary | +5d6 |

### 3.3 Attribute–Skill Mapping (Quick Reference)

| Attribute | Skill 1 | Skill 2 | Skill 3 | Skill 4 |
|------|-------|-------|-------|-------|
| Cunning (CUN) | Trap Craft | Deception | Intelligence | Stealth |
| Dominion (DOM) | Interrogation | Intimidation | Command | Negotiation |
| Arcana (ARC) | Ritual Magic | Curse & Enchant | Arcane Knowledge | Alchemy |
| Industry (IND) | Construction | Gathering | Forging | Engineering |
| Warfare (WAR) | Monster Command | Tactical Deployment | Fortification | Deterrence |

---

## IV. Check Rules

### 4.1 Standard Check

**When Used**: Player takes a proactive action whose result is uncertain and whose failure has meaningful consequences.

**Procedure**:
1. GM announces difficulty level (successes required)
2. Player builds dice pool (Attribute Dice + Skill Dice + Modifier Dice)
3. Player rolls, counts successes
4. Compare against difficulty to determine result

**Rule Entry**:
> Roll all d6 in the pool. Each 5–6 counts as 1 success. Each 6, after counting, grants +1 die (may chain). Net successes ≥ difficulty means the action succeeds.

**Example**:
> A Necromancer Lord wants to interrogate a T3 Paladin captive. GM sets difficulty "Hard (3 successes)." Player has DOM=4, Interrogation skill=2, and the prison Lv2 gives +1 modifier die, pool=7d6. Rolls: 6,6,5,5,3,2,1 → two 6s each count 1 success + each grant 1 die, two 5s each count 1 success. Extra dice: 5,2 → +1 more success. Total 5 successes, net = 5 − 3 difficulty = Critical Success (MoS=2). Captive's will breaks; GM grants extra intel on a high-ranking Adventurers' Guild member.

### 4.2 Opposed Check

**When Used**: Both sides actively contest (interrogation vs will, stealth vs scouting, flee vs chase).

**Procedure**:
1. Both sides build their dice pools
2. Both sides roll simultaneously
3. **Net Successes = Active side's successes − Opposed side's successes**
4. Net successes ≥ 0: active side wins (net successes = margin of success)

**Rule Entry**:
> Captive Willpower (WIL) opposed by interrogation: interrogator rolls Dominion (DOM) pool + Interrogation skill; captive rolls Willpower (WIL) pool. If interrogator's successes > captive's successes, will drops; the difference determines drop magnitude.

**Example**:
> An Abyssal Overlord interrogates a T3 captive (WIL=5). Overlord Dominion (DOM)=4 + Interrogation 2 = 6d6. Captive Willpower (WIL)=5d6. Overlord rolls: 6,5,5,4,2,1 → 3 successes + extra die (3) no success = 3 successes. Captive rolls: 6,5,4,3,2 → 2 successes + extra die (5) = 3 successes. Net = 0 — a tie! The captive grits through this round, but the Overlord also learns the captive's weakness (+1 die next round).

### 4.3 Team Check

**When Used**: Multiple characters cooperate toward the same goal.

**Rule Entry**:
> Designate one lead roller who rolls the full pool. Each meaningful helper grants +1 modifier die (max +3). If the lead fails and a helper has that skill at level ≥3, spend 1 resource to reroll once (once per scene).

**Example**:
> A Goblin Tinkerer (IND=5, Engineering=4) leads a deep excavation; two cultists (Engineering skill=1 and 0) assist. Lead pool = Industry (IND)5 + Engineering 4 = 9d6, assist +2d6 = 11d6, capped to 10d6. Rolls 10d6…

### 4.4 Critical Success & Critical Failure

**Critical Success**:
- Trigger: Net successes ≥ 3, or three or more 6s rolled (whichever comes first)
- Effect: Beyond achieving the goal, GM grants one extra benefit (lower later difficulty, find hidden resource, gain intel, extra output, etc.)

**Critical Failure**:
- Trigger: Successes = 0 and three or more 1s in the pool
- Effect: Action fails with an unexpected negative event (see each subsystem's accident/risk table)

### 4.5 Advantage & Disadvantage

**Advantage**:
- Add X dice before rolling
- Sources: archetype ability, magic amplification, perfect intel, high ground/terrain
- Cap: +2d6

**Disadvantage**:
- Before rolling, remove X highest dice from the pool (not random removal — remove the largest)
- Sources: injury, curse, harsh environment, fear effect
- Floor: pool never below 1d6

> **Design Intent**: Disadvantage removes "highest" rather than "random" — harsher than random removal, fitting the "luck isn't on your side" narrative. A 5d6 expert under Disadvantage −2 loses their two best dice, and the best remaining among the 3d6 are gone, greatly lowering explosion chance.

---

## V. Dungeon Lord Attributes & Dungeon Derived Attribute Mapping

### 5.1 The Five Dungeon Derived Attributes

The Character System defines five independent dungeon attributes (range 1–15), mapped to the Lord's attributes as follows:

| Dungeon Attr | Short | Range | Meaning | Linked Lord Attr | Mapping |
|----------|------|------|------|-------------|---------|
| **Depth** | Depth (DEP) | 1–15 | Dungeon scale & layers | Industry (IND) | DEP determines max buildable rooms, max monster capacity, **max territory expansion count** |
| **Infamy** | Infamy (INF) | 1–15 | Notoriety & legend | Warfare (WAR) | INF determines invading adventurer Tier/frequency, Deterrence (Warfare (WAR)) check + dice (every 3 INF = +1 die) |
| **Defense** | Defense (DEF) | 1–15 | Fortification strength | Warfare (WAR) | DEF used for invasion defense value, **captive escape opposed pool** (roll DEF pool), Fortification (Warfare (WAR)) check |
| **Wealth** | Wealth (WLH) | 1–15 | Economic power & reserve | Industry (IND) | WLH determines resource storage cap, Trade/Negotiation (Industry (IND)) check + dice (every 5 WLH = +1 die), vault capacity |
| **Magic** | Magic (MAG) | 1–15 | Mana seepage & rituals | Arcana (ARC) | MAG determines Mana Crystal storage cap, Ritual Magic (Arcana (ARC)) check + dice (every 3 MAG = +1 die), magic room efficiency |

### 5.2 Dungeon Attribute Dice Pool Derivation Rules

Dungeon attributes **are not directly dice pools** (they are scale/threshold stats), but grant bonus dice in specific scenarios:

| Scenario | Pool Source | Dungeon Attr Contribution |
|------|---------|-------------|
| Captive escape opposed | Defense (DEF) pool | Roll DEF value's corresponding dice directly (DEF=5 → roll 5d6) |
| Adventurer invasion difficulty | Warfare (WAR) + Deterrence | Infamy (INF) gives modifier dice (every 3 = +1 die) |
| Trade/economy action | Industry (IND) + Negotiation/Gathering | Wealth (WLH) gives modifier dice (every 5 = +1 die) |
| Ritual/magic research | Arcana (ARC) + Ritual Magic/Arcane Knowledge | Magic (MAG) gives modifier dice (every 3 = +1 die) |
| Territory expansion | Industry (IND) + Engineering | Depth (DEP) gives no bonus dice but sets expansion count cap |

### 5.3 Derived Attribute Cap Reference

| Dungeon Level | DEP Cap | DEF Base | WLH Base | MAG Base | INF Base |
|----------|---------|---------|---------|---------|---------|
| 1 | 2 | 1 | 1 | 1 | 1 |
| 3 | 4 | 2 | 2 | 2 | 3 |
| 5 | 7 | 3 | 3 | 3 | 5 |
| 7 | 11 | 5 | 5 | 5 | 7 |
| 9 | 15 | 7 | 7 | 7 | 9 |
| 12 | 24 | 10 | 10 | 10 | 12 |
| 15 | 34 | 15 | 15 | 15 | 15 |

---

## VI. Territory Expansion Dice Pool Mechanic

> **Core addition**: The Dungeon Lord digs outward to expand, growing the dungeon map.

### 6.1 Excavation Check

**When Triggered**: Player spends 1 action and pays resources to expand-excavate.

| Item | Content |
|------|------|
| **Dice Pool** | Industry (IND) + Engineering skill |
| **Opposed Difficulty** | Starts at 2; +1 each successful expansion (cumulative) |
| **Resource Cost** | Building Materials × (current DEP ÷ 2, rounded up), Dark Coins ×2 |
| **Action Cost** | 1 action |

**Rule Entry**:
> Lord rolls Industry (IND) pool + Engineering skill dice. Successes ≥ current expansion difficulty means excavation succeeds. Net successes determine result tier.

**Example**:
> Goblin Tinkerer's first expansion (difficulty=2). Industry (IND)=4 + Engineering=3 = 7d6. Rolls 6,5,5,4,3,2,1 → 3 successes + extra die (3) = 3 successes. Net = 3−2 = 1 result. Dug a small space, can build 1 basic room. Next expansion difficulty rises to 3.

### 6.2 Margin of Success Result Table

| Net Successes | Result Tier | Effect |
|----------|---------|------|
| 0 | **Excavation Failed** | Hit hard rock/underground river/cave-in, **Building Materials cost doubled**, location cannot be re-excavated |
| 1 | **Small Space** | Dug a small cave, can build **1 basic room** |
| 2 | **Medium Space** | Dug a mid cave, can build **2 basic rooms or 1 large room**; also roll 1d6, 5–6 finds a resource vein (specified resource output +1/turn) |
| 3 | **Large Cave** | Dug a large space, can build **3 basic rooms or 1 large + 1 basic room**; auto-discover 1 vein; roll 1d6, 4–6 finds a natural mana node (all magic rooms on that floor +25% efficiency) |
| 4+ | **Legendary Discovery** | Large cave + natural mana node + roll 1d6: 1–3 rare vein (double resource output), 4–5 ancient ruin (unlock special research project), 6 natural portal (connects to other Abyssal regions, unlocks new diplomacy/trade options) |

### 6.3 Expansion Risk Table (d6, triggered on excavation failure)

| d6 | Risk Event | Effect |
|----|---------|------|
| 1 | **Cave-in** | Tunnel fully collapses, lose all invested Building Materials, and 1 adjacent room is damaged (offline 1 turn for repair, repair cost = 50% of room build cost) |
| 2 | **Disturb Underground Beasts** | Release a group of underground creatures (power = current dungeon level ÷ 2). Immediately triggers a small encounter. If no monster deployed on that floor, the beasts flood the nearest room causing destruction |
| 3 | **Accidental Surface Breach** | Dug an unexpected rift to the outside! Infamy (INF) +2 immediately (adventurers found a new entrance), next-turn invasion chance doubled. But the rift can be converted to a "fake entrance" — Trap Workshop can deploy 1 free trap there |
| 4 | **Mana Leak** | Pierced a mana vein; all rooms on that floor lose 50% mana-related output this turn, Magic (MAG) temporarily −1 (recovers after 1 turn). But the floor gains a temporary mana boost — all Arcana (ARC) checks +1 die |
| 5 | **Underground River** | Surging river floods the dig site! Location permanently unbuildable (but can be converted to a special room "River Docks" — unlocks water trade/escape routes) |
| 6 | **Abyssal Anomaly** | Dug into something ancient that should not be touched… GM secretly rolls a hidden event (ancient relic/sealed rift/previous Lord's secret lab). Location gains an "anomaly" tag, possibly triggering a special plotline later |

### 6.4 Excavation Cost Escalation

| Expansion # | Difficulty | Building Materials | Dark Coins |
|----------|------|---------|-----------|
| 1st | 2 | 1 | 2 |
| 2nd | 3 | 2 | 2 |
| 3rd | 4 | 2 | 2 |
| 4th | 5 | 3 | 3 |
| 5th | 6 | 3 | 3 |
| 6th | 7 | 4 | 3 |
| 7th | 8 | 4 | 4 |
| 8th | 9 | 5 | 4 |
| 9th | 10 | 5 | 4 |
| 10th+ | 11+ | 6 | 5 |

> **Design Intent**: Difficulty rises linearly (+1 each), but the player's Industry (IND)+Engineering also grows. The Goblin Tinkerer (IND+2 archetype bonus, Engineering specialist) still has ~60%+ success at the 3rd–5th expansion (IND5+Engineering4=9d6 vs difficulty 4–6), while other archetypes may need more prep or accept higher risk. This creates differentiation value for "engineering specialist."

---

## VII. Monster Allocation Dice Pool Mechanic

> **Core addition**: Each monster is allocated between economy and combat; an underlying pool supports switching between the two dimensions.

### 7.1 Monster Dual-Dimension Attributes

Each monster has two contribution values:

| Attribute | Meaning | Use |
|------|------|------|
| **Management Value (MV)** | Monster's contribution when assigned to production/economy | Used when rolling Industry (IND) pool |
| **Combat Value (CV)** | Monster's contribution when assigned to defense/combat | Used when rolling Warfare (WAR) pool |

### 7.2 Allocation Rules

- Each monster is assigned to **Economy Group** or **Combat Group** at the start of each turn
- A monster **cannot contribute to both economy and combat** in the same turn
- Allocation is a free action (costs no action points)
- If an invasion occurs mid-turn, Combat Group monsters immediately take defense positions; Economy Group monsters need 1 action to switch to combat (representing emergency recall from mine/workshop)

### 7.3 Economy Dispatch Dice Pool

**When Used**: Monster assigned to Economy Group for production activities.

**Rule Entry**:
> Each Economy Group monster contributes its MV. Sum all Economy Group monsters' MV, divide by 2 (floor, min 1) to get economy pool bonus dice. Lord rolls Industry (IND) + relevant skill + economy bonus dice for the production check.

```
Economy Total Pool = Industry (IND) + Skill + floor(Σ Management Value (MV) / 2)
```

**Example**:
> An Ancient Wyrm assigns 2 Gargoyle Sentinels (MV 2 each) and 1 Cultist (MV 1) to mine production. ΣMV=5, bonus = floor(5/2)=2d6. Wyrm Industry (IND)=4 + Gathering=2 + monster bonus 2 = 8d6. Rolls 8d6 for mine output check.

### 7.4 Combat Defense Dice Pool

**When Used**: Monster assigned to Combat Group for dungeon defense.

**Rule Entry**:
> Each Combat Group monster contributes its CV. Sum all Combat Group monsters' CV, divide by 2 (floor, min 1) to get combat pool bonus dice. Lord rolls Warfare (WAR) + Monster Command/Tactical Deployment + combat bonus dice for defense/combat check.

```
Combat Total Pool = Warfare (WAR) + Monster Command/Tactical Deployment + floor(ΣCV / 2)
```

**Example**:
> An Abyssal Overlord deploys 2 Hellhounds (CV 3 each) and 1 Gargoyle Sentinel (CV 3) to the defense line. ΣCV=9, bonus = floor(9/2)=4d6. Overlord Warfare (WAR)=4 + Monster Command=2 + combat bonus 4 = 10d6 (cap 10d6). Rolls 10d6 for combat command check.

### 7.5 Monster Base MV/CV Values

| Monster | MV (Economy) | CV (Combat) | Note |
|------|-----------|-----------|------|
| Skeleton Soldier | 1 | 1 | Cheap all-rounder, low efficiency |
| Gelatinous Slime | 0 | 2 | Cannot do fine economy work |
| Shadow Wraith | 1 | 2 | Ambush-type, combat-leaning |
| Gargoyle Sentinel | 2 | 3 | Balanced, build + guard |
| Hellhound | 1 | 3 | Combat-leaning, tracking specialist |
| Elemental Construct | 3 | 4 | Top balanced, but costly upkeep |
| Spider Swarm | 1 | 2 | Trap-synergy type |
| Cultist Acolyte | 2 | 1 | Economy-leaning (human intellect advantage) |
| Death Knight | 4 | 5 | Elite balanced |
| Abyss Demon | 0 | 6 | Pure combat type |
| Chimera Beast | 2 | 5 | Combat-leaning |
| Dragonborn Guardian | 3 | 5 | Top guard |
| Master Assassin | 1 | 4 | Special combat |
| Mechanical Colossus | 4 | 6 | Top construct |
| Bone Dragon | 2 | 7 | Legendary monster |
| Abyss Lord (monster) | 3 | 8 | Legendary combat |
| Ancient Golem | 5 | 8 | Legendary construct |

> **Design Intent**: MV/CV differentiation gives monster allocation strategic depth. Economy dungeons (Goblin Tinkerer, Ancient Wyrm) prefer high-MV monsters; combat dungeons (Abyssal Overlord) prefer high-CV monsters. The floor(Σ/2) formula makes marginal returns diminish — 2 CV3 monsters (6 CV → +3 dice) beat 4 CV1 monsters (4 CV → +2 dice), encouraging quality over sheer quantity.

---

## VIII. Random Monster Economy Ability Generation Table

> **Core addition**: On recruitment or acquisition, each monster rolls once for 1 random economy ability. Abilities come in 3 tiers, tied to monster level.

### 8.1 Generation Flow

1. On acquisition, roll **d66** (two d6, one tens one ones) to look up the ability
2. Determine ability strength by monster level:
   - **Common monster** (Lv1–2): ability is **Common tier**
   - **Elite monster** (Lv3–4): ability is **Enhanced tier**
   - **Legendary monster** (Lv5+): ability is **Expert tier**
3. Each monster has only 1 economy ability (cannot stack)
4. Special archetype abilities (e.g., Necromancer Lord's Undead Affinity) may let undead monsters gain an extra ability or reroll

### 8.2 d66 Economy Ability Table

#### Axis 1: Mining & Resources (Row 1)

| d66 | Ability Name | Common Effect | Enhanced Effect | Expert Effect |
|-----|---------|-----------|-----------|-----------|
| 11 | **Vein Sense** | +1 Management Value (MV) when mining | MV+2 and +1 die to mining check | MV+3, +2 dice to mining, 10% chance rare vein |
| 12 | **Material Refining** | −10% Building Materials on construction | −20% | −30%, 50% of scrapped materials recoverable |
| 13 | **Mana Resonance** | When working magic rooms, MV counts as Arcana (ARC)-related | MV=ARC-related and +1 | MV=ARC-related and +2, Mana Crystal output +1/turn |
| 14 | **Double Output** | On production check, a 6 triggers extra output (+1 unit per 6) | 5–6 triggers extra output | 5–6 triggers, +2 units per 6 |
| 15 | **Resource Regeneration** | Auto-produce 1 random basic resource every 2 turns | 1 random basic resource every turn | 2 random resources every turn, chance of rare |
| 16 | **Storage Expansion** | Room resource storage cap +20% | +40% | +60%, resources above cap no longer lost |

#### Axis 2: Construction & Workshop (Row 2)

| d66 | Ability Name | Common Effect | Enhanced Effect | Expert Effect |
|-----|---------|-----------|-----------|-----------|
| 21 | **Quick Builder** | +1 die to build/upgrade room check | +2 dice | +3 dice, build time halved |
| 22 | **Workshop Boost** | Trap workshop/forging output +1/turn | +2/turn | +3/turn, crafted item quality +1 tier |
| 23 | **Maintenance Expert** | Room maintenance cost −1 resource/turn | −2/turn | Fully free, adjacent rooms −1 |
| 24 | **Quality Control** | Built room initial quality +1 (harder to destroy) | +2 | +3, auto-repairs 50% when destroyed |
| 25 | **Structure Optimization** | Room can hold +1 extra monster | +2 monsters | +3 monsters, adjacent rooms +1 capacity each |
| 26 | **Chain Workshop** | All workshop-type rooms on same floor +10% output | +20% | +30%, synergy effect triggers extra |

#### Axis 3: Magic & Research (Row 3)

| d66 | Ability Name | Common Effect | Enhanced Effect | Expert Effect |
|-----|---------|-----------|-----------|-----------|
| 31 | **Arcane Affinity** | When working research chamber, MV treated as Arcana (ARC) | MV+1 and treated as ARC | MV+2 and ARC, Mana Crystal cost −1 |
| 32 | **Ritual Assistant** | +1 modifier die assisting rituals | +2 modifier dice | +3 modifier dice, 50% no negative on ritual fail |
| 33 | **Curse Amplification** | Curse/magic trap effect +1 on that floor | +2 | +3, adds random curse |
| 34 | **Alchemy Catalyst** | +1 die to alchemy checks | +2 dice | +3 dice, alchemy products always fine+ quality |
| 35 | **Mana Collection** | Collect residual mana each turn, +1 Mana Crystal | ×2 output | ×3, can power adjacent magic rooms |
| 36 | **Forbidden Knowledge** | Unlock 1 hidden research project | Unlock 2, research speed +20% | Unlock 3, research speed +50% |

#### Axis 4: Prison & Management (Row 4)

| d66 | Ability Name | Common Effect | Enhanced Effect | Expert Effect |
|-----|---------|-----------|-----------|-----------|
| 41 | **Jailer Instinct** | When in prison, captive escape check −1 die | −2 dice | −3 dice, riot chance halved |
| 42 | **Psychological Manipulation** | +1 die to Dominion (DOM) check when interrogating | +2 dice | +3 dice, captive will drops extra −1 |
| 43 | **Labor Overseer** | Captive labor efficiency +20% | +40% | +60%, captive stamina cost halved |
| 44 | **Order Maintenance** | Monsters in same room don't lose loyalty naturally | Same floor monsters don't | Whole dungeon loyalty drop halved |
| 45 | **Captive Appeasement** | Captive conversion threshold −1 (easier) | −2 | −3, retains all profession skills after conversion |
| 46 | **Intelligence Screening** | Auto-gain 1 intel from captives every 2 turns | 1 intel every turn | 2 intel every turn, always useful |

#### Axis 5: Recon & Defense (Row 5)

| d66 | Ability Name | Common Effect | Enhanced Effect | Expert Effect |
|-----|---------|-----------|-----------|-----------|
| 51 | **Shadow Recon** | Scout outpost warning +1 turn | +2 turns | +2 turns and identify adventurer class & weakness |
| 52 | **Trap Quick-Hand** | Trap reset time halved | Free reset + halved | Free + instant reset, trap retains 50% effect after trigger |
| 53 | **Sentinel Alert** | Room cannot be ambushed | Floor cannot be ambushed | Whole dungeon cannot, ambusher auto-exposed |
| 54 | **Terrain Modification** | Room convertible to "favorable terrain" (defense +1 die) | +2 dice | +3 dice, invader must pass extra check to enter |
| 55 | **Patrol Boost** | Monster can patrol between 2 adjacent rooms (covering both) | Covers 3 rooms | Covers 5 rooms, invader move −1 in patrol range |
| 56 | **Warning Network** | Forms network with other sentry-type monsters on floor, warning +1 turn | +2 turns | +3 turns and GM must reveal invasion scale & main class |

#### Axis 6: Special Powers (Row 6)

| d66 | Ability Name | Common Effect | Enhanced Effect | Expert Effect |
|-----|---------|-----------|-----------|-----------|
| 61 | **Lucky Star** | Once per turn, reroll 1 die of that monster's check | Reroll 2 dice | Reroll 3 dice or whole pool once |
| 62 | **Adaptive Evolution** | Immune to one specified environmental penalty (e.g. river zone) | Immune to two | Immune to all, and doubles environmental bonus |
| 63 | **Synergy Resonance** | Adjacent same-type monsters, both MV/CV +1 | Both +2 | Both +2 and skill bonus shared |
| 64 | **Lesser Avatar** | Every 2 turns split a temp servant MV1/CV1 (lasts 1 turn) | MV2/CV2, lasts 2 turns | MV3/CV3, lasts 3 turns |
| 65 | **Elemental Infusion** | Can be infused once (fire/ice/lightning), MV or CV +1 | After infusion MV and CV both +1 | Double infusion, MV+2 and CV+2 |
| 66 | **Abyssal Blessing** | Reroll d66 twice, monster gains two abilities (take better) | Gains two (both apply) | Gains two (both apply) + one self-chosen ability |

### 8.3 Ability Strength Distribution

| Strength Tier | Monster Level | Applicable Row | Typical Scenario |
|----------|---------|--------|---------|
| **Common** | Lv1–2 monster | Base effect of all 36 | Skeleton Soldier, Slime, Shadow Wraith etc. |
| **Enhanced** | Lv3–4 monster (elite) | Enhanced effect of all 36 | Death Knight, Abyss Demon, Chimera Beast etc. |
| **Expert** | Lv5+ monster (legendary) | Expert effect of all 36 | Bone Dragon, Abyss Lord, Ancient Golem etc. |

### 8.4 Ability & Archetype Synergy Examples

| Archetype | Recommended Abilities | Reason |
|------|-------------|------|
| Necromancer Lord | 11 Vein Sense, 15 Resource Regeneration, 41 Jailer Instinct | Undead laborers need no prison space; many skeletons → quantity advantage × stacked abilities |
| Abyssal Overlord | 42 Psychological Manipulation, 56 Warning Network, 65 Elemental Infusion | Combat dungeon, needs fast captive conversion and combat bonuses |
| Mad Sorcerer | 31 Arcane Affinity, 34 Alchemy Catalyst, 36 Forbidden Knowledge | Magic research specialist, abilities speed research & experiments |
| Ancient Wyrm | 12 Material Refining, 16 Storage Expansion, 61 Lucky Star | Economy build, lowering cost and expanding storage is key |
| Shadow Council | 46 Intelligence Screening, 51 Shadow Recon, 56 Warning Network | Intel build, more intel = more precise counterplay |
| Goblin Tinkerer | 21 Quick Builder, 22 Workshop Boost, 52 Trap Quick-Hand | Build & trap specialist, speed and efficiency above all |

---

## IX. Captive System Core Checks

> **Cross-review simplification**: Keeps the underlying will-opposition, escape check, and labor-efficiency pool formulas. The six-stage process management (interrogation/torture/charm/isolate/indoctrinate → will-zero outcome table) is handled by the Character System.

### 9.1 Will Opposition (WIL Resistance)

**When Used**: When the Lord applies will-affecting means (interrogation/intimidation/charm) to a captive.

**Rule Entry**:
> Lord rolls **Dominion (DOM) pool + Interrogation skill dice**. Captive rolls **Willpower (WIL) pool** (WIL value = dice). If Lord's successes > captive's successes, will drops. The difference determines drop magnitude:

| Net Successes (Lord − Captive) | WIL Change | Extra Effect |
|---------------------|---------|---------|
| ≤0 | No change | Captive resists; Lord may gain one vague intel (GM secret roll) |
| 1 | Willpower (WIL) −1 | Captive begins to waver |
| 2 | Willpower (WIL) −1 | Captive wavers, captive WIL pool −1 die next interrogation |
| 3+ | Willpower (WIL) −2 | Will greatly weakened, Lord also gains one certain intel |

**Example**:
> Shadow Council interrogates a T2 Thief captive (WIL=4). Council Dominion (DOM)=3 + Interrogation=2 = 5d6. Captive Willpower (WIL)=4d6.
> Lord rolls: 6,5,4,3,2 → 2 successes + extra die (4) = 2 successes. Captive rolls: 5,3,2,1 → 1 success. Net = 1 → Willpower (WIL) −1 (drops to 3).

### 9.2 Escape Check

**When Used**: At end of each turn, every captive with WIL ≥ 2 makes an escape check.

**Rule Entry**:
> Captive rolls **Willpower (WIL) pool**. Dungeon rolls **Defense (DEF) pool** (directly uses dungeon DEF value's dice) + prison level extra dice.
> - If captive successes > dungeon successes → escape attempt begins, enters chase phase
> - If captive successes ≤ dungeon successes → escape suppressed

**Chase Phase** (after escape attempt begins):
> Captive rolls profession pool (Profession Level (PL) value = dice; +1 die if rogue/ranger background).
> Dungeon rolls **Warfare (WAR) pool + Deterrence/Monster Command** (+2 dice if Hellhound deployed).
> - If captive successes > chase successes → captive escapes (removed, may expose dungeon intel)
> - If captive successes ≤ chase successes → escape fails, captive WIL−1, STA−1

**Example**:
> T3 Warrior captive (WIL=3, PL=3) attempts escape. Dungeon DEF=4, prison Lv2 (+1 die).
> Captive Willpower (WIL)=3d6 → rolls 6,5,2 → 2 successes + extra die (4) = 2 successes.
> Dungeon Defense (DEF)=4d6+1d6=5d6 → rolls 6,5,3,2,1 → 2 successes + extra die (2) = 2 successes. Tie → escape suppressed.
> If captive successes were 3, escape begins → chase phase: captive PL=3d6, dungeon WAR+Deterrence+Hellhound tracking bonus → resolve.

### 9.3 Labor Efficiency Pool Formula

**When Used**: When assigning captives to labor, calculates their output efficiency.

**Rule Entry**:
> Each captive's base labor pool = **Stamina (STA) pool + skill bonus dice** (by profession and labor type).

| Labor Type | Pool Formula | Output Calculation |
|----------|---------|---------|
| **Excavation/Expansion** | STA pool + PL dice (if Warrior +1 die) | Each success yields 1 Building Material |
| **Trap Crafting** | STA pool + PL dice (if Rogue +1 die) | Each success crafts 1 basic trap component |
| **Magic Research** | STA pool + PL dice (if Mage +1 die) | Each success yields 1 Mana Crystal |
| **Resource Production** | STA pool + PL dice | Each success yields 1 corresponding resource |
| **Combat Cannon-Fodder** | PL pool (power = PL, not pool output) | Each battle STA−1, power = PL |
| **Special Ritual** | PL pool (no STA cost, costs WIL) | Each success empowers ritual effect +1 |

**Example**:
> T2 Mage captive (STA=4, PL=2) assigned to magic research. Pool = STA 4d6 + PL 2d6 = 6d6.
> Rolls 6,5,5,3,2,1 → 3 successes + extra die (4) = 3 successes. Yields 3 Mana Crystals. STA−1 (drops to 3).

### 9.4 Captive Core Value Quick Reference

| Captive Tier | Willpower (WIL) | PL | STA | Value Reference |
|----------|-----|-----|-----|---------|
| T1 Novice | 3 | 1 | 4 | 2 Soul Essence |
| T2 Proficient | 4 | 2 | 4 | 4 Soul Essence |
| T3 Elite | 5 | 3 | 5 | 8 Soul Essence |
| T4 Hero | 5 | 4 | 5 | 15 Soul Essence |
| T5 Legendary | 5 | 5 | 5 | 25 Soul Essence |

> **Note**: The will-zero outcome table, six-stage process (interrogation/torture/charm/isolate/indoctrination), and moral-dilemma narrative are deeply managed by the Character System. This document only provides the underlying dice-pool resolution rules.

---

## X. Dual-Track Skill Tree & Archetype Abilities

> **Cross-review confirmed**: Dual-track — Skill Tree + Archetype Abilities, stacking without conflict.

### 10.1 Dual-Track Architecture

```
┌────────────────────────────────────────────────┐
│                Dungeon Lord Ability System         │
├─────────────────────┬──────────────────────────┤
│   Skill Tree (Universal Growth) │ Archetype Abilities (Exclusive Talents) │
│   · 20 universal skills      │   · 6 archetypes each 1 passive + 1 active    │
│   · shared by all archetypes │   · archetype-exclusive, not cross-obtainable  │
│   · improved via skill points│   · advanced unlocked via dungeon level     │
│   · represents acquired learning │ · represents innate gift/bloodline      │
├─────────────────────┴──────────────────────────┤
│ Stacking rule: skill bonus dice + archetype passive bonus dice both apply in a check │
│ Example: Necromancer Lord Dominion (DOM)=3 + Interrogation skill=2 + Cruel Interrogator=1 │
│        = 6d6 interrogation pool (attr 3 + skill 2 + archetype 1)          │
└────────────────────────────────────────────────┘
```

### 10.2 Conflict Handling

- If skill and archetype ability give **the same type of bonus** (e.g. both "Interrogation +1 die"), they stack (different sources)
- If skill and archetype ability give **the same-named ability** (e.g. "Cruel Interrogator" appears in both archetype-exclusive and universal auxiliary), the archetype version takes priority and is stronger
- Archetype advanced abilities (Lv3/6/9) provide **new independent actions** or **rule-changing effects**, not conflicting with the skill tree

---

## XI. Mathematical Validation

### 11.1 Core Check Sweet-Spot Validation

**Setup**: Medium difficulty (needs 2 successes), player main attribute 3–4, relevant skill 2–3, pool 5–7d6.

| Scenario | Pool | P(≥2 successes) | Feel Evaluation |
|------|------|-----------|---------|
| New Lord (attr 2 + skill 1) | 3d6 | 11.1% | High challenge, needs env bonus or resource spend |
| Qualified Lord (attr 3 + skill 2) | 5d6 | 32.2% | Challenging, reasonable Standard difficulty experience |
| Specialist Lord (attr 4 + skill 3) | 7d6 | 54.4% | Smooth feel, over 50% success |
| Maxed Specialist (attr 5 + skill 5) | 10d6 | ~80% | Legendary crushes Standard, but Hard (3) still challenging |

**Conclusion**: The 3–5d6 sweet spot holds. Under 12 initial points, player main attribute is 3–4 (4–5 after archetype bonus), with skill 2–3, Standard difficulty success sits in 32–54% — matching the "challenging but achievable" design goal.

### 11.2 Territory Expansion Difficulty Curve

Industry (IND) + Engineering vs escalating difficulty:

| Expansion # | Difficulty | Industry (IND)4+Engineering3 (7d6) P(≥diff) | Industry (IND)5+Engineering5 (10d6) P(≥diff) |
|----------|------|------------------------|--------------------------|
| 1st | 2 | 78.9% | 96.1% |
| 3rd | 4 | 28.3% | 70.8% |
| 5th | 6 | 5.4% | 32.2% |
| 8th | 9 | <1% | 6.5% |
| 10th | 11 | — | <1% |

**Conclusion**: Expansion has a natural slowdown. The Goblin Tinkerer (IND+2 archetype bonus) retains reasonable success at the 4th–5th expansion, while other archetypes need env bonus, archetype ability, or higher risk after the 3rd–4th. This creates a strategic choice of "expansion depth" — keep digging or consolidate the current dungeon.

### 11.3 Monster Allocation Efficiency Curve

| Monster Group | Σ Management Value (MV)/CV | Bonus Dice | Efficiency (bonus/monster count) |
|--------|--------|------|------------------|
| 4 Skeleton Soldiers (CV1×4) | 4 | 2 | 0.50 |
| 2 Hellhounds (CV3×2) | 6 | 3 | 1.50 |
| 1 Elemental Construct (CV4×1) | 4 | 2 | 2.00 |
| 2 Gargoyles + 1 Cultist (MV | 5 | 2 | 0.67 |
| 3 Dragonborn Guardians (MV 3×3) | 9 | 4 | 1.33 |

**Conclusion**: Under floor(Σ/2), high-quality monsters (high individual MV/CV) are more efficient than many low-quality ones. 1 Elemental Construct (CV4) at +2 dice equals 4 Skeleton Soldiers combined. This drives players toward elites and legendaries rather than infinitely stacking low-tier monsters.

### 11.4 Captive Will Opposition Balance

Dominion (DOM) + Interrogation vs WIL opposition:

| Lord Pool | Captive WIL | Lord Win Rate | Avg WIL Drop/turn |
|----------|---------|---------|---------------|
| Dominion (DOM)3+Interrogation1=4d6 vs | Willpower (WIL)3=3d6 | 55% | 0.6 |
| Dominion (DOM)4+Interrogation2=6d6 vs | Willpower (WIL)4=4d6 | 60% | 0.8 |
| Dominion (DOM)4+Interrogation3=7d6 vs | Willpower (WIL)5=5d6 | 57% | 0.7 |
| Dominion (DOM)5+Interrogation4=9d6 vs | Willpower (WIL)5=5d6 | 72% | 1.1 |

**Conclusion**: Will opposition is designed for slow progress — even an interrogation specialist needs 3–5 sessions on average to bring a high-will captive (WIL5) to the breakdown edge. This fits the "captives are a long-term investment" philosophy and gives the Character System's six-stage process ample narrative room.

---

## XII. Glossary

| Term | Abbrev | Definition |
|------|------|------|
| **Dice Pool** | Pool | All d6 rolled in one check |
| **Success** | Success | Die face 5–6 result |
| **Explosion** | Explosion | Mechanic where a 6 grants +1 extra die |
| **Net Successes** | Net Successes | Successes − Difficulty (or opposed successes) |
| **Margin of Success** | MoS | Same as net successes, degree beyond target |
| **Margin of Failure** | MoF | Deficit below required successes |
| **Difficulty Class** | DC | Minimum successes required for an action |
| **Target Number** | TN | Same as DC |
| **Advantage** | Advantage | Favorable state, adds dice before roll |
| **Disadvantage** | Disadvantage | Unfavorable state, removes highest dice before roll |
| **Attribute Dice** | Attribute Dice | Dice from attribute value (1d6–5d6) |
| **Skill Dice** | Skill Dice | Extra dice from skill level |
| **Modifier Dice** | Modifier Dice | Temporary dice from gear/terrain/aid |
| **Management Value** | Management Value (MV) | Monster's contribution when economy-deployed |
| **Combat Value** | CV | Monster's contribution when combat-deployed |
| **Willpower** | Willpower (WIL) | Captive's mental resistance to interrogation/indoctrination |
| **Stamina** | STA | Captive's physical condition, sets labor pool |
| **Profession Level** | PL | Captive's profession skill level |

| Dungeon Attribute | Abbrev | Range |
|----------|------|------|
| Depth | Depth (DEP) | 1–15 |
| Infamy | Infamy (INF) | 1–15 |
| Defense | Defense (DEF) | 1–15 |
| Wealth | Wealth (WLH) | 1–15 |
| Magic | Magic (MAG) | 1–15 |

---

## Appendix A: Quick Check Reference Card

### Standard Check
```
Pool = Attribute + Skill + Modifier
Roll all d6 → 5-6 = 1 success, 6 = +1 die
Successes ≥ Difficulty → Success
```

### Opposed Check
```
Both sides roll pools
Net Success = Active side successes − Opposed side successes
Net Success ≥ 0 → Active side wins
```

### Margin of Success
```
0 = Failure
1 = Partial Success
2 = Full Success
3 = Critical Success
4+ = Legendary Success
```

### Difficulty Reference
```
Easy=1 / Standard=2 / Hard=3 / Extreme=4 / Epic=5
```

---

## Appendix B: Design Notes

### v2.0 Revision List

| # | Revision Item | Status |
|---|--------|------|
| 1 | Initial attribute points 15→12 | ✅ Revised, math validated |
| 2 | Captive system simplified (kept WIL opposition/escape/labor efficiency) | ✅ Done, six-stage process handed to Character System |
| 3 | Unified attribute naming (DRE→WAR) | ✅ Full-text replacement done |
| 4 | Territory expansion dice pool mechanic (IND+Engineering vs escalating difficulty + result table + risk table) | ✅ Added |
| 5 | Monster allocation dice pool mechanic (MV/CV dual-dim + floor(Σ/2) formula) | ✅ Added |
| 6 | Random monster economy ability d66 table (36 items × 3 tiers) | ✅ Added |
| 7 | Skill tree & archetype ability dual-track confirmed | ✅ Confirmed and documented |
| 8 | Dungeon derived attribute mapping (DEP/Infamy (INF)/Defense (DEF)/Wealth (WLH)/Magic (MAG)) | ✅ Mapping established |

### Interface with Character System

- **Attribute naming**: Cunning (CUN)/Dominion (DOM)/Arcana (ARC)/Industry (IND)/Warfare (WAR) — five attributes fully consistent with Character System
- **Archetype abilities**: The six archetype abilities of the Character System stack on the skill tree
- **Captive process**: Underlying dice-pool resolution from this document, six-stage management from Character System
- **Dungeon attributes**: DEP/Infamy (INF)/Defense (DEF)/Wealth (WLH)/Magic (MAG) mapping established, pool interaction rules clarified
- **Monster attributes**: MV/CV values aligned with Character System's monster catalog

### Pending Alignment

- Specific attack/defense dice-pool opposition in combat system (align with combat-designer)
- Dice-pool usage in invasion wave generation algorithm (align with combat-designer)
- Dice-pool correction details for magic item effects (can extend later)

---

*This document is the revised draft of the "Core Resolution Mechanics" within the Abyss Lord TRPG rules system. All values and mechanics are cross-aligned with the Character System (character-dungeon-system.md) and the world setting (worldbuilding-gm-guide.md).*
