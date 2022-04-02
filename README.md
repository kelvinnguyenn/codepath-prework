# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Kelvin Nguyen**

Time spent: **5** hours spent in total

Link to project: https://glitch.com/~silly-capable-dawn

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
Functionality of start/stop button & 4 game buttons:
![](https://i.imgur.com/TrYOx8W.gif)
Example progression:
![](https://i.imgur.com/nIQfhkT.gif)
Example loss:
![](https://i.imgur.com/fWGWA5q.gif)
Example win (starts towards end of game):
![](https://i.imgur.com/1GZrXxH.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
A challenge that I encountered in creating this submission was understanding the general logic of the decision-making algorithm. When first trying to figure out the algorithm, I was confused by the variable names of progress and guessCounter as I thought these were the same thing when counting how many guesses a user has correctly guessed. However, I eventually realized that progress was the overall progress that the player had correctly guessed of the entire pattern rather than  the current turn an individual was on. Once I understood this, I used the flow-chart to understand the logic of the algorithm, writing pseudocode on a separate sheet of paper to understand the purpose of each line in determining the next step in the algorithm. By writing down pseudocode with each of the different conditionals, I was able to break down the code into digestible chunks that I could more easily understand (e.g. what the algorithm should do if a user has gone through the entire pattern & progress is done, what to do turn if the guessCounter isn’t equal to progress, etc.). If a certain condition in the flow chart didn’t make sense to me, I would break it down by writing down how I would figure it out without a computer. This happened in particular when I was figuring out what the computer should do in the case that progress is equal to guessCounter. I was confused as to what the computer should do when a player has completed a given turn as I didn’t know how to allow the game to continue given that a user has finished a turn. I wrote out what I would’ve personally done in this situation, which is moving up the total progress by incrementing by 1 and then soft resetting the game state to the beginning with an additional step (e.g. adding an additional step to the pattern). I turned this written explanation into code and then ran my code with an example pattern, checking the console to see if the code was returning what I expected by including print statements in my code. Writing out pseudocode and breaking down what each part of my code did ultimately allowed me to complete the submission and fully understand each part of the decision-making algorithm.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
Some general questions I have about web development after completing my submission would be relating to user data and interaction between web pages. In particular, if a website were to extract data from a user (e.g. on our website it could be something like a score), where and how would a website store this data? I am particularly interested in this topic as there is a large amount of data being generated every second on many websites and I am curious as to how large websites store and manage this data efficiently? Adding onto this, how do specific websites interact with each other such as being able to share a link onto a certain social media page or embed certain types of files within a website? Another question I have about web development is how do websites design and format how their website is going to look? I understand you can use CSS to make a website look nicer, but how can you use other tools to make a button be in a certain position or an animation be in a certain area? Lastly, another question I have after completing my submission is if we were to add more parts to the webpage such as more animations or just generally more bodies of data (images, text, etc.), how can we make it such that the website runs efficiently on any type of machine regardless of processing power?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had a few more hours to work on this project, I would spend them likely increasing the difficulty of the overall game by adding things such as different shapes, colors, and variations (ordering) in the patterns. I would try to implement a difficulty menu in which a user can choose various difficulty options such as how many buttons there are on the screen, the amount of sounds a user is limited to (in order for a user to just memorize based on a particular sense), and the speed of each clue. I would want to implement these features in particular because I believe increasing the overall difficulty of any game increases the amount of fun a player has and allows them to challenge themselves by increasing how difficult the game can get. Another feature I would add to the game if I had more time would be some way of keeping score and creating some type of leaderboard or personal tracker in which a player can compete with other players or even themselves in trying to get a personal best.



## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.loom.com/share/da17d424e5e54ace88dfc23be0db72dc)


## License

    Copyright Kelvin Nguyen

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
