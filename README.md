Project: Scary Doll Mounted on an Arduino RC Car

Objective:

The objective of this project is to design and build a wireless RC car that utilizes ultrasonic sensors to detect movement and obstacles in three directions: front, left, and right. The car should move towards the direction where movement or an obstacle is detected. In the absence of movement, the car should scan the surroundings by rotating and identifying the shortest distance to an obstacle, and then move towards it.

Components:

Wireless RC car
Ultrasonic sensors (3)
Arduino Uno or similar microcontroller board
Jumper wires
Batteries

Design:

-Mount the ultrasonic sensors on the front, left, and right sides of the RC car.
-Connect the ultrasonic sensors to the Arduino Uno.
- Use Arduino code to control the movement of the RC car based on the sensor readings.

Implementation:

Movement Detection:

-Continuously read the values from the ultrasonic sensors.
-If the sensor value in a particular direction is lower than a certain threshold, indicating an obstacle or movement, move the RC car in that direction.

Obstacle Avoidance:

-When no movement is detected, rotate the RC car slowly and continuously read the sensor values.
-Identify the direction with the shortest distance to an obstacle.
-Move the RC car towards the direction with the shortest distance.


Testing:

Movement Detection:

-Place objects in various directions around the RC car and observe its movement.
-Adjust the threshold value for the sensor readings to ensure accurate movement detection.

Obstacle Avoidance:

-Place obstacles in various configurations around the RC car and observe its scanning behavior.
-Verify that the RC car correctly identifies the shortest distance to an obstacle and moves accordingly.

Additional Considerations:

-Implement a mechanism to adjust the sensitivity of the ultrasonic sensors to avoid false positives.
-Incorporate a feedback loop to refine the car's movement based on sensor readings.
-Explore the possibility of adding additional sensors for more sophisticated obstacle avoidance and movement patterns.
