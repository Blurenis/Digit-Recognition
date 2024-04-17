# Digit Recognizer using CNN
Handwritten Recognition using Python, pygame, sys, numpy and tensorflow.

![Digit Recognition GIF](https://github.com/Blurenis/Digit-Recognition/raw/master/path/to/gif.gif)


## Data to train the model

The data i used come from the [kaggle competition](https://www.kaggle.com/competitions/digit-recognizer).

Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255, inclusive.
The training data set, (train.csv), has 785 columns. The first column, called "label", is the digit that was drawn by the user. The rest of the columns contain the pixel-values of the associated image.
Each pixel column in the training set has a name like pixelx, where x is an integer between 0 and 783, inclusive. To locate this pixel on the image, suppose that we have decomposed x as x = i * 28 + j, where i and j are integers between 0 and 27, inclusive. Then pixelx is located on row i and column j of a 28 x 28 matrix, (indexing by zero).

## Trainning of the model
I was greatly inspired by Chirag Mohan Gupt's work on Kaggle to train my model. 
Here is the link to his Kaggle page: [Chirag Mohan Gupt's Kaggle Page](https://www.kaggle.com/chiragmohangupta)

---------------------------------------------
![Digit Recognition GIF]([https://github.com/Blurenis/Digit-Recognition/raw/master/path/to/gif.gif](https://private-user-images.githubusercontent.com/87265095/323219684-909d1e36-8036-41f1-81cd-c7c84d96b5e4.gif?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTMzNTkzNDIsIm5iZiI6MTcxMzM1OTA0MiwicGF0aCI6Ii84NzI2NTA5NS8zMjMyMTk2ODQtOTA5ZDFlMzYtODAzNi00MWYxLTgxY2QtYzdjODRkOTZiNWU0LmdpZj9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA0MTclMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNDE3VDEzMDQwMlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTFjYTYxYjA1YWQzMTQ3NTU1ZjJjMzA5MWU2NmViMjYxMzg2ZGZjNTczYzIxZTkzYmU2Mzk0NzZkMGVjY2FlNzUmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.FBMn4sIHWru4isrpFnX0EGyVgcoGHSDW0m6feJTh-KM))
