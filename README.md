# Skin Disease Detection using CNN and ResNet50 (Transfer Learning)

This project aims to classify skin diseases using a Convolutional Neural Network (CNN) and a pre-trained ResNet50 model through Transfer Learning. It leverages deep learning techniques to accurately identify skin conditions from medical images.

---

## 📌 Objective

To develop an image classification model that can detect and differentiate between different types of skin diseases using deep learning architectures like CNN and ResNet50.

---

## 🧠 Technologies Used

- **Python**
- **TensorFlow / Keras**
- **NumPy**
- **Pandas**
- **Matplotlib / Seaborn**
- **Google Colab**
- **ResNet50** (Pre-trained on ImageNet)

---

## 📂 Dataset

- The dataset is sourced from the **DermNet** medical image collection.
- It contains images of various skin conditions categorized into multiple classes.
- Images were resized, normalized, and augmented for better training performance.

---

## ⚙️ Project Workflow

1. **Data Loading & Preprocessing**
   - Image resizing, normalization
   - Train-test-validation split
   - Data augmentation (rotation, zoom, shift)

2. **Model Architecture**
   - Custom CNN architecture and ResNet50 (Transfer Learning)
   - Used Global Average Pooling and dense layers
   - Final softmax layer for classification

3. **Model Training**
   - Optimized using `Adam`
   - ModelCheckpoint used

4. **Evaluation**
   - Accuracy, loss, precision, recall
   - Confusion matrix 

5. **Visualization**
   - Training and validation accuracy/loss plots
   - Sample predictions with actual vs predicted labels

---

## 📈 Results

- Achieved **90% validation accuracy**
- Model generalized well due to transfer learning and data augmentation

---

## 💡 Key Features

- Uses **Transfer Learning** with ResNet50
- Robust image preprocessing and augmentation
- Visualization of predictions and model performance





