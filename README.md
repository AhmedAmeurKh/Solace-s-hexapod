# Solace-s-hexapod
A spider-inspired mechanical robot, or more commonly known as a hexapod.
Fallout project link: https://fallout.hackclub.com/projects/3045
A servo-powered mechanical hexapod inspired by spiders

# What is a hexapod?
A hexapod is a six-legged (or 4) walking robot modeled on insect locomotion.

Each leg is driven by three servo motors through a three-segment kinematic chain (coxa, femur, tibia).
This allows more freedom of movement compared to using three servo motors, as seen in many Arduino projects.

The choice between a four-legged hexapod and a six-legged one is critical, as more legs mean more stability, but at the cost of more parts and software implementation.

An MPU or a gyro could be implemented for more stability, but it isn't really a requirement because the robot self balances with using the fact that it could always have 3 legs grounded (forming a triangle, one of the most stable shapes).

Project Goals:

A remote-controlled hexapod.

# Features:

-A self-stabilizing system using an MPU

-NRF/Wifi/Bluetooth connectivity

-Costume firmware

-Easy to print, recreate, and modify. (modular design if possible)

-Structural integrity and resistance to high-speed movement/rough terrain. (target speed: 40-60cm in 5 seconds {7m/minute} )

-Replaceable rubber/TPU foot tips
