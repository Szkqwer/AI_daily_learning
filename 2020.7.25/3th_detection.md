# 3th_detection 7.20~7.26
# Zekun Shi
当前目标检测的热门神经网络有R-CNN系列与yolo系列，R-CNN系列是将分类与检测分离，yolo系列是将两者一起做回归分析

At present, the popular neural networks for object detection include R-CNN series and yolo series. R-CNN series separates classification from detection, and Yolo series makes regression analysis together

https://zhuanlan.zhihu.com/p/27031704

# Tian Chen

# Wenke Huang
# Single Object

(Classification + Localization)

![objectdetectionsingleobject1](.https://github.com/WenkeHuang/Encyclopedia-of-Artificial-Intelligence/tree/master/img/CV/objectdetectionsingleobject1.png)

Update:

![objectdetectionsingleobject2](https://github.com/WenkeHuang/Encyclopedia-of-Artificial-Intelligence/tree/master/img/CV/objectdetectionsingleobject2.png)



Final:

![objectdetectionsingleobject3](https://github.com/WenkeHuang/Encyclopedia-of-Artificial-Intelligence/tree/master/img/CV/objectdetectionsingleobject3.png)



#  Multiple Objects

![objectdetectionmultipleobject1](https://github.com/WenkeHuang/Encyclopedia-of-Artificial-Intelligence/tree/master/img/CV/objectdetectionmultipleobject1.png)

**Region Proposals:** Selective Search

 ● Find “blobby” image regions that are likely to contain objects 

● Relatively fast to run; e.g. Selective Search gives 2000 region proposals in a few seconds on CPU

# Beyond 2D Object Detection

## Object Detection + Captioning = Dense Captioning

![Dense Captioning](https://github.com/WenkeHuang/Encyclopedia-of-Artificial-Intelligence/tree/master/img/CV/DenseCaptioning.png)

## Dense Video Captioning

![Dense Captioning](https://github.com/WenkeHuang/Encyclopedia-of-Artificial-Intelligence/tree/master/img/CV/DenseVideoCaptioning.png)

## Objects + Relationships = Scene Graphs

![Scene Graphs](https://github.com/WenkeHuang/Encyclopedia-of-Artificial-Intelligence/tree/master/img/CV/SceneGraphs.png)

## Scene Graph Prediction

![Scene Graph Prediction](https://github.com/WenkeHuang/Encyclopedia-of-Artificial-Intelligence/tree/master/img/CV/SceneGraphPrediction.png)

## 3D Object Detection

2D Object Detection: 2D bounding box

(x, y, w, h)

3D Object Detection:
 3D oriented bounding box

(x, y, z, w, h, l, r, p, y) Simplified bbox: no roll & pitch

Much harder problem than 2D object detection!

![3D Object Detection](https://github.com/WenkeHuang/Encyclopedia-of-Artificial-Intelligence/tree/master/img/CV/3DObjectDetection.png)

## 3D Object Detection: Simple Camera Model

A point on the image plane corresponds to a **ray** in the 3D space

A 2D bounding box on an image is a **frustrum** in the 3D space

Localize an object in 3D:
 The object can be anywhere in the **camera viewing frustrum**!

![Simple Camera Model](https://github.com/WenkeHuang/Encyclopedia-of-Artificial-Intelligence/tree/master/img/CV/SimpleCameraModel.png)

## 3D Object Detection: Monocular Camera

![3D Object Detection](https://github.com/WenkeHuang/Encyclopedia-of-Artificial-Intelligence/tree/master/img/CV/MonocularCamera.png)

## 3D Shape Prediction: Mesh R-CNN

![Mesh R-CNN](https://github.com/WenkeHuang/Encyclopedia-of-Artificial-Intelligence/tree/master/img/CV/MeshR-CNN.png)

# Reference 

[cs231 **Detection and Segmentation** Semantic segmentation Object detection Instance segmentation](http://cs231n.stanford.edu/slides/2020/lecture_12.pdf)

