# Object Tracking using ROS and Simulink on Raspberry Pi

Copyright 2020 The MathWorks Inc.

## Introduction
This repository contains resources for deploying a ROS node on Raspberry Pi hardware using Simulink showcasing an object tracking example.

## Folder Structure
The repository has two examples which are located in two different folders:
1. ***PublishPi***: Deploy a standalone ROS node with vision and control algorithms and validate it from another Simulink model for visualization.
2. ***PublishSubscribePi***: Publish and Subscribe between a ROS node in Simulink and a standalone ROS node deployed onto Raspberry Pi.

The Raspberry Pi model has to be deployed on the hardware, whereas the Desktop model is to be run on the system. 

## Setup
1. Clone the repository.
2. Open MATLAB and navigate to *PublishPi* or *PublishSubscribePi* folder.
3. Open the Raspberry Pi model. Deploy the model on the hardware using Robot -> Build & Run. Installation of Raspberry Pi Support from Simulink would be necessary: 
https://www.mathworks.com/hardware-support/raspberry-pi-simulink.html
4. Open the Desktop model and **run** the model.

For any queries, contact the authors at roboticsarena@mathworks.con 