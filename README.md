# Asteroids

1. Started by setting up the git repository and then proceded to create the virtual environment for this project. Then I installed Pygame.

2. Created the main.py file.

3. Learned about imports and how to use them to construck our project.
Created the constants.py file and modified main.py to import from constants.py.

4. Updated main.py: Added details for display window, created a infinite loop for the screen.
Tested the loop. Created a .gitignore file.

5. Created the circleshape.py file and added the predefined CircleShape class.

6. Updated the constants.py file to include the player size.
Created the Players class in the Player.py file.
Updated the main.py main function to draw the player object in the screen.

7. Updated the constants.py, main.py and player.py files. Introduced the PLAYER_TURN_SPEED variable to constants.py.
Created the update method on the Player class.
Updated the loop in the main.py to reflect the changes made.
Player can now rotate using a and d keystrokes.

8. Updated the constants.py and player.py Introduced the PLAYER_SPEED variable to constants.py.
Created the move method on the player class and updated the update method.
Player can now move using the w and s keystrokes.

9. Added groups to main.py. Updated loop to reflect the changes.

10. Created asteroids.py and asteroidsfield.py.
Created Asteroid class on asteroid.py.
Created asteroidField class in asteroidfield.py.
Updated main.py to reflect the changes.
There are Asteroids in the game now.

11. Updated circleshape.py and main.py. 
Created the check_collision method on circleshape.py.
Updated main.py to check for asteroid - player collisions.

12. Created Shot class in shot.py
Created the shoot method in player.py
Updated constants.py and main.py to reflect the changes made.
Players can now shoot in a straight forward line.

13. Updtated player.py and constants.py.
Shoot now has a cooldown to prevent infinite shooting.

14. Modified main.py to insert asteroid and bullet collision.
Asteroids now vanish when hit by a bullet, the bullet disappears too.

15. Modified asteroid.py and main.py.
Created the split method on asteroid.py file.
Big and medium now split into two smaller asteroids when hit by a bullet.
Small asteroids disappear when hit by a bullet.
Updated main.py to reflect the changes.

Finished this project!