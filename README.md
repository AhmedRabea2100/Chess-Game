# Chess-Game!

Simple 2D Chess game.

# User Manual

## Game Flow

Starts by the `white` player entering his first move (e.g A7A6) then the black player and so on.

## Input Validation
Input should be in the form `C1R1C2R2`, in which C1R1 indicates the place where the required piece is on the board and C2R2 is the destination
if the move is invalid or written in other format the game will ask for another move.

## Piece Promotion
Same as normal move but in addition to that the player must identify the piece he wishes to upgrade the pawn to (e.g H2H1Q) will upgrade the white pawn into a queen.

## Undo
Type `undo` to undo the last move (the game can be undone till the first move).

## Save and load
For saving the game type `save` and `load` to reload it again.
