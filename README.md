# cld1a0_pcl
cld1a0_pcl is a ROS package, which is designed to visualize 2D/3D distance dataset in real-time.
For more details in the 2D/3D ToF LiDAR, please visit http://www.cygbot.com

## How to build this package

### Preparation
1) Clone this project to your catkin's workspace
2) Run catkin_make

### Set-Up
```bash
roslaunch cld1a0 cld1a0.launch
```

## Parameters
The data types of 2D and 3D are 0 and 1 respectively as below:

2D)
<h1 align="left">
  <img src="screenshots/param_2d.png" width="600"/>
</h1>

3D)
<h1 align="left">
  <img src="screenshots/param_3d.png" width="600"/>
</h1>

### Fixed Frame
```bash
laser_link
```

### Topic
```bash
/scan
```