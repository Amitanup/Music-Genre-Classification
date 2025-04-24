# 🎶 Music Genre Classification using Machine Learning

This project explores the automatic classification of music genres using various machine learning algorithms and acoustic feature extraction techniques. The goal is to build and evaluate robust models that can accurately classify songs into genres using audio characteristics.

---

## 📁 Dataset

- **Source**: GTZAN Dataset (1,000 audio files across 10 genres)
- **Genres**: Blues, Classical, Country, Disco, Hip-Hop, Jazz, Metal, Pop, Reggae, Rock
- **Format**: WAV files, 30 seconds each, 44.1 kHz

---

## 🎧 Features Extracted

Using the **Librosa** library:
- MFCC (Mel-Frequency Cepstral Coefficients)
- Chroma Features
- Spectral Centroid
- Spectral Contrast
- Tempo and Beat Tracking
- Zero Crossing Rate
- Harmonic & Percussive Separation

---

## 🤖 Models Implemented

| Model                  | Train Accuracy | Test Accuracy |
|------------------------|----------------|----------------|
| K-Nearest Neighbors (KNN) | 99.91%         | 91.14%         |
| Decision Tree          | 68.62%         | 58.26%         |
| Support Vector Machine (SVM) | 97.94%    | 89.94%         |
| AdaBoost               | 38.95%         | 38.29%         |
| Logistic Regression    | 66.25%         | 66.42%         |
| Artificial Neural Network (ANN) | 96.08% | 82.63%         |

---

## ⚙️ Implementation Highlights

- GridSearchCV for hyperparameter tuning
- PCA for dimensionality reduction
- Standardized preprocessing using MinMaxScaler
- Data split: 80% Training / 20% Testing
- Visualization of audio waveforms, spectrograms, chroma features, and tempo

---

## 🛠 Tech Stack

- Python
- Librosa
- Scikit-learn
- TensorFlow / Keras
- Pandas / Numpy / Matplotlib / Seaborn

---

## 🌐 Web App (Optional)

A simple interactive web interface to test genre prediction by uploading music files (not included in this repo).

---

## 👨‍💻 Team

- Amit Kumar Duya  
- Tathagata Ghosh  
- Saakshi Gupta  
- Abhisekh Chatterjee  
- Kankana Bose

---



