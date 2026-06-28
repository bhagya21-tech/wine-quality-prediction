# 🍷 Wine Quality Prediction using Machine Learning

📌 Project Overview 
- 

This Project predicts whether a wine is Good or Bad based on its physicochemical properties using Machine Learning.
The Original wine quality scores are converted into a binary classification problem, where wines 
with a quality score of 7 or higher are labeled as Good (1) and those with a score below 7 are labeled as Bad (0).

The project demonstrateds a complete machine learning workflow, including data preprocessing, exploratory
data analysis (EDA), model training, model evaluation, hyperparameter tuning, and feature importance analysis. 

--- 
📂Dataset 
-

* Dataset: Wine Quality Dataset
* Source: UCI Machine Learning Repository
* File Used: winequality-red.csv

Features
-

* Fixed Acidity
* Volatile Acidity
* Citric Acid
* Residual Sugar
* Chlorides
* Free Sulfur Dioxide
* Total Sulfur Dioxide
* Density
* pH
* Sulphates
* Alcohol
* Quality

--- 

🎯 Problem Statement 
-

Predict whether aa wine is:

* Good (1): Quality >= 7
* Bad (0): Quality < 7

This transforms the original multiclass problem into a binary classification task.

---
🚀 Project  Workflow 
- 

1. Data  Loading
   
 * Loaded the Wine Quality dataset into Google Colab.
 * Imported required Python Libraries.

2. Exploratory Data Analysis (EDA)

   * Displayed dataset using head()
   * Checked dataset information using info()
   * Generated statistical summary using describe()
   * Checked dataset dimensions
   * Verified missing values
   * Analyzed feature correlations using a heatmap

3. Data Preprocessing

   * Created a new binary target column quality_label
   * selected features and target variable
   * Split the dataset into training and testing sets
  
4. Model Training

Implemented the following Machine Learning models:

  * Logistic Regression
  * K-Nearest Neighbors (KNN)
  * Decision Tree Classifier

5. Feature Scaling
   
   * Applied StandardScaler
   * Compared Logistic Regression performance before and after scaling

6. Model Evaluation

Evaluated each model using:

  * Accuracy
  * Precision
  * Recall
  * F1 Score
  * Confusion Matrix
  * Classification Report

7. Hyperparameter Tuning

Used GridSearchCV to optimize the best-performing model.

8. Feature Importance Analysis

Analyzed the most influenticsl features contributing to wine quality prediction.

---
🛠️ Technologies Used
-

* Python
* Google Colab
* Pandas
* Numpy
* Matplotlib
* Seaborn
* Scikit-learn

---

📊 Machine Learning Models

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Decision Tree Classifier

---
📈 Evaluation Metrics 
-

* Accuracy Score
* Precision
* Recall
* F1 Score
* Confusion Matrix
* Classification Report

---

📁 Project Structure
-

wine-quality-prediction/
| 
├── wine-quality-prediction.ipynb
├── README.md
├── requirements.txt
├── images/
|    ├── correlation_heatmap.png
|    ├── confusion_matix.png
|    └── feature_importance.png
|
└── dataset/
      └── winequality-red.csv 

---

▶️ How To Run
-

1. Clone the repository.
git clone https://github.com/bhagya21-tech/wine-quality-prediction.git

2. Open the notebook in Google Colab or jupyter Notebook

3. Install the required libraries.
pip install -r requirements.txt

4. run all notebook cells sequentially.


---

📌 Results 
-

* Performed complete exploratory data analysis.
* Converted wine quality into a binary classification problem.
* Compared Logistic Regression, KNN, and Decision Tree models.
* Improved model performance using feature scaling.
* Optimized the best model using GridSearchCV.
* Identified the most important features affecting wine quality.

---

👩‍💻 Author
-

Bhagyashri Raut













