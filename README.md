# kinect_V2_raw_point_cloud_processing
Uses OpenNi to connect to the Microsoft Kinect V2. Make sure to download the Processing IDE and import the OpenKinect-for-Processing library. 

Used this code for point cloud object recognition project. Great for generating point cloud data and simple enough to modify for different use cases. 

DepthPointCloud.pde collects the entire area while DepthPointCloudThreshold.pde only collects points within a distance range. This was useful for creating models/ground truths for our point cloud object recognition project.

If running this code locally, please make sure to create a folder called either DepthPointCloud or DepthPointCloudThreshold depending on which version you would like to run. Also make sure to have the CameraParams.pde file and the data folder inside that folder.

