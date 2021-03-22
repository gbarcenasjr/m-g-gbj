# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Gerardo Barcenas**

Time spent: **3** hours spent in total

Link to project: https://glitch.com/edit/#!/m-g-gbj

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. **Check Reflection Question 2**
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

User begins and the series continues after getting it correct
![]http://g.recordit.co/d0z6NGCwnt.gif

User Losing (with alert)
![]http://g.recordit.co/Nm5IksmAOa.gif

User winning (with alert)
![]http://g.recordit.co/6NqYdiqpKD.gif


Complete Demonstration (long GIF, may have error loading)
![]http://g.recordit.co/e8IYBxAnqm.gif

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
I used https://colorhunt.co/ to find the color palette used to color the background, heading, and body of the website.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
The project refused to play tones when I changed the frequency on the .js file after completing it normally. It made the beeping sounds before changing the frequency.
I made sure both my computer and the Chrome tab was not on mute. I made the console display when the notes were played and at what frequency. 
I used the "Rewind" function on Glitch.com and it seemed to help.
**Turns out, sounds only play on the "Next to the Code" website display after pressing the refresh button on top of the "Next to the Code" website display. Please advise!**

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
Does updates to HTML,CSS, or JS (like from HTML4 to HTML5) causes errors in websites? How often do websites need to be updated to maintain functionality?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had a few more hours to work on the project, I would make the buttons into a 3x3 grid, have the order be randomize (random number generator), and impliment lives (like the play only have 2 mistakes before losing).
I would also change the sound of the buttons. I would impliment mp3 files to play custom button sounds for each button.



## License

    Copyright Gerardo Barcenas

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.