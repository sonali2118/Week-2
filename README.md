# 🏪 Shop Sales Prediction

## 📌 Project Overview

Stores Sales Prediction is a Machine Learning project that predicts **Item Outlet Sales** based on product and outlet-related attributes. The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and deployment using a Flask web application.

The model is trained using the **Gradient Boosting Regressor** algorithm to accurately estimate sales for different store outlets.

---

## 📂 Project Structure

```bash
├── train.csv                 # Training dataset
├── test.csv                  # Testing dataset
├── notebook.ipynb            # Data analysis and model training notebook
├── predicted_output.csv      # Predicted sales output
├── model.pkl                 # Trained Gradient Boosting model
├── scaler.pkl                # Saved preprocessing scaler
├── app.py                    # Flask application
├── templates/
│   ├── index.html            # Input form page
│   └── prediction.html       # Prediction result page
└── README.md
```

---

## 📊 Dataset Information

### Training Dataset Columns

* Item Identifier
* Item Weight
* Item Fat Content
* Item Visibility
* Item Type
* Item MRP
* Outlet Identifier
* Outlet Establishment Year
* Outlet Size
* Outlet Location Type
* Outlet Type
* Item Outlet Sales (Target Variable)

### Testing Dataset Columns

* Item Identifier
* Item Weight
* Item Fat Content
* Item Visibility
* Item Type
* Item MRP
* Outlet Identifier
* Outlet Establishment Year
* Outlet Size
* Outlet Location Type
* Outlet Type

---

## 🔍 Project Workflow

### 1. Exploratory Data Analysis (EDA)

* Dataset inspection
* Missing value analysis
* Statistical summary
* Outlier detection

### 2. Data Visualization

* Sales distribution analysis
* Product category insights
* Outlet-wise performance analysis
* Correlation analysis

### 3. Feature Engineering

* Handling missing values
* Encoding categorical variables
* Feature transformation
* Feature selection

### 4. Model Training

* Algorithm: **Gradient Boosting Regressor**
* Train-test split
* Model evaluation
* Hyperparameter tuning

### 5. Prediction

* Generate sales predictions for test data
* Export results to `predicted_output.csv`

### 6. Model Deployment

* Save trained model using Pickle
* Build a Flask-based web application
* Predict sales through a user-friendly interface

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Flask
* Pickle

---

## 🚀 Running the Project

### Clone the Repository

```bash
git clone https://github.com/your-username/stores-sales-prediction.git
cd stores-sales-prediction
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Flask Application

```bash
python app.py
```

Open your browser and visit:

```bash
http://127.0.0.1:5000
```

---

## 📈 Model Output

The trained model predicts **Item Outlet Sales** based on the provided product and outlet information. Prediction results are displayed through the Flask web interface and can also be exported as a CSV file.


