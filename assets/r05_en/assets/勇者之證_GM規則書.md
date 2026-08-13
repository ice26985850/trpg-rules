# The Hero's Proof — GM Rulebook

> This book = the complete contents of the Player Rulebook + the GM-exclusive chapters. The GM only needs to read this single volume to run the game.
> All numerical values are subject to the finalized System Draft as adjudicated by the GM.

---

# ▍Player Rules (Complete Reprint)

## Chapter One　Core Rules

### 1.1 Dice System and Check Formula

This game uses a **d20 single die**. All non-combat checks follow the same form:

```
d20 + Attribute Modifier (M) + Proficiency (Prof) + status bonus  ≥  Difficulty Class (DC)
```

- **Natural 1 is an automatic failure**: rolling a 1 is an immediate failure (bonuses ignored).
- **Natural 20 is an automatic success**: rolling a 20 is an immediate success (bonuses ignored).
- The total success rate is strictly bounded between **5% and 95%**.

**Hit Check** (only one side rolls in combat; no opposed roll):

```
d20 + Hit Bonus (Hit)  ≥  Evasion (EVA)
Evasion (EVA) = 10 + Dexterity Modifier (M_DEX) + equipment modifier + skill modifier + floor(Class Level (ClassLv) / 3)
```

### 1.2 Difficulty Class (DC) Ladder

| Difficulty | Difficulty Class (DC) |
|---|---|
| Very Easy | 5 |
| Easy | 8 |
| Normal | 12 |
| Hard | 16 |
| Very Hard | 20 |
| Legendary | 24 |
| Mythic | 28 |

### 1.3 Six Attributes and Attribute Modifier (M)

Six Attributes: **Strength (STR)**, **Constitution (CON)**, **Dexterity (DEX)**, **Magic (MAG)** can grow during adventures; **Charisma (CHA)**, **Luck (LUK)** are locked after character creation and no longer grow.

Attribute Modifier `M = floor((attribute − 10) / 2)`, with a hard attribute cap of 22 (corresponding to a max M of +6).

| Attribute | 8 | 9 | 10 | 11 | 12 | 13 | 14 | 15 | 16 | 17 | 18 | 19 | 20 | 21 | 22 |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| M | −1 | −1 | 0 | 0 | +1 | +1 | +2 | +2 | +3 | +3 | +4 | +4 | +5 | +5 | +6 |

**Character Creation**: the six attributes start at 8, with a point pool of 25; cost rate: 8→10 costs 1 point / 11→13 costs 2 points / 14→15 costs 3 points; single-attribute cap at creation is 15.
**Growth**: each Character Level (CL) gained grants 1 attribute point (cap 99). Cost rate: 8–15 costs 1 point per +1 / 16–19 costs 2 points per +1 / 20–22 costs 3 points per +1.

**Proficiency (Prof)** increases with Character Level: +1 (CL1) / +2 (CL11) / +3 (CL21).

### 1.4 Check Bonus System

The cap on stacked bonuses for a single check is **+5** (the sum of M, Prof, status, equipment, and skill modifiers). Permanent bonuses purchased with Skill Points (SP):

| Bonus | Equivalent Multiplier | Skill Point (SP) Cost |
|---|---|---|
| +1 | 0.083 | 3 |
| +2 | 0.167 | 6 |
| +3 | 0.250 | 10 |
| +4 | 0.333 | 14 |
| +5 | 0.417 | 19 |

### 1.5 Action Point (AP) and Mana Point (MP)

- **Action Point (AP) Cap** = `2 + floor(DEX / 4)` (DEX 8~22 → AP 4~7), refreshed at the start of each turn.
- **Mana Point (MP) Cap** = `10 + MAG×2 + class bonus`:

| Class | Mana Point (MP) Class Bonus |
|---|---|
| Warrior | +0 |
| Monk | +8 |
| Mage | +20 |
| Cleric | +12 |
| Thief | +4 |
| Hunter | +6 |
| Dancer | +15 |

- **Health (HP) Cap** = `class base Health + (class Health growth + Constitution Modifier (M_CON)) × (CL − 1)`.

| Class | Base Health | Health Growth | Health (HP) (CL1) | Health (HP) (CL50, M_CON+3) | Health (HP) (CL99, M_CON+6) |
|---|---|---|---|---|---|
| Warrior | 60 | 4 | 60 | 403 | 1040 |
| Monk | 58 | 4 | 58 | 401 | 1038 |
| Hunter | 50 | 3 | 50 | 344 | 932 |
| Cleric | 48 | 3 | 48 | 342 | 930 |
| Thief | 45 | 3 | 45 | 339 | 927 |
| Dancer | 38 | 2 | 38 | 283 | 822 |
| Mage | 35 | 2 | 35 | 280 | 819 |

### 1.6 Three-track Progression

- **Character Level (CL) / Class Level (ClassLv) / Skill Level (SkillLv) are three independent tracks**: the three tracks **do not share** experience sources — Character Level (CL) accumulates Experience (EXP); Class Level (ClassLv) accumulates a **separate class experience pool, Class Experience (CEXP)** (not the CL's EXP); Skill Level (SkillLv) is raised only by Skill Points (SP). The three tracks have different thresholds (see 1.7) and level up separately at different times.
  - Character Level (CL): upon reaching the threshold to level up, gain 1 attribute point + 1 Skill Point (SP), cap 99.
  - Class Level (ClassLv): upon reaching the threshold to level up, unlocks class skill growth; ClassLv 10/20/30/40 are the **four-stage** promotion nodes (see Chapter Three and the Skill Compendium, "Four-stage Three-path Promotion (ClassLv 11–40)"), cap 40.
- **Skill Level (SkillLv)**: raised **only** by Skill Points (SP) (1~5), completely independent of Experience (EXP). The only sources of Skill Points (SP) are Character Level (CL) gains and the starting points at character creation (see 1.6 sources).

**Skill Multiplier (locked)** `f(n) = 1 + n(n−1)/8` → Lv1~5 = **1.00 / 1.25 / 1.75 / 2.50 / 3.50**.
**Skill Point Cost** `C(n) = 4 + n(n−1)/2` → Lv1~5 cumulative 4/5/7/10/14, **max-level total cost 14 Skill Points (SP)**.

- **Skill Point (SP) Sources (locked)**: 8 SP at character creation; +1 per level starting from Character Level (CL) 1 → `cumulativeSP(CL) = 7 + CL`, at Character Level (CL) 99 cumulative **106 Skill Points (SP)**.
- **Single-axis Principle**: choose one between multiplier growth and range/turn-count growth. Percentage / probability / turn-count / count-type effects must not be multiplied by f(n); use explicit listings instead.

### 1.7 Experience (EXP) Curve

- Character Level (CL) per-level requirement: `floor(50 + 20×CL + 2×CL²)`.
- Class Experience (CEXP) cumulative (separate pool exclusive to Class Level ClassLv): `floor(160 × k²)` (k = 1~40, where ClassLv = k).
- Monster Experience (EXP): `floor(15 × CR × (1 + CR/15))`; Boss Experience (EXP) ×4.
- Quest Experience (EXP) ≈ recommended Character Level (CL) per-level requirement ×3.

> **Three-track Note**: the "Character Level (CL) per-level requirement" uses Experience (EXP); the "Class Level (ClassLv) cumulative" uses the **separate class experience pool, Class Experience (CEXP)** — the two have different sources and are not shared; Skill Level (SkillLv) is raised only by Skill Points (SP), unrelated to either EXP or CEXP.

### 1.8 Contested Check

When two sides directly contend (shoving, grappling, snatching, willpower contests, escaping bonds, etc.), each side rolls and compares totals (d20 + Attribute Modifier (M) + Proficiency (Prof) + status bonus; higher total wins; bonuses still subject to the +5 cap from 1.4). Natural 20 wins unconditionally, natural 1 loses unconditionally; ties favor the defender (optional rule: re-roll). See Player Book 1.8 and worked examples. Monsters have no six attributes / M / Prof; in contested checks, use Attack Bonus (ATK) in place of M, with Prof=0 (or the GM may grant an equivalent M baseline by rounding `floor(CR/5)`).

### 1.9 Aid / Teamwork Check

A character spends 1 Action Point (AP) to provide a +2 aid bonus to an ally's same check; at most 1 aid per check, and the aider must have the relevant Proficiency (Prof) or Attribute Modifier (M); the aid bonus comes from an external source and does not count toward the recipient's +5 cap. See Player Book 1.9.

### 1.10 Worked Examples (Lockpicking / Hits)

Player Book 1.10 and 7.10 provide step-by-step worked calculations for skill checks and "CL5 Warrior vs CR5 Goblin" hit/damage, which the GM may quote directly for teaching.

## Chapter Two　Background Origin (6 Options)

Each option grants a **+1 Attribute Modifier** and **1 utility trait** (permanently active, not frozen by promotion).

1. **Warrior Family**: Strength (STR)+1; **Battlefield Etiquette** (combat first round, whole party Hit Bonus (Hit)+1).
2. **Woodland**: Constitution (CON)+1; **Wild Path Familiarity** (terrain movement without slowdown, jungle/mountain reconnaissance +2, once per day trap immunity).
3. **Townsfolk**: Dexterity (DEX)+1; **Market Craft** (10% trade discount, disassembling gear recovers 50% materials, disguise +2).
4. **Temple**: Charisma (CHA)+1; **Divine Prayer Blessing** (once per day free Purify-level removal of 1 abnormal status, friendly with temples).
5. **Scholar**: Magic (MAG)+1; **Erudite Memory** (appraisal/knowledge +2, scroll use without mishap).
6. **Wanderer**: Luck (LUK)+1; **Wanderer's Trail** (once per day re-roll 1d20 in encounter battles, +1 extra carry slot).

## Chapter Three　Classes

Seven classes; each class's Class Level (ClassLv) 1–10 base skill tree contains **4 Active + 2 Passive = 6 skills**; **Four-stage Three-path Promotion** (11–20 second stage / 21–30 third stage / 31–40 fourth stage ultimate, 3 paths per base class). Universal formula for skill damage / healing / shield:

```
Base Value (B) × f(Skill Level) × (1 + relevant Attribute Modifier (M) / 6)
```

Active multiplier skills cost Skill Points (SP) = C(n) (max 14); utility skills are fixed at 1 level, cost 2 Skill Points (SP), and may not carry numerical bonuses.

### 3.1 Warrior

**Requirement** Strength≥13, Constitution≥12 | **Guardian Deity** Galder Iron-oath | **Positioning** Front Row

- **Shield Bash** (Active) AP1 MP0 B=1.2 Physical; Stun 1 turn (chance 20%+5%(n−1)); Cooldown: once per short rest.
- **Iron Wall Stance** (Active) AP2 MP0; Damage Reduction 20%+4%(n−1) (cap 44%), lasts until start of next turn, Cooldown 2.
- **Whirlwind Slash** (Active) AP3 MP4 B=1.0 Physical AOE (Area Effect) 1 ring around; Cooldown 3.
- **Armor-breaking Strike** (Active) AP2 MP3 B=1.6 Physical; Sunder (Damage Reduction (DR) −25%, 2 turns); Cooldown 3.
- **Iron Will** (Passive): per Class Level (ClassLv), all abnormal-status resistance +1%; total abnormal-status resistance capped at 75%.
- **Steadfast Wall** (Passive): when equipped with a shield, per Class Level (ClassLv) Block value +1.2 (converted to Evasion (EVA)); critical hit damage taken −10%.
- **Second / Third / Fourth Stage (3 paths per base class)**:
- Guardian (Defense Master / Living Bastion): ultimate Damage Reduction iron wall, an immovable shield wall for the team.
- Berserker (Rage Lord / War God): grows fiercer the longer the fight, sacrificing defense for devastating output.
- Spellsword (Magic-blade Sovereign / Holy-demon Sword Saint): master of both magic and blade, a magic blade that sunder enemy lines in an instant.

### 3.2 Monk

**Requirement** Dexterity≥13, Constitution≥11 | **Guardian Deity** Sattō the Formless | **Positioning** Front Row

- **Chain Palm** (Active) AP2 MP2; multi-hit, each hit B=0.5, number of hits 2+floor((n−1)/2).
- **Ki-burst Punch** (Active) AP3 MP5 B=2.2 Physical; Knockback.
- **Afterimage Step** (Utility) AP1 MP3; this turn Evasion (EVA)+30% and may move through enemies; Cooldown 2.
- **Breaking Fist** (Active) AP2 MP4 B=1.8 Physical; Sunder + next turn +0.3 multiplier charge; Cooldown 3.
- **Martial Arts Mastery** (Passive): unarmed/fist weapons gain +2.0% damage per Skill Level (SkillLv).
- **Gale Body** (Passive): per Class Level (ClassLv), Evasion (EVA) +0.2; cap +floor(Class Level (ClassLv)/5); DEX≥14 grants an extra +1 Action Point (AP) (fixed).
- **Second / Third / Fourth Stage (3 paths per base class)**:
- Chi-master (Fist Sage / Mountain-crusher Venerable): internal energy projected outward, released in a burst that pierces the enemy line.
- Shadowblade (Shadow-fist Sect / Formless Sword Saint): high-speed multi-hit, afterimages darting to instantly slay the target.
- Grappler (Dragon-lock Sect / Demon-subduing Venerable): grapple and pressure points, hard control that breaks defense and pins down formidable foes.

### 3.3 Mage

**Requirement** Magic≥13 | **Guardian Deity** Ruri Star-chant | **Positioning** Back Row

- **Fireball** (Active) AP2 MP6 B=2.0 Fire; range medium (5 cells); Burn (2 turns, 0.3×MAG fire damage per turn).
- **Frost Nova** (Active) AP3 MP8 B=1.2 Frost AOE (Area Effect) radius 2; Chill (DEX−30%, 2 turns); Cooldown 3.
- **Lightning Chain** (Active) AP2 MP7 B=0.9 Lightning; jumps to 3+floor((n−1)/3) targets; range long (8 cells).
- **Mana Surge** (Utility) AP1 MP0 (recovery); recover Mana Point (MP) = 8+2(n−1); Cooldown 4.
- **Spell Specialization** (Passive): per Skill Level (SkillLv), spell multiplier +1.5%.
- **Elemental Resonance** (Passive): against Burning/Chilled targets, same-element damage +1.0% × Skill Level (SkillLv).
- **Second / Third / Fourth Stage (3 paths per base class)**:
- Pyromancer (Inferno Sovereign / Sky-burning Dragon): fire and thunder incineration, an AOE slaughter at the battlefield's core.
- Cryomancer (Eternal-frost Sage / Aurora Oracle): freezing time and space, controlling the field and locking down the enemy with slows.
- Necromancer (Corpse-art Lord / Stygian Death-master): curse and lifesteal, summoning undead to fight alongside and sustain.

### 3.4 Cleric

**Requirement** Magic≥12, Constitution≥10 | **Guardian Deity** Sephi Mercy-light | **Positioning** Back Row

- **Healing Light** (Active) AP2 MP6; healing B=2.0 ×(1+M_MAG/6); range medium (5 cells).
- **Group Prayer** (Active) AP3 MP10; healing AOE (Area Effect) B=1.0 ×(1+M_MAG/6); Cooldown 3.
- **Warding Aegis** (Active) AP2 MP5; Shield B=1.5 ×(1+M_MAG/6), lasts 3 turns.
- **Purify** (Utility) AP1 MP4; removes 1~2 abnormal statuses; Cooldown 2.
- **Merciful-light Blessing** (Passive): per Skill Level (SkillLv), healing amount +1.8%.
- **Aegis Sustain** (Passive): aegis duration +1 turn per 3 Skill Levels (SkillLv); the healed target gains Evasion (EVA) +1.0 × Skill Level (SkillLv).
- **Second / Third / Fourth Stage (3 paths per base class)**:
- Healer (Life Prophet / Eternal-radiance Shepherd): sustained healing, the wellspring of the team's endurance.
- Inquisitor (Divine-punishment Executor / Sacred-verdict Revelation): holy burning, the judge brings down heavenly punishment.
- Paladin (Verdict Guard / Holy-radiance War-sovereign): shield and holy ward, guarding allies from the Front Row in a holy war.

### 3.5 Thief

**Requirement** Dexterity≥13, Luck≥10 | **Guardian Deity** Night-sparrow Shadow-seam | **Positioning** Flexible

- **Backstab** (Active) AP2 MP2 B=2.0 Physical; when attacking from the side/back, Critical Threshold (CritTh) drops to guaranteed crit; Bleed.
- **Smoke Bomb** (Utility) AP1 MP3; AOE (Area Effect) radius 1, enemies' Evasion (EVA) −20%, self Stealth 1 turn; Cooldown 3.
- **Deadly Venom Blade** (Active) AP2 MP4 B=1.0 Physical + Poison (0.5×DEX per turn, 3 turns).
- **Shadow Clone** (Active) AP3 MP6; summons a clone to assist, +1 attack count, 1 turn; Cooldown 4.
- **Critical Strike** (Passive): per Skill Level (SkillLv), critical hit damage +2.0%.
- **Lucky Thief** (Passive): per Class Level (ClassLv), drop rate and pickpocket success rate +1.0%.
- **Second / Third / Fourth Stage (3 paths per base class)**:
- Assassin (Ending Assassin / Netherworld Death-god): backstab kill, stealing the enemy's head from the shadows in an instant.
- Trapper (Mechanism Grandmaster / Thousand-device Artisan): battlefield control through setups, chained traps that entrap and slaughter groups of foes.
- Twin-blade (Shadow-blade Sect / Thousand-blade Death-god): twin-blade combos, multi-hit crits that instantly sever vital points.

### 3.6 Hunter

**Requirement** Dexterity≥12, Strength≥10 | **Guardian Deity** Pale-wolf Wind-fade | **Positioning** Back Row

- **Precise Shot** (Active) AP2 MP3 B=2.2 Physical; range long (8 cells).
- **Pinning Shot** (Active) AP1 MP2 B=1.0 Physical; Immobilize (movement forbidden, 1 turn); range long (8 cells).
- **Explosive Trap** (Utility) AP2 MP4 B=1.5 Physical; placed on ground, triggers AOE (Area Effect); Knockback; lasts 3 turns.
- **Hawkeye Mark** (Utility) AP1 MP2; Mark: allies' damage against it +10%~+20% (by level), its Critical Threshold (CritTh) −5; Cooldown 2.
- **Beast Instinct** (Passive): per Skill Level (SkillLv), ranged damage +1.8%.
- **Trap Master** (Passive): trap damage +2.0% × Skill Level (SkillLv) and +1 trap deployed per 3 Class Levels (ClassLv).
- **Second / Third / Fourth Stage (3 paths per base class)**:
- Sharpshooter (Star-piercing Ranger / Azure-sky Hawkeye): long-range sniping, a single arrow piercing the vital point for a fatal blow.
- Beastmaster (Lord of Hundred Beasts / King of Ten-thousand Beasts): summons a beast pack, coordinating a pincer to dominate the battlefield.
- Skirmisher (Gale Outrider / Azure-wind Wandering Spirit): mobile displacement, kiting with hit-and-run shots.

### 3.7 Dancer

**Requirement** Charisma≥13, Dexterity≥10 | **Guardian Deity** Ayane Rainbow-echo | **Positioning** Flexible (usually Back Row)

- **Battle Cheer** (Active) AP2 MP4; whole party attack +8%~+15% (by level) and Hit Bonus (Hit)+2; lasts 3 turns; Cooldown 3.
- **Rainbow Waltz** (Active) AP3 MP6; whole party Evasion (EVA)+15% and +1 Action Point (AP) next turn; lasts 2 turns; Cooldown 4.
- **Requiem** (Active) AP2 MP5; sustained healing 0.5×CHA per turn (3 turns); Cooldown 4.
- **Morale Command** (Utility) AP1 MP3; removes Fear; target Critical Threshold (CritTh) −3 (2 turns); Cooldown 2.
- **Stage Charisma** (Passive): per Skill Level (SkillLv), buff effects +2.0%.
- **Harmonic Resonance** (Passive): for each buffed ally in the party, the Dancer's own Evasion (EVA) +1.0.
- **Second / Third / Fourth Stage (3 paths per base class)**:
- War-dancer (Storm Dancer / War-song Goddess): war-song buffs, inspiring the whole party's offense and defense into a raging storm.
- Illusion-dancer (Dream-fantasy Phantom / Illusion-music Demon Queen): illusion control, bewildering foes in dreams to break their fighting spirit.
- Warding-dancer (Mercy-shield Dancer / Eternal-ward Dance-god): Guard Aura, a waltzing shield that protects the whole party.

## Chapter Four　Equipment and Items

For specific entries (weapons, armor, accessories, consumables, magical equipment), consult **`圖鑑/物品圖鑑.md`**; this book only explains the system rules:

- **Class Restriction + Level Requirement (ReqLv)**: failing the requirement imposes a penalty of Hit Bonus (Hit) −2 and effects −10%.
- The **Basic Shop** sells only basic gear and basic consumables (low-grade healing/mana potions + basic food); magical equipment and mid-to-high-grade consumables are obtained via crafting (Life Skills) or drops.
- **Durability**: weapons 40 (heavy 60) / armor 50 (heavy armor 80) / accessories 60; on a hit, Hit −1, Crit −2; at 0 it becomes unusable; repair cost = price × 5% × (max − current)/max; broken-and-reforged costs ×2.
- **Currency**: Gold (G); subsidiary coins Silver (0.1G) / Copper (0.01G).
- **Pricing**: basic equipment price = base price ×(1+0.15×(ReqLv−1)); rarity multiplier Common×1 / Fine×3 / Rare×8 / Epic×20 / Legendary×35; equipment base price = `floor(20 × CL^1.3)`. Consumables: base price ×(1+0.10×(recommended level−1)).
- **Resurrection Fee**: the first time is free (at a temple in the same city); the nth time (n≥2) = `100 × 2^(n−1)` G; at wilderness locations a +50% surcharge applies.
- **Life Skills (no life class)**: divided into "gathering type (raw material acquisition)" and "crafting type (finished product conversion)" layers, neither occupying Skill Points (SP); gathering (Mining / Logging / Herbalism / Fishing & Hunting / Farming) yields raw materials, crafting (Alchemy / Cooking / Smithing) takes raw materials × template to produce finished goods; adopts "material-attribute driven" crafting (see Player Book Chapter Four and `圖鑑/材料圖鑑.md`).
- **Shop Basic-principle (extended to potions/food)**: shops sell only basic equipment + low-grade healing/mana potions + basic food; all other consumables and cooked dishes must be self-crafted or dropped.

### 4.1 Gathering Life Skills (Raw Material Acquisition)

> The gathering type obtains raw materials and produces no finished goods, kept separate from the "crafting type (Alchemy / Cooking / Smithing)"; it occupies no Skill Points (SP) and has no life class. Farms / laboratories / kitchens / forges are mentioned only as "base facilities"; the details of site management are not expanded here. Check: `d20 + relevant Attribute Modifier (M) + Proficiency (Prof) + life-skill proficiency ≥ DC`; DC has five tiers (Common 12 / Fine 16 / Rare 20 / Epic 24 / Legendary 28), dangerous terrain +2~+4, symmetric with the DC reduction from facilities.

| Gathering Skill | Check Attribute | Time | Terrain / Node | Output (see `圖鑑/材料圖鑑.md`) |
|---|---|---|---|---|
| Mining | Strength (STR) / Constitution (CON) | immediate on exploration | ore veins / rock formations (D3~D8) | raw ore → metal ingots, accessory materials |
| Logging | Strength (STR) / Constitution (CON) | immediate on exploration | woodland (D3 / D8) | wood |
| Herbalism (wild) | Dexterity (DEX) / Constitution (CON) | immediate on exploration | herb nodes (D3 / D6 / D7 / D8) | wild herbs |
| Fishing & Hunting | Dexterity (DEX) / Constitution (CON) | immediate on exploration | waters / hunting grounds (D3~D8) | ingredients, hides |
| Farming | Constitution (CON) | immediate on sowing; harvest 3–14 days | base facility "Farm" | cultivated herbs / crops |

Failed wild gathering → empty-handed or reduced yield (rare-and-above yields −50%), no loss to already-held items; failed Farming → that season's yield −50%. The original "Planting" has been split into "Farming + the four wild gathering skills".

### 4.2 Crafting Type Operation Rules

| Crafting Skill | DC | Time Required | Facility | Output | Failure Consequence |
|---|---|---|---|---|---|
| Alchemy | Common 12 / Fine 16 / Rare 20 / Epic 24 / Legendary 28 | several hours | laboratory | potions / bombs / scrolls | material loss (Common/Fine 50%, Rare-and-above 75%) |
| Cooking | Common 12 / Fine 16 / Rare 20 / Epic 24 / Legendary 28 | 1–3 actions | kitchen | dishes | "dark cuisine" (effect halved) |
| Smithing | see 4.3 | several hours ~ several days | forge | equipment | see 4.3 |

Facilities are graded 1–3 (each grade DC −2); per 5 proficiency points DC −1; proficiency occupies no SP. Material-driven replaces recipe-binding (see Player Book 4.3).

### 4.3 Crafting / Manufacturing System (Material-attribute Driven)

Choose 1 item template + main material (+0~2 sub-materials); the finished product's values are determined by the material fields; basic gear is made directly with no requirement (DC 12), while rarities above that follow the product's rarity (Common 12 / Fine 16 / Rare 20 / Epic 24 / Legendary 28). Check: `d20 + relevant Attribute Modifier (M) + Proficiency (Prof) + life-skill proficiency ≥ DC`. On failure: Common/Fine lose 50% of materials, Rare-and-above lose 75%. Finished products are obtained via shop basics (base models) / self-crafting / monster drops / temple-guild exchange; mid-to-high-grade potions, bombs, scrolls, and buff dishes are not on shop shelves.

### 4.4 Gold Sinks (Gold Sink, executed by GM)

To avoid gold inflation and the imbalance of "only grinding, never spending," the GM should consistently collect the following three gold sinks during play; the rates are hard rules:

- **Equipment Repair Fee (short-rest settlement)**: each time a short rest ends in a town/base, charge by each item's durability loss; the formula matches the durability rule in Chapter Four: **repair cost = price × 5% × (max durability − current durability) / max durability**; durability at 0 (broken-and-reforged) costs ×2. Example: a basic weapon priced 100G with durability 40 and 10 lost → 100×5%×10/40 = 1.25G.
- **Guild Tax (commission settlement)**: when settling a commission's reward, the GM deducts **5%** as guild tax before paying out; **actual G received = commission catalog listed G × 0.95 (round down, floor)**. This tax does not affect EXP / IP.
- **Fast Travel Fee (departure settlement)**: charged by the GM at departure based on travel distance:

  | Travel Range | Rate (G) |
  |---|---|
  | Within same town | Free |
  | Cross-town (same region) | 10 |
  | Cross-region (e.g., Forest ↔ Volcano ↔ Ice Plains) | 30 |
  | Cross-continent / expedition (e.g., Demon Realm, beyond the world) | 50 |

> The above three are the primary gold sinks; together with the Resurrection Fee (Chapter Four), equipment purchases, and temple donations they form the gold expenditure structure. Alchemy products (potions / bombs / scrolls) cannot be resold for cash, so they generate no farming income (see Item Compendium Chapter Five).

## Chapter Five　Character Creation (5 Steps)

1. **Concept and Background Origin**: decide the character concept, choose 1 of 6 origins (gaining +1 attribute and 1 utility trait).
2. **Distribute Six Attributes**: point pool 25, six attributes start at 8, single-attribute cap 15; apply origin +1 (cap 16). Confirm the preselected class requirement is met. Note: Charisma (CHA) / Luck (LUK) lock after creation; Strength (STR) / Constitution (CON) / Dexterity (DEX) / Magic (MAG) can grow to the hard cap 22.
3. **Choose Class and Guardian Deity**: pick one of seven classes (must meet requirement), record the Guardian Deity. Calculate HP_max / MP_max.
4. **Allocate Skill Points (SP) and Equipment**: start with 8 SP to learn skills (refer to each class's skill tree and C(n), total SP 106); visit the Basic Shop to buy basic equipment.
5. **Positioning Confirmation**: with the GM, confirm Front Row / Back Row / Flexible positioning for solo / multiplayer mode, and complete the character sheet signing. **GM Obligation**: before step 5, the GM must show the player the "Solo Suitability Table" and verbally explain positioning differences (Warrior / Monk / Thief ◎; Hunter / Mage ○; Cleric △; Dancer ✕).

## Chapter Six　Leveling and Growth Rules

- **Character Level (CL)**: defeat monsters / complete quests to gain Experience (EXP), accumulated into the Character Level (CL) progress bar (**not** written to ClassLv synchronously — Class Level is tracked separately via Class Experience (CEXP), see 1.6 / 1.7). Upon reaching the threshold to level up, Character Level (CL) → gain 1 attribute point + 1 Skill Point (SP) (cumulative Skill Points (SP) = 7 + CL).
- **Class Level (ClassLv)**: accumulates the **separate class experience pool, Class Experience (CEXP)** (separated from CL's EXP, not the same pool); each level gained unlocks class skill growth; ClassLv 10/20/30/40 are the four-stage promotion nodes, cap 40.
- **Skill Level (SkillLv)**: raised by Skill Points (SP) (1~5); multiplier f(n) and cost C(n) are in 1.6, unrelated to Experience (EXP).
- **Promotion (Single-class Four-stage Promotion, not multiclass)**: this game **has no multiclass / multiple classes**. What is called "promotion" is **in-class rank advancement** — at Class Level (ClassLv) 10, choose one of the class's 3 second-stage paths (one of three, irreversible; unlocks CL11), at 21 enter that branch's third-stage mastery, at 31 enter the fourth-stage ultimate (CL31–40); the entire process stays within the same class; no re-meeting of requirements, no skill-unfreeze mechanic. The high-tier skill tree is in the Skill Compendium, "Four-stage Three-path Promotion (ClassLv 11–40)".

## Chapter Seven　Combat Basics (Player Perspective)

### 7.1 Initiative and Turn Structure

- **Initiative** = Dexterity Modifier + d20 (individual order; rolled once at combat start and reused thereafter).
- **Turn Structure**: Start (AP refresh + DoT / Regen settlement + skip on hard control) → Action (spending Action Points (AP)) → End.

### 7.2 Action Point (AP) Economy

| Action | Action Point (AP) | Description |

|---|---|---|
| Normal Attack | 1 | Can trigger a Critical Hit |
| Move | 1 | Move "Movement" squares |
| Active Skill | 1–3 | Varies by Skill Level and power; consumes Mana Point (MP) |
| Defensive Stance | 1 | This turn Damage Reduction +20% (multiplicative) |
| Use Item | 1 | Consumable |
| Grant AP | 1 | **Dancer-line exclusive**; grants one ally +1 Action Point (AP) immediately |
| Reaction | 0 | Once per turn; triggers on enemy turn |
| Free Action | 0 | Granted by specific class features |

> Grant AP exclusive: only the Dancer line may perform it; **incoming Action Point (AP) cap +1 / recipient / per turn.**

### 7.3 Hit and Damage Formulas
- Normal Attack damage = `Weapon Damage Range + corresponding Attribute Modifier (M).`
- Skill damage = `Base Value (B) × f(Skill Level) × (1 + Attribute Modifier (M) / 6).`
- **Multiplicative Damage Reduction and total DR Cap**: `Final Damage = Raw Damage × (1−r₁) × (1−r₂) × …`; **total Damage Reduction (DR) may not exceed 60%** (capped after summing all sources: body / shield / aura / status; shares the same constant as the "DR Cap" in Chapter 4 of the Player Book). Head / hand / foot gear DR exceeding the [body armor's base DR value] is invalid (still bound by the 60% total cap).
- **Attack Skill Cooldown and per-turn limit**: the same attack skill is limited to 1 use per turn; attack skills marked "Cooldown: None" or unmarked are treated as "1 use per short rest" (or the GM may require an additional +1 Action Point (AP) / +Mana Point (MP) cost to allow per-turn use); pure control / utility skills are exempt.
- Damage types: Physical (Pierce / Slash / Bludgeon), Elemental (Fire / Frost / Lightning / Acid), Mystic (Holy / Shadow / Psychic); Resistance ×0.5 / Weakness ×1.5 / Immunity ×0, applied after Damage Reduction.
- **Damage over Time (DoT) correspondence**: Poison → Mystic (Shadow), Burn → Elemental (Fire), Bleed → Physical (Pierce); same Resistance ×0.5 / Weakness ×1.5 / Immunity ×0 apply.

### 7.4 Critical Hits (Threshold System)
- Critical Hit occurs: `natural d20 ≥ Critical Threshold (CritTh)` **and** a hit; no extra roll.
- **The Critical Threshold is set by the attacker**: base 20+ (5%); can be lowered via "Luck reduces threshold by 1 per 3 points" and skills / gear, with a base floor of 14+ (35%). Luck (LUK) can push it below 14 via the 9.4 formula; crit rate beyond the 35% baseline converts to Critical Hit damage per 9.3 "overflow-to-crit-damage" — the two are two halves of the same rule and do not conflict.
- **No hard cap**: crit rate can be stacked beyond 100%; for each 5% of crit rate overflow, Critical Hit damage +7.5% (ratio 1:1.5).
- **Default Critical Hit multiplier ×2.0** (balance knob 1.5~2.0).

### 7.5 Front and Back Row Positioning
- Back Row takes −15% melee attack damage (unsteady footing); ranged protection (enemy melee must pass the Front Row first); Charge (Move + Normal Attack, costs Action Point (AP); +50% Charge damage, can crit); Swap (1 AP).
- **Area Effect (AOE)** affects both Front and Back Rows.

### 7.6 Unified Status Effects Table (with DoT Base Values)

The table below consolidates all statuses. DoT lists the base "start-of-turn damage" value (individual skills may amplify the multiplier); Hard Control is fixed at 1 turn.

| Status | Category | Duration | Per-turn effect | Save DC possible? | Notes |
|---|---|---|---|---|---|
| Stun / Bind / Paralyze / Freeze | Hard Control | 1 | Action phase skipped (melee attacks against a Frozen target count as automatic crits) | No | Charm (Illusion-dance) by level [1,1,2,2,3] |
| Fear | Soft Control | 2 | Cannot take voluntary actions (may Defend); −20% when attacking targets other than itself | Yes, Will save DC14 | Dragon General's flying strike, Death Knight's fear aura; Morale Command can remove it |
| Slow / Chill | Soft Control | 2 | Action Point (AP) −1 / Dexterity (DEX) −30% | No | — |
| Weak | Soft Control | 2 | Output −25% | No | — |
| Immobilize | Soft Control | 1 | Movement prohibited | No | Pinning Shot |
| Shock | Soft Control | 1 | Spellcasting 50% failure or Action Point (AP) −1 | No | — |
| Sunder | Debuff | 2 | Damage Reduction (DR) −25% (multiplicative with other DR sources); does not affect healing | No (refreshes duration) | Warrior · Armor-breaking Strike / Spellsword · Armor-rending Slash |
| Curse | Debuff | 3 | Lasts 3 turns; healing received −30%, Vulnerable +15% (takes +15% damage from all sources); can stack 2 layers (each layer counts down independently); with [Bleed] healing debuff, take the stricter value (−50%) | Will save DC14 (success prevents application); removed by Purify | Necromancer · Curse-kill |
| Lifesteal | Buff (self) | 1 (may be 2) | Each time damage is dealt during the duration, recover X% of that damage as Health (HP); X=20% (Stage 2) / 28% (Stage 3) / 35% (Stage 4); total lifesteal (including passive bonuses such as Pact of Darkness +10%, Corpse-lord Might +15%) capped at 35%, passives count toward the same cap; only applies to damage from the source itself, AOE resolved separately per target | — (attached to attack action / brief self-buff) | Necromancer · Touch of Lifesteal |
| Grapple (= Immobilize) | Hard Control (physical immobilization) | Until escaped or 2 turns (whichever first) | Cannot move / be displaced (Immobilize); at the start of each turn the victim may attempt a "Strength contest" to escape: DC=10+Caster M(STR); size ≥ Large DC+3; successful escape removes it | Strength contest (DC=10+Caster M_STR, +3 for Large); removed by Purify; caster may release voluntarily | Grappler · Dragon-grab Hand |
| MultiHit | Mechanic (multi-hit) | Within the action | Multiple resolution within a single attack action: number of hits = 2+floor((Skill Level−1)/3), each hit at 0.4× base multiplier; each hit resolves hit and crit independently; max 5 hits (Skill Level ≥10) | — (in-action mechanic, not persistent) | Twin-blade · Twin-blade Frenzy |
| Displacement | Buff (self) | 1 (this turn) | +2 extra movement squares this turn; ranged attacks do not trigger enemy Attacks of Opportunity; Evasion (EVA) +20% | No (refresh) | Skirmisher · Wind-fade Step |
| Guard Aura | Buff (whole party) | 3 | Party-wide DR+ (10% Stage 2 / 18% Stage 3 / 25% Stage 4); takes the highest value rather than stacking multiplicatively with other "party Damage Reduction" sources (Guardian · Bastion line, Paladin · Holy Aegis); then multiplied with personal DR | — (by skill) | Warding-dancer · Warding Waltz / Paladin · Blessing of Warding |
| Stealth | Buff | 1 | Cannot be targeted by Normal Attacks | — | Smoke Bomb |
| Poison | DoT | 3 | 0.5× Dexterity (DEX) Mystic (Shadow) damage per turn | Constitution (CON) DC12 | Deadly Venom Blade |
| Burn | DoT | 2 | 0.3× Magic (MAG) Elemental (Fire) damage per turn | Constitution (CON) DC12 | Fireball |
| Bleed | DoT | 2 | 0.4× Strength (STR) Physical (Pierce) damage per turn; healing −50% | Constitution (CON) DC12 | Backstab |
| Shield (revised) | Buff (absorption) | N (by source, usually 3) | Absorption shield = K× Attribute (1.0×CON / 1.2×MAG / 1.5×CHA); applied before true Health (HP) reduction, expires at 0; lasts "N turns or until absorption depleted", whichever first | — (by skill) | Paladin · Holy Aegis / Cleric · Warding Aegis |
| Mark / Regen | Buff/Debuff | 2/3 | Guaranteed hit +20% / recovery each turn | — | By skill |

DoT resolves in the "Start Phase"; stops for Downed targets; increasing resistance to Hard Control see 15.1.

> **New statuses and revision notes (7 new Stage-2 routes)**: ① **Vulnerable (new mechanic)**: "takes +X% damage", distinct axis from [Mark] (attacker deals +20% damage to marked target); Vulnerable is on the target, Mark is on the attacker, and they stack on the same target (Vulnerable + Mark = +35% damage taken), an intended focus-fire design ceiling. ② **Grapple = Immobilize**: the core effect "cannot move" is equivalent to Immobilize; the difference is that it can be actively escaped (Strength contest) + size DC+3 (when target size ≥ Large), and it does not conflict with Immobilize. ③ **Sunder revision**: the original skill text "Defense −15%~−30%, 3 turns" has been unified to "Damage Reduction (DR) −25%, 2 turns", consistent between skills and the status table. ④ **Shield revision**: absorption shield = K× Attribute (1.0×CON / 1.2×MAG / 1.5×CHA), duration explicitly "N turns or until absorption depleted (whichever first)"; Paladin / Cleric use 1.2×MAG, Warrior uses 1.0×CON. ⑤ **Guard Aura**: unified to take the highest value rather than stacking multiplicatively with other "party Damage Reduction" sources (Guardian · Bastion line, Paladin · Holy Aegis), then multiplied with personal DR.

### 7.7 Reaction Actions and Attacks of Opportunity (AoO)

**Reaction (0 Action Point (AP))** limited to 1 per turn, triggers on the enemy turn, and may be: ① **Attack of Opportunity** — when an enemy voluntarily leaves your melee reach (1 square) without disengaging, make 1 Normal Attack (can crit); Charge / Knockback / forced displacement / displacement through an enemy does not trigger it. ② **Block** — when equipped with a shield, after an enemy successfully hits you with a melee attack, an additional −Block Value at the end of final damage (shield base 5 + Warrior's "Iron Wall" +1.2 per Class Level (ClassLv)). ③ **Counterspell** — when an enemy casts a spell within your melee reach, d20+M+Prof ≥ DC (DC = 10 + that spell's Mana Point (MP) cost, DC16 if no cost) interrupts the casting. Applies symmetrically to NPCs / monsters.

### 7.8 Health (HP) ≤0: Downed, Death Save, and Revive

- **Downed**: Health (HP) ≤0 means Downed (HP drops to 0, skips action); DoT stops but Death Saves still occur.
- **Death Save**: at the start of each turn automatically d20 + Constitution (CON) modifier (M_CON) ≥ DC12 (natural 1/20 take priority); 3 cumulative successes → Stable, 3 failures → death (natural 1/20 count as 2).
- **Execute**: an enemy may Execute a Downed target (1 Action Point (AP)); a hit counts as 1 failure.
- **Revive**: an adjacent ally spends 1 Action Point (AP) to rescue via a healing effect (Path A, direct pullback) or a first-aid check DC12 (Path B, pull back to 1 Health (HP)).
- **Combat ends**: surviving Downed targets automatically regain 1 Health (HP); those already dead require post-battle paid resurrection at a temple (Chapter 4).
- Applies to players and important NPCs; fodder with Health (HP) ≤0 dies immediately (GM's discretion); Bosses usually do not enter Death Saves.

### 7.9 Spellcasting (Essentials)

Spells = Active Skill action (Action Point (AP) 1–3 + Mana Point (MP)); attack / control spells use Magic modifier (M_MAG) against Evasion (EVA), while pure control against NPCs instead uses Difficulty Class (DC) for resistance; on hit and natural roll ≥ Critical Threshold (CritTh), it is a Critical Hit; natural 1 always fails, while Shocked causes 50% spellcasting failure; learning rules see the Magic Codex "Magic Learning Rules".

### 7.10 Worked Example: Hit and Damage (CL5 Warrior vs CR5 Goblin)

Hit Bonus (Hit) = Attribute Modifier (M) + Proficiency (Prof) + weapon hit + status. Example: Warrior CL5 (M_STR+3, Prof+1, basic weapon +0) Hit Bonus (Hit) = +4; Goblin CR5 Evasion (EVA) 11. Roll d20=13 → hit succeeds; Normal Attack 1d8(5) + M_STR3 = 8 damage (Damage Reduction (DR) 0). See Player Book 7.10 for details.

## Chapter 8 Single-player Mode

- This game is designed to support single-player (1 Player + 1 GM), and also multiplayer (multiple Players + 1 GM).
- **Single-player suitability**: Warrior / Monk / Thief ◎; Hunter / Mage ○; Cleric △ (take Inquisitor); Dancer ✕ (core Action Point (AP) grant is lost in solo). The GM must present the suitability table at character creation step 5, disclosing the trade-offs in advance.
- **Single-player difficulty adjustment (no sidekick)**: in single-player mode **no assisting characters are provided** (no Sidekick companion); difficulty is instead supported by the party-size adjustment rule — enemy Challenge Rating (CR) −3, enemy count ×0.5 (at least 1), resources normal. Players must self-assess their role using the suitability table. Multiplayer uses the party-size adjustment rule.

---

# ▍GM-exclusive Chapter

## Chapter 9 Complete Check Mechanics and Difficulty Class Setting Guide

### 9.1 Check Procedure
1. The GM selects the relevant attribute and its corresponding Attribute Modifier (M) based on the situation.
2. Determine the Difficulty Class (DC), referencing the table below for a base by scene nature, then adjust ±1~2 to reflect situational modifiers (e.g., "slippery ground −2", "adequate preparation +2").

| Scene nature | Suggested Difficulty Class (DC) | Description |
|---|---|---|
| Daily, practiced actions | Trivial 5 ~ Easy 8 | Nearly always succeeds; only natural 1 fails |
| General challenge (climbing, negotiation, investigation) | Normal 12 | Same-level character ~60% success rate |
| Under pressure (in combat, time pressure) | Hard 16 | ~40%, needs advantage / bonus assistance |
| High risk (lethal environment, powerful enemy pressure) | Very Hard 20 | ~20%, recommend granting bonus sources |
| Legendary / Mythic events | Legendary 24 ~ Mythic 28 | Use only in specific set-pieces; avoid making it routine |

### 9.2 Bonus Stacking Cap and Natural Roll Priority
- **Total bonus cap per single check is +5** (sum of M, Prof, status, equipment, skill modifiers). Multiple sources may stack, but the portion beyond +5 is invalid; confirm the player's actually effective bonus before rolling.
- **Natural 1/20 takes priority over all bonus checks**; the GM should not override a guaranteed fail / success with "high bonus".
- **Contest / assist check exceptions**: in a contest check (1.8) both sides are each bound by the +5 single-check cap (see 1.4); the +2 assist bonus of an assist check (1.9) comes from an external ally and does not count toward the subject's own +5 cap.

### 9.3 Critical Hit Management (Combat Checks)
- Critical Hits occur only on **hit checks**; skill / attribute checks do not crit.
- Threshold-to-crit-rate: 20+ = 5%, 19+ = 10%, 18+ = 15%, 17+ = 20%, 16+ = 25%, 15+ = 30%, 14+ = 35%.
- Overflow-to-crit-damage: when the actual crit rate exceeds the threshold baseline (e.g., 35% at 14+), each 5% of crit rate overflow → Critical Hit damage +7.5% (ratio 1:1.5). When players stack high crit rate, the GM should proactively confirm whether to convert, to avoid inflated crit-rate numbers.
- Luck lowers the threshold: Luck reduces the threshold by 1 per 3 points; the GM should not omit it when calculating crit rate.

### 9.4 Critical Threshold (CritTh) Formula Ruling
```
CritTh = 20 − Crit Level − floor(Luck / 3)
```
Crit Level comes from equipment / crit attribute (0~6 levels, each lowers the threshold by 1); the baseline band 14+~20+ corresponds to 5%~35% crit rate; when Luck (LUK) pushes the threshold below 14, the crit rate beyond the 35% baseline converts to Critical Hit damage per 9.3 "overflow-to-crit-damage" (ratio 1:1.5).

### 9.5 Contest and Assist Checks (GM Perspective)
- **Contest check**: both sides roll d20+M+Prof+status, higher wins; natural 20 wins unconditionally, natural 1 loses unconditionally; a tie favors the defender (reroll optional). Both sides are each bound by the +5 cap; when a monster has no M/Prof, use Attack Bonus (ATK) in place of M with Prof=0 (see 1.8).
- **Assist check**: an ally spends 1 Action Point (AP) to provide +2 to the same check; at most 1 assist per check, the assister must have the relevant Prof or M; the assist bonus does not count toward the subject's +5 cap.
- For detailed rules and examples see Player Book 1.8 / 1.9 / 1.10.

---

## Chapter 10 Complete Combat Rules (GM Perspective)

### 10.1 Initiative and Turn Structure (Detailed)
- **Initiative (INIT)** = Dexterity modifier + d20; sorted high to low; on ties the defending side (player party) goes first. Initiative is rolled once at combat start and reused thereafter.
- **Start Phase**: Action Point (AP) refreshes; resolves "start-of-turn" ongoing effects (Poison / Burn / Bleed tick damage, Regen recovery); status durations −1 (removed at zero); those under Hard Control skip the action phase.
- **Action Phase**: perform actions according to Action Point (AP) cost.
- **End Phase**: resolve end-of-turn effects and clear this turn's temporary markers.

### 10.2 Monster Behavior Logic (AI)
The GM may use the following simple AI to guide monster actions and avoid stalls:
1. **Priority**: heal / protect casters (player Back Row) > attack nearest target > move closer.
2. **Hard Control preference**: prioritize Hard Control on squishy damage dealers; but observe "increasing Hard Control resistance" (see Chapter 15).
3. **Boss phases**: phase switches are bound to Health (HP) thresholds — **native battles (Scenario 1–8) 100% → 66% → 33%; Otherworld battles (Scenario 9–11, CR65+) change to 100% → 50% → 25%**, unaffected by crit fluctuation.
4. **Resource management**: monsters do not track Mana Point (MP), but skills have cooldowns; the AI prioritizes casting high-threat skills when not on cooldown.
5. **Positioning**: ranged monsters keep mid-distance; melee monsters move toward the Front Row, and when facing "ranged protection" prioritize dealing with the Front Row.

### 10.3 Monster Data Template
When designing a new monster, fill in the following fields per the Challenge Rating (CR) table (10.4):
```
Name / Challenge Rating (CR) / Health (HP) / Attack Bonus (ATK) / Evasion (EVA)
Damage Reduction (DR) / Movement / Initiative modifier / Attacks / Skills / Traits / Experience (EXP) / Drops
```

### 10.4 Challenge Rating (CR) System and CR Table
Formula: `HP=floor(40×(1+0.09×(CR−1)))`, `ATK=floor(1+0.25×CR)`, `EVA=10+floor(0.15×CR)`, `Damage=floor(6+1.2×CR)`; Critical Threshold is fixed at 20 (high Challenge Rating (CR) may lower it by 1~2). (Note: the EVA coefficient was reduced from 0.3 to 0.15 to fix high-CR hit collapse; see Player Book 1.1.)

| Challenge Rating (CR) | Enemy Health (HP) | Attack Bonus (ATK) | Evasion (EVA) | Damage/hit | Health (HP) Multiplier |
|---|---|---|---|---|---|
| 1 | 40 | +1 | 10 | 7 | 1.00× |
| 5 | 54 | +2 | 10 | 12 | 1.35× |
| 10 | 72 | +3 | 11 | 18 | 1.80× |
| 20 | 108 | +6 | 13 | 30 | 2.73× |
| 30 | 144 | +8 | 14 | 42 | 3.60× |
| 50 | 216 | +13 | 17 | 66 | 5.40× |

### 10.4b Standard NPC Stat Template (by Challenge Rating CR)
For the GM to fill in "enemy / neutral NPCs" in scenarios. Stats directly apply the enemy CR formula (same source as monsters), then add "traits / dialogue" per identity.

| Challenge Rating (CR) | Health (HP) | Attack Bonus (ATK) | Evasion (EVA) | Damage/hit | Experience (EXP) | Suggested identity |
|---|---|---|---|---|---|---|
| 1 | 40 | +1 | 10 | 7 | 16 | Villager, fodder, wild beast |
| 2 | 43 | +1 | 10 | 8 | 34 | Apprentice Thief, Goblin Warrior |
| 3 | 47 | +1 | 10 | 9 | 54 | Training Phantom, Sentry |
| 5 | 54 | +2 | 10 | 12 | 100 | Mercenary, Orc Warrior |
| 8 | 65 | +3 | 11 | 15 | 184 | Elite Guard, Bounty Hunter |
| 10 | 72 | +3 | 11 | 18 | 250 | Knight, Lich's Minion |
| 15 | 90 | +4 | 12 | 24 | 450 | General's Aide, Demon-realm Vanguard |
| 20 | 108 | +6 | 13 | 30 | 700 | Death Knight, Dragonborn Captain |

> Important: This template is for "enemy / neutral NPC" stat reference only. Per this game's setting, single-player mode "does not provide a Sidekick companion", so no separate "sidekick NPC" template is provided; single-player difficulty is instead supported by the party-size adjustment rule (Challenge Rating (CR) −3, enemy count ×0.5). A neutral NPC's social stats (negotiation / intimidation Difficulty Class (DC)) are set by the GM per the story and need not force-apply the combat columns above.

### 10.5 Combat Map Grid Scale
- 1 square = 2 meters (m). Movement = `3 + floor(Dexterity/4)` squares / move action.
- Range: melee 1 square / short 2–4 squares / mid 5–10 squares / long 11+ squares.
- Area Effect (AOE): center square + radius R squares. Front/Back Row spacing is 2 squares (4m). Recommended combat map width 8–12 squares.

### 10.6 Damage Reduction and Critical Immunity
- The total multiplicative Damage Reduction (DR) already has a hard cap of **60%** in §7.3 (head / hand / foot gear DR exceeding the body armor's base value is invalid); stacking many sources is still bound by this cap and will not make enemy output fully ineffective. If the player's effective Health (EHP) is still too high, prefer balancing with "ignore part of Damage Reduction", "true damage", or "resource cost" rather than directly cutting Damage Reduction.
- Specific Bosses may be given the "Critical Immunity (Crit-Immune)" trait to reverse the feel of "the stronger they are, the easier to crit" (e.g., constructs, undead, slime cores).

### 10.7 Boss Framework (full stats not expanded)
- **Dragon General Ignis Ember-scale**: Phase Three "Berserk State" opens an easy-crit finishing window.
- **Charm General Lilith Charm-shadow**: [Illusion-dance (Charm, 1–3 turns by level)] for crowd control.
- **Necro General Morfana Silent-burial**: Phase Three [Critical Immunity] core; must destroy the life-protecting coffin to remove it.
- **Gel General Plum Gel**: Phase Three [Crystallization] critical immunity + high Damage Reduction, requires [Bludgeon to Shatter Crystal] to break.
- **Demon Lord Vercellia**: Phase Three [Judgment of the End] whole-field instant-death threat countdown.
- **The Fifth, Jeno Gojō**: knows the players' tactics; in Phase Two copies ally skills; if enough Influence Points, turns to atonement sidekick.

### 10.8 Health (HP) ≤0: Downed, Death Save, and Revive (GM Perspective)
- Player characters and important NPCs follow the full 7.8 sequence (Downed → Death Save → Revive → post-battle resurrection).
- Monster handling: ordinary fodder with Health (HP) ≤0 dies immediately (no Death Save, for pacing); **important monsters / elites** may optionally use Death Saves to extend tension.
- Execute abuse prevention: if players Execute Downed monsters too frequently and it saps combat fun, you may instead rule "execution ends that monster's Death Save" for an immediate death ruling, without forcing a roll each time.
- Death weight variant: high-tier resurrection may require "spending part of memory / attributes" as a cost (Chapter 16, 16.2), at the GM's discretion.

### 10.9 Reaction Actions and Attacks of Opportunity (GM Execution)
- Players and monsters symmetrically apply the three types of reactions from 7.7 (Attack of Opportunity / Block / Counterspell), once each per turn.
- When giving monsters reaction traits, suggested: Front Row tank types get "Attack of Opportunity", shield guards get "Block", spellcasting Bosses get "Counterspell" to counter player Charge-casting.
- Counterspell DC = `10 + target's Mana Point (MP) cost`; if the monster does not track Mana Point (MP) (see 10.2.4), uniformly use DC 16.
- Independent from "Free Action (0 Action Point (AP))": a monster's passively triggered effects do not consume its reaction allowance.

---

## Chapter 11 Encounter Design and Difficulty Balance Guide (Difficulty Budget)

Based on "total player level", the sum of enemy Challenge Rating (CR):
- Easy ×0.5 / Standard ×1.0 / Hard ×1.5.
- Boss fight: a single Boss Challenge Rating (CR) ≈ sum of party levels ×0.6 (with fodder maxed out ×1.2).
- Estimate player output including "about 80% crit rate × 2.0 crit multiplier" (effective multiplier ~1.6×), then back-calculate the Boss's Health (HP).

**Construction principles**:
1. Include at least one "positioning incentive" (terrain / Back Row threat) so positioning matters.
2. Control total Hard Control volume; avoid locking more than 1 target per turn.
3. Boss fights must have a "Phase Three finishing window" and a "breakable object / core" mechanic.
4. When a Dancer line is present, the budget may be raised (the party Action Point (AP) engine improves clear speed).

---

## Chapter 12 Lore and Setting Details

### 12.1 Continent and Calendar
- **Altia Continent (Eltyria)**. Calendar: **Demon Lord Calendar (DLC)**; currently **Demon Lord Calendar year 1024**. Human civilization has prospered for a millennium, while the Demon Lord Army holds the border in a long-standing cold-war-like standoff.
- Tone: classic Japanese "hero vs. Demon Lord" orthodox fantasy, with a "heroic hot-blooded + lighthearted comedy" feel.

### 12.2 The Seven Gods
| Divine domain | Full god name | Temple location | Faction |
|---|---|---|---|
| God of Warriors | Galdor Iron-oath | Alno Holy City · Oathiron Grand Cathedral | Martial |
| God of Monks | Hayato Mumyo | Sakura-view Isle · Mumyo Dojo | Martial |
| God of Mages | Ruri Hoshii | Ironfurnace City · Hoshii Tower | Civil |
| God of Clerics | Sephi Mercylight | Alno Holy City · Mercylight Grand Cathedral | Civil (Church headquarters) |
| God of Thieves | Yosuzume Shadow-stitch | Lune Free City-State · Shadow-stitch Sanctum | Martial (grey) |
| God of Hunters | Aolang Wind-fade | Edge of the Aiwen Green Sea · Wind-fade Hunting Fort | Martial |
| God of Bards | Ayane Rainbow-echo | Wanderer (main shrine in Lune) | Civil |

The Seven Temples split into two loose factions, "Martial" and "Civil", and their conflict is a hidden story engine; the core conflict is the Cleric temple's monopoly on the "Resurrection" economy (see Chapter 5 Resurrection Fee), which can spawn side quests granting Influence Points.

### Guardian Deity Graces (triggered once per rest per day)
Each character corresponds to one Guardian Deity by class, gaining a "passive grace (always on)" + "an active ability usable once per rest" + "a simple requirement".

| Guardian Deity (corresponding class) | Passive grace (always on) | Per-rest active ability (1 / rest) | Simple requirement |
|---|---|---|---|
| Galdor Iron-oath (Warrior) | Block Value +1 when equipped with a shield; Critical Hit damage taken −5% | [Oath Counter] First battle after this rest: auto-Block the first time you would take lethal damage (negate death once) | Protect the weak; never break an oath |
| Hayato Mumyo (Monk) | Evasion (EVA) +0.5 per Class Level (ClassLv) (cap +5); +10% evasion on the first turn after disengaging | [Afterimage Step · Modified] First battle after this rest: gain 1 free Movement (through enemies) at combat start | Never bully the weak; protect the nameless |
| Ruri Hoshii (Mage) | Mana Point (MP) cap +5; spell Critical Threshold (CritTh) −1 | [Hoshii Resonance] First battle after this rest: first attack spell is guaranteed to hit and ignores 1 layer of Damage Reduction | Seek knowledge without doubt; never abuse forbidden spells |
| Sephi Mercylight (Cleric) | Healing +5%; purification effects remove 1 extra | [Mercylight Shelter] First battle after this rest: first time the whole party is near death, restore Health (HP) once (amount = base healing B) | Redemption over punishment; show mercy to all |
| Yosuzume Shadow-stitch (Thief) | Drop rate +5%; Steal / Disarm Trap Difficulty Class (DC) −2 | [Shadow-stitch Escape] First battle after this rest: once, escape disadvantage at no cost (withdraw from battle / reroll 1 check) | Rob the rich to aid the poor; keep secrets |
| Aolang Wind-fade (Hunter) | Ranged damage +3%; Initiative +1 | [Eye of Wind-fade] First battle after this rest: mark 1 enemy on the first turn (allies deal +15% damage to it, guaranteed hit for 2 turns) | Never overkill; respect the wild |
| Ayane Rainbow-echo (Dancer) | Buff effects +3%; +1 Evasion (EVA) per buffed ally | [A Rainbow Echo] First battle after this rest: at combat start grant whole party Attack +5%, Hit Bonus (Hit) +1 (2 turns) | Inspire others; never mock the defeated |

> "Rest" means town recuperation or wilderness camping (GM's discretion). Active abilities reset once per day; when a "simple requirement" is violated, the GM may suspend that deity's active ability once (passive unaffected). Graces do not count toward Influence Points (IP).

＊ The "full recovery + resurrection" rules for town / temple recuperation are in Chapter 17, 17.6.

### 12.3 The Demon Lord and the Four Demon Generals, plus the Fifth

> **Level reshuffle (synced with the Monster Codex)**: the Four Demon Generals' thresholds are all raised to ≥40 and distributed, serving as elite barriers in the late game; the Fifth, Jeno is an independent general at CR45; the Demon Lord stays at CR50. CL1–40 is now filled by "six themed dungeons + themed guild commissions" (see Chapter 17 and the Commission Catalog), as the leveling period before the main-story general battles.
> - Dragon General Ignis Ember-scale: **CR 40** (Scenario 5 threshold)
> - Spirit General (Necro General) Morfana Silent-burial: **CR 42** (Scenario 6 threshold)
> - Charm General Lilith Charm-shadow: **CR 44** / Gel General Plum Gel: **CR 46** (Scenario 7 dual-general line)
> - The Fifth, Jeno Gojō: **CR 45** (Scenario 8 reversal general)
> - Demon Lord Vercellia Nornheim: **CR 50** (Scenario 8 final battle)
> - CL50+ endgame is themed on "beyond-the-world (Otherworld)" enemies (see Scenario 9–11 and Monster Codex Chapter 5): Void-realm Sentinel CR65 (Scenario 9 mini-boss) / Eclipse Sovereign CR75 (Scenario 10 mid-boss) / Eschaton Prophet CR85 (Scenario 11 personal guard) / Beyond-the-World · Singularity CR99 (Scenario 11 final BOSS).

- **Demon Lord Vercellia Nornheim (CR 50)**: proud but lonely, sharp-tongued, loves sweets (comedic contrast). Motive: end the cycle of divine-demonic hatred through sheer power; can be romanced / turned / recruited / reconciled with. Humanoid: a tall human-shaped queen in a purple-black gown with demonic embroidery, a thorn crown on her head, heterochromatic eyes (one gold, one purple), wielding the scepter "Oath's End".
- **Dragon General Ignis Ember-scale (CR 40)**: tsundere and warlike, worships strength; can be romanced if won over by power. **Humanoid** (human-shaped, retaining draconic features): crimson long hair, a pair of black dragon horns on the forehead, clad in dragon-scale armor, molten-gold dragon eyes; when battle spirit rises, draconic wing phantoms surface on her shoulders.
- **Charm General Lilith Charm-shadow (CR 44)**: charming and clever, wants to prove demons can be loved too; romance-comedy route available. **Humanoid**: bat wings folded like a cloak, pointed ears, enchanting-purple long hair, alluring smile with occasional glimpse of demonic fangs, figure seductive like a mortal dancer.
- **Spirit General (Necro General) Morfana Silent-burial (CR 42)**: gloomy yet gentle, tends to the dead; gentle-type route available. **Humanoid**: pale shrine-maiden attire, semi-transparent spectral outline, hands cradling ghostly blue netherfire, wielding the bone staff "Silent Burial", footsteps silent like a dead whisper.
- **Gel General Plum Gel (CR 46)**: naive foodie with a baby voice, comedy relief; moe-type route available. **Humanoid**: a semi-transparent gelatin-textured human girl, body like wobbling jelly, innocent big eyes, hair like flowing colored gel, makes a "boing" sound when moving.
- **The Fifth, Jeno Gojō (CR 45) | Female · Human · Traitor | Demon Lord Army "Fifth Demon General"**: originally a human prodigy knight, removed from the order after being falsely accused of cheating in the promotion exam, she defected in anger and became the Demon Lord Army's **Fifth Demon General** (not one of the original Four Demon Generals; insists "I'm the fifth, not one of the Four Heavenly Kings"). Straight-man tsukkomi role, fundamentally not evil. Humanoid: a human swordwoman in a black-knight-style cape, bearing the "Formless Blade", with the "Rebel Flag" emblem branded on her left eye. Potential defection point (S2: striking her loneliness can trigger a defection side quest, granting large Influence Points (IP) and an S4 one-time sidekick — a story mechanic, not a permanent solo assist).

### 12.4 Adventurers' Guild and Temples
- **Adventurers' Guild**: headquartered in Alno Holy City; guild rank (Rank, unrelated to Character Level (CL)) from low to high F→E→D→C→B→A→S determines the max commission level you may accept; each promotion requires passing a guild exam (inserted by the GM as a story node).

### Guild Rank Promotion Table (Rank F→S)
| Rank | Max commission level (Challenge Rating CR) | Unlocked content | Promotion exam method |
|---|---|---|---|
| F Apprentice | 1–4 | Basic commissions, basic shop, temple entry | S0 induction live-combat simulation + commission settlement |
| E | 5–8 | Regional subjugation commissions, guild warehouse | Subjugate a designated CR 5–8 squad (live combat) |
| D | 9–12 | Escort / reconnaissance high-tier commissions | Escort an important target through enemy territory |
| C | 13–18 | Bounty subjugation, guild discount 5% | Regional purge (including undead threats) |
| B | 19–28 | Demon-General-related frontline commissions, discount 10% | Two-pronged parallel operations |
| A | 29–40 | Elite bounties, exclusive forging quota | Duel a powerful foe (designated CR 30+ simulation) |
| S | 41+ | Demon Lord Castle subjugation / full peace authority, legendary renown | Demon Lord Castle battle + Influence Points (IP) review (total Influence Points (IP) ≥40 required to grant S) |

> Failed exams may be retaken (interval set by the GM), no rank deduction. Rank increase also unlocks corresponding "guild commission" side quests, contributing Influence Points (IP).
>
> For specific commission contents (each Rank's concrete commissions: target Challenge Rating (CR), Experience (EXP), Gold (G), Influence Points (IP)) see **the Commission Catalog**; for structured dungeon play see **Chapter 17 Dungeon Exploration**.

### Temple Friendliness Scale (0–100)
The Seven Temples share one "Temple Friendliness" scale (centered on your Guardian Deity's temple). It affects resurrection fees and side-quest rewards.

| Tier | Friendliness | Resurrection fee modifier | Side quest / shopping impact |
|---|---|---|---|
| Hostile | 0–19 | Resurrection fee +50% | Refuses service; may trigger hostile events |
| Cold | 20–39 | Resurrection fee ×1.0 (baseline) | Basic service only |
| Neutral (baseline) | 40–59 | Resurrection fee ×0.9 | Ordinary commissions |
| Friendly | 60–79 | Resurrection fee ×0.8 | Unlocks temple-exclusive side quests, equipment discount 5% |
| Venerated | 80–100 | Resurrection fee ×0.6 | Exclusive epic commissions, discount 10%, free purification |

Friendliness changes: + completing temple commissions (+5~10), donation (about +2 per 100 G), daily (long rest) prayer (+1/long rest; "day" means town / temple full recuperation, see 17.6, not per battle), fulfilling Guardian Deity requirement (+3); − attacking clergy (−15), blasphemy (−20), violating requirement (current active grace suspended and −5). Initial: Temple origin +15 (starts at friendliness 55), others start Neutral (40–50). Compare with the resurrection fee baseline (Chapter 4): first time free, nth time (n≥2) = 100×2^(n−1) G, wilderness location +50%, friendliness modifier applied before location surcharge.

- **Temples**: the Seven Temples are nodes for resurrection / equipment / prayer interaction; temple friendliness affects resurrection fees and side-quest rewards (see table above).

### 12.5 Faction Standing Summary Table (Faction × Standing Level)

> Standing levels reuse the five-tier Temple Friendliness scale from §12.4 (Hostile 0–19 / Cold 20–39 / Neutral 40–59 / Friendly 60–79 / Venerated 80–100) as a unified cross-faction quantification axis. Below are the concrete effects of each major faction on that axis; "Demon Lord Army" being the main-story enemy / romanceable target instead maps to "subjugation / recruitment progress (Influence Points IP)", listed in the last column for reference.

| Faction (quant axis) | Hostile 0–19 | Cold 20–39 | Neutral 40–59 (baseline) | Friendly 60–79 | Venerated 80–100 |
|---|---|---|---|---|---|
| Seven Temples (temple friendliness) | Refuses service; may trigger hostile events; resurrection fee ×1.5 | Basic service only; resurrection fee ×1.0 | Ordinary commissions; resurrection fee ×0.9 | Unlocks temple-exclusive side quests; equipment discount 5%; resurrection fee ×0.8 | Exclusive epic commissions; discount 10%; free purification; resurrection fee ×0.6 |
| Adventurers' Guild (Rank F–S) | Limited to F/E low-tier commissions | May accept up to D rank | Commissions for corresponding Rank (see end-of-chapter table in §12) | High-Rank exclusive commissions, renown rewards | Full S-rank authority, legendary renown (total IP≥40 required to grant S) |
| Martial Temple Alliance (Warrior / Monk / Thief / Hunter) | No funding, questions stance | Neutral watch | Baseline interaction | Funds resurrection bypassing the church; provides combat support | Martial faction gives full support, joint operations |

| Scholastic Temple Alliance (Mage / Cleric / Bard) | Information lockdown; escalating Resurrection Fee | Baseline Resurrection Fee | Baseline knowledge / resurrection access | Knowledge disclosure, Resurrection Fee reduction | Church core authorization, free resurrection franchise |
| Demon Lord Army (subjugation / surrender progress, tied to IP) | No contact = main-story hostile | In contact (combat) | Neutral negotiation (can be pursued) | Surrender → S4 allied unit; Reconciliation → ending unlocked | Full defection, temple reconciliation, issuance of the golden Hero's Proof |

> **Cross-faction drive**: Aside from Guild Rank, the attainability of each faction's "Friendly / Revered" standing is ultimately moderated by **Influence Points (IP)** (see Chapter 6); pure combat progression (no choices) grants 0 IP, so level-grinding alone cannot max out faction standing. The GM should drive standing changes through "choices" rather than "levels."

---

## Chapter 13　Scenario Running Guidelines (Method A)

**This work explicitly adopts "Method A: one scenario + player-count adjustment rules"**: A single universal scenario is written (Prologue / S0 + Scenarios 1–11), and no separate scenario is written for each player count; instead, a "player-count adjustment rule" dynamically scales difficulty and event volume.

### 13.1 Player-count Adjustment Rules (concrete, baseline of 4 players)

**Player count**: Supports **1–6 players**, baseline is a **4-player party** (a 3-player party is also treated as the baseline band, consistent with the original design "3 players → baseline; 4 players → baseline").

| Player count | Enemy Challenge Rating (CR) | Enemy count | Notes |
|---|---|---|---|
| 1 (solo) | Challenge Rating (CR) −3 | enemy count ×0.5 (minimum 1)＊ | Resources normal; no ally (pure solo, see Chapter 8); single-target Boss exception see §13.1b |
| 2 | Challenge Rating (CR) −1 | enemy count ×0.75 | — |
| 3 | Baseline | Baseline | — |
| 4 (baseline) | Baseline | Baseline | — |
| 5–6 | Challenge Rating (CR) +2 | enemy count ×1.5 | Concurrency events +1 |

All adjustments compare "total player level" against the Chapter 11 encounter difficulty budget. Solo-exclusive: This work does not provide allied Non-Player Characters (NPCs) for solo play (see Chapter 8); difficulty is supported by Challenge Rating (CR) −3 and enemy count ×0.5 (minimum 1); players must self-assess their role.

> ＊ The "enemy count ×0.5" in the table above does not apply to single-target Bosses; see §13.1b for details.

### 13.1b Single-target Boss Player-count Adjustment (drafted by combat-designer · finalized by dice-mechanics)

> This section covers the player-count scaling for "single-target Boss (Boss)" encounters, used together with the player-count multiplier in §13.1 above; group Bosses (multiple leaders / twin generals) still use the general multiplier from the table above. This model has been precisely finalized by dice-mechanics based on the values confirmed by the GM (verification: a CR40 solo Boss is breakable in about 6–9 rounds, and players are not one-shot killed).

- **1 player challenging a single-target Boss**: Boss max Health (HP) ×0.6, Boss damage dealt ×0.7, and "locked as a single-target encounter" — the "enemy count ×0.5 (minimum 1)" multiplier in §13.1 **does not apply to single-target Bosses** (a single target is just 1, there is no enemy count to cut); the original "Challenge Rating (CR) −3" tier adjustment is retained.
- **2–4 players challenging a Boss**: Maintain the existing player-count enemy multiplier from §13.1 (×0.5 (2 players) ~ ×1.0 (3–4 players)); the single-target Boss itself is 1, and attached minions scale up or down per the multiplier.
- **5–6 players challenging a Boss**: Maintain the ×1.5 enemy multiplier from §13.1 (including attached minions); the single-target Boss itself remains 1.

> Design principle: When a solo player fights a single-target Boss, the Boss is already weakened threefold by CR−3 and HP×0.6 / damage×0.7, and need not further bear "enemy count ×0.5" — that multiplier only makes sense for "countable enemy groups," is invalid against a single target, and is therefore explicitly excluded.

### 13.1a Player-count-triggered Special Encounters · Mechanics Layer (combat-designer)

> This section is the **mechanics counterpart layer** of §13.2.1 (world-crafter narrative templates "Twin Gate Generals" and "Solitary Solvability"): it defines concrete values and checks so the GM can execute them directly. For narrative staging see §13.2.1; this section only writes mechanics. The corresponding player-perspective split rules are in the Player Book §7.5a.

#### ① 5–6 Player "Two-line Encounter" Mechanics (aligned with §13.2.1 Template ① "Twin Gate Generals")

- **Trigger**: A 5–6 player party using "splittable into two routes" (see Player Book §7.5a / GM Book §13.1 "splittable into two routes + concurrency events +1") naturally produces a two-line encounter.
- **Enemy count ×1.5 total split**: Total enemy count = baseline enemy count ×1.5 (§13.1 player-count multiplier), distributed by the two sub-parties' **combat-power ratio (player-count ratio)** — a 5-player split of 3+2 → 60% / 40%; a 6-player split of 3+3 → 50% / 50%; at least 1 enemy per route.
- **Fewer-player route protection (aligned with §13.2.1 split principle)**: The enemy Challenge Rating (CR) on the fewer-player route (e.g., the 2-player route in a 5-player 3+2 split) does not take the "+2" from §13.1, but is instead treated as **baseline CR** based on that route's player-count ratio (i.e., no extra multiplier); enemy count is still allocated at 40%. The more-player route's enemy CR = baseline +2. This guarantees the fewer-player route "does not stall."
  - Note: This is a **5–6 player two-line exclusive CR concession**, and does **not conflict** with the Player Book §7.5a "split does not change CR" (= the sub-team player count is not recalculated as an independent party CR) — the fewer-player route proactively drops back to baseline CR as protection, not a recalculation as "2-player sub-team = CR−1".
- **Concretizing concurrency events +1**: The two-line encounter is treated as "simultaneously concurrent" — besides the two routes' combat, the GM additionally triggers **1 dynamic event** (e.g., an enemy reinforcement wave, a mechanism lock-down, a timed seal-break), handled by the first route-cleared sub-party or the reinforcing side, fulfilling "concurrency events +1".
- **Combined Boss (Boss) trigger**: After either route A / B "defeats its gatekeeper," a convergence gate opens; once the other route is defeated, the twin generals combine into a "Gatekeeper Boss (Boss)" appearing at the central arena — CR ≈ baseline +2, two phases (aligned with §10.7 Boss framework). If the first route-cleared sub-party dawdles excessively before the other route is cleared, the combined Boss gains a "pre-charged buff" (e.g., +10% attack on the first round, or 1 stack of Damage Reduction) as a tension penalty.
- **Reward division of labor (mechanics layer)**: Route A (combat) drops physical supplies (Gold (G) / materials); Route B (puzzle / social) grants Influence Points (IP) +1~3; convergence shared rewards (boss key / dungeon core) are not duplicated (to avoid double-farming, see §13.2.1).

#### ② Solo "Skippable Social Gate / Puzzle-solvability Guarantee" Mechanics (aligned with §13.2.1 Template ② "Solitary Solvability")

- **Applies to**: Pure solo (1 player) mode (§8 / §13.1: no allies).
- **Social gate guarantee**: For social / negotiation checkpoints in a solo encounter, the GM **must not** force "multiple roles played by several people" or "requiring a teammate to assist persuasion." If the original scenario uses a multi-pronged persuasion, under solo it becomes a single-person negotiation check (Charisma (CHA) or the corresponding attribute), with DC no higher than the original design, and the GM **must provide at least 1 "persuasion side-quest clue"** (lowering DC by 2~3) or allow "bypass" (see below).
- **Puzzle gate guarantee (Intelligence (INT) check DC −2)**: For solo puzzle checkpoints, the GM **must** provide a "solvability guarantee" — at least **1 clue card** or equivalent hint per puzzle, and allow direct progression via "Intelligence (INT) check DC = original DC −2." A failed check **only delays** (retryable, no hard block); natural 1 still fails, natural 20 still succeeds (§1.1).
  - ✅ Aligned with §13.2.1 (L726): solo puzzle Intelligence (INT) check DC −2 (guaranteed solvable); this mechanics layer (L667) and the narrative layer (L726) are consistent, no open items.
- **Bypassing the social gate (Bypass)**: When progress is blocked by "must persuade / intimidate a certain NPC" and the solo player's Charisma (CHA) is insufficient, allow (a) discovering a side door / secret passage (revealed by an investigation or a clue card) as a physical bypass; or (b) using an Intelligence (INT) check to read the NPC's weakness notes and hit the crux directly to complete the persuasion.
- **Pure-combat gate prohibition**: Pure combat checkpoints **must not** force multi-player cooperative actions (e.g., "two people pull levers simultaneously," "require a teammate to cover for output"). If the original design includes cooperative mechanisms, under solo change them so a single player can complete them independently (change the timed mechanism to be single-player operable, or allow summoning a temporary mechanism / self-triggering ward).
- **Difficulty anchoring**: The above guarantee mechanics run in parallel with §13.1 "solo Challenge Rating (CR) −3, enemy count ×0.5"; the "solvable" guarantee does not additionally lower CR, it only ensures solo is not hard-blocked by the checkpoint structure.

### 13.2 Campaign Chapters (stepped)

> **Structure rearrangement note**: All 11 chapters (Scenarios 1–11). CL1–40 is the leveling period of "six themed dungeons + themed guild commissions" (Scenarios 1–4 overview), and the main-story Demon General battles only begin here (Scenarios 5–8); all four Demon Generals' thresholds are ≥40 and spread out (Dragon 40 / Necromancer 42 / Charm 44 + Gel 46), the Fifth, Jeno CR45 appears in a reversal at Scenario 8, and the Demon Lord is CR50; CL50+ is the endgame of "Beyond the World (the Otherworld)" (Scenarios 9–11: minor boss Void-realm Sentinel CR65 / mid boss Eclipse Sovereign CR75 / personal guard End-time Prophet CR85 + final BOSS Singularity CR99).

| Chapter | Suggested Character Level (CL) | Difficulty Class (DC) baseline | Challenge Rating (CR) baseline (4 players) | Main story / role |
|---|---|---|---|---|
| S0 Prologue · Tutorial Village | Character Level (CL) 1–4 | 10–12 | 1–4 | Claim the title of hero, join the guild, first encounter with the Fifth (Hub starting point) |
| Scenario 1 Border Trial | Character Level (CL) 1–12 | 10–15 | 2–12 | Leveling-period overview ①: D1 Goblin Lair + D3 Forest + D4 Desert; paired with the <Commission Catalog> F→D themed commissions |
| Scenario 2 Abyssal Echo | Character Level (CL) 13–26 | 16–21 | 13–26 | Leveling-period overview ②: D2 Slumbering Tomb + D5 Ocean + D6 Volcano; connects to the Fifth's backstory |
| Scenario 3 Frozen Throne | Character Level (CL) 27–34 | 22–24 | 27–34 | Leveling-period overview ③: D7 Ice Plains (Frost Queen CR34) |
| Scenario 4 Ruins Final Stage | Character Level (CL) 35–40 | 23–25 | 35–40 | Leveling-period overview ④: D8 Ancient Ruins (Ruin Guardian CR40); leads to the Demon General threshold |
| Scenario 5 Dragon General Battle | Character Level (CL) 40 | 23 | 40 | Requires Rank S (CR40 cap) threshold; march north to subjugate / persuade the Dragon General |
| Scenario 6 Necromancer General Battle | Character Level (CL) 42 | 24 | 42 | March west into the necro-domain; expose the church's dark secrets; the Fifth's backstory |
| Scenario 7 Charm General + Gel General Battle | Character Level (CL) 44 | 25 | 44 (twin generals) | South (Charm CR44) + East (Gel CR46) two-line |
| Scenario 8 Demon Lord Castle | Character Level (CL) 46–50 | 26–28 | 46–50 | Four Demon Generals settled → castle opens; the Fifth, Jeno (CR45) reversal; IP settlement → subjugation or reconciliation (Demon Lord CR50) |
| Scenario 9 Rift Emergence | Character Level (CL) 50–65 | 28–32 | 55–65 | Beyond the World ①: Otherworld outpost + endgame minor boss Void-realm Sentinel (CR65) |
| Scenario 10 Otherworld Campaign | Character Level (CL) 66–75 | 33–36 | 70–75 | Beyond the World ②: deep realm conquest + endgame mid boss Eclipse Sovereign (CR75) |
| Scenario 11 The End | Character Level (CL) 76–99 | 37–40 | 85–99 | Beyond the World ③: first defeat the personal guard End-time Prophet (CR85), then the final BOSS Singularity (CR99), endgame at max level CL99 |

Stepped: CL1–40 leveling period (Scenarios 1–4) accumulates battle honors / Influence Points (IP) → Four Demon Generals settled (Scenarios 5–7) → Demon Lord Castle (Scenario 8) → after the Demon Lord Castle collapses the ground splits open and the Otherworld invades (Scenarios 9–11).

### 13.2.1 Player-count-triggered Special Encounters · Narrative Templates (world narrative)

> This section is maintained by the worldview and narrative designer (world-crafter), providing **narrative templates** for the GM to apply directly; the corresponding "combat mechanics (split / two-line judgment / enemy multiplier)" are defined by the combat-designer in the §11 / §13.1 mechanics layer — the two do not overlap — **this section only writes "how to stage, how to say it, how to narrate rewards," not values**. The GM picks the templates below based on the player-count trigger conditions in §13.1 (5–6 player two-line / split, 1 player solo puzzle-solvability guarantee).

#### Template ①　Two-line Encounter (5–6 players) — "Twin Gate Generals"

**Applies to**: 5–6 player parties, a "dual gate" scene deep in a dungeon or at a Demon General outpost (aligned with §13.1 "splittable into two routes + concurrency events +1").

**Scene description (GM narration script)**
> The passage splits in two here. From the left "Lava Fork" comes the clang of metal and bestial roars; from the right "Shadow Corridor" drift whispers and the sound of mechanism gears. At the end of the passage, the [Oathbound Twin Doors] stand tightly shut — legend says two "Twin Gate Generals" of the Demon Lord Army guard each line, and only when both lines are broken simultaneously will the doors authenticate and open.

**A / B route split logic (narrative layer)**
- **Route A (Lava Fork)**: Combat-oriented. Advanced by the party's "front row / damage" subgroup, facing Gate General · Flame (physical crowd enemies), a resource-draining attrition fight.
- **Route B (Shadow Corridor)**: Puzzle / social-oriented. Advanced by the party's "Intelligence / Charisma" subgroup, facing Gate General · Shadow (mechanisms + negotiable remorseful soldiers), information- and choice-driven.
- **Split principle**: Make both lines "meaningful and each with its own strength," avoiding either line becoming pure waiting. If a line has fewer players (e.g., a 5-player 3+2 split), the GM lowers CR / enemy count for the fewer-player line per §13.1, guaranteeing no stall.

**Convergence trigger (narrative layer)**
> When Route A shatters the Flame General's "Oathbrand Sigil" and Route B obtains the Shadow General's surrendered "Tacit Key," the twin seals on the doors flare and shatter at once — the [Oathbound Twin Doors] burst open, and the two routes' allies reunite behind the door.

**Reward differences (narrativized, to avoid double-farming)**
- **Route A (combat)**: Leans toward supplies — extra loot / Gold (G) / rare materials, narrated as "confiscated from the Flame General's armory."
- **Route B (puzzle / social)**: Leans toward bonds — Influence Points (IP) +1~3 (revealing the Shadow General's remorse, or sparing his subordinates), unlocks side-quest intel, narrated as "hearing the Demon Lord Army's unknown sighs."
- **Convergence shared reward**: Clearing progress / boss key (e.g., dungeon core), not duplicated.

> The mechanics layer (enemy count ×1.5, concurrency +1, split judgment) is in combat-designer's §13.1 mechanics note; this template is for GM improvisation only.

#### Template ②　Solo Puzzle-solvability Guarantee (1 player solo) — "Solitary Solvability"

**Applies to**: Solo mode (§8 / §13.1: pure solo, no allies). Core promise — **any puzzle / social gate that could hard-block must reserve a solvable path for solo.**

**Guarantee mechanics (pick one of three at the narrative layer, chosen by the GM on the spot)**
1. **Clue Cards**: Split information that "requires multi-player cooperation to see fully" into independently collectible clue fragments. The solo player picks them up one by one via exploration / investigation checks (Perception DC 12~16, see §17.3), and once collected the puzzle is solved, without relying on teammates reporting to each other.
2. **Intelligence (INT) check substitution**: If the puzzle originally requires a specific class skill (e.g., Thief's Sleight of Hand to pick locks, Cleric's Purify), solo allows substituting with "Intelligence (INT) check DC = original DC −2" (guaranteed solvable); natural 1 still fails, natural 20 still succeeds (§1.1).
3. **Bypass Social Gate**: When progress is blocked by "must persuade / intimidate a certain NPC" and the solo player's Charisma (CHA) is insufficient, allow the following detours —
   - Discover a "side door / secret passage" (revealed by an investigation check or clue card), a physical bypass;
   - Use an INT check to read the NPC's "weakness notes" and hit the crux directly to complete persuasion (equivalent DC but still allows a critical-hit judgment);
   - The GM gives an "in-context hint" on the spot rather than dispatching an allied NPC (rule: hints allowed, no proxy play).

**When "Bypass Social Gate" is allowed**: Only when that social gate is "not a main-story critical-info disclosure" (see §15.3 disclosure obligations of choice). If the social gate carries "critical info that must be disclosed" (e.g., the Demon Lord's motive, reconciliation possibility), then **do not bypass**; instead the GM lowers the DC or delivers the info directly via a clue card, ensuring solo does not miss the main story.

**Solo puzzle narrative script (directly applicable)**
> You stand alone before the mechanism. No teammate splits off to investigate for you — but you notice three shallow marks carved on the wall, and a half-torn diary scattered on the floor. You decide to piece the fragments together yourself. (GM: please roll an investigation / Intelligence check; success grants a clue card, and collecting all three solves it.)

---

## Chapter 14　Influence Points (IP) System and Tracking

Influence Points (IP) quantify a character's bonds with the world; they have nothing to do with combat victory or defeat, only with **choices**; they determine whether the Reconciliation Ending is open, the favorability and defection of pursuable characters, and some temple / guild side-quest rewards.

### 14.1 Accumulation Table (IP granted per action)
| Action type | Influence Points (IP) gain/loss |
|---|---|
| Complete a side quest (ordinary) | +2 ~ +5 |
| Protect / save civilians or a village | +4 |
| Spare a defeated enemy (do not kill) | +3 (per enemy) |
| Choose "peaceful dialogue" with a Demon General / Demon Lord | +5 ~ +8 |
| Achieve a favorability event with a pursuable character | +3 (per character per event) |
| Successfully turn / surrender a Demon General | +10 |
| Expose a concealed truth | +2 |
| Indiscriminate killing / village slaughter / betraying companions | −5 (can lock the ending) |
| Pure combat progression (no choices) | +0 |

### 14.2 Reconciliation Ending Open Threshold
- **Total Influence Points (IP) ≥ 40** (settled before the S4 Demon Lord Castle battle begins) → Reconciliation Ending option opens.
- Influence Points (IP) 40–59: Basic reconciliation (the Demon Lord retreats, a peace treaty is signed).
- Influence Points (IP) ≥ 60: True reconciliation (all Demon Generals defect, temples reconcile, the golden "Hero's Proof" is awarded).
- Influence Points (IP) < 40: The system forcibly opens only the subjugation ending.
- Reference budget: A full playthrough can yield a max of about 70–85 Influence Points (IP); the threshold of 40 leaves room for mistakes.

### 14.3 Tracking Suggestions
The GM maintains an Influence Points (IP) tracking sheet, noting each player's choices and accumulation; it is formally settled before S4 begins, and the players are told on the spot whether the ending option is open.

### 14.4 Influence Points (IP) Spending Uses (optional rule)
Besides serving as the ending threshold and favorability indicator, Influence Points (IP) can also be exchanged at a temple or guild for "transcription scrolls" to permanently learn spells:
- **Cost**: **10 IP** per scroll (suggested value, adjusted ±2 at the GM's discretion).
- **Trade-off**: This cost is deducted directly from accumulated Influence Points (IP) and affects the Reconciliation Ending threshold (see 14.2); the player must choose between "learning a spell" and "retaining Influence Points (IP) to push for the peaceful ending."
- **Limit**: A single character may transcribe at most 1 scroll per adventure (per day), to avoid short-term overdraft of Influence Points (IP).
- **One-time scrolls** (battlefield consumables) still only cost Gold (G) and are not subject to this limit.

---

## Chapter 15　GM Toolbox

### 15.1 Hard Control Escalating Resistance
Hard control on the same target from the second consecutive time onward: Difficulty Class (DC) +4 or duration ×0.5 (choose one, take the stricter). Example: first control at DC16 succeeds; the same enemy controlled again → that attempt's Difficulty Class (DC) is treated as 20, or the original 3-round control drops to 1.5 rounds. Does not apply to "one-time control chains from different sources."

### 15.2 Critical Hit Management
Within a single combat, from the 3rd consecutive critical hit from the same source onward, critical hit damage diminishes by 20% (to avoid luck snowballing). Bosses have "critical hit resistance": when Health (HP) drops below 25%, they are immune to instant-death critical hit effects.

### 15.3 Disclosure Obligations of Choice
The GM has a disclosure obligation for "critical info that affects the main story," and may choose the timing and medium:
- Must disclose: the Demon Lord's motive, the reconciliation possibility, the Fifth's identity foreshadowing (at least hinted before S2).
- May conceal: side-quest truths, temple dark secrets (only given if players actively investigate).
- Principle: "Players may be left unaware, but must not be deceived into doing meaningless things." If a certain choice would lock the ending, sufficient foreshadowing must be given.

### 15.4 Story Pacing Control
- **Three-act anchor method**: Each chapter "hook → mid-choice → chapter-end twist."
- **Fatigue threshold**: After 2 or more consecutive combat encounters, insert a social / exploration buffer.
- **Player agency**: Use "Yes, and…" to accept player ingenuity, then layer on consequences, preserving agency.

### 15.5 Random Encounter Table (for GM improvisation)
The GM rolls d20 or chooses freely based on the current region, and consults the table below for the Challenge Rating (CR) range and encounter content; quantity and difficulty are further scaled per the Chapter 11 budget and player-count adjustment rules.

| Region / terrain | Challenge Rating (CR) range | Encounter content example (roll d6 to pick) |
|---|---|---|
| Plains | 1–8 | 1 wild wolf pack (×3) / 2 goblin scout squad (×4) / 3 wandering merchant (neutral, trade) / 4 orc warrior (×2) + wild wolf (×1) / 5 slime (×3) / 6 open and uneventful (may set trap / investigation check) |
| Forest | 1–10 | 1 goblin poisoner (×2) / 2 giant spider (×2) + web / 3 cave bat harassment (×4) / 4 frost wolf (×2) / 5 lost villager (neutral, side quest) / 6 salamander (×2) + flame breath |
| Cave | 5–15 | 1 skeleton soldier (×3) + undead aura / 2 lich servant (×1) + skeleton (×2) / 3 gargoyle (×2) / 4 crypt giant worm (×1) + acid / 5 zombie horde (×4) / 6 treasure vault (trap + loot) |
| Town | 0–5 | 1 street thug (neutral / minor brawl) / 2 mountain rat theft (×2) / 3 patrol guard (neutral, info) / 4 tavern brawl (social check) / 5 wandering merchant (trade) / 6 peaceful, nothing happens |
| Demon Realm (border) | 10–20 | 1 death knight (×1) + undead (×2) / 2 dragonborn soldier (×2) / 3 swamp golem (×1) + Bind / 4 troll (×1) + Regen / 5 ogre (×2) + frenzy / 6 Demon General vanguard (story event) |

> Usage: Towns are primarily social / trade, with combat secondary; the Demon Realm is a hardcore zone before the high-difficulty buffer. All encounters' Experience (EXP) / Gold / drops follow the corresponding entries in the Monster Compendium.
>
> If you want to upgrade an improvised encounter into a preset room-style dungeon (with traps / chests / minor bosses), see **Chapter 17 Dungeon Delve** and the **<Commission Catalog>**.

---

## Chapter 16　Optional Rules and Variants

1. **Side-by-side turns**: To speed up pacing, Initiative can be changed to alternating "full player round → full enemy round" (sacrificing individual agency for narrative advancement).
2. **Resurrection Fee variant**: High-tier resurrection may require "consuming part of memory / attributes" as a cost (e.g., −1 permanent attribute or forgetting an NPC), strengthening the weight of death (at the GM's discretion).
3. **Critical multiplier balance knob**: Default ×2.0, adjustable within 1.5~2.0 to fit party strength.
4. **Life Skill expansion**: Gathering types (Mining / Logging / Herbalism / Fishing & Hunting / Farming) and crafting types (Alchemy / Cooking / Smithing) can be expanded into a base-management gameplay, not consuming Skill Points (SP).
5. **Solo suitability patch**: No numerical patch for pure support (Dancer); only pre-disclose the trade-off; if a player insists on a solo Dancer, suggest reclassing or taking only a support role.

---

## Chapter 17　Dungeon Delve

> The dungeon is a third style of gameplay alongside "main-story Demon General battles (S1–S4)" and "improvised random encounters (15.5)": a **structured, repeatable, room-based** exploration module. Players enter it when they accept a guild commission (see the <Commission Catalog>) or explore proactively; it yields stable Experience (EXP) / Gold (G) / Influence Points (IP) / drops. This work has **no multiclass**, and dungeons also **provide no allied characters** (solo follows 13.1 adjustments).

### 17.1 What a Dungeon Is

- **Difference from main story**: The main story is a linear scenario; a dungeon is a node network of "room map," where players freely choose paths, can retreat, and can re-farm.
- **Difference from random encounters**: Random encounters are GM-improvised table rolls (15.5); a dungeon is a **pre-designed** room layout, traps, chests, and minor bosses, with a visualizable map (under `maps/`, `Dn_*.yaml` + `.svg`).
- **Structure**: One dungeon module = `劇本/Dn_*.md` (room list + rule notes) + `maps/Dn_*.yaml` (room map data) + `.svg` (visual map).

### 17.2 Dungeon Structure: Room Map

A dungeon is composed of "Room" nodes; each room has a **type** and **connections (links)**:

| Room type | Code | Content |
|----------|------|------|
| Entrance | entrance | Sole entry/exit point; retreating here means a safe escape. |
| Combat | combat | Fixed or random enemy group; searchable after clearing. |
| Trap | trap | Contains 1 mechanism (see 17.4). |
| Treasure | treasure | Contains 1 container (see 17.5). |
| Rest | rest | Safe room, can trigger Guardian Deity Grace (see 12.x). |
| Elite | elite | Fixed elite deep in the dungeon (see 17.7). |
| Exit | exit | Clearing point; leave after collecting the clear reward. |

**Fog reveal**: Unentered rooms are initially marked "?"; entering reveals the type and records it on the dungeon map. Players may choose not to enter a "?" room and retreat directly.

### 17.2b Modifying Room Count by Player Count (optional house rule)

> **This section is an optional house rule and does not alter the existing pre-made `Dn_*.yaml`.** Current map sizes scale by "dungeon tier (CR)" (D1 4×3 / 8 rooms → D8 6×5 rooms), independent of player count; this section overlays a "player-count modifier" on top of the **4-player baseline map**, so 1–6 players can all reuse the same pre-made map without redrawing the dungeon per player count.

**Core method: 4-player baseline map + player-count modifier**
- Maintain only one "4-player baseline map" per dungeon (`Dn_*.yaml` ready-made data, see 17.8).
- 1 player: cut rooms / reduce enemies per coefficient; 5–6 players: add rooms / increase enemies per coefficient; 2–4 players use the original map as the baseline band, almost unchanged.
- ⚠️ **Calibration anchor reminder**: The above coefficients use **D1 (4-player baseline map = 8 rooms)** as the calibration anchor; if applied to a high-CR dungeon (e.g., D8's 4-player baseline already reaches 18–30 rooms), converge the room count to the absolute range for the corresponding player count in master table §3 (1 player 6–7 / 4 players 8 / 6 players 12–14), or treat this coefficient as "relative scaling guidance" rather than a hard multiplier — to avoid 1 player getting 13–14 rooms and 6 players 27 rooms, deviating from the low-CR calibration.
- Difficulty is jointly regulated by §13.1 (CR / enemy multiplier) and this coefficient; **do not double-stack enemy count** — this coefficient only scales "exploration node volume," and enemy count still follows the §13.1 multiplier.

**Room count modifier coefficient table (suggested values, marked optional)**

| Players | Room modifier coefficient | Operation (based on the 4-player baseline map) | Notes |
| --- | --- | --- | --- |
| 1 (solo) | ×0.75 | Cut 25% of rooms; first cut 1–2 "non-essential side rooms" (treasure / trap side branches unrelated to main story); enemy count per combat room ×0.5 (aligned with §13.1, minimum 1) | Puzzles guaranteed solvable via clue / Intelligence (INT) checks (see 13.2.1); no allies (§8) |
| 2 | ×0.9 | Cut 1 room or keep baseline; if cutting, prioritize 1 side-quest treasure | Lower edge of baseline band |
| 3 | ×1.0 | Baseline map as-is; may slightly add 1 room (side quest) | Baseline band |
| 4 (baseline) | ×1.0 | Pre-made `Dn_*.yaml` as-is | Ready-made data |
| 5 | ×1.3 (may take ×1.3~×1.5) | Add 3–4 rooms (mostly extra combat rooms + 1 concurrency-event room) | Aligned with §13.1 concurrency events +1 |
| 6 | ×1.5 | Add 4–6 rooms (mostly extra combat rooms + 1 concurrency-event room) | Aligned with §13.1 enemy count ×1.5, concurrency +1 |

> The coefficients are [suggested values]; the GM may float them within ±0.1 based on actual play experience; the principle is "room count scales smoothly with player count, without breaking the pre-made map."

**Resource point rules (by player count)**
- **Chest count**: ≈ room count × 0.15 (round up, minimum 1). Example: 8-room baseline ≈ 1–2 chests; 12 rooms ≈ 2.
- **Rest rooms**: Each dungeon has a fixed 1 (rest type, triggers Guardian Deity Grace 12.x); plus an extra +1 by player count: 2–4 players still 1 (baseline), 5 players +1 = 2, 6 players +1 = 2 (i.e., 2 rest rooms at 6 players). Note: Original D1 has no rest room (per 17.3, rest in a "cleared combat room"); when adding rooms, prioritize adding 1 rest room for 5–6 players to continue fighting.
- **Combat position map**: Fixed 10×10 (implemented in D1/D2) or width 8–12 cells (§10.5 / §17.3), **does not scale with player count** — adding rooms only adds "exploration nodes," not "combat position cells."

**Example (based on D1 Goblin Lair 4×3 / 8 rooms)**
- **1 player**: ×0.75 → about 6 rooms. Suggested to keep Entrance + Antechamber (combat) + Sleeping Den (combat) + Throne Cavern (elite) + Exit, cut 1 treasure (Storage Cave) + 1 trap (Sacrificial Pit), combat room enemy count each ×0.5 (goblin warrior ×1, archer ×1).
- **6 players**: ×1.5 → about 12 rooms. Beyond the baseline 8 rooms, add 2 side-quest combat rooms between the antechamber / sleeping den, add 1 concurrency-event room in the mid-late section (e.g., a "captured goblin begging for mercy" social event), plus 1 more rest room, combat room enemy count ×1.5.

### 17.3 Exploration Flow (step-based)

The dungeon advances via "**exploration rounds**" (not combat rounds). Each exploration round the player party collectively performs **1 exploration action**:

1. **Move**: Move to 1 adjacent (links) and unentered room; upon entering, roll **d6 to reveal encounter**: 1–2 empty room / 3–4 combat / 5 trap / 6 chest (elite / exit rooms are fixed and not rolled).
2. **Investigate**: Search the current room (Perception-type check Difficulty Class (DC) 12~16), discover hidden doors / secret compartments / clues.
3. **Rest**: Perform in a rest room or a cleared combat room; triggers the Guardian Deity Grace active ability (once per rest), and may spend 1 Action Point (AP) to recover a small amount of Health (HP) / Mana Point (MP) (see 7.8 settlement).
4. **Retreat**: Retreat to the entrance along the explored path; loot already obtained is kept, unexplored rooms are abandoned.

> After entering a combat room, switch to the **Chapter 7 / Chapter 10** standard combat; return to exploration rounds after clearing.

> **Position combat map**: Every combat room (including minor-boss rooms) in D1 / D2 already comes with a 10×10 position combat map (YAML + SVG, same format as the S1–S4 Demon General battles, see `maps/D*_戰鬥_*.yaml`), allowing direct grid-distance and range judgments without drawing on the fly. The room map (`.yaml`) also points `combat` / `elite` rooms to the corresponding position map via the `combat_map` field.

### 17.4 Trap Rules

| Level | Detection Difficulty Class (DC) | Disarm Difficulty Class (DC) | Trigger damage |
|------|---------------------|---------------------|----------|
| Weak | 12 | 14 | 1d6 |
| Medium | 16 | 18 | 2d6 |
| Strong | 20 | 22 | 3d6 (+ possible Stun 1 round) |

- **Detection**: Dexterity (M_DEX) or Luck (M_LUK) check ≥ DC (Thief "Perception" skill can add). On failure, stepping in triggers it immediately.
- **Disarm**: After successful detection, make a Dexterity (M_DEX) check at DC+2, or use the Thief "Sleight of Hand" skill; on failure it still triggers but damage is halved (a Constitution (CON) save at Difficulty Class (DC) 12 succeeds to further reduce by 1d6).

### 17.5 Chest Rules

- **Open**: Strength (STR) lockpicking or Dexterity (M_DEX) check at Difficulty Class (DC) 12; Cleric / Thief skills can add. Failure does not damage it; retryable (interval at GM's discretion).
- **Booby trap**: 30% chance of an attached trap (refer to 17.4 Medium). Before opening, "investigate" first to lower the chance (successful investigation → booby-trap chance drops to 10%).
- **Contents**: Base materials (see Monster Compendium drops) + chance of Gold (G) + low chance of rare materials (for crafting magic gear, see Player Book Chapter 4 and the Item Compendium).

### 17.6 In-dungeon Resources and Rest

- After in-dungeon combat settlement, it does **not** auto-refill; recovery must come gradually through **rest actions** (17.3).
- Rest triggers the **Guardian Deity Grace** active ability once per rest (12.x), the core of sustained dungeon fighting.
- When resources run out, you can **retreat** (17.3) anytime to save lives; loot already obtained is not lost.
- **Town / temple rest = full recovery**: After resting once (or one night) at a town stronghold such as Alno Holy City or within the Seven Temples, the whole party's Health (HP) / Mana Point (MP) fully recovers, and resurrection can be performed (see Chapter 5 Resurrection Fee and 12.4 Temple Favorability). Whether to charge and the daily limit is at the GM's discretion (suggested: free, 1 long rest per day). Inside dungeons, this section's rules still apply; recovery can only come gradually through rest actions (17.3), and this full recovery does not apply.

### 17.7 Minor Boss (Elite)

- Located in elite rooms, CR ≈ dungeon recommended CR +3~5; applies a streamlined version of the **Boss framework (10.7)** (1 phase trait + 1 weakness).
- Defeating it always drops a "dungeon core" or key plot item (e.g., D2's "Tomb Key"), often serving as the key to clearing the dungeon or unlocking subsequent content.

### 17.8 Example Dungeon Index

| Dungeon | Recommended Rank | Theme | Minor Boss (CR) | File |
|------|-----------|------|--------------|------|
| D1 Goblin Lair | F / E (1–8) | Wild cave, low-tier resource farming | Goblin King (CR5) | 劇本/D1_哥布林巢穴.md |
| D2 Slumbering Tomb | C / D (13–18) | Undead tomb, connects to S2 necro-line | Graveyard Lich (CR18) | 劇本/D2_沉眠墓窖.md |

> Both examples include complete room maps, trap / chest configurations, and minor bosses; maps at `maps/D1_哥布林巢穴.*` and `maps/D2_沉眠墓窖.*`. The GM can use `gen_dungeon_svg.py` to generate the dungeon SVG from YAML in one click.

---

*— GM Rulebook complete (self-contained; the GM only needs to read this one document) —*
