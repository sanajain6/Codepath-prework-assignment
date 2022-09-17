# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Sana Jain**

Time spent: **5** hours spent in total

Link to project: https://glitch.com/edit/#!/same-youthful-apatosaurus

## Required Functionality

The following **required** functionality is complete:

* Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* "Start" button toggles between "Start" and "Stop" when clicked. 
* Game buttons each light up and play a sound when clicked. 
* Computer plays back sequence of clues including sound and visual cue for each button
* Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* User wins the game after guessing a complete pattern
* User loses the game after an incorrect guess

The following **optional** features are implemented:

* Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* Buttons use a pitch (frequency) other than the ones in the tutorial
* Playback speeds up on each turn
* Player only loses after 3 mistakes (instead of on the first mistake)

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](https://i.imgur.com/gbnYOUX.gif)
![](https://i.imgur.com/tK5swSy.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
I did not use ant outside resources to complete my submission. The step by step breakdown provided was very helpful, and I wanted to spend the time to figure it out on my own if I could!

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
While trying to implement the optional feature, I noticed I was running into a problem and it took me a little bit to figure out the solution. 
The time it took for the clue to playback on each turn increasingly became faster, even after the game had ended and I clicked the start button again.
I used the console to debug my code, and realized that the variable clueHoldTime was decreasing in value, even after the game was over.
This posed a problem since eventually the clue playback would become so fast, the game would no longer be playable. To fix this, I reinitialized 
clueHoldTime to 1000 within the startGame function, so that when it was called the clueHoldTime would go back to its original value as was intended.
Other than this, it took me a little bit of time to get used to the format of coding a HTML file. Although I do have a bit of experience with web
development, it is very limited. Reading the descriptions provided in the task breakdown helped me gain a better understanding, and I already feel more
knowledgable about web development, which is very exciting!

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
Being able to see how all components came together for this project was very interesting. So far, I have been working on mainly backend in my classes, and languages such as C++ and Java. Working on this project definitely opened my eyes to the world of web development. One of the questions I am intrigued about is how more interactive websites are created and managed. In the memory game, we knew we would have exactly 4 game buttons and a start button, and they were all coded in advance. I would be interested in exploring how user input would be handled and the right output was accordingly
displayed. I am also curious about how data would be saved, especially for websites where users are able to make accounts and the website would have to remember information about the user. I also wonder what other languages are commonly used in web development, and which ones would be recommended to gain an understand of as a beginner. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
There is a lot of room for improvement for this project. For games, I think the user interface plays a big role in your experience, so I would defintely spend some time making the project more visially appealing. I would add a start screen that would display the title of the game, and would feature a start button which would then transition to the actual game. When a player wins or loses, I would display a win/loss screen instead of just a pop up which would feature a play again/try again button, respectively. I would also add some movement to the text, such as having the letters in the game over message fade away or jump up and down. I would add a sound effect when the player wins/loses as well. Regarding the functionality of the game, I would randomize the pattern generated so that the player would not know what to expect and could play multiple times. To make the game more interactive,
I would allow the player to pick a level of difficulty, easy, medium, or hard. Depending on the level, the length of the pattern, number of buttons displayed, and the speed at which the clues were played would vary. I would also add a timer like one of the optional features suggsted if I had a bit more time, as it would add to the gameplay. Since I want to learn how to handle user input, I would also add a feature for the player to input their name and then display a "Welcome [name]!" message. 



## License

    Copyright Sana Jain

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.y6
    


