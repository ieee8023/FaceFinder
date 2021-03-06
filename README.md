# FaceFinder


<img src="https://raw.github.com/ieee8023/FaceFinder/master/joe-found.png"/>

Based off FaceTracker:
FaceTracker is a library for deformable face tracking written in C++ using OpenCV 2, authored by [Jason Saragih](http://jsaragih.org/) and maintained by [Kyle McDonald](http://kylemcdonald.net/).

## Changes from `FaceTracker`:

+Compiles for Linux (Ubuntu) with makefile
+Also setup config files for the Eclipse CDT. You can just import this project and then set your opencv path
+setup to batch process images for faces


## `FaceFinder` Usage

It will output an image to the output specified only if a face is found

It will also return status code -1 for failure and 0 for success

To build on Ubuntu Linux you need: 

sudo apt-get install libcv-dev libopencv-dev


````
Usage: facefinder input output [options]
Options:
-m <string> : Tracker model (default: model/face2.tracker)
-c <string> : Connectivity (default: model/face.con)
-t <string> : Triangulation (default: model/face.tri)

````
