The Dataset could be downloaded from https://www.kaggle.com/arunrk7/surface-crack-detection.

**Dataset info:** <br/>
Concrete surface cracks are major defect in civil structures. Building Inspection which is done for the evaluation of rigidity and tensile strength of the building. Crack detection plays a major role in the building inspection, finding the cracks and determining the building health.

The datasets contains images of various concrete surfaces with and without crack. The image data are divided into two as negative (without crack) and positive (with crack) in separate folder for image classification. Each class has 20000images with a total of 40000 images with 227 x 227 pixels with RGB channels. The dataset is generated from 458 high-resolution images (4032x3024 pixel) with the method proposed by Zhang et al (2016). High resolution images found out to have high variance in terms of surface finish and illumination condition. No data augmentation in terms of random rotation or flipping or tilting is applied.

# Methodology:** <br/>
Convolutional Neural Networks (CNN)<br/>
This case study is based on CNN model and the Case Study Paper includes detailed description of all the steps and processes that CNN's include such as:

1- Convolutional Operation
2- Pooling
3- Flattening

**Model Evaluation:*<br/>
Important evaluation steps, described in detail in Case Study Paper , that help the CNN model to train and make accurate predictions such as:

Loss Functions for CNN (SoftMax and Cross-Entropy)
Loss Function Optimizers (SGD and Adam Optimizer)
Activation Functions (Rectifier and Sigmoid)

![CNN architecture](https://user-images.githubusercontent.com/50455870/132298053-51482b6c-7c9e-4216-a88f-4cd12d39b2ef.gif)



Convolutional Neural Networks with TensorFlow
