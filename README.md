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

**29/10/2024 - 4/11/2024**

I Started making the first tutorial which was going to be a simple player movement. there were many problems but working on the second day i was able to fix them. these errors include the player not moving correctly after doing the code for the player movement and the camera rotating in a axis it was not supposed to.

**5/11/2024 - 11/11/2024**

I Stared and finished the second tutorial in those two days. I decided to make a enemy spawning system as something new that I had never done before unlike with the previous tutorial. I first followed one tutorial to make the code. there were some minur errors but it worked in the end. But unfortenatly the code was basicly identical to the one from the video so on the second day I worked on the tutorial I looked at other videos and information online to find what I could add. This lead to many issues as using different tutorials into one script doesn't work all of the time. But i was able to get something working which I liked and wasn't a exact copy of the first video.

**12/11/2024 - 18/11/2024**

I decided for my third tutorial I would make a enemy shooting at the player. This was simple to make but still took me two days to get it done. the script I used was similar to one from a video with some changes as the video was to be used for a player and not a enemy. I tried to use something similar to the second tutorial with the IEnumerator but it didn't work. But I then figured out and learned to use something that would repeat the function which had most of the script.

**19/11/2024 - 25/11/2024**

For the last tutorial I decided to make two mechanincs similar to the ones from the Mega Man franchise. These were Rush coil and Rush Jet. The jump one was easy to make and learn by looking into code on the unity manual. However the hover one was the hardest to get done which is why it took me two days to get it finished. But in the end I was able to figure out something which worked.

**26/11/2024**

Since I was finished making the mechanics for each tutorial I decided to start working on the prototype. I first had to figure out what I was going to make. I then realised I could do a 3D first person platformer since that means I could use all the code I made for the tutorial in the prototype. So I first added every code to the prototype but instead of copying and pasting I wrote them so not to keep any thing that I didn't need.

**3/12/2024**

I Started testing every since mechanic I added last time to make sure everything was working correctly. Once I checked all the mechanics I started planning what I would need to add for the prototype.

**10/12/2024**



**17/12/2024**



**20/12/2024**



**6/1/2025 - 10/1/2025**



# Errors while making the Tutorials:

1.

2.On my second tutorial code there was no error or issue but I realised that the code was basicly identical to one from the tutorial I first watched to learn how to make the mechaninc.

fix: the sollution was to look at other tutorials see how they did it and try to mix some parts to my script so its not copy and paste from the original video.

 3.while testing the code the script used to reset the limit counter was not reseting. The int value should have reverted back to zero but which would then let the enemies spawn agian. but instead it didn't reset which by by default the code would stop when the limit counter was equal or more to another in variable.

 fix: to fix this error in the code I moved the if statement and line of code from the update function to the function which has most of the code.

 4.When i was making the switch script for the hover support on the player i had a problem where the player would not switch back to 

# Errors while making the Prototype:

1.The player attack was giving an error even if it was working fine.

fix: Altered the code so it gets the enemies health script when colliding instead of when is created/awakened.

2.there were errors with the walking enemy script causing it to not moving towards the player when created and not interacting with the support script.

fix: I made so it looks for the player object by the tag it has, and did a similar thing to the enemy script.







