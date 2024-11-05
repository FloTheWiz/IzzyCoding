from random import randint # importing randint from random

my_random_number = randint(1,20) # generate a random number from 1 to 20

right_number = False  # whether or not user has guessed the number

while right_number is False:     # while they have not guessed the right number
    user_input = input ("Guess a number between 1 and 20: ")  # take the users guess as input

    if int(user_input) > my_random_number:      
        print ("Guess again! my number is lower than: " + user_input)  # print that they need to guess lower
    if int(user_input) < my_random_number:    
         print ("Guess again! my number is higher than: " + user_input) #print that they need to guess higher
    if int(user_input) == my_random_number:  
        right_number = True # user has guessed the right number


print("Congratulations, you guessed my number was " + str(my_random_number)) # print to tell user has guessed correctly
