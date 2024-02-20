# Digit Recognizer using CNN
Handwritten Recognition using Python, pygame, sys, numpy and tensorflow.

## Data to train the model

The data i used come from the [kaggle competition](https://www.kaggle.com/competitions/digit-recognizer).

Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255, inclusive.
The training data set, (train.csv), has 785 columns. The first column, called "label", is the digit that was drawn by the user. The rest of the columns contain the pixel-values of the associated image.
Each pixel column in the training set has a name like pixelx, where x is an integer between 0 and 783, inclusive. To locate this pixel on the image, suppose that we have decomposed x as x = i * 28 + j, where i and j are integers between 0 and 27, inclusive. Then pixelx is located on row i and column j of a 28 x 28 matrix, (indexing by zero).

## Trainning of the model
I was greatly inspired by Chirag Mohan Gupt's work on Kaggle to train my model. 
Here is the link to his Kaggle page: [Chirag Mohan Gupt's Kaggle Page](https://www.kaggle.com/chiragmohangupta)
