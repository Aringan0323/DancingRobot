# DancingRobot

Controls:\n\n\t

  ' ': halts all motion for the robot\n
  'e': exits program\n
  'w': moves robot forward\n
  'a': rotates robot left\n
  's': moves robot backwards\n
  'd': rotates robot right\n
  'i': halts all motion and then moves robot forwards\n
  'j': halts all motion and then rotates robot left\n
  'k': halts all motion and then moves robot backwards\n
  'l': halts all motion and then rotates robot right\n
  'f': sends robot into a spiral that grows and then shrinks\n
  'z': moves robot forward in a zig-zag motion\n
  'c': spins robot around at a high velocity, alternating spinning direction randomly\n
  'r': rotates robot towards origin and then moves until nearest obstacle is 0.5 meters away\n\n\n
  
 This project allows you to control the Turtlebot 3 in the Gazebo simulation using the commands
 specified above passed to key_publisher.py. The robot will halt all motion if it reaches within
 0.2 meters of a wall, and in order to control the robot again the user will have to input the
 command 'r' to key_publisher.py. This will rotate the robot towards the origin and move it forward
 until it is at least 0.5 meters away from the nearest obstacle. At this point the user will regain
 control of the robot.
 
 This programming assignment was less difficult to finish than the second programming assignment.
 I believe the reason for this is because this assignment used many aspects that were developed in
 previous assignments, and there was significant potential for code reuse. The most difficult part
 of this assignment was coding the special movement functions such as zig_zag(), spiral(), and 
 go_crazy() because all of them required time to be considered as a factor into which direction
 the robot would either turn or move. Otherwise, I would say that this project was the most enjoyable
 project to code so far because of the many possibilities of what to code and how to code the movements.
 
 
