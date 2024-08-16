<div>
  <img src="https://raw.githubusercontent.com/GeorgeTelles/georgetelles/f69531ec6b293b5148563588a764c010015d315e/logo_clara.png" alt="logo clara" width="300" style="display: inline-block; vertical-align: top; margin-right: 10px;">
  <img src="https://raw.githubusercontent.com/GeorgeTelles/georgetelles/f69531ec6b293b5148563588a764c010015d315e/logo_dark.png" alt="logo dark" width="300" style="display: inline-block; vertical-align: top;">
</div>

# Jogo da Pedra, Papel e Tesoura (Rock, Paper, Scissors Game)

This is a Python implementation of the classic game Pedra, Papel e Tesoura (Rock, Paper, Scissors). Players compete against the computer by selecting their move (rock, paper, or scissors), and the winner is determined based on the standard game rules.

## Functionality

The game offers the following features:

Random computer move: The computer randomly selects its move from the available options (rock, paper, scissors).
Player input validation: The code ensures that the player enters a valid move (0 for rock, 1 for paper, or 2 for scissors).
Win/loss/tie determination: The select_winner function accurately determines the winner based on the player's and computer's moves.
Score tracking: The game keeps track of the player's and computer's wins.
Replay option: Players can choose to play again after a round is complete.
Clear screen: The code clears the screen between rounds on Windows systems for a better user experience.
## Code Structure

The code is organized into well-defined functions:

main_print(): Displays the game title and current score.
select_move(): Randomly selects the computer's move.
get_player_move(): Validates the player's input and returns their chosen move.
select_winner(p_move, c_move): Determines the winner based on player and computer moves, updating the score accordingly.
## Gameplay Flow

Welcome message: The game greets the player with a title.
Game loop: The game continues as long as the player chooses to play again (indicated by the again variable).
Round loop:
The current score is displayed using main_print().
The player is prompted to choose a move using get_player_move().
The computer selects a move randomly using select_move().
The winner is determined and the score is updated using select_winner().
The player's and computer's moves, along with the winner for the round, are displayed.
The player is asked if they want to play again.
Game ends: If the player chooses not to play again, the game exits.
## Dependencies

The code imports the following modules:

random: Used for the computer's random move selection.
os: Used for clearing the screen (optional).
