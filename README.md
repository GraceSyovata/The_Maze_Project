Maze Game MVP Specification

(A 3D Game created using SDL2)
![image](https://github.com/GraceSyovata/Research-Project-approval-Part-1-/assets/123548408/7d208aa9-0a98-4828-8b5d-76dc2f2fcb02)

Minimum Viable Product (MVP) for the Maze Game with SDL2:


Explanation:
Walls: Create a 2D array to represent the maze and draw walls using SDL2 graphics library. The walls should be represented by rectangles or lines.
Define a 2D array to store the maze data.

Use SDL2 graphics library to draw walls by rendering rectangles or lines.

Orientation: Use the arrow keys to control the movement and rotation of the player in the maze. You can use SDL_Event to handle user input.
Implement a function to handle user input using SDL_Event.

Update the player's position and orientation based on the input received from the user.

Move: Implement basic movement logic for the player. Allow the player to move forward, backward, left, and right in the maze.
Implement a function to update the player's position based on the current orientation and input received from the user.

Ouch: Add collision detection between the player and the walls. The player should not be able to move through the walls. If the player collides with a wall, stop the player's movement.

Implement a function to check for collision between the player and the walls.

If the player collides with a wall, stop the player's movement.

Parser: Create a simple parser to read the maze data from a text file and store it in a 2D array.

Implement a function to read the maze data from a text file.

Store the maze data in the 2D array.

Draw the Map: Draw the maze using the maze data stored in the 2D array. You can use different colors for the walls and ground/ceiling to make them visually distinct.

Use the maze data stored in the 2D array to draw the maze.

Use different colors to distinguish between the walls and ground/ceiling.

Textures: Add basic textures to the walls using SDL2's texture rendering functions.

Implement a function to load wall textures.

Use SDL2's texture rendering functions to render textures on the walls.

These are the minimum features required to implement a basic maze game with SDL2.

Data Modelling


USER STORY

End users want to be able to play a maze game using SDL2, so that they can have fun solving the maze and challenging myself to improve my speed and accuracy.

When they start the game, they want to see a main menu that allows them to start a new game, load a saved game, or quit the game. If they choose to start a new game, they want to be able to select the difficulty level of the maze, including the size of the maze and the number of obstacles.

Once the game starts, they want to see a maze on the screen, with a character that they control using the arrow keys on their keyboard. They want the character to move smoothly and quickly, without any lag or delay. They also want to see a timer that counts down the time they have to complete the maze, as well as a score that reflects their progress through the maze.

As they navigate through the maze, they want to be able to collect coins or other rewards that will increase their score. They also want to encounter obstacles that will slow them down or make it harder to reach the end of the maze.

When they reach the end of the maze, they want to see a message that congratulates them on completing the maze, and that displays their final score and the time it took them to complete the maze. They also want the option to save their game, so that they can come back and play again later.

Throughout the game, they want to hear sound effects that correspond to their actions, such as collecting coins or hitting an obstacle. They also want to hear music that adds to the excitement and challenge of the game.

Finally, they want the game to be visually appealing, with high-quality graphics and animations that make it fun to play and keep them engaged throughout the game.

Author Grace Musyoka
![image](https://github.com/user-attachments/assets/7a278027-68c0-499b-b99f-992f4bf3f80c)
https://youtu.be/WWU0EuYEzxI

