# Rock-Paper-Scissors-Go
A simple Rock, Paper, Scissor game made in Python using loops!
````python
import random
print("HELLO WELCOME TO A GAME OF ROCK PAPER SCISSOR!")
x = input("CHOOSE ROCK PAPER OR SCISSOR: ").title()
win_1 =  print(x)
#generate a random response
game = "Rock","Paper","Scissor"
y = random.choice(game)
print (y)

#win conditions and print result 
if x == "rock".title():
    "rock".title() > "scissor".title()
    "rock".title() < "paper".title()
    "rock".title() == "rock".title()
    if x > y:
        print("You Win! Good Job :)")
    elif x == y:
        print("We Tied! Try agin :(")
    elif x < y:
        print("I Win! Better Luck Next Time :)")
elif x == "scissor".title():
    "scissor".title() < "rock".title()
    "scissor".title() > "paper".title()
    "scissor".title() == "scissor".title()
    if x > y:
        print("You Win! Good Job :)")
    elif x == y:
         print("We Tied! Try agin :(")
    elif x < y:
         print("I Win! Better Luck Next Time :)")
elif x == "paper".title():
    "paper".title() < "rock".title()
    "paper".title() > "scissor".title()
    "paper".title() == "paper".title()
    if x < y:
        print("You Win! Good Job :)")
    elif x > y:
        print("I Win! Better Luck Next Time :)")
    elif x == y:
        print("We Tied! Try agin :(")
    
else:
    print("Sorry! I could not understand you :(")
    
    
````
