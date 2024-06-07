# Chess

Using object-oriented design ideas to design and implement the Chess game.

## Chess Game Implementation

### Overview

For this project, a chess game is implemented using object-oriented design principles. The game allows two players to take turns making moves on a chessboard represented in text format. Moves are entered via standard chess notation.

### Features

Real-Time Chessboard: The game draws the chessboard in the terminal and prompts the current player for a move.

Legal Moves: The game validates moves to ensure they comply with the rules of chess.

Special Move Formats: Supports special move formats like castling, pawn promotion, resigning, and offering a draw.

Ending the Game: The game ends with checkmate, resignation, or a draw.

### Implementation Details

Object-Oriented Design: We structured the code using object-oriented principles to encapsulate pieces, players, and the chessboard.

Chess Class: The main logic resides in the Chess class, where the start and play methods are implemented.

### Development Environment

We developed the game using VSCode. The Chess class is located in the chess package, and the main logic is filled in the start and play methods.

### Testing

To test the implementation, we used the PlayChess application provided. This application allows us to call the start and play methods and observe the game's behavior.
