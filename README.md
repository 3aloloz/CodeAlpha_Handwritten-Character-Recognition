📌 Project Overview
This project implements a complete handwritten character recognition system using deep learning. It starts from digit/character classification (CNN) and extends to full word recognition using a CRNN (CNN + BiLSTM + CTC Loss).

---

## 🚀 Features
- EMNIST dataset preprocessing
- Image enhancement & normalization
- CNN-based character classification
- CRNN-based word recognition
- CTC loss for sequence alignment
- Greedy decoding for OCR output
- Full visualization pipeline

---

## 📊 Dataset
- EMNIST (Balanced / Letters subset)
- 28x28 grayscale handwritten characters
- Converted into word-level synthetic data for CRNN

---

## 🧪 Project Pipeline

### 1. Data Loading
- Load EMNIST dataset
- Map labels to characters

### 2. Exploratory Data Analysis (EDA)
- Class distribution visualization
- Sample images visualization
- Dataset imbalance analysis

### 3. Preprocessing
- Noise removal
- Normalization
- Thresholding enhancement
- Image resizing

### 4. CNN Model (Baseline)
- Convolutional Neural Network
- Character-level classification
- Confusion matrix evaluation

### 5. CRNN Model (Advanced OCR)
- CNN + BiLSTM architecture
- CTC Loss for sequence learning
- Word-level recognition

### 6. OCR Inference
- Greedy CTC decoding
- Image → text prediction

---

## 📈 Results
- CNN Accuracy: ~86%+
- CRNN supports word-level recognition
- Robust character sequence prediction

---

## 🛠️ Tech StackPython
TensorFlow / Keras
NumPy
Matplotlib
OpenCV
Scikit-learn

📈 Visualizations

The project includes:

Sample dataset images
Class distribution plots
CNN training accuracy & loss curves
Confusion matrix
OCR predictions visualization

<img width="1144" height="477" alt="Screenshot 2026-04-28 174412" src="https://github.com/user-attachments/assets/95eb8168-444d-4d49-9558-53a8fbbc247a" />
<img width="1083" height="678" alt="Screenshot 2026-04-28 174404" src="https://github.com/user-attachments/assets/bac090d8-b126-4c33-a465-a2c78952085d" />
<img width="1140" height="532" alt="Screenshot 2026-04-28 174353" src="https://github.com/user-attachments/assets/7c7519ba-4830-4f22-b384-d28f8989ae9d" />
<img width="722" height="331" alt="Screenshot 2026-04-28 174344" src="https://github.com/user-attachments/assets/9727f041-1056-4778-ba25-0a71cfccab4c" />
<img width="703" height="369" alt="Screenshot 2026-04-28 162303" src="https://github.com/user-attachments/assets/2601e646-0ba6-4475-a2f6-0380d4e6b1b4" />

<img width="1078" height="733" alt="Screenshot 2026-04-28 155347" src="https://github.com/user-attachments/assets/d55ddbc1-9172-482f-beeb-3c6fb875bef7" />
<img width="709" height="824" alt="MJo1Kd0" src="https://github.com/user-attachments/assets/6f1adf4c-cbc9-46b7-8b76-7d702766b917" />
<img width="1119" height="700" alt="Screenshot 2026-04-28 174429" src="https://github.com/user-attachments/assets/14a7d20e-c2ab-4f5d-9f6c-f7599e6b0acf" />
<img width="593" height="445" alt="Screenshot 2026-04-28 174417" src="https://github.com/user-attachments/assets/17b52468-767e-4409-90be-61583e4bb379" />

🔮 Future Improvements
Beam Search decoding for higher accuracy
Attention-based OCR (Transformer models)
Training on IAM dataset (real handwriting sentences)
Deployment using Streamlit / Flask
Real-time handwriting recognition UI
