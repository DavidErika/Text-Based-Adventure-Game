# Text-Based Adventure Game

## Project Overview
This project is a text-based adventure game designed as part of a lab exercise for learning Python programming and software development fundamentals. 
The game allows players to navigate between rooms, view descriptions, and interact through text commands. The goal is to understand the basics of game logic, functions, and testing.

## Setup Instructions
1.Download the template:

2.Install Python:
Ensure Python 3.x is installed on your system. You can download it from python.org.

3.Run the Game:

-Open a terminal or command prompt.

-Navigate to the extracted folder.

-Run the game: 'python game.py'

4.Run Tests:
Use doctest to verify functionality: 'python -m doctest -v game.py'

## Project Details
### Step 1: Template Setup
The provided template includes two files:

-map.py: Defines the game world, including rooms and exits.

-game.py: Contains the main game logic, functions, and a game loop.

Start by exploring these files and understanding their structure.

### Step 2: Completing Functions
Follow the steps below to build the game incrementally:

1.Define Room Exits:
In map.py, complete the "exits" field for each room using the provided map diagram.

2.Implement Core Functions:

In game.py, complete the following functions as instructed:

-display_room: Displays the description of the current room.

-print_menu_line: Prints a menu option for an exit.

-print_menu: Prints all available exits.

-menu: Displays the exits and prompts the player for input.

-move: Updates the current room based on the player's choice.

### Step 3: Testing
-The template includes doctest comments for most functions. Run the tests after completing each function to verify correctness.

-Use: 'python -m doctest -v game.py'

Fix any issues to ensure all tests pass.

## How to Play
1.Start the game by running python game.py.

2.Follow the prompts to navigate between rooms using text commands (e.g., north, south).

3.Explore the game world and enjoy the adventure!

## Future Enhancements
-Add more rooms, descriptions, and interactions.

-Include items that players can pick up and use.

-Implement a scoring system based on player actions.

-Enhance input handling to recognize more variations in commands.

Feel free to expand and customize the game as you like!
