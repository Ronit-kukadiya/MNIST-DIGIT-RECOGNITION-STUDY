# MNIST-DIGIT-RECOGNITION-STUDY

📌 **A machine learning and deep learning-based study on the MNIST dataset, implemented from scratch and compared across multiple models.** 

---

## 📌 Overview

this project used [DataSet](https://www.kaggle.com/datasets/hojjatk/mnist-dataset) provided on kaggle to make a **step-by-step study** of MNIST digit recognition using **Machine Learning (ML) and Deep Learning (DL) models.** It explores **data preprocessing, model selection, evaluation, and visualization**, leading up to a **Flask-based web app for digit prediction**.

---

## 📁 Project Structure overview

```
MNIST-DIGIT-RECOGNITION-STUDY/
│-- 0DATA_SELECTION/            # Raw dataset and conversion scripts
│-- 1EDA/                       # Exploratory Data Analysis (EDA)
│-- 2PREPROCESSING/             # Image cropping, normalization, preprocessing
│   │-- Processed_CSV/          # Preprocessed CSV datasets
│-- 3MODEL_SELECTION/           # ML & DL model implementations
│-- 4MODEL_EVALUATION/          # Model performance analysis
│-- 5ADVANCED_TRAINING/         # Cross-validation and hyperparameter tuning
│-- 6VISUALIZATION/             # Graphs, metrics, and predictions
│-- 7DEPLOYMENT/                # Flask web app for digit recognition
│-- requirements.txt            # Dependencies
│-- README.md                   # Project documentation (this file)

```

## ✨ Key Features

✅ **Raw MNIST data preprocessing (cropping & normalization)**  
✅ **Comprehensive EDA (distribution, variations, noise analysis)**  
✅ **Comparison of multiple ML and DL models**  
✅ **Cross-validation and hyperparameter tuning**  
✅ **Performance visualization: confusion matrix, ROC curve, misclassified examples**  
✅ **Flask-based digit recognition web app**  
✅ **Live digit drawing for real-time predictions**  

---

##  Installation & Setup

### 🔹 Clone the repository
```bash
git clone https://github.com/Ronit-kukadiya/MNIST-DIGIT-RECOGNITION-STUDY.git
cd MNIST-DIGIT-RECOGNITION-STUDY
```

### 🔹 Install dependencies
```bash
pip install -r requirements.txt
```

### 🔹 (Optional) Set up a virtual environment
```bash
python -m venv venv
source venv/bin/activate  # Mac/Linux
venv\Scripts\activate     # Windows
```

---

## Run the Flask Web App
To start the web application for digit recognition:  
```bash
cd 7DEPLOYMENT
python app.py
```
Then, open your browser and go to `http://127.0.0.1:8000`.

---

## 🙌 Acknowledgments

- **MNIST Dataset** (by Yann LeCun)  
- **Scikit-Learn, TensorFlow, PyTorch** for model implementation  
- **Flask** for the web app  
- **Git & GitHub LFS** for version control

---

## 📌 Final Words

This project was a **deep dive into MNIST digit recognition**, covering everything from **basic ML models** to **advanced deep learning** and **deployment**. Though there are always **ways to improve**, this study serves as **a great foundation** for anyone exploring **image classification**! 🚀  

📌 _Made with ❤️ by [Ronit Kukadiya](https://github.com/Ronit-kukadiya)_  
