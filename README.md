# A two-step deep learning-based framework for metro tunnel lining defect recognition
Aiming to quickly, accurately, and automatically recognize various defects (leakage, crack, spalling) from massive metro tunnel lining image data, a two-step deep learning-based framework is proposed.
![image](https://github.com/FY387/Deep-Learning-for-Tunnels/blob/main/Graphical%20Abstract.jpg)
In this repository, the datasets for metro tunnel lining image classification and multi-defect detection are shared for further research. Meanwhile, the algorithms proposed in the paper and related weight files are also shared.

# Contents
A metro tunnel lining image classification dataset

Image classification algorithms and model weights files generated from classification experiments

A metro tunnel lining multi-defect dataset for object detection

Object detection algorithms and model weights files generated from object detection experiments

# Dataset 1 - Metro tunnel lining image classification dataset


# Algorithm 1 - Tunnel lining image classification network (TLCNet)
The source code for TLCNet is placed in the folder named TLCNet-main.
The relevant model weight files can be downloaded from https://pan.baidu.com/s/1Uniz0kqg8PuFW3Ygv3I4rQ. 
Password: 6ui4.

# Dataset 2 - Metro tunnel lining multi-defect dataset for object detection


# Algorithm 2 - Tunnel lining defect detection network (TDDNet)
The source code for TDDNet is placed in the folder named TDDNet-main.
The relevant model weight files can be downloaded from https://pan.baidu.com/s/1hixgINiUfARwUx1xvKENow.
Password: 8t15.

# Experiments on the generalizability of models
The model generalization experiment in this research was conducted based on some open-source tunnel lining images from three studies[1-3].
[1]https://doi.org/10.1109/ICIP40778.2020.9190900
[2]https://doi.org/10.1016/j.tust.2023.105428
[3]https://doi.org/10.1016/j.tust.2020.103524
Based on the original images, our research team has made labels in VOC format to evaluate the performance of the classification model and the target detection model. The dataset can be downloaded from the link 
