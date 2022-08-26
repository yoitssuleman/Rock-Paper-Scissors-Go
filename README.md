# Rock-Paper-Scissors-Go
A simple Rock, Paper, Scissor game made in Python using loops!
````python
#Ask user for rock paper scissor input
import random
print("HELLO WELCOME TO A GAME OF ROCK PAPER SCISSOR!")
x = input("CHOOSE ROCK PAPER OR SCISSOR: ").title()
win_1 =  print(x)
#generate a random response
game = "Rock","Paper","Scissor"
y = random.choice(game)
print (y)
#win conditions and print result 
if x == "Rock":
    "Rock" > "Scissor"
    "Rock" < "Paper"
    "Rock" == "Rock"
    if x > y:
        print("You Win! Good Job :)")
    elif x == y:
        print("We Tied! Try agin :(")
    elif x < y:
        print("I lose! Good Job :)")
elif x == "Scissor":
    "Scissor" > "Rock"
    "Scissor" < "Paper"
    "Scissor" == "Scissor"
    if x > y:
        print("You Win! Good Job :)")
    elif x == y:
         print("We Tied! Try agin :(")
    elif x < y:
         print("I lose! Good Job :)")
elif x == "Paper":
    "Paper" > "Rock"
    "Paper" < "Scissor"
    "Paper" == "Paper"
    if x > y:
        print("You Win! Good Job :)")
    elif x == y:
        print("We Tied! Try agin :(")
    elif x < y:
        print("I lose! Good Job :)")
else:
    print("Sorry! I could not understand you :(")
    

    
````
