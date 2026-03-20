# Card Deck CLI Tool in Go

A command-line application built in Go to simulate card deck operations such as creation, shuffling, dealing, and persistence. This project focuses on clean design, modular code, and basic file handling.

---

## Features

- Create a new deck of cards
- Shuffle the deck
- Deal cards from the deck
- Save deck to a file
- Load deck from a file
- Modular and testable design

---

## Tech Stack

- Go (Golang)
- CLI (Command Line Interface)
- File I/O
- Unit Testing

---

## Getting Started

### Prerequisites
- Go installed (version 1.18 or above)

### Installation

Clone the repository:
git clone https://github.com/Tylerdurden2003/go-card-deck-cli.git
cd go-card-deck-cli

Run the program:
go run main.go

Project Structure:
.
├── main.go        # Entry point of the application
├── deck.go        # Core logic for deck operations
├── deck_test.go   # Unit tests
├── cards.txt      # Saved deck file (example)

Example Usage

Create a deck

Shuffle cards

Deal a hand

Save or load deck from file

What I Learned

Writing modular and maintainable Go code

Working with file I/O in Go

Designing simple CLI-based tools

Writing and running unit tests

Future Improvements

Add CLI flags for better interaction

Improve error handling

Add more test coverage

Extend to support multiple deck types

Author

Abhinav Gopal
GitHub: https://github.com/Tylerdurden2003
