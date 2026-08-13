# Urban Survivors — GM Rulebook

> **Version:** v1.2
> **Design Studio:** Tabletop Rule Studio
> **Audience:** Game Master (GM)
> **Players:** 1 player + 1 GM (multiplayer optionally supported)

---

# About This Book

This GM Rulebook contains **all the rules of Urban Survivors**—from the player's basic rules, to behind-the-scenes mechanics, enemy data, worldbuilding, scenario framework, and GM techniques. **You only need to read this one book to run the game.**

---

# Part One: Core Rules (Shared by Players and GM)

> This section is identical to the Player Rulebook. Whether you are a player or the GM, these are the fundamental mechanics of the game.

## Chapter 1: The Dice System — 3d6 Bell Curve

Urban Survivors uses a **3d6 + attribute value** check system. Roll three six-sided dice, take the sum, add the attribute value, and compare it to the Difficulty Class (DC).

**Design Philosophy:** Three dice form a bell curve—results cluster toward the center, with extreme values (3 or 18) each occurring only 0.46% of the time. This models the steady competence of ordinary people, rather than heroic randomness.

## Chapter 2: The Five Attributes and Derived Attributes

### The Five Attributes (range 0–5, 20 points to distribute)

| Attribute | Full Name | Meaning |
|-----------|-----------|---------|
| **Physique (PHY)** | Physique (body) | Physical health and stamina |
| **Agility (AGI)** | Agility (dexterity) | Alertness, speed, and nimbleness |
| **Willpower (WIL)** | Willpower (will) | Mental resilience and psychological endurance |
| **Social (SOC)** | Social (social) | Ability to communicate and build trust |
| **Craft (CRA)** | Craft (craft) | Practical skill and adaptability |

The attribute value is the modifier (no conversion needed). Physique 4 means roll 3d6+4.

### Derived Attributes

| Derived Attribute | Formula | Notes |
|-------------------|---------|-------|
| **Stamina** | Physique × 2 + 5 | Daily action-point cap. Reaching zero → unable to act |
| **Satiety** | 0–10 (starts at 7) | <3 → Disadvantage on Physique checks |
| **Warmth** | 0–10 (starts by season) | <3 → −1 Physique per day |
| **Mental State** | Willpower × 2 | Reaching zero → Breakdown State |
| **Stealth** | Agility + environmental cover | The DC for enemy detection |

## Chapter 3: Check Rules

### Difficulty Class (DC) Ladder

| DC | Difficulty | Typical Situation | Success Rate at +2 |
|----|-----------|-------------------|--------------------|
| 6 | Trivial | Finding an obvious can | ~99% |
| 8 | Simple | Sealing a small window | ~95% |
| 10 | Ordinary | Persuading a friendly neighbor | ~84% |
| 12 | Challenging | Staying quiet on patrol | ~62% |
| 14 | Hard | Crossing a sniper's field of view | ~37% |
| 16 | Severe | Leading an evacuation under shelling | ~16% |
| 18 | Extreme | Moving a concrete beam | ~5% |
| 20 | Nearly Impossible | Carrying someone 5 km after 3 days starving | ~0.5% |

### Check Result Tiers

| Result | Condition | Narrative Meaning |
|--------|-----------|-------------------|
| **Critical Failure** | Natural roll ≤ 4 | Situation clearly worsens |
| **Failure** | Total ≤ DC−3 | Normal consequence |
| **Costly Success** | Total = DC−2 or DC−1 | Succeeds, but at a cost |
| **Success** | Total ≥ DC | Completed as expected |
| **Critical Success** | Natural roll ≥ 17 | Exceptional success |

> **GM Tip:** The Costly Success is the core source of tension in this game. Don't let the cost become a pure punishment—let it become a turning point that drives the story. The door opens but makes a sound (drawing attention); you persuaded them but they demand a favor (a debt for later); you found the can but cut your finger (infection risk).

### Contest Check

Both sides roll `3d6 + attribute value`; the higher wins. On a tie, the initiating side succeeds at a Costly Success.

### Group Check

If more than half succeed → overall success. If only one fails → one of the successes covers for them (extra check, costs Stamina).

## Chapter 4: The Advantage & Disadvantage System

| State | Rolling Method |
|-------|----------------|
| **Advantage** | 4d6 keep highest three |
| **Normal** | 3d6 |
| **Disadvantage** | 4d6 keep lowest three |

**Triggering Advantage:** Profession talent, thorough preparation (costs 2 Stamina), companion assistance (assistant costs 1 Stamina), high-quality tools, Fate Point.

**Triggering Disadvantage:** Hunger (Satiety <3), cold (Warmth <3), injury, fear state, acting in darkness.

Do not stack. If both exist → they cancel out.

### Mathematical Impact of Advantage/Disadvantage (attribute +2, DC 12)

| Mode | Success Rate |
|------|--------------|
| Disadvantage | ~22% |
| Normal | ~62% |
| Advantage | ~89% |

## Chapter 5: Rest and Recovery

### Types of Rest

| Rest Type | Stamina Recovery | Other Effects |
|-----------|------------------|---------------|
| **Short Rest** (1–2h) | +(Physique + 2) | Removes 1 level of Exhaustion |
| **Long Rest / Sleep** (6–8h, needs safe environment) | Full | Mental State +Willpower value (DC 10); Trauma −1 (Sealing ≥ 3) |
| **Full Rest Day** (no going out) | Full | Mental State +2; removes all Exhaustion; Wounds advance 1 day |

### Exhaustion State

| Level | Effect | Removal |
|-------|--------|---------|
| Level 1 | Physique −1 | Short Rest |
| Level 2 | Physique, Agility −2 | Long Rest |
| Level 3 | All −3, movement halved | Full Rest Day |

### Morale

| State | Trigger | Effect |
|-------|---------|--------|
| Inspired | Artistic performance, good news | Willpower +1 until next rest |
| Normal | Daily life | — |
| Low | Consecutive failures, death | Social −1 |

> **GM Tip:** Morale is a flexible narrative tool—players don't need to track a number. When the story turns dark, naturally let morale drop. When players perform brave or moving acts, grant Inspired.

## Chapter 6: Fate Point System

Each player starts with **3 points** (max 5). Can be used for: reroll (after rolling), gaining Advantage (before rolling), negating a cost. Recover 1 point per completed scenario chapter; recover 1 point upon a major moral sacrifice.

---

# Part Two: Character Creation (GM Guidance)

## Chapter 7: The Pre-war Profession System

Your players are not heroes—they are ordinary people. The 12 Pre-war Professions define who they were before the siege.

### Profession List and GM Tips

| # | Profession | Core Strength | GM Tip |
|---|------------|---------------|--------|
| 1 | Teacher | Soothing, teaching | Give them NPCs who need comforting; the people they persuade aren't always enemies |
| 2 | Medic | Medical | The most precious role under siege—give them moral dilemmas (one dose of medicine, two wounded) |
| 3 | Baker/Chef | Food handling | Key role in converting supplies; when food is short, their skill decides life and death |
| 4 | Plumber/Mechanic | Repair | Give them things to fix—radios, generators, broken windows |
| 5 | Vendor/Peddler | Bargaining | The black market is their stage; let them use their trading instincts |
| 6 | Journalist/Writer | Observation, recording | Their records can become key in-game items |
| 7 | Student | Quick learning | Potential type—give them opportunities to grow and reasons to be protected |
| 8 | Veteran ⚠️ | Tactics | Restrict use—at most 1 per group; their PTSD is a story engine |
| 9 | Social Worker/Chaplain | Spiritual pillar | Give them NPCs who need comfort; they are the team's spiritual pillar |
| 10 | Driver/Deliveryman | Navigation | Indispensable in urban movement scenes |
| 11 | Artist/Musician | Morale | Give them a chance to shine in dark moments—a song may save someone's sanity |
| 12 | Accountant/Civil Servant | Resource management | Resource tracking is their superpower |

### Profession Mechanic: Proficiency +2 + Advantage

Skills granted by a Pre-war Profession: starting proficiency is +2, and using that skill grants **Advantage** (4d6 keep highest three). This makes profession skills significantly more reliable than ordinary skills.

## Chapter 8: The 20 Skills and Attribute Mapping

### Physique Skills
- **Endurance**: prolonged labor, forced marching, carrying heavy loads
- **Might**: lifting heavy objects, prying open doors/windows, close-quarters strength contests
- **Resilience**: resisting disease and toxins, enduring pain

### Agility Skills
- **Stealth**: moving silently, avoiding sightlines
- **Climbing**: scaling walls, traversing ruins
- **Driving**: operating vehicles, evading pursuit
- **Search**: scavenging supplies, finding hidden items
- **Sleight of Hand**: fine manipulation, theft, lockpicking

### Willpower Skills
- **Composure**: staying calm, resisting fear
- **Vigilance**: sensing danger, noticing something wrong
- **Perseverance**: holding on in extreme environments
- **Memory**: remembering routes, faces, passwords

### Social Skills
- **Persuasion**: changing attitudes, gaining trust
- **Deception**: lying, disguising identity
- **Soothing**: easing fear, defusing conflict
- **Bargaining**: bartering, judging value
- **Read Intent**: judging intentions, sensing lies

### Craft Skills
- **Repair**: fixing items, emergency patches
- **First Aid**: treating wounds, stopping bleeding, splinting fractures
- **Cooking**: preparing food, maximizing nutrition
- **Pharmacology**: identifying drugs, compounding remedies
- **Electrical**: handling power systems, wiring

### Proficiency Ladder

| Tier | Bonus | Effect |
|------|-------|--------|
| Untrained (0) | +0 | May attempt |
| Novice (1) | +1 | Basic understanding |
| Proficient (2) | +2 | Reliable level |
| Seasoned (3) | +3 | Experienced |
| Expert (4) | +3 + Advantage | Authority in the field |
| Master (5) | +3 + Advantage + DC−1 | Legendary |

Skill check formula: `3d6 + attribute value + proficiency bonus` (4d6 keep highest three when a profession override applies)

### GM Tip: Cross-Attribute Skill Use

Allow players to use skills with non-default attributes:
- Climbing (Physique)—prolonged climbing tests Endurance
- First Aid (Willpower)—first aid under fire tests Composure
- Persuasion (Willpower)—persuading others with firm conviction

This ensures a solo character's skill set can flexibly handle varied situations.

## Chapter 9: Nine-Step Character Creation (GM Guidance)

As the GM, guide players through these nine steps. Each step is a combination of **narrative + mechanics**—don't let character creation become a form-filling exercise.

1. **Who are you?** → name, age, Pre-war Profession
2. **Where are you trapped?** → location at the start of the siege and who is with you
3. **Attribute allocation** → distribute 20 points (0–5); each attribute ≥3 grants one Novice skill
4. **Free skills** → choose 2 Novice skills
5. **Shelter** → distribute 3 points among Structure/Sealing/Comfort
6. **The one you lost** → a specific person, a specific way of losing them, the last goodbye
7. **Protected One** → an item or a person—this will be the core driving force of the game
8. **Personal Belongings** → no more than Carrying Capacity slots
9. **Final polish** → personality traits, habits, secrets

### Special GM Notes

- **Steps 6 and 7 are the most important**—they define the character's emotional core
- Have players describe "the loss" in detail—don't let it become a simple "they died"
- The "Protected One" will be your most important story tool as GM—protect it, threaten it, make players make hard choices for it

---

# Part Three: Survival and Conflict Systems (Complete Rules)

## Chapter 10: Stealth and Infiltration (GM Perspective)

### Stealth Calculation

```
Player Stealth = Agility + environmental cover bonus + dynamic modifier
```

| Environment | Cover Bonus |
|-------------|-------------|
| Open ground | −3 |
| Sparse cover | +0 |
| Moderate cover (ruins, behind vehicles) | +3 |
| Good cover (basement, dark alley) | +5 |
| Full Concealment (underground passages, behind disguise) | +8 |

| Dynamic Factor | Modifier |
|----------------|----------|
| Still | +2 |
| Slow movement | +0 |
| Normal movement | −2 |
| Running | −5 |
| Dark clothing | +1 |
| Minor Wound | −1 |
| Serious Wound | −3 |

### Enemy Detection Mechanic

```
Enemy detection check = 3d6 + enemy Awareness vs. Player Stealth
```

**Detection Results:**

| Check Result vs. Stealth | Effect |
|--------------------------|--------|
| Below by 5+ | Completely unnoticed |
| Below by 1–4 | Slightly suspicious—Awareness +1 next turn |
| Equal or exceeds | Spots anomaly—enters alert state, gains Advantage next turn |
| Exceeds by 5+ | Clearly detected—acts immediately (calls support, opens fire, gives chase) |

**Enemy Alert States:**

| State | Awareness Modifier |
|-------|--------------------|
| Routine patrol | −2 |
| Alert | ±0 |
| Manhunt | +3, detection Advantage |

### Noise System (GM Tool)

| Noise Level | Propagation Distance | Typical Action |
|-------------|----------------------|----------------|
| 0 (Silent) | 0m | Holding breath, gestures |
| 1 (Very Low) | 5m | Crawling, whispering |
| 2 (Low) | 15m | Walking slowly, soft voice, opening a door |
| 3 (Medium) | 30m | Fast walking, conversation, lockpicking |
| 4 (High) | 60m | Running, broken glass, battering a door |
| 5 (Very High) | 150m | Gunshot, explosion, scream |
| 6 (Deafening) | 500m+ | Artillery shelling, sustained gunfight |

**Noise Propagation Rules:**
- Each thick wall: distance halved
- Each closed door: distance −25%
- Open building/tunnel: distance ×1.5
- Background noise (shelling/heavy rain): all noise levels −1

**Noise Consequences:**
- Enemy within noise range → detection check (+2)
- Noise level ≥5 → automatically enters Manhunt state + may call Reinforcement

### Light and Line of Sight

| Light | Detection Impact | Stealth Impact |
|-------|------------------|----------------|
| Bright | Normal | Normal |
| Dim | Detection Disadvantage | Stealth +2 |
| Dark | Detection Disadvantage, vision halved | Stealth +5 |
| Pitch Black | No visual detection | Silent = automatically concealed |

> **GM Reminder:** Remind players—any light source is a lighthouse. A handheld flashlight lets you see 20 meters, but also lets enemies see you from 200 meters away.

### Group Stealth

```
Group Stealth = lowest Stealth value − (group size − 1)
```

| Group Size | Penalty |
|------------|---------|
| 1 | −0 |
| 2 | −1 |
| 3 | −2 |
| 4–5 | −3 |
| 6+ | −5 (automatically makes noise) |

### GM Stealth Scene Design

Offer players multiple path choices:
- Mark patrol routes so players can observe and plan
- Always provide at least one detour option (even at higher cost)
- Embed different risk/reward combinations in different paths

---

## Chapter 11: Fleeing and Chases (Complete Rules)

### Chase Trigger

Enemy detection check exceeds Player Stealth by 5+ → chase begins.

**Initiative:** All participants roll `3d6 + Agility`, acting from highest to lowest.

### Distance Band System

| Distance Band | Range | Effect |
|---------------|-------|--------|
| Close | 0–10m | Enemy can melee attack. Cannot hide |
| Medium | 11–30m | Can shoot. Hiding at Disadvantage |
| Far | 31–60m | Can shoot. Can hide |
| Disengaged | 61–100m | Enemy shoots at Disadvantage. Normal hiding |
| Escaped | 100m+ | Can re-establish concealment |

### Player Action Options

| Action | Check | Success | Failure |
|--------|-------|---------|---------|
| Full sprint | Physique DC 10 | +2 bands | +1 band + Exhaustion |
| Nimble weaving | Agility DC 12 | +1 band + pursuer Disadvantage | No change |
| Use obstacle | Agility DC 10 | +2 bands | −1 band |
| Hide | Agility DC 14 | At Far range or beyond: enter hiding | −1 band |

### Pursuer Behavior (GM-controlled)

| Type | Per Turn |
|------|----------|
| Infantry/Patrol Soldier | Move 1 band + 1 shot (if in range) |
| Military Dog | Move 2 bands. Ignores obstacles |
| Vehicle | Move 3 bands. Cannot enter narrow alleys |
| Sniper | Does not move. Each shot is a lethal threat |

### Re-establishing Concealment

1. Find a hiding spot: Agility DC 12
2. Stay silent for 3 turns (no noise ≥ level 2)
3. Wait for enemy to give up: 1d6+1 turns (2d6+3 turns in Manhunt state)

---

## Chapter 12: The Desperate Self-Defense System (Complete GM Rules)

> **Core GM Principle:** The rules in this chapter are NOT for players to "fight" with. If players need to use these rules, they are already in extreme danger. Make sure players know this beforehand.

### Wound Tier System (no HP)

This game does not use Hit Points. All damage is tracked through Wound Tiers:

| Civilian takes… | Wound |
|-----------------|-------|
| 1 hit | Minor Wound |
| 2 hits | Serious Wound |
| 3 hits | Fatal Wound |
| Firearm (rifle) | at least Serious Wound |
| Sniper Rifle | at least Fatal Wound, possible instant death |

### Self-Defense Turn Structure (~6 seconds)

1. Declare intent
2. Initiative order (3d6 + Agility)
3. Each character: 1 major action + 1 move action
4. Resolve ongoing effects + noise

### Attack Formula

```
Attack check = 3d6 + Physique (or Agility)
Target DC = Defense Value = 5 + Agility + cover bonus + armor bonus
```

| Defense Factor | Bonus |
|----------------|-------|
| No cover, standing | +0 |
| Half cover (overturned table, behind vehicle) | +3 |
| Full cover (behind thick wall, only eyes showing) | +5 |
| Heavy clothing | +1 |
| Improvised armor (wooden plank) | +1 |
| **Full Defense** (forgo attack, focus on dodging/blocking) | **+5** |

> **GM Reference:** A civilian with no cover (Agility 3) → Defense 8, patrol soldier hits ~84%. The same civilian with full cover + Full Defense → Defense 18, patrol soldier hits ~5%. Let players know the importance of cover.

**Wound Determination:**

| Check vs. Defense Value | Wound |
|-------------------------|-------|
| Just meets | Minor Wound |
| Exceeds by 3–6 | Serious Wound |
| Exceeds by 7+ | Fatal Wound |
| Natural roll ≥17 and meets | Fatal Wound + special effect |

### Simple Weapon Table

| Weapon | Attribute | Damage | Special |
|--------|-----------|--------|---------|
| Unarmed | Physique | Minor Wound | Disadvantage vs. armed |
| Broken glass | Agility | Minor Wound | 50% self-injury |
| Kitchen Knife | Agility | Serious Wound | Noise 2 |
| Pipe/Wooden club | Physique | Serious Wound | Defense +1 |
| Hammer | Physique | Serious Wound | Cannot move simultaneously |
| Rock (thrown) | Agility | Minor Wound | Range 10m |
| Frying pan | Physique | Minor Wound | Defense +1 |

### Firearm Rules

| Type | Hit Effect |
|------|------------|
| Pistol | Minor Wound (graze) ~ Serious Wound (torso hit) |
| Rifle | at least Serious Wound; exceeds DC by 5+ → Fatal Wound |
| Sniper | at least Fatal Wound; exceeds DC → instant death |

### Noise Chain (Key GM Rule)

Resolve noise at the end of each turn:

| Action | Noise | Consequence |
|--------|-------|-------------|
| Melee | Level 3 | Enemies within 30m detection +2 |
| Scream/Shout | Level 4 | Enemies within 60m move toward sound source |
| Gunshot | Level 5–6 | All within 150m enter Manhunt; Reinforcement arrives in d6 turns |

> **Core GM Strategy:** Noise is the true cost of self-defense combat. Let players know that every extra turn they stay, more enemies will pour in. This creates the urgency of "run now."

---

## Chapter 13: Wounds, Infection, and Recovery (Complete Rules)

### Wound Tier Details

| Tier | Immediate Effect | Ongoing Effect | Worsening |
|------|------------------|---------------|-----------|
| **Minor Wound** | Action −1 | Physique DC 8 every 24h (infection risk) | 3 days → Serious Wound |
| **Serious Wound** | Action −3, movement halved, −1 Stamina per hour | Physique DC 12 daily (infection) | 2 days → Fatal Wound |
| **Fatal Wound** | Falls down, −d3 Stamina per 10 min, action needs Willpower DC 16 | Physique DC 16 daily (death risk) | 1 day → death |

### Wound Stacking

3 Minor Wounds = 1 Serious Wound | 2 Serious Wounds = 1 Fatal Wound | Fatal Wound + Fatal Wound = death

### Infection Mechanic

| Wound | Treatment Window | Infection DC | After Infection |
|-------|------------------|--------------|-----------------|
| Minor Wound | 24h | Physique DC 8 | Extra −1, recovery time ×2 |
| Serious Wound | 12h | Physique DC 12 | Fever: −1 Physique daily |
| Fatal Wound | 1h | Physique DC 16 | Sepsis: −2 Physique daily |

### Infection Treatment

| Method | Requirement | Effect |
|--------|-------------|--------|
| Clean water + bandage | Water + cloth | Infection DC −4 |
| Disinfectant alcohol | Alcohol | Infection DC −6, Willpower DC 10 (pain) |
| Antibiotics | 1 dose antibiotics | Auto-heal (below Fatal Wound stage) |
| Amputation | See disability table | Stops infection, permanent disability |

### Medical Treatment Checks

| Treatment | Check | Requirement |
|-----------|-------|-------------|
| Basic bandage | Craft DC 8 | Cloth |
| Suture wound | Craft DC 14 | Needle & thread + alcohol |
| Emergency surgery | Craft DC 16 | Blade + alcohol + light source + 30 minutes |

### Recovery Time

| Wound | Base | With Medical | Best |
|-------|------|--------------|------|
| Minor Wound | 7 days | 5 days | 2 days |
| Serious Wound | 30 days | 21 days | 7 days |
| Fatal Wound | 90 days | 60 days | 21 days |

### Death Rules

**Trigger Conditions (any one):**
1. Stamina reaches zero and cannot be recovered
2. Fatal Wound untreated within 24 hours
3. Sepsis + Physique at zero
4. 4th-tier Wound
5. Directly fatal event (sniper headshot, buried 10+ minutes, trapped in fire)

**Final Moment:** Willpower DC 16 → conscious for d4 minutes to do one last thing; DC 10 → passes away in coma; <10 → passes away in pain.

### Permanent Disability

After surviving a Fatal Wound, roll 3d6 to determine disability:

| 3d6 | Result |
|-----|--------|
| 3–9 | Miracle—no permanent disability (but with visible scars) |
| 10–11 | Minor disability |
| 12–13 | Moderate disability |
| 14–18 | Severe disability |

**Disability Type (d8 determines location):** missing fingers / hearing loss / limp / vision impairment / chronic pain / facial disfigurement / nerve damage / psychological trauma

---

## Chapter 14: Status Effect System

### Hunger (by Satiety)

| Satiety | Stage | Effect |
|---------|-------|--------|
| 7–10 | Sated | +1 Stamina recovery/day |
| 4–6 | Normal | — |
| 2–3 | Hungry | Physique/Agility Disadvantage, Stamina cap −2 |
| 1 | Starving | All checks at Disadvantage, Stamina cap −5 |
| 0 | Famine | −1 Physique daily, cannot recover Stamina |

### Dehydration (by days without water)

| Days | Stage | Effect |
|------|-------|--------|
| 0 | Normal | — |
| 1 | Thirsty | Physique −1, Social −2 |
| 2 | Dehydrated | All −2, Stamina cap −3 |
| 3 | Severe | All Disadvantage, −1 Physique daily |
| 4+ | Organ failure | Physique DC 16 daily, failure → death |

### Hypothermia (by Warmth)

| Warmth | Stage | Effect |
|--------|-------|--------|
| 7–10 | Warm | +1 Mental State recovery/day |
| 4–6 | Normal | — |
| 2–3 | Cold | Agility −2, Stamina consumption ×1.5 |
| 1 | Hypothermic | All −3, cannot perform fine manipulation |
| 0 | Severe | −2 Physique daily, Willpower DC 16 or falls into coma |

### Sleep Deprivation

| Unslept | Stage | Effect |
|---------|-------|--------|
| 24h | Tired | All −1 |
| 48h | Drowsy | All −2 |
| 72h | Extreme | All Disadvantage + hallucinations |
| 96h+ | Collapse | Automatically falls asleep |

### Common Diseases

| Disease | Infection Route | Effect | Treatment |
|---------|-----------------|--------|-----------|
| Dysentery | Contaminated water | Dehydration ×2 faster, Physique −2 | Purified water + 3 days rest or antibiotics |
| Pneumonia | Hypothermia + dampness | −1 Physique daily, cough noise +1 | Warmth + antibiotics |
| Typhus | Lice | High fever: all −3 | Antibiotics otherwise 40% mortality |
| Tetanus | Wound + rust | Agility −4, cannot eat | Antitoxin otherwise 80% mortality |
| Cholera | Polluted water source | −1 water per half-day, −2 Physique daily | Large amounts of purified water + antibiotics |

---

## Chapter 15: Environmental Hazards (GM Reference)

### Artillery Shelling / Air Raid

**Trigger:** Scenario event or daily random (d20: 1–3)

**Three Phases:**
1. **Scream** (1 turn): may take 1 reaction
2. **Impact:** Physique check

| Intensity | Range | DC | Building Damage |
|-----------|-------|-----|-----------------|
| Light | 20m | 10 | Structure −1 |
| Moderate | 40m | 14 | Structure −1d4, 50% fire |
| Heavy | 80m | 18 | Structure −1d6+2, 30% unexploded ordnance |
| Carpet | 200m+ | 20 | Building collapses directly |

3. **Aftermath:** dust, fire, collapse, survivors buried

### Building Collapse

- First reaction: Agility DC 14 (jump clear) → failure: buried
- Buried: Physique DC 16 (make breathing room) → failure: Serious Wound + −1 Stamina per 10 min
- Rescue: Craft DC 14 (locate) + 5 Stamina (dig) + d20 risk

### Fire

Spreads every 5 minutes: point of origin → adjacent room → entire floor → entire building (1–5 collapse risk per turn)

Crossing flames: Physique DC 12, failure → Minor Wound (burn) + clothing catches fire.

### Unexploded Ordnance

Encounter chance by location risk (DC 5–20). Discovery: Agility DC 14 (passive) / DC 10 (active). Avoid: Agility DC 12. Disarm: Craft DC 20 (failure → instant death).

> **Always tell players: don't touch it. Go around it.**

---

## Chapter 16: Trauma and Growth System (Complete)

### Trauma Event Table

| Event | TDC | Failure Effect | Accumulation |
|-------|-----|----------------|--------------|
| First time seeing a corpse | 8 | Mental State −1 | +1 |
| Life-or-death choice | 10 | Mental State −2 | +3 |
| Starvation >3 days | 10 | Mental State −1, hallucinations | +2 |
| Seeing a child's corpse (first time) | 14 | Mental State −3, second check | +5 |
| Companion death | 16 | Mental State −4, permanent Trauma | +7 |
| Forced to hurt someone | 14 | Mental State −3, insomnia | +4 |

### Trauma Accumulation Effects

| Accumulation | Effect |
|--------------|--------|
| 10+ | Disadvantage on Willpower in specific situations |
| 20+ | Compulsive behavior (violating needs Willpower DC 12) |
| 30+ | Mental State cap permanently −3 |

### Reducing Trauma

- Safe, deep sleep: −1
- Talking with someone trusted (successful Social): −1 (once per week / per target)
- Completing something meaningful: −1
- Luxury/comfort item: temporarily suppressed for 24 hours

### Experience Points (XP)

Grant 2–4 points per session. Spend on:
- Skill improvement: 1–5 points (by tier)
- Learning a Talent: 3–5 points
- Raising an attribute: 8 points (extremely rare—each attribute may be raised at most once per scenario)

### Adaptive Talent (Trauma-triggered)

At 5 Trauma points, choose an initial adaptation (heightened alertness, numbness, etc.); at 12 points, intermediate adaptation; at 20 points, deep adaptation (broken yet reborn, guardian, etc.).

---

# Part Four: Worldbuilding

## Chapter 17: Ostwin — The Besieged City

### Nation: The Kolvannia Federal Republic

Located in the northern Balkans of Eastern Europe, population ~8.5 million, capital Ostwin. A multi-ethnic nation with a fragile economy and corrupt politics.

### City: Ostwin

A river-valley city of ~1.2 million, founded over 600 years ago. Sits on both banks of the River Velta, surrounded by mountains on three sides. Unique blend of neoclassical and Ottoman-style architecture.

### Three Siege Causes (GM choice)

| Setting | Besieging Side | Nature | Suited For |
|---------|----------------|--------|------------|
| **A: Civil War** | Mirza People's Army (MPA) | Ethnic conflict, gray zones | Political narrative lovers |
| **B: Foreign Invasion** | Volko Federal Army (VFA) | Aggression and resistance | Newbie groups, clear sides |
| **C: Compound Crisis** | Multi-sided melee (may include zombie elements) | Civilization collapse | High difficulty, horror elements |

### The Six Districts

| District | Features | Scavenging | Danger | Special |
|----------|-----------|------------|--------|---------|
| **Old Town** | Stone roads, churches, underground passages | ★★★ | ★★★★ | Stealth +1, many snipers |
| **City Center** | Government buildings, banks, squares | ★★★★★ | ★★★★★ | Each scavenge needs an extra shelling check |
| **Industrial District** | Factories, warehouses, power plant | ★★★ | ★★★ | Fuel chance doubled |
| **University District** | Campus, library, medical school | ★★★★ | ★★ | Medicine chance doubled |
| **North Suburb** | Villas, embassy district, international hospital | ★★★★ | ★★★ | Highest comfort-item chance |
| **South Suburb** | Warehouses, railways, refugee camp, black market | ★★ | ★★★★ | Trade +1 Advantage |

### City Map Reference (GM)

Ostwin is a north-south oval, with the River Velta running east-west through it. Three main arteries: Republic Avenue (north-south), Riverside Road (east-west), Ring Road.

**Tactical Points:**
- Three bridges destroyed, only one Federal Army pontoon bridge remains
- Old Town's underground Ottoman drainage system—a concealed movement route
- Republic Avenue's "Sniper Alley" splits the City Center in two

---

## Chapter 18: The Eight Factions

| Faction | Type | Attitude Toward Players |
|---------|------|--------------------------|
| **Kolvannia Federal Army (KFA)** | Nominal defending side | Neutral / exploitative |
| **Besieging Side** (by setting) | Siege army | Hostile |
| **Civil Defense Committee (CDC)** | Community militia | Friendly / suspicious |
| **Black River Merchant Guild (BRS)** | Underground trade network | Trade partner |
| **International Humanitarian Aid (IHA)** | Neutral NGO | Friendly |
| **St. Michael's Church** | Religious shelter | Accepting |
| **University Survivors' Community (USC)** | Knowledge community | Friendly |
| **Voice of Liberty (VoL)** | Armed resistance organization | Recruiting |

---

## Chapter 19: Historical Timeline

### Before the Siege
- **D−30:** Political situation deteriorates, international organizations begin evacuation
- **D−14:** Border conflict escalates
- **D−7:** Enemy forces assemble outside the city
- **D−3:** City enters state of emergency
- **D−1:** Last trains evacuate civilians

### After the Siege
- **D+1:** Communications cut, bridges blown, encirclement formed
- **D+3–7:** Chaos period—shops looted, first shelters formed
- **D+14:** Water and power supply cut, severe material shortage
- **D+30:** Black market network takes shape, CDC organizes, first disease outbreak
- **D+60:** Winter arrives (if autumn/winter), fuel becomes the top resource
- **D+90:** Materials nearly exhausted, community splits, internal conflict rises
- **D+120:** Late siege—everyone prepares for the final ending

---

# Part Five: GM Running Guide

## Chapter 20: Narrative Techniques

### Sensory Narration Method

Don't just say "you walk into a street." Describe:
- **Visual:** dust drifting in the slanted sunlight, windows of the building across like hollow eye sockets
- **Auditory:** intermittent gunfire in the distance, a baby's cry from somewhere nearby
- **Olfactory:** stench of decay, burnt rubber, rain-soaked plaster
- **Tactile:** the crunch of broken glass underfoot, the cold door handle
- **Gustatory:** the taste of dust in your mouth, the preciousness of the last sip of water

### The Glimmer Rule

After each major loss or dark moment, offer a sliver of tiny hope:
- Seeing a child's corpse → find a box of unopened crayons around the corner
- Companion dies → in their pocket, a sketch of you they never showed you
- Shelter discovered → on evacuation, find a secret passage you'd never walked before

The glimmer isn't to make the game "easier"—it's to give those in the dark a reason to keep going.

### Despair Scale (1–10)

| Level | Description | GM Adjustment |
|-------|-------------|---------------|
| 1–3 | Tense but controllable | Normal difficulty |
| 4–6 | Rising pressure | Increase encounter frequency, reduce supplies |
| 7–8 | On the brink of despair | Raise DC by 1–2, increase moral dilemmas |
| 9–10 | Edge of collapse | Story climax—major choice or ending trigger |

### Five Difficulty Levers

To adjust game difficulty, don't change the rules—just adjust these five levers:
1. **Supply appearance rate**—scavenging DC and rewards
2. **Encounter frequency**—trigger chance of random encounters
3. **NPC reliability**—chance an NPC tells the truth
4. **Environmental danger**—shelling frequency and intensity
5. **Information availability**—vagueness of clues

## Chapter 21: Solo Player GM Techniques

### Three Principles of NPC Companion Roleplay

1. **NPCs are people, not tools**—they have their own needs, fears, and limits
2. **Don't make decisions for the player**—NPCs offer opinions but never overstep
3. **NPCs make mistakes too**—their advice may be wrong

### Three-Act Structure

Each session can be designed in three acts (~3–4 hours):

| Act | Share | Content |
|-----|-------|---------|
| **Act One** | 25% | Daily survival, shelter maintenance, NPC interaction |
| **Act Two** | 50% | Going out to scavenge/quest, encounters, moral choices |
| **Act Three** | 25% | Return, consequence handling, setup for next session |

### Failure Is Not the End

When a solo character fails, offer a "cost" rather than "death":
- Captured (opens an escape storyline)
- Lose supplies (increases survival pressure)
- Injured (increases recovery pressure)
- NPC pays the cost (emotional impact)
- Forced to accept an unfavorable deal

## Chapter 22: Moral Choice Design

### Six Types of Moral Dilemma

1. **Resource allocation**—who gets the last medicine/food?
2. **Trust**—open the door for a stranger?
3. **Means and ends**—steal/harm others to save your own?
4. **Sacrifice**—risk your life for another?
5. **Truth and lies**—tell companions the cruel truth or a kind lie?
6. **Leave or stay**—flee yourself or stay to protect others?

### GM Presentation Rules

- **Never preach**—don't imply a "right answer." Every choice has a cost
- **Show consequences, don't judge**—don't say "you did a bad thing," show the corpses in the street the next day
- **Let NPCs remember**—NPCs remember every choice you make and change their attitude toward you because of it
- **No reset button**—consequences are permanent, but it's not the end of the world either

---

# Part Six: Scenario Framework

## Chapter 23: Scenario Overview

The three scenarios can be linked into a complete story arc (early siege → mid → late), or played independently.

| Scenario | Time | Difficulty | Days | Core Theme |
|----------|------|------------|------|------------|
| S1 "The First Day" | Siege Day 3–14 | ★★☆ | 5–7 days | Chaos and adaptation |
| S2 "The Long Winter" | Day 30–90 | ★★★☆ | 14–21 days | Depletion and choices |
| S3 "The Final Gate" | Day 100+ | ★★★★☆ | 7–10 days | Final ending |

## Chapter 24: Scenario One "The First Day" — Difficulty ★★☆

### Overview
The siege has just begun; the city is in chaos. Players must find their footing in the ruins of order—build a Shelter, find the first supplies, decide who to trust.

### Three Starting Scenarios (player choice or GM assignment)

| Scenario | Starting Location | Starting Resources | Starting Challenge |
|----------|-------------------|--------------------|--------------------|
| A | Own apartment (Old Town) | Small household reserves | Neighbor knocks asking for help |
| B | Workplace (City Center/University) | Colleagues/classmates nearby | Building damaged, need to evacuate |
| C | On the street (out when siege began) | Only what's on them | Immediate patrol/shelling encounter |

### Special Event Table (GM triggers by day count)

| Day | Event | Description |
|-----|-------|-------------|
| D+3 | First shelling | Somewhere in the city is shelled—players must find cover |
| D+4 | Water crisis | Tap water stops |
| D+5 | Neighbor's request | A neighbor (NPC) knocks asking for help |
| D+7 | Airdropped leaflets | Planes drop leaflets—surrender demand from besiegers or message from friendly forces |
| D+10 | First black market contact | Someone (Marco NPC) approaches players offering a "deal" |
| D+14 | First sniper appearance | Crossing streets in daylight becomes extremely dangerous |

### Scavenging Locations (available in Scenario One)

| Location | Type | DC | Supply Potential | Risk |
|----------|------|-----|------------------|------|
| Nearby ruined home | Residence | 10 | Food, clothing | Low |
| Corner grocery | Shop | 12 | Cans, batteries | Medium |
| Abandoned vehicle | Outdoor | 8 | Gasoline, tools | Medium (exposure) |
| Underground parking | Indoor | 10 | Fuel, materials | Low |
| Abandoned apartment | Residence | 10 | Medicine, clothing | Medium |
| Elementary school classroom | Public building | 8 | First-aid kit, stationery | Low |

### Ending Conditions
- Successfully establish a stable Shelter (Structure + Sealing + Comfort ≥ 5)
- Build a relationship with at least 1 NPC (REL ≥ 3)
- Survive 7 days

---

## Chapter 25: Scenario Two "The Long Winter" — Difficulty ★★★☆

### Overview
The siege enters its second month. Winter arrives. Supplies are extremely scarce; the black market becomes a necessary evil for survival. The moral choices players face become sharper.

### Winter Special Rules
- Fuel consumption doubled (daily −2)
- Warmth natural decline rate doubled
- Daytime shortened (more Night actions)
- Disease (pneumonia) risk increased
- Scavenging DC +2 (most locations already looted)

### Four-Act Structure

| Act | Theme | Days | Core Event |
|-----|-------|------|------------|
| Act One | Winter descends | D+30–40 | Fuel crisis, shelter reinforcement |
| Act Two | Resource depletion | D+40–55 | Must scavenge high-risk locations |
| Act Three | Test of trust | D+55–70 | NPC secrets revealed, betrayal or loyalty |
| Act Four | Dark dealings | D+70–90 | Key deal with the Black River Merchant Guild |

### New Scavenging Locations

| Location | DC | Supplies | Risk |
|----------|-----|----------|------|
| Border black market (South Suburb) | 14 | Anything | Swindlers, informants |
| Abandoned hospital (University District) | 16 | Large quantities of medicine | Enemy stronghold |
| Industrial warehouse (Industrial District) | 12 | Fuel, tools | Gang-occupied |
| Bombed supermarket (City Center) | 14 | Cans | Unstable structure |
| Other shelters (various districts) | Social | Intel, alliance | Other side's hostility |
| Federal Army outpost | 18 | Weapons, military rations | Military |
| Church basement (Old Town) | 10 | Shelter, spiritual comfort | Already known by many |

### Ending Conditions
- Shelter survives the winter (Warmth not at zero for over 7 days)
- Build meaningful relationships with at least 3 NPCs
- Make at least 2 major moral choices

---

## Chapter 26: Scenario Three "The Final Gate" — Difficulty ★★★★☆

### Overview
The siege enters its hundredth day. The ending is coming—but in what form? Players must make the final choice—and that choice will permanently change everything that remains.

### Final Invitations from Multiple Factions

| Faction | Proposal | Cost |
|---------|----------|------|
| Federal Army (KFA) | Join the final breakout operation | Extremely high death risk |
| Black River Merchant Guild (BRS) | Secret evacuation passage (limited slots) | Huge cost—all supplies or a secret |
| Voice of Liberty (VoL) | Participate in the final resistance operation | Almost certain sacrifice |
| International Humanitarian Aid (IHA) | Negotiated evacuation (civilians only) | Must prove "civilian status"—may need to abandon armed companions |
| The Church | Stay in the city, guard those who remain | Endure the final phase of the siege |

### Key NPC Endgame Choices
Each NPC has their own choice in the endgame—their choices and the players' choices influence each other. Father Andrei chooses to stay and guard the church, Jana considers leading the community in a breakout, "The Professor" prepares his own evacuation plan, Dimitri faces his last chance at redemption, and so on. (Full NPC data in Part Seven.)

### The Ultimate Moral Dilemma — "The Signal"

Players obtain a radio frequency—the besieging side's command frequency. They can:
- **Option A:** Give the frequency to Voice of Liberty → may turn the tide of battle, but will inevitably provoke retaliatory massacre
- **Option B:** Give the frequency to the Black River Merchant Guild → trade for safe evacuation, but everyone else in the city is abandoned
- **Option C:** Use the frequency to negotiate → attempt to secure safe passage for themselves, very low success rate
- **Option D:** Destroy the frequency → do nothing, let fate take its natural course

### Ending Conditions
Based on the accumulated choices from Scenarios One and Two, NPC relationships, resource state, and the final choice in Scenario Three, trigger one of six endings (see Part Eight).

> **🟢 Trauma Relief Node:** When players complete a core task in S3 (such as successfully resolving the "Signal" dilemma, helping a key NPC complete their endgame choice, or making the final choice), they may receive a one-time Trauma Accumulation −5. This is the only major breather in a long campaign—representing that the character found some reconciliation or meaning in the endgame.

---

## Chapter 27: Scenario Linking Guide

### Transition from S1 to S2
- Players must have a stable Shelter
- Must know at least 1 major NPC
- GM describes the time jump (2–3 weeks), briefly summarizing the changes in between

### Transition from S2 to S3
- Players' Shelter must still exist (even if damaged)
- At least 1 NPC has a deep relationship with the player (REL ≥ 5)
- Players have accumulated some Trauma and Experience
- GM describes the overall situation changes of the siege

---

# Part Seven: NPC Roster and Data

## Chapter 28: The 15 Preset NPCs

### NPC Relation Value System

Each NPC has two hidden values:
- **Relation value (REL):** −10 to +10. Positive = trust/favor, negative = hostility/suspicion
- **Secret value (SEC):** 0 to 10. Represents the amount of information the NPC is hiding from the player

### NPC #1: Father Andrei

| Item | Content |
|------|---------|
| **Type** | Spiritual pillar / shelter-giver |
| **Age** | 63 |
| **Background** | Orthodox priest who served at St. Michael's Cathedral for thirty years. Opened the church doors to everyone on the first day of the siege |
| **Personality** | Calm, firm, compassionate |
| **REL Start** | +2 |
| **SEC** | 7—secretly helps those hunted by both sides; precious relics hidden in the church basement |
| **Help** | Shelter, spiritual comfort, underground network |
| **Cost** | Food, medicine |
| **Limit** | Will not participate in any violence |

### NPC #2: Jana Novak

| Item | Content |
|------|---------|
| **Type** | Community organizer / CDC leader |
| **Age** | 41 |
| **Background** | Former history teacher, spontaneously organized the CDC |
| **Personality** | Pragmatic, decisive, charismatic |
| **REL Start** | 0 |
| **SEC** | 4—her husband fled before the siege with the savings and another woman |
| **Help** | CDC resource network, security intel, organizational ability |
| **Limit** | Will not sacrifice the whole community for one person |

### NPC #3: "The Professor"

| Item | Content |
|------|---------|
| **Type** | Black River Merchant Guild leader / gray-market trader |
| **Age** | ~50 (unknown) |
| **Background** | Said to be a former university economics professor. Built the underground trade network after the siege |
| **Personality** | Calm, rational, polite but keeps distance |
| **REL Start** | 0 |
| **SEC** | 9—has secret communication with the besieging side; holds a list of "people who must not die" |
| **Help** | Scarce supplies, intel, safe passage |
| **Limit** | Will not endanger himself; will sell out anyone if necessary |

### NPC #4: Dr. Elena Castro

| Item | Content |
|------|---------|
| **Type** | International volunteer / surgeon |
| **Age** | 38 |
| **Background** | Doctors Without Borders, chose to stay when the siege began |
| **Personality** | Resilient, dark humor |
| **REL Start** | +1 |
| **SEC** | 3—has a chronic illness, medicine running out, never told anyone |
| **Help** | Professional medical care, medicine, medical knowledge teaching |
| **Limit** | Insists on medical neutrality—treats anyone including enemy wounded |

### NPC #5: Dr. Mia Korr

| Item | Content |
|------|---------|
| **Type** | Scientist / USC leader |
| **Age** | 34 |
| **Background** | Associate professor of biology, specializes in epidemiology |
| **Personality** | Rational, curious, analyzes survival with science |
| **REL Start** | +1 |
| **SEC** | 5—holds antibiotic-resistant strain research; in enemy hands it could be a biological weapon |
| **Help** | Lab resources, scientific knowledge, university community manpower |
| **Limit** | Will not abandon research for survival |

### NPC #6: "The Ghost"

| Item | Content |
|------|---------|
| **Type** | Voice of Liberty leader / former special forces |
| **Age** | ~45 |
| **Background** | Former special forces officer, organized armed resistance |
| **Personality** | Taciturn, paranoid, mission-fanatic |
| **REL Start** | −1 |
| **SEC** | 8—the real motive for organizing resistance is to find a dignified death |
| **Help** | Military training, weapons, tactical intel |
| **Limit** | Will sacrifice anyone for the greater goal |

### NPC #7–15 Quick Reference

| # | Name | Type | REL | SEC | Core Help |
|---|------|------|-----|-----|-----------|
| 7 | Grandma Marta | Elder / folk wisdom | +1 | 2 | Herbal knowledge, Old Town secret passages |
| 8 | Dimitri | Traumatized soldier | −2 | 6 | Combat skills (if PTSD can be overcome) |
| 9 | Nico & Lena | Siblings (ages 12 & 7) | 0 | 1 | Emotional drive, Lena's drawings contain intel |
| 10 | Carlo | Swindler | +2 (false) | 10 | Illegally obtained supplies, underworld |
| 11 | Sofia | Mother with infant | 0 | 4 | Moral touchstone |
| 12 | Victor | Informant | +1 | 10 | Intel (including misinformation) |
| 13 | Ivan & Ash | Old man and dog | −1 | 3 | South Suburb terrain knowledge, dog's vigilance |
| 14 | Katarina | Artist / recorder | +1 | 6 | Info (sketchbook contains dangerous intel) |
| 15 | Marco | Black market broker | 0 | 4 | Supply trade (cheaper), street intel |

### NPC Relation Value Change Triggers

| Trigger | REL Change |
|---------|-----------|
| Player shares scarce resource | +1~3 |
| Player saves NPC's life | +3~5 |
| Player's lie is exposed | −2~4 |
| Player refuses to help NPC | −1~3 |
| Player reveals NPC's secret (without consent) | −5 (permanent) |
| Player reveals own secret | +1~3 |

---

# Part Eight: Encounters and Events

## Chapter 29: Random Encounter Tables

### Daytime Encounters (D66, varies by district)

| D66 | Old Town | City Center | Industrial District | University District | North Suburb | South Suburb |
|-----|----------|-------------|---------------------|---------------------|--------------|-------------|
| 11–13 | Patrol Soldier (2) | Sniper sightline | Feral Dog pack (d3+1) | Student survivors | Abandoned mansion (scavengeable) | Black market merchant |
| 14–16 | Feral Dog (d3) | Shelling (light) | Patrol Soldier (2) | University community member | Patrol Soldier | Looter (d3) |
| 21–23 | Other survivors | Patrol Soldier (3+ Officer) | Abandoned supply pile | Researcher (with intel) | IHA vehicle | Refugee camp unrest |
| 24–26 | Collapse risk | Airdropped leaflets | Gang-occupied | Patrol Soldier | Vacant embassy | Victor (informant) |
| 31–33 | Grandma Marta | Unexploded ordnance | Fuel discovery | Dr. Mia | International hospital | Black River Merchant Guild |

(Full 36 encounters per district—see Appendix)

### Night Encounters (D66, all districts)

| D66 | Encounter | Threat |
|-----|-----------|--------|
| 11–15 | Patrol Soldier + searchlight | Medium |
| 16–21 | Feral Dog pack | Low–Medium |
| 22–25 | Other stealthy survivors | Low |
| 26–31 | Abandoned building (scavenge/hide) | Low |
| 32–35 | Deserter | Medium (may cooperate) |
| 36–41 | Looter | Medium |
| 42–45 | Black market night trade | Low |
| 46–51 | Shelling | High |
| 52–55 | Voice of Liberty member | Medium |
| 56–61 | Empty (safe) | None |
| 62–65 | Light source inside a building | Unknown |
| 66 | Airdropped supply crate (rare!) | Medium (contested) |

## Chapter 30: 15 Moral Dilemma Situations

| # | Name | Core Conflict | Options |
|---|------|---------------|---------|
| 1 | The Last Insulin | Diabetic girl vs. injured medic | 3 |
| 2 | The Knock at the Door | Someone knocks on the shelter door at midnight—open or not? | 3 |
| 3 | Two Wounded | Only one first-aid kit—save whom? | 3 |
| 4 | The Crying Baby | A baby's cry may expose the shelter—what to do? | 3 |
| 5 | The Informant's Deal | Victor offers intel—but you know he'll betray you | 2 |
| 6 | The Black Market's "Special Goods" | Someone is selling children—can you intervene? | 3 |
| 7 | The Poisoned Water Source | You find the community water source contaminated—tell everyone or keep it secret? | 2 |
| 8 | The Deserter's Request | Dimitri asks to be hidden—but harboring a deserter is capital punishment | 3 |
| 9 | The Radio Message | Receive an enemy "safe passage" broadcast—trap or opportunity? | 3 |
| 10 | The Forgotten Old Man | The old man next door hasn't moved in three days—go check or save stamina? | 2 |
| 11 | The Student's Plan | The university community plans a breakout—join or dissuade? | 3 |
| 12 | The Last Bullet | You have one bullet—use it to protect a companion or keep it for yourself? | 2 |
| 13 | The Burning Library | The university library is on fire—rush in to save books or let it burn? | 3 |
| 14 | The Besieger's Recruitment | Enemy recruits local guide—reward is safe passage | 3 |
| 15 | The Signal | You hold the besieging side's command frequency (see Scenario Three) | 4 |

### Dilemma Design Formula (GM improv)

```
Dilemma = Rare resource + two (or more) people who need it + time pressure + no perfect answer
```

Example: one dose of antibiotics (rare resource) + injured companion vs. feverish child (two needers) + "must decide before dawn because the patrol route will change" (time pressure). No option lets everyone live.

## Chapter 31: Special Events

### Air Raid

Trigger: specified by scenario or at GM discretion. Describe the scream of the shell cutting the air → shockwave → dust and rubble. May destroy or damage the Shelter, alter terrain, create new scavenging opportunities (in the ruins).

### Ceasefire Negotiation

The besieging side and the defending side hold brief negotiations. During this: daytime outing risk drops sharply, supply convoys may enter the city, black market prices plummet. But the negotiation may break down at any moment—creating a false sense of security.

### Supply Airdrop

Humanitarian organizations airdrop supplies—food, medicine, water. But: the drop site is a dangerous open area, multiple factions will head there to grab at once, may trigger violent conflict.

### Riot

When a rumor (true or false) sparks panic: crowds surge somewhere, stampede and chaos, the shelter may be overrun. Players must decide: join the crowd, hide, or try to help others.

### Plague Outbreak

Dirty environment + malnutrition + lack of medical care = plague. Disease spreads in the shelter/community; players must find medicine, isolate the sick, decide how to allocate limited medical resources.

---

# Part Nine: Ending System

## Chapter 32: The Six Endings

### Ending One: Liberation

Friendly forces break through the siege lines; the city regains freedom.

**Trigger Condition:** Survive past the total siege days (set by GM), and maintain at least one functioning Shelter.

**Narrative Frame:** "The guns fell silent before dawn. Then you heard it—not the scream of shells, but cheering. From the far end of the street, from the depths of the ruins, from every corner where someone still lived. The flag on the armored vehicle was not the enemy's. You stood in the doorway, the sunlight stinging eyes accustomed to darkness. The war was over. But you were not whole—perhaps you never would be."

### Ending Two: Lifting of Siege

Diplomatic pressure or strategic shift leads to the siege being lifted.

**Trigger Condition:** Possess a radio and receive related intel, and successfully pass the intel to a key faction.

### Ending Three: Fall

Enemy forces break the last defensive line, fully occupying the city.

**Trigger Condition:** Unable to stop the enemy's final offensive. Players must flee or hide before the fall.

**Narrative Frame:** "The tank treads crushed the flagstones of Liberty Square—the same stones where you once drank coffee, dated, protested, lived. The city did not surrender; it simply stopped resisting. You watched the flag outside the window being replaced, then drew the curtain."

### Ending Four: Escape

You found a way out of the city.

**Trigger Condition:** Buy safe passage through the black market, or join a breakout operation.

### Ending Five: Freeze and Starve to Death — No Ending Achieved

**Trigger Condition:** Resources exhausted, unable to maintain basic survival.

### Ending Six: Open Ending

For groups who want to continue playing—the siege still goes on, the story is not over.

## Chapter 33: Ending Determination Framework

```
Ending = World Setting (40%) + Player Influence (30%) + Key Events (20%) + Random (10%)
```

Based on the weighted sum of the four factors, the GM decides the siege's final direction. Players cannot "decide" the ending, but every choice they make influences the result.

### Post-Ending Handling

1. **Character Summary:** Each surviving character gets an ending narrative—based on choices, relationships, Trauma
2. **Loose Ends:** Raise the "what happened next?" question—where did the character go? Did the relationship last?
3. **Group Reflection:** Let players share their most memorable moments
4. **GM's Closing Words:** Bring the siege to a close

---

# Part Ten: GM Quick Reference

## Daily Flow Quick Reference

```
Dawn: consume resources → players decide today's actions
Daytime: execute actions (stay in Shelter or go out) → encounter check
Night: execute actions (or return) → encounter check
Before Dawn: resource consumption → condition decay → threshold triggers → recovery attempt → new day
```

## Shelter Improvement Action Quick Reference

| Action | Stamina | Requirement | Effect |
|--------|---------|-------------|--------|
| Reinforce structure | 3 | Materials ×1 | Structure +1 (cap 5) |
| Seal windows | 2 | Cloth/plastic sheet ×1 | Sealing +1 (cap 5) |
| Craft tool | 2 | Craft DC 10 + Materials | Craft simple item |
| Care for wounded | 2 | Craft DC 8 | Wound recovery advances 2 days (once per day per wounded) |
| Rest & recreation | 1 | Entertainment item → Mental State +2 | Mental State +2 |
| Cooking | 1 | Craft DC 8 | 1 raw food → 1.5 cooked food |

### Comfort Mechanic

| Comfort | Effect |
|---------|--------|
| 0–1 | Long Rest Trauma reduction halved |
| 2–3 | Normal |
| 4–5 | Mental State recovery +2; Trauma reduction doubled (−2) |

## Crafting System Quick Reference

| Item | Materials | DC | Stamina | Output |
|------|-----------|-----|---------|--------|
| Simple bandage | Cloth ×1 | 6 | 1 | Treat 1 Minor Wound |
| Improvised torch | Cloth + Fuel ×1 | 6 | 1 | Light 2h (silent) |
| Simple trap | Wire + nails | 12 | 2 | Minor Wound / alarm |
| Reinforcement plank | Materials ×2 | 8 | 2 | Reinforce structure |
| Molotov cocktail | Liquor/gasoline + cloth | 14 | 1 | Fatal Wound (⚠ fire risk, scarce materials) |
| Simple water filter | Plastic sheet + cloth + container | 12 | 3 | Filter 20L (filter element needs 1 cloth per 20L) |

> **GM Tip:** On crafting failure, materials are consumed but no output. On Critical Failure (natural roll ≤4), materials are destroyed + Minor Wound. Having a Mechanic profession → Advantage.

```
Before Dawn: resource consumption → condition decay → threshold triggers → recovery attempt → new day
```

## DC Quick Reference Table

| DC | Name | +0 Success | +2 Success | +5 Success |
|----|------|------------|------------|------------|
| 6 | Trivial | 95% | 99% | 100% |
| 8 | Simple | 84% | 95% | 100% |
| 10 | Ordinary | 62% | 84% | 98% |
| 12 | Challenging | 37% | 62% | 91% |
| 14 | Hard | 16% | 37% | 74% |
| 16 | Severe | 5% | 16% | 50% |
| 18 | Extreme | ~0% | 5% | 26% |
| 20 | Nearly Impossible | 0% | ~0% | 9% |

## Sensory Prompt Cards

| Sense | Word Bank for the Siege |
|-------|--------------------------|
| Visual | dust, smoke, rubble, peeling paint, bullet holes, bloodstains, candlelight, searchlight |
| Auditory | distant gunfire, echoing footsteps, crunch of broken glass, wind howling through broken windows, baby's cry |
| Olfactory | rotting flesh, gunpowder, mildew, damp plaster, diesel, boiling beans |
| Tactile | cold metal, rough plaster, soaked cloth, trembling ground |

---

# Appendix

## Appendix A: Complete Item List (53 items)

### Food (8 items)
| ID | Name | Effect | Slot |
|----|------|--------|------|
| F01 | Canned food | One day basic nutrition | Medium |
| F02 | Compressed biscuits (6 pcs) | Half-day nutrition, very light | Small×3/slot |
| F03 | MRE (military ration) | One day full nutrition + heater pack | Medium |
| F04 | Dried food (500g) | 2–3 days nutrition (needs cooking + water) | Medium |
| F05 | Sugar (200g) | Instant energy | Small×3/slot |
| F06 | Salt (100g) | Seasoning, preservation | Small×3/slot |
| F07 | Vitamin tablets (60 pcs) | Nutritional supplement | Small×3/slot |
| F08 | Energy bar | One meal instant energy | Small×3/slot |

### Water (5 items)
| ID | Name | Effect | Slot |
|----|------|--------|------|
| W01 | Bottled water (1L) | One day drinking water | Medium |
| W02 | Large bottled water (5L) | Five days drinking water | Large (2 slots) |
| W03 | Water purifying tablets (20 pcs) | 1 tablet purifies 1L | Small×3/slot |
| W04 | Simple water filter | Filters 50L | Medium |
| W05 | Foldable water bag (3L) | Water storage container | Medium (empty) / Large (full) |

### Medicine (8 items)
| ID | Name | Effect | Slot |
|----|------|--------|------|
| M01 | First-aid kit | 3 Minor / 1 Serious Wound treatment | Medium |
| M02 | Antibiotics (7-day course) | Treats bacterial infection | Small×3/slot |
| M03 | Painkillers (12 pcs) | Pain relief −1 (4–6h) | Small×3/slot |
| M04 | Disinfectant alcohol (200ml) | Disinfect, clean, fuel | Small×3/slot |
| M05 | Tourniquet | Emergency bleeding stop | Small×3/slot |
| M06 | Burn ointment | Burn treatment | Small×3/slot |
| M07 | Sedatives (6 pcs) | Temporarily suppress panic (2–4h) | Small×3/slot |
| M08 | Epinephrine auto-injector | Allergy first aid / temporary boost | Small×3/slot |

### Fuel (5 items)
| ID | Name | Effect | Slot |
|----|------|--------|------|
| L01 | Lighter | Ignition (~100 uses) | Small×3/slot |
| L02 | Candle | 4–6h light | Small×3/slot |
| L03 | Gasoline (1L) | Vehicle fuel, accelerant | Medium |
| L04 | Crank flashlight | Renewable light | Medium |
| L05 | Solid fuel blocks (8 pcs) | 20 min cooking each | Small×3/slot |

### Materials (6 items)
| ID | Name | Slot |
|----|------|------|
| T01 | Tape (waterproof, strong) | Small×3/slot |
| T02 | Rope (10m nylon) | Medium |
| T03 | Wire (5m) | Small×3/slot |
| T04 | Cloth / old clothing | Medium |
| T05 | Nails & screws (50 pcs) | Small×3/slot |
| T06 | Plastic sheet / tarp (2×2m) | Medium |

### Tools (8 items)
| ID | Name | Effect | Slot |
|----|------|--------|------|
| U01 | Multi-tool | Repair +1 | Small×3/slot |
| U02 | Crank radio | Obtain outside info | Medium |
| U03 | Wrench / crowbar | Pry doors/windows, can be weapon | Medium |
| U04 | Sewing kit | Mend clothing, emergency suturing | Small×3/slot |
| U05 | Binoculars | Observation +2 (far) | Medium |
| U06 | Large backpack | +4 slots (net +2) | Large (2 slots) |
| U07 | Map | Navigation, marking | Small×3/slot |
| U08 | Compass | Sense of direction | Small×3/slot |

### Weapons (6 items)
| ID | Name | Damage | Slot |
|----|------|--------|------|
| A01 | Kitchen Knife | Serious Wound | Small×3/slot |
| A02 | Pipe / Baseball Bat | Light–Medium Wound | Medium |
| A03 | Pistol (12 rounds) | Serious Wound (fatal potential) | Medium |
| A04 | Shotgun (6 rounds) | Serious–Fatal Wound | Large (2 slots) |
| A05 | Pepper Spray | Blind (non-lethal) | Small×3/slot |
| A06 | Rock / Brick (thrown) | Very light wound | Small×3/slot |

### Luxuries & Comforts (7 items)
| ID | Name | Effect | Slot |
|----|------|--------|------|
| C01 | Cigarettes (20) | +1 Willpower for 1h | Small×3/slot |
| C02 | Alcohol (500ml) | Relieve stress / disinfect | Medium |
| C03 | Coffee (100g) | Resist fatigue 4h | Small×3/slot |
| C04 | Book / magazine | Pass time / knowledge | Medium |
| C05 | Paper & pen | Record, journal | Small×3/slot |
| C06 | Toy / plush doll | Soothe children | Medium |
| C07 | Photo / memento | Spiritual pillar | 0 slot (on person) |

## Appendix B: Enemy Data Quick Reference (v1.2 3d6 system)

### Patrol Soldier (Threat 2)
- Attributes: Physique 4 / Agility 3
- Awareness: +2 (routine patrol +0)
- Movement: 1 Distance Band/turn
- Attack: Assault Rifle +3 (at least Serious Wound) / Bayonet +3 (Serious Wound)
- Special: radio call for Reinforcement (2d4 turns), flashlight
- Weakness: fixed route, −2 when tired, may hesitate on civilians (30%)

### Sniper (Threat 4)
- Attributes: Physique 3 / Agility 5
- Awareness: +5 (visual) / +1 (auditory)
- Movement: 0 (fixed position)
- Attack: Sniper Rifle +5 (at least Fatal Wound, exceeds DC → instant death)
- Special: aimed +3, optical scope (ignores cover within 100m), camouflage (detection DC 18)
- Weakness: narrow field of view, greatly reduced efficiency at night, reveals position when firing

### Officer (Threat 3)
- Attributes: Physique 3 / Agility 3 / Willpower 5
- Awareness: +4
- Movement: 1 Distance Band/turn
- Attack: Pistol +3 (Serious Wound) / Saber +3 (Serious Wound)
- Special: command (nearby soldiers' Awareness +2), interrogation (Social contest DC 16)
- Weakness: arrogant, protects self, may be reluctant to call support

### Deserter (Threat 2)
- Attributes: Physique 4 / Agility 4
- Awareness: +3
- Movement: 1 Distance Band/turn
- Attack: Assault Rifle +2 (Serious Wound, only d6 rounds ammo) / Dagger +3 (Serious Wound)
- Special: attack Advantage when desperate, wilderness survival (scavenge +3)
- Weakness: limited ammo, paranoid (Social DC 16 to build trust)

### Looter (Threat 2–3)
- Attributes: Physique 3 / Agility 3
- Awareness: +2
- Movement: 1 Distance Band/turn
- Attack: Club +2 (Light–Serious Wound) / Knife +3 (Serious Wound) / Pistol +1 (30% chance to have)
- Special: +1 attack with 3+ members, knows supply locations
- Weakness: disorganized, bullies the weak (when counterattacked → Willpower DC 12 or retreat)

### Feral Dog (Threat 1–2)
- Attributes: Physique 2 / Agility 4
- Awareness: +4 (smell) / +2 (hearing)
- Movement: 2 Distance Bands/turn
- Attack: Bite +3 (Minor Wound + infection risk DC 10)
- Special: attack Advantage with 3+, tracks scent 24h, night vision
- Weakness: afraid of fire (Willpower DC 8), can be lured with food, flees when injured

## Appendix C: Terminology Cross-Reference

| English Term | Abbrev | Description |
|--------------|-------|-------------|
| Difficulty Class (DC) | DC | Difficulty of a check |
| Trauma Difficulty Class (TDC) | TDC | Difficulty of a trauma event |
| Relation value (REL) | REL | Relation |
| Secret value (SEC) | SEC | Secret |
| Threat Level | Threat | Threat Level |
| Wound Tier | Wound | Wound Tier |
| Stealth | Stealth | Concealment Rating |
| Civil Defense Committee (CDC) | CDC | Civil Defense Committee |
| Black River Merchant Guild (BRS) | BRS | Black River Merchant Guild |
| International Humanitarian Aid (IHA) | IHA | International Humanitarian Aid |
| Voice of Liberty (VoL) | VoL | Voice of Liberty |

---

# Part Eleven: Multiplayer Mode GM Guide

## Multiplayer Mode Adjustments

Urban Survivors is designed for solo play by default. Multiplayer mode (2–4 players) requires the following adjustments:

### Character Creation Coordination
- Suggest players choose different professions—complementary skill sets make the team more resilient
- Character relationships must be negotiated at creation (knew each other before the siege? Met after?)

### Shared Shelter
- Structure/Sealing take the highest value among all members; Comfort takes the average
- Storage capacity = 10 + (member count × 5) units
- Each member consumes food and water independently

### Difficulty Adjustment
- Encounter frequency: +25% (group activity is easier to detect)
- Resource consumption: each member consumes independently
- Group stealth is harder (use the Group Stealth formula)

### Character Conflict Management
- Resource allocation conflict is the core tension of multiplayer—don't avoid it
- Different players' "Protected Ones" may contradict each other—this is excellent story material
- If players cannot reach consensus, use a contested Social check (Social vs. Social)

### Time Management
- The team can split up (one scavenges, one stays behind), performing multiple actions simultaneously
- GM handles each player's action segment in turn (about 10–15 minutes per person)

---

## Driving Skill GM Guide

Vehicles may still be found in the city (abandoned cars, Federal Army leftover jeeps).

### Driving Situations
| Situation | Check | DC |
|-----------|-------|-----|
| Start abandoned vehicle | Craft + Driving | 12 |
| Drive on rubble road | Driving | 10 |
| Evade pursuit | Driving (vs. pursuer) | Contest |
| Judge route safety | Driving | 8 |
| Silent glide (engine off) | Driving | 14 |

### Vehicle Rules
- Driving 1 hour consumes 1 unit of gasoline
- Vehicle noise level 5 (engine sound)—draws attention within 150 meters
- Vehicle provides movement speed ×3 (3 Distance Bands/turn)
- Vehicle can serve as temporary cover (Defense Value +3)

---

> *"As the GM, your job is not to kill the players—your job is to make them feel that in this siege, every person who survives to tomorrow is a miracle. And behind every miracle, there is a choice."*
>
> — Jing Shiwen, Urban Survivors GM Rulebook

---

**End of Document.** Urban Survivors GM Rulebook v1.2.
