# Lord of the Mysteries TRPG — Player Rulebook v1.0

> **This handbook contains all the rules the player needs:** core mechanics, character creation, pathway powers, and basic combat.
> For GM-exclusive content (worldview, modules, encounter design, NPC stats), please refer to the *GM Rulebook*.

---

# Chapter One: Core Rules

## 1.1 Dice Basics

This system uses a **d100 percentile die (roll-under)**. Roll 1d100; if the result is ≤ the Target Number (TN), the check succeeds.

| Term | Abbrev. | Definition |
|------|---------|------------|
| Target Number | TN | The value a check must be ≤; usually an attribute value or attribute + skill value |
| Difficulty Modifier | DC | A bonus/penalty to the TN, e.g., Difficult (−20), Extreme (−40) |
| Advantage | Adv | Roll two dice, take the lower — greatly increases probability |
| Disadvantage | Dis | Roll two dice, take the higher — greatly lowers probability |
| Critical Success | Crit | Result ≤ 5 — guaranteed success with an enhanced effect |
| Critical Failure | Fumble | Result ≥ 96 — guaranteed failure with a negative consequence |
| Spirit Pool | SP | The energy resource used to power Beyonder abilities |
| Loss of Control | LoC | The accumulated measure of Beyonder corruption |
| Loss of Control Threshold | LoCT | Mind × 2 + 10 |

---

## 1.2 The Five Attributes

| Attribute | Meaning | Affected Areas |
|-----------|---------|----------------|
| **Spirituality (SPI)** | Fuel for Beyonder powers, inspiration | Spirit Pool size, divination/spirit-sight/ritual checks |
| **Mind (MND)** | Reason, logic, memory | Loss of Control Threshold, knowledge checks, resisting mental effects |
| **Body (BOD)** | Physical strength, endurance | HP, resistance to toxin/disease |
| **Agility (AGI)** | Dexterity, coordination, combat | Melee/ranged, stealth, initiative, dodge |
| **Charisma (CHA)** | Charm, social, performance | Negotiation/deception, disguise, maintaining "Surface Life" |

### Starting Attribute Allocation

- Each attribute starts at a base of **30**, with **50 points** freely allocated.
- Single-attribute cap 80, floor 30.
- Total: 30 × 5 + 50 = 200.

**Quick-build templates:**

| Template | SPI | MND | BOD | AGI | CHA |
|----------|-----|-----|-----|-----|-----|
| Spirit Caster | 60 | 45 | 35 | 30 | 30 |
| Martial Warrior | 30 | 40 | 55 | 50 | 25 |
| Agile Assassin | 30 | 35 | 30 | 65 | 40 |
| Social Manipulator | 30 | 40 | 30 | 35 | 65 |
| Versatile Scholar | 45 | 55 | 30 | 35 | 35 |

### Derived Attributes

| Attribute | Formula |
|-----------|---------|
| Health Points (HP) | **Body × 2 + 15** |
| Spirit Pool (SP) | **Spirituality × 3 + 5** |
| Loss of Control Threshold (LoCT) | **Mind × 2 + 10** |
| Loss of Control (LoC) | Starts at **0**, accumulates dynamically |
| Initiative | Agility + d10 (rolled once at combat start) |

---

## 1.3 Attribute Growth

Attribute points are freely allocated upon Sequence promotion:

| Promotion | Attribute Points Gained | Per-Attribute Cap |
|-----------|------------------------|------------------|
| 9 (starting) | 0 | 80 |
| 9→8 | +7 | 85 |
| 8→7 | +7 | 90 |
| 7→6 | +8 | 95 |
| 6→5 | +8 | 100 |
| 5→4 | +8 | 105 |
| 4→3 | +9 | 110 |
| 3→2 | +9 | 115 |
| 2→1 | +10 | 120 |
| 1→0 | +10 | 125 |

---

## 1.4 Difficulty Ladder

| Difficulty | Modifier | Description | Success Rate at Attr 50 |
|-----------|----------|-------------|--------------------------|
| Routine | ±0 | Everyday action | 50% |
| Difficult | −20 | Professional skill, time pressure | 30% |
| Extreme | −40 | Extreme environment | 10% |
| Legendary | −60 | Beyond human limits | 0% (requires skill bonus) |

- Modifiers are added/subtracted directly to the Target Number. Floor 1, ceiling 95.
- Multiple modifiers stack (e.g., Difficult −20 + in darkness −20 = effectively Extreme −40).

---

## 1.5 Critical Success and Critical Failure

- **Critical Success:** result ≤ 5 — guaranteed success with an enhanced effect (damage doubled, extra information, etc.).
- **Critical Failure:** result ≥ 96 — guaranteed failure with a negative consequence (weapon jam, +1d3 LoC, etc.).

---

## 1.6 Advantage and Disadvantage

**Advantage:** roll 2d100, take the lower. | **Disadvantage:** roll 2d100, take the higher.

### Advantage Triggers
1. Abundant Spirituality (Spirit Pool ≥ 75%)
2. Adequate preparation (at least 10 minutes spent)
3. Teammate assistance (related skill TN ≥ 40)
4. Target exposes a weakness
5. Correct mystical environment

### Disadvantage Triggers
1. **Whisper stage:** LoC at 50–75% of threshold — all Mind checks at disadvantage
2. Rushed action
3. Fear/Charm status
4. Spirit Exhaustion (Spirit Pool < 25%)
5. Environmental interference

If both Advantage and Disadvantage apply, they cancel and a normal 1d100 is rolled.

| TN | Normal | Advantage | Disadvantage |
|----|--------|-----------|--------------|
| 30 | 30% | 51% | 9% |
| 50 | 50% | 75% | 25% |
| 70 | 70% | 91% | 49% |

---

## 1.7 Opposed Checks

Both sides roll 1d100 and compare success tiers:

1. Critical Success (≤5) > Ordinary Success (≤TN) > Failure > Critical Failure (≥96)
2. Within the same tier, compare degree of success (TN − result); the higher wins.
3. If exactly equal, the defender/passive side wins.

---

## 1.8 Spirit Pool

**Maximum = Spirituality × 3 + 5**

### Expenditure Baseline

| Power Tier | On-Path Cost | Off-Path Cost | Applies To |
|------------|--------------|---------------|------------|
| Cantrip/Low | 1–3 points | 3–5 points | Sequences 9–8 |
| Low | 5–8 points | 7–10 points | Sequences 7–6 |
| Mid | 10–15 points | 15–20 points | Sequences 5–4 |
| High | 18–25 points | 25–35 points | Sequences 3–2 |

> "On-Path": using your own pathway's powers, cost reduced by roughly 30%.

### Spirit Recovery

| Method | Recovery | Limit |
|--------|----------|-------|
| Full rest (8 hours) | Spirituality × 2 | Once per night |
| Brief meditation (1 hour) | Spirituality × 0.5 | Up to twice per day |
| Sequence promotion | Refill instantly | One-time |

**Spirit Exhaustion:** once the Spirit Pool hits zero, spirit-related checks are at disadvantage and Beyonder powers cannot be used.

---

## 1.9 Loss of Control System

### Accumulating Loss of Control

| Trigger | LoC |
|---------|-----|
| Using an off-path Beyonder power | +1d3 |
| Using an on-path Beyonder power | +1 |
| Spirit Pool fully depleted | +2d5 |
| Critical Failure (any check) | +1d3 |
| Witnessing a Mythical Creature's form | +1d10+5 |

### Four Stages of Loss

| Stage | Range | Effect |
|-------|-------|--------|
| **Stable** | < 50% of threshold | Normal, safe and controllable |
| **Whisper** | 50%–75% of threshold | Whispers in the mind; **all Mind checks at disadvantage** |
| **Mutation** | 75%–100% of threshold | Whisper + **Charisma checks at disadvantage** + bodily mutation traits appear |
| **Edge of Loss** | ≥ 100% of threshold | Must make a **Loss Check** before each use of a Beyonder power |

### Loss Check

When LoC ≥ LoCT, before each use of a Beyonder power: **roll d100 ≤ Mind** (pure attribute, no skill bonus).

- **Success:** power works normally, LoC +2.
- **Failure:** Complete Loss of Control — GM takes over for 1d6 rounds, Spirit Pool drops to zero, permanent loss of 1 Mind.

### LoC Subsiding

| Method | Reduction |
|--------|-----------|
| Full rest (no powers used) | −5 |
| Completing a core Acting action | −3 |
| Receiving psychotherapy | −5 |
| Sequence promotion | Halved |

---

## 1.10 Skill System

### General Skills (18)

| # | Skill | Linked Attribute | Use |
|---|-------|------------------|-----|
| 1 | Observation | Mind | Notice details, find clues |
| 2 | Listening | Mind | Eavesdrop, identify sounds |
| 3 | Stealth | Agility | Silent movement, tailing |
| 4 | Concealment | Agility | Hide items, ambush |
| 5 | Negotiation | Charisma | Persuade, negotiate, bargain |
| 6 | Deception | Charisma | Lie, disguise identity |
| 7 | Intimidation | Body | Threaten, extort |
| 8 | Knowledge | Mind | History, science, law |
| 9 | Mysticism | Spirituality | Ritual recognition, Beyonder knowledge |
| 10 | Medicine | Mind | First aid, surgery, diagnosis |
| 11 | Driving | Agility | Carriage/train/ship |
| 12 | Shooting | Agility | Pistol, rifle |
| 13 | Melee | Body | Fists, close combat |
| 14 | Investigation | Mind | Search, analyze evidence |
| 15 | Sleight of Hand | Agility | Steal, pick locks |
| 16 | Performance | Charisma | Disguise a role, oration |
| 17 | Etiquette | Charisma | High-society socializing |
| 18 | Survival | Body | Wilderness survival, tracking |

**Skill base value = linked attribute value.** Skill cap = linked attribute + 40.

### Pathway-Exclusive Skills

Sequence 9 grants the 1st pathway skill (**+20**), Sequence 7 the 2nd (**+15**), Sequence 5 the 3rd (**+15**), Sequence 3 the 4th (**+10**).

### Skill Growth

During interludes, for each skill with a "growth mark," roll d100: if the result > current skill value → +1d10; if result ≤ current → +1.

---

# Chapter Two: Character Creation

## 2.1 The Seven-Step Creation Method

### Step 1: Mortal Identity

Roll d100 or choose freely:

| d100 | Class | Starting Funds | Social Connections |
|------|-------|----------------|--------------------|
| 01–15 | Slum Orphan | 1d10 pence | 1× Street Acquaintance |
| 16–30 | Working Class | 2d10 sol | 2× Coworker |
| 31–50 | Lower Middle Class | 1d6 gold pound | 2× Colleague, 1× Landlord |
| 51–70 | Middle Class | 3d6 gold pound | 2× Colleague, 1× Mentor |
| 71–85 | Upper Middle Class | 5d10 gold pound | 2× Client, Club Member |
| 86–95 | Minor Noble/Gentleman | 10d10 gold pound | 2× Servant, 1× Noble Acquaintance |
| 96–100 | Noble/Upper Class | 50d10 gold pound | 4× Servant, 2× Political Ally, 1× Enemy |

**Mortal Identity Questionnaire:**
1. Place of birth? Family situation?
2. Level of education?
3. What did you live on before taking the potion?
4. Do you have family? Do they know you are a Beyonder?
5. Who is your best friend? Who is the person you hate most?

### Step 2: Attribute Allocation

Base 30 + 50 freely allocated, single attribute 30–80. The quick-build templates from §1.2 may be used.

### Step 3: Choose Pathway and Starting Sequence

Choose from the 22 pathways, default starting Sequence 9. The GM may allow a start at Sequence 8 or 7.

| # | Pathway | Core Role | Recommended For |
|---|---------|-----------|-----------------|
| 1 | **Fool** | Fate Sense / Avatar / Parasite | Players who enjoy narrative progression and secret-digging |
| 2 | **Door** | Teleport / Record / Exploration | Players who enjoy mobility and creative space |
| 3 | **Error** | Pickpocket / Deception / Time Parasite | Players who enjoy outsmarting and indirect confrontation |
| 4 | **Sun** | Light / Purification / Word of Command | Players who enjoy supporting allies and banishing evil |
| 5 | **Tyrant** | Lightning / Ocean / Fury | Players who enjoy high damage and natural forces |
| 6 | **White Tower** | Knowledge / Deduction / Machinery | Players who enjoy investigation and intellectual combat |
| 7 | **Hanged Man** | Dark / Flesh / Shepherding | Players who enjoy high-risk high-reward |
| 8 | **Visionary** | Mind Reading / Hypnosis / Dreams | Players who enjoy control and support roles |
| 9 | **Darkness** | Night / Nightmare / Soul Assurance | Players who enjoy the lone wanderer in the dark |
| 10 | **Death** | Undead / Spirit Medium / Immortality | Players who enjoy summoning and death themes |
| 11 | **Twilight Giant** | Versatile Combat / Guard | Players who enjoy the most direct combat |
| 12 | **Demoness** | Assassination / Poison / Curse | Players who enjoy single-target high damage and intrigue |
| 13 | **Red Priest** | Tracking / Fire / War | Players who enjoy hunting and battlefield control |
| 14 | **Moon** | Potion-making / Beast Taming / Blood | Players who enjoy crafting and the mysteries of life |
| 15 | **Mother** | Plants / Healing / Transformation | Players who enjoy healing and natural forces |
| 16 | **Chained** | Berserk / Beastform / Wraith | Players who enjoy unpredictable combat |
| 17 | **Abyss** | Cold-blooded / Contract / Corruption | Players who enjoy exploiting rules and temptation |
| 18 | **Hermit** | Secrets / Ritual / Constellations | Players who enjoy digging for the truth |
| 19 | **Paragon** | Encyclopedia / Crafting / Invention | Players who enjoy being versatile and creative |
| 20 | **Wheel of Fortune** | Luck / Probability / Fate | Players who enjoy randomness and high risk |
| 21 | **Justiciar** | Rules / Truth / Edict | Players who enjoy order and judgment |
| 22 | **Black Emperor** | Defense / Distortion / Chaos | Players who enjoy using rules against rules |

### Step 4: The First Potion

Roll d10 or choose freely:

| d10 | How Acquired | Starting Resource | Plot Hook |
|-----|--------------|-------------------|-----------|
| 1–2 | Inheritance | Potion notes, old letters | Search for the truth of a parent's disappearance |
| 3–4 | Purchase | Larger remaining funds | Owes a favor to a black-market merchant |
| 5–6 | Forced to Drink | No choice, bears scars | Hunt down who wronged you |
| 7–8 | Mentor Guidance | Mentor connection, basic knowledge | The mentor has ulterior motives |
| 9–10 | Accidental Acquisition | By chance, not fully understood | Targeted by some organization |

### Step 5: Surface Life

Roll d20 or choose freely:

| d20 | Profession | Monthly Income |
|-----|-----------|----------------|
| 1–3 | Detective | £3–8 |
| 4–6 | Reporter | £2–5 |
| 7–9 | Bookstore / Antique Shop Owner | £2–4 |
| 10–12 | Doctor | £5–10 |
| 13–15 | Lawyer / Legal Clerk | £4–8 |
| 16–17 | Teacher / Scholar | £2–4 |
| 18–19 | Artist / Performer | £1–5 |
| 20 | Free choice | — |

### Step 6: Core Motivation

Roll d8 or choose freely:

| d8 | Motivation | Acting Guide |
|----|------------|--------------|
| 1 | Revenge | Deep hatred of someone/an organization — what after revenge? |
| 2 | Protection | Protect someone/somewhere — are you strong enough? |
| 3 | Curiosity | The Beyonder world is too fascinating — digging too deep brings backlash |
| 4 | Called | Something calls you in dreams — what does it want? |
| 5 | Atonement | Mistakes of the past — can they ever be atoned? |
| 6 | Belonging | Want to find a group that accepts Beyonders |
| 7 | Power Itself | Just want to grow stronger — but power has a price |
| 8 | Fate | Feel chosen — is it real? |

### Step 7: Calculate Derived Attributes

- HP = Body × 2 + 15
- Spirit Pool = Spirituality × 3 + 5
- Loss of Control = 0
- Loss of Control Threshold = Mind × 2 + 10
- Initiative = Agility + d10 (rolled in combat)

---

## 2.2 Eight Key Pathways: Sequence 9 Ability Cards

### Fool Pathway · Sequence 9 Seer
**Recommended attributes:** Spirituality primary, Mind secondary

| Power | Cost | Effect |
|-------|------|--------|
| **Pendulum Divination** | 3 Spirit | d100 ≤ Spirituality+15, gain vague information about the future |
| **Dream Interpretation** | 5 Spirit | Spirituality+15, recall yesterday's dream for symbolic clues |
| **Spirit Sight** | 5 to activate +2/min | Sense lingering spirit traces, Beyonder marks |

**Acting notes:** "A Seer must truly believe the divination results." Use divination to help a neighbor find a cat (passive +1), foresee danger (active +3), make an accurate prophecy you refuse to believe and watch it come true (core +5).

### Door Pathway · Sequence 9 Apprentice
**Recommended attributes:** Spirituality primary, Agility secondary

| Power | Cost | Effect |
|-------|------|--------|
| **Open Door** | 2 Spirit | d100 ≤ Spirituality+20, unlock/open a locked door |
| **Blink** | 8 Spirit | Teleport 5m, does not trigger opportunity attacks |
| **Spatial Sense** | 3 Spirit | Sense hidden spaces and anomalies within 20m |

### Tyrant Pathway · Sequence 9 Sailor
**Recommended attributes:** Body primary, Spirituality secondary

| Power | Cost | Effect |
|-------|------|--------|
| **Underwater Breathing** | Passive | Breathe underwater indefinitely, swim speed ×2 |
| **Lightning Touch** | 3 Spirit | Melee adds 2d6 lightning; Body fail → Paralysis; vs metal armor 2d8 + save at disadvantage |
| **Call Lightning** | 5 Spirit | 20m / 3d6 lightning damage, target at dodge disadvantage |

### White Tower Pathway · Sequence 9 Reader
**Recommended attributes:** Mind primary, Spirituality secondary

| Power | Cost | Effect |
|-------|------|--------|
| **Speed Reading & Memory** | 4 Spirit | d100 ≤ Mind+20, finish and remember the key points of a text in one minute |
| **Tactical Analysis** | 2 Spirit | Analyze all enemies; GM reveals one weakness of each enemy |
| **Weakness Insight** | Reaction / 2 Spirit | +15 hit to one ally attack, +1d4 precision damage |

### Visionary Pathway · Sequence 9 Spectator
**Recommended attributes:** Mind primary, Charisma secondary

| Power | Cost | Effect |
|-------|------|--------|
| **Emotion Reading** | 0 AP quick / 1 Spirit | Opposed vs target's Mind, read surface emotions |
| **Presence Concealment** | 1 AP / 3 Spirit | d100 ≤ Charisma, enemies −20 to hit you; ends if you attack |
| **Microexpression Analysis** | Reaction / 2 Spirit | GM reveals the target's next action category |

### Darkness Pathway · Sequence 9 Sleepless
**Recommended attributes:** Agility primary, Body secondary

| Power | Cost | Effect |
|-------|------|--------|
| **Never Sleep** | Passive | Immune to sleep, never need to sleep |
| **Night Vision** | Passive | See 50m in darkness, +10 to all skills in dark |
| **Power of Darkness** | 1 AP / 3 Spirit | 10m / 2d8 dark damage (3d8 at night); Body fail → Blind 1 round |

### Twilight Giant Pathway · Sequence 9 Warrior
**Recommended attributes:** Body primary, Agility secondary

| Power | Cost | Effect |
|-------|------|--------|
| **Combat Instinct** | Passive | Weapon proficiency +10, Initiative +2, HP +5 |
| **Power Strike** | 2 AP / 3 Spirit | Damage dice doubled; Body fail → knockback 3m + Stun |
| **Iron Will** | Reaction / 2 Spirit | Opposed vs Fear/Charm Mind +20; on fail effect halved in duration |

### Red Priest Pathway · Sequence 9 Hunter
**Recommended attributes:** Agility primary, Mind secondary

| Power | Cost | Effect |
|-------|------|--------|
| **Tracking Mark** | 1 AP / 2 Spirit | Mark up to 2 targets, +10 to attacks, tracking at advantage |
| **Precision Shot** | 2 AP / 2 Spirit | Ranged +20 hit, +1d6 precision damage (ignores armor) |
| **Trap Intuition** | Reaction / 1 Spirit | Automatically notice traps within 10m, GM secretly rolls a warning |

---

## 2.3 Sequence Promotion

### Four Conditions for Promotion

1. **Acting Progress 100%** — independent 0–100 per Sequence.
2. **Potion Materials** — main material (Beyonder Characteristic) + auxiliary materials.
3. **Promotion Ritual** — required from Sequence 5 upward.
4. **Mind Check** — d100 ≤ Mind, with penalties rising by Sequence (up to Mind −30). Failure means permanent +5 LoC.

### Gaining Acting Progress

| Acting Tier | Progress | Description |
|-------------|----------|-------------|
| Passive Acting | +1 / scene | Daily behavior fits the Sequence role |
| Active Acting | +3 / scene | Deliberately solving problems as the Sequence role |
| Core Acting | +5 / scene | Completing the Sequence's essential act and bearing the consequences |

> Suggested 5–15 points per game session. **Acting is not "wearing a costume" — it is truly "becoming" that Sequence role.**

---

## 2.4 Equipment and Economy

### Currency

- 1 gold pound (£) = 20 sol (s) = 240 pence (d)

### Weapons

| Weapon | Damage | Range | Reload | Price |
|--------|--------|-------|--------|-------|
| Derringer Pistol | 1d8 | 10m | 2 rounds / 1 AP | £2 |
| Military Revolver | 2d6 | 20m | 6 rounds / 1 AP | £5 |
| Rifle | 2d8+2 | 80m | 1 round / 2 AP | £12 |
| Shotgun | 3d6 (close) / 1d6 (far) | 10m / 30m | 2 rounds / 1 AP | £8 |
| Dagger | 1d6 | Melee | — | 5s |
| Longsword | 2d6 | Melee | — | £2 |
| Two-handed Sword | 2d8 | Melee | — | £5 |

### Armor

| Armor | Defense Value | Weight | Price |
|-------|---------------|--------|-------|
| Heavy Coat | +1 | 2kg | £1 |
| Leather Armor | +2 | 3kg | £3 |
| Chainmail | +5 | 12kg | £15 |

### Encumbrance

- Light load (≤ Body × 2 kg): normal.
- Medium load: Agility −10.
- Heavy load: Agility −20, cannot run.

---

# Chapter Three: Combat Rules

## 3.1 Round Structure

```
┌──────────────────────────────────────────────┐
│              Combat Round                      │
├──────────────────────────────────────────────┤
│ 1. Declaration Phase: GM describes the         │
│    situation and states intent                 │
├──────────────────────────────────────────────┤
│ 2. Action Phase: in Initiative order,          │
│    3 AP per character                          │
├──────────────────────────────────────────────┤
│ 3. Resolution Phase: ongoing damage, Loss      │
│    checks, environment                         │
└──────────────────────────────────────────────┘
```

### Initiative

**Initiative = Agility + d10** (rolled once at combat start), acting from high to low. An ambusher gains +5 Initiative on the first round.

### 3 AP Action Economy

**Standard Action (1 AP):**
- Attack: attack with a weapon
- Use Beyonder power: cast a power that costs 1 AP
- Reload: revolver 6 rounds / 1 AP; rifle 1 round / 2 AP
- Use item: drink a potion, throw an item
- First Aid: d100 ≤ Body, recover 1d6 HP (once per target per scene)
- Ready Action: set a trigger condition, executed when triggered this round

**Movement Action (1 AP):**
- Standard move: up to 10m
- Sprint: up to 20m, but attacks against you get +10 hit
- Crawl / Stand up

**Quick Action (0 AP, once per round):**
- Draw / sheathe a weapon
- Brief command (within 10 words)
- Observe: quick scan of the battlefield

**Reaction Action (spends next round's AP, up to 2 AP per round):**
- Dodge: when hit, d100 ≤ Agility, avoid completely
- Block: when hit in melee, d100 ≤ Agility + weapon skill, halve damage
- Opportunity Attack: when an enemy leaves melee range
- Cover: take damage in place of an adjacent ally

---

## 3.2 Attack and Damage

### Attack Check

**d100 ≤ (Agility + weapon skill bonus − armor defense − cover modifier)**

Weapon skill: untrained +0 / basic +10 / proficient +20 / expert +30 / master +40

Defense sources: armor defense (+1~+10), shield (+1~+5), cover (half −15 / full −25), prone (ranged −10), close-range firearm (<3m) +10

> Reaction Dodge (spends AP): when hit, roll d100 ≤ Agility; success avoids completely. Block is melee only. Dodge and Block limited to once each per round.

### Damage Formula

- **Melee:** weapon base dice + Body modifier (Body/5, rounded down)
- **Ranged:** weapon base dice

| Melee Type | Base Damage | Example |
|------------|-------------|---------|
| Light | 1d8 + Body modifier | Dagger, short club |
| Medium | 2d6 + Body modifier | Longsword, saber |
| Heavy | 2d8 + Body modifier | Two-handed sword, war hammer |
| Unarmed | 1d4 + Body modifier | Fists |

### Damage Types

| Type | Special Effect |
|------|----------------|
| Slashing | Can cause Bleeding |
| Piercing | +2 vs unarmored |
| Blunt | Not halved vs heavy armor |
| Light | ×2 vs Dark |
| Dark | Inflicts Curse |
| Fire | Inflicts Burning |
| Lightning | +1d6 vs metal armor |
| Mental / Spiritual | Ignores physical armor |

**Resistance:** Immune (fully unaffected) / High (halved) / Low (−2) / Weakness (×1.5)

### Dying and Healing

**HP ≤ 0 → Dying:** each round d100 ≤ Body to stabilize; on failure HP keeps dropping −1d6; on Critical Failure, immediate death. Death at HP reaching −(Body × 2).

**Healing:** First Aid (1 AP / recover 1d6 / once per scene), Bandage (after battle / Body modifier × 2), Full Rest (1 day / Body × 2).

---

## 3.3 Status Effects

| # | Status | Effect | Duration |
|---|--------|--------|----------|
| 1 | **Fear** | Attack/power −15, cannot approach fear source | 1d3+1 rounds |
| 2 | **Charm** | Cannot attack charm source, opposed at disadvantage | 1 scene |
| 3 | **Stun** | AP = 0, no reactions, +20 to be hit | 1 round |
| 4 | **Bind** | Move 0, cannot dodge | until escaped |
| 5 | **Burning** | 1d6 fire damage per round, −5 to actions | 1d3 rounds |
| 6 | **Poison** | 1d4 poison damage per round, Body/Agility −10 | 1d6 rounds |
| 7 | **Bleeding** | 1d4 bleeding per round | until bandaged |
| 8 | **Curse** | All checks −10, Critical Failure 91–00 | 1 scene |
| 9 | **Blind** | Attack −30, cannot dodge ranged | 1d3 rounds |
| 10 | **Whisper State** | Each round, Mind fail → lose 1 AP | 1d3+1 rounds |
| 11 | **Mutation State** | Social −20, Beyonder damage +1d4 | until LoC < 75% |
| 12 | **Paralysis** | AP = 0 / partial: lose 1 AP | 1d2 rounds |

**Stacking:** same-name does not stack (refresh duration). With multiple statuses, take the highest penalty + half the second-highest. 3+ negative statuses → GM may add 1 extra LoC.

---

## 3.4 Sealed Artifact Usage Rules

Sealed Artifacts are powerful double-edged swords. Before use, make a **Mysticism check** where possible to learn their positive effects.

| Tier | Danger | Side-effect Intensity | Example |
|------|--------|-----------------------|---------|
| Tier 3 | Controllable | Minor (fatigue/headache) | The Honest Pendulum |
| Tier 2 | Caution needed | Noticeable (LoC + dependency) | The Storm Captain's Compass |
| Tier 1 | Dangerous | Severe (permanent damage) | The Sleepless One's Last Dream |
| Tier 0 | Catastrophic | Catastrophic | GM-exclusive |

---

# Chapter Four: Investigation and Clues

## 4.1 Clue Tiers

| Tier | Can Be Missed | How to Obtain |
|------|---------------|---------------|
| **Core Clue** | ❌ Cannot be missed | Auto-discovered (as long as you investigate the right place) |
| **Key Clue** | ⚠️ May be incomplete | Check success → complete; failure → partial info |
| **Auxiliary Clue** | ✅ Can be missed | Check success + specific condition |
| **Misleading Clue** | ❌ Cannot be missed | Auto-discovered (but can be seen through) |

## 4.2 Investigation Procedure

1. GM describes the scene (surface information only).
2. Player declares investigation method ("I use Observation to check the desk").
3. Core/Misleading clues auto-obtained; Key/Auxiliary clues require a check.
4. At most 3 independent investigation checks per person per scene.

## 4.3 Deduction Check

After collecting 3+ clues, attempt: **d100 ≤ Mind + Investigation − clues × 5**

- Critical Success: GM must reveal the true connection between all clues.
- Success: GM points to the correct direction + one still-missing piece of info.
- Failure: a misleading element mixed into the correct direction.
- Critical Failure: the player becomes convinced of a wrong conclusion.

## 4.4 Investigation Bonuses by Pathway

| Pathway | Bonus |
|---------|-------|
| Fool | Spirit Sight replays on-site spirit activity (3 Spirit / 2-round flashback) |
| White Tower | Speed-read handwritten records (100 pages in 10 seconds); on-site investigation +20 |
| Visionary | Microexpression analysis identifies a forged scene; mind reading identifies lies |
| Darkness | No penalty to night investigation; 100% vision in dark environments |
| Death | Deathbed words — ask the corpse "who killed you" (within 72h) |
| Red Priest | Footprint tracking reconstructs the full route of movement |
| Paragon | Encyclopedia memory retrieves history/science/law background |

---

# Chapter Five: Surface Life

## 5.1 Exposure Level

Your "normal person identity" is threatened by Beyonder actions. The GM secretly tracks Exposure Level:

| Level | Status | Effect |
|-------|--------|--------|
| 0 — Safe | No one suspects | Normal socializing unrestricted |
| 1 — Noticed | Neighbors feel you are "a bit odd" | +20% price buying Beyonder materials |
| 2 — Suspected | Local rumors | Social −10; some NPCs refuse contact |
| 3 — Watched | Officials observing covertly | Illegal actions 50% likely witnessed |
| 4 — Exposed | Identity burned | Nighthawks interview/manhunt; must change identity |

## 5.2 Attention-Drawing Behavior

| Behavior | Exposure |
|----------|----------|
| Using conspicuous Beyonder powers in public (thunder, fire leap) | +3 |
| Mortals see traces of Beyonder combat | +1 |
| Frequent visits to Beyonder locations (Drowned Man Tavern, etc.) | +1 / 3 visits |
| Reported in the newspaper as connected to Beyonder events | +5 |
| Nighthawks investigating you for other reasons | +3 |

## 5.3 Repairing Surface Life

- **Move:** −10 Exposure (£5–20 / once per quarter)
- **Change identity:** Exposure Level reset to 0 (£50–200 + social check)
- **"Return to normal life" for a month:** −3 (no Beyonder powers used)
- **Visionary Pathway memory modification:** −10 (LoC +1d3 per use)

---

# Chapter Six: Social Conflict

## 6.1 Social Opposition Framework

In key social scenes (negotiation, interrogation, debate), use structured social opposition:

**Social Initiative = Charisma + d10**

One social action per round:

| Action | Check | Success Effect | Failure Effect |
|--------|-------|----------------|----------------|
| Present Argument | Negotiation/Deception/Knowledge | Opponent Conviction −1d3 | Own Conviction −1 |
| Emotional Appeal | Charisma (Negotiation +10) | Opponent Conviction −1d4+1 | Opponent Conviction +1 |
| Find Opening | Observation/Mind Reading | +20 to next round's social check | — |
| Reveal Weakness | Mind (Investigation) | Learn opponent's Conviction | — |
| Intimidate | Body (Intimidation +10) | Opponent Conviction −2 / relationship worsens | Own Conviction −2 |

## 6.2 Conviction (Social HP)

**Conviction = 10 + Mind/5 + attitude modifier**

Opponent's attitude toward you: Trust +5 / Friendly +3 / Neutral +0 / Wary −3 / Hostile −5

Conviction dropping to 0 → opponent is persuaded / compromises.

Critical Success (≤5) → damage doubled + opponent reveals true thoughts.
Critical Failure (≥96) → opposition ends + you commit an unforgivable error against the opponent.

---

# Chapter Seven: Pathway Synergy

## 7.1 Synergy Types

**Power Stacking:** when two pathway powers act on the same target simultaneously, a synergy effect occurs.

| Combination | Effect |
|-------------|--------|
| Fool + White Tower | Perfect weakness analysis → attack auto Critical Success |
| Tyrant + Sun | Holy light + lightning → ×3 vs Dark |
| Visionary + Black Emperor | Mind reading + loophole → target Conviction −5 |
| Warrior + Chained | Guard oath removes the friendly-fire side effect of berserk |

## 7.2 Prepared Combo

Declare a free action (0 AP) to prepare a combo of two powers with an ally. When triggered, executes as a reaction (each spends 1 AP). The two powers stack with no decay.

---

# Chapter Eight: Interlude Activities

After each adventure, gain **1d3 Interlude Activity points**.

| Activity | Effect |
|----------|--------|
| Craft Potion / Item | Mind + skill check |
| Train Skill | d100 > skill value → +1d10 (once per interlude) |
| Maintain Surface Life | Reduce Exposure 1d5 |
| Contact NPC | Raise Faction Reputation (3 successes raise 1 level) |
| Gather Intelligence | Gain the next adventure's clue |
| Meditate & Purify | Reduce LoC 2d5 |
| Part-time Work | Gain monthly salary |

---

# Chapter Nine: Long-term Trauma

After brushing the Edge of Loss or witnessing the unspeakable, permanent trauma may remain. Trauma brings mechanical effects (e.g., fear of darkness → −10 in darkness) and roleplay impact. Each Sequence promotion can halve one trauma effect.

The full trauma table is in the *Rules Supplement Manual* or the GM Rulebook.

---

# Quick Start (5-Minute Version)

- **Roll dice:** d100, lower than the Target Number = success. ≤5 = Critical Success. ≥96 = Critical Failure.
- **5 attributes:** Spirituality (magic pool), Mind (sanity), Body (health), Agility (combat), Charisma (social)
- **Make a character:** pick a template → pick a pathway → roll 4 numbers → calculate HP and Spirit Pool (auto-calculated)
- **Combat:** 3 AP per round. Attack / power / move / dodge (reaction)
- **Most important:** act as your character. Make decisions true to the character — not the "optimal solution."

---

> **The above covers all the rules players need to know.** For GM-exclusive content (worldview, scenarios, encounter design, NPC stats, monster templates), please refer to the *GM Rulebook*. New rules (investigation, surface life, social, synergy, interlude activities, trauma) are detailed in the *Rules Supplement Manual*.
