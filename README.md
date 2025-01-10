# Learning_Journal
My journal for programing

idea for what the tutorials will be connected to:
a similar doom mechanics from the first 2 games
a simple start menu
enemy following the player form the moment they are created
a enemy spawner
player projectiles

Notes, Lists and Refences are all in diferent files.

I decided to save my progress in the tutorial and prototype differerntly. The tutorials are all in packages which can be seen. while the Game prototype is saved in a different repository.

link to the prototype github:

https://github.com/CPW42/UnityProjectJoao/tree/Version2Prototype

If you see that tere are two braches, the one called "Main" one is a outdated version of the prototype the one called "Version"Prototype" is the current version. 

# Dates and Info:

**29/10/2024 and 4/11/2024**

I Started making the first tutorial which was going to be a simple player movement. there were many problems but working on the second day i was able to fix them. these errors include the player not moving correctly after doing the code for the player movement and the camera rotating in a axis it was not supposed to.

**5/11/2024 and 11/11/2024**

I Stared and finished the second tutorial in those two days. I decided to make a enemy spawning system as something new that I had never done before unlike with the previous tutorial. I first followed one tutorial to make the code. there were some minur errors but it worked in the end. But unfortenatly the code was basicly identical to the one from the video so on the second day I worked on the tutorial I looked at other videos and information online to find what I could add. This lead to many issues as using different tutorials into one script doesn't work all of the time. But i was able to get something working which I liked and wasn't a exact copy of the first video.

**12/11/2024 and 18/11/2024**

I decided for my third tutorial I would make a enemy shooting at the player. This was simple to make but still took me two days to get it done. the script I used was similar to one from a video with some changes as the video was to be used for a player and not a enemy. I tried to use something similar to the second tutorial with the IEnumerator but it didn't work. But I then figured out and learned to use something that would repeat the function which had most of the script.

**19/11/2024 and 25/11/2024**

For the last tutorial I decided to make two mechanincs similar to the ones from the Mega Man franchise. These were Rush coil and Rush Jet. The jump one was easy to make and learn by looking into code on the unity manual. However the hover one was the hardest to get done which is why it took me two days to get it finished. But in the end I was able to figure out something which worked.

**26/11/2024**

Since I was finished making the mechanics for each tutorial I decided to start working on the prototype. I first had to figure out what I was going to make. I then realised I could do a 3D first person platformer since that means I could use all the code I made for the tutorial in the prototype. So I first added every code to the prototype but instead of copying and pasting I wrote them so not to keep any thing that I didn't need.

**3/12/2024**

I Started testing every since mechanic I added last time to make sure everything was working correctly. Once I checked all the mechanics I started planning what I would need to add for the prototype. The first thing on the list I started to make was an enemy which would follow the player the moment they were created. I first tried to make it without using a NavAgent but realised I would need it. I also made a health system for the player and had so it would be showned on the top left of the screen. It had so if a projectile or a enemy collided with me my health would decrease by one.

**10/12/2024**

I finished the enemy following the player code have tested to see if it worked correctly. I then started to make a enemy health system which would let the player kill them by shooting projectiles similart to how some enemies do.

**17/12/2024**

I fixed some things and started to add a limit system that would limit how many support mechanics i could create. I also started to add so when the player killed a enemy the amout you increase by one maxing a five.

**20/12/2024**

I didn't do a lot compared to other days but I did create a specific spawning system and a gate mechanic which one will let me create any of the two enemies in two locations and make the enemy spawner, while the other is to be used to block the player form progressing until all enemies have spawned. In addition, I also added two text objects in the UI showing the amount of each item the player has.

**6/1/2025 to 10/1/2025**

On the first two days i finished the prototype. I fixed all the errors and issues that each code was having each time I tested the level. I made sure that everything was working as intended and nothing would break. One of those fixes was changing many of the code to where it correctly checked for the player or other things as the code worked if the objects were on the levels but not as prefabs. I tested the game before recording for the video even adding a beggining and ending scene to show the controls and to know when to stop recording.

# Errors while making the Tutorials:

1. This two small issues but while making the first tutorial I notice that the player was not woving correctly and that the camera would rotate too much in a way I didn't want.

Fix: For the first issue I didn't realise that instead of having it one part of the code say right it should have been saying forward. While for the second issue it was mostly due to the fact I was trying to make the camera rotate in two axis but I remembered that in Doom the player can't look up, so I removed that piece of code and it fixed the camera.

2.On my second tutorial code there was no error or issue but I realised that the code was basiclly identical to one from the tutorial I first watched to learn how to make the mechaninc.

Fix: The solution was to look at other tutorials see how they did it and try to mix some parts to my script so its not copy and paste from the original video.

 3.While testing the code For the second tutorial the limit counter was not reseting. The int value should have reverted back to zero but which would then let the enemies spawn again. but instead it didn't reset which by  default the code would stop when the limit counter was equal or more to another in variable.

 Fix: To fix this error in the code I moved the if statement and line of code from the update function to the function which has most of the code.

 4.When I was testing the mechanics for the supports I notice that when the player would collide with the hover object to switch the player to different movement controls, nothing was happening and it game me an error.

 Fix: The reason it wasn't working was because the code was working if the hover object was already on the scene and not a prefab. So to fix this issue I changed the script so it looked for the hidden game object with a specific name which was parented to the player and would then connect to the other script fixing the issue.

5.While trying to make the script for the third tutorial

# Errors while making the Prototype:

1.The player attack was giving an error even if it was working fine.

Fix: Altered the code so it gets the enemies health script when colliding instead of when is created/awakened.

2.There were errors with the walking enemy script causing it to not moving towards the player when created and not interacting with the support script.

Fix: I made so it looks for the player object by the tag it has, and did a similar thing to the enemy script.


3. When I was testing the level I noticed I was getting error messages each time the players projectile collided with the ground or was created.

Fix: I realised that each time it was created the projectile code would always look for the enemy health script even if there was no enemies. So to fix this i seperated the line of code where it looked for the enemy and added the part that looked for the script in the collision function which fixed it.


4. When the enemy that shoot at the player were created they wouldn't rotate towards the players position and i would get an error message of not finding the player.

Fix: To fix this edit the code where a second game object called target would find the player by looking for the tag and then give the position to a different variable.


5. An error which was not a code error was that when test the level once the enemy spawning emtpy game object was created the enemies it should have spawned were not spawning correctly.

Fix: The reason for this was the code were spawning them where the range was at the center of the scene. To fix this issue was to have the numbers be around the same location to where the spawner will be created.


6. When i was testing the creation of the following enemies with the spawner I noticed that they were not following towards the player. This hasn't happen before but only when I was using the prefab version of the enemy and not one that was already in the scene.

Fix: I realised that the code for those enemies was only working if they were already in the scene and not created while the game was playing. To fix this I changed the code where it once is created it look for the tag which the player has. This was similar to the enemies that shoot.

7.

Fix:


