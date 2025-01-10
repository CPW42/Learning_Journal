tutorial 1:

first person player movement similar to doom these are moving forwad and back to where the player is facing. 
Moving left and right to where the player is facing. 
Having the player only move the camera form left and right and not up and down. hiving the player be able to dash with a press of a button.

notes and things to remember about the code: 
.the main player only the main camera. .for the player movement both side and forward movement use similar script with the only difference being if it says right or forward after the vector3. .there are two floats which are used for the dash code in the player movement script. these two are the "speedDash" and "originalSpeed". in addition there is a float used .when the script is first started it first locks the cursor so it can't be moved out of the game. the originalSpeed float becomes equal to the value of the speed float. and the speedDash float has the its number become the double of the speed float. .for the camera movement its similar to the other tow scripts but instead it rotates the camera in the x axis by following the cursor. .for the dash code in the script it simply changes the value of the speed float to the speed dash foalt when pressed and then to the original speed float after the key is released.


enemy spawner:

.have a empty object where all the code will be

.have either a area around the object where the enemies will spawn or have the enemies spawn on the game object

.have where the enemies spawn only a specific amount by possibly having a limit of how many enemies can the spwaner spawn.


enemy shooting:

.have the player know where the player location

.have them shoot the player every certain time

.have the projectiles be destoried when colliding with the player and the environment


player only object*for example rush from the original mega man games:

.have one where it bounces the player up when the player goes into the object

.have the other move the player when they are standing on top. the player can go in the air but can only move up and down slower then moving left and right

.have both disappear after some time has passed*have a timer on the screen or show it on the console*
