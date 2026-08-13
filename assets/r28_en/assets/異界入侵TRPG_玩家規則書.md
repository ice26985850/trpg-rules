# Otherworld Invasion TRPG — Player Rulebook v2.0

> **Version:** v2.0 (Class System Update)
> **Design Focus:** Modern Urban × Otherworld Invasion × Physical Law Conflict × Personal Growth × Class System

---

# Chapter One: Core Rules

## 1.1 Dice System

This game uses **d100 Percentile Dice**.

| Mode | Formula | Scenario |
|------|---------|----------|
| Roll-Low-to-Succeed | d100 ≤ target % | Attack hit |
| Roll-High-to-Succeed | d100 + modifier ≥ Difficulty Class (DC) | Skill check, attribute check |

## 1.2 Six Core Attributes

| Attribute | Abbr | Primary Influence |
|-----------|------|-------------------|
| Strength (STR) | Physical Attack, carry weight |
| Dexterity (DEX) | Initiative, Dodge Rate, Critical Rate |
| Constitution (CON) | Hit Points (HP) max, physical damage reduction |
| Intelligence (INT) | Magic Attack, hacking/decryption |
| Wisdom (WIS) | Hit Rate, detection/recon |
| Spirit (SPI) | Mana Points (MP) max, mental resistance |

**Stepwise cost:** below 10 = 1 pt, 11-20 = 1 pt, 21-40 = 2 pts, 41-60 = 3 pts, 61-80 = 4 pts, 81-100 = 5 pts, 101+ = 6 pts.

> Attribute base value is 10. At creation, 30 attribute points are freely allocated. When attribute points are insufficient, multi-tier jumps are allowed (e.g., jumping from 10 directly to 40 costs 10×1 + 10×2 = 30 points).

## 1.3 Derived Attributes

| Attribute | Abbr | Formula |
|-----------|------|---------|
| Hit Points (HP) | Constitution (CON) × 10 + Character Level × 5 |
| Mana Points (MP) | Spirit (SPI) × 5 + Character Level × 3 |
| Physical Attack (PATK) | Strength (STR) × 2 + weapon bonus |
| Magic Attack (MATK) | Intelligence (INT) × 2 + weapon bonus |
| Physical Defense (PDEF) | Constitution (CON) × 1.5 + armor bonus |
| Magic Defense (MDEF) | Spirit (SPI) × 1.5 + armor bonus |
| Hit Rate (HIT%) | 50% + Wisdom (WIS) × 3% (cap 95%) |
| Dodge Rate (DGE%) | 10% + Dexterity (DEX) × 2% (cap 60%) |
| Critical Rate (CRT%) | 5% + Dexterity (DEX) × 1% |

> **Skill Damage**: A skill's final damage depends on the stack of the character's Attack and Class Level:
> **Skill Final Damage = (Attack + Skill Base Power) × (1 + Class Level ÷ 20)**
> Physical skills use Physical Attack (PATK); magic skills use Magic Attack (MATK).

## 1.4 Attack Resolution

1. Calculate **Effective Hit Rate (EHit%)** = Hit Rate (HIT%) − target's Dodge Rate (DGE%) (min 5%, max 95%)
2. Roll d100
3. Judgment: 1-5 = Critical Success (guaranteed hit + crit + extra effect), 96-100 = Critical Failure (guaranteed miss + negative consequence), 6-95 = d100 ≤ Effective Hit Rate (EHit%) → hit (if ≤ Critical Rate (CRT%) → crit)
4. Damage = max(Attack − Defense, 1); crit ×1.5 (Critical Success ×2.0)
5. If a skill attack: Final Damage = max((Attack + Skill Base Power) × (1 + Class Level ÷ 20) − target's corresponding Defense, 1)

## 1.5 Skill Checks

> d100 + (Attribute + passive bonus) ≥ Difficulty Class (DC)

| Difficulty Class (DC) | Difficulty | Difficulty Class (DC) | Difficulty |
|-----------------------|-----------|-----------------------|-----------|
| 20 | Simple | 80 | Hard |
| 40 | Normal | 100 | Very Hard |
| 60 | Moderate | 120+ | Epic |

## 1.6 Advantage / Disadvantage

Roll 2d100; take the lower on attack, the higher on check (Advantage); reverse (Disadvantage). Multiple instances do not stack.

---

# Chapter Two: Character Creation

## 2.1 Creation Steps

| Step | Content |
|------|---------|
| 1. Background | Choose a modern background (see §2.2) → gain attribute bonuses and background traits |
| 2. Awakening Scene | Roll or choose (see §2.3) |
| 3. Attribute Allocation | Base 10, 30 attribute points freely allocated (stepwise cost) |
| 4. Derived Attributes | Calculate Hit Points (HP) / Mana Points (MP) / Physical Attack (PATK) / Magic Attack (MATK) / Physical Defense (PDEF) / Magic Defense (MDEF) / Hit Rate (HIT%) / Dodge Rate (DGE%) / Critical Rate (CRT%) |
| 5. **Choose Main Class** | Pick 1 of 8 Combat Classes → gain Lv.1 skill (choose 2) + trait |
| 6. **Choose Sub-Class** | Pick 1 of 8 Life Classes → gain Apprentice trait (may choose 0; not mandatory) |
| 7. Awakening Skill | Roll 1d20 to draw (Artist may reroll) |
| 8. Starting Gear | Guild Issue E-tier set + 50 Gold (G) stipend |
| 9. Motivation | Why fight? |

## 2.2 Pre-Awakening Backgrounds (12)

| d12 | Background | Attribute Bonus | Trait |
|-----|-----------|----------------|-------|
| 1 | Office Worker | Spirit (SPI)+1, Wisdom (WIS)+1 | Wage-Slave Grit: first 3 mental-resistance checks per day +1 |
| 2 | College Student | Intelligence (INT)+1, Spirit (SPI)+1 | Academic Training: Intelligence (INT) non-combat checks +1 |
| 3 | Medical Staff | Intelligence (INT)+1, Wisdom (WIS)+1 | First-Aid Training: healing effect +10% |
| 4 | Military/Police | Strength (STR)+1, Constitution (CON)+1 | Basic Combat Training: extra Green · Uncommon weapon |
| 5 | Delivery Worker | Dexterity (DEX)+1, Constitution (CON)+1 | City Runner: non-combat move speed +10% |
| 6 | Engineer | Intelligence (INT)+2 | Logical Thinking: hack/analyze/repair +2 |
| 7 | Athlete | Strength (STR)+1, Dexterity (DEX)+1 | Competitive Fitness: climb/run/swim +1 |
| 8 | Unemployed | Spirit (SPI)+2 | Survival Instinct: when Hit Points (HP) < 50%, all attributes +1 |
| 9 | Freelancer | Wisdom (WIS)+1, Dexterity (DEX)+1 | Save 5 attribute points every 10 levels |
| 10 | Farmer/Fisher | Constitution (CON)+2 | Carry weight +20%, physical damage reduction +1 |
| 11 | Artist | Spirit (SPI)+1, Intelligence (INT)+1 | Reroll Awakening Skill once |
| 12 | High Schooler | Dexterity (DEX)+1, Spirit (SPI)+1 | First 5 levels: +1 skill point per level |

## 2.3 Awakening Scene (d6+d6)

| d6 | Trigger | d6 | Detail |
|----|---------|----|--------|
| 1 | A Rift opens beside you | 1-6 | Commute / home / workplace / mall / hospital / school |
| 2 | Gravely wounded by monster, near death | 1-3 first encounter; 4-6 protecting someone |
| 3 | Witness someone killed | 1-3 stranger; 4-6 someone you know |
| 4 | Awaken inside an Erosion Zone | 1-3 active rescue; 4-6 wandered in |
| 5 | Contact with otherworld item | 1-3 picked up a stone; 4-6 discovered by the Guild |
| 6 | Unknown cause | The System activates on its own |

## 2.4 Level & Dual EXP

### Character Level

| Level Range | Title |
|-------------|-------|
| Lv.1-10 | E-Rank Awakener |
| Lv.11-25 | D-Rank Awakener |
| Lv.26-45 | C-Rank Awakener |
| Lv.46-70 | B-Rank Awakener |
| Lv.71-100 | A-Rank Awakener |
| Lv.101+ | S-Rank Awakener |

Each Character level-up grants: **5 attribute points**.

Character Experience Points (EXP) sources: slaying monsters, completing quests, closing Rifts (see GM book).

Character EXP table: 1→2=100, 2→3=250, 3→4=450, 4→5=700, 5→10 +300 per level, 11→20 +500 per level, 21→40 +800 per level, 41→70 +1200 per level, 71→100 +2000 per level, 101+ +3000 per level.

### Class EXP

Class EXP is independent of Character EXP. Gains:
- Fighting as that class: monster EXP × 0.8
- Using that class's skill: monster EXP × 0.3 (additional)
- Life-class production (per successful craft): Forging: 50 + (target Difficulty Class (DC) − check result) × 2 (cap 200); Alchemy: 40 + rarity tier × 20; Cooking: 30 + ingredient rarity × 15

**Total cap: sum of all Class Levels ≤ Character Level.** (Deity classes do not count.)

| Category | Cap | Nodes |
|----------|:---:|:-----:|
| Main Class (Combat) | 50 | 9 |
| Sub-Class (Life) | 15 | 4 |
| Deity Class | — | 1 |

Class EXP table: 1→2=200, 2→3=500, 3→4=900, 4→5=1400, 5→6=2000, 6→7=2700, 7→8=3500, 8→9=4500, 9→10=5600, 10→11=6800, 11→12=8200, 12→13=9800, 13→14=11600, 14→15=13600, 15→20 +2000 per level, 20→30 +3000 per level, 30→40 +5000 per level, 40→50 +8000 per level.

---

# Chapter Three: Main Classes (Combat Classes)

## 3.1 General Rules

- Skills no longer have Lv.1-10. **You either know it or you don't.**
- Skill Damage = **(Attack + Skill Base Power) × (1 + that Class Level ÷ 20)**; physical skills use Physical Attack (PATK), magic skills use Magic Attack (MATK).
- Skill unlock nodes: Lv.1 (2 skills + trait), Lv.3, Lv.6, Lv.10 (trait evolution), Lv.15 (branch choice), Lv.20, Lv.30 (trait evolution), Lv.40 (Master skill), Lv.50 (Ultimate trait)
- Skills are independent across classes — a Vanguard cannot use a Warlock's skills (unless you also trained Warlock)

## 3.2 Combat Class Overview

| Class | Attributes | Role |
|-------|------------|------|
| MC1 Vanguard | Strength (STR)/Constitution (CON) | Melee tank, frontline pressure |
| MC2 Assaulter | Dexterity (DEX)/Strength (STR) | High-mobility melee, skirmisher |
| MC3 Sniper | Wisdom (WIS)/Dexterity (DEX) | Ranged physical, point elimination |
| MC4 Warlock | Intelligence (INT)/Spirit (SPI) | Magic DPS, AoE pressure |
| MC5 Guardian | Constitution (CON)/Spirit (SPI) | Defense tank, ally protection |
| MC6 Shadowrunner | Dexterity (DEX)/Intelligence (INT) | Stealth assassination, infiltration |
| MC7 Combat Medic | Wisdom (WIS)/Spirit (SPI) | Healing support, sustain |
| MC8 Berserker | Strength (STR)/Constitution (CON) | High-risk high-reward melee |

## 3.3 Class Skill Trees (Quick Reference)

> Full skill descriptions in `catalogs/戰鬥職業技能圖鑑.md`; this is the quick-reference version.

### MC1 Vanguard

| Lv | Unlock |
|----|--------|
| 1 | Heavy Strike (Base Power 40, MP8, Cooldown 2) + Iron Wall (MP15, Physical Defense (PDEF)+8) + Trait: Iron Wall Break (counterattack when hit, 3×/encounter) |
| 3 | Whirlwind Slash (Base Power 25, MP12, Cooldown 3, sweeping slash + Bleed) |
| 6 | Unshakeable Toughness (when Hit Points (HP) <40%, Physical Defense (PDEF)+15) |
| 10 | Trait upgrade: +2 counterattacks |
| 15 | Branch A Bastion (Iron Will) / B Breaker (Charge Strike, Base Power 50) |
| 20 | War Cry (AoE: ally damage +10%, MP18) |
| 30 | Bastion: Immovable (Physical Defense (PDEF)+25, heal). Breaker: first charge hit ×1.8 |
| 40 | Bastion: Steel Great Wall (AoE enemies forced to target you, damage reduction 15%). Breaker: Earthrend Strike (line 2 zones, Physical Attack (PATK)×2.5, knock down, 1×/encounter) |
| 50 | Bastion: Unfallen (HP to 0 → 1 Hit Points (HP)+30% Hit Points (HP), 1×/encounter). Breaker: Unbreakable (vs structures/cores ×2.0) |

### MC2 Assaulter

| Lv | Unlock |
|----|--------|
| 1 | Lethal Thrust (Base 30, MP10, Critical Rate (CRT%)+15%) + Flash Step (MP10, Dodge Rate (DGE%)+10% for 1 turn) + Trait: Lethal Rhythm (combo +8%/stack, cap 3) |
| 3 | Double Strike (Base 20, MP8, two-hit → extra basic attack) |
| 6 | Nimble Footwork (DGE+5%, after dodge Dexterity (DEX)+3) |
| 10 | Lethal Rhythm cap 5 stacks, +10%/stack |
| 15 | Branch A Sword Dancer (Afterimage Step) / B Executioner (Weak Point Lock: when Hit Points (HP)<40%, Critical Rate (CRT%)+20%) |
| 20 | Shadow Pursuit (teleport 3 zones + attack, Base 35, MP12) |
| 30 | Sword Dancer: counterattack after dodge. Executioner: Hit Points (HP)<30% → Lethal Rhythm instantly maxed |
| 40 | Sword Dancer: Thousand-Blade Dance (4-hit, Base 15×4). Executioner: Death Sentence (mark Hit Points (HP)<30%, kill restores 50% Hit Points (HP)) |
| 50 | Sword Dancer: reset Thousand-Blade cooldown once. Executioner: Hit Points (HP)<10% ×2.0 damage, Death Sentence restores 50% Mana Points (MP) |

### MC3 Sniper

| Lv | Unlock |
|----|--------|
| 1 | Precision Shot (Base 35, MP8, Hit Rate (HIT%)+10%) + Marked Shot (MP5, ally Hit Rate (HIT%)+10%) + Trait: Eagle Eye Lock (aim → next turn Hit Rate (HIT%)+25%, ignore cover) |
| 3 | Rapid Fire (Base 15×3, MP12) |
| 6 | Steady Shot (immobile +15%) |
| 10 | Eagle Eye Lock → Swift Action |
| 15 | Branch A Deadeye (crit damage ×2.0) / B Ranger (can shoot after moving) |
| 20 | Burst Shot (Base 45, MP18, flame splash) |
| 30 | Deadeye: Eagle Eye + Critical Rate (CRT%) 25%. Ranger: Hit Rate (HIT%)+15% after moving |
| 40 | Deadeye: Arrow from a Thousand Leagues (Base 80, guaranteed hit & crit, 1×/encounter). Ranger: Barrage Suppression (2-zone all, 1×/encounter) |
| 50 | Deadeye: full-HP first hit ×1.5. Ranger: extra action on first turn |

### MC4 Warlock

| Lv | Unlock |
|----|--------|
| 1 | Mana Bolt (Base 30, MP6, no Cooldown) + Mana Shield (MP15, temp Hit Points (HP) = Spirit (SPI)×3) + Trait: Mana Resonance (after 3 spells → next spell free Mana Points (MP)) |
| 3 | Element Arrow (Base 25, MP8, fire/ice/lightning selectable + element effect) |
| 6 | Mana Affinity (MP max +15%, recover 15% Mana Points (MP) after battle) |
| 10 | Mana Resonance trigger → 2 spells |
| 15 | Branch A Elementalist (chosen element damage +25% + resistance 0.5) / B Hexer (Magic Defense (MDEF)-8, stackable 3 layers) |
| 20 | Element Burst (Base 35, MP25, 2-zone AoE, composite elements) |
| 30 | Elementalist: consecutive same element +10%/stack. Hexer: curse-kill jumps to nearby enemy |
| 40 | Elementalist: Element Storm (Base 60, three elements, 2 zones, 1×/encounter). Hexer: Ultimate Curse (all Disadvantage +3%/turn HP loss, 3 turns, unpurifiable) |
| 50 | Elementalist: Element Avatar (choose form in combat, immune to that element, weakness +50%). Hexer: 5 curse stacks, double Ultimate Curse |

### MC5 Guardian

| Lv | Unlock |
|----|--------|
| 1 | Guardian Oath (MP12, 50% of ally damage redirected to you) + Holy Bastion (MP18, Physical Defense (PDEF)+10, Magic Defense (MDEF)+8) + Trait: Unshakeable Shield (take full damage for ally, 1×/encounter) |
| 3 | Shield Bash (Base 20, MP6, on hit → target Hit Rate (HIT%)-15%) |
| 6 | Iron Body (Physical Defense (PDEF)+8, HP max +10%) |
| 10 | Unshakeable Shield 2×/encounter |
| 15 | Branch A Holy Shield Guard (AoE shared 50%) / B Vengeance Guard (reflect 30%) |
| 20 | Taunt (MP10, AoE enemies forced to attack you, Difficulty Class (DC) 60 SPI resist) |
| 30 | Holy Shield Guard: Physical Defense (PDEF)+5/layer. Vengeance Guard: damage taken → next hit +15%/layer |
| 40 | Holy Shield Guard: Holy Fortress (AoE damage reduction 30% + abnormal immunity, 3 turns, 1×/encounter). Vengeance Guard: Sacrifice Strike (accumulated damage ×1.5 counter, 1×/encounter) |
| 50 | Holy Shield Guard: Undying (to 0 → Holy Fortress + restore 40% Hit Points (HP), 1×/encounter). Vengeance Guard: Sacrifice kill → reset + ×2.0 |

### MC6 Shadowrunner

| Lv | Unlock |
|----|--------|
| 1 | Stealth (MP8, invisible 2 turns) + Assassinate (Base 35, MP10, ×1.5 while invisible) + Trait: Assassination Mark (first invisible hit ×2.0, stacks with Assassinate = ×3.0) |
| 3 | Smoke Bomb (MP10, AoE Hit Rate (HIT%)-20%, self invisible) |
| 6 | Shadow Stride (non-combat stealth Advantage, silent) |
| 10 | Assassination Mark 2×/encounter (different targets) |
| 15 | Branch A Shadow Blade (re-stealth after kill, 2×/encounter) / B Infiltrator (non-combat stealth auto-success below Difficulty Class (DC) 80) |
| 20 | Shadow Bind (MP12, single target Difficulty Class (DC) 60 DEX Paralysis, 2 turns) |
| 30 | Shadow Blade: full-HP Assassinate ×1.3 (total ×3.9). Infiltrator: hack/picklock Advantage, Difficulty Class (DC)-15 |
| 40 | Shadow Blade: Shadow Clone (HP 30%, damage 60%, 3 turns, 1×/encounter). Infiltrator: Lethal Poison (Difficulty Class (DC) 70 CON Poison, apply 3×/encounter) |
| 50 | Shadow Blade: Assassination Mark unlimited uses. Infiltrator: Perfect Infiltration (mimic appearance, 1×/day for 1 hour) |

### MC7 Combat Medic

| Lv | Unlock |
|----|--------|
| 1 | First Aid (MP10, restore Spirit (SPI)×2 Hit Points (HP)) + Healing Shot (Base 15, MP6, no Cooldown, damages enemies / heals allies) + Trait: Battle First-Aid (Swift restore Spirit (SPI)×2 Hit Points (HP), 2×/encounter) |
| 3 | Disinfection Spray (MP15, AoE remove Poison/Bleed/Burn/Curse) |
| 6 | Medic's Intuition (sense ally Hit Points (HP) within 30m) |
| 10 | Battle First-Aid → Spirit (SPI)×3 Hit Points (HP), 3×/encounter |
| 15 | Branch A Surgeon (healing +30% + remove negative) / B Field Pharmacist (heal → empower Attack (ATK)+15%) |
| 20 | Life Link (MP25, ally shares 50% of your healing) |
| 30 | Surgeon: dying-state healing +50%. Field Pharmacist: dual effect Attack (ATK)+15% + Defense (DEF)+10% |
| 40 | Surgeon: Revival (ranged Swift, Dying → 40% Hit Points (HP), 1×/encounter). Field Pharmacist: Adrenaline (all attributes +30% + extra action, 2 turns → Paralysis 1 turn) |
| 50 | Surgeon: Revival 2×/encounter. Field Pharmacist: Adrenaline no side effect, can target two |

### MC8 Berserker

| Lv | Unlock |
|----|--------|
| 1 | Berserk Slash (Base 45, MP0, self-damage 5) + Blood Sacrifice (MP0, consume 15% Hit Points (HP), +25% damage for 2 turns) + Trait: Blood Fury (every 10% HP lost → +6% damage, cap +48%) |
| 3 | Whirlwind Axe (Base 30, MP0, sweeping slash, self-damage 8) |
| 6 | Pain Numbness (Hit Points (HP)<50% → +15% damage, negative duration -1 turn) |
| 10 | Blood Fury +8% per tier, Hit Points (HP)<20% adds Bleed |
| 15 | Branch A Blood Axe (kill restores 15% Hit Points (HP)) / B War Howler (War Howl: consume 10% Hit Points (HP), AoE damage +20%, 2 turns) |
| 20 | Death Grip (Base 60, MP0, kill → heal, no kill → self-damage 15) |
| 30 | Blood Axe: Hit Points (HP)<30% → damage ×1.5. War Howler: War Howl stacks +5%/layer |
| 40 | Blood Axe: Blood-soaked Demon God (Hit Points (HP)<20% → damage ×2.0, Physical Defense (PDEF)-50%, delay lethal damage, 1×/encounter). War Howler: Doom War Cry (consume 30% Hit Points (HP), all enemies Hit Rate (HIT%)-30%, Dodge Rate (DGE%)-20%) |
| 50 | Blood Axe: Blood-soaked Demon God kill restores 25% Hit Points (HP). War Howler: after Doom, a kill → whole party attributes +20% |

---

# Chapter Four: Sub-Classes (Life Classes)

| Class | Lv.1 Apprentice Trait | Lv.5 Professional Skill | Lv.10 Expert Trait | Lv.15 Master Skill |
|-------|-----------------------|-------------------------|--------------------|--------------------|
| SC1 Blacksmith | Artisan's Craft: +1 bonus to equipment crafting | Material Appraisal: appraise otherworld metal quality | Rune Forging: attach random attribute | Masterwork: bonus ×1.5 equipment |
| SC2 Alchemist | Double Mix: 30% chance double potion | Bomb Mixing: craft explosives | Panacea: reverse potion effect | Philosopher's Stone (Fake): full party restore |
| SC3 Explorer | Otherworld Sense: detect hidden supplies/traps | Ruin Knowledge: identify ancient runes | Ruin Resonance: sense crystals within 100m | Treasure Digger: hidden chest +1 tier |
| SC4 Tracker | Hunter's Mark: +20 Perception after tracking | Wilderness Survival: food/water | Track Reading: judge creature/time | Hunter's Intuition: +10% damage to tracked monsters |
| SC5 Negotiator | Silver Tongue: 15% discount + negotiation Advantage | Intelligence Gathering: collect local intel | Network: one informant NPC per city | Diplomatic Immunity: friendly factions exempt |
| SC6 Cook | Monster Cuisine: +15% single-attribute Buff | Ingredient Foraging: always gather ingredients | Dual Buff: stack two dishes | Legendary Recipe: all attributes +10% or single +30% |
| SC7 Analyst | Tactical Analysis: sense 1 enemy weakness at combat start | Damage Assessment: view Hit Points (HP)/Mana Points (MP) | Real-Time Analysis: +next skill | Tactical Master: all enemy weaknesses + perfect counter |
| SC8 Merchant | Passive Income: 5 Gold (G)/day per level | Market Contract: unlock local specialty | Cross-World Logistics: income ×3 | Commercial Empire: income ×5 + trading company |

---

# Chapter Five: Awakening Skills

Awakening Skills are unique talent abilities of every Awakener. At creation, roll 1d20 to randomly gain 1 (Artist background may reroll once).

| d20 | Skill Name | Base Effect (summary) |
|:---:|-----------|-----------------------|
| 1 | Battle Frenzy | After attacking the same target 3 turns in a row, damage +30% |
| 2 | Cheat Death | When Hit Points (HP) reaches 0, forcibly retain 1 Hit Points (HP) (1×/encounter) |
| 3 | Mana Reflux | On killing an enemy, restore 15% max Mana Points (MP) |
| 4 | Shadow Step | After a successful dodge, next attack is guaranteed crit |
| 5 | Soul Sense | Sense position and level of monsters within 30m radius |
| 6 | Unshakeable | When Hit Points (HP) < 30%, all attributes +15% |
| 7 | Time Sense | Once per encounter, foresee one enemy's next action intent |
| 8 | Weapon Resonance | After 5 consecutive turns with same weapon, damage +15% |
| 9 | Life Leech (passive) | Each time you deal damage, 5% of damage dealt converts to Hit Points (HP) restore |
| 10 | Counter Stance | After taking a hit, counter with a basic attack (1×/encounter) |
| 11 | Lone Wolf | When solo, all attributes +10%, damage +15% |
| 12 | Monster Hunter | +15% damage to monster types you've already killed |
| 13 | Rampage | Activate: 3 turns Physical Attack (PATK) +30%, Physical Defense (PDEF) −20% |
| 14 | Elemental Adaptation | After taking elemental damage, resistance to that element +5% (cap 30%) |
| 15 | Equipment Master | Can equip two accessories of same slot, carry weight +30% |
| 16 | Healing Aura | At end of each turn, self-heal Spirit (SPI) × 0.3 Hit Points (HP) |
| 17 | Doppelganger | Create a clone (Hit Points (HP)=20%, damage=50%), 3 turns |
| 18 | Skill Mimic | Once per encounter, mimic the skill the target used last turn |
| 19 | Gravity Control | Enemies in range: Dodge Rate (DGE%) −15%, move speed −30%, 2 turns |
| 20 | Die of Fate | Once per encounter, reroll any one of your own checks |

> Each Awakening Skill has three evolutions (Base → Evolution I → Evolution II); evolution conditions and full effects in `catalogs/覺醒技能圖鑑.md`.

### Awakening Skill Rules

- When gaining a Deity Special Class, the Awakening Skill is replaced by a deity-granted trait. Restored after losing the deity's favor.
- Evolution is announced by the GM when conditions are met; irreversible.

---

# Chapter Six: Equipment & Economy

## 6.1 Rarity System

A piece of equipment = **one base type + one rarity tier**. The same "longsword" can exist at every rarity from White · Common to Red · Mythic:

| Tier | Color | Weapon Bonus | Armor Bonus | # Effects | Source |
|:----:|-------|:------------:|:-----------:|:---------:|--------|
| E | White · Common | +1~+3 | +1~+4 | 0 | Guild Issue, E-Rank Rift |
| D | Green · Uncommon | +3~+7 | +3~+8 | 0-1 | D-Rank Rift, forging |
| C | Blue · Rare | +6~+15 | +6~+15 | 1 | C-Rank Rift, requires Otherworld Crystal |
| B | Purple · Unique | +12~+25 | +10~+22 | 1-2 | B-Rank Boss drop |
| A | Orange · Legendary | +20~+40 | +18~+35 | 2-3 | A-Rank Boss, world-class quest |
| S | Red · Mythic | +35~+60 | +30~+50 | 3-5 | Chief-God Projection, divine-forged |

> Purple tier and above equipment gains a unique name, but the underlying base type remains.

## 6.2 Equipment Slots

| Slot | Influence |
|------|-----------|
| Weapon | Physical Attack (PATK) or Magic Attack (MATK) bonus, effects |
| Body | Physical Defense (PDEF), Magic Defense (MDEF), Hit Points (HP) bonus, effects |
| Feet | Move speed, Dexterity (DEX), Dodge Rate (DGE%) |
| Accessory | Minor attribute bonus, special effects |

## 6.3 Starting Gear (Guild Issue)

| Slot | Name | Effect |
|------|------|--------|
| Weapon | Guild-issue Tactical Knife (White · Common) | Physical Attack (PATK) +2 |
| Weapon (optional) | Guild-issue Hand Crossbow (White · Common) | Physical Attack (PATK) +2, range 30m, 20 bolts |
| Body | Guild-issue Protective Vest (White · Common) | Physical Defense (PDEF) +3 |
| Feet | Guild-issue Tactical Boots (White · Common) | Move speed +5%, Dexterity (DEX) +1 |

## 6.4 Equipment Crate

Equipment typically drops as an "Equipment Crate"; opening yields a random piece of the corresponding rarity. The GM may let players roll to determine slot and specific item.

## 6.5 Gold & Consumables

| Item | Price | Effect |
|------|:-----:|--------|
| Lesser Healing Potion | 15 Gold (G) | Restore 50 Hit Points (HP) |
| Common Healing Potion | 50 Gold (G) | Restore 150 Hit Points (HP) |
| Greater Healing Potion | 150 Gold (G) | Restore 400 Hit Points (HP) |
| Supreme Healing Potion | 500 Gold (G) | Restore 1,000 Hit Points (HP) |
| Lesser Mana Potion | 20 Gold (G) | Restore 30 Mana Points (MP) |
| Common Mana Potion | 60 Gold (G) | Restore 100 Mana Points (MP) |
| Greater Mana Potion | 200 Gold (G) | Restore 300 Mana Points (MP) |
| Antidote | 25 Gold (G) | Remove Poison |

> **Potion use limit**: In each battle, each character may use at most **3 potions** (healing and mana combined). This limit resets after a Short Rest.

> Full equipment list and alchemy/cooking consumables in `catalogs/裝備與物品圖鑑.md`.

---

# Chapter Seven: Combat Rules (Player View)

## 7.1 Combat Framework

- **Turn-Based**: ~6 sec/turn. Initiative = Dexterity (DEX) + d20, higher goes first, order fixed.
- **Action Economy**: each turn you may perform:
  - 1 Standard Action (attack, use skill, throw bomb, use item)
  - 1 Move Action (move to adjacent zone)
  - 1 Swift Action (switch weapon, simple interact, battle first-aid, etc.)
  - 1 Reaction Action (opportunity attack, etc., triggered on others' turns)
- Actions may be traded down: Standard → Move → Swift.

## 7.2 Zone-Based Map

| Distance Tier | Zone Gap | Description |
|---------------|:------:|-------------|
| Same Zone | 0 | Same room, melee can attack |
| Near | 1 | Adjacent room, requires 1 Move action |
| Mid | 2-3 | Requires Dash (Standard+Move) |
| Far | 4-5 | Requires multiple turns of movement or ranged weapon |
| Extreme | 6+ | Edge of sight, only Snipers can attack |

**Move options**: Normal move 1 zone (1 Move action) / Dash 2 zones (Standard+Move) / Careful move 1 zone (no opportunity attack triggered).

## 7.3 Attack Resolution

1. Calculate Effective Hit Rate (EHit%) = Hit Rate (HIT%) − target's Dodge Rate (DGE%) (min 5%, max 95%)
2. Roll d100
3. Judgment: 1-5 = Critical Success (guaranteed hit + crit), 96-100 = Critical Failure (guaranteed miss), 6-95 compared with Effective Hit Rate (EHit%)
4. On hit: if d100 ≤ Critical Rate (CRT%) → crit (damage ×1.5, Critical Success ×2.0)
5. Resolve: Damage = max(Attack (ATK) − target's Defense (DEF), 1). Skill Damage = max((Attack + Base Power) × (1+Class Level÷20) − target's corresponding Defense, 1)

## 7.4 Status Effects (common for players)

| Status | Effect | Typical Source |
|--------|--------|----------------|
| Stun | Skip next turn | Heavy Strike, Shield Bash |
| Bleed | Each turn lose Physical Attack (PATK) × 0.2 × stacks Hit Points (HP) | Whirlwind Slash, Blood Fury |
| Burn | Each turn lose 5 × stacks Mana Points (MP) | Burst Shot, Element Burst (fire) |
| Freeze | Cannot move, Physical Defense (PDEF) +30% | Element Burst (frost) |
| Paralysis | 25% chance action fails | Element Burst (lightning), Shadow Bind |
| Poison | Each turn lose 3 × stacks Hit Points (HP) | Poison fog, poison-type attack |
| Buff | Attack +30% | War Cry, buff potion |
| Shield | Gain temp Hit Points (HP) = Spirit (SPI) × 3 | Mana Shield |

## 7.5 Hit Points to Zero

When Hit Points (HP) ≤ 0, enter **Dying State**:
1. Cannot act
2. At end of each turn make a Constitution (CON) check (d100 + Constitution (CON) ≥ Difficulty Class (DC) 60): succeed 3 times → stabilized (Hit Points (HP)=1, cannot continue fighting); fail 3 times → death
3. Critical Success (1-5): stabilize immediately. Critical Failure (96-100): counts as two failures
4. Each time attacked counts as one failure
5. Ally using First Aid (Difficulty Class (DC) 60) can stabilize immediately

### Death

After a character dies, they may be revived by:
- Lilith's sacrificial revival (deity-granted skill, requires Life Weaver deity class)
- Legendary revival item (GM discretion, extremely rare)
- Story revival under special conditions in some scenarios

Death penalty (GM's choice): lose one piece of equipment / permanently lose 5 attribute points / Character Level −1.

## 7.6 Rest

- **Short Rest** (10 min): use potions to recover, quickly refresh passives.
- **Long Rest** (8 hrs): Hit Points (HP)/Mana Points (MP) fully recovered, daily-use counts reset.

---

# Chapter Eight: Solo Mode

| Adjustment | Rule |
|------------|------|
| Enemy count | −50% |
| Enemy Hit Points (HP) | −20% |
| Boss Hit Points (HP) | −25% |
| Boss damage | −15% |
| Experience Points (EXP) | ×1.3 |
| Non-combat Difficulty Class (DC) | −10 |
| Post-battle recovery | 30% Hit Points (HP)/Mana Points (MP) |

---

# Appendix: Term Reference

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
| Critical Rate (CRT%) | Experience Points (EXP) |  |  |
| Effective Hit Rate | Effective Hit Rate (EHit%) | Gold | Gold (G) |
