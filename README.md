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










CONTACT BOOK:
The provided code is a simple Tkinter-based Python script for a contact book application. This application provides a graphical user interface (GUI) for users to interact with their contacts. Here's a breakdown of the key components and functionalities:

Main Window (root):

The main application window is created using Tkinter (tk.Tk()).
The window is titled "Contact Book" and has dimensions set to 300x300 pixels.
It is configured with a light grey background.
Data Entry Widgets:

Entry widgets for entering contact information, including name and number, are provided.
Labels for "Name" and "Number" are included above the respective entry widgets.
Buttons:

"Add Contact": Calls the add_contact function to add a new contact to the contact list.
"Delete Contact": Calls the delete_contact function to remove the selected contact from the contact list.
"Edit Contact": Calls the edit_contact function to modify the details of the selected contact.
Listbox (contact_list):

A Listbox widget is included to display the list of contacts.
Contacts are shown in the format "Name: Number."
Functions:

add_contact: Retrieves name and number, adds a new contact entry to the contact_list, and clears the entry fields.
delete_contact: Removes the selected contact from the contact_list.
edit_contact: Opens a new window for editing the selected contact's details, updates the contact in the contact_list upon saving.
Edit Window (edit_window):

A separate window is created for editing contacts.
It includes entry widgets for modifying the name and number of the selected contact.
A "Save" button is provided to save the changes and close the edit window.
The code follows a clean structure, separating UI components, functions, and event handling. It provides a basic but functional contact book with the ability to add, delete, and edit contacts through a user-friendly interface.






