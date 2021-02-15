Tic Tac Toe

Tic-tac-toe, noughts and crosses (Commonwealth English), or Xs and Os/“X’y O’sies”, is a game for two players, X and O, who take turns marking the spaces in a 3×3 grid. The player who succeeds in placing three of their marks in a diagonal, horizontal, or vertical row is the winner.

Here both the seperate code are given one using C++ and another way of implementation with random number is shown using Python. 

Python implementation of automatic Tic Tac Toe game using random number

Tic-tac-toe is a very popular game, so let’s implement an automatic Tic-tac-toe game using Python.

The game is automatically played by the program and hence, no user input is needed. Still, developing a automatic game will be lots of fun. Let’s see how to do this.

numpy and random Python libraries are used to build this game. Instead of asking the user to put a mark on the board, code randomly chooses a place on the board and put the mark. It will display the board after each turn unless a player wins. If the game gets draw, then it returns -1.

Explanation :
play_game() is the main function, which performs following tasks :

Calls create_board() to create a 9×9 board and initializes with 0.
For each player (1 or 2), calls the random_place() function to randomly choose a location on board and mark that location with the player number, alternatively.
Print the board after each move.
Evaluate the board after each move to check whether a row or column or a diagonal has the same player number. If so, displays the winner name. If after 9 moves, there are no winner then displays -1.
