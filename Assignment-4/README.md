# MBC-unit2

## Application & Repository Link

###### [Application Link](https://suji-gith.github.io/MBC-Assignments/Assignment-4/QuizPage.html)

###### Repository Link
https://github.com/Suji-GitH/MBC-Assignments/tree/master/Assignment-4

## Table of Content
- [Overview](#Overview)
- [Acceptance Criteria]()
- [Pseudo Code]()
    - [High Score Page]()
    - [Quiz Page ]()
- [UI/UX & Application Screens]()
    - [UI/UX Consideration]()
    - [App Screenshots]()
- [Credits]()
- [Testing]()

## Overview

AS A coding Boot Camp student
I WANT to take a timed quiz on JavaScript fundamentals that stores high scores
SO THAT I can gauge my progress compared to my peers


## Acceptance Criteria

GIVEN I am taking a code quiz
WHEN I click the start button
THEN a timer starts and I am presented with a question
WHEN I answer a question
THEN I am presented with another question
WHEN I answer a question incorrectly
THEN time is subtracted from the clock
WHEN all questions are answered or the timer reaches 0
THEN the game is over
WHEN the game is over
THEN I can save my initials and score


## Pseudo Code

###### High Score Page

Html
1. Title High Scores
2. Button for back to Home Page
3. Button for Clear High Scores
4. Empty ol tag to hold scores

CSS
1. background for the page 
2. Bootstrap buttons 
3. list styling

JavaScript
1. link back to Home Page on "click"
2. Clear HighScore function on "click"
3. get local storage for initials

###### Quiz Page 

Html

home screen
1. View High Scores a tag link 
2. Count down timer
3. Title Coding Quiz Challenge 
4. P tag instruction for game rule
5. Start quiz button

Quiz Start Screen
1. Question
2. 4 multiple choice button
3. empty div to show correct or wrong 

Quiz End Screen
1. Title All done 
2. dynamic final score
3. enter initial textbox
4. submit button 

CSS
1. background for the page 
2. 5 panels of coloured vh div boxes 
3. Buttons for multiple choice 
4. Quiz game appropriate font

JavaScript
1. AddEventListener on start quiz button
2. Object or Array for questions and answers
3. Function to display questions and multiple choices
4. AddEventListener to multiple choice buttons
5. function to display correct or wrong answer
6. Sound effect for correct and wrong answer 
7. function to display Time count down
8. div fade effect for every 15 sec passed 
9. function to show dynamic score depending on the time left 
10. Wrong answer decreases the time by 10 sec
11. AddEventListener for submit high scores button
12. set local storage for high scores initial 
13. Don't allow null value for submit button 

## UI/UX & Application Screens

###### UI/UX Consideration

Application is kept simple with minimal wording, Font that's easier to read and less visual distractions around the screen so that user can focus on the content and questions & multiple choices displayed. 

Buttons are all kept uniform colours and for multiple choice questions, red/green visual aid is given when incorrect/correct answer is chosen in addition to red/green alerts.

In addition to displaying the count down time, the light blue opaque coloured boxes disappear towards to the middle as the time go down towards 0 so that they be able to still see in peripheral vision rough estimate of time left. 

###### App Screenshots

Quiz Game Landing Page

Questions Displayed to User

Incorrect Answer to Question

Correct Answer to Question

Quiz GameOver Screen 

User High Scores Page

## Credits

3rd Party API
    - Bootstrap
    - Google Fonts
    - Font Awesome
    - Favicon.io 
    - jQuery
    
## Testing

No coding test was conducted, only front-end functionality tested.

As User when I land on the Quiz page 



GIVEN I am taking a code quiz
WHEN I click the start button
THEN a timer starts and I am presented with a question
WHEN I answer a question
THEN I am presented with another question
WHEN I answer a question incorrectly
THEN time is subtracted from the clock
WHEN all questions are answered or the timer reaches 0
THEN the game is over
WHEN the game is over
THEN I can save my initials and score