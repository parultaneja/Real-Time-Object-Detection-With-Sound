# Real-Time-Object-Detection-With-Sound
A Real Time Object detection using Single Shot Detectors and MobileNets and OpenCV Deep Neural Network Module.


# Single Shot Detectors
When it comes to deep learning-based object detection there are three primary object detection methods that you’ll likely encounter:
1. Faster R-CNNs 
2. You Only Look Once (YOLO) 
3. Single Shot Detectors (SSDs)
Faster R-CNNs are likely the most “heard of” method for object detection using deep learning; however, the technique can be difficult to understand (especially for beginners in deep learning), hard to implement, and challenging to train.
Furthermore, even with the “faster” implementation R-CNNs (where the “R” stands for “Region Proposal”) the algorithm can be quite slow, on the order of 7 FPS.
If you are looking for pure speed then we tend to use YOLO as this algorithm is much faster, capable of processing 40-90 FPS on a Titan X GPU. The super fast variant of YOLO can even get up to 155 FPS.
The problem with YOLO is that it leaves much accuracy to be desired.
SSDs, originally developed by Google, are a balance between the two. The algorithm is more straightforward than Faster R-CNNs.

# MobileNets: Efficient (deep) neural networks
MobileNets, another paper by Google researchers. They are called “MobileNets” because they are designed for resource constrained devices such as your smartphone. MobileNets differ from traditional CNNs through the usage of depthwise separable convolution.
The general idea behind depthwise separable convolution is to split convolution into two stages:
1. A 3×3 depthwise convolution.
2. Followed by a 1×1 pointwise convolution.
This allows us to actually reduce the number of parameters in our network.

# Combining MobileNets and Single Shot Detectors
 The combination of MobileNets and Single Shot Detectors for fast, efficient deep-learning based object detection. If we combine both the MobileNet architecture and the Single Shot Detector (SSD) framework, we arrive at a fast, efficient deep learning-based method to object detection. The MobileNet SSD was first trained on the COCO dataset (Common Objects in Context) and was then fine-tuned on PASCAL VOC reaching 72.7% mAP (mean average precision).
We can therefore detect 20 objects in images (+1 for the background class), including airplanes, bicycles, birds, boats, bottles, buses, cars, cats, chairs, cows, dining tables, dogs, horses, motorbikes, people, potted plants, sheep, sofas, trains, and tv monitors.

# Libraries 
1. Numpy 
2. OpenCV

# Requirements
1. Pycharm/ Python 3.7 
2. OpenCV

# Testing 
1. Clone the repository.
2. Install the dependencies.


# Copyright
See (https://github.com/parultaneja/Real-Time-Object-Detection-With-Sound/blob/master/LICENSE) for details. Copyright (c) 2019
