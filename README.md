# Java Tic Tac Toe Game

This is a simple console-based Tic Tac Toe game implemented in Java. The game allows two players to take turns entering their moves until one of them wins or the board is full.

## Getting Started

To run the Tic Tac Toe game, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone [repository_url]

2. **Compile the Java Code:**
   ```bash
   javac Main.java

3. **Run the Game:**
   ```bash
   java Main

## How to Play
The game initializes with an empty 3x3 board.

- Players take turns entering their moves. The board is represented by a 3x3 grid, and each cell is identified by its row and column.

- Players enter their move by specifying the row and column (0-indexed) where they want to place their symbol ('X' or 'O'). For example:

```bash
    Player X enter: 0 0
```

- The game continues until one player wins or the board is full. If the board is full and no player has won, the game ends in a draw.

- The winning conditions include having three of the same symbol in a row (horizontally, vertically, or diagonally).

## Additional Information
- The current player is displayed on the console prompt.
- Invalid moves (e.g., choosing an already occupied cell) are not allowed, and the player will be prompted to try again.
