# Image Classification and Style Transfer
Authors: Cindy Chen, Michelle Liu, Yifei Wang, Vivian Zhou

Date: Spring 2023

Master of Science in Machine Learning and Data Science (formerly MS in Analytics)

Northwestern University

## Project Objective
With images of animals obtained from Kaggle, this project aims at using __computer vision__ and __deep learning__ techniques to (1) __classify the animal present in an image__ and (2) achieve __style transfer__ (recompose the content of an image in the style of another).

To achieve the goal of image classification, the team trained a customized CNN (convolutional neural network) and compared the performance with that of a transfer learning model with EfficientNetB3. Then, the team established a fast style transfer model and an optimization-based style transfer model to recompose the animal images in the style of various artworks.

## Repository Structure
<pre>
Image Classification and Style Transfer
│   
├── data
│   ├── Style_Transfer                         <- Folder containing images for style transfer
│   ├── equalized_data                         <- Folder containing color-equalized images
│   ├── original_data                          <- Folder containing original image
│   ├── resize_data                            <- Folder containing resized images
│   ├── train_test_data                        <- Folder containing pickle files for train and test images and labels
│   └── name of the animals.txt                <- List of animal names
│
├── Customized_CNN.ipynb                       <- Jupyter Notebook for customized CNN for classification
├── EDA_Transfer_Learning.ipynb                <- Jupyter Notebook for EDA and transfer learning for classification
├── Fast_Style_Transfer.ipynb                  <- Jupyter Notebook for fast style transfer
├── MSiA432_Final Presentation.pdf             <- Project presentation
├── Optimization_Based_Style_Transfer.ipynb    <- Jupyter Notebook for optimization-based style transfer
├── README.md                                  <- Project description and summary
└── Resize_Image.ipynb                         <- Jupyter Notebook for resizing images
</pre>
