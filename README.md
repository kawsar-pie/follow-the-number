# follow-the-number
At the beginning of the game, ten dots appear at random positions on the screen, each with a number next to it. You need to click on the dots in the correct order to connect them. The game will finish once you’ve connected all the dots together.But if you make a mistake, all the lines will disappear and you’ll have to start from the very first dot again.

![image](https://user-images.githubusercontent.com/79654190/171037276-708c9a58-76ab-4ef1-b744-9dcbe69f80de.png)

The dots appear at random positions on the screen. When you click on the correct dot, a line will be drawn between it and the previous dot you clicked on.
Every time you run this game, the program uses a loop to draw the dots at different positions on the screen.

![image](https://user-images.githubusercontent.com/79654190/171037374-4c775df0-38ff-42e1-ae0d-87256a71cfdd.png)

### Algorithm:
This game uses Python’s randint() function to randomly choose x and y coordinates for each of the dots, and then places them all on the screen. It uses the on_mouse_down() function to know when the player has clicked on a dot. If the player clicks on the correct dot, and it’s not the first dot, a line is drawn between the current dot and the previous dot. If the player clicks on the wrong dot, or clicks anywhere else on the screen, all the lines are deleted and the player has to start again. The game ends once the player has connected all the dots.
