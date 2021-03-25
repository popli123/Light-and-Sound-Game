# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: **Nylan Pierre**

Time spent: **6.5** hours spent in total

Link to project: (insert your link here, should start with https://glitch.com...)

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

- [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
- [ ] More than 4 functional game buttons
- [ ] Playback speeds up on each turn
- [ ] Computer picks a different pattern each time the game is played
- [ ] Player only loses after 3 mistakes (instead of on the first mistake)
- [ ] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

![](https://i.imgur.com/4VulucF.gif)

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.

[No outside resources used.]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)

[Upon my entry to gaining a deeper grasp on programming in HTML, CSS and JavaScript, I have personally felt the
concepts and syntax of the language were easily digestible for both understanding and implementing. Discovering
and venturing through so many aspects, I’ve ran into multiple dilemmas along my journey ranging from trivial to mild
and even to problematic. All which were solved through my key strengths, which are patience and critical thinking.
However, I encountered one problem that had left me stumped resulting in an extensive break, in hopes of getting a
clear headspace. The issue, which was relatively broad in the sense, was me having difficulty visualizing and
comprehending the steps for the program while actively playing the game. Originally, I formulated three ‘if’ statements
that each represented the three potential scenarios you could find yourself in while playing the game. First, if the
button you chose was wrong, you lost. Second, if you were on your last guess and it was correct, you won. Third, if
your guess was correct then it increments the guessCounter and progress variables and plays the clue sequence. At
the time, all my preparations felt coherent and my logic was fool proof. Unfortunately, I missed a very critical step and
that consequently led to the game not playing out as designed. This molded frustration, but also motivation. I began
by tackling this with my personal 3-step problem solving process. To start, I embrace the challenge and I tend to grab
a bigger picture of any issue at hand. Afterwards, I implement my R method that is relax, reflect, and resolve; all
which allows me to take a step back and be resilient. Lastly, my final step I begin document everything from point
beginning to end to grab the detailed portions of my problem. This brings opportunity to truly comprehend how my
written codes were put in action and whether my code was following the game’s logic. During my documentation
stage, I written down the logic of my code and compared it to the logic of the flowchart that was provided. Oddly
enough, I noticed that I never implemented the progress variable besides incrementing it and the whole purpose of it
was to keep track of where you are in the sequence. With that in mind, I finally fixed the issue by making the game
c ontinue only after guessCounter and progress were equal.]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)

[After completing my submission, a plethora of questions came to mind once I saw how user friendly the programming
languages were. Among the dominant questions that piqued my interest were: How to make web applications cross
platform friendly, what are some essential skills every beginner in web development should learn first, what makes a
great user interface design, how long do most web development projects usually take, how often are revisions made
to user interface design, what are some easy-to-use browser developer tools for debugging web code and What
security measures should be considered when developing a web application.]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)

[Considering its my first time using these programming languages, I would need more than just a few more hours to
implement many features. However, multiple ideas came to mind while programming. The first idea would consist of
creating a menu select screen where you would be able to choose different genre of music. Then, depending on what
genre the user would choose, the game would assign sounds specifically from instruments used in that genre to all
the buttons. Additionally, I would also implement a feature that would make the patterns follow a specific beat in
reference to a song, as if the user is playing an audio clip from that song. Finally, the last idea I have would be to
increase difficulty every time you pass a round either by making clues go faster or having some turns give you two
clues instead of just one.]

## License

    Copyright [Nylan Pierre]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
