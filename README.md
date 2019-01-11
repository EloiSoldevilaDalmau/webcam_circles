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


# How the program works: Hough Transforms

This program is able to detect circles using Hough Transforms. The hough transform is a technique that can be used to isolate features of an image of a particular shape (lines, circles or any parametric curve and combination).

!!!!! explicar com funciona la Hough Transform!!!!!!!


Also the program gives information about the size and center of the circle so it can be used in numerous applications.

References:

http://homepages.inf.ed.ac.uk/rbf/HIPR2/hough.htm

https://www.uio.no/studier/emner/matnat/ifi/INF4300/h09/undervisningsmateriale/hough09.pdf

http://people.scs.carleton.ca/~c_shu/Courses/comp4900d/notes/lect10_hough.pdf

https://docs.opencv.org/2.4/doc/tutorials/imgproc/imgtrans/hough_lines/hough_lines.html
