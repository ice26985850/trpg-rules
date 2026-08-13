# Ghost Collector TRPG — GM Rulebook (Complete Game Master Handbook)

> Compiled by: compiler-gm (Ghost Collector TRPG compilation agent)
> Lead: Cheng Guiyao　｜　Design credits: Ke Jiaoying (Characters), Jing Shiwen (Worldbuilding), Zhan Zhige (Combat), Bi Touan (Dice)
> This book is a "self-contained" document: the first half fully restates all content of the Player Rulebook, and the second half contains GM-exclusive chapters. A GM reading just this one book can run the game without needing a separate player book.

---

# Part One: Player Rules (consistent with the Player Book, fully restated)

## Introduction and Solo Mode

You are no Taoist priest, nor a hero—you are a **Ghost Collector**, hired to handle the things the police can't deal with and the hospital can't explain. One phone call, one WhatsApp message, another case. This job has bills to pay, settled by market rate and personal favors.

**Core Tone**: Contemporary Hong Kong and the Lingnan geo-cultural sphere, where the modern city (smartphones, CCTV, Uber) and the supernatural are pressed into the same Tong Lau (walk-up tenement). Magic is not a special effect—it is a **tool**: opening an altar takes time, drawing talismans takes materials, and chanting spells consumes the **Mana Pool (MP)**. Ghost Collectors take cases via WhatsApp and use flashlights to see the cinnabar shimmer on their talismans.

**Solo Mode (1 Player + 1 GM)**: All mechanics are designed so that one player and one GM can run a complete session.
- In solo play the **Difficulty Class (DC)** is lowered overall by 1–2 (to compensate for the lack of ally assistance).
- Enemy **Challenge Rating (CR)** is −1 (minimum 0).
- The DC for downed first aid is 10 (since no one can administer first aid in non-combat, a more lenient window is given).
- If the check is already within the character's specialty (total bonus A ≥ +3), you may leave it unchanged, keeping the original value to preserve the challenge.

---

## Chapter 1: Attributes and Character Basics

### 1.1 The Five Attributes

25-point point-buy system; each attribute ranges 1–10, minimum 1, recommended at least one attribute reach 6+.

| Attribute | Abbrev. | Meaning |
|---|---|---|
| Prowess (PHS) | PHS | Physique, reflexes, melee |
| Dao Attainment (DOW) | DOW | Spell cultivation, talisman potency, lineage depth |
| Intuition (INS) | INS | Perceiving the supernatural, communicating with spirits |
| Knowledge (KNW) | KNW | Folklore knowledge, funeral customs, spirit classification |
| Composure (CMP) | CMP | Mental endurance, willpower, Yin resistance |

**Attribute Modifier (Attr Mod)** = `FLOOR((Attribute Value − 5) / 2)`

| Attribute Value | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 |
|---|---|---|---|---|---|---|---|---|---|---|
| Modifier | −2 | −2 | −1 | −1 | 0 | 0 | +1 | +1 | +2 | +2 |

### 1.2 Derived Attributes (Formulas and Examples)

| Derived Value | Abbrev. | Calculation |
|---|---|---|
| Health Points | Health Points (HP) | `Prowess (PHS) × 3 + 10 + (Level − 1) × 2` |
| Mana Pool | Mana Pool (MP) | `Dao Attainment (DOW) × 3 + 5 + (Level − 1) × 2` |
| Yin Value | Yin Value (YIN) | 0 (dynamically accumulated from environment and contact) |
| Yin Threshold | Yin Threshold (YT) | `Composure (CMP) × 2 + Dao Attainment (DOW)` |
| Perception Range | Perception Range (PR) | `Intuition (INS) × 5` (meters) |
| Possession Resistance | Possession Resistance (PRZ) | `Composure (CMP) Modifier` |

**Example** (A-Yao, Maoshan Main Caster, Lv1): Prowess (PHS) 3, Dao Attainment (DOW) 8, Intuition (INS) 4, Knowledge (KNW) 6, Composure (CMP) 4.
- Health Points (HP) = 3×3 + 10 + 0 = **19**
- Mana Pool (MP) = 8×3 + 5 + Class +5 = **34**
- Yin Threshold (YT) = 4×2 + 8 = **16**
- Perception Range (PR) = 4×5 = **20 meters**
- Possession Resistance (PRZ) = −1
- Yin Value (YIN) starts at **0**

### 1.3 Skill System (20+ skills, belonging to five attributes)

Skills belong to attributes, with levels: 0 Unskilled / 1 Proficient / 2 Expert / 3 Grandmaster. Skill level is added directly to the check total. Unskilled (0) skills can still be used for "attribute checks" (attribute modifier only), but professional actions such as Altar Opening and Talisman Drawing require skill ≥ 1.

| Attribute | Skills (22 total) |
|---|---|
| Prowess (PHS) | Melee Combat, Dodge, Climb, Stealth, Tracking |
| Dao Attainment (DOW) | Talisman Drawing, Incantation, Hand Seals, Altar Opening, Warding |
| Intuition (INS) | Spirit Perception, Communication, Yin Perception, Intuition |
| Knowledge (KNW) | Folklore, Lineage Knowledge, Appraisal, Documentation |
| Composure (CMP) | Will, Fear Resistance, Calm, Poison Resistance |

---

## Chapter 2: Resolution Mechanics

### 2.1 Main Die and Resolution Formula

- Main die: **1d20 (twenty-sided die)**.
- Resolution formula: `1d20 + Attribute Modifier + Skill Level + Circumstance Bonus ≥ Difficulty Class (DC)` → Success.
- **Total Bonus A** = Attribute Modifier + Skill Level (the Circumstance Bonus is granted by the GM for a single check, cap +2).

### 2.2 Success Tiers and Critical Success / Critical Failure Complications

- **Success Tier** (margin above Difficulty Class (DC)): 0–4 above is Ordinary Success; 5–9 is Good Success (more stable / faster / fewer consumables); 10+ is Excellent Success (equivalent to the extra effect of a Critical Success).
- **Critical Success**: rolling a natural 20 and the total ≥ Difficulty Class (DC). For attack/damage checks, the mechanical floor is "damage dice doubled" (roll again and sum); for non-damage checks, the GM assigns one of five situational effects: Talisman Doubled / Strike Paralyzes / Spirit Speech Clear / Effortless Casting / Victory from Peril.
- **Critical Failure**: rolling a natural 1, an automatic failure that triggers one of the complications: Talisman Ruined, Mana Backlash (lose 1d4 Mana Pool (MP) and Disadvantage on related checks next turn), Spirit Alarmed, Yin Surge (environmental Yin Value (YIN) +2), Possession Rift (Possession Resistance (PRZ) temporarily −2).

### 2.3 Contest Check

Both sides roll `1d20 + their respective bonuses` and compare totals; ties are adjudicated by the GM (usually defender succeeds). A spirit's resistance bonus is calculated as **Challenge Rating (CR) × 2** (e.g., a Fierce Ghost with CR 3 has a resistance bonus of +6). Example: in a subjugation contest, you roll `1d20 + Dao Attainment Modifier + Incantation Level` vs the spirit rolls `1d20 + Challenge Rating (CR) × 2`.

### 2.4 Advantage and Disadvantage

- **Advantage**: roll twice, take the higher.
- **Disadvantage**: roll twice, take the lower.
- Group checks may use a split-roll system (majority succeeds) or a cooperation system (each person +2 assistance bonus). In solo mode without ally assistance, the GM should lower the Difficulty Class (DC) by 1–2, or change it to a single check with one instance of Advantage.

### 2.5 Difficulty Class (DC) Name Table

| Difficulty | Difficulty Class (DC) | Example |
|---|---|---|
| Trivial | 5 | Turning on a light, ordinary conversation |
| Simple | 10 | General climbing, steady talisman drawing |
| Ordinary | 12 | Identifying common ghost types, spirit communication |
| Hard | 15 | Deciphering dark arts, high-tier altar opening |
| Very Hard | 18 | Staying calm before a Fierce Ghost, delivering an Infant Spirit |
| Legendary | 20 | Sealing a century-old Resentful Ghost |
| Miracle | 25 | Defying fate, inviting a deity who turns on you instead of submitting |

---

## Chapter 3: Lineages and Classes

### 3.1 The Five Lineages (sources of tradition, treated as a stand-in for background/race)

| Lineage | Attribute Bias (25-point example) | Unique Bonus (numeric) | Signature Spell | Restriction / Weakness |
|---|---|---|---|---|
| Maoshan | Prowess (PHS) 3, Dao Attainment (DOW) 8, Intuition (INS) 4, Knowledge (KNW) 6, Composure (CMP) 4 | ① Talisman Drawing (DOW) starts at level 1; ② all talisman effects +1; ③ Altar Opening (DOW) check +1 | Corpse-Still Talisman, Five-Thunder Palm | Strict precepts: after using forbidden arts, Composure (CMP) checks −2 and Health Points (HP)/Mana Pool (MP) cannot grow by crossing the line; Prowess (PHS) is low |
| Liuren | Prowess (PHS) 3, Dao Attainment (DOW) 7, Intuition (INS) 4, Knowledge (KNW) 3, Composure (CMP) 8 | ① Rest 1 hour to recover Mana Pool (MP) Dao Attainment (DOW)×2; ② "Iron-Plate Soul-Hiding" once per day to turn danger into safety; ③ takes effect immediately upon drawing | Warding Talisman, Evil-Slaying Talisman | High-tier spells require an extra 1 level of Dao Attainment (DOW) as a threshold; Five-Thunder Palm etc. cost +1; Knowledge (KNW) is low |
| Lushan | Prowess (PHS) 6, Dao Attainment (DOW) 6, Intuition (INS) 6, Knowledge (KNW) 4, Composure (CMP) 3 | ① all spirit-tool damage +1; ② innately proficient with one spirit tool; ③ Hand Seals (DOW) starts at level 1; ④ Red-Head Rite exorcism +1, Black-Head Rite deliverance +1 | Exorcism Talisman, Deliverance Rite | Relies on spirit tools (without a tool, power −2); shamanic arts cause Yin Value (YIN) to accumulate faster |
| Self-Taught Talent | Prowess (PHS) 4, Dao Attainment (DOW) 4, Intuition (INS) 9, Knowledge (KNW) 4, Composure (CMP) 4 | ① Perception Range (PR) +5 meters; ② innate Yin-Yang Eyes; ③ Communication (INS) starts at level 1; ④ one free Eye-Opening Talisman per day | Soul-Calming Talisman, Spirit Perception | No systematic lineage: no starting skill for Talisman Drawing/Altar Opening; Mana Pool (MP) cap −2 |
| Folk Eclectic School | Prowess (PHS) 6, Dao Attainment (DOW) 5, Intuition (INS) 5, Knowledge (KNW) 5, Composure (CMP) 4 (re-allocatable, but one attribute must still be ≥6) | ① +1 extra skill point; ② may secretly learn 1 signature spell from another lineage; ③ −10% on equipment purchase prices | Any (choose one) | No core bonus; high-tier spell cost +1; Composure (CMP) is low |

### 3.2 The Five Classes Feature Table

**Main Caster** — opens altars and performs rites, draws talismans, presides over large ceremonies; the backline control core.

| Level | Feature | Numeric Effect |
|---|---|---|
| Lv1 | Lineage Core | Talisman Drawing / Incantation +1; Mana Pool (MP) +5 extra; can open altars |
| Lv2 | Potent Talismans | All talisman effects +1 |
| Lv4 | Altar Amplification | When opening an altar, adjacent allies' spell Mana Pool (MP) cost −1 |
| Lv6 | Five-Thunder Palm Unlock | Learn Five-Thunder Palm |
| Lv8 | Grand Master | Can maintain 2 Warding Barriers simultaneously |
| Lv10 | Patriarch Descends | Once per day Invite Deity Possession with no Composure (CMP) cost |

**Warrior** — physical suppression, protects casters, frontline tank.

| Level | Feature | Numeric Effect |
|---|---|---|
| Lv1 | Robust Physique | Health Points (HP) +10 extra; unarmed suppression damage +2; Peachwood Sword / Coin Sword proficiency |
| Lv2 | Bodyguard | Advantage on Composure (CMP)-related checks when attacked |
| Lv4 | Zombie Bane | +2 physical damage to zombies (ignores White Zombie hard-skin −2) |
| Lv6 | Barrier Guard | Movement (MOVE) within a Warding Barrier costs no extra |
| Lv8 | Bronze Hide | Self physical damage mitigation −2 |
| Lv10 | One-Man Bulwark | Enemies within threat range cannot bypass you and are forced to attack you |

**Medium** — communicates with spirits, perceives Yin energy, intelligence core.

| Level | Feature | Numeric Effect |
|---|---|---|
| Lv1 | Yin-Yang Eyes | Perception Range (PR) +5 meters; can converse with spirits unharmed; Advantage on Yin Perception |
| Lv2 | Empathy | Perceive spirit emotions / cause-of-death clues (investigation +2) |
| Lv4 | Soul Calming | One free Soul-Calming Talisman effect per day |
| Lv6 | Expel Possession | Can perform exorcism rite independently (force out possessed spirit) |
| Lv8 | Summon Spirit | One partial Summon Spirit Rite effect per day (limited to three questions) |
| Lv10 | Spirit Communion | Maintain spirit manifestation for extended periods (Communication Difficulty Class (DC) −3) |

**Scholar** — on-site investigation, identifies spirit weaknesses, deciphers dark arts.

| Level | Feature | Numeric Effect |
|---|---|---|
| Lv1 | Well-Read | One Knowledge (KNW) check Advantage per scene; spirit identification +2 |
| Lv2 | Weakness Analysis | After identification, allies deal +1 damage to that spirit |
| Lv4 | Dark-Art Decryption | Knowledge (KNW) to break dark arts Difficulty Class (DC) −2 |
| Lv6 | Scene Reconstruction | Appraisal (KNW) to reconstruct the course of events (hidden information) |
| Lv8 | Lineage Insight | Can identify enemy lineage source and corresponding weakness |
| Lv10 | Unmatched Erudition | All investigation-type Difficulty Class (DC) −2 |

**Assistant / Apprentice** — prepares materials, sets up arrays, tends to the wounded.

| Level | Feature | Numeric Effect |
|---|---|---|
| Lv1 | Assistant | Assisting others grants Advantage; Material Management (carrying does not count toward load); First Aid Difficulty Class (DC) −2 |
| Lv2 | Array Setup | Warding Barrier setup time −1 turn |
| Lv4 | Encourage | Adjacent allies' Composure (CMP) checks +1 |
| Lv6 | Handyman | Once per day, substitute +1 on any attribute check |
| Lv8 | Transfer Power | Can share Mana Pool (MP) with adjacent allies (≤5 per turn) |
| Lv10 | Graduation | Can take on one Lv1 feature of any class |

---

## Chapter 4: Talents (15)

| ID | Name | Type | Unlock | Prerequisite | Numeric Effect |
|---|---|---|---|---|---|
| T01 | Iron-Plate Soul-Hiding | Passive | Lv1 | Liuren or Composure (CMP) ≥6 | Once per day turn one Possession / lethal check into an ordinary failure |
| T02 | Innate Yin-Yang Eyes | Passive | Lv1 | Self-Taught Talent or Intuition (INS) ≥7 | Perception Range (PR) permanently +5 meters, no need for Eye-Opening Talisman |
| T03 | Calm Mind | Passive | Lv1 | Composure (CMP) ≥5 | Composure (CMP)-related checks +1 |
| T04 | Night Eye | Passive | Lv1 | Intuition (INS) ≥5 | Vision in darkness unrestricted; night Intuition (INS) checks +1 |
| T05 | Talisman Master | Passive | Lv2 | Talisman Drawing (DOW) ≥2 | Talisman Drawing (DOW) check +1, talisman potency +1 |
| T06 | Spirit-Tool Mastery | Passive | Lv2 | Any spirit-tool skill ≥1 | Spirit-tool damage +1 |
| T07 | Corpse-Poison Resistance | Passive | Lv2 | Poison Resistance (CMP) ≥1 or Composure (CMP) ≥6 | Possession Resistance (PRZ) +2; corpse-poison damage −1 |
| T08 | Ghost Speaker | Passive | Lv2 | Communication (INS) ≥1 | Communication Difficulty Class (DC) −3; gaining a true name allows permanent command once |
| T09 | Swift Talisman | Active | Lv3 | Talisman Drawing (DOW) ≥1 | Consume 2 Mana Pool (MP); talisman drawing time halved this turn |
| T10 | Master Key | Passive | Lv3 | Knowledge (KNW) ≥2 | Once per day, substitute +1 on any attribute check |
| T11 | Five-Thunder Infusion Palm | Active | Lv4 | Dao Attainment (DOW) ≥6 and has learned Five-Thunder Palm | Five-Thunder Palm extra +3d6 (total 6d6, ignores hard-skin); Cost: Yin Value (YIN) backlash +1d4, once per day; consumes same as Five-Thunder Palm 8 Mana Pool (MP) |
| T12 | Warding Master | Passive | Lv4 | Warding (DOW) ≥2 | Warding Barrier range +2 meters; maintenance requires no per-turn Mana Pool (MP) |
| T13 | Share Weal and Woe | Active | Lv5 | Assistant class or Composure (CMP) ≥6 | Share Health Points (HP) or Mana Pool (MP) with adjacent allies, ≤5 per turn |
| T14 | Invite Deity Possession | Active | Lv6 | Dao Attainment (DOW) ≥7 | Consume 7 Mana Pool (MP) + incense; during possession attributes +2, can cast arts normally unusable, spell potency doubled; ending requires a Composure (CMP) check at Difficulty Class (DC) 15, failure causes Confusion for 1d4 turns |
| T15 | Life-Borrowing Forbidden Art | Active | Lv8 | One who has crossed the forbidden-art line | Consume 1 year of Yang life + Composure (CMP) permanently −1; all spell potency ×2 this scene (aftermath: Yin Value (YIN) accumulates faster) |

Learning rule: At even levels (Lv2/4/6/8/10), the "Spell / Talent reward" can be used to unlock any talent in the table above that meets the level and prerequisite; passive talents are always active, while active talents require consuming resources to trigger.

---

## Chapter 5: Equipment, Spirit Tools, Talismans

Currency unit: **Nether Coin (COIN)** — the underground currency of the Ghost Collector circle (exchanged for Hell Bank Notes, recorded on the master-disciple ledger). HKD is only for background narrative reference and is not part of the game mechanics. Rarity: Common / Fine / Rare / Legendary.

### 5.1 Spirit Tool Table

| Name | Type | Damage / Effect | Weight | Price (COIN) | Rarity |
|---|---|---|---|---|---|
| Peachwood Sword | Melee | 1d6 + Prowess (PHS) modifier; +2 extra vs spirits/zombies | 1.5 kg | 30 | Common |
| Coin Sword | Melee | 1d6 + Prowess (PHS) modifier; inflicts Paralysis 1 turn on zombies | 2.0 kg | 50 | Common |
| Bagua Mirror | Worn | Reflects malicious energy; Spirit Perception / detection +1 | 0.5 kg | 40 | Common |
| Three Pure Bell | Item | Terrifies low-tier spirits; Intuition (INS) Fear Difficulty Class (DC) −2 | 0.3 kg | 35 | Common |
| Ink Line Reel | Item | Snaps an ink line into a 10-meter Warding Barrier that spirits/zombies cannot cross | 0.5 kg | 20 | Common |
| Luopan Compass | Item | Detects Yin-Yang auras; Yin Perception (INS) +2 | 0.8 kg | 60 | Fine |
| Talisman Paper + Cinnabar + Brush | Talisman Drawing Trio | Essential for drawing talismans | 0.5 kg | 25 | Common |
| Censer + Incense Stick | Essential for Altar Opening | Without it, Altar Opening (DOW) check −3 | 1.0 kg | 30 | Common |
| Century Peachwood Sword | Melee | 1d8 + Prowess (PHS) modifier; damage ×2 vs spirits | 1.5 kg | 400 | Rare |
| Soul-Calming Bell | Item | All spirits below mid-tier are immobilized for 3 turns | 0.3 kg | 350 | Rare |
| Soul-Gathering Gourd | Item | Collects a low-tier spirit for temporary sealing (capacity 1) | 0.5 kg | 380 | Rare |
| Celestial Master Talisman (ready-made) | Consumable | Takes effect without drawing; Exorcism Talisman effect +2 | 0.1 kg | 380 | Rare |
| Thunder-Struck Wood | Melee | 2d6 + Prowess (PHS) modifier; ignores hard-skin mitigation vs zombies | 1.0 kg | 600 | Legendary |

### 5.2 Talisman Table (Mana Pool (MP) costs per memo)

As locked per the compilation memo: Exorcism Talisman 2, Corpse-Still Talisman 3, Warding Talisman 2 (consumed when drawn, passive when worn), Eye-Opening Talisman 3, Pathfinding Talisman 1, Purification Talisman 2, Soul-Calming Talisman 2, Door-Sealing Talisman 2. Drawing talismans consumes **Mana Pool (MP)** and materials at that moment; wearing / using them consumes nothing further.

| Talisman | Effect (trigger) | Status Duration | Mana Pool (MP) | Material | Unit Price (COIN) | Rarity |
|---|---|---|---|---|---|---|
| Exorcism Talisman | Burn and repel | Burn (1d4 per turn, stackable 3 layers, 3 turns) + Slowed (1 turn) | 2 | Yellow Paper + Cinnabar | 10 | Common |
| Corpse-Still Talisman | Applied to forehead to fix in place (can be torn off by external force) | Paralysis (Bonus Action (BA) to break free at Difficulty Class (DC) 12, until torn off) | 3 | Yellow Paper + Cinnabar + Mana infusion | 12 | Common |
| Warding Talisman | Blocks 1 supernatural attack | One-time (consumed after triggering) | 2 (drawn) | Yellow Paper + Cinnabar | 15 | Common |
| Pathfinding Talisman | Drifts toward the strongest Yin direction | Until it reaches the Yin source or burns out | 1 | Yellow Paper + Cinnabar | 8 | Common |
| Purification Talisman | Purifies Yin energy in a small area | Yin Value (YIN) −3 (instant) | 2 | Yellow Paper + Cinnabar + Glutinous Rice Flour | 12 | Common |
| Soul-Calming Talisman | Temporarily calms a Wandering Soul (for communication) | Calmed (2 turns) | 2 | Yellow Paper + Cinnabar | 10 | Common |
| Door-Sealing Talisman | Spirit cannot pass through a sealed door | Until the talisman breaks / Mana runs out | 2 | Yellow Paper + Cinnabar + Black Dog Blood | 14 | Fine |
| Eye-Opening Talisman | Temporarily opens Yin-Yang Eyes | Perception Range (PR) extra +10 meters, can see invisible spirits; lasts 10 minutes | 3 | Yellow Paper + Cinnabar + Mana | 18 | Fine |

### 5.3 Materials and Miscellaneous

| Name | Use | Weight | Price (COIN) | Rarity |
|---|---|---|---|---|
| Yellow Paper (100 sheets) | Talisman base | 0.3 kg | 5 | Common |
| Cinnabar (1 bottle) | Talisman pigment | 0.2 kg | 20 | Common |
| Glutinous Rice (1 kg) | Burn zombies / draw out corpse poison | 1.0 kg | 8 | Common |
| Black Dog Blood (1 bottle) | Weakens zombies / empowers talismans | 0.5 kg | 15 | Fine |
| Hell Bank Notes (1 stack) | Bribe Yin Constables / soothe the dead / deliverance | 0.2 kg | 3 | Common |
| Incense & Candle (1 set) | Consumed for altar opening / deliverance | 0.3 kg | 6 | Common |
| Flashlight | Lighting | 0.3 kg | 12 | Common |
| Camera | Record on-site evidence | 0.5 kg | 80 | Fine |

### 5.4 Economy and Load

- **Case Reward (Nether Coin (COIN))**: Grade D 50–100, Grade C 100–200, Grade B 200–400, Grade A 400–800, Grade S 800+ (plus reputation and rare spirit tools).
- **Load Cap** = `Prowess (PHS) × 5` kg; exceeding it gives Prowess (PHS) checks −1. Under the Assistant's "Material Management", carried materials do not count toward load.
- **Price Discount**: Folk Eclectic School −10%; Temple Keeper / Herbal Shop identity can bargain (GM adjudicates −5%~−15%).
- **Mana Pool (MP) Recovery**: Resting 1 hour recovers Dao Attainment (DOW) points; full sleep recovers to full (Liuren recovers Dao Attainment (DOW)×2).

---

## Chapter 6: Character Creation Process

### 6.1 Eight-Step Character Creation

| Step | Action |
|---|---|
| 1 | Lineage Heritage: Choose one lineage, note its unique bonus and starting skills |
| 2 | Attribute Allocation: Distribute 25 points among the five attributes, each 1–10, at least one ≥6 |
| 3 | Party Role: Choose one class, copy its Lv1 features |
| 4 | Signature Spell: Choose 1 from lineage signature + class unlock |
| 5 | First Case: Write about the success or failure of your first solo case and what you learned |
| 6 | The Case You Couldn't Handle: Write an unsolved case to date (GM foreshadowing) |
| 7 | Your Bottom Line: Decide whether to hold the forbidden-art line; if you cross it, note the reason and aftermath |
| 8 | Daily Identity: Fill in a side-job identity (herbal shop / temple keeper / night shift, etc.), affecting starting equipment and connections |

### 6.2 Character Creation Example: A-Yao

**Lineage**: Maoshan (Talisman Drawing starts at level 1, talisman effect +1, Altar Opening +1). **25 points**: Prowess (PHS) 3, Dao Attainment (DOW) 8, Intuition (INS) 4, Knowledge (KNW) 6, Composure (CMP) 4.
- Modifiers: Prowess (PHS) → −1; Dao Attainment (DOW) → +1; Intuition (INS) → −1; Knowledge (KNW) → 0; Composure (CMP) → −1.
- Class: Main Caster Lv1 → Mana Pool (MP) +5, can open altars. Signature: Corpse-Still Talisman.
- Background: First case successfully delivered a Tong Lau Bound Spirit (gained temple-keeper connections, −10% on incense & candle purchases); couldn't handle a mortuary Infant Spirit (GM foreshadowing); held the forbidden-art line without crossing it; daily identity temple keeper (extra set of incense & candle, Hell Bank Notes).
- Derived values (Lv1): Health Points (HP) 19, Mana Pool (MP) 34, Yin Threshold (YT) 16, Perception Range (PR) 20 meters, Possession Resistance (PRZ) −1, Yin Value (YIN) 0.
- Commentary: A typical "fragile control type" — ample Mana Pool (MP), low Health Points (HP) needing a Warrior's protection, exactly the intended design of party role division.

---

## Chapter 7: Leveling and Growth

Experience Points (EXP) needed to level up = `Level × 100` (this level); accumulate to the threshold to level up. Each level grants fixed gains: Health Points (HP) cap +2, Mana Pool (MP) cap +2, 1 attribute point (cap 10), 1 skill point (cap 3). At even levels (Lv2/4/6/8/10) you additionally learn 1 spell or unlock 1 talent.

| Level | EXP Needed to Level (EXP) | Cumulative EXP (EXP) | Even-Level Reward |
|---|---|---|---|
| Lv1 | — (starting) | 0 | — |
| Lv2 | 100 | 100 | Learn 1 spell / talent |
| Lv3 | 200 | 300 | — |
| Lv4 | 300 | 600 | Learn 1 spell / talent |
| Lv5 | 400 | 1000 | — |
| Lv6 | 500 | 1500 | Learn 1 spell / talent |
| Lv7 | 600 | 2100 | — |
| Lv8 | 700 | 2800 | Learn 1 spell / talent |
| Lv9 | 800 | 3600 | — |
| Lv10 | 900 | 4500 | Learn 1 spell / talent |

**Max-Level Example (A-Yao)**: Health Points (HP) 19+18 = 37; Mana Pool (MP) 34+18 = 52; attribute points total +9; skill points total +9; even levels give 5 spell/talent opportunities.

---

## Chapter 8: Combat Basics

### 8.1 Initiative and Turns

- **Initiative (INIT)** = `d20 + Prowess modifier`, acting in order from high to low; spirits substitute with "Agility". Ties: the one with higher Composure (CMP) goes first.
- Each turn: **1 Main Action (MA) + 1 Move (MOVE, 6 meters) + 1 Bonus Action (BA)**, none of the three substitutes for another.
- Reaction Action: When attacked or approached, you may spend next turn's Bonus Action (BA) to make one Dodge (DC 12) or Bagua Mirror reflection; at most once per round per person.

### 8.2 Action Economy

- **Main Action (MA)**: Attack, instant talisman use, spellcasting (high-tier), suppress zombies, move-attack, open altar and set array.
- **Bonus Action (BA)**: Draw talisman, drink medicine / apply wound, small move 3 meters, Hand-Seal Amplification (consume 1 Mana Pool (MP): next spell damage +1d4 or contest +2 or deliverance +1), instantly apply defensive talisman.
- **Movement and Positioning**: 1 square = 1.5 meters, Move (MOVE) = 4 squares (6 meters). Melee contact within 1 square; spirits/zombies cannot cross Warding Barriers / ink lines; Flying Corpses can fly over (but are still trapped upon landing); cover gives +2~+4 to Armor Class (AC).

### 8.3 Hit and Damage

- Attack: `1d20 + Prowess modifier + Melee Combat / Incantation level ≥ target's Armor Class (AC)` → after a hit, roll damage dice.
- **Armor Class (AC)** = `10 + Prowess modifier + Dodge level` (armor +1~+2).
- **Weapon / Spirit-Tool Damage Dice**: Unarmed 1d4+Prowess modifier (ineffective vs pure spirits, only effective against zombie/possessed flesh); Peachwood Sword 1d6+Prowess modifier (+2 vs spirits/zombies); Coin Sword 1d6+Prowess modifier (Paralysis 1 turn vs zombies); Century Peachwood Sword 1d8+Prowess modifier (×2 vs spirits); Thunder-Struck Wood 2d6+Prowess modifier (ignores hard-skin mitigation vs zombies).

### 8.4 Zombie Hard-Skin Mitigation (physical damage)

| Tier | Hard-Skin Mitigation | Breakthrough Condition |
|---|---|---|
| Fresh Corpse | 0 | Can be physically suppressed directly |
| White Zombie | −2 | Any attack reduced by 2 |
| Black Zombie | −3 | Requires a spirit tool to be effective |
| Hopping Corpse | −5 | Requires a spirit tool or talisman |
| Flying Corpse | −8 | Requires century spirit tool / Celestial Master Talisman / Five-Thunder Palm |
| Cultivated Zombie | Same as base tier | Mitigation fails after destroying the corpse-refiner |

"Status damage" from spells/talismans (Burn, lightning) usually ignores hard-skin mitigation and is the core means against high-tier zombies.

### 8.4.1 Principles for Handling Hard-Skin Bosses

Hard-Skin (Mitigation) X means that each time the target takes weapon/talisman damage, X points are subtracted first (minimum 0) before counting toward Health Points (HP) loss. A Flying Corpse's hard-skin (mitigation) of 8 and a Hopping Corpse's 5 make pure weapon chopping unrealistic — a Peachwood Sword (1d6 + Prowess (PHS)) reduced by 8 mostly zeroes out, and a Flying Corpse takes roughly 11+ turns and is nearly impossible to break through. The correct solution is "control then resolve non-combat": first use glutinous rice, ink line reel, Corpse-Still Talisman, and Soul-Calming Bell to control and limit its actions, then permanently resolve it via Deliverance Rite (Dao Attainment (DOW) + Altar Opening check, Difficulty Class (DC) = 12 + Challenge Rating (CR)) or Sealing (Soul-Gathering Gourd / Corpse-Still Talisman); Thunder-Struck Wood (ignores hard-skin, 2d6) is one of the few spirit tools that can hard-break it. Tip for the Game Master (GM): the challenge of a Boss fight lies in "control and ritual rhythm," not "damage race" — do not let players fall into a damage speedrun. The scenarios (e.g., S3, S8) already add corresponding guidance at the Boss sections.

### 8.5 Status Effects

| Status | Source | Effect | Duration | Removal |
|---|---|---|---|---|
| Burn | Exorcism Talisman, glutinous rice, Thunder-Struck Wood | 1d4 per turn (stackable 3 layers) | 3 turns | Purification Talisman, glutinous rice poultice, leave Yin environment |
| Paralysis | Corpse-Still Talisman, Coin Sword, Soul Calming | Cannot move or take Main Action | Until torn off / broken free | External force tears talisman, or Composure (CMP) Difficulty Class (DC) 12 to break free |
| Fear | Fierce Ghost roar, Resentful Ghost | Move away from source, attack with Disadvantage | 2 turns | Flee from sight, Calmed / Soul-Calming Talisman |
| Possession | Spirit contact, dead-zone assimilation | Lose body control | Until exorcised | Exorcism Talisman, force out via deity possession, deliverance |
| Confusion | Evil entity wave, loss of control in deity possession | Take random action each turn | 1d4 turns | Calm Talisman, full rest |
| Weakness | Infant Spirit draining Yang energy, blood loss | All attribute modifiers −1 | Until treated | Glutinous rice poultice, rest 1 hour |
| Calmed | Soul-Calming Talisman, Soul-Calming Bell | Spirit is still and can communicate; living person's fear subsides | 2 turns | Time expires |
| Slowed | Black Dog Blood, Yin chill, Ghost Wall | Movement halved; one extra Main Action limited to 1 | 1 turn / until broken | Time expires; break Ghost Wall |

### 8.6 Non-Combat Conflict

- **Negotiation (Contest Check)**: When a Resentful Ghost / Spirit Beast / Bound Spirit / Possessed still has the will to communicate. Both sides roll and take the higher; success 0–4 proposes terms, 5–9 reaches compromise for deliverance, 10+ / Critical Success reveals cause-of-death weakness; failure raises hostility +1 and turns to combat.
- **Deliverance Rite (multi-turn concentration)**: Set up altar 1 turn; each turn `Dao Attainment (DOW) + Altar Opening` check at Difficulty Class (DC) = 12 + target's Challenge Rating (CR); success adds +1 progress (Critical Success +2), failure unchanged and Yin Value (YIN) +1; completion threshold: total progress ≥ Challenge Rating (CR) × 2 (Infant Spirit ×3). The Main Caster may only use Bonus Action (BA) to defend each turn.
- **Breaking Ghost Wall (Composure check)**: ① See through it: Composure (CMP) + Will at Difficulty Class (DC) 15 (failure circles in place, Yin Value (YIN) +1); ② Break it: Knowledge (KNW) + Lineage Knowledge or Dao Attainment (DOW) + Warding at Difficulty Class (DC) 15 to apply a Pathfinding Talisman / ink line (fails after 1 hour).

### 8.7 First Aid and Downed

Health Points (HP) ≤ 0 → unconscious. First Aid: `Composure (CMP) or Knowledge (KNW)` check at Difficulty Class (DC) 12, success recovers 1d4 points; untreated, loses 1 point per turn until 0 (death / assimilation). A spirit's Health Points (HP) reaching 0 = dissipation (temporary banishment); permanent resolution requires deliverance / subjugation / sealing.

---

# Part Two: GM-Exclusive Chapters

## Chapter 9: GM Resolution and Difficulty Class (DC) Guidelines

### 9.1 Ghost-Collecting Five-Phase Key Check Difficulty Class (DC) Table (with solo-mode tweaks)

| Phase | Key Check | Suggested Difficulty Class (DC) | Solo Tweak | Notes |
|---|---|---|---|---|
| 1. Take Case | Knowledge (judge truth) | 10 | −1~−2 → 8–9 | Client may exaggerate or conceal |
| | Social (reassure client) | 10 | −1 → 9 | Earn the other party's trust |
| 2. On-Site Investigation | Intuition (perceive spirit) | 12 | −1~−2 → 10–11 | Perceived within Perception Range (PR) |
| | Knowledge (identify type / cause of death) | 12–15 | −1 → 11–14 | Rarer means higher |
| | Social (interview witnesses) | 10 | −1 → 9 | Extract hidden information |
| 3. Prepare Rite | Dao Attainment (altar opening) | 15 | −2 → 13 | High-tier altar opening prone to errors |
| | Knowledge (choose correct method) | 12 | −1 → 11 | Wrong choice doubles the effort |
| 4. Exorcise & Collect | Dao Attainment (rite / subjugation) | 15–18 | −2 → 13–16 | Depends on spirit strength |
| | Intuition (communication / negotiation) | 12 | −1 → 11 | If you reach an understanding, no fight needed |
| | Prowess (suppress zombie) | 12–15 | −1 → 11–14 | Depends on zombie tier |
| | Composure (resist possession) | 15 | −2 → 13 | Against possessed / Ghost Wall |
| 5. Cleanup | Dao Attainment (purification) | 12–15 | −1 → 11–14 | Depends on residual Yin |
| | Composure (fatigue from long rite) | 12 | −1 → 11 | Hold up without collapsing |
| | Social (client feedback) | 10 | −1 → 9 | Affects reward |

> Guideline: In solo mode you may always lower the Difficulty Class (DC) by 1–2; if the check is already within the character's specialty (A ≥ +3), you may leave it unchanged to preserve the challenge.

### 9.2 Yin Energy System Explained (Environmental Yin Value and Personal Yin Value)

Environmental Yin Value (YIN) and personal Yin Value are calculated separately, sharing the same effect bands:

| Environmental Yin Value (YIN) | State | Effect |
|---|---|---|
| 0–2 | Normal | No effect |
| 3–5 | Faint Yin | Intuition (INS)-related checks have Advantage (roll twice, take higher); personal does not accumulate |
| 6–10 | Yin Chill | Each turn Composure (CMP) check at Difficulty Class (DC) 12; failure adds +1 to environmental Yin Value (YIN); personal +1 every 2 turns |
| 11–15 | Extreme Yin | All actions at Disadvantage (roll twice, take lower); personal +1 per turn; requires Warding Barrier protection |
| 16+ | Dead Zone | Each turn forced Composure (CMP) check at Difficulty Class (DC) 15; two consecutive failures → assimilated by Yin energy (possession or unconscious); personal +2 per turn |

### 9.3 Yin Energy Advantage / Disadvantage Probability Conversion Table

| Base Success Rate p | After Advantage | After Disadvantage |
|---|---|---|
| 30% | 51% | 9% |
| 45% | 70% | 20% |
| 55% | 80% | 30% |
| 70% | 91% | 49% |

Example: An Intuition (INS) check with base 55% (A=0, Difficulty Class (DC) 12), Faint Yin turns to Advantage → 80%, Extreme Yin turns to Disadvantage → 30%. The swing in and out is stark, illustrating that "Yin energy is both a help and a hindrance."

### 9.4 Personal Yin Over-Threshold Penalty and Recovery

**Yin Threshold (YT)** = `Composure (CMP) × 2 + Dao Attainment (DOW)` (e.g., Composure 6, Dao Attainment 8 → Yin Threshold (YT) 20).
- When personal Yin Value exceeds the Yin Threshold (YT), each point over reduces "related checks" by −1.
- **Related Checks**: Those related to Intuition (INS), Dao Attainment (DOW), Composure (CMP) (GM adjudicates); pure-physical Prowess (PHS) or social checks are usually unaffected.
- **Recovery**: After leaving the Yin environment, personal Yin Value (YIN) −1 per hour of rest; full sleep (8 hours) clears all; Purification Talisman / purification rite can immediately −2~−3.

### 9.5 Mana Pool (MP) Economy

**Capacity** = `Dao Attainment (DOW) × 3 + 5 + (Level − 1) × 2`

| Dao Attainment (DOW) \ Level | L1 | L5 | L10 |
|---|---|---|---|
| 6 | 23 | 31 | 41 |
| 8 | 29 | 37 | 47 |
| 10 | 35 | 43 | 53 |

**Recovery**: Resting 1 hour recovers Dao Attainment (DOW) points (Liuren ×2); full sleep recovers to full. When depleted, cannot cast; must rest / sleep.

**Single-Encounter Consumption Verification** (Dao Attainment 8, Lv1 → Mana Pool 29): Conservative play (1 talisman per turn, 4 Mana Pool (MP)) for 5 turns = 20 Mana Pool (MP), 9 left, won't deplete; all-out play (5 Mana Pool (MP)) for 5 turns = 25 Mana Pool (MP), 4 left, on the verge of empty and must rest; if stacking altar opening or Five-Thunder Palm (15 Mana Pool (MP)), a single encounter uses 30–40 Mana Pool (MP), clearly requiring a mid-encounter rest. Conclusion: a standard encounter (3–5 turns) consumes 15–25 Mana Pool (MP), 52–86% of capacity — the economy balance holds.

---

## Chapter 10: Monster and Spirit Bestiary (see separate file)

> This book no longer embeds complete monster data. For the full data blocks of the sixteen types of spirits, zombies, and environmental encounters (Challenge Rating (CR), Health Points (HP), Armor Class (AC), Initiative (INIT), weaknesses, correct handling methods, corresponding tactics, Yin emission value (YIN), etc.), please consult the separate bestiary file:

▶ **`怪物圖鑑.md`** (located under `assets/` in this folder; the site will place it under `catalogs/`)

---

## Chapter 11: Complete Spell Entries (see separate file)

> For the complete entries of the eight core talismans and six high-tier spells (Mana Pool (MP) cost, casting time, Area of Effect (AOE), effect values, level requirement, cost and materials), please consult the separate bestiary file:

▶ **`法術圖鑑.md`** (located under `assets/` in this folder; the site will place it under `catalogs/`)

---

## Chapter 12: Worldbuilding and Setting

### 12.1 The Three Major Lineages Examined

- **Maoshan**: Originating from Maoshan in Jurong, Jiangsu, the ancestral seat of the Taoist Shangqing school, founded by Tao Hongjing; merged into the Orthodox One school in the Song dynasty, alongside Longhu Mountain and Gezao Mountain known as the "Three Mountains Talisman Tradition." It branched among the folk into the "Maoshan Ritual Teaching," emphasizing talismans, incantations, hand seals, and spirit tools, focused on exorcism and healing. Historically, the "Black Maoshan" branch drifted to Southeast Asia and became the Nanyang Sorcerers (black art), regarded as a dark-art heretical sect by Ghost Collectors. Signatures: Five-Color Talismans, Hand Seals, Five-Thunder Incantation. Game role: most rigorous talismans, high ceiling, corresponds to Main Caster.
- **Liuren**: Full name "Thirty-Three Heavens Wandering Liuren Orthodox Law Iron-Plate Teaching," a Hakka folk ritual teaching venerating the Liuren Immortal Master. Its feature is "convenient and fast," with the core being "Iron-Plate Soul-Hiding" (life information stored on an iron plate, misfortune auto-transferred). Flourished in Hong Kong in the 1960s–70s, widely practiced across Guangdong-Hong Kong-Macau, the most down-to-earth. Organizations split into Fuying Hall, Qunying Hall, and Fenghuo Court. Distinction from "Spirit Possession Combat": Liuren divine art grants protection from the immortal master while keeping the mind clear. Game role: quick to learn, suited to lone operators, corresponds to Medium / Assistant.
- **Lushan**: From Min-Yue shamanic arts, centered in Fujian, venerating Xu Xun, Lin Shui Madame Chen Jinggu, and Fa Zhu Zhang Shengjun. The Red-Head Rite (exorcism & blessing) and Black-Head Rite (deliverance of the dead) follow separate paths; the spell style is "overbearing," with very heavy ritual. Spirit tools: Dragon Horn, Bell-Sword, Ghost-Subduing Staff, etc. Game role: fiercest offense and defense, strong family lineage, corresponds to Warrior / attack-oriented Main Caster.
- **Relationship Among the Three Lineages**: Same origin, different streams, settling in Hong Kong with southward migration in the late Ming. Polite on the surface but competing in secret, yet they cooperate when facing the corpse-cultivating heretics. Hong Kong established the "Ghost Collector Guild," with each lineage sending elders to form the **Three-Lineage Council**.

### 12.2 Four Factions (+ CID Miscellaneous Section)

- **Ghost Collector Guild (Three-Lineage Council)**: An industry self-regulatory body holding the case roster, newcomer referrals, and disciplinary actions. Violating the bottom line (using the Life-Borrowing Forbidden Art) leads to being "cleansed from the sect." Key NPCs: Council Chair "Cheng Guiyao" (Maoshan background), Liuren representative "Master Wu," Lushan representative "Chen Faqing."
- **Funeral Home Network "Shi Chu Shi"**: On the surface a legal funeral business, but actually an intelligence and frontline node, first to contact restless dead. Key NPC: "Uncle Nine" — a veteran mortuary supervisor holding the blacklist of all mortuaries in Hong Kong.
- **Yin Constable System**: The City God / Underworld's agents in the living world (underworld civil servants), who hook souls and escort them, maintaining Yin-Yang order — reasoned and lawful, not villains. If a Ghost Collector delivers a soul the Yin Constables were to capture, it causes trouble, requiring Hell Bank Note bribes or guild credentials to mediate; they are also a valuable intelligence source. Key NPC: "Ox-Head Bing" — the Yin Constable stationed in Kowloon, who takes red envelopes and follows the rules.
- **Corpse-Cultivating Heretic Sect "Nine Nether Hall"**: Deliberately refines zombies, refines ghosts, and sets up Haunted Houses, treating dead souls and corpses as materials in pursuit of twisted longevity / revenge; the main source of S-tier threats and the core of the sequel's clues. Key NPC: "Corpse-Refiner Seventh Uncle" (a seemingly retired geomancer, actually the person in charge of Nine Nether Hall's Hong Kong station).
- **(Appendix) Police Special Incident Unit "CID Miscellaneous Section"**: Double-faced. Veteran officers privately refer unexplainable scenes; at the same time they monitor whether Ghost Collectors cross the line. When interrogated, a Social (Persuasion) check is needed to get away; failure alarms the media.

### 12.3 Five Location Types (with Yin characteristics)

| Location | Description | Yin Value (YIN) Trait | Common Spirits |
|---|---|---|---|
| Tong Lau | Six floors no elevator, rusty iron gates, talisman paper on stairwell | Accumulates in stairwells / light wells / mailboxes, base 3–8 (murder cases can reach 11+) | Bound Spirit, Wandering Soul, Haunted House |
| Mortuary / Funeral Home | Over-air-conditioned, ghastly white fluorescent lights, drawers like honeycomb | High baseline, base 5–10, stacks with multiple corpses | Fresh Corpse, White Zombie, Resentful Ghost |
| School Toilet / Campus | Mirror water stains, dripping faucets, empty corridors with ventriloquist laughter | Mirrors and water basins as nodes, base 4–9, high possession rate in stalls | Wandering Soul, Infant Spirit, Possessed, low-tier Resentful Ghost |
| Graveyard / Village House (Walled Village) | Hakka walled village / abandoned ancestral home, wild graves and feng shui woods | Corpse-cultivating sites can reach 12–16, wild graves cluster into Ghost Walls | Cultivated Zombie, White/Black Zombie, Spirit Beast, Fierce Ghost |
| Public Housing Estate / Tunnel | Fall-death lingering souls wander, tunnel as Yin energy channel | Estate 4–9; tunnel 10–14 | Fall-death Resentful Ghost, Wandering Soul, Ghost Wall (tunnel) |

---

## Chapter 13: GM Running Guide

### 13.1 Five-Phase Pacing Table

| Phase | Player Focus | GM Pacing Points | Key Checks |
|---|---|---|---|
| 1. Take Case | Judge truth, negotiate reward | Open with a phone call / WhatsApp; plant seeds of client concealment | Knowledge (KNW) judge truth, Social persuasion |
| 2. On-Site Investigation | Perceive spirits, interview, find clues | Slow-burn, give sensory details before checks | Intuition (INS) perception, Knowledge (KNW) identification, Social interview |
| 3. Prepare Rite | Choose method, prepare materials, open altar | Create time pressure (midnight strongest / corpse-change countdown) | Dao Attainment (DOW) altar opening, Knowledge (KNW) choose method |
| 4. Exorcise & Collect | Execute handling (may be non-combat) | Climax, give moral choices; combat is only an option | Dao Attainment (DOW) rite, Intuition (INS) communication, Prowess (PHS) suppression, Composure (CMP) resist possession |
| 5. Cleanup | Purify, soothe, settle | Wind down, client reaction, residual Yin, hooks | Dao Attainment (DOW) purification, Composure (CMP) endure long rite, Social feedback |

> Iron Rule: Never skip Phase 2. If the players haven't found out "this is a Bound Spirit, the cause of death is an unfulfilled wish," Phase 4 will only devolve into brute-force dispersal.

### 13.2 "Yes, and..." Atmosphere Building

- Start from the senses: Don't say "Yin Value (YIN) 8"; instead say "the hairs on the back of your neck stand up, your phone signal drops two bars, water beads seep from the corner of the wall, a smell like stale incense ash," and let the players say themselves "something's wrong here."
- "Yes, and...": Accept the players' speculation and stack on top (Player: "I think she's looking for someone." GM: "Yes, and on the spirit altar sits an undelivered baby photo with writing on the back.").
- Yin energy is an environment, not HP: Use flickering lights, temperature drop, and distorted sound to reflect the rise and fall of Yin Value (YIN); for a Dead Zone (16+), describe "you can't hear your companions clearly, as if separated by a layer of water."
- Silence is scarier than screaming: Before a Fierce Ghost appears, let all sound stop for three seconds.
- Personalized fright: Use the character sheet's "the case you couldn't handle" and "your bottom line" to craft customized fear.

### 13.3 Solo Mode Hosting Points

- Lower Difficulty Class (DC) overall by 1–2; one person playing multiple roles can shift attribute focus across phases; double the information density (proactively give clues discoverable by Intuition (INS) / Knowledge (KNW)) to avoid getting stuck; use Perception Range (PR) fully to create lonely pressure; avoid instant death, give a lenient recovery window after downed (DC 10).

### 13.4 Experience Points (EXP) and Reward Distribution

- **Base Case Experience Points (EXP) (side-quest / single-commission baseline)**: D 50 / C 100 / B 200 / A 350 / S 600. This table applies to side-quest commissions and impromptu encounters outside the eight main scenarios.
- **Main scenario Experience Points (EXP) follow scenarios/*.yaml (do not apply the table above)**: Each main scenario's completion reward directly takes the `rewards.exp` field of the corresponding YAML — S1 100 / S2 300 / S3 600 / S4 500 / S5 600 / S6 700 / S7 800 / S8 900, the eight main scenarios total **4500 Experience Points (EXP)**, exactly matching the total Lv1→Lv10 leveling requirement (leveling needs `Level × 100`, cumulative 100+200+…+900 = 4500). Distribute main scenarios per the YAML values, avoiding double-counting with the side-quest baseline table.
- **Bonuses**: +10~20 per investigation discovery; +50~100 for correct handling (deliverance instead of dispersal, successful negotiation); +30~80 for cleanup quality (satisfied client, no residual Yin); +40 for discovering unsolved-mystery hooks.
- **Penalties**: Accidentally harming the innocent / host, alarming the media, spreading Yin energy, each −30~100 (by severity).
- Leveling: Accumulate to `Level × 100` to level up. Example: reaching level 3 requires cumulative 300 Experience Points (EXP).

### 13.5 Reward Design

- **Reputation / Guild Standing (Reputation Points Reputation (REP))**: The Ghost Collector Guild records fame with "Reputation Points (REP)," determining case-access permissions and the favor of the three-lineage elders. This is an independent subsystem running from character creation to finale (does not affect attributes or combat power).
  - **① Accumulation Method**
  - Cases grant Reputation (REP) by difficulty: D +1 / C +2 / B +3 / A +5 / S +8.
  - Correct deliverance (not dispersal), cleanup with no residual Yin, highly satisfied client: each an extra +1~2.
  - Triggering S-line milestones (pursue Nine Nether Hall clues +5 / defeat forward outpost +8 / destroy main altar +10): counted extra.
  - **Deductions (violating the bottom line)**: Accidentally harming the innocent or host −2; spreading Yin / alarming media −1; violating the "investigate first, report later" protocol (e.g., S6 acting on your own) −1~3. In S1, directly dispersing the Bound Spirit with an Exorcism Talisman triggers "Guild Reputation −1."
  - **② Reputation Levels (threshold = cumulative Reputation (REP))**

  | Reputation Level | Cumulative Reputation (REP) | Unlocked Permissions and Concrete Rewards |
  |---|---|---|
  | Informal (Guest) | 0–4 | Can only take D-grade; guild provides basic intel |
  | Registered (Formal Probation) | 5–11 | Can take D/C-grade; borrow spirit tools (Soul-Calming Bell etc.) once per case |
  | Formal Ghost Collector | 12–23 | Can take B-grade; guild prioritizes case dispatch; 10% off rare materials |
  | Senior Ghost Collector | 24–39 | Can take A-grade; favor of three-lineage elders (Advantage on Invite Deity Possession Composure (CMP) check) |
  | Master (Regional Grandmaster) | 40+ | Can take S-grade; can take apprentices (Assistant); gains "Patriarch's Favor" passive (Advantage on Invite Deity Possession Composure (CMP) check + one free deity invitation per case) |

  - **③ Interaction with other systems**: Reputation (REP) only affects "what cases you can take" and "elder resources"; the "Patriarch's Favor" passive from S-grade completion is in this chapter's 13.5 special talent unlock. Yin Constable accountability (e.g., Ox-Head Bing) counts as breach of contract, deducting Reputation (REP) by circumstance.
- **Special Talent Unlock**: Even levels can learn new spells / talents; S-grade completion additionally grants a "Patriarch's Favor"-type passive (e.g., Advantage on Invite Deity Possession Composure (CMP) check).
- **Rare Spirit Tool Drops**: B-grade and above have a chance to obtain Century Peachwood Sword, Celestial Master Talisman, Soul-Calming Bell, Thunder-Struck Wood, Soul-Gathering Gourd.

---

## Chapter 14: Case File Template, Balance Formulas, and Three-Case Long Arc

### 14.1 Case File Template (scene-transition fields)

| Template Field | Scene Transition Method | GM Execution Tips |
|---|---|---|
| [Take Case] Client / initial description / initial case judgment | Opening hook: call or message, plant concealment | Knowledge (KNW) check to judge "real haunting or person-scaring-person" |
| [On-Site Investigation] Location / witnesses / Yin value / spirit identification / hidden info | Describe senses → give check → reveal clue | Hidden info revealed only on Intuition (INS) or Social success |
| [Prepare Rite] Spirit tools & materials / rite scale | Prep scene: checklist + time pressure | Where to find missing materials? Insufficient time raises risk |
| [Exorcise & Collect] Best / potential risks / alternatives | Climax scene: moral choice + check chain | Ask players "how do you intend to handle it" before giving Difficulty Class (DC) |
| [Cleanup] Purification / feedback / reward / unsolved mystery | Wrap-up scene: settle + hook | Leave one line of unsolved mystery to connect the next case or the S-line |

### 14.2 Encounter Difficulty Balance Formula

- **Player Total Power (PT)** = Σ player levels (or average level × number of players).
- **Encounter Level (EL)** = Σ enemy Challenge Rating (CR) (environmental Ghost Wall / Haunted House counted by their labeled Challenge Rating (CR); mobs take Challenge Rating (CR) 0.5 rounded).
- **Budget Cap (Budget)** = Player Total Power (PT) × Urgency Coefficient (K):

| Urgency | Coefficient K |
|---|---|
| D Harassment | ×0.5 |
| C Threat | ×0.8 |
| B Dangerous | ×1.0 |
| A Lethal | ×1.5 |
| S Disaster | ×2.5 |

- **Balance Criterion**: EL ≤ Budget → balanced and playable; EL at 100%–130% → high difficulty (adequate preparation advised); EL > 130% → too hard, GM should split the encounter or lower its tier. Non-combat resolution (successful negotiation / deliverance) does not count toward EL consumption.
- **GM Tweaks**: In solo mode all enemy Challenge Rating (CR) −1 (minimum 0) or player budget ×1.2; when environmental Yin Value (YIN) reaches Dead Zone (16+), the encounter automatically +1 EL; if players choose a "wrong handling method" (negotiating with a Fierce Ghost, attacking an Infant Spirit), temporarily +1~2 Challenge Rating (CR).

### 14.3 Three-Case Long Arc (with Nine Nether Hall sequel clues)

**S1: D/C-grade "The Red Raincoat in the Stairwell"** (suggested level 1–3, core: Bound Spirit)
- Hook: A tenant in an old Tong Lau in Sham Shui Po complains "every night at three, a woman in a red raincoat walks down and up the stairwell," and the property manager fears it won't rent.
- Core Mystery: The Bound Spirit is a Filipina domestic helper who fell to her death three years ago (falsely accused of theft and fired, she ran out in the rain and fell); every night she repeats "go downstairs to mail a letter to Mama" — the letter was never sent.
- Correct Handling: Non-combat. Investigation finds the letter (at the bottom of the mailbox), Intuition (INS) communication to hear the dying wish, prepare a Deliverance Rite to send her off; Soul-Calming Talisman lets her stay still to communicate. If trapped by a Ghost Wall on the stairwell, a Composure (CMP) check is needed to escape.
- Potential Risk: Directly dispersing her with an Exorcism Talisman → residual resentment, the Tong Lau becomes long-term Yin-chilled, guild deducts reputation.
- Reward: HK$5,000–10,000; Experience Points (EXP) 50–100 + investigation bonus; unlocks "First Deliverance" reputation.
- Hook: The letterhead is the "Shi Chu Shi" funeral home → leads to S2.

**S2: B-grade "The Seventh Drawer in the Mortuary"** (suggested level 4–6, core: Fresh Corpse / White Zombie + Resentful Ghost)
- Hook: Uncle Nine of Shi Chu Shi whispers: "The new corpse in drawer seven sat up by itself in the middle of the night. And... I heard his wife's voice in the corridor, but his wife passed away last month."
- Core Mystery: The newly deceased died in a medical dispute, unresolved in death → corpse change (Fresh Corpse → White Zombie); his wife's Resentful Ghost lingers for revenge over losing her husband (mistakenly believing the hospital killed him). The two stack.
- Correct Handling: Split up. Peachwood Sword / Corpse-Still Talisman physically suppress the corpse change (Prowess (PHS) check); the Medium uses Intuition (INS) communication to soothe the Resentful Ghost and ascertain the truth (deliberate misdiagnosis — plants Nine Nether Hall clues); Corpse-Still Talisman to fix it, glutinous rice to draw out corpse poison, deliver the couple.
- Potential Risk: White Zombie hard-skin −2, fears talismans; failed suppression spreads the corpse change (AOE crisis); if the Resentful Ghost won't negotiate it trends toward Fierce Ghost and must be subdued; the mortuary's "resolve before dawn" time pressure.
- Reward: HK$30,000–60,000; Experience Points (EXP) 200+; may drop Soul-Calming Bell (Rare).
- Hook: The misdiagnosis "lead surgeon" was instigated by someone behind the scenes; the clue points to a retired geomancer selling "life-extension folk remedies" → leads to S3.

**S3: A/S-grade "The Corpse-Cultivating Cellar beneath the Walled Village"** (suggested level 7–10, core: Fierce Ghost / Cultivated Zombie / Haunted House, deliberately refined by Nine Nether Hall)
- Hook: An entire ancestral home in a New Territories walled village is listed as a "Haunted House" with serial deaths; the village chief urgently requests guild aid; the Luopan Compass detects an abnormal underground feng shui layout.
- Core Mystery: "Seventh Uncle," head of Nine Nether Hall's Hong Kong station, built a corpse-cultivating cellar beneath the ancestral home, refining Cultivated Zombies (obeying the corpse-refiner) and nurturing a Fierce Ghost from the village's accumulated dead grievances as a gatekeeper; the Haunted House is a living nest.
- Correct Handling: Party division of labor — the Scholar uses Knowledge (KNW) to crack the feng shui layout and find the node-eye; the Warrior uses Prowess (PHS) to suppress the Cultivated Zombie (Black Zombie and above need century spirit tools); the Main Caster opens the altar + Demon-Sealing Array to imprison the Fierce Ghost; the key is to find and destroy Seventh Uncle — only when the Cultivated Zombie loses its control source does it collapse; full-house purification needs the party.
- Potential Risk: The Cultivated Zombie's Challenge Rating (CR) is far above natural zombies; the Fierce Ghost can't be negotiated with, only subdued / destroyed; the Haunted House's space is distorted (Ghost Wall + Dead Zone 16+ assimilation check each turn); if Seventh Uncle escapes, the Cultivated Zombie goes out of control and engulfs the whole village (S-grade disaster).
- Reward: HK$150,000+; Experience Points (EXP) 350–600; drops Thunder-Struck Wood / Celestial Master Talisman; major reputation for "Defeating Nine Nether Hall."
- Unsolved Mystery (sequel clues): ① Seventh Uncle left "the master awaits the great work's completion" — who is the mastermind behind it? ② The spirit tablet at the bottom of the corpse-cultivating cellar bears a name tied to the character's "case you couldn't handle." ③ A fragment of the "Life-Borrowing Register," listing celebrities who should be dead but still live — the forbidden art was never rooted out. ④ Yin Constable Ox-Head Bing comes to hold you accountable: the souls you delivered were on the underworld's register — who is tampering with the Book of Life and Death?

### 14.4 Random Spirit Encounter Table

When the GM needs to throw an impromptu encounter during an investigation lull, night patrol, or when players actively "night-explore a Haunted House," roll 1d20 against the table below (in solo mode you may instead roll 1d12 for the first half, or the GM assigns directly).

| d20 | Encounter | Type | Challenge Rating (CR) | Handling Points |
|---|---|---|---|---|
| 1–2 | Lost Soul (lonely ghost) | Communication-type spirit | 1 | Can communicate / deliver, no hostility |
| 3–4 | Night-Crying Infant Spirit | Spirit | 2 | Needs soothing or deliverance, avoid forced attack |
| 5–6 | Obsessed Bound Spirit | Spirit | 2–3 | Puzzle-focused, ascertain the dying wish |
| 7–8 | Substitute-Seeking Wronged Ghost | Spirit | 3 | Aggressive, needs suppression + deliverance |
| 9–10 | Freshly-Dead White Zombie | Zombie | 3 | Physical + talisman, glutinous rice draws poison |
| 11–12 | Fierce Black Zombie | Zombie | 4 | Needs century spirit tool, hard-skin −2 |
| 13–14 | Resentful Fierce Ghost | Spirit | 5 | Strong attack, only subdue / destroy |
| 15–16 | Ghost Wall (environment) | Environment | 3 | Composure (CMP) check to escape |
| 17–18 | On-Duty Yin Constable | NPC | 4 | Can cooperate or conflict (e.g., Bing's accountability) |
| 19 | Nine Nether Hall Lackey (probe) | Spirit / Human | 5 | S-line forward outpost, plants clues |
| 20 | Dead Zone Fluctuation (sudden Yin surge) | Environment | 4 | Yin Value (YIN) +4, forced assimilation check |

> After summing the Challenge Ratings (CR), please verify against the 14.2 balance formula: Encounter Level (EL) ≤ Budget Cap (Budget) means balanced and playable; if exceeded, split the encounter or lower its tier. In solo mode all enemy Challenge Rating (CR) −1 (minimum 0) or budget ×1.2.

---

## Appendix A: Complete Terminology Cross-Reference

| Chinese Full Name (Abbrev.) | Description |
|---|---|
| Prowess (PHS) | Physique, reflexes, melee |
| Dao Attainment (DOW) | Spell cultivation, talisman potency, lineage depth |
| Intuition (INS) | Perceiving the supernatural, communicating with spirits |
| Knowledge (KNW) | Folklore knowledge, funeral customs, spirit classification |
| Composure (CMP) | Mental endurance, willpower, Yin resistance |
| Health Points (HP) | Physical damage tolerance |
| Mana Pool (MP) | Energy for casting spells and drawing talismans |
| Yin Value (YIN) | Environmental or personal accumulated Yin pollution |
| Yin Threshold (YT) | Personal Yin tolerance cap (Composure ×2 + Dao Attainment) |
| Perception Range (PR) | Distance to perceive spirits (Intuition ×5 meters) |
| Possession Resistance (PRZ) | Bonus to resist possession / corpse poison (Composure modifier) |
| Difficulty Class (DC) | Check target value |
| Experience Points (EXP) | Gained from cases, used for leveling |
| Challenge Rating (CR) | Spirit / zombie strength tier |
| Attribute Modifier | FLOOR((Attribute Value−5)/2) |
| Total Bonus A | Attribute Modifier + Skill Level |
| Initiative (INIT) | Determines action order |
| Armor Class (AC) | 10 + Prowess modifier + Dodge level |
| Main Action (MA) | Primary action each turn |
| Move (MOVE) | Movement each turn (6 meters) |
| Bonus Action (BA) | Secondary action each turn |
| Area of Effect (AOE) | Area spell / effect |
| Nether Coin (COIN) | In-game common currency |

## Appendix B: Optional Rules and Variants

- **Higher Difficulty Variant**: When a multi-player group still finds it too easy, raise all Difficulty Class (DC) +2, enemy Challenge Rating (CR) +1, or bump the Urgency Coefficient (K) up one notch (e.g., B uses ×1.2). But solo mode is not recommended to add further, to avoid frustration.
- **Life-Borrowing Forbidden Art Aftermath (Variant)**: Beyond the base rule "lifespan −1 year + Composure (CMP) permanently −1, Yin Value (YIN) accumulates faster," you may add: each use of Life-Borrowing permanently lowers Yin Threshold (YT) −1, and the next time a Dead Zone (16+) is encountered, personal Yin Value (YIN) growth rate +1; if discovered by the guild, immediately "cleansed from the sect" (license to take cases revoked, hunted by the Three-Lineage Council).
- **Hardcore Death Variant**: Health Points (HP) reaching 0 and no first aid within 3 turns → character permanently dies (not savable by assimilation), forcing players to value preparation and retreat more.
- **Yin Assimilation Ending Variant**: Two consecutive Composure (CMP) check failures in a Dead Zone (16+), besides unconsciousness, may instead become "possessed by a specific spirit," leaving a long-term character arc (that spirit occasionally takes the lead in action), as a sequel foreshadowing for S3.

---

*This GM Rulebook was compiled by compiler-gm from six drafts: _compile_brief, _core_design, dice_mechanics, character_builder, combat_designer, world_crafter. All values and terminology formats are self-consistent with the source. With just this one book, the GM can fully and completely run Ghost Collector TRPG.*
