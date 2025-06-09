# 🌾 Crop Production Recommendation using Machine Learning

This project predicts whether a crop season is **recommended** or **not recommended** based on historical production data using Natural Language Processing and various ML models.

## 📁 Dataset
- `crop_production.csv`: Contains production data for crops and their seasons.
- `Labeled_Data.csv`: Auto-generated file after applying label logic (recommended or not).

## 🧠 Models Used
- Naive Bayes
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest

Each model is trained on transformed crop season data using `CountVectorizer`.

## 📝 Output
Accuracy scores and classification reports for each model are printed in the terminal.

## 📦 How to Run
1. Clone the repository
2. Run:
   ```bash
   python model_train.py
