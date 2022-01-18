****************************************** Implementation of variants of GLM Report - README file ******************************************

**Datasets: csv files**

There are currently 4 different datasets. Each having training features, training labels. These datasets are -

* A .csv for Logistic Regression
* AP.csv for Poisson Regression
* AO.csv for Ordinal Prediction
* usps.csv for Logistic Regression

All the training features datasets contain number of feature values in each line and training labels datasets contains labels corresponding to each row of features.

**Data Format:**

feature dataset ::

```
0.7867		0.7944	  	0.71628		.	0.57925 . . . . .
0.59202		0.29393		0.48599		.	0.80665 . . . . .
	.			.			.		.	.	.
	.			.			.		.	.	.
0.67256		0.76215	   0.37018		.	0.84401 . . . . .
```

label dataset ::

```
	0
	1
	1
	0
	.
	.
	1
	.
	.
```

**Code Execution Process :** 

* The entire solution is developed in jupyter notebook.
* The ipynb file is kept in a directory and there is a sub-directory called 'pp3data' which contains all the input data files.
* The jupyter notebook contains multiple functions defined to read data files, GLM algorithms defined for each process, Y-variable calculation for ordinal process etc.
* The complete program is written in Three(3) different cells with main() function at the end and other user defined functions above. Each of the 3 cells are designed for Logistic, poisson and Ordinal methods. In each of the code snippet, the main() takes the given inputs dedicated for each process and executes the process steps involved for each methods.
* All the csv input files automatically get detected in the 'pp3data' directory.

**Output:**

For each of the Logistic, poisson and Ordinal method, the below outputs will be displayed in the jupyter notebook.

	* TRAINING SET data shape
	* Mean of training errors per training set size 
	* Mean of run time per iteration per training set size
	* Mean of GLM iterations per training set size
	* Plot of Mean Error per Training Set Size
	* Plot of Runtime per iteration per training set size
	* Plot of GLM iteration per training set siz



