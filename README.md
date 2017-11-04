# Model Evaluation and Validation

## Project: Predicting Boston Housing Prices

### see https://m00nd00r.github.io/Boston-Housing/ for project info

## Install

This project requires **Python 2** and uses the Anaconda Python distribution.
If you haven't already please download and install Anaconda.

Instructions:
1. Clone the repository and navigate to the downloaded folder.
	
	```	
		git clone https://github.com/m00nd00r/Boston-Housing.git
		cd Boston-Housing
	```
    
2. Obtain the necessary Python packages and activate the working environment.  
	
	For __Mac/OSX/Linux__:
	```
		conda env create -f requirements/housing-osx.yml
		source activate housing
	```

	For __Windows__:
	```
		conda env create -f requirements/housing-windows.yml
		activate housing
	```

### Code

Code to run is in the `boston_housing.ipynb` notebook file. Additional supporting code can be found in `visuals.py`.

### Run

In a terminal or command window, navigate to the top-level project directory `boston_housing/` (that contains this README) and run the following command:

```
jupyter notebook boston_housing.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

### Data

The modified Boston housing dataset consists of 489 data points, with each datapoint having 4 features can be found in the `housing.csv` dataset file. This dataset is a modified version of the Boston Housing dataset maintained as one of [Sci-Kit Learn's](http://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_boston.html) datasets.

**Features**
1.  `RM`: average number of rooms per dwelling
2. `LSTAT`: percentage of population considered lower status
3. `PTRATIO`: pupil-student ratio by town

**Target Variable**

4. `MEDV`: median value of owner-occupied homes
