
# 📢 Speech Emotion Recognition (SER) using Hybrid Datasets and Neural Networks

## 🎯 Project Objective

This project aims to develop a **robust Speech Emotion Recognition (SER)** system that classifies speech into five emotional states:  
**Happiness**, **Sadness**, **Fear**, **Anger**, and **Neutral**.

We compare **classical machine learning models** with **deep learning architectures** using both clean (studio-recorded) and noisy (real-world) audio.

---

## 🧠 Models Used

### 🛠 Classical Machine Learning
- Random Forest 🌲
- Support Vector Machine (SVM) 📈
- K-Nearest Neighbors (KNN) 📍
- XGBoost ⚡

### 🤖 Deep Learning
- 2D Deep Convolutional Neural Network (DCNN) 🧩
- Long Short-Term Memory (LSTM) 🧠
- Simple Neural Network (SNN) 🔧

---

## 📊 Performance Summary

| Model        | Type            | Test Accuracy |
|--------------|-----------------|----------------|
| DCNN         | Deep Learning   | 84.18%         |
| LSTM         | Deep Learning   | 81.09%         |
| SNN          | Deep Learning   | 70.83%         |
| Random Forest| Classical ML    | 76.11%         |
| SVM          | Classical ML    | 71.00%         |
| XGBoost      | Classical ML    | 66.00%         |
| KNN          | Classical ML    | 60.81%         |

---

## 📁 Dataset

We used a **hybrid dataset** consisting of:
- **RAVDESS**
- **TESS**
- **CREMA-D**
- **YouTube-scraped real-world audio samples**

All files were standardized into `.wav` format.

---

## ⚙️ Features Extracted

- **MFCCs** (Mel-Frequency Cepstral Coefficients)
- **Dynamic Pulsing Features** (custom temporal intensity features)
- **Mel Spectrograms** for CNN models

---

## 🧪 Evaluation Metrics

- **Accuracy**
- **Precision, Recall, F1-score**
- **Confusion Matrix**
- **Bar Charts** for class-wise performance

---

## 📚 How to Run

1. Clone the repo  
   ```bash
   git clone https://github.com/your-username/speech-emotion-recognition.git
   cd speech-emotion-recognition
   ```

2. Install required libraries  
   ```bash
   pip install -r requirements.txt
   ```

3. Prepare the dataset  
   - Place the `.wav` files in the `data/` folder.
   - Run `preprocessing.py` to extract features.

4. Train models  
   ```bash
   python train_classical.py
   python train_dnn.py
   ```

5. Evaluate models  
   ```bash
   python evaluate.py
   ```

---

## 👩‍💻 Team Members

- **Habiba Ragaey**  
- **Sara Talaat**  
- **Haneen Abdelkader**  
- **Engy Saleh**  
- **Ameena Gamaleldeen**

---

## 📜 License

This project is for academic use only.
