---
layout: page
title: Number Guessing Game
description: Simple number guessing game using the Command Line Interface
img: assets/img/numbers.jpg
importance: 8
category: work
related_publications: false
---

# Number Guessing Game

Simple guessing game using the Command Line interface. Players can select the difficulty that they want and play! The time it took to guess the number and the number of attempts are displayed when you finish.

# Features:

- Various difficulties
- Multiple rounds
- Hint system if guess is within 5 numerical values of the answer
- Records how long the game took
- Records the number of attempts

# Sample Output

```
Welcome to the Number Guessing Game!
I'm thinking of a number between 1 and 100.
You have multiple chances to guess the correct number.

Please select the difficulty level:
1. Easy (10 chances) Max Score: 0
2. Medium (5 chances) Max Score: 0
3. Hard (3 chances) Max Score: 0

Enter a number: 1
Great! You have selected the Easy difficulty level.
Enter your guess: 50
Incorrect! The number is less than 50.
Enter your guess: 25
Incorrect! The answer is greater than 25.
Enter your guess: 37
Incorrect! The answer is greater than 37.
Enter your guess: 43
You're close!
Incorrect! The number is less than 43.
Enter your guess: 40
You're close!
Incorrect! The answer is greater than 40.
Enter your guess: 41
You're close!
Incorrect! The answer is greater than 41.
Enter your guess: 42
You're close!
Congratulations! You guessed the correct number in 7 attempts
It took you 39.325 seconds
Play again? y/n
```
