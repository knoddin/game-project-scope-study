# Game Project Scope Study

## Required Readings

-   [Game Project](https://github.com/ga-wdi-boston/game-project)
-   [Game API](https://github.com/ga-wdi-boston/game-project-api)
-   [What is a User Story](http://searchsoftwarequality.techtarget.com/definition/user-story)

## Deliverables

After reading the `game-project` prompt and the `game-project-api` documentation
please do the following and be prepared to share and discuss during our next
class.

Submit detailed answers to these in this file via a pull request.

-   A wireframe of what your game project will look like.
  I am beginning on paper and moving to
  gomockingbird.com -- https://gomockingbird.com/projects/gf7murv

-   The data structure you plan to use.
Data will be stored in our own game project API, which will store players' game state and also
has the ability to allow two players to compete from separate computers. My main plan is to utilize the
former, to store player information and be able to retrieve it (objects including user and game).

JQuery will be utilized to make the page more seamless

-   How you will take the markup of the game board and represent it in JS
    The game structure will be built using HTML5. It will link to JS pages that
    will contain the game events and functionality. JQuery will be used to make the JS code
    writing easier.

-   How you plan to approach this project.

I plan to approach this project very systematically. I will start with wireframes and user stories to get a solid idea of what I want the functionality to be and what I want the game to look like. I will then begin creating modular folders to store specific information and functionality/code for the game. I will then set up my game structure using HTML. I will then focus on creating necessary buttons and authorization click functions, including sign-up, sign-in, changing password, and using JavaScript. I will then focus on the game theory itself and how JavaScript code will be written to make the game work (e.g. how does a new game start? what happens with each click on the tic tac toe grid? how is a winner determined? how is a loser determined? what if nobody wins?). I will communicate with the API using AJAX/JQuery to get and post data on users and scoring. Throughout each piece of code written, I will test using curl requests to see that the code that I am writing is doing what I want it to do and to get a sense of what the user interaction will be like without actually having user interaction.

-   4-8 user stories for your game project.

  1) As a user, I can create an account with name, email, password, and password
    confirmation.
  2) As a user, I can login to my account to access stored information like saved
    games and game history.
  3) As a user, I can click on a "play game" button to begin a new tic tac toe game.
  4) As a user, I can click on the game grid to unveil X or O during play.
  5) As a user, I can click on "save game" to save and continue playing later.
  6) As a user, wins will be determined and alerted to meautomatically upon completion of "3 in a row".
  7) As a user, I will be able to see whose turn it is - X or O? Mine or theirs?
  8) As a user, I will be able to change my password.

-   How you plan to keep your code modular.

  I plan to keep my code modular by separating pieces of code by their functionality. The main HTML page, which will provide the structure of the page, will be kept as a separate file, called index.html. CSS file(s) will be kept in a separate "Styles" sub-folder. JavaScript files will then be contained depending on their own functionality and event types. Authorizations (like sign up, sign-in, sign-out) will be kept in a specific "authorizations" sub-folder. JS functions for actual
  game play will be kept in a lateral "game-play" sub-folder. UI functionality will have its own files/sub-folder. API file/locations will have their own sub-folder. Curl requests will be kept in their own folder to be copied and pasted to check that data are being entered and stored properly on the API.

-   What creative spin will you add to your project.

    I would like to include charts if possible to show wins and losses over time.

-   How you will use version control to backup / track your project.

    I will be using GitHub and my own game repository to manage version control. I will be committing early and often throughout the process.

-   Do you plan to attempt any of the bonuses.

    I would love to attempt them if I get that far. The plan is to finish the requirements and to have
    a nice looking and functional game, then tackle bonuses if there is time.
