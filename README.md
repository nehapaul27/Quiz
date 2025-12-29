
# python-quiz-game
PYTHON QUIZ GAME (Command-Line)

This is a simple command-line multiple-choice quiz game written in Python.
The user answers programming-related questions, and the program checks correctness and tracks the score.

--------------------------------------------------
FEATURES
--------------------------------------------------
- User is prompted with multiple-choice questions.
- Accepts answers as A, B, C, or D.
- Provides instant feedback (correct/incorrect).
- Tracks score and shows current score after each question.
- Displays final score and percentage at the end.

--------------------------------------------------
HOW THE GAME WORKS
--------------------------------------------------
1. The program loads questions and options from the database.
2. Each question is displayed with four options (A/B/C/D).
3. The user enters their choice.
4. The program checks if the answer is correct.
5. Feedback is displayed immediately:
   - Correct answer
   - Incorrect answer (correct answer shown)
6. Score is updated after each question.
7. At the end, total correct answers and percentage score are displayed.

--------------------------------------------------
REQUIREMENTS
--------------------------------------------------
- Python 3.x
- No external libraries needed

--------------------------------------------------
HOW TO RUN
--------------------------------------------------
1. Open terminal or command prompt.
2. Navigate to the project folder.
3. Run the program using:

   python quiz_game.py

4. Follow the on-screen instructions to play.

--------------------------------------------------
CUSTOMIZING QUESTIONS
--------------------------------------------------
Open `database.py` to add or edit questions:

```python
question_bank = [
    {"text": "Your question here", "answer": "A"}
]

options = [
    ["A.Option1", "B.Option2", "C.Option3", "D.Option4"]
]
