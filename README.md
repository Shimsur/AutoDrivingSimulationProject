# AutoDrivingSimulationProject

Project Overview

AutoDrivingSimulation is a C# console-based simulation system for managing the movement of two cars based on user inputs. The simulation supports commands to move, turn left, and turn right, tracking the position and direction of the cars. Additionally, it checks for collisions between the two cars based on their movements.

Core Features
Car Movement Simulation:

Each car can move in one of four directions (North, South, East, West).
Cars can follow commands like 'M' (move), 'L' (turn left), and 'R' (turn right).
Collision Detection:

The program checks if two cars collide at any given point based on their movements.
User Input:

The program allows users to define the initial position and direction of two cars and enter the movement commands.
Current Design
Key Classes
Car Class:

Holds properties such as the car's name, position (X, Y), direction (N/S/E/W), and movement commands.
Includes methods for moving the car (Move), turning left (TurnLeft), and turning right (TurnRight).
CarSimulation Class:

Executes the movement commands for both cars.
Checks if the two cars collide based on their final positions.
Program Class:

Acts as the entry point for the program.
Takes user inputs for the starting positions and commands for both cars.
Invokes the movement logic and displays final results.

Design Considerations

Monolithic Design:

The program currently uses a monolithic structure where multiple responsibilities (movement logic, simulation, user input) are combined in a single file, making the code harder to maintain and extend.

Thanks
Shimna
