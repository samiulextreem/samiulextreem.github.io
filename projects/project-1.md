---
layout: project
type: project
image: images/Line_follower_robot.jpg
title: PID controlled line following and maze solving robot 
permalink: projects/micromouse
# All dates must be YYYY-MM-DD format!
date: 2015-07-01
labels:
  - Robotics
  - Arduino
  - C++
summary: My team and me developed a robotic mouse that took part in the 2015 uni-micromouse competition.
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/Line_follower_robot.jpg">
</div>

Micromouse is an event where small robot “mice” solve a 16 x 16 maze by following a complex track. The mice are completely autonomous robots that must find their way from a predetermined starting position to the central area of the maze unaided. The mouse will need to keep track of where it is, discover walls as it explores, map out the maze and detect when it has reached the center.  having reached the center, the mouse will typically perform additional searches of the maze until it has found the most optimal route from the start to the center. Once the most optimal route has been determined, the mouse will run that route in the shortest possible time.

For this project, I was the lead programmer who was responsible for programming the various capabilities of the mouse. I started by programming the basics, such as sensor polling and motor actuation using interrupts. From there, I then programmed the basic PD controls for the motors of the mouse.  The PD control the drive so that the mouse would stay centered while traversing the maze and keep the mouse driving straight.  I also programmed basic algorithms used to solve the maze.  From there I worked on a flood-fill algorithm to help the mouse track where it is in the maze, and to map the route it takes. 
