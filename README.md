# Forage of Phrases (FoP)

A Wordle-inspired word guessing game, built in Python and tested in **Google Colab** for a class project. Instead of guessing single letters, you guess **whole words** to reveal a hidden phrase or sentence.

## How to Play

1. The game starts with a secret phrase, fully hidden (letters shown as underscores).
2. On each turn, guess a word.
   - If the word appears in the secret phrase, its letters are revealed.
   - If it doesn't, you still find out which of its individual letters exist somewhere in the phrase.
3. A color-coded on-screen keyboard tracks your guessed letters:
   - 🟩 Green = letter is in the phrase
   - ⬛ Gray = letter is not in the phrase
4. You have **15 attempts** to fully reveal the phrase.
5. Win by uncovering every letter before you run out of attempts!

## Notes
- Currently only handles `.` as end-of-sentence punctuation.
- This repo contains the core game logic (feedback generation, letter tracking, word tokenization, terminal/keyboard display) that is my contribution to the assignment. The word-list/validation component was built by the project partner and is intentionally excluded here, so the game is not currently runnable for now. I'm sharing this to showcase the logic I built; a working version would need a `word_list` (or similar validation source) supplied.

