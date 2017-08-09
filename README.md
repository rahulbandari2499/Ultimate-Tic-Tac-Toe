# Ultimate-Tic-Tac-Toe
A 4x4x4x4 Tic Tac Toe game playing artificial rational agent, which was implemented in Python.

### About the Game
```
Ultimate Tic-Tac-Toe takes the classic game of Tic-Tac-Toe and adds a strategic layer to it.
```

### Description
```
1. Each square of the 4x4 game board contains another, smaller, 4x4 game board. 
2. Where you make your move in a square of any small board, you send the opponent in the respective square of the big board. 
3. 4 in a row in a small board wins the small board and the big square. 
4. 4 small boards in a row wins the game. 
5. Strategize your play, plan your next move, let the opponent win some small boards, while you win the game! 
```

## How to Start?
```
Usage: ' python team64.py <option> '
<option> can be 
1 : Random player vs. Random player
2 : Human vs. Random Player
3 : Human vs. Human
```
## Rules
```
1. This is a 16*16 grid , player has to win 4 grids in row,column or diagonal to win the complete board.
2. Player should make a move in 6 secs, otherwise other player automatically wins.
3. The player will lose if he makes a move in abandoned block or not supposed one according to rules.
4. For detailed explaination of the rules , refer to the pdf file attached.
