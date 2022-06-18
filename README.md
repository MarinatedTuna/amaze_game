# AR Maze Game

## Summary

Sample mazes which were drawn and designed got projected on a real world surface which is where the game would be played. Mazes were drawn by hand and then designed on Unity using 3D rectangular objects. These 3D rectangular objects were aligned using a pseudo-graph that was drawn as a set of 3D cubes spaced out 1 inch apart from each other. Vuforia was the plug-in used to project 3D game objects onto the real-world using the laptop's front-facing camera. The image of a Pokemon Sun logo found online was used as a flag to project the game on and the ds box containing the image would be the surface where the game would be projected on. 

## Gameplay mechanics

The ball was set to always fall downwards. That means the way to play the game was to tilt the box so that the ball would fall through the maze until getting to the finish line. After the player reached the finish line, an invisible hitbox would detect that the ball was now in it and a script would load the next level onto the surface. The more mazes the player completes, the harder it becomes.

## Challenges

One of the biggest challenges was figuring out how to implement game engine physics in the real world since there were issues where the ball would move too fast, too slow, or not at all. There were scenarios where the ball would be stuck and the rectangular objects holding the maze together would need to be shifted to not block the way. Sometimes the ball would fall the wrong direction since gravity was not set to go downwards from the player's perspective. All these physics challenges needed to be tackled one by one before the game could be finished.
