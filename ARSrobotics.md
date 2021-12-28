## Gazebo Robot to Navigate using ROS

**Project description:** This assignment tackle with the simpler version of a more general robotics question. How to make a robot navigate, search and recognise object safely? There are many challenges to realize this idea. In real world, we have many different road condition, various objects to recognise, very dynamic traffic condition with people walking around, this make the task a lot more difficult. 

### 1. Navigation
This model used Robot Operating System (ROS) navigation stack to navigate with the map. The navigation stack have many components work together to come out with a plan to navigate to a goal way point. The design involve a global planner which utilize the map acquired to plan out a path and a local planner which can adapt and improve the global plan locally by taking shorter path.

### 2. Self-Localization
The robot have problem with self-localization with limited sensor and knowledge of environment. A ROS built-in probablistic model has been implemented to make the robot localize itself in the map.

### 3. Computer Vision
We also implemented cv2 to do computer vision. Object detectoion is done by filtering out the colour we want and command the robot to walk towards the object when the condition is satisfied.

### 4. Proportional Integral Derivative (PID) Control
This is the biggest learning outcome of the project. The idea of PID control is very refreshing to me and I managed to implement them. I am amazed by how well the PID control perform.

