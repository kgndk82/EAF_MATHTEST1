# EAF 1x1 Practice Game

## Overview
The EAF 1x1 Practice Game is an interactive web-based game designed to help users practice multiplication and division skills. It offers a mix of multiplication and division tasks, providing a challenging and engaging way to improve mental math abilities.

## Game Features
- 30 questions per game session
- Mix of multiplication and division tasks
- 30-second time limit for each question
- Point system based on speed and accuracy
- Performance tracking and ranking system

## How It Works

### Starting the Game
1. Open the HTML file in a web browser.
2. Enter your name (or play anonymously).
3. Click the "Start Game" button.

### Gameplay
1. A question appears on the screen (either multiplication or division).
2. You have 30 seconds to answer each question.
3. Type your answer in the input field and press Enter or click Submit.
4. If correct, you move to the next question. If incorrect, you have up to 3 attempts per question.
5. The game ends after 30 questions or when time runs out.

### Question Types
- Multiplication: 
  - One-digit number (1-9) × Two-digit multiple of 10 (10-90)
  - Example: 7 × 60 = ?

- Division:
  - Dividend: Multiple of 10 (10-1000)
  - Divisor: Single-digit (1-9) or multiple of 10 up to 100
  - Result: Always a whole number
  - Example: 720 ÷ 80 = ?

### Scoring
- Points are awarded based on speed and accuracy.
- Maximum 10 points per question for fast, correct answers.
- Fewer points for slower responses or multiple attempts.

### Game Over
- After 30 questions, you'll see your total score.
- You can view a detailed overview of your performance.
- Your score is added to the rankings.

### Rankings
- Top 10 scores are displayed and stored locally.
- Medals are awarded based on performance:
  - Diamond: All questions answered correctly within 5 seconds
  - Gold: 20+ questions answered correctly within 5 seconds
  - Silver: 15+ questions answered correctly within 5 seconds
  - Bronze: 10+ questions answered correctly within 5 seconds

## Technical Details
- The game is built using HTML, CSS, and JavaScript.
- It runs entirely in the browser and doesn't require a server.
- Local storage is used to maintain the rankings between sessions.

## Installation
No installation is required. Simply open the HTML file in a web browser to play.

## Customization
You can easily modify the game by adjusting the JavaScript code:
- Change the number of questions by modifying the condition in the `nextQuestion` function.
- Adjust the time limit by changing the `timeLeft` variable.
- Modify the scoring system in the `calculatePoints` function.

Enjoy practicing your math skills with the EAF 1x1 Practice Game!
