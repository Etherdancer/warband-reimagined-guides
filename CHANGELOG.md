# Warband Reimagined - Changelog

*Every public build, newest first. "New game required" means saves from the previous build will not work: start a new game after updating. Back to the [README](README.md), the [feature list](FEATURES.md) or the [testing guide](TESTING.md).*

## Version 11.2 - fixes for tournaments, merchants, the smith and townsfolk news

**Saves from version 11 keep working.** No new game is needed for this update.

### Fixed

- **Tournament events were fought with no equipment.** Every festival event put the fighters in the arena with empty hands, so the duel, the team knockout and the joust all came out as a fist fight. Each event now has its arms: the duel and the team events the arms you choose, the joust a horse, lance and shield, the archery events a bow and ten arrows. The same fault is fixed in the arena bouts outside the festival (the town champion, sparring, the joust ladder, a lord's challenge, a duel on the road).
- **No lances on foot.** The "spear and shield" arms of the duel and the team knockout gave every fighter a lance, which is a rider's weapon. Those arms are now a quarterstaff and shield. The lance stays where it belongs, in the joust.
- **Crash when speaking with the Master Smith.** Choosing "Speak with the Master Smith" in a town's Market Quarter could close the game. His list of replies was far longer than anyone else's. Commissions are now asked under "I want to commission a piece." and repairs and reforging under "I want work done on my gear."
- **Townsfolk gave a wrong line as news.** Asking "What news do you hear?" could be answered with an unrelated line ("You got keys of dungeon."). The same fault put the wrong text on some messages when you walk into a place. All of these now show the text that was meant.
- **Empty merchants at the start of a game.** A character who begins inside a town, such as the merchant heir, found every merchant with no goods and no money until some time had passed on the map. Merchants in every town are now stocked when a new game starts.

### Changed

- **Quest offers are easier to understand.** 172 offers were rewritten so that each one says who is asking, what is wrong and what they want from you. The stories themselves are unchanged.
- **The joust is scored.** A lance on the rider scores a point, a couched lance unhorses him and wins at once, a blow on a horse counts for nothing. First to three points, or the better score after two minutes. Nobody is wounded.
- **Wrestling is scored.** Blows wear a man down until he goes to the ground, which is a fall. First to three falls, or the better score after a minute and a half.

---

## Version 11.1 - tournament fix

**Saves from version 11 keep working.** No new game is needed for this update.

### Fixed

- **Stuck after winning at a festival.** Winning an event at the Great Tournament in Praven (and any third, fifth, seventh, tenth or fifteenth tournament win) opened a pop-up box over the victory page that could not be closed, so the game was stuck. The news is now written on the victory page itself, and the page can always be left with "Back to the festival". Thanks to the player who reported it.
- The victory page now pays its purse and prize exactly once.

---

## Version 11 "The Free Road" - test build, NOT PLAYED YET

**NEW GAME REQUIRED.** Saves from older versions do not work.

This build has been checked by tools only. Please expect rough edges and report what you find.

Version 10 was about stories. Version 11 is for the rider who wants no story at all: the map is busy, every party on it can be met, and riding the roads is a way to wealth and power of its own.

### New

- **A busy map:** Guild convoys, horse traders, treasure hunters, slavers' coffles, a reliquary procession, errant knights, a champion's retinue, banner-seekers, clan warbands, four named Free Companies, road patrols and the king's silver for every kingdom, and the Wardens' Riders. Later in the game: Sea-Wolves, Black Felt Riders, exiled lords and a Pretender's Host.
- **Every party is met by talk:** trade, escort, duel, learn, hire, ride along or rob. Every attack line tells you what it costs before you do it.
- **Rich by riding:** purses, town bounties, 25 named captains' prizes, tokens for a master smith's masterwork forge, ransom for captains, and a weekly stipend at a hundred parties broken.
- **Strong by riding:** every ten parties broken adds a man to your company's limit. Five new milestones (157 in all).
- **Your own patrols:** raise them from a fief's garrison, give orders, pay wages. They run down small bands and keep raiders away. Ravenhold and your outposts can post one too.
- **The raider road:** notoriety ranks with perks, Raider's Bluff as a haven to build up, black rents from villages, tolls from river crossings, a Lookout, a Slaver, three Reaver Captains with a Black Board of work, six named hunters, and an ending of its own (42 endings in all). It pays more and costs friends.
- **25 road stories** (372 stories in all): hunt a band, guard silver, a convoy or a relic, recover robbed silver, retake a crossing, kings' requests at high renown, and raider work from the Black Board.
- **Roads that change:** war doubles patrols and thins convoys; feast weeks bring pilgrims; a claimant's host may seize a river crossing; clans raid the enemies of their friends.
- **Finds and prices:** convoys and horse traders trade at road prices; a saint's reliquary to return to the Faith or sell; imperial curios for the Diggers.
- **A report on the roads** under Reports, a block for the road on the character sheet, and budget rows for patrols, tolls and rents.
- **Start rules:** how lively the roads are, and whether hostile wanderers ride at all.
- **Optional, off by default:** the Lieutenant's Banner. A companion leads a second party of your men.

### Changed

- The early game stays gentle: raiders appear far away at first and leave a company of fewer than twelve alone unless provoked. Story difficulty never sends hostile wanderers.
- Pilgrims, minstrels, tinkers, settlers, smuggling trains and the other wanderers of earlier versions are now kept by one system, so the map stays tidy in long games.
- Raiders no longer march on your settlement while one of your patrols is near it.
- Selling prisoners at camp pays the full price only when a slavers' coffle is near.

### Fixed

- The weekly budget page (Reports > "Your income and costs, week by week") showed wrong numbers; it now shows the stored figures for each week.
- The bishop offered the same blessing twice.
- Smaller repairs from a full code audit of the mod.

---

## Version 10 "The Stories of Calradia" - test build

**New game required.** Saves from version 8 do not work.

### New

- **Every quest rebuilt:** 347 stories on one new engine. Choices show greyed with the reason, there is always an open path, and each ending changes the world.
- **Great stories rewritten:** the Black Khergit Horde, the Pale Fever, the Emperor's Regalia, Blood and Ashes, the Sea-King's Hoard, the Drowned Crown, the Last Vigil, the Great Heist and more, plus a story in each world crisis.
- **Companions:** a three-act story for each of the 16.
- **Kingdoms and organisations:** two ruler lines for each of the six kingdoms, and a rank ladder for each of the five organisations.
- **Personal stories** for 42 townsfolk and a long story for each culture's village.
- **New lines:** the faith, the family, your rival, Ravenhold, the calendar's great events, crime, war service, trade and your own past.
- **Tournament festival** with a bracket, team knockouts, the joust, wrestling, archery and betting.
- **62 unique reward items** made from Native gear.
- **Character creation in one flow,** and character export and import.
- **Records in one place:** a one-screen character sheet, the Chronicle of Deeds with every story you ended, and lords' notes.
- **Culture voices:** people answer in their culture's voice and remember how your stories ended.
- Each season's great event has a fixed host city.

### Changed

- Menus moved to where Warband players look: Reports, Notes and the Chronicle.
- Options you cannot afford are greyed instead of hidden. Costs are shown.
- World crises are foretold ten days ahead.

### Fixed

- Soldiers enlisted in a lord's host and mercenaries on a Free Company war contract could not join sieges or battles against their employer's enemies; they now take on those enemies while they serve.
- Vassals, mercenaries and marshals who could not join sieges: any kingdom at war with your kingdom is now also an enemy of your side, checked every day. (Reported by a tester; the exact cause is not confirmed, so please tell me if it still happens.)
- Quest endings could overwrite other data once there were more than 300 stories; moved to a larger range.
- The troop trees menu showed "{!}culture 1"; it now names the cultures.


---

## Version 8 "The People of Calradia" - test build

**New game required.** Saves from version 7 are not supported (the game warns you if you load one).

Version 7 filled Calradia with people and systems. Version 8 makes them deeper: the people have work, stories and faces of their own, the places can be walked into, and the systems now talk to each other.

### The people have work and stories

- 43 kinds of townsfolk, villagers and keepers. Thirty-two of them offer work in their own trade: the smith needs goods carried, the sheriff has a bounty, the almoner needs grain for the hungry, the huntsman wants deserters out of his woods. They remember who helped them.
- **45 personal stories**, each three steps long, with endings that change what that person can do for you afterwards. Among them: the Master Smith of Praven's lost anvil, the Horse Dealer of Ichamur's stolen mare, the Notary of Uxkhal's forged deed, the Fallen Champion of Suno's lists, the Huntsman of Slezkh and the wolf, the Wise Woman of Kwynn's barrow dreams, the Beggar King's rival, the traitor at Reyvadin's gate, the weeping relic, the doubting abbot, and nineteen more for tavern folk, guild and harbour people, castle officers and the keepers of inns, camps, crossings, mounds, mines, hunting grounds and monasteries.
- Stories end in **lasting perks**: cheaper disguises, a bigger stake in the cellar ring, Wanted that fades faster, siege warnings, half-price penance, double alms.
- **Standing with each person**: anyone whose jobs you have done three times offers one lasting favour.
- **Every person is their own**: townsfolk, villagers, keepers, mayors, tavern keepers, tournament masters, merchants and village elders all get a name, face and clothes that fit the culture of their town, village or site. The smith of Praven is not the smith of Tihr. They remember whether they have met you.

### Walk-in places

- Walk into the Low Town's lanes, the market, the guild hall, the great church, the drill yard, the castle hall and every village green. These are vanilla scenes where each person stands at the post of their trade: the horse dealer by the stables, the miller at the mill, the notary at his table.
- **The harbour**: the harbour towns have a waterfront to walk, with a timber pier, a moored ship, a warehouse and the harbourmaster's house.
- The mod's map places can be walked into: the inn yard, the clan camp, the toll post at a river crossing, the burial mound, the hunting grounds, the quarry and logging camp, the salt pans and iron workings, the monastery. Their keeper comes to meet you.
- Taverns: the taverner at the counter, the bard by the fire, the fence at a corner table, the old soldier on his bench.
- The old "Speak with" lines stay on a quick-talk page, and walk-in places can be switched off in Options.

### The world notices you

- Companions judge your darker deeds (executing prisoners, sacking, poisoning wells, robbing pilgrims, smuggling, turning on allies), with complaints, or approval from the hard-bitten.
- Lords hear when you help or squeeze the people of their fiefs, and speak of it when you meet.
- The party morale report shows morale of your own making: Voice of Command, camp followers, sworn brothers, a recent feast.
- Townsfolk's news comes from the world as it is: your rival asking after you, a realm sick of war, a riot, a lord who hates his king, the watch's description of you.

### Threads between systems

- Your origin still counts every week. Old friends can gather in the nearest tavern at the start.
- Omens before battle, a pre-battle speech that can stir or fail, spoils to share out, sell or keep.
- A four-week budget by category, and injuries that tell you how long you have left to treat them.
- Low estates send petitioners: sixteen cases from reeve, herald, bishop, guildmasters and stewards.
- The rival captain's bounty grows weekly and can be collected at the Wardens; the fence sells his whereabouts.
- Sieges have eighteen camp events, camp works that keep the matching troubles away, and a taunt that may draw a sally.
- A veteran may step forward from the ranks to be your sergeant; companions have ambitions; a banner bearer steadies the line; feasts can be rich or exotic.
- Enlisting starts you at the rank your name deserves and lends you kit for ninety days. Tournament wins can be dedicated to a spouse or a lady; lords remember refused invitations and may challenge you in the arena.
- The Smugglers' Cove has a keeper and runs cargo to the ports. Kings condemn disloyal lords. An optional companion may turn against you. Smiths refit armour heavier or lighter. Boar and wolves roam near the hunting grounds.

### Realm and person

- The form of the crown after the coronation. Offices of the realm (marshal, treasurer, spymaster, chaplain) and a monthly council.
- Rooms, shops and warehouses to own in towns. Beacons over your fiefs.
- Camp sickness in winter, sieges and hungry camps; the fever ward in plague towns.
- The years tell on you from 45 (a year is 120 days).
- The Hooded Council, a hidden rank inside the Grey Road. A ranking of tournament fighters.
- Ravenhold can keep a physician, a master-at-arms and a falconer, and hides you from the hunt.

### Look

- The title logo was redrawn: solid letters with a clean outline, so it no longer shows a ring of dots on PCs with alpha-to-coverage switched on.

### Fixes from play-testing

- **Menus opened the wrong page.** The build numbered menus differently in two places, so some map pop-ups opened the page next to the one intended: the origin choice at the start opened its result page instead (showing an ending's text), and the Faith's skill gift opened a feast page with garbled text. Fixed at the root, with a new build check so it cannot happen again.
- **People in walk-in places stood at the scene's entry point** instead of their posts (at the harbour, up on the hill out of sight). They now appear at their posts.
- **"Take your place in the line!"** did nothing when your lord went into battle while you were enlisted. It now takes you straight into the battle.
- **The camera was left behind** after a battle screen while enlisted. It now stays with your lord.
- "Send word to your companions" at the start found nobody; it now sends up to three free companions to the nearest tavern.
- The feast-day page no longer shows garbled text on a day with no feast.
- The welcome message now appears right after the start pop-ups instead of a day into the game.
- The voyage menu can no longer trap you; robbers who cannot be paid in coin take goods instead.
- Quests whose steps lead to inns, clan camps, work sites, monasteries and crossings can now be completed.
- Estate changes from petitions and events no longer vanish at the weekly recount.

---

## Version 7 "One World" - first public test build

**New game required.**

- **People and places:** town quarters, 60+ talking NPC roles with memory, villages and castles with their own folk.
- **The Faith:** piety ranks, vows, indulgences, relics, the Holy Muster, monasteries, feast days and the Bells of Ymra arc.
- **Crime and law:** Wanted levels per kingdom, arrest, trial, bail, the chain gang, riots, smuggling, the Wardens' League.
- **Economy II:** smith commissions, parcels of land, a wagon, cattle herds, work sites, hunting grounds, fishing, a weekly budget.
- **War II:** order of battle, stances, mutiny, prisoner treatment, trophies, Free Companies.
- **Map II:** inns, clan camps, river crossings, hidden places, burial mounds, secret passes, sea voyages.
- **Kingdom II:** treasury, policies, laws, estates, royal style, coronation, manors, tiered buildings.
- **Diplomacy II:** treaties, infamy, envoys, dictated peace.
- **Character:** twenty graded traits, dilemmas, prestige and social class, sworn brothers.
- **Quests III:** five new story arcs, twenty new side quests, bounties, Grey Road jobs, steward emergencies.
- **Town life:** lessons, drill, feasts, the cellar ring, jousts, horse races, champions.
- Start-of-game rules, reports, the company gathering at an ending, 41 endings in all.
- Difficulty reworked into five tiers (Story, Gentle, Standard, Hard, Brutal).
- Fixes from a full code audit: scripts that failed silently, "change sides" really switches sides, options that took gold you did not have are hidden until you can pay, a Native typo in the courtship check.

## Version 6

**New game required.**

- 42 more events (kingdom road stories, shore and river encounters, companion banter, family scenes) and 26 more quests (a second quest for every companion, ten radiant town quests).
- World crises from about day 230: the Long Winter, the Succession War, the Comet Year, the Iron Tide.
- Your house: heirs, tutoring, passing the mantle, the Heirloom Blade and legacy points.
- Lords' petitions, sworn friends and grudges; minstrels, tinkers, refugees and envoys on the map; rain, snow and fog in field battles; faction gear from vanilla art.
- Difficulty, debug tools, the Active Affairs journal, the in-game Guide and hints.

## Version 5

**New game required.**

- The statistics screen and the soldier's career (enlisting in a lord's host).
- Fixes from the first code audit.

## Versions 1 to 4

- The foundations: origins, reputation tracks, milestones, endings, story arcs, side quests, events, landmarks, legendary items, new troop lines on vanilla models, battle orders, morale and routing, sieges, seasons, organisations, settlements and the royal court.
