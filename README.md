# Piling-sheet-assesment-
## Introduction
Asessing the corrosion on piling sheet according to NEN and estimating distance between the bumps. Two classificiation algorithm have been made:
1. Classification with four classes: Grass, Metal good, Metal bad and Rock.
2. Classification with six classes: Grass, Metal good, Metal acceptable, Metal moderate and Metal bad and Rock.

After the assesment the images that have been labeled with "Metal" will be sent through an Object detection algorithm that was made using YOLOv4. This algorithm was trained to detect: the bumps of a piling sheet and a reference object. The reference object was something that was seen on most piling sheet in which we know the actual dimension. The horizontal distance between the bumps was calculated and using the reference object we converted the pixel distance into actual distance.

## Data
Data can be downloaded from [Kaggle](https://www.kaggle.com/datasets/richiemaskam/piling-sheet-data-2022). The classification data are already stored in different folders representing the classes. The object detection data contains the annotation files. There is a seperate "Model Test" data in which inference was done.

## Inference
If you just want to do inference you can use the keras and weights file. The keras file for the four class model is in this repository. The keras file for the six class classifier can be downloaded [here](https://drive.google.com/file/d/13Up7yLDlxNOzzBImQ9OVIjMZoIFR7lWv/view?usp=sharing). For object detection use the cfg file in this repository. Use this [link](https://drive.google.com/file/d/1--RfLsdJXUGPl9EcDlTDAd57qcZDjXKt/view?usp=sharing) to download the weights.
