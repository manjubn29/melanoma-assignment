# Problem Statement:
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

# Business Goal:
We will build a multiclass classification model using a custom convolutional neural network in TensorFlow. 

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

## Technologies Used
- Python Libraries such as - numpy, pandas & matplotlib
- Jupyter Notebook
- Tensorflow
- Github
- Colab

## Conclusion
We had created 3 models to derive the conclusion
1. Model 1:
   1. This model shows that training accuracy is much higher than validation accuracy.
   2. We can also notice differences in loss functions in training and validation data.
   3. This is a clear instance of overfitting, in which the model learnt too much from the training dataset and is unable to perform well on the validation dataset.
   #### Training Accuracy: 90.82
   #### Validation Accuracy: 52.80
  
3. Model 2 with augmented data:
   1. Post this, Training accuracy has not increased when compared to the first model.
   2. However there is very less difference between training and validation accuracy.
   3. There is very marginal improvement in the Validation accuracy compared to the first model.
   4. Training loss and Validation loss has very less difference.
   5. And we see that overfitting has been decreased as a result of data augmentation.
   #### Training Accuracy: 64.63
   #### Validation Accuracy: 54.81
  
5. Final Model after rectifing class imbalance:
   1. Post the augmentation and class imbalance management, training and validation accuracy has increased.
   2. The model does not overfit.
   3. This model can serve as the final model.
   #### Training Accuracy: 95.11
   #### Validation Accuracy: 84.04

## Acknowledgements
- Upgrade Learning
- Upgrade Faculty

## Contact
Created by Krishna Moorthy
