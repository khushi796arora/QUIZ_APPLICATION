# Quiz Application

A simple and interactive Quiz Application built using Python. This application allows users to answer multiple-choice questions, follow quiz rules, and view their final score at the end of the quiz.

## Features

- Multiple-choice questions
- Score calculation and display
- User-friendly command-line interface
- Question and answer management through a separate file
- Quiz rules displayed before starting
- Easy to customize and extend

## Project Structure

```
quiz-application/
│
├── quiz.py          # Main application file
├── qa.py            # Questions and answers data
├── rules.py         # Quiz rules and instructions
├── score.py         # Score calculation and result display
└── README.md        # Project documentation
```

## How It Works

1. The application displays quiz rules.
2. Questions are loaded from the question-answer file.
3. Users answer each question.
4. The application evaluates responses.
5. Final score is displayed at the end.

## Technologies Used

- Python 3
- Object-Oriented Programming (if applicable)
- Command Line Interface (CLI)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/quiz-application.git
```

2. Navigate to the project directory:

```bash
cd quiz-application
```

3. Run the application:

```bash
python quiz.py
```

## Example Output

```
Welcome to the Quiz Application

Rules:
1. Each question carries 1 mark.
2. No negative marking.
3. Enter the correct option number.

Question 1:
What is the capital of India?

1. Mumbai
2. Delhi
3. Kolkata
4. Chennai

Your Answer: 2

Correct!

Final Score: 8/10
```

## Future Enhancements

- Timer-based quiz
- Difficulty levels
- Category-wise quizzes
- GUI version using Tkinter
- Database integration
- Leaderboard system

## Learning Outcomes

This project helped in understanding:

- Python programming fundamentals
- Functions and modules
- File organization
- User input handling
- Score management logic

## Author

Khushi Arora

---

⭐ If you found this project useful, consider giving it a star.
