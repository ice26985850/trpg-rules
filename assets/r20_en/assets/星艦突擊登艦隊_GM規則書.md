# Starship Boarding Assault TRPG — Game Master Rulebook

> **Version:** v1.0  
> **Codename:** void-breacher-trpg  
> **Audience:** Game Master (GM)  
> **Note:** This rulebook contains the entirety of the *Player Rulebook*. The Game Master (GM) only needs to read this document to run the game.

---

# Part One: Player Rules (Basic Reference)

> The following chapters are identical to the *Player Rulebook*, reproduced here for the Game Master's (GM's) convenience.  
> For the full text, see *Starship Boarding Assault TRPG — Player Rulebook* (`星艦突擊登艦隊_玩家規則書.md`).

## Chapter One: Core Rules

### Dice System

This game uses the **d20 Roll System**. Core formula:

```
Check Result = 1d20 + Attribute Modifier + Proficiency Bonus + Circumstance Modifier
```

A Check Result ≥ the Difficulty Class (DC) is a Success. Natural 20 = Critical Success; natural 1 = Critical Failure.

**Advantage:** Roll 2d20, take the higher.  
**Disadvantage:** Roll 2d20, take the lower.  
They cancel each other out. Equivalent to roughly ±5 modifier (±25% success rate).

### Five Attributes (1–20)

| Attribute | Abbr. | Meaning |
|------|:---:|------|
| Tactics (TAC) | TAC | Close-quarters combat, weapon use, tactical judgment |
| Engineering (ENG) | ENG | Technical operation, device hacking, environment analysis |
| Mobility (MOB) | MOB | Movement ability across gravity environments |
| Perception (PER) | PER | Environmental awareness and tactical anticipation |
| Resilience (RES) | RES | Physical endurance and willpower |

Attribute Modifier = (Attribute Value − 9) ÷ 2 (rounded down).

### Skill System (20 skills, 4 proficiency tiers)

| Attribute | Associated Skills |
|------|------|
| Tactics (TAC) | Melee Attack, Ranged Firearms, Demolitions, Tactical Command |
| Engineering (ENG) | System Hacking, Device Repair, Electronic Warfare, Starship Engineering |
| Mobility (MOB) | Zero-G Movement, Evasion, Stealth, Leap Charge |
| Perception (PER) | Environmental Scan, Threat Detection, Tracking, Initiative |
| Resilience (RES) | Damage Endurance, Will Resistance, Hypoxia Tolerance, Overload Limit |

Proficiency tiers: Untrained +0 / Proficient +2 / Expert +4 / Master +6.

### Difficulty Class Ladder

| DC | Label | DC | Label |
|:--:|------|:--:|------|
| 5 | Trivial | 16 | Challenging |
| 8 | Simple | 19 | Hard |
| 10 | Easy | 22 | Very Hard |
| 13 | Moderate | 25 | Legendary |

### Derived Attributes

| Attribute | Formula |
|------|------|
| Hit Points (HP) | RES × 2 + class base (Assault 12 / Engineer 8 / Medic 10 / Scout 8 / Heavy Gunner 14) |
| Oxygen Reserves (O₂) | RES × 2 + 5 |
| Armor Integrity (ARM) | ⌊RES × 1.5⌋ + equipment armor bonus (max 40) |
| System Hacking Cap | ⌈ENG × 0.5⌉ |
| Carry Capacity | (TAC + RES) × 2 (kg) |
| Defense (DEF) | 10 + MOB modifier + armor bonus |
| Initiative (INIT) | MOB modifier + 1d10 |

---

# Part Two: Game Master Content

---

## GM-1: Complete Check Mechanics and DC Setting Guide

### Core Principles for Setting DC

The Game Master (GM), when setting the Difficulty Class (DC), should follow these principles:

1. **Narrative first** — imagine the action's difficulty in the fictional world before choosing a DC
2. **55% baseline** — a specialized character (Attribute Modifier +3, Proficiency +2, total +5) facing a "Challenging" DC 16 succeeds 50% of the time. This is the system's design sweet spot.
3. **Environment is key** — the same action in crossfire is at least DC +3 versus a quiet environment.
4. **Failure should be interesting** — if failure means "nothing happens," consider lowering the DC or letting failure produce an interesting consequence.

### DC Quick-Setting Reference

| Situation | Suggested DC |
|------|:---:|
| Hack standard access (unnoticed) | 10 |
| Hack standard access (under fire) | 13 |
| Hack command-level system | 16 |
| Hack self-destruct (base DC 15, +2 per round elapsed) | 15–25 |
| Stabilized propulsion in Zero-G | 13 |
| Precise shot in Zero-G | 15 |
| Detect ambush (standard enemy) | 13 |
| Detect ambush (elite enemy stealth) | Contest Check |
| Stand up under 4G gravity | 15 |
| Find enemy vessel structural weak point | 13 (human vessel) / 16 (alien vessel) |

### Open DC vs. Hidden DC

| DC Disclosure Strategy | When to Use |
|------------|------|
| **Open DC** | When the character can reasonably assess the action's difficulty (e.g., "This door's lock looks military-grade — quite tricky.") |
| **Hidden DC** | When the character cannot assess the difficulty (e.g., alien device, unknown environment, enemy mental attack) |
| **Open result, then reveal DC** | When the player needs to learn the mechanic (e.g., "You need a 15 or higher — you just missed it by a bit.") |

---

## GM-2: Complete Combat Rules (with Enemy Behavior and AI Logic)

### Round Structure

Each full round consists of three phases:

```
1. Round Start Phase → ongoing effects trigger, environment changes, gravity state confirmed
2. Action Phase → in Initiative (INIT) order, characters spend Action Points (AP) to act
3. Round End Phase → resolve ongoing effects, status duration −1, oxygen consumption, countdown −1
```

### Action Points (AP) Full Cost Table

Each character has 3 AP per round.

| Action | AP | Notes |
|------|:--:|------|
| Short move ≤3 squares | 1 | ~4.5m at standard gravity |
| Medium move ≤6 squares | 2 | ~9m at standard gravity |
| Sprint move ≤9 squares | 3 | Attack at Disadvantage this round |
| Zero-G propulsion | 2 | Mobility (MOB) check DC 12, up to 4 squares |
| High-G move ≤2 squares | 2 | — |
| Climb/traverse obstacle | 2 | — |
| Standard attack | 2 | — |
| Quick shot (light weapon) | 1 | Damage −2 |
| Aimed shot | 2 | +3 to check. Cannot be used after moving |
| Melee attack | 2 | — |
| Suppressing Fire (Heavy Gunner) | 3 | Suppress an area |
| Throw | 2 | — |
| Operate terminal | 2 | Triggers hacking check |
| Open/close hatch | 1 | — |
| Cut through hatch (breach) | 3 | Triggers Engineering check |
| Pick up/swap item | 1 | — |
| Reload ammo | 1 | — |
| Use medical item | 2 | — |
| Revive downed ally | 2 | — |
| Gravity Takeover (Engineer) | 3 | Triggers Engineering check |
| Establish temporary airlock (Engineer) | 3 | — |
| Scan area (Scout) | 2 | — |
| Deploy drone (Scout) | 2 | — |
| Stabilize gravely wounded (Medic) | 2 | — |
| Adrenaline injection (Medic) | 1 | — |

### Reactions (1 per round)

| Reaction | Trigger | Effect |
|------|------|------|
| Readied Shot | Declared in advance | Immediately attack when enemy enters line of sight (at Disadvantage) |
| Dodge Reaction | When hit by an attack | Mobility (MOB) check vs. attacker's check value. Success → damage halved |
| Attack of Opportunity | Enemy leaves adjacent square | One free melee attack |
| Cover Reaction (Heavy Gunner) | When an ally is attacked | Suppressing fire forces the enemy to attack at Disadvantage |

### Initiative (INIT)

```
Initiative (INIT) = Mobility (MOB) modifier + 1d10
```

- Assault entering a new area on the first round: Initiative (INIT) roll with Advantage
- Ambushing side: +3
- Scout's successful reconnaissance: whole team +2
- Ambushed side: Disadvantage
- In chaos: −5

Enemies of the same type share one Initiative value — the Game Master (GM) rolls once for all same-type enemies.

### Surprise Round

The surprise round occurs before formal combat; only the ambushing side may act:

- Each ambushing character gains 1 AP (may only attack or move)
- Enemies are Disoriented
- After the surprise round, roll Initiative normally

**Breach Assault Effects:**

| Breach Method | Surprise Round Effect |
|---------|-----------|
| Demolition breach (coordinated) | All gain 2 AP; enemies Disoriented + Suppressed |
| Cutting breach | Standard surprise round. Nearest enemy may not be Disoriented |
| Hack-open door | Enemies completely unaware. Still requires one round to notice after surprise round |

### Attack Checks and Damage

**Attack Check:** 1d20 + Tactics (TAC) modifier + weapon proficiency bonus + circumstance modifier ≥ Defense (DEF)

**Damage Formula:**
```
Damage = weapon base damage + clamp(Attack Check − DEF, 0, +3)
```

**Critical (natural 20):** auto-hit + maximize base damage + add D6 effect.

> **Critical added-effect persistence & repair rules:**
> - **Weapon Damaged (effect 2):** Target's weapon is damaged, attack checks at Disadvantage until repaired. Repair requires spending 1 action on a Device Repair check (DC 15); non-Engineer classes may attempt with 2 actions (DC 18).
> - **Heavy Bleeding (effect 4):** −2 HP at the start of each round, naturally clots after 3 rounds; or a Medic may spend 1 action on a Medicine check (DC 15) to stop it immediately.
> - **System Short (effect 5):** Only affects mechanical/automated targets; effect equals Stunned for 1 round.

> **Damage Types:** This system defines seven damage types — ballistic, energy, explosive, biochem, fire, vacuum-burn, and psychic. Full interaction rules are in *Player Rulebook* 4.1. Of these, psychic damage comes from mental attacks, ignores the Armor Integrity (ARM) pool, is ineffective against mechanical and energy units, and on hit has a 50% chance to apply Disoriented.

### Full Status Effects

| Status | Trigger | Effect | Duration | Removal |
|------|------|------|:--:|------|
| Suppressed | Under suppressing fire | Movement halved. Attacks at Disadvantage when exposed from cover | 1–2 rounds | No longer suppressed |
| Disoriented | Gravity shift, explosion | All checks at Disadvantage. Cannot use reactions | 1 round | Round end |
| Critically Wounded | HP ≤ 25% | All checks at Disadvantage. Max 2 AP | Until HP restored | Healing |
| Poisoned | Biochem weapon | −1d4 HP per round. Checks −2 | 1d4 rounds | Medicine DC 15 |
| Burning | Fire (50%) | −1d6 HP per round. Cannot aim | 1d3 rounds | Mobility DC 12 |
| Suffocating | Oxygen depleted | −1d6 HP per round | Until oxygen restored | Pressurized area |
| Vacuum Exposure | ARM=0 in vacuum | −2d6 HP per round | Until leaving vacuum | Repair armor |
| Stunned | Electric weapon, neural attack, system short | Cannot perform any voluntary action (attack/move/skill), only passively endures. At end of each round may roll Will Resistance or Resilience (RES) check (DC 12) to recover early | 1 round | Auto-removed at round end, or pass check to remove early |
| Fatigued | Failed stand check under 3G+ High-G, or consecutive strenuous actions | All action checks −2 | Until 1 round after leaving High-G, or 1 action resting in pressurized area | Leave High-G and wait 1 round, or 1 action resting in pressurized area |

---

## GM-3: Enemy Garrisons and Encounter Construction

### Enemy Types

#### Human Garrison

| Subtype | CR | HP | ARM | DEF | Behavior |
|--------|:--:|:--:|:--:|:--:|------|
| Crewman (Mook) | 1/2 | 12 | 4 | 12 | Poorly trained. Tends to seek cover, call reinforcements |
| Guard (Standard) | 2 | 18 | 6 | 15 | Basic shipboard combat training. Moves on patrol routes |
| Marine (Elite) | 3 | 26 | 10 | 16 | Professional shipboard combat training. Uses cover, crossfire |
| Commander (Boss) | 5 | 40 | 14 | 18 | Commands other garrison. Has special tactical abilities |

#### Alien Creatures

| Subtype | CR | HP | ARM | DEF | Special Ability |
|--------|:--:|:--:|:--:|:--:|------|
| Brood Larva (Mook) | 1 | 10 | 2 | 11 | Swarm attack (more = bigger bonus) |
| Brood Warrior (Standard) | 2 | 18 | 4 | 14 | Acid spit (biochem), wall climbing |
| Brood Guardian (Elite) | 4 | 22 | 6 | 18 | Chitin armor (ballistic −2), melee rend 2d8 |
| Brood Brain (Boss) | 6 | 35 | 4 | 14 | Mind control (DC 18), summon larvae (1d4 every 2 rounds) |
| Silicate Construct (Special) | 5 | 30 | 12 | 18 | Crystal regeneration (recovers 2 HP/round), weakness: fire damage ×2 and ballistic damage ×1 no reduction |
| Energy Entity (Special) | 6 | 24 | 0 | 22 | Non-corporeal (50% immune to ballistic), passes through walls |

#### Automated Defense Systems

| Subtype | CR | HP | ARM | DEF | Special Rules |
|--------|:--:|:--:|:--:|:--:|------|
| Auto Turret (Standard) | 2 | 16 | 6 | 16 | Fixed, auto-fires at nearest enemy. Can be hacked (DC 15 disable / DC 20 turn to your side) |
| Laser Fence (Environment) | 1 | 8 | 2 | 10 | Crossing takes 2d6 energy. Can be hacked (DC 12) |
| Gas Releaser (Environment) | — | 10 | 0 | 8 | Radius 5 squares Poisoned. Can be hacked (DC 14) |
| Defense Robot (Elite) | 3 | 24 | 8 | 18 | Mobile, fire weakness (×1.5), immune to biochem |
| Blockade Turret Matrix (Boss) | 6 | 30 | 10 | 16 | Four linked turrets. Must destroy all or hack the core (DC 22) |

> For full ecology, weakness details, special behaviors, and encounter design tips for each enemy unit, see the *Monster Codex* (`assets/怪物圖鑑.md`).

### Enemy AI Behavior Priority

| Priority | Behavior | Trigger |
|:---:|------|------|
| 1 | Call reinforcements | First available action upon discovering intruders |
| 2 | Raise alarm | Within ≤3 squares of alarm panel |
| 3 | Seek cover | In open area with available cover |
| 4 | Attack highest threat | Those carrying heavy weapons, those hacking systems |
| 5 | Attack nearest target | No obvious high-threat target |
| 6 | Hold position | Ordered to guard a specific room |
| 7 | Retreat/flee | HP ≤ 25% and not Elite/Boss |

### Alarm State System

| State | Enemy Behavior |
|------|------|
| Not Triggered | Patrol routes, passive Perception (DC = 10 + Perception attribute) |
| Yellow Alert | Search mode. Enemy count ×1.5. Perception checks with Advantage |
| Red Alert | Engaged mode. Enemies know player positions. Reinforcements arrive every 1d4 rounds |
| Self-Destruct Alert | Partial retreat, partial last stand. Morale check DC +5 |

### Challenge Rating (CR) and Encounter Level (EL)

```
CR ≈ (average damage output × HP) ÷ 35
EL = Σ(all enemy CR)
```

| EL | Difficulty | Expected Resource Cost | Use Scenario |
|:--:|------|:--:|------|
| 1–2 | Simple | Almost none | First deck, patrol boat |
| 3–4 | Standard | 25% | Main corridor, general area |
| 5–6 | Hard | 50% + likely meds | Key area entrance |
| 7–9 | Very Hard | 75% + someone critically wounded | Command area, boss fight |
| 10+ | Hopeless | High chance of casualties | Final defense, optional challenge |

### Five-Phase Mission Recommended Encounters

| Phase | Recommended EL | Suggested Enemy Composition |
|------|:--:|------|
| Breach | 1–2 | 1–2 sentries |
| Enter | 3–4 | Patrol (2–3 Guards + possibly 1 turret) |
| Advance | 4–6 (split into 2–3 fights) | Different each deck — mixed enemy types |
| Objective | 5–8 | Elite garrison + Boss/special enemy |
| Extract | 3–5 (pursuit) | Remaining garrison + automated defense systems |

### Enemy Quick-Generation Template

| Tier | Base Attribute | HP | DEF | ARM | Attack Bonus | Damage |
|:---:|:---:|:--:|:--:|:--:|:---:|:---:|
| Mook | 8–10 | 8 | 10 | 2 | +1 | 1d6 |
| Standard | 10–12 | 14 | 10+mod | 4 | +2 | 1d8+1 |
| Elite | 12–14 | 22 | 12+mod | 8 | +4 | 2d6+2 |
| Boss | 14–16 | 30 | 14+mod | 12 | +6 | 2d8+3 |

---

## GM-4: Complete Gravity Environment Rules

### Check Impact of Five Gravity States

| Gravity State | Move Cost | Mobility Check | Melee | Ranged | Special |
|:---:|:---:|:---:|:---:|:---:|------|
| Standard 1G | Normal | Normal | Normal | Normal | — |
| Zero-G 0G | Propel 2AP/4 sq | Disadvantage¹ | Disadvantage | Normal (ballistic +2) | 3D orientation |
| Low-G 0.1–0.5G | Halved | Normal | Disadvantage | Normal | Jump ×2 |
| High-G 2–5G | 2G normal; 3G+ doubled | 3G+ Disadvantage | 3G phys −2; 4G+ Disadvantage | 5G unusable | 3G+ each round RES DC 12 or Fatigued |
| Variable-G | Varies each round | ³ | ³ | ³ | Random state each round |

> ¹ If proficient in Zero-G Movement, no Disadvantage.  
> ³ Perception (PER) + Environmental Scan (DC 13) to predict this round's gravity state.

### High-G Level Effects

| Multiplier | Extra Effect |
|:---:|------|
| 2G | Base rules, no extra penalty (optional adaptation check DC 10) |
| 3G | Physical attacks (melee/ballistic/explosive) check −2; each round end Resilience (RES) DC 12 or Fatigued |
| 4G | Each square move costs 2 AP; staying upright requires Resilience (RES) DC 15 each round |
| 5G | Cannot stand, ranged weapons unusable, only melee or crawling |

### Variable-G Per-Round Change Table

| d6 | This Round's Gravity |
|:--:|------|
| 1 | Zero-G (0G) |
| 2 | Low-G (0.3G) |
| 3 | Standard gravity (1G) |
| 4 | High-G (2G) |
| 5 | Extreme High-G (4G) |
| 6 | GM choice or maintain previous round |

Adaptation check = Mobility (MOB) attribute check (DC by change magnitude: same 8 / 1–2 levels 12 / 3–4 levels 16).

### Gravity Takeover (Engineer)

| DC | Effect |
|:--:|------|
| 15 | Successful takeover — choose one gravity switch |
| 20 | Precise control — choose two at once |
| 25 | Global takeover — applies to the entire enemy vessel simultaneously |
| Failure | System locked for 2 rounds |
| Critical Failure | That area becomes Variable-G for 1d6 rounds, cannot retake over |

**Gravity Switch Options:** Zero-G, High-G (3G), Gravity Inversion (180°), Local Gravity Field (3×3 squares), Gravity Wave (0G ↔ 3G oscillation).

---

## GM-5: Self-Destruct Countdown Mechanic

### Countdown Duration

| Vessel Type | Countdown (rounds) |
|---------|:---:|
| Patrol boat | 5 |
| Destroyer | 8 |
| Cruiser/Capital ship | 12 |
| Carrier/Flagship | 15 |

The Game Master (GM) may secretly roll 2d6+3 (range 5–15) or set a fixed value by vessel type.

### Self-Destruct Hack DC (Engineer-only)

Uses a single escalating model, fully consistent with *Player Rulebook* 3.2 Engineer ability:

- **Base Difficulty Class (DC):** 15
- **Escalation rule:** Each round elapsed, DC +2 (i.e., DC = 15 + elapsed rounds × 2)
- **Each attempt:** consumes 1 System Hacking cap + 1 round (no other actions during hack)
- **Success effect:** Self-Destruct Countdown delayed by 1d4 rounds (timer paused)
- **Critical Failure (natural 1):** Countdown halved (rounded down)
- **Engineer attempt:** DC −3 (minimum 12)
- **Non-Engineer class attempt:** DC +3, and even on success can only delay, cannot "fully disable"
- **Ultimate feat "System Master":** DC no longer increases over time (fixed 15)
- **Teamwork:** Primary executor is Engineer; each helper (System Hacking proficient or above) gives +2 assist bonus (max +4); with 2 helpers, a successful hack can "fully disable" self-destruct

> **Design baseline:** At start DC 15 (specialized Engineer ~55% success); if delayed to round 5, DC has risen to 25 (~5% success), highlighting the urgency of "hack early."

### Special Rules During Self-Destruct

- **Time pressure:** Announce countdown aloud each round end. Players have 30 seconds (real time) to declare actions — timeout means that character takes "full retreat"
- **Accelerate action:** +1 AP this round, but all checks −3
- **Abandon objective:** Move speed ×2, no attack or interaction checks needed. But mission fails
- **Last door:** The final hatch on the escape route is always locked (DC 15 + 1d6)
- **Final round before explosion:** Those not within 3 squares of an airlock/extraction point — die (no save)

### Enemy Behavior During Self-Destruct

| Countdown Phase | Enemy Behavior |
|---------|------|
| > 50% | Some enemies retreat (1d4 leave each round) |
| 25–50% | Only Elite and Boss remain on the field |
| < 25% | Remaining enemies "desperate last stand" — do not flee, attack +3 |

---

## GM-6: Oxygen and Armor Management

### Oxygen Consumption Rate

| Activity Intensity | Consumption | Notes |
|:---:|:---:|------|
| Stationary/standby | 1 point per 3 rounds | Holding position, waiting, scouting |
| Normal action | 1 point per round | Moving, searching, operating equipment |
| Strenuous action | 2 points per round | Combat, running, hauling heavy loads |
| Armor breach (vacuum) | ×2 | All consumption doubled |

### Suffocation Rules

Oxygen Reserves drop to 0 → Suffocating condition. Each round Resilience (RES) attribute check:

- Initial DC: 10
- DC +2 each round
- Success: no suffocation damage that round
- Failure: take 1d6 suffocation damage + all checks at Disadvantage (until oxygen resupplied)

Over 3 rounds without oxygen → cumulative survival rate below 16% (even for Resilience (RES) +2 characters).

### Armor Breach Impact

| Environment | Impact |
|------|------|
| Pressurized environment | Mobility (MOB) check at Disadvantage. +2 damage per hit taken |
| Vacuum environment | Above + oxygen consumption doubled + automatic 1d4 HP loss per round |
| High-risk environment | Above + each round Resilience (RES) DC 15 or take environment-specific damage |

---

## GM-7: Special Combat Scenarios

### Breaching Combat

| Breach Method | AP | Check | Effect |
|---------|:--:|:--:|------|
| Plasma Cut | 3 | ENG DC 12 | Standard breach. Cutting sound can be heard (PER DC 14) |
| Demolition Breach | 2 each | ENG DC 10 | 3×3 square 4d6 explosion behind door + Disoriented. Ship-wide Red Alert |
| Hack-open Door | 3 | ENG DC 18 | Silent. Full surprise round. No alarm triggered |
| Force Open | 2 | TAC DC 15 | Quick breach. Assault takes 1d4 impact damage |
| Maintenance Panel | 3 | ENG DC 14 | Bypass hatch — emerges from the side |

### Auto Turret Hacking

| Action | DC | AP | Effect |
|------|:--:|:--:|------|
| Disable | 15 | 2 | Stops operating |
| Turn to your side | 20 | 3 | Attacks enemies. Maintain each round with ENG DC 12 |
| Overload self-destruct | 18 | 2 | Explodes next round (3d6, radius 2 squares) |

### Extraction Combat

| Action | AP | Effect |
|------|:--:|------|
| Tactical Retreat | 2 | Move 6 squares. DEF +2 |
| Cover Retreat (Heavy Gunner) | 3 | Whole team retreats without triggering Attack of Opportunity |
| Set delayed explosive (Engineer) | 2 | Explodes next round (3d6) to block pursuers |
| Seal hatch (Engineer) | 2 | Pursuers need ENG DC 18 or demolition to pass |
| Smoke screen cover | 1 | Radius 3 squares vision blocked for 2 rounds |
| Drag gravely wounded | 3 | Drag 3 squares |

---

## GM-8: Lore and Setting

### Era: Year 378 of the Rift Epoch

Humans have been in the interstellar colonization age for nearly four centuries. Faster-than-light travel — the Jump Drive (JD) — enabled hundreds of colony star systems. But each jump leaves a tiny "rift" in the spacetime structure, and as these rifts accumulate... something begins to watch humanity from beyond.

The Lyra Great Rift — a catastrophic collective jump accident — opened a stable rift, letting the energy beings "the Lumen" enter the human universe en masse for the first time, igniting the "Rift Wars" that swept the galaxy's four great powers.

### Five Great Factions

**Player Faction: Terran Stellar Concord (TSC)**

- Largest interstellar human polity, controls ~140 colony systems
- Military: Concord United Fleet (CUF)
- Core value: "Unity is strength"

**Hostile Faction One: Free Star Alliance (FSA)**

- A human separatist polity of ~30 outer-ring colonies
- More aggressive vessel design — sacrificing defense for over-spec firepower
- Internally chaotic and asymmetrical, reliant on traps and ambushes
- Crew usually fanatical volunteers, using terrain for guerrilla warfare

**Hostile Faction Two: Kislak Brood**

- A biological hive intelligence spanning dozens of star systems
- Vessels are living organisms — bony outer shell, muscle-fiber corridors, sphincter doors, lymphatic circulation
- Spore air (non-brood who inhale must resist nausea with Resilience (RES) DC 10)
- Fire weakness (fire attacks deal ×2 to brood structure)
- Vessels have an "immune response" — after prolonged intrusion, the hull releases antibody creatures
- One brood member discovering intruders = whole vessel's creatures know

**Hostile Faction Three: Crystal Harmony**

- Ancient silicon civilization, consciousness exists within crystal structures
- Vessels made of living crystal, walls translucent and self-glowing
- Structure heals (seals one breach every 1d4 rounds)
- Uneven gravity (different rooms have random gravity distribution)
- Resonant communication — hacking requires special frequency modulator
- Motivation: views organic life as "noise" that must be "muted"

**Hostile Faction Four: the Lumen**

- Pure energy life from rift space
- No physical form — composed of condensed plasma and EM fields
- Vessels are energy-field regions, no solid walls, no gravity, no air
- Uncommunicable (language is EM spectrum patterns)
- Physical laws distorted within their vessels
- Time flow may differ from outside

**Hostile Faction Five: the Remnant**

- Autonomous warships that survived the First AI Rebellion
- Fully controlled by artificial intelligence, no crew
- Internal structure dynamically reconfigures — walls move
- Self-learning — the same attack strategy won't work twice
- Hacking the central AI (ENG DC 25) is the only way to shut down all defenses
- The vessel is the enemy; the enemy is the vessel

### Player Mothership: Arbitrator

- Type: Cerberus-class Assault Cruiser
- Length: 487 meters
- Crew: 842
- Boarding assault teams: 4 standing squads (5 each)
- Captain: Colonel Elena Moro

**Captain Personality:** Calm and composed but not without humor. Once lost an entire ship's crew in a campaign — she was the sole survivor. Has a near-motherly protectiveness over every boarding team member, but never stops them from doing their duty. Favorite saying: "Come back on time."

**Mothership Status:**

| Status | Impact |
|------|------|
| Stable | Extraction DC −2. Comms normal |
| Pressured | Extraction DC normal. Mothership under fire |
| Heavy Damage | Comms cut. Extraction point may shift — Perception (PER) DC 15 to find correct location |
| Extracting | Mothership has left. Must find escape pod or crash-land on your own |

### Historical Timeline (Key Events)

| Year | Event |
|------|------|
| 380 years pre-Rift | Jump Drive invented |
| 200 years pre-Rift | First contact with alien civilization ruins |
| 50 years pre-Rift | Stellar Concord (TSC) founded |
| Rift Year 1 | Lyra Great Rift. Rift Wars erupt |
| Rift Year 5 | Free Star Alliance (FSA) declares independence |
| Rift Year 12 | First encounter with Kislak Brood |
| Rift Year 45 | Crystal Harmony awakened by deep mining |
| Rift Year 89 | First recorded appearance of the Lumen |
| Rift Year 215 | First AI Rebellion |
| Rift Year 378 | **Now** — four-sided war at full stalemate |

---

## GM-9: Five-Phase Boarding Mission Structure

### Phase One: Breach

Players choose a breach point — this is a tactical decision:

| Breach Point | Advantage | Disadvantage |
|--------|------|------|
| **Engineering Bay** | Close to power systems; can quickly disable engines | Engine noise masks enemy movements; high-temperature hazard |
| **Cargo Hold** | Large space, few garrison; recoverable supplies | Farthest from key objectives; may lead to dead ends |
| **Hull near Bridge** | Closest to command systems | Densest garrison; fastest alarm trigger |
| **Observation Pod** | Usually unmanned; can observe internal layout | Fragile structure — breach may cause decompression explosion |
| **Any Point** | Surprise | You don't know what's behind the wall |

**Assault Pod Types (Reputation-unlocked):**

| Type | Effect | Reputation |
|------|------|:---:|
| Standard Assault Pod | Basic ejection — Perception DC 14 to detect | Unknown |
| Stealth Assault Pod | Radar-absorbing coating — Perception DC 20 | Trust |
| Accelerated Assault Pod | Breach time halved (1 round vs 2) | Respect |
| Heavy Assault Pod | Can carry extra 50kg supplies | Legendary |

### Phase Two: Enter

First-encounter design principles:

1. The first fight should be simple — let players adapt to the environment
2. Provide at least two route choices (direct vs detour)
3. Create the feeling that "the enemy ship is alive" — corridor vibrations, distant alarms, strange smells from vents

**Cumulative Alarm System:**

The Game Master (GM) secretly tracks "alarm points":

| Action | Alarm Points |
|------|:---:|
| Demolition breach | +3 |
| Cutting breach | +1 |
| Enemy reinforcement call succeeds | +2 |
| Trigger automated defense system | +2 |
| Failed system hack | +1 |

| Alarm Points | Alarm Level | Effect |
|:---:|:---:|------|
| 0–2 | No alarm | Enemies patrol normally |
| 3–5 | Yellow Alert | Search mode. Count ×1.5. Perception Advantage |
| 6–8 | Red Alert | Engaged mode. Reinforcements every 1d4 rounds |
| 9+ | Self-Destruct triggered | Commander judges vessel lost |

### Phase Three: Advance

**Route Choice Types:**

| Route | Risk | Reward |
|------|:---:|:---:|
| Main corridor | High — most garrison | Fastest to objective |
| Maintenance passage | Mid — narrow, possible auto-traps | Bypass garrison. But single-file only |
| Hull climb | High — vacuum exposure | Fully bypass internal defenses. But requires Engineer to build airlock |

**Three-Dimensional Deck Design Principles:**

- Small vessel: 2–3 decks, linear layout
- Mid vessel: 4–6 decks, mesh-connected (elevators, shafts, stairs)
- Large vessel: 8+ decks, provide deck map for navigation

### Phase Four: Objective Complete

| Mission Type | Completion Condition | Time Frame | Base Reward |
|---------|------|:---:|------|
| Demolition | Place explosives in Engineering Bay/Reactor Room (needs 2 rounds) and extract beyond blast radius | Medium | XP +5, Reputation +1 |
| Data Raid | Data download at Bridge/Data Center (Perception (PER) DC 13, needs 3 rounds) | Long | XP +5, Reputation +2 |
| Decapitation | Eliminate Commander (Boss-level enemy). Optional: bring back Commander's tactical helmet as proof | Short | XP +5, Reputation +3 |
| Captive Rescue | Find captive (Perception (PER) DC 13 search), escort to extraction point | Variable | XP +5+3, Reputation +2 |
| Special Recovery | Find target item (Perception (PER) DC 15 search) and bring back to mothership | Variable | XP +5+2, Reputation +1–3 |
| Total Paralysis | Control Bridge + Engineering Bay + all key system rooms | Very Long | XP +5+5, Reputation +5 |

### Phase Five: Extract

Four extraction methods:

| Method | Requirement | Risk |
|------|------|:---:|
| Return via original route | Remember the route | Enemies may block the original path |
| Alternate route | Perception (PER) DC 15 to find | Unknown environment |
| Hull extraction | Engineer builds airlock | Vacuum exposure |
| Seize escape pod | Find enemy vessel escape pod bay | May already be all used |

**Mothership Status Impact on Extraction:**

- Stable → fire support, Extraction DC −2
- Pressured → normal extraction
- Heavy Damage → comms cut. Extraction point shifted. Perception (PER) DC 15 to find mothership
- Extracting → mothership has left. Must find escape pod or crash-land on nearby celestial body

---

## GM-10: Reputation and Mothership Support

### Mothership Support Types

| Support | Reputation | Effect | Usage Limit |
|------|:---:|------|:---:|
| **Satellite Scan** | Recognition | Get external structure scan of enemy vessel — see all decks and large structures | 1 per mission |
| **Fire Support** | Trust | Mothership fires one barrage at extraction route during Extract phase — clears pursuers | 1 per mission |
| **Orbital Bombardment** | Legendary | Precise orbital strike on specific enemy vessel area (used before boarding) — destroys all defenses in area | 1 per 2 missions |
| **Decoy Signal** | Respect | Project a fake boarding signal on the other side of enemy vessel — disperses the garrison (EL −2) | 1 per mission |
| **Emergency Transport** | Trust | During emergency extraction can transport one team member back to mothership (HP to 0 but survives) | 1 per mission |
| **Reinforcement Boarding Team** | Respect | Call another assault team for support — gain 2 AI allies for 3 rounds | 3 per campaign |

> **AI Ally Rules:** For full data, action options, and the five preset templates (Kirk/Ada/Lin/Ghost/Bastion) of the 2 AI allies summoned by "Reinforcement Boarding Team," see **GM-19: AI Ally System** in this book.

---

## GM-11: Encounter Design and Difficulty Balancing

### Encounter Balance Quick Reference

| Player Count | Recommended EL | Mook Count | Elite Count | Boss |
|:---:|:---:|:---:|:---:|:---:|
| 1 (Lone Wolf) | 1–3 | 1–3 | 0–1 | 0–1 (CR below 3) |
| 2–3 | 3–6 | 2–5 | 1–2 | 0–1 (CR below 5) |
| 4–6 | 5–10 | 3–8 | 2–4 | 1 (CR 6+) |

### Dynamic Difficulty Adjustment

| Problem | Too Easy | Too Hard |
|------|------|------|
| Enemy HP | +25% | −25% |
| Attack bonus | +2 | −2 |
| Count | Reinforcements arrive early | Reduce reinforcements |
| Gravity | Enemy Engineer adjusts | Players find gravity panel |

### General Difficulty Quick Reference

| DC | Use Scenario |
|:--:|------|
| 8 | Make players feel competent |
| 10 | Slight challenge |
| 13 | Standard challenge |
| 15 | Difficult challenge — specialized character needs a bit of luck |
| 16–18 | Hard challenge — even experts must give their all |
| 20 | Very hard — needs teamwork and good luck |
| 22+ | Nearly impossible — ensure failure has interesting consequences |

### Random Encounter Table (improvised insertion during Advance phase)

When players explore during the "Advance" phase, the Game Master (GM) may roll **1d8** to improvise an encounter, or choose the result that best fits the current story. The table below is standard difficulty (Encounter Level EL 3–5); if higher or lower difficulty is needed, adjust enemy count per the "Vessel Type and Difficulty Modifier" below.

| 1d8 | Encounter Composition (EL ~3–5) | Notes |
|:--:|------|------|
| 1 | 2 Alliance Guards (Standard) | Common human-vessel patrol |
| 2 | 1 Auto Turret (Standard) + 1 Alliance Crewman (Mook) | Corridor defense node |
| 3 | 3 Brood Larvae (Mook) + 1 Brood Warrior (Standard) | Alien bio-vessel only |
| 4 | 1 Alliance Marine (Elite) | Single strong enemy — fits Lone Wolf mode |
| 5 | Gas Releaser (Environment) + 2 Alliance Crewmen (Mook) | Environmental hazard + enemy |
| 6 | 1 Commander Adjutant (Standard+) + 1 Guard (Standard) | Half-boss-level threat |
| 7 | Laser Fence (Environment) blockade + 2 Guards (Standard) | Need to hack or detour |
| 8 | GM's choice | Most dangerous combination in current story; or trigger special event |

**Vessel Type and Difficulty Modifier:**

| Vessel Type | Modifier |
|------|------|
| Human/Alliance vessel | Standard (as above) |
| Insectoid Bio-Ship | Replace "Crewman/Guard" in composition with "Brood Larva/Warrior"; count +1 |
| Silicon Crystal Ship | Reduce enemy by 1, but add 1 environmental hazard (crystal regen walls block path) |
| Energy Being Ship | Replace 1 enemy with "Energy Entity (Special)"; non-corporeal, hard to hit |
| AI Unmanned Vessel | Replace with "Defense Robot (Elite)" or extra turrets; whole vessel networked — destroying one summons reinforcements |

**Difficulty Fine-Tuning:** If few players (Lone Wolf) or weak party, downgrade Elite to Standard, halve Mooks; if strong party, upgrade 1 Mook to Standard or add 1 turret.

---

## GM-12: Map Design Guide

### Node-Connection Model

Use the **Node-Connection Model** to design enemy vessel maps:

| Node Type | Icon Suggestion | Notes |
|---------|:---:|------|
| Key Room | ⬛ | Objective area, control room, Bridge |
| Corridor Node | ⬜ | Passage intersection, corner |
| Environmental Hazard | ⚠ | Vacuum breach, radiation zone, high-temp zone |
| Defense Node | 🛡 | Turret position, force field, laser fence |
| Extraction Point | 🚀 | Airlock, escape pod |

### Deck Count Suggestion

| Vessel Type | Decks | Nodes | Key Rooms |
|---------|:---:|:---:|------|
| Patrol boat | 1–2 | 8–12 | Bridge, Engineering Bay, Airlock ×1 |
| Destroyer | 2–4 | 15–25 | Bridge, Engineering Bay, Barracks, Data Center, Airlock ×2 |
| Cruiser | 4–6 | 25–40 | Above + Lab, Brig, Command Deck |
| Carrier | 6–10 | 40–60 | Above + Hangar, multiple Data Centers, Flight Deck |
| Alien Vessel | By species | By species | Adjust to species' organ/structure |

### Passage Logic

- Main corridor: 2 squares wide (3m), two-way
- Secondary corridor: 1 square wide (1.5m), one-way
- Maintenance passage: 1 square wide, requires climb or crouch. Shortcut — but single-file only
- Vertical passage: elevator (mechanical, may be offline), emergency ladder (manual), cable shaft (climb check)

### Environmental Hazard Distribution Suggestion

- At least one environmental hazard every 5–8 nodes
- First hazard should be early in the mission — let players learn the mechanic
- Place hazards on the mandatory path to objectives — force tactical decisions
- Leave detour options — make the Scout's route-planning valuable

---

## GM-13: Pacing Control

### Five-Phase Emotional Curve

```
       Tension
        ↑
        │          ╱‾‾‾‾‾‾‾╲
        │         ╱  Objective  ╲
        │        ╱             ╲   Extract
        │  Enter ╱               ╲╱‾‾‾‾
        │   ╱  ╱  Advance
        │  ╱  ╱
        │ ╱  ╱
    Breach╱  ╱
        └──────────────────────────→  Time
```

- **Breach:** Low tension — establish atmosphere. Describe enemy vessel exterior, space environment
- **Enter:** Tension rising — first firefight. Shouldn't be too hard
- **Advance:** Fluctuating rise — different challenge per deck. Give brief breather after sustained tension
- **Objective Complete:** Highest tension — boss fight or final challenge. Trigger self-destruct here
- **Extract:** Sustained tension — chase under time pressure. The final hatch is the climax

### Self-Destruct Trigger Timing

| Trigger Method | Effect | Usage Advice |
|---------|------|------|
| After objective complete | Last garrison in objective area eliminated → Commander starts self-destruct | Most natural trigger |
| Alarm 9+ | Alarm system accumulates to 9 points → auto-trigger | Punitive trigger — use cautiously |
| Story trigger | Specific story event triggers (e.g., seizing key item) | For climax pacing control |
| Player detonation | Players deliberately detonate reactor as extraction cover | Reward creativity — but consequences are theirs |

### Self-Destruct Countdown Duration Suggestion

- Short scenario (one-round game) — use fixed 5–8 rounds
- Mid scenario — start at 8–12 rounds, allow Engineer to extend
- Long scenario — start at 12–15 rounds, multiple hack chances

---

## GM-14: Gravity Narrative

### Using Gravity to Create Dramatic Scenes

| Scene | Gravity Setting | Narrative Effect |
|------|------|------|
| **Gravity Trap** | Gravity suddenly shifts to 4G after players enter room | All pinned. Must crawl to find gravity control terminal |
| **Gravity Corridor** | Long corridor with gravity in three segments: 0G / 1G / 3G | Tactical obstacle course testing movement skills |
| **Inversion Pursuit** | Enemy Engineer inverts gravity during extraction | Ceiling becomes floor — complete loss of orientation |
| **Zero-G Pincer** | Enemies surround from six directions (3D space) | Unprecedented tactical dilemma |
| **Gravity Wave** | 0G and 3G alternate each round | Creates chaotic but predictable combat rhythm (favors prepared players) |
| **Sacrifice Gravity** | Cut gravity to stop enemy pursuit | Players also affected — but they're prepared |

---

## GM-15: Oxygen Management — Simplified System

The Game Master (GM) may optionally use a simplified **5-level oxygen tracking** instead of precise round counting:

| Oxygen Level | Remaining O₂ | Player Perception | GM Hint |
|:---:|------|------|------|
| 5 | Plenty | "Oxygen reading normal" | No pressure |
| 4 | 75% | "Starting to notice consumption" | Remind players they can find supplies |
| 3 | 50% | "Time to find a supply station" | Place oxygen supply nearby |
| 2 | 25% | "Oxygen warning light flashing" | Tension. Starts affecting decisions |
| 1 | 10% | "Breathing getting difficult" | If in vacuum — emergency |
| 0 | Depleted | Suffocation begins | −1d6 HP per round |

### When to Start Tracking

- Only start tracking oxygen when players enter a **vacuum zone**
- Within pressurized zones — pause tracking
- If the whole mission is in pressurized zones — no tracking needed at all

---

## GM-16: Solo Play Guide

### Encounter Adjustment

- All enemy counts halved (minimum 1)
- Self-Destruct Countdown extended 50%
- Hacking cap ×2
- Oxygen Reserves ×1.5

### Wave Difficulty Curve

Solo players cannot sustain consecutive high-intensity encounters:

```
Difficulty
  ↑   ╱╲      ╱╲
  │  ╱  ╲    ╱  ╲
  │ ╱    ╲╱╱    ╲╱╲
  │╱              ╲
  └──────────────────→  Time
```

- After each high-intensity encounter — give a breather (safe room or enemy-free exploration area)
- Before self-destruct starts — ensure players have enough resources
- After objective complete — provide oxygen supply or medical resources before starting extraction

### Dedicated Stealth System (optional in solo mode)

| Detection Level | Player State | Enemy Reaction |
|:---:|------|------|
| 0 | Fully hidden | Enemies patrol normally |
| 1 | Suspicious signs (footprints, open door) | Enemies alert — Perception (PER) check Advantage |
| 2 | Spotted (briefly) | Enemies search last seen location |
| 3 | Confirmed (seen and identified as intruder) | Trigger alarm |
| 4 | Engaged | Red Alert |

**Noise Radius:**

- Silent action (successful Stealth): 0 squares
- Normal move: 3 squares (audible)
- Running: 6 squares
- Gunshot (unsuppressed): entire deck
- Explosion: whole vessel

---

## GM-17: Improvisation Guide

### Core Response Principles

| Principle | Notes | Example |
|------|------|------|
| **"Yes, and..."** | Player idea works + add interesting consequence | Player wants to use maintenance pipes to bypass garrison → "Yes, and the pipes also have unmarked cables — success on Engineering (ENG) check lets you also disable this deck's comms" |
| **"Yes, but..."** | Player idea works + cost or risk | Player wants to shoot gravity plate to make enemies float → "Yes, but you and allies are also affected. And the broken gravity plate may trigger chain reaction" |
| **"No, but..."** | Player idea infeasible + alternative | Player wants to remotely disable self-destruct → "No, self-destruct is an independent system with no remote access. But you can find the actual location of the self-destruct control room from the terminal" |

### Examples of Responding to Unexpected Player Actions

| Unexpected Situation | Response Strategy |
|---------|------|
| Player wants to bypass all internal defenses via hull | Hull climb = full vacuum. But at the objective area still must cut armor to enter — garrison inside already knows you're coming |
| Player tries to negotiate with enemy Commander | Alliance Commander may negotiate (Tactical Command DC 20). Brood and Lumen cannot communicate. AI may pose logical paradox |
| Player wants to blow up the whole ship instead of boarding | Mothership Commander: "We need that ship's data. Board it." But in emergencies — orbital bombardment is an option (needs Legendary reputation) |
| Player splits forces | Each split side keeps same encounter intensity — but no ally support. High drama but also high risk |

### Improvisation Resource Pool

When you need to quickly generate content, roll 1d6 from the tables below:

**NPC Names:** Kane, Vera, Sergeant Thorne, Dr. Echo, Ghost, Bastion

**Environmental Hazards:** Radiation leak, gravity anomaly, arc discharge, coolant smoke, pipe burst, structural collapse

**Unexpected Finds:** Enemy corpse (with map marks), unencrypted data pad, abandoned med station (with supplies), stuck maintenance robot (reprogrammable), unexploded torpedo, enemy personal item (with photo)

**Complications:** Two enemy factions infighting, discovered captive needing rescue, comms receive friendly fleet distress signal, mothership orders immediate extract (objective incomplete), traces of another assault team that boarded earlier than you, enemy Commander proactively offers surrender — with conditions

**Moral Dilemmas:** Completing objective sacrifices captives, saving captives fails objective, enemy Commander holds civilians hostage, self-destruct will blow up whole ship (including non-combatants aboard), recovered tech may be used by mothership to develop worse weapons, teammate trapped — do you risk going back to save them?

---

## GM-18: Optional Rules and Variants

### Hardcore Mode

- No Lone Wolf bonus (even for solo players)
- Self-destruct hack can only delay (full disable DC 30)
- Armor breach cannot be repaired during mission
- Oxygen depletion = instant death (no suffocation check — dies after 3 rounds)
- For: games seeking maximum tension

### Hero Mode

- One "Heroic Moment" per mission — auto-pass one check (player narrates how)
- All characters' max HP +10
- Self-Destruct Countdown extended 50%
- For: narrative-driven games, new players

### Campaign Mode

- Mothership upgrades with campaign progress (more supplies, better assault pods)
- Enemies learn — same species' vessels, defense strategies players encounter evolve
- After ally death — introduce new character starting at level 1 but with veteran legacy bonus (XP gain +50%)
- Mothership relationship changes over time — Captain may be reassigned, new Captain may have different style

### Zero-G Specialization Variant

- Add "Zero-G Combat" skill (Mobility (MOB) attribute)
- Allow all classes to gain proficiency in Zero-G (rather than only trained avoid penalty)
- New Zero-G tactics: spinning shot, inertial drift, 3D pincer
- For: space-focused campaigns

---

## GM-19: AI Ally System

When players call mothership support "Reinforcement Boarding Team" (Reputation Respect, 3 per campaign), or need a companion in solo mode, the **AI Ally** that appears uses the rules in this section. AI Allies are autonomous combat units controlled by the mothership AI — reliable but lacking human improvisation.

### Simplified Action Rules

AI Allies automatically gain **3 Action Points (AP)** per round, and the player (or Game Master (GM)) decides their single primary action:

| Action Option | Notes |
|---------|------|
| Attack | One standard attack on nearest/highest-threat enemy in line of sight (values in template below) |
| Cover | Occupy cover, grant adjacent ally Defense (DEF) +1 (lasts until its next turn) |
| Heal (Medic-type only) | Restore 2d6 HP to one wounded ally |
| Support (Engineer/Scout-type only) | Engineer-type can make one DC 15 hack; Scout-type can reveal enemy situation in an adjacent area |
| Follow | Move to ally and enter defensive stance (no active attack) |

AI Allies **do not independently perform special actions requiring class abilities like Gravity Takeover or self-destruct hack** — they specialize in basic firefights and support. AI Allies disappear when they die (HP to 0), no permanent casualties.

### Five AI Ally Templates

| Name | Role | HP | DEF | INIT | Attack | Special |
|------|------|:---:|:---:|:---:|------|------|
| **Kirk** | Assault | 20 | 13 | +1 + 1d10 | Assault Rifle +4 (2d6+2 ballistic, 15/60m) | Melee specialist: melee +1d6 |
| **Ada** | Engineer | 16 | 12 | +0 + 1d10 | Plasma Cutter +3 (1d8 energy, melee) | Can hack DC 15 (disable turret/access); establish temporary airlock |
| **Lin** | Medic | 18 | 12 | +0 + 1d10 | Med Pistol +2 (1d6 energy, non-lethal) | Can heal one ally 2d6 HP per round; has 1 Adrenaline (ignores Critically Wounded 1 round) |
| **Ghost** | Scout | 16 | 13 | +2 + 1d10 | Marksman Rifle +3 (1d10 ballistic, 30/100m) | Threat Detection Advantage; can reveal adjacent area enemy situation (Perception (PER) check DC 12) |
| **Bastion** | Heavy Gunner | 24 | 14 | +0 + 1d10 | Squad MG +3 (2d8 ballistic, 20/80m) | Suppressing Fire: spends whole turn, designates area, enemies there cannot act next round (equals player Heavy Gunner ability) |

> If players need a non-preset AI Ally, the Game Master (GM) may use the "Enemy Quick-Generation Template" from GM-3 at "Standard" tier and grant it one corresponding support ability.

---

# Part Three: Appendix

## Glossary (Full Version)

| Traditional Chinese Full Name | Abbr. | Notes |
|-------------|:---:|------|
| Tactics | TAC | Core attribute for close combat, weapon use |
| Engineering | ENG | Core attribute for technical operation, device hacking |
| Mobility | MOB | Core attribute for movement ability |
| Perception | PER | Core attribute for environmental awareness and tactical anticipation |
| Resilience | RES | Core attribute for physical endurance and willpower |
| Difficulty Class | DC | Target number a check must reach |
| Action Points | AP | Points spendable per round |
| Hit Points | HP | Character's ability to absorb damage |
| Armor Integrity | ARM | Remaining durability of armor |
| Defense | DEF | Number enemy attacks must reach against you |
| Initiative | INIT | Determines action order in combat |
| Advantage | — | Roll 2d20, take higher |
| Disadvantage | — | Roll 2d20, take lower |
| Margin of Success | MoS | Gap between winner and loser in contested check |
| Experience Points | XP | Points for character growth |
| Challenge Rating | CR | Relative threat of an enemy unit |
| Encounter Level | EL | Sum of all enemy CR |
| Terran Stellar Concord | TSC | Player's faction |
| Free Star Alliance | FSA | Human separatist enemy |
| Starship Assault Boarding Team | SABT | Player's identity |
| Game Master | GM | Person running the game |
| Non-Player Character | NPC | Character controlled by GM |
| Concord United Fleet | CUF | TSC's military force |
| Jump Drive | JD | Faster-than-light travel tech |
| Artificial Intelligence | AI | Strictly regulated but still active in the shadows |

## Enemy Template Format

When you create an enemy data block, use this standardized format:

```
═══════════════════════════════════════
  Name: [Enemy Name]
  Type: [Human Garrison/Alien Creature/Automated Defense System] ([Mook/Standard/Elite/Boss])
  Challenge Rating (CR): [Value]
═══════════════════════════════════════

  Attributes:
  Tactics (TAC) XX (±Y) | Engineering (ENG) XX (±Y) | Mobility (MOB) XX (±Y)
  Perception (PER) XX (±Y) | Resilience (RES) XX (±Y)

  Hit Points (HP): XX  |  Armor Integrity (ARM): XX
  Defense (DEF): XX  |  Initiative (INIT): ±Y + 1d10
  Move Speed: X squares (standard gravity)

  Attacks:
  • [Attack Name]: Attack +X | Damage XdX+X [Type] | Range [Band]
  • [Backup Attack]

  Special Abilities:
  • [Ability Name]: [Effect]

  Gravity Adaptation: [List]
═══════════════════════════════════════
```

## Single-Round GM Run Checklist

```
□ 1. Round Start Phase
   □ Resolve all "at round start" triggered effects
   □ Variable-G area: roll gravity change (1d6)
   □ All characters make adaptation check (if needed)
   □ Confirm environmental hazard status (gas spread, radiation, etc.)

□ 2. Action Phase (in Initiative (INIT) order)
   For each character (high to low):
   □ Inform current gravity state and environment
   □ Character declares action and spends AP
   □ Resolve action (check → effect → reaction)
   □ Record status changes

□ 3. Round End Phase
   □ Resolve "at round end" triggered effects
   □ All ongoing statuses −1 round
   □ Oxygen consumption tally (vacuum zones)
   □ Self-Destruct Countdown −1 (if applicable)
   □ Check for new events (reinforcements, alarm escalation)
```

---

> *You are not merely running a game. You are guiding a boarding assault team through the dark corridors of an enemy vessel. In your hands are gravity, oxygen, the countdown, and death. Wield them well — to craft stories players recall for years.*  
> *— Starship Boarding Assault TRPG Game Master Rulebook v1.0*
