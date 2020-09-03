### This repository may be no longer maintained.
---
# 3D Reconstruction with RealSenseD435
Some personal implementation of 3d reconstruction with Realsense D435.

## Contents
* **Basic**
> 1.capture RGBD pointcloud and save RGBD images

> 2.Record RGBD stream as '.bag' file

> 3.Read RGBD '.bag' file
* **3D Object Reconstruction Based on Muti-view RGBD Images Using An A4 paper**
> Using an A4 paper to reconstruct an object's 3d pointcloud.

* **Realtime 3D Reconstruction Using Double Opposing RealSenses**
> Using a double side chessBoard to realtime registrating pointclouds from two opposite rgbd camera.

* **Object Recognition Using PointNet**
> Realtime 3d object partial pointcloud recognition based on PointNet.
 
* **Object Pose Estimation Using DenseFusion**
> Realtime object pose estimation using DenseFusion.

## Screenshots
<img src="./Doc/workbench.jpg" height="200" width="" >

point cloud of a toy dog

<img src="./Doc/dog.gif" height="200" width="" >

realtime registration of pointclouds from two cams.

<img src="./Doc/doubleCam.gif" height="200" width="" >

Realtime object recognition using PointNet.

<img src="./Doc/3d_recognition.gif" height="300" width="" >

Realtime object pose estimation using DenseFusion.

(Using the box's pose to control the virtual dog model's pose)

<img src="./Doc/obj_three.gif" height="300" width="" >

