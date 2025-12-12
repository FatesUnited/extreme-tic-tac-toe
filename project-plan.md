# Extreme Tic Tac Toe Project Plan

## User Stories

- As a player, I want an option to see instructions on how to play at all times
- As a player, I want an option to play against the computer
- As a player, I want an option to play against another player
- As a player, I want to click into the relevant squares to make my move
- As a player, I want to see my available options to click my move
- As a player, I want to clearly understand who won a square
- As a player, I want to see who won the game (including ties)
- As a player, I want the option to rematch 
- As a player, I want the option to return to the main screen
---
- Advanced: As a player, I want an undo move in case I misclick. Give me a a limited pool of undos (1 or 2)
- Advanced: As a player, I want to choose who goes first
- Advanced: As a player, I want the option to randomly choose who goes first
- Advanced: As a player, I want score tracked over numerous games
---
- SUPER Advanced: As a player, I want to enter a number to determine the size of my tic tac toe board

## Pseudocode (base functionality)

### Define constants & variables

- Array of winnning combos for a standard tic tac toe game
- Main board array
- Sub-board arrays

### Define app's state variables
- currentTurn
- winner state (for each game?)
- tie state (for each game?)
- Instructions pop-up (manipulate display: none; in CSS to overlay on the screen)
- Overall score

### Cache elements

- Board elements
- Square elements
- Message element
- Button elements

### Event Listeners

- Buttons
- Squares

### Functions 

- Init()
- render()
- updateBoard()
- updateMessage()
- handleClicks()
- placePiece()
- switchTurns()
- checkWinner()
- checkTie()
- reset()
- setTurnOrder()
- instructions()