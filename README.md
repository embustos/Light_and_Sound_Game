This README file was used to explain my thought process for the finalist submission for CodePath x Salesforce Futureforce Internship. As a finalist, I was prompted to create this project and use the README file to answer questions and explain my thoughts.

# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Emiliano Bustos**


## Required Functionality

The following **required** functionality is complete:

* [ ] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [ ] "Start" button toggles between "Start" and "Stop" when clicked. 
* [ ] Game buttons each light up and play a sound when clicked. 
* [ ] Computer plays back sequence of clues including sound and visual cue for each button
* [ ] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [ ] User wins the game after guessing a complete pattern
* [ ] User loses the game after an incorrect guess

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
* I did not use any outside resources to complete the submission of the Light and Sound Game. I followed along with the guidelines with the provided link (Finalist Task Link).

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

* A challenge that I faced when creating this submission was understanding how to change the color of the buttons when the user clicks on it. I thought it was something similar to `#gameButtonArea>button`. This would not work when I tried interacting with the website. I used trial and error with the CSS code and understood how it refers to the button using the id and `.lit`. I solved this with `button1` and used the code to copy and paste it to the other buttons. On `button4`, the last button, I forgot a comma in the CSS Selector section. This didn't allow the code to differentiate from the two different selectors that were being used in the one CSS rule that would apply to `button4`. Without finding this error, buttons 1-3 would change color as I interacted with them, but `button4` would not. After I added the comma to the selector, I resolved the issue and all of my buttons would change color after each click.

4. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

* One of the inital questions I had after completing this submission is, how important or vital is the backend of a web application on a larger scale? Most of the work I completed was frontend based work and it allows the user to interact with the web application. Now I wonder what the overall purpose is of the backend of a web application and how to implement it into a web application. A second question that I have is, what is the importance of the CSS box model? I have some previous experience with CSS before this submission and understand that there are different areas on an HTML web page that I can focus on with CSS. I want to understand more in depth on the usages of each type of area in the CSS box model and how to get an idea of where the element I will be creating will end up on the webpage.


5. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

* The first thing that came to my mind was to add a feature for colorblind options. This would include protanopia, deuteranopia, and tritanopia. I decided to include this since I got the inspiration from video games that also offer this accessibility feature to allow everyone to visually experience the game to the best of their abilities. This would be a button next to the start button and would appear a menu of the four different options: protanopia, deuteranopia, tritanopia, and none.
* A simple feature that I would add is a round counter that would let the user know what round they are currently on. Another simple feature I would add would be the option to change difficulty, where the hardest level would make the pattern be randomized, faster, and would go on for 15 rounds. Also, just in case the user accidentally presses a button twice (after a round ended), I would like to make the button shake or find an animation to tell the user to wait for the sequence to be over. This would also notify them that they have not lost the game. 
* Working with the `script.js` file, I would work with a class so it could be easier to read and work with encapsulation for the global variables and the functions necessary to run the game. If I wanted to add some of the features I previously stated, classes would make it easier to manage. 

## Video Walkthrough 

Add your screen recordings for specified implemented features here:
* [losing screen recording](https://www.loom.com/share/d13c757b36bc4ac9be62c1346f77bb46?sid=c03366e7-e3ca-4780-b026-60a7fdfd0dac)
* [winning screen recording](https://www.loom.com/share/9be583ce45a440439417e0c59d105dd3?sid=0a520519-7de5-444c-b737-62d3370e5f5b)


## License

    Copyright [Emiliano Bustos]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
