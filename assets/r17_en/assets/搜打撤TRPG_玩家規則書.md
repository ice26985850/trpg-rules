# Search, Attack, Retreat TRPG — Player Rulebook v1.0

> **This is everything you need to know—equipment choices, skill use, and the rules of survival. The GM has their own book; you don't need to worry about encounters and world-building. Focus on one thing: get out alive.**

---

# Chapter One: Core Rules

## 1.1 Core Dice System

This game uses the **3d6 Bell Curve** as its core resolution engine. Roll three six-sided dice, add the raw Attribute value and Skill level, and compare against the Target Number.

**Base Formula:** `3d6 + Attribute + Skill ≥ Target Number (TN)`

| 3d6 ≥ | ~% | Situation |
|---|---|---|
| 4 | 98% | Almost certain success |
| 6 | 95% | Very easy |
| 8 | 84% | Easy |
| 10 | 63% | Fifty-fifty |
| 12 | 37% | Challenging |
| 14 | 16% | Hard |
| 16 | 5% | Very hard |

The middle values of the bell curve (9–12) appear most frequently, while extreme values (3, 18) are extremely rare. Attributes and Skills matter more than luck.

---

## 1.2 Five Attributes (1–10 Range)

| Attribute | Code | Meaning | Effect |
|---|---|---|---|
| **Physique (PHY)** | PHY | Strength, carry weight, health | Melee damage, Hit Points (HP), Carry Capacity |
| **Precision (PRC)** | PRC | Shooting, throwing, hand-eye coordination | Base for all ranged weapon accuracy |
| **Perception (PER)** | PER | Hearing, vision, intuition | Whether you spot the enemy first or get spotted first |
| **Tech (TEC)** | TEC | Machinery operation, medicine, explosives | Lockpicking, defusing, first aid, electronic devices |
| **Courage (CRG)** | CRG | Mental stress resistance, greed suppression | Fear suppression, retreat judgment, not fooled by bait |

**Attribute value 5 = average human baseline.** Attributes use their raw value (1–10) added directly to the dice roll.

Average character baseline (Attribute 5 + Skill 2 = +7):

| Target Number (TN) | Success Rate | Typical Check |
|---|---|---|
| 8 (Trivial) | ~100% | Hear running footsteps |
| 11 (Easy) | ~98% | Shoot a standing target, administer first aid to others |
| 14 (Medium) | ~91% | Shoot a crouching target, resist suppression |
| 17 (Hard) | ~63% | Shoot a prone target, resist fear of death |
| 20 (Very Hard) | ~26% | Long-range shooting, tactical roll |
| 23 (Epic) | ~5% | Extreme sniping |
| 26 (Near-Impossible) | <1% | Mythic-level check |

---

## 1.3 Seven-Part Independent Hit Points (HP)

Hit Points (HP) is not a single value—each body part has its own independent HP pool.

| Part | HP Formula | At Physique 5 | Hit Chance |
|---|---|---|---|
| **Head** | Physique + 6 | 11 | 5% |
| **Chest** | Physique × 2 + 10 | 20 | 35% |
| **Abdomen** | Physique + 8 | 13 | 15% |
| **Left Arm** | Physique + 4 | 9 | 12% |
| **Right Arm** | Physique + 4 | 9 | 12% |
| **Left Leg** | Physique + 5 | 10 | 10% |
| **Right Leg** | Physique + 5 | 10 | 10% |

**Effect when a Part reaches zero:**
- Head reaches zero: **Instant Death**
- Chest reaches zero: **Mortal (Near Death)**; each round requires a Courage Target Number (TN) 14 check or death
- Abdomen reaches zero: **Internal Bleeding**; lose 1 Hit Point per minute, requires emergency surgery
- Arm reaches zero: that arm becomes permanently unusable
- Leg reaches zero: Prone, unable to walk

**Hit Location Roll (d100):**

| d100 | Part | | d100 | Part |
|---|---|---|---|---|
| 01–05 | Head | | 56–67 | Left Arm |
| 06–40 | Chest | | 68–79 | Right Arm |
| 41–55 | Abdomen | | 80–90 | Left Leg |
| | | | 91–100 | Right Leg |

**Aimed Shot:** Spend 1 extra Action Point (AP) to aim at a specific part; that part's hit chance +30% (subtracted proportionally from other parts).

---

## 1.4 Derived Attributes

| Derived Attribute | Formula | Use |
|---|---|---|
| **Initiative** | Perception + Precision | Determines combat order, highest to lowest |
| **Carry Capacity** | Physique × 5 kg | Overweight halves movement |
| **Movement** | See table below | Distance moved per Action Point (AP) |
| **Initial Skill Points** | (Tech + Courage) × 2 | Allocated at character creation |

**Carry Weight and Movement:**

| Load State | Condition | Move per Action Point (AP) | Sprint (2 AP) |
|---|---|---|---|
| Light Load | ≤ Carry Capacity | 6 m | 15 m |
| Moderate Overload | > Capacity, ≤ ×1.5 | 4 m | 10 m |
| Heavy Overload | > ×1.5, ≤ ×2 | 2 m | 5 m |
| Immobile | > ×2 | 0 | 0 |

---

## 1.5 Twenty Skills System

| # | Skill | Attribute | Typical Use |
|---|---|---|---|
| **Physique Group** ||||
| 1 | Athletics | Physique | Climbing, swimming, jumping, sprinting |
| 2 | Endurance | Physique | Resist fatigue, long marches under load |
| 3 | Melee | Physique | Melee weapon attacks, grappling, shoving |
| **Precision Group** ||||
| 4 | Firearms | Precision | Pistol/rifle/shotgun shooting |
| 5 | Heavy Weapons | Precision | Machine guns, rocket launchers, anti-materiel rifles |
| 6 | Throwing | Precision | Grenades, thrown weapons |
| **Perception Group** ||||
| 7 | Awareness | Perception | Spot ambushes, search for supplies, listen |
| 8 | Stealth | Perception | Move undetected, hide |
| 9 | Tracking | Perception | Track target footprints, read environmental cues |
| 10 | Survival | Perception | Wilderness survival, identify edible food, find water |
| **Tech Group** ||||
| 11 | First Aid | Tech | Stop bleeding, stabilize wounds, use medical supplies |
| 12 | Lockpicking | Tech | Pick locks, crack mechanical safes |
| 13 | Electronics | Tech | Hacking, decoding, operating electronic devices |
| 14 | Mechanics | Tech | Repair weapons, modify attachments, operate machinery |
| 15 | Crafting | Tech | Craft ammunition, tools, simple weapons |
| **Courage Group** ||||
| 16 | Intimidation | Courage | Interrogate, intimidate enemies, suppress morale |
| 17 | Persuasion | Courage | Negotiate, bargain, build relationships |
| 18 | Willpower | Courage | Resist fear/stress, maintain sanity |
| 19 | Street Smarts | Courage | Find black markets, spot lies, underground intel |
| 20 | Leadership | Courage | Command teammates, boost morale, coordinate actions |

**Skill Level:** 0–5 (0 = Untrained, 5 = Master)

| Skill Level | Cumulative Cost |
|---|---|
| 0 | 0 points |
| 1 | 1 point |
| 2 | 3 points |
| 3 | 6 points |
| 4 | 10 points |
| 5 | 15 points |

---

## 1.6 Seven Difficulty Tiers

| Difficulty | Target Number (TN) | No Skill (Attribute 5) |
|---|---|---|
| Trivial | 8 | 84% |
| Easy | 11 | 63% |
| Medium | 14 | 16% |
| Hard | 17 | 0.5% |
| Very Hard | 20 | <0.1% |
| Epic | 23 | ~0% |
| Near-Impossible | 26 | ~0% |

---

## 1.7 Advantage and Disadvantage

### Disadvantage (4d6 drop lowest)
When the situation is unfavorable, roll **4d6 and drop the lowest 1 die** (keep the highest 3). Mean is ~8.5 (about −2 penalty).

### Double Disadvantage (5d6 drop two highest)
In extremely unfavorable situations, roll **5d6 and drop the highest 2 dice** (keep the lowest 3). Mean is ~7.0 (about −3.5 penalty).

### Advantage (4d6 take highest)
When the situation is favorable, roll **4d6 and take the highest 3**. Mean is ~12.5.

---

## 1.8 Courage System

Courage is the core signature Attribute of Search, Attack, Retreat—its dual mechanism reflects the dual threats of the Quarantine Zone.

### Fear Resistance
| Fear Level | Target Number (TN) | Trigger Example |
|---|---|---|
| Mild | 11 | Distant gunfire, discovering a corpse |
| Moderate | 14 | Teammate severely wounded, being suppressed by gunfire |
| Severe | 17 | Witnessing death, encountering a Boss |
| Extreme | 20 | Near death, facing multiple enemies alone |

**Fear Effects:**
- Success → Stay calm
- Barely (miss by 1–3) → Next round, Action Point (AP) −1
- Panic (miss by 4–6) → All actions at Disadvantage, lasts 1d3 rounds
- Freeze (miss by 7–9) → Lose 1 round
- Flee (miss by 10+) → Must move toward safety, lasts 1d3 rounds

### Greed Suppression
| Loot Value | Target Number (TN) | Failure Consequence |
|---|---|---|
| Blue item | 8 | Spend extra time searching |
| Purple item | 11 | Ignore surrounding threats |
| Gold item | 14 | Backpack items may drop |
| Legendary item | 17 | Fall into greed frenzy, unable to extract on your own |

**Stress Accumulation:** After each failed Fear or Greed check, gain 1 point of Stress. At 4 Stress points, all Courage checks are at Disadvantage. Stress resets after safely returning to the Hideout.

---

## 1.9 Push Mechanic

After failing a check, a character may choose to "Push"—risking more for a chance at success.

**Cost:** Take 1 point of Stress (or a consequence decided by the GM)
**Effect:** Reroll **1 die** of the 3d6 (of your choice), using the new result.

---

# Chapter Two: Character Creation

## 2.1 Creation Steps

### Standard Creation (7 Steps)

| Step | Content |
|---|---|
| **1. Choose Origin** | Pick one of seven Origins (§2.2) |
| **2. Allocate Attributes** | Five Attributes start at base 1; gain 25 Attribute points (§2.3) |
| **3. Allocate Skills** | Initial Skill Points = (Tech + Courage) × 2 (§2.4) |
| **4. Choose Starting Gear** | Starting weapon, armor, and funds determined by Origin (§2.5) |
| **5. Starting Hideout** | One empty room, small funding subsidy |
| **6. Choose Trader Relations** | Pick one initial contact: Arms Dealer / Medic / Information Broker |
| **7. Set Goal** | Why are you entering the Quarantine Zone? |

### 🚀 Quick Creation (3 Minutes)

| Step | Method |
|---|---|
| **1. Pick Character Type** | Assault / Sniper / Technician / Scout / Balanced / Tough Guy (pick one) |
| **2. Apply Preset Attributes** | See table below; includes Origin bonuses |
| **3. Pick 3 Main Skills** | Set to level 3, others at level 0 |
| **4. Collect Standard Gear** | Cheap pistol + 9mm×20 + heavy coat (Damage Reduction (DR) 1) + simple backpack + first aid kit×2 + 500₽ |

#### Preset Attribute Configurations

| Config | Physique | Precision | Perception | Tech | Courage | Suited For |
|---|---|---|---|---|---|---|
| Assault | 7 | 7 | 5 | 4 | 4 | Frontal firefights |
| Sniper | 4 | 8 | 7 | 4 | 5 | Long-range support |
| Technician | 4 | 5 | 5 | 8 | 6 | Lockpicking/Electronics/First Aid |
| Scout | 5 | 5 | 8 | 5 | 4 | Stealth/initiative |
| Balanced | 5 | 5 | 5 | 5 | 7 | All-round |
| Tough Guy | 8 | 4 | 5 | 3 | 7 | Tank |

---

## 2.2 Seven Origins

### A. Veteran
- Attribute bonus: Physique +2, Precision +1, Tech −1
- Starting gear: Military surplus pistol (1d8, 12 rounds), 9mm×30, worn combat boots, dog tags
- Special ability: **Tactical Acumen**—Spend 1 Action Point (AP) to assess cover Damage Reduction (DR) level and durability
- Funds: 800 ₽

### B. Debtor
- Attribute bonus: Courage +2, Perception +1, Physique −1
- Starting gear: Cheap pistol (1d6, 6 rounds), 9mm×15, forged ID, IOU note
- Special ability: **Negotiator's Instinct**—When trading, buy price −5%, sell price +5%
- Funds: 400 ₽ (debt 5,000 ₽, +5% interest after each deployment)

### C. Scavenger
- Attribute bonus: Perception +2, Tech +1, Courage −1
- Starting gear: Old shotgun (2d6, 3 rounds), 12-gauge×9, simple detector, worn backpack
- Special ability: **Keen Nose**—After entering a loot area, the GM tells you the direction of the nearest high-value target
- Funds: 600 ₽

### D. Former Corporate Employee
- Attribute bonus: Tech +2, Precision +1, Physique −1
- Starting gear: Compact pistol (1d6, 7 rounds, concealable), 9mm×24, electronic decoder, company ID
- Special ability: **Inside Knowledge**—Gain +2 Tech on corporate/electronic/security checks
- Funds: 1,200 ₽

### E. Medic
- Attribute bonus: Tech +2, Courage +1, Precision −1
- Starting gear: Small pistol (1d6, 7 rounds), 9mm×12, first aid kit×3 (restores 1d6+2 Hit Points), tourniquet×2
- Special ability: **Battlefield First Aid**—Medical item recovery +2; can stabilize a severely wounded character (Tech Target Number (TN) 12)
- Funds: 700 ₽

### F. Mutant Adapted
- Attribute bonus: Physique +2, Courage +2, Tech −2
- Starting gear: Crowbar (1d6+Physique), heavy coat (Damage Reduction (DR) 1), emergency meds×1
- Special ability: **Adaptive Mutation**—Poison/radiation/biochemical Damage Reduction 2; once per day sense anomalous signals
- Funds: 300 ₽

### G. Border Dweller
- Attribute bonus: Perception +2, Courage +1, Tech −1
- Starting gear: Homemade pistol (1d6, 6 rounds, malfunction rate 1/8), 9mm×18, hand-drawn map, animal trap×1
- Special ability: **Old Hand at the Trail**—Can enter through hidden entrances; spend 10 minutes to find a backup Extraction route (Tech Target Number (TN) 10)
- Funds: 500 ₽

### Origin Quick Reference

| Origin | Physique | Precision | Perception | Tech | Courage | Funds | Core Highlight |
|---|---|---|---|---|---|---|---|
| Veteran | +2 | +1 | — | −1 | — | 800 | Dog tags, tactical assessment |
| Debtor | −1 | — | +1 | — | +2 | 400 | Negotiation bonus, debt |
| Scavenger | — | — | +2 | +1 | −1 | 600 | Detector, nose |
| Former Corporate Employee | −1 | +1 | — | +2 | — | 1,200 | Decoder, inside knowledge |
| Medic | — | −1 | — | +2 | +1 | 700 | First Aid×3, battlefield first aid |
| Mutant Adapted | +2 | — | — | −2 | +2 | 300 | Mutation resistance, anomaly sense |
| Border Dweller | — | — | +2 | −1 | +1 | 500 | Map, hidden entrance |

---

## 2.3 Attribute Allocation

All starting Attributes begin at **1**, with **25 points** to allocate:

| Attribute Value | Cost |
|---|---|
| 1 → 2–5 | 1 point/level |
| 5 → 6–10 | 2 points/level |
| Reaching 10 | Total cost 14 points |

Origin bonuses do not count toward point cost.

---

## 2.4 Skill Allocation

**Initial Skill Points = (Tech + Courage) × 2**

Use **post-creation Attribute values** (including Origin bonuses) when calculating.

Examples:
- Scavenger (Tech 6 + Courage 4) = 20 Skill Points
- Veteran (Tech 4 + Courage 5) = 18 Skill Points
- Former Corporate Employee (Tech 7 + Courage 5) = 24 Skill Points

Initial maximum Skill level is 3. See §1.5 for Skill Point costs.

---

## 2.5 Equipment System Basics

### Equipment Slots

| Slot | Equippable | On Death |
|---|---|---|
| Primary Weapon | Rifle/shotgun/SMG/sniper | Lost (unless insured) |
| Secondary Weapon | Pistol/melee weapon | Lost |
| Head | Helmet/gas mask/night vision | Lost |
| Torso | Body Armor/tactical vest | Lost |
| Backpack | Determines Carry Capacity and loot capacity | Lost |
| Pockets ×4 | Small items, keys, medicine | Lost |
| Security Case | 2 slots, not lost on death | ⭕ Retained |

### Loot Slots
Loot Slots = 4 (pockets) + Tactical Vest (+2~+10) + Backpack (+1~+8) + Security Case (2)

| Combination | Total Slots |
|---|---|
| Minimum (waist bag + worn backpack) | 7 |
| Standard (tactical vest + simple backpack) | 13 |
| Full load (heavy vest + military backpack) | 17 |
| Extreme (assault vest + large gear bag) | 22 |

### Loot Tiers

| Tier | Color | Volume Each | Market Value | Example |
|---|---|---|---|---|
| Junk | Gray | 1 slot | 10–100 ₽ | Rags, empty cans |
| Common | White | 1 slot | 100–500 ₽ | Ammo, basic medical supplies |
| Rare | Blue | 1–2 slots | 500–3,000 ₽ | Weapon attachments, electronic parts |
| Military | Purple | 2–3 slots | 3,000–15,000 ₽ | Military equipment, high-grade drugs |
| Legendary | Gold | 2–4 slots | 15,000+ ₽ | Prototype weapons, rare keys |

---

## 2.6 Equipment Catalog (full data in the compendium)

▶ For complete data on weapons, armor, consumables, and loot (base + expansion, full tables), see **assets/物品圖鑑.md**.
## 2.9 Progression System

### Experience Points (XP) Gain

| Event | XP |
|---|---|
| Successful Extraction | +100 |
| Complete Commission | +50 ~ +300 |
| Discover new location | +25 |
| Defeat elite enemy | +30 ~ +80 |
| Extract with Blue/Purple/Gold items | +10/+25/+50 (per item) |
| Death (for inheritance) | +20 |

### Level Table (10-Level)

| Level | Total XP | Reward |
|---|---|---|
| 1 | 0 | Start |
| 2 | 300 | +1 Attribute |
| 3 | 700 | Feat ×1 |
| 4 | 1,200 | +1 Attribute |
| 5 | 2,000 | Feat ×1, Hideout level 3 unlocked |
| 6 | 3,000 | +1 Attribute |
| 7 | 4,500 | Feat ×1 |
| 8 | 6,500 | +1 Attribute |
| 9 | 9,000 | Feat ×1 |
| 10 | 12,000 | +2 Attribute, Legendary privilege |

---

## 2.10 Feats List (15)

| # | Feat | Effect |
|---|---|---|
| 1 | Iron Stomach | Can eat expired/contaminated food without getting sick |
| 2 | Quick Hands | Once per round, reloading counts as a free action (no Action Point (AP) cost) |
| 3 | Tough Guy | When any part's Hit Points (HP) ≤ 25%, that part's DR +1 |
| 4 | Eagle Eye | Awareness sight range +20m |
| 5 | Demolition Expert | +1d6 damage when using explosives |
| 6 | Mental Resistance | Gain Advantage (4d6 take highest) on Fear checks |
| 7 | Backpacker | Carry Capacity +10 kg |
| 8 | Light-Fingered | Roll 1 extra die and take the highest when searching for supplies |
| 9 | Steady Shooting | No Disadvantage on shooting checks while suppressed |
| 10 | First Aid Specialist | +1d6 recovery when using medical items |
| 11 | Stalker | No movement slowdown while stealthing |
| 12 | Master Negotiator | Extra −5% buy price, extra +5% sell price when trading |
| 13 | Weapon Specialist | Choose one weapon type; damage rolls gain Advantage (take highest) |
| 14 | Survival Instinct | Once per day, when Head/Chest reaches zero, instead drop to 1 Hit Point |
| 15 | Sixth Sense | GM gives a vague warning when entering an ambush range |

---

## 2.11 Insurance Mechanism

| Vault Level | Premium Rate | Insurable Items | Payout Ratio | Payout Delay |
|---|---|---|---|---|
| Level 1 | 25% | 2 | 60% | After 2 deployments |
| Level 2 | 25% | 3 | 70% | After 2 deployments |
| Level 3 | 20% | 4 | 70% | After 1 deployment |
| Level 4 | 15% | 5 | 80% | After 1 deployment |
| Level 5 | 10% | 6 | 100% (optional item return or full refund) | Instant |

- Premium rate ×2 when insuring Gold items
- Payout can be funds (market price × payout ratio) or, at level 3+, an equivalent substitute item

---

## 2.12 Death and Inheritance

### Losses on Death
- All equipped gear lost (unless insured)
- All loot from that run lost
- Character permanently dies

### Inheritance Rules (gained by new character)
- Hideout facilities: **100%** retained
- Weapons stored in Armory: **100%** retained
- Hideout funds: **80%** (20% handling fee)
- Trader favor: **50%** (rounded down)
- Experience: 30% converted to extra Attribute points (every 500 XP = 1 point)
- Previous character's insurance payout: **100%** transferred to vault

---

## 2.13 Hideout Management

### Six Facilities Overview

| Facility | Level 1 Effect | Level 3 Effect | Level 5 Effect | Total Cost (Level 5) |
|---|---|---|---|---|
| Armory | Store 3 weapons | Store 15 weapons, full mods | Unlimited, repair cost −50%, legendary mods | 149,500 ₽ |
| Infirmary | 1 HP per day | 4 HP per day, surgery possible | 6 HP per day, biochemical treatment | 115,000 ₽ |
| Workbench | Disassemble weapons | Craft 7.62/.45, blue attachments | Repair −80%, copy gold attachments | 170,000 ₽ |
| Intelligence Center | 3 Commissions, basic map | Hidden Extraction Points ×2, high-tier Commissions | Gold Commissions, full dynamic map intel | 170,500 ₽ |
| Trading Post | Passive income | Buy −10%/sell +5% | Buy −25%/sell +20%, all Gold unlocked | 136,000 ₽ |
| Vault | Insure 2 items / 25% premium | Insure 4 items / 20% premium | Insure 6 items / 10% premium, instant payout | 205,000 ₽ |

**Total investment for all facilities at level 5: 946,000 ₽**

### Armory (by level)

| Level | Cost | Effect | Required Level |
|---|---|---|---|
| Level 0 | — | No storage space | 1 |
| Level 1 | 1,500 ₽ | Store 3 items; can clean weapons (malfunction rate −1 tier, once per deployment) | 1 |
| Level 2 | 8,000 ₽ | Store 8 items; swap basic attachments; repair cost −10% | 2 |
| Level 3 | 25,000 ₽ | Store 15 items; full mod bench (blue attachments); repair cost −25% | 5 |
| Level 4 | 45,000 ₽ | Store 30 items; install purple attachments; weapon durability cap +20% | 6 |
| Level 5 | 70,000 ₽ | Unlimited storage; legendary mods; repair cost −50% | 8 |

### Infirmary (by level)

| Level | Cost | Effect | Required Level |
|---|---|---|---|
| Level 0 | — | No medical facilities | 1 |
| Level 1 | 1,000 ₽ | Recover 1 Hit Point per day | 1 |
| Level 2 | 6,000 ₽ | Recover 2 HP per day; infection treatment (free); recovery time −25% | 2 |
| Level 3 | 18,000 ₽ | Recover 4 HP per day; surgery to remove permanent limb injury (Tech Target Number (TN) 14); recovery time −40% | 4 |
| Level 4 | 35,000 ₽ | Recover 5 HP per day; radiation cleansing (once between deployments); recovery time −60% | 6 |
| Level 5 | 55,000 ₽ | Recover 6 HP per day; biochemical treatment; remove all permanent injuries (Tech Target Number (TN) 11); recovery time −80% | 8 |

### Workbench (by level)

| Level | Cost | Effect | Required Level |
|---|---|---|---|
| Level 0 | — | Cannot craft or repair | 1 |
| Level 1 | 3,000 ₽ | Disassemble weapons for parts; simple repair (restore 10 durability) | 2 |
| Level 2 | 12,000 ₽ | Craft 9mm/12-gauge ammo (material cost = 60% of market); repair 20 durability | 3 |
| Level 3 | 30,000 ₽ | Craft 7.62/5.56 ammo; craft blue attachments; repair 40 durability | 5 |
| Level 4 | 50,000 ₽ | Craft armor-piercing ammo (material cost 50%); craft purple attachments; weapon upgrade (+1 armor-piercing or durability cap) | 7 |
| Level 5 | 75,000 ₽ | Craft all ammo (material cost 40%); copy gold attachments; repair cost −80% | 9 |

### Intelligence Center (by level)

| Level | Cost | Effect | Required Level |
|---|---|---|---|
| Level 0 | — | 1–2 basic Commissions | 1 |
| Level 1 | 2,500 ₽ | Accept 3 Commissions (Simple~Regular); unlock basic map | 1 |
| Level 2 | 10,000 ₽ | Accept 4 Commissions (incl. Hard); unlock 1 hidden Entry Point; Pulse Surge warning | 3 |
| Level 3 | 28,000 ₽ | Accept 5 Commissions (incl. Extreme); unlock 2 hidden Extraction Points; full regional map | 5 |
| Level 4 | 50,000 ₽ | Accept 6 Commissions; full Quarantine Zone map; predict faction movements (1 per day) | 7 |
| Level 5 | 80,000 ₽ | Gold Commissions unlocked; full dynamic map intel; real-time tracking of any target | 9 |

### Trading Post (by level)

| Level | Cost | Effect | Required Level |
|---|---|---|---|
| Level 0 | — | Basic trading (full price), only Gray/White goods | 1 |
| Level 1 | 1,000 ₽ | List items to sell (Gray items ×1d3 passive income per deployment interval) | 1 |
| Level 2 | 5,000 ₽ | Buy −5%; unlock Blue goods | 2 |
| Level 3 | 20,000 ₽ | Buy −10%, sell +5%; unlock Purple goods | 4 |
| Level 4 | 45,000 ₽ | Buy −15%, sell +10%; random Gold goods (1 per 3 deployments) | 6 |
| Level 5 | 65,000 ₽ | Buy −25%, sell +20%; all Gold goods unlocked | 8 |

### Vault (by level)

| Level | Cost | Premium Rate | Insurable Items | Payout Ratio | Payout Delay |
|---|---|---|---|---|---|
| Level 0 | — | — | 0 | — | — |
| Level 1 | 5,000 ₽ | 25% | 2 | 60% | After 2 deployments |
| Level 2 | 15,000 ₽ | 25% | 3 | 70% | After 2 deployments |
| Level 3 | 35,000 ₽ | 20% | 4 | 70% | After 1 deployment |
| Level 4 | 60,000 ₽ | 15% | 5 | 80% | After 1 deployment |
| Level 5 | 90,000 ₽ | 10% | 6 | 100% | Instant |

> **Suggested investment order:** Infirmary Level 1 (1,000₽) → Trading Post Level 1 (1,000₽) → Intelligence Center Level 2 (12,500₽ cumulative) → Armory Level 2 (9,500₽ cumulative) → Vault Level 1 (5,000₽)

---

## 2.14 Trader Relations

| Trader | Nickname | Goods | Buyback Preference |
|---|---|---|---|
| Arms Dealer | "The Blacksmith" | Weapons, ammo, attachments, armor | Weapons, military parts |
| Medic | "The Doctor" | Medical supplies, biochemical protection, mutation-related | Rare drugs, samples |
| Information Broker | "Owl" | Maps, keys, commissions, extraction points | Encrypted data, Boss intel |

**Favor Levels:**

| Level | Favor | Effect |
|---|---|---|
| Level 1 Stranger | 0 | Basic trading |
| Level 2 Regular | 100 | Buy −5%, unlock Blue goods |
| Level 3 Partner | 300 | Buy −10%, sell +5%, unlock Purple |
| Level 4 VIP | 600 | Buy −15%, sell +10%, random Gold |
| Level 5 Close Friend | 1,200 | Buy −20%, sell +15%, all Gold + exclusive services |

> **Reputation deepening rewards (specific services at Worship Tier for each faction): see GM Rulebook §3.9 or `搜打撤TRPG_規則修補包_v1.0.md` Fix 4.**

---

## 2.15 Rest Phase (between deployments)

After each deployment, enter the Rest Phase. You may perform **3 Rest Actions**:

| Action | Effect |
|---|---|
| **Training** | Pick a skill; 3d6+Attribute≥14 → gain training progress |
| **Gather Intel** | 3d6+Tech≥Target Number (TN) → gain extra intel on next deployment |
| **Socializing** | 3d6+Courage+Persuasion≥11 → Trader favor +1d10 |
| **Crafting Items** | See Crafting System (GM Rulebook) |
| **Equipment Maintenance** | Restore weapon durability 5+(Armory level×5) |
| **Market Trading** | List items to sell, chance to sell at high price |
| **Rest and Relax** | Remove 1d3 Stress (Infirmary level 3+ → 2d3) |
| **Hideout Upgrade** | Pay to upgrade facilities |

> **Full Rest system including random event table: see GM Rulebook or `搜打撤TRPG_規則修補包_v1.0.md` Fix 1.**

---

# Chapter Three: Combat Quick Reference (Player Version)

## 3.1 Action Point (AP) Quick Reference

Each character has **2 Action Points (AP)** per round:

| Cost | Action |
|---|---|
| **0 Action Point (AP)** | Speak, drop item, turn head to observe |
| **1 Action Point (AP)** | Single shot, reload magazine, move, crouch, first aid, aim |
| **2 Action Points (AP)** | Full-auto spray, sprint, loot corpse, go prone/stand up |

You may reserve 1 Action Point (AP) for Reactions (opportunity attack, tactical roll, cover transfer, suppression response).

---

## 3.2 Shooting Modifiers Quick Reference

**Hit Formula:** 3d6 + Precision + Firearms Skill ≥ Target Defense

### Target State
| State | Attacker Effect |
|---|---|
| Standing, open ground | Target Number (TN) 11 (Easy) |
| Crouching | **Disadvantage** (4d6 drop lowest) |
| Prone | **Double Disadvantage** (5d6 drop two highest) |
| Behind light cover | Disadvantage |
| Behind half cover | Disadvantage + cover Damage Reduction (DR) 2 |
| Behind full cover | Double Disadvantage + cover Damage Reduction (DR) 4 |

### Range Modifier
| Distance | Pistol | SMG | Rifle | Shotgun | Sniper |
|---|---|---|---|---|---|
| Point-blank (0–2m) | 0 | −1 | −1 | 0 | −1 |
| Close (3–15m) | 0 | 0 | 0 | 0 | −1 |
| Medium (16–50m) | Disadvantage | −1 | 0 | Disadvantage | 0 |
| Far (51–200m) | Double Disadvantage | Disadvantage | −1 | — | 0 |
| Extreme (200m+) | — | — | −2 | — | −1 |

### Fire Mode
| Mode | Action Point (AP) | Ammo | Hit | Damage | Extra Effect |
|---|---|---|---|---|---|
| Semi-auto | 1 | 1 | Normal | Base | — |
| Double-tap | 1 | 2 | −1 | Base+1 | — |
| Burst | 2 | 3 | −1 | Base+1d4 | — |
| Full-auto | 2 | 5 | −2 | Base+2d4 | **Suppression** (Courage Target Number (TN) 14 within range) |

---

## 3.3 Melee Quick Reference

**Melee Check:** 3d6 + Physique + Melee Skill ≥ Target DV (8 + Target Physique)

| Modifier | Effect |
|---|---|
| Target caught off guard | +2 |
| Target already wounded | +1 |
| Target prone | +2 |

---

## 3.4 Posture and Cover Stacking

| Posture | Enter AP | When Hit | Own Shooting | Move |
|---|---|---|---|---|
| Standing | 0 | Normal | Normal | Normal |
| Crouching | 1 | Attacker at Disadvantage | Normal | Halved |
| Prone | 2 | Attacker at Double Disadvantage | Disadvantage (without bipod) | Crawl 2m/AP |

---

## 3.5 Status Effects Quick Reference

| Status | Trigger | Effect |
|---|---|---|
| Bleeding (Light) | Piercing/slashing damage | −1 Hit Point per round |
| Bleeding (Heavy) | Artery damaged | −1d4 Hit Points per round |
| Fracture | Part Hit Points (HP) ≤ 25% | Cannot use that part |
| Shock | Part destroyed | Courage Target Number (TN) 14 or lose 1 round |
| Suppressed | Failed by suppression fire | Action Point (AP) −1 + Disadvantage on all actions |
| Poisoned | Toxin contact | −1d4 Hit Points per round, lasts 1d6 rounds |

---

## 3.6 Weapon Malfunction

Use **3d6 ≤ malfunction threshold** to determine:

| Weapon Condition | Malfunction Threshold | Malfunction Rate |
|---|---|---|
| Brand new/reliable | 4 | ~2% |
| Normal | 6 | ~5% |
| Old | 8 | ~16% |
| Homemade/damaged | 9–10 | ~26–37% |

---

## 3.7 Independent Part Armor Tracking

Each part independently records its Damage Reduction (DR):

| Armor Type | Protected Parts |
|---|---|
| Helmet | Head only |
| Body Armor | Chest + Abdomen |
| Tactical Vest | Chest + Abdomen (stacks with Body Armor) |
| Gloves/arm guards | Both arms (Damage Reduction (DR) 1, White, 600₽) |
| Knee pads/combat boots | Both legs (Damage Reduction (DR) 1, White, 500₽) |
| Full-body heavy armor | All parts |

**Damage Reduction (DR) cannot stack beyond 6.**

## 3.8 Dual-Wielding

Only **pistols** and **one-handed melee** weapons:

| Mode | Action Point (AP) | Effect |
|---|---|---|
| Dual Pistol Volley | 2 | Two shots at same target, −2 to hit each |
| Alternating Fire | 1+1 | One different pistol per AP, −1 to hit each |
| Gun-Sword Combo | 1+1 | One hand shoots (−1 to hit), other hand melee (normal) |

## 3.9 Prone and Getting Up

| State | When Shot | Own Attack | Move | Get Up |
|---|---|---|---|---|
| Prone | Attacker at Double Disadvantage | Disadvantage | Crawl 2m/AP | **1 Action Point (AP)** |

## 3.10 Friendly Fire

| Situation | Friendly Fire Chance |
|---|---|
| Full-auto spray crossing teammate | 3d6 ≤ 9 (~26%) |
| Burst crossing teammate | 3d6 ≤ 6 (~5%) |
| Teammate and target in same melee square | 50% hit teammate after a hit |

## 3.11 Grenade Scatter

Throwing: 3d6 + Precision + Throwing ≥ Target Number (TN). On failure, deviates 1d6~2d6 m (direction d8).

## 3.12 Ammo Pickup

| Enemy | Ammo Available |
|---|---|
| Newbie/Scavenger | 9mm × 1d12 |
| Warlord Soldier | 5.56 × 2d8 + 9mm × 1d6 |
| Lone Wolf Veteran | 7.62 × 1d8 |
| Elite/Boss | 5.56 × 3d10 + special ammo 1d4 |

Some magazines are retained; two half magazines can be combined (1 Action Point AP).

---

> **You now know everything needed to survive. Remember: the gear you bring in is a bargaining chip—getting out alive is the victory. The choice is in your hands.**
