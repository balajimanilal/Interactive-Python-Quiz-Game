# Interactive-Python-Quiz-Game
# Project Overview
The Python Quiz Game presents a series of questions to the player in a True/False format. The questions are drawn from a predefined set of data, and the player's answers are validated against the correct answers. At the end of the quiz, the player receives a final score.

# File Structure
- **data.py:** Contains the list of questions with their respective correct answers and categories.
- **question_model.py:** Defines the Question class to represent individual questions.
- **quiz_brain.py:** Contains the QuizBrain class, which manages the quiz flow, including presenting questions and validating answers.
- **main.py:** The main entry point of the application, which sets up the quiz and runs it.

# File Breakdown
- **data.py:** This file stores the question data as a list of dictionaries. Each question includes the text, correct answer, and difficulty.
- **question_model.py:** This file defines the Question class, representing a quiz question with text and an answer.
- **quiz_brain.py:** This file handles the quiz logic. It tracks the current question number, checks answers, and keeps score.
- **main.py:** The entry point for running the quiz. It initializes the quiz by converting the question data into Question objects and runs the game loop.

> # Features
> - A set of multiple True/False questions on computer science.
> - Score tracking and feedback on correct/incorrect answers.
> - Simple command-line interface.
> - Questions are drawn dynamically from a data set.
