# 💸 Rupiah-Check

Rupiah-Check is a Computer Vision project based on a **Convolutional Neural Network (CNN)** designed to detect Indonesian Rupiah banknotes from images.

---

## 🎯 Background

This project was created because a friend wanted to develop software that can:

1. 📷 Detect the denomination of Indonesian Rupiah from a camera or image input.
2. 🧑‍🎓 Once the banknote is detected, the system explains the historical background of the national hero featured on the banknote.

Therefore, this project is not just an image classification model, but part of an AI-based educational system.

---

## 🧠 Technologies Used

1. Deep Learning
2. Convolutional Neural Network (CNN)
3. Data Augmentation
4. Callback Optimization:

   * ReduceLROnPlateau
   * EarlyStopping
5. Frameworks:

   * Python
   * TensorFlow / Keras

---

## 🏗 How the Model Works

1. A dataset of Indonesian Rupiah banknote images was collected and processed.
2. The data was split into:

   * Training set
   * Validation set
   * Test set
3. The CNN model was trained to recognize unique visual patterns of each denomination.
4. Once the model detects a denomination, the system links it to historical information about the national hero featured on the banknote.

---

## 📊 Model Performance

* Validation Accuracy: ± 64%
* Test Prediction: Performs fairly well in recognizing denominations
* Model confidence has not yet reached 90%

Although validation accuracy is not very high, the model demonstrates reasonable generalization capability on unseen test data.

---

## 🔧 Techniques Used to Improve Performance

### 1️⃣ Data Augmentation

Used to increase dataset variability and improve model robustness against different image conditions.

### 2️⃣ ReduceLROnPlateau

Automatically reduces the learning rate when validation performance stagnates, allowing better fine-tuning.

### 3️⃣ EarlyStopping

Stops training early when the model starts to overfit.

---

## 🚀 Potential Improvements

Possible future enhancements include:

1. Increasing dataset size
2. Using transfer learning (e.g., MobileNet, EfficientNet, etc.)
3. Hyperparameter fine-tuning
4. Adding preprocessing techniques such as background removal
5. Deploying the model to mobile or web applications

---

## 💡 Project Vision

Rupiah-Check is not just a classification model, but part of an AI-powered educational system that:

1. Helps identify currency denominations
2. Educates users about Indonesian national heroes
3. Can be developed into an interactive learning application
