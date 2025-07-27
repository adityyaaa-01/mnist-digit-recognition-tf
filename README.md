# MNIST Digit Classification with TensorFlow 🧠

This project demonstrates the use of **TensorFlow** to classify handwritten digits from the **MNIST** dataset. It uses a simple neural network model built using the Keras API.

## 🗂️ Dataset
- **MNIST**: Contains 60,000 training images and 10,000 test images of handwritten digits (0-9).
- Loaded directly using `tf.keras.datasets.mnist`.

## 📌 What I Did
- Preprocessed the dataset (normalization and reshaping).
- Built a neural network using:
  - Flatten Layer
  - Dense Layers with ReLU & Softmax
- Compiled the model with `adam` optimizer and `sparse_categorical_crossentropy` loss.
- Trained and evaluated the model.
- Visualized predictions.

## 📚 Technologies Used
- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib

## 🚀 How to Run

```bash
pip install tensorflow matplotlib

---

**📌 Don't forget to star ⭐ the repository if you found it helpful!**
