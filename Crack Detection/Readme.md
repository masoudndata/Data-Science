This folder is about detecting cracks on the concrete. a TensorFlow CNN was used for make our predictions. The dataset consist of 40000 images, however for saving time and memory We use training data consisting of 7000. The Dataset could be downloaded from https://www.kaggle.com/arunrk7/surface-crack-detection.

**Dataset info:** <br/>
Concrete surface cracks are major defect in civil structures. Building Inspection which is done for the evaluation of rigidity and tensile strength of the building. Crack detection plays a major role in the building inspection, finding the cracks and determining the building health.

The datasets contains images of various concrete surfaces with and without crack. The image data are divided into two as negative (without crack) and positive (with crack) in separate folder for image classification. Each class has 20000images with a total of 40000 images with 227 x 227 pixels with RGB channels. The dataset is generated from 458 high-resolution images (4032x3024 pixel) with the method proposed by Zhang et al (2016). High resolution images found out to have high variance in terms of surface finish and illumination condition. No data augmentation in terms of random rotation or flipping or tilting is applied.

**Methodology:** <br/>
Convolutional Neural Networks (CNN)<br/>
This case study is based on CNN model and the Case Study Paper includes detailed description of all the steps and processes that CNN's include such as:

* Convolutional Operation<br/>
* Pooling<br/>
* Flattening<br/>

![i7 pooling](https://user-images.githubusercontent.com/50455870/132310803-800597d0-9456-4a59-ad2e-65a7c566ed7e.jpg)

![i8 flatening](https://user-images.githubusercontent.com/50455870/132311288-f01a03fc-db32-4fc3-af8b-6824c68857f8.jpg)

**Model Evaluation:**<br/>
Important evaluation steps, described in detail in Case Study Paper , that help the CNN model to train and make accurate predictions such as:

* Loss Functions for CNN (SoftMax and Cross-Entropy)<br/>
* Loss Function Optimizers (SGD and Adam Optimizer)<br/>
* Activation Functions (Rectifier and Sigmoid)<br/>

CNN Architecture:
![i9](https://user-images.githubusercontent.com/50455870/132315375-54617cdd-e6f1-4d2b-a281-9073adfe11cd.jpg)

![CNN architecture](https://user-images.githubusercontent.com/50455870/132298053-51482b6c-7c9e-4216-a88f-4cd12d39b2ef.gif)

![i6](https://user-images.githubusercontent.com/50455870/132306835-448303c3-204b-49ee-a3ce-fc6a641a4c20.jpeg)

**Procedure:**<br/>
1- Creating DataFrames
2- Loading Image Data
3- Training 
4- Results

**Results:**<br/>

![i1](https://user-images.githubusercontent.com/50455870/132319074-075ca5da-72ad-40ff-a963-50829d952f78.JPG) 

![i2](https://user-images.githubusercontent.com/50455870/132319104-2129bc13-0c98-4c77-bc42-1c89e3c9a32f.JPG) 
