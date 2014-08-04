This Guessing Game generates a random number between 1 and 100 and prompts the user to guess what it is. 

It has 4 variables:  
correct :  bool flag to signal a correct guess to end the while loop  

userGuess : the users guess, filled by a prompt  

pcNumber : the computers number, decided by Math.random()  

guesses : stores the number of guesses to reach the answer, initialized to 0  


It starts off with the prompt to initialize userGuess, it then runs through the while loop comparing userGuess with pcNumber until the correct number is input. Will respond with 'Too high'  or 'Too low' accordingly and will iterate guesses with every incorrect guess.

Should be able to guess the number within 8 guesses. Try and do it in fewer!
