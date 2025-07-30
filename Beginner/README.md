# 🏡 Boston House Price Prediction

This project focuses on predicting housing prices in Boston using machine learning techniques. It includes data exploration, preprocessing, model training, evaluation, and a user-friendly interface to input house features and get real-time predictions.

---

## 📑 Table of Contents

1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Features](#features)
4. [Setup and Installation](#setup-and-installation)
5. [Usage](#usage)
6. [Models Used](#models-used)
7. [Results](#results)
8. [UI Demo](#ui-demo)
9. [Contributing](#contributing)
10. [License](#license)

---

## 🔍 Project Overview

This project aims to predict the median value of owner-occupied homes in Boston suburbs. It uses the Boston housing dataset and trains regression models to estimate prices based on features like crime rate, number of rooms, property tax rate, etc.

---

## 📊 Dataset

The dataset is the classic **Boston Housing Dataset**, originally from the UCI Machine Learning Repository. It contains 506 samples and 13 features plus the target variable:

- CRIM: Per capita crime rate
- ZN: Proportion of residential land zoned for lots
- INDUS: Proportion of non-retail business acres
- CHAS: Charles River dummy variable
- NOX: Nitric oxides concentration
- RM: Average number of rooms per dwelling
- AGE: Proportion of owner-occupied units built before 1940
- DIS: Distance to employment centers
- RAD: Index of accessibility to highways
- TAX: Property-tax rate
- PTRATIO: Pupil-teacher ratio
- B: Proportion of Black population
- LSTAT: % lower status population
- MEDV (target): Median value of owner-occupied homes

---

## 🌟 Features

- Data preprocessing and normalization  
- Correlation heatmaps and visual analysis  
- Multiple regression models  
- Evaluation using RMSE and R²  
- Interactive UI using `ipywidgets` for price prediction

---

## ⚙️ Setup and Installation

Install the required libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn ipywidgets
```

Enable widgets in Jupyter if needed:

```bash
jupyter nbextension enable --py widgetsnbextension
```

For JupyterLab:

```bash
pip install jupyterlab_widgets
```

---

## ▶️ Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/boston-house-price-prediction.git
   cd boston-house-price-prediction
   ```

2. Launch Jupyter:
   ```bash
   jupyter notebook Boston_House_Price_Prediction.ipynb
   ```

3. Run all cells to:
   - Preprocess data
   - Train models
   - Launch the interactive price prediction UI

---

## 🤖 Models Used

- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  
- Gradient Boosting Regressor  

---

## 📈 Results

Evaluation metrics:

| Model                  | RMSE   | R² Score |
|------------------------|--------|----------|
| Linear Regression      | XX.XX  | XX.XX    |
| Decision Tree Regressor| XX.XX  | XX.XX    |
| Random Forest Regressor| XX.XX  | XX.XX    |
| Gradient Boosting      | XX.XX  | XX.XX    |

_Replace XX.XX with your actual results._

---

## 🖥️ UI Demo

The interactive UI allows users to input values like:

- Average rooms per house  
- Crime rate  
- Property tax  
- % lower income population  
- And more...

It outputs the predicted median house price in USD.

---

## 🤝 Contributing

Feel free to contribute by improving models, UI, or adding new features via pull requests.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).