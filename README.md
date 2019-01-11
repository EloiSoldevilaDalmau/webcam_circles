# webcam_circles

Exercise 2.2 of the Perception Systems course. Circle detection from online webcam images.

Like in exercis 2.1, to have the program running first we need to do some things. We start by forking the git repository https://github.com/beta-robots/webcam_circles, cloning it to our computer with the command

    $ git clone https://github.com/EloiSoldevilaDalmau/webcam_circles
and building the point_capture example.

To build it we create a directory called "build" inside the webcam_point_features directory

    $ mkdir build
and, being inside the new directory we need to compile and run it. First with

    $ cmake .. 
and then

    $ make 
To execute the example we write

    $ ./circle_detector
when inside the build directory.


Example of what can be seen when running the program with something with a circle shape in front of the camera:
<img src="images/circle_detector_1.png" width="500">
