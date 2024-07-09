# PRODIGY_SD_02

Build a program that generates a random number and challenges the user to guess it. The program should prompt the user to input their guess, compare it to the generated number, and provide feedback if the guess is too high or too Iow. It should continue until the user correctly guesses the number and then display the number of attempts it took to win the game.

explanation : Importing the random module

The first line import random imports the random module, which provides functionality for generating random numbers.

Defining the guess_the_number function

The guess_the_number function is defined to contain the game logic. This function will be called when the program is run.

Generating a random number

The line secret_number = random.randint(1, 100) generates a random integer between 1 and 100 (inclusive) using the randint function from the random module. This number will be the secret number that the user needs to guess.

Initializing the attempts variable

The line attempts = 0 initializes a variable attempts to keep track of the number of attempts the user makes to guess the secret number.

The game loop

The while True loop will continue to run indefinitely until the user correctly guesses the secret number.
