Release Notes
=============

The following release notes detail the updates to packages available on
http://packages.fetchrobotics.com. For more details on the changes that
have occured in an individual package, please see the CHANGELOG within
the installed package.

For information on updating your robot to the latest packages, see
:ref:`updating`.

January 21, 2016
----------------
This sync includes new upstream ROS packages. New drivers
include improvements to charge state estimation and a
tool for :ref:`in-field calibration of the torso<torso_calibration>`.
Auto docking includes several fixes for TF-related errors,
as well as a fix for reliability when the odom frame and dock
are aligned.

Updated Fetch Packages:
 * ros-indigo-fetch-drivers: 0.7.3-0 -> 0.7.4-0
 * ros-indigo-fetch-auto-dock: 0.1.0-0 -> 0.2.1-0

A full list of new upstream packages can be found on the
`ROS mailing list <http://lists.ros.org/pipermail/ros-users/2016-January/069795.html>`_

November 23, 2015
-----------------
This sync includes new upstream ROS packages as well
as minor bug fixes and improvements to drivers. Notably,
the deadman must now be held while tucking the arm, this
allows a user to stop the arm tucking should the robot
collide with an obstacle in the environment.

Of note, this release also fixes several inconsistencies
in the wrist_flex range of the robot. If your robot appears
to have an overly limited wrist_flex range, we recommend
recalibrating the robot from a clean URDF after updating
your packages.

Maps have been removed from the fetch_navigation package and
moved to their own package, fetch_maps.

Updated Fetch Packages:
 * ros-indigo-fetch-drivers: 0.7.1-0 -> 0.7.3-0
 * ros-indigo-fetch-depth-layer: 0.6.2-0 -> 0.7.0-0
 * ros-indigo-fetch-description: 0.6.2-0 -> 0.7.0-0
 * ros-indigo-fetch-gazebo: 0.6.2-0 -> 0.7.0-0
 * ros-indigo-fetch-gazebo-demo: 0.6.2-0 -> 0.7.0-0
 * ros-indigo-fetch-moveit-config: 0.6.2-0 -> 0.7.0-0
 * ros-indigo-fetch-navigation: 0.6.2-0 -> 0.7.0-0
 * ros-indigo-fetch-teleop: 0.6.2-0 -> 0.7.0-0

New Fetch Packages:
 * ros-indigo-fetch-maps: 0.7.0-0

A full list of new upstream packages can be found on the
`ROS mailing list <http://lists.ros.org/pipermail/ros-users/2015-November/069765.html>`_

November 12, 2015
-----------------
This sync includes new upstream ROS packages as well as
the first release of auto docking.

Please note that the MD5 checksum for the dock action
will have changed with this release.

Updated Fetch Packages:
 * ros-indigo-fetch-drivers: 0.6.3-0 -> 0.7.1-0
 * ros-indigo-fetch-auto-dock-msgs: 0.5.2-0 -> 0.6.0-0
 * ros-indigo-fetch-driver-msgs: 0.5.2-0 -> 0.6.0-0
 * ros-indigo-fetch-gazebo: 0.6.1-0 -> 0.6.2-0
 * ros-indigo-fetch-gazebo-demo: 0.6.1-0 -> 0.6.2-0

New Fetch Packages:
 * ros-indigo-fetch-auto-dock: 0.1.0

A full list of new upstream packages can be found on the
`ROS mailing list <http://lists.ros.org/pipermail/ros-users/2015-September/069629.html>`_

August 5, 2015
--------------
This sync includes new upstream ROS packages as well
as minor fixes to the URDF and calibration.

Updated Fetch Packages:
 * ros-indigo-fetch-drivers: 0.6.1-0 -> 0.6.3-0
 * ros-indigo-fetch-depth-layer: 0.6.1-0 -> 0.6.2-0
 * ros-indigo-fetch-description: 0.6.1-0 -> 0.6.2-0
 * ros-indigo-fetch-moveit-config: 0.6.1-0 -> 0.6.2-0
 * ros-indigo-fetch-navigation: 0.6.1-0 -> 0.6.2-0
 * ros-indigo-fetch-teleop: 0.6.1-0 -> 0.6.2-0

A full list of new upstream packages can be found on the
`ROS mailing list <http://lists.ros.org/pipermail/ros-users/2015-August/069564.html>`_

July 9, 2015
------------
This sync includes new upstream ROS packages as well as
tuck arm functionality from the robot joystick. This
release also includes charge level estimates for
Fetch and Freight robots.

Updated Fetch Packages:
 * ros-indigo-fetch-drivers: 0.5.3-0 -> 0.6.1-0
 * ros-indigo-fetch-depth-layer: 0.5.13-0 -> 0.6.1-0
 * ros-indigo-fetch-description: 0.5.13-0 -> 0.6.1-0
 * ros-indigo-fetch-driver-msgs: 0.5.1-0 -> 0.5.2-0
 * ros-indigo-fetch-gazebo: 0.5.0-0 -> 0.6.1-0
 * ros-indigo-fetch-gazebo-demo: 0.5.0-0 -> 0.6.1-0
 * ros-indigo-fetch-moveit-config: 0.5.13-0 -> 0.6.1-0
 * ros-indigo-fetch-navigation: 0.5.13-0 -> 0.6.1-0
 * ros-indigo-fetch-teleop: 0.5.13-0 -> 0.6.1-0
 * ros-indigo-robot-calibration: 0.4.0-0 -> 0.5.2-0
 * ros-indigo-robot-calibration-msgs: 0.4.0-0 -> 0.5.2-0

New Fetch Packages:
 * ros-indigo-fetch-auto-dock-msgs: 0.5.2-0

A full list of new upstream packages can be found on the
`ROS mailing list <http://lists.ros.org/pipermail/ros-users/2015-July/069516.html>`_

June 8, 2015
------------
First publicly available release.

New Fetch Packages:
 * ros-indigo-fetch-drivers: 0.5.3-0
 * ros-indigo-fetch-depth-layer: 0.5.13-0
 * ros-indigo-fetch-description: 0.5.13-0
 * ros-indigo-fetch-driver-msgs: 0.5.1-0
 * ros-indigo-fetch-gazebo: 0.5.0-0
 * ros-indigo-fetch-gazebo-demo: 0.5.0-0
 * ros-indigo-fetch-moveit-config: 0.5.13-0
 * ros-indigo-fetch-navigation: 0.5.13-0
 * ros-indigo-fetch-teleop: 0.5.13-0

A full list of new upstream packages can be found on the
`ROS mailing list <http://lists.ros.org/pipermail/ros-users/2015-June/069467.html>`_
