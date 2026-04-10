Demand Forecasting using Machine Learning

Overview
This project focuses on predicting product demand based on key business factors such as price, discount, inventory level, promotion, competitor pricing, and product category. It applies machine learning techniques to analyze historical data and generate accurate demand predictions.

Tech Stack
Python  
Pandas, NumPy  
Matplotlib, Seaborn  
Scikit-learn  
XGBoost  
Streamlit  
Pickle  

Project Structure
analysis.ipynb           - Data analysis and visualization  
machine_learning.ipynb   - Model training and evaluation  
app.py                   - Streamlit application  
demand_forecasting.csv   - Dataset  
xgboost_demand_model.pkl - Trained model  
label_encoders.pkl       - Encoders for categorical features  

Features
- Data preprocessing and feature engineering  
- Demand analysis across multiple business dimensions  
- Model training using XGBoost Regressor  
- Hyperparameter tuning using RandomizedSearchCV  
- Model evaluation using RMSE  
- Web application for real-time demand prediction  

Installation and Setup
1. Clone the repository  
git clone https://github.com/your-username/demand-forecasting.git  
cd demand-forecasting  

2. Install dependencies  
pip install -r requirements.txt  

3. Run the application  
streamlit run app.py  

How It Works
The user provides input values such as price, discount, inventory level, promotion status, competitor pricing, and category. These inputs are processed and passed to the trained model, which returns the predicted demand.

Model Details
Algorithm: XGBoost Regressor  
Optimization: RandomizedSearchCV  
Evaluation Metric: Root Mean Squared Error (RMSE)  

Contributing
Contributions are welcome. Please fork the repository and submit a pull request.

Contact
For any queries or suggestions, feel free to reach out.
