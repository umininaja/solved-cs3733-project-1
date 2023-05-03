Download Link: https://assignmentchef.com/product/solved-cs3733-project-1
<br>
<span class="kksr-muted">Rate this product</span>




Your task is to develop a small standalone application in Java to enable a user to play a mathematical game on a 3×3 grid of tiles where each tile can contain a positive integer.

The goal is to reduce 9 integers into a single value in the center of the grid, using a sequence of moves. Each move consists of a starting tile containing a number and a target tile containing a number. If the move is valid, the starting tile is cleared and the target tile is recomputed, as follows:

Move Right to add: Move 1 right to 7, to add 1 to 7, resulting in 1+7 = 8Move Left to subtract: Move 4 left to 6, to subtract 4 from 6, resulting in 6 – 4 = 2Move Up to multiply: Move 5 up to 7, to multiply 7 by 5, resulting in 5 x 7 = 35Move Down to divide: Move 1 down to 2, to divide 1 into 2, resulting in 2 ̧ 1 = 2; valid only if the result is an integer

One solution above is: Move 3 Right, Move 2 Up, Move 2 Right, Move 5 Up, Move 8 Up, Move 4 Down, Move 18 Left, Move 9 Down. Solution!

When you start your application, the puzzle will be in its initial state. Note there are four possible starting configurations, and each student will be assigned one for this project (see initial configurations in Canvas).

From this initial state, the user can quit the application or reset the puzzle to its original configuration. Moving a tile is a two-step operation. First, the user uses the mouse to select a starting tile by clicking on it. Next the user requests to move the tile either up, down, left, or right one square (this could be done by

https://canvas.wpi.edu/courses/22068/assignments/142719 1/2

6/2/2021 Assignment IP.1

detecting the key press of one of the arrow keys, or you could have four buttons for up, down, left, or right, or you could do a drag/swipe action which is a bit complicated in Java). Naturally only valid moves should be allowed.

When only the center tile contains a value, the user has won, and should be congratulated! If the user has not won and is unable to make a valid move, the user has lost, and should be consoled.

IP.1 Due Thursday October 29th at 1:00 PM (5% of total

grade)

The first deliverable is due in the second week of the course. This deliverable will contain: