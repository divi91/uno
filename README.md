# uno
This is a uno game for learning, this is built on node. 

Dependencies:  Express, Socket.IO

To start the app - Open terminal and use either of Node start or node app.js commands.
    - change directory in terminal to the uno-master folder
    - npm start

Open the dealer page (anyone can be dealer along with being a player) - localhost:5000
Each player should open the player page (the dealer should open this in a new tab) - localhost:5000/player

All the players should add themselves (Add Me button), and then the dealer should start the game by distributing cards (Distribute button) and flipping one card on the board (FlipOne button).
The game can then be played like a normal uno game.

Player's Page: localhost:5000/player
Features:
1. Enter your name and click on the Add Me button
2. Wait for the Dealer to distribute the cards.
3. Double click on the card under My Cards area to play the card.
4. You can double click on the last played card to undo the move.
5. Double click on the card deck above to draw a card.
6. In the Player Cards area, the arrow to the right of names indicates the direction of play, it reverses on playing a reverse card.
7. Last played player name will be highlighted.
8. To declare Uno (only 1 card left) click on the Uno button.
9. To check a player (who did not declare Uno with 1 card left) click on the check button.
10. If someone Checks you before you declare Uno, you will be penalized (as per your own playing rules).
11. Chat - to chat with other players, type a message in the box and click Send. You can also click on Slap button for fun.


Dealer's Page: localhost:5000
Features:
1. Shuffle cards
2. Distribute cards - 7 cards to each player
3. Flip one card to initiate play
4. Reset the game. This will take all cards from player and put it into card deck, player's list will be intact and game can be initiated with same players.
5. Restart Game - This is to completely restart a new game, players will have to register again, this can be used if a player wants to be removed.
