Handwritten Digit Recognition using Machine Learning

This project demonstrates a complete machine learning pipeline for recognizing handwritten digits (0–9) from the *MNIST dataset*. It covers data visualization, model training, performance evaluation, and advanced analysis techniques like t-SNE, class-wise accuracy, and heatmaps.

---

# Goal

Train a machine learning model that can accurately classify images of handwritten digits.  
This is a *multi-class classification* problem.

---

# Features

- Visualize sample digits and label distribution
- Normalize and preprocess image data
- Train multiple classification models
- Analyze results using confusion matrices, heatmaps, and prediction confidence
- Dimensionality reduction with *t-SNE* for clustering visualization
- Side-by-side comparison of *Sigmoid* vs *ReLU + Softmax*
- Misclassified sample analysis

---

# Models Used

| Model                   | Description                         |
|-------------------------|-------------------------------------|
| Simple Neural Network   | 1 dense layer with sigmoid output   |
|			  |					|
| ReLU + Softmax Model    | Hidden layer with ReLU activation   |

*Best Accuracy Achieved*: ~97.8% using ReLU + Softmax

---

# Dataset

- *Source*: [MNIST by Yann LeCun](https://storage.googleapis.com/tensorflow/tf-keras-datasets/mnist.npz)
- 70,000 total images (28x28 pixels)
- 10 classes: digits from 0 to 9
- 60,000 training + 10,000 test samples

---

# Visualizations & Insights

- Digit distribution chart
- *t-SNE 2D projection* of test images
- Average image heatmaps for each digit
- Per-class accuracy chart
- Misclassified digit samples
- Confusion matrix (with normalized percentages)
- Prediction confidence bar for a single digit

---

# Real-Life Applications

-Banking & Finance: Automating cheque processing by reading handwritten digits like account numbers or amounts.
-Postal Services: Reading handwritten zip codes on letters and parcels for faster sorting and delivery.
-Form Digitization: Converting handwritten data from surveys, exams, or registration forms into digital formats for processing.

Blog URL : 
