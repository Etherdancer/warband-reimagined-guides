# Warband Reimagined - Testing Guide
**Thank you for helping. This mod is big and mostly untested by real players, so every report counts - including "it works fine".**

## Before you start

- Start a **NEW game** (older saves are not supported).
- Pick a difficulty you enjoy. If it is too easy or too hard, that is itself useful feedback.
- You do not need to test everything. Pick a section, play it, and report what you saw.

## How to report a problem
Post in this item's Workshop comments or in the Discussions tab with:

- **What you did** (menu names, who you talked to, the town).
- **The in-game day** and your difficulty.
- **Any red error text** (a screenshot of the message log is ideal).
- For a crash: the file *rgl_log.txt* from your Warband folder, and whether you were in a battle, town, menu or on the map.
- Options > Debug tools > **Diagnostics** shows the save version and the state of every system: paste it if you can.

## Highest priority (most likely to break)
These touch Native's battle and encounter code, so a crash or odd behaviour is most likely here. Please try them and report even if all is well:

- **Sally out** of a besieged fortress (siege menu > Sally out).
- **Poisoning a well:** disguise at an enemy gate, carry the vial, find the well in the town.
- **Cellar brawl** in Low Town (real fist fight in the arena).
- **Change sides** when you come upon a battle (does the battle really put you on the other side?).
- **Start as a king** or as a sworn vassal (start-rules menu), then open the Crown menu.
- **Difficulty:** try Gentle or Story and also Hard. Does Gentle feel really easy? Does Hard feel fair?

## Test plan
### Setup

- Camp > The Chronicle > Options: turn "Debug messages" ON. A "Debug tools" option appears on the same page.
- Debug tools gives: +10000 gold, +200 renown, +20 trust/notoriety/piety, 20 knights, fire an event, start the next quest, summon the Horde / the rival, begin or end a world crisis, a grown heir, a lord's petition, +5 legacy, jump to landmarks, and Diagnostics (save version, day, milestones, quests, endings, every system's state). If something breaks, note: what you clicked, the day, and any red error text (a screenshot of the message log is ideal).

### Smoke test - does every screen open and close cleanly?

- ☐ Day 1: the Welcome pop-up appears once; a "Tip:" line appears every 3 days after that.
- ☐ Camp > The Chronicle hub: header shows season, year, day, standing, milestones (and heir / world crisis when present).
- ☐ Records: Active affairs (+ Commitments, + Finished), Standing, Statistics (scroll the whole screen), Journal, Goals, Chronicle, Realms, Tavern talk, Ledger. Each Back returns to Records.
- ☐ Your house: heir text, legacy points, boons (only with points), officers (only with a fief).
- ☐ Guide: all 12 pages open and return.
- ☐ Options: both pages show On/Off correctly and every toggle flips; Difficulty cycles Story > Gentle > Standard > Hard > Brutal.
- ☐ Town menu: WR options sit together above "Leave". Town affairs > Guilds / Services (the physician is in Services when wounded).

### Gameplay checks

- **Events:** ☐ Debug > fire event ~10 times near different kingdoms' towns: kingdom events match the nearest town.
- ☐ With two companions from a pair (Borcha+Marnid, Rolf+Katrin, Baheshtur+Matheld, Ymira+Deshavi, Firentis+Artimenner, Alayen+Klethi) banter events can appear.
- **Quests:** ☐ Tavern talk lists quests; start one in its town; the Active affairs page shows the next town and distance.
- ☐ A companion's first quest, then its second act ("cq2") appears in Tavern talk while they ride with you.
- ☐ Radiant quests: The Ransom Courier (fight OR pay 300), The Trader's Bargain (credit branch can fail).
- **Crises:** ☐ Debug > Begin a world crisis. Town menu shows "The troubles of the age"; Commitments shows progress. Winter: give 10 grain.  Succession: back a claimant (500), then win battles.  Comet: watch every 4 days. Iron Tide: four "Iron Tide Free Company" parties roam and burn villages; beat them.
- ☐ Debug > End the crisis: result pop-up; with enough progress, reward + possible ending; "crises survived" +1.
- **House:** ☐ Debug > grown heir. Your house > Pass the mantle: confirm screen lists what carries over; afterwards your name changes, gold -20%, renown -10%, you get the Heirloom Blade, +3 legacy, tutoring skills.
- ☐ Permadeath ON + heir: lose a battle and be captured. ~20% chance you die: the heir screen appears, then normal captivity continues. Without an heir: "Fallen in Battle" and the game ends.
- ☐ Debug > petition: every answer works; accept 3 times from one lord -> "sworn friend" message. Loan: repaid with interest after 4 weeks.
- **Living world:** ☐ Minstrels, Tinker's Cart, Travelling Envoy appear from ~day 4; Refugees appear near looted villages. Ride into them: a conversation (not a menu) offers choices; after one choice they only greet you.
- ☐ Field battles: sometimes rain, snow (winter) or fog with a message. Archers are a bit worse; after Rally (N) or Volley (J) ends, archers go back to the weather-reduced aim (not to full).
- **Gear:** ☐ Town merchants sometimes sell Swadian Blue Tabard, Vaegir Crimson Tunic, Nord Raider's Sword, etc.
- **Balance:** ☐ Note how fast gold and renown grow by day 50 / 100 / 200 on Standard. Too fast or too slow? Tell me.


## Test plan, continued
### The newest systems(test these in this order)

- **Start:** ☐ New game: origin menu, then the rules menu (crisis day, Horde day, total war, village). Chronicle hub has at most 10 options.
- **People:** ☐ Enter a town on foot: NPCs stand in quarters; talk to a few; Reports > People you know grows; Ask around lists who is in town.
- **Faith:** ☐ Piety rank popup; Holy Muster; vows need piety 20; feast days; Bells of Ymra arc.
- **Law:** ☐ Steal or rob: Wanted rises; gate check at 2+; bail; chain gang; Wardens' League clerk; Justiciar arc.
- **Economy II:** ☐ Smith commission, parcels, wagon, cattle, work sites, hunting grounds, budget report.
- **War II:** ☐ Order of battle prompt; stances; mutiny at low morale; prisoner menu; level-13 trait (key V); Free Companies captain.
- **Map II:** ☐ Inns, clan camps, crossings, hidden places (rumours), mounds after a lord dies, voyages, secret passes.
- **Kingdom II:** ☐ As king: Crown menu -> treasury, policies, laws, estates, style; coronation once; riots; tier upgrades; manors; lances; spoils options on capture.
- **Diplomacy II:** ☐ Treaties (trade/defensive/alliance) expire and fall; infamy on war without casus belli; envoy after 7 days; dictate peace with war score; realms report.
- **Character:** ☐ Traits report; dilemmas; prestige/class in Standing; castle hall gate for Commoners; old friend event day 20-40.
- **Quests III:** ☐ Five arcs (debug: start next quest), 20 side quests, bounty/leader quests, Grey Road jobs, steward emergencies.
- **Town life:** ☐ Lessons (10000), drill, symbel, songs, cellar ring, joust ladder, horse race, champion challenge.
- **Reports:** ☐ Reports > More reports: every page opens with no data and with data.
- **Finale:** ☐ Ending -> gather the company; final score -> deeds; triumph on castle_taken as king.
- **Debug:** ☐ Options > Debug tools has new V7 pages for triggering events.

### Known limits (by design)

- Warband cannot carry anything between separate saves; legacy works between generations inside one save.
- Kingdom gear is sold in every town (rarely), not only in its own kingdom.
- Weather only in open-field battles (not sieges, towns or ambush interiors).
