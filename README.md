# SLAM Path Planning

This repository contains the report for the SLAM course TP1, along with a video demonstration of the SLAM overall project.

## Project Overview

In this project, I implemented a shortest path algorithm (A*) in a SLAM context using real-time LIDAR keypoints in a ROS environment. The keypoints are projected onto a boolean map and used to calculate an optimal path. The entire process is visualized in RViz.

### Key Steps:
1. **ROS Environment Setup**: Initializing the project and processing real-time LIDAR data in ROS.
2. **Projection of Keypoints**: Projecting the keypoints onto a boolean map, where each keypoint represents an obstacle or free space.
3. **Shortest Path Algorithm**: Implementing the A* algorithm to compute the shortest path.
4. **Visualization**: Using RViz to visualize the path, keypoints, and obstacles in real-time.

## Video Demo

A video demonstrating the final version of the project is available below. In the video, you can observe how the project is set up in ROS, the keypoint projection on the map, and the path calculation in real-time.
