# ✈️ Airline Customer Satisfaction Prediction

## 📌 Project Overview

This project predicts whether an airline passenger is **satisfied or dissatisfied** based on their travel experience and service-related information.

The project uses **Machine Learning** to analyze customer information and build a predictive model that can classify passenger satisfaction.

## 🎯 Objective

The main objective of this project is to:

* Analyze airline customer satisfaction data
* Perform data preprocessing and exploratory data analysis
* Train a Machine Learning classification model
* Predict customer satisfaction
* Deploy the prediction model using a Python application

## 📊 Dataset

The dataset contains information about airline passengers and their experiences, including factors related to:

* Customer type
* Age
* Type of travel
* Class
* Flight distance
* In-flight services
* Online booking experience
* Seat comfort
* Food and drink
* Cleanliness
* Departure and arrival delays
* Other airline service features

The target variable is **Customer Satisfaction**.

## 🤖 Machine Learning Model

A **Logistic Regression** classification model is used to predict customer satisfaction.

The trained model is saved as:

```text
logistics_regression.pkl
```

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook
* Streamlit / Python application
* Git & GitHub

## 📁 Project Structure

```text
Airline_Project/
│
├── Airline Satisfaction Data.csv
├── Airline_Satisfaction_prediction.ipynb
├── app.py
├── logistics_regression.pkl
├── requirements.txt
├── README.md
└── .gitignore
```

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/jyoshnapriyanka/Airline-Customer-Satisfaction-Prediction-.git
```

Go to the project directory:

```bash
cd Airline-Customer-Satisfaction-Prediction-
```

Create and activate a virtual environment:

```bash
python -m venv .venv
```

Activate it on Windows:

```bash
.venv\Scripts\activate
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

## ▶️ How to Run

Run the application using:

```bash
python app.py
```

If the application is built with Streamlit, run:

```bash
streamlit run app.py
```

## 🔍 Project Workflow

```text
Data Collection
      ↓
Data Preprocessing
      ↓
Exploratory Data Analysis
      ↓
Feature Selection
      ↓
Train-Test Split
      ↓
Logistic Regression
      ↓
Model Evaluation
      ↓
Customer Satisfaction Prediction
```

## 📈 Results

The trained Machine Learning model can be used to predict whether an airline customer is likely to be **Satisfied** or **Dissatisfied** based on the provided input features.

## 💡 Future Improvements

* Try additional classification algorithms
* Improve model performance through hyperparameter tuning
* Add more visualizations
* Deploy the application online
* Add real-time prediction capabilities
* Compare multiple Machine Learning models

## 👩‍💻 Author

**Jyoshna Priyanka**

GitHub:
https://github.com/jyoshnapriyanka

---

⭐ If you find this project useful, feel free to star the repository!
