# COT4400 Analysis of Algorithm Final Project

## Description of task
This program finds the cheapest solution to the 8-puzzle using BFS, DFS, and Dijkstra algorithms.

##Overview 
The game has 8 tiles, shaped in a 3x3 grid, where the numbers are 1 through 8. There is one gap in the puzzle that allows movement of the tiles. 
For BFS and DFS algorithm, every one tile moving, has a cost of 1. They may move, left, up, right, and down.
For Dijkstra Algorithm, the cost is the number that represent a tile that moves plus the number of displaced tiles.

## Steps to compile and execute code files
The puzzle is provided in the input.txt file. The format of the puzzle can be changed in the input.txt file, or more puzzles can be added to it. 
The format for encoding puzzle is as follows:

  ![Screenshot 2022-04-19 180324](https://user-images.githubusercontent.com/70492660/164109247-9a16e08a-cfa8-4bcd-9367-37abd4224a77.png)

The tiles must be digits from 0 to 8, where 0 represents a blank space, and no digits may be repeated in one puzzle. 

To execute the code, you may run the following command prompt: ./out

