# Blasteroids
Blasteroids is a game where you control a spaceship and defend a planet from falling asteroids. Inspired by classic arcade games such as Space Invaders and Galaga, you move left and right while firing lasers at a never-ending flow of asteroids. Getting a higher score gives you powerups, but it also increasing the difficulty, so look out!


[Play Blasteroids Here!](https://agrudt.github.io/Blasteroids/)
[![image](https://user-images.githubusercontent.com/82253713/121637393-2a379180-ca3e-11eb-98b2-aae75d29d742.png)](https://agrudt.github.io/Blasteroids/)



## Gallery

### Trailer:

[![image](https://user-images.githubusercontent.com/82253713/121637535-5bb05d00-ca3e-11eb-8c25-16314ce18194.png)](https://www.youtube.com/watch?v=ee6V-zWfgCE)

### Welcome to Blasteroids!
![image](https://user-images.githubusercontent.com/82253713/121625119-affc1280-ca27-11eb-8fba-f7a23686600e.png)

### Avoid and Destroy Falling Asteroids
![image](https://user-images.githubusercontent.com/82253713/121624699-d66d7e00-ca26-11eb-9df8-ddd21cb5b23e.png)

### Get powerups every 1000 points
![image](https://user-images.githubusercontent.com/82253713/121624741-ea18e480-ca26-11eb-8b54-86a92246f19f.png)

### But look out, difficulty increases as your score goes up!
![image](https://user-images.githubusercontent.com/82253713/121624778-fb61f100-ca26-11eb-91f9-aea49749f765.png)

### Blast your way to a high score...
![image](https://user-images.githubusercontent.com/82253713/121624844-24828180-ca27-11eb-8536-066cd15d39e6.png)

### Or die trying!
![image](https://user-images.githubusercontent.com/82253713/121624820-19c7ec80-ca27-11eb-9eba-b822a3a61138.png)

### Blasteroids-Available Now!

## Credits

Made by Andrew Grudt, Ryan Anderson, Jerahmy Bindon, and Kranti Paudyal

Assets courtesy of:

Green Laser and Asteroid from KindPNG-https://www.kindpng.com/

Music by Eric Matyas-https://soundimage.org/sci-fi/

SpaceShip by Rozebau-http://pixeljoint.com/pixelart/48537.htm

Planet by deep-fold-https://deep-fold.itch.io/pixel-planet-generator

Space Background by le professeur stagiaire-https://opengameart.org/content/space-star-background

Other Asteroids from Klipartz-https://www.klipartz.com/en

## Playtests

### Alpha Playtest
We learned that we did not set the game to scale to different computers properly. This included setting events to occur based on frames rather than on time, and not anchoring UI aspects to different points of the screen. As a result, the game was inconsistent and much of the feedback related to that. Players were concerned with poor layout and low asteroid spawn rate, although they also requested the ability to mute the game's music.

In response to this, we adjusted the game so that events would happen based on time rather than based on frames. We also anchored UI elements to different parts of the screen so that they would remain in consistent places no matter the size of the screen they are played on.

### Final Playtest
We sent out the game along with a survey to people we knew, along with posting it online. The overall responses were mixed. Many players thought the difficulty was too hard, none was able to acheive a very high final score. 4 people mentioned that they wished that the lasers would move faster, and 6 of 8 survey respondents claimed it was too difficult overall. At least two players failed to get a score of 1000, enough for the first powerup to activate.

As a result of this, we decided ito increase the speed of the lasers from 80 to 110. We lowered the asteroid health from 4 to 3. We believed that this made our game much easier while still being challenging. We also included some minor quality of life improvements, such as removing a bug that allowed players to unpause when they died, making the asteroids rotate as they fell, and having the ship flash red when hit.

## Presentation

https://docs.google.com/presentation/d/1Ito9tLG5qXX76VFMkfw3O0Xz0RM3wKYh19RumESxgUs/edit?usp=sharing

![image](https://user-images.githubusercontent.com/82253713/121635687-864ce680-ca3b-11eb-87db-41bdeab6ef15.png)

![image](https://user-images.githubusercontent.com/82253713/121627179-bd1b0080-ca2b-11eb-9f39-e8770cdb0995.png)

![image](https://user-images.githubusercontent.com/82253713/121627206-c73cff00-ca2b-11eb-90b0-69392dc56bbc.png)

![image](https://user-images.githubusercontent.com/82253713/121627231-d328c100-ca2b-11eb-94c8-0782df32fe13.png)

Link in image (leads to older version): https://srma-uwb.github.io/BlasteroidsWebGL/index.html

## Source Code
 
Available Here: https://github.com/agrudt/Blasteroids-1

Note that the original belongs to Kranti, who dropped the class, so this version is a fork. 

## Space Dragons Dev Log for Blasteroids

Andrew Grudt, Ryan Anderson, Jerahmy Bindon, Kranti Paudyal

Note: Kranti dropped the class later in the quarter.

May 15

We used a build from Hero assignments to start, then modified it since our game was similar. Kranti and Andrew found sprites to use for the Planet, Ship, Background, and Lasers. Andrew implemented sprites and movement for the ship in a locked space and mouse aiming for laser. 

To do: Add falling asteroids, score system.

May 16

Ryan renamed variables and functions containing “Egg” to “Laser” in the scripts. Also added a basic score system to tie to asteroids once they were added. Changed laser travel speed and fire rate. Andrew fixed some bugs related to laser direction and size when spawned. He also added laser firing on mouse click.

To do: Add asteroids and asteroid spawn system. Add player and planet health. 

May 17

Kranti implemented asteroids and an asteroid spawn system and collision with lasers. Andrew added health to the player and asteroids are destroyed when they collide with the player.

To do: Score tied to asteroids, asteroid HP.

May 19

Ryan did some more renaming, changing Egg to Laser and Hero to Ship. He also tied score system to asteroid kills and implemented a basic HP system on asteroids.
To do: Planet health and upgrades.

May 20

Removed Library and Logs folder from GitHub since our gitignore was not working. This solved issues where it would run fine on one member’s PC, but not the others. Andrew added health to the planet and some upgrades to the planet. He used a state machine for the planet for upgrades and hit animation. One state had a huge mass of lasers shoot out to destroy every asteroid on the screen. The other made the planet invincible. These were activated with a key press for testing.

To do: Game over message, upgrades/power ups tied to score.


May 22

Andrew updated the invincible state to be temporary. He also added a game over message when the planet or player dies. Player can restart by pressing R.
To do: Tie upgrades to score. 

May 23

Ryan tied the upgrades to score count. Every 1000 points, you get the laser burst upgrade. He also lowered the spawn rate for asteroids as it was impossibly high.
To do: Find way to use invincible upgrade. Add music.

May 24

Andrew made it so the upgrade alternates between the laser burst and invincible state every 1000 points. He also added background music.
To do (All alpha feedback): Rearrange UI elements. Change spawn rate to use FixedUpdate so it is tied to time. Implement increasing difficulty. Mute music option. Make laser overheat. 

May 26

Andrew anchored different UI elements such as the Game Over message to the center of the screen, so it is not all cramped in the bottom left.

To do: Change spawn rate to time and difficulty. Make laser overheat. 

May 27

Ryan made it so the spawn rate was tied to time using FixcedUpdate and changed spawn rate to compensate for the less frequent update call. He also implemented a difficulty system that increases spawn rates each time score increases by 1000. Andrew made it so the difficulty ceiling was not so high, and made it so after 10000 points, you get the upgrades every 1500 points to reduce the chance of a laser burst chaining points up to the next laser burst. He also added textures to make the asteroids look like they are crumbling when hit with a laser.

To do: Limit max number of asteroids at one time, add option to mute music.

May 29

Andrew limited the max number of asteroids that can spawn at once. He also added the ability to mute the music by pressing M. He also added a UI message saying where the music is from and to press M to mute it.

To do: Make laser overheat, main menu.


May 30

Ryan implemented a laser overheat system so you cannot just hold down the fire key. However, the overheat counter would continue cooling down past zero, meaning you could “save up” cooldown by not firing for a few seconds, allowing you to shoot longer than normally possible.

To do: Meter for player to see overheat, main menu.

May 31

Ryan added a meter in the bottom left to show how close the laser is to overheating. Some bugs were left with how the bar is displayed, and the cooldown bug. Jerahmy added a main menu with the game name and a play button, as well as a pause menu. For some reason, the menu did not work on other member’s computers. Also, the music was buggy with the menu.

To do: Fix overheat and menu bugs.

June 1

Jerahmy fixed the menu button, so it worked for everyone, and the music is now consistent through the menus. Andrew realized we forgot to change the Planet laser and invincibility upgrades to use FixedUpdate, so he changed them.

To do: Fix overheat bar bug, balance invincible time now that it is tied to FixedUpdate.

June 2

Ryan changed the overheat bar to make the red color on top of the background layer, so it is easier to see. He also reduced the invincible planet time since FixedUpdate made the planet invincible several times longer than it was originally. 

To do: Do final playtest and implement feedback changes. 

June 7

Send out playtests for feedback.

June 10

Andrew implemented feedback we got from the playtest: make the laser travel faster, and reduce asteroid hit points. 


## Reflection

In general, game development went somewhat smoothly. The development period was miniscule so we think we should have started development as soon as we had a vague idea of what the game would be. This would have helped us add more features. Our team was good at communicating what we did in terms of development to each other. This dev log and our discord messages are good evidence of communication. If we had more time to work on the game, our highest priority item would be to add our original idea for upgrades. This idea was to collect materials from asteroids that would instantly give you upgrades. The second item would be upgrades for the ship. Right now, the upgrades are more like powerups, and they are only for the planet. The last item we would want to add is different trajectory for the asteroids. Right now, they spawn at the top and fall straight down. We were hoping to have them come in from the sides and follow a curved path down.

