# House-Prediction-Model Predicting Madrid Real Estate Prices Using Linear Regression

This project builds a Linear Regression model using scikit-learn to predict house prices in Madrid. It utilizes the houses_Madrid.csv dataset, incorporating features like property size (sq_mt_built), number of rooms and bathrooms, neighborhood, house type, and various amenities.

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
  conda install -c conda-forge statsmodels

	```



