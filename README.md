# Battleship
Battleship is the game developed in contribution with Maciej Korczak (maciej-kor user).

The game itself is classic battleship player versus player game. Your objective is to destroy all of the hostile ships before
your opponent does it. All you have to do is shoot position on 10 x 10 map. If you hit hostile ship you can make second shot.
But if you miss, next move belongs to your opponent. Game ends when all 10 ships are destroyed.

At the beginning you need to input names of players

First screen:
![](https://github.com/Podkov/battleship/blob/master/src/main/resources/view/screen/startPanel.jpg?raw=true "Starting Screen")

When you are done with that you can step forward by clicking "START". Now you should see the legend for the game like on the screen below.

Second screen:
![](https://github.com/Podkov/battleship/blob/master/src/main/resources/view/screen/legendPanel.jpg?raw=true "Legend Screen")

If everything is clear you can click "NEXT" button. It is time to deploy your ships. Second player needs to turn around and the First one needs to click "RANDOM" button to randomly deploy ships. If setting doesn't match to your expectations then you can shuffle it once again by clicking another time "RANDOM" button. If the ships are finally on your lucky possitions then you can click "NEXT" button for deploy screen of Second player. Ships are generated randomly with minimum of one field space. There will always be 10 ships: 1 x four segment ship, 2 x three segment ships, 3 x two segment ships and 4 x single segment ships. All ships could be only in horizontal or vertical setting.
 
Third and fourth screen:
![](https://github.com/Podkov/battleship/blob/master/src/main/resources/view/screen/randomShipsPanel.jpg?raw=true "Deploy Screen")

If both players set their ships "NEXT" button will start the game randomly picking starting player. Now all you have to do is shoot enemy's fields trying to hit hostile ship. You can shoot one field only once, the game will prevent you from losing your moves trying to hit the same field. But you have to remember about 1 field space between ships.

Fifth screen:
![](https://github.com/Podkov/battleship/blob/master/src/main/resources/view/screen/gamePanel.jpg?raw=true "Game Screen")

When one player lose all of his ships you will be moved to the last screen which shows who won the game.

Sixth screen:
![](https://github.com/Podkov/battleship/blob/master/src/main/resources/view/screen/winnerPanel.jpg?raw=true "Winner Screen")

On almost every stage you can close the game by clicking "EXIT" button. While you start the match the only way to leave is to use window closing button ("X").

Technologies and patterns used in project:
- MVC - Model View Controller. Every class in project was implemented using this software design pattern
- Swing GUI - Whole game frontend is based on Swing GUI
- Music control is implemented using AudioInputStream from javax

Music and background images are not ours.

Made by Maciej Korczak and Maciej Podkowa.
