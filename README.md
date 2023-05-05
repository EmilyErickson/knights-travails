# knights-travails

This is a project from the Odin Project's Javascript course. The goal was to create a function that will find the shortest path a knight could take between two squares on an 8x8 chessboard.

The function goes through the steps as follows.

- It takes two coordinates
- Finds all possible moves the knight could make
- Removes any moves that would go off the board
- Starts at the first coordinate and adds all possible moves from that square to a queue
- Visits each move in the queue, adding all possible moves to the queue, until it reaches the desired square.
