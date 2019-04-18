# hyperparameter-db-project-db15
hyperparameter-db-project-db15 created by GitHub Classroom
Project: Hyperparameter optimization
Abstract: Hyperparameter tuning is choosing a set of optimal hyperparameters for a learning algorithm.  Hyperparameter tuning is critical for building accurate models, yet most researchers use personal experience to specify their range.
There are two different methods for optimizing hyperparameters:
Grid Search
Random Search
In this project, we have dealt with both.
Goal: of this project is to build the database  from thousands of public classification and regression datasets
using the Distributed Random Forest (DRF), Generalized Linear Model (GLM), Gradient Boosting
Machine (GBM) and XGBoost algorithms. This data will allow us to estimate the relative
importance of hyperparameters, appropriate hyperparameter ranges and to build predictive models
of hyperparameter values. Out of those thousands, I am only working on one Dataset-Adult.csv from kaggle.

Description of the Dataset: 
This data was extracted from the census bureau database found at
| http://www.census.gov/ftp/pub/DES/www/welcome.html
| Donor: Ronny Kohavi and Barry Becker,
|        Data Mining and Visualization
|        Silicon Graphics.
|        e-mail: ronnyk@sgi.com for questions.
| Split into train-test using MLC++ GenCVFiles (2/3, 1/3 random).
| 48842 instances, mix of continuous and discrete    (train=32561, test=16281)
| 45222 if instances with unknown values are removed (train=30162, test=15060)
| Duplicate or conflicting instances : 6
| Class probabilities for adult.all file
| Probability for the label '>50K'  : 23.93% / 24.78% (without unknowns)
| Probability for the label '<=50K' : 76.07% / 75.22% (without unknowns)
|
| References:
https://towardsdatascience.com/hyperparameter-tuning-c5619e7e6624
https://www.kaggle.com/wenruliu/adult-income-dataset/version/2?#adult.csv
https://github.com/prabhuSub/Hyperparamter-Samples/blob/master/Meta_Data_Generated/StudentPerformanceDataset/StudentPerformance_100.ipynb
https://github.com/nikbearbrown/CSYE_7245/blob/master/H2O/H2O_automl_model.ipynb
http://docs.h2o.ai/h2o/latest-stable/h2o-docs/grid-search.html
