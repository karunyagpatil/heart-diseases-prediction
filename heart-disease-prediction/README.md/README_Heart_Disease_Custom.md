
# ❤️ Heart Disease Prediction using Machine Learning

[![Made with Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)](https://www.python.org/)
[![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Logistic%20Regression-orange?logo=scikit-learn)](https://scikit-learn.org/)
[![Status](https://img.shields.io/badge/Status-Completed-brightgreen)]()

This project uses **Logistic Regression** to predict the likelihood of heart disease using patient health records from the **Framingham dataset**. The model helps in identifying at-risk individuals and supports healthcare professionals in early diagnosis.

---

## 🔧 Technologies Used

- Python 3.x
- Pandas, NumPy, Matplotlib, Seaborn
- scikit-learn
- Jupyter Notebook

---

## 📊 Features

- Logistic Regression model
- Data normalization and preprocessing
- Train-test split with accuracy evaluation
- Confusion matrix and classification report
- Visualizations using Seaborn and Matplotlib

---

## 📁 Dataset

- Dataset: `framingham.csv`  
- Features: `age`, `sex`, `cigsPerDay`, `cholesterol`, `blood pressure`, `glucose`, etc.
- Target: `TenYearCHD` (0 or 1 – heart disease risk within 10 years)

---

## 🧪 How to Run

```bash
git clone https://github.com/YOUR-USERNAME/heart-disease-prediction.git
cd heart-disease-prediction
jupyter notebook
```

Open the notebook and run all cells.

---

## 📈 Evaluation Metrics

- **Accuracy**: Measured using `accuracy_score()`
- **Confusion Matrix**
- **Classification Report**: Precision, Recall, F1-score

---

## 🔍 Sample Code Snippet

```python
from sklearn.linear_model import LogisticRegression
logreg = LogisticRegression()
logreg.fit(X_train, y_train)
y_pred = logreg.predict(X_test)
```

---

## 📸 Visual Output

- Count plot of class distribution
- Line plot of risk factor
- Heatmap of confusion matrix

*(You can upload figures from your `.docx` report here if available)*

---

## 📜 License

MIT License

---

## 👩‍💻 Author

**Karunyahanika G Patil**  
📧 [Karunyagurupatil@gmail.com](mailto:Karunyagurupatil@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/karunyahansika-guru-patil-83817627a)

---

⭐ If you found this helpful, please star the repository!
