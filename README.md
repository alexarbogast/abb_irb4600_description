# `abb_irb4600_description` package

This package contains URDF files and meshes for the **ABB IRB 4600** robot.

<p align="center">
  <img src=https://github.com/alexarbogast/abb_irb4600_description/assets/46149643/08e91f96-9ef0-455e-9b88-d4b86603e103 width=250/>
</p>

## Installation

Create a catkin workspace and clone the repository locally.

```shell
mkdir -p catkin_ws/src  && cd catkin_ws/src
git clone git@github.com:alexarbogast/abb_irb4600_description.git
```

Build the ROS package

```shell
cd ../
catkin build
```

## Run the demo

After installation run the following command to visualize the robot:

```shell
roslaunch abb_irb4600_description abb_arm_description.launch
```

## Further Assistance

- [ABB IRB 4600](https://new.abb.com/products/robotics/robots/articulated-robots/irb-4600)
- [ROS URDF Tutorial](https://wiki.ros.org/urdf/Tutorials)
