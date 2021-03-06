# my-game
A game I will be working on.

So, my idea for the game is a side-scrolling "ninja" game. It would have a pretty good storyline (I have one in mind) and several levels. The levels would be progressively harder, and you would have to buy upgrades for yourself using coins you earned by defeating enemies in previous levels. If you can't pass a level, you would have to re-play a level to get more coins to upgrade yourself. The "coolness" part of the game that makes it fun to play would probably rely mostly on:

1. **Cool graphics.** To make this a nice game, I can't cut back on graphics, not even for the backgrounds.

2. **Cool power-ups and abilities to buy and unlock.** Something to keep the player playing.

3. **A good story!** You get to find out more of the story only after you beat a level, so its an incentive to beat all the levels.

4. **Running and playing smoothly, no lag or glitches.** This might mean pre-loading images and other things I don't normally do.


A few things to decide on:

1. **How will the story be shown to the player between the levels?** Cutscenes, like in the Lego Batman video games?

2. **How violent is this going to be?** I was thinking that for human enemies, you can only use non-lethal weapons/punches or kicks- just things that stun them. However, you can blow up and destroy the evil robots that come for you.

3. **Finalize storyline.** (Rough storyline below.)

Storyline is currently as follows: (for lack of having a better name I'm just going to use the name Ben)

Ben's father is an inventor who created a time machine. A league of ninjas came and stole it to use it for evil purposes. To get it back, Ben's father makes him take classes from a top-secret (government) place which teaches ninjas for handling crimes that ordinary law enforcement can't. Ben is a loser in school, and gets bullied all the time. After starting to take the ninja lessons, he tries to take on the bullies (that is the first level: Bullies) but the level is extremely hard, so you have to play it several times to get upgrades for yourself before you can beat it. After defeating the bullies and completing his training, he starts his quest to regain the time machine. (The level layout is sort of in a map configuration, the stronghold of the ninjas being the last level. The enemies get increasingly harder as you get closer to the stronghold) After defeating the boss in the final level, Ben finds out that he's really not the boss, but only the 2nd in command, and the boss has captured his father, and is somewhere else. However, Ben has regained the time machine, and the story can be continued in sequel games where he has to rescue his father. (using the time machine too)

The level titles and order:

1. **Tutorial: The Bullies**
2. **Level 1: Robot Guards**
3. **Level 2: Robot Expendables**
4. **Level 3: Shooting Robots**
5. **Level 4: Robot Warriors**
6. **Level 5: Robot Ninjas**
7. **Level 6: Thugs**
8. **Level 7: Marksmen**
9. **Level 8: Warriors**
10. **Level 9: Ninjas!**
11. **Level 10: Stronghold** (Everyone + boss at end)

Levels may include enemies from previous levels, but a new enemy is introduced every level.

Enemies description:

1. **Bullies**
2. **Robot Guards**
3. **Robot Expendables**
4. **Shooting Robots**
5. **Robot Warriors**
6. **Robot Ninjas**
7. **Thugs**
8. **Marksmen**
9. **Warriors**
10. **Ninjas**
11. **Boss**

Hitlist for a bare-bones version:

1. Square that responds to key presses using the player object. (Up arrow, space or w: jump. Down arrow or s: kick. Right arrow or d: punch)
2. Square that moves towards you and can be defeated by kicking or punching (using the enemy object).
3. Small squares for bombs that kill you if you don't jump over them (using the bomb obstacle).

Hitlist for things needed which I can implement:

1. **Menu.** Need cool background, nice buttons, nice level select page(map style), and nice shop page.
2. **Enemies.** Need an object that can hold all the enemies, including their art and abilities (attack, defense, damage) Also need to figure out how to make the levels easy to modify with the difficulty and which enemies come. Array??
3. **Player.** Need an object that holds the player, and "links" to the store so when you buy an abilities upgrade, it upgrades your player. Need art for the player: running, jumping, punching, kicking, and maybe one super-upgrade spinning move.
4. **Background.** Need maybe 3 or 4 different backgrounds for the levels, animated but moving half the speed (or slower) than the player
5. **Obstacles.** Need art for bombs/mines to jump over. Add these to the enemy array?
6. **Story.** Need to figure out how to tell the story between levels.

Hitlist for things which would be nice to have, but not sure I can do them:

1. **Terrain.** A terrain that moves up and down with hills and such, making the players move up and down. Without this, the upper half of the screen is going to be extremely bare because I'm not planning on making anything that flies, so everyone will just be walking/running and fighting at the bottom of the screen.
2. **Weapons.** Weapons for Ben to use; katanas, rocket-launchers, M-16s, grenades, pistols, etc. This would be hard to implement as there would be so many more weapons to have to make, and making the enemies react to them. But, a "golden sword of power" that is extremely expensive but necessary to defeat the boss (and is super over-powered for regular enemies) does sound cool.... That would then be the only weapon.
