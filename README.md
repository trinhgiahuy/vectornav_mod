## vectornav_mod
A modified ROS Interface for the VectorNav IMU/GPS from https://github.com/dawonn/vectornav

## Integrate

Clone the repository and rename it to `vectornav`

Recompile the `ros_catkin_ws` 

```sh
$ cd ros_catkin_ws
$ catkin build vectornav -j32
```

If build do not based on dependencies

```sh
$ catkin build vectornav -j32 --no-deps
```
