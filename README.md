# 2048game

Clone of 2048 game<br>
http://2048game.com/<br>

- TG 04/06/2015(modifed oct/2015)<br>

- project for PoC course by Rice University:<br>
https://www.coursera.org/course/principlescomputing1<br>
- 2048 template:<br>
http://www.codeskulptor.org/#poc_2048_template.py<br>

- graphical user interface "GUI class" provided by instructors and modified by TG (add game instruction)<br>

<p>
!!!! NOTE !!!!
This is PYTHON code written to work in codeskulptor, w'll work in PYTHON 2.X after some changes
Code from text file must be copied and paste into codeskulptor editor: http://www.codeskulptor.org/
popup windows must be enabled
</p>

<p>
<strong>2048</strong> is a simple grid-based numbers game. 
The object of the game is to combine tiles with the same
number to make larger numbered tiles. You "win" when you 
create a 2048 tile.
You will have a grid of 16 tiles (which can be modify 
in this implementation) and two numbers on start: '2' 90% 
of the time and '4' 10% of the time. On each turn, you may 
slide all of the tiles on the board in one direction 
(left, right, up, or down).When you do so, all of the 
tiles on the board slide as far as they can go in the 
given direction leaving no empty squares between the tiles.
Further, if two tiles of the same number end up next to 
each other, they merge to form a new tile with twice the 
value. If any tile slide, new random tile will be given 
with the same manner as on start.If no tiles would combine
or slide in a given direction, then that is not a legal 
move, and you cannot make that move on the current turn.
If there are no free tiles on the grid, the game ends.
</p>

<h3>2048 - HOW TO PLAY?</h3>

- enable pop-up windows!!
- use arrows to slide tiles
- hit 'New Game' button to reset Game
- hit 'How to Play' button to see Game instruction
- hit 'Back to Game' button to hide Game instruction

- change grid size
'2' <= HEIGHT, WIDTH <= '10' # not tested above '10'

-Hit PLAY icon to Start
(left top corner)
