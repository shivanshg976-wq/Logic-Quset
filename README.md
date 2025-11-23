LogicQuest: Algorithmic Training Tool

1. System Overview:-

LogicQuest is a modular Python application designed to simulate logical deduction scenarios. Unlike basic scripts, this project adopts a semi-professional software architecture, separating the User Interface (UI) from the Business Logic and Data Layers. It serves as a practical demonstration of event-driven programming, file I/O operations, and state management in Python.

2. Key Features:-

Modular Architecture: The codebase is split into specific modules (ui.py, game_logic.py, etc.) to ensure scalability and ease of maintenance.

Persistent Data Storage: A dedicated Data Controller (statistics.py) manages local file I/O to save high scores between sessions.

Real-Time Feedback Engine: The system provides dynamic visual cues (High/Low) based on the user's input analysis.

Robust Error Handling: Comprehensive validation prevents application crashes from invalid data types or empty inputs.

3. Tech Stack:-

Language: Python 3.10+

GUI Framework: Tkinter (Standard Python Library)

Design Pattern: Separation of Concerns (Logic vs. Presentation)

4. Installation & Execution Steps:-

Follow these steps to set up the project on your local machine:

Clone the Repository:

git clone https://github.com/shivanshg976-wq/Logic-Quset


Navigate to the Directory:

 LogicQuest


Run the Application:
Execute the entry point script to launch the GUI.

python main.py


5. Instructions for Testing:-

You can verify the system's reliability using these test cases:

Boundary Test: Enter a number outside the range (e.g., 0 or 51).

Expected Result: A warning message displays: "Bounds Error".

Data Type Test: Enter non-numeric text (e.g., "Hello").

Expected Result: A system error message displays: "Non-numeric input detected".

Persistence Test: Play until you win, then close the app and reopen it.

Expected Result: The "System Best" score at the top remains updated with your previous score.