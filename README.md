# Hang_Man

The code for the Hangman game typically follows these steps:

1. **Word Selection:** A random word is chosen from a predefined list or file for the player to guess.
   
2. **Display Setup:** The word is represented by underscores (_), one for each letter, to show how many letters the word contains.

3. **User Input:** The player inputs letters one by one, trying to guess the word. The input is typically checked for validity (e.g., ensuring it's a single letter and hasn't been guessed already).

4. **Game Logic:** 
   - If the letter is correct, the corresponding blanks are replaced with the guessed letter.
   - If the guess is incorrect, the number of remaining attempts decreases, and a part of the hangman figure is drawn.

5. **Winning/Losing Conditions:** 
   - The player wins if they correctly guess all the letters before running out of attempts.
   - The player loses if they use up all their attempts before guessing the word, and the full hangman figure is drawn.

6. **Feedback:** After each guess, the game provides feedback by showing the updated word progress and remaining attempts. 

The game loop continues until the player wins or loses, providing a simple yet engaging experience with easy-to-understand logic and code structure.
