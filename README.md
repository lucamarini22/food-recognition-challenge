# Food Recognition Challenge (Semantic Segmentation)

## Overview
The food recognition challenge involves the building of a model to recognise and segment food items in each image. There are 273 categories of food items and each image may be a binary or multiclass image. More information on the challenge can be found on the [official website](https://www.aicrowd.com/challenges/food-recognition-challenge).

A report was written and submitted as part of the project and may be viewed [here](https://github.com/lucamarini22/food-recognition-challenge/blob/main/results/report.pdf).

## Dataset
The dataset can be downloaded using the following [link](https://www.aicrowd.com/challenges/food-recognition-challenge/dataset_files).

The dataset consists of:

- train-v0.4.tar.gz : 24120 RGB images, with their corresponding 39328 annotations in MS-COCO format.
- val-v0.4.tar.gz : 1269 RGB images, with their corresponding 2053 annotations in MS-COCO format.

## Results
The project is included as a .ipynb file and can be viewed using the [Jupyter nbviewer link](https://nbviewer.jupyter.org/github/lucamarini22/food-recognition-challenge/blob/main/food-recognition.ipynb) or via Jupyter notebook directly on a desktop. 

Example images below show the original image, the true mask and the mask predicted by the model.

### Binary Image
![](https://github.com/lucamarini22/food-recognition-challenge/blob/main/results/images/binary.png)

### Multiclass Image
![](https://github.com/lucamarini22/food-recognition-challenge/blob/main/results/images/multiclass.png)
