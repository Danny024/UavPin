# UavPin
An Intelligent Unmanned Aerial Vehicle For Detection of Pipeline Faults
## Abstract
Leakages on Pipeline continues to be a problem in the petroleum sector, but this research presents the use of state of the art techniques in Robotics and Artificial Intelligence to tacke this menace. This project makes use of an intelligent drone enabled by computer vision algorithm to detect pipeline faults.
The Drone is able to perform the following
1. Real time 3D Reconstruction of the environment
2. Detection of Pipeline Faults using Computer Vision algorithm
3. Obstacle avoidance during drone navigation
4. Tracking of Pipeline path using Path Dijkstra's and A* algorithm

Video Link :


[![Unmanned Aerial Vehicle](https://img.youtube.com/vi/1v-ivv_LiHk/0.jpg)](https://www.youtube.com/watch?v=1v-ivv_LiHk)


## Installation 
1. Unreal Engine 4.27
2. Ubuntu 18.04 on WSL2
3. QGround Control on Windows
4. Airsim on Windows
5. PX4

## Dependencies


## Proposed Hardware Architecture
The Drone has a pay load of Depth Camera, RGB Camera and a LIDAR sensor

## Simulation Architecture
The simulation was carried out using Microsft Airsim on Windows and on Ubuntu 18.04 (WSL2)

## 3D Map Reconstruction
The 3D Map recosntruction was carried out using the fusion of the snesor readings from lidar sensor and the depth sensor. The segmentation point cloud gives better seen understanding of the environment.

## Computer Vision algorithm 

### A.Yolo v8
Training on Real life Dataset

Training on Synthetic Dataset

### B. DETR (Detection Transformer)
Training on Real life Dataset
Colab Link :
## Pipeline Tracking and Obstacle Avoidance

### References
[1]
[2]
[3]
