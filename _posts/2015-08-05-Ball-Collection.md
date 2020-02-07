---
layout: post
title: "Ball Collection"
date: 2015-08-03 03:32:44
image: '/assets/img/'
permalink: Ball-Collection/
description: 'First steps to use this template'
---

# ME 350: Design and Manufacturing II, Ball Collection (2017)

The goal of this project is to design and build an automated mechanism which can catch balls from two chutes and sort them into the correct place based on color.

We first utilized ADAMS to optimize the position of the four bar linkage based on the motor power and weight.

![Table_1](/assets/img/atw_1.png)

The final designs are shown below. The slot in the ball catcher is reserved for the color sensor.

![Design](/assets/img/atw_2.png)

Wiring diagram for the color sensor and motor. PID controls are used to control the position and speed/torque of the motor.

![Tipping](/assets/img/atw_5.png)

Control System:

We used a Arduino Mega to control 4 800W In-Hub BLDC motors with e-bike motor controllers to control each motor independently.

The system is powered by 16 LiFeP04 3.2 V batteries, monitored by BMS, giving us total of 48V at 40AH. We designed and 3D printed the joystick.


