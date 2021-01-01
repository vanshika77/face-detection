FACE DETECTION

This project is about training a model on a set of human photographs and predicting an image on trained model.
Here i have trained my model on 5 classes i.e. images of 5 people.
I had less number of photographs to train my model, hence i have used ImageDataGenerator to increase number of photographs for each class.

___________________________________________________________________________________________________________________________________________________________________________________
ImageDataGenerator

Lets see how ImageDataGenerator works.
The Keras deep learning neural network library provides the capability to fit models using image data augmentation via the ImageDataGenerator class.
For my dataset I have used width_shift_range, height_shift_range, shear_range, zoom_range and channel_shift_range types of augmemation. these augmentation will read the dataset and gives the output as increased number of images.

code for Image Data Augmentation: https://github.com/vanshika77/face-detection/blob/main/imagedatagen_on_faces.py
___________________________________________________________________________________________________________________________________________________________________________________
TRAINING THE MODEL

I have trained my model on the created dataset and saved my model.

code for training and saving the model: https://github.com/vanshika77/face-detection/blob/main/training_model.py
___________________________________________________________________________________________________________________________________________________________________________________
PREDICTING

finally we have to give an image to model and predict the image on trained model.

code for predicting the image: https://github.com/vanshika77/face-detection/blob/main/predicting.py
___________________________________________________________________________________________________________________________________________________________________________________
