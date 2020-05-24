
# Bedsore Patient's Pose Classification Based-on Human Skeleton

This is my first project that I'm working with Machine Learning .Hope you guys enjoy!

## Preparation

for this project you should read the requirements software in [requirements.txt](requirements.txt) first

in this project we have to use [tf-pose-estimation](https://github.com/ildoonet/tf-pose-estimation) or [openpose](https://github.com/CMU-Perceptual-Computing-Lab/openpose) for pose estimation software (if you don't this program will not be able to run)


## Installation Guide

### 1. just git or download this project to your dir
```
git clone https://github.com/northnpk/OPEN-BS.git
cd OPEN-BS/
```

### 2. run

To run the code use 
```
python3 01_OPENBS_Test.py
```
or
```
python 01_OPENBS_Test.py
```
I've try it on Python version 3 but on python 2 It could be run on.

## run on video file
```
python3 01_OPEN-BS_Test.py \
    --model_path model/trained_classifier.pickle \
    --data_type video \
    --data_path data_test/video.avi \
    --output_folder output
```
## run on a folder of images
```
python3 01_OPEN-BS_Test.py \
    --model_path model/trained_classifier.pickle \
    --data_type folder \
    --data_path data_test/path \
    --output_folder output
```
## run on webcam
```
python3 01_OPEN-BS_Test .py \
    --model_path model/trained_classifier.pickle \
    --data_type webcam \
    --data_path 0 \
    --output_folder output
```

## This program can work on CPU but if you need to use it on GPU

please read the requirement software from [tf-pose-estimation](https://github.com/ildoonet/tf-pose-estimation)

and I Recommently !! you should use Nvidia GPU (at least GTX 1060) and check about tensorflow build with CUDA and cuDNN versions support (Yes I have my own with RTX 2060 and have a lot of problem with tensorflow version and CUDA version)

Before you go please don't use this for commercial until I update this Project with higher accuracy.

And This project was supported by JSTP and NSTDA before use it please check [LICENSE.txt](LICENSE.txt)

Thanks!
