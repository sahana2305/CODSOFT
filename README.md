# CODSOFT
ROCK PAPER SCISSOR:
The provided code is an implementation of the Rock, Paper, Scissors game using Python's Tkinter library for creating a graphical user interface (GUI). Here's a detailed description of the code:

Game Logic:

The game logic is defined in the outcome_handler function. When a player clicks one of the buttons ("Rock," "Paper," or "Scissors"), this function is called. It randomly generates the computer's choice, compares it with the player's choice based on predefined rules, and updates the scores and outcome labels.
Data Structures:

The schema dictionary represents the possible outcomes of the game. It defines the relationships between different choices (rock, paper, scissors) and assigns a numerical value to each outcome.
Scores:

The scores are tracked using the variables comp_score (for the computer) and player_score (for the player).
Tkinter GUI:

The GUI is created using Tkinter, a standard GUI toolkit for Python.
Labels are used to display the game title, player and computer scores, player and computer choices, and the game outcome.
Buttons are provided for the player to make choices ("Rock," "Paper," "Scissors").
Button Actions:

Each button is associated with the outcome_handler function using lambda functions. Clicking a button triggers the corresponding game outcome.
Outcome Display:

Labels (player_choice_label, computer_choice_label, outcome_label) are updated dynamically to display the player and computer choices as well as the outcome of each round.
Main Loop:

master.mainloop() is the main event loop that keeps the GUI running. It listens for user inputs (button clicks) and updates the display accordingly.
Styling:

Font styles and colors are used to enhance the visual appeal of the GUI.
Scoring System:

The scoring system is based on the outcomes defined in the schema dictionary. Scores are updated based on whether the player wins, loses, or the round ends in a draw.
Overall, the code provides a user-friendly interface for playing the Rock, Paper, Scissors game against a computer opponent. The graphical elements and scoring system make the game interactive and enjoyable for the user

