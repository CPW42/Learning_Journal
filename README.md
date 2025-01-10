# Learning_Journal
My journal for programing

idea for what the tutorials will be connected to:
a similar doom mechanics from the first 2 games
a simple start menu
enemy following the player form the moment they are created
a enemy spawner
player projectiles

# Dates and Info:

**29/10/2024 - 4/11/2024**

I Started making the first tutorial which was going to be a simple player movement. there were many problems but working on the second day i was able to fix them. these errors include the player not moving correctly after doing the code for the player movement and the camera rotating in a axis it was not supposed to.

**5/11/2024 - 11/11/2024**

I Stared and finished the second tutorial in those two days. I decided to make a enemy spawning system as something new that I had never done before unlike with the previous tutorial. I first followed one tutorial to make the code. there were some minur errors but it worked in the end. But unfortenatly the code was basicly identical to the one from the video so on the second day I worked on the tutorial I looked at other videos and information online to find what I could add. This lead to many issues as using different tutorials into one script doesn't work all of the time. But i was able to get something working which I liked and wasn't a exact copy of the first video.


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







