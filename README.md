# my-robot

This is a simple robot to be used in Gazebo. Built using the urdf format.

It has two wheels with joints and two sensors.

* Camera
* Lidar

When launching it will also display RViz to see what the sensors are reading.

## Usage

`catkin_make`

`source devel/setup.bash`

`roslaunch my_robot world.launch`

### Localisation

`roslaunch my_robot amcl.launch`


![](ref_images/green_robot.png)
