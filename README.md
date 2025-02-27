# Project Tic Tac Toe
Project Tic Tac Toe is a Tic-Tac-Toe variant implemented in C# using Windows Forms. The game allows two players to compete against each other on a configurable board size. The UI provides an interactive way to play the game with a simple and user-friendly interface.

## Features

Customizable board size.

Player vs. Player mode.

Interactive Windows Forms UI.

Validation for moves to prevent overwriting existing marks.

Score tracking for players.

## Project Structure

The project consists of the following key files:

1. LogicBoard.cs

Handles the game logic and board state.

Initializes the board.

Validates moves.

Updates board state.

2. MyButton.cs

Custom button class for the game UI.

Defines button size and spacing.

3. Player.cs

Represents a player in the game.

Stores the player's name, mark (X or O), and score.

4. Point.cs

Struct for representing board coordinates.

Stores X and Y positions.

5. Program.cs

Entry point of the application.

Manages the login form.

Initializes the game form with user-specified settings.
