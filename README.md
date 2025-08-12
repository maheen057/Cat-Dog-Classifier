# 🐱🐶 Cat vs Dog Image Classifier

## 📌 Abstract
This project implements a **Convolutional Neural Network (CNN)** to classify images of cats and dogs.  
The model is trained on a Kaggle dataset and achieves high accuracy in distinguishing between the two classes.  
Google Colab is used for training and evaluation, with TensorFlow/Keras as the deep learning framework.

---

## 📂 Dataset
- **Source:** [Kaggle - Cat and Dog Dataset](https://www.kaggle.com/datasets/tongpython/cat-and-dog)
- **Classes:** 2 (Cats, Dogs)
- **Format:** JPEG images
- **Preprocessing:**
  - Resized all images to `128x128`
  - Normalized pixel values to range `[0,1]`

---

## 🏗 Model Architecture
- **Type:** Convolutional Neural Network (CNN)
- **Layers:**
  1. Conv2D + ReLU + MaxPooling
  2. Conv2D + ReLU + MaxPooling
  3. Flatten
  4. Dense (Fully connected)
  5. Output layer with Sigmoid activation
    ![Training Graph](screenshots/training_graph.png)
    ![Sample Prediction](screenshots/sample_prediction.png)

- **Loss Function:** Binary Crossentropy
- **Optimizer:** Adam
- **Evaluation Metric:** Accuracy

---

## ⚙️ Steps to Run the Project

### 1️⃣ Clone the repository
```bash
git clone https://github.com/maheen057/Cat-Dog-Classifier.git
cd Cat-Dog-Classifier

where to paste ? in github readme?
