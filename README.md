# Rock-Paper-Scissors Game

## Overview

This is a simple Rock-Paper-Scissors game implemented in Python. The game allows a player to choose between Rock, Paper, or Scissors and plays against a computer that makes a random choice. The game then determines the winner based on standard game rules.

## Features

- **Player Input:** Allows the player to select Rock, Paper, or Scissors.
- **Computer Choice:** The computer makes a random choice from the available options.
- **Winner Determination:** The game determines if the result is a win, loss, or draw, and displays the outcome accordingly.

## Prerequisites

- Python 3.x
- No additional libraries are required beyond Python’s standard library.


How to Play

When prompted, enter your choice by typing R for Rock, P for Paper, or S for Scissors.
The computer will make a random choice.
The result will be displayed, showing whether you won, lost, or if the game was a draw.

## Example 

Choices:

(R)ock

(P)aper

(S)cissors

Pick: R

Computer picked: S

Player wins! Rock crushes Scissors.

## Code Details

get_player_choice(): Prompts the player for their choice and validates it.

get_computer_choice(): Generates a random choice for the computer.


is_draw(player_choice, computer_choice): Checks if both the player and the computer made the same choice.

print_winner(player_choice, computer_choice): Determines and prints the result of the game.

play_game(): Main function that orchestrates the game flow.
