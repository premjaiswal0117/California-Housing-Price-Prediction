# California Housing Price Prediction using Machine Learning

An end-to-end Machine Learning project that predicts California housing prices using the California Housing dataset. The project demonstrates the complete ML workflow, including data preprocessing, feature engineering, model training, evaluation, and inference using Scikit-learn.

---

## Features

- Exploratory Data Analysis (EDA)
- Stratified Train-Test Split
- Missing Value Imputation
- Feature Scaling
- One-Hot Encoding
- Scikit-learn Pipelines
- Random Forest Regression
- Model Persistence using Joblib
- House Price Prediction

---

## Dataset

This project uses the **California Housing Dataset**.

**Target Variable**

- `median_house_value`

**Features**

- longitude
- latitude
- housing_median_age
- total_rooms
- total_bedrooms
- population
- households
- median_income
- ocean_proximity

---

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Joblib

---

## Project Structure

```text
California-Housing-Price-Prediction/
│
├── data/
│   ├── housing.csv
│   ├── input.csv
│   └── output.csv
│
├── models/
│   └── pipeline.pkl
│
├── src/
│   └── train.py
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Machine Learning Workflow

1. Load the dataset
2. Perform data preprocessing
3. Create income categories
4. Perform stratified train-test split
5. Handle missing values
6. Encode categorical features
7. Scale numerical features
8. Build preprocessing pipeline
9. Train Random Forest Regressor
10. Save model pipeline
11. Predict house prices on new data

---

## Model Used

- Random Forest Regressor

---

## Installation

Clone the repository:

```bash
git clone https://github.com/premjaiswal0117/California-Housing-Price-Prediction.git
```

Move into the project directory:

```bash
cd California-Housing-Price-Prediction
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Run the project:

```bash
python src/train.py
```

---

## Output

The predicted house prices are saved in:

```text
data/output.csv
```

---

## Note

The trained model (`model.pkl`) is excluded from this repository because it exceeds GitHub's file size limit. Running `src/train.py` will automatically generate the model locally.

---

## Future Improvements

- Hyperparameter tuning with GridSearchCV
- XGBoost Regressor
- LightGBM
- CatBoost
- Model deployment using FastAPI
- Docker support

---

## Author

**Prem Jaiswal**

GitHub: https://github.com/premjaiswal0117