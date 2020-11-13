# minesweeper

This is a Python implementation of 2-D Minesweeper!

Check out the tutorial here: TODO

You can create a new game by running the script and passing in a `-n` flag for dimension (n x n) and a `-b` flag for number of bombs:
```
./minesweeper.py -n 10 -b 10
```
(If you leave these blank, the script will automatically initialize it to a 10x10 board, with 10 bombs)

For now, this script does not have a GUI and you can use terminal :D (If you want to make a GUI, feel free to make a pull request)

In order to "dig" at a certain location, you type in the index of the row, then the column, separated by a comma (whitespace optional). The game "digs" recursively around that location if there are no bombs nearby.

You can continue digging until either you hit a bomb (which is game over) or you've successfully dug up all n-b non-bomb locations (which is victory)!

This repo contains two files:
- minesweeper.py: implementation of minesweeper
- minesweeper_empty.py: empty code template for you to start somewhere :)
