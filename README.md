Loading Game...
INTRO SCREEN
“If you are new, enter a save code (1-3) to save character progress from completed levels,
“If you are a returning player enter your previous save code to go to the next level past one you have completed”
“If you want to clear a save, type “C” and then the save code for the save you want to clear”
loop(Enter Save Code:)
Enter Name: (only if it is a new player)
“Enter H into the prompt ‘> ‘ to see a full list of commands”
LEVEL 1: Gloomy Woods
Character Intro -
Display paths
Path1:
Commit?
Run (go back to previous position, and display paths)
Path2:
Commit?
Run (go back to previous position, and display paths)

Functions for main:
H (help(): prints all commands and descriptions)
E (exit(): prompts the user to confirm an exit, then exits the program loop)
L (look(): prints paths available to the user and vague descriptions if the choices have been completed in the scene)
D (whoami(): prints player lore)
S (stats(): prints player statistics)

Object LevelMap
Array scenes
Story Array
Object character
Name
Intro array (chooses a random one)
Effects vector
Levels Completed
Lore vector of strings
Object scene
id which will match to choices array index
Name
Vague description
Main description
Choices
Array paths
Story addition
