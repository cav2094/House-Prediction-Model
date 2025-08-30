# House-Prediction-Model Predicting Madrid Real Estate Prices Using Linear Regression

This project predicts Madrid house prices by building a linear regression model from scratch and comparing it to the industry-standard scikit-learn implementation. Using the property's size (sq_mt_built) to predict its buy_price, we explore two training methods—Grid Search and Random Search—to understand the fundamentals before validating against a professionally optimized solution.

# Setup
To set up your python environment to run the code in this repository, follow the instructions below.

1. Create (and activate) a new environment.

- __Linux__ or __Mac__: 
	```bash
	conda create --name House-Predictor
	conda activate House-Predictor
	conda env config vars list
	```

2. Clone the repository (if you haven't already!), and navigate to the folder.  Then, install several dependencies.
	```bash
	gh repo clone cav2094/House-Prediction-Model
	cd House-Predictor
	```
3. Install required packages:
- __Linux__ or __Mac__: 
	```bash
  conda install anaconda::pandas
  conda install numpy
  conda install anaconda::scipy
  conda install anaconda::scikit-learn
  conda install conda-forge::matplotlib
  conda install anaconda::seaborn

	```



