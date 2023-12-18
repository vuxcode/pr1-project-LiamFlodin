
# Project Summary

I have coded a game called Hangman that you can play on a website. In this game, you try to guess a word by suggesting letters. The code is written in JavaScript and works together with HTML.
When you open the game, it shows you how many attempts you have left and displays the word you're trying to guess with underscores for each letter. You can input a letter in a box and click a button to make a guess.
The computer picks a random word from a list, and you need to figure out what it is. If you guess a correct letter, the underscores get replaced with that letter in the right positions. If you guess the whole word correctly, you win, and it tells you the word. On the other hand, if you run out of attempts (six in total), it tells you the correct word, and you lose.
The code checks if what you entered is a valid letter and gives you a warning if it's not. It keeps track of your progress and updates the display after each guess.
So, it's a simple game where you try to guess a word by suggesting letters. The code handles the game's logic, like checking your guesses, keeping track of attempts, and letting you know if you won or lost. It provides a basic setup for a Hangman game that can be improved or customized further.

Reflecting on the project i can say that i overestimated myself and my abilities to code. It was much harder than i anticipated just to get the basic logic of a hangman game. But i do think the assignment was very  rewarding. Going from planing stage and making a plan to breaking everything up into smaller parts helped alot. Unfourtunatly i got really sick for a couple of weeks and couldn't make the time budget. But if i could o it all again i would have started with the code much earlier instead of doing reasearch and going through old notes. There are quite a few improvements i would have made if i had more time. First of i would have implemented some kind of UI to show the user what letters have already been guessed. Then i would have liked to make an actual hangman displayed on the screen where you can track the progress instead of just having a div saying how many attemts you have left. These are the biggest improvements i would have made. After that i would have made the game look nicer and maybe even done some CSS.

# User Guide

Here's a list on how to play my hangman game coded in javascript and HTML!

Objective:
Guess the hidden word by suggesting letters. You have a limited number of attempts before the game ends.

How to Play:

You'll see the number of remaining attempts and underscores representing the letters of the hidden word.


1. Locate the "Enter a letter:" text box.
2. Type a single letter (a-z) into the box.
3. Click the "Guess" button after entering a letter.

If your guessed letter is in the word, the underscores will be replaced with the correct letter in the right positions.
If your guess is incorrect, the remaining attempts will decrease.

Continue guessing letters until you either correctly guess the entire word or run out of attempts.
If you correctly guess the word, a congratulations message will pop up

If you run out of attempts (maximum 6), a message will reveal the correct word, and you'll lose the game.

Make sure you only enter only a single letter (a-z) when making a guess.

The display will be updated after each guess, showing the remaining attempts and the current state of the word.

To play again, you need to refresh the webpage. Good luck :)
