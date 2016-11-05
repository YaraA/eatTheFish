<h2> The Chase </h2>
In this assignment, you are required to build a The Chase game using OpenGL. The main game idea is that there is an object (human, car, an animal, or anything) which is stuck in some place. However, this object is not alone. There are others (of its kind, or maybe not) in the same place. Some are chasing,others to be chased. In what follows, the following points are discussed in more details:
  1. Gameplay.
  2. Special power.
  3. Game modes.
  4. Game status.
  5. Controls.
  6. Bonus.
  
<h2> Gameplay </h2>
The game is mainly about an object that the player controls. This object is being chased by a group objects that decrements the players score when they manage to catch him (or kill him in another game mode). Another group of objects are escaping and the player should try to catch them to increment their score. This being said, for the game objects, looks and motion is to be implemented.
  1. Objects looks: player should easily differentiate between objects heads and bodies; minimum requirement is to shapes with deferent colors (10%).
  2. Objects motion is divided into two points:
    a. Objects change their direction of looking as the player always looks the way it goes, chasers always look towards the player, and chased always look towards the opposite direction of the player.
    b. The player moves based on the player control, chasers always move towards the player, chased always move away.
  3. Each group (chasers, and chased) contains at least two objects. Members of the same group should look alike, but moves with deferent speeds.

<h2>Special Power</h2>
After 30 seconds of the game start, the player will be granted the ability of performing one of two special power moves, once in the whole game. Special power moves are:
  1. Double score: for the upcoming 30 seconds, all score acquired (positive or negative) is multiplied by two.
  2. Chasers stun: for the upcoming 30 seconds, all chasers stop moving.

<h2>Game Modes</h2>
The game has two modes:
  1. Time based: the game lasts for 5 minutes.
  2. One shot kill: the game lasts till the player gets caught by a chaser.

<h2>Game Status</h2>
Throughout the gameplay, the player should aware about anything that affects the gameplay. Mainly, there things are to be covered:
  1. Score.
  2. Time.
  3. Special power move ready, active, or already used.

<h2>Controls</h2>
The controls can be divided to:
  1. The player motion control with the mouse.
  2. Activation of special power moves.
  3. Exiting the game, as the game is running on full screen.
