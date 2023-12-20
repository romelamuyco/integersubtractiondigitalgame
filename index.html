<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Integer Subtraction Digital Game</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
            text-align: center;
            margin: 0;
            padding: 0;
        }

        #title {
            font-size: 24px;
            font-weight: bold;
            color: blue;
            margin-top: 20px;
        }

        #author {
            color: blue;
        }

        #question {
            font-size: 36px;
            font-weight: bold;
            margin: 20px 0;
        }

        #answer {
            font-size: 24px;
            padding: 10px;
            margin-top: 10px;
            text-align: center;
            display: block;
            margin-left: auto;
            margin-right: auto;
        }

        #result {
            font-size: 20px;
            color: red;
            margin-top: 10px;
        }

        #statistics {
            font-size: 18px;
            margin-top: 20px;
        }

        #timer {
            font-size: 20px;
            margin-top: 10px;
        }

        #buttons {
            margin-top: 20px;
            display: flex;
            justify-content: center;
        }

        button {
            font-size: 18px;
            padding: 10px;
            margin: 0 10px;
            cursor: pointer;
        }

        #submitBtn {
            background-color: #4CAF50; /* Green */
            color: white;
            border: none;
        }

        #newGameBtn {
            background-color: #008CBA; /* Blue */
            color: white;
            border: none;
        }

        #exitBtn {
            background-color: #FF6347; /* Red */
            color: white;
            border: none;
        }
    </style>
</head>
<body>
    <div id="title">Integer Subtraction Digital Game</div>
    <div id="author">Romela A. Muyco</div>
    <div id="question"></div>
    <input type="text" id="answer" placeholder="Your answer">
    <div id="result"></div>
    <div id="statistics">Statistics: Correct Answers - 0, Wrong Answers - 0, Total Answered - 0</div>
    <div id="timer">Time Left: 600 seconds</div>
    <div id="buttons">
        <button id="submitBtn" onclick="checkAnswer()">Submit</button>
        <button id="newGameBtn" onclick="startNewGame()">New Game</button>
        <button id="exitBtn" onclick="exitGame()">Exit</button>
    </div>
    <script>
        let correctAnswers;
        let wrongAnswers;
        let totalAnswered;
        let timeLeft;
        let timerInterval;
        let questions;

        function generateQuestions() {
            const generatedQuestions = [];
            for (let i = 0; i < 40; i++) {
                const num1 = getRandomInt(-9, 9); // Single-digit integers
                const num2 = getRandomInt(-9, 9);
                generatedQuestions.push({ num1, num2 });
            }
            return generatedQuestions;
        }

        function getRandomInt(min, max) {
            return Math.floor(Math.random() * (max - min + 1)) + min;
        }

        function displayQuestion() {
            const questionElement = document.getElementById('question');
            questionElement.textContent = `${questions[0].num1} - ${questions[0].num2} =`;
        }

        function checkAnswer() {
            totalAnswered++;

            const userAnswer = parseInt(document.getElementById('answer').value, 10);
            const correctAnswer = questions[0].num1 - questions[0].num2;

            if (userAnswer === correctAnswer) {
                correctAnswers++;
                document.getElementById('result').textContent = 'Correct!';
            } else {
                wrongAnswers++;
                const specificRule = getSpecificRule(questions[0].num1, questions[0].num2);
                document.getElementById('result').textContent = `Incorrect! The correct answer is ${correctAnswer}. ${specificRule}`;
            }

            document.getElementById('statistics').textContent = `Statistics: Correct Answers - ${correctAnswers}, Wrong Answers - ${wrongAnswers}, Total Answered - ${totalAnswered}`;

            questions.shift(); // Remove the first question

            document.getElementById('answer').value = '';

            if (questions.length > 0) {
                displayQuestion();
            } else {
                endGame();
            }
        }

        function getSpecificRule(num1, num2) {
            // Provide specific rules based on the values of num1 and num2
            if (num1 > 0 && num2 < 0) {
                return 'When subtracting a negative number, it is the same as adding its positive counterpart.';
            } else if (num1 < 0 && num2 > 0) {
                return 'When subtracting a positive number from a negative number, it is the same as adding its negative counterpart.';
            } else {
                // Add more rules based on specific conditions if needed
                return 'When subtracting integers, subtract the second number from the first number.';
            }
        }

        function endGame() {
            clearInterval(timerInterval);
            const percentageCorrect = (correctAnswers / totalAnswered) * 100;
            const completionMessage = `Congratulations! You completed the game. Your score: ${correctAnswers}/${totalAnswered} (${percentageCorrect.toFixed(2)}% correct).`;
            document.getElementById('question').textContent = completionMessage;
            document.getElementById('answer').style.display = 'none';
            document.getElementById('result').style.display = 'none';
            document.getElementById('timer').style.display = 'none';
            document.getElementById('submitBtn').style.display = 'none';
            document.getElementById('newGameBtn').style.display = 'block';
            document.getElementById('exitBtn').style.display = 'block';
        }

        function updateTimer() {
            timeLeft--;
            document.getElementById('timer').textContent = `Time Left: ${timeLeft} seconds`;
            if (timeLeft <= 0) {
                endGame();
            }
        }

        function startNewGame() {
            correctAnswers = 0;
            wrongAnswers = 0;
            totalAnswered = 0;
            timeLeft = 600;
            clearInterval(timerInterval);
            questions = generateQuestions();
            displayQuestion();
            document.getElementById('answer').value = '';
            document.getElementById('answer').style.display = 'block';
            document.getElementById('result').style.display = 'block';
            document.getElementById('timer').style.display = 'block';
            document.getElementById('question').style.fontWeight = 'bold'; // Set font weight to bold
            document.getElementById('statistics').textContent = 'Statistics: Correct Answers - 0, Wrong Answers - 0, Total Answered - 0';
            document.getElementById('submitBtn').style.display = 'block';
            document.getElementById('newGameBtn').style.display = 'block';
            document.getElementById('exitBtn').style.display = 'block';

            // Reset the timer
            timerInterval = setInterval(updateTimer, 1000);
        }

        function exitGame() {
            document.getElementById('question').textContent = 'Thanks for playing!';
            document.getElementById('answer').style.display = 'none';
            document.getElementById('result').style.display = 'none';
            document.getElementById('timer').style.display = 'none';
            document.getElementById('submitBtn').style.display = 'none';
            document.getElementById('newGameBtn').style.display = 'block';
            document.getElementById('exitBtn').style.display = 'block';
        }

        // Initial setup
        startNewGame();
    </script>
</body>
</html>
