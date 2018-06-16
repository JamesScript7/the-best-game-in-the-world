# The Best Game in the World

_Skills: React_
![Main image of menu and board](https://raw.githubusercontent.com/JamesScript7/the-best-game-in-the-world/master/public/images/rules/main.png)

At each turn of the game (example shown with the center cell):

* Any populated cell with fewer than two neighbors becomes empty.
_Before:_
![Rule 1 before image](https://raw.githubusercontent.com/JamesScript7/the-best-game-in-the-world/master/public/images/rules/1-before.png)
_After:_
![Rule 1 before image](https://raw.githubusercontent.com/JamesScript7/the-best-game-in-the-world/master/public/images/rules/1-after.png)
* Any populated cell with two or three neighbors stays populated.
_No Change:_
![Rule 2 no change image](https://raw.githubusercontent.com/JamesScript7/the-best-game-in-the-world/master/public/images/rules/2-nochange.png)
* Any populated cell with more than three neighbors becomes empty.
_Before:_
![Rule 3 before image](https://raw.githubusercontent.com/JamesScript7/the-best-game-in-the-world/master/public/images/rules/3-before.png)
_After:_
![Rule 3 after image](https://raw.githubusercontent.com/JamesScript7/the-best-game-in-the-world/master/public/images/rules/3-after.png)
* Any empty cell with exactly three or six neighbors becomes populated.
_Before:_
![Rule 4 before image](https://raw.githubusercontent.com/JamesScript7/the-best-game-in-the-world/master/public/images/rules/4-before.png)
_After:_
![Rule 4 before image](https://raw.githubusercontent.com/JamesScript7/the-best-game-in-the-world/master/public/images/rules/4-after.png)

## To start The Best Game in the World:

```
npm i
npm start
```

Then click __START__ in the menu bar to initiate the game!

_Notes on button behavior:_

Once __START__ button is clicked it will remain locked until the
__RESET__ button is clicked. The __PAUSE__ and __RESUME__ button
are locked initially but when the __START__ button is clicked, you
are able to toggle between __PAUSE__ and __RESUME__. The __RESET__
button can be clicked at any point of the game to stop and restore the initial game state.
