# Local Image Descriptors

This repository is based on chapter 2 of the book *Programming Computer Vision with Python* by Jan Erik Solem. Which solve the example proposed about features matching using Harris corners detector. Further, a solution is give for the first proposed problem at the end of the chapter. These solutions are developed with Python with the iPython notebook tool.
In addition, this same problem is solved using the OpenCV open source tool by implementing the SIFT detector.

## Files

* ``ch02-harris-example.ipynb`` developed the example proposed at the beginning of the chapter 2. Here we use the functions defined across the chapter for find correspondences between points in two images. This example is developed with a pair images that you can change for proof the algorithm (In ``Data`` there ara other images to try).

* ``ch02-ex1.ipynb`` give solution to the first proposed problem of chapter. This file modify ``match`` and ``match_twosided`` functions introduced in the ``ch02-harris-example.ipynb`` code. The principal idea is find matches between images points within a radius specified by usuer. By default this search radius is set to 100 px, but you can test with another value.

* ``SIFT_detector.ipynb`` Solution is given to the same problem of the calculation of characteristic points and to the look correspondences using the SIFT detector implemented with the OpenCV library.