
# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Students will implement the classic Hangman word‑guessing game to reinforce Python concepts such as strings, loops, conditionals, and using the random module.

## 📝 Tasks

### 🛠️ Hangman Game Implementation

#### Description
Write a Python program that implements the Hangman word‑guessing game. The program should randomly select a word from a list and allow the player to guess letters one at a time until they either discover the word or run out of attempts.

#### Requirements
Completed program should:

- Maintain a predefined list of words and choose one at random when the game starts.
- Prompt the player to guess a single letter using `input()` each turn.
- Display the current progress with underscores for unguessed letters (e.g. `_ a _ g _ a _`).
- Track and display the number of remaining incorrect guesses (start with a fixed number such as 6).
- Prevent repeated guesses from deducting additional attempts.
- End with a clear win message when the word is fully revealed or a lose message when attempts reach zero.

#### Example interaction

```
Word: _ _ _ _ _
Guess a letter: a
Good guess! _ a _ _ _
Guess a letter: e
Sorry, 'e' is not in the word. Attempts remaining: 5
...
```

> 💡 Once the basic requirements are met, feel free to extend the word list or add extra features (e.g. hints, score tracking, graphical display).
