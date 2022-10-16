Assignment 3 - Sistemas Inteligentes 


Collaborators:Karen Melanie Sasari Alborta - Antonio Medina Padilla
    
Introduction
The project is to program the game "Teeko" so that the computer plays intelligently

The game starts with an empty board on which the player with the black pieces starts by placing the first piece and then the second player until the board has 8 pieces, 4 red and 4 black.
![Teeko_board](https://user-images.githubusercontent.com/53119069/196014725-0df4dd16-88ec-4084-9994-9658e61567af.jpg)
The game continues in phase 2, with the 8 tiles, the player with the black tiles gets to move one to an available place and then it will be the turn of the other player, until there is a winner.
The winner will be the player who has collected the four consecutive tiles (in horizontal line, in vertical line, in diagonal and in square).
for more information about the rules: https://bonaludo.com/2016/07/27/teeko-a-game-and-a-masterpiece-of-john-scarne-the-wizard-of-games/

Solution
Heuristic
It was proposed to use a heuristic that in addition to calculating the sum by rows also weights the cards that are together by rows, thus leaving the following formula that we proposed:

Eval-Rows=sum(1 in row)* sum( 1s consecutives)- sum(-1 in row)* sum( -1s consecutives)

![Heuristic1](https://user-images.githubusercontent.com/53119069/196014667-251baec5-4e98-41c1-ab02-db3e5529f7d9.jpg)


