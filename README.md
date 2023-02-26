
<div align="center">

# Anomaly Detection for Quality Control

----------

[![python](https://img.shields.io/badge/python-3.7%2B-green)]()
[![pytorch](https://img.shields.io/badge/pytorch-1.8.1%2B-orange)]()

## Introduction
This notebook presents anomaly detection model written in PyTorch library, which can be used e.g. on industrial visual quality inspections.

## Data
Model has been trained on MVTec dataset which consists of 17 subsets including 5354 images of different objects and textures. Used datasets are available on the MVTec company website:
https://www.mvtec.com/company/research/datasets/mvtec-ad

### Directory Structure
Downloaded datasets should be in directory data/t
------------
Directory stucture should look like:

    ├── metal_nut
    │   ├── ground_truth
    │   │   ├── bent
    │   │   ├── color
    │   │   ├── flip
    │   │   └── scratch
    │   ├── test
    │   │   ├── bent
    │   │   ├── color
    │   │   ├── flip
    │   │   ├── scratch
    │   │   └── good
    │   └── train
    │       └── good
    ...
--------

##  Dependencies

## License

## References
https://github.com/VainF/pytorch-msssim
https://github.com/PabloMaj/Unsupervised-Anomaly-Detection-with-SSIM-AE
Bergmann, Paul, et al. -- Improving unsupervised defect segmentation by applying structural similarity to autoencoders, 2018