# Medical_Insurance_Cost_Prediction_ML_Project
This project predicts medical insurance costs based on demographic and health-related attributes using machine learning models. The dataset includes features such as age, gender, BMI, number of children, smoking status, and region. The project utilizes Random Forest Regressor and Linear Regression models for predictions.

## Key Features
1. **Data Preprocessing**
   - Imported necessary libraries including pandas, numpy, matplotlib, seaborn, and scikit-learn.
   - Loaded the dataset and performed initial cleaning.
   - Conducted Exploratory Data Analysis (EDA) using visualizations to understand the distribution and relationships within the data.
   - Identified and removed outliers from the "charges" column using z-scores.
2. **Feature Engineering**
   - Applied one-hot encoding to categorical variables such as gender, region, and smoking status.
   - Split the data into training and testing sets with an 80-20 split.

3. **Model Training**
   - mplemented and trained two models: Random Forest Regressor and Linear Regression.
   - The models were evaluated on the test set, with the Random Forest Regressor demonstrating superior performance.

4. **Model Evaluation**
   - The Random Forest model showed better results in terms of accuracy and handling of feature importance.

5. **Model Persistence**
   - The trained Random Forest model was saved using the `joblib` library for future predictions.
   - Demonstrated the process of loading the saved model and making predictions on new data.

5. **Predictions**
   - Provided an example of making predictions using the saved Random Forest model.

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

## License
This project is licensed under the MIT License.
