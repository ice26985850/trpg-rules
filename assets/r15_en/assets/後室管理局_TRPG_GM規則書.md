# The Backrooms Administration Bureau TRPG — GM Rulebook

> **Version:** v1.0
> **A Word to the GM:** What you hold is more than a rulebook — you are the superior, the intelligence officer, fate itself. Your task is not to defeat the players, but to give weight to every decision and a name to every casualty.

---

## Chapter One: Core Rule System (Complete Edition)

### 1.1 Dice System: d100 Modifier vs. Difficulty Class

**Core Formula**:
```
Final Check Value = d100 + Total Modifier
Success Condition: Final Check Value ≥ Difficulty Class (DC)
```

**Modifier Composition**:
| Source | Calculation | Range |
|------|------|:---:|
| Team Experience Bonus | Σ EXP of each Explorer | +5 ~ +125 (5 × 25) |
| Equipment Bonus | Equipment (EQP) × 2 | +4 ~ +24 (initial EQP2–12) / +30 (cap EQP15) |
| Doctrine Bonus | Cautious −5 / Standard ±0 / Aggressive +5 | −5 ~ +5 |
| Specialty Match Bonus | +5 (primary) / +3 (secondary) per matching Specialty | +5 ~ +25 |

### 1.2 Difficulty Class (DC) Full Ladder

| Difficulty | DC | Narrative Description | Typical Missions |
|------|:--:|----------|----------|
| **Trivial** | 40 | Almost no risk. Routine work | Patrol of familiar safe Levels, supply transport on established routes |
| **Easy** | 55 | Minor risk. Tasks that shouldn't go wrong | Light-threat reconnaissance, low-value resource recovery |
| **Moderate** | 70 | Reasonable challenge. Manageable with adequate preparation | Standard reconnaissance, diplomatic contact, routine Search and Rescue |
| **Hard** | 85 | Significant threat. Requires experience and equipment | Resource recovery on dangerous Levels, exploration of known Entity zones |
| **Extreme** | 100 | Extremely dangerous. Only an elite team stands a chance | Unknown deep-layer exploration, Entity hunting, high-value recovery |
| **Suicidal** | 115 | A death sentence. Only Legendary Explorers may survive | Boss-class Entity, Level collapse evacuation, first descent into the deep |

### 1.3 How the GM Uses DC (Information Hidden from Players)

**Step 1**: Based on the mission's true difficulty, set the **True DC**.

**Step 2**: Based on the Intel Tier the players purchased, roll the **Bias Die (d100)** — this die is hidden from the players:

| Intel Tier | Bias Die Result → DC Shift |
|----------|------------------------|
| none | 01–20: −40% / 21–50: −20% / 51–80: +20% / 81–100: +40% |
| basic | 01–33: −25% / 34–66: 0% / 67–100: +25% |
| detailed | 01–50: −15% / 51–100: +15% |
| precise | 01–50: −5% / 51–100: +5% |
| perfect | No Bias |

**Step 3**: Inform the players of the **Estimated DC Range** (i.e., the original DC ± the Bias range corresponding to the Intel Tier), but do not reveal the actual shift.

```
Example: True DC = 70 (Moderate difficulty)
Players purchase detailed Intel (Bias ±15%) → GM says: "Based on intelligence analysis, this mission's difficulty is roughly between 60–81"
GM actually rolls the Bias Die: 85 → shift +15% → Actual DC = 70 × 1.15 = 81 (the harder end)
Player's final Check roll comes up 85 → 85 ≥ 81 → Success!
What the players don't know: they completed the mission "by the skin of their teeth."
```

**Step 4**: After the players roll the mission Check die, resolve the outcome against the **Actual DC**.

### 1.4 Outcome Resolution Rules

**Priority Check Order**:

| Priority | Condition | Result |
|:----:|------|------|
| 1 | Natural d100 01–05 | **Catastrophe** (ignores Modifier) |
| 2 | Natural d100 96–100 | **Critical Success** (ignores DC) |
| 3 | Margin ≥ +20 (Check Value − Actual DC ≥ 20) | **Critical Success** |
| 4 | Margin ≥ 0 (Check Value − Actual DC ≥ 0) | **Success** |
| 5 | Margin ≥ −15 (Check Value − Actual DC ≥ −15) | **Marginal Success** |
| 6 | Margin ≥ −35 (Check Value − Actual DC ≥ −35) | **Failure** |
| 7 | Margin < −35 (Check Value − Actual DC < −35) | **Catastrophe** |

### 1.5 Doctrine Shift (Dual-Axis System)

Doctrine simultaneously affects two independent dimensions:

| Doctrine | Check Bonus | Safety Axis Shift | Reward Axis Shift |
|------|:------:|:------:|:------:|
| **Cautious** | −5 | +1 tier (safer) | −1 tier (lower reward) |
| **Standard** | ±0 | unchanged | unchanged |
| **Aggressive** | +5 | −1 tier (more dangerous) | +1 tier (higher reward) |

The **Safety Axis** affects the Casualty Rate calculation (consult the casualty table using the shifted outcome tier).
The **Reward Axis** affects the mission reward multiplier (consult the reward table using the shifted outcome tier).

```
Example: Base outcome is "Success", Aggressive Doctrine
→ Safety treated as "Marginal Success" (base 35% Casualty Rate)
→ Reward treated as "Critical Success" (×1.5 multiplier)
→ The Director gets more loot — but at the cost of higher casualty risk.
```

### 1.6 Probability Reference (For GM Balancing)

> **Formula**: `Success Rate (Success and above) = 101 − (DC − Modifier)`, floor 1%, cap 100%. `Including Marginal Success = min(100, Success Rate + 10)` (Marginal Success threshold is DC−10).

| Configuration | Total Modifier | vs. Moderate DC 70 (Success and above / incl. Marginal) | vs. Hard DC 85 (Success and above / incl. Marginal) |
|------|:----:|:----------------------------:|:----------------------------:|
| Rookie team (1 Regular, 1 Trainee, Equipment 3, Standard) | +24 | 55% / 65% | 40% / 50% |
| Standard team (2 Regular, Equipment 5, Standard) | +35 | 66% / 76% | 51% / 61% |
| Veteran team (2 Veteran, Equipment 6, Standard) | +48 | 79% / 89% | 64% / 74% |
| Elite team (2 Elite, Equipment 8, Aggressive) | +69 | 100% / 100% | 85% / 95% |
| Legendary team (2 Legendary, Equipment 10, Standard) | +80 | 100% / 100% | 96% / 100% |

> **Design Principle**: The Standard configuration against Moderate difficulty has a Success Rate (Success and above) of about 66%, or about 76% including Marginal — fitting the "reasonable challenge." Suicidal (DC 115) against a Legendary team: Success Rate = 101 − (115 − 80) = **66%** (76% incl. Marginal), still high-risk but not necessarily fatal; the GM should avoid letting low-Modifier teams attempt Suicidal missions (success rate may drop to 1%).

---

## Chapter Two: Casualty System (Complete GM Edition)

### 2.1 Casualty Check Process

```
Step 1: Determine the Safety Axis outcome tier → look up the Base Casualty Rate
Step 2: Apply casualty rate modifiers → calculate the Final Casualty Rate
Step 3: Roll a d100 Casualty Check for each dispatched Explorer
Step 4: Triggered casualties roll for injury severity (d100)
```

### 2.2 Base Casualty Rate (by Safety Axis)

| Safety Axis Outcome | Base Casualty Rate (per Explorer) |
|------------|:--------------------:|
| Critical Success | 0% (no Casualty Check) |
| Success | 15% |
| Marginal Success | 35% |
| Failure | 60% |
| Catastrophe | 90% |

### 2.3 Casualty Rate Modifiers (additive, floor 5%)

| Modifier Source | Effect |
|----------|:---:|
| Each point of Equipment (EQP) | −2% |
| Cautious Doctrine | −10% |
| Aggressive Doctrine | +10% |
| Equipped with Medical Kit (Equipment) | −5% |
| Equipped with Almond Water (1 unit per person) | −5% |
| Medical Specialty Explorer in the team | −5% |
| Encountering a Threat Level 3+ Entity | +10% |
| Mission is "Search and Rescue" and exceeded the time window | +15% |

```
Example: Safety Axis "Marginal Success" (base 35%), Equipment 5 (−10%), Standard Doctrine, equipped with Medical Kit (−5%)
→ Final Casualty Rate = 35% − 10% − 5% = 20%
Each Explorer rolls d100; ≤ 15 triggers a casualty.
```

### 2.4 Injury Severity Table

| d100 | Injury Tier | Recovery Time | Game Effect |
|:---:|----------|:------:|----------|
| 01–40 | **Light Wound (LW)** | 1 Turn | Next mission personal bonus −5 |
| 41–70 | **Moderate Wound (MW)** | 3 Turns | Cannot be dispatched during this period |
| 71–90 | **Severe Wound (SW)** | 6 Turns | Cannot be dispatched. Roll d100 ≤ 30 to permanently reduce Experience tier by 1 |
| 91–100 | **Killed in Action (KIA)** | Permanent | Triggers bereavement pay (per Contract), Reputation event, team Stress |

### 2.5 Missing-in-Action System

On a mission Catastrophe, 20% of death results become "Missing in Action (MIA)" instead of confirmed death.

**Missing-in-Action Handling Options**:
| Action | Effect | Cost |
|------|------|------|
| **Dispatch Search and Rescue** | Generates a new Search and Rescue mission | Manpower, budget, time pressure (see 2.6) |
| **Abandon Search and Rescue** | — | Reputation −3, whole team Stress +1, affects future recruitment |
| **Wait (do not dispatch)** | At each month-start, roll d100; ≤ 5 means they return on their own (carrying basic Intel) | Time cost |

### 2.6 Search and Rescue Mission Rules

| Days Missing | DC Modifier | Survival Rate |
|:------:|:-----:|:---:|
| 1–3 days | Normal DC | 90% |
| 4–7 days | DC +10 | 60% |
| 8–14 days | DC +20 | 30% |
| 15+ days | DC +30 | 5% |

**Clue System**: Based on Intel Tier, initial clue count = Intelligence (INT) ÷ 2 (rounded down, max 3 clues). Each clue reduces the Search and Rescue DC by 10.

**Chain Effects of Abandoning Search and Rescue**: Reputation −3, whole-team Psychological Check (d100 ≥ 50 means Stress +1), additional bereavement pay, long-term low morale for the missing Explorer's team.

### 2.7 Total Party Wipe Rules

Trigger conditions (any one met):
- Mission "Catastrophe" + ≥ 50% of team dead or missing
- Mission "Catastrophe" + no Elite-or-above Explorer in the team
- Boss-class Entity encounter and mission Failure

Consequences:
- Reputation −5 (stackable)
- Triggers an "Investigation Committee" event (consumes 1 month action, forced internal review)
- All on-roster Explorers drop one level in psychological state
- All equipment carried on the mission is lost

### 2.8 Bereavement Pay

| Explorer Rank | Bereavement Pay |
|:--------:|:---:|
| Trainee | 40 Budget |
| Regular | 80 Budget |
| Veteran | 150 Budget |
| Elite | 300 Budget |
| Legendary | 500 Budget + Reputation −3 |

---

### 2.9 Entity Attacks and On-the-Spot Injury Resolution

This game does not use traditional Hit Points (HP). The "damage" dealt by Entities is represented through Casualty Checks. When an exploration team is attacked by an Entity during a mission, apply the following rules:

**Entity Attack Casualty Check**: When encountering an Entity and coming under attack, determine the Base Attack Casualty Rate based on the Entity's Threat Level; after Equipment and medical adjustments, each attacked Explorer independently rolls a d100:

| Entity Threat Level (TL) | Base Attack Casualty Rate |
|:--:|:--:|
| TL1 | 10% |
| TL2 | 20% |
| TL3 | 35% |
| TL4 | 40% |
| TL5 | 60% |

Modifiers are the same as in 2.3 (each point of Equipment (EQP) −2%, Cautious −10%, Medical Kit −5%, Almond Water −5%, Medical Specialty −5%; encountering TL3+ Entity +10%).

**On-the-Spot Injury (Immediate Severe Wound)**: Those who roll into the injury table's 71–90 (Severe Wound) or 91–100 (Death) are immediately incapacitated — unable to continue actions for this mission; the remaining team members decide whether to evacuate or continue. The severely wounded recover for 6 Turns per 2.4, and face the risk of a d100 ≤ 30 permanent tier reduction.

**Team Action Options**: After an on-the-spot severe wound occurs, the Director may (via comms) order: ① Evacuate (whole-team evacuation Check) or ② Stay and continue (remaining members suffer +10% Casualty Rate on the next attack). This choice is the classic "leave your teammate behind?" dilemma.

### 2.10 Unified Status Effects Table (GM Edition)

| Status (Abbr.) | Source | Trigger / Recovery Check | Effect |
|----------|------|--------------|------|
| **Poison (PSN)** | Toxic Moth scale powder, gas spread event | Poisoned on exposure; 1 unit Almond Water cures (high-capacity Almond Water jug +10% to resist) | Personal mission bonus −5, Stress +1 per mission phase |
| **Burning (BRN)** | Flame attack, nest dust explosion | Burns on trigger; auto-extinguishes after d3 Turns (fireproof Equipment −1 Turn) | Encounter / combat-related Checks −5 |
| **Mental Trauma (TRM-S)** | Mental attack event, Partygoer temptation (failed Will Contest), the Hollow | Suffered on failed contest; recovers after mission based on psychological state | Stress +1–+3, personal bonus −5–−10 |
| **Slow (SLW)** | Gravity anomaly, environmental obstacle | Takes effect on entering anomalous zone; cleared after leaving | Evacuation DC +5, encounter escape rate −10% |
| **Environmental Damage (ENV)** | Level 3 electrical station, sudden temperature shift, radiation zone | Triggers once every 10 minutes if unprotected (personal bonus −3); stops once corresponding protective suit worn (radiation suit / thermal sleeping bag) | Continuously weakens personal performance |
| **Darkness (DRK)** | Darkness Descends event, all light sources extinguished | Takes effect when all light sources extinguished; cleared after light restored | All vision-dependent Equipment ineffective, Smilers Threat Level +1 |
| **Existence Erosion (EXI)** | The Hollow | See 2.11 | See 2.11 |

### 2.11 Presence Rules (GM Edition)

**Presence (EXI)** is a hidden value for each Explorer, starting at 10, recorded on the Explorer Character Sheet.

- **Erosion**: When encountering "the Hollow," randomly reduce 1 Explorer's Presence by −1 every 10 minutes
- **Erasure Handling**: Those whose Presence reaches zero vanish from everyone's memory. The GM should privately remove that Explorer from the roster, and in subsequent play plant details like "an empty bunk" or "unclaimed Equipment" so players gradually realize someone is gone — but the other Explorers do not remember them
- **Liquid Silence**: Each drink permanently reduces Presence by −1 (risks manifest after 3+ cumulative uses)
- **Emotional Anchoring**: One carrying a beloved memento (SPC-05) gains a one-time +20 contest bonus (the memento shatters after use)

---

## Chapter Three: The Backrooms Entity Bestiary

> ▶ The Backrooms Entity data (Threat Level TL1–5, complete data for 10 Entities, attack casualty rates, encounter trigger quick-reference) is collected in the standalone bestiary **assets/怪物圖鑑.md**; please consult it separately.

---

## Chapter Four: Worldbuilding and Level Index

### 4.1 What Is the Backrooms?

**The Backrooms** is "the flip side of reality" — a dimension composed of infinitely repeating indoor spaces. It exists within the cracks of reality; when people "no-clip" out of reality in the wrong place, they "clip" into the Backrooms.

### 4.2 The Five Laws of the Backrooms

1. **Non-Euclidean Space**: Space does not obey linear geometry. Walking the same corridor twice may lead to entirely different places.
2. **Spacetime Anomaly**: The flow of time is unstable. A day may feel like a week, and vice versa.
3. **No-Signal Law**: Radio, Wi-Fi, and satellite signals are unreliable or nonexistent in the Backrooms. Cross-Level communication is an extremely rare technology.
4. **Isolated Generation**: The Backrooms generates landscapes based on the entrant's psychological state and memories. This explains why different people may see different Backrooms.
5. **Resource Scarcity**: Food, water, and light sources do not naturally generate in the Backrooms (Almond Water being one of the few exceptions). All resources must be brought in from the outside.

### 4.3 Key Level Directory

| # | Level Name | Threat Level | Role and Game Application |
|---|----------|:------:|--------------|
| **L0** | The Lobby | Class 1 | **Tutorial Level**. Yellowed wallpaper, buzzing fluorescent lights, endless stretching rooms. Entities are rare, with environmental threats dominating. Suitable for players to learn the basic mission flow. |
| **L1** | The Hub | Class 0 | **Player Base**. Location of M.E.G.'s primary outpost. This is the player's "safe zone" — returning here means the mission is over. Trade, recruitment, and rest all take place here. |
| **L2** | Pipe Dreams | Class 2 | **The first truly dangerous area**. Maze-like narrow pipes, high-temperature steam, Clumps' territory. Narrow spaces limit equipment effectiveness. |
| **L3** | Electrical Station | Class 3 | **High-Voltage Crisis**. Filled with exposed wires and buzzing transformers. The environment itself deals damage. Suitable for designing "timed missions." |
| **L4** | Abandoned Office | Class 2 | **Psychological Horror Scene**. Seemingly normal but gradually distorting office spaces. Habitat of Toxic Moths. Suitable for designing "trust crisis" storylines. |
| **L5** | Terror Hotel | Class 3 | **Rule-Based Horror**. Opulent but deadly hotel, nest of Death Moths. Has hidden "hotel rules" — breaking a rule triggers an encounter. |
| **L6** | Lights Out | Class 4 | **Extreme Trust Test**. A completely pitch-black Level, the primary habitat of Smilers. All vision-dependent equipment is ineffective. Communication range is drastically reduced. |
| **L7** | Thalassophobia | Class 4 | **Resource Squeeze**. Boundless waters, with only isolated platforms to stand on. Supply consumption is doubled. The core stage of Campaign "The Rift." |
| **L8** | Cave System | Class 2/4 | **Classic Exploration**. Vast underground cave network, growing more dangerous the deeper you go. Suitable for designing multi-layered exploration missions. |
| **L23** | Hall of Mirrors (original) | Class 3 | **Self-Reflection Theme**. Endless mirror maze, each mirror potentially reflecting a different version of yourself. "What if you had chosen differently" — the player's past decisions are presented visually. |
| **L99** | The Archive (original) | Class 1/5 | **Intel Acquisition**. A vast room piled high with documents. Safe on the surface (Class 1), but its depths hide knowledge that should not be read (Class 5). The core stage of Campaigns "The Call From the Deep" and "The Final Assignment." |

### 4.4 Backrooms Resources

| Resource | Use | Acquisition | Rarity |
|------|------|----------|:---:|
| **Almond Water** | Nutritional supplement, detoxification, mental sedation, low-tier Entity repellent | Fixed supply at the Level 1 Outpost (+3 units per month), randomly found on certain Levels | Common |
| **Royal Ration** | High-energy food, essential for long-term missions | Produced only in specific rooms on Level 5. Very low yield | Rare |
| **Liquid Silence** | After drinking, temporarily lowers "Presence" for a short time, making it harder for Entities to detect you | Can be found in hidden corners of a few Levels. Side effect: a permanent slight decrease in Presence | Very Rare |

---

## Chapter Five: Faction System

### 5.1 Relationship Meter

Faction relationships use a scale of −100 to +100:

| Relationship Value Range | Relationship Tier | Effect |
|:--------:|:------:|------|
| +81 ~ +100 | **Ally** | May borrow Elite Explorers, unlock exclusive missions, receive military support in a crisis |
| +51 ~ +80 | **Friendly** | 20% trade discount, intel sharing, priority mission assignment |
| +21 ~ +50 | **Amiable** | 10% trade discount, occasional intel provision |
| −20 ~ +20 | **Neutral** | Normal interaction |
| −21 ~ −50 | **Cold** | Trade prices raised 20%, refuses cooperative missions |
| −51 ~ −80 | **Hostile** | Trade blocked, may sabotage missions |
| −81 ~ −100 | **Sworn Enemy** | Actively attacks your Explorers, sends assassins, full confrontation |

### 5.2 The Four Factions

#### Faction One: M.E.G. (Major Explorer Group)

- **Relationship**: Initial +30 (cooperative)
- **Role**: Your superior / largest cooperation partner
- **History**: The largest organized force in the Backrooms, founded in Year B.Y. 1 by three of the first clippers
- **Goal**: Map the complete Backrooms, search for exits, protect wanderers
- **Leader**: The Overseer Committee (a three-person decision group)
- **Outpost**: The "Main Base" on Level 1 (population ~5000)

**Relationship Change Triggers**:
| Action | Relationship Change |
|------|:------:|
| Complete an M.E.G. commission mission | +5 |
| Exceed M.E.G. mission expectations (Critical Success) | +10 |
| Refuse an M.E.G. mission | −5 |
| Harm M.E.G. personnel | −20 (may trigger investigation) |
| Conduct unauthorized activities in M.E.G. territory | −10 |
| Cooperate with M.E.G.'s hostile factions | −15 |

#### Faction Two: BNTG (Backrooms Nonprofit Trade Group)

- **Relationship**: Initial +10 (neutral leaning friendly)
- **Role**: Primary trade partner
- **History**: Composed of merchants who established trade routes between various Levels
- **Goal**: Monopolize Backrooms trade, accumulate wealth and resources
- **Leader**: The "Board" — seven of the largest traders
- **Outpost**: The "Market District" on Level 1

**Relationship Change Triggers**:
| Action | Relationship Change |
|------|:------:|
| Sustained trade (spend at least 100 budget per month) | +3/month |
| Transport supplies for BNTG (supply transport mission) | +5 |
| Monopolize a certain resource | −10 (after warning −20) |
| Provide exclusive intel | +10 |
| Sabotage BNTG trade routes | −30 |

#### Faction Three: Independent Outposts

- **Relationship**: Initial ±0 (neutral)
- **Role**: A scattered network of allies. Each outpost is an independent entity, but they share their view of the Bureau
- **History**: Communities self-built by survivors unwilling to join large organizations
- **Goal**: Survival and autonomy
- **Outposts**: The "Sunlight Sanctuary" on Level 4, the "Cave Camp" on Level 8, the "Transformer Community" on Level 3

**Relationship Change Triggers**:
| Action | Relationship Change |
|------|:------:|
| Assist outpost defense | +10 |
| Provide medical support | +8 |
| Plunder or exploit outpost resources | −25 (permanent) |
| Complete missions for an outpost | +5 |
| Outpost member dies during a mission | −10 |

#### Faction Four: Crimson Order — original hostile faction

- **Relationship**: Initial −30 (Nervous)
- **Role**: Ideological enemy
- **History**: Composed of an elite group who believe that "exits open only to those who prove their worth." They show no mercy to the weak.
- **Goal**: Control all Levels leading to potential "exits," eliminate the "unqualified"
- **Leader**: The "Chief Adjudicator" — identity unknown, always wearing a red mask
- **Outpost**: A secret fortress deep within Level 6 "Lights Out"

**Relationship Change Triggers**:
| Action | Relationship Change |
|------|:------:|
| Operate on the same Level (encounter) | −5 (each time) |
| Complete a Crimson Order objective first | −15 |
| Rescue wanderers abandoned by the Crimson Order | −10 |
| Repel a Crimson Order attack | +5 (you won, but the relationship does not improve) |
| Actively attack a Crimson Order outpost | −30 (triggers retaliation) |

> GM Note: The Crimson Order's relationship can only be negative, topping out at −20 ("cold but not actively attacking"). They are not a party to diplomacy — they are one of the prices you must bear.

---

## Chapter Six: Full Structure of the Five Campaigns

### Campaign One: The Rookie Director (Levels 1–3)

**Core Theme**: Prove yourself
**Emotional Ending**: The death of the first Explorer — the player personally handles the death notification

| Act | Content |
|------|------|
| **Act One: Inauguration** | The player arrives, handles the first routine mission (patrol / supply transport). Familiarize with the basic loop. |
| **Act Two: Stress Test** | Unexpected complications arise — mission requirements exceed current capability. Learn to weigh trade-offs. |
| **Act Three: The First Loss** | During a medium-difficulty mission, Intel Bias leads to an unexpected encounter — the first Explorer dies. The player must handle the aftermath. |
| **Wrap-Up** | Write the death notification, handle team morale. At Level 3, a lead to The Rift is triggered. |

**Mission List (6)**:
1. S1.1 — Routine Patrol (L1, Very Easy DC 40, tutorial mission)
2. S1.2 — Supply Transport (L1→L0, Easy DC 55)
3. S1.3 — Missing Person Report (L2, Medium DC 70 — the first real challenge)
4. S1.4 — Resource Recovery (L2, Medium DC 75 — first use of the intel system)
5. S1.5 — Emergency Medical Transport (L1, Easy DC 60 — but timed pressure)
6. S1.6 — Anomaly Signal (L3, Hard DC 85 — campaign climax. The first death occurs here)

**Transition to Campaign Two**: In S1.6, anomalous energy readings are discovered on Level 3 — this is the first sign of "The Rift."

### Campaign Two: The Rift (Levels 4–7)

**Core Theme**: Face the unknown
**Emotional Ending**: Three routes to choose from (Destroy / Stabilize / Study), each with different costs

| Act | Content |
|------|------|
| **Act One: Anomaly Spread** | "Rifts" — regions where physical laws collapse — appear simultaneously across multiple Levels. Daily missions become unstable. |
| **Act Two: Investigate the Truth** | Dispatch a reconnaissance team deep into the source of the Rift. Discover the Rift is connected to L7 "Thalassophobia." |
| **Act Three: The Decisive Choice** | The player chooses among three options — (A) Destroy the Rift (military action, may trigger explosive breakdown), (B) Stabilize the Rift (long-term engineering, resource-intensive but safe), (C) Study the Rift (scientific route, may discover major secrets but may also worsen the situation) |
| **Wrap-Up** | Each choice has different costs and rewards. The Rift incident gives the Bureau valuable experience — but also makes the player doubt for the first time: what exactly is the nature of the Backrooms? |

**Mission List (6)**:
1. S2.1 — Rift Reconnaissance (L4, Easy DC 60 — discover the anomaly)
2. S2.2 — Outpost Defense (L1, Medium DC 75 — the Rift spreads to the base)
3. S2.3 — Abyssal Probe (L7, Hard DC 90 — first entry into the deep-sea Level)
4. S2.4 — Route A/B/C Choice Mission (DC 85–100, depending on the route)
5. S2.5 — Resource Defense War (various Levels, Medium DC 75 — the Rift causes resource loss)
6. S2.6 — Rift Core (deepest part of L7, Extreme DC 105 — campaign climax)

**Transition to Campaign Three**: Crimson Order markings are found in the Rift's wreckage — what are they doing with the Rift?

### Campaign Three: Faction War (Levels 8–11)

**Core Theme**: Choose a side
**Emotional Ending**: The player must decide: war, negotiation, or sabotage from the shadows?

| Act | Content |
|------|------|
| **Act One: Border Invasion** | The Crimson Order begins encroaching on the Bureau's jurisdiction Levels. The player must respond. |
| **Act Two: The Front Lines Unfold** | Regardless of which route is chosen, the Bureau is forced to take a side in a larger conflict. |
| **Act Three: The Key Battle** | A decisive confrontation. The player's choice (war / negotiation / sabotage) leads to completely different endings. |

**The Three Strategies and Their Mission Lines**:

| Strategy | Route | Advantage | Cost |
|------|------|------|------|
| **Total War** | 6 military missions | Ultimately destroys 60% of the Crimson Order's combat strength | High Casualty Rate, massive resource consumption, other factions may distance themselves |
| **Diplomatic Negotiation** | 4 diplomatic + 2 support missions | Ceasefire agreement, may convert some Crimson Order members | Concessions (relinquish partial Level control), internal dissatisfaction |
| **Covert Sabotage** | 5 covert operation missions | Weaken the Crimson Order without triggering full-scale war | If exposed — enemies on two fronts |

**Transition to Campaign Four**: Regardless of the ending, the player will find data about "The Unifier" in the Crimson Order's archives — some ancient existence is awakening in the depths.

### Campaign Four: The Call From the Deep (Levels 12–15)

**Core Theme**: Uncover the truth
**Emotional Ending**: You have found something that may be an "exit" — but what is the cost of opening it?

| Act | Content |
|------|------|
| **Act One: The Signal Source** | Multiple Levels simultaneously receive the same low-frequency signal. Source: deeper within L99 "The Archive." |
| **Act Two: The Archive's Secret** | Ancient records are found in the Archive — "The Unifier" is an existence that crosses dimensions; it is both a threat and a "key." |
| **Act Three: The Threshold** | The player finds the resting place of "The Unifier." Opening the passage to it means potentially triggering an irrecoverable event. |

**Decision Framework**:
- **Open**: Triggers a Boss-tier encounter; on success, unlocks the "Deep Backrooms" — may contain exit clues.
- **Seal**: Protect the existing safety, but never know the answer.
- **Study**: Invest massive resources into remote research, slowly acquiring knowledge without taking direct risk.

**Transition to Campaign Five**: Regardless of the choice, the Bureau has been changed forever. The player will know — the Backrooms may have an exit. Or, it may not.

### Campaign Five: The Final Assignment (Levels 16–20)

**Core Theme**: Endgame choice
**Emotional Ending**: Three completely different endings

| Ending | Trigger Condition | Final Scene |
|------|----------|----------|
| **Legacy** | Bureau is large in scale, high in Reputation | The player retires, passing the Director's seat to a successor they have trained. Final scene: watching the successor sign his/her first mission order. |
| **Dissolution** | Casualties too high, resources depleted | The Bureau is disbanded. The player must find places for all remaining Explorers — the final roll call. Final scene: turning off the light in the office. |
| **Walk In Personally** | Specific conditions (player's Guilt value reaches a critical point, or specific storyline clues) | The player removes the Director's uniform, puts on exploration gear, and personally "clips" into the Backrooms — to do the one thing only he/she can do. Final scene: a letter to the successor left on the desk. |

---

## Chapter Seven: GM Operation Guide

### 7.1 The GM's Core Role

You are the unity of three identities:
1. **Superior**: Assign missions, set deadlines, apply pressure — but not unreasonably.
2. **Intel Officer**: Manage information asymmetry. You always know more than the players, but disclose selectively.
3. **Fate**: When the dice fall, you are responsible for turning numbers into weighty narrative.

### 7.2 Core Hosting Principles

**Principle One: "Yes, and… but at a cost"**
Whatever the player wants to do, try to say "yes." Then add "but that means…." Every choice has a ripple effect.

```
Player: "I want to send two teams to run two hard missions at the same time."
GM: "Sure. But that means all your Elite Explorers are on the front line — if something happens to both at once, you have no backup."
```

**Principle Two: You Are Not a Monster, You Are Fate**
The GM does not side with the Entities. You side with "consequences." When an Explorer dies, do not gloat — describe the death with weight. Every death is part of the story.

**Principle Three: Information Asymmetry Is a Design Feature**
Players should never know everything. Intel Bias is not a bug; it is the core fun of this game. Do not feel bored just because a player bought "perfect intel" — the cost of perfect intel (500 budget) is precisely part of the strategy.

**Principle Four: Consequences Take Priority Over Plot**
Player choice > dice result > your preset plot. If the player makes a stunning decision that makes your planned plot impossible — embrace it. The best stories come from the unexpected.

### 7.3 Mission Pool Management

Each month, provide the player with 3–5 optional missions. Recommended ratio:

| Mission Type | Ratio | Description |
|----------|:--:|------|
| Reconnaissance | 20% | Maintain intel inflow |
| Supply / Resource | 30% | Maintain resource loop |
| Search & Rescue / Diplomacy | 25% | Advance the plot |
| Combat / Crisis | 25% | Create tension |

**"Expiry" Mechanic**: Missions do not exist forever. The GM periodically announces that certain missions have expired due to time running out (search-and-rescue window closed, client withdrew, etc.), forcing the player to trade off between "what to do" and "what not to do."
### 7.4 Pacing: The Four-Week Monthly Cycle

Break each Game Month into four "beats":

| Week | Beat | What the GM Does |
|:--:|------|------------|
| Week 1 | **Briefing** | Present the mission list and intel. Make the players feel the pressure—limited resources, choices must be made |
| Week 2 | **Execution** | Mission Checks, reveal results. This is the climax of rolling dice and narration |
| Week 3 | **Response** | Players deal with the consequences—wounded, missing, equipment depletion. Time for emotional settling |
| Week 4 | **Settlement** | Budget settlement, monthly event triggers, story advancement. Set up for next month |

**Three-tier dramatic event pacing**:
- **Monthly**: at least 1 small event (a random event card drawn during a mission, an NPC dialogue segment)
- **Per season (3 turns)**: at least 1 medium event (faction relationship shift, unexpected discovery)
- **Per campaign (10–15 turns)**: 1 large event (major story turning point)

### 7.5 Emotional Tone Control

The sense of safety and the sense of anxiety form a spectrum. Move the spectrum across different stages:

| Stage | Spectrum Position | Approach |
|------|:------:|------|
| Mission Briefing Stage | Moderate safety | Make information clear but with gaps. "You know enough—but you know you don't know enough" |
| Dispatch Stage | Moderate anxiety | Limit options, highlight the cost. "You can send three people—but only two sets of good gear" |
| Execution Stage | High anxiety | The pause before the roll, the suspense of Intel Bias |
| Result Stage | Release | Reveal the result, let the emotion land. Don't rush to the next mission |
| R&R Stage | Brief tranquility | Small slices of base life, dialogue between Explorers. Build up for the next bout of anxiety |

### 7.6 Special Tips for Solo Mode

- **Make "loneliness" a theme**: Solo players have no other players to discuss with or share responsibility. Use this—give the office scenes a sense of loneliness
- **NPC Explorers need personality**: The solo player's only social counterpart is the NPC you play. Give each Explorer a distinct voice and personality
- **"The Director's Personal Time"**: Every 3–5 turns, insert a short scene—an old photo the Director finds while organizing files in the office, notes left by the previous Director, drinking Almond Water alone late at night while gazing out the window at the endless yellow corridors
- **Don't let numbers drown the story**: Solo players must handle all management details, easily falling into a spreadsheet mindset. Regularly pull them back through narration

### 7.7 Emergency Handling

**Scenario 1: Player Decision Paralysis**
- Symptom: Prolonged hesitation when facing mission choices
- Handling: Introduce time pressure. "Commander on the line—he needs your decision within five minutes." Use in-game pressure to mirror the player's paralysis

**Scenario 2: Recovery After Total Party Wipe**
- Provide a "safety net" mechanism—M.E.G. can lend 2 Regular Explorers (cost: M.E.G. gets mission priority for the next 6 months)
- Trigger a "volunteer" event—an independent Outpost may have Explorers willing to join (cost: obligation to that Outpost)
- Don't let the game end—let rebuilding become a story

**Scenario 3: Faction Relationship Collapse**
- If relations with all factions drop below −50: trigger the "isolation" story line
- The player must rely on themselves—no external support, no trade, no intel sharing
- This is not a punishment, it's another kind of play experience. You can design dedicated events for a "lone-wolf Bureau"

### 7.8 Hidden Information Management

**Things you should never tell the player directly**:
1. The actual DC (only give a range)
2. The result of the Bias Die
3. The exact location and count of Entities (unless perfect intel)
4. The specific script of future events

**Three-layer information disclosure method**:
1. **Layer 1**: What everyone knows (common sense—"L2's pipe maze may have Clumps")
2. **Layer 2**: What intel can reveal ("Based on recent reconnaissance, Clump activity in L2's north zone has increased 30%")
3. **Layer 3**: What only experience reveals ("That Clump's echo frequency is different from ordinary ones—it may have absorbed something")

---

### 7.9 Director's Personal Values (Superior Relationship Value and Guilt Value)

The player rulebook sections 3.6 and 3.7 define two Director personal values; the GM operates them per the following rules:

**Superior Relationship Value (SUP)** (initial 0, −20 to +20):
- At monthly settlement, if the player has met their Superior's "favor conditions" → SUP +3; otherwise −2
- SUP ≥ +10: At the start of each month, grant the player +50 Budget, or 1 free basic intel (choose one)
- SUP ≤ −10: Each month, assign 1 additional mandatory mission (failure to complete results in Reputation −2)

**Guilt Value (GLT)** (initial 0):
- Each mission "Catastrophe" or Explorer "death (KIA)" → GLT +1; errors related to "an evacuation order not issued" grant an extra +1
- GLT ≥ 5 is one of the trigger conditions for Ending C "personally enter The Backrooms"
- The higher the GLT, the greater the narrative intensity of the "Director's Nightmare" event (9.1 d100=60)

---

## Chapter Eight: Mission Generation Framework

### 8.1 Standard Mission Template

```
Mission ID: [Campaign Abbreviation]-[Number]
Mission Name: [Concise and to the point]
Mission Type: Reconnaissance / Supply Run / Search and Rescue / Resource Recovery / Entity Hunt / Diplomatic Mission / Emergency Evacuation
Priority: Routine / Important / Urgent
Target Level: [Level N]
Actual DC: [Value]

──── Briefing ────
[1-2 paragraphs of mission background description, written as natural prose]
Client: [M.E.G. / BNTG / Independent Outpost / Bureau-led]

──── Objectives ────
Primary Objective: [Must be completed for the mission to count as a success]
Secondary Objective: [Completing grants bonus rewards]
Hidden Objective: [A hidden discovery that only triggers on a Critical Success]

──── Known Threats ────
[List threat information based on the player's Intel Tier]
Environmental Threats:
Entity Threats:
Special Conditions:

──── Rewards ────
Base Reward: [Gained on success]
Bonus Reward: [Gained on a Critical Success]

──── Complicating Factors (GM's Option) ────
[1-2 factors that may complicate the mission, triggered during the mission as the situation warrants]
```

### 8.2 Random Mission Generator (d20 Quick Generation)

**Step 1: Basic Skeleton**
| d20 | Mission Type | d20 | Target Level | d20 | Actual DC |
|:--:|----------|:--:|----------|:--:|:------:|
| 1-4 | Reconnaissance | 1-5 | L0–L1 | 1-5 | 40–55 |
| 5-8 | Supply Run | 6-10 | L2–L3 | 6-10 | 60–70 |
| 9-12 | Resource Recovery | 11-14 | L4–L5 | 11-15 | 75–85 |
| 13-15 | Search and Rescue | 15-17 | L6–L7 | 16-18 | 90–100 |
| 16-17 | Diplomatic Mission | 18 | L8 | 19-20 | 100+ |
| 18-19 | Entity Hunt | 19 | L23 (Hall of Mirrors) | | |
| 20 | Emergency Evacuation | 20 | L99 (The Archive) | | |

**Step 2: Add Details (roll d20 again)**
| d20 | Complicating Factor |
|:--:|----------|
| 1-3 | Time Limit (must be completed within X turns) |
| 4-6 | Weather / Environmental Anomaly |
| 7-9 | Competitor (another faction is running a similar mission) |
| 10-12 | Moral Dilemma (mission goal conflicts with ethics) |
| 13-15 | Unexpected Ally (encounter a friendly NPC during the mission) |
| 16-18 | Dual Objective (the client concealed the real mission purpose) |
| 19-20 | Combined Factor (roll twice more, merge) |

**Step 3: Set Rewards (auto-match the reward table based on mission type)**

### 8.3 Plot Twist Design Guide

Five types of twists and their best placement timing:

| Twist Type | Best Timing | Example |
|----------|----------|------|
| **Reversal** | After mission success | The mission succeeded—but what they brought back isn't what they thought |
| **Revelation** | When Intel Bias triggers | The DC is unexpectedly high—because this isn't the Level they thought it was |
| **Sacrifice** | Retreat phase | During evacuation, someone must stay behind |
| **Betrayal** | Mid-campaign | A veteran Explorer turns out to be a Crimson Order sleeper agent |
| **Hope** | After a string of failures | At the lowest point, receive an unknown signal from the depths. Possibly an exit |

---

## Chapter Nine: Random Event Tables

### 9.1 Mid-Mission Events (d100)

#### 🟢 Good Things (01–25)

| d100 | Event | Effect |
|:---:|------|------|
| 01 | Shortcut Found | Mission DC −10 |
| 02–03 | Abandoned Supply Crate | Gain 1 random piece of Equipment |
| 04–05 | Friendly Faceling | Provides direction guidance, Intel Accuracy +1 tier |
| 06–07 | Almond Water Spring | d6+2 units of Almond Water |
| 08–09 | Notes Left by a Predecessor | Permanent DC −5 for that Level |
| 10–11 | Unexpected Ally | Encounter a friendly exploration team from another faction, TEB +5 |
| 12–13 | Moment of Inspiration | One Explorer in this mission gains a one-time skill bonus |
| 14–15 | Perfect Hiding Spot | Encounter trigger rate −20% |
| 16–17 | Team Bond | Whole team Stress −1 |
| 18–19 | Sense of Home | Safety Axis result upgraded one level |
| 20–21 | Reunion with an Old Acquaintance | Encounter a recruitable wanderer (random experience level) |
| 22–23 | Guiding Light | Marginal Success → Success |
| 24 | Short-term Safe Zone | May take one free rest mid-mission (Stress −1, recover minor wounds) |
| 25 | Backrooms' Gift | Gain one random rare item (GM's choice) |

#### 🔴 Bad Things (26–60)

| d100 | Event | Effect |
|:---:|------|------|
| 26 | Route Collapse | Mission DC +10 |
| 27–28 | Communication Blackout | Cannot order retreat; Director loses real-time control |
| 29–30 | Almond Water Leak | Lose 1d3 units of Almond Water |
| 31–32 | Mental Attack | Random 1 Explorer Stress +2 |
| 33–34 | Team Separation | 2 Explorers temporarily leave the group (DC −5 to regroup, otherwise each makes an independent Casualty Check) |
| 35–36 | Level Shift | Evacuation DC +15 |
| 37–38 | Trap | Auto-triggers one encounter |
| 39–40 | Illusion Maze | Explorer Intelligence Contest (d100 ≥ 50); loser's personal modifier −10 |
| 41–42 | Equipment Malfunction | One random piece of Equipment fails |
| 43–44 | Malicious Mark | Someone is tracking you—encounter trigger rate for subsequent encounters +10% |
| 45–46 | Party Invitation | Traces of Partygoers appear nearby—next encounter must be Partygoers |
| 47–48 | Memory Loss | The Hollow is nearby. All Stress +1 |
| 49–50 | Water Contamination | Remaining Almond Water's effect halved |
| 51 | Marauders | Encounter human enemies (Crimson Order scouts or independent marauders) |
| 52–53 | Gas Spread | Must evacuate within d6 turns, otherwise whole team is poisoned |
| 54 | Gravity Anomaly | Movement difficult, Mission DC +5 |
| 55 | Silence Falls | All sound vanishes. Communication fails, encounter perception −20% |
| 56–57 | Darkness Falls | All light sources extinguished. Smilers TL → 4 |
| 58 | Time Loop | Repeat the same route 1d3 times, consuming resources each time |
| 59 | Flesh Wall | The Level begins to "grow"—Evacuation DC +20. This is a residual effect of the rift |
| 60 | Director's Nightmare | The player sees a vision—images of all their dead Explorers. All Stress +1, player gains roleplay clues |

#### 🟡 Unexpected Discoveries (61–85)

| d100 | Event | Effect |
|:---:|------|------|
| 61–62 | Former Director's Log | Discover records left by a predecessor (or another Bureau). Gain story clues |
| 63–64 | Abandoned Lab | Gain 1 Experimental Equipment (random) |
| 65–66 | Entity Corpse | Something more dangerous is here—threat awareness for that Level updated |
| 67–68 | Mural | Visual record of Backrooms history. Permanent Intel +1 |
| 69–70 | Another Bureau | Discover traces of an entirely unknown Bureau branch—Main Story trigger |
| 71–72 | Lost Colony | A forgotten human settlement. May contain recruitable survivors |
| 73–74 | Portal | A brief portal to another random Level |
| 75–76 | Entity Nest | Permanent DC −10 for subsequent missions against that Entity type |
| 77–78 | Anomalous Energy Source | Can be used as a one-time "DC −20" item, or handed to the R&D Lab for +50% Tech Research progress |
| 79–80 | Parallel Reality | Explorer briefly sees "another self"—a version that made different choices. Roleplay material |
| 81–82 | Backrooms Ecology Record | Encounter Contest DC −5 against all known Entities |
| 83–84 | Entity Weakness | Permanent DC −15 for subsequent missions against that Entity type |
| 85 | The Way Home? | Discover clues to a suspected "exit"—Campaign Four Main Story trigger |

#### ⚪ Environmental Changes (86–100)

| d100 | Event | Effect |
|:---:|------|------|
| 86 | Level Pulse | Mission DC fluctuates ±d20 (decided by roll) |
| 87 | Flickering Lights | Briefly visible→briefly all dark→loop. Encounter rate fluctuates |
| 88 | Spatial Stretch | Movement distance doubled, resource consumption increased |
| 89 | Sudden Temperature Shift | Extreme heat or cold. DC +5 if no corresponding protection |
| 90 | Humidity Saturation | Electronic device failure chance +20% |
| 91 | Humming Intensifies | The fluorescent buzz amplifies to an unbearable level. All make a Contest (d100 ≥ 50); failure → Stress +1 |
| 92 | Silent Domain | All sound vanishes. Cannot communicate verbally |
| 93 | Color Drain | Vision gradually turns grayscale. Reconnaissance-related Checks −10 |
| 94 | Maze Reconfiguration | Terrain rearranges behind you. Cannot return the same way. Evacuation DC +10 |
| 95 | Abnormal Time Flow | Subjective and objective time desync—mission may be longer or shorter than expected |
| 96 | Gravity Fluctuation | Intermittent weightlessness/overweight. Movement- and combat-related Checks −5 |
| 97 | Electromagnetic Storm | All electronic devices fail (including communication) |
| 98 | Fog Inrush | Visibility drops to a few meters. Encounter trigger rate +10% |
| 99 | Level "Breathing" | Walls move. Floor moves. Everything slowly lives. All Stress +2 |
| 100 | Boundary Dissolution | Reality itself begins to destabilize. All make a Will Contest (d100 ≥ 60); losers suffer random mental Trauma |

### 9.2 Monthly Random Events (d20)

Roll once at the start of each month (before mission selection):

| d20 | Event | Effect |
|:--:|------|------|
| 1 | **Superior Inspection** | M.E.G. commander personally inspects. Next month must complete at least 1 M.E.G. mission, otherwise Reputation −5 |
| 2 | **Resource Shortage** | This month, all Equipment prices in the trade catalog rise by 30% |
| 3 | **Explorers' Collective Petition** | Triggered by high Casualty Rate (3+ casualties in the last 5 missions). Must choose between "improve safety" and "maintain efficiency" |
| 4 | **Intel Leak** | This month all intel purchases cost double (someone sold intel to competitors) |
| 5 | **Volunteer Wave** | This month recruitment cost halved, recruitment +2 |
| 6 | **Faction Festival** | BNTG holds its annual trade festival. All transactions 20% discount |
| 7 | **Level Unusually Calm** | This month all mission DC −10 (a rare "good day" in the Backrooms—but veteran Explorers will say it's a bad omen) |
| 8 | **Crimson Order Activity Increased** | This month encounter chance with Crimson Order doubles |
| 9 | **Former Director's Relics** | Discover secret documents left by the previous Director. Gain 1 hidden intel + roleplay material |
| 10 | **Rookie Training Class Graduates** | Gain 2 free Trainee Explorers |
| 11 | **Unexpected Donation** | Anonymous donation of 200 Budget (source unknown—possibly a trap, possibly a benefactor) |
| 12 | **Equipment Malfunction** | This month 1 random Equipment needs repair (cost 30% of original price) |
| 13 | **Diplomatic Crisis** | Random 1 faction relationship −10 (misunderstanding or accidental skirmish) |
| 14 | **Almond Water Bumper Harvest** | This month +5 units of Almond Water |
| 15 | **Rumors Abound** | New rumors about the "exit" spread through the Backrooms. All Explorers recruited this month start with "Nervous" mental state |
| 16 | **Valuable Order** | BNTG proposes a special trade—high reward but with specific risks |
| 17 | **Health Crisis** | Disease outbreak within the Outpost. Spend 30 Budget or 1 Explorer cannot be dispatched this month |
| 18 | **Cross-Level Storm** | This month all cross-Level missions DC +10 |
| 19 | **Legend Returns** | A retired Legendary Explorer briefly visits. Provides one free guidance (choose 1 Explorer to immediately advance 1 rank) |
| 20 | **Day of Fate** | Roll this table twice; both events occur simultaneously |
### 9.3 Faction Relationship Events (d20 × Independent Roll per Faction)

Once per month, optional to use. Roll once for each major faction:

| d20 | Event | Effect on Relationship |
|:--:|------|:----------:|
| 1 | Serious Misunderstanding | −15 |
| 2-4 | Minor Friction | −5 |
| 5-8 | Nothing Happens | 0 |
| 9-12 | Friendly Contact | +3 |
| 13-15 | Mutually Beneficial Opportunity | +5 |
| 16-18 | Unexpected Assistance | +8 |
| 19 | Major Cooperation | +12 |
| 20 | Historic Event | +20 (unlocks exclusive Scenario) |

---

## Appendix A: GM Quick Reference

### A.1 Mission Resolution Flow Card

```
1. Director declares Doctrine (Cautious/Standard/Aggressive)
2. Calculate total modifier (TEB + EQB + DOC + SPC)
3. GM declares estimated DC range (including bias)
4. Roll d100 + modifier → Mission Check value
5. Determine five-tier outcome by actual DC
6. Resolve rewards (Mission type × Reward Axis level)
7. Each Explorer rolls casualty die independently (d100 ≤ final Casualty Rate)
8. Resolve equipment depletion (roll d100 ≤ depletion DC → equipment damaged)
9. Resolve stress changes, intel update
10. GM narrates final result
```

### A.2 DC Quick Reference

> Success Rate = 101 − (DC − Modifier), minimum 1%, maximum 100% (consistent with the formula in §1.6).

| Difficulty | DC | Novice Team (+24) Success Rate | Standard Team (+35) | Elite Team (+69) |
|------|:--:|:----------------:|:----------:|:----------:|
| Trivial | 40 | 85% | 96% | 100% |
| Easy | 55 | 70% | 81% | 100% |
| Moderate | 70 | 55% | 66% | 100% |
| Hard | 85 | 40% | 51% | 85% |
| Very Hard | 100 | 25% | 36% | 70% |
| Suicide-level | 115 | 10% | 21% | 55% |

### A.3 Quick Casualty Rate Calculation

```
Final Casualty Rate = Base Casualty Rate − EQP×2% − Doctrine Adjustment − Equipment Adjustment + Penalty
```
- Base Casualty Rate: Critical Success 0% / Success 15% / Marginal Success 35% / Failure 60% / Catastrophe 90%
- Doctrine: Cautious −10% / Aggressive +10%
- Floor: 5% (even if all modifiers are perfect, the minimum risk of The Backrooms endures)

---

## Appendix B: Complete Terminology Cross-Reference

| Abbr. | Traditional Chinese Full Name | English | Description |
|:---:|-------------|------|------|
| MPW | Manpower | Manpower | Number of deployable Explorers and recruitment capability |
| EQP | Equipment | Equipment | Quality of weapons, armor, tools, and vehicles |
| INT | Intelligence | Intelligence | Knowledge reserves regarding The Backrooms |
| REP | Reputation | Reputation | Influence within The Backrooms community |
| BGT | Monthly Budget | Budget | Funds available per month |
| MSC | Mission Cap | Mission Cap | Number of Missions that can be executed simultaneously |
| EDR | Equipment Degradation Rate | Equipment Degradation Rate | Degree of equipment consumption after a Mission |
| IAC | Intel Accuracy | Intel Accuracy | Accuracy of risk assessment |
| EL | Experience Level | Experience Level | Explorer levels 1–5 |
| SPC | Specialty | Specialty | Combat/Recon/Medical/Engineering/Negotiation |
| MS | Mental State | Mental State | Stable/Nervous/Trauma/Breakdown |
| STR | Stress | Stress | 0–10 psychological stress |
| CNT | Contract | Contract | Employment terms |
| ST | Status | Status | On Standby/On Mission/Wounded/Missing/Dead |
| DC | Difficulty Class | Difficulty Class | Mission success threshold |
| TEB | Team Experience Bonus | Team Experience Bonus | Sum of all dispatched Explorers' experience values |
| EQB | Equipment Bonus | Equipment Bonus | EQP × 2 |
| DOC | Doctrine Correction | Doctrine Correction | Cautious −5/Standard ±0/Aggressive +5 |
| BE | Basic Equipment | Basic Equipment | General-purpose |
| CE | Combat Equipment | Combat Equipment | For combat |
| SE | Survival Equipment | Survival Equipment | Extreme environments |
| TE | Tech Equipment | Tech Equipment | High-tech |
| EE | Experimental Equipment | Experimental Equipment | Unstable, high bonus |
| TL | Threat Level | Threat Level | Entity danger level 1–5 |
| KIA | Killed In Action | Killed In Action | Confirmed dead |
| MIA | Missing In Action | Missing In Action | Unknown status |
| LW | Light Wound | Light Wound | Recovers in 1 turn |
| MW | Moderate Wound | Moderate Wound | Recovers in 3 turns |
| SW | Severe Wound | Severe Wound | Recovers in 6 turns |
| M.E.G. | Major Explorer Group | Major Explorer Group | The largest organization in The Backrooms |
| BNTG | Backrooms Trade Group | Backrooms National Trade Group | Trade faction |
| REC | Reconnaissance Mission | Reconnaissance | Exploration-type Mission |
| SPL | Supply Run Mission | Supply Run | Logistics-type Mission |
| SAR | Search and Rescue Mission | Search and Rescue | Rescue-type Mission |
| RRV | Resource Recovery Mission | Resource Recovery | Recovery-type Mission |
| EHT | Entity Hunt Mission | Entity Hunt | Combat-type Mission |
| DPL | Diplomatic Mission | Diplomatic Mission | Negotiation-type Mission |
| EEV | Emergency Evacuation Mission | Emergency Evacuation | Crisis-type Mission |
| EXI | Presence | Existence | The degree of an Explorer's presence in reality and memory |
| SUP | Superior Relation | Superior Relation | Quality of the relationship with the Superior (−20 to +20) |
| GLT | Guilt | Guilt | The Director's accumulated guilt |

---

## Appendix C: Initial Explorer Generation Pool (100 People)

Each Director randomly draws an initial team from the pools below (2 Novices + 2 Veterans + 1 Elite + 1 Special). Roll the corresponding die to determine the specific Explorer; or use the "Random Draw" tab in `空白玩家角色卡.xlsx` for a one-click draw via formula.

### C.1 Novice Explorer Pool (Novice Pool) — Roll d30

| d30 | Name | Gender | Age | Specialty | Background Summary |
|:--:|---|---|---|---|---|
| 1 | Chen Xiaoming | M | 22 | Combat | A young man just graduated from military academy, full of ideals. He thought The Backrooms was just another training ground. |
| 2 | Lin Yuqing | F | 24 | Medical | Former ER nurse, recruited by The Bureau after wandering into The Backrooms. Steady hands. |
| 3 | Zhang Zhigang | M | 28 | Engineering | Former construction worker who discovered in The Backrooms that his intuition for structural anomalies is unusually sharp. |
| 4 | Wang Meiling | F | 21 | Recon | Former track athlete, quiet, fast, and dislikes crowded places—in The Backrooms all of these are advantages. |
| 5 | Huang Guoqiang | M | 25 | Combat | Veteran, a man of few words. There is an unhealed scratch on his arm—he won't say how it got there. |
| 6 | Li Xinjie | F | 23 | Negotiation | Former salesperson. She has persuaded people into everything from insurance to survival odds. Her smile is more soothing than Almond Water. |
| 7 | Liu Jianhong | M | 26 | Engineering | Electronics engineer with a morbid curiosity about the electromagnetic anomalies in The Backrooms. |
| 8 | Zhao Yawen | F | 20 | Recon | Former street photographer with an almost obsessive eye for environmental detail. |
| 9 | Wu Junjie | M | 27 | Medical | Career-changed from veterinarian. He says animal bodies are about the same as human ones—after being attacked by an Entity, roughly the same. |
| 10 | Zhou Sihan | F | 22 | Negotiation | Anthropology student who wandered into The Backrooms during fieldwork. She treats every Mission as "fieldwork." |
| 11 | Sun Zhiyuan | M | 23 | Combat | Former security guard who saved a child on his first entry into The Backrooms. Could never leave after that. |
| 12 | He Yating | F | 22 | Medical | Nursing school intern who learned earlier than her peers how to lie without looking patients in the eye. |
| 13 | Luo Jianwen | M | 26 | Engineering | Plumber/electrician who discovered in The Backrooms that the sounds behind the walls follow a pattern. |
| 14 | Shen Jiarong | F | 21 | Recon | Mountaineering guide with a sixth sense for heights and edges; likes to go where there are no paths. |
| 15 | Gao Weicheng | M | 25 | Combat | Fitness coach whose muscles are faster than his brain. But The Backrooms taught him to follow orders. |
| 16 | Chen Yijun | F | 24 | Negotiation | Broker who specializes in dealing with tenants others don't want to handle. Came in handy in The Backrooms. |
| 17 | Xie Zonghan | M | 27 | Engineering | Network engineer who always feels the lighting frequency in The Backrooms hides a signal. |
| 18 | Lin Xiaoman | F | 20 | Recon | Parkour enthusiast who can squeeze through any gap. Rumor says she's never been caught. |
| 19 | Huang Shihan | F | 23 | Medical | Pharmacist who can tell real from fake Almond Water by its scent at a glance. |
| 20 | Wu Cheng'en | M | 28 | Combat | Retired security captain who led a twenty-person squad. The Backrooms made bringing people home his creed. |
| 21 | Zheng Kaiwen | M | 22 | Engineering | Motorcycle shop apprentice who can fix anything that moves, including himself. |
| 22 | Zhang Yunxuan | F | 25 | Negotiation | Front desk manager who can turn complaints into thanks. In The Backrooms she's the one who negotiates with them. |
| 23 | Yang Mingzhe | M | 24 | Recon | Journalist accustomed to asking too many questions. In The Backrooms, curiosity once cost him a life. |
| 24 | Lü Xiuqin | F | 26 | Medical | Midwife who has delivered two children in The Backrooms; they have never seen the sun. |
| 25 | Zeng Baiyu | M | 21 | Combat | Boxer with an old scar on his left cheek. He says that wasn't a loss, it was tuition. |
| 26 | Hong Wanting | F | 22 | Negotiation | Customer service rep who honed the skill of smiling after being yelled at for an hour. The Backrooms needs that even more. |
| 27 | Lai Junxiong | M | 27 | Engineering | Welder who says some doors in The Backrooms are safer welded shut than opened. |
| 28 | Qiu Meiling | F | 24 | Recon | Courier whose gift for remembering routes became a survival skill in The Backrooms. |
| 29 | Xiao Zhiqiang | M | 23 | Combat | Night-shift guard accustomed to darkness. But he says the darkness of The Backrooms looks back. |
| 30 | Jiang Yizhen | F | 21 | Medical | Intern nurse thrown into The Backrooms right after graduation. She says she hasn't learned to be afraid yet. |

### C.2 Veteran Explorer Pool (Veteran Pool) — Roll d30

| d30 | Name | Gender | Age | Primary Specialty | Secondary Specialty | Background Summary |
|:--:|---|---|---|---|---|---|
| 1 | Zheng Yongkang | M | 34 | Combat | Recon | Former special forces. Spent three years in The Backrooms. His left eye is a prosthetic—with a micro camera hidden inside. |
| 2 | Xu Shuhua | F | 31 | Medical | Negotiation | Former battlefield doctor. Has seen more wounds than most combat Explorers. Can calm anyone down within five minutes. |
| 3 | Yang Zhiming | M | 36 | Engineering | Combat | Trained as a mining engineer, found after spending six months in Level 2's pipe maze. His knowledge of the piping system is unmatched. |
| 4 | Cai Jingyi | F | 29 | Recon | Medical | Once survived two weeks alone in Level 9's blizzard. Became very quiet after returning. |
| 5 | Ye Tianyou | M | 33 | Negotiation | Recon | Former BNTG trade representative. Skilled at negotiation, but The Bureau isn't quite sure where his loyalty lies. |
| 6 | Jian Ruifeng | M | 35 | Combat | Engineering | Heavy weapons specialist. Likes explosions more than most people. But is surprisingly protective of teammates. |
| 7 | Lu Yaqi | F | 30 | Recon | Negotiation | Former investigative journalist. Has an instinct—she can sense "something is off." That instinct has saved her life countless times in The Backrooms. |
| 8 | Dong Jianguo | M | 38 | Engineering | Medical | Former M.E.G. equipment maintenance supervisor. Demoted for "telling superiors too much truth." You picked up a gem. |
| 9 | Fan Xiaowen | F | 32 | Medical | Recon | Psychiatrist. Specializes in PTSD (post-traumatic stress disorder)—she chose to enter The Backrooms to study the limits of the human psyche. Her patients sometimes worry about her. |
| 10 | Peng Zhihao | M | 31 | Negotiation | Combat | Former lawyer. Discovered in The Backrooms that negotiation and litigation use the same skill set. Calm to an unsettling degree. |
| 11 | Mark Chen | M | 33 | Combat | Engineering | Former mercenary who can defuse bombs and build them. He says the two are essentially the same. |
| 12 | Sophia Lin | F | 30 | Medical | Negotiation | Doctors Without Borders, seamlessly switches between the negotiation table and the operating table. |
| 13 | Kenichi Tanaka | M | 35 | Recon | Combat | Former JSDF reconnaissance scout who single-handedly marked an entire area in Level 11. |
| 14 | Claire Wu | F | 31 | Negotiation | Recon | Hostage negotiation expert whose voice can quiet a madman for three seconds. |
| 15 | Robert Zheng | M | 34 | Engineering | Medical | Mine rescue team member who digs people out before saving them. Has three scars on his hands from rubble. |
| 16 | Emily Huang | F | 29 | Recon | Medical | Wilderness survival instructor who can improvise a bandage out of nothing. |
| 17 | Kevin Yang | M | 36 | Combat | Negotiation | Former Blackwater instructor whose backup plan when negotiations break down is faster than anyone's. |
| 18 | Nicole Zhang | F | 32 | Medical | Recon | Combat journalist turned medic, steady with both camera and tourniquet. |
| 19 | David Lee | M | 33 | Engineering | Recon | Bridge engineer who learned in The Backrooms which structures cannot be trusted. |
| 20 | Sarah Hsu | F | 30 | Negotiation | Combat | Security company crisis handler whose principle is to speak before shooting. |
| 21 | "Nightingale" Zhou | F | 31 | Medical | Recon | Real name unknown. She saved an entire squad in Level 4's red-light district without leaving a name. |
| 22 | Frank Ke | M | 37 | Combat | Engineering | Demolition consultant who hates delays. He says rather than go around, blast a path. |
| 23 | Eva Shen | F | 34 | Negotiation | Medical | Refugee camp coordinator who believes everyone has a price worth negotiating—including Entities. |
| 24 | Martin Gao | M | 35 | Engineering | Combat | Oil field safety supervisor accustomed to caging danger. In The Backrooms, that cage is his teammates. |
| 25 | "Raven" Ono | M | 32 | Recon | Engineering | Former communications soldier who can cobble a working radio from scrap. Nickname comes from always being last to withdraw. |
| 26 | Grace Yang | F | 29 | Medical | Engineering | Biomedical engineer who builds prosthetics from parts scavenged in The Backrooms. Patients call her the Restorer. |
| 27 | Leon Cai | M | 38 | Combat | Recon | Former special agent, recalled by The Backrooms after retirement. He says it's an unfinished account. |
| 28 | Vera Fang | F | 33 | Negotiation | Engineering | Procurement manager who can trade scrap metal for scarce supplies. She says The Backrooms is the worst auction house. |
| 29 | "Stone" Wu | M | 36 | Engineering | Negotiation | Silent wall-builder, responsible for half the outpost's reinforcements. Speaks only to negotiate terms. |
| 30 | Diane Lo | F | 30 | Recon | Negotiation | Private detective who specializes in finding disappeared people. The Backrooms keeps her cases forever unsolved. |

### C.3 Elite Explorer Pool (Elite Pool) — Roll d20

| d20 | Name | Gender | Age | Primary Specialty | Secondary Specialty | Background Summary |
|:--:|---|---|---|---|---|---|
| 1 | "Phantom" Rex | M | 41 | Recon | Combat | Real name unknown. Rumor says he can navigate Level 6's total darkness. Has never lost a teammate on a Mission—according to him. |
| 2 | Cassandra Lee | F | 37 | Medical | Negotiation | Developed three first-aid techniques used in The Backrooms. Her hands are long-soaked in Almond Water—her skin is translucent, veins visible beneath. |
| 3 | "Wrench" Thomas | M | 43 | Engineering | Recon | Rumor says he can fix anything with a wrench and a roll of tape—including a radio stomped by an Entity. Always has machine oil on his hands. |
| 4 | Victoria Chen | F | 39 | Negotiation | Medical | Once mediated an impending war between M.E.G. and three independent Factions. The way she speaks makes refusing her feel impossible. |
| 5 | "Bulwark" Jackson | M | 40 | Combat | Engineering | A 130-kilogram giant. Rumor says in one Mission he held a door shut with his back to let the whole team evacuate. The door's imprint is still on his back. |
| 6 | Isabelle Lin | F | 35 | Recon | Negotiation | Linguist. Speaks seven languages—including two "Backrooms languages." She can communicate with certain Entities. Others find it terrifying. |
| 7 | "Ice" Morris | M | 42 | Combat | Recon | Sniper. Rumor says he hit a moving Entity from 800 meters away. Speaks very little. Some say he's killed more Entities than words he's spoken. |
| 8 | Anna Wang | F | 38 | Engineering | Combat | Former M.E.G. Tech Research department chief engineer. Equipment she designed is still used by The Bureau. Left R&D over "ethical differences." |
| 9 | "North Star" Noah | M | 41 | Recon | Negotiation | Legend says he can read direction in Level 7's dense fog. Never gets lost, and never says how. |
| 10 | "Iron Hand" Ivan | M | 43 | Engineering | Combat | Former tank mechanic who can build a makeshift shelter from treads and steel plates. His hands are steadier than a machine. |
| 11 | "Saint Hand" Erin | F | 39 | Medical | Negotiation | Legend says she brought an Explorer who had stopped breathing back to life. She denies it herself. |
| 12 | "Peregrine" Carlos | M | 40 | Combat | Recon | Former special assault soldier whose entry speed outpaces an Entity's reaction. He says slow is death. |
| 13 | "Weaver" Mei | F | 37 | Negotiation | Recon | The hub of an intelligence network; rumor says there's no Backrooms secret she doesn't know, only ones she won't tell. |
| 14 | "Sledge" Oscar | M | 44 | Combat | Engineering | Built like a mountain. Once held a collapsing passage with a steel beam for seven minutes. |
| 15 | "Glimmer" Leah | F | 35 | Medical | Recon | Can perform surgery in total darkness. She says her hands remember the way, no eyes needed. |
| 16 | "Compass" Dimitri | M | 42 | Recon | Engineering | Former Arctic explorer whose navigation instinct is unaffected by The Backrooms' distortion. Teammates call him a human GPS. |
| 17 | "Antidote" Hannah | F | 38 | Medical | Engineering | Toxicologist who cracked the Almond Water variants. She made drinking water safe. |
| 18 | "Shadow" Fade | M | 45 | Combat | Recon | Infiltration specialist never detected—including one Mission he shouldn't have been present at. |
| 19 | "Mediator" Oliver | M | 41 | Negotiation | Medical | Ender of Faction conflicts. He says the real weapon is making both sides feel they won. |
| 20 | "City-Builder" Sonya | F | 36 | Engineering | Negotiation | Outpost architect who can negotiate building materials and draw the blueprints. The walls she built have held back Entity tides. |

### C.4 Special Specialty Explorer Pool (Special Pool) — Roll d20

| d20 | Name | Gender | Age | Rank | Specialty Combination | Special Background |
|:--:|---|---|---|---|---|---|
| 1 | "Prophet" Mira | F | 26 | Veteran | Recon+Recon (Dual Primary Specialties) | Claims to foresee changes in The Backrooms in her dreams. Sometimes she's right—which unsettles everyone. |
| 2 | Albert Zhong | M | 45 | Elite | Medical+Engineering | Former surgeon and machinery enthusiast. The prosthetics he makes work better than the originals. |
| 3 | "Priest" John | M | 52 | Veteran | Negotiation+Medical | Former clergy. Found a new faith in The Backrooms—or rather, faith found him. Can soothe the most broken souls. |
| 4 | Keiko Sato | F | 29 | Veteran | Combat+Negotiation | Former JSDF psychological warfare specialist. Her weapons are words and bullets—used in that order. |
| 5 | "Collector" Gray | M | 33 | Veteran | Engineering+Recon | Encyclopedic knowledge of anomalous items in The Backrooms. His Dormitory is like a small museum. |
| 6 | Natasha Wolfe | F | 36 | Elite | Combat+Medical | Former special forces combat medic. Equally efficient at saving and taking lives. She says the line between the two is finer than you think. |
| 7 | "Kid" Bao | M | 19 | Novice | Recon+Engineering | Born and raised in The Backrooms—yes, that can happen. He has never seen the "normal world." His understanding of The Backrooms is instinctual. |
| 8 | Margaret Shen | F | 48 | Elite | Negotiation+Recon | Former diplomat who brokered a historic trade agreement between M.E.G. and BNTG. Persuaded by you to "do one last time" before retirement. |
| 9 | "Echo" Freeman | M | 31 | Veteran | Recon+Medical | Once disappeared for six months and was declared MIA. Then he walked back to the Outpost—unscathed. He cannot (or will not) explain what happened in those six months. |
| 10 | Luna Martinez | F | 27 | Veteran | Engineering+Negotiation | Former architect. The outpost reinforcement plans she designed are widely adopted within The Bureau. Her blueprints bear strange marks—she calls them "decoration." |
| 11 | "Traveler" Kai | M | 19 | Novice | Recon+Engineering | One of the children raised in The Backrooms, a few years older than Bao. He says the exits are stories made up by adults. |
| 12 | "Ferryman" Old Zhou | M | 55 | Veteran | Negotiation+Medical | Middleman for twenty years in a small settlement at the edge of The Backrooms. He remembers more paths than the maps show. |
| 13 | "Twin Blade" Rena | F | 28 | Elite | Combat+Combat (Dual Primary Specialties) | Dual-wielder, equally accurate with either hand. She asks why choose just one side. |
| 14 | "Perfumer" Vivi | F | 26 | Veteran | Medical+Engineering | Blends substitute Almond Water from Backrooms plants. The formula is classified; the effect rivals the original. |
| 15 | "Shadow" Ajay | M | 30 | Veteran | Recon+Combat | Stealth master who once followed an Entity pack for a whole day undetected. |
| 16 | "Anvil" Marcus | M | 47 | Elite | Engineering+Combat | Former armorer who can forge weapons from ruins. He says what The Backrooms gives, The Backrooms can also take away. |
| 17 | "Storyteller" Eli | M | 33 | Veteran | Negotiation+Recon | Uses stories to lower people's guard. The outpost's children love his Backrooms fairy tales—which are all true. |
| 18 | "Twins" Sisters | F | 25 | Veteran | Medical+Negotiation | Twin sisters, one saves and one soothes. Half as effective apart, unstoppable together. |
| 19 | "Anchor" Old Zheng | M | 50 | Elite | Engineering+Medical | Backrooms veteran who kept leading teams even after breaking three legs. The young ones say with him around, things are steady. |
| 20 | "Subject Zero" Specimen | Unknown | 30 | Veteran | Recon+Medical | Of unknown origin, survived some experiment. He can sense Entities' emotions. Most dare not look him in the eye. |

> Explorers produced by the recruitment system (open recruitment / poaching / discovered during Missions / event-triggered) are all randomly drawn from the corresponding rank's pool above.

## Appendix D: Mission Discovery Result Table

"Discovered During Mission (MDS)" recruitment method: after the Mission Check, roll d20; a natural 18–20 triggers the "Encounter a Wanderer" event, then roll d10 to determine the discovered Explorer:

| d10 | Discovery | Persuasion DC | Notes |
|:--:|------|:------:|------|
| 1–3 | Novice Wanderer | 10 | A lost novice willing to join any organization that provides safety |
| 4–6 | Veteran Wanderer | 14 | An experienced independent wanderer who needs persuading to join |
| 7–8 | Veteran (defector from another Faction) | 16 | An Explorer who fled from another Faction, possibly with unresolved issues |
| 9 | Elite Wanderer | 18 | A powerhouse who has survived alone in The Backrooms for years—convincing them to join requires a compelling reason |
| 10 | Special Individual (GM-determined) | 20 | An Explorer with a unique background, possibly carrying special items or knowledge |

---

> **"Courage is not walking into The Backrooms—courage is sending others into The Backrooms, then sitting here waiting for them to come back."**

> — Founding precept of The Backrooms Administration Bureau, B.Y. 1

> **Final Words for the GM**:
> Behind every number is a decision. Behind every decision is a name.
> When your players fall silent after a Mission ends—staring at the casualty report, not immediately asking "what's the next Mission"—
> that's when you'll know you did it right.
