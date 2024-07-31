# Medical_Insurance_Cost_Prediction_ML_Project
This project predicts medical insurance costs based on demographic and health-related attributes using machine learning models. The dataset includes features such as age, gender, BMI, number of children, smoking status, and region. The project utilizes Random Forest Regressor and Linear Regression models for predictions.

## Key Features
1. **Data Preprocessing**
   - Handling missing values and outliers
   - Exploratory Data Analysis (EDA)
   - Encoding categorical variables

2. **Feature Engineering**
   - One-hot encoding
   - Data splitting into training and testing sets

3. **Model Training**
   - Trained using Random Forest Regressor and Linear Regression
   - Model evaluation based on R² score, MAE, and RMSE

4. **Model Persistence**
   - Saved trained models for future use

5. **Predictions**
   - Example of predictions using the saved model

## Files
- `Medical Insurance Cost Prediction.ipynb`: Jupyter Notebook with the complete workflow
- `medical_insurance.csv`: Dataset used for training and evaluation
- `trained_random_forest_model_project.joblib`: Saved Random Forest model

## How to Use
1. Clone the repository:
   ```bash
   https://github.com/shubhu111/Medical_Insurance_Cost_Prediction_ML_Project.git
   ```
2.Navigate to the project directory:
```bash
cd medical-insurance-cost-prediction
```
3. Install the required packages:
```bash
pip install -r requirements.txt
```
4. Run the Jupyter Notebook:
```bash
jupyter notebook Medical Insurance Cost Prediction.ipynb
```
5. Load the trained model and make predictions with new data as shown in the notebook.

## Conclusion
The Medical Insurance Cost Prediction project successfully developed a machine learning model to estimate insurance costs based on demographic and health factors. By analyzing the data and using Random Forest Regressor and Linear Regression models, we found that the Random Forest model provided more accurate predictions. This project demonstrates effective data preprocessing, feature engineering, and model evaluation techniques, highlighting the practical application of machine learning in predicting insurance costs.
