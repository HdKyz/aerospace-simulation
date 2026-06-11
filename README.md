# aerospace-simulation
A Python-based aerospace simulation modelling lift, drag, thrust and altitude using real aerodynamic equations.

# Overview 
This prroject aims to simulate the motion of an aircraft by calculating aerodynamic forces at each time step and updating the aircraft's velocity and altitude accordingly.
It uses a modular structure so each part of the physics can be developed and modified independantly.

# Features
Realistic lift and drag modelling
Adjustable aircraft parameters
ISA-based air density model
Velocity-time and Altitude-time graphs
Modular file structure for expansion
Clean separation between physics, aircarft data and simulation logic

# File Structure 
aerospace-simulation
|
+-README.md
+-simulation.py
+-physics.py
+-aircraft.py

# Physics Model
The simulation uses standard aerodynamic equations
 -Lift: L= 
 -Drag: D= 
 -Thrust: constast or variable depending on aircraft
 -Weight: mg
 -Air density: ISA approxiamtion
These equations are constructed in physics.py then imported into the simulation code

# Example Output


