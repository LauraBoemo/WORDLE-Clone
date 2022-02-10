# Functional Requirements

## Gameplay

6 tries to guess a 5-letter word
Typing in the letter will display the letter in the tile
Backspace will delete letters
Enter will submit guess
    - Dark gray means the letter is not in the word ("Absent")
    - Yellow means it is in the word but not in the right position ("Present")
    - Green means it is in the word and in the right positio ("Correct")
Guesses must be a real word, "in word list"
Hard Mode: present or correct letters must be used in subsequent guesses 
Guesses are saved in local storage

## Design

Tiles  5x6
Virtual Keyboard

## Interactions 

When typing a letter:
    - The border of the tile changes to light gray
    - Blinking in animation with letter
    - Backspace will remove letter, border changes to gray

When submitting a guess:
    - Tiles will flip up and the background color will change based on guess