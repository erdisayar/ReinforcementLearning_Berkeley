# pacman
UC Berkeley CS188 Intro to AI 

<img src="/media/maze.png" height="500" width="600">


Introduction
These projects are from [UC Berkeley CS 188](http://ai.berkeley.edu/project_overview.html)


There are 2 different projects in this repository.1st project is about search and 2nd project is about reinforcement learning.


In 1st project, the Pacman agent will find paths through his maze world which is based on search algorithms such as DFS , BFS, UCS, ASTAR.
To understand the mechanism, the tiny maze is used and simple run the [pacman.py](https://github.com/erdisayar/pacman/blob/master/search/pacman.py).It will open automatically the tinymaze map and agent will find its path base on dfs algorithm.The analysis of this search in tinymaze is written in this [figure](https://github.com/erdisayar/pacman/blob/master/search/documents/IMG_20200113_161547.jpg)


To run the pacman in console, please remove the code below from the [pacman.py](https://github.com/erdisayar/pacman/blob/master/search/pacman.py)
<<<<<<< HEAD
=======

```sh
input_parameters = ['-l', 'bigMaze', '-z', '.5', '-p', 'SearchAgent', '-a', 'fn=dfs']
```
>>>>>>> 4f9aa9e83412b580bda2fec62b4bad54c7eca696

```sh
input_parameters = ['-l', 'bigMaze', '-z', '.5', '-p', 'SearchAgent', '-a', 'fn=dfs']
```

[![Alt text](https://img.youtube.com/vi/VID/0.jpg)](https://www.youtube.com/watch?v=VID)

## Depth First Search(DFS)
<<<<<<< HEAD
<img src="media/bigmaze_DFS.png" height="450" width="450">

```sh
 python pacman.py -l bigMaze -z .5 -p SearchAgent -a fn=dfs
```
## Breadth First Search(BFS)
<img src="media/bigmaze_BFS.png" height="450" width="450">

```sh
python pacman.py -l bigMaze -p SearchAgent -a fn=bfs -z .5
```
=======
<img src="media/bigmaze_DFS.png" height="400" width="542">
```
$ python pacman.py -l bigMaze -z .5 -p SearchAgent -a fn=dfs

## Breadth First Search(BFS)
<img src="media/bigmaze_BFS.png" height="400" width="542">
```
$ python pacman.py -l bigMaze -p SearchAgent -a fn=bfs -z .5

## Uniform Cost Search (UCS)
<img src="media/bigmaze_ucs.png" height="400" width="542">
```
$ python pacman.py -l bigMaze -p SearchAgent -a fn=ucs

## A* Search

<img src="media/bigmaze_astar.png" height="400" width="542">
```
$ python pacman.py -l bigMaze -z .5 -p SearchAgent -a fn=astar,heuristic=manhattanHeuristic
>>>>>>> 4f9aa9e83412b580bda2fec62b4bad54c7eca696

## Uniform Cost Search (UCS)
<img src="media/bigmaze_ucs.png" height="450" width="450">

```sh
python pacman.py -l bigMaze -p SearchAgent -a fn=ucs
```

## A* Search
<img src="media/bigmaze_astar.png" height="450" width="450">

```sh
python pacman.py -l bigMaze -z .5 -p SearchAgent -a fn=astar,heuristic=manhattanHeuristic
```

- DFS, BFS, UCS, ASTAR, ASTAR heuristic 
```
$ python pacman.py -l bigMaze -z .5 -p SearchAgent -a fn=dfs
$ python pacman.py -l bigMaze -p SearchAgent -a fn=bfs -z .5
<<<<<<< HEAD
```


## REINFORCEMENT LEARNING


## Q-LEARNING
[![](http://img.youtube.com/vi/vj7c6t9Eb5w/0.jpg)](http://www.youtube.com/watch?v=vj7c6t9Eb5w "")

## CRAWLER

[![Alt text](https://i9.ytimg.com/vi/X9o_uLF4Goc/mq2.jpg?sqp=CN7lofEF&rs=AOn4CLB4YOEzErUQ8nn7N-BA-f-2z9_ShQ)](https://youtu.be/X9o_uLF4Goc)

## PACMAN
=======


>>>>>>> 4f9aa9e83412b580bda2fec62b4bad54c7eca696

[![](http://img.youtube.com/vi/-CDq9vIAwds/0.jpg)](http://www.youtube.com/watch?v=-CDq9vIAwds "")
