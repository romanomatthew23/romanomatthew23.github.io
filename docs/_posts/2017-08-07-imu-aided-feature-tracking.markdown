---
layout: post
title:  "IMU-Aided Feature Tracking"
date:   2017-08-07 00:00:00 -0400
categories: posts
---

At UIUC I worked in the [Bretl Research Group](http://bretl.csl.illinois.edu/) on the Construction Site Monitoring Project (which aims to use robotics technology to automate this task). Specifically, I worked on a project trying to use Inertial Measurement Unit (IMU) data to improve a feature tracking algorithm. The project can be found [here](https://github.com/jomnipotent17/IMUTrack).

The starting point of this project was based off of this [paper](http://www.cs.cmu.edu/~myung/IMU_KLT/). They provided open source code in which they were using IMU data to improve the Kanade-Lucas-Tomasi (KLT) feature tracker.

From this I implemented a few different methods to incorporate IMU data trying to improve the accuracy as well as computation time. Below you can see an example plot of 3 different methods I used comparing how many feature points they tracked over time. The angular velocity is also aligned for context. Note how much the "noIMU" method degrades in performance when there are large changes in angular velocity. However, these "violent motions" are easily handled by an algorithm that can sense them using an IMU.
