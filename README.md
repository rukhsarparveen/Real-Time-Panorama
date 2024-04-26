This project is an implementation of the research paper Automatic Panoramic Image Stitching using Invariant Features by Matthew Brown and David G. Lowe.


Implementation Steps:  
I. Extract SIFT features from all n images

II. Find k nearest-neighbours for each feature

III. For each image: 
      
      (i) Find geometrically consistent feature matches using RANSAC to solve for the homography between pairs of images.
      
      (ii) Stitch and Blend each image to form a panorama.

OUTPUT: Panoramic image
