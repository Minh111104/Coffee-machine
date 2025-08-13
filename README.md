# Coffee-machine ☕

This project is a simple Coffee Maker command-line interface (CLI) simulation built in Python. It models a coffee machine that allows users to choose from different drinks, check resources, process payments, and serve coffee.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Modules](#modules)

## Features

- **Menu of Drinks**: Choose from latte, espresso, or cappuccino.
- **Resource Management**: The coffee maker tracks water, milk, and coffee supplies.
- **Payment Processing**: Simulates accepting coins and calculating the change.
- **Report Function**: Check the current resource levels and profit.
- **Turn Off**: A command to shut down the coffee maker.

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/coffee_maker.git
    ```

2. Navigate to the project directory:
    ```bash
    cd coffee_maker
    ```

3. Ensure Python 3.x is installed.

## Usage

1. Run the `main.py` script:
    ```bash
    python main.py
    ```

2. Choose from the available options:
   - Type `latte`, `espresso`, or `cappuccino` to order a drink.
   - Type `report` to view the machine's resource and profit report.
   - Type `off` to turn off the coffee machine.

## Modules

### `coffee_maker.py`
Manages the coffee machine's resources. It checks if there are enough ingredients for the selected drink and deducts resources when a drink is made.

### `main.py`
Acts as the main driver of the application. It continuously prompts the user for their choice and coordinates the interaction between the coffee maker, menu, and payment systems.

### `menu.py`
Contains the `Menu` and `MenuItem` classes, which define the available drinks and their required ingredients.

### `money_machine.py`
Handles the coin processing and payment system. It calculates the total amount of coins entered and checks if the payment is sufficient for the chosen drink.

## License
This project is created for educational purpose.
