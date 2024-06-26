# Micromouse-Robot
A repository to maintain and collaborate on the code for the summer intern project Micromouse Robot

## Objective:
The objective of the micromouse project was to design a robot that autonomously navigates a grid maze and identifies the shortest path from the start cell to the goal cell. This project integrated sophisticated graph algorithms to enhance pathfinding efficiency.

## Software Phase:
The software phase of the project focused on the exploration and implementation of several search algorithms, including:
-Breadth-First Search (BFS): Ensured the shortest path in an unweighted grid by exploring all neighboring nodes at the present depth before proceeding to the next depth level.
-Depth-First Search (DFS): Examined all possible paths by exploring as far as possible along each branch before backtracking.
-Wall Follower: A heuristic approach where the robot navigates by keeping in contact with one wall.
-Flood Fill: Ultimately, we implemented the flood fill algorithm. This method allowed the robot to methodically explore the maze, mark visited cells, identify obstacles, and update a flood map that assigns values to each cell based on its proximity to the goal. During subsequent runs, the robot referenced this flood map to make informed decisions and optimize its navigation route.
The flood fill algorithm facilitated intelligent and adaptive traversal, enabling the robot to dynamically adjust its path based on real-time exploration of the maze.

## Hardware Phase:
In the hardware phase, we built the robot using an Arduino Nano microcontroller, ultrasonic sensors for wall detection, and motors with encoders for precise motion control, all powered by a LiPo battery. This hardware setup enabled the robot to accurately navigate and solve the maze autonomously.

## Conclusion:
This project underscored our capability to implement advanced graph algorithms and develop efficient autonomous systems. By leveraging BFS, DFS, wall follower, and particularly the flood fill algorithm, we created a robot capable of sophisticated and intelligent maze navigation. 

