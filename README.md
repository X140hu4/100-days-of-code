# #100DaysOfCode Log - Round 1 - Fabien

The log of my #100DaysOfCode challenge. Started on [January 15, Monday, 2017].

### Day 036: February 19, 2018
**Today's Progress**:
1. [30DaysOfJS] Lesson 5 - Flex Panels
2. [fCC - Simon Game] Working on the logics

**Thoughts**
Javascript 30
Learning about transform: translateY(xx%) to hide/show elements
Use of JS object.classList.toggle(classname); to add/delete a class from an element
fCC - Simon Game
Learned that this.style.gridColumnStart gets only the inline value. Need to use the window.getComputerStyle(element).getPropertyValue('cssPropertyName'); to get the value defined from CSS.
fCC - Simon Game (pomodoro notes)
- Research on timeout for replaying the sequence. Applied to the playSound function and toggling the active class.
- Writing computer sequence logics. Trouble replaying the sequence 
- Starting writing playing logics
- Set column start of toggles and get the value from the CSS (via computed style rather than element inline style) 

**Link(s) to work**
1. [fCC - Simon Game](https://github.com/X140hu4/FCC/tree/master/09.%20Simon%20Game)

### Day 035: February 18, 2018
**Today's Progress**:
1. [30DaysOfJS] Lesson 4 - Array Cardio Day 1
2. [fCC - Simon Game] Designing control board

**Thoughts**
Javascript 30
- Reviewing map, reduce, sort and filter
fCC - Simon Game (pomodoro notes)
- Working on row toggle buttons styling. 
- Redesigning toggling buttons with css grid to make it more flexible than nit picking and aligning elements when toggling.
- Wrote function changing the toggle button's grid-column-start.
- Working on refactoring the toggle buttons. 
- Restyling power toggle with grid and JS manipulation.

**Link(s) to work**
1. [fCC - Simon Game](https://github.com/X140hu4/FCC/tree/master/09.%20Simon%20Game)

### Day 034: February 17, 2018
**Today's Progress**:
1. [fCC - Simon Game] Designing buttons

**Thoughts**
Not much time today as I have a work shift from 1PM to 12AM :(
fCC - Simon Game
- Finished a first design of the toggle buttons

**Link(s) to work**
1. [fCC - Simon Game](https://github.com/X140hu4/FCC/tree/master/09.%20Simon%20Game)

### Day 033: February 16, 2018
**Today's Progress**:
1. [30DaysOfJS] Lesson 3 - Playing with CSS Variable with JS
2. [fCC - Simon Game] Designing control board

**Thoughts**
Javascript 30
- Learned about CSS variables
- Two new eventlisteners: 'change', 'mousemove'
- Personalized 'data' attributes on HTML elements and JS manipulation
fCC - Simon Game (pomodoro notes)
- Designing row of buttons.
- Finished styling buttons row. Completing styling of toggle start button to replicate to Game and Skill level controls 

**Link(s) to work**
1. [fCC - Simon Game](https://github.com/X140hu4/FCC/tree/master/09.%20Simon%20Game)

### Day 032: February 15, 2018
**Today's Progress**:
1. [30DaysOfJS] Lesson 2 - JS and CSS Clock
2. [fCC - Simon Game] Designing control board

**Thoughts**
Javascript 30
- Learned about transform and transition
fCC - Simon Game (pomodoro notes)
- Working on controls. Designing power block (on/off)
- Panel grid and position to be in middle of the controls div.

**Link(s) to work**
1. [fCC - Simon Game](https://github.com/X140hu4/FCC/tree/master/09.%20Simon%20Game)



### Day 031: February 14, 2018
**Today's Progress**:
1. [CSS] Reading on Naming conventions
2. [30DaysOfJS] Lesson 1 - Drum Kit
3. [fCC - Simon Game] Board outline and play sound function

**Thoughts**
CSS
- Read about [BEM naming convention](https://medium.freecodecamp.org/css-naming-conventions-that-will-save-you-hours-of-debugging-35cea737d849). I think I will try using this first before trying other conventions such as OCSS, ACSS and SMACSS.
Javascript 30
- Learned about addEventListeners keydown and transitionend.
fCC - Simon Game (pomodoro notes)
- Succeeded using css grid to create and position buttons. Working on the central piece with the commands.
- Research to style the center piece with ::before and ::after.
- ::before element on button is not good because it would be a circle when adding space between buttons. Exploring ::before on #game-device. Issue with positioning and also for the content that will have to contain the controls
-  Created a control div. In order for it to have a % of parent div as height/width the parent needed to be position: relative while the child is position:absolute. Working out the design of the buttons on paper.
- Added onclick eventlistener and playsound function. Worked out the frame of the controls.


**Link(s) to work**
1. [fCC - Simon Game](https://github.com/X140hu4/FCC/tree/master/09.%20Simon%20Game)

**Additional links**
1. [Get BEM](http://getbem.com/introduction/)

### Day 030: February 13, 2018
**Today's Progress**:
1. [Javascript Allongé] Read until Combinators and Function Decorators
2. [You Don't Know JS] Read chapter 'this All Makes Sense Now!'
3. [fCC - Simon Game] Working on the style of buttons

**Thoughts**
See progress' description


**Link(s) to work**
1. [fCC - Simon Game](https://github.com/X140hu4/FCC/tree/master/09.%20Simon%20Game)

### Day 029: February 12, 2018
**Today's Progress**:
1. [Portfolio] Updated portfolio with new completed projects
2. [Pomodoro clock] Solved issue pointed by feedbacks
3. [fCC - Simon Game] Folder set up and started working on view

**Thoughts**
Added new projects to the portfolio. Added a min-height to portfolo cards.
Solved skills section overflow by setting height to min-height.
Pomodoro project:
- Solved issue with timer starting at 0 initially and counting down from -2.
- Added text to show if the current timer is working or on break.
Simon Game project:
- I will need to push my CSS skills a bit further to do the game device

**Link(s) to work**
1. [fCC - Tic Tac Toe github](https://github.com/X140hu4/FCC/tree/master/8.%20Tic%20Tac%20Toe)

### Day 028: February 11, 2018
**Today's Progress**:
1. [fCC] Tic Tac Toe: Finished project

**Thoughts**
Pomodoro notes:
- Finished styling of settings. Finished coloring. Added pointer style. Started writing functions for selecting player.
- Implemented pointer state change. Implemented settings player choice, display board and play.
- Started refactoring and solving computer start bug
- Refactored the play logics (dom and array manipulation from player and AI). Working on restart and togglepanes.
- Abandonned togglePane function. Worked on a bug where player could play even though it was computer's turn. Using CSS on the game board 'pointer-event: none' to disable clicks.
- Completed project.

**Link(s) to work**
1. [fCC - Tic Tac Toe github](https://github.com/X140hu4/FCC/tree/master/8.%20Tic%20Tac%20Toe)

### Day 027: February 10, 2018
**Today's Progress**:
1. [fCC] Tic Tac Toe: Finished implementing perfect AI. Started design of player choice.

**Thoughts**
Pomodoro notes:
- Starting implementing computer player into game flow.
- Computer is working! Did some title styling (choose a cursive font). Started adding html elements for player choice logics. 

**Link(s) to work**
1. [fCC - Tic Tac Toe github](https://github.com/X140hu4/FCC/tree/master/8.%20Tic%20Tac%20Toe)

### Day 026: February 09, 2018
**Today's Progress**:
1. [fCC] Tic Tac Toe: Working on AI with minimax algorithm

**Thoughts**
The computer function was returning undefined because there was no return from the function. The function was called recursively.
The function seems to work but the final choice is still not correct. I would have to work on that.

Pomodoro notes:
- Working on minmax
- Needed to return a value to push on scores... working on minmax return value
- Working on minmax core calculation.
- Worked on the depth caculation to give the correct answer.

**Link(s) to work**
1. [fCC - Tic Tac Toe github](https://github.com/X140hu4/FCC/tree/master/8.%20Tic%20Tac%20Toe)

### Day 025: February 08, 2018
**Today's Progress**:
1. [fCC] Tic Tac Toe: Working on AI with minimax algorithm

**Thoughts**
- Defined a test boardStatus. Started implementing minmax. Trouble passing winstate. 
- Variable scoping is making things difficult to implement the different functions
- Working on the simulation of boards with local variables.
- Continuing working on simulation...
- Finished implementing possibleGame generation. Working on scoring.
- Continuing struggling with scoring

**Link(s) to work**
1. [fCC - Tic Tac Toe github](https://github.com/X140hu4/FCC/tree/master/8.%20Tic%20Tac%20Toe)


### Day 024: February 07, 2018
**Today's Progress**:
1. [fCC] Tic Tac Toe: Started project

**Thoughts**
- Set up folder and files. Initial design and list of todo
- Board structure is Table with 3 table rows containing 3 td elements. Gave different id to each td and added onclick handling event. Coded handleClick to show cross or circle icon from fontawesome based on turn (turnCross boolean).
- Working on the checkBoard for winning conditions. 
- Finished checkBoard for winning conditions. Started reading on minimax algorithm for the computer player. 
- Reading 'Tic Tac Toe Understanding the minmax algorithm'. Working out the pseudo code and thinking about how to implement it in JS.
- Setting up initial state for testing minmax implementation. Set up display board, had problems with the array not being correct. Started with a dynamic implementation but it really does not matter so will have a hardcoded array instead.

**Link(s) to work**
1. [fCC - Tic Tac Toe github](https://github.com/X140hu4/FCC/tree/master/8.%20Tic%20Tac%20Toe)

### Day 023: February 06, 2018
**Today's Progress**:
1. [fCC] Pomodoro: Finished project

**Thoughts**
- Nested conditionals to get correct length value (break, break lg or session). 
- Logics for the maxtime value from which is determined the width of the progress bar.
- The code to change the color of the progress bar induced a Bug with val and width when finishing a session.
- Solved the bug. The timerVal kept the previous value because it was outside the scope. 
- Implemented toggleDisplay function (save a few lines and a lot of characters)
- Corrected the timer clock that was not at the bottom of the box (reason: scope of the flexbox)
- Reset logics and styled UI element
- Styled footer.
- CSS cleanup and comment

**Link(s) to work**
1. [fCC - Pomodoro codepen](https://codepen.io/X140hu4/pen/mXyMvg?editors=0100)

### Day 022: February 05, 2018
**Today's Progress**:
1. [fCC] Pomodoro: Finetuning javascript logics

**Thoughts**
First day with evening shift at Alex&resorts. I need to get up earlier to be able to do more coding and reading.
- Worked on nested conditionals to get correct length value (break, break lg or session). Started working on logics for the maxtime value. 
- Changed color of progress bar. Bug with val and width when finishing a session. 

**Link(s) to work**
1. [fCC - Pomodoro codepen](https://codepen.io/X140hu4/pen/mXyMvg?editors=1100)

### Day 021: February 04, 2018
**Today's Progress**:
1. [fCC] Pomodoro: Finished most of the design

**Thoughts**
Had kanji kentei test at 1:30 and finished at 2:40. Went for macdonalds before going to the Brooklyn coffee to work on the pomodoro project.
Worked 5 pomodoros on:
- Refactoring the increaseValue and decraseValue into a unique changeValue function 
- Worked on the progress background in the timer pane. Originally tried with linear-gradient but gradient wouldn't provide a clear demarcation of progress. 
- Used a parent element for the progress bar. Changing the width percentage to show the progress. It makes the progress function also simplier.
- Decided not to use rounded corners as it was hard to manage with the progress bar parent element. The border-radius would be relative to the width of the element, the width starting at 0 and enlarging with time, the borders would overflow the box's borders. Having right angles makes things easier to manage.

**Link(s) to work**
1. [fCC - Pomodoro codepen](https://codepen.io/X140hu4/pen/mXyMvg?editors=1100)

### Day 020: February 03, 2018
**Today's Progress**:
1. [fCC] Pomodoro: Continue designing

**Thoughts**
Worked a bit in the morning and in the afternoon on the design of the pomodoro clock.
- Styled the setting pane with CSS grid. 
- Added a play button on the right side.
- Figured out a way to have a filler that can be manipulated to show the passage of time using a linear-gradient.

**Link(s) to work**
1. [fCC - Pomodoro codepen](https://codepen.io/X140hu4/pen/mXyMvg?editors=1100)

### Day 019: February 02, 2018
**Today's Progress**:
1. [fCC] Pomodoro: Continue designing

**Thoughts**
Had an afternoon shift at work and didn't have the mental energy to do much. Spent one pomodoro on styling the left side of the timer-container.

**Link(s) to work**
1. [fCC - Pomodoro codepen](https://codepen.io/X140hu4/pen/mXyMvg?editors=1100)


### Day 018: February 01, 2018
**Today's Progress**:
1. [fCC] Pomodoro: Continue designing
2. [Codewars] Completed 6 kyu Kata "Perfect Square"

**Thoughts**
Getting a better idea of how to use flexbox and grid to style effectively the different elements without heavily relying on position relative, margins and paddings. However I don't take into account capabilities for responsiveness, I would like to get a good working grasp of positioning properties before pursuing responsiveness with these techniques.

**Link(s) to work**
1. [fCC - Pomodoro codepen](https://codepen.io/X140hu4/pen/mXyMvg?editors=1100)

### Day 017: January 31, 2018
**Today's Progress**:
1. [fCC] Pomodoro: Design search, Wireframe, styling

**Thoughts**
The logics being well advanced, I decided to start making the UI. First, I opened all the website I had for design inspiration in my bookmarks. I found a few nice design and picked a few design concepts I liked. I am going with a landing view to define the settings then start the pomodoro. The pomodoro will then have a bar that will change color/fill with another color as time passes by. I started styling the landing page.

**Link(s) to work**
1. [fCC - Pomodoro codepen](https://codepen.io/X140hu4/pen/mXyMvg?editors=1100)

### Day 016: January 30, 2018
**Today's Progress**:
1. [fCC] Pomodoro: Pause, continue and automatic switch

**Thoughts**
The problem of clearInterval was because of it being declared in the toggle function. I have to be careful of scopes. When designing the automatic switch function with recursion, the management of switch variables caused issues as one was reset at the begining of a new toggle call.

**Link(s) to work**
1. [fCC - Pomodoro codepen](https://codepen.io/X140hu4/pen/mXyMvg)

### Day 015: January 29, 2018
**Today's Progress**:
1. [Portfolio] Tested website with w3C markup validation and Google speed test

**Thoughts**
There are improvements to make with the image sizes. They load fast enough but they could take less space in memory.

**Link(s) to work**
No link!

### Day 014: January 28, 2018
**Today's Progress**:
1. [fCC] Started Pomodoro project
2. [Portfolio] Contact form, languages and scrollspy

**Thoughts**
[fCC] 
- Started pomodoro project
- Manage length of session and break
- Countdown functionality started

[Portfolio]
- Made the contact form work with formspree. Since the submit form was outside the form element, I had to add a JS code to perform the submit on click.
- Translated the portfolio to French and Japanese
- Added a scrollspy functionality when clicking on an internal link or scrolling the page.

**Link(s) to work**
1. [fCC - Pomodoro](https://github.com/X140hu4/FCC/tree/master/6.%20JS%20Calculator)
2. [Portfolio](https://github.com/X140hu4/X140hu4.github.io)

### Day 013: January 27, 2018
**Today's Progress**:
1. [fCC] Finished JS Calculator
2. [WebDevBootcamp] Started JS section

**Thoughts**
[fCC] 
- Finished JS calculator challenge and wrote a post on fCC forums
- Memory management (MRC, M-, M+)
- Handling Percentage 
- Handling CE
- Finish styling of button board

[WebDevBootcamp]
- Finished section 8 to 10. Started Section 11 JS Array Iteration

**Link(s) to work**
1. [fCC - Javascript Calculator](https://codepen.io/X140hu4/pen/QaXMbv)

### Day 012: January 26, 2018
**Today's Progress**:
1. [fCC] Main logics of JS Calculator

**Thoughts**
- [fCC] Wrote the main logics of the JS calculator 
- Addition, substraction, multiplication and division of integer and floats in two cases: showing result when clicking '=' or '+', '-', 'x', '/'.
- Hiding/showing the screen when clicking on ON/C
- handling Square root (no follow up operations yet)

To do:
- Memory management (MRC, M-, M+)
- Handling Percentage 
- Handling CE
- Finish styling of button board

**Link(s) to work**
1. [fCC JS Calculator](https://codepen.io/X140hu4/pen/goNxpa?editors=0100)

### Day 011: January 25, 2018
**Today's Progress**:
1. [fCC] Made the design for the JS Calculator

**Thoughts**
- [fCC] Started the JS calculator project. 
- Started trying with flexbox but it was hard to spread the divs of the input panel equally. [Flexbox free course](https://scrimba.com/g/gflexbox)
- Used CSS grid to space the different elements, in particular the input panel. [Grid free course](https://scrimba.com/c/cbVn4t4)

**Link(s) to work**
1. [fCC JS Calculator](https://codepen.io/X140hu4/pen/goNxpa?editors=0100)

### Day 010: January 24, 2018
**Today's Progress**:
1. [Portfolio] Finished first version

**Thoughts**
- [Portfolio] Finished a first version of the portfolio in English. The contact form is missing its functionality but I couldn't make it work to make a post request. 
- Added color on hover of logos
- Added skills section. I used font awesome 5 as it had icons instead of fa4
- Added actual portfolio content

**Link(s) to work**
1. [Portfolio](https://github.com/X140hu4/X140hu4.github.io)

### Day 009: January 23, 2018
**Today's Progress**:
1. [Portfolio] Worked on portfolio's sections

**Thoughts**
- [Portfolio] Made a hero section, populated and styled it. Found a trick for the internal link from navbar to section of the page. The problem was that when clicking on "My work", the page would go below the Portfolio header. The trick I found and was satisfied with was to have a `<a></a>` tag with a class of anchor with certain properties, including an negative vertical offset.
Added the about section, work in progress. I would need to add the skills section too at some point but I had some issues with the logos having different sizes... I think I would need to resize them first for the screen size and file size so that they don't use too much data on load.

**Link(s) to work**
1. [Portfolio](https://github.com/X140hu4/FCC/tree/master/1.%20Portfolio/Ver_2018_01)

### Day 008: January 22, 2018
**Today's Progress**:
1. [Portfolio] Worked on portfolio's
2. [fCC] Helped campers on gitter and fCC's forum

**Thoughts**
- [Portfolio] I had some trouble with the different navbars and how they should be nested. Managed to get a basic navbar with all the elements I wanted and responsiveness thanks to bootstrap 4.

**Link(s) to work**
1. [Portfolio](https://github.com/X140hu4/FCC/tree/master/1.%20Portfolio/Ver_2018_01)

### Day 007: January 21, 2018
**Today's Progress**:
1. [WebDevBootcamp] Finished Bootstrap

**Thoughts**
- [WebDevBootcamp] 771 (Forms and inputs) 781 (End of Bootstrap chapter)

**Link(s) to work**
No links today!

### Day 006: January 20, 2018
**Today's Progress**:
1. [WebDevBootcamp] Started Bootstrap

**Thoughts**
- [WebDevBootcamp] Finished 547 (Specify and the cascade) 771 (Forms and inputs)

**Link(s) to work**
No links today!

### Day 005: January 19, 2018
**Today's Progress**:
1. [WebDevBootcamp] Started Intro to CSS (Refresh)

**Thoughts**
- [WebDevBootcamp] Finished 435 (Form exercise) to 547 (Specify and the cascade)

**Link(s) to work**
No links today!

### Day 004: January 18, 2018
**Today's Progress**:
1. [Portfolio] Set up of folders
2. [WebDevBootcamp] Refresh HTML knowledge

**Thoughts**
- [Portfolio] Starting setting up the folder structure and the files with some html and styling. I will go with bootstrap to quicken the development process
- [WebDevBootcamp] Started at 317 (Basic tags) stopped at 435 (Form exercise)

**Link(s) to work**
1. [Geckos-36 repo](https://github.com/chingu-voyage3/geckos-26)

### Day 003: January 17, 2018
**Today's Progress**:
1. [geckos-26] Finished CRUD routes
2. [Portfolio] Finished initial wireframing

**Thoughts**
- [Geckos] Issues encountered:
    - Delete route: I wanted to delete the list but also the related cards. The cards' ids are in a cards property of List. I needed to get the list first, then get the cards array and iterate through the cards and delete them. Once the cards are delete the list is deleted. When the cards are deleted their reference in the cards array of list are not.
- [Portfolio] Finished initial wireframing for a one page page. Another idea would be to have the body show only the part selected in the navbar instead of having everything available to scroll?

**Link(s) to work**
1. [Geckos-36 repo](https://github.com/chingu-voyage3/geckos-26)


### Day 002: January 16, 2018
**Today's Progress**:
1. [geckos-26] Worked on create route for new list
2. [Portfolio] Used Evolus Pencil to start wireframing the portfolio site

**Thoughts**

- [Geckos] Issues encountered trying to pass data around for Create List:
    - Get data from the form: Used ref on the input field
    - Access ref from parent component: pass 'hook' via props to the child to assign value to variable in parent
    - post a json request: added a header specifying content-type to be json and assigned JSON.stringify(data) to the body.
Used the article ["CRUD in React and Express (MySQL)"](https://medium.com/@avanthikameenakshi/crud-react-express-99025f03f06e) to kickstart working on fetch post.
[Portfolio] Hands on pencil to start wireframing the portfolio.


**Link(s) to work**
1. [Geckos-36 repo fetchPost branch](https://github.com/chingu-voyage3/geckos-26)

### Day 001: January 15, 2018
**Today's Progress**:
1. [geckos-26] Merged candy's card moving branch. Closed PR and deleted branch.

**Thoughts**

It is a big mess when there are conflicts... I had to loose the props in the subcomponents Lists and Cards.
Also capitalization on file name seems to throw github off when making comparisons between files... So defintely need to be all aligned on no capitalization in name file, and no spaces.


**Link(s) to work**
1. [Geckos-36 repo](https://github.com/chingu-voyage3/geckos-26)
