# Virtual Racetracks Collection

A ROS 1 training package with virtual race tracks displayed as markers in RViz. The [launch/](launch/) directory contains multiple track layouts; [scripts/](scripts/) contains small helpers for generating coordinate arguments.

**Original author:** Roberto Zegers. **License:** BSD 3-Clause. This repository is course and training material; the original attribution is retained.

## Explore a track

With a compatible ROS 1 installation and a catkin workspace:

```bash
cd ~/catkin_ws/src
git clone https://github.com/anirban2190/virtual_racetracks_collection.git
cd ..
catkin_make
source devel/setup.bash
roslaunch virtual_racetracks_collection race-track-26NKzM0j.launch
```

The example launch file publishes a track marker and starts RViz with the included configuration. Other layouts are available in [launch/](launch/). This package uses ROS 1 `catkin`, `rospy`, and `rviz`; it is not a ROS 2 package.

See [CONTRIBUTING.md](CONTRIBUTING.md) for contribution guidance and [LICENSE](LICENSE) for license terms.
