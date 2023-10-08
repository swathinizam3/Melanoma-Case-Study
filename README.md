# Melanoma detection using CNN
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
> The data set contains the following diseases:
Actinic keratosis Basal cell carcinoma Dermatofibroma Melanoma Nevus Pigmented benign keratosis Seborrheic keratosis Squamous cell carcinoma Vascular lesion


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)



## General Information
- evaluate images and alert the dermatologists about the presence of melanoma
- reduce a lot of manual effort needed in diagnosis.
- 75% of skin cancer deaths


## Conclusions
- Model 1 with 2 convolution layers, epoch 20 has training accuracy: 79%, validation accuracy:46%. Has overfitting.
- Model 2 with multiple convolution layers, epoch 20 has training accuracy: 61%, validation accuracy:48%. Gap is reduced but still has overfitting
- Model 3 was built with epoch 20, with augmentation. It reduced the gap between training and validation accuracy.
- Model 4 with epoch 30, post handling class imbalance using augmentor increased training and validation dataset accuracy. training accuracy: 92%, validation accuracy:80%. 

## Technologies Used
- tensorflow 
- keras
- pandas
- matplotlib.pyplot
- Jupyter
