# FacialFeatureLocalization

Facial feature detection is an important and challenging problem in the fields of machine learning and computer vision. The most
important 4 applications of facial feature localization are face recognitions, medical purposes, tracking faces in image and videos
and at last face filters. In this contribution we introduce a method to do feature localization more accurately. In this project, we are given
a list of 96×96-pixel 8-bit gray level images with their corresponding (x, y) coordinates of 15 facial keypoints. We first adopt Sklearn train
test split to randomly split the data set into a training set and a test set, so that we can develop our algorithm on the training set and
assess its performance on the test set. The baseline model was Convolutional Neural Network and our aim is to outperform the
results of it by using Transfer Learning and Cascaded Convolutional Neural Network. Also the project shows one of the applications that
is facial filters on the predicted facial key points.
