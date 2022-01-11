# Flood-It-Clone
App clone of the popular game 'Flood It', created using Android Studio.

**Created with partner Dennis Mills (https://github.com/dennismills)**

The game starts with an n⨉n grid made up of different colored squares. Some areas of the board can be the same color, i.e. it is not required that all adjacent squares on the starting board are different colors. The player starts out in the upper left-hand corner of the board. The player chooses a color and the square in the upper left-hand corner of the board changes to that color - if any surrounding squares match that color, those squares are now part of the player’s ‘flooded’ area. The player then chooses another color, and the ‘flooded’ area will change to the new color, and any surrounding squares that match that color are added to the ‘flooded’ area. The player continues until they have flooded the entire board with the same color or they run out of turns. If the player floods the entire board with the same color they win, if they run out of turns they lose. The number of turns is adjusted based on the number of colors and the dimensions n of the n⨉n board. Some versions of the game do not limit the number of turns a player can take, instead they track the player’s ‘best’ score.

Our game is played with four colors (blue, green, red, and yellow) on a default 10⨉10 board. Players have 13 turns to flood the board. The board size can be adjusted to 14⨉14 (18 turns) or 18⨉18 (24 turns). In some versions of the game, the player can click squares on the board to change the color of the flooded area, and in other versions the player clicks color buttons separate from the board to change the color of the flooded area. Our version includes buttons separate from the board to change the color of the flooded area.


Instructions for using the app:
1) Download the app files from the Github Repository.
2) Launch using Android Studio emulator.
3) Select the “PLAY” button from the launch page.
4) Play the game - press the colored buttons to select a flood color. Starting from the upper left-hand corner of the board, the colors of the flooded area on the board will change according to your selection. The goal is to fill the board with a single color before you run out of turns.
5) To change the board size or turn off the sound effects, select the gear icon from the app bar. This will take you to a settings page to adjust the board size.
6) Other important information: The application was developed to run on minimum android version API 23 (Android 6.0 - Marshmallow) and tested on a Pixel 3a AVD.
