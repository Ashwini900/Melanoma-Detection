# Melanoma_Detection_Assignment_Upgrad
> Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
The analysis shows that the class rebalance helped in reducing the overfitting of the data and also the losses is being reduced. However, it reduced the Accuracy very low.
Firstly, we analysis without the ImageDataGenerator. Which created data overfit at high ratio.
Secondly, we introducted Dropout and ImageDataGenerator which reduced the Overfit.
Lastly, we have done analysis with Batch Normalization and Augumentaiton which really helped to reduce losses.
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Google-CoLab

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
