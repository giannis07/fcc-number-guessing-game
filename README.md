# 🎯 Number Guessing Game

This is my solution for the [Number Guessing Game project on freeCodeCamp](https://www.freecodecamp.org/learn/relational-database/build-a-number-guessing-game-project/build-a-number-guessing-game).

## 📌 Overview

A simple terminal-based number guessing game built with Bash and PostgreSQL. The game picks a random number between 1 and 1000, and the user must guess it. The app stores each user's number of games played and their best score (least number of guesses).

## 🧠 How It Works

- The script generates a random number.
- Prompts the user to guess until they find the correct number.
- Keeps track of each guess.
- Stores username, games played, and best score in PostgreSQL.

## 🗃️ Technologies Used

- Bash  
- PostgreSQL

## 🛠️ Getting Started

1. Make sure PostgreSQL is installed and running.  
2. Clone the repository:  
   git clone https://github.com/giannis07/fcc-number-guessing-game.git  
   cd fcc-number-guessing-game  
3. Run the script:  
   ./number_guess.sh

## 💾 Database

The script creates and uses a PostgreSQL database called `number_guess`, with a `users` table to store player statistics.

## 💻 GitHub Repository

https://github.com/giannis07/fcc-number-guessing-game
