frontend-nanodegree-arcade-game
===============================
# Title
Arcade Game

## Table of Contents

* [Title](#Title)
* [Instructions](###instructions)
* [Contributing](####contributing)
* [Dependencies](#####Dependencies)

### Instructions
How to load the game
* The repository contains css, images, and js folders, as well as an index.html and a README.md file.
*  Once you have downloaded the files we have provided, you will have to edit app.js to build the game.
* The css folder contains a style.css file 
* The images folder contains the png image files, which are used when displaying the game. 
* The images for the player and enemy character are going to be loaded from this folder.
* The js folder also contains the app engine needed to run the game and a resources.js file.
* index.html - opening index.html should load the game
* The Enemy function, which initiates the Enemy by:
* Loading the image by setting this.sprite to the appropriate image in the image folder (already provided)
* Setting the Enemy initial location (you need to implement)
* Setting the Enemy speed (you need to implement)
* The update method for the Enemy
* Updates the Enemy location (you need to implement)
* Handles collision with the Player (you need to implement)

How to play
* We have a Player and Enemies (Bugs). 
* The goal of the player is to reach the water, without colliding into any one of the enemies. 
* The player can move left, right, up and down.
* Once a the player collides with an enemy, the game is reset and the player moves back to the start square. 
* Once the player reaches the water the game is won..
#### Contributing
* Oject Oriented JavaScript
##### Dependencies
*  <script src="js/resources.js"></script>
*  <script src="js/app.js"></script>
*  <script src="js/engine.js"></script>
*  [object Oriented Javascript] https://javascript.info/object-oriented-programming
* [Objects in depth: Udacity]https://classroom.udacity.com/nanodegrees/nd001/parts/c02fda3b-67bf-48d6-a64f-c6960e2d4d79

