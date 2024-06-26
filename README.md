# Colored-Square-
The main function:

Seeds the random number generator with the current time using srand(time(0)).
Generates a random target color using generateRandomColor.
Enters an infinite loop where the user is prompted to guess the color of the square.
The user's input is converted to lowercase using a for loop.
The input is validated against the possible color strings (e.g., "red", "green", etc.). If valid, the corresponding Color enum value is assigned to userColor.
If the user's guess matches the target color, the program congratulates the user and exits the loop. Otherwise, it prompts the user to try again.
If the input is invalid, the program displays an error message.

