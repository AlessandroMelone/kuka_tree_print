# kuka_tree_print

1) $ roscore
2) load the scene "iiwa_tf_tree_pub.ttt" on CoppeliaSim and start simulation
3) launch the file "kuka_print_tree.launch"

NOTE: the launch file do a remap of the name of the topic wich the node robot_state_publisher use to read the joint states

<remap from="joint_states" to="/sim_ros_interface/joint_states" />
