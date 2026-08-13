# Last Stand TRPG — GM Rulebook

> **Version:** v1.0  
> **Audience:** Game Master (GM)  
> **Prerequisite:** Recommended to read the Player Rulebook first to understand the rules from the player's perspective  
> **Document purpose:** One document covering everything needed to run the game—including all player rules (no need to read the player rulebook separately)

---

# Part One: Player Rules (Full Reprint)

> The following chapters are identical to the Player Rulebook. If you have already read the player rulebook, skip to Part Two.

---

## Chapter One: Game Overview

### 1-1 What Kind of Game Is This?

**Last Stand TRPG** is a tabletop role-playing game (TRPG) themed around near-future battle-royale competition. Players play Contestants dropped onto a sealed battlefield—with only the gun they scavenged, the armor they looted, and that one second of composure over their opponent.

### 1-2 The Core Loop

```
Drop-point Selection → Loot Scavenging → Combat Encounter → Zone Contraction & Relocation → Final Showdown
```

### 1-3 Player Count and Modes

| Mode | Players | GMs | Description |
|------|:---:|:---:|------|
| Solo Mode | 1 | 1 | One player plays a Lone Wolf; the GM controls all enemies |
| Squad Mode | 2–4 | 1 | Players form a squad and cooperate |

### 1-4 What Does the GM Need to Prepare?

| Item | Description |
|------|------|
| This rulebook | GM Rulebook |
| Player Rulebook | Optional—this document already contains all player rules |
| Dice | At least 1×d20, several each of d4/d6/d8/d10/d12 |
| Map | The battlefield map for this match (see the Map section) |
| Enemy Roster | Pre-generated enemy squads or Lone Wolf list |
| Loot Distribution Map | Pre-marked loot points and airdrop plan |
| Zone Plan | The Safe Zone path for this match |
| Tokens or markers | For marking player and enemy positions on the map |

---

## Chapter Two: Core Rules (Full Restatement)

### Core Check Formula

```
d20 + Attribute Modifier (AM) + Proficiency Bonus (PB) ≥ Difficulty Class (DC)
```

### Special Rolls

| Result | Effect |
|------|------|
| Natural 1 | Critical failure—automatic failure, may jam when firing |
| Natural 20 | Automatic hit, Precision Hit—damage die takes maximum |
| Critical Success (≥ DC+5) | GM grants an extra reward |

### Five Core Attributes and Modifiers

| Attribute | Abbr. | Meaning |
|------|:---:|------|
| Aim (AIM) | AIM | Ranged weapon accuracy |
| Physique (PHY) | PHY | Body strength, carry capacity, endurance |
| Tactics (TAC) | TAC | Battlefield awareness, acoustic location |
| Driving (DRV) | DRV | Vehicle control and repair |
| Calm (CLM) | CLM | Judgment and composure under pressure |

### Attribute Modifier = ⌊(Attribute Score − 10) ÷ 2⌋

| Score | Mod | Score | Mod |
|:---:|:---:|:---:|:---:|
| 1 | -5 | 12–13 | +1 |
| 2–3 | -4 | 14–15 | +2 |
| 4–5 | -3 | 16–17 | +3 |
| 6–7 | -2 | 18–19 | +4 |
| 8–9 | -1 | 20 | +5 |
| 10–11 | +0 | 21+ | +5 |

### Derived Stats

| Stat | Formula |
|------|------|
| HP | Lv1: 10+PHYmod, each level +1d8(min 5)+PHYmod |
| Carry Capacity | PHY × 3 + 5 kg |
| Initiative (INIT) | d20 + TACmod + ½ AIMmod |
| Hearing Range | TAC × 10 m |
| Stress Threshold | CLM × 2 + 5 |
| Downed Timer | 3 rounds |
| Movement Speed | Normal 30m, Sprint 60m |

### Skill System and Proficiency Bonus

The skill list is in the Player Rulebook, Chapter Two, section 2-4. Proficiency Bonus (PB):

| Level | PB |
|:---:|:---:|
| 1–4 | +2 |
| 5–6 | +3 |
| 7–8 | +3 |
| 9–10 | +4 |

### Advantage and Disadvantage

| State | Rule |
|------|------|
| Advantage | Two d20s, take higher |
| Disadvantage | Two d20s, take lower |
| Both present | Cancel each other out |

---

## Chapters Three to Nine (Player Rules Full Reprint)

> The full content of Chapter Three "Character Creation," Chapter Four "Equipment Details," Chapter Five "Combat Basics," Chapter Six "Zone Contraction and Stress System," Chapter Seven "Vehicle System," Chapter Eight "Growth and Leveling," and Chapter Nine "Solo Mode Exclusive Rules" is identical to the Player Rulebook. To avoid duplication, please refer directly to the corresponding chapters of the Player Rulebook. Key value quick reference is in Appendix A of this document.

---


# Part Two: GM Exclusive Rules

---

## Chapter Ten: Complete Combat System (GM View)

### 10-1 Combat Phase Details

```
Encounter Phase → Initiative Roll → Action Phase (one by one) → Reaction Phase → Round Settlement
```

#### Phase One: Encounter Determination

Both sides make a **Tactics (TAC) Perception Contest**:

- Active side: d20 + TACmod + PB (if proficient in Perception/Stealth)
- Passive side: d20 + TACmod + PB
- Active side wins → gains "First Strike": first-round attack +2 hit, Initiative +5
- Passive side wins → both discover simultaneously, normal Initiative
- Neither side notices the other → keep moving until one enters the other's hearing/visual range

#### Phase Two: Initiative Roll

```
Initiative = d20 + TACmod + max(AIMmod, 0) ÷ 2 (round down)
```

Initiative modifiers:

| Situation | Modifier |
|------|:---:|
| First Striker | +5 |
| Ambushed side | All attacks at Disadvantage first round |
| Holding pistol | +2 |
| Holding LMG / sniper rifle | -2 |
| Adrenaline active | +3 |
| Crouch / prone posture | -2 |
| Holding crossbow | +1 |

#### Phase Three: Action Phase

Each character may execute one of three configurations per round:

| Config | Move | Fire | Tactical Action |
|------|:---:|:---:|:---:|
| Tactical Shot | Half-speed (15m) | ✓ | 1 |
| Aimed Shot | No move | Aim then fire | 1 |
| Suppressing Shot | No move | Burst ×2 | None |

Movement speed is detailed in the Player Rulebook, Chapter Five.

#### Phase Four: Reaction

Each character has **1 Reaction per round** (no stacking):

| Reaction | Trigger | Effect |
|------|------|------|
| Emergency Dodge | When shot at | Disadvantage TAC check vs attacker's hit result; on success the attack is at Disadvantage |
| Suppressive Counter | When suppressed | Disadvantage single-shot counter |
| Cover Shift | When aimed at | TAC DC 15; on success this attack's DC +5 |
| Smoke Throw | Anytime | Throw equipped smoke grenade (takes effect immediately) |

#### Phase Five: Round Settlement

- Burning damage settlement
- Smoke / status effect duration -1
- Stress settlement (see Chapter Eleven)
- Downed timer -1
- Out-of-Zone damage settlement (see Chapter Eleven)

### 10-2 Complete Hit DC System

#### Base DC Table

| DC | Condition | Example GM Description |
|:---:|------|------|
| 8 | Stationary target, within 50m | "He's scavenging supplies, completely unaware you're aiming at him." |
| 10 | Slow-moving, within 50m | "He's trotting between covers, but his rhythm is regular." |
| 12 | Moving target, 50–150m | "Normal combat movement, changing cover now and then." |
| 14 | Moving + partial cover | "He pops half his body out from the corner and fires a shot—opportunity." |
| 16 | Fast-moving, 150–300m | "He's sprinting—you struggle to track him through the scope." |
| 18 | Fast-moving + cover, 150–300m | "A head poking from a vehicle—only visible for a second." |
| 20 | Extreme sniper (300m+) | "There's a small black dot moving by that tree—that's a person." |
| 22 | Extreme + head only exposed | "A sniper 600m away—he even noticed the glint off the helmet." |

#### Complete DC Modifier Table

| Modifier Source | DC Change |
|------|:---:|
| **Scope** | |
| Red Dot / Holographic (within 50m) | -1 |
| 2x Scope (within 100m) | -1 |
| 4x Scope (within 150m) | -2 |
| 8x Scope (within 300m) | -3 |
| **Own State** | |
| Self moving | +2 |
| Self crouching / prone | -1 |
| Self using adrenaline | -1 |
| **Target State** | |
| Target crouching | +1 |
| Target sprinting | +3 |
| Target half cover | +3 |
| Target head only exposed | +5 |
| Target prone / crawling | +5 |
| Target inside vehicle | +3 |
| Target in smoke | Attack at Disadvantage |
| **Firing Mode** | |
| Each extra round of Burst Fire | +1 |
| Aim one round (sniper) | -3 |
| Hip-fire (no aim) | +2 |
| **Environment** | |
| Dense fog / sandstorm | +3 |
| Heavy rain | +2 |
| Night (no night-vision) | +5 |
| Strong backlight | +2 |

### 10-3 Damage and Hit-Location System (Full Rules)

#### Hit Location (d20)

| d20 | Location | Multiplier | Example GM Description |
|:---:|------|:---:|------|
| 1–8 | Torso | ×1.0 | "The bullet goes into his chest—the armor absorbs most of the impact." |
| 9–14 | Limbs | ×0.5 | "You hit his thigh—he staggers, slowing down." |
| 15–18 | Head | ×2.0 | "Sparks burst off the helmet—the impact knocks him backward!" |
| 19–20 | Vital | ×2.5 | "The bullet passes through his throat. He didn't even have time to cry out." |

#### Damage Calculation Formula

```
Final Damage = max(Weapon Damage Die × Hit-Location Multiplier − Armor DR, 1)
```

(Minimum 1 damage dealt)

#### Armor DR Application

- DR applies only to the armor of the hit location (head uses helmet DR, torso uses armor DR)
- Limbs and Vitals have no armor protection
- Armor durability ≤ 50%: DR -1
- Armor durability ≤ 25%: DR halved
- Penetrating weapons (Desert Eagle, AKM, Kar98k (aimed), AWM): can ignore part of armor DR
  - Penetration Lv.1: ignore 2 DR
  - Penetration Lv.2: ignore 3 DR
  - Penetration Lv.3 (AWM): ignore all DR

#### Armor Durability Consumption

| How durability is consumed | Amount |
|------|:---:|
| Normal hit | -1 |
| Penetrating-weapon hit | -2 |
| Explosion area damage | Each armor in range -1 |
| Burning damage | No consumption |
| Melee attack | No consumption |

### 10-4 Special Attack Methods

#### Burst Fire

- Each extra bullet: Hit DC +1
- Each bullet rolls a **separate hit die**
- Each hitting bullet rolls a **separate hit-location die and damage**
- Burst cap is determined by the weapon

#### Suppressing Fire (LMG Exclusive)

- Designate a 5m × 5m area for suppressing fire
- All enemies in the area next round: half Movement Speed, firing at Disadvantage
- Suppression lasts 1 round, consumes 10 rounds of ammo per round
- Enemies in the area who try to move draw a free shot (no Disadvantage)

#### Thrown Weapons

| Weapon | Damage | Range | Delay | Save |
|------|:---:|:---:|:---:|------|
| Frag Grenade | 3d8 | 5m radius | Instant | TAC DC 12 for half |
| Incendiary Grenade | 2d6/round | 3m radius | Instant | Stops on leaving |
| Smoke Grenade | — | 5m radius | Instant | Lasts 2 rounds |
| Flashbang | — | 5m radius | Instant | CLM DC 14 to resist |

### 10-5 Cover and Environment

#### Cover Classification

| Cover Type | DC Bonus | Durability | Destructible | Example |
|------|:---:|:---:|:---:|------|
| Light Cover | +3 | 20 HP | Yes (AR+) | Wooden crate, wooden door, thin wall |
| Medium Cover | +3 | 50 HP | Yes (LMG+) | Concrete wall, vehicle |
| Heavy Cover | +5 | 100 HP | Yes (explosives) | Reinforced concrete, rock |
| Indestructible Cover | +5 | ∞ | No | Cliff face, large building structure |

#### Special Environment Effects

| Environment | Game Effect |
|------|------|
| Shallow water (knee) | Movement halved |
| Deep water (swimming) | Needs PHY check, cannot fire |
| Dense shrubbery | Provides light cover, makes sound when passing |
| Snow | Leaves footprints (Track check Advantage) |
| Mud | Sprint PHY DC 12, failure means fall |
| Ruins | Lots of cover, blocked line of sight |

---

## Chapter Eleven: Zone System (GM Full Operation)

### 11-1 Zone Generation

The GM secretly decides the zone shape before the game starts. The player's **Zone Prediction** (TAC skill) check can be used to guess the Safe Zone location (DC 15—success gives a vague hint).

#### Five Zone Shapes

| Zone Shape | Operation | Player Experience |
|------|------|------|
| **Central Contraction** | Each circle contracts around the current Safe Zone center | Predictable—good for novice scenarios |
| **Edge Drift** | Each circle drifts toward a specific direction (N/S/E/W) | Those who read direction benefit |
| **Jump Reversal** | One circle suddenly shifts far to the opposite side | Ruins everyone's plan—high difficulty |
| **Watery End** | Final circle on a bridge or over water | Forces vehicle fight or bridge standoff |
| **Building Lock** | Final circle within a specific building cluster | Forces close-quarters street fighting |

### 11-2 Zone Timeline

| Zone Layer | Safe Zone Diameter | Contraction Countdown | Out-of-Zone Damage | GM Notes |
|:---:|:---:|:---:|:---:|------|
| First Circle | 2 km | 5 rounds | 1d4 | Give players ample scavenging time. You may start describing distant gunshots here |
| Second Circle | 1.2 km | 4 rounds | 2d4 | Enemy encounters begin. Describe "the blue electric field is closing in" |
| Third Circle | 600 m | 3 rounds | 3d4 | Encounter frequency rises sharply. Multiple players may meet at the zone edge |
| Fourth Circle | 200 m | 2 rounds | 4d4 | Fierce firefight. Almost nowhere to hide inside the Safe Zone |
| Fifth Circle | 50 m | 1 round | 5d4 | Final showdown. Mind-game outweighs gunplay |
| Final Circle | Disappears | — | 6d4/round | No one can hide—whoever breaks first loses |

### 11-3 Out-of-Zone Movement Rules

- Moving outside the zone does not reduce speed (so escaping the zone isn't too hard)
- But auto-takes Out-of-Zone Damage each round
- If multiple characters are outside the zone together, a "zone-edge encounter" may trigger—the most dangerous fight type

### 11-4 Airdrop System

#### Airdrop Timeline

| Airdrop # | Appears at which circle | Contents |
|:---:|:---:|------|
| Airdrop 1 | When Second Circle contracts | d20 decides (see Airdrop Contents table below) |
| Airdrop 2 | When Third Circle contracts | d20 decides |
| Airdrop 3 | At start of Fourth Circle | d20 decides (high-tier scenarios only) |

#### Airdrop Contents (d20)

| d20 | Contents |
|:---:|------|
| 1–4 | AUG + 5.56mm ×90 + Lv.3 Helmet |
| 5–8 | AWM + .300 ammo ×20 + 8x Scope |
| 9–11 | M249 + 5.56mm ×150 + Lv.3 Armor |
| 12–14 | MG3 + 7.62mm ×150 (high-tier scenarios only) |
| 15–17 | DBS + 12G shells ×30 + Lv.3 Helmet + Lv.3 Armor |
| 18–19 | Armored Car (separate airdrop, red smoke visible map-wide) |
| 20 | GM's choice—could be double loot, or a trap |

---

## Chapter Twelve: Enemy System (GM Operation Core)

### 12-1 Enemy Squad Types

#### Six Difficulty Tiers

| Tier | Attribute Points | HP | Weapons | Armor | AI Behavior |
|:---:|:---:|:---:|------|------|------|
| ★ Rookie | 18 | 20–25 | Pistol / SMG | Lv.1 | Scatter to scavenge, hide at gunshots, passively wait for zone |
| ★★ Steady | 24 | 35–45 | AR / SMG | Lv.1–2 | Move as a group, hold buildings, use smoke reasonably |
| ★★★ Assault | 28 | 50–60 | AR / LMG | Lv.2 | Chase gunshots, relocate by vehicle, grab airdrops |
| ★★★ Ambush | 28 | 50–60 | SR / SMG + Frag Grenade | Lv.2 | Camp on must-pass routes, prioritize attacking vehicles, grenade to block paths |
| ★★★★ Professional | 32 | 65–80 | Fully-kitted AR / SR | Lv.3 | Perfect coordination, resource allocation, precise zone math |
| ★★★★★ Champion | 34 | 90–120 | AWM / AUG + M249 | Lv.3 | "Foresees your every step"—near-perfect prediction |

#### Enemy Attribute Templates

**Rookie Tier (★)**

| Attribute | Score | Mod |
|------|:---:|:---:|
| Aim | 10 | +0 |
| Physique | 10 | +0 |
| Tactics | 8 | -1 |
| Driving | 8 | -1 |
| Calm | 8 | -1 |

**Steady Tier (★★)**

| Attribute | Score | Mod |
|------|:---:|:---:|
| Aim | 13 | +1 |
| Physique | 12 | +1 |
| Tactics | 12 | +1 |
| Driving | 10 | +0 |
| Calm | 11 | +0 |

**Assault Tier (★★★)**

| Attribute | Score | Mod |
|------|:---:|:---:|
| Aim | 15 | +2 |
| Physique | 14 | +2 |
| Tactics | 12 | +1 |
| Driving | 12 | +1 |
| Calm | 11 | +0 |

**Ambush Tier (★★★)**

| Attribute | Score | Mod |
|------|:---:|:---:|
| Aim | 14 | +2 |
| Physique | 12 | +1 |
| Tactics | 16 | +3 |
| Driving | 10 | +0 |
| Calm | 13 | +1 |

**Professional Tier (★★★★)**

| Attribute | Score | Mod |
|------|:---:|:---:|
| Aim | 16 | +3 |
| Physique | 14 | +2 |
| Tactics | 15 | +2 |
| Driving | 13 | +1 |
| Calm | 14 | +2 |

**Champion Tier (★★★★★)**

| Attribute | Score | Mod |
|------|:---:|:---:|
| Aim | 18 | +4 |
| Physique | 16 | +3 |
| Tactics | 17 | +3 |
| Driving | 14 | +2 |
| Calm | 18 | +4 |

### 12-2 AI Behavior Logic (for GM)

#### Rookie Squad AI

```
Each round roll d6:
1-2: Hide behind cover, do not fire
3-4: Single shot at nearest target (no aim)
5: Attempt to flee (move toward Safe Zone)
6: Panic fire—random target, burst but DC +3
```
- Does not proactively change cover
- Poor reload timing (reloads with ammo still left)
- Will not revive Downed teammates
- **GM narrative hint**: "Their gunplay is terrible—bullets hit the wall beside you."

#### Steady Squad AI

```
Each round judge in order:
1. Teammate Downed? → One provides fire cover, one revives
2. In unfavorable position? → Smoke cover, group relocation
3. Normal firefight → Take turns firing from cover, keep fire sustained
```
- Reasonable cover allocation
- Uses smoke for tactical relocation
- **GM narrative hint**: "You can tell they've been trained—not random rookies spraying."

#### Assault Squad AI

```
Each round judge in order:
1. Enemy low on HP? → Whole squad pushes, burst suppression
2. Airdrop nearby? → Prioritize grabbing airdrop
3. Normal firefight → One suppresses, two flank
```
- Uses vehicles to close distance fast
- Good at flanking
- **GM narrative hint**: "Engine noise comes from your flank—they're circling you!"

#### Ambush Squad AI

```
Before encounter:
- Pick a must-pass route (bridgehead, building entrance) to set up ambush
- Lay mines (if any)
- At least one with sniper rifle at high ground

After encounter:
- First round full fire (all members fire same target simultaneously)
- Use frag grenades to force target out of cover
- If ambush fails (target didn't enter trap range), wait for the next batch
```
- **GM narrative hint**: "The bridge is deserted—too quiet."

#### Professional Squad AI

```
Global strategy:
- Front line: Lv.3 Armor + AR/LMG (draw fire)
- Back line: Lv.3 Helmet + suppressed SR (ranged output)
- Support: Smoke + first-aid kit + frag grenades (logistics)

Each round coordinate:
1. Front line marks target → back line focuses fire
2. Front line hurt → support advances, front line retreats to bandage
3. Zone unfavorable → group vehicle relocation (front line covers retreat)
```
- Will compete with you for airdrops
- Will rush out the moment you reload
- **GM narrative hint**: "These aren't ordinary Contestants—their coordination is like an army's."

#### Champion Tier AI

```
The Champion doesn't crush you with numbers—it crushes you with "prediction."
When running the Champion, treat it as "knowing the players' intent":

- Players scavenge a building? The Champion may be waiting across the way for you to come out
- Players set an ambush at the bridgehead? The Champion may swim under the bridge
- Players about to throw a grenade? The Champion charges exactly as you pull the pin

But the Champion isn't invincible—the GM needs to give the Champion a "weakness":
- Overconfident (will take high-risk actions)
- Fixed tactical habits (can be used for counter-prediction)
- Some emotional attachment (may hesitate)
```
- **GM narrative hint**: "The moment you reload—he moves. Like he knows exactly how many rounds are left in your magazine."

### 12-3 Enemy Squad Generation Tables (rolled by GM before each game)

#### Novice Scenario Generation (d20)

| d20 | Squad Composition |
|:---:|------|
| 1–6 | Rookie squad ×2 |
| 7–12 | Rookie squad ×3 |
| 13–16 | Rookie squad ×2, Steady squad ×1 |
| 17–19 | Steady squad ×2, Rookie squad ×1 |
| 20 | Steady squad ×2, Assault squad ×1 |

#### Mid-Tier Scenario Generation (d20)

| d20 | Squad Composition |
|:---:|------|
| 1–5 | Rookie squad ×2, Steady squad ×1 |
| 6–10 | Steady squad ×2, Rookie squad ×2 |
| 11–15 | Steady squad ×2, Assault squad ×1 |
| 16–18 | Assault squad ×1, Ambush squad ×1, Steady squad ×1 |
| 19–20 | Professional squad ×1, Assault squad ×1 |

#### High-Tier Scenario Generation (d20)

| d20 | Squad Composition |
|:---:|------|
| 1–4 | Assault squad ×2, Ambush squad ×1, Steady squad ×2 |
| 5–8 | Assault squad ×1, Ambush squad ×2, Professional squad ×1 |
| 9–12 | Ambush squad ×2, Professional squad ×1, Steady squad ×1 |
| 13–16 | Professional squad ×2, Ambush squad ×1, Assault squad ×1 |
| 17–19 | Professional squad ×2, Champion ×1 |
| 20 | Champion ×2 (GM beware—this will be very hard) |

### 12-4 Dynamic Elimination System (combat between NPCs)

"The players aren't the only ones moving."

The GM rolls d20 each round (or every two rounds) to determine whether NPCs fight each other and the outcome:

| d20 | NPC Encounter Result |
|:---:|------|
| 1–8 | No NPC-vs-NPC combat this round |
| 9–12 | Combat occurs—both survive, each spends resources (both HP -1d10) |
| 13–15 | One side wins—eliminates one weaker Lone Wolf / squad member |
| 16–17 | One side wins—eliminates one mid-strength Lone Wolf / squad member |
| 18–19 | Distant explosion—a squad wiped out (maybe mine or vehicle explosion) |
| 20 | Fierce firefight—eliminates 2–3 Contestants (GM chooses who, and gives players the gunshot details they hear) |

#### Behavior Modifiers

| Modifier Source | NPC Encounter Die |
|------|:---:|
| Assault squad present in same area | +3 |
| Professional squad present in same area | +2 |
| Safe Zone shrunk to ≤ 1km | +1 |
| Safe Zone shrunk to ≤ 500m | +2 |
| Safe Zone shrunk to ≤ 100m | +3 |

**Nemesis Protection Rule**: The Nemesis cannot be dynamically eliminated (before the final circle). The Nemesis always waits for the players in the final circle.

#### GM Narrative Conversion Examples

| Die Result | How the GM Might Describe It |
|:---:|------|
| 9–12 | "A burst of rapid gunfire from the northern slope—about ten seconds, then silence. Someone met their match." |
| 13–15 | "Bang. Bang. Bang. Three sniper shots—then only a thud of a body falling. Contestant #15 eliminated." |
| 18–19 | "BOOM—!!! A huge explosion from the southeast. You see a column of black smoke rise." |
| 20 | "To the northwest—the sound of a machine gun sweeping. Someone is being pinned down. The gunfire lasted a full half-minute before stopping." |

---

## Chapter Thirteen: Loot Distribution and Scavenging System

### 13-1 Loot Tiers

| Tier | Marker Color | Distribution Area | Drop Pool |
|------|:---:|------|------|
| **Scarce (Gray)** | Gray | Wilderness huts, roadside toilets, abandoned vehicles | Pistol, Lv.1 gear, bandages |
| **Common (Green)** | Green | Ordinary houses, small warehouses | SMG, AR (low chance), Lv.2 gear, first-aid kit |
| **Abundant (Blue)** | Blue | Large buildings, factories, schools | Full weapon pool (incl. SR), Lv.2–3 gear, medical kit |
| **Military (Purple)** | Purple | Military bases, supply crates | Lv.3 gear, rare weapons (suppressed SR, AWM) |
| **Airdrop (Gold)** | Gold | Airdrop crate | Unique gear (see 11-4 Airdrop Contents table) |

### 13-2 Scavenging Rolls

Each time a player scavenges a loot point, roll d20 to determine the found item:

#### Scarce Loot Point (d20 scavenging table)

| d20 | Item |
|:---:|------|
| 1–5 | Nothing |
| 6–8 | 9mm ammo ×30 |
| 9–11 | P92 Pistol |
| 12–14 | Bandage ×2 |
| 15–16 | Lv.1 Helmet |
| 17–18 | Lv.1 Armor |
| 19 | Energy Drink ×2 |
| 20 | Random rare item (GM's choice of one Blue-tier item) |

#### Common Loot Point (d20 scavenging table)

| d20 | Item |
|:---:|------|
| 1–3 | 9mm ammo ×60 |
| 4–6 | UMP45 or MP5K (50% chance each) |
| 7–9 | Bandage ×3 |
| 10–11 | First-Aid Kit ×1 |
| 12–13 | Lv.2 Helmet |
| 14–15 | Lv.2 Armor |
| 16–17 | M16A4 (30% chance with red dot) |
| 18 | 4x Scope |
| 19 | Frag Grenade ×2 |
| 20 | Random rare item (GM's choice of one Purple-tier item) |

#### Abundant Loot Point (d20 scavenging table)

| d20 | Item |
|:---:|------|
| 1–2 | 5.56mm ammo ×90 |
| 3–4 | SCAR-L or AKM (50% chance) |
| 5–6 | First-Aid Kit ×3 |
| 7–8 | Lv.2 Helmet + Lv.2 Armor |
| 9–10 | Lv.3 Helmet |
| 11–12 | Lv.3 Armor |
| 13–14 | SKS + 4x Scope |
| 15–16 | M24 |
| 17 | Kar98k + 8x Scope |
| 18 | Medical Kit ×1 |
| 19 | Adrenaline ×1 |
| 20 | Random airdrop item |

#### Military Loot Point (d20 scavenging table)

| d20 | Item |
|:---:|------|
| 1–2 | 7.62mm ammo ×120 |
| 3–5 | AKM + compensator + extended magazine |
| 6–7 | M416 + vertical grip |
| 8–9 | Lv.3 Helmet |
| 10–11 | Lv.3 Armor |
| 12–13 | M24 + 8x Scope + suppressor |
| 14 | AWM + 8x Scope (only 1 Military point has this item; remove from drop pool once found) |
| 15–16 | M249 + bipod |
| 17 | C4 explosive ×2 + remote detonator |
| 18 | Adrenaline ×2 |
| 19 | Self-Revive Syringe (Solo Mode) |
| 20 | GM-customized legendary item |

### 13-3 GM Scavenging Pace Control

| Zone Layer | Scavenging Level Players Should Have | GM Adjustment |
|------|------|------|
| First Circle | Basic armament complete (at least one primary weapon + Lv.1 armor) | If players still have no weapon, secretly adjust the scavenging table |
| Second Circle | Found upgrade gear (Lv.2 gear, attachments) | Increase encounter pressure, urge movement |
| Third Circle | Gear basically formed | No more adjustment—players on their own |
| After Fourth Circle | Scavenging no longer the focus | Remove scavenging opportunities—focus on combat |

---

## Chapter Fourteen: Weather and Environment System

### 14-1 Weather Types

| Weather | Game Effect | GM Narrative Hint |
|------|------|------|
| **Clear** | Normal | "The sun is glaring—the backlit direction is hard to aim at." |
| **Overcast** | Normal | "Thick clouds soften the light. Perfect weather for snipers." |
| **Dense Fog** | Visibility ≤ 100m, ranged DC +3 | "You can only see thirty meters ahead—beyond that, only white." |
| **Heavy Rain** | Visibility halved, Hearing Range -20m, DC +2 | "Rain hammers the tin roof—you can't hear your own footsteps, let alone anyone else's." |
| **Sandstorm** | Visibility ≤ 50m, DC +3, Hearing Range halved | "Yellow sand obscures everything—you hear the vehicle engine but can't see where." |
| **Blizzard** | Visibility ≤ 80m, DC +2, each round PHY check to avoid speed halved | "In the howling wind, your eyelashes freeze—every breath stings the lungs." |
| **Thunderstorm** | Random lightning (5% chance hits highest point), DC +1, Hearing Range -10m | "Lightning splits a nearby tree—the whole sky flashes for half a second." |

### 14-2 Weather Change (d6 table)

Every 10 rounds or upon entering a new zone layer, roll d6 to determine weather change:

| d6 | Change |
|:---:|------|
| 1–3 | Weather unchanged |
| 4–5 | Weather worsens one step (Clear→Overcast→Fog→Rain→Storm) |
| 6 | Weather improves one step |

### 14-3 Day-Night System

| Light Mode | Effect | Needs Night-Vision? |
|------|------|:---:|
| Day | Normal vision | No |
| Dusk | Vision -20% | Recommended |
| Night (no moon) | Vision ≤ 30m, DC +5 (no night-vision) | Required |
| Night (full moon) | Vision ≤ 80m | Recommended |

#### Night-Vision Goggles Tiers

| Tier | How Obtained | Effect |
|:---:|------|------|
| Lv.1 Night-Vision | Common loot point (low chance) | Night vision 80m, DC penalty -2 |
| Lv.2 Night-Vision | Abundant loot point | Night vision 150m, DC penalty -4 |
| Thermal Imager | Airdrop-exclusive | Night vision 200m, can see target silhouette through smoke |

### 14-4 Red Zone Bombing

#### Trigger Conditions

- After the Second Circle begins, a Red Zone check every 5 rounds
- Roll d20: result ≤ 10 triggers Red Zone Bombing
- Military base areas: Red Zone chance doubled (d20 ≤ 15 triggers)

#### GM Operation Steps

1. **Announce Red Zone**: "The bomber's engine sound comes from afar—the Red Zone is coming."
2. **Mark area**: Randomly select a 200m × 200m area on the map
3. **Wait 1 round**: Give players time to react (hide in buildings, flee the area)
4. **Bombing**: All characters in the area—2d10 damage per round, lasting 2 rounds

#### GM Narrative Example

> "A low rumble from the sky—not a vehicle, a bomber. You look up and see a red flare streak across the sky, marking the bombing zone. You have less than a minute."

---

## Chapter Fifteen: Encounter Design Guide

### 15-1 Zone-Layer Encounter Difficulty Curve

| Zone Layer | Encounter Density | Encounter Nature | Design Focus |
|------|:---:|------|------|
| First Circle | Low | Occasional (1–2 times) | Let players experience first fight—low difficulty |
| Second Circle | Medium | Planned firefight (2–3 times) | Test players' scavenging results and tactical judgment |
| Third Circle | High | Zone-edge melee (3–4 times) | Multiple encounters under zone pressure |
| Fourth Circle | Very High | Meat grinder (continuous firefight) | Almost unavoidable combat |
| Fifth Circle | Ultimate | Final showdown (1 time) | Mind-game—not a gunfight duel, a composure duel |

### 15-2 Third-Party Intervention Design

The "opportunist drawn in by the sound of gunfire" is one of Last Stand TRPG's most dramatic mechanics.

#### Trigger of Third-Party Intervention

When a firefight lasts over 2 rounds, and a potential third party (other squad or Lone Wolf) is within 300m:

| Third-Party Type | Arrival Delay | Behavior |
|------|:---:|------|
| Rookie | 3–4 rounds | Hide at a distance and watch, decide who wins |
| Steady | 2–3 rounds | Find a high ground to observe, ambush survivors after firefight ends |
| Assault | 1 round | Join the melee directly—"Enemies fighting each other is the best chance!" |
| Professional | 1 round | First eliminate the most threatening side, then harvest the other |
| Champion | Already on site | Has been waiting—until both sides are down to their last breath |

#### Three-Way Dynamic GM Operation

```
When the third party arrives:

① First describe the clues the players can perceive
  "You hear footsteps to your rear-left—not a teammate's."

② Then describe the third party's effect on the fighting side
  "Sniper fire comes from another direction—not at you. He's shooting your opponent."

③ Let the players decide: retreat? Team up with the third party? Or fight both at once?

④ Key: Don't let the third party become "GM fighting GM"—the third party should affect the players' battle
```

### 15-3 "Three-Round Rule"

> In a battle royale, three bullets can decide everything.

As GM, you should design each encounter to end within 3–8 rounds:

- **Rounds 1–2**: Positioning and probing—who spots whom first? Who fires first?
- **Rounds 3–4**: Decisive firefight—someone is hit, someone changes cover
- **Rounds 5–8**: Pursuit or retreat—one side at disadvantage, chooses to flee or fight to the death

Don't let combat drag past 10 rounds—that means both sides are wasting bullets ineffectively. Accelerate the pace: bring in third-party intervention, close the zone, exhaust resources.

### 15-4 Cover Principles

Each firefight area should have at least:

- **2–3 covers** (give both sides tactical choices)
- **At least 1 escape route** (make retreat an option)
- **1 high ground** (add verticality)
- **At least 1 entrance a third party can slip through** (foreshadowing)

### 15-5 Airdrop Contest Dramatic Design

The airdrop is a "golden trap"—the GM should design it as:

1. **Visibility**: Red smoke visible map-wide—everyone knows where the airdrop is
2. **Arrival time gap**: Nearest player reaches in 1–2 rounds, farthest in 3–4 rounds
3. **First wave**: Fastest-arriving player vs equally fast Assault squad—first to arrive has the edge
4. **Second wave**: Other squads drawn by gunshots—form a three-way melee
5. **Escape**: The one who grabs the airdrop faces pursuit—"Now you have the best gun—but everyone is chasing you"

---

## Chapter Sixteen: GM Narrative Guide

### 16-1 Narrative Arc of a Match

| Phase | Time Share | GM Focus | Suggested Tone |
|------|:---:|------|------|
| **Drop** | 5% | Create the grand spectacle of large-scale competition | Excited, anticipatory |
| **Scavenging** | 25% | Build map atmosphere, intersperse distant gunshots | Sense of exploration, unknown |
| **Relocation & Encounter** | 35% | Maintain pace—alternating tension and release | Tension and release in turn |
| **Final Circle** | 25% | Create extreme pressure—every footstep may be the last | Oppressive, desperate |
| **Ending** | 10% | Give the victor glory, give the defeated dignity | Epic |

### 16-2 Six Techniques for Building Tension

#### 1. Information Deprivation

Don't tell players everything—let them discover it themselves:

```
❌ "You see an enemy squad moving 100m north of you."
✅ "The bushes to the north twitched—maybe wind, maybe a person."
```

#### 2. Resource Scarcity

Make players aware that ammo and medical supplies are limited:

```
"You feel the magazine—only two left. That means you have 60 rounds to deal with everyone coming."
```

#### 3. Time Pressure

Use the zone countdown to create urgency:

```
"The blue electric field's hum grows closer—you're now 50m outside the zone. Run, or loot one more room?"
```

#### 4. Sensory Description

Don't just describe visuals—describe sound, vibration, smell:

```
"Gunpowder mixed with the smell of burning—the incendiary's flame dances in the next room. The wall is hot."
```

#### 5. Weight of Choice

Make every decision cost something:

```
"You could charge into that building—there may be a medical kit to save your teammate. But you also saw the sniper-scope glint reflecting off the second-floor window."
```

#### 6. Narrativizing the Stress System

Turn stress changes into the character's inner monologue:

```
(As stress nears breakdown)
"Your hands start trembling on their own—not from cold. You stare at the cross in the scope, but it keeps jumping. Breathe. Breathe. Breathe—useless."
```

### 16-3 Pace Control Methods

| Pace Adjustment | Trigger Signal | Method |
|------|------|------|
| **Accelerate** | Players scavenge too long, combat drags, scene is dull | Early zone contraction, third-party intervention, Red Zone bombing, describe masses of distant gunshots |
| **Slow down** | Players under too much pressure, story needs emotional space | Brief calm moment, find a safe small room, meet an NPC who doesn't attack |

---

## Chapter Seventeen: Solo Mode GM Exclusive Guide

### 17-1 19 Lone Wolf Roster Building

In Solo Mode, the GM plays all other Contestants on the field.

#### Building Steps

**Step One: Generate the Roster**

Use the following template to fill in basic data for each Lone Wolf:

| Field | Description | Example |
|------|------|------|
| ID | 1–19 | #07 |
| Name | Real name | Ivan Kovac |
| Codename | Battlefield nickname | "Sentinel" |
| Preferred Weapon | Main weapon type | Sniper rifle + pistol |
| Tactical Style | Rookie / Steady / Assault / Ambush | Steady |
| Initial Drop Point | Starting position on map | Southwest corner of military base |
| Strength Rating | 1–10 | 6 |

**Step Two: Assign Tactical Styles**

| Tactical Style | Suggested Count (9-person scenario) | Suggested Count (14-person scenario) | Suggested Count (19-person scenario) |
|------|:---:|:---:|:---:|
| Rookie | 5 | 4 | 4 |
| Steady | 3 | 3 | 5 |
| Assault | 1 | 3 | 4 |
| Ambush | 0 | 3 | 4 |
| Professional | 0 | 0 | 1 |
| Nemesis | 1 (counted separately) | 1 | 1 |

**Step Three: Design the Nemesis**

The Nemesis is "someone like you"—not a stat monster. Choose a Nemesis type:

| Nemesis Type | Motivation | GM Operation Key |
|------|------|------|
| **Mirror Nemesis** | Uses the same weapons, same tactical style as the player—a younger or older version of you | Make the player feel "this could be another me in a parallel world" |
| **Sworn Enemy** | The player previously eliminated their teammate/partner | Leave a taunting message in the final circle (an empty shell, a photo) |
| **Mentor–Student Nemesis** | Trained under the same coach as the player | Knows every habit of the player—but the player knows theirs too |
| **Legendary Hunter** | No shortage of money or fame—entered only because they heard the player entered too | Briefly appears in earlier circles then vanishes—"I'm waiting for you to grow stronger" |

### 17-2 Dynamic Elimination Detailed Operation

In Solo Mode, dynamic elimination matters even more—19 people can't all be killed by the player's own hand.

#### Operation Steps

Run once every 2–3 rounds:

```
① Roll d20 to determine if NPC-vs-NPC combat occurs
② If so, determine which Lone Wolves are involved (prioritize those in the same area)
③ Roll the contest result (who is eliminated? whose resources are spent?)
④ Convey it to the player through narrative
```

#### Elimination Pace Control

| Survivors | Eliminations per Round (avg) | GM Adjustment |
|:---:|:---:|------|
| 20–15 | 0.5–1 / round | Eliminate slower—give players time to develop |
| 14–10 | 1–2 / round | Normal pace |
| 9–5 | 1–2 / round | Keep a few strong ones for the player |
| 4–2 | GM manual control | Nemesis and player—final showdown |

### 17-3 Nemesis Dynamic Operation

#### Nemesis Five-Stage Operation

| Stage | Zone Layer | Operation | Nemesis Narrative |
|------|:---:|------|------|
| 1. Shadow | First Circle | Nemesis appears in the distance, but player can't see clearly | "On the hillside—a figure. Standing still, like watching you. Then turns and leaves." |
| 2. Trace | Second Circle | Player finds what the Nemesis left behind | "In the room you scavenge, an empty shell stands upright on the table. This is for you." |
| 3. Approach | Third Circle | Nemesis is nearby, but no contact | "You hear gunshots not far away—two clean pistol shots. Your most familiar gunshot. You use that gun too." |
| 4. Wait | Fourth Circle | Nemesis enters the final-circle edge | "Fewer than ten left in the circle. You know he's inside. He knows you're outside." |
| 5. Showdown | Final Circle | You vs Nemesis | "The circle shrinks to just thirty meters. No cover left—only you and the person across from you." |

### 17-4 Final Circle 1v1 Exclusive Rules

#### Final Circle Structure

| Stage | Operation |
|------|------|
| Positioning (Round 1) | Both confirm each other's position. Circle too small—nowhere to hide |
| Standoff (Round 2) | Make a **Calm Contest Check**: both d20 + CLMmod. Loser acts with Disadvantage next round |
| Eruption (Round 3+) | Free firefight. But Out-of-Zone Damage is 5d4/round—everyone dies |
| Endgame | One falls, or both are swallowed by Out-of-Zone Damage |

#### GM Narrative Guidance

```
"Thirty meters. That's all there is. The blue electric field crackles around you,
the air hot as if about to burn.

The person across from you—you know them.

They raise their gun—the same one you use.
They even aim in the same stance as you.

You both pull the trigger at the same time."
```

### 17-5 Radio Tower GM Operation Rules

#### Four Monitoring Channels

When a player activates a Radio Tower, the GM may provide intel through the following channels:

| Channel | Intel Provided | Usage Limit |
|------|------|:---:|
| **Area Scan** | "You receive thermal imaging from a drone—3 red dots moving within 200m." | 1 per tower |
| **Airdrop Marker** | "The next airdrop will land at grid E7—about 400m southeast of your position." | 1 per tower |
| **Nemesis Location** | "A blurry surveillance image—the back of your Nemesis. Background is 'North District Power Plant'." | Only once—used up, the Nemesis will know |
| **Extraction Call** | "This is the extraction helicopter—we have your signal. Cannot land in the final circle. Figure it out yourself." | Only in scenarios with an extraction point |

#### Risks of Using the Radio

- Tower-top warning light turns on—**visible map-wide** (clearly visible within 1km range)
- After activation, 30 minutes (about 5 rounds) before the same tower can be used again
- Other Lone Wolves may wait below the tower for you to come down

---

## Chapter Eighteen: Scenario Framework

### 18-1 Multiplayer Scenario Overview

| Tier | Scenario Name | Suggested Level | Map | Enemy Squads | Total Players | Duration |
|:---:|------|:---:|------|:---:|:---:|:---:|
| I | Novice Trial | 1–2 | Erangel | 4 | 20 | 2–3h |
| II | Jungle City Street War | 3–4 | Sanhok | 6 | 28 | 3–5h |
| III | Desert Military Base | 5–6 | Miramar | 8 | 36 | 4–6h |
| IV | Snowfield Survival Contest | 7–8 | Vikendi | 10 | 44 | 5–7h |
| V | The Ultimate Battlefield | 9–10 | Mixed | 12 | 52 | 6–8h |

### 18-2 Solo Scenario Overview

| Tier | Scenario Name | Suggested Level | Map | Lone Wolves | Nemesis | Duration |
|:---:|------|:---:|------|:---:|------|:---:|
| I | S6 The Survivor | 1–2 | Night Mist Island | 9+Nemesis | Veteran | 1.5–2h |
| II | S7 Hunter and Prey | 3–4 | Salt Flats | 14+Nemesis | Retired Special Forces | 3–4h |
| III | S8 Lone Wolf Trial | 5–6 | Rust Belt Industrial Park | 16+Nemesis | Bounty Hunter | 4–5h |
| IV | S9 The Last Match | 7–8 | Drowned City | 19+Nemesis | Former Partner | 5–7h |
| V | S10 Legendary Endgame | 9–10 | Ascension Arena | 5 Champion+Nemesis | Reaper | 6–8h |

> The complete design of each scenario (scene list, NPC configuration, loot layout, zone settings) is in the separate YAML files in the `scenarios/` directory.

---

## Chapter Nineteen: Optional Rules and Variants

### 19-1 Quick Play Mode (30 minutes)

| Adjustment | Change |
|------|------|
| Map | Condensed to 1×1 km |
| Players | 10 (player + 9 NPCs) |
| Starting Gear | Pre-set basic gear (P92 + Lv.1 helmet/armor + bandage ×2) |
| Zone | Fixed Central Contraction, contracts every 2 rounds |
| Scavenging | Simplified—enter any building, d6 decides loot tier found |

### 19-2 Two-Player Squad Mode

| Adjustment | Change |
|------|------|
| Gameplay | 2 players form a squad vs an enemy 2-person squad |
| Downed Revival | Only teammates can revive (standard rule) |
| Enemy Config | Enemy becomes two-person teams (double the count to keep total players) |

### 19-3 Hardcore Mode

| Adjustment | Change |
|------|------|
| No HUD | Players don't know their HP—GM informs via narrative ("you feel very weak", "the bleeding stopped") |
| Realistic Damage | Torso ×1.5 (organ damage), head without helmet = instant death |
| Weapon Jam | Natural 1–2 jams, requires a full round to clear |
| No Dynamic Elimination | All NPCs manually controlled by GM (more realistic but more time-consuming) |

### 19-4 Custom Map Generation Rules

1. **Decide size**: 2×2 (small) to 8×8 (large) km
2. **Draw terrain**: At least 3 terrain types (water / urban / wilderness / mountain / forest)
3. **Mark loot points**: By loot tier distribution (see Chapter Thirteen)
4. **Place special locations**: Radio Towers (2–3), bridges, military bases
5. **Plan zone shape**: Choose one of the five zone shapes

---

# Appendix A: GM Quick Reference

## A-1 Hit DC Quick Reference

| DC | Condition |
|:---:|------|
| 8 | Stationary within 50m |
| 10 | Slow-moving within 50m |
| 12 | Moving 50–150m |
| 14 | Moving + partial cover |
| 16 | Fast-moving 150–300m |
| 18 | Fast-moving + cover |
| 20 | Extreme 300m+ |
| 22 | Extreme + head only |

## A-2 Damage Quick Calc

```
Damage = (Weapon Die + PB) × Hit-Location Multiplier − (Enemy DR − ⌊Level÷2⌋) (min 1)
```

| Location | d20 | Multiplier |
|------|:---:|:---:|
| Torso | 1–8 | ×1.0 |
| Limbs | 9–14 | ×0.5 |
| Head | 15–18 | ×2.0 (helmet ×1.5) |
| Vital | 19–20 | ×2.5 |

## A-3 Action Economy

```
Each round = Move + Fire + Tactical Action (or No move + Aim + Tactical Action)
```

| Tactical Action | Description |
|------|------|
| Reload | 1 Tactical Action (LMG needs full round) |
| Switch Weapon | 1 (pistol is Free Action) |
| Use Consumable | 1 (first-aid kit needs 2 rounds) |
| Revive Ally | 1 full round |
| Throw Item | 1 |
| Go Prone / Crouch | Free Action |

## A-4 Stress System Quick Reference

| Stage | Stress % | Effect |
|------|:---:|------|
| Calm | < 50% | — |
| Tense | 50–74% | Aim Disadvantage |
| Panic | 75–99% | Aim + Tactics Disadvantage |
| Breakdown | ≥ 100% | d6 random action |

## A-5 Out-of-Zone Damage Quick Reference

| Zone Layer | Damage |
|:---:|:---:|
| First Circle | 1d4 |
| Second Circle | 2d4 |
| Third Circle | 3d4 |
| Fourth Circle | 4d4 |
| Fifth Circle | 5d4 |
| Final | 6d4 |

---

## A-6 GM FAQ

**Q: Players keep scavenging and won't move—what do I do?**
A: The zone contraction is your best friend. Remind players "the blue electric field is closing in" and start applying pressure to those outside the zone. You can also use distant gunshots to hint "the good stuff is being grabbed by someone else."

**Q: Combat is dragging on too long—what do I do?**
A: Trigger third-party intervention, accelerate the zone, or make one side run out of ammo—pick one, don't use all three at once.

**Q: Players find it too hard / too easy—what do I do?**
A: Adjust secretly—too hard: let enemy AI "make mistakes" (Rookie AI behavior); too easy: upgrade a Steady squad to Assault, increase Red Zone bombing frequency.

**Q: When should the Nemesis appear?**
A: Always in the final circle. In earlier circles the Nemesis may briefly appear then vanish (the "Shadow stage")—but don't let players eliminate the Nemesis in the Second Circle. That breaks the whole scenario's tension.

**Q: Players ask to reroll—what do I do?**
A: You have final say. Suggestion: don't allow rerolls unless it's an error from a rules misunderstanding. The core tension of the battle royale comes from "irreversible" consequences.

---

## A-7 Lv11–15 Expansion Rules (Optional)

The core rules treat Lv1–10 as a complete cycle. If the GM wishes to run higher-level games, use the following expansion:

| Level | Cumulative XP | PB | This Level's Gain |
|:---:|:---:|:---:|------|
| 11 | 36,000 | +4 | 1 feat |
| 12 | 50,000 | +4 | Attribute increase |
| 13 | 68,000 | +5 | Background ability enhancement |
| 14 | 90,000 | +5 | Background final enhancement |
| 15 | 120,000 | +5 | Legendary pinnacle |

**Lv11+ Notes:**
- HP keeps growing at 1d8(min 5)+PHYmod
- Lv15 character HP is about 150 (PHY 16) to 200 (PHY 20)
- Enemies need custom Boss-tier templates (base attributes 18+) to stay challenging
- Recommended to design dedicated high-difficulty scenarios for Lv11+

## A-8 Random Non-Combat Event Table (d20)

During the scavenging phase or while relocating, the GM may roll d20 to trigger a non-combat event to enrich the narrative:

| d20 | Event | GM Narrative Hint |
|:---:|------|------|
| 1–6 | No special event | "All as usual—only wind and the occasional distant gunshot." |
| 7–8 | Find footprints | "A set of fresh footprints on the ground—no more than two minutes old. Solo, heading southeast." |
| 9 | Find abandoned loot | "Behind the door in the corner is a forgotten first-aid kit—someone must have fled in a hurry." |
| 10 | Distant explosion | "BOOM—a column of black smoke rises to the northeast. Not an airdrop—a vehicle explosion." |
| 11 | Radio static | "Your walkie-talkie suddenly emits a brief burst of static—someone nearby is using radio equipment." |
| 12 | Startled birds | "A flock of birds suddenly flies up from the forest—something spooked them. In that direction." |
| 13 | Abandoned camp | "You find an abandoned temporary camp—empty shells, a used bandage. Someone has been here." |
| 14 | Dead silence | "Suddenly—everything goes quiet. No gunshots, no wind. Too quiet." |
| 15 | Pandora broadcast | "The broadcast system sounds: 'Contestants—remaining count: 14. Good luck to you all.' Sweet and cold." |
| 16 | Sudden weather change | "The sky suddenly darkens—not the zone, a storm is coming. (Roll weather change table)" |
| 17 | Animal tracks | "A rustle in the bushes—not a person, a wild boar. But it still makes your heart race." |
| 18 | Trap trace | "You notice a very thin steel wire on the ground—someone set a tripwire trap here. (Perception DC 16, triggers if failed)" |
| 19 | Body and loot | "A fallen Contestant—not shot, but Out-of-Zone Damage. The backpack beside them is still full." |
| 20 | Nemesis's trace | "Your heart skips a beat—a mark you recognize is on the wall. It's left for you." |

---

> **Remember: You are not the players' opponent—you are the co-author of their story. Your goal is not to "beat the players," but to make their victory hard-won and their defeat glorious and meaningful.**
