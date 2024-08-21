# Quiz Game Python Project

Welcome to the Quiz Game Python Project! This project is a fun and interactive quiz game built using Python. The game fetches trivia questions from the [Open Trivia Database](https://opentdb.com/api.php) and provides a graphical user interface (GUI) using Tkinter. 

## Project Overview

This project demonstrates how to build a quiz game with a modular codebase and a user-friendly interface. The core functionalities are divided across multiple files to keep the code organized and maintainable.

## Features

- Fetch trivia questions from the Open Trivia Database API.
- Interactive GUI built with Tkinter.
- Modular code with different files handling various functionalities.

## Getting Started

### Prerequisites

Make sure you have Python 3.x installed on your machine. You will also need the following Python packages:

- `requests` (for making HTTP requests)
- `tkinter` (for the GUI, which is included in the standard library for Python)

You can install the required packages using pip:

```bash
pip install requests
```

## Clone the Repository

To get started, clone the repository to your local machine:

```bash
git clone https://github.com/AyushKanyal-me/Quiz-Game-PythonProject.git
cd Quiz-Game-PythonProject
```

## Project Structure

Project Structure

- `main.py`: The main script to run the quiz game.
- `data.py`: Contains functions to interact with the Open Trivia Database API.
- `ui.py`:  Manages the Tkinter GUI elements and layout.
- `quiz_brain.py` and `question_model.py`: Implements the core logic of the quiz game, including question handling and scoring.


## Running the Game

To start the quiz game, run the `main.py` file. You can execute it from the command line:
```bash
python main.py
```
This will launch the Tkinter GUI, allowing you to start playing the quiz game.

## How It Works

1. **Fetching Questions**: 
   - The game retrieves trivia questions from the Open Trivia Database API using functions defined in `data.py`.
   - The API provides various categories and difficulty levels of questions which are parsed and formatted for the game.

2. **Game Logic**: 
   - The core game mechanics, including question handling, scorekeeping, and game progression, are implemented in `quiz_brain.py` and `question_model.py`.
   - This module manages the flow of the game, processes user answers, and updates the score based on correctness.

3. **User Interface**: 
   - The graphical user interface (GUI) is created and managed by `ui.py` using Tkinter.
   - It includes elements such as question displays, answer choices, and score tracking. The GUI updates dynamically based on user interactions and game state.

4. **Main Execution**: 
   - `main.py` serves as the entry point for the application.
   - It initializes the game, sets up the GUI, and integrates the different components of the project (API interaction, game logic, and GUI).

Each component communicates with the others to create a seamless and interactive quiz experience.


## Contributing
Contributions to this project are welcome! If you have any suggestions or improvements, please feel free to open an issue or submit a pull request.

## Contact
If you have any questions or feedback, you can reach out to me via GitHub: AyushKanyal-me.
