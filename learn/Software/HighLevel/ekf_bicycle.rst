.. _doc_ekf_bicycle:

.. |check| raw:: html
    <input checked=""  type="checkbox">

.. |check_| raw:: html
    <input checked=""  disabled="" type="checkbox">

.. |uncheck| raw:: html
    <input type="checkbox">

.. |uncheck_| raw:: html
    <input disabled="" type="checkbox">

EKF Bicycle Model
=========================

EKF or the Extended Kalman Filter is used for accurate state estimations of robots. We used the EKF algorithm to fuse GPS and IMU measurements to obtain a faster rate of response of our state estimations as relying only on GPS measurements is extremely slow for fast autonomous driving.

We used the following reference to implement the EKF algorithm: `EKF Bicycle Model Paper <https://escholarship.org/content/qt3v08d6nt/qt3v08d6nt.pdf?t=lnpyrf>`_

The high level overview of the paper is as follows:
    * The paper proposes a IMU + GPS state estimation system using the EKF to increase the robustness of state estimations in situations where GPS fails to perform accurately.
    * A Bicycle model is used for propagating the state variables forward. This model takes into considerations the attributes of the vehicle such as the center of mass, weight of the car and cornering stiffness of the tires. Hence these properties have to be measured for the vehicle on which this system is to be implemented.
    * The Jacobians used for linearization are not computed or mentioned explicitly in the paper and hence need to be computed.

For a working code implementation refer here: `EKF Bicycle Model Code <https://github.com/mlab-upenn/gokart/tree/ekf-bicycle/src/gokart>`_

STATUS - Tested in
+---------------------+------------------+
| Tested in Simulation| Tested on Go Kart|
+=====================+==================+
| YES                 |NO                |
+---------------------+------------------+


STATUS
[X] - Tested in simulation |check|
[ ] - Tested on Go Kart |uncheck|
