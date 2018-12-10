# image_pub

ROS node to publish as an Image topic the content of a mp4 file.

## Build Intructions
Go to your catkin_ws folder location, for example `cd ~/catkin_ws/src`.

Download the source for this node by running

`git clone https://github.com/ladrians/image_pub`

Compile the code with `catkin_make`.

## Running the Node
Once you have the node built, you can run it using a launch file.

Run `roslaunch image_pub mp4.launch`

It will launch a sample mp4 file

## Node Information

Topics:

* `/camera_front_image_raw [sensor_msgs/Image]`:
  Default image topic
* `/camera/camera_info [sensor_msgs/CameraInfo]`:
  Default camera information

## Visualization

To visualize it, you can use the `rqt_image_view` utility.
