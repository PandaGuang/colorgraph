Overview

This work is doing the implementation of the graph coloring with greedy algorithm, the problem is to color the nodes of a graph with the constraint that two nodes connected by the same edge cannot be same color. 

Input (Standard input): Includes multiples lines. The first line contains two integers $n$ and $m$ that correspond to the number of nodes and edges, respectively. Each of the following `m` lines contain two integers `u` and `v`, separated by one space, to denote an edge from u to v. Nodes are numbered from 1 to n. The last line contains n integers that are the colors of the nodes. Uncolored nodes are indicated with color 0.

Output (Standard output): The first line contains an integer `D` that is the number of additional colors needed to color all the uncolored nodes in the graph. The next line contains n positive integers that are colors of the nodes.


How to use

1 to build:

1.1 installl boost
 ubuntu: `sudo apt install libboost-all-dev`
 mac: `brew install boost`

1.2 compile
```mkdir build && cd build`
  cmake ..`
  make
  ```


2 to run:

`cd bin/`

`./main 9`  #run the program on randomly generated graph with size 9
`./main (pull a txt file here)`  #run the program on the graph in the txt file
