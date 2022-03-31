# 15-Puzzle

Java implementation of a program which solves the 15-Puzzle problem using  A* search Algorithm  showing each step of the solution and the amount of moves once it solves the puzzle.


The input for the program should consist of 16 numbers(0-15) with spaces wherein "0" indicates the blank space in a 4x4 board.

## Running the 15-Puzzle Program

This project was tested on VS Code with a java version "17.0.2" 2022-01-18 LTS. To run the program, type in
the command

```
javac fifteenPuzzle.java

java fifteenPuzzle.java
```

The program will ask to input the Start State/Initial State of 16 numbers from 0 to 15 where 0 is the blank space, then will display the
steps of solving the 15 puzzle by A* Algorithm and will display the total # of moves at the end of the solution.

## Sample outputs
```
Enter the start state(15 numbers with spaces): 5 1 4 8 7 0 2 11 9 3 14 10 6 13 15 12
Finding solution for:
5 1 4 8 
7 0 2 11 
9 3 14 10 
6 13 15 12 

Solution found!    
-------START-------
1:
5 1 4 8
7 3 2 11
9 0 14 10
6 13 15 12

2:
5 1 4 8
7 3 2 11
9 14 0 10
6 13 15 12

3:
5 1 4 8
7 3 2 11
9 14 10 0
6 13 15 12

4:
5 1 4 8
7 3 2 0
9 14 10 11
6 13 15 12

5:
5 1 4 0
7 3 2 8
9 14 10 11
6 13 15 12

6:
5 1 0 4
7 3 2 8
9 14 10 11
6 13 15 12

7:
5 1 2 4
7 3 0 8
9 14 10 11
6 13 15 12

8:
5 1 2 4
7 0 3 8
9 14 10 11
6 13 15 12

9:
5 1 2 4
0 7 3 8
9 14 10 11
6 13 15 12

10:
5 1 2 4
9 7 3 8
0 14 10 11
6 13 15 12

11:
5 1 2 4
9 7 3 8
6 14 10 11
0 13 15 12

12:
5 1 2 4
9 7 3 8
6 14 10 11
13 0 15 12

13:
5 1 2 4
9 7 3 8
6 0 10 11
13 14 15 12

14:
5 1 2 4
9 7 3 8
0 6 10 11
13 14 15 12

15:
5 1 2 4
0 7 3 8
9 6 10 11
13 14 15 12

16:
0 1 2 4
5 7 3 8
9 6 10 11
13 14 15 12

17:
1 0 2 4
5 7 3 8
9 6 10 11
13 14 15 12

18:
1 2 0 4
5 7 3 8
9 6 10 11
13 14 15 12

19:
1 2 3 4
5 7 0 8
9 6 10 11
13 14 15 12

20:
1 2 3 4
5 0 7 8
9 6 10 11
13 14 15 12

21:
1 2 3 4
5 6 7 8
9 0 10 11
13 14 15 12

22:
1 2 3 4
5 6 7 8
9 10 0 11
13 14 15 12

23:
1 2 3 4
5 6 7 8
9 10 11 0
13 14 15 12

24:
1 2 3 4
5 6 7 8
9 10 11 12
13 14 15 0

-------END-------


Total # of moves:24
```
