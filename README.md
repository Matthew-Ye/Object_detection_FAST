# Object Detection by FAST

This is about object detection, corner detection and feature matching. In this report, I’m going to introduce a brief description of the FAST, BRIEF and ORB and their implementations to images. During the implementations parts, I compute the keypoints of images and compare the keypoints between two images to find matches. The result will be showed below so that we could use the matches to find a general mapping between the images and align other images in the future.

FAST (Features from Accelerated Segment Test) is a common cornor detector and basically can be divided to two steps: Feature Detection and Machine Learning.

The implementation is by openCV in python. Please check the report `report.pdf` to get more details.


