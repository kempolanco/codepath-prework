# Hello Website

# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Kiara Polanco

Time spent: 3 hours spent in total

Link to project:  https://splashy-tortoiseshell-baritone.glitch.me/

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

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](https://i.imgur.com/bYJLijx.gif)
![](https://i.imgur.com/DQ5GvoS.gif)
![](https://i.imgur.com/8nsl0iF.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
I used my previous homework and labs from my introductory courses CSE 101 (python) and CSE 114 (java).

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
I have never worked with javascript, html, or css so experiencing that with the pre-work was a challenge since I'm not used to writing in these languages. I thought the instructions were helpful in getting me to understand what the written code meant. However, due to my lack of experience writing part for the function guess(btn) is what I found most challenging. The way I approached this was just by working with what I know, so first I wrote out what needs to be done within the function. I thought that first it needs to know when the player won, lost, and progressed to the next round. Then I tried to figure out which ones needed if and or else statements that would keep the code neat. Then, I looked through my notes from my classes in both python and java to see similar codes I've written that had the same functionality. Lastly, I adjusted the code based on what the pre-work code had written already. The only thing I was missing from my code that was different from your version was that I forgot to include playClueSequence(). After reviewing, I corrected my code to have the same naming and missing details as your version. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
Since I've only worked with one coding language at a time through my, I never really thought about how to approach using several at the same time or how to implement it. Through the use of making a really simple game, we had to use three separate languages so it made me question if bigger projects can turn out really seamless. In addition, it made me question if there was a singular language that can accomplish everything css, html, and js did today in a really simple and readable way or if when we want to use several languages at the same time we have to work with a program like glitch all the time.


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
I would add additional features like titling for every round with time shortening for the player as well as the button pattern speed increasing. I would also randomize a pattern for the game rather than just having the one given pattern. I also think it would be interesting to do a point system that is based on time and correctness of the player. So, the faster they guess the pattern in the round, the more points they get added to their total points. Then, I would incorporate a leadership board where a player inputs a username for themselves and can compare their points to others. 

## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright [Kiara Polanco]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.