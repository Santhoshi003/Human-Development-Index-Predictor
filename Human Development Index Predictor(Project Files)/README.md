# 🌍 Human Development Index (HDI) Prediction System

An end-to-end Machine Learning web application that predicts the **Human Development Index (HDI)** of a country based on key socio-economic indicators using **Linear Regression** and **Flask**.

---

## 📖 Project Overview

The Human Development Index (HDI) is a composite measure developed by the United Nations Development Programme (UNDP) to assess a country's overall development. It considers three major dimensions:

- Health (Life Expectancy)
- Education (Expected & Mean Years of Schooling)
- Standard of Living (Gross National Income per Capita)

This project uses Machine Learning to predict the HDI score from these indicators and classifies the result into different Human Development categories.

---

## 🎯 Objectives

- Build an HDI prediction model using Machine Learning.
- Perform data preprocessing and exploratory data analysis.
- Train and evaluate a Linear Regression model.
- Deploy the trained model using Flask.
- Provide a user-friendly web interface for HDI prediction.

---

## 🚀 Features

- Interactive Flask web application
- Predict HDI using user inputs
- Automatic Human Development category prediction
- Clean and responsive user interface
- Model trained using Linear Regression
- Data preprocessing and visualization
- Saved model using Pickle

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

### Model Serialization

- Pickle

### Frontend

- HTML
- CSS

---

## 📂 Project Structure

```
HumanDevelopmentIndex/
│
├── Dataset/
│   ├── HDI.csv
│   └── HDI_Simplified.csv
│
├── Training/
│   └── HDI_Model.ipynb
│
├── Model/
│   └── HDI.pkl
│
├── Flask/
│   ├── app.py
│   ├── HDI.pkl
│   ├── templates/
│   │      ├── index.html
│   │      └── result.html
│   │
│   └── static/
│          ├── css/
│          └── images/
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 📊 Dataset

The project uses the **Human Development Index Dataset** containing development indicators of different countries.

Selected Features:

- Life Expectancy
- Expected Years of Schooling
- Mean Years of Schooling
- Gross National Income (GNI) Per Capita

Target:

- Human Development Index (HDI)

---

## 🔍 Exploratory Data Analysis

The following analyses were performed:

- Dataset Information
- Missing Value Analysis
- Statistical Summary
- Correlation Heatmap
- HDI Distribution
- Life Expectancy vs HDI
- Mean Years of Schooling vs HDI

---

## 🤖 Machine Learning Workflow

1. Import Libraries
2. Load Dataset
3. Data Cleaning
4. Handle Missing Values
5. Feature Selection
6. Train-Test Split
7. Train Linear Regression Model
8. Predict HDI
9. Evaluate Performance
10. Save Model
11. Deploy with Flask

---

## 📈 Model Performance

Evaluation Metrics

| Metric | Value |
|----------|---------|
| Mean Absolute Error | 0.0216 |
| Mean Squared Error | 0.00106 |
| Root Mean Squared Error | 0.0326 |
| R² Score | 0.9582 |

The model achieved approximately **95.8% prediction accuracy (R² Score)**.

---

## 🖥️ Web Application

Users enter:

- Life Expectancy
- Expected Years of Schooling
- Mean Years of Schooling
- GNI Per Capita

The application predicts:

- HDI Score
- Human Development Category

Categories:

- 🟢 Very High Human Development
- 🔵 High Human Development
- 🟠 Medium Human Development
- 🔴 Low Human Development

---

## ▶️ Installation

Clone the repository

```bash
git clone <repository-url>
```

Go to project folder

```bash
cd HumanDevelopmentIndex
```

Create Virtual Environment

```bash
python -m venv venv
```

Activate

Windows

```bash
venv\Scripts\activate
```

Install packages

```bash
pip install -r requirements.txt
```

Run Flask

```bash
cd Flask
python app.py
```

Open

```
http://127.0.0.1:5000
```

---

## 📷 Screenshots

### Home Page

(Add Screenshot)

### Prediction Result

(Add Screenshot)

---

## 📌 Future Enhancements

- Country dropdown with pre-filled values
- Multiple Machine Learning algorithms comparison
- Deep Learning implementation
- Real-time UNDP dataset integration
- Interactive dashboards
- Cloud deployment

---

## 🎓 Learning Outcomes

Through this project, we gained practical experience in:

- Data Preprocessing
- Data Visualization
- Feature Engineering
- Machine Learning
- Linear Regression
- Model Evaluation
- Flask Web Development
- Model Deployment
- End-to-End AI Application Development

---

## 👩‍💻 Author

**Anaparthi Laxmi Santhoshi**

B.Tech - Artificial Intelligence & Machine Learning

---
