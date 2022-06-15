.. _doc_lidar_cone_detection:

Lidar Cone Detection
========================

In the race at the Purdue Grand Prix, the race track was lined with cones to map the boundaries. Thus in order to accurate localize the car, the cones need to be detected and localized properly themselves.

This task could be done using a camera running an object-detection algorithm but the downside of this is that the detections are not robust enough in situations of variable light intensities. 
Also using monocular cameras does not provide us with sufficient information regarding the depth of cones. Hence we decided to use a Lidar to perform all our cone object detections because it come with the added advantage of robust depth-estimations even over stereo cameras.

The algorithm used by us for lidar cone estimation is highlighted here: `Lidar Cone Detection Blog <https://murmotorsports.eng.unimelb.edu.au/news-and-events/news-and-events/mur-blog-real-time-cone-detection-with-lidar>`_

For a working code implementation refer here: `Lidar Cone Detection Code <https://github.com/mlab-upenn/gokart/tree/lidar-cones/src/gokart/lidar_cones>`_

Note that the above implementation was implemented on an Ouster OS1 32 Layer Lidar and cones of certain fixed sizes. If the lidar and cone sizes are different then change appropriate parameters in **cluster.cpp** in the source code.

Below is a video demonstrating our algorithm:

.. raw:: html

	<iframe width="560" height="315" src="https://www.youtube.com/embed/4snktyzZFpI" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
