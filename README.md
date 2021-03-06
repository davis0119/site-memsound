# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Davis Tran**

Time spent: **1-2** hours spent in total

Link to project: https://glitch.com/edit/#!/memsound

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
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
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
https://drive.google.com/file/d/1qCss9vWC0gVNDz8eJka2GT3dbgrmfTll/view?usp=sharing
![alt-text](https://github.com/davis0119/site-memsound/blob/main/memsound_demo.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
I used an HTML color picker: https://htmlcolorcodes.com/

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
I needed a bit of time to sit down and understand some things that were going on. For example, when I was implementing
the game logic towards the end, I had to take the time to understand what certain variables would be useful for. Instead of diving straight
ahead and attempting to implement stuff, I wrote comments for myself (after reading some of the earlier documentation) in a pseudocode
format, which made things much easier to implement as I was writing code. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
There were some things I had never worked with before, such as writing multiple 
JavaScript functions to interact with the HTML and using multiple properties such us
"onmousedown". I wonder how much more there is to know about web development. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had a few more hours, I would definitely work on a few things to make the game feel more robust and complete.
As of the game's current state, the user could click on the tiles as the demo is playing. I would not allow the user to press on the tiles 
until the demo is gone and add a "fast-forward" button as a compromise. I also might make the length of the button presses matter (with some wiggle room) so that
the user must follow a certain rhythm. I may also add more buttons as levels progress. 


## License

    Copyright [YOUR NAME]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.