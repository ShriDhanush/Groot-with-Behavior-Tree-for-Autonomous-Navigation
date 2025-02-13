Please refer to the following page for Turtlebot3 installation:
https://zenn.dev/tasada038/articles/0a69eb6c6b444f

Install BehaviorTree.CPP 3.8x & Groot1.0:
https://zenn.dev/tasada038/articles/b7d193b567b94a

Using this Github repo:

1) Clone this repository in ur workspace and install tb3 and BT, Groot

2) build your workspace

3) Run the following in seperate (new) terminals :

a) cd ~/BehaviorTree/Groot/build/

  ./Groot

b) cd ~/turtlebot3_ws/

  . install/setup.bash
  
  ros2 launch turtlebot3_gazebo turtlebot3_jp_world_empty.launch.py

c) cd ~/dev_ws/

  . install/setup.bash
  
  ros2 run tb3_behavior_tree tb3_behavior_node
