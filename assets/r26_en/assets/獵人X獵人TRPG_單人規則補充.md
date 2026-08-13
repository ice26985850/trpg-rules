# Hunter × Hunter TRPG — Solo Play Rules Supplement

> **Version:** v1.0
> **For:** 1 Player (PC) + 1 Game Master (GM)
> **Depends on:** Hunter × Hunter TRPG Player Handbook v1.0 + Game Master (GM) Handbook v1.0

---

## I. Why This Supplement Is Needed

The existing rules and scenarios are designed for **3–5 player parties**. The following core systems encounter problems in solo mode:

| System | Original Design Assumption | Solo Problem |
|------|------|------|
| **Encounter Points (EP) Encounter Budget** (GM Handbook §3-1) | Daily budget calculated for a 4-person party | 1 person cannot handle the enemy count meant for 4 |
| **Action Economy** (Player Handbook §3-1) | 1 standard + 1 move + 1 minor per round | A lone Player Character (PC) surrounded by multiple enemies cannot fight back effectively |
| **Reverse Declaration Order** (Player Handbook §3-1) | Multiple players declare in turn, read-ahead mind games | Solo declaration loses the "read-ahead" layer |
| **Group Check** (Player Handbook §1-6) | Multiple helpers grant a +2 bonus | Cannot trigger group check advantage |
| **Skill Coverage** (Player Handbook §1-4) | 4–5 people share 28 skills | 1 person can only be proficient in 6–8 skills |
| **Scenario Design** | Multi-track missions, team cooperation scenes | Some scenario segments cannot proceed (e.g., a trial that requires protecting teammates) |

Without altering the core rules, this supplement provides **solo-mode adjustment parameters, Non-Player Character (NPC) companion mechanics, and a skill-coverage solution**.

---

## II. Encounter Points (EP) Encounter Budget — Solo Adjustment

The daily Encounter Points (EP) budget in the original Game Master (GM) Handbook §3-1 is based on a "4-person party." Solo mode uses the following conversion:

### Solo Daily Encounter Points (EP) Budget

| PC Growth Stage | Original 4-person EP Budget | **Solo EP Budget** | Conversion |
|------|:---:|:---:|------|
| Rookie | 100 Encounter Points (EP) | **30 Encounter Points (EP)** | ÷ 3.3 |
| Apprentice Hunter | 300 Encounter Points (EP) | **90 Encounter Points (EP)** | ÷ 3.3 |
| Licensed Hunter | 800 Encounter Points (EP) | **240 Encounter Points (EP)** | ÷ 3.3 |
| Professional Hunter | 1,600 Encounter Points (EP) | **480 Encounter Points (EP)** | ÷ 3.3 |
| Star Hunter | 2,800 Encounter Points (EP) | **840 Encounter Points (EP)** | ÷ 3.3 |
| Legendary | 4,000+ Encounter Points (EP) | **1,200+ Encounter Points (EP)** | ÷ 3.3 |

> **Reference:** The original Encounter Points (EP) budget table is found in Game Master (GM) Handbook §3-1, "Daily Encounter Points (EP) Budget (4-person party)." The encounter difficulty multiplier (25%/50%/75%/100%) remains unchanged.

### Solo Encounter Example

A 4-person Apprentice Hunter party's moderate encounter = 300 × 50% = 150 Encounter Points (EP) (from the original Game Master (GM) Handbook §3-1 example)
→ **Solo Apprentice Hunter moderate encounter = 90 × 50% = 45 Encounter Points (EP)**

You may arrange: 1 Challenge Rating (CR) 1/4 enemy (25 Encounter Points (EP)) + 1 Challenge Rating (CR) 1 enemy, with the Player Character (PC) receiving Non-Player Character (NPC) companion assistance.

### Enemy Count Limit

In solo mode, the **maximum enemy count** in an encounter:

| PC Growth Stage | Enemy Max Without Companion | Enemy Max With 1 Companion |
|------|:---:|:---:|
| Rookie | 2 | 3 |
| Apprentice ~ Licensed | 3 | 4 |
| Professional and above | 4 | 5 |

> Exceeding the enemy cap causes action economy to collapse — a lone Player Character (PC) gets only 1 standard action per round and cannot respond effectively when surrounded by 5+ enemies.

---

## III. Non-Player Character (NPC) Companion System

In solo mode, the Game Master (GM) may assign the Player Character (PC) **1 Non-Player Character (NPC) companion**. A companion is not a second Player Character (PC) — their capabilities are limited, and they mainly fill action-economy gaps and skill coverage.

### Companion Rules

| Item | Rule |
|------|------|
| **Action** | The companion gets 1 standard action per round (no move/minor/reaction). The companion's Initiative is fixed to come after the Player Character (PC). |
| **Control** | In combat, the **PC player** decides the companion's actions. Outside combat, the Game Master (GM) plays the companion. |
| **Hit Points (HP) / Spirit Points (SP)** | The companion has independent Hit Points (HP) and Spirit Points (SP); once dead, it cannot be revived within the current scenario. |
| **Growth** | The companion does not gain Experience Points (XP). When the Player Character (PC) advances a Growth Stage, the companion advances together (see table below). |
| **Limit** | Each Player Character (PC) may carry at most 1 companion at a time. |

### Companion Growth Table

| PC Stage | Companion CR | Companion HP | Companion SP | Companion Skills |
|------|:---:|:---:|:---:|:---:|
| Rookie | 1/2 | 30 | 15 | 2 Proficient (+2) |
| Apprentice Hunter | 1 | 45 | 25 | 3 Proficient (+2) |
| Licensed Hunter | 3 | 70 | 40 | 4 Proficient (+2) |
| Professional Hunter | 5 | 100 | 60 | 4 Proficient (+2) + 1 Expert (+4) |
| Star Hunter | 7 | 140 | 80 | 5 Proficient (+2) + 1 Expert (+4) |
| Legendary | 9 | 180 | 100 | 5 Proficient (+2) + 2 Expert (+4) |

### Companion Nen Abilities

A companion may possess 1 Nen ability (no Binding Pledge points (BP) design needed; the Game Master (GM) selects from the table below or customizes):

| Companion Type | Nen Ability | Effect |
|------|------|------|
| Combat | Covering Fire | Spend 2 Spirit Points (SP); the Player Character (PC)'s next attack gains advantage |
| Defense | Guardian Barrier | Spend 3 Spirit Points (SP); the Player Character (PC) gains +2 Armor Class (AC) for 2 rounds |
| Support | Emergency Treatment | Spend 3 Spirit Points (SP); the Player Character (PC) recovers 1d8+2 Hit Points (HP) |
| Intel | Weakness Analysis | Spend 2 Spirit Points (SP); target enemy's Armor Class (AC) −2 for 1 round |
| Disruption | Restraining Strike | Spend 2 Spirit Points (SP); target enemy's next-round attack has disadvantage |

> **Reference:** Companion combat action rules follow Player Handbook §3-1 (Action Economy); companions use a standard action to perform attacks or Nen abilities.

### Companion Excel Card

See the accompanying `獵人X獵人TRPG_NPC合集.xlsx` ("NPC Companion Template" tab), or manually create one using a blank Non-Player Character (NPC) card.

---

## IV. Reverse Declaration Order — Solo Adjustment

The reverse declaration order in the original Player Handbook §3-1 is designed for multiplayer mind games. In solo mode it is adjusted as follows:

**The Game Master (GM) first declares enemy intent (a vague description), then the Player Character (PC) declares their action.**

> **Example:** Game Master (GM): "The thief leader looks like he's preparing to charge at you (standard action: melee attack), and his lieutenant is waiting nearby for an opening (readied action: shoot if you move)."
> Player Character (PC): "Then I'll use a Nen bullet on the lieutenant first, then move behind cover."
>
> This preserves the "read-ahead" strategic layer — the Player Character (PC) still needs to decide their action based on the Game Master (GM)'s declaration.

---

## V. Group Check — Solo Alternative

The group check in the original Player Handbook §1-6 (helper with Difficulty Class (DC) 10 grants the main actor +2) is unavailable in solo mode. The alternative:

| Original Group Check Scenario | Solo Alternative |
|------|------|
| Skill check needing assistance | If an NPC companion is present and proficient in that skill, automatically gain +2 (no assisting check roll needed) |
| Multiple people attempting simultaneously | Changed to a solo attempt; Difficulty Class (DC) reduced by 2 |
| Team success determination (at least half succeed) | Not applicable |

---

## VI. Skill Coverage Solution

A single Player Character (PC) gains 6–8 proficiency points at character creation (Player Handbook §1-4) and can only cover 3–4 proficient skills. Recommendations:

1. **At character creation, ensure coverage of at least:** 1 combat skill (melee or Nen attack) + 1 social skill (Persuasion or Insight) + 1 exploration skill (Perception or Survival)
2. **Let the NPC companion fill the gaps:** when choosing a companion type, prioritize having the companion be proficient in skills the Player Character (PC) does not cover
3. **Attribute substitution:** In solo mode, the Game Master (GM) relaxes the Difficulty Class (DC) for "Unskilled checks" — when the Player Character (PC) must use an unskilled skill, the base Difficulty Class (DC) is reduced by 3 (because there are no teammates to help)

---

## VII. Solo Adjustment for the Original Scenarios

The existing 10 main scenarios + 52 side quests are all designed for multiple players. The Game Master (GM) uses the following conversion table for quick adjustment:

### Multiplayer → Solo Quick Conversion

| Original Scenario Element | Solo Adjustment |
|------|------|
| Enemy count | Count ÷ 3 (minimum 1) |
| Enemy CR | CR − 2 (minimum CR 1/4) |
| Time limit | Extended by 50% (solo requires more rounds) |
| Simultaneous multi-track missions | Changed to linear — the PC handles each track one by one |
| Scenes requiring "protect teammates" | Changed to "protect NPC companion" or "protect key item" |
| Puzzles requiring "teamwork" | Changed to NPC companion assistance, or PC gains a hint (Intelligence DC reduced by 5) |

### Scenes That Cannot Be Soloed

The following scenes were originally designed to deeply rely on multiplayer interaction, and **forcing them into solo play is not recommended** — use the standalone solo scenario collection in this supplement as a replacement:

- Scenario 1 "Hunter Exam," Scene 3 (Mirror Maze — requires two people to cooperate on a switch)
- Scenario 5 "Trial of the Gate," "Proof of Guardianship" (originally designed to protect teammates)
- Scenario 7 "Kakin Throne" (the social network of multiple princes cannot be condensed)

> **Alternative:** See the standalone solo scenario collection, which designs dedicated solo plots for each stage.

---

## VIII. Solo Experience Points (XP) Acquisition Adjustment

The Experience Points (XP) acquisition table in the original Player Handbook §2-9 is slightly adjusted for solo mode:

| Source | Original XP | Solo XP | Reason |
|------|:---:|:---:|------|
| Combat victory (easy) | 1 | 2 | Solo combat is relatively harder |
| Combat victory (hard) | 3–5 | 4–6 | Same as above |
| Complete Hunter commission | 2–5 | 3–6 | Solo completion equals whole-party completion |
| Character story milestone | 3–10 | Unchanged | Personal growth is unaffected by party size |

> The remaining Experience Points (XP) acquisition items (Nen ability use, restriction discovery, attendance bonus) remain unchanged.

---

> **Companion Documents:**
> - 📘 `獵人X獵人TRPG_單人劇本集_v1.pdf` — 5 standalone solo scenarios, covering Rookie → Legendary
> - 📊 `獵人X獵人TRPG_NPC合集.xlsx` ("NPC Companion Template" tab)

> **Version History**
> - v1.0 (2026-06-29): Initial release. Solo adjustment of the Encounter Points (EP) budget, Non-Player Character (NPC) companion system, solo adaptation of reverse declaration, skill coverage solution, and original scenario conversion table.
