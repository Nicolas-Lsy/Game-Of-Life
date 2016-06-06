# Conway-s-Game-of-Life
The basics of the Python language by coding a simple implementation of Conway's Game of Life.

Game of Life Overview

"Game of Life" board will be an n-by-n grid of square cells, each of which can be either "alive" or "dead". A given cell's neighbors are those cells directly above, below, left, or right of the cell, plus with the cells diagonally adjacent to it (the cells touching its diagonals). Each cell changes from one time step to the next according to the following rules:

Any living cell with fewer than two living neighbors dies.
Any living cell with exactly two or exactly three living neighbors remains alive.
Any living cell with more than three living neighbors dies.
Any dead cell with exactly three living neighbors becomes alive.

《生命游戏》简单介绍

“生命游戏”建立在一个N乘N的正方形格子中，每个细胞有“生”或“死”两种状态。每个细胞的邻居是指它上下左右以及对角线的其他细胞。细胞会按照一定步骤发生变化，具体规则如下：

1.任何细胞少于两个活的邻居，过于孤独，则细胞死。
2.任何细胞有两个或三个活的邻居，正常生活，则细胞活。
3.任何细胞超过三个活的邻居，过于拥挤，则细胞死。
4.任何死了的细胞周围如果有三个活的邻居，则细胞复活。
