Minor fixes and balance changes for Evil Way Home WoG campaign.
All maps:
- Experience, Spells and Secondary Skills are still transferred to the later maps, but Primary Skills are not, as they can be farmed infinitely at the Flea Markets. 
Map 1:
- Fixed a typo in the final_fight script which made the enemies land in the wrong garrison, resulting in no final fight at all.
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
Map 4:
- AI given a daily event in all of their towns (not active for humans): +1000 Gold and +1 of each resource daily from each town. This allows the AI to mostly hire their army and develop their towns. Without it they were way too poor for their recruitment needs. This also lets the player influence the AI's progress by taking their towns, even the first 2 ones.

Minor changes and fixes for In the Wake of Gods WoG campaign:
Map 1:
- Fixed wrong small/large letters used in video and image paths.
- Converted avi animated images to gifs, as those seem better for compatibility with modern systems. If they flicker, try changing HD mod graphics mode settings.
- Customized the friend's name (default Dan like previously).
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
