# Starship Convoy TRPG — Player Manual

> **Code:** `fleet-trpg` | **Version:** v1.0
> **You need:** one d20, this manual, a character sheet, and your crew.

---

# Chapter 1: Core Rules

## 1.1 Basic Checks

All actions with uncertain outcomes: roll **d20 + Attribute**, compared with the **Difficulty Class (DC)** set by the Game Master (GM).

```
d20 + Attribute ≥ DC → Success
```

- **Natural 20** (die face = 20): **Critical Breakthrough** — automatic success + extra benefit (GM adjudicates)
- **Natural 1** (die face = 1): **Catastrophic Failure** — automatic failure + extra consequence

### Advantage / Disadvantage

| Mechanic | Rule | Feel |
|------|------|------|
| **Advantage** | Roll 2d20, take higher | You came prepared, fully in command |
| **Disadvantage** | Roll 2d20, take lower | You acted in haste, caught in danger |

---

## 1.2 The Five Captain Attributes

**Core rule: Attribute value = your modifier.** Attribute 7 means d20 + 7.

| Attribute | Code | You use it to... |
|------|------|-------------|
| **Command** | Command (CMD) | Lead crew, direct combat, persuade others in voting |
| **Engineering** | Engineering (ENG) | Repair hull, crack systems, improvise modifications |
| **Navigation** | Navigation (NAV) | Plan routes, traverse hazards, calculate jumps |
| **Diplomacy** | Diplomacy (DIP) | Bargain, negotiate diplomacy, poach crew |
| **Intuition** | Intuition (INT) | Sense danger, read people, act first |

**Attribute level meanings:**

| Value | You are... | vs DC 15 |
|:--:|------|:------:|
| 1-2 | Amateur | 30-35% |
| 3-4 | Novice | 40-45% |
| **5** | **Qualified Expert** | **55%** |
| 6 | Proficient | 60% |
| **7** | **Exceptional (starting cap)** | **65%** |
| 8 | Elite | 70% |
| 9 | Master | 75% |
| 10 | Legendary | 80% |

---

## 1.3 Difficulty Ladder

| Difficulty | DC | Situation |
|------|:--:|---------|
| Trivial | 8 | Everyday trivial matters |
| Simple | 10 | Basic training suffices |
| Ordinary | 12 | Requires some expertise |
| **Standard** | **15** | **A real challenge** |
| Advanced | 17 | Only experts are confident |
| Hard | 20 | Luck also matters |
| Extreme | 22 | Legendary challenge |

---

## 1.4 Check Types

### Standard Check
> d20 + relevant Attribute ≥ DC → Success

**Example:** Persuading a space station official to release cargo → d20 + Diplomacy (DIP) vs DC 15

### Contest Check
> Both sides roll d20 + relevant Attribute; higher wins

**Example:** Trying to poach the engineer from the next ship → d20 + Diplomacy (DIP) vs their d20 + Command (CMD)

### Team Check
> Everyone rolls individually. If more than half succeed → team success

---

## 1.5 Margin of Success (MoS)

When your check succeeds, the more you exceed the DC, the better the effect:

| MoS | Effect |
|:---:|------|
| 0-2 | Bare success — you manage it, but with a small cost |
| 3-6 | Solid success — clean and efficient |
| 7-10 | Exceptional success — beyond expectations; GM grants extra benefit |
| 11+ | Legendary success — exemplary |

> MoS = (d20 + modifier) - DC

---

# Chapter 2: Character Creation

## 2.1 Seven-Step Creation Process

| Step | What to do |
|:---:|------|
| **1** | **Pick a Background** — choose one of eight backgrounds |
| **2** | **Allocate Attributes** — distribute 25 points across five attributes |
| **3** | **Record Boons** — advantages, gear, and connections from background |
| **4** | **Choose a Ship Class** — pick one of five starting ship classes |
| **5** | **Recruit Crew** — 3 starting crew members |
| **6** | **Buy Equipment** — purchase with starting funds |
| **7** | **Fill in the Dossier** — what is your ship called? What is the convoy's goal? |

---

## 2.2 Attribute Allocation

- **Total points:** 25 points
- **Per-attribute minimum:** 1 (cannot be 0)
- **Creation cap:** 7
- **Attribute value = points spent** (1 point buys 1 point)

**Recommended arrays:**

| Style | Command (CMD) | Engineering (ENG) | Navigation (NAV) | Diplomacy (DIP) | Intuition (INT) |
|------|:---:|:---:|:---:|:---:|:---:|
| Balanced | 7 | 6 | 5 | 4 | 3 |
| Commander | 7 | 4 | 5 | 6 | 3 |
| Tech Maniac | 5 | 7 | 6 | 4 | 3 |
| Explorer | 4 | 5 | 7 | 4 | 5 |

---

## 2.3 The Eight Captain Backgrounds

### Bankrupt Merchant
- **Specialty Advantage:** Advantage on Diplomacy (DIP) checks (bargaining, cargo appraisal)
- **Starting Resources:** 5,000 credits (Cr) + Trade Analysis Terminal
- **Debt:** 20,000 credits (Cr) (owed to the Mining Guild, 2% monthly interest, first three months interest-free)
- **Faction Relations:** Mining Guild -2 / Merchant Alliance +1

### Defected Officer
- **Specialty Advantage:** Advantage on Command (CMD) checks (tactics, military knowledge)
- **Starting Resources:** 3,000 credits (Cr) + Plasma Pistol + Encrypted Data Chip
- **Bounty on Head:** 15,000 credits (Cr) (Imperial Navy bounty)
- **Faction Relations:** Imperial Navy -3 / Free Resistance +2

### Academic Exile
- **Specialty Advantage:** Advantage on Engineering (ENG) checks (tech analysis, ruin interpretation)
- **Starting Resources:** 3,000 credits (Cr) + Alien Relic Analyzer + Pioneer Star Chart Fragment
- **Faction Relations:** Sector University -1 / Independent Scholars Network +1

### Interstellar Smuggler
- **Specialty Advantage:** Advantage on Intuition (INT) checks (stealth, concealment, black market)
- **Starting Resources:** 3,000 credits (Cr) + Hidden Cargo Hold (+1 Cargo Hold (CRG), illegal cargo only) + Forged Registry ID
- **Faction Relations:** Smugglers' Guild +1 / Sector Customs -1

### Colonist Survivor
- **Specialty Advantage:** Advantage on Intuition (INT) checks (survival, crisis response)
- **Starting Resources:** 3,000 credits (Cr) + Colony Log + Radiation Suit
- **Faction Relations:** Colonist Mutual Aid Society +2 / Insurance Company -1

### Mercenary Captain
- **Specialty Advantage:** Advantage on Command (CMD) checks (combat command, firepower assessment)
- **Starting Resources:** 3,000 credits (Cr) + Combat-modified Ship (WPN+1, Cargo Hold (CRG)-1) + 3 Veterans
- **Faction Relations:** Mercenary Guild +1 / Former Employer -1

### Religious Pilgrim
- **Specialty Advantage:** Advantage on Diplomacy (DIP) checks (persuasion, morale boosting)
- **Starting Resources:** 3,000 credits (Cr) + Scripture Fragment + Temple Badge (free monthly supplies)
- **Faction Relations:** Temple of the Stars +2 / Heretic Inquisition -1

### Explorer
- **Specialty Advantage:** Advantage on Navigation (NAV) checks (jump navigation, star chart mapping)
- **Starting Resources:** 3,000 credits (Cr) + Pioneer Jump Data + Advanced Star Chart Mapper
- **Faction Relations:** Explorers' Guild +2 / A certain mining company -1

---

## 2.4 The Five Starting Ship Classes

### Allocation Methods

You have two ways to determine your ship's attributes:

**Method One: Choose a Preset Ship Class (recommended for beginners)**
Directly use the preset ship classes below, with values already optimized. Each ship class comes with special abilities and module slots.

**Method Two: Free Allocation (recommended for veterans)**
Gain **10 free allocation points** + the chosen ship class's bonus (see each ship class detail). Per-attribute cap of 4 at creation. You still use that ship class's module slots and special abilities.

### Ship Class Overview

| Ship Class | Engine (ENG-S) | Armor (ARM) | Firepower (WPN) | Sensors (SEN) | Cargo Hold (CRG) | Hull Points (HP) | Energy | Role |
|------|:-----:|:---:|:---:|:---:|:---:|:--:|:----:|------|
| Starseeker-class (星巡者級) | 4 | 1 | 2 | 4 | 2 | 30 | 30 | Exploration/Recon |
| Trader-class (商旅級) | 2 | 2 | 1 | 2 | 5 | 40 | 20 | Cargo/Supply |
| Swordfish-class (劍魚級) | 3 | 4 | 4 | 3 | 1 | 60 | 25 | Combat/Escort |
| Nomad-class (遊牧民級) | 3 | 3 | 3 | 3 | 3 | 50 | 25 | Multi-purpose |
| Ghost-class (幽靈級) | 4 | 1 | 2 | 5 | 1 | 30 | 30 | Stealth/Recon |

> 💡 The table above shows preset allocation. If using free allocation, Hull Points (HP) / Energy / Cargo Hold change with your allocation.
> 
> Formulas: Hull Points (HP) = Armor (ARM) × 10 + 20 | Energy = Engine (ENG-S) × 5 + 10 | Cargo Hold = Cargo Hold (CRG) × 20 Standard Cargo Units (SCU) | Armor Class (AC) = 10 + Engine (ENG-S) | Damage Reduction (DR) = Armor (ARM) × 2

### Starseeker-class (Exploration/Recon Vessel)
- **Special Ability "Deep Scan":** Spend 4 Energy, reveal stealth targets, ally attacks +2
- **Exclusive Equipment:** Long-range Scanner (range ×3), Jump Probe ×3, Advanced Navigation Computer (jump Advantage)

### Trader-class (Cargo/Supply Vessel)
- **Special Ability "Cargo Mod":** Reaction — a mid-range allied ship counts as extreme-long-range this turn
- **Exclusive Equipment:** Oversized Cargo Hold (×1.5 capacity), Fuel Tank (×2 fuel), Trade Depot Module (Diplomacy (DIP) Advantage)

### Swordfish-class (Combat/Escort Vessel)
- **Special Ability "Combat Stance":** Reaction 5 Energy — grants self or mid-range ally Armor (ARM) × 3 temporary shield
- **Exclusive Equipment:** Multi-weapon Slot ×3, Shield Amplifier, Point Defense System, Combat Bridge (Command (CMD) +2)

### Nomad-class (Multi-purpose Vessel)
- **Special Ability "Modular Interface":** Can install exclusive equipment from any ship class (cost ×1.5)

### Ghost-class (Stealth/Recon Vessel)
- **Special Ability "Cloak Screen":** Activate at 6 Energy — this ship cannot be directly attacked, up to 2 turns

---

## 2.4b Ship Energy System

Your ship has an energy bar that powers all tactical abilities.

### Energy Basics

```
Energy Cap = ENG-S × 5 + 10
Energy Regen = ENG-S points / per turn (auto-recovers in combat)
```

| Engine Level | 1 | 2 | 3 | 4 | 5 |
|:------:|:--:|:--:|:--:|:--:|:--:|
| Energy Cap | 15 | 20 | 25 | 30 | 35 |
| Regen per Turn | 1 | 2 | 3 | 4 | 5 |

### Energy Uses (in combat)

| Use | Cost | Timing | Effect |
|------|:---:|------|------|
| Shield Charge | 5 | Main Action | Gain Armor (ARM) × 3 temporary shield |
| Weapon Overload | 3 | Before Attack | +1 damage die |
| Engine Overload | 4 | When Moving | Move 2 distance bands / Armor Class (AC) +4 |
| Emergency Turn | 3 | Reaction | Single attack Armor Class (AC) +3 |
| Sensor Overload | 4 | Main | Reveal stealth + attack +2 |
| Emergency Repair | 5 | Main | Restore 2d6 + Engineering (ENG) Hull Points (HP) |
| Seize Position | 3 | Stance Phase | Engine +2 (initiative + AC) |

> **Energy Depletion (0)** → unable to use any consuming abilities → shields drop to zero → auto-recover 1 point per turn → restore to 5+ to return to normal.

### Energy Outside Combat

In non-combat scenes (voyage, exploration), energy powers jumps, long-duration scans, or activates large equipment. The GM will tell you how much is needed.

---

## 2.5 Your Crew

Recruit **3 starting crew** (First Mate required + choose two other positions). Initial Loyalty = 5 + your Command (CMD), floored at positive.

| Role | Skill Bonus |
|------|---------|
| **First Mate** | Command (CMD) check +2 |
| **Chief Engineer** | Repair +2 Hull Points (HP) |
| **Navigator** | Navigation (NAV) check +2 |
| **Medical Officer** | Crew casualty rate -50% |
| **Communications Officer** | Diplomacy (DIP) check Advantage (roll twice, take higher) |

### Loyalty

| Value | Status |
|:--:|------|
| 1-2 | May betray at any moment |
| 3-4 | Does only their job |
| 5-6 | Normally loyal |
| 7-8 | Will take risks |
| 9-10 | Will sacrifice for you |

**How to raise Loyalty:** Save their lives (+1), complete their personal sidequest (+2), pay bonuses on time (+1), public praise (+1), cover them from the rear in combat (+1/battle).

**How to lose Loyalty:** No bonus for three months (-1), abandon them in danger (-3), decisions cause serious injury (-1), public humiliation (-2).

---

## 2.6b Your Reputation

Your fame in the sector affects NPC attitudes, trade discounts, and mission tiers.

| Reputation | Title | NPC Attitude Modifier | Unlocks |
|:---:|------|:----------:|------|
| 1 | Unknown | 0 | Basic missions |
| 2 | Somewhat Known | +1 | Mid-tier missions, 10% port discount |
| 3 | Widely Known | +2 | High-tier missions, 20% discount, can issue alliance invitations |
| 4 | Sector Legend | +3 | Legendary missions, Class-A port VIP |
| 5 | Living Legend | +4 | NPCs seek you out proactively |

**Reputation Progress:** Complete sidequest +1 / complete convoy chapter +2 / sector-level event +3 / public major failure -1 / betraying ally made public -3. Every 5 points accumulated levels up. GM settles at end of each chapter.

---

## 2.7 Convoy Relations and Goals

### Relations with Other Captains (-3 ~ +3)

At creation, roll d20 for each player captain:

| d20 | Relation | Value |
|:---:|------|:--:|
| 1 | Blood Feud | -3 |
| 2-3 | Old Grudge | -2 |
| 4-5 | Rivalry | -1 |
| 6-8 | Stranger | 0 |
| 9-11 | Mutual Respect | +1 |
| 12-14 | Comrade-in-arms | +2 |
| 15-16 | Debt Relation | +2 |
| 17-18 | Old Friend | +2 |
| 19 | Family | +3 |
| 20 | Bound by Fate | +3 |

### Convoy Goal

| d10 | Why did we form the convoy? |
|:---:|------|
| 1 | Find a new home |
| 2 | Legendary treasure |
| 3 | Escape — evade pursuit |
| 4 | Commercial empire |
| 5 | Hired to explore the unknown |
| 6 | Revenge |
| 7 | Dream of freedom — establish our own order |
| 8 | Scientific expedition |
| 9 | Journey of atonement |
| 10 | Mixed goal (roll twice) |

---

## 2.7 Growth and Feats

### Experience (XP) Sources

| Source | XP |
|------|:--:|
| Complete convoy goal | 500 |
| Personal background sidequest | 300 |
| Resolve major crisis | 200-500 |
| Discover new star system | 50 |
| Complete crew sidequest | 100 |
| Each battle | 50-100 |

### Level Table

| Level | Cumulative XP | Gain |
|:----:|:-------:|------|
| 1 | 0 | Starting |
| 2 | 500 | Attribute +1, new crew |
| 3 | 1,200 | **Feat ×1**, hull upgrade point +1 |
| 4 | 2,500 | Attribute +1, crew cap +1 |
| 5 | 4,000 | **Feat ×2**, hull upgrade point +1 |
| 6 | 6,000 | Attribute +1, reputation event |
| 7 | 8,500 | **Feat ×3**, hull upgrade point +1 |
| 8 | 12,000 | Attribute +1, legendary crew chance |
| 9 | 16,000 | **Feat ×4**, hull upgrade point +1 |
| 10 | 20,000 | Attribute +1, flagship ability |

> 💡 **Attribute Cap:** Any attribute is at most **10**. Attribute points gained from growth cannot push a single attribute above 10. |

### Optional Feats

| Tree | Feat | Threshold | Effect |
|----|------|:---:|------|
| Command (CMD) | Tactical Master | 6+ | Ally attacks may be rerolled (1/battle) |
| Command (CMD) | Iron-fisted Leadership | 7+ | Poaching contest Advantage |
| Command (CMD) | Fleet Coordination | 7+ | Coordinated strike +1 |
| Engineering (ENG) | Emergency Repair | 6+ | Repair with half parts |
| Engineering (ENG) | Reverse Engineering | 7+ | Alien tech analysis Advantage |
| Navigation (NAV) | Shortcut Jump | 6+ | Jump fuel -20% |
| Navigation (NAV) | Star Chart Master | 7+ | Known sectors no navigation needed |
| Diplomacy (DIP) | Silver Tongue | 6+ | Trade price ±20% |
| Diplomacy (DIP) | Connection Network | 7+ | Free intel per port |
| Intuition (INT) | Sixth Sense | 6+ | Danger pre-warning |
| Intuition (INT) | Preemptive Reaction | 7+ | Act first in ambush round |

---

## 2.8 Supply and Money

### Five Resources

| Resource | 1 unit can... | Volume |
|------|----------|:---:|
| Fuel | Sail 1 day or 1 jump | 1 SCU |
| Food | Sustain 1 person for 10 days | 0.1 SCU |
| Parts | Repair 5 points of hull damage | 1 SCU |
| Ammunition | Fight 1 standard battle | 1 SCU |
| Medicine | Treat 5 serious injuries | 0.5 SCU |

### Market Reference

| Resource | Price (Cr) |
|------|:------:|
| Fuel | 200 |
| Food | 100 |
| Parts | 500 |
| Ammunition | 400 |
| Medicine | 600 |

### Hull Upgrade Cost

| Upgrade | Credits (Cr) | Parts | Facility Needed |
|:---:|:---:|:---:|------|
| 1→2 | 500 | 2 | None |
| 2→3 | 1,500 | 5 | Engineering ship or space station |
| 3→4 | 4,000 | 10 | Engineering ship or space station |
| 4→5 | 10,000 | 20 | Engineering ship drydock or large space station |

### In-Port Consumption and Fees

When docked at a port, your ship **does not consume Fuel** (engine off), but still consumes Food (0.1 unit/person/day).

| Fee | Amount |
|------|:---:|
| Berthing fee (Class-A port / day) | 50 credits (Cr) |
| Berthing fee (Class-B port / day) | 20 credits (Cr) |
| Berthing fee (Class-C / day) | 5 credits (Cr) |
| Berthing fee (Class-D / abandoned) | Free |
| Crew monthly salary (per person, from next month) | 200 credits (Cr) |
| Crew bonus (one-time, raises Loyalty +1) | 500 credits (Cr) / person |

> 💡 **About Salary:** Crew are not paid in their first month after joining (treated as prepaid). From the second month, 200 credits (Cr) per person per month. Three consecutive months unpaid → Loyalty -1.

---

## Appendix A: Combat Quick Reference (for Players)

```
Your attack: d20 + WPN + weapon accuracy vs enemy AC (10 + enemy ENG-S + distance)
Your AC: 10 + your ENG-S + distance modifier + status modifier

On hit: Damage = weapon die + MoS - enemy Armor×2 (minimum 1)
Critical (Natural 20): full damage + ignore armor
Malfunction (Natural 1): weapon disabled for 1 turn

MoS ladder (on hit):
  0-2 → normal damage
  3-6 → damage +2
  7-10 → damage +4 + enemy system check
  11+ → damage +6 + enemy system directly damaged

Each turn you may: move 1 + main action 1 + (free action) + reaction 1
Energy regen: recover ENG-S points at end of each turn

Focus Fire: each additional friendly ship attacking same target → your attack +1, damage +2
Retreat: vote passes → collective ENG-S check vs DC (10 + fastest enemy ship's Engine)
```

### Your Ship Takes Damage

| Stage | Hull Points (HP) | Effect |
|------|:--:|------|
| Intact | 76-100% | Normal |
| Lightly Damaged | 51-75% | No penalty |
| Moderately Damaged | 26-50% | Random 1 system damaged |
| Heavily Damaged | 1-25% | Random 2 systems damaged, global -2 |
| Paralyzed | 0% | Lost power, cannot act |

### If Your Ship Is Paralyzed...

**You are not out.** The core premise of the Convoy TRPG is "ships can be defeated, captains don't die." Here are your options:

| Your Situation | You can... |
|---------|---------|
| Convoy still fighting | Use escape pod to transfer to allied ship — you become a "guest captain" of that ship, can assist with Command (CMD) checks to give the allied ship Advantage, but cannot control it |
| Combat ended | Allied ship can tow your ship back to port for repair (requires a ship with Engine (ENG-S) ≥ 2 to perform tow) |
| Ship irreparable | Buy a new ship at port. Used basic hull about 8,000-15,000 credits (Cr) (weapons not included). You may also negotiate with the GM to inherit a ship obtained during missions |
| Don't want new ship | You can switch role to "Convoy Advisor" — stay on other captains' bridges, using your attributes and feats to assist convoy decisions. When a new ship becomes available in the scenario, you have priority |

> **Core Principle:** A captain does not leave play just because their ship exploded. Losing a ship is a story twist, not game over.

---

## Appendix B: Common Check Quick Reference

| What you want to do | Use | DC |
|-----------|:--:|:--:|
| Standard tactical command | Command (CMD) | 12 |
| Maintain formation under fire | Command (CMD) | 15 |
| Reverse a losing battle | Command (CMD) | 18 |
| Repair combat engine | Engineering (ENG) | 15 |
| Crack alien terminal | Engineering (ENG) | 21 |
| Standard system navigation | Navigation (NAV) | 10 |
| Traverse asteroid belt | Navigation (NAV) | 15 |
| Jump to unmapped sector | Navigation (NAV) | 18 |
| Ordinary trade bargaining | Diplomacy (DIP) | 12 |
| Persuade neutral faction | Diplomacy (DIP) | 15 |
| Hostile faction ceasefire negotiation | Diplomacy (DIP) | 21 |
| Sense ambush | Intuition (INT) | 15 |
| See through elaborate scam | Intuition (INT) | 21 |

---

## Appendix C: The Daily Voyage — RP Guidance for Players

### You Are Not Alone

Your ship has 3-5 named, characterized crew with hidden agendas. They are not data — they are your only companions. During the long voyages between jumps, don't just stare at the resource table.

### What You Can Do While Voyaging

| Situation | What you can do |
|------|------------|
| Bridge routine | Discuss next route with navigator, review crew schedule with first mate |
| Engineering bay | Inspect engine with chief engineer, discuss modification plans |
| Crew mess | Eat with crew — listen to them chat, tell stories, complain |
| Captain's quarters | Write voyage log, read received intel, plan next step |
| Comm channel | Talk with other captains in the convoy — discuss plans or just chat |
| Port bar | Gather intel, recruit new crew, have a drink with old friends |
| Crisis moment | Make tough decisions on the bridge — your crew is watching you |

### Three Techniques to Bring Crew to Life

1. **Give them a catchphrase or habit** — the engineer takes a sip of liquor before every repair; the navigator always talks to themselves while looking out the window
2. **Let them react to your decisions** — the first mate may privately express concern; the comms officer may let something slip at port
3. **Remember their birthdays** — the GM may remind you during a voyage "today is the navigator's birthday." What do you do?

### The Convoy Is Not Your Subordinate

Other captains are **equals** — they are not NPCs in your story. Instead of thinking "how do I persuade them to vote my way," think "why would my character believe this decision is right." A lost vote is the best RP material — forced to execute a decision you disagree with, how would you react?

---

> **Remember:** You are not some position on the ship — you ARE the captain. Your engineer may be poached by the next ship, your vote may lose and then you're forced to execute a decision you don't agree with. But that's also why this sector is worth sailing.
