

# Gradebook App

This project is a simple JavaScript gradebook utility for calculating student grades and class averages.

## Features

- **Calculate Class Average:** Computes the average score for a list of students.
- **Grade Assignment:** Assigns letter grades (A++, A, B, C, D, F) based on score thresholds.
- **Pass/Fail Detection:** Determines if a student has passed or failed based on their grade.
- **Student Message Generator:** Provides a message to each student with their grade, the class average, and pass/fail status.

## How It Works

- Use `getAverage(scores)` to calculate the average score from an array of numbers.
- Use `getGrade(score)` to get the letter grade for a score.
- Use `hasPassingGrade(score)` to check if a score is passing.
- Use `studentMsg(totalScores, studentScore)` to generate a summary message for a student.

## Example Usage

```javascript
const scores = [95, 82, 67, 100, 76];
const myScore = 82;
console.log(studentMsg(scores, myScore));
// Output: Class average: 84. . Your grade: B. You passed the course.
```

## Files
- `main.js`: Contains all gradebook logic and functions.
- `README.md`: Project documentation.

## License
MIT License
