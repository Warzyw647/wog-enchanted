Minor fixes and balance changes for Evil Way Home WoG campaign.
All maps:
- Experience, Spells and Secondary Skills are still transferred to the later maps, but Primary Skills are not, as they can be farmed infinitely at the Flea Markets. 
Map 1:
- Fixed a typo in the final_fight script which made the enemies land in the wrong garrison, resulting in no final fight at all.
- Changed ground under first garrison to Rough, in case of AI acting more logically in some game versions and shooting the one stack with Antimagic.
- Set starting hero's Experience to 0.
Map 2:
- Fixed Grand Elf army behind the Green Border Gate trying to increase weekly if they were defeated and a hero was standing in their place. This could lead to game crash.
- Renamed central Inferno to "Not Hell Hole" as this is the one where the player actually has to build the Grail while the opening mission text claims the Grail has to be installed in Hell Hole.
- Added a locked, menacingly looking Blue hero near the Unfightable Devils and allowed him to live forever. This forces the player to complete the main quest and build the Grail instead of just defeating all the opponents.
- Fixed the Lonesome Vampire not actually giving hints.
- Skeleton near the South-East underground Dungeon town moved 1 tile to not block the path. That path was probably not intended to be blocked as it interferes with the main quest line.
- Quest hut in the Southern part of the Rampart zone requires 1000 Supreme Archangels instead of 1 Archangel. 1 Archangel could easily be produced with the help of the Transformation Altar, skipping a large part of the main quest line.
- Griffin Conservatories behind the Unfightable Devil swapped with Mercenary Guild and Hill Fort, as those are more useful for the Angel Wings quest.
- AI not allowed to trigger Waiting Deads' messages.
- Waiting Dead near the Crust Cave fixed, script messages were triggered from a nearby rock instead. 
Map 3:
- Wandering Water Elementals fixed to trigger only once, allowed to wander only on water (where they start) instead of only on land (default behaviour) and they don't use a timer to trigger now.
- Timer in the Artificer script changed from TM16 to TM12 in order to not interfere with the Flea Market script.
- Living Skull can be revisited weekly instead of daily. This fits the object texts better and makes more sense balance-wise.
- Gold actually taken from the player if he or she decides to upgrade the Zombies at the Living Skull.
- Fixed typo "If" instead of "IF" in the Windmill script.
- Fixed 1 wrong answer in the Obelisk Quiz. Now the actual correct answers to the Obelisk questions are accepted.
- Moved a few Trees, a Mountain and a Rock a bit near the area with Angels guarding Gold Mines and Lion Shield. This allows for (a bit hidden) path into that area. No path into that area was most likely an error, as Angel Wings, Flight and Dimension Door are not available on this map. 
- Fixed Artificer, now works once per day even if the player has less gold than doubled upgrade price.
- Replaced hero portrait change in Mask Shop with showing crude mask pictures once when buying them. Because portrait change corrupts game saves and I did not find a workaround like for map 1 of Samaritan and WoG. Does not influence interactions with other objects, because those are done with hero w variables.  
Map 4:
- AI given a daily event in all of their towns (not active for humans): +1000 Gold and +1 of each resource daily from each town. This allows the AI to mostly hire their army and develop their towns. Without it they were way too poor for their recruitment needs. This also lets the player influence the AI's progress by taking their towns, even the first 2 ones.

Minor changes and fixes for In the Wake of Gods WoG campaign:
Map 1:
- Set starting hero's Experience to 0 and level to 0 (level 1 given behind castle walls, upon visiting its inner garrison, next to the +1 stats, or in map 2 if castle not visited).
- Secondary skills available: Learning, Archery, Estates, Scholar (can get one of those at level-up from level 0 to level 1).
- Fixed wrong small/large letters used in video and image paths.
- Converted avi animated images to gifs, as those seem better for compatibility with modern systems. If they flicker, try changing HD mod graphics mode settings.
- Customised the friend's name.
- Replaced 'Dan' in static messages with 'your friend'. Also changed Peasant creature name to the friend's name, visible in whining texts. 
- Slightly changed texts to eliminate 'him' when referring to the friend as the player may have picked a female friend's name.
- Ratibor's text about Pitchfork fighting slightly shortened as it didn't fit the hint text field. 
- When the friend goes back to the field, his or her home is labelled 'Home of Dan and family' (or the friend name selected by the player instead of Dan).
- Changed default names to MrTwardowski/MsTwardowska (based on selected portrait) and Mefistofeles. From Polish legends. Changed "bible" from Kirr's cottage to "ERM manual".
- Fix wrong spell displayed when Air Magic is selected (Haste was displayed while Disrupting Ray is given). Also fixed a typo there (was "choise" instead of "choice").
Map 2:
- Replaced some of multiple consecutive exclamation marks in hero Ufretin's text with 'One', 'ONE' and 'ELEVEN' to avoid error message about trying to interpret those as code.
- Banned Air, Earth, Water and Fire Magic skills to make the magic choice from map 1 matter more.
- Changed skills offered at map start to Intelligence/Tactics/Ballistics and banned those from level-ups, like in map 3. To make them more unique and slightly increase the chances of getting Archery at level-ups.
Map 3:
- Banned Spellbinder's Hat and Magic Tomes (were available via Magic Wand) as they allowed the heroes to get the banned spells and meet after crossing the one-way portals.
- Gave Gorynych 10 times more damage and Mind Immunity (with a MA:X flag, not with EA:B) for the final battle. Banned Black Orb Artifact to not trivialise the final battle too much by Blind-locking the Gorynych.
- Companions also visit the free +1 power-ups and Learning Stones when one of them visits such an object. No need to run with everyone to every corner of the map for +1 stats.
- Gave Orange and Purple their level 8 troops if they fail to recruit. Not giving Orange extra stats, don't want to risk making them much stronger than the next targets - the Inferno heroes.
- Fixed main hero's starting troops. Was HE:C0/1/-1/1 instead of HE:C0/1/-1/0.

Minor changes and fixes for A life of A-D-V-E-N-T-U-R-E WoG campaign:
Map 1 (the only one):
- Set starting hero's Experience to 0.
- Archer upgrade script next to Light Blue Tent takes gold only once. Also takes away 1 morale until next battle if the hero had less than 1000 gold when agreeing to the deal, for taking advantage of the archery instructor.
- Message at Dwarf Ellam's house fixed. He no longer "walks into his house" if he's not in the army or if he got upgraded.
- Luamesoum can be fought only once. If player did not help him but completed the quest, message about Xeja giving gold no longer repeats, message about seeing some knights train is displayed instead. No reaction at training field entrance if Luamesoum helped and Cavaliers already killed before getting the quest for them, because it's the same state as when Cavaliers are killed and then the training field has been visited.
- Necromancer Aria given mana for 1 Meteor Shower. Seems fine story-wise, I think.
- When exiting the Crypt, added a check if the "visited object" is a Subterranean Gate or a Hero. Proceed only if it's a Gate. Crypt exit script triggers only for human player and disabled the Gate for Purple player at map start. Just in case.
- Strange Monastery, if player refuses to enter, exit script without processing rewards. Player can come back and visit the Monastery later. Added check to "provoke battle" and "disable/enable Tactics" script lines. Execute only if quest not completed yet. Disable/enable Tactics only if the hero has that skill.
- Enabled creature experience, enemies get 1 level every (6-difficulty) weeks (first increase in week 2/3/4/5/6 at difficulty 200/160/130/100/80%), player gets creature xp from battles. Set Commanders as disabled, disabled leaving troops and Artifacts on the map. Set hero's starting experience to 0.
- Mad Monk gets 1 War Zealot plus 1 Hierofant in battle, called Fnord and Gaidal Cain respectively. At start of each battle round (except Tactics round) cast Berserk on everyone on both sides of the battlefield with IF:L message "The madness of Fnord and Gaidal Cain affects you all.". Gave Mad Monk correct colour.
- Increased Tactics from Advanced to Expert temporarily for the time of Monk encounters (If player has Advanced Tactics). This is to allow deploying a stack closer to the opponents than to allies and run towards them when Berserked. If hero has Expert Leadership, give temporary +20 Defence instead, taken away after the Mad Monk encounter is done.
- Monk events disabled in the other exit from the Monk area to the north.
- Library name moved from z19 (used by Wyvern Gate) to z29.
- Added creature experience manually at start of combat (gets updated after combat). Most likely it could not be awarded automatically because of hero level limit. Gave  10*enemy hp experience to each creature. Not taking enemy hp boost from creature experience into account. For example a Pikeman awards 100 xp, no matter if he's trained or not.
- Upgrading Dwarf, Archers and Swordsmen keeps their Creature Experience unchanged.
- Initialised flags 501 (Knights of Ni) and 502 (Water Altar)

Minor fixes for The Samaritan WoG campaign:
Map 1:
- Set starting hero's Experience to 0.
- Fixed wrong capitalisation of some of the variable initialisation script lines. This caused warning messages at map start.
- Made Dima's Mill a working Windmill when it's built. It was named Object.
Map 2:
- Fixed hero name not transferred from map 1.
- Added region label in mission start screen.
- Enabled Power of Gaia script. Was inactive. Replaced random part of the condition with dependency on number of regenerated Crystals. How this works now:
1. Works only if main hero attacks an enemy who has Behemoths (any of the 3 types)
2. Calculate the hero's "Behemoth Diplomacy" level as 12 plus levels of Luck, Leadership and Diplomacy, plus 1 for each type of Behemoth in the hero's army.
Examples:
Basic Luck, no Leadership, no Diplomacy, no Behemoths, no Ancient Behemoths, no Ghost Behemoths in army. This adds up to 13 "Behemoth Diplomacy" (minimum possible, unless you use Market of Time to forget Luck, then you can go down to 12).
Advanced Luck, Advanced Leadership, Basic Diplomacy, Behemoths and Ancient Behemoths in army but no Ghost Behemoths. That's 19 "Behemoth Diplomacy".
Expert Luck, Expert Leadership, Expert Diplomacy, Behemoths, Ancient Behemoths and Ghost Behemoths in army. Result: 24 "Behemoth Diplomacy" (maximum possible).
3. Compare "Behemoth Diplomacy" with number of Crystals left to regenerate. If your hero's "Behemoth Diplomacy" is higher, the effect triggers. If too many Crystals did not get regenerated yet, the effect does not trigger.
4. Now, if the effect triggers (see above), then from each of the enemy Behemoth stacks (all 3 types of Behemoths) 20% (rounded down) will join your hero before the fight.
Originally, "Behemoth Diplomacy" was supposed to be compared with a random number between 1 and 36 and not with the number of Crystals left. But I guess comparing with non-regenerated Crystals makes sense story-wise. If you convince the Behemoths that you can complete the task, then some of them will join you.
Also removed the requirement that the previous battle has to be fought by the human player. Replaced that with a check at start of script that the human player is involved (flag 1000) and that Ivor is the attacker.
- Moved Peasants and Swordsmen next to one Arena and one Library. In their previous location, they invalidated these objects' types set when killed. The object types were set at map start with !#OB:T and !#OB:S. 
- Brown Mushrooms are empty Objects. Only the other 4 colours are coded. Same as in WoG mission 2, but there Purple is unused and Brown gives Earth Magic. Unchanged.
- Fixed Green Town deletion one day after all 4 'special' Obelisks (in the zone without towns) are visited. FU70 was not called. Removed temporary use of v91 in TM13, freed up for other use. 
- Fixed v95 getting used for both letting Green into the neutral zone and checking if the Obelisk behind the Faerie Dragons was visited. Now v91 is used to unblock Green's one-way portals instead.
- Added a loss condition: 150-350 (depending on selected game difficulty) Behemoths dead in all fights on the map.
- Added an alternative win condition: gather 100 Ghost Behemoths. Also applies to AI. Standard win also allowed.
- FU2 took 200 movement from Ivor after jumping off an Obelisk and jumping back on it. Now it also checks if Ivor has at least 200 movement. If he has less, takes all remaining movement, if he has at least 200, takes 200. This removes the possibility of getting negative movement, in case it had any consequences.
Map 3:
- Added region label in mission start screen.
- Built Taverns in AI towns. Without them, it takes them about 1.5 week to build it. Which gives the player a huge advantage due to starting with a hero.
- Replaced VR:T with VR:R in week type randomisation to prevent endless loops. Initialised "previous week type" variable v20 to -1 "none" to allow all week types on week 1.

