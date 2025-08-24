# Heart Disease Classification Project

## **Project Overview**

This is a comprehensive machine learning project aimed at building a model to predict the presence of heart disease in patients. The project follows a complete data science workflow, from initial exploratory data analysis to the training and evaluation of a robust classification model. The ultimate goal is to create a tool that can assist in early identification and risk assessment.

## **Dataset**

The analysis is based on the **Heart Disease Classification Dataset** from Kaggle. This dataset includes 14 key clinical and demographic features, which are used to predict the `target` variable (0 = no heart disease, 1 = heart disease).

### **Data Dictionary:**

* **`age`**: Age of the individual.
* **`sex`**: (1 = male, 0 = female).
* **`cp`**: Chest pain type.
* **`trestbps`**: Resting blood pressure.
* **`chol`**: Serum cholesterol.
* **`fbs`**: Fasting blood sugar > 120 mg/dl.
* **`restecg`**: Resting electrocardiographic results.
* **`thalach`**: Maximum heart rate achieved.
* **`exang`**: Exercise-induced angina.
* **`oldpeak`**: ST depression induced by exercise relative to rest.
* **`slope`**: The slope of the peak exercise ST segment.
* **`ca`**: Number of major vessels (0-3) colored by flourosopy.
* **`thal`**: Thalassemia (a blood disorder).
* **`target`**: The prediction target (1 = heart disease, 0 = no heart disease).

## **Methodology**

The project was executed through the following key stages:

1.  **Exploratory Data Analysis (EDA):** Performed initial analysis to understand the data distribution, check for missing values, and identify key relationships between features.
2.  **Data Preprocessing:** Handled categorical variables and scaled numerical features to prepare the data for modeling.
3.  **Model Selection & Training:** A variety of classification models were trained and evaluated, including:
    * `[ Logistic Regression, KNeighborsClassifier, RandomForestClassifier ]`
4.  **Model Evaluation:** Performance was rigorously evaluated using key metrics such as accuracy, precision, recall, and the F1-score to determine the most effective model.

## **Technologies Used**

* **Python 3.x**
* **pandas:** For data manipulation and analysis.
* **NumPy:** For numerical operations.
* **scikit-learn:** For machine learning algorithms and evaluation metrics.
* **Matplotlib & Seaborn:** For data visualization.
