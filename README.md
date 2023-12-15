# detect-shaking-of-camera-using-SIFT
In this notebook, I show that SIFT is robust but not invariant to the perspective view of the camera
## Description
The SIFT algorithm is one of the most useful algorithms for detecting corresponding points of 2 frames. 
In this practice. I want to show you although SIFT is invariant to the scale and rotation of a frame, it is robust(and not invariant) to the perspective view of a frame. 
## Details
This notebook considers some concepts like FlannBasedMatcher, BFMatcher, and SIFT. finally, I show that for cameras 1 and 3, the SIFT algorithm 
detects robust corresponding points in comparison with cameras 2 and 4. If you look at these frames carefully(each folder contains 2 frames that correspond to one camera)
you understand that the first and third cameras are stable while the 2 others are moving. Finally, based on the results of this practice, I indicate the methods of Video Stabilization
in computer vision.


