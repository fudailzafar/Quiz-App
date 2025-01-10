# Quiz App

A simple and interactive Quiz App built using ReactJS. The app presents users with multiple-choice questions and displays their score at the end of the quiz.

## Features
- Multiple choice questions with four possible answers.
- Displays correct and incorrect answers.
- Calculates and displays the total score at the end of the quiz.
- Option to restart the quiz after completion.

## File Structure

```bash
└── Quiz-App/
    ├── README.md
    ├── eslint.config.js
    ├── index.html
    ├── package.json
    ├── vite.config.js
    └── src/
        ├── App.css
        ├── App.jsx
        ├── index.css
        ├── main.jsx
        ├── Components/
        │   └── Quiz/
        │       ├── Quiz.css
        │       └── Quiz.jsx
        └── assets/
            └── data.js


```

## How It Works

1. The quiz presents a set of questions, each with four answer options.
2. When a user selects an answer, the app verifies if it is correct or incorrect.
3. The selected answer is marked as green if correct and red if incorrect.
4. After answering a question, the user can click the **Next** button to proceed.
5. At the end of the quiz, the total score is displayed with the option to restart.

## Future Enhancements

- Add more questions with varying difficulty.
- Implement a timer to make the quiz more challenging.
- Add animations and sound effects to enhance user experience.