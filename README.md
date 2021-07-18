# -Smart-Vacuum
Vacuum Cleaner is a typical domain of artificial intelligence in which you imagine having a certain number of clean or dirty rooms and a robot vacuum cleaner that must take care of the cleaning moving, under certain constraints, between the rooms. In this project we propose an extended version of thedomain presented in class in which the rooms can be more or less dirty, there is a starting point of the robot and a point of arrival. Some rooms are not accessible. The topology of the rooms is assumed to be predefined according to a square matrix. The coding of the whole domain (topology of the rooms, definition of the actions, etc.) is part of the exercise. Starting from an initial configuration, it is asked to find the sequence of actions of the robot vacuum cleaner to have all the rooms clean and the robot in the position coded as final. The initial and final states of the robot, along with the initial state of the rooms, are passed to the system via an image.

The condition of the rooms and the initial and final positions of the robot are encoded through a capital letter according to the legend:
- S (Start): initial position of the robot
- F (Finish) : final position of the robot


- X : room not accessible
- C (Clean) : clean room
- D (Dirty) : dirty room
- V (Very Dirty) : very dirty room

