Time Series Analysis in the Presence of Noise and Missing Data. Focus on Water Quality System

## Background

This directory contains classification models and data processing code for anomaly detection in water quality data set.
For complete background, see our paper pdf in the directory [thesis](https://github.com/FitoreMuharremi/master-thesis-project/tree/master/thesis).

## Code Directories

[classifiers/](https://github.com/FitoreMuharremi/master-thesis-project/tree/master/classifiers)

- Contains: 
  - jupyter notebooks:
    - Build the models(the selected ones as best performers in their class)
    - Test on our testing set(same configuration as training set)
    - Hyperparameter optimisation using GridSearch CV
    
    
[final_classifiers/](https://github.com/FitoreMuharremi/master-thesis-project/tree/master/final_classifiers)
- Contains: 
  - jupyter notebooks:
    - The selected classifiers after parameter tuning
   

[preprocessing/](https://github.com/FitoreMuharremi/master-thesis-project/tree/master/preprocessing)
  - Contains:
    - jupyter notebooks:
      - Missing values imputation
      - Stationarity tests
      - Smothing data- moving average filter
      - Low-pass filters
      - Plot different diagrams shown on the paper
      
 
## Walkthrough

 ### Install Required Packages
 
 - Pandas([instructions](http://pandas.pydata.org/pandas-docs/stable/install.html))
 - NumPy([instructions](https://docs.scipy.org/doc/numpy/user/install.html))
 - Scikit-learn([instructions](http://scikit-learn.org/stable/install.html))
 - GeoPy([instructions](https://github.com/geopy/geopy#installation))
 - SciPy([instructions](https://www.scipy.org/install.html))
 
