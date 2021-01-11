# Self Driving Car Beta Testing Nanodegree
# Midterm - 3D Object Detection


In this project, we used real-world data from the Waymo Open Dataset, detected objects in 3D point-clouds and evaluted the detections results. The major tasks accomplished to complete the project:

1. Compute Lidar Point-Cloud from Range Image
2. Create Birds-Eye View from Lidar PCL
3. Model-based Object Detection in BEV Image
4. Performance Evaluation for Object Detection


## Compute Lidar Point-Cloud from Range Image

### TASK: Visualize range image channels

In the Waymo Open dataset, lidar data is stored as a range image. The range image is a two dimensional array. Its row is pitch, and its column is yaw, and it has two channels, range and intensity. This task is about extracting the "range" and "intensity" from the range image and converting the floating-point data to an 8-bit integer value range. 

<img src="http://sparkandshine.net/wordpress/wp-content/uploads/2016/02/dominating_sets_example2.png" alt="dominating_sets_example2"/>
*Fig. 2: The minimum dominating set of a graph*

