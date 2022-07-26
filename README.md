# Turtlebot_final_project
## modified copy of Turtlebot3 SLAM Simulation tutorial.
#### Comes with maze world model file. Configured to find the file automatically without placing it in the default Gazebo model folder (.gazebo/models)
#### Spawns Turtlebot at center of maze (as defined in launch/my_world.launch)
To improve mapping performance, edit config/gmapping_params.yaml

**To set up Git:**
1. check if git is already installed: `git --version`
2. If not installed, follow this https://git-scm.com/book/en/v2/Getting-Started-Installing-Git (ignore the building from source stuff)
3. Install vscode: `sudo snap install --classic code`
4. Follow this to set up user.name,user.email: https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup
5. Navigate to your ros workspace/src folder (catkin_ws/src or other) and git clone from my turtlebot_final_project repo

From there, just devel/setup.bash and you should be able to start running it.

**To run project:**
1. Navigate to ws folder
2. Run: `source devel/setup.bash`
3. Run: `roslaunch final_project my_world.launch`
4. Run: `roslaunch final_project slam.launch`
5. To use teleop: `roslaunch turtlebot3_teleop turtlebot3_teleop_key.launch`