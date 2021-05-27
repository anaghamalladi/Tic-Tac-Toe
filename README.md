# Tic-Tac-Toe
Tic-Tac-Toe is a two player game, that is played on a 3*3 square grid. Each player occupies a cell in turns, with the objective of placing three marks in a horizontal, vertical or diagonal pattern. One player uses cross 'X' as his marker, while the others uses a nought 'o'.
tkinter Python library is used to create the GUI. Two options are available to play the game, along with the system or with another player.
A small winning strategy is used to play with the system. The system will try to find the best place to put its naught or cross by which the system will win or try to stop players to win. 

Approach:
Create a landing page containing selection buttons: Single-player or multiplayer.
Create a game-board containing nine tiles to play the game along with other details (i.e. playing with a system or another player, whose turn etc.).
Allow the player to press the tile and check the status of the game (i.e. Tie game, anyone of the players won the match or the game is still running).
Display the message, who won the match.

Description of other functions:
gameboard_pc() and gameboard_pl() will create the another geometry to play the game. It will add 9 buttons on 3×3 board of the game (Three rows of buttons containing three buttons each).
get_text_pc() and get_text() functions will put the text on buttons as it pressed.
pc() function will decide the next move of the system.
winner() function will check whether the player won the match or not.
isfree() function will check whether the player can put it’s a coin or not.
