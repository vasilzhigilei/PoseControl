# PoseControl
Control monitors depending on head pose direction relative to the camera in multi-monitor setups


Tools being used:
* opencv & dlib for face positioning data
* windll and other libraries from ctypes in Python

Overarching goal: Improve productivity in multimonitor systems by reducing time spent moving the mouse from screen to screen

Features to be added:
* auto focus on window being looked at
* ability to "lock" focus on one screen despite looking elsewhere

Steps to program:
* fetch monitor layout information
* do math to figure out head position ranges for each monitor
* programmatically focus on windows open on monitor looked at
* other future features
