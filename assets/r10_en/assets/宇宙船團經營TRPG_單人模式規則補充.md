# Starship Convoy TRPG — Solo Mode Rules Supplement

> *Version 1.0*

> **Audience:** 1 Player + 1 Game Master (GM)
> **Prerequisite Reading:** Player Manual + Game Master (GM) Manual (core rules unchanged; this supplement modifies only the multiplayer-dependent parts)
> **Citation Marks:** `[Player§X.X]` = corresponding section of the Player Manual / `[GM§X.X]` = corresponding section of the Game Master (GM) Manual

---

# Chapter One: Solo Mode Design Rationale

## 1.1 Why Is This Supplement Needed?

The original rules' core design revolves around the "Convoy" — multiple ships, multiple captains, voting decisions. When only one player is present, the following systems cannot operate directly:

| Original System | Multiplayer Dependency | Solo Alternative |
|-----------------|------------------------|------------------|
| Convoy Voting `[Player§2.6]` `[GM§4.7]` | Requires multiple captains to vote | **Crew Council** — the player discusses with NPC Bridge Crew; the player makes the final decision |
| Convoy Coordinated Combat `[GM§1.11]` | Requires multiple player ships | **Wingmate System** — the player commands their own ship + up to 2 NPC wingmates |
| Convoy Relationship Value `[Player§2.6]` | Players score each other | **Ally Reputation** — friendliness with NPC captains/factions |
| Crew Poaching `[Player§2.5]` | Other player captains poach your crew | **Loyalty Crisis Events** — NPC factions/hostile captains attempt to poach |
| Convoy Resource Sharing `[GM§5.2]` | Multiple ships allocate resources | **Single-Ship Resource Management** — simplified tracking, priorities discussed by the Crew Council |

## 1.2 Core Design Goals

- Preserve the "crisis management × crew daily life" road-movie tone
- Upgrade NPC crew from "data" to "characters" — they are your Crew Council
- Ensure combat depth is not reduced by solo play
- Provide a complete Lv1–10 growth curve

---

# Chapter Two: Crew Council (Replacing Convoy Voting)

## 2.1 What Is the Crew Council?

Whenever the original rules require Convoy Voting `[GM§4.7]`, use the **Crew Council** instead:

> Your Bridge Crew (First Mate, Engineer, Navigator, Communications Officer) each voice opinions based on their personality and information. After listening, you make the **final decision** — but this decision affects the crew's Loyalty and Morale.

## 2.2 Council Procedure

1. **The GM describes the situation** — the decision that needs to be made (route choice, resource allocation, whether to accept a dangerous commission)
2. **Each Bridge Crew member voices an opinion** (the GM roleplays based on that NPC's personality and Hidden Agenda)
3. **The player may ask questions, rebut, or persuade a specific crew member** (Diplomacy (DIP) contest check)
4. **The player makes the final decision**
5. **Adjust Loyalty based on how well the decision aligns with each crew member's stance**

## 2.3 Disagreement and Loyalty Impact

| Crew Stance vs. Your Decision | Loyalty Change |
|-------------------------------|:--------------:|
| Crew member strongly agrees with your decision | +1 (max 2 per chapter) |
| Crew member disagrees but you successfully persuade them | No change |
| Crew member disagrees and you directly overrule them | -1 |
| You ignore the same crew member's opinion three times in a row | -2 |
| A crew member's Hidden Agenda conflicts with your decision `[GM§3.3]` | -1 ~ -4 (depending on conflict severity) |

> **Design Note:** This preserves the "dramatic tension of losing a vote" from the original rules — merely changed in form from "being outvoted by other captains" to "making a decision your First Mate vehemently opposes."

## 2.4 Emergency Decisions (In Combat)

Quick decisions in combat follow the original rules `[GM§4.7]`, but changed to:

- The player decides directly (you are the Captain)
- But if the player hesitates for more than 30 seconds → the GM may have the First Mate "interject" with a suggestion
- The First Mate's suggestion may help or mislead (based on their Command (CMD) attribute)

---

# Chapter Three: Wingmate System (Replacing Convoy Coordination)

## 3.1 Overview

In solo mode, you primarily command your own ship. But in specific situations, you can gain the support of NPC wingmates. Wingmates are not full PCs — they are simplified friendly starships.

## 3.2 Wingmate Types

| Type | Source | Availability | Control Method |
|------|--------|:------------:|----------------|
| **Ally Captain** | An NPC captain allied in the story | Specific mission / chapter | Player gives simple orders, GM executes |
| **Mercenary Escort** | Hired for money | Stationed during paid period | Follows the player, fights autonomously (GM controlled) |
| **Story Wingmate** | Specific segments of the main story | Story-limited | GM controlled |

## 3.3 Wingmate Orders

Each turn, the player may give each wingmate one simple order (does not cost an action):

| Order | Effect |
|-------|--------|
| **Concentrate Fire** | The wingmate attacks the player's current target |
| **Cover Me** | The wingmate uses reactive interception against enemies attacking the player (if point defense is available) |
| **Keep Distance** | The wingmate moves to long range and uses ranged weapons |
| **Free Action** | The GM decides the best action based on the wingmate captain's personality |

## 3.4 Wingmate Simplified Rules

Wingmates do not track full resources (fuel, ammunition, etc.) — the GM only needs to track:

- Hull Points (HP) and damage stages
- Energy (simplified: fixed recovery of 2 each turn)
- Weapons (use the preset configuration)

**Wingmates are not affected by "poaching" or "loyalty changes"** — they are story tools, not long-term management objects.

## 3.5 Combat Balance Without Wingmates

When the player fights alone, the GM should:

- Reduce enemy count by 30–50% (relative to multiplayer convoy encounters)
- Avoid TL3+ enemies that require convoy coordination to defeat (unless this is an intentional high-difficulty challenge)
- Add encounters where combat is optional (Diplomacy, detour, stealth)
- Refer to the following solo difficulty adjustment table:

| Original Encounter (Multiplayer) | Solo Adjustment |
|----------------------------------|-----------------|
| 1d3+1 light raiders | 1d2 light raiders |
| 1 medium + 1d2 light | 1 medium raider (no escort) |
| 1 heavy flagship + 2d3 light | Change to a non-combat encounter or grant a story wingmate |

---

# Chapter Four: NPC Crew Depth System

## 4.1 Bridge Crew Role Upgrade

In solo mode, your NPC crew are **not just bonus providers** — they are your primary interaction targets. The GM is advised to prepare the following for each Bridge Crew member:

| Element | Description |
|--------|-------------|
| **Personality Keywords** (3) | Quick RP reference (e.g., "loyal, conservative, superstitious") |
| **Catchphrase** | A signature line |
| **View of Captain** (initial) | admiration / respect / suspicion / fear |
| **Personal Goal** | Besides the Hidden Agenda, a public, long-term minor goal |

## 4.2 Crew Personal Storylines

Replace the "internal convoy events" `[GM§4.15]` from the original rules with crew personal storylines:

| d12 | Event |
|:---:|-------|
| 1 | The First Mate privately requests a one-on-one talk — about one of the Captain's recent decisions |
| 2 | The Engineer discovers a hidden compartment in the engine room — possibly the previous owner's |
| 3 | The Navigator has a nightmare about the star system ahead — the details are disturbingly specific |
| 4 | The Communications Officer intercepts an encrypted message about the Captain — sender unknown |
| 5 | The Medical Officer requests a stop at the next port to handle "personal matters" — unwilling to elaborate |
| 6 | Two crew members argue in the mess hall — the Captain must mediate |
| 7 | A crew member's birthday — the others secretly prepare a surprise |
| 8 | A crew member receives the last communication from their home colony — the colony is facing a crisis |
| 9 | The crew discovers something "moving" on the ship — it could be a stowaway, or it could be a hallucination |
| 10 | The First Mate proposes a bold improvement suggestion — but implementation is risky |
| 11 | The Communications Officer hears their own name on a monitored channel |
| 12 | A crew member accomplishes something amazing in their off-time — a painting, a song, or an invention |

## 4.3 Loyalty Crisis (Replacing Poaching)

The original rule's poaching mainly came from other player captains. Solo mode uses the following triggers instead:

| Trigger | Effect |
|---------|--------|
| Meeting an NPC captain in port offering "better terms" | Diplomacy (DIP) contest: your Command (CMD) vs. the NPC's Diplomacy (DIP) |
| A crew member receives a message from family / old captain | If unhandled, Loyalty -1 |
| A faction directly recruits the crew member | You must resolve it before the next port call (negotiate / persuade / let the crew member choose) |
| A crew member's Hidden Agenda is exploited by a hostile faction | May lead to betrayal or information leak |
| Three consecutive months without a bonus | Loyalty -1 (same as the original rule `[Player§2.5]`) |

---

# Chapter Five: Solo-Mode-Specific Rule Adjustments

## 5.1 Starting Setup

A solo-mode player starts at Lv1, using standard character creation `[Player§2.1-2.8]`, but with the following adjustments:

- **Starting Crew:** 4 (one extra — you fly alone and need a more complete bridge team)
- **Starting Funds:** background starting credits + 2,000 credits (Cr) (compensates for having no convoy resource sharing)
- **Hull Allocation:** may use free allocation or a preset ship type (suggest choosing the **Nomad-class** or **Star Rover-class** — versatile ships suit solo survival better)

## 5.2 XP Adjustment

Solo players face more challenges, so the XP gain rate is adjusted:

| Source | Original XP | Solo XP |
|--------|:-----------:|:-------:|
| Complete a target chapter | 500 | 600 |
| Personal background sidequest | 300 | 400 |
| Crew personal story completed | 100 | 150 |
| Discover a new star system | 50 | 50 (unchanged) |
| Each combat | 50–100 | 75–150 |

## 5.3 Resource Management Simplification

With no convoy shared resources, tracking is simplified to:

- Only track your own ship's resources (fuel, food, parts, ammunition, medicine)
- Port service fees see `[GM§5.1]`
- Optionally track NPC wingmate resources (default: not tracked; the GM decides when a wingmate needs resupply based on the story)

## 5.4 Reputation System

The solo-mode reputation system is the same as `[Player§2.6b]`, but adds:

| Event | Reputation Progress |
|-------|:-------------------:|
| Defeat a TL2+ enemy alone | +1 |
| Rescue an NPC captain / colony | +2 |
| An NPC ally publicly praises you | +1 |
| Being wanted simultaneously by multiple factions | -2 |

---

# Chapter Six: NPC Ally System (Replacing Convoy Relations)

## 6.1 Ally Reputation Levels

Replacing the original rule's Convoy Relationship Value `[Player§2.6]`, use **Ally Reputation** to track your relationship with important NPCs:

| Value | Level | Effect |
|:-----:|-------|--------|
| -3 ~ -1 | Hostile / Cold | NPC refuses cooperation, may actively obstruct |
| 0 | Neutral | Normal interaction |
| 1–2 | Friendly | Willing to provide intel, small favors |
| 3–4 | Trusted | Can sortie as a wingmate, willing to lend resources |
| 5–6 | Ally | Willing to ally long-term, risk their life to rescue you in peril |
| 7+ | Life-and-Death Bond | Willing to sacrifice for you, unlocks special story |

## 6.2 How to Raise Ally Reputation

| Action | Change |
|--------|:------:|
| Complete an NPC's personal quest | +2 |
| Rescue an NPC's ship in combat | +3 |
| Provide resources / intel when the NPC needs them | +1 |
| Publicly support an NPC's stance | +1 |
| Betray an NPC's trust | -4 |
| Stand by idly while an NPC faces danger | -2 |

## 6.3 Starting Allies

At the start of solo mode, the player automatically gains a **starting ally** (determined by background):

| Background | Starting Ally |
|-----------|---------------|
| Bankrupt Merchant | Old client "Echo" — an independent trader who owes you a favor (Reputation 3) |
| Defected Officer | Former subordinate "Kane" — defected with you but chose a different path (Reputation 4) |
| Academic Exile | Mentor "Dr. Orion" — still at the university, helps you secretly (Reputation 3) |
| Interstellar Smuggler | Black-market contact "Shadow" — you saved their life (Reputation 4) |
| Colonist Survivor | Fellow villager "Leah" — a childhood playmate who escaped together with you (Reputation 5) |
| Mercenary Captain | Former teammate "Iron Fist" — retired but owes you a life (Reputation 4) |
| Religious Pilgrim | Fellow devotee "Brother Ezekiel" — still at the temple, prays for you (Reputation 3) |
| Explorer | Rival-turned-friend "Kasha" — once discovered a major ruin together (Reputation 3) |

> The starting ally is not necessarily on the ship — they may be a port contact, a chance-met friendly ship, or a distant pen pal. The GM arranges a substantive interaction with the starting ally before the end of Chapter One.

---

## Citation Index

| This Supplement Cites | Original Rule Location |
|-----------------------|------------------------|
| Convoy Voting `[GM§4.7]` | GM Manual §4.7 Convoy Voting System |
| Convoy Coordination `[GM§1.11]` | GM Manual §1.11 Convoy Coordinated Tactics |
| Crew Loyalty `[Player§2.5]` | Player Manual §2.5 Your Crew |
| Port Services `[GM§5.1]` | GM Manual §5.1 Port Services and Trade |
| Convoy Resources `[GM§5.2]` | GM Manual §5.2 Convoy Shared Resource Rules |
| Convoy Relations `[Player§2.6]` | Player Manual §2.6 Convoy Relations and Goals |
| Reputation System `[Player§2.6b]` | Player Manual §2.6b Your Reputation |
| Internal Convoy Events `[GM§4.15]` | GM Manual §4.15 Internal Convoy Events Table |
| Combat Voting `[GM§4.7]` | GM Manual §4.7 Convoy Voting System (in-combat instant voting) |
| Crew Hidden Agenda `[GM§3.3]` | GM Manual §3.3 Crew Hidden Agenda Bank |
