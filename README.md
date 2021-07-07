# Face-mask-detection
Real time face mask detection using OpenCV and Convolutional Neural Network

## About the Project
This project uses a Deep Neural Network, more specifically a custom Convolutional Neural Network, to differentiate between images of people with and without masks. The Convolutional Neural Network manages to get an accuracy of 99.48% on the training set and 100% on the test set. Since the model was giving a generalized model, the model with 100% test accuracy was saved. Then stored weights of this CNN are used to classify as mask or no mask in real time using OpenCV. With the webcam capturing the video, the frames are preprocessed and fed to the model to accomplish this task efficiently. The model works efficiently with no apparent lag time between wearing/removing mask and display of prediction.

### The model is also capable of predicting multiple faces with or without wearing mask.

## Data Set
The model was trained with 1314 number of images of 2 classes, wearing mask and without masks and tested with 194 images of 2 classes. I used data augumention to generate more number of images to make the model performs well. 

# Working Images

## Without Mask
![NO_Mask](https://user-images.githubusercontent.com/75533233/124681583-224a0080-dec9-11eb-9da4-837ff23b027c.png)

## With Mask
![With_Mask](https://user-images.githubusercontent.com/75533233/124681641-44438300-dec9-11eb-9657-6c1edea64384.png)
