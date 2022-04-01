# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Bryan Rivas

Time spent: 5 hours spent in total

Link to project: (live site - https://meadow-spotted-team.glitch.me/)                                    
                (Code - https://glitch.com/edit/#!/meadow-spotted-team)

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
![](https://i.imgur.com/HQCiZPq.gif)

![](https://i.imgur.com/vyOPYqs.gif)

![](https://i.imgur.com/Tox6dz2.gif)

![](https://i.imgur.com/nPIfVf8.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
    
    Codepath TA slack channel 
    
    https://www.w3schools.com/js/js_if_else.asp
    https://cssreference.io/
    https://www.w3.org/Style/Examples/007/fonts.en.html
    https://www.w3schools.com/css/css_font.asp
    https://www.w3schools.com/cssref/pr_font_font-family.asp
    https://www.w3schools.com/js/js_events.asp
   

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
    
    A challenge I encountered in creating the prework project was understanding all the different attributes and properties that were being implemented. I really wanted to gain a more in depth understanding of what 
    was going on in my project. I haven't worked on a project that required the use of html, javascript, and css. This was very new to me and it was a challenge that I looked as a great opportunity for me to expand 
    my computer science knowledge. In step 4 where we had to add style to the game, I felt like I didn't really understand how the "font-family" worked. So, I decided to do some research and experimentation of my own of 
    how the different fonts can be implemented. I looked up different fonts and different styles that can be used in my game. I had the preview panel open on the side so I could see the changes in live time. This helped 
    me understand the different properties of both the parent and child elements. Another challenge I faced was in step 9, where we handle the logic of the different events that occur in the game. I drew out my own type 
    of flow chart to organize my logic and how I was going to tackle this problem. As I mentioned, I struggled in keeping up with everything that was going on and how it was connected across the different files in the project. 
    I also researched the syntax of conditional statements of javascript as I was unfamiliar with how to do that and how to work with nested statements in javascript. From there I had to figure out how I check for correct guesses 
    and if the turn was over. I had to take a step back and look at the variables that I was going to need to accomplish this task. I realized that I was going to need the array "pattern", "guessCounter", and "progress". These are 
    the variables that are going to tell me the state of the player and at what level he is at in the game. From there I started my logic with if the player lost and I would call the "lostGame" function. After that I was able to 
    focus on situations like if the player had won or if the player was still progressing in the game. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
    
    A question that I have about web development is when it comes to the web development languages which languages are best for certain types of projects when working with them. I have also questioned if are you able to combine languages 
    such as html and javascript with higher ones like C++. Similar to how we did with the prework project, is one able to combine different languages that may be considered higher object oriented? Also, I want to know what are some of the 
    bigger projects one is able to build using these web development coding languages and how to maximize each of the languages capabilities. For example, the designing capabilities that one can use when developing a website and its framework. 
    Another question I have is, how to implement and connect APIs to a website which adds another layer to the UI/UX. I also wonder, in what ways cybersecurity and protection of privacy of the users data is managed, especially with websites 
    that may require or contain personal information of the user. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

    If I had more time to work on the project I would implement a feature for the user to be able to select music of their choice while they play the game. They would be able to connect their Spotify or Apple music 
    account and play music from their playlist. I would also try to adjust some of the design of the game. For example, have a selection of backgrounds that the user can choose from or if they wanted to they can 
    upload an image that they want as their background. They can even add images to the different buttons of the game and sound bites for when they light up instead of the beeping sound. I would also add a scoreboard 
    to keep track of the best times from the users who play the game and to add a feel of competitiveness to the game. 



## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.loom.com/share/a46fd369f03c40299f595db4af90539e)


## License

    Copyright [Bryan Rivas]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.