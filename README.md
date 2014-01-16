# FaceFinder

Based off FaceTracker:
FaceTracker is a library for deformable face tracking written in C++ using OpenCV 2, authored by [Jason Saragih](http://jsaragih.org/) and maintained by [Kyle McDonald](http://kylemcdonald.net/).

This project is designed to be build inside the Eclipse CDT. You can just import this project and then set your opencv path


## `FaceFinder` Usage

It will output an image to the output specified only if a face is found

It will also return status code -1 for failure and 0 for success

````
Usage: FaceFinder input output [options]
Options:
-m <string> : Tracker model (default: model/face2.tracker)
-c <string> : Connectivity (default: model/face.con)
-t <string> : Triangulation (default: model/face.tri)

````
