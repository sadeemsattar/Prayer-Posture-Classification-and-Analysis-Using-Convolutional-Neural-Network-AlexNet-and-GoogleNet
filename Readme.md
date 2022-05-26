# Prayer Posture Classification and Analysis Using Convolutional Neural Network, AlexNet and GoogleNet Deep Learning Neural Network
This is the sixth semester project implemented with Python, Tensorflow, Keras and Scikit-learn for the Artificial Intelligence Course.

# Introduction
Prayer is the essential part in every religion existing on the planet. 

In the religion Islam, prayer that is Salat is the fundamental part. It is the second pillar of Islam that the believers have to obey. It is the essential worshipping activity that the believers have to perform five times a day. 

Salat consists of multiple human gesture perform by a worshipper. It contains a predefined set of posture activity that must be followed precisely. However, for several people, these postures are not accurately performed due to new to the religion or even learned in an incorrect manner. Furthermore, the duration of each posture has to be balanced. 

Therefore, to cater this issue, we propose to develop an artificial intelligence model that aims to identify the posture through an image. We classify three prayer posture that includes Ruku, Sujud and Qiam.

# Dataset
Prayer Postures Dataset consist from a set of images of students and laboratory members performing different Salat positions using mobile phones, from various view angles, especially captured for the purpose, complemented with images (and video frames) of people in prayer collected from the Internet.

The total number of collected images is 653 that we manually labelled into three classes which include Ruku, Sujud and Qiam. The total images are then shuffled and 70-30 ratio is performed through which training dataset of 457 images and 196 test images of different postures are split.

# Results
The Experiment shows that the accuracy obtained by 457 trained images and giving 196 test images to CNN is 90.8%, AlexNet 82.6% and GoogleNet 90.3% with 50 iterations.