# raspimouse_navigation
Package for implement navigation on Raspberry Pi Mouse


# Requirements

This package requires the following to run:

* Ubuntu
  * Ubuntu 16.04 (Ubuntu 16.04 Server recomended)
* ROS
  * Kinetic Kame
* ROS Package
  * Raspberry Pi Mouse Controller - [ryuichiueda/pimouse_slam](https://github.com/ryuichiueda/pimouse_slam)

# Installation

First of all, install the latest stable version of ROS.
Please refer to [ROS WiKi](http://wiki.ros.org/kinetic/Installation) for installation.

Next, download the dependent ROS package into `~/catkin_ws/src` and build it.

```
cd ~/catkin_ws/src
git clone https://github.com/ryuichiueda/pimouse_slam.git
cd ~/catkin_ws && catkin_make && source ~/catkin_ws/devel/setup.bash
```

Finally, download this repository and build it.

```
cd ~/catkin_ws/src
git clone https://github.com/zaki0929/raspimouse_navigation.git
cd ~/catkin_ws && catkin_make && source ~/catkin_ws/devel/setup.bash
```

# Usage

It will be appended soon.
