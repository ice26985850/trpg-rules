# Arcane Origins TRPG — Player Rulebook

> **Design Focus:** Mages do not choose spells — they invent them. Shard combination × research loop × Mage Tower management.  
> **Intended Audience:** Players (mage characters)

---

# Chapter One: Core Rules

## 1.1 Dice System

### Core Engine: 2d10 + Attribute

```
check result = 2d10 + Attribute + Proficiency bonus + Facility bonus + other modifiers
```

### Critical Success / Critical Failure

| Result | Condition | Frequency | Effect |
|------|------|------|------|
| **Critical Success** | double 10 | 1% | effect maximized + extra narrative benefit |
| **Critical Failure** | double 1 | 1% | automatic failure + may trigger negative consequences |

### Advantage / Disadvantage

| State | Rule | Expected Value Change |
|------|------|-----------|
| **Advantage** | roll 4d10, take the highest two | approx. +3.3 |
| **Disadvantage** | roll 4d10, take the lowest two | approx. −3.3 |

> Advantage and Disadvantage cancel each other out (regardless of how many of each). Critical Success/Critical Failure is still determined by the original two dice (if the original dice are double 10, even under Advantage only one set of double 10 is judged).

---

## 1.2 Attribute System

### Five Attributes

| Attribute | Meaning | Role in the Research Loop |
|------|------|-------------------|
| **Perception (PER)** | observational ability, sensitivity to magical phenomena | Observe phase |
| **Theory (THY)** | logical reasoning, causal analysis, academic literacy | Hypothesize and analysis phases |
| **Craft (CRA)** | precise manipulation, ritual execution, material handling | Experiment phase |
| **Will (WIL)** | mental resilience, resistance to magical backlash | "can you still hold on?" when an experiment fails |
| **Erudition (ERU)** | existing knowledge reserve, document lookup | Bibliographic research |

### Attribute Value Meaning

| Attribute Value | Meaning |
|--------|------|
| 1 | Catastrophic — publicly acknowledged disaster in this area |
| 2–3 | Weak — clearly below peer average |
| 4–5 | Adequate — baseline level of an Independent Mage |
| 6–7 | Excellent — among the best of peers |
| 8 | Outstanding — has touched the limit of mortal talent |
| 9–10 | Legendary — achievable only through special events or facilities |

> **Attribute is used directly as a modifier.** Attribute 5 is +5, attribute 8 is +8.

---

## 1.3 Derived Attributes

| Derived Attribute | Formula | Description |
|----------|----------|------|
| **Spirit Pool (SP)** | Will × 3 + Theory | energy for casting spells. Half restored on Short Rest (rounded down), fully restored on Long Rest |
| **Safety Threshold (ST)** | Craft + floor(Will/2) + Laboratory Level | maximum damage absorption when an experiment fails. Exceeding it triggers an accident |
| **Research Action Points (RAP)** | 3 + (Theory ≥ 5: +1) + (Chief Apprentice: +1), max 5 | number of actions available to the tower per turn (one week) |
| **Shard Capacity (SC)** | Theory + Erudition + Library Level | number of unused Shards that can be held simultaneously |
| **HP** | 15 + Will | the mage's physical resilience. See 1.4 |
| **Spellbook Capacity (SBC)** | Theory + Erudition | number of spells that can be memorized simultaneously. See 2.15 |

---

## 1.4 HP and Damage

### HP Calculation

```
Max HP = 15 + Will
```

Will directly contributes to HP — a mage with strong spirit can better withstand damage.

### HP Growth

| Path | HP Increase |
|------|---------|
| Will attribute increase (per +1) | Max HP +1 |
| Any attribute reaching 8 | Max HP +5 (one-time) |
| Laboratory reaching Lv5 | Max HP +5 (one-time) |

Theoretical max HP: 15 + 10 (Will 10) + 5 (attribute 8) + 5 (Laboratory Lv5) = 35.

### Injury and Death

**HP drops to 0**: enters **Dying** state — loses consciousness, cannot act, makes a **Death Saving Throw** at the start of each turn.

**Death Saving Throw**: roll 2d10 (no attribute modifier):
- Result ≥ 10: one success
- Result < 10: one failure
- double 1: two failures
- double 10: recover to 1 HP, awaken

Accumulate **3 successes**: stabilized — no longer need Death Saving Throw, recover to 1 HP after 1d4 hours.  
Accumulate **3 failures**: death.

**When taking damage (while Dying)**: automatically counts as one failure. If it is a Critical Hit (double 10 attack), counts as two failures.

### HP Recovery

| Method | Recovery Amount |
|------|--------|
| Short Rest | recover Will value in HP (at least 1) |
| Long Rest | recover all HP |
| "Life" Element spell | see spell effect |
| Tower maintenance action | does not recover HP (only recovers tower HP) |

---

## 1.5 Rest Rules

### Short Rest
- **Time**: 1 hour of light activity (reading, organizing notes, meditation)
- **Location**: inside the tower, or a safe location in the wild (GM's judgment)
- **Effect**: recover half of max Spirit (rounded down) + recover Will value in HP
- **Limit**: at most 2 Short Rests between each Long Rest

### Long Rest
- **Time**: 8 hours (at least 6 hours sleep + 2 hours light activity)
- **Location**: must be at a safe location — tower, defended camp, inn, etc.
- **Effect**: recover all Spirit + recover all HP + remove one level of Fatigue
- **Limit**: only one Long Rest per 24 hours
- **Interruption**: if a Long Rest is interrupted by combat or an emergency for more than 1 hour, it must be restarted

### Wilderness Camping
- Taking a Long Rest in the wild requires successfully establishing a camp: **Perception or Craft DC10**
- Failure: can still take a Long Rest, but recovery effect is halved (half of Spirit and HP each)
- Critical Failure: nocturnal encounter with a wilderness threat (GM rolls the encounter table)

### Fatigue
- For every 24 hours without a Long Rest, gain one level of Fatigue
- Fatigue levels: 1 = all checks −1; 2 = speed halved; 3 = Disadvantage on all checks; 4 = HP halved; 5 = unable to act; 6 = death
- Each Long Rest removes one level of Fatigue

---

## 1.6 Proficiency System

### Skill List (3 per attribute, 15 total)

| Attribute | Skills |
|------|------|
| Perception | Observe, Track, Intuition |
| Theory | Analyze, Reason, Magic Theory |
| Craft | Precise Manipulation, Ritual Execution, Material Handling |
| Will | Concentration, Resistance, Mental Defense |
| Erudition | Document Lookup, Historical Knowledge, Foreign Cultures |

### Proficiency Bonus

| Proficiency Level | Bonus | Cumulative Points Invested |
|----------|------|-------------|
| Novice | +1 | 1 point |
| Proficient | +2 | 2 points |
| Expert | +3 | 3 points |
| Master | +5 | 5 points (unlocked via special event) |

> Each skill is invested independently. When making a check, use "Attribute value + corresponding skill's Proficiency bonus".

### Acquiring Proficiency Points

| Source | Points Gained | Condition |
|------|----------|------|
| **Starting** | **2 points** | gained at character creation |
| Academic Reputation 10 | 1 point | one-time |
| Academic Reputation 30 | 1 point | one-time |
| Academic Reputation 60 | 1 point | one-time |
| Any facility reaching Lv5 | 1 point | once per facility |
| Major Discovery (GM reward) | 1 point | GM's discretion |

> **Total obtainable**: starting 2 + reputation 3 + facilities (up to 8) = up to about 13 points. Can raise about 4–5 skills to Expert level, or 2 skills to Master level.

---

## 1.7 Research Loop

```
set goal → Observe(Perception) → Hypothesize(Theory) → Prepare(consume materials) → Experiment(Craft) → Analyze(Theory)
```

### Accident Trigger Rules

When an experiment fails:
- **Accident margin (DC − check result) ≤ Safety Threshold**: materials consumed, no Shard gained, may retry
- **Accident margin > Safety Threshold**: trigger the d20 Experiment Accident Table (GM reference)

---

## 1.8 Spirit Overexertion

When a spell's Spirit cost exceeds the current Spirit Pool, you may "overextend" to cast:
- For each 1 point of Spirit overextended, take 1d4 force damage (cannot be reduced)
- Overextended Spirit is repaid first at the next Long Rest
- If overextension causes HP to drop to 0, the caster loses consciousness and the spell fails (Spirit already spent is not refunded)

---

# Chapter Two: Character Creation

## 2.1 Creation Process Overview

| Step | Content | Output |
|------|------|------|
| 1 | Background | starting funds, special benefits, initial reputation |
| 2 | Attribute allocation | 25 points allocated to five attributes + 2 Proficiency points |
| 3 | Research style | choose 1 of 5, cannot be changed |
| 4 | Starting Shards | 3 common Element Shards + 1 common Form Shard |
| 5 | Starting spell | first spell combined from starting Shards |
| 6 | Mage Tower | location (city/suburb/wilderness/mobile), name |
| 7 | Research goal | ultimate research concept |
| 8 | Rival | a peer who dislikes you |

---

## 2.2 Step 1: Background

### Noble Scion
| Item | Content |
|------|------|
| Starting funds | 300 GP |
| Starting reputation | Academic 0, Practical +10 |
| Extra benefit | Noble contact network: monthly d20 → 1–10: 1d6×10GP; 11–17: common materials; 18–20: rare collectible |
| Special equipment | Family signet ring (Advantage on social checks at academic conferences) |
| Hidden cost | Academic bias — publishing a paper grants −1 Academic Reputation |

### Street Orphan
| Item | Content |
|------|------|
| Starting funds | 150 GP |
| Starting reputation | Academic −2, Practical 0 |
| Extra benefit | Perception or Craft +1; Advantage on material acquisition checks; street contact NPC |
| Special equipment | Concealment tools |

### Magic Family
| Item | Content |
|------|------|
| Starting funds | 150 GP |
| Starting reputation | Academic +10, Practical 0 |
| Extra benefit | +2 starting document Shards; one monthly family tome consultation; Theory or Erudition +1 |
| Special equipment | Family spellbook (contains a spell recipe with hidden errors) |
| Hidden cost | annual output requirement |

---

## 2.3 Step 2: Attribute Allocation and Proficiency

### Attributes
| Rule | Description |
|------|------|
| Total points | 25 points |
| Single attribute minimum | 1 |
| Single attribute maximum | 7 (background +1 can break through to 8) |
| Timing of allocation | allocate 25 points first, then apply background adjustments |

### Proficiency
Starting gain of **2 Proficiency points**, invest in any skill.

### Recommendations by Style

| Research Style | Priority Attributes | Recommended Proficiency |
|----------|----------|----------|
| Empirical | Craft > Perception > Will | Precise Manipulation, Observe |
| Intuitive | Perception > Theory > Will | Intuition, Magic Theory |
| Bibliographic | Erudition > Theory > Perception | Document Lookup, Analyze |
| Taboo | Will > Craft > Theory | Resistance, Precise Manipulation |
| Collaborative | Theory > Erudition > Craft | Magic Theory, Document Lookup |

---

## 2.4 Step 3: Research Style

> **Once chosen, cannot be changed.**

### Empirical
**Advantage**: Advantage on experiment Craft checks; roll accident table twice take lower  
**Cost**: materials ×1.3; +1 AP to perform experiment (recover 30% materials on failure)  
**School advancement**: 10+ Standardized Process (DC−2) → 30+ Laboratory Automation (free quick experiment) → 60+ Methodology Foundation

### Intuitive
**Advantage**: Hypothesize at zero cost; experiment DC−2  
**Cost**: accident table d12+8 (9–20); notes not reproducible (DC+2)  
**School advancement**: 10+ Flash of Insight → 30+ Intuitive Insight → 60+ Formalized Breakthrough

### Bibliographic
**Advantage**: Library starts at rare tier (50%/35%/15%); Theory advantage in library; zero accidents  
**Cost**: 30% hidden errors; Disadvantage on experiment Craft  
**School advancement**: 10+ Cross-Reference → 30+ Document Authentication → 60+ Encyclopedia

### Taboo
**Advantage**: experiment DC−4; Legendary Shards ×2  
**Cost**: Will DC15/experiment (failure corruption +2); Academic Reputation cap 30; corruption 20 → NPC-ified  
**School advancement**: 10+ Shadow Channel → 30+ (cap) Taboo Acceleration (×3, DC rises to 18)

### Collaborative
**Advantage**: both cooperating parties benefit; DC−2 per assistant (max −6)  
**Cost**: solo DC+3; publishing reveals Shards publicly  
**School advancement**: 10+ Research Network → 30+ Joint Publication (not public) → 60+ School Convocation

**DC modifier stacking order**: first calculate base DC → add style modifier (+3 or −2/person) → subtract facility/material modifiers → finally apply Advantage/Disadvantage.

### Style Quick Reference

| | Empirical | Intuitive | Bibliographic | Taboo | Collaborative |
|---|---|---|---|---|---|
| Experiment DC | Normal | **−2** | Normal (Disadvantage on personal test) | **−4** | +3 / −2 per person |
| Craft | **Advantage** | Normal | **Disadvantage** | Normal | Normal |
| Materials | **×1.3** | Hypothesize zero | Normal | Normal | Normal |
| Accident | Take lower | **d12+8** | Zero (library) | Normal + Will | Normal |
| Legendary efficiency | Normal | Normal | Low | **×2** | Shared |
| Reputation cap | None | None | None | **30** | None |

---

## 2.5 Step 4: Starting Shards

Choose **3 common Element Shards + 1 common Form Shard**.

### Starting Elements (choose 3)

| Code | Element | Common-grade Base Effect |
|------|------|---------------|
| E01 | Flame | 1d6 fire + ignite (DC10 Dexterity → Craft save) |
| E02 | Water Jet | 1d4 bludgeoning + wet (Disadvantage on Lightning save) |
| E03 | Storm | 1d6 slashing + push back 10 ft |
| E04 | Earth | 1d6 bludgeoning + 5 ft difficult terrain |

### Starting Forms (choose 1)

| Code | Form | Effect |
|------|------|------|
| F01 | Projectile | 60 ft, single target, spell attack |
| F02 | Touch | reach, spell attack (Advantage) |
| F03 | Area | 60 ft, 15 ft radius, target Craft save |
| F04 | Cone | self, 30 ft cone, target Craft save |
| F05 | Attached | attach to weapon/object, lasts 1 minute |
| F06 | Delayed | 60 ft, triggers after 1–3 turns |
| F07 | Sustained | 60 ft, requires Concentration, 3+Theory turns |
| F08 | Instant | self/reach, cannot be interrupted by reactions, effect ×0.7 |

---

## 2.6 Step 5: Starting Spell

```
starting spell = 1 Element + 1 Form
```

Quality ★ Apprentice-grade. Spirit cost 1. Automatically passes.

**Example: "Flame Bolt"**
- E01 Flame + F01 Projectile
- ★ Apprentice-grade | Spirit 1
- 60 ft spell attack, hit 1d6 fire + ignite (Craft DC10)

---

## 2.7 Step 6: Mage Tower

### Tower Location

| | City | Suburb | Wilderness | Mobile |
|---|---|---|---|---|
| Maintenance fee adj. | +20/month | 0 | 0 | +50/month |
| Max facility level | 4 | 5 | 5 | 5 |
| Element Chamber cap | 2 | 2 | **3** | 2 |
| Research advantage | Advantage on material purchase | balanced | Advantage on Observe/field gathering | can relocate (every 2 months) |
| Upgrade cost | Normal | Normal | Apprentice dorm ×1.5 | all ×1.5 |

### Tower HP

```
Tower Max HP = 30 + Defense System Level × 5
```

Tower HP drops to 0: all facilities disabled, requires major repair (cost = level × 200GP, takes 2d4 turns).

---

## 2.8 Step 7: Research Goal

Define your ultimate research goal — a spell concept that requires Legendary Shards to complete.

---

## 2.9 Step 8: Rival

### d6 Relationship Origin

| d6 | Relationship | d6 | Relationship | d6 | Relationship |
|----|------|----|------|----|------|
| 1 | Academic plagiarism | 3 | Competing for the same Legendary Shard | 5 | Personal grudge |
| 2 | Split from same mentor | 4 | Methodological opposition | 6 | Mutual respect but competition |

Monthly d20 rival developments: 1–5 public breakthrough; 6–10 setback; 11–15 nothing; 16–20 action affecting the player.

---

## 2.10 Growth and Advancement

### Attribute Improvement

| Path | Condition | Effect |
|------|------|------|
| Major Breakthrough | successfully obtain a Legendary Shard | **on first Legendary Shard obtained**, attribute definitely +1; thereafter 10% chance +1 each time (max +3 per person) |
| Deep Study | 4 consecutive turns DC20 Theory/Erudition | success grants +1 to a chosen attribute (max once per attribute). Failure refunds 2 AP, second attempt DC−2 |
| Master Facility | any facility reaches level 5 | related attribute +1 |

Attribute theoretical cap: 10. HP increases automatically as Will grows.

### Dual-Axis Reputation

| Academic Reputation | Status | Unlock |
|----------|------|------|
| 0–9 | Unknown Scholar | — |
| 10–29 | Cited One | basic school ability; small academic fund; +1 Proficiency point |
| 30–59 | Field Authority | advanced school ability; senior apprentice; +1 Proficiency point |
| 60–79 | Scholarch | master school ability; can found a school; +1 Proficiency point |
| 80+ | Legendary Mage | can change the rules of the academic world |

> **Reputation gain notes**: publishing papers (common +1d3 / uncommon +1d6+2 / rare +2d6+5 / legendary +3d6+10). **When publishing a paper on an element domain for the first time, gain an additional +2 Academic Reputation** (discovery bonus, once per element).

| Practical Reputation | Status | Unlock |
|----------|------|------|
| 0–9 | Nobody Cares | — |
| 10–29 | Local Advisor | accept noble commissions |
| 30–59 | Court Mage Candidate | court stipend +50GP/month |
| 60–79 | "The Mage Who Solves Wars" | royalty provides rare materials/quarter |
| 80+ | National Treasure | may receive a fief |

---

## 2.11 Economy and Materials

### Monthly Income/Expense

| Income | GP/month | Expense | GP/month |
|------|------|------|------|
| Base stipend | 50 | Base maintenance | 30 |
| Academic stipend (≥10) | Academic÷10×20 | City surcharge | +20 |
| Practical stipend (≥10) | Practical÷10×30 | Mobile surcharge | +50 |
| Apprentice reagents | **30**/apprentice | Apprentice salary | 15/person |
| Court stipend (Practical≥30) | 50 | Element Chamber maintenance | 20/each |
| Fief (Practical≥80) | 100 | Defense energy | level×10 |

### Experiment Material Cost

| Rarity | Cost | Empirical (×1.3) | Material Requirement |
|--------|------|--------|----------|
| Common | 5 | 7 | basic reagents sufficient |
| Uncommon | 20 | 26 | corresponding Element specialized reagent ×1 |
| Rare | 80 | 104 | rare material ×1 |
| Legendary | 500+ | 650+ | unique material ×1 (must be obtained through play) |

### Rare Materials List (partial)

| Material | Grade | Typical Source | Reference Price |
|------|------|----------|--------|
| Elemental Essence (Fire/Water/Wind/Earth) | Specialized | Element Chamber synthesis / wild elemental storm | 15–25 GP |
| Phoenix Ash | Rare | volcanic region / alchemical synthesis | 100 GP |
| Dragon Scale | Rare | dragon nest / dragon trade | 150 GP |
| Deep Sea Pearl (magical) | Rare | deep sea ruins / marine creatures | 120 GP |
| Void Crystal | Rare | Void Rift / taboo research | 200 GP |
| Ancient Dragon's Heartblood | Unique | dragon's deathbed ritual | 1000+ GP |
| Selena's (賽琳娜) Prime Shard | Unique | deep Spirit Realm (Scenario Five) | not purchasable |
| Mark of the Void God (虛無之神) | Unique | core of the Void Rift (Scenario Five) | not purchasable |

### Research Discounts

- **First Exploration Bonus**: when a mage researches a specific element's rare Shard for the first time, material cost is **halved** (once per element). This discount does not stack with other discounts.
- **Material Recovery (Empirical)**: when an experiment fails, recover 30% of material cost (rounded down, at least 1GP refunded). Recovered amount is added directly back to Gold Pieces.

---

## 2.12 Equipment and Consumables

▶ For the complete list of magical equipment, consumables, and alchemical items (with prices and effects), see **`assets/Equipment Compendium.md`**. The compendium contains two parts — "Advanced and Plot Equipment" and "Player Starting Equipment List" — for starting purchases, consult the latter.

Purchasing equipment consumes Gold Pieces (GP); prices and effects follow the compendium.
---
## 2.13 Tower Management

### Action Point Economy

| Base | Theory≥5 | Chief Apprentice | Cap |
|------|--------|----------|------|
| 3 | +1 | +1 | **5** |

Each turn = 1 week.

### Action List

| Action | AP | Description | Key Check |
|------|-----|------|----------|
| Run experiment | 3 (Empirical 4) | full research loop | Perception → Theory → Craft → Theory |
| Quick experiment | 2 (Empirical 3) | retry known target | Craft |
| Library research | 2 | obtain Shards from documents | Erudition or Theory |
| Spell combination | 1 | combine Shards into a spell | Theory |
| Spell correction | 2 | remove side effects | Theory |
| Facility upgrade | 1 | start construction | — |
| Material acquisition (outing) | 3 | wild/market | Perception or social |
| Delegate to apprentice | 0 | apprentice executes | apprentice skill |
| Teach apprentice | 2 | improve apprentice | Theory or Craft |
| Tower maintenance | 1 | recover tower HP 1d6; check contained items | — |
| Social activity | 1–3 | visit, seminar | social |
| Write paper | 2 | prepare for publication | Erudition or Theory |
| Deep study | 1 × 4 turns | attempt to raise attribute | Theory or Erudition DC20 |
| Establish communication | 1 | establish Scrying Pool communication with another mage tower | — |

### Eight Tower Facilities Quick Reference

| Facility | Lv1 | Lv2 | Lv3 | Lv4 | Lv5 |
|------|-----|-----|-----|-----|-----|
| **Laboratory** | Safety +1 | +2, parallel 1 prep | +3, parallel 2 experiments | +4, DC−1, accident take lower | +5, free reroll, HP+5 |
| **Library** | Theory +1, 5 Shards | +2, 10 Shards | +3, 20 Shards, lend/borrow | +4, known DC−2 | +5, infinite, gain 1 Shard/month |
| **Element Chamber** | DC−1 | DC−3, accident take lower | DC−5, monthly purification | — | — |
| **Observatory** | Perception +1 | +2, detect 10km | +3, predict 1 turn | +4, perceive Spirit Realm | +5, Critical Failure to normal |
| **Containment Chamber** | capacity 1, 30% escape | 2, 20% | 4, 10% | 6, 5% | 10, 1% |
| **Apprentice Dormitory** | 1 person 20% botch | 2 persons 10% | 4 persons 5% + Chief | — | — |
| **Defense System** | 5 defense | 10, alarm | 15, anti-magic | 20, golem | 30, teleport interception |
| **Scrying Pool** | 50km | 500km | continental range | — | — |

> Full upgrade costs see GM Rulebook.

### Apprentice Management

| Level | Tasks Executable | Success Rate |
|------|-----------|--------|
| Trainee (newly recruited) | collect common materials, maintenance | 50% |
| Qualified (taught 2 times) | + run common experiments, make reagents | 65% |
| Senior (taught 4 times) | + run rare experiments, independent library | 75% |
| Chief | + independently manage research loop | 85%+ special skill |

**Chief Apprentice condition**: Apprentice Dormitory Lv3 + select one from Senior apprentices already taught 4+ times.

**Chief special skill (d8)**: 1 Alchemy Talent 2 Research Intuition 3 Safety Expert 4 Document Speed 5 Wilderness Survival 6 Social Butterfly 7 Defense Specialization 8 Secret Talent

---

## 2.14 Wilderness Exploration

### Travel Speed

| Method | Daily Distance | Cost |
|------|----------|------|
| Walking | 30 km | 1 Ration |
| Horseback | 60 km | 2 Rations + 10GP (relay station) |
| Carriage | 40 km | vehicle maintenance |
| Teleport Gate | instant | 100GP + requires known bearings |
| Mobile Tower | 10 km (when relocating) | 50GP/month maintenance |

### Wilderness Actions

| Action | Check | Description |
|------|------|------|
| Search area | Perception DC set by GM | can search about 500 ft square per hour |
| Track | Perception (Track) vs target Craft | requires footprints or other traces |
| Sneak | Craft (Stealth) vs target Perception | requires cover or dim environment |
| Gather materials | Perception + Erudition DC12 | success gains 1d3 portions of basic reagents |
| Establish camp | Perception or Craft DC10 | safe overnight, failure halves Long Rest effect |
| Detect danger | Perception DC set by GM | used passively (GM rolls secretly) |

### Wilderness Encounter Frequency

Each travel day or camping, GM rolls d20: 17–20 triggers an encounter (by terrain). Encounter is not necessarily combat — may be a natural magical phenomenon, a merchant, or another mage's exploration party.

---

## 2.15 Social Rules

### NPC Attitude

| Attitude | Modifier | Description |
|------|------|------|
| Hostile | DC +4 | unwilling to communicate, may attack directly |
| Unfriendly | DC +2 | reluctant, needs persuasion |
| Neutral | DC +0 | normal interaction |
| Friendly | DC −2 | willing to help |
| Ally | DC −4 | actively assists |

### Social Checks

| Action | Check | Opposed By |
|------|------|------|
| Persuade | Theory or Erudition + Proficiency | target Will (may add attitude modifier) |
| Deceive | Theory + Proficiency | target Perception |
| Intimidate | Will + Proficiency | target Will |
| Impression (first meeting) | Erudition or Perception + Proficiency | DC by occasion |

- Success: attitude rises one level (cap at Friendly)
- Critical Success: attitude rises two levels + gain extra information
- Failure: attitude unchanged, retry DC+2
- Critical Failure: attitude drops one level, cannot retry (at least that day)

### Academic Debate

Opposed Theory check, best of three:
- Each round: both sides 2d10 + Theory + Proficiency, higher wins
- Well-prepared position paper: +1 each (max +3)
- Expose opponent's weakness: opponent has Disadvantage that round
- Winner gains reputation (see reputation event table)

---

## 2.16 Spellbook and Memory

### Spellbook Capacity

```
number of spells memorizable = Theory + Erudition
```

- Starting mage (Theory 3–5, Erudition 3–5) can memorize 6–10 spells
- Spells over capacity are still recorded in notes, but cannot be quickly cast during adventure
- In the tower, spend 1 AP to swap a memorized spell

### Casting a Created Spell

- Created and recorded spells can be cast repeatedly, paying Spirit cost each time
- No need to re-make the spell combination check
- All spell arguments (damage dice, DC, duration) are **locked at creation** — based on the Theory value and quality grade at creation
- If Theory value increases, already-created spells do not automatically grow stronger — must recreate a new version

### Spirit Handling on Casting Failure

| Situation | Spirit |
|------|------|
| Spell attack misses | full cost |
| Target save succeeds (half damage) | full cost |
| Concentration interrupted | already spent, not refunded |
| Counterspelled | already spent, not refunded |
| Casting interrupted midway (e.g. ritual interrupted) | refund half (rounded down) |

> **Core principle**: Spirit is paid in full at the moment the spell completes casting. Once the spell "leaves the hand", Spirit is consumed.

### Locking of Sustained Spells

- Lock all arguments at casting (sustained turns, DC, effect)
- After casting, even if Theory value changes, an already-active sustained spell is unaffected
- Concentration interrupted: spell ends immediately, Spirit not refunded

---

## 2.17 Multiplayer and Tower Interaction

### Default Setup

Each player has their own independent tower. Players interact through the following means:

### Communication Methods

| Method | Condition | Cost |
|------|------|------|
| Letter | none | 1–3 days delivery (by distance) |
| Scrying Pool communication | both have Scrying Pool Lv1+ | 10 Spirit per call |
| Scrying Pool teleport gate | both have Scrying Pool Lv2+ | 20 Spirit/hour |

### Meetings and Cooperation

- **Academic Conference**: held regularly, all mages may attend (arranged by GM)
- **Visiting**: spend travel time to go to another player's tower
- **Temporary Base**: in scenarios, players may choose one player's tower as a "rendezvous point"

### Collaborative Style Special Rules

- A Collaborative mage visiting another mage's tower **does not consume travel action points** (magic link already established)
- The Collaborative mage's Research Network ability allows maintaining cooperative relationships with multiple mages simultaneously

### Group Research

When multiple players research at the same location:
- May use the "cooperative research" rule (assistant provides DC−1/person, max −3)
- Library Lv3+ can establish "inter-library loan" — participating mages share Shard Capacity

---

# Chapter Three: Spells and Conflict

## 3.1 Spell Creation Principles

### Core Formula

```
Spell = Element (1–3) + Form (1–2) + [Medium (0–2)] + [Constraint (0–2)]
```

Minimum 2 Shards, recommended maximum 7 Shards.

### Creation Process

1. Choose Element (1–3) → damage type and main effect
2. Choose Form (1–2) → range/area/duration
3. Optional Medium (0–2) → condition for benefit
4. Optional Constraint (0–2) → cost for benefit
5. Calculate Quality (highest rarity)
6. Calculate Spirit cost
7. Name → GM review

---

## 3.2 Shard Overview

▶ The complete list of Element Shards (15 types), Form Shards (8 types), Medium Shards (7 types), Constraint Shards (7 types) — including base values, rare/legendary upgrades, and Element cross effects — see **`assets/Shard Compendium.md`**.

Spells are composed of the above four types of Shards (see 3.1 Core Formula). For specific entries and values, consult the compendium; this book does not restate them.
---
## 3.6 Quality Grades and Effect Scaling

| Quality | Stars | Requirement | Multiplier |
|------|------|------|------|
| Apprentice-grade | ★ | all common | ×1.0 |
| Formal-grade | ★★ | ≥1 uncommon | ×1.5 |
| Expert-grade | ★★★ | ≥1 rare | ×2.0 |
| Master-grade | ★★★★ | ≥1 legendary | ×3.0 |
| Legendary-grade | ★★★★★ | ≥2 legendary | ×5.0 |

| Quality | Damage Dice | Range | Radius | Duration | Healing |
|------|----------|------|------|------|------|
| ★ | 1 | 60 ft | 15 ft | 3+Theory | 1d8 |
| ★★ | 2 | 90 ft | 22 ft | 4+Theory | 2d8 |
| ★★★ | 2 | 120 ft | 30 ft | 6+Theory | 2d8 |
| ★★★★ | 3 | 180 ft | 45 ft | 9+Theory | 3d8 |
| ★★★★★ | 5 | 300 ft | 75 ft | 15+Theory | 5d8 |

---

## 3.7 Spirit Cost

```
Spirit cost = base value × quality coefficient (rounded down, minimum 1)
```

| Shard Count | Base | ★(×0.5) | ★★(×1.0) | ★★★(×1.5) | ★★★★(×2.5) | ★★★★★(×4.0) |
|--------|------|----------|-----------|------------|-------------|--------------|
| 2 | 2 | 1 | 2 | 3 | 5 | 8 |
| 3 | 4 | 2 | 4 | 6 | 10 | 16 |
| 4 | 6 | 3 | 6 | 9 | 15 | 24 |
| 5 | 8 | 4 | 8 | 12 | 20 | 32 |
| 6 | 12 | 6 | 12 | 18 | 30 | 48 |
| 7 | 16 | 8 | 16 | 24 | 40 | 64 |

---

## 3.8 Casting Rules

### Casting Check
- **Spell attack** (Projectile, Touch): `2d10 + Theory value + Proficiency bonus`
- **Spell save DC** (Area, Cone, Sustained): `10 + Theory value + Proficiency bonus`

### Save Attribute Mapping (player vs spell)

| Save required by spell | Attribute used by player |
|---------------|---------------|
| Dexterity (dodge) | **Craft** |
| Constitution (endurance) | **Will** |
| Perception (psychic) | **Perception** |
| Theory (magic) | **Theory** |

### Action Economy
Each turn: 1 major action + movement + 1 bonus action + 1 reaction

### Concentration Rules
- Can only maintain one Concentration-requiring spell at a time
- When taking damage, Will save (DC = 10 or half damage, whichever higher); failure → Concentration interrupted
- Knocked down/unconscious → automatically interrupted

---

## 3.9 Element Cross Rules

When a spell contains two or more Elements simultaneously, an "Element cross" effect is triggered. The specific synthesis results for dual-Element (13 types) and triple-Element (4 types) are detailed in the "Dual/Triple Element Cross" section of **`assets/Shard Compendium.md`**.

Basic principle: cross effect intensity increases with the number of Elements and rarity, and overrides the base effect of a single Element.
---
## 3.10 Spell Duels

### Spell Collision
Both sides `2d10 + Theory + Proficiency` opposed:
- Winner advances, loser dissipates
- Tie: 15 ft force explosion (equal to the higher base die)
- Both double 10: miracle collision (GM adjudicates)

### Counterspell
Instant spells can be used to counterspell. Counterspeller's spell attack vs target spell DC:
- Counterspeller wins: target spell suppressed
- Difference ≥5: reflection (counterspell's base damage)
- Target wins: counterspell dissipates

---

## 3.11 Paths to Obtain Taboo Shards

Taboo Elements (Blood, Soul, Chaos) DC30 — this is a ceiling unreachable by attributes alone. Paths to achieve:

```
DC30 = 2d10 + 8 (Will/Theory) + 5 (Proficiency Master) + 5 (facility Lv5) = 2d10 + 18
```

Plus: Element Chamber (−5) + rare material (−3) + documents (−2) = net DC20  
2d10+18 vs DC20 = 64% success rate.

**Invest top resources** (Taboo style DC−4): net DC16  
2d10+18 vs DC16 = 85% success rate.

The Taboo style's Legendary Acceleration (acquisition rate ×2 or ×3) further boosts efficiency. This means researching Legendary Taboo Shards is a lifelong pursuit — not easily achieved, but not impossible.

---

## 3.12 Example Spell Library

### ★ Apprentice-grade

**Searing Missile**: Flame + Projectile | 1 Spirit | 60 ft spell attack, 1d6 fire + ignite (Craft DC10)  
**Frost Touch**: Frost + Touch | 1 Spirit | reach spell attack (Advantage), 1d6 frost + speed −10 ft

### ★★ Formal-grade

**Firestorm**: Flame (◑) + Storm (◑) + Area | 4 Spirit | 90 ft/33 ft, 2d6 fire + 2d6 slashing + push back

### ★★★ Expert-grade

**Void Grasp**: Void (◆) + Force (◑) + Touch + Blood Sacrifice | 9 Spirit | reach, 2d8 void + 1d4 + 2 force, recover 50%  
**Holy Light Burst**: Radiance (◆) + Life (◆) + Area + Safety Lock | 9 Spirit | 120 ft/30 ft, enemies 2d6 radiance (undead +1d6), allies 2d8 healing

### ★★★★ Master-grade

**Phoenix Judgment**: Flame (◈) + Radiance (◆) + Life (◆) + Area + Instant | 30 Spirit | 45 ft radius, 3d6 fire (ignores resistance), allies 3d8 healing, revive from death

### ★★★★★ Legendary-grade

**Falling Stars**: Flame (◈) + Radiance (◈) + Void (◆) + Area + Delayed + Cooldown | ~42 Spirit | detonates after 3 turns at 75 ft radius, 5d6 fire + 5d6 radiance + 3d8 void  
**Eternal Winter**: Frost (◈) + Void (◈) + Storm (◆) + Area + Sustained + Ritual + Concentration | 32 Spirit | 1 minute casting, 300 ft/75 ft miniature winter domain, 5d6 frost + 3d8 void per turn

---

> **Closing**: Arcane Origins is not a game about "getting stronger" — it is a game about "seeking knowledge". Your fireball is unlike any other mage's. Pick up your parchment, and prepare to face exploding hypotheses.
