# Test Gazebo

Run in terminal
    
    gz sim

This may take a while as some of the textures and background items may not have downloaded correctly. 

# Test ROS

Run in terminal 1:

    source /opt/ros/kilted/setup.bash
    ros2 run demo_nodes_cpp talker

Run in terminal 2:

    source /opt/ros/kilted/setup.bash
    ros2 run demo_nodes_py listener

Extremely fast tests, should know almost immediately if the setups is communicating correctly between the "server" vs "client" terminal.
