# 🎤 Voice Biased Gender Detection using Deep Learning

## 📌 Overview

This project focuses on detecting the **gender (male/female)** from voice data using machine learning techniques. It utilizes pre-extracted audio features and applies a classification model to predict gender.

---

## 🚀 Features

* 🎧 Voice-based gender classification
* 📊 Uses preprocessed dataset (`balanced-all.csv`)
* 🧠 Machine Learning model training and testing
* 🖥️ Simple GUI interface for predictions
* ⚖️ Balanced dataset for fair evaluation

---

## 🛠️ Tech Stack

* **Python**
* **NumPy, Pandas**
* **Scikit-learn**
* **Librosa (for audio processing)**
* **TensorFlow / Keras**
* **Tkinter (GUI)**

---

## 📂 Project Structure

```
voice-gender-detection/
│
├── train.py               # Train the model
├── test.py                # Test the model
├── gui2.py                # GUI application
├── utils.py               # Helper functions
├── audio_processing.py    # Feature extraction
├── balanced-all.csv       # Dataset
├── assets/                # Images (male/female)
└── model/                 # Saved model
```

---

## ⚙️ Installation

### 1. Clone the repository

```
git clone https://github.com/ajaycharan50/voice-biased-gender-detection-by-using-deep-learning.git
cd voice-biased-gender-detection-by-using-deep-learning
```

### 2. Create virtual environment

```
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies

```
pip install numpy pandas scikit-learn librosa tensorflow soundfile tqdm matplotlib
```

---

## ▶️ Usage

### 🔹 Train the Model

```
python train.py
```

### 🔹 Test the Model

```
python test.py
```

### 🔹 Run GUI

```
python gui2.py
```

---

## 📊 Dataset

The project uses a **balanced dataset** (`balanced-all.csv`) containing extracted audio features such as:

* Mean Frequency
* Standard Deviation
* Spectral Entropy
* Skewness & Kurtosis
* Pitch-related features

---

## ⚠️ Notes

* Original project referenced `.npy` audio files which may not be available.
* This version uses **CSV-based features directly** for training.
* Ensure all files are in the correct directory before running.

---

## 🔮 Future Improvements

* 🌐 Convert to a web app using Streamlit
* 🎤 Add real-time microphone input
* 🤖 Improve model accuracy using deep learning (CNN/RNN)
* ☁️ Deploy on cloud platforms

---

## 👨‍💻 Author

* Ajay Charan (Original Project)
* Modified & improved by [Your Name]

---

## ⭐ Acknowledgements

* Open-source datasets and libraries
* Librosa for audio processing
* Scikit-learn for ML models

---
