# Face Detection Using HOG

![View Private Cody Leaderboard on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)

### Problem_1.m 
This files implements the User created HOG.m function.

1. HOG.m - This implements HOG function from scratch, without using any matlab functions. It uses the supporting functions that are created without using any inbuilt functions.
2. filter_image.m - This is used to calculate image gradient along x and y axis.
3. get_gradients.m - This is used to calculate gardient magnitude and angle.
4. build_histogram.m - This is used to create Histogram of gradients.
5. create_HOG_features_image.m - This is used visualize the HOG created by build_histogram functions.
6. get_block_descriptor.m - This functions is used to nomralize the HOG features created by build_histogram.m.

### Problem_2.m 
This files implements the face detection using HOG features.

1. face_detector.m - This functions uses HOG functions and sliding window to find faces in images . This returns the blocks or faces found.



