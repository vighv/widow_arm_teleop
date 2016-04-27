# widow_arm_teleop
Teleoperation of Trossen WidowX arm using arbotix_gui

Usage: roslaunch widow_arm_teleop widow_arm_teleop.launch
In another terminal: arbotix_gui

Some quirks:
If the arbotix_gui does not seem to be working, open an arbotix_terminal and list the servos ( 'ls' )

Seems to establish communication to the board in the roslaunch terminal

After that, operate away!
