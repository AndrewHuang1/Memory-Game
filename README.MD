# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Andrew Huang

Time spent: **4** hours spent in total

Link to project: https://glitch.com/edit/#!/cp-memory-game?path=README.MD%3A49%3A0

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
[https://imgur.com/a/HnHWwis]



## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

[W3Schools]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

[One of the challenges I encountered while working on this submission was during the implementation of the additional optional features.
When creating the strikes feature, I experienced problems with updating the innerHTML of the div that would display the number of
tries left the user had. The strikes feature had worked itself since I was able to check with console.log() to see the amount of tries
left while conducting trials to test the feature. I realized that I had to update the innerHTML of the tries left display after each
incorrect guess within the guess() function so that it would reflect the change during the game.]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

[What ways could I make my page look more complete?
What other ways could I implement this game?]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

[If I had a few more hours to work on the project, I would create a difficulty setting, decreasing the amount of time that the sound clue 
is played for as the difficulty increases and allowing the player to choose the length of the pattern. A scoreboard would also
be implemented to keep track of the largest amount of correct guesses along with the difficulty it was played at.]



## License

    Copyright Andrew Huang

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.