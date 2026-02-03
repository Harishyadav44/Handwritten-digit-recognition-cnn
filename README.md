# Handwritten Digit Recognition using CNN

---

## Description
This project implements a Convolutional Neural Network (CNN) to recognize handwritten digits from the MNIST dataset. The model achieves over 99% accuracy on the test set.

---

## Tech Stack
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib

---

## Dataset
MNIST handwritten digits (28x28 grayscale images)

---

## Model Architecture
- Conv2D + ReLU
- MaxPooling
- Conv2D + ReLU
- MaxPooling
- Flatten
- Dense (ReLU)
- Dense (Softmax)

---

## Results
- Test Accuracy: ~99%
- Sample predictions saved in images folder

---

## How to Run
1. Install dependencies  
pip install -r requirements.txt

2. Run the notebook
jupyter notebook

3. Open digit_recognition.ipynb and run all cells.

---

## Output
Trained model: digit_cnn_model.h5
Sample predictions image

----

## Author
Harish Kumar
