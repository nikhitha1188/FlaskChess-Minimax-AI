Flask Chess Minimax AI

A simplified chess game where a human player competes against an AI using the Minimax algorithm.
The board contains only three pieces, making the game fast, focused, and ideal for understanding AI decision-making.

📌 Game Overview

This is a custom-built chess variant played on a standard board but with only 3 pieces:

White (Player)

♔ King

♖ Rook

Black (AI)

♚ King

The player's objective is to checkmate the AI’s King, while the AI’s objective is to survive using strategic movement.

🧠 AI Behavior (Minimax Algorithm)

The AI King uses a Minimax search strategy to evaluate all possible moves and choose the safest one.
The algorithm ensures:

Avoiding danger zones
The AI does not move into squares attacked by the player's King or Rook.

Survival-focused decision-making
AI prioritizes moves that keep it alive the longest.

Optimal path selection
AI explores move outcomes and selects the one with the best evaluation score.

🎨 Custom GUI

The game features a custom-designed GUI, as shown in the screenshot, with:

Clear board visuals

Marked move boundaries

Interactive piece movement

Real-time display of player and AI turns

Tech Stack

Python

Flask

Minimax Algorithm

HTML / CSS / JavaScript

Built using Flask + HTML/CSS/JS.
