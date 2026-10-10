# Warband Reimagined - Testing Guide

Thank you for helping. Play the way you like, and tell me what looked wrong.

## Before you start

- Start a **NEW game**. Old saves do not work.
- Pick any difficulty. Story is fine for testing.
- You do not have to do everything. A short session and a short report already help.
- Save before you try something, so you can go back.

## The quick check

Tick off what you try. Write down anything odd.

1. **Start.** Make a character. Do you reach the map without an error message?
2. **Menus.** Open Camp > The Chronicle. Open Reports (the map bar) and look at the character report and the Chronicle of Deeds. Do the screens open and read well? Are any words odd (like {!} or "culture 1")?
3. **A town.** Enter a town and choose "Walk the quarters". Visit a quarter and speak to someone. Are people standing in sensible places?
4. **A story.** Talk to a tavern keeper or a villager and ask about work or news. Accept a story. Follow it for a few steps. Can you always find something to do next? Are greyed options explained?
5. **Finish a story** (any ending). Did you get the reward it promised? Does it show in the Chronicle of Deeds among your stories?
6. **The roads.** Ride for a few days. Ride up to a party you have not seen before (a convoy, knights, a patrol) and talk to it. Do the options make sense? Then open Reports > The roads. Does the list match what you see on the map?
7. **A fight.** Play one battle (a bandit group is fine). Press F4 (the order card), then F5 and F6 (shield wall): do your men form up? Try B (battle cry) and N (rally).
8. **A lord.** Talk to a lord. Try "What do people say of me?" and "What do you think of your liege?".
9. **A companion** (if you have one). Ask "How do you find the company, and me?".
10. **Time.** Let the game run for two weeks of game days. Do any errors pop up? Does the game pause or stutter on the map?
11. **Speed.** If your PC is old or slow, tell me how the game runs.

## New in version 11.8: battle orders

How to use the order pages (F4 to F11) is in the [player guide](PLAYER_GUIDE.md), section 11. In short: choose who listens (1-9, or 0 for all), press the key of a page, then the key of the order. Field battles only, not sieges.

**Six prepared test battles.** Options > Debug tools > Battle and war > "Test battles for the battle orders." Each lends you the soldiers it needs, puts an enemy beside you and starts the fight; a yellow line in the log says which keys to try. The soldiers stay with you, so use a test save.

1. **A line and the shapes.** F5 F5: do your men form ranks facing the enemy? F1 F1 elsewhere: does the line move there? F5 F6, F5 F7, F5 F8, F5 F11: does each shape look like its name? Do men fight back when reached, or stand idle?
2. **Archers.** Press 2, then F7 F5 (volleys): do they loose together? F7 F8 (skirmish): do they give ground?
3. **Horse.** Press 3, then F8 F6: do they charge, ride back and charge again? F8 F7 (feigned flight): does the enemy follow, and do your riders turn on him? F8 F8: the riding circle.
4. **A plan.** F9, then F5 (Three Battles). Does the army do what each stage message says?
5. **Captains.** A Khergit host, then a Rhodok host. Fight each, then switch the captains' tactics off (F11, F10) and fight it again. Do they behave differently?

If a page does not show, the orders still work; please tell me. Then save the game: the save keeps a record of the orders, so a save sent with your report shows what happened.

## New in version 11: please look at these

- **Trading on the road:** buy and sell with a Guild convoy or the horse traders. Does the trade screen open with the right goods?
- **Attacking a peaceful party:** the attack line names its cost first. If you go ahead, does the fight start, and do you pay the cost it named?
- **Breaking a hostile band** (Sea-Wolves, Black Felt Riders): do you get the purse, and later the town bounty?
- **Your own patrol** (if you own a fief): raise one from the garrison, give it an order, wait a week. Is it still there, and are the wages taken?
- **The raider road:** rob on the roads until your notoriety passes 20, then visit Raider's Bluff. Do the Bluff's menus work?
- **The weekly budget:** after one full week, open Reports > "Your income and costs, week by week". Do the numbers look right?
- **The Lieutenant's Banner** (off by default): switch it on in Camp > The Chronicle > Reimagined options > More options, then raise it from the camp menu with a companion. Does the second party ride with you, and can you recall it?

## If you want to test more

Pick one of these and play it for a while:

- **Origins:** start a new game with a different origin. Does the opening make sense?
- **Tournament:** go to a town with a tournament and join the festival. Enter each event once. Does every fighter have the right arms (a lance and horse in the joust, a bow in archery, bare hands only in the fist fight)? Do the joust and the fist fight count points and end at three?
- **A great story:** ask around for the Emperor's Regalia (a scholar in Zendar), Blood and Ashes (your first week), or the Pale Fever (when the plague starts).
- **The soldier's life (rebuilt in 11.9):** ask a lord to take you into his host. Does the host stay in sight as it marches? Does time run by itself, and does Space halt and start it? Does the H key open your place? Do the horns call you into the line, and does the report after the fight show merit and battle money?
- **Your own settlement or kingdom:** if you get there, tell me what breaks.
- **A long game:** past day 100, is the map still tidy? Options > Debug tools > Roads, patrols and raiders has "Roads: count orphans".
- **The places:** Options > Debug tools > Places and people has "Tour: walk into the next place." It walks you into all 37 rebuilt areas in turn. Does your character stand on what you see, on the right land? Press P on a bad spot to mark it in the save, then Tab for the next.

## How to report a problem

The easiest way is the **[Discord server](https://discord.gg/qqpPMAX46R)**: open a report in **bug-reports** (private: only you and I see it). Say in a sentence what went wrong; a screenshot, your zipped save and your log are optional.

Not on Discord? Use the **[bug report page](https://warband-reimagined-bugs.pages.dev/)**. Nothing is ever sent by the game or the mod: only what you choose to send yourself.

The Workshop **Comments** and **Discussions** work too. It helps to include:

- **What you did** (menu names, who you talked to, the town).
- **The in-game day** and your difficulty.
- **Any red error text** (a screenshot helps).
- For a **crash**: the file *rgl_log.txt* from your Warband folder, and whether you were in a battle, a town, a menu or on the map.
- Options > Debug tools > Pages, the log and diagnostics > **Diagnostics** shows the state of every system: paste it if you can.

Reports of "it works fine" are useful too.

## New in version 11.5: please look at these

- A story fight against a band: you can always "Charge", even when you are notorious or your road record is clean.
- A story that names a person at a town (a reeve, a miller, an abbot): look for the "Look for the ..." line in that town's quarters menu.
- A lesson, a drill, a landmark gift, a plunder: after taking it, the option should say when it will be there again.
- Sally out of a besieged fortress: the lent soldiers go back an hour after the battle.
- A coronation: pick a way to be crowned once; the page should close.
