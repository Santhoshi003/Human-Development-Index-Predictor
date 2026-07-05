# 🌍 Human Development Index (HDI) Prediction System

An end-to-end Machine Learning web application that predicts the **Human Development Index (HDI)** of a country based on key socio-economic indicators using **Linear Regression** and **Flask**.

---

## 📖 Project Overview

The **Human Development Index (HDI)** is a composite measure developed by the United Nations Development Programme (UNDP) to assess a country's overall development. It considers three major dimensions:

- 🩺 Health (Life Expectancy)
- 🎓 Education (Expected Years of Schooling & Mean Years of Schooling)
- 💰 Standard of Living (Gross National Income per Capita)

This project uses Machine Learning to predict the HDI score from these indicators and classifies the result into different Human Development categories through an interactive web application.

---

## 🎯 Objectives

- Build an HDI prediction model using Machine Learning.
- Perform data preprocessing and exploratory data analysis.
- Train and evaluate a Linear Regression model.
- Deploy the trained model using Flask.
- Provide a user-friendly web interface for HDI prediction.

---

## 🚀 Features

- 🌐 Interactive Flask Web Application
- 🤖 HDI Prediction using Linear Regression
- 📊 Human Development Category Prediction
- 🎨 Responsive User Interface
- 📈 Data Visualization & EDA
- 💾 Model saved using Pickle
- 🔄 Predict Again functionality

---

## 🛠️ Technology Stack

### Programming Language
- Python

### Machine Learning
- Scikit-learn
- Linear Regression

### Data Processing
- Pandas
- NumPy

### Data Visualization
- Matplotlib
- Seaborn

### Backend
- Flask

### Frontend
- HTML
- CSS

### Model Serialization
- Pickle

---

## 📂 Project Structure

```text
Human-Development-Index-Predictor
│
├── Dataset
├── Flask
├── Training
├── images
│   ├── Home.jpeg
│   └── Result.jpeg
├── README.md
└── requirements.txt
```

---

## 📊 Dataset

The project uses the **Human Development Index Dataset** containing development indicators of different countries.

### Input Features

- Life Expectancy
- Expected Years of Schooling
- Mean Years of Schooling
- Gross National Income (GNI) per Capita

### Target

- Human Development Index (HDI)

---

## 🔍 Exploratory Data Analysis

The following analyses were performed:

- Dataset Information
- Missing Value Analysis
- Statistical Summary
- Correlation Analysis
- Feature Relationships
- Data Visualization

---

## 🤖 Machine Learning Workflow

1. Import Libraries
2. Load Dataset
3. Data Cleaning
4. Handle Missing Values
5. Feature Selection
6. Train-Test Split
7. Train Linear Regression Model
8. Evaluate Model
9. Save Trained Model
10. Deploy with Flask

---

## 📈 Model Performance

| Metric | Value |
|---------|-------|
| Mean Absolute Error | 0.0216 |
| Mean Squared Error | 0.00106 |
| Root Mean Squared Error | 0.0326 |
| R² Score | 0.9582 |

The model achieved an **R² Score of approximately 95.8%**, indicating excellent prediction performance.

---

## 🖥️ Web Application

Users enter the following inputs:

- Life Expectancy
- Expected Years of Schooling
- Mean Years of Schooling
- GNI Per Capita

The application predicts:

- HDI Score
- Human Development Category

### Categories

- 🟢 Very High Human Development
- 🔵 High Human Development
- 🟠 Medium Human Development
- 🔴 Low Human Development

---

## ▶️ Installation

Clone the repository

```bash
git clone https://github.com/Santhoshi003/Human-Development-Index-Predictor.git
```

Navigate to the project folder

```bash
cd Human-Development-Index-Predictor
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the Flask application

```bash
cd Flask
python app.py
```

Open your browser

```
http://127.0.0.1:5000
```

---

## 🎥 Project Demo

**Demo Video**

https://drive.google.com/file/d/1Px5ec6hmMCRiJotMJXiRjVGpo-w2tOnM/view

---

## 📌 Future Enhancements

- Country-wise HDI comparison
- Cloud deployment
- Interactive dashboards
- Additional Machine Learning algorithms
- Real-time UNDP dataset integration
- User authentication

---

## 🎓 Learning Outcomes

Through this project, we gained practical experience in:

- Data Preprocessing
- Exploratory Data Analysis
- Data Visualization
- Machine Learning
- Linear Regression
- Model Evaluation
- Flask Web Development
- Model Deployment
- End-to-End AI Application Development

---

## 👩‍💻 Team Members

- **Anaparthi Laxmi Santhoshi**
- **Pentakota Snehitha**

---

## 📄 License

This project is developed for **educational and academic purposes only**.
