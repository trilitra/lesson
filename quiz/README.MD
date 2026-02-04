# Country Quiz (Go)

A simple command-line quiz game written in Go.  
The player is asked to enter the capital city for a given country, and the program counts how many answers are correct.

## Features
- Loads quiz questions from a separate package
- Shuffles questions before the game starts
- Case-insensitive answer checking
- Displays the final score at the end

## How it works
- The game asks the user for the capital of each country
- User input is read from the terminal
- Each correct answer increases the score by one

## How to run
```bash
go run main.go
