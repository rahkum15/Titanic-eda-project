# Titanic-eda-project
Exploratory Data Analysis and Machine Learning on the Titanic dataset.

# 🚢 Titanic Survival Prediction - EDA & Machine Learning

This project explores the famous Titanic dataset from Kaggle and builds a predictive model to determine whether a passenger survived or not. It includes **exploratory data analysis (EDA)**, **feature engineering**, **data cleaning**, and applying **machine learning models** such as Decision Trees and Logistic Regression.

## 📌 Project Goals

* Perform in-depth exploratory data analysis on the Titanic dataset.
* Clean and preprocess the data effectively.
* Build classification models to predict passenger survival.
* Evaluate and compare model performance.
* Visualize data for better understanding and communication.

## 🔍 Exploratory Data Analysis (EDA)

We conducted EDA using **pandas**, **matplotlib**, and **seaborn**:

* Missing value analysis
* Univariate & Bivariate analysis
* Distribution of categorical and numerical features
* Correlation heatmap
* Relationship between features (e.g., age, class, sex) and survival

### Key Findings:

* Females had a higher survival rate than males.
* Passengers in higher classes (1st class) were more likely to survive.
* Younger passengers had higher survival chances.
* Missing values were mostly in Age and Cabin columns.

## 🧹 Data Preprocessing

* Imputed missing values in `Age` using median or grouped average.
* Filled missing `Embarked` values with the most frequent port.
* Converted categorical variables (`Sex`, `Embarked`, `Pclass`) using label encoding or one-hot encoding.
* Dropped irrelevant or high-missing-value columns like `Cabin`, `Ticket`.

## 🧠 Machine Learning Models

### Models Used:

* **Logistic Regression**
* **Decision Tree Classifier**


## 📊 Visualizations

* Count plots (Survived vs Sex/Class)
* KDE plots for age distribution
* Heatmap for feature correlation
* Bar plots for categorical feature impact

## Sample View
Snapshot Review = https://github.com/rahkum15/Titanic-eda-project/blob/main/Sample%20View.png
## ✅ Results

* **Best Accuracy Achieved**: \~**X%** (replace with your score)
* Decision Trees provided interpretable results.
* Logistic Regression gave decent performance after scaling and tuning.


## ⚙️ Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

