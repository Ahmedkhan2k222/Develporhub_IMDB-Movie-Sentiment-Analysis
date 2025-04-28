# Develporhub_IMDB-Movie-Sentiment-Analysis
# 🎬 IMDB Movie Sentiment Analysis

A sentiment classification project on IMDB movie reviews using **Python**, **Pandas**, **NumPy**, **NLTK**, **scikit-learn**, and **Logistic Regression** with TF-IDF features.

---

## 📂 Project Structure

- **sentiment_analysis.py**: Main script containing data preprocessing, modeling, and evaluation
- **IMDB dataset.csv**: Raw dataset of movie reviews and sentiments
- **README.md**: Project documentation (this file)

---

## 📝 Project Workflow

1. **Import Libraries**: pandas, numpy, re, nltk, and scikit-learn modules.
2. **Load Dataset**: Read the CSV file and sample a subset for quicker experimentation.
3. **Text Preprocessing**: Convert text to lowercase and remove non-alphabetic characters. Optional steps include tokenization, stopword removal, and stemming.
4. **Feature Extraction**: Transform cleaned text into TF-IDF vectors with a cap of 5000 features and English stopword removal.
5. **Train-Test Split**: Split data into training and testing sets (80/20 split).
6. **Model Training**: Fit a Logistic Regression model on the training data.
7. **Evaluation**: Generate a classification report and compute accuracy on the test set.

---

## 📈 Results

- The script outputs precision, recall, F1-score for each class.
- Overall accuracy is displayed for quick performance assessment.

---

