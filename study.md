# Game Project Scope Study

## Required Readings

-   [Game Project](https://github.com/ga-wdi-boston/game-project)
-   [Game API](https://github.com/ga-wdi-boston/game-project-api)
-   [What is a User Story](https://www.mountaingoatsoftware.com/agile/user-stories)

## Deliverables

After reading the `game-project` prompt and the `game-project-api` documentation
please do the following and be prepared to share and discuss during our next
class.

Submit detailed answers to the following in this file via a pull request:

-   A wireframe of what your game project will look like.
-   The data structure you plan to use.
-   How you will take the markup of the game board and represent it in JS
-   How you plan to approach this project.
-   4-8 user stories for your game project.
-   How you plan to keep your code modular.
-   What creative spin will you add to your project?
-   How will you use version control to backup / track your project?
-   Do you plan to attempt any of the bonuses?

You may want to submit pictures for your wireframes and/or user stories.
[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
has instructions to link to a picture you've uploaded to a service like [Imgur]
(http://imgur.com/).



# Initial Wireframe.
Planning began with a wireframe of the site.  This early wireframe included:
 - Placement of elements
 - Game Board
 - Title
 - Buttons (login, new game, etc)

![alt text](http://evolutiontalk.com/images/wireframe_original.jpg "First Wireframe Concept")

The wireframe allowed me to begin with some simple html outlining and, in an effort to remain simple, evolved into a Tic Tac Zen concept.

![alt text](http://evolutiontalk.com/images/ttt_zen.jpg "HTML Concept")

Note that the html design illustrated here is an early-stage design and still contains some div box borders to assist in placement.

# LOGIC
An early attempt at outlining the logic behind the game took the form of a text document that outlined, in simple english, the flow of the game.  This helped to determine the coding that may be involved (knowing full well that it may all change once actual development began!).

![alt text](http://evolutiontalk.com/images/logic_notes.jpeg "Logic Notes")

# DATA
The data will be structured and modeled using a js-template structure.  This will compartmentalize the html, css, and javascript into a structure that will be easy to both manage and interpret.

The GameBoard itself, as represented to the User in html, will be translated into JS using a multi-dimensional array.

# User Stories

- A User will be able to login and create a game.

- A User will be able to click on a square to indicate their move.

- The System will not allow a User to click more than one square furing their turn.

- The System will record the 'moves' performed by a User.

- The System will calculate the winner based on the square's interacted with by each player

# Version Control
Game version will be maintained and managed within a github repository.

# Bonuses

The inclusion of Bonus features will be considered after the completion of the initiial GameBoard delivery.
