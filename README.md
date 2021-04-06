# Homework4
This project was brutal. 

HTML:
index.html is my quiz page.
highscore.html is my highscore page.

highscore.css is styling dedicated to highscore.html
style.css is style dedicated to index.html

highscore.js exists to pull from local storage and update the current highscore.

javascript.js was very difficult. Once I figured out how to dynamically update my questions and answers, things improved. 
My next hurdle was figuring out how to trigger the next function without having previous question sets running at the same time.
Then I had to figure out how to create a setinterval timer to track a global timer, I have yet to figure out how to reduce the remaining seconds with wrong answers, every iteration of this either exponentially reduced time, or didn't work.  
Finally I had to track highscores only if the current score is greater than the users highscore, and store it locally for persistance, and to pull in the highscore page.

Challenging to say the least, I'll keep working on getting the interval to work properly.
