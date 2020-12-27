# Facial-Expression-Recognition
The goal of this project is to classify each facial image into one of the seven facial emotion categories considered in this study.
## Dataset
The dataset was taken from [Kaggle](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data). The data consists of 48x48 pixel grayscale images of faces. The faces have been automatically registered so that the face is more or less centered and occupies about the same amount of space in each image. The task is to categorize each face based on the emotion shown in the facial expression in to one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral). 
The training set consists of 28,709 examples. The public test set used for the leaderboard consists of 3,589 examples. The final test set, which was used to determine the winner of the competition, consists of another 3,589 examples.
## Python Libraries Used
1. TensorFlow
2. Keras
3. Pandas
4. Numpy
5. Scikit Learn
6. Matplotlib
## Model
The model is the implementation of the paper [**Convolutional Neural Networks for Facial Expression Recognition**](https://arxiv.org/pdf/1704.06756.pdf) and has achieved a validation accuracy of **61%** and test accuracy of **61%**.
