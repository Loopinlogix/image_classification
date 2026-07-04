# image_classification
Image Classification with Random Forest & SVM
This project is my attempt at learning how image classification works using the digits dataset from scikit‑learn. The dataset is basically a bunch of tiny 8×8 pixel images of handwritten numbers. I wanted to try building a model that could look at one of these images and guess what number it is.

I used Random Forest first, then later added an SVM model to compare the results. I followed a pretty standard machine‑learning workflow and learned a lot along the way.

What This Project Does
Here’s what I worked through in the notebook:

Loaded the digits dataset

Normalized the pixel values

Split the data into training and testing sets

Trained a Random Forest model

Used GridSearchCV to tune the hyperparameters

Evaluated the model using accuracy, precision, recall, and F1

Plotted confusion matrices and feature importances

Wrote a small function to predict new images

Added an SVM model at the end to compare performance

This was mostly a learning exercise for me, Crystal MacNeil, and I tried to keep everything clear and easy to follow.

Results (In Plain English)
Random Forest did well ~ around 96% accuracy.

SVM did even better ~ around 99% accuracy.

So in this case, SVM was the stronger model.

How to Run It
Option 1: Google Colab
This is the easiest way. Just open the notebook in Colab and run the cells. Colab already has the libraries installed.

What You’ll See in the Notebook
Sample digit images

Confusion matrices

Feature importance charts

Predictions on new test images

A comparison between Random Forest and SVM

I tried to make the outputs easy to understand, especially if you're new to machine learning.

Why I Made This
I’m learning machine learning step‑by‑step, and this project helped me understand:

How models handle image data

How hyperparameter tuning works

How to evaluate models properly

How different algorithms compare

It’s not perfect, but it’s mine and it helped me learn a lot.

Credit
All analysis and work done by Crystal MacNeil.
