# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Calvin Garcia

Time spent: 10 hours spent in total

Link to project: https://glitch.com/edit/#!/sdfadasdasd

## Required Functionality

The following **required** functionality is complete:

* [X] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [X] "Start" button toggles between "Start" and "Stop" when clicked. 
* [X] Game buttons each light up and play a sound when clicked. 
* [X] Computer plays back sequence of clues including sound and visual cue for each button
* [X] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [X] User wins the game after guessing a complete pattern
* [X] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [X] Buttons use a pitch (frequency) other than the ones in the tutorial
* [X] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [X] Computer picks a different pattern each time the game is played
* [X] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](gif1-link-here)
![](gif2-link-here)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

    I used a few outside resources such as w3schools.com because I was confused on how to implement some code in Javascript where it would generate a random pattern each time the user pressed the start button on the screen.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

    When I was working on this project, I had a hard time trying to make the Guess function. This was because I was a bit confused on what variables controlled the guessCounter and progress. It was also difficult at first to implement a function where each time the user pressed the start button, a new pattern would be generated. I thought this could be done by setting all the values of the array to values 1-6 but I realized I need to set my array to size "8," and then use a for-loop to set each variable to a value between 1-6. I also had a little difficulty implementing.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

    Regarding web development, what would happen if I attempted to make a website using just HTML since CSS controls the website’s appearance and Javascript controls the website’s behavior. Is it also good to have some experience in some back-end programming language when trying to learn Javascript, because I noticed that it’s very similar to Java/C++ that I learned in school. I also want to know if it's possible to show a variable in Javascript in the HTML body because I was trying to implement a mistakeCounter but I was confused on how to show it.


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

    If I had a few more hours to work on this project, I would have definitely added a mistakeCounter so it shows the user how many mistakes they are from getting a "Game Over" notifcation. I also would've added a section where it shows all the previous buttons pressed or how far the user is from winning the game.



## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright Calvin Garcia

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
