# RobotC Labyrinth-Challenge Physical Project

## A fully functional project written in RobotC that allows a TETRIX robot to safely reach its goal destination whilst navigating through physical obstacles.

This project showcases my team's solution to the labyrinth challenge assigned in my Robotics CTE class. There are three parts to this challenge which include the following:

* Part 1: Requires only the robot's motors
* Part 2: Requires a touch sensor in addition to the motors
* Part 3: Requires an ultrasonic sensor in addition to the motors

## Materials:

1. Tetrix Robot
2. USB Cable (Download and Upload Program)
3. Laptop (RobotC Program)
4. AC Adapter (Laptop Charger)
5. Rechargeable Battery with battery charger (Provides Power to NXT)
6. Ultrasonic Sensor
7. Touch Sensor
8. NXT brick

## Part 1 Pseudocode:

1. Turn on motor d and set speed to 15 
2. Turn on motor e and set speed to 15 
3)Wait 2.1 seconds
4)Set motor d to 0 speed
5)Set motor e to 15 speed
6)Wait .875 seconds
7)Set motor D to 15 speed
8)Set motor E to 15 speed
9)Wait .5 seconds
10)Set motor d to 15 speed
11)Set motor e to 0 speed
12)Wait .9 seconds
13)Set motor D to 15 speed
14)Set motor E to 15 speed
15)Wait .425 seconds
16)Set motor d to 0 speed
17)Set motor e to 15 speed 
18)Wait .9 seconds
19)Set motor d to 15 speed
20)Set motor e to 15 speed
21)Wait 1.55 seconds
22)Set motor d to 0 speed
23)Set motor e to 15 speed
24)Wait .817 seconds
25)Set motor d to 15 speed
26)Set motor e to 15 speed
27)Wait 2.4 seconds
28)Set motor d to 0 speed
29)Set motor e to 15 speed
30)Wait .57 seconds
31)Set motor d to 15 speed
32)Set motor e to 15 speed
33)Wait .72 seconds
34)Set motor d to -15 speed
35)Set motor e to 15 speed
36)Wait .61 seconds
37)Turn off motor d
38)Turn off motor e

## Part 2 Pseudocode:

Section 1: The robot will keep moving forward at a speed of 20 until the touch sensor is pressed and then it will back up.

Section 2: The robot will wait.

Section 3: The robot will turn for 1.4 seconds.

Section 4: The robot will move forward at a speed of 30 until the touch sensor is pressed and it will back up.

Section 5: The robot will make a turn for 1.9 seconds.

Section 6: The touch sensor is programmed to make the robot back up when it’s touched.

## Part 3 Pseudocode:

Section 1: If the robot detects the wall, it breaks up. If the robot doesn’t detect the wall it keeps moving forward. In lines 24 through 26 the robot makes a turn after it backs up.

Section 2: If the robot detects the wall, it breaks up. If the robot doesn’t detect the wall it keeps moving forward. In lines 37 through 39 the robot makes a turn after it backs up.

Section 3: If the robot detects the wall, it breaks up. If the robot doesn’t detect the wall it keeps moving forward. In lines 50 through 52 the robot makes a turn after it backs up.
