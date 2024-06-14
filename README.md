# AI_Project
Connect4 AI using Q-learning: Trained agent plays against itself or random player, with real-time game rendering after each move.

Connect4 Game using Reinforcement Learning
AI Project

Background:
Connect4 is a two-player board game in which players alternately drop colored discs into a vertically hanging grid. The goal is to be the first to create a horizontal, vertical, or diagonal line of four discs of your own color. The game is won by the first player to do this, or it finishes in a draw if the grid is completed without any players establishing a winning configuration.

Objective:
The goal of this project is to use reinforcement learning techniques to teach an AI agent to efficiently play the Connect4 game against a human player or another AI agent.

Connect-4 is a game in which if one were to connect 4 of his moves either horizontally, vertically or diagonally, one records a win. In reinforcement learning setting, we grant reward = 1 for a win, -1 for a lose and 0.5 for a draw. The following game engine object provides five methods.

Render :Showing the board state with 1 and 0s.
Reset : For playing over and over.
Get available moves : Scan the board state and give available moves.
Check game done : Based on which player is making the move, check if one has won the game or a draw has resulted.
Make move : Record the move by players and return observation and reward.

Folder Structure:

AI_Project: Main script for running the Connect4 game and training the AI agent.
DQN_agent: Defines the DQNAgent class responsible for training the AI agent using Deep Q-Networks.
README.md: Documentation for the project.
Presentation in PDF.

Langauge/Concepts Used:
Q-Learning
Reinforcement Learning
PyTorch
Keras
