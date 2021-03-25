# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: Rachel Silver

Time spent: 4 hours spent in total

Link to project: https://glitch.com/edit/#!/earthy-fantastic-magnesium

## Required Functionality

The following **required** functionality is complete:

- [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
- [x] "Start" button toggles between "Start" and "Stop" when clicked.
- [x] Game buttons each light up and play a sound when clicked.
- [x] Computer plays back sequence of clues including sound and visual cue for each button
- [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess.
- [x] User wins the game after guessing a complete pattern
- [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

- [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [x] Buttons use a pitch (frequency) other than the ones in the tutorial
- [x] More than 4 functional game buttons
- [x] Playback speeds up on each turn
- [x] Computer picks a different pattern each time the game is played
- [x] Player only loses after 3 mistakes (instead of on the first mistake)
- [ ] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

_User loses after 3 errors_
<img src="https://cdn.glitch.com/b16369cc-9a51-4075-8054-387a92d68fbd%2F3strikes.gif?v=1616653914035">
_User wins_
<img src="https://cdn.glitch.com/b16369cc-9a51-4075-8054-387a92d68fbd%2Fwalkthrough.gif?v=1616654219392">

## Reflection Questions

**1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.**

To help pick colors I used https://www.color-hex.com
I also used https://www.w3schools.com/html to better familiarize myself html options
In order to fill the array randomly I referred to https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/fill and https://developer.mozilla.org/en-US/docs/web/javascript/reference/global_objects/math/random
To help debug my javascript code as I was going along I used https://onecompiler.com/javascript/

**2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)**

As a new programmer, I found the implementation of randomizing the pattern particularly challenging because it involved many different components including a function to create random numbers and a for loop to populate the pattern array. When I’m coding with a new language I often don’t like to add a ton of code at one time. I’d rather write one step, test and debug if necessary. Adding things step by step does add more work but I find it vital to my process. If i get too ahead of myself then it can be hard to know where I went wrong.

When I had to write a program filling an array with random output in my Computer Programing class, I found it extremely helpful to print out statements so I can see the data each step of the way. For a little while writing in Javascript felt like working with a black box. I was very excited when I realized I could use console.log so I could see all the numbers created in the console. I could then verify that the numbers were truly random, in the correct range, and that the pattern array would be generated at the correct time. I also found it helpful to isolate the code for this portion of the program so I would have less factors to worry about. I found an online compiler https://onecompiler.com/javascript and it made everything feel so much less overwhelming.

**3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)**

This assignment was my first true taste of javascript. After learning Python, coding in Javascript felt more intuitive than I expected. This made me wonder how does coding in Javascript using Glitch compare to using other platforms? Would this be similar to building a website from Wordpress? I also wondered if I would usually be working with something like Glitch or if it is common to have to build websites from scratch.

It seems that web development is a collaborative act. It's fun working on assignments like this independently but I wonder how common it is at most real world companies. Are there any best practices, or habits to avoid, when working on code as a team? How would these tasks be broken up at a large company? Is it common to work only on the javascript or html portion of code? I'm excited that this internship will be team oriented as I hope it will shed some light on some of these questions.

**4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)**

I would love to add animation to make the gameplay feel more vibrant and dynamic. Having characters popping out of an hole instead of simply hitting buttons the user would feel a much better sense of engagement. An animation celebrating success could heighten the user’s feeling of satisfaction. An sad animation could also increase the impact of the user losing the game. Animation is a simple ways to make a user feel much more emotionally engaged with the game. An easy way to implement this would be by adding animated gifs that change from visible to hidden depending on what conditions are met.

I also think it would be fun to create an easy, medium, and hard level which would alter the speed, length of the sequence, and number of boxes accordingly. An easy game could offer only three boxes. The sequence would be short and slow. The user could work their way up to a hard level which would have 10 boxes with a quick and long sequence. I feel this would make the game much more replayable. It also could be a way to make the game versatile for all ages.

## License

    Copyright Rachel Silver

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
