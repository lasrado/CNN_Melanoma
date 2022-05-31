# Skin cancer identification
> Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
The idea is to build a CNN based model which can accurately detect melanoma. 


## Table of Contents
* [General Info](#general-information)
* [Dataset](*data-set)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The project uses Tensorflow to build a CNN which can detect the cancer like Melanoma by analysing the image.

## Data Set
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set has below distribution:
- actinic keratosis has 114 images
- vascular lesion has 139 images
- melanoma has 438 images
- dermatofibroma has 95 images
- pigmented benign keratosis has 462 images
- basal cell carcinoma has 376 images
- nevus has 357 images
- seborrheic keratosis has 77 images
- squamous cell carcinoma has 181 images
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The data is imbalanced and few classes dominate the percentage of data. This causes overfitting.
- Resolving the class imbalance using Augmentation has resolved the overfitting issue.
- The Model is able to detect unknown images with a 88% accuracy.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python 3.x
- Tensorflow
- Keras
- Pandas and numpy



## Contact
Created by [@lasrado] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->