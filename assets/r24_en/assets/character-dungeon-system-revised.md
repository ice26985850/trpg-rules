# Dungeon Lord: Character Creation, Dungeon Management, and Territory Expansion System

> **Design Version**: Draft v2.0 (cross-review revised edition)  
> **Dice System**: d6 Dice Pool (5–6 is a success, a 6 may explode for +1 die)  
> **Attribute Ranges**: Lord attributes 1–5 (attribute value = base dice pool size); Dungeon attributes 1–15  
> **Complexity**: Moderate strategy  
> **Alignment Baseline**: Fully unified with the dice system (dice-mechanics) attribute framework

---

## Table of Contents

1. [Dungeon Lord Core Attributes](#i-dungeon-lord-core-attributes)
2. [Skill Tree: 20-Skill Universal Growth System](#ii-skill-tree-20-skill-universal-growth-system)
3. [Dungeon Lord Archetypes](#iii-dungeon-lord-archetypes)
4. [Dungeon Attribute Panel](#iv-dungeon-attribute-panel)
5. [Territory Expansion System](#v-territory-expansion-system) ⭐**Core Addition**
6. [Rooms and Facilities System](#vi-rooms-and-facilities-system)
7. [Monsters and Minions System](#vii-monsters-and-minions-system)
8. [Monster Assignment System](#viii-monster-assignment-system) ⭐**Core Addition**
9. [Random Monster Management Abilities](#ix-random-monster-management-abilities) ⭐**Core Addition**
10. [Captive Management System](#x-captive-management-system)
11. [Resources and Economy System](#xi-resources-and-economy-system)
12. [Character Creation Process](#xii-character-creation-process)
13. [Appendix: Character Sheet Template](#xiii-appendix-character-sheet-template)

---

## I. Dungeon Lord Core Attributes

Each Dungeon Lord has 5 core attributes, ranging from 1 to 5. The attribute value directly maps to the number of dice in the dice pool. **Attribute names are fully unified with the dice system (dice-mechanics).**

### 1.1 Attribute Table (Final Version)

| Abbrev | Full Name | Core Domain | Typical Check Scenarios |
|------|---------|----------|-------------|
| **Cunning (CUN)** | **Cunning** | Traps, deception, intelligence, ambush | Setting traps, forging intel, hiding passages, counter-recon, plotting assassinations |
| **Dominion (DOM)** | **Dominion** | Interrogation, intimidation, commanding minions | Commanding minions, interrogating captives, maintaining discipline, battlefield command, negotiation |
| **Arcana (ARC)** | **Arcana** | Magic, rituals, curses, enchantment | Casting spells, magic research, dispelling, soul-binding, mana manipulation |
| **Industry (IND)** | **Industry** | Construction, harvesting, forging, engineering | Expanding rooms, harvesting resources, trade negotiation, forging equipment, building mechanisms |
| **Warfare (WAR)** | **Warfare** | Monster command, tactical deployment, deterrence/fear | Spreading terror, tactical maneuvering, intimidating enemies, battlefield command, morale strikes |

### 1.2 Attribute Value Mapping

| Attribute Value | Description | Dice Pool |
|--------|------|------|
| 1 | Novice / Weak | 1d6 |
| 2 | Competent / Average | 2d6 |
| 3 | Skilled / Powerful | 3d6 |
| 4 | Expert / Terrifying | 4d6 |
| 5 | Legendary / Mythic | 5d6 |

### 1.3 Attribute Point Allocation

- Initial allocation points: **12 points**
- All five attributes (Cunning (CUN) / Dominion (DOM) / Arcana (ARC) / Industry (IND) / Warfare (WAR)) start at 1
- Raising an attribute by 1 = spending 1 allocation point
- Initial single-attribute cap: 4 (archetype bonus may break through to 5)
- Gain **1 attribute point** per Dungeon Level increase

### 1.4 Attribute Name Change Reference

| New Abbrev | New Full Name | Old Abbrev | Old Full Name | Change Note |
|--------|-------|--------|-------|---------|
| Cunning (CUN) | Cunning | Cunning (CUN) | Cunning | Minor semantic tweak, more precise coverage of "cunning strategy" |
| Dominion (DOM) | Dominion | Dominion (DOM) | Sovereignty | Minor semantic tweak, emphasizing majesty + leadership charisma |
| Arcana (ARC) | Arcana | Arcana (ARC) | Arcane | Minor semantic tweak, closer to "the source of magic" |
| Industry (IND) | Industry | Industry (IND) | Management | Major adjustment: focuses on construction / engineering / harvesting |
| Warfare (WAR) | Warfare | DRE | Fear | **Major adjustment**: Fear → Warfare, covering tactical command + deterrence |

---

## II. Skill Tree: 20-Skill Universal Growth System

> **Aligned with the dice system**: The dice system provides a 20-skill universal growth tree (4 skills per attribute, levels 0–4). Archetype abilities are exclusive superpowers layered on top of the skill tree—the two coexist without conflict.

### 2.1 Skill Tree Structure

Each Dungeon Lord may develop among 20 universal skills; skill levels range from 0 to 4. **Skill level is independent of attribute value**—even at attribute value 1, a skill can be trained to level 4.

### 2.2 Cunning (CUN) Skill Tree

| Level | Skill 1: Trap Master | Skill 2: Espionage | Skill 3: Stealth | Skill 4: Toxicology |
|------|---------------|-----------|----------|-------------|
| Lv0 | Not learned | Not learned | Not learned | Not learned |
| Lv1 | Trap crafting +1 die | +1 intel on intrusions | Dungeon entrance hidden; intruders must check to detect | Can brew basic poison |
| Lv2 | Trap trigger difficulty +1 | Can obtain adventurer class intel | Stealth check +1 die | Poison damage +1 |
| Lv3 | Traps may chain-trigger | Learn invasion size 1 round early | Dungeon location hidden from outside (Infamy growth halved) | Can brew paralysis poison |
| Lv4 | Traps may add Cunning attribute damage | Intel network covers adjacent dungeons | Stealth state Infamy threshold ×2 | Poison may specify effect (sleep / weakness / confusion) |

### 2.3 Dominion (DOM) Skill Tree

| Level | Skill 1: Interrogation Expert | Skill 2: Leader Charisma | Skill 3: Diplomacy | Skill 4: Strict Discipline |
|------|---------------|---------------|---------------|--------------|
| Lv0 | Not learned | Not learned | Not learned | Not learned |
| Lv1 | Interrogation +1 die | Minion loyalty check +1 die | Trade prices −10% | Monster Loyalty drop-check frequency halved |
| Lv2 | May interrogate 2 captives at once | May recruit 1 lieutenant (+1 action) | May ally with another dungeon | Monsters won't flee in combat |
| Lv3 | On 3+ interrogation successes, Willpower −2 | Lieutenant grants +1 efficiency level to a room | May request reinforcements after alliance | Monster base Loyalty +1 |
| Lv4 | May directly turn WIL≤2 captives | May recruit a 2nd lieutenant | May form a dungeon coalition (multilateral) | Minions never betray (Loyalty locked ≥3) |

### 2.4 Arcana (ARC) Skill Tree

| Level | Skill 1: Mana Affinity | Skill 2: Ritual Master | Skill 3: Enchanting | Skill 4: Cursing |
|------|---------------|---------------|------------|------------|
| Lv0 | Not learned | Not learned | Not learned | Not learned |
| Lv1 | Mana Crystal output +1/turn | Ritual check +1 die | Can add magic property to traps | Can curse 1 adventurer (check −1 die) |
| Lv2 | Mana storage cap +50% | Ritual time halved | Can enchant monsters to gain elemental attacks | Curse may lower an adventurer's Tier effect by 1 level |
| Lv3 | Mana Crystals auto-recover 1/turn | May perform 2 rituals simultaneously | Can enchant rooms (+1 level equivalent effect) | May cast area curse (whole floor of adventurers −1 die) |
| Lv4 | Mana burst: +2 dice to one check per scene | Ultimate ritual unlocked | Can create legendary magic items | Death curse: enemies who defeat you permanently −1 attribute |

### 2.5 Industry (IND) Skill Tree

| Level | Skill 1: Master Builder | Skill 2: Resource Management | Skill 3: Smithing | Skill 4: Engineering |
|------|---------------|---------------|------------|------------|
| Lv0 | Not learned | Not learned | Not learned | Not learned |
| Lv1 | Build/upgrade cost −10% | Resource storage cap +20% | Can forge basic weapons/armor | Mechanism build requirement −1 success |
| Lv2 | Build check +1 die | Auto-produce 1 Building Material/turn | Can forge fine equipment | Can build mechanical traps |
| Lv3 | Can build 2 rooms simultaneously | Mine/vault output +50% | Can forge magic items | Can build giant mechanisms (cross-room effect) |
| Lv4 | Rooms may reach Lv4 (over-limit) | Resource consumption reduced 20% | Can forge legendary equipment | Ultimate engineering: doomsday device / giant drill |

### 2.6 Warfare (WAR) Skill Tree

| Level | Skill 1: Tactical Command | Skill 2: Fear Aura | Skill 3: Battle Adaptation | Skill 4: War Cry |
|------|---------------|---------------|---------------|-----------|
| Lv0 | Not learned | Not learned | Not learned | Not learned |
| Lv1 | Defensive combat: monster CP +1 temporarily | First-floor invaders' morale −1 | Terrain use: 1 room defense +1 die | Opening war cry: all enemies −1 die for 1 turn |
| Lv2 | May redeploy 1 monster/turn (free) | Morale strike doubled (−2) | May choose targeted tactics per invasion source | War cry range extends to whole floor |
| Lv3 | In combat, may use Warfare instead of monster CP to attack | Enemies may panic-flee (1/6 chance) | Adapted to that invasion source (permanent +1 die opposed) | War cry adds 1 point of damage |
| Lv4 | May redeploy all monsters 1 extra time/turn | Enemy starts with 1 die lost | Adapted to all known invasion sources | Legendary war cry: all invaders Willpower −1 |

### 2.7 Skill Point Acquisition

| Acquisition Method | Skill Points |
|---------|--------|
| Character creation | **6 points** |
| Each Dungeon Level increase | **2 points** |
| Each successful captive conversion | **1 point** |
| Completing a GM-set dungeon objective | **1–2 points** |
| First defeat of a T3+ adventurer squad | **1 point** |

- Skill Lv1→Lv2: costs 1 skill point
- Skill Lv2→Lv3: costs 2 skill points
- Skill Lv3→Lv4: costs 3 skill points

---

## III. Dungeon Lord Archetypes

The six archetypes correspond to six distinctly different play styles. Each archetype provides attribute adjustments, core archetype abilities (1 passive + 1 active), an initial dungeon configuration, and an advanced ability pool. **Archetype abilities (passive + active + advanced) are exclusive superpowers layered on top of the 20-skill universal growth tree—the two coexist without conflict.**

---

### 3.1 Necromancer Lord

> *"Death is not an end, but the beginning of the workforce."*

**Attribute Adjustment**: Arcana (ARC)+1, Cunning (CUN)+1

**Core Abilities**:
- **Necro Affinity (Passive)**: You may revive the corpses of fallen adventurers into skeleton laborers without spending Soul Essence. Skeleton laborers need no prison space, but labor efficiency is halved (Management Value = 1). Every 3 corpses yields +1 free skeleton laborer.
- **Army of the Dead (Active)**: Spend 3 Mana Crystals (◇), make an Arcana check. Each success summons 1 skeleton soldier (Combat Power = successes, Management Value = 0) into the current defensive combat. Skeletons crumble after battle. Limited to 1/scene.

**Initial Dungeon Configuration**:
- Throne Room Lv1 (free)
- 2 small spaces (undeveloped, must be dug)
- Initial monsters: Skeleton Soldier ×3, Shadow Wraith ×1
- Initial resources: Dark Coins 3, Mana Crystals 5, Building Materials 4, Soul Essence 6

**Play Style**: Win by numbers; skeleton laborers are inefficient but free and never revolt. For players who enjoy the undead theme and pursue "endless labor."

**Advanced Abilities** (Lv3/6/9):
- Lv3 **Soul Harvest**: Each time an adventurer dies in your dungeon, automatically gain 1 Soul Essence
- Lv6 **Lich Conversion**: May convert a captive with zeroed will into a lich lieutenant (Management Value +2, Combat Power +3, may serve as a room supervisor)
- Lv9 **Necro Cataclysm**: Army of the Dead summons 2 skeleton soldiers per success, and skeletons no longer crumble after battle (may retain up to Arcana value ×2 permanent skeleton soldiers)

---

### 3.2 Abyssal Overlord

> *"Power is justice; fear is order."*

**Attribute Adjustment**: Dominion (DOM)+1, Warfare (WAR)+1

**Core Abilities**:
- **Demon Majesty (Passive)**: Against adventurers, your Warfare dice may be used to lower their morale. Each time you appear in combat personally, all enemy units' morale −1. Defeated adventurer captives suffer Willpower (WIL) −1 (initial fear effect).
- **Abyssal Gate (Active)**: Spend 5 Soul Essence (●), make a Dominion check. Each success summons 1 demon minion (Combat Power 3, Management Value = 1, with fire attack), lasting until end of combat. Limited to 1/scene.

**Initial Dungeon Configuration**:
- Throne Room Lv1 (free)
- 2 small spaces (undeveloped, must be dug)
- Initial monsters: Hellhound ×2, Cultist Acolyte ×1
- Initial resources: Dark Coins 4, Mana Crystals 3, Building Materials 4, Soul Essence 7

**Play Style**: Direct confrontation, an overpowering style where you fight in person. Fear is the strongest weapon—for players who like the "steamroll" approach.

**Advanced Abilities** (Lv3/6/9):
- Lv3 **Hellfire**: All monsters deployed in your dungeon gain fire damage +1
- Lv6 **Demon Pact**: Before combat, may recruit temporary demon reinforcements with Soul Essence + Dark Coins (every 3 Dark Coins + 1 Soul Essence = 1 demon, Combat Power 4)
- Lv9 **Abyss Lord**: Abyssal Gate-summoned demon minions' Combat Power raised to 5, and 2 may be kept permanently

---

### 3.3 Mad Sorcerer

> *"Experiment failed? No, that was just an unexpected success."*

**Attribute Adjustment**: Arcana (ARC)+2 (initial Arcana may reach 5)

**Core Abilities**:
- **Mad Experiment (Passive)**: Research Chamber output +50%. But each time you use the Research Chamber, roll 1d6; a 1 triggers an "experiment accident" (random effect table: explosion / mutation / uncontrolled summoned creature, etc.).
- **Chaos Mutation (Active)**: Spend 4 Mana Crystals (◇), make an Arcana check. Inject a mutant serum into a captive or monster; roll 2d6 to determine the effect:
  - 2–3: Death / collapse
  - 4–6: Random positive mutation (Management Value or Combat Power +1)
  - 7–9: Combat Power +1 and a random management ability
  - 10–11: Combat Power +1 and a new special ability
  - 12: Combat Power +2 and loyalty locked at maximum
  Limited to 1/turn.

**Initial Dungeon Configuration**:
- Throne Room Lv1 (free)
- 2 small spaces (undeveloped, must be dug)
- Initial monsters: Gelatinous Slime ×2, Mutant ×1 (with random management ability)
- Initial resources: Dark Coins 2, Mana Crystals 8, Building Materials 3, Soul Essence 4

**Play Style**: High-risk high-reward Rogue-like. Abundant random effects bring chaos and surprise—for players who enjoy the "mad scientist" play style.

**Advanced Abilities** (Lv3/6/9):
- Lv3 **Mutation Stabilizer**: Mad Experiment accident chance drops from 1/6 to 1/12
- Lv6 **Fusion Experiment**: May fuse two same-type monsters into an elite mutant with Combat Power +3 (retains both management abilities, max 2)
- Lv9 **Reality Warp**: Once per turn, may reroll all dice of any one of your own checks

---

### 3.4 Ancient Wyrm

> *"Gold is breath; treasure is scales."*

**Attribute Adjustment**: Industry (IND)+1, Warfare (WAR)+1

**Core Abilities**:
- **Dragon Greed (Passive)**: For every 10 Dark Coins stored in the Vault, produce 1 extra Dark Coin/turn (interest). Vault capacity +50%.
- **Dragon Breath Descent (Active)**: Spend X Dark Coins (X=1–5), make a Warfare check. Each success deals 2 damage to a whole floor of current invaders. Limited to 1/scene. The larger X, the wider the coverage (X=1–2: 1 room, X=3–4: 2 adjacent rooms, X=5: whole floor).

**Initial Dungeon Configuration**:
- Throne Room Lv1 (free)
- 2 small spaces (undeveloped, must be dug)
- Initial monsters: Gargoyle Sentinel ×2, Cultist Acolyte ×1
- Initial resources: Dark Coins 12, Mana Crystals 2, Building Materials 5, Soul Essence 2

**Play Style**: Economy flow. Wealth is the strongest weapon—you can bury enemies under coins. For players who enjoy management and snowball development.

**Advanced Abilities** (Lv3/6/9):
- Lv3 **Great Dragon Majesty**: Every 20 Dark Coins in the Vault grants +1 Warfare die (cap +3)
- Lv6 **True Dragon Form**: May fight in person, converting Dark Coin expenditure into combat power (every 5 Dark Coins = +1 Combat Power dragon-breath attack, one-time)
- Lv9 **Endless Vault**: Vault interest doubled (every 10 Dark Coins produces 2 Dark Coins/turn)

---

### 3.5 Shadow Council

> *"Information is the sharpest blade; lies are the sturdiest shield."*

**Attribute Adjustment**: Cunning (CUN)+2 (initial Cunning may reach 5)

**Core Abilities**:
- **Intel Network (Passive)**: Before each adventurer invasion, make a Cunning check. Each success reveals one piece of intel about the invaders (number, class, Tier, weakness, captain identity, etc.). Knowing intel in advance lets you adjust defensive deployment.
- **Assassination Order (Active)**: Spend 3 Dark Coins, make a Cunning check. Each success deals 1 damage to one adventurer who has not yet entered the dungeon (weakening the enemy before invasion). Higher adventurer Tier requires more successes (T1=1, T2=2, T3=3, and so on). Limited to 1/turn.

**Initial Dungeon Configuration**:
- Throne Room Lv1 (free)
- 2 small spaces (undeveloped, must be dug)
- Initial monsters: Shadow Wraith ×3, Cultist Acolyte ×1
- Initial resources: Dark Coins 6, Mana Crystals 3, Building Materials 3, Soul Essence 5

**Play Style**: Intel flow. Win through information asymmetry, weakening enemies before they even enter the dungeon. For players who enjoy strategic mind-games and "spy warfare."

**Advanced Abilities** (Lv3/6/9):
- Lv3 **Double Agent**: May attempt to turn a captive (Dominion check); success means the captive actively provides adventurer intel and lowers fellow adventurers' morale
- Lv6 **False Intel**: May spread false information to the Adventurers' Guild, lowering the next invasion wave's Tier by 1 level
- Lv9 **Shadow Empire**: Intel network covers all adjacent dungeon regions; you know every movement in the area. Assassination Order may be used on adventurers already inside the dungeon

---

### 3.6 Goblin Tinkerer

> *"Explosions are art; gears are magic."*

**Attribute Adjustment**: Industry (IND)+2 (initial Industry may reach 5)

**Core Abilities**:
- **Mechanical Genius (Passive)**: Trap Workshop build and upgrade cost halved. All trap trigger difficulty +1 (harder to disarm). Trap reset is free.
- **Self-Destruct Machine (Active)**: Spend 2 Building Materials (■)+1 Mana Crystal (◇), make an Industry check. Each success deploys 1 self-destruct goblin robot (Combat Power 1, Management Value = 0; when defeated, explodes dealing 2 damage to adjacent enemies). Robots last until end of combat. Limited to 1/scene.

**Initial Dungeon Configuration**:
- Throne Room Lv1 (free)
- 2 small spaces (undeveloped, must be dug)
- Initial monsters: Mechanical Sentry ×2 (construct, needs no food upkeep, Management Value = 1), Gelatinous Slime ×1
- Initial resources: Dark Coins 3, Mana Crystals 4, Building Materials 10, Soul Essence 1

**Play Style**: Tower-defense flow. Traps are everything; solve enemies with clever mechanisms and explosions. For players who enjoy engineering planning and "letting the dungeon fight for itself."

**Advanced Abilities** (Lv3/6/9):
- Lv3 **Chain Mechanisms**: Traps in adjacent rooms on the same floor may trigger chain reactions (once one trap fires, adjacent traps auto-fire simultaneously)
- Lv6 **Giant Drill**: Dig actions gain an automatic 2 successes on the Industry check. May build the special room "Drilling Platform"
- Lv9 **Doomsday Device**: May build a one-time "Doomsday Device" at the dungeon core that destroys an entire invasion wave, but consumes 20 Building Materials + 10 Mana Crystals

---

### 3.7 Archetype Quick Reference (New Version)

| Archetype | Attribute Bonus | Core Resource Preference | Combat Style | Core Check Attribute |
|------|---------|-------------|---------|------------|
| Necromancer Lord | Arcana (ARC)+1, Cunning (CUN)+1 | Soul Essence | Horde tactics | Arcana (ARC) |
| Abyssal Overlord | Dominion (DOM)+1, Warfare (WAR)+1 | Soul Essence | Frontal steamroll | Dominion (DOM) / Warfare (WAR) |
| Mad Sorcerer | Arcana (ARC)+2 | Mana Crystals | Mutant creatures | Arcana (ARC) |
| Ancient Wyrm | Industry (IND)+1, Warfare (WAR)+1 | Dark Coins | Coin barrage | Industry (IND) / Warfare (WAR) |
| Shadow Council | Cunning (CUN)+2 | Dark Coins | Intel weakening | Cunning (CUN) |
| Goblin Tinkerer | Industry (IND)+2 | Building Materials | Traps and mechanisms | Industry (IND) |

---

## IV. Dungeon Attribute Panel

The dungeon itself has an attribute panel independent of the Lord, representing the dungeon's overall power. **Depth (DEP) / Infamy (INF) / Defense (DEF) / Wealth (WLH) / Magic (MAG) (1–15) are the protagonist attributes; the dice system's derived attributes are used only as quick combat reference values.**

### 4.1 The Five Dungeon Attributes

| Dungeon Attribute | Abbrev | Meaning | Influence |
|----------|------|------|------|
| **Depth** (Depth) | Depth (DEP) | The dungeon's scale and number of floors | Determines total room cap, space level cap, total monster capacity |
| **Infamy** (Infamy) | Infamy (INF) | The dungeon's notoriety and legend status | Determines invading adventurers' Tier and frequency, recruitable monster types |
| **Defense** (Defense) | Defense (DEF) | Strength of defensive fortifications | Per-floor defense value during invasion, captive escape difficulty |
| **Wealth** (Wealth) | Wealth (WLH) | Economic strength and resource reserves | Resource yield bonus, trade negotiation advantage, vault capacity |
| **Magic** (Magic) | Magic (MAG) | Mana penetration and ritual power | Magic room efficiency, ritual success rate, magic defense value |

### 4.2 Dungeon Level and Attribute Growth

Dungeon Level ranges from **1 to 15**; leveling up requires large resource expenditure.

| Dungeon Level | Total EXP Required (Experience (EXP)) | DEP Cap | INF Baseline | Actions/turn | Room Cap | Unlocks |
|----------|----------------|---------|---------|-------------|---------|------|
| 1 | — | 1 | 1 | 2 | 3 | Basic rooms, small-space digging |
| 2 | 10 | 2 | 2 | 2 | 5 | Medium cave digging |
| 3 | 25 | 3 | 3 | 3 | 8 | Advanced rooms, archetype Lv3 ability |
| 4 | 45 | 5 | 4 | 3 | 10 | — |
| 5 | 70 | 7 | 5 | 3 | 12 | Large crypt digging, may recruit elite monsters |
| 6 | 100 | 9 | 6 | 4 | 15 | Archetype Lv6 ability |
| 7 | 140 | 11 | 7 | 4 | 18 | Abyssal Hall digging |
| 8 | 190 | 13 | 8 | 4 | 22 | — |
| 9 | 250 | 15 | 9 | 5 | 26 | Archetype Lv9 ability |
| 10 | 320 | 18 | 10 | 5 | 30 | Legendary monsters |
| 11 | 400 | 21 | 11 | 5 | 35 | — |
| 12 | 500 | 24 | 12 | 6 | 40 | — |
| 13 | 620 | 27 | 13 | 6 | 46 | — |
| 14 | 760 | 30 | 14 | 6 | 52 | — |
| 15 | 920 | 34 | 15 | 7 | 60 | Ultimate ability |

### 4.3 Experience Acquisition

| Action | EXP Gained |
|------|---------|
| Repel one wave of adventurer invasion | +3 Experience (EXP) |
| Capture one adventurer (Tier ×1 EXP) | +1~5 Experience (EXP) |
| Build / upgrade one room | +1 Experience (EXP) |
| Successfully dig a new space | +2 Experience (EXP) |
| Raise a dungeon attribute by 1 | +2 Experience (EXP) |
| Complete a GM-set dungeon objective | +2~5 Experience (EXP) |
| First recruitment of a monster type | +1 Experience (EXP) |
| Successful captive conversion | +2 Experience (EXP) |
| Adventurer Boss defeated | +5 Experience (EXP) |

### 4.4 Dungeon Attribute Increases

Raising a dungeon attribute requires spending resources and making a check:

| Raise Target | Resource Cost | Check Attribute | Difficulty | Note |
|----------|---------|---------|------|------|
| Depth (DEP)+1 | Building Materials ×8, Dark Coins ×3 | Industry (IND) | 2 successes | Dig to expand dungeon (may combine with Territory Expansion System to lower cost) |
| Infamy (INF)+1 | Soul Essence ×5 | Warfare (WAR) | 2 successes | Spread notoriety rumors |
| Defense (DEF)+1 | Building Materials ×5, Dark Coins ×2 | Industry (IND) / Cunning (CUN) | 2 successes | Reinforce fortifications |
| Wealth (WLH)+1 | Dark Coins ×10 | Industry (IND) | 2 successes | Invest in economy |
| Magic (MAG)+1 | Mana Crystals ×8 | Arcana (ARC) | 2 successes | Build mana node |

---

## V. Territory Expansion System ⭐Core Addition

> *"Start from a tiny throne room, dig into the dark depths—who knows what the next pick strike will reveal."*

### 5.1 Spaces and Digging

A dungeon is composed of "spaces." The initial dungeon has only the Throne Room (free) + 2 small spaces (undeveloped). The player must unlock more spaces through **dig actions**, then build rooms.

#### 5.1.1 Space Levels

| Space Level | Name | Room Slots | Dig Difficulty (Industry (IND)) | Building Material Cost | Time (turns) | Unlock Condition |
|----------|------|---------|--------------|---------|-----------|---------|
| — | **Throne Room** | 1 | — | — | — | Initially free |
| Lv1 | **Small Cave** | 1 | 1 success | ■×2 | 1 | Available from start |
| Lv2 | **Medium Cave** | 2 | 2 successes | ■×5 | 2 | Depth (DEP)≥2 |
| Lv3 | **Large Crypt** | 3 | 3 successes | ■×8 | 3 | Depth (DEP)≥5 |
| Lv4 | **Abyssal Hall** | 4 | 4 successes | ■×12, ◇×3 | 4 | Depth (DEP)≥7 |

**Space Occupancy Rules**:
- Small space = 1 room slot (can build 1 basic room)
- Medium Cave = 2 room slots (can build 1 medium room or 2 basic rooms)
- Large Crypt = 3 room slots (can build large facilities)
- Abyssal Hall = 4 room slots (ultimate facilities, e.g. Doomsday Device, Dragon Lair, etc.)

#### 5.1.2 Dig Action

```
Player spends 1 action → choose target space level to dig → pay Building Materials → roll Industry check
                                                ↓
                               ┌─────────────────┼─────────────────┐
                         0 successes:      1 success:         2+ successes:
                         Dig fails         Partial success     Full success
                         Materials spent   Space unlocked but  Space unlocked
                         but space locked  extra cost +1 turn  normally
                                          or attached discovery canceled
```

**Dig Bonuses**:
- Goblin Tinkerer archetype: Industry check auto +1 die
- Industry skill "Master Builder" Lv1+: cost −10%
- Monster "Sapper" management ability: Industry +1 die
- Captive warriors assigned to dig labor: +Profession Level dice

### 5.2 Two-Step Build Process

```
Step 1: Dig to unlock space
  ↓ spend Building Materials + time, roll Industry check
Step 2: Choose room type to build
  ↓ build room in an unlocked space (see Chapter Six)
  Done!
```

**Important Rules**:
- Must **dig first** to unlock space, **then build** rooms
- Cannot build directly in an undug space
- Number of rooms a space can hold is determined by its space level
- The Throne Room is unique—you may own only one Throne Room; other spaces cannot be converted into a Throne Room

### 5.3 Expansion Limits

| Limit Type | Rule |
|----------|------|
| **Total Room Cap** | Determined by Depth (DEP) (see 4.2 level table) |
| **Space Level Unlock** | Determined by Depth (DEP) for diggable space levels |
| **Resource Limit** | Cannot dig without enough Building Materials |
| **Time Limit** | Higher-level spaces take longer; unavailable during that period |
| **Geographic Limit** | Each space must connect to an existing space via tunnels (forming a layered structure) |

### 5.4 Discovery System ⭐

While digging you may unexpectedly find natural resources! After each successful dig, roll 1d6:

| d6 | Discovery | Effect |
|----|------|------|
| 1 | **No Special Discovery** | Only a standard space gained |
| 2–3 | **Mineral Vein** | Mine output in that space +50% (permanent) |
| 4 | **Mana Node** | Magic-related rooms in that space gain +1 die efficiency (permanent) |
| 5 | **Underground Lake** | Space may freely supply monster drinking water upkeep (upkeep −50%), may build special aquaculture facilities |
| 6 | **Ancient Ruins** | Discover random treasure / magic item / hidden knowledge. GM rolls 1d6 sub-table: 1–2 = 2d6 Dark Coins, 3–4 = 1d6+1 Mana Crystals, 5 = 1 fine magic item, 6 = hidden plot thread clue |

**Discovery Modification**:
- Industry skill "Resource Management" Lv3+: discovery result +1 (min 2, max 6+)
- Higher Depth → higher discovery chance: at Depth≥5, 1–2 = Mineral Vein, 3–4 = Mana Node, 5 = Underground Lake, 6 = Ancient Ruins (i.e. "No Special Discovery" result eliminated)

### 5.5 Dungeon Layer Structure

```
Dungeon layer structure diagram (initial Depth (DEP)=1):

┌──────────────────────────────────────┐
│  Depth (DEP) 1 (Outer Layer)                 │
│  ┌────────┐  ┌────────┐  ┌────────┐  │
│  │ Throne │  │Small   │  │Small   │  │
│  │ Room   │  │Space A │  │Space B │  │
│  │ (free) │  │(undev.)│  │(undev.)│  │
│  └────────┘  └────────┘  └────────┘  │
│       ↑           ↑           ↑       │
│       └───────────┼───────────┘       │
│               Tunnel connection               │
└──────────────────────────────────────┘

Example after expansion (DEP=3):

┌──────────────────────────────────────┐
│  Depth (DEP) 1 (Outer Layer - Defense Zone)         │
│  [Throne Room]──[Trap Workshop (Small Space A)]          │
│       │                               │
│       └──────[Scrying Post (Small Space B)]        │
│                │                      │
├────────────────┼──────────────────────┤
│  Depth (DEP) 2 (Middle Layer - Combat Zone)         │
│       [Monster Lair (Medium Cave C)]             │
│                │                      │
├────────────────┼──────────────────────┤
│  Depth (DEP) 3 (Inner Layer - Resource Zone)         │
│       [Mines (Small Space D)]──[Research Chamber (Small E)]  │
└──────────────────────────────────────┘
```

### 5.6 Depth and Invasion Routes

| DEP Range | Invader Arrival Difficulty | Typical Use |
|---------|-------------|---------|
| Depth (DEP) 1 | First to contact | Trap defense zone, outpost |
| Depth (DEP) 2–3 | Middle defense line | Monster deployment, training ground |
| Depth (DEP) 4–5 | Core outpost | Resource zone, research zone |
| Depth (DEP) 6+ | Deepest layer | Throne Room, Vault, Altar (safest) |

---

## VI. Rooms and Facilities System

### 6.1 Room Building Rules

Building a room requires:
1. An unlocked buildable space
2. Paying build cost (Dark Coins + Building Materials + others)
3. Spending 1–2 actions
4. No check needed (building is deterministic), but upgrading high-level rooms may require an Industry check

### 6.2 Basic Room Types

#### 1. Throne Room — Unique
> *The heart of the dungeon, where the Lord's throne sits.*

| Level | Build Cost | Effect | Upkeep/turn |
|------|---------|------|----------|
| Lv1 | Initially free | Dungeon command center, +1 action/turn | None |
| Lv2 | ■×8, ◆×5 | +1 action/turn, Dominion check +1 die | ◆×1 |
| Lv3 | ■×15, ◆×10, ◇×5 | +2 actions/turn, Dominion + Arcana check each +1 die | ◆×3 |

**Special**: Throne Room breached = dungeon defeated. Must always own exactly 1 Throne Room.

---

#### 2. Trap Workshop

| Level | Build Cost | Effect | Upkeep/turn |
|------|---------|------|----------|
| Lv1 | ■×4, ◆×2 | May craft 1 trap/turn | ■×1 |
| Lv2 | ■×8, ◆×4 | May craft 2 traps/turn, trap damage +1 | ■×2 |
| Lv3 | ■×14, ◆×8, ◇×3 | May craft 3 traps/turn, traps carry magic property | ■×3, ◇×1 |

---

#### 3. Monster Lair

| Level | Build Cost | Effect | Upkeep/turn |
|------|---------|------|----------|
| Lv1 | ■×3, ●×3 | Holds 3 monster units, may recruit 1 basic monster/turn | ◆×1 |
| Lv2 | ■×7, ●×5 | Holds 6 monster units, recruited monster Combat Power +1 | ◆×2, ●×1 |
| Lv3 | ■×12, ●×10, ◇×5 | Holds 12 monster units, may recruit elite monsters | ◆×4, ●×2 |

---

#### 4. Prison Cells

| Level | Build Cost | Effect | Upkeep/turn |
|------|---------|------|----------|
| Lv1 | ■×2, ◆×1 | Holds up to 2 captives | ◆×1 |
| Lv2 | ■×5, ◆×3 | Holds up to 5 captives, interrogation check +1 die | ◆×2 |
| Lv3 | ■×10, ◆×6, ◇×4 | Holds up to 10 captives, may perform "brainwashing ritual" | ◆×4, ◇×1 |

---

#### 5. Mines

| Level | Build Cost | Effect | Upkeep/turn |
|------|---------|------|----------|
| Lv1 | ■×3, ◆×2 | Produces ■×2, ◆×1/turn | None |
| Lv2 | ■×7, ◆×5 | Produces ■×4, ◆×2, ◇×1 (chance)/turn | ◆×1 |
| Lv3 | ■×13, ◆×10 | Produces ■×6, ◆×4, ◇×2/turn | ◆×3 |

---

#### 6. Research Chamber

| Level | Build Cost | Effect | Upkeep/turn |
|------|---------|------|----------|
| Lv1 | ■×2, ◇×5 | Produces ◇×2/turn, may research 1 project | ◇×1 |
| Lv2 | ■×5, ◇×10 | Produces ◇×4/turn, research speed +50% | ◇×2 |
| Lv3 | ■×9, ◇×20, ●×5 | Produces ◇×6/turn, may research 2 projects simultaneously | ◇×4 |

---

#### 7. Treasure Vault

| Level | Build Cost | Effect | Upkeep/turn |
|------|---------|------|----------|
| Lv1 | ■×4, ◆×5 | Storage cap 30◆, interest +1◆/10 deposited/turn | None |
| Lv2 | ■×8, ◆×10 | Storage cap 80◆, interest +2◆/10 deposited | ◆×1 |
| Lv3 | ■×15, ◆×20, ◇×5 | Storage cap 200◆, interest +3◆/10 deposited, magic protection | ◆×3 |

---

#### 8. Ritual Chamber

| Level | Build Cost | Effect | Upkeep/turn |
|------|---------|------|----------|
| Lv1 | ■×3, ●×5 | May hold basic rituals, produces ●×1/turn | ◇×1 |
| Lv2 | ■×7, ●×10, ◇×5 | Ritual effect +50%, may hold advanced rituals | ◇×2, ●×1 |
| Lv3 | ■×12, ●×20, ◇×10 | May hold ultimate rituals, produces ●×3/turn | ◇×4, ●×2 |

---

#### 9. Training Ground

| Level | Build Cost | Effect | Upkeep/turn |
|------|---------|------|----------|
| Lv1 | ■×4, ◆×3 | May train 1 monster +1 Combat Power/turn (cap +2) | ◆×2 |
| Lv2 | ■×8, ◆×6 | May train 2 monsters +1 Combat Power/turn (cap +3) | ◆×3 |
| Lv3 | ■×13, ◆×10, ◇×3 | May train monsters' special combat arts, Combat Power cap +5 | ◆×5 |

---

#### 10. Scrying Post

| Level | Build Cost | Effect | Upkeep/turn |
|------|---------|------|----------|
| Lv1 | ■×2, ◇×3 | Invasion Warning +1 turn prep time, Cunning check +1 die | ◇×1 |
| Lv2 | ■×5, ◇×6 | Invasion Warning +2 turns, may see adventurers' specific class | ◇×2 |
| Lv3 | ■×9, ◇×10, ●×3 | May remotely scout Adventurers' Guild movements, 1 free intel/turn | ◇×3 |

---

### 6.3 Room Synergy Effects

| Room Combination | Synergy Effect |
|----------|---------|
| Trap Workshop + Research Chamber | Trap trigger difficulty +1 |
| Monster Lair + Training Ground | Recruited monster initial Combat Power +1 |
| Prison Cells + Altar | Soul Essence from sacrificing captives +50% |
| Mines + Vault | Mines produce extra ◆×1/turn |
| Research Chamber + Altar | Research speed +25%, may research ritual-type projects |
| Throne Room + Scrying Post | All defense checks +1 die |
| Prison Cells ×2 + Altar | Unlocks "Soul Farm"—captive will slowly auto-drains, producing ● |
| Monster Lair + Research Chamber | Unlocks "Chimera Experiment"—fuse two monsters to create a new breed |

---

## VII. Monsters and Minions System

### 7.1 Monster Dual-Dimension Attributes ⭐

Each monster has values in two dimensions—**combat** and **management**:

| Attribute | Abbrev | Meaning | Range |
|------|------|------|------|
| **Combat Power** | Combat Power (CP) | Combat dice pool, used for both attack and defense | 1–8 |
| **Management Value** | Management Value (MV) | Management dice pool, used for production / construction | 1–5 |
| **Loyalty** | Loyalty (LOY) | Degree of obedience | 1–5 |
| **Upkeep** | Upkeep | Resources consumed per turn | Varies |
| **Management Ability** | Management Ability (MA) | Randomly gained special management skill | d66 random |
| **Size** | Size | Occupies lair capacity | 1–3 |

**Key Design**: Combat Power and Management Value are two independent dimensions. A monster may be weak in combat but strong in management (e.g. Cultist Acolyte Combat Power 1, Management Value (MV) 3), or vice versa (e.g. Gargoyle Sentinel Combat Power 3, Management Value (MV) 1). The Monster Assignment System (see Chapter Eight) requires the player to decide each monster's use every turn.

### 7.2 Monster Loyalty

| Loyalty Value | Status | Check Difficulty | Behavior |
|--------|------|---------|------|
| 5 | Absolute Loyalty | — | Never betrays, Combat Power +1 |
| 4 | Loyal | Needs 2 successes to shake | Executes orders normally |
| 3 | Obedient | Needs 1 success to shake | Executes orders but may be passive |
| 2 | Wavering | Auto check each turn, 1 success = revolt | May flee or rebel |
| 1 | Hostile | Immediately revolts | Attacks the dungeon side |

### 7.3 Basic Monster Catalog (with Management Value)

#### 1. Skeleton Soldier
| Combat Power (CP) | Management Value (MV) | Loyalty (LOY) | Upkeep/turn | Size |
|----|-----|-----|----------|------|
| 1 | 0 | 5 | None | 1 |

**Traits**: **Undead**: needs no food/rest, immune to poison/fear. **Fragile**: when hit, roll 1d6; on 1–2 it crumbles immediately. **No Management Ability**: skeletons are too dimwitted to gain random management abilities.

Recruit cost: ●×1 (requires corpses)  
Suited for: Necromancer Lord, cheap cannon fodder

---

#### 2. Gelatinous Slime
| Combat Power (CP) | Management Value (MV) | Loyalty (LOY) | Upkeep/turn | Size |
|----|-----|-----|----------|------|
| 2 | 1 | 2 | ◆×1 (food scraps) | 2 |

**Traits**: **Corrosion**: attacks can dissolve metal armor. **Split**: when defeated, roll 1d6; on 5–6 splits into 2 CP1 small slimes.

Recruit cost: ◇×2  
Suited for: Mad Sorcerer, corridor defense

---

#### 3. Shadow Wraith
| Combat Power (CP) | Management Value (MV) | Loyalty (LOY) | Upkeep/turn | Size |
|----|-----|-----|----------|------|
| 2 | 2 | 3 | ◇×1 | 1 |

**Traits**: **Void**: physical attacks only hit 50% of the time. **Shadow Walk**: may deploy in any room without occupying a tunnel.

Recruit cost: ●×3  
Suited for: Shadow Council, ambush tactics

---

#### 4. Gargoyle Sentinel
| Combat Power (CP) | Management Value (MV) | Loyalty (LOY) | Upkeep/turn | Size |
|----|-----|-----|----------|------|
| 3 | 1 | 4 | ◇×1 | 2 |

**Traits**: **Petrify**: each combat turn may attempt to petrify 1 enemy (Dominion opposed). **Flight**: may support adjacent rooms.

Recruit cost: ■×4 + ◇×3  
Suited for: Ancient Wyrm, middle-layer defense

---

#### 5. Hellhound
| Combat Power (CP) | Management Value (MV) | Loyalty (LOY) | Upkeep/turn | Size |
|----|-----|-----|----------|------|
| 3 | 2 | 3 | ◆×2, ◇×1 | 2 |

**Traits**: **Fire Breath**: attacks carry burning. **Tracking**: when a fleeing captive is tracked by a hellhound, escape check −2 dice.

Recruit cost: ●×4 + ◆×3  
Suited for: Abyssal Overlord, tracking fleeing captives

---

#### 6. Elemental Construct
| Combat Power (CP) | Management Value (MV) | Loyalty (LOY) | Upkeep/turn | Size |
|----|-----|-----|----------|------|
| 4 | 2 | 5 | ◇×3 | 3 |

**Traits**: **Construct**: absolutely loyal, immune to mind effects and poison. **Elemental Shield** (fire/ice/lightning): corresponding element Combat Power +1.

Recruit cost: ■×6 + ◇×6  
Suited for: Goblin Tinkerer (mechanical), Mad Sorcerer

---

#### 7. Spider Swarm
| Combat Power (CP) | Management Value (MV) | Loyalty (LOY) | Upkeep/turn | Size |
|----|-----|-----|----------|------|
| 2 | 2 | 2 | ◆×1 | 2 |

**Traits**: **Weaving**: after deployment, that room gains +1 trap effect. **Venom**: after a hit, enemy loses 1 Combat Power/turn (stackable twice).

Recruit cost: ●×2 + ◆×2  
Suited for: any archetype, trap synergy

---

#### 8. Cultist Acolyte
| Combat Power (CP) | Management Value (MV) | Loyalty (LOY) | Upkeep/turn | Size |
|----|-----|-----|----------|------|
| 1 | 3 | 4 | ◆×1 | 1 |

**Traits**: **Jack of All Trades**: may be used as 1 unit of captive labor. **Faith**: each turn may pray once, low chance to produce ●×1.

Recruit cost: ◆×5  
Suited for: dungeons needing extra labor

---

### 7.4 Elite Monsters (unlocked at Dungeon Level 5+)

| Monster | Combat Power (CP) | Management Value (MV) | Loyalty (LOY) | Upkeep | Size | Traits |
|------|-----|-----|-----|------|------|------|
| **Death Knight** | 5 | 3 | 4 | ◆×3, ●×1 | 2 | Undead aura: adjacent skeleton soldiers Combat Power +1. Command: may lead 3 skeleton soldiers |
| **Abyssal Fiend** | 6 | 1 | 2 | ●×3 | 3 | Sacrifice: sacrifice allies to recover 2 HP. Frenzy: at HP<50%, Combat Power +2 |
| **Chimera Beast** | 5 | 2 | 2 | ◆×3, ◇×2 | 3 | 2 random monster traits. Unstable: 1/6 chance to attack allies |
| **Dragonborn Guard** | 5 | 3 | 4 | ◆×5 | 2 | Dragon-breath area attack. Loyalty never drops |
| **Assassin Master** | 4 | 3 | 3 | ◆×4 | 1 | Assassinate: before combat, Cunning check to assassinate 1 enemy |
| **Mechanical Colossus** | 6 | 2 | 5 | ◇×4 | 3 | Construct immunity. Destroyer Mode: Combat Power +2 for one turn |

### 7.5 Legendary Monsters (unlocked at Dungeon Level 10+)

| Monster | Combat Power (CP) | Management Value (MV) | Loyalty (LOY) | Upkeep | Size | Traits |
|------|-----|-----|-----|------|------|------|
| **Bone Dragon** | 7 | 2 | 4 | ●×5 | 3 | Undead dragon breath: area fear + damage |
| **Abyss Lord** | 8 | 4 | 3 | ●×6 | 3 | Summon minions, hell portal |
| **Ancient Golem** | 8 | 3 | 5 | ◇×6 | 4 | Complete magic immunity, self-repair each turn |

### 7.6 Monster Deployment Rules

- Each Monster Lair Lv1 supports 3 **size units** of monsters
- Monsters may deploy in any room (not just lairs), but monsters not deployed in a lair lose 1 Loyalty/turn
- Each room may deploy up to (room level × 2) size units of monsters
- Monsters may move between dungeon floors (costs 1 action)
- Defeated in combat: Combat Power drops to 0, roll 1d6 (1–2: permanent death, 3–4: heavy wound needs 3 turns to recover, 5–6: light wound recovers next turn)

---

## VIII. Monster Assignment System ⭐Core Addition

> *"Every monster has two callings: swing the pick in the dungeon depths, or swing the claw at the dungeon entrance."*

### 8.1 Core Mechanic

Each monster must be assigned to one of two posts **before each turn begins**:

```
                      ┌──────────────┐
                      │   Monster Pool  │
                      │  (all minions)  │
                      └──────┬───────┘
                             │
              ┌──────────────┴──────────────┐
              │                             │
     ┌────────▼────────┐          ┌────────▼────────┐
     │   Management Post │          │   Combat Defense  │
     │  (Management)    │          │  (Combat)        │
     ├──────────────────┤          ├──────────────────┤
     │ • Assign to       │          │ • Deploy to       │
     │   production       │          │   defense floors  │
     │ • Contribute mgmt  │          │ • Contribute combat│
     │   dice pool        │          │   dice pool        │
     │ • Use mgmt ability │          │ • Use combat traits│
     │ • Monsters with    │          │ • Monsters with    │
     │   MV > CP should   │          │   CP > MV should   │
     │   be prioritized   │          │   be prioritized   │
     └──────────────────┘          └──────────────────┘
```

### 8.2 Assignment Rules

1. **Assign once per round**: At the start of the "Action Phase" each turn, all monster post assignments must be completed
2. **No double posts**: The same monster cannot appear in both management and combat posts
3. **Combat-post monsters cannot do management**: Monsters assigned to defense contribute no Management Value that turn
4. **Management-post monsters are not on the front line by default**: Monsters assigned to management do not participate in that turn's combat defense (unless emergency redeployed)
5. **Emergency Redeployment**: During the invasion phase, spend 1 action to urgently pull a management-post monster into combat (but that monster's management contribution is zeroed that turn, and Loyalty temporarily −1)
6. **Default rule**: Unspecified monsters default to combat defense

### 8.3 Management Deployment

Monsters assigned to **production facilities** (Mines, Research Chamber, Trap Workshop, etc.) contribute management output.

| Monster MV | Management Contribution |
|--------|---------|
| 1 | Corresponding facility output +1 die (or equivalent +1 resource/turn) |
| 2 | Corresponding facility output +2 dice |
| 3 | Corresponding facility output +3 dice, and may use 1 management ability |
| 4 | Corresponding facility output +4 dice, and may use all management abilities |
| 5 | Corresponding facility output +5 dice, and may use all management abilities |

**Facility Matching**:
- Mines: suited to high-MV monsters with miner-related management abilities
- Research Chamber: suited to high-MV monsters with magic/research management abilities
- Trap Workshop: suited to high-MV monsters with deft-hands/craftsman management abilities
- Training Ground: suited to high-MV monsters with beastmaster abilities
- Prison Cells: suited to high-MV monsters with warden abilities

### 8.4 Combat Defense

Monsters deployed in rooms across dungeon floors for defense.

| Monster CP | Combat Contribution |
|--------|---------|
| 1 | Combat dice pool 1d6 |
| 2 | Combat dice pool 2d6 |
| 3 | Combat dice pool 3d6 |
| 4 | Combat dice pool 4d6 |
| 5 | Combat dice pool 5d6 |
| 6–8 | Combat dice pool CP number of d6 + extra combat traits |

### 8.5 Assignment Strategy Example

**Scenario**: The player owns 5 monsters—Gargoyle Sentinel (Combat Power (CP) 3 / Management Value (MV) 1), Hellhound (Combat Power (CP) 3 / Management Value (MV) 2), Cultist Acolyte (Combat Power (CP) 1 / Management Value (MV) 3), Shadow Wraith (Combat Power (CP) 2 / Management Value (MV) 2), Skeleton Soldier (Combat Power (CP) 1 / Management Value (MV) 0)

| Strategy | Management Deployment | Combat Defense | Note |
|------|---------|---------|------|
| **Balanced** | Cultist Acolyte (Management Value (MV) 3) + Shadow Wraith (Management Value (MV) 2) | Gargoyle Sentinel (Combat Power (CP) 3) + Hellhound (Combat Power (CP) 3) + Skeleton Soldier (Combat Power (CP) 1) | Management dice 5, Combat dice 7 |
| **Management-leaning** | Cultist Acolyte (Management Value (MV) 3) + Shadow Wraith (Management Value (MV) 2) + Hellhound (Management Value (MV) 2) | Gargoyle Sentinel (Combat Power (CP) 3) + Skeleton Soldier (Combat Power (CP) 1) | Management dice 7, Combat dice 4 |
| **Defense-leaning** | Cultist Acolyte (Management Value (MV) 3) | Gargoyle Sentinel (Combat Power (CP) 3) + Hellhound (Combat Power (CP) 3) + Shadow Wraith (Combat Power (CP) 2) + Skeleton Soldier (Combat Power (CP) 1) | Management dice 3, Combat dice 9 |

**Decision Dimensions**:
- Expecting invasion this month → lean defense
- Urgently need Building Materials to expand → lean management
- Skeleton Soldier MV=0 cannot be management-deployed, only fights or idles

---

## IX. Random Monster Management Abilities ⭐Core Addition

> *"You never know if the next hellhound will turn out to be an excellent miner."*

### 9.1 Ability Acquisition Mechanic

When recruiting/hatching a monster, roll d66 (two d6, one tens one units) to gain 1 random management skill. Legendary/elite monsters may have 2 management abilities.

### 9.2 Ability Strength Tiers

| Monster Level (ML) | Ability Strength | Abilities Obtainable | Dice Pool Range |
|-------------|---------|--------------|---------|
| ML1–2 (basic monsters) | **Normal** | 1 ability | d66, 1–36 |
| ML3–4 (elite monsters) | **Enhanced** | 1 ability | d66, 1–52 |
| ML5+ (legendary/elite+) | **Expert** | 2 abilities | d66, full table |

### 9.3 Management Ability Table (d66, 16 abilities total)

| d66 | Ability Name | Effect | Strength |
|-----|---------|------|------|
| 11 | **Miner** | When assigned to Mines, mine output +1 die | Normal |
| 12 | **Vein Sense** | When assigned to Mines, mine output +2 dice and 1/6 chance/turn to find extra vein (◆+2) | Expert |
| 13 | **Warden** | When assigned to Prison Cells, captive escape check difficulty +1 | Normal |
| 14 | **Jailer** | When assigned to Prison Cells, captive escape difficulty +2 and auto-lowers 1 captive's Willpower −1/turn | Enhanced |
| 15 | **Deft Hands** | When assigned to Trap Workshop, trap build cost −20% Building Materials | Normal |
| 16 | **Trap Master** | When assigned to Trap Workshop, trap build cost −30% and crafts 1 extra trap/turn | Expert |
| 21 | **Lab Assistant** | When assigned to Research Chamber, research output +1 die | Normal |
| 22 | **Mana Resonance** | When assigned to Research Chamber, research output +2 dice and Mana Crystal output +1/turn | Enhanced |
| 23 | **Overseer** | When assigned to any production facility, all captive labor efficiency in that facility +20% | Normal |
| 24 | **Cruel Overseer** | When assigned to any production facility, captive labor efficiency +40% but Stamina cost doubled | Enhanced |
| 25 | **Treasure Hunter** | When assigned to Vault, vault interest extra +1◆/10 deposited | Normal |
| 26 | **Wealth Scent** | When assigned to Vault, interest doubled; invading adventurers' death drop of Dark Coins +50% | Expert |
| 31 | **Artisan** | When assigned to any room, that room's build/upgrade cost −10% | Normal |
| 32 | **Master Builder** | When assigned to any room, build/upgrade cost −25% and time −1 turn (min 1) | Expert |
| 33 | **Sentinel** | When assigned to any outer-layer room, invasionWarning +1 turn | Normal |
| 34 | **Vigilant Guard** | When assigned to any outer-layer room,Warning +2 turns and can identify invaders' specific identity | Enhanced |
| 35 | **Hauler** | When assigned to any facility, that facility's resource storage cap +20% (global effect) | Normal |
| 36 | **Logistics Expert** | When assigned to any facility, all resource storage caps +30% and auto-hauls 1 Building Material/turn | Enhanced |
| 41 | **Whisperer** | When assigned to Scrying Post, intel collection Cunning check +1 die | Normal |
| 42 | **Spy Network** | When assigned to Scrying Post, 1 free intel automatically/turn, Cunning check +2 dice | Expert |
| 43 | **Hatcher** | When assigned to Monster Lair, monster recruit cost −20% | Normal |
| 44 | **Breeding Master** | When assigned to Monster Lair, recruit cost −30% and newly recruited monsters' initial Loyalty +1 | Enhanced |
| 45 | **Ritual Aide** | When assigned to Ritual Chamber/Altar, ritual check +1 die | Normal |
| 46 | **High Priest** | When assigned to Ritual Chamber/Altar, ritual check +2 dice and Soul Essence output +1/turn | Expert |
| 51 | **Beastmaster** | When assigned to Monster Lair, all monsters in same lair Loyalty +1 | Enhanced |
| 52 | **Crystallizer** | When assigned to any mana-related room, Mana Crystal output +1/turn | Enhanced |
| 53 | **Sapper** | When participating in dig actions, Industry check +1 die | Normal |
| 54 | **Tunnel Expert** | When participating in dig actions, Industry check +2 dice and Building Material cost −20% | Enhanced |
| 55 | **Anatomist** | When assigned to Prison Cells/Altar, captive conversion success rate +10% (at will-zeroing, +1 modifier) | Normal |
| 56 | **Soul Artisan** | When assigned to Altar/Prison Cells, captive conversion success rate +20%, and converted minions retain original class skill level +1 | Expert |
| 61 | **Apothecary** | When assigned to Research Chamber, may craft 1 basic potion/turn (heal/poison/buff) | Enhanced |
| 62 | **Diviner** | When assigned to Scrying Post, may foresee next invasion wave's Tier and headcount (exact values) | Enhanced |
| 63 | **Negotiator** | When assigned to any facility, all trade prices −15% | Enhanced |
| 64 | **Diplomat** | When assigned to Throne Room, difficulty to ally with other dungeons −1 die, may take 1 free diplomatic action/turn | Expert |
| 65 | **Scholar** | When assigned to Research Chamber, research project time −1 turn (min 1), may run 3 projects simultaneously | Expert |
| 66 | **Hidden Talent** | **Reroll this table twice and gain two abilities** (reroll again on duplicates); elite/legendary monsters getting this result instead gain +1 extra ability | Special |

### 9.4 Ability Stacking Rules

- A single monster may have at most 2 management abilities (legendary/elite)
- Multiple monsters' same-named abilities in one facility do **not** stack (take highest value)
- Different-named abilities in the same facility **may** stack
- Mad Sorcerer's "Chaos Mutation" may grant monsters extra random abilities

### 9.5 Relationship Between Management Abilities and Skill Tree

- A monster's management abilities are independent of the Lord's skill tree
- Monster abilities provide **facility-level** bonuses (only take effect when assigned to a specific facility)
- Lord skills provide **global-level** bonuses (take effect whether or not monsters are assigned)
- The two may stack: Lord's "Master Builder" + monster's "Artisan" both lower build cost

---

## X. Captive Management System

(The core content of this section is consistent with the original, with only necessary attribute-name updates and streamlining.)

### 10.1 Captive Process Overview

```
Adventurer invasion → defeat in combat (HP zero ≠ death) → captive (needs Prison Cells) / escape / death
                    ↓
              ┌─────┴─────┐
        Interrogation/Intimidation  Appeasement  Torture
        (Dominion check)  (Dominion (DOM)  (Dominion (DOM)
              └─────┬─────┘
                    ↓
              Willpower to 0?
              ┌───┴───┐
          Willpower (WIL)>0     Willpower (WIL)=0
          Assign labor    →  Collapse/Numb/Convert
```

### 10.2 Captive Attributes

| Attribute | Meaning | Range | Note |
|------|------|------|------|
| **Willpower** (Willpower (WIL)) | Resistance will | 1–5 | Initial = 3 + Tier |
| **Class** (Class) | Adventurer class | Warrior/Mage/Thief/Cleric/Ranger | Determines labor bonus |
| **Profession Level** (PL) | Class skill level | 1–5 | = Adventurer Tier |
| **Stamina** (Stamina (STA)) | Physical condition | 1–5 | Drops to 0 = death |
| **Status** (Status) | Current psychological state | Defiant/Resigned/Broken/Converted | Changes with Willpower |

### 10.3 Labor Types and Efficiency

| Labor Type | Best Class | Output Formula | Stamina Cost | Risk |
|----------|---------|---------|---------|------|
| **Dig Expansion** | Warrior | Building Materials ×(Profession Level×0.5) rounded up/turn | 1/turn | Low |
| **Trap Crafting** | Thief | Traps (Industry check + Profession Level dice)/turn | 1/turn | Low |
| **Magic Research** | Mage | Mana Crystals ×(Profession Level×0.5)/turn | 1/turn | Medium |
| **Resource Production** | Any | Corresponding resource ×(Profession Level×0.5)/turn | 2/turn | Low |
| **Combat Fodder** | Warrior | Combat Power = Profession Level | 2/combat | Extreme |
| **Special Ritual** | Cleric | Ritual effect + Profession Level dice | 0 | High |

### 10.4 Willpower System

| WIL Value | Status | Behavior |
|-------|------|---------|
| 5 | Unyielding | Defiantly resists, attempts escape or sabotage every turn |
| 4 | Resisting | Refuses labor (efficiency −50%), high escape tendency |
| 3 | Wavering | Normal labor efficiency, moderate escape tendency |
| 2 | Submissive | Normal labor efficiency, low escape tendency |
| 1 | Edge of Collapse | Efficiency +50%, won't flee but may break |
| 0 | — | Roll to determine outcome (collapse/numb/convert) |

**Ways to Lower Willpower**:

| Method | Check | Effect | Risk |
|------|------|------|------|
| Interrogation | Dominion (DOM) vs Willpower (WIL) | Willpower (WIL) −1 (critical −2) | Failure: Willpower temporarily +1 |
| Torture | Dominion (DOM) (auto 2 successes base) | Willpower (WIL) −2, Stamina −1 | Death risk, other captives' Willpower +1 |
| Appeasement | Dominion (DOM) (difficulty +1) | Willpower (WIL) −1, conversion chance doubled | No penalty but slow |
| Isolation | No check | Willpower −1 every 2 turns | None |
| Brainwashing Ritual | Arcana (ARC) (needs Ritual Chamber Lv3) | Willpower directly zeroed | Failure = permanent madness |

---

## XI. Resources and Economy System

### 11.1 Four Core Resources

| Resource | Icon | Main Acquisition | Main Consumption |
|------|------|-------------|-------------|
| **Dark Coins** | ◆ | Mines, vault interest, adventurer drops, trade | Building, recruitment, upkeep |
| **Mana Crystals** | ◇ | Research Chamber, mana nodes, mage drops | Casting, rituals, magic traps, high-tier upkeep |
| **Building Materials** | ■ | Mines, captive digging, trade | Digging spaces, building/upgrading rooms, traps |
| **Soul Essence** | ● | Altar, adventurer death, sacrifice | Undead monsters, rituals, dark magic |

### 11.2 Per-Turn Resource Phase

Each management turn resolves in this order:

1. **Assignment Phase** ⭐: Decide each monster's post (management deployment vs combat defense)
2. **Income Phase**: All room output → monster management contribution → captive labor output → vault interest
3. **Upkeep Phase**: Monster upkeep → room upkeep → captive maintenance
4. **Action Phase**: Player uses action points for operations (dig/build/recruit/interrogate, etc.)
5. **Event Phase**: GM triggers random events → captive escape checks → monster loyalty checks
6. **Invasion Phase**: If invasion, enter combat
7. **Post-War Phase**: Settle loot/captives → dungeon attribute growth check

### 11.3 Adventurer Drop Table

| Adventurer Tier | Dark Coins | Mana Crystals | Magic Item Chance |
|------------|--------|---------|-------------|
| T1 | 1d3 | 0 | None |
| T2 | 1d6+2 | 1d3 | 5% common |
| T3 | 2d6+5 | 1d6+2 | 15% fine |
| T4 | 3d6+10 | 2d6+5 | 30% rare |
| T5 | 5d6+20 | 3d6+10 | 60% legendary |

---

## XII. Character Creation Process

### 12.1 Creation Step Overview

```
Step 1: Choose Dungeon Lord archetype (one of six)
  ↓
Step 2: Allocate Lord attribute points (12 points, range 1–4 initial)
  ↓
Step 3: Allocate skill points (6 points, into 20-skill universal tree)
  ↓
Step 4: Determine archetype core abilities (passive + active auto-gained)
  ↓
Step 5: Configure initial dungeon (Throne Room + 2 undeveloped small spaces + 3–5 basic monsters)
  ↓
Step 6: Name and backstory
  ↓
Step 7: Fill character sheet → ready!
```

### 12.2 Detailed Steps

#### Step 1: Choose Dungeon Lord Archetype

Choose one of the six archetypes (see Chapter Three) to set the play direction.

#### Step 2: Allocate Lord Attribute Points

- Gain **12 points** of attribute allocation
- All 5 attributes (Cunning (CUN) / Dominion (DOM) / Arcana (ARC) / Industry (IND) / Warfare (WAR)) start at 1
- Raising an attribute by 1 = spending 1 allocation point
- Initial single-attribute cap is 4 (archetype bonus may break through)
- Archetype's own attribute bonus stacks after allocation

#### Step 3: Allocate Skill Points

- Gain **6 points** of initial skill points
- Choose upgrades in the 20-skill universal tree (see Chapter Two)
- Lv0→Lv1: 1 point, Lv1→Lv2: 1 point, Lv2→Lv3: 2 points, Lv3→Lv4: 3 points
- Suggest investing skill points into the main-attribute skill tree related to the archetype's core play style

#### Step 4: Determine Archetype Core Abilities

- 1 passive ability (auto-gained)
- 1 active ability (auto-gained)
- Advanced abilities auto-unlock at Dungeon Level Lv3/6/9

#### Step 5: Configure Initial Dungeon

Gain initial configuration per archetype template, mark on the dungeon map:
- Throne Room Lv1 location (dungeon core)
- 2 undeveloped small-space locations (connecting to Throne Room)
- Initial monster deployment locations

#### Step 6: Name and Backstory

Fill in:
- **Dungeon Name**: _____________
- **Lord Title**: ______________
- **Dungeon Theme**: _____________
- **Core Motivation**: _____________
- **Dungeon Sigil**: _____________

#### Step 7: Fill Character Sheet

See Chapter Thirteen appendix.

---

## XIII. Appendix: Character Sheet Template (Revised)

```
╔══════════════════════════════════════════════════════════╗
║              DUNGEON LORD CHARACTER SHEET  v2.0          ║
╠══════════════════════════════════════════════════════════╣
║  Dungeon Name: __________________  Lord Title: ______________  ║
║  Archetype: ____________________  Dungeon Level: ___  Experience (EXP): ___/___ ║
║  Dungeon Theme: ____________________________________________  ║
║  Core Motivation: ____________________________________________  ║
╠══════════════════════════════════════════════════════════╣
║              LORD STATS       SKILL TREE  ║
║  ┌──────┬─────┬─────┬─────┬─────┬─────┐                ║
║  │ Attr │ Cunning (CUN) │ Dominion (DOM) │ Arcana (ARC) │ Industry (IND) │ Warfare (WAR) │                ║
║  │      │Cunning │Dominion │Arcana │Industry │Warfare │                ║
║  ├──────┼─────┼─────┼─────┼─────┼─────┤                ║
║  │ Value│     │     │     │     │     │                ║
║  │ Pool │ d6  │ d6  │ d6  │ d6  │ d6  │                ║
║  └──────┴─────┴─────┴─────┴─────┴─────┘                ║
║  Cunning (CUN): □Traps Lv_ □Espionage Lv_ □Stealth Lv_ □Toxicology Lv_              ║
║  Dominion (DOM): □Interrogation Lv_ □Leadership Lv_ □Diplomacy Lv_ □Discipline Lv_              ║
║  Arcana (ARC): □Mana Lv_ □Ritual Lv_ □Enchant Lv_ □Curse Lv_              ║
║  Industry (IND): □Build Lv_ □Resource Lv_ □Smith Lv_ □Engineer Lv_              ║
║  Warfare (WAR): □Tactics Lv_ □Fear Lv_ □Adapt Lv_ □WarCry Lv_              ║
║  Available Skill Points: ___                                       ║
╠══════════════════════════════════════════════════════════╣
║              DUNGEON STATS                      ║
║  ┌──────┬─────┬─────┬─────┬─────┬─────┐                ║
║  │ Attr │ Depth (DEP) │ Infamy (INF) │ Defense (DEF) │ Wealth (WLH) │ Magic (MAG) │                ║
║  │      │Depth │Infamy │Defense │Wealth │Magic │                ║
║  ├──────┼─────┼─────┼─────┼─────┼─────┤                ║
║  │ Value│  1  │  1  │  1  │  1  │  1  │                ║
║  └──────┴─────┴─────┴─────┴─────┴─────┘                ║
║  Actions/turn: 2  Room Cap: 3  Spaces: Throne Room + 2 small spaces   ║
╠══════════════════════════════════════════════════════════╣
║                    Archetype Abilities                                ║
║  Passive: ________________________________________________  ║
║  Active: ________________________________________________  ║
║  Advanced (Lv3/6/9): _______________________________________  ║
╠══════════════════════════════════════════════════════════╣
║             RESOURCES         ASSIGNMENT     ║
║  ◆Dark Coins: ____  ◇Mana Crystals: ____                        ║
║  ■Building Materials:   ____  ●Soul Essence: ____                        ║
║  ┌──────────┬────┬────┬────┬──────┐                    ║
║  │ Monster   │ Combat Power (CP) │ Management Value (MV) │Loyalty (LOY) │ Post │                    ║
║  ├──────────┼────┼────┼────┼──────┤                    ║
║  │          │    │    │    │Mgmt/Combat │                    ║
║  │          │    │    │    │Mgmt/Combat │                    ║
║  │          │    │    │    │Mgmt/Combat │                    ║
║  └──────────┴────┴────┴────┴──────┘                    ║
║  Total Mgmt Dice: ___  Total Combat Dice: ___             ║
╠══════════════════════════════════════════════════════════╣
║          ROOMS              PRISONERS           ║
║  ┌────────────┬────┬──────┐  ┌──────┬────┬───┬───┐    ║
║  │ Room       │Lvl │Space  │  │ Name │Willpower (WIL) │Cls │PL │    ║
║  ├────────────┼────┼──────┤  ├──────┼────┼───┼───┤    ║
║  │            │    │      │  │      │    │   │   │    ║
║  └────────────┴────┴──────┘  └──────┴────┴───┴───┘    ║
╠══════════════════════════════════════════════════════════╣
║              DUNGEON MAP (attach separately)                ║
║  Depth (DEP)1: [Throne Room]──[Small Space A:_____]──[Small Space B:_____]       ║
║  Depth (DEP)2: (to be dug)                                          ║
╠══════════════════════════════════════════════════════════╣
║                       NOTES                          ║
║                                                          ║
╚══════════════════════════════════════════════════════════╝
```

---

## Appendix A: Quick Reference Tables

### A.1 Action List (per turn)

| Action | Action Cost | Note |
|------|-----------|------|
| **Dig Space** | 2 | Industry check, space unlocked after success |
| Build Room | 2 (or 1) | Build within an unlocked space |
| Upgrade Room | 1 | Pay resources to upgrade |
| Recruit Monster | 1 | Recruit from unlocked monsters (with d66 management ability) |
| **Assign Monster Post** | 0 | Free action (must complete at turn start) |
| Interrogate Captive | 1 | Dominion (DOM) vs Willpower check |
| Torture Captive | 1 | Auto-lower Willpower but high risk |
| Appease Captive | 1 | Dominion (DOM) (difficulty +1) lower Willpower |
| Assign Captive Labor | 0 | Free action |
| Craft Trap | 1 | Industry check |
| Upgrade Dungeon Attribute | 2 | See section 4.4 |
| Research Project | 1+ | Arcana check |
| Hold Ritual | 1 | Arcana (ARC)/Dominion check |
| Deploy/Redeploy Monster | 0 | Free action (with limits) |
| **Emergency Redeployment** | 1 | Management-post monster into combat (MV zeroed that turn) |
| Trade | 1 | Trade with dark merchants |

### A.2 Check Difficulty Reference

| Difficulty | Successes Required | Example |
|------|-----------|------|
| Easy | 1 | Command skeleton, dig small space |
| Standard | 2 | Interrogate T2 captive, dig medium cave, build room |
| Hard | 3 | Turn a high-will captive, dig large crypt |
| Extreme | 4+ | Convert legendary adventurer, dig Abyssal Hall |

---

## Appendix B: Design Alignment Notes

### B.1 Alignment with Dice System Confirmed
- Lord attributes Cunning (CUN)/Dominion (DOM)/Arcana (ARC)/Industry (IND)/Warfare (WAR) (1–5) = base dice pool 1d6–5d6 ✓
- Dungeon attributes Depth (DEP)/Infamy (INF)/Defense (DEF)/Wealth (WLH)/Magic (MAG) (1–15) = non-pool protagonist attributes ✓
- Monster Combat Power (1–5/8) = combat dice pool ✓
- Monster Management Value (1–5) = management dice pool ✓
- Captive Willpower (1–5) = resistance dice pool ✓
- All checks follow: 0 successes = failure, 1 = partial success, 2+ = full success ✓

### B.2 Attribute Name Unification Confirmed
- Cunning (CUN)=Cunning, Dominion (DOM)=Dominion, Arcana (ARC)=Arcana, Industry (IND)=Industry, Warfare (WAR)=Warfare ✓
- Fully consistent with dice-mechanics ✓

### B.3 Archetype Ability + Skill Tree Dual-Track Confirmed
- 20-skill universal growth tree (4 skills per attribute, levels 0–4) ✓
- Archetype abilities (passive + active + advanced) layered on top of skill tree ✓
- The two coexist without conflict ✓

### B.4 New System Confirmed
- Territory Expansion System (dig → space level → discovery system) ✓
- Monster Assignment System (management deployment vs combat defense) ✓
- Random Monster Management Abilities (d66, 16 abilities, three strength tiers) ✓

### B.5 Initial Configuration Reduction Confirmed
- All archetypes initial: Throne Room (free) + 2 undeveloped small spaces + 3–5 basic monsters ✓
- Compared to v1.0, initial resources greatly reduced ✓

---

*This document is the v2.0 cross-review revised edition of the "Character System + Dungeon Management" portion of the Dungeon Lord TRPG rules system. All values are fully aligned with the dice system (dice-mechanics).*
