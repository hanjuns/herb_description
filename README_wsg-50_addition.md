## Instructions For WSG-50 Simulation Setup

1. Copy package into catkin work space.

2. Go to catkin work space directory.

3. Execute catkin_make. This will create all the urdf files in the following directory:
   
   (catkin work space name)/devel/share/herb_description/robots

4. The "herb_weiss.launch" file will launch the herb model with two wsg-50 grippers and is contained in the launch 
   folder. The rviz configuration file is saved in the rviz folder. The following command will launch the 
   referenced launch file:

   roslaunch herb_description herb_weiss.launch
   