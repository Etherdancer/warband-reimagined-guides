# Warband Reimagined - Changelog

*Every public build, newest first. "New game required" means saves from the previous build will not work: start a new game after updating. Back to the [README](README.md), the [feature list](FEATURES.md) or the [testing guide](TESTING.md).*

## Version 11.8 - formations, tactics and battle plans

**No new game needed.** Saves from versions 11.6 and 11.7 keep working. If you come from 11.6, this update also brings the 37 rebuilt places of version 11.7.

### New

- **Order pages on F4 to F11.** F1, F2 and F3 stay the old orders. F4 opens the order card, which shows the pages and what each of your groups is doing. F5 to F11 each open a page, and on a page F5 to F11 give the order. The page lies over the battle, which does not stop. Orders go to the groups that are listening (keys 1-9 and 0), like the old ones.
- **Formations your men keep (F5).** Line in ranks, shield wall, wedge, square, loose order and column. Every man has a place and goes back to it, with shields and the best men in front. The same formation again makes it one rank deeper. Hold moves the formation to the flag, Follow keeps it behind you, Charge lets the men go.
- **Formations change the fight.** Men with a shield in a shield wall take half the damage from arrows and bolts and less from blows. Men in loose order are missed by a quarter of the shots from far off. A horse that rides into braced spears is badly hurt.
- **Tactics for the foot (F6).** Advance in order, brace spears, the boar's snout, hold the anvil, skirmish, and throw then charge.
- **Tactics for the shot (F7).** Volleys, hold fire till close, the arrow storm, skirmish, a screen in front of the foot that falls back behind it, and shooting from behind pavises.
- **Tactics for the horse (F8).** The lance wedge, strike and re-form, the feigned flight that draws the enemy after it and turns on him, the riding circle of horse archers, a sweep round the left or right flank into his rear, and a reserve that waits out of the fight until you release it.
- **Battle plans (F9).** One order that takes your whole army through a battle, stage by stage, and tells you each stage as it comes: Three Battles (Swadian), The Ambush Regiment (Vaegir), The Feigned Flight (Khergit), Shield Wall and Snout (Nord), Hedge and Bolt (Rhodok), Attack and Withdraw (Sarranid), and Hammer and Anvil.
- **Each people's own way of war.** Any troops can be given any order, but they do a thing better when it is their own people's way: Nords in the wall and the snout, Rhodoks with braced spears and pavises, Swadian horse with the lance, Khergits in the circle and the flight, Sarranid horse striking and withdrawing, Vaegir archers in the storm.
- **Captains who know them too.** Enemy lords and the lords at your side now fight by the plan of their people when they have the troops for it. Outlaws use the ways of the land they come from; small bands just fight. If you prefer the old battles, switch it off on the F11 page (F11, then F10); the game remembers it.

### How to use it

1. **Choose who listens:** 1-9 for one group (1 infantry, 2 archers, 3 cavalry), or 0 for everybody.
2. **Open a page:** F5 formations, F6 foot, F7 shot, F8 horse, F9 battle plans. It shows at the top left; the battle goes on.
3. **Press the key of the order** on that page. A message says what each group now does, or why it cannot.

- **Try this first:** press 1, then F5 and F6: your infantry forms a shield wall. Press 2, then F7 and F5: your archers shoot in volleys. Or press F9 and the plan of your own troops' people, and watch the army work through it.
- **The old orders still lead:** Hold (F1, F1) moves a formation to your flag, Follow (F1, F2) keeps it behind you, Charge (F1, F3) ends it and lets the men go. To end only a tactic, give a formation (F5).
- **F4 shows the order card** at any time: every page, and what each of your groups is doing.
- The full guide, with what every order does and when to use it, is in the [roadmap](ROADMAP.md), section 11.

### Changed

- **Your powers on one page (F10).** Battle cry, rally, surge, resupply, loose!, your own power and lock shields (boiling oil in a siege) can be given from the F10 page. Their letter keys (B, N, K, L, J, V, H, O) work as before.
- **Signals (F11).** Release the reserve, re-form on me, fall back to the start line, end the battle plan, end every formation and tactic, and the pace of the plans.
- **The guide.** Notes > Game Concepts > "Reimagined: Battle orders and keys" explains how to give an order and lists every key.

### For testers

- Formations, tactics and plans work in **field battles**, not in sieges; the powers work in both.
- This is new: it has been checked by tools, but not yet proven in played battles. Please report what you see: men who stand idle in a formation while they are being hit, a group that does not do what its order says, a page that does not show (the orders still work, and the message log names each one).
- The [testing guide](TESTING.md) has six short test battles.

## Version 11.7 - places rebuilt on real ground

**No new game needed.** Saves from version 11.6 keep working.

### Fixed

- **37 walk-in areas rebuilt.** The 29 map sites you walk into on open ground (6 river crossings, 4 clan camps, 8 burial mounds, 8 hunting grounds, the quarry, the logging camp and Ravenhold) and the open ground of 53 story scenes all shared one bare meadow, where you floated above the ground or sank into it. Each now stands in a real location with solid ground: what you see is what you stand on.
- **The right land.** Every place matches the map around it: 14 areas on grass and in woods, 9 on the steppe, 9 in the snow and 5 in the desert. No more grass in the desert. A burial mound takes the land it was raised on, and a story's ground takes the land where the story is told.
- **Water where it belongs.** The Jelkala Bridge has its river and a wooden bridge. The Praven and Reyvadin fords have shallow water to wade through. The Curaw Ferry stands on the shore of a frozen lake, the Oasis of the Sand Tribes has its pond, and shore stories are told on a beach.
- **Places you can recognise.** The Hall of the Hill Clans is an earth-walled hillfort, the quarry a mine mouth in a rock canyon, the logging camp stands among snowy pines, and Ravenhold is the yard of a whole castle. Elsewhere the place is built from what belongs there: toll bars, tents, nets, graves, ruined walls, a well.
- **People and things on the ground.** Keepers, crowds, props and the spots where a story's fight, chase or search happens are placed on level ground you can walk to, away from cliffs, piers and walls.

### For testers

- **A tour of the places.** Options > Debug tools > Debug tools II has "Tour: walk into the next place." on one of its pages. It walks you into all 37 areas, one after another. Once you have used it in a game, pressing P in any walk-in place marks the spot where you stand in the save's log, so a bug report can say exactly where something is wrong.
- These places have been checked by tools but not yet walked by many players. If you float, sink, or find a place bare, please report it.

## Version 11.6 - stories that fit together

**No new game needed.** Saves from version 11.5.3 keep working. A story you are halfway through may restart its current step.

### Fixed

- **The Low Town and other walk-in places.** People there no longer answer with "Surrender or die"; they talk like townsfolk again.
- **Stories that went nowhere.** Five journeys started at the place they were meant to end (the pardon petition, the soldier's discharge, the Patriarch's summons, the bishop's inspector, the queen's bier); each now begins somewhere else, with a real road to ride.
- **Chases and rides.** The Black Khergit riders and the Khan's baggage train now have a real head start to catch up on, and the ride to Yalen in "Letter by Sea" gives you enough time.
- **What you found is remembered.** Winning a scene or finishing a ride now tells the next page what you found, so it no longer starts from nothing.
- **Money that bought nothing.** In stories where you paid for something that changed nothing later, a good ending now gives experience for the outlay.
- **Borcha, the miners, the Great Heist, the Bells of Saint Ymra.** Borcha's court route has its own ending and a lost argument no longer hangs him; the miners' strike always has a way forward; the Heist's take follows what you chose to carry out; the bell must be taken down before it can be sold or kept.
- **Small texts.** Baheshtur's clan elder is in Peshmi; the king in "The King's Ear" is the ruler of the town's own kingdom.

### Changed

- **Old kindnesses pay off.** Church policy, the inns' league, the road toll, the clans' friendship, the oath-dead, hidden places and your family's favour now leave a small weekly reward.
- **Scenes leave a mark.** When you win a scene (a hold, a catch, a night watch, a storm), the next page now says so under its text ("Done so far: ..."), so the story remembers what you did. It shows only if you really did it.
- **A real arrival.** A new game now starts with you riding into the town through its gate, with guards, relations and the Leave option working as in any visit. The town menu gives news, notices and events their own page, and the rules page is shorter.
- **People stand where you can reach them.** In every walk-in place, people are moved onto ground you can walk to, away from walls, props and each other; the walled inn yard, the abbeys, the salt pans and the iron workings have their own spots.
- **Crowds dress like the place.** Townsfolk, country people and the watch wear the clothes of the town's own culture, with women's dress for women.
- **"Look for somebody who is waiting to be asked."** The page now lists only the people who have something to say to you, and its Back option is always the first line, so it can no longer be pushed off the screen. The entry shows only while somebody is waiting.
- **Quest log.** Two quests of the old game (capture a lord, night bandits) had placeholder lines in the log; they now read as real text.
- **Money and rewards.** A good ending you paid for no longer buys rank, a dishonest loot ending costs honour, back pay is not paid twice, and help you paid for along the way makes a story's later skill checks easier.
- **Stories that could stall.** Clocks on five talks, trial evidence on the lords' road, a fight in the Iron Tide and the Horde's field now always lead somewhere.
- **Battle keys.** The guide's page on keys in battle lists every key the battle uses.
- **Camps.** Clan camps are filled with that clan's own people.

## Version 11.5.3 - companions' gear screen fixed

**No new game needed.** Saves from version 11.5 keep working.

### Fixed

- **The "after the battle" gear screen.** The companions' names now show, clicking one shows their settings, Auto Equip Companions equips them, and "Continue (Browse the loot)" opens the loot that is left.
- **Walk the quarters.** The people waiting to be asked now stand behind one entry, so the Back option is always on screen.
- **Wardens' League prisoners.** The bounty option appears only when you hold outlaw prisoners, and says the League pays for outlaws only.

## Version 11.5.2 - saves fixed

**Saves from version 11.5 keep working.** No new game is needed. Version 11.5.1 shifted some saved values, so a save made with it may show wrong numbers (for example a road duel stake of -1 denars); load a 11.5 save if you have one.

### Fixed

- **Wrong numbers in older saves.** The new screens of 11.5.1 moved other saved values out of place. Everything is back where 11.5 had it, and later versions will keep it that way.

## Version 11.5.1 - companions' gear

**Saves from version 11.5 keep working.** No new game is needed.

### New

- **Companions' auto-equip screen.** After a won battle, before the loot screen, choose a companion and set what goes in each of its four weapon slots (one-handed, two-handed, polearm, any melee, shield, bow, arrows, crossbow, bolts, thrown), whether it takes only blunt weapons, armour, and a horse. "Apply these settings to ALL companions" copies them; "Auto Equip Companions" lets everyone take the best loot, judged by battle stats and not by price (weapons by damage, reach and speed; armour by rating; horses by speed, manoeuvre, health, charge and armour); "Continue (Browse the loot)" goes on to the loot. A companion never takes what they lack the strength, skill or riding for, and gear they put down goes back into the loot.
- **Prisoner limit grows with your party.** It is 20% of your party's size for each point of Prisoner Management (skill 1 is 20%, skill 5 is 100%, skill 10 is 200%).
- **Prisoners eat less.** Each day the company gets back most of the food its prisoners cost, as grain.

### Fixed

- **Troop upgrades.** The Squire of the Lantern and the other new troop lines offered a wrong troop ("multiplayer end") to upgrade to. They now upgrade to the right one.
- **Notes.** The realm notes list at most six lords, which should stop the game closing when Notes is opened.

## Version 11.5 - many fixes

**Saves from version 11.3 and 11.4 keep working.** No new game is needed. (Version 11.4 was never published; its changes are listed below and are part of this version.)

### Fixed

- **Enemy bands are always hostile.** Bounty hunters, assassins, your rival, avengers, toll-post bands, story bands and village raiders no longer turn neutral or friendly when you are notorious or your road record is clean. A story fight against a band is always a fight.
- **The fences no longer pay absurd sums.** A quiver of arrows or a sack of spice used to sell for a thousand denars or more. Stacks pay their real value, and your story rewards, tokens and relics are never bought.
- **The coronation page can be left,** and each choice pays once.
- **War stories fit enlistment.** They are offered only while you serve in a host, and their discharge endings really discharge you.
- **Story people can be found.** A reeve, miller or abbot a story names at a town can be looked for from that town's quarters menu. The Iron Door and the Emperor's Hunting Hall are on the map once their story is accepted; three old barrows stay on the map for the mound stories.
- **Councils cannot stand still for ever** when a king's realm has fallen or a shady member will not meet you. A lost roll in the renegade, bandit-leader and sheriff stories brings you back to the page that offers the fight, instead of paying for a battle you never fought.
- **Road stories name the right towns,** and the marshal's calls come only where the marshal's town is your realm's.
- **The game no longer hangs late in a long campaign** when all four world crises are over.
- Timed services at map sites no longer reset when you visit another town. Taverns count as indoor rooms for story scenes. Escort raiders no longer share slots with your patrols. Hunting-ground guards must be beaten before you claim their prize; a razed clan camp returns; the mound oath names the right realm; a lord's lent soldiers return after a sally; the beacon no longer lights against its own watch; deer herds stay near their hunting ground; the rival's bounty grows; dilemmas come again; road captain 17 can be sold.

### Changed

- **Repeatable gifts now have a cooldown:** landmark gifts and rests, lessons, drill and sparring, feasts, jousts and cellar-ring runs, monastery plunder and donations, horse theft, village drills, the rented room, parley with besiegers, tribute threats and the Pale Fever work (one task a day). Tools, food and cattle cannot be bought cheap and sold dear any more.
- **The 42 career "endings" are now called Legacies**, because the game goes on after one (a story still has endings). Menus, guide pages, the Chronicle and these guides use the new word; the points that heirs inherit are still "legacy points".
- Promote-all only promotes what your purse covers. An overdue bank loan is collected from your deposit and purse. A king's own war is not ended by war weariness. Spawned people stand calm instead of with raised fists.

### Not in this version

- **This build has not been played yet.** Please report problems.
- Still to come: stories that remember what you did in a scene (so a page does not repeat or contradict it), and scene layouts measured from the scene files (tents on slopes, crowds in the clan's own dress).

---

## Version 11.4 - many fixes

**Saves from version 11.3 keep working.** No new game is needed.

### Fixed

- **Enlisting in a lord's host, or taking a Free Companies war contract, no longer ends in war with the Sarranid Sultanate.**
- **Battles you join are credited to the right side.** Helping a caravan or pilgrims against bandits no longer counts as robbing them, and beating the attacking band now pays its purse and counts for your stories.
- **Story scenes inside buildings can be done.** Chests, runners and enemies are placed inside the room; a freed prisoner is no longer cut down by his guards; the false "He is gone" in the first second is gone; three scenes that ran in the wrong town now run at the right place.
- **Two stories reach their endings:** the Free Companies' sergeants' quarrel (and the Captain's Brigandine) and the Deserter Captain. Fourteen more stories gained endings and clues that nothing used to reach.
- **Several stories at one town take turns** on the town menu line, instead of the first hiding the rest.
- **The level-13 battle trait and other pop-up pages are no longer lost** when two fall due at once.
- **A full pack no longer loses a reward:** the item goes to your inn chest and a message says so.
- **The trade ledger shows true prices.** Festival bets pay what the page says on every difficulty. The dice table is even for both sides.

### Changed

- **Road escorts are earned.** Guarding a Guild convoy, the king's silver or an envoy now brings raiders on the road, and the fee, trust and standing are paid when you beat them.
- **Rides and their riders:** the bands that wait on a ride grow with you and vary from story to story.
- **Services belong to a town:** a lesson from the smith in one town no longer delays the smith in another.
- **A lord who dies ends the stories that wait on him** instead of leaving them stuck.
- The "Companions only" order fades only your own soldiers. More roaming parties can be on the roads at once.

### Not in this version

- **This build has not been played yet.** Please report problems.

---

## Version 11.3 - every story has something to do

**Saves from version 11.2 keep working.** No new game is needed. A story you have already begun may open on its new first step.

### New

- **Every one of the 372 stories now has something to do, not only something to read.** On every way to a good ending you must, at least once, do a thing with your hands and your horse: catch a runner through a market or a yard, follow a man without being seen, carry a chest out past guards, hold a gate, a lane or a barn door against a crowd, keep a watch through the night, free a prisoner from a cell, fight a duel in the arena, fight a band on the road, or bring a wagon, a herd or a pilgrim safely through. Choosing a clever option can still help, but it no longer replaces the deed.
- **Journeys.** Many stories now send you out of town: a timed ride to a place, with riders waiting for you on the way, or a short trip to the village where a witness, a boat, a field or a mason is. The hunts and fights of the bounty, renegade and sheriff jobs happen in the hills instead of in the town.
- **Scenes at the places of the map.** A scene can now take place in an inn yard, a clan camp, a toll post, a hunting ground, a quarry, a mine, an abbey or on open ground at a landmark or a village, not only in the town's quarters.
- **Night watches.** The watch scenes can be done only after dark; by day the option is greyed and says so.
- **Companions' fights are yours.** Where you used to watch or coach a companion in a fight (five stories), you now fight in the arena in their name.

### Changed

- **Failed rolls are remembered one by one.** Before, two different skill checks in one story could share a memory slot, so failing one could grey out the other.

### Not in this version

- Shooting and racing scenes, and a companion who fights beside you in the arena. Wolves and boar are still met in conversation, not fought.
- Two stories (the sword in the burial mound, and the vigil of the oath-dead) stay in one place: burial mounds are raised during play and have no fixed spot on the map.
- **This build has not been played yet.** The new scenes and rides are checked by tools only. If a scene does not start, a runner stands still or a ride never ends, please report it with the story's name.

---

## Version 11.2 - fixes for tournaments, merchants, the smith and townsfolk news

**Saves from version 11 keep working.** No new game is needed for this update.

### Fixed

- **Tournament events were fought with no equipment.** Every festival event put the fighters in the arena with empty hands, so the duel, the team knockout and the joust all came out as a fist fight. Each event now has its arms: the duel and the team events the arms you choose, the joust a horse, lance and shield, the archery events a bow and ten arrows. The same fault is fixed in the arena bouts outside the festival (the town champion, sparring, the joust ladder, a lord's challenge, a duel on the road).
- **Stuck at the festival after three wins.** Reaching thirty points at one festival (three events won) made you Champion of the Games, and the news came in a pop-up box that could not be seen or closed: the festival page stopped answering, and "Leave the festival grounds" did nothing. The news is now written on the festival page itself. Results are also counted exactly once now; before, a win could be counted again when its page was reopened.
- **Sites in the wrong place on the map.** Landmarks, inns, camps and other sites were put at a random spot near their town, so one could stand in a river, a bridge in a dry valley and the Hall of the Hill Clans on a river bank. Every site now has a fixed place checked against the map: dry land for all, high ground for the hill sites, the coast or a river bank for those by the water, and the Veluca Bridge at the end of a real bridge. A game already in progress moves its sites to the new places within a day.
- **"Crossroads Gallows" renamed.** Calradia's map has no roads, so the landmark is now Gallows Hill, and it stands on a hill.
- **Wrestling could not be won.** A fist did no damage through the padded tunic, so neither man ever went down and the bout never ended. Every blow that lands now counts: three blows are a fall, three falls win.
- **Stuck in a contest.** In the joust and in wrestling the Tab key now yields the contest (a loss) instead of doing nothing.
- **Archery targets half in the ground.** The targets of the archery and horse archery contests now stand at chest height.
- **No lances on foot.** The "spear and shield" arms of the duel and the team knockout gave every fighter a lance, which is a rider's weapon. Those arms are now a quarterstaff and shield. The lance stays where it belongs, in the joust.
- **Crash when speaking with the Master Smith.** Choosing "Speak with the Master Smith" in a town's Market Quarter could close the game. His list of replies was far longer than anyone else's. Commissions are now asked under "I want to commission a piece." and repairs and reforging under "I want work done on my gear."
- **Townsfolk gave a wrong line as news.** Asking "What news do you hear?" could be answered with an unrelated line ("You got keys of dungeon."). The same fault put the wrong text on some messages when you walk into a place. All of these now show the text that was meant.
- **Empty merchants at the start of a game.** A character who begins inside a town, such as the merchant heir, found every merchant with no goods and no money until some time had passed on the map. Merchants in every town are now stocked when a new game starts.
- **"Attack the camp" did nothing.** At the clan camps the fight never started and you were left on the map. It starts at once now, and so do the fights that stories, landmarks, river crossings and work sites announce.
- **People standing inside the tent** at the walk-in clan camps (and inside the cart at the quarry): the tents and carts are moved clear of them.

### New

- **A page for reporting bugs:** [warband-reimagined-bugs.pages.dev](https://warband-reimagined-bugs.pages.dev/). Say in a sentence what went wrong; a screenshot and your save file are optional, and the page shows the folder your saves are in. Nothing is ever sent by the game or the mod: only what you choose to send yourself.
- **A debug log for bug reports, kept in your save.** The mod keeps a trail of what happened in your game (pages, choices, dialogue, missions) inside the save file, so a save sent with a report shows exactly what led to a fault. Nothing has to be switched on and nothing leaves your computer unless you send the save. (The earlier Edit Mode log is gone: it did not work on Linux.) The Game Concepts page "The debug log" explains it.
- **Single combat is fought, not rolled.** Where a story has you meet a champion, fight a duel or stand a trial by combat, you now fight it yourself in the nearest arena with the arena's arms (twenty stories, and the pit of the Old Imperial Arena). The option says so: "You fight this yourself."
- **Trouble at the inn is played.** Ask an innkeeper whether there is trouble: robbers, stable thieves by night or drunken carters now come out into the inn yard, and you deal with them in person.

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
- **The raider road:** notoriety ranks with perks, Raider's Bluff as a haven to build up, black rents from villages, tolls from river crossings, a Lookout, a Slaver, three Reaver Captains with a Black Board of work, six named hunters, and a Legacy of its own (42 Legacies in all). It pays more and costs friends.
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
- Smaller repairs across the mod.

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
- Start-of-game rules, reports, the company gathering at a Legacy, 41 Legacies in all.
- Difficulty reworked into five tiers (Story, Gentle, Standard, Hard, Brutal).
- Fixes: scripts that failed silently, "change sides" really switches sides, options that took gold you did not have are hidden until you can pay, a Native typo in the courtship check.

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
- Fixes and repairs.

## Versions 1 to 4

- The foundations: origins, reputation tracks, milestones, Legacies, story arcs, side quests, events, landmarks, legendary items, new troop lines on vanilla models, battle orders, morale and routing, sieges, seasons, organisations, settlements and the royal court.
