# ROS_Motion
Moving Turtlesim robot in a straight Line, rotating left and right, Go to goal Location,Spiral control and cleaning application.

# Linux Commands:

```
Motion in ROS(building robot cleaning application):

$catkin_create_pkg turtlesim_cleaner geometry_msgs rospy
$catkin_make
$rosrun turtlesim turtlesim_node
$rostopic list
$rostopic info /turtle1/cmd_vel
```
