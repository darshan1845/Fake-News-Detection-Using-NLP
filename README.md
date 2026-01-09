# 📰 Fake News Detection Using NLP

## 📌 Project Overview
This project is a Machine Learning based Fake News Detection system built using Natural Language Processing (NLP) techniques.  
It classifies news articles as **Fake** or **Real** using TF-IDF vectorization and Logistic Regression.

---

## 🚀 Technologies Used
- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- NLTK
- Scikit-learn

---

## 📂 Dataset

Dataset used: **Fake and Real News Dataset** from Kaggle.

Due to GitHub file size limits, the dataset is not included in this repository.

Please download it manually from Kaggle:

Search on Kaggle: "Fake and Real News Dataset" by Clément Bisaillon

After downloading, place the following files in the project folder:
- Fake.csv
- True.csv


Each news article is labeled as:
- 0 → Fake News
- 1 → Real News

---

## ⚙️ Project Workflow

1. Load and merge datasets
2. Data cleaning and preprocessing using NLTK
3. Remove stopwords, symbols, URLs, etc.
4. Convert text into numerical features using **TF-IDF Vectorizer**
5. Split data into training and testing sets
6. Train model using **Logistic Regression**
7. Evaluate model performance
8. Build a custom prediction system

---

## 📊 Model Performance
- Accuracy achieved: **~95% to 99%** (depending on split)

---

## 🧪 How To Run The Project

1. Clone the repository
2. Install requirements:
3. Open Jupyter Notebook:
4. Open:
5. Run all cells

---

## 🧠 Note
This model works very well on the dataset distribution but may misclassify completely unseen or very short real-world news due to domain differences. This is a known limitation of classical ML models.

---

## 👨‍💻 Author
Darshan Patil
