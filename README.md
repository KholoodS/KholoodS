# Hi ![Hi](<iframe src="https://giphy.com/embed/d8oI97avlJAygnp7RC" width="480" height="418" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/shaymitchell-shay-mitchell-d8oI97avlJAygnp7RC">via GIPHY</a></p>)


# I'm Kholood Jenan Sajid  👋

Full Stack Developer | Open Source Enthusiast | Problem Solver

📫 Reach me at: [Email](mailto:kholoodjenansajid@gmail.com) | [LinkedIn](https://www.linkedin.com/in/kholood-jenan-sajid/) | 
[Twitter](https://twitter.com/KholoodSajid)

[![Tech Stack](https://img.shields.io/badge/Tech%20Stack-React%20%7C%20Node.js%20%7C%20MongoDB-blue)](#tech-stack)

## Tech Stack

- React
- Node.js
- MongoDB
- PHP, CI3
- MySQL
- React & Redux
- Node.js & Express
- Database Design (SQL & MongoDB)
- Git & Version Control

## Play Guess the Number Game

<details>
<summary>Click to play the game!</summary>

```javascript
const secretNumber = Math.floor(Math.random() * 100) + 1;
let attempts = 0;
let guessed = false;

while (!guessed) {
  const guess = parseInt(prompt("Guess a number between 1 and 100:"));

  if (isNaN(guess)) {
    console.log("Please enter a valid number.");
  } else {
    attempts++;

    if (guess === secretNumber) {
      guessed = true;
      console.log(`Congratulations! You guessed the number ${secretNumber} in ${attempts} attempts.`);
    } else if (guess < secretNumber) {
      console.log("Try a higher number.");
    } else {
      console.log("Try a lower number.");
    }
  }
}




