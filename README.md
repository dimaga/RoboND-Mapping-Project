# RoboND-Mapping-Project
My solution of "Map My World" project from Udacity Robotics Software Engineer course, Term 2

To launch the project:
1. Create your catkin workspace
2. Git-clone this repository into ```./src/slam_project``` folder of your catkin workspace
3. Git-clone https://github.com/ros-perception/depthimage_to_laserscan.git into ```./src/depthimage_to_laserscan``` folder
4. Git-clone https://github.com/introlab/rtabmap_ros.git into ```./src/rtabmap_ros``` folder.
5. ```catkin_make``` your workspace

If you have problems with ```rtabmap_ros``` package build due to RTABMAP ROS version compatibility issues between 0.18.1 and 0.18.2, go to rtabmap_ros package folder, type in ```git reset --hard 801bac52212971acddfe9390cf22f4e4841abdd6``` command from ```./src/rtabmas_ros``` folder, return to catkin workspace folder and ```catkin_make``` your workspace once again.

To restore 0.17.0 version of ```rtabmap_ros```, type in ```git reset --hard a39ffe382c4a72b969d18fe9c3ce2bbdb71e349e``` command from ```./src/rtabmas_ros``` folder.
