# Travel Time Optimization

## Problem Overview
The goal of this exercise is to **minimize the travel time** for a car trip between 5 cities. The trip has **variable speeds allowed on different road sections**, and the driver wants to determine the **optimal speed distribution** to reach the destination in the shortest time while respecting speed limits. It asks how is the better route if it begins at BA and must to visit all the cities and come back to BA with the smallest time and km?

Cities to trip:
- Buenos Aires (BA)
- La Plata (LP)
- Mar del Plata (MDP)
- Rosario (ROS)
- Cordoba (COR)

## Objective
- Find the best optime route with the smallest time and km

### Techniques
- Derivatives 

## Data
- City: Identifies each location
- Latitude: Used to calculate geographic distance in a continuous space
- Longitude: Complements latitude to compute real distances between cities
- Max_speed_kmh: Defines the maximum velocity allowed per route
- Road_factor: Reflect real road conditions or traffic
    - 1.0 = Route with optimal conditions(it doesn't reduce the max speed)
    - <1.0 = Exists traffic and obstacles reduces the max speed

