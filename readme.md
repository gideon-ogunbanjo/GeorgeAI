# GeorgeAI
# Overview:
## How GeorgeAI Works

GeorgeAI is programmed to analyze the current state of the board and calculate the best possible move. It uses a neural network model to predict the outcome of each possible move and selects the move that will result in the highest chance of winning.

## findBestMove() Function

The findBestMove() function is a new addition to GeorgeAI's programming. It is designed to find the best possible move in the current state of the board. The function considers all possible scenarios and evaluates the outcome of each move using the neural network model.

## How to Use GeorgeAI

To use GeorgeAI, simply call the findBestMove() function and pass in the current state of the board. The function will return the best possible move.

```python
# Example usage
from georgeai import findBestMove

board = [
    ['X', 'O', ' '],
    [' ', 'X', 'O'],
    ['O', ' ', 'X']
]

best_move = findBestMove(board)

print(f"The best move is {best_move}")

```

## Conclusion

GeorgeAI is a powerful AI designed to play Tic Tac Toe at an expert level. With the addition of the findBestMove() function, it is now even more efficient and effective at selecting the best possible move.

## Tools Used:
VSCode, Git, GitHub, Python.

## Contributors:
Gideon Ogunbanjo
