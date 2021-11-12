# EpicXOs

Team Name - cashmoney inc

Members:

Moses Luna: (YorkU Email: moseslun@my.yorku.ca, Lecture Section: B, Lab 02)

Kush Naik: (YorkU Email: kush12@my.yorku.ca, Lecture Section: B, Lab 03)

Meththisage Payoe: (YorkU Email: rehanp@my.yorku.ca, Lecture Section: B, Lab 04)


Project Title - Tic Tac Toe

Project Description: 
The website will contain a program that plays a game of tic tac toe between the user and the server. The user will select whether or not they want to use x or o, and if they want to go first or second. The game will start and a 3 by 3 box will be displayed. The user will select a square at the start or after the server depending on the user's previous selection. The server will select a box at random. The sequence of code will continue until the array checks and confirms that the same symbols form a line, and will display a message win or loss which will be determined by the symbol the player chose. If no boxes are left to be selected then the game will be determined to be a stalemate. The user will then be prompted to play again and a win, loss, and stalemate counter will be displayed. 

Additionally, the program will contain two types of game modes: a player vs player system, where using the same pc you will be able to input the names of both people, and then randomly selecting who goes first, and who is x and o. Then there will be the player vs AI system, where the player will input their name, and then select x or o, and whether they want to go first or not, and then will be put up against the AI. There is also planned to be a leaderboard system that will count wins, and will display the wins for both of the gamemodes, and display who is first and second. After each game the player will be asked to play again. (Optional: We can add 2 difficulties for the AI, easy and hard, where the bot will randomly place on easy, and then on hard will try to win against the player every time.)

Functional Requirements:

-During the start of the game, the player will be asked to input their name, and must be 1-20 characters long, which will be displayed during the game.

-The player will not be able to place X or O on an already placed slot.

-The player should be able to click a button to hide/unhide the leaderboard.

-Game Log in order to track who's turn it is, and where the player/AI placed their X or O.

-The leaderboard tracks wins for the player/AI from the start of the game, until player leaves or refreshes the page.

-There must be two options for the player to choose to play: PVP or PVB. Selection is made by clicking one of two buttons: PVP or PVB.

-The player should be able to play again without refreshing the page, by clicking the play again button.

-For PVB, the player should be able to select if they want to be X or O and play first or second by clicking button at start of the game.

-The website will have the game interface in the middle with game log below it, and the leaderboard on the right hand side.

-(Optional: AI works properly on easy and hard difficulties. Selected by clicking easy or hard button.)

-(Optional: Instead of hard difficulties, the AI will scale with the amount of wins the player has.)

Wireframe Descriptions -

Wireframe 1: Asks the player to enter the name they want to play with which will be displayed on the leaderboard. On top of the screen there will be a banner depicting the name of the game and at the bottom it will show the leaderboard, game log and name of the authors.

Wireframe 2: On the next screen if will ask whether the user wants to play singleplayer (player vs computer) or multiplayer (player vs player). If the multiplayer option is chosen, then the second player must also enter the name they want to play under.

Wireframe 3: The first player will get the option on whether they want to move first or second. After, the second player will move based on what option the first player chose.

Wireframe 4: This is the screen where the game is actually played. The first player will be "O's" and the second player will "X's". It will keep asking for the players to make their turns until a winner is determined (3 of the same sign either vertically, horizontally or diagonally). The game log will also be updated according to each move made so it is clear on whos turn it is to go.

Wireframe 5: Once a winner is determined, it will be outputted on the screen saying either "P1 wins", "P2 wins" or "no winner" (tie). The leaderboard on the bottom left will also be updated accordingly to track who has more overall wins.
