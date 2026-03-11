# Fashion MNIST Classification

This project builds a **Machine Learning / Deep Learning model** to classify clothing images from the Fashion MNIST dataset using a **Fully Connected Neural Network (Dense Neural Network)** implemented with TensorFlow/Keras.

---

## Dataset

The **Fashion MNIST dataset** contains **70,000 grayscale images** of clothing items.

* Image size: **28 × 28 pixels**
* Total classes: **10 clothing categories**

Classes include:

* T-shirt/top
* Trouser
* Pullover
* Dress
* Coat
* Sandal
* Shirt
* Sneaker
* Bag
* Ankle boot

Dataset source: Zalando Research.

---

## Model Architecture

This project uses a **Sequential Neural Network model** built with Keras.

Model structure:

Flatten → Dense(128, ReLU) → Dense(10, Softmax)

### Layer Explanation

1. **Flatten Layer**

   * Converts the 28×28 image into a **784 feature vector**

2. **Dense Layer (128 neurons)**

   * Activation: **ReLU**
   * Learns patterns from the image features

3. **Output Layer**

   * **10 neurons**
   * Activation: **Softmax**
   * Produces probability scores for each clothing category

---

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Google Colab
