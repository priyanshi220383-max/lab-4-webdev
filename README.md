WEB DEV LAB 4
This project is the complete solution for Web Dev I Lab Assignment 4. I developed a simple quiz game that runs entirely in the browser's JavaScript Console,
relying on core JavaScript features like arrays, functions, loops, and conditionals.
IMPLEMENTATION DETAILS:
My solution fully meets all lab requirements and includes several improvements:

Code Structure: The quiz logic is contained within a dedicated runQuiz() function, and a separate startGame() function manages the overall game flow with restarts using a while loop and confirm(). This ensures excellent organization and readability.

Question Array: Used quizQuestions array of objects to store 10 diverse questions (exceeds minimum 5 required), covering geography, math, and web technologies.

Answer Normalization: Robust input handling with userAnswer.toLowerCase().trim() on every response, plus null check for cancel button to handle graceful exits.

Scoring System: let score = 0 accurately tracks performance, increments on correct answers, and displays final result with alert(Quiz Over! Your final score is ${score} out of ${totalQuestions}.).

Immediate Feedback: alert("Correct!") for right answers and alert(Wrong! The correct answer is: ${currentQuizItem.answer}) for incorrect ones with learning feedback.

Restart Functionality: Entire game wrapped in while(playAgain) loop within startGame(), allowing multiple plays via confirm() dialog after each completion.

Console Execution: Pure JavaScript designed for browser console - paste code, type runQuiz() or startGame() to run perfectly.
