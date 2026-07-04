# Titanic Survival Prediction using Machine Learning

## 📌 Project Overview

This project predicts whether a passenger on the Titanic survived or not using Machine Learning. The model is trained on the Titanic dataset by analyzing passenger information such as age, gender, passenger class, fare, and family details.

The project demonstrates the complete Machine Learning workflow, including data preprocessing, exploratory data analysis, model training, evaluation, hyperparameter tuning, and prediction.

---

## 🎯 Objective

To build a machine learning model that predicts passenger survival on the Titanic based on historical passenger data.

---

## 📂 Dataset

**Dataset:** Titanic Dataset

The dataset contains information about passengers such as:

- Passenger ID
- Passenger Class (Pclass)
- Name
- Gender (Sex)
- Age
- Number of Siblings/Spouses (SibSp)
- Number of Parents/Children (Parch)
- Ticket Number
- Fare
- Cabin
- Port of Embarkation (Embarked)
- Survival Status (Target Variable)

Target Variable:

- **0** → Did Not Survive
- **1** → Survived

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook / VS Code

---

## 📊 Project Workflow

1. Load the Titanic dataset
2. Perform Exploratory Data Analysis (EDA)
3. Handle missing values
4. Encode categorical variables
5. Remove unnecessary columns
6. Split the dataset into training and testing sets
7. Train multiple Machine Learning models
8. Evaluate model performance
9. Perform Hyperparameter Tuning
10. Validate using Cross Validation
11. Predict survival for new passengers
12. Save the trained model

---

## 📈 Exploratory Data Analysis

The following visualizations were created:

- Survival Count
- Survival by Gender
- Survival by Passenger Class
- Age Distribution
- Fare Distribution
- Passenger Class Distribution
- Embarkation Port Distribution
- Correlation Heatmap
- Missing Values Heatmap

---

## 🤖 Machine Learning Models Used

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

## 📊 Model Performance

| Model | Accuracy |
|--------|----------|
| Logistic Regression | **80.45%** |
| Decision Tree | **82.12%** |
| Random Forest | **81.56%** |

**Best Performing Model:** Decision Tree Classifier

---

## ⚙️ Model Evaluation

The model was evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report
- Feature Importance

---

## 🚀 Hyperparameter Tuning

GridSearchCV was used to optimize the Decision Tree model.

Cross Validation was also performed to improve the reliability of the model.

---

## 📁 Project Structure

```
Titanic Survival Prediction/
│
├── Titanic_Survival_Prediction.ipynb
├── Titanic-Dataset.csv
├── optimized_titanic_model.pkl
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run the Project

### 1. Clone the Repository

```bash
git clone <repository-link>
```

### 2. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib
```

### 3. Run the Notebook

Open the notebook using Jupyter Notebook or VS Code and execute all cells sequentially.

---

## 📌 Results

- Successfully cleaned and preprocessed the dataset.
- Trained and compared three Machine Learning models.
- Decision Tree achieved the highest accuracy of **82.12%**.
- Performed Hyperparameter Tuning using GridSearchCV.
- Evaluated the model using multiple performance metrics.
- Successfully predicted passenger survival for new input data.

---

## 🔮 Future Improvements

- Deploy the model using Flask or Streamlit.
- Perform additional Feature Engineering.
- Experiment with advanced Machine Learning models such as XGBoost or LightGBM.
- Improve model accuracy through advanced hyperparameter optimization.

---

## 👨‍💻 Author

**Krishna Rajoo**

B.Tech – CSE-Data Science
## 📜 License

This project is created for educational and internship purposes.
