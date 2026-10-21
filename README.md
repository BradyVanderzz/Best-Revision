# Best Revision
## What is this?
A quick and intuitive revision application allowing you to input your own questions & answers for quizzes and flashcards to help with your revision.

## Features
- Allows users to input their own questions and answers which can be saved in up to 5 different docuements and can be further updated or removed later.
- Users can choose between Quiz mode or Flashcard mode
- Quiz mode gives users three attempts to answer a randomly selected question
- Flashcard mode displays a random question and allows users to flip the card to view the answer

## Why I built this
I built this project to help with my A Level revision so I could create and practise questions on topics across my subjects. I tried other apps but I needed one with no bloatware and that I could also use offline.

## Future improvements
- Allow users to label questions as "confident" or "needs practise" for Quiz and Flashcards
- Have the application keep track of what questions the user gets correct or not
- Include an LLM API to help users create questions and asnwers easier.

## How to use
- Click the "Questions & Answers" button at the top and a menu and select a document. A text box will then appear where you can write a question in the first line and the answer to that question in the line below it. This can then be repeated with every odd line being a question and every even one being answers.
- Once all questions and answers have been written, click "Save & UsenQuestions" and they will be updated and active in the Quiz and Flashcard modes immediately.
- In the quiz section a question will appear, then you need to write an answer in the text box. Once you have written the question, click "Submit" and it will display if you got it wrong or right. If you get a question wrong it will give you three tries and then will tell you the answer. You can then click "Next Question" to load and answer the next one.
- In the flashcards section a question will appear and you can click "flip" to see the answer. You then need to click "Next Question" to show the next flashcard.

## If you want to run the Python file instead of the exe:
### Requirements (when running with python)
- Python 3
- Custom TKinter

### How to install CustomTKinter
- In Command Promp (Windows) or Terminal (macOS/Linux), run "pip install customtkinter"
    - If pip is not recognised try running:
        "python -m pip install customtkinter" or "py -m pip install customtkinter"
- If that still doesn’t work, ensure Python is installed and added to PATH or find further tutorials for this process online

### How to run
Run the main python file after installing CustomTkinter and Python 3 - This can be done by double clicking the MainProgram.py file in the folder
