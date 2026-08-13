# Starship Convoy TRPG — GM Rulebook

> **Codename:** `fleet-trpg` | **Version:** v1.0
> **You will need:** one d20, the Player Manual, this rulebook, and a ship full of players who are always ready to cause trouble.

---

# Chapter 1: Complete Combat System

## 1.1 Turn Structure

```
[Each Turn]
1. Situation Phase → Sensor scan, range declaration, tactical discussion
2. Action Phase → Act in descending ENG-S order (players first, enemies second)
3. Resolution Phase → Status countdown, energy recovery, ongoing damage, morale
```

## 1.2 Action Economy (per ship / per turn)

| Action | Count | Description |
|------|:---:|------|
| Move | 1 | Change 1 range band (Engine (ENG-S) 4+ can change 2 bands) |
| Major Action | 1 | Attack / special ability / full-speed evasion / emergency repair |
| Bonus Action | 0–1 | Provided by some equipment / abilities |
| Reaction | 1/round | Triggered on enemy turn |
| Free Action | Unlimited | Communication, voting |

## 1.3 Range Band System

| Band | Range | Light | Medium | Heavy | Missile/Torpedo |
|----|------|:---:|:---:|:---:|:--------:|
| C Close | 0–100 km | 0 | 0 | -2 | -4 |
| M Medium | 100–1,000 km | -2 | 0 | 0 | 0 |
| F Far | 1,000–10,000 km | -4 | -2 | 0 | 0 |
| X Extreme | 10,000+ km | N/A | -4 | -2 | 0 |

> The modifier is added to the target's **Evasion Class (AC)**.

## 1.4 Attack Formula

```
Attack = d20 + WPN + weapon accuracy vs AC(10 + ENG-S + range + status)
Damage = weapon die + MoS − ARM×2 + penetration (minimum 1)
Critical (Natural 20) = full damage + ignore all armor
Malfunction (Natural 1) = weapon disabled for 1 turn
```

## 1.5 Margin of Success (MoS) Ladder (Attack Only)

| Margin of Success (MoS) | Effect |
|:---:|------|
| 0–2 | Normal |
| 3–6 | +2 damage |
| 7–10 | +4 damage + target subsystem damage check Difficulty Class (DC) 12 |
| 11+ | +6 damage + target directly triggers system damage |

## 1.6 Energy System

```
Energy Cap = ENG-S × 5 + 10 | Recovery = ENG-S / turn
```

| Use | Energy | Timing | Effect |
|------|:---:|------|------|
| Shield Charge | 5 | Major | Armor (ARM)×3 temporary Shield (cap Armor (ARM)×5) |
| Weapon Overload | 3 | Before attack | +1 weapon die, then overheats for 1 turn |
| Engine Overload | 4 | Move | Move 2 bands / Evasion Class (AC) +4 |
| Emergency Turn | 3 | Reaction | Evasion Class (AC) +3 (single attack) |
| Sensor Overload | 4 | Major | Reveal stealth + attack +2 |
| Emergency Repair | 5 | Major | 2d6+Engineering (ENG) Hull Points (HP) / clear system damage |
| Seize Position | 3 | Situation | Engine +2 (initiative + AC) |

## 1.7 Hull Damage

| Stage | Hull Points (HP) | Effect | Repair Difficulty Class (DC) |
|------|:--:|------|:-----:|
| Intact | 76–100% | Normal | — |
| Light | 51–75% | No penalty | 12 |
| Moderate | 26–50% | 1 system damaged (d6) | 15 |
| Severe | 1–25% | 2 systems damaged + global −2 | 18 |
| Disabled | 0% | Loss of power | — |

### System Damage d6

| d6 | System | Effect |
|:--:|------|------|
| 1 | Engine | Evasion Class (AC) −3, move −1 band, energy recovery −2 |
| 2 | Weapon | Attack −3, damage −2 |
| 3 | Sensors | Attack −2, cannot lock on / detect stealth |
| 4 | Shield | Reset to zero, cannot raise new shields, +3 damage when hit |
| 5 | Energy Leak | Energy cap halved, −1d4 per turn |
| 6 | Life Support | Crew takes 1 damage every 3 turns, Loyalty −1 if not repaired |

> **Hull Points (HP) reaching zero = Disabled, not destroyed.** It can be rescued, captured, or abandoned — leaving room for drama.

## 1.8 Weapons and Equipment

▶ For the full list of weapons, hull modules, personal equipment, and consumables, see the **Item Compendium** (`assets/物品圖鑑.md`).

## 1.9 Ship-Type Tactical Abilities

### Combat Escort Frigate
| Ability | Energy | Effect |
|------|:---:|------|
| Shield Amplifier | 5 | Reaction — Armor (ARM)×3 temporary Shield to self or a Medium-range friendly ship |
| Fire Suppression | 4 | Major — three-round burst 1d8+Margin of Success (MoS) |
| Taunt Position | 3 | Major — this ship's Evasion Class (AC) −2 but friendly ships' Evasion Class (AC) +4 |

### Mining & Processing Ship
| Ability | Energy | Effect |
|------|:---:|------|
| Mineral Cutting Laser | 2 | Major — 2d4+Margin of Success (MoS), penetration 3, attack −2 |
| Debris Shield | 3 | Reaction — against physical projectiles Evasion Class (AC) +5 |
| Emergency Smelting | 6 | Major — 1 Parts → friendly ship 3d6 Hull Points (HP) |

### Cargo Supply Ship
| Ability | Energy | Effect |
|------|:---:|------|
| Supply Drone | 3 | Major — deliver 1 Resource or recover 10 Energy |
| Ammo Dump Release | 2 | Major — 3 Ammunition → all friendly ships +1 Ammunition |
| Cargo Bay Cover | 4 | Reaction — Medium-range friendly ship treated as Extreme range this turn |

### Reconnaissance Scout Ship
| Ability | Energy | Effect |
|------|:---:|------|
| Stealth Device | 6 | Major — cannot be directly attacked, up to 2 turns |
| Target Lock Uplink | 4 | Bonus — friendly ship attacks on that target +3 and ignores range |
| Early Warning Array | 3 | Reaction — enemy attack becomes Disadvantage |

### Repair Engineering Ship
| Ability | Energy | Effect |
|------|:---:|------|
| Field Drydock | 8 | Major — this ship + Close-range friendly ships 2 Hull Points (HP)/turn, 3 turns |
| System Reboot | 6 | Major — clear all damage on friendly ship; +2d8 when Hull Points (HP) ≤25% |
| Overload Fabrication | 5 | Major — 2 Parts → 1 Ammunition or 1 Medicine |

## 1.10 Captain Command Abilities

| Command (CMD) | Uses/battle | Ability |
|:---:|:-----:|------|
| 1–2 | 1 | **Tactical Command:** friendly ship action +2 |
| 3–4 | 2 | + **Turning Point:** reroll a failed attack |
| 5+ | 3 | + **Convoy Rally:** all friendly ships' Evasion Class (AC) +2 |

## 1.11 Convoy Coordination

### Formations

| Formation | Effect |
|------|------|
| Escort | Escort frigates on the outer layer; attacking the inner layer requires passing interception |
| Search | Scout ship advances 1 band; Sensors +3; initiative +1 |
| Assault | Coordinated damage +2→+3; own Evasion Class (AC) −3 |
| Retreat | Non-combat ships retreat first; movement doubled; escort frigates' Evasion Class (AC) +2 |

### Coordinated Strike Chain

| Ship Count | Attack Bonus | Damage Bonus |
|:---:|:------:|:------:|
| 2 | +1 | +2 |
| 3 | +2 | +4 |
| 4+ | +3 | +6 |

## 1.12 Escape and Crew Casualties

**Escape:** Vote passes → collective Engine (ENG-S) check (take the lowest) vs Difficulty Class (DC) (10 + fastest enemy Engineering (ENG)-S) → on failure, the rear ship endures one round of full attack before breaking away.

**Crew Casualties:** Moderate damage → 1 minor injury / Severe damage → 1 serious injury / Hull Points (HP)=0 → survival check d20+Command (CMD) Difficulty Class (DC) 12, failure causes 1d3 deaths.

---

# Chapter 2: Enemy Units

▶ For all enemy units (pirate ships, space creatures, hyperspace anomaly entities) and quick-generation guidelines, see the **Bestiary** (`assets/怪物圖鑑.md`).

Below is a summary of the enemy quick-generation steps commonly used in combat:

1. Set Threat Level (TL) → allocate attributes (Engine/Armor/Firepower/Sensors/Special)
2. Calculate derivations: Hull Points (HP) = Armor (ARM)×10+20 | Evasion Class (AC) = 10+Engine (ENG-S) | Energy = Engine (ENG-S)×5+10 | Damage Reduction (DR) = Armor (ARM)×2
3. Choose weapon → grant 1–2 special abilities → define tactical script

---

# Chapter 3: Expanded Side Quest Library

## 3.1 Side Quest Generator

### Step One: Roll Quest Type (d10)

| d10 | Type |
|:---:|------|
| 1 | Rescue — someone is trapped and needs you |
| 2 | Recovery — there is something valuable somewhere |
| 3 | Transport — deliver X from A to B |
| 4 | Investigate — figure out what happened |
| 5 | Eliminate — something needs to be removed |
| 6 | Escort — protect a target until it reaches its destination |
| 7 | Infiltrate — sneak in somewhere to obtain intel/items |
| 8 | Negotiate — reach an agreement between two parties |
| 9 | Build — establish an outpost/facility somewhere |
| 10 | Compete — contend with other convoys for something |

### Step Two: Roll the Client (d8)

| d8 | Client | Typical Reward |
|:--:|------|------|
| 1 | Skyhook Group (天鉤集團) | Fuel quota + Credits (Cr) |
| 2 | Drifters' Alliance (漂泊者同盟) | Star chart data + intel |
| 3 | Relic Watchers (遺物守望者) | Ancient tech fragments |
| 4 | Independent Colony (獨立殖民地) | Supplies + safe harbor |
| 5 | Anonymous Employer (encrypted channel) | Double Credits (Cr), but of unknown origin |
| 6 | Other Convoy (其他船團) | Favor debt + alliance opportunity |
| 7 | Black Market Merchant (黑市商人) | Rare equipment + illegal cargo |
| 8 | Academic Institution (學術機構) | Research data + tech unlock |

### Step Three: Roll Location (d6)

| d6 | Location | Voyage Difficulty |
|:--:|------|:------:|
| 1 | Abyss Gate Sector (深淵門扇區) | Difficulty Class (DC) 10–12 |
| 2 | Ash Belt Edge (灰燼帶邊緣) | Difficulty Class (DC) 13–15 |
| 3 | Ash Belt Depths (灰燼帶深處) | Difficulty Class (DC) 16–18 |
| 4 | Starfall Sector (星墜扇區) | Difficulty Class (DC) 15–20 |
| 5 | Still Sea Sector Edge (靜海扇區邊緣) | Difficulty Class (DC) 18–22 |
| 6 | Still Sea Depths (靜海深處) | Difficulty Class (DC) 20+ |

### Step Four: Roll Twist (d8)

| d8 | Twist — things are not as they seem... |
|:--:|------|
| 1 | **Competitor:** Another convoy is also carrying out the same quest |
| 2 | **Trap:** The commission itself is a snare set by some faction |
| 3 | **Moral Dilemma:** Completing the quest will harm innocents |
| 4 | **Time Pressure:** Must be completed within X days, or else... |
| 5 | **Double Agent:** What the client truly wants is not the thing on the surface |
| 6 | **Hidden Cost:** The quest item/location has dangers no one told you about |
| 7 | **Unexpected Ally:** Encounter an unforeseen helper during the quest |
| 8 | **Truth Revealed:** Discover a secret during the quest that affects the entire star sector |

---

## 3.2 Preset Side Quests (20)

### Abyss Gate Sector Quests

**1. Fuel Express (Transport)**
> Skyhook Group needs an urgent batch of fuel delivered to Outpost B-7 on the edge of the Abyss Gate Sector. Reward: this month's fuel quota ×2. Twist: the outpost has actually been taken over by pirates — they will attempt to hijack the fuel. If the convoy delivers successfully, they will discover the outpost's personnel have been replaced.

**2. The Missing Survey Team (Investigate)**
> Three weeks ago, a five-person survey team went to the edge of the Ash Belt to investigate an abandoned military ship, then lost all contact. The Drifters' Alliance requests that the convoy travel to the last known coordinates to investigate. Reward: star chart update + 30% of whatever the survey team discovered. Twist: the survey team is still alive — but trapped by the automated defense AI aboard the military ship. The AI is still executing patrol orders from 110 years ago.

**3. The Commission from Below the Gate (Rescue)**
> A woman named Mara, from the lower levels of the Abyss Gate, implores the convoy to find her son — a youth who joined a smuggler convoy three months ago. Reward: meager (200 Cr), but she is the ex-wife of a mid-level Skyhook manager. Twist: the youth is actually doing fine — he has discovered the smuggler convoy's secret and is considering whether to report them.

**4. The Great Used-Ship Auction (Compete)**
> The Abyss Gate is about to auction a decommissioned military escort frigate (Swordfish-class refit). Multiple convoys are interested. The convoy must raise enough funds before the auction or find a rare item to trade. Reward: acquire the ship (can serve as a backup ship/mothership). Twist: the night before the auction, the ship is sabotaged — someone does not want it to fall into others' hands.

### Ash Belt Sector Quests

**5. Warship Graveyard (Recovery)**
> An intact Inheritance War–era destroyer has been found deep in the Ash Belt, still emitting an automated signal. The Relic Watchers offer to recover its "Tactical AI Core" — but on the condition that the hull is not destroyed (they regard it as a war memorial). Reward: ancient star chart + the Watchers' goodwill. Twist: there are survivors aboard — the original crew, cryo-sleeping for 110 years.

**6. The Rogue Harvester (Eliminate)**
> A wartime automated mining robot has gone rogue on the edge of the Ash Belt and is attacking passing ships. The local colony has posted a bounty to eliminate it. Reward: 5,000 Credits (Cr) + one year of free colony supplies. Twist: the robot contains a large amount of rare ore — eliminating it yields materials worth 15,000 Credits (Cr).

**7. The Black Box (Recovery)**
> An anonymous employer offers a high price to locate the flight recorder (black box) aboard a specific abandoned ship. Reward: 12,000 Credits (Cr), no questions asked. Twist: the black box recorded evidence that Skyhook Group deliberately sabotaged a rival ship ten years ago.

**8. The Smugglers' Secret Warehouse (Infiltrate)**
> Inside word from the Smugglers' Guild: a certain pirate boss has hidden a large cache of smuggled goods in an abandoned space station in the Ash Belt. The convoy can sneak in and take them — but the pirates' patrol is also nearby. Reward: everything in the warehouse. Twist: the warehouse holds not only cargo but also several kidnapped crew members — if they are rescued, the convoy earns great favor with the Drifters' Alliance.

### Starfall Sector Quests

**9. Alien Signal (Investigate)**
> A regular alien signal has been detected deep in the Starfall Sector — repeating every 47.3 minutes, of unknown origin. An Academic Institution requests that the convoy investigate. Reward: 8,000 Credits (Cr) in research funding + naming rights to the discovery. Twist: the signal comes from an alien facility still in operation — and something alive is inside.

**10. The Relic Watchers' Trial (Negotiate)**
> The Relic Watchers intercept the convoy with a deal: help them retrieve an item from an alien ruin (they cannot enter — the ruin reacts defensively to "impure intent"), and they will share an ancient star chart. Reward: the star chart leads to a resource-rich star system never before discovered. Twist: the retrieved item is actually an alien AI — the Watchers intend to destroy it, but it begs the convoy for protection.

**11. The Pilgrims' Path (Escort)**
> A group of pilgrims from the Star Temple wishes to travel to a "sacred ruin" in the Starfall Sector — said to be a religious holy site left by the first-generation colonists. They need the convoy to escort them through pirate-active zones. Reward: the Temple's blessing (free monthly supplies + permanent Advantage on spirit-related checks). Twist: the ruin is not a religious site at all — it is a pre-war secret laboratory. The pilgrim leader knows the truth, but the others do not.

**12. The Rival (Compete)**
> Another convoy, the "Children of the Stars," is also searching for the same alien relic in the Starfall Sector. Both sides know of the other's existence. You may choose to compete (whoever arrives first) or cooperate (share the discovery). Reward: the relic. Twist: if you choose to cooperate, the captain of the "Children of the Stars" is actually an old acquaintance of one of the player characters — the relationship value may shift as a result.

### Still Sea Sector Quests

**13. Alternate Route (Explore)**
> The Drifters' Alliance posted a bounty to find a safe passage through the Still Sea Sector — an alternate route that avoids pirate-controlled zones. Reward: 20,000 Credits (Cr) + lifetime fuel discount. Twist: the route does exist — but it passes through a Time Dilation Zone. Using it means the outside world fast-forwards by several months.

**14. The Lonely Outpost (Rescue)**
> Outpost C-12 on the edge of the Still Sea Sector has been silent for six months. The convoy is asked to go and check. Reward: if communications are successfully restored, the outpost can be claimed as the convoy's permanent base. Twist: the outpost's inhabitants are not dead — they discovered an alien substance that extends lifespan, but at the cost of being unable to leave this place.

**15. The Void Behemoth (Eliminate/Avoid)**
> A gigantic space creature wanders the edge of the Still Sea Sector, destroying many passing ships. Multiple factions have jointly posted a bounty to deal with it. Reward: 30,000 Credits (Cr) + any rare materials recovered from the behemoth's body. Twist: the behemoth is not a monster — it is protecting its young. If you choose to drive it off non-lethally, the Relic Watchers will grant you the highest respect.

### Cross-Sector Quests

**16. The Convoy Tournament (Compete)**
> Multiple convoys have organized a tournament at the Abyss Gate — a series of challenges (voyage, combat, exploration), with the winner receiving a brand-new starship. The convoy may sign up to participate. Reward: a new ship + star-sector fame. Twist: the tournament was orchestrated by Skyhook Group — they are using it to assess each convoy's strength and decide who is worth a long-term partnership.

**17. The Trial of the Traitor (Negotiate)**
> A captain has been accused of betraying the Drifters' Alliance — selling the Alliance's safe-route data to pirates. The Drifters' Alliance summons all convoys for a trial. The convoy may choose to serve as defense, prosecution, or jury. Reward: if the outcome matches a faction's expectations, earn that faction's great favor. Twist: the accused did sell the data — but the purpose was to infiltrate the pirates and obtain greater intel.

**18. The Vaccine (Transport)**
> A deadly plague has broken out on a colony, and the only vaccine is in a medical lab at the Abyss Gate. It must be delivered within 7 days — through pirate-active zones. Reward: the colony's permanent gratitude + priority supply for any need. Twist: the vaccine's side effect causes genetic mutation in 5% of those inoculated — the lab knows but has not disclosed it.

**19. The Legend of the Jump Gate (Explore)**
> Rumor has it that deep in the Still Sea lies an undiscovered "backup Jump Gate" — built during the Far Leap Project era, never activated. Whoever finds it can reconnect the Glass Sea Sector (玻璃海星域) with the outside world. Reward: incalculable. Twist: the Jump Gate does exist — but activating it requires consuming the complete energy core of one ship. Who will sacrifice?

**20. The Final Voyage (Mixed)**
> The Abyss Gate's fuel reserves have only one year left. Skyhook Group has announced a desperate plan — to organize a large joint convoy and set out into unknown deep space for one last great exploration, seeking new fuel sources or habitable star systems. All convoys are invited to join. Reward: humanity's future. Twist: not everyone wants to be saved — some believe staying in the Glass Sea Sector to await the end is better than taking the risk.

---

## 3.3 Crew Hidden Agenda Table (d20)

| d20 | Hidden Agenda |
|:---:|------|
| 1 | Search for a long-lost family member |
| 2 | Repay an old debt that cannot be refused |
| 3 | Save enough money to buy back their old ship |
| 4 | Secretly provide intel to some faction |
| 5 | Search for the "Flower of the Star Sea," said to cure any disease |
| 6 | Avenge a dead crew member — the target is in some pirate group |
| 7 | Prove they are more fit to command than the Captain |
| 8 | Hid a fortune somewhere in the star sector and wants to go back for it |
| 9 | Flee a past identity — someone is hunting them |
| 10 | Record the locations of all abandoned space stations in the star sector (reason unknown) |
| 11 | Find a legendary alien technology to save their home colony |
| 12 | Secretly follow a forbidden religion, searching for "omens" |
| 13 | Was once a pirate; old crew might recognize them |
| 14 | Owe a life-debt to someone "below the Gate" — who may come calling at any time |
| 15 | Suffers a rare disease that only a specific alien substance can ease |
| 16 | Once invented a technology stolen by Skyhook Group — wants it back |
| 17 | Believe someone in the convoy is a spy — investigating in secret |
| 18 | Once received a supernatural "summons" from the depths of the Still Sea |
| 19 | Had a romance with an NPC captain before joining the convoy |
| 20 | Secretly writing a book about the convoy — including all the awkward truths |

---

# Chapter 4: Random Encounter Generator

## 4.1 Port Event Table (d20)

Each time the convoy arrives at a port (Grade A–C), roll once:

| d20 | Event |
|:---:|------|
| 1–3 | **Uneventful** — a quiet resupply day, everything by the book |
| 4–5 | **New Face** — an interesting NPC appears at the port (roll on the NPC table below) |
| 6–7 | **Market Fluctuation** — a resource's price is abnormal (d6: 1–2 spike / 3–4 crash / 5–6 out of stock) |
| 8–9 | **Info Broker** — someone peddles intel, true or false unknown (50% true / 50% false, Diplomacy (DIP) Difficulty Class (DC) 15 to discern) |
| 10–11 | **Old Acquaintance** — an NPC crew member's past catches up with them (triggers a Hidden Agenda) |
| 12–13 | **Convoy Conflict** — two convoys are arguing in port, may drag in the players |
| 14–15 | **Limited-Time Offer** — the port store discounts a rare item, but only for today |
| 16–17 | **Emergency Call** — the port posts an urgent quest (quick-generate using the side quest generator) |
| 18–19 | **Faction Visitor** — a representative of some faction proactively contacts the convoy |
| 20 | **Unexpected Discovery** — something valuable is found somewhere in the port (GM's call) |

## 4.2 Port NPC Quick-Generation Table

| d12 | Type | Example |
|:---:|------|------|
| 1 | Retired Captain | Covered in scars, tells stories in the bar — half of what he says is true |
| 2 | Info Broker | Always in a trench coat, always in the corner — knows the departure time of every ship |
| 3 | Orphan | Parents died at sea; survives by stealing — may know the port's secret passages |
| 4 | Mechanic | Can turn trash into Parts, but is always drunk — Repair Difficulty Class (DC) −2, but 30% chance to break something else |
| 5 | Star Chart Merchant | Sells unverified star charts — 40% chance of a pleasant surprise, 60% chance of a nasty one |
| 6 | Bounty Hunter | Hunting someone — could be a player's crew member, or a player |
| 7 | Missionary | A priest of the Star Temple — can offer spiritual counseling, or recruit believers |
| 8 | Casino Owner | Runs an underground casino — can gamble money, Parts, or even a ship |
| 9 | Smuggler | Always has "special cargo" — the less you ask, the better the price |
| 10 | Refugee | Just escaped from some abandoned colony — may know valuable intel |
| 11 | Collector | Specializes in strange alien items — pays well, but only collects specific types |
| 12 | Spy | Secretly works for some faction — can the players detect them? (Intuition (INT) Difficulty Class (DC) 18) |

## 4.3 Deep Space Encounter Table (d20, while voyaging)

| d20 | Event | Resolution |
|:---:|------|------|
| 1–5 | **Calm Voyage** | No event, roleplay time |
| 6 | **Asteroid Belt** | Navigation (NAV) Difficulty Class (DC) 15 to avoid; failure → Hull 2d6 damage |
| 7 | **Derelict Ship** | Can explore: d6 (1–3 resources / 4–5 danger / 6 both) |
| 8 | **Distress Signal** | 50% genuine distress / 30% pirate trap / 20% already dead — only wreckage remains |
| 9 | **Space Creature (non-hostile)** | Detour (1 day +1 Fuel) or drive off (Sensors (SEN) Difficulty Class (DC) 13) |
| 10 | **Smuggler Encounter** | Diplomacy (DIP) Difficulty Class (DC) 15 → trade; failure → they flee; critical failure → report you |
| 11 | **Pirate Ambush** | d3+1 light pirate ships; may attempt Diplomacy (DIP) Difficulty Class (DC) 15 to pay passage toll |
| 12 | **Abandoned Outpost** | Can explore (same as derelict ship table) |
| 13 | **Radiation Storm** | Engineering (ENG) Difficulty Class (DC) 15 to protect systems; failure → Energy −2d6 |
| 14 | **Unstable Jump Point** | Drift off target star system by 1d3 days' voyage |
| 15 | **Drifting Cargo** | Cargo containers floating in space — d6 (1–2 resources / 3–4 junk / 5–6 hazardous material) |
| 16 | **Time Dilation Bubble** | Navigation (NAV) Difficulty Class (DC) 18 to detect and avoid; if not avoided → outside time fast-forwards 1d6 days |
| 17 | **War Ruins** | Automated defense system still active (Threat Level (TL) 1–2 drones) |
| 18 | **Alien Signal** | Regular signal of unknown origin — may lead to a side quest |
| 19 | **Convoy Encounter** | Meet another NPC convoy — friendly/neutral/hostile (d6: 1–2/3–4/5–6) |
| 20 | **Unknown Anomaly** | GM free reign: threat, opportunity, or worldbuilding secret |

## 4.4 Explore Derelict Ship Table (d20)

| d20 | Discovery |
|:---:|------|
| 1–3 | **Empty Ship** — thoroughly scavenged |
| 4–6 | **Parts Stash** — 2d6 Parts |
| 7–8 | **Fuel Residue** — 1d6×10 Fuel |
| 9–10 | **Cargo Residue** — 1d4 units of random resource |
| 11–12 | **Voyage Log** — contains valuable star chart or intel |
| 13 | **Weapon Stock** — 2d4 Ammunition |
| 14 | **Medical Supplies** — 1d6 Medicine |
| 15 | **Mod Parts** — 1 rare hull accessory |
| 16 | **Survivor** — in cryo-sleep |
| 17 | **Trap** — bait left by pirates (triggers ambush) |
| 18 | **Alien Item** — purpose unknown, may be valuable or dangerous |
| 19 | **Automated Defense** — onboard AI/robot still active |
| 20 | **Black Box** — flight data recording some important event |

## 4.5 Explore Planetary Surface Table (d20)

| d20 | Discovery |
|:---:|------|
| 1–3 | **Wasteland** — no value, but safe |
| 4–5 | **Mineral Resource** — Engineering (ENG) Difficulty Class (DC) 12, 2d6 ore |
| 6–7 | **Alien Plant** — Intuition (INT) Difficulty Class (DC) 15 → can be converted into 1d4 Medicine |
| 8–9 | **Abandoned Colony** — can be scavenged, see derelict ship table |
| 10–11 | **Geological Anomaly** — Navigation (NAV) Difficulty Class (DC) 15 → may discover rare minerals |
| 12–13 | **Ancient Ruin** — structure left by the Pioneers or an alien civilization |
| 14 | **Underground Cave** — may require days of exploration, high reward/high risk |
| 15 | **Dangerous Creature** — local predator of Threat Level (TL) 1–2 |
| 16 | **Water Source** — can resupply fresh water (reduces Food consumption by 20%) |
| 17 | **Natural Shelter** — can serve as a future outpost site |
| 18 | **Castaway Camp** — others are stranded here |
| 19 | **Alien Technology** — a functional alien device (GM's creative call) |
| 20 | **Major Discovery** — a major discovery tied to the core of the setting |

---

## 4.6 Voyage Event Difficulty Adjustments

Difficulty modifiers based on route and star sector:

| Route Type | Event Roll Modifier | Enemy Threat Level (TL) Modifier |
|---------|:---------:|:----------:|
| Safe Route | −4 (fewer events) | −1 (weaker enemies) |
| Normal Route | 0 | 0 |
| Dangerous Route | +4 (more events) | +1 (stronger enemies) |
| Abyss Gate Sector | −2 | −1 |
| Ash Belt | 0 | 0 |
| Starfall Sector | +2 | +1 |
| Still Sea Sector | +4 | +2 |

---

## 4.7 Random Treasure Table (d20)

| d20 | Treasure | Value (Cr) |
|:---:|------|:--------:|
| 1–5 | Rare Ore | 2d6×100 |
| 6–8 | Ancient Star Chart Fragment | 1d4×500 |
| 7–9 | Military Parts | 1d6×500 |
| 10–11 | Alien Relic | 2d4×1,000 |
| 12–13 | Prototype Tech | 1×3,000 (function pending appraisal) |
| 14–15 | Intel Data | Value fluctuates based on content |
| 16–17 | Artwork/Luxury Goods | 1d10×1,000 |
| 18–19 | Rare Hull Accessory | Priceless (cannot be purchased) |
| 20 | Dimensional Shard | Priceless (consumable: Jump auto-success) |

---

## 4.8 Quick Plot Hook Table (d20, Disaster/Accident)

| d20 | The convoy suddenly faces... |
|:---:|------|
| 1 | The main engine fails mid-jump — must emergency-anchor in an unknown star system |
| 2 | A crew member is infected by an alien parasite — must find a cure within 48 hours |
| 3 | Receives a distress signal from the future — sent by the convoy itself |
| 4 | Some cargo in the hold turns out to be alive — and dangerous |
| 5 | The shipboard AI begins acting abnormally — has it gained self-awareness? |
| 6 | Fuel is contaminated — all jump calculations are off by 2d6 light-years |
| 7 | A crew member was actually an undercover agent for some faction — but they now want to truly join the convoy |
| 8 | The Abyss Gate suddenly announces a 50% cut to fuel quotas — black market prices spike |
| 9 | Discovers a ship belonging to a convoy member — empty, floating in space, undamaged |
| 10 | Two factions simultaneously extend alliance invitations to the convoy — refusing either may provoke hostility |
| 11 | The convoy is framed for a major crime — must prove its innocence within the time limit |
| 12 | A child is hiding in the convoy's cargo hold — they come from a destroyed colony |
| 13 | Discovers a new fuel that can replace jump-drive fluid — but the raw material is extremely rare |
| 14 | The entire convoy is trapped in a time loop — every wake-up is the same day |
| 15 | The Relic Watchers declare some item of the convoy to be a "forbidden object" — demanding it be handed over |
| 16 | A crew member suddenly manifests psionic talent — extremely rare and feared in the star sector |
| 17 | Pirates propose an offer that cannot be refused: trade one piece of intel for the convoy's "one hour" |
| 18 | The convoy's jump accidentally opens a passage to unknown space — and the passage does not close |
| 19 | All communication channels are simultaneously overlaid by the same message — the sender calls themselves "the First Colonist of the Glass Sea" |
| 20 | The Abyss Gate's countdown suddenly accelerates — the fuel-exhaustion deadline shrinks from 20 years to 2 years |

---

## 4.9 Expanded Deep Space Event Table (d100, full version)

The table below integrates and greatly expands the deep space encounters; the GM can directly roll d100 to quickly generate voyage events.

| d100 | Event | Resolution |
|:----:|------|------|
| 1–15 | **Calm Voyage** | No event — prime roleplay time |
| 16–20 | **Asteroid Belt** | Navigation (NAV) Difficulty Class (DC) 13 to avoid; failure → Hull 1d6 damage / ship |
| 21–23 | **Micrometeorite Swarm** | Engineering (ENG) Difficulty Class (DC) 12 to block with shields; failure → 1d4 damage across the ship |
| 24–26 | **Abandoned Civilian Ship** | Explore (see derelict ship table), no automated defense |
| 27–29 | **Abandoned Military Ship** | Explore (see derelict ship table), 30% chance of automated defense |
| 30–31 | **Distress Signal (Real)** | Genuine survivors — possibly drifting crew or stranded colonists |
| 32–33 | **Distress Signal (Trap)** | Pirate bait — upon approach, 1d3+1 light raider craft ambush |
| 34–35 | **Distress Signal (Too Late)** | Only wreckage and a voyage log remain — recording some valuable intel |
| 36–37 | **Space Creature (Migrating)** | Interstellar jellyfish swarm — non-hostile, detour 1 day or drive off with Sensors (SEN) Difficulty Class (DC) 13 |
| 38–39 | **Space Creature (Juvenile)** | Small harmless creature cluster, can collect 1d4 biomass |
| 40–41 | **Smuggler Encounter** | Neutral smuggler ship. Diplomacy (DIP) Difficulty Class (DC) 13 → trade. Can buy black-market-priced supplies |
| 42–43 | **Smuggler (Panicked)** | A smuggler being hunted — jettisons cargo then accelerates to flee. Can freely pick up 2d4 random resources |
| 44–46 | **Light Pirate Ambush** | 1d3+1 light raider craft. May attempt Diplomacy (DIP) Difficulty Class (DC) 13 passage toll 1d6×50 Credits (Cr) |
| 47–48 | **Medium Pirate Raid** | 1 medium raider ship + 1d2 light. Diplomacy (DIP) Difficulty Class (DC) 17 passage toll |
| 49 | **Pirate Fleet** | 1 heavy flagship + 2d3 light. Recommend fleeing or a massive passage toll |
| 50–51 | **Radiation Storm** | Engineering (ENG) Difficulty Class (DC) 14 to protect systems. Failure → Energy −2d6, Sensors (SEN) −2 (restored by repair) |
| 52–53 | **Ion Storm** | All electronic systems interfered with. Navigation (NAV) Difficulty Class (DC) 15 to maintain course. Failure → drift off route by 1d3 days |
| 54–55 | **Gravity Anomaly** | Unknown gravity source pulls at the hull. Engine (ENG-S) versus Difficulty Class (DC) 15. Failure → Hull 2d4 damage |
| 56–57 | **Abandoned Outpost (Grade C)** | Small abandoned base — see derelict ship exploration table |
| 58–59 | **Abandoned Outpost (Grade D)** | Pre-war military facility — higher exploration Difficulty Class (DC) but greater reward |
| 60–61 | **Unstable Jump Point** | After the jump, drift off target by 1d4 days' voyage. Navigation (NAV) Difficulty Class (DC) 16 to correct |
| 62–63 | **Unexpected Jump Point** | Discover a jump point not on any star chart — may lead to unknown regions |
| 64–65 | **Drifting Cargo** | d6: 1–2 = 1d4 resources / 3–4 = junk (worthless) / 5 = valuable item / 6 = hazardous material |
| 66–67 | **Time Dilation Bubble (Small)** | Outside time fast-forwards 1d4 hours — minor effect but unsettling |
| 68 | **Time Dilation Bubble (Large)** | Navigation (NAV) Difficulty Class (DC) 18 to avoid. If not avoided → outside time fast-forwards 1d6 days. Extra Fuel/Food consumption |
| 69–70 | **War Ruins (Small)** | Abandoned sentinel drone (Threat Level (TL) 1, 1–2 units). Recoverable Parts |
| 71–72 | **War Ruins (Large)** | Abandoned destroyer wreckage. Automated defense still active (Threat Level (TL) 2). Abundant Parts |
| 73–74 | **Eerie Regular Signal** | Repeats every 47.3 minutes — origin unknown. May lead to an alien ruin side quest |
| 75–76 | **Musical Signal** | Music from deep space — origin unknown, disturbingly beautiful |
| 77–78 | **Friendly Convoy Encounter** | Meet an NPC convoy — friendly, can trade/exchange star charts |
| 79–80 | **Neutral Convoy Encounter** | A cautious neutral convoy — Diplomacy (DIP) Difficulty Class (DC) 13 to build a friendly relationship |
| 81–82 | **Hostile Convoy Encounter** | A rival convoy — friction or competitive quests may occur |
| 83–84 | **Space Whale** | A gigantic non-hostile space creature — a spectacular sight. Observation yields unique star chart data |
| 85–86 | **Cosmic Dust Cloud** | Can collect rare mineral particles — Engineering (ENG) Difficulty Class (DC) 15 → 1d4 rare alloy |
| 87–88 | **Lost Ship** | A ship from 80 years ago — crew still in cryo-sleep. They do not know the war has ended |
| 89–90 | **Pirate Derelict** | A ship abandoned by pirates — signs of a struggle inside. May have resources or intel |
| 91 | **Alien Probe** | A small alien device drifting in space — passively recording star-sector data |
| 92 | **Pioneer Beacon** | A navigation beacon left from the Far Leap Project era — malfunctioning, but repairable to obtain ancient route data |
| 93 | **Mysterious Cargo** | A sealed cargo container with no markings — contents unknown. Open it? (GM's call) |
| 94–95 | **EM Anomaly Zone** | All communications cut. Sensors fail. Can only navigate by visual means — Navigation (NAV) Difficulty Class (DC) 18 |
| 96–97 | **Hyperspace Echo** | Feel the "echo" of hyperspace in normal space — all crew Intuition (INT) Difficulty Class (DC) 13 to avoid headaches and hallucinations |
| 98 | **Dimensional Rift (Micro)** | A tiny dimensional rift — emits strange energy. Approach to collect 1 Dimensional Shard (consumable: Jump auto-success) |
| 99 | **Unknown Giant Structure** | A gigantic artificial structure floating in the stars — no known builder. May be the core discovery of this campaign |
| 100 | **GM Special Event** | Reserved entirely for the GM's discretion — can be anything |

## 4.10 Extended Side Quest Library (21-50)

### Abyss Gate Sector (深淵門) (cont.)

**21. Auction House Turmoil (Competition/Infiltration)**
> The upper tier of the Abyss Gate (深淵門) is about to host a black-market auction; the headline item is said to be the "Pioneer Jump Core (先驅者躍遷核心)" — a complete, never-used hyperspace engine. Multiple factions want it. The Convoy can: bid (requires a huge sum of Credits) or sneak in and steal it. Reward: the Pioneer Jump Core (can be installed on any ship — jump distance ×1.5). Twist: the core is fake — the real one was swapped out before the auction began. Who did it?

**22. Riot at the Gate's Bottom (Negotiation/Rescue)**
> The Skyhook Group (天鉤集團) announces cuts to the food rations at the bottom of the Gate, sparking a riot. The Convoy receives requests from both sides: the Skyhook Group demands help suppressing it, while the residents at the bottom of the Gate ask for help negotiating. Choose a side. Reward: Skyhook route → Fuel quota / Gate-bottom route → permanent Loyalty of the Gate-bottom residents and a secret passage network. Twist: Someone is instigating the riot from behind the scenes — a faction that wants to replace the Skyhook Group.

**23. The Last Navigator (Escort)**
> An 87-year-old former Far Leap Project (遠躍計劃) navigator — the last surviving Jump Gate (跳躍門) builder still alive — asks the Convoy to take her to the Still Sea Sector; she claims there is "a backup Jump Gate that was never activated." Her time is running out. Reward: If the Jump Gate exists, the Convoy will earn a place in history. Twist: She suffers from dementia — 50% of her memories are accurate, 50% are fabricated. Which parts are true?

### Ash Belt Sector (灰燼帶扇區) (cont.)

**24. Frozen Crew (Rescue)**
> A wartime medical ship is discovered deep in the Ash Belt, with 40 cryo-sleeping wounded soldiers still in its cryo-pods — from 110 years ago. Awakening them means forcing them to face a world with no home to return to. Not awakening them means letting them sleep forever. This is a Convoy vote. Reward: If awakened — 40 veterans possessing lost knowledge (some can be recruited as Crew). Twist: One of them is an important figure in a Player Character's backstory — an ancestor or relative.

**25. The AI's Last Wish (Recovery/Investigation)**
> The AI core of an abandoned warship is still operational — for 110 years it has carried out patrol orders alone. It contacts the Convoy over an encrypted channel, requesting to be "relieved of duty" — it wants to be shut down. But it is program-locked and cannot terminate itself. Reward: The complete military database within the AI core. Twist: Before shutting down, the AI provides some intel — at a specific set of coordinates there is an "anomalous energy reading." What is it?

**26. The Arms Dealer's Stock (Recovery)**
> An interstellar arms dealer had a secret warehouse deep in the Ash Belt — he died five years ago, and no one knows the warehouse's exact location. But fragments of his navigation log circulate on the black market. The Convoy can find the warehouse by piecing the log fragments together. Reward: Weapons and modification parts in the warehouse. Twist: The warehouse is not empty — someone got there first. But they are trapped inside, locked in by the Automated War-Ruins Defense System.

**27. The Two Colonies (Negotiation)**
> On the edge of the Ash Belt are two small colonies — one an agricultural colony, one a mining colony. They have long traded with each other, but recently conflict erupted over water rights, nearing the brink of civil war. Both sides ask the Convoy for help. Reward: Successful mediation → priority trade rights with both colonies. Twist: The conflict is secretly instigated by a third colony — they want to annex both colonies.

**28. Derelict Race (Competition)**
> An unofficial "tradition" of the Ash Belt — Captains cobble together race ships from derelict parts and run a dangerous obstacle race through the wreckage field. The stakes are high, the crowd is wild. The Convoy can enter the race or place bets. Reward: First-place prize of 15,000 Credits (Cr) + a year's worth of bragging rights. Twist: Last year's champion died in an "accident" — his race ship was tampered with. Who does not want the Convoy to win?

### Starfall Sector (星墜扇區) (cont.)

**29. Alien Greenhouse (Exploration)**
> Beneath the surface of a dead planet in the Starfall Sector, an alien "greenhouse" was discovered — a vast underground ecosystem full of plants that do not belong to this galaxy. The Relic Watchers (遺物守望者) forbid anyone from entering, but it is said to contain plants that can cure any disease. Reward: The legendary "Star-Sea Flower" — can cure any disease or extend life. Twist: The greenhouse is alive — it observes those who enter and reacts based on their intentions.

**30. The Watcher's Secret (Investigation/Infiltration)**
> A person claiming to be a "former Watcher" contacts the Convoy, asserting that the higher-ups of the Relic Watchers have concealed a major secret — they discovered something "still operational" inside an alien ruin, and decided to seal off the entire area. He wants to expose the truth. Reward: The truth about the alien technology. Twist: The Watchers had a reason for sealing the ruin — that "still operational something" is extremely dangerous. Exposing it may release it.

**31. Alien Language (Investigation)**
> The same writing system has been found in multiple ruins across the Starfall Sector, but no one can decipher it. Academic institutions have put out a bounty for a "Rosetta Stone" — an alien artifact containing a bilingual counterpart. Reward: If found, you may name the writing system and receive permanent research funding. Twist: The stele does exist — but it lies deep inside an alien facility that is still operational. Something guards it.

**32. Starfall Pilgrimage (Escort)**
> Every year, pilgrims of the Star Cathedral (星空聖殿) travel to a "glowing ruin" in the Starfall Sector on pilgrimage — but this year's route has been blocked by the Rift Valley Pirates (裂谷海盜). The Convoy is asked to provide escort. Reward: A high blessing from the Cathedral + hidden talent among the pilgrims. Twist: This year the ruin glows brighter than in past years — and it is broadcasting a decipherable signal.

**33. The Rival's Challenge (Competition)**
> A Convoy named "Iron Star (鐵星)" publicly challenges the players' Convoy — to an exploration race in the Starfall Sector: whoever first finds the most valuable alien artifact within a designated area wins. The loser must publicly acknowledge the other's superiority. Reward: Reputation + the discovered artifacts. Twist: The Captain of "Iron Star" actually wants to use this opportunity to observe the players' capabilities — he is evaluating potential allies for a certain faction.

**34. The Fallen Watcher (Elimination/Negotiation)**
> A squad of Relic Watchers has mutinied — they have begun selling alien artifacts stolen from the ruins. The orthodox Watchers ask the Convoy to hunt them down (preferably alive). Reward: Great respect from the Watchers + rare technology. Twist: The mutineers claim they discovered the Watcher higher-ups have long been doing the same thing in secret — they simply no longer wish to be excluded from the profits.

### Still Sea Sector (靜海扇區) (cont.)

**35. Deep-Space Signal Source (Exploration)**
> The Wanderers' Alliance (漂泊者同盟) detected an extremely faint, regular signal deep in the Still Sea — it comes from no known human or alien source. The frequency is gradually increasing, as if counting down. The Convoy is asked to investigate. Reward: Unknown — but it may be the most important discovery of this campaign. Twist: The signal source is a wartime hyperspace communication device still in operation — it is receiving a message from the other end of the galaxy. Human civilization did not perish.

**36. Ghost Fleet (Exploration/Rescue)**
> A complete fleet was found on the edge of the Still Sea Sector — 12 ships, neatly arranged, motionless. No signs of life, no damage. All ships have their engines shut down. Board one: the Crew are missing. Every ship is the same. What happened? Reward: 12 usable ships (if the Convoy can find a way to bring them back). Twist: The Crew are not missing — they collectively decided to enter cryo-sleep, waiting for a certain "signal." The date is set for 3 months later.

**37. Time Island (Rescue/Investigation)**
> The Convoy encounters a time-dilation bubble in the Still Sea Sector — inside it is a ship, frozen in time. From its hull markings, it is an expedition ship that departed 50 years ago. The Crew may still be alive — from their perspective only a few hours have passed. Reward: Star charts and intel from 50 years ago (possibly containing forgotten resource points). Twist: Rescuing them means they must face a fact: everyone they loved has grown old or died.

**38. Lighthouse in the Void (Construction)**
> The Wanderers' Alliance plans to build a new beacon relay station on the edge of the Still Sea Sector — this would greatly expand the range of safe navigation. But it requires the Convoy to escort construction materials and personnel, and provide protection during construction. Reward: Naming rights to the beacon + permanent free use. Twist: Frequent hyperspace anomalies are detected near the construction site — something may not want that beacon to exist.

**39. The Great Beast Migration (Avoidance/Investigation)**
> Multiple observation stations report: the space creatures of the Still Sea Sector are migrating en masse — not normal seasonal movement, but as if fleeing from something. If the Convoy tracks the reverse direction of the migration route, they may discover the cause. Reward: Discover the source that drove the great beasts to flee (possibly a threat, possibly an opportunity). Twist: The source is a gigantic alien starship — it is sleeping.

**40. The Last Colony (Rescue)**
> Deep in the Still Sea is a human colony — never contacted since the Inheritance War (繼承戰爭). They survived in complete isolation for 110 years. The Wanderers' Alliance received an extremely faint signal — the colony's last reactor is about to fail, and they need evacuation. But the voyage there is extremely dangerous. Reward: Save hundreds of lives + a human culture isolated for 110 years. Twist: The colony's residents do not want to leave — they only want a new reactor. They have grown accustomed to solitude.

### Cross-Sector / Special Missions

**41. Sector Disease (Transport/Investigation)**
> A mysterious disease is spreading in the lower levels of the Abyss Gate — symptoms include hallucinations and abnormal body temperature. The medical lab needs a compound found only in alien plants of the Starfall Sector to make a treatment drug. The Convoy must obtain it within a time limit. Reward: Permanent free medical care at the Abyss Gate + if successful, the treatment will be named after the Convoy. Twist: The disease is man-made — someone is testing a biological weapon. Obtaining the plant is only the first step.

**42. Pirate Throne (Elimination/Negotiation)**
> Multiple factions of the Rift Valley Pirates are in a civil war — fighting for control of the "Pirate Throne." This is an opportunity — the Convoy can support one side (in exchange for an alliance with the pirates), or attempt to eliminate all factions (in exchange for great respect from all legitimate factions). Reward: Depends on the chosen route. Twist: The Skyhook Group is manipulating the pirate civil war from behind the scenes — they do not want the pirates too strong, nor do they want the pirates to vanish completely.

**43. Spy Game (Investigation/Infiltration)**
> The intelligence division of the Skyhook Group suspects a "mole" among its higher-ups — leaking fuel transport routes to the Rift Valley Pirates. They hire an outside Convoy to investigate (because internal investigation is untrustworthy). Reward: 5,000 Credits (Cr) retainer + an additional 20,000 Credits (Cr) if the mole is found. Twist: The mole is the granddaughter of the Skyhook Group's founder — she believes the Group's fuel monopoly is choking the Sector's future, so she secretly helps the pirates break the monopoly.

**44. Parallel Convoy (Competition/Cooperation)**
> Another Convoy, "Horizon (地平線)," competes with the players' Convoy across the entire Sector — they take the same missions at the same time, explore the same areas, and try to obtain the same resources. But their Captain makes a proposal: rather than expend each other, merge into a larger Convoy. Reward: Resource sharing + doubled Convoy size. Twist: After merging, the Captain of "Horizon" privately reveals to the players — there is a traitor in their Convoy, feeding information to a certain faction.

**45. Star-Sea Music Festival (Social)**
> The Wanderers' Alliance organizes the inaugural "Star-Sea Music Festival" at the Crossroads Outpost (十字路口前哨站) — three days and nights of music, trade, and Captain gatherings. All Convoys are invited. This is a purely social and role-play scene. Reward: New connections, possible Crew recruitment, black-market trading opportunities. Twist: On the second night of the festival, a famous Captain's ship is stolen — right while everyone is reveling.

**46. Across Generations (Escort)**
> A group of young people — the second generation of a colony — want to leave their colony to see the Star-Sea. Their parents object. They secretly hire the Convoy to take them away. Reward: Meager (they scraped together 800 Cr), but several of them have special talents (untrained potential Crew). Twist: Their parents show up in pursuit — not to forcibly bring them back, but to decide to go with them. The whole group wants to join the Convoy.

**47. Assassination Contract (Moral Dilemma)**
> An anonymous employer offers a contract over an encrypted channel: eliminate a specific Crew member on a specific ship. The reward is extremely high (30,000 Cr), but there is no explanation. The target is an apparently ordinary middle-aged engineer. Reward: 30,000 Credits (Cr). Twist: That engineer is the sole person who knows about a wartime superweapon project — someone wants to make sure he stays silent forever. Or the opposite — someone wants to eliminate him before he tells the truth.

**48. Lost-Tech Auction (Competition/Negotiation)**
> A Sector-level black-market auction is held at an abandoned Space Station in the Ash Belt. The lots include: a complete alien small craft, a Pioneer communication device, and a vial of water said to come from "Earth." The Convoy can participate in the bidding. Reward: Depends on the bidding outcome. Twist: The auction is a trap set by law-enforcement factions — they plan to arrest everyone after it ends.

**49. Convoy Marathon (Competition)**
> The first "Glass Sea Sector (玻璃海星域) Convoy Marathon" — departing from the Abyss Gate, passing checkpoints in four sectors, the first Convoy to reach the finish wins. It tests navigation skill rather than combat power. Entry fee 1,000 Credits (Cr). Reward: Winner's prize of 50,000 Credits (Cr) + Sector-wide fame. Twist: One of the checkpoints has been occupied by pirates — they intend to charge all participants a "special passage fee."

**50. Countdown (Game Master (GM)-Only — Campaign Climax)**
> The Abyss Gate's last liter of jump fluid is about to run out. The Skyhook Group announces "The Final Departure" — all Convoys still at the Abyss Gate will form a joint fleet that, once departed, never returns, heading into unknown deep space for a final exploration. All ongoing storylines converge on this decision: stay (await the end) or depart (face the unknown). Reward: The final chapter of humanity in the Glass Sea Sector — whatever the ending.

---

## 4.11 Quick Plot Matrix (3D Combination Generator)

Cross-referencing the three tables below can generate hundreds of quest frameworks. After choosing a quest type, layer on a patron and a twist.

### A. Quest Object (d20) — replaces "transport X from A to B"

| d20 | What are you looking for / transporting? |
|:---:|------|
| 1 | A complete derelict ship |
| 2 | Someone's relative (alive or deceased) |
| 3 | An AI core / data module |
| 4 | An alien creature sample |
| 5 | A batch of stolen cargo |
| 6 | A lost star chart |
| 7 | A specific person (the target may not want to be found) |
| 8 | A functional alien device |
| 9 | A batch of medicine / vaccine |
| 10 | A fugitive |
| 11 | A specific item from war ruins |
| 12 | A missing Convoy |
| 13 | Coordinates of a location |
| 14 | An encrypted message |
| 15 | A rare material |
| 16 | A colony's population |
| 17 | A hostage |
| 18 | A scientific sample (planetary geology, atmosphere, etc.) |
| 19 | "Something that needs to be destroyed" |
| 20 | A location from an old photograph |

### B. Obstacle (d12) — the road will not be smooth

| d12 | Obstacle |
|:---:|------|
| 1 | Competitor — another Convoy is also looking for the same thing |
| 2 | Guardian — the target is protected by an Automated War-Ruins Defense System / AI / creature |
| 3 | Deception — the patron did not tell you the whole truth |
| 4 | Time limit — must be completed within X days |
| 5 | Division — the Convoy is internally divided on the mission objective |
| 6 | Cost — completing the mission requires sacrificing something important |
| 7 | Double commitment — you have simultaneously promised two mutually hostile factions |
| 8 | Environment — the destination itself is the greatest danger |
| 9 | Third party — an unexpected faction intervenes |
| 10 | Identity crisis — during the mission you discover a personal connection to it |
| 11 | Choice — you can only save / take part of it, and must choose |
| 12 | Truth — when the mission is complete, the truth found matters more than the mission itself |

### C. Reward Form (d10) — rewards other than Credits (Cr)

| d10 | Non-monetary reward |
|:---:|------|
| 1 | Rare hull modification part (unavailable for purchase) |
| 2 | A special Crew member with extremely high Loyalty |
| 3 | Major faction relationship boost |
| 4 | Safe haven — a secret base available for permanent use |
| 5 | Knowledge — unlock a new technology or star-chart region |
| 6 | Favor — a major help redeemable in the future |
| 7 | Fame — Sector-wide fame increase, affecting all Non-Player Character (NPC) attitudes |
| 8 | Intel — a clue about some major world-setting secret |
| 9 | Legend — the outcome of this mission becomes a legend in the Sector |
| 10 | No reward — but you learned something important about yourself / the Convoy in the process |

---

## 4.12 Abandoned Facility Deep-Exploration Tables

Use when the Convoy decides to explore an abandoned facility in depth (rather than a quick scavenge).

### Inside a Derelict Ship (d20)

| d20 | Discovery |
|:---:|------|
| 1-3 | Empty bridge — the navigation log records the final moments |
| 4-5 | Cargo residue — 2d4 random Resources |
| 6-7 | Engineering bay — 1d6 Parts + possibly usable engine parts |
| 8 | Medical bay — 1d4 Medicine + medical log |
| 9-10 | Crew quarters — personal items. May reveal clues related to a Hidden Agenda |
| 11 | Armory — 2d4 Ammunition + 1 weapon (possibly usable) |
| 12 | Laboratory — research samples (possibly valuable, possibly dangerous) |
| 13 | Bridge vault — 1d4×500 Credits (Cr) + possibly high-end items |
| 14 | Cryo-pod — someone is still in hibernation. Awaken? |
| 15 | Black box — flight recorder, logs a key event |
| 16 | Secret compartment — contraband or private collection |
| 17 | Damaged AI core — partial data can be extracted |
| 18 | Biological contamination — dangerous alien creature aboard (Threat Level (TL) 1-2 encounter) |
| 19 | Trap — left by pirates or scavengers |
| 20 | Intact escape pod — contains emergency supplies and navigation data |

### Inside an Alien Ruin (d20)

| d20 | Discovery |
|:---:|------|
| 1-4 | Empty corridor — murals depict the builders' history |
| 5-7 | Energy core — still operational. Engineering (ENG) Difficulty Class (DC) 18 to extract as 2d6 energy reserves |
| 8-9 | Data terminal — contains alien text. Engineering (ENG) Difficulty Class (DC) 20 to decipher |
| 10-11 | Biology lab — dormant alien plants inside (convertible into medicine) |
| 12-13 | Star-chart room — contains celestial data not of this Sector |
| 14 | Armory — alien weapons (unusable but of great research value) |
| 15 | Hibernation pod — alien creature in dormant state. Awaken? |
| 16 | Teleport gate — leads to another area of the ruin — or another place |
| 17 | Gravity anomaly — gravity directions are chaotic, hard to move |
| 18 | Defense system — automated defense still powered (Threat Level (TL) 2-3) |
| 19 | Builder remains — fossil or well-preserved corpse of an alien creature |
| 20 | A still-operational core facility — the ruin's fundamental function still executes, and can be interacted with |

### Abandoned Colony (d20)

| d20 | Discovery |
|:---:|------|
| 1-4 | Abandoned residential area — daily items, diaries, photos. Emotional clues |
| 5-7 | Warehouse — 3d6 Parts, 2d6 Fuel |
| 8-9 | Medical center — 1d6 Medicine, medical equipment (sellable) |
| 10 | Communication tower — can be repaired to obtain the colony's last communications record |
| 11 | Power plant — reactor still has residual warmth. Engineering (ENG) Difficulty Class (DC) 16 to restart part of the facility |
| 12 | School — children's homework and drawings. May contain clues about the colony's history |
| 13 | Shelter — where the colonists last gathered. May contain a leftover message |
| 14 | Laboratory — colony research facility. May still have usable data |
| 15 | Underground area — storage zone never scavenged |
| 16 | Colony AI — still-operational management AI, possibly friendly or possibly malfunctioning |
| 17 | Graveyard — the colonists' final resting place. May contain special items |
| 18 | Contaminated zone — traces of some disaster (radiation/biological/chemical) |
| 19 | Illegal facility — secret base beneath the colony. Pirates? Smuggling? Military experiment? |
| 20 | Complete water system — can replenish large amounts of fresh water (reduces Food consumption by 50% for one month) |

---

## 4.13 Port NPC Deep-Interaction Tables

Use when the Convoy stays at a port for more than a day and interacts deeply with a specific Non-Player Character (NPC).

### What an NPC Can Provide (d12)

| d12 | NPC provides |
|:---:|------|
| 1 | **A quest** — quickly create using the side-quest generator |
| 2 | **Intel** — true intelligence about a certain star system / faction / person |
| 3 | **A rumor** — 50% true-false mix — may lead to hidden content |
| 4 | **A trade** — some Resource below market price (d4 units) |
| 5 | **A favor** — accepts a small help, can request a big help in the future |
| 6 | **A warning** — about danger ahead for the Convoy (may save lives or may mislead) |
| 7 | **A secret** — private information about a certain Crew member or NPC Captain |
| 8 | **An invitation** — something is happening somewhere in the port (party / meeting / auction) |
| 9 | **A challenge** — to the Captain or Convoy (competition / gambling / confrontation) |
| 10 | **A gift** — unconditional offering (may be a trap, or may just be goodwill) |
| 11 | **A story** — first-hand experience from somewhere in the Sector (convertible into star-chart intel) |
| 12 | **A choice** — the NPC presents two options, each with different consequences |

### An NPC's Hidden Motive (d8)

| d8 | What the NPC truly wants is… |
|:--:|------|
| 1 | To leave this port — wants to join the Convoy as Crew |
| 2 | Revenge — the target is at one of the Convoy's destinations |
| 3 | To find a specific person — possibly in the Convoy, possibly where the Convoy is going |
| 4 | To sell a hot item — the faster the better, no questions asked |
| 5 | To deliver a message — but dares not use normal communication channels |
| 6 | To gather intel on the Convoy — working for a certain faction |
| 7 | To repay an old debt — owed to someone in the Convoy (or to a Convoy enemy) |
| 8 | Pure goodwill — rare but existing sincere person |

---

## 4.14 Random Crew Event Table (d20)

When the Convoy is traveling, in port, or exploring, the Game Master (GM) may roll this table to trigger a small Crew-related event:

| d20 | Event |
|:---:|------|
| 1 | Two Crew members argue on a private channel — accidentally overheard by the Captain |
| 2 | A Crew member does something amazing in their spare time — paints a mural, composes a tune |
| 3 | The Navigator discovers an "error" on the star chart — a shortcut no one noticed |
| 4 | The Engineer accidentally finds a hidden hull compartment while repairing |
| 5 | The Medical Officer requests extra budget to buy a rare drug — refusal may affect Loyalty |
| 6 | The Comms Officer intercepts an encrypted message — its source is another ship in the Convoy |
| 7 | The First Mate privately expresses concern about a certain decision to the Captain |
| 8 | A Crew member's birthday — others secretly prepare a surprise |
| 9 | Crew discover a new way to pass the time — the whole ship becomes obsessed (may be good or bad) |
| 10 | Someone keeps an alien pet aboard — others don't know yet |
| 11 | Crew find something off in the supply inventory — something is slowly disappearing |
| 12 | The Navigator dreams of an unknown star system — the details are disturbingly specific |
| 13 | The Engineer claims to receive a signal only she can hear |
| 14 | Informal cliques form among Crew — supporting or excluding each other |
| 15 | The Medical Officer finds a slight radiation leak aboard — source unknown |
| 16 | A Crew member requests special leave — to a certain port to handle personal matters |
| 17 | The First Mate organizes Crew training — can raise a collective skill |
| 18 | The Comms Officer hears the Convoy's name while monitoring pirate channels |
| 19 | Multiple Crew members have similar dreams at once — the content is unsettling |
| 20 | Crew discover an invention eligible for a patent — must decide how to handle it |

---

## 4.15 Convoy Internal Event Table (d12)

Use when Convoy relations are tense or the Game Master (GM) wants to push internal plot:

| d12 | Event |
|:---:|------|
| 1 | Two ships argue fiercely over route choice — a vote is required |
| 2 | One ship's Crew publicly criticizes another ship's Captain — tense relations |
| 3 | A discovered Resource is clearly more useful to one ship — but others want it too |
| 4 | Someone says offhand, "If I were Convoy leader…" |
| 5 | One ship unintentionally monopolizes the comms channel — others feel excluded |
| 6 | A certain Captain privately proposes an alliance with you — mutual support in votes |
| 7 | A rumor spreads in the Convoy that someone is hiding important information |
| 8 | A successful cooperation noticeably warms relations between two ships |
| 9 | Someone in port tries to sow discord among Convoy members |
| 10 | Someone proposes modifying Convoy rules — a vote is required |
| 11 | In a crisis, someone does not act according to the vote result |
| 12 | The Convoy receives an external message — aimed directly at a specific Captain |

# Chapter 5: Ports, Trade, and Convoy Management

## 5.1 Port Services and Trade

### Class A Port (e.g., Abyss Gate)

| Service | Fee | Description |
|------|:---:|------|
| Berthing (/day) | 50 Credits (Cr) | Includes basic security check and docking services |
| Hull repair (/HP) | 50 Credits (Cr) | Includes Parts cost, repairs 10 Hull Points (HP) per day |
| System damage repair (/item) | 500 Credits (Cr) | Includes diagnosis and repair |
| Fuel refill (/unit) | 200 Credits (Cr) | Quota system: 20 units max per month |
| Hull upgrade | See upgrade table | Requires reservation, queue 1d4 days |
| Intelligence exchange | 100-500 Credits (Cr) | By intel tier |
| Used ship trade | 8,000-30,000 Credits (Cr) | Basic used hull, no weapons |

### Class B Port

| Service | Fee | Description |
|------|:---:|------|
| Berthing (/day) | 20 Credits (Cr) | — |
| Hull repair (/HP) | 30 Credits (Cr) | Limited Parts, repairs 5 Hull Points (HP) per day |
| System damage repair | 800 Credits (Cr) | May need to wait for Parts (1d3 days) |
| Fuel refill (/unit) | 250 Credits (Cr) | Max 10 units |
| Barter market | — | No fixed price, decided by Diplomacy (DIP) check |

### Class C Port

| Service | Fee | Description |
|------|:---:|------|
| Berthing (/day) | 5 Credits (Cr) | May only have a docking arm |
| Emergency repair (/HP) | 50 Credits (Cr) | Max 3 Hull Points (HP) per day |
| Fuel refill | 300 Credits (Cr) | Max 5 units, may not have stock (50%) |

### Trade Goods and Arbitrage

| d8 | Goods | Buy price | Sell price |
|:--:|------|:---:|:---:|
| 1 | Rare ore | 1d6×100 | 2d6×150 |
| 2 | Alien artifact | 1d4×500 | 2d4×1,000 |
| 3 | Military parts | 1d6×300 | 1d6×600 |
| 4 | Jump fluid | 200 | 400-600 |
| 5 | Medical supplies | 600 | 1,000-1,500 |
| 6 | Smuggled luxury goods | 500 | 1,000 |
| 7 | Biomass | harvested | 300/unit |
| 8 | Colonial equipment | 2,000 | 4,000-6,000 |

> Each port call rolls d6 for market state: 1-2 = buyer's market (sell -30%) / 3-4 = normal / 5-6 = seller's market (sell +30%)

---

## 5.2 Convoy Shared-Resource Rules

When the Convoy is formed, a vote decides the resource management mode (can be changed at any time):

**Mode 1: Each Ship Self-Sufficient (default)** — each ship keeps its own Resources, votes decide whether to force sharing.
**Mode 2: Convoy Common Treasury** — Resources are pooled in the largest Cargo Hold ship; use requires a Simple Majority vote. Each ship may keep a Cargo Hold (CRG)×2 Standard Cargo Unit (SCU) private stash.
**Mode 3: Quota System** — allocated by pre-set ratio, no vote needed to use one's own quota. Emergency situations can trigger a special withdrawal vote.

### Resource Lending

Private lending between Captains: the debtor's relationship -1 until repaid. If relationship is already negative and still not repaid → triggers a Convoy internal event.

---

## 5.3 Personal Combat and Boarding Actions

When a Captain / Crew personally uses force, resolve quickly with opposed checks — do not enter turn-based combat.

| Action | Attribute |
|------|:---:|
| Shooting / melee | Command (CMD) |
| Cover / movement | Intuition (INT) |
| Medical first aid | Engineering (ENG) |
| Intimidate / Persuade | Diplomacy (DIP) |

### Personal Weapons

| Weapon | Damage | Trait |
|------|:---:|------|
| Plasma pistol | 2d4 | Standard |
| Shotgun | 3d4 | Close-range advantage |
| Gauss rifle | 2d6 | Long range, Penetration 1 |
| Concussion grenade | 3d6 | Area, one-time |
| Stun baton | 1d6 | Non-lethal |

### Personal Damage (condition-based, does not track Hull Points (HP))

| Failures | Condition |
|:-------:|------|
| 1 | Light wound: -1 to subsequent actions |
| 2 | Heavy wound: -3 to subsequent actions, requires Medicine |
| 3 | Incapacitated — captured / fallen |

Captain knocked down → First Mate takes command until recovery.

### Boarding Actions

1. Boarding side makes a Command (CMD) check (Difficulty Class (DC) = 10 + defending side's First Mate Command (CMD)/2)
2. Success → 3 rounds of personal opposed checks
3. Result: occupy / repel
4. Casualties: losing side takes 1 Crew light wound per round

---

## 5.4 Bounty Hunters and Debt

### Bounty Tracking

Each time docking at a Class A/B port: d20 ≤ Reputation → a bounty hunter appears. Level d4 (1-2 = TL1 / 3 = TL2 / 4 = TL3).

Clearing a bounty: pay in full / complete an atonement mission / employer dies.

### Debt Collection

Bankrupt merchant monthly interest 2% (400 Credits (Cr)/month), first three months interest-free. Overdue 3 months → debt collector (TL2). Overdue 6 months → Mining Guild seizes the ship.

---

## 5.5 Convoy Split and Merger

**Voluntary exit:** Immediate at port / separates at next port while traveling. Common treasury distribution requires a final vote.

**Forced expulsion:** Unanimous (excluding the expelled). Relationship -2. If expelled in deep space, must be given enough Fuel and Food to reach the nearest port.

**Merger:** Both sides Two-Thirds Majority. Re-vote relationships and objectives. Personal supplies retained, common treasuries merged.

---

## 5.6 Multi-Ship Exploration Rules

| Mode | Time cost | Risk |
|------|:---:|:---:|
| Group action | Normal | Low |
| Divided exploration | Total time halved | Medium (single-ship risk) |
| Orbital standby | Normal | Standby ship's Sensors assist surface |

When dividing: the Game Master (GM) announces exploitable locations → Convoy votes on allocation → each ship explores independently → may call for help if in distress (1d4 hours of support)

---

## Quick Reference Master Table (for the Game Master (GM))

```
[Attack]   d20 + WPN + Acc vs AC(10 + ENG-S + distance + status)
[Damage]   weapon die + MoS - ARM×2 + penetration (min 1)
[Critical] Natural 20 = full damage + ignore armor
[MoS]      0-2 normal | 3-6 +2 | 7-10 +4 + systems check | 11+ +6 + systems damaged
[Synergy]  each additional ship → attack +1, damage +2
[Energy]   cap = ENG-S×5+10 | recovery = ENG-S/turn
[HP]       = ARM×10+20 | [AC] = 10+ENG-S | [DR] = ARM×2
[Repair DC] light 12 | medium 15 | heavy 18
[Standard DC] 15 | [Advantage] 2d20 higher (+3.3) | [Disadvantage] 2d20 lower (-3.3)
```

## Voting Process Quick Reference

| Decision type | Threshold | Can Persuade NPC |
|---------|:---:|:----------:|
| Route / Resources | >50% | Yes (Diplomacy (DIP) vs DC) |
| Charter / Major commission | ≥67% | Yes |
| New member / High-risk action | 100% | Yes |
| Combat pursuit / disengage | >50% | No (instant vote) |
| Combat surrender | ≥67% | No |
| Abandon-ship rescue | >50% | No |

**Persuade Difficulty Class (DC) = 10 + NPC Intuition (INT) + stance modifier (opposed +8 / leaning opposed +4 / neutral +0 / leaning in favor -4 / strongly in favor -8)**

## Resource Consumption Quick Reference

| Activity | Consumption |
|------|------|
| In-system travel 1 day | 1 Fuel |
| Adjacent system jump | 5 Fuel |
| Medium-distance jump | 10 Fuel |
| Cross-Sector jump | 20 Fuel |
| 1 Crew member 1 day | 0.1 Food |
| Repair 5 Hull Points (HP) | 1 Parts |
| 1 standard battle | 1 Ammunition |
| Treat 1 heavy wound | 0.2 Medicine |

---

> **Remember: you are not writing a novel — you are building a stage.** Players will make choices you never anticipated. Let them. Let them fail. Let them lose a vote and then be forced down the route they thought was dangerous. That is where the Convoy's story truly begins.

