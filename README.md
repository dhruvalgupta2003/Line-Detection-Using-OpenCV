# Line-Detection-Using-OpenCV


# 1. Load the image
![](https://media.discordapp.net/attachments/1123630739213258834/1177233737851875389/original_image.png?ex=6571c35b&is=655f4e5b&hm=a36f6e552e0a399cff799fbb8812b7d6934b8e3e89e81536935265d9c8ff1e1a&=&format=webp&width=1000&height=575)

# 2. Convert the image to grayscale & Reduce noise using Gaussian Blur 
![]([images/gray%20image.png](https://media.discordapp.net/attachments/1123630739213258834/1177233736740384838/gray_image.png?ex=6571c35a&is=655f4e5a&hm=6592b8f50e3deb3fb853872da3987fc8013ac637215382d146c0d5902a28c303&=&format=webp&width=1010&height=575))

# 3. Find Lane lines using canny function
![]([images/canny%20image.png](https://media.discordapp.net/attachments/1123630739213258834/1177233735310127164/canny_image.png?ex=6571c35a&is=655f4e5a&hm=885e88c4fc56b65da24594946819c5801016713775e98f6d56786b2ced90f948&=&format=webp&width=1000&height=575))

# 4. Find Region of interest
![]([images/region%20of%20interest.png](https://media.discordapp.net/attachments/1123630739213258834/1177233738237747251/region_of_interest.png?ex=6571c35b&is=655f4e5b&hm=af4f238df4a7c036fc610613a3d7d45e5776c4c60277e7948a8410419c6844a7&=&format=webp&width=998&height=575))

# 5. Merge it with Canny image using Bitwise and operator to each pixel
![](https://media.discordapp.net/attachments/1123630739213258834/1177233734781640845/bitwise_and_image.png?ex=6571c35a&is=655f4e5a&hm=2abc77caee2bd6b1965973bd5d5d921e43b36428e965dcde7e0b6a8fee0bb6f2&=&format=webp&width=1006&height=575)

# 6. Use Hough Transform to find the best fit line
![](https://media.discordapp.net/attachments/1123630739213258834/1177233737172394064/Line_image_unoptimise.png?ex=6571c35a&is=655f4e5a&hm=1d6da808c697d72c84a55f97e74f40516367447710f737b42af36e57aa7c6e53&=&format=webp&width=1023&height=575)

# 7. Optimize the lines using average slope and intercept 
![](https://media.discordapp.net/attachments/1123630739213258834/1177233737172394064/Line_image_unoptimise.png?ex=6571c35a&is=655f4e5a&hm=1d6da808c697d72c84a55f97e74f40516367447710f737b42af36e57aa7c6e53&=&format=webp&width=1023&height=575)

# 8. Repaeat the same steps for the video
![](https://media.discordapp.net/attachments/1123630739213258834/1177233736346124408/Final_image.png?ex=6571c35a&is=655f4e5a&hm=4e226b01dbbdc8e77fba4f81243c88841929753abd0e00e47fb53d9314de6806&=&format=webp&width=1000&height=575)

