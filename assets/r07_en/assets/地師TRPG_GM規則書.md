# Earth Master TRPG — GM Rulebook

> **Version:** v1.0
> **Design Studio:** Tabletop Rules Studio
> **Genre:** Eastern Folk Customs × Tomb-Raiding Adventure × Low-Martial True Qi × Folk Spells
>
> This rulebook contains everything needed to run a game of "Earth Master TRPG." If you only read one book, make it this one.

---

# Part One: Core Rules (same as the Player Rulebook)

## Chapter One: Core Check System

### 1-1 Check Formula

```
Check Result = 2d10 + Attribute Value + Skill Level + Equipment Modifier
Success Condition: Check Result ≥ Difficulty Class (DC)
```

### 1-2 Critical Success and Critical Failure

| Roll Result | Effect |
|:---:|------|
| Double 10 (20) | Critical Success — automatic success, additional positive effect |
| Double 1 (2) | Critical Failure — automatic failure, unexpected negative effect |

### 1-3 Advantage and Disadvantage

| State | Mechanic | Equivalent Modifier |
|------|------|:---:|
| Advantage | Roll 3d10, take the higher two | +3.8 |
| Disadvantage | Roll 3d10, take the lower two | −3.8 |
| Double Disadvantage | Roll 4d10, take the lower two | −5.5 |

### 1-4 2d10 Success Rate Reference

| Modifier | DC 6 | DC 10 | DC 14 | DC 18 | DC 22 | DC 26 | DC 30 |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| +0 | 90% | 64% | 28% | 6% | 1% | 0% | 0% |
| +4 | 100% | 97% | 64% | 28% | 6% | 1% | 0% |
| +8 | 100% | 100% | 94% | 64% | 28% | 6% | 1% |
| +12 | 100% | 100% | 100% | 94% | 64% | 28% | 6% |

### 1-5 Five Attributes

| Attribute | Abbrev | Meaning |
|------|:---:|------|
| Agility (身) | 身 | Dexterity, movement, physical stamina |
| True Qi (氣) | 氣 | Internal cultivation, breath circulation |
| Geomancy (輿) | 輿 | Feng Shui knowledge, tomb layout, trap principles |
| Spirit Sense (靈) | 靈 | Perceiving the supernatural, talisman potency, spirit communication |
| Courage (膽) | 膽 | Willpower, psychological endurance |

Attribute Value Range: 1–10. Character creation gives 25 points, cap 9. 10 can only be gained via leveling.

### 1-6 Derived Attributes

| Derived Attribute | Abbrev | Formula |
|------|:---:|------|
| Health Points (HP) | HP | Agility × 3 + 10 (+ each Heritage talent and growth) |
| Qi Pool (QP) | QP | True Qi × 3 + 5 (+ each Heritage talent and growth) |
| Fear Value | Fear Value | Starts at 0, accumulates dynamically |
| Fear Threshold (FT) | FT | Courage × 2 + 5 |
| Yin-Yang Perception (YY) | YY | 10 + Spirit Sense |
| Putrefaction Resistance (PR) | PR | True Qi + floor(Courage ÷ 2) |
| Defense (DEF) | DEF | Agility + Equipment Defense Modifier + Iron Body Modifier |
| Initiative (INIT) | INIT | Agility + floor(Courage ÷ 2) (fixed value) |

### 1-7 Difficulty Class (DC) Full Ladder

| DC | Difficulty | GM Usage Guide |
|:---:|------|------|
| 6 | Trivial | Occasions where a roll should almost never be required — unless the character is in an extremely unfavorable state |
| 8 | Easy | Beginner-friendly — exploration and social difficulty of Scenario S1 |
| 10 | Simple | Standard exploration — Imperial Mausoleum acupoint location, basic talisman drawing |
| 12 | Slightly Hard | Advanced exploration — main DC range of S2–S4 |
| 14 | Moderate | Core challenge — General's Tomb acupoint location, Evil-Dispelling Talisman, standard combat checks |
| 16 | Moderately High | High difficulty — core scenes of corpse-raising grounds, Black Jiangshi confrontation |
| 18 | Hard | Professional grade — hidden ancient tomb acupoint location, Corpse-Suppressing Talisman, non-putrefied-bone dialogue |
| 20 | Arduous | Expert grade — Hopping Corpse confrontation, S5 altar core |
| 22 | Very Hard | Grandmaster grade — fake tomb discernment, Five-Thunder Talisman drawing |
| 24 | Grandmaster | Legendary difficulty — non-putrefied-bone defense, corpse poison resistance |
| 26 | Legendary | Fame-securing — seal the corpse-raising ground |
| 30 | Nearly Impossible | Legendary feat — GM should very rarely set this difficulty |

### 1-8 Twenty-Five Skill System

| Attribute | Skills |
|------|------|
| Agility (身) | Climb, Dodge, Stealth, Melee Weapon, Throwing |
| True Qi (氣) | Qi Guard Body, Inner Breath Regulation, Qi Sense Detection, Qi External Release, Meridian Penetration |
| Geomancy (輿) | Divide-Gold Fix-Point, Trap Discernment, Tomb Chamber Deciphering, Earth Vein Sensing, Antique Appraisal |
| Spirit Sense (靈) | Talisman Drawing, Yin-Yang Eye, Spirit Summoning, Evil Dispelling, Spirit Communication |
| Courage (膽) | Will Hold, Fear Resistance, Pressure Confrontation, Calm Judgment, Near-Death Struggle |

Skill Level 0–6. Creation cap Lv3, Lv2 unlocks Lv4, Lv6 unlocks Lv5, Lv12 unlocks Lv6.

---

## Chapter Two: Character System (fully included)

This section is completely identical to Chapters Two, Three, and Five of the *Player Rulebook* — it includes the Four Heritages (Orthodox Daoist Transmission / Folk Martial Master / Touch-Gold Clan / Maoshan Disciple) and their complete LV1–15 progression martial art tables, the Four Great Sects and their exclusive abilities (Golden Light Incantation, Xuan Kong Heart Method), the 10-step character creation, the complete 1–15 level growth system tables, martial art level definitions, rest and recovery system, equipment and item list (with weight), and the encumbrance system. The GM needs to be familiar with this content in order to assist players with character creation and game management.

> **Quick Reference:** The GM only needs to read the GM-exclusive content below this section. For player character creation, growth, and equipment details, please refer to the *Player Rulebook*. If there is any inconsistency between the Player Rulebook and this section, the Player Rulebook takes precedence.

---

## Chapter Three: Complete Combat Rules

### 3-1 Combat Flow

#### Turn Order

```
1. Determine Initiative (INIT is a fixed value; the highest acts first)
2. Each round loop:
   a. Players/Enemies act in initiative order
   b. Each character: one Main Action + one Move Action + free actions (unlimited)
   c. Reaction Actions can be used on turns other than your own
3. End of round — status effect resolution
```

#### Initiative Tie Handling

```
INIT tie → higher Agility acts first
Agility tie → higher Courage acts first
Courage tie → act simultaneously (damage resolves simultaneously)
```

### 3-2 Action Economy

| Action Type | Count | Content |
|------|:---:|------|
| **Main Action** | 1 | Attack, use item, draw talisman (combat), perform martial art, open coffin, evil-dispelling ritual |
| **Move Action** | 1 | Move 30 feet. May forgo Main Action for a second move (Double Move) |
| **Reaction Action** | 1/round | Dodge (Cat-Spin Reverse), Qi Guard Body, Attack of Opportunity |
| **Free Action** | Unlimited | Speak, drop items, switch weapons |

### 3-3 Attack and Defense System

#### Attack Check

```
Attack Check = 2d10 + Agility + Martial Art Level (or Melee Weapon skill)
Target DEF = Agility + Equipment Defense Modifier + Iron Body Modifier
Hit Condition: Attack Check ≥ Target DEF
```

#### Monster Defense Reference

| Monster | DEF | Description |
|------|:---:|------|
| Fresh Corpse | 5–8 | Just mutated, limbs stiff |
| White Jiangshi | 12–13 | Body grows white hair, Agility 2–3 + innate hard skin |
| Black Jiangshi | 14–16 | Body turns black, Agility 3–4 + hardened skin |
| Hopping Corpse | 17–18 | Bronze skin iron bone, Agility 5–6 |
| Hopping Corpse · Flying Corpse (variant) | 19–20 | Can fly, Agility 6–7 |
| Non-Putrefied Bone | 22–24 | Millennia-old corpse, Agility 7–8 + corpse body like steel |
| Resentment Spirit (incorporeal) | 14 (only hit by spirit weapons) | No physical form, normal attacks automatically miss |

### 3-4 Damage System

#### Damage Formula

**Physical Damage:**
```
Final Damage = Weapon Base Damage + True Qi Bonus Damage − Target Damage Reduction
```

**Talisman Damage (vs supernatural):**
```
Final Damage = Talisman Base Damage (ignores physical reduction)
```

#### Damage Types

| Type | Description | Valid Targets |
|------|------|------|
| Physical | Normal weapons, unarmed | Living people, creatures (reduced or ineffective vs Jiangshi) |
| True Qi | Palm techniques, martial art bonus | All targets (reduced vs Non-Putrefied Bone) |
| Talisman | Evil-Dispelling Talisman, Five-Thunder Talisman, etc. | Jiangshi, spirits (ineffective vs living people) |
| Spirit Weapon | Peachwood Sword, Coin Sword | Jiangshi, spirits |
| Mental | Resentment Spirit attack | Living people, conscious Jiangshi |
| Environmental | Poison gas, flame, collapse | All targets |

#### Supernatural Damage Matrix (complete)

| Attack | White Jiangshi | Black Jiangshi | Hopping Corpse | Hopping Corpse · Flying Corpse | Non-Putrefied Bone | Resentment Spirit |
|------|:---:|:---:|:---:|:---:|:---:|:---:|
| Normal Weapon | 1d6÷2 | 1d4÷2 | 0 | 0 | 0 | 0 |
| Unarmed | 1d4 | 1d2 | 0 | 0 | 0 | 0 |
| Palm Technique (True Qi) | 1d6 + Martial Art Level | 1d6 + Martial Art Level | 1d4 + Martial Art Level | 1d4 + Martial Art Level | 1 + Martial Art Level | Martial Art Level damage |
| Peachwood Sword | 1d4 | 1d4 | 1d2 | 1d2 | 0 | 1d6 |
| Coin Sword | 1d8+1d4 | 1d8 | 1d6 | 1d6 | 1d4 | 1d4 |
| Century Peachwood Sword | 1d10 | 1d10 | 1d8 | 1d8 | 1d8† | 2d6 |
| Five-Thunder Talisman | 3d8 | 3d8 | 3d8 | 2d8 | 2d8 | 2d8 |
| Dragon-Severing Sword★ | 3d8+3 | 3d8+3 | 3d8+2 | 3d8+1 | 3d8 | 2d8 |

> † The Century Peachwood Sword's damage against Non-Putrefied Bone is treated as **Spirit Weapon damage**, and does not apply physical reduction.
| Evil-Dispelling Talisman | 1d8+weaken | 1d6+weaken | 1d4+repel | 1d4 | 0 | 1d8 |
| Heavenly Master Talisman | ×2 | ×2 | ×2 | ×2 | normal | ×2 |

---

### 3-5 Status Effects (complete list)

#### Physical Status

| Status | Effect | Source | Removal |
|------|------|------|------|
| **Burn** | 1d4 damage per round | Evil-Dispelling Talisman, Coin Sword, Glutinous Rice | Subsides after 3 rounds or healed |
| **Fracture** | Disadvantage on related actions | Heart-Crushing Palm, fall | Bandage DC 14 (non-combat) |
| **Paralysis** | Cannot act for one round | Acupoint-Sealing Hand (1 round) | Auto-recover |
| **Pinned** | Cannot move, attack Disadvantage | Grapple, trap | Contest check to break free |
| **Prone** | Needs to stand to move (costs half move), melee has Advantage against you | Push down, impact | Stand with half move |
| **Knockback** | Pushed 10 feet away | Cloud-Dispersing Palm, Jiangshi charge | — |

#### Poison and Disease

| Status | Effect | Source | Removal |
|------|------|------|------|
| **Putrefaction Infection (Mild)** | −1 HP per hour, PR check DC 12 | White Jiangshi scratch | Glutinous Rice toxin extraction DC 14 / Detox Pill |
| **Putrefaction Infection (Moderate)** | −1 HP per round, PR check DC 16 | Black Jiangshi scratch | Same as above + True Qi suppression |
| **Putrefaction Infection (Severe)** | −2 HP per round, PR check DC 20 | Hopping Corpse scratch | Same as above + Talisman Sect purification (DC 18) |
| **Corpse Qi Erosion** | Fear +1 per round, True Qi recovery −1 | Areas dense with Sha | Leave area or Defile-Breaking Talisman |
| **Poisoning (general)** | 1d6 damage per round | Trap poison needle, poison gas | Detox Pill |

#### Mental Status

| Status | Effect | Source | Removal |
|------|------|------|------|
| **Fear** | Disadvantage on all actions | Fear Value > FT | Move away from fear source, Calming Talisman |
| **Panic** | Forced to flee from fear source | Fear Value > FT × 1.5 | Courage check DC 18 |
| **Breakdown** | Cannot act | Fear Value > FT × 2 | Courage DC 18 per round |
| **Stun** | Cannot act for one round | Pressure, high-rank spirit | Auto-recover |
| **Charm** | Controlled actions | Spirit charm | Will Hold DC 16 |
| **Possession** | Body controlled by spirit | Vengeful ghost possession | Evil Dispelling DC 18 / Talisman purification |
| **Hallucination** | Sees things that don't exist | Resentment Spirit, Sha | Yin-Yang Eye check DC 14 to see through |

#### Positive Status

| Status | Effect | Source | Duration |
|------|------|------|------|
| **Guard Qi Aura** | Damage reduction 2–3 | Innate Aura, Golden Bell Cover | Consumes True Qi per round |
| **Spirit Weapon Blessing** | +1d damage vs supernatural | Consecrated spirit weapon | Permanent |
| **Protective Talisman Blessing** | Blocks one supernatural attack | Protective Talisman | Burned after trigger |
| **Eternal Lamp Guardian** | +1 to supernatural checks | Light Eternal Lamp | Until lamp goes out |
| **Glutinous Rice Defense Line** | Jiangshi entering takes 1d4 burn | Scatter glutinous rice | Until trampled apart |

#### Long-Term Status

| Status | Effect | Duration |
|------|------|------|
| **Fatigue** | −1 to all checks | Until long rest |
| **Yang Qi Depletion** | Temporary HP/QP max −5 | Until deep meditation (1 hour) |
| **Karmic Entanglement** | Probability of supernatural threat doubles | Until atonement completed |
| **Courage Trauma** | Fear Threshold −3 | Until major mental breakthrough completed |

---

### 3-6 Martial Art Combat System (complete 22 techniques)

#### Footwork (6 techniques)

| Martial Art | Heritage | True Qi | Corresponding Skill | Effect |
|------|------|:---:|------|------|
| Eight-Step Toad Chase | Martial Master | 1 | Dodge | Move doubles for one round, wall-kick three steps vertically |
| Gecko Technique | Touch-Gold | 1 | Climb | Free movement on vertical surfaces, lasts Geomancy value rounds |
| Water Skimming | Universal | 2 | Climb | Tread three steps on water surface |
| Sparrowhawk Reverse | Touch-Gold | 1 | Dodge | Reaction when hit: reroll opponent's attack |
| Void-Treading Step | Orthodox Daoist | 3 | Dodge | All attacks against you have Disadvantage this round |
| Distance-Shrinking Art | Orthodox Daoist | 4 | Meridian Penetration | Teleport instantly to a visible location within 60 feet |

#### Palm Techniques (6 techniques)

| Martial Art | Heritage | True Qi | Effect |
|------|------|:---:|------|
| Iron Sand Palm | Martial Master | 1/hit | Adds 1d6 True Qi damage, shatters wood and stone |
| Taiji Force | Orthodox Daoist | 2 | Halves physical damage this round |
| Heart-Crushing Palm | Martial Master | 4 | 2d8 True Qi damage, target Constitution check DC 16 or internal injury |
| Soft Palm | Orthodox Daoist | 2 | 1d6, ignores Iron Body reduction |
| Cloud-Dispersing Palm | Martial Master | 3 | 1d8, knockback 10 feet |
| Stele-Shattering Palm | Martial Master | 5 | 3d6, Non-Putrefied Bone DEF −4 |

#### Finger Techniques (5 techniques)

| Martial Art | Heritage | True Qi | Effect |
|------|------|:---:|------|
| Acupoint-Sealing Hand | Universal | 2 | Target paralyzed 1 round (Constitution contest DC 14) |
| Meridian-Cutting Finger | Orthodox Daoist | 3 | Target Qi Pool −5, martial art use DC +2 |
| Throat-Locking Finger | Martial Master | 3 | Target suffocates, 1d6 damage per round until broken free |
| Acupoint-Sealing Combo | Orthodox Daoist | 4 | Three-hit combo, attacks different acupoints respectively |
| Reverse-Meridian Finger | Martial Master | 4 | Target attacks self or ally next round |

#### Body-Guard Techniques (4 techniques)

| Martial Art | Heritage | True Qi | Effect |
|------|------|:---:|------|
| Qi Guard Body | Universal | 1/round | 1 True Qi = negate 2 damage |
| Innate Aura | Orthodox Daoist | 1/round | Reduction 2 (DEF +2 vs physical) |
| Golden Bell Cover | Martial Master | 2/round | Reduction 3 (DEF +3 vs physical) |
| Indestructible Golden Body | Martial Master LV15 | 5 | Immune to physical damage for one round. Once per battle |

#### Iron Body (passive)

| Martial Art | Heritage | DEF Modifier | Extra Effect |
|------|------|:---:|------|
| Iron Sand Palm · Firm | Martial Master | — | Unarmed damage +1 |
| Iron Cloth Shirt | Martial Master/Touch-Gold | +2 | Blocks blades |
| Iron Arm Technique | Martial Master | +1 | +1 additional DEF when blocking |
| Iron Head Technique | Martial Master | +1 | Headbutt attack 1d6 |
| Vajra Indestructibility | Martial Master LV12 | +3 | Unarmed attacks treated as spirit weapons |
| Rock-Shattering Technique | Martial Master LV15 | +2 | Strength check +4 |

---

### 3-7 Spell / Talisman Combat System

#### Talisman Drawing DC and Effects

| Talisman | Draw DC | True Qi | Material | Effect |
|------|:---:|:---:|------|------|
| Evil-Dispelling Talisman | 14 | 1 | Cinnabar + Yellow Paper | Spirit/Jiangshi 1d8 burn, attack Disadvantage + half move speed 1 round |
| Corpse-Suppressing Talisman | 18 | 3 | Cinnabar + Yellow Paper + True Qi | Holds Jiangshi for hours; fails if torn off by force / soaked |
| Protective Talisman | 18 | 2 | Cinnabar + Yellow Paper | Blocks one supernatural damage |
| Protective Talisman (Enhanced) | 20 | 3 | Cinnabar + Yellow Paper + Black Dog Blood | Blocks two supernatural damages |
| Path-Guiding Talisman | 10 | 1 | Cinnabar + Yellow Paper | Floats toward densest Yin energy, 10 minutes |
| Message Talisman | 10 | 1 | Cinnabar + Yellow Paper ×2 | A pair of talismans, remote communication |
| Defile-Breaking Talisman | 14 | 3 | Cinnabar + Yellow Paper + Glutinous Rice Powder | 20 feet Yin purification, low-rank spirits forcibly dispersed |
| Five-Thunder Talisman | 22 | 4 | Cinnabar + Yellow Paper + True Qi | 3d8 spirit weapon damage, can cleave Jiangshi body surface |

#### High-Rank Spells

| Spell | Check DC | True Qi | Material | Effect |
|------|:---:|:---:|------|------|
| Five-Thunder Palm | 18 | 4 | Five-Thunder Talisman + True Qi | Condenses aura in palm, 3d8 spirit weapon damage |
| Spirit Summoning Rite | 18 | 5 | Spirit-Summoning Banner + deceased's item | Forces dead soul to answer three questions |
| Path-Borrowing Rite | 14 | 3 | Paper Money + Coin Array | Opens Yin-Yang passage for spirit to pass through |
| Medium Invocation / Deity Summoning | 20 | 8 | Incense + Talisman + Body | Possession 10 minutes, casts without material restriction. After end, Courage DC 15 |
| Raise Little Ghost | — | — | — | ⚠️ Forbidden evil art, cannot be used by the orthodox path |

#### Three Talisman-Drawing Modes

| Mode | Condition | Check DC | Time |
|------|------|:---:|------|
| Pre-Drawn Talisman | Safe environment, non-combat | Auto success | 1 minute per talisman |
| Combat Activate Talisman | Use pre-drawn talisman | No check needed | Main Action |
| Urgent Draw Talisman | Draw on-site during combat | Draw DC +4 | Main Action |

### 3-8 Putrefaction Infection Rules (complete process)

#### Infection Trigger

When a character is hit by a Jiangshi claw strike and takes damage, a Putrefaction Infection check is triggered:

```
Putrefaction Contest Check = 2d10 + Putrefaction Resistance (PR) vs Putrefaction DC

Putrefaction DC:
  White Jiangshi scratch: DC 12
  Black Jiangshi scratch: DC 16
  Hopping Corpse scratch: DC 20
  Non-Putrefied Bone scratch: DC 24
```

#### Infection Stages

| Stage | Effect | Progression Condition |
|------|------|------|
| **Incubation** | No obvious symptoms (lasts 1 hour) | — |
| **Mild Infection** | −1 HP per hour | PR check DC 12 per hour, fail to worsen |
| **Moderate Infection** | −1 HP per round, Disadvantage on all actions | PR check DC 16 within 10 minutes, fail to worsen |
| **Severe Infection** | −2 HP per round, cannot act | PR check DC 20 per minute, fail to mutate into Fresh Corpse after death |
| **Corpse Mutation** | Character dies, transforms into Fresh Corpse (NPC) | Irreversible |

#### Treatment Methods

| Method | Effect | Condition |
|------|------|------|
| Glutinous Rice Toxin Extraction | DC −2, consumes 1 jin glutinous rice | Needs to be in incubation or mild stage |
| True Qi Suppression | Prevents worsening (consumes 2 True Qi/round) | Needs continuous consumption until treatment |
| Detox Pill | Mild directly cured, moderate DC −4 | Each pill only valid for one infection |
| Talisman Sect Purification | Severe infection DC 18 treatment | Requires Talisman Sect Earth Master to perform ritual |
| Pure Yang Pill | Mild/moderate infection 1 hour immunity | Cannot cure already-infected |

### 3-9 Complete Coffin-Opening Mechanism

#### Three-Stage Process

**Stage One: Preparation**

| Action | Check | Success Effect |
|------|:---:|------|
| Bind Ink-Line | Trap Discernment DC 10 | Boundary seals coffin, Advantage on initiative check after opening |
| Apply Corpse-Suppressing Talisman | Draw Talisman DC 18 | If corpse mutates, auto-immobilized first round |
| Light Eternal Lamp | — | Supernatural check +1, Yin energy range −10 feet |
| Scatter Glutinous Rice | — | 1d4 burn/round within Jiangshi exit range |

**Stage Two: Open Coffin (roll d6)**

| d6 | Result | GM Handling |
|:---:|------|------|
| 1 | No corpse mutation | Tomb owner rests in peace. Burial goods can be safely taken |
| 2 | Normal remains | Burial goods can be taken. No threat |
| 3 | White Jiangshi | Corpse sits up. Initiative check. If prepared adequately, players go first |
| 4 | Black Jiangshi | Jiangshi has memories from life — willing to converse. Social or combat decided by players |
| 5 | Hopping Corpse | Coffin empty — Hopping Corpse is behind players. Ambush check. Tense scene |
| 6 | Special | No corpse in coffin — letter / spirit weapon / sealing object / spirit tablet with character's name written on it |

**Stage Three: Response**

If corpse mutation is triggered, enter combat. If d6=4 (Black Jiangshi), GM should provide dialogue cues:
- Black Jiangshi may ask players why they came here
- Black Jiangshi may propose conditions ("Bring my deputy general's last letter, and I'll let you leave")
- If players respect the tomb owner, Black Jiangshi may lower hostility or even provide help
- If players speak disrespectfully or attempt theft, combat triggers immediately

### 3-10 Fear System (complete GM version)

#### Trigger Conditions and Values

| Event | Fear Value | Note |
|------|:---:|------|
| Enter ancient tomb (first time) | +1 | Environmental oppression |
| Discover bones | +1 | First encounter |
| Witness Fresh Corpse | +1 | No increase if already seen |
| Witness White Jiangshi | +2 | — |
| Witness Black Jiangshi | +3 | — |
| Witness Hopping Corpse | +4 | — |
| Witness Hopping Corpse · Flying Corpse | +4 | — |
| Witness Non-Putrefied Bone | +5 | — |
| Witness Resentment Spirit appearance | +3 | — |
| Hit by Resentment Spirit mental attack | +2 | Each time |
| Corpse in coffin opens eyes | +3 | One-time |
| Companion heavily wounded and falls | +2 | — |
| Companion death | +5 | — |
| Ghost Wall (lost path) | +2 | Every 10 minutes trapped |
| Tomb Chamber collapse | +3 | — |
| Area dense with Sha | +1/round | — |
| Corpse Qi Erosion | +1/round | Stacks |

#### GM Techniques for Controlling Fear Value

- **Don't let Fear Value stay at 0 long-term** — there should always be a faint sense of oppression in the tomb
- **Let Fear Value slowly subside at safe points (resting in side chambers)** — give players room to breathe
- **When Fear Value approaches the threshold is the moment of greatest dramatic tension** — slow the pace, strengthen environmental description
- **Exceeding the threshold is not game over** — the Disadvantage mechanic lets players still act, just more difficultly
- **Breakdown state should very rarely appear** — this is usually the result of players' consecutive poor decisions, not a GM punishment

---

## Chapter 4: Supernatural Threat Data

### 4-1 Jiangshi Tier System

| Level | Name | CR | HP | DEF | Initiative (INIT) | Movement |
|------|------|:---:|:---:|:---:|:---:|------|
| L0 | Fresh Corpse | 0.5 | 15 | 5–8 | 1–3 | 10 ft (stiff) |
| L1 | White Jiangshi | 2–3 | 30 | 12–13 | 2–4 | 20 ft (hopping) |
| L2 | Black Jiangshi | 4–5 | 50 | 14–16 | 3–5 | 25 ft (stiff walk) |
| L3 | Leaping Jiangshi | 6–7 | 80 | 17–18 | 5–7 | 30 ft (free running) |
| L3v | Leaping Jiangshi · Flying Jiangshi | 8–9 | 65 | 19–20 | 7–8 | 30 ft + flight 40 ft |
| L4 | Unrotting Bone | 10–12 | 120 | 22–24 | 7–9 | 30 ft (fully free) |

### 4-2 Monster Data Index (see the Bestiary)

> **▶ Complete monster data (Jiangshi of all tiers, Resentful Spirits / Vengeful Ghosts, Fox Immortals / Spirit Creatures, Ghost Wall, Corpse-Raising Ground, etc.) can be found in the standalone *Monster Bestiary*.** This book does not repeat-stat the values; it only retains GM staging and roleplaying advice as follows.

#### Fox Immortal / Spirit Creature — GM Roleplaying Advice
- Curiosity of spirit creatures — fascinated by human behavior
- Long-term perspective — unconcerned with timescales of days or months
- Speaking in circles — does not answer directly, enjoys testing human wisdom
- Observant — may have been watching the players for a long time

#### Jiangshi / Resentful Spirit — GM Staging Points
- Progress from "something's off" to "direct threat": first heard, then seen traces, finally encounter the entity itself
- Corpse Qi and Fear Value are the core sources of pressure, accumulating each turn; alleviate with a short rest when necessary
- High-tier threats (Leaping Jiangshi and above) possess intelligence and tactics — they retreat, set ambushes, and exploit hostages; never treat them as mindless monsters

---

### 4-6 Encounter Difficulty Design

#### TTV (Total Threat Value) Formula

```
TTV = Σ (CR × count of each monster) × Environment Factor

Environment Factor:
  Open Space = 0.8
  Standard Tomb Chamber = 1.0
  Narrow Tomb Passage = 1.2 (Jiangshi advantage — cannot dodge)
  Sha-Saturated Zone = 1.5
```

#### Difficulty Reference Table (baseline: 4-person party)

| Avg Player Level | Easy TTV | Medium TTV | Hard TTV | Extreme TTV |
|:---:|:---:|:---:|:---:|:---:|
| 1–3 | 2–6 | 6–10 | 10–14 | 14–18 |
| 4–6 | 6–12 | 12–16 | 16–20 | 20–24 |
| 7–9 | 12–18 | 18–24 | 24–28 | 28–34 |
| 10–12 | 18–24 | 24–30 | 30–36 | 36–42 |
| 13–15 | 24–30 | 30–38 | 38–44 | 44–52 |

#### Party Size Adjustment

```
Adjusted TTV = Baseline TTV × (Player Count ÷ 4)

1 player: × 0.6 (and an NPC companion must be provided)
2 players: × 0.75
3 players: × 0.9
4 players: × 1.0 (baseline)
5 players: × 1.15
```

#### Six Principles of Encounter Construction

1. **Horror Escalation**: First let players feel that something is off → then see the threat → only then confront it directly
2. **Environment as Weapon**: The tomb chamber structure itself is a threat — narrow passages, collapse risk, toxic-gas zones
3. **Non-Combat Options**: Every encounter should have at least one non-combat means of resolution (dialogue, detour, negotiation)
4. **Three-Wave Pacing**: Encounters should appear in waves (exploration → light threat → core threat); do not commit everything at once
5. **Resource Pressure**: Every encounter should consume resources (HP/QP/talisman paper/elixirs), making players tense between encounters
6. **Retreat Is an Option**: Not every encounter must be won. Fleeing is a reasonable strategy; design should leave a way out

---

## Chapter 5: Worldview Setting

### 5-1 Era Background

Early Republican Era (1912–1937): the millennia-old imperial system collapsed and warlords carved up the land. The Earth Masters — special inheritors of Feng Shui geomancy, True Qi martial arts, and folk talisman craft — dwindled rapidly amid the tide of modernization.

### 5-2 Five Laws of the Yin-Yang Realms

| Law | Content |
|------|------|
| **First Law: Obsession Never Dies** | When a person dies with a strong obsession, their soul refuses reincarnation and becomes a lingering spirit |
| **Second Law: Yin Sha Takes Form** | A lingering spirit that remains long in a Yin-saturated place gradually materializes into a Jiangshi |
| **Third Law: Yin and Yang Counteract** | Yang substances (Cinnabar, Peachwood, Glutinous Rice) subdue Yin Sha |
| **Fourth Law: Earth Qi Flows** | Beneath the earth flows the Qi of the Dragon Veins; tomb-site selection affects the earth's Qi |
| **Fifth Law: Human Presence Is Yang Qi** | The breathing and body heat of the living generate human presence; where people gather, Yang Qi is strong and Yin things retreat |

### 5-3 Causes of Jiangshi

| Cause | Probability | Typical Location |
|------|:---:|------|
| Lingering Resentment | 40% | Tomb of the wrongly killed |
| Feng Shui Gathering Sha | 30% | Deliberately sited inauspicious acupoint |
| Artificial Refinement | 20% | Heretic sorcerer's workshop |
| Accidental Trigger | 10% | Robbed tomb |

### 5-4 Four Great Sects

| Sect | Core Heritage | Current Status |
|------|------|------|
| Dragon-Shaker Sect | Judging mountain Dragon-Vein courses; Seek the Dragon & Locate the Acupoint | ~50 members, headquarters in Jiangxi |
| Xuan Kong Sect | Precise Luopan calculation; time-dimensional Feng Shui | ~30 members, headquarters in Fujian |
| Talisman Sect | Talisman exorcism; Sha-suppression and sealing | ~40 members, scattered across Taoist temples |
| Mountain-Mover Sect | Trap-breaking; practical tomb descent | ~20 members (fewest) |

### 5-5 Six Major Factions

| Faction | Attitude | Significance to Players |
|------|------|------|
| **Four Great Sects** | Fellow disciples / fellow practitioners | Belonging, resources, quest sources |
| **Tomb-Robbing Warlord** | Instrumentalized | Client, potential betrayer, Boss |
| **Foreign Expedition** | Curio-seeking / contempt | Competitor, employer, potential ally |
| **Folk Tomb-Robbing Gang** | Reverence | Information source, temporary cooperation |
| **Official Antiquity Institution** | Awkward | Legitimization channel, private cooperation |
| **Ghost Market Merchant** | Normal trade | Source of rare items, information exchange |

### 5-6 Antique Market

| Market | Price | Risk |
|------|:---:|------|
| Underground Antique Dealer | High | Low (identity discreet) |
| Fellow Occultists | Fair | Low (internal trade) |
| Ghost Market | Variable | Extreme (but may acquire Legendary items) |
| Museum | Low (legal) | Medium (origin may be questioned) |
| Foreign Buyer | Highest | High (cultural relics outflow) |

**Price Formula (for GM use):**

```
Final Price = Base Value × Condition Factor × Market Factor × Bargaining Factor

Base Value = Dynasty Factor × Item Type Factor × Rarity Factor
  Dynasty: Qin-Han=1.5, Tang=1.3, Song=1.0, Ming=0.8, Qing=0.5
  Type: Gold=2.0, Jade=1.8, Calligraphy/Painting=1.5, Bronze=1.3, Ceramic=1.0
  Rarity: Unique=3.0, Rare=2.0, Uncommon=1.5, Common=1.0

Condition Factor: Clean=1.0, Yin Qi Entwined=0.7, Obsession Attached=0.5, Cursed=0
Market Factor: Foreign Buyer=1.5, Underground Antique=1.2, Ghost Market=0.5~3.0, Official=0.8
```

---

## Chapter 6: GM Narrative Guide

### 6-1 Building Horror Atmosphere — Five-Sense Description Method

| Sense | Description Direction | Example |
|------|------|------|
| **Sight** | Insufficient light, abnormal colors, moving shadows | "The torchlight reaches only three steps ahead — beyond those three steps, the darkness seems to have substance, slowly pressing in on you." |
| **Hearing** | Faint sounds in silence, sounds that shouldn't be there | "You hear the sound of water dripping behind you — but at this depth, there cannot be water. Drip. Drip. It's getting closer." |
| **Smell** | Decay, dampness, anomalous sweetness | "There's a sweet, cloying reek in the air — not the stench of a corpse, more like aged honey mixed with rotting flowers." |
| **Touch** | Sudden temperature drop, abnormal humidity | "Your hand touches the tomb wall — it shouldn't be warm. Stone at this depth should be cold. But it isn't." |
| **Intuition** | Sense of being watched, indescribable unease | "You see nothing. Your Luopan shows no anomaly. But you just know — something is watching you." |

### 6-2 Three-Layer Clue Method

| Layer | Acquisition Method | Revealed Content |
|------|------|------|
| **Surface Clue** | Observable, no check needed | Environment description, obvious items, visible traces |
| **Mid-Clue** | DC 10–14 check | Tomb's era, Feng Shui layout, tomb owner's approximate identity |
| **Deep Clue** | DC 16–20 or specific condition | Tomb owner's secret, truth of the obsession, hidden area entrance |

- Each new tomb chamber should provide at least one surface clue + one obtainable mid-clue
- Deep clues should hook into the core plot
- Prepare alternative paths when clues are missed

### 6-3 Pacing Control Loop

```
Exploration → Tension → Release → Tension Again
  │            │          │          │
  Clue         Encounter   Safe Pt    Loop
  Environment   Threat     Breather
```

- Do not trigger two high-intensity encounters in a row
- "Silence" itself can be horror — let players feel unease in a threat-free environment
- Every encounter should consume resources

### 6-4 The "Yes, And…" Principle

- Player says "I use the Luopan to sense the Yin Qi flow" → Don't say "Check failed, you sense nothing"
- Instead say: "The Luopan's needle trembles violently, but the direction is chaotic — this means the Yin Qi has been deliberately disturbed by something. You can sense the source lies deeper, but its exact location requires getting closer to confirm."
- **Failure creates a new narrative branch, not the end of the narrative.**

### 6-5 Solo Play Adjustments

A solo Earth Master descending into a tomb is extremely dangerous — insufficient Yang Qi.

| Adjustment Item | Rule |
|------|------|
| Threat Count | Reduced to 60% of normal (TTV × 0.6) |
| NPC Companion | Must provide at least one (fellow disciple, helper, rescued person) |
| Environmental Puzzles | DC unchanged (intellectual challenges unrelated to party size) |
| Insufficient Yang Qi | Yin-related checks DC +2 |
| Extra Resources | Start with double talisman paper and medical supplies |

### 6-6 Narrative Levels of Luopan Use

| Check Result | Narrative Example |
|------|------|
| **Critical Failure** | "The Luopan's needle spins wildly — either there's an extremely strong Sha source nearby, or your Luopan is broken. You can't be sure." |
| **Failure** | "The needle drifts slightly, but the reading is unstable. You can sense something is there, but can't pinpoint it." |
| **Success** | "The Luopan steadily points northwest — the magnetic needle sinks three degrees; the Sha source is below, about twenty zhang." |
| **Critical Success** | "The vibration pattern of the magnetic needle tells you this isn't an ordinary corpse mutation. The vibration frequency corresponds to Black Jiangshi level or above, and… more than one." |

---

## Chapter 7: Tomb Design Tools

### 7-1 Quick Tomb Chamber Generation (2d6)

| 2d6 | Tomb Owner | Dynasty | Seek-Dragon DC | Primary Threat | CR |
|:---:|------|------|:---:|------|:---:|
| 2 | Commoner | Qing | 6 | None / Fresh Corpse | 0–0.5 |
| 3–4 | Wealthy Merchant | Ming | 8 | Fresh Corpse | 0.5 |
| 5–6 | Official / Landlord | Ming/Qing | 10 | White Jiangshi | 2–3 |
| 7 | General | Song/Ming | 12 | Black Jiangshi | 4–5 |
| 8–9 | Prince / Noble | Tang/Song | 14 | Leaping Jiangshi | 6–7 |
| 10–11 | Emperor | Han/Tang | 18 | Leaping Jiangshi · Flying Jiangshi | 8–9 |
| 12 | Special | Pre-Qin | 22 | Unrotting Bone | 10–12 |

### 7-2 Complete Tomb Design Template

```
Tomb Name: __________
├── Tomb Owner
│   ├── Former Identity: (Emperor/Noble/General/Wealthy Merchant/Occultist/Commoner)
│   ├── Manner of Death: (Natural/ Killed/ Suicide/ Accident/ Live Burial)
│   ├── Core Obsession: (why won't the soul disperse?)
│   └── Secret in Life: (what the tomb owner didn't want known)
├── Era: (dynasty, specific year, historical background)
├── Feng Shui Layout
│   ├── Dragon Vein Type: (True Dragon Proper Acupoint/ Branch Dragon Side Acupoint/ Off Vein/ No Vein/ Reversed Dragon)
│   ├── Feng Shui Rating: (Great Auspicious/ Auspicious/ Neutral/ Inauspicious/ Great Inauspicious/ Deliberately Reversed Feng Shui)
│   └── Yin Qi Concentration: (1–7+)
├── Tomb Chamber Structure
│   ├── Tomb Passage (length, condition)
│   ├── Front Chamber (function, contents)
│   ├── Side Chamber ×? (contents of each)
│   ├── Main Chamber (coffin, strongest threat)
│   └── Rear Chamber / Secret Chamber (true treasure or true tomb owner)
├── Trap Type (Mechanical / Environmental / Chemical / Supernatural)
├── Supernatural Threat (type, tier, count, trigger condition, weakness)
├── Burial Goods (main artifacts, total value, spiritual state)
├── Tomb Owner's Obsession (content, manifestation, resolution, consequence if unresolved)
└── Hidden Secret (secret in the tomb, how discovered, impact of disclosure)
```

### 7-3 Influence of Feng Shui Layout on the Tomb

| Feng Shui Rating | Yin Qi Concentration | Corpse Mutation Probability | Effect on Players |
|:---:|:---:|:---:|------|
| Great Auspicious | Low | 5% | Tomb owner rests in peace, no supernatural threat |
| Auspicious | Low-Medium | 15% | Possible mild paranormal phenomena |
| Neutral | Medium | 30% | Standard-difficulty supernatural threat |
| Inauspicious | Medium-High | 50% | High difficulty, Sha affects checks |
| Great Inauspicious | High | 70% | Extreme difficulty, all checks at Disadvantage |
| Deliberately Reversed Feng Shui | Extreme | 90% | Tomb owner may have sited it for a special purpose |

### 7-4 Five Types of Sha

| Sha | Source | Luopan Manifestation | Effect on Players |
|------|------|------|------|
| Yin Sha | Corpse mutation, resentful spirit | Needle sinks | Body temperature drops, breathing difficulty |
| Form Sha | Poor Feng Shui layout | Needle trembles | Loss of directional sense |
| Water Sha | Underground river, mercury | Needle sways | Dampness, equipment corrosion |
| Fire Sha | White phosphorus, sulfur | Needle rises | Body temperature rises, dry mouth |
| Blood Sha | Human sacrifice, mass death | Needle spins violently | Hallucination, loss of emotional control |

---

## Chapter 8: Burial Goods and Curse System

### 8-1 Appraisal of Burial Goods' Spiritual State

| State | DC | Market Value | Risk |
|------|:---:|:---:|------|
| Clean | 6 | Normal market price | None |
| Yin Qi Entwined | 10 | ×0.7 | Yin Qi check −1 |
| Tomb Owner Obsession Attached | 14 | ×0.5 | Long-term possession risks obsession infection |
| Cursed | 18 | Cannot be sold normally | See Curse Table |
| Suppression Item | 22 | Not for sale | Removing it releases the sealed thing |

### 8-2 Curse Effect Table (d10)

| d10 | Curse | Removal |
|:---:|------|------|
| 1 | Haunted by Nightmares: Long rest Will check DC 12, failure prevents True Qi recovery | Talisman Sect purification DC 14 |
| 2 | Yin Sha Attraction: Supernatural encounter probability doubled | Return to original tomb |
| 3 | Fortunes Decline: Natural rolls of 1–2 are Critical Failures | Fulfill tomb owner's last wish |
| 4 | Body Heat Loss: Constitution-related checks at Disadvantage | Seven days of noonday sunlight exposure |
| 5 | Hallucinations: GM secretly rolls d6 each turn, 6 = hallucination | Advanced talisman purification DC 18 |
| 6 | Tomb Owner's Call: Weekly Will check DC 14, failure forces return | Return and fulfill the demand |
| 7 | Life Drain: −1 temporary HP daily | Destroy the item or purify the earth vein |
| 8 | Language Curse: Cannot speak a specific word | Reveal the truth publicly |
| 9 | Bloodline Curse: Passed to the next generation | Three generations of atonement |
| 10 | Tomb Owner Possession: Replaced by the tomb owner's will | Will contest DC 18 or exorcism DC 22 |

### 8-3 Special Burial Goods Types

| Type | Description | GM Usage Advice |
|------|------|------|
| **Suppression Item** | An arcane implement placed in the coffin to suppress something. Removing it = releasing that thing | The ultimate moral dilemma — take it or not? |
| **Tomb Owner Relic** | An item carrying the tomb owner's strong obsession. The holder sees fragments of the tomb owner's memories | Both clue and trap. Can be used to advance the plot |
| **Sealed Container** | A seemingly ordinary burial good that is actually a sealed object. Opening = release | Classic horror beat — curiosity killed the cat |
| **Fake** | Refined forgery. May mislead players about the tomb owner's identity | Second layer of defense for the false tomb |
| **Curse Trap** | The item that looks most valuable — actually under the strongest curse | Tests the players' antique appraisal skill |

---

## Chapter 9: Random Encounter Table

When players deviate from the scenario to explore, or the GM needs to improvise tomb content, roll d20:

| d20 | Encounter Type | Content |
|:---:|------|------|
| 1–5 | **Silence** | Nothing at all — but silence itself is the most terrifying thing in the tomb. GM describes the environment; players may make a Perception check |
| 6–7 | **Environmental Threat** | Cave-in (DC 12 Dodge, failure 1d6), toxic gas (Constitution DC 12), slippery floor (Agility DC 10 to avoid falling) |
| 8–9 | **Minor Discovery** | Murals/inscriptions (DC 12 tomb-chamber reading to gain tomb-owner clues), predecessors' left-behind items (broken tools, dried blood) |
| 10–11 | **Traces** | Jiangshi drag marks (Tracking DC 14), glutinous rice residue (left by a previous band of tomb robbers), burnt talisman paper ashes |
| 12–13 | **Minor Spirit** | Harmless lingering spirit (can converse for information DC 14), wandering animal spirit |
| 14–15 | **Trap** | Crossbow bolt (DC 12 Dodge, 2d4), flip panel (DC 14 Awareness), falling rocks (DC 14 Dodge, 2d6) |
| 16 | **Supplies** | Predecessors' leftover supplies (1d4: 1=first-aid kit 2=rations 3=rope 4=fire starter) |
| 17 | **Fresh Corpse ×1** | CR 0.5, HP 15. May have just crawled out of the coffin |
| 18 | **White Jiangshi ×1** | CR 2, HP 25. Patrolling or feeding |
| 19 | **Black Jiangshi ×1 + Clue** | CR 4, HP 45. Defeating it reveals tomb-owner-related clues |
| 20 | **Special Discovery** | GM decides: hidden side chamber (with extra burial goods), sealed object, or a friendly spirit creature |

> **Usage advice:** Do not trigger two combat encounters in a row in the same area. Leave at least one tomb chamber / stretch of exploration between two d20 results.

---

## Chapter 10: Scenario Running Guide

### 9-1 Scenario Structure (Standard Three Acts)

```
Act One: Take the Case & Prepare
  - Accept the commission (or discover clues yourself)
  - Gather intel, buy supplies
  - Travel to the tomb

Act Two: Descend & Explore
  - Enter the tomb passage (first encounter)
  - Tomb chamber exploration (environment description, clue discovery, trap handling)
  - Core encounter (main chamber, open coffin, corpse mutation)

Act Three: Retreat & Settle
  - Retreat from the tomb (may encounter pursuit)
  - Handle burial goods (appraise, trade, lift curses)
  - XP settlement and plot wrap-up
```

### 9-2 Overview of the Seven Scenarios

| No. | Scenario | Level | Difficulty | Sessions | Key Features |
|:---:|------|:---:|:---:|:---:|------|
| S1 | First Cry | 1–3 | Easy | 1–2 | Newbie-friendly, first Fresh Corpse, social puzzle |
| S2 | General's Mound | 3–5 | Medium | 2–3 | Black Jiangshi dialogue, Broken-Tail Tiger Feng Shui, dual spirits |
| S3 | Mercury Maze | 5–7 | Medium | 2–3 | Environmental challenge, mercury gas, Qin-era traps |
| S4 | Ghost Market Deal | 5–7 | Special | 1–2 | Social-led, auction, non-human trade partners |
| S5 | Corpse-Raising Ground | 7–9 | Hard | 2–3 | Mass corpse mutation, great Sha-suppression formation, ancient altar |
| S6 | Unrotting Bone | 9–12 | Extreme | 3–4 | Cross-region hunt, cat-and-mouse, moral choice |
| S7 | Imperial Mausoleum | 12–15 | Epic | 4–6 | Ultimate challenge, Five-Element Hall, immortality choice |

### 9-3 Scenario Selection Advice

| Player Level | Recommended | Notes |
|:---:|------|------|
| 1–3 | S1 | Newbie must-play |
| 3–5 | S2 | Natural progression after S1 |
| 5–7 | S3 or S4 | Can run in parallel or any order |
| 7–9 | S5 | Requires some S3 knowledge |
| 9–12 | S6 | Cross-region hunt unlocked |
| 12–15 | S7 | All prerequisites complete |

### 9-4 Single-Session Time Estimate

| Content | Time |
|------|:---:|
| Character intro + case acceptance | 30 min |
| Pre-departure prep (shopping, intel gathering) | 20–30 min |
| Each tomb chamber exploration | 30–60 min |
| Small combat (TTV ≤ 6) | 15–30 min |
| Medium combat (TTV 7–14) | 30–60 min |
| Large combat (TTV 15–25) | 45–90 min |
| Boss battle (TTV 26+) | 60–120 min |
| Retreat + settlement | 20–30 min |

---

# Appendix

## Appendix A: GM Quick Reference

### Core Formulas

| Formula | Content |
|------|------|
| Check | 2d10 + Attribute + Skill + Equipment vs DC |
| Attack | 2d10 + Agility + Martial Art/Weapon Combat vs DEF |
| Corpse Poison | 2d10 + PR vs Corpse Poison DC (12/16/20/24) |
| Fear | Fear Value accumulates → exceeds FT = Disadvantage → exceeds 1.5×FT = Panic → exceeds 2×FT = Breakdown |
| Talisman Drawing | 2d10 + Spirit Sense + Talisman Drawing vs Talisman DC (10/14/18/22) |
| TTV | Σ(CR × count) × Environment Factor × (Player Count ÷ 4) |

### Monster Quick Reference

| Monster | CR | HP | DEF | Core Weakness |
|------|:---:|:---:|:---:|------|
| Fresh Corpse | 0.5 | 15 | 5–8 | Sunlight, Evil-Dispelling Talisman instant kill |
| White Jiangshi | 2–3 | 25 | 12 | Evil-Dispelling Talisman, Glutinous Rice, Corpse-Suppressing Talisman |
| Black Jiangshi | 4–5 | 45 | 15 | Coin Sword, Ink-Line Boundary |
| Leaping Jiangshi | 6–7 | 70 | 17 | Five-Thunder Palm, arcane implement |
| Leaping Jiangshi · Flying Jiangshi | 8–9 | 65 | 19 | Same as Leaping Jiangshi + narrow space |
| Unrotting Bone | 10–12 | 120 | 24 | Only arcane implements / Five-Thunder Palm effective |
| Resentful Spirit | 3–6 | 30–50 | 14 (illusory) | Arcane implement, talisman, fulfill obsession |

### DC Quick Reference

| DC | Difficulty | Use |
|:---:|------|------|
| 6 | Extremely Easy | Daily actions |
| 8 | Easy | S1 exploration |
| 10 | Simple | Imperial Mausoleum acupoint fixing, path-finding talisman, message talisman |
| 12 | Slightly Hard | S2–S4 core DC |
| 14 | Medium | Evil-Dispelling Talisman, Filth-Breaking Talisman, General's Mound acupoint fixing |
| 16 | Upper-Medium | S5 core DC |
| 18 | Hard | Hidden ancient tomb, Corpse-Suppressing Talisman, Unrotting Bone dialogue |
| 20 | Difficult | Leaping Jiangshi related |
| 22 | Extremely Hard | False tomb, Five-Thunder Talisman |
| 24 | Master Level | Unrotting Bone defense |
| 26 | Legendary | Sealing Corpse-Raising Ground |
| 30 | Impossible | Rarely used |

---

> **Earth Master TRPG GM Rulebook v1.0**
>
> "You are the darkness in the tomb. You are the breath beneath the coffin lid. You are the tomb owner's unfulfilled obsession.
> You are also the lantern-bearer — leading players through fear, waiting at the exit."
>
> Tabletop Rules Studio © 2025
