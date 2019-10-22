---
layout: post
title: "All-Terrain Wheelchair"
date: 2015-08-03 03:32:44
image: '/assets/img/'
permalink: /All-Terrain-Wheelchair/
description: 'First steps to use this template'
---

# All-Terrain Wheelchair

The goal of this project is to help Jason, our sponsor who is disabled, increase his mobility. As an avid outdoors man, he needs a way    to walk his dog, go to the beach, etc. His current wheelchair cannot traverse through rough terrain and he has requested us to design and build an all terrain electric wheelchair for him.

My team talked to him and asked him what he needs out of this wheelchair and transformed his user needs into engineering requirements.

![Table_1](/assets/img/atw_1.png)

The final design and specifications are shown below

![Design](/assets/img/atw_2.png)

We conducted tipping analysis, battery analysis and torsional rigidity analysis of our chassis to ensure our design meets his needs and safety.

![FEA](/assets/img/atw_3.png)

![Battery](/assets/img/atw_4.png)

![Tipping](/assets/img/atw_5.png)

Control System:

We used a Arduino Mega to control 4 800W In-Hub BLDC motors with e-bike motor controllers to control each motor independently. The system is powered by 16 LiFeP04 3.2 V batteries, monitored by BMS, giving us total of 48V at 40AH. We designed and 3D printed the joystick.

<iframe width="560" height="315" src="https://www.youtube.com/embed/6Ac5SBsI1DA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
