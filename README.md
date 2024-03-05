## Quiz Game Web App

### Concept
This is an interactive quiz game where users can answer questions on 
various topics. You can choose a specific theme (e.g., science, movies,
history) or make it more general.

### Steps:
### 1. Project Setup:
Set up a new project folder.
Create an index.html file, a styles.css file, and a script.js file.

### 2. HTML Structure:
Design a simple layout with question text, answer options, and a submit button.
Use HTML tags like ```div```, ```h1```, ```p```, and ```button```.

### 3. JavaScript Logic:
- Create an array of quiz questions and their corresponding answers.
- Randomly select a question from the array.
- Display the question and answer options dynamically.
- Validate user input and show correct/incorrect feedback.

### 4. Styling:
Use CSS to style your quiz app. Add colors, fonts, and layout adjustments.

### 5. Code Snippets
```HTML 
  <main>
        <div class="container">
            <div id="question-container" class="hide">
              <div id="question">Question</div>
              <div id="answer-buttons" class="btn-grid">
                <button class="btn">Answer 1</button>
                <button class="btn">Answer 2</button>
                <button class="btn">Answer 3</button>
                <button class="btn">Answer 4</button>
              </div>
            </div>
            <div class="controls">
              <button id="start-btn" class="start-btn btn">Start</button>
              <button id="next-btn" class="next-btn btn hide">Next</button>
            </div>
          </div>
    </main>
```

```javascript
const startButton = document.getElementById('start-btn')
const nextButton = document.getElementById('next-btn')
const questionContainerElement = document.getElementById('question-container')
const questionElement = document.getElementById('question')
const answerButtonsElement = document.getElementById('answer-buttons')

const questions = 
{
    question: 'What is 2 + 2?',
    answers: [
      { text: '4', correct: true },
      { text: '22', correct: false }
    ]
}
``` 

### Demo
click [here](https://gbevwunu.github.io/Quiz/) to test the application
































































