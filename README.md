# Line-Detection-Using-OpenCV


# 1. Load the image
![](images/original%20image.png)

# 2. Convert the image to grayscale & Reduce noise using Gaussian Blur 
![](images/gray%20image.png)

# 3. Find Lane lines using canny function
![](images/canny%20image.png)

# 4. Find Region of interest
![](images/region%20of%20interest.png)

# 5. Merge it with Canny image using Bitwise and operator to each pixel
![](images/nitwise%20and%20image.png)

# 6. Use Hough Transform to find the best fit line
![](images/line%20image%20unoptimise.png)

# 7. Optimize the lines using average slope and intercept 
![](images/optimise%20line%20image.png)

# 8. Repaeat the same steps for the video
![](images/Final%20image.png)

