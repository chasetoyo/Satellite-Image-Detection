# Satellite Image Object Detection with Mask R-CNN

## Chase Toyofuku-Souza

## Table of Contents

* [About](#about)
* [Required Dependencies](#Required-Dependencies)
* [Files](#Files)
* [Notes](#Notes)
* [References](#References)

## About
Final project for CPSC 393 (Machine Learning) at Chapman University. This is an example of using Matterports Mask R-CNN framework to detect and create masks around cars and swimming pools from satellite images. There are an abundance of satellite imagery data available and manually sorting through all of it would be tedious, this project was a proof of concept that it is possible to accurately detect objects via satellite images. Other important applications include surveying areas via drones and detecting things such as stolen cars or fires.

## Required-Dependencies
* matplotlib
```sh
pip install matplotlib
```
* numpy
```sh
pip install numpy
```
* cv2
```sh
pip install opencv-python
```
* xml-python
```sh
pip install xml-python
```

* mask-rcnn
```sh
git clone https://github.com/matterport/Mask_RCNN.git
```

* tensorflow-gpu
```sh
conda create -n tf-gpu tensorflow-gpu
conda activate tf-gpu
```

* keras
```sh
conda install -c conda-forge keras
```

### Files
- [`Notebook`](final.ipynb)
- [`Presentation`](CPSC_393_Final_Presentation.pdf)

### Notes
- This project was heavily based on the `train_shapes.ipynb` found at https://github.com/matterport/Mask_RCNN/blob/master/samples/shapes/train_shapes.ipynb, as well as the article https://machinelearningmastery.com/how-to-train-an-object-detection-model-with-keras/, as noted in the references.

### References:
- https://machinelearningmastery.com/how-to-train-an-object-detection-model-with-keras/
- https://medium.com/analytics-vidhya/confusion-matrix-accuracy-precision-recall-f1-score-ade299cf63cd
- https://towardsdatascience.com/r-cnn-fast-r-cnn-faster-r-cnn-yolo-object-detection-algorithms-36d53571365e
- https://github.com/matterport/Mask_RCNN
- https://www.edureka.co/blog/tensorflow-object-detection-tutorial/
- https://blog.paperspace.com/mask-r-cnn-tensorflow-2-0-keras/
- https://github.com/matterport/Mask_RCNN/issues/2165
- https://stackoverflow.com/questions/59308263/using-a-tf-tensor-as-a-python-bool-is-not-allowed-in-graph-execution-use-ea
- https://stackoverflow.com/questions/55149026/tensorflow-2-0-do-you-need-a-tf-function-decorator-on-top-of-each-function
- https://docs.python.org/3/library/xml.etree.elementtree.html
- https://stackoverflow.com/questions/3430372/how-do-i-get-the-full-path-of-the-current-files-directory
- https://stackoverflow.com/questions/40690598/can-keras-with-tensorflow-backend-be-forced-to-use-cpu-or-gpu-at-will
- https://github.com/matterport/Mask_RCNN/tree/master/samples/shapes
- https://www.kaggle.com/kbhartiya83/swimming-pool-and-car-detection