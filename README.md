# image_classification
This project is my walkthrough of image classification using the Digits dataset from scikit‑learn.
The full analysis myself, learning step‑by‑step how Random Forest and SVM models work for classifying small 8×8 pixel handwritten digit images.

I kept everything simple and beginner‑friendly so anyone can follow along, even if you're new to machine learning.

📘 What I Did
Here’s the basic flow of what I learned and implemented:

Loaded the digits dataset

Normalized the pixel values

Trained a Random Forest model

Used GridSearchCV to tune the hyperparameters

Evaluated the model using accuracy, precision, recall, and F1

Visualized:

Confusion matrices

Feature importances

Heatmaps

Sample digit images

Wrote a function to predict new images

Bonus: Trained an SVM (RBF kernel) model and compared it to Random Forest

Everything is inside the notebook so you can run it and see the results yourself.



🚀 How to Run the Notebook
Option 1 — Google Colab (Easiest)
You can upload the notebook to Colab and run it right away.
Colab already has all the libraries installed.

🧠 Model Results 
Random Forest
Grid Search found the best settings:

Code
max_depth: 10
min_samples_leaf: 1
min_samples_split: 2
n_estimators: 100
Performance:

Metric	Score
Accuracy	0.9611
F1‑Score	0.9609


SVM (Bonus)
Performance:

Metric	Score
Accuracy	0.9917
F1‑Score	0.9916


SVM beat Random Forest in both accuracy and F1‑score.

📊 Visuals Included
The notebook shows:

Confusion matrices

Feature importance charts

Pixel heatmaps

Sample digit images

Predictions on new test images

🔮 Predicting New Images
I wrote a simple function:

python
predict_new_image(image, model=best_model)
It gives you:

The predicted digit

The probability scores

A confidence value

📝 Credit
All analysis, coding, and explanations were done by Crystal MacNeil  
as part of learning machine learning and image classification.

📜 License
MIT License — feel free to use or modify this project.
