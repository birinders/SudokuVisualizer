# Sudoku Visualizer
## Getting Started-
- Run ```git clone https://github.com/birinders/SudokuVisualizer.git``` OR<br>
- Download the Source code from the "Releases" section.
----------------------------
This is a Sudoku Visualizer implemented inside python. It uses the terminal to visualize how backtracking works for such a seemingly complex problem.

The board shows how each and every state gets tested, and how the program backtracks upon finding a invalid state.
This works as a great learning tool, and a visual aid for people who may still be learning their data structures and algorithms, and may find it hard to conceptualize how backtracking actually works, or what does it exactly do inside the program.
<br><br>
You can either watch the program solve an extremely hard preset board, or give it your own board by modifying the [Board.py](/Board.py) file.

Make sure you provide the algorithm with a valid board, since remember-<br><br>
The board is a 9x9 grid with a total of 81 squares.<br>
Each square can have upto 9 values in a filled board.<br>
This gives us ```9*9*9*9.....77 more times == 9^81``` possible valid board states.<br><br>
This number evaluates to ```196627050475552913618075908526912116283103450944214766927315415537966391196809``` possible board states, which is clearly beyond the means of what my computer can possibly compute within my lifespan. (Maybe yours would be able to do it, but I have my doubts)

### Exercise to the reader!
Try and implment a function called ```is_board_valid(board)``` which can detect if a board is invalid even before the backtracking search begins. If the board is invalid, just print "Invalid Board" and exit the program.
<br><br>Do this, and publish a pull request for your changes. Maybe I'll merge your solution with this project!
<br><br>
## Watch it run!
You can check out my other visualizers [here](https://birinders.github.io).

