# Learning_Journal
My journal for programing

idea for what the tutorials will be connected to:
a similar doom mechanics from the first 2 games
a simple start menu
enemy following the player form the moment they are created
a enemy spawner
player projectiles


tutorial 1:

first person player movement similar to doom
these are moving forwad and back to where the player is facing. 
Moving left and right to where the player is facing.
having the player only move the camera form left and right and not up and down.
hiving the player be able to dash with a press of a button.

notes and things to remember about the code:
.the main player only the main camera.
.for the player movement both side and forward movement use similar script with the only difference being if it says right or forward after the vector3.
.there are two floats which are used for the dash code in the player movement script. these two are the "speedDash" and "originalSpeed". in addition there is a float used 
.when the script is first started it first locks the cursor so it can't be moved out of the game. the originalSpeed float becomes equal to the value of the speed float. and the speedDash float has the its number become the double of the speed float.
.for the camera movement its similar to the other tow scripts but instead it rotates the camera in the x axis by following the cursor.
.for the dash code in the script it simply changes the value of the speed float to the speed dash foalt when pressed and then to the original speed float after the key is released.

things not needed to be included in the tutorial * these are not part of the tutorial but just so i could test the script to see if it works correctly with ridgid body*:
player interacting with object
player having a ridgid body 

tutorial 2 *may change what im doing*:

a enemy spawner
have a spawning mechanic where it spawns a enemy. 
have it where when a certain requirement is met it will stop spawning enemies or will spawn different enemies

tutorial 3 

enemies shooting projectiles at the player


reference i used for code of the script for the tutorials:


Tutorials:

1.

2.On my second tutorial code there was no error or issue but I realised that the code was basicly identical to one from the tutorial I first watched to learn how to make the mechaninc.

fix: the sollution was to look at other tutorials see how they did it and try to mix some parts to my script so its not copy and paste from the original video.

 3.while testing the code the script used to reset the limit counter was not reseting. The int value should have reverted back to zero but which would then let the enemies spawn agian. but instead it didn't reset which by by default the code would stop when the limit counter was equal or more to another in variable.

 fix: to fix this error in the code I moved the if statement and line of code from the update function to the function which has most of the code.

 4.When i was making the switch script for the hover support on the player i had a problem where the player would not switch back to 

Prototype

1.The player attack was giving an error even if it was working fine.

fix: Altered the code so it gets the enemies health script when colliding instead of when is created/awakened.

2.there were errors with the walking enemy script causing it to not moving towards the player when created and not interacting with the support script.

fix: I made so it looks for the player object by the tag it has, and did a similar thing to the enemy script.







