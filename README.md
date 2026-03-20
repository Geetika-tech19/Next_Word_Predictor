# 🧠 Next Word Prediction using Deep Learning

## 📌 Overview
This project implements a **Next Word Prediction system** using deep learning models.  
It takes a sequence of words as input and predicts the most probable next word.

The project explores multiple RNN-based architectures and selects the best-performing model based on accuracy.

---

## 🚀 Features
- Text preprocessing and cleaning  
- Tokenization and sequence generation  
- Training multiple models (LSTM, BiLSTM, GRU)  
- Model comparison based on accuracy  
- Text generation (next word prediction)  

---

## 🧠 Models Used
- **LSTM (Long Short-Term Memory)**  
- **Bidirectional LSTM**  
- **GRU (Gated Recurrent Unit)** ✅ *Best Performing*  

> 📊 GRU achieved better accuracy and faster training compared to other models.

---

## 🛠️ Tech Stack
- Python 🐍  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  

---

## 📂 Project Workflow

1. **Data Collection**
   - Dataset loaded from Kaggle  

2. **Data Preprocessing**
   - Sentence splitting  
   - Lowercasing and cleaning  
   - Removing special characters  

3. **Tokenization**
   - Convert text into sequences  
   - Build vocabulary  

4. **Sequence Generation**
   - Create n-gram sequences  
   - Apply padding  

5. **Model Training**
   - Train LSTM, BiLSTM, GRU  
   - Compare performance  

6. **Model Selection**
   - GRU selected as best model  

7. **Prediction**
   - Generate next words based on input  

---

## 📊 Results

| Model     | Performance |
|----------|------------|
| LSTM     | Good       |
| BiLSTM   | Better     |
| GRU      | ⭐ Best     |
