# icuas
# Exploration of GPS-denied environment using Depth Sensor on a UAV 
 		
Developed obstacle avoidance algorithm in ROS to guide and map a UAV across an uncharted territory using a depth camera and IMU as sensors while operating in a GPS-denied environment. 

It consists of your original package which has been modified by us according to your needs. We have modified the `session.yaml`and the Dockerfile, so that it builds and installs all the dependencies. The given `start.sh` can be used to launch the simulation.

The *custom_packages* folder contains the packages that were heavily modified by us to be used in this simulation. These packages must be placed in the *uav_ws/src* folder, and `catkin b` be used to build the packages.

In case of any errors, please contact

Vayam Jain - jainvayam@gmail.com
(Software and Avionics Head, UAS-DTU)

Arjun Gupta - arjun222gupta@gmail.com
(Avionics Technician, UAS-DTU)
