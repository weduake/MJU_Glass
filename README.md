# MJU_Glass Dataset

## Overview

MJU_Glass is an RGB-D dataset created for glass surface segmentation from a service robot perspective. It contains 4,900 RGB images with aligned depth maps captured using two Orbbec Gemini Pro cameras mounted at different heights and angles on a wheeled robot platform.

The images were collected at Minjiang University, China, covering indoor and outdoor scenes such as offices, labs, corridors, and public areas, including challenging lighting conditions.

## Dataset Details

- Total images: 4,900  
- Training set: 3,430 images (70%)  
- Test set: 1,470 images (30%)  
- Difficult test subset: 400 images selected for challenging cases based on model performance, featuring strong light, high transparency, and complex scenes.

All RGB and depth images were resized to 640×480 pixels for uniformity.

## Dataset Structure

- `dataset/images.zip`: RGB images  
- `dataset/depth.zip`: Depth maps aligned with RGB images  
- `dataset/mask.zip`: Ground truth masks for glass segmentation  

## Usage

Download and unzip the dataset files. The dataset can be used to train and evaluate glass segmentation models.

## Citation

Please cite our work if you use this dataset.

## Repository

[https://github.com/weduake/MJU_Glass](https://github.com/weduake/MJU_Glass)
