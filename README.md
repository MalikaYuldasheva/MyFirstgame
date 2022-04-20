# MyFirstgame
RockPaperScissor
import random

variations = ["rock", "paper", "scissors"]

player = int(input("type your variations"))

computer = random.randrange(0, 2)

ROCK = 0
PAPER = 1
SCISSORS = 2

if player == computer:
    print('DRAW')

if player == PAPER and computer == SCISSORS:
    print('YOU LOOSE AGAINST COMPUTER: SCISSORS')

elif player == SCISSORS and computer == ROCK:
    print('YOU LOOSE AGAINST COMPUTER: ROCK')

elif player == ROCK and computer == PAPER:
    print('YOU LOOSE AGAINST COMPUTER: PAPER')
else:
    print('YOU WON AGAINST COMPUTER: ' + variations[computer])
