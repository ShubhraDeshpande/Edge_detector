# Edge_detector
We see that image is a two dimensional array of pixels. The task of edge detection is performed using sobel operator. Operating sobel operator on image and collecting the edges in ‘x’ and ‘y’ direction, program calculates the norm i.e. root mean square distance of every pixel of both matrices and define the resulting pixel as edge defining agent.

Very crude method of logical hard coding is used to complete this task hence no external library has been used. The task can be seen as collection of three main functions 

-Defining kernels or sobel filters for X and Y direction
-Defining convolution function 
-Calculating norm

Defining Kernels: Functions kernel-x(), kernel_y() define sobel operators as shown in figure 1.a

![the sobel operator](http://homepages.inf.ed.ac.uk/rbf/HIPR2/sobel.htm)

Kernel Gx filters out all the Y leading points and hence giving horizontal subpart of the image
Kernel Gy filters out all X leading points and gives vertical defining edges


