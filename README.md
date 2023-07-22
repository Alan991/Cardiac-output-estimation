# Cardiac-output-estimation
This repository includes the files in the paper titled: "Machine learning algorithm to estimate cardiac output based on non-invasive arterial blood pressure measurements."
This research applied the SINDy algorithm to discover features that relate arterial blood pressure to cardiac output. The optimum number of cardiac cycles needed to extract features was also examined.

This study uses two datasets to train, test, and validate the learned model: Vitaldb and MIMIC. Using these two datasets, six regression models were trained: linear, lasso, ridge, decision tree, random forest, and XGBoost. Our best-performing model was ridge regression.

The repository uses several folders, data, figures, and code. You can find the raw data from both datasets and feature matrics in the data folder. All figures used in this study can be found in the figures folder. Finally, all codes used throughout this project can be found in the code folder. 
