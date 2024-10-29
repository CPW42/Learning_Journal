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


reference i used for code of the script for the tutorials:

tutorial 1:
1.https://discussions.unity.com/t/how-to-rotate-the-camera-up-and-down-using-mouse-input/239201
