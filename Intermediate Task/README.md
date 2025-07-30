# 🏦 Loan Prediction Analysis and UI

This project analyzes a loan prediction dataset, builds multiple machine learning models, and provides an interactive interface for predicting loan approval status based on user input.

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

The primary goal of this project is to predict whether a loan application will be approved or rejected based on various applicant and loan attributes. The project involves data preprocessing, visualization, model building, evaluation, and deployment of an interactive user interface for real-time predictions.

---

## 📊 Dataset

The dataset used in this project is named `loan_prediction.csv`. It contains the following columns:

- **Gender**
- **Married**
- **Dependents**
- **Education**
- **Self_Employed**
- **ApplicantIncome**
- **CoapplicantIncome**
- **LoanAmount**
- **Loan_Amount_Term**
- **Credit_History**
- **Property_Area**
- **Loan_Status** (Target variable)

---

## 🌟 Features

- Data cleaning and preprocessing  
- Exploratory Data Analysis (EDA)  
- Machine learning model training (Logistic Regression, Random Forest, Decision Tree)  
- Accuracy comparison across models  
- Interactive user interface using `ipywidgets` for live predictions  

---

## ⚙️ Setup and Installation

To run this project, make sure you have Python 3 installed and run the following commands to install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn ipywidgets
```

If using Jupyter Notebook:

```bash
jupyter nbextension enable --py widgetsnbextension
```

For JupyterLab:

```bash
pip install jupyterlab_widgets
```

---

## ▶️ Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/loan-prediction-ui.git
   cd loan-prediction-ui
   ```

2. Open the notebook in Jupyter:
   ```bash
   jupyter notebook Loan_Prediction_UI.ipynb
   ```

3. Run all cells to:
   - Load and clean data
   - Visualize insights
   - Train multiple ML models
   - Launch the interactive UI for predictions

---

## 🤖 Models Used

The following classification algorithms are trained and evaluated:

- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  

Each model is compared based on accuracy and confusion matrix.

---

## 📈 Results

Model performance was evaluated using accuracy scores:

| Model                | Accuracy |
|---------------------|----------|
| KNeighbours         | 0.7967%  |
| Decision Tree       | 0.6991%  |
| Random Forest       | 0.7804%  |
| GussianNB           | 0.8292%  |

---

## 🖥️ UI Demo

The interactive UI allows users to input the following and get a prediction:

- Gender  
- Marital Status  
- Number of Dependents  
- Education  
- Employment status  
- Applicant & Co-applicant income  
- Loan amount & term  
- Credit history  
- Property area

It returns a prediction: **Loan Approved** ✅ or **Loan Rejected** ❌

---

## 🤝 Contributing

Feel free to fork this repository, raise issues, or submit pull requests to improve the model or UI!

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
