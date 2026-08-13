# The Backrooms Administration Bureau TRPG — Player Rulebook

> **Version:** v1.0
> **Design Positioning:** You sit in the office of the frontline base. The screen shows the live status of the dispatched teams — one signal after another goes dark. You sent them in. They had names, contracts, families. And now you must write this mission report.

---

## Chapter One: Welcome to the Bureau

### 1.1 What Kind of Game Is This?

**The Backrooms Administration Bureau TRPG** is a strategy-management tabletop roleplaying game. You are not a survivor in The Backrooms — you are the **Director**, responsible for making decisions from the safety of your Outpost: who to dispatch into The Backrooms, how much Equipment to give them, and how much risk to take.

This is not a game about personal heroism. It is a game about **responsibility** — every mission order is signed by your own hand, and every casualty report is reviewed by you personally.

### 1.2 What You Need

| Item | Purpose |
|------|------|
| This rulebook | Learn the game rules |
| Player Character Sheet (see Appendix) | Record your Administration Department data |
| Explorer Character Sheet | Record each Explorer's data |
| Two ten-sided dice (percentile dice, d100) | Mission Checks and casualty determination |
| Pen and paper | Record mission results and budget income/expenses |

### 1.3 Core Game Loop

The game operates in units of **each month**:

1. **Month-Start Settlement**: Calculate this month's budget income, and resolve issues left over from last month (wounded recovery, missing-person follow-up, Equipment repair)
2. **Accept Missions**: Select the Missions to run this month from the Mission Pool (the number may not exceed the Mission Cap)
3. **Dispatch Preparation**: For each Mission, select Explorers, allocate Equipment, and set the action Doctrine
4. **Mission Execution**: Roll the mission Check die and resolve results
5. **Follow-up**: Handle the wounded, distribute rewards, and update Intelligence
6. **Story Advancement**: The GM narrates Main Story developments and triggers Special Events

### 1.4 Number of Players

This game is designed to support a **Solo Mode of 1 Player + 1 Game Master (GM)**, while also being compatible with multiple players each managing their own department. Chapter Seven of the rulebook provides a complete guide to Solo Mode.

### 1.5 Time Unit Reference

The time units in this game are easily confused; the following provides unified conversions:

| Unit | Definition | Notes |
|------|------|------|
| **Game Month** | One complete Mission Cycle (see 1.3) | The game's basic time unit |
| **Week** | 1 Month = 4 Weeks | Contract "Weekly Salary" is deducted at the start of each month = Weekly Salary × 4 |
| **Turn** | The unit for Facility Upgrades, Tech Research, and Training | 1 Turn = 1 Game Month |
| **Day** | The time-window unit for Search and Rescue Missions | One Mission is roughly equal to 1 week (7 days) in The Backrooms; Search and Rescue "days" are the in-mission Backrooms time |

> Example: A contract for an "Elite (ELT)" Explorer with a Weekly Salary of 100 deducts 400 from the budget at the start of each month. Upgrading the "Dormitory" facility over "4 Turns" = 4 Game Months.

---

## Chapter Two: Your Bureau — The Four Pillars

### 2.1 Core Attributes

Your "character" is the entire Administration Department, defined by four Core Attributes:

| Attribute (Abbrev.) | Meaning | Low Value | High Value |
|:-----------|------|----------|----------|
| **Manpower (MPW)** | The number of dispatchable Explorers and recruiting capability | Can only run simple Missions; hard to replace personnel after casualties | Can run multiple Missions simultaneously with ample specialist staff |
| **Equipment (EQP)** | Stock quality of weapons, armor, tools, and vehicles | Dispatch teams can only carry Basic Equipment | Can provide advanced exploration gear and experimental technology |
| **Intelligence (INT)** | Knowledge reserve regarding Backrooms Levels and Entities | Inaccurate mission risk assessment, frequently encountering "the unexpected" | Can precisely estimate mission difficulty and learn of target Level changes in advance |
| **Reputation (REP)** | The Bureau's influence and trust within the Backrooms community | No one wants to work for you; poor trade terms | Elite Explorers apply to join on their own; other Factions are willing to cooperate |

### 2.2 Attribute Value Range

- **Initial Creation**: 20 points freely allocated, each attribute minimum 2, maximum 8
- **Growth Cap**: Each attribute can be raised to 12 (under specific conditions it can break through to 15)
- **Suggested Initial Setup**: Manpower 5 / Equipment 5 / Intelligence 5 / Reputation 5 (Balanced)

### 2.3 Derived Attributes

Your Core Attributes produce four Derived values, calculated automatically each month:

| Derived Attribute (Abbrev.) | Formula | Purpose |
|:--------------|----------|------|
| **Monthly Budget (BGT)** | 200 (base facility) + Reputation (REP) × 60 + Intelligence (INT) × 40 | Recruiting, buying Equipment, paying salaries, purchasing Intelligence |
| **Mission Cap (MSC)** | ⌈Manpower (MPW) ÷ 3⌉ (round up) | The maximum number of Missions that can run simultaneously each month |
| **Equipment Depletion Rate (EDR)** | max(0, mission difficulty value − Equipment (EQP)) | The degree of Equipment consumed after a Mission |
| **Intel Accuracy (IAC)** | Intelligence (INT) × 10% | The accuracy of pre-mission risk assessment |

> **Starting Treasury**: Upon taking office, a new Director receives a one-time Starting Treasury of **400**, merged into the budget at the start of the 1st Game Month as a first-month buffer (covering initial team salaries and basic expenses).

**Monthly Budget Example**:

| Reputation (REP) | Intelligence (INT) | Monthly Budget (BGT) |
|:--------:|:--------:|:-----------:|
| 2 | 2 | 400 |
| 5 | 5 | 700 |
| 8 | 8 | 1000 |
| 10 | 10 | 1200 |
| 12 | 15 (cap) | 1520 |

**Mission Cap Reference**:

| Manpower (MPW) | Mission Cap (MSC) |
|:--------:|:-----------:|
| 2–3 | 1 |
| 4–6 | 2 |
| 7–9 | 3 |
| 10–12 | 4 |

---

## Chapter Three: Department Creation — Your Bureau

### 3.1 Creation Steps Overview

| Step | Content | Reference |
|:--:|------|:------:|
| 1 | Choose Department Origin | 3.2 |
| 2 | Allocate Core Attributes (20 points) | 3.3 |
| 3 | Generate initial Explorer team (6 people) | 3.4 |
| 4 | Set up your Outpost | 3.5 |
| 5 | Set your Superior | 3.6 |
| 6 | Set your Guilt | 3.7 |

### 3.2 Step One: Department Origin (roll d6 or choose)

| d6 | Origin | Starting Bonus | Story Hook |
|:--:|------|----------|----------|
| 1 | **Internal Promotion** | Intelligence (INT) +1 | You were once a Veteran Explorer and know the real situation on the front lines — but your old colleagues are now your subordinates |
| 2 | **Parachuted Director** | Reputation (REP) +1 | You were transferred from M.E.G. (Major Explorer Group) headquarters. Bureaucratic support, but the grassroots doesn't trust you |
| 3 | **Thrust into Crisis** | Manpower (MPW) +1 | The previous Director went missing on a mission and you were hastily pushed into the position. The predecessor's shadow looms over the entire department |
| 4 | **Founder** | Equipment (EQP) +1 | You single-handedly built this Bureau branch. Loyal subordinates — but the resources were all scraped together by yourself |
| 5 | **Defector** | Intelligence (INT) +1, Reputation (REP) -1 | You once belonged to a hostile Faction and defected with inside Intelligence. No one fully trusts you |
| 6 | **Inheritor** | Reputation (REP) +2, other attribute -1 (any one) | You inherited the position of a Legendary Director. Everyone's expectations of you are high — too high |

### 3.3 Step Two: Attribute Allocation

Allocate **20 points** across the four attributes (minimum 2 each), then apply the Origin bonus.

**Quick Build Templates (reference only)**:

| Template | Manpower (MPW) | Equipment (EQP) | Intelligence (INT) | Reputation (REP) | Style |
|------|:--------:|:--------:|:--------:|:--------:|------|
| Balanced | 5 | 5 | 5 | 5 | Well-rounded |
| Manpower-Heavy | 7 | 4 | 4 | 5 | Strength in numbers |
| Well-Equipped | 4 | 7 | 4 | 5 | Elite-force approach |
| Intelligence-First | 4 | 4 | 7 | 5 | Know your enemy |
| Reputation-Above-All | 4 | 4 | 5 | 7 | Diplomatic master |

### 3.4 Step Three: Initial Team

Draw from the Explorer pool or have the GM assign **6 initial Explorers**:

- **2 Rookie Explorers** (Experience Level 1)
- **2 Regular Explorers** (Experience Level 2)
- **1 Veteran Explorer** (Experience Level 3)
- **1 Special Explorer** (possesses a rare dual-Specialty or unique background, Experience Level 2–4)

(For the complete 100-person initial Explorer pool, see the GM rulebook appendix.)

### 3.5 Step Four: Outpost Setup

Which Backrooms Level is your frontline base set in? What is its scale?

| Element | Options |
|------|------|
| **Level Location** | Defaults to **Level 1 "Habitable Zone"**, or may be set in another safe Level with GM permission |
| **Scale** | Small (under 30 people), Medium (30–80 people), Large (over 80 people) | Determines the facility level cap and Dormitory base capacity (see table below) |
| **Initial Special Facility** (choose 1) | Medical Station (faster wounded recovery), R&D Lab (unlocks tech tree), Intelligence Center (Intel Accuracy +5%), Training Ground (faster rookie training), Trade Post (trade discount) |

**Outpost Scale Effects Table**:

| Outpost Scale | Facility Level Cap | Dormitory Base Capacity |
|----------|:----------:|:----------:|
| Small (under 30 people) | Up to Lv2 | 10 people |
| Medium (30–80 people) | Up to Lv3 | 25 people |
| Large (over 80 people) | Up to Lv3 (no additional limit) | 50 people |

> Dormitory capacity can be increased by upgrading the "Dormitory" facility (Lv1 10 people / Lv2 25 people / Lv3 50 people).

**Overcapacity Rule**: When the number of on-roster Explorers exceeds Dormitory capacity —

- Each excess person consumes an additional **+10 budget** per month (crowding maintenance fee)
- Public Recruitment automatically fails when already over capacity (you must first upgrade the Dormitory or reduce personnel before recruiting again)
- The department card (see Appendix) should record "on-roster headcount" and "Dormitory capacity" to detect overcapacity promptly

### 3.6 Step Five: Superior Setup

Reporting to superiors is part of your daily routine. Choose your Superior type:

| d4 | Superior Type | Source of Pressure | Favor Condition |
|:--:|----------|----------|----------|
| 1 | **M.E.G. Regional Commander** | Mission quotas, strict reporting requirements | Exceed mission targets, maintain low Casualty Rate |
| 2 | **Independent Faction Leader** | Political loyalty, interest exchange | Serve the Faction's interests, reject hostile Factions |
| 3 | **Military Committee** | Efficiency above all, casualties are acceptable | Complete the most Missions at the lowest cost |
| 4 | **Mysterious Patron** | Obsession with specific Levels or items | Provide discoveries of interest to the patron |

**Superior Relationship Value (SUP)**: After choosing a Superior, record a Superior Relationship Value, starting at 0, ranging from −20 to +20.

- **Month-Start Settlement**: If you meet that Superior's "Favor Condition" this month, Superior Relationship Value +3; if not, −2
- **Effects**:
  - SUP ≥ +10: The Superior provides extra resources — gain +50 budget at the start of each month, or 1 free basic Intelligence
  - SUP ≤ −10: The Superior applies pressure — assign 1 extra mandatory Mission each month (Reputation −2 if uncompleted)
  - −10 < SUP < +10: No additional effect

> Choosing a Superior is no longer purely background flavor — it actually affects your resources and mission burden.

### 3.7 Step Six: Guilt Setup (roleplay core)

Every Director carries their own baggage. Choose or roll d6:

| d6 | Guilt | Roleplay Prompt |
|:--:|------|------------|
| 1 | **The Sacrificed Apprentice** | You once signed off on a mission you knew would fail. You still remember that rookie's name to this day |
| 2 | **The Evacuation Order Never Sent** | You hesitated for fifteen minutes. The cost of those fifteen minutes was three lives |
| 3 | **The Trade** | You once traded an Outpost's location for your own department's safety. That Outpost is now ruins |
| 4 | **Family** | Your brother/sister/partner works in your department. Your hand trembles every time you dispatch them |
| 5 | **The Very First Mission** | It was the first mission after you took office. You now know that decision was wrong — but that no longer matters |
| 6 | **Guiltless** | You genuinely feel no guilt. That may be the most frightening thing of all |

**Guilt Value (GLT)**: After choosing a Guilt option, record a Guilt Value, starting at 0.

- **Increase**: +1 each time a mission result is "Catastrophe", or an Explorer is "Killed in Action (KIA)"; if your Guilt option is "The Evacuation Order Never Sent" and a related decision error occurs, an additional +1
- **Effects**:
  - One of the trigger conditions for Ending C "Walk Into The Backrooms Yourself" is **Guilt Value ≥ 5** (or holding a specific story clue)
  - The higher the Guilt Value, the stronger psychological events such as "The Director's Nightmare" become
  - The Guilt Value does not decrease automatically — it is a debt you cannot erase

---

## Chapter Four: Explorers — The People You Send Out

### 4.1 Explorer Attributes

Each Explorer is an independent Character Sheet containing the following attributes:

| Attribute (Abbrev.) | Meaning | Description |
|:----------|------|------|
| **Experience Level (EL)** | Levels 1–5 | Determines the base contribution value in Missions |
| **Specialty (SPC)** | Combat/Recon/Medical/Engineering/Diplomacy | Primary Specialty + optional Secondary Specialty, affects performance in specific mission types |
| **Mental State (MS)** | Stable/Nervous/Trauma/Breakdown | Affects mission performance and dispatchable status |
| **Stress Value (STR)** | 0–10 | Accumulating to a certain point triggers Mental State deterioration |
| **Contract (CNT)** | Type/Weekly Salary/Remaining Turns | Determines salary cost and contractual obligations |
| **Status (ST)** | Standby/On Mission/Wounded (Light/Moderate/Severe)/Missing/Killed | Determines current dispatchability |
| **Presence (EXI)** | 0–10 | The individual's "degree of existence" in reality and others' memories, subject to Hollow erosion (see 4.8) |

### 4.2 Experience Level

| Level | Name | Mission Bonus | Promotion Condition | Special Ability |
|:--:|------|:------:|----------|----------|
| 1 | **Trainee Explorer** | +5 | — | None |
| 2 | **Regular Explorer** | +10 | Complete 5 Missions | None |
| 3 | **Veteran Explorer** | +15 | Complete 15 Missions | **Cool Head**: May reroll one Stress Check per mission |
| 4 | **Elite Explorer** | +20 | Complete 35 Missions | **Professional Intuition**: Gain one extra Intelligence clue during mission preparation |
| 5 | **Legendary Explorer** | +25 | Cannot be promoted | **Legendary Will**: Immune to Breakdown, Stress locked at 9, gains one "Last Stand" |

**"Last Stand"**: A Legendary Explorer may declare its use during a mission to directly upgrade one mission Check result to a "Critical Success". After use, that Explorer automatically suffers Severe wounds and permanently lowers their Stress cap — this is not a resource to be used lightly.

### 4.3 The Five Specialties

| Specialty (Abbrev.) | Applicable Mission Types | Specialty Bonus | Special Ability |
|:----------|------------|:------:|----------|
| **Combat (CMB)** | Entity hunting, Outpost defense, escort | +5 | Suppressing Fire: Gain advantage on one crisis Check |
| **Recon (RCN)** | Reconnaissance, exploration, search | +5 | Intel Accuracy automatically raised one tier (for that mission) |
| **Medical (MED)** | Search and Rescue, medical support, disaster response | +5 | Field First Aid: Can reduce one ally's injury by one tier |
| **Engineering (ENG)** | Construction, resource recovery, tech deployment | +5 | Temporary Repair: Can restore the function of one depleted Equipment |
| **Diplomacy (DIP)** | Diplomacy, trade, recruiting, persuasion | +5 | Rhetoric Reroll: Reroll one failed persuasion-related Check |

**Specialty Stacking Rules**:

- Each person has **1 Primary Specialty** (full bonus +5 + special ability)
- Veteran and above may gain **1 Secondary Specialty** (bonus halved to +3, no special ability)
- Trainee and Regular Explorers have only a Primary Specialty
- If a mission type matches both the Primary and Secondary Specialty, only the highest bonus applies (no stacking)
- **Dual Primary Specialty**: If the Secondary Specialty is the same as the Primary Specialty (e.g., "Combat + Combat"), it counts as pure specialization, granting **+10** (Primary +5 + same-specialty bonus +5), which is higher than the usual Secondary Specialty's +3. This is the rare advantage of Special Explorers (see GM Appendix C.4).
### 4.4 Mental State and Stress

**Stress Value (STR) Range**: 0–10

| Stress Range | Mental State | Mission Impact | Deployability |
|:------:|----------|----------|:------:|
| 0–3 | **Stable (STB)** | No effect | ✅ |
| 4–6 | **Nervous (TNS)** | Personal mission bonus −5 | ✅ (May refuse high-risk missions) |
| 7–9 | **Trauma (TRM)** | Personal mission bonus −10, Specialty unusable | Each turn roll d6: 1–3 means cannot be dispatched |
| 10 | **Breakdown (BRK)** | Cannot take missions | ⚠️ Reversible (see Breakdown Handling Options below) |

**Stress Change Triggers**:
| Event | Stress Change |
|------|:------:|
| Participate in a mission | +1 |
| Teammate lightly wounded | +1 |
| Teammate severely wounded or missing | +2 |
| Teammate dies | +3 |
| Mission "Marginal Success" | +1 |
| Mission "Failure" | +2 |
| Mission "Catastrophe" | +3 |

**Stress Recovery Methods**:
| Method | Effect | Cost |
|------|:--:|:---:|
| Rest one turn (not dispatched) | Stress −2 | None |
| Psychological Counseling | Stress −3 | 30 Budget |
| Team Meal | Whole team Stress −2 | 50 Budget |
| Complete mission "Critical Success" | Whole team Stress −1 | (inherent to mission) |

**Breakdown Handling Options** (when Mental State reaches "Breakdown," the Explorer cannot take missions, but still has uses):
| Option | Description | Cost |
|------|------|------|
| **Transfer to Instructor** | Assigned to the training ground, improving rookie training efficiency (training ground promotion requirement reduced by an additional −1 session) | No longer takes missions |
| **Transfer to Logistics** | Assigned to Outpost administration, provides +5% Monthly Intel Accuracy per month, or −5% Equipment repair cost (choose one) | No longer takes missions |
| **Terminate Contract** | Pay bereavement compensation and remove from roster, triggers a Reputation event | Lose the Explorer |
| **Long-Term Treatment** | Arrange 3–6 Game Months of recuperation (not dispatched) + professional care costing 50 Budget per month; at the end roll d100 ≤ 50 to recover to "Trauma" | Occupies roster slot long-term, high cost |
| **Special Treatment** | Consume legendary-tier resources (e.g., Liquid Silence) or trigger a specific event; 40% chance to immediately recover to "Trauma" | Costly resources / story-dependent |

### 4.5 Contract System

| Contract Type | Applicable To | Weekly Salary | Length | Key Terms |
|----------|:------:|:---:|:---:|----------|
| **Temporary (TMP)** | Trainee | 15 | 4 turns | Can be terminated at any time, no penalty |
| **Standard (STD)** | Trainee/Regular | 30 | 8 turns | Early termination penalty = 4 weeks' salary |
| **Long-Term (LNG)** | Regular/Veteran | 60 | 12 turns | Disability insurance (half salary while injured) |
| **Elite (ELT)** | Elite | 100 | 16 turns | Hazard pay +20 per mission |
| **Legendary Contract (LGD)** | Legendary | 200 | 24 turns | Veto right (may refuse a single dispatch) + private dormitory |

**Total Monthly Salary**: Sum the Weekly Salary of all enlisted Explorers, deducted from Budget at the start of each month.

### 4.6 Recruiting Explorers

| Method | Cost | Output | Cooldown | Risk |
|------|:---:|------|:---:|------|
| **Open Recruitment (REC)** | 50 Budget + Reputation (REP) Check DC 50 | 1–3 Trainee Explorers | 4 turns | Failure wastes cost + Reputation −1 |
| **Poaching (PCH)** | 200 Budget + Reputation (REP) Check DC 75 | 1 Veteran or Elite | 8 turns | Faction relations worsen |
| **Discovery in Mission (MDS)** | No cost | Random (see GM rulebook random table) | No cooldown (pure chance) | No gain if persuasion fails |
| **Event Trigger (EVT)** | Variable | High-value Explorer | GM-controlled | Story-guaranteed |

**Recruitment Output Source**: All recruited Explorers are randomly drawn from the "Explorer Pool" of the corresponding rank (see Appendix C of the GM rulebook for the full 100-Explorer pool):
- Open Recruitment → yields Trainee Explorers (Rank 1, drawn from the Rookie Pool)
- Poaching → yields Veteran or Elite Explorers (Rank 3 / 4, drawn from the Veteran Pool / Elite Pool)
- Discovery in Mission → Rank and persuasion difficulty determined by the "Discovery in Mission Result Table" (GM rulebook Appendix D)
- Event Trigger → designated by the GM per the story



---

### 4.7 Status Effects Overview

Explorers may fall into the following abnormal states during missions. All states have full rule support from character creation to the end of the game:

| Status (Abbrev.) | Common Source | Effect | Duration / Removal |
|----------|----------|------|--------------|
| **Poison (PSN)** | Toxic Moth scale powder, gas spread event | Personal mission bonus −5, Stress +1 per mission phase | Use 1 unit of Almond Water to detoxify (high-capacity Almond Water canister +10% resistance) |
| **Burning (BRN)** | Flame attack, nest dust explosion | Encounter/combat-related Checks −5 | d3 turns (fireproof Equipment can shorten) |
| **Psychological Trauma (TRM-S)** | Mental attack event, Partygoer temptation, The Hollow | Stress +1~+3, personal bonus −5~−10 | Recovers per Mental State rules after mission ends |
| **Slow (SLW)** | Gravity anomaly, environmental obstacle | Evacuation DC +5, encounter escape rate −10% | During the current mission |
| **Environmental Damage (ENV)** | Level 3 electrical station, sudden temperature change, radiation zone | −3 personal bonus per 10 minutes if unprotected | Stops upon entering a protected environment or wearing corresponding protective gear (radiation suit / constant-temperature sleeping bag) |
| **Darkness (DRK)** | Darkness descent event, all light sources extinguished | All vision-dependent Equipment ineffective, Smilers Threat Level +1 | Removed after light source is restored |
| **Existence Erosion (EXI)** | The Hollow | Presence −1; those Erased vanish from everyone's memory | See §4.8 Presence rules |

> For detailed GM-version trigger and removal resolutions, see Chapter 2 of the GM rulebook, "Unified Status Effects Table."

### 4.8 Presence Rules (EXI)

**Presence (EXI)** is a hidden value for each Explorer, starting at 10, recorded on the Explorer Character Sheet (see Appendix B).

- **Erosion**: When encountering "The Hollow," 1 random Explorer's Presence −1 every 10 minutes
- **Erasure**: Those whose Presence reaches zero vanish from everyone's memory—as if they never existed. Their Equipment and records may remain as "unclaimed mysteries," but they are treated as never having joined the roster.
- **Liquid Silence**: Each drink permanently reduces Presence by −1 (risks manifest after 3 or more cumulative uses)
- **Emotional Anchor**: An Explorer carrying a cherished keepsake (SPC-05) gains a one-time +20 resistance bonus (see the Bestiary entry "The Hollow")

## Chapter Five: Equipment System

### 5.1 Equipment Categories

| Category (Abbrev.) | Scope of Effect | Mission Bonus | Example |
|:----------|----------|:------:|------|
| **Basic Equipment (BE)** | General | +1 each | Standard uniform, flashlight, rations, Almond Water (standard) |
| **Combat Equipment (CE)** | Combat-related missions | +2 each | Assault rifle, armor, flashbang, shotgun |
| **Survival Equipment (SE)** | Long-duration / extreme environment missions | +2 each | High-capacity Almond Water canister, radiation suit, tent, beacon |
| **Tech Equipment (TE)** | Intelligence gathering, communication missions | +2 each | Recon drone, cross-Level communicator, thermal imager |
| **Experimental Equipment (EE)** | Various missions (high bonus) | +4 each | Prototype teleporter, Almond Water concentrate injector, dimensional stabilizer |

**Stacking Limits**:
- Effects of up to **3 pieces** of the same category may stack
- Total bonus from all Equipment in a single mission is capped at **+30**
- The Equipment (EQP) attribute value × 2 determines the Equipment bonus base for a single mission (EQP 2 → +4, EQP 12 → +24, cap EQP 15 → +30)

### 5.2 Equipment Catalog Quick View

#### Basic Equipment (BE)

| Item | Price | Effect |
|------|:--:|------|
| Standard Uniform | 10 | Basic protection |
| High-Power Flashlight | 15 | Resists dark environments |
| Basic Rations (3-day) | 10 | Sustain mission duration |
| Almond Water (standard ×3) | 25 | Detoxify, soothe mind, drive off low-tier Entities |
| Basic Toolbox | 30 | Repair Equipment |
| First Aid Kit | 30 | Light wounds need not count as casualties |
| Communication Headset | 25 | Maintain squad comms |

#### Combat Equipment (CE)

| Item | Price | Effect |
|------|:--:|------|
| Assault Rifle | 80 | Basic firepower |
| Tactical Armor | 100 | Casualty Rate −5% |
| Flashbang (×3) | 45 | Encounter escape +10% |
| Shotgun | 70 | Close-range advantage |
| Stun Baton | 40 | Non-lethal subdual |
| Smoke Grenade (×3) | 35 | Retreat cover |
| Sniper Rifle | 150 | Long-range fire support |

#### Survival Equipment (SE)

| Item | Price | Effect |
|------|:--:|------|
| High-Capacity Almond Water Canister | 60 | 6 units of Almond Water, Poison/mental resistance +10% |
| Radiation Suit | 90 | Environmental Damage resistance |
| Reinforced Tent | 40 | Safe point for long-duration missions |
| Navigation Beacon | 50 | Reduces chance of getting lost |
| Portable Water Filter | 35 | Water source replenishment |
| Constant-Temperature Sleeping Bag | 30 | Adapts to extreme temperatures |
| Climbing Gear Kit | 45 | Terrain traversal |

#### Tech Equipment (TE)

| Item | Price | Effect |
|------|:--:|------|
| Micro Recon Drone | 100 | Intel Bias −1 tier, encounter chance −5% |
| Cross-Level Communicator | 150 | Director may order immediate retreat, retreat Casualty Rate −10% |
| Thermal Imager | 80 | Ignores dark environments |
| Sonar Detector | 90 | Sense behind walls |
| Environmental Analyzer | 120 | Early warning of environmental hazards |
| Electronic Unlocker | 70 | Crack electronic locks |
| Holographic Map Projector | 200 | All subsequent missions on the same Level DC −5 |

#### Experimental Equipment (EE)

| Item | Price | Effect | Side Effect (roll d100) |
|------|:--:|------|------|
| Prototype Teleporter | 300 | +4 bonus, can escape encounters | 01–30: Displacement (1 person missing); 31–60: EMP explosion (whole team lightly wounded); 61–100: Normal |
| Almond Water Concentrate Injector | 180 | +3 bonus, severe wound → light wound | 01–40: Injector suffers mental breakdown; 41–70: Half effect; 71–100: Normal |
| Resonance Destroyer | 250 | +4 bonus, area attack against Entities | 01–50: Overheat shutdown; 51–100: Normal |
| Cognitive Enhancement Helmet | 220 | +3 bonus, immune to mental attacks | 01–30: Addiction (mental downgrade + dependency); 31–100: Normal |
| Phase Vest | 280 | +3 bonus, halves physical damage | 01–40: User severely wounded; 41–100: Normal |
| Dimensional Stabilizer | 350 | +4 bonus, immune to spatial anomalies | 01–50: Overheat shutdown; 51–100: Normal |
| Telepathy Amplifier | 300 | +3 bonus, foresees encounters | 01–50: Mental backlash (user Trauma); 51–100: Normal |

### 5.3 Equipment Management

| Operation | Cost | Description |
|------|:---:|------|
| **Purchase** | As catalog price | Bought from the trade catalog at the start of each month. Some Equipment has rarity restrictions (GM controls stock) |
| **Post-Mission Depletion** | Depends on mission result | Equipment may be damaged after completing a mission. Depletion Check: Success/Marginal Success DC 25; Failure DC 60; Catastrophe DC 90 (failed Check = Equipment damaged) |
| **Repair** | 30% of original price | Repair damaged Equipment |
| **Full Overhaul** | 50/month | All Equipment auto-passes the next Depletion Check |
| **Recycle** | — | May acquire special Backrooms items during missions as a new Equipment source |

**Consumable Carry Limit**: Echoing the "resource scarcity" worldview, each Explorer may carry a maximum of **6 units of Almond Water** per mission (high-capacity canister counts as 6 units, standard pack ×3 counts as 3 units). Excess occupies an "Equipment slot" and counts toward the per-mission total bonus cap (+30). Extremely rare consumables such as Liquid Silence do not count toward this limit, but at most 1 copy may be carried per mission.

---

## Chapter Six: Mission System — The Player's Perspective

### 6.1 Mission Flow (once per month)

```
Intelligence Gathering → Mission Selection → Dispatch Team Composition → Doctrine Setting → Execution Check → Result Settlement
```

### 6.2 Step One: Intelligence Gathering

Before selecting a mission, you may purchase Intelligence for the mission's target area:

| Intel Tier | Cost | Effect (what you see) |
|:------:|:---:|------|
| **No Intel** | 0 | The GM only gives a vague difficulty description ("might be dangerous") |
| **Basic Intel** | 50 | The GM gives an estimated Difficulty Class (DC), but there may be a ±25% bias |
| **Detailed Intel** | 150 | The GM gives a more precise DC, bias reduced to ±15%. You learn the main Entity types |
| **Precise Intel** | 300 | DC bias only ±5%. You learn Entity positions and numbers |
| **Perfect Intel** | 500 | No bias. Near-complete mission preview |

> **Note**: Intel Accuracy (IAC) determines your maximum Intel Tier. For example, if Intelligence (INT) is 4, you can only purchase up to "Basic Intel."

### 6.3 Step Two: Mission Selection

The monthly mission list is provided by the GM. You decide which missions to run this month based on the **Mission Cap (MSC)**. Each mission type has different risks and rewards:

| Mission Type | Typical Difficulty (DC) | Minimum Members | Recommended Specialty | Budget Reward (base) | Main Gains (non-budget) |
|----------|:-----------:|:-----:|----------|:--------------:|------------------|
| **Recon (REC)** | 60–80 | 2 | Recon, Engineering | +40 | Intelligence +2~+5 |
| **Supply Run (SPL)** | 40–60 | 1 | Combat, Engineering | +80 | Reputation +1 |
| **Search and Rescue (SAR)** | 80 | 3 | Medical, Recon | +80 | Manpower recovery, Reputation +3 |
| **Resource Recovery (RRV)** | 80 | 3 | Combat, Engineering | +120 | Equipment +2, rare items |
| **Entity Hunting (EHT)** | 100 | 4 (at least 1 Elite) | Combat, Medical | +200 | Reputation +5, special loot |
| **Diplomacy (DPL)** | 60 | 1 (recommended 2) | Negotiation | +60 | Reputation +3, unlock new trades |
| **Emergency Evacuation (EEV)** | 100–120 | All available | Combat, Engineering, Medical | +100 | Protect Manpower, possible Equipment loss |

> **Note**: The above DCs are true values. What you see are estimates including Intel Bias.
>
> **Budget Reward Settlement**: Actual Budget gained = base value × Result Reward Multiplier (Critical Success ×1.5 / Success ×1.0 / Marginal Success ×0.7 / Failure and Catastrophe ×0, see §6.5 Result Table). Doctrine adjusts the Reward Tier (Cautious −1 tier, Aggressive +1 tier), folded into the multiplier at settlement. For example, "Supply Run" Critical Success = 80 × 1.5 = **+120 Budget**; "Entity Hunting" Success = 200 × 1.0 = **+200 Budget**.

### 6.4 Steps Three-Four: Dispatch Team Composition and Doctrine

**Dispatch Team Selection**:
- Select members from standby Explorers, calculate team experience bonus (sum of each Explorer's experience level value)
- Ensure member count is not below the mission's required minimum
- Consider Specialty matching (matched Specialty provides an extra +5 bonus)

**Doctrine Selection**:

| Doctrine | Check Bonus | Safety Effect | Reward Effect |
|------|:------:|----------|----------|
| **Cautious** | −5 | Safety Level +1 (Casualty Rate lowered) | Reward Level −1 (reward lowered) |
| **Standard** | ±0 | No change | No change |
| **Aggressive** | +5 | Safety Level −1 (Casualty Rate raised) | Reward Level +1 (reward increased) |

### 6.5 Step Five: Execution Check

```
Final Check Value = d100 + Team Experience Bonus (sum of each Explorer's Experience) + Equipment Bonus (EQP × 2) + Doctrine Bonus + Specialty Matching Bonus
```

**The GM will inform you of the Check result**, but you do not know the actual DC (unless Intel Bias is 0). Results correspond to:

| Result | Condition | Reward Multiplier | Casualty Risk |
|------|------|:------:|:------:|
| **Critical Success** | Check Value ≥ DC+10, or natural 96–100 | ×1.5 | No casualties |
| **Success** | Check Value ≥ DC | ×1.0 | Low risk (15%) |
| **Marginal Success** | Check Value ≥ DC−15 | ×0.7 | Medium risk (35%) |
| **Failure** | Check Value ≥ DC−35 | ×0 | High risk (60%) |
| **Catastrophe** | Check Value < DC−35, or natural 1–5 | ×0 | Whole-team risk (90%) |

> Natural 1–5 (d100 roll of 01–05) = inevitable Catastrophe; natural 96–100 = inevitable Critical Success. The unpredictability of The Backrooms is ever-present.
### 6.6 Step Six: Outcome Resolution

After the mission is complete, perform the following settlement:

1. **Reward Settlement**: Based on mission type and outcome tier, gain rewards such as Intelligence, Budget, Equipment, and Reputation
2. **Casualty Determination**: Each dispatched Explorer independently rolls a Casualty Check (d100) based on the mission outcome (Safety Axis). The Base Casualty Rate is determined by the mission outcome, then adjusted by Equipment and Doctrine
3. **Equipment Depletion**: Equipment depletion is determined by the mission difficulty value − Equipment (EQP) value
4. **Intelligence Update**: That Level's Intel Tier automatically increases by one tier (no Budget spent)
5. **Stress Update**: Update participating Explorers' Stress value based on the mission outcome

---

## Chapter Seven: Solo Play Guide

### 7.1 Why Support Solo Play?

The core of this game is strategic management rather than social interaction—you can make all decisions alone, just like a real Director sitting at the desk, without needing to negotiate with other players.

### 7.2 The "Commit-then-Reveal" Mechanic

The biggest challenge in Solo Mode is that the Intel Bias system requires "information you don't know." The solution:

1. **Make all decisions first**: Choose dispatch personnel, Equipment, and Doctrine—once everything is confirmed, no changes can be made
2. **Roll the Bias Die (covered)**: Roll the d100 Bias Die, but cover it with a cup or use a dice tower (do not look immediately)
3. **Roll the mission check die**: Roll the d100 mission check and record the result
4. **Reveal the Bias Die**: Check the Bias Die and calculate the actual DC
5. **Determine the outcome**: Determine mission success or failure based on the actual DC

> Key: Never go back between steps 1–2. If you only discover after rolling the mission check die that the Bias Die caused the DC to spike, that is the price of The Backrooms—not a flaw in the rules.

### 7.3 Simplified Alternative: The Poker Card Bias Method

If you lack the means to hide dice, you can substitute a deck of poker cards:

- **No Intel**: Draw 1 card. Red suit = DC increases, black suit = DC decreases. Number × 4 = offset percentage
- **Basic Intel**: Same as above, but number × 2.5
- **Detailed Intel**: Same as above, but number × 1.5
- **Precise Intel**: Same as above, but number × 0.5
- **Perfect Intel**: Do not draw a card

### 7.4 Solo Monthly Decision Checklist

```
□ Month-start: Calculate this month's Budget (Reputation × 50 + Intelligence × 30)
□ Month-start: Deduct this month's total salary
□ Month-start: Handle wounded recovery, follow up on missing personnel
□ Choose missions (do not exceed the Mission Cap)
□ For each mission:
  □ Purchase Intel (decide how much Budget to invest)
  □ Read the intel report (check the estimated DC)
  □ Select dispatched Explorers
  □ Choose action Doctrine (Cautious / Standard / Aggressive)
  □ Perform the "Commit-then-Reveal" check
  □ Record outcome, casualties, equipment depletion
□ Perform the Bureau's monthly maintenance (repairs, recruitment, facility upgrades)
□ Advance the timeline, roll monthly events (see GM rulebook random event table)
□ Write this month's Director's log (optional, enhances roleplay immersion)
```

---

## Chapter Eight: Department Growth

### 8.1 Attribute Improvement

| Attribute | Improvement Method | Cost | Condition |
|-----------|--------------------|:---:|-----------|
| **Manpower (MPW)** | Recruit expansion | 200 Budget | Reputation (REP) ≥ current value |
|  | Facility Upgrade (Dormitory) | 400 Budget | Own a Training Ground |
| **Equipment (EQP)** | Equipment Procurement | 300 Budget | — |
|  | R&D Upgrade | 400 Budget + 8 Turns | Own an R&D Lab |
| **Intelligence (INT)** | Dispatch reconnaissance missions | Mission accumulation | Intel auto-improves after 3 missions on the same Level |
|  | Intel Purchase Plan | 250 Budget | — |
| **Reputation (REP)** | Mission completion | Mission accumulation | For every 6 missions completed cumulatively (any outcome), Reputation +1 (stackable, up to the cap) |
|  | Critical Success | Mission accumulation | Each "Critical Success" grants an additional +1 (not counted toward the 6-mission cumulative total) |
|  | Public Relations Campaign | 300 Budget | Reputation +1 (immediate) |

### 8.2 Facility Upgrades

| Facility | Level 1 (already owned) | Level 2 (300 Budget + 4 Turns) | Level 3 (600 Budget + 8 Turns) |
|----------|:----------------------:|:------------------------------:|:------------------------------:|
| **Medical Station** | Wounded recovery accelerated by 1 Turn | Severe wound recovery −1 Turn | Death→Severe wound chance +10% |
| **R&D Lab** | Unlock tech tree Lv1 | Unlock tech tree Lv2 | Unlock tech tree Lv3 |
| **Intel Center** | Intel Accuracy +5% | Intel Accuracy +10% | Gain 1 free Basic Intel per month |
| **Training Ground** | Trainee training −1 Turn | Regular training −1 Turn | Veteran promotion −5 missions |
| **Trade Post** | Equipment price 95% | Equipment price 90% | Unlock exclusive Equipment |
| **Dormitory** | Capacity 10 people | Capacity 25 people | Capacity 50 people + morale bonus |

**Training Ground and Promotion Cycle**: The base cycle for Explorer promotion is the number of missions completed (see 4.2). The Training Ground can shorten this cycle:
- Base cycle: Trainee→Regular 5 missions; Regular→Veteran 15 missions; Veteran→Elite 35 missions
- Training Ground Lv1: Missions required for Trainee promotion −1 (5 → 4)
- Training Ground Lv2: Missions required for Regular promotion −1 (15 → 14)
- Training Ground Lv3: Missions required for Veteran promotion −5 (35 → 30)
- **Accelerated Promotion (paid)**: Spend 1 Game Month + 50 Budget to directly promote 1 Trainee to Regular (not counted toward mission count)

### 8.3 Tech Research Tree

Each research requires spending Budget + waiting time; at the end, roll a research check (d100 + INT × 3 ≥ DC 70):

| Tech Line | Lv1 (200 Budget + 4 Turns) | Lv2 (400 Budget + 8 Turns) | Lv3 (800 Budget + 12 Turns) |
|-----------|:-------------------------:|:-------------------------:|:--------------------------:|
| **Protection Tech** | Improved Uniform (casualties −3%) | Lightweight Armor (casualties −6%) | Energy Shield (first hit immunity) |
| **Almond Water Application** | High-Efficiency Filter | Concentrated Almond Water (double effect) | Synthetic Almond Water (+5 units per month) |
| **Communication Tech** | Enhanced Signal (encounter −5%) | Quantum Communication (retreat DC −10) | Cross-Dimensional Communication (contact any Level) |
| **Entity Research** | Entity Encyclopedia (known Entity +3) | Expulsion Device (encounter DC −5) | Entity Communication Protocol |
| **Dimensional Theory** | Level Prediction (Intel Accuracy +5%) | Exit Location (evacuation +10%) | Controlled Teleport (mission DC −10) |
| **Human Augmentation** | Endurance Enhancement (long-duration mission DC −5) | Cognitive Enhancement (Will Contest +10%) | Adaptive Mutation (Environmental Damage immunity) |

---

## Appendix A: Player Quick Reference

### A.1 Monthly Settlement Process

| Order | Action | Calculation |
|:----:|--------|-------------|
| 1 | Calculate budget income | Reputation (REP) × 50 + Intelligence (INT) × 30 |
| 2 | Deduct salary | Sum of all on-roster Explorers' weekly salaries |
| 3 | Handle recovery | Wounded recovery time −1, follow up on missing personnel |
| 4 | Choose missions | Do not exceed the Mission Cap (Manpower ÷ 3, rounded up) |
| 5 | Execute missions | See A.2 |
| 6 | Post-processing | Repairs, recruitment, facility upgrades, events |

### A.2 Mission Check Quick Reference

```
Final Check Value = d100 + Team Experience Bonus + Equipment Bonus (EQP × 2) + Doctrine Bonus + Specialty Match Bonus
```

### A.3 DC Difficulty Reference

| Difficulty | DC | Example |
|-----------|:--:|---------|
| Trivial | 40 | Routine patrol of a familiar Level |
| Easy | 55 | Supply transport on a lightly threatened Level |
| Medium | 70 | Standard reconnaissance, diplomatic contact |
| Hard | 85 | Resource recovery, search and rescue on a dangerous Level |
| Very Hard | 100 | Unknown deep-level exploration, Entity hunting |
| Suicide-Level | 115 | Boss-level Entity, Level collapse evacuation |

### A.4 Mission Outcome Quick Reference

| Outcome | Condition | Reward | Base Casualty Rate |
|---------|-----------|:------:|:------------------:|
| Critical Success | ≥ DC+10 or natural 96+ | ×1.5 | 0% |
| Success | ≥ DC | ×1.0 | 15% |
| Marginal Success | ≥ DC−15 | ×0.7 | 35% |
| Failure | ≥ DC−35 | ×0 | 60% |
| Catastrophe | < DC−35 or natural 1–5 | ×0 | 90% |

### A.5 Casualty Calculation Quick Reference

```
Final Casualty Rate = max(5%, Base Casualty Rate − EQP × 2% − other adjustments + other penalties)
```

Each dispatched Explorer independently rolls d100; if ≤ Final Casualty Rate, a casualty is triggered.

Doctrine offset: Cautious −10%, Aggressive +10%. Medical Equipment −5%. Almond Water −5%.

### A.6 Injury Quick Reference Table

| d100 | Injury | Recovery Time | Special Effect |
|:---:|--------|:-------------:|----------------|
| 01–40 | Minor Wound | 1 Turn | Next mission personal bonus −5 |
| 41–70 | Moderate Wound | 3 Turns | Cannot be dispatched during this period |
| 71–90 | Severe Wound | 6 Turns | If d100 ≤ 30, permanent experience level −1 |
| 91–100 | Death | — | Permanently removed, triggers pension and Reputation event |

---

### A.7 Search and Rescue Mission Rules

When an Explorer goes "Missing in Action (MIA)", a search and rescue can be launched:

- **Time Window**: Missing 1–3 days DC normal / 4–7 days DC +10 / 8–14 days DC +20 / 15+ days DC +30
- **Initial Clue Count** = Intelligence (INT) ÷ 2 (rounded down), maximum 3. Each clue lowers the search-and-rescue DC by 10
- **Wait for Self-Return**: At the start of each month, roll d100; if ≤ 5, the missing person returns on their own (carrying Basic Intel)

> Full rules in GM rulebook Chapter Two, "Search and Rescue Mission Rules."

---

## Appendix B: Blank Player Character Sheet

```
┌──────────────────────────────────────────────────────────────────────────────┐
│          The Backrooms Administration Bureau Explorer Character Sheet          │
├──────────────────────────────────────────────────────────────────────────────┤
│ Name: ___________  Gender: ___  Age: ___                                      │
│ ID: ___________  Department: ___________                                       │
├──────────────────────────────────────────────────────────────────────────────┤
│ Experience Level (EL): ___ (Trainee / Regular / Veteran / Elite / Legendary)  │
│ Mission Bonus: ___                                                             │
│ Missions Completed: ___                                                        │
├──────────────────────────────────────────────────────────────────────────────┤
│ Primary Specialty (SPC): ___ (Combat / Recon / Medical / Engineering / Negotiation)│
│ Secondary Specialty (SPC): ___ (if any)                                       │
│ Specialty Bonus: Primary +5 / Secondary +3                                    │
├──────────────────────────────────────────────────────────────────────────────┤
│ Mental State (MS): ___ (Stable / Nervous / Trauma / Breakdown)                │
│ Stress (STR): ___/10                                                          │
│ Presence (EXI): ___/10                                                        │
├──────────────────────────────────────────────────────────────────────────────┤
│ Contract Type (CNT): ___  Weekly Salary: ___                                  │
│ Remaining Turns: ___  Special Terms: ___________                              │
├──────────────────────────────────────────────────────────────────────────────┤
│ Current Status (ST): ___                                                      │
│ □ On Standby □ On Mission □ Wounded (Minor / Moderate / Severe)              │
│ □ MIA □ Dead                                                                  │
├──────────────────────────────────────────────────────────────────────────────┤
│ Background Summary:                                                           │
│ _________________________________________                                    │
│ _________________________________________                                    │
├──────────────────────────────────────────────────────────────────────────────┤
│ Special Abilities:                                                           │
│ _________________________________________                                    │
└──────────────────────────────────────────────────────────────────────────────┘
```

> A standalone Excel template `sheets/空白玩家角色卡.xlsx` is provided, with fields identical to this sheet and built-in auto-calculating Mission Bonus / Specialty Bonus / Promotion Remaining / Presence (EXI) hints, so you can copy the sheet to fill in each Explorer directly.

---

## Appendix C: Term Reference Table

| Abbr | Full Name | Description |
|:----:|-----------|-------------|
| MPW | Manpower | Number and quality of dispatchable Explorers |
| EQP | Equipment | Quality of weapons, armor, tools, vehicles |
| INT | Intelligence | Knowledge reserve of The Backrooms |
| REP | Reputation | Influence within the Backrooms community |
| BGT | Budget | Monthly available funds |
| MSC | Mission Cap | Number of missions executable simultaneously |
| EDR | Equipment Degradation Rate | Equipment consumption after missions |
| IAC | Intel Accuracy | Risk assessment accuracy |
| EL | Experience Level | Explorer rank |
| SPC | Specialty | Explorer's professional field |
| MS | Mental State | Explorer's mental health |
| STR | Stress | Accumulated psychological pressure |
| EXI | Presence | Degree of an individual's existence in reality and memory |
| SUP | Superior Relation | Quality of relationship with the Superior |
| GLT | Guilt | Director's accumulated guilt |
| CNT | Contract | Explorer employment terms |
| ST | Status | Explorer's current situation |
| DC | Difficulty Class | Mission success threshold |
| BE | Basic Equipment | General-purpose equipment |
| CE | Combat Equipment | Combat-use equipment |
| SE | Survival Equipment | Extreme-environment equipment |
| TE | Tech Equipment | High-tech equipment |
| EE | Experimental Equipment | Unstable high-bonus equipment |

---

> **"Courage is not walking into The Backrooms—courage is sending someone else into The Backrooms, and sitting here waiting for them to come back."**
>
> — Founding precept of The Backrooms Administration Bureau, B.Y. 1
