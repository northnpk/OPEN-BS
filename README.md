
# Bedsore Patient's Pose Classification Based-on Human Skeleton

This is my first project that I'm working with Machine Learning .Hope you guys enjoy!

## Installation Guide

### 1. just git or download this project to your dir
```
git clone https://github.com/northnpk/OPEN-BS.git
cd OPEN-BS/
```

### 2. check the requirements software in [requirements.txt](requirements.txt)

### 3. to get skeleton keypoint (pose estimation library) you have to install [tf-pose-estimation](https://github.com/ildoonet/tf-pose-estimation) first (if you don't this program will not be able to run)

### 4. run

To run the code use 
```
python3 01_OPENBS_Test.py
```
or
```
python 01_OPENBS_Test.py
```
for this version, you can use video source from webcam (automatically)

## This program can work on CPU but if you need to use it on GPU

please read the requirement software from [tf-pose-estimation](https://github.com/ildoonet/tf-pose-estimation)

and I Recommently !! you should use Nvidia GPU (at least GTX1060) and check about tensorflow build with CUDA and cuDNN versions support (Yes I have my own with RTX2060 and have a lot of problem with tensorflow version and CUDA version)

Before you go please don't use this for commercial until I update this Project with higher accuracy.
