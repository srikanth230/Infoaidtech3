import random

def roll_dice():
    num_dice = int(input("Enter the number of dice to roll: "))
    while num_dice < 1:
        print("Please enter a valid number of dice (1 or more).")
        num_dice = int(input("Enter the number of dice to roll: "))

    rolls = []
    for _ in range(num_dice):
        roll = random.randint(1, 6)
        rolls.append(roll)

    print("Dice rolls:", rolls)

    roll_again = input("Do you want to roll the dice again? (y/n): ")
    while roll_again.lower() not in ['y', 'n']:
        print("Please enter 'y' to roll again or 'n' to quit.")
        roll_again = input("Do you want to roll the dice again? (y/n): ")

    if roll_again.lower() == 'y':
        roll_dice()

roll_dice()
