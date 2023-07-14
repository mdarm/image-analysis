# Image Analysis Techniques with Python

This repository contains a wide range of image analysis techniques. Whether one is interested in computer vision, machine learning, or artificial intelligence, understanding these fundamental techniques is invaluable.

The exercises cover a wide range of topics in image analysis, from smoothing and segmentation to color spaces and morphological operations. The goal is to illustrate the use of several fundamental image processing techniques and how they can be implemented using Python libraries like NumPy, Matplotlib, and Scikit-Image. The project also touches upon feature extraction methods, a crucial aspect of machine learning and artificial intelligence.

The images used for analysis are located within the [datasets folder](datasets) and the resulting outputs are stored in the [outputs folder](outputs).

## Contents

1. **Image Loading and Display** - Loading an image using Matplotlib and displaying it for subsequent processing.

2. **Image Smoothing** - Application of Gaussian smoothing to reduce image noise and detail. Different types of smoothing filters like the Median filter, Gaussian filter, and Bilateral filter were explored and their impact on image noise reduction and detail preservation were examined.

3. **Edge Detection** - Use of the Canny edge detection method to identify the boundaries of objects within the image. Further, the Hough transform was utilized to identify lines and circles in images, and the effect of different parameters on the Hough transform was discussed.

4. **Image Segmentation** - Implementation of the Watershed algorithm to segment the image into different regions. Methods of applying morphological operations to improve the segmentation results were also explored.

5. **Color Spaces** - Converting the image to different color spaces (RGB, HSV, and LAB) to explore the benefits of each in image processing. Also, the effect of color space conversion on image processing tasks such as segmentation and edge detection was investigated.

6. **Morphological Operations** - Applying morphological operations, including Erosion, Dilation, Opening, and Closing on the image. The effects of these operations on image noise and detail preservation were discussed.

7. **Feature Extraction** - Extracting features from the image using the Histogram of Oriented Gradients (HOG) method, an essential step in object detection and image recognition tasks. A detailed discussion on the HOG feature descriptor and its implementation was carried out.

8. **Image Enhancement** - Various image enhancement techniques such as arithmetic operations, gray level transformations, and sharpening spatial filters were applied to transform one image into another. A pipeline of processes was proposed and implemented for this purpose.

9. **Image Similarity** - A comprehensive assessment of image similarity was carried out by blending two distinct similarity metrics: Mean Structural Similarity Index (MSSIM) and Normalized Mutual Information (NMI). The blend was controlled by the weights `w_mssim` and `w_nmi`.

10. **Angle Estimation** - The angle of the diagonal edges of a roof in an image was estimated using the Hough Transform. Similarly, the angle of a billiard cue in an image was estimated and the image was rotated based on this angle.

11. **Corner Detection** - The Harris corner detection algorithm was applied to identify corner points in an image. The detected corners were then used to locate the windows in the image.

12. **Image Combination** - Techniques such as edge detection, Hough Circle and Line Transformations, and pixel intensity thresholding were used to combine two images to generate a new image.
