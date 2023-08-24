# Robot Competition - Physical Robot

Welcome to the repository for our robot competition project! This repository contains the code and details for a robot designed to excel in a series of challenging physical subtasks. Our robot is designed to navigate a line maze, follow a curved wall, solve a blind box challenge, and demonstrate line-following capabilities.

## Project Overview
![Task](https://github.com/RavinduMPK/Physical-Robot/assets/68577937/19232b7c-f208-4518-8976-905df7b997b3)


Our project aims to develop a versatile robot capable of tackling a range of physical challenges. These challenges test the robot's navigation, control, and problem-solving abilities. The main subtasks include:

1. **Line Maze**
2. **Curved Wall**
3. **Blind Box**
4. **Line Following**

## Line Maze

### Exploration Stage

In this stage, the robot starts from the white starting square. It embarks on a journey to explore the maze, using 90-degree turns at intersections. The goal is to reach the white checkpoint square on the opposite side of the maze. Once the checkpoint is reached, the exploration stage concludes.

### Speeding Stage

Having completed the exploration, the robot employs the gathered data to compute the shortest path back to the starting square. The time it takes for the robot to return to the starting square influences its score in this stage.

## Curved Wall

The robot leaves the starting square of the maze to follow a curved wall, which is situated to the robot's left. The robot must navigate the wall without crossing the red line that marks the boundary. A penalty will be incurred if the robot crosses the line. The curved wall leads to the entrance of the blind box challenge.

## Blind Box

Within the blind box, the robot encounters three openings: an entrance, a wrong exit, and a correct exit. The robot's task is to exit through the correct opening and follow a line on the floor to reach the final destination square. Collisions with the blind box walls trigger penalties, so precise control is essential.


## Code Organization

The repository is structured as follows:

- Line following test code
- Wall following test code
- Fully structured code

## Media Showcase
![Physical_Robot_3](https://github.com/RavinduMPK/Physical-Robot/assets/68577937/c79ccab6-8c26-4631-8988-cb98f38a599c)
![Physical_Robot_2](https://github.com/RavinduMPK/Physical-Robot/assets/68577937/ab8260e5-1d9d-4596-b0c6-7eee8cce683e)
![Physical_Robot_1](https://github.com/RavinduMPK/Physical-Robot/assets/68577937/ea73612e-a9ff-4236-b1cc-3f198ca3dc8b)
![Physical_Robot](https://github.com/RavinduMPK/Physical-Robot/assets/68577937/8deb7d83-8d81-4324-9bd0-15517c4e3f3c)

