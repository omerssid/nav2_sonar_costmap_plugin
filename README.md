# nav2_sonar_costmap_plugin

## Setup
1. clone this into a ROS2 workspace
2. build the package
```
colcon build --packages-select nav2_sonar_costmap_plugin --symlink-install
```
3. Add to plugins list in `nav2_params.yaml' as 'sonar_layer' for global/local costmap 


## References
- [Nav2 Range Layer](https://navigation.ros.org/configuration/packages/costmap-plugins/range.html)

- [Writing a New Costmap2D Plugin](https://navigation.ros.org/plugin_tutorials/docs/writing_new_costmap2d_plugin.html)
