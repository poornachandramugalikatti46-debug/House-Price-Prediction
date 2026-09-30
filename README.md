# 🏠 House Price Prediction using Linear Regression

A beginner-friendly Machine Learning project that predicts house prices based on **area, number of bedrooms, number of bathrooms, and house age** using **Linear Regression**.

## 📌 Project Overview

The goal of this project is to understand the complete Machine Learning workflow:

```text
House Dataset
      ↓
Data Loading
      ↓
Feature Selection
      ↓
Train/Test Split
      ↓
Linear Regression
      ↓
Model Training
      ↓
Prediction
      ↓
Model Evaluation
```

The model takes the following information about a house:

* Area (sq. ft.)
* Number of Bedrooms
* Number of Bathrooms
* Age of the House

and predicts the estimated house price.

---

## 🎯 Project Goal

### Input

```text
Area
Bedrooms
Bathrooms
Age
```

### Output

```text
Predicted House Price
```

Example:

```text
Area       = 1200 sq.ft
Bedrooms   = 2
Bathrooms  = 2
Age        = 5 years

Predicted Price ≈ ₹36.78 Lakhs
```

---

## 🤖 Machine Learning Algorithm

### Linear Regression

Linear Regression is a supervised Machine Learning algorithm used to predict a continuous numerical value.

In this project:

```text
Features → House information
Target   → House Price
```

The model learns the relationship between the house features and its price from the training data.

---

## 📊 Dataset

The project uses a custom beginner-friendly dataset containing house information.

### Features

| Feature   | Description               |
| --------- | ------------------------- |
| Area      | House area in square feet |
| Bedrooms  | Number of bedrooms        |
| Bathrooms | Number of bathrooms       |
| Age       | Age of the house in years |

### Target

| Target | Description |
| ------ | ----------- |
| Price  | House price |

The dataset is included in:

```text
data/house_data.csv
```

> **Note:** The dataset is created for learning and demonstration purposes. It is not intended to represent real-world property market prices.

---

## 🗂️ Project Structure

```text
HOUSE PRICE PREDICTION/
│
├── data/
│   └── house_data.csv
│
├── train.py
├── predict.py
├── requirements.txt
└── README.md
```

### File Description

**`data/house_data.csv`**

Contains the house dataset used for training and prediction.

**`train.py`**

Loads the dataset, trains the Linear Regression model, and evaluates the model.

**`predict.py`**

Uses the trained Linear Regression logic to predict the price of a new house.

**`requirements.txt`**

Contains the Python libraries required to run the project.

---

## 🛠️ Technologies Used

* Python
* Pandas
* Scikit-learn
* Linear Regression
* Git & GitHub

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone <YOUR-GITHUB-REPOSITORY-URL>
```

### 2. Open the project

```bash
cd HOUSE-PRICE-PREDICTION
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

If `pip` does not work:

```bash
python -m pip install -r requirements.txt
```

---

## ▶️ How to Run

### Train the model

Run:

```bash
python train.py
```

Example output:

```text
MSE: 24008143578.87034
R2 Score: 0.9952850092394511
```

### Make a prediction

Run:

```bash
python predict.py
```

Example output:

```text
Predicted House Price: 3677644.456286446
```

Approximately:

```text
₹36.78 Lakhs
```

---

## 📈 Model Evaluation

The model is evaluated using:

### Mean Squared Error (MSE)

MSE measures the average squared difference between the actual and predicted values.

```text
Lower MSE → Smaller prediction errors
```

The project achieved:

```text
MSE = 24,008,143,578.87
```

### R² Score

R² measures how well the model explains the variation in the target value.

The project achieved:

```text
R² Score = 0.9953
```

or approximately:

```text
99.53%
```

> Because this project uses a small synthetic dataset created for learning, the high R² score should not be interpreted as real-world housing-market accuracy.

---

## 🧠 What I Learned

Through this project, I learned the basic Machine Learning workflow:

* Loading datasets using Pandas
* Selecting features and target variables
* Splitting data into training and testing sets
* Creating a Linear Regression model
* Training a Machine Learning model
* Making predictions
* Evaluating a model using MSE
* Evaluating a model using R² Score
* Organizing a Machine Learning project
* Running an ML project from the command line

---

## 🔮 Future Improvements

I plan to improve this project by adding:

* [ ] Larger real-world housing dataset
* [ ] Data cleaning and preprocessing
* [ ] Exploratory Data Analysis (EDA)
* [ ] Data visualization
* [ ] Feature scaling where appropriate
* [ ] More Machine Learning algorithms
* [ ] Model comparison
* [ ] Save the trained model using Joblib
* [ ] FastAPI backend
* [ ] Frontend interface
* [ ] Cloud deployment

Future application architecture:

```text
Frontend
    ↓
FastAPI
    ↓
ML Model
    ↓
Prediction
    ↓
Frontend
```

---

## 👨‍💻 Author

**Poornachandra P. Mugalikatti**

BCA Student | Python Developer | Backend Developer | Machine Learning Enthusiast

### Skills Used

```text
Python
Pandas
Scikit-learn
Machine Learning
Linear Regression
Git
GitHub
```

---

## ⭐ Project Status

**Status:** Completed — Beginner Machine Learning Project

This project is part of my journey from **Machine Learning fundamentals to real-world AI applications**.

If you found this project useful, consider giving the repository a ⭐.
