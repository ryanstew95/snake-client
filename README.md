#Snake Client Project
Snake game is a very popular video game. It is a video game concept where the player maneuvers a dot and grows it by ‘eating’ pieces of food. As it moves and eats, it grows and the growing snake becomes an obstacle to smooth maneuvers. The goal is to grow it to become as big as possible without bumping into the side walls, or bumping into itself, upon which it dies.

This is simply a multiplayer take on the genre.

Before you can run this client, you will need to be running the server side which you can download and install from here.

##Purpose
This project was made by Ryan Stewart and was conducted as part of the Lighthouse Labs Web Development Flex Program curriculum.

##Credits
This game is inspired by the game Snek created by Tania Rascia. The server code for this game was not written from scratch - it is a refashioned version of Rascia's game.

##Final Product

<img width="1470" alt="snek_game" src="https://github.com/ryanstew95/snake-client/assets/127888213/06408074-4212-4f39-a8dd-c14d73dbd336">

##Instructions
-Enter these commands in your terminal to start up server side
`git clone https://github.com/lighthouse-labs/snek-multiplayer.git`
`cd snek-multiplayer`
`npm install`
`npm run play`
-Run the development snake client using the node `play.js` command.
-Use your `WASD` keys to navigate your snake up, down, left, or right.
-Use your numbered keys `1, 2, 3, 4, 5` to send banter messages when playing with other players.
  `1`: "Good Move!",
  `2`: "HAHA you died!",
  `3`: "I'm in the lead",
  `4`: "GG!",
  `5`: "Hello"
-Eat the red dots to grow your snake and gain points.
-Avoid colliding into the walls or into your own tail, otherwise, it's game over.
-Press `CTRL + C` to quit the game.
-If you get game over you need to quit `CTRL + C` and re-enter `play.js`.
