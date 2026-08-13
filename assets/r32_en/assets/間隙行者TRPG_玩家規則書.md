# Rift Walker TRPG — Player Rulebook

> **Version:** v1.2

> **Version:** v1.0
> **Design Premise:** You exist in the seam between spaces. Thresholds, corridors, tunnels, "the in-between moments" — most people pass through them without noticing. But you do. You can stop there.
> **Core Philosophy:** "Space is not empty. Crammed between spaces are all the forgotten things."

---

## Table of Contents

| Chapter | Content | Designer |
|---|---|---|
| **Chapter One** | Core Rules — dice system, attributes, checks, Gap Endurance, time flow | Bi Ao'an |
| **Chapter Two** | Character Creation — seven-step creation, Anchoring Item, Return Mark, Gap Sickness, growth system | Ke Jiao'ling |
| **Chapter Three** | Action & Conflict — action economy, Gap Creatures, negotiation exchange, Sealed Spaces, Gap physics | Zhan Zhige |
| **Chapter Four** | World & Narrative — the Two-Layer Worldview, GM running guide, scenario framework, sample scenario | Jing Shiwen |
| **Appendix** | Glossary, character sheet templates, GM quick reference | Cheng Guiyao (compiler) |

---

# Chapter One: Core Rules

> **Designer: Bi Ao'an (dice-mechanics)**

---

## 1. Dice System

### 1.1 Basic Mechanic: d20 + Attribute Value vs Difficulty Class (DC)

"Rift Walker" uses a **d20 + Attribute Value** versus **Difficulty Class (DC)** resolution system. Roll a 20-sided die, add the relevant attribute value; if the result is greater than or equal to the DC, it is a success.

**Reason for Choice**: The linear distribution of the d20 makes every +1 exactly equivalent (+5% success rate), giving clear meaning to every point spent in attribute allocation, supporting the system's design philosophy of "careful resource management."

### 1.2 Attribute Value Range

| Attribute Value | Description | Meaning |
|:---:|:---|:---|
| 1 | Deficient | Naturally lacking in this area; almost unable to rely on this attribute |
| 2–3 | Thin | Below the average level of a Gap Walker |
| 4–6 | Competent | Standard capability range of a Gap Walker |
| 7–8 | Excellent | Significant talent in this field; among the best of peers |
| 9–10 | Master | Has touched the limit of human capability in this dimension |

- **Creation Cap**: A single attribute maxes at 8 (can grow to 10 through long-term play)
- **Creation Floor**: A single attribute minimum is 1
- **Point Pool**: 25 points

### 1.3 Probability Distribution Table (core reference)

Using attribute value 5 (average level) as baseline, the success rates against each DC:

| Difficulty Class (DC) | Required Roll | Attribute 5 Success | Attribute 8 Success | Attribute 2 Success | Difficulty Label |
|:--:|:--------:|:------------:|:------------:|:------------:|:---|
| 6 | 1+ | 100%* | 100%* | 85% | Trivial |
| 8 | 3+ | 90% | 95% | 75% | Very Easy |
| 10 | 5+ | 80% | 95% | 65% | Easy |
| 12 | 7+ | 70% | 85% | 55% | Normal |
| 14 | 9+ | 60% | 75% | 45% | Slightly Hard |
| 15 | 10+ | 55% | 70% | 40% | Hard |
| 16 | 11+ | 50% | 65% | 35% | — |
| 18 | 13+ | 40% | 55% | 25% | Very Hard |
| 20 | 15+ | 30% | 45% | 15% | — |
| 22 | 17+ | 20% | 35% | 5% | Near Impossible |
| 24 | 19+ | 10% | 25% | 0%† | Legendary |

> \* A natural 1 always fails (see 1.5); † only a natural 20 can possibly succeed (5%)

### 1.4 Advantage / Disadvantage

| Advantage | Disadvantage |
|:---|:---|
| Having the appropriate professional tool or item | Acting while Gap Endurance is below 25% |
| Another character successfully assists | Under the effect of Gap Sickness |
| Spending extra time preparing (at least 10 minutes) | Acting within a Time-Flow Anomaly zone |
| Having prior intelligence or research results | Suffering from injury or fear conditions |
| A chained check after a natural 20 | A recovery check after a natural 1 |
| GM's ruling based on narrative context | GM's ruling based on narrative context |

**Mechanic**: With Advantage, roll 2d20 and take the higher; with Disadvantage, roll 2d20 and take the lower. Advantage/Disadvantage do not stack.

**Probability Impact** (Attribute 5 vs DC 12): Normal 70% / Advantage 91% / Disadvantage 49%

### 1.5 Critical Success (Natural 20) and Critical Failure (Natural 1)

**Critical Success (Natural 20)**: The check automatically succeeds. Gain one of the following: Insight (discover unexpected information), Recovery (+1 Gap Endurance), Echo (Advantage on the next related check), Resonance (a Gap Creature's attitude improves by one level).

**Critical Failure (Natural 1)**: The check automatically fails. Suffer one of the following: Drain (extra −1 Endurance), Attention (draw the attention of an unfriendly presence), Tremor (Disadvantage on the next related check), Fracture (the Gap structure at your current location becomes unstable).

---

## 2. Attribute System

### 2.1 The Five Attributes

**Awareness (AW)**: Noticing anomalies, sensing Gap entrances, noticing things in the Surface world that shouldn't be there.

**Traverse (TR)**: The smoothness of moving between the Surface and the Gap, as well as the ability to navigate within the Gap.

**Retrieval (RE)**: The ability to identify and recover Lost Items. Perceiving an item's emotional resonance, understanding its "forgotten story."

**Negotiation (NG)**: Communicating with the "residents" of the Gap — understanding their logic and finding a way to coexist.

**Anchor (AN)**: The core ability to maintain your connection to reality and avoid being assimilated by the Gap. Defines Gap Endurance maximum, recovery rate, and the threshold against Gap Sickness.

### 2.2 Attribute Value Meaning Table

| Attribute Value | Label | Meaning in the Gap Walker Community |
|:---:|:---|:---|
| 1 | Deficient | Almost no talent in this field; every reliance carries great risk |
| 2 | Thin | Can barely handle basic situations, but cannot be relied upon |
| 3 | Novice | Has received basic training or has some talent |
| 4 | Forming | Can be reliably used in non-stressful situations |
| 5 | Competent | General level of a Gap Walker; can work independently |
| 6 | Proficient | Often relied upon by the team to handle such matters |
| 7 | Refined | Known in the Gap Walker community for this ability |
| 8 | Excellent | The peak of character creation; an authority among peers |
| 9 | Grandmaster | Decades of experience or innate genius (only achievable through growth) |
| 10 | Legendary | The theoretical limit of humanity in this dimension |

### 2.3 25-Point Allocation Rules

1. All five attributes start at 0; the points invested become the attribute value
2. Each point invested increases the attribute value by +1
3. A single attribute has a **minimum of 1** (must invest at least 1 point)
4. A single attribute has a **maximum of 8** (cannot exceed 8 at creation)
5. Total investment must be **exactly 25 points**

---

## 3. Derived Attributes

| Derived Attribute | Formula | Description |
|:---|:---|:---|
| **Gap Endurance (GE)** | Anchor × 3 + 5 | Energy reserve for acting in the Gap; hitting zero means facing assimilation |
| **Threshold Sense Range** | Awareness × 5 meters | Effective passive radius for sensing Gap entrances |
| **Gap Sickness Threshold** | Anchor × 2 + Traverse | The judgment threshold for resisting the effects of Gap Sickness |
| **Residual Sense** | Awareness + Retrieval | Passively noticing traces of other Gap Walkers or entities that recently passed through |
| **Will Defense** | Anchor + Negotiation | Defense value against the mental influence of Gap entities |

### Typical Derived Attribute Value Ranges

| Anchor Value | Gap Endurance | Gap Sickness Threshold (Traverse=5) |
|:---:|:---:|:---:|
| 1 | 8 | 7 |
| 3 | 14 | 11 |
| 5 | 20 | 15 |
| 7 | 26 | 19 |
| 8 | 29 | 21 |
| 10 | 35 | 25 |

---

## 4. Check Rules

### 4.1 Passive Checks

**Passive Value = 10 + Attribute Value**

| Passive Check | Formula | Use |
|:---|:---|:---|
| Passive Awareness | 10 + Awareness | Automatically sense Gap entrances and anomalies within range |
| Passive Residual Sense | 10 + Awareness + Retrieval | Notice traces of other beings passing through |
| Passive Will Defense | 10 + Anchor + Negotiation | Resist persistent Gap environmental influence |

### 4.2 Active Check Procedure

1. GM declares the check attribute and Difficulty Class (DC)
2. Player may present a reason for Advantage
3. Roll d20 + attribute value
4. Compare result with Difficulty Class (DC)

### 4.3 Difficulty Class (DC) Difficulty Ladder

| Difficulty | DC Range | Example |
|:---|:---:|:---|
| Trivial | 5–7 | Noticing an obvious Gap fluctuation |
| Very Easy | 8–9 | Crossing a Natural Threshold, retrieving a Common Lost Item |
| Easy | 10–11 | Marking a clear anchor point |
| Normal | 12–13 | Crossing an Artificial Threshold, retrieving a Benevolent Keepsake |
| Slightly Hard | 14–15 | Moving quickly in the Gap, dealing with an unfriendly resident |
| Hard | 15–16 | Crossing a Trauma Threshold, retrieving a Memory Crystal |
| Very Hard | 17–19 | Crossing a Memory Threshold, retrieving a Gap Construct |
| Near Impossible | 20–23 | Sealing a Crack, retrieving the Forgotten |
| Legendary | 24+ | Repairing a collapsing Gap region |

### 4.4 Contest Checks

Both sides roll d20 + the relevant attribute value. The higher result wins. On a tie, the situation remains as it is.

### 4.5 Assist Rules

The assisting character must have ≥ 3 in the check's attribute and be able to reasonably provide help. The assisted character gains Advantage. At most one assistant per check.

---

## 5. Gap Endurance System

### 5.1 Endurance Cost Trigger Table

| Action | Gap Endurance (GE) Cost | Note |
|:---|:---:|:---|
| Cross Natural Threshold (enter) | 1 | — |
| Cross Artificial Threshold (enter) | 2 | — |
| Cross Trauma Threshold (enter) | 3 | Requires a Traverse check first |
| Cross Memory Threshold (enter) | 4 | Requires a Traverse check first |
| Move between Gap regions | 1 | Per "Gap region" crossed |
| Search for Lost Item (each attempt) | 1 | Regardless of success |
| Deep interaction with Gap entity | 1–3 | GM decides by depth of interaction |
| Mark anchor point | 2 | One-time cost |
| Maintain existence in the Gap (per scene) | 1 | Passive cost |
| Emergency evacuation (forced return to Surface) | 3 | No check required |
| Seal a Crack | 3 | Requires a Negotiation check |
| Critical Failure extra cost | 1 | — |
| In a Time-Flow Anomaly zone (per scene) | +1 | Stacks |

### 5.2 Endurance State Tiers

| State | Endurance Range | Mechanical Effect | Narrative Description |
|:---|:---|:---|:---|
| **Stable** | > 50% | No penalty | Clear consciousness; solid connection to reality |
| **Tense** | 25%–50% | Disadvantage on all Negotiation and Retrieval checks | Fingers begin to go numb; the silence of the Gap grows deeper |
| **Faded** | 10%–25% | Disadvantage on all checks except Anchor | Memories of the Surface begin to blur; your name becomes unfamiliar |
| **Dissolving** | < 10% | Full Disadvantage + DC 15 Anchor check/scene | You're no longer sure which side is "real" |
| **Zeroed** | 0 | DC 18 Anchor assimilation check | Silence swallows everything |

### 5.3 Endurance Recovery Mechanics

| Recovery Method | Amount | Condition |
|:---|:---|:---|
| Surface rest (per hour) | Anchor value | Must be in the Surface world |
| Full sleep (8 hours) | Full recovery | In a safe Surface environment |
| Rest while holding Anchoring Item (per hour) | Anchor value + 2 | Item must have personal meaningful connection |
| Leave the Gap (each return to Surface) | +1 | Voluntary, non-emergency evacuation |

---

## 6. Time Flow System

### d6 Time Flow Table

| d6 | Flow Name | Effect |
|:---:|:---|:---|
| 1 | **Backflow** | 1 hour in the Gap = Surface rewinds 1d6×10 minutes |
| 2 | **Stasis** | 1 hour in the Gap = Surface 1d6 minutes |
| 3 | **Sync** | 1:1 normal flow |
| 4 | **Drift** | 1 hour in the Gap = Surface 1d6 hours |
| 5 | **Rush** | 1 hour in the Gap = Surface 1d6 days |
| 6 | **Shatter** | Time shatters; reroll 2d6 and take two results, switching between them |

---

## 7. Quick Reference Card

### One-Time Check Procedure
1. GM declares: Attribute + Difficulty Class (DC)
2. Player states reason for Advantage (optional)
3. Roll d20 + attribute value
4. Result ≥ Difficulty Class (DC) → success

### Gap Endurance (GE) Cost Quick Reference
- Enter the Gap: 1–4 (by threshold type)
- Move: 1 / region
- Search: 1 / attempt
- Interact: 1–3 / time
- Maintain: 1 / scene
- Mark: 2
- Emergency evacuation: 3
- Seal a Crack: 3

### Endurance State Quick Reference
- >50% Stable: no penalty
- 25–50% Worn: Disadvantage on Anchor checks
- 10–25% Eroded: hear the Gap's whispers (GM gives fragmented perceptions)
- <10% Critical: before each action, DC 12 Anchor check; failure means Lost
- 0 Depleted: worsening contest + ejection to safe Threshold + 1d4 days Exhaustion

---

*End of Chapter One — continued in Chapter Two: Character Creation*
# Chapter Two: Character Creation

> **Design Intent**: You are not a warrior, mage, or thief. You are a "Gap Walker" — someone who can, at the right time, stand on the right Threshold and slip into the interlayer between spaces. Your character is not defined by a class, but by what you have lost, what you are looking for, and which Threshold you hesitated before.

---

## 2.1 Character Creation Overview

Creating a Gap Walker takes seven steps. Each step builds both numbers and story — there is no "fill attributes first, then think of background" order. Your attributes come from your experiences; your experiences come from your attributes.

| Step | Name | Output |
|---|---|---|
| One | First Crossing | The character's origin story; determines "why you can see" |
| Two | Attribute Allocation | The five attribute values; 25-point distribution |
| Three | Your First Threshold | Naming and description of a specific location |
| Four | Anchoring Item | An item (or an absence — your plot goal) |
| Five | What You Lost | A lost item and its story |
| Six | An Acquaintance in the Gap | A Gap Creature relationship |
| Seven | the Threshold You Won't Cross Again | A traumatic location |

---

## 2.2 Step One: First Crossing

> "Everyone first falls into the Gap differently. But one thing is the same — from then on, the way you see the world changed."

### Rules Explanation

When did your character first enter the Gap? This determines your initial relationship with the Gap. Choose one of the following origins, or create one with the GM:

#### Origin Options

**A. Childhood Accident** (Traverse +1 Background Modifier)
When you were little, you ran after something across a Threshold — a marble, a cat, or just because that door was half open and you wanted to see what was behind it. You were gone for fifteen minutes. No one believed you'd been to "another place." It took you many years to be sure it wasn't a dream.

- *Guiding Questions*: How old were you that year? What were you chasing? After you came back, did anyone believe you?

**B. Near-Death Experience** (Anchor +1 Background Modifier)
You once died — briefly. Or came very close. In the few seconds your heart stopped, you didn't see light — you saw a door. You chose to turn back. But since then, you began to notice other doors.

- *Guiding Questions*: How did you "die"? On the operating table? A car crash? Drowning? What did that door you saw look like?

**C. Led In by Another** (Negotiation +1 Background Modifier)
There was a person — another Gap Walker — who, at some point in your life, held your hand and led you across a Threshold. Maybe to save you. Maybe to show you. Maybe that person was also looking for something. Where is that person now? Can you still find them?

- *Guiding Questions*: Who led you in? What was your relationship? Are they still around? Do you owe them something, or do they owe you?

**D. Pulled In** (Awareness +1 Background Modifier)
You didn't go in voluntarily. Something — something in the Gap — pulled you. Maybe a hand reached out from the gap in the door. Maybe a wind you couldn't resist. Maybe just a thought: *Come in.* You went in, you came out, but you're not sure you came out "whole."

- *Guiding Questions*: What pulled you? Did you see it? Do you think it's still waiting for you to come back?

**E. Deliberate Seeker** (Retrieval +1 Background Modifier)
You lost something very important. You knew it didn't fall on the ground — it vanished. You found some strange discussion threads online, found a book with no title in a library basement, and then one morning at 2 a.m., you deliberately stood on the Threshold you were sure of. You went in. You didn't find what you wanted — but you knew it was inside.

- *Guiding Questions*: What did you lose? Are you still looking? What price did you pay to find a way into the Gap?

#### Background Modifier Explanation

The origin you choose grants a +1 "Background Modifier" to an attribute. This modifier does **not** count against the 25-point allocation cap in Step Two. In other words, you can raise that attribute to 9 (the Background Modifier can break the cap) — this is the only way to exceed the attribute cap of 8 at character creation.

If you create a custom origin with the GM, discuss with the GM which attribute receives the Background Modifier.

---

## 2.3 Step Two: Attribute Allocation

### 2.3.1 Attribute Definitions

| Attribute | Meaning | Typical Use in Play |
|---|---|---|
| **Awareness** | Perceiving anomalies, finding Gap entrances | Find Thresholds, notice spatial distortion, passive sensing |
| **Traverse** | Smoothness of moving between Surface and Gap | Enter/exit the Gap, move within the Gap, evade danger |
| **Retrieval** | Ability to identify and recover Lost Items | Search for Lost Items, judge an item's origin and ownership |
| **Negotiation** | Communicating with the "residents" of the Gap | Gap Creature interaction, Sealed Crack negotiation, exchange bargaining |
| **Anchor** | Maintaining connection to reality, not being assimilated by the Gap | Resist Gap Sickness, mark paths, remember who you are |

### 2.3.2 Attribute Value Meaning

| Attribute Value | Meaning |
|---|---|
| 1 | Ordinary person level — you have no special talent in this area |
| 2 | Slightly above average — some basic training or life experience |
| 3 | A capable Gap Walker — you can reliably use this attribute |
| 4 | A proficient Gap Walker — this is your comfort zone |
| 5 | Expert level — other Gap Walkers will recognize your ability here |
| 6 | Excellent — you can do things most Gap Walkers cannot |
| 7 | Top tier — you are a recognized master in this field within the circle |
| 8 | Human peak — the limit reachable at character creation |
| 9 | Legendary — only reachable via Background Modifier; your talent itself rewrites the rules |
| 10 | Beyond — only reachable via the growth system; you redefine the possibilities of this ability |

### 2.3.3 Allocation Rules

1. **Total Points**: 25 points, distributed among the five attributes (Awareness, Traverse, Retrieval, Negotiation, Anchor).
2. **Attribute Range**: Each attribute minimum 1, maximum 8 (excluding Background Modifier).
3. **Starting Point**: Each attribute starts at 0. Points invested = attribute value. Investing 1 point = attribute value 1; investing 8 points = attribute value 8.
4. **Floor**: Each attribute must receive at least 1 point (five attributes require at least 5 points total; remaining 20 points freely distributed).
5. **Step One Background Modifier**: After allocation is complete, add the +1 Background Modifier to the corresponding attribute. That attribute can thus reach 9.
6. **Cannot hold points**: All 25 points must be used.

#### Allocation Calculation Demonstration

```
Start (each attribute=0): 0 / 0 / 0 / 0 / 0 (25 points remaining)

Each attribute invests at least 1 point (5 points total), remaining 20 points freely distributed:

Plan One: Balanced
Awareness5 + Traverse5 + Retrieval5 + Negotiation5 + Anchor5 = 25 points
Final: 5 / 5 / 5 / 5 / 5 (all attributes balanced, expert level)

Plan Two: Specialist
Awareness8 + Traverse8 + Retrieval3 + Negotiation3 + Anchor3 = 25 points
Final: 8 / 8 / 3 / 3 / 3 (focus on Awareness/Traverse, others maintain basic ability)

Plan Three: Omnipotent (unreachable)
Try 8 / 8 / 8 / 8 / 8 = 40 points → far exceeds the 25-point cap.
25 points cannot make you omnipotent — you must make trade-offs.
```

**Design Note**: All-5 (expert-level balance) is fully viable — it means the character reaches a reliable level in every area. All-8 is impossible — you must make trade-offs, choosing which attributes are strengths and which are weaknesses. The 25-point design ensures characters inevitably have variation: there will always be things you do well and things you need teammates for. Attributes can still be raised to 10 later via the growth system (see §2.12), but growth is rare and significant.

### 2.3.4 Quick Creation: Attribute Arrays

If you want to create a character quickly, choose one array from below, then apply the Background Modifier:

| Array Name | Awareness | Traverse | Retrieval | Negotiation | Anchor | Suitable Style |
|---|---|---|---|---|---|---|
| **Searcher** | 7 | 5 | 7 | 2 | 4 | Focused on finding Lost Items, poor at dealing with creatures |
| **Communicator** | 4 | 4 | 4 | 8 | 5 | Skilled at negotiation, less reliant on technical abilities |
| **Crosser** | 5 | 8 | 4 | 5 | 3 | Movement expert, but weak Anchor — easily Lost |
| **Gatekeeper** | 7 | 4 | 5 | 3 | 6 | High in both sensing and anchoring; stable and reliable |
| **Scavenger** | 4 | 5 | 7 | 6 | 3 | Retrieval and Negotiation expert, but average Awareness and Anchor |
| **Balanced** | 5 | 5 | 5 | 5 | 5 | Balanced development in all areas |

---

### 2.3.5 Derived Attribute Calculation

From the five attributes, three key values are derived. The formulas remain unchanged; calculation examples for the 1–10 range are provided below.

| Derived Attribute | Formula | Description |
|---|---|---|
| **Gap Endurance Maximum** | Anchor × 3 + 5 | Total endurance cost you can withstand in the Gap |
| **Threshold Sense Range** | Awareness × 5 meters | Distance at which you can passively sense the existence of Thresholds |
| **Gap Sickness Threshold** | Anchor × 2 + Traverse | Personal protection value against Gap Sickness worsening (see §2.10.2) |

#### Calculation Examples

Three typical allocations showing derived attributes:

| Attribute Config | Anchor | Traverse | Awareness | GE Max | Threshold Sense | Gap Sickness Threshold |
|---|---|---|---|---|---|---|
| Balanced (5/5/5/5/5) | 5 | 5 | 5 | 20 | 25m | 15 |
| Specialist (8/8/3/3/3) | 3 | 8 | 8 | 14 | 40m | 14 |
| Anchor-Specialized (4/4/4/5/8+BG=9) | 9 | 4 | 4 | 32 | 20m | 22 |

**Interpretation**:
- **Balanced** (Anchor5/Traverse5): Gap Sickness Threshold 15, d20+5 needs ≥15 to resist, 55% success rate
- **Specialist** (Anchor3/Traverse8): High Traverse brings high threshold (14) and high sense (40m), but low Anchor gives only +3 check bonus, 50% resistance success rate
- **Anchor-Specialized** (Anchor9/Traverse4): Threshold as high as 22, d20+9 needs ≥13 to resist (40% success rate); the real advantage is the extremely high Gap Endurance (32 points) — can stay in the Gap longer

> **Design Note**: The Gap Sickness Threshold is affected by both Anchor and Traverse — Anchor is "how solidly you connect to reality," Traverse is "how skillfully you move in the Gap." A high-Traverse low-Anchor character (movement expert but weakly connected) and a high-Anchor low-Traverse character (iron anchor but clumsy movement) each have their pros and cons when resisting Gap Sickness.

---

## 2.4 Step Three: Your First Threshold

> "Every Gap Walker has a 'starting point' — the Threshold you can sense without looking for it. You crossed through it the first time; after that, every time, you recognize it."

### Rules Explanation

Choose or create a specific location as your first Threshold — the entrance you could earliest and most stably enter and exit the Gap.

#### You Must Define These Three:

1. **Location Description**: Where is it? In what corner of the real world? Is it a door? A flight of stairs? A bridge? A specific corridor corner?
2. **The Threshold's "Name"**: What name did you give it? This name need not be told to anyone — it is a secret between you and this Threshold.
3. **Threshold Type**: Determine its type based on the classification below (this affects the Traverse DC):

| Threshold Type | Traverse DC | Description |
|---|---|---|
| Natural Threshold | 8 | Thresholds of old buildings, both ends of bridges, staircase corners — these places are naturally "in-between" |
| Artificial Threshold | 12 | Habitual thresholds crossed repeatedly — the balcony you walk across every day, the same office door |
| Trauma Threshold | 15 | A place where a major event occurred — someone died here, a relationship ended here |
| Memory Threshold | 18 | A Gap entrance you have crossed before — it remembers you, and you remember it. If this Threshold is also the character's first Threshold, the Traverse check gains Advantage (effectively DC ~13) |

#### Special Effects of Your First Threshold

You have an emotional connection to your first Threshold. When you enter the Gap through it:
- **Traverse check gains Advantage** (you know it too well)
- **No extra endurance cost when entering the Gap** (first-turn base endurance cost waived)

This is your safest entrance — and your most vulnerable. If someone knows where your first Threshold is, they hold the key to your connection with the Gap.

#### Guiding Questions
- How often do you go back?
- Does anyone know it's your Threshold?
- If you stood on that Threshold but chose *not* to cross — what do you see in that instant?

---

## 2.5 Step Four: Anchoring Item

> "An Anchoring Item is not a charm. It doesn't protect you — it reminds you. When you stay too long in the Gap and start forgetting what color blue is, forgetting your mother's voice — you touch this thing, and you remember: right. I came from that side."

### 2.5.1 What Is an Anchoring Item?

An Anchoring Item is a physical object deeply connected to your personal history. It does not change in the Gap — when the Gap distorts everything, the Anchoring Item **stays as it is**. That is why it can anchor: it is the only thing unaffected by the Gap.

An Anchoring Item **cannot** be:
- Something you found in the Gap (Gap Constructs cannot anchor — they come from the Gap and cannot remind you what the Surface is)
- An ordinary item without personal emotional connection (a common key won't do — unless it's the one your late grandmother gave you)

An Anchoring Item **can** be:
- A family heirloom (grandmother's ring, father's watch)
- An item tied to a major turning point in your life (university acceptance letter, the ticket stub from your first trip abroad)
- Something someone left you — especially someone no longer here
- Something you made with your own hands — because you invested time, it remembers you

### 2.5.2 States of the Anchoring Item

At character creation, the Anchoring Item has three possible states:

| State | Description | Mechanical Effect |
|---|---|---|
| **Owned** | You have already found your Anchoring Item and carry it | **Passive**: GE Max +5, Advantage on Gap Sickness worsening checks, symptoms below Middle Stage alleviated. **Active**: Each Gap turn, spend 1 Action to "touch Anchoring Item" to gain Advantage on that turn's Anchor checks (not limited to Gap Sickness — includes marking paths, confirming current layer, resisting being Lost, etc.). **Meditation**: Once per day in the Gap, spend 10 minutes focused on Anchoring Item Meditation, recover Anchor value × 3 Gap Endurance |
| **Lost (Known)** | You know what it might be, but haven't found it yet | No immediate mechanical effect. This is your personal plot goal. The GM should design finding the Anchoring Item as an important narrative milestone |
| **Lost (Unknown)** | You don't know what your Anchoring Item is | Left blank at creation. The GM may arrange a "discover the Anchoring Item" moment in the narrative — usually when you need it most |

### 2.5.3 "Wear" of the Anchoring Item

An Anchoring Item is not invincible. The Anchoring Item wears when you are in the following situations:

- Forcing yourself to stay after Gap Endurance hits zero
- Witnessing an extremely severe "Unexplainable Phenomenon"
- Personally Sealing a Crack

When the Anchoring Item wears, the GM tells you: "You touch your Anchoring Item — it's a bit cooler than usual." or "A crack you've never seen before appeared on it." At this point, the Anchoring Item's effects are temporarily disabled: the GE bonus is retained, but the "touch Anchoring Item" Advantage, Anchoring Item Meditation recovery, and the passive Advantage on Gap Sickness worsening checks are all unavailable. Wear persists until the character lives continuously on the Surface for 3+ days.

### 2.5.4 Loss of Anchoring Item

If you lose your Anchoring Item in the narrative (stolen, lost, or taken by something in the Gap):

1. **Immediately trigger a Gap Sickness check** (see §2.10), using your Gap Sickness Threshold for the contest
2. **GE Maximum reverts to base value** (lose the +5 bonus)
3. **After each endurance cost in the Gap, an Anchor check (DC 12) is required** — failure means Disadvantage on all other checks that turn
4. Recovering the Anchoring Item becomes the character's **highest-priority plot goal**

#### Guiding Questions
- If you already own an Anchoring Item — how did it come to you? Who gave it to you? Or did you find it yourself?
- If you haven't found it yet — when did you last see it? Why do you know "it's the one"?
- If someone wanted to take your Anchoring Item — why would they do that?

---

## 2.6 Step Five: What You Lost

> "Not every Lost Item falls into the Gap. But the one you lost — you know it's inside. Because you occasionally feel it."

### Rules Explanation

Define an item extremely important to your character but already lost. This item may have fallen into the Gap — you may still be looking for it.

You must define:

1. **Item Description**: What is it? What does it look like? Any special marks?
2. **How It Was Lost**: How did you lose it? Where? Under what circumstances?
3. **Why It Matters**: Why is this item so important to you? Who is it connected to? What does it represent?
4. **Your Attitude**: Are you still looking for it? Or have you given up? Or are you afraid to find it — because finding it means you must face something?

### Item Quality (optional, discuss with GM)

If you want to actually find it in play, discuss with the GM which quality this lost item might belong to:

| Quality | Retrieval DC | Description |
|---|---|---|
| Common Lost Item | 8 | Emotional value far exceeds actual value |
| Benevolent Keepsake | 12 | Deliberately left in the Gap — maybe by another Gap Walker |
| Memory Crystal | 15 | Contains a memory — when you find it, you see the moment you lost it |
| Gap Construct | 18 | Not from the Surface — something the Gap itself generated. Purpose unknown |
| the Forgotten | 22 | Not an item — a person. A living person trapped in the Gap |
> See §3.12 for rules on retaining and using Lost Items.|

### Mechanical Effect

Your lost item provides a **one-time inspiration bonus** to your Retrieval checks: when you search in the Gap for something "similar to what you lost" (e.g., you lost a ring, you're looking for another ring), you may declare use of "Lost-Item Resonance" — that Retrieval check gains Advantage. Usable once per game session (chapter).

#### Guiding Questions
- If you really found it in the Gap — would you return it (to yourself)? Or leave it in the Gap?
- After losing this thing, what kind of person did you become? How is that different from before?
- Did anyone blame you for losing it — or blame themselves?

---

## 2.7 Step Six: An Acquaintance in the Gap

> "It's not your friend. You're not even sure it has the concept of 'friend.' But you recognize each other. When you move through its territory, it doesn't block you. Once, it even helped you."

### Rules Explanation

Define a Gap Creature you know. You're not friends — but there's a "mutual recognition" relationship between you. It helped you once. You owe it a favor — or it owes you.

### You Must Define:

1. **Creature Type**: Choose one of the following, or create with the GM:

| Type | What It Is | What It Helped You With (Example) |
|---|---|---|
| **Threshold Lingerer** | A person who hesitated too long before a Threshold — now it can never cross over | It told you a certain Threshold was "unsafe" — it saw the danger before you did |
| **Lost Item Collector** | A forgotten former Gap Walker, now hoarding Lost Items | It gave you a key item — but you don't know why it was willing to let go |
| **the Mirror** | A product of the Gap itself — a reflection that mimics your movements | When you were lost in the Gap, it mimicked you halfway, then suddenly pointed in another direction — that was the way out |
| **Path Guardian** | A giant creature blocking an important path | Once it didn't block you. To this day you don't know why |
| **Seal Watcher** | A presence guarding near a Sealed Space Crack | Its gaze told you "not yet" — you listened, and later it proved right |

2. **Relationship Details**:
   - What did it help you with? (specific event)
   - What do you owe it? (or does it owe you?)
   - How does it recognize you? (smell? movement? a specific sound?)
   - When did you last see it?

3. **Its "Name"**: What do you call it? (Gap Creatures have no True Name — or they do, but you don't know it. So you gave it one.)

### Mechanical Effect: Acquaintance Summon

Once every two game sessions, you may attempt to summon your acquaintance. Spend 3 Actions in the Gap focused on "thinking of it." Make a Negotiation check (DC set by GM based on narrative, usually 12–15):

- **Success**: It responds to you in some way — appears, gives guidance, or offers an exchange opportunity
- **Failure**: It didn't come. Or worse — something else came
- **Critical Success (Natural 20)**: It doesn't just appear — it actively helps you, requiring no exchange from you
- **Critical Failure (Natural 1)**: You accidentally summoned the wrong thing. GM decides what appears

### Evolution of the Relationship

As play progresses, your relationship with the acquaintance may change. The GM adjusts the relationship state based on narrative progression and your choices:

- You fulfilled what you owed it → relationship deepens, Negotiation DC lowers
- You betrayed its trust → relationship breaks, it no longer responds to summons
- You helped it complete its Passing Over → it is free, you gain a Return Mark, you lose this acquaintance forever

#### Guiding Questions
- If you saw it again — what would your first words be?
- Why do you think it helped you? What did it get from you?
- If one day it needed you to help it Pass Over — would you? (That would mean you'd lose it forever)

---

## 2.8 Step Seven: the Threshold You Won't Cross Again

> "Every Gap Walker has a Threshold — one they'd rather take a detour than cross. Not because it's dangerous. But because on the other side of the door is something they don't want to face."

### Rules Explanation

Define a Threshold you never want to cross again. You once experienced something there — perhaps trauma, loss, or a decision you can't undo.

### You Must Define:

1. **Threshold Description**: Where is it? What does it look like? A door? A corridor? A specific point in time (e.g., "every December 24 at 3 p.m., the back door of my old family house")?
2. **What Happened**: What did you experience there? Who did you lose? What wrong decision did you make? Or what did you see that you shouldn't have?
3. **Why You Won't Cross Again**: Is it because you're afraid — or because you feel guilty? Or because crossing that Threshold would make something "real" — and you don't want it to be real?
4. **Consequences**: If you were forced to cross that Threshold — what would happen? (Discuss possible mechanical consequences with GM)

### Special Rules for the Threshold You Won't Cross Again

- You **cannot** voluntarily enter the Gap from this Threshold — you need to pass a DC 20 Anchor check to force yourself
- If another Gap Walker tries to lead you across this Threshold — they need a DC 18 Negotiation check to persuade you
- If in the narrative you are forced to enter the Gap from this Threshold — upon entering, immediately trigger a Gap Sickness check, and difficulty +5

### Narrative Function of This Threshold

This Threshold is the core of your character arc. It represents your character's deepest fear or regret. The GM should weave this Threshold into the main plot — not by immediately forcing you to cross, but by letting its existence become a sustained pressure.

A good "Threshold You Won't Cross Again" comes into play at some pivotal moment in the game — perhaps at the ending you must cross it to save someone, perhaps crossing it is the only way to complete a journey.

#### Guiding Questions
- If you stood one meter before that Threshold — what would you feel?
- Does anyone else know what this Threshold means to you?
- Do you think one day you'll cross it? If so — under what circumstances?

---

## 2.9 Return Mark System

> "You returned the thing to its true owner. In that moment — in the Gap, between two spaces — something left a mark on you. Not a scar. More like... a signature. The Gap remembers you did this."

### 2.9.1 What Is a Return Mark?

A Return Mark is a permanent mark left on you when you return a Lost Item to its original owner. It is a metaphysical mark — invisible on the Surface, but in the Gap, certain creatures can "see" the Return Mark on you. They look at you differently.

### 2.9.2 Gaining Return Marks

Return Marks can be gained in two ways:

**Method A: Return a Lost Item to Its Owner**

You gain a Return Mark when you meet all of the following conditions:

1. You found a Lost Item in the Gap
2. You identified its original owner (through a Retrieval check or narrative)
3. You personally returned it to the original owner
4. The owner is genuinely grateful — the item truly means something to them

Additionally, when you return a Lost Item to its owner, you immediately recover **5 Gap Endurance** — the kind act of returning it makes you temporarily more solidly connected to reality.

**Method B: Help a Gap Creature Pass Over**

When you help a Gap Creature Pass Over (specific rules in §2.11.3), upon success you also gain a Return Mark. This means you helped not only humans — but also those trapped in the Gap.

**Note**: You cannot deliberately arrange things just to farm Marks. The GM has final discretion to judge whether a return act is "sincere."

### 2.9.3 Return Mark Tiers and Effects

Return Marks accumulate. Each time you accumulate a certain number, you gain new effects:

| Accumulated Marks | Tier Name | Effect |
|---|---|---|
| 1 | First Mark | When negotiating with Gap Creatures, Negotiation check +2 (they sense what you've "returned" — at the 1–10 attribute range, +2 is roughly one attribute level of difference) |
| 3 | Familiar Mark | You can sense the "direction of belonging" of a Lost Item — when you hold a Lost Item, spend 1 Action on a Retrieval check (DC set by GM); on success you vaguely sense the direction and distance of the original owner. Additionally, when you are in **Early Stage Gap Sickness**, you gain Advantage on Gap Sickness worsening checks (the Return Mark passively protects you) |
| 5 | Deep Mark | You gain a "Reputation" in the Gap — non-hostile Gap Creatures won't attack or block you first (they observe first). In Negotiation Exchange, the price the other party demands is lowered one level (e.g., originally demanding a Memory Crystal, now accepts a Common Lost Item). Additionally, protection extends to **Middle Stage Gap Sickness**: when you are in Middle Stage, you gain Advantage on Gap Sickness worsening checks |
| 7 | Inscribed Mark | You can help a Gap Creature Pass Over without knowing its True Name — you only need to understand its story. This lets you treat Late Stage Gap Sickness (see §2.10) without relying on a GM-arranged specific scenario |
| 10 | Legendary Mark | The Gap itself knows you. All Traverse checks gain Advantage. You can sense all Thresholds within line of sight (no Awareness check needed). Your name will be sung by other Gap Walkers — though you don't know this. **Return Resonance**: You may choose to spend all your Return Marks (zero them) to reverse a character in Terminal Stage Gap Sickness back to Late Stage. After use you lose all Return Mark-related effects — but you will remember: what you truly own is what you gave away |

### 2.9.4 Interaction Between Return Marks and Anchor

Return Marks form a different kind of "anchor" on you from the Anchoring Item — it comes from the kind connection between you and the world.

- For every 3 Return Marks you have, your **effective Anchor value** gains +1 when contesting Gap Sickness (affects only Gap Sickness checks, not other Anchor checks)
- If you lose your Anchoring Item but have at least 5 Return Marks — you won't trigger the immediate Gap Sickness check from losing the Anchoring Item (but other loss-of-Anchoring-Item penalties still apply)

### 2.9.5 Situations Where Return Marks Cannot Be Gained

- The returned item is your own (self-return produces no Mark)
- The item was obtained non-voluntarily (returning a stolen Lost Item produces no Mark — but stealing then returning may produce other narrative consequences)
- The original owner has died with no heir — at this point, leaving the item at the door of the space the owner once lived in; GM decides whether a Mark triggers

---

## 2.10 Gap Sickness Tracking System

> **Chapter Position**: This section provides the **player-view overview** of Gap Sickness — what Gap Sickness is, the general symptoms of the four stages, and the basic risks you as a player need to know.
> **Full mechanical rules** (worsening contest formula, detailed DC, unified treatment table) are in **Chapter Three §3.6**. When creating a character, reading this section is sufficient; when actually encountering a Gap Sickness check in play, the GM will guide you to reference Chapter Three.


> "The Gap has no air, no food, no water — but none of that is the problem. The problem is the Gap has no 'you.' Stay too long, and you start forgetting you're a person."

### 2.10.1 Triggers for Gap Sickness Worsening

Gap Sickness does not worsen without cause. A Gap Sickness check triggers in the following situations (using the unified Threshold Contest of §2.10.2):

| Trigger Condition | Description |
|---|---|
| Gap Endurance hits zero (after returning to Surface) | The most common trigger — you exhausted all endurance in the Gap |
| Staying continuously in the Gap beyond 10 turns | Re-check every additional 5 turns |
| Entering the Gap from the "Threshold You Won't Cross Again" | See Step Seven — resonance of the traumatic place intensifies erosion |
| Losing the Anchoring Item | See §2.5.4 — the shock of losing the anchor to reality |
| Witnessing an "Unexplainable Phenomenon" (GM judgment) | GM may grant Disadvantage based on phenomenon intensity |
| Attempting to escape from a Sealed Space | There is no Gap inside a Sealed Space — you are effectively "denying the reasonableness of your existence" |

### 2.10.2 Check Method: Threshold Contest

The Gap Sickness check uses the **Threshold Contest** mechanic, replacing the old fixed DC system.

**Gap Sickness Threshold** = Anchor × 2 + Traverse (pre-calculated on the character sheet)

When a trigger occurs:
1. Roll **d20 + Anchor modifier**
2. Contest your **Gap Sickness Threshold**
3. **Success** (roll result ≥ Gap Sickness Threshold): Gap Sickness does not worsen, stays at current stage
4. **Failure** (roll result < Gap Sickness Threshold): Gap Sickness worsens by one stage, takes effect immediately
5. **Critical Failure (Natural 1)**: Skip a stage — jump directly to two stages later (e.g., from Early directly to Late Stage)

**Design Note**: The Gap Sickness Threshold includes both Anchor (how solidly you connect to reality) and Traverse (how skillfully you move in the Gap). The higher both are, the higher the threshold — but your Anchor also appears in the check bonus. This creates an internal tension: high Anchor gives a higher check bonus, but also raises the threshold you need to meet. True protection comes from the balance of Anchor and Traverse — not from stacking a single attribute.

### 2.10.3 Detailed Mechanical Effects of the Four Gap Sickness Stages

#### Stage One: Early Stage (Threshold Glows)

**Symptom Description**: You start seeing things on the Surface you shouldn't — Thresholds faintly glow, corridors are longer than they actually are, something moves in the corner but when you turn there's nothing.

| Mechanical Effect |
|---|
| You cannot voluntarily turn off Awareness checks — the GM may require an Awareness check at any time, even if you don't want to sense the Gap |
| When talking with people on the Surface, every 10 minutes you must make an Anchor check (DC 8); failure means you briefly "zone out" — you saw a flash of the Gap and missed what the other person said |
| No extra cost when entering the Gap (at this stage the Gap still accepts you) |

**Roleplay Hint**: You start doubting whether what you see is real. You become more cautious — or more irritable. You're not quite sure if you're "losing your mind."

#### Stage Two: Middle Stage (Boundary Blurs)

**Symptom Description**: The boundary between Surface and Gap begins to dissolve. You walk into a room, unsure if you're still on the Surface. People on the street look like Gap Creatures. Gap Creatures look like people on the street.

| Mechanical Effect |
|---|
| **The GM no longer tells you your current layer.** You can only rely on your own judgment and surrounding clues to infer |
| When making any check in the Gap, if you fail — you temporarily "lose your sense of direction," and next turn must spend 1 Action on an Anchor check (DC 12) to continue acting |
| Disadvantage on social interactions on the Surface (you look unsettled, slow to react) |
| On the first turn of entering the Gap, you must make an Anchor check (DC 10) to "confirm you came in" — failure means you're unsure where you are now |

**Roleplay Hint**: You develop the habit of touching things — walls, tabletops, your own Anchoring Item. You need physical touch to confirm "this is real." You start distrusting your own senses.

#### Stage Three: Late Stage (Translucent)

**Symptom Description**: Your body begins to refuse to stay on the Surface. In light, others can see through you to what's behind — not fully transparent, but enough that someone in conversation suddenly stops and frowns at you. Those near death can see your full figure. They sometimes actively speak to you, thinking you've come to fetch them.

| Mechanical Effect |
|---|
| Disadvantage on all social checks with "normal humans" — they subconsciously don't want to look at you |
| Advantage on interactions with "those near death" (severe patients, the elderly, the dying) — they can see your true form and aren't afraid of you |
| On the Surface, every 24 hours you must make an Anchor check (DC 14); failure means you find yourself "unconsciously" standing on a Threshold — your body is trying to return to the Gap |
| When moving in the Gap you don't consume base endurance (you're already "half of the Gap") — but this is not a good thing |
| Gap Creatures start treating you as "one of their own" — in Negotiation Exchange the price may rise (they feel you no longer need "special treatment") |

**Roleplay Hint**: You start avoiding crowds. You no longer look in mirrors — or you look much longer, because you need to confirm you're still there. You've considered whether you should "move into the Gap" — after all, you're already half in it.

#### Stage Four: Terminal Stage (Becoming a Gap Creature)

**Symptom Description**: You are not you.

| Mechanical Effect |
|---|
| Character taken over by GM |
| Character becomes an NPC — specifically, a new "Lost Item Collector" or "Threshold Lingerer" (decided by GM based on character history) |
| Character still exists in the game world — other PCs may encounter them in the Gap |
| The player of that character needs to create a new character |
| The old character cannot be "saved back" — they are no longer "a person trapped in the Gap," but "a part of the Gap" |

**Roleplay Hint (for that player's other characters)**: You lost your former character. Maybe one day you'll meet them — but that's no longer you. When you see them hoarding Lost Items in the Gap, or hesitating before a Threshold, what will you do?

### 2.10.4 Gap Sickness Stage Tracking Table

| Character's Current Stage | Healthy | Early | Middle | Late | Terminal |
|---|---|---|---|---|---|
| Check Method | — | d20+Anchor vs Gap Sickness Threshold | d20+Anchor vs Gap Sickness Threshold | d20+Anchor vs Gap Sickness Threshold | — |
| Treatable? | — | ✅ | ✅ | ✅ | ⚠️ Only one DC 22 Terminal Final Check |

---

## 2.11 Treatment System

### 2.11.1 Treatment Methods Table

| # | Treatment Method | Effect | Required Condition | Time Needed | Source |
|---|---|---|---|---|---|
| 1 | **Surface Rest** | Early symptoms fully cleared, return to Healthy | 7 consecutive days without entering the Gap, one DC 10 Anchor check per day, accumulate 7 successes (if passively triggered Awareness check, that day doesn't count) | 7 in-game days | Ch2+Ch3 |
| 2a | **First Finding Anchoring Item** | Middle→Early (one-time reversal); GE Max +5 | Complete the GM-arranged Anchoring Item plot line. If you already had it but lost it, recovering it also applies | Narrative time (usually 1–2 chapters) | Ch2 |
| 2b | **Continuously Holding Anchoring Item** | GE Max +5, Advantage on Gap Sickness worsening checks, stage progression below Middle slowed | Must hold Anchoring Item and be in non-worn state | Continuous passive effect | Ch3 |
| 3 | **Help Gap Creature Pass Over** | Reverse one stage below Late (Late→Middle, Middle→Early, Early→Healthy) | Meet the creature's "Pass Over" conditions — understand its story, find key item/person/info, help it take that step (see 2.11.3) | Narrative time (usually 1–3 chapters) | Consistent |
| 4 | **Return Mark Protection** | 3 Marks→Advantage on worsening checks at Early Stage Gap Sickness; 5 Marks→protection extends to Middle Stage also with Advantage | Accumulate corresponding number of Return Marks (see 2.9.3) | Continuous passive effect | Merged |
| 5a | **Other's Anchor Assistance** | Next Gap Sickness worsening check gains Advantage (short-term delay, no stage reversal) | Any Gap Walker spends 1 hour with you, makes DC 14 Anchor check | 1 hour | Ch3 |
| 5b | **Master Treatment** | Middle→Early | Needs a PC or NPC with 7+ Return Marks ("Inscribed Mark" tier) willing to help you | One scene | Ch2 |
| 6 | **Terminal Final Check** | DC 22 Anchor check (Advantage if holding Anchoring Item), success→Terminal→Late. Failure→transformation irreversible. **Each character gets only one chance** | At Terminal Stage | One scene | Ch3 |
| 7 | **Mirror's Sacrifice** | Reverse one stage (any stage, excluding Terminal), but permanently lose your Mirror | Your Mirror chooses to "take your place" — it bears the erosion of Gap Sickness for you | One scene | Ch2 |

### 2.11.2 "Immunity" After Treatment

- After recovery from Early: no Gap Sickness check triggered by Gap Endurance hitting zero for the next 7 days
- After recovery from Middle: Advantage on Gap Sickness checks for the next 3 days
- After recovery from Late: Advantage on Gap Sickness checks for the next 24 hours
- After recovery from any stage, if it worsens again into the same stage — that stage's DC permanently +2 (your body "remembers" this stage)

### 2.11.3 Specific Rules for "Helping a Gap Creature Pass Over"

This is the most reliable method to treat Late Stage Gap Sickness, and one of the most meaningful acts in the game. (Terminal Final Check see Treatment Table #6, Mirror's Sacrifice see Treatment Table #7.)

**Steps to Pass Over**:

1. **Understand its story**: Through Negotiation Exchange or observation, understand why this Gap Creature is trapped. What is it waiting for? What is it hesitating about? What did it lose?
2. **Find the key item/person/info**: Usually requires returning to the Surface to search — a name, an item, or a person. This forms a small Lost-Item Commission.
3. **Return to the Gap, help it complete**: Give the key item to it, call its name, or bring that person to see it one last time.
4. **Roll Negotiation check (DC set by GM by narrative, usually 15–18)**: Success — it Passes Over, disappears (where to? no one knows). You gain a Return Mark. Failure — it hesitated. You can try again, but next DC +2.

**Design Note**: The GM should make each "help Pass Over" a unique narrative climax. Don't let it become a mechanical task. Each Gap Creature's Passing Over is a micro-story.

---

## 2.12 Growth and Advancement System

> "You don't get stronger just by crossing the Gap a few more times. But every time you return something, help a Gap Creature, or stand for a minute before the Threshold you didn't want to face — you change. Not stronger. More... yourself."

### 2.12.1 Design Philosophy

"Rift Walker" does not use an experience point (XP) system. Character growth comes from three layers: **Narrative Milestones**, **Relationship Deepening**, and **Rare Attribute Increases**.

### 2.12.2 Milestone System

The game is divided into "Chapters" and "Arcs." An Arc usually contains 3–5 Chapters, forming a complete story unit. At the end of each Arc, the GM grants character growth based on the following criteria:

#### Milestone Checklist (at end of each Arc)

| Achievement | Growth Reward |
|---|---|
| Return at least one Lost Item | Gain a Return Mark |
| Help a Gap Creature (not necessarily Pass Over) | Gain a new Gap acquaintance relationship |
| Discover a new Threshold and cross it successfully | That Threshold joins your Known Threshold list; thereafter entering the Gap from that Threshold gives Traverse check Advantage |
| Face your "Threshold You Won't Cross Again" — even without crossing, just standing before the door or thinking | That Threshold's crossing DC lowered by 2 (you're starting to face it) |
| Learn a Sealed Space's secret | Gain a "Knowledge Mark" about that specific Sealed Space — thereafter Advantage on checks related to that Sealed Space |
| Character completes personal plot goal (e.g., find Anchoring Item) | See attribute growth below |

### 2.12.3 Attribute Growth

Attribute increases are rare and significant — not just numbers getting bigger, but the character essentially becoming stronger.

| Condition | Attribute Growth |
|---|---|
| Complete the personal plot goal set at creation (find Anchoring Item, recover lost item, face Threshold You Won't Cross Again) | Any attribute +1 (cannot exceed 10; Background Modifier attribute can reach 9 then grow to 10 via growth) |
| Complete a full Arc (3–5 Chapters), and the character underwent profound transformation in the Arc | GM may allow any attribute +1 (at most once per Arc) |
| Gain the 7th Return Mark (Inscribed Mark) | Negotiation or Anchor +1 (choose one) |

**Attribute Cap Rules**:
- Creation stage: normal cap is 8, Background Modifier attribute can reach 9
- Growth stage: attribute can grow from creation value step by step up to max 10
- Growth calculation: growth times per attribute = 10 − that attribute's creation value (including Background Modifier)
  - Example: Anchor 5 at creation, that attribute can grow at most 10−5 = 5 times
  - Example: Anchor 8 at creation (9 after Background Modifier), that attribute can grow at most 10−9 = 1 time
- Each growth is +1 attribute value, from a major milestone (see table below)
- 8→9 requires a story-level milestone; 9→10 requires a legendary achievement (GM discretion)

**Design Note**: Attribute growth is no longer a fixed "cap of 3 times," but tied to the character's starting point. The lower the starting attribute, the more room to grow — your weaknesses are where the most story can be told. A character growing from Anchor 3 to Anchor 8 continuously strengthens their connection to reality across five major milestones; while a character created with Anchor 8 is already near the human limit in that regard, able to grow only to 10 (two legendary achievements).

### 2.12.4 Non-Numeric Growth

This is the primary form of growth. Below are abilities a character can gain in play that don't change attribute numbers:

#### Known Threshold Network

Each time you successfully enter the Gap from a new Threshold and return safely, that Threshold joins your "Known Threshold list." This isn't a number — it's a location you can use.

| Number of Thresholds | Effect |
|---|---|
| 3+ | You can "chain" Thresholds in the city — enter the Gap from A, and without returning to the Surface, exit directly from B (requires a Traverse check contesting the higher of the two Thresholds) |
| 5+ | You no longer get lost in the Gap — you always know the direction of the nearest Known Threshold |
| 10+ | You are called a "Cartographer" — other Gap Walkers come to you for directions |

#### Gap Acquaintance Network

Beyond the initial acquaintance created in Step Six, each time you help a Gap Creature (not necessarily Pass Over), you may attempt to build a new relationship. Make a Negotiation check (DC set by GM):

- Success: the creature becomes a new "acquaintance," joining your acquaintance list
- Failure: the creature won't hurt you, but won't especially help you either
- Critical Success: the creature isn't just an acquaintance — it actively provides an important piece of intel about the Gap

#### Special Knowledge

Knowledge gained through narrative, unmeasurable by attributes:

| Knowledge Type | How to Gain | Use |
|---|---|---|
| **Origin of Sealed Spaces** | Investigate Surface historical records, interview relevant people | Know why a Sealed Space was sealed — may find the "key" to open it |
| **Gap Creature's "True Name"** | Exchanged from other Gap Creatures, seen in a Lost Item (Memory Crystal) | Calling the True Name makes that creature serve you once, after which it is free |
| **Gap Geography** | Repeatedly explore a specific Gap Layer region | Know a region's Shortcuts, danger zones, Gravity Anomaly Zone locations |
| **Time-Flow Pattern** | Accumulated experience (GM may grant after multiple crossings) | Some prediction of a specific Threshold's time flow — from completely random to "you know this Threshold usually makes you come back late" |

### 2.12.5 Character Arc Tracking Table

It is recommended each player track their character arc on the back of the character sheet (or another page):

| Tracking Item | Status |
|---|---|
| Found Anchoring Item? | ☐ No / ☐ Yes:_________ |
| Recovered lost item? | ☐ No / ☐ Yes:_________ / ☐ Gave up |
| Faced Threshold You Won't Cross Again? | ☐ No / ☐ Stood before door / ☐ Crossed |
| Number of Lost Items returned (Return Marks) | ____ items |
| Number of Known Thresholds | ____ |
| Number of Gap acquaintances | ____ |
| Gap Creatures helped Pass Over | ____ |
| Attribute growth record | See below |

---

## 2.13 Character Sheet Template

The complete character sheet format is below. Players should fill out this sheet after creation.

---

```
╔══════════════════════════════════════════════════════════╗
║              G A P   W A L K E R   C H A R A C T E R   S H E E T              ║
╠══════════════════════════════════════════════════════════╣
║                                                          ║
║  Character Name: ________________  Player Name: ________________  ║
║  Age: ________   Appearance: ___________________________  ║
║                                                          ║
╠══════════════════════════════════════════════════════════╣
║  I. Attributes (25-point allocation + Background Modifier) ║
╠══════════════════════════════════════════════════════════╣
║                                                          ║
║  Awareness  [___] (1-8)  Sense anomalies, find Gap entrances ║
║  Traverse    [___] (1-8)  Move between Surface and Gap    ║
║  Retrieval   [___] (1-8)  Identify and recover Lost Items ║
║  Negotiation [___] (1-8)  Communicate with Gap Creatures  ║
║  Anchor      [___] (1-8)  Maintain connection to reality  ║
║                                                          ║
║  Background Modifier: ______ +1  →  Current Value: ______ [___] ║
║                                                          ║
╠══════════════════════════════════════════════════════════╣
║  II. Derived Attributes                                   ║
╠══════════════════════════════════════════════════════════╣
║                                                          ║
║  GE Maximum: Anchor × 3 + 5 = ______                     ║
║  Current GE: ______ / ______                             ║
║  Threshold Sense Range: Awareness × 5 = ______ m         ║
║  Gap Sickness Threshold: Anchor × 2 + Traverse = ______   ║
║                                                          ║
╠══════════════════════════════════════════════════════════╣
║  III. Origin & Background                                 ║
╠══════════════════════════════════════════════════════════╣
║                                                          ║
║  Step One | First Crossing (Origin Type: __________)     ║
║  ____________________________________________________   ║
║  ____________________________________________________   ║
║                                                          ║
║  Step Three | First Threshold                            ║
║  Threshold Name: ____________________  Type: ______ (DC: __) ║
║  Location Description: __________________________________ ║
║  ____________________________________________________   ║
║                                                          ║
║  Step Four | Anchoring Item                              ║
║  State: ☐ Owned / ☐ Lost (Known) / ☐ Lost (Unknown)     ║
║  Item Description: ______________________________________ ║
║  ____________________________________________________   ║
║                                                          ║
║  Step Five | What You Lost                               ║
║  Item: ________________  How Lost: ___________________   ║
║  Why It Matters: ________________________________________ ║
║  Attitude: ☐ Still searching / ☐ Gave up / ☐ Afraid to find ║
║                                                          ║
║  Step Six | Acquaintance in the Gap                      ║
║  Type: ______________  You call it: ____________________ ║
║  It helped you: ________________________________________ ║
║  You owe it / It owes you: ____________________________  ║
║                                                          ║
║  Step Seven | Threshold You Won't Cross Again            ║
║  Threshold Description: ________________________________ ║
║  What Happened: ________________________________________ ║
║  Why you won't cross again: ____________________________ ║
║                                                          ║
╠══════════════════════════════════════════════════════════╣
║  IV. Gap Sickness Tracking                               ║
╠══════════════════════════════════════════════════════════╣
║                                                          ║
║  Current Stage: ☐ Healthy / ☐ Early / ☐ Middle / ☐ Late / ☐ Terminal ║
║  Gap Sickness Threshold (Anchor×2+Traverse): ______  (Check: d20+Anchor vs Threshold) ║
║                                                          ║
║  [Recovery Tracking]                                     ║
║  Continuous Surface Life: ____ / 7 days                  ║
║                                                          ║
╠══════════════════════════════════════════════════════════╣
║  V. Growth Tracking                                      ║
╠══════════════════════════════════════════════════════════╣
║                                                          ║
║  Return Marks: ____ (Tier: ______________)              ║
║  Known Thresholds: ____                                  ║
║  Gap Acquaintances: ____                                 ║
║  Helped Pass Over: ____                                  ║
║  Growth Milestone Record:                                ║
║  ☐ ☐ ☐ ☐ ☐ ☐ ☐ ☐ ☐ ☐ (each ☐ = one +1, cap = 10 − starting value) ║
║  Anchoring Item: ☐ Found / ☐ Not found                  ║
║  Lost Item: ☐ Recovered / ☐ Not recovered / ☐ Gave up   ║
║  Threshold You Won't Cross Again: ☐ Not faced / ☐ Stood before door / ☐ Crossed ║
║                                                          ║
╠══════════════════════════════════════════════════════════╣
║  VI. Notes & Memo                                        ║
╠══════════════════════════════════════════════════════════╣
║                                                          ║
║  ____________________________________________________   ║
║  ____________________________________________________   ║
║  ____________________________________________________   ║
║  ____________________________________________________   ║
║                                                          ║
╚══════════════════════════════════════════════════════════╝
```

---

## Appendix A: Character Creation Quick Reference

### Seven-Step Quick Reference

| # | Step | What to Decide |
|---|---|---|
| 1 | First Crossing | Choose origin (A/B/C/D/E or custom) → gain Background Modifier +1 |
| 2 | Attribute Allocation | 25 points distributed to five attributes (each 1–8), plus Background Modifier |
| 3 | First Threshold | Name, describe location, determine Threshold type |
| 4 | Anchoring Item | Choose state (Owned / Known-Lost / Unknown-Lost), describe item |
| 5 | What You Lost | Describe item, how it was lost, its importance, your attitude |
| 6 | Acquaintance in the Gap | Choose creature type, describe relationship, what it helped you with |
| 7 | Threshold You Won't Cross Again | Describe location, what happened, why you won't cross again |

### GM Character Creation Guidance Hints

- Encourage players to weave each step into one coherent story. Example: "My Anchoring Item is part of what I lost — my grandmother's ring was a pair; I lost one, I carry the other."
- Let Step Six and Step Seven connect — maybe the Threshold You Won't Cross Again relates to your acquaintance?
- Don't rush to "resolve" things at creation — a blank Anchoring Item and an unresolved lost item are the GM's best narrative material.
- All-5 attributes (expert-level balance) is fine — but all-8 is impossible; players must make trade-offs. An all-5 character is reliable everywhere but has no standout advantage; their growth will come more from narrative than numbers.

### Design Notes

**On Attribute Range and Allocation**: 25 points distributed among five attributes in the 1–8 range means characters inevitably vary — all-8 needs 40 points, far exceeding the cap. You can choose balanced 5/5/5/5/5 (expert) or specialized 8/8/3/3/3. This shifts the player's attention from "how to get stronger" to "what my character is good at, what they're bad at." No matter how high the attributes, the character remains fragile — because Gap Sickness doesn't look at your attributes, only at how long you stayed.

**On the Classless System**: All PCs share the identity of "Gap Walker." Character differences come from their origin stories, what they lost, the Gap Creatures they know, and the Thresholds they won't face. This creates deeper character differentiation than a class system — because the differences come from narrative, not mechanical labels.

**On the Interaction Between Anchoring Item and Return Mark**: These two form a complementary "anchoring ecology." The Anchoring Item is internal — it comes from your personal history. The Return Mark is external — it comes from the kind connection between you and the world, between you and others. A character can have both, or only one. Losing both at once is the most dangerous state.

---

> *"You don't need to write your class on the character sheet. You only need to write — where you came from, what you lost, where you stood for a minute before a Threshold, and then decided not to cross."*
>
> — An anonymous Gap Walker, after returning their 107th Lost Item


---

## §3.1 Gap Action Economy (2 Action Point (AP) System)

### 3.1.1 Gap Turn

Time in the Gap is counted in "Gap Turns." The subjective time of each Gap Turn matches the Surface, but the actual time elapsed on the Surface is determined by the time flow (see §3.4.3).

Each Gap Turn, each character has **2 Action Points (AP)**. A character may use AP in any order within the turn — moving, observing, negotiating, exiting can be mixed freely.

### 3.1.2 Available Actions

| Action | AP | Key Attribute | DC | Failure Consequence |
|---|---|---|---|---|---|
| **Enter the Gap** | 1 | Traverse | By Threshold type (8–22) | Still enters but −2 Endurance |
| **Move** | 1 | Traverse | GM sets by distance/distortion | Double Gap Endurance cost |
| **Search for Lost Items** | 1 | Retrieval | By item quality (8–22) | Not found; GM rolls secretly |
| **Observe the Surface** | 1 | Awareness | 12 (general) | See nothing, or see wrong information |
| **Negotiate** | 1 | Negotiation | By creature's Negotiation DC (10–20) | Negotiation fails; creature attitude may worsen |
| **Exit the Gap** | 1 | Traverse | Same as entry Threshold's DC | Deviation 1d10m (see §3.7.2 Deviation Table) |
| **Confirm Layer** | 1 | Anchor | 12 | Cannot determine current layer depth |
| **Mark Location** | 2 | Anchor | 10 | Marking fails — next time cannot use that location's reduction |
| **Seal a Crack** | 3 | Negotiation | 22 | The Crack instead expands — Seal DC permanently +2 |
|> For detailed DC baselines, see Chapter One §4.3 DC Difficulty Ladder.|

### 3.1.3 First-Turn Special Actions

| Action | AP | Key Attribute | Description |
|---|---|---|---|
| **Enter the Gap** | 1 | Traverse | Enter from a Threshold. DC depends on Threshold type (see §3.1.4). Failure still enters but −2 Endurance |
| **Confirm Current Layer** | 1 | Anchor | Determine which layer of the Gap you are currently on. Failure means you cannot determine depth |

### 3.1.4 Thresholds and Entry Difficulty

| Threshold Type | Traverse DC | Example |
|---|---|---|
| Natural Threshold | 8 | Threshold of an old house, both ends of a bridge, staircase landing |
| Artificial Threshold | 12 | The same door crossed repeatedly, the moment you step onto the same balcony every day |
| Trauma Threshold | 15 | A place where a major event occurred — the entrance to a room where someone died, the doorway of the conference room where a key contract was signed |
| Memory Threshold | 18 | A Gap entrance you have crossed before — it remembers you |
| Sealed Crack | 22 | The only crack of a deliberately Sealed Space — extremely hard to enter; once in, you may never get out |

> **Attribute Range Note**: Threshold DCs are set in the 1–5 system. After switching to 1–10, a high-attribute character's Traverse (8–10) has a clear advantage against low-difficulty Thresholds (DC 8) — this is by design: a proficient Gap Walker should handle everyday Thresholds with ease. Memory Threshold (DC 18) and Sealed Crack (DC 22) still pose a challenge.

---

## §3.2 Five-Stage Gap Endurance

### 3.2.1 Endurance Formula and Maximum

```
GE Maximum (GE Max) = Anchor × 3 + 5
```

| Anchor Value | GE Max | Anchor Value | GE Max |
|---|---|---|---|
| 1 | 8 | 6 | 23 |
| 2 | 11 | 7 | 26 |
| 3 | 14 | 8 | 29 |
| 4 | 17 | 9 | 32 |
| 5 | 20 | 10 | 35 |

> When holding an Anchoring Item, GE Max +5 (see Ch2 §2.5). E.g., Anchor 7 + Anchoring Item = GE 31.

### 3.2.2 Endurance Cost

| Trigger Condition | GE Cost |
|---|---|
| Base cost per turn | –1 |
| Traverse check failure | –2 |
| Staying in a Gravity Anomaly Zone (extra per turn) | –2 |
| Deep exchange with a Gap Creature (each time) | –2 |
| Witnessing an "Unexplainable Phenomenon" (GM judgment) | –1～–3 |
| Per turn in a Sealed Space | –2 (base) |
| Crossing a Threshold (between layers) | –2 (each time) |

### 3.2.3 Five-Stage Endurance States

| Stage | GE % | Effect |
|---|---|---|
| **Stable** | > 50% | Everything normal. You clearly perceive the boundary between Gap and Surface |
| **Worn** | 25%–50% | Disadvantage on Anchor checks. You start forgetting which Threshold you entered from |
| **Eroded** | 10%–25% | Hear the Gap's whispers — not language, but fragments of emotion. Every 1d4 turns the GM gives you a fragmented perception from the Gap — which may or may not be true |
| **Critical** | < 10% | Before each action, must first pass an Anchor check (DC 12). Failure means "Lost" — GM decides your movement direction and distance that turn |
| **Depleted** | 0 | Gap Sickness outbreak — process: (1) immediately make a Gap Sickness worsening contest (see §3.6); (2) character is Forcefully Ejected to the Surface location of the "last crossed Threshold"; (3) suffers 1d4 days Exhaustion (Disadvantage on all checks); (4) Gap Sickness symptoms persist after returning to Surface. If the last crossed Threshold is unusable, eject to the nearest Natural Threshold |

### 3.2.4 Endurance Recovery

| Recovery Method | Amount | Condition |
|---|---|---|
| Return to Surface and long rest (8 hours) | All | Once per day. Removes Critical and Lost states |
| Surface short rest (1 hour) | 1d6 + Anchor | Once per Gap visit |
| Anchoring Item Meditation | Anchor × 3 | Once per day, 10 minutes focused. **Unavailable if Anchoring Item is Worn** (see Ch2 §2.5.3) |
| Return a Lost Item to its owner | +5 | Triggered at the moment of return (see Ch2 §2.9.2) |
| Help a Gap Creature Pass Over | +1d6 | Recovered after witnessing the Passing Over |
| Another Walker's assistance | +1d6 | Spend 1 hour together; the Walker makes a DC 12 Anchor check |

> **Worn Note**: For recovery methods involving the Anchoring Item, if the Anchoring Item is in a Worn state (Ch2 §2.5.3), that method is unavailable. One who lost the Anchoring Item (Ch2 §2.5.4) loses all recovery and protection effects dependent on the Anchoring Item.


## §3.4 Damage — Appearing as Conditions

> Core Design Principle: Gap Walkers do not deal "damage" to Gap Creatures — conflict in the Gap is not based on Hit Points (HP). Characters bear **Conditions** rather than losing HP.

### 3.4.1 Conflict Sources and Conditions

| Conflict Source | Consequence | Removal Condition |
|---|---|---|
| Contact with an Eroded being | **Erosion (condition)**: lose 1d4 maximum GE per turn. Stacks | Automatically removed after returning to Surface; in the Gap requires DC 15 Anchor check |
| the Mirror's active contest | **Resonance (condition)**: the GE you consume, the Mirror also bears equally. And vice versa | Removed when either side's GE drops to 0 — but the loser suffers Gap Sickness worsening |
| Lost (triggered at Critical stage) | **Lost (condition)**: Disadvantage on all directional checks, cannot mark paths. GM decides your movement | Successfully pass a DC 14 Anchor check (spend 1 AP) |
| Witnessing an Unexplainable Phenomenon | **Stun (condition)**: lose 1 AP (next turn) | Automatically removed |
| Rejected by a Path Guardian | **Repulsion (condition)**: that path cannot be attempted again for 24 hours | Wait for time to pass |
| Isolation in a Sealed Space | **Isolation (condition)**: Anchor check DC +5. You feel the Surface drifting away | Removed after leaving the Sealed Space |

### 3.4.2 Condition Chain

Certain conditions can stack into a Condition Chain — three of the same type lead to permanent consequences:

| Condition Chain | Consequence after 3 accumulations |
|---|---|
| Erosion ×3 | Maximum GE permanently –2 |
| Lost ×3 | GM secretly rolls one Gap Sickness worsening — doesn't tell you the result until you return to Surface |
| Resonance ×3 | the Mirror gains one of your memories. You no longer remember what it was — but it does |

### 3.4.3 No Death Rule

Gap Walkers do not "die" in the Gap — at least not in the traditional sense. When a character bears excessive conditions in the Gap:

- GE Depleted → acute Gap Sickness outbreak → character is Forcefully Ejected from the Gap (back to the nearest safe Threshold), suffers 1d4 days Exhaustion
- If a character fails the worsening contest three times in a row at Terminal Stage Gap Sickness → character transforms into a **Lost Item Collector** (NPC, taken over by GM)

**Gap Walkers don't die. They get lost.** — this is the core of the design.


## §3.9 Action Rules for the Surface World

> Gap Walkers don't live only in the Gap. Most Commissions begin on the Surface and end on the Surface — you need to interview clients, investigate scenes, dig through archives, persuade witnesses. This chapter defines what you can do in the Surface world.

### 3.9.1 Surface Action Types

The Surface world does not use turns. The following actions can be combined freely; the GM judges by narrative pacing when a roll is needed.

| Action | Main Attribute | Typical DC | Description |
|---|---|---|---|
| **Interview NPC** | Negotiation | 10–16 | Get information from clients, witnesses, related people. DC depends on the other party's cooperation and resistance to the truth |
| **Scene Investigation** | Awareness | 8–15 | Find clues at a physical scene — unusual traces, a Threshold's faint glow, spatial anomalies |
| **Dig Through Documents** | Retrieval | 10–14 | Find Gap-related historical records from archives, newspapers, digital data |
| **Covert Observation** | Awareness | 12–16 | Observe someone or somewhere without intervening — may discover they approach a specific Threshold at a specific time |
| **Persuade / Reassure** | Negotiation | 12–18 | Make an ordinary person accept "something is wrong" without panic; or make a client accept your unexplainable investigative methods |
| **Disguise Identity** | Negotiation | 10–14 | Enter restricted areas as a journalist, researcher, insurance investigator, etc. (using a false or half-true identity) |
| **Research Gap History** | Retrieval | 12–16 | In libraries, online, from local elders, find Gap-related legends about a specific place |

### 3.9.2 Clue Layering System

The fruits of Surface investigation are classified by "clue level." The GM should preset a level for each important piece of information — shallower clues are easy to obtain, deeper clues need more investment.

| Level | DC Baseline | Content Example |
|---|---|---|
| **Shallow Clue** | 8 | Basic facts — "Mr. Chen has lived in the nursing home for three years," "the mansion was built in 1910" |
| **Mid Clue** | 12 | Requires active questioning or careful observation — "the nurse noticed the old man always walks toward the door at dusk" |
| **Deep Clue** | 16 | Hidden truth — "the old doctor remembers the director had a small silver box he never parted with" |

**Cumulative Success**: For deep clues requiring thorough investigation, the GM may require 3 cumulative successes (not necessarily consecutive) to fully reveal.

### 3.9.3 Social DC Baseline

| Target Attitude | DC Baseline |
|---|---|
| Friendly / actively seeking help (e.g., client) | 8–10 |
| Neutral / willing to cooperate | 12 |
| Hesitant / hiding something | 14–16 |
| Resistant / fearful | 18 |
| Hostile / deliberately misleading | 20+ |

**Adjustments**:
- Holding a Lost Item related to the other party: +5
- The other party is a Sensitive (can sense the Gap but cannot cross): attitude raised one level
- Player at Late Stage Gap Sickness (translucent): −5 against normal people, +5 against the dying

### 3.9.4 Assisted Investigation

In Surface investigation, multiple characters can divide the work:

- **Division of labor**: Each handles a different action (one interviews, one investigates, one digs documents). Each rolls separately, but information is shared.
- **Assist**: One leads, another provides assistance (leader gains Advantage, rules see Ch1 §4.5).
- **Time cost**: Thorough investigation takes hours to days. The GM tracks time passing — some clues may disappear with time (witness forgets, scene is destroyed).


## §3.10 Team Collaboration Rules

> Gap Walkers rarely act alone. When 2–5 Walkers enter the Gap together, their Anchors can support each other — but they can also get Lost together.

### 3.10.1 Shared Threshold

If multiple characters enter the Gap from the same Threshold, only one needs to succeed on the Traverse check — the successful one can "guide" the others through. The guided need not roll, but still spend the corresponding GE (see §3.2.2).

**Limit**: Each guidance covers at most 2 people. The guide cannot take other actions that turn.

### 3.10.2 Endurance Shield

A high-Anchor character (Anchor ≥ 6) can spend their own GE to absorb damage for a teammate:

- Spend 1 AP, consume their own GE (1–3 points, chosen by player), to offset equal GE consumption for one teammate within line of sight.
- This ability can be used at most 2 times per scene.

**Principle**: Your Anchor is so solid that it forms a brief "safe radius" in the Gap — when teammates are within your Anchor range, the Gap's consumptive influence is weakened by your presence.

### 3.10.3 Separation & Recovery

When a character is Lost in the Gap (Lost triggered at Critical stage), other characters can:

- **Track**: Awareness DC 14, find the Lost one's direction. Spend 1 AP.
- **Call**: Negotiation DC 12, guide the Lost one with voice. The Lost one's Anchor check DC −3.
- **Shared Anchor**: If the Lost one has touched your Anchoring Item during this Gap entry, you can spend 1 AP to activate "Resonance" — the Lost one automatically senses your direction.

### 3.10.4 Anchoring Item Lending

In extreme cases, a character may temporarily lend their Anchoring Item to another:

- **Condition**: Deep trust between the two characters (GM ruling — usually requires at least one complete scenario experienced together)
- **Effect**: The borrower gains GE Max +5 and worsening-contest Advantage (as normal), but the lender loses these effects
- **Limit**: Each lending lasts at most 1 scene. After it ends, the Anchoring Item automatically returns to the lender (the Gap remembers "whose")
- **Risk**: If the Anchoring Item wears while borrowed — the lender also suffers the worn consequences

### 3.10.5 Group Exit

- **Individual exit**: Each independently makes a Traverse check, each bearing failure consequences.
- **Synchronized exit**: All hold hands, designate one to make the Traverse check. Success means all exit safely; failure means all bear exit Deviation (each rolls the Deviation Table).
- **Forced Ejection**: When any character's GE hits zero, only that character is ejected — teammates may choose whether to exit together.

### 3.10.6 Communication in the Gap

- **Short distance** (within line of sight): normal conversation. But the Gap slightly distorts sound — the other sounds farther than they are.
- **Medium distance** (same region but out of sight): Negotiation DC 10 to be heard clearly.
- **Long distance** (different Gap regions): no communication. Unless both have Known Threshold Networks and are acquaintances (see Ch2 §2.7), they can make a DC 16 Negotiation to "sense" the other's presence and rough direction.


## §3.11 Interlude: Downtime Rules

> The time between two adventures is not blank — it is the soil where characters live, recover, and grow.

### 3.11.1 Downtime Activities

After each scenario ends, characters enter Downtime. The length of Downtime is set by the GM by narrative (usually 1–4 weeks). Characters may choose **2** activities from below:

| Activity | Attribute Check | Effect |
|---|---|---|
| **Surface Rest** | No check (automatic) | If in Early Stage Gap Sickness, recover to Healthy after 7 days. Cannot choose other activities during this time |
| **Research Threshold** | Retrieval DC 12 | Find a new Threshold location. Success joins Known Threshold list; Critical Success discovers a Memory Threshold |
| **Visit Acquaintance** | Negotiation DC 10 | Deepen relationship with a Gap acquaintance — Negotiation DC permanently −1. Critical Success gains a piece of intel |
| **Seek Commission** | Negotiation DC 10 | Through the Sensitive network, receive a lead on a new Commission (GM uses this as the hook for the next scenario) |
| **Sort Lost Items** | Retrieval DC 12 | From unreturned Lost Items in hand, identify an owner's identity or location |
| **Strengthen Anchoring Item** | Anchor DC 12 | Spend time on the Surface "keeping company" with the Anchoring Item — next Gap entry, Anchoring Item Meditation recovery +2 (one-time) |
| **Part-Time Work** | No check | Maintain Surface life. Gap Walkers live a Double Life — you might work at a café while waiting for the next Threshold to glow |

### 3.11.2 Gaining New Commissions

New Commissions usually come from:
- **Ripples of the previous Commission**: the person you returned a Lost Item to last time recommends another who needs help
- **Sensitive network**: those who cannot cross but can sense the Gap — antiquarian bookshop owners, late-night café keepers, funeral workers — they watch for "something off"
- **Messages from the Gap**: a creature you met last time in the Gap gave you intel — "three Thresholds east, someone is waiting for you"

The GM should let Commission sources blend naturally into the narrative, not appear from nowhere.

### 3.11.3 Long-Term State Tracking


### 3.11.4 Double Life: a Gap Walker's Surface Survival

Most Gap Walkers live a Double Life. Daytime — or "Surface time" — they have jobs: perhaps a librarian, a convenience store clerk, a freelance photographer, or any profession that lets you "vanish for a few hours" without questions.

**Why work?**
Gap exploration doesn't pay rent. The reward for returning Lost Items is Return Marks — metaphysical wealth, unusable to buy food. Walkers need to maintain a minimal Surface existence.

**GM Guidance**:
- No need to track money numbers. Assume the character has enough income for basic living.
- When narrative needs time pressure, the GM can use "you've taken too much leave, your supervisor is noticing" as a narrative lever.
- A character may choose to invest more time in part-time work → reduce Downtime activities available (from 2 to 1).
- A character may choose a "full-time Gap Walker" life — but that means relying on the Sensitive network's support, living in cheap motels, or sleeping in 24-hour establishments. This carries no mechanical penalty, but offers rich roleplay material.

**The Role of the Sensitive**:
Those who cannot cross but can sense the Gap — the "Sensitive" — often become the Walkers' support network. They may provide:
- Temporary lodging ("I have an empty room above my shop")
- Commission referrals ("a customer says something's been off at her home lately")
- Material support ("these cans are about to expire, take them")

This is not an economy — it is a community. A Gap Walker's survival depends not on money, but on "those who know but don't say it out loud."


- If a character is still at Middle Stage or worse Gap Sickness during Downtime: the daily Anchor check must still be made (see §3.6)
- If a character chooses "Surface Rest" during Downtime: cannot simultaneously do other Downtime activities
- Holding the Anchoring Item and specially tending it during Downtime: the Anchoring Item's "Worn" recovery time shortens from 3 days to 2 days


## §3.12 Retaining and Using Lost Items

> Returning a Lost Item to its owner gains a Return Mark — but not every Lost Item can find its owner. Some owners have died, some memories' ownership is unknowable, some things you don't want to let go of yet. This chapter defines what retained Lost Items can do.

### 3.12.1 Lost Item Retention Mechanic

When you choose to retain a Lost Item (rather than return it), the following rules apply:

**Ownership Check**: Each month (in-game time), a retained Lost Item must pass an **Ownership Check** (Retrieval DC 10 + item quality tier). Failure means the item vanishes from your pocket — it found its owner, or the Gap reclaimed it. Critical Failure (natural 1) adds a subtle GM-narrated consequence (the owner sees you holding their thing in a dream).

**Retention Cap**: A character may retain at most **3** Lost Items at once. Lost Items beyond this number get "sucked back" by the Gap on next Gap entry.

### 3.12.2 Retention Effects by Quality

| Quality | Retrieval DC | Retention Effect | Ownership Check DC |
|---|---|---|---|
| **Common Lost Item** | 8 | **Emotional Resonance**: while held, Negotiation checks related to the item's emotional theme +1. E.g., an old key gives a bonus to "conversations about home." | 10 |
| **Benevolent Keepsake** | 12 | **Kind Echo**: one-time use. Consume the item (it returns to the Gap), immediately recover 1d6+2 GE in the Gap. The item fulfilled its mission. | 10 |
| **Memory Crystal** | 15 | **Memory Flashback**: activate with 1 minute of focus. GM provides a 30-second "memory scene" — you briefly see the moment the owner lost it. Usable 3 times, then the crystal shatters. After each use the GM may secretly roll for intel — perhaps a clue, name, or location. | 12 |
| **Gap Construct** | 18 | **Unpredictable Use**: effect set by GM per item design. Typical uses: key to open a specific Sealed Space, reveal an unknown Threshold's location, summon a specific Gap Creature once, or grant Traverse Advantage in a specific region. **Single use** — item vanishes after use. The GM need not reveal the use in advance — the player may need a Retrieval check to "infer" the Construct's function. | 15 |
| **the Forgotten** | 22 | **Cannot be retained**. the Forgotten is not an item — it's a person. After recovery, must help them Pass Over within 24 hours (see Ch2 §2.11.3), or they vanish back into the Gap. On successful Passing Over, gain a Return Mark. | — |

### 3.12.3 Lost Items as Negotiation Leverage

Retained Lost Items can be used in Negotiation with Gap Creatures (see Ch3 §3.3.2). A Lost Item "related" to a creature is worth "medium–high," an entirely unrelated Lost Item is worth "low–medium." After a Lost Item is used in Negotiation, whether success or failure, the item is taken by the creature — removed from your retention list.


## §3.13 Exploration Tools and Consumables

> Gap Walkers don't carry weapons — but they carry flashlights. Not to light the dark, but to confirm a shadow is still a shadow.

### 3.13.1 Exploration Tools

The following tools provide no numeric bonus — they unlock the possibility of specific actions, or grant Advantage in specific situations.

| Tool | Effect | Acquisition |
|---|---|---|
| **Flashlight / Headlamp** | No Disadvantage on Awareness checks in "lightless" Gap regions. Batteries drain twice as fast in the Gap (GM tracks). | Surface purchase (everyday item) |
| **Chalk / Glow Tape** | Can mark already-traveled paths in the Gap. Equivalent to a free "Mark Location" effect, but provides no DC −5 reduction. | Surface purchase (everyday item) |
| **Notebook and Pen** | Record Gap maps, Threshold locations, creature behavior. Each Interlude can make a "organize notes" check (Retrieval DC 10); success grants a Memory Threshold effect on one Known Threshold (next entry DC −3). | Surface purchase (everyday item) |
| **Rope (10 m)** | When moving in a Gravity Anomaly Zone, Traverse check gains Advantage (physical connection). In Directional Tilt regions can serve as an "artificial horizon" to aid orientation. | Surface purchase (everyday item) |
| **First-Aid Kit** | Treat minor injuries on the Surface. No direct mechanical effect — but gives the GM reason not to impose Disadvantage for small wounds. | Surface purchase (everyday item) |
| **Anchoring Backup Chain** | Fix the Anchoring Item to yourself with a chain. Halves the risk of losing the Anchoring Item (if it could be taken in narrative, GM grants one extra contest chance). | Self-made (requires Anchoring Item) |

### 3.13.2 Consumable Design Principles

Gap Walkers don't use magic potions or enhancement items. Consumable design follows these principles:
- **From the Surface**: all tools are everyday items, not magical items
- **Unlock options, don't grant bonuses**: tools let you "do something," not "raise something's success rate by X"
- **Have a cost**: flashlights need batteries, notebooks fill up, chalk runs out — the GM should occasionally remind of resource consumption, but need not track strictly (unless in a survival-pressure scene)

### 3.13.3 Advanced Tools (optional rule)

For longer campaigns, the GM may introduce the following advanced tools as narrative rewards:

| Tool | Effect | Acquisition Condition |
|---|---|---|
| **Gap Compass** | Always points to the "nearest Natural Threshold" in the Gap. Doesn't tell you what Threshold it is — only the direction. | Gratitude left by a Path Guardian after you help it Pass Over |
| **Resonance Mirror** | A small hand mirror. Spend 1 AP to observe within — you can see a Mirror creature's "true intent" (friendly/neutral/hostile). Each use requires a DC 12 Anchor check; failure shatters the mirror. | Gained after reaching a "fusion" ending with your own Mirror |
| **Thread of Forgetfulness** | A spool of never-ending red thin thread. Lay thread in the Gap to mark paths. When returning along it, Traverse check gains Advantage. Invisible on the Surface. | Gained from a Lost Item Collector after returning 10+ Lost Items |


# Chapter Four: World & Narrative

> *"Space is not empty. Crammed between spaces are all the forgotten things."*
> — First lesson of an old Gap Walker

---

## 4.0 Design Philosophy: The Back of the World

Before constructing the world, establish the core design principles of this chapter. These principles underpin all subsequent settings; the GM should return here when making any ruling.

### Four Core Principles

**Principle One: The Gap is not another world**
The Gap is not another dimension, parallel universe, or alternate reality. It is the "back" of the same world — like the reverse of a coin, the other side of a mirror, the "something's missing" you feel in a room. The best Gap scenes make players feel: "This has always existed, I just couldn't see it before."

**Principle Two: The Gap is made of absence**
Everything in the Gap is made of "things not on the Surface" — forgotten memories, lost items, repressed emotions, unfinished buildings, canceled plans. The Gap's "matter" is the embodiment of negative space.

**Principle Three: The Gap remembers**
The Gap is not neutral. It has a kind of "memory" — not consciousness, more like sedimentary rock. The longer you stay in the Gap, the more you feel the layers of the past piling up. This is also the root of Gap Sickness: your self-awareness begins to mix with the sediment of others' memories.

**Principle Four: Crossing has a cost**
Every crossing of a Threshold is a tiny tear — to the world, and to the Walker themselves. There is no free passage. This principle underpins, at the mechanical level, Gap Sickness, time-flow differences, and Threshold danger.

### Aesthetic Reference Coordinates

| Concept | Source | Correspondence in Rift Walker |
|------|------|-------------------|
| **Liminal Space** | Internet aesthetics / transitional spaces | The basic visual of the Gap Layer — empty office buildings, airports at 4 a.m., unfinished subway stations |
| **Kenopsia** | John Koenig, *The Dictionary of Obscure Sorrows* | The strange feeling of empty spaces — the air quality of the Gap Layer |
| **"Ma" (間)** | Japanese aesthetics | Negative space, pause, the power of silence — the core philosophical concept of the Gap |
| **"The Backrooms"** | Internet collective creation | The labyrinthine and unpredictable nature of the Gap Layer (but the Gap has more "meaning") |
| **"Invisible Cities"** | Italo Calvino | Every city has a double existence — the relationship between Surface and Gap |
| **The ice fields of "The Terror"** | Dan Simmons / TV series | The isolation of the Gap Layer and slowly accumulating dread |

---

## 4.1 The Two-Layer Worldview

### 4.1.1 The Surface: The World We Know

#### Era Setting

**Default Era: Contemporary (a flexible "now")**

The default setting of Rift Walker is **contemporary urban**, for three reasons:

1. **The contemporary nature of Liminal Space**: empty office buildings, convenience stores at dawn, malls after closing, abandoned industrial zones — the most liminal-feeling spaces are contemporary products.
2. **Tension of contrast**: When the Surface is full of crowds, technology, and information floods, the silence of the Gap is most powerful.
3. **Resonance of Lost Items**: What contemporary people lose (phones, keys, digital copies of childhood photos) players immediately understand the meaning of.

**Era Adjustment Suggestions**:

| Era | Suitable Tone | Notes |
|------|-----------|---------|
| **1980s** | Warm horror of the analog age — no phones, sparse surveillance cameras, disappearances more easily overlooked | Lost Items lean physical (cassettes, film, handwritten letters); the Gap Walker community relies more on word of mouth |
| **Near Future** | Sense of technological alienation — in a world where AR is always on, the Gap Walker is the only one who "sees the blank" | Lost Items may include digital existences (deleted AIs, abandoned virtual personas); Thresholds may appear in server rooms |
| **1990s–2000s** | Unease of a transition period — the internet just rising, the old world fading | Lost Items from both eras coexist (film and flash memory); Gap Walkers witness the world accelerating |
| **Any era** | The Gap exists in all eras — but the GM should adjust the texture of Lost Items to match the era | Medieval Lost Items are parchment and wax seals; Edo-period are woodblock prints and hairpins |

> **GM Hint**: Don't over-specify the year. Saying "like now, but unsure which year" is better — Gap Walkers themselves live in the blurry zone of time.

#### The Surface World's Perception of the Gap

Ordinary people know **almost nothing** about the Gap. But "almost" is important:

- **Intuition**: Normal people sometimes "feel something's off" — walk into a room and forget why, can't find the keys they just set down, feel an unexplained gaze in an empty parking lot. These are faint perceptions of the Gap.
- **the Sensitive**: About one in a thousand people has higher sensitivity — they more easily feel unease in liminal spaces, often dream of "the other side," occasionally see the Residual of Gap Creatures. They are not Gap Walkers, but may become Walkers' informants or clients.
- **Institutional ignorance**: Governments, corporations, and academia have zero cognition of the Gap. Any attempt to "scientize" the Gap ends in failure — not because the Gap resists study, but because researchers gradually "forget" what they were studying.
- **Folklore**: Ghost stories, urban legends, forbidden places around the world... many are actually crude human explanations of the Gap. Gap Walkers know: not ghosts, but the Gap.
