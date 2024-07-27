# Data Prep for Machine Learning in Python

## Build
```bash
poetry build
poetry install
```

## Project Tree
```python
├── README.md
├── data
│   ├── processed
│   │   ├── eda
│   │   │   ├── indian_cars_dataset.csv
│   │   │   ├── phone_marketplace_dataset.csv
│   │   │   └── student_grades_eda.csv
│   │   ├── feature_engineering
│   │   │   ├── airbnb_dataset_testing.csv
│   │   │   ├── airbnb_dataset_training.csv
│   │   │   ├── basketball_stats.csv
│   │   │   ├── binning_for_target.csv
│   │   │   ├── breastcancer_dataset.csv
│   │   │   ├── cx_survey_data.csv
│   │   │   ├── cx_survey_data_test.csv
│   │   │   ├── dunk_data.csv
│   │   │   ├── dunk_data_test.csv
│   │   │   ├── kc_house_data.csv
│   │   │   ├── kc_house_data_test.csv
│   │   │   ├── phone_marketplace_dataset.csv
│   │   │   ├── stores.csv
│   │   │   ├── stores_norm_dist.csv
│   │   │   ├── stores_norm_dist_test.csv
│   │   │   └── stores_test.csv
│   │   ├── feature_selection
│   │   │   ├── indian cars dataset categorical nonulls.csv
│   │   │   ├── indian cars dataset incnulls.csv
│   │   │   └── indian cars dataset nonulls.csv
│   │   ├── import_clean_data
│   │   │   ├── phone_marketplace_dataset_cleaning_set.csv
│   │   │   ├── school report.xlsx
│   │   │   ├── student grades.csv
│   │   │   └── student grades.xlsx
│   │   └── train_test_split
│   │       ├── airbnb_dataset_testing.csv
│   │       ├── airbnb_dataset_training.csv
│   │       └── phone_marketplace_dataset.csv
│   └── raw
├── dist
│   ├── dpfml-0.1.0-py3-none-any.whl
│   └── dpfml-0.1.0.tar.gz
├── dpfml
│   ├── __init__.py
│   └── app.py
├── notebooks
│   ├── 1 Import & Clean Data
│   │   ├── Import and Clean - 1 Import & Filter Data - Student Version.ipynb
│   │   ├── Import and Clean - 1 Import & Filter Data.ipynb
│   │   ├── Import and Clean - 2 Data Validation - Student Version.ipynb
│   │   ├── Import and Clean - 2 Data Validation.ipynb
│   │   ├── Import and Clean - 3 Cleaning Data and Imputation - Student Version.ipynb
│   │   └── Import and Clean - 3 Cleaning Data and Imputation.ipynb
│   ├── 2 EDA
│   │   ├── EDA - 1 Single Variable Analysis-Student.ipynb
│   │   ├── EDA - 1 Single Variable Analysis.ipynb
│   │   ├── EDA - 2 Multiple Variable Analysis-Student.ipynb
│   │   └── EDA - 2 Multiple Variable Analysis.ipynb
│   ├── 3 Train Test Split
│   │   ├── Training & Testing - 1 - Train Test Split - Student Copy.ipynb
│   │   └── Training & Testing - 1 - Train Test Split.ipynb
│   ├── 4 Feature Engineering
│   │   ├── Feature Engineering - 1a One Hot Encoding - Student Version.ipynb
│   │   ├── Feature Engineering - 1a One Hot Encoding.ipynb
│   │   ├── Feature Engineering - 1b GetDummies Vs OneHotEncoder.ipynb
│   │   ├── Feature Engineering - 2a Transformations - Student Version.ipynb
│   │   ├── Feature Engineering - 2a Transformations.ipynb
│   │   ├── Feature Engineering - 3a Outliers - Student Version.ipynb
│   │   ├── Feature Engineering - 3a Outliers.ipynb
│   │   ├── Feature Engineering - 4a Binning - Student Version.ipynb
│   │   ├── Feature Engineering - 4a Binning.ipynb
│   │   ├── Feature Engineering - 4b Final thought on Binning.ipynb
│   │   ├── Feature Engineering - 5a Scaling - Student Version.ipynb
│   │   └── Feature Engineering - 5a Scaling.ipynb
│   └── 5 Feature Selection
│       ├── Feature Selection - 1 - Manual Methods - Student version.ipynb
│       ├── Feature Selection - 1 - Manual Methods.ipynb
│       ├── Feature Selection - 2 - Auto Methods with Continuous Target - Student Version.ipynb
│       ├── Feature Selection - 2 - Auto Methods with Continuous Target.ipynb
│       ├── Feature Selection - 3 - Auto Methods with Categorical Student Version.ipynb
│       └── Feature Selection - 3 - Auto Methods with Categorical Target.ipynb
├── poetry.lock
└── pyproject.toml
```
