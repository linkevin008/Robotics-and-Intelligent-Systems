# Path Planning Algorithms

For a school project led by Professor Daniel Meger.

Contained in these two files are two path planning algorithms, A* (A modified dijkstra) and RRT (Rapidly exploring Random Trees). 

The algorithms take a simple image (such as "simple.png") and considers the dark pixels as obstacles that cannot be traversed, while the white pixels are available and navigatiable. 

Within the code is a start location and a goal location (defined by pixel x pixel on the given image). The respective algorithm will create a path or attempt to create a path from the start position to the target location and produce a map of its results.

To run a file

`python3 astar_planner.py simple.png` 

or 

`python3 rrt_planner.py simple.png`

with the proper modules.
