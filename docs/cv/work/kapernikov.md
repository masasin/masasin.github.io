# Industrial Automation Engineer, [Kapernikov](https://www.kapernikov.com/)
_March to October 2019, Brussels, Belgium._

???+ summary

    - Developed a monitoring system for a conveyor belt using Python 3 and ROS.
    - Used a laser profiler and camera for object identification and created a 3D representation of the conveyor belt.
    - Detected potentially disruptive objects in real time and produced visualizations for the client’s video management system.
    - Fixed bugs in C++ code and created a standalone ROS node for camera communication.

Kapernikov is a consulting company specializing in industrial automation and Industry 4.0.
The client had irregularly shaped objects on a long conveyor belt, some of which blocked the belt and caused long delays.

I developed a monitoring system for the conveyor belt, primarily using Python 3 and ROS.
I used a laser profiler and a camera to identify the highest points in the plane of the laser,
and transformed that into physical coordinates using custom calibration code written in Python.

Knowing the speed of the belt thanks to a connected encoder, I was able to create a 3D representation of the conveyor belt.
This was analyzed, and potentially disruptive objects were detected in real time.
Visualizations were produced and annotated, and then sent to the client’s video management system.

The camera had drivers in C++, as well as in-house C++ code which contained some bugs that I fixed.
I created a standalone ROS node which would talk to the camera and forward only the data needed by the rest of the system.
All other ROS nodes, transformations, and analyses were written in Python.
