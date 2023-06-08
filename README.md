# EV3-PID_Line_Follower_C

 Line-Tracking Robot designed to perform the following: 
 
  a) Track the simple line given an initial position using right edge of the line.
  
  b) Once an obstacle is seen in 10 cm distance, the robot stops and make a beep for two seconds.
  
  c) According to the color of the line, the robot does one of the following tasks. 

If the line is green:
   1. the robot continues moving toward the obstacle and pushes it away from its original position 
   and towards the direction where the obstacle will be away from the line for around 10 cm.
   2. return to the tracking line and continue moving forward. 

If the line is blue:
   1. it turns 180 degrees and move backward to the start point of the path. 
