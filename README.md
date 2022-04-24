ENPM661: Project 4
---------------------------------------------------------------------------------------------------------------
Name: Joseph Pranadeer Reddy Katakam
UID: 117517958

Name: Bharadwaj Chukkala
UID: 118341705

----------------------------------------------------------------------------------------------------------------

Project 4: Picking and Placing an object (in Rviz) on a custom created Table (.stl file), while having an obstacle in the work environment.

GitHub Link: https://github.com/roboticistjoseph/pick_and_place_using_panda_serial_manipulator

Video Drive Link: https://drive.google.com/drive/folders/1XFZpRhO46K4BW6bGGjnpWKlbma2VAts4?usp=sharing

-----------------------------------------------------------------------------------------------------------------

Project Description:
1. The Panda Serial Manipulator was used as the robot for picking and placing an object.
2. Using moveit assistant and panda robot urdf.xacro file, the panda_moveit_config package is created where assigning the controllers, move groups, poses etc were done.
3. A custom created Table was imported into the RViz.
4. An Object (for pick and place operation) and an obstacle (to avoid collision) are created.
5. The manipulator pose configuration for start and goal node, adding objects to collision list, grasping operations were written in cpp.


Instructions to Run the Code:

- Open the rviz environmnet with panda robot: "roslaunch panda_moveit_config demo.launch"
- Press 'ADD' in rviz console and add 'Motion Planning'
- Performing operation: "rosrun panda_moveit_config pick_place_node"

Outputs:
- Pick and Place operation video from Side View.
- Pick and Place operation video from Top View.
