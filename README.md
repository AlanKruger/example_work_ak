# My Example Work

<hr>

- This is the final demo of my thesis, "A Vision-Based Approach to Real-Time Trust Evaluation within Multi-Agent Systems" under the advisory of Dr. Sun Yi and the sponsorship of AFRL. This shows 2 heavily modified and autonomous TurtleBot3s in patrol_mode and follow_mode and a remote-controlled Bebop drone. Together, they are collaboratively mapping out the target area until I decide to hack 1 TurtleBot3 to demonstrate vision-based trust and its practical applications. {ROS Kinetic, C++, OpenCV, PCL, Python, TensorFlow, MATLAB, Jetson TX2, Ubuntu 16.04}

<img src="gifs/MAS.gif" width="720" height="405" />

<hr>

- This is a simulated lane detection algorithm using video footage my colleague, Kenny Lindsay, and I recorded in a real car and boulevard for real-world conditions. Intersections, bridges, and underexposure/overexposure are all areas of improvement. {ROS Kinetic, C++, Ubuntu 16.04}

<img src="gifs/bolt_lane_detection.gif" width="720" height="405" />

<hr>

- This is a third-scale toy car that has been modified by my colleague, Kenny Lindsay, that is running a spatial-maze solving algorithm I wrote with only LiDAR. In concert, we demonstrated it autonomously traversing the hallway, avoiding obstacles, and stopping for pedestrians for our sponsor, the DOD under ACCESS Labs. {ROS Kinetic, C++, Ubuntu 16.04}

<img src="gifs/third_scale_hall_detection.gif" width="720" height="405" />

<hr>

- This is a visualization of all the sensors aboard the Aggies' Autonomous Auto (A3). This includes The Imaging Source (TIS) camera-feed, 2 merged Velodyne LiDAR Pucks (second LiDAR shows white dots), and a Novatel Global Navigation Satellite System (GNSS). We used this data as inputs to our algorithms before testing. {ROS Kinetic, C++, Ubuntu 16.04}

<img src="gifs/bolt_sensors.gif" width="720" height="405" />

<hr>

- This is a simultaneous localization and mapping (SLAM) result of a portion of our campus using a Velodyne LiDAR Puck. {ROS Kinetic, Ubuntu 16.04}

<img src="gifs/campus_SLAM.gif" width="720" height="405" />

<hr>

- This is a simulation of way-point following. This Ackerman Model adjusts the front steering of this Chevy Bolt to follow the immediate (red) array of way-points. The curvature impacts the accelerator and braking responses to be able to make the turns without overshooting. It looks perfect, but keep in mind this is purely theoretical and does not use a physics engine like Gazebo. However, the algorithm we applied to drive this simulated car was used on the real car as well. {ROS Kinetic, C++, Ubuntu 16.04}

<img src="gifs/waypoint_follow.gif" width="720" height="405" />

<hr>

- Using my own data set of TurtleBot3 images, I trained them on a pre-built TensorFlow model, Coco SSD MobileNet V2, and achieved a usable sampling rate of 13-17 Hz onboard an NVIDIA Jetson TX2. {Python, TensorFlow, OpenCV, Jetson TX2, Ubuntu 16.04}

<img src="gifs/cnn_tb3.gif" width="720" height="405" />

<hr>

- This shows a trust algorithm using AR tag identification (ar_track_alvar ros package). {ROS Kinetic, C++, Jetson TX2, Ubuntu 16.04}

<img src="gifs/bebop_ar.gif" width="720" height="405" />

<hr>

- This shows a trust algorithm using sensor fusion. Image data was fused with LiDAR data in real-time achieving a sampling rate of 15 Hz. Yellow had the most issues in returning stable roll values. {ROS Kinetic, C++, OpenCV, Jetson TX2, Ubuntu 16.04}

<img src="gifs/bebop_fusion.gif" width="720" height="405" />

<hr>

- This is an autonomous chess-controller mode, patrol_mode, for this modified TurtleBot3. This would be a part of a mapping mission, so being slow and predictable while avoiding collisions was the goal. In contrast, follow_mode used a PD-controller to follow a selected agent and maintain a certain distance (shown in thesis demo above). {ROS Kinetic, C++, Jetson TX2, PCL, Ubuntu 16.04}

<img src="gifs/patrol_mode.gif" width="720" height="405" />

<hr>

- This car was made from scratch in Gazebo using a homemade Ackerman Steering model. I demonstrate the smooth and skid-free response while analyzing the steering data and displaying the feed from a ros-camera. {ROS Melodic, C++, Simulation, Ubuntu 18.04}

<img src="gifs/gazebo_car.gif" width="720" height="405" />

<hr>

- This is an algorithm that locates all objects nearby, sorts them out from nearest to furthest, and tracks their location and velocity all using just a Velodyne LiDAR Puck. This is intended to provide an input for a colleague's Clearpath Husky to autonomously navigate. {ROS Melodic, C++, PCL, Ubuntu 18.04}

<img src="gifs/auto_husky.gif" width="720" height="405" />

<hr>

- This shows decentralized and collaborative point cloud sharing. Mitigating the fidgeting of the data while robots move is an area of improvement. This is done without having to measure the distance between the robots; they sense each other and compensate for translation and rotation. {ROS Kinetic, C++, PCL, OpenCV, Jetson TX2, Ubuntu 16.04}

<img src="gifs/merged_SLAM.gif" width="720" height="405" />

<hr>

- This is a vehicle I designed as a hobby to do cool stuff with like autonomously following lane markings. Here, I am testing out the vehicle's responses to certain commands while sending image data to host laptop. {ROS Melodic, C++, OpenCV, Raspberry Pi OS}

<img src="gifs/hobby_car.gif" width="720" height="405" />

<hr>

- This is the lane detection algorithm the car will use to collect the set points that will be used by the controller. The vehicle was just gathering this data manually. {ROS Melodic, C++, OpenCV, Raspberry Pi OS}

<img src="gifs/hobby_lane_detection.gif" width="720" height="405" />
