# Word-Guess-Game

My Word Guess Game is a simple version of a hangman style game. I chose World Cities! The purpose of this assignment was to create a word guess game using Javascript.

Link to game: 

https://sheimagh.github.io/word-guess-game/

How to Play:

Press any Alpha key (A-Z, a-z) to start game. Non alpha keys are ignored. The theme of the game is 'World Cities'. The game will randomly select a world city from its internal list. It will then display a blank word using underscores to represent the letters in the word. It is possible to have a multi-word city such as Los Angeles.

If a correct letter is guessed, the game will reveal the letter in its correct location. If an incorrect letter is selected, then it will add the letter to a list on incorrectly guessed letters and decrement the remaining guesses count.

If the user guesses the correct city name before remaining guesses equal zero, then the game increments the number of wins and restarts the game by selecting a new random city name and reseting the game parameters.

If the user does not guess the correct city name within the allocated number of guesses, then the game resets.

Assets used:

Background image: https://www.shutterstock.com 

Sounds: https://notificationsounds.com Public License


![screenshot](https://user-images.githubusercontent.com/44955946/50499151-eb97f300-0a0c-11e9-94e8-d51b813a5be3.PNG)


Side notes:

I spent some time trying to get it to work when either the user guessed the correct city or ran out of guesses. I was able to get something partially working. I also didn't spend much time enhancing the website with more CSS. My thought was to enhance its functionality using more Javascript functions (i.e.'You Win' or 'You Lose'). As I gain more experience, I would like to revisit this exercise and improve both the JS functions and include Jquery with the styling (like incorporating the letter buttons that were used for example like the "Fridge Game" and other fancy elements.)

---------------------------------------------------------------------------------------------------------------------------------------

# JavaScript Assignment

### Overview

In this assignment, you'll create one of two possible computer games: Word Guess or Psychic. These apps will run in the browser, and feature dynamically updated HTML and CSS powered by your JavaScript code.

### Submission on BCS

* Please submit both the deployed Github.io link to your homework AND the link to the Github Repository!

### Before You Begin

1. Create a new GitHub repo called `Word Guess Game` or `Psychic-Game`, in accordance with the assignment you choose to complete. Then, clone it to your computer.

2. Inside your local git repository, create an `index.html`.

3. While still in your local git repo, create a directory called `assets`.
4. `cd` your way into the `assets` folder, then make three additional folders: `javascript`, `css` and `images`.

   * In the `javascript` folder, make a file called `game.js`. Use the `src` attribute of the `script` tag to link to this file, rather than embedding the code directly in your HTML document.
   * In the `css` folder, make a file called `style.css`.
   * Also in the `css` folder, make a file called `reset.css`. Paste into it the code from the Meyerweb reset stylesheet. If you opt to use Bootstrap instead of writing your own CSS, skip this step, and simply include a link to Bootstrap via CDN.
   * In the `images` folder, save whatever images you plan on using.

```
├── assets
|  ├── css
|  |  └── style.css
|  ├── images
|  └── javascript
|     └── game.js
└── index.html
```

5. Push the above changes to GitHub.

6. Choose whichever game you'd like to build. Making the Psychic game will prove less challenging than coding Word Guess. However, as the challenge of the Word Guess exercise provides a more comprehensive review of this unit's material, we suggest attempting that assignment first.

7. Note: There's no shame if you'd prefer submitting Psychic—it's still a proper challenge.

8. Push your selected game to Github Pages.


## Option Two: Word Guess Game (Challenge - Recommended)

1. [Watch the demo](https://youtu.be/W-IJcC4tYFI).

2. Choose a theme for your game! In the demo, we picked an 80s theme: 80s questions, 80s sound and an 80s aesthetic. You can choose any subject for your theme, though, so be creative!

3. Use key events to listen for the letters that your players will type.

4. Display the following on the page:

5. Press any key to get started!

6. Wins: (# of times user guessed the word correctly).

   * If the word is `madonna`, display it like this when the game starts: `_ _ _ _ _ _ _`.

   * As the user guesses the correct letters, reveal them: `m a d o _  _ a`.

7. Number of Guesses Remaining: (# of guesses remaining for the user).

8. Letters Already Guessed: (Letters the user has guessed, displayed like `L Z Y H`).

9. After the user wins/loses the game should automatically choose another word and make the user play it.

##### Word Guess Game Bonuses

1. Play a sound or song when the user guesses their word correctly, like in our demo.
2. Write some stylish CSS rules to make a design that fits your game's theme.
3. **HARD MODE:** Organize your game code as an object, except for the key events to get the letter guessed. This will be a challenge if you haven't coded with JavaScript before, but we encourage anyone already familiar with the language to try this out.
4. Save your whole game and its properties in an object.
5. Save any of your game's functions as methods, and call them underneath your object declaration using event listeners.
6. Don't forget to place your global variables and functions above your object.
   * Remember: global variables, then objects, then calls.
7. Definitely talk with a TA or your instructor if you get tripped up during this challenge.

- - -

#### A Few Tips

1. **IMPORTANT:** Whichever assignment you choose, code your game one piece at a time! Code all of your apps one piece at a time. _Always code one piece at a time!_
2. Pseudocode your program and break the app down into tiny, manageable fragments. This will make the coding process much less frustrating and a veritable Mach number faster. Otherwise, you'll be chipping away at a giant chunk of abstraction for way too many hours.

   * The ability to solve a large problem by treating it as a set of smaller ones is the hallmark of a strong programmer. Best start adapting this into your development routine now, to better prepare for your more complex future projects.
   * Remember:
     1. Split the whole program into many distinct, pseudocoded problems.
     2. Focus on one of the smaller problems and solve it.
     3. Only when you solve one problem should you then move onto your next problem.

3. When you encounter bugs (and we all do), `console.log` will become your best friend. Regularly check your console to make sure your app is spitting out the right values.

   * As a more advanced—but more powerful—alternative, feel free to experiment with the [Chrome DevTools Debugger](https://developers.google.com/web/tools/chrome-devtools/).

4. Try your best to deliver a 'working/playable game' by the end of the deadline. If you're not making progress with Word Guess, switch gears to the Psychic game. Contact your TA/Instructor if you're not making progress after 2 hours. We're here to help!

5. Substance over style! Submitting a working game matters more that making a broken app that at least looks pretty. We're focusing on game mechanics, not just on the look and feel of your app.
6. That said, coding a functional app that also looks pretty would be impressive.

7. Always commit your work and back it up with GitHub pushes. You don't want to lose hours of your work because you didn't push it to GitHub every half hour or so.

   * **Commit often**.

8. Turn in anything you have! Even if you don't finish, we still want to see what you were able to accomplish in the time we gave you. This will help us know what concepts we could help you with, as well as what topics we should focus on in the coming lectures.

### Reminder: Submission on BCS

* Please submit both the deployed Github.io link to your homework AND the link to the Github Repository!

- - -

### Minimum Requirements

Attempt to complete homework assignment as described in instructions. If unable to complete certain portions, please pseudocode these portions to describe what remains to be completed. Adding a README.md as well as adding this homework to your portfolio are required as well and more information can be found below.

- - -

### Create a README.md

Add a `README.md` to your repository describing the project. Here are some resources for creating your `README.md`. Here are some resources to help you along the way:

* [About READMEs](https://help.github.com/articles/about-readmes/)

* [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)

- - -

### Add To Your Portfolio

After completing the homework please add the piece to your portfolio. Make sure to add a link to your updated portfolio in the comments section of your homework so the TAs can easily ensure you completed this step when they are grading the assignment. To receive an 'A' on any assignment, you must link to it from your portfolio.

- - -

### One More Thing

If you have any questions about this project or the material we have covered, please post them in the community channels in slack so that your fellow developers can help you! If you're still having trouble, you can come to office hours for assistance from your instructor and TAs.

**Good Luck!**
