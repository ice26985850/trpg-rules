# Nation Building TRPG — Player's Handbook

> **Version:** v1.0  
> **Design Premise:** You are no adventurer — you are the King. Your attributes are national data, your adventures are diplomatic negotiations, and your battles are the building of a nation that can survive in this world.  
> **Players:** 1 player + 1 Game Master (GM). Optional multiplayer mode (each player governs a nation).

---

## Table of Contents

1. [Chapter One: Game Overview](#chapter-one-game-overview)
2. [Chapter Two: Core Rules — Dice & Checks](#chapter-two-core-rules--dice--checks)
3. [Chapter Three: Nation Creation](#chapter-three-nation-creation)
4. [Chapter Four: National Attributes & Derived Values](#chapter-four-national-attributes--derived-values)
5. [Chapter Five: The Race System](#chapter-five-the-race-system)
6. [Chapter Six: Era Progression](#chapter-six-era-progression)
7. [Chapter Seven: Construction System](#chapter-seven-construction-system)
8. [Chapter Eight: Nation Ideals & Policies](#chapter-eight-nation-ideals--policies)
9. [Chapter Nine: Turn-Based Game Flow](#chapter-nine-turn-based-game-flow)
10. [Chapter Ten: Diplomacy & Conflict](#chapter-ten-diplomacy--conflict)
11. [Chapter Eleven: Hero Units](#chapter-eleven-hero-units)
12. [Chapter Twelve: Crisis Management](#chapter-twelve-crisis-management)
13. [Chapter Thirteen: Equipment, Items & Magic Applications](#chapter-thirteen-equipment-items--magic-applications)
14. [Appendix](#appendix)

---

## Chapter One: Game Overview

### 1.1 What Kind of Game Is This?

**Nation Building TRPG** is a tabletop role-playing game centered on "nation management." Unlike traditional TRPGs, you do not play a sword-swinging adventurer hunting monsters — instead, you play **a ruler who builds a nation from nothing**.

Your "Hit Points (HP)" are your population; your "equipment" is your infrastructure; your "skill tree" is your technology and magic systems. Starting from a small camp of 50 people, you pass through the Tribal Age, City-State Age, Kingdom Age, and Empire Age, and may eventually enter the Legendary Age — building a Sky City, and conversing with the gods.

### 1.2 The Core Game Loop

```
Nation Creation → Turn Start (Spring) → Player Declares Action →
Check & Roll → Action Resolution → Crisis Trigger → Turn End →
Next Turn (Summer) → ... (four turns per year) → Era Progression
```

### 1.3 What Do You Need to Prepare?

| Item | Description |
|------|------|
| This rulebook | This very document |
| Nation Sheet | Records your nation's data (Excel sheet or printed blank sheet) |
| A set of dice | At least one twenty-sided die (d20); a standard dice set is recommended |
| Paper & pen | For taking notes and calculating data |
| A GM | The Game Master runs the world, plays neighboring nations, and triggers events |

### 1.4 Core Terminology

| Term | Full Name | Description |
|------|------|------|
| Population (POP) | Population | Total number of the nation's citizens, determines labor force and troop supply |
| Resources (RES) | Resources | Composite output capacity of food, minerals, timber, and other natural resources |
| Economy (ECO) | Economy | Trade networks, monetary system, tax efficiency |
| Military (MIL) | Military | Army size, equipment quality, strategic capability |
| Technology (TEC) | Technology | Technical level, research speed, magic systems |
| Morale (MOR) | Morale | Citizen loyalty, cultural cohesion, happiness index |
| National Power (NP) | National Power | The nation's composite influence, used for diplomatic opposition |
| Difficulty Class (DC) | Difficulty Class | The target value a check must reach |
| Modifier (MOD) | Modifier | The bonus/penalty an attribute adds to a check |
| Game Master (GM) | Game Master | The person who runs the game and plays the world |

---

## Chapter Two: Core Rules — Dice & Checks

### 2.1 The Dice System: d20 + Modifier

This game uses the **d20 System** — roll a twenty-sided die (1d20), add the relevant attribute Modifier (MOD), and compare it against the target Difficulty Class (DC).

**Check formula:**

```
Check Result = 1d20 + Attribute Modifier (MOD) + Other Bonuses/Penalties

Success Condition: Check Result ≥ Difficulty Class (DC)
```

### 2.2 Attribute Modifier (MOD)

Every 5 points in the National Six Dimensions provides +1 Modifier (⌊(Attribute − 10) ÷ 5⌋), letting highly developed nations retain a clear edge on specialized checks, and the growth outpaces the pressure of Crisis Difficulty Class (DC) increases:

| Attribute Range | Modifier (MOD) |
|-----------|-------------|
| 1 – 4 | -2 |
| 5 – 9 | -1 |
| 10 – 14 | 0 |
| 15 – 19 | +1 |
| 20 – 24 | +2 |
| 25 – 29 | +3 |
| 30 – 34 | +4 |
| 35 – 39 | +5 |
| 40 – 44 | +6 |
| 45 – 49 | +7 |
| 50 – 54 | +8 |
| 55 – 59 | +9 |
| 60 – 64 | +10 |
| 65 – 69 | +11 |
| 70 – 74 | +12 |
| 75 – 79 | +13 |
| 80 – 84 | +14 |
| 85 – 89 | +15 |
| 90 – 94 | +16 |
| 95 – 99 | +17 |
| 100+ | +1 for every +5 |

**Formula:** MOD = ⌊(Attribute Value − 10) ÷ 5⌋ (rounded down)

### 2.3 Difficulty Class (DC)

| Difficulty | DC | Description | Example |
|------|-----|------|------|
| Trivial | 5 | Almost impossible to fail | Build a simple wooden palisade |
| Easy | 10 | Easily achieved by anyone experienced | Clear a small farmland |
| Normal | 15 | Requires some competence | Establish trade with a neutral neighbor |
| Hard | 20 | Requires professional skill or luck | Persuade a hostile neighbor to cease fire |
| Very Hard | 25 | Even experts face risk | Build an oasis city in the desert |
| Legendary | 30 | Beyond mortal reach | Persuade two nations to set aside a generations-old feud and fight together |

### 2.4 Advantage (ADV) & Disadvantage (DIS)

In certain situations, the GM grants "roll Advantage" or "roll Disadvantage":

- **Advantage (ADV):** Roll 2d20, take the **higher** result
- **Disadvantage (DIS):** Roll 2d20, take the **lower** result

Advantage and Disadvantage cancel each other out (one Advantage + one Disadvantage = a normal roll).

### 2.5 Critical Success & Critical Failure

- **Critical Success (Crit):** Natural 20 (d20 shows 20) → automatic success, plus an extra benefit
- **Critical Failure (Fumble):** Natural 1 (d20 shows 1) → automatic failure, plus negative consequences

### 2.6 Check Types

#### Standard Check

Player declares action → GM decides the applicable attribute and difficulty → player rolls → compare result.

```
Player: "I want to persuade the neighbor to open a trade route."
GM: "This is a diplomatic negotiation. Use the higher of Economy (ECO) and Morale (MOR), difficulty 15."
Player: Rolls 1d20; Economy (ECO) 30 → Modifier +2; rolls 14 → total 16 → Success!
```

#### Opposed Check

Both sides roll simultaneously and compare results. Used for diplomatic negotiations, wars, espionage, etc.

```
Nation A (National Power 45, MOD +7) vs Nation B (National Power 30, MOD +4)
Nation A rolls 12 + 7 = 19
Nation B rolls 7 + 4 = 11
→ Nation A wins, gaining the upper hand in the trade negotiation
```

#### Group Check (Multiplayer Mode)

When multiple players' nations cooperate on a single great endeavor, the overall effort succeeds if at least half of the players succeed.

#### Aid Check

When one character (the ruler themselves, an advisor, or a hero) assists another's action, the helper first makes an Aid Check of `1d20 + relevant attribute` (difficulty 10):

- **Success:** The main actor gains a **+2 bonus** (an action may only be aided once).
- **Critical Success (natural 20):** The main actor gains a **+4 bonus**.
- **Failure:** No bonus; a **Critical Failure (natural 1)** instead imposes a **−2 penalty** on the main actor.

In solo play, an advisor Non-Player Character (NPC) played by the GM may likewise initiate an Aid Check.

### 2.7 Seasonal Modifiers

Different seasons bring environmental modifiers to checks:

| Season | Effect |
|------|------|
| Spring | Diplomacy checks gain +1 Modifier (all things renew; envoys travel frequently) |
| Summer | Construction checks gain Advantage (ADV) (ample sunlight, high construction efficiency) |
| Autumn | Trade checks gain +2 Modifier (harvest season, caravans come and go) |
| Winter | Construction checks gain Disadvantage (DIS); food consumption ×1.3; disease event chance rises |

---

## Chapter Three: Nation Creation

You are not creating a character — you are creating a nation. Below is the six-step nation creation process.

### Step One: Choose an Origin

Why did your first citizens gather together? Choose an origin:

| Origin | Description | Attribute Impact |
|------|------|----------|
| **Refugees** | Fled war or persecution, seeking a new home | Morale (MOR)+10, Military (MIL)-5 |
| **Pioneers** | Dreamers and settlers who actively sought new land | Resources (RES)+10, Economy (ECO)-5 |
| **Rebels** | Former resistance fighters who fled tyranny, carrying military experience | Military (MIL)+10, Morale (MOR)-5 |
| **Expedition** | Hired or volunteer explorers who discovered this land | Technology (TEC)+10, Population (POP)-5 |
| **Exiled Nobility** | Nobles who lost their lands, and their followers | Economy (ECO)+10, Resources (RES)-5 |
| **Faithful** | Believers following a religious leader in search of a holy site | Morale (MOR)+10, Technology (TEC)-5 |

### Step Two: Choose Racial Composition

Choose your initial population's race. You may choose a **single race** or a **dual-race mix**:

- **Single race:** That race's "aptitude bonus" value is **doubled** (see Chapter Five race table), and initial Racial Satisfaction is **+10**; the advantage is an extremely strong single specialty, the drawback is a lack of diversity and greater sensitivity to special needs.
- **Dual-race mix:** Each race's "aptitude bonus" is taken at **100%** (original value, not doubled), but unlocks "Cultural Fusion" — specific fusion buildings enjoy a **20% discount**, and the Racial Satisfaction cap is higher; the drawback is an initial Racial Satisfaction of only **50** (must be raised through policy management).

> Upon completing nation creation, your nation immediately gains **starting Gold 150** and **starting Food 200** (see Chapter Four derived values and resource stockpiles), enough to kick off construction in the first turn.

**Initial Population:** Regardless of racial composition, initial Population (POP) is 50 (± origin adjustment).

See [Chapter Five: The Race System](#chapter-five-the-race-system).

### Step Three: Choose Geography

What environment is your initial territory located in?

| Terrain | Advantage | Disadvantage | Resource Output |
|------|------|------|----------|
| **Forest** | Resources (RES)+10, abundant timber | Military (MIL)-5, limited visibility | Wood, Game, Herbs |
| **Plains** | Population (POP)+10, developed agriculture | Military (MIL)-5, no natural barrier | Food, Pasture |
| **Mountains** | Military (MIL)+10, easy to defend | Resources (RES)-5, limited farmland | Ore, Stone |
| **Coast** | Economy (ECO)+10, convenient shipping | Population (POP)-5, maritime threats | Fish, Salt, Trade Port |
| **Riverside** | Resources (RES)+5, Population (POP)+5 | Military (MIL)-10, flood risk | Irrigation, Fishing, Transport |
| **Highland** | Technology (TEC)+10, open vistas | Economy (ECO)-5, poor access | Special Minerals, Stargazing |

### Step Four: Distribute Initial Attribute Points

The National Six Dimensions base value is **10**. You have **30 extra points** to distribute freely (for a total of 40 points across the six dimensions, plus origin and terrain bonuses).

| Step | Calculation |
|------|----------|
| Base value | Each attribute starts at 10 |
| Free distribution | 30 points distributed across the six dimensions (each at least 0, at most +15) |
| Origin bonus | Add the origin's bonuses/penalties |
| Terrain bonus | Add the terrain's bonuses/penalties |
| Race bonus | Add the race's aptitude bonuses/penalties (see Chapter Five) |

**Initial value range:** The initial value of the six dimensions is usually between 15 and 55.

### Step Five: Choose a Nation Ideal

Choose a core value that determines the nation's long-term development direction:

| Nation Ideal | Core Effect | Policy Direction |
|----------|----------|----------|
| **Military Power** | Military (MIL)+10, military unit cost -20% | Conquest, expansion, military tech |
| **Trade Hub** | Economy (ECO)+10, trade income +30% | Commerce, diplomacy, shipping |
| **Magic Realm** | Technology (TEC)+10, research points +50% | Magic, alchemy, arcane research |
| **Free City-State** | Morale (MOR)+10, population growth rate +20% | Culture, immigration, democratic experiment |

See [Chapter Eight: Nation Ideals & Policies](#chapter-eight-nation-ideals--policies).

### Step Six: Meet Your First Neighbor

The GM sets up a neighboring power based on your chosen starting region. Record:
- The neighbor's name and racial composition
- Their initial attitude toward you (relationship value: -100 to +100)
- Their approximate National Power level

---

## Chapter Four: National Attributes & Derived Values

### 4.1 The National Six Dimensions (Six Attributes)

| Attribute | Abbrev | Core Function | Low Value Impact | High Value Impact |
|------|------|----------|----------|----------|
| Population (POP) | POP | Labor, conscription cap, market size | Labor shortage, weak taxes | Large market, strong army |
| Resources (RES) | RES | Food output, building material supply | Famine risk, stalled construction | Self-sufficiency, exports |
| Economy (ECO) | ECO | Taxation, trade, currency stability | Inflation, deficits, poverty | Full treasury, investment |
| Military (MIL) | MIL | Army quality, defense capability | Invasion risk, pirates | Deterrence, expeditions |
| Technology (TEC) | TEC | Research speed, magic level | Backwardness, unable to face new threats | Tech lead, patents |
| Morale (MOR) | MOR | Loyalty, culture, happiness | Rebellion, emigration | Patriotism, cultural export |

### 4.2 Derived Attributes

#### Derived Ability Values (auto-calculated each turn)

| Derived Attribute | Abbrev | Formula | Use |
|----------|------|----------|------|
| National Power (NP) | NP | Population (POP) × 0.5 + Resources (RES) + Economy (ECO) + Military (MIL) | International influence, diplomatic opposition baseline |
| Tax (TAX) | TAX | Economy (ECO) × Population (POP) × 0.01 | Gold gained per turn |
| Food Consumption (FOD) | FOD | Population (POP) × 0.8 (Winter × 1.3) | Food consumed per turn |
| Research Points (RP) | RP | Technology (TEC) × 0.5 | Tech progress gained per turn |
| Population Cap (CAP) | CAP | 10 + Resources (RES) × 5 | Max population current infrastructure can support |
| Military Cap (MCP) | MCP | Population (POP) × 0.1 + Military (MIL) × 0.5 | Total military units that can be maintained |

#### Resource Stockpiles (variables requiring long-term tracking)

| Resource | Abbrev | Initial Value | Change Rules |
|------|------|--------|----------|
| Gold (GOLD) | Gold | **150** | Per turn: + Tax (TAX) − building maintenance − troop wages − other expenses |
| Food (FOOD) | Food | **200** | Per turn: + food output (Autumn ×2) − food consumption (FOD); if < 0 then set to 0 and Morale (MOR) −5 |
| Wood (MAT_WOOD) | Wood | 30 | Produced per turn by production buildings such as lumberyards; or bought at market at 1 Gold = 1 Wood |
| Stone (MAT_STONE) | Stone | 20 | Produced per turn by production buildings such as quarries; or bought at market at 1 Gold = 1 Stone |
| Iron Ore (MAT_IRON) | Iron | 10 | Produced per turn by production buildings such as mines; or bought at market at 1 Gold = 1 Iron Ore |

> Building materials (Wood / Stone / Iron Ore) are **separate stockpiles**, calculated independently from the abstract attribute "Resources (RES)." When a building's cost lists "Stone 100," deduct it from the Stone stockpile; if insufficient and a market has been built, you may buy the shortfall with Gold (1 Gold = 1 building material). In the Tribal Age without a market, you must first build the corresponding production building (lumberyard→Wood, quarry→Stone, mine→Iron Ore) or obtain it through trade with neighbors.

### 4.3 Attribute Changes

Attributes change during play for the following reasons:

| Cause | Affected Attribute | Magnitude |
|------|----------|----------|
| Construction complete | By building type | +1 ~ +10 |
| Era upgrade | All attributes | × 1.2 (rounded) |
| War defeat | Population (POP), Military (MIL), Resources (RES) | -5 ~ -30 |
| Crisis resolved successfully | By crisis type | +1 ~ +5 |
| Crisis resolution failed | By crisis type | -3 ~ -15 |
| Trade agreement | Economy (ECO) | +2 ~ +10 |
| Hero action | By action type | Variable |

---

## Chapter Five: The Race System

### 5.1 Race List

| Race | Abbrev | Aptitude Bonus | Pop. Growth | Special Need | Cultural Trait |
|------|------|----------|----------|----------|----------|
| **Human (HUM)** | Human | Economy (ECO)+5, Morale (MOR)+5 | +0% | No special need | Highly adaptable, neutral diplomacy |
| **Dwarf (DWA)** | Dwarf | Resources (RES)+10 | +0% | Requires mountain terrain to maintain satisfaction | Master forger, building cost −20% |
| **Elf (ELF)** | Elf | Technology (TEC)+10 | +0% | Requires forest cover > 30% | Magic affinity, extremely long-lived |
| **Orc (ORC)** | Orc | Military (MIL)+10 | +0% | Requires at least one battle/hunt per turn | War cry intimidation, morale rarely drops |
| **Halfling (HAL)** | Halfling | Economy (ECO)+5, Morale (MOR)+5 | **+20%** | Avoid war exceeding 3 turns | Agriculture expert, food output +20% |
| **Dragonborn (DRA)** | Dragonborn | Military (MIL)+5, Technology (TEC)+5 | +0% | Requires the special building "Dragon Nest Temple" | Prestige bonus, diplomatic deterrence |
| **Gnome (GNO)** | Gnome | Technology (TEC)+10 | +0% | Requires "Invention Workshop" to maintain satisfaction | Research acceleration, invention chance +10% |
| **Goliath (GOL)** | Goliath | Military (MIL)+5, Resources (RES)+5 | **−50%** | Slow population growth | Construction efficiency +30%, defense bonus |

> **Single-race bonus calculation**: When choosing a single race, the "aptitude bonus" values in the table above are **doubled** (e.g., single Human → Economy +10, Morale +10). When choosing a dual-race mix, each takes its original value (not doubled), but unlocks the "Cultural Fusion" advantage (see Step Two). The adjustments in the "Population Growth" column apply to the population natural-growth formula at turn resolution (see Chapter Nine).

### 5.2 Racial Satisfaction

Each race has an independent satisfaction (0 – 100). When a race's satisfaction falls below 30, it may trigger **unrest**:

| Satisfaction | Effect |
|--------|------|
| 80 – 100 | That race's output +20%, may volunteer for the army |
| 50 – 79 | Operates normally, no special effect |
| 30 – 49 | That race's output -10%, mild discontent |
| 10 – 29 | That race's output -30%, protest event chance rises |
| 0 – 9 | May rebel — that race's population may secede or defect to a neighbor |

**Ways to maintain satisfaction:** Build race-exclusive buildings, enact fair policies, and avoid favoring a single race.

### 5.3 Multi-Race Nations

Multi-race nations can unlock **Race & Culture Fusion** tech:

| Race Combination | Fusion Reward |
|----------|----------|
| Human + any other race | Diplomatic relationship improvement speed +50% |
| Dwarf + Elf | Unlock special building "Mithril Forge" (gains both Technology (TEC) + Resources (RES)) |
| Dwarf + Goliath | Unlock "Mountain Fortress," defense +40% |
| Elf + Dragonborn | Unlock "Dragon Magic" — a special spell system |
| Orc + Halfling | Military-agricultural unity — military units consume no extra food |

---

## Chapter Six: Era Progression

### 6.1 The Five Eras

| Era | Trigger Condition | Duration | Main Theme |
|------|----------|----------|--------|
| **Tribal Age** | Initial | ~1-20 turns | Survival, foundation |
| **City-State Age** | Population (POP) > 250 | ~20-60 turns | Expansion, competition |
| **Kingdom Age** | National Power (NP) > 150 + "City Wall" built | ~60-120 turns | Diplomacy, conquest |
| **Empire Age** | National Power (NP) > 350 + at least one ally | ~120-200 turns | Governance, export |
| **Legendary Age** | Technology (TEC) > 150 + special event | Until game end | Breakthrough, myth |

### 6.2 Era Progression Effects

Each time you enter a new era:
1. **All attributes × 1.2** (rounded)
2. **Unlock a new batch of buildings, units, policies**
3. **Crisis difficulty rises** (DC increases by 2)
4. **Trigger an era event** (arranged by the GM)

> **On growth and caps**: This game has **no traditional level / experience-point system** — a nation's growth comes from "construction accumulation" and "era progression," plus the legendary deeds of heroes. After the Legendary Age there is **no hard level cap**; the game's ending is decided by the scenario's conclusion or by the players together.

### 6.3 Unlocked Content by Era

| Era | New Buildings | New Military Units | New Diplomatic Options |
|------|--------|-----------|-----------|
| Tribal | Farmland, Hunter's Hut, Wooden Palisade, Well | Militia, Hunter | Exchange supplies |
| City-State | Market, Barracks, Stone Wall, Port | Infantry, Archer, Scout | Trade Agreement, Send Ambassador |
| Kingdom | Castle, University, Mint, Naval Dockyard | Knight, Siege Engine, Warship | Military Alliance, Marriage Alliance, Vassalage |
| Empire | Grand Arena, Royal Academy, Expedition Camp | Cannon, Dragon Rider, Colonial Army | Colonize, Cultural Export, Hegemony Declaration |
| Legendary | Sky City (Wonder), Teleport Gate | Golem Legion, Aerial Fleet | Planar Diplomacy, Divine Covenant |

---

## Chapter Seven: Construction System

### 7.1 Construction Categories

| Category | Icon | Main Effect |
|------|------|----------|
| Infrastructure (INF) | 🏠 | Population capacity, resource output, basis of national operation |
| Economy (ENC) | 💰 | Gold income, trade efficiency, market size |
| Military (MLC) | ⚔️ | Defense value, military cap, unit unlock |
| Technology (TEC) | 📚 | Research points, new tech unlock, magic capability |
| Culture (CUL) | 🎭 | Morale, cultural influence, tourism income |
| Special (SPC) | ⭐ | Unique effects, wonder bonuses, one-time powerful rewards |

### 7.2 Construction Rules

The number of buildings you may construct per turn depends on available labor:

```
Construction cap per turn = Population (POP) × 0.05 (at least 1 item)
```

Each building has:

| Parameter | Description | Example |
|------|------|------|
| Build cost | Gold, stone, wood, etc. | 200 Gold + 50 Wood |
| Build time | Turns required | 2 turns |
| Labor demand | Population occupied | Occupies 10 population |
| Prerequisite building | Building that must be built first | Requires "Library" |
| Tech requirement | Required Technology (TEC) value | Technology (TEC) > 30 |
| Era requirement | Era that must be reached | City-State Age |
| Maintenance | Gold consumed per turn | 5 Gold/turn |
| Effect | Benefit the building provides | Economy (ECO)+5 |

**Building material stockpiles**: The "Wood / Stone / Iron Ore" in a building's cost are separate stockpiles (see Chapter Four resource stockpiles). With the corresponding production building (lumberyard, quarry, mine), they are produced automatically each turn; otherwise they can be bought at market at **1 Gold = 1 material** (in the Tribal Age without a market, you must first build production buildings or trade with neighbors).

**Ongoing gold consumption (gold sink)**: To avoid early false poverty and late-game gold overflow, two deductions are made at turn resolution:
- **Building maintenance** = total of all built "Gold cost" × 2% (rounded).
- **Troop wages** = total of all units' "cost" × 2% (rounded); militia are exempt from wages.
(See Chapter Four resource stockpiles and Chapter Nine turn-end resolution.)

**Build time (City-State and above)**: Tribal buildings are marked in each table (1–2 turns); City-State Age buildings uniformly 2 turns; Kingdom Age 2–3 turns; Empire Age 3–4 turns; Legendary Age 4–5 turns (the GM may fine-tune by scale).

### 7.3 Tribal Age Buildings

| Building | Category | Cost | Time | Effect |
|------|------|------|------|------|
| Farmland | Infrastructure (INF) | 50 Gold | 1 turn | Food output +10, Resources (RES)+2 |
| Hunter's Hut | Infrastructure (INF) | 40 Gold, 20 Wood | 1 turn | Food output +5, Military (MIL)+1 |
| Wooden Palisade | Military (MLC) | 60 Gold, 30 Wood | 1 turn | Defense value +5 |
| Well | Infrastructure (INF) | 30 Gold | 1 turn | Population Cap +10 |
| Warehouse | Infrastructure (INF) | 80 Gold | 2 turns | Resource storage cap +50 |
| Simple Shrine | Culture (CUL) | 50 Gold | 1 turn | Morale (MOR)+2 |
| Workshop | Technology (TEC) | 100 Gold | 2 turns | Technology (TEC)+2, Research Points (RP)+1/turn |
| Trading Post | Economy (ENC) | 60 Gold | 1 turn | Economy (ECO)+2, may conduct basic trade with neighbors |
| Lumberyard | Infrastructure (INF) | 50 Gold | 1 turn | Wood (MAT_WOOD)+5/turn |
| Quarry | Infrastructure (INF) | 80 Gold | 1 turn | Stone (MAT_STONE)+6/turn |
| Mine | Infrastructure (INF) | 120 Gold | 2 turns | Iron Ore (MAT_IRON)+2/turn |

> Lumberyard / Quarry / Mine are the Tribal Age's main source of building materials; without them, the Wood / Stone / Iron Ore in building costs can only come from neighbor trade or (after the City-State Age) market purchase.

### 7.4 City-State Age New Buildings (selected)

| Building | Prereq | Cost | Effect |
|------|------|------|------|
| Market | Trading Post | 200 Gold | Economy (ECO)+5, Tax (TAX)+10% |
| Stone Wall | Wooden Palisade | 300 Gold, 60 Stone | Defense value +15 |
| Barracks | — | 250 Gold | Military (MIL)+5, unlocks Infantry |
| Port | Coast terrain | 350 Gold | Economy (ECO)+5, unlocks fishing boats and trade ships |
| Library | Workshop | 200 Gold | Technology (TEC)+5, Research Points (RP)+3/turn |
| Merchant Guild | Market | 300 Gold | Trade income +20% |
| Smithy | — | 200 Gold, 50 Iron Ore | Military unit equipment +1 |
| Temple | Simple Shrine | 250 Gold | Morale (MOR)+5, cultural influence +10 |

### 7.5 Kingdom Age New Buildings (selected)

| Building | Prereq | Cost | Effect |
|------|------|------|------|
| Castle | Stone Wall + Barracks | 1,000 Gold, 300 Stone | Defense value +30, era-upgrade condition |
| University | Library | 800 Gold | Technology (TEC)+10, Research Points (RP)+8/turn |
| Mint | Merchant Guild | 600 Gold | Economy (ECO)+10, Tax (TAX)+25% |
| Naval Dockyard | Port | 700 Gold | Military (MIL)+5, unlocks Warship |
| Embassy | — | 500 Gold | Diplomatic relationship improvement speed +50% |
| Arena | — | 400 Gold | Morale (MOR)+8, Gold income +5/turn |

### 7.6 Empire Age & Legendary Age Buildings

(Detailed data in the GM Guide's complete building table.)

---

## Chapter Eight: Nation Ideals & Policies

### 8.1 The Four Nation Ideals

#### Military Power

| Stage | Effect |
|------|------|
| Base | Military unit cost -20%, Military (MIL)+10 |
| Development | Unlock policy "Nation of Soldiers" — Population (POP) × 0.1 may be converted to militia (does not occupy military cap) |
| Peak | Unlock policy "War Machine" — all military units gain roll Advantage (ADV) in war |

#### Trade Hub

| Stage | Effect |
|------|------|
| Base | Trade income +30%, Economy (ECO)+10 |
| Development | Unlock policy "Free Port" — neutral nations automatically gain a trade agreement |
| Peak | Unlock policy "Financial Hegemony" — may use Gold to influence other nations' diplomatic relations |

#### Magic Realm

| Stage | Effect |
|------|------|
| Base | Research Points (RP)+50%, Technology (TEC)+10 |
| Development | Unlock policy "Arcane Resonance" — magic building cost -30% |
| Peak | Unlock policy "Mana Source" — unlock legendary magic affecting the whole nation |

#### Free City-State

| Stage | Effect |
|------|------|
| Base | Population growth rate +20%, Morale (MOR)+10 |
| Development | Unlock policy "Immigrant Paradise" — attract population inflow from neighbors |
| Peak | Unlock policy "Beacon of Enlightenment" — cultural export influences the global diplomatic landscape |

### 8.2 Policy Unlocks

Whenever National Power (NP) reaches a specific threshold (60 / 180 / 380 / 600), one new policy may be unlocked. The GM Guide contains the complete policy tree.

---

## Chapter Nine: Turn-Based Game Flow

### 9.1 Turn Structure

The game advances in "turns." **Each turn represents one season** (about three months), **four turns = one year**.

Each turn is divided into five phases:

```
Phase 1: Season Declaration (GM)
Phase 2: Player Action Declaration
Phase 3: Action Check & Resolution
Phase 4: Crisis Trigger & Resolution
Phase 5: Turn-End Resolution
```

### 9.2 Phase Details

#### Phase 1: Season Declaration

The GM declares the current season and special effects:

| Quarter | Special Effect |
|------|----------|
| **Spring** | Diplomatic actions gain +1 Modifier; must decide planting plan |
| **Summer** | Construction actions gain Advantage (ADV); military action window |
| **Autumn** | Trade actions gain +2 Modifier; food output settlement |
| **Winter** | Construction actions gain Disadvantage (DIS); food consumption ×1.3; disease risk |

#### Phase 2: Player Action Declaration

Each turn you may execute **3 major actions** (chosen by the player):

| Action Type | Example |
|----------|------|
| Construction action | Build/upgrade buildings |
| Diplomatic action | Send ambassador, trade negotiation, alliance proposal |
| Military action | Recruit army, border patrol, launch war |
| Tech action | Invest in research, unlock tech |
| Internal action | Adjust tax rate, enact policy, soothe morale |
| Hero action | Dispatch a hero on a mission |

#### Phase 3: Action Check & Resolution

The player rolls a check for each action; the GM declares the result and impact.

#### Phase 4: Crisis Trigger & Resolution

The GM draws 1-2 crises (see [Chapter Twelve](#chapter-twelve-crisis-management)); the player responds in real time.

#### Phase 5: Turn-End Resolution

```
1. Gold (GOLD) += Tax (TAX) − building maintenance − troop wages − other expenses
2. Food (FOOD) += food output (Autumn ×2) − food consumption (FOD); if FOOD < 0 → FOOD = 0 and Morale (MOR) −5
3. Research Points (RP) += Technology (TEC) × 0.5 → accumulate toward tech progress (every 50 RP may be spent to unlock one "Tech Breakthrough," see below)
4. Calculate population natural change (formula below)
5. Check era-upgrade conditions
6. Record all data changes
```

**Population natural growth formula:**

```
Base growth rate = 3%
If Morale (MOR) ≥ 60 and Food (FOOD) > 0: growth rate +1% (total 4%)
If Morale (MOR) < 40: growth rate = −1% (population loss)
If Food (FOOD) = 0: extra loss = FLOOR(food deficit ÷ 2)
Race modifier: Goliath × 0.5, Halfling × 1.2; the "Free City-State" ideal's "population growth +20%" is × 1.2 (multiplied onto the growth rate, not +20 percentage points).
Population change = Population (POP) × growth rate × race modifier (Goliath ×0.5, Halfling ×1.2)
Population (POP) = MIN(Population (POP) + population change, Population Cap (CAP))
```

**Tech Breakthrough (the spending outlet for Research Points (RP))**: Every time 50 Research Points (RP) accumulate, you may spend those 50 RP to unlock one "Tech Breakthrough" — choose one: ① permanently Technology (TEC) +2; ② unlock a specialization bonus (e.g., agriculture +10% food output, military +2, or unlock a type of magic). Must be performed at the location of the corresponding tech building (Workshop / Library / University).

### 9.3 Annual Flow Example

```
Year 1 Spring: Decide to plant wheat → build Farmland (success) → send envoy to neighbor (success)
    Crisis: Beast threat → dispatch hunter to drive off (success)
    Resolution: Gold +15, Food +50, Research Points (RP)+2

Year 1 Summer: Build Well (success) → recruit militia (success) → sign trade agreement with neighbor (success)
    Crisis: None
    Resolution: Gold +20, Food +40, Population (POP)+5

Year 1 Autumn: Harvest settlement → expand Farmland (success) → hold harvest festival (success)
    Crisis: Autumn-rain flood (partial success)
    Resolution: Gold +25, Food +80, Morale (MOR)+3

Year 1 Winter: Research basic forging (success) → indoor remodeling (failure) → enact winter ration decree (success)
    Crisis: Cold wave arrives (handled successfully)
    Resolution: Gold +10, food consumption ×1.3, Technology (TEC)+2
```

---

## Chapter Ten: Diplomacy & Conflict

### 10.1 Neighbor Relationship Levels

| Level | Value Range | Effect |
|------|----------|------|
| Hostile (HOS) | -100 ~ -51 | May declare war, embargo, conduct espionage |
| Cold (CLD) | -50 ~ -11 | Border closure, trade restrictions |
| Neutral (NTR) | -10 ~ +10 | Basic trade open, envoys may enter |
| Friendly (FRD) | +11 ~ +50 | Trade preferences, cultural exchange, possible defense alliance |
| Allied (ALL) | +51 ~ +100 | Military alliance, free trade, tech sharing |

### 10.2 Diplomatic Actions

| Action | Cost | Effect |
|------|------|------|
| Send Ambassador | 1 turn + 50 Gold | Establish formal diplomatic relations |
| Trade Negotiation | 1 turn, Check: Economy (ECO) | Sign a trade agreement |
| Alliance Proposal | 1 turn, requires relationship > 30 | Establish a military or defense alliance |
| Marriage Alliance | Triggered by special event | Relationship +30, with family obligations attached |
| Declare War | — | Relationship drops to Hostile, enters war state |
| Sue for Peace | Gold + resources | End the war; terms depend on the situation |
| Send Gift | 100 Gold | Relationship +5 ~ +15 (by check result) |

### 10.3 War System (Overview)

(Complete war rules in the GM Guide.)

Once in a state of war, each turn you may:
- **Mobilize army:** Deploy troops to the front line
- **Launch campaign:** Use Military (MIL) for opposed rolls
- **Siege:** Attack enemy defensive works
- **Retreat:** Preserve strength

War cost: each turn war consumes Gold (wages, supplies); prolonged war drags down the economy.

---

## Chapter Eleven: Hero Units

### 11.1 What Is a Hero?

A hero is an individual with special abilities who can perform special missions for your nation. Each hero has independent attributes, loyalty, and personal goals.

### 11.2 Hero Types

| Type | Main Attribute | Core Function |
|------|----------|----------|
| **General (GEN)** | Attack (ATK) + Tactics (TAC) | Command armies, provide tactical bonuses |
| **Spy (SPY)** | Stealth (STL) + Cunning (INT) | Infiltrate enemy nations, gather intel or sabotage |
| **Scholar (SCH)** | Cunning (INT) + Knowledge (KNW) | Accelerate research, unlock hidden tech |
| **Envoy (ENV)** | Charisma (CHA) + Eloquence (ELO) | Diplomacy specialist, complete difficult agreements |
| **Legendary Artisan (ART)** | Craft (CRF) + Creativity (CRE) | Build special buildings, reduce construction cost |

### 11.3 Hero Attributes

Heroes use personal attributes independent of national attributes (each 0 – 20):

| Attribute | Abbrev | Use |
|------|------|------|
| Attack (ATK) | ATK | Personal combat, martial intimidation |
| Cunning (INT) | INT | Strategic planning, puzzle solving |
| Charisma (CHA) | CHA | Social persuasion, leadership charm |
| Stealth (STL) | STL | Infiltration, covert action |
| Knowledge (KNW) | KNW | Knowledge checks, magic use |
| Tactics (TAC) | TAC | Command in battle, military planning |
| Craft (CRF) | CRF | Building design, item crafting |
| Eloquence (ELO) | ELO | Negotiation debate, diplomatic phrasing |
| Creativity (CRE) | CRE | Invention, artistic activity |

Hero check formula: **1d20 + corresponding hero attribute**

### 11.4 Hero Recruitment

| Recruitment Method | Cost | Difficulty |
|----------|------|------|
| Domestic discovery | 100 Gold | Normal (DC 12) |
| Foreign recruitment | 200 Gold | Hard (DC 18) |
| Event acquisition | Special event | Automatically gained |

### 11.5 Hero Loyalty

Each hero has loyalty (1 – 10). Low loyalty may lead to:
- **Loyalty 1-3:** May defect or leak secrets
- **Loyalty 4-6:** Serves normally, but will not go the extra mile
- **Loyalty 7-9:** Fully committed; missions gain Advantage (ADV)
- **Loyalty 10:** Sworn to the death — may reroll once on failure

Raise loyalty by: granting Gold, fulfilling personal goals, building relevant facilities.

### 11.6 Hero Personal Combat

A hero may leave the army to perform missions alone or fight directly (hero vs hero, hero vs monster).

**Hit Points (HP):** A hero's Hit Points = 20 + Attack (ATK) × 4 + Constitution (CON) × 2 (Constitution is set by the GM from background, 0–10, default 5).

**Combat action economy**: Hero combat is turn-based; each hero may perform **1 major action + 1 move action per turn** (Movement (MOV) = 3 + FLOOR(Attack (ATK) ÷ 5)).

**Hero Defense (DEF):** A hero's base Defense (DEF) = 10, plus armor bonuses (see Chapter Eleven Section Eight and the item catalog). For example, a hero in Leather Armor (+2) has Defense (DEF) = 12.

**Damage calculation:**

```
Hit check: 1d20 + corresponding hero attribute (melee uses Attack (ATK), ranged uses Stealth (STL), spell uses Knowledge (KNW)) ≥ enemy Defense value (DEF)
Melee damage per hit = hero Attack (ATK) + weapon attack bonus + FLOOR(Attack (ATK) ÷ 3)
Ranged damage per hit = hero Stealth (STL) + weapon attack bonus + FLOOR(Stealth (STL) ÷ 3)
(Weapon base damage is based on the hero's corresponding attribute; the weapon's "Attack +N" stacks on top)
```

**Monster vs hero**: Monster hit = 1d20 + monster Attack (ATK) ≥ hero Defense (DEF); on hit, actual damage = monster Attack (ATK) − armor bonus (minimum 1). Armor thus provides both a "dodge chance" and "damage reduction," no longer being merely cosmetic.

**Rest & recovery**: Resting at a safe location (town, camp, temple) recovers **max Hit Points (HP) × 10%** per turn (rounded, at least 1); Mana (MP) recovers 5 that same turn (town / temple 10).

**Death & down**: When Hit Points (HP) drop to 0, the hero is **downed** (loses ability to act, in a dying state). If not aided within 3 turns after being downed, the hero **dies** (permanently lost). Hit Points may be restored with Healing Potions, rest, or spells.

### 11.7 Hero Skills & Spells

Each hero has 2–3 specialization skills by type (see table below), and may learn common skills through missions and training. Casting spells consumes **Mana (MP)** (see Chapter Thirteen).

| Hero Type | Specialization Skills (examples) | Key Attributes |
|----------|----------------|----------|
| General (GEN) | Tactical Command (whole army +2 attack), Charge Order, Hold the Line | Attack (ATK), Tactics (TAC) |
| Spy (SPY) | Stealth Infiltration, Intel Theft, Poison (target -3 attribute/turn, 2–3 turns) | Stealth (STL), Cunning (INT) |
| Scholar (SCH) | Arcane Missile (damage 2d6+Knowledge), Appraise, Quick Research | Knowledge (KNW), Cunning (INT) |
| Envoy (ENV) | Persuade (opposed +3), Treaty, Diplomatic Intel | Charisma (CHA), Eloquence (ELO) |
| Legendary Artisan (ART) | Enchant (equipment +1), Rapid Build (construction -1 turn), Invent | Craft (CRF), Creativity (CRE) |

**Common skills** (learnable by any hero): Scout, First Aid (restore 1d6+2 Hit Points), Ride, Intimidate, Climb.

### 11.8 Hero Equipment

Heroes may wear weapons and armor; effects stack directly onto the hero's attack and defense:

- **Weapon** (e.g., Iron Sword Attack +2): adds to the hero's weapon base damage.
- **Armor** (e.g., Leather Armor Defense +2): adds to the hero's Defense value (DEF).
- **Special equipment** (e.g., Arquebus Attack +8 ranged): takes effect per the item catalog values.

> For the rules on how equipment applies to "national attributes" and "military units," see [Chapter Thirteen: Equipment, Items & Magic Applications](#chapter-thirteen-equipment-items--magic-applications).

### 11.9 Hero Growth & Training

Heroes are not maxed-out at recruitment — through missions and training they keep growing stronger, avoiding devaluation as the nation and monsters grow.

- **Attribute points**: Every **3 hero missions completed** (or **3 hero victory battles** accumulated) grants 1 attribute point, assignable to any hero attribute (single-attribute cap 20).
- **Specialized training**: Spend 50 Gold/turn on training to directly give a chosen hero attribute +1 (at most once per hero per turn); requires staying at a safe location.
- **Legendary deeds**: The "hero attribute +1" reward from the Chapter Twenty-Three "Legendary Deeds" system is folded into this growth mechanism.
- **Skill points**: Every 3 hero missions completed also unlocks 1 new common or specialization skill (see Chapter Eleven Section Seven).

---

## Chapter Twelve: Crisis Management

### 12.1 The Crisis System

At the end of each turn, the GM randomly draws **1-2 crises** from the Crisis Deck. Crisis severity rises with National Power (NP).

### 12.2 The Five Crisis Types

| Type | Example Events | Main Affected Attribute |
|------|----------|-------------|
| **Natural Disaster (NAT)** | Flood, drought, locust plague, plague, earthquake | Resources (RES), Population (POP) |
| **Economic Crisis (ENC)** | Inflation, trade disruption, fiscal deficit, currency devaluation | Economy (ECO), Morale (MOR) |
| **Diplomatic Crisis (DIP)** | Border conflict, neighbor coup, trade sanctions, detained envoy | Military (MIL), Morale (MOR) |
| **Internal Crisis (INT)** | Noble rebellion, religious schism, strike wave, succession dispute | Morale (MOR), Population (POP) |
| **Supernatural Crisis (SUP)** | Monster invasion, magic disaster, planar rift, undead calamity | All attributes |

### 12.3 Crisis Resolution Methods

Each crisis usually has 2-4 resolution methods. The player chooses one and rolls a check:

| Method | Common Attribute | Style |
|----------|----------|------|
| Military Suppression | Military (MIL) | Fast and direct, but may harm morale |
| Negotiated Compromise | Economy (ECO) + Morale (MOR) | Spend resources for a peaceful solution |
| Technical Solution | Technology (TEC) | Use tech or magic for a permanent fix |
| Diplomatic Appeal | Economy (ECO) | Appeal to neighbors for help (may come with conditions) |
| Hero Intervention | Hero attribute | Dispatch a hero (high risk, high reward) |

### 12.4 Crisis Resolution Results

| Check Result | Effect |
|----------|------|
| Critical Success (natural 20) | Crisis perfectly resolved, extra reward gained |
| Success (≥ DC) | Crisis resolved, attributes unaffected |
| Partial Success (within DC - 3) | Crisis lessened, attributes mildly damaged (-2) |
| Failure (< DC - 3) | Crisis deals full damage (-5 ~ -15) |
| Critical Failure (natural 1) | Crisis worsens, may trigger chain events |

---

## Chapter Thirteen: Equipment, Items & Magic Applications

### 13.1 Who Equipment Affects

Equipment in the item catalog is divided into three categories by target:

| Target | How It Applies | Example |
|------|----------|------|
| **Hero** | Weapon adds to hero weapon damage, armor adds to hero Defense value (DEF) | Iron Sword +2 attack, Leather Armor +2 defense |
| **Military unit** | Via buildings like "Smithy," all units of a type gain +1 attack/defense (or per equipment description) | Cavalry Lance: cavalry attack +3 |
| **Nation** | Strategic equipment affects national attributes or war | God-Cannon: siege attack +50 |

### 13.2 The Mana (MP) System

Casting and some hero skills consume **Mana (MP)**.

- **Mana Cap (MP_MAX)** = 10 + Knowledge (KNW) × 2 (Scholar-type heroes usually highest).
- **Per-turn recovery**: Resting one turn recovers 5 Mana; resting in town / temple recovers 10.
- **Cost**: Common spells 2–5 points; powerful spells 6–10 points.
- **Replenish**: "Lesser Mana Potion" restores 10 Mana.

### 13.3 Magic Types & Casting

The five magics (Arcane / Divine / Nature / Rune / Alchemy) each have a corresponding attribute check:

| Magic Type | Casting Check Attribute | Typical Effect |
|----------|--------------|----------|
| Arcane Magic | Knowledge (KNW) | Arcane Missile, Arcane Shield |
| Divine Magic | Charisma (CHA) | Heal, Turn Undead |
| Nature Magic | Knowledge (KNW) | Entangle, Speak with Beasts |
| Rune Magic | Craft (CRF) | Enchant, Warding Rune |
| Alchemy | Craft (CRF) | Explosive, Healing Draught |

Casting: `1d20 + corresponding hero attribute (raw value) ≥ Spell Difficulty (DC)`; on failure, Mana is wasted and there is no effect.

> ▶ **The complete spell list (including Difficulty DC, Mana MP, Cooldown CD, and effects) is collected separately in `assets/魔法圖鑑.md` (with `魔法圖鑑.yaml`)**, categorized by magic type (Arcane / Divine / Nature / Rune / Alchemy / Chrono). Consult it directly before casting.

---

## Appendix

### A. Quick Reference — Check Formula

```
Standard Check:    1d20 + Attribute Modifier (MOD) + other bonuses ≥ Difficulty Class (DC)
Opposed Check:     both sides 1d20 + MOD, higher wins
Hero Check:        1d20 + corresponding hero attribute
Advantage (ADV):    roll 2d20, take higher
Disadvantage (DIS): roll 2d20, take lower
Attribute Modifier: FLOOR((Attribute Value - 10) / 5)
```

### B. Quick Reference — Derived Attribute Formulas

```
National Power (NP)   = Population (POP) × 0.5 + Resources (RES) + Economy (ECO) + Military (MIL)
Tax (TAX)             = Economy (ECO) × Population (POP) × 0.01
Food Consumption (FOD) = Population (POP) × 0.8 (Winter × 1.3)
Research Points (RP)  = Technology (TEC) × 0.5
Population Cap (CAP)  = 10 + Resources (RES) × 5
Military Cap (MCP)    = Population (POP) × 0.1 + Military (MIL) × 0.5
Gold (GOLD)           = starting 150 + each turn (Tax (TAX) − maintenance)
Food (FOOD)           = starting 200 + Σ food output (Autumn ×2) − food consumption (FOD)
Wood/Stone/Iron Ore   = produced by corresponding production buildings; market 1 Gold = 1 material
Population natural growth = Population (POP) × growth rate (3%~4%) × race modifier, capped at Population Cap (CAP)
Hero Hit Points (HP)  = 20 + Attack (ATK) × 4 + Constitution (CON) × 2
```

### C. Quick Reference — Seasonal Effects

| Season | Effect |
|------|------|
| Spring | Diplomacy +1; planting decision |
| Summer | Construction Advantage (ADV); military window |
| Autumn | Trade +2; harvest settlement |
| Winter | Construction Disadvantage (DIS); food ×1.3; disease risk |

### D. Sheet Notes

Use `sheets/空白玩家角色卡.xlsx` to record your nation's data. This sheet already contains all auto-calculation formulas — simply fill in the base values, and derived attributes calculate automatically.

---

> **Next step:** After reading this rulebook, refer to `sheets/範例玩家角色卡.xlsx` for a sample character and begin creating your nation.
> 
> GMs should read `建國模擬TRPG_GM規則書.md` for the complete game-running rules.
