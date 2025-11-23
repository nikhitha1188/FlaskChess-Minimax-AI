# Flask Chess Minimax AI

A simplified chess game where a human player competes against an AI controlled by the Minimax algorithm. The game uses only three pieces, making it fast, focused, and ideal for understanding how AI makes decisions.

## Game Overview

The game is played on a standard chessboard but with only three pieces:

White (Player)
- King
- Rook

Black (AI)
- King

Player objective: Checkmate the AI’s King  
AI objective: Survive as long as possible using optimal moves

## AI Behavior (Minimax Algorithm)

The AI evaluates possible moves using the Minimax strategy and selects the move that provides the best chance of survival.

AI behavior includes:
- Avoiding danger zones where the player's pieces can attack
- Choosing moves that increase survival time
- Exploring future move outcomes and selecting the optimal path

## Custom GUI

The game includes a custom-designed graphical interface featuring:
- Clear board visuals
- Marked move boundaries
- Interactive piece movement
- Real-time display of both player and AI turns

## Tech Stack

- Python
- Flask
- Minimax Algorithm
- HTML, CSS, JavaScript



