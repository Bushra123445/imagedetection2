# Inferno
FPGA Deployable Fire Detection Model for Real-Time Video Surveillance Systems Using Convolutional Neural Networks


Project Description: The project serves as an alternative method to ordinary fire detection
using short-range smoke and heat sensors. No special hardware is required here, just a camera
and computer analysing the cameras output. We are proposing a cost-effective CNN
framework for flame detection in surveillance videos using images and videos based on deep
learning. Transfer learning has been used in training the model wherein a pre-trained
MobileNet architecture was modified and trained specific to our dataset (3GB) consisting of
fire and non fire images extracted from real time footage. The trained model achieved an
overall accuracy of 98% and was deployed onto a raspberry pi3 (1GB RAM). The time taken
by the model to classify a frame as fire / non-fire is around 0.78 seconds on the raspberry pi.
In case of positive fire detection consecutively for 20 frames, the notification system is
triggered and a fire alarm is raised.


Technologies Used: Python3, Deep learning: Convolutional Neural Networks (CNN),
openCV, Tensorflow, Keras, Computer Vision, Cloud Computing, Transfer Learning.
