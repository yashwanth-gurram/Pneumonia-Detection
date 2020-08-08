# Pneumonia-Detection
Using Chest-X Ray images from a very well known Kaggle Dataset (https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia), we can use Deep Learning models to detect Pneumonia.

## Motivation
Healthcare is an important part of the current technological revolution, with more and more fields like Deep Learning applying methods to this versatile and pivotal field. Pneumonia is a very common infection with more than 10 million cases annually. Detecting this infection at an early stage using a simple chest x-ray scan could prove to be a game-changer

![](https://github.com/yashwanth-gurram/Pneumonia-Detection/blob/master/Images/xray.png)

## Goal
The goal of the project is to detect visual signals for pneumonia from medical chest X-Ray images.

## Dataset
The dataset consists of over 5800 images labeled as normal, pnuemonia.

## Technologies Used
This project uses Tensorflow 2.1.0 and Keras 2.3.0.

## Architecture Used
The project used a tranfer learning technique with base model as VGG16
(https://keras.io/api/applications/vgg/#vgg16-function)

## Result
After a 5 epochs of training, the model gets a train accuracy of 98% validation accuracy of 91%.

![](https://github.com/yashwanth-gurram/Pneumonia-Detection/blob/master/Images/chestXray%20accuracy.png)
![](https://github.com/yashwanth-gurram/Pneumonia-Detection/blob/master/Images/chestXray%20loss.png)
