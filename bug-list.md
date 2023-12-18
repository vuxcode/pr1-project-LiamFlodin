# Bug List
Bug in random word selection:
I tried to make the game pick a random word, but sometimes it was picking weird numbers, like 3.75, instead of just a whole number.

Why it happened:
When I wanted the computer to choose a random word, I used a math thing (Math.random() * words.length), but this sometimes gave me a number with a dot (3.75 for example). For the game to find the word, it had a whole number.

How i fixed it:
I figured out that I needed to make sure the number is always a whole number. So, I added another math function called Math.floor() to round down the number to the nearest whole number. That way, I made sure the game always picked a proper word from the list.

Input validation bug:
The game didn't always stop invalid letters and allowed more than one letter.

Why it happened:
I didn't consider uppercase letters, and I allowed more than one letter.

How i fixed It:
I made restrictions to only allow downcase and a single letter.

Winning alert repeatedly shown bug:
The winning message kept showing even after the game was over.

Why it happened:
I didn't stop the game from showing the winning message multiple times.

How i fixed it:
I added a condition to check if the game was still going before showing the winning message.

Lose message if you guessed the word on the last try bug

Why it happened:
The losing message didn't consider when the player guessed the word.

How i fixed it:
I made sure to show the losing message only if the word wasn't guessed.
