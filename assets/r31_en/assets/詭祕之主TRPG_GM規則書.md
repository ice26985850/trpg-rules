# Lord of the Mysteries TRPG — GM Rulebook v1.0

> **This handbook contains GM-exclusive content:** complete combat rules, worldview setting, GM running guide, starting module, advanced campaign framework, encounter designer, monster template library, and quick-reference tables.
> For player rules (core mechanics, character creation), please refer to the *Player Rulebook*.

---

# Chapter One: GM Combat Management

## 1.1 Encounter Design

### Challenge Rating (CR)

| CR | Description | Equivalent Player |
|----|-------------|-------------------|
| 1/2 | Mortal thug | Sequence 9 × 1 |
| 1 | Trained mortal, novice Sequence 9 | Sequence 9 × 1 |
| 2 | Wild Sequence 9 Beyonder | Sequence 9 × 2 |
| 3 | Sequence 8 Beyonder | Sequence 9 × 3 |
| 4 | Sequence 7 Beyonder, Spirit World creature | Sequence 9 × 4 |
| 5 | Elite Sequence 7 | Sequence 9 × 5 |
| 6 | Sequence 6 Beyonder | Sequence 8 × 4 |
| 8 | Sequence 5 Beyonder | Sequence 7 × 4 |
| 10 | Sequence 4 Demigod | Sequence 5 × 4 |
| 12+ | Sequence 3–0 high-tier | Requires plot devices |

### Encounter Budget (4–5 Sequence 9 players)

| Difficulty | Total CR | Resource Cost |
|-----------|----------|---------------|
| Easy | 3–4 | 10–20% Spirit |
| Normal | 5–7 | 30–40% Spirit |
| Hard | 8–10 | 50–70% Spirit |
| Lethal | 11–14 | Near exhaustion, high death risk |

> CR stacking: total CR of multiple low-CR enemies = single CR × count × 0.7

### Design Principles

1. **Variety:** at least 2–3 enemy types per scene (frontline / backline / control).
2. **Environmental storytelling:** gas lamps (can be broken to cause fire), abandoned factories (periodic mechanical damage), churches/graveyards (pathway bonus/penalty), Spirit World Rift (accelerated Loss).
3. **Loss variable:** unstable Sealed Artifacts, enemies who may lose control first, environmental whispers.
4. **Non-combat goals:** recover a Sealed Artifact, protect mortals, break a blockade, prevent a disaster.
5. **Elastic adjustment:** reinforcements (d6 rounds), enemy infighting, environmental upheaval (heavy fog / explosion), third-party intervention.

### Quick Encounter Generator (d10)

| d10 | Type | Enemy | Environment | Twist |
|-----|------|-------|-------------|-------|
| 1 | Street Brawl | 2d4 mortal thugs | Narrow alley | Someone carries a Sealed Artifact |
| 2 | Wild Beyonder | 1 Edge-of-Loss Sequence 9 | Abandoned building | Fully loses control mid-combat |
| 3 | Sealed Artifact Leak | 1 spawn | Anywhere | Can "persuade" the artifact to stop |
| 4 | Gang War | Two groups of mortals + Beyonder boss | Docks/warehouse | Third party bursts in |
| 5 | Cult Ritual | Sequence 8 + 2d4 believers | Basement | Ritual completion summons something stronger |
| 6 | Spirit World Invasion | 1d3 Spirit World creatures | Weak point in the Spirit World | Rift gradually widens |
| 7 | Official Raid | 1d3 Nighthawks | Player stronghold | Can be negotiated |
| 8 | Beyonder Assassination | Sequence 7 assassin | Social setting | Must protect a target person |
| 9 | Monster Hunt | Inhuman monster | Wilderness / sewers | Flees to ambush after being wounded |
| 10 | Pathway Conflict | Hostile Sequence 8–7 of a pathway | Pathway-related scene | Both sides may lose control |

---

## 1.2 Managing Loss of Control in Combat

### Loss of Control Triggers (in combat)

| Trigger | LoC | Frequency |
|---------|-----|-----------|
| Spending over 50% Spirit in a single scene | +1 | Once per scene |
| Forcing a power after Spirit Pool depleted | +3 | Each time |
| Beyonder power Critical Failure | +1 | Each time |
| Witnessing a Sequence 4+ high-tier manifestation | +1d3 | — |
| Being gazed at / touched by a high-tier entity | +2d3 | — |
| Teammate fully loses control | +1 | Once per scene |
| Taking > 50% HP damage in a single round | +1 | Once per scene |
| Using an incompatible Sealed Artifact | +2 | Each time |
| Fighting in a Spirit World / corrupted site | +1 / 5 rounds | Ongoing |

### Per-Round Check at the Edge of Loss

Trigger: LoC ≥ threshold. Each round, in the Resolution Phase, **d100 ≤ Mind**.

| Result | Effect |
|--------|--------|
| Critical Success (≤ Mind/5) | Suppress madness, +10 next round |
| Success | Barely suppress, all checks −10 |
| Failure | Partial loss, roll the Loss Behavior table |
| Critical Failure | Complete Loss of Control, GM takes over |

### Loss Behavior Table (d10)

| d10 | Behavior |
|-----|----------|
| 1–2 | Instinct Burst: attack the nearest target indiscriminately for 1 round |
| 3–4 | Mad Flight: move at full speed in a random direction for 1 round |
| 5–6 | Stupor: mutter to self, lose all actions for 1 round |
| 7–8 | Power Rampage: random Beyonder power at a random target for 1 round |
| 9 | Self-harm: attack self |
| 10 | Mutation Release: 2d10 pathway-attribute damage in a 5m radius around self |

### Handling Complete Loss of Control

1. GM fully takes over the character, becoming an NPC/monster.
2. Attack the nearest target indiscriminately, preferring the strongest in Spirituality.
3. +2 LoC per round (accelerating deterioration).
4. LoC > 2× threshold → permanent transformation → material for the next group's Boss.

### Recalling a Lost Character

**Recall action (2 AP, requires contact or ≤ 5m): d100 ≤ Charisma**

| Result | Effect |
|--------|--------|
| Critical Success | Immediate recovery, LoC −3, remaining Loss checks this scene +10 |
| Success | Regain autonomy this round, LoC −1 |
| Failure | No effect, treated as a threat |
| Critical Failure | The recaller's own LoC +1 |

Modifiers: deep bond +15 / true name +10 / personal item +5 / same pathway +5 / mutation −10 / lost control within 24h −15

> **A character can only be recalled once per combat. A second loss means immediate Complete Loss of Control.**

---

## 1.3 Monster and NPC Templates

### Template Format

```
[Name]                CR: [Challenge Rating]
[Type] [Mortal/Beyonder/Spirit World Creature/Sealed Artifact Spawn]
[Pathway/Sequence] [if any]
Attributes: SPI__ MND__ BOD__ AGI__ CHA__
HP: __ / Spirit Pool: __ / Initiative: __ / Dodge: __
LoC: __ / Threshold: __ (Beyonder NPCs only)
Attack: [Attack Name] — Hit +__, Damage __, Range __, Special __
Power: [Power Name] — [Brief description]
Resistance/Weakness / Loot
Tactical Tendency / Loss Risk
```

### Example 1: A Wild Beyonder at the Edge of Loss

**[Corrupted Seer]** CR: 2 | Fool Pathway / Sequence 9
- Attributes: SPI 45 MND 30 BOD 35 AGI 30 CHA 10
- HP: 115 / Spirit Pool: 140 (32 remaining)
- LoC: 58 / Threshold: 70 (Whisper stage)
- Attack: Dagger (+10 / 1d8+7), Mad Throw (+5 / 1d4+7 / 10m)
- Power: Danger Premonition (reaction / weakened), Pendulum Tracking (distorted → points to the strongest in Spirituality)
- Weakness: Mental damage ×1.5
- Tactics: Paranoid, attacks the highest-SPI target. Flees when HP < 30.

### Example 2: A Sequence 7 Villain Beyonder

**[Witch Serafina]** CR: 5 | Demoness Pathway / Sequence 7 Witch
- Attributes: SPI 55 MND 50 BOD 40 AGI 55 CHA 60
- HP: 130 / Spirit Pool: 170
- Attack: Poisoned Dagger (+25 / 1d8+11 + Poison), Shadow Arrow (+20 / 2d8 Dark + Curse / 15m), Spider Silk Binding (+15 / Bind / 15m)
- Power: Ambush Specialization, Black Magic Curse (−15 / 3 rounds), Charm Eye (1 AP), Spider Movement (passive)
- Resistance: Dark halved | Weakness: Mental attack −2
- Tactics: Cunning, charms + controls on the first round. Retreats when HP < 50%.

### Example 3: An Inhuman Monster

**[Spirit World Dream Eater]** CR: 4 | Native Spirit World predator
- Attributes: SPI 40 MND 20 BOD 50 AGI 45 CHA 5
- HP: 180 / Spirit Reserves: 60
- Attack: Spirit Tentacle (+20 / 2d8+10 Mental + Whisper / 10m), Dream Devour (+15 / 3d6 / sleeping targets only / drains 50% HP), Spirit Shriek (auto-hit / 1d8 Mental / 15m radius / all Whisper 1 round)
- Power: Spirit Form (1 AP / immune to physical / can be hit by Light & Lightning), Dream Traversal (vanishes 1 round then appears 30m away), Fear Aura (10m / every 3 rounds)
- Resistance: physical halved (non-silver), Mental immune
- Weakness: Light ×1.5, Silver ×1.5 and ignores Spirit Form, Lightning ×1.5 and disables Spirit Form 1 round
- Tactics: priority-attacks the highest-LoC target. Uses Spirit Form to escape when Spirit Reserves run low.

---

# Chapter Two: World Setting

## 2.1 Era Background

This is a world resembling the mid-Victorian era (1850s–1880s style).

- **Tech level:** steam engines, difference engines (early computers), revolvers, rifles, telegraph, trains, airships.
- **Social structure:** royalty → nobility → middle class → workers → poor, with clear stratification.
- **Surface world:** industrial civilization thrives, imperial colonial expansion, scientific rationality reigns supreme.
- **Hidden world:** the 22 Beyonder pathways vie in the shadows, churches cover up supernatural truth, and secret organizations pull strings from behind the scenes.

---

## 2.2 Gray Mist City

The empire's third-largest city, population 1.2 million, the industrial heart of the north. Shrouded in thin mist year-round, where coal smoke and spirituality intertwine.

### Seven Districts

| District | Feature | Beyonder Ecology |
|----------|---------|------------------|
| **Crown District** | Noble mansions, Royal Theater | Hideout of noble Beyonders |
| **Gear District** | Factories everywhere, roaring steam | Difference-engine anomalies mask Loss events |
| **Ash Harbor District** | Docks, warehouses, taverns | Sealed Artifact smuggling and info-trading hub |
| **Academy District** | Mistgrave University | Forbidden knowledge in the underground library |
| **Iron Bridge District** | Middle-class housing, commercial streets | Decent surface hiding Beyonder heritage |
| **Sunken Smoke District (Slum)** | Slums, abandoned factories | Hideout of wild Beyonders and cults |
| **Underground Mistgrave** | Abandoned mines + ancient ruins | Headquarters of secret organizations |

### Five Beyonder Locations

1. **Drowned Man Tavern** — an information exchange where every secret has its price.
2. **Warehouse No. 10** — a Sealed Artifact black market, hidden inside a disguised dock-district warehouse.
3. **Echo Hall** — a secret gathering point in an abandoned opera house.
4. **Mistgrave University Underground Library** — forbidden knowledge deep in maze-like shelves.
5. **St. Maria Asylum** — a secret asylum for those who have lost control.

---

## 2.3 The Seven Factions

| Faction | Public Identity | True Purpose | Attitude Toward Players |
|---------|----------------|--------------|--------------------------|
| **Church of the Evernight** | Imperial state religion | Uphold theocracy, suppress heresy | Wary — wild Beyonders are a threat |
| **Church of the Steam and Machinery God** | Rising church | Tech + Beyonder fusion | Curious — willing to recruit technical Beyonders |
| **Nighthawks** | Official Beyonder management | Maintain order, cover up truth | Watchful — but also a potential employer |
| **Secret Order (Twilight Hermit Order)** | Aristocratic scholarly circle | Study forbidden knowledge | Elitist — admits those of value |
| **Blood Money Gang** | Underclass gang | Beyonders control the underworld kingdom | Wooing — needs capable people |
| **Church of the Fool** | Hidden rising faction | Recruits oppressed Beyonders under Tarot code-names | Shelters — but demands loyalty |
| **Gnostic Order** | Scholar circle | Seek the ultimate source of Beyonder knowledge | Neutral — trades knowledge for knowledge |

---

## 2.4 Historical Timeline

| Epoch | Era | Key Events |
|-------|-----|------------|
| **First Epoch** | Primordial Dark (Mythical Age) | Old Ones struggle for chaos. The 22 pathways take embryonic form |
| **Second Epoch** | Descent of the Seven Gods | The Seven Orthodox Gods descend and defeat the Ancient Gods. The First God War |
| **Third Epoch** | Forging of Order | Church systems established. Heretic inquisition institutionalized |
| **Fourth Epoch** | Steel and Spirituality | Steam Revolution, invention of the difference engine. Beyonder vs. Technology opposition |
| **Fifth Epoch** | Flame in the Fog (Present Day) | New factions rise. Loss-of-Control rate climbs. "Mechanical Spirituality" appears |

---

# Chapter Three: GM Running Guide

## 3.1 Acting Progress Judgment

### Three-Tier Acting System

| Tier | Progress | Criteria | Example (Fool Pathway) |
|------|----------|----------|-------------------------|
| **Phoning It In** | +0 | Only named the power then rolled | "I use Pendulum Divination" then rolls |
| **Passive** | +1 | Acting present but does not advance plot | Uses divination to help a neighbor find a lost cat |
| **Active** | +3 | Solves a problem by Beyonder means | Abandons investigation, directly uses pendulum to locate the clue |
| **Core** | +5 | Emotional investment and bearing consequences | Makes an accurate prophecy yet watches it happen, powerless to stop it |

### Suggested Issuance Per Game

- New group (first game): 5–8 points
- Regular group: 8–12 points
- Climax group (key plot node): 12–15 points
- At least 1 Core-acting opportunity per session

---

## 3.2 Loss-of-Control Pace Control

### Four-Stage Narrative Framework

**Stable Stage (< 50% of threshold)**
- What the GM does: plant environmental foreshadowing. Strange sounds, a shadow flickering in the corner, a familiar sense of déjà vu.
- How the player feels: safe and controllable.

**Whisper Stage (50%–75%)**
- Mechanic: all Mind checks at disadvantage.
- What the GM does: hand the player a secret note. E.g., "You hear someone calling your name — but using the childhood nickname you have long forgotten. No one should know that name."
- How the player feels: someone is speaking inside your head — and you know what it says is true.

**Mutation Stage (75%–100%)**
- Mechanic: Whisper effect + Charisma checks at disadvantage + bodily mutation.
- Optional GM rule "Twisting Power": using a Beyonder power deals +1d4 damage, but LoC gains an extra +1d3.
- What the GM does: describe bodily changes. "You notice your fingers twitching unconsciously — not from fear, but because they are trying to trace a symbol you do not recognize."
- How the player feels: your body no longer fully belongs to you.

**Edge of Loss (≥ 100%)**
- Mechanic: must make a Loss Check before each power use.
- What the GM does: the ultimate temptation. "Power has never been so pure. You feel you could glimpse the truth of the world — if only you let go." Give a line of narrative guidance before the check.
- How the player feels: every use of a power is a gamble with fate.

### Complete Loss Transformation

1. **Endgame moment:** after a failed Loss Check, describe — "You feel something inside you finally break free. It has been waiting for this moment."
2. **Transform into NPC/Boss:** use the lost form's stats directly in the next combat. Suggest keeping the original character's powers but +50% damage, adding a random behavior table.
3. **Narrative echo:** the original character's Surface Life is exposed, teammates remember them, may briefly appear as a spirit.

---

## 3.3 Narrative Pace

### Three-Act Structure

| Act | Share | Content | GM Notes |
|-----|-------|---------|----------|
| **Investigation** | 40% | Gather clues, visit NPCs, spirit sense | At least 1 Beyonder-discernible piece of info per scene |
| **Conflict** | 35% | Combat / social opposition / ritual contest | Keep CR within budget, Normal–Hard |
| **Truth** | 25% | Reveal the conspiracy, moral choice | At least 2 viable choices, no "correct" answer |

### Four-Layer Information Revelation

1. **Surface clue** (visible to mortals too): newspaper reports, eyewitness testimony, scene traces.
2. **Spirit clue** (found via divination / spirit sight): energy residue, spirit presence, omens.
3. **Professional knowledge** (Mysticism / pathway knowledge): identify pathway, Sealed Artifact tier, ritual purpose.
4. **Deep truth** (changes the worldview): the true power behind the scenes, the human side of the villain.

### Share Recommendations

Investigation 30% + social acting 20% + mysticism exploration 10% + combat action 25% + plot revelation 15%.

---

## 3.4 Atmosphere Building

### Five Elements of Victorian Gothic

1. **Fog** — obscures not only sight but also Beyonder traces.
2. **Gas lamp** — dim yellow light blurs in the moisture.
3. **Chimney industry** — black smoke day and night, enough to mask the sounds of Beyonder combat.
4. **Class decorum** — everyone wears a mask. A Beyonder wears two.
5. **Ancient secrecy** — the underground ruins are older than the city.

### Techniques for Describing the Unspeakable

- **Describe the sense, not the category:** "What you see is not a face — it is the overlapping pattern of your grandmother's face, your boss's face, and your own face in the mirror at once."
- **Describe the effect on the observer:** "You glance at it and forget what it looked like, but you know you forgot — you forgot what you did not want to forget."
- **Contrast and paradox:** "It is moving, yet it does not move. It is growing larger, yet the distance does not lessen."

---

# Chapter Four: Starting Module — "The Crimson Ball of the White Room"

## 4.1 Basic Info

- **Recommended players:** 3–5, Sequence 9, all pathways accepted.
- **Duration:** 2–3 sessions (3–4 hours each).
- **Core theme:** beauty and terror as two sides of one coin; how obsession destroys a person.
- **Villain:** Lady White — Visionary Pathway Sequence 6 "Hypnotist," who uses dance as a medium for emotional manipulation.

## 4.2 Background

For three months, a rumor has spread through Gray Mist City's artist circles: receive a white invitation printed with a red rose, and you will attend an unforgettable ball in the "White Room." Those who returned produced work suddenly full of astonishing vitality. But after the most recent ball, a painter vanished — leaving an unfinished painting in his studio: six people dancing, the sixth's face blurred.

## 4.3 Hooks (choose 1 of 3)

1. **Commission:** the missing painter's family hires the players to investigate.
2. **Rumor:** the players hear the ball's rumor at the Drowned Man Tavern, triggering a spiritual intuition.
3. **Chance:** a player receives a white invitation.

## 4.4 Act One: Investigation

**Clue Point 1 — The Missing One's Home:** Surface clue: the face of the sixth dancer in the painting seems to be changing. Spirit clue: Spirit Sight can sense Visionary Pathway residue.

**Clue Point 2 — 13 Moran Street:** Surface clue: neighbors say a black carriage comes for people every Friday night. Spirit clue: divination shows the carriage comes from the direction of the Iron Bridge District.

**Clue Point 3 — Drowned Man Tavern:** Social challenge: must succeed at Negotiation / bribe to pry from an informant that Lady White was once a genius dancer who lost everything in a performance accident.

**Clue Point 4 — Mistgrave University:** Academic challenge: checking old newspapers reveals that five years ago, a dancer miraculously survived a fire at the Royal Theater — but all subsequent reports vanished.

## 4.5 Act Two: Conflict

**Scene 1 — Ball Infiltration:** The players sneak into the White Room (basement of an abandoned theater in the Iron Bridge District). Over 20 guests are dancing. Investigation reveals one of the six dancers has already died, but Lady White refuses to admit it. Social path: talk with Lady White; Stealth: sneak backstage; Combat: triggered if discovered.

**Scene 2 — Confrontation:** Lady White activates her power — all guests become "dancers" under her emotional control. Options: knock her down directly, recall the controlled guests, destroy the Sealed Artifact "Eternal Metronome."

**Sealed Artifact — "Eternal Metronome" (Tier 2)**
- Form: a small metronome, its pendulum engraved with musical notes.
- Positive: uses rhythm to manipulate the emotions of those around her (Visionary Pathway Sequence 6 power).
- Side effect: the user becomes addicted to "perfect rhythm," thinking of everything in 8-beat measures.
- Hidden: at the stroke of midnight it sways on its own, summoning the "dancers" of the last ball.

## 4.6 Act Three: The Choice

Reveal the truth: five years ago Lady White did not "miraculously survive" the fire — she lost control; her rampaging power bound the theater audience in an endless dance hallucination. She has been "reholding" that ball, believing that if she dances perfectly enough, everything can begin again. That dead dancer — was herself, as she saw her in the hallucination.

### Ending Branches

| Choice | Result | Reward |
|--------|--------|--------|
| **Eliminate** | Defeat the Sequence 6 lost-control entity in direct combat | Tier 1 Sealed Artifact + 200 team Acting Progress |
| **Hand to Authorities** | Contact the Nighthawks (requires persuading with evidence) | Moderate reward + Nighthawks favor + 100 Progress |
| **Attempt Redemption** | Recall Lady White to help her face the truth | Lady White's keepsake + the Temperance Tarot card + 300 Progress |

### Loss Risk Markers

1. Spirit Sight sees the truth of the ball → +1d3
2. Directly affected by Lady White's dance → +2
3. Contact with the metronome > 3 rounds → +1d5
4. Witness Lady White's lost form → +1d3
5. Forcefully use Visionary Pathway powers to oppose → +2
6. Critical Failure check → +1d3
7. Spirit Pool depleted → +2d5
8. Witness the truth of the dancer's death → +1d5

---

# Chapter Five: Advanced Campaign Framework

## 5.1 Full Pace (Sequence 9 → 5)

| Stage | Sessions | Scale | Core Content |
|-------|----------|-------|--------------|
| Seq 9→8 | 10–15 sessions | Neighborhood-level | Discover the Beyonder world, meet the first lost-control entity, villain plants first threads |
| Seq 8→7 | 12–18 sessions | District-level | Contact secret organizations, choose a side, discover the mentor's secret |
| Seq 7→6 | 15–20 sessions | City-level | Understand the faction landscape, defeat the villain's lieutenant |
| Seq 6→5 | 20–25 sessions | Imperial-level | Promotion ritual as the plot's endpoint, final confrontation |

## 5.2 Villain Foreshadowing Template: Dr. Blackwood

| Player Sequence | Appearance | Clue Depth |
|-----------------|-----------|------------|
| Sequence 9 | A short newspaper note about a "missing scientist" | Name appears in a sidebar |
| Sequence 8 | Multiple Beyonder incidents point to one source — someone systematically collecting Beyonder Characteristics | Begin investigating |
| Sequence 7 | Reveal the "Mechanical Heart" experiment — decoding Third Epoch Blasphemy Slate fragments | Understand the threat |
| Sequence 6 | Full conflict with the doctor's lieutenant (Sequence 5) | Defeat the lieutenant |
| Sequence 5→4 | Promotion ritual and final confrontation completed together | Endgame |

---

# Chapter Six: GM Quick-Reference Tables

## 6.1 Difficulty Reference

| Difficulty | Modifier | Attr 30 | Attr 50 | Attr 70 |
|-----------|----------|---------|---------|---------|
| Routine | ±0 | 30% | 50% | 70% |
| Difficult | −20 | 10% | 30% | 50% |
| Extreme | −40 | — | 10% | 30% |
| Legendary | −60 | — | — | 10% |

## 6.2 Loss of Control Quick Reference

| Trigger | Value | Frequency |
|---------|-------|-----------|
| On-path power | +1 | Each time |
| Off-path power | +1d3 | Each time |
| Contact Sealed Artifact | +1d5 | Per scene |
| Witness Mythical form | +1d10+5 | One-time |
| Critical Failure | +1d3 | Any |
| Spirit Exhaustion | +2d5 | When depleted |
| Full rest | −5 | Each night |
| Core Acting | −3 | Each time |
| Psychotherapy | −5 | Each time |

## 6.3 Scene Pace Checklist

- [ ] Does this scene have investigation / social elements? (Goal: 60%+ scenes contain non-combat elements)
- [ ] Are there Beyonder clues? (Goal: at least 1 spirit-discernible piece of info per scene)
- [ ] Is the Loss risk controllable? (Goal: LoC gained per scene ≤ 5)
- [ ] Do the players have choices? (Goal: at least 2 viable paths at each decision point)
- [ ] Is the difficulty appropriate? (Goal: core check success rate 50–70%)

## 6.4 NPC Quick-Build Table

| d10 | Type | Example | CR Reference |
|-----|------|---------|--------------|
| 1 | Street punk | Sunken Smoke District gang member | 1/2 |
| 2 | Ordinary civilian | Merchant, teacher, reporter | 1/4 |
| 3 | Police / security | Nighthawks affiliated personnel | 1 |
| 4 | Low-sequence Beyonder | Wild Sequence 9 Beyonder | 2 |
| 5 | Gang boss | Blood Money Gang area manager | 3 |
| 6 | Sequence 8 Beyonder | Secret organization member | 3–4 |
| 7 | Sequence 7 Beyonder | Church mid-level / organization cadre | 4–5 |
| 8 | Sequence 6 Beyonder | Organization leadership | 6 |
| 9 | Sequence 5 Beyonder | City-level threat | 8 |
| 10 | Spirit World creature | Dream Eater / spirit | 3–6 |

---

> **This handbook is GM-exclusive.** For more scenarios and monster stats, please refer to the *Scenario Collection* and the Excel character sheet file.
> For the complete Sequence 9–5 ability values across all 22 pathways, please refer to *Complete Pathway Sequences*.

---

# Chapter Seven: Large-Scale Combat and Command

## 7.1 Abstraction Rules

When combat involves more than 12 participants, switch to unit and wave concepts:

**One unit = an aggregate of 5–10 similar combatants.**
- Unit HP = individual HP × count / 5
- Unit attack = individual attack + 5 per 5 people
- Unit damage = individual damage × √count (rounded)

## 7.2 Command Check

**d100 ≤ Charisma + Leadership skill bonus**

| Result | Effect |
|--------|--------|
| Critical Success | Allied unit +20 attack this round, morale +3 |
| Success | Allied unit +10 attack this round |
| Critical Failure | One unit attacks a random target this round |

Red Priest Pathway command is automatically at Advantage. Twilight Giant Pathway command gives allied units +20% damage.

## 7.3 Morale

| Morale | State | Effect |
|--------|-------|--------|
| 15+ | Fanatic | Attack +20 / 1% chance to disobey |
| 8–14 | Normal | Acts normally |
| 4–7 | Shaken | Attack −10 / 25% retreat |
| 1–3 | Collapsing | Attack −20 / 50% retreat |
| ≤0 | Routed | Permanently exits combat |

## 7.4 Quick Unit Types

| Unit (10 men) | CR | Attack | Damage | HP | Morale |
|---------------|-----|--------|--------|-----|--------|
| Mortal thugs | 1 | +5 | 1d6 | 30 | 6 |
| Armed militia | 2 | +10 | 1d8+2 | 40 | 8 |
| Regular soldiers | 3 | +15 | 2d6 | 60 | 10 |
| Nighthawks squad | 4 | +20 | 2d8 | 80 | 12 |

---

# Chapter Eight: Reputation and Factions

## 8.1 Reputation Levels

| Level | Reputation Value | Effect |
|-------|------------------|--------|
| 5 Revered | 76–100 | Proactively offers help, core resources available |
| 4 Trusted | 51–75 | High-level commissions, intel sharing |
| 3 Friendly | 26–50 | Regular commissions, intel purchasable |
| 2 Neutral | 1–25 | Basic interaction (starting value) |
| 1 Wary | −1 to −25 | Fewer commissions, guarded |
| 0 Hostile | Below −26 | Actively hunts you down |

## 8.2 Reputation Changes

| Behavior | Change |
|----------|--------|
| Complete a commission | +5 |
| Exceed-expectation commission | +10 |
| Conflict with the faction's members | −10 |
| Sabotage the faction's plans | −15 |
| Sell valuable Sealed Artifact / intel | +3–10 |

**Chain effect:** when raising Reputation with one faction, its "sworn enemy" automatically −2, its "cooperating" faction +1. Being Friendly with both the Church of the Evernight and the Church of the Fool will be discovered by both → each −10.

---

# Chapter Nine: Sealed Artifact Crafting

## 9.1 Five-Step Crafting Process

**Step 1:** Determine the source (fallen one's relic / extracted Characteristic / natural evolution).

**Step 2:** Determine tier and positive effect.

| Tier | Equivalent Sequence | Positive Baseline |
|------|---------------------|-------------------|
| Tier 3 | Sequence 9–7 | 1 low-tier power or check +15/20 |
| Tier 2 | Sequence 6–5 | 1 mid-tier power or check +25 |
| Tier 1 | Sequence 4–2 | 1 high-tier power or battlefield-rule change |

**Step 3:** Balance side effects (positive effect × compensation factor).
- Tier 3: 0.5 — minor (headache / fatigue)
- Tier 2: 0.8 — moderate (LoC / attribute penalty)
- Tier 1: 1.2 — severe (permanent damage / pathway conflict)

**Step 4:** Define usage limits (daily count / cooldown / conditions).

**Step 5:** Design ≥1 hidden trait (discoverable only via Mysticism check).

## 9.2 Crafting Recipe Baseline

| Tier | Material Value | Time | Check DC | Failure Consequence |
|------|----------------|------|----------|---------------------|
| Tier 3 | £30–60 | 1 week | 60 | 50% material loss |
| Tier 2 | £80–150 | 2 weeks | 75 | Total loss + LoC +1d5 |
| Tier 1 | £200–400 | 1 month | 90 | Total loss + LoC +2d5 + explosion (2d10) |

---

# Chapter Ten: Permanent Trauma System

After a character brushes the Edge of Loss or witnesses the unspeakable, the GM may grant permanent trauma (up to 3 per character). Each Sequence promotion can halve one trauma effect. The full trauma table is in the *Rules Supplement Manual*.

---

# Chapter Eleven: GM Quick-Reference Screen

```
Difficulty: Routine 0 / Difficult -20 / Extreme -40 | Adv ≈ +25% / Dis ≈ -25% | Crit ≤5 / Fumble ≥96
Loss triggers: on-path +1 / off-path +1d3 / artifact +1d5 / mythic +1d10+5 / fumble +1d3 / exhaustion +2d5
4 Loss stages: Stable <50% / Whisper 50-75% Mind disadv / Mutation 75-100% +CHA disadv / Edge ≥100% → each power → Loss Check
Clue tiers: Core (unmissable) / Key (check) / Aux (conditional) / Misleading (see-through)
Acting progress: Passive +1 / Active +3 / Core +5 | issue 5-15 per scene | per-Sequence 0-100
Reputation: 5 Revered / 4 Trusted / 3 Friendly / 2 Neutral / 1 Wary / 0 Hostile | complete commission +5
Encounter gen (d10): 1 street / 2 wild Beyonder / 3 artifact / 4 gang / 5 cult / 6 spirit / 7 official / 8 assassin / 9 monster / 10 pathway conflict
Quick NPC: Mortal (attr 20-30) / low-seq (40-50) / mid-seq (55-65) / high-tier (70+) | HP = Body × 2 + 15
Interlude: 1d3 points per adventure | craft / train / maintain surface life / contact / purify
```
