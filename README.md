# 🧠 CommentCure: Multi-Label Toxic Comment Classifier

**CommentCure** is a machine learning-powered tool that identifies and categorizes harmful online comments into six toxicity types:  
`toxic`, `severe_toxic`, `obscene`, `threat`, `insult`, and `identity_hate`.

Designed for community platforms, forums, and social media moderation, this project helps promote respectful and inclusive online discourse.

---

## 🔍 Problem Statement

Online toxicity is a growing concern that affects user experience and mental well-being. The goal of CommentCure is to automatically flag toxic comments using a multi-label classification model trained on real-world data, enabling faster moderation and safer communities.

---

## 🧠 Key Features

- Multi-label classification with six toxicity types
- TF-IDF-based text preprocessing
- Models: Logistic Regression and Naive Bayes in a One-vs-Rest setup
- Evaluation using ROC-AUC and detailed classification reports

---

## 🛠️ Tech Stack

- **Language**: Python
- **Data Processing**: pandas, NumPy
- **Text Preprocessing**: NLTK
- **Modeling**: scikit-learn
- **Visualization**: matplotlib, seaborn

---

## 📎 Dataset

This project uses the [Jigsaw Toxic Comment Classification Challenge dataset](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge), which includes over 150,000 comments labeled across multiple toxicity types.

---

## 🚀 Getting Started

1. Clone the repo
2. Install dependencies
   - It's recommended to use a virtual environment:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:
   -Start the notebook interface and run the main project file:
```bash
jupyter notebook "Toxic Comment Classification - Multi Label - NLP.ipynb"
```
4. **Commit the Changes**:
   - After pasting the new content, scroll down and click **Commit changes** to save the updated README.
---

## 📂 Project Structure

- 📁 `CommentCure/`
  - 📓 `Toxic Comment Classification - Multi Label - NLP.ipynb`
  - 📄 `train.csv`
  - 📄 `requirements.txt`
  - 📄 `README.md`
   
## 📈 Evaluation Metrics
ROC-AUC Score: Evaluates model's discriminatory ability across classes

Classification Report: Includes precision, recall, and F1-score for each label


