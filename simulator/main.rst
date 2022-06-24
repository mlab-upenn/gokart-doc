.. _doc_simulator:

Simulator
======================

The simulator is built in Gazebo and contains the GPS accurate track from Purdue. It was used for testing of all :ref:`doc_high_level`.

.. raw:: html

	<iframe width="560" height="315" src="https://www.youtube.com/embed/nfZCW_M_rH0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

.. raw:: html

	<iframe width="560" height="315" src="https://www.youtube.com/embed/bswCUaMeaE4" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Running the simulator:

Use a running terminal window/tab:

source install/setup.bash
ros2 launch simulator simulation.launch.py teleop:=key

See `gokart-simulation/simulator <https://github.com/mlab-upenn/gokart-simulation/tree/main/simulator>`_ for more information