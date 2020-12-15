# JPS
Course project on heuristic planning - implementation of Jump Point Search, Canonical A*, Bounded JPS. Results presented at the end of the notebook. 

Algorithms implementation presented in functions JumpAStar, CanonicalAStar, BoundedJumpAStar, AStar in JumpPointSearch.ipynb. As input, every function demands grid cart, coordinates of start and goal node, heuristic function. BoundedJumpAStar also has an integer bound parameter. Examples of grid maps and tasks for them could be found in the Data folder - in this project used maps and tasks format from MovingAILab. All these tasks and maps are processed in the MassiveTest function, and after processing returns algorithm info - length of the path, is path optimal, etc.

Benchmarks were taken from the MovingAILab page - https://movingai.com/benchmarks/grids.html.
