# game-proposal
JS Project Proposal: slither.io

Background

slither.io is a variation on the classic snake game. Players play against each other in a live battlefield instead of against themselves:

If a player runs into another player, they die and their remains can be eaten
Eating the remains of another player makes you grow
Players of any size can be taken down if they run into another player, allowing for quick changes in the playing field

Functionality & MVP

Users will be able to:

 Start, pause, and restart the game
 Navigate by having their snake/worm follow their mouse
 Choose different colors for their snake
 Hold down the mouse to get a temporary burst of speed
In addition, this project will include:

 An About modal describing the background and rules of the game
 A production README
 
 Architecture and Technologies

This project will be implemented with the following technologies:

JavaScript/HTML5 Canvas for game logic and rendering.
A simple rails backend to keep track of users scores 
In addition to the entry file, there will be three scripts involved in this project:

board.js: this script will handle the logic for creating and updating the necessary elements and rendering them to the DOM.

snake.js: this script will handle the logic of handling snake movements and actions, responding to user input, etc

game.js: this will handle the higher level actions related to running the game, i.e. starting stopping, running the event loop, etc.
