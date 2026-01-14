# Dark-Image-Feature-Detection

***CA1 from EE5731 Computer Vision of NUS***

***The project is intended solely for practice and learning purposes; any other use is prohibited.***

This project consists of two main computer vision tasks:
## Task 1: Feature Detection in Ultra-Dark Images with Enhancement Techniques

-Implement Canny edge detection and Harris corner detection from scratch

-Analyze histograms of dark (Dark-1) and bright (GT1) images

-Implement histogram equalization (HE) manually and apply to dark image

-Test feature detection on HE-enhanced image and compare results

-Implement additional enhancement method and analyze performance differences

-Compare results across original dark, HE-enhanced, custom-enhanced, and bright images

## Task 2: Fundamental Matrix Estimation for Stereo Image Pair

-Manually select corresponding feature points in stereo image pair (GT1 and GT2)

-Implement normalized 8-point algorithm from scratch to compute fundamental matrix

-Visualize epipolar lines for selected points

-Analyze epipolar geometry and camera position relationships

-Test epipolar constraint on new points not in the original set

## Key Technical Requirements:

-Prohibited: Using built-in functions for Canny, Harris, histogram equalization, fundamental matrix computation, or epipolar line calculation

-Required: Manual implementation of all core algorithms

-Required: Detailed analysis and discussion of results at each step

-Optional: Image conversion to grayscale or resizing with proper documentation

## Learning Objectives:

-Understand challenges of feature detection in low-light conditions

-Evaluate effectiveness of different image enhancement methods

-Master fundamental matrix computation and epipolar geometry principles

-Develop practical implementation skills for core computer vision algorithms
