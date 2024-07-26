# Card Game

This project is a simple implementation of a two-player card game in Python, inspired by the classic "War" card game. The game is designed to simulate a card battle where players draw cards from their decks and compare their values to determine the winner.

## Features

- Two-player gameplay
- Deck creation and shuffling
- Card dealing and comparison
- Handling of "war" scenarios when cards are of equal value
- Game ending conditions based on card availability

## Requirements

- Python 3.x

## Files

- `class.py`: Contains the classes for the card game, including `Card`, `Deck`, and `Player`.
  - **Card Class**: Represents a single card with a suit, rank, and value.
  - **Deck Class**: Represents a deck of 52 cards, with methods to shuffle and deal cards.
  - **Player Class**: Represents a player with a hand of cards and methods to add or remove cards.

- `main.py`: The main script that sets up and runs the game.
  - Initializes two players and a deck.
  - Deals cards to each player.
  - Manages game rounds, including handling the "war" scenarios when cards are of equal value.
  - Determines and prints the winner of each round and the overall game.

## Installation

1. Ensure you have Python 3.x installed on your system.
2. Download or clone the repository.

## Usage

To start the game, run the `main.py` script:

```bash
python main.py
