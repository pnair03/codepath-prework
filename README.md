# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Pranav Nair**

Time spent: **3** hours spent in total

Link to project: https://glitch.com/edit/#!/amethyst-wirehaired-sailor?path=script.js%3A10%3A38

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
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [X] Playback speeds up on each turn
* [X] Computer picks a different pattern each time the game is played
* [X] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](https://i.imgur.com/vnkUQW2.gif)

![](https://i.imgur.com/NaYRzxY.gif)

![](https://i.imgur.com/H66pIzI.gif)

![](https://i.imgur.com/IemKrgK.gif)

![](https://i.imgur.com/7L1KqVi.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

https://www.w3schools.com/js/js_arrays.asp

https://www.w3schools.com/js/js_random.asp

https://www.w3schools.com/jsref/prop_html_innerhtml.asp

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
 
A challenge I encountered was having the current number of mistakes made visible. This is because I initially did not know how to reference a JavaScript variable (var mistakes) through HTML and have it constantly update based on user performance. I initially created an ID for this variable and name it “mistakeNum.” I then added this to my HTML file so that it would be shown. While this initially seemed to work, I quickly realized that the value would always show up as 0, even after the user made a mistake. I then had to do extensive research on the innerHTML property to observe how it worked and when I could use it. After this, I then had to find where to place statements involving the innerHTML property so that the “mistake” value would always be accurate. By observing the JavaScript file and continuously testing the program, I was able to place the statements in the correct places, and the number of mistakes now regularly updates based on the user’s performance. From this, I learned that learning how to debug properly is significant; not everybody will have the right code on the first try, so it is important to know how to debug effectively so that mistakes can quickly be created. I also realized that researching coding concepts while working on a project is perfectly normal; I don’t have to know everything about a project as soon as I start.  

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

While this project has taught me much about web development, I still have a few questions. First off, I noticed that this entire project was contained within one page. One thing that I am curious about is how to create different pages and have them accessible from a central page. For example, if I wanted to make different modes of the game, how would I enable the user to select a certain game mode so that they could play it? Another question I have is how programs can access user data. I believe that this relates to JavaScript more than HTML, but this is also something that I would want to explore because this project did not deal with user inputs in the form of numbers or words. Lastly, I am unsure about how advertisements are implemented on certain websites. How do these advertisements show up in an HTML file? I will be sure to explore these questions.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had a few more hours to work on this project, I would likely spend them adding additional features so that the project is more original. As mentioned in my answer to the previous question, one thing that I would have worked on is creating different versions of the game. I would then allow the user to select which version they wanted to play, and by clicking the corresponding button, the user would be able to play that version. Additionally, I may also try to implement a user-input element to the project. I could build a custom game mode where the user can choose how many buttons exist, how many mistakes can be made, and so on. The game then creates itself using these conditions. Lastly, I may try to implement songs that are currently trending; each button may represent a few seconds of a song. I think this is more interesting than having plain sounds, so the user will likely be more engaged with the game.  

## License

    Copyright Pranav Nair

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
