# Chess Board

## Overview

Construct a chessboard using numpy and matplotlib.

## Links

- [See the Code](chess_board.ipynb)
- [Pull Request](https://github.com/daveeS987/chess-board/pull/1)

## Feature Tasks and Requirements

- Render out chess boards with red and blue queens on them.
- Chess board is an 8 by 8 grid of alternating black and white squares.
- Each board will have one red and one blue queen at different coordinates.
- In addition to displaying the board, identify if the queens are “under attack” based on their coordinates.

## Implementation Notes

Define a ChessBoard class - should contain an 8x8 grid - Each cell in grid should have a color represented in RGB format. - black = (0,0,0) - white = (1,1,1) - blue = (0,1,1) - red = (1,.2,0)

- should have add_red method that accepts a row and column as input which colors corresponding cell.
- should have add_blue method that accepts a row and column as input which colors corresponding cell.
- should have render method that displays the chess board on screen with red and blue shown in correct locations
- should have is_under_attack method that return boolean if red is under attack by a blue piece horizontally, vertically or diagonally

## Tools and Dependencies

- Poetry
- Numpy
- Matplotlib
- Jupyterlab

## Getting Started

- Clone down this repo
- cd chess-board
- `poetry install`
- `poetry shell`
