.. _doc_pure_pursuit:

Pure Pursuit
==================

The Pure Pursuit algorithm is used to navigate and execute effective path planning from one given waypoint to another. It is the main algorithm that moves the GoKart autonomously around the race track.

Learn more about Pure Pursuit here: `Pure Pursuit Tutorial <https://f1tenth.org/learn.html>`_
    * Navigate to the above mentioned link
    * Click on the "Module D: Planning" side-bar option
    * Refer Lecture 13 - Pure Pursuit

For a working code implementation refer here: `Pure Pursuit Code <https://github.com/mlab-upenn/gokart/tree/main/src/gokart/pure_pursuit_gokart>`_

The above mentioned Pure Pursuit implementation also consists of a Local Planning algorithm. This algorithm is used to locally avoid obstacles placed in the way of the GoKart.
It uses a clothoid-based local path generation and selects the best path that does not have an obstacle in the way.