# ML_Project 
(R version 3.6.3 (2020-02-29))

Building of best regression model given training set, to predict pleasantness grades given by people exposed to a particular sent.

Our repertory includes:  
- the folder **src** containing 5 others folders:
  - **Exploration**
  - **linear models**: Lasso cross-validation
  - **non-linear models**: 2 files: 
      - Neural Networks
      - Boosting (also tree, randomForest)
  - **Variance of models**: Comparison of the different best models after individual tunning in the previous files. 
  - **Submissions**: code of the kaggle submissions 
- **Report**

We used our own test sets to compare models and estimate the RMSE, but submissions have been made using the full data set.

The results are reproducible as seeds have been used throughout the code.
We implemented the code on Jupyter notebooks and the version of R is 3.6.3.

Before running the code, pay attention to the path for the download of the data. The data folder should be located at the same level as src.  

