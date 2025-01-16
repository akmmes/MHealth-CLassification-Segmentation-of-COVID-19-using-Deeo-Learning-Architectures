## Project title
MHealth Classification and Segmentation of COVID-19 using Deep Learning Architectures

## Description
This research proposes a comprehensive comparison of deep learning models for CAD (Computer-Aided Design) systems which differentiates between COVID-19 and normal healthy lungs of CT & X-ray images using image classification and segment the radiological images of COVID-19 by using image segmentation.

 ## Features
The research aims to use deep learning techniques to detect COVID-19 in medical imaging such as CT scans and X-rays. The model was trained on a dataset of images from COVID-19 positive patients to learn the characteristic features of the disease in medical images. This allows for efficient and accurate detection of COVID-19 in medical imaging, which can assist in early diagnosis and treatment of the disease. Additionally, the model can be used as a tool for radiologists and other medical professionals to help them quickly identify COVID-19 in patients.

## Datasets

Classification
- https://github.com/ieee8023/covid-chestxray-dataset
- https://github.com/UCSD-AI4H/COVID-CT
- https://www.kaggle.com/tawsifurrahman/covid19-radiography-database/data
- https://www.kaggle.com/plameneduardo/sarscov2-ctscan-dataset

Segmentation
- https://www.kaggle.com/c/covid-segmentation
- https://zenodo.org/record/3757476#.YZjtbE5BzIU

## Results
![img](https://github.com/akmmes/MHealth-CLassification-Segmentation-of-COVID-19-using-Deep-Learning-Architectures/blob/main/Classification/Radiography%20DB/Confusion%20Matrix.png)

![img](https://github.com/akmmes/MHealth-CLassification-Segmentation-of-COVID-19-using-Deep-Learning-Architectures/blob/main/Segmentation/segmented%20images%20(Ground%20Truth%20vs%20Predicted).png)

![img](https://github.com/akmmes/MHealth-CLassification-Segmentation-of-COVID-19-using-Deep-Learning-Architectures/blob/main/Segmentation/Pixelwise%20Accuracy%20Reuslt%20%22medical%20segmentation%20dataset%22.png)


## Tech/framework used
Library is build to work together with Keras and TensorFlow Keras frameworks
- [Tensorflow](https://www.tensorflow.org)
- [Keras](https://keras.io/)


## Installation
- Tensorflow==2.1.0 
- Keras==2.3.1
- Segmentation-models==0.2.1


## Architectures
| Architecture for Classification |
| --- | 
| VGG (16 - 19) | 
| Resnet (50 - 101 V2 - 50 V2) |
| Nasnet Large | 
| Inception (V3 - Resnet V2) | 
| Efficientnet | 
| Xception | 
| Mobilenet V2 | 
| Densenet 121 | 

| Architecture for Segmentation |
| --- | 
| Unet | 
| Pyramid Scene Parsing Net |
| Linknet | 
| Feature Pyramid Network | 


Cite the code:  [![DOI](https://zenodo.org/badge/588248652.svg)](https://zenodo.org/badge/latestdoi/588248652)

<!-- 
## Credits
The original idea for this project was taken from the Github repository created by Pavel Iakubovskii and would like to give credit to for their valuable contribution in the AI society. Without their work and inspiration, this project would not have been possible. We encourage others to check out Pavel Iakubovskii's Github repository for more information and updates.
- https://github.com/qubvel
- https://github.com/qubvel/segmentation_models
-->


## Citations
* H M Sarmad. Khan, A. Shaukat, M. Usman Akram and U. Asgher “Pixel wised prediction on COVID-19 CT imaginary: An automated based Image Segmentation Architecture".
* H M Sarmad. Khan, A. Shaukat, M. Usman Akram and U. Asgher “A comprehensive comparison of deep learning architectures for COVID-19 classification on CT and X-ray Imaginary".
