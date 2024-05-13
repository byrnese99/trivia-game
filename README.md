# Trivia Game

The Trivia Game web application allows users to test their knowledge by answering multiple-choice trivia questions. It features a simple and intuitive user interface where users can start the game, answer questions, and check their answers. The application is built using React and utilizes the Open Trivia Database API for retrieving trivia questions.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [How to Play](#how-to-play)
- [Components](#components)
- [Styles](#styles)
- [Technologies Used](#technologies-used)
- [License](#license)

## Features

- Allows users to start the game and answer multiple-choice trivia questions.
- Dynamically updates the questions and answers fetched from the Open Trivia Database API.
- Provides immediate feedback on correct and incorrect answers.
- Users can return to the home screen at any time.

## Installation

To run the Trivia Game application locally, follow these steps:

1. Clone the repository: git clone <repository-url>
2. Navigate to the project directory: cd trivia-game
3. Install dependencies: npm install

## How to Play

To play the Trivia Game, follow these steps:

1. Start the game by clicking the "Start Game" button.
2. Answer the multiple-choice questions by selecting an option for each question.
3. Once you've answered all questions, click the "Check Answers" button to see the results.
4. You can return to the home screen at any time by clicking the "Return to Home Screen" button.

## Components

### Question Component

The `Question` component renders the text of a trivia question.

### Answer Component

The `Answer` component displays a single answer option for a trivia question. It handles different styles based on whether the answer is selected, correct, incorrect, or unchecked.

## Styles

The project utilizes CSS for styling. Here are some key styles used in the project:

- Custom variables for primary, secondary, and accent colors.
- Different styles for correct, incorrect, selected, and unselected answers.
- Responsive design for various screen sizes.

## Technologies Used

- React
- nanoid
- Open Trivia Database API

## License

This project is licensed under the [MIT License](LICENSE).
