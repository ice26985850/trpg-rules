# League of Legends TRPG — GM Toolkit v0.2

> This document is split from Chapter Four of the main rulebook and collects all GM-only tools.
> Before use, read the main rulebook `LOL_TRPG_Rulebook_v0.2.md`.

---

## 📑 Table of Contents

- I. Regional Battlefield Rules
- II. GM Running Guide
- III. Narrative Rules
- IV. Enemy AI Rules
- V. GM Difficulty Adjustment Quick Reference
- VI. Quick Reference Cards
- VII. Exploration & Travel Rules
- VIII. Downtime Activities
- IX. Social Conflict System
- X. Environmental Hazards
- XI. Non-Combat Economy
- XII. Per-Level DPR Baseline Table

---

## I. Regional Battlefield Rules

When combat occurs in a specific region, apply the following field effects. This makes the same fight feel completely different depending on where it happens:

| Regional Battlefield | Field Effect | Appearance Chance |
|------|------|:--:|
| Freljord Tundra | Every 3 turns a full-field frost storm: Move Speed -2, ranged hit DC +2 (lasts 1 turn) | 70% |
| Shurima Desert | Sandstorm shifts 1d4 squares every 2 turns, reduces area vision to 2 squares | 60% |
| Shadow Isles | After an ally dies, acts as a "soul" for 2 turns: HP=1, invulnerable, cannot attack, can move and use non-damage skills | 80% |
| Zaun Inferno | Every turn full-field poison fog: all non-mechanical units take HP×1% true damage | 50% |
| Ionia Sacred Grove | At start of each turn all heal 5+AP×0.1 HP; fire spells disabled in range | 40% |
| Bilgewater Harbor | Every 2 turns a 1-square cannon barrage: AD×1.5 physical damage (random location), DC15 Perception to dodge early | 50% |
| Demacia Fortress | 2-3 anti-magic stone pillars on field (HP 100), within 2 squares of a pillar AP halved | 60% |
| Noxus Arena | Full-field damage +10%; crowd throws weapons: every 3 turns a random unit gets a random thrown item (heal/damage/control) | Per story |

### Random Field Draw (d8)

| d8 | Region | d8 | Region |
|:--:|------|:--:|------|
| 1 | Freljord Tundra | 5 | Ionia Sacred Grove |
| 2 | Shurima Desert | 6 | Bilgewater Harbor |
| 3 | Shadow Isles | 7 | Demacia Fortress |
| 4 | Zaun Inferno | 8 | Noxus Arena |

---

## II. GM Running Guide

### Standard 4-Hour Session Structure

| Time | Length | Content | Beat |
|:--:|:--:|------|:--:|
| 0:00-0:15 | 15 min | Recap + opening hook | Reveal |
| 0:15-1:00 | 45 min | First encounter (explore/social/skirmish) | Challenge |
| 1:00-1:15 | 15 min | Transition: handle consequences, character RP | Consequence |
| 1:15-1:30 | 15 min | Breathing room (shopping/dialogue/intel) | Breather |
| 1:30-2:00 | 30 min | Second encounter (core fight or key choice) | Challenge |
| 2:00-2:15 | 15 min | Intermission + plot twist reveal | Reveal+Breather |
| 2:15-3:00 | 45 min | Third encounter (last obstacle before climax) | Challenge |
| 3:00-3:15 | 15 min | Boss fight prep + choice moment | Consequence |
| 3:15-3:50 | 35 min | Boss fight | Challenge (finale) |
| 3:50-4:00 | 10 min | Ending narration + reward distribution | Breather + Reveal |

### Four-Beat Rule

1. **Reveal**: Give new information (scene, NPC, clue)
2. **Challenge**: Let players act (combat/skill check/social gambit)
3. **Consequence**: Show the result of actions (success/failure/surprise)
4. **Breather**: Give characters RP space and players thinking room

### Encounter Design Principles

**Three-Wave Combat Design**:
- Wave 1: Probing contact (enemy frontline + ranged)
- Wave 2: Tactical escalation (enemy reinforcements, Boss appears)
- Wave 3: Climax (Boss enters final phase, environment shifts)

**Five Elements of a Boss Fight**:
1. Clear weak point (Baron's Eye, anti-magic stone core)
2. Phase transition (HP threshold or turn trigger)
3. Environmental interaction (destructible pillars, energy pools)
4. Party role division (tank holds aggro, carry hits weak point, support cleanses debuffs)
5. Time pressure (berserk timer, minion reinforcements)

### MOBA Objective Narrative Conversion

| MOBA Objective | Narrative Scene |
|-----------|-----------|
| Push tower | Break through enemy lines / destroy enemy stronghold |
| Slay dragon | Delve into forbidden land for ancient power |
| Teamfight | Ambush enemy elite / defend key NPC |
| Hold lane | Escort caravan through occupied zone |
| Vision | Infiltrate enemy camp, plant spies |
| Farm | Seek lost artifact to empower self |

### Five-Element Improvised Scene Building

When a scene must be generated quickly on the spot:
1. **Location**: Where? (roll d8 for region)
2. **Danger**: What threat? (combat/trap/environment)
3. **Reward**: What makes it worth the risk? (intel/gear/gold/bond)
4. **NPC**: Who is here? (friendly/neutral/hostile)
5. **Time**: How much time? (turn limit / countdown / unlimited)

---

## III. Narrative Rules

### Group Decision Mechanism

| Mode | Rule | Applicable Scene |
|------|------|----------|
| **Consensus** | All agree | Major moral choice |
| **Captain** | Designated captain has final say | Combat command |
| **Roll** | When opinions clash, relevant skill contest | Cannot reach consensus |

### Fate Die

Once per chapter: A player uses the "Fate Die" to rewrite a small detail (an NPC happens to know someone, an unexpected item is at the scene, etc.); the GM adjudicates.

### Choice Moment

Moral/emotional choices at the climax affect Boss fight mechanics — e.g., choosing "save the hostage" gives the Boss a certain weakness but adds a turn limit.

### Background Tag System

**Three-layer tags**:
- **Origin tag**: Where from, what identity
- **Loyalty tag**: Why fight, whom serve
- **Secret tag**: Hidden ambition or fear

**Invocation rules**:
- **Active invocation** (2/chapter): Checks related to the tag gain Advantage
- **Passive invocation** (GM-triggered): Tag causes Disadvantage, grants a narrative reward
- **Forced invocation** (story progression): Tag drives the character to automatically make a choice

### "Yes, And…" Rule

| Player says | GM Response Mode |
|------|------|
| Feasible and fun | "Yes, and…" → add a reward |
| Feasible | "Yes." → execute normally |
| Risky | "Yes, but…" → with a cost or disadvantage |
| Infeasible | "No, but…" → offer an alternative |
| Disruptive | "No." → explain why |

### Three-Layer Secret Structure (for designing adventures)

| Layer | Content | Reveal Timing |
|:--:|------|:--:|
| **Surface truth** | Clues discoverable on first investigation | First encounter |
| **Hidden truth** | Backstage motive needing deep exploration | After second encounter |
| **Core truth** | Ultimate secret that changes all understanding | Before Boss fight |

---

## IV. Enemy AI Rules

When the GM controls the enemy lineup, use simplified AI:

### Behavior Die

`1d6 → 1-2 Defend / 3-4 Balanced / 5-6 Aggressive`

### AI Behavior Table

| Behavior | Roll | Assassin/Marksman enemy | Warrior enemy | Mage/Support enemy |
|------|:--:|------|------|------|
| Defend | 1-2 | Retreat 1 sq + attack farthest target | Hold ground + taunt | Heal most-wounded ally |
| Balanced | 3-4 | Attack nearest low-HP target | Attack nearest target | Attack + shield |
| Aggressive | 5-6 | Dash to backline + full output | Charge squishiest target | Ultimate priority (if cooldown allows) |

### 5 NPC Templates

| Template | HP | AD | AP | AR | MR | AS | Corresponding Archetype |
|------|:--:|:--:|:--:|:--:|:--:|:--:|----------|
| Assassin | 500 | 55 | 0 | 35 | 30 | 0.70 | Assassin |
| Warrior | 550 | 60 | 0 | 35 | 30 | 0.65 | Warrior |
| Mage | 450 | 45 | 48 | 20 | 28 | 0.60 | Mage |
| Marksman | 480 | 58 | 0 | 25 | 28 | 0.75 | Marksman |
| Support | 520 | 48 | 38 | 30 | 30 | 0.60 | Support |

The GM may override AI rolls as tactics require.

### NPC Quick Generator (d6 × d6)

| Roll | Template | Strength Mod | Skill Set |
|:--:|------|:--:|------|
| 1 | Assassin | -20% HP/AD (mook) | Skill Catalog §2, pick Assassin Template A |
| 2 | Warrior | -10% HP/AD (elite) | Skill Catalog §3, pick Warrior Template A |
| 3 | Mage | Baseline (standard enemy) | Skill Catalog §4, pick Mage Template A |
| 4 | Marksman | Baseline | Skill Catalog §5, pick Marksman Template A |
| 5 | Support | +10% HP (elite) | Skill Catalog §6, pick Support Template A |
| 6 | Any + 1 Rare Augment | +30% HP/AD (captain) | Self-pick template + Augment Device |

---

## V. GM Difficulty Adjustment Quick Reference

### Basic Adjustments

| Problem | Adjustment Direction |
|------|----------|
| Players too strong | Lower enemy attributes ~10% |
| Players too weak | Raise own HP or minion waves |
| Challenge too easy | Raise EXP gain, set starting level to Lv.3 |
| Combat too long | Lower skill base damage 10-20% |
| Farming too slow | Base AD+5 |

### DC Quick Reference Table

| Difficulty | DC | Description | Example Scene |
|------|:--:|------|----------|
| Trivial | 5 | Nearly impossible to fail | Climb a low wall barehanded |
| Simple | 10 | 50/50 for the untrained | Recognize common herbs |
| Medium | 15 | Requires professional training | Pick a simple rune lock |
| Hard | 20 | Expert-level challenge | Stealth through a dense patrol camp |
| Very Hard | 25 | Master-level feat | Hit a target 300 yards away in a storm |
| Legendary | 30 | Beyond mortal limits | Decipher lost millennium-old god-script |

### Encounter Difficulty Budget

| Difficulty | Total Enemy XP Budget (vs 5-person party) | Note |
|------|:--:|------|
| Easy | 50% of party XP | Consumes few resources |
| Normal | 75% of party XP | Normal challenge |
| Hard | 100% of party XP | A character may fall |
| Lethal | 150% of party XP | Death risk |

---

## VI. Quick Reference Cards

### Opening Hook Template

```
"You meet at [location]. The air is thick with [smell/sound].
 [NPC name] says to you: '[quest briefing].'
 From here — what do you do?"
```

### Pacing Transition Signals

| From | To | Transition Line |
|------|------|------|
| Narrative | Combat | "You hear footsteps approaching — roll initiative." |
| Combat | Narrative | "The last enemy falls. Smoke clears, and you see…" |
| Exploration | Social | "The door opens. Standing behind it is an unexpected figure…" |
| Climax | Ending | "With the Boss's final cry — the story draws to its close." |

### Atmosphere Control

| Region | Keywords | Sensory Detail |
|------|------|------|
| Demacia | White, order, oppression | Marble reflections, anti-magic stone hum, patrol footsteps |
| Noxus | Rust, ambition, power | Forge heat, boot tremors, scent of blood |
| Freljord | Frost, ancient, wild | Howling wind, cracking ice, campfire crackle |
| Shadow Isles | Death, mist, despair | Cold damp of black fog, whispers of the dead, sweet rot |

---

## VII. Exploration & Travel Rules

### Travel Pace

Long-distance movement uses "travel day" as the unit. Each day is split into three periods: **Morning, Afternoon, Night**. Each period allows 1 main activity.

| Activity | Periods Needed | Effect |
|------|:--:|------|
| Fast March | 1 | Move 2× distance, but all make Constitution DC15 or gain 1 Fatigue level |
| Normal March | 1 | Move standard distance (by terrain) |
| Cautious March | 2 | Move standard distance + Stealth check Advantage + no ambush |
| Scout | 1 | Perception DC -5, discover hidden paths/resources |
| Forage | 1 | DC15 Survival check, success yields 1 day of food/water |
| Rest | 1 | Effect equals a short rest |
| Make Camp | 1 (night) | Set up camp, gain safe long-rest environment |

### Daily Movement Distance (normal march)

| Terrain | Daily Distance | Encounter Chance |
|------|:--:|:--:|
| Road/Plains | 30 sq | 15% (d20 ≤3) |
| Forest/Hills | 20 sq | 25% (d20 ≤5) |
| Mountain/Swamp | 10 sq | 30% (d20 ≤6) |
| Desert/Icefield | 8 sq | 20% (d20 ≤4) |
| Zaun Undercity | 5 sq | 40% (d20 ≤8) |

### Navigation Check

When traveling in unfamiliar areas, roll DC15 Survival (PER) check daily:

| Result | Effect |
|:--:|------|
| Success | Advance normally |
| Failure | Off course, lose half a day's progress |
| nat1 | Lost — need DC18 check to reorient |

### Fatigue

Characters accumulate Fatigue levels:

| Fatigue Level | Effect |
|:--:|------|
| 1 | Initiative -2 |
| 2 | Move Speed -1, Initiative -4 |
| 3 | Disadvantage on all checks |
| 4 | Move Speed halved, Max HP -20% |
| 5 | Cannot act, need immediate long rest |

Each long rest removes 1 Fatigue level. Consecutive long rests speed recovery.

---

## VIII. Downtime Activities

Between chapters (or extra time during a long rest), characters may perform the following activities:

### Training

| Activity | Cost | Effect |
|------|:--:|------|
| Skill Training | 5 days + 500 gold | Gain 1 new skill proficiency |
| Physical Training | 3 days + 200 gold | Permanent HP +10 (max 3/campaign) |
| Tactical Study | 3 days + 300 gold | Next chapter, Advantage on initiative checks (1 use) |

### Crafting

| Item | Cost | Requirement |
|------|:--:|------|
| Health Potion | 25 gold + half day | Alchemy tools |
| Shimmer Injector | 100 gold + 1 day | Arcane DLC Shimmer formula |
| Hextech Crystal (standard) | 300 gold + 2 days | Hextech Forging knowledge (Piltover origin or DC18 Lore) |
| Trap Kit (3) | 150 gold + 1 day | DC12 Lore |

### Social Activities

| Activity | Cost | Effect |
|------|:--:|------|
| Build Connections | 200 gold + 3 days | Gain 1 local contact (provides intel/small quests) |
| Gather Intelligence | 100 gold + 1 day | DC15 Persuasion → gain 1 hidden intel for next chapter |
| Manage Reputation | 500 gold + 5 days | +1 reputation in a designated region (affects shop discount/quest access) |

### Research

| Activity | Cost | Effect |
|------|:--:|------|
| Decode Ancient Text | 3 days + DC18 Lore | Gain 1 hidden plot clue |
| Monster Research | 2 days + DC15 Lore | +10% damage vs a specific monster type (next chapter) |
| Recipe Development | 5 days + 1,000 gold + DC20 Lore | Craft 1 unique item (GM review) |

---

## IX. Social Conflict System

When a social scene needs structured handling (negotiation, debate, interrogation), use the following system.

### Social Round

Similar to combat, but uses **social initiative**. Roll d20 + CHA modifier to decide speaking order.

### Social Actions

Each turn allows 1 main social action:

| Action | Check | Effect |
|------|:--:|------|
| **Persuade** | DC by target stance | Target attitude shifts +1 toward players |
| **Intimidate** | DC by target stance (Disadvantage vs high-status target) | Immediate concession but long-term relationship -1 |
| **Deceive** | Contest target PER (passive awareness) | Short-term mislead; if exposed, relationship resets to zero |
| **Empathize** | DC15 (no attitude change) | Reveal 1 hidden motive of target |
| **Provoke** | Contest target CHA | Target loses composure next turn (Disadvantage on all social checks) |
| **Concede** | No check | Give concession, target attitude +1, but lose negotiation leverage |

### NPC Attitude Ladder

| Attitude | Starting DC | Help Willing to Offer |
|:--:|:--:|------|
| Hostile | DC25 | Any help requires coercion |
| Cold | DC20 | Intel exchange (equivalent value) |
| Neutral | DC15 | Small help (directions, discount) |
| Friendly | DC12 | Medium help (lend gear, accompany) |
| Ally | DC8 | Large help (risk own life) |

### Negotiation Leverage

Players may use the following leverage to lower DC:
- Money: every 200 gold -1 DC (max -5)
- Intel: providing valuable intel -3 DC
- Reputation: each region reputation level -1 DC
- Threat: show of force -5 DC (but relationship permanently -2)

---

## X. Environmental Hazards

### Fall Damage

| Fall Squares | Damage | Note |
|:--:|:--:|------|
| 1-2 sq | AD×0.5 | Light injury |
| 3-4 sq | AD×1.0 | Moderate |
| 5-7 sq | AD×1.5 | Heavy |
| 8-9 sq | AD×2.0 | Broken bones |
| 10+ sq | AD×3.0 | Lethal |

**Reduction**: Characters with AGI modifier ≥ +3 may make DC15 Acrobatics check; success treats the fall as 2 squares lower.

### Drowning

A character can hold breath in water for (CON × 2) turns. After that, CON DC15 check each turn; failure deals HP×10% damage (ignores Armor).

### Extreme Temperature

| Temperature | Effect | Protection |
|------|------|------|
| Cold (Freljord) | Each turn CON DC12 or Move Speed -1 (stackable) | Warm clothing |
| Extreme Cold (blizzard) | CON DC15 or HP×3% frost damage (per turn) | Magic protection |
| Heat (Shurima) | Each turn CON DC12 or Fatigue +1 | Water supply |
| Lava/Flame | HP×5% fire damage (per turn) | Fire-immune gear |

### Traps

| Trap Type | Perception DC | Damage | Disarm DC |
|------|:--:|------|:--:|
| Tripwire | 12 | None (triggers alarm) | 10 |
| Poison Dart | 15 | AD×1.0 + 3 stacks Poison | 15 |
| Falling Rocks | 18 | AD×2.0 (2-sq range) | 18 |
| Magic Rune | 20 | AP×2.0 + Silence 2 turns | 20 (Lore) |
| Void Rift | 22 | HP×10% true damage (per turn, 3 turns) | 25 |

---

## XI. Non-Combat Economy

### Hiring & Services

| Service | Cost | Note |
|------|:--:|------|
| Mercenary (1/day) | 50 gold | Use generic template NPC (Assassin/Warrior/Mage/Marksman/Support) |
| Elite Mercenary (1/day) | 200 gold | +30% HP/AD |
| Guide (1 day) | 100 gold | Removes navigation check need |
| Informant (1 tip) | 100-500 gold | By intel value |
| Bribe Official | 500-2,000 gold | By official rank |
| Forge Documents | 300 gold | DC Perception 15 to detect |

### Property & Investment

| Investment | Cost | Return |
|------|:--:|------|
| Shop Shares (5%) | 5,000 gold | 500 gold passive income per chapter |
| Workshop | 10,000 gold | Crafting cost -30% |
| Small Base | 20,000 gold | Safe long rest + free warehouse + 1 butler NPC |
| Vessel | 15,000 gold | Sea travel + naval combat ability |

### Reputation Discount

| Region Reputation | Shop Discount | Unlocks |
|:--:|:--:|------|
| 0 | None | Basic goods |
| 1-3 | 5% | Rare consumables |
| 4-6 | 10% | Rare-rarity Augment Device |
| 7-9 | 15% | Legendary equipment commission crafting |
| 10 | 20% | Region-exclusive Legendary equipment |

---

## XII. Per-Level DPR Baseline Table

Reference for the GM when designing custom monsters and adjusting overall difficulty.

### Player-Side Expected Damage Per Round (DPR)

| Level | ADC (single) | Mage (AOE) | Assassin (burst) | Warrior (sustained) | Party Total DPR (5) |
|:--:|:--:|:--:|:--:|:--:|:--:|
| 1 | 30-40 | 25-35 | 45-65 | 30-40 | 160-210 |
| 5 | 55-75 | 50-70 | 80-110 | 55-75 | 290-400 |
| 10 | 100-140 | 90-120 | 140-180 | 100-130 | 530-700 |
| 15 | 160-220 | 150-200 | 220-280 | 150-200 | 830-1,100 |
| 18 | 220-300 | 200-280 | 280-360 | 200-260 | 1,120-1,500 |

### Monster-Side Expected HP Pool (vs same-level 5-person party)

| Encounter Difficulty | Total HP | TTK Turns | Note |
|:--:|:--:|:--:|------|
| Easy | Party DPR × 1.5 | 1-2 turns | Mook cleanup |
| Standard | Party DPR × 3 | 2-3 turns | Normal fight |
| Hard | Party DPR × 5 | 3-4 turns | Resource war |
| Boss | Party DPR × 8 | 5-7 turns | Includes phase transitions |

### Monster Damage Baseline (vs same-level tank, AR≈120)

| Level | Mook AD | Elite AD | Boss AD | Tank Damage Taken/turn |
|:--:|:--:|:--:|:--:|:--:|
| 1-5 | 30-50 | 50-70 | 70-90 | 20-40 |
| 6-10 | 50-80 | 70-100 | 100-130 | 35-60 |
| 11-16 | 80-110 | 100-140 | 140-180 | 50-80 |
| 17-20 | 110-150 | 140-180 | 180-250 | 65-100 |

> **How to use**: When designing an encounter, first compute Party DPR × expected turns = monster total HP pool, then distribute across monsters. Monster AD should make the tank take roughly 5-10% of its HP per turn.

---

> **Companion files**: Player Rulebook `英雄聯盟TRPG_玩家規則書.md`, Campaign Script Collection `adventures_campaign_v0.2.md`, Enemy Stat Database `怪物圖鑑.md`

---

# Solo Rules Supplement (GM / Host Only)

# League of Legends TRPG — Solo / Duet Rules Supplement v0.2

> This document is the 1-player + 1-host (Duet) dedicated rules expansion for *League of Legends TRPG*.
> Must be used together with the main rulebook `LOL_TRPG_Rulebook_v0.2.md`.
> All referenced section numbers (e.g., §1.7) correspond to sections in the main rulebook.

---

## I. Applicability Analysis

### Three Fatal Problems of the Existing Rules in Solo Mode

| Problem | 5-Player Party | Solo | Consequence |
|------|:--:|:--:|------|
| Action economy | 5 standard actions/turn | 1 standard action/turn | DPS drops to 1/5, combat lengthens 5× |
| Boss HP pool | Designed for 5-player DPR × 3 turns | Same pool vs 1 player | Lv.5 Boss 800 HP, solo needs 13 turns to kill, dies mid-fight |
| Character coverage | Tank+Carry+Heal+Control+Ranged | Single character | No heal = no sustain, no tank = instant death, no ranged = kited |

> Conclusion: **Not suitable**. Below are three layers of correction — baseline rule changes, Companion System, encounter scaling formula.

---

## II. Baseline Rule Changes

### 2.1 Elite Actions

A solo player has **2 standard actions per turn** (original rule §3.2 has 1).

| Action Type | 5-Player Rule (§3.2) | Solo Rule |
|----------|:--:|:--:|
| Standard action | 1 | **2** |
| Move action | 1 | 1 (may downgrade 1 standard action to a move) |
| Bonus action | 1 | **2** |
| Reaction | 1/turn | 1/turn |

> Design rationale: 2 standard actions let a solo player attack+heal or dash+output simultaneously, mimicking a duo party's rhythm without ballooning to 5-player scale.

### 2.2 Rest Adjustments

| Rule | 5-Player Rule (§1.7) | Solo Rule |
|------|------|------|
| Short rest HP recovery | DC10 Constitution → recover HP×10% | DC10 Constitution → recover **HP×25%** |
| Post-long-rest weakness | After revival 3 turns -20% damage | After revival **1 turn** -20% damage |
| Encounter-day budget | Standard 4-6 | **2-4** (each harder but fewer) |

### 2.3 Heroic Tenacity (passive)

A solo player automatically gains the following passive (does not occupy a talent slot):

**Heroic Tenacity**: Once per combat, when HP drops to 0, keep 1 HP, and gain 1 extra standard action next turn.

> Reference: This mechanic resembles the design philosophy of the Resolve talent "Unbreakable Shield" (§2.2), but reframed as a solo survival floor.

---

## III. Companion System

The player may bring **1 companion NPC**. The companion uses simplified rules, controlled by player or GM.

### 3.1 Companion Creation

The companion uses the generic NPC template (reference: `gm_toolkit_v0.2.md` Chapter Four enemy AI rules' five templates, or the `NPC_cards_all.xlsx` generic enemy template sheet).

| Step | Note |
|:--:|------|
| 1 | Choose companion type: Assassin / Warrior / Mage / Marksman / Support |
| 2 | Companion level = player level − 2 (minimum Lv.1) |
| 3 | From `NPC_cards_all.xlsx` "Generic Mob Generator", look up HP/AD/AP/AR/MR/AS for the corresponding level |
| 4 | Give the companion 1 simple passive (see table below) |

### 3.2 Companion Passive (choose 1 of 5)

| Passive | Effect |
|------|------|
| **Cover Fire** | Once per turn, companion deals AD×0.3 damage to the player's attacked target (no action cost) |
| **First Aid** | On short rest companion may make DC12 Medicine check; success heals player extra HP×15% |
| **Taunt** | Once per combat, companion forces 1 enemy to attack it for 1 turn (companion takes 30% less damage that turn) |
| **Scout** | Companion passive awareness = 12 + PER modifier; may actively scout traps/hidden doors |
| **Tactical Command** | Player initiative +3 (companion gives tactical advice) |

### 3.3 Companion Action Rules

- Companion acts **after** the player's turn
- Each turn may take **1 move + 1 basic attack** (no skills)
- After companion HP drops to 0 it leaves combat (does not die), recovers after long rest
- Companion cannot use equipment active effects or Summoner Spells
- Companion takes AOE damage normally

### 3.4 Story Companion

At specific story nodes, the GM may have a story NPC join with full stats (reference: any character in `NPC_cards_all.xlsx` with full Q/W/E/R). Story companions use full action rules but are controlled by the GM.

---

## IV. Encounter Scaling Formula

### 4.1 Enemy Count Scaling

When designing a 5-player encounter, enemy count is N. For solo, adjust to:

```
Solo enemy count = max(1, ceil(N × 0.4))
```

| 5-Player Encounter | Solo Encounter |
|:--:|:--:|
| 5 mobs | 2 |
| 8 mobs | 3 |
| 3 elite + 5 mobs | 1 elite + 2 mobs |
| Boss + 3 mobs | Boss + 1 mob |

### 4.2 Boss HP Scaling

For any Boss whose HP is noted in the 5-player rules (reference: Boss data in `adventures_campaign_v0.2.md` and `arcane_dlc_gm_v0.2.md`), apply the following multiplier for solo:

```
Solo Boss HP = original HP × 0.35
```

| Boss | 5-Player HP | Solo HP |
|------|:--:|:--:|
| Forge Master Viktor (Lv.5) | 800 | **280** |
| Ancient Iceborn (Lv.10) | 1,800 | **630** |
| The Forbidden Ascended (Lv.16) | 3,200 | **1,120** |
| Malzahar (Lv.20) | 8,000 | **2,800** |

### 4.3 Boss Phase Simplification

The 5-player Boss's 3 phases become **2 phases** (merge P1+P2):

- **P1 (100%-40% HP)**: Uses original P1 + P2 skills (alternating)
- **P2 (40%-0% HP)**: Uses original P3 skills

Reference: Original Boss phase rules in main rulebook §3.13.

### 4.4 Encounter Difficulty Budget (Solo Version)

Reference GM Toolkit `gm_toolkit_v0.2.md` Chapter Twelve DPR baseline table. Solo adaptation below:

| Difficulty | Total Enemy HP (vs solo player + companion) | Note |
|:--:|:--:|------|
| Easy | Player DPR × 2 | Mook cleanup |
| Standard | Player DPR × 4 | Normal challenge |
| Hard | Player DPR × 6 | Resource war |
| Boss | Player DPR × 10 | Includes phase transitions |

---

## V. Character Creation Suggestions

### 5.1 Recommended Archetypes

| Priority | Archetype | Reason |
|:--:|:--:|------|
| ⭐⭐⭐ | **Warrior** | Built-in sustain (Bloodthirster Berserker template) + mid tankiness, most well-rounded solo |
| ⭐⭐⭐ | **Mage** | Time Manipulator template gives dash + self-defense, fast AOE clear |
| ⭐⭐ | Marksman | Needs companion (tank type) on frontline, else hard to output |
| ⭐⭐ | Assassin | High burst but low sustain, needs frequent short rests |
| ⭐ | Support | Not recommended — too low output, pure support cannot clear alone |

### 5.2 Recommended Talents

| Archetype | Recommended Primary Tree | Reason |
|------|------|------|
| Warrior | Precision (Conqueror) | 8% damage to healing → self-sufficient |
| Mage | Sorcery (Arcane Mastery) | +15% skill damage + cooldown -1 → maximize output |
| Marksman | Precision (Lethal Tempo) | AS stacks → maximize solo DPS |
| Assassin | Domination (Electrocute) | 3 hits trigger extra damage → quick execute |

> Reference: Talent system detailed in main rulebook §2.2.

### 5.3 Recommended Companion Combinations

| Player Archetype | Best Companion | Reason |
|------|:--:|------|
| Warrior | Marksman / Mage | Supplement ranged output |
| Mage | Warrior (Taunt) | Frontline draws fire |
| Marksman | Warrior (Taunt) | Must have frontline |
| Assassin | Support (First Aid) | Supplement sustain |

---

## VI. Quick Start Checklist

```
□ Player uses Elite Actions rule (2 standard actions/turn)
□ Choose 1 companion (template + passive)
□ All encounters: enemy count × 0.4
□ Boss HP: original × 0.35
□ Boss phases: 3 merged into 2
□ Short rest recovery: HP×25% (was 10%)
□ Confirm recommended archetype and talent combo
```

---

> **Companion files**: Main Rulebook `LOL_TRPG_Rulebook_v0.2.md`, GM Toolkit `gm_toolkit_v0.2.md`, Campaign Script Collection `adventures_campaign_v0.2.md`, Solo Scenario Supplement `solo_adventures_v0.2.md`

---

# Arcane DLC — GM Handbook

# League of Legends TRPG — Arcane DLC (GM Handbook) v0.2
> This document contains GM-only content for the Arcane DLC. See the Player Handbook.
> ⚠️ Contains spoilers below — do not let players read this.

---

## Table of Contents

- I. Villains & Original Character Stats
- II. Arcane Campaign Scripts
- III. Arcane Dungeons & Fields

---

## I. Villains & Original Character Stats

### Faction: Villains

#### Sevika (Lv.8 Warrior / Silco's Lieutenant)

| Attribute | Value |
|------|:--:|
| HP 680 | AD 70 | AP 0 | AR 50 | MR 35 | AS 0.75 |
| **Passive: Shimmer Enhancement** | Once per combat, use Shimmer with no side effects + effect duration extended 1 turn |
| **Q - Mechanical Arm Strike** | 【Lock-On Target】 AD×1.3 + Slow -2 (cooldown 2) |
| **R - Shimmer Frenzy** | 【Auto-Hit】 3 turns AD+30%, AS+50%, CC-immune, then Stun 1 turn after (cooldown 8) |

---

#### Singed (Lv.14 Mage / Mad Alchemist)

| Attribute | Value |
|------|:--:|
| HP 900 | AD 50 | AP 95 | AR 55 | MR 70 | AS 0.60 |
| **Passive: Poison Trail** | Leaves a poison fog along path when moving (lasts 2 turns); those who step in take AP×0.3 poison/turn + Slow -1 |
| **Q - Poison Toss** | 【Area Check】 3-sq 1-sq poison fog 3 turns, AP×0.5 poison/turn, stackable (cooldown 2) |
| **W - Mega Adhesive** | 【Area Check】 3-sq 2-sq adhesive 2 turns, those who step in Immobilize + Slow -3 (cooldown 6) |
| **R - Chemical Elixir** | 【Auto-Hit】 4 turns AP+30%, Move Speed+3, heal AP×0.3 HP/turn, immune to slow during (cooldown 10) |

---

### Faction: Arcane Original Characters

#### Silco (Lv.12 Support / Zaun Underground Leader) ⚠️ Arcane Original

| Attribute | Value |
|------|:--:|
| HP 650 | AD 45 | AP 80 | AR 35 | MR 45 | AS 0.65 |
| **Passive: Silver-Tongued Leader** | Auto Advantage on Persuasion checks in Zaun Undercity; all Zaun gang members within 3 sq +2 hit, +10% damage |
| **Q - Shimmer Injection** | 【Lock-On Target】 Inject Shimmer into 1 ally within 2 sq (no side effects, effect 2 turns, AD/AS+30%) (cooldown 3) |
| **W - Shadow Network** | 【Auto-Hit】 Reveal all enemy positions within 6 sq for 2 turns; may plant 1 "Informant" at any location (stealthed unit, vision 4 sq, permanent until discovered) (cooldown 5) |
| **R - Final Speech** | 【Auto-Hit】 All allies gain Advantage on hits and +20% damage for next 2 turns; all enemies must make DC16 Charisma save, failure means cannot act next turn (cooldown 10) |

| Character Role | Can serve as: ultimate social Boss, grey ally, or tragic villain |
|------|------|
| **Bond Route** | Lv.1-3: Undercity informant → Lv.4-6: Zaun revolution financier → Lv.7-9: replace or cooperate — choice moment |
| **Story Death** | Dies by default in Script B (killed by Jinx). GM may choose to let players save him, opening a "Zaun Independence" parallel line |

---

#### Mel Medarda (Lv.9 Mage / Piltover Councilor) ⚠️ Arcane Original

| Attribute | Value |
|------|:--:|
| HP 480 | AD 30 | AP 65 | AR 20 | MR 35 | AS 0.60 |
| **Passive: Political Intuition** | In social scenes can detect lies (DC +5); has 2 inherent council votes (self + swing councilors she can influence) |
| **Q - Light Shield** | 【Auto-Hit】 Grant 1 ally within 3 sq AP×0.8 shield + reflect next single-target skill received (cooldown 4) |
| **W - Radiance** | 【Area Check】 3-sq radius blooms light — enemies inside Blinded 1 turn (basic attacks auto-miss) + reveal stealthed units (cooldown 6) |
| **R - Blood of Solari** | 【Auto-Hit】 Passive trigger — at HP < 20% auto-release light explosion (3-sq AP×2.0 + self heal 50% HP); once per combat |

| Character Role | Key swing vote on the council; hidden magic bloodline (Noxus Solari family) |
|------|------|
| **Bond Route** | Lv.1-3: Patron → Lv.4-6: Political ally → Lv.7-9: Reveal her magic secret → Lv.10: Joint stand against Ambessa |

---

#### Ambessa Medarda (Lv.16 Warrior / Noxus Warlord) ⚠️ Arcane Original

| Attribute | Value |
|------|:--:|
| HP 1,400 | AD 110 | AP 20 | AR 90 | MR 60 | AS 0.80 |
| **Passive: Blood of Noxus** | Below 50% HP damage +25%, damage reduction +15%; on killing enemy recover 20% max HP |
| **Q - Warlord Cleave** | 【Lock-On Target】 AD×1.6 + Bleed (3 turns, AD×0.2/turn) (cooldown 2) |
| **W - Tactical Command** | 【Auto-Hit】 Whole party +2 Move next turn + basic attacks deal extra AD×0.3 (cooldown 5) |
| **R - Descent of Noxus** | 【Area Check】 Leap 4 sq, land AD×2.5 (2-sq AOE) + enemies -25% damage for 2 turns (cooldown 8) |

| Character Role | Hidden mastermind of Script C — attempts to use Hextech to build super-soldiers for Noxus |
|------|------|
| **Bond Route** | Cannot bond (hostile). After defeat may choose: execute / imprison / exile to Noxus (affects later plot) |

---

#### Marcus (Lv.6 Marksman / Piltover Sheriff) ⚠️ Arcane Original

| Attribute | Value |
|------|:--:|
| HP 380 | AD 50 | AP 0 | AR 25 | MR 20 | AS 0.70 |
| **Passive: Corrupt Enforcer** | Can be bribed (500 gold → ignore 1 player illegal act); after exposed all social checks Disadvantage |
| **Q - Enforcement Shot** | 【Directed Projectile】 3 sq AD×0.9 + mark (allies +2 hit vs marked target) (cooldown 2) |
| **W - Call Reinforcements** | 【Auto-Hit】 Summon 2 guards (HP 200, AD 30) into combat (cooldown 6) |

| Character Role | Grey NPC — fallen sheriff blackmailed by Silco. May choose: expose him / use him / sympathize with him |
|------|------|

---

#### Deckard (Lv.5 Warrior / Shimmer Convert) ⚠️ Arcane Original

| Attribute | Value |
|------|:--:|
| HP 450 | AD 55 | AP 0 | AR 30 | MR 20 | AS 0.75 |
| **Passive: Shimmer Dependency** | Permanent 4 stacks Shimmer Dependency (Disadvantage on Constitution checks). After kill may scavenge 1 Shimmer Injector |
| **Q - Frenzied Strike** | 【Lock-On Target】 AD×1.4 (deals AD×0.1 self-damage — Shimmer side effect) (cooldown 2) |
| **R - Shimmer Mutation** | 【Auto-Hit】 Trigger mutation at HP < 25%: size +50%, HP+200, AD+20 (until end of combat) (once per combat) |

| Character Role | Tragic thug under Silco — victim of Shimmer. Low-tier Boss or redeemable NPC |
|------|------|

---

#### Sky (Lv.3 Support / Jayce's Assistant) ⚠️ Arcane Original

| Attribute | Value |
|------|:--:|
| HP 300 | AD 20 | AP 35 | AR 15 | MR 20 | AS 0.55 |
| **Passive: Research Assistant** | DC -5 on Hextech-related Lore checks; may assist Jayce with Hextech forging (cost halved) |
| **Q - Emergency Heal** | 【Auto-Hit】 2-sq ally heals AP×0.6 HP + removes 1 debuff (cooldown 3) |

| Character Role | Pure good NPC — Viktor's secret crush. Her survival/death directly affects Viktor's story route |
|------|------|

---

#### Filo Janna (Lv.8 Support / Firelight Lieutenant) ⚠️ Arcane Original

| Attribute | Value |
|------|:--:|
| HP 420 | AD 35 | AP 45 | AR 25 | MR 30 | AS 0.65 |
| **Passive: Firework Logistics** | At start of each combat, whole party gains 1 small healing pack (use: heal 50 HP) |
| **Q - Cover Fire** | 【Directed Projectile】 3 sq AD×0.6 + mark enemy (next turn +3 hit vs it) (cooldown 2) |
| **R - Firework Signal** | 【Auto-Hit】 Call Firelight hoverboard patrol — 2 Firelight members + Ekko (Lv.8) join combat for 3 turns (once per chapter) |

| Character Role | Ekko's right hand. May develop a bond to unlock special Firelight tree functions |
|------|------|

---

---

## V. Arcane Campaign Scripts

### Script A: Shadows of the Twin Cities (Lv.1-6 · Piltover & Zaun)

> Main-line script. Players step in as a third party in the Piltover-Zaun conflict.

| Chapter | Level | Scene | Core Encounter |
|:--:|:--:|------|------|
| A1 | Lv.1-2 | Zaun Undercity | Street survival, gang probing, meet Ekko |
| A2 | Lv.3 | Piltover Academy | Infiltrate Hextech lab, meet Jayce & Viktor |
| A3 | Lv.4 | The Last Drop | Negotiate/fight Sevika, gain Shimmer intel |
| A4 | Lv.5 | Singed's Laboratory | Dungeon exploration + Boss fight "Singed" (Lv.14 template weakened to Lv.9: HP 500, AP 60) |
| A5 | Lv.6 | Council Hall | Report truth to council — choice moment: support Piltover / Zaun / stand alone |

---

### Script B: Sisters (Lv.7-12 · Zaun & Piltover Border)

| Chapter | Level | Scene | Core Encounter |
|:--:|:--:|------|------|
| B1 | Lv.7-8 | Border Slums | Search for Vi's trail, fight Zaun gangs |
| B2 | Lv.9 | Stillwater Prison | Prison infiltration/riot + fight alongside Vi |
| B3 | Lv.10 | Firelight Tree | Defend Ekko's refuge: repel Sevika's assault |
| B4 | Lv.11 | Hextech Tower | Stop Jinx's second rocket attack — Boss fight "Jinx" + emotional choice with Vi |
| B5 | Lv.12 | Council Ruins | Social finale deciding the Twin Cities' fate: war or peace? |

---

### Script C: Glorious Evolution (Lv.13-18 · Deep Zaun)

| Chapter | Level | Scene | Core Encounter |
|:--:|:--:|------|------|
| C1 | Lv.13-14 | Viktor's Sanctuary | Discover Viktor's Glorious Evolution plan has gone out of control |
| C2 | Lv.15 | Mech Graveyard | Fight the runaway machine legion; reveal Singed's involvement in the mechanized soldier program |
| C3 | Lv.16-17 | Singed's Ultimate Laboratory | Boss "Complete Singed" (Lv.14→Lv.17: HP 1,800, AP 130) + biochemical behemoth |
| C4 | Lv.18 | Hextech Core Tower | Final Boss "Glorious Viktor" (HP 2,500, AP 160, fully mechanized — physical damage halved) |

#### Epic Endings (after C4)

| Ending | Condition | Consequence |
|------|------|------|
| **Tech Peace** | Defeat Viktor but preserve his core + council votes pass Twin Cities equality act | Piltover and Zaun reconcile; Hextech opened to share |
| **Glorious Sacrifice** | Viktor self-destructs core to stop Singed's bioweapon | Piltover and Zaun barely coexist; Viktor remembered as a hero |
| **Total War** | Defeat Viktor + council vote fails | Twin Cities enter prolonged civil war; opens new campaign line |

---

### Script D: Shimmer Dungeon (Side Line · Lv.4-8)

> Short script. Pure Zaun dungeon exploration — Singed's underground lab complex.

| Floor | Theme | Boss | Reward |
|:--:|------|------|------|
| B1 | Abandoned Warehouse | Shimmer Addict ×5 | Shimmer Injector ×3 |
| B2 | Ventilation Maze | Mutant Rat Swarm (HP 200, AD 30) | Hextech Belt |
| B3 | Bioculture Chamber | Biochemical Behemoth (HP 800, AD 70, heal 15 HP/turn) | Shimmer Tolerance Augment |
| B4 | Singed's Office | Singed (HP 600, AP 70) | Silco's Legacy Augment |

---

## VI. Arcane Dungeons & Fields

### 6.1 Stillwater Prison

#### Environment Rules

| Rule | Effect |
|------|------|
| Anti-Magic Stone Walls | All spells AP -30%; teleport spells cannot cross outer prison walls |
| Cell Block | Each cell holds 1-2, DC20 Athletics/Thieves' Tools to unlock |
| Guard Patrol | Every 3 turns 2 guards patrol a random area (DC15 Stealth to avoid) |
| Riot State | If alarm triggered: whole prison riots — all prisoners released, guard reinforcements +3 every 2 turns |
| Escape Tunnel | DC18 Perception may discover hidden escape tunnel (leading to Zaun Undercity) |

#### Prison NPCs

| NPC | Role | Special |
|------|------|------|
| Warden | Boss (Lv.10 Warrior) | All prison guards under his command gain Advantage |
| Old Prisoner | Intel source | Knows all secret passages; needs 500 gold or DC18 Persuasion |
| Young Guard | Can be bribed | 500 gold → open 1 area; sympathetic to prisoners |

---

### 6.2 Firelight Tree

Ekko and the Firelights' refuge — the only place in Zaun Undercity with sunlight and green plants.

#### Field Effects

| Rule | Effect |
|------|------|
| Tree of Life | At start of each turn, all allies within 3 sq of tree heal 10+LV×2 HP |
| Sunlight Rift | The only natural light pillar piercing Zaun's poison fog — light skills +20% effect |
| Mural Wall | Firelights' history murals (DC15 Lore to decode, gain hidden plot clue) |
| Anti-Air Net | Firelight hoverboard patrol flies by every 3 turns — may call support (1/chapter, 2 Firelight members join combat) |

---

### 6.3 Hextech Tower

Jayce and Viktor's lab — Piltover's tallest building.

#### Dungeon Structure (5 floors)

| Floor | Content | Guard |
|:--:|------|------|
| 1F Lobby | Reception + showroom | 2 Academy Guards (HP 300, AD 40) |
| 2F Laboratory | Hextech gem research zone | Viktor's Mechanical Assistants ×3 (HP 200, AD 25) |
| 3F Library | Ancient rune literature | DC20 Lore to learn 1 random Mage skill variant |
| 4F Jayce's Office | Hextech core prototype | DC18 Stealth to avoid Jayce; or DC20 Persuasion to persuade him to cooperate |
| 5F Tower Top | Hextech portal lab | Portal can reach any known Piltover/Zaun location (costs 1 Hextech gem) |

---

### 6.4 The Last Drop

Silco's former base, now controlled by Sevika.

#### Social Scene

| Activity | DC / Cost | Result |
|------|:--:|------|
| Gather Intel | DC12 Persuasion | Random 1 Zaun underground intel |
| Recruit Helper | DC16 Persuasion + 500 gold | 1 Zaun gang member joins next fight |
| Buy Shimmer | 150 gold each | Gain Shimmer Injector |
| Provoke Sevika | DC20 Intimidate | Trigger fight with Sevika |
| Underground Gambling | 100 gold stake | d20: 1-10 lose, 11-18 win 200 gold, 19-20 win 500 gold |

---

> **Companion files**: Main Rulebook `LOL_TRPG_Rulebook_v0.2.md`, GM Toolkit `gm_toolkit_v0.2.md`, Campaign Script Collection `adventures_campaign_v0.2.md`

> **Companion files**: Main Rulebook , GM Toolkit , Player Handbook