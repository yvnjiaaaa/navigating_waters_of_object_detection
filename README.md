
# navigating_waters_of_object_detection
This repo provides supplementary materials for the repeatability of the paper "Navigating the Waters of Object Detection: Evaluating the Robustness of Real-time Object Detection Models for Autonomous Vessels". 

## Acknowledgments
For the three object detection appoaches used here, we run the experiments with the codes from the following repositories:

- [YOLOv8](https://github.com/ultralytics/ultralytics)
- [SSD](https://github.com/lufficc/SSD)
  - The repo does not provide ResNet backbone. Therefore we add ResNet backbone files to run SSD+Resnet. The ResNet backbone files are provided in approaches\SSD\SeaShips\backbones\
- [NanoDet-Plus](https://github.com/RangiLyu/nanodet)

For the dataset generation of the SMD dataset, we refer to the following repository:
- [SMD dataset generation](https://github.com/tilemmpon/Singapore-Maritime-Dataset-Frames-Ground-Truth-Generation-and-Statistics)

## Object detection approaches 
The config/args files as well as the random seeds of YOLOv8 and NanoDet-Plus are provided in approaches\. The SSD repo we used to implement the SSD approach does not provide the random seed parameter, but we can provide the .pth files if necessary.

## Datasets
We use three waterborne object detection datasets: SeaShips, SMD, and SSAVE. The detailed data splitting is provided in datasets/. 

