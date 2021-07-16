# project-pcb

Small project on computer vision, classification of pcbs based on cnn and Feature matching(SIFT, SURF) and knn based matcher for finding the best match among all categories.

So this was a small 3 day project i did last week.

## The objectives of this small projct are as follows: 

We have **60 images** with **12 different types of
pcbs** . 
![image](https://user-images.githubusercontent.com/32160223/125993367-2fae5318-9ffb-4cfb-9454-0592f2084e5e.png)


And we are supposed to do following things with it-

Objective 1. To classify the testing PCB images into corresponding categories(12 categories).
Objective 2. To identify whether the given image has PCB or Not in real time?



## **CONCLUSION**

For Objective 1: I  used the approach of classical compurer vision feature matching technique that are robast to the position and angle of observation of pcb in image taking 12 images as query(training) with 37 images  as testing. And got the accuracy of 68% on testing images.

![image](https://user-images.githubusercontent.com/32160223/125993448-55474dd1-b6e2-4ce3-8856-2a3eba06964e.png)
![image](https://user-images.githubusercontent.com/32160223/125994589-4aec3796-4a73-4dce-949a-4c5f7c969b0d.png)


For Objective 2: I used the deep learning approach of training a small cnn with dropout network with augmentation of data(320 images more generated from 60 for both classes). And got the accuracy of 92% on testing images.

![image](https://user-images.githubusercontent.com/32160223/125993578-57234c3f-7dd8-4f46-806a-49d2e7ed51df.png)
![image](https://user-images.githubusercontent.com/32160223/125993593-2ef21071-363c-429e-b35a-d1d554afbb34.png)


