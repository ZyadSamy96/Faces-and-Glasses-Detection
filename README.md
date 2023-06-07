# Faces-and-Glasses-Detection
Achieved face detection by utilizing OpenCV, applied deep learning to detect that the image contains glasses or not by using pretrained model “MobileNet-V2” to fine tune the performance.

# Steps of project 

## Data Exploration 
- 1- Diplay some samples of the Data 
- 2- Data Balance Check
- 3- Split the data into trainning folder and validation folder

## Building models

#### a) Conv Model
- 1- Used Data Augmentation 
- 2- Used Simple Architecture

#### b) Pre-Trained Model (MobileNet-V2)
- 1- Used Data Augmentation 
- 2- Freezed Conv Base 

#### c) Fine Tunning Stage
- 1- Unfreeze Some Layers


![image](https://github.com/ZyadSamy96/Faces-and-Glasses-Detection/assets/94635686/73d25292-dbed-4667-bacf-f8027af12137)
###### Note that first 20 epochs concerned with stage (a) and the last 20 epochs concerned with stage (b)

# Prediction Results 
![image](https://github.com/ZyadSamy96/Faces-and-Glasses-Detection/assets/94635686/db4e3e99-5dde-41d8-829f-04ba8d647093)

# _______________________________________________________________________________________________________________________________________

# Face Detection 
![Face Detection_GIF](https://github.com/ZyadSamy96/Faces-and-Glasses-Detection/assets/94635686/7b0bb663-5967-4c99-9197-02f4ffe8646f)

# Face and Glasses Detection 

![Glasses an No-Glasses with Face Detection_GIF](https://github.com/ZyadSamy96/Faces-and-Glasses-Detection/assets/94635686/6ece336a-3d5b-4b81-8ec2-7b02c5e042fe)
