# Exiles of the Empire TRPG — Player's Handbook

> **Version:** v0.3  
> **Core Resolution:** d100 Roll-Under  
> **Core Question:** The Empire has abandoned you. How much of your faith remains?

---

# Chapter One: Core Rules

## 1.1 Core Resolution Formula

```
Target Number (TN) = Attribute Value × 10 + Skill Bonus + Difficulty Modifier + Environmental Modifier
```

Roll d100 (two ten-sided dice); a result ≤ Target Number (TN) is a success.

> **Target Number (TN) Cap Rule:** The final Target Number (TN) for any test may never exceed **95**. Even if the calculation yields ≥ 95, a roll of 96–00 is still a Critical Failure. This ensures that even a legendary character always has a chance to fail — in the 40k universe, nothing is ever one hundred percent certain.

### Degree of Success (DoS)

| Formula | Meaning |
|------|------|
| **Degree of Success (DoS) = ⌊(Target Number (TN) − Roll) / 10⌋** | Every 10 points exceeded = 1 level of Degree of Success |
| **Degree of Failure (DoF) = ⌊(Roll − Target Number (TN)) / 10⌋** | Every 10 points short = 1 level of Degree of Failure |

### Critical Success and Critical Failure

| Roll | Result | Effect |
|------|------|------|
| **01–05** | Critical Success | Automatic success + maximum Degree of Success (DoS) + additional positive effect |
| **96–00** | Critical Failure | Automatic failure + most severe negative consequence |

---

## 1.2 The Five Attributes

| Attribute | Mortal Meaning | Astartes Meaning | Primary Use |
|------|----------|-------------|----------|
| **Faith (FTH)** | Piety toward the Emperor | The dual oath to Chapter and Emperor | Resist Chaos, trigger miracles, suppress fear |
| **Body (BOD)** | Human physical strength | Transhuman physical presence | Hit Points (HP), melee, withstand damage, toxin resistance |
| **Mind (MND)** | Willpower and reason | Mental steel under hypnotraining | Resist Psychic, solve puzzles, maintain sanity |
| **Tech (TEC)** | Training and experience | Centuries of combat experience | Ballistic Skill, tech operation, tactical judgment |
| **Fate (FAT)** | The Emperor's favor | The Chapter's legendary "not yet your time to die" | Critical rerolls, miracle dodges, dramatic survival |

### Dual-Baseline Attribute Meaning

| Attribute Value | Mortal Meaning | Astartes Meaning |
|--------|----------|-------------|
| 1 | Weaker than average (disabled, elderly) | — |
| 2 | Ordinary person | Severely damaged (multiple organs lost, near death) |
| 3 | Well-trained (soldier, enforcer) | Wounded Space Marine |
| 4 | Elite (Inquisition acolyte, Commissar) | Normal Space Marine |
| 5 | Human limit | Chapter veteran |
| 6 | — | Terminator veteran, Captain-level |
| 7+ | — | Chapter Master, Champion-level |

> **Key Rule:** A mortal's Attribute 5 is roughly equal to an Astartes's Attribute 1 at the physical level. In physical contests between mortals and Astartes, the mortal automatically has Disadvantage. But Faith, Mind, and Fate contests have no such restriction — before the Emperor, souls are equal.

---

## 1.3 Difficulty Ladder

| Difficulty | Target Number (TN) Modifier | Mortal Attribute 3 Success Rate | Astartes Attribute 5 Success Rate |
|------|---------|-------------------|----------------------|
| Trivial | +40 | 70% (TN 70) | 90% (TN 90) |
| Easy | +20 | 50% (TN 50) | 70% (TN 70) |
| Standard | +0 | 30% (TN 30) | 50% (TN 50) |
| Difficult | −20 | 10% (TN 10) | 30% (TN 30) |
| Extreme | −40 | Critical Success only (5%) | 10% (TN 10) |

---

## 1.4 Advantage and Disadvantage

| State | Rule | Success Rate at TN=50 |
|------|------|---------------|
| **Advantage** | Roll d100 twice, take the lower value | 75% |
| **Disadvantage** | Roll d100 twice, take the higher value | 25% |
| Double Advantage / Double Disadvantage | Do not stack | — |
| Advantage + Disadvantage | Cancel out, roll normally | 50% |

**Gain Advantage:** Suitable tools or equipment, spending extra time to prepare (one round), a successful ally Assistance, the Faith ability "Holy Zeal," or GM ruling of narrative plausibility.

**Gain Disadvantage:** Mortal vs. Astartes physical contest (automatic), operating without light in darkness, Hit Points (HP) < 50%, under Fear or Suppression effects, Corruption stage "Tainted" or above (social tests).

---

## 1.5 Skill System (14 Skills)

| # | Skill | Primary Attribute | Secondary Attribute | Typical Use |
|----|------|----------|----------|----------|
| 1 | Athletics | Body | Tech | Climb, swim, run, jump |
| 2 | Weapon Skill | Body | Tech | Close-quarters combat |
| 3 | Endurance | Body | Mind | Resist fatigue, toxins, extreme environments |
| 4 | Awareness | Mind | Tech | Detect ambushes, spot details |
| 5 | Investigation | Mind | Faith | Search for evidence, analyze clues |
| 6 | Lore | Mind | Faith | Imperial history, xenos knowledge, Chapter lore |
| 7 | Medicae | Mind | Tech | Treat wounds, diagnose illness |
| 8 | Psyniscience | Faith | Mind | Sense Warp fluctuations and Psychic traces |
| 9 | Oratory | Faith | Mind | Inspire allies, intimidate foes, recite prayers |
| 10 | Ballistic Skill | Tech | Mind | Ranged shooting |
| 11 | Tech-Use | Tech | Mind | Operate machinery, crack security, repair gear |
| 12 | Stealth | Tech | Body | Move silently, hide, disguise |
| 13 | Command | Fate | Faith | Lead allies, issue tactical orders |
| 14 | Deceive | Fate | Mind | Disguise, lie, impersonate |

### Skill Levels

| Level | Bonus | Mortal Acquisition | Astartes Acquisition |
|------|------|-------------|-----------------|
| Untrained | +0 | Default | Default |
| Trained | +10 | 4 selectable at character creation | 6 selectable at creation (Weapon Skill, Ballistic Skill, Lore natively Trained) |
| Expert | +20 | Requires Trained base + XP spend | Requires Trained base + XP spend |
| Master | +30 | One skill only, GM permission required | Two skills only, GM permission required |

> **Mortal Street Smarts:** At character creation, choose one "Illegal Skill" to start at Expert level (limited to one of Stealth, Deceive, or Tech-Use).

---

## 1.6 Assistance and Group Tests

**Assistance:** An ally makes the same skill test (Attribute × 10 only, no skill required). On success, the primary character gains Advantage.

**Group Test:** The whole team makes the same Attribute test. More than half succeed → team success. The GM adjusts the consequences based on the number of failures.

---

## 1.7 Opposed Tests

Both sides roll d100 and compare Degree of Success (DoS). The higher Degree of Success (DoS) wins.

**Tie Resolution:**
- Physical contest → higher Body wins
- Social contest → higher Fate wins
- Psychic contest → higher Faith wins
- Still tied → defender wins

**Mortal vs. Astartes Physical Contest:** The mortal automatically has Disadvantage. This can be canceled if they have special equipment or environmental Advantage.

---

# Chapter Two: Character Creation

## 2.1 Derived Attributes

| Derived Attribute | Mortal Formula | Astartes Formula |
|----------|---------|-------------|
| **Hit Points (HP)** | Body × 4 + 5 | Body × 8 + 20 |
| **Faith Pool** | Faith × 3 + 5 | Faith × 2 + 10 |
| **Corruption** | Starts at 0, max 100 | Starts at 0, max 100 |
| **Wound Threshold** | Mind × 2 + 3 | Mind × 3 + 10 |
| **Psychic Ward** | Mind + Faith ÷ 2 | Mind × 2 + Faith ÷ 2 |
| **Defense** | Tech ÷ 2 (round up) + Armor | Tech ÷ 2 (round up) + Armor + 1 |
| **Initiative** | d10 + Mind + Tech | d10 + Mind + Tech + 2 |
| **Movement** | 6 + ⌊Body ÷ 2⌋ meters/round (round down) | 8 + Body meters/round (Power Armor +2) |
| **Encumbrance** | Body × 10 + 20 kg | Body × 50 + 100 kg |
| **Fate Points** | Fate Value / per scenario | Fate Value / per scenario |

### Hit Points (HP) Status Effects

| Hit Points (HP) Status | Mortal Effect | Astartes Effect |
|----------|---------|-------------|
| Healthy (>75%) | None | None |
| Light Wounds (50%–75%) | No significant effect | None |
| Heavy Wounds (25%–50%) | Disadvantage on physical tests, Movement −2 | Disadvantage on physical tests |
| Critical (1%–25%) | Cannot act, Body test each round to maintain consciousness | Actions −50%, can keep fighting |
| Dead (≤0) | Medical intervention needed within 1 round | Enters "Last Watch" state |

### Wound Effects

When a single attack's damage **exceeds the Wound Threshold**, a wound effect triggers:

| Degree of Success (DoS) (excess amount) | Mortal Effect | Astartes Effect |
|---------------|---------|-------------|
| Exceeds by 0–4 | **Minor Wound:** Disadvantage next round | None (transhuman resilience) |
| Exceeds by 5–9 | **Moderate Wound:** 1d3 rounds stunned + permanent scar (RP) | **Minor Wound:** Disadvantage next round |
| Exceeds by 10–14 | **Major Wound:** lose limb/organ function (GM adjudicates specifics), HP max −1d4 (permanent) | **Moderate Wound:** 1 round stunned + Armor Machine-Spirit (APM) −1 |
| Exceeds by 15+ | **Lethal Wound:** instant death (mortal) / immediately enters Last Watch (Astartes) | **Major Wound:** lose limb function, HP max −1 (permanent) |

**Treating Wounds:** Moderate and above wounds require a Medicae test (Difficult) + consuming one Medikit. Major Wounds require a Chapter Apothecary or equivalent medical facility.

---

## 2.2 Mode A: Mortal Character Creation (Seven Steps)

### Step 1: Former Profession (d10)

| d10 | Former Profession | Attribute Bonus |
|-----|---------|---------|
| 1 | Hive Laborer | Body +1 |
| 2 | Astra Militarum Veteran | Tech +1 |
| 3 | Ecclesiarchy Acolyte | Faith +1 |
| 4 | Arbites Enforcer | Mind +1 |
| 5 | Merchant Fleet Crew | Fate +1 |
| 6 | Noble Steward | Mind +1 |
| 7 | Tech-Adept Novice | Tech +1 |
| 8 | Medicae Zealot | Body +1 |
| 9 | Hive Gang Member | Fate +1 |
| 10 | Free Choice | Choose own +1 |

### Step 2: Attribute Allocation

**20 points** freely allocated to the five attributes (each 1–5).

### Step 3: Verdict — Your Crime (choose one of seven)

#### Heretic
> *"Spreading unapproved variants of Emperor Worship."*

- Attribute: Faith +1
- Ability: **Know the Heretic's Heart** — Faith test Advantage when identifying heretical acts/items
- Penance: Personally destroy three heretical shrines or relics
- Reward: Faith Pool max +3, social Advantage against Ecclesiarchy institutions

#### Thief
> *"Stealing Inquisition-sealed objects."*

- Attribute: Tech +1
- Ability: **Shadow's Hand** — Advantage on Stealth, conceal, and lockpick tests
- Penance: Return a relic of equal or greater value
- Reward: Gain one "Inquisition Immunity"

#### Deserter
> *"Retreating before the enemy."*

- Attribute: Body +1
- Ability: **Belated Courage** — first Fear test each scenario automatically succeeds
- Penance: Lead the charge in three key battles
- Reward: Advantage on all Fear tests

#### Psyker
> *"Unregistered psychic talent."*

- Attribute: Mind +1
- Ability: **Bounded Flame** — spending 1 Faith when using Psychic lowers Warp risk by one tier
- Psychic: Starting Psi 1–2, choose one minor Psychic power (Telepathy / Telekinesis / Bioluminescence / Precognitive Flash)
- Penance: Complete 5 "Psychic Services"
- Reward: Gain "Controlled Psyker" status, Psychic strength +1 level

#### Traitor
> *"Formerly a rebel logistics officer."*

- Attribute: Mind +1
- Ability: **Traitor's Knowledge** — Mind test Advantage when identifying Chaos symbols and cult structures
- Penance: Kill three mid-tier Chaos Cultists
- Reward: Gain "Infiltration Specialist" status

#### Corrupt Official
> *"Embezzling Imperial tithes."*

- Attribute: Fate +1
- Ability: **Accountant's Eye** — Tech test Advantage when assessing an item's true value
- Penance: Find and turn in resources equal to the crime's value
- Reward: Gain "Resource Requisition Authority"

#### Contaminator
> *"Tier-2 xenos contact."*

- Attribute: Body +1
- Ability: **Contamination Resistance** — Corruption gain −1 when contacting xenos items (minimum 1)
- Penance: Recover three xenos-tech items and hand them to the Inquisition
- Reward: Permanent Corruption gain −2 when using xenos tech (minimum 0)

### Step 4: Red Line

Define an inviolable moral boundary.

- Breaking the Red Line: +5 Corruption + lose 3 Faith
- Holding the Red Line (under extreme pressure): recover 2 Faith

### Step 5: Equipment Ration

| Category | Base | Optional |
|------|------|------|
| Primary Weapon | Autogun + 3 magazines | Lasgun, Shotgun, Hunting Rifle |
| Secondary Weapon | Combat Knife | Pistol |
| Armor | Flak Armor (AR 2) | Carapace Armor (AR 4, 8kg) |
| Tools | Basic Tool Kit | Medikit / Demolition Tools / Auspex (choose one of three) |
| Personal Relic | Emperor Icon or Prayer Scroll | — |
| Personal Item | One "Permitted to Keep" item | Family heirloom, etc. |

**Squad Shared Resources:**
- Medikit ×3 (restores 2d6 HP)
- Holy Water ×5 (purify, 2d4 damage to Warp entities)
- Holy Oil ×5 (bless weapons)
- Flare ×5 (illuminate 30m, 1d6+2 rounds)
- Food and Water ×10 days' supply
- Ammunition: 2 magazines each (extra magazines can be bought from the Quartermaster at 15 Throne Gelt (TG)/mag, or scavenged from the battlefield)

### Step 6: Companion Relationship (d6)

| d6 | Relationship | Effect |
|----|------|------|
| 1 | Acquaintance | Knew each other before capture |
| 2 | Debt | You owe a companion your life (or vice versa) |
| 3 | Suspicion | You suspect one companion's crime |
| 4 | Trust | Mind test TN +5 when in same scene |
| 5 | Rivalry | You are competing for something |
| 6 | Stranger | No special relationship |

### Step 7: Temptation Note (GM distributes privately)

The GM gives each player an identically-appearing note:

| d4 | Note Content |
|----|---------|
| 1 | "Prove a mission failure was a certain companion's fault — their crime is yours, sentence halved" |
| 2 | "One companion has been Chaos-tainted; observe and report" |
| 3 | "The mission's 'true' goal is not the relic — it is to test who will betray" |
| 4 | "Nothing. You are just an ordinary Penitent." |

> The 4th note is the real one — but it looks identical to the first three. Players never know whether a companion received a Temptation Note.

---

## 2.3 Mode B: Astartes Character Creation (Eight Steps)

### Step 1: Chapter and Service History

**Chapter (d10):**

| d10 | Chapter Gene-Line | Attribute Bonus | Gene Flaw |
|-----|-----------|---------|---------|
| 1-2 | Blood Angels | Body +1 | Blood Thirst |
| 3-4 | Raven Guard | Tech +1 | Shadow Wrath |
| 5-6 | Space Wolves | Body +1 | Wolf Blood |
| 7 | Imperial Fists | Mind +1 | Stubborn |
| 8 | Dark Angels | Fate +1 | Secret |
| 9 | Iron Hands | Mind +1 | Cold of Iron |
| 10 | Custom Chapter | Choose own +1 | GM negotiation |

**Service Experience (d6):**

| d6 | Experience | Additional Adjustment |
|----|------|---------|
| 1 | Neophyte (Scout) | Fate +1 |
| 2 | Battleline Brother | Tech +1 |
| 3 | Assault Squad | Body +1 |
| 4 | Devastator Squad | Tech +1 |
| 5 | Librarian Novice | Mind +1 |
| 6 | Chaplain's Aide | Faith +1 |

### Step 2: Attribute Allocation

**25 points** freely allocated to the five attributes (each 2–7).

### Step 3: Brand of Failure (choose one of five)

#### Last Man
- **Lone Wolf:** When acting alone (teammates >50m away), all tests TN +10
- **Redemption:** Ensure at least one battle-brother survives to final extraction
- **Failure:** All battle-brothers dead → permanent −1 Faith

#### Command Disobeyed
- **Traitor's Intuition:** Faith test Advantage when judging whether an order is reasonable
- **Redemption:** Prove this planet should not be destroyed
- **Failure:** If the objection is proven wrong → permanent −2 Faith

#### Shame of the Chapter
- **Belated Stand:** When HP < 25%, one free reroll per battle
- **Redemption:** Hold the line and survive in a hopeless battle
- **Failure:** Permanent armor crack, Defense −1

#### Gene Flaw
- **Controlled Flame:** Can deliberately trigger the flaw, permanent +1 Corruption
- **Redemption:** Control the flaw until extraction
- **Failure:** Flaw harms a battle-brother → permanent +5 Corruption

#### Captain's Doubt
- **Inquisitor:** Extra die roll during Crisis of Faith, pick the preferred result
- **Redemption:** Believe in the Emperor to the end in the ultimate trial
- **Failure:** Doubt proven → permanent +10 Corruption, Faith Pool halved

### Step 4: Vow Priority

Rank the five vows by priority (1 = highest):

1. **Oath to the Emperor**
2. **Oath to the Chapter**
3. **Oath to the Battle-Brothers**
4. **Oath to the Mission**
5. **Oath to the Innocent**

When vows conflict, choose the higher priority. Breaking a vow leaves a "Vow Crack" — using that vow's related Chapter ability adds +1 Corruption. Breaking the same vow three times → that vow is permanently void.

**Specific abilities affected by Vow Cracks:**

| Broken Vow | Affected Chapter Ability (Corruption +1 when used) |
|-----------|--------------------------------|
| Oath to the Emperor | Emperor's Hand, Holy Zeal, Faith tests |
| Oath to the Chapter | Power Armor abilities (Strength Amplification / Auto-Senses), Chapter Tactics |
| Oath to the Battle-Brothers | Protect Brother reaction, Unshakeable Will, Assistance tests |
| Oath to the Mission | Twin Shot, Power Charge, Command actions |
| Oath to the Innocent | Chapter's Wrath, Oratory tests, social tests interacting with civilian NPCs |

### Step 5: Chapter Relic (d6)

| d6 | Relic | Effect |
|----|------|------|
| 1 | Tattered Chapter Banner | Allies within 10m Faith test TN +5 |
| 2 | Fallen Brother's Helm | Speak once in combat (GM decides), +1 Corruption after use |
| 3 | Chapter Holy Oil | Bless weapon: next battle's hit TN +10 |
| 4 | Broken Power Sword | In melee, spend 1 Faith to gain +20 TN |
| 5 | Fragment of Chapter Chronicle | Reading restores 2 Faith (once per scenario) |
| 6 | Purity Seal | Immune to one Chaos temptation (one-time) |

### Step 6: Brother Relationship (d6)

| d6 | Relationship | Combat Bonus |
|----|------|---------|
| 1 | Sworn Brothers | Can take one hit for the other (once per battle) |
| 2 | Mentor & Pupil | When assisting the other, the other gains Advantage |
| 3 | Rivalry | Both gain +2 Initiative in the same battle |
| 4 | Witness | Witnessed your darkest hour |
| 5 | Sole Survivor | Share a secret |
| 6 | Stranger | From a different Chapter or company |

> When the relationship's subject dies: permanent +3 Corruption, Advantage on all tests against the killer ("Vengeance").

### Step 7: Power Armor Status (d6)

| d6 | Status | Defense Bonus | HP Buffer | Negative Effect |
|----|------|---------|---------|---------|
| 1 | Pristine | +8 | 10 | None |
| 2 | Lightly Damaged | +7 | 7 | Left sensor −5 to evasion |
| 3 | Moderately Damaged | +6 | 5 | Unstable climate control |
| 4 | Severely Damaged | +5 | 3 | Stealth Disadvantage, unstable power |
| 5 | Near Failure | +4 | 0 | Life support only 24 hours remaining |

**Power Armor Passive Abilities:** Strength Amplification (Body test Advantage), Fully Sealed (immune to toxin gas/vacuum), Auto-Senses (30m perception not reduced in dark/smoke), Climate Control (immune to natural temperature extremes), Magnetic Lock (weapons cannot be disarmed), Machine-Spirit Link.

### Armor Machine-Spirit (APM) System

Power Armor has 0–10 Armor Machine-Spirit (APM) points, tracking the mental state of the armor's built-in machine-spirit:

| Armor Machine-Spirit (APM) | Status | Effect |
|-----|------|------|
| 10 | Perfect Harmony | All abilities normal, Initiative +1 |
| 7-9 | Minor Discomfort | No negative effect (RP: feel "someone is watching you") |
| 4-6 | **Restless Machine-Spirit** | Auto-Senses 50% failure (roll d6 each round: 1–3 fail), climate fluctuation |
| 2-3 | **Armor Rejection** | Strength Amplification fails, Movement −2, requires Mind test (Standard) each time worn or all armor abilities fail |
| 1 | **Machine-Spirit Fury** | Systems randomly malfunction (GM rolls d6 each round to disable one system) |
| 0 | **Machine-Spirit Silence** | Armor Mitigation (AR) halved (round down), all abilities fail — equivalent to wearing dead metal |

**Armor Machine-Spirit (APM) Changes:**

| Event | Armor Machine-Spirit (APM) Change |
|------|---------|
| Conduct Mechanicus litany after battle ends (if facility/skill available) | +2 (requires Tech test, Standard) |
| Rest in a holy or consecrated place (long rest) | +3 |
| Each time a Critical Hit is taken (armor absorbs) | −1 |
| Wearer's Corruption stage increases | −2 |
| Hit by a Chaos weapon | −1 |
| Successfully complete Chapter ritual (GM discretion) | +1 |
| Wearer experiences Crisis of Faith (win or lose) | −1 |

### Step 8: Gene-Seed Flaw (choose one of six)

| Flaw | Trigger Condition | Trigger Test | Effect | Duration | Control (attempt each round) |
|------|---------|---------|------|------|---------------------|
| **Blood Thirst** | Witness large amounts of blood or HP <25% | Mind (Difficult, TN−20) | Melee damage ×2, cannot distinguish friend from foe, must attack nearest target each round | 1d6 rounds or no target | Spend 1 Faith + Mind (Standard); success suppresses for 1 round |
| **Cold of Iron** | Battle-brother critically wounded (HP <25%) and cannot be rescued | Auto-trigger | Immune to Fear / mental control, combat test +10 TN, cannot socialize | 1d3 hours or rescue brother | Auto-recover after rescuing brother |
| **Shadow Wrath** | Exposed suddenly after Stealth >1 hour | Mind (Standard) | Must return to shadow or attack at Disadvantage, Defense −4; attack Advantage in shadow | Recovers 2 rounds after returning to shadow | Slow adaptation: each round spent in dim light lowers DC by 5 |
| **Wolf Blood** | Warp fluctuation / full moon / 3 consecutive melee rounds | Mind (Difficult, TN−20) | Melee Advantage + damage +1d6, speed +2, cannot use ranged weapons | Battle ends or 1 round without melee | Spend 1 Faith + Mind (Standard) to recover |
| **Imperial Fists Stubborn** | Asked to change tactical plan | Mind (Standard) | Hold original plan → Defense +3 / Faith Advantage; change → all tests Disadvantage | Plan complete / failed / persuaded | Companion Mind test (Difficult, TN−20) to persuade |
| **Dark Angels Secret** | Outsider repeatedly asks about Chapter history | Mind (Standard) | Paranoia: cannot trust outsiders, Awareness test Advantage, attack Advantage against outsiders | Outsider leaves or proves loyalty | Outsider performs a highly convincing action (GM discretion) |

> **"Controlled Flame"** (Brand Four exclusive): Spend one minor action to deliberately trigger the gene flaw, gaining full power. **Cost: permanent +1 Corruption.** When triggering deliberately, may additionally spend Faith to suppress negative effects (such as Blood Thirst's friend-foe confusion).

---

## 2.4 Faith and Corruption

### Faith Pool

| | Mortal | Astartes |
|---|------|---------|
| Formula | Faith × 3 + 5 | Faith × 2 + 10 |
| Typical Value | 14–17 (Faith 3–4) | 16–20 (Faith 3–5) |

### Faith Expenditure

| Ability | Mortal Cost | Astartes Cost | Effect |
|------|---------|-------------|------|
| Seek Guidance | 2 | 3 | GM gives a veiled hint |
| Purge Corruption | 3 | 5 | Lower Corruption by 1 |
| Holy Zeal | 5 | 4 | All tests this round Advantage |
| Emperor's Hand | 8 | 6 | Critical Failure becomes ordinary failure |
| Last Prayer | All | All | Auto-stabilize when critical |

### Faith Recovery

| Method | Mortal | Astartes |
|------|------|---------|
| Complete mission objective | +5 | +3 |
| Save the innocent | +3 | +2 |
| Reject Chaos temptation | +5 | +4 |
| Recite prayer (one round) | +1 | +1 |
| Destroy Chaos item | +3 | +2 |

### Between-Mission Recovery

After each completed mission returning to base (mortals to Carcassonne, Astartes find a safe point):

| Item | Mortal | Astartes |
|------|------|---------|
| **HP Recovery** | Auto-recover to max (basic medical) | Body test (Standard): success → recover 3d10 HP; failure → recover 1d10 HP. Astartes' transhuman physique allows natural healing |
| **Faith Pool Recovery** | Recover 1d6 + Faith value points | Recover 1d3 + Faith value points |
| **Psychic Points** | Full recovery | Full recovery |
| **Permanent Damage** | HP max loss from wounds does not auto-recover (needs special medical) | Same as above |
| **Equipment Resupply** | GM decides new ration based on mission performance and Inquisitor | Can only scavenge ruins or repair existing gear |
| **Corruption** | Does not auto-decrease (needs Purge Corruption Faith spend or special event) | Does not auto-decrease |

### Corruption (0–100)

**Corruption Gain:**

| Source | Mortal | Astartes |
|------|------|---------|
| Contact with Chaos relic | +1~5 | +1~3 |
| Witness Warp manifestation | +3~8 | +2~6 |
| Use xenos tech | +1/time | +1/time |
| Kill innocent (unnecessary) | +2 | No increase |
| Accept Chaos "gift" | +5~15 | +5~15 |
| Long-term in corrupt environment | +1/day | +1/day |

### Corruption Stages

| Stage | Corruption | Mortal Effect | Astartes Effect |
|------|--------|---------|-------------|
| Pure | 0-9 | None | None |
| Dusty | 10-29 | Occasional nightmares | Occasional nightmares |
| Tainted | 30-59 | Minor mutation, social Disadvantage | Restless machine-spirit |
| Fallen | 60-89 | Obvious mutation, Whisper of Chaos, Faith cost ×2 | Armor rejection |
| Lost | 90-99 | Almost unable to resist Chaos | Almost unable to resist Chaos |
| Cursed | 100 | Becomes a Chaos spawn, GM takes over | Becomes a Chaos Space Marine, GM takes over |

### Crisis of Faith

**Trigger:** Faith Value + Corruption Value ≥ 100

1. Player makes a Faith test (Faith × 10 + Oratory bonus)
2. GM makes a Corruption test (Corruption Value ÷ 2 as TN)
3. Judgment:

| Result | Verdict |
|------|------|
| Faith success + Corruption failure | **Faith wins:** Corruption −10, gain "Emperor's Mark" |
| Faith failure + Corruption success | **Corruption wins:** Faith −10, gain "Chaos Mark" (with power) |
| Both succeed | Compare Degree of Success (DoS), higher wins |
| Both fail | No change, next Crisis of Faith TN −5 |

### Faith Depleted — "Night of the Soul"

When the Faith Pool drops to 0, the character enters the **"Night of the Soul"** state:

- **Immediately triggers Crisis of Faith** (ignoring whether Faith + Corruption ≥ 100)
- Character cannot use any Faith ability (including Emperor's Hand, Holy Zeal, etc.)
- All Faith tests against Chaos automatically Disadvantage
- Gains 1 Corruption per day (despair is eroding you)

**Escaping the Night of the Soul:** Requires passing a special "Faith Rekindled" action — perhaps completing a great good deed, accepting a battle-brother's Oratory (Oratory test, Difficult), or witnessing an Emperor's miracle (Emperor's Eye phenomenon). On success, Faith Pool recovers to 25% of the formula value (round up).

> **Astartes Difference:** An Astartes's Night of the Soul is rarer (their faith is more stable), but harder to escape — requiring not just action, but Chapter ritual or a battle-brother's sacrifice.

### Emperor's Mark (d6)

| d6 | Mark | Effect |
|----|------|------|
| 1 | Emperor's Shield | Immune to next Chaos temptation |
| 2 | Emperor's Eye | Sense Chaos corruption within 30m |
| 3 | Emperor's Voice | Once per day, GM gives a truthful answer |
| 4 | Emperor's Hand | Faith Pool max +5 |
| 5 | Emperor's Flame | All damage to Chaos units +1d6 |
| 6 | Emperor's Chosen | Fate value max +1 |

### Chaos Mark (d6)

| d6 | Mark | Power | Cost |
|----|------|------|------|
| 1 | Sight of Chaos | Tracking Chaos Advantage | After use, Mind test or brief madness |
| 2 | Flesh Power | Melee damage +2d4 | Appearance mutation |
| 3 | Warp Whisper | Ask GM one question | +2 Corruption each use |
| 4 | Shadow's Gift | Stealth TN +30 | Uncomfortable in light |
| 5 | Chaos Resilience | HP +10/20 | Healing powers ineffective |
| 6 | Curse Eye | Impose Disadvantage on target (3/scenario) | +1 Corruption when used |

---

## 2.5 Advancement System

### Mortal Milestones

| Trigger | Growth |
|------|------|
| Complete a mission | +1 Attribute point (max 5) |
| Complete penance condition | Penance reward + Fate +1 |
| Win Crisis of Faith | Emperor's Mark |
| Hold the Red Line | Faith +1 |
| Betrayed by companion | Mind +1 |

Mortal single attribute cap: 5, total cap: 30.

### Astartes Milestones

| Trigger | Growth |
|------|------|
| Complete mission objective | +1 Attribute point (max 7) |
| Complete redemption condition | +1 Fate (max 8) |
| Vow trial | Related attribute +1 |
| Recover battle-brother's gene-seed | Gain +1 any attribute (cannot exceed that brother's highest attribute, once only) |
| Ultimate sacrifice | Fate +2 |

Astartes single attribute cap: 7, total cap: 40.

---

# Chapter Three: Combat and Conflict

## 3.1 Round Structure

```
1. Initiative determination: d10 + Mind + Tech (Astartes +2)
2. Character action: 1 Major + 1 Move + 1 Minor + 1 Reaction
3. Environmental effects: Warp phenomena, environmental hazards
4. Round end → return to step 2
```

## 3.2 Action Economy

### Mortal vs. Astartes

| Trait | Mortal | Astartes |
|------|------|---------|
| Speed | 6 + Body÷2 m | 8 + Body m (Power Armor +2) |
| Extra Reaction | None | Minor can convert to second Reaction |
| Heavy Armor Movement | Speed −2 | No slowdown |
| Crossing Obstacles | Tech (Difficult) | Body≥4 auto-success |
| Recover from Prone | Spend half Move | Spend 1 Minor |
| Dual-Wield Attack | Major+Minor (Disadvantage) | Two attacks within Major (no Disadvantage) |

### Major Actions

| Action | Description |
|------|------|
| Attack | One melee or ranged attack |
| Full Attack | Two melee or one aimed ranged (Advantage) |
| Cast Psychic | Use a Psychic ability |
| Use Skill | A skill action requiring focus |
| Ready Action | Set a trigger condition |
| Full Defense | Until next round, attacker has Disadvantage against you, Defense +2 |
| Sprint | Move 2× speed |
| Disengage | Safely leave melee |
| Stabilize | First aid on critical character (Medicae test, Standard) |

### Minor Actions

| Action | Description |
|------|------|
| Reload | Change ammunition |
| Switch Weapon | Stow / draw |
| Use Item | Medikit, injector |
| Stand / Go Prone | Stand up or voluntarily go prone |
| Mark Target | Allies gain TN +5 attacking it |

### Reactions

| Reaction | Trigger | Effect |
|------|------|------|
| Attack of Opportunity | Enemy moves within melee without disengaging | Free melee attack |
| Defense Reaction | When attacked | That attack's TN against you −10 |
| Psychic Counter | Someone casts Psychic within 30m | Opposed test to interrupt |
| Protect Brother | Battle-brother within 5m attacked in melee | Take the damage instead |

### Astartes Exclusive Actions

| Action | Description |
|------|------|
| Twin Shot | Boltgun two shots (different targets within 10m) |
| Power Charge | Charge 2× speed + melee at endpoint (Advantage) |
| Unshakeable Will | Faith reroll when hit by mental/Psychic attack |
| Chapter Tactics | Silent tactical communication within 30m |

---

## 3.3 Attack and Damage

### Attack Test

```
Melee: d100 ≤ Body × 10 + Weapon Skill − Target Defense − Difficulty Modifier
Ranged: d100 ≤ Tech × 10 + Ballistic Skill − Target Defense − Range Modifier
```

### Defense

```
Target Defense = Tech ÷ 2 (round up) + Armor Defense Bonus + Cover Bonus (Astartes +1)
```

### Cover

| Cover | Attacker TN Penalty |
|------|---------------|
| Light Cover | −10 |
| Medium Cover | −20 |
| Heavy Cover | −30 |
| Full Cover | Cannot be aimed at |

### Range Modifier

| Range | TN Modifier |
|------|---------|
| Close (≤ 1/4 range) | +0 |
| Medium (≤ 1/2 range) | −10 |
| Long (≤ range) | −20 |

### Damage Formula

```
Final Damage = Weapon Base Damage + Degree of Success (DoS) × 2 − Target Armor Mitigation (AR) (minimum 1)

Critical Hit (Critical Success 01–05): Maximize damage + Degree of Success (DoS) × 2 − Armor Mitigation (AR)
```

### Damage Types

| Type | Source | Armor Interaction |
|------|------|---------|
| Ballistic | Autogun, Boltgun | Standard Armor Mitigation (AR) |
| Energy | Laser, Plasma, Melta | Carapace −2 |
| Explosive | Grenade, Rocket | Light armor +2 |
| Flame | Flame Thrower | Ignores 2 points of Armor Mitigation (AR) |
| Rending | Chain Sword, Power weapon | −2 vs Armor Mitigation (AR), ignored on Critical Hit |
| Corrosive | Strong acid, Chaos weapon | Permanent −1 Armor Mitigation (AR) per hit |
| Psychic | Psychic attack | Ignores physical Armor Mitigation (AR) |
| Holy | Holy Water, blessed weapon | ×2 vs Chaos creatures |

> **▶ The equipment database (weapons / armor / consumables / prices) is collected separately in `assets/物品圖鑑.md`; this handbook no longer embeds it. Please refer to it directly.**

## 3.5 Death and Dying

### Mortal Dying

HP ≤ 0: Falls prone, roll d20 at end of each round:
- ≥15: Stabilized (HP 0)
- 10–14: Continue rolling next round
- 5–9: HP −1
- 1–4: HP −3
- Natural 1: Instant death

True Death: HP ≤ −(Body + Mind)

### Astartes Last Watch

HP ≤ 0: Enters "Last Watch"
- Does not automatically fall prone
- Only 1 action per round
- HP −2 after each action
- HP ≤ −(Body × 2 + 20) → Suspended Coma

Suspended Coma: Physiological hibernation; only an Apothecary can awaken, can last 1d100+100 years.

---

## 3.6 Status Effects

| Status | Mortal Effect | Astartes Effect | Removal |
|------|---------|-------------|------|
| Bleeding | −1d4 HP per round | −1 HP per round | First aid / Medikit |
| Burning | −1d6 HP per round | −1d3 HP per round | Extinguish / water |
| Poisoned | Body test each round | Immune to most toxins | Antidote |
| Stunned | 1 round unable to act | Only loses Minor action | Round end |
| Suppressed | Half movement, attack Disadvantage | Half movement | Enter full cover |
| Prone | Melee Advantage / Ranged Disadvantage | Same as mortal | Minor to stand |
| Feared | Cannot approach source, attack Disadvantage | Resist with Faith test | Source disappears |
| Confused | 50% unable to act | 30% unable to act | Mind test |
| Immobilized | Completely unable to act | Body test to break free | Break free / expires |

---

> **▶ The equipment database (weapons / armor / consumables / prices) is collected separately in `assets/物品圖鑑.md`; this handbook no longer embeds it. Please refer to it directly.**

## 3.9 Psychic System

### Psychic Strength

| Level | Mortal | Astartes |
|------|------|---------|
| Psi 1 | Talent Awakened | — |
| Psi 2 | Senser | Trainee |
| Psi 3 | Manipulator | Full Librarian |
| Psi 4 | Strong | Senior Librarian |
| Psi 5 | Psychic Master | Chief Librarian |
| Psi 6+ | Alpha-level | — |

### Psychic Use

```
1. Declare Psychic and strength
2. Pay Psychic Points (PP)
3. Roll Psychic test: d100 ≤ Mind×10 + Psi×5
4. vs Psychic Difficulty Class (DC)
5. Success → takes effect, failure → triggers Warp phenomenon
```

### Psychic Points

| Character | Psychic Points (PP) | Recovery |
|------|----|------|
| Mortal Psyker | Mind×2 + Psi×3 | Long rest |
| Astartes Librarian | Mind×3 + Psi×4 | Long rest |

### Warp Risk

| Psi | Trigger (d20) |
|-----|----------|
| 1-2 | ≤2 |
| 3 | ≤5 |
| 4 | ≤8 |
| 5+ | ≤12 |

> **▶ The complete list of common Psychic powers and Librarian-exclusive abilities is collected in `assets/魔法圖鑑.md`. Please refer to it.**

## Appendix A: Probability Quick Reference

| Target Number (TN) | Success Rate | Advantage | Disadvantage |
|----|--------|------|------|
| 10 | 10% | 19% | 1% |
| 20 | 20% | 36% | 4% |
| 30 | 30% | 51% | 9% |
| 40 | 40% | 64% | 16% |
| 50 | 50% | 75% | 25% |
| 60 | 60% | 84% | 36% |
| 70 | 70% | 91% | 49% |
| 80 | 80% | 96% | 64% |
| 90 | 90% | 99% | 81% |

---

## Appendix B: Mortal Character Sheet

```
╔══════════════════════════════════════════════════════════╗
║              Exiles of the Empire TRPG — Mortal Sheet     ║
╠══════════════════════════════════════════════════════════╣
║ Name: ______________  Former: ______________  Crime: ____ ║
╠══════════════════════════════════════════════════════════╣
║ Attributes: Faith[ ] Body[ ] Mind[ ] Tech[ ] Fate[ ]      ║
╠══════════════════════════════════════════════════════════╣
║ HP: ____/____  Faith Pool: ____/____  Corruption: ____/100 ║
║ Wound Threshold: ____  Defense: ____  Initiative: ____  Speed: ____m ║
║ Psychic Ward: ____  Fate Points: ____/____                ║
╠══════════════════════════════════════════════════════════╣
║ Primary: ______________  Damage: ____  Mags: ____/____    ║
║ Secondary: ______________  Damage: ____                   ║
║ Armor: ______________  AR: ____  Defense Bonus: ____      ║
║ Items: ____________________________________________       ║
╠══════════════════════════════════════════════════════════╣
║ Skills (mark U/T/E/M):                                    ║
║ Athletics[ ] Weapon Skill[ ] Endurance[ ] Awareness[ ]    ║
║ Investigation[ ] Lore[ ] Medicae[ ]                       ║
║ Psyniscience[ ] Oratory[ ] Ballistic Skill[ ] Tech-Use[ ] ║
║ Stealth[ ] Command[ ] Deceive[ ]                          ║
╠══════════════════════════════════════════════════════════╣
║ Verdict Ability: __________________  Penance: __________  ║
║ My Red Line: __________________  Companion: ___________   ║
║ Mark: ___________________________________________         ║
╚══════════════════════════════════════════════════════════╝
```

---

## Appendix C: Astartes Character Sheet

```
╔══════════════════════════════════════════════════════════╗
║           Exiles of the Empire TRPG — Astartes Sheet      ║
╠══════════════════════════════════════════════════════════╣
║ Name: ______________  Chapter: ______________  Brand: ___ ║
╠══════════════════════════════════════════════════════════╣
║ Attributes: Faith[ ] Body[ ] Mind[ ] Tech[ ] Fate[ ]      ║
╠══════════════════════════════════════════════════════════╣
║ HP: ____/____(Buffer: ____)  Faith Pool: ____/____        ║
║ Corruption: ____/100  Wound Threshold: ____  Defense: ____║
║ Initiative: ____  Speed: ____m  Psychic Ward: ____  Fate: ║
╠══════════════════════════════════════════════════════════╣
║ Primary: ______________  Damage: ____  Ammo: ____/____    ║
║ Secondary: ______________  Damage: ____                   ║
║ Power Armor: Status____  AR: ____/____/____/____/____     ║
║   Defense____  Armor Machine-Spirit (APM): ____/10        ║
║ Chapter Relic: ______________________________             ║
╠══════════════════════════════════════════════════════════╣
║ Skills (natively Trained: Weapon Skill/Ballistic/Lore):   ║
║ Athletics[ ] Weapon Skill[ ] Endurance[ ] Awareness[ ]    ║
║ Investigation[ ] Lore[ ] Medicae[ ]                       ║
║ Psyniscience[ ] Oratory[ ] Ballistic Skill[ ] Tech-Use[ ] ║
║ Stealth[ ] Command[ ] Deceive[ ]                          ║
╠══════════════════════════════════════════════════════════╣
║ Brand Effect: ______________  Redemption: __________      ║
║ Gene Flaw: ______________  Vow Priority: 1.__2.__3.__4.__ ║
║ Brother Rel: ______________  Mark: ________________       ║
╚══════════════════════════════════════════════════════════╝
```

---

> **Player's Handbook Version: v0.3 | Tabletop Rule Studio**
