# Where Am I?
## Saminda Abeyruwan

### Introduction

Mobile robot localization estimates the robot pose relative to a given map of the environment. This project empirically evaluates the Adaptive Monte Carlo Localization (AMCL) algorithm using Gazebo simulator and RViz visualizer. Using ROS framework, a baseline two- and custom four-wheeled mobile robot platforms with senors have been developed. The robots have used ROS AMCL and navigation stack packages for global localization and path planning. By tuning the AMCL and planner parameters, the robots have been localized on the map and successfully navigated to predefined target locations. 
Please refer to [writeup](writeup.pdf) for detail explanation.

### Installation Instructions

Please follow the [instructions](https://github.com/samindaa/RoboND-Localization-Project)
to setup ROS Kinetic environment. 

### Run the Project

First create a catkin workspace, if it is not already available.

```sh
$ mkdir -p ~/catkin_ws/src
$ cd ~/catkin_ws/
$ catkin_make
```

Then clone and build _udacity_bot_ project:

```sh
$ cd ~/catkin_ws/src
$ git clone https://github.com/samindaa/udacity_bot.git
$ cd ~/catkin_ws
$ catkin_make
$ source ~/catkin_ws/devel/setup.bash
```

To simulate the navigation tasks:

1. Udacity Bot:

```sh
$ roslaunch udacity_bot udacity_run.launch
```

2. Saminda Bot: 

```sh
$ roslaunch udacity_bot saminda_run.launch
```
 






