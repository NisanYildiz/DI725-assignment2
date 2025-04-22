# DI725 Assignment 2: Object Detection

Fine-tuning YOLOS-small for object detection on the AU-AIR traffic surveillance dataset.

## Overview
- **Model**: `hustvl/yolos-small` transformer-based object detector + coco pre-trained DETR for evaluation
- **Dataset**: [AU-AIR](https://bozcani.github.io/auairdataset) (30k low-altitude traffic images, 8 classes)

## Dataset Preparation

    Annotations: auair2019data/annotations.json

    Images: auair2019data/images/

    Automatic 70-15-15 split stored in yolos_finetuned/dataset_splits.pkl


Note: Dataset not included - download from AU-AIR official site and place in auair2019data/

WANDB report is available [here](https://wandb.ai/yildizz-nisan-middle-east-technical-university/object_detection_transformer/reports/DI725-YOLOS-small-training--VmlldzoxMjQxNDk3OA?accessToken=bhih0y2uqcuoetfibmcft97fo1qd6lo5fim3v08ym1cwms8zsk9cb1boh744vris)
