# ROS_Image_viewer
Viewing sensor_msgs/Image in the browser using HTML and Javascript

## Step 1: 
``` rosrun image_transport republish raw in:=/rgbd_FBL/depth/image_raw/compressed/compressed out:=/rgbd_FBL/depth/image_raw/compressed/compressed```

## Step 2: 
```roslaunch rosbridge_server rosbridge_websocket.launch```
