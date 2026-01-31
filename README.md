Number Guessing Game

A simple Java console-based application where the user tries to guess a randomly generated number within a given range.

Description
This program generates a random number between 1 and 100 and prompts the user to guess it. After each guess, the program provides feedback indicating whether the guess is too high, too low, or correct. The game continues until the correct number is guessed.

Technologies Used
Java
java.util.Random
java.util.Scanner

How the Program Works
1. The program generates a random number between 1 and 100.
2. The user enters a guess through the console.
3. The program compares the guess with the generated number.
4. Feedback is displayed as:
   Too High!
   Too Low!
   Correct Guess!
5. The loop continues until the correct number is guessed.

How to Run the Program
Step 1: Compile the program
javac NumberGuessingGame.java

Step 2: Run the program
java NumberGuessingGame

Project Structure
NumberGuessingGame
|-- NumberGuessingGame.java
|-- README.md

Future Improvements
Add attempt counter
Add difficulty levels
Limit the number of guesses
Add replay option

Author
Yagna
