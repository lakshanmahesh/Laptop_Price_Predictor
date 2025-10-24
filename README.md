
Project Overview:

A machine learning project that predicts the price of laptops based on features such as brand, processor, RAM, graphics, and other specifications. Built using Python, pandas, scikit-learn, and Random Forest, this project demonstrates data cleaning, feature engineering, model building, and evaluation to provide accurate price predictions


Key Features:

1) Data preprocessing   
2) Feature encoding for categorical variables
3) Model selection using Random Forest,Linear Regression,Lasso,DecisionTreeRegressor

	* LinearRegression() --> 0.716168129572538
	* Lasso() --> 0.7156506868006923
	* DecisionTreeRegressor() --> 0.7173947653627537
	* RandomForestRegressor() --> 0.8048943406880643 ✅ Best Model
     
     Among the models tested, Random Forest Regressor achieved the highest accuracy (0.805), making it the   most reliable model for predicting laptop prices.
	
4) Random Forest identified as the best-performing model with highest accuracy
5) Model saved using Pickle for easy deployment and prediction (predictor.pickle)

			import pickle
			with open('predictor.pickle', 'rb') as file:
   			model = pickle.load(file)

			# Example prediction
			model.predict([[feature_values_here]])

Technologies Used:

1)Python for data analysis and modeling 

2)pandas, NumPy for data manipulation 

3)scikit-learn for machine learning and GridSearchCV 

4)Flask → Web interface for predictions

✅ Summary:

Python → main programming language
pandas → handle, clean, and analyze datasets
NumPy → numerical operations and array handling
scikit-learn → build, tune, and evaluate machine learning models
pickle → save and load trained models for deployment

<img width="868" height="627" alt="image" src="https://github.com/user-attachments/assets/fb5219b3-ddd3-4a57-b682-5fe474d75087" />


