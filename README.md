# Drowsiness-Detection
A motion-based detector that will help detect the driver's eyes whether or not the driver is sleepy or drowsy.The general flow of our drowsiness detection algorithm is fairly straightforward. First, we’ll setup a camera that monitors a stream for faces,if a face is found, we apply facial landmark detection and extract the eye regions. Once the region is identified we check the eye aspect ratio and set an alarm if the ratio is less than the calculated. 

![image](https://user-images.githubusercontent.com/50576454/116205160-16202500-a75b-11eb-81ef-93d9989f11bb.png)


**For more information on this you can review the following sites for reference :** 
1. https://www.kaggle.com/adinishad/driver-drowsiness-using-keras
2. https://towardsdatascience.com/drowsiness-detection-with-machine-learning-765a16ca208a

**Reference Papers (that helped me work along):**
1. https://ieeexplore.ieee.org/abstract/document/8261140
2. https://www.mdpi.com/2076-3417/10/8/2890/pdf

