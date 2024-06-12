# Learn With Game
An intreactive desktop game for ButterflyFields Company as part of an assignment for the internship.<br />
You can Play the game [Here](http://htmlpreview.github.io/?https://github.com/ReyanshKharga/Magnet-Game-For-ButterflyFields/blob/master/Magnet_Game_final_version/playGame.html)<br />
Note: If You are using firefox, the flip functionality doesn't work



# Objective:
Create a game which can be played on a browser. Simulate the scenario given in the image below:

# Game Play:
Player moves a magnet on a path & keeps collecting iron keys on the path. Each time the player's magnet gets attracted to another magnet, the player loses a life. <br />

<h4> Elements in the game:</h4>
1. Main bar magnet (which moves) <br />
2. Bar magnets - at fixed positions <br />
3. Iron keys <br />
4. Obstruction on the path <br />

<h4>Expected behaviour:</h4>
1. Iron keys attract to the bar magnet <br />
2. Two bar magnets repel or attract based on their poles <br />

(Hint: Like poles repel & unlike poles attract) <br />

<h4>Movements: (on specific key press events)</h4>

1. Main bar magnet : <br />
 - Move Right <br />
 - Flip (Change orientation of poles) <br />
 - Jump <br />


2. Iron key - Disappears when main bar magnet comes close to it <br />

3. Fixed position bar magnets: <br />
 - Move upwards when facing a like pole of main bar magnet <br />
 - Player loses life when facing an unlike pole of main bar magnet <br />

<h4>Data to capture & display:</h4>
1. Timer <br />
2. Keys collected <br /><br />


![alt text](https://github.com/speedious/Magnet-Game-For-ButterflyFields/blob/master/Magnet_Game.png)<br />

