# Pneumonia-Detection

To build an algorithm to detect a visual signal for pneumonia in medical images using Deep Learning algo's as CNNs.
Specifically, your algorithm needs to automatically locate lung opacities on chest radiographs.


## Installations required
This project requires Python 3.x and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](https://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)



## Content
Data set is collected from [Kaggle](https://www.kaggle.com/datasets).
Some Notebook code references are used from the related Kaggle Notebook.     


### About this Dataset
#### What should I expect the data format to be?
The training data is provided as a set of patientIds and bounding boxes. Bounding boxes are defined as follows: x-min y-min width height.
There is also a binary target column, Target, indicating pneumonia or non-pneumonia.
There may be multiple rows per patientId.


#### What am I predicting?
In this challenge competitors are predicting whether pneumonia exists in a given image. They do so by predicting bounding boxes around areas of the lung. Samples without bounding boxes are negative and contain no definitive evidence of pneumonia. Samples with bounding boxes indicate evidence of pneumonia.
When making predictions, competitors should predict as many bounding boxes as they feel are necessary, in the format: confidence x-min y-min width height.
There should be only ONE predicted row per image. This row may include multiple bounding boxes.


#### Data fields
patientId _- A patientId. Each patientId corresponds to a unique image.
x_ - the upper-left x coordinate of the bounding box.
y_ - the upper-left y coordinate of the bounding box.
width_ - the width of the bounding box.
height_ - the height of the bounding box.
Target_ - the binary Target, indicating whether this sample has evidence of pneumonia.



## Run

In a terminal or command window, navigate to the top-level project directory ```Pneumonia-Detection/```  (that contains this README) and run one of the following commands:

```ipython notebook Pneumonia-Detection.ipynb```

or

```jupyter notebook Pneumonia-Detection.ipynb```

This will open the iPython Notebook software and project file in your browser.