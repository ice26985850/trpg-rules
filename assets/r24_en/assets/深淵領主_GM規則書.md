# Abyss Lord TRPG — Game Master Rulebook

> **Version**: v2.3 (Forging + Enchanting Expansion — Forge/11 Rooms/Equipment System/Mineral Materials/Enchanting System 7 Schools/Enchanting Spells 6 Spells/Creature Enchanting/Enchanting Trade)
> **Type**: Mid-weight strategy TRPG / Dungeon Management
> **Core Gameplay**: Players take the role of a Dungeon Lord, managing and expanding their dungeon, fighting off invading adventurers, and capturing and enslaving them
> **Players**: 1 GM + 1–4 players
> **Dice System**: d6 Dice Pool (5–6 = success, 6 may explode)
> **Attribute Ranges**: Lord Attributes 1–5 / Dungeon Attributes 1–15

---



# Chapter One: Combat & Conflict

## 1.1 Combat Framework

### Turn Structure (six-phase)

```
Phase 0: Preparation Phase — Cunning (CUN) recon check, emergency conscription, pre-battle ritual
Phase 1: Initiative Phase — invader 1d6+Tier mod vs defender 1d6+Lord Cunning (CUN)
Phase 2: Action Phase — both sides take unit actions in turn
Phase 3: Environment Phase — trap trigger, ongoing effect settlement, room effects
Phase 4: Morale Phase — check rout/shaken, monster loyalty check
Phase 5: Advance Phase — invader decides whether to advance to next layer, tally battle losses
```

### Initiative Rules

- Invader: 1d6 + [Tier] (T1=+0, T2=+1, T3=+2, T4=+3, T5=+4)
- Defender: 1d6 + [Lord Cunning (CUN) value]
- Initiative side chooses to go first or last

### Action System

| Action | Per Round | Description |
|------|---------|------|
| Move | 1 | Move to adjacent room |
| Standard Action | 1 | Attack, cast, use ability |
| Bonus Action | 1 | Quick ability, switch weapon, command |
| Reaction | 1 | Opportunity attack, guard, trigger ability |

---

## 1.2 Defense Layer System

Adventurers must break through dungeon defenses layer by layer. Four escalating layers:

| Layer | Name | Defense Value (DV) | Trap Slots | Monster Slots | Special Slots |
|------|------|-----------|--------|--------|--------|
| Outer | Outer Defense | Defense (DEF)÷2 | 2 | 2 | Scout Outpost |
| Middle | Core Combat Zone | Defense (DEF) | 3 | 3 | Monster Lair/Training Ground |
| Inner | Lord Domain | Defense (DEF)×1.5 | 1 | 4 | Altar/Research Chamber |
| Core | Throne Chamber | Defense (DEF)×2 | 0 | Unlimited | Throne Hall |

### Breach Mechanism

Adventurers must accumulate damage ≥ current layer DV to advance to next layer. After breaching, the layer suffers **permanent damage**—loses traps and part of monster HP.

---

## 1.3 Trap System

### Six Trap Types

| Trap | Damage | Effect | Stealth DC | Build Time | After Trigger |
|------|------|------|--------|---------|--------|
| Rockfall Trap | 2d6 | Area AOE | 2 | 1 turn | Needs reset (1 turn) |
| Poison Gas Room | 1d6/turn | 3-turn poison | 3 | 2 turns | Depleted, rebuild |
| Spike Pit | 3d6 | Single + 1 turn unable to act | 3 | 1 turn | Auto-reset |
| Magic Rune | 2d6 | Spell counter (dispel buff) | 4 | 2 turns | Depleted, rebuild |
| Curse Trap | No direct | Willpower (WIL)-1, check -1 die | 2 | 1 turn | Permanent (needs purge) |
| Summon Trap | 0 | Summon CP2 monster from lair | 3 | 1 turn | Auto-reset |

---

## 1.4 Damage System

### Damage Formula

> Net Successes = Attacker Dice Pool - Defender Dice Pool

> Damage = Net Successes + Weapon/Spell Bonus - Defense Reduction

### Status Effects

| Status | Effect | Remove Condition |
|------|------|---------|
| Poison | 1 damage/turn | After 3 turns or antidote |
| Burn | 1 damage/turn, attack die -1 | Use 1 action to extinguish |
| Paralyze | Cannot move or act | After 2 turns or external |
| Curse | All checks -1 die | Purify (ARC check) |
| Fear | Active attack needs WIL check | Leave fear source or 3 turns |
| Stun | Next turn only move or bonus action | After 1 turn |

---

## 1.5 Adventurer System

### Adventurer Tier & Dice Pool

| Tier | Dice Pool Range | Squad Size | Drop Tier | INF Requirement |
|------|---------|---------|---------|---------|
| T1 Novice | 2–3 dice | 2–3 | Basic | 1–3 |
| T2 Skilled | 4–5 dice | 3–4 | Advanced | 4–6 |
| T3 Elite | 6–7 dice | 4–5 | Rare | 7–9 |
| T4 Hero | 8–9 dice | 5–6 | Epic | 10–12 |
| T5 Legendary | 10+ dice | 6–8 | Legendary | 13–15 |

### Five Classes

| Class | Core Ability | Trap Counter |
|------|---------|-----------|
| **Warrior** | High HP high defense, taunt draws fire | Physical trap resist +2 |
| **Mage** | Area magic, dispel magic traps | Magic rune resist +2 |
| **Rogue** | Scout disarm traps, high crit | Stealth DC -2 |
| **Cleric** | Heal dispel, counters undead/demon | Curse resist +2 |
| **Ranger** | Ranged attack, tracking | Summon trap focus fire |

### Boss Adventurer (three-phase stage mechanic)

| Phase | Trigger | Boss Ability |
|------|------|---------|
| **Phase 1** | Initial | Normal dice pool |
| **Phase 2** | HP to 50% | Dice pool +2, unlock domain skill |
| **Phase 3** | HP to 25% | Dice pool +4, ultimate skill, team bonus |

---

## 1.6 Invasion Generation

### Invasion Trigger Check

> Each turn end roll: INF + 1d6 ≥ 8 triggers invasion

Infamy (INF)≥7 → invasion every turn (target of all).

### Invasion Construction (GM five-step)

1. **Determine Trigger**: roll invasion check
2. **Determine Source**: roll 1d6 1-2=Adventurers' Guild, 3-4=Order of Light, 5=Royal Investigation Corps, 6=Freelance Hunters
3. **Determine Scale & Tier**: cross-reference INF table
4. **Generate Class Composition**: roll d6 for party mix
5. **Add Narrative Hook**: roll d6 for adventurer motive

### Adventurer AI Behavior Table (2d6)

| 2d6 | Tactical Behavior |
|-----|---------|
| 2 | Reckless charge—whole team rushes next layer at any cost |
| 3–4 | Scattered search—split to scout multiple rooms |
| 5–6 | Cautious advance—rogue scouts traps first |
| 7 | Steady—cleric center, warriors front/back guard |
| 8–9 | Fire suppression—mage ranged magic weakens defense |
| 10–11 | Tactical retreat—fall back to last safe layer on disadvantage |
| 12 | All-in—whole team releases ultimate, surprise core |

---

## 1.7 Special Tactics Rules

### Ambush/Surprise

Defender may ambush in own dungeon (CUN+Stealth vs adventurer scout). Success → first-turn surprise—all enemy defense dice -2, own attack dice +2.

### Dungeon Lord Fights in Person

Lord may join any defense-layer battle. Lord HP = Dominion (DOM)+WAR (min 5). Lord may roll WAR or ARC dice pool to attack. If Lord HP 0, all dungeon checks Disadvantage -3 until Lord recovers.

### Captive Cannon Fodder

May drive captives to front as fodder. Captive combat = PL. Each battle captive STA-1. If captive downed, 1/3 chance permanent death. Captive escape risk doubled.

### Active Retreat/Scorched Earth

Defender may abandon a layer. On retreat all monsters withdraw to next layer, but adventurers advance to latter half of that layer. May spend 1 action on scorched earth—destroy all traps in layer (deal max 1 trap damage to pursuing adventurers).

---

## 1.8 Magic System

Magic is the Lord's second combat ability system besides combat arts. Combat arts are "martial path" (cost bonus action or ◇, physical/mixed skills), magic is "spell path" (cost ◇ + action, pure ARC casting). Freely combined.

### 1.8.1 Magic Learning

Lord doesn't natively know all spells. Learning needs time, resources, research.

**Three ways to learn new spell**:

| Path | Condition | Cost | Time |
|------|------|------|:---:|
| **Self-Research** | Research Chamber Lv1+, ARC check vs spell level difficulty | ◇×(spell level×2) | 1–3 turns |
| **Learn from Captive** | Captive mage (PL≥2), DOM interrogation success reveals known spell | No extra resource | Captive loses that spell memory |
| **Exchange from Ally** | Relation with NPC dungeon ≥5, other lord knows spell | ◆×(spell level×5) or equivalent | Learn immediately |

**Self-Research Check**:

| Spell ◇ cost | Research Difficulty | Research Time |
|:---:|:---:|:---:|
| 1◇ spell | Standard (2 successes) | 1 turn |
| 2–3◇ spell | Hard (3 successes) | 2 turns |
| 4–5◇ spell | Extreme (4 successes) | 3 turns |
| 6◇ spell | Epic (5 successes) | 3 turns + special condition |

**Spell Slot Cap** (max learnable spell count):
| Condition | Spell Slots |
|------|:---:|
| Arcana (ARC)≥2 | 2 |
| ARC each +1 | +1 (ARC=5 → total 5) |
| Skill "Ritual Master" Lv1/2/3/4 | each +1 |
| Skill "Cursecraft" Lv3+ | +1 |
| Research Chamber Lv2/3 | each +1 |
| Abyss Lord assist | +1 legendary spell slot |

**Max spell slots**: ~10–12 spells (Lord may selectively learn, not forced to fill).

> Lord may choose up to "Arcana (ARC)+2" spells as "prepared spells" for the invasion from learned spells before battle. Unprepared can't be cast. Prepared in Preparation Phase free.

### 1.8.2 Spell Casting

> Casting Dice Pool = ARC Dice Pool + Arcane Knowledge skill dice + Research Chamber bonus

Casting costs 1 standard action + ◇ Mana Crystals (varies per spell). Cast range: any same-layer room.

### 1.8.3 Spell List

#### Destruction School (attack spells)

| Spell | ◇ | Level | Effect |
|------|:---:|:---:|------|
| **Shadow Arrow** | 1 | Basic | Arcana (ARC) vs Defense, single target damage = net successes, pierces 1 physical armor |
| **Corrosion Touch** | 2 | Arcana (ARC)≥3 | Melee spell. Damage = ARC level×2, +1 acid damage/turn ×3 turns |
| **Shadow Storm** | 3 | Arcana (ARC)≥4 | Same-room AOE. All enemies take ARC dice÷2 damage (each defends) |
| **Annihilation Ray** | 4 | Arcana (ARC)≥5 | Choose a straight line piercing 2 rooms. First enemy each room takes ARC dice damage |
| **Soul Collapse** | 5 | Arcana (ARC)=5+Legendary | Single target. Ignore defense, damage = ARC dice×1.5. Extra 1● |
| **Abyss Flood** | 6 | Ultimate | Whole-layer AOE. All enemies take ARC dice damage. Extra 2●. 1/battle |
| **Chaos Burst** | 3 | Arcana (ARC)≥3 | Single. ARC dice damage, random add burn/paralyze/poison one |
| **Void Arrow** | 2 | Arcana (ARC)≥3 | Ranged. Pierce walls/obstacles to hit out-of-sight target (need rough location) |

#### Curse School (weaken/control spells)

| Spell | ◇ | Level | Effect |
|------|:---:|:---:|------|
| **Weak Curse** | 1 | Basic | Single. Target attack die -2, 2 turns |
| **Dark Chain** | 2 | Arcana (ARC)≥3 | Single. Arcana (ARC) vs target defense, success = immobilize 2 turns + 1 dark erosion/turn |
| **Words of Fear** | 1 | Basic | Single in sight. Dominion (DOM) vs WIL, success = fear 2 turns (can't approach Lord) |
| **Mana Seal** | 3 | Arcana (ARC)≥4 | Single. Arcana (ARC) vs ARC opposed, success = target casting dice disabled 1 turn (silence) |
| **Fate Curse** | 4 | Arcana (ARC)≥5 | Single. Target next 3 checks take Disadvantage (roll twice take worse) |
| **Group Weakness** | 4 | Arcana (ARC)≥4+Legendary | All enemies same-room attack die -1, 2 turns |
| **Memory Erosion** | 3 | Arcana (ARC)≥4 | Single. Arcana (ARC) vs WIL, success = target forgets 1 skill/spell (GM decides), whole battle |
| **Blood Curse** | 2+●1 | Arcana (ARC)≥3 | Single. 1 dark erosion/turn ×3 turns. Each damage recovers Lord 1 HP |
| **Mad Whisper** | 2 | Arcana (ARC)≥4 | All enemies same-room need WIL check, fail = attack random target (may include ally) 1 turn |

#### Defense School (shield/protect spells)

| Spell | ◇ | Level | Effect |
|------|:---:|:---:|------|
| **Dark Shield** | 1 | Basic | Self/adjacent monster. Defense dice +2, until hit once or 3 turns |
| **Mana Barrier** | 2 | Arcana (ARC)≥3 | All friendly same-room gain magic defense dice (share ARC dice), 2 turns |
| **Anti-Magic Field** | 3 | Arcana (ARC)≥4 | Self. ARC dice opposed all casting, success = spell absorbed (convert ◇×1) |
| **Undying Pact** | 4 | Arcana (ARC)≥5 | Self. On HP 0 auto-trigger: instantly recover 2d6 HP, 1/battle |
| **Bone Armor** | 2 | Arcana (ARC)≥2 | Self/monster. Physical damage reduction = Arcana (ARC)/2 (floor), 3 turns |
| **Group Shield** | 3 | Arcana (ARC)≥4 | All monsters same-layer defense die +1, 2 turns |
| **Magic Reflect** | 4 | Arcana (ARC)≥5 | Reaction spell. Triggered when hit by single-target spell, ARC opposed, success = spell reflected to caster |

#### Summon/Undead School

| Spell | ◇ | Level | Effect |
|------|:---:|:---:|------|
| **Skeleton Revival** | 2+●1 | Basic | Summon CP1 skeleton from fallen adventurer corpse. Each extra 1◇ → Combat (CV)+1 (cap CP3). Until battle end |
| **Shadow Creature Summon** | 3 | Arcana (ARC)≥3 | Summon CP2 shadow beast (independent), 3 turns. Each extra 1◇ → +1 Combat (CV) |
| **Undead Legion** | 5+●3 | Arcana (ARC)≥4+Undead exclusive | Summon CP1 skeleton × ARC value. No corpse needed—from Abyss Rift directly. Dissipates after battle |
| **Demon Gate** | 5+●2 | Arcana (ARC)≥5+Demon exclusive | Summon CP3 demon servant × DOM value. 5 turns. 1/battle |
| **Soul Puppet** | 3+●2 | Arcana (ARC)≥4 | Briefly convert captive to battle puppet (CP=PL+2). 3 turns, after captive WIL permanent -1 |
| **Abyss Hound** | 2 | Arcana (ARC)≥2 | Summon CP1 hellhound ×2, 3 turns. Tracking scent auto-locks fleeing/stealthed enemy position |
| **Elemental Servant** | 3 | Arcana (ARC)≥3 | Summon CP2 small element (fire/ice/lightning/stone choose one, matching element damage), 4 turns |
| **Bone Dragon Projection** | 6+●5 | Arcana (ARC)=5+Undead exclusive+Legendary | Summon bone dragon phantom (Combat (CV)6), only 2 turns but ignores defense reduction. 1/campaign |

#### Utility School (non-combat spells)

| Spell | ◇ | Level | Effect |
|------|:---:|:---:|------|
| **Darkvision** | 1 | Basic | Target gains darkvision, 1 expedition day / whole dungeon battle |
| **Abyss Whisper** | 1 | Basic | Send 25-char mental message to 1 known dungeon (needs Embassy Lv1) |
| **Item Appraisal** | 1 | Basic | Appraise 1 magic item, learn function and hidden properties |
| **Portal** | 3 | Arcana (ARC)≥4 | Spend 1 action, teleport self from throne hall to any defense layer (combat turn) or from dungeon to any embassy location in Abyss (non-combat) |
| **Illusion** | 2 | Arcana (ARC)≥3 | Create 3-turn realistic illusion (fake monster/fake trap/fake terrain). CUN opposed adventurer scout |
| **Soul Trace** | 3 | Arcana (ARC)≥4 | Touch captive, extract 1 concrete intel from captive memory (GM must answer) |
| **Shadow Cloak** | 2 | Arcana (ARC)≥2 | Self invisible 2 turns. Removed after attack or cast. CUN+2 dice avoiding encounter on expedition |
| **Abyss Repair** | 2 | Arcana (ARC)≥2 | Repair 1 trap to trigger-ready, or repair 1 room's damaged state |
| **Tongues** | 1 | Basic | 1 expedition day, read/speak all surface languages. For infiltration/recon |
| **Void Storage** | 2 | Arcana (ARC)≥3 | Store 1 item (max volume = 1 building-material unit) in void, permanent, retrievable anytime |

#### Transformation/Enhancement School

| Spell | ◇ | Level | Effect |
|------|:---:|:---:|------|
| **Shadow Form** | 2 | Arcana (ARC)≥3 | Become semi-solid shadow, physical damage -50%, pass narrow gaps, 2 turns |
| **Enlarge** | 3 | Arcana (ARC)≥4 | Self/monster. Size doubled, CP+2, HP+5. But defense die -1 (bigger target). 3 turns |
| **Stone Skin** | 2 | Arcana (ARC)≥3 | Self/monster. Physical defense +3 dice. Move -1 room (heavy). 3 turns |
| **Abyss Fusion** | 4+●2 | Arcana (ARC)≥4 | Lord and 1 monster temporarily fuse → share HP pool, dice pool take higher of two, 2 turns. After Lord takes 1d3 damage |

### 1.8.4 Archetype Spell Affinity

| Archetype | Affinity School | Bonus | Banned School |
|------|---------|------|---------|
| Necromancer Lord | Summon/Undead, Curse | Summon spell CP+1 | Defense school effect halved |
| Abyssal Overlord | Destruction, Defense | Destruction damage +1 | Summon/Undead unavailable |
| Mad Sorcerer | All schools (incl transform) | Cast check +1 die, but 1/12 chance spell produces random extra effect | None |
| Ancient Wyrm | Destruction (dragon-breath related), Utility | Destruction may choose fire/ice/acid/lightning one of four elements | Summon/Undead unavailable |
| Shadow Council | Curse, Utility (illusion/whisper), Transform | Curse duration +1 turn | Destruction damage -1 |
| Goblin Tinkerer | Utility (appraisal/portal/repair) | Utility ◇ cost -1 (min 1) | Destruction/Summon/Undead/Transform unavailable (use arts instead) |

### 1.8.5 Enchanting Spells (seventh school)

Enchanting spells permanently infuse Abyss mana into equipment or creatures—unlike combat spells, enchant effects are **permanent or long-lasting**, cast in Management Phase not combat turn.

| Spell | ◇ | Level | Effect |
|------|:---:|:---:|------|
| **Basic Enchant** | 2 | Arcana (ARC)≥2 | Apply 1 basic enchant (Keen/Sturdy/Lightweight) to 1 equipment. Needs Forge Lv1. Permanent |
| **Element Imbue** | 4+●1 | Arcana (ARC)≥3 | Apply 1 element enchant (flame/frost/lightning/dark erosion/holy light resist) to 1 equipment. Needs Arcane Workshop synergy. Permanent |
| **Creature Enhance** | 3 | Arcana (ARC)≥3 | Apply 1 creature enchant (magic skin/shadow affinity/loyalty mark) to 1 monster. No slot. Permanent |
| **Advanced Enchant** | 5+●2 | Arcana (ARC)≥4 | Apply 1 enhancement enchant (vampiric/indestructible/regeneration) to 1 equipment. Needs Forge Lv2+. Permanent |
| **Group Element Infusion** | 8+●3 | Arcana (ARC)≥5 | Apply element-bloodline enchant to up to 3 same-layer monsters at once. Needs Forge Lv3 + Research Chamber Lv3. Permanent |
| **Legendary Enchant** | 10+●5 | Arcana (ARC)=5+Legendary | Apply 2 enchants (own choice combo) to 1 Lord Armament at once. Needs Arcane Workshop + Altar Lv3. 1/campaign |

**Enchanting Spell Special Rules**:
- Enchanting spell cast time = 1 full management turn (not combat turn)
- Cannot use enchanting spells in battle—battle has dedicated enhancement spells (see Transformation/Enhancement)
- Enchant scroll may be bought at Abyss black market (price = ◇ cost ×3 Dark Coins)
- Mad Sorcerer's enchant check has 1/12 chance of "unexpected enchant"—random extra hidden effect GM secretly rolls (blessing or curse)

---

## 1.9 Expanded Combat Arts & Magic Quick Reference

### Complete Combat Art Overview

| Track A Archetype Exclusive | Track B Universal Schools | Total |
|------------|------------|:---:|
| 6 archetypes × 5 arts × Lv0-4 = 120 levels | 4 schools × 6 arts = 24 universal arts | 144 combat art options |

### Complete Magic Overview

| School | Spell Count | Typical ◇ Cost |
|------|:---:|:---:|
| Destruction | 8 | 1–6◇ |
| Curse | 9 | 1–4◇ |
| Defense | 7 | 1–4◇ |
| Summon/Undead | 8 | 2–6◇ + ● |
| Utility | 10 | 1–3◇ |
| Transform/Enhance | 4 | 2–4◇ |
| Enchant | 6 | 2–10◇ + ● |
| **Total** | **52** | |

> 144 combat arts + 52 magic (incl enchant) = Lord has 196 tactical choices in battle, enchant system adds extra forge equipment customization.


## 1.10 Ritual System

Rituals are grander, longer magic acts than spells. Spells cast in combat turn (seconds), rituals in Management Phase (hours to turns).

### Ritual Types

| Ritual | Requirement | Duration | Cost | Effect |
|------|------|:---:|------|------|
| **Sacrifice Ritual** | Altar Lv1 | 1 turn | ●×3 + 1 captive (WIL 0) | ARC check, each success = dungeon MAG temp +1 (3 turns) |
| **Enhance Ritual** | Altar Lv1 | 1 turn | ◇×5 | Choose 1 monster, its CP or MV permanent +1 (cap 3 times each) |
| **Curse Ritual** | Altar Lv2 | 2 turns | ◇×8+●×5 | Curse all next-wave adventurers—all checks -1 die (whole invasion) |
| **Grand Summon Ritual** | Altar Lv2 | 3 turns | ◇×10+●×8 | ARC check, each success summons 1 random elite monster (LOY=3). Kept after battle |
| **Dungeon Blessing** | Altar Lv3 | 3 turns | ◇×15+●×10 | All dungeon checks +1 die, monster LOY+1, captive escape -2 dice. 5 turns |
| **Ultimate Ritual** | Altar Lv3 | 5 turns | ◇×25+●×20 | See archetype exclusive ultimate ritual table (below). 1/campaign |

### Ritual Check

Ritual uses `Arcana (ARC) + Ritual Master skill` dice pool. Some rituals allow multiple assistants (each +1 die, cap +3 dice).

Ritual's "net successes" determine effect strength not success/failure—ritual doesn't fail (resources spent), but low successes = reduced effect.

| Net Successes | Ritual Effect |
|:---:|------|
| 0 | Minimum—only 50% efficacy |
| 1–2 | Standard—per table |
| 3+ | Enhanced—effect ×1.5 or extra benefit |

### Archetype Exclusive Ultimate Rituals

| Archetype | Ultimate Ritual | Effect |
|------|---------|------|
| Necromancer Lord | **Undying Legion** | Summon CP1 skeleton × ARC value (permanent, free upkeep) |
| Abyssal Overlord | **Abyss Rift** | Dungeon gains permanent demon gate—may summon 1 extra demon servant per battle |
| Mad Sorcerer | **Reality Warp** | Self ARC permanent +1 (may break cap to 6); but gain 1 permanent random negative mutation |
| Ancient Wyrm | **Dragon Lair Awakening** | All treasury Dark Coins doubled; treasury interest permanent +0.5× |
| Shadow Council | **Shadow Network** | Permanently know all adjacent dungeon intel; assassination edict usable on any target |
| Goblin Tinkerer | **Doomsday Device** | Spend ■×20+◇×10, build one-time doomsday device—destroy entire invasion wave (after use device fails, needs rebuild) |

> Ultimate Ritual is campaign-level investment—suggest at Lv12+, facing the Light Crusade.



---

# Chapter Two: World & Narrative

## 2.1 Worldbuilding

### Core Inversion

In this world, **dungeons are not monster nests, but the Dungeon Lord's kingdom**; **adventurers are not heroes, but invaders and plunderers**. This rulebook redefines classic fantasy from the dungeon's perspective.

### Creation Myth

World born from conflict of two primordial gods—**Aoth** (Light God) and **Nexis** (Abyss Mother). Aoth created surface Realms of Light, Nexis banished to deep underground. Nexis's blood seeped into rock, becoming first mana source; her bones became underground mountains; her thought-fragments became first Abyssal consciousness.

First dungeon was Nexis's tomb, also portal to Abyss. After her banishment, world's rift grew, more lords rose from Abyss.

### World Geography: Two-Layer Structure

**Surface World**:
- **Kingdom of Dawn**: strongest surface kingdom, Order of Light HQ
- **Silver Federation**: commercial federation, Adventurers' Guild patron
- **The Holy See**: theocratic nation, fanatical crusade organization

**Underground World**:
- **Sea of Shadows**: labyrinthine tunnel maze, Shadow Council and Necromancer Lord traditional territory
- **Magma Plains**: Abyssal Overlord's scorching kingdom
- **Gloom Forest**: eerie subterranean ecology, Mad Sorcerer's lab
- **Scrap Canyon**: ancient dwarven ruins, Goblin Tinkerer paradise
- **Abyssal Core**: deepest primal mana sea, legend says Nexis's sleep place

### Historical Timeline

| Era | Event |
|------|------|
| Genesis Era | Aoth-Nexis war, Nexis banished |
| Rift Era 500 years before | Modiras the Archmage invented "Conversion Method"—convert defeated adventurers to Abyss servants |
| Rift Era 200 years before | Edwin—Radiant Paladin Order commander—fell to Abyss Lord, shocked Light world |
| Rift Era 50 years before | Lord War—large-scale civil war between dungeons |
| **Rift Era Year 700 (now)** | Era players inhabit—Light forces grow, adventurer invasions more frequent |

---

## 2.2 Four Adventurer Factions

| Faction | Nature | Tactical Style | Treatment of Captives |
|------|------|---------|---------|
| **Order of Light** | Religious fanatic, counters undead/demon | Holy Light purge, dispel curse | Never surrender when captured (WIL locked 4) |
| **Adventurers' Guild** | Orthodox profit-seekers, honor-valued | Standard squad tactics | Ransom redeemable (ransom = Tier×10 Dark Coins) |
| **Royal Investigation Corps** | State force, well-equipped | Military suppression | State organizes rescue |
| **Freelance Hunters** | Grassroots diverse, varied means | Guerilla harassment | Varied backgrounds, best conversion-story potential |

---

## 2.3 Dungeon Ecology

### Social Hierarchy

```
Dungeon Lord (player)
├── Generals/Lieutenants (loyal converted former adventurers)
│   └── Monster minions (skeleton, gargoyle, hellhound…)
│       └── Captive slaves (defeated adventurers)
```

### Dungeon Styles by Archetype

- **Necromancer Lord's Bone Mound**: unsettlingly quiet, bone walls interwoven, floor covered gray-white dust
- **Abyssal Overlord's Inferno**: lava rivers flow through, air of sulfur and rust
- **Mad Sorcerer's Laboratory**: cluttered bottles, walls occasionally seep colored liquid
- **Ancient Wyrm's Hoard**: mountains of gold, every step a coin-clink
- **Shadow Council's Dark Hall**: corridors move themselves, low light but always eyes visible in dark
- **Goblin Tinkerer's Machine City**: gear-mesh noise, steam pipes, auto-rivet rhythm

---

## 2.4 GM Running Guide

### GM's Five Roles

1. **Adventurer Commander**: control invading adventurer squad
2. **World Engine**: drive seasons, weather, world events
3. **NPC Voice**: play captives, dark merchants, adjacent dungeon lords
4. **Rule Judge**: set difficulty, arbitrate disputes
5. **Narrative Pacemaster**: balance management vs combat rhythm

### Invasion Construction Six-Step

1. **Invasion Check**: INF + 1d6 ≥ 8 triggers
2. **Invasion Source**: 1d6 decides which faction
3. **Scale & Tier**: cross-reference INF→Tier map, roll d6 for squad size
4. **Class Composition**: roll d6: 1-2=mixed, 3=physical-leaning, 4=magic-leaning, 5=scout-leaning, 6=all cleric (church)
5. **Narrative Hook**: 1d6: 1=revenge, 2=rescue, 3=treasure, 4=ordered, 5=trial, 6=lost
6. **Special Event Check**: 1/6 chance extra special event (weather, extra reinforcements, temp ally)

### Pace Control

**Management Phase** (dungeon calm):
- Opening: "Another calm Abyss week…" depict dungeon daily life
- Length: 10–20 min, let players discuss and decide
- End signal: when players start hesitating repeatedly, roll invasion to push pace

**Invasion Phase** (combat tension):
- Opening: "Scout outpost reports movement—more from the surface came down"
- Length: 15–30 min, layer-by-layer advance builds tension
- End signal: after last layer breached or adventurers retreat, settlement

### Difficulty Real-Time Tuning

| Means | Direction | Use Case |
|------|------|---------|
| Adjust squad size | ±1–2 | Fine-tune |
| Leak intel early | Lower | Players lack intel |
| Hide intel | Raise | Players too easy |
| Weather/env mod | ±dice | Add variables |
| Insert Boss midway | Raise | Climax needs |

### Captive Narrative Toolbox

**3d6 Captive Background Quick Table**:

| Origin (1d6) | Motive (1d6) | Secret (1d6) |
|-----------|----------|-----------|
| 1=farm kid | 1=raise drug money for sister | 1=actually noble bastard |
| 2=city poor | 2=prove self | 2=carries old lover's letter |
| 3=fallen noble | 3=repay debt | 3=fear of dark (claustrophobia) |
| 4=orphanage raised | 4=follow idol | 4=first mission |
| 5=merchant family | 5=escape past | 5=knows guild high-level secret |
| 6=adventurer family | 6=find missing kin | 6=actually Abyss bloodline |

**Conversion Narrative Four Stages**:
1. **Resistance**: "I'd rather die than work for you!"
2. **Wavering**: "At least… it's more honest here than up there. No one pretends to be good."
3. **Adapting**: "Yesterday I fixed the third-corridor trap, more efficient than that guild bunch."
4. **Converted**: "My lord, a familiar face among the new adventurers—shall I 'reconnect' with them?"

---

## 2.5 Campaign Framework

### Four-Stage Long Campaign

| Stage | DEP Range | Theme | Est. Duration |
|------|---------|------|---------|
| **Establishment** | 1–3 | Build basic dungeon, repel first invasion, first captive | 2–4 sessions |
| **Growth** | 4–7 | Expand defense layers, recruit elite monsters, Adventurers' Guild notices you | 3–6 sessions |
| **Threat** | 8–11 | Legendary heroes deploy, dungeon diplomacy, Abyssal Council | 4–8 sessions |
| **Overlord** | 12–15 | Become Abyss legend, ultimate standoff (Order of Light army vs dungeon alliance) | 6+ sessions |

---

## 2.6 Starter Module: "First Incursion"

### Scene 1: Establish Initial Dungeon

GM depicts:
> "You are a newly risen Dungeon Lord. The throne hall's mana torches are lit—this is your first dungeon. Only three chambers so far: your throne hall, and two undeveloped dark tunnel ends. A few newly recruited monsters pace uneasily at your feet. Faint sounds of surface humans drift from afar—are they coming?"

Player needs: familiarize attributes, assign initial monsters, plan which side to dig first.

### Scene 2: First Excavation Expansion

Player spends 1 action + Building Materials×2, rolls IND+Engineering check for first dig. GM guides narrative of discoveries—may hit ore vein, may find broken diary in ancient ruins.

### Scene 3: First Invasion Wave

Warning: Scout skill check reveals "2 T1 adventurers approaching".

Preset adventurers:
- **Alan** (Warrior T1): CP=1d6, HP=5, shield, "loyal simple, raising drug money for sister"
- **Mira** (Rogue T1): CP=2d6, HP=3, can scout traps, "impulsive, wants to prove self"

Invasion route: outer→middle. Player commands defense.

### Scene 4: First Captive & Interrogation

If defeat adventurer (HP 0 = unconscious): may capture. GM teaches interrogation—let player choose means (interrogate? torture? charm?). Alan's weakness: "mention sister, eyes flicker".

### Scene 5: Post-Battle Settlement & Second Expansion

Distribute loot, use gained resources for second dig. First experience of full "dig→build→assign→defend" loop.

---

## 2.7 Campaign Framework: From Cavern to Abyss Empire (Lv1–15)

### Act One: Establishment (Lv1–3) — 2~4 sessions

**Theme**: survive. Newly crowned Dungeon Lord starts from throne hall + 2 dark tunnels. Outside unknown—every dig sound may bring first adventurers.

| Dungeon Lv | Key Event | GM Focus |
|:---:|------|------|
| 1 | **First Incursion** (see §2.6). Repel 2 T1 adventurers, first taste of defense battle | Tutorial battle. Familiarize combat phase, trap trigger, monster deploy |
| 2 | First excavation expansion success. Find first natural resource (ore vein/mana node). Adjacent NPC dungeon first appears—a letter to your throne hall | Introduce expansion system. Introduce diplomacy concept (reply to letter?) |
| 3 | **"Adventurers' Guild Notices You"**. Two consecutive invasion turns—second wave is revenge squad (led by escaped adventurer). Must decide: strengthen defense or accelerate expansion? | Introduce consecutive invasion pressure. Player must make strategic tradeoff |

**Act One Climax**: "Adventurers' Guild Wanted"—INF reaches 3, guild formally lists your dungeon on "wanted list". GM introduces physical wanted poster (printable prop).

---

### Act Two: Growth (Lv4–7) — 3~6 sessions

**Theme**: expansion and choice. Dungeon takes shape. Abyssal Embassy built—must choose one of Four Alliances to join. Choice affects all future diplomacy.

| Dungeon Lv | Key Event | GM Focus |
|:---:|------|------|
| 4 | May build Abyssal Embassy. Two known NPC dungeons each invite you to their alliance. **Balzec, "Earth-Render"**'s flame missive vs **Malthus, "Iron-Bone Marquis"**'s bone pigeon. Must choose—or stay neutral | Alliance choice. Affects all future diplomacy |
| 5 | Unlock elite monster recruit. First elite invasion (T3, with Boss captain). If allied—ally dungeon may send reinforcements | Boss battle mechanic introduced (Phase 2 trigger). First alliance synergy |
| 6 | Archetype Lv6 advance unlocked. After certain scale—first discover conflicts between other dungeons. **Moris, "Thousand-Faces"** asks you mediate his territory dispute with Balzec | Inter-dungeon politics. Player's choice affects tri-party relation |

**Act Two Climax**: "Abyssal Black Market"—**Grix, "Goldtooth"** (Ancient Wyrm) hosts annual black-market auction in Scrap Canyon. All known NPC dungeon lords attend. Player may: socialize with multiple lords face-to-face / bid on 1 legendary item (min ◆50 start) / assassination event after auction—Shadow Network intel trade.

---

### Act Three: Threat (Lv8–11) — 4~8 sessions

**Theme**: war and betrayal. Dungeon becomes regional power. Order of Light begins organized large-scale expeditions—not adventurer squads but company-level offensives.

| Dungeon Lv | Key Event | GM Focus |
|:---:|------|------|
| 8 | **"Church Expedition"**—Order of Light sends 3–4 T3 squads invading from different entrances simultaneously! Must use ally reinforcements. Dungeon diplomacy check decides how many NPC dungeons willing to send troops | First large-scale multi-front defense. Tests player's resource allocation and diplomacy results |
| 9 | Archetype Lv9 ultimate advance unlocked. Around here—cracks appear within your alliance. Bone Mound Council: Malthus challenged? Abyssal Legion: Balzec demands you take Trial of Fire? Free Artisans: tech-piracy dispute? Shadow Network: traitor leaks intel? | Intra-alliance politics. Player's response decides alliance direction |
| 10 | Unlock first legendary monster. **Moris, "Thousand-Faces"**'s forbidden experiment has serious accident—his dungeon spiraling out of control. If you were friendly—he sends desperate distress signal | Time-sensitive sidequest. Rescue/exploit/ignore three choices affect whole |

**Act Three Climax**: "Breath of Nexis"—Abyss mana tide anomalously fluctuates. **Ethlin** (Void-Weaver) warns: mana tide may be prelude to something "awakening". GM here introduces **Primordial Rift (D-16)**'s first anomaly—it made a sound. Ancient dungeons begin to wake.

---

### Act Four: Overlord (Lv12–15) — 6+ sessions

**Theme**: fateful choice. Your dungeon is top Abyss power. Order of Light prepares "Crusade"—full assault on Abyss. And the being sleeping in **Primordial Rift** is about to wake.

| Dungeon Lv | Key Event | GM Focus |
|:---:|------|------|
| 12 | **"Dungeon Covenant"**—you convene (or are invited to) Abyssal Council. All Lv8+ dungeon lords gather. Topic: unite against Order of Light, or each fight alone? Your diplomacy check decides united front's strength | Multi-NPC diplomatic negotiation. Complete social encounter scene |
| 13 | **"Light Crusade"** begins. T4–T5 adventurer legions attack all alliance dungeons at once. Troops assigned to your dungeon decided by INF—high infamy attracts strongest foes | Ultimate defense battle. Use all accumulated resources, monsters, allies, captive fodder |
| 14 | Crusade continues. If defended successfully last turn—adventurers heavy losses but church reinforces. Turning point appears: **Corwin, "Rusted Duke"** (former holy knight) reveals church has fatal weakness—needs your help to get last intel shard | Surface infiltration mission. May be Lord's last expedition |

**Act Four Climax — Grand Event: "Awakening of Nexis"**:

> *On the 14th full-moon Abyss night of Rift Era Year 700, the Primordial Rift split open. What walked out was no monster—but a consciousness. Nexis, Abyss Mother, opened her eyes after eons of sleep. Her first words echoed through every dungeon in the Abyss:*

> *"My children—what have you made of my underworld?"*

GM scene framework:

| Stage | Content | Check |
|------|------|------|
| **Descent** | Nexis's voice rings through Abyss. All dungeons' Mana Crystals resonate with light at once. Dungeon mana temporarily ×2—but may be reclaimed after | No check. Narrative scene |
| **Judgment** | Nexis examines each alliance. She sees not a united Abyss—but division, infighting, compromise with surface. Her query: **"With my blood, what have you built?"** Player represents own dungeon in response | DOM check (answer query). ARC check (understand her true intent) |
| **Choice** | Nexis gives two choices: **A.** Become her right hand—gain ultimate power, but dungeon becomes her extension (lose some autonomy). **B.** Refuse—banished from Abyss, become wandering lord. **C.** Persuade her—Abyss has evolved, no single mother-goddess needed (extremely hard: DOM+Diplomacy ×3 multi-check, all must succeed) | This is the campaign's ultimate check. Player may use all accumulated intel, ally support, captive testimony to aid debate |
| **Consequence** | A=gain "Mark of Nexis" (dungeon MAG locked 15, all monsters CP+2), but never defy her will again. B=dungeon reclaimed—but at last moment receive joint letter from all allies: you are not alone. Become "Wandering Lord"—dungeon co-kept by allies. C=Nexis smiles. "Perhaps this era truly needs no mother-goddess." She dissipates into mana-filled sky—whole Abyss gains permanent mana +3. Your dungeon becomes new Abyss center |

**Act Four Aftermath — Finale Event**:

Whatever the choice, campaign ends with a **New Abyss Era** initiation ritual:

- If A: your dungeon becomes Nexis's temple. All NPCs come to worship.
- If B: you lose dungeon, but gain "Wandering Legend" status—freely roam between any ally dungeon, with a 24-hour surface counterattack grand event to play.
- If C: your dungeon recognized "new center of Abyss". Order of Light forced to sign ceasefire. Henceforth—dungeons are not monster nests. **They are kingdoms.**

---



# Appendix

## A. Quick Reference

### Check Quick Reference

```
Dice Pool = Attribute + Skill + Environment Mod (cap 10d6)
Roll all d6 → 5-6=1 success, 6=+1 die appended
Successes ≥ Difficulty → success

Degree: 0=Failure / 1=Partial / 2=Full / 3=Critical / 4+=Legendary
Difficulty: Easy=1 / Standard=2 / Hard=3 / Extreme=4 / Epic=5+
```

### Core Formulas

```
Management Dice = Industry (IND) + relevant skill + floor(Σ Management (MV) ÷ 2)
Combat Dice = Warfare (WAR) + monster command/tactical deploy + floor(Σ Combat (CV) ÷ 2)
Attack Damage = Attack dice successes - Defense dice successes + bonus

Captive Will Opposed = Dominion (DOM) + Interrogation skill vs captive WIL
Captive Escape Opposed = captive WIL vs DEF dice + Prison level
Captive Labor Efficiency = STA dice + PL dice (specific class extra +1)

Excavation Check = Industry (IND) + Engineering skill vs space difficulty
Invasion Trigger = Infamy (INF) + 1d6 ≥ 8
```

### Dungeon Attribute Mapping

```
Defense (DEF) → direct dice pool (captive escape opposed)
Infamy (INF) → WAR check bonus dice (every 3 +1 die)
Wealth (WLH) → IND check bonus dice (every 5 +1 die)
Magic (MAG) → ARC check bonus dice (every 3 +1 die)
Depth (DEP) → total room cap + excavation count cap
```

### Adventurer Drop Quick Reference

| Tier | ◆ | ◇ | ● | Magic Item |
|------|---|---|---|---------|
| T1 | 1d3 | 1 | 1 | 5% |
| T2 | 1d6 | 1d3 | 2 | 10% |
| T3 | 2d6 | 1d6 | 3 | 20% |
| T4 | 3d6+5 | 2d6 | 4 | 35% |
| T5 | 5d6+10 | 3d6+3 | 5 | 50% |

---

## B. Glossary

| Term | Abbrev | Definition |
|------|------|------|
| Cunning | Cunning (CUN) | Trap design, ambush, deception, intelligence |
| Dominion | Dominion (DOM) | Interrogation, intimidation, commanding minions, negotiation |
| Arcana | Arcana (ARC) | Magical knowledge, rituals, curses, enchanting |
| Industry | Industry (IND) | Construction, harvesting, forging, engineering |
| Warfare | Warfare (WAR) | Monster command, tactical deployment, defense, deterrence |
| Depth | Depth (DEP) | Dungeon scale and number of layers |
| Infamy | Infamy (INF) | Dungeon notoriety (higher = stronger invasion) |
| Defense | Defense (DEF) | Dungeon fortification strength |
| Wealth | Wealth (WLH) | Economic power and reserves |
| Magic | Magic (MAG) | Mana seepage and ritual power |
| Management Value | Management (MV) | Monster contribution when deployed to management |
| Combat Value | Combat (CV) | Monster combat power when deployed to combat |
| Willpower | Willpower (WIL) | Captive mental resistance to interrogation |
| Stamina | STA | Captive physical condition |
| Profession Level | PL | Captive class skill level |
| Loyalty | Loyalty (LOY) | Monster loyalty to Dungeon Lord (1–5) |
| Net Successes | MoS | Difference between successes and target |
| Dark Coins | ◆ | General currency |
| Mana Crystals | ◇ | Magic resource |
| Building Materials | ■ | Construction resource |
| Soul Essence | ● | Ritual/undead resource |

---

## C. Character Card Template

```
╔══════════════════════════════════════════════════════╗
║                 Abyss Lord  —  Character Card        ║
╠══════════════════════╤═════════════════════════════╣
║ Dungeon: ___________  │ Archetype: ___________      ║
║ Lord Name: _________  │ Dungeon Lv: ___  EXP: ___   ║
╠══════════════════════╧═════════════════════════════╣
║                     Lord Attributes                ║
║  Cunning (CUN): ___ ║ Dominion (DOM): ___ ║ Arcana (ARC): ___ ║
║  Industry (IND): ___ ║ Warfare (WAR): ___           ║
╠══════════════════════════════════════════════════════╣
║                     Dungeon Attributes              ║
║  Depth (DEP): ___  Infamy (INF): ___  Defense (DEF): ___  Wealth (WLH): ___  Magic (MAG): ___ ║
║  Actions: ___/turn   Rooms: ___/___    Gold: ___◆    ║
╠══════════════════════════════════════════════════════╣
║  Core Abilities:                                     ║
║  Passive: ________________________________________   ║
║  Active:  ________________________________________   ║
╠══════════════════════════════════════════════════════╣
║  Skills                                              ║
║  Cunning (CUN): Trap__ Esp__ Stealth__ Poison__      ║
║  Dominion (DOM): Inter__ Lead__ Dip__ Disc__         ║
║  Arcana (ARC): Mana__ Rit__ Ench__ Curse__           ║
║  Industry (IND): Build__ Res__ Forge__ Eng__         ║
║  Warfare (WAR): Tact__ Fear__ Adapt__ Cry__          ║
╠══════════════════════════════════════════════════════╣
║  Resources                                           ║
║  ◆ ________  ◇ ________  ■ ________  ● ________     ║
╠══════════════════════════════════════════════════════╣
║  Monsters/Minions                                    ║
║  ┌─────────┬────┬────┬────┬──────────┬──────┐       ║
║  │ Name    │ Combat(CV) │ Management(MV) │ Loyalty(LOY) │ Mgmt Ability │ Post │ ║
║  ├─────────┼────┼────┼────┼──────────┼──────┤       ║
║  │         │    │    │    │          │ M/C  │       ║
║  │         │    │    │    │          │ M/C  │       ║
║  │         │    │    │    │          │ M/C  │       ║
║  └─────────┴────┴────┴────┴──────────┴──────┘       ║
╠══════════════════════════════════════════════════════╣
║  Captives                                           ║
║  ┌─────────┬─────┬────┬────┬──────────┬──────┐      ║
║  │ Name    │ Will(WIL) │ PL │STA │ Labor     │ State │      ║
║  ├─────────┼─────┼────┼────┼──────────┼──────┤      ║
║  │         │     │    │    │          │      │      ║
║  └─────────┴─────┴────┴────┴──────────┴──────┘      ║
╠══════════════════════════════════════════════════════╣
║  Dungeon Layout (DEP=___, Rooms ___/___)             ║
║  ┌────────────┬────────────┬────────────┐            ║
║  │ [Throne Hall]│ [Space A]  │ [Space B]  │            ║
║  │ Lv_        │ Undev/___   │ Undev/___   │            ║
║  └────────────┴────────────┴────────────┘            ║
║  ______________________________________              ║
╚══════════════════════════════════════════════════════╝
```

---



## E. Magic Item Table (d66)

Magic item drop chance see adventurer drop table. Roll d66 to decide item type and quality:

### Weapons & Armor (11–26)
| d66 | Item | Quality | Effect |
|:---:|------|:---:|------|
| 11 | Shadow Dagger | Common | CUN attack +1 die; on hit target next turn -1 die |
| 12 | Flame Longsword | Common | WAR attack +1 fire damage |
| 13 | Dragonbone Shield | Fine | Defense die +2; fire damage -1 |
| 14 | Holy Light War Hammer | Fine | Damage ×1.5 vs undead/demon (adventurer exclusive) |
| 15 | Poison Blade | Common | Hit applies poison, 1 damage/turn ×3 turns |
| 16 | Frost Staff | Fine | ARC ice spell damage +2; free 1 "Shadow Arrow"/battle |
| 21 | Thunder Spear | Fine | WAR attack may jump to adjacent enemy (second target dice -2) |
| 22 | Dark Erosion Armor | Fine | Physical damage reduction = Warfare (WAR)/2; Holy Light damage +50% |
| 23 | Vampiric Blade | Epic | Recover 1 HP per 3 damage dealt |
| 24 | Demon-Bane Bow | Fine | Ranged attack ignores magic shield (adventurer exclusive) |
| 25 | Giant Slayer | Epic | +3 damage vs targets with CP≥5 |
| 26 | Abyss Verdict | Legendary | Warfare (WAR)+ARC attack dice take higher; 1 free "Annihilation Ray"/battle |

### Accessories & Rings (31–46)
| d66 | Item | Quality | Effect |
|:---:|------|:---:|------|
| 31 | Mana Ring | Common | ◇ storage cap +3 |
| 32 | Invisibility Cloak | Fine | 1/battle: invisible 2 turns (removed after attack/cast) |
| 33 | Lucky Rabbit Foot | Common | 1/battle: reroll 1 die |
| 34 | Charm Necklace | Fine | DOM interrogation +1 die; captive charm effect +1 |
| 35 | Shield Badge | Common | 1/battle: reaction activate, defense dice +3 single |
| 36 | Teleport Stone | Epic | 1/battle: instant teleport to any same-layer room |
| 41 | Undead Charm | Fine | Undead monster LOY+1; skeleton CP+1 |
| 42 | Elemental Heart | Epic | Choose 1 element immunity (fire/ice/lightning/acid, permanent after choose) |
| 43 | Hourglass of Time | Legendary | 1/battle: gain 1 extra full-turn action |
| 44 | Oath Ring | Fine | Exchange with 1 ally: each gains other's 1 archetype passive (shared cooldown) |
| 45 | Void Gem | Epic | May absorb 1 lethal attack (HP recover from 0 to 1, 1/campaign) |
| 46 | Dragon Heart Charm | Legendary | HP cap +5; auto-recover 1 HP/turn |

### Consumables (51–66)
| d66 | Item | Quality | Effect |
|:---:|------|:---:|------|
| 51 | Healing Potion | Common | Recover 2d6 HP (once) |
| 52 | Mana Potion | Common | Recover ◇×3 (once) |
| 53 | Holy Water | Common | 3d6 damage to undead/demon (once, held by adventurer) |
| 54 | Explosive Vial | Common | Same-room AOE 2d6 damage (once) |
| 55 | Invisibility Potion | Fine | 3 turns invisible (once) |
| 56 | Antidote | Common | Remove poison status (once) |
| 61 | Scroll: Shadow Storm | Fine | Cast 1 "Shadow Storm" (needs ARC≥2) |
| 62 | Scroll: Group Shield | Fine | Cast 1 "Group Shield" (needs ARC≥3) |
| 63 | Scroll: Undying Pact | Epic | Cast 1 "Undying Pact" (needs ARC≥4) |
| 64 | Soul Stone | Fine | Store ●×3 (usable as Soul Essence) |
| 65 | Rune Trap | Fine | Immediately deploy 1 free magic rune trap (no build turn) |
| 66 | Tear of Nexis | Legendary | Recover all HP+◇+● to full. 1/campaign hold |

### Magic Item Acquisition

| Source | Chance | Quality Preference |
|------|:---:|------|
| T1 drop | 5% | Common |
| T2 drop | 10% | Common (80%) / Fine (20%) |
| T3 drop | 20% | Fine (70%) / Epic (25%) / Legendary (5%) |
| T4 drop | 35% | Fine (50%) / Epic (35%) / Legendary (15%) |
| T5 drop | 50% | Epic (50%) / Legendary (50%) |
| Abyss Black Market | price = quality base price | Common ◆10 / Fine ◆30 / Epic ◆80 / Legendary ◆200+ |
| Ancient Ruins | 100% | Quality relates to DEP |

---

## D. Design Notes

### Design Team

| Role | Name | Area |
|------|------|---------|
| Core Mechanic Designer | Bi Shi'an | Dice system, attribute framework, check rules, math verification |
| Character System Designer | Ke Jiao'ling | Lord archetypes, dungeon management, expansion, monster system, captive management |
| Combat System Designer | Zhan Zhige | Defense-layer combat, trap system, adventurer templates, invasion generation |
| Worldbuilding Narrative Designer | Jing Shiwen | Worldbuilding, GM guide, captive narrative, starter module |

### Adjustable Directions

1. **Complexity Tuning**: if lighter—drop skill tree, use only attribute + archetype ability checks
2. **Co-op/Competitive Mode**: may switch to multiple players each managing dungeon, compare infamy
3. **Adventurer Mode**: invert perspective, play adventurers attacking dungeon
4. **Expand Monster Pool**: add more monster types per setting as needed
5. **Detailed Magic Item Table**: may later expand full magic item/equipment system |
