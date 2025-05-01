# Solar Panel Defect Detection using MobileNetV3Small

This project identifies defects in solar panels using a Convolutional Neural Network based on the **MobileNetV3-Small** architecture. The model is trained on a Kaggle dataset and slightly modified from an existing implementation to achieve improved accuracy.

## Overview

- Uses a lightweight CNN (MobileNetV3Small) for efficient defect detection.
- Based on an existing Kaggle notebook with minor modifications and tuning.
- Achieved slightly better performance compared to the original.
- The model used is optimized for mobile and edge devices, so it can be easily deployed en masse.

## Dataset

The dataset used for training and evaluation is available on [Kaggle](https://www.kaggle.com/datasets/pythonafroz/solar-panel-images).

## Original Code Reference

The base code was adapted from [this Kaggle notebook](https://www.kaggle.com/code/burakksz/using-mobilenetv3-efficient-computing-94-350).

## Modifications Made

- Added class weights to counter imbalanced dataset.
- Miscellaneous minor tweaks.

## Discarded Modifications

The following modifications were tried but discarded due to either not improving the accuracy or decreasing it altogether.

- Learning Rate Scheduler.
- Unfreezing the last few layers of MobileNetV3Small model.
- Data Augmentation.
- Permutations of the above.

This is a personal project made by [@Axy2003](https://github.com/Axy2003), [@Ayush180204](https://github.com/Ayush180204), and I.
