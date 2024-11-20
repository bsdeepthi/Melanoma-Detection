# Project Name
> Outline a brief description of your project.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- To build a CNN based model which can accurately detect melanoma. 
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. 
- A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

## Conclusions
- With an Epoch of 20
       accuracy: 0.8663 - loss: 0.3656 - val_accuracy: 0.8255 - val_loss: 0.5133
- With an Epoch of 25
        accuracy: 0.9375 - loss: 0.1695 - val_accuracy: 0.9301 - val_loss: 0.2316
  With an Epoch of 40, Model fitment early stopped at 16.
        accuracy: 0.9119 - loss: 0.2387 - val_accuracy: 0.9227 - val_loss: 0.2320
-  Though the accuracy is high in Epoch as 25 and 40 on the training set, the performance on the test set is very less. Whereas the Epoch of 20 has less accuracy the prediction on the test data is 80% accurate.
- So the correct Epoch value is 20 for a model with 3 CNN layer with ann active function of RelU.

## Technologies Used
- library - version 1.0
- library - version 2.0
- library - version 3.0


## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@bsdeepthi] - feel free to contact me!
