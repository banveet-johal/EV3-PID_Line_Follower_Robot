# EV3-PID_Line_Follower_C

 Line-Tracking Robot designed with PID algorithm to perform the following: (Used Lego EV3 Mindstorms Parts and programmed in C language and Python.)
 
  a) Track the simple line given an initial position using right edge of the line.
  
  b) Once an obstacle is seen in 10 cm distance, the robot stops and make a beep for two seconds.
  
  c) According to the color of the line, the robot does one of the following tasks. 

If the line is green:
   1. the robot continues moving toward the obstacle and pushes it away from its original position 
   and towards the direction where the obstacle will be away from the line for around 10 cm.
   2. return to the tracking line and continue moving forward. 

If the line is blue:
   1. it turns 180 degrees and move backward to the start point of the path. 

If you want to watch the demo, you can view it here https://youtu.be/OXqYBuOPO54. 
   
Path:

![Model](https://github.com/banveet-johal/EV3-PID_Line_Follower_C/blob/main/image/robot_path.PNG)

Robot:

![Model](https://github.com/banveet-johal/EV3-PID_Line_Follower_C/blob/main/image/robot.PNG)
