# Project Name
Melanoma Detection : To build a CNN based model which can accurately detect melanoma.

## Table of Contents
* [Technologies Used](#technologies-used)
* Neural Networks, Python , Tensorflow, Keras


## General Information
Melanoma is a type of cancer that can be deadly if not detected early. 
It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert 
dermatologists about the presence of melanoma has the potential to reduce a lot of 
manual effort needed in diagnosis.
The dataset consists of 2357 images of malignant and benign oncological diseases, 
which were formed from the International Skin Imaging Collaboration (ISIC)

## Conclusions
We can see from the training accuracy and the loss  graph, that with more epochs the model has started to overfit. 
Training accuracy is almost touching 1 with more epochs while validation accuracy has almost hit plateau. 
In loss graph, training loss has decreased significantly, and validation loss has reached a stable value.
So the first model created has overfit. 
Hence we will use augmentaion strategy to reduce the overfit for 2nd model.
In 2nd model - Yes there is improvement in the model, as the validation accuracy is increasing.
accuracy: 0.5759 & val_accuracy: 0.5503
There is very little difference in train accuracy and validation accuracy - which is good for the model.

In the last model we have used a library called Augmentor which creates more images/samples across all classes so that 
none of the classes have very few samples. Using this approach the model gives the best results.