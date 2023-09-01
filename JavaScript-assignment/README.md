JAVASCRIPT ASSIGNMENT

TASK:
Creating small game that user has to light up tha map by placing lights on the white tiles. Rules are described in the game description.

GAME DESCRIPTION:

-The king's palace has rooms with square shaped floors that consist of black and white tiles only.

-Light bulbs can only be placed above white tiles.

-The light from the light bulbs does not spread diagonally, only straight along the given row and column.

-The black tiles have objects placed on them, which block the propagation of light.

-Black cells can optionally contain an integer from 0 to 4. This indicates how many adjacent (bottom, top, right, left) cells contain light bulbs. If there is such a number, the puzzle must be solved accordingly!

-Two light bulbs can NEVER illuminate each other!

-The goal of the game is to place the light bulbs so that all the white tiles are illuminated.

-The game is played by one player until he solves the puzzle, so there is no need to manage multiple players at the same time or divide into rounds.

GAME IMPLEMENTATION:

The game launches on a map selector screen that performs the following:

    -displays a short description of the game
    -the map to be played can be chosen from the (pre-implemented) list of maps
    -the name of the player can be entered
    -the results of previous games are visible here
    -the saved game (if there is one) can be continued
    -the map editor can be launched from here (task for extra points)

There is also the board itself where the game takes place:

    -the elements belonging to the selected map are displayed here (e.g. a table for the correct size but another display method can be used as well, see the help section later)
    -light bulbs can be placed or removed by clicking
    the validity of the player's solution can be checked (either automatically after a stop or with the press of a button)
    -the game can be saved or restarted