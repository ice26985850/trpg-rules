# Death Return TRPG — GM Rulebook

> *"You are the guardian of time. Every timeline, every NPC's secret, every change in each loop—all rests in your hands."*

---

## How to Use This Book

This book contains all the content of the Player Rulebook, plus GM-exclusive chapters. The GM only needs to read this book to master all the rules.

### Chapter Guide

- **Chapters One through Five**: Same as the Player Rulebook (Core Rules, Character Creation, Death Return Mechanics, Combat Basics, World Intro)
- **Chapter Six**: Full check mechanics and DC-setting guide
- **Chapter Seven**: Full combat rules (including enemy AI, monster stat templates)
- **Chapter Eight**: NPC relationship rebuilding and suspicion system
- **Chapter Nine**: Timeline management system
- **Chapter Ten**: Worldview and setting details
- **Chapter Eleven**: Full frameworks for the five scenarios
- **Chapter Twelve**: Encounter design and difficulty balancing
- **Chapter Thirteen**: Solo-player GM techniques
- **Chapter Fourteen**: Optional rules and variants
- **Appendix**: Glossary, GM screen quick reference

---

# Chapter One: Core Rules

*(Same as Player Rulebook Chapter One—dice system, five attributes, skill system, check rules, difficulty tiers)*

### 1.1 Dice System

This game uses the **twenty-sided die (d20)** as its core die.

> **Check Value = d20 + Attribute Modifier (MOD) + Skill Level**
> **Success Condition: Check Value ≥ Difficulty Class (DC)**
> **Attribute Modifier (MOD)** = floor(Attribute Value ÷ 2); attribute range 4–9, character creation uses 18-point buy (see Player Rulebook 1.1/1.2)

**Advantage (ADV)**: 2d20 take higher | **Disadvantage (DIS)**: 2d20 take lower | Advantage and Disadvantage cancel out

**Special Results**: Natural 20 = Critical Success (Crit), Natural 1 = Critical Failure (Disaster), ≥DC+5 = Exceptional Success, ≤DC−5 = Severe Failure

### 1.2 The Five Attributes

| Attribute | Abbrev. | Meaning | Range |
|------|------|------|------|
| Insight (INS) | INS | Observing details, noticing anomalies | 4–9 (growth cap 12) |
| Memory (MEM) | MEM | Retaining info from previous loops | 4–9 (growth cap 12) |
| Execution (EXE) | EXE | Actual operational ability | 4–9 (growth cap 12) |
| Social (SOC) | SOC | Persuasion, charm | 4–9 (growth cap 12) |
| Will (WIL) | WIL | Bearing psychological burden | 4–9 (growth cap 15) |

Starting 18-point buy (base 4 free, single-attribute cap 9, increasing cost; Memory and Will share the same range, no minimum-3 limit).

### 1.3 Skill System

11 skills (including Alchemy), starting 8 points, creation cap 3.

**Intel Layer**: Reconnaissance (REC/INS), Conversation Mining (DIA/SOC), Anomaly Sense (ANO/INS), Cause-of-Death Analysis (DEA/WIL)
**Execution Layer**: Combat (COM/EXE), Stealth (STE/EXE), Mechanics (MEC/EXE), Persuasion (PER/SOC)
**General**: Memory Recall (RECALL/MEM), Mental Resistance (RES/WIL)
**Crafting**: Alchemy (ALC/EXE)—crafting potions, fire bombs, simple antidotes, scroll materials (see 14-9)

### 1.4 Check Rules

Standard check: d20 + Attribute Modifier (MOD) + Skill ≥ DC
Contested check: both sides roll d20 + Attribute + Skill, higher wins
NPC assistance: NPC Skill ≥ 2 → player Advantage; NPC Skill ≥ 4 → player Advantage +2

### 1.5 Difficulty Tiers

| Difficulty | DC | Success Rate (Attr5+Skill2=+7) |
|------|-----|---------------------|
| Trivial (TRI) | 8 | 95% |
| Easy (EAS) | 12 | 80% |
| Medium (MED) | 16 | 60% |
| Hard (HRD) | 20 | 40% |
| Extreme (EXT) | 24 | 20% |
| Nearly Impossible (NIM) | 28 | 5% |

GM may adjust DC by ±2 per situation.

**Dynamic Shift**: The base DC table does not change with character growth; increased challenge comes from enemies and environment. But to prevent S4–S5 core checks from becoming too easy due to character growth: S1–S3 no shift; **S4** core checks (those directly tied to main-story progression and survival) DC **+2**; **S5** core checks DC **+4**, or open DC **32 (Legendary) / 36 (Miraculous)** tiers for S5-exclusive top-tier threats (see Player Rulebook 1.5.1).

---

# Chapter Two: Character Creation

*(Same as Player Rulebook Chapter Two—six-step creation, eight backgrounds, derived attributes, character growth)*

### Derived Attribute Formulas (GM Reference)

| Derived Attribute | Formula | Notes |
|----------|------|------|
| Hit Points (HP) | Execution + Will + 5 | Total damage capacity; wound level derived from remaining proportion |
| Mind Points (MP) | Will + Memory + 3 | Social/mental check consumption and fear resistance |
| Stamina Points (SP) | Execution + Will + 3 | Stamina resource (attack/sprint/reaction); distinct from "Hit Points" |
| Memory Fragment Capacity | Memory × 2 + 5 + source bonus | Total fragment capacity carried per loop |
| Rift Threshold | fixed at 10 | Unbalanced starting point, purely narrative cue; stages judged by absolute Rift Mark value, not shifted by Will |
| Damage Tolerance (TOL) | Armor Value (AV) + floor((Execution (EXE) + Will (WIL)) ÷ 4), soft cap 9 | Damage reduction: final damage = raw damage − Damage Tolerance |

---

# Chapter Three: Death Return Core Mechanics

*(Same as Player Rulebook Chapter Three—Save Points, Memory Fragments, Rift Mark system, Intel Layer and Execution Layer)*

### Memory Fragment Overview (GM Quick Reference)

| Fragment | Cost | Effect |
|------|------|------|
| Event Fragment | 1 | Precisely recall event details |
| Character Fragment | 1 | Advantage on social checks vs a specific NPC |
| Location Fragment | 2 | Advantage on stealth/recon vs a specific location |
| Skill Fragment | 2 | Retain one "temporarily learned this loop" skill to next loop (1 per loop; creation and already-learned skills permanently retained) |
| Fate Fragment | 5 | Force survival (1 per loop) |

### Rift Mark Stages (GM Quick Reference)

| Rift Mark | State | Effect |
|------|------|------|
| 0–9 | Calm | None |
| 10–19 | Unbalanced | Social Disadvantage |
| 20–29 | Shattered | Insight Advantage + Will Disadvantage |
| 30–39 | Critical | After each death, Will DC 15, failure skips Save Point |
| 40+ | Uncontrolled | GM narrative intervention |

---

# Chapter Four: Combat Basics

*(Same as Player Rulebook Chapter Four—TU system, action types, attack & defense, wounds & damage, memory bonus)*

### Wound Quick Reference (from Hit Points)

| Wound Level | Remaining HP | Main Effect |
|---------|-----------|----------|
| 0 No Wound | 100% | Normal action |
| 1 Light Wound | 76–99% | Record wounded location |
| 2 Moderate Wound | 51–75% | Disadvantage on actions for that location + Bleeding (Sharp) |
| 3 Severe Wound | 26–50% | All Execution Disadvantage + halved movement + each round Will DC 12 (failure sustains and accumulates fatigue, next round DC +2) |
| 4 Fatal Wound | 1–25% | Cannot take major actions + each round Will DC 15 (failure enters Unconscious-savable; death only after two consecutive failures) |
| 5 Death | 0% | Triggers Return (player) / removal (enemy) |

---

# Chapter Five: World Intro

*(Same as Player Rulebook Chapter Five—Resonance Continent, Ashfall City, Three Great Factions)*

---

# Chapter Six: Full Check Mechanics and DC-Setting Guide

## 6-1 Check Difficulty Selection Guide

### When to Use Each DC Tier

| DC | When to Use | Example |
|-----|----------|------|
| 8 (Trivial) | Nearly always succeeds, only roll on Disadvantage | Finding an obvious book in a quiet library |
| 12 (Easy) | Requires basic ability, but proficient easily pass | Picking a normal door lock, persuading a friendly NPC for a small favor |
| 16 (Medium) | **Core difficulty**—needs ability or preparation | Sneaking into a guarded building, extracting info from an untrusting NPC |
| 20 (Hard) | Needs intel support or high attributes | Moving under tight surveillance, persuading an NPC to take a risk |
| 24 (Extreme) | Even experts need intel | Cracking a magical security system, changing an NPC's core belief |
| 28 (Nearly Impossible) | Needs perfect preparation | Crafting complex tools on the spot, completing within impossible time |

### Dynamic DC Adjustment Table

| Favorable Factors (−2 DC) | Unfavorable Factors (+2 DC) |
|-------------------|-------------------|
| Detailed map or precise intel | Insufficient or false intel |
| Proper tools at hand | Insufficient or broken tools |
| Ample time | Tight time |
| Friendly or assisting NPC | Hostile or interfering NPC |
| Good environment (well-lit, quiet) | Harsh environment (dark, noisy, raining) |
| Already performed same action successfully | First attempt at a completely unfamiliar action |

## 6-2 Hidden DC Principle

Keeping DC vague to players is a core technique of Death Return TRPG:

- **Never state the DC number directly**—describe difficulty in narrative language
- Say "this lock looks quite complex, you'll need considerable skill to open it" rather than "DC 18"
- Only reveal the result after the player rolls—maintain suspense
- **Exception**: When the player has attempted the same action in a previous loop, you may say "you remember this lock took roughly above-medium skill last time"

## 6-3 Intel-Check-Specific DCs

### Reconnaissance (REC)

| DC | What's Found |
|-----|----------|
| 8 | Obvious clues (footprints on ground, documents on a desk) |
| 14 | Hidden items (drawer secret compartment, note behind bookshelf) |
| 18 | Hidden door/trap (unnatural floor wear) |
| 22 | Subtle anomaly (medicine scent in the air, different pendulum rhythm) |

### Conversation Mining (DIA)

| DC | Info Gained |
|-----|----------|
| 8 | Public information |
| 14 | Steer topic to a specific domain |
| 18 | NPC inadvertently leaks what they meant to hide |
| 22 | NPC's core secret |

---

# Chapter Seven: Full Combat Rules

## 7-1 Enemy AI Behavior Logic

### Five-Tier Intelligence System

| Tier | Description | Typical Enemy | Combat Logic |
|------|------|----------|----------|
| **Instinctive** | Animals, zombies | Beasts, undead | Attack nearest target; fiercer when wounded but no strategy change |
| **Ordinary** | Ordinary humans | Thugs, civilian mobs | Use cover; consider fleeing below 50% HP; call allies |
| **Trained** | Soldiers, guards | Guards, mercenaries | Coordinated tactics (flanking +2); prioritize fragile targets; orderly retreat |
| **Cunning** | Elites, schemers | Assassins, mages | See through tactics; targeted counter; exploit weakness; set traps |
| **Genius** | Bosses, legendaries | Main antagonist | Predict 2–3 rounds; cross-loop memory; multi-phase tactic switching |

### AI Behavior Templates per Tier

#### Instinctive Tier

```
1. Move: toward nearest non-downed target
2. Attack: basic attack
3. Moderate Wound or worse: attack becomes Advantage (berserk)
4. Fatal Wound: keep attacking, no retreat
```

#### Ordinary Tier

```
1. Move: seek cover
2. Attack: basic attack or use special ability
3. HP < 50%: Will DC 10, failure flees
4. Ally down: Will DC 12, failure flees
```

#### Trained Tier

```
1. Assess: choose most threatening/most fragile target
2. Move: form flanking with ally (attack +2)
3. Attack: use most effective attack method
4. HP < 50%: orderly retreat (mutual cover)
5. Call reinforcements: spend 1 TU
```

#### Cunning Tier

```
1. Observe: spend 1 TU, Insight check to observe player tactics
2. Counter: react against player strategy
3. Exploit weakness: prioritize weakness attacks
4. Control field: use environment to limit player movement
5. HP < 1/3: activate backup plan
```

#### Genius Tier

```
1. Predict: view player HP and wounds—choose most restrained action
2. Memory: player repeats same tactic -> auto-counter
3. Multi-phase: switch tactic mode at 75%/50%/25% HP
4. Endgame: near-death triggers final ability or story event
```

### Genius-Tier Cross-Loop Memory (Optional Rule)

Genius-tier enemies can "notice anomalies" across different Return loops:
- Player shows same knowledge/tactic across loops → enemy Insight check
- Success → enemy suspects player has abnormal intel source
- Accumulated suspicion → behavior changes, breaking player's foreknowledge advantage
- Extreme cases → enemy realizes the loop's existence (story-level event)

## 7-2 Enemy Stat Templates

### Difficulty Grading

| Difficulty | Challenge Rating (CR) | Attribute Sum | Typical HP | Suited Player |
|------|---------------|----------|-----------|----------|
| **Minion** | CR 1–3 | 12–18 | 8–12 | Any |
| **Elite** | CR 4–7 | 18–25 | 13–17 | Memory 3+ |
| **Boss** | CR 8–12 | 25–32 | 18–22 | Memory 5+ |
| **Legendary** | CR 13–16 | 32–40 | 23–28 | Memory 7+ |

### Encounter Budget

```
Encounter Budget (EB) = Player Memory × 2 + Player Execution
Minion cost = EB×0.2 | Elite cost = EB×0.5 | Boss cost = EB×1.0 | Legendary cost = EB×1.8
```

### NPC Quick Combat Stats

> Note: In the table below, "HP" is the enemy's total health (equivalent to player Hit Points (HP)); the "Skill" column corresponds to Chapter Eight's NPC assistance rule (Skill ≥ 2 gives player Advantage, ≥4 gives Advantage +2).

| NPC Type | HP | TOL | Attack | Skill | Damage | Armor | Init | Special |
|---------|--------|------|------|------|------|------|------|------|
| Innocent Bystander | 6 | 0 | +1 | 0 | 1d2 | 0 | +1 | Panic flee |
| Guard | 10 | 3 | +4 | 2 | 1d6 | 2 | +3 | Call reinforcements |
| Veteran Soldier | 13 | 6 | +6 | 3 | 1d8+1 | 4 | +4 | Flanking tactic |
| Assassin | 9 | 2 | +7 | 4 | 1d8+3 | 1 | +6 | Sneak-attack Advantage |
| Scholar/Mage | 7 | 0 | +2 | 2 | 1d4 | 0 | +4 | Special knowledge |
| Medium Monster | 14 | 5 | +5 | 3 | 1d10 | 3 | +2 | Bestial frenzy |
| Large Monster | 20 | 8 | +7 | 4 | 2d6 | 5 | +1 | Area attack |

### Monster Special Ability Pool

> Note: Monsters do not have a separate "Stamina" resource; ability costs are shown in Time Units (TU) or "passive".
> Specific monster stats and codex are in the *Monster Codex*; weapons, armor, and items are in the *Item Codex*.

| Ability | Cost | Effect |
|------|------|------|
| Bestial Frenzy | Passive | Below 50% HP: Attack Advantage, Defense Disadvantage |
| Pack Tactics | Passive | +2 when attacking same target with ally |
| Terrifying Howl | 3 TU | Enemy Will DC 13, failure loses reaction right |
| Regeneration | Passive | Recover 2 HP per round (suppressed by fire) |
| Invisibility | 3 TU | Become invisible, reappear after attack |
| Flight | Passive | Unaffected by ground difficult terrain |
| Venom Secretion | Passive | Melee hit adds Poison |
| Petrifying Gaze | 2 TU | Target Execution DC 14, failure doubles move cost |
| Devour | Major | Inflict Fatal Wound on downed target |

---

## 7-3 Status Effect Summary

Common abnormal states in combat and exploration, shared by players and enemies:

| Status | Abbrev. | Effect | Removal |
|------|------|------|----------|
| **Stun** | STN | Cannot act | Pass Will DC 10 at end of each round |
| **Bleeding** | BLDe | −1 HP per round (−2 at Severe Wound or worse) | First Aid (Execution+First Aid DC 13) stops it |
| **Poisoned** | PSN | Wound level upgrades one step every 10 min | Antidote, or Will DC 12 / hour |
| **Burning** | BRN | −1 final damage per round (not reduced by TOL, −2 at Severe Wound or worse) | Extinguish (water/roll/fire suppression) |
| **Fear** | FER | Can only move and take minor actions | Threat gone, or pass Will DC 12 |
| **Bound** | BND | Cannot move | Break free (Execution DC 12) or external removal |
| **Blinded** | BLD | Disadvantage on attack checks | Pass Will DC 12 at end of each round to restore sight (or eye wash/treatment) |

### Medical and Rest (GM Settlement Reference)

| Method | Condition | Effect |
|------|------|------|
| **Short Rest** | 1 hour safe time | Restore all Stamina; restore 50% Mind Points; no HP restored |
| **Long Rest** | 8 hours safe sleep | Restore all Stamina and Mind Points; HP restored to max (requires no untreated Bleeding/Poison) |
| **First Aid** | Consume medical kit; Execution+First Aid DC 13 | Stabilize Bleeding, restore 1d4+Will HP, stop wound worsening |
| **Medical Treatment** | Consume medical kit; Execution+First Aid DC 15 | Severe Wound needs hours, Fatal Wound needs days; only after treatment can Long Rest restore |
| **Healing Potion** | Consume 1 bottle | Restore = max(1d6+3, floor(Max HP × 25%)), after healing not exceeding 75% of max HP |
| **Antidote** | Consume 1 bottle | Immediately remove Poisoned |

---

# Chapter Eight: NPC Relationship Rebuilding and Suspicion System

## 8-1 Relationship Value (RV)

| RV | Tier | NPC Behavior |
|----|------|---------|
| 0 | Stranger | Basic courtesy, keeps distance |
| 1–3 | Acquainted | Willing basic conversation, may give public info |
| 4–6 | Friendly | Willing small favors, gives non-confidential info |
| 7–9 | Close | Willing risky help, shares secrets |
| 10 | Bond | Beyond the loop—new loop RV starts at 3. NPC may show "déjà vu" |

### Relationship Rebuild Acceleration

Each loop, players can use prior-loop knowledge to accelerate relationship rebuilding:

- Use Memory Fragment: spend 1 Character Fragment, state info known only from prior loop → NPC feels déjà vu, RV +2 directly
- "Perfect first impression": use known preferences, RV starting base can begin higher (+1 to +3)
- Avoid triggers: avoid known offensive topics (passive Advantage, no roll needed)

### Relationship Reset Rules

- Player dies and Returns → all NPCs' RV reset to 0 (Bond NPCs reset to 3)
- Player remembers everything—NPC remembers nothing
- GM should actively describe the emotional weight of each "re-acquaintance"

## 8-2 Suspicion Value (SV)

| SV | State | NPC Reaction |
|----|------|---------|
| 0 | Normal | No anomaly |
| 1–3 | Confused | "Haven't I seen you somewhere?"—looks a bit more, interaction basically normal |
| 4–6 | Wary | "How do you know that?"—keeps distance, brief answers |
| 7–8 | Hostile | Direct interrogation, refuses interaction, may call guards |
| 9+ | Extreme Reaction | Flees, preemptive attack, reports to faction |

### SV Triggers

| Behavior | SV Increase |
|------|--------|
| Tell NPC personal info they haven't told you yet | +2~3 |
| Appear during NPC's "private moment" | +3 |
| Precisely predict future event that then happens | +2~4 |
| Behavior pattern doesn't fit current situation | +1~2 |
| Show abnormal knowledge of NPC ability/weakness | +1~2 |

### SV Reduction Methods

| Behavior | SV Decrease |
|------|--------|
| Offer reasonable (or seemingly reasonable) explanation | −2 (needs Social check) |
| Show sincere goodwill | −1~2 |
| Successfully divert topic or soothe | −1~3 |
| Leave NPC's sight for over half a day | −1/half-day |
| Vouched for by someone NPC trusts | −3~5 |

### GM Tracking Principles
- SV invisible to players—convey indirectly through NPC behavior
- Track SV independently per NPC
- SV ≥ 7 and NPC belongs to a faction → that faction may raise overall alertness

---

# Chapter Nine: Timeline Management System

## 9-1 Timeline Record Sheet

GM must prepare a timeline record sheet for each scenario. Format:

```
Scenario: S1 - Who Killed the Mayor
Current Loop: Loop [N]

Day 1
├─ Dawn: [Fixed] Mayor gives speech at Bell Tower Square
├─ Morning: [Variable]
├─ Afternoon: [Variable]
├─ Dusk: [Semi-Fixed] Mayor meets Merchant Guild
└─ Night: [Variable]

Day 2
├─ Dawn: [Fixed] Mayor absent from breakfast (received threat letter)
├─ Day: [Variable]
├─ Dusk: [Fixed] Mayor private meeting with someone (identity variable)
└─ Night: [Semi-Fixed] Mayor works in study until late

Day 3
├─ Day: [Variable] final investigation window
├─ Afternoon: [Fixed] Mayor's last public sighting
└─ Dusk–Midnight: [Fixed] murder occurs (unless prevented)
```

## 9-2 Three-Tier Event Fixity Classification

### Fixed Events
- Happen no matter what the players do
- Change condition: usually the scenario's core clear condition
- **GM operation**: prepare "player present" and "player absent" versions; tweak details each loop to keep freshness

### Semi-Fixed Events
- Happen but time/method can be influenced by players
- **GM operation**: record actual occurrence time each loop; allow reasonable delay or advance; track chain reactions

### Variable Events
- Entirely depends on player action
- **GM operation**: ensure at least three reasonable outcomes per variable event; record outcome for future loops

## 9-3 GM Checklist After Each Loop

1. □ Record 3–5 new intel items players gained this loop
2. □ Record NPC Relationship Value (RV) changes
3. □ Record which events players changed (Fixed→Semi-Fixed, Semi-Fixed→Variable)
4. □ Record current player Memory Fragment count and state
5. □ Confirm available "shortcut options" for next loop
6. □ Record any traces players left (letters, items, words said to NPCs)

---

# Chapter Ten: Worldview and Setting Details

## 10-1 Full Historical Timeline

### First Era—Serpentine Era (3000 to 1500 years ago)

| Year | Event |
|------|------|
| Before Era | Ouroboros (the Time Serpent) created time. Time-Watchers built the first Tower of Time |
| Serpentine 487 | Kadros born |
| Serpentine 512 | **"Crime of Time-Sundering"**—Kadros pierces Ouroboros, the first seven Returners born |
| Serpentine 513 | "Seven Days of Mourning"—time anomalies begin |
| Serpentine 800 | Time-Watcher civilization vanishes |

### Second Era—Radiant Gold Era (1500 to 300 years ago)

| Year | Event |
|------|------|
| Radiant Gold 1 | Radiant Gold Empire founded |
| Radiant Gold 87 | Empire excavates Time-Watcher ruins, founds Royal Time Research Institute |
| Radiant Gold 200 | "Returner Hunt Decree"—Witch-Hunter Knight Order founded |
| Radiant Gold 450 | "Rebellion of the Reverse Scale"—Emperor Olesius VII awakens as Returner, mental collapse |
| Radiant Gold 451 | Empire collapses |

### Third Era—Age of Embers (300 years ago to present)

| Year | Event |
|------|------|
| Age of Embers 1 | Ashfall City becomes independent city-state |
| Age of Embers 45 | Death Church founded |
| Age of Embers 120 | Tower of Time reopened |
| Age of Embers 200 | "Surge Tide Phenomenon"—frequency of Returner appearances rises sharply |
| Age of Embers 280 | Shadow Guild founded |
| Age of Embers 300 (now) | Time anomalies increasingly frequent, new Returners (players) awaken |

## 10-2 Geographic Map

### Ashfall City Five Districts Detail

| District | Feature | Key Locations | Atmosphere |
|------|------|----------|------|
| **Bell Tower District** | Upper class, council seat | Council Hall, Mayor's Mansion, Bell Tower Square (13 bells at noon daily) | Elegant surface, hotbed of political intrigue |
| **Hearth District** | Commercial center | "The Cup of Cycles" tavern (Returner mutual-aid gathering spot), guild hall, market square | Noisy, pragmatic, well-informed |
| **Ash Alley** | Slums, guild HQ | "Spider's Nest" (guild HQ), black market stalls | Dangerous but full of opportunity |
| **Holy Relic District** | Church territory | Holy Relic Cathedral (above the Eternal Well), Inquisition, Contemplation Garden | Solemn, mysterious |
| **Old City Ruins** | Imperial palace ruins | Shattered Throne Hall, Royal Archive, Gate of the Abyss | Desolate, buried truths |

### Surrounding Regions

| Region | Location | Feature |
|------|------|------|
| **Wailing Forest** | Half-day east of city | Unstable time, twisted trees, soil soaked in Serpent's Blood |
| **Iron Ridge Mountains** | North of city | Time-Watcher astronomical observatory ruins, thin-time zone |
| **Sunken Plains** | West of city | Submerged imperial villages, time frozen underwater |
| **Mirror Lake** | Deep in Wailing Forest | Lake surface reflects random past moments, shows future at specific times |

## 10-3 Faction Details

### Death Church

- **Symbol**: Biting-tail serpent ring, a drop of blood at center
- **Core Doctrine**: Death is the beginning of Return; Returners are vessels chosen by the Serpent; the "Final Cycle" will mend the time rift
- **True Goal**: Control all known Returners, cultivate the "Final Returner"
- **Key NPCs**: Archbishop Esselyn (former Returner, stopped after 30+ loops), Inquisitor Marcus (zealous hunter), Nun Liz (sincerely kind low-rank nun)

### Tower of Time

- **Symbol**: Spiral tower, octagonal star at top
- **Core Mission**: Understand time, repair rifts (academically neutral)
- **True Goal**: The Core Ring knows "Return is a time disease." Repair faction wants to eliminate Return phenomenon, divert faction wants to channel the energy
- **Key NPCs**: Chief Scholar Victor (Repair faction, emotionally detached), Time Weaver Eileen (Divert faction, can briefly see future), Apprentice Kay (possibly awakening as Returner)

### Shadow Guild

- **Symbol**: A hand reaching from shadows, holding a closed eyeball
- **True Business**: Intel selling, Returner hiring (infinite-retry tasks), time-contraband trade
- **Guild Master "the Spider"**: A Returner, lived a hundred loops, learned not to form emotional bonds to stay sane
- **Key NPCs**: Information Broker Rena (player's main contact), Scavenger Gregor (former imperial officer)

### Returner Mutual Aid Society (Hidden)

- Underground mutual-aid organization, ~20 Returners
- Meeting spot: basement of "The Cup of Cycles" tavern
- Core rule: "Never hide a Save Point location from a companion"
- **Key NPCs**: "Old Granny" Martha (spiritual leader after 200+ loops), the Silent One Aldin (communicates in writing, holds 50+ loops of observation notes)

---

# Chapter Eleven: Five Scenario Frameworks

## S1—Who Killed the Mayor (Novice, recommended 1–3 loops)

**Time Span**: three days | **Save Point**: Eternal Well | **Core Skills**: Insight, Social

**Case**: Mayor Aldric is poisoned on the night of the third day. The killer is someone he knew and trusted.

**Three-Layer Truth**:
- Surface (Loop 1): The mayor recently pushed some investigation
- Middle (Loop 3): The investigation touched something forbidden; multiple parties have motive to kill
- Deep (Loop 5+): The mayor discovered the Church's truth of "guiding" Returners; the killer is the coerced personal doctor Edwin

**Three Routes**:
- A (Social): Political investigation—visit political enemies and allies, attend noble banquets
- B (Execution + Insight): Underground investigation—through Shadow Guild, sneak into crime scene
- C (Insight + Will): Church route—use Church goodwill for support

**Clear Condition**: Identify the killer and stop the murder, or expose the truth after the murder.

**Key NPCs**: Mayor Aldric, Mayor's Wife Alicia, Secretary Leonard (Red Herring), Guard Captain Callen, opposition Lord Morton, Doctor Edwin (true culprit)

---

## S2—The Collapsing Tower (Intermediate, recommended 3–6 loops)

**Time Span**: seven days | **Save Points**: Eternal Well + in-tower relay | **Core Skills**: Insight, Execution, Memory

**Case**: The central research tower of the Tower of Time has a "time explosion" at noon on the seventh day. Actually internal sabotage.

**Tower's Seven-Level Structure**:
- Ground level: hall and reception (public)
- Second level: book storage (library and archive)
- Third level: element research (time-element interaction experiments)
- Fourth level: Returner research (not open to public—"samples" and experiment records)
- Fifth level: Core Ring conference (private studies of five scholars)
- Sixth level: time weaving (Eileen's prophecy observatory)
- Seventh level: tower-top core resonance chamber—explosion source

**Deep Truth**: The saboteur comes from inside the Core Ring—a scholar planted as mole by the Church.

**Clear Condition**: Stop the seventh-day explosion, expose the mastermind.

---

## S3—The Traitor's Smile (Intermediate, recommended 5–9 loops)

**Time Span**: five days | **Core Mechanic**: Variable Traitor System | **Core Skills**: Social, Memory, Insight

**Core Mechanic**: The traitor is not a fixed person but a fixed "role." Different NPCs may become the traitor each loop, depending on player actions and external faction intervention. But the traitor always leaves the same "signature"—a smile mark.

**Companion NPC Pool** (4–6 per loop): Nun Liz, Apprentice Kay, Information Broker Rena, Scavenger Gregor, the Silent One Aldin, Guard Captain Callen

**Three Routes**:
- A (Social + Insight): Trust and observe—build deep relationships, watch for anomalies
- B (Memory + Insight): Cross-verify info—give different people different info, track leak source
- C (Memory + Execution): Pre-set traps—use multi-loop memory to set traps

**Core Experience**: Understanding matters more than punishment. Every traitor has a reason for being coerced or deceived.

---

## S4—The Forgotten Save Point (Advanced, recommended 7–12 loops)

**Time Span**: ten days | **Core Mechanic**: Memory Fragment Overload | **Core Skills**: Memory, Will, Insight

**Core Concept**: The player discovers a Save Point they created but completely don't remember. Accessing it triggers Memory Fragment overload—massive repressed memories flood in at once.

**Hidden Truth**: A past player discovered a shocking truth—some NPC in the game (e.g., the Archbishop or Chief Scholar) is actually a companion from a past loop, and the player personally pushed them toward their current fate. The past player couldn't bear this truth, so sealed the memory.

**Memory Fragment Overload Mechanic**:
- Accessing Save Point grants 3–5 "past loop" Memory Fragments
- Need to pass Will check: success = clear memory, failure = authenticity unclear
- Accessing three or more times consecutively: permanently lose part of memory

**Multiple Endings**: Reconcile (Will +1), Shoulder (bear alone), Forget Again (short-term calm but fierce future return), Collapse (fragmented state)

---

## S5—The Last Day (Epic, recommended 10–15 loops)

**Time Span**: fourteen days | **Only Save Point**: Eternal Well | **Core Skills**: all five

**Core Concept**: On the fourteenth day, time begins to collapse—different city districts move at different speeds, rifts showing past and future appear in the sky, Returner abilities go out of control. Must stop it before time fully freezes.

**Three Stopping Routes**:

| Route | Goal | Cost | Result |
|------|------|------|------|
| **Repair Serpent Scales** | Go to Wailing Forest to repair Ouroboros's wound | A Returner devotes all loops | Return phenomenon vanishes, all become ordinary people |
| **Break the Cycle** | Activate the empire-era "Time Rending Device" | All Returners' memories erased | No one remembers anything from any loop |
| **Coexist with the Serpent** | Returners collectively sync Save Points to form a Time Anchor | Can never truly "leave" | Returners form a community across loops |

**Fourteen-Day Timeline**:
- Days 1–3: identify anomalies
- Days 4–6: factions mobilize, choose cooperation partners
- Days 7–9: deep investigation, determine final route
- Days 10–12: key turning point, possible NPC sacrifice
- Day 13: final preparation, farewell to important NPCs
- Day 14: **Finale**—execute final plan, multiple endings

---

# Chapter Twelve: Encounter Design and Difficulty Balancing

## 12-1 Combat Encounter Design Template

```
Encounter Name: [name]
Encounter Type: Combat
Location: [scene description—including interactive environment elements]
Enemy Setup:
  - Primary threat ×1: [type] [core ability] [weakness]
  - Secondary threat ×2-3: [type] [core ability]
Environment Elements: [at least 3 elements players can exploit]
Intel Reward: [what players can learn from the fight]
```

## 12-2 Social Encounter Design Template

```
Encounter Name: [name]
Encounter Type: Social
Target: [NPC name, identity, personality summary]
NPC Goal: [what they want]
NPC Weakness: [what can sway them]
Dialogue Branches: Friendly/Threaten/Outwit
Failure Consequence: [non-lethal—e.g., lose info source, RV drop]
Intel Reward: [what success gains]
```

## 12-3 Exploration Encounter Design Template

```
Encounter Name: [name]
Encounter Type: Exploration
Location: [five-senses description]
Discoverable Elements:
  - Obvious: [low Insight DC]
  - Hidden: [medium Insight DC]
  - Secret: [high Insight DC or needs specific clue]
Time Cost: [time for quick/careful/thorough search]
Intel Reward: [intel corresponding to each layer]
```

## 12-4 Intel Grading

| Tier | Description | Suggested Count per Loop |
|------|------|-------------|
| **Fragment-level** | Small details, multiple can form a pattern | 5–7 |
| **Clue-level** | Clearly points, leads to next scene | 2–3 |
| **Breakthrough-level** | Directly changes understanding of the case | 1 |
| **Truth-level** | Reveals core truth | 0–1 (at scenario climax) |

## 12-5 Difficulty Curve

| Difficulty | Scenario | Loops | Combat Frequency | Time Pressure |
|------|------|--------|----------|----------|
| Novice | S1 | 1–3 | Low (can be fully avoided) | Low (three days) |
| Intermediate | S2,S3 | 3–9 | Medium | Medium (5–7 days) |
| Advanced | S4 | 7–12 | Medium-High | Medium (ten days) |
| Epic | S5 | 10–15 | High (multi-phase) | Extreme (fourteen days) |

## 12-6 Difficulty Calibration

| Player Prep State | EB Usage | Expected Result |
|-------------|----------|----------|
| First encounter, no intel | 30–50% | High death chance, gain intel |
| Some intel (1–2 fragments) | 50–70% | Even match |
| Full intel + ambush prep | 70–100% | Clear player advantage |
| Multi-loop intel + full prep | 100–130% | Can challenge stronger enemies |

## 12-7 Random Encounter Tables

When players move in non-scripted scenes, or GM wants to add tension, roll d20 for an encounter (pick table by terrain). Encounter difficulty should match the scenario's suggested loop count. If player Memory (MEM) < 5 and draws a Boss/Legendary encounter (e.g., ruins table d20 20), auto-drop one tier (Legendary→Elite, Boss→Elite) to prevent party wipe; if encounter completely unfit for current plot, may reroll d20 once.

**City (Ashfall City streets/market)**

| d20 | Encounter |
|-----|------|
| 1–6 | Nothing—daily bustle, can gather gossip |
| 7–9 | Patrol guard checkpoint (Social DC 14, failure SV+1) |
| 10–12 | Pickpocket attempt (Stealth contest, failure loses money) |
| 13–15 | Church preacher (can gain free Save Point blessing, SV secretly rises) |
| 16–17 | Gang skirmish (can watch or intervene, intel reward) |
| 18–19 | Returner Mutual Aid member secretly contacts |
| 20 | Assassin ambush (combat, GM decides source) |

**Wilderness (Wailing Forest/Sunken Plains)**

| d20 | Encounter |
|-----|------|
| 1–7 | Nothing—natural environment, can explore |
| 8–10 | Twisted Beast (combat, Minion tier) |
| 11–13 | Time anomaly signs (see 14-6) |
| 14–16 | Lost traveler (can give info or commission) |
| 17–18 | Mad Returner (social risk, may gift key info) |
| 19–20 | Elite threat (combat, Elite tier) |

**Ruins/Underground (Old City Ruins/Tower interior)**

| d20 | Encounter |
|-----|------|
| 1–6 | Nothing—can search |
| 7–10 | Trap (Insight DC 14 to find, failure Light Wound) |
| 11–14 | Guard/Mechanism Puppet (combat, Minion~Elite) |
| 15–17 | Ancient knowledge fragment (intel reward) |
| 18–19 | Time anomaly zone (see 14-6) |
| 20 | Legendary guard (combat, Boss~Legendary; if MEM<5 drop to Elite) |

---

# Chapter Thirteen: Solo-Player GM Techniques

## 13-1 NPC Companions Fill Skill Gaps

Prepare recruitable NPC companions:
- **Combat type**: Scavenger Gregor, fills Execution gap
- **Social type**: Nun Liz, fills Social gap
- **Knowledge type**: Apprentice Kay, fills Insight gap

Each companion needs specific conditions and Relationship Value threshold to recruit.

## 13-2 "Solo Solution" Principle

Each obstacle has at least three paths:

> Combat path (Execution)｜Stealth/infiltration path (Insight + Execution)｜Social/outwit path (Social + Memory)

At least one feasible under the player's attribute build.

## 13-3 Intel Density Control

- **At least 3 new intel per loop**: even when repeating same action
- **Intel marking**: track player-known intel, judge which scenes can be skipped
- **"You notice now…" technique**: actively add new details when describing repeated scenes

## 13-4 Death as Narrative Tool

- Death provides new clues (killer/method/location are all intel)
- Death reveals patterns (killed by same trap third time → tell player it's a fixed trap)
- Death creates urgency (you have only X days left, but you know more than last time)

## 13-5 Shortcut System

When players experience enough repeated scenes (usually 3+ times):
- Allow skipping already-proven-feasible actions
- Provide "butterfly effect summary" for skipped spans
- Example: "In the two hours you skipped, the flower girl didn't show up today; the guard captain was replaced by a newcomer; it started raining, two hours earlier than you remembered."

## 13-6 Three-Act Loop Rhythm

| Act | Share | Content |
|----|------|------|
| **Restart** | 20% | Wake from Save Point, reorient, make plan |
| **Explore & Advance** | 60% | Execute plan, track butterfly effects, new intel surfaces |
| **Climax** | 20% | Event pressure peaks, choose to face result |

## 13-7 Macro Rhythm

| Loop | Phase | GM Focus |
|------|------|--------|
| 1–3 | Exploration | Build atmosphere, show possibilities, each death reveals key intel |
| 4–7 | Deepening | Introduce twists, hidden layers, NPC relationship complexity |
| 8–12 | Climax | Multiple clues converge, reveal deep truth |
| 13–15 | Endgame | All accumulated intel and relationships bloom at once |

---

# Chapter Fourteen: Optional Rules and Variants

## 14-1 Hardcore Mode

- Starting attribute points raised to 24
- Rift Mark increase ×1.5 (round up)
- Memory Fragment Capacity −2
- For players seeking extreme challenge

## 14-2 Hero Mode

- Starting attribute points raised to 36
- Fate Fragment cost lowered to 3
- Rift Mark relief effect ×1.5
- For players wanting story over challenge

## 14-3 Multi-Player Variant

Though designed for solo, supports 2–3 players:

- Each player independently manages their own Rift Mark and Memory Fragments
- Players may share Memory Fragments (cost 1 minor action)
- Encounter Budget (EB) = sum of all players' Memory + highest Execution value
- **Enemy Scaling**: each extra combat unit (player or combat companion), enemy HP ×1.5 or count +1 (take higher threat); avoid 2–3 players directly steamrolling original enemy count
- When S3 recruits combat companion, enemy strength raises one tier simultaneously
- Team check: all players roll, majority success = team success
- Each scenario ending has "Multi-Player GM Tips" giving specific scaling and division suggestions for that scenario (see scenarios/)

## 14-4 GM No-Roll Variant

All NPC actions use fixed values instead of rolls:
- NPC Attack Value = 10 + NPC Attribute + NPC Skill
- NPC Defense Value = 10 + NPC Attribute + NPC Skill
- Player still rolls normally against fixed values
- Advantage: faster pace, GM focuses on narrative

## 14-5 Quick Loop Mode

For single sessions:
- Skip all auto-success for explored scenes
- Death uses simplified Rift Mark (fixed +2 each)
- GM directly summarizes butterfly effect

## 14-6 Time Anomaly Zones

Around Ashfall City (Iron Ridge Mountains, deep Wailing Forest, bottom of Old City Ruins) exist **Time Anomaly Zones**—time flows abnormally within. This mechanic mainly serves S5 *The Last Day*, but can also be an environmental threat in advanced scenarios.

| Anomaly Type | Effect | Rule |
|----------|------|------|
| **Thin-Time Zone** | Time accelerates, rapid aging | Every 1 hour stayed, Will (WIL) DC 12 check; failure one **non-Will** attribute temporarily −1 (excluding Will, preventing Will↓→easier fail→−1 spiral; recovers after leaving zone) |
| **Time-Stasis Zone** | Time frozen, actions sluggish | Every hour Will (WIL) DC 14 check; failure −1 usable Time Unit that round |
| **Jump Zone** | Random forward/back jumps | On entry and every hour roll d6: 1–2 back 10 min, 3–4 unchanged, 5–6 forward 10 min |

**General Rules:**
- Inside Time Anomaly Zones **no Save Point can be established** (time unstable, anchor fails).
- Players can mitigate via "known routes" and "time markers"—if passed in a prior loop, related checks this loop gain Advantage.
- S5's fourteenth-day city collapse is essentially city-wide stacked Time Anomaly Zones; to reduce fatigue, GM rolls once every 2–3 in-game hours to decide anomaly intensity, avoiding continuous high-frequency checks.

## 14-7 Faction Reputation

The Three Great Factions (Death Church, Tower of Time, Shadow Guild) each hold a **Reputation Value (REP)** toward the player, range −10 to +10, starting at 0.

| Reputation | Tier | Effect |
|--------|------|------|
| −10~−6 | Hostile | Faction members actively hostile; entry to their territory restricted |
| −5~−1 | Suspicious | Trade price +50%; key intel withheld |
| 0–4 | Neutral | Normal interaction |
| 5–8 | Friendly | Trade price −20%; can get non-confidential aid |
| 8–10 | Devoted | Gain faction-exclusive resource or shelter |

**Up/Down Methods:** Assist faction goal +1~3; betray or harm its core member −2~5; complete faction commission +2. **Limits:** per loop per faction net change cap **+3/−5**, same-type action counts at most once per loop (prevent farming to Devoted in one loop); Devoted tier expanded from 9–10 to **8–10**. GM should track the three reputation lines independently.

## 14-8 Follower Loyalty

Solo players may recruit NPC companions (see 13-1). Each companion, besides Relationship Value (RV), has **Loyalty (LOY)** 0–10, deciding reliability in combat and possibility of betrayal (echoes S3).

| Loyalty | Behavior |
|--------|------|
| 0–3 | Reluctantly obeys, may retreat or betray in crisis |
| 4–6 | Normal cooperation, acts on orders |
| 7–9 | Proactively covers, risks assistance |
| 10 | Follows to death; new loop RV starts at 3 (Bond tier) |

**Recruit Initial:** On successful recruit Loyalty = **4** (if Relationship Value RV ≥ 7 then **6**).

**Up/Down:** Achieve goal together +1; saved by player +2; abandoned or deceived −2~3. Loyalty not reset by death (unlike RV), but no interaction per loop = **−1 (floor 0)**.

## 14-9 Alchemy and Crafting

Players may craft items (potions, traps, simple tools). This is an optional system enriching the resource loop.

| Item | Check | Material Source | Failure Consequence |
|------|------|----------|------|
| Basic potion (bandage, simple antidote) | Execution+Alchemy DC 12 | Shop/wild gather | Material loss, no product |
| Advanced potion (healing potion, fire bomb) | Execution+Alchemy DC 16 | Shop/monster drop | Material loss, 50% produce inferior |
| Trap/tool | Execution+Mechanics DC 14 | Junk/disassemble | Equipment damaged |

- Materials obtained from *Item Codex* and scenario exploration (healing potion materials 40–60G, fire bomb materials 10G, simple antidote materials 5G); monster drops depend on type.
- Crafting needs corresponding tools (e.g., Alchemy Kit 25G), else DC +4.
- **Anti-infinite-farm**: single character may craft at most **3** products per loop; materials must be actually obtained (paid or gathered), no conjuring high-value potions from nothing.

## 14-10 On Magic and Player Abilities

Resonance Continent has elemental, life, shadow, and time magic. But **ordinary Returners (player characters) cannot cast magic**—you are ordinary people with Death Return.

- **From NPC**: magic of nuns, scholars, guild mages forms threat/support in combat and social.
- **From items**: magic scrolls, alchemy potions and other consumables let players indirectly gain one-time magic effects (see *Item Codex*).
- **From environment**: residual magic of time anomaly zones and ancient ruins affects rules (see 14-6).

> If some background or special ability allows casting, GM will clearly mark limits and costs at character creation. Consistent with Player Rulebook 5.3.

---

# Appendix

## Appendix A: GM Screen Quick Reference

### Check Difficulty
| DC | Name | Success Rate (+7) |
|----|------|-----------|
| 8 | Trivial | 95% |
| 12 | Easy | 80% |
| 16 | Medium | 60% |
| 20 | Hard | 40% |
| 24 | Extreme | 20% |

### Rift Mark Stages
| Rift Mark | State | Effect |
|------|------|------|
| 0–9 | Calm | None |
| 10–19 | Unbalanced | Social Disadvantage |
| 20–29 | Shattered | Insight Advantage + Will Disadvantage |
| 30–39 | Critical | After death Will DC 15 |
| 40+ | Uncontrolled | GM intervention |

### Manner of Death
| Manner | Rift Mark |
|------|------|
| Quick | +1 |
| Voluntary | +2 |
| Painful | +3 |
| Betrayal | +5 |
| Despair | +7 |

### Enemy AI
| Tier | Key Behavior |
|------|----------|
| Instinctive | Attack nearest target |
| Ordinary | Use cover, flee at low HP |
| Trained | Flanking +2, orderly retreat |
| Cunning | See through tactics, targeted counter |
| Genius | Cross-loop memory, multi-phase |

### Derived Attributes
| Attribute | Formula | Notes |
|------|------|------|
| Hit Points (HP) | EXE+WIL+5 | Total damage capacity; wound level from remaining proportion |
| Mind Points (MP) | WIL+MEM+3 | Social/mental check consumption, fear resistance |
| Stamina (SP) | EXE+WIL+3 | Stamina resource (attack/sprint/reaction); not HP |
| Damage Tolerance (TOL) | Armor + floor((EXE+WIL)÷4), soft cap 9 | Damage reduction: final damage = raw − TOL |
| Fragment Cap | MEM×2+5 | Per-loop fragment capacity |
| Rift Threshold | fixed 10 | Unbalanced start, pure narrative cue |

---

## Appendix B: Glossary

| Term | Abbrev. | Notes |
|----------|------|------|
| Insight | INS | Observation, perception |
| Memory | MEM | Retained across loops |
| Execution | EXE | Physical action |
| Social | SOC | Communication, relationships |
| Will | WIL | Mental resilience |
| Difficulty Class | DC | Check target value |
| Advantage | ADV | 2d20 take higher |
| Disadvantage | DIS | 2d20 take lower |
| Memory Fragment | MF | Cross-loop info |
| Rift Mark | RM | Psychological trauma |
| Save Point | — | Return destination |
| Time Unit | TU | Combat action measure |
| Hit Points | HP | Total damage capacity (Execution+Will+5) |
| Mind Points | MP | Social/mental check consumption and fear resistance (Will+Memory+3) |
| Stamina Points | SP | Stamina resource (Execution+Will+3), zero = Exhaustion |
| Damage Tolerance | TOL | Damage reduction (TOL = AV + floor((EXE+WIL)÷4), soft cap 9; final damage = raw − TOL) |
| Stun | STN | Cannot act, Will DC 10 each round to remove |
| Bleeding | BLDe | −1 HP per round (Severe+ −2), first aid stops |
| Poisoned | PSN | Wound level upgrades every 10 min, antidote or Will DC 12 removes |
| Burning | BRN | −1 final damage per round (not reduced by TOL, Severe+ −2), extinguish stops |
| Fear | FER | Will DC 13 failure = only move and minor actions |
| Bound | BND | Cannot move, need to break free |
| Blinded | BLD | Disadvantage on attack checks, Will DC 12 pass or sight restored removes |
| Relationship Value | RV | NPC closeness |
| Suspicion Value | SV | NPC suspicion |
| Encounter Budget | EB | Encounter difficulty budget |
| Returner | — | Death Return ability holder |
| Ouroboros | — | The Time Serpent |
| Eternal Well | — | Default Save Point |

---

> *"Time flows. The serpent still bites its own tail. And you—you stand at the edge of the rift, watching the beginning and end of everything. Are you ready?"*

**Death Return TRPG GM Rulebook v1.0**
