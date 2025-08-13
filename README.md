## 📌 Project Overview

# Image Recognition Bootcamp Project
This project was done as part of the **Build an AI That Sees** bootcamp.
  
The goal was to learn and implement **image recognition models** using deep learning techniques in Python.  
Over 5 days, we worked with three datasets to build, train, and evaluate image classification models:
- **MNIST**
- **CIFAR-10**
- **Cats vs Dogs**

The project covers:
- Image preprocessing and augmentation
- Building custom CNN models
- Using Transfer Learning (MobileNetV2)
- Model evaluation and visualization
- Making live predictions

---

## 📂 Datasets Used

| Dataset       | Description | Classes | Source |
|---------------|-------------|---------|--------|
| **MNIST**     | Handwritten digits (28x28 grayscale images) | 10 | [Keras Built-in](https://keras.io/api/datasets/mnist/) |
| **CIFAR-10**  | Small object images (32x32 RGB) | 10 | [Keras Built-in](https://keras.io/api/datasets/cifar10/) |
| **Cats vs Dogs** | Real images of cats and dogs | 2 | [Kaggle Dataset](https://www.kaggle.com/c/dogs-vs-cats) |

---

## 📊 Model Accuracies

| Dataset       | Model Type | Accuracy |
|---------------|-----------|----------|
| **MNIST**     | Custom CNN | **98.87%** |
| **CIFAR-10**  | Custom CNN | **73.18%** |
| **Cats vs Dogs** | Transfer Learning (MobileNetV2) | **79.05%** |

---

## 🛠️ Tech Stack & Libraries

- **Programming Language:** Python
- **Deep Learning Framework:** TensorFlow / Keras
- **Other Libraries:** NumPy, Matplotlib, scikit-learn, OpenCV
- **Environment:** Google Colab (GPU enabled)
- **Dataset Source:** Keras Datasets & Kaggle

---

## 📜 Features Implemented
- ✅ Image loading, resizing, normalization
- ✅ Data augmentation (rotation, flipping, zoom)
- ✅ CNN architecture from scratch
- ✅ Transfer Learning with MobileNetV2
- ✅ Model evaluation with accuracy, precision, recall, F1-score
- ✅ Visualization of training/validation curves
- ✅ Confusion matrix plotting
- ✅ Live predictions on uploaded images

---

## ▶️ How to Run This Project
## How to Run
1. Open the notebook in Google Colab.
2. Run all cells.
3. For Cats vs Dogs, upload your `kaggle.json` when prompted.
```bash
git clone https://github.com/kanishka-gupta1/Image-Recognition.git
