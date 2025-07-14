## 🚢 Titanic Survival Prediction — Logistic Regression Project

This project uses **machine learning** to predict passenger survival aboard the Titanic, based on various features such as age, gender, class, fare, and more. The model is trained using **logistic regression** with proper preprocessing, evaluation, and visual analysis.

---

### 📌 Project Highlights

* ✅ Built with `seaborn`’s built-in Titanic dataset (no manual CSV upload)
* 📊 Performed exploratory data analysis (EDA) with visual insights
* 🧹 Cleaned and encoded data, handled missing values
* 🤖 Trained a **Logistic Regression** model using `scikit-learn`
* 📈 Evaluated using accuracy score, confusion matrix, and classification report
* 💾 Exported the trained model using `joblib` for deployment

---

### 📁 Dataset

This project uses the Titanic dataset available via:

```python
import seaborn as sns
df = sns.load_dataset("titanic")
```

Key features used:

* `pclass` – Passenger class (1, 2, 3)
* `sex` – Gender (encoded)
* `age` – Age of passenger
* `sibsp` – Number of siblings/spouses aboard
* `parch` – Number of parents/children aboard
* `fare` – Ticket fare
* `embarked` – Port of embarkation (encoded)

---

### 🧠 Machine Learning Model

* Model: `LogisticRegression` from `sklearn`
* Scaler: `StandardScaler` applied to features
* Accuracy:

  * **Training:** \~82%
  * **Testing:** \~79%

---

### 📊 Visualizations

* Survival distribution overall and by gender/class
* Data distributions via `countplot` and `heatmap`
* Confusion matrix and classification report for performance insights

---

### 🔧 Technologies Used

* Python 3.x
* Pandas, NumPy
* Seaborn, Matplotlib
* Scikit-learn
* Google Colab
* Joblib

---

### 💾 Model Export

Trained model saved as:

```
titanic_logistic_model.pkl
```

