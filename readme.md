# GeorgeAI
# Overview:
## How GeorgeAI Works

GeorgeAI is a model designed to play Tic Tac Toe optimally, considering all possible scenarios to make the most optimal move. It is built using Python and several popular machine learning libraries, including Numpy and Scipy.

### Game Rules
Tic Tac Toe is a two-player game played on a 3x3 grid board. The game starts with an empty board and players take turns to place their mark ('X' or 'O') on an empty cell. The first player to place three of their marks in a row (horizontally, vertically, or diagonally) wins the game. If all cells are filled without any player winning, the game is drawn.

### Model Architecture
GeorgeAI uses a minimax algorithm to find the most optimal move in each turn of the game. Minimax is a decision-making algorithm that is used to minimize the possible loss for a worst-case scenario. In Tic Tac Toe, this means that GeorgeAI considers all possible moves that could be made by the opponent and selects the move that minimizes the maximum possible loss.

To further optimize the minimax algorithm, GeorgeAI uses alpha-beta pruning, a search algorithm that reduces the number of nodes that need to be evaluated in the minimax algorithm. This reduces the computational cost of evaluating the game tree, making it possible to play Tic Tac Toe optimally in real-time.

The Pseudo code is as follows:
```
 function findBestMove(board):
    bestMove = NULL
    for each move in board :
        if current move is better than bestMove
            bestMove = current move
    return bestMove
    ```

### Usage
To use GeorgeAI to play Tic Tac Toe, follow these steps:

Load the Tic Tac Toe board into Python using a suitable method.
Define which player is going to start the game.
Call the get_optimal_move() function, passing in the current state of the board and the current player.
The function will return the most optimal move for the current player to make.
Update the Tic Tac Toe board with the optimal move, and repeat steps 3-5 until the game is won, drawn or lost.



## Tools Used:
VSCode, Git, GitHub, Python.

## Contributors:
Gideon Ogunbanjo
