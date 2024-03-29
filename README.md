import random

print("1. Rock\n2. Paper\n3. Scissors")

while True:
    computer_choice = random.randint(1, 3)
    player_choice = int(input("Enter your choice (1/2/3): "))

    print(f"Computer chose: {computer_choice}")

    player_win = False

    if player_choice == 1 and computer_choice == 2:
        player_win = False
        print("You chose rock and the computer chose paper.")
        print("You got covered by paper. You lost.")
    elif player_choice == 2 and computer_choice == 1:
        player_win = True
        print("You chose paper and the computer chose rock.")
        print("You covered the rock. You won!")
    elif player_choice == 2 and computer_choice == 3:
        player_win = False
        print("You chose paper and the computer chose scissors.")
        print("The computer cut you down. You lost.")
    elif player_choice == 3 and computer_choice == 2:
        player_win = True
        print("You chose scissors and the computer chose paper.")
        print("You tore down the computer. You won!")
    elif player_choice == 3 and computer_choice == 1:
        player_win = False  
        print("You chose scissors and the computer chose rock.")
        print("You got crushed by the rock. You lost.")
    elif player_choice == 1 and computer_choice == 3:
        player_win = True
        print("You chose rock and the computer chose scissors.")
        print("You smashed the computer. You won!")
        
SumanManna96/SumanManna96 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
