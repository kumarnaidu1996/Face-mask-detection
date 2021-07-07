# Face-mask-detection
Real time face mask detection using OpenCV and Convolutional Neural Network

## About the Project
This project uses a Deep Neural Network, more specifically a Convolutional Neural Network, to differentiate between images of people with and without masks. The Convolutional Neural Network manages to get an accuracy of 99.48% on the training set and 100% on the test set. Since the model was giving a generalized model, the model with 100% test accuracy was saved. Then stored weights of this CNN are used to classify as mask or no mask in real time using OpenCV. With the webcam capturing the video, the frames are preprocessed and fed to the model to accomplish this task efficiently. The model works efficiently with no apparent lag time between wearing/removing mask and display of prediction.

### The model is also capable of predicting multiple faces with or without wearing mask.
