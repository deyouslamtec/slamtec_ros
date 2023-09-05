# slamtec_ros

## How to deploy slamtec_ros

```bash
git clone --recurse-submodules https://github.com/deyouslamtec/slamtec_ros.git
```

```bash
cd slamtec_ros

rosdep install -y -r -q --from-paths src --ignore-src --rosdistro noetic

source /opt/ros/<Your ROS_DISTRO>/setup.bash

catkin_make

source devel/setup.bash
```
