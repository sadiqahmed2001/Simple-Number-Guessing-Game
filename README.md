# Simple-Number-Guessing-Game
This code creates a rudimentary number guessing game, in which the player attempts to guess a randomly generated target number.
Import statement (commented out): 
import random. This line is commented out. It implies that the random module will be used to generate a random number, although it is not in the present version of the code.

To generate a random target number:
 target=random.randint(1,100) This line (commented out) would produce a random integer from 1 to 100 (inclusive) and put it in the variable target. However, it is commented out in the current version of the code.

Game Logic Within a While Loop:

The code enters an endless while loop by using while True:.
Inside the loop, the player is encouraged to guess the goal number or type 00 to exit the game.

If the user types 00, the game outputs "user wants to quit the game" and exits the loop using the break statement.
If the user's estimate equals the target number (userchoice == target), the game displays "successful: your guess is correct!!!" and exits the loop.
If the user's guess is less than the goal number (userchoice < target), the game will display "your number is too small." Make a greater guess...".
If the user's guess exceeds the target number (userchoice > target), the game prints."your number is too big, take a smaller number" .
The cycle repeats until the player correctly guesses the number or chooses to exit the game.

Game Over Message:

After the loop ends, regardless of whether the user guessed the correct number or exited the game, the code writes "----GAME OVER---".

conclusion:-
Overall, this code creates a simple number guessing game in which the player attempts to predict a randomly generated target number. The game runs until the user correctly guesses the number or enters 00 to exit.

# THE CODE:-

# import random

# target=random.randint(1,100)

# while True:  
#     userchoice=int(input("guess the target or quite(00): "))
#     if (userchoice==00):
#         print("user want to quite the game")
#         break
# #    userchoice=int(userchoice)
#     if(userchoice==target):
#         print("successfull: your guess is corerct!!!")
#         break
#     elif(userchoice<target):
#         print("your number is too small. take a bigger guess...")
#     else:
#         print("your number is too big, take a smaller number: ")
   
# print("----GAME OVER---")

---------------------- THE END-----------------------------






