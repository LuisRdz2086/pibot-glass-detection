# Project Repositories Overview

This repository contains several sub-projects related to object detection and depth estimation in computer vision. Each sub-project modifies existing approaches to suit specific requirements such as running on CPU instead of GPU, employing external datasets, and adjusting output formats.

## 1. Mirror-Glass-Detection

This sub-project includes a slightly modified version of the GDNet approach, originally developed for mirror and glass detection. The primary modification involves the use of an external dataset.

- **Original Repository**: [Charmve/Mirror-Glass-Detection](https://github.com/Charmve/Mirror-Glass-Detection)
- **Modifications**: Integration with an external dataset.
- **Note**: Pre-trained models have been removed to reduce the size of the uploaded files.

## 2. fanet

This sub-project adapts the 'FakeMix Augmentation Improves Transparent Object Detection' approach. Modifications are made to enable CPU execution and to alter the output to the inferred image.

- **Original Repository**: [yangcaoai/fanet](https://github.com/yangcaoai/fanet)
- **Modifications**: Adapted for CPU execution and changed output format.
- **Note**: Pre-trained models have been removed to reduce the file size.

## 3. Implicit Depth

This sub-project is based on the 'RGB-D Local Implicit Function for Depth Completion of Transparent Objects' approach. Changes were made for testing purposes, but the output was reverted to its original form.

- **Original Repository**: [NVlabs/implicit_depth](https://github.com/NVlabs/implicit_depth)
- **Modifications**: Temporary changes for output testing.
- **Note**: The original output format has been restored.

## 4. Evaluation

This section contains inferences and ground truth masks from the dataset, along with a Python script used for calculating the results and generating .csv files with the metrics.

- **Dataset**: The dataset used for obtaining the metrics is available on [Google Drive](https://drive.google.com/drive/folders/1cwlCnjbqtyv46KLMiCVRoCo2kbBxa6Q2?usp=sharing).
- **Note**: Pre-trained models have been removed from all approaches to minimize upload sizes. These models and datasets can be obtained from their respective original repositories.

