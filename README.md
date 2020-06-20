# Dimension reduction using PCA and LDA and 3D Convolutional Neural Network for Hyperspectral Image classification

## Abstract
A Hyperspectral image is a collection of several hundreds even thousands of reflectance bands of different wavelengths that is captured by a satellite sensor. HSI has provided significant opportunities for material identification and
classification because of its ability to contain rich information. But the processing of hyperspectral
image is a challenging task because of its high dimensionality and data redundancy.That is why dimension reduction is necessary otherwise high dimensional data suffers from Hughes Phenomenon. Dimension can be reduced by using feature selection and feature extraction approaches.In here, supervised Linear Discriminant Analysis(LDA) & unsupervised Principal Component Analysis (PCA) have been used as preprocessing step to classify Hyperspectral Image.


## Dataset
(Indian Pines)<br/>
Image size: 145×145×200.
200 spectral bands.
Wavelength range: 0.4−2.5𝜇𝑚.
16 classes.<br/>

University of Pavia<br/>
Image size: 610×340×103.
103 spectral bands.
9 classes.<br/>

## WorkFlow
The steps of the proposed methods are:

    1.Perform PCA to reduce dimension from the input dataset.
    2.Perform 3D CNN to classify.
    3.Perform LDA to reduce dimension from the input dataset.
    4.Perform 3D CNN to classify.
    
## Kaggle Code Link
[PCA+3DCNN](https://www.kaggle.com/tasmiajannat/3d-cnn)  <br/>
[LDA+3DCNN](https://www.kaggle.com/tasmiajannat/lda-3dcnn)
    
## Classification Accuracy
 [classification_report](classification_report.txt)
    






