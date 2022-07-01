# 3D-Model-from-2D-Slices
A cost efficient model that makes a 3D model of various parts of human body using their 2D slices

This project includes various different methods of image processing like binary thresholding, canny edge detection and K-means clustering to segment the region of our interest.

The goal was to visualize 2D images of any body organ in three-dimension. We were able to visualize our given dataset which consisted of ultrasound chest images using two approaches :
VTK’s marching cubes for isosurfaces and point cloud using pyvista.

We can move forward to improve the results by applying machine learning techniques for generating intermediate slices, for obtaining smoother 3D volume and better visualization. Preprocessing of ultrasound images can also be focused on to produce better results.
