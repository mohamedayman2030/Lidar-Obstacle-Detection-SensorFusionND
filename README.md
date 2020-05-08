# Lidar obstacle detection
in this project , point cloud data are fed through PCD processor , the road is represented onn green and the obstacles are represented on multiple colors with bounding boxing are placed around these obstacles 

<img src="https://video.udacity-data.com/topher/2019/March/5c85992d_pcdstreamdetection/pcdstreamdetection.gif" width="700" height="400" />

## Installation

### Linux Ubuntu 16

Install PCL, C++

The link here is very helpful, 
https://larrylisky.com/2014/03/03/installing-pcl-on-ubuntu/

A few updates to the instructions above were needed.

* libvtk needed to be updated to libvtk6-dev instead of (libvtk5-dev). The linker was having trouble locating libvtk5-dev while building, but this might not be a problem for everyone.

* BUILD_visualization needed to be manually turned on, this link shows you how to do that,
http://www.pointclouds.org/documentation/tutorials/building_pcl.php

#### Build instructions
1. cd to build
2. cmake ..
3.make
4. run ./environment
