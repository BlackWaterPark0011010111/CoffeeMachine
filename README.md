# CoffeeMachine


This is a simulation of a coffee machine using Python. The application allows users to select various
types of coffee, tracks the resources required to make each type, and alerts users when resources need to be replenished.

The Coffee Machine application lets users simulate the operation of a coffee machine. It supports creating, 
editing, and deleting coffee recipes. It includes user authentication and an admin panel for managing content.


Follow the on-screen instructions to select coffee options, view the report, or turn off the machine.

## Main Structure

- `coffee.py`: Main script to run the coffee machine simulation.
- `README.md`: This readme file.


You can set the following environment variables to configure the coffee machine:

- `WATER`: Initial amount of water (in ml).
- `MILK`: Initial amount of milk (in ml).
- `COFFEE_BEANS`: Initial amount of coffee beans (in grams).
- `MONEY`: Initial amount of money (in dollars).

Create a `.env` file in the root directory and add the following content:

```plaintext
WATER=1000
MILK=500
COFFEE_BEANS=200
MONEY=0
