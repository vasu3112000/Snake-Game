# Snake Game

We all have played a very famous game in our childhood on our touch button mobile phones known as snake game. In the game, there is a square box which acts like a snake in the game. There is another square box which is referred to as the food of the snake. The snake can change it's directions using the arrow keys in our keypad. Whenever, the snake eats the food, i.e., the two squares meet collide, another square is added the tail of the snake and the length of the snake increases. Further, to increase the difficulty of the game, the speed of the snake also increases gradually with time. This is the overall working of the game that I've implemented. 

## Installation

Download the complete folder and save it anywhere on your desktop. Open the file named test.py in a any python IDE such as pycharm, anaconda etc.

Install pygame, time and random libraries in your interpreter if they are not present. Once installed, you're ready to use the software.

## Basic Summary

Once you run the code, a new window will open up and software will be launched. The screen will contain three items: - A pink colored square indicating the snake, a white colored square indicating the food and your score at the top left corner. 

The square indicating the snake will start moving as soon as you press anyone of the arrow keys present in our keyboard. The snake will change it's directions according to the arrow keys you press, and on intersecting with the food box, it's length will increase by adding another square box.

The game will end when the snake touches it's tail or the head of the snake collides with any of the boundaries. To replay, press the "C" button key on the keyboard and to quit, press "Q".


## Code Explanation

In the initial lines of code, I've declared the colors that will be used in our software, the size of the window to play the game and the initial block size and block speed.

The first function Your_score is use to display the user's score for the current game.

The next function our_snake shows our square for snake on the screen.

The message function is used to display any message on the screen. The message will be inputted when we use the function.

The gameLoop is the main function in our code. It sets the gave over and game close variable to false to start the game. It'll further set different variables like x and y co-ordinates of the snake and food, length of snake as 1 etc. Then, the main code for overall functioning of the software comes. If the game close variable gets true, the message will come out for further action that needs to perform. On starting the game, the actions of arrow keys will be set, random locations of the food square will set and the length of the snake will also gets increased if the snake gets the food. At the end, it'll also calculate the time of the game.
