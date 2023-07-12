# Blackjack Game

This is a simple implementation of the popular card game Blackjack. The code allows you to play the game against a computer opponent. The game follows the basic rules of Blackjack, where the goal is to get a hand with a total value as close to 21 as possible without exceeding it.

The code consists of two files: `main.py` and `art.py`. The `main.py` file contains the main logic of the game, while the `art.py` file contains ASCII art used for the game's visual elements.

## Prerequisites

- Python 3.x

## How to Play

1. Run the `main.py` file in a Python environment.
2. The game will display the ASCII art logo.
3. You will be dealt two cards, and the computer opponent will also receive two cards. One of the computer's cards will be hidden.
4. The game will prompt you with your current cards and score, as well as the computer's first card.
5. You have two options:
   - Type 'y' to request another card (hit).
   - Type 'n' to pass (stand).
6. If you exceed a total score of 21, you will lose the game (bust).
7. Once you pass or reach a score of 21, the computer opponent will play its turn automatically.
8. The computer will continue to draw cards until it has a score of 17 or higher.
9. The final hands and scores of both players will be displayed.
10. The game will determine the winner and display the result.
11. You will be asked if you want to play again. Type 'y' to play another round or 'n' to exit the game.

Please note that the current implementation of the game does not take into consideration changes in card probability as cards are added to the players' hands.

## File Organization

- `main.py`: Contains the main logic for the Blackjack game.
- `art.py`: Contains ASCII art used for visual elements in the game.

## Disclaimer

This implementation is for python learning purposes only and does not include all the features and complexities of a professional Blackjack game.