# MNIST in TensorFlow

**Handwritten Digit Classification using the MNIST dataset with TensorFlow**

---

## 📦 Overview

This project demonstrates how to train a deep neural network to classify the MNIST handwritten digits dataset.  
It includes:

- Data loading (using `tf.keras.datasets`)
- Data preprocessing (normalization, reshaping)
- A **multi-layer perceptron architecture** (dense & residual-style layers)
- Training & validation
- Model serialization (saving/loading)
- Evaluation with accuracy and loss metrics
- (Optional) TensorBoard integration for visual insights

---

## ⚙️ Features

- **TensorFlow 2.x / Keras API**
- Clean model using Functional API with branching and merging
- Easy-to-follow training loop
- Support for CPU and GPU environments
- Modular structure—update model, hyperparameters, or dtype easily

---

## 🚀 Quick Start

### 1. Clone
```bash
git clone https://github.com/Legendary-Nerd/MNIST-in-TensorFlow.git
cd MNIST-in-TensorFlow
````

### 2. Setup (Recommended: Virtualenv or Conda)

```bash
pip install tensorflow numpy matplotlib
```



## 🧠 Model Architecture

* **Input**: flattened 28×28 = 784 vector
* **Dense layer** (100 neurons, ReLU)
* Two parallel Dense layers (100 neurons each)
* **Residual additions & concatenations**
* **Output layer**: 10 neurons with softmax (digits 0–9)

---

## 🎓 Tips for Improvement

* Try **Convolutional Neural Networks (CNNs)** for better spatial learning
* Add **Dropout** or **Batch Normalization** to regularize the model
* Play with:

  * Optimizers: Adam, RMSprop
  * Learning rate schedules
  * Data augmentation (e.g., rotation, translation)
* Integrate **TensorBoard**, e.g., `tensorboard --logdir logs/`

---

## 🧾 Requirements

* Python 3.7+
* [TensorFlow 2.x](https://www.tensorflow.org/install)
* NumPy
* (Optional) Matplotlib for learning curves


---

## 🔗 References & Inspiration

Many tutorials demonstrate similar approaches, such as:

* Exploring MNIST with TensorFlow to achieve \~99% accuracy ([github.com][1], [reddit.com][2], [blog.tensorflow.org][3], [gist.github.com][4], [reddit.com][5])
* Official TensorFlow Keras MNIST example
* Functional API examples in TensorFlow blog
