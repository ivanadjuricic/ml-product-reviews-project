# 🧠 Sentiment Analysis ML Project

A complete machine learning pipeline for **sentiment analysis** of product reviews using Python and scikit-learn.

This project was developed as part of a learning module, covering all typical phases of a machine learning workflow — from raw data to a ready-to-use trained model.

---

## 📦 Project Structure

```
ML-PRODUCT-REVIEWS-PROJECT/
├── data/
│   └── product_reviews_full.csv      # raw dataset
├── notebook/
│   └── product_reviews_analysis.ipynb  # EDA and preprocessing
├── src/
│   ├── test_model.py                 # script for testing saved model
│   └── train_model.py               # script for training and saving the model
├── .gitignore
└── README.md
```

---

## ✅ What We Did in This Module

Through this module, we covered all major steps of a real-world ML project:

### 1. Project Setup

- Created a new GitHub repository.
- Defined project folder structure.
- Uploaded raw dataset.

### 2. Data Exploration

- Loaded and analyzed a large dataset with product reviews.
- Used `matplotlib` and `seaborn` for visualizations.
- Investigated distribution of sentiments and text characteristics.

### 3. Data Cleaning and Preprocessing

- Removed missing values.
- Standardized sentiment labels (positive / negative / neutral).
- Parsed and validated prices.
- Converted review text to numerical length.

### 4. Feature Engineering

- Selected meaningful input features: `review_title`, `review_text`, and `review_length`.
- Removed irrelevant columns.
- Explored correlation between price and sentiment.

### 5. Model Training and Evaluation

- Compared multiple ML models (Logistic Regression, Naive Bayes, Decision Tree, Random Forest, SVM).
- Used `ColumnTransformer` and `Pipeline` for unified preprocessing.
- Evaluated using precision, recall, F1-score, and confusion matrix.

### 6. Final Model Training

- Trained final model on full dataset.
- Saved the pipeline using `joblib` to `sentiment_model.pkl`.

### 7. Inference and Usage

- Loaded saved model.
- Built an interactive interface for predicting sentiment of new reviews.
- Enabled real-time testing via console input.

---

## 🚀 How to Use

### 🔧 Train the Model

```bash
cd src
python train_model.py
```

This will create a file called `sentiment_model.pkl` in the root directory.

### 🔍 Run Inference

Use the interactive script `test_model.py` to classify new reviews using the trained model.

```bash
python test_model.py
```

---

## 👷 Author

**Ivana Đuričić** — developed as part of [AI & Python Development] program course.
[GitHub](https://github.com/ivanadjuricic) · [Repository](https://github.com/ivanadjuricic/ml-product-reviews-project)

---

## 📄 License

This project is open-source and freely available for educational use.
