# Hog Game 

Hog is a dice game with simple rules: two players alternate turns and accumulate points, trying to reach a score of 100. 

![Project Banner](https://github.com/RyanLilleyman/Hog/blob/main/banner.gif)

## Table of Contents
1. [Game Rules](#game-rules)
2. [Prerequisites](#prerequisites)
3. [Running Hog](#running-hog)
4. [Features](#features)
5. [Contact](#contact)


## Game Rules
On each turn, a player has two choices:

- Roll a six-sided die as many times as they want, adding the result of the rolls to their score. However, if they roll a 1, it ends their turn and their score for the turn is only 1 point, as per the **"Sow Sad"** rule.
- Choose to roll zero dice to score 0 points for the turn and add 1 to their score.

In addition to these base rules, the game offers optional rules that can be enabled or disabled on a per-game basis for added complexity:

- **"Boar Brawl"**: If a player rolls zero dice, they score three times the absolute difference between the tens digit of the opponent’s score and the ones digit of the player’s score, or 1 point, whichever is higher.
- **"Fuzzy Factors"**: After a player gains points for their turn, if their resulting score is a "fuzzy number" (any number n where the greatest common divisor (GCD) of n and 100 is greater than 10), the player's score increases by two times the tens digit of the GCD.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- You have installed Python 3.x

## Running Hog

To start playing Hog, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the cloned repository.
3. Run the command `python3 hog_gui.py`.

The game will start, and you can choose to play against either a second player or against a built-in AI. You can also enable or disable the "Boar Brawl" and "Fuzzy Factors" rules per game.

## Features

1. **Command Line Interface** - Play the game through a simple, text-based interface.
2. **Graphical User Interface** - A GUI version of the game is included as well.
3. **AI Opponent** - Play against an AI that uses different strategies to play the game.
4. **Customizable Rules** - The "Sow Sad", "Boar Brawl", and "Fuzzy Factors" rules can be turned on or off for each game, adding extra layers of strategy.

We hope you enjoy playing Hog! Please share any feedback, issues, or suggestions.

## Contact

Please reach out if you have any questions or need further instructions.


