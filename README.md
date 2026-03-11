# Sonar Rock vs Mine Prediction

## Project Overview

This project uses Machine Learning to predict whether an object detected by sonar signals is a **Rock** or a **Mine**.
The model is trained on the **Sonar Dataset**, which contains 60 numerical features representing sonar signal frequencies.

A Logistic Regression model is used to classify the object based on these sonar readings.

---

## Dataset Information

The dataset consists of sonar signals bounced off different surfaces.

* Total Instances: **208**
* Total Features: **60**
* Target Classes:

  * **R** → Rock
  * **M** → Mine

Each feature represents the energy within a particular frequency band.

---

## Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn

---

## Machine Learning Workflow

1. Import required libraries
2. Load the dataset using Pandas
3. Perform basic data exploration
4. Separate features and labels
5. Split dataset into training and testing sets
6. Train a Logistic Regression model
7. Evaluate the model using accuracy score
8. Build a predictive system for new sonar input data

---

## Model Used

Logistic Regression

This algorithm is suitable for binary classification problems and works well with structured datasets like the Sonar dataset.

---

## Project Structure

sonar-rock-vs-mine-prediction

│
├── Rock_vs_Mine_Prediction.ipynb
├── sonar data.csv
└── README.md

---

## How to Run the Project

1. Clone the repository

git clone https://github.com/CodeBy-Divya/sonar-rock-vs-mine-prediction.git

2. Install required libraries

pip install numpy pandas scikit-learn

3. Run the Jupyter Notebook

Rock_vs_Mine_Prediction.ipynb

---

## Example Prediction

Input: Sonar frequency values
Output:

* **Rock**
  or
* **Mine**

---

## Author

Divya Singh

---

## Future Improvements

* Add feature scaling
* Implement additional ML models
* Add confusion matrix and classification report
* Build a web app using Streamlit
