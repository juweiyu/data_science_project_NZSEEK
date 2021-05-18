![alt text](https://github.com/juweiyu/data_science_project_NZSEEK/blob/main/images/nzseek_logo.jpg)

# NZ Seek Data Visualisation

## NZ seek datasets
Our NZ seek raw datasets include newly released admin jobs, banking jobs, and CEO jobs across New Zealand. They can be found in https://github.com/juweiyu/data_science_project_NZSEEK/tree/main/data%20source/raw%20data.

The raw dataset is irregulated and imcomplete, and hence it requires data preprocessing. Cleaned datasets can be found in  https://github.com/juweiyu/data_science_project_NZSEEK/tree/main/data%20source/cleaned%20data.

## Notebooks
#### Data preprocessing
https://github.com/juweiyu/data_science_project_NZSEEK/blob/main/notebooks/01_data_cleaning.ipynb

#### Data preprocessing (using spark)
https://github.com/juweiyu/data_science_project_NZSEEK/blob/main/notebooks/02_spark_data_preprocessing.ipynb


#### Data visualisation
..

#### Regression
..


#### A reference table
https://github.com/juweiyu/data_science_project_NZSEEK/blob/main/notebooks/reference_table.xlsx

## Project highlights

![alt text](https://github.com/juweiyu/data_science_project_NZSEEK/blob/main/images/highlights.jpg)

## XGBOOST
We use the XGBoost regressor [1] to perform regression on our dataset. The result demonstrates a promising performance. 

![alt text](https://github.com/juweiyu/data_science_project_NZSEEK/blob/main/images/result_boost.png)


## Reference
[1] Chen, Tianqi, and Carlos Guestrin. "Xgboost: A scalable tree boosting system." Proceedings of the 22nd acm sigkdd international conference on knowledge discovery and data mining. 2016.

