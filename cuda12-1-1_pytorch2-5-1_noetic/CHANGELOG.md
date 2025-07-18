Version 1.2.0 (Jul 18, 2025)
----------------------------

+ Installed `scikit-learn` package for DBSCAN pointcloud clustering

Version 1.1.0 (Jun 19, 2025)
----------------------------

+ Installed `norfair` package for object tracking

Version 1.0.0 (Jun 2, 2025)
----------------------------

+ Built from `nvidia/cuda:12.1.1-cudnn8-devel-ubuntu20.04`
+ Installed crucial packages:
  - ROS Noetic
  - CUDA 12.1.1
  - Pytorch 2.5.1
  - Ultralytics (YOLO object detection)
  - Detectron2 (instance segmentation)
  - Albumentations (data augmentation)
+ Added `nvidia-` and `libnvidia-` packages to `Unattended-Upgrade::Package-Blacklist {}`
+ Added aliases:
  - `cm = catkin_make`
  - `sd = source devel/setup.bash`
