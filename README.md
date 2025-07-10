🗺️ U.S. State Game

An interactive game built with Python and the Turtle graphics module that helps users learn the names and locations of all 50 U.S. states.


📌 About the Project

This project is inspired by educational games that challenge players to recall and locate all 50 states on a blank U.S. map. Users are prompted to type in the name of a U.S. state, and if correct, the state name appears at the appropriate location on the map.

If a user types "Exit", the game ends, and a states_to_learn.csv file is generated containing the states the user did not guess—allowing for further study.


🎮 How to Play

* Run the main.py file.

* A blank U.S. map will appear.

* Enter the name of a state in the prompt that appears.

* If correct, the state will be labeled on the map.

* The game continues until all 50 states are guessed or the user exits by typing "Exit".


🧠 Features

* Interactive map using Turtle graphics.

* CSV file output (states_to_learn.csv) with missed states.

* Keeps track of correct guesses in real-time.

* Clean UI using a .gif image of a blank U.S. map.


📁 Files Included

* main.py: The main script to run the game.

* 50_states.csv: Contains state names along with their x and y coordinates for map placement.

* blank_states_img.gif: Image of a blank U.S. map used as the game's background.

* states_to_learn.csv: (Generated during gameplay) List of states the user missed.


🛠️ Requirements

* Python 3.x

* pandas

* turtle (comes with standard Python)


Install required package:

pip install pandas


📷 Screenshot

![Screenshot 2025-07-10 at 9 38 37 AM](https://github.com/user-attachments/assets/1a96d424-caf9-4a20-a360-665e0c3386da)


🚀 How to Run

python main.py

Make sure all files (main.py, 50_states.csv, blank_states_img.gif) are in the same directory.


💡 Future Improvements

* Add a timer or score system.

* Add hints or multiple-choice mode.

* Include territories or regions.

* Add sound effects for correct/incorrect answers.
