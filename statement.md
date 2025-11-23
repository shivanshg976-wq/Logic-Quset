Problem Definition: LogicQuest

1. Problem Statement

In computer science education, understanding search algorithms—specifically the "Divide and Conquer" approach—is fundamental. However, students often find theoretical explanations dry and difficult to visualize. LogicQuest bridges this gap by offering a graphical, interactive simulation. It transforms the abstract concept of Binary Search into an engaging challenge, requiring users to apply logical elimination strategies to solve problems efficiently under constraint.

2. Project Scope

The project delivers a standalone desktop application built on Python's Tkinter framework.

In-Scope Functionality:

Algorithmic Engine: A backend module that generates randomized targets and validates user logic.

Graphical Dashboard: A user-centric interface for input and real-time status feedback.

State Persistence: A file-based system (statistics.py) to record and retrieve user performance metrics across sessions.

Validation Layer: A robust error-handling mechanism to filter invalid inputs (strings, empty values).

Out-of-Scope:

Cloud synchronization of scores.

Mobile device support (Android/iOS).

Artificial Intelligence opponents.

3. Target Audience

CS Fundamentals Students: To visualize the efficiency of binary search versus linear search.

Brain Training Users: Individuals seeking daily cognitive exercises in deductive reasoning.

Programming Beginners: To study the implementation of modular Python architecture.

4. Key Features

Constraint-Based Gameplay: Users are limited to a specific number of attempts, forcing optimized decision-making.

Session Persistence: High scores are serialized to a local text file, preserving data integrity between application restarts.

Dynamic Visual Cues: The interface updates labels and colors dynamically based on the accuracy of the user's input (High/Low logic).