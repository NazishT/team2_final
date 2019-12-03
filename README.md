# CSCI 4530/6530 Final Project



## TEAM MEMBERS
Linsey Briley    UG
<br>
Nazish Tahir     G
<br>
Javier Rodriguez G
<br>

## Husky github
https://github.com/husky/husky

## TO RUN THIS PACKAGE

Make sure to ```catkin_make``` in *catkin_ws* dir to build package before inital use.
```
$ roscore

$ export HUSKY_GAZEBO_DESCRIPTION=$(rospack find husky_gazebo)/urdf/description.gazebo.xacro

$ export GAZEBO_MODEL_PATH=$(rospack find team2_final)/worlds
```

  Create launch file to make world and bot → final.launch
<br>
```
$ roslaunch team2_final final.launch
```

  launch rviz to see lazer/kinect data and rviz
<br>
```
$ roslaunch husky_viz view_robot.launch
```


## NEEDS TO BE UPDATED TO INCLUDE SERVICE, ETC

  launch gmapping/hector slam/amctl
<br>
```
$
```

  launch A-star
<br>
```
$ roslaunch husky_navigation move_base_astar_dwa.launch
```
  launch computer vision
<br>
```
$
```



## NEED TO ADD VIDEO
