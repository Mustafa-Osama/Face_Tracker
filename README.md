
# Face Tracker

Real time face detection model from scratch passing through collecting data, label it, augmentation and finally building a deep learning model using state of art VGG-16.

## Defenition

Face detection system is a technology capable of detecting that there is a human face in a digital image or a video frame.

## Datasets

I have collected the dataset manually using web-cam.

I have captured about 300 images but this number of images will be increased using augmentation.

## Annotate Images with LabelMe

In this step, I have used Labelme to annotate images that I have captured.

https://user-images.githubusercontent.com/113447865/191507665-44dbca61-47cd-42b1-a60b-58bfc6b6a97e.mp4

## Augmentation using Albumentations

As the data I have collected was so small so augmentation is necessary to increase the dataset from about 300 images to 8000 images.

These 8000 images were enough to train the model and gave us a great performance.

## Model

After preparing data passing through the previous steps, it's time to build deep learnig model and train it.

## Test the model

https://user-images.githubusercontent.com/113447865/191507565-793e137e-885b-437e-9408-a8faa0cfa224.mp4
