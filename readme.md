To run tests, run the following command in the command line:

python3 tests.py


The goal of this assignment is to add unit tests to the Tic Tac Toe game:

1. All the tests should live in tests.py
2. The tests should be run via the command line successfully, passing all tests
3.Please add how to run your test in the README.md file in the Git repo, I should be able to run the tests in the command line by copy and pasting the command from your README.md
4. You can use either unittest or pytest


In writing the tests, you may need to consider refactoring your code to make it easier to test.
As with code in general, where a test is not obvious to understand from the code, add documentation to describe it

The tests should cover the following features

1. The game is initialized with an empty board
2. The game is initialized with either 2 players (human-human) or 1 player (human-bot)
3. Players are assigned a unique piece to plays: X or O
4. After one player plays, the other player has a turn
5. All winning end of the games detected, and draw games are identified
6. Players can play only in viable spots
7. The correct game winner, if one exists, is detected
