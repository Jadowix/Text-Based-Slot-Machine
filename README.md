# Python Slot Machine Game

This Python project implements a simple slot machine game where players can place bets and spin the reels to win credits. The game is implemented using Python and utilizes random number generation to determine the outcome of each spin.

## Features

- **Basic Slot Machine Gameplay:** Players can deposit credits, place bets, and spin the reels to try and win.
- **Customizable Bet Amounts:** Players can choose the amount to bet on each line within specified limits.
- **Multiple Betting Lines:** Players can bet on multiple lines, increasing their chances of winning.
- **Winning Conditions:** The game checks for winning combinations on each spin and calculates the player's winnings accordingly.

## How to Play

1. **Deposit Credits:** Players start by depositing a certain amount of credits into the game.
2. **Place Bets:** Players choose the number of lines to bet on and the amount to bet per line.
3. **Spin the Reels:** Players spin the reels to see if they win any credits.
4. **Repeat or Quit:** Players can choose to continue playing by pressing Enter or quit the game by typing 'Q'.

## Getting Started

To run the game locally on your machine, follow these steps:

1. Clone this repository to your local machine:

   ```
   git clone https://github.com/Jadowix/slot-machine-game.git
   ```

2. Navigate to the project directory:

   ```
   cd slot-machine-game
   ```

3. Run the Python script:

   ```bash
   python slot_machine.py
   ```

## Configuration

- **MAX_LINES:** The maximum number of lines that players can bet on.
- **MAX_BET:** The maximum bet amount per line.
- **MIN_BET:** The minimum bet amount per line.
- **ROWS:** The number of rows in the slot machine.
- **COLS:** The number of columns in the slot machine.
- **symbol_count:** Dictionary mapping symbols to their frequencies in the slot machine.
- **symbol_value:** Dictionary mapping symbols to their respective values.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, feel free to fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE] file for details.
