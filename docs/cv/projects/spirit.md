# SPIRIT (Masters thesis)
_2015 &ndash; 2017, [Kyoto University](kyoto)_

???+ summary

    - Masters thesis project at Kyoto University, developing a third-person view interface for controlling a monocular drone.
    - Created a system that superimposed a CGI version of the drone on top of an actual image taken by the FPV camera earlier.
    - Designed, conducted, and analyzed user studies which were performed to test the efficacy of the system,
      which showed a large improvement in many metrics, even with a 2 Hz transmission rate.

SPIRIT stands for "Subimposed Past Image Records Implemented for Teleoperation".

![SPIRIT development](/assets/images/spirit_dev.jpg){: style="width:300px", align=left}

Japan is prone to natural disasters.
Inspection of collapsed structures paves the way for a safer search and rescue operation in the aftermath.
Using drones is tight spaces is difficult,
and the boundaries of the drone are not visible in the first-person view (FPV) feed,
especially with a monocular camera.
In addition, signal quality may be degraded due to structural materials, leading to a bad or spotty connection.


Building upon previous work of the [Mechatronics lab](http://www.mechatronics.me.kyoto-u.ac.jp/index.php?ml_lang=en)
on the use of Past Image Records for teleoperation, mobile manipulators, and narrow communication bands,
I created a third-person view interface for controlling an AR.Drone, primarily using Python and ROS.
A CGI version of the drone was superimposed on top of an actual image taken by the FPV camera earlier,
which contains the current position of the drone. 

![SPIRIT interface](/assets/images/spirit.png){: style="width:400px", align=right}

The position of the drone was known thanks to motion capture cameras,
but could also be derived from other metrics such as e.g. visual odometry.
It used a single camera as its source, and simulated a degraded transmission environment by dropping frames.
I designed, conducted, and analyzed user studies which were performed to test the efficacy of the system.
It showed a large improvement in many metrics, even with a 2 Hz transmission rate.

The biggest challenge was deciding which images to use.
I created multiple evaluation functions, and modularized the code to be able to select the function from the launch files.
I also automated the generation of new launch files using xacro programming and Python.

!!! abstract "Source code"

    The source code is available on [GitHub](https://www.github.com/masasin/spirit).
    It is well-documented, including a [wiki](https://github.com/masasin/spirit/wiki), checklists, and instructions.
    It contains a ROS core;
    data collection, analysis, and visualization code;
    and the full LaTeX source code for the thesis.

    A summary of the individual components is [here](https://github.com/masasin/spirit/wiki/Components),
    and the thesis itself can be downloaded [here](https://github.com/masasin/spirit/releases/download/v1.0/mshtsy_thesis.pdf).