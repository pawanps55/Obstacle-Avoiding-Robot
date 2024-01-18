# Obstacle-Avoiding-Robot
I made this project in my Diploma 6 semester in Mechatronics Course

Introduction of Obstacle Avoiding Robot - 
1.Obstacle Avoiding Robot is an intelligent device that can automatically sense the obstacle in front of it and avoid them by turning itself in another direction.
2.This design allows the robot to navigate in an unknown environment by avoiding collisions, which is a primary requirement for any autonomous mobile robot.
3.Generally obstacle avoidance robot is design to allow robot to navigate in unknown environment by avoiding collisions. 
4.And it’s senses obstacles in the path, avoids it and resumes its running. 
5.Sometimes we have make use of sensors to achieve this objective.
6.The use of these methods front to classic methods (path planning) is a natural alternative when the scenario is dynamic with an unpredictable behaviour.
In these cases, the surroundings do not remain invariable, and thus the sensory information is used to detect the changes consequently adapting moving.

Components Used - 
1.Arduino UNO
2.BO Motor
3.Ultrasonic Sensor HC-SR04
4.L298N Motor Driver Module
5.Screw terminal connector 

Working principle - 
1.The obstacle avoidance robot uses ultrasonic sensors for its movements. A microcontroller is used to achieve the desired operation. 
2.The motors are connected through the motor driver IC to the microcontroller and the ultrasonic sensor is attached in front of the robot.
3.Whenever the robot is going on the obstacle then ultrasonic sensor transmits the ultrasonic waves continuously from its sensor.
4.Then if obstacle comes ahead of it the ultrasonic waves are reflected from an object and that information is passed to the microcontroller.
5.The microcontroller controls the motors left, right, back, front, based on ultrasonic signals.

Applications - 
1.Obstacle avoiding robots can be used in almost all mobile robot navigation systems.
2.They can be used for household work like automatic vacuum cleaning. 
3.They can also be used in dangerous environments, where human penetration could be fatal.

Advantages -
I.Whenever robot senses any obstacle automatically diverts its position to left or right and follows the path without human guidance.
II.The programming of the microcontroller is easy.
III.It is a low’ cost circuit.

Disadvantages - 
I.It is time consuming project.
II.It is use for short distance only.
III.It is not recommended to keep the range very long because this would cause the ROBOT to keep moving forward and backward as it senses any obstacle, even far away from it.
It is not in human control
