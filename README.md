# CRIC-IN: A Visual Cricket Game

CRIC-IN is a simple console-based cricket game implemented in C++. The game allows users to create two teams, Team-A and Team-B, with four players each from a pool of 11 predefined players. The game simulates a cricket match between the two teams, with each innings consisting of six balls.

First unzip file and download for implementation

## Features

- Create two teams (Team-A and Team-B) with four players each from a pool of 11 players.
- Toss to decide the batting and bowling teams.
- Simulate a cricket match with each innings consisting of six balls.
- Display scorecard and match summary after each innings.
- Determine the winner based on the total runs scored and wickets lost.

## Implementation Details

The game is implemented using object-oriented programming principles in C++. The following classes are defined:

- Player: Represents an individual player with attributes like name, runs scored, balls played, balls bowled, runs given, and wickets taken.
- Team: Represents a team with attributes like name, total runs scored, wickets lost, total balls bowled, and a vector of players.
- Game: Manages the overall game flow, including player selection, toss, innings simulation, scoring, and result calculation.

The Game class contains various member functions to handle different aspects of the game, such as displaying the welcome message, selecting players, simulating the toss, playing innings, updating scores, and displaying the scorecard and match summary.
