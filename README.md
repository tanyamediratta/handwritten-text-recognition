# Handwritten Character Recognition using EMNIST

## Project Overview

This project presents a comparative study of multiple Machine Learning and Deep Learning models for handwritten character recognition using the EMNIST (Extended MNIST) dataset.

The objective was to evaluate how classical machine learning algorithms perform in comparison to a Convolutional Neural Network (CNN) on image classification tasks. The project also analyzes the impact of hyperparameter tuning on overall model performance.

---

## Models Implemented

The following models were implemented and evaluated:

- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Logistic Regression
- Decision Tree
- Convolutional Neural Network (CNN)

---

## Dataset

- Dataset: EMNIST (Extended MNIST)
- Contains handwritten digits and characters
- Image size: 28 × 28 grayscale
- Multi-class classification problem

---

## Methodology

1. Data preprocessing (normalization and reshaping)
2. Train-test split
3. Model training
4. Hyperparameter tuning:
   - K value for KNN
   - C parameter for SVM
   - Maximum depth for Decision Tree
   - Epochs and Dropout for CNN
5. Performance evaluation using:
   - Accuracy
   - Precision
   - Recall
   - F1-Score
   - Confusion Matrix

---

## Results and Observations

- Classical machine learning models provide reasonable performance on image classification tasks.
- CNN achieves superior results due to its ability to capture spatial and hierarchical features from image data.
- Hyperparameter tuning improves performance across all models.
- Deep learning models are better suited for high-dimensional image datasets.

(Performance metrics can be added here if required.)

---

## Tech Stack

- Python
- NumPy
- Pandas
- Scikit-learn
- TensorFlow / Keras
- Matplotlib

---

## Project Structure

handwritten-text-recognition/
│
├── ELC_Handwritten_Digit_Recognition.ipynb
├── handwritten_text_recognition.ipynb
├── README.md

---

## Key Learnings

- Feature representation plays a critical role in traditional ML algorithms.
- CNNs automatically learn spatial features, improving classification performance.
- Model selection should depend on the type and dimensionality of data.
- Proper experimentation and tuning significantly impact results.

---

## Future Improvements

- Refactor notebook into modular Python scripts
- Add structured training pipeline
- Deploy as a web application
- Implement transfer learning approaches

---

## Author

Tanya Mediratta  
