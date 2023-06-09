# Tic-Tac-Toe-with-pygame

Tic Tac Toe Game using Pygame
This is a simple implementation of the Tic Tac Toe game using the Pygame library. The game features a graphical user interface where two players take turns marking X and O on a 3x3 grid. The first player to get three marks in a row, column, or diagonal wins the game.
Dependencies
The game requires the following dependencies to be installed:
•	Python 3.x
•	Pygame library
You can install the Pygame library by running the following command:
Copy code
pip install pygame 
How to Play
1.	Run the script using Python.
2.	A Pygame window will open with a 3x3 grid representing the Tic Tac Toe board.
3.	The first player is represented by circles (O), and the second player by crosses (X).
4.	Players take turns clicking on an empty cell to mark their symbol.
5.	The game automatically detects the winner or a tie and displays the result.
6.	To restart the game, press the 'R' key.
Code Structure
The code is structured into several functions to handle different aspects of the game:
•	draw_lines(): Draws the horizontal and vertical lines to form the Tic Tac Toe board.
•	draw_figures(): Draws the X and O symbols on the board based on the state of the game.
•	mark_square(): Marks a square on the board with the player's symbol.
•	available_square(): Checks if a square on the board is available for marking.
•	is_board_full(): Checks if the board is completely filled with symbols, resulting in a tie.
•	check_win(): Checks if a player has won the game by getting three symbols in a row, column, or diagonal.
•	draw_vertical_winning_line(), draw_horizontal_winning_line(), draw_asc_diagonal_win_line(), draw_desc_diagonal_win_line(): Draws a line on the winning row, column, or diagonal.
•	restart(): Resets the game state to play again.
•	main(): The main game loop that handles user input and updates the game state.
Customization
You can customize the game by modifying the constants defined at the beginning of the script. These constants define the size of the game window, the dimensions of the Tic Tac Toe board, the colors used for drawing, and the size of the symbols.
Feel free to modify these constants to change the appearance and behavior of the game.
Conclusion
This Tic Tac Toe game provides a fun and interactive way to play the classic game. By utilizing the Pygame library, the game creates a graphical user interface that allows players to mark their symbols on the board and automatically detects the winner or a tie. The code is organized into functions for easy understanding and modification.
Have fun playing Tic Tac Toe!

