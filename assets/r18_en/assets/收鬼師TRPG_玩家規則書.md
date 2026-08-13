# Ghost Collector TRPG · Player Rulebook

> You are no Taoist priest, and no hero. You are simply someone hired to deal with the things the police can't handle and the hospitals can't explain.
> The phone rings. Another case.
>
> Design credits: Character System — Ke Jiao Ling ｜ Worldbuilding — Jing Shi Wen ｜ Combat Design — Zhan Zhi Ge ｜ Dice Mechanics — Bi Shou An ｜ Lead Designer — Cheng Gui Yao

---

## Cover & Introduction

### What Is *Ghost Collector*

*Ghost Collector* is a supernatural-investigation TRPG (tabletop role-playing game) set in **contemporary Hong Kong and the Lingnan geo-cultural sphere**. You play a "Ghost Collector" — a gray-area professional who makes a living handling paranormal commissions. On the street they are called "Master" or "Feng Shui Gentleman"; officially, the Guild registers them as "Folk Custom Consultants."

This is not a monster-slaying, level-grinding game. Ghost Collectors take cases over WhatsApp, find haunted houses via Google Maps, and use a flashlight to catch the cinnabar glint on a talisman. Spells are not magical-girl special effects, but **tools**: opening an altar takes time, drawing talismans takes materials, and chanting incantations drains your Mana Pool (MP).

### Core Philosophy

- **Haunted Tong Lau**: A six-story walk-up with no elevator, rusted iron gates, and stairwells plastered with yellowing talisman paper. Bound Spirits love to repeat their pre-death behaviors on the stairs and in the airwell; the tomb-like silence is more terrifying than any scream.
- **Zombie Mortuary**: The funeral home's AC is cranked too high; you sneeze as you draw talismans, and the mortuary's drawers sense something before you do. A freshly dead person who died with eyes unclosed is most prone to corpse mutation.
- **The phone rings, another case**: Collecting ghosts is not a relentless battle, but a rhythm of "Investigate → Prepare → Dispose." Judging *whether you should fight* always matters more than *whether you can win*. For many cases, if you can talk it through, there is no need to fight; if talk fails, then subdue or deliver.

Core tone: **The last words a departed soul whispers in your ear are often not "save me," but "help me post a letter to my ma."**

### Solo Mode Notes

All mechanics in this rulebook are designed so it can be played in full with **1 player + 1 GM (Host)**:

- In solo mode, the overall Difficulty Class (DC) is lowered by 1–2 points, compensating for the lack of teammates' aid.
- Enemy Challenge Rating (CR) −1 (minimum 0).
- The Difficulty Class (DC) for first aid after collapsing drops to 10, giving you a more forgiving recovery window.
- The sense of isolation is precisely the selling point of solo mode — the entire tong lau holds only you and a single unclosed-eye spirit, a pressure that a multi-player group can rarely replicate.

The GM will also more proactively hand you clues discoverable through Intuition (INS) or Knowledge (KNW) checks, so you do not get stuck alone.

---

## Chapter One · Attributes & Character Basics

### 1-1 The Five Attributes

A character is defined by five attributes, each with a value between 1–10. At character creation you have **25 points** to distribute (see Chapter Six), each attribute at least 1, and **at least one attribute at 6 or above**.

| Attribute (Full Name) | Abbr. | Meaning |
|---|---|---|
| Prowess | PHS | Physique, reflexes, melee |
| Dao Attainment | DOW | Spell cultivation, talisman potency, lineage depth |
| Intuition | INS | Perceiving the supernatural, communing with spirits |
| Knowledge | KNW | Folkloric learning, funeral customs, spirit classification |
| Composure | CMP | Mental endurance, willpower, Yin resistance |

### 1-2 Attribute Modifier

All checks use the **Attribute Modifier (Attr Mod)**, with the formula:

```
Attribute Modifier = FLOOR((Attribute Value − 5) / 2)
```

| Attribute Value | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 |
|---|---|---|---|---|---|---|---|---|---|---|
| Modifier | −2 | −2 | −1 | −1 | 0 | 0 | +1 | +1 | +2 | +2 |

Example: Prowess (PHS) 8 → FLOOR((8−5)/2) = +1; Composure (CMP) 4 → FLOOR((4−5)/2) = −1.

### 1-3 Derived Attributes

Derived attributes are calculated from the five attributes, per the formulas below (with worked examples, using the character "A-Yao": Prowess 3 / Dao Attainment 8 / Intuition 4 / Knowledge 6 / Composure 4, Level 1):

| Derived Value (Full Name) | Abbr. | Calculation | A-Yao Example |
|---|---|---|---|
| Health Points | Health Points (HP) | `Prowess (PHS) × 3 + 10 + (Level − 1) × 2` | 3×3+10+0 = **19** |
| Mana Pool | Mana Pool (MP) | `Dao Attainment (DOW) × 3 + 5 + (Level − 1) × 2` | 8×3+5+0 = **29** (class bonus added later) |
| Yin Value | Yin Value (YIN) | Starts at 0, accumulates dynamically (from environment and contact) | **0** |
| Yin Threshold | Yin Threshold (YT) | `Composure (CMP) × 2 + Dao Attainment (DOW)` | 4×2+8 = **16** |
| Perception Range | Perception Range (PR) | `Intuition (INS) × 5` (meters) | 4×5 = **20 m** |
| Possession Resistance | Possession Resistance (PRZ) | `Composure (CMP) modifier` | **−1** |

**Notes:**

- **Health Points (HP)**: The upper limit of physical and paranormal damage you can endure. Reaching zero means unconsciousness.
- **Mana Pool (MP)**: Energy for casting spells and drawing talismans. Once depleted you cannot cast; requires rest (recovers Dao Attainment (DOW) points per hour, or fully recovers after complete sleep).
- **Yin Value (YIN)**: Yin contamination accumulated on you or in the environment. Environmental Yin Value (YIN) and personal Yin are tracked separately.
- **Yin Threshold (YT)**: The maximum personal Yin you can withstand. Once your personal Yin Value (YIN) **exceeds the Yin Threshold (YT)**, every point over imposes −1 on relevant checks (those concerning Yin / spirits / the supernatural), until you leave the Yin environment and rest.
- **Perception Range (PR)**: The distance at which you can perceive spirits (Intuition (INS) × 5 meters). Spirits beyond this range appear to you only as silhouettes.
- **Possession Resistance (PRZ)**: A bonus to resist possession and corpse-poison, equal to your Composure (CMP) modifier.

**Yin Environment Effects (perceptible by players):** The higher the environmental Yin Value (YIN), the more dangerous it is —

| Environmental Yin Value (YIN) | State | Effects You Will Feel |
|---|---|---|
| 0–2 | Normal | No effect |
| 3–5 | Light Yin | Your Intuition (INS)-related checks gain Advantage (roll twice, take higher) |
| 6–10 | Yin Chill | Each round you must pass a Composure (CMP) check (Difficulty Class (DC) 12); on failure, environmental Yin +1 |
| 11–15 | Extreme Yin | All your actions fall under Disadvantage (roll twice, take lower); requires Warding protection |
| 16+ | Dead Zone | Each round forces a Composure (CMP) check (Difficulty Class (DC) 15); two consecutive failures → Assimilated by Yin (Possession or unconsciousness) |

### 1-4 Skill System

Skills belong to the five attributes, with levels: **0 Untrained / 1 Proficient / 2 Expert / 3 Grandmaster**. Skill level is added directly to your check total.

| Parent Attribute | Skills (22 total) |
|---|---|
| Prowess (PHS) | Melee Combat, Dodge, Climb, Stealth, Tracking |
| Dao Attainment (DOW) | Talisman Drawing, Incantation, Hand Seals, Altar Opening, Warding |
| Intuition (INS) | Spirit Perception, Communication, Yin Perception, Intuition |
| Knowledge (KNW) | Folklore, Lineage Knowledge, Appraisal, Documentation |
| Composure (CMP) | Will, Fear Resistance, Calm, Poison Resistance |

> Untrained (level 0) skills can still perform a "pure attribute check" (using only the attribute modifier, no skill bonus); but some professional actions (such as Altar Opening, Talisman Drawing, or operating spirit tools) require skill ≥ 1 to perform.

---

## Chapter Two · Resolution Mechanics (Player View)

### 2-1 Basic Check Formula

When you need to attempt a challenging action, the GM will ask you to roll a check. The main die is the **1d20 (twenty-sided die)**:

```
1d20 + Attribute Modifier + Skill Level + Circumstance Bonus ≥ Difficulty Class (DC)  →  Success
```

- **Attribute Modifier**: See Chapter One, 1-2.
- **Skill Level**: 0–3, added directly.
- **Circumstance Bonus**: Granted by the GM for items or environment, capped at +2 per instance (usually 0 in solo mode).

Example: You use Dao Attainment (DOW) + Talisman Drawing (level 2) to draw an Exorcism Talisman on the spot, Difficulty Class (DC) 12. Dao Attainment 8 modifier +1, skill +2, total bonus +3. Roll a 10 → 10+3 = 13 ≥ 12, success.

### 2-2 Critical Success & Critical Failure

- **Critical Success**: Roll a natural 20, and total ≥ Difficulty Class (DC). Indicates an exceptional success and triggers an extra effect.
- **Critical Failure**: Roll a natural 1. The check automatically fails, and may trigger a complication.

**Critical Success Extra Effect (attack / damage-type checks):** Damage dice auto-double (e.g., Peachwood Sword 1d6 → 2d6; Thunder-Struck Wood 2d6 → 4d6; Burn 1d4 per round → 2d4).

**Critical Success Extra Effect (non-damage checks, GM picks one):**
1. **Doubled Talisman**: This talisman or rite's effect doubles (e.g., Exorcism Talisman Burn lasts longer, subdue check gets extra +5).
2. **Instant Paralysis**: Pin / Melee roll of 20; zombie is immediately paralyzed for 1 round.
3. **Spirit Speech**: Communication / Spirit Perception roll of 20; the spirit voluntarily reveals one key piece of intel (such as cause of death or weakness).
4. **Effortless Casting**: Altar Opening / Rite roll of 20; this Mana Pool (MP) cost is halved, Warding stability +1.
5. **Victory from Danger**: Roll of 20 in an Extreme Yin / Dead Zone environment; this check ignores Yin Disadvantage, and clears 1 point of personal Yin Value (YIN).

**Critical Failure Complications (GM picks one or rolls):**
1. **Ruined Talisman**: Roll of 1 while drawing; the talisman fails, wasting materials and the Mana Pool (MP) already invested.
2. **Mana Backlash**: Roll of 1 while casting; lose 1d4 Mana Pool (MP), and related checks next round fall under Disadvantage.
3. **Disturbed Spirit**: Roll of 1 on Communication / Stealth; the spirit is startled, turns hostile or acts early (Initiative +5).
4. **Yin Surge**: Roll of 1 in a Yin environment; surrounding environmental Yin Value (YIN) +2, possibly raising the environmental effect by one tier.
5. **Possession Crack**: Roll of 1 on a Composure (CMP)-related check; Possession Resistance (PRZ) temporarily −2 until next rest.

### 2-3 Contest Check

When you vie with a spirit or another person (such as a subdue contest, or negotiation), each side rolls `1d20 + their own bonus` and compares totals. Ties are usually adjudicated by the GM (defender's success counted). A spirit's resistance uses Challenge Rating (CR) × 2 as its bonus.

### 2-4 Advantage & Disadvantage

- **Advantage**: Roll twice, take higher. The higher roll counts.
- **Disadvantage**: Roll twice, take lower.

**Yin environments create advantage/disadvantage:** In Light Yin (environmental Yin Value (YIN) 3–5), your Intuition (INS)-related checks gain Advantage; in Extreme Yin (11–15), all your actions fall under Disadvantage; in the Dead Zone (16+), your sanity is threatened every round. This is exactly the design tension of "Yin Energy is both aid and obstacle" — know the environment, and you can seek fortune and avoid misfortune.

### 2-5 Difficulty Class (DC) Tier Names

The GM uses the Difficulty Class (DC) to represent the target value of an action's challenge. The seven tiers are:

| Tier Name | Description |
|---|---|
| Trivial | Almost anyone can do it, easily picked up. |
| Simple | Slight threshold, but doable with a little preparation. |
| Ordinary | Standard challenge, requiring the corresponding ability to be safe. |
| Hard | Not easily achieved; requires expertise or good preparation. |
| Very Hard | Very high threshold, often accompanied by risk and pressure. |
| Legendary | A feat only rare masters can attempt. |
| Miracle | Nearly heaven-defying, usually requiring preparation, items, or team effort. |

> In solo mode, the GM lowers the overall Difficulty Class (DC) by 1–2 points to compensate for the lack of teammate aid.

---

## Chapter Three · Lineages & Classes

### 3-1 The Five Lineages (Tradition Source, treated as Origin)

Lineage determines your starting skills and passive bonuses, and is not locked to class — any lineage can pair with any class.

| Lineage | Attribute Bias (example) | Bonus | Signature Spell | Restriction / Weakness |
|---|---|---|---|---|
| **Maoshan** | High Dao Attainment (DOW), mid Knowledge (KNW) | ① Talisman Drawing (DOW) starts at level 1; ② all talisman effects +1; ③ Altar Opening (DOW) check +1 | Corpse-Still Talisman, Five-Thunder Palm | Strict precepts: after using forbidden arts, Composure (CMP)-related checks −2; low Prowess (PHS) needs shoring up |
| **Liuren** | High Composure (CMP), mid Dao Attainment (DOW) | ① resting 1 hour recovers Dao Attainment (DOW) ×2 Mana Pool (MP); ② "Iron-Plate Soul-Hiding": once per day, turn one possession / lethal check into an ordinary failure; ③ instant-draw, immediate effect | Warding Talisman, Evil-Breaking Talisman | Insufficient spell depth: high-tier spells need an extra 1 level of Dao Attainment (DOW) gate; low Knowledge (KNW) |
| **Lushan** | Balanced Prowess (PHS) / Intuition (INS) / Dao Attainment (DOW) | ① all spirit-tool damage +1; ② innate proficiency with one spirit tool (choose: Dragon-Horn / Bell-Blade / Ghost-Whip Staff); ③ Hand Seals (DOW) starts at level 1; ④ Red-Head exorcism +1, Black-Head deliverance +1 | Exorcism Talisman, Deliverance Rite | Relies on spirit tools: without them, spell power −2; close combat easily accumulates Yin Value (YIN); low Knowledge (KNW) |
| **Self-Taught Talent** | Extremely high Intuition (INS) | ① Perception Range (PR) extra +5 m; ② innate Yin-Yang Eyes (permanently see spirits, no Eye-Opening Talisman needed); ③ Communication (INS) starts at level 1; ④ once per day, free Eye-Opening Talisman effect | Soul-Calming Talisman, Spirit Perception | No systematic tradition: Talisman Drawing / Altar Opening start with no skill; Mana Pool (MP) cap −2; high-tier Altar Opening requires apprenticeship or talent unlock |
| **Folk Eclectic School** | Fairly balanced, freely reallocatable | ① +1 extra skill point at creation; ② can steal-learn 1 signature spell from another lineage; ③ equipment purchase cost −10% | Player-chosen one move | No core bonus: does not enjoy lineage core skill starts; high-tier spell Mana Pool (MP) cost +1; low Composure (CMP) easily possessed |

### 3-2 The Five Classes (Team Roles)

Class determines your combat / investigation role, and the growth features gained every 2 levels. The table below lists the Lv1 starting feature + the growth feature at each even level, plus recommended point allocation and skills.

#### Main Caster
- **Role**: Opening altars and performing rites, drawing talismans, presiding over large ceremonies; the team's core damage dealer and controller.
- **Recommended attributes**: Prowess (PHS) 2 / Dao Attainment (DOW) 8 / Intuition (INS) 4 / Knowledge (KNW) 5 / Composure (CMP) 6.
- **Recommended skills**: Talisman Drawing 2, Incantation 1, Altar Opening 1, Warding 1.
- **Growth Feature Table**:

| Level | Feature | Effect |
|---|---|---|
| Lv1 | Lineage Core | Talisman Drawing / Incantation skill +1; Mana Pool (MP) extra +5; can initiate altar rites |
| Lv2 | Potent Talismans | All talisman effects +1 |
| Lv4 | Altar Amplification | Allies adjacent during Altar Opening get spell Mana Pool (MP) cost −1 |
| Lv6 | Five-Thunder Palm Unlocked | Learn the high-tier spell "Five-Thunder Palm" |
| Lv8 | Grand Ritual Master | Can maintain 2 Warding Barriers simultaneously |
| Lv10 | Patriarch Descends | Once per day, Invite Deity Possession with no Composure (CMP) cost |

#### Warrior
- **Role**: Physically suppressing zombies, protecting casters, chasing fleeing enemies; frontline tank and melee.
- **Recommended attributes**: Prowess (PHS) 8 / Dao Attainment (DOW) 3 / Intuition (INS) 4 / Knowledge (KNW) 4 / Composure (CMP) 6.
- **Recommended skills**: Melee Combat 2, Dodge 1, Climb 1, Poison Resistance 1.
- **Growth Feature Table**:

| Level | Feature | Effect |
|---|---|---|
| Lv1 | Superior Physique | Health Points (HP) extra +10; unarmed pin damage +2; Peachwood Sword / Coin Sword proficiency |
| Lv2 | Bodyguard | When attacked, Composure (CMP)-related checks gain Advantage (roll twice, take higher) |
| Lv4 | Zombie Bane | +2 physical damage to zombies (ignores White Zombie hard-skin −2) |
| Lv6 | Warden | Moving within a Warding Barrier (MOVE) costs no extra |
| Lv8 | Iron Hide | Self physical damage mitigation −2 |
| Lv10 | One-Man Gate | Enemies within threat range are forced to attack it |

#### Medium
- **Role**: Communing with spirits, sensing Yin fluctuations, detecting hidden spirits; investigation and intel core.
- **Recommended attributes**: Prowess (PHS) 3 / Dao Attainment (DOW) 4 / Intuition (INS) 8 / Knowledge (KNW) 4 / Composure (CMP) 6.
- **Recommended skills**: Spirit Perception 2, Communication 1, Yin Perception 1, Intuition 1.
- **Growth Feature Table**:

| Level | Feature | Effect |
|---|---|---|
| Lv1 | Yin-Yang Eyes | Perception Range (PR) extra +5 m; can converse with spirits without harm; Yin Perception advantage |
| Lv2 | Empathy | Sense spirit emotion / cause-of-death clues (investigation check +2) |
| Lv4 | Soul Calming | Once per day, free Soul-Calming Talisman effect |
| Lv6 | Exorcise | Can perform exorcism ritual independently (expel possessing spirit) |
| Lv8 | Summon Spirit | Once per day, partial Summon Spirit Rite effect (limited to three questions) |
| Lv10 | Mediumship | Sustain spirit manifestation for extended periods (Communication Difficulty Class (DC) −3) |

#### Scholar
- **Role**: On-site investigation, identifying spirit types and weaknesses, consulting documents to break evil arts; intel and tactical analysis.
- **Recommended attributes**: Prowess (PHS) 4 / Dao Attainment (DOW) 5 / Intuition (INS) 4 / Knowledge (KNW) 8 / Composure (CMP) 4.
- **Recommended skills**: Folklore 2, Lineage Knowledge 1, Appraisal 1, Documentation 1.
- **Growth Feature Table**:

| Level | Feature | Effect |
|---|---|---|
| Lv1 | Erudite | Once per scene, Knowledge (KNW) check Advantage; spirit identification +2; document retrieval |
| Lv2 | Weakness Analysis | After identification, allies gain +1 damage against that spirit |
| Lv4 | Evil-Art Breaker | Knowledge (KNW) to break evil arts Difficulty Class (DC) −2 |
| Lv6 | Scene Reconstruction | Appraisal (KNW) reconstructs the course of events (gaining hidden info) |
| Lv8 | Lineage Savant | Can identify enemy lineage source and corresponding weakness |
| Lv10 | Unmatched Learning | All investigation-type Difficulty Class (DC) −2 |

#### Assistant / Apprentice
- **Role**: Preparing rite materials, setting up Warding Barriers, caring for the wounded; support and all-rounder.
- **Recommended attributes**: Prowess (PHS) 5 / Dao Attainment (DOW) 5 / Intuition (INS) 3 / Knowledge (KNW) 5 / Composure (CMP) 7.
- **Recommended skills**: Warding 1, Poison Resistance 1, Calm 1, Appraisal 1.
- **Growth Feature Table**:

| Level | Feature | Effect |
|---|---|---|
| Lv1 | Assistant | Using Main Action (MA) to aid others grants Advantage; material management (carried materials ignore weight); first aid (Composure (CMP) check to save others Difficulty Class (DC) −2) |
| Lv2 | Array Setup | Warding setup time −1 round |
| Lv4 | Encourage | Adjacent allies' Composure (CMP) checks +1 |
| Lv6 | Handy | Once per day, substitute +1 on any attribute check |
| Lv8 | Transfer Power | Can share Mana Pool (MP) with adjacent allies (≤5 per round) |
| Lv10 | Graduation | Can assume 1 Lv1 feature of any class |

---

## Chapter Four · Talents (15)

Talents are divided into **Passive (always in effect)** and **Active (triggered by spending resources)**. The unlock level indicates the minimum level at which one may spend an even-level bonus point to learn it; prerequisites must be met first.

| ID | Name | Type | Unlock Level | Prerequisite | Effect |
|---|---|---|---|---|---|
| T01 | Iron-Plate Soul-Hiding | Passive | Lv1 | Liuren lineage or Composure (CMP) ≥6 | Once per day, turn one possession / lethal check into an ordinary failure (death substitution) |
| T02 | Innate Yin-Yang Eyes | Passive | Lv1 | Self-Taught Talent or Intuition (INS) ≥7 | Perception Range (PR) permanent +5 m, no Eye-Opening Talisman needed |
| T03 | Calm Mind | Passive | Lv1 | Composure (CMP) ≥5 | Composure (CMP)-related checks +1 |
| T04 | Night Eye | Passive | Lv1 | Intuition (INS) ≥5 | Vision in darkness unrestricted; night Intuition (INS) checks +1 |
| T05 | Talisman Master | Passive | Lv2 | Talisman Drawing (DOW) ≥2 | Talisman Drawing (DOW) check +1, talisman power +1 |
| T06 | Spirit-Tool Mastery | Passive | Lv2 | Any spirit-tool skill ≥1 | Spirit-tool damage +1 |
| T07 | Corpse-Poison Resistance | Passive | Lv2 | Poison Resistance (CMP) ≥1 or Composure (CMP) ≥6 | Possession Resistance (PRZ) +2; corpse-poison damage −1 |
| T08 | Ghost Speaker | Passive | Lv2 | Communication (INS) ≥1 | Communication with spirits Difficulty Class (DC) −3; obtaining true name allows one permanent command |
| T09 | Swift Talisman | Active | Lv3 | Talisman Drawing (DOW) ≥1 | Spend 2 Mana Pool (MP); this round's talisman-drawing time halved (no prep round needed) |
| T10 | Master Key | Passive | Lv3 | Knowledge (KNW) ≥2 | Once per day in non-combat scenes, substitute +1 on any attribute check |
| T11 | Five-Thunder Infusion Palm | Active | Lv4 | Dao Attainment (DOW) ≥6 and learned Five-Thunder Palm | When casting Five-Thunder Palm, infuse extra gang-qi: damage +3d6 (total 6d6, ignores hard-skin); cost: after casting, Yin Value (YIN) backlash +1d4, once per day |
| T12 | Warding Master | Passive | Lv4 | Warding (DOW) ≥2 | Warding range +2 m, maintenance needs no per-round Mana Pool (MP) |
| T13 | Share Weal and Woe | Active | Lv5 | Assistant / Apprentice or Composure (CMP) ≥6 | Share Health Points (HP) or Mana Pool (MP) with adjacent allies, ≤5 points per round |
| T14 | Invite Deity Possession | Active | Lv6 | Dao Attainment (DOW) ≥7 | Spend 7 Mana Pool (MP) + incense; during possession attributes +2, can cast arts normally unusable, spell power doubles; end requires Composure (CMP) check Difficulty Class (DC) 15, failure causes Confusion 1d4 rounds |
| T15 | Life-Borrowing Forbidden Art | Active | Lv8 | One who has crossed the forbidden-art line | Spend 1 year of yang life + Composure (CMP) permanently −1; all spell power ×2 this scene (aftermath: Yin Value (YIN) accumulates faster) |

> The "Spell / Talent Bonus" at even levels (Lv2/4/6/8/10) may be used to unlock any talent in the above table that meets the level and prerequisite.

---

## Chapter Five · Equipment, Spirit Tools & Talismans

### 5-1 Currency: Nether Coin (COIN)

All in-game transactions use the **Nether Coin (COIN)** — the shadow-market currency of the Ghost Collector circle, settled in Hell Bank Note exchange and sect bookkeeping. HKD is background narrative only and is not part of the game mechanics.

### 5-2 Spirit Tool Table

| Name | Type | Damage / Effect | Weight | Price (COIN) | Rarity |
|---|---|---|---|---|---|
| Peachwood Sword | Melee | 1d6 + Prowess (PHS) modifier; extra +2 vs spirits / zombies | 1.5 kg | 30 | Common |
| Coin Sword | Melee | 1d6 + Prowess (PHS) modifier; inflicts "Paralysis" 1 round on zombies | 2.0 kg | 50 | Common |
| Bagua Mirror | Worn | Reflects evil aura; Spirit Perception / detection checks +1 | 0.5 kg | 40 | Common |
| Three Pure Bell | Item | Stuns low-tier spirits; Intuition (INS) Fear check Difficulty Class (DC) −2 | 0.3 kg | 35 | Common |
| Ink Line Reel | Item | Snaps ink line into a 10 m Warding Barrier spirits / zombies cannot cross | 0.5 kg | 20 | Common |
| Luopan Compass | Item | Detects environmental Yin-Yang aura; Yin Perception (INS) +2 | 0.8 kg | 60 | Fine |
| Talisman Paper + Cinnabar + Brush | Talisman trio | Essential for drawing talismans (cannot draw without any one) | 0.5 kg | 25 | Common |
| Censer + Incense | Essential for Altar Opening | Altar Opening "power source"; without it, Altar Opening (DOW) check −3 | 1.0 kg | 30 | Common |
| Century Peachwood Sword | Melee | 1d8 + Prowess (PHS) modifier; spirit damage ×2 | 1.5 kg | 400 | Rare |
| Soul-Calming Bell | Item | Ring it: all mid-tier-and-below spirits frozen for 3 rounds | 0.3 kg | 350 | Rare |
| Soul-Gathering Gourd | Item | Seals a low-tier spirit inside temporarily (capacity 1) | 0.5 kg | 380 | Rare |
| Celestial Master Talisman (finished) | Consumable | Takes effect without drawing; Exorcism Talisman effect +2 | 0.1 kg | 380 | Rare |
| Thunder-Struck Wood | Melee | 2d6 + Prowess (PHS) modifier; ignores hard-skin mitigation vs zombies | 1.0 kg | 600 | Legendary |

### 5-3 Talisman Table

> Talismans cost Mana Pool (MP) and materials at the moment of drawing; wearing / using them costs nothing extra.

| Talisman | Effect | Mana Pool (MP) Cost | Material | Weight | Unit Price (COIN) | Rarity |
|---|---|---|---|---|---|---|
| Exorcism Talisman | Deals Burn to spirits / zombies and repels (Slowed) | 2 | Yellow Paper + Cinnabar | 0.05 kg | 10 | Common |
| Corpse-Still Talisman | Stuck on zombie's forehead for Paralysis (can be torn off by force) | 3 | Yellow Paper + Cinnabar | 0.05 kg | 12 | Common |
| Warding Talisman | Wearer resists 1 supernatural attack (passive when worn) | 2 | Yellow Paper + Cinnabar | 0.05 kg | 15 | Common |
| Eye-Opening Talisman | Temporarily opens Yin-Yang Eyes (Perception Range (PR) extra +10 m, see invisible spirits; lasts 10 min) | 3 | Yellow Paper + Cinnabar + Mana | 0.05 kg | 18 | Fine |
| Pathfinding Talisman | When lit, drifts toward the heaviest Yin direction (navigation) | 1 | Yellow Paper + Cinnabar | 0.05 kg | 8 | Common |
| Purification Talisman | Purifies a small area of Yin (Yin Value (YIN) −3) | 2 | Yellow Paper + Cinnabar + glutinous rice flour | 0.05 kg | 12 | Common |
| Soul-Calming Talisman | Temporarily stills a Wandering Soul (aids communication, Calmed) | 2 | Yellow Paper + Cinnabar | 0.05 kg | 10 | Common |
| Door-Sealing Talisman | Stuck on a door; spirits cannot pass through | 2 | Yellow Paper + Cinnabar + Black Dog Blood | 0.05 kg | 14 | Fine |

### 5-4 Materials & Misc Table

| Name | Use | Weight | Price (COIN) | Rarity |
|---|---|---|---|---|
| Yellow Paper (100 sheets) | Talisman base | 0.3 kg | 5 | Common |
| Cinnabar (1 bottle) | Talisman pigment | 0.2 kg | 20 | Common |
| Glutinous Rice (1 kg) | Zombie Burn / drawing out corpse-poison | 1.0 kg | 8 | Common |
| Black Dog Blood (1 bottle) | Weakens zombies / strengthens talismans | 0.5 kg | 15 | Fine |
| Hell Bank Notes (1 stack) | Bribe Yin Constables / soothe dead souls / deliverance | 0.2 kg | 3 | Common |
| Incense & Candle (1 set) | Altar Opening / Deliverance consumable | 0.3 kg | 6 | Common |
| Flashlight | Lighting (not a spirit tool, but lets you see the way) | 0.3 kg | 12 | Common |
| Camera | Record on-site evidence | 0.5 kg | 80 | Fine |

### 5-5 Weight & Prices

- **Weight Cap** = Prowess (PHS) × 5 kg. Exceeding it imposes −1 on Prowess (PHS)-related checks; under the Assistant / Apprentice "Material Management" feature, carried materials ignore weight.
- **Price discount**: Folk Eclectic School lineage enjoys −10%; daily identities such as temple keeper / herbalist can haggle with corresponding merchants (GM adjudicates −5%~−15%).
- **Mana Pool (MP) recovery**: Resting 1 hour recovers Dao Attainment (DOW) points; complete sleep (8 hours) recovers fully. Liuren lineage recovers Dao Attainment (DOW) ×2 points.

---

## Chapter Six · Character Creation Flow

### 6-1 Eight Steps to Create a Character

| Step | Action |
|---|---|
| 1 | **Lineage**: Choose one lineage (see Chapter Three), note its unique bonus and starting skills. |
| 2 | **Attribute Allocation**: Distribute 25 points across the five attributes, each 1–10, at least one ≥6. |
| 3 | **Class**: Choose one class (see Chapter Three), copy the Lv1 feature. |
| 4 | **Signature Spell**: From lineage signature spells + class unlocks, pick 1 as your representative. |
| 5 | **First Case**: Write a background — the success or failure of your first solo case and what you learned (narrative). |
| 6 | **The Case You Couldn't Handle**: Write a case unresolved to this day, where you weren't sure you should act (narrative, left as GM foreshadowing). |
| 7 | **Your Bottom Line**: Decide whether to keep the forbidden-art boundary; if crossed, note the reason and aftermath (affects Yin Value (YIN) / Composure (CMP)). |
| 8 | **Daily Identity**: Fill in a side job identity (herbalist / temple keeper / night shift, etc.), affecting starting equipment and connections. |

### 6-2 Character Creation Example: "A-Yao"

**Character**: A-Yao, Maoshan-school Main Caster, part-time temple keeper.

**Steps 1–2 ｜ Lineage & Point Buy**
- Lineage: Maoshan → Talisman Drawing (DOW) starts at level 1, talisman effect +1, Altar Opening (DOW) +1.
- 25 points: Prowess (PHS) 3, Dao Attainment (DOW) 8, Intuition (INS) 4, Knowledge (KNW) 6, Composure (CMP) 4 (total 25, Dao Attainment (DOW) 8 ≥6 ✓).
- Attribute Modifier (Attr Mod):
  - Prowess (PHS) 3 → FLOOR((3−5)/2) = **−1**
  - Dao Attainment (DOW) 8 → FLOOR((8−5)/2) = **+1**
  - Intuition (INS) 4 → FLOOR((4−5)/2) = **−1**
  - Knowledge (KNW) 6 → FLOOR((6−5)/2) = **0**
  - Composure (CMP) 4 → FLOOR((4−5)/2) = **−1**

**Steps 3–4 ｜ Class & Signature Spell**
- Class: Main Caster Lv1 → Mana Pool (MP) extra +5, can open altars.
- Signature Spell: Corpse-Still Talisman (Maoshan signature, talisman effect +1 → more stable paralysis).

**Steps 5–8 ｜ Background** (narrative, briefly noting key effects)
- First case: Tong lau Bound Spirit, deliverance succeeded, gained temple-keeper connections (purchase Incense & Candle −10%).
- Couldn't handle: Mortuary Infant Spirit, unsure whether to send it away → GM foreshadowing.
- Bottom line: Kept the forbidden-art line, did not cross.
- Daily: Temple keeper → starts with 1 extra set of Incense & Candle, Hell Bank Notes.

**Derived Value Calculation (Lv1)**

| Derived Value | Formula | Calculation | Result |
|---|---|---|---|
| Health Points (HP) | `Prowess (PHS) × 3 + 10 + (1−1)×2` | 3×3 + 10 + 0 | **19** |
| Mana Pool (MP) | `Dao Attainment (DOW) × 3 + 5 + 0` + class +5 | 8×3 + 5 + 5 | **34** |
| Yin Threshold (YT) | `Composure (CMP) × 2 + Dao Attainment (DOW)` | 4×2 + 8 | **16** |
| Perception Range (PR) | `Intuition (INS) × 5` | 4×5 | **20 m** |
| Possession Resistance (PRZ) | `Composure (CMP) modifier` | −1 | **−1** |
| Yin Value (YIN) | Dynamic accumulation (starts at 0) | — | **0** |

> Summary: A-Yao is a typical "squishy controller" — ample Mana Pool (MP) 34, but low Health Points (HP) 19, needing a Warrior's protection. This is precisely the design intent of team division of labor.

---

## Chapter Seven · Leveling & Growth

### 7-1 Level 1–10 Growth Table

Each level gained grants fixed: Health Points (HP) cap +2, Mana Pool (MP) cap +2, 1 attribute point (max 10), 1 skill point (max 3). Even levels (Lv2/4/6/8/10) additionally learn 1 spell or unlock 1 talent.

> **Eligibility for learning spells at even levels**: The spell learned must meet "level requirement ≤ current level" (see the Spell Codex; those marked "None" can be learned anytime). Talents must meet their unlock level and prerequisites (see the Chapter Five talent table). There are 5 even-level opportunities total (Lv2/4/6/8/10); it is advised to prioritize the core talismans with "no level requirement," then learn high-tier spells as the story demands.

**Experience Points (EXP) needed to level = Level × 100 (this level)**, level up upon reaching the cumulative total.

| Level | EXP to Level (EXP) | Cumulative EXP (EXP) | HP Cap | MP Cap | Attr Pts (cum.) | Skill Pts (cum.) | Even-Level Bonus |
|---|---|---|---|---|---|---|---|
| Lv1 | — (start) | 0 | Prowess (PHS)×3+10 | Dao Attainment (DOW)×3+5 | 0 | 0 | — |
| Lv2 | 100 | 100 | +2 | +2 | +1 | +1 | Learn 1 spell / talent |
| Lv3 | 200 | 300 | +2 | +2 | +1 | +1 | — |
| Lv4 | 300 | 600 | +2 | +2 | +1 | +1 | Learn 1 spell / talent |
| Lv5 | 400 | 1000 | +2 | +2 | +1 | +1 | — |
| Lv6 | 500 | 1500 | +2 | +2 | +1 | +1 | Learn 1 spell / talent |
| Lv7 | 600 | 2100 | +2 | +2 | +1 | +1 | — |
| Lv8 | 700 | 2800 | +2 | +2 | +1 | +1 | Learn 1 spell / talent |
| Lv9 | 800 | 3600 | +2 | +2 | +1 | +1 | — |
| Lv10 | 900 | 4500 | +2 | +2 | +1 | +1 | Learn 1 spell / talent |

**Max level (Lv10) cumulative gains example (using A-Yao, starting Health Points (HP) 19 / Mana Pool (MP) 34):**
- Health Points (HP) = 19 + 9×2 = **37**
- Mana Pool (MP) = 34 + 9×2 = **52**
- Attribute points total +9 (can push Dao Attainment (DOW) to the cap of 10, or shore up Prowess (PHS))
- Skill points total +9 (Talisman Drawing etc. can reach Grandmaster level 3)
- 5 even-level opportunities to learn spells / talents

### 7-2 Base Case-Closing Experience Points (EXP)

After closing a case, base Experience Points (EXP) are awarded by case urgency, plus investigation / correct-disposal / cleanup bonuses:

| Case Tier | Base Case-Closing EXP (EXP) |
|---|---|
| D Harassment | 50 |
| C Threat | 100 |
| B Danger | 200 |
| A Lethal | 350 |
| S Disaster | 600 |

> Example: Reaching level 3 requires a cumulative 300 EXP, roughly 3 C-tier cases.

---

## Chapter Eight · Combat Basics (Player View)

### 8-1 Initiative (INIT)

At combat start, all participants roll **Initiative (INIT) = d20 + Prowess (PHS) modifier**, acting in order from high to low. On a tie, the higher Composure (CMP) modifier goes first.

### 8-2 Round Structure

On your turn, execute in sequence (order customizable):

1. **Move (MOVE)**: Up to 6 m (may be split before/after).
2. **Main Action (MA)**: 1 time (attack / use talisman / cast / pin / move-attack).
3. **Bonus Action (BA)**: 1 time (draw talisman / drink potion / small move 3 m / hand-seal amplification).

At end of each round: resolve Yin environment effects, clear timers. Each character fixedly gets **1 Main Action (MA) + 1 Move (MOVE, 6 m) + 1 Bonus Action (BA)** per round, none substitutable for another.

### 8-3 Action Economy

**Main Action (MA) can do:** Attack (weapon / spirit-tool melee or ranged) ｜ instant talisman use (tear and cast attack / control-type talisman) ｜ cast spell (high-tier spells such as Five-Thunder Palm, Summon Spirit Rite, Deliverance Rite, Demon-Sealing Array, Invite Deity Possession) ｜ pin zombie (close-quarters grapple) ｜ move-attack (move 6 m first, then attack) ｜ open altar / set array.

**Bonus Action (BA) can do:** Draw talisman (take out 1 talisman paper ready) ｜ drink potion / dress wound (drink to recover Health Points (HP) or glutinous rice to cure poison; healing consumables see item codex Chapter Five Purifying Talisman Water / Golden Wound Salve) ｜ small move (move another 3 m) ｜ hand-seal amplification (form seal to empower next spell / talisman: damage +1d4 or contest +2) ｜ defensive talisman quick-stick (stick Warding Talisman / Corpse-Still Talisman on self or adjacent ally).

> Hand-seal amplification costs 1 Mana Pool (MP); "Main Action cast" and "Bonus Action hand-seal" can combine in the same round, achieving "amplify then cast."

### 8-4 Hit & Damage Resolution

- **Attack**: Roll `1d20 + Prowess (PHS) modifier + Melee Combat / Incantation skill level ≥ target Armor Class (AC)` → Hit.
- After a hit, roll the **damage dice**, then subtract from the target's Health Points (HP). Against pure spirits (ghost types) you need a spirit tool or talisman to take effect; unarmed is useless.
- **Armor Class (AC)** = `10 + Prowess (PHS) modifier + Dodge skill level (0–3) + armor bonus` (armor bonus comes from Ritual Robe-type armor, see item codex Chapter Six; coarse robe +1 / custom robe +2, cap +2).

### 8-5 Weapon / Spirit-Tool Damage Dice

| Weapon / Spirit Tool | Damage Dice | Notes |
|---|---|---|
| Unarmed / Close Pin | 1d4 + Prowess (PHS) modifier | Useless vs pure spirits, only effective on zombie / possessed flesh |
| Peachwood Sword | 1d6 + Prowess (PHS) modifier | Extra +2 vs spirits / zombies |
| Coin Sword | 1d6 + Prowess (PHS) modifier | Inflicts "Paralysis" 1 round on zombies |
| Century Peachwood Sword | 1d8 + Prowess (PHS) modifier | Spirit damage ×2 |
| Thunder-Struck Wood | 2d6 + Prowess (PHS) modifier | Ignores hard-skin mitigation vs zombies, one-shot heavy wound |
| Glutinous Rice (scattered) | 1d4 Burn / round | Zombie stepping into area (Area-of-Effect (AOE) radius 3 m) takes Persistent Burn |
| Spell / Talisman Status Damage | Per spell | Mostly special status rather than pure damage, usually ignores hard-skin mitigation |

### 8-6 Zombie Hard-Skin Mitigation

Physical attacks against zombies have "hard-skin mitigation," subtracted from damage:

| Zombie Tier | Hard-Skin Mitigation | Break Condition |
|---|---|---|
| Fresh Corpse | 0 (none) | Can be physically pinned directly |
| White Zombie | −2 | Any attack reduced by 2 |
| Black Zombie | −3 | Needs spirit tool (Peachwood / Coin Sword) to be effective |
| Hopping Corpse | −5 | Needs spirit tool or talisman; ordinary weapons nearly useless |
| Flying Corpse | −8 | Needs century spirit tool / Celestial Master Talisman / Five-Thunder Palm |
| Cultivated Zombie | Same as its base tier | Mitigation fails after destroying the Corpse-Refiner |

> Status damage from talismans and spells (Burn, lightning, etc.) usually **ignores hard-skin mitigation** — this is the core means against high-tier zombies.

### 8-7 The Eight Status Effects

| Status | Trigger Source | Effect | Duration | Removal |
|---|---|---|---|---|
| **Burn** | Exorcism Talisman, glutinous rice, Thunder-Struck Wood, Yin fire | 1d4 damage at start of each round (stackable, max 3 layers) | 3 rounds | Purification Talisman, glutinous rice poultice, leave Yin environment |
| **Paralysis** | Corpse-Still Talisman, Coin Sword, Soul-Calming (forced) | Cannot move or use Main Action (MA); can struggle free with Bonus Action (BA) | Until torn off / struggled free | Force removes talisman; or Composure (CMP) check Difficulty Class (DC) 12 to break free |
| **Fear** | Fierce Ghost roar, Resentful Ghost retaliation | Forced to flee source, attacks under Disadvantage (roll twice, take lower) | 2 rounds | Flee line of sight; Calming Talisman / Soul-Calming Talisman |
| **Possession** | Successful spirit contact, Dead Zone assimilation | Lose body control, spirit manipulates actions (may attack companions) | Until exorcised | Exorcism Talisman, forced out by Invite Deity Possession, Deliverance Rite |
| **Confusion** | Evil entity wave, out-of-control deity possession | Random action each round (GM adjudicates); may hit companions by mistake | 1d4 rounds | Calming Talisman, full rest |
| **Weakness** | Infant Spirit drains yang, heavy blood loss | All Attribute Modifiers (Attr Mod) −1 (all attributes) | Until treated / rested | Glutinous rice poultice, 1 hour rest, healing talisman |
| **Calmed** | Soul-Calming Talisman, Calming Incantation, Soul-Calming Bell | Spirit stilled and communicable; living person's Fear subsides (removes Fear) | 2 rounds | Auto-removed when time expires |
| **Slowed** | Black Dog Blood, Yin chill, Ghost Wall | Movement halved (3 m); Main Action limited to 1 and bonus −1 | 1 round (Black Dog Blood) / until broken (Ghost Wall) | Time expires; break Ghost Wall |

### 8-8 Non-Combat Conflict

Collecting ghosts is not always combat; the following three conflict types are resolved by "check" rather than "attrition":

- **Negotiation (Contest Check)**: Negotiate with a spirit still willing to communicate. Each side rolls `1d20 + relevant bonus`, higher side leads. Success lets the spirit compromise, be delivered or leave directly; on Critical Success the spirit voluntarily reveals cause of death and weakness (bonus intel). Failure raises the spirit's hostility, possibly turning into combat.
- **Deliverance Rite (multi-round focus)**: Set up a simple altar (needs 1 round to prepare), then each round perform a `Dao Attainment (DOW) + Altar Opening` check, Difficulty Class (DC) = 12 + target Challenge Rating (CR). Success advances progress +1 (Critical Success +2); total progress reaching `Challenge Rating (CR) × 2` (Infant Spirit ×3) completes it. During the rite the main caster can only use Bonus Action (BA) to protect self each round, and may not leave the altar more than 3 m, else progress resets to zero.
- **Breaking Ghost Wall (Composure check)**: ① See through — Composure (CMP) + Will check Difficulty Class (DC) 15, success reveals the spatial loop; ② Break — after seeing through, roll Knowledge (KNW) + Lineage Knowledge or Dao Attainment (DOW) + Warding check Difficulty Class (DC) 15, stick a Pathfinding Talisman / draw an Ink Line Reel line to break it; success disables the Ghost Wall for 1 hour.

### 8-9 Collapse & First Aid

- Health Points (HP) ≤ 0 → unconscious.
- **First Aid**: Roll Composure (CMP) or Knowledge (KNW) check (solo mode Difficulty Class (DC) 10, normal Difficulty Class (DC) 12), success recovers 1d4 Health Points (HP). If untreated, lose 1 point per round, until more severe consequences.
- Spirit Health Points (HP) reaching zero = dissipation (temporary banish, not permanent); permanent resolution needs deliverance / subdual / sealing.

### 8-10 Endgame Rules (Character Death & Assimilation)

Collapse and first aid are only temporary — the following are the rulebook's default (gentle) Endgame rulings; groups seeking high pressure may use the hardcore variant in the appendix.

- **Health Points (HP) Confirmed Death**: After Health Points (HP) ≤ 0 unconscious, if **no successful first aid within 3 rounds (about 1 minute)**, or after first aid stabilizes but Health Points (HP) returns to zero with no one to continue aid, the character is confirmed dead. Character Endgame: that character exits; the GM and player agree to continue with a "successor / new Ghost Collector" replacement, or close the case there.
- **Yin Assimilation Endgame**: In the Dead Zone (Yin Value (YIN) 16+) with two consecutive Composure (CMP) check failures, or successfully possessed by a spirit and not expelled that round, the character is assimilated by Yin — becomes a hostile spirit (Character Endgame). If the GM allows, a rare rite "Soul Recall to Body" (Dao Attainment (DOW) + Altar Opening Difficulty Class (DC) 18, costs 1 round / day, must succeed 3 days running) can rescue them; see GM Book Chapter Thirteen.
- **Default Tone**: This rulebook defaults to a "gentle endgame" — death / assimilation are dramatic turns rather than instant death, encouraging continued play.

---

## Appendix

### A. Terminology Cross-Reference (Full Name (Abbr.))

| Full Name (Abbr.) | Description |
|---|---|
| Prowess (PHS) | Physique, reflexes, melee |
| Dao Attainment (DOW) | Spell cultivation, talisman potency, lineage depth |
| Intuition (INS) | Perceiving the supernatural, communing with spirits |
| Knowledge (KNW) | Folkloric learning, funeral customs, spirit classification |
| Composure (CMP) | Mental endurance, willpower, Yin resistance |
| Attribute Modifier | FLOOR((Attribute Value−5)/2) |
| Health Points (HP) | Tolerance of physical and paranormal damage |
| Mana Pool (MP) | Energy for casting spells and drawing talismans |
| Yin Value (YIN) | Yin contamination accumulated in environment or person |
| Yin Threshold (YT) | Personal Yin tolerance cap (Composure ×2 + Dao Attainment) |
| Perception Range (PR) | Distance to perceive spirits (Intuition ×5 m) |
| Possession Resistance (PRZ) | Bonus to resist possession / corpse-poison (Composure modifier) |
| Difficulty Class (DC) | Check target value |
| Experience Points (EXP) | Earned by closing cases, used to level up |
| Challenge Rating (CR) | Strength tier of spirit / zombie |
| Armor Class (AC) | Difficulty to be hit (10 + Prowess modifier + Dodge + armor bonus) |
| Initiative (INIT) | Determines action order (d20 + Prowess modifier) |
| Main Action (MA) | Primary action each round |
| Move (MOVE) | Movement each round (6 m) |
| Bonus Action (BA) | Secondary action each round |
| Area-of-Effect (AOE) | Effect that influences an area |

### B. Character Sheet Usage Notes

This rulebook is used with the Excel character sheet in the `sheets/` directory:

- **Character Sheet (Excel)**: Records the five attributes and modifiers, derived attributes (Health Points (HP) / Mana Pool (MP) / Yin Threshold (YT) / Perception Range (PR) / Possession Resistance (PRZ)), skill levels, lineage and class features, talents, equipment and talisman inventory, Experience Points (EXP) and level.
- After each level-up, update Health Points (HP) / Mana Pool (MP) caps, attribute points and skill points per the Chapter Seven growth table, and fill in newly learned spells / talents at even levels.
- After each case ends, settle Mana Pool (MP) spent, talisman inventory and cumulative Experience Points (EXP) on the character sheet.
- It is advised to open a separate column recording "The Case You Couldn't Handle" and "Your Bottom Line," for the GM to design bespoke fears and choices.

> See the project `sheets/` directory for the character sheet template.

---

*Ghost Collector TRPG Player Rulebook · End. The phone rings — ready to take the case.*
