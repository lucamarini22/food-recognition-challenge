# Deep Learning Project (Food Recognition Challenge)

## Overview
The food recognition challenge involves the building of a model to recognise and segment food items in each image. There are 273 categories of food items and each image may be a binary or multiclass image. More information on the challenge can be found on the [official website](https://www.aicrowd.com/challenges/food-recognition-challenge).

The dataset used can be downloaded using the following [link](https://www.aicrowd.com/challenges/food-recognition-challenge/dataset_files) and consists of:

- train-v0.4.tar.gz : 24119 RGB images, with their corresponding 39328 annotations in MS-COCO format.
- val-v0.4.tar.gz : 1269 RGB images, with their corresponding 2053 annotations in MS-COCO format.

The steps taken are described in detail in the [Report](https://github.com/lucamarini22/food-recognition-challenge/blob/main/Report.pdf).

The code may also be viewed directly from the [Notebook](https://github.com/lucamarini22/food-recognition-challenge/blob/main/main.ipynb).

## Authors
- [Leonidas Gee](https://github.com/LeonidasY)
- [Luca Marini](https://github.com/lucamarini22)

## Results
Example images below show the original image, the true mask, and the prediction by the trained model.

### Binary Image
![](https://github.com/lucamarini22/food-recognition-challenge/blob/main/images/binary.png)

### Multiclass Image
![](https://github.com/lucamarini22/food-recognition-challenge/blob/main/images/multiclass.png)
