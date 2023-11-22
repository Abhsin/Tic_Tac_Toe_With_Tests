The goal of this assignment is to add unit tests to the Tic Tac Toe game:

All the tests should live in tests.py
The tests should be run via the command line successfully, passing all tests
Please add how to run your test in the README.md file in the Git repo, I should be able to run the tests in the command line by copy and pasting the command from your README.md
You can use either unittest or pytest
In writing the tests, you may need to consider refactoring your code to make it easier to test.
As with code in general, where a test is not obvious to understand from the code, add documentation to describe it

The tests should cover the following features

The game is initialized with an empty board
The game is initialized with either 2 players (human-human) or 1 player (human-bot)
Players are assigned a unique piece to plays: X or O
After one player plays, the other player has a turn
All winning end of the games detected, and draw games are identified
Players can play only in viable spots
The correct game winner, if one exists, is detected
