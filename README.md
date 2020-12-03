# Introduction to Machine Learning for Imaging

A short hands on training workshop introducing machine learning for imaging. In the first part of the workshop a brief introduction to the ideas of machine learning as they apply to image classification and segmentation is given. In the second part, the Trainable WEKA framework available in ImageJ/Fiji is introduced, and the participants are led through a series of hands on exercises on creating and applying classifiers for segmentation. 

<b>Part I - A very brief overview ideas in machine learning</b>
* Types of machine learning: supervised, unsupervised, reinforcement
* Types of machine learning: NN, SVM, Bayesian Networks, …
* 2D linear support vector machine as an easy visual example
* Basic ideas of image classification using image statistics
* Image segmentation as classifying pixels in an image

<b>Part II - Hands on image segmentation with Trainable WEKA and ImageJ</b>
* Trainable WEKA for image segmentation in ImageJ
* TW interface
* Creating a classifier
* Fixing errors and retraining
* Applying a trained classifier to new image sets
* Visualising the image statistics used for classification
* Trying other image statistics for classification
* Overfitting
* Using other machine learning methods on TW
* Application to 3D imaging
* Interactive examples:  microscopy imaging of kidneys, imaging salmonella in cells

<b>Note:</b> Each image example has its own folder directory in <em>MLWorkshopDatasets</em>. Within the directory for an example there is a subfolder named <em>ExampleSegmentation</em> which contains two images: <em>Classified Image.png</em> which is an example segmentation for the image; and <em>TrainingRegionsSelected.png</em> which shows the regions used for training to obtain the example segmentation.

Trainable WEKA is available in recent versions of [Fiji](https://imagej.net/Fiji), which is free to [download](https://imagej.net/Fiji.html#Downloads).
