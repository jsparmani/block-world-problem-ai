# Blocks World AI

A basic AI that solves the Blocks World Problem using searching algorithms.
Built in Python 3.8.

### Searching algorithms

* Depth First Search (DFS)
* Breadth First Search (BFS) 
* Depth Limited Search (BFS) 
* Iterative Deepening (BFS) 

A* and Best First chose the state with the smallest heuristic value.

### Running the program

The program takes 3 command line arguments:

* Search algorithm: depth/breadth/limited/itdeep
* Problem file name: Choose a .txt file from the problems folder.
* Solution file name: Optional. If it's not specified the solution will be
    saved in a folder called solutions.

To run it simply type in your terminal the following command:
```
python main.py depth ./problems/Q1.txt
python main.py breadth ./problems/Q2.txt
python main.py limited ./problems/Q3.txt
python main.py itdeep ./problems/Q4.txt
```
