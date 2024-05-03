# Sheep Breed Classification:
Developed a sheep breed classification deep learning model using fine-tuned VGG-16, fine-tuned VGG-19, and an enhanced version of fine-tuned VGG-16 to classify the four different types of sheep.

### Technologies/frameworks used

<img src="https://img.shields.io/badge/python%20-%2314354C.svg?&style=for-the-badge&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/Keras%20-%23D00000.svg?&style=for-the-badge&logo=Keras&logoColor=white"/> <img src="https://img.shields.io/badge/TensorFlow%20-%23FF6F00.svg?&style=for-the-badge&logo=TensorFlow&logoColor=white" />
![OpenCV](https://img.shields.io/badge/Opencv-red.svg?&style=for-the-badge&logo=open-source-initiative&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c.svg?&style=for-the-badge&logo=python&logoColor=white) <img src="https://img.shields.io/badge/Google%20Colab%20-%23F9AB00.svg?&style=for-the-badge&logo=Google%20Colab&logoColor=white"/>


### :file_folder: Dataset
The dataset used can be downloaded here - [KAGGLE](https://www.kaggle.com/datasets/divyansh22/sheep-breed-classification)

This dataset consists of __3299 images__ belonging to two classes:
*	__Sheep Face:1680 images__
*	__Full Sheep: 1619 images__

### Neural Network Architecture Used:
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![](https://github.com/SubashGupta/SheepBreedClassification/blob/main/HighestAccuracyModel.png)

# Results:
The plots for the different models training and validation accuracy can be seen in the paper attached or the code files attached.

In this study, various training parameters were analyzed, and experiments were conducted using two types of training images: full sheep images containing noise and significant variation, and cropped facial images with minimal noise and variation. Our findings indicate that fine-tuning the last six layers of VGG-16 for 10 epochs resulted in a classification accuracy of 93.75% with a standard deviation of 1.93. Fine-tuning the last 7 layers of the VGG-19 for the same 10 epochs has resulted in a slightly higher classification accuracy of 93.87%. But **fine-tuning the VGG-16 by adding a few additional convolutions layers and performing batch normalization and data augmentation have helped in improving the accuracy by 3.93%, making it 97.68% of the highest accuracy. ** This demonstrates the effectiveness and practicality of the model for on-farm use.

With this model, the farmers can easily classify the sheep and also help me make informed decisions regarding flock management and commercial valuation.


PS: I included the reports and results for your reference.

***** IF YOU FIND ANY PROBLEMS RELATED TO THIS CODE FILES, FEEL FREE TO CONTACT ME *****

***** LEAVE A COMMENT IF YOU LOVED MY WORK *****

THANK YOU FOR VIEWING AND DOWNLOADING :)
