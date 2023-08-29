# Project-Moringa
This is my Moringa Project on Dosage Management Task.
Its my way of managing medication intake task by creating timelines and options of adding and removing.
Initialization: The script begins with an empty list dosage_times, which will record information about the dosage times and whether or not they were received.

Display Options Function: The display_options() function returns a list of available actions/options from which the user can select.

Add Dosage Time Function: The add_dosage_time() function allows the user to enter a dosage time, which is appended to the dosage_times list with a "completed" value of False by default.

The mark_dosage_received() function provides a numbered list of dosage periods and their completion status. It prompts the user to select a dosage to mark as received, and if the input is genuine, the dosage's "completed" state is set to True.

Dosage Schedule list_dosage_times() returns a list of all the dosage times in dosage_times, along with their completion status (received or not received).

Remove Dosage Time Function: The remove_dosage_time() function displays a list of dosage times and prompts the user to select one to remove. If the entry is correct, the dosage specified is deleted from dosage_times.

The main() function is the heart of the programme. It displays the introductory line, then enters a loop to offer options and gather user input periodically, before calling the relevant routines based on the user's selection.

Start the programme: If the script is being run directly, the if __name__ == "__main__": block checks to see if the script is being run directly, and if so, it calls the main() method to start the programme.

