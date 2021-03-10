# LAVDNet
Light-weighted Autonomous Vehicle Driving Network

## Description

This repository is for the paper 'LAVDNet: A Light-weighted Network Towards Addressing Drivable Area Detection and Autonomous Navigation', by [ZHANG Zhanpeng](<https://github.com/phosphenesvision>), QIN Jiahu and [WANG Shuai](<https://github.com/wsustcid>)

## Usage

The source code is under review, will be open sources soon.



## CULane-LAVD Dataset

CULane-LAVD Dataset is available at 

```
CULane-LAVD
├── driver_23_30frame ## trainset part1
├── driver_37_30frame ## testset part1
├── driver_100_30frame ## trainset part2
├── driver_161_30frame ## testset part2
├── driver_182_30frame ## trainset part3
├── driver_193_30frame ## testset part3
├── laneseg_label_w16 ## just ignore the directory, delete it
└── list ## txt files of the image paths and the label paths

```

explanations of the labels

```
## lane label txt file
xxxxx.lines.txt
keypoint1_x keypoint1_y keypoint2_x keypoint2_y keypoint3_x keypoint3_y ......

## obstacle label txt file
xxxxxob.txt
label x_center y_center width height 
#The coordinates are be scaled [0, 1]
#label corresponds to the row number of the class name
```



## Reproducing the Results

Re-training of LAVDNet

source code is under review, will be open sources soon.



## Sample Demonstration

The demo video is available at . 