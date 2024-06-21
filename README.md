# Dijkstra-Algorithm-Implementation
Finding shortest path using Dijkshtra Algorithm in python. 

# Required Libraries

!pip install numpy matplotlib ipywidgets ipython

# steps to run this program
Open google collab
create new repository
copy this code and run in the cell
Enter the all required input like - starting point, goals, and obastcles.
click on run Dijkshtra button and wait few minutes output will be printing soon with drone moving animation.


# Explanation
Grid Creation: The create_grid function generates a 3D grid within the specified bounds.
Node Class: The Node class represents each point in the grid with a position and cost. The cost is used for Dijkstra's algorithm.
Dijkstra's Algorithm: The dijkstra function performs the pathfinding using Dijkstra's algorithm.
Collision Checking: The is_collision_free function checks if a node is free from obstacles.
UI Integration: The UI elements and event handling for user input are included as before.
By running the provided code in Google Colab, you should be able to input the start point, goal, and obstacles, and see the drone move along the path found by Dijkstra's algorithm. Adjust the inputs as needed for your specific scenarios.


