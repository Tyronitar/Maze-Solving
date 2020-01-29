<h1>Random Maze Creation and Subsequent Solving</h1>
Recursively generates mazes and employs various path-finding algorithms to solve the maze. Also visualizes the maze-solving as it happens.

<h2>Requirements</h2>
 
 - Python 3.x
 
<h2>General Information</h2>
The mazes that are generated by this code always have one solution, so they aren't terribly useful for comparing the different algorithms. To satisfy this, I created what I call "broken mazes" which is basically a normal maze, but it deletes extra walls such that there are muliple ways to solve it. This allows different algorithims to find different paths. This allows you to actually notice differences in the algorithims and how they find solve the maze. Finally, there are "empty mazes" which have no internal walls at all.
 
 <h2>Pathfinding Algorithms Used</h2>
 
 - Depth-First Search - does <b><i>not</i></b> guarantee the shortest path.
 - Dijkstra's Algorithm - guarantees shortest path
 - A* Search - guarantees shortest path

I plan to add more algorithms in the future.
