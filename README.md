# Getting Started

# This Game is about creating a warrior and killing Monsters. Once the main Monster "Barlog" is killed, the warrior wins the game.
# The warrior is giving initial health/live points. After each monster killing, the warrior is given some experience points and deducted some health points.
# Once the warrior reaches a threshold of experience points, he will be moved to the next level called adventurer.
# If the warrior is killed by the monster, the game is over.

I have implemented below features
- At the start of the game you could set the name of you Warrior. 
- I have not implemented any map, you just exploring and trying to find and beat a monster.
- After each move you could encounter a monster
- If you think that you couldn't beat a monster, you could run away.
- Fighting is computed in following order: warriorhitting monster, than, if monster is alive, it is hitting back. If everybody are alive after that - repeat.
- For each killed monster you will gain a bunch of experience points.
- On each level up you health points are restored (to the new maximum)
- After you'll kill the final monster - the game is over, you won it!
You could save the game and resume it at the start (but there could be only one file per installation)

### For running the application use the below command.

java -jar target/game-rpg-1.0.jar


