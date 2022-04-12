# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Ron Underwood**

Time spent: *4** hours spent in total

Link to project: https://glitch.com/edit/#!/immediate-thunder-soil

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
* [X] More than 4 functional game buttons
* [X] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
https://drive.google.com/file/d/1_K3hzDBevqZslbW7Dt8LaMjRCOhpbK9g/view?usp=sharing
*recordit was not functional for my device for some reason and this was the best that I could do using screentogif.com, the video does not show sound but if you demo the code you will see that it is sound functional. 

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

I looked through some of the JavaScript random documentation along with JavaScript documentation, but ultimately did not end up using any of the 
random function that I generated as I prefered being able to manually choose the pattern and I wanted to turn in the most fun
version of the game that I could create. 

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it?  
I spent a good portion of my time working on this project experimenting with some of the optional features including but not limited to the images on the tiles and having the pattern be randomly decided. From an optimal play perspective I did not like how the images looked in the way that I implemented them. In terms of the random function I thought it was much more interesting being able to dictate the pattern myself and I liked the flexibility that having the manual option provided. In deciding which optional features to implement I talked to 9 different users who were all college aged students like myself and had them try the game out for themselves. This allowed me to gain a better understanding of what the tiles should be, what colors to include, and how fast or slow to have the game pace. As a result, my answer to the question in optimizing the game was talking to users and understanding their perspectives rather than allowing my assumptions to run free. 

3. What questions about web development do you have after completing your submission? 
My main question that I have is how to go from the code that I have on glitch to an actual functioning website. I realize that there are a wide variety of server services including AWS, Google Cloud, and Amazon Azure, but I have yet to deep dive into how to actually deploy something. From there I also would love to have a better perspective on some of the modern developments in the field of web development. I know that the MERN stack has proven to be quite popular, but new frameworks like Next.js have also from what I have seen shown themselves to be incredibly useful and time saving. A final question would be what is the future of web development. With no code tools being more popular by the day, will we eventually see a future where the web will operate on no code? How will web development play into web3 and how will it play into the metaverse? There are also so many web development specific questions like how to connect a front end to a back end to explore, but I think I reached enough here. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. 
If I had a few more hours to work on this project I would experiment with some of the sound systems. I would want to create custom sounds rather than relying on the frequency map. In order to do so my best guess would be that I would need to import some of the custom sounds into the assets folder. From there I am unsure on whether I could directly link those into the frequency map or if I would have to find a work around. The thing is I am a big fan of the linear progression in the sounds so the custom sounds would have to follow the current pattern of low frequencies to high frequencies.



## Interview Recording URL Link

[My 5-minute Interview Recording](https://youtu.be/AFu1-CRvfrE)


## License

    Copyright [Ron Underwood]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
