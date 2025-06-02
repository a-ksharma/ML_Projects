# Logistic Regression Model - Binary Classification

This repository contains a simple machine learning model trained using Logistic Regression for binary classification.

## 📊 Dataset

The dataset used contains 1,000 rows of integer values with two input features and one binary output.

##⚙️ Model Details

- **Model Type:** Logistic Regression
- **Training Tool:** scikit-learn
- **Model File:** `model.pkl` (Pickle format)

## 🧪 How to Use

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/logistic-regression-model.git
    cd logistic-regression-model
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Load and use the model:
    ```python
    import pickle
    import numpy as np

    # Load model
    with open('model.pkl', 'rb') as file:
        model = pickle.load(file)

    # Sample prediction
    input_data = np.array([[45, 60]])  # input1, input2
    prediction = model.predict(input_data)
    print(f"Prediction: {prediction[0]}")
    ```

## 📂 Files

- `model.pkl` – Trained Logistic Regression model
- `requirements.txt` – Required Python packages
- `README.md` – Project overview and instructions
- `sample_ml_dataset.csv` – (Optional) Sample dataset used for training

## 📌 Notes

- The model is not deployed to a server or API.
- Ideal for offline usage or as a template for further development.