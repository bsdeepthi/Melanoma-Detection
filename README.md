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
- The data set contains the following diseases:
  
Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion

## Conclusions
- With an Epoch of 20
       accuracy: 0.8834 - loss: 0.3102 - val_accuracy: 0.7602 - val_loss: 0.7241
- With an Epoch of 30 , early stop at 26
        accuracy: 0.9219 - loss: 0.2061 - val_accuracy: 0.8932 - val_loss: 0.3809
  With an Epoch of 40, Model fitment early stopped at 29.
        0.9130 - loss: 0.2350 - val_accuracy: 0.9202 - val_loss: 0.3180
- The model is overfitted with the Epoch of 30 and 40 as the predictions on test dataset is not correct.
- So the correct Epoch value is 20 for a model with 3 CNN layer with an active function of RelU. 4 classes is predicted correctly and other 3 classes has not been predicted correctly


## Contact
Created by [@bsdeepthi] - feel free to contact me!
