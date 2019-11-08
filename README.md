# Picknik UR5 Moveit Config

UR5 launch files, calibration data, and urdf files to simplify using the UR5.

Developed by Mike Lautman and Tyler Weaver at [PickNik Consulting](http://picknik.ai/)

## Feature Status

Currently Supported:

* Table collision object
* Calibration from UR5
* Simulation with Rviz
* Fake controller to test without hardware
* OEM UR Driver

Roadmap:

* UR modern driver
* Fully document arguments to launch files

## Example Use

The [ur5_examples](https://github.com/PickNikRobotics/ur5_examples) repo has examples for using these launch files.

## demo.launch
This is the primary launch file that uses other launch files to start the example.

### Simulation rosgraph

![Simulation Nodes](/doc/rosgraph_nodes_demo_simulation.svg)
![Simulation Nodes/Topics](/doc/rosgraph_topics_demo_simulation.svg)

### OEM UR Driver

![OEM UR Nodes](/doc/rosgraph_nodes_demo_oem.svg)
![OEM UR Nodes/Topics](/doc/rosgraph_topics_demo_oem.svg)

### UR Modern Driver

TODO(tylerjw): Update after demo.launch works with ur_modern driver

![UR Modern Nodes](/doc/rosgraph_nodes_demo_modern.svg)
![UR Modern Nodes/Topics](/doc/rosgraph_topics_demo_modern.svg)
