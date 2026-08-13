# Dungeon Defense Combat System v2.0

> **Design Version**: Draft v2.0 (cross-review revision)
> **Dice System**: d6 Dice Pool (5–6 = Success, 6 may explode for +1 die)
> **Opposed Rule**: Attacker pool − Defender pool = Net Successes = Effect
> **Lord Attributes**: Cunning (CUN) / Dominion (DOM) / Arcana (ARC) / Industry (IND) / Warfare (WAR), range 1–5
> **Dungeon Attributes**: Depth (DEP) / Infamy (INF) / Defense (DEF) / Wealth (WLH) / Magic (MAG), range 1–15

---

## Table of Contents

1. [Combat Framework](#i-combat-framework)
2. [Damage System](#ii-damage-system)
3. [Special Ability System](#iii-special-ability-system)
4. [Monsters & NPCs (Dual-Dimension Template)](#iv-monsters--npcs-dual-dimension-template)
5. [Monster Allocation Mechanic](#v-monster-allocation-mechanic)
6. [Monster Economy Abilities](#vi-monster-economy-abilities)
7. [Defense Layers & Room Type Alignment](#vii-defense-layers--room-type-alignment)
8. [Invasion System](#viii-invasion-system)
9. [Encounter Design Guide](#ix-encounter-design-guide)

---

## I. Combat Framework

### 1.1 Round Structure

Combat uses a **phase-based combat round structure**, each round containing the following phases:

```
┌──────────────────────────────────────────────────┐
│               Combat Round Structure               │
├──────────────────────────────────────────────────┤
│ Phase 0: Preparation Phase                        │
│   · Recon check (Cunning) reveals invader intel     │
│   · Emergency Conscription: economy monsters → combat (optional) │
│   · Lord casts pre-battle ritual/spell              │
├──────────────────────────────────────────────────┤
│ Phase 1: Initiative Phase                          │
│   · Invader rolls initiative: 1d6 + Adventurer Tier mod │
│   · Defender rolls initiative: 1d6 + Lord Cunning mod │
│   · Winner decides who acts first on this floor     │
├──────────────────────────────────────────────────┤
│ Phase 2: Action Phase                              │
│   · Both sides take unit actions in turns           │
│   · Each unit per round: 1 Move + 1 Standard + 1 Bonus │
│   · Initiative side completes all units, then other side follows │
├──────────────────────────────────────────────────┤
│ Phase 3: Environment Phase                         │
│   · Trap triggers (auto-resolved by trap type)      │
│   · Ongoing effects resolved (Burning, Poison, Curse, etc.) │
│   · Room special effects resolved                   │
├──────────────────────────────────────────────────┤
│ Phase 4: Morale Phase                              │
│   · Check both sides' morale status                │
│   · Trigger rout/shaken check (Warfare or Dominion opposed) │
│   · Monster loyalty change check                   │
├──────────────────────────────────────────────────┤
│ Phase 5: Advance Phase                             │
│   · Invader decides whether to advance to next defense layer │
│   · Defender decides whether to tactically retreat  │
│   · Battle loss tally, captive determination        │
└──────────────────────────────────────────────────┘
```

### 1.2 Initiative Rules

**Initiative Roll**:
- Invader: 1d6 + [Adventurer Tier] (T1=+0, T2=+1, T3=+2, T4=+3, T5=+4)
- Defender: 1d6 + [Lord Cunning value]

**Initiative Effect**:
- Initiative winner chooses "act first" or "act last" this round
- All units within a side act in any order during their turn
- Boss monsters have "Initiative Intervention": spend 1 Mana Crystal to insert one action during the enemy turn

**Optional Variant — Individual Initiative** (for small fights):
- Each unit rolls 1d6 + Cunning mod individually
- Act in descending order of result
- Fits: captive riots, small encounters, PC fighting personally

### 1.3 Action System

Each unit per round has:

| Action Type | Count | Description |
|---------|------|------|
| **Move** | 1 | Move to adjacent room/area. Some monsters have special movement (flight, phase through walls, shadow walk) |
| **Standard** | 1 | Attack, cast spell, use ability, defense stance, command, etc. |
| **Bonus** | 1 | Quick ability, weapon switch, drink potion, brief command |
| **Reaction** | 1 | Opportunity attack (when enemy moves from adjacent square), guard (take attack for adjacent ally), triggered ability |

**Common Standard Actions**:

| Action | Cost | Effect |
|------|------|------|
| Melee Attack | Standard | Roll Combat Power (CP) pool vs target Defense pool |
| Ranged Attack | Standard | Roll CP pool vs target Defense pool (−1 die, unless ranged trait) |
| Cast Spell | Standard | Spend Mana Crystal/Soul Essence, roll Arcana (ARC) pool |
| Defense Stance | Standard | This round's Defense pool +2, but cannot attack |
| Command | Standard | Warfare (WAR) check; success grants a friendly unit +1 attack die this round |
| Use Item | Standard/Bonus | Per item |
| Aid | Standard | +1 die to adjacent ally's next check |
| Intimidate | Standard | Warfare (WAR) vs enemy Willpower (WIL); success lowers target morale −1 |
| Retreat | Standard | Withdraw from current defense layer to next (needs Cunning check to avoid opportunity attack) |

### 1.4 Combat Status Tracking

| Status | Effect | Duration |
|------|------|------|
| **Burning** | 1 fire damage each Environment Phase | 1d3 rounds, or extinguished by water/mana |
| **Poisoned** | −1 die to pool each Action Phase | 1d3 rounds, or antidote |
| **Petrified** | Cannot act, Defense pool +2 | 1d3 rounds, or dispelled |
| **Feared** | Attack pool −2, cannot voluntarily approach fear source | 1d3 rounds, or overcome via Warfare (WAR) check |
| **Stunned** | Lose Bonus action and Reaction | 1 round |
| **Prone** | Melee against it +1 die, its melee −1 die | Spend Move to stand |
| **Restrained** | Cannot move, Defense pool −1 | Escape check (CP vs restraint strength) |
| **Cursed** | All check pools −1 | Needs ritual/spell to remove |

---

## II. Damage System

### 2.1 Damage Formula

**Core Formula**:

```
Attack Check = Attacker pool (roll d6, 5-6=success, 6 explodes +1 die)
Defense Check = Defender pool (roll d6, 5-6=success, 6 explodes +1 die)

Net Successes = Attack successes − Defense successes
Damage = max(1, Net Successes) + Weapon/Ability mod
```

**Pool Sources**:
- Attack pool = unit CP + weapon bonus + ability bonus + env bonus − negative status
- Defense pool = unit CP + armor bonus + cover/DV bonus + defense stance − negative status

**Explosion Rule**:
- Each 6 rolled, besides counting 1 success, grants +1d6
- Extra die also 5–6 = success, 6 continues exploding
- Explosion chain has no cap (theoretically infinite)

**Damage Thresholds**:
- If Net Successes ≤ 0: attack fully blocked/dodged, 0 damage
- If Net Successes = 1: graze/light hit, 1 damage
- If Net Successes ≥ 3: heavy blow! extra effect triggers (knockback/armor break/bleed, etc., by attack type)

### 2.2 Damage Types

| Damage Type | Typical Source | Special Rule |
|---------|---------|---------|
| **Slashing** | Sword, axe, claw | +1 net success vs unarmored target |
| **Piercing** | Arrow, spear, fang | Ignores 1 armor bonus |
| **Bludgeoning** | Hammer, fist, falling rock | +1 net success vs heavy armor |
| **Fire** | Dragon breath, fireball, hellfire | On hit applies "Burning" status (50% chance) |
| **Frost** | Frost breath, ice magic | On hit target's next-turn move halved |
| **Lightning** | Lightning bolt, thunderstorm | +1 net success vs metal armor target |
| **Acid** | Slime, acid trap | On hit permanently lowers target armor bonus by 1 |
| **Poison** | Venom, poison gas trap | Damage delayed: resolved at start of next turn |
| **Necrotic** | Undead magic, curse | Cannot be restored by normal healing |
| **Radiant** | Holy light, divine magic | Double damage vs undead/demon |
| **Psychic** | Mental attack, fear aura | Ignores armor, directly opposes Willpower (WIL) |

### 2.3 Defense & Resistance

**Defense Value (DV) Sources**:

| Source | DV Bonus | Note |
|------|--------|------|
| Base | 0 | No protection |
| Light Armor | +1 DV die | Leather, chain shirt |
| Medium Armor | +2 DV die | Mail, scale |
| Heavy Armor | +3 DV die | Plate, dragon-scale |
| Shield | +1 DV die | Needs one hand to wield |
| Cover | +1~2 DV die | Half cover +1, full cover +2 |
| Room Defense | +Room DV | By room type and level |
| Defense Stance | +2 DV die | Costs Standard action |

**Resistance/Weakness/Immunity**:

| Rating | Effect | Example |
|---------|------|------|
| **Immune** | That damage type = 0 | Fire Elemental immune to Fire |
| **Resistant** | That damage halved (floor, min 1) | Gargoyle resistant to Slashing |
| **Vulnerable** | That damage doubled | Ice Elemental vulnerable to Fire |
| **Absorb** | That damage becomes HP recovery | Slime absorbs Acid |

### 2.4 Hit Points & Death

**Monster HP**:

| Combat Power (CP) | Base HP | Boss HP |
|----|--------|---------|
| 1 | 3 | — |
| 2 | 5 | — |
| 3 | 7 | 12 |
| 4 | 9 | 15 |
| 5 | 11 | 18 |
| 6 | 13 | 22 |
| 7 | 16 | 26 |
| 8 | 20 | 32 |

**Monster Defeat Handling**:

| 2d6 | Result | Note |
|-----|------|------|
| 2–3 | Permanent Death | Monster fully destroyed, removed from game |
| 4–6 | Heavy Wound | Cannot fight for 3 economy turns, upkeep doubled |
| 7–9 | Light Wound | Fully recovers after 1 economy turn |
| 10–12 | Dying Counter | HP recovers to 1, can act once immediately this round, Heavy Wound after battle |

**Adventurer HP (Reference)**:

| Adventurer Tier | Individual HP | Squad Total HP (4) |
|-----------|--------|--------------|
| T1 (pool 2–3) | 4–6 | 18–24 |
| T2 (pool 4–5) | 7–10 | 30–40 |
| T3 (pool 6–7) | 11–15 | 45–60 |
| T4 (pool 8–9) | 16–22 | 65–88 |
| T5 (pool 10+) | 23–30 | 95–120 |

**Captive Rule**: When adventurer HP hits 0, roll 1d6:
- 1–2: Death (gain Soul Essence)
- 3–5: Unconscious & captured (enters captive system)
- 6: Dying, dies next round if untreated

---

## III. Special Ability System

### 3.1 Spell/Skill Tier Framework

Combat abilities split into three categories, independent yet combinable:

| Category | Driving Attribute | Resource | Typical Effect |
|------|---------|------|---------|
| **Combat Arts** | Warfare (WAR) | None (uses per battle) | Command, intimidate, tactical maneuver |
| **Cunning Tricks** | Cunning (CUN) | None (environment-dependent) | Ambush, feint, trap activation |
| **Arcane Spells** | Arcana (ARC) | Mana Crystals (MC) | Attack magic, defense magic, curses |
| **Rituals** | Arcana (ARC)/Dominion (DOM) | Soul Essence (SE) | Pre-battle curse, summon, sacrifice |

### 3.2 Spell Level & Cost

| Spell Level | Required ARC | MC Cost | Effect Pool Bonus | Example |
|---------|---------|--------|------------|------|
| Cantrip | 1 | 0 | +0 | Mage Hand, Light |
| 1st Circle | 2 | 1 MC | +1 | Magic Missile, Shield |
| 2nd Circle | 3 | 2 MC | +2 | Fireball, Invisibility |
| 3rd Circle | 4 | 3 MC | +3 | Lightning Bolt, Flight |
| 4th Circle | 5 | 5 MC | +4 | Ice Storm, Banishment |
| 5th Circle | 5+ | 8 MC | +5 | Meteor Burst, Time Stop |

**Spell Check**: Roll Arcana (ARC) pool + spell level bonus; each success = spell hit/effect. Opposed spells need target to roll corresponding Defense.

**Concentration Mechanic**:
- Some spells need "Concentration" upkeep (costs 1 Bonus action per round)
- When damaged, make an Arcana (ARC) check (difficulty = damage taken); fail breaks concentration
- Only 1 spell concentrated at a time
- Constructs/undead immune to concentration break

**Spell Range**:

| Range | Coverage |
|------|---------|
| Touch | Adjacent units within same room |
| Close | Any unit within same room |
| Medium | Any room on current defense layer |
| Far | Any room on adjacent defense layer |
| Dungeon | Entire dungeon (needs ritual hall support) |

### 3.3 Combat Spell Samples

#### Attack Spells

| Spell | Level | MC | Range | Effect |
|------|------|-----|------|------|
| **Magic Missile** | 1st | 1 | Medium | Arcana (ARC) check, each success = 1 force damage (always hits, no defense opposed) |
| **Fireball** | 2nd | 2 | Far | Arcana (ARC) check, successes = fire damage to all targets in area, targets may roll Defense for half |
| **Lightning Bolt** | 3rd | 3 | Medium | Arcana (ARC) check, successes = damage, pierces all targets in a line |
| **Finger of Death** | 4th | 5 | Touch | Arcana (ARC) vs target CP opposed, net ≥3 means target HP to 0 instantly |
| **Meteor Burst** | 5th | 8 | Dungeon | Arcana (ARC) check, 4 independent fireballs each deal successes damage, can cover whole layer |

#### Defense/Support Spells

| Spell | Level | MC | Range | Effect |
|------|------|-----|------|------|
| **Shield** | 1st | 1 | Self | Reaction cast, this round's Defense pool +3 |
| **Blur** | 1st | 1 | Self | 3 rounds, all attacks vs caster −1 die |
| **Haste** | 2nd | 2 | Touch | 3 rounds, target gains 1 extra Standard action per round |
| **Stoneskin** | 3rd | 3 | Touch | Until battle ends, target gains Slashing/Piercing/Bludgeoning resistance |
| **Greater Invisibility** | 4th | 5 | Close | 3 rounds, all friendly units in area invisible (cannot be targeted until they attack) |

#### Curse/Control Spells

| Spell | Level | MC | Range | Effect |
|------|------|-----|------|------|
| **Vulnerability Curse** | 1st | 1 | Medium | Arcana (ARC) vs target Willpower (WIL), success lowers target Defense pool −1 (whole battle) |
| **Hold Person** | 2nd | 2 | Medium | Arcana (ARC) vs target Willpower (WIL), success means target cannot act 1d3 rounds |
| **Fear** | 2nd | 2 | Close | Warfare (WAR) (instead of ARC) vs target Willpower (WIL), success means target gains "Feared" status |
| **Confusion** | 3rd | 3 | Medium | Arcana (ARC) vs WIL, success means target 50% chance to attack allies each round (3 rounds) |
| **Dominate** | 5th | 8 | Medium | Arcana (ARC) vs WIL, net ≥3 means target defects to defender side until HP to 0 |

### 3.4 Non-Magic Combat Abilities (Combat Arts / Cunning Tricks)

These need no Mana Crystals, but have per-battle use limits.

| Ability | Attribute | Uses/Battle | Effect |
|------|------|---------|------|
| **War Cry** | Warfare (WAR) | 2 | Warfare (WAR) check, each success gives all friendly units on this floor +1 attack die (1 round) |
| **Rally** | Warfare (WAR) | 1 | Warfare (WAR) check, each success restores 1 Loyalty (LOY) to a shaken monster |
| **Sneak Attack** | Cunning (CUN) | 2 | Cunning (CUN) check, deals successes×2 damage to an unaware unit |
| **Feint** | Cunning (CUN) | 1 | Cunning (CUN) vs target Cunning (CUN), success lowers target Defense pool −2 next round |
| **Emergency Repair** | Industry (IND) | 2 | Industry (IND) check, each success repairs 1 trap or restores 2 HP to a construct |
| **Field Fortification** | Industry (IND) | 1 | Industry (IND) check, each success gives this floor +1 DV (until battle ends) |

---

## IV. Monsters & NPCs (Dual-Dimension Template)

### 4.1 Monster Attribute Template

Each monster has **Combat Dimension** and **Economy Dimension** attribute sets:

#### Combat Dimension

| Attribute | Short | Meaning | Range |
|------|------|------|------|
| Combat Power | Combat Power (CP) | Combat dice pool (attack & defense) | 1–8 |
| Hit Points | HP | Damage capacity | 3–20 |
| Loyalty | Loyalty (LOY) | Obedience, affects in-battle betrayal | 1–5 |
| Armor | ARM | Extra defense dice | 0–3 |
| Speed | SPD | Rooms movable per round | 1–3 |
| Size | SIZ | Nest capacity occupied | 1–3 |
| Damage Type | DTY | Main attack damage type | Slashing/Piercing/Bludgeoning etc. |
| Combat Trait | CT | Special combat ability | — |

#### Economy Dimension

| Attribute | Short | Meaning | Range |
|------|------|------|------|
| Economy Value | BIZ | Economy output efficiency | 1–5 |
| Economy Ability | BA | Random economy ability | From 10 types |
| Upkeep | UPK | Per-turn resource cost | Varies |
| Recruit Cost | RCR | Resources to recruit | Varies |
| Best Room | BR | Room type where ability peaks | Corresponding 10 rooms |

### 4.2 Monster Examples (10, dual-dimension)

---

#### 1. Skeleton Soldier

**Combat Dimension**:
| Combat Power (CP) | HP | Loyalty (LOY) | ARM | SPD | SIZ | DTY |
|----|----|-----|-----|-----|-----|-----|
| 1 | 3 | 5 | 0 | 1 | 1 | Slashing |

**Combat Traits**:
- **Undead**: Immune to Poison, Fear, Psychic damage. Needs no food/rest.
- **Brittle**: When hit, roll 1d6, on 1–2 it crumbles instantly (ignores HP).

**Economy Dimension**:
| BIZ | BA | UPK/turn | RCR | BR |
|-----|----|---------|-----|-----|
| 1 | Random | None | 1 Soul Essence | Mine |

---

#### 2. Gelatinous Slime

**Combat Dimension**:
| Combat Power (CP) | HP | Loyalty (LOY) | ARM | SPD | SIZ | DTY |
|----|----|-----|-----|-----|-----|-----|
| 2 | 5 | 2 | 0 | 1 | 2 | Acid |

**Combat Traits**:
- **Corrosion**: On hit, permanently lowers target ARM by 1 (min 0).
- **Split**: At HP 0, roll 1d6, on 5–6 splits into 2 CP1/HP2 small slimes.
- **Acid Absorption**: Acid damage becomes HP recovery.

**Economy Dimension**:
| BIZ | BA | UPK/turn | RCR | BR |
|-----|----|---------|-----|-----|
| 1 | Random | 1 Dark Coin | 2 Mana Crystals | Research Chamber |

---

#### 3. Shadow Wraith

**Combat Dimension**:
| Combat Power (CP) | HP | Loyalty (LOY) | ARM | SPD | SIZ | DTY |
|----|----|-----|-----|-----|-----|-----|
| 2 | 4 | 3 | 0 | 2 | 1 | Necrotic |

**Combat Traits**:
- **Void**: Non-magic/non-Radiant attacks must first roll 1d6, hit only on 4+.
- **Shadow Walk**: Moving does not trigger opportunity attacks. Can pass through enemy-occupied space.
- **Radiant Weakness**: Radiant damage doubled.

**Economy Dimension**:
| BIZ | BA | UPK/turn | RCR | BR |
|-----|----|---------|-----|-----|
| 2 | Random | 1 Mana Crystal | 3 Soul Essence | Scout Outpost |

---

#### 4. Gargoyle Sentinel

**Combat Dimension**:
| Combat Power (CP) | HP | Loyalty (LOY) | ARM | SPD | SIZ | DTY |
|----|----|-----|-----|-----|-----|-----|
| 3 | 7 | 4 | 2 | 2 | 2 | Slashing |

**Combat Traits**:
- **Petrifying Gaze**: Standard action, Dominion (DOM) vs target Willpower (WIL) opposed, success means target Petrified 1d3 rounds.
- **Flight**: Can move over obstacles. Can attack from air (ground melee vs it −1 die).
- **Stone Skin**: Slashing/Piercing resistance.

**Economy Dimension**:
| BIZ | BA | UPK/turn | RCR | BR |
|-----|----|---------|-----|-----|
| 2 | Random | 1 Mana Crystal | 4 Building Materials + 3 Mana Crystals | Throne Hall |

---

#### 5. Hellhound

**Combat Dimension**:
| Combat Power (CP) | HP | Loyalty (LOY) | ARM | SPD | SIZ | DTY |
|----|----|-----|-----|-----|-----|-----|
| 3 | 7 | 3 | 1 | 3 | 2 | Piercing + Fire |

**Combat Traits**:
- **Fire Breath**: Ranged attack (Medium), on hit applies "Burning."
- **Tracking Scent**: No die penalty vs invisible/hidden units. Tracked escaping captives −2 die on checks.
- **Pack Tactics**: +1 CP when at least 1 friendly Hellhound in same room.

**Economy Dimension**:
| BIZ | BA | UPK/turn | RCR | BR |
|-----|----|---------|-----|-----|
| 2 | Random | 2 Dark Coins + 1 Mana Crystal | 4 Soul Essence + 3 Dark Coins | Prison |

---

#### 6. Elemental Construct

**Combat Dimension**:
| Combat Power (CP) | HP | Loyalty (LOY) | ARM | SPD | SIZ | DTY |
|----|----|-----|-----|-----|-----|-----|
| 4 | 9 | 5 | 2 | 1 | 3 | Variable (fire/ice/lightning choose one) |

**Combat Traits**:
- **Construct**: Immune to mind, poison, necrotic, psychic damage. Loyalty (LOY) always 5.
- **Elemental Shield**: Immune to its element, weak to opposing element (fire↔ice, lightning has none).
- **Self-Repair**: Recovers 1 HP at start of each round (unless hit by Acid).

**Economy Dimension**:
| BIZ | BA | UPK/turn | RCR | BR |
|-----|----|---------|-----|-----|
| 3 | Random | 3 Mana Crystals | 6 Building Materials + 6 Mana Crystals | Trap Workshop |

---

#### 7. Spider Swarm

**Combat Dimension**:
| Combat Power (CP) | HP | Loyalty (LOY) | ARM | SPD | SIZ | DTY |
|----|----|-----|-----|-----|-----|-----|
| 2 | 6 | 2 | 0 | 2 | 2 | Poison |

**Combat Traits**:
- **Web**: After deploy, trap trigger difficulty +1 on that room. Standard action can re-web for boost (max +2).
- **Venom**: On hit target −1 die per round (stacks 2×), until battle ends or healed.
- **Swarm**: Single-target attacks have 50% chance to only take half damage.

**Economy Dimension**:
| BIZ | BA | UPK/turn | RCR | BR |
|-----|----|---------|-----|-----|
| 2 | Random | 1 Dark Coin | 2 Soul Essence + 2 Dark Coins | Trap Workshop |

---

#### 8. Cultist Acolyte

**Combat Dimension**:
| Combat Power (CP) | HP | Loyalty (LOY) | ARM | SPD | SIZ | DTY |
|----|----|-----|-----|-----|-----|-----|
| 1 | 4 | 4 (can waver) | 0 | 1 | 1 | Bludgeoning |

**Combat Traits**:
- **Versatile**: Can make Arcana (ARC) support checks. Can take one attack for adjacent ally (Reaction).
- **Fanatic Faith**: Can spend Standard action to pray, roll 1d6, on 6 this round CP+2.
- **Sacrifice**: At HP 0 may self-detonate, dealing 2 Necrotic damage to all adjacent units.

**Economy Dimension**:
| BIZ | BA | UPK/turn | RCR | BR |
|-----|----|---------|-----|-----|
| 3 | Random | 1 Dark Coin | 5 Dark Coins | Altar |

---

#### 9. Death Knight [Elite]

**Combat Dimension**:
| Combat Power (CP) | HP | Loyalty (LOY) | ARM | SPD | SIZ | DTY |
|----|----|-----|-----|-----|-----|-----|
| 5 | 11 (18 Boss) | 4 | 3 | 2 | 2 | Slashing + Necrotic |

**Combat Traits**:
- **Undead Aura**: Friendly undead units in same room +1 CP.
- **Command Undead**: Can command up to 3 Skeleton Soldiers to act in sync (same round).
- **Necrotic Strike**: Attacks add Necrotic damage. Hit targets cannot recover HP (until battle ends).
- **Boss Phase** (triggers at HP≤6): Undead Aura extends to whole floor, self-recovers 2 HP per round.

**Economy Dimension**:
| BIZ | BA | UPK/turn | RCR | BR |
|-----|----|---------|-----|-----|
| 3 | Random | 3 Dark Coins + 1 Soul Essence | 8 Soul Essence + 10 Dark Coins | Training Ground |

---

#### 10. Master Assassin [Elite]

**Combat Dimension**:
| Combat Power (CP) | HP | Loyalty (LOY) | ARM | SPD | SIZ | DTY |
|----|----|-----|-----|-----|-----|-----|
| 4 | 9 (15 Boss) | 3 | 1 | 3 | 1 | Piercing + Poison |

**Combat Traits**:
- **Assassinate**: Before battle (Preparation Phase), may make one Cunning (CUN) check (difficulty 3 successes); success instantly kills one T1–T3 enemy unit (T4 needs 5 successes).
- **Stealth**: Considered invisible when not acting. First attack from stealth CP+2.
- **Poisoned Blade**: 3× per battle, hit applies "Poisoned" status.
- **Boss Phase** (triggers at HP≤5): Each round may Assassinate (difficulty lowered to 2 successes), and gains 1 extra Move.

**Economy Dimension**:
| BIZ | BA | UPK/turn | RCR | BR |
|-----|----|---------|-----|-----|
| 4 | Random | 4 Dark Coins | 6 Soul Essence + 12 Dark Coins | Scout Outpost |

---

### 4.3 NPC Quick Generation

#### Adventurer Squad Quick Generation Table

| Step | Operation |
|------|------|
| 1. Determine Tier | By Infamy (INF) value (see Invasion System) |
| 2. Determine size | Roll 1d6: 1–2=2, 3–4=3, 5–6=4 |
| 3. Determine class | Roll 1d6 per member: 1=Warrior, 2=Mage, 3=Rogue, 4=Cleric, 5=Ranger, 6=Random |
| 4. Determine pool | Individual = random in Tier's pool range |
| 5. Determine HP | Individual = random in Tier's HP range |
| 6. Special ability | 1–2 class traits each (GM picks or random from class table) |

#### Adventurer Class Combat Template

| Class | Pool Mod | Typical HP | Armor | Damage Type | Signature Ability |
|------|---------|--------|------|---------|---------|
| Warrior | +1 die | +2 | Heavy (+3) | Slashing/Bludgeoning | 1×/battle: double damage |
| Mage | −1 die | −2 | None (0) | Variable magic | 3 spells/battle |
| Rogue | +0 die | +0 | Light (+1) | Piercing | Sneak attack: first hit +3 dice |
| Cleric | +0 die | +1 | Medium (+2) | Bludgeoning | 2×/battle: heal 2 HP |
| Ranger | +1 die (ranged) | +0 | Medium (+2) | Piercing | 2×/battle: mark target (+1 die) |

#### Captive Cannon-Fodder Quick Generation

When throwing captives into battle as fodder:
- **Combat Pool** = Profession Level (PL) (1–5)
- **HP** = Stamina (STA) (1–5)
- **Armor** = None (0, unless given gear)
- **Special**: STA−1 each battle; if STA hits 0, dies
- **Escape**: At end of each round, if in escapable position, roll Willpower (WIL) to flee

### 4.4 Boss Phase Mechanic

Boss monsters (CP≥5 and with Boss tag) have phase-transition ability:

```
Phase Transition Rule:
┌─────────────────────────────────────────┐
│ Boss HP drops below 50% → trigger transition │
│                                         │
│ 1. Boss immediately gains 1 free action  │
│ 2. Clear all negative statuses           │
│ 3. Activate second-phase traits          │
│ 4. Battlefield environment may change    │
│                                         │
│ Boss HP below 25% → optional third phase │
│ (legendary monsters CP7+ only)          │
│ 1. Same as second phase flow            │
│ 2. Activate ultimate ability (1×/battle) │
└─────────────────────────────────────────┘
```

**Boss Design Checklist**:
- [ ] Base CP/HP/ARM
- [ ] First-phase traits (1–2)
- [ ] Second-phase traits (HP≤50%, 1–2 new)
- [ ] (Optional) Third-phase traits (HP≤25%, ultimate)
- [ ] Environment change at transition
- [ ] Loot drop

---

## V. Monster Allocation Mechanic

### 5.1 Economy vs Combat Deployment

Each monster must be assigned to **Economy** or **Combat** each economy turn (choose one):

```
┌──────────────────────────────────────────────────────┐
│                   Monster Deployment Decision          │
├──────────────────────┬───────────────────────────────┤
│    Deploy to "Economy"│       Deploy to "Combat"       │
├──────────────────────┼───────────────────────────────┤
│ · Not counted in layer combat power │ · Counted in layer combat power (CP pool) │
│ · Produces resources/build progress │ · Forfeits economy output          │
│ · Economy ability passive active      │ · Economy ability still passively active │
│ · Contributes output by Economy Value │ · Participates in invasion defense battle │
├──────────────────────┼───────────────────────────────┤
│ Switch deploy: costs 1 action │ Switch deploy: costs 1 action        │
│ (except Emergency Conscription) │                              │
└──────────────────────┴───────────────────────────────┘
```

**Economy Deployment Output Table**:

| Economy Value (BIZ) | Resource/turn | Build progress/turn | Room Bonus |
|-------------|-------------|-------------|------------|
| 1 | Corresponding resource ×1 | 0 | — |
| 2 | Corresponding resource ×2 | 1 | — |
| 3 | Corresponding resource ×3 | 1 | +1 efficiency tier to room |
| 4 | Corresponding resource ×4 | 2 | +1 efficiency tier to room |
| 5 | Corresponding resource ×5 | 2 | Room effect doubled |

**Corresponding resource** by monster's "Best Room (BR)":
- Mine → Building Materials + Dark Coins
- Research Chamber → Mana Crystals
- Altar → Soul Essence
- Treasury → Dark Coins
- Other rooms → by room output type

### 5.2 Emergency Conscription Rules

When an invasion occurs (Preparation Phase), any number of economy-deployed monsters may be urgently recalled to combat:

```
Emergency Conscription Flow:
┌──────────────────────────────────────────┐
│ 1. Declare conscription in Preparation Phase │
│ 2. Select target monsters (unlimited count)  │
│ 3. Monster switches economy→combat instantly │
│ 4. Pay the price                             │
└──────────────────────────────────────────┘
```

**Price**:
- **Resource Interruption**: That monster's economy output this turn cleared (already produced not retroactive)
- **Confusion Penalty**: Conscripted monsters −1 die on first battle round
- **Loyalty Shock**: Loyalty (LOY)≤2 monsters conscripted immediately make loyalty check (1 success = defect)

**Mitigation**:
- If monster deployed in "Training Ground": ignore confusion penalty
- If Lord Warfare (WAR)≥4: confusion penalty from −1 die to −0 die (no penalty)
- If monster Loyalty (LOY)=5: ignore loyalty shock

### 5.3 Boss Battle Minimum Defense Line

**Core Layer Guard Rule**:
- The core layer (where Throne Hall sits) **must always keep at least 1 monster** in combat deployment
- That monster can be any CP, but must be able to fight
- Violating this = dungeon exposed, invaders may attack Throne Hall directly (Defense (DEF)=0, Lord fights alone)

**Sovereign Guard**:
- By default, Lord designates 1 monster as "Sovereign Guard"
- Sovereign Guard Loyalty (LOY)+1, and +1 CP when fighting in Throne Hall
- Sovereign Guard cannot be deployed to economy (always combat)
- After Sovereign Guard defeated, Lord may designate a new guard (effective next economy turn)

---

## VI. Monster Economy Abilities

### 6.1 Economy Ability List (10 types)

Each monster randomly gains one of these 10 economy abilities. Economy abilities **are always passively active**, whether monster is economy- or combat-deployed — but effect doubles when deployed in its "Best Room."

---

#### BA-01: Sentinel
> *"Its eyes never close in the dark."*

| Attribute | Content |
|------|------|
| **Passive Effect** | Recon +1, Preparation Phase reveals 1 extra invader intel |
| **Combat Impact** | Invaders cannot ambush the room this monster occupies (lose first-round initiative advantage) |
| **Best Room** | Scout Outpost (doubled: Recon +2, reveal 2 extra intel) |

---

#### BA-02: Armorer
> *"It polishes blades with its claws, tempers arrows with its spit."*

| Attribute | Content |
|------|------|
| **Passive Effect** | All trap damage on its defense layer +1 |
| **Combat Impact** | 1×/battle, spend Bonus action to repair 1 triggered trap (reactivate) |
| **Best Room** | Trap Workshop (doubled: trap damage +2, can repair 2 traps/battle) |

---

#### BA-03: Tactician
> *"It passes orders with a low growl, coordinates attacks with a glance."*

| Attribute | Content |
|------|------|
| **Passive Effect** | All other monsters on same floor +1 Defense pool (self excluded) |
| **Combat Impact** | 1×/battle, can reassign attack targets for all friendly units on floor (optimize fire) |
| **Best Room** | Training Ground (doubled: same-floor monsters' attack pool also +1) |

---

#### BA-04: Fortifier
> *"Its presence makes walls stronger, ground steadier."*

| Attribute | Content |
|------|------|
| **Passive Effect** | Its defense layer's DV +2 |
| **Combat Impact** | Invaders must spend 2 Moves to enter this monster's room |
| **Best Room** | Mine (doubled: DV+4, also gives all same-floor friendlies +1 ARM) |

---

#### BA-05: Overseer
> *"Its whip keeps captives from slacking, its presence keeps fodder from retreating."*

| Attribute | Content |
|------|------|
| **Passive Effect** | Captive labor efficiency +50% (output ×1.5) |
| **Combat Impact** | All captive fodder on floor +1 combat die, captive fodder escape check −1 die |
| **Best Room** | Prison (doubled: captive labor ×2, fodder combat +2 dice) |

---

#### BA-06: Alchemist
> *"Its secreted slime corrodes metal, its breath ignites flame."*

| Attribute | Content |
|------|------|
| **Passive Effect** | Research Chamber Mana Crystal output +1/turn |
| **Combat Impact** | 2×/battle, spend 1 Mana Crystal to give all floor monsters' attacks Fire or Acid damage (2 rounds) |
| **Best Room** | Research Chamber (doubled: Mana Crystal +2/turn, alchemy uses +2) |

---

#### BA-07: Beastmaster
> *"Its roar makes beasts submit, its breath calms monsters."*

| Attribute | Content |
|------|------|
| **Passive Effect** | Monsters in same room Loyalty (LOY)+1 (self included), Loyalty won't drop from losses in battle |
| **Combat Impact** | 1×/battle, can command 1 shaken monster in same room back into battle (cancels escape/defect check) |
| **Best Room** | Monster Den (doubled: same-floor monsters Loyalty (LOY)+1, new recruits start +1 Loyalty) |

---

#### BA-08: Ritualist
> *"Its chanting nears prayer; its very presence is a sacrifice to dark powers."*

| Attribute | Content |
|------|------|
| **Passive Effect** | Altar ritual effect +25% (Soul Essence output +1 per 2 rituals) |
| **Combat Impact** | Each Environment Phase, roll 1d6: on 6 one wounded monster on floor recovers 2 HP (on 5–6 if deployed at Altar) |
| **Best Room** | Altar (doubled: ritual effect +50%, healing triggers every round in battle) |

---

#### BA-09: Treasure Hunter
> *"It always finds the coins adventurers hide — wherever they are."*

| Attribute | Content |
|------|------|
| **Passive Effect** | After defeating invaders, gain extra 1d3 Dark Coins (wherever deployed) |
| **Combat Impact** | 1×/battle, can "mark" one enemy unit as "fat sheep," defeat grants extra 2d3 Dark Coins |
| **Best Room** | Treasury (doubled: extra 2d3 Dark Coins, vault interest +1 per 10 stored) |

---

#### BA-10: Intimidator
> *" Merely its shadow is enough to make adventurers' knees tremble."*

| Attribute | Content |
|------|------|
| **Passive Effect** | At invasion start, entire adventurer squad morale −1 (first-round attack pool −1) |
| **Combat Impact** | Standard action Warfare (WAR) check (vs target Willpower (WIL)), success means target gains "Feared" status |
| **Best Room** | Throne Hall (doubled: morale −2, fear duration doubled) |

---

### 6.2 Economy Ability Random Assignment Table

| d10 | Economy Ability | Short |
|-----|---------|------|
| 1 | Sentinel | SENT |
| 2 | Armorer | ARMR |
| 3 | Tactician | TACT |
| 4 | Fortifier | FORT |
| 5 | Overseer | OVRS |
| 6 | Alchemist | ALCH |
| 7 | Beastmaster | BSTM |
| 8 | Ritualist | RITL |
| 9 | Treasure Hunter | TRSR |
| 10 | Intimidator | INTM |

**Reroll Rule**: If 3+ monsters already share the same economy ability, reroll.

---

## VII. Defense Layers & Room Type Alignment

### 7.1 Defense Layer Structure

The dungeon splits from outside to inside into 4 defense layers, each corresponding to a Depth range and buildable room types:

```
┌─────────────────────────────────────────────────────────┐
│                     Dungeon Defense Layers                 │
├─────────────┬──────────┬────────────────┬───────────────┤
│  Defense Layer │ Depth Range │  Buildable Room Types │  Defense Trait  │
├─────────────┼──────────┼────────────────┼───────────────┤
│ Outer Line   │ Depth (DEP) 1-2 │ Scout Outpost    │ Warning +1 round │
│ (Outer)      │          │ Trap Workshop    │ Trap dice +2     │
│              │          │                 │ Base DV=1       │
├─────────────┼──────────┼────────────────┼───────────────┤
│ Middle Line  │ Depth (DEP) 3-4 │ Monster Den      │ Monster cap +2   │
│ (Middle)     │          │ Training Ground  │ Monster LOY+1    │
│              │          │ Prison           │ Base DV=2       │
├─────────────┼──────────┼────────────────┼───────────────┤
│ Inner Line   │ Depth (DEP) 5-6 │ Mine            │ Resource protect │
│ (Inner)      │          │ Research Chamber │ Base DV=2       │
│              │          │ Treasury         │ Barricade buff  │
├─────────────┼──────────┼────────────────┼───────────────┤
│ Core Line    │ Depth (DEP) 7+  │ Throne Hall ★    │ Final defense   │
│ (Core)       │          │ Altar           │ Base DV=3       │
│              │          │                 │ Boss battle only│
└─────────────┴──────────┴────────────────┴───────────────┘
```

★ Throne Hall must always be in the Core Line. Core Line breached = dungeon defeat.

### 7.2 Special Slots & Room Type Alignment

Each defense layer has **Monster Slots**, **Trap Slots**, and **Special Slots**. Special Slots are determined by the room types the layer contains:

| Room Type | Defense Layer | Special Slot Name | Special Slot Effect |
|---------|-----------|-----------|-----------|
| **Scout Outpost** | Outer | Warning Slot | Warning +1 round; Lord Cunning (CUN) recon check +1 die. Reveals adventurer class composition |
| **Trap Workshop** | Outer | Chain Trap Slot | After a trap triggers on this floor, may chain-detonate first trap of adjacent layer (1 free extra trigger) |
| **Monster Den** | Middle | Den Guardian Slot | Monster deployed here +1 CP, +2 HP, +1 Loyalty (LOY) |
| **Training Ground** | Middle | Tactical Command Slot | Lord Warfare (WAR) check +1 die when on this floor. 1×/battle: this slot's monster can command all floor monsters to act simultaneously |
| **Prison** | Middle | Cannon-Fodder Release Slot | In emergency, release up to 2 captives to fight (power = PL, no action cost). Survivors may escape after battle |
| **Mine** | Inner | Barricade Slot | Spend 2 Building Materials: this floor DV temporary +3 (until battle ends). Reusable |
| **Research Chamber** | Inner | Magic Amplification Slot | Arcana (ARC)-related checks +2 dice. 1×/battle free 1st-circle spell (no MC) |
| **Treasury** | Inner | Mercenary Hire Slot | Spend 5 Dark Coins: summon 1 T2 mercenary temporarily (this battle). 1×/battle |
| **Altar** | Core | Ritual Curse Slot | Before battle, one curse ritual (Arcana (ARC) check), each success lowers whole invader squad pool −1 (whole battle) |
| **Throne Hall** | Core | Lord's Throne | Slot where Lord fights personally. Lord uses Warfare (WAR) pool in combat. Cannot be occupied by monsters |

### 7.3 Defense Layer Value Overview

| Defense Layer | Monster Slots | Trap Slots | Special Slots | Base DV | Monster Cap |
|--------|--------|--------|--------|--------|---------|
| Outer | 2 | 3 | 1–2 | 1 | Depth (DEP)×1 |
| Middle | 3 | 2 | 1–2 | 2 | Depth (DEP)×1.5 |
| Inner | 2 | 1 | 1–2 | 2 | Depth (DEP)×1 |
| Core | 2 | 1 | 1 | 3 | Depth (DEP)×0.5 |

**Total Defense Power** = Σ(monster CP deployed per layer) + Σ(trap pools) + Σ(room DV) + special slot bonuses + Lord Warfare (WAR) bonus

---

## VIII. Invasion System

### 8.1 Invasion Trigger Formula

**Invasion Check**: At end of each economy turn, GM makes an invasion check:

```
Invasion Check = Infamy (INF) + 1d6

If result ≥ 8 → Invasion triggers
If result < 8 → This turn is safe
```

**Invasion Frequency Expectation**:

| Infamy (INF) | d6 needed | Probability | Expected interval |
|-----|-----------|------|------------|
| 1 | 7+ | 0% → floored to 1/6 (guarantee) | ~6 turns |
| 2 | 6+ | 16.7% | ~6 turns |
| 3 | 5+ | 33.3% | ~3 turns |
| 4 | 4+ | 50% | ~2 turns |
| 5 | 3+ | 66.7% | ~1.5 turns |
| 6 | 2+ | 83.3% | ~1.2 turns |
| 7+ | Auto trigger | 100% | Every turn |

**Design Note**: INF≥7 means invasion every turn, the dungeon is everyone's target. Players must lower INF or strengthen defense.

### 8.2 Infamy (INF) vs Adventurer Tier

| INF Range | Invasion Check Result | Adventurer Tier | Individual Pool | Squad Power (4) | Squad Total HP |
|---------|------------|-----------|---------|-------------|---------|
| 1–3 | 8–9 | T1 Novice | 2–3 dice | 8–12 dice | 18–24 |
| 4–6 | 10–11 | T2 Proficient | 4–5 dice | 16–20 dice | 30–40 |
| 7–9 | 12–13 | T3 Elite | 6–7 dice | 24–28 dice | 45–60 |
| 10–12 | 14–15 | T4 Hero | 8–9 dice | 32–36 dice | 65–88 |
| 13–15 | 16+ | T5 Legendary | 10+ dice | 40+ dice | 95–120 |

**Special Invasion Events** (roll 1d6, on 6 triggers):
- Infamy (INF) 1–3: "Reckless Novice" — T1 squad but with unexpectedly good gear (loot +50%)
- Infamy (INF) 4–6: "Bounty Hunter" — T2 squad with 1 T3 captain
- Infamy (INF) 7–9: "Adventurers' Guild Expedition" — double-size T3 squad
- Infamy (INF) 10–12: "Heroes Assemble" — T4 squad + 1 T5 legendary hero
- Infamy (INF) 13–15: "Trial of the Gods" — T5 squad + deity avatar (CP=12 Boss-grade adventurer)

### 8.3 Wave Generation

**Standard Wave Generation Algorithm**:

```
Input: Infamy (INF) value
Output: Invasion wave config

Step 1: Roll invasion check (Infamy (INF) + 1d6)
Step 2: If ≥ 8, look up base Tier
Step 3: Roll 1d6 for squad size: 1-2=2, 3-4=3, 5-6=4
Step 4: Roll class per member: 1d6 → Warrior/Mage/Rogue/Cleric/Ranger/Random
Step 5: Roll special event: 1d6, on 6 triggers special invasion
Step 6: Generate each member's combat data (pool, HP, abilities)
Step 7: Squad total power = Σ(individual pool)
Step 8: Compare vs defender total power → determine difficulty
```

**Difficulty Levels**:

| Attack/Defense Ratio (Invader total pool : Defender total pool) | Difficulty | GM Hint |
|----------------------------------|------|--------|
| < 0.5:1 | Easy | Crushing; monsters feast |
| 0.5:1 ~ 0.8:1 | Simple | Defender clear advantage |
| 0.8:1 ~ 1.2:1 | Even | Classic challenge, uncertain |
| 1.2:1 ~ 2:1 | Hard | Defender at disadvantage, needs strategy |
| > 2:1 | Desperate | Likely to fall, prepare emergency plan |

---

## IX. Encounter Design Guide

### 9.1 Difficulty Budget

**Defender Power Budget Formula**:

```
Defense Total Pool = Σ(combat-deployed monster CP)
            + Σ(trap pools)
            + Room DV dice bonus
            + Lord combat bonus (if fighting personally = Warfare (WAR) value)
            + Economy ability bonus (Tactician, Fortifier, etc.)
```

**Recommended Defense Power per Layer** (by Adventurer Tier):

| Defense Layer | T1 Target | T2 Target | T3 Target | T4 Target | T5 Target |
|--------|--------|--------|--------|--------|--------|
| Outer | 4–6 dice | 6–8 dice | 8–10 dice | 10–12 dice | 12–15 dice |
| Middle | 6–8 dice | 8–10 dice | 10–13 dice | 13–16 dice | 16–20 dice |
| Inner | 4–6 dice | 6–8 dice | 8–10 dice | 10–13 dice | 13–16 dice |
| Core | 6–8 dice | 8–10 dice | 10–12 dice | 12–15 dice | 15–20 dice |

**Design Principle**: Adventurers must spend power breaking each layer (HP loss, spell spend) — Outer consumes by probing, Middle by main force, Inner by resources, Core is the decisive battle.

### 9.2 Encounter Construction Principles

#### Principle 1: Gradual Escalation
- Outer: Recon + traps mainly, drain invader resources and HP
- Middle: Main monster group, head-on
- Inner: Protect resource rooms, defend and counter
- Core: Boss battle, total showdown of remaining strength

#### Principle 2: Variety
- At least 2 different damage types of monsters per layer
- Trap types complement monster abilities (e.g. Spider Swarm + Trap Workshop)
- Avoid all monsters same CP — mix high and low

#### Principle 3: Resource Game
- Leave players "deployment tradeoff" space: which monsters economy? which combat?
- Emergency Conscription brings short-term gain but long-term cost
- Make economy ability choices have real combat impact

#### Principle 4: Narrative Integration
- Invaders aren't random — their class composition reflects the Adventurers' Guild's knowledge of the dungeon
- Boss monsters should have names, personalities, history with the Lord
- Battle results affect dungeon narrative (Infamy rise/fall, survivor revenge, guild attitude shift)

### 9.3 Quick Encounter Build Table

| Step | Content | Time |
|------|------|------|
| 1 | Determine invasion Tier (Infamy (INF) check) | 10 sec |
| 2 | Roll squad size and class | 15 sec |
| 3 | Quick-generate combat data | 30 sec |
| 4 | Compare vs defender power | 10 sec |
| 5 | Adjust difficulty (if needed) | 20 sec |
| **Total** | | **~1.5 min** |

---

## Appendix A: Combat Flow Diagram

```
Economy turn ends
      │
      ▼
┌─────────────┐
│ Invasion Check│ ← Infamy (INF) + 1d6
│ (≥8 triggers)│
└──────┬──────┘
       │ triggers
       ▼
┌─────────────┐
│ Preparation  │ ← Recon (Cunning (CUN)), Emergency Conscription, pre-battle ritual
└──────┬──────┘
       │
       ▼
┌─────────────┐
│ Outer Line   │ ← Invaders enter
│ Battle starts│
└──────┬──────┘
       │ invaders break through?
       ▼
┌─────────────┐
│ Middle Line  │
│ Main battle  │
└──────┬──────┘
       │ invaders break through?
       ▼
┌─────────────┐
│ Inner Line   │
│ Resource guard│
└──────┬──────┘
       │ invaders break through?
       ▼
┌─────────────┐
│ Core Line    │ ← BOSS battle
│ Final showdown│
└──────┬──────┘
       │
       ▼
┌─────────────┐
│ Win/Loss     │ → Victory: captives + loot
│             │ → Defeat: dungeon falls narrative
└─────────────┘
```

## Appendix B: Dice System Alignment Confirmation

| Item | dice-mechanics spec | combat-system implementation | Aligned |
|------|-------------------|-------------------|------|
| Dice type | d6 | d6 | ✅ |
| Success face | 5–6 | 5–6 | ✅ |
| Explosion | 6 grants +1 die | 6 grants +1 die | ✅ |
| Opposed check | Attack − Defense = net success | Attack − Defense = net success | ✅ |
| Adventurer T1 pool | 2–3 dice | 2–3 dice | ✅ |
| Adventurer T2 pool | 4–5 dice | 4–5 dice | ✅ |
| Adventurer T3 pool | 6–7 dice | 6–7 dice | ✅ |
| Adventurer T4 pool | 8–9 dice | 8–9 dice | ✅ |
| Adventurer T5 pool | 10+ dice | 10+ dice | ✅ |
| Lord attributes | Cunning (CUN)/Dominion (DOM)/Arcana (ARC)/Industry (IND)/Warfare (WAR) (1–5) | Uniformly used | ✅ |
| Dungeon attributes | Depth (DEP)/Infamy (INF)/Defense (DEF)/Wealth (WLH)/Magic (MAG) (1–15) | Combat mainly uses Defense (DEF) and Infamy (INF) | ✅ |

## Appendix C: Character System Alignment Confirmation

| Item | character-builder spec | combat-system implementation | Aligned |
|------|----------------------|-------------------|------|
| 10 room types | Throne Hall/Trap Workshop/Monster Den/Prison/Mine/Research Chamber/Treasury/Altar/Training Ground/Scout Outpost | Defense layer special slots map 1:1 | ✅ |
| Monster CP range | 1–8 | 1–8 (base/elite/legendary) | ✅ |
| Monster Loyalty (LOY) | 1–5 | 1–5 | ✅ |
| Captive combat | Power = PL | Combat pool = PL | ✅ |
| Infamy (INF) 1–15 | Determines invasion Tier & frequency | Invasion formula Infamy (INF)+1d6≥8 | ✅ |
| Defense (DEF) 1–15 | Fortification strength | Mapped to base DV (Defense (DEF)/5 floored) | ✅ |

---

> **Designer**: Zhan Zhige (combat-designer)
> **Version**: v2.0 cross-review revision
> **Status**: Pending owner confirmation; pending final alignment with dice-mechanics/character-builder
