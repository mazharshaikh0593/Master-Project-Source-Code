For running MQTT based approach with mqtt_bridge follow below steps:

1. Download the 'mqtt_bridge' package to the your_workspace/src from "https://github.com/groove-x/mqtt_bridge" and compile using catkin_make.
2. Replace the file demo_params file in mqtt_bridge/config folder and compile again using catkin_make.
3. Launch the mqtt_bridge node.
4. Launch multi-mbot main launch file.

rrt_exploration is a work package created by Hassan Umari - https://github.com/hasauino/rrt_exploration

pioneer_gridmap_maz - Is a CoppeliaSim file of type .ttt which is a working simulation for generating map of an environment using 2D occupancy grid map plugin.
                      The grid map plugin is the work of Leopoldo Armesto - https://www.youtube.com/watch?v=fV0ZoDa1FaQ&list=PLjzuoBhdtaXOoqkJUqhYQletLLnJP8vjZ&index=58

pioneer_gridmap_maz_map - Is a CoppeliaSim file of type .ttt which is a simulation file which implements the intregration of ROS with CoppeliaSim for map generation using    'gmapping' package and ROS API interface. Unfortunately it is not generating complete map and work needs more research and further implementation.
