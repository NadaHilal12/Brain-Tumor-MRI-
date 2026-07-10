# 🧠 Brain Tumor Classification using Deep Learning

## 📌 Project Overview
This project focuses on classifying brain tumor MRI images using Deep Learning techniques. Two different neural network architectures were implemented and compared:

- Feedforward Neural Network (FFNN)
- Convolutional Neural Network (CNN)

The project evaluates each model based on classification performance, training time, inference speed, and generalization ability.

---

## 📂 Dataset

The dataset is not included in this repository because of GitHub storage limitations.

📥 Dataset Link:
((https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset))

Dataset Structure:

```
Training/
    ├── Glioma
    ├── Meningioma
    ├── Pituitary
    └── No Tumor

Testing/
    ├── Glioma
    ├── Meningioma
    ├── Pituitary
    └── No Tumor
```

---

## 🚀 Features

- Image preprocessing and normalization
- Data loading using TensorFlow
- Dataset visualization
- Duplicate filename checking
- FFNN implementation
- CNN implementation
- Early Stopping
- Dropout Regularization
- Performance comparison
- Model evaluation using Accuracy and F1-Score
- Training and inference time analysis
- Hyperparameter optimization experiments

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Pandas
- Scikit-learn

---

## 📊 Models

### Feedforward Neural Network (FFNN)

- Flatten Layer
- Dense (512)
- Dropout (0.3)
- Dense (256)
- Dropout (0.3)
- Softmax Output

### Convolutional Neural Network (CNN)

- Conv2D
- MaxPooling
- Conv2D
- MaxPooling
- Conv2D
- MaxPooling
- Dense
- Dropout
- Softmax Output

---

## 📈 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Loss
- F1-Score
- Training Time
- Inference Speed

---

## 🧪 Optimization Experiments

Several experiments were performed to improve model performance:

- High Learning Rate
- Lower Learning Rate
- Removing Dropout
- Data Augmentation

---

## 📷 Visualizations

The project includes:

- Class Distribution
- Sample Images
- Learning Curves
- Accuracy Comparison
- Training Time Comparison
- Inference Speed Comparison

---

## ▶️ How to Run

Clone the repository

```bash
git clone https://github.com/YourUsername/Brain-Tumor-Classification.git
```

Install the required packages

```bash
pip install -r requirements.txt
```

Run the notebook or Python script.

---

## 📌 Results

The CNN model achieved better classification performance and generalization than the FFNN model. Although CNN required slightly longer training time, it produced higher accuracy and better F1-Scores on unseen test images.

---

