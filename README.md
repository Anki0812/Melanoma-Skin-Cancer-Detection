# Melanoma Detection
Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


The data set contains the following diseases:

- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion

## Conclusions
- At initial stage overfitting was observed with great fluctuation in validation accuracy
- On modifying some images, the model became less overfitted but the accuracy had to be improved
- Accuracy on training data has increased by using Augmentor libraryof 90% and validation accuracy of 83%
- Melanoma Detection Accuracy: 0.8644

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- tensorflow - version 2.13.0
- keras - version 2.13.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- The training provided by IIIT Bangalore and Upgrad greatly contributed to the successful execution of this project.


## Contact
Created by [@Anki0812] - feel free to contact.


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->