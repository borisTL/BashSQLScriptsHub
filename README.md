
# [Periodic Table Lookup](https://github.com/borisTL/BashSQLScriptsHub/tree/main/Periodic-Table-Database%20)

This Bash script retrieves information about elements from a PostgreSQL database. The user can input an atomic number, element name, or symbol, and the script will return details such as atomic mass, type, melting point, and boiling point.

 Features
- **Input Options**: Search by atomic number, name, or symbol.
- **Detailed Element Info**: Returns atomic mass, type, melting point, and boiling point.
- **Error Handling**: Displays errors for invalid inputs or missing elements.

---
# [Number Guessing Game](https://github.com/borisTL/Number-Guessing-Game)


This project is a command-line number guessing game implemented in Bash, with PostgreSQL used to store player information and game statistics. Players guess a random number between 1 and 1000, and their game history is saved to the database, including the number of games played and their best result.

## Features
- **User Management**: 
  - New users are welcomed, and their information is saved in the database.
  - Returning users are greeted with their game history, including the number of games played and their best score (fewest guesses).
  
- **Game Play**:
  - The game generates a random number between 1 and 1000.
  - Players continue guessing until they guess the correct number.
  - Feedback is provided after each guess, indicating whether the guess was too high or too low.

- **Database Interaction**:
  - Player data (username, games played, best game) is stored in a PostgreSQL database.
  - The game updates the number of games played and the best game (if the current game was completed with fewer guesses than the previous best).
 ---
