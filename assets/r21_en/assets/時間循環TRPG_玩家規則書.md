# Time Loop TRPG — Player Rules Book v1.0

> **Codename:** `timeloop-trpg`
> **Core Engine:** 2d6 + Attribute Modifier (PbtA-style Success Bands)
> **You need:** 2 six-sided dice (2d6) + character sheet + note-taking tools

---

## Quick Start (Learn in 30 Seconds)

```
Roll 2d6 + Attribute Modifier + Situation Modifier

6 or lower → Failure
7-9      → Partial Success (achieved, but at a cost)
10 or higher → Full Success
Natural 12   → Critical Success (extra reward)
Natural 2    → Critical Failure (disastrous consequence)
```

| Concept | One-liner |
|------|--------|
| **Loop** | Time keeps resetting. Death = start over |
| **Memory Anchoring** | At the end of a loop, "lock" a few pieces of information to carry into the next loop |
| **Player Knowledge ≠ Character Knowledge** | You remember everything, but the character wakes up blank each time |
| **World Degradation** | With each reset, the world slightly breaks down |
| **Loop Fatigue** | Witnessing death, repeated failure—the mind accumulates trauma |

---

# Chapter One: Core Rules

## 1.1 Dice System

### Success Bands (fixed, do not adjust the target value)

| Roll Result | Success Level | Meaning |
|---------|:---:|------|
| Natural 12 ("Boxcar") | **Critical Success** | A perfect result beyond expectation + extra reward |
| Adjusted ≥ 10 | **Full Success** | Goal achieved, no cost |
| Adjusted 7–9 | **Partial Success** | Goal achieved, but with a cost/complication |
| Adjusted ≤ 6 | **Failure** | Not achieved, situation may worsen |
| Natural 2 ("Snake Eyes") | **Critical Failure** | Disastrous consequence |

### Difficulty is applied through "Situation Modifier" (do not adjust the target value)

| Difficulty | Situation Modifier | Description | Full Success rate at Attribute +1 |
|:---:|:---:|------|:---:|
| Easy | +2 | Almost impossible to fail | 58% |
| Normal | +0 | A competent person can handle it | 28% |
| Hard | −1 | Even a skilled person faces a challenge | 17% |
| Very Hard | −2 | Requires professional training and luck | 8% |
| Nearly Impossible | −3 | Only top experts can attempt | 3% |

### Advantage/Disadvantage
- **Advantage:** Roll 3d6, keep the highest 2
- **Disadvantage:** Roll 3d6, keep the lowest 2
- Advantage and Disadvantage cancel each other out (normal 2d6)

### Contested Check
Both sides roll 2d6 + Attribute Modifier; higher wins. Tie = the active side gets a Partial Success.

---

## 1.2 The Five Attributes

| Attribute | Abbrev. | Meaning | Role in the Loop |
|------|:---:|------|------|
| **Memory** | Memory (MEM) | Information retention, detail recall | Determines Anchor count—how much information can be carried into the next loop |
| **Insight** | Insight (INS) | Pattern recognition, contradiction detection | Detecting NPC behavior shifts, noticing degradation signs |
| **Will** | Will (WIL) | Mental resilience, fatigue resistance | Resisting Loop Fatigue, maintaining drive amid despair |
| **Action** | Action (ACT) | Physical ability, execution efficiency | Action Points per loop, chase/combat/stealth |
| **Empathy** | Empathy (EMP) | Understanding others, building relationships | Persuading NPCs, soothing teammates, social contests |

### Attribute Value → Modifier

| Attribute Value | Modifier | Meaning |
|:---:|:---:|------|
| 1 | −1 | Significant flaw |
| 2 | +0 | Ordinary level |
| 3 | +1 | Capable (human average) |
| 4 | +2 | Excellent |
| 5 | +3 | Legendary |

### Check Scenarios by Attribute

**Memory:** Recall NPC lines, reproduce routes, identify detail changes, reconstruct a map mentally.

**Insight:** Search a scene, notice behavioral anomalies, find contradictions, solve puzzles, perceive degradation.

**Will:** Resist fear, stay calm under high pressure, face death, maintain focus, self-regulate.

**Action:** Chase, stealth, pick locks, fight, move quickly, fine manipulation, complete tasks under time pressure.

**Empathy:** Persuade NPCs, soothe teammate fatigue, see through lies, gain trust, negotiate deals.

---

## 1.3 Derived Attributes (auto-calculated)

| Derived Attribute | Abbrev. | Formula | Range | Use |
|---------|:---:|------|:---:|------|
| **Memory Anchor Points** | Memory Anchor Points (MAP) | Memory (MEM) + ⌊Insight (INS)/2⌋ | 1–7 | Number of pieces of information that can be locked at loop end |
| **Loop Fatigue Threshold** | Loop Fatigue Threshold (LFT) | Will (WIL) × 2 + 5 | 7–15 | Once fatigue exceeds this, negative effects begin |
| **Daily Action Points** | Daily Action Points (DAP) | 8 + Action (ACT) modifier | 7–11 | Action Points available per loop |
| **Déjà Vu DC** | Déjà Vu DC (DVD) | 10 − exposure count this loop (minimum 6) | 6–10 | Difficulty of intuitively sensing unanchored information |

### Déjà Vu DC Explained

| Exposure Count | DC | Meaning |
|:---:|:---:|------|
| 1st time | 10 | Almost impossible by intuition alone |
| 2nd time | 9 | A vague sense of familiarity begins |
| 3rd time | 8 | Faintly feel you've seen it |
| 4th time | 7 | Strong Déjà Vu |
| 5th+ time | 6 | Nearly certain—the body remembers more than the brain |

---

## 1.4 Core Mechanics

### Memory Anchoring (performed at loop end)

| Step | Content |
|------|------|
| **1. Review** | List all important information obtained this loop |
| **2. Choose** | Spend Memory Anchors to lock information (1 Anchor = 1 piece of information) |
| **3. Write** | Write the chosen information on the character sheet; next loop it is "intuitively available" |
| **4. Forget** | Unanchored information—you still remember, but the character does not |

**Anchor Strength:**

| Cost | Clarity | Usable As |
|:---:|------|------|
| 1 Anchor | Vague impression | "I feel it's better not to take that alley" |
| 2 Anchors | Clear memory | "The guard goes to smoke at 3 PM, the back door has a 5-minute window" |
| 3 Anchors | Full reproduction | Can draw the map, write the code, recite the dialogue |

### Player Knowledge vs Character Knowledge

| Information Type | Usable by Character? |
|------|:---:|
| **Anchored Information** (locked by spending Anchors) | ✅ Treated as "strong intuition" or "a dream" |
| **Déjà Vu Information** (triggered a successful Déjà Vu check) | ⚠️ Only a vague hint ("this person feels off") |
| **Lost Information** (neither anchored nor triggered Déjà Vu) | ❌ You know it but the character does not |

### Loop Degradation

| Loop Count | Degradation Chance | World State |
|:---:|:---:|------|
| 1-3 | 0% | Stable—establish the baseline |
| 4-6 | 30%/loop | Slight deviation |
| 7-9 | 60%/loop | Obvious distortion |
| 10-12 | 100%/loop | Accelerating collapse |
| 13+ | Unpredictable | World loses its logic |

**Degradation Effects:** Detail shifts, NPC behavior changes, anomalies appear, time shortens, memory erodes.

### Loop Fatigue

**Accumulation (event-triggered):**

| Trigger Event | Fatigue |
|------|:---:|
| Character death | +3 |
| Witnessing teammate death | +2 |
| Witnessing the death of an NPC with an established relationship | +1 |
| Key mission/plan failure | +2 |
| Encountering a World Degradation event | +1 |

**Stage Effects:**

| Fatigue Range | Stage | Effect |
|------|:---:|------|
| 0 – Loop Fatigue Threshold (LFT) | **Normal** | No negative effects |
| Loop Fatigue Threshold (LFT)+1 ~ Loop Fatigue Threshold (LFT)+5 | **Weary** | Action Points (AP) −1, Anchor −1 |
| Loop Fatigue Threshold (LFT)+6 ~ Loop Fatigue Threshold (LFT)+10 | **Exhausted** | Action Points (AP) −2, Anchor −2, Déjà Vu DC +3 |
| > Loop Fatigue Threshold (LFT)+10 | **Collapse** | May give up or take extreme action |

**Recovery:**
- Teammate Empathy soothing: Partial Success recovers 1, Full Success recovers 2
- Self Will self-heal (2 Action Points (AP)): Partial Success recovers 1, Full Success recovers 2
- Piecing together a Truth Fragment: −3
- Saving someone who died in a previous loop: −4
- Discovering a new hope clue: −2
- Doing a completely unrelated small thing (coffee and sunset): −1 (once per loop)
- Loop Reset: returns to zero

---

# Chapter Two: Character Creation

## 2.1 Creation Process (6 steps, about 20-30 minutes)

```
Step 1 → Step 2 → Step 3 → Step 4 → Step 5 → Step 6
 Background   Attribute Allocation   Time Attitude   Core Relationship   Starting Information   Starting Equipment
```

### Step 1: Background

Answer the following questions:
1. Who are you? (name, age, occupation)
2. What were you doing before you were trapped in the loop?
3. What is your last clear memory?
4. What is something distinctive about you?
5. In this place, what is your most important daily habit?

**Background Examples:**

| Type | Typical Identity | Advantage | Information Tendency |
|------|------|------|------|
| Enforcer | Police, security, soldier | Knows geography and people | Order, security related |
| Seeker | Teacher, journalist, researcher | Habit of observing and recording | Information, documents related |
| Caregiver | Doctor, nurse, social worker | Understands others' vulnerabilities and secrets | NPC private lives |
| Laborer | Worker, driver, clerk | Knows the city's "backstage" | Locations, item positions |
| Outsider | Drifter, artist | Goes unnoticed | Taboo, anomalies |
| Connected | Townsfolk, acquaintance, relative | Has a personal relationship with an NPC | NPC past |

> Background is not bound to attributes—"a Will 5 drifter-poet" is a better story than "a Will 5 soldier."

### Step 2: Attribute Allocation (choose one of three)

**Plan A: Standard Array (recommended for beginners)**
```
[3, 2, 2, 2, 1]   Total 10
You have one thing you're good at, and one thing you're clearly not.
```

**Plan B: Point-Buy**
```
Start all attributes = 1 (total 5), 5 points available
1→2→3→4 costs 1 point per level, 4→5 costs 2 points
```

| Example | Memory (MEM) | Insight (INS) | Will (WIL) | Action (ACT) | Empathy (EMP) |
|------|:---:|:---:|:---:|:---:|:---:|
| Balanced | 2 | 2 | 2 | 2 | 2 |
| Focused | 3 | 2 | 2 | 2 | 1 |
| Bimodal | 3 | 3 | 2 | 1 | 1 |
| Specialized | 4 | 2 | 2 | 1 | 1 |

**Plan C: Free Allocation** (9-11 points, GM approval)

### Step 3: Time Attitude (core choice)

| Attitude | Core Gain | Core Cost | Special Ability |
|------|------|------|------|
| **Optimist** | −1 fatigue when discovering fragments | — | Light of Hope: teammate gains Advantage on Will checks (once per loop) |
| **Skeptic** | Insight Advantage | Empathy Disadvantage | Eye for Flaws: force GM to reveal NPC contradiction (once per loop) |
| **Guardian** | +2 recovery when saving someone | +1 when witnessing death | Guardian Instinct: when Core Relationship NPC is in danger, auto-sense + free move |
| **Fatalist** | Fatigue Threshold +5, fatigue source −1 | Anchor −1 (minimum 1) | Gift of Fate: fatigue → temporary Anchor +1 (once per loop) |
| **Curious** | Anchor +1, Déjà Vu +1 | Degradation fatigue +1 | Detail Hunter: force GM to give an observation detail (once per loop) |

**Attitude Details:**

**Optimist** — "Every time I wake up, it's a new chance."
- Roleplay: writes "hope notes" at loop start, noting the new approach to try this time
- Low point: when loops pass with no progress, falls into deepest self-doubt

**Skeptic** — "Nothing is right, no one can be trusted."
- Roleplay: deliberately tests NPCs each loop—changes a small detail to see the reaction
- Low point: discovers they wrongfully blamed someone who genuinely wanted to help

**Guardian** — "This time, I'm going to get everyone out alive."
- Roleplay: at the start of each loop, first confirms everyone's location and safety status
- Low point: must choose between "saving A" and "saving B"

**Fatalist** — "The loop isn't a curse, it just happens."
- Roleplay: sits quietly for a moment at loop end, sorting thoughts
- Low point: when "it'll all reset anyway" slides toward the edge of giving up

**Curious** — "That NPC's sock color today is different from yesterday!"
- Roleplay: frantically takes notes, draws charts, faces the most painful anchoring choice at loop end
- Low point: too much memory, too few Anchors—knows everything but can't take it all

### Step 4: Core Relationship

Choose one person from the scenario's key NPC list as the person you must save.

**Effect:**
- Successful save → +2 extra fatigue recovery
- Death without prevention → +2 fatigue
- Cannot be "abandoned"

**Guiding Questions:**
1. What is your relationship? (be specific)
2. What do you owe them? Or what do they owe you?
3. If you could say one last sentence, what would it be?

### Step 5: Starting Information

The GM grants 1-2 pieces of "information the character already knew" based on your background and Core Relationship. These are public (shared by the group).

### Step 6: Starting Equipment

**Common:** Everyday clothes, phone (can photograph/record/take notes, cannot dial out), wallet/ID, key ring.

**Background Bonus:** Enforcer → badge & cuffs; Seeker → notebook & voice recorder; Caregiver → first-aid kit; Laborer → toolbox; Outsider → sketchbook/telescope; Connected → a keepsake related to the Core NPC.

---

## 2.2 Hidden Information Card (secret draw)

Drawn secretly at character creation—only you and the GM know it.

| # | Name | Core Content |
|:--:|------|------|
| 1 | Figure | Before the loop began, saw a figure... not sure if it was a hallucination |
| 2 | Grudge | Had a grudge with some NPC before the loop |
| 3 | The Culprit? | Vaguely feel... this loop was caused by you? |
| 4 | Reflection | Your reflection in the mirror was a moment slower than you |
| 5 | Slowing Watch | Your watch is 2 seconds slower each time you wake up |
| 6 | Unanswered Confession | The day before the loop, an NPC confessed to you—still unanswered |
| 7 | Future Diary | A page was added to the diary—your handwriting, but you don't remember writing it |
| 8 | Premonition Dream | Two days before the loop, had an identical nightmare |
| 9 | The Thing You Can't Say | There's a secret that would change everything if spoken |
| 10 | One More Person | There should be another person in the loop—but they never appeared again after the second time |
| 11 | Smell of Burning | Every fourth hour of the loop, you smell something burning—only you |
| 12 | The Mark on Your Body | A mark on your body that grows slightly larger each loop |

---

## 2.3 Cross-Loop Growth: Cognition Points (CP)

Characters have no levels. Growth is achieved through Cognition Points.

**Cognition Points (CP) Acquisition:**

| Source | Cognition Points (CP) | Note |
|------|:---:|------|
| Discover a Truth Fragment | +1 | Personally participated in the discovery |
| Major loop breakthrough | +1 | GM judgment, at most once per loop |
| Save a key NPC (first time) | +2 | Once per NPC |
| Moment of insight | +2~4 | GM triggered |
| Team puzzle 50%/75%/100% | +2/+2/+4 | Team shared achievement |

**Cognition Points (CP) Spending:**

| Spend | Cognition Points (CP) | Limit |
|------|:---:|------|
| Raise attribute +1 | New value ×3 | Max 5 |
| Second special ability | 5 | Once per person |
| Memory Anchor +1 | 4 | Max +2 |
| Cross-loop skill | 3 | Max 2 |
| Lower base Déjà Vu DC −1 | 3 | At most once |
| Fatigue Threshold +2 | 3 | Max +6 |

**Cross-Loop Skills (choose 2 of 8):**

| Skill | Effect |
|------|------|
| Time Sense | Know the time without a clock; +1 to time-race actions |
| Body Memory | Reproduce unanchored routes by body memory; +1 Déjà Vu |
| Speed Reading | Can examine one extra item during investigation without spending Action Points (AP) |
| Mind Notes | Freely anchor 1 piece of personally discovered information per loop (no Anchor spent) |
| Crisis Reflex | Advantage on actions when facing an identical threat |
| Face Memory | Can remember basic NPC info even if not anchored |
| Fatigue Management | Once per loop, a small recovery action costs no Action Points (AP) |
| Team Sync | Quick action to send a brief message to a teammate |

### Natural Memory Anchor Growth

| Condition | Growth |
|------|:---:|
| Every 5 loops completed | All surviving characters' Anchors +1 (temporary) |
| Team puzzle 50% | All characters' Anchors +1 (permanent) |
| Team puzzle 75% | All characters' Anchors +1 (permanent) |

---

## 2.4 Cross-Loop Item Rules

| Item Type | Behavior on Reset |
|------|------|
| Default Equipment | Returns to loop-start state |
| Ordinary items obtained in the loop | Disappear |
| **Anchored Item** (locked by spending 1 Anchor) | Retained—appears beside you on next wake |
| Key Plot Item | GM decides |

**Anchored Item vs Anchored Information:** Anchors are never enough. You must choose—anchor a key (open the door directly next time), or remember a key conversation?

---

# Chapter Three: Action and Conflict

## 3.1 Action Point Economy (AP)

```
Daily Action Points = 8 + Action (ACT) modifier  (ACT modifier = Action attribute − 2)
```

| Action (ACT) | Action Points (AP) | Action (ACT) | Action Points (AP) |
|:---:|:---:|:---:|:---:|
| 1 | 7 | 4 | 10 |
| 2 | 8 | 5 | 11 |
| 3 | 9 | | |

### Action Categories

| Category | Action Points (AP) | Example |
|------|:---:|------|
| **Instant** | 0 | Notice bloodstains, exchange a glance, remember a door number |
| **Quick** | 1 | Walk briskly, scan a document, say one line, hide in a wardrobe |
| **Standard** | 2 | Search a room, deep conversation, pick a lock, treat |
| **Full** | 3 | Cross-town movement, comb the archive room, long persuasion |
| **Cross-zone** | 4 | From in-town to outskirts, to a new area |

### Loop Phase Action Windows

| Phase | Usable | Restriction |
|------|------|------|
| ☀ Morning | Organize info, review memory, make plans | No long-distance movement |
| 🌤 Daytime | **All actions** | None (main window) |
| 🌅 Dusk | Limited actions | Fixed plot events occur, time pressure |
| 🌙 Night | Last chance | Most locations closed, danger rises |

Action Points (AP) do not accumulate across days. After a loop reset they return to the initial value.

### Team Action Points (AP) Coordination

| Method | Effect |
|------|------|
| Split investigation | Act separately to cover more locations |
| Assist action | Assister spends 1 Action Point (AP) → main actor gains Advantage |
| Team movement | Calculated by the slowest member's speed |
| Emergency call | 0 Action Points (AP), within one sentence |

---

## 3.2 Five Types of Conflict

### Type One: Physical Contest (chase, shove, grab) — Three-Round Contest

Both sides roll 2d6 + Action (ACT); whoever wins two of three rounds wins. 1 Action Point (AP) per round.

| Round | Winner | Tie |
|------|------|------|
| Burst | Gains initiative, +1 next round | Stalemate |
| Struggle | Advances goal 50% | Slight advance |
| Decisive | Achieves goal | Partial achievement (GM adjudicates cost) |

### Type Two: Violent Conflict — Instant Resolution

```
Attacker: 2d6 + Action (ACT) + weapon modifier + situation modifier
Defender: 2d6 + Action (ACT) (dodge)
   Attacker > Defender → Full hit (+2 wound level)
   Tie → Partial hit (+1 wound level)
   Defender > Attacker → Full dodge
```

| Attack | Situation Modifier | Base Damage | Special |
|------|:---:|:---:|------|
| Unarmed | Normal (+0) | Minor Wound | — |
| Unarmed vital | Hard (−1) | Moderate Wound | Defender's next-round Action (ACT) −1 |
| Blunt Weapon | Normal (+0) | Moderate Wound | Full hit → possible Severe Wound |
| Sharp Weapon | Normal (+0) | Moderate Wound | Full hit → certain Severe Wound |
| Firearm | Very Hard (−2) | Severe Wound | Full hit → Near-Death |

### Type Three: Stealth Hiding — Alert Level System

| Guard | Situation Modifier |
|------|:---:|
| Normal | +0 |
| Alert | −1 |
| Professional | −2 |

Each failure → Alert Level +1 (0→1→2→3 = discovered)

### Type Four: Social Contest — Stance Shift System

PC rolls 2d6 + Empathy (EMP) vs NPC rolls 2d6 + Will (WIL) (equivalent). NPC stance from −5 (hostile) to +5 (full trust). Four strategies: rational persuasion, emotional infection, threat/pressure, interest exchange.

### Type Five: Time Race — Progress Bar System

Set a target progress; each successful check advances 1-2 squares. Countdown consumes in sync.

| Pressure | Countdown | Situation Modifier |
|:---:|:---:|:---:|
| Light | −1/round | +0 |
| Moderate | −2/round | −1 |
| Urgent | −3/round | −1 |
| Extreme | −4/round | −2 |

---

## 3.3 Wounds and Death (no HP)

### Four-Level Progression

| Level | State | First-Aid Situation Modifier |
|:---:|------|:---:|
| 0 | Uninjured | — |
| 1 | **Minor Wound**: slight reduction | Easy (+2) |
| 2 | **Moderate Wound**: action limited | Normal (+0) |
| 3 | **Severe Wound**: action severely limited | Hard (−1) |
| 4 | **Near-Death**: dies within three minutes | Very Hard (−2) |

First Aid: 2d6 + Action (ACT) or Empathy (EMP) (take higher) + Situation Modifier

| Result | Effect |
|------|------|
| Full Success | Recover one level |
| Partial Success | Stabilized but with limits/aftermath |
| Failure | Worsen one level |

### Death = Loop Reset
- That loop ends immediately → Reset
- Fatigue +3, all unanchored information lost
- Body state fully reset (wounds gone)
- Near-Death reset → freely gain 1 piece of GM information

### Teammate Rescue
- **Take the hit:** Voluntarily take an attack meant for a teammate
- **Last moment:** When a Near-Death teammate has only the last minute left, first aid gets +2 Situation Modifier

---

## 3.4 Status Effects Quick Reference

| Status | Main Effect | Removal Method |
|------|------|------|
| Fatigue·Weary | Action Points (AP) −1, Anchor −1 | Fatigue recovery |
| Fatigue·Exhausted | Action Points (AP) −2, Anchor −2, Déjà Vu DC +3 | Fatigue recovery |
| Fatigue·Collapse | Character loses control | Will check or loop reset |
| Mild Panic | One check at Disadvantage | Successful Will check |
| Moderate Panic | All actions −1 | Will (Hard) or teammate soothing |
| Severe Panic | −2, cannot use special abilities | Teammate soothing or withdrawal |
| Minor Wound | Slight reduction | Rest or first aid |
| Moderate Wound | Action limited | First aid (Normal) |
| Severe Wound | Action severely limited | First aid (Hard) |
| Near-Death | Dies within 3 minutes | First aid (Very Hard) |
| **Resolve** | All checks +1, panic immunity | Lasts one scene |

---

## Appendix A: Glossary

| Term | Abbrev. | Note |
|------|:---:|------|
| Success Band | — | 6−Failure / 7-9 Partial Success / 10+ Full Success |
| Situation Modifier | — | GM-applied ± value to the roll based on difficulty |
| Critical Success | — | Natural 12 ("Boxcar") |
| Critical Failure | — | Natural 2 ("Snake Eyes") |
| Advantage/Disadvantage | — | 3d6 keep highest/lowest 2 |
| Memory Anchor | Memory Anchor Points (MAP) | Cross-loop information capacity = Memory (MEM) + ⌊Insight (INS)/2⌋ |
| Fatigue Threshold | Loop Fatigue Threshold (LFT) | Mental breakdown line = Will (WIL) × 2 + 5 |
| Daily Action Points | Daily Action Points (DAP) | Single-loop action budget = 8 + Action (ACT) modifier |
| Déjà Vu DC | Déjà Vu DC (DVD) | Intuition difficulty = 10 − exposure count (min 6) |
| Cognition Points | Cognition Points (CP) | Growth resource |
| World Degradation | — | GM penalty mechanism advancing with the loop |

## Appendix B: Core Formula Quick Reference

| Formula | Calculation |
|------|------|
| Attribute Modifier | Attribute Value − 2 |
| Memory Anchor Points (MAP) | Memory (MEM) + Insight (INS) ÷ 2 (rounded down) |
| Fatigue Threshold (LFT) | Will (WIL) × 2 + 5 |
| Daily Action Points (DAP) | 8 + (Action (ACT) − 2) |
| Déjà Vu DC (DVD) | 10 − exposure count (minimum 6) |

---

> **Time Loop TRPG Player Rules Book v1.0** | Tabletop Rules Studio
