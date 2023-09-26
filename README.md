# Welcome to Intro to Programming

Hey friend!! Today, we're diving into a world of pixelated wonders, fantastic gameplay, and the enchanting world of game development and programming. In this course we will take a simple tutorial to build our first game together, and hopefully by the end we'll have Miagi'd some core fundamental programming concepts and knowledge into you while having oodles of fun along the way.

## What are we going to cover?

- Variables
- Loops
- Arrays
- Objects
- Functions
- Control flow or conditionals
- FUN

This might seem like a lot at first, but don't sweat, before long we'll be having fun breaking our game just as much as we celebrate when we fix our game again. These learning concepts will be a bi-product of our fun.

## What is Dragon Ruby?

Dragon Ruby is a wonderfully lightweight game engine designed, built, and owned by [Amir](http://amirrajan.net/). Check out his talk at [RubyConf 2022](https://www.youtube.com/watch?v=s2rngApV1WU). Just a genuine human. As the name implies it allows you to code entirely in Ruby, which, just so happens to be a great a beautiful laguange to code with. I'll save most of the details and say that it's got everything we need to seamlessly build and deploy our very own game to [ich.io](https://itch.io/).

## When does our adventure start?

NOW!!! Like right now! 

## Course Modules

### Module 1: Environment

Kickoff:
- Downloading Dragon ruby and setting up our environment
 - Intro to Git flow
  - Basic commands
 - How to clone this repo
 - [Oh shit git](https://ohshitgit.com/)
 - [Download Dragon Ruby](https://dragonruby.org/toolkit/game)
 - Install VS Code, set up everyone to launch Dragon Ruby in VS code
  - Talk extensions and Github Student and Copilot

Async work:
- Download Dragon Ruby
- Clone this repo
- Install VS code
- Play around with the files inside Dragon Ruby

Pair programming:
- Everyone will pair up and help each other get their environments all set up. 
- Trade back and forth messing around with the game files and playing different samples
- What is happening in the code? What happens when you change things in the file? Can you break the games?

### Module 2: Game play loop and variables.

Kickoff:
- What is `def tick(args)`??
- Can we display something to the screen?
- What if we make it move?
- Lets talk variables, constants, integers, strings, symbols. 
 - Why do we use these data types?
 - What can we do with these data types?
 - Math?!?! Barf. But actually it's kinda cool. (Just wait for methods and functions.)
- Let's import the dragon image, render it to the screen and make it move around.
- Then lets build a text object and display the name of the game

Async work:
- Display the player character
- Make the play character move around
- Render text to the screen
- Render enemies to the screen
- Render a background

Pair programming:
- Play with [Exercism](https://exercism.org/tracks/ruby/concepts)
- The goal is not to get as far as you can, it's to work together to understand what Ruby is doing.
- If you know how to code more than the other person then you are navigating today!
- Today is about being comfortable not knowing, and helping each other to find answers and problem solve.


### Module 3: Conditionals, triggers, and loops

Kickoff:
- What are loops?
- What are triggers?
- If Else End

Async work:
- Make our character point where our mouse is
- Shoot when we click
- Destroy game objects when they reach "out of bounds"
- Make enemies spawn and move on their own
- Add collision so enemies die when they are hit and the player dies when they get touched.
- Give the player health and display it in a text box

Pair programming:
- Play games as a group for 30min
- Cut everyone into break out rooms to talk about game design. What makes a game fun?
- What's your favourite game(s)?
- Find a good article to discuss game design from a popular indy game.
- Bring everyone back to share and talk openly about game design for 45min.

### Module 4: Functions and methods, let's refucktor it!

Kickoff:
- What are functions and methods? Are they different? Ruby is special.
- How could we use what we've learned so far inside of a function?
- What is refactoring? What is something we could refactor from our game?
- What is Object Oriented Design?
- What is DRY code? 
- What are SOLID principles?

Async work:
- Refactor:
 - Player movement
 - Player shooting
 - Enemy spawning
 - Checking if an enemy is dead.
 - Checking if the player is dead
- Build a game over function
- Switch the state between so the player can replay now after they die instead of restarting the game completely.
- Display stats on the Game over screen
- I guess you need a way to keep score, so build a score block
- Save the score at game over to a file
- Can we make and display top 5 scores from our save file?

Pair programming:
50/50 split, you will each drive half the session and help each other think of way to refactor your code and make it dryer. 

### Module 5: Animations, sound, and adding that JUICE

Kickoff:
Let's at some sound!
- What makes good sound design in a game?
- What is "JUICE"?
- Is there bad sound design?
- Let's make terribly designed sound in our game. 
- Is it actually bad? 
- What could we do to make it better without changing the audio?
- What is animation? 
- How do we animate with frames? 
- We aren't artists, so how do we think in ways that help our artists when designing games and asking for assets? (Or finding assets that work for us.)
- Introduce Aseprite/Pixilart, and Audacity/reaper

Async work:
- Add a background song that loops while playing.
- Add a background game over song.
- Add a shooting sound
- Add a death/game over sound for the player.
- Add a death/hit sound for the enemy.
- Add a hit sound for the player getting hit.
- Add an animation loop for the player, the enemies, and the bullets.

Pair programming:
- Can you replace the hit sound to something you can record? 
- Mess around together in Audacity and make a sound, any sound and tune it to oblivion and put it in your game!


### Module 6: Diving deep and breaking things! What are scene transitions?

Kickoff:
- What is a class?
- File structure and importing objects.
- Abstract design

Async work:
- Build scene transitions through:
 - Title
 - Gameplay
 - Game over
Redisign the UI convey game feel without obstructing gameplay

Pair programming:

### Module 7: Play test, Publish, Share!!!!

Kickoff:
- How to give and take great feedback.
- What's a user story?
- How to ask and engage with someone playtesting our game.
- Everyone will play one of my games. 

Async work:
- Finsh any outstanding parts
- Ship to [itch.io](https://itch.io)
- Work on any stretch goals you have! What do you want to add?

Pair programming:
- No break outs, we are all going to play each other's game and write comments on thier Itch.io plages!! Today is all about celebrating you and all you've accomplished!!

