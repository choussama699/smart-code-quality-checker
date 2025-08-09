# Code Smell Detection Using Deep Learning

## 📌 Overview
This project was developed as my **Graduation Project** in Software Engineering.  
The main objective is to **detect code smells** in software codebases using **deep learning techniques** applied to code embeddings.

I adapted popular **Convolutional Neural Network (CNN)** architectures — **LeNet**, **AlexNet**, and **Inception** — to work with **1D input** derived from code embeddings, enabling effective classification of code smells.

---

## 🎯 Objectives
- Build a predictive model for **automatic code smell detection**.
- Compare different CNN architectures adapted for **1D sequences**.
- Evaluate the performance using a **real-world dataset** of code smells.
- Contribute to improving **code quality** and **software maintainability**.

---

## 🗂 Dataset
- **Name:** MLCQ Dataset for Code Smells  
- **Content:** Contains labeled code fragments representing different types of smells Feature Envy and Data Class
- **Preprocessing:**  
  - Tokenization of source code.
  - Conversion to embeddings (numeric representation).
  - Normalization for deep learning models.

---

## 🏗 Methodology
1. **Data Preprocessing**
   - Load and clean dataset.
   - Generate code embeddings.
   - Split into training, validation, and testing sets.

2. **Model Architectures**
   - **LeNet** (adapted for 1D input).
   - **AlexNet** (adapted for 1D input).
   - **Inception** (adapted for 1D input).

3. **Training**
   - Optimizer: Adam
   - Loss Function: Categorical Crossentropy
   - Evaluation Metrics: Accuracy, Loss, Precision, Recall, F1-score.

4. **Evaluation**
   - Comparison of architectures.
   - Visualization of results (confusion matrix, performance graphs).

---

## 📊 Results
| Model     | Accuracy | Loss | 
|-----------|----------|-----------|
| LeNet     | 47 %    | 20 %     | 
| AlexNet   | 91 %    | 17 %     | 
| Inception | 97 %    | 7 %     | 


---

## 💻 Technologies Used
- **Python**
- **TensorFlow / Keras**
- **NumPy, Pandas, Matplotlib**
- **Scikit-learn**
- **Jupyter Notebook**

---

## 📂 Project Structure
