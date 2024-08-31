# Hindi Flash Card App

This project is a flashcard application built using Python's Tkinter library, designed to help users learn Hindi. The app displays Hindi words and their English meanings, allowing users to practice and memorize vocabulary.

## Overview

The Hindi Flash Card App is an educational tool that helps users learn Hindi words by displaying flashcards. Each card shows a Hindi word for 3000 milliseconds, after which it flips to reveal the English meaning. If the user correctly guesses the meaning, the word is removed from the deck, preventing it from being shown again.

## Features

- **Graphical User Interface (GUI):** Built using Tkinter, the application provides an intuitive interface for learning Hindi words.
- **Timed Card Flipping:** The flashcard automatically flips from Hindi to English after 3000 milliseconds.
- **Progress Tracking:** Correctly guessed words are removed from the deck, helping users focus on words they need to learn.
- **Customizable Word List:** The app uses a CSV file (`hindi_words.csv`) that can be easily modified to add or remove words.

## Installation

To run this application, you'll need Python installed on your system. Tkinter is included with Python, so no additional installation is required.

## Usage

1. Clone this repository or download the files.
2. Run the main Python file to start the application.

```bash
python main.py
```

## Files Description

- **main.py:** The main file containing the logic for the flashcard app, including the Tkinter GUI setup, card flipping mechanism, and progress tracking.
- **data/hindi_words.csv:** The CSV file containing Hindi words and their corresponding English meanings.
- **image folder:** Contains design elements for the flashcards.

## How It Works

1. **Display Hindi Word:** The app displays a word from the `hindi_words.csv` file.
2. **Timed Flip:** After 3000 milliseconds, the flashcard flips to reveal the English meaning.
3. **Correct Guess:** If the user guesses the word correctly, it is removed from the deck.
4. **Next Word:** The user can then move on to the next word in the list.
