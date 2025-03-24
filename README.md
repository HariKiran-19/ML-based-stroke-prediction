# ML-Based Stroke Prediction

## Overview
This project implements a machine learning model to predict the likelihood of heart disease in patients using logistic regression. The dataset used for this model is "heart.disease.csv," which contains various medical attributes related to heart conditions.

## Dataset
The dataset consists of multiple features such as age, gender, blood pressure, cholesterol levels, and other relevant health indicators. The target variable represents whether a patient has heart disease (1) or not (0).

## Dependencies
Ensure you have the following Python libraries installed before running the code:
- numpy
- pandas
- scikit-learn

Install them using:
```bash
pip install numpy pandas scikit-learn
```

## Code Explanation
1. **Import Libraries:** The required libraries are imported, including NumPy, Pandas, and scikit-learn for data processing and modeling.
2. **Load Data:** The dataset is loaded into a Pandas DataFrame.
3. **Data Exploration:** Basic exploratory data analysis (EDA) is performed using `.head()`, `.info()`, `.describe()`, and `.value_counts()`.
4. **Preprocessing:**
   - Missing values are checked.
   - Features (X) and target variable (Y) are separated.
5. **Splitting Data:** The dataset is split into training and testing sets using `train_test_split()`.
6. **Model Training:** A logistic regression model is trained using `LogisticRegression().fit()`.
7. **Model Evaluation:** Accuracy scores are calculated for both training and testing datasets.
8. **Making Predictions:** The model predicts whether a new patient (with given input data) is likely to have heart disease.

## Running the Model
To test the model, update the `input_data` variable with patient details and run the script. Based on the model’s prediction, it will print:
- "Good News the patient doesn't have any heart disease"
- "The patient should visit the doctor"

## Usage
Clone the repository and run the script:
```bash
git clone https://github.com/Harikiran-19/ML-based-stroke-prediction.git
cd ML-based-stroke-prediction
python stroke_prediction.py
```

## Future Improvements
- Implement additional machine learning models for better accuracy.
- Use feature scaling and hyperparameter tuning.
- Deploy the model as a web application for real-time predictions.

## License
This project is open-source and available under the MIT License.

