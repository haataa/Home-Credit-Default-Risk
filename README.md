#### Table of Contents

1. [Installation](#Installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)


# Installation<a name="Installation"></a>
libraries needed by this project are provided by the Anaconda distribution of Python. he code should run with no 
issues using Python versions 3.*.

# Project Motivation<a name="motivation"></a>
In this project, I look into home credit default data and try to build a model that predict the likelihood of each applicant repaying a loan .
Features are generated both manually and automaticly.
LightGBM is used to predict likelihood.

# File Descriptions<a name="files"></a>
data file folder contain original data from kaggle competition
EDA notebook contain all steps of data EDA and cleaning process.
Features_Models notebook contain all steps of building the model

# Result<a name="results"></a>
The final model gives local cv 0.77954 and 0.78205 on test data

The full findings of the code can be found at the post available [here](https://medium.com/@haataa/how-we-can-predict-credit-default-risk-by-machine-learning-algorithm-33e0b056ab47?postPublishedType=initial).

# Licensing, Authors, Acknowledgements<a name="licensing"></a>
Data Source can be acquired from [Kaggle](https://www.kaggle.com/c/home-credit-default-risk/data)
