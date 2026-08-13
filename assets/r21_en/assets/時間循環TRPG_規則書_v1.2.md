# Time Loop TRPG — Rules Book v1.2

> **Codename:** `timeloop-trpg` | **Version:** v1.2 (numeric balance fixes: Skeptic / fatigue reset / Blunt vs Sharp Weapon differentiation)
> **Tabletop Rules Studio** co-published
> **Core Engine:** 2d6 + Attribute Modifier (PbtA-style Success Bands)
>
> **Design Positioning:** A time-loop TRPG built around the core tension of "player knowledge carries across loops, character memory resets each time." Every death is a clue, every choice is a countdown—because the loop won't wait for you forever.

---

## Quick Start

### What You Need
- 2 six-sided dice (2d6)
- 1 ten-sided die (d10, for time jumps)
- 1 hundred-sided die (d100, for GM degradation rolls)
- Character sheet (see appendix)
- 3-4 players + 1 GM

### Core Concepts in 30 Seconds

| Concept | One-liner |
|------|--------|
| **Loop** | Time keeps resetting. After each death or specific event, everything returns to the start |
| **Memory Anchoring** | At loop end, you can "lock" a few pieces of information to carry into the next loop—but Anchors are never enough |
| **Player Knowledge ≠ Character Knowledge** | You remember everything, but your character wakes up blank each time—this is the core tension |
| **World Degradation** | The loop isn't free. With each reset, the world slightly breaks down |
| **Loop Fatigue** | Witnessing death, repeated failure—your mind accumulates trauma |
| **Truth Fragment** | The goal isn't "escape," but "understand why the loop exists" |

### Core Dice Rules (learn in 5 seconds)

```
Roll 2d6 + Attribute Modifier + Situation Modifier

6 or lower → Failure (not achieved, situation may worsen)
7-9      → Partial Success (goal achieved, but at a cost)
10 or higher → Full Success (goal achieved, no cost)
Natural 12   → Critical Success (perfect result beyond expectation)
Natural 2    → Critical Failure (disastrous consequence)
```

---

# Chapter One: Core Rules

## 1.1 Dice System: 2d6 + Modifier

This game uses a unified **2d6 + Attribute Modifier** engine. Every check—whether an attribute check, contest, social, insight, or fatigue recovery—uses the same adjudication logic.

### Success Bands (fixed, do not adjust the target value)

| Roll Result | Success Level | Narrative Meaning |
|---------|:---:|------|
| Natural 12 ("Boxcar") | **Critical Success** | Fortune favors you—a perfect result beyond expectation, extra reward |
| Adjusted ≥ 10 | **Full Success** | Goal achieved, no cost |
| Adjusted 7–9 | **Partial Success** | Goal achieved, but with a cost/complication/limited effect |
| Adjusted ≤ 6 | **Failure** | Goal not achieved, situation may worsen |
| Natural 2 ("Snake Eyes") | **Critical Failure** | Fortune turns—disastrous consequence |

### Difficulty Applied Through "Situation Modifier"

**Do not adjust the target value**; instead add or subtract from the roll result. This keeps GM adjudication intuitive.

| Difficulty | Situation Modifier | Full Success rate at Attribute +1 | Description |
|:---:|:---:|:---:|------|
| Easy | +2 | 58.33% | Almost impossible to fail |
| Normal | +0 | 27.78% | A competent practitioner can usually handle it |
| Hard | −1 | 16.67% | Even a skilled person faces a challenge |
| Very Hard | −2 | 8.33% | Requires professional training and luck |
| Nearly Impossible | −3 | 2.78% | Only top experts at their best can attempt |

### Advantage/Disadvantage

- **Advantage:** Roll 3d6, keep the highest 2 (about equivalent to +1.5 modifier)
- **Disadvantage:** Roll 3d6, keep the lowest 2 (about equivalent to −1.5 modifier)
- Advantage and Disadvantage present simultaneously → cancel out (roll normal 2d6)
- Multiple Advantage sources do not stack, same for multiple Disadvantage sources

### Contested Check

Both sides roll 2d6 + relevant Attribute Modifier; higher result wins. On a tie, the active side gets a "Partial Success" effect.

---

## 1.2 The Five Attributes

| Attribute | Abbrev. | Meaning | Role in the Loop |
|------|:---:|------|------|
| **Memory** | Memory (MEM) | Information retention, detail recall | Determines how many pieces of information can be "anchored" and carried back after each loop ends |
| **Insight** | Insight (INS) | Pattern recognition, contradiction detection | Detecting NPC behavior shifts, noticing signs of World Degradation |
| **Will** | Will (WIL) | Mental resilience, Loop Fatigue resistance | Resisting accumulation of Loop Fatigue, maintaining drive amid despair |
| **Action** | Action (ACT) | Physical ability, execution efficiency | Efficiency of task completion—loop time is limited, every turn is precious |
| **Empathy** | Empathy (EMP) | Understanding others, building relationships | Persuading NPCs, soothing teammate fatigue—but relationships reset each loop |

### Attribute Value → Modifier Mapping

| Attribute Value | Modifier | Narrative Meaning |
|:---:|:---:|------|
| 1 | −1 | Significant flaw—this area is your weak point |
| 2 | +0 | Ordinary level—natural state without special training |
| 3 | +1 | Capable—through training or innate gift (**human average**) |
| 4 | +2 | Excellent—a standout in this area |
| 5 | +3 | Legendary—performance near the human limit |

### Attribute Check Quick Reference

**Memory check scenarios:** Recall key lines an NPC spoke, reproduce routes walked in previous loops, identify whether a detail appeared in a previous loop, reconstruct a scene map mentally.

**Insight check scenarios:** Search a scene, notice NPC behavioral anomalies, find logical contradictions in the environment, solve puzzles/codes, perceive World Degradation.

**Will check scenarios:** Resist fear/madness, stay calm under high pressure, force yourself to face death, maintain long focus, self-regulate to recover fatigue.

**Action check scenarios:** Chase, stealth, pick locks, combat, move quickly, fine manipulation, complete tasks under time pressure.

**Empathy check scenarios:** Persuade NPCs, soothe teammates' Loop Fatigue, see through lies, quickly gain a stranger's trust, negotiate and trade.

---

## 1.3 Derived Attributes

| Derived Attribute | Abbrev. | Formula | Range | Use |
|---------|:---:|------|:---:|------|
| **Memory Anchor Points** | Memory Anchor Points (MAP) | Memory (MEM) + ⌊Insight (INS)/2⌋ | 1–7 | Number of pieces of information that can be locked and carried cross-loop at loop end |
| **Loop Fatigue Threshold** | Loop Fatigue Threshold (LFT) | Will (WIL) × 2 + 5 | 7–15 | Once fatigue exceeds this, stage negative effects trigger |
| **Daily Action Points** | Daily Action Points (DAP) | 8 + Action (ACT) modifier | 7–11 | Action Points available per loop |
| **Déjà Vu DC** | Déjà Vu DC (DVD) | 10 − exposure count (min 6) | 6–10 | Difficulty of intuitively sensing unanchored repeated information |

### Design Notes

**Memory Anchor Points:** The formula uses "Memory (how much you can remember) + half Insight (what you can recognize as worth remembering)." Average (MEM 3, Insight (INS) 3) = 4 Anchors—exactly covering the 4 most important discoveries in a loop, forcing players into strategic choices.

**Loop Fatigue Threshold:** Will × 2 reflects Will's leverage on fatigue resistance; +5 ensures even the lowest-Will character has a 7-point buffer. Average 11 points—roughly 5-7 major blows or 2-3 deaths before entering the first stage.

**Daily Action Points:** A base of 8 guarantees a minimally effective character can still take meaningful actions. Action modifier ±1-3 shows up within a single loop as about 2-3 extra actions. Each Action Point is roughly equal to 1-2 hours of narrative time in the game.

**Déjà Vu DC:** DC starts at 10, drops 1 per extra exposure, minimum 6. The check uses 2d6 + Insight (INS) modifier. This rewards players for repeatedly exploring the same scenes and dialogues—even without anchoring, repeated contact makes intuition sharper.

**Note:** The Déjà Vu check uses the Insight (INS) modifier—because Déjà Vu is "intuitively sensing the pattern match between the current scene and past experience," which is Insight's domain. This is the only mechanism in the system that uses a "contested DC" rather than "Success Bands."

### Complete Déjà Vu Check Rules

**When triggered:** When a character encounters information that is "not anchored, but experienced in a previous loop," the GM may proactively prompt or the player may request a Déjà Vu check.

**Roll:** `2d6 + Insight (INS) modifier`, contested against the Déjà Vu DC. DC = 10 − exposure count of that information this loop (minimum 6).

| Check Result | Effect |
|------|------|
| ≥ DC | **Déjà Vu triggered**—GM gives a hint at the corresponding level based on exposure count |
| < DC | Not triggered—didn't sense it this time (does not affect the DC decrement on later exposures) |
| Natural 12 | **Clear Flashback**—GM reveals full information + one extra detail |
| Natural 2 | **False Sense**—GM gives a seemingly reasonable but actually wrong feeling |

| Exposure Count | DC | Success rate at Insight (INS) +1 | Déjà Vu Level |
|:---:|:---:|:---:|------|
| 1st time | 10 | 28% | No sense—you've only seen it once |
| 2nd time | 9 | 42% | Faint—a vague sense of familiarity |
| 3rd time | 8 | 58% | Obvious—strong Déjà Vu, GM gives brief confirmation |
| 4th time | 7 | 72% | Clear—GM may give a concrete content summary |
| 5th+ time | 6 | 83% | Certain—even unanchored, your body remembers |

**Déjà Vu Information usage limit:** Information gained through Déjà Vu is only a "vague intuition" to the character. The character cannot take precise action based on Déjà Vu information—for example, "Déjà Vu tells you this NPC is lying," the character can only say "I feel this person is off," not "I'm certain he's lying about something."

---

## 1.4 Core Mechanics Overview

### Memory Anchoring System

At the end of each loop, players each perform anchoring:

| Step | Content |
|------|------|
| **1. Review** | Player lists all important information obtained this loop |
| **2. Choose** | Spend Memory Anchors to choose the information to lock (1 Anchor = 1 piece of information) |
| **3. Write** | Write the chosen information on the character sheet; next loop this information is "intuitively available" to the character |
| **4. Forget** | Unanchored information—the player still remembers, but the character does not |

**Anchor Strength:**

| Anchor Cost | Information Clarity | Usable As |
|:---:|------|------|
| 1 Anchor | Vague impression | "I feel it's better not to take that alley" |
| 2 Anchors | Clear memory | "That guard goes to smoke at 3 PM, the back door has a 5-minute window" |
| 3 Anchors | Full reproduction | Can draw the building interior map, write the code, recite the dialogue |

> Anchors are never enough to lock all information. The player must choose—remember "who the killer is" or remember "the escape route"?

### Player Knowledge vs Character Knowledge

| Information Type | Definition | Usable by Character? |
|------|------|:---:|
| **Anchored Information** | Information "locked" by spending Anchors at loop end | ✅ Treated as "strong intuition" or "a dream," usable by character |
| **Déjà Vu Information** | Not anchored, but triggered a successful Déjà Vu check on encounter | ⚠️ Only a vague hint ("you feel this person is off") |
| **Lost Information** | Neither anchored nor triggered Déjà Vu | ❌ Player knows but character does not—this is the test |

### Loop Degradation System

At the end of each loop, the GM secretly rolls d100 to determine degradation.

| Loop Count | Degradation Chance | Max Degradation Effect | World State |
|------|:---:|------|------|
| 1-3 | 0% | None | Stable—establish the baseline |
| 4-6 | 30% per loop triggers 1 degradation | Minor | Slight deviation |
| 7-9 | 60% per loop triggers 1-2 degradations | Obvious | Obvious distortion |
| 10-12 | 100% per loop triggers 2 degradations | Severe | Accelerating collapse |
| 13+ | Unpredictable (GM free reign) | Total collapse | World begins to lose its logic |

**Degradation Effect Types:**
- **Detail shift:** A door is locked this time, an item moved position
- **NPC behavior change:** A friendly NPC is cold this time, a witness disappears this time
- **Anomaly appears:** Something that shouldn't exist appears—a thirteenth bell toll, an extra person in the mirror
- **Time shortens:** The loop endpoint moves up two hours
- **Memory erosion:** NPCs begin to show "as if they remember the last round"

**Degradation Trigger and Perception:** The GM secretly rolls during step 4 of the settlement phase. Degradation effects appear **gradually in the next loop**—the GM need not announce all degradation at once, but let it surface naturally as scenes progress.

| Degradation Type | Check Required? | Perception Method |
|------|:---:|------|
| Detail shift | Required | Insight check (Normal +0); success notices the anomaly |
| NPC behavior shift | Auto/check | Obvious shift (drastic mood change) = auto-noticed; subtle shift (wording change) = requires a player who has had ≥2 prior interactions with that NPC to auto-notice |
| Anomaly appears | Auto | Directly described to all players |
| Time shortens | Auto | GM informs at loop start that Action Points (AP) −1 |
| Memory erosion | Auto | NPC directly speaks a cross-loop line—this is a narrative event |

**Fatigue trigger:** The player triggers "+1 fatigue for encountering degradation" in the scene where they **first clearly perceive** a degradation effect. At most 1 fatigue from degradation events per loop. **Characters with Insight ≥ +2** automatically get a free Insight check to perceive anomalies whenever degradation triggers.

### Loop Fatigue System

**Fatigue Accumulation (event-triggered, no roll):**

| Trigger Event | Fatigue Gain |
|------|:---:|
| Character death | +3 |
| Witnessing teammate death | +2 |
| Witnessing the death of an NPC with an established relationship | +1 |
| Key mission/plan failure | +2 |
| Encountering a World Degradation event | +1 |
| Prolonged high-pressure state | GM discretion +1 |

**Fatigue Stage Auto-Switch:**

| Fatigue Value Range | Stage | Effect |
|------|:---:|------|
| 0 – Loop Fatigue Threshold (LFT) | **Normal** | No negative effects |
| Loop Fatigue Threshold (LFT)+1 – Loop Fatigue Threshold (LFT)+5 | **Stage 1: Weary** | Action Points (AP) −1, Memory Anchor −1 |
| Loop Fatigue Threshold (LFT)+6 – Loop Fatigue Threshold (LFT)+10 | **Stage 2: Exhausted** | Action Points (AP) −2, Memory Anchor −2, Déjà Vu DC +3 |
| > Loop Fatigue Threshold (LFT)+10 | **Stage 3: Collapse** | Action Points (AP) −3, Memory Anchor −3, all checks at Disadvantage (3d6 keep low 2). Character cannot actively plan or initiate complex actions. At key choice moments, the GM may require a Will check (Normal +0): failure means the GM takes over the character for 1 scene (character acts emotionally or self-destructively); success means the character briefly rallies (regains normal check ability for this scene). If fatigue still > Loop Fatigue Threshold (LFT)+10 after the next loop resets, they re-enter Collapse starting from the second scene. |

**Fatigue Recovery:**
- Empathy soothing (teammate rolls 2d6 + Empathy (EMP) modifier): Partial Success recovers 1, Full Success recovers 2
- Will self-heal (self rolls 2d6 + Will (WIL) modifier, spends 2 Action Points (AP)): Partial Success recovers 1, Full Success recovers 2
- Successfully piecing together a Truth Fragment: −3 fatigue
- Successfully saving someone who died in a previous loop this loop: −4 fatigue
- Discovering a new hope clue: −2 fatigue
- Doing a completely unrelated small thing (coffee and sunset): −1 (once per loop)
- Loop Reset: fatigue returns to zero

> **Fatigue is an in-loop resource, not a cross-loop punishment.** Fatigue fully clears at the start of each new loop. Its role is to create tension *within* each loop—making you careful in *this* loop, rather than accumulating despair across loops. The truly cross-loop accumulated pressures come from **Degradation** (the world grows more twisted) and **insufficient Anchors** (you know more and more but can always carry away less).

### Truth Fragment System

In scenario design, the GM breaks the truth into **8 Truth Fragments**.

| Fragment Type | Acquisition Method | Example |
|------|------|------|
| Character Fragment | A specific NPC's hidden dialogue, dying words | "The mayor actually knew the truth of the mine disaster 15 years ago" |
| Location Fragment | Appearing at a specific location at a specific time in the loop | "At midnight, cries come from the church basement" |
| Event Fragment | Triggering a specific condition in the loop | "If you stop A and B from arguing, C won't commit suicide" |
| Paradox Fragment | Two contradictory facts simultaneously true | "The mayor is both drinking at the tavern and praying at the church—at the same time" |
| Key Item | An item that exists only in specific loops | A diary whose contents differ each loop |

**Truth Puzzle Completion:**

| Completion | Fragment Count | Ending Quality |
|------|:---:|------|
| 25% | 2-3 | Barely escape, but don't know why |
| 50% | 4-5 | Escape and understand part of the truth |
| 75% | 6-7 | Fully understand the whole event, can choose different endings |
| 100% | 8 | Not only understand the truth, but can "repair" the cause of the loop—true ending |

---

## 1.5 Loop Settlement Phase (fixed process)

Regardless of how the loop ends (death, time exhausted, voluntary reset), the GM must execute the settlement in this order. **Dead characters also fully participate in settlement.**

```
┌──────────────────────────────────────────┐
│            Loop Settlement Phase (5 steps)  │
│                                          │
│  1. Review: all players review key finds   │
│  2. Anchor memory: each spends Anchors     │
│  3. Truth Fragment confirm: GM confirms     │
│  4. World Degradation roll: GM secretly     │
│     rolls d100                              │
│  5. Loop Fatigue settle: tally gain/loss     │
│     + judge stage                           │
│                                          │
│  → Enter the N+1th loop                     │
└──────────────────────────────────────────┘
```

| Step | Executor | Operation |
|:--:|------|------|
| 1. Review | All players | Each player publicly states their 1-3 most important finds this loop. GM confirms the team memory pool update. |
| 2. Anchor memory | Each player | Each spends Memory Anchors, writing chosen information onto the character sheet. **Dead characters also participate in this step** (death does not strip anchoring rights). |
| 3. Fragment confirm | GM | GM announces "which Truth Fragments were formally discovered this loop." Recorded in the team puzzle tracking sheet. |
| 4. Degradation roll | GM (secret) | Roll d100 to determine degradation. Results appear gradually next loop as environmental anomalies / NPC shifts. |
| 5. Fatigue settle | All | Tally this loop's fatigue gain/loss (death +3, NPC death +1, etc.), judge whether a new stage is entered. **Note: fatigue returns to zero at next loop start**—but if it ended in Stage 3 (Collapse), all checks −1 within the first 1 scene of the next loop. |

---

# Chapter Two: Character Creation

## 2.1 Creation Process (6 steps)

```
Step 1 → Step 2 → Step 3 → Step 4 → Step 5 → Step 6
 Background   Attribute Allocation   Time Attitude   Core Relationship   Starting Information   Starting Equipment
```

### Step 1: Background — Who Are You?

Before you were trapped in the loop, you were an ordinary person. Answer these questions:

| # | Question |
|---|------|
| 1 | **Who are you?** (name, age, occupation/identity) |
| 2 | **What were you doing before you were trapped in the loop?** |
| 3 | **What is your last clear memory?** |
| 4 | **What about you makes you different?** (optional) |
| 5 | **In the place where this loop happens, what is your most important daily habit?** |

**Background Examples:**

| Background Type | Typical Identity | Background Advantage (narrative) | Starting Information Tendency |
|------|------|------|------|
| **Enforcer** | Police, security, soldier | Knows town geography and people | Info related to order, security |
| **Seeker** | Teacher, journalist, researcher, student | Habit of observing and recording | Info related to information, documents |
| **Caregiver** | Doctor, nurse, social worker, parent | Understands others' vulnerabilities and secrets | Info related to NPC private lives |
| **Laborer** | Worker, driver, clerk, cook | Knows the city's "backstage" | Info related to locations, item positions |
| **Outsider** | Drifter, artist, outsider | Goes unnoticed | Info related to taboo, anomalies |
| **Connected** | Townsfolk, acquaintance, relative | Has a personal relationship with a key NPC | Info related to NPC past |

### Step 2: Attribute Allocation

**Attribute range: 1-5.** Three allocation plans available:

**Plan A: Standard Array (recommended for beginners)**
```
[3, 2, 2, 2, 1] (total 10 points)
```
You have one thing you're good at, and one thing you're clearly not.

**Plan B: Point-Buy (recommended for experienced players)**
```
Start: all attributes from 1 (total 5)
Points available: 5 (target total ~10)
Each +1 attribute costs 1 point (1→2→3→4)
From 4 to 5 costs 2 points
```

| Point-Buy Example | Memory | Insight | Will | Action | Empathy |
|------|:---:|:---:|:---:|:---:|:---:|
| Balanced | 2 | 2 | 2 | 2 | 2 |
| Focused | 3 | 2 | 2 | 2 | 1 |
| Bimodal | 3 | 3 | 2 | 1 | 1 |
| Specialized | 4 | 2 | 2 | 1 | 1 |

**Plan C: Free Allocation (requires GM approval)**
```
Total range: 9-11 points
All attributes: 1-5
```

### Step 3: Time Attitude — Your Relationship with the Loop

**This is the most core character choice.** Time Attitude determines how you view the loop, how you respond to pressure, and grants unique mechanical effects.

| Attitude | One-liner | Core Gain | Core Cost | Special Ability |
|------|------|------|------|------|
| **Optimist** | "Every time I wake up, it's a new chance" | −1 fatigue when discovering fragments | — | Light of Hope: once per loop, teammate gains Advantage on Will checks |
| **Skeptic** | "Nothing is right, no one can be trusted" | Insight check Advantage (limited to investigation: search/notice shift/Déjà Vu/solve puzzle—combat perception gets no advantage) | Empathy check Disadvantage | Eye for Flaws: once per loop, force GM to reveal contradiction in NPC's words |
| **Guardian** | "This time, I'm going to get everyone out alive" | +2 recovery when saving someone | +1 when witnessing death | Guardian Instinct: when Core Relationship NPC is in danger, auto-sense + free move |
| **Fatalist** | "The loop isn't a curse, it just happens" | Fatigue Threshold +5 | Memory Anchor −1 (minimum 1) | Gift of Fate: once per loop, fatigue does not increase → instead temporary Anchor +1 |
| **Curious** | "That NPC's sock color today is different from yesterday!" | Memory Anchor +1 | Degradation fatigue +1 | Detail Hunter: once per loop, ask the GM a specific observation question |

### Step 4: Core Relationship — The Person You Must Save

Choose one person from the scenario's key NPC list. This NPC is the person you care most about in the loop.

**Mechanical Effect:**
- If you try to save the Core Relationship NPC and succeed, fatigue recovery +2 (on top of base recovery)
- If the Core Relationship NPC dies this loop and you failed to prevent it, fatigue +2
- The Core Relationship NPC cannot be "abandoned"

**Guiding Questions:**
1. What is your relationship? (specific—not "friend," but "college roommate, lent him 30k and never got it back")
2. What do you owe them? Or what do they owe you?
3. If you could say one last sentence to them, what would it be?

### Step 5: Starting Information

Based on your background and Core Relationship, the GM grants **1-2 pieces of Starting Information**. This information is "things the character should already know before the loop began"—unlike the Hidden Information Card, Starting Information is public.

### Step 6: Starting Equipment

**Common Equipment:** Everyday clothes, phone (can photograph/record/take notes, cannot dial out), wallet/ID, key ring.

**Background Bonus:**
- Enforcer: badge/ID, cuffs, notepad, walkie-talkie
- Seeker: notebook and pen, voice recorder/camera
- Caregiver: simple first-aid kit, work ID
- Laborer: toolbox, gloves, practical knife (not a weapon)
- Outsider: sketchbook or diary, telescope or old camera, a meaningful small object
- Connected: an item related to the Core Relationship NPC (group photo, letter, keepsake)

---

## 2.2 Hidden Information Card

Each player secretly draws an "information card known only to themselves" at character creation. Only the card-holding player and the GM know its content.

| No. | Name | Type | Core Content |
|:--:|------|------|------|
| #1 | Figure | Visual anomaly | Saw a figure before the loop began... not sure if it was a hallucination |
| #2 | Grudge | Social secret | Had a grudge with some NPC before the loop |
| #3 | The Culprit? | Guilt/responsibility | Vaguely feel... this loop was caused by you? |
| #4 | Reflection | Visual anomaly | Found your reflection a moment slower than yourself |
| #5 | Slowing Watch | Temporal anomaly | Your watch is 2 seconds slower each loop wake-up |
| #6 | Unanswered Confession | Social secret | The day before the loop began, an NPC confessed to you—still unanswered |
| #7 | Future Diary | Memory anomaly | A page was added to the diary—your handwriting, but you don't remember writing it |
| #8 | Premonition Dream | Premonition/fate | Two days before the loop began, had an identical nightmare |
| #9 | The Thing You Can't Say | Social secret | There's a secret, related to some NPC, that would change everything if spoken |
| #10 | One More Person | Memory anomaly | There should be another person in the loop—but they never appeared after the second loop began |
| #11 | Smell of Burning | Temporal anomaly | Every fourth hour of the loop, you smell something burning—only you can smell it |
| #12 | The Mark on Your Body | Memory anomaly | A mark on your body that grows slightly larger each loop |

### Hidden Information Card GM Usage Principles

| Principle | Note |
|------|------|
| **Confidentiality** | Card content is known only to the card-holding player and the GM. Other players (including teammates) should not know. |
| **Voluntary disclosure** | The player decides when to reveal. GM does not force—but may create "natural disclosure" opportunities in the narrative. |
| **Truth calibration** | Before dealing cards, the GM should confirm the card content is compatible with the scenario. Adjust details if necessary. |
| **Not guaranteed true** | Some cards may be the character's illusion, guilt, or a product of World Degradation—not necessarily "confirmed." |
| **Paired distribution** | The GM may give potentially related cards to different players. For example #2 (Grudge) and #9 (Thing You Can't Say) may point to the same NPC. |
| **One card per person** | Cannot be changed or exchanged. |

---

## 2.3 Cross-Loop Growth: Cognition Points System

Characters have no levels. Growth is achieved through **Cognition Points (CP)**.

**Cognition Points (CP) Acquisition:**

| Source | Cognition Points (CP) | Note |
|------|:---:|------|
| Discover a Truth Fragment | +1 | Character personally participated in discovery |
| Loop settlement: major breakthrough | +1 | GM judgment, at most once per loop |
| Save a key NPC (first time) | +2 | Once per NPC |
| Moment of insight | +2~4 | GM triggered (at specific plot nodes) |
| Team puzzle 50%/75%/100% | +2/+2/+4 | Team shared achievement |

**Cognition Points (CP) Spending:**

| Spend Item | Cognition Points (CP) Cost | Limit |
|------|:---:|------|
| Raise attribute +1 | New value × 3 | Max 5 |
| Unlock second Time Attitude special ability | 5 | Once per person |
| Increase base Memory Anchor +1 | 4 | Max +2 |
| Gain cross-loop skill | 3 | Max 2 |
| Lower base Déjà Vu DC −1 (10→9) | 3 | At most once |
| Fatigue Threshold +2 | 3 | Max +6 |

**Cross-Loop Skill Table:**

| Skill Name | Cognition Points (CP) | Effect |
|------|:---:|------|
| Time Sense | 3 | Sense current time without a clock; +1 to action checks in time-race scenes |
| Body Memory | 3 | Routes once walked can be reproduced by body memory even if unanchored; +1 Déjà Vu check |
| Speed Reading | 3 | Can examine one extra item during investigation without spending extra Action Points (AP) |
| Mind Notes | 3 | Once per loop, "freely" anchor one piece of information (no Anchor spent) |
| Crisis Reflex | 3 | Advantage on action checks when facing an identical threat |
| Face Memory | 3 | Can remember an NPC's face and basic info even if not anchored |
| Fatigue Management | 3 | Once per loop, a small recovery action costs no Action Points (AP) |
| Team Sync | 3 | Can send a brief message to a teammate with one quick action |

---

## 2.4 Cross-Loop Item Rules

| Item Type | Behavior on Loop Reset |
|------|------|
| Default Equipment | Returns to loop-start state |
| Ordinary items obtained in the loop | Disappear—not on you at loop start |
| **Anchored Item** | Retained—spend 1 Memory Anchor to lock, carried cross-loop |
| Key Plot Item | GM decides |

**Anchored Item:** Spend 1 Memory Anchor to anchor an item you are holding. After anchoring, the item appears on you at the next loop wake-up. There is a resource trade-off between Anchored Items and Anchored Information—your Anchors are never enough.

---

# Chapter Three: Action and Conflict

## 3.1 Action Point Economy

```
Daily Action Points = 8 + Action (ACT) modifier (ACT modifier = Action attribute − 2)
```

| Action Attribute | Modifier | Daily Action Points (AP) |
|:---:|:---:|:---:|
| 1 | −1 | 7 |
| 2 | +0 | 8 |
| 3 | +1 | 9 |
| 4 | +2 | 10 |
| 5 | +3 | 11 |

### Action Categories and Action Points (AP) Cost

| Action Category | Action Points (AP) | Note | Example |
|------|:---:|------|------|
| **Instant Action** | 0 | Completed instantly | Notice blood on the floor, exchange a glance with a teammate, remember a door number |
| **Quick Action** | 1 | Brief, low-risk | Quickly walk to the next room, swiftly scan a document title, say one line to an NPC |
| **Standard Action** | 2 | Requires focus, or risky | Carefully search a room, deep conversation with an NPC, pick a lock, treat |
| **Full Action** | 3 | Time-consuming, high-investment | Travel from one end of town to the other, thoroughly comb the archive room, long persuasion of an NPC |
| **Cross-zone Action** | 4 | Cross large map blocks | From in-town to outskirts, to a new area on the map |

### Loop Phases and Action Windows

A day's Action Points (AP) are not forced to be allocated by phase, but different phases have limits on "action types usable":

| Phase | Usable | Restriction |
|------|------|------|
| **Morning** | Organize info, review memory, make plans | No long-distance movement, no interaction with unawakened NPCs |
| **Daytime** | All action types | No restriction (main action window) |
| **Dusk** | Limited actions | Fixed plot events occur, time pressure increases |
| **Night** | Last chance | Most locations closed, social opportunities gone, danger rises |

Action Points (AP) **do not accumulate across days**. After a loop reset, Action Points (AP) return to the initial value (unless fatigue causes a −1/−2 modifier).

**Multi-day loop Action Points (AP) usage:** For 3-day or 7-day loops, Action Points (AP) are calculated independently each day. The GM should announce the available Action Points (AP) at the start of each "day."
- **Day 1 Action Points (AP) fully spent** → does not affect Day 2 Action Points (AP) (independent calculation)
- **Fatigue-caused Action Points (AP) reduction** → affects all remaining days of that loop (e.g., if Day 2 enters Weary stage, then remaining Day 2 time + all of Day 3 Action Points (AP) −1)
- **The narrative boundary of a "day"** → preset by the GM in scenario design. Most scenarios use "sleeping at night" or "a fixed event" as the day boundary.

---

## 3.2 Five Types of Conflict

> **Core Principle:** The goal of all conflict is not "reduce the opponent's Hit Points (HP) to zero," but "achieve your purpose." Death resets everything—but psychological trauma (fatigue value) does not disappear.

### Type One: Physical Contest (chase, shove, grab)

**Three-Round Contest:** Both sides roll 2d6 + Action (ACT) modifier; whoever wins two of three rounds achieves the goal.

| Round | Winner Effect | Tie Effect |
|------|------|------|
| Round 1: Burst | Gains initiative, next round Situation Modifier +1 | Stalemate |
| Round 2: Struggle | Advances goal 50% | Slight advance |
| Round 3: Decisive | Achieves goal | Partial achievement (GM adjudicates cost) |

Action Points (AP) cost: 1 Action Point (AP) per round (max 3 Action Points (AP)), may choose to give up after any round.

### Type Two: Violent Conflict

**Instant Resolution:**

```
1. All participants roll initiative: 2d6 + Action (ACT) modifier, higher goes first
2. Attacker rolls: 2d6 + Action (ACT) modifier + weapon modifier + situation modifier
   Defender rolls: 2d6 + Action (ACT) modifier (dodge)
3. Compare results:
   - Attacker > Defender → Full hit (+2 wound level)
   - Tie → Partial hit (+1 wound level)
   - Defender > Attacker → Full dodge
```

**Attack Types:**

| Attack Type | Situation Modifier | Base Damage | Special |
|------|:---:|:---:|------|
| Unarmed attack | Normal (+0) | Minor Wound | — |
| Unarmed vital | Hard (−1) | Moderate Wound | After hit, defender's next-round Action (ACT) −1 |
| Blunt Weapon | Normal (+0) | Moderate Wound | Full hit → defender's next-round Action (ACT) −1 (stun); partial hit → may upgrade to Severe Wound |
| Sharp Weapon | Normal (+0) | Moderate Wound | Full hit certain upgrade to Severe Wound |
| Firearm (extremely rare) | Very Hard (−2) | Severe Wound | Full hit directly Near-Death |

> **Blunt Weapon vs Sharp Weapon:** The advantage of the Blunt Weapon is control (weakens the opponent after a hit), the advantage of the Sharp Weapon is lethality (causes Severe Wounds faster). The choice depends on whether you want to subdue or kill—in a time loop, the former is often wiser.

### Type Three: Stealth Hiding

**Alert Level System:** The GM sets the Situation Modifier.

| Guard Quality | Situation Modifier |
|------|:---:|
| Normal guard | Normal (+0) |
| Alert guard | Hard (−1) |
| Professional security | Very Hard (−2) |

Each failed check → Alert Level +1 (0→1→2→3 = discovered). Distractions can lower the Alert Level.

### Type Four: Social Contest

**Stance Shift System:** PC rolls 2d6 + Empathy (EMP) modifier vs NPC rolls 2d6 + Will (WIL) (equivalent) modifier.

NPC stance ranges from −5 (extreme hostility) to +5 (full trust), shifting 1-2 points per successful interaction. Four strategies available: rational persuasion, emotional infection, threat/pressure, interest exchange—different NPCs resist different strategies differently.

**Simplified Mode:** NPC fixed resistance = 10 + Will (WIL) modifier + stance difficulty modifier.

### Type Five: Time Race

**Progress Bar System:** Set a target progress (e.g. "accumulate 8 successes before the countdown ends"). Each successful check advances 1-2 squares of progress. Countdown and actions consume in sync.

| Pressure Level | Countdown per Round | Check Situation Modifier |
|:---:|:---:|:---:|
| Light | −1 square | Normal (+0) |
| Moderate | −2 squares | Hard (−1) |
| High | −3 squares | Hard (−1) |
| Urgent | −4 squares | Very Hard (−2) |
| Extreme | −5 squares | Nearly Impossible (−3) |

---

## 3.3 Wounds and Death

### No Hit Points (HP) System: Four-Level Progression

| Level | Name | State | Recovery |
|:---:|------|------|------|
| 0 | Uninjured | Normal | — |
| 1 | **Minor Wound** | Slight reduction, doesn't affect most actions | Brief rest or loop reset |
| 2 | **Moderate Wound** | Action limited, some actions cannot be performed | Requires first aid (Normal +0) |
| 3 | **Severe Wound** | Action severely limited, may be unable to move | Requires first aid (Hard −1) |
| 4 | **Near-Death** | At death's door, dies within three minutes | Requires first aid (Very Hard −2) |

**First Aid:** Roll 2d6 + Action (ACT) modifier (or Empathy (EMP) modifier, take higher) + Situation Modifier.

| Wound | Situation Modifier | Full Success | Partial Success | Failure |
|------|:---:|------|------|------|
| Minor Wound | Easy (+2) | Fully recovered | Partially recovered | Not recovered |
| Moderate Wound | Normal (+0) | Stabilized (recover to Minor Wound) | Stabilized but limited movement | Worsens |
| Severe Wound | Hard (−1) | Stabilized (recover to Moderate Wound) | Stabilized but with aftermath | Worsens to Near-Death |
| Near-Death | Very Hard (−2) | Recover to Severe Wound | Stabilized but may worsen every minute | Death |

### Death = Loop Reset

**Individual Death Rules:**
1. After a character dies, that player cannot continue acting—but may still participate in table discussion and advise teammates.
2. Other surviving players **continue the current loop**. The loop does not force-end on a single death.
3. The dead character fully participates in the **settlement phase** (anchor memory, fatigue settlement). Death does not skip settlement.
4. At next loop start, the dead character wakes at the start point with everyone else (body fully reset, wounds gone).
5. Death → fatigue +3; all unanchored information lost.

**Full Team Death (wipeout):**
1. All player characters dead → loop ends immediately.
2. Degradation accelerates 2 steps (wipeout has bigger impact). Full team still fully participates in settlement.
3. At next loop start, the GM gives the team a "collective Déjà Vu"—a wordless eye-contact sharing of a vague intuition.

**Voluntary Reset (suicide):**
- Single suicide: that player immediately ends participation, returns at settlement.
- Full-team agreed suicide: executed after all confirm. Same cost as single.

| Loop | Suicide Restart Cost |
|:--:|------|
| 1-3 | Information obtained this loop cannot be anchored |
| 4-6 | Above + degradation accelerates 1 step |
| 7-9 | Above + one random NPC permanently degrades 2 levels |
| 10-12 | Above + loop cap −1 |
| 13 | Suicide restart not allowed |

**Near-Death Memory:** When a character enters settlement in Near-Death state (wound level 4), the GM gives 1 extra clue from their perspective—not a full fragment, but a hint only the Near-Dead can "see." Example: "In the blurred last instant of consciousness, you see the clock on the clock tower has stopped. Stopped for a long time. Maybe it never moved."

### Teammate Rescue

- **Take the hit:** Voluntarily take an attack about to hit a teammate, automatically take the damage
- **Last moment:** When a Near-Death teammate has only the last minute left, the rescuer gets a +2 Situation Modifier first-aid check

---

## 3.4 Status Effects Quick Reference

| Status | Source | Main Effect | Removal Method |
|------|------|------|------|
| **Loop Fatigue·Stage 1** | Fatigue ≥ Loop Fatigue Threshold (LFT)+1 | Action Points (AP) −1, Memory Anchor −1 | Fatigue recovery |
| **Loop Fatigue·Stage 2** | Fatigue ≥ Loop Fatigue Threshold (LFT)+6 | Action Points (AP) −2, Memory Anchor −2, Déjà Vu DC +3 | Fatigue recovery |
| **Loop Fatigue·Stage 3** | Fatigue > Loop Fatigue Threshold (LFT)+10 | Character loses control | Will check or loop reset |
| **Mild Panic** | Triggered by anomaly | One check at Disadvantage | Successful Will check |
| **Moderate Panic** | Triggered by world distortion | All action checks −1 | Will (Hard) or teammate soothing |
| **Severe Panic** | Teammate death / spatial collapse | Checks −2, cannot use special abilities | Teammate soothing or scene withdrawal |
| **Minor Wound** | Violence/accident | Slight reduction | Rest or first aid |
| **Moderate Wound** | Violence | Action limited | First aid (Normal) |
| **Severe Wound** | Severe violence | Action severely limited | First aid (Hard) |
| **Near-Death** | Extreme violence | Dies within 3 minutes | First aid (Very Hard) |
| **Resolve** | Gain a Truth Fragment / save an NPC | All checks +1, panic immunity | Lasts one scene |

---

# Chapter Four: World and Narrative

## 4.1 Meta-Worldview: Rift Theory

The time loop is not magic, nor is it divine punishment. It is the spontaneous fracture of reality's structure under extreme emotional pressure.

**Core Principle:** When a single moment carries too much emotional energy—an irrecoverable death, a truth that cannot be spoken, an ending that cannot be accepted—reality fractures at that point. The rift tears that moment out of the flow of time, forming an enclosed loop interval.

The loop is not punishment, but reality's attempt to "heal" itself. Each loop is reality making a tiny adjustment, trying to find a path that can heal the rift.

**Loop Dynamics:**
- The loop is sustained by the "Anchor Event"—that is the source of the rift
- On each loop reset, all NPC memories reset except for the "Anchor Person"
- Players' memories can be carried across loops—a signal from the rift seeking outside help
- The boundaries of the loop interval are fixed: there may be a geographic range, a time range, or a spatial range

**Who controls the loop?** No one. The loop is a natural phenomenon. This means there is no "final boss," and you cannot end it by "killing the controller." The only way to end the loop is to "heal the rift"—resolve that original, unbearable moment.

### Unified Setting Elements

| Concept | Definition |
|------|------|
| **Anchor** | The core of the rift—the original "unbearable moment." Find the Anchor = find the key to ending the loop |
| **Degradation** | Loss of reality's structural stability after each loop—physical shifts, causal breaks, NPC distortion |
| **Déjà Vu** | NPCs' unconscious residue of previous loops—a vague "feeling," not true memory |
| **Awakened One** | A person who can retain memory in the loop. Player characters are typical Awakened Ones |
| **Loop Fatigue** | The psychological pressure borne by the Awakened One—unlike physical fatigue (which resets), Loop Fatigue is cumulative |

### Tone

**Core Tone: Persistence amid despair.** The emotional core of this game is not horror, but existential tenderness.

> You have watched the same person die twelve times. You remember every word they said before dying. But they don't remember you. The twelfth time, you no longer try to save them—you just sit beside them, quietly listening until they finish that sentence. You know they'll say it a thirteenth time. But you listen anyway. That is the tone of this game.

---

## 4.2 GM Running Guide

### Loop Management

The GM prepares a simple page per loop:

```
Loop #___  │  Degradation Level: ___  │  Special Event: ___________
————————————
This loop's player action summary:
  Time Slot 1: ___________
  Time Slot 2: ___________
  Time Slot 3: ___________
Truth Fragments obtained: ___________
NPC behavior shift record: ___________
This loop's ending: □ Natural end  □ Player death  □ Voluntary reset
Leftover clues: ___________
```

Also prepare a cross-loop summary sheet to track global state (degradation level, fragment count, NPC shift values, key items, special events).

### Information Control: Handling "Metagaming"

**Core Principles:**
- Loops 1-3: The character must obtain clues in this loop to act
- Loops 4-6: Players may propose "intuitive actions," GM decides if reasonable
- Loops 7-9: Most cross-loop knowledge can be rationalized through "Déjà Vu"
- Loop 10+: Fully open

**GM Phrasing Examples:**

| Player Says | GM Response |
|--------|---------|
| "I know he'll appear at the dock at that time" | "Your character has a strange feeling that the dock might be an important place. Will you go?" |
| "Don't talk to him, he lied to us last time" | "You look at this person's face and feel an inexplicable unease. What do you want to do?" |
| "Just go to the basement, the code is 1945" | "You stand before the door. Your fingers move involuntarily toward the code lock—as if your body remembers something your mind does not." |

**Key Technique: Turn metagaming into a worldview element.** Not "you can't do that," but "why can you do that—because the loop is changing you."

### Pacing Control: The Four-Stage Narrative Arc

| Stage | Loop | Player Mindset | GM Goal | Pacing |
|------|:--:|------|------|:--:|
| **Exploration** | 1-3 | "What happened here?" | Build the world, plant seeds | Slower |
| **Optimization** | 4-6 | "Let me optimize every step" | Allow attempts, deepen relationships | Accelerating |
| **Truth** | 7-10 | "We're about to know" | Puzzle takes shape, emotional pressure | Slow then sudden |
| **Endgame** | 11-13+ | "This is the last chance" | Endgame pressure, emotional release | Extremely tense |

### Handling "Suicide Restart"

**Not forbidden, but there must be a cost:**

| Loop | Cost |
|:--:|------|
| 1-3 | Information lost (memory pool cannot record) |
| 4-6 | Above + degradation accelerates 1 step |
| 7-9 | Above + random NPC permanently degrades 2 |
| 10-12 | Above + loop cap −1 |
| 13 | Suicide restart not allowed |

Every suicide should be a narrative moment. The GM should reveal something new in the suicide scene—not to reward suicide, but to make it part of the story.

### Team Memory Pool (complete rules)

**Concept:** The team memory pool is the cross-loop information collection held jointly by the player group—both a physical table tool (whiteboard/sticky notes) and a lightweight game rule.

**Information Sharing Rules:**

| Sharing Type | Rule |
|------|------|
| **Anchored Information sharing** | Players may verbally tell teammates their anchored information at any time. After receiving it, teammates get DC −2 on the Déjà Vu check for that information next loop (easier to trigger). Teammates cannot write that information into their character sheet as their own anchored information—what they gain is "secondhand intuition." |
| **Déjà Vu Information** | Cannot be shared. "I feel something's off" can't make a teammate feel off too. |
| **Starting Information** | Automatically enters the team memory pool (public information). |
| **Hidden Information Card** | Player decides when to reveal. After revelation, automatically enters the team memory pool. |

**Team Puzzle Calculation:** All Truth Fragments individually discovered by players sum to the team's total fragment count. Puzzle completion is based on the team total (not every person needs to find all fragments).

**Physical Presentation:**
- 🟡 Yellow = Confirmed fact
- 🔵 Blue = Hypothesis (to be verified)
- 🔴 Red = Urgent/critical
- 🟢 Green = Resolved/disproven

Let players maintain it together. **Separating "facts" from "hypotheses" is the memory pool's most important function.**

### Loop Echoes

Never say "same as last time." Even if the scene is 90% identical, find the 10% difference and amplify it:

- 1st time: First experience, full description
- 2nd time: Detail discovery—"last time you didn't notice the vase in the corner"
- 3rd time: Emotional layer—"when he spoke that line, you noticed his right hand trembles slightly"
- 4th time: Meaning shift—"same conversation, but now you know what he did last night"
- 5th+ time: Beyond the scene—"what you hear is not the content of the words—but the apology unspoken for thirty years behind them"

---

## 4.3 NPC Design System

### Behavior Baseline Card Template

Each key NPC needs a "first-loop behavior baseline" set during scenario station prep:

```
NPC Name: ______  Role Position: ______

[Surface Persona]
  Occupation/identity: ______  Age: ______
  Public personality: ______  Hidden personality: ______

[First-Loop Baseline]
  Fixed action schedule:
    Time A: ___________
    Time B: ___________
    Time C: ___________

  Key dialogue baseline (the 3 most important lines):
    1. ___________
    2. ___________
    3. ___________

  Emotional baseline: ______/10 (5 = calm)
  Trust baseline: toward players ______/10
  Secret baseline: ___________

[Relationship to the Anchor]
  Direct relationship / indirect relationship / how much they know / why they deny it

[Degradation Sensitivity]
  □ Low (+0 shift check) — unrelated to the Anchor
  □ Medium (+10) — indirectly related to the Anchor
  □ High (+20) — direct participant in the Anchor
  □ Extreme (+30) — the Anchor Person itself
```

### d100 NPC Behavior Shift Table

At the start of each new loop, the GM rolls a shift check for each key NPC:

```
Shift check = d100 + degradation level modifier + NPC degradation sensitivity modifier

Degradation level modifier: Lv1 −10 / Lv2 +0 / Lv3 +10 / Lv4 +20 / Lv5 +30
```

| d100 (after modifier) | Shift Type | Effect |
|:---:|:---:|------|
| ≤10 | **No shift** | NPC acts exactly by baseline |
| 11-30 | **Minor shift** | Habit action/wording/emotion slightly changes |
| 31-50 | **Moderate shift** | Time/emotion obviously changes |
| 51-70 | **Significant shift** | Déjà Vu fit / memory fragment / role inversion |
| 71-85 | **Severe shift** | Cross-loop dialogue / truth leak / temporal confusion |
| 86-100 | **Extreme shift** | Freeze / edge of awakening / reversal |
| 101+ | **Truth Collapse** | NPC directly states the truth—then disappears after speaking |

### NPC Memory Residue (Loop 10+)

Triggers only when loop count ≥ 10, the NPC is directly associated with the Anchor, and the NPC had "meaningful interaction" with players in previous loops. Roll d6:

| d6 | Memory Residue Type |
|:--:|------|
| 1 | **Echo:** NPC repeats a line they spoke in a previous loop, word for word |
| 2 | **Emotional residue:** NPC has an unexplained emotion toward the player (fondness or hostility) |
| 3 | **Scene flashback:** NPC describes a scene that happened in a previous loop, but believes it was a dream they had |
| 4 | **Trigger-word reaction:** NPC has a strong reaction to a specific word or name |
| 5 | **Precognitive residue:** NPC reacts before the event happens |
| 6 | **Half-awakening:** NPC realizes the loop exists—lasts one minute, then forgets |

---

## 4.4 Scenario Design Template

```
═══════════════════════════════════
Scenario Name: ______
Loop Length: ______ days/hours
Loop Endpoint: ______
Starting Moment: ______
═══════════════════════════════════

I. Core Truth
  Anchor Event: ___________
  Surface Story: ___________
  True Story: ___________
  Rift-Healing Conditions: ___________
  Awakening Trigger: ___________
  ※ Why do players wake in the loop? What is their emotional resonance with the rift?
  ※ Each player's awakening reason should echo their background and Core Relationship.

II. Truth Fragments × 8
  Fragments 1-8 (content/type/acquisition method/difficulty)

III. Key NPCs (3-5 people)
  NPC-1 (behavior baseline card)
  NPC-2 (behavior baseline card)
  ...

IV. Daily Event Table

V. Degradation Roadmap (loops 1-13)

VI. Key Items

VII. Ending Panel (at least 3)
  Ending A (perfect) / B (ordinary) / C (bad) + dissipation ending

VIII. Hidden Information Cards (matching player count)
```

---

## 4.5 Emotional Beat Guide

| When | What to do |
|------|------|
| Every 3-4 loops | Arrange a "stillness moment"—no clues, only atmosphere |
| After players' 2 consecutive high-pressure loops | Hint at a "coffee and sunset" opportunity |
| After NPC memory residue | Give the team private reflection space |
| Approaching the truth | Let an NPC show unexpected tenderness |
| Before the last loop | Give players a "last ordinary day" scene |

### GM Opening Narration Template

**Loop 1:** "You wake up. Sunlight streams through the hotel's old curtains. The air smells of autumn—dry leaves, distant cooking smoke. From downstairs comes the sound of the hotel proprietress preparing breakfast. Everything is normal. Everything is peaceful. Except... you don't quite remember how you came to this small town."

**Loop 5+:** "Sunlight streams through that curtain again. This time you notice the pattern on the curtain—in Loop 1 it was blue flowers, now those flowers look slightly purple. You're not sure if it's the light, or if it's truly changing. The sound from downstairs comes on time. You close your eyes and can perfectly predict the next 15 seconds."

**Loop 10+:** "Waking up has become hard. Not physically—the body always resets perfectly. But mentally. You know exactly what will happen every minute. You know who will say what. You know who will die. But you still open your eyes."

---

# Appendix

## A. Glossary

| Term | Abbrev. | Note |
|------|:---:|------|
| Success Band | — | Fixed adjudication range: 6− (Failure) / 7-9 (Partial Success) / 10+ (Full Success) |
| Situation Modifier | — | GM-applied ± value to the roll based on difficulty |
| Critical Success | — | Natural roll of 12 ("Boxcar") |
| Critical Failure | — | Natural roll of 2 ("Snake Eyes") |
| Advantage / Disadvantage | — | Roll 3d6 keep highest/lowest 2 |
| Memory Anchor | Memory Anchor Points (MAP) | Memory Anchor Points—cross-loop information capacity |
| Loop Fatigue Threshold | Loop Fatigue Threshold (LFT) | Loop Fatigue Threshold—mental breakdown line |
| Daily Action Points | Daily Action Points (DAP) | Daily Action Points—single-loop action budget |
| Déjà Vu DC | Déjà Vu DC (DVD) | Déjà Vu Difficulty—intuition sensing difficulty |
| Cognition Points | Cognition Points (CP) | Cognition Points—growth resource |
| World Degradation | — | World Degradation—GM mechanism's loop-advancing penalty |
| Rift | — | The spontaneous fracture of reality's structure under extreme emotional pressure |
| Anchor Event | — | The source of the rift, the root cause sustaining the loop's existence |
| Awakened One | — | A person who can retain memory in the loop |
| Loop Echo | — | Tiny variations and deepened meaning in repeated scenes |

## B. GM Quick Reference

### Loop Stage Quick Reference

| Loop | Stage | Degradation | Tone | Key Action |
|:--:|:---|:--:|:---|:---|
| 1-3 | Exploration | 1 | Curious | Build world + plant seeds |
| 4-6 | Optimization | 2 | Focused | Release fragments + trigger Déjà Vu |
| 7-9 | Truth | 3 | Heavy | Push puzzle + NPC shift |
| 10-12 | Endgame | 4 | Determined | Endgame pressure + memory residue |
| 13+ | Collapse | 5 | Poetic | Last chance + emotional climax |

### Information Control Quick Reference

| Loop | Cross-Loop Knowledge Use | GM Handling |
|:--:|:---|:---|
| 1-3 | Needs this-loop clues | "Your character doesn't know this yet." |
| 4-6 | "Intuitive action" may be requested | "You have a strange premonition..." |
| 7-9 | Mostly accessible via Déjà Vu | "Your body remembers before your mind does." |
| 10+ | Fully open | "You have become one with the loop." |

### Suicide Restart Cost Quick Reference

| Loop | Cost |
|:--:|:---|
| 1-3 | Information lost |
| 4-6 | Above + degradation accelerates 1 step |
| 7-9 | Above + random NPC permanently degrades 2 |
| 10-12 | Above + loop cap −1 |
| 13 | Suicide restart not allowed |

### Check Difficulty Quick Reference

| Difficulty | Situation Modifier | Full Success rate at Attribute +1 | Narrative Reference (Action) |
|:---:|:---:|:---:|------|
| Easy | +2 | 58% | Climbing dry rock with many handholds |
| Normal | +0 | 28% | Picking a standard door lock under time pressure |
| Hard | −1 | 17% | Silently climbing rusty pipes in the dark |
| Very Hard | −2 | 8% | Jumping from a moving vehicle to another in a storm |
| Nearly Impossible | −3 | 3% | Grabbing a cable in mid-air inside a falling elevator |

## C. Character Sheet Template

```
╔══════════════════════════════════════════════════╗
║              [Time Loop TRPG Character Sheet]     ║
╠══════════════════════════════════════════════════╣
║  Name: _______  Age: ___  Occupation: _______     ║
║  Background: _______________________________      ║
╠══════════════════════════════════════════════════╣
║                  The Five Attributes              ║
║  Memory [ ] ═══╗                                   ║
║                 ╠══ Memory Anchor Points: ___ (Memory (MEM)+⌊Insight (INS)/2⌋)  ║
║  Insight [ ] ═══╝                                   ║
║  Will [ ] ─── Fatigue Threshold: ___ (Will (WIL)×2+5)       ║
║  Action [ ] ─── Daily Action Points (AP): ___ (8+Action (ACT) modifier)        ║
║  Empathy [ ] ─── Déjà Vu DC: ___ (10−exposure count, min6) ║
╠══════════════════════════════════════════════════╣
║  Time Attitude: □ Optimist □ Skeptic □ Guardian  ║
║                 □ Fatalist □ Curious              ║
║  Special Ability: ___________________________      ║
╠══════════════════════════════════════════════════╣
║  Core Relationship NPC: _______  Relation: _______ ║
║  Hidden Information Card #___: (known only to player and GM) ║
╠══════════════════════════════════════════════════╣
║  Starting Equipment: □ Everyday clothes □ Phone □ Wallet/ID ║
║            □ Key ring □ _______________           ║
╠══════════════════════════════════════════════════╣
║  Cognition Points (CP): ___                         ║
║  Fatigue Track: Current ___ / Threshold ___       ║
║  Stage: □ Clear □ Weary □ Exhausted □ Collapse    ║
╠══════════════════════════════════════════════════╣
║  Anchored Information                              ║
║  Total Anchors: ___  Used: ___  Remaining: ___     ║
║  #1 _______________ │ Cost__ │ Clarity □Vag □Clr □Ful ║
║  #2 _______________ │ Cost__ │ Clarity □Vag □Clr □Ful ║
║  ...                                               ║
╠══════════════════════════════════════════════════╣
║  Anchored Items                                    ║
║  #1 _______________ │ Source Loop #___             ║
║  #2 _______________ │ Source Loop #___             ║
╚══════════════════════════════════════════════════╝
```

## D. Design Notes

### Design Choices and Trade-offs

1. **2d6 instead of d20:** The pyramid distribution of 2d6 makes the average more meaningful; the three-band success degree (Failure/Partial Success/Full Success) precisely maps to the narrative-game "No/Yes-but/Yes" structure, making every check advance the story.

2. **No Hit Points (HP) System:** In a time loop, death is not an endpoint but a reset. The four-level wound progression focuses more on "state" than "numbers," naturally matching the loop reset mechanism.

3. **No Level Growth:** Character growth is achieved through Cognition Points (CP), not levels. This reflects the investigative nature of the game—you grow stronger because you understand more, not because you killed more monsters.

4. **Degradation instead of fixed:** The World Degradation system ensures the loop doesn't become infinite trial-and-error—each reset is a countdown with a cost.

### Development Priority

| Priority | Module | Status |
|:---:|------|:--:|
| P0 | Five Attributes framework | ✅ v1.0 |
| P0 | Loop structure + Memory Anchoring system | ✅ v1.0 |
| P0 | Loop Degradation system | ✅ v1.0 |
| P1 | Truth Fragment system | ✅ v1.0 |
| P1 | Loop Fatigue system | ✅ v1.0 |
| P1 | Character creation (incl. Time Attitude and Hidden Information Card) | ✅ v1.0 |
| P2 | GM scenario design template | ✅ v1.0 |
| P2 | Team Memory Pool rules | ✅ v1.0 |
| P3 | Example scenario ×1 | ✅ Town Judgment Day framework |
| P3 | Balance tables for different loop lengths | ⏳ later version |

---

> **Time Loop TRPG Rules Book v1.0**
> Tabletop Rules Studio © 2026
>
> **Design Team:**
> - Bi Shu'an — Core mechanics (2d6 dice engine)
> - Ke Jiao'ling — Character system
> - Zhan Zhige — Action and conflict system
> - Jing Shiwen — Worldview and GM guide
> - Cheng Guiyao — Rules compilation and system architecture
