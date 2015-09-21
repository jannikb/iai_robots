# Testing a camera in gazebo
```
roscore
roslaunch gazebo_ros empty_world.launch
roslaunch iai_test_camera upload.launch
rosrun gazebo_ros spawn_model -urdf -param robot_description -model camera_test
```

## Viewing the image
```
rgt
```

Plugins -> Visualization -> Image Viewer


## Something to look at
Use the gazebo client to drop something in front of the camera.
