# Gestural Control of Robots
_2014 &ndash; 2015, [[kyoto|Kyoto University]]_

???+ summary
    - Initial research project at Kyoto University aimed at developing infrastructure to allow ergonomic control of robots using gestures.
    - Designed and developed infrastructure that abstracted away the interface used by using an API,
      with a proof of concept using the Myo armband from Thalmic Labs to control robots.

My initial research topic was developing infrastructure which would allow the ergonomic control of robots using gestures.

![The Myo armband, worn](/assets/images/myo_worn.jpg){: style="width:300px", align=right}

My proof of concept was going to be using the Myo armband from Thalmic labs to control robots,
either a Kinova robotic arm, or one of the lab’s other robots.
Eventually, my professor determined that it was too much development, and not enough research,
and I changed my thesis to [[spirit|SPIRIT]].
The source code is not publically available.

I designed and developed infrastructure which would allow gestural control of robots,
while abstracting away the interface used by using an API.
While I tested with the armband, the system also allowed control using e.g., computer vision from a webcam.

The most difficult part was figuring out good, intuitive mappings to use.
I looked at ergonomics, as well as manually modifying the configurations,
but the project was cancelled before a fully functional version could be made.

Most of the code was written in Python, including wrappers for [C++ code]{{ urls.projects.myo_thalmic }} which I wrote to talk to the armband and the robotic arm.
