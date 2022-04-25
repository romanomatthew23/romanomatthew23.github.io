---
layout: post
title:  "Multilift Slung Load Transport with Haptic Guidance"
date:   2022-03-28 00:00:00 -0400
categories: posts
---
Payloads that do not fit conveniently within an aircraft or rotorcraft cargo bay can be transported short distances as a tethered slung load. Carriage by a single vehicle is effective, but as payload weight increases, so must the carrying capacitiy of the single vehicle. Alternatively, using multiple vehicles allows for compartively smaller vehicles to carry the same heavy payload. Typical multilift slung load systems are guided by either following pre-planned trajectories or with a remote pilot. However, in unknown, cluttered, and dynamic environments this may fail. In scenarios such as disaster relief or package delivery, a user would be on the ground ready to interact with the system but would have no prior training.
 
This work [1] considers a novel haptic guidance scheme where the user simply pushes on the payload in the direction they want it to move. A team of five quadrotors is connected with individual tethers to an instrumented payload. A user issues haptic guidance commands by applying force on the slung payload. The system estimates user applied force and direction from inline tension sensors in real-time. This force updates the virtual dynamics of an admittance controller to execute the desired trajectory of the payload in the direction of the applied force. A centralized payload controller commands quadrotor trajectories to track the admittance controller trajectory. Custom open-source autopilot software tracks user commands by translating each quadrotor to pull on the tethers in a manner that collectively moves the payload according to user input force. Simulation and experimental flight test results in a netted facility validate the system with a user applying force directly on the slung payload to guide it.



<iframe width="560" height="315" src="https://www.youtube.com/embed/22yr16A7ELs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


[1] M. Romano, A. Ye, J. Pye, and E. Atkins, “Cooperative Multilift Slung Load Transportation
using Haptic Admittance Control Guidance,” AIAA Journal of Guidance, Control, and Dynamics,
2022 (Under Review)