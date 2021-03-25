# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Michael Mao**

Time spent: **8** hours spent in total

Link to project: https://sassy-cautious-petalite.glitch.me

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

* [X] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [X] Buttons use a pitch (frequency) other than the ones in the tutorial
* [X] More than 4 functional game buttons
* [X] Playback speeds up on each turn
* [X] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [X] Added audio compatibility with Google Chrome

## Video Walkthrough

Here's a walkthrough of implemented user stories:
https://imgur.com/a/oCNBe1p


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
Websites.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
A challenge I encountered in creating this submission was making the audio work on Google Chrome, since after Chrome's Audio Autoplay Policy changes in 2018 websites could only play audio once the user made an action on the website. To overcome it, I used Chrome's developer tools to first figure out why my audio wasn't working, and then I followed an article on how to modify my javascript code to fix the issue.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
The biggest question about web development I have after completing my submission is how developers make their websites compatible with all of the browsers used by people today. For example, I noticed my game did not work on my smart phone, and before I fixed the audio issue mentioned earlier, my game did not work on Chrome but did work on Microsoft Edge for example.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had a few more hours to work on my project, I would create a theme for my game by changing the background, adding pictures for the buttons, and using special sound effects. For example, I could make a Star Wars theme with space as the background, main characters as the graphics for the buttons, and different lightsaber sound effects when buttons are pressed.



## License

    Copyright Michael Mao

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
