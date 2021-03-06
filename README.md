# CS50-Project

## Welcome!

Welcome to our CS50 project! Justin, Cindy and Joey are excited to share with you the work that we have done over the last couple of weeks. 

A brief presentation video of our project can be found here: https://youtu.be/GhRuss3m7B8

## Project Overview 

Our project's objective was to use a genetic learning algorithm to beat our version of "The World's Hardest Game". When you open our project later, you will see that the final product has three different components. The first option is to play the game, the second option is to watch the computer train itself to play the game, and the final option is to see the computer play the game by itself. 

## Getting Started 

Before running the game, it is essential to have installed Python from https://www.python.org/downloads/ , as this game was made for Python 3.8.5. Then, to play the game, you need to install Pygame, which can be done by following these [instructions](https://www.pygame.org/wiki/GettingStarted). This may require you to install [pip](https://pip.pypa.io/en/stable/installing/). Then, to get started with the game itself, download the zip file onto your local computer and unzip the included files into a folder. After doing so, open the folder with either a local or cloud IDE, or navigate to the folder through terminal. 

## Running the Project 

Running the game is done through the file game.py. Depending on your IDE, this will be done through different methods; however, if running through the Command Line Terminal or through CS50 IDE, run `python game.py` in the main folder. After you have run this file, you will see a homescreen presenting you the options to either play the game, watch the computer train, or to see a trained copy running thie game. Use the arrow keys to navigate through the homepage and the enter key to select the option that you wish to play. If you select the option to play the game, you will progress from level 1 to level 5. If you select the option to train the computer or watch a trained program run through the game, you will have the option to choose a specific level from 1 to 3. 

## Playing the Game 

After selecting the option to play the game, you are in control of the red square. Using the arrow keys, try to navigate yourself to the blue dot. You can touch the white walls and will not have to restart, but you cannot cross through the white walls. You must avoid the green obstacles, hitting one will result in a restart of the level that you are on. After reaching the blue dot, you will see a quick success message, and will then be moved on to the next level. After finishing all 5 levels, the game will close. At any point, press H to go back to the homepage and press R to restart the level. 

## Training the Computer and Watching the Computer 

After selecting the option to train the computer or watch the computer play and the specific level, sit back and enjoy! There's not much to do at this point except to watch the dot or cluster of dots try and find its way to the blue goal. At any point, press H to go back to the homepage to select another level to view. 

## Additional Information
### Level Data
Level data is stored in the [level_data](https://github.com/jye-1243/CS50-Project/tree/main/level_data) folder, along with the file used to create the .dat files. Each level has hard-coded walls and obstacles that are then read through the main program. You may elect to change or add levels to the game, which can be done by modifying the [make_levels.py](https://github.com/jye-1243/CS50-Project/blob/main/level_data/make_levels.py) file. 

### Saving Training Data
Currently, running the computer training gamemode does not save the train model to a specific file. To change this, you can uncomment line 453 in [game.py](https://github.com/jye-1243/CS50-Project/blob/main/game.py). This will generate a new file designed to store the best performing dot that is created through training. These files will be created in the main folder.

### Previous Attempts
During the course of this project, we attempt to create a neural network using Keras to train the game based on similar code for [Snake](https://github.com/maurock/snake-ga). While this ultimately did not work (likely due to hardware limitations), the code creating the model can be found in the [PrevTests](https://github.com/jye-1243/CS50-Project/tree/main/PrevTests) folder. This folder also includes our own explorations of the snake code before implementing it into the game.




