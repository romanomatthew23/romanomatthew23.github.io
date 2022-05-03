---
layout: post
title:  "M330-Quadrotor & rc_pilot_a2sys Flight Controller"
date:   2022-03-28 00:00:00 -0400
categories: posts
---

![M330Quadrotor](/images/m330_quadrotor.png)

My PhD has focused on autonomy for multi-UAS teams with a large importance placed on experimental testing and validation. To support this, I developed the M330-Quadrotor, a low-cost ($300), opensource, quadrotor. It uses off-the-shelf and 3D printed components, allowing for rapid repair with replaceable parts in the event of collisions. 3D printed propeller guards act as bumpers such that vehicles bounce off of each other rather than breaking propellers when in close proximity. A BeagleBone Blue computer runs the rc_pilot_a2sys flight controller to enable autonomous flight operations. <b>A Bill of Materials, Assembly Instructions, software, and guides are all available in the opensource project [here](https://drive.google.com/drive/u/0/folders/1c1IxiEmO9NtAwvNjbBFhNUQv-BWFgEg5)</b>.

We created [rc_pilot_a2sys](https://gitlab.eecs.umich.edu/m330-quadrotor/rc_pilot_a2sys) as a fork from rc_pilot - which is a project developed by StrawsonDesign that leverages the librobotcontrol library. The original project wasn’t intended to be fully functional and for public use and it had some bugs here and there. We fixed a few bugs and added some additional functionality for use in our research vehicles and are now calling the flight control software, rc_pilot_a2sys. 

One of the greatest benefits of rc_pilot is its simplicity. It is only set up to work with the Beaglebone Blue, and it is only configured to be used by multirotor vehicles. This results in very few files (about 10 CORE .c/.h files) and relatively few lines of code. Compare this with Ardupilot (APM) which we were using previously which has 100s (maybe 1000s?) of files and probably 100s of thousands of lines of code. There is a trade-off in that Ardupilot can handle a tremendous number of different hardware platforms (Pixhawk, Beaglebone Blue, etc.) as well as a number of different vehicle types (multirotor, plane, rover, sub), however, that comes with tremendously more complexity in the software organization and management.

The goal of this project is to support researchers to get off of the ground. The codebase is accessible and allows for easy implementations of specific research use cases without worrying about the basic setup. 











