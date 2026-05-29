import random

choices = ["rock", "paper", "scissors"]

print("=== Rock Paper Scissors Game ===")

user = input("Enter rock, paper, or scissors: ").lower()

if user not in choices:
    print("Invalid input!")
else:
    computer = random.choice(choices)

    print("You chose:", user)
    print("Computer chose:", computer)

    if user == computer:
        print("It's a Tie!")

    elif user == "rock" and computer == "scissors":
        print("You Win!")

    elif user == "paper" and computer == "rock":
        print("You Win!")

    elif user == "scissors" and computer == "paper":
        print("You Win!")

    else:
        print("Computer Wins!")
