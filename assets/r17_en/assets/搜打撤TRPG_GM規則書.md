# Search, Attack, Retreat TRPG — GM Rulebook v1.0

> **You are the master of the Quarantine Zone (QZ). You control the footfalls of the Residuals, the radio chatter of the Iron Brotherhood patrols, and every Gold-tier item hidden among the ruins. This book tells you how to make every sortie an unforgettable survival gamble for your players.**

---

# Chapter One: GM Quick Start

## 1.1 System Core Overview

| Item | Value |
|---|---|
| Core Roll | 3d6 + base Attribute + Skill Level ≥ Target Number (TN) |
| Attribute Range | 1-10 (5 = human baseline) |
| Skill Range | 0-5 (0 = Untrained) |
| Target Number | 8/11/14/17/20/23/26 |
| Seven-Part Hit Points (HP) | Head/Chest/Abdomen/Left & Right Arms/Left & Right Legs (independent Hit Point (HP) pools) |
| Armor System | Damage Reduction (DR) |
| Action Point (AP) / Round | 2 Action Points, may reserve 1 Action Point for Reactions |

## 1.2 First-Time GM Preparation Checklist

1. Read the Player Rulebook, Chapters One to Three
2. Prepare the "Ash Mall" map (see §4.3)
3. Familiarize yourself with the five NPC Scavenger templates (see §3.5)
4. Prepare 2-3 Commissions
5. Prepare Extraction Point conflict scenarios (see §5.4)
6. Print blank character sheets
7. Set the Extraction time limit (60-90 minutes)
8. Plan a Pulse Surge countdown (optional tension tool)

## 1.3 Golden Ratio (Single Session 3-4 Hours)

| Activity | Time Share | Approx. Minutes |
|---|---|---|
| Explore & Scavenge | 40-50% | 72-90 min |
| NPC Interaction | 15-20% | 27-36 min |
| Combat | 20-25% | 36-45 min |
| Extraction | 10-15% | 18-27 min |

---

# Chapter Two: Complete Combat Rules (GM Version)

## 2.1 Round-Based Framework

Each combat round is approximately 6 seconds:

```
Phase One: Declaration Phase
  • GM declares the NPC's visible intent
  • Players verbally declare their intent for this round

Phase Two: Execution Phase
  • Act in Initiative order (Initiative = Perception + Precision)
  • 2 Action Point (AP) per character
  • May reserve 1 Action Point (AP) for Reactions

Phase Three: Resolution Phase
  • Persistent effects (bleeding, fire, etc.)
  • Morale check
  • Effect duration −1
```

## 2.2 Hit Location Roll (d100)

| d100 | Part | Hit Points (HP) Formula | At PHY 5 |
|---|---|---|---|
| 01–05 | Head | PHY+6 | 11 |
| 06–40 | Chest | PHY×2+10 | 20 |
| 41–55 | Abdomen | PHY+8 | 13 |
| 56–67 | Left Arm | PHY+4 | 9 |
| 68–79 | Right Arm | PHY+4 | 9 |
| 80–90 | Left Leg | PHY+5 | 10 |
| 91–100 | Right Leg | PHY+5 | 10 |

### Part Injury Effects

| Part | 50% Hit Points (HP) | 25% Hit Points (HP) | 0 Hit Points (HP) |
|---|---|---|---|
| Head | −1 to all checks | −2 to all checks + may lose Action Point (AP) | **Instant Death** |
| Chest | Difficulty breathing (Movement −1m) | Pneumothorax (−1 Hit Points (HP) per round) | **Mortal (Near Death)** (Courage Target Number (TN) 14 each round) |
| Abdomen | −1 Physique check | Internal Bleeding (−1d4 Hit Points (HP) per round) | Death by internal bleeding |
| Arm | −1 action with that arm | That arm unusable | Permanent disability |
| Leg | Movement −1m/Action Point (AP) | Movement −3m, cannot sprint | Permanent disability (dragging 1m/Action Point (AP)) |

## 2.3 Damage Reduction (DR) Resolution Chain

```
Weapon Damage → Cover Damage Reduction (DR) → Armor Damage Reduction (DR) → Final Damage (minimum 1)
```

| Cover Type | Cover Damage Reduction (DR) | Hit Effect |
|---|---|---|
| No Cover | 0 | Normal |
| Light Cover | 0 (concealment only) | Attacker has Disadvantage |
| Half Cover | 2 | Attacker has Disadvantage |
| Full Cover | 4 | Attacker has Double Disadvantage |

Armor Damage Reduction (DR). Helmet = Head, Body Armor + Vest = Chest/Abdomen, Gloves = Both Arms, Combat Boots = Both Legs. Damage Reduction (DR) cannot stack above 5.

## 2.4 Reactions (Spend Reserved 1 Action Point (AP))

| Reaction | Trigger Condition |
|---|---|
| **Attack of Opportunity** | Enemy moves away within melee range |
| **Suppression Response** | Return fire when suppressed (Disadvantage) |
| **Tactical Roll** | When shot, Perception Target Number (TN) 14 to dodge (if successful, that shot is at Disadvantage) |
| **Cover Shift** | In half cover, move 2m to adjacent cover after being hit |

## 2.5 Special Actions

| Action | Action Point (AP) | Check | Effect |
|---|---|---|---|
| First Aid (Self) | 2 | Tech Target Number (TN) 14 | Recover 1d6 Hit Points (HP) + stop bleeding |
| First Aid (Others) | 1 | Tech Target Number (TN) 11 | Recover 1d6+2 Hit Points (HP) + stop bleeding |
| Reload | 1 | — | Swap magazine; Action Point (AP) cost can be negated by the "Quick Hands" Feat |
| Loot Body | 2 | — | Search a fallen enemy |
| Retreat Move | 1 | — | Move + does not trigger Attack of Opportunity |
| Extraction Call | 2 | — | Use flare gun/radio to call extraction vehicle |
| Drag Ally | 2 | — | Drag a Prone ally up to 3m |
| Set Explosive | 2 | Tech Target Number (TN) 14 | Place explosive at a designated location (timed/remote) |
| Suppressing Fire | 2 | — | Characters in target area make Courage Target Number (TN) 14 |

## 2.6 Stealth and Detection

**Stealth Check:** 3d6 + Perception + Stealth Skill vs target's passive Perception (Perception + Awareness)

| Modifier | Effect |
|---|---|
| Half-speed movement | +2 |
| Sprinting | −3 |
| In darkness | +2 (stealth side) |
| Making noise | −2 |
| 50m+ distance | +2 (stealth side) |

### Ambush Round
1. The ambushed side makes an Awareness check vs the ambusher's remaining Stealth check value
2. Success → normal Initiative; failure → ambusher acts with surprise on the first round (cannot React)
3. Ambusher gains +3 Initiative

## 2.7 NPC Morale (2d6 Simplified System)

| 2d6 Result | NPC Reaction |
|---|---|
| ≤ 4 | Flee/Surrender |
| 5-6 | Tactical retreat (begin extraction next round) |
| 7-8 | Hold position (do not advance, keep firing) |
| 9+ | Act normally |

Morale check triggers when: lose more than 50% of personnel, commander falls, or facing overwhelming firepower.

## 2.8 Environmental Damage

| Source | Damage | Range |
|---|---|---|
| Fragmentation Grenade | 3d6 | 5m |
| C4 Explosive | 5d6 | 3m (degrades to 2d6 at 10m) |
| Fall (per 2m) | 1d6 | — |
| Fire (ignited) | 1d6 per round | Contact |
| Chemical Leak | 1d4 per round (poison) | Leak area |
| Smoke Grenade | Smoke screen (3 rounds) | 5m radius |

---

## 2.9 Vehicle Rules

| Vehicle | Hit Points (HP) | Armor Damage Reduction (DR) | Speed | Handling Target Number (TN) | Crew |
|---|---|---|---|---|---|
| Off-road Motorcycle | 15 | 0 | 40m | 11 | 1+1 |
| Civilian Truck | 35 | 2 | 25m | 14 | 2+6 |
| Military Humvee | 45 | 4 | 30m | 14 | 2+4 |
| Armored Personnel Carrier | 60 | 6 | 20m | 17 | 3+8 |
| Extraction Helicopter | 30 | 2 | 60m | — | 2+6 |

**Driving Check:** 3d6 + Precision ≥ Handling Target Number (TN) (hazardous conditions). Collision: (Speed/10)d6. Hit Points (HP) ≤25% halves speed; Hit Points (HP) =0 → explodes next round (3d6/10m).

## 2.10 Stealth / Vision Unified

| Lighting | View Distance | Shooting | Stealth |
|---|---|---|---|
| Bright | Normal | Normal | Normal |
| Dim | −20m | Disadvantage | +2 |
| Dark | −50m | Double Disadvantage | +4 |
| Total Darkness | 0m | Cannot aim | Automatic success |

**Hearing Distance:** Footsteps (stealth) 5m (Target Number (TN) 17) / Footsteps (normal) 15m (Target Number (TN) 11) / Gunshot (rifle) 500m (Target Number (TN) 8) / Explosion 2km (Target Number (TN) 8)

## 2.11 Independent Part Armor

Each part independently tracks Damage Reduction (DR). Helmet = Head, Body Armor + Vest = Chest/Abdomen, Gloves = Both Arms, Combat Boots = Both Legs. Damage Reduction (DR) cannot stack above 5.

## 2.12 Dual-Wielding / Prone / Friendly Fire Quick Reference

- **Dual Pistol Volley:** 2 Action Point (AP), each of two shots −2. **Alternate Fire:** 1+1 Action Point (AP), each −1. **Gun-Sword Dual-Wield:** shooting −1 + melee normal.
- **Prone:** attackers have Double Disadvantage, self attacks at Disadvantage, crawl 2m/Action Point (AP), stand up 1 Action Point (AP).
- **Full-auto Friendly Fire on Ally:** 3d6≤9 (~26%). **Grenade Scatter:** on failure, deviates 1d6~2d6m (d8 direction).

## 2.13 Weather and Environment (d20)

| d20 | Weather | Effect |
|---|---|---|
| 1-8 | Haze Layer (default) | Dim lighting, view distance −20m |
| 9-11 | Dense Haze | Dark lighting, view distance −50m |
| 12-13 | Rain | Hearing −2, Movement −1m/Action Point (AP) |
| 14-15 | Acid Rain | Rain + 1 corrosion per 30 min without protection |
| 16-17 | Strong Wind | Throwing −2, smoke disperses in 1 round |
| 18 | Stagnation | Sound propagation ×2, anomaly intensity +1 |
| 19 | Pulse Surge | Electronic devices fail on 3d6≤8 |
| 20 | Double Anomaly | Re-roll twice, effects stack |

## 2.14 Ammo Pickup

| Enemy | Can Pick Up | Enemy | Can Pick Up |
|---|---|---|---|
| Newbie/Scavenger | 9mm 1d12 | Warlord Soldier | 5.56 2d8+9mm 1d6 |
| Lone Wolf Veteran | 7.62 1d8 | Elite/Boss | 5.56 3d10+special 1d4 |

## 2.15 NPC Name Generator

| d20 | Name | Nickname | | d20 | Name | Nickname |
|---|---|---|---|---|---|---|
| 1 | Alexei | Iron Fist | | 11 | Anna | Cat |
| 2 | Victor | Ghost | | 12 | Ekaterina | Redhead |
| 3 | Sergei | Doctor | | 13 | Olga | Nightingale |
| 4 | Ivan | Rat | | 14 | Natalia | Ice Cube |
| 5 | Mikhail | Silent | | 15 | Svetlana | Witch |
| 6 | Nikolai | Old Dog | | 16 | Irina | She-Wolf |
| 7 | Andrei | Lucky | | 17 | Tatyana | Crow |
| 8 | Dmitri | Vulture | | 18 | Maria | Spark |
| 9 | Yuri | Shell Casing | | 19 | Vera | Ghost |
| 10 | Pavel | Scar | | 20 | Katya | Dagger |

# Chapter Three: NPC and Enemy Templates

▶ Enemy templates such as Residuals, Mutant Hound, Mutants, Lone Wolf Veteran, Warlord Patrol, Bounty Hunter, and Boss "Iron Wall" Cossack are detailed in **assets/怪物圖鑑.md**.

## 3.8 Encounter Difficulty Budget

| Player Level | Recommended Total Threat Value | Rough Equivalent |
|---|---|---|
| Level (Lv.) 1 (2-3 players) | 6-10 | 2-3 Residuals, or 1 Lone Wolf Veteran |
| Level (Lv.) 1 (4 players) | 8-14 | 3-4 Residuals, or 1 Mutant + 1 Residual |
| Level (Lv.) 3 (4 players) | 14-22 | 4 Warlord Soldiers, or 2 Mutants |
| Level (Lv.) 5 (4 players) | 18-28 | 5 Warlord Soldiers, or 1 Bounty Hunter + 3 Soldiers |
| Level (Lv.) 7+ (4 players) | 24-40 | Boss + reinforcements, or mixed elite team |

---

# Chapter Four: Setting

## 4.1 Curtain Collapse

Three years ago, the Northern Federation's "Ashila Research Facility" lost control of its codenamed "Curtain" high-energy physics experiment, tearing open an unstable Dimensional Rift. An Anomalous Pulse spread outward from the facility, rewriting the physical constants, biological structures, and even the flow of time within a 20 km radius.

This area became known as the **Quarantine Zone (QZ)**. The Quarantine Zone Administration Commission (QZAC) surrounds it with the Perimeter Wall. But walls cannot block human nature — Scavengers hunt through the ruins for a chance at fortune or atonement.

## 4.2 Five Factions

| Faction | Role | Territory | Attitude Toward Players |
|---|---|---|---|
| **Quarantine Zone Administration Commission (QZAC)** | Official quarantine management | Perimeter Wall | Turns a blind eye |
| **Scavengers' Compact** | Scavenger mutual-aid alliance | Old Town safehouse | Welcomes rule-abiders |
| **Iron Brotherhood** | Rebel military organization | Industrial Zone | Strong territorial awareness |
| **Order of the Watchers** | Anomaly-worshipping cult | Core Zone edge | Not actively hostile |
| **Smuggler's Ring** | Illegal external trade | Secret routes | Pure transaction |

### Reputation System (Hidden Value)

| Tier | Range | Effect |
|---|---|---|
| Nemesis | Below −50 | Actively hunts you down |
| Hostile | −20∼−49 | Opens fire on sight |
| Cold | −19∼−1 | Trade price +20% |
| Neutral | 0 | Basic trade |
| Friendly | 1∼20 | Trade price −10% + intel |
| Respected | 21∼50 | Trade price −20% + special commission |
| Worship | 51+ | One of their own (see specific rewards below) |

### Reputation Gain/Loss

| Action | Impact |
|---|---|
| Complete faction commission | +5∼+15 |
| Kill faction member | −10∼−20 |
| Rescue faction member | +5∼+10 |
| Betray agreement | −15∼−25 |
| Provide valuable intel | +2∼+10 |

### Specific Rewards for Worship Tier of Each Faction

| Faction | Worship (51+) Reward |
|---|---|
| **Quarantine Zone Administration Commission (QZAC)** | Trade price −20%, **Helicopter Extraction** (arrives d6 rounds after call / any zone), **May commission clearing of one enemy outpost** (once) |
| **Scavengers' Compact** | Trade price −20%, **Old Ke accompanies sorties** (NPC ally), **Compact Sanctuary** (provides hiding when hunted), **Emergency Rescue** (50% rescued if extraction fails) |
| **Iron Brotherhood** | Trade price −20%, **Honorary Member** (Brotherhood soldiers across the zone assist), **Private meeting with Cossack** |
| **Order of the Watchers** | Trade price −20%, **Rift Blessing** (random low-tier mutation ability), **May request a cult ritual** (one powerful effect) |
| **Smuggler's Ring** | Trade price −20%, **Outside Passport** (retirement ending), **VIP Extraction Service** |

### Cross-Faction Reputation Conflicts

| Situation | Consequence |
|---|---|
| QZAC Worship + Brotherhood Worship | Both −10 (suspected double agent) |
| Cult Worship + QZAC Friendly or above | QZAC lists you as a potential threat; reputation cap locked at Respected |
| Brotherhood Worship + Compact Respected or above | Compact reputation −20 (betraying the Scavenger class) |
| Any faction at Nemesis | Every 1d4 sorties, a hit squad is dispatched (Threat Value 8-12) |

---

# Chapter Five: Geography

## 5.1 Quarantine Zone Layout (Concentric Rings, ~200 km²)

| Zone | Distance from Core | Danger | Main Faction | Loot Quality |
|---|---|---|---|---|
| Edge Zone | 15-20km | ★☆☆☆☆ | QZAC, Newbies | Junk~Common |
| Old Town | 8-15km | ★★★☆☆ | Compact, Smugglers | Common~Rare |
| Industrial Zone | 3-8km | ★★★★☆ | Brotherhood, Cult | Rare~Military |
| Core Zone | 0-3km | ★★★★★ | Unknown | Military~Legendary |

## 5.2 Sample Map One: "Ash Mall" (Edge Zone ★☆☆☆☆)

500m×400m, three-story shopping center + parking garage + gas station. Suitable for Level (Lv.) 1-2.

**Landmarks:** Food Court (medical supplies), Electronics Store (electronic parts), Underground Parking Garage (vehicle parts/ambush point), Management Office (keys/intel), Gas Station (fuel)

**Entry Points:** East service entrance (low risk), north bus stop (low-medium), west ventilation duct (medium)

**Extraction Points:** East parking lot (fixed/flare gun), behind gas station (fixed/requires waiting), rooftop helipad (hidden/requires key + flare gun)

**Loot Distribution:** Junk (corridors), Common (store shelves), Rare (management office/electronics store warehouse)

**AI/Encounters:** Residuals 2-5, Mutant Rats 0-1, NPC encounters 5+ (d10) / 30 minutes

## 5.3 Sample Map Two: "Silent Community" (Old Town ★★★☆☆)

600m×500m, six blocks + community center + elementary school. Suitable for Level (Lv.) 2-4.

**Landmarks:** Clock Tower Apartment (sniper point), Community Center (safehouse), Convenience Store Street (rear warehouse), Elementary School (infirmary), Detached Housing District (locked basement)

**Entry Points:** Community north gate (open), sewer exit (hidden/possible Mutants), elementary school fence (hidden)

**Extraction Points:** Community north gate (fixed/may be occupied), clock tower top floor (hidden/flare gun), sewer escape hatch (conditional/requires key), school playground (random/open)

**Loot Distribution:** Junk (streets), Common (residences), Rare (basement/safehouse), Military (specific houses)

**AI/Encounters:** Residuals 3-8, Mutant Creatures 1-2, varied NPC Scavengers

## 5.4 Sample Map Three: "Rusted Factory" (Industrial Zone ★★★★☆)

800m×600m, heavy industrial park + chemical plant. Suitable for Level (Lv.) 4-7.

**Landmarks:** Furnace Workshop (military metal), Chemical Storage Zone (toxic gas hazard), Administration Building (Brotherhood HQ), Railway Freight Yard (sealed containers), Underground Pipeline (hidden route)

**Entry Points:** South perimeter breach (may be watched), west pipeline entrance (hidden), east scrap yard (lots of cover)

**Extraction Points:** South perimeter breach (fixed/Brotherhood blockade), railway freight yard (random/may be ambushed), underground pipeline escape hatch (hidden/one person only), administration building rooftop (conditional/requires radio)

**Loot Distribution:** Junk (periphery), Common (warehouse), Rare (chemical zone/containers), Military (administration building/supply crates)

**AI/Encounters:** Brotherhood patrols 2-3 teams (3-5 per team), Industrial Mutants 1-3, chemical leak toxic gas zone

---

# Chapter Six: Sortie Cycle Management

## 6.1 Hideout Handling (Two Modes)

**Quick Mode (single session):** 10-15 minutes. Summary-style menu — "You receive three commissions... the trader has the following items... depart when ready."

**Deep Mode (long campaign):** Detailed roleplay. Traders have personalities and side stories. Hideout upgrades come with narrative events. Other Scavengers may visit.

## 6.2 Entry Guidance

Entry is the transition from safety to danger. The GM should let players feel this shift.

Key narrative elements:
- The ritual feel of the "final check" — the weight of gear selection
- The physical presence of the boundary (perimeter wall, haze layer, ruins)
- Silence and ambient sound — do not immediately drop encounters upon entry
- A brief "illusion of safety" — relative calm in the first few minutes after entry

## 6.3 In-Zone Pacing Template (60 minutes)

| Time | Phase | Tension | Content |
|---|---|---|---|
| 0-10 min | Entry Period | Low | Environment description, familiarize with terrain |
| 10-25 min | First Scavenging Period | Medium | Loot points, patrol AI, distant gunfire |
| 25-35 min | Turning Point | High | High-value loot, NPC encounters, environmental changes |
| 35-45 min | Decision Period | Highest | Backpack nearly full — continue or extract? |
| 45-60 min | Extraction Period | Extreme | Countdown, extraction point conflict |

## 6.4 Tension GM Tools

| Tool | Method |
|---|---|
| Time Pressure | "The Pulse Surge will arrive in 30 minutes" |
| Auditory Cues | Distant gunfire, echoing footsteps — do not pinpoint the threat |
| Loot Temptation | "Through the crack you see a crate marked blue — but it's at the far end of the hall, fully exposed" |
| Terrain Pressure | The only retreat is blocked, the door locks behind you |
| NPC Pressure | Hearing radio chatter, a flashlight beam sweeping in the distance |
| Resource Ritual | Ask players to physically cross off ammo, mark their carry weight |

> **Most Important Principle:** Always give players a choice. The best tension comes from "I choose to keep searching, but I know it's dangerous" — not "the GM threw another wave of enemies."

---

# Chapter Seven: Commission System

## 7.1 Commission Types

| Type | Description | Difficulty Range | Reward Range |
|---|---|---|---|
| Scavenge | Bring back a specific item | Simple~Extreme | 500~20,000+ ₽ |
| Eliminate | Kill a specific target | Regular~Extreme | 1,000~20,000+ ₽ |
| Recon | Confirm location/target info | Simple~Hard | 500~5,000 ₽ |
| Rescue | Rescue a trapped NPC | Regular~Hard | 1,000~8,000 ₽ |
| Courier | Transport items in/out of the Quarantine Zone | Simple~Regular | 500~3,000 ₽ |
| Mark | Place a device at a specific location | Regular~Hard | 1,000~6,000 ₽ |

## 7.2 Difficulty and Reward

| Difficulty | Reward (₽) | Suitable Level | Extra Reward |
|---|---|---|---|
| Simple | 500-1,000 | Level (Lv.) 1 | Base favor +5 |
| Regular | 1,000-3,000 | Level (Lv.) 2-3 | Favor +10 |
| Hard | 3,000-8,000 | Level (Lv.) 4-6 | Favor +15, Rare item |
| Extreme | 8,000-20,000+ | Level (Lv.) 7+ | Favor +20, Military/Gold item |

---

# Chapter Eight: Extraction System

## 8.1 Extraction Point Types

| Type | Description | Example |
|---|---|---|
| Fixed | Location unchanged each time | Perimeter breach, main road |
| Random | Random location each sortie | Extraction beacon, helicopter landing point |
| Hidden | Requires specific condition to trigger | Underground passage, management office key |
| Conditional | Requires meeting specific conditions | Flare gun + radio, specific time window |

## 8.2 Extraction Point Conflict Scenarios

| Scenario | Description | Player Options |
|---|---|---|
| Occupied | An NPC squad is already using the extraction point | Wait → Negotiate → Fight → Relocate |
| Ambushed | A hostile faction has set an ambush at the extraction point | Counter-ambush → Relocate → Hard push |
| Time Pressure | Pulse Surge / extraction time limit approaching | Speed up → Lighten load → Take a gamble |
| Extraction Point Closed | Random extraction point fails early | Relocate to backup extraction point |

## 8.3 Consequences of Extraction Failure

**GM Suggested Ratio: 40% death, 60% other.**

| Consequence | Loss | Narrative Opportunity |
|---|---|---|
| Swallowed by Pulse Surge | All non-insurance-box equipment | The scene is rewritten upon return |
| Forced into Hiding | Partial equipment (GM-designated) | Survival scenario: find a way out |
| Captured | All equipment | New narrative thread: escape or negotiate |
| Death | Total loss | New character inherits (Inheritance rules) |

---

# Chapter Nine: NPC Scavenger Behavior AI

## 9.1 Five Behavior Modes

| NPC Type | Scale | Equipment | Discover → React → Fight → Retreat |
|---|---|---|---|
| Lone Wolf Veteran | 1 | Well-equipped | Long-range observation → Assess → Fire only when necessary → Retreat at Hit Points (HP) <50% |
| Newbie Team | 2-3 | Pistol/Shotgun | Nervous patrol → Panic → Wild fire → Flee at Hit Points (HP) <30% |
| Bounty Hunter | 1-2 | Well-equipped | Confirm target → Shout challenge → Engage → Retreat at Hit Points (HP) <40% |
| Scav Gang | 3-6 | Mismatched | Greedy search → Intimidate via numbers → Overwhelm with fire → Breaks after losing 2 members |
| Warlord Patrol | 3-5 | Heavy-armed | Fixed patrol → Fire on sight → Cover fire → Morale check after 50% losses |

## 9.2 Random Encounter Trigger

Each encounter check rolls d10; a 6+ triggers:

| Zone | Check Frequency | Description |
|---|---|---|
| Edge Zone | Every 30 minutes | Mostly newbie teams / lone wolves |
| Old Town | Every 20 minutes | Mixed types |
| Industrial Zone | Every 15 minutes | Brotherhood permanent + occasional cult |
| Core Zone | GM triggers at will | Extreme anomalies + legendary enemies |

## 9.3 Interaction Trigger Conditions

| NPC | Trade Intel | Negotiable | Cooperable | Intimidatable | Rescuable |
|---|---|---|---|---|---|
| Lone Wolf Veteran | ✅ | ❌ | Very rarely | ❌ | ❌ |
| Newbie Team | ✅ | ✅ | ✅ | ✅ | ✅ |
| Bounty Hunter | Conditional | ✅ | ❌ | ❌ | ❌ |
| Scav Gang | ✅ | ✅ | Not trustworthy | ✅ | ❌ |
| Warlord Patrol | ❌ | ❌ | ❌ | ❌ | ❌ |

---

# Chapter Ten: GM Running Techniques

## 10.1 Building Tense Atmosphere

| Technique | Specific Approach |
|---|---|
| Silence | Let players act in silence — do not interject |
| Auditory Cues | Distant gunfire, echoing footsteps, inhuman snarls — do not pinpoint the threat |
| Resource Ritual | Ask players to physically cross off ammo, mark their carry weight |
| Incomplete Information | "You hear three sets of footsteps — but cannot tell the direction" |
| Time Visualization | Place a countdown timer on the table |
| Physical Description | "Your hands are trembling. The aftertaste of adrenaline." |

## 10.2 Responding to Death

1. **Acknowledge** — Give the death a solemn description
2. **Let It Sink In** — Give other players 1-2 minutes to react
3. **Close the Loop** — Settle inheritance, let players see what was left behind
4. **Inherit** — Create a new character, show the inherited hideout
5. **Legacy** — Turn the old character into part of the world

## 10.3 Three Elements of Encounter Design

1. **Warning** — Give players a chance to perceive the threat (sound, footprints, radio interference)
2. **Choice** — Provide multiple response options (avoid, negotiate, ambush, hard push)
3. **Consequence** — Every encounter involves consuming or gaining resources

## 10.4 Encounter Types

| Type | Frequency | Description |
|---|---|---|
| Environmental Storytelling | Multiple | Distant sounds, bloodstains, abandoned camps — build atmosphere but do not force combat |
| Optional Encounter | 2-3 per sortie | Players may choose to approach or bypass |
| Corner Encounter | ≤2 per sortie | Unavoidable encounter, not to be used when extracting with a full pack |
| Boss Encounter | Special commission | Requires prerequisites, high risk high reward |

---

# Appendix A: Quick Reference

## Core Checks

`3d6 + Attribute + Skill ≥ Target Number (TN)` | Target Number (TN): 8/11/14/17/20/23/26

## Seven Parts

| Part | Hit Points (HP) Formula | Hit % | | Part | Hit Points (HP) Formula | Hit % |
|---|---|---|---|---|---|---|
| Head | PHY+6 | 5% | | Abdomen | PHY+8 | 15% |
| Chest | PHY×2+10 | 35% | | Left Arm | PHY+4 | 12% |
| | | | | Right Arm | PHY+4 | 12% |
| | | | | Left Leg | PHY+5 | 10% |
| | | | | Right Leg | PHY+5 | 10% |

## Loot

| Color | Value |
|---|---|
| Gray | 10-100 ₽ |
| White | 100-500 ₽ |
| Blue | 500-3,000 ₽ |
| Purple | 3,000-15,000 ₽ |
| Gold | 15,000+ ₽ |

## Quick Threat Value Reference

| Enemy | Threat Value |
|---|---|
| Residual | 3 |
| Mutant Hound | 5 |
| Mutant | 8 |
| Lone Wolf Veteran | 6 |
| Warlord Soldier | 7 |
| Bounty Hunter | 7 |
| Boss Cossack | 16 |

---

> **You are the demiurge of the Quarantine Zone. Let every piece of junk in the ruins have once belonged to someone, and let every footstep possibly be the last.**

---

# Chapter Eleven: Crafting System

## 11.1 Crafting Check

**3d6 + Tech + Crafting Skill ≥ Recipe Target Number (TN)**

| Item Rarity | Target Number (TN) | Minimum Workbench Level |
|---|---|---|
| Gray | 8 | Level (Lv.) 1 |
| White | 11 | Level (Lv.) 1 |
| Blue | 14 | Level (Lv.) 3 |
| Purple | 17 | Level (Lv.) 4 |
| Gold | 20 | Level (Lv.) 5 |

Success = complete. Failure (off by 1-3) = materials consumed, may retry. Critical Failure (off by 4+) = materials destroyed.

## 11.2 Ammo Recipes (Costs 1 Rest Action)

| Output | Materials | Workbench | Target Number (TN) |
|---|---|---|---|
| 9mm ×30 | Scrap Metal×5 + Industrial Chemicals×1 | Level (Lv.) 2 | 11 |
| 5.56 ×20 | Scrap Metal×8 + Industrial Chemicals×1 | Level (Lv.) 3 | 11 |
| 7.62 ×15 | Scrap Metal×10 + Industrial Chemicals×2 | Level (Lv.) 3 | 14 |
| 12-gauge ×15 | Scrap Metal×5 + Industrial Chemicals×1 | Level (Lv.) 2 | 11 |
| Armor-piercing Rounds×10 | Corresponding materials + Military-grade Metal×1 | Level (Lv.) 4 | 17 |

## 11.3 Tool/Attachment Recipes

| Output | Materials | Workbench | Target Number (TN) |
|---|---|---|---|
| Lockpicking Tools | Scrap Metal×3 + Tool Parts×2 | Level (Lv.) 1 | 11 |
| Suppressor (Pistol) | Scrap Metal×8 + Tool Parts×5 | Level (Lv.) 3 | 14 |
| Suppressor (Rifle) | Scrap Metal×15 + Tool Parts×8 | Level (Lv.) 3 | 17 |
| Simple Explosive (2d6) | Industrial Chemicals×3 + Electronic Parts×1 | Level (Lv.) 2 | 14 |
| Red Dot Sight | Electronic Parts×2 + Scrap Metal×5 | Level (Lv.) 3 | 14 |
| Foregrip | Scrap Metal×8 + Tool Parts×3 | Level (Lv.) 3 | 11 |
| ACOG 4× | Electronic Parts×5 + Scrap Metal×10 | Level (Lv.) 4 | 17 |

## 11.4 Medical Recipes

| Output | Materials | Workbench | Target Number (TN) |
|---|---|---|---|
| Bandages×3 | Rags×5 | Level (Lv.) 1 | 8 |
| First Aid Kit | Bandages×2 + Antibiotics×1 | Level (Lv.) 1 | 11 |
| Military First Aid Kit | First Aid Kit×2 + Antibiotics×2 | Level (Lv.) 3 | 14 |

## 11.5 Weapon Repair

| Tier | Workbench | Cost | Restores Durability |
|---|---|---|---|
| Simple Cleaning | Level (Lv.) 1 | 1 Rest Action | 10 |
| Standard Repair | Level (Lv.) 2 | +Scrap Metal×3 | 20 |
| Deep Repair | Level (Lv.) 3 | +Weapon Parts Kit×1 | 40 |
| Full Refurbish | Level (Lv.) 4 | +Weapon Parts Kit×2 | 60 |
| Master Restoration | Level (Lv.) 5 | +Military-grade Metal×1 | Fully restored |

---

# Chapter Twelve: Long Campaign Structure Guide

## 12.1 Three-Act Structure

| Act | Level | Tone | Zone | Key Events |
|---|---|---|---|---|
| **Survival** | Level (Lv.) 1-3 | Learn the rules | Edge Zone | Complete rookie contract, build trader relations |
| **Rise** | Level (Lv.) 4-7 | Faction maneuvering | Old Town → Industrial | Discover cult secrets, infiltrate Brotherhood, deal with Iron Fist Victor |
| **Truth** | Level (Lv.) 8-10 | Core secret | Industrial → Core | Cult leader, Iron Wall Cossack, close the rift |

## 12.2 Recommended Scenario Chains

| Route | Scenario Order | Feature |
|---|---|---|
| Standard | One→Two→Three→Four→Five→Seven→Eight→Nine→Ten | Balanced experience |
| Stealth | One→Two→Three→Four→Six→Eight→Ten | Emphasis on stealth/intel |
| Combat | One→Two→Five→Six→Seven→Nine→Ten | Emphasis on combat |
| Cult | One→Three→Four→Eight→Ten | Focus on cult storyline |

## 12.3 World State Tracking

| State | Trigger | Consequence |
|---|---|---|
| Brotherhood Internal Split | Scenario Seven completed | Some soldiers in Scenario Nine do not fight |
| Cult Radicalization | Scenario Four or Eight completed | Cult encounter frequency ×2 |
| Intensified Pulse Surge | Level (Lv.) 5+ | Frequency becomes every 2-3 days |
| QZAC Intervention | QZAC reputation Respected+ | Unlock helicopter extraction |
| Unstable Rift | Level (Lv.) 8+ | Random rifts appear on the Core Zone periphery |

## 12.4 Campaign Endings

| Ending | Condition |
|---|---|
| **Rift Closed** | Complete Scenario Ten → Quarantine Zone decays, players become legends |
| **Choose to Leave** | Smuggler Worship → Outside Passport retirement |
| **Become the New Warlord** | Eliminate Cossack then take over the Brotherhood |
| **Knowledge Guardian** | Obtain all Curtain data but do not release it → permanent agent of Owl's organization |

---

# Chapter Thirteen: Rest Phase and Survival

## 13.1 Rest Action Rules

After each sortie, enter the Rest Phase (several days). You may perform **3 Rest Actions**. The GM should have each player declare, then resolve one by one.

| Action | Check | Success Effect |
|---|---|---|
| Training | 3d6+Attribute≥14 | Choose one skill to gain 1 training point (accumulate to required points = level up) |
| Intelligence Gathering | 3d6+Tech≥Target Number (TN) (zone) | Gain extra intel on next sortie |
| Socializing | 3d6+Courage+Persuasion≥11 | Trader favor +1d10; ≥17 = triggers special dialogue event |
| Equipment Maintenance | — | Restore weapon durability 5+(Armory Lv×5) |
| Market Trade | 3d6+Courage+Persuasion≥11 | List for sale at 110% price; failure = 90% |
| Rest & Relax | — | Remove 1d3 stress (Infirmary Level (Lv.) 3+ = 2d3) |
| Hideout Upgrade | — | Pay upgrade cost + materials |
| Anomaly Research | 3d6+Tech+Electronics≥14 | Gain hidden properties of anomaly item |

## 13.2 Rest Random Events (d20)

Roll d20 at the end of each Rest Phase:

| d20 | Event |
|---|---|
| 1 | Debt collector visits / loan shark pitch |
| 2-3 | Stranger Scavenger knocks for help or trade |
| 4-5 | Random trader visits, limited-time discount |
| 6-7 | Faction delivers message or new commission |
| 8-9 | Discover items left by previous resident (Gray×1d3) |
| 10-14 | Nothing happens, calm |
| 15-16 | Random facility temporarily malfunctions (Tech Target Number (TN) 11 to repair) |
| 17-18 | Hideout burglarized (lose 1d10% funds, Vault Level (Lv.) 3+ immune) |
| 19 | Hostile faction sends a warning |
| 20 | Hidden item found in the wall (Blue-Purple×1) |

## 13.3 Food and Survival

- **Daily Need:** 1 food + 2 water. Tracked during Rest Phase.
- **Not tracked during sorties** (single sortie under 24 hours).
- **Deprivation:** Each missing portion of food/water → Stress +1.
- **3 consecutive days deprived:** Physique −1 (recovers 1 day after resuming eating).
- **Over 24 hours without sleep:** Every 6 hours Physique Target Number (TN) 11 or all checks at Disadvantage.
- **6 hours of sleep:** Remove fatigue + recover 1 Stress.

---

# Chapter Fourteen: Commission Library

#### 1.1 Simple Commissions (Level (Lv.) 1-2, Reward 500~1,200 ₽)

| # | Commission Name | Client | Type | Objective | Time Limit | Reward | Extra |
|---|---|---|---|---|---|---|---|
| S01 | A Rookie's First Contract | Owl | Scavenge | Encrypted data from Ash Mall management office | 75min | 1,200 | Intel Level (Lv.) 1 materials |
| S02 | Supply Courier | Smuggler | Courier | Deliver a crate of medicine to Silent Community safehouse | 90min | 800 | Smuggler favor +5 |
| S03 | Ammo Shortage | The Blacksmith | Scavenge | Bring back any caliber ammo ×50 | None | 500 | Open purchase discount |
| S04 | Missing Scout | Scavengers' Compact | Rescue | Find missing Compact member in Ash Mall underground parking garage | 60min | 1,000 | Compact favor +10 |
| S05 | Rodent Extermination | The Blacksmith | Eliminate | Mutant Rats ×6 in Ash Mall underground parking garage | None | 600 | Rat skins can be sold |
| S06 | Sample Collection | The Doctor | Scavenge | Any mutant creature tissue sample ×3 | None | 700 | Doctor favor +5 |
| S07 | Radio Relay | Owl | Mark | Install signal repeater on Ash Mall rooftop | 90min | 900 | Unlock extraction point intel |
| S08 | Veteran's Bet | Old Ke | Scavenge | Complete a sortie in Ash Mall without firing a single shot | None | 1,200 | Old Ke's special intel |
| S09 | Debtor's Commission | Debtor (NPC) | Rescue | His brother is trapped at an Edge Zone gas station | 60min | 600 | Can be recruited as hideout assistant |
| S10 | Food Supply | Snake Eye | Scavenge | Any canned food ×10 | None | 400 | Smuggler favor +3 |
| S11 | Flare Gun Recovery | QZAC | Scavenge | Recover 3 abandoned flare guns | None | 1,000 | QZAC favor +5 |
| S12 | Water Purifier | The Doctor | Scavenge | Find water purifier parts from Silent Community convenience store warehouse | 90min | 800 | Doctor favor +8 |

#### 1.2 Regular Commissions (Level (Lv.) 2-4, Reward 1,200~3,000 ₽)

| # | Commission Name | Client | Type | Objective | Time Limit | Reward | Extra |
|---|---|---|---|---|---|---|---|
| N01 | Secrets of the Underground Parking Garage | The Blacksmith | Scavenge | Weapon crate from deep military supply truck in Ash Mall | 90min | 1,800 | May keep weapons found |
| N02 | Distress Signal from Silent Community | The Doctor | Rescue | Rescue research team trapped in clock tower | 120min | 2,500 | Advanced medical kit |
| N03 | Smuggler's Package | Snake Eye | Courier | Deliver package into Silent Community sewer | 90min | 1,500 | Smuggler favor +15 |
| N04 | Clear the Residual Nest | Scavengers' Compact | Eliminate | Residuals ×8 inside Silent Community elementary school | None | 2,000 | Compact reputation +10 |
| N05 | Cult Surveillance | Owl | Recon | Confirm the range of Order of the Watchers activity in Silent Community | 120min | 1,800 | Unlock Intel Level (Lv.) 2 |
| N06 | Military Dog Patrol Route | QZAC | Recon | Map the Brotherhood patrol routes in the Industrial Zone | 150min | 2,500 | QZAC reputation +15 |
| N07 | Chemical Sample | The Doctor | Scavenge | Specific chemical agent from Rusted Factory chemical storage zone | 120min | 2,800 | Advanced antidote recipe |
| N08 | Communication Intercept | Owl | Mark | Install bug in Rusted Factory administration building | 120min | 3,000 | Intel Level (Lv.) 3 materials |
| N09 | Old Ke's Old Acquaintance | Old Ke | Rescue | Old Ke's former colleague trapped in a Silent Community basement | 90min | 2,000 | Key intel fragment on Core Zone |
| N10 | Evict the Scav Gang | Scavengers' Compact | Eliminate | Drive out the Scav Gang occupying the community center | None | 2,200 | Permanent safehouse usage rights |
| N11 | Weapon Test | The Blacksmith | Eliminate | Kill 10 Residuals with the new rifle provided by the Blacksmith | None | 1,500 | Keep the test weapon |
| N12 | Smuggling Route Survey | Snake Eye | Recon | Survey backup route from Silent Community to Industrial Zone | 150min | 2,000 | Unlock new hidden entry point |
| N13 | Medicine Shortage | The Doctor | Scavenge | Any Rare-tier or higher medical item ×5 | None | 2,500 | Medical discount 20% |
| N14 | Pulse Surge Data | Owl | Mark | Place data loggers at 3 locations during the Pulse Surge | 120min | 2,800 | Pulse Surge early-warning system |

#### 1.3 Hard Commissions (Level (Lv.) 4-6, Reward 3,000~8,000 ₽)

| # | Commission Name | Client | Type | Objective | Time Limit | Reward | Extra |
|---|---|---|---|---|---|---|---|
| H01 | The Basement Mystery | Owl | Recon | Investigate the secrets of all detached-house basements in Silent Community | 150min | 3,500 | Unlock Intel Level (Lv.) 3 |
| H02 | Brotherhood Armory | Smuggler | Scavenge | Steal prototype weapon attachment from armory in Rusted Factory administration building | 150min | 8,000 | Gold attachment ×1 |
| H03 | Chemical Factory Infiltration | The Blacksmith | Scavenge | Military-grade metal sample from Rusted Factory chemical storage zone | 120min | 5,000 | Workbench Level (Lv.) 3 materials |
| H04 | Bounty: Chemical Mutant | Scavengers' Compact | Eliminate | Eliminate the mutant in Rusted Factory chemical storage zone | None | 4,500 | Chemical protective suit |
| H05 | Brotherhood Warrant Officer | QZAC | Eliminate | Eliminate 1 Brotherhood patrol captain | 180min | 6,000 | QZAC reputation +20 |
| H06 | Cult Relic | Owl | Scavenge | Obtain ritual stone tablet from Silent Community cult stronghold | 150min | 5,000 | Unlock Curtain knowledge |
| H07 | Abandoned Container Inventory | Snake Eye | Recon | Confirm contents of all containers in Rusted Factory railway freight yard | 180min | 3,500 | +500 per confirmed container |
| H08 | Mutation Research | The Doctor | Scavenge | Capture one Industrial Mutant alive (requires sedative) | None | 7,000 | Mutation resistance drug recipe |
| H09 | Brotherhood Supply Line | Scavengers' Compact | Mark | Plant trackers on 3 Brotherhood supply routes | 150min | 4,000 | Compact reputation +25 |
| H10 | Encrypted Data Recovery | QZAC | Scavenge | Recover pre-Collapse research data from administration building server | 180min | 6,500 | QZAC reputation +25 |
| H11 | The Railway's Secret | Owl | Recon | Find the Brotherhood's hidden passage in Rusted Factory underground pipeline | 150min | 4,500 | Permanently unlock hidden extraction point |
| H12 | Bounty: Defected Officer | Iron Brotherhood | Eliminate | Eliminate the former Brotherhood officer who defected to the Industrial Zone edge | None | 5,000 | Brotherhood reputation +10 (rare) |

#### 1.4 Extreme Commissions (Level (Lv.) 7-10, Reward 8,000~30,000+ ₽)

| # | Commission Name | Client | Type | Objective | Time Limit | Reward | Extra |
|---|---|---|---|---|---|---|---|
| E01 | Iron Fist Victor | Scavengers' Compact | Eliminate | Eliminate Brotherhood regional commander Victor | 180min | 12,000 | Compact reputation +40 |
| E02 | The Cult's Secret | QZAC | Recon | Investigate the cult's ritual activity on the Core Zone edge | 240min | 15,000 | QZAC reputation +20, Intel Level (Lv.) 5 |
| E03 | Iron Wall Cossack | All Factions | Eliminate | Eliminate Iron Brotherhood leader Cossack | None | 25,000 | Gold weapon ×2 |
| E04 | The Deep Laboratory | QZAC+Compact+Smuggler | Mark | Close the Ashila Facility dimensional rift | None | 100,000 | Legendary status + all Gold ×3 |
| E05 | Cult Leader | QZAC | Eliminate | Eliminate the Order of the Watchers leader | 240min | 18,000 | QZAC reputation +30, Curtain data |
| E06 | Core Zone Recon | QZAC | Recon | Map the Core Zone periphery + mark anomaly points | 240min | 12,000 | QZAC reputation +25 |
| E07 | Clear the Brotherhood Remnants | Scavengers' Compact | Eliminate | After Cossack's death, clear 3 remaining Brotherhood strongholds | None | 15,000 | Industrial Zone passage rights |
| E08 | Rift Sample | The Doctor | Scavenge | Obtain rift energy sample from Core Zone edge | 240min | 20,000 | Ultimate medical recipe |
| E09 | Smuggler's Ultimate Commission | Snake Eye | Courier | Transport the Dimensional Resonator out of the Quarantine Zone to an outside buyer | 240min | 30,000 | Unlock outside contact |
| E10 | The Truth of the Curtain | Old Ke | Recon | Enter the Deep Laboratory to obtain complete data on the truth of the Collapse | None | 20,000 | All-faction reputation +50, world truth revealed |

---

---

# Chapter Fifteen: Side Storylines

#### 2.1 Old Ke's Past

**Trigger:** Complete 3 Scavengers' Compact commissions
**Progression:**
1. Old Ke begins to reveal he was once the head of security at the Ashila Facility
2. Commissions the players to find his personal belongings left in the Silent Community clock tower
3. Find a photo of Old Ke's daughter — she worked inside the facility at the time of the Collapse
4. Old Ke gives you the backup security code for the Deep Laboratory (key item for Scenario Ten)
5. If you return alive and tell him the truth, Old Ke leaves the Quarantine Zone after leaving all his savings to you

#### 2.2 The Blacksmith's Secret Recipe

**Trigger:** Blacksmith favor Level (Lv.) 3+
**Progression:**
1. The Blacksmith reveals he was formerly an engineer in the military weapons R&D department
2. Commissions you to retrieve his confiscated blueprints from the Rusted Factory
3. The blueprints reveal the complete manufacturing process of the prototype shock hammer
4. The Blacksmith can forge Gold weapons for you (you supply the materials)
5. If he learns the blueprints were copied by the Brotherhood, he commissions you to destroy the Brotherhood's version

#### 2.3 The Doctor's True Identity

**Trigger:** Doctor favor Level (Lv.) 3 + complete 2 medical commissions
**Progression:**
1. While treating you, the Doctor casually mentions "the side effects of the Curtain experiment"
2. You may press further — the Doctor was once the medical director of the Ashila Facility
3. He carries one thing with him: an unaltered medical record from the day of the Collapse
4. The record mentions "Test Subject Zero" — a person infected by rift energy even before the Collapse
5. The Doctor is searching for this person. The clue points to the Core Zone.

#### 2.4 Owl's Chess Game

**Trigger:** Owl favor Level (Lv.) 4 + complete 5 intel commissions
**Progression:**
1. Owl reveals he does not act alone — he is an agent of an outside organization
2. The organization's goal is to ensure "Curtain technology" is not monopolized by any faction
3. He needs you to steal one piece of key intel from each of the five factions
4. Upon completion, it is revealed: an outside secret military operation against the Quarantine Zone is being brewed
5. Branching ending: assist Owl to stop the operation / sell the intel to QZAC / sit back and reap the benefits

#### 2.5 The Debtor's Redemption

**Trigger:** Character origin is "Debtor"
**Progression:**
1. The debt collector sends someone to collect — a Bounty Hunter appears at the hideout door
2. Choices: pay off the debt / take the collector's dangerous commission to offset it / try to eliminate the debt collector
3. If choosing the debt-offset commission: go deep into the Industrial Zone to fetch a Gold item
4. The faction behind the debt collector is high-level within the Smuggler's Ring
5. Upon completion, gain a permanent passive: Negotiation Instinct upgraded (buy price −10%, sell price +10%)

#### 2.6 The Border Dweller's Hidden Route

**Trigger:** Origin is Border Dweller + Level (Lv.) 3+
**Progression:**
1. A mark on a hand-drawn map suddenly makes sense — it is a sign left by your grandfather
2. On-site investigation of the marked location: an abandoned weather station on the Core Zone edge
3. Beneath the weather station is a secret shelter built before the Collapse
4. Inside: your grandfather's relics + a route in and out of the Core Zone never discovered by anyone
5. This route can be used permanently, and completely avoids all known factions

#### 2.7 The Mutant Adapted's Mutation

**Trigger:** Origin is Mutant Adapted + Level (Lv.) 5+
**Progression:**
1. Your mutation begins to evolve — gain a new sensory ability (GM's choice)
2. The Doctor is very interested and offers a free examination
3. Exam result: your DNA is actively adapting to rift energy — you are a living "Curtain Resonator"
4. Once the cult learns of this, they try to recruit you (or kidnap you as the ritual core)
5. Ending: you may choose to suppress the mutation (return to normal) or fully accept it (permanently gain teleportation ability, but Charisma permanently −2)

#### 2.8 The Veteran's Brotherhood Ties

**Trigger:** Origin is Veteran + first encounter with Brotherhood soldier
**Progression:**
1. The Brotherhood soldier hesitates upon seeing your dog tags — does not open fire immediately
2. One of them recognizes your unit insignia: he served in the same unit as you
3. He gives you a choice: join the Brotherhood, or at least remain neutral
4. If choosing cooperation: can obtain a Brotherhood pass (free movement in the Industrial Zone)
5. If refused: the Brotherhood treats you as a "Traitor," Threat Value +2 (against all Brotherhood soldiers)

#### 2.9 The Quarantine Zone Radio

**Trigger:** Radio equipment + tuning search during any sortie
**Progression:**
1. You accidentally receive a mysterious broadcast: a woman reading poetry
2. The frequency is different each time. The content received each time is different — as if passing on some kind of message
3. Owl tells you this radio is called "Voice of the Curtain" within the Quarantine Zone
4. Trace the signal source: the main broadcast tower of the Ashila Facility deep in the Core Zone
5. If you enter the broadcast tower: you find a female researcher trapped in a time bubble by rift energy — she has been broadcasting there for three years

#### 2.10 The Brotherhood's Traitor

**Trigger:** First time defeating a Brotherhood patrol captain (after Scenario Five)
**Progression:**
1. On the patrol captain's body you find an unsent letter — written to his daughter outside the Quarantine Zone
2. The letter reveals: he no longer wants to keep risking his life for Cossack, but defecting means execution
3. You may choose: ignore / deliver the letter (requires going through a smuggler) / seek out more Brotherhood members who want to defect
4. If you dig deeper: you discover a small faction within the Iron Brotherhood planning to overthrow Cossack
5. Ending: assist the coup — your Scenario Nine difficulty is lowered (someone inside the Brotherhood opens the door)

#### 2.11 The Smuggler's Treasure

**Trigger:** Snake Eye favor Level (Lv.) 5
**Progression:**
1. Snake Eye invites you to his private storage room — filled entirely with contraband shipped in from the outside
2. He takes out one thing: the "Prototype Blueprint" that leaked from the Ashila Facility before the Collapse
3. The blueprint depicts the true purpose of the "Curtain" experiment: it was never an energy experiment, but **weaponization**
4. QZAC knows the truth but has suppressed the news. Some outside want to restart this experiment.
5. Snake Eye asks you: sell the blueprint to the highest bidder, or destroy it?

#### 2.12 The Children of the Quarantine Zone

**Trigger:** Discover children's belongings in Silent Community during any sortie
**Progression:**
1. You discover traces of children living inside the Quarantine Zone — small footprints, leftover food
2. Old Ke tells you: a group of children separated from their parents during evacuation are protected by the Scavengers' Compact
3. One of the children is sick and needs specific medicine (only obtainable at the Industrial Zone chemical plant)
4. If you obtain the medicine: all Scavengers' Compact reputation resets to "Worship"
5. The children will give you a "lucky charm" they found in the ruins — a random Gold item

---

---


# Chapter Sixteen: Random Encounter d100 Tables

#### 3.1 Edge Zone (Ash Mall Area)

| d100 | Encounter | Type | Threat |
|---|---|---|---|
| 01-05 | Newbie Team ×2-3 (in panic, rescuable) | NPC | Low |
| 06-10 | Residual ×1d3 (patrolling) | Combat | Low |
| 11-14 | Lone Wolf Veteran ×1 (observes you from afar, does not attack proactively) | NPC | Medium |
| 15-18 | Mutant Rat Swarm ×2d4 (pours out from ventilation ducts) | Combat | Low |
| 19-22 | Scav Gang ×3-5 (scavenging, negotiable) | NPC | Medium |
| 23-26 | Abandoned QZAC supply crate (d6: 1-3=White, 4-5=Blue, 6=Trap) | Loot | — |
| 27-30 | Distant gunfire — a battle is happening somewhere (ends after d6 rounds) | Environment | — |
| 31-34 | Blood trail found in ruins leading to a hidden spot (Perception Target Number (TN) 14 → Blue ×1) | Loot | — |
| 35-38 | Minor gravity anomaly — items become lighter (carry weight temporarily halved, 10 min) | Environment | — |
| 39-42 | Radio receives distress signal from a stranger Scavenger | NPC | Medium |
| 43-46 | Residual ×1d4+1 (former store employees, gathered at the food court) | Combat | Medium |
| 47-50 | No one there but items have been rummaged — someone passed recently (Tracking Target Number (TN) 11 to identify direction) | Environment | — |
| 51-54 | Reinforced Residual ×1 (former mall security, wearing damaged body armor) | Combat | Medium |
| 55-58 | Pick up a backpack dropped by other Scavengers (random Gray-White items, 1d3 pieces) | Loot | — |
| 59-62 | Hear children's laughter — but there should be no children in the Quarantine Zone | Environment | — |
| 63-66 | QZAC patrol drone flies by (leaves after 30 sec; if photographed → QZAC reputation −2) | Environment | — |
| 67-70 | Bounty Hunter ×1 (looking for a specific target, ignores you if not it) | NPC | Medium |
| 71-74 | Discover a hidden room (the former mall manager's secret storage, Tech Target Number (TN) 14 to unlock) | Loot | — |
| 75-78 | Medium Mutant Creature ×1 (Mutant Hound or giant mutant rat) | Combat | Medium |
| 79-82 | Lone Wolf Veteran ×1 (wounded, Hit Points (HP) 50%, willing to trade intel for medical aid) | NPC | Low |
| 83-86 | Brotherhood Scout ×1 (rare — Brotherhood appearing in the Edge Zone, what does it mean?) | NPC | High |
| 87-90 | Gold-tier loot hint — footsteps lead to an overlooked store | Loot | — |
| 91-94 | Pulse Surge precursor — electronic devices begin flickering (Pulse Surge in 30 min) | Environment | — |
| 95-97 | Scav Gang ×4-6 (just found high-value items, in greedy state, attacks preferentially) | NPC | High |
| 98-99 | Gold item — unguarded but extremely exposed (Greed check Target Number (TN) 14) | Loot | — |
| 100 | Brotherhood Infiltration Squad ×4 (fully armed, conducting secret mission in Edge Zone) | Combat | Extreme |

#### 3.2 Old Town (Silent Community Area)

| d100 | Encounter | Type | Threat |
|---|---|---|---|
| 01-05 | Residual ×1d4 (former residents, performing daily activities in their homes) | Combat/Stealth | Low-Medium |
| 06-10 | Scav Gang ×3-6 (looting residences, negotiable/intimidable) | NPC | Medium |
| 11-13 | Lone Wolf Veteran ×1 (occupies clock tower as sniper point, watching the community) | NPC | Medium |
| 14-17 | Time Bubble ×1 (entered by chance, inside/outside time differs by 1d6×) | Environment | — |
| 18-21 | Newbie Team ×2-3 (lost, rescuable/guide for intel) | NPC | Low |
| 22-25 | Mutant Pet ×1 (mutated dog/cat of former community resident) | Combat | Low |
| 26-29 | Scavengers' Compact safehouse open (trade, rest, take new commissions) | Safe Zone | — |
| 30-33 | Complete family photo album found in abandoned residence (Gray×1 + narrative prop) | Loot | — |
| 34-37 | Gravity anomaly corridor — a 10m stretch of corridor with only 30% gravity | Environment | — |
| 38-41 | Hear radio communication from another Scavenger team (may attempt contact) | NPC | Medium |
| 42-45 | Cult Member ×2 (posting cult symbols, can talk to gain intel) | NPC | Low |
| 46-49 | Basement entrance — door locked but light leaks through (Tech Target Number (TN) 14 to unlock) | Loot | — |
| 50-53 | Residual ×2d3 (gathered at community center, seemingly holding some kind of assembly) | Combat | Medium |
| 54-57 | Smuggler's courier box (marked location, delivering earns 500₽ + favor) | Loot/Commission | — |
| 58-61 | Bounty Hunter ×1-2 (looking for you or someone else — Perception Target Number (TN) 14 to judge) | NPC | High |
| 62-65 | Abandoned medical station (First Aid Kit ×1d3 + possible blue medical items) | Loot | — |
| 66-69 | Ground collapse — the spot you just stepped on caves into a 3m-deep hole | Environment | — |
| 70-73 | Remnants of a cult ritual (can collect ritual items (Blue) ×1d2) | Loot | — |
| 74-77 | A note slipped under a detached-house door: "Something's in the basement. Don't go down. —M" | Environment | — |
| 78-81 | Warlord Patrol ×3 (Brotherhood rarely appears — what are they looking for) | NPC | Extreme |
| 82-85 | Abandoned vehicle — engine still starts (can be used for fast movement or making noise) | Loot | — |
| 86-89 | Hear knocking from the basement — someone is trapped | Commission Trigger | — |
| 90-93 | Spatially distorted residence — interior is 3× larger than exterior, may get lost | Environment | — |
| 94-96 | Cult Guardian ×1 (patrols cult territory, prioritizes expulsion over killing) | Combat | High |
| 97-98 | Gold item — hidden in a master-bedroom safe of some residence | Loot | — |
| 99 | Captured Brotherhood soldier (can be rescued for intel → leads to Brotherhood internal split clue) | NPC | — |
| 100 | High Cult Priest ×1 + Cult Member ×3 (conducting outdoor ritual) | Combat | Extreme |

#### 3.3 Industrial Zone (Rusted Factory Area)

| d100 | Encounter | Type | Threat |
|---|---|---|---|
| 01-05 | Brotherhood Patrol ×3-5 (fixed route, predictable movement) | NPC/Combat | High |
| 06-09 | Chemical leak zone (no protection = poison 1d4/round, lasts 1d6 rounds) | Environment | — |
| 10-13 | Industrial Mutant ×1 (bursts out of a storage tank) | Combat | Medium |
| 14-17 | Underground pipeline passage — can safely bypass a zone | Terrain | — |
| 18-21 | Brotherhood supply crate ×1 (combination lock, Tech Target Number (TN) 17 → Military items ×1d2) | Loot | — |
| 22-25 | Gravity anomaly zone — Movement halved, jump distance ×2 | Environment | — |
| 26-29 | Cult Member ×2 (secretly crossing Industrial Zone toward Core Zone, can talk) | NPC | Low |
| 30-33 | Lone Wolf Veteran ×1 (lurking in the shadows, also watching the Brotherhood) | NPC | Medium |
| 34-37 | Idle heavy machinery — can be used as cover or restarted (Tech Target Number (TN) 14) | Terrain | — |
| 38-41 | Brotherhood Soldier ×2 (resting off-route, may be ambushed) | Combat | Medium |
| 42-45 | Abandoned laboratory — pre-Collapse research equipment (Blue-Purple ×1d2) | Loot | — |
| 46-49 | Alarm sounds — the Brotherhood has discovered something, zone-wide alert level +1 | Environment | — |
| 50-53 | Iron Brotherhood infighting — two soldiers arguing (can eavesdrop for intel) | NPC | Low |
| 54-57 | Teleport-type Mutant ×1 (seeps from Core Zone, unstable teleportation) | Combat | High |
| 58-61 | Smuggler's dead drop — contains a message or item for you | Loot | — |
| 62-65 | Brotherhood Patrol Captain ×1 + Guards ×2 (high alert, hard to sneak past) | NPC/Combat | Extreme |
| 66-69 | Container cluster — some unopened (Tech Target Number (TN) 14-17 to unlock → random loot) | Loot | — |
| 70-73 | Unstable structure — ceiling collapse (Perception Target Number (TN) 14 or take 2d6 damage) | Environment | — |
| 74-77 | Deep Diver ×1 (infiltrates from Core Zone, foraging in Industrial Zone) | Combat | Extreme |
| 78-81 | QZAC secret reconnaissance team ×2 (disguised as Scavengers, can trade intel) | NPC | Medium |
| 82-85 | Military vehicle wreckage — can scavenge military parts (Purple) ×1 | Loot | — |
| 86-89 | Brotherhood emergency broadcast — zone-wide troop redeployment (all patrols change routes) | Environment | — |
| 90-92 | Cult Guardian ×1 + Cult Member ×2 (setting up an altar on the Industrial Zone edge) | Combat | High |
| 93-95 | Administration building sub-level entrance discovered (new exploration area) | Terrain | — |
| 96-97 | Elite Guard ×3 (on special mission, extremely hard to avoid) | Combat | Extreme |
| 98-99 | Gold item — container marked "Top Secret" by the Brotherhood | Loot | — |
| 100 | Iron Fist Victor or Iron Wall Cossack patrolling in person (Boss random encounter!) | Boss | Lethal |

#### 3.4 Core Zone Periphery

| d100 | Encounter | Type | Threat |
|---|---|---|---|
| 01-10 | Gravity fully inverted — ceiling becomes floor for 1d6 rounds | Environment | — |
| 11-20 | Time Bubble ×1 (1 inside round = 1d10 outside rounds) | Environment | — |
| 21-30 | Core Zone Mutant ×1d2 (surges from the rift direction) | Combat | Extreme |
| 31-40 | Dimensional Rift Fragment — touching grants brief precognition (Advantage on next check) | Environment | — |
| 41-50 | Deep Diver ×2-4 (hunting in packs) | Combat | High |
| 51-60 | Faulty Space — walked the same corridor three times before realizing space is looping | Environment | — |
| 61-70 | Teleport-type Mutant ×1d3 (group blink attacks) | Combat | Extreme |
| 71-80 | Ashila Facility abandoned research station (Purple~Gold ×1d2) | Loot | — |
| 81-90 | Dimensional Guardian's domain sense — feeling of being watched (Courage Target Number (TN) 17) | Environment | — |
| 91-95 | Pre-Collapse researcher Residual (non-hostile — retains full memory and language ability) | NPC | Low |
| 96-98 | Gold item — prototype equipment floating in rift energy | Loot | — |
| 99-100 | Dimensional Guardian ×1 (Boss random encounter — run or fight?!) | Boss | Lethal |

---

---


# Chapter Seventeen: Complete Pickup Item List

▶ The complete loot (pickup items) list is in **assets/物品圖鑑.md** (Chapter Three: Complete Pickup Item List).

# Chapter Eighteen: GM Quick Reference

#### 8.1 Quick Random Loot Generation

**General Containers:** Roll d100, consult the loot tier distribution:
- Edge Zone: 01-50=Gray, 51-85=White, 86-97=Blue, 98-100=Purple
- Old Town: 01-35=Gray, 36-75=White, 76-92=Blue, 93-99=Purple, 100=Gold
- Industrial Zone: 01-20=Gray, 21-55=White, 56-80=Blue, 81-95=Purple, 96-100=Gold
- Core Zone: 01-10=Gray, 11-30=White, 31-55=Blue, 56-85=Purple, 86-100=Gold

**Loot Bodies:** Based on NPC type:
- Residual: Gray×1-2
- Mutant Creature: White×1 + special material
- Newbie Team: Gray×2-3 + White×1-2
- Scav Gang: Gray×1-3 + White×1-2 + Blue×1 (50%)
- Lone Wolf Veteran: White×1-3 + Blue×1-2
- Bounty Hunter: White×2 + Blue×1-2
- Warlord Soldier: White×1-2 + Blue×1 + Purple×1 (30%)
- Elite/Officer/Boss: Blue×2-3 + Purple×1-2 + Gold×1

#### 8.2 Quick Encounter Generation

1. Roll d10 to determine if an encounter occurs: Edge 5+, Old Town 4+, Industrial 3+, Core Zone any
2. When an encounter triggers, roll d100 and consult the random encounter table for the corresponding zone
3. Encounter interval per sortie must be no less than 5 minutes of game time (except corner encounters)
4. Per sortie, the forced encounter cap (including Boss) by zone: Edge 2, Old Town 3, Industrial 4

---

> **Expansion Content Pack v1.0 — To be used with Rulebook v1.0. All values are aligned with the core rules (3d6 + Attribute + Skill ≥ Target Number (TN), Seven-Part Hit Points (HP), Damage Reduction (DR) system).**
