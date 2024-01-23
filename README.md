# TicTacToe-CoreJava

Sure, let's break down the code in simpler terms:

1. **TicTacToe Class:**
   - It's like the game board. It sets up a 3x3 grid to play Tic-Tac-Toe.
   - It has methods to clear the board, show the board, put X or O marks on the board, and check if someone has won or if the game is a draw.

2. **Player Abstract Class:**
   - Think of this as a blueprint for players in the game.
   - Every player (human or AI) needs a name and a mark (X or O).
   - It says that every player must have a way to make a move, and there's a rule to check if a move is valid.

3. **HumanPlayer Class:**
   - This is a type of player where a real person (you, for example) can play.
   - When it's your turn, you'll be asked to pick a row and column to place your X or O on the board.

4. **AIPlayer Class:**
   - This is a type of player that's controlled by the computer.
   - When it's the computer's turn, it randomly picks a row and column on the board to place its mark.

5. **LaunchGame Class:**
   - This is where the game actually starts.
   - It creates the game board, a human player, and a computer player.
   - Players take turns making moves until someone wins or the game ends in a draw.

**Game Flow:**
   - The game begins with an empty board.
   - Players (you and the computer) take turns placing their marks on the board.
   - The computer makes random moves, and you input your moves through the console.
   - The game continues until someone wins or the board is full (draw).

**Note:**
   - The `initBoard()` method sets up the board with empty spaces.
   - `displayBoard()` shows you what the board looks like after each move.
   - There are checks (`checkColWin()`, `checkRowWin()`, `checkDiagWin()`, `checkDraw()`) to see if someone has won or if the game is a draw.

In short, it's a simple game where you play Tic-Tac-Toe against the computer. The code handles the rules, the board, and the moves.
